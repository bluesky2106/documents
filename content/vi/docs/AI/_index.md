---
title: "AI"
linkTitle: "AI"
weight: 10
description: >
  Chuyên mục trí tuệ nhân tạo AI.
---

{{% pageinfo %}}
*Trí tuệ nhân tạo (AI) là gì và nó hoạt động như thế nào ? Tại sao những năm gần đây, AI càng ngày càng trở nên phổ biến và len lỏi vào hầu như tất cả các lĩnh vực của cuộc sống con người ? Những câu hỏi trên sẽ dần được hé lộ trong chuyên mục này.*
{{% /pageinfo %}}

## Trí tuệ nhân tạo là gì ?

**Trí tuệ nhân tạo** (Artificial Intelligence - AI) là một thuật ngữ dùng để chỉ sự mô phỏng các quá trình suy nghĩ của con người bằng máy móc, đặc biệt là hệ thống máy tính. AI được sử dụng để tạo ra rất nhiều chức năng và tiện ích, bao gồm hệ thống chuyên gia, xử lý ngôn ngữ tự nhiên, nhận dạng giọng nói và thị giác máy.

Trí tuệ nhân tạo (Artificial Intelligence) được bắt đầu nghiên cứu từ thập niên 1950, với các cánh chim đầu đàn như Allen Newell và Herbert Simon (hai người sáng lập phòng thí nghiệm trí tuệ nhân tạo đầu tiên ở Đại học Carnegie Mellon), cùng với John McCarthy và Marvin Minsky (hai người sáng lập phòng thí nghiệm trí tuệ nhân tạo tại trường đại học MIT, năm 1959). Đến thời điểm hiện tại, trí tuệ nhân tạo đã được ứng dụng trong rất nhiều lĩnh vực của đời sống và chúng dần thay thế sức lao động của con người trong rất nhiều ngành nghề. Các sản phẩm của trí tuệ nhân tạo đã vượt qua trí thông minh của con người trong rất nhiều lĩnh vực đòi hỏi tính logic cao như các môn cờ (cờ vua, cờ tướng, v.v...), cũng như hàng nghìn công việc khác nữa. Sắp tới, các xe ô tô tự lái ứng dụng trí tuệ nhân tạo có thể sẽ được thả rong lái xe trên cao tốc và thậm chí các sản phẩm dự đoán giá cổ phiếu có thể được sử dụng phổ biến nhằm tăng lợi nhuận giao dịch ở phố Wall.

## AI hoạt động như thế nào ?

Trí tuệ nhân tạo (AI) có thể được phân loại thành bốn tập con khác nhau dựa trên phương thức học :

- Supervised Learning (Học có giám sát)

- Unsupervised Learning (Học không giám sát)

- Semi-Supervised Learning (Học bán giám sát)

- Reinforcement Learning (Học Củng Cố)

Với mỗi phân loại khác nhau, chúng ta có thể hiểu là mô hình AI sẽ hoạt động khác nhau. Vì vậy, để trả lời cho câu hỏi **"AI hoạt động như thế nào"** thì chúng ta cân phải biết được mô hình AI mà chúng ta đang xây dựng hay sử dụng thuộc phân loại nào trong bốn phân loại kể trên.

### Supervised Learning (Học có giám sát)

Với phương thức học có giám sát (Supervised Learning), một machine learning pipeline đơn giản sẽ gồm các bước được mô tả như hình bên dưới:

<image src="ml-pipeline.png" width=75%>

- **Data Collection**: để huấn luyện cho mô hình AI thì chúng ta cần phải có dữ liệu. Dữ liệu có thể được cào từ các trang web trên internet, hoặc chúng ta cần phải bỏ tiền để mua license từ các vendor - những người "chủ" của dữ liệu mà chúng ta muốn lấy để sử dụng. Sau khi thu thập dữ liệu, thông thường chúng ta sẽ lưu các dữ liệu "thô" này vào *Datalake*. Với GCP thì Datalake thông thường là Cloud Storage, còn với AWS thì S3, là những dịch vụ lưu trữ các các file ảnh, csv, html, v.v...

- **ETL**: Dữ liệu thô sau khi đã lưu trữ ở Datalake sẽ được "làm sạch" (clean) hoặc "làm giàu" (enrich) bằng cách bỏ bớt các dữ liệu thừa, thêm siêu dữ liệu, v.v... Sau đó, dữ liệu tinh này sẽ được lưu vào **Technical Database** hoặc **Data Warehouse** và được dùng để phân tích tìm ra các "câu chuyện" ẩn đằng sau các dữ liệu này. Hoặc dữ liệu tinh cũng có thể được sử dụng để xây dựng các mô hình AI phục vụ cho các bài toán cụ thể nào đó.

- **Training**: Như đã đề cập ở bước trên, dữ liệu sau khi được "làm mịn" sẽ được sử dụng để huấn luyện các mô hình AI. Sau khi huấn luyện, chúng ta sẽ được các mô hình với các tham số đạt được sau khi huấn luyện. Mô hình này sẽ được sử dụng cho việc dự đoán (predict) đầu ra (output) với các đầu vào (input) mới.

- **Interference**: dự đoán (predict) đầu ra (output) với các đầu vào (input)

## Tầm quan trọng của AI

AI đang len lỏi vào mọi lĩnh vực trong cuộc sống của chúng ta từ y tế, ngân hàng tới giải trí ... cho thấy tầm quan trọng của công nghệ trí tuệ nhân tạo trong đời sống nhân loại.

Đã xa rồi thời con người phải làm mọi thứ thủ công. Ngày nay, đa phần công việc được máy móc, phần mềm hay các quy trình tự động hóa đảm trách. Không ai có thể phủ nhận vai trò đặc biệt của AI (trí tuệ nhân tạo) trong những tiến bộ công nghệ hiện đại.

Hiểu đơn giản, AI là ngành khoa học về máy tính và các loại máy được phát triển trí thông minh giống như con người. Nhờ đó, những thiết bị vô tri có thể thực hiện công việc từ đơn giản tới khó khăn, thay thế sức lao động của nhân loại.

Hệ thống AI hiện nay đã đủ hiệu quả để giảm sự có mặt của con người trong lao động ở nhiều lĩnh vực khác nhau. Với lực lượng lao động công nghệ này, công việc được hoàn thành nhanh chóng và với độ chính xác cao.

Một thế giới với năng xuất lao động cao và không sự cố, sai sót là mục tiêu chính của các nhà nghiên cứu AI. Không chỉ các ngành công nghiệp sản xuất, công nghiệp nặng, lĩnh vực ngân hàng và tài chính cũng bắt đầu ứng dụng rộng rãi công nghệ này.

Ở hai ngành trên, các hoạt động hàng ngày đòi hỏi phải được thực hiện với độ chính xác cao và tiêu tốn nhiều thời gian, nhân công, tuy nhiên luôn tiềm ẩn nguy cơ xảy ra lỗi do yếu tố con người. Những công việc như đầu tư, vận hành tài chính, quản lý tài sản... được hỗ trợ bởi AI đã chứng minh hiệu quả rõ rệt, đồng thời tiết kiệm được nhiều thời gian.

Y khoa càng không thể đứng ngoài xu thế sử dụng AI, thậm chí có thể nói trí tuệ nhân tạo đã thay đổi những gì ngành lĩnh hội từ vài năm trước. Những thành tựu mới đạt được xem là đáng kinh ngạc trong công tác chăm sóc sức khỏe, đặc biệt với sự xuất hiện của y tá ảo cá nhân.

Các robot tự động trang bị kiến thức chuyên ngành giúp hỗ trợ nhanh cho bệnh nhân, trả lời các câu hỏi thường gặp hay lên lịch khám nhanh chóng chỉ trong tích tắc.

Còn rất nhiều ngành, nghề khác cho thấy sự phổ biến của AI đang có tác động tích cực tới hiệu suất công việc. Như trong lĩnh vực điện thoại di động, AI đã len lỏi vào chiếc smartphone bé nhỏ, tích hợp vào camera, chip xử lý để tối ưu hóa việc sử dụng điện thoại của người dùng. 

Trong lĩnh vực này, Oppo là hãng đầu tiên ứng dụng AI và camera chụp hình với sản phẩm F5. Khi người dùng chụp ảnh selfie, AI quét các đối tượng của con người trong hình ảnh. Đồng thời, dựa trên cơ sở dữ liệu hình ảnh toàn cầu khổng lồ của từ Beauty Lab của Oppo, AI sẽ nhận ra và thực hiện các cải tiến làm đẹp phù hợp nhất cho từng cá nhân. Với camera sau, AI cũng giúp nhận diện được bối cảnh chụp là món ăn, thú cưng, phong cảnh... để đưa ra các giải pháp bắt trọn vẻ đẹp chân thực. Các sản phẩm mới đây của hãng như F7, F7 Youth, R15 Pro cũng được đánh giá là lợi hại nhờ AI.

Ngoài ra, cũng phải kể đến đóng góp của AI trong các ngành công nghiệp nặng, lĩnh vực hàng không, giải trí...

Ngày nay, nhiều kỹ sư đang thiết kế máy móc theo hướng học tập từ cấu tạo bộ não con người sau đó sao chép, ứng dụng trí thông minh. Dù vẫn còn nhiều thách thức, hướng đi này đầy hứa hẹn. Khi AI sao chép được bộ não người sẽ mở ra cánh cửa giúp chữa trị các tổn thương não, bệnh tật... đồng thời khiến trí tuệ nhân tạo có tác động lớn hơn tới xã hội, có thể vượt qua những gì mà loài người đang đạt được.

CEO Google, Sundar Pichai từng chia sẻ niềm tin rằng AI sẽ có tác động lớn hơn tới thế giới. Theo ông, trí tuệ nhân tạo là một trong những phát minh quan trọng nhất mà con người đang phát triển. "AI quan trọng hơn điện, hoặc lửa", người đứng đầu Google nói.

Là lãnh đạo của một trong những hãng công nghệ hàng đầu thế giới hiện nay và đang ứng dụng AI trong rất nhiều lĩnh vực hoạt động, kinh doanh, ông Pichai nhận định AI có tiềm năng để biến cuộc sống của con người tốt hơn trong tương lai.

"AI có thể mang tới những tiến bộ lớn lao nhất mà con người sẽ được chứng kiến", CEO Google nhấn mạnh.

Điều này hoàn toàn có khả năng trở thành hiện thực khi các nhà khoa học tin rằng trí tuệ của máy sẽ vượt qua bộ óc loài người. Theo đó, sẽ có ngày hệ thống AI làm việc với toàn bộ công suất, tái sáng tạo thế giới mà loài người biết tới ngày nay.

Giới nghiên cứu tin rằng khi ngày đó đến, sẽ không còn cảnh phân biệt đối xử đẳng cấp giữa các cá nhân và con người được giải phóng khả năng để có thể phát triển tới mức cao hơn, từ đó tiếp tục phát triển lên một tầm mới.

Tuy nhiên, viễn cảnh tươi đẹp đó cũng không thể tránh khỏi những nguy cơ nhất định. Một trong những mối lo lớn nhất hiện nay là khả năng công nghệ vượt qua tầm kiểm soát và quay lại phá hủy, tấn công loài người.

Hiện có không ít tổ chức và nhà khoa học đang thúc đẩy những quy định về ứng dụng và đạo đức của AI trong cuộc sống con người. Đây không chỉ là vấn đề của riêng quốc gia nào mà trở thành mối quan tâm quốc tế và sẽ cần rất nhiều luật lệ, định hướng quản lý cũng như lộ trình để phát triển song song với kiểm soát công nghệ này.

## Tiếp theo

* [Machine Learning](/docs/machinelearning/): Get started with machine learning
* [Deep Learning](/docs/deeplearning/): Get started with deep learning
