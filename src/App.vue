<template>
<div class="flex justify-center my-10">
  <div class="text-center w-full ">
    <img :src="'profilePhoto.png'" alt="" class="w-[120px] rounded-2xl flex  mx-auto" />
    <div class="my-4 md:my-6">
    <h1 class="text-[16px] md:text-[24px] font-medium">Rodney Cotton</h1>
    <p class="text-[12px] md:text-[14px] font-medium text-[#A9A9A9]">Helsinki, Finland</p>
    </div>
    <div class="flex justify-center ">
      <div class="bg-[#E5E5E5] md:px-8 px-4 rounded-2xl py-2  mx-2 font-medium">
        <h1 class="md:text-[18px] text-[14px]">100</h1>
        <p class="text-[#BDBDBD] md:text-[14px] text-[10px]">Posts</p>
      </div>
      <div class="bg-[#E5E5E5] md:px-8 px-4 rounded-2xl py-2  mx-2 font-medium">
        <h1 class="md:text-[18px] text-[14px]">2,242</h1>
        <p class="text-[#BDBDBD] md:text-[14px] text-[10px]">Followers</p>
      </div>
      <div class="bg-[#E5E5E5] md:px-8 px-4 rounded-2xl py-2  mx-2 font-medium">
        <h1 class="md:text-[18px] text-[14px]">1,432</h1>
        <p class="text-[#BDBDBD] md:text-[14px] text-[10px]">Following</p>
      </div>
    
    </div>
  </div>
</div>

<div class="container mx-auto  px-5 py-2  w-full md:w-[800px] ">
  <div class="-m-1 flex flex-wrap md:-m-2 ">
    <div class="flex w-1/3  flex-wrap">
      <div class="w-full p-1 md:p-2">
        <img alt="gallery" class="block h-full w-full rounded-lg object-cover object-center" :src="'photo1.png'" />
      </div>
    </div>
    <div class="flex w-2/3  flex-wrap">
      <div class="w-full p-1 md:p-2">
        <img alt="gallery" class="block h-full w-full rounded-lg object-cover object-center" :src="'photo2.png'" />
      </div>
    </div>
  </div>
  <div class="-m-1 flex flex-wrap md:-m-2">
    <div class="flex w-2/3 flex-wrap">
      <div class="w-full p-1 md:p-2">
        <img alt="gallery" class="block h-full w-full rounded-lg object-cover object-center" :src="'photo3.png'" />
      </div>
      <div class="w-1/2 p-1 md:p-2">
        <img alt="gallery" class="block h-full w-full rounded-lg object-cover object-center" :src="'photo5.png'" />
      </div>
      <div class="w-1/2 p-1 md:p-2">
        <img alt="gallery" class="block h-full w-full rounded-lg object-cover object-center" :src="'photo6.png'" />
      </div>
    </div>
    <div class="flex w-1/3 flex-wrap">
      <div class="w-full p-1 md:p-2">
        <img alt="gallery" class="block h-full w-full rounded-lg object-cover object-center" :src="'photo4.png'" />
      </div>
    </div>
  </div>
</div>

<p class="h-[200px]"></p>
</template>

<style>
* {
  font-family: 'Montserrat', sans-serif;
}
</style>