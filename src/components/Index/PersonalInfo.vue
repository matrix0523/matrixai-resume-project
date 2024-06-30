<script lang="ts">
export default {
  data() {
    return {
      msg: '个人简历',
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
  <!-- 页面标题 -->
  <!-- <h1>{{ msg }}</h1> -->
  <!-- <input v-model="msg"> -->
  <!-- 个人基本信息介绍 -->
  <div  class="header">
    <!-- 基础信息 -->
    <section>
        <!-- <img src="./avatar.png" alt="" class="src">   -->
        <h2>个人信息</h2>
        <ul>
          <li><p>姓名:<a>{{ name }}</a></p></li>
          <li><p>性别:<a>{{ sex }}</a></p></li>
          <li><p>年龄:<a>{{ age }}</a> 岁</p></li>
          <li><p>籍贯:<a>{{ native }}</a></p></li>
          <li><p>联系电话:<a>{{ phone }}</a></p></li>
          <li><p>电子邮箱:<a>{{ email }}</a></p></li>
          <li><p>求职意向:<a>{{ applyjob }}</a></p></li>
          <li><p>期望薪资:<a>{{ salary }}</a></p></li>
        </ul>  
    </section>  
  </div>
</template>
<style>
  body {
      font-family: Georgia, serif;;
      margin: auto;
      background: linear-gradient(to bottom, #4cc7de,#47b4de,#5736ff,#6e36ff,#515de6,#b8009b, #f4009a);
  }
  .header {
    border-radius: 5px;
    background-color: white;
    color: white;
    padding: 20px;
    margin: 20px;
    text-align: left;
  }
  h1 {
      font-size: 50px;
      font-family: Georgia, serif;
      color: black; /* 灰色 */
  }
  h2 {
      font-size: 25px;
      color: black; /* 灰色 */
  }
  h3 {
      font-size:medium;
      font-family:Georgia, serif;
      color: black; /* 灰色 */
  }
  p {
      color: black;
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
  .header img{
      border-radius: 5px;
      /* display: flex; */
      /* margin: 20px; */
      width: 160px;
      height: 170px;
      align-content:end;
  }
  .header h1{
      text-align: right;
  }
  .header ul{
    list-style-type:disc; /* 将项目符号更改为方形 */  
    color: black; /* 改变项目符号的颜色 */  
  }
  .header li{
    font-size: 18px;
    font-family: serif;
  }
</style>