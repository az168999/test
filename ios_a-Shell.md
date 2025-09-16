# 命令中文注释表

> 本文档整理了常用命令及工具的中文注释，按字母顺序排列。

---
## A–C 部分（到 cp）

| 命令        | 中文注释 |
|-------------|----------|
| .pkg.swp    | Vim 编辑 `.pkg` 文件时产生的交换文件（临时文件，用于崩溃恢复） |
| 2to3        | Python 2 代码自动转换为 Python 3 工具 |
| 2to3-3.11   | 与 `2to3` 相同，指定 Python 3.11 版本使用 |
| alias       | 创建命令别名 |
| amstex      | TeX 排版系统的数学增强版本 |
| apropos     | 在手册页（man page）中搜索关键字 |
| ar          | 创建、修改、提取归档文件（常用于 `.a` 静态库） |
| awk         | 强大的文本处理工具，支持模式匹配与报表生成 |
| base64      | 进行 Base64 编码与解码 |
| basename    | 提取路径的最后部分（去掉目录部分） |
| bc          | 命令行计算器，支持高精度运算 |
| bibtex      | TeX 排版系统的参考文献工具 |
| blink       | 浏览器或终端闪烁测试命令（依环境而定） |
| bokeh       | Python 数据可视化库的命令行工具 |
| bookmark    | 浏览器或终端中用于保存书签的命令（依环境而定） |
| brave       | 调用 Brave 浏览器 |
| calc        | 命令行计算器（部分系统内置） |
| call        | 在脚本或批处理里调用另一个命令 |
| cat         | 连接文件并输出内容 |
| cd          | 切换当前目录 |
| chflags     | 修改文件/目录的标志位（macOS 常见，如 `hidden`） |
| chmod       | 修改文件或目录的权限 |
| cksum       | 计算文件的校验和（CRC） |
| clang       | C 语言编译器（LLVM 项目） |
| clang++     | C++ 编译器（LLVM 项目） |
| clear       | 清屏 |
| compare     | 图像比较（ImageMagick 工具） |
| composite   | 图像叠加合成（ImageMagick 工具） |
| compress    | 文件压缩工具（传统 UNIX） |
| config      | 配置工具（依环境可能指 Python、Node、系统配置等） |
| conjure     | ImageMagick 脚本解释器 |
| convert     | 图像格式转换（ImageMagick 核心命令） |
| corelist    | Perl 工具，查看模块是否存在于核心发行版 |
| cowsay      | 终端小工具，显示一只会说话的 ASCII 牛 |
| cp          | 复制文件或目录 |

## C–L 段（从 cpan 到 ls）

| 命令             | 中文注释 |
|------------------|----------|
| cpan             | Perl 的 CPAN 模块安装工具 |
| credits          | 显示 Python 交互解释器的鸣谢信息 |
| cslatex          | 基于 LaTeX 的捷克语/斯洛伐克语支持 |
| csplain          | TeX 的捷克语/斯洛伐克语支持版本 |
| ctags.wasm3      | WebAssembly 版本的 ctags，生成代码标签索引 |
| curl             | 用于发送 HTTP/FTP 等网络请求的命令行工具 |
| cygdb            | Cython 调试工具，集成 GDB |
| cython           | 将 Python 代码编译为 C/C++ 扩展模块的工具 |
| cythonize        | 批量编译 Cython 源文件的命令 |
| dash             | 一种轻量级 POSIX shell（比 bash 更快） |
| date             | 显示或设置系统日期时间 |
| dc               | 命令行逆波兰记法计算器 |
| deactivate       | 退出 Python 虚拟环境的命令 |
| deletemark       | 删除标记（具体依赖环境，可能是编辑器相关） |
| diff             | 比较文件内容差异 |
| dig              | DNS 查询工具，比 nslookup 功能更强 |
| dirname          | 提取路径中的目录部分 |
| distro           | Python 库 `distro` 的命令行工具，查看 Linux 发行版信息 |
| docutils         | Python 文档处理工具包（RST 转换） |
| downloadFile     | 下载文件的命令（环境相关，非标准 UNIX 命令） |
| downloadFolder   | 下载文件夹的命令（环境相关） |
| du               | 显示文件或目录的磁盘使用情况 |
| dvilualatex      | 使用 LuaLaTeX 生成 DVI 文件 |
| dviluatex        | 使用 LuaTeX 生成 DVI 文件 |
| dvipdfmx         | 将 DVI 文件转换为 PDF |
| ebong            | 用于生成测试文档的工具（依赖环境） |
| echo             | 输出字符串到终端 |
| ed               | 最早的 UNIX 文本编辑器 |
| egrep            | 扩展正则表达式匹配（相当于 `grep -E`） |
| enc2xs           | Perl 工具，用于生成编码转换模块 |
| encguess         | 猜测文本编码格式的工具 |
| env              | 显示或设置环境变量 |
| eplain           | TeX 的扩展宏包 |
| etex             | 增强版 TeX 引擎 |
| euptex           | 支持日文处理的 Unicode pTeX 引擎 |
| exit             | 退出当前 shell |
| export           | 设置并导出环境变量 |
| expr             | 计算表达式（算术或字符串操作） |
| f2py             | Fortran 与 Python 接口生成工具 |
| f2py3            | 与 f2py 相同，指定 Python3 使用 |
| f2py3.11         | 与 f2py 相同，指定 Python3.11 使用 |
| ffmpeg           | 功能强大的音视频处理工具 |
| ffprobe          | 获取音视频文件的详细信息 |
| fgrep            | 匹配固定字符串（相当于 `grep -F`） |
| file.wasm3       | WebAssembly 版本的 file 命令，用于识别文件类型 |
| find             | 在目录树中查找文件 |
| fio              | 磁盘 I/O 性能测试工具 |
| firefox          | 调用 Firefox 浏览器 |
| fits2bitmap      | 将 FITS 天文数据文件转换为位图 |
| fitscheck        | 检查 FITS 文件的标准兼容性 |
| fitsdiff         | 比较两个 FITS 文件的差异 |
| fitsheader       | 显示 FITS 文件的头信息 |
| fitsinfo         | 显示 FITS 文件的内容概要 |
| fmtutil          | TeX 工具，管理格式文件 |
| fmtutil-sys      | 系统级 fmtutil |
| fonttools        | Python 字体处理工具 |
| googlechrome     | 调用 Google Chrome 浏览器 |
| grep             | 文本搜索工具，支持正则匹配 |
| gunzip           | 解压 `.gz` 文件 |
| gzip             | 压缩文件为 `.gz` 格式 |
| h2ph             | Perl 工具，将 C 头文件转换为 Perl 模块 |
| h2xs             | Perl 工具，从 C 头文件生成 Perl 扩展模块 |
| head             | 显示文件开头几行 |
| help             | shell 内置命令，查看帮助信息 |
| hideKeyboard     | 隐藏键盘（移动端或 GUI 环境相关） |
| hideToolbar      | 隐藏工具栏（环境相关） |
| history          | 显示命令历史记录 |
| host             | DNS 查询工具 |
| httpx            | Python HTTP 客户端库的命令行工具 |
| id               | 显示用户 UID、GID 等身份信息 |
| identify         | ImageMagick 工具，显示图像信息 |
| idle3            | Python 3 自带的图形交互开发环境 |
| idle3.11         | Python 3.11 对应的 IDLE |
| ifconfig         | 显示或配置网络接口（较旧命令，Linux 现多用 ip） |
| import           | 截屏工具（ImageMagick 的命令） |
| instmodsh        | Perl 工具，交互式查看已安装模块 |
| internalbrowser  | 内部浏览器（具体依赖环境） |
| ipython          | 交互式 Python Shell |
| ipython3         | Python3 版本的 IPython |
| isForeground     | 检查进程是否在前台（环境相关） |
| isympy           | SymPy 的交互式命令行工具 |
| jadetex          | TeX 宏包，支持 Jade DSSSL 文档转换 |
| jlpm             | JupyterLab 的 Yarn 包管理封装命令 |
| jq               | 命令行 JSON 处理工具 |
| jsc              | JavaScriptCore 引擎（WebKit）命令行工具 |
| jsc_core         | JavaScriptCore 的核心命令行接口 |
| jsi              | JavaScript 接口工具（依环境而定） |
| json_pp          | JSON 格式化工具（pretty print） |
| jsonpointer      | JSON Pointer 工具 |
| jsonschema       | JSON Schema 校验工具 |
| jump             | 快速跳转目录的命令（依赖环境） |
| jupyter          | Jupyter 项目的统一入口命令 |
| jupyter-bundlerextension | 管理 Jupyter Bundler 扩展 |
| jupyter-console  | Jupyter 交互式终端 |
| jupyter-contrib  | Jupyter 社区贡献扩展 |
| jupyter-dejavu   | Jupyter 相关扩展（具体依赖版本） |
| jupyter-events   | Jupyter 事件管理工具 |
| jupyter-execute  | 执行 Jupyter Notebook 单元格的工具 |
| jupyter-kernel   | Jupyter 内核管理工具 |
| jupyter-kernelspec | 管理 Jupyter 内核规范 |
| jupyter-lab      | 启动 JupyterLab 界面 |
| jupyter-labextension | 管理 JupyterLab 扩展 |
| jupyter-labhub   | JupyterLab 与 Hub 集成 |
| jupyter-migrate  | 升级/迁移 Jupyter 配置 |
| jupyter-nbclassic | 经典 Jupyter Notebook 界面 |
| jupyter-nbclassic-bundlerextension | Notebook 经典界面的打包扩展 |
| jupyter-nbclassic-extension | Notebook 经典扩展 |
| jupyter-nbclassic-serverextension | Notebook 经典服务器扩展 |
| jupyter-nbconvert | 将 Notebook 转换为 HTML、PDF 等格式 |
| jupyter-nbextension | 管理 Notebook 扩展 |
| jupyter-nbextensions_configurator | Notebook 扩展配置器 |
| jupyter-notebook | 启动 Jupyter Notebook |
| jupyter-qtconsole | Jupyter Qt 图形终端 |
| jupyter-run      | 在 Jupyter 内运行脚本 |
| jupyter-server   | 启动 Jupyter Server |
| jupyter-serverextension | Jupyter Server 扩展管理 |
| jupyter-troubleshoot | Jupyter 故障排查工具 |
| jupyter-trust    | 信任 Jupyter Notebook（执行已保存的输出） |
| keepDirectoryAfterShortcut | 保持目录（依环境） |
| kpsewhich        | TeX 工具，查找文件位置 |
| l4p-tmpl         | Perl Log::Log4perl 模块相关工具 |
| latex            | 使用 LaTeX 引擎编译 `.tex` 文件 |
| ld               | GNU 链接器 |
| ld.lld           | LLVM 的链接器 |
| ld64.lld         | macOS 平台 LLVM 链接器 |
| less             | 分页查看文本内容 |
| lessecho         | less 工具的辅助命令 |
| lex              | 词法分析器生成工具 |
| lg2              | libgit2 提供的 Git 命令行接口 |
| libnetcfg        | Perl 工具，配置网络库 |
| link             | 创建硬链接 |
| llc              | LLVM 编译器后端，生成汇编代码 |
| lld              | LLVM 链接器 |
| lld-link         | Windows 兼容的 LLVM 链接器 |
| lli              | LLVM 解释器，直接执行 LLVM IR |
| llvm-dis         | LLVM IR 反汇编工具 |
| llvm-link        | 链接多个 LLVM 位码文件 |
| ln               | 创建符号链接或硬链接 |
| ls               | 列出目录内容 |

## M–P 段（从 lua 到 prove）

| 命令           | 中文注释 |
|----------------|----------|
| lua            | Lua 脚本语言解释器 |
| luac           | Lua 字节码编译器 |
| luahbtex       | 支持 HarfBuzz 字体渲染的 LuaTeX 引擎 |
| lualatex       | 使用 LuaTeX 引擎编译 LaTeX 文档 |
| luatex         | Lua 支持的 TeX 引擎 |
| magick         | ImageMagick 主命令入口 |
| magick-script  | ImageMagick 脚本执行器 |
| make           | 构建工具，根据 Makefile 自动编译项目 |
| makeindex      | TeX 工具，生成索引文件 |
| man            | 查看命令的手册页 |
| mandoc         | 格式化并显示 man 文档的工具 |
| mandocdb       | 为 man 页面建立索引数据库 |
| md5            | 计算 MD5 哈希值 |
| mercantile     | Python mercantile 库的命令行工具（切片地图坐标转换） |
| meson          | 现代化构建系统（比 CMake 更快更简洁） |
| mex            | MATLAB 的 MEX 文件编译器 |
| mkdir          | 创建目录 |
| mktemp         | 创建临时文件或目录 |
| mktexfmt       | 生成 TeX 格式文件 |
| mktexlsr       | 刷新 TeX 文件数据库 |
| mllatex        | LaTeX 的多语言版本 |
| mltex          | TeX 的多语言扩展 |
| mogrify        | ImageMagick 工具，批量修改图像 |
| montage        | ImageMagick 工具，将多张图片拼接成一张 |
| more           | 分页显示文件内容 |
| multimarkdown  | Markdown 扩展版转换器 |
| mv             | 移动或重命名文件/目录 |
| nc             | netcat，网络调试与数据传输工具 |
| newWindow      | 打开新窗口（环境相关） |
| nltk           | Python NLTK 自然语言处理工具的命令行接口 |
| normalizer     | 文本正则化工具（依赖环境） |
| nslookup       | DNS 查询工具 |
| open           | macOS 下打开文件或应用程序 |
| openurl        | 打开指定 URL（环境相关） |
| opera          | 调用 Opera 浏览器 |
| opt            | LLVM 优化器 |
| pbcopy         | macOS 下复制内容到剪贴板 |
| pbpaste        | macOS 下从剪贴板粘贴内容 |
| pdfcslatex     | 使用 pdfLaTeX 的捷克语/斯洛伐克语支持 |
| pdfcsplain     | pdfTeX 的捷克语/斯洛伐克语支持版本 |
| pdfetex        | 增强版 pdfTeX 引擎 |
| pdfjadetex     | JadeTeX 的 PDF 输出版本 |
| pdflatex       | 使用 pdfTeX 引擎编译 LaTeX 文档 |
| pdfmex         | pdfTeX 的多语言扩展版本 |
| pdftex         | TeX 引擎，直接生成 PDF |
| pdfxmltex      | XMLTeX 的 PDF 输出版本 |
| perl           | Perl 语言解释器 |
| perl5          | Perl5 的别名 |
| perlbug        | 报告 Perl 错误的工具 |
| perldoc        | 查看 Perl 文档 |
| perlivp        | 检查 Perl 安装完整性的工具 |
| pickFolder     | 选择文件夹（环境相关命令） |
| pico           | 简单的命令行文本编辑器 |
| piconv         | Perl 工具，进行字符编码转换 |
| ping           | 网络连通性测试命令 |
| ping6          | IPv6 网络连通性测试命令 |
| pip            | Python 包管理器 |
| pip3           | Python3 的 pip |
| pip3.10        | Python 3.10 的 pip |
| pip3.11        | Python 3.11 的 pip |
| pkg            | 软件打包工具（依系统不同含义不同） |
| pl2pm          | 将 Perl 脚本转换为模块的工具 |
| play           | 播放音频或视频（依赖环境，可能为 SoX 的命令） |
| pod2html       | 将 Perl POD 文档转换为 HTML |
| printenv       | 打印环境变量 |
| prove          | Perl 测试框架命令，运行测试文件 |

## P–R 段（从 ptar 到 rstpep2html.py）

| 命令                  | 中文注释 |
|-----------------------|----------|
| ptar                  | Perl 工具，用于打包/解包 tar 归档文件 |
| ptardiff              | Perl 工具，比较 tar 包内容的差异 |
| ptargrep              | 在 tar 包中搜索文件内容 |
| pwd                   | 显示当前工作目录 |
| pybabel               | Python Babel 国际化工具的命令行接口 |
| pybind11-config       | Pybind11 C++/Python 绑定工具的配置查询 |
| pydoc3                | Python3 文档工具，生成和查看模块文档 |
| pydoc3.11             | Python 3.11 版本的文档工具 |
| pyftmerge             | 字体工具，合并字体文件 |
| pyftsubset            | 字体工具，提取子集字体 |
| pygmentize            | 语法高亮工具（Pygments 库命令行接口） |
| pyjson5               | Python JSON5 解析器命令行接口 |
| pyproj                | 地理坐标转换工具（基于 PROJ 库） |
| python                | Python 语言解释器 |
| python3               | Python3 解释器 |
| python3-config        | Python3 配置查询（编译扩展时使用） |
| python3.11            | Python 3.11 解释器 |
| python3.11-config     | Python 3.11 配置查询 |
| python3.9             | Python 3.9 解释器 |
| qtpy                  | Python Qt 封装库的命令行接口 |
| ranlib                | 生成静态库索引（与 `ar` 搭配使用） |
| readlink              | 显示符号链接所指向的路径 |
| readtags.wasm3        | WebAssembly 版本的 readtags 工具 |
| realpath              | 显示文件的绝对路径 |
| rehash                | 刷新 shell 的命令查找哈希表 |
| renamemark            | 重命名标记（环境相关，可能是编辑器命令） |
| repeatCommand         | 重复执行上一条命令（环境相关） |
| rio                   | RIO 工具（依环境不同，可能为数据流或远程 IO 工具） |
| rlogin                | 远程登录命令（早期 UNIX 工具，现多用 ssh） |
| rm                    | 删除文件 |
| rmdir                 | 删除空目录 |
| rst2html.py           | 将 reStructuredText 转换为 HTML |
| rst2html4.py          | 将 reStructuredText 转换为 HTML4 |
| rst2html5.py          | 将 reStructuredText 转换为 HTML5 |
| rst2latex.py          | 将 reStructuredText 转换为 LaTeX |
| rst2man.py            | 将 reStructuredText 转换为 man 页面 |
| rst2odt.py            | 将 reStructuredText 转换为 ODT 文档 |
| rst2odt_prepstyles.py | 为 ODT 文档生成样式表（辅助命令） |
| rst2pseudoxml.py      | 将 reStructuredText 转换为伪 XML 格式（调试用） |
| rst2s5.py             | 将 reStructuredText 转换为 S5 幻灯片 |
| rst2xetex.py          | 将 reStructuredText 转换为 XeTeX |
| rst2xml.py            | 将 reStructuredText 转换为 XML |
| rstpep2html.py        | 将 reStructuredText 格式的 PEP 转换为 HTML |

## S–T 段（从 safari 到 ttx）

| 命令        | 中文注释 |
|-------------|----------|
| safari      | 打开 Safari 浏览器（macOS 专用） |
| say         | 将文本转为语音朗读（macOS TTS 命令） |
| scp         | 安全复制文件（基于 SSH 的远程文件传输） |
| script      | 记录终端会话到文件 |
| scriptreplay| 回放 `script` 命令录制的终端会话 |
| sdiff       | 并排比较两个文件的差异 |
| seaf-cli    | Seafile 云存储命令行客户端 |
| seaf-fsck   | 检查和修复 Seafile 文件系统完整性 |
| seaf-fuse   | 使用 FUSE 挂载 Seafile 文件系统 |
| seaf-gc     | 清理 Seafile 数据库中的垃圾文件 |
| seaf-fsck   | 校验 Seafile 数据一致性 |
| seaf-server | 启动 Seafile 服务器 |
| sed         | 流编辑器，用于文本替换、过滤与处理 |
| seq         | 生成数字序列 |
| setfile     | 修改 macOS 文件元数据（如文件类型、创建日期） |
| sftp        | 安全文件传输协议客户端（基于 SSH） |
| sh          | Bourne shell 解释器 |
| sha1sum     | 生成/校验 SHA-1 哈希值 |
| sha224sum   | 生成/校验 SHA-224 哈希值 |
| sha256sum   | 生成/校验 SHA-256 哈希值 |
| sha384sum   | 生成/校验 SHA-384 哈希值 |
| sha512sum   | 生成/校验 SHA-512 哈希值 |
| shred       | 安全删除文件（覆盖多次以防恢复） |
| shuf        | 随机打乱文件中的行或生成随机数 |
| shutdown    | 关闭或重启系统 |
| sips        | macOS 图像处理工具（可调整大小、格式转换） |
| sleep       | 暂停指定时间（秒） |
| sort        | 排序文本行 |
| source      | 在当前 shell 环境中执行脚本 |
| split       | 将文件分割成多个小文件 |
| sqlite3     | SQLite 数据库命令行工具 |
| ssltap      | SSL/TLS 测试工具 |
| stat        | 显示文件详细信息（大小、权限、时间戳等） |
| stdbuf      | 修改命令的标准输入输出缓冲方式 |
| strings     | 提取二进制文件中的可打印字符串 |
| strip       | 删除二进制文件中的符号表（减小体积） |
| stty        | 设置/显示终端行属性 |
| su          | 切换用户身份（superuser） |
| sum         | 计算文件校验和与块数 |
| sw_vers     | 显示 macOS 系统版本信息 |
| sysctl      | 查看和设置内核参数 |
| system_profiler | 显示 macOS 硬件和软件信息 |
| tac         | 反向显示文件内容（行倒序） |
| tail        | 显示文件结尾部分 |
| tar         | 打包/解包归档文件 |
| tee         | 从标准输入读取数据并写入文件，同时输出到终端 |
| test        | 测试表达式（条件判断） |
| tftp        | 简单文件传输协议客户端 |
| time        | 测量命令的执行时间 |
| timeout     | 在指定时间后中断命令执行 |
| top         | 动态显示系统进程信息 |
| touch       | 创建空文件或修改文件时间戳 |
| tput        | 终端控制工具（光标、颜色、模式等） |
| tr          | 替换或删除字符 |
| true        | 返回成功状态（0），什么也不做 |
| truncate    | 缩短或扩展文件大小 |
| tsc         | TypeScript 编译器 |
| tscd        | TypeScript 守护进程编译器 |
| tset        | 初始化终端设置 |
| tty         | 显示当前终端设备名称 |
| ttx         | 字体工具（TrueType/XML 转换器） |

## U–Z 段（从 unalias 到 zipdetails）

| 命令                  | 中文注释 |
|-----------------------|----------|
| unalias               | 删除命令别名 |
| uname                 | 显示系统信息（内核名称、版本、架构等） |
| uncompress            | 解压 `.Z` 文件（旧 UNIX 压缩格式） |
| uniq                  | 去除重复行（常与 sort 配合使用） |
| unlink                | 删除文件（单独删除，不适用目录） |
| unrar                 | 解压 RAR 文件 |
| unsetenv              | 删除环境变量（csh/tcsh） |
| updateCommands        | 刷新系统或环境的命令索引（环境相关） |
| updmap                | TeX 工具，更新字体映射 |
| updmap-sys            | 系统级 TeX 字体映射更新 |
| uplatex               | 日本 Unicode LaTeX 引擎 |
| uptex                 | 日本 TeX 引擎，支持多字节字符 |
| uptime                | 显示系统运行时间和负载 |
| utf8mex               | TeX/LaTeX UTF-8 扩展工具 |
| versioneer            | Python 工具，用于自动管理版本号 |
| view                  | 用于查看文件（vi 的只读模式） |
| vim                   | 高级文本编辑器（vi 改进版） |
| volint                | 体积积分工具（依环境，可能用于计算三维数据体积） |
| wasm                  | WebAssembly 工具入口 |
| wasm-ld               | WebAssembly 链接器 |
| wasm3                 | WebAssembly 解释器 |
| wc                    | 统计文件的行数、字数、字符数 |
| wcslint               | 字符串或代码的语法检查（依环境） |
| whatis                | 显示命令简要说明 |
| wheel                 | Python 打包工具，管理 `.whl` 文件 |
| whoami                | 显示当前用户 |
| whois                 | 查询域名或 IP 的注册信息 |
| wol                   | Wake-on-LAN 网络唤醒工具 |
| wordcloud_cli         | Python 词云生成命令行工具 |
| wsdump                | WebSocket 测试工具 |
| xargs                 | 将输入转换为命令行参数执行 |
| xcode-select          | macOS Xcode 工具链选择管理 |
| xdvipdfmx             | 将 XeTeX DVI 文件转换为 PDF |
| xelatex               | 使用 XeTeX 编译 LaTeX 文档 |
| xetex                 | XeTeX 引擎 |
| xmltex                | XMLTeX 引擎 |
| xsubpp                | Perl 工具，处理 XS 模块接口 |
| xxd                   | 二进制文件转十六进制显示/编辑 |
| xz.wasm3              | WebAssembly 版本的 xz 压缩工具 |
| xzdec.wasm3           | WebAssembly 版本的 xz 解压工具 |
| yandexbrowser         | 调用 Yandex 浏览器 |
| z                     | 快速跳转目录工具（目录导航工具） |
| zipdetails            | 查看 ZIP 文件详细信息 |

