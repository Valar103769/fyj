<template>
  <div>
    <div class="hero">
      <div class="hero-body">
        <h2 class="title">游记</h2>
        <div class="columns is-multiline">
          <div
            class="column is-3"
            v-for="n in 6"
            :key="n"
          >
            <figure class="image is-4by3">
              <img
                :src="require(`@/assets/girl${n}.jpg`)"
                alt=""
              >
            </figure>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "Photos",
  data: () => ({})
}
</script>
