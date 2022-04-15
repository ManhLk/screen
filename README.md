# Screen
## 1. Cài đặt screen trên Ubuntu 
* **Sử dụng lệnh sau để cài đặt screen trên Ubuntu:**

```
sudo apt update
sudo apt install screen
```

* **Sau khi cài đặt xong, ta sử dụng lệnh sau để kiểm tra version của screen đã được cài đặt:**

```
screen --version 
```
Kết quả như hình dưới đây:

![screen_version](https://user-images.githubusercontent.com/63502091/163511423-cfe7b533-bf83-4e0b-8aef-f12523f04796.png)
## 2. Một số lệnh cơ bản 
* **Tạo một session mới**

``` 
screen -S session_name
```
![new_ss](https://user-images.githubusercontent.com/63502091/163512855-87005076-dc74-4183-88d9-9dafbc1c734f.png)

* **Detach khỏi screen session**

```
Ctrl + a d 
```
* **Xem danh sách các screen đang chạy**

```
screen -ls 
```

Kết quả như hình dưới đây:

![list](https://user-images.githubusercontent.com/63502091/163513622-106f15c0-6af1-48c2-b428-23c6895f8af2.png)

* **Attach vào session đang chạy ngầm**

```
screen -x session_name 
``` 

Ví dụ như hình dưới:

![attach](https://user-images.githubusercontent.com/63502091/163514019-2bd5b481-e682-4348-9c9d-6982ffe18e51.png)

* **Kill session**

```
screen -S session_name -X quit
```

Kết quả như hình dưới:

![kill](https://user-images.githubusercontent.com/63502091/163514466-21420e30-033b-412a-8159-abe5abf66d74.png)

## 3. Một số lệnh tham khảo thêm 
* **Tạo một cửa sổ mới trong session**

```
Ctrl + a c
```

* **List các cửa sổ (window) trong session**

```
Ctrl + a "
```

* **Chuyển đổi (switch) tới cửa sổ 0 (by number)**

```
Ctrl + a 0
```

* **Đổi tên cửa sổ (window) hiện tại**

```
Ctrl + a A
```

* **Chia cửa sổ (window) theo chiều ngang**

```
Ctrl + a S
```

* **Chia cửa sổ (window) theo chiều dọc**

```
Ctrl + a |
```

* **Di chuyển giữa các vùng được chia**

```
Ctrl + a tab 
```

* **Đóng tất cả các vùng được chia**

```
Ctrl + a Q
```

* **Đóng vùng hiện tại**

```
Ctrl + a X
```
