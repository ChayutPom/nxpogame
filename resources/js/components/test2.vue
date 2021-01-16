<template>
   <nav
      class="navbar navbar-light"
      style="background-color: #e3f2fd; height: 85px"
    >
      

    <div class="col-2">
      <a class="navbar-brand" href="#">Sticky top</a>
    </div>
    <div class="col-10">
 <b-progress
                      variant="warning"
                      :max="10"
                      :value="countDown"
                      height="25px"
                    ></b-progress>
       
  </div>
    </nav>
</template>

<script>
</script>

<style lang="stylus">

</style>