## PUSH

    git push : đẩy code từ local lên remote

## PULL

    git pull origin main : kéo code từ remote về local

## Git Log

    git log --oneline : hiển thị các commit của project

## Git ignore

    bỏ qua file : vd node-modules

## Markdown

    ul li
    - đây là 1 thẻ ul li

![Đây là logo](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQKtrOMG_WFFn6wkymZGe1T8sbrNza1A_BraZ08_OR4Rh_PxVpx)
**In đậm**
_In nghiêng_

> đây là quotes

đây là `javascript`

```javacript
console.log("Dao Viet Anh");
```

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
  </head>
  <body></body>
</html>
```

```c++
print("Dao Viet Anh");
```

## Tạo ra 1 branch mới

    git branch : example : git branch feature/Login

## Tạo ra 1 brach mới và switch sang branch đó luôn

    git checkout -b feature/Register
    git switch -c feature/Form

## Để chuyển qua lại giữa các branch

    git checkout main
    git switch main

## Để đồng bộ các branch từ remote về local

    git fetch

## Để đổi tên 1 branch

    **Cách 1**
    -truy cập vào branch đó
    - vd : git checkout feature/Login
           git branch -m feature/FunctionLogin
    **Cách 2**
    git branch -m feature/Login feature/FunctionLogin

## Để xóa 1 branch tại local

    git branch -D feature/FunctionLogin

## Để xóa 1 branch tại remote

    git push origin --delete feature/HandleError

## Push code lên 1 branch

    nếu như branch đó không tồn tại ở remote chạy câu lệnh sau
    git push -u origin localBranch
    git push -u origin HEAD
