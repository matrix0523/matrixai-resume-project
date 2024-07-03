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
  <div class="content">
      <!-- 重点项目介绍 -->
      <h2>关于创世CreativeAI</h2>
      <p>使用AI技术为您的创意加速</p>
      
      <h2>用户指南</h2>
      <p>以下是一些使用本网站的简单指南：</p>
      <ul>
          <li><strong>导航：</strong>点击顶部菜单来浏览不同部分。</li>
          <li><strong>联系我们：</strong>如果您有任何疑问或建议，请<a href="mailto:contact@example.com">联系我们</a>。</li>
          <li><strong>社交媒体：</strong>关注我们的<a href="https://twitter.com/example">Twitter</a>和<a href="https://www.facebook.com/example">Facebook</a>账号以获取最新消息。</li>
      </ul>
      
      <h2>联系方式</h2>
      <!-- <p>如果您对我们的服务有任何问题，欢迎随时联系我们：</p> -->
      <address>
        <ul>
          <li>地址：<a>{{}}</a></li>
          <li>电话：<a>{{}}</a></li>
          <li>电子邮件(E-mail)：<a href="mailto:matrixai@local.local">matrixai@local.local</a></li>
        </ul>
      </address>
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
.footer  {
  margin-top: auto;
  margin-bottom: auto;
  margin-left: auto;
  margin-right: auto;
  display: flex;
}
</style>