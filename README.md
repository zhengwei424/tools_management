# tools_management
运维工具管理平台
# 创建功能分支
```bash
git checkout -b feature/user-registration
```

# 前端开发
```bash
git add frontend/src/register/
git commit -m "feat(frontend): registration form"
```

# 后端开发
```bash
git add backend/app/routes/auth.py
git commit -m "feat(backend): registration endpoint"
```

# 继续迭代...
```bash
git add frontend/
git commit -m "fix(frontend): fix form validation"

git add backend/
git commit -m "fix(backend): add email validation"
```
# 功能完成后，一次性合并
```bash
git checkout main
git merge feature/user-registration
git push origin main
```

# 其他
```bash
echo "# tools_management" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/zhengwei424/tools_management.git
git push -u origin main

git remote add origin https://github.com/zhengwei424/tools_management.git
git branch -M main
git push -u origin main
```
