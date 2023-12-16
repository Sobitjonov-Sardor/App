<template>
  <div class="wrapper">
    <Header />
    <Main />
    <Footer />
  </div>
</template>

<script>
import Header from "@/components/Header.vue";
import Main from "./components/Main.vue";
import Footer from "@/components/Footer.vue";

export default {
  data() {
    return {
    }
  },
  components: {
    Header,
    Main,
    Footer,
  }
}
</script>

<style lang="scss">
:root {
  --mainColor: #0C7F8E;
  --greyColor: #A6A6A6;
  --blackColor: #000;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

li {
  list-style: none;
}

a {
  text-decoration: none;
}

input,
button {
  border: none;
  outline: none;
  background: none;
  transition: .3s;
}

button {
  cursor: pointer;
  &:active {
    transform: scale(0.95);
  }
}


.container {
  max-width: 1010px;
  width: 100%;
  padding: 0 35px;
  margin: 0 auto;
}

.containerHeader {
  max-width: 1010px;
  width: 100%;
  padding: 0 21px 0 55px;
  margin: 0 auto;
}

body {
  background: #F5FCFC;
}


@font-face {
  font-family: 'Inter';
  src: url('./assets/fonts/Inter-Regular.ttf');
  font-weight: 400;
}

@font-face {
  font-family: 'Rubik';
  src: url('./assets/fonts/Rubik-Regular.ttf');
  font-weight: 400;
}

@font-face {
  font-family: 'Rubik';
  src: url('./assets/fonts/Rubik-SemiBold.ttf');
  font-weight: 600;
}

@font-face {
  font-family: 'Road Rage';
  src: url('./assets/fonts/RoadRage-Regular.ttf');
  font-weight: 400;
}
@font-face {
  font-family: 'Roboto';
  src: url('./assets/fonts/Roboto-Regular.ttf');
  font-weight: 400;
}
@font-face {
  font-family: 'Roboto';
  src: url('./assets/fonts/Roboto-Bold.ttf');
  font-weight: 700;
}
</style>
