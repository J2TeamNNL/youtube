# Lập trình web chuyên sâu - 3 - MVC - CRUD 2 bảng

- Video ID: `3V5iGyUyfxA`
- URL: https://www.youtube.com/watch?v=3V5iGyUyfxA
- Published: 2022-03-13
- Duration: 1h 38m 42s (5922s)
- Language: vi
- Subtitle source: auto
- Kind: live

## Transcript

[00:00:07] à à
[00:00:19] ờ ờ
[00:00:32] Hôm nay thật là thì tùy có vẻ là Nghe có
[00:00:37] vẻ là
[00:00:40] Anh nhìn
[00:00:42] nhầm
[00:00:43] crd2 bảng thì nó sẽ giữa phức tạp nhưng
[00:00:46] mà tí tối cốt thì mình sẽ thời gian
[00:00:49] nhanh bởi vì làm xong một hàng thì copy
[00:00:52] xong rồi copy paste sang hàng còn lại sẽ
[00:00:54] rất là nhanh nên là bây giờ tôi nghĩa
[00:00:57] vẫn có kịp thời gian để mà tâm sự một tí
[00:01:01] Cho tôi xin phép bà
[00:01:03] em tâm sự một tí đã được ạ
[00:01:07] Và bây giờ cũng đang có mỗi vài ông ấy
[00:01:10] thì
[00:01:11] ở đầu tiên thì hôm trước tôi còn nói
[00:01:15] chuyện về
[00:01:16] gửi đứa bạn thì bạn đang bảo là nó đang
[00:01:20] mông như cho đùa kiểu hiện tại của nó
[00:01:23] hoặc kiểu dạng mà nó đang không có gì
[00:01:26] trong tay ta và đang đi làm thêm để đỡ
[00:01:29] lao động chân tay từ bồi bàn cứ thứ cũng
[00:01:32] không theo đúng ngành này nó nó là ngành
[00:01:34] công nghệ thông tin chúng tôi nhưng mà
[00:01:36] nó học đại học mà xong rồi nó không
[00:01:39] không không làm được đấy nó không theo
[00:01:42] được đấy bởi vì không phải không theo
[00:01:44] được ở trên giường mà chỉ đơn giản là
[00:01:46] Họp xong học xong đi làm học trên trường
[00:01:49] nó bị lý thuyết quá cơ bản quá đi hoàn
[00:01:52] trả dụng được gì cả Thì giờ nó vẫn kéo
[00:01:55] không làm theo đúng này nào chưa tìm
[00:01:58] được việc vân vân thì
[00:02:00] Vì thế nên là ông đấy cũng cũng gọi là
[00:02:05] nhà cũng đánh giá mình kiểu hơi tự tin
[00:02:07] một tí Thế ông ấy không dám tán gái kiểu
[00:02:12] thế không làm bạn gái rồi bạn nghĩ rằng
[00:02:15] cầu mình đang Chả có gì trong tay mình
[00:02:18] đang phân vân không tự tin mà tệ nào khá
[00:02:22] tự ti thì
[00:02:25] Ừ thôi có nói không Đấy Đó là cái gì
[00:02:30] nhất là ông người có tôi cảm thấy ông
[00:02:32] người còn năng lực chẳng qua ông ấy có
[00:02:33] thể đạt đã chuẩn bị đi sang hướng chứ
[00:02:36] không có nghĩa là ông đấy không tương
[00:02:38] lai mày sẽ kiểu mịt mù hay gì cả mà ông
[00:02:42] phải tự tin mà bạn thân lên bởi vì tôi
[00:02:44] đã từng như thế và tôi nghĩ ai từng như
[00:02:47] thế nó kiểu cảm thấy tương lai mông lung
[00:02:50] cho cậu
[00:02:52] mất niềm tin cảm thấy chẳng có tin nào
[00:02:55] mà cái gì cả
[00:02:56] Ừ nhưng mà tôi khác mấy bạn đấy à Nó về
[00:03:01] đúng nghĩa là tôi không có một cái gì cả
[00:03:03] thật từ bạn bè không có gia đình
[00:03:06] cũng chán nản sau đó thì chưa đọc hàng
[00:03:10] như cũng kiểu
[00:03:11] cũng kêu bình thường đấy
[00:03:14] Ừ lúc đấy tôi chỉ có thư duy nhất là cái
[00:03:18] niềm tin thôi không có niềm tin được xa
[00:03:20] tôi cảm thấy tôi đã từng nghĩ à Ai chẳng
[00:03:24] từng nghĩ việc à từ xa mà từ từ các thứ
[00:03:27] thứ
[00:03:28] Ừ nhưng mà tôi không
[00:03:31] không không chọn con được đấy rất là nội
[00:03:33] mới chỉ có niềm tin là tao cứ nghĩ là
[00:03:36] mọi thứ sẽ ổn thôi cứ cố làm cổ tin là
[00:03:40] một cái điều gì đó Cái ngành này thì
[00:03:42] thực sự đến năm đầu các bạn làm được
[00:03:45] việc rồi các bạn vẫn mông lung Nhưng mà
[00:03:46] trò đùa vậy các bạn cảm thấy à Chưa đi
[00:03:49] làm được 2 vạn vật
[00:03:52] Hà Nội dung cái niềm tin ở trong cuộc
[00:03:54] sống tôi thấy một thứ rất quan trọng mà
[00:03:57] cái tương lai một sự không ai thể cho
[00:03:59] thắng được kể cả ông
[00:04:03] Ừ ông xã đâu có là nhắn tin chia nữa
[00:04:05] chưa chắc à đoán được tương lai thực sự
[00:04:07] của ông
[00:04:08] Ừ mình chính là mình làm chủ Tương Mai
[00:04:11] không tin nội bộ toàn không tin bất kỳ
[00:04:13] ai nói gì cả tự mình quyết định tương
[00:04:15] lai mình số phận mình là do mình quyết
[00:04:17] định đấy tôi có những quan điểm rất dứt
[00:04:20] khoát vì những vấn đề đấy mà niềm tin nó
[00:04:22] sẽ khiến cho tôi củng cố những cái hành
[00:04:24] động thôi
[00:04:30] từng đi vào toán đi cậu xem bói cho tứ
[00:04:32] với nghỉ xong rồi xem tử vi xem quyển
[00:04:36] sách cái gì đó tôi không bật tin là mấy
[00:04:39] cái điều đấy
[00:04:40] kiểu tự nhiên nó còn nói tốt với mình cả
[00:04:44] tương lai mình giàu em ạ những nhưng mà
[00:04:46] tôi không có tôi không tin được à bói
[00:04:50] toán bói tương lai tới dầu với tôi sẽ
[00:04:52] chỉ ngồi chơi thôi đợi đúng phát tôi
[00:04:54] giàu à không nó ngon nữa tôi sẽ
[00:04:57] để xem niềm tin mình làm thôi Ừ vội toàn
[00:05:00] nói tốt với mình ở mình cũng cảm thấy nó
[00:05:02] vui có thể nó sẽ thành sự thật
[00:05:05] ô chữ bài toán về bảo là
[00:05:09] năm sau anh sẽ kiểu mất chẳnghạn hai cái
[00:05:12] gì đó gồm nhiều ý nghĩa của lời tiên tri
[00:05:14] ấy đúng không Thì thì ông sẽ sống nha
[00:05:18] ông sẽ sống tốt lên không sẽ sống tệ hơn
[00:05:21] mà bạn cả đến đúng ngày khi ông không
[00:05:23] bớt thì như thế nào ngon thì thôi ạ này
[00:05:26] Tôi chẳng bao giờ ở trả vờ tin vào một
[00:05:30] cái gì đâu tuyệt đối về Em về mấy cái mà
[00:05:33] người khác đã nói về tương lai mình nghe
[00:05:34] mà tự tương lai do mình quy định duyên
[00:05:37] số hay mọi thứ do mình có những hết
[00:05:46] mày mấy cái
[00:05:47] các truyền thuyết về con người còn đánh
[00:05:49] bại thần
[00:05:51] Ừ cái đấy nhưng mà thôi Nó hơi là màn
[00:05:53] quá đại khá là tôi có niềm tin mãnh liệt
[00:05:56] vào mấy cái kiểu mình làm chủ số phận
[00:05:58] mình cái kiểu thế
[00:06:01] a tiếp theo có cái video này thì nhờ tôi
[00:06:04] vừa mới lưu Đại Hiệp
[00:06:06] Ừ ừ
[00:06:11] được đâu biết tại sao tôi muốn
[00:06:20] Xong rồi đây nữa không cho tôm vừa mua
[00:06:23] chả sao hiện quảng cáo trên Facebook ảo
[00:06:25] vãi đấy nhưng mà cái vấn đề không muốn
[00:06:26] nói các bạn Chuyện gì có hai mặt bố
[00:06:28] trong những cái mà hay của IOS mới đó là
[00:06:31] nó chắc khiến cho ứng dụng Facebook
[00:06:33] không theo dõi được đứng và phân phối
[00:06:34] quảng cáo để cho chúng ta đây chúng ta
[00:06:36] cứ nói là mỗi khi ta nói chuyện gì để
[00:06:37] Facebook biết nó quảng cáo ngay hiểu như
[00:06:39] là tôi đã nói về việc làm Tôi muốn học
[00:06:42] chứng chỉ thêm về tiếng Pháp được ông
[00:06:45] Dương tự nhiên Facebook tôi hiện quảng
[00:06:46] cáo massage nuru Chả hiểu sao lại hôm
[00:06:49] nay tôi đang bảo là con nó muốn học thêm
[00:06:51] mà đánh golf shopee quảng cáo bán với
[00:06:53] cái đầu nó không nữa tôi chả hiểu gì cả
[00:06:54] nhưng bà đây cũng là thứ mà tôi nghĩ
[00:06:57] rằng là bây giờ rất nhiều người sẽ gặp
[00:06:59] và tương tự do với tôi thật đó là khi nó
[00:07:02] ra chặn Facebook Lấy thông tin không
[00:07:05] phải là nó ở phân phối quảng cáo đi
[00:07:07] chúng ta mình nó đang quảng cáo Quá
[00:07:09] nhiều thứ vẫn phải ta sẽ cùng nhau đi
[00:07:10] xem người ta vòng có gì thế không
[00:07:13] nhã tôi cho mấy hôm nay một đoạn thôi
[00:07:15] Thì đại khái thì anh anh ấy hiểu qua
[00:07:20] công nghệ cho tôi anh không Anh em biết
[00:07:21] về công nghệ Nhưng mà không phải là dân
[00:07:23] công nghệ thông tin như bọn mình thật sự
[00:07:25] thì cái vừa rồi thì bây giờ thằng is và
[00:07:30] hình như là có vài hôm nữa rồi 3 ngăn
[00:07:32] chặn việc là các ứng dụng thu thập thông
[00:07:35] tin của người dùng thì cái đấy à là ngọn
[00:07:38] na ná giống như kiểu mày không tra
[00:07:40] Google nó sẽ đề xuất ví dụ Giả sử về tôi
[00:07:43] trả thời tiết Nga chặn lại
[00:07:45] Bởi vì nó xác định là tôi đang ở Hà Nội
[00:07:48] không chứ Ở đây đang ở chỗ khu vực này
[00:07:52] này nó sẽ đề xuất tới giờ chuẩn Còn nếu
[00:07:54] mà ông xã xử ông cha bằng bác bác gấu
[00:07:57] này thì ạ Ừ thì thấy cái này nó sẽ là
[00:08:01] kiểu riêng tư hơn ơi
[00:08:11] thể chính xác
[00:08:12] kiểu dạng là ông đang ở đâu Vân Vân Để
[00:08:16] như vừa rồi các trang tiếng Việt đến nó
[00:08:17] sẽ gợi ý Kiểu tiếng Việt có thứ cái cái
[00:08:21] vừa rồi một phần là do thằng này nó còn
[00:08:23] nhận diện mà nó thu cho nó giận nhận
[00:08:27] diện location như hài sẽ thả nó phải
[00:08:29] công nhận diện location Lego nó công cụ
[00:08:32] tìm kiếm trở lại không thu thập thông
[00:08:33] tin này dùng thì thì đấy nghĩ em bé uống
[00:08:36] sẽ thấy là có những lúc mà thu thập
[00:08:38] thông tin người dùng có lợi để bụng với
[00:08:41] mục đích là để mà hỗ trợ cho mình mà
[00:08:43] đúng ạ đứng yên là nó hơi bị sai thời
[00:08:47] điểm mà nó thu thập rồi nó bán Thằng thứ
[00:08:49] ba thở ra là không hẳn hay lắm Nhưng mà
[00:08:51] nếu mà nó thu thập và nó để mà em hỗ trợ
[00:08:56] cho mình thì còn hơn cái việc mà không
[00:08:58] thu thập bởi vì à như anh Vinh anh vừa
[00:09:02] nói đó là chắc chắn là nó vẫn sẽ quảng
[00:09:05] cáo cho mấy ông thôi chả con nó sẽ để nó
[00:09:08] sẽ quảng cáo những cái mà trong tầm tuổi
[00:09:10] của ông hỏi cả trong khu vực Hạnh quanh
[00:09:12] ông thì sẽ cái gì mà vân nên nó sẽ rất
[00:09:15] là nhà nên mụn Nếu mấy ông muốn xem cầu
[00:09:19] dạng mà đến tầm tuổi của mấy ông đã bị
[00:09:22] ông còn khai ông Dân công nghệ thông tin
[00:09:24] này nó sẽ đề xuất quảng cáo với bệnh
[00:09:27] viện chị ạ
[00:09:34] Đấy hạn chế bờ sầu này mất lần nữa thì
[00:09:41] mới mấy ông có thích điều đấy không hay
[00:09:43] thì thằng bạn đâu mà kiểu tự nhiên nhìn
[00:09:46] thấy quảng cáo đấy trên Facebook nói anh
[00:09:48] nghĩ ông bị bệnh nói thật
[00:09:50] đấy nó còn tệ hơn ngoạn tha nó quảng cáo
[00:09:54] gì đó nó Ừ đúng những thứ Ông tìm kiếm
[00:09:57] trừ khi mấy ông Tìm kiếm Cũng bài thứ
[00:10:00] tương tự thế rồi không nói ờ
[00:10:04] không Hôm nay phải qua được
[00:10:07] làm với 2 bảng đã rồi buổi sau mình sẽ
[00:10:10] dạy các bạn sang bên OB sau mình mình
[00:10:14] cắt buổi của mình sẽ gần như là sử dụng
[00:10:17] cốt hôm trước thỉnh thoảng sẽ đập đi làm
[00:10:20] lại thôi nhưng thường là sử dụng có hôm
[00:10:22] trước và sửa lại để mà sao cho các bạn
[00:10:25] thấy là nó sẽ thay thay đổi lần nghĩa
[00:10:28] buổi hôm trước học ví dụ là học một cộng
[00:10:30] một bằng hai bạn hôm nay sẽ thay dấu
[00:10:33] cộng này thấp nhân ở ngọn thì sẽ ra kết
[00:10:34] quả như thế nào Cái kiểu như thế đấy thì
[00:10:37] ah không Ví dụ thì hơi sai ví dụ tôi Chị
[00:10:41] chuẩn rồi à
[00:10:43] vì một cộng một bằng hai thì bây giờ
[00:10:45] biến thành 1 x2 = mấy nặng hơn chỉ Kết
[00:10:48] quả nó phải Tân Nương nghĩa là cái phần
[00:10:50] hiển thị được ăn nó tương đương thôi
[00:10:51] nhưng cái cốt của mình cái tổ chức cốt
[00:10:53] mình nó sẽ khác đấy
[00:10:56] a
[00:10:57] tiếp theo Thực ra tôi tâm sự nốt cái này
[00:11:00] cho dù nó chả liên quan đến từ dân công
[00:11:02] nghệ discard nhưng mà tôi
[00:11:06] cho tôi bảo tôi tôi sẽ hướng đến 500m Mà
[00:11:10] nè tôi Đôi khi tôi sẽ tâm sự với góc
[00:11:12] nhìn của tôi một tí à
[00:11:14] À mà thôi Tôi nghĩa chủ đề này đến cuối
[00:11:17] buổi nói đi tôi sẽ nói về một cái mà thử
[00:11:20] Tôi vừa xem
[00:11:21] Ừ thứ nhất là mấy hộ mấy ông Hôm trước
[00:11:24] có mà thường xuyên mấy ông hỏi thôi việc
[00:11:26] cho tôi học tiếng Anh như thế nào kết
[00:11:28] hợp việc làm học tiếng Anh thì cho tôi
[00:11:31] từng nói đó là nếu không phải đắm chìm
[00:11:34] vào tim anh hơi cạo rồi Nếu mà xem xem
[00:11:37] phim nghe nhạc và Vân những hồi đấy là
[00:11:40] tôi làm mấy cái đấy thì đúng là tôi nghe
[00:11:42] nghe nhạc đã xem phim không cần phụ đề
[00:11:45] nhưng mà về phát âm cũng như là
[00:11:50] ở chung nhà về viết này phát âm này Đọc
[00:11:54] mình thỏa còn tệ này bởi vì Xem phim mà
[00:11:58] và tạm biệt là mấy ông không phải lôi
[00:12:00] với mỗi đúng kiến thức đấy để mà đi thi
[00:12:02] ở trường hay là thi Ielts được thì hồi
[00:12:07] cấp 3 tôi Đặc biệt cô giáo tiếng Anh tôi
[00:12:10] thể hiện rõ đậu vùi dập tôi luôn nó kiểu
[00:12:13] dạng kiếm mày không được thêm của dao
[00:12:15] đúng đúng nghĩa Tôi chẳng biết kể mấy
[00:12:18] ông chưa đó là rồi nha cô Xin
[00:12:22] mời bạn lên kiểm tra miệng à
[00:12:26] ở bãi sao đời xa hai câu cô cho Tám Rồi
[00:12:29] đi xuống tôi sao rồi Kiểu cuộc gọi tôi
[00:12:32] lên rồi còn tự tin rồi mấy cái này dễ mà
[00:12:35] Đấy xong rồi nó trả lời đúng hết sạch
[00:12:39] bài thứ nhất và ơi sai khá rồi cậu Cô
[00:12:42] bảo là mày thứ 2 vẫn làm đúng hết Xong
[00:12:47] rồi cô vào làm thế mày thứ ba làm bài
[00:12:50] thứ ba xong sai đúng một câu cô bạn ngồi
[00:12:53] tưởng thế nào rồi cho bảy điểm đi xuống
[00:12:56] đúng khi họ luôn 2 cả lớp cá ạ Có thể rõ
[00:12:59] là có thể hiện rõ động giặt Hàng ngày
[00:13:01] tôi không hiểu là bài thứ Ba ở tôi đúng
[00:13:03] hết thì cô bác làm bài đến mày mà nhiều
[00:13:06] bởi cái sai rồi đấy thì nói chưa cô các
[00:13:12] bà tôi đúng thể hiện như thế luôn mà tôi
[00:13:15] khẳng định ở tiếng Anh cô các bà ấy có
[00:13:17] khi là kém hơn cả rồi vì vẫn nhớ cái hồi
[00:13:19] mà vui có hành quyển sách quyển sách học
[00:13:22] tiếng Anh cơ bản ở trên bàn Cô và cô đọc
[00:13:24] cái đấy Thật chứ không phải mẹ con cô
[00:13:26] được nhá
[00:13:28] cục phát âm tiếng Anh bật cười em nhưng
[00:13:30] mà tại Thái Cô ấy làm tôi chán tiếng Anh
[00:13:34] từ thời cấp 3 và khiến tôi kiểu học
[00:13:36] tiếng Anh tệ hơn thì hồi đời tôi có có
[00:13:40] một chị gia sư Chị ấy cũng tốt phết mà
[00:13:43] chị xinh nữa
[00:13:45] để mà xinh vợ chị nhà có tuổi nó vẫn
[00:13:49] thích à Thì
[00:13:51] anh chị đấy là động lực to lớn của tôi
[00:13:54] để học tiếng Anh
[00:13:55] sức khỏe mới sinh em nhé bởi vì cậu chị
[00:13:59] lấy cậu truyền được cảm hứng cho tôi
[00:14:01] cũng như là
[00:14:03] dạy rất hay nói chỗ nào về cơ bản ở
[00:14:07] truyền được cảm hứng thôi chứ tôi khả
[00:14:08] năng tự học tôi vẫn đùa tốt và
[00:14:12] ở những chỗ mà chị đấy cũng là kiểu ở
[00:14:15] truyền truyền hổ chương dạy ở lò đào tạo
[00:14:19] IELTS luôn còn bây giờ Chị tự mở lớp
[00:14:21] riêng tôi để Linh ở đây để Bởi vì tôi à
[00:14:25] Ý tôi là trò một trận Trả chó đó thứ hai
[00:14:29] của chị ấy và cũng bị lâu lắm rồi từ hồi
[00:14:33] cấp 3 bây giờ chờ lâu lắm rồi nhỉ
[00:14:36] Ông Ngoại trưởng hồi cấp 3 mình là 10 10
[00:14:40] 15 hả Bây giờ 16 bây giờ
[00:14:43] 25 tuổi mỗi lần 10 năm rồi đấy ạ
[00:14:47] khi nghe tôi vẫn sẽ để lên ở đây quảng
[00:14:50] cáo cho bé ông Thế mở lớp ở Hà Nội nhá
[00:14:54] và Tí nữa chị thấy sinh bị và có tuổi
[00:14:59] Nếu mà Cái quan trọng là lớp chị thằng
[00:15:02] con gái xinh không ạ Tải vậy chứ Tìm đứa
[00:15:06] đó toàn cái xinh
[00:15:07] đi học còn động lực à
[00:15:11] à à
[00:15:14] anh dương vật này tô quảng cáo hơi lộ
[00:15:17] liễu một tí
[00:15:18] Ừ nhưng mà tôi quảng cáo trong bếp ông
[00:15:21] thường mà những cái ấy mà tôi chính nhất
[00:15:22] Sẵn đem lại cho tôi cái gì chỉ đơn giản
[00:15:26] là tôi cảm thấy nó nó tốt thật thì thôi
[00:15:28] quảng cáo cho bé uống thôi
[00:15:35] ông lướt qua xem nhanh nhỉ
[00:15:48] à hài chửi cho xem trên điện thoại
[00:15:51] Ừ đợi tí nhé Vì vậy tôi xem cái này trên
[00:15:54] à
[00:16:01] Ừ biết rồi
[00:16:03] nói chỗ nào hay video này thì Tóm tắt
[00:16:06] lại vậy Hay video này đề xuất hai cái
[00:16:09] mẹo khá 21 mẹ và một mẹo là Kiều thứ
[00:16:14] ngày tháng ở trong Excel có để hiển thị
[00:16:17] là Thành A không một ngày cụ thể trong
[00:16:20] mới xem Nó kiểu như này
[00:16:22] anh à Mấy thôi không ấy Seo tôm cái Xem
[00:16:25] sheet.new này nó sửa cụ thể một ngày
[00:16:29] tháng gì đó
[00:16:30] thật sự không một này à
[00:16:33] anh không
[00:16:35] 1978 ạ Như này sau đó thì nó sẽ bằng một
[00:16:40] cái gì đó này ra cái thứ là sử dụng là
[00:16:43] bằng cách này
[00:16:45] ở nhà trọ ngắn
[00:16:47] ở
[00:16:54] sao rồi có cách ở trong mẹ này nữa nó sẽ
[00:16:58] biến ảnh được từ tiếng Việt cơ thì thì
[00:17:01] để mẹo Tôi thấy video để được mấy chục
[00:17:04] nghìn lượt thích sau một nhẹ thứ hai nữa
[00:17:07] là kiểu thay vì một có bảng vàng dọc như
[00:17:10] này rồi các bạn ông Ấn xăm bằng xăm của
[00:17:12] mình cái thằng trên thu hồi ở đoạn cuối
[00:17:15] này vẫn ở xa mà em trên thì bạn ấy có
[00:17:17] xinh phát kiểu an tp có nhớ để cậu nhiên
[00:17:21] như thế nào đấy nhở đấy tôi thấy à kìa
[00:17:23] khi tôi thấy à Mấy mẹo kiểu như thế rất
[00:17:26] nhiều người ủng hộ hai sáng các thử thử
[00:17:28] thấy giờ hai xong rồi còn theo dõi thêm
[00:17:31] mấy kênh đấy để mà học được thêm nhiều
[00:17:34] cái thấy cái nửa hai nửa tệ Tại sao phải
[00:17:40] tệ cái này tôi nói thẳng luôn đó là bây
[00:17:43] giờ có rất nhiều thầy đang dạy sao hai
[00:17:46] người đang di chuyển đấy Sao có được mức
[00:17:49] tại ở điểm và Mấy người đang làm cho mấy
[00:17:52] người kia thụ động trong việc học
[00:17:56] khi mua bia à anh Bởi vì có những cái mẹ
[00:18:00] như thế thì mình nên hướng dẫn ra cách
[00:18:03] tra gồm như tôi hướng dẫn mấy ông cách
[00:18:04] tra Google để mở tìm kiếm một cái gì anh
[00:18:06] anh nói thẳng là mấy cái mẹo này trao
[00:18:08] gồm 1 phát ra ngay Thay vì phải lục lại
[00:18:10] video mấy ông để xem cũng như phải cố
[00:18:13] nhớ xem nói cái gì không vậy không Mình
[00:18:16] không bao giờ cần phải nhớ cái phím tắt
[00:18:18] mà cái gì cả hãy nhớ cái mẹo vặt nào như
[00:18:22] thế này không
[00:18:23] à Thế bây giờ Bây giờ mình không không
[00:18:26] biết được cái mẹo đấy làm như nào rồi
[00:18:29] kết hợp với việc là
[00:18:31] nghỉ kia chưa đăng ấy video ở thôi Mình
[00:18:33] chịu à
[00:18:34] à à
[00:18:36] Ừ cái đấy tôi thấy tốt ở điểm là có
[00:18:39] truyền cảm hứng là do mấy ông thích về
[00:18:41] Excel có thể làm được những gì nó rất là
[00:18:43] tốt nhưng cái nhược điểm ở đây đó là
[00:18:46] việc mấy ông bị thụ động quá về cố Hãy
[00:18:48] xem tất cả những cái video đấy để mình
[00:18:50] biết là hết mẹo thế rất là sai bổ vì
[00:18:53] toàn bộ những cái mà mình có thể làm thì
[00:18:56] tra Google là ra à
[00:18:59] Ừ
[00:19:00] ông kia đang hỏi là phải biết có nó mà
[00:19:03] tra thì nếu không có cha thì xem coi
[00:19:05] không được mà ứng dụng nhưng mà nên
[00:19:07] trang bằng tiếng Anh hỏi ra tiếng Việt
[00:19:08] ví dụ giả sử như em trường hợp này nhá
[00:19:10] đầu tiên thì biến biến biến này Thành
[00:19:14] đây thì đấy sẽ là thường sẽ biến thì sẽ
[00:19:19] Converse này
[00:19:20] để biết
[00:19:22] tootec đấy nó đề xuất luôn này tách hoa
[00:19:27] cà which they were named này
[00:19:31] nó xảy ra này đúng không mà Mấy ông muốn
[00:19:34] sang vừa nãy ông kêu còn bảo là có thể
[00:19:37] biến sang tiếng Việt thì mình có sẽ là
[00:19:39] language như này
[00:19:47] pha ra luôn
[00:19:49] Ừ Để xong mẹ không có về à
[00:19:52] cho tôi sẽ dạy mấy ông cách tra Google
[00:19:54] chứ không phải là
[00:19:57] nhớ cắt từ khóa để mà bấm xong rồi phải
[00:20:00] nhớ cả cụ mày bấm không không cậu sẽ chỉ
[00:20:03] hướng dẫn mình cái tra thôi ví dụ điển
[00:20:06] hình giống như bạn vừa nãy bảo cách để
[00:20:08] mà để mà xăm đây xăm thấy bố mày treo
[00:20:12] bạn như này
[00:20:15] Đấy sau đó thì lấy kéo xuống này nó có
[00:20:19] cái phím tắt nó sẽ có cái phím tắt là
[00:20:22] cắm t là sẽ ăn luôn cả bảng này xong Tại
[00:20:26] sao chúng ta phải cũng ở những cái từ
[00:20:27] khóa và cố đậu những cái video người ta
[00:20:30] dậy
[00:20:31] Ừ
[00:20:32] đúng rồi
[00:20:34] Chị chuẩn là sẽ dạy mấy ông người cắt
[00:20:37] key word thì mày không chào Google chứ
[00:20:39] không phải là dạy cho mấy ông mấy kiến
[00:20:42] mẹo như thế này thì đúng là mấy mẹ mày
[00:20:44] rất là hai mấy ông có thể không biết ok
[00:20:47] nhưng mà có nhiều nhưng mà ý tôi ý Nó là
[00:20:51] kiểu mấy ông sẽ bị Nếu mà nhiều bạn đấy
[00:20:54] nó sẽ bị thụ động thụ động việc học chủ
[00:20:56] động việc đội có video mới ra để biết
[00:20:59] được thêm cái Mẹo gì đó mà cố phải tìm
[00:21:02] lại thì đi nào đấy để biết được cách làm
[00:21:05] chứ không biết trao gồ mấy ông sẽ cố tìm
[00:21:08] lại video này thì mà làm các bạn với mấy
[00:21:10] ông chẳng biết được lấy đâu
[00:21:13] à à
[00:21:16] cho nên là
[00:21:18] A và đấy mình mang tiếng mình dân công
[00:21:21] nghệ nhưng mình biết cách trao gỗ để
[00:21:23] mạnh làm được mấy cái tin học như thế
[00:21:25] này mình nghĩ mình sao Mình kế toán được
[00:21:35] chủ động tìm kiếm và mình nên chủ động
[00:21:37] cậu nói chung là nếu thấy mình sẽ biết
[00:21:40] được có rất nhiều thứ làm được nữa chứ
[00:21:42] không phải mỗi mấy mẹ nữa đúng không ạ
[00:21:54] mấy ông có thể hỏi người khác key Word
[00:21:57] để tránh cái học lập trình nhỏ như thế
[00:21:59] sẽ không có tỷ Hà mà Mấy ông không phải
[00:22:01] biết nó phải tra trước mình không phải
[00:22:04] đội một ai đó hướng dẫn kiểu Đề xuất cho
[00:22:06] một cái hàm gì đó
[00:22:08] à à
[00:22:10] Ừ nếu hiểu gì tôi không ạ
[00:22:15] bạn kia đang nói là
[00:22:17] ở
[00:22:18] Clickbuy hơi kỳ đáng lẽ phải trẻ tăng
[00:22:22] Trần và mấy hết đúng không phân sinamay
[00:22:25] hết chỉ là cái mà mình sẽ dạy vào Open
[00:22:28] này mình sẽ dạy các bạn về cái đấy thôi
[00:22:31] ok con buổi hôm nay bạn chắc là vẫn sẽ
[00:22:34] in groups
[00:22:36] Ừ đúng rồi mày cái video đấy giáo dục
[00:22:39] thì mấy đâu nó nó có cái tốt ở điểm là
[00:22:42] nó làm cho mình cảm thấy kích thích về
[00:22:45] việc ở Excel của Excel cảm thấy hấp dẫn
[00:22:47] này có đam mê thêm ấy sao thì được
[00:22:50] nhưng mà đấy thì được cái ở bên có nhớ
[00:22:53] được đâu Mấy ông có nhớ được là người ta
[00:22:57] làm đã làm những cái gì ra cái điều đấy
[00:22:59] đâu ông ạ sợ mấy ông chạy video không
[00:23:03] không như thế Ok nhờ Thôi bây giờ xong
[00:23:06] rồi buổi hôm nay bắt đầu nhá á
[00:23:08] ờ ờ
[00:23:10] cho tôi một tí ý
[00:23:14] ừ ừ
[00:23:17] cô
[00:23:24] Linh
[00:23:26] Linh thôi nghỉ à
[00:23:36] à à
[00:23:43] bạn lớp trưởng tạo cho anh cái link mít
[00:23:46] tiếp nhé rồi tôi sẽ chia sẻ cho mày
[00:23:48] không phải Linh ở đây
[00:23:50] ở mỗi buổi lại phải gửi Linh cũng hơi
[00:23:53] mệt à
[00:24:03] ông cúi không ở nhà mất tích đâu đấy ạ
[00:24:12] người anh không dậy Cái đấy được
[00:24:22] có thể vào xem à paste ôm cùng với tôi
[00:24:25] đúng không và một Linh thì mấy ông có
[00:24:27] thể vào link bạn kia để bạn ấy tự chia
[00:24:29] sẻ cho biết không với hôm nay mình sẽ
[00:24:31] dạy cho các bạn sẽ theo như thế này ví
[00:24:35] dụ hôm trước mình sẽ vào thì nó sẽ là
[00:24:37] cậu em lên cao nhé
[00:24:43] như thế này không ạ nhưng thực ra là
[00:24:45] thực ra là mình Bây giờ mình sẽ muốn làm
[00:24:48] theo cổ là hiển thị ra à
[00:24:51] cho các sinh viên và cả lớp bây giờ mình
[00:24:55] sẽ có thêm cả lớp nữa
[00:24:56] A và mình nhập vào nhập vào à
[00:25:06] lớp theo kiểu có mã lớp thôi là được rồi
[00:25:09] Anh chưa chơi cần làm phức tạp hội tôi
[00:25:11] tôi sẽ nâng cao tuần sau
[00:25:13] cho mấy ông
[00:25:15] em đổi tỉ lệ V chị sẽ có là gì
[00:25:23] you school Witch
[00:25:42] I
[00:25:43] read the table lớp này
[00:25:46] mã in a
[00:25:59] tôi tạm bỏ qua mấy cái giường đà sau 72
[00:26:03] giờ vẫn đúng rồi ô tô phiên mình vẫn
[00:26:06] đăng ký thật
[00:26:08] tôi tạm bỏ qua khóa ngoại tao thử nhé
[00:26:10] chị sau nhé ê
[00:26:23] nữa đi 1 cột 1 cột mà lớp đi à
[00:26:33] à
[00:26:38] làm việc tí nó Đôi khi mình sẽ làm việc
[00:26:41] của đêm thôi à
[00:26:43] ở bên mình sẽ có bảng lớp ở sinh viên và
[00:26:46] bây giờ mình sẽ chấp nhận Cốt lại hết
[00:26:48] toàn bộ cốt hôm trước đi nếu mà sẽ theo
[00:26:50] một tí format khác tí cho bé ông xem qua
[00:26:53] nhé
[00:27:01] Ừ ok đầu tiên thì như tôi bảo là luôn có
[00:27:04] tạo phải đánh trước này
[00:27:12] vội Tôi muốn khi mới vào trang web như
[00:27:15] thế này
[00:27:16] khi mới vào trang web như thế này có cần
[00:27:19] muốn hiển thị ra có cái Menu ở đây là
[00:27:22] hiển thị ra là một cái Menu xong rồi có
[00:27:25] thể bấm vào danh sách sinh viên này sang
[00:27:27] sách lớp gì đó thì sẽ ổn hơn thì tôi sẽ
[00:27:31] cần gọi đến một thằng tôi như tôi từng
[00:27:34] nói anh sẽ gọi đến mua hàng là thằng
[00:27:36] controller đã thằng con Zalo nó sẽ làm
[00:27:38] gì Làm sao bằng bộ bàn đúng ạ sẽ làm gì
[00:27:41] Làm sao mình sẽ lickytung controller
[00:27:43] được ạ
[00:27:52] anh em cho anh chàng Ngọc Ánh Ừ đợi thì
[00:27:58] con trả lời này nó sẽ làm gì đó Đầu tiên
[00:28:02] thì bây giờ tôi muốn à nó cầm là chèn
[00:28:05] thêm cái máy ngủ em ạ Nhưng giờ như tôi
[00:28:08] đã nói thì mình nên luôn để cái file
[00:28:11] view nằm trong thư mục view Tí nó sẽ có
[00:28:13] rất nhiều view đấy thì mình lên đó cho ở
[00:28:16] trong môi thư mục riêng
[00:28:19] thì mình sẽ review này
[00:28:21] anh xóa tạo file đây là menu chấm pp này
[00:28:26] ở đây mình sẽ có thể 216 to là
[00:28:30] ở đây là menu chẳng hạn
[00:28:35] ở đó sau đó thì mình sẽ có thường mình
[00:28:38] sẽ có oli kiểu ngay
[00:28:40] a cho thể a a thôi danh sách
[00:28:45] lớp cho này kiểu ngay mục alo đi
[00:28:51] và đây sẽ là danh sách sinh viên này ạ
[00:28:54] theo chuẩn như thế
[00:28:56] Bây giờ khi mình bấm Mình muốn bấm vào
[00:28:59] cái danh sách lớp này bản chất là nó sẽ
[00:29:01] nhảy đến một cái gì đó không ạ Mình sẽ
[00:29:04] mình cần mình bấm nhảy đến sẽ chưa lên
[00:29:08] hai địa chỉ này một cái gì đó để mình
[00:29:10] hiểu được là nhảy sang bên lớp chứ mày
[00:29:13] nghỉ chẳng đến sinh viên là sử mình sẽ
[00:29:15] có hai thằng nọ một thằng lớp rồi thằng
[00:29:16] sinh viên không ạ
[00:29:19] thì mình cần phân biệt ở bấm là thằng
[00:29:21] này nó sẽ nhảy ở bên lớp bấm thằng ảnh
[00:29:24] để bên sinh viên không ạ
[00:29:29] Ừ thì thì mình cần ở đây tôi sẽ truyền
[00:29:32] lên đây nó sẽ khác rồi Đã trận hôm trước
[00:29:34] mình làm tôi có thể có thể truyền lên
[00:29:37] đây Container là ạ bằng ở đây một thằng
[00:29:40] là lớp một thằng đấy sẽ sinh viên là đã
[00:29:44] cầm nhà
[00:29:46] mình hãy bấm vào đây sẽ chuyển một
[00:29:48] Angeles và bấm đây truyền control sinh
[00:29:51] viên ngoạn
[00:29:52] đương nhiên khi mình bấm vào control of
[00:29:54] mà mình chưa truyền đã trường gì thì tôi
[00:29:57] muốn hiển thị an toàn bộ lớp đúng ạ thì
[00:30:00] mình sẽ làm nhà thì ở bên ở bên này vẫn
[00:30:04] sẽ gọi
[00:30:06] Ừ tôi sẽ ở đây tôi sẽ phải sửa một tí
[00:30:09] trong sợ mày à tôi sẽ không gọi Hoàng
[00:30:11] controller tổng nữa mà tôi sẽ gọi cho
[00:30:14] lớp controller là sinh viên controller
[00:30:16] được
[00:30:22] Ở đây là tôi sẽ là ít MT
[00:30:27] đôla get đ
[00:30:30] xe
[00:30:30] [âm nhạc]
[00:30:33] container
[00:30:34] kéo lúc đầu không có này thì tôi sẽ gọi
[00:30:37] hoặc Angeles bình thường con Eo sao ạ
[00:30:43] chợ hoa cài ở rộng như hôm trước tôi làm
[00:30:45] thưởng này dùng xích cây đấy tôi thử
[00:30:47] dùng những xích cay cho mấy ông quen nhé
[00:30:51] thích cây đấy
[00:30:57] nếu mà không trống này cho biết
[00:31:00] controller Cho
[00:31:02] xem điện Castle này à
[00:31:06] anh ở đây controller
[00:31:09] Nếu lúc đầu cây là chấm thì mình sẽ
[00:31:13] White thằng controller gấp thế này
[00:31:17] subject này còn đều cây ở lớp
[00:31:20] Ừ
[00:31:22] thì mình sẽ đi qua lớp controller thằng
[00:31:24] nào
[00:31:31] gì
[00:31:32] Ừ tôi thường nhà ở Tôi thường là nếu mà
[00:31:36] Real thì nó sẽ để tên nó trước cái chữ
[00:31:39] container cơ
[00:31:40] thì nó sẽ kiểu là nó sẽ viết hoa cơ chắc
[00:31:44] là tôi cứ tạm viết kiểu nhà trong đêm
[00:31:46] quen đã
[00:31:48] không anh em không hứng thủ viết code để
[00:31:51] ở đây cả
[00:31:53] sinh viên này à
[00:31:59] là như này và mình sẽ có một cái đẹp khô
[00:32:03] gần như hôm trước mình có một cái đẹp
[00:32:04] đâu thì sẽ cho ở đây rằng ạ cái là kiểu
[00:32:09] đấy Ăn đậu Nó đôi khi nó gợi ý gửi cho
[00:32:11] hai đúng không Không tin Không Không tìm
[00:32:15] thấy controller phù hợp trở lại ạ
[00:32:20] ừ ừ
[00:32:30] hợp này báo lỗi không tìm thấy file này
[00:32:32] nhà tôi bước ra xử nhập viện gia đình
[00:32:34] ngay nó sẽ báo lại ngay đúng không Không
[00:32:37] tìm thấy phù hợp còn mặc định lúc đầu
[00:32:39] vào nó sẽ để làm menu nóng lạnh bởi một
[00:32:42] controller nước này rồi Bây giờ mình sẽ
[00:32:44] tạo nên lớp controller
[00:32:46] Ê
[00:32:46] mấy ông có thể là tạo hẳn một thư mục ăn
[00:32:49] cho lợn được thường mà tôi cũng sẽ tạo
[00:32:51] một phần của chung 1 của controller đấy
[00:32:53] thôi Tấm và trong đấy cũng là một cách
[00:32:54] hay ừ bây giờ có khi tôi tạo luôn mày
[00:32:57] Ông nhé để tạo nhé sẽ là một thư mục là
[00:33:00] cần cho lợn
[00:33:07] tôi làm kiểu dạng là nhét hết vào trong
[00:33:10] như này cho mấy ông quen dần đi tôi sẽ
[00:33:13] tạ Nếu thế tôi nhét hàng ngày vào trong
[00:33:15] ngày trước đã
[00:33:32] tôi phải sửa lại các tên hay nữa tên là
[00:33:35] rút đi
[00:33:44] này
[00:33:45] A và cắm trailer hay trèo lớp theo kiểu
[00:33:48] nha à
[00:33:54] anh kể tiện mà Mấy ông về sau Sửa tên nó
[00:33:57] dễ hiểu nha Coffee vào cái xong OK đương
[00:34:02] nhiên vẫn chưa có hoài vậy mình sẽ tạo
[00:34:04] lớp cần trả lời nha ở bảng xếp
[00:34:16] là lúc đầu chưa có gì cả Lúc nào chưa gì
[00:34:18] cả như này thì mình sẽ cần là mình sẽ
[00:34:20] kết nối đến thằng Mua đồ xong rồi từ
[00:34:22] hàng mua đồ mình sẽ lấy toàn bộ lớp xong
[00:34:25] rồi in ra ở trong một phòng vi là không
[00:34:27] ạ Mình sẽ gọi mà mua đồ này
[00:34:30] cái tên này ạ
[00:34:33] ờ ờ
[00:34:34] Ừ nhưng mà như như bây giờ các bạn thấy
[00:34:37] thời bây giờ nó sẽ có hai mua đồ luôn
[00:34:39] một mua đồ mua đồ lớp mua đồ mua đồ sinh
[00:34:42] viên không ạ Mình có thể là tạo phần 1
[00:34:45] thư mục nữa là thư mục
[00:34:48] đi mua đồ mà mình sẽ có
[00:34:51] I love đ.tp mấy ông thầy bắt đầu tôi tạo
[00:34:55] rất nhiều thư mục con ở rất nhiều Phai
[00:34:56] đúng không Mình có thể khó theo nên mày
[00:34:59] ông vào vào của tôi xem hoặc cào vào
[00:35:01] link của bạn lớp trưởng để mà xe mình nó
[00:35:03] tiện hơn Xem của tôi là file nó bị lại
[00:35:07] tải nhỏ mấy ông sẽ không tập trung không
[00:35:09] không không theo dõi được không ạ
[00:35:12] Anh thường à Bây giờ tôi còn tạo thành
[00:35:15] một file riêng file con dê cơ tôi cấu
[00:35:18] tạo một cái con nít trước đã nhé
[00:35:26] à à
[00:35:27] hình
[00:35:28] ảnh chưa nhiều nhưng mà rõ ràng các bạn
[00:35:31] khác loạn đấy ạ
[00:35:39] gọi nó đề xuất hiện mãi nhé cao
[00:35:42] Selection from Plus này
[00:35:46] sau đó thì mark
[00:35:49] từ
[00:35:56] khi nói ở đây nó báo không tìm thấy bảng
[00:35:59] vì tôi chưa reset lại cái này sẽ vào đây
[00:36:02] reflect này thì nó sẽ tìm lại được các
[00:36:05] bạn đó
[00:36:06] à tiện đúng không
[00:36:08] Đấy nó sẽ trả về kết quả vào trong cái
[00:36:11] Ji Sub này sau đó thì thằng này mình sẽ
[00:36:15] mình sẽ gọi đến zwei đến một thằng view
[00:36:19] Sao chửi mày tôi view tôi lại chưa nhỏ
[00:36:22] đó nữa lại thương một con nữa là lớp như
[00:36:26] thế này sau đó tôi tạo một thư mục nữa
[00:36:28] nó lại Index chạm p p
[00:36:31] gì để mà Thì địa danh sách
[00:36:33] I I love này duc.tp như thế này vào đây
[00:36:37] Bây giờ mình mới hiển thị ra
[00:36:40] danh sách lớp này mình cho một cái thấy
[00:36:44] bồ
[00:36:56] không sao
[00:36:59] mã tên kiểu ngay sau đó thì mình sẽ có
[00:37:03] ích này
[00:37:05] em bị sốt từ kết quả này à
[00:37:09] em
[00:37:27] mã này nó chủ đề tên
[00:37:31] đó in ra
[00:37:34] Ừ cái cảnh báo để kệ đi bởi vì bản chất
[00:37:37] cái virus này mình lấy từ Model cơ Chẳng
[00:37:39] phải là không Hiệp trả lại này đó mình
[00:37:43] sẽ có bộ đồ
[00:37:46] a bít lại
[00:37:48] nó như thế này
[00:37:51] ừ ừ
[00:38:00] qua với cô đi à Thằng chụp cho tao dùng
[00:38:02] cái gì để được chuyển có sau đây tách
[00:38:04] được à
[00:38:06] Ừ ok
[00:38:08] Bây giờ đưa nhiên cho cả lớp nào thì cho
[00:38:10] ngoài như này bây giờ sử tôi có tạo
[00:38:12] trước một lớp mình không xem nhé
[00:38:15] anh ở đây rất là trình đi thôi Để hẳn
[00:38:19] tiếng Việt có dấu với ạ
[00:38:26] đời
[00:38:27] khi họ sao nó không nhập với có dấu
[00:38:30] anh về nha
[00:38:36] đó lâu chưa
[00:38:46] thêm này mình sẽ có Hz ở đây
[00:38:51] trong trường hợp này trong trường hợp
[00:38:53] này thì mệt
[00:38:56] Ê mày ông sẽ thấy là thức a khi bấm Hz
[00:38:59] này nếu mà Mấy ông truyền Á trên không
[00:39:03] thôi giống như hôm trước là là crash
[00:39:06] chẳnghạn đúng không Thế này bấm vào nhá
[00:39:08] thiếu mấy ông thấy làm mất cái
[00:39:10] controller thì mất mất cái controller
[00:39:13] gốc mà ông nhận để em ạ đang controller
[00:39:17] ở lớp đúng không thì bấm vào thì nó sẽ
[00:39:19] ghi đè lên cái cái cũ để làm mất đi ông
[00:39:23] ạ nhiều ra cách kiểu như là nó không tốt
[00:39:25] Nó không tốt thì đang nghe mày ông sẽ
[00:39:28] phải truyền cả controller l vào trong
[00:39:29] máy nữa thế này
[00:39:32] những
[00:39:32] ngày này bằng lớp như này
[00:39:36] đây như thế này nhưng mà
[00:39:39] nói chung là tí rồi sẽ chỉ mấy ông sửa
[00:39:42] mà cái đoạn này nhanh cho cho dễ Hiệp à
[00:39:45] ừ ừ
[00:39:47] Ông
[00:39:47] Hà ông ý ông có thể truyền kiểu em ở đây
[00:39:53] đúng không ạ thử nhà à
[00:39:58] bấm lại bấm này đâu Ông bảo em kiểu gì
[00:40:03] không không không kiểu như thấy được bản
[00:40:06] chất khi bấm vào đường link mà Kiểu gì
[00:40:08] nó suy nghĩ đèn lên nó sẽ không kiểu như
[00:40:10] thế được trừ khi ở mấy ông chơi trò là
[00:40:12] mấy ông điện than thở không không cách
[00:40:15] nào cái đấy Được mà Chắc là ông sẽ phải
[00:40:17] ghi lại thôi nghe cách tôi thường ai làm
[00:40:20] không Đây đây là cách tôi thường làm nhé
[00:40:22] ngờ tôi có một ví dụ như mấy ông cậu
[00:40:24] ngay tại mấy ông cứ bây giờ có bấm là ok
[00:40:27] ngay đúng không Bây giờ mình sẽ
[00:40:30] ở tạm Tắt bớt nó ngoài đã thôi Dùng dào
[00:40:33] Buddy thì trong trường hợp này thì lại
[00:40:36] bắt chước giống như lần trước và lần này
[00:40:38] mình sẽ lấy á truyền ra đúng không ạ thì
[00:40:40] thường à Kiểu gì Bị sẽ lấy áo trần nhận
[00:40:43] thường tôi sẽ lấy ác Trần ngay từ trong
[00:40:45] khai báo ở bên này tội lẽ trên đời này
[00:40:46] để đỡ đoạn mấy cái thằng container kia
[00:40:49] phải lá ison sẽ thay bảo trước ở trên
[00:40:52] đây là cách ngắn gọn hơn viết của thằng
[00:40:55] này theo pp 7 nó còn ngắn hơn tôi sẽ
[00:40:58] viết lại cái này theo cách của P7 nha
[00:41:00] mình em sẽ thấy Container bằng
[00:41:02] đồ ghét controller này
[00:41:05] hỏi chấm hỏi chấm như thế này
[00:41:09] anh Bày cách viết của pp7 đội lên thì nó
[00:41:12] sẽ biết được cả ngày nghĩa là kiểm tra
[00:41:15] hàng ngày tồn tại không không sẽ lấy
[00:41:17] xanh này Đấy 1 trong 2 hai tay sai của
[00:41:21] tôi đang mặc định đến của tôi là 5.6
[00:41:24] không có nghe mấy ông đổi VTV7 của tôi
[00:41:26] 7.4 em ạ nó thì nó sẽ không báo lỗi nữa
[00:41:29] Ok chưa đó như này nó sẽ tiện hơn nếu
[00:41:33] bạn Ok thì
[00:41:35] tôi sẽ lấy a trên về đúng như thế
[00:41:38] này thỉnh thoảng tôi sẽ tối ưu cốt cho
[00:41:41] mấy ông xem một tí không ạ Không hẳn cái
[00:41:44] tắt làm đâu tối ưu lại cách viết cho
[00:41:48] nhìn cho thoáng hơn nhưng mà không phải
[00:41:50] hiểu nhé Nó không khác gì vậy bản chất
[00:41:51] nó không khác gì nhau cả
[00:41:56] Ừ Ừ
[00:41:58] đang định nói rồi bạn ở
[00:42:01] bên Angeles này thì bây giờ trong trường
[00:42:05] hợp mình lại thích cái thôi trong trường
[00:42:08] hợp là á chân Ê
[00:42:10] bà cách là trống như thế này thì mình sẽ
[00:42:16] White toàn bộ đoạn này
[00:42:18] a subject ông ạ Còn nếu trường hợp cây
[00:42:22] là les thì mình sẽ chỉ đi qua một cái
[00:42:26] view một cái lớp và đầy C class 6A
[00:42:31] Ừ nếu không sẽ thấy cái này copy pate
[00:42:34] khá nhiều đấy
[00:42:35] a form này
[00:42:38] ở đây là tên đến phút 22
[00:42:43] à à
[00:42:47] khi tách mềm tên Tân thêm mặt nạ
[00:42:53] khi
[00:43:00] ờ
[00:43:01] ờ hỏi chấm
[00:43:04] bài hát chân bằng
[00:43:06] store and controllers
[00:43:09] bằng lớp
[00:43:12] kẹo nhà à
[00:43:15] chú chó Mày không thấy nó sẽ nhảy sang
[00:43:17] cái này không ạ Và khi mình Điền ở đây
[00:43:21] là sự là bảo mật rồi lại rất bảo mật
[00:43:23] thêm một lớp mới không ạ thêm vào không
[00:43:27] báo lỗi gì cả và bản chất là nó sẽ nhảy
[00:43:30] vào cái cây này một cái phố ở đây nè
[00:43:33] anh không ạ Thật sự đây đã bình thường
[00:43:37] nên phải có một cái đẹp vô để trong
[00:43:39] trường hợp người dùng nhập quá trình
[00:43:41] tinh nhật hát Trần của lớp sai rồi em ạ
[00:43:47] Các bạn rồi ghi rõ lớp vì sao còn không
[00:43:51] biết được nó nhảy và thằng lớp hai thằng
[00:43:53] sinh viên nó sai à
[00:43:55] chỉ có như này nhưng mà bây giờ ra sự
[00:43:58] mình store và như này gọi thằng mô đồ và
[00:44:03] nhôm trước mình bảo là mình sẽ lấy lại
[00:44:05] cái thứ mà mình đã điền trong form ở bị
[00:44:07] caro sẽ lấy tên bằng đôla hot
[00:44:12] tên như này rồi chuyền vào thằng Model
[00:44:15] modem trường hợp này thì mình lại copy
[00:44:18] cái xích cây này
[00:44:20] à à
[00:44:22] à à anh không cần giấy FO
[00:44:26] thì mình sẽ chị có chia trường hợp là
[00:44:28] trường hợp
[00:44:30] anh nói chung là kiểu gì nó cũng giờ mấy
[00:44:33] trường hợp đúng rồi nó còn không mà
[00:44:34] không ngậy và thằng mua đồ chúng nó sai
[00:44:36] không cần đấy phô gì cả anh ở đây mình
[00:44:39] sẽ là
[00:44:40] em ra mà Insert into love tên
[00:44:53] là tên
[00:44:55] nhà đúng ạ
[00:45:07] hoa nhà
[00:45:10] chạy này không báo lỗi nhưng mà cứ quay
[00:45:14] bên này em làm lại chắc ngoan ra bảo mật
[00:45:16] rồi
[00:45:17] Ừ thế giờ Xóa Xóa Thằng này đi này đó
[00:45:22] thì dao động ngay nó ngoan ý cho mấy bạn
[00:45:27] này thật ra bởi Hôm trước mình làm rồi
[00:45:29] nhưng mà các bạn thấy nó phức tạp hơn
[00:45:30] điểm mà nó trên nhỏ nhiều thêm một con
[00:45:32] nữa thì mới ông sẽ bị loạn hơn tí nhưng
[00:45:36] mà tội sẽ tôi Nhanh cái mấy loại này Hôm
[00:45:38] trước làm rồi mà bạn đấy thì đôi khi có
[00:45:41] nhiều Buổi tôi sẽ nhắc lại kiểu như thế
[00:45:42] này nhưng tôi sẽ thay đổi một tí thì mới
[00:45:46] ông phải nhận Nguyễn buổi hôm trước đã
[00:45:48] buổi hôm nay nằm kiểu nó đỡ bị choáng
[00:45:51] chứ tôi không muốn lại chỗ hoàn toàn
[00:45:53] được không ạ còn lại hoàn toàn thì lưu
[00:45:55] lại video của mình cho à
[00:46:04] cái đít này em
[00:46:07] controller
[00:46:09] bằng lớp này em này
[00:46:13] mã nữa
[00:46:15] ừ ừ
[00:46:23] Mã
[00:46:26] ngày để xuất ra nhiều ạ
[00:46:29] anh
[00:46:31] sửa à
[00:46:38] quen cái kiểu nhà đã để mà khi mà xăng
[00:46:40] Facebook thì mấy ông thấy nhẹ nhàng vãi
[00:46:49] không mua đổ em không hướng về bên chưa
[00:46:51] Cho làm ok đâu nên là mua đồ của em nó
[00:46:53] vẫn đang hơi nông dân một tí khi mà em
[00:46:55] để sang ov10 C và các hợp âm nữa thì thì
[00:46:58] nó mới khác còn bây giờ mua đồ kiểu ngay
[00:47:01] thì bạn chất nó giống cái á p thuần
[00:47:04] Chẳng qua bây giờ nó suốt cây si cây
[00:47:06] thôi nó sẽ là thích cây thôi bà bây giờ
[00:47:09] mình đang làm thì cả mới xe rồi chia nhỏ
[00:47:11] những cái hại ra dư âm từng từng mảng
[00:47:13] từng mảng riêng đến các bạn hiểu rồi
[00:47:16] chưa chưa có USB thì đây cả controller
[00:47:18] hay mua đồ bây giờ nó vẫn đang rất là
[00:47:20] nông dân
[00:47:22] à à
[00:47:23] ờ ờ đó bé mình bấm vào sửa này thì đương
[00:47:28] nhiên là lại phải khai báo ác chân ở bên
[00:47:30] bên cần trả lời trước đúng không
[00:47:33] Ừ ừ thì hôm nay thầy dự giờ tôi biết mà
[00:47:36] thấy cảnh báo trước rồi
[00:47:38] Không sao Không sao ạ ừ ừ
[00:47:46] view nữa để mà hiển thị ra Adidas nóng
[00:47:50] hoặc format
[00:47:52] trong trường hợp này thì đây sẽ là edit
[00:47:55] này
[00:47:56] thì mình sẽ lách mình copy đoạn này thôi
[00:47:59] đó là celexa for love em mình sẽ
[00:48:04] ba que
[00:48:07] a mã bằng đô la mã này mà lần này mình
[00:48:12] chỉ trả về một thằng thì lại về dụng
[00:48:14] phases ai đúng không như này trở về đâu
[00:48:18] Like xong rồi chuyền vào trong tháng ADN
[00:48:21] này thằng ấy đi này bản chất là như tôi
[00:48:23] bảo thì hãy copy đã ký kết của thằng
[00:48:25] Grant này nó sẽ dai đít này
[00:48:34] lưu cho nó
[00:48:35] mày không thấy gợi ý gì đâu xin mãi một
[00:48:39] tí phút hai lần đi
[00:48:41] chị thay bằng đỏ như thế này
[00:48:46] vẫn công nhận bây giờ nó không Tôi thấy
[00:48:50] cách gõ nó không tối ưu được bảng bên
[00:48:53] sau khi tách nên nó đề xuất thế giới
[00:48:55] Ngon hơn thôi
[00:48:57] ở đây mã này
[00:48:59] để sửa đấy
[00:49:02] tôi gõ hơi bị nhanh quá với ông không
[00:49:05] biết nếu không theo kiểu không ạ
[00:49:08] ở đó như thế này
[00:49:10] bây giờ lập trình như này sợ đi
[00:49:13] đi đái Tuấn sửa sửa Bây giờ mình lại lại
[00:49:18] Cập nhật lại bên lại vẫn điệp khúc mà
[00:49:20] cần cho lo xong rồi vợ là mua đồ đúng 0h
[00:49:24] đêm này
[00:49:25] lấy về
[00:49:31] Anh tên này
[00:49:33] Ừ ừ ừ rồi Tao quên điều hướng đấy phải
[00:49:35] thêm xong rồi tôi phải điều hướng về tôi
[00:49:37] quên đấy ạ bây giờ sợ lại
[00:49:45] đúng không không không Em muốn làm kiểu
[00:49:47] các bạn chưa động và phong trần vội xanh
[00:49:50] Ok thì em sẽ làm theo cẩu vừa phong
[00:49:53] phanh trần luôn
[00:49:55] em có mấy giờ tôi Em đang làm hay cỡ là
[00:49:57] em hiểu gì anh nghĩa là một file Mua đồ
[00:50:00] xong rồi tạo theo nhiều phương trinh
[00:50:02] không ạ Cũng cũng cũng giống giống làm
[00:50:06] xanh OB thì mình cũng gọi đến Hàm Phong
[00:50:08] trên mấy thước của nó thôi
[00:50:11] ờ ờ
[00:50:13] ạ bây giờ bản chất thì mình vẫn là xích
[00:50:16] cay xong rồi mình sẽ chia trường hợp ra
[00:50:18] được mà gọi đến gọi đến cái tương ứng
[00:50:20] của nó nên nó không khác gì nhau mấy
[00:50:23] à à
[00:50:26] thể loại mà
[00:50:28] sang update này mình sẽ update
[00:50:32] a date of này set
[00:50:36] tên bằng tên này hay ở thỉnh thoảng nó
[00:50:39] cực và ở sông được trồng dễ nhìn
[00:50:43] đưa tên này à
[00:50:45] ở trong cái tôi thấy trợ chung thích dễ
[00:50:48] nhìn hơn đấy ạ
[00:50:51] Ừ ok xe tên bằng tên chỉ còn chạy thôi
[00:50:54] không cần trả kết quả này không ạ à
[00:50:58] khi
[00:51:00] chạy thử đã nhá không báo lỗi này đó ra
[00:51:04] được rồi này khi mà chắc chắn Các bạn
[00:51:06] thấy đều ổn như này thì các bạn sẽ điều
[00:51:07] hướng quay về không ạ
[00:51:15] hết đồ
[00:51:18] cái sân này
[00:51:28] khi chuyển sang mua đồ làm việc với tao
[00:51:30] bây Đúng rồi mua đồ làm việc với
[00:51:33] database Nhưng mà như bạn chất thì mình
[00:51:35] vẫn phải
[00:51:37] đã theo theo ý Có phải bạn đang thắc mắc
[00:51:41] kể ý của anh Chánh đang góp ý các bạn
[00:51:44] kia có bí là mình có thể không cần dùng
[00:51:46] thích cày đây này mình sẽ tạo những
[00:51:48] phông chữ nhỏ phăng chuyện nhỏ để mà sau
[00:51:52] đó thì mình sẽ gọi em thằng thằng mình
[00:51:55] sẽ gắn inplus hả Mua đồ gọi phanh chân
[00:51:57] của thằng này sợ là Shake to này để lấy
[00:52:01] tất cả này nè select One để lấy một
[00:52:03] thằng hèn gì đó
[00:52:05] à à
[00:52:07] anh em thì đang không muốn độngphong
[00:52:09] trường vội em muốn chị làm sui cây thân
[00:52:12] hết Còn khi mà sang o p lại động và
[00:52:15] phanh chân mới thất các thứ thứ sao
[00:52:21] đã bình tĩnh
[00:52:23] đoạn này thì bản chất là lỗi cái chân nó
[00:52:26] vẫn sẽ à
[00:52:28] về bản chất nấu cái sân ở đây cái đoạn
[00:52:31] Index nó vẫn sẽ nhảy về nách không ạ
[00:52:33] nhưng mà nó sẽ hỏi chấm thêm khá dài
[00:52:35] dòng này tôi thường sẽ hỏi chẳng hạn các
[00:52:38] bạn lại khá dày được gì
[00:52:40] a&amp;p đúng không
[00:52:43] Không cần ăn kiêng gì cả chỉ có Zalo
[00:52:46] thôi bằng lớp này chắc lại thử nhé á
[00:52:51] à à
[00:52:58] là khuyên nhau
[00:53:00] làm thêm phải xóa nữa xa lạ này
[00:53:05] à à
[00:53:09] đã
[00:53:15] một cái gì cả Chỉ đơn giản là Delete để
[00:53:17] xóa thôi thì cái lại xa ngắn sẽ Delete
[00:53:20] này rồi Đây là mấy thoát ra ghét này
[00:53:24] anh tặng tắt cái đĩa ai đúng không ở đây
[00:53:28] mình sẽ có cái Delete này à Ừ mình ạ
[00:53:34] I Delete for love
[00:53:37] ngài xong đĩa xong rồi
[00:53:41] anh ấy nhỉ
[00:53:44] đã xóa này
[00:53:51] cho điều hướng quay trở lại
[00:53:53] Ừ ok chưa để em làm đầy đủ tính năng
[00:53:55] thêm sữa xóa nhanh của lớp mấy ông sẽ
[00:53:59] thấy là vừa rồi thực cả không ăn nhanh
[00:54:01] lắm nếu là tôi thì copy cái này sang bên
[00:54:04] copy toàn bộ Cái này sang bên sinh viên
[00:54:09] nhưng mà ông sẽ thấy có thể nhanh nha
[00:54:10] nhìn cậu cách tôi copy nhá Ờ
[00:54:18] Để tôi tạm tắt hay đi đầu tiên mọi thứ
[00:54:22] vẫn tự nhiên tôi đã khai báo đây một cái
[00:54:24] là sinh viên rồi ông ạ Tôi sẽ copy đầu
[00:54:26] tiên copy lớp này rồi copy sinh viên này
[00:54:29] nhớ đây trong trường hợp mà Mấy ông làm
[00:54:32] theo kiểu là
[00:54:33] nó sẽ có khác nhau một tí của vì sinh
[00:54:37] viên đây còn thêm một cột cột bạn lớp
[00:54:38] nữa như cột mã còn có tên là giống nhau
[00:54:40] em cách copy nó cũng khá nhanh thôi Đây
[00:54:45] Anh thường là tôi chỉ đổi toàn bộ truyện
[00:54:47] lớp ở trong này tôi để hết hàng triệu
[00:54:49] sinh viên làm được nếu mà Mấy ông làm
[00:54:51] theo cậu quy tắc là cậu đặt tên file tên
[00:54:54] biển có xử nó hợp lý nó giống nhau để
[00:54:57] thử cho mình xem nhé à
[00:55:04] khích đâu
[00:55:05] nhưng có một nhược điểm đây tôi không
[00:55:08] thích cái vụ là cái controller này ăn
[00:55:10] cho lợn này nó đôi khi nó lặp lại được
[00:55:12] đúng thì biến controller ở ở đây mình
[00:55:14] thấy báo ấy thế là tôi thường là tôi sẽ
[00:55:18] I read luôn được mình controller vào
[00:55:20] trong may bay để tôi ví dụ mày Ông ấy
[00:55:22] ông dễ hình dung hơn
[00:55:30] này tạm bỏ tạm bỏ đầy giá nhé
[00:55:35] ở đầu tiên mình có vào bên A
[00:55:39] cho sinh viên trước
[00:55:41] Anh chưa tìm hiểu về mua đồ sinh viên
[00:55:45] đúng không Ok tôi sẽ khai báo một cái
[00:55:47] mua đồ sinh viên ở đây à
[00:55:54] có một file khác nữa thì ổn hơn này ở
[00:55:56] thì tôi sẽ tầm cái thoại cái này sao một
[00:55:58] cái file
[00:55:59] cài đặt tên file wi-fi Connect p
[00:56:04] chậm nhai
[00:56:07] mấy ông sẽ chỉ cần Wifi này là ổn
[00:56:16] mấy ông thấy là rõ ràng là cái file lớp
[00:56:20] này nó cùng cấp về cái file con ếch
[00:56:23] không ạ Nếu không sẽ nghĩ ra là chị gọi
[00:56:25] con ếch nghe được đâu em ạ Nhưng không
[00:56:27] Cái cái cách của mình bây giờ mình đi
[00:56:30] quay một cái thứ gì đói mình sẽ phải
[00:56:32] luôn
[00:56:33] cho mình mình sẽ phải luôn nhìn từ cái
[00:56:36] file Index bởi vì bản chất mình luôn
[00:56:38] đứng ở file đắt nên là nó sẽ phải ghi rõ
[00:56:42] là nhà mua đồ cho cái chéo con ếch cái
[00:56:45] này cơ mà ông sẽ thấy là từ controller
[00:56:48] mình đã phải làm như thế rồi rõ ràng
[00:56:50] trong container nhá mày không để ý kỹ
[00:56:52] lại nha trong Trailer này đáng lẽ thường
[00:56:54] với ông nghĩ là mình sẽ phải thoát ra
[00:56:56] khỏi có chút một con trả lời xong rồi
[00:56:57] vào thư mục Mua đồ xong mới gọi gọi được
[00:57:00] và những cái này hay vào máy cày view
[00:57:02] đúng không ạ nhưng mà không thấy rõ ra ở
[00:57:04] tôi chỉ gọi tên thư mục ngay thôi Bởi vì
[00:57:07] bản chất là mình vẫn đang đứng từ trên
[00:57:09] đấy để mà gọi xa những thằng kia đúng ạ
[00:57:11] nên thằng này làm thế chúng ta sẽ về đi
[00:57:14] quay ở ngay
[00:57:18] bạn tiếp theo bể nát chân là xong rồi
[00:57:21] đây tôi hiện đội hết đồng loạt
[00:57:23] và đáp án sinh viên là xong đấy à
[00:57:26] và đương nhiên là cái này vẫn chưa chạy
[00:57:28] được hết đâu vì có thêm một cột nữa ở
[00:57:30] cột mã lớp nữa cứ bình tĩnh đã
[00:57:38] view này
[00:57:43] đương nhiên à Cái này tôi chỉ đang chỉ
[00:57:47] cho bé ông về cái mẹo vặt để mà có thể
[00:57:49] làm được nhanh thôi Bình thường à chúng
[00:57:52] ta biết được là mỗi bảng mình phải làm
[00:57:55] nhiều cái khác nhau ấy không hẳn là copy
[00:57:57] được Kiểu hoàn toàn như này đâu Như Ý
[00:57:59] tôi là khi mà các bạn làm một cái mô
[00:58:01] hình mvc rồi làm cậu nhóc các thứ ổn rồi
[00:58:04] các bạn thay đổi sửa nó vẫn dễ và có thể
[00:58:09] gọi là sao chép cũng dễ với tính năng về
[00:58:12] các bạn nữa tính nào chị xem thêm sửa
[00:58:14] xóa ngày copy rất là nhanh rất dễ các
[00:58:16] bạn chỉ cần đổi tên bảng đã xong nãy giờ
[00:58:19] tôi thật là tôi cố tình để hẳn Nó là
[00:58:21] kiểu Huy hàm phát cốt ở Nga ghi hình
[00:58:23] trên mạng ngay thực tế là nếu có thể mất
[00:58:27] cái ví dụ ở mấy cũng thể đổi thay bồ như
[00:58:29] ngày bằng sinh viên ở trên đấy này
[00:58:31] sôi Ông mấy ông chị còn hay hết toàn bộ
[00:58:34] xuống dưới là thấy bồ nhé mày anh thấy
[00:58:37] hết toàn bộ xuống dừa như thế này thì
[00:58:38] cũng không cần được ăn chôn hát Giống
[00:58:39] Như Tôi vừa làm nó mấy ông chỉ cần đúng
[00:58:41] đúng rồi mình không chỉ cần đổi tên bảng
[00:58:43] thê bộ trên này thì toàn bộ Cái dưới nó
[00:58:46] sẽ nhận nếu không hiểu thì không ạ Đấy
[00:58:49] nó rất là nhanh rất tiện như thế khi mà
[00:58:51] các bạn làm thì cậu mô hình tưởng như
[00:58:52] này nghĩ ra các bạn hồi trước các bạn
[00:58:54] làm trong đón một các bạn có rất nhiều
[00:58:57] file mỗi file lại phải kết nối các thứ
[00:59:00] thứ rất lằng nhằng thuốc ta với ngọn đấy
[00:59:02] mời các bạn chỉ tập chung 1 file Đây là
[00:59:04] các bạn thì cần sửa cái pha đấy tất cả
[00:59:06] chỗ khác đều rồi chạy đúng
[00:59:08] Ừ đấy quy tắc của mới xe nghĩa là các
[00:59:11] bạn sửa ở chỗ liên quan cơ sở dữ liệu
[00:59:14] được các bạn sửa một file thôi sửa Rose
[00:59:16] để sửa một file thôi những chỗ khác nó
[00:59:18] vẫn sẽ chạy à à
[00:59:30] khi ở vẫn phải xem qua cách
[00:59:33] cách
[00:59:35] cái cấu trúc cách viết của TP như nào đã
[00:59:39] ô chữ k nhảy sang cái này thì sẽ hơi
[00:59:42] loạn một tí đấy trừ khi cấp
[00:59:45] Trừ khi bạn có nên sẵn giống như nên sẵn
[00:59:48] Java có thứ tình nhảy sáng mới sẽ ok thì
[00:59:52] mẹ thì ông có nhận cũng dễ hiểu thôi
[00:59:59] tôi sẽ bị đổ cái này thì tên biến
[01:00:01] control thì nó sẽ ổn hơn à
[01:00:09] nhiên là bây giờ thì đâu Cả em vẫn còn
[01:00:11] Hiếu ví dụ thứ nhất là bây giờ tôi muốn
[01:00:13] gì Tên lớp này
[01:00:16] Ừ chắc ạ
[01:00:24] Tôi muốn làm một cái là tên lớp nghe
[01:00:27] chẳng hạn ạ
[01:00:28] em ạ thì cái tên lớp này lại ở đâu
[01:00:32] Anh tên lớp này mình sẽ gọi đến ở bên
[01:00:34] modal sinh viên này mình sẽ
[01:00:41] nữa
[01:00:43] bộ phim sex thầy trò i i
[01:00:52] ạ
[01:01:00] Lớp chấm tên HP love nhà để lấy được đến
[01:01:06] lớp ở đây lời chứ Thằng này nó tự động
[01:01:09] Asiad cho mình
[01:01:16] sẽ đầy đủ đi
[01:01:20] 3 - đánh e định xài hết toàn bộ biến cả
[01:01:24] tên Mạnh thành nhà tiếng Anh ấy nhưng mà
[01:01:27] bị Hôm nay tôi thấy cũng khá nặng rồi
[01:01:29] tôi dậy cậu vẫn
[01:01:30] vẫn tương đối thôi chưa dậy mấy ông Tiến
[01:01:33] anh hoàn toàn
[01:01:35] à để buổi sáng nữa nhé Nói chung là tối
[01:01:38] cư mỗi buổi tôn thêm một tí thôi chứ
[01:01:41] đùng một phát mà khác hẳn cái mấy ông
[01:01:44] thoáng này
[01:01:45] buổi sau xanh opal mày cũng thấy nó khác
[01:01:48] nhiều đấy
[01:01:50] Anh Thọ đây để không ra được nghỉ cho
[01:01:55] lớp mã lớp Ừ đúng rồi nó không ra bởi vì
[01:01:58] khi mình dùng cho như này à
[01:02:01] cho mày xong cái đó sinh viên mình đã có
[01:02:04] lớp nào đâu Thì nó sai mình phải rep cho
[01:02:07] này đúng nét voi
[01:02:13] nóng ạ bây giờ xử tôi cho lớp đang vào
[01:02:16] lớp 2 cho mở lớp là hai này
[01:02:19] đó Ok chưa
[01:02:22] em còn nếu mà Mấy ông không mà dụng nét
[01:02:24] cho là mày không sẽ bắt buộc sinh viên
[01:02:26] nào sẽ có lớp nóng lạnh thì không cần
[01:02:28] phải ghép choi nữa à
[01:02:31] Ừ ok Bây giờ tôi giờ xử tốt thêm một
[01:02:34] sinh viên mới Thêm bây giờ trong trường
[01:02:36] hợp này không cần ấy không phải ở hiển
[01:02:37] thị mũi tên nữa thêm môi trường hợp này
[01:02:39] mình sẽ cần làm gì mình cần phải gọi đến
[01:02:43] Hằng à
[01:02:50] ạ Bây giờ Bây giờ nó sẽ sinh là cái vấn
[01:02:53] đề này
[01:02:54] giống như giống như anh Tráng Vừa nãy có
[01:02:57] nói đó Bây giờ trong trường hợp là nếu
[01:02:59] class này Grande Ariana Grande nhá
[01:03:03] Angeles nhớ về tôi gọi mua đồ của lớp
[01:03:08] Ừ để lấy ra toàn bộ lớp để hiển thị hiển
[01:03:12] thị vào trong trong ngày để mà Shake
[01:03:15] Shake option tất cả lớp thì cái hàng mua
[01:03:19] đồ mà không sử dụng nữa không ạ
[01:03:21] mã sản phẩm mua đồ này sẽ không sử dụng
[01:03:23] nữa nhé Hiểu gì cho anh
[01:03:32] khi mà ạ chị
[01:03:34] Em hãy để tôi nói lại đi nhé
[01:03:38] em tắt đợt mà cái này đi mày ông xem kỹ
[01:03:41] nhé
[01:03:47] này thả trên của thằng này đang là Kris
[01:03:49] đúng không quá chừng bên này không có
[01:03:51] thằng a hundred này và nó cũng sẽ hiểu
[01:03:54] là thằng controller cũng không phải con
[01:03:56] cho lợn lớp này là nó sẽ không gọi xong
[01:03:58] cái này đâu
[01:03:59] ừ ừ
[01:04:00] Vì thế nên là giống như anh chạy mưa anh
[01:04:03] nói là bạn Chất hàng ngày thứ thích cây
[01:04:05] ở bên mua đồ nó không tối ưu đúng không
[01:04:08] Mình sẽ đổi hết cái này thằng Phong chân
[01:04:09] lại Bây giờ em mới bắt đầu Dạy Phần đấy
[01:04:12] thì nếu mà trong trường hợp một bảng như
[01:04:15] hôm trước thì mình làm được theo kiểu
[01:04:16] dạng sức cây cảnh ngay Còn bây giờ thì
[01:04:19] mình sẽ đổ cái toàn bộ phanh chân và
[01:04:21] mình sẽ gọi nó theo phán trình đây mình
[01:04:24] sẽ có những cái phân sinh kiểu nhà ở
[01:04:28] cho tôi sẽ đặt tên ở đây trường đặt nó
[01:04:32] là tên của căn cho l sau đó kết hợp với
[01:04:35] tên của mấy thức sẽ hiểu lớp cả nhà sẽ
[01:04:39] lách này à
[01:04:48] không biết được chèn vào
[01:04:50] biến này sợ ở biển này không tràn được
[01:04:52] vào
[01:04:54] ừ ừ
[01:04:59] thì ông gọi cái phân Trần kiểu ngại thì
[01:05:02] ông sẽ phải có Return rồi một cái sống
[01:05:05] sẽ gọi lại nó
[01:05:07] là như thế này nhá được thử ví dụ cho
[01:05:10] mấy ông nhé Tôi tạm à
[01:05:19] roble thay thay vì thay vì kẹo trong này
[01:05:22] đợi em tí
[01:05:28] a reward thằng Hải đúng không cho thì
[01:05:31] mình sẽ reset bằng lốp xe Lead ngày để
[01:05:35] gọi lên các phóng viên này
[01:05:36] anh
[01:05:37] còn thằng con ếch này thì mình sẽ đổi
[01:05:41] Global
[01:05:52] Anh em lâu không động Global cơ Để em tí
[01:05:55] nhé ạ
[01:06:04] đấy con lô bồ cả Loco rôcô đâu Nè đây à
[01:06:09] ý nghĩa làm chỉ kia các bạn khai báo
[01:06:11] biến ở ngoài phong trần các bạn dùng nó
[01:06:14] bên trong thì chúng ta sẽ gọi của Global
[01:06:16] cả ngay ok
[01:06:24] ra con ếch này
[01:06:27] thì mình sẽ sử dụng được biện con nít ở
[01:06:29] trong này cho mình sẽ truyền biển vi rút
[01:06:32] ra ngoài này khi đói suốt
[01:06:35] ở đây mình sẽ đặt tên nó là lớp thêm chữ
[01:06:38] s cũng được
[01:06:40] ấm chỉ có nhiều lớp
[01:06:43] ạ sau đó thì từ lớp này mình mới gọi
[01:06:46] mình truyền vào trong thằng class này
[01:06:48] tại Đợi mình tí
[01:07:02] hoàng sa vai tách phố ích này nó thông
[01:07:05] minh hơn
[01:07:10] trong trường này tôi không thích dùng để
[01:07:12] biến Vietsub nó cả x bởi vì tí nó sẽ bị
[01:07:15] ngon ấy tôi sẽ phải đặt tên nó tên bia
[01:07:18] nó hơi bị chiều kia tí đi
[01:07:21] à à
[01:07:23] à à Ờ Ờ
[01:07:30] mình là
[01:07:33] pê sô đa lớp tại mã này
[01:07:41] Copy đoạn này đi
[01:07:43] Anh
[01:07:44] tên này à
[01:07:50] bận đợi thì nhé
[01:07:52] nó báo lỗi Tại sao rồi nhỉ aquila
[01:08:16] sạch xà phòng lớp sau rồi nghỉ hai thằng
[01:08:21] con ếch này có vấn đề rồi
[01:08:29] anh ạ
[01:08:33] ạ Bây giờ là ít công ty dùng mvc thuận
[01:08:37] lắm gần như sẽ dùng
[01:08:49] cho em toàn dùng câu lạc bộ cả nhà ạ
[01:08:56] cách sửa nhà như thế nào bây giờ cái con
[01:08:58] ếch nó không tìm được bây giờ thử con
[01:09:01] ếch nữa nhé
[01:09:03] đài được đi à
[01:09:06] ở
[01:09:08] đâu mày nghỉ à
[01:09:16] you make me rồi đây có vẻ không được này
[01:09:20] vì nó không nhận biết con lắc đấy
[01:09:35] hai thằng 2 ngày khác nhau mà đúng không
[01:09:37] rõ ràng tôi thấy y hai thằng khác nhau
[01:09:40] thằng như này thằng rưỡi chết
[01:09:44] cho tôi thử đổi nó thành Nobody
[01:09:58] quen à
[01:10:18] được cái vì con ếch này lại nhỉ
[01:10:25] tôi thường cái này tự động rất lâu rồi
[01:10:29] ờ ờ đợi tôi một tí còn không thì mình sẽ
[01:10:32] phải chơi cách này chơi một cách ta hơi
[01:10:35] nông dân một tí Mình sẽ
[01:10:38] thì mình sẽ tạo cái này là một cái phong
[01:10:41] chân và phương trên kinect Sau đó mình
[01:10:43] sẽ có thành các phòng trên đấy cũng được
[01:10:46] đây ạ
[01:10:49] Ừ nó kìa bình tĩnh
[01:10:52] con ếch này à
[01:10:58] Lại Sau đó thì tôi sẽ ghi tên Hoàng con
[01:11:01] nít này à
[01:11:04] Ừ nó thì đây sẽ là con ếch
[01:11:07] bằng hơi nông dân của Thị
[01:11:10] Như lại ạ
[01:11:13] ở đó thế này cũng được lại một cách
[01:11:16] anh
[01:11:18] alo đương nhiên à với sau ông sang model
[01:11:22] không phải làm cái kiểu nông dân ở ngay
[01:11:23] đi
[01:11:33] trong này đúng rồi nhá ạ
[01:11:39] dòng 44 lỗi
[01:11:42] à à
[01:11:47] có đồ rồi à
[01:11:52] cho tôi Tôi chỉ đang nói qua việc là
[01:11:54] giống như mày anh kia bạc đó là mình sẽ
[01:11:56] tống hết cái nào tăng trưởng thì cách
[01:11:58] cách làm nó sẽ tiện hơn địa là nó không
[01:12:02] áp dụng được thích cái ở trong Model
[01:12:04] giống như hôm trước mình làm nữa nếu
[01:12:06] mình làm hiện nhiều và đúng ạ
[01:12:08] Cái này nó hơi khó hiểu một tí nhưng mà
[01:12:11] khi mà xanh Ok buổi sau tôi hướng dẫn bé
[01:12:14] ông xã Ok thì cái đoạn này sẽ gọn hơn
[01:12:16] gọn hơn khá nhiều đây tôi sẽ tạm Xóa
[01:12:19] những cái đoạn này đi này nó sẽ viết lại
[01:12:21] theo cậu đúng kiểu dạng ngay trong đó
[01:12:22] không xem nhé à
[01:12:26] anh gửi tin nhắn
[01:12:36] gì này cái em đã in sơ về đúng
[01:12:41] vợ Totti Story Of em sẽ mất trước kiểu
[01:12:46] kia một cái lớp Index này
[01:12:49] ở mặt đất này
[01:12:51] I love stoned lưu lại ở đây đôla tên
[01:12:56] truyền RT là đây này tiếp theo
[01:13:00] khi edit đúng không
[01:13:02] à à
[01:13:03] ừ ừ
[01:13:14] Ừ
[01:13:15] thôi chỉ cần chuyển mã về thôi ở đây
[01:13:18] mình sẽ Return đó là ít này à
[01:13:22] tôi
[01:13:23] lại edit một cái nào đó này
[01:13:26] ừ ừ
[01:13:39] v-app đê ê
[01:13:42] em chuyển mã này chuyển tên này
[01:13:46] à à
[01:13:55] em không cần trả về cái gì này
[01:13:58] à
[01:13:59] mà delay cũng thể lớp Delete đợi tôi một
[01:14:03] tí
[01:14:09] à à
[01:14:14] ở đó
[01:14:20] mình sẽ biến thành các fan trình kẹo kéo
[01:14:22] ngay nhá cách mình gọi nó để để tôi sang
[01:14:26] bên A controller
[01:14:27] lớp để làm lại trong mấy ông thì ông sẽ
[01:14:30] thấy nó sẽ kiểu cách gọi nó sẽ như nào
[01:14:32] đầu tiên nó báo lỗi mình sẽ sửa lại cái
[01:14:36] biển controller lớp một tí
[01:14:38] số bài gọi thằng lớp này chị sẽ có kết
[01:14:41] quả trở về bằng xe lại bên lớp nhé mình
[01:14:44] sẽ có lớp Index Gọi Love mien Bac ngay
[01:14:47] để trả về cái thông tin kết quả nha à Là
[01:14:51] được nó sẽ như nhau
[01:14:53] a tiếp theo bên này crash
[01:15:01] tên này đúng không gọi cho anh này sau
[01:15:04] đó thì mình sẽ gọi đến cái Plus to này
[01:15:08] chuyển đưa tên vào như thế này là sau
[01:15:10] theo tôi thêm lại cho mấy ông Mày lập
[01:15:13] trình
[01:15:15] ăn thêm này
[01:15:17] đó tôi thử xem lại nha
[01:15:22] do đó nếu thêm đúng không
[01:15:31] anh
[01:15:32] em Em hiểu ý anh có thể sử dụng cái này
[01:15:35] ở bên ngoài nữa đúng không
[01:15:38] ở hướng bên ngoài ngay đúng không ạ sau
[01:15:40] đó bên trong này sự xô bồ không
[01:15:43] để em thử luôn nhé
[01:15:46] anh em em chưa Rủ em chưa thử thử xem
[01:15:49] nha Đây lớp
[01:15:51] ạ Bây giờ mình sẽ có lớp edit này
[01:15:55] thì
[01:15:56] mình sẽ có đôla x bằng lớp edit truyền
[01:16:00] mã vào trong máy
[01:16:02] đúng nhỉ
[01:16:05] Ừ đúng rồi đúng không ạ
[01:16:13] sữa này đó nó sẽ ra được đúng không em
[01:16:17] thử đổi nó cả lớp đi này em đổ nha tấm
[01:16:21] này ra ngoài đúng không ạ
[01:16:23] ạ sau đây em sẽ lâu bồ
[01:16:38] được nghỉ hơi dị
[01:16:39] chợ hoa dại quá đấy ok
[01:16:43] Ừ nếu thấy kiểu Đây cái này cho tiện hầm
[01:16:46] tí thôi
[01:16:48] anh như thế Mình có thể đóng nó kết nối
[01:16:51] lại được sau hết toàn bộ mày cái thằng
[01:16:53] này mình thể đóng cái nồi đấy
[01:16:55] ở nhóm nhạc không không không không được
[01:16:57] không được dọn hàng mua đồ này sớm mình
[01:17:01] gọi mua đồ này Sao mình gọi cho này mình
[01:17:03] không đóng được mình vẫn phải đau một
[01:17:05] bên trong vẫn đóng ở bên trong cái phần
[01:17:07] trên nó hợp lý hơn
[01:17:09] khi đóng đóng này trở về đội ích này con
[01:17:13] mẹ Ok rồi Tiếp theo vừa update cái này
[01:17:18] sẽ update này
[01:17:20] khi
[01:17:25] anh hiểu update này à
[01:17:29] ở đó ok rồi này tiếp theo lớp Delete thì
[01:17:34] sẽ copy cái này đổi Delete này à
[01:17:38] Em chỉ cần truyền mã này à
[01:17:46] mấy ông thấy cái vừa rồi nó hơi bị loạn
[01:17:49] một tí đúng bởi vì tôi bắt chước cái hôm
[01:17:52] trước để làm cái 10 xe Opa mbcc od01 bạc
[01:17:57] Ừ thì nó không cần nó chỉ cần suy cây
[01:18:00] đơn giản là cả thằng bến container ở
[01:18:02] phòng mua đồ thôi nhưng hôm nay bởi vì
[01:18:04] nếu không thấy đã sang bên sinh viên thì
[01:18:07] nó có thể gọi lại cái đùa lại cái thằng
[01:18:09] ở bên lớp thế nào chắc chắn tôi phải tạo
[01:18:12] hàm cả ngày để mà gọi đến Hàm đấy nó mới
[01:18:15] được chứ nếu mà xích cây Thôi cậu trên
[01:18:17] thì nó sẽ không được đấy tôi phải làm
[01:18:20] hơi bị loạn ở một tí
[01:18:22] Ừ nhưng mà ông thầy hôm nay có thể hơi
[01:18:24] khó hiểu một tí nhưng mà đến A để buổi
[01:18:28] sau khi mà xanh Ok hoàn toàn đấy thì mấy
[01:18:31] ông nội thấy toàn bộ Cái này không phải
[01:18:32] xích cây rồi em sẽ không phải suy cây
[01:18:34] cảnh này nó sẽ dễ hơn dễ hơn đoạn này
[01:18:36] nhiều rồi Hôm nay công nhận tôi khẳng
[01:18:39] định hôm nay hơi loạn một tí
[01:18:41] nhờ tí tôi đầy cốt lên mấy ông xe này
[01:18:44] mình cũng sẽ thấy không cũng không Không
[01:18:47] phải lỗi thế đâu
[01:18:49] AE aber Nói chung là tôi xong tôi làm
[01:18:52] lại được bên Cần bên lớp đúng không Tôi
[01:18:54] sẽ đổi lại sang bên sinh viên mà không
[01:18:56] xem nhé lỗi hết vậy chưa
[01:19:00] Xóa hết đi anh ta lại sang bên sinh viên
[01:19:02] nhé Mà tôi copy lại sang bên từ lớp 6
[01:19:05] đến sinh viên mấy ông sẽ được đấy
[01:19:08] Ừ thì tôi lại xóa đi
[01:19:10] Ừ tôi sẽ làm lại
[01:19:11] A Plus Anh Sinh viên vào xem nhé
[01:19:15] cô gái lại copy đấy à
[01:19:17] cô sinh viên à à
[01:19:24] dám làm cái gì đó dễ mà Anh chắc chắn nó
[01:19:26] phải hơi loạn làm gì đấy ta phải chấp
[01:19:28] nhận điều đấy ạ
[01:19:30] Ừ tôi sẽ copy hết này
[01:19:41] dàng gì đâu mà chẳng hiểu tôi đang làm
[01:19:43] gì đó copy đúng như cốt của thầy bảo
[01:19:46] U16 vẫn chạy Magic Ok
[01:19:52] ta lại này
[01:19:54] là con view nữa
[01:19:58] Em hãy sinh viên
[01:20:07] từng cái một nhá Ừ anh sinh viên hoa
[01:20:11] đội lớp hình sinh viên này ạ
[01:20:15] ở
[01:20:16] đầu tiên là mình cầm chỉ tên lớp và như
[01:20:19] vừa nãy tôi bảo đúng không cái lớp này à
[01:20:22] à à
[01:20:25] Dạ vâng Em có xem quả cốt ở anh trên
[01:20:28] công ty đúng không chẳng ai hiểu
[01:20:30] à tên lớp này
[01:20:33] thằng bộ đồ sinh viên này giống như vừa
[01:20:36] nãy tôi bảo thì mình sẽ lap doi đi sẽ
[01:20:38] lắp đẹp do đơn giản đi nhưng đây sẽ có
[01:20:41] lẽ trôi ư
[01:20:49] điều kiện vận sinh viên chấm này và alo
[01:20:54] chấm tên stof đó
[01:21:05] đây đây đôi khi các bạn Hiển thị Cái lỗi
[01:21:07] này lỗi này thì các bạn cứ cố tra cái
[01:21:10] dòng 17A ở đây rồi Các bạn không hiểu
[01:21:12] tại sao nó lại sai cái phối này bản chất
[01:21:15] là cái resort này nó không phải là cái
[01:21:17] mạng không
[01:21:19] forsberg nó không đúng nữa đây là nó
[01:21:21] không phù hợp cho thằng phối tức là xa
[01:21:24] nó vi rút này đang có vấn đề tất cả cái
[01:21:26] câu truy vấn các bạn đang say thì thôi
[01:21:30] tên lớp từng lớp về không Dạ
[01:21:33] các bạn lớp là hai tên nó phải ra nhỉ
[01:21:41] à À đúng rồi đúng rồi đấy vợ nó gợi ý
[01:21:44] sau đây phải mà lớp Đúng
[01:21:47] đó Ok tôi thêm một sinh viên mới này thì
[01:21:52] lúc thêm này tôi cần hiển thị toàn bộ
[01:21:54] danh sách lớp để mà thêm nó không ạ thì
[01:21:57] bây giờ tôi sẽ sửa bên này
[01:21:59] Ê thik White Cái thằng lớp này sau đó
[01:22:04] thì tôi để lớp Index này
[01:22:07] lại xong rồi Tôi đặt tên đây lớp hình
[01:22:10] chữ S cho hiệu là lớp số di động từ mày
[01:22:13] không nên chưa cho ai đâu nhé nên để
[01:22:15] tiếng Anh ở hợp lý hơn đấy thì ở đây tôi
[01:22:18] sẽ có lớp
[01:22:19] select options
[01:22:30] Ừ
[01:22:39] dùng cái cậu không dùng không dùng kiểu
[01:22:42] ngọc nhọn để không thể dùng cái này
[01:22:45] ốp trần
[01:22:47] à à
[01:22:49] a cho tôi sẽ làm cho phím tắt nhanh để
[01:22:52] mà Metro với lại nhanh nhìn lại khó chịu
[01:22:54] quá à
[01:22:56] à à
[01:23:08] đó đang có một lớp thôi Nếu sẽ ra như
[01:23:11] này ông ngoại ô
[01:23:14] Ừ
[01:23:15] nếu thấy là cách viết của tôi nó sẽ hiểu
[01:23:19] xem xem xem làm gì nhé cái viết của tôi
[01:23:21] bên hàng mua đồ này á Không không phải
[01:23:24] bên bên hàng controller này không thấy
[01:23:26] là rõ ràng mình kế thừa là được những
[01:23:28] cái hàm những cái hàm mình đã viết ở bên
[01:23:31] controller lớp bên lớp rồi đây cái Hàn
[01:23:34] lớp indec đúng không Mình lấy lại được
[01:23:36] cái cũ cái cách cách tối ưu của cốt hồi
[01:23:40] hồi mà các bạn làm đón một thì các bạn
[01:23:41] không tối được không sử dụng được cái cũ
[01:23:43] các bạn viết lại cái Cậu axwell viết lại
[01:23:45] có truy vấn các hư thứ và về sau giờ sự
[01:23:48] về sau mình thay đổi tên bảng ở trên cầu
[01:23:50] gì đó các bạn phải sửa rất nhiều file
[01:23:52] đúng không Mình không mờ nên làm thế
[01:23:54] mình lên về sau tôi sẽ hướng dẫn và mấy
[01:23:57] ông mấy ông sẽ phải băn khoăn luôn băn
[01:23:59] khoăn những cái điều này đó là khi mà về
[01:24:01] sau mà thay đổi tên bảng 2 tên cột thì
[01:24:04] mới ông Hạn chế sử ấy nó có thể thì làm
[01:24:07] cách nào để mà hạn chế sửa khi đó ngoại
[01:24:10] tên bảng tên một thứ gì đó Cái bản rồi
[01:24:13] Ra ít khi mà đổi nhưng mà cũng có thể
[01:24:15] lấy ví dụ thêm cột mới các từ thứ thì
[01:24:18] mới ông sửa như thế nào để cho ít nhất
[01:24:20] có thể Cái đấy bé là mục tiêu của cái mô
[01:24:23] hình nó ra đời mô hình càng chuyên
[01:24:25] nghiệp càng nâng cao thì nó sẽ cậu sẽ
[01:24:27] cần tối ưu các bạn đỡ phải sửa cốt khi
[01:24:30] mà có thay đổi mỗi gì đó
[01:24:32] A và lẫn cả các bạn copy paste kiểu
[01:24:35] ngang cũng nhanh nếu mà các bạn chỉ làm
[01:24:38] tình năng giống nhau thì copy pate nó
[01:24:39] dẫn ngay nó chỉ ở thay đổi một tên bản
[01:24:42] trên cầu thôi khi sang khi sang razzil
[01:24:45] thì tôi sẽ hướng dẫn mày ông đòi đánh
[01:24:47] ngắn cực mỗi thằng mỗi khoanh chân có
[01:24:50] hai dòng nữa Song Hành
[01:25:01] mình không biết dùng tôi cái gì cả thông
[01:25:04] cảm hơi kén không biết dùng rồi đấy à
[01:25:08] ạ Bây giờ mình cấp mình sửa mình sửa bây
[01:25:12] giờ mình sẽ có cả chèn thêm cả Đợi tí ở
[01:25:16] đây Tôi phải chuyển thêm nêm và nó làm à
[01:25:18] lớp nữa
[01:25:19] mình chuyển đấy mà lớp này thì khi mình
[01:25:21] to Mình lưu lại mình sẽ truyền lại mã
[01:25:23] lớp ở trong này
[01:25:25] Đây là bạn lớp và đương nhiên đây mình
[01:25:29] chuyển thêm một cái biến là bạn lớp này
[01:25:31] à à
[01:25:40] Em
[01:25:47] buồng ạ
[01:25:50] cho hai thằng cùng một lớp
[01:25:52] có
[01:25:52] thêm
[01:25:54] không lên nữa không Không nên tại không
[01:25:58] lên Tại sao không đây xem nhé Insert mã
[01:26:02] lớp trong bài đúng rồi nhỉ store này gọi
[01:26:06] đến mà lớp mà lớp
[01:26:14] tải lại cái này đã ok ok
[01:26:16] mới phát nữa này
[01:26:30] ừ ừ
[01:26:40] control of sai đúng không ạ
[01:26:43] Đấy nếu mà ông không để mình cái đoạn
[01:26:46] này Thế nên vừa nãy tôi đang định bảo là
[01:26:49] tôi có thể chơi cậu cách này tôi sẽ chơi
[01:26:52] cái kiểu vãi chưởng ngay
[01:27:00] em không đi ấy Nó nó cái cái xin nó vừa
[01:27:04] rồi ở nhảy trên controller lớp nên hay
[01:27:06] là nó không không lên được Wow phát nợ
[01:27:08] này à
[01:27:11] Ừ tao về câu trả lời sinh viên này đó đồ
[01:27:14] rồi
[01:27:16] Khi mà chắc chắn được rồi thì mình có
[01:27:18] thể điều hướng quay về đúng không sẽ
[01:27:20] điều hướng quay về
[01:27:22] à à
[01:27:24] anh Hải Tặc
[01:27:26] mấy ngày Delete Delete thì nhanh họ
[01:27:29] Delete thì thà chẳng giống vào nào Ngoại
[01:27:32] bên mình sửa nữa
[01:27:34] đã sửa thì mình sẽ
[01:27:38] thì mình sẽ lại phải truyền lãi Cái
[01:27:40] thằng à lớp Index ở bên sửa
[01:27:44] á nhon nó lợi ích
[01:27:46] cho tôi sẽ copy cái bên này đi
[01:27:49] vào bên lớp edit
[01:27:52] này mà tôi sẽ
[01:27:56] anh đi xe đây
[01:27:59] pp ở đây này ít
[01:28:03] đồ lớp tại Mã anh bằng bằng bằng R = R
[01:28:09] vật chất mà lớp
[01:28:23] à à
[01:28:24] em sợ gì nhiều gì ở site
[01:28:27] có con ếch con ếch
[01:28:29] I had it
[01:28:42] này lỗi rồi
[01:28:48] không bị lỗi
[01:28:49] chứ nhỉ
[01:29:07] chồng mình sẽ không khai bảo logo sẽ
[01:29:09] không lỗi
[01:29:11] em
[01:29:12] bị lỗi biến kinect lòng ba à Nó đi quay
[01:29:17] lại hay Thái cùng đi có ai à
[01:29:21] A gọi tôi sẽ đổi hay Wendy
[01:29:24] hai công ty vợ sao ạ
[01:29:31] ok
[01:29:33] 02 tháng củ rồi có ai thằng con ếch nên
[01:29:36] này ra thoại khai báo 2 phát
[01:29:38] xong trận này sau đó hai phát
[01:29:41] hoặc là mình có thể kiểm tra ngay trong
[01:29:43] fashion là và phân sinh này tồn tại hay
[01:29:46] chưa Nếu mà nếu có tồn tại rồi không cần
[01:29:48] phải khai báo Lại Văn Sâm nữa cũng được
[01:29:52] ở thời loạn không sao xanh Ok mẹ dạy
[01:29:56] ngon cá MC là lại bắt đầu thời đoạn đấy
[01:29:59] Ờ ok ở đây sẽ có lợi bu bu
[01:30:06] à à
[01:30:07] tử vi vu nằm Download Woa bị vụ
[01:30:11] s7s lỗi bởi vì à mình mình phải ở trong
[01:30:16] thì mình phải là biển trỗi mà mình phải
[01:30:20] Escape cái cái dấu nháy nó mới không
[01:30:24] biết anh Trỗi p phét ở lỗi này à
[01:30:33] nghỉ mà tại sao nhẹ nhàng controller lớp
[01:30:36] này tôi sẽ sai Ừ ừ
[01:30:38] bên đợi tỷ lệ gì đây này phải sinh viên
[01:30:43] đúng không ạ
[01:30:50] trà sữa này
[01:30:52] do đó nếu mà vừa rồi không sửa được tên
[01:30:56] lớp đâu vì vừa rồi là mình chuyển mã lớp
[01:30:59] xanh này sinh viên khi mẹ edit mình lấy
[01:31:03] mỗi ạ
[01:31:04] AE AE update thiếu mình sẽ phải lấy làm
[01:31:08] à lớp xanh nữa mà lớp này
[01:31:12] nếu sẽ thấy có nhược điểm đây là có bao
[01:31:16] nhiêu cột tôi là khẳng khai báo bấy
[01:31:18] nhiêu ở đây nó rất là dài dòng nóng bọn
[01:31:20] mày không thấy không có bao nhiêu bao
[01:31:23] nhiêu thương rồi khai bởi nhiều đây
[01:31:24] những tâm đến xanh rosler mày cũng sẽ
[01:31:27] không phải làm cái tình trạng này nữa sẽ
[01:31:29] làm mấy ông tối ưu rất nhiều cái đoạn
[01:31:31] này là nó sẽ không bắt ông phải ghi lại
[01:31:34] câu SQL này mấy ông truyền bao nhiêu và
[01:31:38] nó sẽ cập nhật bấy nhiêu cho mấy ông ở
[01:31:40] chỗ nào sang bên đấy thôi mình thấy cho
[01:31:42] sức mạnh của Uyên Quốc nó như thế nào
[01:31:44] vẫn làm kiểu rất là nông dân hiểu Có bao
[01:31:48] nhiêu phải điền đầy nhiều hơi khó chịu
[01:31:49] gì chị đã có sửa đổi tên đổi lớp này nó
[01:31:55] rồi đó đấy đầy đủ tính năng thêm sữa xóa
[01:31:58] bột dài vãi chưởng Nếu bây giờ tình ra
[01:32:00] khá là dài đấy nhưng mà tính ra là
[01:32:03] nó sẽ nhỏ gọn theo kiểu là mấy ông bây
[01:32:07] giờ thêm những cái bảng mới nữa thì mới
[01:32:09] ông chỉ cần copy những copy cả thư mục
[01:32:12] cả những cái file con này thôi
[01:32:14] Rồi mấy ông chỉ cần giống như tôi bảo
[01:32:17] cân cho Thái đổi để một cách để một cách
[01:32:20] thôi nha mấy ông có thể tổng nghệ tổng
[01:32:24] cái tên bảng này ra ngoài sợ mấy ông sẽ
[01:32:26] chỉnh sửa tên bạn rồi còn gì thay đổi cả
[01:32:29] Đấy là một cách
[01:32:30] A và nhưng mà Mấy ông không cho mẹ nghĩ
[01:32:34] việc tối với làm đâu về xanh cái đồ ăn
[01:32:36] là xanh buổi sau tôi sẽ đập hết toàn bộ
[01:32:40] về bạn ơi đi mấy ông có thể hôm nay thuế
[01:32:41] hơi khó điểm đi hôm nay khó hiểu thật
[01:32:44] khỏe hơi nữa thì hôm sau rồi cũng sẽ đập
[01:32:47] đi để tôi lại là đại hội của mở Oppa cho
[01:32:50] mấy ông
[01:32:51] nghe mấy ông học hôm nay chị biết qua về
[01:32:54] thứ nhất là khi m với xe
[01:32:57] a sails 2 bảng thì nó sẽ khá lằng nhằng
[01:33:00] hơn ở điểm mà nó sẽ phải tách riêng ra
[01:33:04] gọi thằng Model của thằng khác rồi gọi
[01:33:07] nhún Hàn đã như thế này đúng không ạ Nếu
[01:33:08] không phải nhớ điều này đây một điều đầu
[01:33:11] tiên cần nhớ lắm Nếu mày nhớ điều này đó
[01:33:13] là gọi thằng mua đồ thằng khác và gọi
[01:33:15] đến Hàm cả các đồ hoạ để mà buổi ông sau
[01:33:19] tôi sẽ làm như khẩu hướng đối tượng là
[01:33:21] sẽ cũng gọi mua đồ khác cũng gọi đến Hàm
[01:33:24] cả các đúng như thế này như hôm nay luôn
[01:33:26] nhưng theo dạng nào tiểu đối tượng thì
[01:33:30] nó sẽ như nào thì nó sẽ theo kiểu đối
[01:33:32] tượng rồi
[01:33:34] anh nói trong buổi ông sao sẽ quan trọng
[01:33:36] hơn bữa mày nên bộ của mày mấy ông thấy
[01:33:38] là tôi dậy nó hơi bị ạ lại phải dùng tốt
[01:33:42] nhất gừng cũng đúng vì tôi không hẳn ở
[01:33:44] chuyên cái này từ lâu lắm rồi Không động
[01:33:46] vào cái này nói thật là như thế bởi vì
[01:33:48] đi làm thì chắc chắn tôi không động cái
[01:33:50] này nữa đi làm đi Ở nhà lắm không ai làm
[01:33:53] nên Cổ Phần Nông dân kiểu này cả nên mấy
[01:33:55] ông thấy có thể ngoài Tại sao anh ấy kêu
[01:33:58] mấy năm kinh nghiệm ở làm cái đoạn này
[01:34:00] trông chán đấy Cá thứ bởi vì đi làm một
[01:34:03] Tôi không động vào cái này nên lên là
[01:34:06] tôi đang dạy cho mấy ông chỉ ở mức tương
[01:34:08] đối để không biết qua biết qua nhé nó
[01:34:11] cũng không cần phải hiểu sâu cái này bởi
[01:34:13] vì hôm sau Rửa thì cũng
[01:34:15] anh cũng đập đi xây lại và sẽ làm theo
[01:34:18] kiểu tối ưu và nó chuyên nghiệp hơn cái
[01:34:21] này nó vẫn là nông dân nên là
[01:34:25] bởi lâu tôi không đọc Tôi nói thật như
[01:34:27] thế có nghỉ đi dạy hơn một năm nữa đoạn
[01:34:31] này có lâu lắm rồi có động vào đâu ạ
[01:34:34] Ừ tôi còn không lên à Tôi có bị một tính
[01:34:37] hơi bị sống Tí đó tôi sẽ không lên giáo
[01:34:39] án được à
[01:34:41] Ừ nhưng mà đến cái đoạn lelio thôi có
[01:34:43] giá đầy đủ rồi và tôi đang làm nữa mẹ sẽ
[01:34:46] sáng đoạn nào điều từ tôi tự tin hơn còn
[01:34:49] hôm nay thì tôi hơi tệ Tí xin lỗi các
[01:34:52] bạn
[01:34:52] à à
[01:34:54] từ hôm nay chị để cho biết thôi Mày chỉ
[01:34:57] biết qua về MC làm hai bạn như nào còn
[01:35:00] là buổi sau thì mình sẽ mới xe ốp thì
[01:35:04] lúc đầy nó mới ổn không Tí và
[01:35:09] khi tôi tôi nghĩa tôi sẽ dạy mới xe OB
[01:35:12] cũng lại một bảng trước đi Tôi sẽ xóa
[01:35:15] cho toàn bộ cốt này tôi là một bản trước
[01:35:17] thì cho mấy ông đỡ bị choáng sợ buổi sau
[01:35:19] nữa tôi sẽ làm cho hai bạn thôi buổi sau
[01:35:22] nữa tôi có thể cân nhắc xem à lại tiếp
[01:35:24] tục ôn lại hay là nhẹ xanh là gram đều
[01:35:28] ngã
[01:35:29] khi mà nhớ xanh yaourt thì chắc à Mà ông
[01:35:32] sẽ thấy nó nó làm cái gì đó khác biệt
[01:35:37] cốt nhàn hơn rất nhiều người tạo nhiều
[01:35:39] pha ngày nữa tạm một file 1 Hifi thôi à
[01:35:44] Anh
[01:35:45] Huy cho ca là tôi dậy cho bé ông tôi
[01:35:49] không chuẩn bị trước thì cũng làm tôi
[01:35:51] nghĩ ở thực ra nó có một tí hay có một
[01:35:55] tí Dở Những cái dở thì mới ông sẽ thấy à
[01:35:57] đấy tốt cho bảo rồi có nghề ông ấy sẽ cả
[01:36:00] báo sẽ nghĩ là thầy này đểu không học
[01:36:04] nữa họ bị nản họ nghĩa khó quá không nữa
[01:36:06] Nhưng nếu mà mày ông Nghĩa hướng
[01:36:09] tích cực một tí giống như ông keo vào
[01:36:12] bảo để học cách của một người
[01:36:14] có một người có ký hiệu Nội đi Bắc giải
[01:36:17] quyết vấn đề khi mà gặp một cái bớt thì
[01:36:19] sẽ giải quyết như thế nào bởi vì thực tế
[01:36:22] là các bạn đi làm các bạn sẽ có lúc gặp
[01:36:24] bất Thôi thì là chuyển nghiệp ấy không
[01:36:26] kiên nghiệp chữ nghiệp thì không nói chữ
[01:36:29] nghiệp thì sẽ không ngờ gặp vớ vẩn ngoại
[01:36:32] các bạn sẽ gặp những cái vấn đề gì đó
[01:36:33] thì cách giải quyết
[01:36:35] tư vấn đề các bạn như thế nào các bạn
[01:36:37] tốn hàng giờ thì các bạn cầu nguyện nó
[01:36:40] chạy đúng không các bạn sẽ giải quyết
[01:36:42] cái cái đầy Nói như nào
[01:36:45] 3 bài tập bài tập thì tôi nghĩ là chưa
[01:36:48] bài tập gì cả đâu Tôi nghĩ là mấy buổi
[01:36:51] này nếu không chỉ cần xem lại này để
[01:36:52] hiểu Đã mày cũng làm lại Nó là một cái
[01:36:55] bài tập rồi còn à Buổi
[01:36:59] Chắc là khi mà xanh.rar thôi sẽ bắt đầu
[01:37:04] bắt mấy ông làm xem thêm sửa xóa một cái
[01:37:07] gì đó rồi dần dần Sang Woo cũng bắt đầu
[01:37:10] cũng chuẩn bị nhảy sang đồ ăn Đấy mẹ nó
[01:37:12] cũng sẵn sàng đi xăm xắp lại thêm một
[01:37:15] cái đồ nữa đấy đồ ăn hai mấy ông nghĩ đề
[01:37:18] tài trước đi à Ừ đúng rồi anh kiểu gì
[01:37:22] kiểu gì chẳng có bất
[01:37:24] trên công ty em tệ hơn nhiều nước luôn
[01:37:27] mỗi ngày làm xong một tính năng mỗi ngày
[01:37:30] tao cho con bậc II
[01:37:33] Ừ cái buổi hôm nay được à Không hẳn là
[01:37:36] suôn sẻ lắm chỉ ra vẫn vẫn ra được kết
[01:37:39] quả gì đó Nếu mấy ông xem thì ông xe mà
[01:37:42] đó để thì được thì
[01:38:03] ở đây tôi sẽ đẩy lên link ít nhé sẽ làm
[01:38:06] ở với xe
[01:38:07] i-sound hai bạn ạ
[01:38:12] sự nghiệp
[01:38:25] tôi nghĩa mày ông choáng trở không cần
[01:38:27] phải học thêm gì nữa
[01:38:29] em xấu nhỉ chúng ta tặng kết thúc đấy
[01:38:32] thôi bạn Chào mấy ông nha
[01:38:40] à à
