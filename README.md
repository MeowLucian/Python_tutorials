# Python_tutorials

Python 程式設計筆記

## Add path

1. 進階系統設定

![進階系統設定](images/path/01.png?raw=true)

2. 進階 -> 環境變數

![進階系統設定](images/path/02.png?raw=true)

3. 變數 Path -> 編輯

![進階系統設定](images/path/03.png?raw=true)

4. 加入 Python, Scripts Path

```
路徑之間加 分號 ;
```

* C:\Program Files\Python36
* C:\Program Files\Python36\Scripts

![進階系統設定](images/path/04.png?raw=true)

## Virtual Environment

在 Python 虛擬環境可依資料夾各別建立不同版本的插件而不互相干擾

1. 建立新虛擬環境

```
python -m venv [name]
```

2. 列出已建立的虛擬環境

```
ls
```

3. 進入虛擬環境

```
.\[name]\Scripts\activate.bat
```

4. 退出虛擬環境

```
deactivate
```

## 安裝插件

```
pip install [name]
```

* 檢查版本

```
print([name].__version__)
```

## Jupyter notebook

1. 開啟 Jupyter notebook

進入合適資料夾

```
cd ~/[name]
```

```
Jupyter notebook
```

2. 退出 Jupyter notebook

關掉網頁後，在 Command Line 下指令：

```
Ctrl + C
```