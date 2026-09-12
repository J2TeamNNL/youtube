# Lập trình Web cơ bản - Buổi 19 - PHP - CRUD 2 bảng liên kết

- Video ID: `MemEhFGO2X0`
- URL: https://www.youtube.com/watch?v=MemEhFGO2X0
- Published: 2021-12-07
- Duration: 1h 45m 15s (6315s)
- Language: vi
- Subtitle source: auto
- Kind: live

## Transcript

[00:00:06] à à
[00:00:10] anh alo
[00:00:13] Ừ ok em
[00:00:22] chấp nhận là do là hôm thì chủ nhật mới
[00:00:24] là chỉ nên là hôm nay mình vẫn cảm thấy
[00:00:25] ra à
[00:00:30] áo kiểu cách 1 ngày livestream một lần
[00:00:33] công nhận là cũng dày đặc đúng ạ Không
[00:00:36] biết các bạn thế nào nhưng mà có bạn thì
[00:00:40] bảo với mình là hiểu giúp là bạn ấy đôi
[00:00:43] khi cuối tuần mà mới rảnh thì bạn đấy
[00:00:45] cậu cuối tuần mà phải xem một phát 3
[00:00:48] video Rồi mỗi video phải hơn tiếng
[00:00:51] nghe cũng khá là mệt nếu mà học dồn đấy
[00:00:53] là không ổn lắm
[00:00:56] à vì học lập trình của mình nên chải đều
[00:00:59] nghĩa là thánh chỉ là nếu mà phù hợp
[00:01:02] nhất thì nếu mà không kiểu Xem trực tiếp
[00:01:06] được hết thì ạ Vẫn nên một ngày xem cách
[00:01:09] ra bởi vì mình đã dạy cách rồi thì các
[00:01:12] bạn xem cách hơn là kiểu một ngày dồn
[00:01:14] hết vào trong 10 ngày cuối cùng cuối
[00:01:17] tuần do mà ngồi xem hết thì
[00:01:21] khó khó để mà làm được
[00:01:24] À hôm nay ra ăn sớm như thế này nhưng mà
[00:01:25] mình
[00:01:29] mình có mỗi cái tâm sự hôm trước mình
[00:01:31] nói lại mỗi một cái
[00:01:33] em
[00:01:36] nghe Bây giờ mình tranh thủ đang có ít
[00:01:39] bạn ở đây mình xin cho hỏi trước thì hồi
[00:01:41] trước là cái
[00:01:43] mình mình trong nón mình từng tham gia
[00:01:46] công ty cấp thì công ty cấp và từ hỏi
[00:01:50] mình coi rất là hai cái câu họ có hỏi
[00:01:51] khiến Kiều
[00:01:54] ở chỗ dạng là thơm các bạn hai cái câu
[00:01:57] này nghe nhạc trên mạng suốt rồi nhầm
[00:01:58] như là
[00:02:00] bạn phải luôn trả lời được rồi câu hỏi
[00:02:04] đó là tôi là ai đúng các bạn nghe câu
[00:02:05] nói về chị ạ
[00:02:09] I và mục đích sống của tôi là gì với cậu
[00:02:14] Bây giờ thích thì các bạn có thể trả lời
[00:02:16] trước là có người đi không ạ
[00:02:20] bạn thử nghĩ xem trả lời được câu ấy giờ
[00:02:22] gen liên quan đến triết học nhiều hơn đủ
[00:02:26] chia ly thứ tôi là ai ngoạn mục đích
[00:02:29] sống của tôi là gì
[00:02:31] em đã từng có rất nhiều người trả lời
[00:02:35] cái câu là cái câu tôi là ấy chỉ đứng
[00:02:36] tên của họ
[00:02:39] cái việc ví dụ Giả sử tôi là ai Tôi là
[00:02:41] Nguyễn Nam Long thì nó trả nghĩa gì cả
[00:02:44] thì thực sự người ta nghe những xăm gạo
[00:02:50] đề thi
[00:02:53] thì các bạn sẽ phải trả lời cái câu tôi
[00:02:56] là hay sao cho người ta hình dung được
[00:02:59] ra con người bạn mặc câu đấy phải là một
[00:03:02] câu nên là trong một câu thay vì câu quá
[00:03:03] dài dòng
[00:03:05] một câu kiểu
[00:03:07] chi tiết
[00:03:09] ờ ờ
[00:03:12] có một cái câu kéo dạng là các bạn không
[00:03:16] để liệt kê ra giả sử Tôi là Long tôi là
[00:03:18] là kiểu
[00:03:22] áo kiểu là lập trình viên Vân Vân các
[00:03:25] thứ thứ đâu là con người hài hước hay
[00:03:27] cái gì đó
[00:03:29] Ừ nó nào giống như là kiểu trên tình đời
[00:03:31] chẳng biết ở trên tin domain không giới
[00:03:34] thiệu bản thân như thế nào trên đi đâu ở
[00:03:37] thôi tôi giới thiệu bản thân bay bướm
[00:03:39] kêu dạ thôi
[00:03:42] copy mấy cái ở 22 hay đăng lên đấy ý cho
[00:03:44] người ta nghĩ mình có vẻ hay hài hước
[00:03:51] như đại Khánh Thế cái cái cái công ty đa
[00:03:53] cấp đấy
[00:03:57] Cho hỏi hỏi tôi câu đấy xấu rồi cùng thì
[00:04:01] còn còn bảo là bây giờ các bạn thử viết
[00:04:06] lại à à viết lại là mục đích sống của
[00:04:09] bạn là gì ra xử là
[00:04:13] là bây giờ bạn tưởng tượng là bạn à
[00:04:17] Khi bạn mất đi thần tượng là bạn sẽ chết
[00:04:20] thì thì người thân của bạn
[00:04:23] sẽ cậu nói gì
[00:04:26] có đền đám tang mạnh không mà phải 5tam
[00:04:29] bạn sẽ nói gì này họ sẽ
[00:04:33] họ sẽ nhiều gì nhất về bạn đấy
[00:04:35] cái đấy nó sẽ trả lời rồi sau cái câu
[00:04:39] tôi là ai cũng của của mấy ông
[00:04:41] à
[00:04:44] nghĩa làm chỉ là lúc lúc đấy Xong rồi họ
[00:04:47] còn mở cái nhạc của Quà Tặng Cuộc Sống
[00:04:49] như vậy áo phải Quà Tặng Cuộc Sống Nó là
[00:04:51] kiểu đánh nhạc của Secret gardens nhớ
[00:04:54] thế tôi mà em ở đây trong bị ăn mòn
[00:04:57] khuyên bất ngờ cả nhà cái khác sầu thôi
[00:05:00] tôi mua xem à Thôi ngồi Cố viết cái kia
[00:05:03] cũng nghĩ về tưởng tượng cảnh mình mất
[00:05:06] thôi rồi cậu vì giờ người thân mình có
[00:05:08] thể buồn vì mình như nào vớ vẩn rồi kết
[00:05:11] hợp với bản nhạc vậy chuyện nó cả khán
[00:05:15] trường đấy ảnh khóc cười vì thế khi mà
[00:05:18] mạng bọn Bằng cấp thì làm xong việc ở
[00:05:20] ông ngồi khóc Hai ông ngồi cười vì nó là
[00:05:25] nó điểm rồi Nó kêu là nó lừa được bởi vì
[00:05:29] bản chất là lúc đấy thì ông sẽ
[00:05:33] áo kiểu gỡ bỏ cái Hạnh bức tườngbức
[00:05:36] tường ông đã giao ra đời mà
[00:05:40] cậu Chạm vào nó thì giờ bọn nó thể len
[00:05:42] lỏi vào trong tình cảm uống Nhưng suy
[00:05:45] nghĩ là em cũng sẽ hiểu chị nay chuyện
[00:05:47] bởi lời nói nó giờ thấy thấy thấy thấy
[00:05:50] nói chung là cái buổi khóa lần đấy tôi
[00:05:53] đi Ừ thôi bảo tôi tham đa cấp là đẹp hả
[00:05:55] đi đèo gái
[00:06:00] thì cái buổi lần đấy Thôi đi
[00:06:03] hội Hảo lên đấy thấy thành công phết Cái
[00:06:05] kiểu đó
[00:06:09] họ còn họ còn là lừa được theo vụ là cả
[00:06:13] các bạn phải có nhìn à Các bạn ơi nghe
[00:06:16] cái vụ mà đi qua than hồng nữa chỉ có
[00:06:18] than hồng ngược trở lại không phải có
[00:06:21] lửa đâu mà đi qua than hồng Nếu bận than
[00:06:22] hồng ở nhiệt độ
[00:06:25] tháng nồng nhiệt độ nóng bao nhiêu tiền
[00:06:27] rồi đấy ở người ta bảo nói chung là
[00:06:29] 2.000 độ hay cái gì đó nghe mày nói ghê
[00:06:32] rồi bảo là nếu mà chân của mình bình
[00:06:34] thường chạm vào đấy lâu sẽ bị bỏng đúng
[00:06:37] không Nhưng mình phải có niềm tin là
[00:06:38] mình thấy bước quá nhanh được đấy vân
[00:06:42] vân đấy Hay sao ngồi cậu mọi người có
[00:06:45] tin tôi không là họ làm
[00:06:48] lòng khoan khoan qua hiểu cái kiểu nói
[00:06:52] trước nó có rất nhiều cái trò hỗ trợ
[00:06:56] mạng khơi gợi lòng tin lòng trắc ẩn đủ
[00:07:00] cơ thể loại trong cái cái buổi hội thảo
[00:07:03] đấy còn thêm cái vụ là
[00:07:07] à à vụ là kêu bây giờ từng thành viên
[00:07:09] trong nhóm Các bạn sẽ
[00:07:13] chị sẽ ngã với người về phía sau và
[00:07:15] những người có lại sẽ đỡ bạn mà không
[00:07:18] chỉ đỡ là bình thường mà nhạc người ngã
[00:07:23] ở trên cao xuống cơ của sợ vãi vừa đầy
[00:07:25] tôi không dám làm vì tôi chẳng tưởng đứa
[00:07:26] nào
[00:07:30] và tôi bé nhất ở đây nữa mình kia mình
[00:07:35] người kia Toàn anh chị và các bác ạ
[00:07:41] a nhớ đại khái là cái cái đấy đã khiển
[00:07:44] nó tôi quay quay lại vấn đề một tí Ở đây
[00:07:46] ít khi nó tôi nghĩ về cái kính nghĩa
[00:07:50] cuộc sống của tôi khi mà tôi ra xử là
[00:07:57] Nếu giả sử của bạn được
[00:08:00] bạn là một thiên thần được Phải đến cậu
[00:08:03] Trái Đất những kiểu gì tôi không ngờ cái
[00:08:07] cô ấy câu hỏi hay phết văn vở sẽ đấy thì
[00:08:08] bạn
[00:08:12] sứ mệnh của bạn là gì được cái thế chắc
[00:08:14] chắn không phải đã cho rồi Chạy ghi vậy
[00:08:16] ông đấy
[00:08:20] nhưng mà lúc đấy Tôi nghĩ là kìa Nếu
[00:08:22] thật sự là kiểu mình có một cái gì đó
[00:08:25] Còn mục đích to lớn trong cuộc sống của
[00:08:28] mình thì mình muốn là mình muốn chia sẻ
[00:08:36] kiểu lại là chưa sẻ toàn bộ những cái mà
[00:08:39] mình có thể kích thước có những ngày thứ
[00:08:42] mình cảm thấy hay ho hay là cái tốt đẹp
[00:08:50] mà Đúng đấy Bây giờ tôi vẫn đang
[00:08:52] phấn đấu làm điều đấy Kể tạo việc là
[00:08:55] chia sẻ kiến thức cũng như là
[00:09:00] chia sẻ mấy cái gái xinh hả những bức
[00:09:10] Ừ thôi tôi nhổ đi Cái bộ phải ý nghĩa
[00:09:12] cuộc sống này bởi vì hôm trước cũng có
[00:09:14] một bạn bình luận ở trên cái bài tâm sự
[00:09:18] của tôi hỏi là ông đầy đang bị mất mục
[00:09:20] đích sống
[00:09:23] Ừ thì tôi có khuyên ông đấy là kiểu
[00:09:25] Ê bà
[00:09:27] Ừ cái mục cái mục đích sống ra nó vẫn
[00:09:30] giống như vừa rồi nói về giống như cái
[00:09:34] câu tôi là ai Nó mông lông là nó kiểu
[00:09:38] nó bao la lắm nhiều thế không thấy ai
[00:09:40] cũng trở thành một người ở vĩ nhân được
[00:09:42] có người này người kia đúng không ạ
[00:09:46] Nếu mà chắc chắn ở mình khó chịu với có
[00:09:48] nhiều bạn bảo là mục đích sống của tôi
[00:09:51] là tiền bụng vết xấu cho là ăn
[00:09:55] cái mục đích bạn ấy nói có lấy không
[00:09:57] biết đùa hay thật nhưng mà tầm nhìn thấy
[00:09:59] nó bị hại quá đúng không ạ
[00:10:02] du lịch sử và mình có một cái mục tiêu
[00:10:05] gì đó to lớn cao lớn tí
[00:10:08] mẹ con mình cố phấn đấu vì nó thì hơn
[00:10:12] thay vì nó những cái hạn hẹp vừa rồi bởi
[00:10:14] vì nghèo thì ông vẫn có tiền 12 nghìn
[00:10:16] tiền
[00:10:22] Ê mèo nằm thấy ăn được loại vân vân Nếu
[00:10:24] mà ông có mục đích to lớn thì ông sẽ làm
[00:10:27] được những người to lớn là thôi
[00:10:29] à à
[00:10:29] a
[00:10:33] good fella server với tên miền nhưng nó
[00:10:43] chắc là bạn cứ hỏi thế chắc lại Xem lại
[00:10:47] phải cốt các bạn xem lại file cốt của
[00:10:49] bạn đấy thường là mặc định là file tên
[00:10:59] à à
[00:11:05] Ok
[00:11:08] hôm nay không biết tâm sự thêm cái gì hả
[00:11:11] mọi mình lâu mình còn chưa Chấm bài
[00:11:14] không không bị lừa à
[00:11:23] ý nghĩa có bạn trả lời mấy câu xin đây
[00:11:26] vậy ạ
[00:11:35] a a
[00:11:38] đấy còn chưa chữa về khâu SQL là đấy
[00:11:58] với bạn này về cơ bản thử nó 7 cũng làm
[00:12:23] A2 ở Thôi bây giờ nghỉ tranh thủ đi trả
[00:12:25] lời trước mấy câu này xong rồi hôm buổi
[00:12:27] hôm nay cũng thể sẽ dài nữa nên là mình
[00:12:28] sẽ
[00:12:31] thì mình dậy nhé
[00:12:34] đầu tiên thì hôm trước có bạn hỏi câu
[00:12:38] này cái câu trong cốt của mình tự nhiên
[00:12:40] có thêm cái đoạn cao sao các bạn biết
[00:12:43] các bạn nhớ cái dòng này nó nằm ở chỗ
[00:12:46] đoạn nào thấy tính năng nào thì có sinh
[00:12:47] ra cái đoạn này không ạ
[00:12:59] đi tí mình sẽ nhắc lại nếu mà có đề cập
[00:13:02] đến nó là này nhá
[00:13:11] ông
[00:13:13] bố ngồi cái Đoạn này đoạn phân tranh này
[00:13:16] đoạn này là cậu để mà đến trên tổng số
[00:13:20] tổng số sản phẩm này tổng số gì đó để
[00:13:23] phân tranh dọn
[00:13:26] những lúc lười thì thầy làm gì à
[00:13:29] Dạo này tôi đang bị lừa đấy tôi bị lừa
[00:13:34] cốt thấy cô ngồi chơi game thôi à
[00:13:36] ừ ừ
[00:13:38] Cô lười các bạn sẽ chơi game nghe nhạc
[00:13:46] Cũng Hôm trước có bạn hỏi về cái vụ là
[00:13:48] thế thì mình đang làm đó theo mô hình
[00:13:52] thác nước À thì mình xin phép chia sẻ
[00:14:04] các bạn các bạn sẽ hiểu xanh nước đấy Nó
[00:14:07] là kiểu nó bản chất là nó chạy nó chảy
[00:14:10] từ trên xuống dưới nó không có kiểu nó
[00:14:13] không có kiểu là chửi ngược lại đúng ạ
[00:14:17] thì thì gần như là cái mô hình thác nước
[00:14:19] nó sẽ như này hình này cũng phải tương
[00:14:22] có vẻ tương đối đúng thì mình sẽ nói Tại
[00:14:23] sao từng nói đúng
[00:14:28] Ô kìa Ở đây các bạn sẽ thấy là được đầu
[00:14:31] tiên là sẽ có các yêu cầu này sau đó
[00:14:36] thiết kế này thì thì mình kể về vụ đồ ăn
[00:14:37] các bạn cũng thế
[00:14:42] mình sẽ có những người yêu cầu phải phải
[00:14:45] ghi đặc tả cho các thứ là kiểu
[00:14:48] bên admin thì sẽ cần những tính năng gì
[00:14:50] bên khách hàng cần những tính năng gì
[00:14:53] Chuẩn bị buổi tối tôi sẽ bắt máy Ông
[00:14:55] phải ghi tất cả những cái điều đấy tiếp
[00:14:58] theo là cho từ đó chúng ta sẽ thiết kế
[00:15:00] cứ kêu cái gì thiết kế và giao diện
[00:15:02] thiết kế với cơ sở dữ liệu thiết kế về
[00:15:05] sơ đồ thực thể này đấy
[00:15:09] khi cây và ở đây thiết kế này nó sẽ bầu
[00:15:12] có phân tích nhá đó là phân tích xem là
[00:15:14] tính năng tính năng này phải cần làm như
[00:15:17] nào vân vân vân đấy
[00:15:19] Ồ không tôi không chuyên về anh đi mê
[00:15:22] xuân của cs đâu Tao không thấy đâu
[00:15:25] Tôi không dậy chưa người xét mà tắm rồi
[00:15:27] có một cái trang chuyên dậy CS rất là
[00:15:30] hay Tôi định chia sẻ trong mấy ông nhưng
[00:15:32] mà tôi nghĩ là
[00:15:35] mấy đó không cần nên chuyên CS tôi không
[00:15:38] dậy ông kia đã hỏi đây cái cây này
[00:15:42] online Totoro này cái nhà chuyên dạy CS
[00:15:45] và kiểu cốt từ đầu đến cô ấy
[00:15:48] bạn ấy không nói gì cả đâu với ông ạ Bạn
[00:15:51] ấy có đến đâu ơi cho xem đến đấy hay
[00:15:58] đi
[00:16:06] a tiếp theo là làm thì mình sẽ lập trình
[00:16:08] nó giống họ mình dựa theo những cái
[00:16:10] thiết kế mình lập trình Natri xong rồi
[00:16:13] mình sẽ test để mà kiểm tra kiểm tra lại
[00:16:17] hết một lượt xem nó ổn hay không Nhưng
[00:16:19] mà thực ra trong ở đây Thế Thực ra nó
[00:16:22] hơi bị như mình vẫn nói thời gian nó vẫn
[00:16:24] còn hơi bị sai một tí bởi vì té xong mà
[00:16:26] đương nhiên mà có lỗi thì anh em mình
[00:16:28] cũng phải vòng lại đây là trình không ạ
[00:16:32] nghĩa ghế đoạn này thì ra chuẩn đoạn này
[00:16:35] nó sẽ phải hơi bị
[00:16:38] cái đoạn này có thể nó là vòng lặp
[00:16:42] ở đoạn này có thể ở phòng lập kiểu lập
[00:16:46] trình sau đó thì test so Nếu có test mà
[00:16:48] vẫn còn lỗi Huệ lập trình cái thứ Nói
[00:16:51] chung riêng đoạn này lặp lại thôi Sau đó
[00:16:53] thì tết xong rồi thì sẽ nhận sản vip loi
[00:16:56] tất cả kiểu đầy nó lên trang web các thứ
[00:17:00] thứ triển khai nó đúng không ạ sau đó
[00:17:04] thì cái vụ bên tên là để bảo trì bảo trì
[00:17:06] bản chất là nó cũng sẽ đến nó có thể
[00:17:07] quay lại cái con này
[00:17:10] phần kiểu lập trình sau lại test nó cứ
[00:17:12] thứ
[00:17:15] nhưng mà về cơ bản thì nó vẫn là mô hình
[00:17:18] theo nước tất cả vào water flow tự water
[00:17:19] food tới ga ở chạy từ trên xuống dưới
[00:17:23] tại tại tại sao lại có cái mô hình này Ừ
[00:17:29] cái mô hình này nó dụng khi nào để và nó
[00:17:31] sẽ phù Nói chung là nó phù hợp trong
[00:17:33] trường hợp nào nó phù hợp trong trường
[00:17:38] hợp mà các bạn muốn làm một cái dự án
[00:17:41] trong một khoảng thời gian xác định Gia
[00:17:42] Xử giống như là
[00:17:45] đó là sự giống như là bên A
[00:17:46] ở
[00:17:48] bên làm đồ án của mình chỉ trong vòng
[00:17:51] hai ba tháng nữa là sẽ phải sóng Grow
[00:17:54] bán thì nó khá phù hợp trong ô tô Ford
[00:17:55] theo kiểu là
[00:17:59] mình mình phải chốt thời gian chứ nếu mà
[00:18:01] làm theo kiểu mô hình khác theo tưởng mô
[00:18:05] hình thật sự là không bị lỗi là
[00:18:09] cơm đâu mà IP đồ
[00:18:13] lên đầu nha à
[00:18:15] Anh ở trung mô hình này thì nó sẽ thường
[00:18:18] ngay quay vòng trở lại cứ xong tính năng
[00:18:21] nào đó thì mình sẽ lại kiểu kiểm tra lại
[00:18:24] xem nó phù hợp với không do người còn
[00:18:26] phát triển thêm tính năng nữa nghĩa là
[00:18:28] cái mô hình này phù hợp để phát triển
[00:18:30] thêm nhiều tính năng nữa các thử hướng
[00:18:33] để cho sản phẩm trở nên hoàn thiện nhưng
[00:18:35] mà chính vì như thế thì các bạn sẽ gần
[00:18:37] như không bao giờ có chuyện nhảy sang
[00:18:40] phần được sang phần kiểu cái tinh xong
[00:18:43] rồi diploid cả vừa việc các bạn tốt quá
[00:18:47] như là gian ở dai Đúng rồi Tao gửi ở ra
[00:18:48] à
[00:18:49] thì
[00:18:52] các bạn sẽ tốn quá nhiều thời gian cho
[00:18:55] gái vụ phát triển cái cái đấy phù hợp để
[00:18:59] làm về phố đắp và hợp cho việc là có một
[00:19:02] bên nào đó bà lại em muốn làm bao nhiêu
[00:19:04] bao nhiêu thời gian được miễn là ngon
[00:19:07] lành cành đào cho anh chú ngọn gió rất
[00:19:07] trong tâm
[00:19:09] [âm nhạc]
[00:19:13] thực là cái cái cái đấy nó còn phải phù
[00:19:15] hợp với việc vào ngân sách thoải mái bởi
[00:19:17] water Phone này thì nó hợp với cái kiểu
[00:19:20] là ví dụ như lúc đầu ông cho tôi 200
[00:19:24] triệu thì tôi sẽ chỉ làm đủ sản phẩm kẹo
[00:19:27] nó ổn phù hợp với giá 25 triệu con dẻo
[00:19:30] dai thì thì nó là nó sẽ còn quay lại hỏi
[00:19:32] khách hàng xem là khách hàng ưng này
[00:19:35] chưa Khách hàng đó điều chỉnh nữa vân
[00:19:37] vân thì chả nó tiền nó sẽ bị đẩy lên
[00:19:39] công chuyện ở khách hàng sửa miễn phí
[00:19:42] không ạ trấn thành ra là nó vừa bị rồi
[00:19:45] thời gian nó vừa kẹo
[00:19:48] kẹo làm cho nó các bạn mệt hơn cá nha bộ
[00:19:50] phim
[00:19:52] Nghe bài hát thành ra là
[00:19:56] mình mình thì chỉ dạy các bạn đồ án theo
[00:19:59] mô hình có được vô thôi nhưng mà đi làm
[00:20:01] nhưng các bạn sẽ thấy nó khác đi làm các
[00:20:04] bạn sẽ thấy nó theo kiểu bây giờ chủ yếu
[00:20:05] là slime
[00:20:09] ở dai đầu nhọn photo foody hợp để làm
[00:20:12] cho mấy kiểu water phone lại hợp cho
[00:20:15] mình cái dự án rất là to Điền hiệu của
[00:20:18] chính phủ của mình theo kiểu là một vì
[00:20:22] Ngân sách nó sẽ chỉ có gần đấy tia không
[00:20:26] bao giờ hơn và phải bắt buộc trong một
[00:20:28] khoảng thời gian nhất định không phát
[00:20:33] gạo là không không được phép kiểu thay
[00:20:35] đổi thời gian lắm Hay ra là kiểu những
[00:20:38] cái dự án đấy Xin chào bạn thấy là làm
[00:20:41] xong rồi Gần như là người ta sẽ ít Ít
[00:20:44] tính năng và ít bạn chì kẹp Thế thì tác
[00:20:46] hại bảo trì
[00:20:49] ở đây do có rất nhiều trang web
[00:20:51] trang web
[00:20:53] á của chính phủ hay phần mềm của chính
[00:20:56] phủ mà Ông thấy là tiền có thể tìm tỷ
[00:20:59] đấy nhưng mà thật là kiểu trong nó cứ bị
[00:21:03] cũng cũ và nó ít thì năng tự thứ nó cửa
[00:21:06] bị khô xơ ấy đúng không
[00:21:14] à à
[00:21:17] Ừ nếu hiểu đi
[00:21:20] khi tôi đề cập Thế thôi nha Tôi không có
[00:21:21] nó
[00:21:24] động chạm gì đâu tiếp theo
[00:21:29] Thế à HTML và mà gần thì nên đi thực tập
[00:21:31] Fan thấy bác em ạ Phan ông Quý sanh ra
[00:21:35] được 3 cái đúng cái sai ra được ok Thì
[00:21:39] bạn này biết chồng có về biết hiểu đã
[00:21:43] cửa là cả bên file xử lý file và cả bác
[00:21:47] em nữa thì thực ra là nếu không nên biết
[00:21:49] về xử lý với bảo lương cũng sẽ giữ hậu
[00:21:53] hĩnh không phải về mỗi giao diện nữa
[00:21:56] bộ phim
[00:21:59] ở những nhưng mà mình nghĩ là cái này
[00:22:02] thì bạn đấy phải theo thêm hướng gì nữa
[00:22:05] vì hát về giao diện thì về các bạn thì
[00:22:06] các bạn kiểu gì sẽ khởi động một tí theo
[00:22:09] diện theo kiểu là phải có mắt thẩm mỹ
[00:22:13] với Lý Còn bác em thì đúng chuyên về xử
[00:22:15] lý hơn không cần phải kiểu có mắt thẩm
[00:22:18] mỹ lương bây giờ hai bên nó đều tương
[00:22:20] đương nhau nếu mà các bạn làm đều liên
[00:22:23] quan bên xử lý
[00:22:26] ở trường hợp một bạn bỏ giữa chừng thì
[00:22:29] nhóm đó dậy sao hả anh Ờ cái này thì ra
[00:22:31] còn tùy Bởi vì trong tuần này của mình
[00:22:35] Mình vẫn đang khá thoải mái em cả là
[00:22:37] mình đang kêu gọi là vẫn còn nhiều nhóm
[00:22:39] vẫn còn chưa có bạn nào cơ chưa Bạn nói
[00:22:43] lại Mình ra thì mà có nhóm thì mới chỉ
[00:22:45] có một bạn
[00:22:48] thì nên là mình đang xem cuối tuần này
[00:22:51] xem tình hình các nhóm như thế nào để có
[00:22:53] thể có thể là trong tuần này vẫn còn thì
[00:22:57] có thể điều chỉnh để sắp xếp loại 1 và
[00:22:58] nhóm
[00:23:03] Vì thế nên con con sau đó nữa thì thì
[00:23:05] mình sẽ cân nhắc trong một vài tình
[00:23:07] huống là chị ạ Có thể bạn ấy sẽ chuyển
[00:23:11] sang làm một mình thật ra là cho dù kể
[00:23:13] cả làm một mình hay làm hai mình vẫn sẽ
[00:23:16] có nhóm mà bạn kia làm nhiều hơn bạn còn
[00:23:19] lại vẫn chỉ là bạn còn lại vì vấn đề gì
[00:23:21] đó bạn ấy kiểu không theo kịp với Vân
[00:23:24] Vân không làm được như vòng bạn kia trở
[00:23:28] lại thì thì mình mình không biết mình
[00:23:31] nói các bạn chưa Rồi Long Bình chấm mình
[00:23:33] chấm thì sẽ là Dựa theo
[00:23:36] sự cố gắng của từng cá nhân chứ không
[00:23:41] phải là mình chấm cả thời trang web
[00:23:45] bạn nào Ví dụ như mình nói là bạn nào
[00:23:47] làm bên khách Hạnh bạn bên admin đúng ạ
[00:23:49] Bạn làm bên admin thì mình sẽ chấm phần
[00:23:51] bên em nhìn bạn này đã làm không ạ thì
[00:23:55] nó sẽ tách biệt với cái bạn là mấy khách
[00:23:57] hàng Bạn làm cái cái hàng có thể rất là
[00:23:59] đểu thậm chí là trang web bên cái hàng
[00:24:01] chẳng có chỗ nào sẽ được rằng mình sẽ
[00:24:04] không đánh giá cái bạn làm đến 5 inch bị
[00:24:07] ảnh hưởng nó sẽ luôn là độc lập thế nên
[00:24:09] là
[00:24:12] A và đi làm các bạn sẽ thế thôi đi làm
[00:24:13] thì các bạn sẽ cố gắng hết sức của mình
[00:24:16] chẳng ai có quyền đánh giá mạnh Nếu mà
[00:24:19] xử cái sản phẩm nó có vấn đề vì người
[00:24:22] khác cả mọi người ta sẽ không đổi việc
[00:24:25] bạn vì bạn đã cố gắng thử Thế à Thế là
[00:24:29] nên là bây giờ mình cũng sẽ chấm theo
[00:24:31] kiểu hình thức như thế nghe các bạn đừng
[00:24:34] lo khi mà kiểu dạng là sự mình làm bao
[00:24:36] nhiêu việc thằng kia chẳng làm gì cả Nếu
[00:24:37] như các bạn vẫn phải phản ánh lại với
[00:24:40] mình để mình xem mình mình nói bạn đấy
[00:24:44] được không hay là vân vân và nếu mà nếu
[00:24:46] mà Giả sử bạn
[00:24:48] anh không làm được với người ta người ta
[00:24:50] không hề làm gì nữa người ta bỏ chặn ạ
[00:24:53] Bạn sẽ nó nằm một mình ạ
[00:24:56] Ừ thì mình vẫn sẽ giảm việc cho bạn mà
[00:24:58] không cần yêu cầu cái trang web của bạn
[00:25:02] khắc hay lắm đấy trong trường hợp mà giờ
[00:25:04] xử không ghép được bạn với nhóm khác là
[00:25:08] sự đang làm đến 60 phần trăm tiền đâu ở
[00:25:11] trẻ em ạ thì sẽ khó mà ghép nhóm bạn với
[00:25:13] người khác đi
[00:25:15] Ừ thì bạn làm một mình thì chắc chắn à
[00:25:18] Thì vẫn làm được thôi Bởi vì chính mình
[00:25:21] đã từng một mình gánh cả đòn 1 đoàn 2
[00:25:23] đoàn 3 à
[00:25:26] em đứng yên à mình không nói mình có nhà
[00:25:31] người ta hay gì cả mà chẳng qua là trong
[00:25:33] 23 tháng thừa sức bất kì ai làm một mình
[00:25:37] đến một thời trang web quá vẫn quán dư
[00:25:40] thời gian
[00:25:43] à mà trong đi đó mình đã nói đó là mình
[00:25:46] sẽ dạy các bạn từ đầu đến cuối cùng một
[00:25:49] trang web cả tin tức cả bán hàng rồi các
[00:25:50] bạn còn nhiều Xem toàn bộ như thế nào
[00:25:53] mình gõ Cốt lại thì cũng cũng tương đối
[00:25:56] tương đối với da đồng 10 sản phẩm rồi
[00:25:59] i7 thế nên là các bạn không phải lo họp
[00:26:02] với đi đấy Không phần loi thời gian này
[00:26:05] không cần lo vị thành viên mình này mà
[00:26:07] chị lo chính bản thân mình xem mình có
[00:26:10] theo được hay không thôi Thế thôi Bọn
[00:26:13] tiếp theo cái này tổ chức một lần hả
[00:26:17] Thầy cái ý bạn này hỏi về cái việc à
[00:26:19] bảo vệ quán này thì thực ra mình đang
[00:26:21] định là cũng chưa Mình có đăng này mà sẽ
[00:26:24] là tâm mà mua tháng một mình sẽ mở thêm
[00:26:27] cho vay nhóm nữa có thể
[00:26:29] anh cũng bắt tay vào làm nhưng mà sẽ bảo
[00:26:32] vệ sau vậy Sao bọn mình
[00:26:35] Ừ nếu giờ 23 tháng nữa thì chắc là mình
[00:26:37] sẽ bảo vệ phải chắc là 6 tết nhà như sau
[00:26:40] Tết âm hi vọng sau Tết âm Mấy ông không
[00:26:43] có bị ăn bánh chưng xong quên hết ông ạ
[00:26:45] ạ
[00:26:49] các bạn có vừa nãy mình mới xem là có
[00:26:52] bạn hỏi là nếu làm vài vết và một cái
[00:26:55] cha mà chứa các mã không tồn tại thì trả
[00:27:00] về nun hay là báo lỗi thời gian thì cả
[00:27:03] hai nó vẫn đều là người dùng không được
[00:27:04] phép đi
[00:27:07] Ừ thứ nhất là người giàu không được phép
[00:27:09] nhìn thấy cốt mình lỗi anh đúng không ạ
[00:27:13] người dùng sẽ cần nhìn thấy cái gì người
[00:27:14] dùng cần biết phải quay trở lại trang
[00:27:17] khác hòa vào với đường lên khác đúng ạ
[00:27:19] thì các bạn thì chả biết trang trắng
[00:27:22] tinh Nếu mà hiểu về cơ bản thì chả thấy
[00:27:25] cha trắng tinh thôi cũng được rồi Nếu mà
[00:27:27] bạn hiển thị thêm mấy cái thông báo lỗi
[00:27:29] thì dùng biết thì quay trở lại nữa thì
[00:27:32] càng tốt không ạ không hiển thị lỗi đâu
[00:27:36] nhé Nói chung là là khi mà bảo vệ đồ án
[00:27:39] tới khuya là mấy ông sẽ phải không có
[00:27:41] cái trường hợp nào khi bấm vào một cái
[00:27:44] gì đó nói hiển thị Cái lỗi cốt của mấy
[00:27:48] ông thế là 100 những cái điều tối kỵ khi
[00:27:51] mà cậu Tuyết Trinh đúng hoặc tự nhiên
[00:27:53] hiển thị ra dòng lỗi này lỗi tại dòng
[00:27:56] bao nhiêu Vân chết đúng không ạ
[00:27:59] a tiếp theo nào mình xin phép trả lời
[00:28:03] cái câu mà hôm trước mình đã hỏi đó là
[00:28:06] Đã có lúc ngồi trước thì có lúc mình đã
[00:28:08] từng dùng cái này
[00:28:08] I
[00:28:12] wait you like Các bạn thấy vẫn chạy được
[00:28:15] là xử với mình thử đi mua luôn nóng ạ
[00:28:19] local hót à
[00:28:21] trả lời giao diện khách hàng
[00:28:24] sữa
[00:28:26] giả sữa vào đây
[00:28:29] ở quản lý sản xuất này
[00:28:35] Anh An ninh bấm sữa này các bạn thấy ai
[00:28:39] đi vòng 1 đúng ạ vì chưa và code của
[00:28:41] mình hôm đấy Mình nhớ không lầm là cốt
[00:28:43] của mình hôm đấy đã có
[00:28:45] chị đã có
[00:28:50] Where mã ID ở trong nhà trong trong cái
[00:28:52] giàu nhà như thế này bơ giờ xử mình xóa
[00:28:55] video nháy đi Các bạn thấy thực các cụm
[00:28:57] Cốt nó vẫn chạy như thế cũng chẳng thay
[00:29:01] đổi gì cả đúng ạ Tại sao đầu tiên là tại
[00:29:05] sao đã đó là khi mà quen như thế này thì
[00:29:09] cái ID của mình ở đây nó nó là nó là số
[00:29:12] hàng ra là nó hoàn toàn hợp lệ trong
[00:29:15] trường hợp này theo kiểu là các bạn nhớ
[00:29:19] với mặt với AOE thì số thì có bạn không
[00:29:21] cần phải để trong chống ngáy không ạ
[00:29:24] Ừ nếu mà cũng chính vì cái câu mình vừa
[00:29:27] nói là số không cần để trong rừng ái Tại
[00:29:30] sao mình để nháy làm gì đúng ạ mình xóa
[00:29:32] đi yêu phải trong nó tiện hơn không Cái
[00:29:34] này là liên quan đến để toán là lại liên
[00:29:37] quan Mai toán là cái lập trình viên
[00:29:39] nhiều năm kinh nghiệm người ta sẽ thường
[00:29:42] hay để trong dấu nháy Tại sao ạ bởi vì à
[00:29:46] Nếu vì sau là sử là có vấn đề gì đó kiểu
[00:29:49] dạng ID của mình không phù hợp với làm
[00:29:51] việc theo kiểu là số ngày nữa mà đổi
[00:29:55] sang Dạ chữ được cha và cha gì đó
[00:29:58] Đó là kiểu chữ đó ngoại thì các bạn phải
[00:30:01] sửa lại toàn bộ chỗ cốt mà thiếu dấu
[00:30:03] nháy đấy
[00:30:06] anh bởi vì ở toàn bộ Nếu nó là chữ chắc
[00:30:10] chắn là đây là sự để chữ thản thì đây
[00:30:12] Xóa đoạn này đi các bạn sẽ thấy nó lỗi
[00:30:14] không ạ
[00:30:18] xin lỗi như thế này bởi vì đây bây giờ
[00:30:20] chữ chữa không thỏa mãn nữa rồi Còn nếu
[00:30:22] để trong dấu nháy nó không sao cả
[00:30:25] em đứng yên ở đây vẫn sẽ lỗi nhưng mà
[00:30:27] không phải lỗi con chỉ cần nữa mà lỗi ở
[00:30:29] đây là lỗi là không tìm thấy Không tìm
[00:30:33] thấy cái thằng nào có mã bằng A trong
[00:30:35] trường hợp mà nếu không tìm thấy thì như
[00:30:37] vừa nãy mình vừa nói không tìm thấy thì
[00:30:39] phải phải trả vậy Trang chống mày vừa
[00:30:43] lội hay vì để nó chạy xuống cuối này lỗi
[00:30:45] không ạ thì các bạn Thể chạy đoạn ở đây
[00:30:49] đó là các bạn kiểm tra xem là
[00:30:52] cho mình mình sẽ kiểm tra xem là cậu nó
[00:30:57] có tồn tại tồn tại có bao nhiêu bạn ghi
[00:31:00] không ạ sẽ là kiểu mình sẽ là số bạn đi
[00:31:08] bằng mai que 5 pro II
[00:31:14] bị sốt như lai
[00:31:15] tra lại
[00:31:18] ở đây trong trường hợp nhiễm mại ít
[00:31:25] nằm 5 pro bằng bằng một rất là có một
[00:31:27] bản ghi thì các bạn sẽ in ra
[00:31:33] bộ
[00:31:37] dao này khi các bạn sẽ in ra là một cái
[00:31:39] thẻ hát một chỗ to đây à
[00:31:43] Không tìm thấy
[00:31:45] à à
[00:31:48] anh Treo mày chẳng lại
[00:31:56] ở đó nhớ trong trường hợp mà Các bạn
[00:31:59] truyền mãi mà không hợp lệ làm thì nó sẽ
[00:32:02] như thế này còn nếu mà mã hợp lệ cử như
[00:32:03] thế này
[00:32:05] ở lại mà không hợp lệ lại
[00:32:08] các loại hiệu trưởng
[00:32:11] trở lo lắng chỉ là mình sẽ dùng cái Hàn
[00:32:15] mowry năm dâu đếm xem là là cái kết quả
[00:32:20] trả về nó là bao nhiêu bạn ghi Ừ nếu nó
[00:32:22] là một ẩn gì rất là nó đúng rồi thì mình
[00:32:25] sẽ chạy như bình thường Còn nếu mà em là
[00:32:27] ngược lại đúng không ạ thì mình sẽ in
[00:32:31] thẻ h1o là không tìm thấy Ông Ngoại thế
[00:32:32] được
[00:32:34] à à
[00:32:38] Ừ Ok thì bây giờ mình sẽ
[00:32:41] và buổi hôm nay nhá và Bồ Hôm nay thật
[00:32:44] rất là dài đấy
[00:32:46] bắt đầu từ bây giờ là buổi nào Hùng Tiến
[00:32:50] đấy Chẳng biết là có khó đủ thời gian để
[00:32:52] chia sẻ những bạn thứ hay ho khác không
[00:32:56] hiện đại khái nó sẽ dài đây bây giờ đầu
[00:32:59] tiên thì mình sẽ cầm là lên
[00:33:01] sân bay Đông ạ
[00:33:04] Đúng rồi nhìn cái thẻ đóng hay mở của TP
[00:33:06] như này trong một khá xấu Vì công nhận
[00:33:10] cho khá xấu như này và nhiều lúc của bạn
[00:33:13] mình mình mình là mình thêm cái tiện ích
[00:33:15] Nếu các bạn để ý kĩ là mình thêm với chị
[00:33:19] ích ở đây thông báo là nó có mở mở còn
[00:33:22] đây và đóng ở đây này còn các bạn mà
[00:33:24] quên không thêm cái tiện ích đấy các bạn
[00:33:28] không nhớ được là đã mở Em mở cái ngoặc
[00:33:30] nhọn ở đâu để đóng được đâu các thương
[00:33:32] Nếu mà quên đóng thì các bạn chắc chắn
[00:33:36] nó sẽ bị lỗi như này thôi tôi sẽ bị lỗi
[00:33:40] anh như thế này Cái lỗi này lỗi xin xin
[00:33:43] Alo lỗi của Pháp Nói chung mà các bạn
[00:33:45] làm việc với TP nhiều ấy thì chất rắn à
[00:33:47] các bạn sẽ quen việc nó thông báo rất
[00:33:51] nhiều cái lỗi và các bạn sẽ phải quen
[00:33:57] thì các bạn không quen lập lỗi nói gì
[00:33:59] đấy thì các bạn sẽ không biết cách dbox
[00:34:01] không ạ
[00:34:06] à Hôm nay mình sẽ làm thêm về foods ở
[00:34:08] phố đắt thì bản chất
[00:34:09] khi
[00:34:13] nó là sản phẩm thì tức à
[00:34:16] đây tay để mình Nó qua một tí cũng trước
[00:34:18] là về nhà sản xuất đúng ạ
[00:34:24] Thì bây giờ mình sẽ có đề minh họa nhé à
[00:34:25] là
[00:34:28] một nhà sản xuất
[00:34:31] thì tạo được
[00:34:38] à à
[00:34:45] là một nhà sản xuất thì tạo được bao
[00:34:53] em có nhiều sản phẩm hãy trả lời rồi
[00:34:56] Nhiều lúc ạ ok
[00:34:57] Ừ
[00:35:01] thì mình sẽ để nó lo mặc các bạn kia trả
[00:35:04] lời nghe lời cho bạn biết rồi Tiếp theo
[00:35:07] một sản phẩm
[00:35:23] ở ngoài chuẩn trong trường hợp này là 1n
[00:35:25] và không n vẫn cũng đúng
[00:35:29] Ai bảo Arsenal không cần bắt buộc
[00:35:32] em nấu ăn thường là một sản phẩm thì có
[00:35:35] thể tạo bởi một nhà sản xuất thực ra thì
[00:35:38] topic thực tế thì có thể làm nhiều nhưng
[00:35:40] mà mình làm đơn giản thì nó làm theo
[00:35:43] kiểu mô hình đơn giản đấy thì nó sẽ là
[00:35:46] một thì nó sẽ đơn giản Còn nếu mà theo
[00:35:49] nhiều thì nó bày trò nó phức tạp của nó
[00:35:51] phức tạp hơn
[00:35:53] thì các bạn sẽ thấy là mối quan hệ giữa
[00:35:57] nhà sản xuất với với sản phẩm nó sẽ là
[00:36:00] mối quan hệ một lọ hoa giống như bạn kia
[00:36:03] vừa nãy nói thì có thể không ngờ Tức là
[00:36:07] tất cả ám chỉ là là không chính xác là
[00:36:11] không phải không nở đâu mà nói là
[00:36:13] thì nó vẫn là một lời thôi để làm chị ạ
[00:36:15] một hàng có thể tạo được và không tạo
[00:36:18] được sản phẩm nào
[00:36:19] đề
[00:36:22] thi cái cái vừa rồi mình nói về cái vụ
[00:36:26] một lời ấy tất cả sao Tức là sản phẩm sẽ
[00:36:29] luôn phải lưu lại mã nhà sản xuất phải
[00:36:31] luôn có mãi nhà sản xuất ở trong bảng
[00:36:32] sản phẩm
[00:36:35] đề mà hiểu được là thằng nào thằng tạo
[00:36:37] ra nó
[00:36:41] không phải là nhà sản xuất có mã sản
[00:36:43] phẩm vào nhé bởi vì nhà sản xuất mà lưu
[00:36:45] lại mã sản phẩm thì thành nhà suốt đấy
[00:36:49] lại lưu lại quá nhiều quá nhiều cái sản
[00:36:50] phẩm
[00:36:53] anh theo kiểu là cột đấy nó sẽ thấy cột
[00:36:56] 3 chị thì không tốt mà phải là sản phẩm
[00:36:59] lưu lại mã ngành sản xuất đúng ạ
[00:37:03] Cái này hồi mình dạy về ashwell về lớp
[00:37:05] với sinh viên để cho bị nói qua các bạn
[00:37:07] rồi
[00:37:09] bây giờ thì sản phẩm thường hay mình sẽ
[00:37:14] lưu lại thêm mã này tên này ảnh này
[00:37:16] Ý giá này
[00:37:19] thì các bạn là như thế có thể thêm số
[00:37:21] lượng cũng được nhưng mình khuyên là các
[00:37:22] bạn làm đơn giản thì các bạn không nên
[00:37:26] thêm số lượng Tại sao vì
[00:37:29] vì số lượng nào số lượng các bạn Nhập về
[00:37:33] hay số lượng ba còn trong kho ừ ừ
[00:37:36] ạ Và nếu mà các bạn thêm số lượng là các
[00:37:40] bạn sẽ phải làm là khi mà giả sử mình
[00:37:42] làm trang web bán hàng không ạ táo khi
[00:37:45] mà khách hàng đặt hàng các bạn phải thêm
[00:37:47] một cái đoạn thì kiểm tra xem số lượng
[00:37:49] nó có
[00:37:52] vì nó có đủ thỏa mãn để mà các bạn bán
[00:37:55] sản phẩm đấy không Thế nên mình tạm bỏ
[00:37:58] qua số lượng cứ coi như là số lượng của
[00:38:00] sản phẩm này Thoải mái đi mình đặt bao
[00:38:03] nhiêu thì mình đều có thể mình đều có
[00:38:06] thể sản xuất được đều có thể bán được
[00:38:08] còn nếu mà các bạn lưu lại số lượng thì
[00:38:11] các bạn sẽ phải thêm cái đoạn cốt để
[00:38:14] kiểm tra xem là có đủ số lượng để bán 20
[00:38:17] số lượng còn trống kho này Vân Vân Vân
[00:38:20] thì bài toán ơi nó sẽ phức tạp hơn rất
[00:38:21] nhiều
[00:38:24] anh hạnh phúc nào hơn đấy bởi vì không
[00:38:26] phải mỗi kiểm tra như thế đâu nhá Giả sử
[00:38:29] là các bạn bán đất được một sản phẩm Ví
[00:38:30] dụ ở sử lớp đầu số lượng trong kho của
[00:38:33] các bạn là mười không ạ xong rồi có một
[00:38:36] bạn đặt đơn là bạn 5 cái nó ạ Thì rõ là
[00:38:37] các bạn sẽ phải cập nhật số lượng lại
[00:38:39] chậm kho lại hàng còn 5 chẳnghạn đúng
[00:38:41] không Nhưng mà giả sử là cái khách hàng
[00:38:44] kia lại hủy hóa đơn này đi thì các bạn
[00:38:46] lại phải mất thêm một đoạn cốt nữa thì
[00:38:49] cập nhật lại số lượng đông ạ Các bạn
[00:38:51] hiểu ý mình không ạ thì các bạn sẽ thấy
[00:38:56] đó à sẽ phải làm làm thêm đoạn Cốt và
[00:38:58] kiểm tra khá nhiều với đoạn số lượng là
[00:39:01] Cập nhật lại số lượng nữa
[00:39:03] cho nên à cái bài toàn đấy nó hơi bị
[00:39:05] nghiệp vụ một tí và sáng tạo hơn một tí
[00:39:07] thì mình nghĩ bậy xanh đồ bàn hay nó sẽ
[00:39:09] phù hợp hơn
[00:39:11] chị còn đoán bộ thì mình cứ làm đơn giản
[00:39:12] thì cậu là
[00:39:15] à à hiển thị l sản phẩm cho khách hàng
[00:39:18] đặt đặt được nhiều sản phẩm các thư vân
[00:39:22] vân là được rồi lại thành công luôn đi
[00:39:27] vụ tai nạn tương đối này 55 cụt Đúng rồi
[00:39:29] còn mô tả đúng ạ sản phẩm cái mô tả chứ
[00:39:31] ông không phải nhìn mỗi cái ảnh cho anh
[00:39:34] xem giá phục hồi ông đạt được đúng không
[00:39:40] ạ sửa 6 đi 300 cái chip câu nó là cái
[00:39:43] bên nâng cao ý thì mình sẽ không dậy
[00:39:47] mình không dạy các bạn sử dụng à
[00:39:51] Ê mày cài Apple nâng cao chuyên sâu mà
[00:39:53] mình đã từng dạy các bạn
[00:39:56] ở trong cái
[00:40:00] về thực tế thì mình đã từng nói thực tế
[00:40:03] được là Ý công ty áp dụng mày cả đấy chỉ
[00:40:06] có dụng mỗi view rõ ra
[00:40:10] Index trong dự án thực tế thôi còn chị
[00:40:13] girl này hay là của Cydia thì ít Công ty
[00:40:14] áp dụng mà người ta sẽ ghi thẳng vào
[00:40:17] trong cốc thì xử lý chứ không xử lý em
[00:40:20] sẽ dp như thế mình dậy do các bạn thì
[00:40:23] các bạn biết thôi I
[00:40:28] à à a name nên cứ để 50 thoải mái rồi
[00:40:32] ở đó thì ở đây là ảnh
[00:40:35] ảnh này thì có bạn bảo muốn lưu lại như
[00:40:37] vậy nhưng mà lưu lại nhiều ảnh thì nó sẽ
[00:40:40] phải ba chị đúng không ạ Mình đang lưu
[00:40:42] lại theo kiểu đơn chị là chỉ có một ảnh
[00:40:48] về giá trial
[00:40:52] có đèn flash cũng được à à
[00:40:54] à à
[00:40:55] ở
[00:41:02] description hội chả nhớ viết viết cái
[00:41:10] này nữa cơ đấy Này làm tách này và ờ
[00:41:15] e-manifest ID này kiểu in Ok trong bể
[00:41:23] ảnh 3D để như vừa nãy bạn kia nói về
[00:41:25] khóa khoa ngoại
[00:41:29] ở khoa ngoại khóa ngoài có ngoại thì các
[00:41:32] bạn sẽ Nhấn vsphere ở đây này rồi các
[00:41:34] bạn sẽ tạo khoa ngoại cho nó sẽ là kiểu
[00:41:38] nối cột manifesta này vỡ bạn marphasol
[00:41:43] Tại nó sẽ gợi ý đây cột ID học ở đây còn
[00:41:44] hai cục lên của việc một nếp là unique
[00:41:46] thì các bạn vẫn hình nối được nhưng
[00:41:48] không anh nối yêu đấy cả
[00:41:50] ở đó thì bây giờ nó sẽ có ràng buộc
[00:41:56] khoáng ngoại để ông ạ nghĩa là khi mà
[00:41:58] nhà sản xuất nào mà có sản phẩm rồi thì
[00:42:02] khi mà xóa nhà suốt đây đi sẽ bị cảnh
[00:42:05] báo tám triệu không được phép xóa tại
[00:42:06] Khánh Như thế
[00:42:10] Ok Bây giờ thì
[00:42:12] thì mình sẽ thứ nhất là mình sẽ thêm vào
[00:42:15] trong máy new thế mà trong menu các bạn
[00:42:18] nhờ menu ạ Mình sẽ có ghé Hôm trước mình
[00:42:20] có cái vụ mẹ ngủ đây
[00:42:23] là quản lý nhà xuất giờ mình sẽ thêm
[00:42:32] mà đổi đây sẽ bù đắp ạ
[00:42:35] anh như này
[00:42:37] khi mình bấm lại
[00:42:41] Em không tìm thấy vì chưa có tạo nóng ạ
[00:42:46] tạo phụ đề là phố đắc ý
[00:42:49] À hôm nay mình mình sẽ chốt nhanh hơn
[00:42:52] rất nhiều Sau hôm trước nhé bởi vì mình
[00:43:08] sẽ for PC trên
[00:43:10] Hari White
[00:43:13] menu
[00:43:16] bị fan nằm ngoài
[00:43:18] này
[00:43:26] nhà mình cần kết nối cơ sở liệu đã nóng
[00:43:28] cái nồi cơ sở liệu để mà
[00:43:32] chị địa địa toàn bộ các sản phẩm thì sẽ
[00:43:32] là
[00:43:35] lại thêm liky
[00:43:38] con ếch chấm thấy phê này
[00:43:43] mà cô ấy quelle sẽ là select sao Ford
[00:44:00] ai đi
[00:44:04] nhập mã luôn mã
[00:44:09] trên ảnh giá
[00:44:12] ở mô tả thì có bạn không cần hiển thị vì
[00:44:14] mô tả mà rất là dài các bạn nhưng bấm nó
[00:44:16] xem chi tiết thì hơn
[00:44:25] có ai mình sẽ là phối cái đây này
[00:44:39] Đây là ai đi này nên ô tô này
[00:44:42] và y là giá cho này
[00:44:44] cho
[00:44:48] biết các bạn nhìn cốt có nhìn rõ nhỉ à
[00:44:49] vì
[00:44:52] vậy Nhìn nó rõ nhé
[00:44:54] ừ ừ
[00:44:55] anh
[00:44:58] chàng này không có gì mới chưa có sản
[00:45:15] A
[00:45:33] em Alo ạ Ừ cái mình sẽ copy rồi đoạn này
[00:45:34] đi
[00:45:37] à à
[00:45:42] ừ ừ
[00:45:47] ở đây sẽ có tên YouTube
[00:46:02] lần này mình sẽ dạy cho các bạn luôn cả
[00:46:05] à Hấp load được file này lên luôn không
[00:46:07] ạ
[00:46:42] ở
[00:46:46] mô tả thì nó sẽ đưa kết chân tôi quên
[00:46:51] thế
[00:47:00] có toàn không ngờ cách viết từ đấy trong
[00:47:01] dài vãi
[00:47:25] à à
[00:47:28] Bạn đoạn này các bạn sẽ thấy là trước
[00:47:31] trước trước nghe thấy thì các bạn sẽ
[00:47:33] thấy khó chịu ở cái đoạn này đó là phần
[00:47:35] Nhàn Suốt này các bạn sẽ thành nhập lại
[00:47:37] cái đúng ngay đi của cái nhà sản xuất
[00:47:39] thực ra là người dùng không nhớ được cái
[00:47:42] đi của nhà suốt nó là gì đâu không ạ Nên
[00:47:43] có đoạn này không nên để cho khỏe Ôi
[00:47:46] phút nhập như này Đấy do mình có cái
[00:47:49] loại snack ở trên này mình sẽ là select
[00:47:52] thường người ta sử select toàn bộ
[00:47:53] ừ ừ
[00:47:58] an toàn bộ nhà hàng xuất ở đây sau đó
[00:48:01] thì mình sẽ làm gì mình sẽ có cái ô xà
[00:48:02] lách áp trưng ở đây nào
[00:48:05] mà mình sẽ còn lên mà nó là mono fossil
[00:48:07] luôn
[00:48:12] ai đi và mình sẽ vòng lặp for us như thế
[00:48:21] và mình sẽ và có bao nhiêu thằng có bao
[00:48:24] nhiêu thẳng nhà sản xuất thì mình sẽ là
[00:48:32] mà valeu của cái thương gót chân đấy bản
[00:48:36] chất nó lại là từ ngay đi của cả nhà sản
[00:48:38] xuất chứ không phải từng nêm ở nhà xuất
[00:48:40] tại nó sẽ kiểu như này
[00:48:43] Ừ để khi mình bấm là mình chọn cái gì đó
[00:48:45] như này trở lại thì nó vẫn thêm mày các
[00:48:47] bạn sẽ thấy là nó sẽ chuyên nó thành địa
[00:48:51] chỉ có là ai đi vòng sáu này hoặc có ai
[00:48:53] đi bằng một loại khác như thế như thế
[00:48:58] a
[00:49:01] tiếp theo là
[00:49:05] Em nhớ là phải để mấy thớt của cái phòng
[00:49:13] Và á chân thì sẽ nhảy đêm Cái pha là cô
[00:49:17] set in search này
[00:49:20] và còn thêm một cái nữa đó là nếu mà
[00:49:23] file file ảnh như này đúng hạn thì các
[00:49:25] bạn sẽ phải thêm một cái đoạn nữa là mã
[00:49:29] hóa nó and Chris thôi không nhớ nó lắm
[00:49:33] đâu các bạn thường anh cha em clip HTML
[00:49:35] form như thế này
[00:49:38] thì nó sẽ ra
[00:49:41] thì các bạn copy đoạn này là được đoạn
[00:49:44] này nó là gì chị để cho phép các bạn
[00:49:46] trong phone của hệ truyền đến được file
[00:49:48] đấy
[00:49:51] thứ Ba phải tải lại đúng không ạ
[00:49:54] Ừ để tải được trên Face rồi Cá thứ rồi
[00:49:58] chồng có vẻ Tôi muốn mình sẽ nhập nha
[00:50:01] iPhone không ạ
[00:50:04] em giá 10k
[00:50:06] hình ảnh
[00:50:17] Ừ đúng rồi dùng mấy cái kia thì tốc độ
[00:50:19] truy vấn hay các thứ mọi thứ sẽ nhanh
[00:50:21] không ạ Nhắn chậm là
[00:50:25] ý là bây giờ khi mà lưu lại cái đấy
[00:50:29] trong ta bay thì người đi người sau khi
[00:50:31] người sẽ không biết được
[00:50:33] anh đột nhiên ở tự nhiên ông chạy một
[00:50:35] cái gì đó tự nhiên ngày kia đó lập tức
[00:50:38] được chặn mà trong khi đó mò cốt mãi
[00:50:40] không thấy thì ông sẽ thắc mắc mà giờ họ
[00:50:43] rất khó để sửa không không biết gì không
[00:50:46] sửa được cái ra à bây giờ ít công ty áp
[00:50:48] dụng rồi đấy
[00:50:49] ở đây sẽ là
[00:50:52] từ táo cắn dở này
[00:50:57] sẽ nặn em buồn thêm
[00:50:59] ý dĩ nhân bây giờ chưa thêm được không ạ
[00:51:08] mình bỏ qua bộ váy đẹp có thừa thôi nha
[00:51:10] các bạn sẽ phải tự làm virus các thử nha
[00:51:20] hình ảnh này
[00:51:24] chợ hoa ảnh giá Mô tả sản xuất còn thiếu
[00:51:31] Ừ ừ như vậy lại năm cũ thì phải
[00:51:37] xe ô tô đậu hũ
[00:51:38] a
[00:51:48] Hình như đúng
[00:51:49] a
[00:51:57] Ừ nhưng mà cái đoạn này các bạn thấy là
[00:52:00] riêng cái file này hiểu chưa Lên các bạn
[00:52:02] sẽ không dùng được cái đô la poste kiện
[00:52:05] này đâu các bạn sẽ phải dùng cho pha như
[00:52:07] thế này tự nhiên phải thêm chữ s nữa cơ
[00:52:11] thì lòng ra đúng được đâu ạ và đấy Cái
[00:52:14] thứ nhất thứ hai là khi chuyển pha lên
[00:52:17] thế này như mình đã từng nói các bạn Nếu
[00:52:18] mà chưa Nhớ thì các bạn
[00:52:22] bây giờ mình nhắc lại cái local host này
[00:52:23] chính là con máy ảo
[00:52:27] Ừ đúng ạ cái file mình vừa chọn lại từ
[00:52:30] trên cái con mày thật của mình Thức ạ Cứ
[00:52:32] cả máy ví dụ mày chết hàng không ạ máy
[00:52:35] khách hàng 7 cái file ảnh đầy lên con
[00:52:38] máy ảo như này
[00:52:41] có phải đẩy file lên và mình lưu lại cái
[00:52:44] pha đấy ở trên trên con máy ảo của mình
[00:52:47] Tại sao lại phải làm thế ạ Mình cần lưu
[00:52:49] lại và cái ảnh đấy vào trong thư mục gốc
[00:52:52] của mình này lưu lại ở trong cái con máy
[00:52:54] ảo mình ra sự con mèo mình bây giờ trong
[00:52:57] trường học này nó có server tệ tên là j
[00:53:01] high school Đúng không ạ bởi vì à
[00:53:04] Ừ Nếu mình không lưu lại thì mình sẽ
[00:53:04] không
[00:53:07] không thể có thể lần sau giày truy cập
[00:53:09] được cái file ảnh từ trên máy khách hàng
[00:53:11] nữa Đúng là đơn giản thế thôi nghĩa là
[00:53:13] khách hàng ban ảnh lên thì mình phải lưu
[00:53:16] lại để mà Lần sau mình hiển thị lại ra
[00:53:19] gái không ạ Mình mình không thể cái nồi
[00:53:22] để cái ảnh đấy Lần Nữa ở trên máy khách
[00:53:24] hàng được không ạ Mình chưa có thể lưu
[00:53:28] lại trên trên trên chính máy trên gọi là
[00:53:32] chuyến server mình để mình hiển thị ra
[00:53:34] Ừ nó nó giống như kiểu bây giờ mấy ông
[00:53:36] ta lại lên Facebook đấy bản chất là
[00:53:38] Facebook mà sẽ lưu lại ảnh của ông ở
[00:53:41] trên máy chủ của nó để bề mà khi mở Ông
[00:53:43] đăng nhập bằng máy khác thì ông có xem
[00:53:45] được ảnh của ông đối ngoại người khác
[00:53:46] cũng thể xem được ảnh của ông bởi dao
[00:53:48] ảnh đấy ra công khai ở trên máy chủ của
[00:53:51] nó đơn giản thế thôi đúng ạ
[00:53:55] thì cái việc lấy cái ảnh để lên thì rất
[00:53:58] ra mình sẽ dùng cái hàm hàm khi mà cái
[00:54:00] file này được tăng lên nó sẽ luôn nằm ở
[00:54:03] trong thư mục quả là ten nó thư mục tem
[00:54:05] tất cả thư mục tạm thời
[00:54:09] Ừ nó chưa hề được lưu lại ở trong cái
[00:54:12] server của mình các bạn thấy à đâu nằm
[00:54:14] thì có cái ảnh nào đây đâu đúng ạ mình
[00:54:15] Thứ nhất là mình nên tạo một cái thư mục
[00:54:18] để mà chưa cái ảnh đấy thay vì kiểu lưu
[00:54:21] bừa ở bất kỳ đâu thì nó sẽ bị về sau mới
[00:54:23] nhiều ảnh của anh sự giác như các bạn
[00:54:25] nên lưu lại ở trong một thư mục thường
[00:54:28] là mình sẽ lưu lại ở thư mục và đây Giả
[00:54:30] sử Trong trường hợp này mình tại một thư
[00:54:32] mục nữa Đây là thư mục Phố Đôi này ạ à
[00:54:34] Photo để ạ
[00:54:36] Vì mình nghĩ mình nên tắm vào đâu nhỉ
[00:54:39] anh Bởi vì bản chất là
[00:54:42] bên này bên admin à
[00:54:47] bên này bên emminh Bình Tổng thư mục ảnh
[00:54:50] ở cái chỗ ở đây đi là sự tạm đấy nhé ô
[00:54:53] tô ngay đúng không ạ Đấy mình sẽ về sau
[00:54:56] sẽ tống hết ảnh vào trong mục photo này
[00:54:59] vi phạm và cái như mình vừa nói là cái
[00:55:02] thư mục là khi mà ảnh được đẩy lên nó
[00:55:04] luôn lưu hội và trong thư mục tạm thời
[00:55:07] này mình phải chuyển cái ảnh ở thư mục
[00:55:11] tạm thời là như copy nó là chuyển nó vào
[00:55:14] cái thu mục photo này nên là sẽ sẽ có
[00:55:18] khái niệm mà dùng cái hạ mu mu file ảnh
[00:55:23] thử thế thực là mình đang nói về cái kéo
[00:55:26] mặt nhiệm vụ rồi được bạn Tôi cũng không
[00:55:28] nhớ Toàn bộ cốt để làm đâu nên tôi
[00:55:30] thường này lên đây để cốt
[00:55:32] amplified à
[00:55:38] ở tp lapisschool mày ông sẽ lên đây Cốc
[00:55:40] Cốc
[00:55:42] ở đầu tiên ở trên này nó hướng dẫn đầy
[00:55:45] đủ đầu tiên là các bạn phải chỉ là phải
[00:55:48] cho A flash file này thường là server nó
[00:55:50] đôi khi nếu các bạn thấy học sinh thường
[00:55:53] là nó sẽ tắt cái đi chợ này nếu mà lag
[00:55:56] ol2shop in các bạn cài ngay cả cái này
[00:55:57] thường nay được mở rồi các bạn không cần
[00:55:58] quan tâm nữa
[00:56:02] tiếp theo là có cái phom để mà truyền
[00:56:04] file lên này không ạ sau đó thì đây là
[00:56:06] đoạn cốt Bạn cố này đoạn cốc giữ cơ bản
[00:56:10] mà chỉ đơn giản đã có thư có thư mục này
[00:56:13] sau đó đi lấy tên file này sau đó thì
[00:56:16] cái đoạn này thì cốt là để mà cậu anh
[00:56:19] nói chung là sửa lại tên file có thử thứ
[00:56:23] sau đó đi Thanh Vân kiểm tra xem file có
[00:56:26] đúng là file ảnh không file
[00:56:28] ạ sau đó đi đây là
[00:56:30] Ừ đúng rồi Có đúng là file ảnh hay không
[00:56:34] à đấy có thư thực ra là
[00:56:37] em kéo xuống dưới này thì các bạn sẽ
[00:56:39] thấy là ở đây người ta đã vi Hàn đoạn
[00:56:42] cốt rất là dài từ đầu đến cuối cốt là để
[00:56:45] mà kiểm tra xem file phải phải ảnh 20
[00:56:48] này phải đã tồn tại chưa Này độ dài của
[00:56:51] a nội dung lượng của file còn lớn hay
[00:56:54] không này Đấy xong rồi có đúng định dạng
[00:56:57] ảnh ấy không này tại như này
[00:57:00] Ẩm Thực ra là nếu mà các bạn không cần
[00:57:03] phải va biết chị quá như thế này thì nó
[00:57:05] rất là nắn sẽ có một đoạn ngắn hay Thôi
[00:57:08] để tôi trông sẽ nó sẽ chỉ dùng hàng này
[00:57:13] à à
[00:57:26] thì cái test file này chính là cái file
[00:57:30] a file mình sẽ chậu lưu lại nó ở đâu vậy
[00:57:33] Mình tỷ tỷ
[00:57:40] thì nó sẽ lưu lại phải ở đâu cái file
[00:57:42] này như mình vừa nói mình sẽ lại ở trong
[00:58:00] Ừ đúng rồi biết được
[00:58:04] lâu không động và tiếng Anh nháo không ạ
[00:58:06] mày cái chéo nhé bớt mùi thì phải trèo
[00:58:10] nhé Đây là thư mục mà mình sẽ lưu vào
[00:58:14] đúng ạ tiếp theo là tên của Wifi đấy bản
[00:58:16] thân ghẻ phải đăng lên thì có bạn phải
[00:58:19] lấy tên được cái file thì tên file đó sẽ
[00:58:27] xe tải tên file nó sẽ là chế độ này ạ à
[00:58:30] à
[00:58:34] ở lại nó sẽ là
[00:58:38] bí thư mục thư mục mạch kết hợp với cái
[00:58:41] file truyền lên đây này Ở đây trong
[00:58:42] trường hợp file mình chuyển lên nó sẽ là
[00:58:44] cái đoạn này thôi
[00:58:48] photo này mình sẽ lấy bay nên tức là lại
[00:58:56] Chờ Đợi mình tí nhá ở đây nó có kiểm tra
[00:59:09] anh không không không cần không quan tâm
[00:59:12] mình thử bay cái
[00:59:23] Sau đó các bạn sẽ thấy là file nó sẽ cho
[00:59:25] nó sẽ lưu lại ở trong cái đường dẫn là
[00:59:27] như thế này mình đang cần phải lấy cái
[00:59:29] hướng dẫn mà Đây chính là đường dẫn của
[00:59:31] file file nó sẽ có đơn giản là như thế
[00:59:34] này là nằm trong thực sẽ nằm trong thư
[00:59:37] mục photo này tên gốc của nó là như thế
[00:59:41] nào đuôi file đó như thế nào như này Ok
[00:59:44] thì ở đây mình nếu mà đặt tên chuẩn hơn
[00:59:46] thì phải phát file tất cả động dẫn của
[00:59:50] file nói chuyện hơn là như này
[00:59:53] sự thay đổi photo lại thành đoạn này
[00:59:54] được
[00:59:57] đây file lúc đầu sẽ nằm ở trong thư mục
[00:59:59] tạm thời nhá sau đó chuyển vào cái file
[01:00:02] như kia là sao Hay tôi thử chạy thử mấy
[01:00:05] ông xe này ạ
[01:00:08] em có ảnh rồi
[01:00:09] Ừ Ok chưa
[01:00:12] thế nhưng đây sẽ có nhược điểm nó sẽ có
[01:00:15] nhiều điểm bởi vì do cái ảnh vừa rồi của
[01:00:17] mình nếu các bạn để ý cái ảnh của mình
[01:00:20] vừa rồi của mình tên nó là như thế này
[01:00:22] tên nó được cả làm con số ngẫu nhiên gì
[01:00:23] đó rồi
[01:00:31] ạ Bây giờ tôi Giả sử tôi đổi về tên file
[01:00:34] này tên là A chuẩn B ng chẳng hạn đúng
[01:00:36] you are in png Nha
[01:00:40] Ừ tôi chọn lại cái file.vn khuẩn
[01:00:43] Ở đây có thêm à
[01:00:47] Ừ nếu không sẽ xảy ra nó ra đời ảnh a.vn
[01:00:49] đúng nghĩa lấy được đúng cái tên gốc của
[01:00:52] cái file ảnh đó ông ạ ok
[01:00:57] ạ Bây giờ tôi đổi cái file tên là bê tôi
[01:01:00] đội ảnh khác tên là Nhạn bê rất là anh
[01:01:01] khác không ạ
[01:01:07] xe tải tôi lại chọn lại cái ảnh là a
[01:01:09] chấm b ng này đây rất là làng khác Chẳng
[01:01:12] qua trùng tên không ạ bấm và này
[01:01:15] anh không thấy nó bị ghi đè lên bằng cái
[01:01:18] ảnh khác bởi vì sao Bởi vì đơn giản thôi
[01:01:21] bởi vì nói chung Tết đúng ạ thì cái cái
[01:01:23] trường hợp này là cái trường hợp mà
[01:01:26] không nên không nên đó làm chỉ các bạn
[01:01:28] nếu mà vẫn giữ nguyên cái tên file ảnh
[01:01:31] mà khách hàng đẩy lên đấy Chắc chắn là
[01:01:33] ảnh để có thể bị trùng tên và nó sẽ ghi
[01:01:36] đè lên như thế và ghi đè lên như thế là
[01:01:39] hỏng rồi đúng ạ Vì người dùng đặt tên sẽ
[01:01:42] làm linh tinh không ạ
[01:01:44] Vì thế nên là mình cách làm của mình và
[01:01:46] làm sao cho cái tên file của nó không bị
[01:01:49] chung mà thường không bị trùng thì có
[01:01:51] thể là chơi như cách mà lấy nhiều thời
[01:01:54] gian hiện tại theo kiểu My nó sẽ không
[01:01:57] bờ sẽ rất hiếm trường hợp trùng không
[01:01:58] nói chuyện là hai ông ăn Min cũng đăng
[01:02:02] và cùng cái đi đây cả Không ạ Cái cách
[01:02:05] để lấy tro Ly mình mình sẽ đặt tên file
[01:02:08] nó sẽ bây giờ mình sẽ đặt tên file là gì
[01:02:12] thì mình sẽ đặt tên file là Minisa cái
[01:02:18] cộng với đuôi của file
[01:02:19] a
[01:02:26] Nhưng mà nãy giờ các bạn thấy là để mình
[01:02:29] thử dê dê cái
[01:02:35] à à đẻ mình inna gái này Win
[01:02:39] Photo để các bạn xem qua Cài file ảnh
[01:02:40] của mình bạn chất lúc đầu nó sẽ có những
[01:02:42] cái gì nhé á
[01:02:46] ở đây nó sẽ có là gì
[01:02:50] Anh tên file là gì này định dạng file là
[01:02:56] gì này cái này dậy hơi khó lấy và tiếp
[01:02:59] theo là file đang lưu tại thư mục đường
[01:03:03] dẫn mặc định là gì đó thu mục tạm thời
[01:03:09] nhờ ông ạ và size của pha là gì này à
[01:03:12] Ừ Thì bây giờ mình lấy mình cần lấy cái
[01:03:15] trắng bên là giờ này thì cách để lấy nó
[01:03:18] là mình sẽ lấy á
[01:03:20] và đương nhiên là thường mình thưởng ai
[01:03:23] lấy Sẽ thưởng ai sau dấu chấm
[01:03:26] mình sẽ thường lấy Sau đó chấm
[01:03:29] Ừ mai mình sẽ có về à
[01:03:35] I
[01:03:39] find extension đuôi định dạy một vài này
[01:03:43] sẽ bằng photo tại nêm này
[01:03:47] và sau dấu chấm thì sẽ có dùng hàm acro
[01:03:49] được
[01:03:50] ở
[01:03:55] hà max pro này tức là sao nó sẽ cắt cái
[01:03:56] chuối
[01:03:56] một
[01:04:01] chuỗi tên của ảnh cắt nhau bởi dấu chấm
[01:04:05] và mình sẽ lấy hàng ở vị trí thứ 1 Đức à
[01:04:07] sau khi ở cắt xong mà biến hình mạc
[01:04:11] Thành A là nó sẽ là vị trí không thằng B
[01:04:14] ng sẽ vị trí một mình sẽ lấy thằng vị
[01:04:17] trí thứ 1 thì sẽ ra được đuôi pha
[01:04:20] và bây giờ mình sẽ có
[01:04:25] Anh tên Tiến ảnh sẽ giống như bạn Dũng
[01:04:27] Bùi và nói dùng hạn tham cũng được cái
[01:04:29] lấy thời gian hiện tại nó sẽ là sông Hàn
[01:04:32] tham này sau đó thì nối nhau bởi Dấu
[01:04:33] chấm này
[01:04:48] Sau đó các bạn sẽ thấy nó bây giờ thì
[01:04:51] thể file ảnh nó sẽ luôn nó sẽ là thời
[01:04:54] gian và nó sẽ không có chuyện nói chung
[01:04:56] cái tả lại các bạn thấy thay đổi số rồi
[01:05:00] ông ạ Em ở mình như này đó sẽ ra đời một
[01:05:03] cái ảnh như này Vợ mình tải lại nó lại
[01:05:06] ra ảnh nữa Cái này có hơi bị nhược điểm
[01:05:10] một tí của vì a Chính vì do là nó thời
[01:05:13] gian nó không bao giờ kiểu trùng nên là
[01:05:17] các bạn mà cơ vừa rồi mình Các bạn thấy
[01:05:19] ra cứ mỗi lần mình tại lại trang thì nó
[01:05:21] lại in sốt ra thêm một cái ảnh nữa đóng
[01:05:23] ngoặc thì ra thế này hơi bị nhược điểm
[01:05:26] nên là nhiều nôi thì nó lại làm theo cơ
[01:05:30] chế nó sẽ lưu lại cái ảnh theo ID của
[01:05:33] cái vô Đắc cũng được cũng được làm theo
[01:05:34] kiểu lạ
[01:05:37] Anh làm chỉ làm 11 Cô Đắc thì sẽ không
[01:05:40] một ảnh là sự thế và khi mà
[01:05:44] force xóa đi thì sẽ xóa cái theo cái ảnh
[01:05:47] đấy cũng được không sao cả
[01:05:50] à Còn bây giờ mình chị đã nói vụ là để
[01:05:52] mà tránh chồng đi Đây là một cách không
[01:05:54] ạ nhưng nó sẽ nhược điểm các bạn vừa
[01:05:56] thấy nếu mà ảnh mà giống hệt nhau thì nó
[01:05:59] vẫn sẽ là bị trùng vẫn bị lặp lại đúng
[01:06:03] vì
[01:06:05] sao mình không lấy tên mà nhà sản xuất
[01:06:08] đã không không Mình lưu lại là mình lưu
[01:06:10] lại chóng mã mà mình không lưu lại thiệu
[01:06:12] tên
[01:06:14] vì mình lưu lại trong đêm Bên mình có
[01:06:16] loại theo mã không ạ
[01:06:19] tên có thể thay đổi khuẩn mã gì nó sẽ
[01:06:21] không thay đổi Mình sẽ lưu lại theo cái
[01:06:23] mã thôi
[01:06:24] anh nói chung là nãy giờ này anh khai
[01:06:27] các bạn thấy không bị mất công người
[01:06:30] đoạn mỗi đoạn về ban file lên để bọn
[01:06:32] mình sẽ làm ngay
[01:06:43] lại tôi đang dậy rồi à từ từ có nhiều
[01:06:46] bạn mà biết đoạn này rồi các bạn sẽ thấy
[01:06:48] cát dài lắm
[01:06:51] nhưng mà thế này nó mới kiểu tương đối
[01:06:58] ừ ừ
[01:07:00] Ừ đúng rồi lưu lại theo mã sản phẩm thì
[01:07:02] nó ổn nhưng với các bạn như các bạn sẽ
[01:07:04] phải đi sốt chưa Đã rồi các bạn xưa nek
[01:07:06] lại thì các bạn bị lấy được cái cài
[01:07:11] mã của sản phẩm nhưng mà cái bài toán
[01:07:13] Lưu lại hai mã sản phẩm thì nó phù hợp
[01:07:16] với việc là một sản phẩm một ảnh thôi
[01:07:18] còn nếu mua sản phẩm nhiều ảnh thì cách
[01:07:21] này nó phù hợp hơn lại đâu ạ tất cả các
[01:07:23] bạn lại có thể chơi cái trò là tạo hẳn
[01:07:26] thư mục theo mã sản phẩm sao lưu lại tất
[01:07:28] cả ảnh trong cái Không mục đấy
[01:07:30] tư nhân ảnh vẫn thể chung nhá Nhưng mà
[01:07:32] về sau giải quyết bài toán đơn giản khi
[01:07:36] mà mình xóa sản phẩm thì mình sẽ còn xóa
[01:07:39] cái thư mục theo ID của phạm sản phẩm
[01:07:40] cũng được
[01:07:42] anh nói chung là mình đang dậy vẫn là
[01:07:45] chỉ mức Cơ bản mình chưa nói bài toán
[01:07:48] tối ưu Ở đây các bạn sẽ có thể sẽ thắc
[01:07:50] mắc thì mình mới ra đã chứ bây giờ mình
[01:07:53] mà cứ chuyên sâu về cái tối ưu quá cũng
[01:07:55] như dạy các bạn chuyên sâu quá các bạn
[01:07:57] sẽ thấy nó bị phức tạp lên và các bạn sẽ
[01:08:00] bị đau đầu đúng không ạ Thế mình vẫn thì
[01:08:02] đang dạy các bạn mức tương đối các bạn
[01:08:03] thôi
[01:08:06] nhưng mà các bạn mà hỏi thì mình sẽ trả
[01:08:10] lời ok không ạ Chứ không phải là tôi
[01:08:11] không biết mấy điều đấy đâu
[01:08:13] a cho tôi dậy trong bé ông Toàn người
[01:08:15] nâng cao rồi mấy ông sẽ thấy được quay
[01:08:17] mang tiếng nhà
[01:08:21] cơ bản mà Tôi thấy đau đầu quá thức rằng
[01:08:23] những cái Nãy giờ đang nói nó cũng có tí
[01:08:25] nâng cao tí rồi
[01:08:28] tính đến nhiều trường hợp nó là nâng cao
[01:08:30] đấy ạ
[01:08:31] ở
[01:08:34] chung Kitty linh tinh rồi không có Star
[01:08:35] hiện
[01:08:39] Tôi không cần mấy ông Ba để kiếm thương
[01:08:40] khác nữa nhé
[01:08:42] á đấy thỉnh thoảng quên không đóng phí
[01:08:45] nỗi này thì chả thời đóng kết nối trong
[01:08:46] ngày vui này
[01:08:50] chạy chạy này tạm thời không xem lỗi gì
[01:08:52] cả nhé
[01:08:55] à à quên quên quên bây giờ không phải
[01:08:57] photo là à Bây bị lỗi các bạn cũng thấy
[01:09:01] này I'd like to drink nữa là Cái lỗi này
[01:09:04] lỗi khi mà mạng nó đang bị biến thành
[01:09:05] chuỗi
[01:09:07] bạn trong trường hợp này photo đang làm
[01:09:11] à nếu các bạn vừa nãy để ý không ạ Bây
[01:09:13] giờ mình sẽ chỉ cần lưu lại tên của file
[01:09:16] và đường dẫn mình cái ai đừng dẫn ở
[01:09:18] trong trường hợp này nó sẽ ra phát file
[01:09:21] này sẽ lưu lại cái này
[01:09:22] Anh
[01:09:29] Anh tên file ảnh thì nếu Thế bên phải
[01:09:36] sẽ ra cái này
[01:09:40] nó lấy sẽ là file name
[01:09:43] mà mình sẽ lưu lại file đấy thôi
[01:09:45] ông này chạy này
[01:09:49] khi trở thành công rồi Đúng nãy giờ
[01:09:53] không Nãy giờ chắc là bị khán nhiều thừa
[01:09:55] thừa ảnh
[01:09:57] cách tạo khá nhiều anh không ạ
[01:10:00] Bây giờ mình sẽ là Cô Đắc này các bạn sẽ
[01:10:03] thấy có 2 cái Đây Rồi
[01:10:05] Việt cho Android
[01:10:08] ở cái đoạn này vừa nãy mình bị sai nhưng
[01:10:12] mà héo queo nó bị biến hình kiểu vẫn
[01:10:15] biết hãy lưu lại chữ ra đây buồn cười
[01:10:19] bơ cái ảnh nó ảnh nó sẽ bây giờ mình sẽ
[01:10:21] ra
[01:10:24] chứ không phải là thì địa là chữ ảnh
[01:10:26] ngay đúng không ạ mình sẽ phải là
[01:10:36] Ê bà sẽ thu mục photo Bởi vì các bạn
[01:10:37] nhiều không ạ mình nằm trong thư mục
[01:10:44] ở đây anh ấy bị lỗi chứ chả nôi bởi vì
[01:10:46] rõ ràng này để làm thiếu thông tại đâu
[01:10:47] không ạ
[01:10:51] ông cho hay cho nó là 100 tháng
[01:10:57] ở đó ok chưa em mình sẽ sửa xóa ngoại đã
[01:11:00] sửa xóa
[01:11:03] ảnh này nhạy cảm quá nhỉ Mày không Đừng
[01:11:13] has three là mình sẽ nhận đến format
[01:11:19] Ông mốt nào nó xóa cái bình luận kia hộ
[01:11:23] tôi cả nhìn ngứa mắt mắt sửa à ở đây này
[01:11:38] sau khi mình bấm vào sữa
[01:11:40] cho tôi Tôi làm tình làng xóm cho tôi
[01:11:41] nhìn cái
[01:11:44] hình ảnh hàng nghìn cái ảnh cái khó chữa
[01:11:46] xóa nhé
[01:11:57] Ê bà sẽ Delete này à
[01:12:00] Em bấm vào đây sẽ xóa không ạ nhưng tạo
[01:12:03] phải xoa này à
[01:12:04] ở
[01:12:06] wp
[01:12:17] em copy cái đoạn là
[01:12:20] em kết nối cho thử này cho nhanh à
[01:12:26] Anh và đội đây là Delete from or Where
[01:12:31] ID bằng id chưa xong à
[01:12:34] Ừ mình đang chưa điều hướng gì cả về thế
[01:12:36] là không như mình đã nói mình không nên
[01:12:38] dùng hết đồ sớm muộn gì ạ
[01:12:42] anh Bởi vì kéo nếu mà các bạn cốt của
[01:12:44] vấn đây lỗi gì đó các bạn hết đồ về thì
[01:12:46] không nhỉ Chị không nhìn thấy kịp lỗi
[01:12:52] à à
[01:12:55] vì ai Bây giờ mình sẽ đắp liên kết kẹp
[01:12:57] file ISO
[01:13:03] để nó thành file update đó đi này à
[01:13:07] Ừ nhưng mình lắm sữa đây nhưng mà bây
[01:13:09] giờ bạn thân mà mình cần vẫn phải lấy
[01:13:11] lại thông tin của sản phẩm để màn hình
[01:13:13] thì ra đây Điền chưa tất cả thông tin
[01:13:17] đối ngoại thì sẽ làm như thế nào mình sẽ
[01:13:21] là đã quy kết lên như này một cái sẽ ra
[01:13:22] em
[01:13:24] có đặt này
[01:13:37] Anh bình thường đã đặt tên là mình đặt
[01:13:45] thế này sẽ không bị chung nữa
[01:13:46] thế
[01:14:00] đó là x tại lên à
[01:14:03] chỉ có thế điện tự động Điền không ạ
[01:14:06] Tôi thử trong mấy ông nhé
[01:14:08] xe ô tô
[01:14:12] ở Facebook à
[01:14:14] à à
[01:14:19] vụ bí kíp xuân này à
[01:14:22] Ê mấy ông sẽ thấy có một cái thứ ở đây
[01:14:24] nó không tự động điền được đó chính là
[01:14:27] cái ảnh cái ảnh bản chất nó không thể tự
[01:14:29] động điền được Cho dù kể cả các bạn có
[01:14:30] truyền vào đường dẫn có phải đúng như
[01:14:32] nào nữa
[01:14:35] thì các bạn hiểu mà
[01:14:38] Ê cái cơ chế của thằng này nó không cho
[01:14:40] phép điều đấy nó không cho phép chọn lại
[01:14:43] cái cũ là tính
[01:14:48] a masterpiece Ý bạn là cái phụ là Master
[01:14:51] your hiểu là chia bố cục của trang web ạ
[01:14:54] Anh nhớ em Mình mạnh mình nhớ rồi Khánh
[01:14:57] deepest đấy ạ
[01:14:59] à à
[01:15:02] có cây cây Nói chung ở cái vụ ảnh nó sẽ
[01:15:05] không cho các bạn chọn lại cái hàng cũ
[01:15:08] vì nó không coi chờ đấy Nên là thường sẽ
[01:15:11] có kiểu như thế này thường tôi dậy sinh
[01:15:13] viên sẽ có hai hai cái
[01:15:16] ẩm thực thực sự đá người dùng không
[01:15:20] ở người người dùng đôi khi và sửa người
[01:15:22] ta đôi khi không cần sửa cái ảnh đâu nên
[01:15:29] nên nên làm sẽ là theo cậu là có ông nên
[01:15:31] hệ thứ nhất ở các mông vẫn phải liên
[01:15:32] hiển thị lại ảnh cũ đấy điều chắc chắn
[01:15:34] người dùng biết được có nên sửa hay
[01:15:37] không nhưng mà khi mà người dùng chọn đề
[01:15:40] sửa đâu ạ thì mình mới sửa còn không thì
[01:15:42] mình phải giữ nguyên lại anh cũng phải
[01:15:44] toàn nó phức tạp như thế cơ
[01:15:48] em tắt cái suy nghĩ đen Ok thì bây giờ
[01:15:50] thứ nhất là mình sẽ cân hiển thị ảnh
[01:15:53] cũng như nào đó ngoại chị ăn dặm thôi
[01:16:02] các bạn cũng sợ nhất cái này và sóng đây
[01:16:04] đây là anh cũ
[01:16:11] anh sẽ chiều cao cho nó tắm trăm nữa lại
[01:16:17] Ừ anh sẽ của anh cũng như thế này vào
[01:16:20] đây sẽ là thường là tôi sẽ thiệt cậu đã
[01:16:23] một là đổi mới
[01:16:42] Ừ ok
[01:16:45] thì tức à Một là người dùng có thể vẫn
[01:16:47] là chọn thêm một cái ảnh nào đó mới về
[01:16:49] mà thay đổi ảnh như này hay là giữ ảnh
[01:16:53] cũ không làm gì cả ngoại thì cách tốt ở
[01:16:56] đây có chối nữa đó là mình sẽ vẫn luôn
[01:17:00] chuyển lên cái in bút như để hai bên là
[01:17:05] nên sẽ là photo ô trở lại tất cả ảnh cũ
[01:17:09] tui sẽ vẫn sẽ lấy được tên của cái file
[01:17:15] mà tại sao lại cần phải làm như thế bởi
[01:17:18] vì mình kiểu tí mình sẽ chạy cậu update
[01:17:20] mà ông ạ Mình sẽ update update là mình
[01:17:24] sẽ bế cả photo nữa Thế nên là mình cần
[01:17:28] lấy mình sẽ lấy lại luôn cái tên cũ thì
[01:17:30] mình update vào thì nó sẽ không sao cả
[01:17:31] đúng không ạ
[01:17:34] Ừ nhớ đấy trong trường hợp mà người ta
[01:17:36] không chuyền lạnh mới lên thôi không ạ Ở
[01:17:38] đây các bạn thấy thời gian nó còn thêm
[01:17:41] cái nữa là nó không tự động chọn vào cái
[01:17:43] nhà sản xuất của tôi nhà xuất Tôi vừa
[01:17:45] nãy ra để nó Apple để không sao nhưng mà
[01:17:48] cứ là sự nhà xuất tôi tôi đội hàng ở
[01:17:51] trên database này tự động nhé
[01:17:54] thì mình sẽ đổi nó thành nhà sản xuất
[01:17:58] anh ạ mã là sáu như thế này đúng ạ khi
[01:18:00] bấm máy sưởi chị các bạn thấy thời ra nó
[01:18:03] vẫn chị lấy phòng đầu tiên Vì mình chưa
[01:18:06] tự động chọn nhọn thì mình sẽ chọn như
[01:18:08] nào mình sẽ thường ngay cho một cái ít
[01:18:10] vào đây này Mình đang chạy vòng lọc rồi
[01:18:12] đấy nhé Đây vòng lặp đúng không ạ Mong
[01:18:15] gặp ở đây in tất cả các chân có thể thì
[01:18:18] mình sẽ ít ở đây ở trong vòng lặp
[01:18:23] là nếu mà đủ lợi ích tại manufacturer ID
[01:18:26] bằng bàn với cái
[01:18:29] manufacturer ID này này
[01:18:31] Ừ thì mình sẽ
[01:18:38] selected này
[01:18:41] là là sẽ chọn đúng ạ
[01:18:46] sự tích vào đấy auction Đấy nó như này
[01:18:48] đó các bạn hãy nó sẽ tự động chọn đúng
[01:18:50] không ạ
[01:18:51] à à
[01:18:54] Ừ đúng rồi Nếu mà không phải chuyển lên
[01:18:56] thì mình không ăn bếp Nhưng mà mình mình
[01:18:59] đang định là mình sẽ chỉ ghi đúng câu I
[01:19:01] Swear thôi thay vì phải mất công ghi
[01:19:03] tặng 2 cô gái của em ạ
[01:19:05] anh bởi vì ở nơi thế các bạn sẽ bị đi
[01:19:07] hai câu ghép với anh một câu fpl có cả
[01:19:09] photo và một câu ghép của em là không ăn
[01:19:11] Bim Photo nó không ạ thì thay vì như thế
[01:19:13] thì mình sẽ làm theo cơ chế hết là kẹo
[01:19:16] chị có một con fqr update bao gồm cả
[01:19:17] photo
[01:19:21] đây mình hiểu Ghi các bạn sẽ hiểu
[01:19:23] sửa
[01:19:40] tại thì ah à thực ra nhìn lấy cái đoạn
[01:19:42] cũ này thì hơn nhỉ
[01:19:45] như thế này
[01:19:49] à không nhầm nhầm nhầm nhầm vậy mà nó có
[01:19:57] anh như này thì bây giờ mình sẽ có cái
[01:20:01] photo photo này thử các bạn để photo new
[01:20:08] Nó
[01:20:15] thì
[01:20:18] mình lấy theo Dona paz lại ra khi có va
[01:20:20] luu rồi
[01:20:23] à à
[01:20:24] anh
[01:20:27] Huy không hiểu ý bạn lắm để mình cứ thử
[01:20:30] làm nhé sẽ xem bạn hiểu ý mình không nhá
[01:20:32] Đây giờ sư trọng trường hợp mà mình có
[01:20:35] photo Note này và photo không ạ thì mình
[01:20:37] sẽ kiểm tra xem mà người dùng có chọn
[01:20:40] ảnh 20 trong trường hợp này thì các bạn
[01:20:41] thử xem
[01:20:45] mình thuộc ee2 đường hợp ra để các bạn
[01:20:52] mình sẽ bay kết thúc ngay được lên để
[01:20:55] các bạn xem là là đây đây trong trường
[01:20:57] hợp là sự đây trường hợp không không trợ
[01:21:00] ảnh không ạ bấm và này
[01:21:01] Anh
[01:21:04] Đài đấy rồi mày nghỉ anh em lên nha và
[01:21:07] lạy cha đã vừa nãy vẫn đang nhìn sang bố
[01:21:08] sẽ research
[01:21:11] đây đây trong trường hợp này các bạn sẽ
[01:21:14] thấy alo 4 này sai là không đúng không ạ
[01:21:21] ạ bây bây giờ Nếu giả sử mình chọn cái
[01:21:24] ảnh chọn mảng bất kỳ không ạ
[01:21:28] nó sửa đó thì các bạn thấy là Alo bằng
[01:21:30] không này mà sai và con số lớn không ạ
[01:21:34] Không phải con số không đúng đấy Cái
[01:21:36] cách mình lấy ở đây mình có thể chơi trò
[01:21:39] đó là mình kiểm tra xem lại mình thường
[01:21:41] ấy thường là mình sẽ làm kiểm tra xem là
[01:21:44] cái sai của cái ảnh để nó khó là không
[01:21:58] Cài foto đúng không ạ hồ sơ lưu
[01:22:00] sai
[01:22:06] Nếu bọn nó lớn hơn không Vì sao không ạ
[01:22:10] Nếu nó lớn không thì mình sẽ đi
[01:22:13] em có cái loạn bạn này thôi
[01:22:17] có đoạn này đề mà lưu lại cái ảnh đúng
[01:22:21] không ạ ô tô ở đây đổi với cái photo đấy
[01:22:27] thì cái file name ở đây sẽ như thế này
[01:22:31] và ngược lại thì sao thì cái file name
[01:22:34] của mình chính là cái photo ô như thế
[01:22:39] nghĩa là đang cái ảnh cũ sau đó thì câu
[01:22:42] truy vấn của mình sẽ là
[01:22:51] thật đấy à bù đắp đủ ngoại xét
[01:23:06] cho nên bằng lên này ờ
[01:23:11] còn 5 trường không ạ năm chưa
[01:23:14] sẽ photo này
[01:23:23] know first rowland ai và ai đi à
[01:23:31] mình quên mình quên chưa Nay đi đấy các
[01:23:33] bạn Nếu bạn không nhớ
[01:23:36] thì mình quên chuyện này đi trong này
[01:23:40] mình sẽ để hai bên nên mày đi vào lưu
[01:23:42] cho nó là
[01:23:45] đô la ích tại
[01:23:53] A A Break with mikan nãy giờ mình đang
[01:23:56] lấy lấy hơi sai khi đang lấy thằng đầu
[01:23:59] tiên những nhiều mình quên chưa lấy theo
[01:24:01] đôla ID phòng đôla get ID ở trên này nữa
[01:24:06] quên đấy này ở đây mình sẽ thấy quay lại
[01:24:10] đi vòng cho ID đây nữa
[01:24:12] Ừ nếu mì ông chắc cũng không cho thêm
[01:24:15] Limit một ở đây nữa cho chắc thường mà
[01:24:17] chắc là không có chuyện ai đi chung đâu
[01:24:21] Đi đã bị bấm vào sửa thì nó sẽ làm là gì
[01:24:24] sẽ cảm nhận như thế này tuy nhiên đến
[01:24:26] lợn photo này sẽ sai mà mình sẽ thay đổi
[01:24:28] Photo nó vào đây như thế này mới đúng
[01:24:29] này
[01:24:32] ở trong trường hợp Hạnh bằng tay lệ tôi
[01:24:35] test thử máy ông xem nhé
[01:24:37] anh đã không chọn ảnh hoặc vẫn giữ ảnh
[01:24:41] cũ nhé đổi đây là 12 này Tao cắn giờ
[01:24:43] nhưng vẫn ngon
[01:24:47] giá 12k anh này
[01:24:51] về cơ cấu dự Nguyên này đi anh sữa nè
[01:24:53] anh không thấy lỗi gì cả
[01:24:56] cha không vấn đề gì ở bên tay bề không
[01:24:59] có vấn đề gì Thử sáng B nasware rửa xe
[01:25:12] tí nữa là tao cắn giờ Hà môi chuyện chưa
[01:25:15] đẩy đưa kiếp sân lên chưa chưa sửa được
[01:25:16] Epson họ sao
[01:25:19] Sao lại sửa bí quyết Sơn La
[01:25:23] Nếu như các bạn thấy là 12 12 rồi Ảnh
[01:25:25] vẫn có thể giữ nguyên đúng không ạ Tại
[01:25:39] các bạn chưa đang nói việc là cập nhật
[01:25:42] theo key của code
[01:25:45] anh kia post thì ta vẫn được nhưng mà
[01:25:47] trong trường hợp đấy thì cái phôtôn Ê
[01:25:48] mày nó không đúng lắm
[01:25:52] nhà mình ý bạn là sẽ kiểu kiểm tra theo
[01:25:54] từng ty ở đây đúng không
[01:25:57] ý thì cái đoạn đấy à
[01:26:00] thì mình sẽ chạy vòng sport for Women
[01:26:04] kiểu hòa x từng đi để mình nourish ra
[01:26:13] thế à Các bạn hiểu ý mình cái đoạn vừa
[01:26:16] rồi không ạ Cái cái đoạn này đó là nếu
[01:26:19] mà file file ảnh chuyển lên thì mình sẽ
[01:26:22] cấp cập nhật không ạ Rồi là không truyền
[01:26:26] lên cái ảnh nào thì nó sẽ như thế này à
[01:26:31] có bao giờ sự là mình sẽ truyền phải lên
[01:26:33] như thế này
[01:26:35] Ừ chị ông kia là false
[01:26:38] A7 nhiêu câu
[01:26:43] SQL để mà chen giacco spo2 à
[01:26:46] 77 nhiêu câu I Swear để update bấy nhiêu
[01:26:50] cái trường đó nếu mà update bấy nhiêu
[01:26:52] lần thì thôi Không khuyên mấy ông chơi
[01:26:54] trò này em nhé Không phải truyền bao
[01:26:56] nhiêu lên rồi ông update bấy nhiêu đâu
[01:26:58] Đúng
[01:27:01] Em học việc là định chân risaco Apple
[01:27:04] thì nó hơi bị hơn
[01:27:06] à à
[01:27:08] Ừ nhưng mà thứ là cái nhưng mà các bạn
[01:27:11] vừa nói nó sẽ còn bị lỗ hổng đấy
[01:27:14] Ừ nó bị lỗ hổng về bảo mật nghĩa là nếu
[01:27:18] thế thì có người dùng mà sửa cái nên của
[01:27:21] cái trong post các bạn mà các bạn chưa
[01:27:25] Violet rồi ạ ạ Các bạn chuyển lên sửa
[01:27:27] sửa những cái nó không mình không quy
[01:27:36] anh ấn vào này không thấy lỗi gì cả em
[01:27:38] mình sẽ thử à
[01:27:40] Ô thế Mình chỉ cần quay lại đây rồi tài
[01:27:42] lạnh Trang là được chúng gọi thấy ảnh
[01:27:45] thay đổi tới ủng hộ đúng không ạ tớ ra
[01:27:48] mình đã cập nhật lại ảnh thì thôi
[01:27:50] Ai Cập nhật hàng rồi
[01:27:52] Ừ anh lỗi
[01:27:54] hình ảnh đưa lạ
[01:27:57] ở nhà ở vừa nãy mình đúng rồi Vừa nãy
[01:27:59] mình lỡ nhảy sang file xap Thành bị bị
[01:28:01] pet một cái
[01:28:08] đó các bạn vừa thấy đầy đủ see you d
[01:28:10] Nó là liên kết đến hai bạn nóng bọn nó
[01:28:14] sẽ có thêm câu truy vấn đề em ạ lấy lên
[01:28:17] lấy từ cái bản khác nữa đúng ạ ạ à quên
[01:28:20] quên quên Còn bây giờ nốt nốt nốt Kỳ nữa
[01:28:23] đó là ừ ừ
[01:28:27] nhà mình cần in ra được cả nhà tên nhà
[01:28:29] sản xuất này
[01:28:32] tên nhà sản xuất
[01:28:37] ở đây trả lại thì các bạn sẽ thấy là ở
[01:28:40] trong bảng bản này khi chỉ có ma đâu
[01:28:43] phước trời đi thôi không có tên nhà sản
[01:28:46] xuất không ạ cho mình là tên của gì mình
[01:28:49] sẽ lại cho hay thôi mình sẽ cho ở đây là
[01:28:52] bị cho Model fossil
[01:28:57] on cô đất chấm mà nó Future lại đi bằng
[01:29:03] Mortal chở mai đi này không ạ Và đây
[01:29:06] nhưng mà khi ở các bạn chạy như này nó
[01:29:13] Ừ Thế xem tại xã lỗi nhé các câu truy
[01:29:15] vấn lại mình có gì sai
[01:29:24] các câu truy vấn này cũng nghĩ có gì sai
[01:29:25] à
[01:29:29] Ừ
[01:29:32] nếu mà nó chạy báo lỗi Như CIA tất cả
[01:29:40] à à thiếu chữ s
[01:29:43] à à
[01:29:49] thế này các bạn sẽ thấy là cái cái khi
[01:29:52] mà chạy cái này xong thì cái nêm này của
[01:29:54] mình nó bị ghi đè lên bởi nêm cổ thằng
[01:29:57] montefeltro và IDE thế tất cả những cái
[01:30:00] thằng thằng nó bị do đằng sau Nó sẽ ghi
[01:30:03] đè lên hàng nói trước ngày ra là cách
[01:30:06] tốt của mình thôi Làm ở đây đó là mình
[01:30:10] sẽ thường hay khi forests chấm sao là
[01:30:14] lấy tất cả sự tất cả cột từ bảng cố lắp
[01:30:18] ạ sau đó thì mình sẽ lấy thêm những cái
[01:30:21] cột mình cần lấy thôi từ bảng này và
[01:30:24] mình sẽ đổi tên nó Nó làm an ở for Touch
[01:30:28] ID mà nêm như này xa lạ và đây sẽ là mày
[01:30:31] Future lên như thế này đó thì nó sẽ ổn
[01:30:34] đó các bạn thấy không
[01:30:37] ở đây đây đây là về cơ bản của toàn bộ
[01:30:40] về CRD để mà
[01:30:44] ep3 cậu liên kết 23
[01:30:47] sẽ cho bạn thấy ở thật ra mình cũng nhắc
[01:30:49] đi nhắc lại về máy cày kiểu xem thêm sữa
[01:30:52] Xóa các thư cũng khá nhiều đúng không ạ
[01:30:56] cần nhở cũng bộ ôn tập nữa
[01:30:58] Ừ nhưng mà nói chung à
[01:31:01] Ừ thế này cũng tương đối rồi đấy ạ là
[01:31:04] mình đã làm được tính năng ở bên A
[01:31:05] ở
[01:31:09] bên admin như này thì các bạn sẽ chỉ cần
[01:31:10] ạ
[01:31:13] ở gần nhà làm lại đống này đã gần nửa
[01:31:14] cái nó khán
[01:31:18] ở bên emminh rồi về với lại bên admin
[01:31:20] thực ra mình cũng không yêu cầu nhiều
[01:31:28] em muốn sữa kích cỡ của ảnh khi viết in
[01:31:31] like thì chị được internal vết kiểu
[01:31:34] Exciter hồi đôi khi là nó còn lưu cách
[01:31:37] xét như là đôi khi ở các bạn sẽ bị
[01:31:41] phải nó bị cách cái các bạn phải xóa
[01:31:43] cách đi mới sửa lỗi nhé á
[01:31:46] Các bạn nhớ mạng có phần có tiện ích của
[01:31:48] mình từ ly cách này các bạn tải về các
[01:31:51] bạn thử Xóa đi biết đâu chạy được
[01:31:54] Em ở chỗ nào Buổi sau của mình thì mình
[01:31:56] sẽ dạy các bạn về bên giao diện với
[01:31:57] khách hàng để hiển thị ra toàn bộ sản
[01:31:59] phẩm xong rồi các thứ nó ngoại phải kết
[01:32:01] hợp với Phương Trang đã tìm kiếm nữa
[01:32:08] 300 đón một thì không có tính năng
[01:32:11] nghiệp tất cả toán một thì về cơ bản nó
[01:32:13] sẽ chỉ có tương đồng như này thôi nó
[01:32:21] Ừ ông kia ở nói cái gì Cái thống kê cơ à
[01:32:23] Thôi tôi sẽ đồ ăn một thì tôi sẽ không
[01:32:26] dậy xong mấy ông mấy cái điều đấy còn
[01:32:27] nếu mấy ông vẫn muốn làm thì tôi vẫn cho
[01:32:30] phép nhưng mà tôi sẽ chỉ dạy toàn bộ như
[01:32:32] cái có bạn những cơ thể ông ạ yên tâm
[01:32:35] còn thêm những cái tính năng cũng có tí
[01:32:37] sức tạp nữa giống như tôi nói phức tạp
[01:32:40] nhất của bên bán hàng so với bên tin tức
[01:32:43] mà chính là cái giỏ hàng không ạ thì thì
[01:32:45] tôi sẽ dạy người không
[01:32:48] ô thưa cải cái một tối đang dạy này thì
[01:32:50] các bạn cũng ôm sang bên A tin tức được
[01:32:51] mà nó nhọn
[01:32:53] à
[01:32:55] Tôi đang dậy mấy cái này thì mấy ông sẽ
[01:32:57] thấy là cho các nhà sản xuất này bạn
[01:33:01] chất nó là tắt Dạ hoặc sản phẩm nó sẽ là
[01:33:02] bài đăng tin tức trở lại đúng không ạ
[01:33:12] 3000 có phân quyền gì cả sự phân quyền
[01:33:14] các bạn chạy thẳng vào trong cốc thôi
[01:33:17] làm chứ ạ Ai ra được gì đó Cái về bài
[01:33:20] toán về ạ quyền hay các thứ đấy thì nó
[01:33:22] liên quan đăng nhập thì mình sẽ hướng
[01:33:24] dẫn các bạn phải đăng nhập nữa ở trung
[01:33:27] hòa những những buổi sắp tới nhé mình sẽ
[01:33:30] dạy về nhất là thí sinh này họ đăng nhập
[01:33:33] này buổi sau đây sẽ là giao diện với
[01:33:37] khách hàng này không ạ nghĩa trang chủ
[01:33:40] này rồi bấm vào xem cụ thể hoặc trang
[01:33:44] chủ này xem cụ thể sản phẩm sản chưa chữ
[01:33:47] làm nhiệm vụ bên giỏ hàng vội mà mình sẽ
[01:33:49] tìm hiểu về season đi qua đăng nhập
[01:33:53] trước đã đăng nhập này đăng ký rồi ra
[01:33:55] đăng ký đơn giản hãy đăng ký nó bạn chất
[01:33:58] nó Insert thôi mà nóng lạnh mình dậy các
[01:34:00] bạn để đăng nhập
[01:34:02] ạ sau đó thì mình sẽ dạy các bạn với
[01:34:05] Cookie để mà kiểu lưu lại khi năng lưu
[01:34:07] lại trạng thái đăng nhập bằng gì đó là
[01:34:09] xinh đăng nhập đúng không ạ
[01:34:12] điều lạ đăng nhập
[01:34:14] sau đó thì mình mới dậy các bạn về giỏ
[01:34:16] hàng
[01:34:18] đúng rồi người ta thường ai dùng
[01:34:21] localstorage hoa cà thậm chí đưa đại
[01:34:23] trong tay giống như hôm trước các bạn
[01:34:25] nói nhưng mà mình dậy các bạn thì ghi
[01:35:06] cô bạn kia vợ làm sao nhiều hướng là như
[01:35:12] số
[01:35:31] Ừ đúng đúng rồi season me mình hôm trước
[01:35:36] mình tự nói đấy đó là đó là season mình
[01:35:38] mình không nói giờ còn lưu giỏ hàng
[01:35:40] trong chất sừng này nó sẽ ra cái cậu nó
[01:35:42] là cậu cái tiện nhất hay các thứ mà mình
[01:35:44] dạy các bạn làm việc lưu lại trong sự
[01:35:46] gìn thấy để các bạn với qua khái niệm về
[01:35:49] màn và biết qua khái niệm chưa dừng thôi
[01:35:52] rồi cay thường là nhiều nhiều nơi bây
[01:35:55] giờ sẽ rượu trông DB nhưng mà nóng sẽ bị
[01:35:59] rát nó sẽ bị rát dp không ạ
[01:36:02] em không có họ không có khóa là của mình
[01:36:05] dạy về api cả Chắc mình sẽ chỉ để mô các
[01:36:08] bạn api những cái buổi lại like cốc thôi
[01:36:10] Bởi vì à
[01:36:15] ở vỉa kiểu đến đến cả bên rare những gì
[01:36:17] dạy các bạn cơ bản chứ không dạy các bạn
[01:36:27] âm thanh tra xuân sang thì hôm trước họp
[01:36:30] rồi nữa không ạ oke này còn gì nữa nhỉ
[01:36:35] họ hàng này nọ hàng ở đây sẽ là là thêm
[01:36:38] sửa thêm thêm sản phẩm xóa xóa gọi hàng
[01:36:41] các thứ thứ sau đó còn Xem giỏ hàng
[01:36:49] cập nhật số lượng này
[01:36:53] Xóa gọi hàng vào Xem giỏ hàng
[01:37:00] ạ sau đó thì các bạn cái cuối cùng là
[01:37:10] đó đó là đầy đủ những cách tính năng cơ
[01:37:13] bản nhất của cái trang web bán hàng Thì
[01:37:17] mình sẽ dạy các bạn để bọn mình sẽ dạy
[01:37:19] các bạn tất cả những cái này con các bạn
[01:37:21] muốn kiểu làm hư cậu là làm thêm tính
[01:37:24] năng nữa thì các bạn hãy hỏi mà mình sẽ
[01:37:26] cân nhắc Nếu mà có nhiều bạn cũng hỏi
[01:37:29] thì mình sẽ để để mua qua thứ hòa mình
[01:37:32] sẽ chị hưởng qua
[01:37:35] khoa học cơ bản thế cho là bạn chưa đọc
[01:37:38] mua tạm rồi này trở khi mình sẽ thấy ghi
[01:37:41] lại phần mô tại sao cái cày danh sách
[01:37:44] này cái cái khóa học cơ bản này chỉ để
[01:37:47] cho các bạn hiểu qua tương đối thể lập
[01:37:51] trình web nó là như nào nó lại nó nó là
[01:37:54] như thế nào thôi làm được rõ thuần như
[01:37:56] thế nào chứ để mà đi đi thực tập 2 để đi
[01:37:59] làm thì có bạn sẽ chưa chưa đủ kiến thức
[01:38:01] cũng như là
[01:38:04] em vừa chưa đủ kiến thức này vừa phải
[01:38:06] họp lại thêm nhiều thứ nữa với thực tế
[01:38:08] nó cũng sẽ phát ra khá nhiều
[01:38:12] À thỉnh cái cái này cần điều thì cho các
[01:38:13] bạn biết thế nào lập trình này mà cũng
[01:38:14] như là
[01:38:17] xem các bạn có phù hợp với ngay nhé
[01:38:18] không thì các bạn làm xong mà các bạn
[01:38:21] thấy dễ quá rồi không đến nỗi như các
[01:38:23] bạn thấy ổn và các bạn xem được thì các
[01:38:26] bạn sẽ nên cần học thêm khóa nâng cao
[01:38:30] sau của mình để mà cũng tra cũng chỉ mất
[01:38:31] ba bốn tháng nữa thôi để mà các bạn với
[01:38:34] hiểu biết thực tế nhất
[01:38:37] đi hát kẹo thực tế nó sẽ cậu cốt như thế
[01:38:39] nào đúng không ạ Mình sẽ dụng Facebook
[01:38:41] như thế nào mô hình rồi là như thế nào
[01:38:43] xử lý bài toán chuyên sâu nói như thế
[01:38:46] nào Vân Vân Vân đó ngoại để các bạn khi
[01:38:49] đi ra với các bạn sẽ đi làm được luôn
[01:38:51] không cần phải cần như ở không cần phải
[01:38:54] mất thời gian thực tập nữa Cái đấy mình
[01:38:57] phải này được vì các bạn thể làm được
[01:38:58] việc luôn
[01:39:05] A và nâng cao về nội trẻ 23 tháng các
[01:39:06] thứ thôi
[01:39:08] nhưng mà
[01:39:11] Ừ nó cũng giống như cái đồ án này sau 23
[01:39:12] tháng các bạn sẽ phải có một cái sẵn
[01:39:16] phẩm đoán là các bạn sẽ cũng áp lực phết
[01:39:20] Nói chung là các bạn theo từ giờ thì mà
[01:39:23] theo đến cuối cứ cho nó 6 tháng nữa
[01:39:25] không ạ Có thể hơn một tí
[01:39:29] cho 7 tháng đi cho giải
[01:39:31] Ừ thì 7 tháng nữa là các bạn sẽ hoàn
[01:39:35] toàn là đi làm được ngon Nếu thực sự các
[01:39:37] bạn theo được từ đầu đến cuối
[01:39:39] ảnh của khóa của mình
[01:39:41] đó là đương nhiên là đền cái khóa nâng
[01:39:44] cao thì như các bạn sẽ vừa học vừa hơi
[01:39:47] bị chặn bật một tí hóa cơ bản này mình
[01:39:50] còn cầm tay chỉ lỗi được yêu kiểu từng
[01:39:51] bước từng bước các bạn cũng sẽ hiểu từng
[01:39:54] bước hành khóa nâng cao thì mình cũng
[01:39:58] cũng thức cũng vẫn sẽ dậy như này nhưng
[01:40:00] mà các bạn sẽ phải tự tìm hiểu cũng cũng
[01:40:04] nhiều đúng hạn vì mình không phải dạy
[01:40:07] hết được vì cái nó nâng cao nó rất nhiều
[01:40:10] cái mình không thể dạy hết được vì chỉ
[01:40:13] dẫn cách bao quát thôi thì
[01:40:15] Ừ đúng rồi đã có thể đi thực tập Vượt
[01:40:17] Lụa đi làm được luôn chứ không phải là
[01:40:20] hai tháng thực tập 2 3 4 hãng được tập
[01:40:22] nữa đúng không ạ Cái đấy mình khẳng định
[01:40:26] được vì vì cái họ nâng cao mình định dậy
[01:40:29] thì nó sẽ là kiểu các bạn sẽ ghi hậu qua
[01:40:32] về cả mày mô hình có thứ
[01:40:35] ở gần như xong khóa nâng cao của mình
[01:40:37] các bạn hệ của chén là các bạn có 1 hoặc
[01:40:40] 2 năm kinh nghiệm vẫn có thể được cái
[01:40:44] đấy thì mình mình nghĩ à Bởi vì bản chất
[01:40:46] và các bạn sau hóa nâng cao thì các bạn
[01:40:48] sẽ phải làm thêm có đồ ăn nữa thì nhanh
[01:40:50] bằng các bạn làm hai cái đồ án rồi thì
[01:40:54] nha bằng 15 thí nghiệm rồi
[01:41:00] e100 nếu mà mình dậy cốt thuật thì mình
[01:41:02] sẽ chỉ để mô qua mình mình thỉnh thoảng
[01:41:04] mình sẽ
[01:41:07] chị sẽ hướng dẫn các bạn về khách khùng
[01:41:09] mà nóng lạnh chỉ các bạn về nghị cần đỗ
[01:41:10] hỏng cái thứ
[01:41:14] có cái in Hôm trước mình gọi để mua các
[01:41:17] bạn về Acquy Arsenal không ạ
[01:41:20] anh vào mấy hôm nữa thì
[01:41:23] mấy hôm nữa Chắc là hôm sau cũng được
[01:41:26] Hôm sau về cái vụ trang chủ của khách
[01:41:29] hàng có tìm kiếm đã gặp phân trang mình
[01:41:31] sẽ dạy các bạn về xs nữa để các bạn hình
[01:41:34] dung thêm về cái vụ nó thì nguy hiểm như
[01:41:37] nào ở trên cái đón một các bạn khi mà
[01:41:39] các bạn cốt thuần cơ mà không kiểm tra
[01:41:41] người dùng nhập thì nó sẽ đầy lỗ hộp
[01:41:44] nhưng về đến đồ án 2 thì cần đưa nó sẽ
[01:41:47] nó là Facebook nó hỗ trợ các bạn vì mình
[01:41:49] cái lỗ hổng rồi các bạn sẽ gần như không
[01:41:51] vừa phải quan tâm đấy nữa có phải chỉ
[01:41:54] quan tâm đến những cái về lôgic thôi
[01:41:55] chi tiết
[01:41:56] Xin
[01:41:58] chào bạn bạn mới biết đến kênh của mình
[01:42:01] hơi muộn thế cơ à mới biết đến kênh của
[01:42:03] mình mà đã xem cái video này rồi là nó
[01:42:07] lại hơi say quá quay lại video đổi tiền
[01:42:08] xem bạn ạ
[01:42:14] khi được dùng computer không
[01:42:15] anh
[01:42:17] đi bạn hả
[01:42:20] Ý bạn là scf được nhưng không dây bạn
[01:42:23] kia hỏi hay là như này thật ra các bạn
[01:42:26] vẫn được dùng có bao giờ cái thứ
[01:42:28] cái đấy nó là trình biên dịch cho họ
[01:42:34] từ nãy giờ đầy đủ kiến thức mình dậy rồi
[01:42:36] nha Bây giờ mình đang chờ được câu hỏi
[01:42:38] thôi đúng ạ Hôm nay thì mình Khâm định
[01:42:41] chia sẻ thêm cái gì sợ hơi quá tải các
[01:42:43] bạn ấy thì mình hứa buổi sau vậy nhá
[01:42:45] buổi sau mình sẽ chia sẻ có thời gian
[01:42:48] thêm mình sẽ chia sẻ một tí hay khủng
[01:42:51] nếu như bạn kia bảo nó không ạ xss lại
[01:42:54] avantech sinh con Nếu mà có thêm thời
[01:42:55] gian nữa thì mình sẽ tranh thủ chữa bài
[01:43:00] câu ashwell hôm trước nữa nợ hơi lâu rồi
[01:43:03] thì các bạn còn hỏi gì không ạ
[01:43:07] à à con boss của của pp này thì thoải
[01:43:08] mái thôi
[01:43:10] thì các bạn sẽ trải Lên thư viện Hãy
[01:43:13] dùng có boso để máy chạy cốt được không
[01:43:21] anh có xem được không Ý bạn là sao nhỉ
[01:43:24] Thế các bạn thì à
[01:43:28] cách dùng dùng nốt hết dùng cái ngôn ngữ
[01:43:31] Bắc em thì cần đưa nó sẽ bị mã hóa kiểu
[01:43:38] cô bạn kia hỏi mình hỏi đây
[01:43:42] ngồi nhiều thì mình thì ngồi mình cũng
[01:43:45] thấy biển đệm nữa bởi vì mình gây Nếu
[01:43:46] mình ngồi không thì con nhận cũng bị đau
[01:43:53] Ừ đúng rồi bây giờ cũng có nhiều ai ai
[01:43:57] được các bạn lên gõ lên gõ cậu gọi mô tả
[01:44:01] đấy nó sẽ sinh ra được cả trang web hoặc
[01:44:07] à vẽ vẽ bừa gì đó nó sinh ra được trang
[01:44:08] web
[01:44:17] khi xem màn đấy vẫn chỉ ở giao diện thôi
[01:44:25] Ừ Ok bạn chỗ mà bây giờ cũng muộn rồi
[01:44:28] khi cha đẻ có gì các bạn thắc mắc thì cứ
[01:44:31] bình luận sau nhé mình sẽ trả lời sau
[01:44:39] thế Element node.js thì có xem được khóa
[01:44:44] này không Ừ thế cũng được Nhưng mà như
[01:44:46] hôm trước tôi nói cả Mệt mấy ông nữa mon
[01:44:49] nộp đoán cho tôi không không đi nộp bằng
[01:44:51] ngôn ngữ khác thì tôi dậy là thì chắc
[01:45:01] à À còn con ông làm bằng ngôn ngữ lập
[01:45:03] trình nào ông xem khóa của tôi thì cũng
[01:45:05] biết thêm được thêm kiến thức mới mà
[01:45:07] không thưa đâu nóng lạnh
