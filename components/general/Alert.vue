<template>
  <div class="alert" :class="type">
    {{ message }}
  </div>
</template>

<script>
export default {
  name: 'Alert',
  props: ['message', 'type'],
};
</script>

<style>
.alert {
  width: 98%;
  border: 0px solid;
  border-radius: 10px;
  text-align: center;
  padding: 10px;
  color: white;
  margin: 5px;
}
.information {
  background-color: purple;
}
</style>
