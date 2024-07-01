<script lang="ts">
export default {
  data() {
    return {
      msg: '很高兴你能认识我！',
      name: '陶朝阳',
      sex: '男',
      age: '23',
      native: '江苏省泰州市',
      phone: '1888888888',
      email: 'matrixai@local.local',
      applyjob: '电商运营',
      salary: '7k~8k',
      detail: '',
      personaldetail: '',
      edudetail: '',
      projectdetail: '',
      internshipdetail: '',
      certdetail: '',

    }
  }
}
</script>
<template>
    <div class="front">
        <!-- 页面标题 -->
        <img src="@/assets/logo.png" alt="" class="logo"/>
        <hr />
        <h1>{{ msg }}</h1>
        <!-- <input v-model="msg"> -->
    </div>
</template>
<style>
  body {
    font-family: Georgia, serif;;
    margin: auto;
    background: linear-gradient(to bottom, #4cc7de,#47b4de,#5736ff,#6e36ff,#515de6,#b8009b, #f4009a);
  }
  .front {
    border-radius: 5px;
    background-color: rgba(255, 255, 255, 0);
    color: rgba(255, 255, 255, 0);
    padding: 20px;
    margin:20px;
    text-align: left;
  }
  .front h1 {
    border: 5px;
    font-size: 25px;
    font-family: Georgia, serif;
    color: black; /* 灰色 */
    text-align: center;
    margin-top: 5px;
    margin-bottom: auto;
    margin-left: auto;
    margin-right: auto;
  }
  .front .logo {
    width: 100px;
    height: 100px;
    border-radius: 50%;
    margin-top: auto;
    margin-bottom: 5px;
    margin-left: auto;
    margin-right: auto;
    display: flex;
  }
  .front hr{
    border: 1px solid #000;
    margin-top:auto;
    margin-bottom: auto;
    margin-left: 20%;
    margin-right: 20%;
  }
  h2 {
    font-size: 25px;
    color: #666; /* 灰色 */
  }
  h3 {
    font-size:medium;
    font-family:Georgia, serif;
    color: #666; /* 灰色 */
  }
  p {
    color: #666;
  }
  a {
    color: #008CBA; /* 蓝色 */
    text-decoration: none;
  }
  a:hover {
    text-decoration: underline;
  }
  .content {
    border-radius: 5px;
    background-color: white;
    padding: 20px;
    margin-top: 20px;
  }
  .front img{
    border-radius: 5px;
    /* display: flex; */
    /* margin: 20px; */
    width: 160px;
    height: 170px;
  }
  ul{
    font-size: 18px;
  }
  li{
    font-family: serif;
  }
</style>