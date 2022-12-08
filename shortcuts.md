# 快捷键
## tmux快捷键
* tmux new -s //新建名称为demo的会话
* tmux detach //断开会话后台运行,同prefix + d
* tmux attach-session -t session-name //重新连接session
* tmux kill-session -t session-name //关闭session会话
* tmux kill-server //关闭服务器,所有的会话都会关闭
* tmux list-session //查看所有会话
* prefix + s //查看session窗口
* prefix + D //选择断开的会话
* prefix + & //关闭当前窗口
* prefix + - //水平拆分窗口
* prefix + | //垂直拆分窗口
* prefix +p //上一个窗口
* prefix + n //下一个窗口
* prefix + <c-k> //往上调整10个单元格
* prefix + <c-j> //往下调整10个单元格
* prefix + <c-h> //往左调整10个单元格
* prefix + <c-l> //往右调整10个单元格


## nvim
### telescope
* prefix + ff //搜索文件
* prefix + fb //搜索buff
* prefix + fs //搜索当前string
* prefix + fh //搜索帮助
* prefix + fg //live grep

* <c-j> //代码补全后跳转
* gd //go to define
* <c-o> // 回退

