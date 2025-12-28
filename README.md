# 🚀 Database Knowledge Hub

Chào mừng đến với **Database Knowledge Hub** - kho tàng kiến thức toàn diện về các công nghệ cơ sở dữ liệu phổ biến nhất hiện nay.

Dự án này tổng hợp các cheat sheets, bài học, và tài liệu tham khảo từ cơ bản đến nâng cao cho Firestore, MongoDB, MySQL, PostgreSQL, SQL Server, và SQLite.

## 📚 Nội Dung Chính

Dự án được chia thành các thư mục riêng biệt cho từng công nghệ:

### 🔥 [Firestore](FirestoreDB/index.html)

- **Modules**: Data Model, CRUD, Querying, Indexing, Real-time Listeners, Security Rules.
- **Đặc điểm**: NoSQL, Real-time, Offline support.

### 🍃 [MongoDB](MongoDB/MongoDB%20Cheat%20Sheets%20-%20Master%20Index%20(links%20to%2016%20HTML%20files).html)

- **Modules**: Architecture, CRUD, Aggregation, Indexing, Replication, Sharding.
- **Đặc điểm**: NoSQL Document-based, Flexible schema, High performance.

### 🐬 [MySQL](MySQL/index.html)

- **Modules**: Foundations, Database Design, Performance Optimization, Administration.
- **Đặc điểm**: RDBMS phổ biến nhất, ACID compliant, Replication mạnh mẽ.

### 🐘 [PostgreSQL](PostgreSQL/index-postgresql.html)

- **Modules**: Advanced Querying, JSONB, PL/pgSQL, Partitioning.
- **Đặc điểm**: RDBMS tiên tiến, hỗ trợ JSON tốt, khả năng mở rộng cao.

### 🗄️ [SQL Server](SQLServer/Index.html)

- **Modules**: T-SQL, CTEs, Window Functions, Stored Procedures, Security.
- **Đặc điểm**: Enterprise-grade RDBMS từ Microsoft, tích hợp tốt với .NET ecosystem.

### 🪶 [SQLite](Sqlite3/index-sqlite.html)

- **Modules**: Foundations, Transactions, FTS5, JSON support.
- **Đặc điểm**: Serverless, Zero-configuration, Embedded database.

## 🌐 Deployment (Cloudflare Pages)

Dự án này được thiết kế để hoạt động hoàn hảo dưới dạng **Static Website**. Bạn có thể deploy miễn phí và nhanh chóng lên **Cloudflare Pages**.

### Các bước thực hiện

1. **Push code lên GitHub**:
    - Tạo một repository mới trên GitHub.
    - Push toàn bộ thư mục dự án lên repository đó.

2. **Thiết lập Cloudflare Pages**:
    - Truy cập [Cloudflare Dashboard](https://dash.cloudflare.com/) > **Pages**.
    - Chọn **Create a project** > **Connect to Git**.
    - Chọn repository GitHub bạn vừa tạo.

3. **Cấu hình Build**:
    - **Project name**: Đặt tên cho dự án (ví dụ: `database-hub`).
    - **Production branch**: `main` (hoặc `master`).
    - **Framework preset**: `None` (vì đây là static HTML).
    - **Build command**: (Để trống).
    - **Build output directory**: `/` (hoặc để trống nếu root directory chứa file `index.html`).

4. **Deploy**:
    - Nhấn **Save and Deploy**.
    - Cloudflare sẽ tự động build và cung cấp cho bạn một đường dẫn (ví dụ: `database-hub.pages.dev`).

## 🛠️ Đóng Góp & Phát Triển

Để thêm nội dung mới:

1. Tạo file HTML mới trong thư mục tương ứng (ví dụ: `MySQL/8.MySQL-New-Topic.html`).
2. Cập nhật file `index.html` của thư mục đó để link tới bài mới.
3. Commit và Push lên GitHub, Cloudflare Pages sẽ tự động update.

---
*Created with ❤️ for the Database Community*
