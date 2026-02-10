# Cách khai báo hoàn thuế cho người làm thêm bằng Moneyforward

## 1. Các công việc cần làm khi bắt đầu làm thêm
+ Đăng kí thẻ mynumber
+ Đăng kí 個人情報
  + Sau khi đăng kí sẽ được nhận giấy chứng nhận mở 事業 có đóng dấu, ko phát lại và giấy này sẽ còn dùng trong chương sau, nên scan luôn 1 bản mềm phòng thân.
+ Đăng kí 青色申告承認申請書
+ Download app Moneyforward ME
+ Download app Moneyforward tax-return
+ Đăng kí tài khoản moneyforward (miễn phí)

## 2. Quá trình tiêu thụ
Tối thiểu cần liên kết 2 tài khoản với Moneyforward ME: Tài khoản ngân hàng nhận tiền 売上 và thẻ tín dụng dùng chi trả cho mục đích khấu trừ thuế.  
Nếu mua nhiều trên amazon hay shop khác thì liên kết thêm sẽ tiện hơn (nhưng ko bắt buộc).
Mỗi khi tiêu cần làm 2 thao tác cho giao dịch:
+ Tick 確定申告
+ Set category cho giao dịch (nếu ko tự động được set chính xác)
<img width="922" height="2048" alt="image" src="https://github.com/user-attachments/assets/f504a44c-f401-4204-a4c8-b43a2ce371ab" />

Các category nên sử dụng:
| Mục đích | MF ME Category | 仕分け項目 (tự động map_ |
| --- | --- | --- |
| Đi ăn uống với người khác | 飲み会 | 接待交際費 |
| Mua đồ liên quan tới công việc | 特別な支出 | 消耗品費 |
| Thu nhập | 事業・副業 | 売上 |

Ngoài ra còn có tiền đi lại, thuê nhà, tiền điện, mấy cái này category quá rõ rồi, thường là MF ME cũng tự mapping được mà không cần chỉnh.
Chú ý là chi phí ăn phải chọn nomikai, nếu chọn mục ăn uống sẽ bị mapping vào phần tiền họp (bản chất là đi họp/hội nghị ra nghỉ trưa ăn trưa thì mới tính vào cái này)

Đối với thiết bị trên 10 man thì không được tick 確定申告 mà sẽ cần khai báo thủ công (sẽ nói ở phần dưới).

Nên sử dụng các loại thẻ có dữ liệu nhanh như thẻ Kyash, chứ dùng thẻ credit thường phải 3 ngày mới có data thì dễ quên.

## 3. Khai báo thuế
1. Lên myportal vào phần Advance Preparation of Final Tax Returns rồi liên kết hết các loại có thể loại có thể liên kết được.
2. Lên [Moneyforward](https://erp.moneyforward.com/) xúc 1 gói personal mini (dùng xong thì 解約 luôn)
3. Lên [Moneyforward accounting](https://accounting.moneyforward.com/) khởi tạo 年度, xong vào 20XX年度確定申告
4. Nhập thông tin cơ bản, phần 申告区分 nhớ chọn 青色申告. Phần 提出方法 chọn スマホアプリで提出（電子申告）. Phần 青色申告特別控除 chọn 65万円.  
  Lần đầu có thể cần vào etax lấy mã số thuế để điền.
5. Mở app điện thoại Moneyforward tax-return ra, chọn liên kết MF ME rồi lấy data từ MF ME.
6. Nếu có mua đồ trên 10man thì vào [固定資産](https://accounting.moneyforward.com/fixed_assets/new) đăng kí.  
  1 năm có thể có 1 đồ trị giá 10万〜30万円 có thể chọn 償却方法: 即時償却, phần 今期償却額 điền luôn giá tiền.  
  Đối với đồ khác (trên 30万 hoặc đồ thứ 2 trên 10万) thì chọn 一括償却. Phần 今期償却額 tính bằng `(giá tiền)/耐用年数/12*(số tháng sử dụng trong năm)`. (chả biết sao con app này ko tính hộ cho luôn).  
  Tạo xong là sẽ thấy có 仕訳 tự động được đẻ ra. Với những đồ 一括償却 thì năm sau sẽ tự đẻ tiếp 仕訳.  
7. Vào [家事按分](https://accounting.moneyforward.com/home_devotes), tạo 水道光熱費 và 地代家賃 (nếu thuê nhà). Chọn tỉ lệ 50%. Chọn xong ấn 一括仕訳登録.  
  Tới đây là xong phần khai báo 青色申告 để đủ điều kiện khấu trừ thuế 65万円. Tiếp đó là làm 確定申告 như bình thường.
8. Vào liên kết với mynumber, điền nốt phần dữ liệu chưa được liên kết.  
  Nếu không lấy được thông tin furusato từ mynumber thì tự lên trang shop down file xml về up lên là được.  
  Tương lai thì chắc liên kết mynumber là sẽ đồng bộ được hết dữ liệu từ 源泉所得, y tế, furusato, vay mua nhà, bảo hiểm, shoken,... etc nên chả phải điền gì nữa.
9. Xong thì mở app Moneyforward tax-return ra bấm submit tax-return là xong.

Thường thì tháng 4 sẽ có tiền về tài khoản. (nếu được hoàn thuế)
Nếu thu nhập ngoài (ko tính đầu tư) lớn hơn 1000万円 thì cần khai báo thuế tiêu thụ nữa, nhưng tác giả chưa kiếm được tới mức ấy nên chưa có kinh nghiệm, bao giờ kiếm được sẽ lên bài 😂
