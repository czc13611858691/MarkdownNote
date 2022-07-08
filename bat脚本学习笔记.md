# bat脚本学习笔记

## 1.bat执行时会在窗口打印命令，使用@不打印命令

**测试代码**

```
echo hello
@echo world	
```

**运行结果**

<img src="bat脚本学习笔记.assets/image-20220707213945438.png" alt="image-20220707213945438" style="zoom: 50%;" />

**结果分析**

>   echo hello打印了执行命令，@echo world没有打印执行命令
>
>   @的作用在于不在cmd中打印执行的命令 