<template>
    <div class="w-11/12 xl:w-3/4 mb-4">
        <div class="flex items-baseline justify-between tracking-tight">
            <h3 class="font-bold text-base text-gray-700">Stories</h3>
            <a href="#" class="font-semibold text-blue-600">See All</a>
        </div>

        <div class="flex justify-around">

            <div class="h-40 w-24 rounded-lg object-cover mx-1 shadow-xl relative bg-gray-800 hover:bg-gray-600 transform transition duration-200">
                <div class="absolute z-10 h-8 w-8 flex items-center justify-center mx-1 my-2 rounded-full border-2 border-white">
                    <span class="absolute h-8 w-8 rounded-full bg-gray-100 opacity-25"></span>
                    <svg class="absolute z-10 h-2 w-2" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M24 10h-10v-10h-4v10h-10v4h10v10h4v-10h10z" fill="#fff"/></svg>
                </div>
                <img src="https://images.pexels.com/photos/736716/pexels-photo-736716.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=940&w=650" alt="" class="h-40 w-24 rounded-lg object-cover absolute opacity-75">
                <p class="absolute text-white font-semibold font-sm bottom-0 tracking-tight mb-1 px-2 leading-4">Add to Story</p>
            </div>

            <div class="h-40 w-24 rounded-lg object-cover mx-1 shadow-xl bg-gray-800 relative hover:bg-gray-600 transform transition duration-200">
                <div class="absolute z-10 h-8 w-8 flex items-center justify-center mx-1 my-2 rounded-full border-2 border-white">
                    <img src="https://images.pexels.com/photos/874158/pexels-photo-874158.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500" alt="sidebar-item" class="absolute w-6 h-6 rounded-full object-cover z-10 border-2 border-white">
                </div>
                <img src="https://cdn.webshopapp.com/shops/290883/files/320051105/anerkjendt-anerkjendt-max-shirt-0007.jpg" alt="" class="h-40 w-24 rounded-lg object-cover opacity-75">
                <p class="absolute text-white font-semibold font-sm bottom-0 tracking-tight mb-1 px-2 leading-4">Joe Doe</p>
            </div>
            <div class="h-40 w-24 rounded-lg object-cover mx-1 shadow-xl bg-gray-800 relative hover:bg-gray-600 transform transition duration-200">
                <div class="absolute z-10 h-8 w-8 flex items-center justify-center mx-1 my-2 rounded-full border-2 border-white">
                    <img src="https://images.pexels.com/photos/324658/pexels-photo-324658.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500" alt="sidebar-item" class="absolute w-6 h-6 rounded-full object-cover z-10 border-2 border-white">
                </div>
                <img src="https://www.googleapis.com/download/storage/v1/b/svo_9jaar/o/participant_4432.jpg?generation=1568324667696273&alt=media" alt="" class="h-40 w-24 rounded-lg object-cover opacity-75">
                <p class="absolute text-white font-semibold font-sm bottom-0 tracking-tight mb-1 px-2 leading-4">Jane Doe</p>
            </div>
            <div class="h-40 w-24 rounded-lg object-cover mx-1 shadow-xl bg-gray-800 relative hidden sm:flex hover:bg-gray-600 transform transition duration-200">
                <div class="absolute z-10 h-8 w-8 flex items-center justify-center mx-1 my-2 rounded-full border-2 border-white">
                    <img src="https://images.pexels.com/photos/1587009/pexels-photo-1587009.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500" alt="sidebar-item" class="absolute w-6 h-6 rounded-full object-cover z-10 border-2 border-white">
                </div>
                <img src="https://www.ronddelinge.nl/wp-content/uploads/2018/12/DSC_2324-16-9klein.jpg" alt="" class="h-40 w-24 rounded-lg object-cover opacity-75">
                <p class="absolute text-white font-semibold font-sm bottom-0 tracking-tight mb-1 px-2 leading-4">Ronald Doe</p>
            </div>
            <div class="h-40 w-24 rounded-lg object-cover mx-1 shadow-xl bg-gray-800 relative hidden sm:flex hover:bg-gray-600 transform transition duration-200">
                <div class="absolute z-10 h-8 w-8 flex items-center justify-center mx-1 my-2 rounded-full border-2 border-white">
                    <img src="https://images.pexels.com/photos/1212984/pexels-photo-1212984.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500" alt="sidebar-item" class="absolute w-6 h-6 rounded-full object-cover z-10 border-2 border-white">
                </div>
                <img src="https://www.googleapis.com/download/storage/v1/b/svo_9jaar/o/participant_4329.jpg?generation=1567604730872719&alt=media" alt="" class="h-40 w-24 rounded-lg object-cover opacity-75">
                <p class="absolute text-white font-semibold font-sm bottom-0 tracking-tight mb-1 px-2 leading-4">Stephany Doe</p>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "Stories"
    }
</script>

<style scoped>

</style>
