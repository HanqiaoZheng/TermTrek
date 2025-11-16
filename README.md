# TermTrek
终端小游戏(Terminal Mini Game)
支持bash,cmd

使用pyinstaller进行打包


# 运行
直接执行可执行文件
- windows cmd
```bash
./dist/term_trek.exe
```
- linux bash
```bash
./dist/term_trek
```


# 开发
使用uv管理虚拟环境
1. 创建虚拟环境
```bash
uv venv --python 3.12
```

2. 同步环境
```bash
uv sync
```

3. 执行
```bash
python main.py
```

4. 打包
linux直接执行，windows可以用git bash
```bash
sh build.sh
```