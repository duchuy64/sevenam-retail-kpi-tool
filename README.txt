SEVEN.AM – KPI HIỆU SUẤT HỆ THỐNG BÁN LẺ – V6

CÁCH DÙNG
1. Mở index.html bằng Chrome hoặc Microsoft Edge.
2. Copy nguyên bảng Excel/Google Sheets và dán vào ô dữ liệu.
3. Bấm “Đối chiếu & tạo Dashboard”.
4. Xem cảnh báo. Nếu hợp lệ, bấm “Xuất PNG 2K”.

CỘT BẮT BUỘC
- SR.
- TG T8 / TG tháng: Target tháng.
- Thực đạt.
- Hoàn thành TG tháng: dùng trực tiếp để so với tiến độ thời gian và phân loại trạng thái.

CỘT ĐỐI CHIẾU
- DS CẦN ĐẠT.
- Thừa thiếu.
- Target cần chạy 1 ngày.
Các cột này không phải nguồn tính chính. Tool tự tính lại từ TG tháng + Thực đạt + thời gian và cảnh báo nếu số dán sai.

NGÀY BÁO CÁO
- Mặc định tự động: ngày cập nhật = ngày mở tool; số liệu chốt hết ngày hôm trước.
- Nếu dữ liệu có dòng “Cập nhật ngày dd/mm/yyyy”, tool ưu tiên ngày đó và chốt = ngày cập nhật - 1 ngày.
- Chỉ dùng ô ngày nhập tay khi cần xem báo cáo lịch sử.
- Tool KHÔNG còn suy ngày báo cáo từ DS CẦN ĐẠT; DS CẦN ĐẠT chỉ dùng để đối chiếu sai lệch.

SẮP XẾP SHOWROOM
- Toàn bộ bảng showroom tự động sắp xếp từ % Hoàn thành TG tháng cao xuống thấp.
- Top 5 dùng cùng thứ tự này.
- Các showroom trong từng nhóm nhận xét cũng được sắp xếp từ cao xuống thấp.

QUY ƯỚC TRẠNG THÁI
Chênh lệch = Hoàn thành TG tháng - Tiến độ thời gian.
- < -10 điểm %: ĐỎ – CHẬM NHIỀU.
- từ -10 đến < 0 điểm %: CAM – CHẬM.
- từ 0 đến +10 điểm %: XANH DƯƠNG – KỊP.
- > +10 điểm %: XANH LÁ – VƯỢT NHIỀU.

CÔNG THỨC
- % hoàn thành kiểm tra = Thực đạt / TG tháng × 100.
- Tiến độ thời gian = Ngày chốt / Tổng số ngày tháng × 100.
- DS CẦN ĐẠT tự tính = TG tháng × Tiến độ thời gian.
- Thừa/thiếu so với schedule = Thực đạt - DS CẦN ĐẠT tự tính.
- GAP TO KPI = max(0, TG tháng - Thực đạt).
- Target cần chạy/ngày = GAP / số ngày còn lại.
- Forecast cuối tháng = Thực đạt / số ngày đã chốt × tổng số ngày tháng.
- Schedule = Hoàn thành TG tháng - Tiến độ thời gian.

GIAO DIỆN V2
- Dùng đúng hệ font của tool mẫu: Arial, Helvetica, sans-serif.
- Showroom sắp xếp giảm dần theo mức độ hoàn thành.
- Footer 4 trạng thái được chia đều 4 ô và căn giữa chính xác theo chiều rộng thực của chữ.
- Icon KPI, lịch, Top 5, Nhận xét, Schedule và GAP được vẽ lại theo phong cách 3D/gradient có chiều sâu.
- Khối Nhận xét đã cân lại font, line-height và chiều cao từng nhóm để không chồng chữ hoặc vượt nền trắng.
- Card “Tỷ lệ hoàn thành hệ thống / Dự đoán cuối tháng” đã chia lại tỷ lệ và tách tiêu đề thành 2 dòng để không chạm đường phân cách.
- Phần dưới vẫn là AHEAD/BEHIND SCHEDULE + GAP TO KPI, không lặp forecast lần hai.

KÍCH THƯỚC
- Preview logic: 1536 × 1024 px (3:2), đúng tỷ lệ dashboard gốc.
- PNG 2K: 2046 × 1364 px, giữ chính xác tỷ lệ 3:2.

TOOL CHẠY OFFLINE, KHÔNG CẦN BACKEND.


V3 CRISP UI
- Icon KPI vẽ lại dạng 3D sắc nét, không blur/glow.
- 5 KPI đầu tăng kích thước số và font đậm.
- Tiến độ thời gian ưu tiên hiển thị % lớn, thanh tiến độ nằm ngay bên dưới.
- Nhận xét dùng 4 icon trực quan khác nhau; căn dòng động để không chồng chữ.
- Footer 4 trạng thái căn giữa đều theo 4 phân đoạn.
- Giữ sort showroom theo % Hoàn thành TG tháng giảm dần và mặc định chốt hết ngày hôm trước.


V4 – CÂN CHỈNH GIAO DIỆN
- STT trong bảng chính và Top 5 dùng căn giữa theo baseline giữa, số nằm chính giữa hình tròn.
- Tiến độ thời gian: % là số chính; dòng “x/xx NGÀY ĐÃ QUA” nằm bên phải, ngay trên thanh tiến độ; bỏ dòng mô tả lặp phía dưới.
- Target hiển thị trực tiếp “TARGET THÁNG X”; bỏ dòng T8/2026 riêng.
- Icon KPI chuyển sang bộ 2D sắc nét, kích thước lớn, không viền trắng bao quanh và không blur/glow.
- Icon cúp Top 5 và bong bóng Nhận xét tăng kích thước, nét rõ hơn.
- Chênh lệch hệ thống “±x,xx điểm % vs TG” tăng cỡ chữ, in đậm và lấy màu trạng thái.
- Khối Nhận xét bỏ chiều cao cố định từng nhóm: tự đo số dòng tên showroom rồi phân bổ chiều cao động cho 4 nhóm, tránh chồng chữ và tránh khoảng trống thừa.
- Footer chú giải và 3 ghi chú cuối trang tăng font, tăng độ đậm nhưng vẫn giữ cân giữa 4 phân đoạn.
- Không thay đổi công thức, quy tắc trạng thái, cách sort showroom, ngày chốt tự động hoặc kích thước xuất ảnh.

V5 – FIX DỨT ĐIỂM ICON + KPI + GAP
- 5 icon KPI đầu không còn vẽ bằng nhiều stroke trên canvas. Tool dùng bộ SVG 2D cố định, cùng viewBox 64×64, cùng tỷ lệ hiển thị; không còn tình trạng icon cái to cái nhỏ hoặc nét chồng nhau.
- SVG được nhúng trực tiếp dưới dạng data URI trong app.js để chạy offline và không làm canvas bị lỗi khi xuất PNG; thư mục assets/icons vẫn kèm bản SVG gốc để dễ thay thế về sau.
- 5 số KPI chính tăng kích thước và căn giữa theo toàn bộ vùng KPI tương ứng.
- Thanh tiến độ thời gian chạy gần trọn chiều rộng card, cân giữa theo card thay vì trừ vùng icon.
- Nhận xét: tên showroom tăng font; Action dùng chính màu trạng thái tương ứng; chiều cao nhóm tiếp tục tự tính theo số dòng.
- Khối cuối tách hẳn “SO VỚI TIẾN ĐỘ” và “GAP TO KPI”. Mỗi mục có tiêu đề riêng và icon riêng.
- GAP TO KPI chia tiếp thành 2 ô: GAP còn thiếu và CẦN ĐẠT / NGÀY; số cần chạy/ngày được tăng kích thước để dùng như Action trực tiếp.


V6 – FONT + ICON FINAL TUNING
- Icon lịch ở card Cập nhật dữ liệu giảm kích thước và dịch lên trên để không chạm dòng “Số liệu chốt hết ngày”.
- 5 icon KPI đầu tăng khoảng 20% và dịch thấp nhẹ trong từng card; giữ cùng hệ tỷ lệ SVG 64×64.
- Icon SO VỚI TIẾN ĐỘ và GAP TO KPI thay mới bằng SVG không có vòng tròn bao ngoài; mũi tên dùng stroke lớn, line-cap tròn, không bị mất nét khi xuất 2K.
- Tiêu đề lớn dùng Arial Black/Arial Bold; toàn bộ dòng phụ và nhãn báo cáo dùng Arial Bold.
- Không thay đổi logic dữ liệu, công thức, trạng thái, sort showroom, ngày chốt hoặc kích thước xuất ảnh.


CẬP NHẬT V7 – FONT XUẤT ẢNH + CARD CẬP NHẬT
- Thay Arial Black/Arial bằng Tahoma Bold với fallback Segoe UI/Arial/sans-serif để hiển thị tiếng Việt ổn định hơn khi Canvas xuất PNG.
- Chuẩn hóa mọi tiêu đề/dòng phụ về weight 700; không còn dùng weight 900/Arial Black.
- Thu gọn card CẬP NHẬT DỮ LIỆU; icon + ngày + tiêu đề được cân giữa trong khung, không còn dư khoảng trắng bên phải.
- Icon calendar tiếp tục dùng SVG cố định, thu nhỏ và giữ khoảng cách an toàn với dòng chốt số.


CẬP NHẬT V8
- Khôi phục bộ font của bản trước V7: Arial / Arial Black như yêu cầu.
- Hạ toàn bộ 5 icon KPI đầu xuống thêm 7 px để cân hơn trong thẻ.
- Giữ nguyên mọi logic tính toán, bố cục và kích thước xuất ảnh.


CẬP NHẬT V9
- Khôi phục chính xác cơ chế font Canvas của V5: Arial, sans-serif; toàn bộ weight 600/700/800 quy về Bold 700 để xuất PNG ổn định như V5.
- 5 KPI đầu: tiêu đề tăng nhẹ kích thước và dịch sang phải khoảng 8 px.
- 5 giá trị chính (%/Target) tăng khoảng 8–10% và dịch sang phải khoảng 8 px, vẫn giữ trong giới hạn từng card.
- Giữ nguyên vị trí icon đã hạ ở V8 và toàn bộ logic/tính toán hiện có.
