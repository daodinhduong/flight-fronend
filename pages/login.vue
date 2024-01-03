<script setup>

const password = ref('');
const userName = ref('');

</script>
<template>
<div class="flex justify-center items-center h-[100vh]">
    <div class="flex flex-col w-[40%] items-center">
      <img class="w-[300px]" src="~assets/image/logo.jpg" />
   <div class=" h-[300px] w-[100%] rounded-md shadow-lg flex flex-col justify-center gap-5 items-center">
    <div>
    <div>User Name:</div>
    <el-input  class="!w-[300px] mt-1" size="large" v-model="userName" placeholder="User Name" />
    </div>
    <div>
    <div>Password:</div>
    <el-input type="password" show-password  class="!w-[300px] mt-1" size="large" v-model="password"  placeholder="Password" />
</div>
<el-button type="success">Đăng nhập</el-button>
   </div>
</div>
</div>
</template>
<style scoped>
</style>