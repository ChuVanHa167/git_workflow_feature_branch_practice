# git_workflow_feature_branch_practice
thực hành feature branch workflow

**_Giả sử dự án:_**
Một nhóm lập trình đang phát triển _website bán hàng online_.

_**Các tính năng:**_
* Trang chủ
* Trang sản phẩm
* Trang giỏ hàng
* Trang thanh toán

Nhóm quyết định sử dụng **Feature Branch Workflow**.

_**Trong mô hình này:**_
* Nhánh chính: `main`
* Mỗi tính năng được phát triển trên **một branch riêng**

_**Ví dụ:**_
```
main
 ├─ feature/homepage
 ├─ feature/product-page
 ├─ feature/cart
```

_**Sau khi hoàn thành tính năng:**_
1. Merge branch feature vào `main`
2. Xóa branch feature

_**Mục đích, Repo này dùng để minh họa:**_
* Cách tạo feature branch
* Cách phát triển tính năng riêng
* Cách merge vào main

_**Workflow:**_
```
           feature/homepage
          /
main -----
          \
           feature/product-page
```

_**Sau khi hoàn thành:**_

```
feature/homepage → merge → main
```

_**Ưu điểm**_
* Mỗi tính năng phát triển độc lập
* Dễ review code
* Giảm conflict

**_Nhược điểm_**
* Cần quản lý nhiều branch
