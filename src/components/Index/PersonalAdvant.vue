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
      adv1: '具有出色的沟通技巧和人际交往能力，能够建立和维护良好的工作关系。在过去的工作中，我成功地与多个部门合作，推动项目进展并解决问题。',
      adv2: '熟练掌握多种编程语言（如Python、Java）和软件开发工具（如Git、Docker），能够独立完成软件开发任务。',
      adv3: '具有强烈的自我驱动和学习能力，始终保持对新技术和行业趋势的关注，通过参加培训和阅读专业文献来不断提升自己的知识和技能。',
      adv4: '善于团队合作，能够积极参与团队讨论，提出建设性的意见和解决方案，与团队成员共同实现目标。'
    }
  }
}
</script>
<template>
    <div class="advant">
    <section>  
        <h2>个人优势</h2>
        <ul>
            <li><a>{{ adv1 }}</a></li>
            <li><a>{{ adv2 }}</a></li>
            <li><a>{{ adv3 }}</a></li>
            <li><a>{{ adv4 }}</a></li>
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
  .advant {
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
  .advant img{
      border-radius: 5px;
      /* display: flex; */
      /* margin: 20px; */
      width: 160px;
      height: 170px;
      align-content:end;
  }
  .advant h1{
      text-align: right;
  }
  ul{
    list-style-type:disc; /* 将项目符号更改为方形 */  
    color: black; /* 改变项目符号的颜色 */  
    font-size: 18px;
  }
  li{
    font-size: 18px;
    font-family: serif;
  }
</style>