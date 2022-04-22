<template>
  <div>
    <div class="container-fluid">
      <div class="d-flex row bg_myblack justify-content-between align-items-center py-2">
        <div class="col">
           <a href="#"><img src="../assets/img/logo.png" alt="logo boolflix"></a> 
        </div>
        <div class="d-flex col align-items-center">
          <div class="input-group input-group-sm mb-3 justify-content-end">
            <input type="text" class="form-control-sm me-3" aria-label="Sizing example input" 
            aria-describedby="inputGroup-sizing-sm" placeholder="Search movies or series">
            <button type="button" class="btn-sm btn-danger">Search</button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HeaderFlix',
 
}
</script>

<style scoped lang="scss">

@import './style/index.scss';

.bg_myblack{
  background-color: $bg-header;
}

</style>