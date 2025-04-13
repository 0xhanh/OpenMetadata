# REST API

## Chi tiết kết nối

$$section
### Máy chủ và Cổng $(id="hostPort")
URL điểm cuối API OpenMetadata.

$$

$$section
### Xác thực $(id="authentication")
Chọn cơ chế xác thực:
- **Không xác thực**: Truy cập API mà không cần xác thực.
- **Xác thực cơ bản**: Sử dụng tên người dùng và mật khẩu để xác thực.
- **Khóa API**: Sử dụng xác thực JWT Token.
- **Bearer Token**: Sử dụng xác thực Bearer Token.
- **Thông tin xác thực Amazon IAM**: Sử dụng vai trò AWS IAM để kiểm soát quyền truy cập vào API.
- **OIDC tùy chỉnh**: Sử dụng nhà cung cấp OpenID Connect tùy chỉnh để xác thực.
$$