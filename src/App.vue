<script setup>
import Header from '@/components/Header.vue'
</script>

<template>
  <Header />
</template>

<style>
body {
	margin: 0;
	font-family: "RF Rufo", sans-serif;
	font-size: 18px;
	color: #FFFFFF;
	-webkit-font-smoothing: antialiased;
}

*,
*:before,
*:after {
	box-sizing: border-box;
}

h1,
h2,
h3,
h4,
h5,
h6 {
	margin: 0;
}

p {
	margin: 0 0 10px;
}

a {
	text-decoration: none;
	color: #FFFFFF;
}

.container {
	width: 100%;
	max-width: 1300px;
	margin: 0 auto;
	padding: 0 15px;
}

.social__items--item {
	margin-right: 22px;
}

.social__items--item:last-child {
	margin-right: 0;
}
</style>
