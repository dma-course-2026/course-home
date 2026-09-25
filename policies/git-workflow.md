# Git Workflow

## Mental model

- **Repo** = hồ sơ học tập của cả khóa.
- **Folder** = bài của một tuần.
- **Branch** = không gian làm bài của tuần đó.
- **Commit** = mốc thay đổi có ý nghĩa.
- **Pull Request** = hành động nộp bài và nơi review.
- **main** = trạng thái đã được merge sau review.

## Workflow chuẩn

```text
main
  ↓
git pull
  ↓
create hw/wXX-topic
  ↓
làm bài
  ↓
git add / commit
  ↓
git push
  ↓
Pull Request
  ↓
review
  ↓
fix + push
  ↓
approve
  ↓
merge
```

## Lệnh thường dùng

```bash
git checkout main
git pull
git checkout -b hw/wXX-topic

git status
git diff
git add .
git commit -m "feat: complete assignment"

git push -u origin hw/wXX-topic
```

## Commit message

Nên dùng message rõ nghĩa:

```text
feat: add pandas filtering exercises
fix: handle missing values
docs: update README
```

Tránh:

```text
update
final
final2
done
```

## Sau khi merge

Branch cũ có thể được xóa.

Không cần giữ toàn bộ branch bài tập đã hoàn thành.
