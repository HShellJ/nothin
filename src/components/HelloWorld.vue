<template>
  <p id="hello"> {{ counter }}
  </p>
  <div id="hello-worlds"  @click="clickHandle">
    <p>
      shit
      </p>
  </div>
</template>


<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  data(){
      return {
        fuck: 'fuck',
        ht : "<a href='http://www.baidu.com'>fuck this</a>",
        counter : 0
      }
  },
  methods:{
      clickHandle(){
        this.counter +=1;
      }
  }
}
</script>
