# cmake

> [**现代cmake**](https://modern-cmake-cn.github.io/Modern-CMake-zh_CN/README_GitBook.html)

---

### configure_file

configure_file是CMake中的一个命令，用于将文件内容复制到另一个文件，并在复制过程中替换源文件中的变量。它通常用于生成配置文件，其中包含一些参数化的内容。

configure_file的基本语法如下：
```
cmake
Copy code
configure_file(input_file output_file [COPYONLY] [ESCAPE_QUOTES] [@ONLY])
```
其中：
- input_file是源文件的路径。
- output_file是目标文件的路径，可以是相对路径或绝对路径。
- COPYONLY选项表示只复制文件而不替换变量。
- ESCAPE_QUOTES选项表示在变量替换时转义引号。
- @ONLY选项表示只替换@标记的变量，而不替换$标记的变量。

---

