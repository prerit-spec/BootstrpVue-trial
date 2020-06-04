<template>
  <div class="home">
    <b-container>
      <b-row align-v="center">
        <card />
        <card />
        <card />
        <card />
        <card />
      </b-row>
    </b-container>
  </div>
</template>

<script>
import card from "@/components/card.vue";
// @  is an alias to /src
export default {
  name: "Home",
  components: { card },
};
</script>
