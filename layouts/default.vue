<template>
  <div>
    <TheHeader/>
    <Nuxt />
    <TheFooter/>
  </div>
</template>

<script>
import TheHeader from "../components/header/TheHeader";
import TheFooter from "../components/footer/TheFooter";

export default {
  name: "App",
  components: {
    TheHeader,
    TheFooter
  },
}
</script>
