<template>
    <div class="bg-gray-100 rounded shadow w-full lg:w-10/12 xl:w-4/6 mt-4 md:mt-6 overflow-hidden">
        <div class="flex flex-col pt-3 px-3 pb-0">
            <div class="flex items-center">
                <div class="w-10 h-10 rounded-full border-2 border-blue-600 flex items-center justify-center object-cover box-content">
                    <img src="https://images.pexels.com/photos/4890733/pexels-photo-4890733.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260" alt="Smiling man" class="w-8 h-8 object-cover rounded-full"></div>
                <div class="ml-2 w-full">
                    <div class="flex items-center justify-between">
                        <div class="text-sm font-bold"><a href="#" class="text-black">Joe Doe</a></div>
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 32.055 32.055" class="fill-current w-4 h-4 mr-2" >
                            <path d="M3.968,12.061C1.775,12.061,0,13.835,0,16.027c0,2.192,1.773,3.967,3.968,3.967c2.189,0,3.966-1.772,3.966-3.967
                     C7.934,13.835,6.157,12.061,3.968,12.061z M16.233,12.061c-2.188,0-3.968,1.773-3.968,3.965c0,2.192,1.778,3.967,3.968,3.967
                     s3.97-1.772,3.97-3.967C20.201,13.835,18.423,12.061,16.233,12.061z M28.09,12.061c-2.192,0-3.969,1.774-3.969,3.967
                     c0,2.19,1.774,3.965,3.969,3.965c2.188,0,3.965-1.772,3.965-3.965S30.278,12.061,28.09,12.061z" fill="#4a5568"/>
                        </svg>
                    </div>
                    <div class="text-sm text-gray-600 tracking-tight">12 mins • </div>
                </div>
            </div>
            <div>
                <div class="mt-2">
                    <p class="mb-1">Not having fun at all</p>
                </div>
            </div>
        </div>
        <div class="w-full mt-2" v-if="true">
            <img src="https://learn.zoner.com/wp-content/uploads/2018/08/landscape-photography-at-every-hour-part-ii-photographing-landscapes-in-rain-or-shine.jpg" alt="Post Image" class="w-full">
        </div>

        <div class="flex px-3 pt-3 justify-between text-gray-700 text-sm">
            <div class="flex">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" class="fill-current w-5 h-5"><path d="M20.8 15.6c.4-.5.6-1.1.6-1.7 0-.6-.3-1.1-.5-1.4.3-.7.4-1.7-.5-2.6-.7-.6-1.8-.9-3.4-.8-1.1.1-2 .3-2.1.3-.2 0-.4.1-.7.1 0-.3 0-.9.5-2.4.6-1.8.6-3.1-.1-4.1-.7-1-1.8-1-2.1-1-.3 0-.6.1-.8.4-.5.5-.4 1.5-.4 2-.4 1.5-2 5.1-3.3 6.1l-.1.1c-.4.4-.6.8-.8 1.2-.2-.1-.5-.2-.8-.2H3.7c-1 0-1.7.8-1.7 1.7v6.8c0 1 .8 1.7 1.7 1.7h2.5c.4 0 .7-.1 1-.3l1 .1c.2 0 2.8.4 5.6.3.5 0 1 .1 1.4.1.7 0 1.4-.1 1.9-.2 1.3-.3 2.2-.8 2.6-1.6.3-.6.3-1.2.3-1.6.8-.8 1-1.6.9-2.2.1-.3 0-.6-.1-.8zM3.7 20.7c-.3 0-.6-.3-.6-.6v-6.8c0-.3.3-.6.6-.6h2.5c.3 0 .6.3.6.6v6.8c0 .3-.3.6-.6.6H3.7zm16.1-5.6c-.2.2-.2.5-.1.7 0 0 .2.3.2.7 0 .5-.2 1-.8 1.4-.2.2-.3.4-.2.6 0 0 .2.6-.1 1.1-.3.5-.9.9-1.8 1.1-.8.2-1.8.2-3 .1h-.1c-2.7.1-5.4-.3-5.4-.3H8v-7.2c0-.2 0-.4-.1-.5.1-.3.3-.9.8-1.4 1.9-1.5 3.7-6.5 3.8-6.7v-.3c-.1-.5 0-1 .1-1.2.2 0 .8.1 1.2.6.4.6.4 1.6-.1 3-.7 2.1-.7 3.2-.2 3.7.3.2.6.3.9.2.3-.1.5-.1.7-.1h.1c1.3-.3 3.6-.5 4.4.3.7.6.2 1.4.1 1.5-.2.2-.1.5.1.7 0 0 .4.4.5 1 0 .3-.2.6-.5 1z"/></svg>
                <p class="pl-1">John Smith and 91 others</p>
            </div>
            <div>
                <p>27 comments</p>
            </div>
        </div>

        <div class="flex justify-between border-1 border-gray-400 mx-4 mb-2">
            <button class="flex justify-center items-center py-2 rounded-lg text-sm text-gray-700 w-full hover:bg-gray-200">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" class="fill-current w-5 h-5"><path d="M20.8 15.6c.4-.5.6-1.1.6-1.7 0-.6-.3-1.1-.5-1.4.3-.7.4-1.7-.5-2.6-.7-.6-1.8-.9-3.4-.8-1.1.1-2 .3-2.1.3-.2 0-.4.1-.7.1 0-.3 0-.9.5-2.4.6-1.8.6-3.1-.1-4.1-.7-1-1.8-1-2.1-1-.3 0-.6.1-.8.4-.5.5-.4 1.5-.4 2-.4 1.5-2 5.1-3.3 6.1l-.1.1c-.4.4-.6.8-.8 1.2-.2-.1-.5-.2-.8-.2H3.7c-1 0-1.7.8-1.7 1.7v6.8c0 1 .8 1.7 1.7 1.7h2.5c.4 0 .7-.1 1-.3l1 .1c.2 0 2.8.4 5.6.3.5 0 1 .1 1.4.1.7 0 1.4-.1 1.9-.2 1.3-.3 2.2-.8 2.6-1.6.3-.6.3-1.2.3-1.6.8-.8 1-1.6.9-2.2.1-.3 0-.6-.1-.8zM3.7 20.7c-.3 0-.6-.3-.6-.6v-6.8c0-.3.3-.6.6-.6h2.5c.3 0 .6.3.6.6v6.8c0 .3-.3.6-.6.6H3.7zm16.1-5.6c-.2.2-.2.5-.1.7 0 0 .2.3.2.7 0 .5-.2 1-.8 1.4-.2.2-.3.4-.2.6 0 0 .2.6-.1 1.1-.3.5-.9.9-1.8 1.1-.8.2-1.8.2-3 .1h-.1c-2.7.1-5.4-.3-5.4-.3H8v-7.2c0-.2 0-.4-.1-.5.1-.3.3-.9.8-1.4 1.9-1.5 3.7-6.5 3.8-6.7v-.3c-.1-.5 0-1 .1-1.2.2 0 .8.1 1.2.6.4.6.4 1.6-.1 3-.7 2.1-.7 3.2-.2 3.7.3.2.6.3.9.2.3-.1.5-.1.7-.1h.1c1.3-.3 3.6-.5 4.4.3.7.6.2 1.4.1 1.5-.2.2-.1.5.1.7 0 0 .4.4.5 1 0 .3-.2.6-.5 1z"/></svg>
                <span class="ml-2">
                    Like
                </span>
            </button>
            <button class="flex justify-center items-center py-2 rounded-lg text-sm text-gray-700 w-full hover:bg-gray-200">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" class="fill-current w-5 h-5"><path d="M20.3 2H3.7C2 2 .6 3.4.6 5.2v10.1c0 1.7 1.4 3.1 3.1 3.1V23l6.6-4.6h9.9c1.7 0 3.1-1.4 3.1-3.1V5.2c.1-1.8-1.3-3.2-3-3.2zm1.8 13.3c0 1-.8 1.8-1.8 1.8H9.9L5 20.4V17H3.7c-1 0-1.8-.8-1.8-1.8v-10c0-1 .8-1.8 1.8-1.8h16.5c1 0 1.8.8 1.8 1.8v10.1zM6.7 6.7h10.6V8H6.7V6.7zm0 2.9h10.6v1.3H6.7V9.6zm0 2.8h10.6v1.3H6.7v-1.3z"/></svg>
                <span class="ml-2">
                    Comment
                </span>
            </button>
        </div>

        <!--Post 2-->
        <div class="flex flex-col pt-3 px-3 pb-0 mt-8">
            <div class="flex items-center">
                <div class="w-10 h-10 rounded-full border-2 border-blue-600 flex items-center justify-center object-cover">
                    <img src="https://images.pexels.com/photos/4890733/pexels-photo-4890733.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260" alt="Smiling man" class="w-8 h-8 object-cover rounded-full"></div>
                <div class="ml-2 w-full">
                    <div class="flex items-center justify-between">
                        <div class="text-sm font-bold"><a href="#" class="text-black">Joe Doe</a></div>
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 32.055 32.055" class="fill-current w-4 h-4 mr-2" >
                            <path d="M3.968,12.061C1.775,12.061,0,13.835,0,16.027c0,2.192,1.773,3.967,3.968,3.967c2.189,0,3.966-1.772,3.966-3.967
                     C7.934,13.835,6.157,12.061,3.968,12.061z M16.233,12.061c-2.188,0-3.968,1.773-3.968,3.965c0,2.192,1.778,3.967,3.968,3.967
                     s3.97-1.772,3.97-3.967C20.201,13.835,18.423,12.061,16.233,12.061z M28.09,12.061c-2.192,0-3.969,1.774-3.969,3.967
                     c0,2.19,1.774,3.965,3.969,3.965c2.188,0,3.965-1.772,3.965-3.965S30.278,12.061,28.09,12.061z" fill="#4a5568"/>
                        </svg>
                    </div>
                    <div class="text-sm text-gray-600 tracking-tight">12 mins • </div>
                </div>
            </div>
            <div>
                <div class="mt-2">
                    <p class="mb-1">Not having fun at all</p>
                </div>
            </div>
        </div>
        <div class="w-full mt-2" v-if="true">
            <img src="https://learn.zoner.com/wp-content/uploads/2018/08/landscape-photography-at-every-hour-part-ii-photographing-landscapes-in-rain-or-shine.jpg" alt="Post Image" class="w-full">
        </div>

        <div class="flex px-3 pt-3 justify-between text-gray-700 text-sm">
            <div class="flex">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" class="fill-current w-5 h-5"><path d="M20.8 15.6c.4-.5.6-1.1.6-1.7 0-.6-.3-1.1-.5-1.4.3-.7.4-1.7-.5-2.6-.7-.6-1.8-.9-3.4-.8-1.1.1-2 .3-2.1.3-.2 0-.4.1-.7.1 0-.3 0-.9.5-2.4.6-1.8.6-3.1-.1-4.1-.7-1-1.8-1-2.1-1-.3 0-.6.1-.8.4-.5.5-.4 1.5-.4 2-.4 1.5-2 5.1-3.3 6.1l-.1.1c-.4.4-.6.8-.8 1.2-.2-.1-.5-.2-.8-.2H3.7c-1 0-1.7.8-1.7 1.7v6.8c0 1 .8 1.7 1.7 1.7h2.5c.4 0 .7-.1 1-.3l1 .1c.2 0 2.8.4 5.6.3.5 0 1 .1 1.4.1.7 0 1.4-.1 1.9-.2 1.3-.3 2.2-.8 2.6-1.6.3-.6.3-1.2.3-1.6.8-.8 1-1.6.9-2.2.1-.3 0-.6-.1-.8zM3.7 20.7c-.3 0-.6-.3-.6-.6v-6.8c0-.3.3-.6.6-.6h2.5c.3 0 .6.3.6.6v6.8c0 .3-.3.6-.6.6H3.7zm16.1-5.6c-.2.2-.2.5-.1.7 0 0 .2.3.2.7 0 .5-.2 1-.8 1.4-.2.2-.3.4-.2.6 0 0 .2.6-.1 1.1-.3.5-.9.9-1.8 1.1-.8.2-1.8.2-3 .1h-.1c-2.7.1-5.4-.3-5.4-.3H8v-7.2c0-.2 0-.4-.1-.5.1-.3.3-.9.8-1.4 1.9-1.5 3.7-6.5 3.8-6.7v-.3c-.1-.5 0-1 .1-1.2.2 0 .8.1 1.2.6.4.6.4 1.6-.1 3-.7 2.1-.7 3.2-.2 3.7.3.2.6.3.9.2.3-.1.5-.1.7-.1h.1c1.3-.3 3.6-.5 4.4.3.7.6.2 1.4.1 1.5-.2.2-.1.5.1.7 0 0 .4.4.5 1 0 .3-.2.6-.5 1z"/></svg>
                <p class="pl-1">John Smith and 91 others</p>
            </div>
            <div>
                <p>27 comments</p>
            </div>
        </div>

        <div class="flex justify-between border-1 border-gray-400 mx-4 mb-2">
            <button class="flex justify-center items-center py-2 rounded-lg text-sm text-gray-700 w-full hover:bg-gray-200">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" class="fill-current w-5 h-5"><path d="M20.8 15.6c.4-.5.6-1.1.6-1.7 0-.6-.3-1.1-.5-1.4.3-.7.4-1.7-.5-2.6-.7-.6-1.8-.9-3.4-.8-1.1.1-2 .3-2.1.3-.2 0-.4.1-.7.1 0-.3 0-.9.5-2.4.6-1.8.6-3.1-.1-4.1-.7-1-1.8-1-2.1-1-.3 0-.6.1-.8.4-.5.5-.4 1.5-.4 2-.4 1.5-2 5.1-3.3 6.1l-.1.1c-.4.4-.6.8-.8 1.2-.2-.1-.5-.2-.8-.2H3.7c-1 0-1.7.8-1.7 1.7v6.8c0 1 .8 1.7 1.7 1.7h2.5c.4 0 .7-.1 1-.3l1 .1c.2 0 2.8.4 5.6.3.5 0 1 .1 1.4.1.7 0 1.4-.1 1.9-.2 1.3-.3 2.2-.8 2.6-1.6.3-.6.3-1.2.3-1.6.8-.8 1-1.6.9-2.2.1-.3 0-.6-.1-.8zM3.7 20.7c-.3 0-.6-.3-.6-.6v-6.8c0-.3.3-.6.6-.6h2.5c.3 0 .6.3.6.6v6.8c0 .3-.3.6-.6.6H3.7zm16.1-5.6c-.2.2-.2.5-.1.7 0 0 .2.3.2.7 0 .5-.2 1-.8 1.4-.2.2-.3.4-.2.6 0 0 .2.6-.1 1.1-.3.5-.9.9-1.8 1.1-.8.2-1.8.2-3 .1h-.1c-2.7.1-5.4-.3-5.4-.3H8v-7.2c0-.2 0-.4-.1-.5.1-.3.3-.9.8-1.4 1.9-1.5 3.7-6.5 3.8-6.7v-.3c-.1-.5 0-1 .1-1.2.2 0 .8.1 1.2.6.4.6.4 1.6-.1 3-.7 2.1-.7 3.2-.2 3.7.3.2.6.3.9.2.3-.1.5-.1.7-.1h.1c1.3-.3 3.6-.5 4.4.3.7.6.2 1.4.1 1.5-.2.2-.1.5.1.7 0 0 .4.4.5 1 0 .3-.2.6-.5 1z"/></svg>
                <span class="ml-2">
                    Like
                </span>
            </button>
            <button class="flex justify-center items-center py-2 rounded-lg text-sm text-gray-700 w-full hover:bg-gray-200">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" class="fill-current w-5 h-5"><path d="M20.3 2H3.7C2 2 .6 3.4.6 5.2v10.1c0 1.7 1.4 3.1 3.1 3.1V23l6.6-4.6h9.9c1.7 0 3.1-1.4 3.1-3.1V5.2c.1-1.8-1.3-3.2-3-3.2zm1.8 13.3c0 1-.8 1.8-1.8 1.8H9.9L5 20.4V17H3.7c-1 0-1.8-.8-1.8-1.8v-10c0-1 .8-1.8 1.8-1.8h16.5c1 0 1.8.8 1.8 1.8v10.1zM6.7 6.7h10.6V8H6.7V6.7zm0 2.9h10.6v1.3H6.7V9.6zm0 2.8h10.6v1.3H6.7v-1.3z"/></svg>
                <span class="ml-2">
                    Comment
                </span>
            </button>
        </div>

    </div>
</template>

<script>
    export default {
        name: "Post"
    }
</script>

<style scoped>

</style>
