# Lập trình Web cơ bản - Buổi 24 - PHP - Đặt hàng

- Video ID: `yndPkfUMozI`
- URL: https://www.youtube.com/watch?v=yndPkfUMozI
- Published: 2021-12-22
- Duration: 1h 56m 50s (7010s)
- Language: vi
- Subtitle source: auto
- Kind: live

## Transcript

[00:00:00] à à
[00:00:11] anh alo chào các
[00:00:16] à à
[00:00:27] anh alo Chào bạn
[00:00:30] rõ hết cỡ chưa
[00:00:33] tắt truyện I
[00:00:40] chú ý Hôm hôm nay thì chắc là do bạn
[00:00:42] thấy cái tựa đề rồi ông ạ nay mình sẽ
[00:00:44] học về đặt Hà hôm trước và hôm trước
[00:00:48] mình học với giỏ hàng rồi không ăn mình
[00:00:50] sẽ học về kẻo khi mà ở nốt đặt hàng thì
[00:00:52] nó bản chất là mình sẽ lưu lại những cái
[00:00:55] gì thì sẽ xử lý như thế nào thì mình
[00:00:58] không làm như mình đã nói là các bạn
[00:01:00] chưa cần làm vụ thanh toán nhau ở phải
[00:01:03] nhập thẻ thanh toán qua mạng thanh toán
[00:01:05] qua thẻ ngân hàng hay liên kết cái gì đó
[00:01:08] bởi vì mình
[00:01:10] chưa Con Biết điều đấy Và và cái đấy là
[00:01:13] bạn sẽ rồi mẹ thằng thứ ba nó sẽ cung
[00:01:16] cấp thư viện cho mình để mình là nếu mà
[00:01:18] đương nhiên là cũng phải đòi hỏi được là
[00:01:20] mình phải đăng ký anh em nhiều cái để mà
[00:01:24] cậu xác thực cho nó chứ Không chuyện này
[00:01:26] được các bạn có một cái thẻ đấy cứ khách
[00:01:30] hàng nhập và với khách hàng mất tiền với
[00:01:31] Google được đúng ạ
[00:01:33] Ê chúng mày Cái đèn nó rất là lằng nhằng
[00:01:36] nên mình sẽ không dạy các bạn ít nhất là
[00:01:38] ở cơ bản không ạ ạ
[00:01:42] ở nhà bây giờ thì tranh thủ tâm sự trước
[00:01:45] đã nhỉ em chụp ở đây tôi sẽ có hại Hôm
[00:01:49] nay tôi sẽ có hai cái Linh để mấy ông có
[00:01:50] thể xem một cái là Em sắp ta như vậy
[00:01:55] Ngân sách tăng
[00:01:57] à à
[00:02:00] Em sắp anh thì à
[00:02:06] hình ảnh tượng cho con gái ông xem
[00:02:10] à à
[00:02:12] ừ ừ
[00:02:16] are you tube nó đáng sợ YouTube đánh bản
[00:02:20] quyền âm thanh nữa chúng ta chuyển qua
[00:02:22] xem phim này em có bị gì không
[00:02:25] Ừ chắc không dám đâu
[00:02:31] à à
[00:03:31] ừ ừ
[00:04:31] ờ ờ
[00:05:31] anh ạ
[00:06:31] hi
[00:06:56] ceri share something happened Today so
[00:07:00] wait and see the basic tạo lập những
[00:07:04] protein đến bệnh viện để giao simpler
[00:07:08] syntax
[00:07:08] to use of prisoners and life Happy
[00:07:13] không lại tham gia cuộc sống ở
[00:07:20] [âm nhạc]
[00:07:23] a
[00:07:27] story Vinh à
[00:07:34] à à
[00:07:36] em
[00:07:36] vừa rồi Các bạn xem có video các bạn
[00:07:40] thấy đại ý của cái video ấy Thực ra nó
[00:07:42] nó đã có trong tiêu đề rồi mà nói về
[00:07:44] việc bỏ cuộc hay không
[00:07:46] Ừ thật ra thì À
[00:07:49] cái này tiện thể mình cho xem luôn cả
[00:07:52] cái bài ở dưới nữa trước thì mình nói
[00:07:59] con
[00:08:00] gà Các bạn cũng chỉ cần đọc tựa đề này
[00:08:03] được rồi Không cần đọc thì đọc tiêu đề
[00:08:05] và tóm tắt thôi ông ạ
[00:08:09] em đã từng có lúc em uống 71 viên thuốc
[00:08:12] một ngày nhưng vẫn cố gắng làm việc để
[00:08:15] đủ tiền lọ lo cho gia đình em cảm thấy
[00:08:18] may mắn khi sinh ra với khối khối tài
[00:08:21] sản vô giá là hai bàn tay trắng Nếu nó
[00:08:24] mà em không bờ sợ khó khăn thử thách
[00:08:25] trước mắt
[00:08:26] Âm Nhạc
[00:08:29] Ừ hai cái này mình muốn nói đó là
[00:08:32] áo kiểu thực sự thì khi mà con người bị
[00:08:35] đẩy xuống đến cuối cùng như thế Một là
[00:08:38] chúng ta sẽ bỏ qua hay là người chúng ta
[00:08:41] không có gì để mất cả mình chúng ta vẫn
[00:08:43] tiếp tục chúng ta thiếu duy nhất chúng
[00:08:45] ta đang có lúc đấy chắc chắn là trẻ hai
[00:08:48] Phần Lan trạng hai bàn tay trắng anh đấy
[00:08:50] người khác nhìn thấy nó là như thế thì
[00:08:52] ra chúng ta còn cả hoài bão nữa cái hoài
[00:08:55] bão khi mà
[00:08:57] sau khi mà chúng ta bắt đầu
[00:09:00] so với việc ở khi mà chúng ta vỡ bị đẩy
[00:09:03] xuống sùng bái như thế Bị tất cả những
[00:09:07] cái người thành công người ta chê bai
[00:09:08] cái gì đó
[00:09:10] anh không ạ
[00:09:11] Mà cả thế giới quay lại quay lại quay
[00:09:16] lưng với mình hiểu gì hết
[00:09:18] khi mà chúng ta vẫn cố gắng có thể có
[00:09:22] nhiều người sẽ bảo cái cảnh bảo các bạn
[00:09:25] là bảo thủ chắc chắn bởi vì không nghe
[00:09:28] ai cả thì có thì nó là bọn ngủ nhưng mà
[00:09:31] khi mà các bạn chứng minh được và họ sai
[00:09:33] và mình đúng ấy
[00:09:34] Ừ thì cảm giác đấy thì mình tin à cũng
[00:09:37] sẽ rất là sướng
[00:09:39] A và Bởi bởi vì thôi à Không có một
[00:09:42] người nào có thể biết được là các bạn
[00:09:45] đang
[00:09:46] đang cảm thấy gì đảm đã trải qua tất cả
[00:09:49] những người nhìn gì đến được Đến Được
[00:09:52] đấy thời điểm đấy
[00:09:54] khi họ chỉ nhìn qua vẻ bề ngoài và họ
[00:09:57] đặt bạn hơn họ và đấy Và nghĩ rằng nhà ạ
[00:10:00] cái đấy khó quá Với họ họ trong trường
[00:10:03] hợp của họ không làm được nhưng họ đâu
[00:10:06] phải là bạn nên thành ra là
[00:10:09] bạn bạn vẫn phải tự quyết định là ngoạn
[00:10:12] mình Không khuyên được các bạn kiểu
[00:10:15] Ừ cố gắng cố gắng đến nỗi là kiểu không
[00:10:18] bao giờ bỏ cuộc
[00:10:20] Ừ cái từ không bao giờ bỏ cuộc nó hơi
[00:10:22] sai các bạn luôn mà nhìn nhận lại mình
[00:10:24] đê xem cái này có đáng hay không và vân
[00:10:27] vân vân Nếu mà các bạn mà bỏ cuộc một
[00:10:30] cách dễ dàng thì các bạn sẽ không ngờ
[00:10:33] Đạt đúng cái gì to tát cả cũng như là
[00:10:36] các bạn vì sau sẽ ân hận tại sao mình
[00:10:39] lại bỏ cuộc dễ dàng thế nó ngoạn các bạn
[00:10:42] gần như ở toàn bộ những cái ân hận về
[00:10:45] sau đều xuất phát được việc là các bạn
[00:10:48] đã bỏ lỡ cái điều gì đã không làm điều
[00:10:51] gì trong phải các bạn đã làm điều gì Các
[00:10:54] bạn đã làm điều gì Các bạn ân hận không
[00:10:56] bao giờ ân hận bằng kìa các bạn không
[00:10:57] làm gì
[00:10:58] Ừ cái đấy là cái mình muốn nói
[00:11:01] à thực ra thì có nhiều bạn mà Ôi anh ơi
[00:11:04] vẫn vờ vãi anh lại cái lý thuyết suông
[00:11:06] ấy kia người nói đạo lý Xưa nay sống như
[00:11:09] cái cái gì đó đúng ạ Nhưng thực tế thì
[00:11:13] cái đây anh cũng là chính là trải nghiệm
[00:11:14] của chính mình mày không nói là bây giờ
[00:11:16] mình thành công sẽ sẵn rồi cho dù kể cả
[00:11:19] lương nghìn đô trong nữa thì đường hẹn
[00:11:22] mọi thứ bây giờ làm như mình nói được ra
[00:11:25] nó cũng chẳng nghĩa gì cả nhưng mà khi
[00:11:28] mà mình so sánh mình với bản thân so với
[00:11:30] quá khứ khi mình không gì trong tay khi
[00:11:32] mà mình không có nổi bạn bè theo kiểu
[00:11:35] lại nói chuyện chẳng ai nghe chẳng hạn
[00:11:38] đấy bây giờ ý sao có hiện tại đang có 40
[00:11:41] Ông đang ngồi nghe tôi phải ngồi nghe
[00:11:43] tôi hay vì hồi để trả cho anh nghe tôi
[00:11:45] cả đấy Chẳng ai muốn nọ tiếp chuyện với
[00:11:48] mình a real mình nha màu sắc mình nói
[00:11:51] chuyện chán mình không Mình nghèo mình
[00:11:54] mình hiểu đủ thứ vẫn còn Vân
[00:11:59] thì biết là ít ra ở chắc chắn của tôi
[00:12:02] rồi khác xưa khá nhiều nếu các bạn đặc
[00:12:05] biệt là bạn thân của tôi trong nữa
[00:12:08] Nó cứ mỗi 15 nó có anh lại nhìn tôi thì
[00:12:12] nó lại thấy à Ôi sao mày thay đổi như
[00:12:14] thế không phải thay đổi về bé ngoài nếu
[00:12:17] mà ông nào mà theo dõi tôi ở trên kênh
[00:12:20] Facebook của tôi rảnh tôi so với ngày
[00:12:23] năm xưa gần như các bạn báo của anh sao
[00:12:25] trong anh vẫn vẫn thế chẳng khác gì
[00:12:27] trong vẫn vẫn trẻ con như thế này nhưng
[00:12:31] mà em còn nói về việc làm
[00:12:35] sự thay đổi theo kiểu là
[00:12:37] sự nghiệp hay Vân Vân tạm trữ mối tình
[00:12:41] nhưng cái này sẽ khác thì sẽ thấy cậu
[00:12:45] mình thay đổi một cách tích cực một cách
[00:12:49] tích cực mình không vừa đánh mất cái kệ
[00:12:52] con người bản chất riêng của mình là một
[00:12:55] hành kiểu dụ điển hình là một thằng ghét
[00:12:57] à
[00:12:59] a z về chuyện tiền bạc
[00:13:01] là một hành chính trực tiêu tiểu nghĩ gì
[00:13:04] nói đấy
[00:13:05] không số lệnh không kiểu nói chung cảm
[00:13:09] biến thiết bởi vì tính mạng tính mình
[00:13:11] thích kẹo cây ngay không sợ chết đường
[00:13:13] đấy
[00:13:15] thì tất cả những cái đèn mình vẫn giữ mà
[00:13:17] mình phát triển nó ở chung nhà mình có
[00:13:20] cái chính kiến riêng của mình và mình
[00:13:22] dần dần thể hiện được cái chính kiến của
[00:13:26] mình đã đúng cái kiểu như thế
[00:13:34] anh nói chung là đấy để những cái thứ
[00:13:37] mình muốn chia sẻ đó là việc là các bạn
[00:13:40] là không hẳn là nên bảo thủ nhưng mà
[00:13:44] cũng nên có cái chứng kiến và bảo vệ
[00:13:46] được nó cũng như là kiểu có một cái gì
[00:13:49] đó định hướng rõ ràng để mà làm một cái
[00:13:52] gì đó đúng không ạ Các Bạn Bè Mình mình
[00:13:55] phải khuyên thế phải vì thực sự tầm tuổi
[00:13:57] các bạn bây giờ các bạn đang ngồi xe hả
[00:13:59] mẹ thì chắc chắn là các bạn có thể cấp 3
[00:14:02] để học
[00:14:03] Em có phải bạn đi làm rồi có vài bạn đi
[00:14:06] làm rồi nhưng mà nói chung Những Người
[00:14:09] Bạn đang xem mình tin và phải đến nửa
[00:14:12] nửa phần là ý thế là đang vẫn mông lung
[00:14:16] ở tương lai bởi vì có nhiều ông vẫn còn
[00:14:19] đang ngồi học lập trình của tôi cơ bản
[00:14:21] tất cả mấy ông thực sự ạ có thể ra ngành
[00:14:24] khác muốn học này hoặc là thậm chí à Ông
[00:14:27] học trên trường nhưng chẳng hiểu gì cả
[00:14:29] nhưng không mới phải học ở đây tôi nói
[00:14:31] thẳng là như thế - có mấy ông hiểu dạng
[00:14:34] thích thể hiện vào học của tôi bóc mẽ
[00:14:36] thôi chứ Thì ông cũng rảnh đấy đúng ạ
[00:14:40] Ừ Thì
[00:14:42] Ừ thì tất cả những ông tôi chỉ khuyên đó
[00:14:45] là kiểu mấy ông phải đặt sẵn những cái
[00:14:47] mục tiêu luôn đặt ra mục tiêu và
[00:14:51] mục tiêu không cần vậy
[00:14:53] Mục tiêu cực kỳ khó có một mục tiêu rất
[00:14:57] dày và mục tiêu rất ngắn phải có những
[00:15:00] cái mô tiêu từng cột mốc như thế từ
[00:15:02] trước các bạn không để ngay lúc đầu các
[00:15:04] bạn chưa từng leo núi qua bạn đặt mục
[00:15:07] tiêu ở đỉnh Everest thì ông không bao
[00:15:10] giờ ông nghĩ đến giờ không đeo nó đâu
[00:15:11] ông ạ Ông đặt từ mục tiêu bé bé sau đó
[00:15:16] thì ông cứ Kiều cố gắng đạt được cái gì
[00:15:19] thì ông thỏa mãn nào đã và quan trọng
[00:15:21] tôi từng bảo là tôi có cách đó là tôi
[00:15:23] chọn có người đi cùng một là bạn bè hay
[00:15:27] là người yêu chồng ạ thì mình sẽ có động
[00:15:30] lực để mà cùng đạt đến mục tiêu lấy hơn
[00:15:33] hỗ trợ Ông đi một mình mà không được đi
[00:15:35] xa được
[00:15:43] à à
[00:15:45] cô bạn kia vào ngồi nghe mình tâm sự để
[00:15:48] giải trí thôi cũng được
[00:15:50] ạ bây giờ như thế thì có lẽ tôi dậy Đúng
[00:15:53] rồi tôi vào rồi thôi nhé nghĩ đó tôi
[00:15:55] đang định quá giờ mới đi tôi xin phép
[00:15:58] tâm sự em tí nhé
[00:16:00] em Dựng 10 phút mình
[00:16:04] à Mình mình đang nghĩ là mình sẽ phát
[00:16:08] triển ạ thực ra mình không ý định phát
[00:16:10] triển là kênh nha kênh trên như Facebook
[00:16:13] lúc nào đâu Em vừa nãy mình nghĩa là có
[00:16:15] khi mình sẽ tạm cái fanpage tên là gì
[00:16:18] cũng là gi ti NL ở trên Facebook Thực ra
[00:16:21] là có khá nhiều ông ấn gửi kết bạn tôi
[00:16:25] hỏi cái theo dõi tôi ở trên Facebook mà
[00:16:28] mếu không ai để ý là tôi đăng chẳng có
[00:16:30] tí thì liên quan đến cái dân công nghệ
[00:16:32] lắm không còn đang uống kiểu anh Mạnh
[00:16:35] Tuấn Anh Mẹ tuấn hưng ai đang điều rất
[00:16:37] nhiều cái mẹo về công nghệ chia sẻ và
[00:16:39] công nghệ đứng cả chuyện hại về công
[00:16:41] nghệ Còn tôi thì ít như thế cái trang cá
[00:16:44] nhân của tôi đúng nghĩa là trang cá nhân
[00:16:46] của tôi tôi thường hay đăng những cái
[00:16:48] thứ mà tôi để mong là sau này là ngày
[00:16:51] này năm sau tôi xem lại là chính chứ tôi
[00:16:54] không có đăng mấy cái công nghệ lắm Ê
[00:16:56] mấy ông sẽ bảo là
[00:16:58] chỉ sau một khoảng thời gian để không
[00:17:00] theo dõi tôi chắc là
[00:17:02] tại sao tao phải theo dõi cây xanh thì
[00:17:04] kia trong số chai như này rồi toàn đăng
[00:17:06] mấy cái tao không có tâm nghỉ Cứu Thế
[00:17:09] thì tôi đang định tôi sẽ tạo một cái
[00:17:11] fanpage cũng theo bị danh của tôi Trái
[00:17:14] tim và tôi sẽ thương ai chia sẻ những
[00:17:17] cái thứ mất cảm thấy hay ho lên đấy tiền
[00:17:19] hình à là cốt đoạn code nào hay đấy chứ
[00:17:22] xe những thực phẩm chứa tôi chia sẻ
[00:17:24] những cái tâm sự thôi ạ chia sẻ mấy cái
[00:17:26] và chim vân vân hoa cả
[00:17:29] anh nói chung những thứ tôi thấy hay
[00:17:32] thậm chí là cả Âm nhạc luôn tôi tôi
[00:17:35] Thỉnh thoảng tôi thích chia sẻ nhạc cực
[00:17:37] Tôi thích con người thích nghe nhạc Tôi
[00:17:39] sẽ chia sẻ là xinh bảo toàn bộ những cái
[00:17:41] thứ tôi thấy hay Tôi rất thích chia sẻ
[00:17:43] chia sẻ gần đây thì mấy ông có thể theo
[00:17:47] dõi cái đấy thì tôi nghĩ là ổn hơn cái
[00:17:49] tôi đang định sẽ tạo một cái fanpage
[00:17:51] kiểu như thế thật giết tôi là ví dụ tôi
[00:17:54] thích nhạc thể đoạn nhạc điện tử nạn tôi
[00:17:57] sẽ chia sẻ lên đấy thậm giữa ảnh gái
[00:17:58] xinh mà tôi thì xinh là đổi chia sẻ lên
[00:18:00] đây thậm chí là cả về zota là nặn Tôi
[00:18:03] đang thích một cái gì Họ nói Chúng tớ sẽ
[00:18:05] chia sẻ hết lên đấy để ở nhưng ông làm ở
[00:18:07] hợp gu của tôi kéo ra cùng chung giờ
[00:18:10] thích thì sẽ xem được một vài cái đúng
[00:18:12] không ạ Có nghĩa là thế khá hợp lý mà
[00:18:14] không ạ à
[00:18:17] Ê mày không thấy ổn không ạ Và thấy cá
[00:18:19] có nhiều người bạn lắm phát triển để mà
[00:18:21] nhiều người biết đến mình hơn ngoài ra
[00:18:24] phát triển có thể phát triển group Bởi
[00:18:25] vì nó có tương tác hai chiều nhưng mà
[00:18:27] tôi thực sự ở Tôi ghét chứ việc là tạo
[00:18:29] thêm group rồi là tên là kiểu nhóm Hồi
[00:18:33] trước tôi từng tạo cái nhóm là lớp học
[00:18:35] anh Long thì có rồi cho sinh viên của
[00:18:37] tôi nhưng mà chủ yếu tôi đăng lên đấy để
[00:18:39] mà tương tác với sinh viên của tôi cho
[00:18:41] cậu ra ngoài tập thôi nhưng mà tôi nghĩ
[00:18:43] bây giờ tôi bây hết sang fanpage thì hợp
[00:18:45] lý hơn được ra ở khi mà Hồi đấy tôi từng
[00:18:48] tạo lỗi các bạn kia sẵn rồi chia sẻ tự
[00:18:51] cái gì đấy cả gần như tôi tự đăng mà tôi
[00:18:54] tự đăng này tôi nghĩa rồi đang ở fanpage
[00:18:56] hơn cả đăng group nên là Ừ bây giờ tôi
[00:19:00] nghĩa tôi sẽ chuyển qua fanpage thôi à à
[00:19:02] À đúng rồi mà cái cuối cho mày không xem
[00:19:06] những cái thứ mà tôi thường anh xem trên
[00:19:08] YouTube Không hôm trước tôi lại Xem lại
[00:19:10] kể anh ra từ Phạm Anh đấy ờ ờ
[00:19:16] Ừ anh đẩy cũng bảo là kiểu có bóng video
[00:19:19] Anh ấy bảo là kéo có câu hỏi anh lấy họ
[00:19:23] rất hay cho Tí tôi sẽ đăng lên hỏi trên
[00:19:26] YouTube công ty gọi tâm sự Đó là
[00:19:31] các bạn hãy xem gì trước khi ngủ
[00:19:36] đó như thế này
[00:19:39] cùng ai hay vậy chưa yêu kẹo là nó sẽ họ
[00:19:42] được đá Chi ạ Con mở đa chiều nhưng ai
[00:19:46] cũng có thể trả lời được ngoại thì
[00:19:50] Ừ tí chiều cao là cái goose em của tôi
[00:19:52] tôi cho mấy ông Xe này mấy ông đôi khi
[00:19:55] là Mày có hợp với ông thể xem qua được
[00:19:56] đấy Cái đang gợi ý đây rồi nhưng tôi cho
[00:19:59] ông xem lịch sử của tôi thường này xem
[00:20:01] gì à
[00:20:04] Ừ để nó qua về mà con người tôi và thôi
[00:20:07] cả tội chia sẻ một vài kênh mà mọi người
[00:20:08] cũng có thể có cùng chung sở thích của
[00:20:11] tôi ra mà không ạ nhất là tôi xem chim
[00:20:13] sẻ đi nắng này để chết đấy nó ngoại tôi
[00:20:16] thường xem game moba thôi tiếp theo là
[00:20:19] tôi xem lại mấy cái video mà mình đã
[00:20:22] từng dậy xem ạ mình dậy đoạn đấy Có ổn
[00:20:25] hay chưa cũng nhờ xem lại câu hỏi các
[00:20:27] bạn để tổng hợp phải câu hỏi này thế
[00:20:29] theo tôi còn theo dõi kênh nha vật vờ
[00:20:31] studio vì kênh này về công nghệ Thực ra
[00:20:35] tôi không quan tâm hẳn về công nghệ ấm
[00:20:36] bởi vì công nghệ thay đổi liên tục thật
[00:20:38] là mang tiếng là dân công nghệ nhưng mà
[00:20:40] mình không phải thức đây có phải thứ mà
[00:20:43] tôi quan tâm đến cậu Chíp hay ở cái gì
[00:20:45] đó camera Tôi thấy thực sự bây giờ mấy
[00:20:49] cái đấy nó nó sẽ khác biệt nhau từng tí
[00:20:51] từng tí một mỗi năm nay thay đổi một tí
[00:20:52] thay vì cái kiểu tai thỏ biến thành nốt
[00:20:55] ruồi gì gió tôi không quan tâm được đấy
[00:20:57] một con Tâm cách người ta
[00:20:59] 3 cách người ta cậu thuyết chỉnh giới
[00:21:03] thiệu một cái sản phẩm mà mình vốn là
[00:21:05] mình không ấn tâm là họ vẫn chưa chỉnh
[00:21:07] hay như thế có mình có Xem Châu Tinh Trì
[00:21:10] hay mà Đấy thì khi thực sự thì mình học
[00:21:15] mình học cách nói chuyện đấy À đúng rồi
[00:21:17] nó có hình cái nữa chết hẳn rồi đấy tiếp
[00:21:20] theo mấy ông nên xem mấy ông Khi mà ngủ
[00:21:22] nên nghe nhạc à đừng đeo tai nghe nhạc
[00:21:25] nghe không tốt đâu khi các bạn nên kiểu
[00:21:28] Mở bài ca nhạc thư giãn không nổi thôi
[00:21:31] Hồi tôi thi đại học tôi còn mở nhạc
[00:21:33] opera rồi mày nghe nói là nó dễ tăng IQ
[00:21:36] gì đấy
[00:21:37] thế heo là tôi có xem yuta đúng ạ thì có
[00:21:40] cái anh Super Hiếu này gần đó xe và 23
[00:21:44] creative vn nữa thì mì anh đợi bình luận
[00:21:47] cả hai nước mình học được cách bình luận
[00:21:50] người ta ngoại không biết về sau tôi có
[00:21:52] định làm bình luận viên hay không nhưng
[00:21:54] mà thích cách người cách nói chuyện rồi
[00:21:56] đấy 22 a
[00:21:59] a tiếp theo đơn nhân baking soda bình
[00:22:01] thường thôi ông ạ Đây bạn này xin phép
[00:22:04] được
[00:22:05] và đấy đi cũng là vật vào này Minh xô
[00:22:08] này tại đại khái như thế này sau đó đi
[00:22:11] Nhạc này Thu Nga của tôi sẽ là ngạc của
[00:22:14] tôi khá là cũ Tôi từng nói Tôi có hủy
[00:22:16] rồi còn thích nghe những nhạc cũ tầm 90
[00:22:18] cậu
[00:22:20] 90 cả Việt Nam ở nước ngoài kiểu tầm đấy
[00:22:23] đương nhiên là cũng có nhà Điện tử tôi
[00:22:25] có nghe nhạc điện tử nhạc hiện đại Tôi
[00:22:27] Có nhưng mà ít hơn so với Nga cũ
[00:22:33] Có ai có nghe nhạc điện tử này có hư
[00:22:35] hướng Nghe nhạc này mới không ạ Còn bộ
[00:22:38] môn Tôi thích nữa là bộ môn Quốc cơ Quốc
[00:22:41] Ờ tôi thích 3 game nhưng mà chả ai đi xe
[00:22:44] bus game mà trên YouTube cả thì thể loại
[00:22:47] Walker của cơ thì
[00:22:49] các bạn thấy thời gian nó cũng có tính
[00:22:51] toán hack não tí và có một tí nhân vật
[00:22:53] tính thôi con người phá thích kiểu chỗ
[00:22:56] cái thứ gì đó mình không đoán được bởi
[00:22:58] vì à Tôi nghĩ nhiều Tôi thường ai đoán
[00:23:00] được ngoại tình huống
[00:23:02] và Quốc cơ gì cả các bạn đoán không ở
[00:23:05] hết rồi khác tình huống đây này nó hay
[00:23:07] đi
[00:23:09] em yêu heo từ nhân vật này chắc các bạn
[00:23:12] biết rồi nhân vật này cách chửi của anh
[00:23:15] đấy à Của ông đấy ông ạ bạn chú đại khái
[00:23:20] như hết thì
[00:23:21] chỉ của
[00:23:24] Ừ anh đợi cứ gọi anh ấy Chú ấy thì rất
[00:23:28] là hay chửi thông Thúy cười và cái cái
[00:23:32] cái cái chân like me này các bạn nên xem
[00:23:36] ở điểm mới thứ nhờ các bạn cải thiện
[00:23:37] tiếng Anh các bạn nghe được tiếng Anh
[00:23:39] thứ hai đó là các bạn sẽ ở
[00:23:45] Cho tôi xem những cái video này rất cảm
[00:23:47] động bởi vì đây là video chương trình
[00:23:51] thực tế ở bên Mỹ bên anh đỡ bất giác hơn
[00:23:55] bên Mỹ thì thì đều là những cái quán rất
[00:23:58] tồi tệ
[00:24:00] khi được Kiểu ông này đến ông ấy trở
[00:24:03] thay đổi thay đổi kể quan điểm người ta
[00:24:05] thay đổi cuộc sống về ra luôn tại tôi
[00:24:09] thấy kiểu giống như người thầy luôn Đấy
[00:24:10] thế là tôi cũng xem rất nhiều video cảm
[00:24:13] động của ông ai cậu khóc luôn đấy Kiểu
[00:24:17] ông ấy thay đổi được Kiểu số phận của
[00:24:20] nhiều người kiểu thế làm cho tôi toàn
[00:24:23] hiệu lực là tôi muốn cũng cũng muốn
[00:24:25] tương tự như thế
[00:24:28] về game game này Tôi thích ca game mày
[00:24:32] buổi không phải vì cái móng nghe mà ngủ
[00:24:33] gì ạ Tôi không thích thần thoại Hi Lạp
[00:24:38] em có mấy trăm other cái bộ phim thay
[00:24:40] đổi khá nhiều cái con người bản chất của
[00:24:43] tôi lại khác như thế và Ma Trận nữa Một
[00:24:45] Huyền Thoại
[00:24:48] ở công ty âm nhạc còn gì Thế cho các bạn
[00:24:51] xem đúng rồi đây kênh tôi xem game nữa
[00:24:55] thì tôi sẽ xem kênh mê game à tại kênh
[00:24:58] phân tích game những Nói chung là các
[00:25:00] bạn thấy nãy giờ ở tôi đều xe mà gần
[00:25:02] trưa Xem chủ yếu là nội dung là một con
[00:25:05] nói được ra tôi không chơi mấy game này
[00:25:06] đấy Kiểu thế số xe mà Bởi vì à
[00:25:09] anh nghe cách họ nói chuyện để mà tôi
[00:25:12] nói chuyện cải thiện dân nghe cách họ
[00:25:14] Phân tích đúng gridview thì gần đây tội
[00:25:17] xem việc rồi livewell là gần như
[00:25:21] anh đấy là cá nói chuyện rất hài hước
[00:25:23] nhà mang tính kiểu châm biếm cập nhà
[00:25:26] theo kiểu là giải trí Còn tôi xem mà tôi
[00:25:31] vẫn đang muốn xem thiên hướng về cái
[00:25:32] phân tích hơn nếu không hiểu ý thôi ông
[00:25:35] ạ Đã là đúng hiểu đủ lý do giải trí là
[00:25:39] có tí phân tích trong đấy có vui thì có
[00:25:41] nhưng phải có tí động não trong đấy cái
[00:25:43] rồi mình thích chứ tôi không ạ
[00:25:46] a cho tôi không thích kiểu dạng mà chỉ
[00:25:48] đơn giản giải trí
[00:25:51] Cho tôi chơi game Tôi cũng phải cần máy
[00:25:54] game kiểu na ná giống như cho ta này
[00:25:56] chẳng nhắn nó con gì trai hot là đế chế
[00:25:58] các kiểu thứ ở đây còn mọc phiện đã nghe
[00:26:02] nhạc Thấy sao rồi xem xem thì tôi xem
[00:26:04] thỉnh thoảng đón xem những cái điều nâng
[00:26:06] cao trình độ bản thân ơi này nóng đầy
[00:26:08] xót cho tôi mà cả hai cách
[00:26:10] để anh từ phạm tôi vừa nói đấy
[00:26:13] a monster morsi ôtô tuna nói trước đại
[00:26:18] thái hồi trước tôi tôi có theo dõi anh
[00:26:20] đấy và rồi tôi mới xe mình nhưng có cái
[00:26:22] phốt cho anh đấy vì vậy à
[00:26:24] Ừ Thật ra tôi đã từng nói Tôi không quan
[00:26:26] tâm 10 phút thì cả nó không quan tâm mà
[00:26:28] người đấy từng làm thận Thế đã làm đang
[00:26:31] làm abc.xyz cái gì tôi không quan tâm
[00:26:35] Không quan tâm đến việc cả anh ấy chia
[00:26:39] sẻ cái gì có về ô tô xe
[00:26:43] em lấy lại khá như thế Ok gửi sang
[00:26:52] à à
[00:26:55] Ừ ông kia spa nữ giờ Check Facebook bóc
[00:26:59] hết hai tuần mà đây tôi không biết chị
[00:27:03] mày không chưa Tôi có cài cái tiện ích
[00:27:05] là ở
[00:27:08] a web developer ngay để một phát check
[00:27:13] luôn toàn bộ cái checkbox Nếu mà ý ông
[00:27:15] kia hỏi là như thế
[00:27:17] Ừ để tôi thử ví dụ cho em nhé
[00:27:20] cho tôi Tôi vừa nãy tôi vừa dùng Xong để
[00:27:22] mà tôi lấy cho Ken mà a rapper này
[00:27:26] Có ai có cái tạo một tô canh mới này
[00:27:31] Có
[00:27:32] ai có cái toàn bộ trách box này đúng
[00:27:35] không ạ thì mùi các bạn ship bằng ra
[00:27:36] Swift để mà checkbox tích vào hai các
[00:27:39] bạn cài tiện ích nhà thôi à Không bấm
[00:27:41] nhầm đấy mình em ạ Các bạn tài tiện ích
[00:27:43] này xong rồi ấn vào form này check cho
[00:27:46] chết bóp xong mày đấy nhớ mẹ Ý bạn hỏi
[00:27:50] như thế
[00:27:52] anh
[00:27:53] đứng đây làm nữa đó Đương nhiên thực ra
[00:27:55] là không có một ai thực sự hoàn hảo cả
[00:27:57] Nói chung là cũng khó vấn đề đạo đức hay
[00:28:00] có sai lệch quá thì đúng ở không nên gen
[00:28:01] Còn nếu mà những cái mà họ giống như ở
[00:28:04] điển hình nhá Điền hình nhá Tôi đang dạy
[00:28:06] mấy ông về lập trình nó ngoạn cái thì
[00:28:09] khi mà tôi đang dậy ông bản thân tôi dậy
[00:28:12] vẫn ổn chứ ra nếu không cần quan tâm
[00:28:14] những cái đời sống cá nhân của tôi
[00:28:15] chương kiểu đó tôi có
[00:28:19] ABC sẽ gửi gió lời ca Không phải món Tâm
[00:28:23] Ừ đúng ạ reset khi mỏng mấy ông rạch
[00:28:27] giỏi về quan điểm đấy Giả sử là mấy ông
[00:28:28] còn ăn kỳ dị người ạ người tình thứ ba
[00:28:32] hay là người da đen Vân gì đó mà chính
[00:28:35] cánh người ấy lại dậy ông nghịch tự
[00:28:37] nhiên về sau mới biết được điều anh ạ
[00:28:39] anh không ạ kéo quần tôi tưởng từ trước
[00:28:43] nay ông ông con ngay ở em ạ Nhớ về hóa
[00:28:46] ông con gái à Ông tội vì thế tôi không
[00:28:48] nghe nữa tôi không em gái dậy trả lại
[00:28:50] thế không Cái cái đấy cái việc riêng của
[00:28:54] họ tôi không quan tâm đáng Nếu mày ra
[00:28:56] cho những cái vấn đề ra đương nhiên có
[00:28:58] những cái thứ mà nó hơi bị tiêu cực quá
[00:29:01] nên hình giống như à à
[00:29:03] cho ví dụ tôi con người yêu nước ạ Nếu
[00:29:06] mà có có
[00:29:08] diễn viên đóng bộ phim kiểu mà ông Hiếu
[00:29:12] cuốc đây đóng những bộ phim
[00:29:14] tài liệu về chính nước nhà kiểu thủybán
[00:29:19] lịch sử của nước nhà vì rất là nó tôi
[00:29:21] cũng lên rồi đấy nó phải như thế
[00:29:23] anh hoặc là có nghĩa vụ Donut cho mấy
[00:29:27] cái thần tượng Trung Quốc thì được tôi
[00:29:30] thấy cái đấy cái gì chị không phải chỉ
[00:29:33] thấy nó vẫn thôi nhưng mà tiền của họ mà
[00:29:37] tôi sẽ không phải bán được đây là chỉ
[00:29:39] phê phán vụ không ngờ xem phim thì bạn
[00:29:42] lịch sử nữa nha thì thôi I
[00:29:53] tự hào Tôi không biết thì ta tôi không
[00:29:56] xem rất nhiều cá đâu thì cả không nhiều
[00:29:58] thời gian để xem nhé Mấy ông có thể đề
[00:30:01] xuất tí nữa sẽ đọc hết nha Giờ tôi không
[00:30:03] nghệ vừa cho tôi sẽ trả lời câu hỏi đây
[00:30:06] đã sau đó thì tôi dạy học còn tất cả
[00:30:08] những cái bình luận của mấy ông thì ra
[00:30:10] để bữa sau nha À đấy thôi Đang định ghi
[00:30:12] nhiều bạn không biết được tôi sẽ phải
[00:30:14] ghi lại là à
[00:30:17] chị sẽ ghim lại để mấy bạn biết à
[00:30:22] ở mọi câu hỏi mà mình chưa kịp xem 2 trả
[00:30:28] lời thì mình sẽ tổng hợp lại và trả
[00:30:36] rồi ở của sao ạ
[00:30:42] chị
[00:30:43] Linh có họ họ
[00:30:46] cho
[00:30:48] tổng hợp
[00:30:51] đó à
[00:30:55] anh xóa mấy cái sau đó hỏi chấm đi này
[00:30:58] không cần này mấy ông chỉ cần quan tâm
[00:31:00] cái này thôi nó như thế này à
[00:31:07] anh làm sao mình chết hết sản phẩm khi
[00:31:09] mà mình cốt à À Ý bạn là hình như là
[00:31:14] đang nói về cái giỏ hàng đặt hàng đúng
[00:31:16] không
[00:31:17] Em làm theo kẹo Lộc khi đặt hàng các bạn
[00:31:20] kiểm tra xem ạ sản phẩm để hết về chưa
[00:31:23] Hay như nào nhỉ à
[00:31:26] thì các bạn hỏi câu hỏi ở nó quay cái
[00:31:30] vượt qua thứ tự này
[00:31:32] em coi bỏ cái Linh đi nhưng chắc chỉ cần
[00:31:35] nghe này
[00:31:45] à à
[00:31:51] ở bảng cái bảo đúng rồi là cái gì Đúng
[00:31:53] rồi nghỉ à Ê mày nhiều người đã hỏi bạn
[00:31:56] mà
[00:31:57] Ok nó cho vợ
[00:32:02] cho tôi tôi sẽ đi ý phần 1 câu hỏi sau
[00:32:05] đi không bị phân tâm áp không dậy được
[00:32:06] gì đâu
[00:32:09] khi có thư mục
[00:32:12] mà quên quên hỏi nó cái này nữa hay sao
[00:32:15] đấy nốt này nữa còn tiền thì nhất là có
[00:32:16] bạn hôm trước hỏi đó là các bạn đang làm
[00:32:19] việc theo nhóm nó không ạ thì việc dùng
[00:32:21] chung đang sân bay rồi Như thế nào là sự
[00:32:23] các bạn muốn tạo hẳn đã tới đây để mà
[00:32:26] các bạn dùng chung theo kiểu là các bạn
[00:32:28] đang sản phẩm vào trong cái database đấy
[00:32:31] thì người chưa nhận được bản chất cái
[00:32:32] đấy đứng yên mà ờ ờ
[00:32:35] khi bạn bắn chất Cái đấy là ấm chứ tao
[00:32:38] bây giờ nó phải công khai tất làm chuyện
[00:32:40] đó đẩy ra ngoài Nhưng đấy thường là để
[00:32:42] làm được điều này thì các bạn sẽ phải
[00:32:44] thuê hút sinh hoạt thêm cái thằng thứ ba
[00:32:46] mà nó miễn phí không mất tiền tùy tiền
[00:32:49] mà cho cả hai cùng kết nối vào nhưng mà
[00:32:52] ở quy mô như thế hiện tại hiện đại như
[00:32:55] bây giờ thì thực ra là các bạn chưa cần
[00:32:58] phải đến mức độ đấy hoặc là Thậm chí các
[00:33:00] bạn thuê cũng được mà miễn phí cũng được
[00:33:03] thuê mất tiền nó có tí động lực Hồi đấy
[00:33:05] tôi cũng thuê đấy có tính động lực kìa
[00:33:07] mỗi ngày cảm thấy mất 3.000 tiền gửi xe
[00:33:10] thấy thốn lắm trong 1 tháng 11 năm có
[00:33:13] thuê một triệu mà Đấy Tôi có động lực để
[00:33:16] ngày nào phải ngồi cốt có một cách nhờ
[00:33:19] nữa Mấy ông không muốn kiểu như thế thì
[00:33:21] mấy ông ạ
[00:33:22] Có thể tách riêng bậc có thể hai bạn cốt
[00:33:26] riêng debay ngoại chung cấu trúc là được
[00:33:30] Nhưng mà tao tao bây dữ liệu nó có thể
[00:33:32] không được nhau đi
[00:33:35] Ừ đúng rồi có thể miễn phí nó chết cho
[00:33:38] nó sẽ giới hạn một vài cái gì đó rồi
[00:33:39] Không ạ Lúc để ngon được
[00:33:44] Anh ở tiếp theo nhá Thực ra là hôm trước
[00:33:47] tôi tôi chấm cho mấy ông từ gan nó có
[00:33:51] một cái vấn đề nho nhỏ như thế này nó
[00:33:53] nhau ở thôi đó là từ ra các bạn ạ nhiều
[00:33:57] nhóm này nhóm yếu rồi không nói nhầm yếu
[00:33:59] thì nên nó giống hệt cái mà tôi đã hướng
[00:34:01] dẫn là quá đâu rồi nhờ vào những nhóm
[00:34:03] khá Tôi thấy thì ra mấy bạn đang hơi bị
[00:34:07] nạo thêm nhiều ra bay quá thì ra là như
[00:34:10] tôi nói là cơ bản thì các bạn không cần
[00:34:12] phải tạo quá nhiều như thế nhưng gần
[00:34:16] nhiều tôi không thấy có nhóm nào thực sự
[00:34:18] là làm ra tao bây theo đúng cái đề tài
[00:34:21] mà các bạn thì đã chọn mà các bạn làm
[00:34:23] theo kiểu làm thêm nhiều nó là cây ý của
[00:34:27] tôi đang muốn nói nó nhìn lại tôi thử cứ
[00:34:30] phải cho ví dụ mày ông dễ hình dung hơn
[00:34:32] không ạ thì là sửa các bạn làm à trang
[00:34:35] web bán về xe máy tính ở Lạnh thì cái
[00:34:39] bảng sản phẩm các bạn đúng không ạ mã
[00:34:41] sản phẩm các bạn thực ra là các bạn nếu
[00:34:44] Để ý kỹ ở trên bất kì cái trang máy tính
[00:34:46] nhà sự như là Trang Hà Nội công tơ
[00:34:50] tôi không quảng cáo xanh này đâu Thực ra
[00:34:52] tôi biết mũi trang này chẳng khám phá
[00:34:53] thôi em
[00:34:56] Các bạn thấy một loạt ở đây đó chính là
[00:34:59] cái gì ạ Cái này thể loại Ok thể loại
[00:35:02] các bạn thấy rồi nhưng mà con chia nhỏ
[00:35:03] nhưng cái này nữa OK thì có thể thể đoạn
[00:35:06] nhiêu cấp Okay tiếp theo nữa các bạn sẽ
[00:35:08] thấy ở dưới này nó là gì ạ Nó có những
[00:35:11] cái cái
[00:35:12] Ừ cái có thể Peter có thể lựa chọn này
[00:35:16] nó Peter Peter Peter như này tất cả
[00:35:19] những cái này nó là cái gì ạ Cái này
[00:35:21] không phải thể loại nữa Cái này cấu hình
[00:35:24] nóng ạ cấu hình cái kiểu cái thế danh
[00:35:28] mục à danh mục từ ra cũng được Nhưng
[00:35:30] thật là cái này bản chất nó cấu hình hơn
[00:35:31] và đây là đối với laptop cái là tôi thử
[00:35:34] cho ông xem cái khác thì sao laptop nó
[00:35:37] về cả
[00:35:38] em nhảy sang
[00:35:40] phím chuột này đi kiểu Nga
[00:35:43] Nghe tin bão ngày thấy cái này nó gì nó
[00:35:45] là hãng này giá này cũng lại cấu hình
[00:35:48] thì chỉ đó nữa này tất cả cái này vẫn là
[00:35:51] cấu hình ngoại cấu hình của bàn phím nó
[00:35:54] khác với cấu hình của máy tính không ạ
[00:35:55] Có không ạ thì thì cái bản chất là các
[00:35:59] bạn à thiếu mấy cái những cái này nó lắm
[00:36:03] chị ạ Nếu mà đã ta bây các bạn mà thiết
[00:36:06] kế Hồi đấy là tôi bị từng bị trừ 1 điểm
[00:36:09] vì cái vì cái vụ đấy Đó là
[00:36:12] Ừ thứ Bảy có bạn hãy thiết kế cho cậu là
[00:36:16] anh có thể dùng được cho mọi để tải
[00:36:18] người ta Đấy là ta bây không chi tiết
[00:36:22] Ừ tôi phải nói thế Tại sao ạ Giờ sự đây
[00:36:25] có mã này có tên này có giá này có ảnh
[00:36:29] này có mô tả này ông nhìn nó là bình này
[00:36:33] ông cũng biết được đây đời tôi Bây này
[00:36:35] bán thì cái gì không ạ khóc Không nhìn
[00:36:38] này ông chẳng biết là bán được cái gì về
[00:36:40] cơ bản thì cái này thể bán được mọi thứ
[00:36:42] cái này ra tôi mẫu thì anh yên không nói
[00:36:45] các bạn Thể Ôm nguyên như này không sao
[00:36:47] Nhưng mà thực sự là cái đã tới Bây này
[00:36:49] có thể bán được mọi thư đâu phải vậy mỗi
[00:36:51] người tình đâu ạ đúng không ạ Đâu phải
[00:36:54] 10 mỗi linh kiện từ bản bánh mà ghé lại
[00:36:56] được cái bán điện thoại cái này được cái
[00:37:00] bán quần áo còn cái lại được Bởi vì tao
[00:37:02] đây này đã ra đây một mức tương đối Đông
[00:37:05] ạ Nó không chi tiết về một cái gì vậy để
[00:37:07] ý tôi như thế
[00:37:09] Đã thế lại chẳng chưa có nhóm nào làm vụ
[00:37:11] này tôi cũng thử nói qua để những nhóm
[00:37:14] khá nhé những ông khá Nếu mà muốn thay
[00:37:17] đổi muốn sửa thì à Thì theo hướng của
[00:37:20] tôi nó sẽ như thế này là sự các bạn vừa
[00:37:22] rồi thấy cấu hình
[00:37:24] các bạn không nên có một cột là cột cấu
[00:37:26] hình luôn như nay ở trong này nếu mà các
[00:37:29] bạn làm như thế này thì rõ ràng cái cấu
[00:37:31] hình của một máy 1 máy có nhiều cấu hình
[00:37:32] khác nhau mà không ạ Cứ kệ nó còn có thể
[00:37:35] filter Tìm kiếm nữa thì không nên có cột
[00:37:38] này như thế này ở đây mà nếu thế phải
[00:37:40] tách riêng ra anh Chương ra nó sẽ là cậu
[00:37:44] áo kiểu dạng nó là như thế nào Đó là
[00:37:47] kiểu à
[00:37:49] Ừ vợ ạ
[00:37:50] Ê mấy ông thấy bản chất một máy tính có
[00:37:53] nhiều cấu hình đúng ạ và một cấu hình
[00:37:56] lại có thể thuộc nhiều máy tính đúng ạ
[00:37:59] thì rõ ràng nó là mối quan hệ mờ mờ
[00:38:02] Không ạ gọi là 1n bằng 1 n đấy không ạ
[00:38:05] thì tức à cấu hình này
[00:38:09] mã này tên này sau đó thì ở đây sẽ là
[00:38:13] cấu hình sản phẩm trở lại và sản phẩm
[00:38:17] cấu hình với
[00:38:18] sản phẩm chi tiết vì các bạn đặt thì đây
[00:38:22] sẽ la mã sản phẩm
[00:38:23] mã tên
[00:38:25] nhập mã cấu hình và đây giá trị họ gì đó
[00:38:31] từ trường đã đặt tên là giá trị đầy giả
[00:38:34] sử á là sự một ví dụ đi cho các bạn dễ
[00:38:36] Hình dung là sự đây là máy máy một này
[00:38:39] mẹ điều này không ạ và Vần đây xong rồi
[00:38:43] một ở đây tên là ra mẹ nào đó ngoại thì
[00:38:47] ở đây sẽ có mái một này mà cấu hình một
[00:38:50] này cho món này hiểu ra mà Bốn ạ nhắn tự
[00:38:54] ái hàng hay này nó sẽ là màn hình này
[00:38:57] đúng không ạ đây sẽ là một này hay này
[00:39:01] sẽ oled là chẳng hạn hoặc ips kiểu cơ
[00:39:06] Thế thì mày ông nhìn thấy có thể và
[00:39:09] đương nhiên để cũng sẽ nối lại cái này
[00:39:11] cái này cái này để khi màn hình điện sản
[00:39:14] phẩm da sẽ thì đầy đủ cấu hình của một
[00:39:17] sản phẩm cũng như là vì sau mấy ông muốn
[00:39:19] chỉ tìm kiếm tất cả những sản phẩm Ram
[00:39:21] 4GB em ạ khi bạn sẽ nối hai bà này với
[00:39:24] nhau rồi các bạn tìm kiếm đồng mạ ạ ở
[00:39:27] đây làm Đang tập bay thiết kế để cho về
[00:39:30] cái gì thì cho về mộ Nhìn cái là có thể
[00:39:33] hình dung được mình đang bán cái gì
[00:39:35] không ạ Cái này có thể ôm xăng bán bánh
[00:39:38] không ạ Không ôm bạn quần áo rồi ạ Không
[00:39:41] thì các bạn Nhi nói đó Bây này các bạn
[00:39:44] mới biết được nó là một đợt tao bây chi
[00:39:46] tiết về một cái gì đó ông ạ
[00:39:49] Ý tôi nói cái này thật ra nhiều bạn bây
[00:39:53] giờ đang nghĩ buổi như thế anh em phải
[00:39:55] sửa tao bay Gấp luôn không không còn nếu
[00:39:58] mà nhóm các bạn mà làm mức tầm trung
[00:40:02] bình hoặc yếu thì ra các bạn không cần
[00:40:04] quan tâm này như mình đang gợi ý và các
[00:40:06] bạn ngay bởi vì sợ thì tất cả các nhóm
[00:40:09] từ nhóm khá mà mình thấy các bạn lại tạo
[00:40:13] quá nhiều bạn lại không không đúng cái
[00:40:17] đề tài đó sao các bạn tạo thêm bảng về
[00:40:20] chat này với bình luận đấy xong rồi ở
[00:40:25] Ừ mạng gì nhỉ Bằng nhận thông báo này
[00:40:27] vẫn nó với những cái thứ mà thực sự thì
[00:40:30] nó hơi bị Hơi bị đi xa phải toán một tí
[00:40:34] cái cái cái
[00:40:36] gần nhất với các bài toán đó chính là
[00:40:39] cái gì đó là thịt là xem rõ được thông
[00:40:42] tin của một sản phẩm thì các bạn đã
[00:40:44] không có thế nên là mình thấy đó ạ Đây
[00:40:48] mình mình sẽ nói cái này để các bạn à
[00:40:51] anh hình dung được là các bạn phải phải
[00:40:55] làm được một bài toán ở những mức gọi là
[00:40:58] như thầy mình từng nói nó không lan man
[00:41:01] mà phải khoan tròn trịa đã cho nó chị ạ
[00:41:04] máy bay dõi đừng có la nan quá đừng có
[00:41:07] thêm rất nhiều tính năng mà mỗi tính
[00:41:09] năng chỉ được một tí tớ không cần mấy
[00:41:12] ông vậy cô chú trọng vào một cái tính
[00:41:15] năng mà nó rất là hoàn thiện hoàn chỉnh
[00:41:17] thì ổn hơn để ý ông muốn nói về ngoại
[00:41:21] rồi hôm trước của ông Tạm dẫn hai mươi
[00:41:24] mấy Hai mươi hai mươi mấy với bạn thôi
[00:41:26] em lấy sợ vãi đồ ăn 12 mấy cái bạn không
[00:41:29] biết đâu bán hai ông ấy cho tôi bao
[00:41:30] nhiêu chỗ à
[00:41:32] ừ ừ
[00:41:35] Ăn tim heo
[00:41:37] Tại sao lưu thông tin liên hệ ở các bạn
[00:41:40] order và bảng cúp summer
[00:41:43] Ừ
[00:41:43] thì à
[00:41:46] ai dọn ra là không Trước Các bạn có thấy
[00:41:48] là bảng hóa đơn của mình ông ạ hóa đơn
[00:41:53] thì mình còn lưu lại thông tin người
[00:41:55] nhận đúng là sửa là mình sẽ có một mã
[00:41:59] này cột à mã khách hàng à
[00:42:06] à à Ừ nhưng mà mình tự nhiên là mình có
[00:42:10] thêm tên khác à và tên người nhận
[00:42:12] số điện thoại mày ạ
[00:42:15] Địa chỉ người nhận em ạ
[00:42:18] kiểu nha các bạn sẽ thấy Ok Nhưng mình
[00:42:22] không trước mình có bà à cái thằng đặt
[00:42:24] chưa chắc là bạn nhận được ạ nhưng mà tự
[00:42:26] nhiên trong mảng khách Hà
[00:42:28] mình lại vẫn có mã có tên và số điện
[00:42:31] thoại và có địa chỉ
[00:42:33] Tại sao các bạn đã thắc mắc à Thế xong
[00:42:36] thì hiểu tại sao lại như thế này ạ Rõ
[00:42:39] ràng mà anh bắt người dùng nhập lại toàn
[00:42:42] bộ Cái này thì mình lưu lại những cái
[00:42:43] này cho mà khách hàng làm gì không ạ
[00:42:45] Không mà chính hôm nay mình sẽ dạy các
[00:42:47] bạn cái vụ này đó là khi mà đăng ký
[00:42:51] khách hàng điền thông tin này một lần và
[00:42:53] lưu lại không ạ Và khi mà đặt đặt hàng
[00:42:57] ấy thì mấy cái này nó sẽ tự động tự động
[00:43:00] điền vào tất cả những cái cái cột này
[00:43:02] trước và người dùng chỉ phép sửa lại ghi
[00:43:05] âm thể hiện người dùng không cần phải
[00:43:06] điền lại vụ đấy Ừ thì cứ mỗi lần đặt
[00:43:09] hàng rồi chồng lại phải điền lại tên số
[00:43:11] điện thoại cho ra họ không Hay còn nếu
[00:43:14] mà có bạn nào mà thích làm trải nghiệm
[00:43:16] người dùng tốt hơn đấy là
[00:43:18] thậm chí ở người dùng sửa cái tên người
[00:43:21] nhận số điện thoại người nhận địa chỉ
[00:43:22] người nhận rồi ra xử lại tôi thường ai
[00:43:26] đặt đồ cho bạn gái chẳng thế thì tôi sẽ
[00:43:29] ra một là tôi điểm tên tôi hay tôi điền
[00:43:32] tên bạn gái chỉ thế thôi Mày không biết
[00:43:35] cái bọn shopee đường ai có tạo tạo thêm
[00:43:38] cả nhiều địa chỉ người nhận không ạ nhé
[00:43:40] lắm chị ạ
[00:43:41] Gọi tạm nhiều danh bạ chứ tạm ngưng danh
[00:43:44] bạ làm chưa Một là tôi nhận hay là bạn
[00:43:47] gái hư nhận chị hai người thôi thì có
[00:43:49] mục lựa chọn nó đây chẳng hạn nữa ám chỉ
[00:43:52] một là các bạn chọn lại những cái thông
[00:43:54] tin cũ đã có sẵn của khách hàng này hay
[00:43:57] ở các bạn Nhập mới thường các bạn chị có
[00:44:00] một hạn hay người nhận thôi các bạn đỡ
[00:44:03] Ừ cái việc trải nghiệm khách hàng sẽ tốt
[00:44:06] hơn khi mặc các bạn khiến cho người ta
[00:44:08] đỡ phải mất công gõ đi Gõ lại những cái
[00:44:11] thứ người ra gõ rồi ông ạ lấy lại đơn cũ
[00:44:14] hay hàng để mạnh đề xuất ra đây ông một
[00:44:17] phương án khai ông ạ
[00:44:19] à Tôi đang nói ví dụ thì thôi mày Ông
[00:44:21] đừng có nghĩ quá nhiều mấy ông cứ ôm
[00:44:24] nhiều quá rồi cũng không làm cái gì đâu
[00:44:25] Thì em ví dụ thế
[00:44:27] Ừ đúng
[00:44:29] À mà đấy Cái mà tôi vừa tôi thưởng này
[00:44:32] nói mấy ông đó lại tôi lấy ý từ những
[00:44:35] cái ứng dụng mà người ông có thể đã dùng
[00:44:37] rồi shopee cái hay mua bán bán hàng gì
[00:44:40] đó mấy ông kiểu J mấy ông chẳng thường
[00:44:42] dùng rồi đúng không ạ Mấy ông phải phải
[00:44:45] thấy nó có cái gì hay mấy ông ôm về đóng
[00:44:48] ạ Hãy tạo cho mình cái thói quen kéo cái
[00:44:50] suy nghĩ ấy hiểu mấy ông ấy Đúng là dân
[00:44:52] công nghệ thông tin không phải một khách
[00:44:54] hàng bình thường nữa mà khi mày ông nhìn
[00:44:56] vào cái thằng kia nó áp dụng với gì mấy
[00:45:00] ông nghĩ tại sao làm được như thế nó làm
[00:45:03] cái đấy bằng cái gì Và mấy ốp bây được
[00:45:05] thì đấy mẹ Tư duy của một developer mà
[00:45:08] nhà phát triển chứ không phải là kiểu
[00:45:10] một người bình thường nữa mà em chưa
[00:45:14] Tiếp theo
[00:45:17] có mặn nói về cái bạn dưới tính tức là
[00:45:21] cài á
[00:45:24] thế giới tính hay làm
[00:45:27] ở đây là sự này có bạn có bạn nhân viên
[00:45:31] em ạ Hôm trước mình nói là sợ mã tên
[00:45:34] giới tính ở đây sau đó thì mạ và cấp độ
[00:45:38] em ạ Thì hồi trước mà mình nó là vụ là
[00:45:42] mình có thể quy ước luôn không là nữ còn
[00:45:46] một là nam này ạ Xin lỗi các bạn nữa thì
[00:45:49] thì
[00:45:51] Ừ mình quy ước như thế này bởi vì bạn sẽ
[00:45:54] là thật lạ thường là giới tính theo kiểu
[00:45:56] tóc theo sinh học đấy thì ra nói chuyện
[00:45:59] ở hai thôi thì các bạn phải quyết thằng
[00:46:01] ở trong cốt con nếu mà các bạn tạo theo
[00:46:05] kiểu nó là mã giới tính ở Nga
[00:46:07] Sau đó các bạn tách hẳn vậy bạc riêng
[00:46:10] bạn giới tính có mã có tên như thế này
[00:46:13] mở màn thứ ba cái này vốn dĩ nó chẳng Vợ
[00:46:16] thay đổi vào nó cũng chỉ có 2 giá trị
[00:46:17] Thôi thì mình thấy rồi ra hơi thừa tính
[00:46:20] nhất là thừa thừa ạ việc cứ mỗi lần lấy
[00:46:23] ra được giới tính là các bạn phải nối
[00:46:25] tận hai ba thằng em nó bị kiểu bình Nặng
[00:46:28] cũng như là nó con bị Hơi sai đó ra sao
[00:46:31] vì thường mình phải thẳng Thế ba là để
[00:46:35] mà mình thay đổi có thể thêm sữa xóa nó
[00:46:38] nhiều thì mình phải tách hẳn ra cái ba
[00:46:40] con việc ở dưới tính gần như cháu vừa
[00:46:42] thay đổi được cậu không mới mổ thì các
[00:46:44] bạn việc thêm không mở thêm dự tính mới
[00:46:46] cũng không ở xóm dưới tính cũ đi Anh ra
[00:46:49] à Cái này nó thừa tương tự thế với cái
[00:46:52] cấp độ cũng có bạn bảo là em muốn tách
[00:46:54] hẳn ra em không muốn nó không lấy một
[00:46:56] giống như anh Bảo nữa em muốn có hành
[00:46:59] bạn bạn cấp độ không ạ sau đó thì cũng
[00:47:02] có mã cấp độ thì giống như mình vừa nói
[00:47:04] về cũng tương tự với thằng giới tính đó
[00:47:07] là Anh trừ khi về sau các bạn muốn thêm
[00:47:09] nhiều cấp độ và sự cấp độ 1 thìa nhân
[00:47:11] viên cấp độ 2 thư ký cấp độ 3 là giám
[00:47:14] đốc cấp 4 là kia bố ra mốc này ạ kiểu
[00:47:17] như thế thì mới tạo thêm phần mùa bảng
[00:47:20] riêng để phân biệt các cấp độ còn nếu mà
[00:47:23] các bạn chỉ có hai cái lỗ thôi thì thì
[00:47:26] cho việc tạo trên bảng có thành thừa Bởi
[00:47:29] mình không chỉnh sửa thêm sửa xóa gì nó
[00:47:32] không ạ
[00:47:34] a tiếp theo
[00:47:36] anh có thể dùng cột email làm khóa chính
[00:47:39] không Nếu các bạn có thể ý thì ạ
[00:47:42] đôi khi mạn nhân viên hoặc cả bạn à
[00:47:45] khách Hà
[00:47:47] Ừ thì mình sẽ có cuộc Email là đệ mình
[00:47:50] hơi để nó là muốn nick theo kiểu nó là
[00:47:52] duy nhất ở ngoại tí mèo không bị chung
[00:47:54] Và thậm chí khi mà các bạn nối vạn thì
[00:47:58] ra nó có đề xuất là những cái cột Yoona
[00:48:00] có thể làm quá ngoại trừ ra là các bạn
[00:48:03] không nên dùng nó làm khóa ngoại
[00:48:06] Ừ thế này cũng không nên dùng nó nó khóa
[00:48:08] trình luôn tại sao bởi vì à à
[00:48:12] từ khóa chính cũng giống như ở cái trả
[00:48:15] lời luôn cột người này là là cột bà còn
[00:48:20] nên có cột mã và thận chữa để nó tự động
[00:48:23] tăng 20
[00:48:28] hóa chính thì nên là số thì nó nhẹ nhất
[00:48:32] để nó nấu ra mà khác không nên để nó chữ
[00:48:34] rồi nói ra mà khác nó nặng hơn đấy Cái
[00:48:37] thứ nhất thứ hai là
[00:48:39] các bạn là
[00:48:42] về việc để phân biệt hàng ngày với thằng
[00:48:45] kia các bạn thường ai có truyền theo mã
[00:48:48] để mà sửa xóa thằng nào đó chỉ việc mạn
[00:48:51] hay vì truyền mã Các bạn truyền Email
[00:48:53] thì sửa hàng nào đó thì mình thấy bài
[00:48:55] toán nó trong nó vẻ phức tạp hơn các bạn
[00:48:58] nên chỉ truyền mã thì nó sửa xem thêm
[00:49:01] sửa xóa thằng nào đó hơn hơn là truyền
[00:49:03] email dễ thương lắm mã này có thể số thì
[00:49:06] đúng hoặc à đoạn chuỗi theo kiểu là
[00:49:09] Uruguay đi chơi thường là chẳng ai nó
[00:49:11] kiểu truyền truyền email treo để nó
[00:49:14] xưởng cái gì đó gà nên nó thành vô lý
[00:49:16] đúng ạ Các bạn thấy chẳng thằng nào làm
[00:49:19] từ điều đấy khác đâu chị ạ ạ
[00:49:23] A và bảng nào cũng có cần cột mã tự động
[00:49:26] tăng hay không thì ra là không
[00:49:29] sau khi mà các bạn muốn thêm sửa xóa à
[00:49:32] muốn nối nó sang thẳng bản khác thì có
[00:49:35] bạn mới có cột cần Còn mã tự động tăng
[00:49:38] anh còn không thì gần như các bạn sẽ
[00:49:40] không cần cột Mã làm gì cả trừ khi ở cậu
[00:49:43] các bạn muốn sửa nó dễ và không có cột
[00:49:46] nào của tunick thôi Bây giờ thì mình thử
[00:49:48] Ví dụ nhé Có bạn hóa đơn chi tiết
[00:49:52] các bạn nhiều nó sẽ có mã hóa đơn này và
[00:49:56] mã sản phẩm
[00:49:57] và số lượng hôm trước cũng có bạn ốp
[00:50:01] thêm cả cuộn Mã từ đóng băng ở đây nữa
[00:50:03] Mình thấy được ra cột này nó chả mơ nối
[00:50:06] đến đâu ạ mà chẳng để làm gì cả các bạn
[00:50:08] để mà biết tiền lấy ra được cái hóa đơn
[00:50:11] thì ra các bạn lấy theo mã hóa đơn không
[00:50:13] ạ lấy ra hóa đơn kèm sản phẩm của bạn sẽ
[00:50:16] dựa theo hai cục này hay cột này cũng là
[00:50:18] khóa chính luôn được chưa Thế là chẳng
[00:50:22] cần cột mã tự đóng băng làm gì cả
[00:50:24] ừ ừ
[00:50:26] thì các bạn đừng có bị Rập khuôn là bảo
[00:50:28] nào cũng cần mã cột mã tự động đăng nhé
[00:50:30] bây giờ đấy
[00:50:31] hôm mình đang trả lời rất nhiều câu mà
[00:50:35] Thậm chí à hôm bảo vệ đồ án tôi sẽ hỏi
[00:50:38] cho tôi tôi sẽ có hỏi cả lý thuyết và
[00:50:41] thực hành nhé thực hành là nói về bài
[00:50:44] toán về cốt và về cách giải quyết vấn đề
[00:50:48] và cách xử lý vấn đề
[00:50:50] cho con về lý thuyết thế là tôi hỏi
[00:50:53] những cái này đâu ạ Đây tôi mà đã dậy
[00:50:57] Cái gì Tôi luôn nhớ là tôi đã dạy cho
[00:50:58] đến rồi tôi hỏi mấy ông mà mấy hôm trời
[00:51:01] được thì đương nhiên với ông Định trừ
[00:51:03] điểm không ạ Có đấy nhá Ừ
[00:51:06] a Tiếp theo là cái cái Các bạn nhớ mình
[00:51:12] từng nói các bạn viết tài liệu ông ạ sẽ
[00:51:14] mình sẽ cho các bạn xem lại cái tài liệu
[00:51:16] có một cái bản tài liệu nó đầy đủ thì nó
[00:51:20] sẽ làm như thế nào
[00:51:21] em gái mình sẽ cho các bạn xem
[00:51:24] từ nãy giờ mình vẫn đang vừa trả lời vừa
[00:51:27] dậy luôn đấy nhá Không không không bảo
[00:51:31] mình tính thời gian cứ thư được đây mình
[00:51:33] sẽ có cái tài liệu mẫu
[00:51:36] Em không biết đấy Đúng là liệu mẫu nhỉ
[00:51:39] anh ở đây đây đúng không có tài liệu mẫu
[00:51:41] sẽ bia hôm đấy bọn tôi tôi yêu cầu mới
[00:51:45] hoang y này nữa em phải có bia
[00:51:48] Khi ra về sau các bạn cũng nên có mấy
[00:51:51] bia rượu trong Nghệ sĩ không ạ
[00:51:55] I lời mở đầu này
[00:51:57] cách móc hoa giới thiệu đưa ra vấn đề
[00:52:02] anh về sau kể từ rồi sẽ nhắc lại này để
[00:52:04] ông làm tài liệu mà nhưng tớ nói qua đã
[00:52:06] giới thiệu chung về dự án xuất xứ dự án
[00:52:09] Lý do cận hình giao tạo dự án đấy hệ
[00:52:13] thống hiện tại Đức à trước khi có dự án
[00:52:15] này trước khi làm ra các phần mềm này
[00:52:17] thì bản chất mình đã làm gì Ví dụ là sử
[00:52:21] trước này trước khi có cái trang web bán
[00:52:23] hàng bán hàng này thì chị có bán hàng
[00:52:26] trực tiếp không bán hàng online cả không
[00:52:28] ạ Đấy số 10 lưu lại thông tin qua Excel
[00:52:32] Word hoặc lưu lại trên giấy nó ngoạn đó
[00:52:36] sau đó Thì bây giờ mình sẽ cần làm ra
[00:52:38] một cái sản phẩm như thế nào yêu cầu gì
[00:52:41] Yêu cầu chạy được trên ie không Vân Vân
[00:52:44] Vân yêu cầu như thế nào đúng ạ Vì rõ hết
[00:52:46] ra công nghệ mình áp dụng lần này sẽ là
[00:52:49] gì đấy phân tích này Phân tích khi trước
[00:52:52] Nam giữa các phím chức năng không phải
[00:52:54] một tính năng gì đó ví dụ Giả sử là giao
[00:52:57] diện bắt mắt này giao diện trụ To 20 cho
[00:53:00] người già cho sạch trẻ con Ừ mẹ không
[00:53:03] dùng dùng được trên kiểu máy hệ điều
[00:53:07] hành Windows 20 V.League P20 chẳng hạn
[00:53:10] thế Vân không ạ ừ ừ
[00:53:13] ở nhóm người sử dụng loại
[00:53:16] khách hàng chưa tay có tài khoản làm
[00:53:19] được J có tài khoản làm cái gì cái không
[00:53:21] trước nói rồi sau đó phân tích Chức Nam
[00:53:23] thì chức năng này cái thứ mà mình đang
[00:53:25] định nói ở đây chính là cái này đó là
[00:53:28] các bạn phải liệt kê rõ toàn bộ là
[00:53:32] ai là người ví dụ đăng nhập ở lại Ai là
[00:53:35] người có thể làm được cái nói chung
[00:53:38] hướng sử dụng được chức năng này không ạ
[00:53:40] mô tả này chúng mang này nó làm gì à
[00:53:46] khi kích hoạt khi bấm ở đâu đấy nó sẽ
[00:53:49] kích hoạt tổ chức năng này đầu và là
[00:53:51] những cái thước của người đăng nhập từ
[00:53:52] bàn phím và bảo hiểm tràn ngập những cái
[00:53:54] gì đó trình tự xử lý nó là gì Lấy lấy
[00:53:59] cái thông tin gì gì đó về virus ung thư
[00:54:02] sau đó kết nối cơ sở liệu đóng gói thì
[00:54:05] kiểm tra xem khớp hay không khớp thì cho
[00:54:08] vào không đi giao đầu ra thì hiển thị
[00:54:10] Đúng là gì sai là gì đấy lưu ý ạ Đây huy
[00:54:14] những cái gì Cái này nó là văn xuôi
[00:54:17] không phải Cốt nó là nhưng cần như tôi
[00:54:21] thấy nó mã ra để mà các bạn nhìn ở đây
[00:54:24] các bạn cốt được cái thường hay được
[00:54:27] viết Ừ để cho dân
[00:54:30] vì dân không phải dân công nghệ đọc
[00:54:33] Ừ cái tài liệu này không phải là dân
[00:54:36] công nghệ đọc vẫn phải hiểu được Thế em
[00:54:39] làm mấy ông không được viết tắt cũng đi
[00:54:41] là không được viết
[00:54:42] Ừ
[00:54:43] từ chuyên ngành mấy ở trong này phải
[00:54:46] biết sao cho dân không phải dân công
[00:54:48] nghệ đọc Tại sao cái này vừa là tài liệu
[00:54:51] để mà tham khảo để mà gửi cho bất kỳ ai
[00:54:55] vừa mới vào công ty các bạn có thể đọc
[00:54:57] qua để thiệu qua được cái phần mềm các
[00:55:00] bạn đang làm là là gì và giao cho ông
[00:55:04] công việc kiểu ôm làm tính năng này
[00:55:05] không nhìn vào cái ông hiểu được phần mô
[00:55:07] tả thì mấy ông có được cũng như là cái
[00:55:11] này mấy ông xem sắp tang cho biết qua về
[00:55:14] mấy cái vụ kia lên để mặc cái gọi vốn
[00:55:16] không ạ
[00:55:17] Cái này thì cũng là cái in tài liệu ra
[00:55:20] để cho mẹ ông mấy ông ở trên kia đọc đầu
[00:55:24] nhọn mà hình dung qua được là sản phẩm
[00:55:28] Ông nó nó như thế nào Có cần phải làm
[00:55:31] những cái gì
[00:55:32] Vì thế nên là nghĩa là không phải dân
[00:55:36] trong ngành đọc cũng phải hiểu được
[00:55:37] không ạ Và nó chúng ở hôm buổi bảo vệ đồ
[00:55:41] nó đúng là như thế đó mới không phải
[00:55:43] thuyết phục được người kia cảm thấy sản
[00:55:46] phẩm của ông đánh này là Ừ kệ bản chất ở
[00:55:50] tài liệu là hết thứ nhất là phải có
[00:55:51] trước cái phần mềm để mà cái người cái
[00:55:55] người kiểu giặc sư giám đốc đi đêm em
[00:55:58] cái hình dung ngay nhé mày ông đang định
[00:56:01] làm một cái
[00:56:03] chạm một cái trang web một cái phần mềm
[00:56:05] mấy ông Nghĩa phải mất nửa Nam và cần
[00:56:08] đầu tư vậy cũng tầm
[00:56:11] gần tỷ 300 triệu gì gì đó để làm phần
[00:56:14] mềm mấy người tốn thời gian thôi nhưng
[00:56:16] tốn kém các thử thứ thì ông sẽ làm tài
[00:56:19] liệu này là mày ông dễ làm một cái sản
[00:56:21] phẩm để môi trước để mà
[00:56:24] đưa lên thuyết trình cho giám đốc hoặc
[00:56:27] cả nói cho Hoa cấp trên là ngọn để cấp
[00:56:30] chân chính cấp trên duyệt sau đó cấp rên
[00:56:32] trên mày đưa tiền mới rót vốn vào để đầu
[00:56:35] tư để mà làm sản phẩm chứ không phải mấy
[00:56:38] ông làm phần một sản phẩm hoàn Trinh
[00:56:40] ở sông lý thuyết trình ra ai chẳng ai
[00:56:43] hiểu sản phẩm mấy đâu và là sự người ta
[00:56:46] không tốt 4 và thịnh mấy ông chết à
[00:56:48] không ạ Nếu ông bỏ thôi thời gian công
[00:56:51] sức ra người ta không duyệt thì dao động
[00:56:53] ngoại Thế nên là đều phải có tài liệu
[00:56:56] đầy đủ cũng như là mấy ông phải làm các
[00:56:59] sản phẩm demo một cách tương đối thôi
[00:57:01] cũng được để mấy ông đem đi trên Đông ạ
[00:57:04] Cái bảo vệ đồ án này đương nhiên là sản
[00:57:07] phẩm đấy mộ sẽ ăn đấy sản phẩm đến mô
[00:57:09] rồi bởi vì sản phẩm của ông là mong hai
[00:57:11] tháng chẳng có ai dung được nó còn đầy
[00:57:14] lỗi đầy thứ cần phải làm nữa nhưng người
[00:57:18] ra thấy là
[00:57:19] vì nó có tiềm năng nó có triển vọng nó
[00:57:22] bán đáng để đầu tư vào thì họ sẽ đầu tư
[00:57:25] ông ạ Thế nên là cái cái tài liệu này
[00:57:29] cũng như là phải sản phẩm demo của ông
[00:57:31] phải phải tương đối và tương đối ôn ông
[00:57:35] ạ và phải dễ hiểu về chưa chứ trình của
[00:57:39] mấy ông phải dễ hiểu bởi Nếu nó kêu gọi
[00:57:41] vốn mà Mấy ông nói thì được
[00:57:44] sản phẩm của em thợ sơ sài lắm chả có
[00:57:46] cái gì đâu hơn dân thì chả ngay dốc muốn
[00:57:49] ôm cả không ạ Đấy Nói chung là không bảo
[00:57:52] vệ đồ án thì mấy ông cũng xem nhiều sắp
[00:57:54] anh mà mình không học dần đi đứng nhà
[00:57:58] tôi không muốn họ bảo mấy ông phải báo
[00:58:00] cáo thống kê được các báo cáo với tài
[00:58:02] chính không nghe máy không phải
[00:58:04] Ừ biết biết cách thuyết trình ở ngoại ô
[00:58:07] ai biết cách thuyết phục người khác
[00:58:10] ý nghĩa của tài liệu như thế thế nên là
[00:58:13] mấy ông đừng có viết tài liệu theo kiểu
[00:58:14] mình ông lọc được nhé cái tài liệu này
[00:58:17] không phải ông làm ra để ngày này năm
[00:58:18] xong xem lại đâu nhé Đây liệu này viết
[00:58:21] ra để cho người khác đọc nhưng mà Mấy
[00:58:22] ông phải viết sao cho nó tim mì nó nó
[00:58:26] chi tiết ý kỹ tính và đi để ngoại hôm
[00:58:30] trước tôi xem Khánh Như của nhóm say
[00:58:32] mình lỗi chính tả nỗi buồn lắm nhưng
[00:58:34] không phải học lại cách viết code đi
[00:58:36] à à
[00:58:37] a tiếp theo các bạn bị Cái lỗi này thật
[00:58:42] ra mình không biết được Cái lỗi này
[00:58:43] Nhưng mà mình cứ để cho các bạn tự trải
[00:58:47] nghiệm đã một mình mới bắt đầu chữa Cái
[00:58:49] lỗi này là khi các bạn à
[00:58:51] Sistar thận thì các bạn lỗ sự tác ở
[00:58:53] trong cái file menu rồi các bạn ở trên ở
[00:58:57] pha bình thường các bạn đã Sinh tát rồi
[00:58:59] trong file menu các bạn restart lại phát
[00:59:01] nữa nếu bạn include the famine vào xảy
[00:59:04] ra nó Sistar tận 23 lần gì đó khá nhanh
[00:59:08] nó lỗi thì cách đơn giản ở đây mình có
[00:59:11] đề cập đó là các bạn chỉ nên xét phát ở
[00:59:14] ngay cái file đầu tiên và Không chèn xây
[00:59:18] dựng Tát ở ở những cái file mà mình sẽ
[00:59:20] in Plus là sự file crack này thì các
[00:59:22] loại stop ngay đâu nè ở đó dưới này các
[00:59:25] bạn nút vào thì chẳng mới đề gì à các
[00:59:27] bạn đừng có Sinh tát ở trong này trong
[00:59:29] này hay trong mai đúng ạ Các bạn xin xác
[00:59:32] mỗi trên cùng như này thôi của một cái
[00:59:34] file chính đều không ạ thì nó sẽ không
[00:59:36] lỗi và cái bài toán ở đây thì mình có
[00:59:38] nói đó là em
[00:59:40] có bạn thì bảo là em sẽ ít theo ở kiểm
[00:59:44] tra xem đó xin sát hay chưa ở trong từng
[00:59:46] file này cũng được được nhà cái đấy hỡi
[00:59:49] kỵ tinh quá và thực ra về sau mình cũng
[00:59:51] không làm theo mô hình hưởng rộng rãi mà
[00:59:53] trẻ hết mình đóng vai lằng nhằng nhưng
[00:59:54] ai trong nói dối các bạn sẽ không biết
[00:59:57] được là file này đang chứa gì file kia
[00:59:59] chứ gì là 1 thì mình sẽ tách nó ra mô
[01:00:02] hình mvc và vì sao còn theo phương Quốc
[01:00:05] nữa thì các bạn không cần phải lo việc
[01:00:06] được các bạn phải hiểu quá rõ về mấy cái
[01:00:09] mấy cái kiểu tách ghép file như này về
[01:00:13] sau có mô hình nó làm hết rồi các bạn
[01:00:14] này các bạn không cần phải
[01:00:17] chuyên sâu này quá nên mình đang chị dậy
[01:00:21] tương đối là các bạn mẹo các bạn ạ Bạn
[01:00:24] cứ start ở mỗi trên trang mỗi file chính
[01:00:27] rồi cũng phải nốt điều mơ dịch sữa Smart
[01:00:29] là được à
[01:00:31] em có bạn hỏi nữa mình trả lời nhanh đó
[01:00:34] mà có bạn hỏi là crack ở đâu ổn ra sự
[01:00:37] crack Office hóa crack win thì mẹ từng
[01:00:40] nói đó là các bạn lên Facebook các bạn
[01:00:43] tìm một cái nhóm là kích hoạt
[01:00:47] khi kích hoạt bản quyền
[01:00:51] kế hoạch Office hoặc kích hoạt Windows
[01:00:54] dưới đó có rất nhiều nhóm và chuyện
[01:00:57] Facebook như thế thì như là lượng người
[01:00:59] thiện nguyện lượng người tham gia chỉ có
[01:01:01] tầm 20 mệnh hay mấy nghìn người thôi nhớ
[01:01:04] thấy đã nhưng mà nhỏ mẹ đi tí mình mấy
[01:01:07] lần lên đấy ý chỉ cần đăng đăng mà cậu
[01:01:10] các bạn nên đang theo cú pháp như thế
[01:01:13] này nhá Nếu mà các bạn xem cái Bài ghim
[01:01:16] người ra rồi thì các bạn kiểu còn không
[01:01:18] thì các bạn cứ làm cú pháp nó ra Kiểu
[01:01:21] nhớ là các bạn phải xem được là
[01:01:24] Em đừng có lên đang đúng một câu lục đó
[01:01:27] hả ai đó kích hoạt Win hộ em chấm hết
[01:01:30] Hình như bài sẽ không mua được rồi vì
[01:01:33] hỏi không vô tâm được hỏi có dâm ở như
[01:01:35] nào các bạn sẽ phải Vào setting để xem
[01:01:38] được là
[01:01:39] hệ điều hành các bạn Win bao nhiêu cái
[01:01:43] thứ nhất nhì thế ngoạn là sự như thế này
[01:01:48] vào xem được Kiểu các bạn dùng Win mấy
[01:01:50] đây
[01:01:51] rồi nha Win 10 pro này version mấy này
[01:01:55] đã khá nhìn này đi nhân như thế Office
[01:01:59] các bạn như thế bạn phải nói cụ thể là
[01:02:01] các bạn sẽ không
[01:02:03] sử dụng Office phiên bản bao nhiêu Vân
[01:02:05] Vân Đấy đấy Cái thứ nhất nhé thứ hai đó
[01:02:09] là sẽ có một người sẽ bà là các bạn
[01:02:11] inbox cho họ
[01:02:13] thì các bạn đừng bao giờ lên à
[01:02:17] cho nên a kiểu gửi luôn cái tivi ở trên
[01:02:20] trang ở trên cái bài đang đấy vì ai Nếu
[01:02:23] Thế lại vào được tivi các bạn thì chết
[01:02:24] các bạn nên kiểu ý nhắn qua inbox và các
[01:02:28] bạn còn đến xem lại và các bạn ấn bấm mà
[01:02:30] luôn nick người kia để nó xem qua người
[01:02:33] kia hoạt động thế nào ở trong nhà nhóm
[01:02:35] đấy cuộc sống nổi không Bởi vì có nhiều
[01:02:38] người thì đúng là vào đấy là mà lừa ai
[01:02:40] đó trên view vào khách máy này ra
[01:02:44] Ừ thì các bạn hãy xem xem người đấy Có
[01:02:47] ổn hay không Hãy gửi teamview sao về đây
[01:02:49] người bị hack qua teamview rồi đấy mày
[01:02:53] không Thế nên tôi mới bảo là mày ông
[01:02:55] crack Xong rồi ông cũng thương hay dẫn
[01:02:57] lên có vấn đề gì đó con thường là mấy về
[01:03:01] anh kia kiểu teamview qua làm việc
[01:03:03] chuyên nghiệp hết mình thấy chị 23 phút
[01:03:05] thôi là crack xong 10 là crack Đông mình
[01:03:08] đã kích hoạt thi cho mình đấy hoặc đi
[01:03:11] bằng điều gì mình không rõ lắm kích hoạt
[01:03:12] cho mình đấy bây giờ không crack cho
[01:03:14] mình đâu ngờ cái hoạt này có vẻ vĩnh
[01:03:16] viễn gì vậy Mình mình cứ mỗi lần mình ở
[01:03:18] xong lại đi rằng là nó ổn vài năm sau A
[01:03:24] a tiếp theo học ở trang nào cũng kết nối
[01:03:27] đoàn tàu bay Có vấn đề gì không ra thì
[01:03:30] về sau các bạn sẽ biết được mà
[01:03:32] Ừ thứ nhất ở đó nhưng kết nối nhiều nó
[01:03:35] sẽ sẵn ở không ổn thôi nhe thế không ổn
[01:03:37] rồi nhưng là thực tế là vì sau ở trang
[01:03:40] nào cũng lấy dữ liệu ra mà cũng mặc kiểu
[01:03:42] định phải kết nối nên các bạn về sau nếu
[01:03:44] tìm hiểu kỹ hơn về các bạn sẽ biết rất
[01:03:46] nhiều cách để hạn chế điều này làm như
[01:03:48] lưu lại đây lại cách để mà giảm thiểu
[01:03:51] cho cái nối này hơn vân vân vân Thế mình
[01:03:54] sẽ dạy kỹ hơn sau còn bây giờ hiện tại
[01:03:56] thì các bạn làm như mình làm đó là Mở
[01:04:00] kết nối nhờ nhờ đóng cái nỗi nhớ để cái
[01:04:02] thứ nhất thứ hai các bạn nghĩ rằng làm
[01:04:03] việc là tôi yêu cầu truy vấn cho bớt
[01:04:06] truy vấn thôi cũng được cũng được rồi
[01:04:09] phim hoạt hình làm mịn quá Hôm nay bắt
[01:04:12] đầu bây giờ bắt đầu học nha là màn bao
[01:04:15] giờ nó có ok
[01:04:18] Ừ ok ở đây thì mình hôm nay mình sẽ dạy
[01:04:21] các bạn về hôm trước làm cái giỏ hàng
[01:04:24] rồi nghỉ à
[01:04:27] à à
[01:04:30] Em
[01:04:31] đổi tên rồi
[01:04:33] web cơ bản à
[01:04:40] Ừ đúng rồi bị đội tên miền này là mất ít
[01:04:43] hơn nữa vào đăng nhập lại vậy thì mới ở
[01:04:45] trước hết đăng nhập lại thì vừa mình cho
[01:04:48] các bạn xem lại tao bay mình phải sửa
[01:04:50] jambe một tí Bởi vì lần này mình sẽ lưu
[01:04:53] lại thông tin của khách hàng ở trong
[01:04:56] trong bạc khách hàng để mà tí mình bảo
[01:04:59] hành mình chỉ cần lấy thông tin này ra
[01:05:00] tự động điện nó sẽ dễ hơn khi mà khách
[01:05:04] hàng đăng ký rồi khách hàng ở mất công
[01:05:05] nghiệp địa chỉ rồi thì lần sau mình phải
[01:05:08] lấy lại địa chỉ cũ gái hàng đã nhập để
[01:05:10] mà dùng tránh việc bắt khách hàng nhập
[01:05:12] niệm loại nó dỗi nó không vì nó không
[01:05:16] đặt lại nữa hãy khó chịu ra
[01:05:18] Ừ tôi từng thế
[01:05:20] em có nhiều Trang nó khó chịu đúng kiểu
[01:05:23] như thế luôn Thế là sao mẹ đặt mỗi pizza
[01:05:25] tắt Đăng ký xong rồi đăng ký xong vẫn
[01:05:28] gọi điện lại thông tin mình vừa lại vừa
[01:05:30] nhập đăng ký
[01:05:31] UC vãi
[01:05:34] ô nhiễm đường như thế
[01:05:36] Tôi tin là chắc chắn ở sinh viên của tôi
[01:05:39] Cậu gì về sau cũng sẽ làm một ngày trang
[01:05:41] web gì đó Tôi không muốn về Sao tới động
[01:05:44] là đúng những cây xăng web đấy mà Mấy
[01:05:45] ông lại gây khó chịu người dùng
[01:05:48] buồn lắm
[01:05:53] ở chỗ nào Nhưng cái cốt đấy những cái
[01:05:55] cốt rất là dễ luôn đấy chồng ạ Nhưng nếu
[01:05:59] không ở những người dùng mới không
[01:06:00] thương người dùng không thương người
[01:06:02] dùng thì ghen à
[01:06:04] Ê mấy ông mà làm cái á
[01:06:07] Ừ
[01:06:08] đúng rồi thưởng các cấp các bạn đăng ký
[01:06:11] đặt hàng thì các bạn vẫn để điền thông
[01:06:13] tin người nhận là người khác có nhưng mà
[01:06:15] các bạn nên tự nên là có kén nút một là
[01:06:18] nút ở Ấn và tích là sẽ tự động điền
[01:06:21] thông tin mình đã đăng nhập này hòa tự
[01:06:23] động Điền chiếu cũng được người dùng thả
[01:06:25] xóa đi để Điệp lại trải nghiệm dùng một
[01:06:28] tốt hơn việc là người dùng cứ thấy mình
[01:06:31] vừa Điền xong thông tin lại bắt buộc
[01:06:33] phải điền lên thông tin nữa khó chịu cực
[01:06:37] Ừ cái đây trải nghiệm người dùng không
[01:06:39] tốt đâu cứ khẳng định luôn cái á
[01:06:42] một số người bỏ bỏ về đơn đấy
[01:06:46] anh chủ yếu là lúc mà khi người ta đến
[01:06:49] mức cô ấy người ta không phải bước cuối
[01:06:51] thanh toán đâu bước cuối người ta đến
[01:06:52] thông tin về à Cái thời gian đấy người
[01:06:54] ta thường ngày lưỡng hợp nhất để bỏ cái
[01:06:56] đơn thôi Nếu mà làm cho người ta khó
[01:06:59] chịu lúc đấy là người ta sẽ luôn Bỏ đơn
[01:07:00] Nếu ông mặt thống kê cái vụ đơn đã bị bỏ
[01:07:03] đi tỷ lệ thấp Cực
[01:07:05] nhà tỷ lệ thành công thấp quý Tôi làm ở
[01:07:09] trên trang web là bán hàng đôi biết mà
[01:07:11] Lợi chị hai ba phần trăm nữa là cao ấy
[01:07:14] rất là cao ấy nhiều chả không đến cơ à
[01:07:19] ờ ờ
[01:07:23] có thêm thông tin mà ngon
[01:07:26] số
[01:07:27] [âm nhạc]
[01:07:31] phận mình lại chưa
[01:07:34] Ê con chó rất mình là nó cứ sủa mà nó
[01:07:37] xuôi mình lại giận mình theo ý
[01:07:44] à à
[01:07:47] à
[01:07:49] À quên One để tiếng Anh à phone number
[01:07:52] nóng lạnh ạ
[01:07:55] à à
[01:07:57] anh không Nó sủa nó mà sửa cái tiếng
[01:08:00] động lạ thì thôi không đánh nó nó 1 xổ
[01:08:04] con mèo chỗ rách thì tôi sẽ này ngon
[01:08:06] ờ ờ địa chỉ address à
[01:08:12] chú chó nhắc Hôm nay đánh
[01:08:16] Ô Ôu bao giờ tôi đang dùng cái mic thu
[01:08:18] hái ngạnh có để mức mắc cả vô lu bu
[01:08:23] Ý anh là mấy ông tôi ngay cái gì mày Ông
[01:08:26] cố Thế nghe vậy gấp đôi tôi nghĩa về để
[01:08:29] trải nghiệm công việc tốt giá
[01:08:31] Bphone đăng ký không ạ
[01:08:34] thì mình sẽ có đã sai hát này
[01:08:38] chị sẽ có mật khẩu à
[01:08:42] cho
[01:08:43] số điện thoại
[01:08:48] or number
[01:08:53] địa chỉ và có để tách nữa cho họ tách
[01:08:57] alo thôi Nói đùa thôi thường Mấy ông
[01:09:01] không nhập địa chỉ xuống làm đâu ạ
[01:09:05] thì ra tất cả không cần các bạn bị pha
[01:09:08] tra được thôi để tách cả được là hơi
[01:09:10] nhiều quá
[01:09:11] Chưa chết nổ Nội để chị nhà mới rồi
[01:09:14] không đi đâu mèo không không thấy gì nhé
[01:09:17] tôi mở lại gần rang nha
[01:09:20] các mẹ Đấy nó hiển thị cái nhỉ
[01:09:25] Mấy ông đừng đốt nhé Đây là ngõ rồi mày
[01:09:29] Ông đốt nhầm nhà đấy
[01:09:32] à mật khẩu 123 đi
[01:09:35] ừ ừ
[01:09:40] chị đã lẽ là tôi có thể dùng cái nick
[01:09:44] khác thì sẽ không có lộ mới thông tin nó
[01:09:46] đề xuất ra thôi kể chắc sinh viên Trang
[01:09:50] toàn sinh viên xem mà không có ông nào
[01:09:52] ghét tôi mà ngồi xem mấy đâu đúng không
[01:09:54] ạ
[01:09:58] Ừ cái báo lỗi
[01:10:00] báo lỗi vì À đây mẹ sang xem Tại sao Nó
[01:10:04] lỗi
[01:10:06] cái bản chất là khi mình đến này Ok này
[01:10:10] ổn rồi này Nhưng khi mình Insert xong
[01:10:13] rồi mình lấy lại thông tin thì nó bị lỗi
[01:10:15] còn gì ở rõ là ý shop mình có vấn đề
[01:10:16] mình chắc chắn là như thế vì rõ là chiếu
[01:10:19] cột mà nó ngoại gì chứ vấn đề rồi đấy
[01:10:21] mình sẽ thêm là phần nằm mơ này I
[01:10:26] à à
[01:10:32] ăn xong tôi không sợ chồng như anh Tuấn
[01:10:35] đâu anh Tuấn kiểu ẩn danh hoàn toàn thôi
[01:10:37] chứ ra mấy ông Nếu mà không thực sự mà
[01:10:39] ghét một ai đó tôi nói thẳng là kiểu thư
[01:10:41] da là nếu có thể tra nhiều cách mà cha
[01:10:45] không ra được thông tin từ chính cái
[01:10:47] thằng đấy là sự thật này không đăng
[01:10:49] thông tin lên thì ra là người ông thấy
[01:10:51] ví dụ chiến tranh là nhất mà thôi có mẹ
[01:10:53] có tác thôi thường xuyên là nặng Nếu
[01:10:55] không tra theo là lớn lớn hơn đường ai
[01:10:57] cũng sai tất cả thứ trên Facebook không
[01:11:00] lại thăm chị em mấy ông có thể tạo một
[01:11:02] cái nick kiểu nick của bạn là người lớn
[01:11:04] đấy Có ảnh đại diện của bạn lớn đấy sợ
[01:11:07] tên giống hệt cản sau đây cũng lặp lại
[01:11:10] nick rồi bà Lạt sao kết bạn lại với với
[01:11:15] người người lớn đấy đúng không Sao lại
[01:11:16] bỏ đó Nick mới bị hack mà vẫn không
[01:11:20] không hỏi kiểu dáng nhờ chuyển tiền thì
[01:11:23] cứ hư đâu mà Mấy ông chỉ cần bà kìa
[01:11:26] Dạo này thằng thằng Long dạo này thế nào
[01:11:29] cả nạn đúng ạ à
[01:11:31] máy cạo râu không gặp đó thôi giặt giờ
[01:11:34] khỏi thăm nó cứ rồi bạn hẹn à Bây giờ
[01:11:36] nhà nó đang ở đâu rồi Nãy giờ xử thế giờ
[01:11:39] hết thông tin à
[01:11:46] Ừ cái đấy gọi social Engineering đấy là
[01:11:50] thí nghệ xã hội Em bé uống sữa đã hack
[01:11:52] não người già chứ không lẽ Hack bằng
[01:11:54] công nghệ mình nếu không sẽ lừa thường
[01:11:58] người lớn người ta nhẹ dạ cả tin lắm
[01:12:03] Tôi nói đúng không Sao sai được thì
[01:12:06] không hệ Đúng rồi à quên quên quên mình
[01:12:09] sẽ lấy lại hai cái này
[01:12:12] gì
[01:12:13] hả ông bảo ông không kết bạn người thân
[01:12:16] à
[01:12:17] ông chết đàn ông các bạn bè lắm thế thôi
[01:12:20] chứ khi ông Kiểu ni kiểu Clone ông không
[01:12:23] kết bạn bạn bè không liên quan bất kỳ ai
[01:12:25] hết thì chị
[01:12:33] à à
[01:12:40] anh không báo lỗi gì cả trong với vẻ dù
[01:12:42] thử xem nhé
[01:12:45] ừ ừ
[01:12:47] ở đó ra rồi này ông ngoại ra cái địa chỉ
[01:12:50] nhà mình đây này đại khái như thế Ok Bây
[01:12:54] giờ sửa quay lại bên bên này đặt thự mua
[01:12:57] sắm sản phẩm nó không ạ
[01:13:00] nhà máy sản phẩm trên chả khác biệt
[01:13:02] Nhưng tôi chỉ đặt những sản phẩm trong
[01:13:04] người phát hiện nhé
[01:13:05] đỏ như thế này nó sự có 2 sản phẩm đây
[01:13:09] là các bạn nên khó cái nút ở khi mà ở
[01:13:11] đây sẽ có nút là kiểu và không phải mỗi
[01:13:14] lúc đăng xuất nữa đúng không Xem giỏ
[01:13:15] hàng thì lại cái thế không ạ Các bạn sẽ
[01:13:18] ra sẽ chở hàng ở đây chẳng hạn
[01:13:22] I
[01:13:25] love you kept này à
[01:13:30] khi
[01:13:31] tăng số lượng lên ngoại
[01:13:34] Ừ thì ah bây giờ mình sẽ có nút đặt hàng
[01:13:37] ở dưới nhưng mà kèm theo điền thông tin
[01:13:39] người nhận nữa sao nó có thêm tổng tiền
[01:13:42] đấy đã có nút xóa giỏ hàng đấy nữa Ừ
[01:13:44] ngon thì đầu tiên cái tổng tiền ý đầu
[01:13:47] tiên mình hiển thị Cẩm Tiên đã thì cái
[01:13:50] cách để lấy tổng tiền được ra nó dễ thôi
[01:13:53] đầu tiên là mình cứ trước vòng lọc mình
[01:13:55] cho
[01:13:56] dụ là săn ăn bằng không ạ sau đó trong
[01:14:00] vòng lặp này mình sẽ xăm xăm bằng cái
[01:14:04] này đúng ạ nó sẽ như thế này
[01:14:07] anh
[01:14:08] ở đây nó là
[01:14:13] anh
[01:14:15] ở đây sẽ là kẻ vi rút đi đi sút bằng
[01:14:20] nhờ các cụ này
[01:14:22] xăm cộng bằng vi sốt
[01:14:26] ở đây là bản chất mình in lại virus ra
[01:14:29] thôi
[01:14:32] em xăm cậu bằng lấy sốt mà Thôi kết thúc
[01:14:35] kể thuê bồ mình sẽ có đây à tổng tiền
[01:14:38] hóa đơn này
[01:14:40] sẽ làm cho đồ ra săm là xong thì chuyện
[01:14:45] đô la lần trước cho mẹ chồng nhiều tiền
[01:14:47] như này ngoại t.ư
[01:14:52] Ừ đúng nhỉ đúng lúc Ok mà máy tính tính
[01:14:57] nữa rọi mình tính rồi sẽ đúng đấy
[01:14:59] Ok thì bây giờ mình sẽ điền thông tin ở
[01:15:02] đây thì bản chất điền thông tin nó cái
[01:15:04] form nó không ạ sẽ có bom này à
[01:15:07] thì mình sẽ điện à tên người nhận này
[01:15:12] phút đây đi sẽ tách này à
[01:15:18] thì mình sẽ là hình sẽ bây giờ mình phải
[01:15:22] tạo ra ta bây đã đóng loa mình sẽ tạo ra
[01:15:24] tao bay trước đã mình sẽ có hóa đơn chi
[01:15:27] tiết thì ok ở đây mang hóa đơn số lượng
[01:15:29] tôi đẩy xuống dưới này đấy thì ở đây sẽ
[01:15:32] có bảo Hóa đơn đã hóa đơn này mình sẽ
[01:15:35] gồm những gì mình sẽ của mã này mà khách
[01:15:38] hàng
[01:15:40] có tên người nhận là đường ngoại tên
[01:15:43] người nhận
[01:15:43] số điện thoại người nhận
[01:15:46] địa chỉ người nhận
[01:15:51] trạng thái trạng thái đơn là kiểu
[01:15:55] mới đặt nó nhọn đã hoàn thành đã hủy gì
[01:15:58] đó
[01:16:00] thời gian đặt ạ ạ
[01:16:03] Ừ đấy đại khái nhất là phải cơ bản những
[01:16:06] cái kiểu như thế này không ạ thì lại tên
[01:16:09] người nhận đi sẽ là
[01:16:10] nên VSIP Ơ
[01:16:13] không rõ tiếng anh ngắm tí Supper seat
[01:16:17] Ừ vợ
[01:16:19] ấy mẹo để mạng tra tiếng Anh nhanh đấy
[01:16:24] số điện thoại người nhận
[01:16:30] mình tôi nên chia sẻ nếu uống hơi nhiều
[01:16:32] mẹ mày tranh này nên đặt tên đội lại mẹo
[01:16:36] vặt chấm com
[01:16:37] ừ ừ
[01:16:49] Ừ
[01:16:54] anh sẽ là đặt hàng à
[01:16:58] khi hết pin Arsenal ở Việt Nam Á
[01:17:03] ở Phú phết nhỉ
[01:17:11] con gà nó vô set.tre cao đấy Đặt hàng mà
[01:17:14] à
[01:17:16] Ừ ok à
[01:17:23] Ừ nó sau đó thì mình phải thấy cái đây
[01:17:25] đã nghỉ thì chả là bây giờ
[01:17:28] chị sẽ hóa đơn này đây sẽ có
[01:17:33] à à
[01:17:34] thứ bảy cụt
[01:17:39] Có ai đi nè
[01:17:41] xe Honda
[01:17:42] Mỹ Tâm em
[01:17:46] ID này
[01:17:47] ờ ờ
[01:17:52] a
[01:17:53] neves shipper
[01:17:56] for Transfer
[01:17:59] HP shipper status ở
[01:18:03] Ừ cái này là
[01:18:06] ừ ừ
[01:18:10] ở
[01:18:10] thời gian đặt có thể thời gian tạo được
[01:18:14] rất ít
[01:18:16] đường này đặt ngay sau chuẩn nào chưa
[01:18:20] cài đặt như này
[01:18:21] cho mình cái này một là mình dùng Mà
[01:18:24] thường Lưu lại theo kiểu một là đến ham
[01:18:28] hai thăm xem từ các bạn ạ hết ham thì
[01:18:31] các bạn nhìn thấy ở đây nó sẽ là ngày
[01:18:34] tháng năm giờ phút giây còn cái tham
[01:18:37] stem này thì nó cũng kiểu như thế nhưng
[01:18:39] mà nó theo dạng là số dây từ năm 1970
[01:18:42] đến hiện tại thì cái số dây này đôi khi
[01:18:45] nó hợp lý là điểm mà là mình dùng cái
[01:18:48] hàm convert để đổi nó sang thứ Hiển mì
[01:18:51] hiển thị mình mong muốn cũng được hoặc
[01:18:55] cả cái này nó đến ham thì các bạn in ra
[01:18:58] luôn thì trong nó cũng cũng đọc được
[01:19:00] nhưng mỗi tội là nhiều người không thích
[01:19:02] bị in ra luôn nó ngày tháng năm giờ phút
[01:19:05] giây mình hẹn thường ai đọc nó là À nhầm
[01:19:09] năm tháng ngày giờ phút giây mình đọc
[01:19:11] thường ngày tháng năm hơn không ạ ạ
[01:19:14] Ô thế Mình nghĩ là các bạn nên chuyển
[01:19:17] qua dần một cái thang tap nhiều nơi
[01:19:18] thằng này dùng tham step hơn
[01:19:20] ạ sau đó thì con bớt nào Theo hiển thị
[01:19:23] theo thứ mình muốn thì nó hợp lý hơn
[01:19:25] Ừ cái này để tách này nhà để cha
[01:19:35] U20 này
[01:19:38] có ai
[01:19:40] k50id à
[01:19:43] tự động Ai đi tự động tăng cái xát Ớt
[01:19:48] này mình sẽ để quy ước nó không là 15
[01:19:51] thẳng cái gì đó dạng số rồi sau đó mình
[01:19:54] cứ vừa là hàng cốt được và các bạn tách
[01:19:57] hẳn dựa riêng em bạn nhưng mình nói ta
[01:19:59] các bạn nào nếu mà có nhiều sao tốt hơn
[01:20:01] mà các bạn muốn gửi cho chỉnh sửa sau
[01:20:03] Tết thì các bạn tách hẳn ra riêng thận
[01:20:05] bạn sẽ tốt nhé
[01:20:10] thì
[01:20:11] mình sẽ đây sẽ có bảo hóa đơn Chi tiết
[01:20:14] nữa
[01:20:17] chợ hoa cà thường là các bạn một là hóa
[01:20:20] đơn chi tiết đời thiếu hay các bạn có
[01:20:24] thể đặt khi mà một bảng trung gian giữa
[01:20:27] 2 3
[01:20:27] bảng này chúng là Node phố đắt thì các
[01:20:30] bạn thể đặt tên nó nó đầu của đắt cũng
[01:20:32] được như này cách để mà là tên mạng này
[01:20:35] Tại sao không phải bố decoder mà oder
[01:20:37] của đắp mà thường là nó sẽ đặt tên thứ
[01:20:40] nhất là không phải do bạn nào sinh ra
[01:20:42] trước bạn nào mà theo bạn theo khi bạn
[01:20:45] trung gian như thế này nó thường này
[01:20:46] theo bạn theo ạ xót thêm là chữ cái chứ
[01:20:50] nào làm năng trước thì đã lên đâu Kiểu
[01:20:52] như này bởi vì ví dụ là sự là bảng này
[01:20:55] trung gian giữa lớp sơn mờ với nhau rồi
[01:20:56] em ạ Nó sẽ cố trong màu áo đồ cho mày
[01:20:59] order customer kiểu như thế à các bạn sẽ
[01:21:03] gồm 3 cột
[01:21:07] chị sẽ là họ đờ ID
[01:21:11] customer ID
[01:21:13] Anh tên tên Mạnh trước này tôi về dưới
[01:21:16] rồi ai đi lại trong nhà dễ hiểu còn tin
[01:21:19] à
[01:21:20] anh lại không có cô nào tự động tăng đấy
[01:21:22] đâu nhá lưu lại này và riêng cái này thì
[01:21:26] à nhưng mình nói aid mình mình sửa bên
[01:21:30] order trước nhé riêng mình thì mình có
[01:21:32] cột nối cốt 10 đi mình phải nói đến bạn
[01:21:37] có xâm Mau mình sẽ bridgeview này hoa
[01:21:40] Các bạn nhớ về câu truy vấn trong SQL để
[01:21:43] tạo khói mãi không ạ Các bạn sử dụng
[01:21:44] enter để có bạn sửa còn đây mình đang sợ
[01:21:47] bằng tool thì các bạn thấy vậy dễ hơn
[01:21:49] mình sẽ chọn là tôi sẽ 10 đi mình sẽ nối
[01:21:52] đến cơ sở Mơ này nó sẽ tự động resort
[01:21:55] các bạn có cột nào Có thể nối thường là
[01:21:58] cô tự động tăng này thôi hỏi của email
[01:22:00] nhưng mình nói email nó unique nên nó
[01:22:03] được đề xuất giờ chẳng ai nối rồi đấy cả
[01:22:05] sẽ nối với cậu Út khóa chính thôi
[01:22:10] a tiếp theo and therefore thứ nhất là
[01:22:13] trước khi nổi trước khi nổi nhá thì các
[01:22:16] bạn sẽ phải tạo nó khai khóa chính thức
[01:22:19] đã
[01:22:20] à à khi tạ bạc tình yêu mình chọn được
[01:22:22] quả chính vì vậy những quên mất nó giả
[01:22:24] sử lỡ tạm rồi thì các bạn sẽ có ăn khái
[01:22:27] niệm enter table này app Viber kia này
[01:22:32] Make Me Đỏ Chắc ở nhà
[01:22:37] Xin chào không dưỡng đấy bạn sẽ có
[01:22:41] ch3 Mickey này
[01:22:43] nó thì với bạn order của đất nước ạ
[01:22:47] Chị sẽ có 2 cột khóa chính nó còn Oh
[01:22:51] Daddy và cơ sở 10 đi
[01:22:55] vì mình đã từng mình từng rảnh qua về
[01:22:58] cái vụ ạ Tại sao hai con này khóa chính
[01:23:01] rồi nhé nhưng mình không nhớ nó video ở
[01:23:03] đâu này các bạn rồi các bạn là nào mới
[01:23:07] xe mày có bạn phải xem lại từ đầu đến
[01:23:09] cuối đấy Đúng rồi mình khó mà lưu lại
[01:23:12] từng cái mục nhỏ một lắm và sự không có
[01:23:15] thời gian làm tất cả những điều đấy
[01:23:19] em về mình sẽ nối khóa ngoại này
[01:23:27] anh một cái
[01:23:29] anh nói khoác ngoài để ràng buộc thôi
[01:23:31] chức ra nó cũng không ạ Tại sao cô cho
[01:23:34] mới đi đấy Thôi xong tôi nhầm rồi
[01:23:38] Cái phải để nó là Bố đặt cái đi Anh nhớ
[01:23:43] hình như nãy giờ ngủ gật thì phải mấy
[01:23:44] ông chặn Nhắc tôi cả đậu xanh
[01:23:47] anh alo ngủ hết rồi đúng không
[01:23:54] phụ nữ yêu khám phá thấy nguội à
[01:23:57] Khi hết giờ rồi
[01:24:07] anh alo đâu hết rồi Kiểm tra đồ hết rồi
[01:24:10] ừ ừ
[01:24:12] Ừ nếu có gì nhắc rồi à mình tao ngồi
[01:24:15] nghe nghe thế kiểu đang đợi đến giây
[01:24:18] phút quấy để chia sẻ gì đó rồi
[01:24:20] Ừ
[01:24:21] Thế mấy ông thầy tôi say con này nhắc
[01:24:23] lại cả đậu xanh tôi cố tình xa đấy
[01:24:26] vì nó không anh em là nhắc thôi Tôi buồn
[01:24:29] quá
[01:24:31] hai
[01:24:32] lúa cái đoạn đấy có gì luôn đó tôi nói
[01:24:35] chậm mà thế Chứng tỏ ông vừa nghe Em
[01:24:37] buồn ngủ rồi
[01:24:44] ừ ừ
[01:24:45] anh
[01:24:46] nói chung là bây giờ mình mình cần điền
[01:24:49] toàn bộ Nếu phải tương tác nào mày mày
[01:24:52] không buồn ngủ còn không thì mấy ông
[01:24:54] nghe nhưng nghe giảng đạo mấy cũng chẳng
[01:24:55] buồn ngủ
[01:25:01] ừ ừ
[01:25:03] à à Bạn bị Xem thầy cô để bài giảng
[01:25:06] không ạ Hay
[01:25:07] anh giống như kẹo Tại sao thể dạng trong
[01:25:10] khi em đang buồn ngủ đúng không Thế lỗi
[01:25:12] rồi thầy ạ
[01:25:15] anh nói chung à Ok thì bây giờ mình cần
[01:25:18] lấy toàn bộ những cái điên trong form ở
[01:25:19] ngọn
[01:25:22] Ừ
[01:25:23] nhưng mà không phải mỗi thế mà Bởi vì a
[01:25:26] mình cần là này nó khó hơn tận thế mất
[01:25:28] cả bộ Hôm nay chị vừa nó nó yêu sớm nó
[01:25:32] hỏi rất giận 23 nó order vào đồ đắt
[01:25:34] ngoại thì bây giờ để để tôi nói không
[01:25:39] hỏi mấy ông mà Mấy ông đi ngủ nhé em
[01:25:43] xe máy béo nhìn kỹ lại ở bên này
[01:25:47] Ừ nó nhìn lại cái Trang
[01:25:50] Trang do hàng đầu đúng không Thì mấy ông
[01:25:52] nó lại rồi đó là bây giờ khi mình đi rớt
[01:25:55] vào thì mình phải in rất là bao nhiêu
[01:25:56] bạn và ờ
[01:26:00] I Insert vào bao nhiêu Bảng và mỗi bảng
[01:26:04] đấy có bao nhiêu bạn đi Thiên xuất và
[01:26:06] a research
[01:26:08] vào bao nhiêu bạn ạ
[01:26:12] ở mỗi bảng
[01:26:14] sẽ có bao nhiêu bạn đi ừ
[01:26:19] hình ảnh
[01:26:24] ở đây là cái hôm đặt hàng của tôi không
[01:26:27] ạ
[01:26:30] khi cha cha trả lời trả lời trả lời à
[01:26:36] em trả lời tình ngủ nữa
[01:26:39] Ừ tự nhiên ông kia hỏi về Unity vậy thôi
[01:26:42] Chả biết Unity cái gì cơ
[01:26:44] À có rồi ông ấy thấy chứng rõ mày ngủ
[01:26:47] gật rồi mẹ vợ tôi kết nối nối khóa mà
[01:26:51] hết rồi
[01:26:54] em
[01:26:55] trả lời trả lời nào Alo
[01:26:58] anh nói 90 ông rồi cũng
[01:27:00] b8200 kia ngủ luôn đó
[01:27:03] bà bà
[01:27:06] để đáp án ở giờ rồi
[01:27:13] cho muối vào mùa bạn đi thế cũng là giờ
[01:27:15] rồi
[01:27:18] rất nhiều bạn nhiều bạn là cái gì
[01:27:22] em không ở đây có cụ thể đấy
[01:27:25] sau khi mình đặt hàng nhé mình sẽ usopp
[01:27:27] vào bao nhiêu Ba Đó là những bản à Nói
[01:27:30] rõ ra đó là những bảng nào
[01:27:35] và mỗi vàng sẽ có bao nhiêu bạn ghi cụ
[01:27:39] thể mỗi bạn không ạ
[01:27:41] bà cụ thể
[01:27:43] mỗi bạc sẽ có bao nhiêu bạn đi
[01:27:49] U23 order 1 order Black n bạn chưa nói
[01:27:54] có đúng không ạ phải thế mới chuẩn em
[01:27:58] Thực ra cụ thể ở đây không phải đâu nó
[01:27:59] lấy có mỗi hai sản phẩm thôi nó sẽ chỉ
[01:28:01] giữa hai bản ghi thôi ông ạ
[01:28:04] à à
[01:28:06] anh nói sốt 2 bạn nó là bảng order Đông
[01:28:10] ạ order cô đắt bạn order thì mình chỉ
[01:28:14] đến suốt một bạn ghi đó mình tạo một hóa
[01:28:16] đơn thôi không ạ một hóa đơn thôi nhưng
[01:28:19] mà một hóa đơn này sẽ có nhiều sản phẩm
[01:28:20] đông lạnh có 2 sản phẩm bị tất cả có hai
[01:28:23] bạn ghi bởi vì nó sẽ ra mã hóa đơn là
[01:28:25] cái mình sẽ lại đây thôi ông ạ Mình sẽ
[01:28:29] Insert đấy có mã là một mã hoặc mã hóa
[01:28:32] đơn là một Nhưng mình có tận 2 sản phẩm
[01:28:34] sản phẩm Một và sản phẩm hay là em ạ sẽ
[01:28:37] lặp lại như thế này không ạ xong nó lấy
[01:28:39] đúng với số lượng đã đặt như thế này
[01:28:41] Insert và ngoại 31 nha Chừng nào ông ạ
[01:28:44] Thế thôi
[01:28:47] Ê mày ông Vợ nhỉ Mấy ông buồn ngủ quá
[01:28:49] tỉnh lại đi Alo
[01:28:53] Ừ tôi không phải vừa dậy mã tấu hài ông
[01:28:56] được thì cái đoạn này không có gì ở đâu
[01:28:58] phải cả
[01:29:00] hết miếu có thể trách tôi vì cái đoạn
[01:29:02] này không có gì để tấu hài ông à mà họ
[01:29:05] có phải là để cột nhà đâu đúng không ạ
[01:29:07] Không phải tấu hài dục được
[01:29:09] thôi chị cố dạy dễ hiểu thì tao không để
[01:29:12] vừa dậy và hai nước sẽ
[01:29:15] say quá
[01:29:18] Nói chung là lấy rồi những thông tin này
[01:29:20] ông ạ Đấy những cái mình lấy được à À
[01:29:24] quên quên quên quên này quên đấy thì ở
[01:29:26] trước trước khi mình lấy được thông tin
[01:29:27] đấy thì như giờ anh nói đó ạ hành khách
[01:29:30] hàng hải đăng nhập rồi ông ạ Mình cần
[01:29:32] cho điền lại toàn bộ thông tin này để
[01:29:34] khách hàng đỡ phải điện nữa thì mình làm
[01:29:37] nha Thì mình sẽ lấy thông tin của cái
[01:29:39] thằng đang đăng nhập bằng cách lấy từ
[01:29:42] xuân này lấy từ season ID của nó sau đó
[01:29:45] kết nối này đây để mình có thể thông tin
[01:29:47] của nó sẽ đây này Ai đi khách hàng sẽ
[01:29:51] bằng và season II Có ai đi này sau đó
[01:29:55] thì lại phải truy vấn vào
[01:29:59] lại phạm truy vấn vào à Tao bây thôi Để
[01:30:03] lại thông tin khách hàng
[01:30:05] không Đừng có lưu lại thông tin khách
[01:30:07] hàng này trong rất xinh nhé Thực ra tôi
[01:30:08] bảo không nên hẳn lưu lại rồi đấy thì
[01:30:10] được cái này thì cần lấy lại chị đấy một
[01:30:12] lần thôi cứ sợ mở Where ID bằng id này à
[01:30:23] ừ ừ
[01:30:35] Ừ tôi cứ cho Điền luôn nhé Thực ra các
[01:30:39] ông có thể làm theo kiểu là à
[01:30:43] em có cái nút có nút ở đây nhanh được
[01:30:46] một là điền hay có nút chết bao này hoặc
[01:30:49] giấy thông tin người đang đăng nhập cái
[01:30:53] để phải điên này nữa cũng được có một
[01:30:55] cách
[01:30:58] ở đây này
[01:31:00] a
[01:31:00] phone number
[01:31:03] Anh ở Đại Nghĩa mà đây nữa Thế mình sẽ
[01:31:06] phải là phone number VSIP ơ cho nó thống
[01:31:09] nhất
[01:31:12] anh không gì phải dạ nối à quên quên
[01:31:15] quên thiếu Zalo
[01:31:17] vì tội bắt đầu buồn ngủ bằng máy
[01:31:20] lẽ do mấy ông ấy không phải do tôi đâu
[01:31:22] nhé ạ
[01:31:24] Em nói như này ok chưa ạ
[01:31:29] Ừ đấy Sau đó thì mình mình có thể mình
[01:31:32] sửa lại đúng ạ Nhưng thể sửa lại là cho
[01:31:35] bạn này thôi đúng ạ thay đổi này đi nghe
[01:31:39] sẽ nặn không ạ hồ chí minh rằng
[01:31:43] hãy tha
[01:31:45] ở Hòa Minh dưỡng nguyện được đúng không
[01:31:47] ạ
[01:31:49] Ok ở đây lấy hết về này mình vỡ lại con
[01:31:54] ếch để đóng Bạn có khách vào
[01:31:57] Anh nhắn nhầm con ếch ba này
[01:32:01] sau đó thì mình sẽ có câu SQL Insert
[01:32:05] into their à
[01:32:10] à à quên quên quên quên ngày này quên
[01:32:14] Mấy ông cái này một cái đó là
[01:32:17] cái này Thực ra là cái tao bên mình nên
[01:32:20] thiết kế nó vẫn tức nổi cơ bản các bạn
[01:32:23] đã điểm gì
[01:32:25] ở đó là mình không có cột ở Tâm Tiền ở
[01:32:29] trong order để lấy tổng tiền ra cứ mỗi
[01:32:32] lần lấy tổng tiền ra thì mình sẽ phải
[01:32:34] nói nô đó xong rồi nhân vào để mở ra em
[01:32:38] thường là tôi dậy ở sinh viên Tôi thường
[01:32:41] này thêm một cột của Tổng tiên đây tôi
[01:32:44] sẽ thêm một cột của Cẩm Tiên nhé
[01:32:46] ờ ờ
[01:32:49] a Toto Pride điện ảnh
[01:32:53] xe tải phim sẽ đẩy + Flash đi
[01:32:59] khi cuộc tổng tiền này bạn chất là mình
[01:33:01] sẽ
[01:33:02] mình mình sẽ tính lại để toàn bộ đơn
[01:33:05] hàng này sau đó mình ra cục tổng tiền
[01:33:07] đồng ngoại mình lưu nó lại để những lần
[01:33:10] sau khi xem lại đơn này thì không cần
[01:33:13] phải tính lại nữa họ sẽ nó sẽ tính một
[01:33:16] lần thôi Vậy mỗi lần tải lại trang các
[01:33:18] bạn lại phải kết nối lại phải nối hai
[01:33:21] bạn ấy với nhau ở tính lại thì nó bị
[01:33:23] nặng ra nếu hình Dung ạ thì mình nên
[01:33:27] tính một lần thôi vì rõ ràng là đơn đơn
[01:33:29] đã đặt rồi thì gần như chẳng đổi thay
[01:33:31] đổi thay đổi cái tổng tiền chẳng còn như
[01:33:33] cháu đã thay đổi cả Không ạ đi cho
[01:33:37] nên là bây giờ sẽ không Insert được mấy
[01:33:40] ông mình thấy Bây giờ Bây giờ không đi
[01:33:42] sớm được mình đã làm tổng tiền này phải
[01:33:44] tính đã đúng không ạ Có ông thì sẽ bảo
[01:33:46] là tôi đã ký kết một tí nhé Có mình sẽ
[01:33:50] bảo là nếu thế thì em có tổng tiền đây
[01:33:52] rồi em Chỉ còn truyền cái này qua xin mà
[01:33:56] không đặt hàng em chuyển qua thôi thế là
[01:33:58] thế càng sai một việc mình phải lấy tổng
[01:34:01] tiền từ season mình tính toán ra chứ nếu
[01:34:04] mà ông có một cái vai một cái ô input ở
[01:34:06] đây này xong rồi có cái tổng tiền đây
[01:34:09] thì khách hàng ẩn ẩn concho xem được cái
[01:34:12] tổng tiên đấy có cò chuyen.com cũng sửa
[01:34:15] cái tổng tiền đấy hạng âm nhạc đặt hàng
[01:34:17] thì hoa cái hóa đơn đấy ông phải trả
[01:34:20] tiền đó nó không ạ
[01:34:23] Ừ thế thì nên là phải toán tổng tiền lại
[01:34:25] kêu gì mình phải tính ở trên bác em đừng
[01:34:27] có ra tổng tiền đâu mà mình sẽ không xử
[01:34:29] lý ở có làm sai được
[01:34:31] thì bây giờ mình sẽ nói chung và bây giờ
[01:34:34] mình có Sistar đi làm việc về với thí
[01:34:38] sinh mà mình sẽ có cát bằng đũa season
[01:34:41] tại Cáp này Đấy sau đó thì mình cứ phối
[01:34:45] cả đây Các này
[01:34:49] a s d shakur Lấy từng thẳng đi
[01:34:54] Ừ mình bạn chất là mình có một cái tổng
[01:34:57] đấy đi Total file lúc đầu bằng 0
[01:35:01] xe ô tô Prime nó sẽ cộng bằng lên tăng
[01:35:05] dần lên chị mà X con tê tê
[01:35:09] nhân với x tại file sở nào để mình sẽ ra
[01:35:14] tổng tiền thôi đó Bên mình có tổng tiền
[01:35:16] rồi bây giờ mình Mỹ sơ vào đây
[01:35:19] ô coffee house Insert into all those
[01:35:23] đi sẽ có
[01:35:26] add id id mình để tự động tăng nói đúng
[01:35:30] thì
[01:35:30] mình sẽ có à
[01:35:35] a customer lại đi này có sợ mai đi à
[01:35:41] à à
[01:35:43] Ừ tôi có cái mẹ mày ngang cho mày không
[01:35:45] biết tí nữa nhé em ở nó đầy ở nice này
[01:35:48] cho mình có cái này nó nhanh
[01:35:51] Tôi có người lười mà ở
[01:35:55] a nhớ đương nhiên là có cái dấu nháy này
[01:35:58] thì không phải đội nháy rồi ông mấy vợ
[01:35:59] nó không thể Bôi đen nó dỡn consume hát
[01:36:02] rồi nó vplayer đúng xóa đi nhanh được
[01:36:06] Ừ Ok rồi đấy tôi có ba lô nó
[01:36:09] Khi nào có cái này à
[01:36:12] a modern tất cái
[01:36:14] à à
[01:36:15] ba ngày là xong
[01:36:17] ở ngõ
[01:36:21] Ừ ok Ở đây có mấy ông thể tha thứ nhất
[01:36:24] là cốt mời đi của mình chưa có Xuân Mai
[01:36:26] đi mình bạn chất là đu assistant Tại ai
[01:36:30] đi không ạ tiếp theo namely shipper rồi
[01:36:35] Fully shipper rồi arrecife
[01:36:39] thiếu đồng loại
[01:36:41] này đây Atlas này tiếp theo status
[01:36:45] status không có đúng không ạ sa tế ớt ở
[01:36:49] đây như mình vừa nãy nói mình là sự mình
[01:36:50] cái nước không là mới đặt đi những chú
[01:36:53] thích đây mới đặt đó như này
[01:36:56] a tiếp theo Total Price rồi Crystal
[01:36:59] method Mình chưa có mình sẽ góc khuyết
[01:37:01] tật Tắt ở đây mấy ông có thể cho Nếu
[01:37:05] không có thể không điền cái cột này mình
[01:37:08] bé ông cho nó sẵn ở trong dp cũng được
[01:37:10] nghĩa là kiểu giá trị mặc định luôn cũng
[01:37:13] được hoặc bé ông có thể dùng hàm nào nha
[01:37:16] để lấy thời gian hiện thoại từ bên TP
[01:37:20] cũng được nhưng mà mình thấy có nhanh
[01:37:22] hơn sẽ làm theo cách này bị sẽ ấn
[01:37:27] thì mình sẽ quy ước luôn trong đây b là
[01:37:29] default là cô đơn tham stem nhà được lấy
[01:37:32] luôn thời gian hiện tại chúng mỗi lần
[01:37:34] mình khi rót mình không điền vào cột mày
[01:37:36] thì nó sẽ lấy theo thời gian hiện tại
[01:37:37] cũng nhanh
[01:37:41] ở ngã tư nhân có chấm phẩy đây
[01:37:44] à Dạ Mình Sai rồi Sai rồi à
[01:37:47] anh xem lại nhé status này tôi quan có
[01:37:51] phải đúng đấy
[01:37:52] Ừ ok
[01:37:55] em thấy mình đang dậy rất à từ từ và cố
[01:38:00] chỉ ra các bạn vài cái đấy ông ạ
[01:38:03] Tối đoạn nào tối ưu không ạ
[01:38:07] I bami thử đai câu truy vấn ra
[01:38:10] các bạn xem nha
[01:38:13] đó nó sẽ như thế này
[01:38:16] à Có sao mai đi là năm này tên mình thử
[01:38:20] in xuất chai vào trong này đã sẽ bị sốt
[01:38:22] được không
[01:38:28] ở đó anh xuất thành công nó sẽ thành
[01:38:31] công mình cứ tạm xóa đi á ấy đã
[01:38:36] anh ở đây mình mình một lúc và mình muốn
[01:38:38] đi xa tận hai vàng cùng lúc sau đó Xóa
[01:38:40] luôn cả giỏ hàng đấy Đặt hàng rồi không
[01:38:43] chuyện chở hàng vẫn còn không ạ
[01:38:50] a a a
[01:38:52] anh ở đây mình sẽ in xuất luôn cái rọ Hà
[01:38:57] ý thì cái Yên số giỏ hàng ngày thì bạn
[01:38:59] chất là nó hơi bị có người vấn đề này để
[01:39:02] không để ý nhá nó có đây đi tất cả chỉ
[01:39:05] là mình phải lấy đúng vào đây đi mà Mình
[01:39:07] vừa mới như giấc
[01:39:08] em ở trên này lấy nó về đúng ạ thì có
[01:39:12] một cái trường hợp này có thể xảy ra này
[01:39:14] đó là nhiều người cùng đặt cái giỏ hài
[01:39:18] cùng lúc
[01:39:20] anh nhịn bài toán để ăn nhiều người
[01:39:23] không phải cùng tỏ hàng mà ý tôi ở nhiều
[01:39:25] người cùng top 1 cùng một lúc thì nếu mà
[01:39:27] ông lỡ vừa mày Insert cái thằng này vì
[01:39:31] rất là này
[01:39:33] à mà không lấy mắt lại salad mắc ID của
[01:39:38] thằng mắc lớn nhất thì thế Đàn ông vừa
[01:39:40] vì đáp đúng không ạ của cái
[01:39:43] có cái order đấy thì đôi khi là nó sẽ bị
[01:39:47] nhầm sang ai đi của cái thằng mà nó vừa
[01:39:51] đặt cùng lúc với ông ở một ở một nơi
[01:39:54] khác nhận nó cũng đã thế thì mắc này đôi
[01:39:57] khi nó 01
[01:39:59] cho nó hiểu thì thôi em ạ này Shake Mac
[01:40:03] ID này
[01:40:04] for dead
[01:40:07] Ừ để để lấy được ID lớn nhất không ạ
[01:40:10] khi mẹ bị ốm hiểu họ lấy order phải đi
[01:40:14] được truyền sang Idol vô đắt này nhập
[01:40:16] vào truyền là màn không ạ
[01:40:18] Ừ thì bây giờ có cách đó là mếu thể thêm
[01:40:22] đoạn quay ở đây mời đi Bằng chính cái
[01:40:25] thằng mà mình
[01:40:27] mình vừa mình đang bật cái thằng nào thì
[01:40:30] mình sẽ mắc thì nó sẽ gần như nó sẽ nó
[01:40:33] đúng hơn chứ Khi ông ông khách hàng này
[01:40:35] còn tạo ra 2 trang thời trang để mà
[01:40:39] cùng cùng đợt hàng nữa thì có khi còn
[01:40:42] vấn đề nữa
[01:40:47] ib1 Mẹ của tôi thôi Nếu không có thể
[01:40:50] chơi mẹo chắc cú hơn và mày ông sẽ sẽ
[01:40:54] ngay từ lúc đầu mày ông salad mắt trước
[01:40:56] như và mấy ông không cho ai đi tự động
[01:41:00] tăng mấy ông sẽ không cho ai đi tự động
[01:41:02] tăng
[01:41:03] à Mà ông salad mắt trước sau đó mới ông
[01:41:06] y-shirt thẳng vào trong dp theo 10id
[01:41:09] cũng được theo kiểu như thế này nhá thì
[01:41:11] tôi chỉ em với ông dễ hình dung nhé Mấy
[01:41:15] ông theo cách nào có hay có 2cách nhé
[01:41:17] Tôi sẽ luôn đời suốt ông những cái hướng
[01:41:20] giải quyết bài toán này mấy ông hình
[01:41:22] dung cái tư duy lập trình thế tôi đang
[01:41:24] dạy không bản chất vẫn là tư duy lập
[01:41:26] trình chứ không phải là dạy cho ông ấy
[01:41:28] Ông chỉ biết cốc thôi Biết cốt thôixem
[01:41:30] thêm sửa xóa mấy ông ấy biết rồi ông ạ
[01:41:32] Tôi đang dậy mấy ông những cái khó nhất
[01:41:33] này chỉ là thứ duy lập trình đó là
[01:41:38] tác giả phở
[01:41:40] niệm đầu tiên thì trường hợp một cách
[01:41:44] một đi cách 1 Shake mắc ID từ đây à Ừ
[01:41:51] nếu mà chỉ lấy ngày thôi ông ạ thì nó sẽ
[01:41:54] có vấn đề là
[01:41:56] nếu
[01:41:58] người dùng
[01:42:00] cùng đặt hàng
[01:42:04] anh một lúc cơ à
[01:42:07] ký xuất cùng lúc trở lại thì cái mắc ai
[01:42:12] đi Mắc AD này chưa chắc là đúng ngay đi
[01:42:14] của cái thằng mà vừa mới ăn rất vào nó
[01:42:17] ID của cô đơn khác của cái thằng B em ạ
[01:42:20] thì khi các bạn Insert vào trong order
[01:42:23] codes
[01:42:24] đi theo cái others đi đấy thì nó là sai
[01:42:27] ông ạ anh nó say nên là mình vừa bảo là
[01:42:32] các bạn một là các bạn sẽ well có số 10
[01:42:34] đi nữa những cái trình diễn thảm đang
[01:42:36] đặt đơn Nó có vẻ ổn hơn vì nó vừa mới
[01:42:39] đặt mà đúng ạ
[01:42:41] ở đấy đến trường học một con cá trường
[01:42:44] hợp cách cách giải quyết một khoảng cách
[01:42:47] giải quyết hay đó là các bạn sẽ selec
[01:42:50] này ngay từ lúc đó các bạn sẽ cho cái
[01:42:53] sonax này ngày thứ đầu trên này
[01:42:55] đang ở chế này chẳng hạn như này không
[01:42:58] cần que cái gì đó nữa sau đó thì giờ sự
[01:43:01] ra đời một cái ID điều đó
[01:43:04] em lấy từ cái đoạn này ra một cái gì đó
[01:43:07] cho các bạn sẽ in xuất thẳng vào trong
[01:43:08] này kèm theo cái đi luôn như thế này và
[01:43:12] ở và ở dưới này các bạn sẽ dùng một này
[01:43:15] đi đấy in sớm mà sao đầu blog cũng được
[01:43:20] Ừ cũng được các bạn không để cho cột ID
[01:43:23] là tự động tăng nữa có bạn sẽ in such ai
[01:43:25] vào
[01:43:26] Ừ Thì Mình thấy cách này nó hợp vị hơn
[01:43:28] cái này nó sẽ luôn đúng
[01:43:30] Anh ta sẽ luôn đúng
[01:43:35] anh bởi vì là khi mà selects mắc này nếu
[01:43:38] là sự ý xuất và nó bị lỗi là sử vẫn có
[01:43:41] hai người đặt cùng một lúc thì sẽ lên
[01:43:43] mắc này sau đó ý rất là bị lỗi ông ạ thì
[01:43:46] mình chỉ thì chắc chắn là một hành lỗi
[01:43:48] một hàng thanh toán được còn hơn việc ạ
[01:43:50] Thằng này đặt đơn sản phẩm của thằng này
[01:43:53] nhảy vào đơn thằng kia nó hơi sai đấy
[01:43:58] mấy ông ấy giờ có tiền ngủ hôm nay bây
[01:44:00] giờ một tiếng bốn phút 23 phút rồi thì
[01:44:03] cũng hơi dài bố mày hơi dài hi vọng mấy
[01:44:05] ông Lễ vẫn tịch
[01:44:09] Ừ thôi thì chắc là tôi áp dụng bằng cách
[01:44:11] đơn giản hơn cho mấy ông dễ dễ hình dung
[01:44:13] nhé
[01:44:14] anh không bị ngủ hết rồi
[01:44:17] thì mình sẽ có đây là à
[01:44:23] à à
[01:44:31] cả hai
[01:44:33] ông kia động viên rồi à
[01:44:39] Anh
[01:44:43] ấy thấy gian hai lớp vải dù chẳng hết à
[01:44:52] chú ý bạn là cái ngày đúng không cái này
[01:44:55] thật ra như mình nói Thật ra cũng cũng
[01:44:57] được nhưng mà cũng có trường nào xảy ra
[01:44:59] thằng cu Summer đấy nó bằng một lí do
[01:45:03] thần thái muốn chơi trò đấy cả là nó
[01:45:06] cùng cùng Đăng nhập cùng một nick của
[01:45:10] thận hai máy là Nhạn thì sẽ ăn nó khác
[01:45:12] mà bọn Sơn vẫn khác nhé thế là cùng một
[01:45:16] nick nhưng mà vẫn tạo ra 2 phiên giữa
[01:45:18] rừng nó cung đặt thì nó sẽ nó sẽ cái mắt
[01:45:22] AD vẫn có thể có vấn đề thì các trường
[01:45:25] hợp hai nó sẽ đúng hơn hộp 2 thì tự
[01:45:28] nhiên mình nói là có trường hợp mà hai
[01:45:30] hàng cúi sát tại một thằng bị lỗi rồi ạ
[01:45:32] thì khi mà bị lỗi thì mình có thể bắt
[01:45:34] được cái lỗi đấy mình tăng ai đi lên đấy
[01:45:36] nó sẽ không đổi nữa ừ ừ
[01:45:39] khi con gái trường hợp này thì vẫn có
[01:45:41] thể sai trường hợp này vẫn thể sai ý
[01:45:45] e-mail web cho bị spam thời giảm hay quá
[01:45:49] cơ hội tôi không cần cái lời đâu mà ông
[01:45:53] ngồi học đi à
[01:45:56] em
[01:45:58] tắt đi à
[01:46:00] Không nhớ cái này không ạ Mình lấy thử
[01:46:03] cái dọn hàng ra mình sẽ cỏ cô đã phải đi
[01:46:06] ở đây và đây ít này nó sẽ có con Ti
[01:46:12] Em có biết were D băng
[01:46:15] research into your therefore I
[01:46:27] ừ ừ
[01:46:32] à à
[01:46:34] ừ ừ
[01:46:36] I
[01:46:39] want it I mình sẽ lấy à
[01:46:41] Bạn đôla x tại quantity
[01:46:46] và bây giờ chỉ đơn giản nhưng sẽ truy
[01:46:49] vấn mà thôi
[01:46:52] nếu không sẽ thấy có bao nhiêu sản phẩm
[01:46:55] trong cái rọ Hà mình sẽ in giấc 7 ngư
[01:46:57] dân và muộn muộn một là mấy ông sẽ đi
[01:47:01] xuất cảnh ngay nó sẽ bị Hơi nhược điểm
[01:47:03] một tí ạ và sẽ mất mấy như lần câu truy
[01:47:05] vấn bằng cách giữa hai ở mấy ông có thể
[01:47:07] chơi được Kiểu là nối chuỗi cũng được nó
[01:47:10] làm gì ở tạo một câu Insert ở trên này
[01:47:11] sau đó thì nối chuỗi value value thêm
[01:47:14] vào sau đó của cô ấy chạy một thể một
[01:47:17] cái quay đấy cũng được thì đỡ phải có
[01:47:21] bao nhiêu lần sơ nhé mình em dụng cách
[01:47:23] đơn giản để nó như này thôi Mỹ Tâm
[01:47:25] Chuyện xót nha Em tải lại trang
[01:47:28] xin lỗi à
[01:47:29] ờ ờ đầu tiên xem lỗi này dòng 23 đổi gì
[01:47:34] Ừ cái này đã
[01:47:36] u-mac ID for mother always customer ID
[01:47:41] đang báo lỗi cái câu câu truy vấn này có
[01:47:45] vấn đề thế nên là cái cái con ếch này nó
[01:47:49] không chặn không trả về được giá trị khi
[01:47:51] muốn thì sẽ đang ở đây ft out chạy trai
[01:47:55] đã
[01:47:56] à à
[01:48:09] khi trở về ngồi nghỉ trở về mà
[01:48:14] - xuất quả lại a rồi mình phải đi sơ ta
[01:48:18] xin lỗi xin lỗi mình chuyên shop mà sao
[01:48:21] không được để Insert cả rồi sao sẽ lách
[01:48:25] này à
[01:48:27] à à
[01:48:29] anh vẫn lỗi vòng 21
[01:48:33] I Connect này Ừ nhưng mà nó sao
[01:48:40] ừ ừ
[01:48:42] hai anh em nhà tôi nhầm hàm Tôi xin lỗi
[01:48:45] Tôi nhầm Hà An
[01:48:47] ừ ừ
[01:48:51] à à
[01:48:54] anh không báo lỗi nữa không có lỗi không
[01:48:56] nghĩa chạy được không ạ Cứ thử đã
[01:48:59] a research Ok này Total Price có vẻ ổn ở
[01:49:03] đây wonderflex đó Gold rồi đó ok Bây giờ
[01:49:09] mình chỉ cần đóng kết nối dẫn tả
[01:49:12] xóa cái
[01:49:14] xóa xin thôi mình sẽ ăn xét
[01:49:17] và season tại khác để xóa đi
[01:49:21] bởi vì bây giờ cũng mỗi mình tả lại sang
[01:49:24] nói in sẽ lại phát nữa này các bạn thấy
[01:49:26] nó lại thêm một hóa đơn nữa Ngại thế
[01:49:28] không được không ạ khi ở mình thanh toán
[01:49:31] này xong mình sẽ phải header quay trở
[01:49:33] lại trang cậu thông báo thành công những
[01:49:36] cái gì đó tôi thì tự điều hướng với
[01:49:39] trang chủ và cả trang người dùng để mà
[01:49:41] người dùng có thể xem lại đơn vẫn thứ
[01:49:43] sau không ạ
[01:49:45] anh nói chung là bây giờ chạy lại thì
[01:49:47] các bạn sẽ xin lỗi vì rõ là sai rồi ông
[01:49:50] ạ
[01:49:52] ở nhà xe lửa hành vừa nó chống nóng lỗi
[01:49:55] này cũng chưa tôi phải làm vài đoạn này
[01:49:57] khi đó đại khái như thế
[01:50:00] trong bộ hôm nay à
[01:50:05] Khi bữa hôm nay mấy ông thấy à thực ra
[01:50:07] nó rất là dài thì ra nó tk cốt ngắn
[01:50:11] nhưng mà tôi phải giải thích rất kỹ rất
[01:50:13] nhiều thế thành ra nó dài như này à
[01:50:17] à à
[01:50:18] Ừ
[01:50:19] Cái vụ mà shopee đăng nhập Hai thiết bị
[01:50:23] hay lượng chữ N thiết bị nó cùng một dầu
[01:50:24] 21 vì cái giỏ hàng này nó lưu lại trên
[01:50:26] sốc trên đó Bây này do mà ông vào bất kỳ
[01:50:30] Ừ cái thiết bị nào mấy ông nhà vẫn xem
[01:50:34] được cái giỏ hàng giống nhau vì nó lừa ở
[01:50:36] trong đây bê được ở trong đây còn mình
[01:50:39] đang dậy luận chung xuân thành ra là cứ
[01:50:42] một thiết bị là y rằng là một cái giỏ
[01:50:44] hàng mới giờ hàng khác để mở mình mở
[01:50:47] bằng danh này xinh Em do hàng nữa ngoặt
[01:50:49] sang nhà cậu khi mà cùng một tài khoản
[01:50:53] mà cùng cùng bạc hàng ấy thì cũng có
[01:50:56] trường hợp mà kiểu tạo ra order 2 đ** đồ
[01:51:00] và hai kéo đời đi Đấy nó thì chúng ta
[01:51:03] cái mắc godaddy nó sẽ có một cơ mà không
[01:51:06] ạ hàng ra thì thành em một order sẽ có
[01:51:09] nhiều sản phẩm có đời kia con cho đời
[01:51:12] còn lại không có sản phẩm nào Tất cả
[01:51:14] cũng chắc là không có trường hợp người
[01:51:16] dùng cùng làm thế đâu ông ạ
[01:51:19] Ừ Chắc không có đâu không ạ Nhưng mà
[01:51:22] thường là thật ra không ai chơi xin kẹo
[01:51:24] ngay cả như mình nói nghe cái bài toán
[01:51:26] mình chỉ ăn nói ở mức giải quyết được
[01:51:29] vấn đề Nếu giờ sự các bạn ở thắc mắc gì
[01:51:31] thì nó có gửi do gì không ạ
[01:51:37] Hình như tôi đã nói thì tôi đang dạy mấy
[01:51:39] ông ạ tư duy lập trình chúng mày dạy mày
[01:51:41] không về cốt không ạ Vì cốt để thờ ca
[01:51:44] mấy ông thật ra mấy ông thấy Cốt nó rất
[01:51:47] là ngắn và cũng là mấy ông phải có cốt
[01:51:49] này về là nó ra trong web bán hàng rồi
[01:51:51] nhưng là Nhưng mà nếu không có tư duy
[01:51:53] thì mày ông không thể phát triển được
[01:51:55] thêm một cái nữa không ạ
[01:51:59] à à
[01:52:00] Ừ đúng rồi chúng ta là không cần nó tin
[01:52:03] vẫn thể đạt được ha noisinh Ở đây chỉ
[01:52:05] đơn giản là như hồi trước thì mình bạo
[01:52:08] loạn để mà tránh việc là người dùng tạo
[01:52:11] giác nhiều đặt đơn quá thì mình có cho
[01:52:14] đăng ký có về đỡ hơn tí ngoại và lẫn cả
[01:52:18] là để cho có khái niệm mà khách hàng Bạn
[01:52:21] xem được đơn hàng cũ đã đặt ông ạ Có bên
[01:52:26] khách hàng đăng nhập đăng ký do nó chuẩn
[01:52:28] chỉ có một cái trang web đó nhé
[01:52:34] à Có chứ thêm Phong địa chỉ rồi mà mày
[01:52:38] ông quen à
[01:52:39] đã có lãi thông tin địa chỉ người nhận
[01:52:42] rồi
[01:52:50] à à
[01:52:51] Ừ đúng rồi Cái này gần như sởi ép lắm
[01:52:53] Đăng ký
[01:52:54] đặt ở thì ra cũng có khá nhiều trang web
[01:52:58] vì thế mà cho thêm sản phẩm vào giỏ hàng
[01:53:00] nó cứ thứ xong đến cuối thì vẫn bắt đăng
[01:53:03] ký mới cho thanh toán mà à
[01:53:10] Ừ Từ hôm nay còn định chia sẻ thêm người
[01:53:12] nữa cơ ngoài tôi chia sẻ là được ạ chẳng
[01:53:15] ở đây tôi sẽ nốt một cái giải trí mấy
[01:53:18] ông này Thế có hôm trước có một ông hỏi
[01:53:21] là
[01:53:22] hôm trước anh cài cái gì để mà chạy hiển
[01:53:25] thị điều cái trang medium thì tôi hôm ấy
[01:53:29] tô của nó chỉ cách mấy ông mở cái IP
[01:53:33] config Lên Điểm IP sửa cái DNS của nó để
[01:53:38] mà vào được cái trang màu trời xanh mà
[01:53:41] Việt Nam đang bị chặn không ạ trạm địa
[01:53:45] chỉ IP Ừ thì mình sẽ đổi DNS sang của
[01:53:49] Google là của
[01:53:51] U11 là nhiều của em là mất à cái kiểu
[01:53:55] thế hoặc cả mấy ông có thể cài thêm cái
[01:53:58] cái
[01:53:59] nó là
[01:54:02] cloudflare nè này thôi nó không biết
[01:54:05] phát tởm cái đằng sau nó gì quá mà Đấy
[01:54:08] cái cái VPN kiểu như này đến mấy ông thể
[01:54:11] truy cập được vào trang web có thể trang
[01:54:13] web đen được không ạ
[01:54:15] Đấy thì
[01:54:18] chợ hoa tiện ích ở trên mạng có một vài
[01:54:20] tx Nhưng mà nếu giờ sự mấy ông cài mình
[01:54:23] cứ lấy Vào mà vẫn không Vẫn không được
[01:54:26] thì mới ông có vài trang có trang này à
[01:54:32] Ở trang này nó tên đọc tên rồi nó thể
[01:54:36] hiểu luôn rồi Nó là mấy ông có thể liền
[01:54:39] biết cái xanh nào vào đây để kiểm tra
[01:54:41] xem trang đây đã sập nó có sắp thực thực
[01:54:44] sự hay không Hay là chỉ còn hơn giản ông
[01:54:47] không gọi được thôi là sự ông không vào
[01:54:49] được mấy home ngoãn với ông gõ mir vào
[01:54:51] đây rồi xong rồi ấn nút này ngọn nó sẽ
[01:54:55] thông báo cho em cái Trang đấy có thực
[01:54:56] sự sập phải không Hay là mỗi mình gọi
[01:54:58] ông không được lại tôi sử dụng nhé trang
[01:55:01] Google rồi mà Bởi vì nhiều lúc ông thấy
[01:55:03] à Facebook không bị ơi ông ạ Ông Thực
[01:55:05] bấm vào đây sẽ xem ra đối với người khác
[01:55:08] thì Facebook của bạn được không đấy
[01:55:13] anh
[01:55:14] không chỉ với bạn thôi Google vẫn lên
[01:55:17] tại Chẳng thế bởi vì đã tự Và thậm chí
[01:55:20] có phải Trang tương tự như này nó còn
[01:55:22] liệt kê cả cụ thể thời gian mà cái trang
[01:55:24] này đã bị sập bao lâu rồi anh ấy rất là
[01:55:26] hay
[01:55:27] từ lần trước ở vụ Facebook sập 4 phút
[01:55:31] thì phải mất cũng khá nhiều cổ phiếu hội
[01:55:35] để mất gần 2 triệu đô chỉ còn 4 cũ đây ạ
[01:55:42] ở trong trong cái khóa học này thì cậu
[01:55:46] không không còn ngôn ngữ nào nữa còn
[01:55:48] khóa sau thì
[01:55:50] anh không còn ngôn ngữ là nữa cũng sẽ
[01:55:52] chỉ chuyên về thì ra Swift nữa thể paleo
[01:55:55] thôi mình không biết về mấy cái ngôn ngữ
[01:55:58] khác từ ra mình
[01:56:00] nhà mình có biết thì mình không thạo lắm
[01:56:02] em mình không dậy được các bạn mày một
[01:56:03] cái đấy
[01:56:05] các bạn về sau các bạn cứ học ngôn ngữ
[01:56:08] một ngôn ngữ rồi Các bạn thấy tự nhiên
[01:56:11] là thấy có thể không hứng thú nó lắm thì
[01:56:14] nhảy sang hạn khác vẫn được mà không sao
[01:56:18] Ừ Ok Google hôm nay quá dài rồi gần hai
[01:56:21] tiếng thôi mình sẽ tạm ngừng tại đây nhé
[01:56:23] Mọi thắc mắc ý kiến Xin vui lòng liên hệ
[01:56:26] đó à thì liên hệ mình qua Facebook đầy
[01:56:30] đủ tất cả kênh hoặc bình luận video sau
[01:56:33] nhé
[01:56:34] ý là có lollia chứ nhưng mà khóa sẵn
[01:56:36] khóa khác Xin chào các bạn nhé Có mình
[01:56:41] sẽ dạy các bạn về Abi nhưng mà cũng là
[01:56:44] khóa sau
