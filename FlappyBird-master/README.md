# Flappy Bird 

Game Flappy Bird viết bằng JavaScript, sử dụng thư viện p5.js và đóng gói bằng webpack.

## Tổng quan

- Thư viện: `p5.js`
- Trình đóng gói: `webpack` (Webpack 5)

Repository: https://github.com/Buiminhquan1210/BTL_CNPM

## Yêu cầu

- Node.js (LTS) và `npm`

## Chạy trên máy local

Mở PowerShell hoặc terminal, sau đó chạy các lệnh sau:

```bash
cd C:\Users\PC\Downloads\FlappyBird-master\FlappyBird-master
npm install
npm start
```

Mặc định dev server sẽ mở trang trên http://localhost:8080 (hoặc mở thủ công trình duyệt tới địa chỉ đó).

Nếu muốn chạy trên cổng khác:

```bash
npx webpack-dev-server --config webpack.dev.js --open --port 8081
```

## Build production

```bash
npm run build
```

Kết quả build nằm trong thư mục `dist` (hoặc `build` tùy cấu hình). Bạn có thể deploy nội dung này lên GitHub Pages hoặc hosting tĩnh.

## Cấu trúc chính

- `src/` — mã nguồn và assets
- `webpack.*.js` — cấu hình webpack
- `package.json` — scripts và dependencies

## Ghi chú

- Nếu gặp lỗi về `webpack-dev-server` khi chạy `npm start`, chạy `npm install` trong thư mục dự án rồi thử lại.
- Để push lên GitHub: `git add . && git commit -m "Update README" && git push`.
