<template>
  <div
    @click="$router.push({ name: 'entry', params: { id: 1 } })"
    class=" entry-container mb-3 pointer p-2"
  >
    <div class="entry-title d-flex">
      <span class="fs-5 text-success fw-bold ">15</span>
      <span class="mx-1 fs-5">Julio</span>
      <span class="mx-2 fw-ligth"> 2021,Jueves </span>
    </div>
    <div class="entry-description">
      Lorem ipsum dolor, sit amet consectetur adipisicing elit. Officia, in! Ea
      obcaecati, ducimus rem eos rerum ad aspernatur animi saepe sed architecto
      autem. Qui in autem asperiores perspiciatis provident placeat.
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.entry-container {
  border-bottom: 1px solid #2c3e50;
  transition: 0.2s all ease-in;

  &:hover {
    background-color: lighten($color: grey, $amount: 45);
  }
  .entry-description {
    font-size: 12px;
  }
}
</style>
