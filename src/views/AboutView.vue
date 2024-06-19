<template>
  <div class="about">
    <font-awesome-icon icon="fa-solid fa-user-secret" />
    <h1>This is an about page</h1>
  </div>
  <button @click="count++">{{ count }}</button>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";

@Options({
  components: {},
})
export default class HomeView extends Vue {
  public count = 0;
}
</script>
