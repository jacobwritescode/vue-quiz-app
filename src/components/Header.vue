<template>
  <div>
    <b-nav tabs>
      <b-nav-item disabled><b>Quiz App</b></b-nav-item>
      <b-nav-item disabled>Score : {{numberCorrect}}/{{numberTotal}}</b-nav-item>
    </b-nav>
  </div>
</template>
<script>
export default {
    props:{
        numberCorrect:Number,
        numberTotal:Number
    }
}
</script>