<template>
  <div id="app" class="container">
    <div class="border-gray-300">
      <div id="nav">
        <router-link to="/">Home</router-link>|
        <router-link to="/about">About</router-link>
      </div>
      <router-view />
    </div>
  </div>
</template>

<style src="./assets/tailwind.css">