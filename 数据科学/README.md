## 【数据 · 基础题：收集优化问题】
  
---
### 【赛题说明】
&emsp;&emsp;在一片区域内有N个地点，每个地点有价值不同的物品，所有地点之间都有道路相连，且经过每条道路需要耗费相应的时间。现在给定时间T，要求在规定时间内收集物品，并使其总价值最大。其中出发点可以为所有地点中的任意一个，输出结果为物品的最大总价值及其所经过的路线（只需一条）。同时，若可在规定时间T内到达所有地点，则要求出耗时最短的路线，并输出所需的最短时间。例如：  
<p align="center">
 <img src="https://github.com/CXCYGZF-UESTC/SME_2018/raw/master/%E6%95%B0%E6%8D%AE%E7%A7%91%E5%AD%A6%20%C2%B7%20%E5%9F%BA%E7%A1%80%E9%A2%98/picture/%E5%9B%BE%E4%B8%80.png" width="600">
</p>  
  
N=4，T=70，则从20经9到8，再经34到12，最后经15到4  
则输出结果为：  
44   
20-(9)-8-(15)-12-(15)-4  
20-(9)-8-(15)-12-(15)-4  
39   
<br />
  
### 【测评标准】
- 本题将会提供五幅图片（图片如下）作为求解对象，参赛选手需按照要求输出所有的正确答案。  
  - 输出收集到的物品的最大总价值及其所经过的路线。  
  - 若可在规定时间T内到达所有地点，则要求出耗时最短的路线，并输出所需的最短时间。  
  - 使用Python：要求读写操作，以txt.文件输入，输入信息及格式自行决定，但需要添加说明。输出结果格式以例题为标准，以txt.文件输出。  
  - 使用C语言：不需要读写操作，输入可以直接写在程序中，输出直接给结果，然后以例题格式上交。  
- 参赛选手需为自己的代码添加详细的注释，说明代码的步骤及功能。
- 参赛选手书写一份100字至300字之间的解题思路，包括使用的算法等。 
#### 图一：T=45
<p align="center">
 <img src="https://github.com/hanwen9663uestc/SME_2018/raw/master/%E6%95%B0%E6%8D%AE%E7%A7%91%E5%AD%A6%20%C2%B7%20%E5%9F%BA%E7%A1%80%E9%A2%98/picture/%E9%99%84%E4%BB%B61.png" width="500">
</p>  

#### 图二：T=70  
<p align="center">
 <img src="https://github.com/hanwen9663uestc/SME_2018/raw/master/%E6%95%B0%E6%8D%AE%E7%A7%91%E5%AD%A6%20%C2%B7%20%E5%9F%BA%E7%A1%80%E9%A2%98/picture/%E9%99%84%E4%BB%B62.png" width="500">
</p>  
  
#### 图三：T=90
<p align="center">
 <img src="https://github.com/hanwen9663uestc/SME_2018/raw/master/%E6%95%B0%E6%8D%AE%E7%A7%91%E5%AD%A6%20%C2%B7%20%E5%9F%BA%E7%A1%80%E9%A2%98/picture/%E9%99%84%E4%BB%B63.png" width="500">
</p>  
  
#### 图四：T=70
<p align="center">
 <img src="https://github.com/hanwen9663uestc/SME_2018/raw/master/%E6%95%B0%E6%8D%AE%E7%A7%91%E5%AD%A6%20%C2%B7%20%E5%9F%BA%E7%A1%80%E9%A2%98/picture/%E9%99%84%E4%BB%B64.png" width="500">
</p>  
  
#### 图五：T=100
<p align="center">
 <img src="https://github.com/hanwen9663uestc/SME_2018/raw/master/%E6%95%B0%E6%8D%AE%E7%A7%91%E5%AD%A6%20%C2%B7%20%E5%9F%BA%E7%A1%80%E9%A2%98/picture/%E9%99%84%E4%BB%B65.png" width="500">
</p>  
<br />
  
### 【注意事项】  
- 收集物体总价值最大的路线和到达所有地点耗时最短的路线可能存在多条，但两者均各输出一条即可。  
<br />
  
### 【参考资料】  
#### 《Python 基础教程》：  
<p align="center">
 <img src="https://github.com/CXCYGZF-UESTC/SME_2018/raw/master/%E6%95%B0%E6%8D%AE%E7%A7%91%E5%AD%A6%20%C2%B7%20%E5%9F%BA%E7%A1%80%E9%A2%98/picture/%E5%9B%BE%E4%B8%89.jpg">
</p>  

#### 《C/C++ Primer Plus》：  
<p align="center">
 <img src="https://github.com/CXCYGZF-UESTC/SME_2018/raw/master/%E6%95%B0%E6%8D%AE%E7%A7%91%E5%AD%A6%20%C2%B7%20%E5%9F%BA%E7%A1%80%E9%A2%98/picture/%E5%9B%BE%E4%BA%8C.png">
</p>  


