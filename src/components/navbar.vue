<template>
    <nav class="navbar">
        <div class="nav-container">
             
            <NuxtLink to="/" class="logo"></NuxtLink>

            <!--Menu Principal-->
            <div class="nav-menu">
                <ul>
                <li><NuxtLink to="/team">TEAMS</NuxtLink></li>
                <li><NuxtLink to="/responsibility">RESPONSIBILITY</NuxtLink></li>
                <li><NuxtLink to="/insigths">INSIGTHS</NuxtLink></li>
                <li><NuxtLink to="/login">INVESTOR LOGIN</NuxtLink></li>
                </ul>
            </div>
            
        </div>
        

    </nav>
</template>

<script setup>
import '../assets/css/navbar.css'  
</script>



