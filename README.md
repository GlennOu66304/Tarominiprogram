## Enviroment Building:
1.NVM shift the node to the latest version:  
```
source ~/.bash_profile 
command -v nvm  
nvm use node 
```
Node version in the project:  v14.14.0 (npm v6.14.8)
NVM:[11.Bugs: fixing when you run the project in the Local shell:](https://github.com/GlennOu66304/Uniapp-Mini-Program-Development)  

2.Install Taro
````
npm install -g @tarojs/cli 
taro -v
taro init myApp
```

3. Move to unde the project directory:   
```
cd /Users/zt/Tarominiprogram/myApp
```
4. Test the project in  the wechat, h5
Wechat
```
yarn dev:weapp 
```
 open the Wechat dev tool, then import the project into the Wechat dev tool. Then wait for the project loading in the wechat dev tool:  
Check the video begin 08:42, you will see the effect:[Taro开发小程序 - 开始](https://www.bilibili.com/video/av540990204/)  

5.H5 page Check :
```
source ~/.bash_profile  
command -v nvm 
nvm use node 
yarn dev:h5  
```
Node version management: [11.Bugs: fixing when you run the project in the Local shell:](https://github.com/GlennOu66304/Uniapp-Mini-Program-Development)  

Main reference:  
[安装及使用](https://taro-docs.jd.com/taro/docs/GETTING-STARTED/)
[多端统一开发框架 Taro 的安装与使用](https://juejin.im/book/6844733744830480397/section/6844733744918560782)  
[【原创：Taro系列基础篇】一：taro简介及项目准备](https://blog.huangkaihan.tech/article/47)  
[Taro开发小程序 - 开始](https://www.bilibili.com/video/av540990204/)  

## Learning Resource
Main  Reference: 掘金小册：[Taro 多端开发实现原理与项目实战](https://juejin.im/book/6844733744830480397)  
Taro doc:[Taro](https://taro.jd.com/)  
Tarogithub:[Taro Github](https://github.com/NervJS/taro)   
[使用 Taro 开发微信小程序的实践 + 踩坑合集](https://juejin.im/post/6844903793935515655)  
[Taro 小程序开发大型实战（一）：熟悉的 React，熟悉的 Hooks](https://juejin.im/post/6844904032125845517)  
[Taro 小程序开发大型实战（二）：多页面跳转和 Taro UI 组件库](https://juejin.im/post/6844904033929396237)  
[Taro 小程序开发大型实战（三）：实现微信和支付宝多端登录](https://juejin.im/post/6844904038635405320)  
[Taro 小程序开发大型实战（四）：使用 Hooks 版的 Redux 实现应用状态管理（上篇）](https://juejin.im/post/6844904038652182535)  
[Taro 小程序开发大型实战（五）：使用 Hooks 版的 Redux 实现应用状态管理（下篇）](https://juejin.im/post/6844904048039034894)  
[Taro 小程序开发大型实战（六）：尝鲜微信小程序云（上篇）](https://juejin.im/post/6844904048101949454)  
[Taro 小程序开发大型实战（七）：尝鲜微信小程序云（下篇）](https://juejin.im/post/6844904067475439623)   
[Taro 小程序开发大型实战（八）：尝鲜 LeanCloud Serverless 云服务](https://juejin.im/post/6844904068981194766)  