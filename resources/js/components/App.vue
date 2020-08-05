<template>
    <div class="flex flex-col flex-1 h-screen overflow-y-hidden">
        <Nav />

        <div class="flex overflow-y-hidden flex-1 justify-center">
            <Sidebar />
            <div class="overflow-x-hidden w-full p-0 md:w-3/4 lg:w-2/4">
                <router-view> </router-view>
            </div>
                <SuggestedBar />
        </div>
    </div>
</template>
<script>
    import Nav from './Nav';
    import Sidebar from './Sidebar';
    import SuggestedBar from './SuggestedBar'

    export default {
        name: "App",

        components: {
            Nav,
            Sidebar,
            SuggestedBar
        }
    }
</script>

<style scoped>

</style>
