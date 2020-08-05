<template>
    <div class="w-4/12 xl:w-1/4 bg-white p-3 border-r border-gray-400 hidden lg:flex flex-column overflow-y-scroll">
        <div class="flex items-baseline justify-between tracking-tight">
            <h3 class="font-bold text-base pt-2 text-gray-700">Suggested</h3>
        </div>

        <!-- Groups Card-->
        <div class="relative w-11/12 flex flex-col justify-center items-center rounded-lg shadow transform transition duration-500 hover:-translate-y-1 hover:shadow-2xl">
            <div class="bg-black rounded-t-lg">
                <img src="https://images.pexels.com/photos/1438072/pexels-photo-1438072.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260" alt="" class="w-full h-40 object-cover rounded-t-lg opacity-75">
            </div>
            <div class="absolute text-white w-full px-4">
                <div class="flex justify-start w-2/3">
                    <h4 class="text-base font-bold">Groups</h4>
                </div>
                <div class="flex justify-start text-sm tracking-tighter leading-4 w-7/12">
                    <p>New ways to find and join communities</p>
                </div>
                <div class="flex justify-start w-2/3 text-black mb-6">
                    <button class="bg-gray-200 px-2 py-1 rounded-lg font-semibold text-sm shadow-lg tracking-tight">Find Your Groups</button>
                </div>
            </div>

            <!--Friends joined-->
            <div class="flex relative items-center">
                <div class="flex flex-row justify-start w-full flex-1">
                    <div class="border-white border rounded-full w-6 h-6 -mr-2 box-content  z-30">
                        <img src="https://images.pexels.com/photos/733872/pexels-photo-733872.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500" alt="sidebar-item" class="w-6 h-6 rounded-full object-cover">
                    </div>

                    <div class="border-white border rounded-full w-6 h-6 -mr-2 box-content z-20">
                        <img src="https://images.pexels.com/photos/733872/pexels-photo-733872.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500" alt="sidebar-item" class="w-6 h-6 rounded-full object-cover">
                    </div>
                    <div class="border-white border rounded-full w-6 h-6 box-content z-10">
                        <img src="https://images.pexels.com/photos/733872/pexels-photo-733872.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500" alt="sidebar-item" class="w-6 h-6 rounded-full object-cover z-10">
                    </div>



                </div>

                <!-- Text -->
                <div class="flex-4 mx-1 py-1">
                    <p class="text-gray-600 text-sm tracking-tight mb-0 py-2"><strong>Jochem</strong> and <strong>9 friends</strong> joined Groups</p>
                </div>

            </div>
        </div>

        <!-- Contacts -->
        <div class="mt-4">
            <div class="flex items-center justify-between">
                <h3 class="font-bold text-base pt-2 text-gray-700">Contacts</h3>
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 32.055 32.055" class="fill-current w-4 h-4" >
                    <path d="M3.968,12.061C1.775,12.061,0,13.835,0,16.027c0,2.192,1.773,3.967,3.968,3.967c2.189,0,3.966-1.772,3.966-3.967
                     C7.934,13.835,6.157,12.061,3.968,12.061z M16.233,12.061c-2.188,0-3.968,1.773-3.968,3.965c0,2.192,1.778,3.967,3.968,3.967
                     s3.97-1.772,3.97-3.967C20.201,13.835,18.423,12.061,16.233,12.061z M28.09,12.061c-2.192,0-3.969,1.774-3.969,3.967
                     c0,2.19,1.774,3.965,3.969,3.965c2.188,0,3.965-1.772,3.965-3.965S30.278,12.061,28.09,12.061z" fill="#4a5568"/>
                </svg>
            </div>
            <ul class="font-semibold tracking-tight">
                <li class="flex items-center">
                    <img src="https://images.pexels.com/photos/1516680/pexels-photo-1516680.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500" alt="sidebar-item" class="w-8 h-8 rounded-full object-cover mr-2 my-2">
                    <a href="#" class="text-black">Ronald Doe</a>
                </li>
                <li class="flex items-center">
                    <img src="https://images.pexels.com/photos/1858175/pexels-photo-1858175.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500" alt="sidebar-item" class="w-8 h-8 rounded-full object-cover mr-2 my-2">
                    <a href="#" class="text-black">Isabel Doe</a>
                </li>
                <li class="flex items-center">
                    <img src="https://images.pexels.com/photos/733872/pexels-photo-733872.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500" alt="sidebar-item" class="w-8 h-8 rounded-full object-cover mr-2 my-2">
                    <a href="#" class="text-black">Pete Doe</a>
                </li>
                <li class="flex items-center">
                    <img src="https://images.pexels.com/photos/936229/pexels-photo-936229.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500" alt="sidebar-item" class="w-8 h-8 rounded-full object-cover mr-2 my-2">
                    <a href="#" class="text-black">Stephany Doe</a>
                </li>
                <li class="flex items-center">
                    <img src="https://images.pexels.com/photos/38554/girl-people-landscape-sun-38554.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500" alt="sidebar-item" class="w-8 h-8 rounded-full object-cover mr-2 my-2">
                    <a href="#" class="text-black">Luke Doe</a>
                </li>
                <li class="flex items-center">
                    <img src="https://images.pexels.com/photos/1065084/pexels-photo-1065084.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500" alt="sidebar-item" class="w-8 h-8 rounded-full object-cover mr-2 my-2">
                    <a href="#" class="text-black">Jaimy Doe</a>
                </li>
                <li class="flex items-center">
                    <img src="https://images.pexels.com/photos/324658/pexels-photo-324658.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500" alt="sidebar-item" class="w-8 h-8 rounded-full object-cover mr-2 my-2">
                    <a href="#" class="text-black">Hank Doe</a>
                </li>
                <li class="flex items-center">
                    <img src="https://images.pexels.com/photos/874158/pexels-photo-874158.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500" alt="sidebar-item" class="w-8 h-8 rounded-full object-cover mr-2 my-2">
                    <a href="#" class="text-black">Jake Doe</a>
                </li>
                <li class="flex items-center">
                    <img src="https://images.pexels.com/photos/1587009/pexels-photo-1587009.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500" alt="sidebar-item" class="w-8 h-8 rounded-full object-cover mr-2 my-2">
                    <a href="#" class="text-black">Jane Doe</a>
                </li>
                <li class="flex items-center">
                    <img src="https://images.pexels.com/photos/1212984/pexels-photo-1212984.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500" alt="sidebar-item" class="w-8 h-8 rounded-full object-cover mr-2 my-2">
                    <a href="#" class="text-black">John Doe</a>
                </li>
            </ul>
        </div>
    </div>


</template>

<script>
    export default {
        name: "SuggestedBar"
    }
</script>

<style scoped>

</style>
