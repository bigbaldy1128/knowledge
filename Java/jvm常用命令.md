# 查看vmid
jps
# 查看对象数量以及内存占用
jmap [vmid]
# 查看GC状态
jstat -gcutil [vmid]
# 查看内存使用并且对齐列显示
jstat -gccapacity [vmid]|column -t