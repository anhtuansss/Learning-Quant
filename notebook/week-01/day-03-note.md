## Bản chất của Quantitative Trading
- Định nghĩa: Là phương pháp giao dịch tài chính sử dụng các mô hình toán học và chiến lược tự động hóa để tìm kiếm cơ hội sinh lời trên thị trường.

- Ứng dụng chính: Thường xuất hiện trong giao dịch tự doanh (proprietary trading) tại các ngân hàng đầu tư, quỹ đầu tư định lượng (hedge funds), và hoạt động tạo lập thị trường (market making) để cung cấp thanh khoản.

# Ưu điểm & Nhược điểm:

- Ưu điểm: Dựa trên dữ liệu và quy trình hệ thống, giúp loại bỏ cảm xúc cá nhân.

- Thách thức: Dễ gặp rủi ro khi thị trường biến động mạnh đột ngột hoặc xảy ra khủng hoảng (market regime changes & crashes).

## Công việc của một Quantitative Trader
- Họ chuyên thiết kế, kiểm tra và thực thi các chiến lược thông qua mô hình toán - thống kê trên nhiều loại tài sản (cổ phiếu, trái phiếu, hàng hóa, tiền tệ, phái sinh). Các khâu chính gồm:

# Valuation (Định giá): Dùng thuật toán để xác định giá trị hợp lý của tài sản dựa trên dữ liệu quá khứ.

# Execution (Thực thi lệnh): Quản lý và thực hiện các lệnh mua/bán tự động.

# Position Management (Quản lý vị thế): Theo dõi danh mục và quản lý rủi ro thông qua hedging hoặc mua/bán.

## Dữ liệu và Công nghệ sử dụng
- Dữ liệu đầu vào: Dữ liệu giá/khối lượng lịch sử (bao gồm cả dữ liệu tần suất cao - tick data), thông tin doanh nghiệp và các dữ liệu thay thế (alternative data từ thiết bị di động, vệ tinh,...).

- Công cụ cốt lõi: Quá trình nghiên cứu dựa trên Backtesting (kiểm thử chiến lược qua dữ liệu quá khứ). Ngôn ngữ lập trình phổ biến nhất hiện nay là Python, đi kèm xu hướng tích hợp mạnh mẽ của Khoa học dữ liệu và Học máy (Machine Learning).

## Yêu cầu kỹ năng và Định hướng học tập
- Nền tảng học thuật: Thường tốt nghiệp các ngành định lượng như Toán học, Thống kê, Vật lý, Khoa học máy tính, Kỹ thuật hoặc Tài chính định lượng.

- Kỹ năng cần có: Am hiểu thị trường tài chính, thành thạo lập trình, khai thác dữ liệu và xây dựng hệ thống giao dịch tự động.

- Các chương trình đào tạo chuyên sâu như CQF (Certificate in Quantitative Finance) cung cấp nền tảng toàn diện về toán học tài chính, lập trình Python, học máy và kỹ năng định giá, quản lý rủi ro cho những ai muốn theo đuổi lĩnh vực này.

## Giả thuyết thị trường hiệu quả (Efficient Market Hypotheses)
- Bản chất: Giá tài sản trên thị trường đã phản ánh toàn bộ thông tin có sẵn, do đó không thể liên tục "đánh bại thị trường" (kiếm lợi nhuận vượt trội một cách ổn định) bằng phân tích.

- EMH chia thành 3 cấp độ tương ứng với mức độ "thấm" thông tin vào giá:

# Weak-form (Dạng yếu)
- Thông tin phản ánh: Toàn bộ dữ liệu giá và khối lượng giao dịch trong quá khứ (historical prices & volume).

Hệ quả:

- Phân tích kỹ thuật (Technical Analysis / xem biểu đồ, pattern) VÔ TÁC DỤNG vì mọi quy khứ đã nằm trong giá hiện tại.

- Phân tích cơ bản (Fundamental Analysis) vẫn có thể kiếm lời.

# Semi-strong form (Dạng bán mạnh)
- Thông tin phản ánh: Toàn bộ thông tin quá khứ + thông tin công khai hiện tại (Báo cáo tài chính, tin tức kinh tế, thông tin chia cổ tức, báo cáo lợi nhuận...).

Hệ quả:

- Cả Phân tích kỹ thuật và Phân tích cơ bản truyền thống đều VÔ TÁC DỤNG để kiếm lợi nhuận bất thường. Ngay khi tin tức vừa ra, giá lập tức điều chỉnh phản ánh vào đó.

# Strong-form (Dạng mạnh)
- Thông tin phản ánh: Toàn bộ thông tin quá khứ + công khai + thông tin nội bộ / bí mật (Private / Insider information).

Hệ quả:

- Thị trường hoàn hảo tuyệt đối. Kể cả người nội bộ (CEO, ban lãnh đạo giữ tin mật) cũng không thể dùng thông tin độc quyền đó để kiếm lời thường xuyên.

- Mọi cố gắng tìm kiếm alpha (lợi nhuận vượt trội) đều là vô nghĩa, nhà đầu tư chỉ nên chọn đầu tư thụ động (mua index fund).