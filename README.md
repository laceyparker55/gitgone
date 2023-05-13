# gitgone
gitgone
# 更新所有脚本（包括自用own脚本）
5 * * * * sleep 54 && jup >> /jd/log/jup.log 2>&1

# 删除旧日志
57 13 * * * jlog

# 导出所有互助码清单，日志在log/jcode下
48 5 * * * jcode
