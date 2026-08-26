🎨 Web Designer
<p align="center"> <img src="https://img.shields.io/badge/Web%20Designer-Website%20Builder-6366F1?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Web Designer"> <img src="https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React"> <img src="https://img.shields.io/badge/Node.js-20-339933?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js"> </p> <p align="center"> <strong>🚀 Công cụ thiết kế website trực quan, hiện đại và mạnh mẽ</strong> </p> <p align="center"> Xây dựng website chuyên nghiệp bằng giao diện kéo-thả<br> mà không cần phải viết quá nhiều code. </p> <p align="center"> <a href="#-tính-năng">Tính năng</a> • <a href="#-demo">Demo</a> • <a href="#-cài-đặt">Cài đặt</a> • <a href="#-công-nghệ">Công nghệ</a> • <a href="#-đóng-góp">Đóng góp</a> </p>
📸 Demo

🖼️ Screenshot

<p align="center"> <img src="./docs/images/editor-preview.png" alt="Web Designer Editor" width="900"> </p> <p align="center"> <em>Giao diện trình thiết kế website</em> </p>
✨ Giới thiệu

Web Designer là phần mềm hỗ trợ thiết kế website với giao diện Drag & Drop, cho phép người dùng tạo và chỉnh sửa giao diện trực tiếp trên Canvas.

Thay vì phải xây dựng toàn bộ giao diện bằng code, người dùng có thể:

Kéo component vào trang.
Chỉnh sửa nội dung trực tiếp.
Thay đổi màu sắc, kích thước và bố cục.
Thiết kế Responsive cho nhiều thiết bị.
Xem trước website theo thời gian thực.
Xuất website sau khi hoàn thành.

🎯 Mục tiêu: xây dựng một công cụ thiết kế website đơn giản cho người mới nhưng đủ mạnh cho developer và designer chuyên nghiệp.

🚀 Tính năng
🎨 Visual Editor
🖱️ Drag & Drop component.
✏️ Chỉnh sửa trực tiếp trên Canvas.
📐 Resize và căn chỉnh element.
🎯 Positioning chính xác.
📏 Hỗ trợ Grid và Flexbox.
↩️ Undo / Redo.
🧩 Component System

Hỗ trợ nhiều loại component:

📦 Components
├── Text
├── Heading
├── Button
├── Image
├── Video
├── Container
├── Card
├── Navbar
├── Footer
├── Form
├── Input
└── Custom Component

📱 Responsive Design

Thiết kế và kiểm tra giao diện trên:

Thiết bị	Kích thước
🖥️ Desktop	≥ 1200px
💻 Laptop	992px – 1199px
📱 Tablet	768px – 991px
📱 Mobile	< 768px
🎛️ Style Editor

Cho phép tùy chỉnh:

Màu sắc.
Font chữ.
Font size.
Line height.
Margin.
Padding.
Border.
Border radius.
Box shadow.
Background.
Opacity.
Width / Height.
👁️ Live Preview

Xem trước website ngay trong quá trình thiết kế mà không cần reload trang.

💾 Project Management
Tạo project.
Tạo nhiều page.
Lưu project.
Duplicate page.
Xóa page.
Import / Export project.
🖥️ Giao diện
┌─────────────────────────────────────────────────────────────┐
│                       TOOLBAR                               │
├──────────────┬───────────────────────────────┬──────────────┤
│              │                               │              │
│  COMPONENTS  │                               │  PROPERTIES  │
│              │                               │              │
│  ┌────────┐  │                               │  ┌─────────┐ │
│  │ Text   │  │                               │  │ Layout  │ │
│  ├────────┤  │            CANVAS             │  ├─────────┤ │
│  │ Button │  │                               │  │ Style   │ │
│  ├────────┤  │       Your Website            │  ├─────────┤ │
│  │ Image  │  │                               │  │ Spacing │ │
│  ├────────┤  │                               │  └─────────┘ │
│  │ Card   │  │                               │              │
│  └────────┘  │                               │              │
│              │                               │              │
└──────────────┴───────────────────────────────┴──────────────┘

🛠️ Công nghệ
Frontend
<p> <img src="https://img.shields.io/badge/React-18-61DAFB?style=flat-square&logo=react&logoColor=black"> <img src="https://img.shields.io/badge/Vite-7-646CFF?style=flat-square&logo=vite&logoColor=white"> <img src="https://img.shields.io/badge/TailwindCSS-4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white"> </p>
Backend
<p> <img src="https://img.shields.io/badge/Node.js-20-339933?style=flat-square&logo=node.js&logoColor=white"> <img src="https://img.shields.io/badge/Express.js-5-000000?style=flat-square&logo=express&logoColor=white"> </p>
Database
<p> <img src="https://img.shields.io/badge/PostgreSQL-15-4169E1?style=flat-square&logo=postgresql&logoColor=white"> </p>
Development
<p> <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"> <img src="https://img.shields.io/badge/ESLint-4B32C3?style=flat-square&logo=eslint&logoColor=white"> <img src="https://img.shields.io/badge/Prettier-F7B93E?style=flat-square&logo=prettier&logoColor=black"> </p>
📦 Yêu cầu hệ thống

Trước khi chạy project, hãy đảm bảo máy tính đã cài:

Node.js >= 20
npm >= 10
PostgreSQL >= 15
Git

Kiểm tra phiên bản:

node -v
npm -v
git --version

⚡ Cài đặt
1. Clone project
git clone https://github.com/your-username/web-designer.git

2. Truy cập thư mục
cd web-designer

3. Cài đặt package
npm install

4. Tạo file môi trường

Copy file .env.example:

cp .env.example .env


Sau đó cập nhật:

VITE_API_URL=http://localhost:3000/api

DATABASE_URL=postgresql://username:password@localhost:5432/web_designer

JWT_SECRET=your-secret-key

5. Chạy development server
npm run dev


Ứng dụng sẽ chạy tại:

http://localhost:5173

📜 Scripts
Command	Description
npm run dev	🚀 Chạy development server
npm run build	📦 Build production
npm run preview	👁️ Preview production
npm run test	🧪 Chạy test
npm run lint	🔍 Kiểm tra code
npm run format	✨ Format code
📁 Cấu trúc project
web-designer/
│
├── 📁 public/
│   ├── images/
│   └── icons/
│
├── 📁 src/
│   │
│   ├── 📁 components/
│   │   ├── Canvas/
│   │   ├── Editor/
│   │   ├── Sidebar/
│   │   ├── Toolbar/
│   │   ├── PropertiesPanel/
│   │   └── Preview/
│   │
│   ├── 📁 pages/
│   ├── 📁 hooks/
│   ├── 📁 services/
│   ├── 📁 store/
│   ├── 📁 utils/
│   ├── 📁 styles/
│   │
│   ├── App.jsx
│   └── main.jsx
│
├── 📁 server/
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   ├── middleware/
│   └── server.js
│
├── 📁 tests/
│
├── 📁 docs/
│   └── images/
│
├── .env.example
├── .gitignore
├── package.json
├── vite.config.js
└── README.md

🏗️ Kiến trúc hệ thống
                         ┌──────────────┐
                         │     USER     │
                         └──────┬───────┘
                                │
                                ▼
                    ┌─────────────────────┐
                    │    WEB DESIGNER     │
                    │      FRONTEND       │
                    ├─────────────────────┤
                    │                     │
                    │  Editor             │
                    │  Canvas             │
                    │  Components         │
                    │  Properties         │
                    │  Preview            │
                    │                     │
                    └──────────┬──────────┘
                               │
                              API
                               │
                               ▼
                    ┌─────────────────────┐
                    │     BACKEND API     │
                    │   Node.js/Express   │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │      DATABASE       │
                    │     PostgreSQL      │
                    └─────────────────────┘

🔄 Quy trình thiết kế
Create Project
      │
      ▼
Choose Template
      │
      ▼
Open Editor
      │
      ▼
Drag & Drop Components
      │
      ▼
Customize Design
      │
      ▼
Responsive Check
      │
      ▼
Live Preview
      │
      ▼
Save Project
      │
      ▼
Export / Deploy

🧪 Testing

Chạy toàn bộ test:

npm run test


Chạy test ở chế độ watch:

npm run test:watch


Các thành phần quan trọng cần được kiểm thử:

Editor.
Drag & Drop.
Component rendering.
Responsive layout.
Undo / Redo.
Project management.
Authentication.
API.
Database.
Export website.
🗺️ Roadmap
Editor
 Basic Editor
 Drag & Drop
 Component System
 Properties Panel
 Live Preview
 Undo / Redo
 Advanced Grid System
 Flexbox Editor
 Animation Editor
Project
 Create Project
 Multiple Pages
 Save Project
 Project Templates
 Version History
 Auto Save
Collaboration
 Team Workspace
 Real-time Collaboration
 Comments
 Permission Management
AI
 AI Website Generator
 AI Layout Generator
 AI Content Generator
 AI Image Generator
 AI Code Assistant
Deployment
 Export HTML/CSS
 Export React
 Export Vue
 One-click Deployment
 Custom Domain
🤝 Đóng góp

Đóng góp của bạn luôn được chào đón ❤️

Fork project
git clone https://github.com/your-username/web-designer.git

Tạo branch
git checkout -b feature/my-feature

Commit
git add .
git commit -m "feat: add my feature"

Push
git push origin feature/my-feature


Sau đó tạo Pull Request trên GitHub.

📋 Quy ước Commit

Dự án sử dụng Conventional Commits:

Prefix	Ý nghĩa
feat:	✨ Tính năng mới
fix:	🐛 Sửa lỗi
docs:	📝 Tài liệu
style:	🎨 Thay đổi UI / format
refactor:	♻️ Refactor code
test:	🧪 Test
chore:	🔧 Công việc cấu hình

Ví dụ:

git commit -m "feat: add responsive editor"

🔐 Security

Nếu phát hiện vấn đề bảo mật, vui lòng không tạo issue công khai.

Hãy liên hệ với maintainer của project để báo cáo vấn đề một cách riêng tư.

📄 License

Dự án được phát hành dưới giấy phép MIT License.

Xem file LICENSE để biết thêm thông tin.

👨‍💻 Author
<p align="center">
Web Designer Team

Made with ❤️ and ☕ by Web Designer Team

</p>
⭐ Support

Nếu bạn thấy project hữu ích:

⭐ Star repository

🍴 Fork project

🐛 Report bugs

💡 Suggest features

📢 Share project

<p align="center"> <strong>🎨 Build your idea. Design your website. Ship faster. 🚀</strong> </p> <p align="center"> © 2026 Web Designer Team </p>
