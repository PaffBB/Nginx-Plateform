<script></script>
<template>
<div class="sidebar">
    <a href="#">概览</a>
    <a href="#">实例管理</a>
    <a href="#">证书管理</a>
    <a href="#">个性化配置</a>
    <a href="#">闲置实例</a>
    <a href="#">访问日志</a>
</div>
</template>
<style>
.sidebar{
    width:15%;
    list-style:none;
    background-color:#ffadad;
}
.sidebar a {
  display: block;
  text-decoration: none;
  text-align:center;
  font-size: 14px;
  color: #fff;
  background-color:rgb(37, 42, 46);
  height: 50px; 
  line-height: 50px; 
  transition:0.4s
}
.sidebar a:hover{
    background-color:rgb(46, 52, 57);
}
</style>