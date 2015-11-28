# WHY
##Tại sao UDP lại hay được sử dụng trong truyền media
***Ngoài lí do UDP nhanh còn 1 vài lí do khác e tìm kiếm đc:***
- Khi chuyền media có thể chấp nhận việc mất thông tin và chễ thời gian nên sử dụng UDP sẽ tiết kiệm được chi phí
- UDP có độ trể nhỏ:bỏ qua thời gian xử lý và việc trễ gói tin 
- đơn giản hơn:phía gửi và nhận không cần ghi nhớ trạng thái gửi và nhận
- Không có cơ chế kiểm soát tắc nghẽn, điều khiển lỗi, điều khiển luồng nên bên gửi có thể gửi dữ liệu với tốc độ tối đa
