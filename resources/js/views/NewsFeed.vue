<template>
    <div class="flex flex-col items-center py-4">
        <Stories />

        <NewPost />

        <Post />
    </div>
</template>

<script>
    import Stories from '../components/Stories'
    import NewPost from '../components/NewPost';
    import Post from '../components/Post';
    import SuggestedBar from "../components/SuggestedBar";

    export default {
        name: "NewsFeed",

        components: {
            SuggestedBar,
            Stories,
            NewPost,
            Post,
        },

        data: () => {
            return {
                posts: [],
            }
        },

        mounted() {
            axios.get('/fb_clone2/clone_2/api/posts')
            .then(res => {
                this.posts = res.data;
                console.log('Posts fetched')
            })
            .catch(error => {
                console.log('Unable to fetch posts: ' + error);
            });
        }


    }
</script>

<style scoped>

</style>
