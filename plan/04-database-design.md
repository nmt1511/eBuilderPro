# 04. Thiết Kế Database

## Mục tiêu
Thiết kế schema đủ cho MVP, chuẩn hóa vừa đủ và dễ migrate/seed.

## Nhóm bảng chính
- [ ] `AspNetUsers` / `AspNetRoles` nếu dùng Identity
- [ ] `Categories`
- [ ] `Units`
- [ ] `Products`
- [ ] `Suppliers`
- [ ] `Customers`
- [ ] `PurchaseOrders`
- [ ] `PurchaseOrderItems`
- [ ] `SalesOrders`
- [ ] `SalesOrderItems`
- [ ] `InventoryTransactions`
- [ ] `InventoryBalances`
- [ ] `Debts`
- [ ] `DebtTransactions`
- [ ] `CashTransactions`
- [ ] `AuditLogs`

## Cột dữ liệu tối thiểu
- [ ] Khóa chính, khóa ngoại
- [ ] Mã định danh nghiệp vụ
- [ ] Tên hiển thị
- [ ] Số lượng, đơn giá, thành tiền
- [ ] Trạng thái chứng từ
- [ ] Thời điểm tạo/cập nhật
- [ ] Người tạo/cập nhật

## Chỉ mục và ràng buộc
- [ ] Unique cho mã nghiệp vụ
- [ ] Index cho khóa tra cứu thường xuyên
- [ ] FK rõ ràng cho quan hệ cha-con
- [ ] Check constraint cho trạng thái hợp lệ nếu cần

## Seed dữ liệu
- [ ] Category mặc định
- [ ] Unit mặc định
- [ ] Admin user ban đầu
- [ ] Dữ liệu demo tối thiểu cho dashboard

## Kết quả đầu ra
- [ ] Có ERD logic
- [ ] Có lược đồ bảng đủ để bắt đầu code migration
- [ ] Có seed strategy cho môi trường dev

