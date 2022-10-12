<template>
  <div>
    <h5>Hi I am MD Obaydullah</h5>
    <p>{{ msg }}</p>
  </div>
</template>

<script>
  export default {
    name: 'MyBaby',
    props: {
      'msg': String
    }
  }
</script>