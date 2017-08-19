渐进式vue：响应的数据绑定，组合的视图组件-->只关注视图层view
vue的两个核心点（vue不兼容IE8）
           响应的数据绑定，--数据发生改变，界面发生改变（Object.definePrototype）
           组合的视图组件，--UI页面映射组件树，划分组件，相对独立（饿了吗）
vue-router:路由
虚拟DOM：‘’
MVVM：model（m） view（v） view-model（VM）
声明式渲染


vue语法 ；
  {{ message}} 
  let data={
          message:"vue学习"
       }
  var VM= new vue（{//选项对象，且VM是以$开头的内置属性
        el:“#con”//元素选择器
        data:data //代理数据
        methods(){//ES6函数写法
            name:function(){代码}
        }
       }）
       
 指令：v-on  简写@：事件监听
      v-bind（简写：）动态绑定数据
      v-html=“html”
 模板：字符串模板：template
     HTML模板：基于DOM的模板，可以解析的HTML{{key值||简单的数字或者三目}}
     render函数模板
