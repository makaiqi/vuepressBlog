### 1.在 .md 文件中书写代码时，可在 ``` 后增加 js、html、json等格式类型，代码块即可按照指定类型高亮
### 2.自定义容器

##### 代码:

::: tip 提示
this is a tip
:::

::: warning 注意
this is a tip
:::

::: danger 警告
this is a tip
:::

### 3.支持Emoji
:tada:  :100:  :bamboo:  :gift_heart:  :fire:

### 4.支持 PWA

config.js 文件中增加

``` 
head: [ // 注入到当前页面的 HTML <head> 中的标签
  ['link', { rel: 'manifest', href: '/photo.jpg' }],
  ['link', { rel: 'apple-touch-icon', href: '/photo.jpg' }],
],
serviceWorker: true // 是否开启 PWA
```