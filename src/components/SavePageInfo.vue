<template>
  <div class="warning">
    <h1>Please save this page to your local drive before use</h1>
    <div>
      Please <a href="." download="BananaSplit.html">save this html file</a> to
      a folder on your local drive, and then open the file from there.
    </div>
  </div>
</template>

<script>
export default {
  name: "SavePageInfo"
};
</script>

<style>
.warning {
  background: #ffbbb3;
  border: solid #e87f73 7px;
}
</style>
