# github-helper
改版Github助手  
https://blog.csdn.net/sherpahu/article/details/95049550

1. 单个文件下载
2. 单个文件夹下载
3. 图片放大
4. ipynb直接使用nbviewer打开
# 具体实现方法
1. 单文件下载和图片放大沿用了YeomanYe的方法。  
2. 文件夹下载利用https://minhaskamal.github.io/DownGit/#/home 实现下载功能。  
我之前试过直接遍历解析文件夹下的所有文件，但是效果不好，还是直接跳转到DownGit比较方便有效。  
3. 因为墙的存在，Github的很多CDN被DNS污染，还可能是Github自身的一些原因，ipynb打开极为缓慢，时不时像下面这样特别慢。
![1563348432742](https://i.loli.net/2019/07/17/5d2eccf73290a83178.png)
甚至是打不开。
![1563348432743](https://i.loli.net/2019/07/17/5d2ecd542e37731167.png)
但利用nbviewer可以完美打开。
![1563348432744](https://i.loli.net/2019/07/17/5d2ecdaa2855589724.png)
