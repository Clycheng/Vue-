## vue 基本知识
    >vue双向绑定原理
        object.defineProty
    >mvvm详解
        m mode v view  viewmodel
    >单页面优缺点
        优点：加载速度快
        缺点：不利于seo优化
## vue组件知识点
    >组件的注册（全局、局部）
        vue.component(全局)
        components:{
            组建挂载
        }
    >父子组件传值、兄弟组件传值
        props 父传子
        $emit 子传父

        vux 
    >生命周期
        生成前后 挂在前后 更新前后 卸载前后
    >计算属性
        computed
    >监听属性
        watch
    >solt插槽  子组件slot标签   父组件 标签+slot  作用：子组件里有不确定的元素 可以写个插槽，通过父组件里插进去 
    >动态添加class  css
        三目运算符
    >修饰符(默认事件) .stop ....
    >computed与methods的区别
        computed是用于计算  可以将函数名直接写到模板内 并且计算  methods里是存一些方法
    >keep-alive
    >NextTick
## vue-router知识点
    >嵌套路由，父子路由
        children 
    >导航钩子
        to from  next  
        全局钩子
        局部路由钩子  可以获取到上下层页面的信息  并且进行判断  next 函数做一些接下来的事情
    >路由懒加载  component 箭头函数 （import 组件路径） 
    >重定向 
    >路由传参  1/router-link  to+参数   2/router.push (path  params)
    >history模式 
    >路由命名 name
    >导航守卫 (钩子)
    >$route和$router区别
    >滚动行为
## Vuex知识点
    >state 存储数据
    >Getter 
    >mutation
    >action
    >module
## Vue Loader

