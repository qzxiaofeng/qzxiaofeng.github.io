# 我的第一个网站

# 第一次
echo "# qzxiaofeng.github.io" >> README.md
git init
git add README.md  -- 可以改为添加所有 add *
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:qzxiaofeng/qzxiaofeng.github.io.git
git push -u origin main


# 后续修改用它就行
git remote add origin git@github.com:qzxiaofeng/qzxiaofeng.github.io.git
git branch -M main
git push -u origin main