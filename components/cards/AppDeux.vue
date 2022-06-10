<template>
  <div :class="col">
    <div class="card">
      <div class="card-body">
        <h3 class="card-title" v-text="title"></h3>
        AppDeux
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "AppDeux",
  props: ["col", "title"],
};
</script>
