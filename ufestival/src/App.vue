<template>
  <header>
    <AppHeader />
  </header>
  <body>
    <div>
      <router-view />
    </div>
  </body>
  <footer>
    <AppFooter />
  </footer>
</template>

<script>
import AppHeader from "./AppHeader.vue"; // Use the correct filename and no curly braces
import AppFooter from "./AppFooter.vue"; // Use the correct filename and no curly braces

export default {
  name: "App",
  components: {
    AppHeader,
    AppFooter,
  },
};
</script>

<style scoped>
.title {
  width: 100%;
  padding: 50px;
  box-shadow: 0 5px 0px rgba(0, 0, 0, 0.1);
  color: #000000;
  font-family: bold 700;
  font-weight: 700;
  font-size: 5em;
  text-align: left;
  margin: 20px;
}

footer {
  display: flex;
  align-items: flex-end;
  box-shadow: #9f9f9f 0px 0px 10px;
  justify-content: space-between;
  gap: 24px; /* space between SVGs */
  padding: 20px;
  position: fixed;
  bottom: 0;
  left: 0;
  background: #fff;
  width: 100%;
}

.footer-svg {
  color: #000000;
}
</style>

<!-- cd C:\xampp\htdocs\U-Festival\UFestival -->
