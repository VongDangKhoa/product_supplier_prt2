# Node.js MVC CRUD - Supplier & Product

Dự án web CRUD (Create, Read, Update, Delete) xây dựng bằng **Node.js + Express + MongoDB + Mongoose** theo kiến trúc **MVC**.

## Tính năng
- Quản lý **Supplier**: `name`, `address`, `phone`
- Quản lý **Product**: `name`, `price`, `quantity`, `supplierId`
- Giao diện hiển thị bằng **EJS**
- Kết nối MongoDB với **Mongoose**

## Cấu trúc thư mục
project/
│── app.js
│── models/
│ ├── Supplier.js
│ └── Product.js
│── controllers/
│ ├── supplierController.js
│ └── productController.js
│── routes/
│ ├── supplierRoutes.js
│ └── productRoutes.js
│── views/
│ ├── suppliers/
│ └── products/
│── public/
│── package.json
│── README.md


