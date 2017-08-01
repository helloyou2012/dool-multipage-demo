Dool Multipage Demo
===================

```bash
npm i dool -g

git clone https://github.com/helloyou2012/dool-multipage-demo.git
cd dool-multipage-demo

npm i
dool server
open http://localhost:8000/demo/home.html

// 编译、压缩、打包，默认路径 dist
dool build

// 如果页面很多可以开启 Cluster 加快打包速度
dool build --cluster
```