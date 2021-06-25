# Kinh nghiệm tính toán liên quan tới giảm thuế
## Đăng kí phụ thuộc được giảm bao nhiêu tiền thuế
Để tính chính xác thì bạn cần có 源泉徴収票 của năm mình muốn tính.
Có thể kiểm tra bằng cách tính thuế khi không đăng kí phụ thuộc rồi trừ đi thuế nếu có đăng kí phụ thuộc.  
Tool tính thuế thị dân: https://zeisim.e-civion.net/tax-project/MinatoMenuAction (đối với Tokyo và các tỉnh lân cận, ai ở xa hơn cần tìm link khác)  
Tool tính thuế thu nhập: https://www.jtuc-rengo.or.jp/activity/kurashi/zei/calculate/index.php (tool này tính cả thuế thị dân nhưng không chính xác, thuế thu nhập có thể tính lệch 1%)

Với người có thu nhập trung bình trở xuống (dưới 1sen man) thì với 2 người phụ thuộc được giảm 14.6man thuế.

Thuế thị dân đóng từ tháng 6 năm 2 ~ tháng 5 năm 3 được tính dựa trên kết quả 源泉徴収票 của năm 1.

Cần gửi về bao nhiêu để được miễn giảm:  
Theo tài liệu chính thức từ chính phủ Nhật thì không có hướng dẫn giới hạn, tuy nhiên nếu gửi quá ít tiền thì bên phía chính phủ có thể yêu cầu xác minh lại.  
Thông thường thì 10man/người là mức an toàn.  
https://www.nta.go.jp/publication/pamph/pdf/kokugaifuyou-QA.pdf

## Cách tính furusato nozei
Đối với trường hợp sử dụng 確定申告:  
Tiền mua furusato (X) trong năm được tính vào năm 1  
Đợt 確定申告時期 vào năm 2 khai báo furusato nozei  
Tháng 4~5 sẽ được back lại 1 khoản nhỏ (từ thuế thu nhập), gần 10% số tiền furusato bạn đã mua. (Y)  
Từ tháng 6 năm 2 -> tháng 5 năm 3, thuế sống sẽ được miễn trừ.  
Mỗi tháng sẽ được miễn trừ (X - 2000 - Y)/12 (có thể dùng tool tính thuế thị dân ở trên để tính chính xác số tiền thuế thị dân phải đóng sau khi được miễn trừ)  
![image](https://user-images.githubusercontent.com/6410496/123445246-ad4a1180-d612-11eb-81d2-f8c8d1a30894.png)

Cách tính tối đa số tiền mua furusato:
https://www.furusato-tax.jp/about/simulation
Tuy trong tool sử dụng 源泉徴収票 để làm ví dụ điền giá trị, tuy nhiên 源泉徴収票 gần nhất bạn có được là của năm ngoái chứ không phải năm nay, trường hợp tăng/giảm lương thì nên tự tính tổng thu nhập thay vì lấy từ 源泉徴収票.

Tool đăng kí 確定申告 (có thể free trial 1 tháng): https://biz.moneyforward.com/tax_return/
Nếu sử dụng tool trên để đăng kí 確定申告 thì không cần in ấn gì, chỉ cần thẻ mynumber có gắn chip và smartphone là được, không cần dùng tới đống giấy tờ chứng minh từ địa phương gửi cho bạn.

# TODO
+ tính thuế thu nhập từ fukugyo
+ tính thuế thu nhập từ cổ phiếu
+ tính thuế thu nhập từ RSA
+ tính thuế thu nhập từ cho thuê nhà
+ tính thuế miễn giảm từ vay ngân hàng mua nhà ở
