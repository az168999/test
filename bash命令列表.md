``` Text 
🔴常规类

🔹1. Shell 内建命令 (bash builtins)
cd：切换目录
echo：输出字符串
export：设置环境变量
alias / unalias：创建/删除命令别名
bg / fg / jobs：后台/前台作业控制
exit：退出 shell
history：查看命令历史
source / .：执行脚本

🔹2. 文件与目录操作
ls：列出目录内容
cp：复制文件或目录
mv：移动或重命名
rm：删除文件
rmdir：删除空目录
mkdir：创建目录
stat：显示文件信息
basename / dirname：处理文件路径

🔹3. 文本处理
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

🔹4. 压缩与解压
gzip / gunzip / zcat
bzip2 / bunzip2
xz / unxz / xzcat
zipinfo / unzip
tar：打包和解包
zstd / unzstd

🔹5. 系统与进程管理
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

🔹6. 网络命令
ping：测试网络连通性
curl / wcurl：请求 URL
ftp / telnet / tftp：网络工具
ifconfig / ip（取决于环境）：查看网络接口
netstat：网络连接
nsenter：进入命名空间

🔹7. 包管理 (Debian/Ubuntu/Termux)
apt / apt-get：安装/升级/卸载软件
apt-cache：查询包信息
dpkg：底层包管理
termux-change-repo：更换 Termux 源
termux-setup-storage：授权存储访问
termux-open / termux-open-url：在 Android 打开文件或 URL

🔹8. 加密/校验
md5sum / sha1sum / sha256sum：文件校验
base64 / base32：编码解码
xxhsum / b2sum：哈希算法

🔹9. 归档与备份
tar：打包压缩
zip / unzip：压缩解压
cpio / rsync（可能需要额外安装）

🔹10. 其他常用
date：显示/设置时间
cal：日历
whoami：显示当前用户
id：显示 UID/GID
chmod / chown / chgrp：修改权限
find：查找文件
xargs：参数传递
```

``` Text 
🟠 Shell 内建命令（bash 自带）

命令 说明
alias 定义命令别名
unalias 取消别名
bg 将任务放到后台运行
fg 将任务放到前台运行
jobs 查看后台任务
cd 切换目录
pwd 显示当前目录
echo 输出字符串
read 读取输入
history 查看命令历史
type 显示命令类型（内建/外部命令/别名）
help 显示内建命令帮助
export 设置环境变量
unset 删除变量
set 设置 shell 选项或显示所有变量
shopt 设置 bash 特性开关
let 计算算术表达式
eval 执行字符串命令
exec 替换当前进程执行新命令
exit 退出 shell
logout 退出登录 shell
return 从函数返回值
function 定义函数
readonly 设置变量只读
shift 移动位置参数
getopts 解析命令行选项
case … esac 条件匹配语句
if … then … fi 条件判断
for / while / until 循环结构
break 跳出循环
continue 跳过本次循环
time 统计命令执行时间
trap 捕捉信号执行命令
umask 设置默认权限掩码
ulimit 设置资源限制

🔹 文件与目录操作
命令 说明
ls 列出目录内容
cp 复制文件或目录
mv 移动/重命名文件
rm 删除文件
rmdir 删除空目录
mkdir 创建目录
stat 显示文件详细信息
basename 取文件名部分
dirname 取路径部分
realpath 显示文件的绝对路径
file 显示文件类型
touch 创建空文件/更新时间戳
find 搜索文件
namei 显示路径分解
readlink 显示符号链接指向
link 创建硬链接
ln 创建符号链接

🔹 文本处理
命令 说明
cat 显示文件内容
tac 倒序显示文件
head 查看文件前 N 行
tail 查看文件后 N 行
less 分页查看文件
more 分页查看文件（简化版）
strings 提取文件可打印字符（部分系统）
nl 给文件加行号
cut 按列切割文本
paste 按列合并文件
sort 排序
uniq 去重
wc 统计行数、字数、字节数
cmp 比较两个文件是否不同
diff 比较文件差异
comm 比较两个有序文件
tr 替换/删除字符
fold 按列数折行
fmt 文本重新排版
col 处理制表符/退格符
colrm 删除指定列
column 格式化为表格
rev 文本反转
od 按八进制/十六进制显示文件
hexdump 十六进制转储
strings 提取文件中的文本内容
grep 匹配文本
egrep 扩展正则匹配
fgrep 固定字符串匹配
zgrep 在压缩文件中 grep
```

``` Text 
🟡 压缩与解压

命令 说明
tar 打包/解包（支持 gzip、bzip2、xz、zstd 等）
gzip 压缩文件（生成 .gz）
gunzip 解压 .gz 文件
zcat 查看 .gz 文件内容
zgrep 在 .gz 文件中搜索
bzip2 压缩文件（生成 .bz2）
bunzip2 解压 .bz2 文件
bzcat 查看 .bz2 文件内容
bzgrep 在 .bz2 文件中搜索
bzcmp / bzdiff 比较压缩文件内容差异
bzip2recover 尝试恢复损坏的 .bz2 文件
xz 压缩文件（生成 .xz）
unxz 解压 .xz 文件
xzcat 查看 .xz 文件内容
xzgrep / xzfgrep / xzegrep 在 .xz 文件中搜索
xzcmp / xzdiff 比较 .xz 文件差异
lzma 旧版 LZMA 压缩
unlzma 解压 .lzma 文件
lzcat 查看 .lzma 文件内容
lzcmp / lzdiff 比较 .lzma 文件差异
lzgrep / lzegrep / lzfgrep 在 .lzma 文件中搜索
lzmore / lzless 分页查看 .lzma 文件
lzmainfo 显示 .lzma 文件信息
zstd 压缩文件（生成 .zst，Zstandard 算法）
unzstd / zstdcat 解压 .zst 文件 / 查看内容
zstdgrep 在 .zst 文件中搜索
zstdless 分页查看 .zst 文件
zstdmt 多线程压缩 .zst
zipinfo 查看 zip 文件信息
zipgrep 在 zip 文件中搜索
unzip 解压 zip 文件
unzipsfx zip 自解压可执行文件
funzip 从 zip 中直接解压单个文件到标准输出
gzexe 将可执行文件压缩并保持可执行
compress / uncompress 老式 .Z 压缩/解压（有些系统没有）
znew 把 .Z 文件转换为 .gz

⚡ 这一类命令主要用来处理 不同压缩格式：
- .gz → gzip/gunzip
- .bz2 → bzip2/bunzip2
- .xz → xz/unxz
- .lzma → lzma/unlzma
- .zst → zstd/unzstd
- .zip → zip/unzip

```

``` Text 
🟢系统与进程
主要用于查看、控制进程、系统状态和资源。

🔹 系统与进程管理命令
命令 说明
ps 显示进程信息
pstree 以树状结构显示进程
top 实时显示进程和资源使用情况
uptime 显示系统运行时间和负载
w 显示登录用户及其进程（有的系统才有）
whoami 显示当前用户
id 显示用户 UID/GID
groups 显示用户所属组
uname 显示系统信息
uname26 在 2.6 兼容模式下显示内核信息（特殊环境）
hostname 显示/设置主机名
dnsdomainname 显示 DNS 域名
uptime 显示开机时间与平均负载
vmstat 显示虚拟内存、CPU 使用情况
free 显示内存使用情况
df 显示磁盘分区空间
du 显示目录/文件大小
lsblk 显示块设备信息（部分环境才有）
lsfd 显示打开的文件描述符
lsipc 显示 System V IPC 资源
lsirq 显示中断请求 (IRQ) 信息
lsof 显示进程打开的文件
pmap 显示进程的内存映射
pwdx 显示进程工作目录
prlimit 显示/设置进程资源限制
taskset 设置/查看进程 CPU 绑定
nice 设置进程优先级
renice 调整已运行进程的优先级
kill 通过 PID 终止进程
killall 通过进程名终止进程
pkill 模糊匹配进程并终止
pgrep 查找进程 PID
wait 等待后台任务结束
waitpid 等待指定进程结束
disown 移除作业控制中的进程
nohup 使命令在退出终端后继续运行
fg 将后台作业调到前台
bg 让任务在后台运行
jobs 显示当前 shell 的作业
time 统计命令执行时间
times 显示当前 shell 的进程时间
stty 设置终端行属性
tty 显示当前终端设备
reset 重置终端
clear 清屏
script 记录终端会话
scriptreplay 回放终端会话
dmesg 查看内核启动和运行日志
sysctl 查看/设置内核参数
rtcwake 控制系统待机/唤醒（依赖硬件支持）

⚡ 这一类命令大多和 CPU / 内存 / 进程 / 内核 相关。在 Termux 里，有一些命令（比如 lsblk、uptime、vmstat）可能要额外安装 procps、util-linux 之类的软件包才有。
```

``` Text 
🔹 网络相关命令
包含常见网络调试、连接、配置工具
命令	说明
ping	测试网络连通性（ICMP 请求）
ping6	IPv6 版本的 ping
ifconfig	显示或配置网络接口（旧工具，已被 ip 替代）
ipmaddr	显示/修改多播地址
iptunnel	配置 IP 隧道
netstat	显示网络连接、路由、接口（旧工具，推荐用 ss）
route	显示/修改路由表
arp	显示/修改 ARP 缓存
rarp	反向 ARP
nsenter	进入指定进程的命名空间（网络、挂载、PID 等）
telnet	远程登录/测试端口连接
ftp	文件传输协议客户端
tftp	简单文件传输协议客户端
curl	HTTP/HTTPS 请求工具
wcurl	Termux 提供的简化版 curl
curl-config	显示 curl 配置选项
wget	下载文件（Termux 可能要安装）
logger	将消息写入系统日志（可用于远程 syslog）
hostname	显示或设置主机名
dnsdomainname	显示 DNS 域名
whoami	显示当前用户名（常用于网络认证脚本）
mcookie	生成随机认证 cookie（X 会话或 RPC 用）
ssh	远程登录（Termux 需安装 openssh）
scp	安全复制文件（基于 ssh）
sftp	安全文件传输（基于 ssh）
nc / netcat	网络调试工具，可建立 TCP/UDP 连接
nc.openbsd	OpenBSD 版本的 netcat
socat	高级 socket 工具（需安装）

⚡ 这些命令常用于：
•	网络诊断：ping, traceroute, netstat
•	远程访问：ssh, telnet
•	文件传输：ftp, sftp, scp, tftp, curl, wget
•	路由/接口管理：ifconfig, route, arp, ip* 系列
去除空行 呈现代码块
```
