# Unscure
> Bài này không có source

Mở trang web thì mình tới được trang login

![image](https://github.com/GermanyNghia/LIC-CTF/assets/111063228/6754f48e-0071-45f5-bcca-2dd4f7095b07)

Thường mọi người sẽ mặc định username là admin và kết hợp với password password123 (đề bài)
Login

![image](https://github.com/GermanyNghia/LIC-CTF/assets/111063228/80b0f4e7-6bae-4705-85a3-044766d6d266)

Mình đã bị điều hướng sang trang wikipedia nên sẽ thử lại bằng CMD

![image](https://github.com/GermanyNghia/LIC-CTF/assets/111063228/5ff03c96-6447-443e-9b4e-bba9c7f3d42d)

Có thể thấy được là trước khi bị điều hướng sang trang khác thì nó đã qua trang **there_might_be_a_flag_here**
Tiếp tục bằng cách đổi **http://{YOURURL}/login** thành **http://{YOURURL}/there_might_be_a_flag_here**

![image](https://github.com/GermanyNghia/LIC-CTF/assets/111063228/8fa696c5-0cfe-4948-a2b4-09222bc5f6d1)

Đổi tiếp

![image](https://github.com/GermanyNghia/LIC-CTF/assets/111063228/42aee498-7eff-4535-a304-8b8a5dad2110)

Sau đấy chỉ là điều hướng sang trang wike nên Flag là **LITCTF{0k4y_m4yb3_1_l13d}**


