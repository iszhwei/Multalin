# multalin
这是一个**基因序列比对工具**，主要用于**1个模板比对N个测序结果**

三年生物缘结束了，希望为该工具为更多的研究者减轻工作负担！！！

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
