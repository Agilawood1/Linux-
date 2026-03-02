# Linux-

## 文件与目录操作

- `ls`：列出目录内容
  - `ls -l`：显示详细信息（权限、大小、时间）
  - `ls -a`：显示所有文件，包括以.开头的隐藏文件，也可以显示某个文件目录下的全部文件，如`ls -a .github`
- `cd`：切换目录
  - `cd ..`：切换上一级
  - `cd - `：跳到家目录
- `pwd`：显示当前所在的绝对路径
- `mkdir`：创建文件夹，`-p`参数可以递归创建，例如`mkdir -p build/debug`
- `rm`：删除文件或目录，慎用`rm -rf <文件夹名>`，强制递归删除文件夹及其所有内容
- `cp`/`mv`：复制/移动（或重命名）文件
- `touch`：创建文件，如`touch .github/copilot-instructions.md`（或先cd后，直接touch）
- `echo`：创建文件并写入内容，如`echo "# Copilot System Prompt" > .github/copilot-instructions.md`，注意`>`会覆盖文件原有内容，如果要追加，用`>>`
