# LearnSetGit  
## 二级标题  
/##不同的 Markdown 应用程序处理 # 和标题之间的空格方式并不一致。为了兼容考虑，请用一个空格在 # 和标题之间进行分隔。
--------
**嘿嘿**   
强调/**  
--------
[Markdown官方语法](https://markdown.com.cn/)  
----
要创建代码块，请将代码块的每一行缩进至少四个空格或一个制表符    

    <a> </a>  
    
----

*哈哈*
*酷捏*
## 公钥
- 本机已配置
> 1. 打开git bash 
> 2. `cat ~/.ssh/id_rsa.pub`
> 3. 获取到ssh公钥去git配置
- 本机未配置
> 1. 打开git bash 
> 2. `ssh-keygen -t rsa -C`
> 3. 查看id_rsa.pub文件，获取到ssh公钥去git配置  

> 通讯测试 `ssh -T git@github.com`
