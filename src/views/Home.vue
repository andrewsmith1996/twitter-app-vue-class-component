
<template>
  <div>
    <Tweet />
    <Tweet />
    <Tweet />
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import Tweet from "../components/Tweet.vue";

@Component({
  components: {
    Tweet
  }
})
export default class Home extends Vue {

}
</script>