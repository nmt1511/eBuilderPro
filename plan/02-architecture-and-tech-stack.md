# 02. Kiến Trúc Và Tech Stack

## Mục tiêu
Chốt kiến trúc đủ đơn giản để code nhanh, chạy ổn định, dễ mở rộng trong giai đoạn sau.

## Hiện trạng dự án
- [ ] ASP.NET Core Razor Pages `.NET 8`
- [ ] Chưa có tầng domain, service, repository
- [ ] Chưa có database
- [ ] Đang ở trạng thái template mặc định

## Kiến trúc đề xuất cho MVP
- [ ] UI: Razor Pages
- [ ] Application layer: service cho nghiệp vụ
- [ ] Data access: EF Core
- [ ] Database: SQL Server hoặc SQLite cho dev local
- [ ] Validation: DataAnnotations + service validation
- [ ] Auth: ASP.NET Core Identity hoặc auth custom tối giản
- [ ] Logging: built-in logging + audit table

## Nguyên tắc thiết kế
- [ ] Ưu tiên chạy được lần đầu, ít phụ thuộc
- [ ] Chia module theo nghiệp vụ thay vì chia theo kỹ thuật thuần túy
- [ ] Tránh over-engineering ở MVP
- [ ] Có thể seed dữ liệu mẫu ngay sau khi tạo database

## Quy ước thư mục tương lai
- [ ] `Domain/`
- [ ] `Data/`
- [ ] `Services/`
- [ ] `Pages/Inventory/`
- [ ] `Pages/Sales/`
- [ ] `Pages/Purchases/`
- [ ] `Pages/Reports/`
- [ ] `Shared/`

## Kết quả đầu ra
- [ ] Có kiến trúc chốt để bám theo khi code
- [ ] Có quyết định rõ về DB, auth, logging, validation

