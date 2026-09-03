# 03. Domain Model Và Luồng Nghiệp Vụ

## Mục tiêu
Định nghĩa thực thể lõi và cách chúng vận hành với nhau trước khi đụng đến database.

## Thực thể lõi
- [ ] User
- [ ] Role
- [ ] Product / Material
- [ ] ProductCategory
- [ ] UnitOfMeasure
- [ ] Supplier
- [ ] Customer
- [ ] PurchaseOrder
- [ ] PurchaseOrderLine
- [ ] SalesOrder
- [ ] SalesOrderLine
- [ ] StockMovement
- [ ] InventoryBalance
- [ ] DebtLedger
- [ ] CashTransaction
- [ ] AuditLog

## Luồng nghiệp vụ
- [ ] Tạo vật tư
- [ ] Nhập kho từ nhà cung cấp
- [ ] Bán hàng cho khách
- [ ] Cập nhật tồn kho theo giao dịch
- [ ] Sinh công nợ khi chưa thanh toán đủ
- [ ] Ghi nhận thu chi
- [ ] Theo dõi thay đổi trên nhật ký

## Quy tắc nghiệp vụ tối thiểu
- [ ] Không cho xuất âm kho nếu chưa có chính sách cho phép
- [ ] Mỗi giao dịch kho phải truy được nguồn phát sinh
- [ ] Công nợ phải gắn với khách hàng hoặc nhà cung cấp
- [ ] Mọi thao tác quan trọng phải có timestamp và user thực hiện

## Kết quả đầu ra
- [ ] Sơ đồ domain rõ ràng
- [ ] Định nghĩa trạng thái và quan hệ giữa các entity
- [ ] Có basis để thiết kế bảng dữ liệu

