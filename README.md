# multalin
这是一个**基因序列比对工具**，主要用于**1个模板比对N个测序结果**
## 背景
虽然市面上有很多优秀的软件或网站能做双序列比对或者多序列比对，但对于每个基因要对几十个甚至上百个样品测序结果比对步骤太繁琐，浪费大量时间和人力，因此编写了个小工具解放劳动力，现在把它分享出来，希望能对医学方向的同学和生物方面研究的同学提供些许帮助，尤其是对做**基因编辑方向**的同学简直就是福音。

依次致敬我的三年生物缘吧！！！

## 工具内容
1. 三个文件夹“result”、“sequence”、“wt”
2. multalin.exe

## 使用方法
1. sequence文件夹用于存放测序后的结果。解压后的“.seq”和“.ab1”文件可以直接放在这个文件夹内
2. wt文件夹用于存放模板序列。每次比对只能放该基因的模板序列
3. 比对后的结果以照片的形式保存在result文件夹内，为了方便日后查看又把结果自动存储到word内便于编辑
4. 每次比对只需要改动wt内的模板序列和sequence内的测序结果，result内的结果照片会在比对开始自动清空

![image](https://user-images.githubusercontent.com/113836412/190904212-6efd6790-153a-4b71-a174-9cb04ca284bc.png)
![image](https://user-images.githubusercontent.com/113836412/190904381-403f7238-171b-4552-9dd9-3b486d41d986.png)
## 注意：
1. 有小伙伴问我模板(wt文件夹下)格式是什么样的
```
//template.txt	注意内容为fasta格式
>tempalteName   
ATCGATCGATCGATCGATCGATCGATCGATCGATCGATCGATCGATCGATC
```
2. 如果软件出问题，说明服务器出现了问题，请隔几天再尝试
