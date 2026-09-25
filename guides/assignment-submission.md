# Hướng dẫn nộp Assignment

## Bước 1 — cập nhật main

```bash
git checkout main
git pull
```

## Bước 2 — tạo branch tuần mới

```bash
git checkout -b hw/wXX-topic
```

Ví dụ:

```bash
git checkout -b hw/w07-pandas
```

## Bước 3 — tạo folder bài

```text
assignments/wXX-topic/
```

## Bước 4 — làm bài và commit

```bash
git status
git diff
git add .
git commit -m "feat: complete assignment"
```

Nên commit theo các mốc có ý nghĩa trong quá trình làm.

## Bước 5 — push

```bash
git push -u origin hw/wXX-topic
```

## Bước 6 — tạo Pull Request

```text
base: main
compare: hw/wXX-topic
```

Title:

```text
[WXX] Topic - Student ID
```

## Bước 7 — nhận review

Instructor có thể comment trực tiếp trên PR và yêu cầu chỉnh sửa.

## Bước 8 — sửa bài

Vẫn trên branch hiện tại:

```bash
git add .
git commit -m "fix: address review feedback"
git push
```

PR cũ sẽ tự động cập nhật.

## Bước 9 — merge

Sau khi được review/approve, merge vào `main`.

Branch bài tập sau đó có thể xóa.
