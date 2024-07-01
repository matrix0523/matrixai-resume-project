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
    <div class="header">
    <!-- 实习经历 -->
    <section>  
        <h2>实习经历</h2>
        <div><h3>{{ internshipdetail }}</h3></div> 
        <!-- 在这里可以添加具体的实习经历详情 -->  
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
      text-align: left;
  }
  h1 {
      font-size: 50px;
      font-family: Georgia, serif;
      color: black; /* 灰色 */
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
  .header img{
      border-radius: 5px;
      /* display: flex; */
      /* margin: 20px; */
      width: 160px;
      height: 170px;
      align-content:end;
  }
  .header-h1{
      text-align: right;
  }
  ul{
    font-size: 18px;
  }
  li{
    font-family: serif;
  }
</style>