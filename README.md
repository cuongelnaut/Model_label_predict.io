# Model_label_predict.io

I. GIỚI THIỆU

Với sự phát triển vượt bậc của Công nghệ Thông tin
và các lĩnh vực liên quan, việc tìm kiếm việc làm thông
qua internet đã là điều quá bình thường đối với người tìm
việc nói chung và sinh viên nói riêng. Một điều không
thể trách khỏi là lượng thông tin trong các mô tả công
việc là vô cùng đa dạng và có thể diễn tả theo nhiều cách
thức khác nhau. Đối với các nhà tuyển dụng, việc đăng
tin tuyển dụng để tìm ứng viên phù hợp và chính xác là
một việc hết sức cần thiết. Tuy nhiên, các mô tả công việc
thường được gán với nhiều ngành nghề và lĩnh vực khác
nhau. Điều này làm cho các nhà tuyển dụng dễ mắc các
thiếu sót trong việc đánh dấu các ngành nghề liên quan
đến công việc đó khi đăng tin tuyển dụng. Do đó, chúng
ta cần các mô hình giúp phân loại đa nhãn có khả năng
đưa ra ngành nghề hoặc các lĩnh vực có liên quan đối với
thông tin trên từng mô tả công việc. Điều này làm giảm
đáng kể thời gian xem xét, chọn lọc và đăng tin tuyển dụng
của các nhà tuyển dụng.
Bài toán phân loại mô tả công việc thành các lĩnh
vực, ngành nghề là một bài toán phân loại văn bản
(Text Classification). Đây là bài toán ứng dụng Học máy
(Machine Learning) và Xử lý ngôn ngữ tự nhiên (Natural
Language Processing) để dự đoán các ngành nghề, lĩnh
vực dựa vào từng thông tin trong mô tả công việc như
kiến thức, kỹ năng, sở thích,... Tuy nhiên, đây là một bài
toán phân lớp đa nhãn (Multi-label Classification) vì các
mô tả công việc thường sẽ có một hoặc nhiều ngành nghề
tương ứng có liên quan nhất. Bài toán có đầu vào là một
văn bản chứa nội dung của mô tả công việc, sau đó mô
hình sẽ đưa ra dự đoán về các ngành nghề, lĩnh vực có
liên quan nhất đối với mô tả công việc đó. Đầu ra có thể
là một ngành nghề, một lĩnh vực hoặc có thể có nhiều
ngành nghề, nhiều lĩnh vực khác nhau.

II. BỘ DỮ LIỆU

Chúng tôi thu thập dữ liệu ở dạng văn bản từ hai trang
tìm kiếm việc làm online: Vietnamworks và TopCV. Dữ
liệu chúng tôi đã thu thập bao gồm mô tả công việc, yêu
cầu của công việc, và các lĩnh vực trực tiếp liên quan đến
công việc đó (có thể là một ngành nghề hoặc nhiều ngành
nghề). Chứa tất cả 74 các nhãn ngành nghề có
trong tập dữ liệu. Tập dữ liệu sau khi được thu thập có
40090 dòng.
