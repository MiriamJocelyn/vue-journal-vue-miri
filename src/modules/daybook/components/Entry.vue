<template>
  <div 
  @click="$router.push({name:'entry',params:{id:10}})" 
  class="entry-container mb-3 pointer p-2">
    <div class="entry-title d-flex">
      <span class="text-success fs-5 fw-bold">15</span>
      <span class="mx-1 fs-5">Julio</span>
      <span class="mx-2 fw-light">2021,jueves</span>
    </div>

    <div class="entry-description">
      Duis elit adipisicing aliqua qui eiusmod. Esse ut proident tempor elit
      sint pariatur velit. Tempor nulla nostrud sunt enim sit anim aute irure
      sit ea amet consectetur. Mollit voluptate velit sit occaecat pariatur
      tempor proident. Labore mollit pariatur in laboris deserunt eiusmod ea non
      non in nisi eu velit qui. Est sunt ea ea aute dolore occaecat exercitation
      ex exercitation proident aliquip nostrud deserunt sint.
    </div>
  </div>
</template>

<script>


export default {
  
};
</script>

<style lang="scss" scoped>
.entry-container {
  border-bottom: 1px solid #2c3e50;
  transition: 0.2s all ease-in;
  &:hover {
    background-color: lighten($color: grey, $amount: 45);
    transition: 0.2s all ease-in;
  }
  .entry-description {
      font-size: 12px;
  }
}
</style>