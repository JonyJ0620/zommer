放大镜组件

# 使用场景

![image-20220914194720943](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20220914194720943.png)

图片内展示遮罩层对图片进行放大预览

# 使用方法

1.通过包管理工具下载 

```shell
npm i yu-zoomer
pnpm i yu-zoomer
yarn yu-zoomer
```

2.在使用的页面引入组件

```vue
import Zoomer from 'zoomer';
```





3.将img图片src路径使用:imgSrc传入

```vue
<zoomer :imgScr="图片路径" />
```

4.对组件进行宽高css设置

```vue
<zoomer class="glass"></zoomer>

<style lang="scss" scoped>
    .glass {
        width: 400px;
        height: 400px;
    }

</style>
```
