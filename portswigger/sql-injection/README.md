# SQL Injection

---

**What is SQL injection (SQLi)?**

> Là lỗi bảo mật web cho phép attacker can thiệp vào các truy vấn đối với CSDL. Thường sẽ cho phép attacker xem data mà không được cấp phép. Nhiều case thì attacker có thể thêm, sửa, xóa dữ liệu tùy ý.

---

**Tác hại của SQLi**

> Một cuộc attack SQLi thành công sẽ dẫn tới hậu quả khó lường như bị truy cập vào những data bí mật, nhạy cảm chẳng hạn như passwd, thẻ tín dụng, thông tin cá nhân...

---

**SQLi example**

1. Retrieving hidden data: Sửa đổi truy vấn SQL để trả về thêm kết quả
2. Subverting applicatication logic: Thay đổi query để can thiệp vào logic của app
3. Union attacks: Truy xuất các data từ các table khác nhau
4. Examining the database: Trích xuất thông tin về version, structure của database
5. Blind SQL injection: Kết quả query sẽ được trả về trong response của app
