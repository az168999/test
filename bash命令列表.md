``` bash 
1. Shell 内建命令 (bash builtins)
cd：切换目录
echo：输出字符串
export：设置环境变量
alias / unalias：创建/删除命令别名
bg / fg / jobs：后台/前台作业控制
exit：退出 shell
history：查看命令历史
source / .：执行脚本

2. 文件与目录操作
ls：列出目录内容
cp：复制文件或目录
mv：移动或重命名
rm：删除文件
rmdir：删除空目录
mkdir：创建目录
stat：显示文件信息
basename / dirname：处理文件路径

3. 文本处理
cat：显示文件内容
head / tail：查看开头或结尾内容
less / more：分页查看文件
grep / egrep / fgrep：文本搜索
cut：按列切分文本
awk：文本处理工具
sed：流编辑器（替换/删除/插入文本）
sort：排序
uniq：去重
wc：统计行数、单词数、字节数
tr：字符替换/删除
diff / cmp：文件比较

4. 压缩与解压
gzip / gunzip / zcat
bzip2 / bunzip2
xz / unxz / xzcat
zipinfo / unzip
tar：打包和解包
zstd / unzstd

5. 系统与进程管理
ps：查看进程
top / htop（部分环境无 htop）：实时监控
kill / killall：终止进程
nice / renice：调整进程优先级
uptime：系统运行时间
free：内存使用情况
df：磁盘空间
du：目录/文件大小
vmstat：虚拟内存统计
uname：系统信息
dmesg：内核日志

6. 网络命令
ping：测试网络连通性
curl / wcurl：请求 URL
ftp / telnet / tftp：网络工具
ifconfig / ip（取决于环境）：查看网络接口
netstat：网络连接
nsenter：进入命名空间

7. 包管理 (Debian/Ubuntu/Termux)
apt / apt-get：安装/升级/卸载软件
apt-cache：查询包信息
dpkg：底层包管理
termux-change-repo：更换 Termux 源
termux-setup-storage：授权存储访问
termux-open / termux-open-url：在 Android 打开文件或 URL

8. 加密/校验
md5sum / sha1sum / sha256sum：文件校验
base64 / base32：编码解码
xxhsum / b2sum：哈希算法

9. 归档与备份
tar：打包压缩
zip / unzip：压缩解压
cpio / rsync（可能需要额外安装）

10. 其他常用
date：显示/设置时间
cal：日历
whoami：显示当前用户
id：显示 UID/GID
chmod / chown / chgrp：修改权限
find：查找文件
xargs：参数传递
```