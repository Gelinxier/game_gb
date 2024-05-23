# 五子棋

## 版本更新

### 1.0 版本 - 2024.5.23
- 实现五子棋的基础逻辑

#### 漏洞/未实现
1. 屏幕下满时，未实现平局判断逻辑
2. 白棋颜色实际上是蓝色，尚未修改

## 环境要求
- Python 3.7 及以上
- Pygame 2.5.2

## Windows 下转为 exe 文件

如果需要将项目转为 exe 文件，请按以下步骤操作：

1. 安装 PyInstaller:
    ```sh
    pip install pyinstaller
    ```
    **提示：** 如果网速太慢，可以切换成国内源来加速。

2. 在命令行中切换到项目文件所在的目录：
    ```sh
    cd 项目文件路径
    ```

3. 输入以下命令生成 exe 文件：
    ```sh
    pyinstaller -F -w -i xxxxxx.ico 五子棋.py
    ```
    - `xxxxxx.ico` 可以自行修改，放入同一目录下即可。

4. 等待生成过程完成。

## 联系方式
如有任何问题或建议，请提交 Issue 或与我联系。

---

感谢您的使用与支持！