# Natural_Language_Processing_DS310
GÁN NHÃN TỪ LOẠI TIẾNG VIỆT TRÊN BỘ DỮ LIỆU VLSP2013

- **Mô tả bài toán :**

  - Trong ngữ pháp, từ loại chính là các thành phần
nhỏ của một câu văn hoặc câu nói gồm danh từ
(noun), động từ (verb), tính từ (adjective), giới từ
(preposition)... Ngoài ra, trong các ngôn ngữ khác
nhau có những hình thức từ loại khác nhau. Ví dụ
tiếng Nhật có đến ba loại tính từ, tiếng Anh thì
chỉ có một; tiếng Trung, tiếng Việt còn có thêm
các lượng từ trong khi các ngôn ngữ ở châu Âu lại
không có.

  - Hiện nay có nhiều phương pháp gán nhãn POS
khác nhau, ở đề tài này chúng tôi nghiên cứu hai
phương pháp tiêu biểu là Dự đoán theo xác suất
(Probabilistic Methods) và phương pháp gán nhãn
bằng cách sử dụng mạng nơ ron.

- **Mô hình embeding :Word2Vec,FastText.**
- **Mô hình Deep learning :GRU, LSTM, Bi-LSTM.**
- **Kết Luận :** Trong nghiên cứu này, nhóm chúng tôi đã tiến hành
thực nghiệm các mô hình phổ biến trong xử lý
ngôn ngữ tự nhiên như GRU, LSTM, Bi-LSTM
để gán nhãn từ loại tiếng Việt dựa trên bộ dữ liệu
VLSP2013. Ngoài ra chúng tôi cũng sử dụng thêm
một mô hình xác suất đặc biệt đó là Hidden Markov
kết hợp với thuật toán Viterbi để tìm được đường đi
(dãy) của các nhãn từ loại. Kết quả thu được khá tốt
ở các mô hình với độ đo f1 xấp xỉ 0.7 đến 0.8. Dựa
vào kết quả này, chúng tôi bước đầu đã xây dựng
được nền tảng cho tác vụ gán nhãn từ loại tiếng
Việt, trong tương lai chúng tôi sẽ nghiên cứu các
hướng phát triển mô hình mới phù hợp hơn nhằm
tăng độ chính xác cho kết quả
