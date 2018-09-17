<template>
	<div class="test">
		<p>{{msg}}</p>	
		<TestComponent :testWord="testWord"></TestComponent>		
	</div> 
</template>
<script>
//@ is src
import TestComponent from "@/components/TestComponent.vue";

export default {
  data() {
    return {
      msg: "test vue page!",
      testWord: "this is test word from parent!"
    };
  },
  name: "test",
  components: {
    TestComponent
  }
};
</script>