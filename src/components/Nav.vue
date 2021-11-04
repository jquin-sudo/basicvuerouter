<template>
<div class="bg-yellow-500 text-black">
<div class="container mx-auto flex items-center justify-between">
<h1 class="tracking-tight text-3xl font-thin">    
    Basic
    <span class="font-normal ">Router</span>
</h1>
<nav>
    <ul class="flex space-x-4 ">
        <router-link to="/">
        <li class="py-8 px-4 hover:cursor-pointer hover:bg-blue-300 hover:text-white">
            Home
            
            </li>
            </router-link><router-link to="/about">
        <li class="py-8 px-4 hover:cursor-pointer hover:bg-blue-300 hover:text-white">
            About
            
            </li>
            </router-link><router-link to="/hello">
        <li class="py-8 px-4 hover:cursor-pointer hover:bg-blue-300 hover:text-white">
            Hello
            
            </li>
            </router-link>
    </ul>
</nav>
</div>
</div>
</template>