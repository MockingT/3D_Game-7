# 3D_Game-7  
## 简单粒子制作  
### 题目要求  
- 按参考资源要求，制作一个粒子系统，参考资源  
- 使用 3.3 节介绍，用代码控制使之在不同场景下效果不一样  
### 实现效果  
不同颜色的光圈会循环显示  
![avatar](https://github.com/MockingT/3D_Game-7/blob/master/pictures/1a6433fe7682fe6ae92ec52a6ed3597.png)  
![avatar](https://github.com/MockingT/3D_Game-7/blob/master/pictures/257c4d3174ebd368819ba6d8277d67d.png)  
![avatar](https://github.com/MockingT/3D_Game-7/blob/master/pictures/25b8cb301040977e1e4bd0cdfea072c.png)  
![avatar](https://github.com/MockingT/3D_Game-7/blob/master/pictures/25de3b61755e9f969a2c7dc98af9d1e.png)  
![avatar](https://github.com/MockingT/3D_Game-7/blob/master/pictures/8a5900f35e01640d88b8b7fbc000457.png)  
### 实现步骤  
- 粒子系统结构(第一个粒子系统是光源，第一个子系统是光芒的效果，第二个子系统用于产生星光)  
![avatar](https://github.com/MockingT/3D_Game-7/blob/master/pictures/10ed31a567830c3a11e28d28f41d1d2.png)  
- 先完成一个简单的粒子系统
创建一个空对象，添加粒子系统，
