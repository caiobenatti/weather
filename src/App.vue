<template>
  <div id="app">
    <main>
      <div class="serch-box">
        <input type="text" class="search-bar" placeholder="Search..." />
      </div>
    </main>
  </div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      api_key: "2e6f3a48a7d1db4218d23364e6a65440",
    };
  },
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: "monteserrat", sans-serif;
}

#app {
  background-image: url(./assets/cold-bg.jpg);
}
</style>
