# The - Definitive - Guide

#Chapter 1

##Google RankBrain: Giải thích trực quan
RankBrain là một trí tuệ nhân tạo mà Google sử dụng để sắp xếp các kết quả tìm kiếm. Nó cũng giúp Google sử lý và hiểu các truy vấn tìm kiếm.

Vậy điều gì làm RankBrain khác biệt?

Trước RankBrain, 100% thuật toán của Google được viết bằng tay.
Vì thế quá trình sử lý được diễn ra như thế này:

![1](https://cdn-backlinko.pressidium.com/wp-content/uploads/2017/11/1_2_google-engineers.png)



Tất nhiên, Các kĩ sư con người vẫn làm việc trên thuật toán. NHưng ngày nay, RankBrain cũng làm điều đó trong nền.

Nói ngắn gọn, RankBrain tự điều chỉnh thuật toán

Tùy thuộc vào từ khóa, RankBrain sẽ tăng hay giảm bớt tầm quan trọng của backlinks, sự mới mẻ của nội dung, chiều dài của nội dung,
cơ quan tên miền, etc.

Sau đó, Nó nhìn vào cách người tìm kiếm của Google tương tác với kết quả tìm kiếm mới. Nếu người dùng thích thuật toán mới hơn nó sẽ giữ lại. Nếu không, RankBrain sẽ quay lại thuật toán cũ.

Đây là phần điên rồi nhất:

Google yêu cầu một nhóm kỹ sư xác định trang tốt nhất cho một kết quả tìm kiếm và họ cũng yêu cầu RankBrain.

Và RankBrain thông minh hơn các kỹ sư 10 %.

![2](https://cdn-backlinko.pressidium.com/wp-content/uploads/2017/11/1_4_accuracy.png)

Nó ngắn gọn, RankBrain làm việc. Và nó ở đây.

Bây giờ cái bạn đã thấy tổng quan về RankBrain. Hãy tìm hiểu sâu hơn cách nó hoạt động.


#Chapter 2

##RankBrain có 2 công việc chính:

1. Hiểu các truy vấn tìm kiếm (các từ khóa)
2. Đo lường cách con người tương tác với kết quả (sự hài lòng của người dùng)

Hãy phân tích từng phần. 

##Cách mà RankBrain hiểu bất kì thứ gì bạn tìm kiếm.


Một vài năm trước, Google có một vấn đề:

15% từ khóa mà mọi người đã nhập vào google chưa từng thấy trước đây.

15% có lẽ nhìn không nhiều. Nhưng khi bạn sử lý hàng tỷ tìm kiếm một ngày, điều đó có nghĩa là 450 triệu từ khóa làm Google bối rối mỗi ngày.

Trước RankBrain, Google sẽ quét các trang để xem nó có chứa các từ khóa mà ai đó tìm kiếm không.

Nhưng bởi vì  những từ khóa này là thương hiệu mới, Google không có đầu mốt về cái mà người tìm kiếm cần. Vì vậy họ đoán.

Ví đụ, Giả sử bạn tìm kiếm “the grey console developed by Sony”. Google sẽ tìm các trang có chứa các điều kiện "grey", “console”, “developed” và “Sony”.

![3](https://cdn-backlinko.pressidium.com/wp-content/uploads/2017/11/2_2_search-keywords.png)



Ngày nay, RankBrain thực sự hiểu cái mà bạn yêu cầu. Và cung cấp kết quả tìm kiếm chính xác 100% :
![4](https://cdn-backlinko.pressidium.com/wp-content/uploads/2017/11/2_3_rankbrain-results.png)

Không tệ.

Những gì đã thay đổi? Trước, Google sẽ cố gắng kết hợp các từ trong truy vấn tím kiếm của bạn với các từ trong một trang.

Ngày nay, RankBrain cố gắng tìm hiểu ý của bạn.Bạn biết đó, giống như một con người.
Làm sao? Bằng cách kết hợp những từ khóa chưa bao giờ thấy trước đây với các từ khóa Google đã thấy trước đây.

Ví dụ, Google RankBrain có thể nhận thấy rằng có rất nhiều người tìm kiếm “grey console developed by Nintendo”.

Và nó học được rằng những người tìm kiếm“grey console
developed by Nintendo” muốn nhìn thấy tập hợp các kết quả về tay cầm chơi game.

Vì thế khi ai đó tìm kiếm“the grey console developed
by Sony”, RankBrain đưa lên kết quả tương tự cho từ khóa nó đã biết  (“grey console developed by Nintendo”).

Vì vậy nó cho kết quả về các tay cầm. Trong trường hợp này là PlayStation.

![5](https://cdn-backlinko.pressidium.com/wp-content/uploads/2018/01/2_4_rankbrain-method.png)

Một ví dụ: một thời gian trước khi Google công bố một bài đăng trên blog cách mà họ sử dụng máy móc để học cách hiểu rõ hơn về ý định của người tìm kiếm:

![6](https://cdn-backlinko.pressidium.com/wp-content/uploads/2017/11/2_5_google-open-source-blog.png)

Trong bài viết này họ miêu tả một công nghệ được gọi là “Word2vec” biến từ khóa thành khái niệm

Ví dụ, Google nói công nghệ này “ hiểu rằng Pháp và Paris là liên quan giống như Berlin và Đức (Thủ đo và quốc gia) và không giống như Madrid và Italy”.

![7](https://cdn-backlinko.pressidium.com/wp-content/uploads/2017/11/2_6_country-and-capital.png)


Mặc dù bài đăng này không nói cụ thể về RankBrain,
RankBrain có khả năng sử dụng công nghệ tương tự.

Nói ngắn gọn: Google RankBrain vượt trội so với so sánh từ khóa đơn giản. Nó biến từ khóa tìm kiến của bạn thành các khái niệm và cố gắng tìm thấy các trang bao gồm các khái niệm đó.

Ở chapter 3 Tôi sẽ cho bạn thấy làm thế nào điểu này thay đổi cách chúng ta nên nghiên cứu từ khóa SEO. Nhưng đầu tiên, hãy xem phần thú vị nhất của RankBrain.

##Cách RankBrain đo lường sự hài lòng của người dùng

Chắc chắn rồi, RankBrain có thể lấy một cú đâm vào sự hiểu biết từ khóa mới.Và nó cũng có thể tự tinh chỉnh thuật toán

Nhưng câu hỏi lớn ở đây là: Khi RankBrain hiển thị một tập hợp các kết quả shows a set of results, làm cách nào để biết liệu chúng có thật sự tốt không?

Vâng nó quan sát:

![8](https://cdn-backlinko.pressidium.com/wp-content/uploads/2017/11/2_7_rankbrain-uses-ux-signals.png)

Nói cách khác, RankBrain cho ta thấy một tập hợp các kết quả tìm kiếm mà nó nghĩ bạn sẽ thích. Nếu nhiều người thích một trang cụ thể trong kết quả, nó sẽ cho trang đó tăng hạng.

Và nếu bạn không thích trang đó? Nó sẽ bỏ trang đó và thay thế nó bằng một trang khác. Và lần tới ai đó tìm kiếm với từ khóa đó (hoặc một thuật ngữ tương tự) họ sẽ thấy nó hoạt động như thế nào.

Cái mà RankBrain quan sát chính xác?

Nó rất chú ý tới các mà bạn tương các với kết quả tìm kiếm. Đắc biệt, nó xem xét:

    Tỷ lệ kích có tổ chức
    Thời gian dừng lại
    Tỉ lệ thoát
    Pogo-sticking

Đây gọi là tín hiệu trải nghiêm người dùng (Tín hiệu UX ).

Hãy xem xét một ví dụ:

Bạn căng cơ lưng sau khi chơi. Vì thế bạn tìm kiếm “bị căng cơ lưng” trên Google.

Giống như hầu hết mọi người, bạn click vào kết quả đầu tiên. Không may, phần mở đầu có nội dung ngoài lề(“Lưng của bạn là một nhóm cơ quan trọng...”).

Vì thế bạn ấn quay lại và kiểm tra kết quả thứ 2:

![9](https://cdn-backlinko.pressidium.com/wp-content/uploads/2017/11/2_9_pogo-stick-effect-1.png)


Cái này không tốt hơn. Nó có các lời khuyên chung chung như “ Nghỉ ngơi và chườm đá lưng của bạn”.

Vì thế bạn lại ấn quay lại một làm nữa và ấn vào kết quả thứ 3.
![10](https://cdn-backlinko.pressidium.com/wp-content/uploads/2017/11/2_10_pogo-stick-effect-2.png)


Bingo! Đó là hết quả chính xác cái mà bạn đang tìm kiếm.

Vì vậy thay vì ấn trở lại, bạn mất 5 phút đọc qua các cách trị liệu vật lý của trang. Và bởi vì bạn có những gì bạn muốn bạn không trở lại kết quả tìm kiếm.

Việc quay lại và ra được gọi là “Pogo-sticking”. Đó là một cái gì đó mà RankBrain rất coi trọng hành động đó.

Nếu Google được thông báo rằng mọi người nhanh chóng rời khỏi trang và click vào một kết quả tìm kiếm khác, điều đó gửi một thông báp mạnh mẽ tời Google:
“Trang đó không tốt!”.
![11](https://cdn-backlinko.pressidium.com/wp-content/uploads/2017/11/2_11_pogo-stick-effect-3.png)

Và nết Google được thông báo rằng nhiều người dừng pogo-sticking lên một kết quả cụ thể, nó sẽ đẩy trang đó lên để trang đó tìm kiếm dễ dàng hơn.

Tôi sẽ nói nhiều hơn nữa về tín hiệu UX trong Chapters 4
và 5. Nhưng bây giờ, là thời gian để tôi cho bạn thấy cách mà RankBrain thay đổi cách hoạt động nghiên cứu từ khóa.
Nghiên cứu từ khóa trong thế giới RankBrain.