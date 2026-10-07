Phân tích lỗi & Lập bảng Test Cases
1. Phân tích lỗi
 .priceKey dẫn tới việc js tìm đúng cái tên thuộc tính priceKey. Mà bookingReservation không tồn tại thuộc tính trên.
2. Test case
a. 
Trường hợp kiểm thử: Lấy phòng qua biến priceKey
Dữ liệu đầu vào: priceKey = "roomPrice"
Kết quả sai thực tế: undifined như phân tích lỗi
Kết quả đúng mong đợi: basePrice = 1500000

b. 
Trường hợp kiểm thử: Tính tiền 
Dữ liệu đầu vào: checkInHour = 9
Kết quả sai thực tế: NaN vì không có số liệu để thực hiện phép tính
Kết quả đúng mong đợi: 
    surcharge = 450000
    totalAmount = 1950000 VNĐ
