# Hướng dẫn thiết lập GitHub

## 1. Chuẩn bị

Học viên cần:

- tài khoản GitHub;
- Git trên máy;
- quyền truy cập repo cá nhân.

## 2. Cấu hình Git identity

```bash
git config --global user.name "Tên của bạn"
git config --global user.email "email-cua-ban"
```

Kiểm tra:

```bash
git config --global user.name
git config --global user.email
```

## 3. Đăng nhập GitHub

Cách đơn giản khuyến nghị:

```bash
gh auth login
```

Chọn:
- GitHub.com
- HTTPS
- Login with a web browser

Kiểm tra:

```bash
gh auth status
```

## 4. Clone repo cá nhân

```bash
git clone https://github.com/dma-course-2026/<repo-cua-ban>.git
cd <repo-cua-ban>
```

Kiểm tra remote:

```bash
git remote -v
```

## 5. Kiểm tra repo

Bạn nên thấy các file/folder cơ bản như:

```text
README.md
.gitignore
assignments/
.github/
```
