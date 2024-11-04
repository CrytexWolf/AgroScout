<script>
import Header from '@/components/Header.vue'

export default {
  components: {
    Header,
  }
};
</script>

<template>
  <Header />
</template>

<style>
  body {
	margin: 0;
	font-family: "Raleway", sans-serif;
	font-size: 14px;
	color: #6c7279;
	-webkit-font-smoothing: antialiased;

	background-color: #fff;
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

  .container {
    max-width: 1300px;
    width: 100%;
    margin: 0 auto;
    padding: 0 15px;
  }
</style>
