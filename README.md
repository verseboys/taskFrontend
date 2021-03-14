参考https://www.runoob.com/vue2/vue-install.html


npm install -g cnpm --registry=https://registry.npm.taobao.org
npm install --save element-ui element-ui/lib/theme-chalk/index.css vue-layer vue-layer/lib/vue-layer.css

1. 安装

   ```
   cd my-project
   cnpm install
   ```

2. 运行

   ```
   cnpm run dev
   ```



安装组件

1. install

   ```
   cnpm install vue-layer
   ```
   
   npm install webpack-dev-server --save

   

2. src/main.js

   ```
   import layer from 'vue-layer'
   import 'vue-layer/lib/vue-layer.css'
   
   Vue.prototype.$layer = layer(Vue)
   
   ```

   

3. 
