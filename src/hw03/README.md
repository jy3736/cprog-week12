## 依指定資料寬度及每一行(row)的列數(col)輸出陣列。

### Test in Windows

```shell
hw03> echo 1 2 3 4 5 6 7 8 9 0 1 2 3 4 5 6 | .\main.exe
    1    2    3    4    5
    6    7    8    9    0
    1    2    3    4    5
    6

         1         2         3         4         5
         6         7         8         9         0
         1         2         3         4         5
         6

         1         2         3
         4         5         6
         7         8         9
         0         1         2
         3         4         5
         6
         
hw03> python ..\..\tools\check03.py
測試通過!

   23   81   55   68   33
   20   18   87   45   61
   94

        23        81        55        68        33
        20        18        87        45        61
        94

        23        81        55
        68        33        20
        18        87        45
        61        94
````