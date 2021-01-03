<!--
 * @Author: taiduo
 * @Date: 2020-12-13 21:34:06
 * @LastEditTime: 2021-01-03 23:18:01
 * @LastEditors: Please set LastEditors
 * @Description: 面试核心点
 * @FilePath: /review/webpack/README.md
-->


## 1:webpack执行的过程
    

## 1:webpack 插件原理，如何写一个插件


## 2:webpack 配置优化


## 3:webpack 的 require 是如何查找依赖的


## 4:webpack 如何实现动态加载


## 5:webpack中loaders作用？plugins和loaders区别？
   #### 1:webpack原生只支持js和json类型文件，通过loaders可以处理其他类型的文件
   #### 2:plugins作用于整个构建过程，用于文件的优化，资源管理和环境变量的注入。

## 6:loader的执行顺序为什么是后写的先执行
> webpack选择了函数式编程的方式，所以loader的顺序编程了从右往左，如果webpack选择了pipe的方式，那么大家现在写loader的时候的顺序就变成从左往右了


## 7:tree-shaking作用，如何才能生效


## 9:webpack的分包策略
