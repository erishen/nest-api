# 创建 .env

- PORT=8083

# Command

- curl http://localhost:8083/upload -F 'file=@./package.json' -F 'name=test'
- curl http://localhost:8083/uploads/\*
