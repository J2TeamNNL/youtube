# Lập trình Web cơ bản - Buổi 7 - CSS - Pseudo & Selector

- Video ID: `qJusq22MRvA`
- URL: https://www.youtube.com/watch?v=qJusq22MRvA
- Published: 2021-10-26
- Duration: 1h 28m 41s (5321s)
- Language: vi
- Subtitle source: auto
- Kind: live

## Transcript

[00:00:00] ừ ừ
[00:00:04] anh alo Chào tất cả bạn
[00:00:07] Các bạn thấy màn hình mình chưa ạ
[00:00:13] chờ đợi mình thấy nghe nói chọn nhầm mà
[00:00:16] nạ OOO
[00:00:24] ở lại Ok Ok vợ ạ
[00:00:28] ừ ừ
[00:00:31] ờ ờ
[00:00:34] Tại sao tạo thành bột cuối rồi khi bản
[00:00:37] chất là mình bảo lỗi mình sẽ chỉ dạy
[00:00:38] lướt qua nhanh hgcs sấy phẳng nó sẽ
[00:00:42] không nhanh được như thế này ra quyết
[00:00:44] thì mình vẫn phải dạy lại từ đầu các bạn
[00:00:46] thế nào muốn lập trình nữa kết hợp với
[00:00:48] việc là Switch thì bắt buộc phải làm
[00:00:51] xong cái gì đó còn HTML CS thì được ra
[00:00:53] các bạn chỉ cần biết cơ bản để làm về cơ
[00:00:55] bản thôi
[00:00:59] nay học muộn thì rất là muộn hơn cho mọi
[00:01:02] hôm như cá thì
[00:01:04] 8:00 bác đồ vào học mà không ạ
[00:01:08] Chừng nào mà muộn hơn rồi đấy thì mình
[00:01:11] mình sẵn hàng để nó bạn khiển trách mà
[00:01:13] bây giờ chị nó vẫn đúng mà Ừ
[00:01:18] anh chạy một phần là mình có nói đây đó
[00:01:22] Hôm nay học muộn vì mình soạn bài nữa
[00:01:24] gửi bài hôm nay sẽ dài hơn
[00:01:26] buổi cuối Sẽ Chẳng Còn nhiều cái hơn kết
[00:01:29] hợp với việc là
[00:01:32] thực ra là thì mình mình bảo mấy lần
[00:01:36] mình ngon sớm để mà tâm sự chia sẻ cái
[00:01:39] gì đó
[00:01:40] chủ yếu tâm sự hơn chứ chia sẻ thì mình
[00:01:43] cảm thấy là đã lẽ phải cuối buổi lắm
[00:01:45] chia sẻ thấy ra là bật Bây giờ mình đang
[00:01:48] chẳng biết chia sẻ cái gì cả từ đây mình
[00:01:50] không không dám mon sớm ăn sớm nói tình
[00:01:54] các bạn lại ghét rồi thoát ra gì hết
[00:01:59] Ừ
[00:02:00] thế thì quan trọng thì cũng đúng Nhưng
[00:02:04] mà mình sẽ không dại có bạn gì hết để
[00:02:07] làm mọi thứ hai chỉ dạy gì hết để mà làm
[00:02:09] cái ra hết về sau mình sẽ nói để các bạn
[00:02:14] biết vai đấy là cái gì nghe nói chung ạ
[00:02:16] để các bạn hiểu được
[00:02:18] ra squat có tác dụng gì thôi Nó được rồi
[00:02:22] còn là mình làm cái khóa này thì nó lại
[00:02:27] gọi lập trình tức là chúng ta sẽ phải
[00:02:29] dùng ngôn ngữ lập trình để mà làm nũng
[00:02:31] hoặc là năm có trang web tất cả mình sẽ
[00:02:34] chủ yếu cốt có thể bằng VP chắc chắn sẽ
[00:02:39] nhiều hơn rất nhiều chiếm Chắc phải bảy
[00:02:41] mươi phần trăm
[00:02:42] bảy mươi tám mươi phần trăm của cái
[00:02:44] trang web p + 10 máy Wave A
[00:02:48] ạ
[00:02:50] bây giờ chắc à Chuẩn bị trả lời câu hỏi
[00:02:53] thôi bây giờ tranh thủ trước thì mình
[00:02:57] trả lời cái câu lại câu này trước đi
[00:03:02] chứ
[00:03:02] không phải là sai chính tả với nhiều bắn
[00:03:05] teencode Tôi không biết Không phải bạn
[00:03:06] đang bao nhiêu tuổi nữa
[00:03:08] ờ Anh ơi em hỏi một câu chắc hơi cũ một
[00:03:12] chút
[00:03:13] Ừ anh treo cái này thì khó không anh
[00:03:16] ở kho với anh không Cái này đa số từ đâu
[00:03:21] ạ
[00:03:22] Ừ hình như thế à
[00:03:25] thế nhưng bây giờ nói thật ra mình không
[00:03:27] thể khẳng định được là các ngành công
[00:03:29] nghệ thông tin này nó dễ dàng cả
[00:03:31] phải bình tĩnh nhìn cái khó chữa trị
[00:03:35] những cái này
[00:03:37] Ừ thì ah cái này công nghệ thông tin là
[00:03:40] không hề họ dễ dàng đến bây giờ bảo dễ
[00:03:44] dàng ông không lại bảo tôi lừa mấy ông
[00:03:46] nghĩ nhưng mà
[00:03:48] cái việc à
[00:03:53] Ừ cái việc này nó cảm thấy cho mình khá
[00:03:55] Hưng Phú Cần phải làm xong mình sẽ khá
[00:03:59] là vui khi mà giải quyết được sau một
[00:04:01] cái gì đó chị gần như là tìm được bác
[00:04:04] cái hay làm xong một cái tính năng gì đó
[00:04:06] hoặc và khiến hôm trước là mình cảm thấy
[00:04:08] rất vui khi mà cậu Cái trang web mình
[00:04:12] đang chạy mất 3 giây chậm lại mình làm
[00:04:14] nó nó chạy thì 0,3 giây ạ Tôi cảm thấy
[00:04:17] có nó mình kiểu mình thấy mình hàng
[00:04:21] thông minh vãi chưởng với dễ Kiều
[00:04:25] Nó là một cái hình thức tự sướng nhiều
[00:04:27] hơn ngày ngày tự sướng chứ
[00:04:30] khoe với người khác thì người ta có hiểu
[00:04:32] gì đâu Đó Ngoại
[00:04:34] nói chung là kiểu
[00:04:36] A
[00:04:38] và cái vui của ngày ngày nữa đó là mình
[00:04:41] cảm thấy mình có
[00:04:44] nhà mình có tác dụng mình tiểu học có
[00:04:47] thể hoàn toàn là làm chia sẻ cho nhiều
[00:04:50] người khác khác với nhiều ngành
[00:04:53] thực ra mỗi ngày thì đương nhiên là rồi
[00:04:56] thường ai giúp đỡ lẫn nhau với Vân ngày
[00:04:58] này thì có thể dịch vụ cái gì đó giúp đỡ
[00:05:02] ngành kia
[00:05:03] Ừ nếu mà mình vẫn phải có tìm được những
[00:05:07] niềm vui thôi công việc đấy đúng ạ
[00:05:10] Nên là khi khi đấy xong mình chưa rồi
[00:05:14] nghĩ việc ở cửa khóa không
[00:05:17] mình chỉ nghĩ việc giải quyết và toàn
[00:05:20] như nào thôi chúng mình không gặp vấn đề
[00:05:22] với việc và thấy khó gì nào ạ
[00:05:25] à à
[00:05:30] à à
[00:05:31] à à
[00:05:33] Ừ cái vụ vay Dead ở friend 2 bác em thì
[00:05:37] chắc là vì sau mình sẽ nói cụ thể hơn
[00:05:39] cho bạn nha Ờ anh biết tổ chức tổ chức
[00:05:45] với xanh tại lúc
[00:05:46] Ê AK gần đây mình theo dõi cái Tết à
[00:05:50] tiếng Việt giàu đẹp thì tôi không khẳng
[00:05:53] định được là ông nào sang phải ông nào
[00:05:54] không nữa rồi vì có nhiều từ rõ ràng từ
[00:05:57] trước là mình tưởng ạ
[00:05:59] Nó là như thế người ta không phải thế
[00:06:01] bởi vì theo từ Hán Việt Nó là kiểu như
[00:06:03] hành ABCD Z thì B không dám bắt lỗi
[00:06:07] chính tả người khác này à
[00:06:08] ờ ờ
[00:06:10] cái tổ chức Anonymous Nếu mà bạn đang
[00:06:14] nói chắc là tổ chức liên quan nó như mất
[00:06:16] hacker không ạ kìa
[00:06:19] Cái này chắc chắn là nhiều biết rồi vào
[00:06:23] kiểu thì mình hẹn tưởng nói là thật chia
[00:06:26] lúc đầu mình không định theo ngành lập
[00:06:28] trình mình theo ngành khách không thì
[00:06:30] kiểu gì mình cũng thần tượng với anh này
[00:06:33] mà ra đúng không ạ
[00:06:36] Ừ nếu mà thực tế đi à mì cay đấy nó vẫn
[00:06:40] một phần được thêu dệt cái gì đó là để
[00:06:42] cho nó ngầu thôi nhưng mà
[00:06:44] số kiểu mình thủy tổ chức này làm ít vụ
[00:06:49] không không hẳn nhiều vụ lắm
[00:06:52] ở trong giới hacker nhầm thì chắc chắn
[00:06:54] nó sẽ có chỗ có nhiều cái nhóm chuyên
[00:06:58] làm nhiều vụ hơn
[00:07:02] à à
[00:07:04] các
[00:07:05] tester có cần biết phân em để lấy anh em
[00:07:08] mình không
[00:07:10] ờ ờ
[00:07:14] Ẩm Thực sự thì toàn bộ công việc của
[00:07:16] tester thì bị chỉ hiểu cách tương đối
[00:07:18] rồi Chắc là cái này các bạn à
[00:07:21] cha tra xem giấy tờ Yêu cầu những cái cụ
[00:07:25] thể gì thì các bạn học thì ổn hơn
[00:07:30] ừ ừ
[00:07:33] à Anh ơi Em không biết em thích cái gì
[00:07:36] em vẫn cố gắng theo tốt vì nó là ngành
[00:07:39] kiếm nhiều tiền Cái này không phải mỗi
[00:07:42] chỉ mỗi ngày công nghệ thông tin này mà
[00:07:44] đôi khi nó về tắm luôn thua được Ừ
[00:07:48] Ừ mình may mắn hơn các bạn ở điểm là
[00:07:51] mình tự nhiên mình kiểu có cái góc nhìn
[00:07:54] khác đầu tiên mình có góc nhìn khác về
[00:07:57] những cái môn học
[00:07:59] ở trường
[00:08:02] thì các bạn đôi khi có bạn học một cái
[00:08:05] môn và các bạn sẽ tự hỏi là môn này có
[00:08:07] tác dụng gì trong cuộc sống kiểu thế Tự
[00:08:09] nhiên mình học môn Sinh học môn hóa học
[00:08:12] môn vật lý Và thậm chí ở các toán nâng
[00:08:14] cao Toán kiểu hàm số đại số cái gì nhỉ
[00:08:19] thích Phân nó ngọn vân vân vân rồi các
[00:08:22] bạn sẽ hỏi là tác dụng gì trong cuộc đời
[00:08:25] này mình có ở Dùng cái đấy đi chợ ở đâu
[00:08:28] đừng Ngoại nên thành ra là kiểu các bạn
[00:08:31] chán học kiểu gì thế
[00:08:33] Mình không ngừng như thế mình thấy hợp
[00:08:36] tất cả những cái môn đấy Kiểu mình biết
[00:08:39] được là lý do đến học những môn đầy kiểu
[00:08:41] để rèn tư duy cả để có một tí kiến thức
[00:08:43] về em ạ Cái vụ là để vì sao tra Google
[00:08:46] Thay vì mình hỏi cái cô cho Google theo
[00:08:48] kiểu là cái gì bảy màu ở trên trời thì
[00:08:51] mình chỉ được cha là tại sao có cầu vồng
[00:08:53] nhãn hãy kiểu thế người có học có người
[00:08:56] không đi học mà sẽ khác nhau vài cái chỗ
[00:08:58] như thế
[00:09:00] A và tương tự thế khiến cho khi mà lên
[00:09:04] đại học mình
[00:09:06] mình kiểu hoàn toàn thích khá nhiều
[00:09:09] ngành chưa Thế thế ngành nào cũng thật
[00:09:11] thế à Mình có thể treo được được Kiểu
[00:09:14] mình lúc đầu mình nhận định theo cả báo
[00:09:16] chí theo cờ
[00:09:19] và chia của vì tôi thích tự do ngôn luận
[00:09:22] thôi chứ tôi không thích thành liều vào
[00:09:24] đâu
[00:09:25] thích đi dạy bởi vì mình từng dậy người
[00:09:29] khác và cảm thấy à Người ta dễ hiểu lên
[00:09:32] thành mình tự tin việc đấy mình còn
[00:09:34] thích cả luật bởi vì à
[00:09:36] Ừ mình giỏi cãi Chắc thế
[00:09:41] Nói chút mà mình thích nhiều ngày
[00:09:44] và có nhiều bạn thì không bị thế không
[00:09:48] thể bởi vì à Cậu có thể nhàng mà ai
[00:09:51] thích là ngành mà kiểu dạng là không
[00:09:52] kiếm Như Tiến kết hợp kết hợp việc là
[00:09:55] hội bé các bạn bị dễ bị làm hai cả ví dụ
[00:09:58] nhé giờ xử mới ông thích hát chẳng ạ
[00:10:00] Nhưng mà từ bé đến lớn ông đi học cái
[00:10:04] môn âm nhạc ở trường dạy rất hợp làm cho
[00:10:07] ông cảm thấy từ Tao không thích dần dần
[00:10:09] Không thích nó nữa không đam mê hơn nữa
[00:10:11] Trừ khi nhà ông dầu vãi chưởng cho ông
[00:10:13] hẳn và các lớp năng khiếu ngay từ hồi bé
[00:10:15] không học kiểu trình đại trà ấy thì mình
[00:10:18] cái lợi mấy cái môn đấy thì ở trường tôi
[00:10:22] còn từng bỏ luôn cả Mun đấy để mà dậy
[00:10:25] Cái môn Toán làm bài tập cơ cô cô giáo
[00:10:29] chủ nhiệm bỏ môn âm nhạc Mỹ thuật để ba
[00:10:32] sinh viên ngồi làm bài tập môn môn chính
[00:10:34] là thế làm cho thực sự được Ừ cái đam mê
[00:10:37] có bị mất dần theo những hàng đầy so về
[00:10:40] sau chẳng biết là ông đam mê Cái gì cả
[00:10:42] Sao rồi cùng gì về sau ông theo sự chỉ
[00:10:46] dẫn của mấy ông kia bảo là ngành này
[00:10:49] đang hót kiếm được việc xong rồi Bố Mẹ
[00:10:52] bảo là kiểu
[00:10:55] đặt đâu Con ngồi đấy thành ra các bạn
[00:10:57] theo cái gì nó rất nửa vời
[00:11:01] May mà mình không bị như thế
[00:11:04] Ngay từ thì mình bảo ở đây cái gốc rễ
[00:11:06] rồi ra ngay từ chiến trường các bạn phải
[00:11:08] có tư duy đó kêu
[00:11:11] học
[00:11:13] được ba đa dạng kiểu thế
[00:11:16] khi họ xác định được cái môn mình thích
[00:11:18] thì thì về sau theo Đại học
[00:11:22] Tại sao cấp 1 cấp 2 cấp 3 học các môn
[00:11:26] dàn trải như thế để mà các bạn thực sự
[00:11:28] Các bạn thấy thích kể cái môn nào nhất
[00:11:30] để mà lên đại học các bạn chỉ chú trọng
[00:11:33] những môn đấy thôi đâu như là đi thì học
[00:11:36] này mình thấy thực ra nó không Hắn
[00:11:38] tự nhiên Thì mình vẫn nhiều chính xác
[00:11:41] mình thi vào ngành Công nghệ thông tin
[00:11:43] tự nhiên mình phải khi môn văn cần thấy
[00:11:46] sai lại chưa
[00:11:47] mình bị trượt trường chỉ vì môn Văn Miếu
[00:11:52] em
[00:11:53] nghe nói thế thì lại hơi đụng chạm ở bên
[00:11:55] giáo dục nữa rồi theo đại khá như thế
[00:11:58] Mình cảm thấy
[00:12:00] đấy cái mình nói về việc là các bạn chọn
[00:12:03] ngành rồi Tiếp theo là việc à Ở lời
[00:12:07] khuyên cho bạn này
[00:12:09] lời khuyên thì
[00:12:11] xơ ca nó liên quan Vừa chọn lành đó là
[00:12:14] các bạn không nên chọn những kẻ nhàng mà
[00:12:16] chỉ nhận ra mình thấy nó Giang Rất là
[00:12:18] Hót bởi vì chính vì góc nhìn của bạn như
[00:12:22] thế rất nhiều người đang như thế rất
[00:12:24] nhiều người rất nhiều trường bây giờ vạn
[00:12:26] năm đào tạo công nghệ thông tin thực sự
[00:12:28] là vẫn đang đầy người ra có cái bằng
[00:12:31] nhôm thất nghiệp mình quen rất rất nhiều
[00:12:33] và rất nhiều người bỏ không theo ngày
[00:12:35] đấy nên thành ra là
[00:12:38] mình không thể khuyên bạn là cứ theo đi
[00:12:42] được
[00:12:45] Ý bạn nói chung là nếu bạn xem cái lý do
[00:12:49] từ hôm trước thì sao bạn vẫn đang thử
[00:12:50] theo phải khóa này Thì nghĩa là bạn bạn
[00:12:54] cứ theo thử nốt chút tiền cái khóa cơ
[00:12:56] bản này bạn thấy phù hợp hay không Không
[00:12:59] thì bạn đến chuyện thực sự vẫn còn rất
[00:13:02] nhiều ngành khác còn nếu không được thì
[00:13:04] chắc là ở bất ông Vỹ phải làm những cái
[00:13:06] thứ mình không thích rồi ông
[00:13:12] thực là hồi năm nhất của mình mình cũng
[00:13:15] làm rất nhiều thứ mà mình từng kể rồi đó
[00:13:17] là mình làm
[00:13:19] Linh làm từ việc gõ mãi gõ máy này xong
[00:13:23] buổi bàn các thứ thứ đủ mọi kiểu để cho
[00:13:26] mình cảm thấy mình phù hợp với cái gì
[00:13:28] hoặc là chỉ đơn giản là cảm thấy mình
[00:13:31] không phù hợp với cái gì để mà về sau
[00:13:34] mình khi mình quay lại trường học đấy
[00:13:36] thì sẽ phấn đấu Bởi vì thực sự những cái
[00:13:39] nhanh chứ không hề phù hợp với mình đâu
[00:13:42] thế cho mình chân yếu tay mềm Key ở mình
[00:13:46] dân công nghệ cười cùng ngon mà anh ra
[00:13:48] là không làm được việc nặng cũng như là
[00:13:50] không không kiểu đứng chạy cả ngày được
[00:13:54] ra là mình phù hợp với việc ngồi ngồi
[00:13:58] trước máy mới gõ chém gió như này còn
[00:14:00] được
[00:14:05] cái tên bác học điên có nghĩa gì
[00:14:09] thực à Có khi cái câu vừa nãy mình đã
[00:14:12] trả lời cho cái này rồi đó là trên
[00:14:15] trường mình hồi bữa trước sinh trường
[00:14:17] mình học có phải rất là giỏi nhé Mình ko
[00:14:20] phải con nhà người ta chẳng qua là mình
[00:14:23] rất thích kiểu tìm tòi Tìm tìm hiểu các
[00:14:27] thứ thứ có khi chạm phải kiến thức ở
[00:14:30] trên trường Anh ngồi đây tôi còn kiểu
[00:14:32] tôi nhưng mà thằng tôi bảo rồi tôi là
[00:14:35] kiểu màu sách mà cái này là tôi nói
[00:14:38] chuyện nhằm nhẽo lắm từng Kể câu chuyện
[00:14:40] cười bằng cách đọc y nguyên lại câu
[00:14:41] chuyện cười ấy và với con trai cười thế
[00:14:44] thế nên là
[00:14:46] tôi hồi đấy thôi Kiểu cô đơn muốn kết
[00:14:50] bạn thêm Tôi ngồi tìm hiểu thêm cả những
[00:14:53] cái ví dụ là những cái mà người khác
[00:14:56] thích nghe đó về tâm linh này hay ở Về
[00:14:59] nhà ạ truyện 18 + vẫn Vân này rồi chuyện
[00:15:03] có học vũ trụ thì em ạ xong rồi tìm hiểu
[00:15:07] rất nhiều để mã kiểu nói nói ra người
[00:15:10] khác thích nghe
[00:15:12] thì thế nên là dần dần là kiểu cái mác
[00:15:17] bác học điên có họ các mình tìm hiểu rất
[00:15:20] nhiều đứa nghèo ngồi đây vẫn chẳng ai
[00:15:22] nước gì cả à khi
[00:15:25] học xong khóa này là fullback hả thầy
[00:15:29] Ừ thì fulltech thì đầu tiên là dịch cho
[00:15:33] các bạn chưa biết cái từ này không tách
[00:15:35] là kẹo làm được cả fan được bác
[00:15:37] anphatland là làm các giao diện này và
[00:15:39] bác E là làm cả xử lý nhưng mà phun sách
[00:15:42] bây giờ nó đang bị khó thêm một tí thiên
[00:15:45] hướng đó là
[00:15:46] làm cả bên Forland nghĩa là có cả ra quý
[00:15:49] vị ra quyết định xử lý hết ở bên bên
[00:15:52] krait bên giao diện khách hàng cũng được
[00:15:55] bác em xử lý gì ở một phần thôi nên
[00:15:59] phong cách và bao nhiêu nghĩ ám
[00:16:00] nhưng đại khái là đúng khóa này chị sẽ
[00:16:05] cho các bạn biết qua một tí về giao diện
[00:16:07] và chủ yếu là bên papain nhiều hơn nhà
[00:16:11] nó cũng sẽ có qua là giao diện rồi ừ ừ
[00:16:15] đi tìm cốt mà không biết diễn tả thì cho
[00:16:18] dù như thế nào Cái này không phải là mỗi
[00:16:21] cốt mà rất nhiều bạn không biết cách kỹ
[00:16:23] năng cho Google K thì mình từng nó qua
[00:16:26] với kỹ năng cho Gồ rồi
[00:16:28] khi con bạn này nói hỏi cụ thể về cốt
[00:16:32] thì chắc à các bạn thể inbox hỏi mình
[00:16:35] hoặc à hỏi ở trên link discord của nhóm
[00:16:39] thì từ khóa cho Google bởi vì đôi khi
[00:16:43] các bạn dụng là điển hình nhé các bạn
[00:16:46] muốn hiển thị tâm một cái kiểu một cái
[00:16:48] cửa sổ bấm vào nói gì để mua cửa sổ hiển
[00:16:50] thị lên để bạn điền thông tin em ạ Các
[00:16:52] bạn không đi được từ khóa tiếng Anh đấy
[00:16:53] là gì Các bạn để hỏi người khác khác trả
[00:16:56] lời bạn ví dụ nó làm cái parte 1 cái mua
[00:16:58] đồ hiệu Thế thì
[00:17:02] khi Cái đấy là kinh nghiệm của người đi
[00:17:05] trước thôi chứ được gửi thì không không
[00:17:08] có cách nào để mà các bạn biết được toàn
[00:17:10] bộ tất cả các từ khóa đấy đâu
[00:17:13] và cuối cùng mình trả lời nói có này
[00:17:15] mình xin còn
[00:17:17] hi hi
[00:17:19] Ờ Ờ
[00:17:20] mình tin là có nhiều bạn cũng đang dùng
[00:17:24] đương nhiên là nhiều bạn với đa số dùng
[00:17:27] pin ông ạ Không biết các bạn là crack
[00:17:29] crack crack nhiều hơn là mua bản quyền
[00:17:31] thì crack chưa cái là nó không tốt sẽ
[00:17:35] chặn rồi vì a có thể nó dính thêm tí mã
[00:17:38] độc một tí có ông nào nó đang cày cái
[00:17:41] kiểu gọi là à Em bé gọi bé cụm từ thường
[00:17:47] thế cài một cái kiểu nó có nó sẽ chạy
[00:17:51] ngầm trên máy ông và có thể hoàn toàn
[00:17:53] khách không Mày không bất cứ lúc nào mà
[00:17:56] không nên cài mấy cái kiểu crack thế thì
[00:17:58] mày ông đi mua bản quyền à không không
[00:18:01] nên kms chứ nhiều nơi ca mới chính là em
[00:18:05] bé ờ
[00:18:07] và
[00:18:08] đương nhiên là
[00:18:11] Ừ mình không khuyên các bạn được việc là
[00:18:13] dùng hàng lậu cái gì cả nhớ mình mình
[00:18:16] thường ai lên cái cái nhóm ở trên
[00:18:18] Facebook Hồi trước mình tìm được đó là
[00:18:19] nó nó
[00:18:21] tên là kiểu kích hoạt Windows hoặc
[00:18:25] Office kích hoạt Win dows báo Phí tiên
[00:18:30] anh
[00:18:31] đấy người ông Tìm mấy cái nhóm này lên
[00:18:34] đấy băng họ
[00:18:36] mấy anh đấy sẽ kích hoạt cho mấy ông
[00:18:38] kích hoạt bằng mình nhớ Active byphone À
[00:18:43] cái chỗ kích hoạt thì hôm ấy ông và nó
[00:18:45] sẽ Vĩnh Nó gần như vĩnh viễn thì vậy
[00:18:47] không biết được cái đấy không biết là
[00:18:50] cái đấy nó cơ chế nó như thế nào nhưng ở
[00:18:52] chung nhà
[00:18:53] chắc là Windows nó cũng cho kiểu lắc lắc
[00:18:57] như thế Tôi bảo rồi tôi nói vụ đấy rồi
[00:18:59] thở ra Windows hoàn toàn không quan tâm
[00:19:01] mấy ông đâu Mấy ông thế mới cho mày
[00:19:03] không dễ rách như thế à
[00:19:07] anh nói chua miệng để làm nó sẽ uy tín
[00:19:09] hơn nữa việc Hôm Cài Hàn Quốc cái phần
[00:19:11] mềm từ một cái trang lạ hoặc về đấy Ờ
[00:19:16] đương nhiên là mấy ông cũng phải đọc qua
[00:19:19] về mấy cái nhóm đấy Đều là mấy cái nhóm
[00:19:21] là miễn phí nhưng có nội quy của họ
[00:19:25] không phải đọc qua với nội quy trước khi
[00:19:28] ông Đăng mày câu hỏi người ta tin nên
[00:19:30] không mới ra chặn luôn đấy à
[00:19:33] A và kiểu
[00:19:36] A và
[00:19:38] trong đấy thường người ta sẽ bảo là mấy
[00:19:41] ông chia sẻ teamview Thượng Mã teamview
[00:19:43] hoặc cả mã
[00:19:45] ultraview thì mấy ông đừng có nên bình
[00:19:48] luận luôn cái mã ở đấy bởi vì có một cốc
[00:19:51] ông Chia sẻ mã đấy Thằng nào nó nhảy đều
[00:19:54] vào máy ông này là rất nguy hiểm mấy ông
[00:19:57] nên để cho mấy anh kia inbox Và thậm chí
[00:19:59] A đầy kỹ xem mày Thế Anh inbox mình là
[00:20:02] là người như nào trong mà Nhóm kia hoạt
[00:20:05] động như thế nào cho nhóm kia tránh việc
[00:20:07] Kiều
[00:20:08] đưa mãi cho người lạ mà người ta có thể
[00:20:11] chiếm quyền vẫn có thể truyền quyền được
[00:20:13] mấy ông
[00:20:14] Ừ thế do ông tự cho người khác truy truy
[00:20:17] cập vào máy may sóng mạng đi
[00:20:20] à à
[00:20:22] khi tái Mình vừa trả lời qua tất cả đến
[00:20:24] ngày đúng ạ Bây giờ chúng ta sẽ bắt đầu
[00:20:26] buổi học thì hôm nay mình sẽ học về Bose
[00:20:29] đô và spectre chất cả hai cái này nó đem
[00:20:33] là sợi tơ Chính xác là thế thế đều chọn
[00:20:36] một cái thẻ nó đó theo ý của mình thì
[00:20:39] cái cô Shadow nó sẽ viết theo tội loại
[00:20:41] như thế này này Tôi ví dụ trong mấy ông
[00:20:45] ừ ừ
[00:20:53] à à
[00:20:55] à à
[00:21:04] em thật sự ở mình cứ Xóa hết toàn bộ cái
[00:21:07] bài cũ nhé
[00:21:10] à à
[00:21:11] ạ Bây giờ sửa mình có thể này
[00:21:16] sẽ là đây là link virus cho lại
[00:21:24] mình chạy thử nhé ạ
[00:21:28] à à
[00:21:30] thì
[00:21:32] các bạn sẽ thấy là cái này tuy nằm trong
[00:21:35] thẻ ra nhưng mà nó chưa Bấm được và nó
[00:21:39] chơi hiển thị giống như là mình có thể
[00:21:40] bấm được bình thường các bạn thấy nó sẽ
[00:21:43] được bôi màu với cậu có thể bấm được khó
[00:21:47] chỉ vào biểu tượng này sẽ bấm được đóng
[00:21:49] ạ bởi vì à Mình đang thiếu cái Hz cái
[00:21:52] đường dẫn để hiểu là nó thể A có thể bấm
[00:21:55] được cái mình sẽ cho Hz và nó là sự nó
[00:21:58] sẽ nhảy trang trang Google hay gì đó
[00:22:00] không ạ
[00:22:01] 1.com trả nào
[00:22:03] Ở
[00:22:03] đây các bạn sẽ thấy là bây giờ màu của
[00:22:08] nó sẽ đổi sang màu tím tại sao nó lại
[00:22:10] sang màu tím
[00:22:12] thì
[00:22:12] tại sao tự nhiên mình để cảm với vũ màu
[00:22:15] đây bởi vì ạ bây giờ xưởng mình sẽ tra
[00:22:17] mà sang một cái trang nào đó thế này
[00:22:20] thời trang sẽ trả chưa Rồi vào khi nó là
[00:22:22] đổi sang màu xanh để ngon nếu việc màu
[00:22:25] tím màu xanh ở đây để thể hiện điều gì
[00:22:27] màu tím thì có sẽ hình dung được là nó
[00:22:29] từng được bấm rồi còn màu xanh để hiểu
[00:22:32] nó chưa từng bấm ờ
[00:22:35] A và chỉ ở đây thì các bạn thấy biểu
[00:22:38] tượng con trò này đúng không ạ và các
[00:22:40] thứ từ đây đó ngoan nhé các bạn thấy mặc
[00:22:42] định khi một thẻ ra trình duyệt nó sẽ
[00:22:46] hiểu và tự tự thêm sẽ cho nó là đổi màu
[00:22:52] này gạch chân ở dưới này sôi trỏ chuột
[00:22:55] vào thì thì hiển thị ra là có thể bấm
[00:22:58] được dấu ngoặc Và nếu mà cái việc
[00:23:03] cái việc bấm cái nick một lần rồi thì
[00:23:06] màu nó sẽ khác đúng không ạ nhưng mà đây
[00:23:09] là mặc định của trình duyệt với mỗi
[00:23:11] trình duyệt thường thường là sẽ phát
[00:23:13] khác 1 tí nhưng mà giờ sự các bạn không
[00:23:15] muốn như kiểu màu như thế các bạn muốn
[00:23:17] màu đỏ chói à mã sau khi chỉ vào sẽ có
[00:23:20] thêm cái gì gì đó thì sao đúng không Thì
[00:23:23] cái này nó là liên quan đến sẽ à Odo tất
[00:23:27] cả cách viết kiểu nó vẫn là thẻ ra nhưng
[00:23:31] mà vì nó có những cái gọi là trạng thái
[00:23:35] khác nhau đều mặc áo kiểu cưỡi Tôi không
[00:23:38] biết dùng từ như thế nào Vì tớ bảo rồi
[00:23:41] có nhiều từ 0 đến dịch sẽ là kiểu như
[00:23:43] này Nghệ A Khi mẫu ngón trỏ chuột vào và
[00:23:46] sự tố đổi nó sang màu khác đi đầu nhọn
[00:23:49] con kia nó sẽ là hoa vợ nhé
[00:23:53] Nó sẽ hai chấm chấm gì vậy không nhiều
[00:23:56] lắm thử thực có lâu sẽ là sang màu đỏ
[00:24:00] cho này
[00:24:02] á thay thế mua chấm Không ạ đó béo khỏe
[00:24:06] không hả trọ chuột ở sẽ sang màu đỏ nha
[00:24:09] kích thích kích thích cho người dùng
[00:24:11] được
[00:24:12] Ừ tôi chỉ chuột vào nó sẽ thay đổi gì đó
[00:24:15] làm tôi cảm thấy cái thích bấm vào cho
[00:24:17] dù đây là link virus trở lại kêu hết cái
[00:24:20] Thậm chí có thể hoàn toàn không phải mỗi
[00:24:22] đổi màu ông già sử ông cho nền thay đổi
[00:24:25] hoa chữ to lên tùy âm ông ạ nên thay đổi
[00:24:28] đi sẽ đổi sang màu vàng này
[00:24:32] xong rồi phun sai người to lên kiểu nhằm
[00:24:35] nhấn mạnh không ạ chúng ta link virus
[00:24:38] này ấy kêu thế này cái nhìn
[00:24:42] cái này trông thấy so với cũ từ thời nào
[00:24:45] ấy ạ
[00:24:48] ở
[00:24:49] đây sau đó thì giống như mình vừa nói
[00:24:53] các bạn hoàn toàn thể đổi ý
[00:24:57] khi đổi sang kiểu đổi thêm cả linh đã
[00:25:01] được bấm bấm rồi Như này có thể được
[00:25:03] ngồi cho nó đúng ạ
[00:25:04] sẽ là thuộc tính Vista như thế này sẽ là
[00:25:08] do sự mình cho nó là kiểu một màu à
[00:25:12] thường đi cái kiểu thế này đã sửa mình
[00:25:17] có hai đường Linh á sự đây là Google
[00:25:20] virus chặn ạ
[00:25:23] bây giờ xuống dạng đi
[00:25:27] Hãy kiểu Nga Linh chưa được bấm nó ạ
[00:25:30] Linh bấm rồi
[00:25:32] em bấm rồi nó sẽ có bầu nhưng mình chưa
[00:25:35] được Bấm thì màu nó sẽ mặc định màu xanh
[00:25:37] thấy kiểu thế
[00:25:39] ấy thì các bạn sẽ thấy nó hai chấm như
[00:25:42] này sau đó là một cái gì đó gọi là code
[00:25:46] đấy cậu chậm cội không nhớ cách viết của
[00:25:49] nó làm đâu mà ông xem lại nhé
[00:25:53] TC sale đâu gì đấy CS pccc đô class này
[00:25:59] như thế này sau đó thì mấy ông có thể
[00:26:02] tham khảo qua ở trên trang này
[00:26:05] thì ông sẽ thấy đây toàn bộ với sữa Đâu
[00:26:08] của nó là khi mà khi và nick nick vào nó
[00:26:12] cũng có thể màu đó đây ở đây ông thấy
[00:26:15] tôi Click vào nó chẳng hiển thị gì đúng
[00:26:17] không Tôi thử click là cho xem nhé Thì
[00:26:21] anh tít này
[00:26:22] khi ra sự là nó sẽ đổi sang màu kiểu
[00:26:26] Oppo này màu u
[00:26:29] ở đó mà không thấy đổi màu sĩ nào hãy
[00:26:32] Kiểu thế à
[00:26:39] a
[00:26:40] slide của tôi là lấy từ trang web
[00:26:42] address Line này là một phần là cũng mà
[00:26:45] từ trường cũng là em thôi Mày không chia
[00:26:47] sẻ được cho bé ông cái giờ việc lại
[00:26:48] slide này chẳng nói thẳng là lấy từ mình
[00:26:52] phải Trang copy từ mới cái trang Kiểu
[00:26:54] như đặt school này về thì ra là các bạn
[00:26:57] Hà lên trên đây còn hơn đọc mũi sline
[00:26:59] của tôi tôi có bờ tôi dậy đến trường Rồi
[00:27:02] chồng dạy con schleich thì méo không cần
[00:27:06] quan tâm điều đấy đâu
[00:27:09] ờ ờ Các bạn thấy ở trên này có rất nhiều
[00:27:12] nữa ngồi tôi sẽ không chạy hết tất cả
[00:27:14] đúng này không quá à Ừ tôi không được
[00:27:16] dạy hết một cái gì đó như thế đâu
[00:27:19] bà Tôi chỉ khuyên mày ông tôi thích nhất
[00:27:21] cái này Nốt này và cái selector là này
[00:27:25] tí thôi sẽ dạy cho ông béo paper sẽ dậy
[00:27:28] luôn mấy ông về cái selecto nhé đi
[00:27:32] ạ Bây giờ giả sử là bơ bỏ qua vụ thời a
[00:27:36] mấy ông nhớ thẻ à nhé bỏ qua nhé Ok tạm
[00:27:39] xóa hết đi này ạ
[00:27:40] anh phải đi nè
[00:27:43] anh có giả sử tôi có ba ngày nút đi
[00:27:46] có một cái nút đầu sẽ là nó có thai đúng
[00:27:51] là ướt Tân Nghĩa là là là nút Thôi ngủ
[00:27:54] mà nó chẳng có ý nghĩa gì nữa
[00:27:57] đây là nút bình thường thì chị Yến
[00:28:02] đúng không tiếp theo mình sẽ có một cái
[00:28:05] nút nữa nó không bình thường mà lắm đó
[00:28:08] là
[00:28:09] khi bị nút là nút em ít
[00:28:12] đây là nút để thực hiện hành động
[00:28:16] thì đó đúng à Gửi cái Fami đúng ạ
[00:28:22] em
[00:28:23] thừa về đồng ý mày thừa thì sẽ đi thôi
[00:28:27] đúng không ạ Các bạn thấy là giấu vàng
[00:28:28] thường cái gì đó htl nó không được báo
[00:28:30] lỗi thiếu cái gì họ không vào lỗi cháu
[00:28:33] qua có thể nói chuyện thì sai rồi có thể
[00:28:35] rồi Đúng bạn Các bạn thấy vừa rồi nó cho
[00:28:37] nhìn gì sai mình không nhận ra được đấy
[00:28:40] Đây là cái nút để thực hiện hành động
[00:28:42] thì các bạn thấy à hai nút này chả khác
[00:28:45] gì nhau cả và cuối cùng thêm người nút
[00:28:47] nữa đúng ạ nút này nút reset thì bạn để
[00:28:51] xóa anh động
[00:28:53] hoặc khôi phục hành động thì gì đó đúng
[00:28:55] không ạ Các bạn thấy ba ngày nút này
[00:28:57] đang để giống hệt nhau thành ra là kiểu
[00:29:00] người dùng nhìn thấy rất dễ bấm nhầm vào
[00:29:03] một trong ba lúa này vậy khi người dùng
[00:29:06] thực đôi khi để màu nhanh hơn về việc là
[00:29:10] để ý chữ ở trên cái nút thành ra là bây
[00:29:13] giờ mà tôi để cái nút này màu đỏ và nút
[00:29:15] này màu xanh này và khi mày người ta bấm
[00:29:17] sử cái nút màu xanh Nếu bấm nút màu đỏ
[00:29:19] nâu đỏ thường anh thể hiện sự nguy hiểm
[00:29:21] mà không ạ
[00:29:23] anh em thành ra là bây giờ để mình nếu
[00:29:26] mà làm như thế này gần như bài cũ thì
[00:29:28] mới ông sẽ để cho nó cứ class đúng không
[00:29:30] ạ class cái gì đó ID gì đó thực ra là
[00:29:33] thế cũng được hoặc cả Bây giờ mình sẽ
[00:29:36] kết hợp với selector tất cả sao mình sẽ
[00:29:38] cùng là nốt mặt cùng một bát tuần nữa
[00:29:40] ông ạ Mình sẽ có thay bằng bút Tân chẳng
[00:29:44] hạn Cái này là nhảy đơn mà máy quét tụi
[00:29:49] mấy ông nhắn Tôi bảo ở trong này không
[00:29:51] quan trọng Lợi đơn Lợi kép lắm Ờ
[00:29:54] mình sẽ có bác rau color ạ là màu lúc
[00:30:00] bình thường rồi cái À đó chị có màu bình
[00:30:03] thường thôi cửa màu trắng hoặc màu
[00:30:06] gì đó như này màu ra à cổ bình thường
[00:30:10] màu gì nhỉ
[00:30:12] sản phẩm Một bình thường chẳng biết màu
[00:30:15] hồng đi
[00:30:16] ở đó
[00:30:21] a
[00:30:22] tiếp theo là
[00:30:24] mình về cái nút sắp ít thì mình không
[00:30:28] thể để chúng màu được đúng không ạ Chị
[00:30:30] sẽ phải để màu của cái nút hành động là
[00:30:34] nút kém nút hộ hôm Triệu Hồi trước mình
[00:30:36] từng nói qua về cái nút call to Action
[00:30:38] Nhã thực hiện hành động ạ thì cái nút
[00:30:41] này nào thứ nhất là màu phải có tí thể
[00:30:43] hiện là kiểu nó hành động thành công
[00:30:45] theo kiểu là màu xanh lá cây màu xanh
[00:30:48] dương
[00:30:49] mồ à Nói chung gồm với cái màu cậu nó
[00:30:53] nổi nhưng mà nó không mang nghĩa tiêu
[00:30:55] cực lắm
[00:30:56] cho ví dụ giả sử như là màu Aqua 1 tráng
[00:31:00] dương
[00:31:01] ở đó như này hoặc màu xanh lá cây
[00:31:06] như thế này và đương nhiên là đang ví dụ
[00:31:11] thể màu nói hơi xấu ra các bạn vì sau
[00:31:13] các bạn có giao diện màu đẹp hơn sặc sỡ
[00:31:16] hơn rất nhiều Mình đang ví dụ ở thế tiếp
[00:31:19] theo nữa nút reset với xét là để kiểu
[00:31:22] như thế này thì nó giống mà nút bình
[00:31:23] thường không tốt mình sẽ nên có một nút
[00:31:26] cho thể hiện một cảnh báo nó là sự như
[00:31:29] này đi đồ ngoại đấy thì đây nó là
[00:31:32] spectre các bạn sẽ thấy là
[00:31:34] thế hệ cú pháp sợi tơ ở xã kiểu mọc nhọn
[00:31:38] như ngày sau khi tên của thuộc tính nó
[00:31:41] biển ngay shop các bạn sẽ thắc mắc là
[00:31:43] hết Nếu giả sử của em có nhiều thuộc
[00:31:45] tính ở trong mày thì sao mà sự là mình
[00:31:48] sẽ có thai thù cho nọ cậu cùng là hai
[00:31:51] nút bình thường em một cái là bình
[00:31:53] thường và thay thơm một cái là cậu bình
[00:31:57] thường hay Ví dụ ở đâu nhé
[00:31:59] và ông chỉ muốn là cho một cái nút bình
[00:32:02] thường hay nói màu xanh và màu hồng còn
[00:32:06] bình thường một thì không trò này thì
[00:32:08] công sẽ thấy ghi hay thổ thêm ở trong
[00:32:11] như thế này bằng tiếp
[00:32:14] Ừ thôi không nhớ là biết này đúng hay
[00:32:16] không thử sự thử thì biết họ ạ
[00:32:21] Ừ anh có vẻ nha Không đúng như phải như
[00:32:24] này
[00:32:27] đó Thì có ông sẽ thấy là kiểu nói chuyện
[00:32:30] ra là thêm cái mỏ nhọn thêm nhầm thêm
[00:32:33] những mặt vuông đó ạ ngon thêm dấu ngoặc
[00:32:36] vuông sau đó thì mình sẽ tiếp cái thuộc
[00:32:39] tỉnh nữa tiếp theo để mà mình gán chuẩn
[00:32:42] cho đúng cái mà mình muốn hồi không ạ
[00:32:44] Đấy
[00:32:47] Ừ thì các bạn sẽ thấy à Đây là theo kiểu
[00:32:49] selector tất cả chọn Cụ thể một cái gì
[00:32:53] đó đóng ngoặc
[00:32:55] ở lại thế thôi
[00:32:57] ừ ừ
[00:32:59] anh không Mình đã nói không bài toán về
[00:33:01] đặt ID các bạn sẽ thấy là về đặc biệt là
[00:33:05] về giao diện nút này thường ở một người
[00:33:07] ta cho class giống như các bạn biết bút
[00:33:10] tre thì có bạn sẽ biết được là nó thường
[00:33:12] hay có class burton xong ngồi bất Tân
[00:33:14] sắp xít nghĩa là kiểu thể hiện thành
[00:33:16] công nó có tên banjo thể hiện kéo cảnh
[00:33:19] báo thì nó sẽ là cái class thôi là ai đi
[00:33:23] nhưng mà cảnh sợi tơ này mình đang ngoài
[00:33:26] qua thế để các bạn phải sau không phải
[00:33:28] để áp dụng cái này trong CF đâu Thì có
[00:33:31] sợi tơ này là một cái phù hợp để bảo vệ
[00:33:34] sau các bạn làm cho cả về bên ra Swift
[00:33:37] nữa Swift sẽ viết theo kiểu sợi tơ như
[00:33:40] thế này về mà chọn Cụ thể một cái thẻ
[00:33:43] nào đó khi mà các bạn không phải tốn
[00:33:46] công bạt mái đi vì đô thị Tôi nói thẳng
[00:33:48] với ông đôi khi ông đã phải đi Mày cũng
[00:33:50] chả nhớ tên của bé đi ấy là gì đâu về
[00:33:53] cái nút này hai cái nút này thì mới Ông
[00:33:55] định đã đi như thế nào
[00:33:56] nút bình thường hay ạ ông ạ
[00:34:09] em được mấy ông có thể chơi theo kiểu là
[00:34:11] kiểu thằng bút tuần thứ bao nhiêu thì
[00:34:13] bao nhiêu được Nói chung có nhiều cách
[00:34:15] để giải quyết một vấn đề mà đúng ạ
[00:34:17] ở đó Nói chung nhà kiến thức hôm nay thì
[00:34:20] các bạn thấy ạ Cũng tương đối hiểu hiểu
[00:34:24] na ná rồi có thể không nhớ mà có thể
[00:34:26] hiểu nó nào rồi
[00:34:30] ờ ờ Nếu mà bây giờ bây giờ mới sang bài
[00:34:34] tập thực sự bài tập hôm nay mình sẽ phải
[00:34:37] làm bài bài này
[00:34:40] ờ ờ
[00:34:42] ở đây tôi hôm nay tôi chạy hướng dẫn các
[00:34:45] ông làm chỉ là menu thôi và bài tập cuối
[00:34:51] ngày cuối của cái xe này đù ngon nếu như
[00:34:54] là tổng hợp lại mình sẽ làm một trang
[00:34:56] web như hôm trước tôi nói có thể làm một
[00:34:59] trang web mạng xã hội nào đó cũng được
[00:35:02] mấy ông sẽ tổng hợp những cái kiến thức
[00:35:06] Mình đã học mình đã biết càng tốt Nó
[00:35:08] ngoan để làm một cái trang web
[00:35:11] công thích bất kỳ chẳng quay gì cũng
[00:35:13] được về mấy ông bang lên kênh thích cái
[00:35:16] bồ để mấy ông ạ
[00:35:19] đưa nhà Đăng không phải một cái ảnh
[00:35:21] không ạ Nếu không đi Đang nha link get
[00:35:24] hát để để mà
[00:35:26] tôi thể vào xem xem mấy ông thực sự gõ
[00:35:30] mấy cái đấy Hai đứa mày đi cốt ở đâu về
[00:35:32] nhìn có chuyên nghiệp hay cốt bình
[00:35:35] thường bên nay đi
[00:35:37] thế thì kiếm thì mấy ông
[00:35:41] đấy đấy sẽ bài tập của mấy ông đó là
[00:35:44] kiểu làm hẳn lại một cái giao diện chỉ
[00:35:47] cần một trang HTML rồi nhé Kết hợp với
[00:35:49] CS để mà làm ra đồng giao diện mà ông
[00:35:52] cảm thấy ổn còn ngọn ạ
[00:35:55] e100 bất kỳ
[00:35:59] ngồi code của mấy ông không khóm à
[00:36:02] chuyên nghiệp trừ khi mày ông cậu chơi
[00:36:04] kiểu spud vào đây dọa tôi
[00:36:07] anh nói chúc bà bây giờ tôi sẽ hướng dẫn
[00:36:09] mấy ông làm cái Menu kem thường là bơi
[00:36:13] ít hàng hả máy nuôi theo kiểu như này
[00:36:14] những cô có hướng dẫn với ông bản chất
[00:36:18] là mấy ông thấy đó hả Khi trỏ chuột ở
[00:36:20] đây thì cái cái chữ nó sang màu đỏ chữ
[00:36:24] to lên này bạn nền của cái này thay đổi
[00:36:26] không ạ Thế ăn nên cái này đơn giản vì
[00:36:29] cái nền là nó cái ảnh đấy ạ bác limeade
[00:36:31] thì mình mình mình sẽ thử làm nhé
[00:36:36] à à
[00:36:38] Ừ
[00:36:38] cái này bạn nếu mày ông Để ý kỹ người ta
[00:36:42] Cái này nó là cái thế bồ này
[00:36:46] đương nhiên là thường mới là chẳng ai
[00:36:48] làm bánh ngu thì cậu thấy bồ cả nhưng mà
[00:36:49] tôi đang chạy qua mày không phải như thế
[00:36:51] thế Bồ đây và thấy cái chữ này in đậm
[00:36:54] này tao nó giữa này thì nó sẽ th đúng
[00:36:57] không ạ Mình sẽ tr từng tr và chỉ có một
[00:37:01] th thôi nghe sẽ thể loại phim này
[00:37:05] tiếp theo là Tarot tiếp này
[00:37:08] TD này hành động ở
[00:37:14] a kinh dị người lớn nhỏ ạ
[00:37:24] cô
[00:37:29] không Mấy ông không được dùng bút chép
[00:37:32] hay di li càng không mùi rõ làm thôi Chị
[00:37:36] nói với ông được làm hlcs không không
[00:37:40] không chơi được à bút chát không chơi
[00:37:42] Facebook gì nhiều nhé á
[00:37:47] Ừ
[00:37:48] đấy rõ ràng mấy ông Định Smart tôi rồi
[00:37:51] tôi biết mà
[00:37:52] không được
[00:37:56] đây nếu mà chạy thử cái này mấy ông sẽ
[00:37:59] thấy nó ra như này rất nhạt nhẽo đóng
[00:38:01] ngoặc tí nữa để làm ra được trong chậu
[00:38:04] như này thì đầu tiên là các bạn phải
[00:38:07] chỉnh cho Mắm cái cái cái bàn này đang
[00:38:09] cái vít của nó đang còn 100 không ạ Mình
[00:38:12] chỉ quýt nó
[00:38:14] style cho nó luôn đấy cũng được trăm
[00:38:17] phần trăm kè Nếu mà Mấy ông muốn nằm
[00:38:19] ngang như thế này thôi nhá
[00:38:21] đó Tiếp theo là cái này như tôi đã nói
[00:38:25] bạn chất mấy cái này đều là backgroud
[00:38:27] hết bác limeade những để chỉnh nhanh cho
[00:38:30] nó nó là với cái th đấy với thẻ th mình
[00:38:33] sẽ có bác rau inmates L cho nó 1 cái ảnh
[00:38:37] không ạ Anh ở đây của tôi là cái ảnh nó
[00:38:41] Ừ nó nên nó đậm
[00:38:44] thật sự không nhớ ảnh gì luôn xem thử
[00:38:47] xem ạ
[00:38:48] ờ ờ
[00:38:50] em copy đường dẫn này
[00:38:52] Em
[00:38:54] đổi cái này thành
[00:38:56] Suốt này thì nó mới nhận này
[00:39:01] Khoa
[00:39:01] học Xã hội Suốt này à
[00:39:05] Anh thử nha à
[00:39:08] ở
[00:39:09] đó chắc là được cho là đúng đấy tiếp
[00:39:13] theo là tôi có PD đúng không ạ ạ
[00:39:21] ở
[00:39:23] bến xe lấy nốt cái ảnh ở trên này à
[00:39:29] Sau
[00:39:30] đó các bạn sẽ thấy thời gian nó hơi khó
[00:39:34] chịu một ý nghĩa vì nó bị thừa khỏi
[00:39:36] trống ở đây đó nhà thì cái để mà mình
[00:39:39] chỉ trỏ đẻ chọn inspect này mình kiểm
[00:39:42] sau đó thì mình à đây cho bạn xem
[00:39:47] Vì mình thấy có khoảng trống ở đây Tại
[00:39:49] sao tại sao nó cũng hỏi trống ở đây xem
[00:39:52] kỹ nhé
[00:39:54] vì nó có cái bát đinh một này nhớ là mặc
[00:39:57] định nó đang cách với cái lề
[00:40:00] để tạo ra khoảng trống ở ngoài mình hoàn
[00:40:04] toàn thì mình chỉnh cho nó kiểu tránh bị
[00:40:06] từ đấy mình sẽ để cho dụ
[00:40:10] cho tác cả thằng này vẫn không ai đều
[00:40:13] bọc eding đi đã đây là không ạ
[00:40:17] Em đỡ ai nhớ cái này không đúng Đợi mình
[00:40:20] thích nhưng không đúng không em
[00:40:22] Ừ bắt đình này không không không phải
[00:40:25] đâu như cái bò đâu đấy
[00:40:27] Ừ để mình xem kỹ lại nhé
[00:40:30] em không nhớ về vụ này lắm đó
[00:40:33] a Tale lồ này
[00:40:37] ở Bắc Ninh
[00:40:41] Ừ đúng rồi nhỉ
[00:40:43] a Model
[00:40:47] em có khi mình nói xem lại cái này Tại
[00:40:49] sao nó được như này đấy
[00:40:53] ở tt background
[00:40:56] đó là sage Bắc Ninh đúng là xe Bắc Ninh
[00:40:59] trình cho từng từng Cái ô này cách nhau
[00:41:02] nữa Đúng rồi quên đấy mình sẽ thay bồ
[00:41:05] này
[00:41:08] siêu bá tinh này
[00:41:11] đã không ạ
[00:41:14] Ừ đúng nhỉ
[00:41:19] à à
[00:41:21] em à cái ghi thẳng ở trong thuộc tính
[00:41:23] Giống nhờ kiểu HCl C
[00:41:27] trong CS thì chả có thôi mình không nhớ
[00:41:30] nó là cái gì có tạm copy đấy nhá và
[00:41:34] spurs
[00:41:35] spacing này Ok này
[00:41:39] những kẻ thống trị như các bạn đang thấy
[00:41:42] có thể mình chưa biết được cái này bởi
[00:41:44] vì vốn dĩ À cái này mình chỉ đang làm
[00:41:47] cho các bạn biết qua thôi Thực ra là
[00:41:51] cái này mình chỗ được áp dụng ngoài
[00:41:55] ngoài thực tế bây giờ thành ra mình
[00:41:56] chẳng biết chịu không không không nhớ nó
[00:41:59] là cái gì cả
[00:42:01] a
[00:42:03] Marine không đúng đâu bị marquezine rồi
[00:42:05] nó không phải mặt Magie nó trống đấy ạ
[00:42:12] 10 cái đấy không ạ chôm cốt đâu vì
[00:42:16] koastal Eco tự mình gõ ra mà nhưng mà
[00:42:19] chẳng qua là mấy năm trước rồi
[00:42:20] ở ngã tự mình chung cốt của mình
[00:42:25] à à
[00:42:27] à à
[00:42:32] Ừ
[00:42:34] đấy thì các bạn sẽ thấy nó là giống rồi
[00:42:38] nhưng mà rõ ràng là Đây chưa phải là thẻ
[00:42:40] a nên thành ra là nó không kiểu chỉ vào
[00:42:42] để mà trông có vẻ bấm được như này kết
[00:42:45] hợp với việc là ở
[00:42:47] yêu cầu các bạn phải nền nó thay đổi đối
[00:42:50] ngoại thực ra là đứt khi một là các bạn
[00:42:54] không cần làm thẻ các bạn chỉ cần làm
[00:42:55] hiệu ứng thôi Chứ người ta không bấm
[00:42:57] được cũng là một cái cách để ngoài như
[00:43:00] bây giờ mình cứ làm theo chuẩn chuẩn đi
[00:43:02] sử dụng cái spectre mình vừa học đi
[00:43:06] có gì sẽ đẩy đổi đây thẻ này
[00:43:10] mà đây sẽ à hf cho nó thăng các bạn
[00:43:15] thường hay thấy hạt lép đôi khi là một
[00:43:17] cái thằng như thế này
[00:43:19] Ừ chị đã giản là bởi vì à tạm thời không
[00:43:22] biết đẩy nó đi đâu Và không không muốn
[00:43:25] bấm nhảy sang lại trang web khác thì tạm
[00:43:27] để nó như thế này để khi bấm nó vẫn có
[00:43:30] vẻ bấm được đưa ra là chỉ là chẳng để ý
[00:43:33] đâu cả đấy thì thường khó trang web mới
[00:43:36] thường anh sự thăng Hiểu ngay ý
[00:43:39] thì các bạn thấy nó đang rất khó chịu
[00:43:41] cái này tôi không thích cái này đâu
[00:43:43] ngoại thì mình thể
[00:43:44] link này mình sẽ đổi đổi vẫn giữ nguyên
[00:43:48] màu cũ này vẫn màu hoa này trả nợ thế
[00:43:51] Thế mình xóa này đi nhá
[00:43:55] đi hát đây để đạt được hãy cho mình sẽ
[00:43:59] tách đi Collagen sẽ à năm bỏ cái and
[00:44:03] like đi các bạn sẽ thấy là cái này thì
[00:44:05] thẻ không bấm được đầy thế bấm được đấy
[00:44:08] ạ ạ
[00:44:12] ừ ừ
[00:44:14] ờ ờ
[00:44:19] em lấy tiếp theo là mình
[00:44:22] đợi Đợi mình tí
[00:44:24] có bố mẹ mình đến à
[00:45:16] thì alo
[00:45:18] mình đang ở đâu
[00:45:21] Ừ mình đang thuê nhà ở riêng thì da dầu
[00:45:23] bố mẹ để đốt mục loạn một tí Con chó thì
[00:45:27] con chó mình nó hơi bị ngu mình tí Nó
[00:45:31] sủa tất cả ý
[00:45:35] à à
[00:45:39] anh alo cho ạ Vẫn chưa ông là áo mai
[00:45:43] nghỉ Okay tiếp nhá Khi cái này muốn đổi
[00:45:47] cho nó sang kiểu khác thì dùng a server
[00:45:51] thôi đúng ạ
[00:45:53] Em
[00:45:54] à mình sẽ cho nó care là last này
[00:46:00] thế này và cho nó kiểu chữ nó đậm lên đi
[00:46:03] đúng ạ là thôn huyết này
[00:46:07] bồn này khi mà chỉ vào chữ sẽ đậm hơn
[00:46:10] này đó xong rồi mình có thể trách say
[00:46:14] Vậy à Đâu phần sai không sai cho nó sẽ
[00:46:18] to lên là sự 20 hết đó Nhưng mà các bạn
[00:46:22] phải nền nó còn thay đổi được đúng không
[00:46:23] Thế là sao mình sẽ cho nó cả bác ra
[00:46:26] winmate này oll xong rồi cho nó những
[00:46:28] cái ảnh nó thể kiểu đổi đổi khi mà trỏ
[00:46:33] chuột vào lại cái Server này ạ
[00:46:38] à à
[00:46:41] ở
[00:46:41] đó nhớ mà các bạn thấy là ở đây nó nó
[00:46:47] hơi sai sai một tí đúng ạ Các bạn thấy ở
[00:46:50] đây là cả cái cả cái ô nhé không phải là
[00:46:54] cái Hà nó nhé các bạn để ý kĩ là cả cái
[00:46:56] ô rồi khi rõ là một ở đây đang chiếm cả
[00:46:59] cái hàng nhưng bản chất đây là cả kéo
[00:47:00] vui thôi Nó đang được đổi chứ không phải
[00:47:04] là
[00:47:05] mình muốn đổi cho cái bát rau cho cái
[00:47:08] mỗi chữ đối ngoại thì cái làm như thế
[00:47:10] nào Cái này là khi mà cái cái thẻ mà nó
[00:47:16] được vu vơ thì cái thằng cha nó sẽ được
[00:47:20] thay đổi đúng ạ ra xong TD thì các bạn
[00:47:24] sẽ phải TD xong rồi ahaha vơ như thế này
[00:47:29] nghĩa là đây đây là mở - AV đúng không ạ
[00:47:33] thì nó sẽ đổi backgroud
[00:47:35] Ừ đúng nhỉ
[00:47:37] khi cài đặt hình như bị ngược lại đợi
[00:47:40] mình thấy ngược lạ á
[00:47:45] em ở đâu đâu đâu không khó không Nghĩa
[00:47:48] là chỉ cần tới đây hoa vợ rồi thì phải
[00:47:51] bệnh tim I ở đó như thế này ừ ừ
[00:47:59] Ừ cái này cũng được không ạ
[00:48:03] em hết đồ rồi thì các bạn sẽ thấy à
[00:48:07] Ừ ừ
[00:48:08] hình nhờ Đợt này là mình làm nữa
[00:48:13] chỉ cần tới đê
[00:48:15] đây đây đây hoover rồi Thằng A là thay
[00:48:18] đổi cũng được không ạ mình Nếu mình làm
[00:48:20] cái cái này thì nó sẽ ngược lại thôi nó
[00:48:23] sẽ là khi TD hoover này thì tới đây họ
[00:48:26] vợ nhé Thì thằng A nó thay đổi này nó sẽ
[00:48:29] như thế này copy toàn bộ này xuống dưới
[00:48:31] thôi I
[00:48:33] Hồ Ngọc Như nhau cả
[00:48:35] chả qua là bây giờ là mình TD bị ho vơ
[00:48:39] và TD luôn Mình không cần Harvard và thẻ
[00:48:41] nữa đấy nó sẽ như thế này
[00:48:44] ở đó
[00:48:46] ở đâu chưa
[00:48:51] ở trong ổn mà đúng không ạ
[00:48:53] xe tải
[00:48:55] ở đây không phải là cái Menu mà các bạn
[00:48:59] thường máy Thấy bây giờ để cho mình dậy
[00:49:02] đó các bạn hai cái meru mà các bạn
[00:49:05] thường ai gặp thường hay gặp thôi đó tôi
[00:49:09] sẽ dùng Chính hai đối thủ cạnh tranh đó
[00:49:11] là án phát ký
[00:49:14] D10 mua cả hai chị chai cái tôi nhỏ
[00:49:18] có một cái là menu theo kiểu là ông chị
[00:49:21] Đây là lúc đầu nó là menu dọc mà béo để
[00:49:25] kia ông nói mày ngu dọc này đấy nhưng mà
[00:49:28] khi chỉ chuột và từng cái thì nó sẽ hiển
[00:49:32] thị xanh cái ở bên phải nó sẽ mandu kéo
[00:49:35] nó vẫn tính làm nên ngu dọc nha Trả qua
[00:49:37] mày menu nó mới nó khai cấp thức à Chỉ
[00:49:40] vào nó sẽ chị ram cấp con và nó nữa làm
[00:49:43] bánh phạt
[00:49:44] đấy tiếp theo là một cái một ông nữa Ông
[00:49:49] Hà Nội Computer
[00:49:53] ông này thì
[00:49:55] bây giờ nó đổi sang rọc mà
[00:49:58] mình nhớ hồi trước có để nhanh rồi nghỉ
[00:50:00] ở
[00:50:02] anh bắt chước nhau
[00:50:04] ở đây ông mày vẫn còn cái nha này tôi
[00:50:08] tôi dùng hôm nay vậy nha đây ông có thấy
[00:50:10] à Ở trên này nó vẫn là menu ở trên vẫn
[00:50:13] là nhanh được nhé Chỉ vào nó để thị dọc
[00:50:16] xuống đây đưa mà Đấy thì mình sẽ mình sẽ
[00:50:20] dạy các bạn về cái vụ à
[00:50:23] dịch vụ làm được menu treo chiều dọc
[00:50:27] trước bởi vì nó dễ hơn sau đó mình đôi
[00:50:30] theo chiều ngang để bọn
[00:50:34] khi
[00:50:41] gà nói thế thì bây giờ mới Ông chẳng ông
[00:50:45] nào đi ngồi làm menu thuần thuần nữa Nếu
[00:50:48] không đi có sự giao diện về đóng anh đã
[00:50:50] hướng dẫn như thế
[00:50:53] ở tiên là mình sẽ có ul lời đi này rồi
[00:50:57] nha yêu em nói họ Oh Ly Tùy các bạn hãy
[00:51:00] cho kẻ này
[00:51:05] cũng sẽ giống như kiểu này đi theo ngoại
[00:51:08] hành động này à
[00:51:12] a
[00:51:13] kinh dị này ạ ừ ừ
[00:51:18] ở người lớn ạ
[00:51:22] Mình chạy thử lại nha
[00:51:25] đây Thế bây giờ đang chưa Bấm được này
[00:51:28] mình sẽ cho nó 1 cái
[00:51:31] đều cho nó cái Hz thì nó để nó có thể
[00:51:35] bấm được đi
[00:51:37] à
[00:51:38] Các bạn thấy cái Menu như thế này chẳng
[00:51:41] có trang web hợp Tìm kiếm cái ngu kiểu
[00:51:44] xấu xấu ngày đúng không ạ Thế bây giờ
[00:51:46] mình muốn làm cho kiểu menu trở nên màu
[00:51:48] mè thôi cả lại nói hiển thị ở châu rọc
[00:51:50] Thôi bỏ vào đấy nó sẽ hiển thị ra Ví dụ
[00:51:53] là
[00:51:54] kỳ dị này có yếu tố đây giờ sự là thêm
[00:51:58] cả
[00:52:01] từ nhỏ không Ba mẹ để nó Ngoài ra trong
[00:52:03] nha
[00:52:04] mình nhưng ở ngoài này Google một kẻ lý
[00:52:08] và lời y tiếp này
[00:52:10] cái A tiếp này
[00:52:14] là yếu tố hài hước ra ngoài đi
[00:52:17] và yếu tố đây là
[00:52:20] tình cảm của ngài đi
[00:52:24] đấy thì thì bây giờ mình muốn là kiểu
[00:52:28] lúc đầu đây là menu gọi menu 2 cấp đúng
[00:52:31] không ạ nghĩa là có thằng cha này thằng
[00:52:34] con này đúng không ạ Và mình muốn à đầu
[00:52:38] tiên là mình sẽ xóa đi toàn bộ nhưng cái
[00:52:40] kiểu giấu Mấy cái biểu tượng ở đằng
[00:52:43] trước này đi này kết hợp việc là mình
[00:52:45] khi mà Lúc đầu thì cái thằng con nó sẽ
[00:52:48] ẩn đi mình trỏ chuột vào thằng cha thì
[00:52:50] nó mới nhịn đi thằng con khi làm như thế
[00:52:52] nào để bọn nó tin là mình phải ẩn đi
[00:52:54] toàn bộ những cái
[00:52:57] ly này Thảo ul thôi cũng phải display I
[00:53:03] ris play outside Tuynel
[00:53:08] đó bây giờ ẩn đi những cái tưởng tượng
[00:53:10] rồi đúng ạ
[00:53:12] tiếp theo là mấy ông thấy thử làm bài
[00:53:15] toán được cái thằng này nó cũng bị đó là
[00:53:18] nó đang cách mặc định nó cách vào khoảng
[00:53:21] như này tôi muốn bỏ cái cái cái đi mình
[00:53:24] sẽ có mặc định bát tinh bằng không sẽ bỏ
[00:53:27] đi đỏ như này Nếu bỏ đi thì đồng nghĩa
[00:53:30] việc là nếu không thấy nó đang bị như
[00:53:33] này trong một khó chịu đầu tiên mình cần
[00:53:35] thế thằng con đi thằng con đấy đúng
[00:53:39] không ạ thường là nếu thế thì tôi thường
[00:53:41] anh đặt ID thằng cha để mà Ẩn Hoàng Con
[00:53:43] gì nó dễ hoặc là mấy ông đi hẳn hẳn như
[00:53:47] thế này l lời này ul tiếp này thì beat
[00:53:52] mai là năm và sẽ là ngon quá đi này
[00:53:56] ý nghĩa thằng cha này gọi đến thằng con
[00:54:00] này và gọi đến thằng con nữa thì sẽ ở nó
[00:54:03] đi như thế này đấy ông ạ
[00:54:07] khi reset CF
[00:54:09] ẩm thực cả mấy ông mấy hôm nay nhắc đến
[00:54:12] ri sexy nó cũng chả hiểu lý sách sẽ trả
[00:54:14] lời gì cả thì tôi thử tra xem
[00:54:21] displace để ẩn nào đi Như thế này đều
[00:54:23] ngoạn đấy tiếp theo nữa đó là mấy ông
[00:54:27] muốn trỏ chuột vào thì nó ảnh hiển thị
[00:54:28] ra thì thế nào đúng không ạ
[00:54:30] thì mình sẽ là ở mỗi với mỗi nồi ý khi
[00:54:37] mà ho vơ vào thì euler sẽ ít lây là blog
[00:54:42] là thì chị ra cản
[00:54:44] đó hay không này
[00:54:48] và bây giờ Ông mấy ông có thể hoàn toàn
[00:54:51] thêm những cái yếu tố kiểu đẹp hơn làm
[00:54:54] như là mình sẽ cho nó 1 cái background
[00:54:58] color là màu hồng đi
[00:55:01] xong ngồi
[00:55:03] chữ là màu đỏ
[00:55:07] rồi
[00:55:09] khách đi coi chừng bỏ đi thẳng a
[00:55:15] âm mưu trên wii cho cái này chỉ là 200
[00:55:19] mét thôi 3 Đây là một
[00:55:22] Souls II a black Đà Nẵng
[00:55:27] vào như thế này
[00:55:30] Anh chỉ bảo nói ra nhưng mà cái và Toán
[00:55:33] chỉ và hiển thị ra này nó sẽ gây khó
[00:55:35] chịu cho bé ông của thì tôi muốn nó chui
[00:55:37] sang bên này cơ không phải chui ra như
[00:55:39] thế này không ạ Cái bao đời này đang hơi
[00:55:41] dính dính với nhau
[00:55:44] bother này nó đang bị đè lên nhau nên
[00:55:46] nói chung càng giá ngay đúng ạ Mình có
[00:55:48] thể chỉnh cho nó tách ra một tí nó mắc J
[00:55:51] nói gì đó
[00:55:54] thì tại sao tự nhiên tôi phải đi cập
[00:55:56] Border đấy thì tí mấy ông sẽ hình dung
[00:55:58] được việc là nó đang chiếm bao nhiêu bao
[00:56:00] nhiêu bể quý cả các thứ thứ ạ
[00:56:05] Ừ nhưng mà cái này đang rình cái này nó
[00:56:08] đang bị đè với nhau chúng cảm giác khó
[00:56:10] chịu nghỉ mình có thể là
[00:56:14] mecghi mắt Model I
[00:56:20] ở đâu đấy xem nhé
[00:56:21] [âm nhạc]
[00:56:24] nhớ rồi đấy làm như thế nào đấy mình có
[00:56:27] làm ở đây rồi
[00:56:28] Trông cái này không phải đỡ À đấy tôi
[00:56:32] làm cái bạn này như thế nào nhỉ Đợi xin
[00:56:35] phép một phút thì xem lại không nhớ lấy
[00:56:37] đi làm nhà luôn ly
[00:56:41] a Google thôi thử xem ạ này
[00:56:45] lâu rồi tôi không làm chúng cặp
[00:56:50] vẫn thế mà bị bắt
[00:56:53] à à
[00:56:54] nhà
[00:56:55] xe mạnh nha à
[00:57:00] a mother
[00:57:02] em bỏ qua Võ Xuân lifegoeson Tím Minh
[00:57:06] triệu rồi
[00:57:08] phim hài
[00:57:10] Ê biết à
[00:57:12] em
[00:57:13] có gửi cho nó 1 cái hay đi 50 Tết Ừ đúng
[00:57:17] rồi đúng rồi nó sát vào nhau rồi mà mình
[00:57:20] chỉ hay cho nó khách ra thì nó sẽ không
[00:57:22] bị dính vào nhau nữa
[00:57:23] là lâu nó vẫn thế mà vì rồi mình sẽ cho
[00:57:27] nó bị rồi à
[00:57:31] à
[00:57:36] a
[00:57:37] color Black của tôi đang không có này
[00:57:40] không ạ
[00:57:44] ừ ừ
[00:57:47] khi
[00:57:48] con đơn này phải đi đè và cái A nó không
[00:57:51] ạ
[00:57:52] này năn số ít
[00:57:57] À nó chịu rồi chưa hiểu tại sao nó có nó
[00:58:01] cái đèn nhau nha tạm bỏ qua đi đã Em
[00:58:05] à nhớ Bây giờ cứ tạm bỏ qua vụ bother
[00:58:09] bây Làm thế nào để cho nó sẽ sang bên
[00:58:12] phải của cái này như vừa rồi Các bạn có
[00:58:15] thấy qua người mẫu được ra là mình sẽ
[00:58:17] chỉnh cái này là có reason nhớ một con
[00:58:20] Sơn nó nhọn sau đó thì thằng này sẽ làm
[00:58:22] cha thằng con nó sẽ nổi hiển thị lên
[00:58:26] nhưng mà cách thằng cha ở bên phải trở
[00:58:28] lại không ạ
[00:58:29] Nó sẽ là ờ
[00:58:32] mỗi ngày sẽ có Sơn là Huế tiếp
[00:58:37] thứ ba thằng ngày Khi mà được kế thừa
[00:58:40] Khi mà gọi ra được nghe nó
[00:58:43] Google họ đến nơi dai covers thế này thì
[00:58:49] thằng này phố sơn nó sẽ là a absolute
[00:58:52] trở lại à
[00:58:57] th2 sẽ à day là sự cách right 200pf này
[00:59:03] à
[00:59:06] thì trừ 200 kế
[00:59:10] đó nó như thế này bạn thấy được gà Nó bị
[00:59:13] nó bị một tí ở đây bởi vì À cái này nó
[00:59:17] liên quan đến ba đây nữa bộ đồ nó là bao
[00:59:20] đời Trái bộ đội phải làm cho nó bị rách
[00:59:22] da như thế này thì mình sẽ phải là 202
[00:59:25] nóng sẽ được đó như này và đương nhiên à
[00:59:29] Vì nó có thêm một tí ở đây nữa nên là
[00:59:32] mấy ông ngoại cắm trình căn chỉnh tí cho
[00:59:35] đẹp à
[00:59:37] chỉ đứng ngắm nhìn giao diện thôi thì
[00:59:39] mày Ông cố tuần nếu không bị nó hỏi nó
[00:59:42] đẹp được cả chỉ là mức tương đối thôi
[00:59:49] Ừ thì mấy ông sẽ thấy là nó sẽ cách như
[00:59:52] này thì mấy ông Chị có thể có có thể
[00:59:54] chơi bằng cách này đây à
[00:59:59] Mở bài nhạc hàng ngày đúng không ạ
[01:00:02] ờ ờ ờ
[01:00:07] à à
[01:00:13] thì
[01:00:15] mình sẽ cho một cái đây là tốp là
[01:00:21] 3 - 10 pack à
[01:00:24] à à Ô
[01:00:27] thế hạnh - 10 rồi nghỉ đợi vậy Tí hình
[01:00:31] như không đấy hả - 10
[01:00:38] Anh Phan định chỉ em béo mà có thể thay
[01:00:41] rồi cái gì 10 ngay ở trong clip tu này
[01:00:42] nè Nhưng có vẻ cái hồ vơ nó không thì
[01:00:44] chị ra hơi khó lấy cho mình cứ phải giảm
[01:00:48] dần làm nhân vật thể
[01:00:53] ở đó - 2 - 2 cái này đúng rồi đấy Chẳng
[01:00:57] qua là do cái này là nó bị đè lên cái bò
[01:00:59] đơn nên chồng có thấy đâu nhé á Ừ thôi
[01:01:02] thì Dạy vẽ ở mức tương đối mà đúng ạ
[01:01:05] Cái này vừa rồi tôi còn nói qua đó là
[01:01:08] ông đang bị Tuy là ông để cho cái ly nó
[01:01:11] là mộ màu đỏ nhưng mà như tôi từng nói
[01:01:13] đó là thằng nào gần gần nó hơn họ sẽ ghi
[01:01:17] đè CF lên hơn thằng thẻ a này nó gần hơn
[01:01:21] Xóa Thằng lời dai nên hành gia nó vẫn
[01:01:23] ghi đè CS của thằng Thế lên một là ông
[01:01:26] ghi đè hẳn CS của thằng thể A2 là không
[01:01:29] phải thêm importance vào trong này để
[01:01:30] cho nó ghi đè lên tất cả những cái thằng
[01:01:32] khác không có đi vào tân đấy thì ông có
[01:01:36] thể hoàn toàn ghi vào thìa như thế này
[01:01:38] cũng được color-les và thaek bị coi
[01:01:40] chừng là năm như thế này hay gì ở đây
[01:01:43] thì nó sẽ làm mất đi thế này nó cho nó
[01:01:47] cũng đỡ hơn rồi mà nó không ạ
[01:01:55] Em bấm vào chưa có vở Tôi chưa thử ngủ
[01:01:58] đãi về theo tôi mà phát Đấy nói chung
[01:02:01] nhà vừa rồi chỉ cho các bạn Ngang Qua về
[01:02:03] việc làm menu menu
[01:02:07] dọc đường ạ Cái có mấy nung anh phải ra
[01:02:10] mày ngủ nhanh thì ra chỉnh theo đúng như
[01:02:12] cái form này nó cũng nhanh thôi
[01:02:14] đây tôi thể
[01:02:17] Ừ vậy thì chị méo Nhanh nhá Còn chắc là
[01:02:19] vẫn thể giữ nguyên tất cả đúng này nhá Ừ
[01:02:24] à à
[01:02:26] thì
[01:02:27] mình cứ xóa đỡ đầu tiên là tôi muốn cho
[01:02:31] cái này nó sang ngang đã đúng ạ thì
[01:02:34] thường là tôi sẽ chơi cái trò nó là
[01:02:35] flash nép mình sẽ trôi hết tất cả cái
[01:02:39] bản chất là từng cái lồi này sợi đít nó
[01:02:43] sẽ display-block cái Vlog này này là sẽ
[01:02:46] đẩy thằng khác xuống dòng cái cái
[01:02:49] display-block này có nhiều thẻ nó sẽ con
[01:02:52] display-block có nhiều thẻ dispray nó
[01:02:54] lại in life in like thức à nó sẽ vẫn nằm
[01:02:58] trong cùng một rằng Đấy cùng đồ lót thì
[01:03:00] nó sẽ nó thêm nó giống hiểu thêm một cái
[01:03:03] Basel đấy để giúp sáng kia nhảy xuống
[01:03:05] dòng những cái thằng với những hàng like
[01:03:08] thì các bạn từng thấy rồi nó lại bị biết
[01:03:10] nó thấy Maria này phải spam này có thể
[01:03:14] dịch nha Em hãy input này lại là khi hòa
[01:03:19] thể gót chân này không ạ khi mà các bạn
[01:03:21] sử dụng sang thẻ này các bạn thấy hoàn
[01:03:23] toàn là nó vẫn nó vẫn không xuống dòng
[01:03:26] các bạn phải thêm PR để nó xuống gặp con
[01:03:29] những cái mặc định nó sẽ giúp chúng ta
[01:03:30] với Như ạ Các Thẻ H1 H2 H3 này đúng
[01:03:33] không ạ thẻ thấy bồ này form này thẻ
[01:03:38] Em đừng như thế bây rồi chắc chắn xuống
[01:03:41] thôi à Còn thể diện nhé
[01:03:43] thẻ đúng ngoài thể lấy này đúng không ạ
[01:03:47] à còn gì nhỉ
[01:03:49] anh ấy lại Thái Tôi nhớ Thế hả đúng
[01:03:51] không phải tên nữa quan trọng bên đấy
[01:03:54] thì những thẻ này khi mà đúng rồi phải
[01:03:57] đít nữa nhỉ những cái thẻ này khi mà nó
[01:04:00] đóng xong ấy nó sẽ luôn đẩy khác xuống
[01:04:03] dòng và các bạn nhớ đặc biệt cái thẻ đi
[01:04:06] uống trước các bạn nhớ để mà nó cùng nằm
[01:04:08] trên cùng một dòng thì các bạn sẽ phải
[01:04:10] flashless
[01:04:11] đúng rồi in like thiếu và cái a nữa Khi
[01:04:14] mà đóng thể là các bạn thấy nó vẫn nằm
[01:04:16] trên cùng một dòng đúng ạ
[01:04:19] tôi là lúa tục không nhớ hết rồi
[01:04:22] thì vợ mình muốn cho cái lỗ ý khi mà
[01:04:27] nhớ ở mình chỉ muốn cho cái này nó xuống
[01:04:30] dòng thôi Còn cái còn cái thang này vẫn
[01:04:32] Dự là cái tháng ngày không xuống dòng
[01:04:34] còn thằng này vẫn sẽ xuống lòng ấy thì
[01:04:36] mình chỉ có
[01:04:38] cool gọi đến lợi y
[01:04:41] anh như này ra sự flash kép nhé là cho
[01:04:44] nó cũng nằm trên cùng một dòng này
[01:04:49] anh đợi mình đi lấy đó
[01:04:55] à à
[01:04:58] khi đó nó sẽ như này
[01:05:01] Anh chỉ vào này
[01:05:04] có nên sang chợ giờ này chỉ vào các bạn
[01:05:06] thấy à nó sẽ
[01:05:08] nó đang top như thế này thành ra bị bị
[01:05:11] nhảy không ạ thì trong trường hợp này
[01:05:13] mình lại phải chỉnh lại một tí
[01:05:17] a picture này vẫn vẫn thế là lần này
[01:05:20] Like nó không nghe ngày nữa mà mình
[01:05:22] chỉnh top
[01:05:23] dụng là
[01:05:26] ở top sẽ là
[01:05:30] U50 bếp chẳng hạn
[01:05:34] số 52 52 -
[01:05:38] 5 Út à à
[01:05:42] U22 51 ở chỗ Quảng Trị tương đối được
[01:05:45] ngay thôi ông ạ và các bạn thấy được ra
[01:05:48] nó vẫn còn cái dính tí ba đây cái thử
[01:05:50] nữa nó đương nhiên ở đây đang ví dụ thôi
[01:05:53] Thường mấy ông chẳng chưa portal.dau thì
[01:05:55] mới ông sẽ cắm cái này nó sẽ khá khớp
[01:05:57] không ạ
[01:05:59] đó thì các bạn thấy là một khi mà làm
[01:06:02] cái Menu dọc song đội xong daruma chỉ
[01:06:05] cần thêm cái flashless là xong
[01:06:08] nhớ rõ rồi còn BT cốt mấy ông hoàn toàn
[01:06:13] thể xem tham khảo lại để làm
[01:06:18] anh hả Mà ông đã nghe được karaoke hàng
[01:06:20] xóm của tôi hai mấy ông đang than phiền
[01:06:22] cái karaoke hàng xóm nhà ông ấy
[01:06:25] ừ ừ
[01:06:27] ừ ừ
[01:06:30] ẩm thực tế thì cái này không liên quan
[01:06:33] một tí nhưng thực tế là tôi từ mới khỏi
[01:06:35] gọi 113 thì xử lý hàng xóm
[01:06:39] tử vi hàng xóm hát Quá ồn nửa đêm và
[01:06:44] mấy ngày liền như thế không hiểu Nó kiểu
[01:06:48] Liên Hoàng cái gì
[01:06:51] Ừ thì cho ca thì các bạn cái này cái bài
[01:06:54] toán yếu tố của đây đó là tôi không phải
[01:06:58] ác thì đâu ra mấy người này có bị phạt
[01:06:59] gì đâu tuy Phạm Chuẩn là phải pha đấy
[01:07:03] anh Bởi vì theo luật nó thế các bạn thứ
[01:07:06] hai Đăng Khôi bị sai việc là à
[01:07:10] thì các bạn đương nhiên là nếu mà một
[01:07:13] ngày như thế thôi châm chước người ta
[01:07:15] còn nhiều ngày thật là người ta người ta
[01:07:18] kiểu không quan tâm các bạn các bạn
[01:07:19] chẳng cần quan tâm người ra à
[01:07:22] vì tình cảm Nghĩa xóm Thực ra lõm ảnh
[01:07:25] hưởng nhưng thực ra tôi thuê nhà nó cũng
[01:07:27] chẳng nên là cũng chả liên quan gì cả
[01:07:30] À hôm ấy tôi định quà nhắc nhở hàng xóm
[01:07:32] ấy chứ nhưng mà người ta hát quả kho nói
[01:07:34] từ đập cửa người ta ở không không để ý
[01:07:36] thậm chí công an đến đập cửa gọi liên
[01:07:39] tục 13 không để ý con cơm Công An bậc
[01:07:42] của trường Công an đập đập cửa hơn mười
[01:07:44] phút đồng hồ không gọi được chưa Thế
[01:07:48] thì ông phải hiểu rằng người ta đang hát
[01:07:50] nó như nào không quan tâm Trời đất gì cả
[01:07:52] kệ luôn á
[01:08:01] Ừ thì
[01:08:03] thực Hà nói qua một tí vụ đấy Đó là thứ
[01:08:06] ra nó tính Tôi không thích làm ảnh hưởng
[01:08:09] khác thế được là cái đấy nó liên quan để
[01:08:11] ô nhiễm âm thanh giờ trải nghiệm không
[01:08:13] tốt
[01:08:14] em ở thành phố rồi này bị ô nhiễm âm
[01:08:16] thanh tự vệ có chữ ạ ạ
[01:08:20] à à Ừ thì bây giờ 9 giờ cho các người ta
[01:08:24] cũng cái kệ mấy ông tra Google về ô
[01:08:28] nhiễm Thanh là thừa Đôi khi phải đến cái
[01:08:31] tâm số bao nhiêu bao nhiêu thì nóng đó
[01:08:33] là phạt các thứ thử cơ à
[01:08:37] ừ ừ
[01:08:39] em ở chỗ là đầy đủ kiến thức ngày hôm
[01:08:41] nay ở đông lạnh bài tập thì tôi còn nói
[01:08:43] qua rồi tôi chia sẻ chị xem tôi sẽ chia
[01:08:48] sẻ cho mấy ông cái gì
[01:08:50] Ê hồi trước ở tôi tìm được cái á sẽ hai
[01:08:54] cực cái HTML để mà chị với cả giao diện
[01:08:56] kiểu nó
[01:08:58] 22p cái ạ âm lượng cơ chia sẻ trong nhóm
[01:09:01] mình rồi tôi tìm lại bài đấy không được
[01:09:08] em chẳng nhớ là tại chết sạch
[01:09:17] Ừ cái gì nhỉ Lưu nhớ không nhớ nó cái gì
[01:09:21] nữa
[01:09:21] à à
[01:09:26] ừ ừ
[01:09:30] à à
[01:09:39] sau
[01:09:40] khi nhảy dây lành mạnh nha À à OK thực
[01:09:44] ra cái gì đó hồi trước tôi có đọc Đó là
[01:09:46] thức đặc biệt ở Dân công nghệ như bọn
[01:09:48] tôi yêu thật đậm kiểu tập thể dục thì
[01:09:52] cái vụ nhảy dây ý thì cái là nó rất là
[01:09:55] tốt đó là kiểu nó cũng là tập thể dục
[01:09:59] kết hợp việc à Đừng đừng Nghĩa nhảy sai
[01:10:01] chỉ thành con gái gì đó mà nhảy dây nó
[01:10:04] sẽ là vận động được Toàn có thể cả chân
[01:10:08] cả tay và rất nhiều cơ như mấy ông để kỵ
[01:10:11] đọc đọc đọc thử nghiên cứu hết thì mấy
[01:10:14] ông sẽ thấy thế nhỉ dây nó vận động rất
[01:10:18] nhiều cơ ông kia nó đá bóng đá bóng
[01:10:20] không vận động cản trở cả tay đâu đúng
[01:10:22] không ạ thì ạ
[01:10:24] Ừ thì nhảy dây nó sẽ làm cho cơ thể Ông
[01:10:27] vừa dẻo dai hơn vừa vận động được nhiều
[01:10:31] cơ Cá thứ mà làm tại nhà được đúng ạ
[01:10:34] Mình cảm thấy ạ Mấy ông nên ngoài thế
[01:10:38] xong tự nhiên ngày hôm sau đấy
[01:10:40] tiền tiền bán bàn về cái dây ở tăng ra à
[01:10:47] Ê
[01:10:49] mấy ông kia đang Đề cập về những cái môn
[01:10:51] thể thao khác đơn nghĩa mỗi thể thao Nó
[01:10:53] sẽ vận động theo khá nhiều đôi khi là
[01:10:56] toàn bộ cũng kiểu nghị tương tự như thế
[01:10:58] và nó đỡ chỉ thích hơn tình yêu Tổ thích
[01:11:01] bơi lặn bơi khá tốt nhưng mà
[01:11:04] nhưng mà đang nói là ông luyện tại nhà
[01:11:06] cơ mà đúng ạ được tại nhà mấy ông một là
[01:11:09] ông chạy bộ tại nhà hay ông những dây
[01:11:12] hoa cả làm kiểu tập gym hoặc tập võ tại
[01:11:16] nhà nhưng mà cho J10 võ thì cả nó này
[01:11:20] đôi khi chuyển hướng hẳn với một cái cơ
[01:11:22] vì đó không phải liên quan hiểu dai võ
[01:11:26] thì còn tí dẻo dai một cứng cáp nhưng mà
[01:11:28] nó không hiểu Nó không vận động được
[01:11:30] toàn thân nếu mà ông không Ông không tập
[01:11:33] toàn bộ các các động tác thế hiểu vấn đề
[01:11:37] dây về cơ bản thì nó sẽ luôn luôn kích
[01:11:42] thích tất cả các cơ của ông trừ khi ô
[01:11:45] không nhỉ Không nhảy dây đúng thế thôi
[01:11:47] xe tải Cờ Thế à
[01:11:57] ừ ừ
[01:12:00] a
[01:12:13] ha bị giảm khả năng sinh con thì rung
[01:12:17] lắc quá nhiều ạ ạ
[01:12:19] Ê mấy ông mạnh thì đương nhiên nếu phải
[01:12:22] mặc bộ đồ thể dục để tránh rung rồi à
[01:12:27] ạ
[01:12:37] Bây giờ chẳng biết chia sẻ với ông cái
[01:12:39] gì nhỉ Dạo gần đây rồi ca tôi tôi tôi
[01:12:42] từng nói rồi đỡ Hà môi cứ chảy về những
[01:12:45] cái phần mềm Tôi đang dùng đi à
[01:12:48] ở đây à
[01:12:56] từ hôm nay sắc là mấy ông không biết từ
[01:12:59] hôm trước rồi Chắc thế nó không thắc mắc
[01:13:01] về cái vụ biểu tượng biểu tượng này của
[01:13:06] tôi tượng này tôi Dũng thôi à Cũng như
[01:13:10] không trả lời rồi cũng chưa sợ đâu rồi
[01:13:12] dùng Cài classic sail này để mà thay đổi
[01:13:15] tượng này
[01:13:16] Thật ra tôi hội đấy tôi dùng thêm cái cứ
[01:13:20] Lina này để đề mà cô ấy thích cậu dọn
[01:13:23] rác với vùng thì về sau trận ra mình
[01:13:25] lười quét cái này lắm
[01:13:28] Nhưng trên này ra nó còn có người cái vụ
[01:13:31] là kiểu Xóa dùm cái ứng dụng vì nó nhanh
[01:13:34] đây toàn bộ những phần mềm tôi đang cày
[01:13:37] ngoài mấy phần mềm vô số Tôi không nói
[01:13:39] thì tôi nói qua thứ nhất ở cái cái
[01:13:41] anydesk này cho thể ndtec này
[01:13:44] ở gần đây có vẻ tôi và dẫn công nghệ
[01:13:47] dùng nhiều hơn
[01:13:49] khi dùng có vẻ tốt hơn cái Teamviewer
[01:13:52] rồi cậu là gì
[01:13:54] Ừ nó
[01:13:56] Ừ thôi không biết nói nó tốt hơn về
[01:14:00] những cái gì nữa nhưng mà tôi khuyên với
[01:14:01] ông thử dùng qua mấy ông sẽ thế là nó
[01:14:04] thích hơn teamview và ít nhất là nó
[01:14:05] không đòi nó không có giới hạn thời gian
[01:14:08] như làn teamview lỡ khó chịu được hả
[01:14:10] Which are viewed được cho nó không giới
[01:14:11] hạn thời gian các thứ II
[01:14:15] ờ ờ còn gì nhé
[01:14:19] Ừ cái cloud Phen này là để thỉnh thoảng
[01:14:22] tôi Cậu muốn kết nối đi ra ngoài nó là
[01:14:27] VPN để kết nối sang một cái trang Army
[01:14:31] cái kiểu server nước ngoài
[01:14:34] Vì vậy tôi làm việc với đội ta nước
[01:14:36] ngoài phải mở ngày lên nó chạy cái
[01:14:40] clownfish này tôi gần đây tôi cài để mà
[01:14:45] thay đổi giọng gà Nó cũng chẳng thay đổi
[01:14:48] được mấy số tưởng được cài xong giọng
[01:14:50] rồi sẽ đến anh nữ nữ Nhưng mà không
[01:14:52] chẳng ngọt ngào gì cả
[01:14:54] Bởi vì tôi xem mấy cái video của mấy ông
[01:14:57] trên blog tự nhiên kiểu đôi dặm ông ấy
[01:15:02] kiểu đang rộng chậm năm tình ngoại rồi
[01:15:04] thằng giọng nữ rồi sợ đi lừa với thằng
[01:15:07] khác được cô che Vậy thì cờ thấy hay hay
[01:15:11] với định kiểu K thể trêu bạn cuối cùng
[01:15:14] Giọng tôi chị dành cho trò ơi buồn vãi
[01:15:16] sao phải mất tiền của vụ này
[01:15:20] ở nhà anh Tuấn cũng mua hẳn cái mất tiền
[01:15:24] rồi đấy nhưng mà tôi tay thử cái đấy
[01:15:27] cũng biến thành giọng nữa đâu cũng chẳng
[01:15:29] ngọt ngào đấy
[01:15:34] Ồ không Tôi đang dùng cái mic xịn như
[01:15:37] tội trạng dùng ngay cái đấy em gì là tôi
[01:15:39] dùng cái đấy trời xoay trai sẵn có
[01:15:42] Ừ cái này đi bây girl này có vẻ miễn phí
[01:15:46] mà kệ kết hợp việc là nó hỗ trợ được khá
[01:15:48] nhiều DB này mày Ông Mười xóm cân nhắc
[01:15:51] có cái cày cái này
[01:15:53] A discourse thì mấy ông cho biết qua rồi
[01:15:56] à
[01:15:59] Ừ kệ bi sinh này nghệ bị sinh này là để
[01:16:02] tìm kiếm một cái gì đó rất là nhanh ở
[01:16:04] trên máy của ông Ông không cần phải chọn
[01:16:07] thư mục bất kỳ ông chuẩn gõ tên bức Kim
[01:16:10] wi-fi nó đó tốc độ Tìm kiếm của nó nó sẽ
[01:16:13] nó ra nào giống như nó bánh đất toàn bộ
[01:16:16] những cái file trên máy ông để tìm kiếm
[01:16:18] nó sẽ nhanh hơn Tìm kiếm thông thường
[01:16:21] bằng Windows XP is pro này rất nhiều nếu
[01:16:25] nghịch cài này cái này nó chị chỉ trong
[01:16:28] vòng ở đây tìm cái gì đó cho Quỳnh ra
[01:16:33] nhé á
[01:16:35] Anh Thương Nhiều lúc đầu nó có phải đợi
[01:16:37] một tí vui vì ạ
[01:16:38] thì nó đang đây là lần đầu tiên lần đầu
[01:16:42] tiên Lâu lâu không chạy hoa cà ông không
[01:16:46] để nó mở tự động ấy thì nó sẽ không bán
[01:16:49] đất cho toàn bộ file
[01:16:51] Nhưng mà nếu ông dùng thường xuyên rồi
[01:16:54] thì nó sẽ nhanh
[01:16:56] đời Hình như là tôi pháp sư cái tự động
[01:16:59] chạy của nó rồi Thằng Anh nó bị đơ thì
[01:17:01] không Bọn Phát
[01:17:05] Nghe
[01:17:07] đài tiếng nói tự tắt sự của nó rồi
[01:17:10] à à
[01:17:13] Ừ nếu mà cài cái này xong bê tông sẽ
[01:17:17] kiểu gõ cái gì Nhận dạng xảy ra rất
[01:17:19] nhanh đấy như thế này phải không Tôi có
[01:17:23] gì đâu nó tìm kiếm nhanh lên đấy thì ông
[01:17:25] sẽ thấy được là nó nhanh như thế nào
[01:17:28] đúng
[01:17:29] ừ ừ
[01:17:31] thu hẹp này tôi cái ép này nó hơn cái tự
[01:17:36] động tự động điều chỉnh cái Windows là
[01:17:40] da nó có tự động điều chỉnh độ sáng đấy
[01:17:44] Sáng độ sáng tiếng Anh là cái gì nhỉ
[01:17:47] trước
[01:17:49] a close friend à
[01:17:54] vì
[01:17:56] nó có chỉnh độ chế độ natri này nhưng mà
[01:18:00] nitrites tinh của nó thực ra Nó chỉ có
[01:18:02] mỗi
[01:18:03] treo khoảng mặt trời mọc và mặt trời
[01:18:06] lạnh hết Nó không chỉ theo tuần thời
[01:18:08] gian trong ngành này tự nhiên phải nhìn
[01:18:11] đất vậy thì sẽ tạo một cái một cái file
[01:18:15] như một cái thư mục hay file gì đó Tìm
[01:18:17] mã trên đất thì có pha nhấn nhẹ thôi
[01:18:20] mình nghĩ là không ảnh hưởng gì nhiều
[01:18:22] lắm đâu
[01:18:23] Ờ
[01:18:25] nó sẽ theo mốc thời gian trong ngày như
[01:18:28] thế này Từ chỗ ông xem em nhảy nó sẽ có
[01:18:32] rất nhiều mốc và đặc biệt ông còn có thể
[01:18:34] tự có chỉnh nó nhưng các thứ thứ nữa
[01:18:36] thành ra là tốt hơn so với việc tự động
[01:18:40] của thằng Window có mỗi hợp đến bình
[01:18:44] minh thì bảo lên hoàng hôn xuống hết rồi
[01:18:47] nên tôi thấy mà ép này hơn
[01:18:50] Hoài vì là để 7 để mà đẩy cốt của ông
[01:18:54] main hosting ai cái gì đó Mạnh cũng cần
[01:18:57] này get em thế này
[01:18:59] I get up this popular ghi thôi
[01:19:03] Tải Google Chrome trình duyệt tôi thấy à
[01:19:06] về cơ bản thì gần đây tôi dùng nó vẫn
[01:19:09] rất tự nhiên nó giật giật Chắc là cài
[01:19:12] thêm nhiều tiện ích nhưng tôi cảm thấy ạ
[01:19:14] Bởi vì nó có sẵn tích hợp tài khoản
[01:19:17] Google nên là tôi vẫn ngại thay thế nó
[01:19:19] so với thăm hết hay là thằng Cốc Cốc ạ
[01:19:24] Ê
[01:19:24] thằng Firefox thừa rõ ràng hả Mấy thằng
[01:19:28] ấy có những cái điểm mạnh ghi âm
[01:19:31] khi Internet Download Manager
[01:19:34] ô tô mua sự bản quyền rồi người ta nó
[01:19:36] rất là rẻ nhưng cụ mày Việt thì phải bốn
[01:19:39] trăm rưỡi hay 500 gì đấy mà trọn đời nên
[01:19:42] khởi nghĩa là nó cũng xứng đáng khi mình
[01:19:44] có tiền thì mình nên mua cái này tốt để
[01:19:46] mà tải rất nhiều cái thứ nó còn Hỗ trợ
[01:19:49] nó giống kiểu thằng Cốc cốc cái kiểu nó
[01:19:50] tự động gợi ý những cái để mà tải video
[01:19:54] hay à Hay nhạc gì đó A lagon để mày ông
[01:19:59] với 6 chốt này à
[01:20:03] Ừ cái Logitech option để mà cho phù hợp
[01:20:07] cho một cái cái chuột Hình như từng nói
[01:20:11] qua rồi một con chuột đầy nút của tôi về
[01:20:14] thôi chỉnh cho rất nhiều cái nút ở trên
[01:20:18] chuột tôi Thành rất nhiều đây còn cho
[01:20:20] tôi đang dụng này thì ông sẽ thấy nó có
[01:20:22] rất nhiều cái nút để thể bấm vào và tôi
[01:20:24] cấu hình hết cho nó dụ lại bấm bấm nút
[01:20:28] này mở
[01:20:30] tắt cái cửa sổ này đi này sạc cửa sổ
[01:20:33] xuống ăn gì đó chúng rất là ngon
[01:20:37] gì hết này tôi vẫn chưa gỡ này à
[01:20:41] Ê mày Cái này đưa ra mặc định của
[01:20:45] Ê mày cái này tôi nói qua mấy Ông Nếu
[01:20:48] mấy ông không biết mày mấy cái SQL
[01:20:51] Server này
[01:20:52] Anh
[01:20:53] thật là mấy cái C + + này nhiều hồi
[01:20:58] trước chính tôi là người gỡ phải đi gửi
[01:20:59] tôi chẳng hiểu Nó là điểm gì nhưng về
[01:21:01] sau tôi chuẩn về sao Thôi mẹ ân hận là
[01:21:04] bởi vì ạ gỡ cái này song nhiều cái phần
[01:21:06] mềm không chạy được bởi nhiều phần mềm
[01:21:07] để bắt buộc phải có cái này nó chạy được
[01:21:10] Thế Chi móng cài một phần mềm mà đó là
[01:21:12] đôi khi là nó sẽ cài thêm những cái hỗ
[01:21:14] trợ cho cái ấy chạy và nó chính là C + +
[01:21:17] hai cái gì đó acid servo kia là để mặt
[01:21:20] ngôn ngữ để mà chạy cái phần mềm đấy
[01:21:22] hoặc lại em quê server để lưu lại các dữ
[01:21:25] liệu của phần mềm đấy thế nên là mấy ông
[01:21:28] gỡ cái này ra mấy phần mềm viện không
[01:21:30] chạy luôn đấy thì nữa Đừng đừng như tôi
[01:21:33] nhé
[01:21:34] khi
[01:21:34] tôi dùng cái á stickynote Để mà kiểu nó
[01:21:39] Nó kiểu nốt luôn kiểu hiển thị ra đây nó
[01:21:42] rất là tiện nhưng mà tôi vẫn dùng luôn
[01:21:45] cả thằng mai có súp doo doo
[01:21:48] a thodu này bởi vì a tôi thấy nó đồng bộ
[01:21:50] lên cả trên qua điện thoại của tôi nữa
[01:21:52] Nếu dùng sai rõ là có những có một vài
[01:21:55] phần mềm khác cũng tương tự nhưng mà nó
[01:21:57] không có cả ở windows nó cả cả ở
[01:22:01] cả trên điện thoại nên tôi thích dùng
[01:22:04] thằng này
[01:22:06] a viscose tôi lỡ cài tôi tôi sẽ xóa đi
[01:22:12] Ừ cái này nghe mặc định của cài Win mấy
[01:22:15] cái này có này
[01:22:17] xe máy ép wespen này ra tôi thấy không
[01:22:20] thích lắm à
[01:22:21] Ừ cái này tự nhiên mày Ông thấy bình
[01:22:25] thường cái cái cái này cho miễn phí
[01:22:29] ở công ty nhé
[01:22:32] ở đây tôi lướt qua xem còn gì không
[01:22:41] ừ ừ
[01:22:41] [âm nhạc]
[01:22:46] ở Zalo cho bạn nào kiểu chưa biết thì
[01:22:49] chơi lô này nó là cái á cũng là để mà
[01:22:55] Ừ cái mặt để mở quản lý các công việc
[01:22:58] của ông các thứ thứ ông ghi chủ lại tôi
[01:23:01] là một người ghi dù rất là nhiều bởi vì
[01:23:03] mình không nên mình không nên kiểu cậy
[01:23:07] não mình nhớ tốt mình tôi bảo rồi những
[01:23:10] cái gì mà máy tính làm được thì mình
[01:23:13] không cần phải nhớ Nhưng hãy để máy tính
[01:23:15] làm vụ đấy đúng ạ Hãy để não mình kiểu
[01:23:19] thứ thư giãn một tí cậu không cần lấy
[01:23:21] nhớ mời ông đôi khi thật nhớ đủ thứ
[01:23:25] nếu phải nói phải ghi chú lại hết các
[01:23:28] thứ thứ và ghi chú cách khoa học đối thủ
[01:23:31] ghi chú rất nhiều Tôi thấy khả năng làm
[01:23:34] việc của tôi nó cũng là rất chuyên
[01:23:36] nghiệp đi tôi phải dùng từ chuyên nghiệp
[01:23:38] bởi vì ạ tôi ghi chú lại rất nhiều cái
[01:23:41] khi mà tôi nói chuyện với các đối tác
[01:23:43] hay nói chuyện với sếp tôi Mở ghi chú
[01:23:45] tôi lên rồi tôi nói nói cậu liền mạch
[01:23:48] các cư xử rất ổn mà giống như ở bản báo
[01:23:50] cáo có người chửi xong rồi Kiểu
[01:23:52] ở những kẻ anh em đồng nghiệp khác của
[01:23:55] tôi thì kiểu
[01:23:57] chẳng ghi chú Cái gì kia không
[01:23:59] biết báo cáo cái gì có thứ tự mang tiền
[01:24:02] ông tôi không thể dân kế toán không phải
[01:24:04] là thư ký nói tôi ghi chú rất là đủ các
[01:24:06] thử mọi thứ dễ nghe tôi vẫn khẳng định
[01:24:09] là tôi làm việc chuyên nghiệp
[01:24:11] gì hả Tôi có chơi game mà chẳng có rồi
[01:24:15] không Giới thiệu mày ông ấy không phải
[01:24:17] tự biết
[01:24:19] cho con đi nha
[01:24:22] Ừ
[01:24:22] chắc hết rồi
[01:24:25] em nhớ hết rồi đại Khải có ông biết qua
[01:24:28] được một vài cái thôi
[01:24:30] a thào nhớ vẫn còn hồi trước tôi cài Hồi
[01:24:34] trước tôi cả nhiều chẳng qua tôi bị Tôi
[01:24:36] gỡ vợ đi cài lại máy nhiều nên là tôi bị
[01:24:40] mất ấy rồi chứ tôi có nhiều cái hay lắm
[01:24:44] anh đợi mình một tí lại
[01:24:47] Ừ Đúng rồi hình như tôi gỡ đi nhiều nên
[01:24:50] là lại ít cái mà chia sẻ trong bé uống
[01:24:53] hết rồi hôm đấy tôi cài rất nhiều cái mà
[01:24:56] tôi cảm thấy hay ho thôi cái nhưng mà
[01:24:59] Chính vì nó hay ho nhưng mà chỉ dùng 12
[01:25:02] lần nên là tôi mấy kiểu bây giờ tôi còn
[01:25:06] không nhớ là tôi cài lại
[01:25:08] Ừ nếu mà nói chung ở khi nào mà có gì
[01:25:12] tôi sẽ chắc là đăng bài lên như tim công
[01:25:15] ty để cho mấy ông mấy ông xem qua lại
[01:25:19] bài hát em vẫn nhìn vào cái thư mục
[01:25:22] Action sân này của tôi đúng không
[01:25:25] Ừ cái
[01:25:27] Ừ cái này
[01:25:30] Em làm về cái tiện ích tôi lưu lại mà
[01:25:32] Thì có cái tiện ích này Hồi đấy tôi làm
[01:25:35] việc làm với
[01:25:37] cậu em sinh năm 2k hay tôi từng nó giới
[01:25:42] thiệu qua cái đứa em ấy rồi Kiểu quê tôi
[01:25:45] một trong những đứa học trò đầu tiên tôi
[01:25:47] dạy gia sư theo kiểu là vệ gia sư lập
[01:25:50] trình ấy chỉ cần dậy nó một vài buổi bây
[01:25:53] giờ nó thành một thằng đội trưởng ấy thì
[01:25:55] à
[01:25:57] Chúng tôi sẵn đứa em để chuyên gia Swift
[01:26:01] với nó làm cái Tĩnh hàng cho tôi cái
[01:26:02] tiện ích này là kiểu về tổng hợp rất
[01:26:04] nhiều phím tắt bao gồm phím rất tải ảnh
[01:26:06] ở được trên rất nhiều trang hay ạ bấm
[01:26:09] phím tắt này nó sẽ mở cái gì đó lên về
[01:26:12] sau tôi giới thiệu chứ không mấy cái thì
[01:26:14] cũng tương tự để mày ông biết cách làm
[01:26:17] tiện ích cũng như
[01:26:19] cậu có chuyện Nếu Để ý kỹ trên thanh này
[01:26:23] của bộ có rất nhiều cái thực âm nó là ra
[01:26:26] Suite đấy Bấm vào nó sẽ mở được cái gì
[01:26:28] Đợi gì đòi lấy Tôi Sẽ Về do tôi sẽ dạy
[01:26:31] mày ông về mấy cái này à
[01:26:33] à à
[01:26:36] để tham khảo cách chế loa đây tôi thử mở
[01:26:39] ông có cái Zalo của tôi nhé đây tôi vì
[01:26:43] nốt lại tất cả những cái thứ mà tôi
[01:26:47] Ừ tôi sẽ hỏi này tôi hỏi sếp sẽ có những
[01:26:52] cái gì những cái gì tôi đang cầm làm đấy
[01:26:54] đấy mở lên nó sẽ bị trước ít này cái này
[01:26:58] nó có thể tích hợp thêm rất nhiều cái
[01:27:00] kẹp power-up này nó thể tích hợp thêm
[01:27:02] rất nhiều cái tiện ích nữa chắc là mình
[01:27:04] phải mò mò dần em ấy ông mới hiểu
[01:27:09] Ê mấy ông đang cứ hỏi tôi về chia sẻ cấu
[01:27:12] hình máy tính thức A máy tính của tôi
[01:27:14] tôi từng đăng bài Phút về cái máy này
[01:27:17] rồi vợ ạ Tuy trong bố mẹ lúc đầu có phải
[01:27:20] rất chị mày chặn các thứ nhưng mà ra là
[01:27:23] nó không như thế nó đều ấy chưa ạ
[01:27:26] cho
[01:27:27] tôi từ 57 phút rồi lại những 40 phút rồi
[01:27:30] Cái cái bên đấy rồi Nhưng tôi sẽ không
[01:27:32] tăng nữa chứ
[01:27:34] à à
[01:27:39] à à
[01:27:45] mà bạn 2k hay đấy á bạn 2k hay lấy là
[01:27:48] người sống nội tâm đến chắc là tôi không
[01:27:50] thể chia sẻ cho mấy ông cái gì đâu tôi
[01:27:53] chỉ bật mí một tí ở ông đấy cũng từng là
[01:27:55] kiểm duyệt của nó từng từng làm kiểm
[01:27:57] duyệt nhóm thôi
[01:28:00] Ừ Ok chắc à phạm mới thế Hôm nay anh sẽ
[01:28:04] ra mình chưa biết chia sẻ cái gì cả bài
[01:28:06] tập thì tôi cũng sẽ đăng lên và ngắm
[01:28:07] thôi đúng không ạ
[01:28:09] em buổi sau mình sẽ học thời gian switch
[01:28:13] Ừ chắc là từ buổi sau nó sẽ khó và khô
[01:28:16] khan hơn về nhà không chuyên giao diện
[01:28:18] nữa nó sẽ khô khan hơn một tí bắt đầu từ
[01:28:21] buổi sau luôn buổi sau lại là nhảy sang
[01:28:24] lập trình nó không làm về giao diện nữa
[01:28:25] sẽ phải có tí động não nhiều hơn Đây là
[01:28:29] mấy ông cũng chuẩn bị tâm lý rất là vừa
[01:28:31] đúng không ạ Thôi chào các bạn nhé Ừ ok
[01:28:37] ừ ừ
