| Method | Endpoint | Mục đích |
|---|---|---|
| GET | /api/v1/materials/list | Lấy danh sách tài liệu chuẩn |
| GET | /api/v1/materials/detail | Xem chi tiết một tài liệu (nội dung, trang/mục) |
| POST | /api/v1/materials/create | Thêm tài liệu chuẩn mới |
| PUT | /api/v1/materials/update | Cập nhật nội dung tài liệu chuẩn |
| DELETE | /api/v1/materials/delete | Xóa tài liệu chuẩn |
| POST | /api/v1/explanations/submit | Gửi lời giải thích để chấm theo Rubric (100 điểm) |
| GET | /api/v1/explanations/list | Xem lịch sử các lần giải thích và điểm |
| GET | /api/v1/explanations/detail | Xem chi tiết một lần chấm: điểm từng tiêu chí, điểm đúng, điểm sai/thiếu, câu hỏi phản biện |
| POST | /api/v1/explanations/reply | Trả lời câu hỏi phản biện duy nhất của lượt chấm |
| POST | /api/v1/explanations/hint | Chế độ Gia sư Socratic khi người học nói "tôi không nhớ" (1 gợi ý, không chấm) |
| GET | /api/v1/gaps/matrix | Xem Ma trận lỗ hổng tri thức (Khía cạnh, Mức độ, Trang cần đọc lại) |
| GET | /api/v1/stats | Xem thống kê tiến bộ theo thời gian |