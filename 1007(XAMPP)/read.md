

## 安裝XAMPP
![a.png](a.png)
# 安裝位置在C: 且目錄下共有5個執行檔 上圖連結為xampp-control.exe
![d.png](d.png)

# 以下程式碼在使用中文時會產生亂碼，原因是編碼。
```

<!DOCTYPE html>
<html>
<head>
    <title>Pooh Heeee!</title>
</head>
<body>

<h1>Haachamachama</h1>

<h9>哈洽馬洽馬洽馬</h9>
</body>
</html>

```
![b.png](b.png)
# 加入<meta charset="utf-8">後可將編碼改為utf-8，如圖，此編碼支援中文。
# 即便在文字(h9)後也依然可行。
```
<!DOCTYPE html>
<html>
<head>
    <title>Pooh Heeee!</title>
</head>
<body>

<h1>Haachamachama</h1>

<h9>哈洽馬洽馬洽馬</h9>
<meta charset="utf-8">
</body>
</html>

```
![c.png](c.png)

