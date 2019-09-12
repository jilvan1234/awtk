## tk\_ostream\_file\_t
### 概述
![image](images/tk_ostream_file_t_0.png)


 input stream base on fileory



----------------------------------
### 函数
<p id="tk_ostream_file_t_methods">

| 函数名称 | 说明 | 
| -------- | ------------ | 
| <a href="#tk_ostream_file_t_tk_ostream_file_create">tk\_ostream\_file\_create</a> |  |
#### tk\_ostream\_file\_create 函数
-----------------------

* 函数功能：

> <p id="tk_ostream_file_t_tk_ostream_file_create">
 创建ostream对象。






* 函数原型：

```
tk_ostream_t* tk_ostream_file_create (const char* filename);
```

* 参数说明：

| 参数 | 类型 | 说明 |
| -------- | ----- | --------- |
| 返回值 | tk\_ostream\_t* | 返回ostream对象。 |
| filename | const char* | 文件名。 |