# NapThe_PMMP

# Các web có thể sử dụng:
+ thesieure.com
+ trumthe.vn
+ doithengay.com
+ naptudong.com
+ đang cập nhật...

# Tính năng:
+ Lưu lại thẻ nếu thẻ đúng khi thẻ đang ở trạng thái đang xử lý (Người chơi offline)
+ Form giúp dễ dàng nhập thẻ
+ Config

# Lưu ý:
- Bạn cần cài [FormAPI](https://github.com/jojoe77777/FormAPI) trước khi sử dụng

# Config example
```
#trumthe.vn | thesieure.com | doithengay.com | naptudong.com

driver: "thesieure.com"

partner_key: "" #Do web cung cấp

partner_id: "" #Do web cung cấp

ratio: 1000 #1.000VND = 1 xu

bonus: 1.5 # khuyến mãi 50%

commands:
 - give {player} diamond {money}
 - givemoney {player} {money} 
```
