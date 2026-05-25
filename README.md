# -novel-writer-# 解压下载的文件
tar -xzf novel-system-deploy.tar.gz
cd novel-system

# 初始化并上传
git init
git add .
git commit -m "initial commit"
git branch -M main
git remote add origin https://github.com/ 您的用户名/novel-system.git
git push -u origin main
