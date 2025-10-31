# GitHub 协作练习说明

欢迎来到 hello-github-for-cpu 仓库！这是一个专门为练习 GitHub 协作而设计的项目。

## 目录结构

```
hello-github
 ├── README.md           # 项目简介
 ├── students/           # 学生文件目录
 │    └── example.txt    # 示例文件
 └── instructions.md     # 本说明文件
```

## 如何参与

### 1. Fork 这个仓库
点击页面右上角的 "Fork" 按钮，将此仓库复制到你自己的 GitHub 账户下。

### 2. 克隆到本地
```bash
git clone https://github.com/你的用户名/hello-github-for-cpu.git
cd hello-github-for-cpu
```

### 3. 创建你的文件
在 `students/` 目录下创建一个以你的名字或学号命名的文件，例如：
```bash
cd students
touch 你的名字.txt
```

在文件中添加你的信息（参考 `example.txt`）：
- 姓名
- 学号
- 邮箱
- 其他你想分享的信息

### 4. 提交更改
```bash
git add students/你的名字.txt
git commit -m "添加我的信息"
```

### 5. 推送到你的仓库
```bash
git push origin main
```

### 6. 创建 Pull Request
1. 访问你 Fork 的仓库页面
2. 点击 "Pull Request" 按钮
3. 点击 "New Pull Request"
4. 填写 PR 标题和描述
5. 提交 Pull Request

## 注意事项

- 请只在 `students/` 目录下添加你自己的文件
- 不要修改其他人的文件
- 保持文件命名规范，避免使用特殊字符
- 提交信息要清晰明了

## 学习资源

- [Git 官方文档](https://git-scm.com/doc)
- [GitHub 官方指南](https://guides.github.com/)
- [Pro Git 中文版](https://git-scm.com/book/zh/v2)

祝你学习愉快！🎉
