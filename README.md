# git_workflow_feature_branch_practice
thực hành feature branch workflow

Giả sử dự án
Một nhóm lập trình đang phát triển **website bán hàng online**.

Các tính năng:
* Trang chủ
* Trang sản phẩm
* Trang giỏ hàng
* Trang thanh toán
Nhóm quyết định sử dụng **Feature Branch Workflow**.

Trong mô hình này:
* Nhánh chính: `main`
* Mỗi tính năng được phát triển trên **một branch riêng**
Ví dụ:
```
main
 ├─ feature/homepage
 ├─ feature/product-page
 ├─ feature/cart
```

Sau khi hoàn thành tính năng:
1. Merge branch feature vào `main`
2. Xóa branch feature

Mục đích repo
Repo này dùng để minh họa:
* Cách tạo feature branch
* Cách phát triển tính năng riêng
* Cách merge vào main

Workflow
```
           feature/homepage
          /
main -----
          \
           feature/product-page
```

Sau khi hoàn thành:

```
feature/homepage → merge → main
```

Ưu điểm
* Mỗi tính năng phát triển độc lập
* Dễ review code
* Giảm conflict

Nhược điểm
* Cần quản lý nhiều branch
