# Screen
## Cài đặt screen trên Ubuntu 
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
## Một số lệnh cơ bản 
* **Tạo một session mới**

``` 
screen -S session_name
```
![new_ss](https://user-images.githubusercontent.com/63502091/163512855-87005076-dc74-4183-88d9-9dafbc1c734f.png)

* **Detach khỏi screen session**

```
screen + a d 
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

