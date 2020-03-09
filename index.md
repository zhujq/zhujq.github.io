# 一级标题
## 三级标题
**bold**  
*斜体*  
***YES***  
~~delete~~  

 ---
[简书](http://jianshu.com)  
* 首先  
     * 1
     * 2
     * 3
          * ab

1. one
2. two
3. three

  
   表头|表头|表头
   ---|:--:|---:
   内容|内容|内容
   内容|内容|内容

`int 5 `

```
    function fun(){
         echo "这是一句非常牛逼的代码";
    }
    fun();
```  

```flow
st=start:Start
i=inputoutput:输入年份n
cond1=condition:n能否被4整除？
cond2=condition:n能否被100整除？
cond3=condition:n能否被400整除？
o1=inputoutput:输出非闰年
o2=inputoutput:输出非闰年
o3=inputoutput:输出闰年
o4=inputoutput:输出闰年
e=end

st-i-cond1
cond1(no)-o1-e
cond1(yes)-cond2
cond2(no)-o3-e
cond2(yes)-cond3
cond3(yes)-o2-e
cond3(no)-o4-e
```