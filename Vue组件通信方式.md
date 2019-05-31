Vue组件通信方式：

一、组件通信分类：
1. 父子组件通信： 
    a. 父向子组件使用props,子向父通过events($emit)
    b. 通过实例访问（$parent/$children); 
    c. provide/inject API
    d. $attrs/$listeners

2. 兄弟组件通信： Bus； vuex
3. 跨级通信： Bus; Vuex; Provide/Inject API; $atts/$listeners

