为typora 0.9.72(beta)版本编写的css样式, 能够自动生成**标题标号**

# 内容
这里给出了四种版本:
* v1: 显示所有标题标号
* v2: 一级标题不显示
* v3: 只显示1,2级标题
* v4: 只显示2,3级标题
* v5: 只显示1,2级标题,并且1级标题中文显示.
* 最终版本: 1级标题中文显示,1,2,3级标题显示数字, 其他标题使用列表样式
    > 陆佬的改造版本

----------
除此之外, 这里还给出了调整Vue主题样式的css文件(`Vue.user.css`), 有如下功能:
* 使得含链接的标题能够有不同的颜色, 区分其他普通标题.
* 使所有标题更大一点.

# 使用
* 打开主题目录: `typora-->文件-->偏好选择-->外观-->主题-->打开主题文件夹`
* 将某个版本的css放入该目录下即可
* 重启

# 待修复Bug
- [ ] 正文标题中有代码时会显示错误