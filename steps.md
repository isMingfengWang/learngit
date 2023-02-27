本地文件夹和repositories建立关联的步骤：

- 对本地文件夹进行初始化
  - git init
  - 该命令会创建一个.git文件
- 创建一个新的respositories
- 将本地文件夹和github的repositories进行关联

```bash
git remote add origin git@github.com:michaelliao/learngit.git
```

- 如果本地文件夹中有文件，需要以下步骤将文件上传
  - git add readme.txt
    - 可以上传多个文件到暂存区stage
  - git commit -m "comments"
    - 将文件提交
  - git push origin main
    - 将文件推送到github的repositories

