<template>
  <div >
    <!--中-->
<!--    <m-button :type="'warn'">nio</m-button>-->
    <slot></slot>
    <!--footer-->
    <div >
      <span>Copyright &copy;{{ currentDate }}  orangeconnex Inc. All rights reserved.</span>
    </div>
  </div>
</template>

<script >

  // import MButton from './MButton'

  export default {
    name: 'LayoutMain',
    computed: {
      currentDate(){
        return new Date().getFullYear();
      }
    },
    // components:{
    //   MButton
    // },
    data() {
      return {
        driver: null,
        treeData:[]
      }
    },
    mounted(){
      /*加载问候信息*/
    },
    methods:{
    }
  };
</script>

