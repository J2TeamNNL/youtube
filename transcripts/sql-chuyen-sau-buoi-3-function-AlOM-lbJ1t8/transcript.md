# SQL chuyên sâu - Buổi 3 - Function

- Video ID: `AlOM-lbJ1t8`
- URL: https://www.youtube.com/watch?v=AlOM-lbJ1t8
- Published: 2021-10-22
- Duration: 1h 24m 7s (5047s)
- Language: vi
- Subtitle source: auto
- Kind: live

## Transcript

[00:00:13] anh alo chào các bạn
[00:00:21] Hôm nay cuối tuần là không Hôm nay không
[00:00:23] hẳn là cuối tuần nhiều hôm nay mình ngủ
[00:00:26] thỉnh thoảng bọn mình mới bắt đầu Ồ dọn
[00:00:30] dẹp nhà cửa ở
[00:00:42] anh alo các bạn nghe thấy rõ alo alo
[00:00:46] Hôm trước có bạn bảo Mic bé
[00:01:00] có thêm phụ đề tự động á
[00:01:05] Ừ mình mình có mình luôn chỉnh nó phụ đề
[00:01:13] Mình thấy ở đây có vẻ nó không thêm này
[00:01:15] thôi lại
[00:01:18] bình thường mà mình mình có chỉnh cài
[00:01:21] đặt thì con nghỉ à
[00:01:29] à à
[00:01:49] Ừ ok thì bạn đang thể các bạn đang thấy
[00:01:51] màn hình của mình về hôm nay cái thứ
[00:01:54] mình sẽ học thuộc
[00:01:56] như mình đã nói là
[00:02:00] các bạn không hỏi nhiều ở trong
[00:02:03] buổi học word trong toàn kiểm tra rồi
[00:02:05] thành ra là cậu chẳng có câu hỏi gì cả
[00:02:09] cũng như là những đời thường của mình
[00:02:11] chia sẻ nhiều bạn ở đây còn đã học cả
[00:02:13] bên quá lãi phải ra là mình chỉ mình
[00:02:15] không muốn chia sẻ những kiểu hôm nay
[00:02:17] mình chia sẻ xong rồi hôm west lại chia
[00:02:19] sẻ chung
[00:02:23] nhà mình sẽ phải chia ra là hôm nay chia
[00:02:25] sẻ những cái gì đó mà bên web cũng chia
[00:02:29] sẻ hơi khó
[00:02:31] từ
[00:02:34] hôm trước có thể các bạn thấy lúa hôm
[00:02:37] nay nó sẽ dễ hơn rồi đi dễ hơn một tí
[00:02:40] thôi hôm nay mình cũng sẽ không thể dạy
[00:02:43] nó canh dễ quá được Bởi vì thực tế là
[00:02:46] cái này mình đang dậy nó đúng kiểu định
[00:02:49] nghĩa là chuyên sâu thì ra là kiểu chứ
[00:02:51] thực tế thì các bạn học ở chính Trường
[00:02:54] ấy thì người ta ngại dạy cái mức độ khó
[00:02:56] như là nhiều thầy cô không hà nặng thích
[00:02:58] cái này làm nên là không Chuyến sau lắm
[00:03:01] đấy thì
[00:03:03] các thầy cô khác chỉ việc
[00:03:07] dạy các bạn về Kris xong rồi tên của nó
[00:03:11] xong ngồi á xơ Begin em xong trong đấy
[00:03:13] có thể mấy cái câu đơn giản Shake Asus
[00:03:16] đó ngoại Thế cũng là xong được một cái
[00:03:21] bài rồi nhưng mà như thế thì sẽ sẽ làm
[00:03:23] cho sinh viên cảm thấy thắc mắc rất
[00:03:25] nhiều cái cũng những cũng như là không
[00:03:29] hiểu được thực sự là nó gì 2i
[00:03:31] Ừ để mà dậy được hết cái hay của nó thì
[00:03:36] bắt buộc phải dậy cả cái khó đúng ạ Thức
[00:03:37] dậy mày đơn giản không hiểu sẽ lấy
[00:03:40] Insert thì thì các bạn thấy không dùng
[00:03:42] nó không dùng code không dùng phân sinh
[00:03:44] cũng được đầu ngoan
[00:03:47] thì bắt buộc phải dạy những cái nó
[00:03:50] chuyên sâu tí mà càng chuyên sâu luôn
[00:03:52] nha các bạn sẽ càng thấy nó loạn bởi vì
[00:03:55] nó mới bởi vì thực tế Tùy các bạn đang
[00:03:58] bảo kia là học học cái này phải ngay ba
[00:04:00] bốn lần mấy hiểu không ạ thì đúng là như
[00:04:02] thế bởi vì ở trên trường trên trường
[00:04:05] mình dậy mình không phải dậy một một
[00:04:08] buổi xong Được hẳn một cái một cái như
[00:04:11] thế mà hôm trước mình nghe trong vòng
[00:04:13] một tiếng đầy đúng à nhưng bằng 3 buổi
[00:04:16] dậy trên lớp của mình là một buổi dậy
[00:04:18] theo lớp của mình bốn điểm 4 tiếng thực
[00:04:22] hành một tiếng lý thuyết và 3 tiếng mà
[00:04:24] lại mình sẽ cho sinh viên mình thực hành
[00:04:26] từ A đến Z Vì thế nên là các bạn mà lĩnh
[00:04:29] hội kiến thức của ba buổi chỉ ra vòng
[00:04:32] một tiếng ấy hiểu ạ nghĩa là 12 tỷ không
[00:04:34] Đúng không cả bao gồm thực hành trong
[00:04:38] vòng một tiếng nghe online mà các bạn
[00:04:40] mới hiểu được hết thì các bạn chắc là
[00:04:44] giỏi siêu nhân ấy giỏi hơn nhà mình vì
[00:04:46] mình không thể làm được điều đấy
[00:04:50] thế nên là mình thấy một tuần học một
[00:04:52] buổi như thế này rất là ổn mà các bạn
[00:04:55] làm bài tập cũng như là xem đi xem lại
[00:05:00] cho hiểu hoa - - trên lớp của mình nào
[00:05:03] kiểu 3 buổi cái là nó sẽ là kiểu cách
[00:05:06] nhau cứ một ngày học một buổi Thì nghĩa
[00:05:09] là trong vòng kiểu 556 ngày bao nhiêu
[00:05:11] lĩnh hội từ được đấy cũng tương đương
[00:05:13] đúng không ạ
[00:05:16] là không Mình đã dậy gì đâu Mình đang
[00:05:19] chỉ nói qua về cách học của cái này nó
[00:05:24] khó à rất là khó thấy à các bạn kêu chỉ
[00:05:26] cần hiểu cơ bản thôi cũng được hiểu tác
[00:05:28] dụng của nó cũng được Còn nếu mà các bạn
[00:05:31] muốn chuyên sâu Giống như mình nói thì
[00:05:34] các bạn sẽ để phần chính sau phải học
[00:05:37] mấy cái khó khó lắm ạ con nếu mà chuẩn
[00:05:39] đấy thì chắc là mình sẽ phải chia lại
[00:05:43] cái mục lục của cái video là đoạn nào sẽ
[00:05:47] là đoạn Cơ bản nó ngoan bạn ở đoạn khó
[00:05:51] ra đến đoạn khó mình sẽ bảo thôi Nhưng
[00:05:54] mà mình sẽ chia thấy nó có bạn kiểu lúc
[00:05:57] đầy ý giờ sẵn ra Tinh thần này nhảy sang
[00:06:01] đấy một khó ngắm hoa gợi cảm thấy não ra
[00:06:04] thực cá Thế mới gọi là học mà nó ngọn
[00:06:06] học thì nó phải khó
[00:06:07] Đi
[00:06:11] học mà thấy dễ quá cậu
[00:06:13] một cộng một bằng hai thì các bạn chẳng
[00:06:16] cần nhớ mọi chuyện và bài học gì cả à
[00:06:18] giới
[00:06:21] thiệu hôm nay mình sẽ học về Phong Trần
[00:06:24] này xong rồi Ở đây cái link này mình để
[00:06:35] à à
[00:06:38] à à
[00:06:40] à à
[00:06:49] học lại cơ bản lẹ không ạ khi gạch cây
[00:06:53] lại thì chưa chắc nó nó đã cẩn Trì Nên
[00:06:55] là các bạn cứ phải chịu khó học dần dần
[00:06:57] dần thôi
[00:06:57] Ừ
[00:07:02] cái cái thời gian đầu nói chung là đối
[00:07:04] với mình nhé Mình quan điểm là lập trình
[00:07:06] viên mình sẽ có hai cái giai đoạn rất
[00:07:11] khó đó đoạn đầu tiên đó là giai đoạn mới
[00:07:12] học
[00:07:16] Ừ thì có rất nhiều cái ấy trên mạng
[00:07:18] Hương Trà bao nhiêu tài liệu bao nhiêu
[00:07:22] khóa học cơ bản vân vân vân mỗi thầy cô
[00:07:25] dạy một kiểu kiểu cảm thấy an tỷ tỷ thứ
[00:07:28] cần phải học được hiểu là
[00:07:31] các bạn thích heo mạng web thì phải học
[00:07:34] một kiểu theo mạnh ứng dụng và sẽ một
[00:07:37] kia thì mạnh ghê mình hôm kiểu
[00:07:40] Ừ để giai đoạn và khi các bạn có gì thứ
[00:07:43] để mà học có giai đoạn 2 nó không phải
[00:07:44] là khi các bạn học xong hết rồi không
[00:07:47] khi các bạn hiểu thực chất là làm không
[00:07:50] phải tầm hợp tất cả các bạn chỉ cần học
[00:07:53] chuyên các bạn biết được cái thứ mà mình
[00:07:56] mình mình muốn theo rồi các bạn sẽ còn
[00:08:00] chuyên thứ đấy thì đến giai đoạn đấy thì
[00:08:02] lại rất ít tài liệu được các bạn thực sự
[00:08:05] là học bởi vì còn đầy người hiểu mình
[00:08:07] làm rồi nhưng người ta không chia sẻ
[00:08:09] hoặc Thậm chí bạn là một trong những
[00:08:11] người tiên phong đầu tiên làm đấy chẳng
[00:08:13] hạn ví dụ Giả sử Hồi trước mình làm mì
[00:08:15] tôm Facebook đấy rất nhiều cái là ở mình
[00:08:18] mình có thể học được từ người đi trước
[00:08:20] nhưng thực ra có nhiều cái cái nó chả
[00:08:22] chia sẻ đâu cả mình và tự mò tất cả
[00:08:25] những điều đấy mình cảm thấy rất nhiều
[00:08:28] cái kiểu các bạn muốn làm nó phần mềm
[00:08:31] kiểu chưa ai làm đúng không ạ từ kiểu
[00:08:34] thành một doanh nhân một Bill Gates hạn
[00:08:37] kiểu gửi hết thì
[00:08:39] có phải là những người tiên phong đúng
[00:08:42] không làm những người đấy thì đương
[00:08:44] nhiên mình sẽ khó học hỏi từ nhiều người
[00:08:49] Ừ
[00:08:53] tí tí mình sẽ giải thích các bạn các bạn
[00:08:55] sẽ thấy sự khác nhau giữa hai thằng này
[00:08:58] ngang mặt phẳng xin với Oxy Lưu 2 tháng
[00:09:01] ngày Nếu mà đương nhiên là với ngôn ngữ
[00:09:03] lập trình thì cả hai thằng được tính hàm
[00:09:06] thôi hàm hàm xong rồi truyền tham số rồi
[00:09:09] xử lý rất thứ vân vân Nhân và đối với
[00:09:13] FBI là tách làm hai cái một cái là cái
[00:09:17] xử lý không Chuyển là xử lý dữ liệu và
[00:09:20] một cái cái chỉ ra để lấy dùng lấy dữ
[00:09:29] à à
[00:09:30] có
[00:09:33] phải chuyên sâu này sẽ dạy kiến thức nào
[00:09:36] vậy ạ Thực ra thì cho là bạn không biết
[00:09:38] được bạn theo từ buổi đầu không Nhưng mà
[00:09:41] thực ra đây đây đây toàn bộ toàn bộ
[00:09:43] những cái Tab ở trên này sẽ là những bạn
[00:09:47] nhưng sẽ dạy này từ Index viewiew xong
[00:09:51] có viết phương trình trên sân Thì cái
[00:09:54] trang sách như mình đã nói là em mình ít
[00:09:57] áp dụng như là
[00:10:00] mình chưa kinh nghiệm thực tế giờ này
[00:10:01] lắm
[00:10:04] Mình sẽ Chị nói qua các bạn các bạn lý
[00:10:05] thuyết cái này thì các bạn
[00:10:09] các bạn biết thôi mà người biết thôi các
[00:10:11] bạn không biết được về sau sẽ đưa các
[00:10:21] có thể là hai bộ nữa sẽ hết
[00:10:25] đấy là trong trường hợp mà mày ông theo
[00:10:27] được cái bộ chi cơ vừa buổi trưa là khó
[00:10:30] hơn rất nhiều hợp có khó nó khó hơn của
[00:10:33] boot nhưng mà
[00:10:37] sau đó thì mình sẽ cho thử làm cái câu
[00:10:41] hỏi Vẫn đá này nghỉ rồi các bạn trả lời
[00:10:45] mình đang nghĩ mình đang nghĩ đâu nhé là
[00:10:47] hôm đấy sẽ có thể gọi Dung trước thử một
[00:10:48] lần đi
[00:10:53] gọi zoom để mà các bạn à
[00:10:56] thì các bạn qua đấy để mà hiểu trả lời
[00:11:00] thi vấn đáp Đóng mặc ạ
[00:11:03] thì mình sẽ bọc tên Ngẫu nhiên Bạn ở đó
[00:11:06] ngồi hỏi bạn đấy dài câu rồi Bạn ấy thử
[00:11:08] bật mí trả lời cho nó vui đúng không
[00:11:13] Cũng như là kiểu về sau là kiểu thị mình
[00:11:16] như mình định nói thì cuối khóa của wep
[00:11:19] thì sẽ có bảo vệ bảo vệ đồ án cũng sẽ
[00:11:22] nhớ mà online cho cũng qua rồi mà nó bạn
[00:11:24] thì lần này mình cứ thử trước qua dùm
[00:11:29] cái vụ trả lời câu hỏi vẫn đánh mày đi
[00:11:32] khi phát bằng không quan trọng về việc
[00:11:35] bằng cấp ở đây đâu đúng ạ trường Cái này
[00:11:45] anh nói chung ở cái này còn là yếu tố tự
[00:11:47] tin nữa đúng không các bạn tự tin nói
[00:11:49] trước đám đông chịu rất nhiều nhưng quan
[00:11:51] trọng là Toàn người lạ mà mình không yêu
[00:11:55] cầu các bạn phải mở camera thấy K thì ra
[00:11:58] thoải mái mà đúng không ạ Các bạn cứ cứ
[00:12:01] Chỉ việc lên tiếng trả lời
[00:12:04] bởi vì bài toán ở đây là mình muốn rèn
[00:12:06] các bạn về các độ tự tin nữa
[00:12:09] tự tin phát biểu những cái thứ kiến thức
[00:12:14] à
[00:12:18] thực ra thì như mình nói là sẽ có bị bên
[00:12:21] mình đang thử nói chuyện vài bên để mà
[00:12:24] nó có tài trợ gì đó cho sinh viên mình
[00:12:27] đương nhiên là sẽ đổi lại là các bạn sẽ
[00:12:29] phải làm cho bên đấy Chẳng hạn hay gì đó
[00:12:32] đúng à Không thể người ta cho mình thứ
[00:12:34] gì làm miễn phí được cuộc đời sáng ai
[00:12:42] Ừ thế thì đấy nghĩa là họ sẽ tài trợ cho
[00:12:45] các bạn gần như là để mạnh các bạn phải
[00:12:55] em kết bạn kia nói về axwell lồng nó
[00:12:57] ngoan hết Kia lồng bản chất nó chính là
[00:13:01] kiểu dạng như là sapaly đúng không Thì
[00:13:04] thỉnh thoảng mình sẽ dạy một tí Safari ở
[00:13:06] trong những cái bài học này tưởng như tí
[00:13:10] mình sẽ phải tập sẽ có spree nhưng mà để
[00:13:12] phải chuyên sâu hơn giống như là cho rất
[00:13:15] nhiều bạn với nhau thì ở cái đấy liên
[00:13:19] quan hệ khi âm nâng cao hơn quen sâu thì
[00:13:22] cái này thì mình trỗi dậy các bạn tương
[00:13:26] đối thôi chứ mình cũng không không tự
[00:13:28] tin nói chuyện hẳn kéo quý ông nâng cao
[00:13:33] anh nghe hài xóa ở cũng sẽ khó mà khó
[00:13:37] khó mà có hẳn một cái khóa ép ga trên
[00:13:40] nâng cao như thế
[00:13:42] ờ ờ
[00:13:45] sau cái khóa chuyên sau này thì như mình
[00:13:49] từng nói nó sẽ là chắc là mình sẽ gặp
[00:13:53] lại với khóa quét cơ bản tất cả mình sẽ
[00:13:57] dạy 357 khó web cơ bản sẽ không còn lại
[00:14:00] thêm thì với O nữa bởi vì thế này là thế
[00:14:02] này là đủ kiến thức
[00:14:05] thì các bạn tương đối về Apple rồi
[00:14:09] sẽ không Không cần phải biết hên lắm cái
[00:14:11] queo nữa mà các bạn chỉ cần biết áp dụng
[00:14:13] và thực hành làm ra một sản phẩm mà nó
[00:14:15] thôi
[00:14:17] à à
[00:14:22] ô
[00:14:40] bạn với thể sang bên lớp quá phải học
[00:14:41] cũng được
[00:14:45] hình dung được cách áp dụng swar vào làm
[00:14:47] ra một sản phẩm trong nó sẽ như thế nào
[00:14:53] à à từ hôm trước thì thực ra ở có mình
[00:14:57] mình tự nốt lại đấy thôi là
[00:15:01] đó là việc là xinh thoảng Các bạn nhớ
[00:15:05] cốt của mình thỉnh thoảng nó sẽ có vết
[00:15:06] xong rồi Thỉnh thoảng mình phải thêm rốt
[00:15:09] đúng không biết một cái gì đó đây đúng
[00:15:11] không ạ sau đó thỉnh thoảng mình phải có
[00:15:15] group Giả sử mình muốn muốn xóa nó đi để
[00:15:19] mà tạo lại mới đúng không Đúng trước
[00:15:21] mình mới tra được có lệnh rất là hay nó
[00:15:24] class or play này trong một vài trường
[00:15:27] hợp great wall in enter được
[00:15:31] các bạn thử tra nhé or replace Word
[00:15:33] trong đó thì
[00:15:36] ví dụ là View được ạ Mình nhớ vui vì có
[00:15:39] đây nhưng mà nếu là xử hôm trước mình
[00:15:43] học ngu thì nó sẽ không có press Play mà
[00:15:46] nó Chris bowen enter Tức là sao nghĩa là
[00:15:49] sẽ thêm mới hoặc là thay thế cảm thấy
[00:15:52] mình cái đấy rất hay à
[00:15:57] à à
[00:16:06] cách setup 1db đến nào cho bảo mật không
[00:16:11] Cái này mình đã hôm trước à Buổi đầu
[00:16:13] buổi đầu bởi Thứ hai nhớ rồi nhưng còn
[00:16:15] nói qua các bạn về cái vụ
[00:16:21] hát mã hóa các cột cột mật khẩu rồi Cái
[00:16:22] đấy là liên quan đến bảo mật Tuổi đấy
[00:16:24] còn bể thêm bảo mật thêm mình chắc là
[00:16:27] các bạn phải áp dụng vô CPU này xong rồi
[00:16:30] video để mà cho các lập trình viên không
[00:16:32] bị can thiệp một cách trực tiếp vào
[00:16:38] à à
[00:16:39] để
[00:16:43] tối ưu hóa có quay đi cái này nhưng mình
[00:16:45] vừa nói thì nó rất là nó liên quan hệ
[00:16:48] yêu cao chuyên sâu nhằm nâng cao thì
[00:16:51] mình mình cho mình chỉ dạy một cách vừa
[00:16:53] đủ ở trong cái khó ai thôi chứ mình cũng
[00:16:56] không chuyên để nó dậy các bạn với cái
[00:17:08] thế hả bạn kia nói là biết sơ sơ HTML CS
[00:17:10] rồi cho đỡ theo dạy xanh ra Swift học
[00:17:13] thứ ra cũng được các bạn sẽ thỉnh thoảng
[00:17:16] sẽ bỏ lỡ những cái chia sẻ trên diện
[00:17:18] kiến thức khác của mình khi mình dậy Cái
[00:17:32] Ờ
[00:17:36] Ờ nhưng mà vừa rồi nhận nhân tự nhân
[00:17:40] tiện là mình à Mình có nói qua vụ là
[00:17:44] Tuyết và kết lọ enter này đúng nghĩa là
[00:17:50] kiểu thêm hoặc là sửa đúng hoa thì mà
[00:17:52] bản chất là nó không có thêm sửa mà nó
[00:17:54] sẽ là kiểm tra lại ít sĩ để kiểm tra của
[00:17:57] quân 70 sau đó thì mình mới tạo mới nếu
[00:18:00] mà giờ sự nó không còn bạn
[00:18:04] ở đâu trong trường hợp này nó là tồn tại
[00:18:06] thì xóa nó đi này sâu tạo mới đúng không
[00:18:10] ạ nhưng mà ở đây nó bị
[00:18:13] có bạn bình luận ở ngay dưới này
[00:18:16] ở đó là có thể trường hợp xảy ra là khi
[00:18:21] mà khi mà cái rốp cái dốc ở trên này gốc
[00:18:23] ở trên này có vấn đề thì khi mà tạm mời
[00:18:27] đấy lại nó sẽ lỗi kiểu cờ thế thành ra
[00:18:30] cách cách hợp lý hơn đấy
[00:18:33] đó có tạo 1 cái code trống sau đó thì
[00:18:37] mới bắt đầu enter sửa capo trong đấy sẽ
[00:18:38] luôn được
[00:18:41] xe mình nghĩa là cái cách này là 100
[00:18:44] những cái tư duy mình mình đang nói qua
[00:18:45] về cái việc là tư duy khi mà giải quyết
[00:18:49] một bài toán các bạn có thể xử lý bằng
[00:18:51] nhiều cách có thể là kiểu giống như ở
[00:18:54] đây kiểm tra có tồn tại này nếu mà không
[00:18:56] Nếu mà có tồn tại thì xóa nó đi Xong rồi
[00:19:01] tạm mới thì thì có thể nó sẽ lỗi còn ở
[00:19:04] đây kiểm tra tội có nôn tại không tồn
[00:19:08] tại thì nó mới tạo và mình sẽ sửa nó giả
[00:19:09] sử cái đoạn kiểm tra không tồn tại này
[00:19:12] có vấn đề cũng không sao cả
[00:19:14] ở Ninh Bình vẫn sẽ sửa được nó ở ngay
[00:19:17] Mình thấy cái đây nó sẽ hợp lý hơn việc
[00:19:18] là
[00:19:21] kiểm tra tại này
[00:19:24] Vì mình thấy trên cái sách flow này có
[00:19:26] nhiều bạn trả lời rất hay anh Cử mình
[00:19:28] học hỏi cố từ người khác đấy
[00:19:32] là đầy chỗ một chàng trai chàng lập
[00:19:34] trình các bạn học công nghệ thông tin
[00:19:48] cho các bạn học thực sự là mình học
[00:19:49] khi
[00:19:53] mình học các thù với họ chủ yếu toàn là
[00:19:56] không không có trên một cái trang khóa
[00:19:58] học nào cả nên em thực sự các bạn hỏi
[00:20:00] mình khóa nào ổn anh không gặp chắc đi
[00:20:06] Đang ngồi chơi à các bạn hỏi người khác
[00:20:07] thôi
[00:20:12] và Không không bài toán ở đây đó là kiểu
[00:20:16] chuyến Chắc là ổn với mình sẽ ổn với bạn
[00:20:19] mà ngoan các bạn hãy phải tự cảm thấy
[00:20:22] nếu mà nó miễn phí cho trời là miễn phí
[00:20:24] một vài buổi giờ các bạn học thử nó tốt
[00:20:26] Còn không thì đúng kiểu các bạn cũng 50
[00:20:27] 50 đó
[00:20:31] không gì Chắc chắn là các bạn bỏ tiền ra
[00:20:34] các bạn sẽ học ổn cả bởi bởi vì các bạn
[00:20:35] cũng biết đâu có rất nhiều người mất
[00:20:43] bây giờ gần bám được rồi đúng không ạ
[00:20:45] Giờ đang có tên 60 người
[00:20:48] Xin chào sau buổi hôm trước thì lượng
[00:20:50] người bắt đầu giảm hẳn cảm thấy ở ban
[00:21:01] kỹ thuật toán thì các bạn không cần phải
[00:21:03] chuyện nó đã bị khóa EXO đến bây giờ
[00:21:06] mình cũng mình cũng vận dụng thật toàn
[00:21:09] đi lắm mà đi ray và tìm thì cái rất là
[00:21:12] tốt để mà các bạn muốn cậu bởi vì một
[00:21:15] vài công ty Đúng là tuyển
[00:21:17] nhưng mà thực ra là facile à cái đã
[00:21:19] không lên đòi họ gì nhiều và cà phê xơ
[00:21:22] cả xơ cho ta chỉ cần biết toàn bộ cơ bản
[00:21:27] cũng như là có cái gọi là có khó tinh
[00:21:29] thần như thế họ sẽ đánh giá cao về mặt
[00:21:32] tinh thần hơn chứ kinh nghiệm hay Kiến
[00:21:36] thức là mấy cái đấy có thể bổ sung sau
[00:21:41] nhà mình có biết dùng pin đâu mà hướng
[00:21:43] dẫn
[00:21:46] Ok nói chung bây giờ bắt đầu buổi học là
[00:21:47] không ạ Mình sẽ chữa bài Bố hôm trước
[00:21:48] nhé
[00:21:49] Khi
[00:21:54] bữa hôm trước thì thử k là
[00:21:57] Ừ cái câu 3 sao ấy thường ra có nhiều
[00:22:00] bạn Mình thấy bạn gần cuối bạn là nó trả
[00:22:03] lời tương đối ổn rồi nhưng mình không
[00:22:06] chắc là mình không nên chữa hẳn có 3 sao
[00:22:08] này mà mà
[00:22:11] à mà để cho buổi sau với chi cơ mình sẽ
[00:22:13] chữa và các bạn sẽ thấy khi mà dụng chỉ
[00:22:17] cơ vào thì câu 1 sao ạ Nói cho mấy câu
[00:22:22] này và sự ra dễ hơn dễ dễ hơn nhiều
[00:22:23] anh
[00:22:25] à mấy câu này được ra ở mới khấu trước
[00:22:28] thì nó lại có trong buổi ông như trước
[00:22:29] mình chữa rồi nhỉ
[00:22:35] cho mấy con này mình nhớ hôm nào nó hôm
[00:22:38] trước mình là mình đã chữa mấy cái này
[00:22:41] rồi Thế thôi chắc là mình nhảy sang Hàn
[00:22:49] tiên thì cái phong trần đấy
[00:22:57] Nó là loại Bean
[00:23:01] song sinh và một loại là loại à
[00:23:07] thi
[00:23:12] cái cái này hiện đầy đủ Story như này
[00:23:15] phải Win nhé Thì nếu mà dịch nôm na ra
[00:23:18] là sẽ là kiểu nó được dựng sẵn nó có sẵn
[00:23:22] ở trên trong trong cái hệ cơ sở dữ liệu
[00:23:26] này và vào cái này nếu mà dịch thu ra ấy
[00:23:28] thì nó sẽ là người dùng nữa người dùng
[00:23:29] định nghĩa
[00:23:33] store đã được lưu đã được chị đã được
[00:23:36] lưu lại Bởi người dùng định nghĩa ra Tức
[00:23:39] là sao xa sử ở đây các bạn sẽ lại bộ hôm
[00:23:41] trước là sự sẽ xa phóng sinh viên ở hạn
[00:23:42] ông ạ
[00:23:45] ai như mình không trưởng hôm trước mình
[00:23:48] dốt thế thôi rồi xin với một điện
[00:23:51] nó không có bạn nào chẳng hạn nó ngon Kể
[00:23:53] cả không có bạn nào như này thì ra mình
[00:24:05] ừ ừ
[00:24:08] Ừ thì nó sẽ ra là không chẳng hạn đúng
[00:24:12] không Không ngày thức à các bạn học qua
[00:24:13] về cái Hà này các bạn biết rồi nói
[00:24:16] chuyện giờ đến không có bạn nào trả lời
[00:24:19] không ngờ bản chất ở đây nó là cái này
[00:24:21] là belfort này đi em khoai Trần tất cả
[00:24:25] các bạn thấy dùng hàng có sẵn của thằng
[00:24:28] Amway nó có những cái hàm này hoa nó còn
[00:24:31] những cái hạn gì nữa Thế Hệ hàm lấy thời
[00:24:35] gian hiện tại này Xóa hàm săn hàm đến
[00:24:37] gần nó ngon
[00:24:41] thì nó lên billboards còn hôm nay mình
[00:24:43] sẽ học nó sẽ là học là mình sẽ định
[00:24:45] nghĩa làm cái phòng trừ mới thứ là cái
[00:24:48] thứ hai chung là cực lớn nhất nữa hả
[00:24:50] Mình sẽ có luôn điệp khúc và crash
[00:24:51] khoáng chất như thế này
[00:24:54] nhà đầu tiên thì mình cách tạo bảng chưa
[00:24:56] mình sẽ tạo lại các bạn phê bổ sinh viên
[00:24:59] để bạn sẽ hình dung đã
[00:25:03] sửa đây mình sẽ có mã in DAMtv tự động
[00:25:04] toàn không ạ
[00:25:07] xong rồi Anh tên
[00:25:22] Ờ Ờ
[00:25:25] mình sẽ có giới tính là kiểu để kiện ít
[00:25:28] đi và mình sẽ có như mình đã nói mình
[00:25:32] không nên lưu tuổi của người dùng bởi vì
[00:25:35] cái đấy thì tình toàn được và cứ xanh
[00:25:37] Nam thì dùng để thay đổi tuổi không ạ
[00:25:40] Mình sẽ lưu lại là ngày sinh năm sinh
[00:25:42] Rồi ạ Hoàng ngày sinh gì đó đóng ngoặc
[00:25:44] ngày sinh điện sẽ để cậu biết như thế
[00:25:48] này đó là tự nhiên mình sẽ có khóa chính
[00:25:50] cho chúng đầy đủ
[00:25:53] là sự nhà chắc lại ạ
[00:25:57] Ừ Ok bây giờ xử mình sẽ đi sát vào bạn
[00:26:00] sinh viên
[00:26:08] ở đây sẽ là
[00:26:28] không Này 2.000 chỗ ạ Ngày đúng không
[00:26:31] cho sửa mình có hai bạn
[00:26:47] [Vỗ tay]
[00:26:55] thì ở đây các bạn sẽ xảy ra nó sẽ ra
[00:26:58] thông tin tưởng nhớ này viết ra hiển thị
[00:26:59] thông tin như thế này cho người dùng rất
[00:27:02] là khó chịu Tại sao ạ Bởi vì các bạn
[00:27:04] thấy Hiển thị một cái không với người
[00:27:06] dùng bình thường dùng bình thường sẽ
[00:27:08] trải nghiệm một Với 0 điểm gì tiếp theo
[00:27:11] là hiển thị ra kiểu ngày sinh như này
[00:27:14] Thực ra thì người dùng đôi khi không có
[00:27:16] tâm ngày sinh này ra quan tâm đến tuổi
[00:27:18] hoài cùng nó năm sinh của người ta thôi
[00:27:20] Thì bây giờ mình sẽ hiển thị như thế nào
[00:27:23] thì nó sẽ có nhiều cách ở đây mình sẽ
[00:27:24] thử nhé
[00:27:28] đã sửa đây mình sẽ điền lại là sẽ lacta
[00:27:33] này giới tính ngày sinh này Đây đây nó
[00:27:35] sẽ Nham bằng sẽ lexar của mình thôi đúng
[00:27:37] không Nhưng bây giờ mình bắt đầu thay
[00:27:41] thế dần là không sẽ là gì một sẽ là gì
[00:27:42] để ngoan
[00:27:46] thì kiểu như thế là sử ra sự là mình sẽ
[00:27:48] có thể dùng chú
[00:27:51] ý tem ở đây cũng được
[00:27:54] cây quen mình thức thường hay dùng cây
[00:27:56] quen với trong này cây số em nó chuẩn
[00:27:57] hơn
[00:28:00] Tức là sao mà mình kiểm tra nếu mà giới
[00:28:04] tính bằng một này đúng ngoan thì Zen này
[00:28:08] sẽ in là Nam em ạ eo mình sĩ nữ được ạ
[00:28:10] nữ này
[00:28:14] rồi em này đây này chạy thử nè
[00:28:18] đó các bạn sẽ thấy là một cái không nắng
[00:28:21] đội nó thành nam với nữ đồng loạt và nó
[00:28:24] không có tên cụ ở đây mình có thể cho nó
[00:28:26] vào trong về ngót tròn như hai sao mình
[00:28:29] sẽ app is ở đây tên cột lại tên giới
[00:28:38] Ừ nó như thế này thì các bạn sẽ thấy ra
[00:28:41] à ok Cái này nó là bản chất là gì nó nói
[00:28:44] ít theo ngay lúc mà mình in ra vì sẽ in
[00:28:46] từng cái hang này ra một và trong lúc mà
[00:28:49] mình in ra đúng ạ Mình sẽ lấy được cái
[00:28:51] cục thời tình cũ để mà mình
[00:28:55] mình kiểm tra xem nó phù hợp với cái
[00:28:57] điều câu điều kiện của mình không là câu
[00:28:59] tiếp theo đây động hoặc kiểm tra nếu
[00:29:02] dịch tính bằng 1 thì mình sẽ hiển thị
[00:29:06] cho chị nam giới tính là còn ngược lại
[00:29:08] đó mà ngược lại thì mình sẽ dị giới tính
[00:29:13] nữ đúng thì thì đây mình sẽ
[00:29:15] chị thay cái này bằng phẳng chỉnh thì nó
[00:29:18] sẽ như thế nào ạ Mình sẽ viết phóng
[00:29:19] trình này
[00:29:23] mình bản chất là mình đầu tiên mình vẫn
[00:29:25] sẽ phải đặt tên nó phân trần đời đã mình
[00:29:27] sẽ đặt tên Phong Trần là ứng dụng loại Ừ
[00:29:31] nếu mà để tiếng Anh thôi để nặn hết bằng
[00:29:35] tiếng Việt Anh ấy là tên giới tính ạ
[00:29:40] thì để bên cạnh tiếng Việt đi ạ mình để
[00:29:44] thì mày đi họa nếu viết tắt thường là
[00:29:46] viết tắt họ sẽ là như thế này
[00:29:54] Thôi mình cứ để đầy đủ đi cho con đợi
[00:29:56] phải tắt thì cả hai nó sẽ phải truyền
[00:29:59] một cái gì đó vào trong cái này trong
[00:30:01] trường hợp này mình truyền cái giới tính
[00:30:03] và đúng không ạ và giới tính này nó số
[00:30:06] mình sẽ để chuyển giới tính
[00:30:09] giới tính vào à
[00:30:10] Ê
[00:30:12] thằng Phát triển nó sẽ có thêm những
[00:30:15] kiểu quy tắc nó đầu tiên là các bạn có
[00:30:16] thể truyền tham số vào thì phải khai báo
[00:30:19] kiểu như thế này
[00:30:22] tiếp theo là sau đó thì mình sẽ phải trả
[00:30:27] trả về trả về một cái phải luôn khai báo
[00:30:29] sẽ trả lời cái gì thì trả về ở đây chẳng
[00:30:32] phải chữ này mình sẽ Return chả nọ
[00:30:36] Return Duy Tân có chữ f nhá vào chữ s là
[00:30:39] cái thứ mình sẽ về này Peter nó là
[00:30:43] Nevada đúng không ạ Đừng bỏ ra 50 này đó
[00:30:46] sau đó thì các bạn sẽ luôn của anh và em
[00:30:49] cho điệp khúc Như ngay sau đó các bạn sẽ
[00:30:51] copy rồi đoạn này anh
[00:30:54] ở đây mình sẽ ghi kiểu ngày cho gọn dễ
[00:30:59] hình dung mà Wen giới tính bằng một gen
[00:31:02] Return Nam em ạ
[00:31:06] sau đó thì em ở đây này
[00:31:16] xe tải
[00:31:19] Anh vừa chạy thử
[00:31:23] xin lỗi tại bit nhớ ảnh ngựa phía sau
[00:31:32] có cây cây từ những xem lại nhé
[00:31:35] a Nhớ Mỹ Duy Tân ở đây theo chuẩn đi tơ
[00:31:39] nữa đây là như này đi
[00:31:46] khi con luôn giới tính nóng Ôi cái này a
[00:31:49] còng mình chuyển giới tính vào không
[00:31:50] không còn là có luôn nữa
[00:31:54] đó rồi đúng không ạ ạ
[00:31:57] Anh ở trong trường hợp này thì ở trong
[00:32:00] SQL thì nó lại ngược lại mà luôn là tên
[00:32:03] chứa tên dữ liệu trước sau đó thì mới
[00:32:10] luôn có Return là đây nhá mình phải trả
[00:32:12] về một cái gì đó mà đúng không ạ
[00:32:17] case when i kiện ngay đấy
[00:32:19] Ừ thì bây giờ để mà mình gọi được cái
[00:32:22] hàng này Hà Phong trên máy tính ở trong
[00:32:25] này thì mình sẽ chỉ thay thế đoạn này là
[00:32:27] con Trường tên giới tính sau đó chuyên
[00:32:29] cột tới tính vào là xong để mình chẳng
[00:32:30] hợp này
[00:32:34] thì nó sẽ bị lỗi nó sẽ bảo lỗi này là
[00:32:36] cái xong trên này nó không phải là Build
[00:32:39] phong trần các bạn không gọi được dạng
[00:32:42] như kiểu xoăn cao được như thế này à
[00:32:45] Ừ đấy thì các bạn muốn gọi thì có bị
[00:32:46] nghĩa
[00:32:48] you ready for truyền đấy thì các bạn
[00:32:50] phải thêm dbo xong rồi chấm như thế này
[00:32:52] thì hiểu Nó là cái Hà mà các bạn vừa
[00:32:55] khai báo thì cụ giờ đi file khoanh chân
[00:32:58] Họ chạy thử này có thể kết quả nó vẫn sẽ
[00:33:00] như nhau thôi như cách viết như thế này
[00:33:03] nữa là các bạn sẽ tống hết cái xử lý nó
[00:33:05] sẽ làm cải hàm riêng để máy hiển thị con
[00:33:08] còn C của mình thì chị em đã gọi cái Hàn
[00:33:11] đấy là được đâu mà
[00:33:14] tiếp theo cũng tương tự Thế thì các bạn
[00:33:16] sẽ thấy vừa rồi biết qua được cách gọi
[00:33:19] của một cái phong trần nó ngoác đó sẽ dư
[00:33:21] sử dụng pvo cho chấm thôi mà tên của hàm
[00:33:24] sôi cái Hà mày bạn chất nó sẽ truyền vào
[00:33:27] rất nhiều cái thậm chí ở bên Nếu mình
[00:33:29] muốn dậy hồi của các bạn nhất để thì
[00:33:32] mình sẽ classf Asen là ví dụ ra hàm + đi
[00:33:35] Các bạn thấy muốn của cái hàng này rồi
[00:33:37] ra sự ở mình chuyển A vào kiểu y này
[00:33:41] chuyển bê và kiểu này mình sẽ cộng hai
[00:33:43] số với nhau thì mình xin chào để cái
[00:33:46] nóng à Xong rồi á sẵn này cái ghi nè e
[00:33:50] này cho bạn chất là mình sẽ Return à Còn
[00:33:54] a + a + b + thì đây mình muộn mình tạo
[00:33:57] cái hàng này ra và mình muốn gọi thì cái
[00:33:59] Hàn này mình từng tạo vợ
[00:34:00] ơi
[00:34:03] mình tạm dốc ở đây nhá lốp bóng chuyền
[00:34:07] này cộng này à
[00:34:08] chỉ
[00:34:12] có mình tạo lại hàng này nha đó ông ạ
[00:34:14] ở đây mình muốn gọi hàng này chỉ có bạn
[00:34:18] lại thấy là slex Evo chấm + số chuyển
[00:34:21] hai số vào trà sữa các bạn không biết số
[00:34:24] 1 cộng với số 2 + số 3 bao nhiêu ạ Các
[00:34:27] bạn gõ gõ như này sẽ trở về cứ gọi là
[00:34:32] thì các bạn sẽ thấy bài toán ở đây nó sẽ
[00:34:37] là cần nhớ Thứ nhất là tên của hàm mình
[00:34:38] có thể truyền vào hoặc không truyền Tùy
[00:34:40] các bạn Các bạn thích thì trả về hẳn một
[00:34:43] cái gì đó luôn là sự à
[00:34:46] có một cái hàm không cần truyền về tham
[00:34:49] số gì cả đúng không Đây
[00:34:53] hàm trả về số
[00:34:57] 2.000 21 Chọn nó chả còn truyền đi cả và
[00:35:02] nó trả về 20 21 kéo này cũng được
[00:35:05] cũng được đúng à chẳng đi sai được đấy
[00:35:08] đi hàn mày nó sẽ chỉ đơn giản là trả lời
[00:35:12] 2021 nhà ấy một trong những cái giờ đơn
[00:35:15] giản của các phóng sinh đúng không Đó là
[00:35:19] các bạn sẽ thấy là nó có thể truyền tham
[00:35:21] số nào hoa không cần chuyện cũng được
[00:35:25] sau đó nhỉ các bạn sẽ thêm vì trơn thêm
[00:35:28] chữ s nhé nhớ phải thêm chữ s và khai
[00:35:31] báo Kiểu của nó sẽ trả về sau đó thì
[00:35:34] mình sẽ đã bị zener Điệp một mà mình sẽ
[00:35:37] thêm chữ rito mà sự nó sẽ xào với cái gì
[00:35:39] đây là những cái rễ
[00:35:43] bờ tiết heo xanh cái nâng cao Thêm một
[00:35:44] tí
[00:35:50] ờ ờ Giả sử bây giờ đến ngày sinh đều
[00:35:53] ngoan thì các bạn để lấy ngày sinh gì
[00:35:54] đâu nha các bạn sẽ lấy
[00:35:57] lấy ra tuổi không ạ sử Thế các bạn muốn
[00:35:59] in ra tuổi là sử mình muốn có một cái
[00:36:03] hàm Tưởng như hai là ngày sinh này
[00:36:06] đi ô phong trần là
[00:36:08] phong trần là ah
[00:36:11] lấy tuổi em ạ
[00:36:16] đây đó ông ạ em tuổi nghe đi
[00:36:18] Ừ mình tại một cái khoảng trở lại đúng ạ
[00:36:23] Mình sẽ crash on trên này
[00:36:27] mình truyền ngày sinh vào có hoa là kiểu
[00:36:30] bếp mình sẽ Return về
[00:36:34] with ơn về kiểu tin rằng ạ sử các bạn
[00:36:39] muốn giấu chị 5 tuổi nó chuẩn chứ không
[00:36:41] phải phải phải vậy đó ông ạ thì ghi này
[00:36:44] em này mà trận mình sẽ ghi tên rồi còn
[00:36:48] cái gì đó khi ở đây Nếu các bạn muốn anh
[00:36:50] kiểu đơn giản thì mình sẽ lấy là nền năm
[00:36:53] của hiện tại - năm của cái thằng này là
[00:36:55] được đúng không ạ
[00:37:08] và gas bếp ê
[00:37:09] bí
[00:37:12] đỏ này
[00:37:15] nhiêu được nhiều được
[00:37:18] để mình thử thử trước nhé Mà thôi mình
[00:37:21] áp dụng luôn ở trên này được mà
[00:37:32] Đây vẫn chỉ là mấy gái nó vẫn cơ bản
[00:37:34] thôi
[00:37:36] có bạn theo kiểu lại các bạn hoàn toàn
[00:37:38] là truyền mà một thứ gì đó rồi tính toán
[00:37:40] gì đó để nó sẽ để lại kết quả đúng không
[00:37:42] ạ
[00:37:46] Thế còn cái nào có thể phức tạp hơn thì
[00:37:49] cái phong trần này ra một trong những
[00:37:51] cái khó của nói đây mình sẽ cho bạn xem
[00:37:59] 100 những cái khó của nó có thể là nó
[00:38:04] hoàn toàn thể Return Thay bồ toàn hệ
[00:38:06] anh chả phải cảm cái bảng cho các bạn
[00:38:09] đây ra xử ra sự nhé
[00:38:12] là sử là các bạn Nhớ buổi hôm trước mình
[00:38:17] học là mình có biết voz em sinh viên
[00:38:18] ngoan
[00:38:27] Xem sinh viên ngoãn
[00:38:31] sau đó thì các bạn sẽ truyền mã vào kiểu
[00:38:32] in này
[00:38:37] lại xong rồi Beginning and không ạ Rồi
[00:38:40] Starex sao form sinh viên
[00:38:47] Where mã bằng có mã đối ngoại như này
[00:38:49] hôm trước còn tạo này rồi đúng không
[00:38:52] Mình sẽ rốt vào đi nhé
[00:38:54] à à
[00:39:01] à à
[00:39:07] can not you
[00:39:12] It's table và Plus One Thing I
[00:39:13] à à
[00:39:16] anh
[00:39:20] à hình như có phong trên này rồi ạ
[00:39:22] thông báo
[00:39:24] à À hiểu mình tạo phong trên đây rồi
[00:39:28] Không sao đây khi bây giờ mình sẽ đây do
[00:39:30] và đôi khi ở để tránh nhầm mình thường
[00:39:33] hay có viết tắt của cái á cái tắt của
[00:39:36] cái này trước để cho mình nhớ nó là cái
[00:39:39] gì không bị chụp nó không được cái chung
[00:39:41] kể cả tăng Trần và code rồi không được
[00:39:46] có đồng bọn
[00:39:49] mình lần trước mình chạy ở cạnh ngay là
[00:39:52] sự thật và mã bằng một cho bạn đó ngoãn
[00:39:56] chạy như này kia sẽ là mấy ra toàn bộ
[00:39:59] sinh viên toàn bộ sinh viên có mã bằng 1
[00:40:02] đóng ngoặc ra chỉ có một bạn thôi nhớ
[00:40:04] cách này thử không ai áp dụng cách này
[00:40:07] cho bố sẽ đưa cả mà chuẩn là bây giờ cái
[00:40:10] gì mà chả bị dữ liệu gì đó thì mình sẽ
[00:40:19] sẽ clip phương trình là phần sinh này
[00:40:23] xem sinh viên đúng không ạ ở
[00:40:25] đó Sao Bây giờ mình chuyển mã vào như
[00:40:31] thế này get ơn về thuê bộ và cái này cái
[00:40:33] này hồi nãy mình mò mãi mới ra được đó
[00:40:36] là riêng cái trường hợp Twitter mà trả
[00:40:38] về phần của cái bảng như này thì các bạn
[00:40:41] sẽ không được dùng Aspirin và em không
[00:40:42] dùng được
[00:40:45] cái này bắt buộc phải dùng cái mà không
[00:40:47] ghi tên về thay đổi các bạn báo vội dùng
[00:40:51] cái này điều hòa và phải gọi còn cái này
[00:40:53] thì các bạn chỉ có Return thẳng luôn như
[00:40:55] thế này nó Pit ơn selects
[00:41:00] sao form sinh viên đúng không que
[00:41:02] a mã vàng mã
[00:41:04] ở nhà thôi
[00:41:08] em có và bây giờ cách thì gọi đến hàng
[00:41:12] này thì các bạn lại select sao for thằng
[00:41:13] này
[00:41:15] Anh
[00:41:20] chờ
[00:41:24] đợi bình tĩnh snack này thôi thì phải
[00:41:26] có rule name
[00:41:29] sao phom đúng rồi ạ nhưng phải review
[00:41:32] nói vậy ạ
[00:41:33] anh
[00:41:36] không không phải video Nhớ à Đúng rồi
[00:41:42] thì
[00:41:47] các bạn sẽ thấy là riêng riêng cái vụ
[00:41:50] Thay bồ này nó sẽ biến thành như một cái
[00:41:53] bạn mới rồi các bạn nó ngoan nó giống
[00:41:55] Thằng Biêu ý nhưng thằng này nó khác với
[00:41:57] thằng vi của mạch điện và có thể truyền
[00:42:02] tham số còn hàng hàng ngày chị đấy đúng
[00:42:03] rồi nó trở khát Hồng Vi Hổ điểm trong
[00:42:05] trường hợp này nó chuyển đến 5 số thầm
[00:42:08] phòng view thì các bạn nhớ là mình sẽ
[00:42:11] phải vì tham số ngoài giống như kiểu
[00:42:15] mình sẽ là select sao for view là nó
[00:42:18] đúng không mưu sinh viên ạ ạ Mình nhớ
[00:42:20] hồi đấy đây này xong quen mã bằng mã như
[00:42:23] thế này đúng không ngủ đấy mình làm view
[00:42:25] mình sẽ về truyền tham số ở ngoài như
[00:42:27] này con lần này mình chuyển hẳn như thế
[00:42:31] này và nó giống họng view là nơi kiểu nó
[00:42:32] vẫn là bảo mật Đúng không thực sự mới
[00:42:34] dùng sẽ không biết được là cái bảng
[00:42:36] chuẩn của mình nó sẽ
[00:42:40] tên là gì và có những cái cột vì sự mình
[00:42:42] lên mình vì vậy tất cả cột mình chỉ thấy
[00:42:45] một vài câu thôi đúng không ạ
[00:42:50] Tại đây đây đây sẽ là đầy đủ của cây từ
[00:42:53] trả về dữ liệu theo kiểu là các bạn thấy
[00:42:55] vừa rồi mình trả lời cả chữ này chả phải
[00:42:58] có số này trở về cảm cái bà ta sẽ như
[00:43:08] chả về một thấy bổ tự định nghĩa a đây
[00:43:12] thì cái bài toán ở đây đó là sẽ cái câu
[00:43:15] select này nó sẽ khác với code yêu ở
[00:43:17] điểm mà nó sẽ không chạy được Insert
[00:43:18] update Delete
[00:43:22] cái mình mình từ hỏi các bạn và không
[00:43:24] biết các bạn còn nhớ không Cái khái niệm
[00:43:29] DL đó là data free fire
[00:43:33] language gì đó đúng không khi các DL tất
[00:43:35] cả nó sẽ bao gồm press
[00:43:40] enter mà không tạo được bà không không ở
[00:43:45] bảng mà không sửa bạn ạ Không phải mỗi
[00:43:47] bảng đâu nó sẽ ra bao gồm cả tạo là bố
[00:43:48] sẽ điều hay tạo
[00:43:51] tạm phong trần gì rõ Vân Vân Vân Thi
[00:43:55] Thăng thằng quá trình này nó không chạy
[00:43:59] được BL tiếp theo là dml tất cả data
[00:44:01] manipulation
[00:44:05] là chi phối cái cái trên là định nghĩa
[00:44:09] đúng không mà đi
[00:44:18] mày nhiều đại khái Thế các bạn xấu hổ sẽ
[00:44:21] biết mà Thì thì nó là sẽ là những câu
[00:44:24] lệnh Insert update Delete nghĩa là thay
[00:44:27] đổi thay đổi cái dữ liệu
[00:44:30] thì thằng Phát triển nó cũng sẽ không
[00:44:33] chạy được nốt cả cái này nữa không Sao
[00:44:34] anh vẫn đi lấy được Nghĩa Đồng Nghĩa
[00:44:37] được à trong câu phong trần các bạn chỉ
[00:44:40] có khai báo biến và các bạn
[00:44:43] a black trả về một cái gì đó trả về một
[00:44:45] giá trị trả phải biến hay dùng iPad Air
[00:44:48] vẫn thử thứ chứ không tạo ra được một
[00:44:51] cái bảng ở trong nó giống thằng ngu đã
[00:44:54] từng là đồ ngoại thành phố sẽ lưu các
[00:44:56] bạn nhiều âm nó tạm được cả bà mày tạo
[00:45:00] được bạn tạm thời này Đấy Nghĩa thành
[00:45:03] phố C bị u đi Ủa nó làm được hết cả DL
[00:45:07] đó là đêm em còn thăm thằng thằng mai
[00:45:09] này chúng nó sẽ chỉ là được lại bql thôi
[00:45:14] Nó data quay language để ngoan thế ngôn
[00:45:17] ngữ ngôn ngữ truy vấn tất cả nó là mỗi
[00:45:18] cái nó chạy được đĩa xôi lách đường này
[00:45:37] đợi mình đi con chó nó người quá đấy đi
[00:46:13] em Tự nhiên hôm nay không hiểu sao cậu
[00:46:16] Nhà cửa thì phải dọn phòng con chó thì
[00:46:25] ok Nói chung là về phân Trần ghi là đối
[00:46:26] với mình nghĩ nó cũng sẽ không hoàn dài
[00:46:29] lắm nhưng mình nói nó không hẳn khó loa
[00:46:31] Các bạn thấy nó vẫn đơn giản nhưng mà
[00:46:34] nãy giờ thì ra là nó cũng chưa hẳn mức
[00:46:36] độ khó Còn nếu các bạn khó hơn giống như
[00:46:38] mình thấy mình có làm ở đây đó là các
[00:46:40] bạn hoàn toàn bệnh trong anh nhiều bảng
[00:46:43] với nhau để mà ra được hoặc cao thậm chí
[00:46:45] dùng cái phong trần này trong Word cũng
[00:46:46] được
[00:46:50] trang wed được ví dụ là kiểu
[00:46:55] anh ở đây là mình sẽ có hàm
[00:46:57] kiểu như này Điện
[00:47:06] fashion kiệm kiểm tra tuổi I
[00:47:09] ở trên 18 lần ạ
[00:47:12] là sửa ngày để ngoan thì mình cũng sẽ
[00:47:14] truyền và là ngày sinh đi
[00:47:17] đết này chính sẽ Return ở đây là này
[00:47:20] mình ghi tên bit thì trở về đúng hoặc
[00:47:22] sai rồi chẳng hạn đúng không ạ sau đó
[00:47:26] thì ở đây mình sẽ có ai bị ghi này em
[00:47:29] này lần này mình sẽ copy cũng giống cái
[00:47:32] ở trên này đó là mình lấy tuổi nhưng lần
[00:47:35] này mình sẽ So sánh nó với Twitter này
[00:47:38] nhưng lần này mình sẵn sàng nói với 18
[00:47:39] tuổi em ạ
[00:47:42] thì bản chất cái này nó sẽ trả về là nếu
[00:47:45] mà Ngày sinh hợp lệ chị sẽ là sẽ thỏa
[00:47:48] mãn cái 18 tuổi này họ sẽ cậu chạy được
[00:47:55] Khi
[00:47:58] so sánh này Tại sao không được
[00:48:00] không the
[00:48:04] Ừ cái này rồi mày nghỉ Đợi mình tí đâu
[00:48:08] à à
[00:48:13] À mà thôi Mình chưa tròn ấy 18 lớn không
[00:48:19] anh không đúng nhỉ à
[00:48:21] Ừ hình như ở trong này nó không có so
[00:48:24] sánh chợ này Nếu thế thì không sao Mình
[00:48:32] có ai lấy ra tuổi thì 18 cùng so sánh nó
[00:48:35] với không cái đoạn quen cũng được tình
[00:48:37] nhiều cách mà nó ngon
[00:48:40] thì mình tạm bỏ lại đi tạm không cần mày
[00:48:41] nữa
[00:48:43] chắc là nó không cho dù copy ở trong
[00:48:46] file thì mình sẽ cứ lấy tuổi nhưng
[00:48:47] thường nhé
[00:48:51] Tôi chưa lấy tuổi đúng không Mình sẽ
[00:48:55] mình sẽ lại mình lấy tất cả sinh viên đủ
[00:49:01] tuổi hạ sinh viên như này Where
[00:49:04] divio.com trần đấy tuổi này truyền cột
[00:49:07] ngày sinh vào này không còn -18 xong rồi
[00:49:08] nó không ở đây là điều gì đúng không ạ
[00:49:12] chạy này các bạn thấy em nói vẫn sẽ ra
[00:49:15] tuổi đúng không ạ anh
[00:49:18] ở đây ở đây Chắc chắn là những bạn này
[00:49:21] thì nó trên 18 tuổi rồi sợ sự là mình sẽ
[00:49:25] lấy thật sự là lấy 250 ạ
[00:49:29] ở đây không có bạn nào chưa 25 cả đổi 24
[00:49:34] nhãn thì sẽ có 1 rau xanh đấy tuổi vừa
[00:49:36] nãy rõ phản có bạn trên
[00:49:39] ở trên mà ở
[00:49:42] anh em trả lại nhé các bạn hãy trên lại
[00:49:46] 24 tuổi thôi cái kiểu như thế thì các
[00:49:47] bạn sẽ thấy là
[00:49:50] cái đêm u này cái hàm quanh trường này
[00:49:53] có thể dùng được cả trong Word Và thậm
[00:49:56] chí nó có thể cho được Mình soi được hạn
[00:49:58] của bạn thấy bồ khác Nếu như trong
[00:50:02] trường hợp ở đây nhá Mình có thể là sếp
[00:50:05] select như thế này đúng không ạ xong rồi
[00:50:08] voi với 9 lại bạn sinh viên à ạ kiểu như
[00:50:12] ai on cái cục gì đó là sinh viên chấm mã
[00:50:15] bằng để Adidas đi
[00:50:18] Asiad đây là
[00:50:21] Facebook một tí nữa này
[00:50:25] thêm một chấm mã ngay vẫn chạy được
[00:50:29] ở đó bạn sẽ thấy da tăng trưởng bây giờ
[00:50:31] nó sẽ tính bằng một cái bảng và hoàn
[00:50:33] toàn thể do được cả 4 cái bảng khác kiểu
[00:50:34] như này
[00:50:37] và phong trần Thậm chí còn dùng được
[00:50:40] trong cả que vân vân
[00:50:44] mở
[00:50:47] mã khóa trên Apple
[00:50:51] 10 Thực ra là mã hóa các bạn sẽ dùng
[00:50:53] ngôn ngữ lập trình chứ không không lại
[00:50:56] dùng FBI để mà là mã hóa được
[00:51:03] sự tăng trưởng có tham số rồi quay
[00:51:09] Delete qua thăm số
[00:51:15] không ở trong phong thủy mình nhớ nó
[00:51:16] không chạy được câu lệnh Insert Delete
[00:51:19] Thôi để mình thử nhé
[00:51:23] Thử Thử thì biết thôi đó ngon sự mình sẽ
[00:51:25] classf span xin
[00:51:28] xóa sinh viên em ạ
[00:51:34] thì chuyện ở đây là mã này kiểu in này à
[00:51:38] Return về một cái gì đó kiểu đi
[00:51:43] elite four
[00:51:47] sinh viên Where mã bằng mã
[00:51:51] pro select How tall is
[00:51:56] where mã mã kiểu ngay chạy thử nhé ah
[00:51:58] Peter này mình ghi tên hàng thì thấy bồ
[00:52:00] đi khác không
[00:52:04] Mình Return này một đi ra sắt đúng không
[00:52:08] Ở
[00:52:11] đây các bạn sẽ thấy nó lỗi mà nó khai
[00:52:13] báo là không không sử dụng Delete ở
[00:52:15] trong toàn trường được mà cái Insert
[00:52:18] cũng sẽ thế thôi chả Bạn áp dụng ở trong
[00:52:20] nhà máy quét mã QR mình chưa thử nhé
[00:52:23] nhưng mà chuẩn về về lý thuyết mình nhớ
[00:52:25] chắc thì nó là trong quá trình sẽ không
[00:52:29] dùng được dml 2 dl
[00:52:32] a fashion hyperview dùng được nhiều hơn
[00:52:35] Không cái này là tùy tùy công ty các bạn
[00:52:39] thực ra là có nhiều nhiều công ty mình
[00:52:41] từng mình từng tiếp xúc thì người ta lại
[00:52:43] không dùng một tí
[00:52:47] view Để phong trần hypo CPU hay là thích
[00:52:50] cơ mà nó sẽ tập trung làm hết toàn bộ ở
[00:52:53] bên bác em ngôn ngữ lập trình nào xử lý
[00:52:54] nhưng mà
[00:52:57] chị nhiều là những đấy những công ty bé
[00:52:59] và mình thường đặt mình không chưa gặp
[00:53:02] không tin lớn sẽ ăn trộm như em như mình
[00:53:04] đã nói được ra cái này liên quan vấn đề
[00:53:06] về bảo mật nữa Thực sự không phải ai
[00:53:08] cũng được phép chọc thẳng vào DB để nó
[00:53:10] xem toàn bộ trong bảng để có những cái
[00:53:13] gì kể cả cho dù cột nó được mã hóa nữa
[00:53:15] Nhưng có rất nhiều cột nó vẫn kiểu nghị
[00:53:18] cả mấy kiểu dạng như này đưa các bạn sẽ
[00:53:20] xa foam bảo khách hàng không ạ sau đó
[00:53:22] thì các bạn thấy đấy à khách hàng này
[00:53:24] thanh toán rất nhiều hóa đơn rồi xong
[00:53:26] rồi Các bạn thấy được email nữa là số
[00:53:28] điện thoại người ra các bạn lưu lại toàn
[00:53:30] bộ những thông tin khách hàng Vì sao đói
[00:53:32] Vì sao các bạn nghỉ việc các bạn có thể
[00:53:34] dùng thông tin khách hàng đấy để các bạn
[00:53:37] span telesale quảng cáo gì gì đó thì lôi
[00:53:38] kéo khách hàng đối với công ty mới của
[00:53:41] bạn sẽ hạ toàn bộ những thông tin về số
[00:53:44] điện thoại hay là email địa chỉ vẫn cả
[00:53:47] tên của khách hàng nếu như không có thể
[00:53:49] lưu kẹt ở trên đấy được nhưng mà những
[00:53:51] cái thông tin đấy hoàn toàn nó không mã
[00:53:54] hóa chẳng ai mã hóa và mã hóa ấy chẳng
[00:53:57] giải quyết vấn đề gì ạ thì nên là
[00:53:59] ở những cái đấy chỉ đơn giản là không
[00:54:01] nên cho lập trình viên trực tiếp biết
[00:54:04] được điều đấy thôi đúng không thì các
[00:54:07] bạn sẽ phải làm việc qua view để mở hoặc
[00:54:10] là Oppo để mà thao tác với cái bạn đấy
[00:54:12] chứ không được phép chọc thẳng và xếp
[00:54:22] Ừ đúng rồi hệ quản trị cơ sở dữ liệu
[00:54:24] khác nhau để có thể nó sẽ khác nhau rồi
[00:54:26] cái phương trình này nhưng mà thấy thì
[00:54:29] nó không đúng nó không đúng về cái ý
[00:54:31] nghĩa của nó nữa vì nếu thế thì nó không
[00:54:33] khác gì vô Siri là ngọn thế này mình mới
[00:54:37] dậy Cái bạn ấy là mình có thể dạy các
[00:54:39] bạn hoàn toàn theo máy của em những thứ
[00:54:42] em mai que là không đúng lắm về KS về
[00:54:45] chuẩn seoweb và thằng mai có số pasquale
[00:54:47] mới ra chuẩn nhất thế Mình mới dậy các
[00:54:50] bạn ở trên Microsoft Word nhưng mà về
[00:54:52] sau thì nếu mà sang bên web thì mình lại
[00:54:54] phải dậy lại các bạn gửi mai qua em
[00:54:55] nhưng mà
[00:54:59] ở đó nó thay đổi tí thôi nhưng mà đương
[00:55:01] nhiên là em quay chuẩn nhất thì phù hợp
[00:55:04] và dạy ở trên cái nền tảng máy Microsoft
[00:55:09] à à
[00:55:15] từ hôm nay mình mới đổi cái logo này
[00:55:19] sang thai logo như thế này Đấy mình mới
[00:55:20] xem lại các video của mình hội trước
[00:55:23] mình đừng quay ấy thì mình hồi trước
[00:55:25] mình dùng logo này nhưng mà gần đây là
[00:55:28] mình mới cài lại máy nó bị xóa mất
[00:55:30] Hôm nay chắc các bạn tình ý các bạn nhìn
[00:55:34] thấy cái logo tim ở đây không ạ
[00:55:38] cái logo này thì đã có bạn Chính thức ra
[00:55:39] chính bạn trong nhóm mình từng chia sẻ
[00:55:43] cái ảnh logo đấy Đấy mình mới tải về cơ
[00:55:45] mà cái ảnh đấy
[00:55:47] À thế à Các bạn của với ảnh như thế này
[00:55:49] đúng không ạ sau đó thì các bạn dùng cài
[00:55:51] thêm một cái ra Classic
[00:55:54] Classic Shell
[00:55:57] Ừ cái này trên win mới có thôi các bạn
[00:55:59] cài thêm cái này cho các bạn chọn vào
[00:56:02] các bạn nhớ chọn cái này
[00:56:04] em
[00:56:07] chọn cái custome ở chọn là cái ảnh như
[00:56:09] các bạn nên nhớ nhé cài cái này nó sẽ
[00:56:11] mặc định là đổi các bạn về cái định dạng
[00:56:14] kiểu dạng là classic mà tức là đơn giản
[00:56:17] mà tất cả cái cái start menu menu này
[00:56:19] của các bạn nó sẽ thay đổi như các bạn
[00:56:22] muốn taman menu các bạn vẫn giữ nguyên
[00:56:25] đấy thì các bạn sẽ phải ở bên bên cái
[00:56:27] basic này các bạn đổi hết toàn bộ những
[00:56:30] cái lép Rick mấy cái đây này
[00:56:34] Đấy thành nhà Windows chapman menu chứ
[00:56:36] không phải đổi hình classic menu
[00:56:39] stallman u không đổi hết
[00:56:42] Ừ đúng rồi bà đôi khi nó sẽ thay luôn cả
[00:56:44] trong này mình thấy khó chịu này chắc
[00:56:51] Ừ cái thử ta cái này xong nó có cái ức
[00:56:54] chế riêng sẽ tự nhiên đổi của mình nhiều
[00:57:02] Ừ Nó kiểu nó nghĩa là sẽ tốt Nhưng thì
[00:57:04] ra là mình không cần những cái điều đấy
[00:57:06] thì mình chỉ cần đội mỗi ngày men cái
[00:57:09] biểu tượng đây thôi mà
[00:57:12] đi xe Suka đủ kiến thức của hôm nay ở
[00:57:13] các bạn thấy kiến thức hôm nay nó rất
[00:57:16] ngắn nó ngoác và cũng cơ bản không khó
[00:57:18] lắm hôm trước mình có nói mà có khó lắm
[00:57:21] đâu nhưng các bạn cũng sẽ phải đọc qua
[00:57:24] cái ở dưới này nhá tổng hợp sự khác biệt
[00:57:26] giữa
[00:57:28] đấy Mình có nói đúng không cục sữa đi
[00:57:31] phương trình với
[00:57:35] sau rồi bu để các bạn hiểu về sau hỏi
[00:57:45] à à
[00:57:46] em
[00:57:49] sợ bài tập bài tập mua mạnh không thể
[00:57:52] dài được đâu quá đúng ai
[00:58:04] không Mình có biết bị thon đâu thì thon
[00:58:07] là ngôn ngữ của người yêu cũ mình sẽ
[00:58:14] bây giờ thừa vẫn còn thời gian chắc là
[00:58:16] mình sẽ tranh thủ ngồi chia sẻ vừa nãy
[00:58:18] mình có tổng hợp lại các video có thể
[00:58:21] chia sẻ các bạn thôi Ngồi xem tạm video
[00:58:24] thì hết rồi nhé tạm cái ghế
[00:58:26] Ừ em cứ nghe người cũ Tôi mỉm cười nữa
[00:58:30] nhé Quên nó đi khỏi nó quá khứ đi
[00:58:33] ra tôi không coi nó quá khứ không quên
[00:58:35] nói đi ừ
[00:58:38] tôi có những cái cái này hay cực
[00:58:41] không mình không thấy con nhỏ đó mình có
[00:58:44] biết gửi cái đấy đâu mình không nắm rõ
[00:58:45] lý thuyết thì dạy những cái khó như hết
[00:58:53] anh kể cái này hay cực Cái này là có gì
[00:59:02] mấy ông Nếu đôi khi ông chẳng hiểu sao
[00:59:05] thích chạy mấy cái kiểu dạng mà cuộc thi
[00:59:08] kiểu dáng mà bài đăng nào nhiều luật
[00:59:10] chia sẻ nhiều lời thích hơn thì sẽ được
[00:59:12] điểm cao hơn Ngón Vân Vân để tạo hiệu
[00:59:15] ứng hết cùng mấy ông không lại thấy mấy
[00:59:18] thằng khác nó ngồi spa chia sẻ các thứ
[00:59:21] nên này nhìn cái rõ ràng có một ông chưa
[00:59:25] dài Do sản thế lại phải phải hỏi tu nào
[00:59:28] để mà ngồi lọc có những cái điều đấy thì
[00:59:31] tôi làm cái tool kiểu ngay
[00:59:34] đây tôi đang hướng dẫn tải về thôi bỏ
[00:59:40] ở Đài nó xảy ra được cái trang web về
[00:59:46] Hồi này vẫn còn giao diện rất là xấu
[00:59:48] nhưng mà tôi vẫn ngon thế được không ạ
[00:59:52] nhập ID họ mấy cái bài đăng này lại ID
[00:59:56] Mày đang dẫn 2 căn 5 chia sẻ cho ngoan
[01:00:01] suốt cả bài nữa bài này lên đến 400 rồi
[01:00:03] chia sẻ kiểu kiểu như thế sự xem Thực sự
[01:00:06] nó được bao nhiêu giờ sẻ nhé á
[01:00:12] bài này có đúng có 370 74 là chia sẻ
[01:00:17] Ê máy bài bài lên mỗi 500 này cái kiểu
[01:00:20] gì thế thế Hồi này mình là do diện vẫn
[01:00:22] còn xấu thời tiếp theo là cái giao diện
[01:00:23] cho mẹ ngon lành hơn không phải đánh đi
[01:00:29] à à
[01:00:30] à à
[01:00:35] anh lại kể cái này thì nó nó là còn Lộc
[01:00:36] cả bình luận chung mà lập chia sẻ chung
[01:00:38] là lọc được Thích Vân Vân rất nhiều cái
[01:00:48] ạ Bây giờ Bây giờ thực ra vẫn còn dùng
[01:00:51] được nếu mà ông ấy ngậm Lấy cho tao quen
[01:00:53] thứ hai tay thì ra Facebook nó thay đổi
[01:00:56] cách để lấy mình cái này rồi
[01:01:00] phải phải sửa lại cái api một tí
[01:01:03] Anh Lộc lọc nick dòng nick ảo này đúng
[01:01:07] các bạn để ý kĩ nhé Mình có thêm một vài
[01:01:09] cái giống như cặp
[01:01:12] lập nick rồng nách nạm đây không ảnh đại
[01:01:15] diện này nét không còn tồn tại đây
[01:01:20] xe tải lọc nick ảo theo bài 5 nghĩa lượt
[01:01:22] vượt tương tác của bé đang nó thấp vậy
[01:01:25] lọc chưa phải là thành viên nhóm là sự
[01:01:27] theo kiểu muốn kiểu dạng lại chị thành
[01:01:30] viên nhóm này vừa tính không ạ ấy còn
[01:01:33] tất cả những cái kiểu như thế này
[01:01:36] phim Hai Số Phận lọc
[01:01:38] Ừ cái này hồi này là cốt mình có còn
[01:01:42] trong đều lắm Khổ đấy mình mới mấy cái
[01:01:45] cẩu vừa tự học vừa ngồi làm thực ra là
[01:01:48] vẫn còn điều trị mức tương đối này thôi
[01:01:51] như thế này thử gặp mình tự hào hoa đấy
[01:01:54] mình tự hào có rỡ và cái này không thể
[01:01:57] đến lên hạng 7 phút như này được code
[01:02:12] cô bạn kia đã nói việc là có nên dùng
[01:02:15] tăng trưởng để mà kiểu hiển thị ra số
[01:02:18] giống kiểu mãi là ngon cẩu Ví dụ ở bệnh
[01:02:23] bách khoa B k0001 đúng gọi thì cái đấy
[01:02:25] và mình nên dùng ngôn ngữ lập trình làm
[01:02:28] hơn là dùng word để làm cái vụ đấy à
[01:02:30] à à
[01:02:33] ở đây hôm trước là tôi có chia sẻ cho
[01:02:36] nhóm Hà bên khóa
[01:02:41] à hóa học ở web là Tải ảnh rồi còn bây
[01:02:48] con gà nó tương đương cốt của nó chẳng
[01:02:52] thay đổi thì mấy rồi
[01:02:55] Thật sự đây tôi lấy cái ID của về
[01:03:02] khi xảy ra một cái ID epad đây đúng
[01:03:06] không xong rồi lại giao diện trông rất
[01:03:09] là xấu nhưng mà miễn là cô chạy được là
[01:03:12] được không ạ
[01:03:24] à à
[01:03:27] cha mẹ có những cái video rất thú vị mà
[01:03:32] em để cái cốt để mà Tải toàn bộ video từ
[01:03:35] từ 1 pass hoặc là thậm chí ép một trang
[01:03:38] cá nhân về nhóm thì hồi đấy là tôi chưa
[01:03:43] à à
[01:03:46] khi sex
[01:03:48] anh có thể sắp xếp lại những buổi dậy
[01:03:52] vườn kiến thức môn nào ra muốn đó Ừ ra
[01:03:56] là mua nào của mình cũng để để Đều ghi
[01:03:59] rõ ở trên cái tiêu đề các bạn hãy xem
[01:04:00] theo TD thôi
[01:04:03] và mình có ghi rõ buổi mấy buổi mấy rồi
[01:04:07] à à
[01:04:09] à Tôi đang hướng dẫn mấy ông hỏi làm hư
[01:04:12] mà ông đâu mà tôi đang dẫn mày ông ạ Để
[01:04:15] để làm mấy cái ra không thì khó cả cốt
[01:04:17] tất cả mấy cái này gần đưa nó chưa để
[01:04:18] mua cho lòng Cốt
[01:04:21] cho ví dụ điển hình ở đây là cái này Tại
[01:04:24] hôm trước nói rồi đấy đang ra sự Cái này
[01:04:27] sáng Chúng tôi có một cái file với đấy
[01:04:29] tự nhiên có một anh ở trong nhóm này là
[01:04:32] chia sẻ một cái file tex có tận
[01:04:35] 65.000 dòng
[01:04:38] Khi dòng lạnh mỗi rằng là một linh ảnh
[01:04:41] lấy từ bên thăm bồ rồi cả anh ấy ngồi Do
[01:04:45] anh ngồi cào hết toàn bộ ảnh ở trên mê
[01:04:48] cái mấy cái pass mấy người thích về đó
[01:04:50] lên được 65.000 cái đường lên ngay sau
[01:04:52] đó thì hồi đấy à tôi bảo tôi là ăn
[01:04:54] minjiang gái
[01:04:59] nhập trang ám ảnh gái xinh đấy thì thì
[01:05:02] tôi muốn tải hết là đống ảnh để về tôi
[01:05:05] lọc thì tôi tự nhiên tôi phải cốt cái
[01:05:08] đoạn này mà kiểu đọc được cái file
[01:05:10] 65.000 kia rồi tự động tải về chứ không
[01:05:13] phải là kiểu tôi ngồi tại thủ công về
[01:05:15] copy pate thủ công từng cái lính ảnh
[01:05:18] không kho tôi không nộp thuế tự nhiên là
[01:05:21] thằng IDM nó có hỗ trợ vụ đầy đấy in em
[01:05:24] em có hỗ trợ vụ inbox được file vào
[01:05:27] nhưng mà thằng in animal nó Nó kiểu nó
[01:05:30] hỗ trợ mức tương đối thôi lần đấy lần
[01:05:33] đấy filepost vào nó cũng chết luôn cởi
[01:05:49] a key Word để làm được cái tu nè
[01:05:51] Ừ chắc chẳng cần key word gửi mấy ông
[01:05:53] lên xem cố của tôi tôi xong rồi mày ông
[01:05:56] cha được đúng cái Hà mà tôi dùng nó nó
[01:06:08] Em hãy tôi có file file này 65.000 dòng
[01:06:20] à à
[01:06:22] à à
[01:06:28] ở đó sẽ nó sẽ tự động
[01:06:30] thì nó sẽ tự động tải liên tục liên tục
[01:06:32] về
[01:06:35] Ừ cái này nó Tôi đang dùng ngôn ngữ p
[01:06:36] thì các bạn dùng ngôn ngữ lập trình nào
[01:06:40] được không khác gì nhau cả
[01:06:42] em vừa rồi ở về qua mấy cái tool kiểu
[01:06:45] thứ ra còn thêm một vài cái tool rất là
[01:06:48] hai nữa hưởng như là còn nhiều bạn sẽ
[01:06:50] cần phải vụ
[01:06:57] à à
[01:06:59] ê ê
[01:07:06] cách
[01:07:10] lấy ID từ ở một trang nào đó bất kỳ em ạ
[01:07:14] là sự bấm vào đây để lấy được ID học
[01:07:19] Anh bảo trong nhóm đấy thức anh đi nhóm
[01:07:21] này vào trang cá nhân lấy được ID cá
[01:07:23] nhân này
[01:07:26] anh hoặc là vào pack thì lấy được ID của
[01:07:28] page chọn hoặc cái đi bài đăng cái gì đó
[01:07:31] quê tôi làm cái này bởi vì thứ ba này nó
[01:07:33] các bạn 15 tung lên Facebook này các bạn
[01:07:34] phải biết ID
[01:07:38] Ừ đi mà lấy thông tin từ cái đi đấy
[01:07:43] Vì sao
[01:07:45] anh không gọi hỏi bạn gái tôi người Nhật
[01:07:46] nữa
[01:07:53] ở thời tiếp theo nữa là hôm trước có bạn
[01:07:56] hỏi là làm tiện ích thì làm bằng ngôn
[01:08:01] ngữ gì thì tiện ích Tôi đang làm sẽ là
[01:08:05] làm bằng da Switch thứ mà các bạn có thể
[01:08:07] sẽ được học trong cái khóa học web của
[01:08:11] bạn ấy sẽ làm bằng đá Speed sau đó Chỉnh
[01:08:14] ở cam Hiệp và cái HTML để làm đã được
[01:08:15] cái chậu như này
[01:08:22] Hôm
[01:08:29] em lại nói chung là có một cái tiện ích
[01:08:31] nhóm lợi ích này là Hồi đấy tôi chặn
[01:08:33] quảng cáo này chặn mấy cái nút các tiểu
[01:08:36] tử này đó
[01:08:41] ạ sau đó thì tôi mà lại sang thôi
[01:08:44] a complete Suite làm từ đấy chuyển bắt
[01:08:48] Ê
[01:08:51] bà hồi đấy là tôi làm ở bờ rìa tôi thử
[01:08:52] nhiều quá nhưng ơi thằng Facebook ghét
[01:08:55] tôi nó còn không hiển thị quảng cáo trên
[01:08:58] trên trang của tôi nữa nên tôi phải làm
[01:09:00] thay thế toàn bộ váy đăng hình quảng cáo
[01:09:04] em chọn đến để mua Thôi anh sẽ hiển thị
[01:09:06] ra tôi còn bấm được biết phải cảnh nhé
[01:09:09] Mấy ông thấy tôi cậu thay thế luôn cả
[01:09:12] bài đăng bài bằng ảnh gái xinh lại
[01:09:14] thường về như thế
[01:09:22] ở nhà đưa nhân tiện ích ngày của tôi
[01:09:24] không dùng đỡ của việc tháng Facebook
[01:09:27] lại thay đổi cơ chế rồi Cái này nhược
[01:09:30] điểm khi các bạn theo thằng thứ ba như
[01:09:33] thế là nó thay đổi cái gì mình lại phải
[01:09:36] chạy theo rất là mệt
[01:09:40] Ừ cái này còn version version 3 nữa Đó
[01:09:42] là theo kiểu như này cô đấy tôi chặn
[01:09:43] được cả
[01:09:46] bình luận chứa tử khóa hoặc cả bài văn
[01:09:49] chứa từ khóa nữa Rất là hay có rất nhiều
[01:09:52] bạn cần lấy ví dụ điện hệ nhà tội ghét
[01:09:54] một cái bình luận Họ ghét cái bài đăng
[01:09:56] nào nhắc đến thất thất tình chia tay này
[01:09:59] chính trị Vân Vân Vân này còn sự nhập và
[01:10:02] thôi chẳng hạn Hồi đấy mình nhập giờ sự
[01:10:04] chữa rồi chẳng hạn nó sẽ thấy ông nào
[01:10:22] Ê mày có video này thì thỉnh thoảng mình
[01:10:26] mới đang hơi mình đang đôi khi từ
[01:10:27] bộ phim
[01:10:30] cho mình đăng có thể ở trên kênh của
[01:10:33] mình hoặc mình banh ở trong nhóm như tên
[01:10:38] à à
[01:10:41] có 2 Giả sử có một bài đăng mà không bị
[01:10:43] ẩn nha nha Bình luận cũng có thể bị ẩn
[01:10:50] em gà hồi đấy mình chưa làm được ẩn ẩn
[01:10:55] bình luận bằng ẩn Xóa nút cái ảnh nó đi
[01:10:58] Dù sao mình cũng sẽ nghiên cứu làm mấy
[01:11:01] cái vụ đấy giọng nói chung à cái mục
[01:11:03] tiêu của tiện ích bẫy của mình nó là
[01:11:05] thưởng ẩn đi tất cả những thứ mình cảm
[01:11:07] thấy khó chịu phiền phức Ở trên mạng xã
[01:11:10] hội từ bình luận mà từ 75 này sẽ ẩn hết
[01:11:11] đi
[01:11:14] Nam nào giống như mình mình còn khó chịu
[01:11:16] ở những cái bài mà họ chia sẻ cho bạn
[01:11:18] hết
[01:11:27] khi mình đã ví dụ thế thôi không phải
[01:11:29] các bạn làm thế sẽ phải làm về gái đâu
[01:11:32] mà cái này chị em nói là cách để các bạn
[01:11:35] có động lực làm cái gì đó thôi mình có
[01:11:37] động lực kéo thích ngắm gái thích chia
[01:11:39] sẻ cái đấy cho người khác thì mình sẽ áp
[01:11:47] ở đây phó những cái mà trải qua đường
[01:11:50] gái mấy ông nhé Ví dụ ở đây Tôi có một
[01:11:53] loạt ạ một loạt các đường link này cơ
[01:11:55] thể từng link này biến hình ID Facebook
[01:11:57] cũng được
[01:12:05] Ừ hai cái này là
[01:12:09] toàn bộ điều dùng tool hết đấy dùng tool
[01:12:10] để mà lọc Mà này
[01:12:11] Ừ
[01:12:14] để xem nữa
[01:12:15] anh
[01:12:17] như kiểu như này
[01:12:21] ở đây tôi sẽ lấy hết toàn bộ bình luận
[01:12:23] từ cái bài đăng này lấy được email
[01:12:27] số của tất cả các bạn các bạn đấy chồng
[01:12:35] à à
[01:12:52] à à
[01:13:03] cô này mày Ông vừa thấy không nghĩa tôi
[01:13:06] sẽ lấy tất cả bình luận có chứa Email
[01:13:12] nhé Không phải lấy được email từ từ cậu
[01:13:15] Cái này em các bạn sẽ biết về khái niệm
[01:13:17] về núi Jack về sau mình sẽ dạy các bạn
[01:13:19] với khách sẽ lọc hết toàn bộ thông tin
[01:13:22] để lấy những cái thứ mình muốn trong một
[01:13:24] cái cậu một cái văn bản nữa là dài
[01:13:28] A77 có lập trình Lập trình là nó làm hết
[01:13:30] cho các bạn tự động từ a đến z tất cả
[01:13:38] Ồ không Tôi có nói ngày mai xóa đâu Tôi
[01:13:40] bảo là khi nào tôi ngủ dậy tôi sẽ xóa
[01:13:41] thôi nhưng nhiều lúc rồi tôi ngủ dậy
[01:13:43] được lên thật
[01:13:54] Ê nhớ à
[01:13:57] Cho con thêm cái cuối này quấy được sẽ
[01:13:59] rất phức tạp nha Tôi không biết là có em
[01:14:03] mấy ông chưa Cái này Hồi đấy tôi làm cái
[01:14:16] 30 cách là để mà lọc cũng cả thay thế
[01:14:22] thông tin thể lọc thay thế dữ liệu đ
[01:14:22] ờ ờ
[01:14:27] cái cái cái cái song với mày hồi để làm
[01:14:30] đấy nó là để mang mang thiên hướng là
[01:14:34] kiểu chia sẻ chia sẻ quyền xem trang cá
[01:14:38] nhân người khác do sự là như là ông
[01:14:41] đã có trường hợp như này đi là sửa Ông
[01:14:44] chia tay với người yêu rồi em ạ
[01:14:47] Bây giờ ông muốn vào để xem lại nick bạn
[01:14:50] đấy nhưng mà bị ông chia tay ông chặn
[01:14:53] rồi Hoặc cáo ủy các bạn rồi mà bạn kia à
[01:14:54] Không đăng chế độ công khai không không
[01:14:57] xem được không tin vào đấy thì ông muốn
[01:15:01] là ông muốn xem xem bạn bài đăng của bạn
[01:15:03] kia với tư cách bạn bè thôi chẳnghạn
[01:15:04] cũng được đúng không ạ
[01:15:09] À thì ra thằng bạn thân của ông lại lại
[01:15:13] xem được thông tin của người yêu cũ của
[01:15:15] ông để hạn nó bị hai đứa kết bạn với
[01:15:16] nhau đã lại thế
[01:15:19] thì nghĩa là thằng bạn thân của ông có
[01:15:21] thể đưa nick của nó cho ông để ông đăng
[01:15:23] nhập vào ứng xem đúng không như thế thì
[01:15:27] lại nhạy cảm quá nó ông vào không thể
[01:15:28] làm được rất nhiều cái chứ không phải
[01:15:32] mỗi không phải mỗi cậu hả chị xem thế
[01:15:34] kia thôi thì sẽ nên là tôi Hồi đấy tôi
[01:15:37] là mở trang web này thiệu cậu đặt Ông
[01:15:40] muốn thể chia sẻ góc nhìn của mình cho
[01:15:42] người khác dùng cái video review mình
[01:15:45] từng học kỳ I
[01:15:46] Anh không phải người ta không công khai
[01:15:49] vẫn xem được mà đang nói là cái thằng
[01:15:51] thứ ba ấy nó xem được bài làm gì Thì ông
[01:15:54] có thể chia sẻ cái quyền ông đang xem
[01:15:57] đấy cho thằng khác được đấy nó trường
[01:15:59] hợp đấy chứ không phải là thằng kia đăng
[01:16:01] bài chế độ mình tôi mà cái trang web này
[01:16:03] vẫn xem được đó nhé Không phải như thế
[01:16:06] đâu nhé Mà cái việc là ông xem được cái
[01:16:10] gì đó ngọn ông nhờ ông nhớ bài video Mẹ
[01:16:12] Thứ tôi dậy rồi đúng không chia sẻ góc
[01:16:15] nhìn của mình một phần góc nhìn của mình
[01:16:16] cho người khác được mà toàn bộ góc nhìn
[01:16:19] mình cho khác cũng được đấy nhưng mà
[01:16:20] không chưa sang tài khoản của ông cho
[01:16:23] người ta đúng ạ Mẹ người ta không để
[01:16:24] đăng nhập vào tài khoản không người ta
[01:16:26] sẽ bấm vào đường link đấy mà xem được nó
[01:16:29] sẽ lại khá em như thế này
[01:16:31] Em ở chỗ nào đương nhiên là ông phải
[01:16:32] đăng nhập nick Facebook của ông vào đây
[01:16:34] rồi để mà tôi lấy cho tao kem của ông
[01:16:36] Thực ra là nghe thế nó hơi nguy hiểm thì
[01:16:40] cho nó sẽ ra tôi chẳng chẳng lưu lại à
[01:16:42] chúng chẳng để làm gì mấy cái các bạn
[01:16:49] xe tải về xem thử lên nhà Đấy Tôi vừa
[01:16:51] tới chọn một vài bạn đúng không ạ một
[01:16:54] vài bạn ở trong danh sách bạn bè tôi rồi
[01:16:56] Bây giờ tôi chỉ việc bấm vào xem bất kỳ
[01:16:58] bạn ở đấy thì sẽ ra toàn bộ thông tin
[01:17:00] như này cái này sẽ rất là phù hợp với
[01:17:03] việc ở muốn làm sticker hai ông kiểu
[01:17:06] dạng là đôi khi là ông ông kiểu là ông
[01:17:09] muốn mai mối bạn của mình cho một ông
[01:17:12] nào đó chẳng hạn một ai đó mà bạn không
[01:17:16] ạ Cái ông có thể lên đây ông ông gửi
[01:17:19] đường link này cho họ họ vào thể xem qua
[01:17:20] được toàn bộ thực sự người kia đăng
[01:17:22] những cái gì về từ các bạn bè xem được
[01:17:25] đâu mà ngày hôm đấy tôi làm theo dõi
[01:17:25] ngay
[01:17:28] giao diện được mới học không được đẹp
[01:17:29] lắm
[01:17:32] Ừ cái này ở xem được ảnh này xem trọn
[01:17:34] video người đang xanh 15 để đăng này Vân
[01:17:40] hồi đấy Mình đăng nhập ở đây mình không
[01:17:41] bị chơi for gì cả Không biết là bây giờ
[01:17:48] nó đương nhiên là hội cốt đấy Bây giờ
[01:17:52] Bây giờ toàn bộ code file Facebook của
[01:17:54] mình phải hơn 2 năm rồi mình không cập
[01:17:56] nhật nên có thể có vài dãy nó xong thấy
[01:17:59] bộ đổi rồi nó khó không làm được nữa nhớ
[01:18:05] à à
[01:18:09] ai đấy Cái cái bài toán Vừa rồi tôi nói
[01:18:11] qua các bạn thế để các bạn biết được à
[01:18:14] Làm một cái phần mềm thì các bạn chỉ cần
[01:18:17] nghĩ tưởng ra sôi các bạn tìm cách để mà
[01:18:18] làm thôi Đúng bọn nó không hẳn gì khó
[01:18:19] khăn cả
[01:18:22] toàn bộ mấy cái này tôi thấy Cốt nó bể
[01:18:25] tôi có lại vẫn được bởi vì nó rất là rẽ
[01:18:28] và các bạn chỉ cần tìm hiểu thêm về
[01:18:31] Facebook Lấy thông tin Facebook như nào
[01:18:34] là làm được thôi và vừa rồi còn biết qua
[01:18:36] thì lại một tí về cái bill đó không ạ
[01:18:43] Vì
[01:18:45] con cần gì có thể chia sẻ được mấy ông ở
[01:18:54] tôi nghĩa Tại hệ thế có một cái video
[01:18:57] của tôi đang rất nhạy cảm nữa không biết
[01:18:59] là chia sẻ mấy ông ở đây mấy ông có số
[01:19:04] bóc phốt tôi không nghe là thôi I
[01:19:06] à à
[01:19:07] em
[01:19:11] yêu tinh Security cái gì cả
[01:19:14] em làm tool centos mà người khác không
[01:19:17] thấy đi cái này thực à
[01:19:19] Ừ thì có nhiều cách
[01:19:23] anh có thể dùng như tim sakati kìa bản
[01:19:25] chất cái utxico ở nó sẽ là
[01:19:30] khi mà ông Tải video về chị thường là
[01:19:33] ông sẽ còn gửi thêm cảm cái đoạn thẳng
[01:19:35] Facebook thường ai làm cơ chế đấy Gửi
[01:19:38] lên sắc thuộc cái việc và ông đã xem
[01:19:40] video đấy thì thằng như tim protein nó
[01:19:41] tắt
[01:19:46] nó chặn cái việc gửi lên đấy thôi Nó nào
[01:19:48] giống như tim sokute nó chặn việc của
[01:19:52] mình là ngon thế nhưng mà chính vì chặn
[01:19:55] việc mình đang on là không báo lên hoặc
[01:19:57] Facebook là mình đã ngon đấy thì nó lại
[01:20:00] có nhược điểm đó là ông sẽ không nhận
[01:20:01] được thông báo
[01:20:04] Áo kiểu kiểu như thế bởi vì rõ ràng là
[01:20:08] ông chặn không bảo thằng Facebook là tao
[01:20:10] đang offline thì thằng Facebook nó sẽ
[01:20:12] không gửi lại cho ông cái việc là những
[01:20:14] cái thông báo mới đến an toàn này tại
[01:20:28] tí bạn đi xem những Story màng mình chưa
[01:20:37] à cái cái cái cái đấy cũng hay thế thôi
[01:20:39] mà tôi làm cái vừa nãy ý tôi phải chia
[01:20:41] sẻ cùng xem rồi đấy nó không có Sorry
[01:20:44] đâu chứ nếu mà có Sony sẽ tôi cũng làm
[01:20:45] đấy
[01:20:50] ừ ừ
[01:20:54] anh nói chung à Cái tune cuối này nó nó
[01:20:56] hơi nhạy cảm một tí tôi nói ra ở đây có
[01:20:59] gì cũng có một vài bạn nữ sẽ ghét tôi ở
[01:21:00] bóc phốt tôi nên tôi sẽ không chia sẻ
[01:21:03] rồi Như tôi sẽ chia sẻ với cái này
[01:21:05] khi tôi vừa nãy tôi Còn nói tôi Tải hết
[01:21:07] ảnh về đúng không ạ
[01:21:10] Và tôi nói tôi sẽ lọc những cái ảnh đấy
[01:21:12] như cách để cho lọc những cái ảnh đấy
[01:21:14] còn cách tôi sẽ làm tôi làm hạt cái tool
[01:21:17] này là cảnh như thế này nó kiểu ví dụ
[01:21:19] vừa rồi nó nói là thận sóng với mấy nhìn
[01:21:20] cái ảnh tao không bị diệt cùng một lúc 6
[01:21:24] mấy nghìn cái được thì tôi cần phải xóa
[01:21:26] những cái nào tôi đã xóa mà lưu lại
[01:21:29] những cái nào tôi đã duyệt không đấy thì
[01:21:37] ô tô tại hết ảnh về rồi tôi chỉ chọn thư
[01:21:39] mục thôi không ạ sẽ chỉ đi ra hết toàn
[01:21:41] bộ ảnh sau đó thì mình có thể làm có chế
[01:21:46] ra mình tích và những cái ảnh mà mình sẽ
[01:21:49] muốn lưu lại và xóa cải nào mình không
[01:21:57] a computing soket không phải do tôi làm
[01:22:00] đâu do Anh Tuấn làm đấy Anh đấy Thì đúng
[01:22:02] là anh anh ấy chưa khỏi định làm trên
[01:22:07] Firefox và tìm hiểu trên đấy mệt mà
[01:22:09] anh ấy không phải đấy Tôi làm cơ chế này
[01:22:10] nghĩa là tôi sẽ
[01:22:14] để duyệt đến một nửa sau tôi ấn nút chọn
[01:22:16] đâu chả lạ khi nó sẽ xóa toàn bộ những
[01:22:18] cái câu không chọn nhưng mà từ đầu cho
[01:22:20] đến cái tôi không trọng chứ không phải
[01:22:23] Xóa hết toàn bộ những cái thông trọng
[01:22:25] Ừ cái cái lâu rách để nó khá hợp lý mà
[01:22:28] thậm chí là cái này vừa rồi các bạn để ý
[01:22:30] kĩ kỳ tôi chỉ và ảnh nó còn phóng to
[01:22:33] được ảnh lên để mà cậu kiểm tra mụn kiểm
[01:22:36] tra gì đó hiểu Xem ảnh Thực sự nghe à
[01:22:38] Hồi nãy tội dùng cái tiện ích kỷ mà tải
[01:22:44] tải ảnh từ Instagram Ông thấy ở trên à
[01:22:47] ở trên thanh địa chỉ của tôi có cái phần
[01:22:50] tiện ích à chị nick nó down bung thì
[01:22:53] phải sẽ tải toàn bộ ảnh từ trên
[01:22:55] Instagram hình Nghĩa hồi đấy là có hỗ
[01:22:58] trợ cả Tải ảnh toàn bộ ảnh trên Facebook
[01:23:09] à à
[01:23:15] ok Nói chung là bây giờ cạn 9 giờ rồi
[01:23:18] ngoại mình chắc là hôm nay thở ra hơi
[01:23:20] nhàm chán một tí vì mình lỡ chia sẻ rất
[01:23:24] nhiều về cũng hay hay ở bên đó bên quét
[01:23:27] rồi và Xuka à Cũng gần đây cũng chẳng
[01:23:29] biết là chia sẻ thêm cái gì mới nữa bởi
[01:23:32] vì có rất nhiều vẻ hay nhưng thực sự thì
[01:23:35] phải đến theo các bạn đủ lượng kiến thức
[01:23:37] nhất định đã mình mới chia sẻ được con
[01:23:40] này mình chia sẻ với các bạn
[01:23:43] toàn bộ những cái khó khó được nên là
[01:23:45] các bạn không Ta không à
[01:23:48] không để hay hài hước mãi được
[01:23:53] do hôm nay tạm thế đã mình khi vọng mình
[01:23:54] nói truyền cảm hứng nữa các bạn một phần
[01:23:55] nào đó
[01:23:58] chào các bạn nha à
