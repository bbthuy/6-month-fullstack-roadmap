# 6-month-fullstack-roadmap

*Stack định hướng: JavaScript → TypeScript, React, Next.js, API, Python (vừa đủ cho AI), SQL Server, Docker*

**Mục tiêu lõi:**
Nắm cực chắc nền tảng web và hiểu rõ một stack full-stack vận hành end-to-end. Python trong lộ trình này chỉ là công cụ hỗ trợ tích hợp AI/API và tách AI microservice khi cần, không phải trọng tâm đào sâu thuật toán ML.

**Chiến lược:**
- Học theo nguyên tắc: hiểu bản chất trước, framework sau; build nhỏ trước, đồ án sau; hoàn thành đầu ra được demo trước khi tối ưu.
- Trục chính của lộ trình là JavaScript/TypeScript/React/Next.js. Python chỉ học phần đủ dùng để gọi AI API, xử lý dữ liệu nhẹ và dựng FastAPI service nhỏ.
- Không nhảy framework liên tục. Trong 6 tháng, ưu tiên 1 stack chính chạy tốt hơn là biết nhiều nhưng nông.
- Mỗi tuần phải có đầu ra nhìn thấy được: mini app, module, ERD, API, AI feature, hoặc sprint capstone.

**Lộ trình chi tiết theo giai đoạn**

***Giai đoạn A - Tuần 1 đến 4: Cắm rễ JavaScript và web fundamentals***
- Mục tiêu: hiểu browser, DOM, event, fetch, JSON, async/await, module, data transformation.
- Đầu ra bắt buộc: 3 mini app JS thuần (todo, weather/public API app, notes app).
- Nếu chưa tự giải thích được request/response, DOM render, localStorage và lỗi async thì chưa qua giai đoạn này.

***Giai đoạn B - Tuần 5 đến 6: TypeScript để làm code an toàn hơn***
- Mục tiêu: dùng TS để làm code JS dễ bảo trì, không phải biến mọi thứ thành lý thuyết type-level phức tạp.
- Đầu ra bắt buộc: chuyển 1 mini app JS sang TS strict mode.

***Giai đoạn C - Tuần 7 đến 12: React → Next.js***
- Mục tiêu: nắm component, state, props, hooks, rồi chuyển sang App Router, data fetching, route handlers, env, form action.
- Đầu ra bắt buộc: 1 dashboard hoặc CRUD app bằng React và 1 mini full-stack app bằng Next.js.

***Giai đoạn D - Tuần 13 đến 16: Database và API***
- Mục tiêu: thiết kế schema tử tế, hiểu quan hệ dữ liệu, viết query, rồi nối Next.js với SQL Server.
- Đầu ra bắt buộc: ERD, SQL script, seed data, CRUD app có DB thật.

***Giai đoạn E - Tuần 17 đến 20: Python vừa đủ + AI integration***
- Mục tiêu: chỉ học Python đủ cho script/API/JSON/error handling và FastAPI service nhẹ.
- Đầu ra bắt buộc: ít nhất 1 AI feature chạy thật trong web app và 1 service FastAPI nhỏ nếu cần tách logic.

***Giai đoạn F - Tuần 21 đến 24: Docker + capstone sprint***
- Mục tiêu: đóng gói hệ thống, build MVP, polish sản phẩm, chuẩn bị demo và bảo vệ.
- Đầu ra bắt buộc: docker compose chạy full stack, bản demo 5 phút, báo cáo, slide, video ngắn.
