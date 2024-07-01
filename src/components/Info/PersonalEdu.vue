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
    <div class="edu">
    <!-- 教育经历 -->
    <section>  
        <h2>教育经历</h2>
        <div>
            <ul>
                <li><p>学校名称：<a>{{}}</a></p></li>
                <li><p>专业：<a></a></p></li>
                <li><p>学位：<a></a></p></li>
                <li><p>相关课程：<a></a></p></li>
                <li><p>学习时间：<a></a></p></li>
            </ul> 
        </div>
        <hr />
        <div>
            <ul>
                <li><p>学校名称：<a></a></p></li>
                <li><p>专业：<a></a></p></li>
                <li><p>学位：<a></a></p></li>
                <li><p>相关课程：<a></a></p></li>
                <li><p>学习时间：<a></a></p></li>
            </ul> 
        </div>
    </section>  
    </div>
</template>
<style>
  body {
      font-family: Georgia, serif;;
      margin: auto;
      background: linear-gradient(to bottom, #4cc7de,#47b4de,#5736ff,#6e36ff,#515de6,#b8009b, #f4009a);
  }
  .edu {
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
  .edu img{
      border-radius: 5px;
      /* display: flex; */
      /* margin: 20px; */
      width: 160px;
      height: 170px;
      align-content:end;
  }
  .edu h1{
      text-align: right;
  }
  .edu ul{
    list-style-type:disc; /* 将项目符号更改为方形 */  
    color: black; /* 改变项目符号的颜色 */  
    font-size: 18px;
  }
  .edu li{
    font-size: 18px;
    font-family: serif;
  }
  .edu div{
    margin:10px;
  }
  .edu hr{
    margin-top: auto;
    margin-bottom: auto;
    margin-left: auto;
    margin-right: auto;
    height:50%;
    width:50%;
    border-radius:5px;
    background-color: rgba(255, 255, 255, 0);
    border-bottom: 1px solid;
  }
</style>