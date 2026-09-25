# Quy định nộp bài

## 1. Nơi nộp

Mỗi học viên có một repo cá nhân trong GitHub Organization.

Bài tập được nộp bằng **Pull Request** từ branch bài tập vào `main`.

## 2. Quy ước folder

```text
assignments/wXX-topic/
```

Ví dụ:

```text
assignments/w07-pandas/
```

## 3. Quy ước branch

```text
hw/wXX-topic
```

Ví dụ:

```text
hw/w07-pandas
```

Không làm bài trực tiếp trên `main`.

## 4. Quy ước Pull Request

Title:

```text
[WXX] Topic - Student ID
```

Ví dụ:

```text
[W07] Pandas - HV01
```

## 5. Mốc nộp

Theo quy ước mặc định, thời điểm tạo Pull Request đầu tiên là mốc submission, trừ khi instructor thông báo khác.

## 6. Sửa bài sau review

Nếu được yêu cầu chỉnh sửa:

- tiếp tục dùng branch hiện tại;
- commit phần sửa;
- push tiếp;
- không tạo PR mới trừ khi instructor yêu cầu.

## 7. Trước khi nộp

Học viên cần đảm bảo:

- code/notebook chạy được;
- output đã được kiểm tra;
- không có password, API key hoặc secret;
- không commit môi trường local hoặc file rác;
- commit message có ý nghĩa;
- khai báo việc sử dụng AI nếu có.
