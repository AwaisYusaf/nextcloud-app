<template>
  <NcAppContent>
    <div id="liqueous">
      <h1>Hello world!</h1>
      <a href="https://www.liqueous.com">Redirect to Liqueous</a>
    </div>
  </NcAppContent>
</template>

<script>
import NcAppContent from "@nextcloud/vue/dist/Components/NcAppContent.js";

export default {
  name: "App",
  components: {
    NcAppContent,
  },
};
</script>

<style scoped lang="scss">
#liqueous {
  display: flex;
  justify-content: center;
  margin: 16px;
}
</style>
