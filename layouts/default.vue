<template>
<!-- navigation -->
<nav class="bg-transparent mt-5 p-4">
    <ul class="flex space-x-4 is-justify-space-between  ml-24 gap-4">
        <li class="text-black text-xs font-bold pr-4" >
            <NuxtLink to="/"> ホメウ</NuxtLink>
        </li>
        <li class="text-black text-xs font-bold pr-4">
                <NuxtLink to="/Aboutus"> 私たちに関しては</NuxtLink>
            </li>
            <li class="text-black text-xs font-bold pr-4">
                    <NuxtLink to="/"> 科目</NuxtLink>
                </li>
                    <li class="text-black text-xs font-bold pr-4">
                        <NuxtLink to="/Home">アーカイブ</NuxtLink>
                    </li>
                    <li class="text-black text-xs font-bold pr-4">
                            <NuxtLink to="/Home"> イベント</NuxtLink>
                        </li>
        
        
        
    </ul>
</nav>




















<!--  
insert everthing here        -->
<div  class=" flex ml-28">
    
    <slot />
</div>





</template>

<style>
body{
    background-color: #F5F1E9;
}
</style>