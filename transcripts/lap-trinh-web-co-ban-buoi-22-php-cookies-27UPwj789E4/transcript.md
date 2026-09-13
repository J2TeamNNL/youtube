# Lập trình Web cơ bản - Buổi 22 - PHP - Cookies

- Video ID: `27UPwj789E4`
- URL: https://www.youtube.com/watch?v=27UPwj789E4
- Published: 2021-12-17
- Duration: 1h 41m 11s (6071s)
- Language: vi
- Subtitle source: auto
- Kind: live

## Transcript

[00:00:04] à à
[00:00:16] anh alo Chào con bằng Alo gọi nói này có
[00:00:19] vẻ hơi to quá vậy mình đẹp Cái này hay
[00:00:21] mình cảm thấy rất to to
[00:00:25] ờ ờ chào các bạn
[00:00:29] tranh thủ tâm sự một tí trước
[00:00:31] anh check mail
[00:00:34] bảo này bạn vừa gửi mail tâm sự tình cảm
[00:00:43] Ừ ok thì mình mình thử cái hôm nay không
[00:00:44] biết tâm sự gì hôm qua hôm trước thì
[00:00:46] muốn tâm sự đủ thứ hôm nay sẽ không biết
[00:00:49] tâm sự gì mấy mày sao Mình chỉ nói qua
[00:00:50] nhanh vậy cả giá
[00:00:54] kệ bày thử ta cái Ngó mà mình chưa làm
[00:00:57] ra khá nhiều nhóm kiểu tình cờ mình thấy
[00:01:01] ở trên trang chủ bởi vì mình mình không
[00:01:03] biết thì nói các bạn chưa là được là
[00:01:05] trang chủ của mình mình không theo dõi
[00:01:07] bạn bè mình bạn bè hôm trước hôm trước
[00:01:09] của ông mới cưới tôi còn chẳng biết ông
[00:01:12] đấy đã cưới rồi cơ kiểu thế gì à
[00:01:14] Ừ tôi không theo dõi bất kỳ bạn bè nào
[00:01:15] cả
[00:01:18] các bạn bè đôi bạn bè đôi khi đăng những
[00:01:20] cái thìa mình không quan tâm
[00:01:24] Ê bà thậm chí ở thằng Facebook nó còn nó
[00:01:26] còn thay đổi cơ chế thuật toán mà nó là
[00:01:29] bạn bè bình luận hay thích cái gì đó nó
[00:01:31] sẽ hiển thị lên trang chủ của mình thành
[00:01:32] ra là có rất nhiều thứ mà bạn bè thích
[00:01:35] mấy cái nhảm nhí tôi phải tình trạng cái
[00:01:35] thăm
[00:01:38] thằng bạn khá thân rồi ơi
[00:01:42] hội thân từ hồi cấp 2 tôi chạm nó chỉ bị
[00:01:45] nó chia sẻ mấy cái của em Plus chẳng hạn
[00:01:47] khi anh cờ thế
[00:01:50] Ừ Tôi Vẫn Nhớ cái lần mà hôm mà đi chơi
[00:01:53] với nó xong vui vẻ xong sao đi về rồi
[00:01:56] tôi bảo là có gì nhắn tin nói chuyện nốt
[00:02:00] ruồi nó nói câu đó là ông dặn tôi rồi
[00:02:02] còn đâu như kiểu thế
[00:02:07] nghe đại khái thế nhưng mà tôi lại vô
[00:02:09] tình thỉnh thoảng vẫn thấy được vài bài
[00:02:11] đăng từ người khác mà chính xác là từ
[00:02:13] những cái bạn nó hot girl mà tôi đang
[00:02:14] theo dõi
[00:02:17] Ừ tôi theo dõi mấy bạn hóa đơn thì Mục
[00:02:19] Đích Ngắm phần cũng là để mà
[00:02:22] em lấy ảnh mấy bạn đấy là đáng lên nữa
[00:02:24] mà thấy có mấy bạn gái anh chia sẻ Đủ
[00:02:28] thứ tiền hình à Mấy cái 22 cũng cũng
[00:02:30] cũng hay cũng một sự giải trí giống như
[00:02:32] cái bài này chẳng ạ Bạn ấy thì ra không
[00:02:34] hài cái nhóm này công nhận đăng nhiều
[00:02:36] cái hay liên quan đến công việc nhưng bà
[00:02:39] này không mẹ mày Mình thấy khả là hai
[00:02:43] lại cực tươi đây là nói lên tất cả đó là
[00:02:49] các bạn bạn này kiểu thư cá à Chẳng cần
[00:02:50] mình mình không cần phải đọc dài dòng
[00:02:53] tất cả đúng này thì ra là như tôi đã
[00:02:55] từng nói mấy bạn đó là đừng bao giờ nghe
[00:02:57] như kiểu của người giàu kể chuyện nó họ
[00:03:01] đã thành công Từ từ ABC như thế nào các
[00:03:03] bạn bắt chước thì đôi khi lại không được
[00:03:06] đâu cũng như là bắt chước Ở đây có rất
[00:03:08] nhiều yếu tố phải phải những nói chung
[00:03:11] là rất nhiều yếu tố thì họ kiểu đi con
[00:03:13] đường đấy mà nó ổn mẹ các bạn đừng phải
[00:03:16] nghe lời khuyên hay nghe hiểu anh học
[00:03:18] lập trình như thế nào để được như bây
[00:03:22] giờ vẫn Vân không không mỗi người sẽ có
[00:03:25] cách hợp khác nhau vân vân Nói chung ở
[00:03:28] mình chỉ cần học đúc kết là người ta có
[00:03:30] cái tư duy gì khi
[00:03:34] người ta có cái tư duy gì khi mà khi mà
[00:03:39] xử lý vấn đề khi mà cậu gặp khó khăn
[00:03:43] nóng ạ và họ có cái kiểu mục tiêu ngay
[00:03:46] từ lúc đầu họ đặt ra là gì mấy cái người
[00:03:48] thành công ấy ngay từ đầu người ta không
[00:03:50] nằm mục tiêu bé thôi chúng ta đặt mục
[00:03:52] tiêu lớn mà Đó Ngoại rất nhiều người
[00:03:54] thành công người ta đặt mục tiêu lớn chứ
[00:03:56] không phải đặt mục tiêu bé tí là tự
[00:03:57] nhiên thành công không có chuyện đấy
[00:04:01] đúng ạ Thật ra hôm trước tôi còn đọc một
[00:04:03] cái bài nữa Hai nữa
[00:04:07] anh nghe tội không lưu đó là kiểu à
[00:04:14] ờ ờ bài bài đấy Hãy tiêu đề bảo là chắc
[00:04:17] phỏng vấn chắc ma các sự thứ ra tôi
[00:04:19] không thích cái tiêu đề giật Tít kiểu
[00:04:21] như thế bởi vì tôi còn chẳng biết là
[00:04:24] thực sự ông ấy có nói có đấy không cũng
[00:04:26] như là chắc chắn ăn thêm mắm thêm muối
[00:04:29] vân vân được nghe người giàu kể chuyện
[00:04:31] nó vẫn là chuyện người giàu đúng không ạ
[00:04:35] nhưng mà ông ấy có cũng có nói việc là
[00:04:37] kiểu
[00:04:40] người nghèo là người
[00:04:43] ở nhà là người không phải là người không
[00:04:46] có tài sản mà người không thể làm ra
[00:04:49] được tẩy sạch ví dụ sợ là ông trúng số
[00:04:52] ông có vẻ Đang có triệu đô ông tay nhưng
[00:04:55] thực ra ông không biết tạo ra thêm tiền
[00:04:58] mỏng chỉ biết tiêu Thì đấy vẫn là người
[00:05:01] nghèo có nhiều tiền còn nếu mà nếu mà
[00:05:03] người mà đang không có tiền trong tay
[00:05:06] nhưng mà họ có thể làm đây của tài sản
[00:05:09] giống như các danh nhân hay các thứ thì
[00:05:11] họ chẳng qua là họ chưa đến thời để họ
[00:05:13] giàu nhưng mà họ sẽ giàu
[00:05:16] Ừ thế thế nơi nào Thực ra tôi cũng có
[00:05:18] một tí liên quan lễ hội trước tôi nói
[00:05:20] với ông rồi cái chị tiến thủ theo kiểu
[00:05:24] là đôi khi con gái họ sẽ chọn người mà
[00:05:26] có thể giàu trước à Có thể đâu nha Chứ
[00:05:28] biết rồi không Tôi bảo rồi cái đấy con
[00:05:30] nhưng con nhiều yếu tố nhưng mà họ có
[00:05:34] chí Tiến thủ họ có thể phấn đấu họ có
[00:05:37] thể thành công chứ không phải họ đứa
[00:05:40] hiểu quá khu nhà giàu Nhưng mà ăn chơi
[00:05:43] phá chỗ ngồi kiểu chẳng biết làm gì cả
[00:05:45] đúng ạ
[00:05:47] Ừ thì đứa con gái yêu khi không thích
[00:05:49] kiểu đấy nó thể thích theo kiểu thích
[00:05:53] yêu hẹn hò kiểu đi chơi họ không bao giờ
[00:05:56] thích cưới hồi đấy mối quan hệ lấy họ
[00:05:59] cảm thấy à về tương lai về sau trừ khi
[00:06:02] Giàu nó tiêu mãi không hết
[00:06:04] à à
[00:06:07] anh nói chung là vệ còn đúng rồi rồi
[00:06:10] nhắc hơi quá Nhưng nói chung và về cái
[00:06:12] bài này thì ra tội từng nói mấy ông về
[00:06:15] cái quan điểm của tôi đó là tôi làm việc
[00:06:17] ở trên công ty là rất là đài đinh lăng
[00:06:20] mạ tôi mang tiếng ở dân gọi là dân đẹp
[00:06:21] đúng không ạ
[00:06:25] Từ nhỏ tôi làm từ a đến z nhưng quán cả
[00:06:30] để hỗ trợ các thứ hướng hỗ trợ nhiều bên
[00:06:33] Ừ nhưng mà tôi không vừa nói cái câu là
[00:06:37] đấy không phải việc của em thứ thứ xếp
[00:06:40] mà có nhựa xếp có bảo là cậu đang có khó
[00:06:44] khăn gì thì thì tôi hỏi xong rồi tôi thử
[00:06:47] mỹ cách giải quyết Cùng Sếp cứ nói chung
[00:06:49] à Tôi chưa Rồi cái quan điểm đó là cái
[00:06:53] không phải việc của mình thì thực ra nó
[00:06:56] cũng hơi bị bốc đồng và cũng như là hơi
[00:06:58] bị tộc mạch một tí hoặc mặt trời không
[00:07:02] ăn thôi không là một đứa hay tò mò và
[00:07:03] chuyện riêng người khác nhưng mà ông chỉ
[00:07:06] đọc mạch ở đây làm chưa ạ việc gì cũng
[00:07:14] Em đã tắm rồi Đâu 8 giờ mới được học mà
[00:07:16] Đúng không ông vào sớm thì cũng phải
[00:07:25] khi hạ trầm ông ấy không thích nghe tôi
[00:07:28] sớm xong rồi Tôi ở xảy rất nhiều bình
[00:07:32] luận gần gần đây í a
[00:07:34] Em đừng như là bình luận ở những video
[00:07:36] cũ cơ nhưng mà vẫn ở gần đây chẳng hiểu
[00:07:39] sao mấy ông bảo là em không vào học đâu
[00:07:41] em kiểu đang chán đời tự như em vào nghe
[00:07:44] anh tâm sự để có lấy lại sự sợ ngay ngay
[00:07:47] giờ đây luôn rồi kìa Em em đang buồn rồi
[00:07:50] cậu nghe anh tâm sự dòng thoải mái các
[00:07:54] thứ có bạn và chỉ thích mấy cái kiểu
[00:07:58] mì cay cậu tâm sự đầu của video của anh
[00:07:59] thôi
[00:08:02] nhà nghèo hơi sai sai rồi rõ ràng hả
[00:08:06] ý là đây video chỉ với mục đích học đối
[00:08:09] nhà tôi cũng bảo tôi sẽ gửi gắm cái việc
[00:08:11] à tâm sự này để mà về sau các bạn quen
[00:08:14] dần với việc là tôi mà nhảy sang làm gì
[00:08:17] Locker như kiểu là vì sao tôi sẽ tâm sự
[00:08:20] nhiều hơn cũng cũng cũng vẫn là dân công
[00:08:22] nghệ thôi vẫn sẽ có liên quan đến cốt
[00:08:24] nhưng mà sẽ
[00:08:27] và chia sẻ nhiều cái không chỉ về mỗi
[00:08:36] khoa học TP như nào rồi qua level thì ở
[00:08:39] trận Thực ra là chính là cái khóa học
[00:08:40] này đây chính là khóa học lập trình web
[00:08:42] cơ bản này đây các bạn sẽ biết toàn bộ
[00:08:45] cơ bản hết một lượt từ đầu đến cuối
[00:08:48] và kết hợp với cả máy Ware để làm đầy đủ
[00:08:51] tính năng xem thêm sửa xóa ra mồi biết
[00:08:53] qua về những khái niệm kiểu sơn xong rồi
[00:08:55] Cookie hôm nay học này đối ngoại và giỏ
[00:08:59] và liên quan đến mạng các dư thứ sau đó
[00:09:03] thì khi mà nắm tương đối chắc rồi thì sẽ
[00:09:07] nhảy sang mô hình mô hình mới C sau đó
[00:09:11] thì ok hơn đối tượng sau đó thì nhảy
[00:09:15] sang lehrwerk nó có cả hai cái đấy đấy
[00:09:17] thì thì nói chung nhà mình thấy cái lộ
[00:09:31] Em làm thế nào để cho ra chữ như kiểu
[00:09:35] thẻ trong HTML nghĩa ý bạn ở inna Thẩm
[00:09:37] thẻ luôn đúng không Thì nó là
[00:09:41] chỗ thời cả các bạn phải lưu lại cả đấy
[00:09:43] đã đúng không ạ đưa lại rồi hiển thị ra
[00:09:47] chữ hay với lại các thẻ ở trong database
[00:09:50] xong rồi in nó ra hay như nào Nếu các
[00:09:52] bạn muốn in nó ra thuần thì các bạn có
[00:09:56] thể dùng cái này dùng có có thẻ để mà in
[00:09:59] ra khi mà các bạn ấy cho da mình nó sẽ
[00:10:02] Đúng là cái thứ mà các bạn Nhập vào đó
[00:10:07] là thẻ free hoặc vợ thể cốt đây hai cái
[00:10:10] thẻ này mình thường ai dùng thẻ cốt
[00:10:12] nhiều hơn thì vui rồi nó hiển thị nào
[00:10:16] trong hơi xấu thể cốt các bạn thể in
[00:10:18] vitro vào trong thể cốt thì nó các bạn
[00:10:20] Nhập vào cái gì nó sẽ in ra đúng như thế
[00:10:38] à à
[00:10:43] xe máy Ware có khác với SQL Server không
[00:10:47] mình nghĩa là sẽ có cú pháp khác khi con
[00:10:50] lợn về cơ chế chung thì mình nghĩa
[00:10:52] ashworth nó tương đối giống nhau chắc là
[00:10:54] nó sẽ có thêm vài cái ngoại lệ là khó
[00:10:57] thằng có cái này Có thằng không thôi có
[00:10:59] ở đây không chịu tất cả những thằng kia
[00:11:00] vẫn có nhá vẫn có nhưng mà ý kiến mình ạ
[00:11:03] Có ở đây làm chị ạ có một vài cái thay
[00:11:07] đổi nhỏ kiểu là vì ví dụ nhá thằng SQL
[00:11:09] Server thì nó có chi cơ liên quan đến
[00:11:11] Đăng nhập mẹ của em mình nhớ không có
[00:11:14] cái điều đấy Đấy đấy là một trong những
[00:11:16] cái thằng kia có thằng này không nhưng
[00:11:18] mà chích cơ nó cũng có những cái những
[00:11:27] Ừ Ok nói chung và bây giờ đến buổi học
[00:11:31] rồi thì hôm nay mình đầu tiên mình trả
[00:11:33] lời câu hỏi nhưng mà trước khi trả lời
[00:11:37] câu hỏi thì mình xin phép và chia sẻ cái
[00:11:43] à À cái giáo án mà mình từng là mình
[00:11:47] từng từng soạn để mà dạy ở trường mình
[00:11:50] nói qua một tí về cái giáo án này lại
[00:11:53] tâm sự thêm vài phút nữa tranh thủ
[00:11:59] thì đây tôi kể cho mấy hôm có chuyện về
[00:12:06] đầu tiên là trưởng chúng tôi thực ra
[00:12:09] chuẩn ở trường tôi nhiều các bạn tra thì
[00:12:12] nó là chuyên về mạnh chống lại chuyên
[00:12:15] viên lập chính nhưng mà cái thầy của tôi
[00:12:18] thấy thầy dạy biến Aptech Hồi đấy thời
[00:12:21] sự viên Aptech vậy sau đó thầy về trường
[00:12:24] này trường đầy À thầy thầy giáo dân
[00:12:26] chuyên toán nhưng thầy nhảy sang bên lập
[00:12:29] trình ạ sau đó đi vì dân chuyên toán nên
[00:12:32] tư duy thấy rất là hồn nè thành ra thầy
[00:12:37] cậu làm luôn và thầy cũng rất ạ giỏi
[00:12:38] xong việc à
[00:12:41] Nói thuyết phục người khác cũng như ở
[00:12:44] hiệu quản lý hay ra thầy kiêm luôn được
[00:12:48] cả bên quản lý nhân nhân nhân lực cho dù
[00:12:50] vẫn là thầy thầy Bình thường thôi nhưng
[00:12:53] mà thấy ở kiểu được phong lên làm trưởng
[00:12:54] phòng đào tạo nữa là quản lý con người
[00:12:59] sau đó thì Thầy nghĩ là trường
[00:13:01] thầy nghĩ ra luôn cả giáo án dạy bên lập
[00:13:03] trình ở trường của tôi và cùng trường
[00:13:06] tôi đã trở thành ra là kiểu nhiều người
[00:13:08] biết đến là do ngành bên lập trình hơn
[00:13:11] bởi vì ngành lập trình trường tôi thời
[00:13:14] mà tôi được đi học đấy thì cái cái đầu
[00:13:17] ra của trường tôi tỷ lệ đi làm cao phết
[00:13:19] phải bảy mươi phần trăm thôi mà còn hai
[00:13:23] thấy đầy dậy công nhận ông ông biết bảy
[00:13:24] mươi phần trăm là con số lớn như thế nào
[00:13:29] so với đại Em không sợ còn lên nội 50
[00:13:31] phần trăm chứ nó 70 phần trăm
[00:13:34] đây thì
[00:13:37] ạ sau đó thì phải
[00:13:39] thấy là cái bằng cấp của chúng tôi về cơ
[00:13:42] bản không phải bằng đại học mà sẽ chứng
[00:13:45] chỉ nghề ngọn cả là bằng cao đẳng nên
[00:13:49] thành ra thầy nên xin liên kết với
[00:13:53] trường đại học bên anh Quốc trường đấy
[00:13:57] nó có cái bằng quốc tế là cái bàn đấy Nó
[00:14:01] còn to hơn cả đại học chính quy ở to hơn
[00:14:02] đại học chính quy và được công nhận quốc
[00:14:06] tế luôn nhé Ừ đúng rồi thấy hạnh bạn kia
[00:14:09] học ở trường mình biết rồi thì
[00:14:12] từ thiện thế này là cái chương trình của
[00:14:14] nó rất khó Chương trình nó thực ra
[00:14:15] chương trình của anh Quốc thì nó sẽ biết
[00:14:25] áo kiểu dạng nào kiểu nó bị lý thuyết
[00:14:28] rất nhiều luôn ấy và nhưng mà trường
[00:14:29] mình ở trường nghề
[00:14:32] Vì thế nên là cái việc mà dạy lý thuyết
[00:14:35] như thế nó sẽ đi ngược lại với cái lúc
[00:14:36] đầu
[00:14:38] Ơ cái định hướng lúc đầu của trường mình
[00:14:41] nên là thầy phải cố sao cho là biến cái
[00:14:44] việc vừa kết hợp cả việc lý thuyết đấy
[00:14:46] vừa phải kết hợp việc thực hành nghĩa
[00:14:48] khó rất hiểu
[00:14:50] Ừ đúng rồi chương trình đấy chương trình
[00:14:53] bị tách cái chương trình đấy à Ở mới có
[00:14:58] 22 trường đại học ở Hà Nội mới mới nhận
[00:15:01] cái dạng cái giáo trình nói chung và
[00:15:04] nhận cái chương trình dậy một là FPT 2
[00:15:07] Đại học Kinh tế quốc dân như vậy nhưng
[00:15:08] Đại học Kinh Tế Quốc gia đình như chết
[00:15:10] cái chương trình này ngồi vì không dậy
[00:15:19] ở trường nghề nó sẽ giảm thiểu các môn
[00:15:21] đại cương khá nhiều đưa như có dậy mày
[00:15:23] cái buôn đầy nhưng mà giảm thiểu là cậu
[00:15:27] dậy chỉ là chùa không hẳn quan trọng
[00:15:29] chính là những môn đấy học vọng tương
[00:15:31] đối dễ thôi
[00:15:32] Ừ
[00:15:35] đúng rồi chương trình thực Hạnh chương
[00:15:36] trình nước ngoài đúng nhưng có thực hành
[00:15:38] nhiều nhưng mà cái chương trình bị chết
[00:15:40] đấy thì nó lý thuyết nó cũng rất rất
[00:15:43] nặng và nó toàn bộ bằng tiếng Anh nữa
[00:15:46] tay nhau các bạn phải 96 chấm các bạn
[00:15:48] mình gửi lãnh hội được thôi Đấy mình
[00:15:50] soạn giờ đây mình sẽ cho các bạn xem bây
[00:15:51] giờ mình
[00:15:52] cô
[00:15:54] giáo án của mình lên lại giờ mình sẵn
[00:15:56] sàng chia sẻ không ạ Nó không liên quan
[00:15:58] gì cả logo chúng tôi
[00:16:02] Nhớ lại hồi đấy à Tôi Tôi tự nhiên tôi
[00:16:05] phải dậy Cái môn à phải dậy nhưng mà
[00:16:09] chưa được dậy thì tôi nhỉ Mày thích dậy
[00:16:12] mình anh nữa cơ sở sau đó là toàn bộ
[00:16:18] và đương nhiên là tôi tôi nghe nói đọc
[00:16:20] viết thì ta cũng tương đối
[00:16:22] để tôi chữa thì IELTS nhưng mà tô ý
[00:16:25] nghĩa là tôi tôi tôi để tôi học được
[00:16:28] tiếng Anh tương đối rồi đấy Thì hôm nay
[00:16:32] tôi chính vì tôi đang nói hơi like hơi
[00:16:35] Lê Thế màn chất là tôi định cho mấy ông
[00:16:37] biết về cái này cái hôm nay tôi định nói
[00:16:43] là BM vs đi em ngoặc nó vô dmanager và
[00:16:46] crack manager đấy thì
[00:16:50] Ê hồi trước là tôi khi mà nghe kể về cô
[00:16:53] đắp Malaysia Tôi rất thích về cái đấy
[00:16:56] Tại sao bởi vì ở người ta làm người ấy
[00:17:06] ở chương trình học không có toán theo
[00:17:08] giá
[00:17:10] Ừ đúng rồi mà chỉ ông đang họp bị tách
[00:17:13] thì ta toàn ra cái thời tôi thì có
[00:17:16] cái code Manager thì
[00:17:20] nó là kiểu nó nó sẽ làm việc với cả
[00:17:23] khách hàng nhựa hơn khách hàng để mà đưa
[00:17:26] ra những quyết định của dự án
[00:17:30] Ê bà Kiểu Tâm nhìn nhờ chiến lược các tự
[00:17:34] thứ không Thời gian cứ xong rồi Kiểu nói
[00:17:36] chung là nó lên Nó lên kế hoạch
[00:17:39] còn phu Jackman other thì nó sẽ là kiểu
[00:17:43] đi và thực hành nó sẽ là kiểu dao pass
[00:17:46] là sau đó thì nó phải kiểu và toàn
[00:17:48] dashed Line này sao nó quản lý nhân nhân
[00:17:52] lực này và luôn vần các thứ thì tôi thấy
[00:17:56] thực ra là có nhiều công ty nó gộp chung
[00:17:58] hai cái này vào một đặt tên nó leader
[00:18:00] thì cho anh
[00:18:04] những tùy từng công ty nhé Thực ra là
[00:18:07] những kẻ khái niệm về về cái vị trí nhân
[00:18:09] lực này nó sẽ có thể khác nhau tùy từng
[00:18:11] công ty luôn Ông đặc biệt ông cha mình
[00:18:13] cái này ở trên công ty Việt Nam cho bạn
[00:18:17] cứ cứ mỗi một công ty nó quan điểm cái
[00:18:20] cánh cái việc đấy làm cãi nhau một tí
[00:18:23] nhưng mà thực À cái cái này là tôi cái
[00:18:26] này tôi soạn vào từ Chuẩn rồi đấy ạ ở
[00:18:29] trang nào tôi chả nhớ trang gì Nói Chúng
[00:18:32] mày chém nữa ngoài nói chung là cũng
[00:18:35] tương đối tín đi ấy kiểu Huế
[00:18:39] đại cái thế này là ám chỉ đây đây cũng
[00:18:41] là thêm 2 công việc nữa để cho mấy ông
[00:18:44] Cân nhắc nói cho một cái thì nó liên
[00:18:47] quan đến việc bà ông làm lít Nhưng mà
[00:18:49] ông sẽ là kiểu đưa ra quyết định và làm
[00:18:52] việc với con người nhiều hơn con người
[00:18:54] con người ngoài kiểu khách hàng ấy và
[00:18:58] một cái thì ông sẽ cũng là làm lít Nhưng
[00:19:01] mà ông sẽ làm việc với đội tách độ
[00:19:04] chuyên môn nhiều hơn bóng làm việc nói
[00:19:07] chung và ông ông làm theo dạng Suneo
[00:19:10] kiểu thế đấy nếu thể cân nhắc việc là
[00:19:12] đương nhiên là ông Làm lập trình viên
[00:19:14] thì không về sau sẽ phải cân nhắc nhở
[00:19:15] ông sẽ thăng tiến lên thành cái gì ông ạ
[00:19:18] Chị có hỏi mãi em là trình viên được cái
[00:19:20] cậu đấy chỉnh Anh Tuấn gần đây có nói
[00:19:24] thôi anh Thiện Thiện Bởi vì tôi bảo là
[00:19:26] tôi không muốn làm quản lý con người
[00:19:29] nhanh bảo về sau kiểu gì em phải lên làm
[00:19:32] lãnh làm kiểu vị trí cao hơn chứ em là
[00:19:35] mãi là mã lập trình viên suốt là nó
[00:19:40] ngoan khi thì mấy ông mấy ông sẽ phải
[00:19:42] cậu nghĩ ông chạy lên và ngồi trước gì
[00:19:45] đó không ạ thì mày ông sẽ cân nhắc này
[00:19:48] hay đấy Hai cái cái này đó là một cái
[00:19:51] thì quản lý quản lý theo kiểu là quản lý
[00:19:53] chiến lược sau đó thì nói chuyện với đối
[00:19:57] tác nhiều hơn một cái là quản lý đội tá
[00:20:01] à Mà ông sẽ vẫn làm việc với độ tách Ông
[00:20:03] vẫn sẽ làm công việc tách nhiều hơn để
[00:20:11] à à
[00:20:17] Ê mấy ông nghỉ rồi Đang bận chuyện đấy
[00:20:20] Alo
[00:20:22] à Tôi đang chia sẻ Nhắc tôi không tâm sự
[00:20:30] Ừ Ok thôi mà quay lại câu hỏi vậy Nó
[00:20:33] tiên thì có bạn không trước họ rất là 2a
[00:20:37] các bạn bạn để hỏi thôi Thực ra là cùng
[00:20:41] mua mic giống nhau nên chắc nó cùng thu
[00:20:43] lại giọng giống nhau đấy
[00:20:48] đầu tiên là bạn ấy hỏi ra viết sky kéo
[00:20:51] Anh hiểu Phân tích các kiểu thứ thực là
[00:20:54] tôi chưa dạy mấy ông vụ đấy mà Đến gần
[00:20:56] cuối của cái đùa này tôi sẽ dạy mày
[00:20:59] không biết tại sao cái này là phân tích
[00:21:02] cụ thể là xem xem xem là cậu thực cao
[00:21:04] tính năng đăng nhập đấy thì các bạn sẽ
[00:21:06] phải làm từng bước từng bước như nào thì
[00:21:08] lăng đăng ký các bạn làm từng bước từng
[00:21:11] bước nhạc thậm chí hiển thị Hiển thị tất
[00:21:12] cả sản phẩm thì các bạn phải làm từng
[00:21:14] bước từng bước như nào nghĩa làm chi rồi
[00:21:17] Ai là người có thể thực hiện được tính
[00:21:19] năng đấy tính năng lấy bản chất nó là gì
[00:21:23] thì dụng tính năng đăng đăng ký chẳng
[00:21:25] hạn nó ngoan hôm trước các bạn xem một
[00:21:28] cái đăng ký rồi đăng kỵ các bạn bây giờ
[00:21:30] chả cốt được tính năng đăng ký rồi nhưng
[00:21:33] bây giờ để để mà thử phân tích đó lại
[00:21:37] nha Ờ thì đầu tiên nào khi mập thi và
[00:21:39] đăng ký chị các bạn sẽ Click vào cái nút
[00:21:42] đăng kí ở Đông ạ sau đó thì sẽ hiển thị
[00:21:44] ra cái form để các bạn điền thông tin
[00:21:47] điền cái gì Điền email và mật khẩu không
[00:21:49] ạ sau đó thì các bạn sẽ nhấn nút đăng
[00:21:52] nhập sau đó thì nữa thì sẽ nhảy sang ván
[00:21:57] sang trang xử lý đăng ký sợ lấy thông
[00:22:00] tin mà người dùng bạn Điền về có thể
[00:22:02] vides Dạo này kiểm tra không được để
[00:22:05] trống các thứ ngoại sau đó thì các bạn
[00:22:08] sẽ kết nối cơ sở dữ liệu kiểm tra có có
[00:22:11] bất kỳ tài khoản nào ở trong bảng người
[00:22:14] dùng bằng khách hàng là bạn nó nhọn dùng
[00:22:16] email mật khẩu đã nhập đúng không Đấy
[00:22:19] sau đó thì nếu mà chồng thì sao Nếu
[00:22:21] không chung thì sao đấy các bạn phải
[00:22:24] liệt kê hết tất cả những cái những cái
[00:22:27] đấy ra bằng văn xuôi bằng văn xuôi nghĩa
[00:22:29] các bạn sẽ phải làm tình năng phân tích
[00:22:34] Chị chuẩn chuẩn là thực ra làm cái phần
[00:22:36] mềm này các bạn phải phân tích cái đấy
[00:22:38] bằng văn xuôi trước gần như kiểu sông Mã
[00:22:41] giả trước trước khi mà các bạn cốt nhưng
[00:22:44] mà vì bản chất là các bạn còn chưa biết
[00:22:45] được chốt mình cái bạn này như thế nào
[00:22:47] nên thành ra là tôi phải làm ngược lại
[00:22:50] đó tôi phải dậy Nếu cốt trước đã sau đó
[00:22:53] thì tôi mới dậy Mà ông viết tài liệu về
[00:22:57] nó còn đến đồ ăn 2 đến đồ ăn hay thì
[00:23:00] không phải làm Huawei đồng ạ nghĩa là
[00:23:03] mấy ông phải phân tích phải thiết kế sau
[00:23:05] đó Nói chung phải làm hết tất cả những
[00:23:09] cái kiểu những cái đầu trước trước khi
[00:23:11] mà Mấy ông đến cốt Nếu không được anh
[00:23:13] ngại nhất về mình cái đâu đấy nhưng mà
[00:23:15] khi mà các bạn phân tích xong hết rồi
[00:23:18] thì các bạn Cốt và cốt chỉ dựa theo cái
[00:23:21] đấy thôi thì nó mới chọn ngoạn phải có
[00:23:23] tài liệu chứ để mà người sau người ta
[00:23:25] không nhìn vào cốt của mấy ông người ta
[00:23:27] nhìn vào tài liệu ở làm và đặc biệt là
[00:23:29] đôi khi vứt cái tài liệu đấy cho bất kỳ
[00:23:32] ai Ừ cũng được chứ nếu mà không gửi ông
[00:23:35] tự nghĩ ra cốc à đúng ạ Nếu bắt buộc
[00:23:39] phải có phải có tài liệu nó phải có
[00:23:42] chuẩn như thế nếu người có tài liệu và
[00:23:44] về sau người ta sẽ gửi trong tài liệu để
[00:23:49] Anh để máy mài ông nhìn vào tài liệu này
[00:23:55] Ừ đúng rồi mu nữa
[00:23:57] ở gần đây tôi học liên thông được cũng
[00:24:00] có phải môn nó có nhắc đến vụ này quản
[00:24:05] lý mềm xô ngồi các thứ có
[00:24:07] ông ngoại môn phân tích nhất thì thiết
[00:24:10] kế hệ thống có rồi cũng mệt vãi Hình như
[00:24:18] bí ngô mới không hiểu gì tôi không đấy
[00:24:21] mẹ không phải có những cái đấy trước
[00:24:24] à Tôi đang dạy tôi bảo tôi dạy nghề nên
[00:24:26] Hãy nghe tôi dậy mấy ông nó đôi khi mà
[00:24:29] nhìn ra được kết quả trước đúng ạ nhưng
[00:24:31] mà để mà làm chuẩn từ đầu đến cuối đứng
[00:24:33] yên kiểu gì Miễu ngày có nếu không tránh
[00:24:34] được
[00:24:36] Ừ nhưng mà đương nhiên để tôi bảo ở nếu
[00:24:38] không phải Ông làm cái đấy ông thấy chán
[00:24:40] không ạ Ok thì về sau mấy ông sẽ tập
[00:24:43] trung vào pin code nhiều hơn không nhất
[00:24:45] thiết mấy ông vì sao đăng ký mấy ông sẽ
[00:24:47] phải làm những cái việc đấy
[00:24:50] Tôi học nghề tôi không không phải học
[00:24:53] cái đấy nhiều Hồi đấy tôi cũng được học
[00:24:55] giống như là tôi đang dạy mấy ông này
[00:24:58] tôi đang dạy mấy ông những cái mà tôi đã
[00:24:59] từng được học
[00:25:02] Ừ Thế hồi Mở tôi đang ôm đúng đầy giáo
[00:25:03] án giáo trình mà hồi ấy tôi điều hòa với
[00:25:06] tao giận mày ông thôi Đó là theo kiểu là
[00:25:09] tôi sẽ học cốt trước sau đó đi về sau
[00:25:12] tôi làm tài liệu đấy được không ạ
[00:25:16] tôi thấy tôi thấy nó hiệu quả với tôi
[00:25:18] thế nên tôi đang dạy lại mấy ông như thế
[00:25:20] đương nhiên là tôi tôi không chết ấy còn
[00:25:22] nói cho tôi đã chỉnh sửa một vài cái đó
[00:25:25] tôi đã giảm tải phải cái mà Tôi thấy à
[00:25:28] rồi đấy Tôi không Không cần phải nghe
[00:25:30] những điều đấy Mình chưa đủ quan trọng
[00:25:32] Tôi đã giảm tải mấy ông rồi nên em mấy
[00:25:35] ông bây giờ mới thấy tôi dậy nó khá là
[00:25:38] mượt và nhanh nhanh ấy phải rùng mình
[00:25:41] anh Bởi vì ạ Thôi đấy tôi đi tôi học
[00:25:45] HTML CSS là Swift xô ngồi TP phải 34
[00:25:48] tháng Có chứ phải đến bây giờ đã nhảy
[00:26:02] Ừ ok Tiếp theo là cái vụ ở đây là tôi có
[00:26:04] hứa cũng ngồi bạn nào đó
[00:26:07] 2095 tên ở đây đó là nếu là bạn đấy mà
[00:26:09] làm đồ án này tương đối thành công thì
[00:26:13] thôi sẽ vào Đà Nẵng có thể thế nói rõ mà
[00:26:17] phải đợi bước dịch đã thì nên là mấy anh
[00:26:20] em ở đây mà có ông nào Đà Nẵng thì ra là
[00:26:23] điểm danh phát thì tôi thấy đông đủ làm
[00:26:32] anh ở đây sẽ có tôi có quen cũng ba bốn
[00:26:35] ông ở trong Đà Nẵng thôi từng vào Đà
[00:26:37] Nẵng một lần trần đấy khá thân thiện
[00:26:40] Ừ ông anh tôi từng rơi hai lần cái điện
[00:26:45] thoại iPhone iPhone 10 Nói chung là thời
[00:26:47] đại hiện Hồi đấy là iPhone này IPhone
[00:26:49] mới nhất rồi hai lần trên taxi người ta
[00:26:50] được gọi trả lại
[00:26:53] sự thay đổi thực hiện vãi chưởng
[00:26:54] à à
[00:26:58] em hỏi ông kia ở Đà Nẵng ngon
[00:27:01] ở Sài Gòn thì kiểu gì tôi bảo tôi định
[00:27:02] sẽ vào
[00:27:03] ở nhà
[00:27:06] đợi bất dịch cho tôi sẽ vào đã Sài Gòn
[00:27:09] trước cơ à
[00:27:11] anh nói nói như kiểu mình là người nổi
[00:27:13] tiếng Nga không có lỗi gì em bao nhiêu
[00:27:16] mà ý tôi là kiểu Tôi sẽ mở offline có
[00:27:17] thể không phải mỗi cho anh em mình mà
[00:27:21] cho cả dư tin community anh bởi vì mấy
[00:27:23] ông từng câu ca rồi mấy cái kiểu tỉnh
[00:27:27] lớn này từ thiếu ca rồi nó lắm chị ạ Mấy
[00:27:29] anh Tân tổ chức offline ở hai tỉnh lớn
[00:27:30] kia mà những cái tình lớn còn lại thì
[00:27:34] không tổ chức Offline lần nào thì thì ca
[00:27:36] Tôi từng nói là bởi vì không có ban quản
[00:27:39] trị nào đấy vào đấy tổ chức cả thì lần
[00:27:41] này tôi vào thì tôi có thể dẫn sẽ tôi
[00:27:49] Ẩm Thực ra là không quan trọng mình
[00:27:52] nhiều người lắm nhiều người lắm chứ Tôi
[00:27:55] đang sợ quá tay anh cậu ít thôi tầm
[00:27:59] lý tưởng nhất ở thực ra chỉ cần mà mà
[00:28:03] 23 bàn cà phê giống kiểu hai bà nội lậu
[00:28:08] ấy bây giờ kiểu đứng đứng từ đừng những
[00:28:10] từ đầu cái bàn lại rồi đến cuối lần kia
[00:28:12] kêu mà người kia chả nghe thấy gì vậy
[00:28:15] Bốn ngoại nếu lúc đầy cho không nói
[00:28:17] chuyện được với nhau với ông kéo chỉ
[00:28:19] ngồi vắt thôi
[00:28:27] a tiếp theo nhé học học về an ninh mạng
[00:28:30] Thực ra tôi có từng học ạ an ninh mạng
[00:28:34] và biết qua thì tôi thấy thực ra là
[00:28:37] không cần đại học ngôn ngữ lập trình lắm
[00:28:41] anh không cần lắm Bởi vì A vẫn có thể có
[00:28:42] theo kiểu
[00:28:45] ở Mỹ hay vẫn còn anh quan bởi vì có viết
[00:28:48] bot các thứ nhưng mà không cần lắm chủ
[00:28:52] yếu về phần cứng thì đúng và mạng nữa
[00:28:54] anh em hãy ở thời ra các bạn lên tra
[00:28:57] mạng nhiều hơn nó hỏi trực tiếp như một
[00:28:59] thằng dân công gần không liên quan lắm
[00:29:02] không ạ tiếp theo là hôm chưa có bạn hỏi
[00:29:04] về cái season flash vào sao không áp
[00:29:06] dụng cái này thì chở Hôm nay tôi sẽ ăn
[00:29:10] dụng luôn này và hầm ăn xét nữa ham ăn
[00:29:13] xét là hàm gì À đây mình trả lời nó câu
[00:29:16] này trước khi nhảy sang cốt nhé Thì có
[00:29:18] bạn bảo là Clone của web khác kiểu như
[00:29:21] thế nào thực ra là các bạn đã từng nghe
[00:29:23] khái niệm về chromaweb thích cám chim
[00:29:26] tao copy hết toàn bộ web khác về trong
[00:29:29] ống Hiệp cái quét khác về thời ra các
[00:29:32] bạn khó là thể load web khác về được trừ
[00:29:34] khi các bạn hoàn nuôi cá tải hết toàn bộ
[00:29:37] hgcs nó về thì chồng có về giống hệt nó
[00:29:40] chứ không còn khái niệm mà lắm chị ạ Có
[00:29:42] được cả cốt hổ cốt của nó thì không có
[00:29:45] gì cô nói Chủ yếu là xử lý bác em thì
[00:29:48] các bạn sẽ không mờ biết được Cố tỏ như
[00:29:52] nào à Còn nếu làm chỉ các bạn copy và
[00:30:00] ở đây mình sẽ nói về hàm ăn xét đầu tiên
[00:30:09] à à
[00:30:12] dịch vụ đăng ký này thì các bạn thấy à À
[00:30:14] nhầm đang xuất đăng xuất thì hôm trước
[00:30:17] mình nó là có hai cách một là các bạn
[00:30:19] dùng season flash assistant
[00:30:24] trên sân golf để mà xóa toàn bộ cái đang
[00:30:26] lưu trong sân đi
[00:30:30] như thế này nhưng mà thực ra cách này
[00:30:32] như mình đã nói Thực ra là nó không hay
[00:30:34] hiểu nghĩa về sau mình còn là liên quan
[00:30:36] đến sẽ dần nữa đó là chỉ mang cái giỏ
[00:30:38] hàng các bạn không thể đăng đăng xuất ở
[00:30:40] bài thơ cái giỏ hàng người ta được trải
[00:30:42] nghiệm mình không tốt nên là các bạn chỉ
[00:30:44] nên xóa những cái mà các bạn đang lưu
[00:30:47] trong thời kỳ đăng nhập tất cả ID hoặc
[00:30:50] rõ tên đó ông ạ thì thì
[00:30:54] dù kẻ phàm ăn xét này nó xóa đi cải đang
[00:30:55] lưu
[00:30:59] khi cài nó đang tồn tại ạ đương nhiên là
[00:31:02] cái này nếu sử đang trống thì nó vẫn
[00:31:04] không báo lỗi gì cả và cái này nó sẽ
[00:31:07] không chỉ bạn đấy bảo là làm việc với
[00:31:09] mỗi mảnh nó không đúng cái ăn sẽ này thể
[00:31:12] xóa được cảm biến hay bất cứ cái gì cả
[00:31:16] Tôi cho ông một ví dụ đơn giản đi mình
[00:31:19] có test chấm pp này cái phê ở đây là sự
[00:31:22] đối là a = 5 này xong rồi ê trôi đâu là
[00:31:25] a này kiểu như này em một cái rất đơn
[00:31:34] I have shown that này cho P đấy
[00:31:37] đấy mời bạn phải đi là số 50 ạ nhưng bây
[00:31:42] giờ sửa mình sẽ ăn xét đô la ngày trước
[00:31:45] đi Tôi có xóa bina đi các bạn sẽ thấy là
[00:31:47] biển a Không Tồn tại nói chuyện đó giảm
[00:31:50] đi đâu Anh sẽ xóa đi một cái gì đó khỏi
[00:31:54] bộ nhớ đệm vừa để tiết kiệm bộ nhớ và để
[00:31:57] cho cái bé này không tồn tại nữa cái ăn
[00:31:59] xét này được Dùng khá nhiều về sau các
[00:32:01] bạn sẽ thấy được Dùng khá nhiều tiền
[00:32:03] hình giống như tôi đang làm ở công ty
[00:32:05] giờ thực ra có nhiều dữ liệu nó lớn quá
[00:32:09] các bạn không sử dụng nó nữa ở dưới các
[00:32:12] bạn muốn cậu giải phóng ra mỏng Anh ấy
[00:32:15] thì các bạn sẽ ăn xe đi đứng yên à sẽ có
[00:32:17] một thời gian là để cái file chạy sóng
[00:32:20] thực thi rồi ram nóng sẽ bị xóa và ram
[00:32:23] thôi nhưng mà nó vẫn về các bạn thì mình
[00:32:25] xóa nhanh nó luôn đi thì các bạn sử dụng
[00:32:27] ăn sét Đồ ngoại mà
[00:32:29] a tiếp theo là
[00:32:37] ờ ờ
[00:32:39] À hôm trước là mình nói về cái vụ là
[00:32:41] thật sự là
[00:32:44] khi đăng nhập bại thì phải Đợi mình tí
[00:32:51] an Đăng ký Đăng ký Các bạn nhớ Cái vụ
[00:32:53] hôm trước về cái vụ đăng ký này lại thử
[00:32:54] nhé
[00:32:58] size up trên phê này
[00:33:02] ở đây cũng trước là sự Càn Long hacker
[00:33:03] Đông ạ ạ
[00:33:11] À hôm trước của ký Email này rồi em mình
[00:33:14] đăng ký lại như này bạn sẽ thấy nó sẽ
[00:33:18] báo lỗi gọi chồng email rồi nhưng mà Cái
[00:33:20] lỗi này để hai địa chỉ như thế này tất
[00:33:22] cả bên mình tải đạn cha nó lại thì chị
[00:33:25] Đỗ này tôi giờ xử lý copy cái lỗ này cho
[00:33:29] một bạn ABC Eyes các bạn ấy lại hiểu lại
[00:33:30] xem rồi cả lỗi này sẽ trải nghiệm người
[00:33:33] dùng để không tốt cái lỗ này chỉ cần nên
[00:33:35] Hiển thị một lần thôi thì thì nên là sẽ
[00:33:38] có khái niệm mà system flash tất cả chị
[00:33:41] ạ là nó lưu đại season vừa nói hiển thị
[00:33:44] đúng một lần thấy cả tôi biết đấy biến
[00:33:49] lauras thôi chứ áp dụng nó trên PC rồi
[00:33:51] để tôi thử tra Google phát nhá á
[00:33:53] các em à
[00:33:57] từ đó làm cơ chế là như thế nào
[00:34:01] ở hà nộiăn xét ở đây thôi ok lẽ là lấy
[00:34:04] nó ra in là ra cho ăn xét xóa nó đi ok
[00:34:07] thì các bạn vừa rồi thấy được có cốt rồi
[00:34:10] đấy đúng ạ đó rất là đầu tiên mình sẽ xử
[00:34:12] lý đăng đăng ký này
[00:34:16] ở đây cái đoạn này thay vì các bạn như
[00:34:18] thế này Xóa đi này
[00:34:21] đây cái đoạn thông báo lỗi đúng ạ hả đi
[00:34:25] Sủa đúng không ạ Mình sẽ có season start
[00:34:26] này
[00:34:30] sau đó thì mình sẽ lưu vào trong sân một
[00:34:34] cái biến gyro này sẽ bằng cái đoạn suối
[00:34:36] này như thế này vừa có bạn vẫn sẽ lưu
[00:34:40] hướng về những thứ còn ở bên này thì các
[00:34:41] bạn sẽ là
[00:34:44] thì mình sẽ restart Ở đây thư da như tôi
[00:34:49] đã từng nói phát ở trên cùng nó vẫn hơn
[00:34:52] đầy hội ở đây cũng được đây mình sẽ là
[00:34:54] ít
[00:34:58] Ừ nếu có tồn tại là Issac season Hero
[00:34:59] đúng ạ
[00:35:03] đều có trong vệ sinh thì mình sẽ cho
[00:35:05] assistant
[00:35:10] Hero sau đó thì ăn xét nó đi để xóa nó
[00:35:14] đi in một lần rồi xóa đi như này à
[00:35:17] ở đây Các bạn thấy đầu tiên là bây giờ
[00:35:19] không có gì mình chưa lưu trong thí sinh
[00:35:21] tạo lại
[00:35:28] này mật khẩu không quan trọng không ạ ạ
[00:35:34] á khẩu nhạc ấy chung email rồi nó tại
[00:35:36] lại tra thì có bạn sẽ không thấy cái lỗi
[00:35:39] đấy nữa đây sẽ là áp dụng cái sân flash
[00:35:43] con Bộ hôm nay mình dạy về bánh quy đúng
[00:35:46] không ạ với Cookie thì được à Mấy ông bà
[00:35:48] hỏi tôi tại sao tên nó có kì đâu không
[00:35:51] biết giải thích nha đi cái đấy tên của
[00:35:54] nó đặt từ lâu quý không nó cũng được Tại
[00:35:57] sao là tới nó bất vậy Bắp thì ít ra là
[00:36:00] bởi vì đã từng có một con bọ ở trong máy
[00:36:03] tính mà không có thật tên nó bất con
[00:36:05] quốc kỳ tôi không không hiểu thật
[00:36:08] Nhưng mà đại khái đồng tiền này các bạn
[00:36:12] sẽ phân biệt à season Cookie và thuận
[00:36:15] chỉ cách nữa mình sẽ giải thích qua cái
[00:36:18] ảnh này mình đang mở ba cái tát về nó
[00:36:20] bởi vì mỗi cái bài đăng nó có một cái ra
[00:36:23] ý nào đó không đụng hẳn và thằng viên
[00:36:26] phải là mình phải mở 3 bài nhưng mà mình
[00:36:28] thấy cái bài này có cái ảnh này Thực ra
[00:36:28] tôi
[00:36:31] em thấy cái ảnh này khá ổn này mấy ông
[00:36:33] thấy lúc đầu có bốn cái bánh quy ở trên
[00:36:35] cái máy này không ạ sau đó thì khi mà
[00:36:38] kết nối qua server đó nó sẽ có thêm một
[00:36:41] cái bánh quy và gửi lại cho ông Thành 5
[00:36:43] cái bánh quy không ạ Ở đây thì ra nó
[00:36:45] không phải nói đúng lắm không đúng lắm
[00:36:47] lại sao vì thứ nhất
[00:36:49] ở đó nè
[00:36:52] ở đầu tiên tôi nói nó về cái đúng đi đó
[00:36:54] đúng à khi mong kết nối mất cái gì nó sẽ
[00:36:57] luôn Hỏi ông cái quyền thường Xuka nó
[00:36:58] hỏi cho có thôi Được cái kiểu gì nó cũng
[00:37:01] sẽ lấy những cái hỏi đấy là bởi vì theo
[00:37:04] quy tắc của bên châu Âu bây giờ nó bắt
[00:37:06] buộc cả nó luôn phải nói lại em nuôi dù
[00:37:07] nhà ạ là
[00:37:11] mày có cho lấy cô kia không hôm trước
[00:37:13] rồi có câu chuyện cười cái này rồi Bây
[00:37:29] khi nghe tin mới to
[00:37:34] mà sắp được con khỉ như cô thì đố vui
[00:37:39] cuộc thi selfie now You can tell me Okay
[00:37:41] I
[00:37:44] thì ra là có những cái những cái kiểu và
[00:37:47] cái MI hài phải có kỹ lại khá nhiều rồi
[00:37:49] í
[00:37:51] thế nhưng đại khái như thế bên châu Âu
[00:37:54] bây giờ đang chơi trò là kiểu hỏi là
[00:37:58] kiểu phải cho tao cho tao kiểu truy cập
[00:38:00] và quốc kỳ của mày đã sau đó thì mới cho
[00:38:03] Duy tiếp Nhưng mà bản chất thì dùng ra
[00:38:05] Swift với nó vẫn lấy được rồi nó bảo rồi
[00:38:07] bởi vì trâu bây giờ đang có bật lại như
[00:38:10] thế nhưng thực ra thì mẹ không chấp nhận
[00:38:14] a
[00:38:17] tiếp theo là nó lấy xong rồi nó sẽ làm
[00:38:21] gì còn chết rồi Nó lấy để mà để mà nó có
[00:38:23] thể thu thập thông tin từ của ông để Mã
[00:38:25] Phục phục vụ cho ông tốt hơn thường ý
[00:38:29] thế nên là thật ra cái trong Cookie đôi
[00:38:30] khi nó không còn những cái thứ có thể
[00:38:33] nhạy cảm trong đấy Cường chỉ ở những cái
[00:38:35] thông tin mà những cái trong cái ông
[00:38:37] dùng truy cập Thấy cái là nó cũng hơi bị
[00:38:39] sai một tí bởi vì dựa theo những trang
[00:38:42] web của ông truy cập thành ra là nó đề
[00:38:43] xuất cho ông quảng cáo rất là nhiều điển
[00:38:46] hình là mấy ông thấy rõ ràng là ông chắc
[00:38:51] ông theo ông và bất kỳ Trang web nào sau
[00:38:53] lúc sau quảng cáo ở trên Google nó quảng
[00:38:55] cáo Facebook đi xuống vậy Rất chuẩn em ạ
[00:38:58] Đấy Chúng tôi là bởi vì nó lấy Cookie
[00:39:00] đầu tiên thì ông và những trong Peppa
[00:39:02] trang web ấy đưa nó tự động ghi công ty
[00:39:06] và sinh máy của ông đấy Sau đó thì khi
[00:39:08] mà ông vào lại Facebook hay ở Google thì
[00:39:11] nó lại lấy lại Cookie từ những thằng kia
[00:39:13] xong nó đề xuất quảng cáo thành ra ở
[00:39:16] Quảng cáo rất là chuẩn ông vừa xem bài
[00:39:21] đăng nào vừa xem cái sản phẩm về máy
[00:39:24] A gọi đồ cho người lớn ở ạ Đấy sau đó
[00:39:27] thì lúc sau đề xuất một loạt ở trên
[00:39:28] quảng cáo của ông ông không hiện lại sa
[00:39:30] lạc Nhạn không đi giải thích trong video
[00:39:33] nha em ạ đấy thì cái đấy là do cái cơ
[00:39:37] chế có key này cái lý do mà Mấy ông lướt
[00:39:39] mày cái những cái mà cũng không muốn đi
[00:39:41] suốt quảng cáo thì mới ông nên dùng bằng
[00:39:43] trình chuẩn danh đúng không ạ thì nó sẽ
[00:39:45] không khí quốc kỳ của ông và nó không
[00:39:47] đấy không khí của ông ạ
[00:39:50] Ừ ok thấy là tôi bảo cái này không đúng
[00:39:54] là điểm là đôi khi ạ Nó sẽ lấy và nó sẽ
[00:39:57] đọc nhưng mà chưa chắc màu ghi vào có tí
[00:39:58] đường cái nó sẽ đi vào
[00:40:05] Ừ chứ không phải lại trước vợ ở trang
[00:40:07] nào nó sẽ ghi Cookie vào đâu có vài
[00:40:10] trang nó kiểu có ngoài xanh nó ghi là
[00:40:20] a và và cái Xin thí sinh hôm trước tội
[00:40:22] nhấn mạnh đi nhà mạng lại Thứ nhất là nó
[00:40:25] lưu lại sự sợ vợ nó không ạ Tại sao bởi
[00:40:27] vì a thằng cu kia nó ngược lại họ sẽ lưu
[00:40:31] lại trên lên cryin máy khách Hà Đông ạ
[00:40:35] và như tôi không cho tôi cũng có nói đó
[00:40:37] là khi mà mày ông Lưu Xuân Mãn chất là
[00:40:39] nó lưu lại trong Cookie trên máy ông
[00:40:43] để mà để mở dùng cái khi mà truy cập vào
[00:40:45] thì cứ ghi sẽ được gửi lên rồi mà sắp
[00:40:48] nhận cái sĩ Trần kia đều ngoạn nhưng mà
[00:40:51] cái key này nó lại được mã hóa một cách
[00:40:53] tự động nên thành ra ông khó mà ông sửa
[00:40:55] được nó để đổi thành sân của thằng khác
[00:40:57] à
[00:41:01] A và season này nó sẽ bởi vì nó lưu lại
[00:41:04] trên máy chủ khó sửa tay béo để xem qua
[00:41:06] cái này Cookie được lưu trên trình duyệt
[00:41:09] người dùng này sẽ dần không được lưu nó
[00:41:11] lưu lại trên server đó ông ạ
[00:41:14] oke có thể dễ dàng thay đổi bởi vì nó
[00:41:16] lừa trên mái nhà dụng nó thì ở file tex
[00:41:19] thôi nó fytech nghe mấy ông mở lên Nếu
[00:41:21] không sửa được con cái này thì nó không
[00:41:24] dễ sửa vì nó lưu trên server rồi
[00:41:30] ở đây và Cookie nó thường thường là
[00:41:32] nghe thưởng thức ca ít khi hết hạn lắm
[00:41:34] thường là đôi khi có người lại có kia
[00:41:36] thành vĩnh viễn cơ ngày ăn trẻ nhỏ ít
[00:41:39] khi được xóa Hoàn season thì nó lại giữa
[00:41:41] ngắn đôi khi ông Tắt trình duyệt ông
[00:41:43] ngắt kết nối cái thằng server sẽ chấm
[00:41:45] dứt luôn để sơ sinh sản của ông Khi mà
[00:41:48] Ông nhắn kết nuôi nó bé tùy từng vài
[00:41:49] trang
[00:41:52] như tôi đã nói thẳng ra là mấy ông bạn ạ
[00:41:55] Ừ anh điêu thế Bây giờ em tắt hẳn
[00:41:58] Facebook rồi Sao em ở lại như này anh
[00:42:00] thấy lại truy cập vào không cần đăng
[00:42:03] nhập nóng ạ Thực ra bản chất ở đây nó đã
[00:42:05] kết thúc thí sinh của ông rồi nó kết
[00:42:07] thúc season rồi nhé Chẳng qua nó dùng
[00:42:09] Cookie cũ của ông vẫn còn hiệu lực để mà
[00:42:12] tạo phiên đăng nhập mới cho ông Liên
[00:42:14] hàng ra làm mấy ông thấy à Nếu không cần
[00:42:16] phải đăng nhập lại thực ra bản chất là
[00:42:19] nó đã dùng Cookie để mà đăng nhập lại
[00:42:21] cho ông rồi nên là hôm nay tôi sẽ dạy
[00:42:23] mấy ông điều đấy nếu không sẽ làm tình
[00:42:25] năng mà tính năng khi mà đăng nhập vào
[00:42:29] nó sẽ có nút là nút ghi nhớ tôi được
[00:42:31] Nhạn các bạn biết cái nút để không ạ
[00:42:34] I say in nhiều hôm trước tôi biết xanh
[00:42:43] à à
[00:42:47] Ừ thì ở đây sẽ có cái nút à
[00:42:50] à cậu ghi nhớ đăng nhập không ạ bấm vào
[00:42:54] mình sẽ đây là ở kiểu các bạn khi vào
[00:42:57] lại đăng nhập vào luôn không ạ ạ
[00:43:00] em không có key dài nhất không phải 135
[00:43:02] lậu nó thì vĩnh viễn đấy nó sẽ không
[00:43:09] ý là nốt thêm cảnh nữa này
[00:43:11] Ừ cái cái này cái thứ ở bên này không có
[00:43:15] đây đó là Cúc y phù hợp với lưu lại
[00:43:16] những thông tin giải hạn Không nhẹ cả
[00:43:18] không nhận cả một vì sao Bởi vì anh mà
[00:43:22] lưu lại trên máy khách Hà nên là một Nó
[00:43:24] ông những cái nhạy cảm quá giả sự như
[00:43:26] cái đăng nhập chuẩn bị tôi sẽ làm thì
[00:43:33] 100 kiểu sửa nó để mà đăng nhập vào tài
[00:43:36] khoản người khác tí rồi sẽ phải là vụ
[00:43:36] đấy
[00:43:39] A và lưu lại những thông tin điện hình
[00:43:41] dạng giống như ông trình sửa cái gì đó
[00:43:44] thường là chỉnh sửa về à
[00:43:52] ở cây Trang Leo này không nên thầy Tôi
[00:43:55] đang để nó là nền tối đúng không ông để
[00:43:59] nó là niềm tối Tất cả chỉ là tôi không
[00:44:01] thể đăng nhập vào cái trang web này đúng
[00:44:10] Ý anh nói với anh nhìn tuổi này
[00:44:13] vợ yêu nhỉ Thế giờ nó vẫn ăn cốc kỳ thôi
[00:44:14] vậy
[00:44:16] khi bật đèn sáng nhé
[00:44:19] hai cây đèn sáng ấy
[00:44:21] ý là không không Thằng này mặc định Nam
[00:44:25] để tối rồi đấy mẹ Mẹ tôi từ đội để đây
[00:44:36] chú chó mặc mặc định cái này lên tối Ok
[00:44:39] mày Ông thấy nhá thời đó là nền sàn đúng
[00:44:39] không
[00:44:42] thứ Hai lên tối đúng không Tại sao lại
[00:44:45] có điều này sẽ sẽ xảy ra khi mà tôi tải
[00:44:47] lại sang thì nó vẫn là nền tối không
[00:44:50] phải lý giá mọi việc thằng thằng này nó
[00:44:54] không yêu cầu tôi đăng nhập ừ nóng và nó
[00:44:56] lưu lại cái việc thay đổi cái cái giao
[00:44:59] diện của tôi mà trong Cookie nên ăn hàng
[00:45:02] ra khi mà tôi vào bằng ẩn danh nó không
[00:45:05] lấy được Coca của tôi nên nó lấy lại mặc
[00:45:08] định còn nếu mà Bây giờ tôi vào lại thời
[00:45:10] trang này tắt đi mở lại như này thì mới
[00:45:12] Ông thấy nó vẫn giao diện sáng bởi vì nó
[00:45:15] lấy Cookie của tôi đấy một trong những
[00:45:17] cái đơn giản đó làm gì ạ mày ông đôi khi
[00:45:19] không cần lại lưu cái gì đó lên con nó
[00:45:21] nhập gì cả mà ông Chị lưu lại cấu hình
[00:45:23] người dùng thôi cũng là một cái người
[00:45:27] dùng chương trình Cái gì đó mà và có thể
[00:45:30] ông lưu lại giỏ hàng của người dùng Ông
[00:45:32] thấy thật ra có nhiều cái kiểu lựa giò
[00:45:35] hàng cũng qua cũng kia được đón chị rồi
[00:45:37] ông vào một trang nào đó không đặt các
[00:45:39] sản phẩm sản phẩm đó ngoạn cho ông ông
[00:45:42] đã ông đâu Yêu cầu phải đăng nhập mà
[00:45:44] mông vẫn làm được cái được thêm giỏ hàng
[00:45:47] không ạ sau đó thì ông tự Nhưng chán rồi
[00:45:48] ông
[00:45:51] Ừ ông tắt Sư Cái trang web phải đi sau
[00:45:53] đó vài ngày sau ông lại nhớ lại trang
[00:45:55] web để ông vào lại ông thấy rõ hàng của
[00:45:58] ông vẫn còn bản chất là do nó là dùng
[00:46:01] Cốc đi đấy có thể nó sẽ dùng
[00:46:04] localstorage nữa cũng là một cách nhưng
[00:46:06] mà về cơ bản thì hai thằng nó giống nhau
[00:46:08] nó lưu lại trên máy người dùng và thông
[00:46:10] tin đấy không phải thông tin ngay cả
[00:46:12] thông tin thấy hoàn toàn người dùng sửa
[00:46:15] cũng được không sao cả đều ạ Nó không
[00:46:17] phải thông tin nhạy cảm còn trong sân
[00:46:19] Thì nó sẽ khác các bạn phải phân biệt kỳ
[00:46:22] diệu này season nó sẽ lưu lại không tin
[00:46:26] ai cả Thì thì những cái còn đăng nhập
[00:46:31] A và cuối cùng mình nói nốt thêm cái nữa
[00:46:34] nhanh này nó cách thưa cách thì mình đã
[00:46:36] từng nói qua việc là hồi mà mình chỉnh
[00:46:40] sửa CF thì giao diện đôi khi không Lập
[00:46:41] tức thay đổi vì trình duyệt đôi khi nó
[00:46:45] tự động như lại cách và thận chế ở lập
[00:46:46] trình viên mình có thể
[00:46:48] sf Cái trình duyệt lưu lại cách nhiều
[00:46:51] cái để cho trang web nó tải nhanh hơn
[00:46:55] nhược điểm là khi mà Mấy ông trình sửa
[00:46:58] giao diện rồi thì đôi khi giao diện cũ
[00:47:00] vẫn còn hiển thị xe máy người dùng bởi
[00:47:02] vì cái đấy nó lưu lại trên cách của
[00:47:04] trình duyệt người dùng cái đấy khó mà ép
[00:47:08] người dùng khó mà ép người dùng kiểu xóa
[00:47:10] được cái cáp người dùng phải tự thủ thủ
[00:47:13] công làm điều đấy chứ mình không thể bị
[00:47:15] không thể hiểu dạng là
[00:47:16] những
[00:47:18] kiểu cắm thiệp được và cách của trình
[00:47:21] duyệt người dùng nên là hồi trước phải
[00:47:24] có chơi trò là hồi nãy tôi nhớ là cái
[00:47:26] trinh cái cái cái giao diện các trang
[00:47:29] web để nó bị lỗi lỗ rất nặng luôn nên
[00:47:31] thành ra là kiểu mà lỡ lưu cách cài rồi
[00:47:34] nên là phải đổi cái tên miền điều hướng
[00:47:38] tên miền sang hẳn để kiểu ví dụ là phim
[00:47:41] mới Z chẳng ngại thương thế để mà để mà
[00:47:45] không lưu cách của cái giao diện nữa mấy
[00:47:47] ông hình dung không Thế à thế là cũng
[00:47:49] hơi bị nhược điểm vụ đấy nghĩa ông sửa
[00:47:51] xong đôi khi nó không đồng bộ
[00:47:53] anh Bởi vì nó có căn cứ cách mà đồng
[00:47:56] tiền hình dạng dạng như là thế giới di
[00:47:58] động đi
[00:48:01] cái gì đập nát ngang
[00:48:04] hai tay nếu không thể hai giây rồi đúng
[00:48:07] không ạ tải lại này 1,3 giây này Tại lại
[00:48:11] nữa này 1,3 1,1 giây này Tại nữa 1,1 đây
[00:48:13] Tại sao từ hai giây mà xuống hàng như
[00:48:16] thế chỉ với đơn giản vì nó đã lưu cách
[00:48:19] lại khá nhiều địa hình lưu cách lại để
[00:48:21] hình cái Tháng 3 này hai cái thứ
[00:48:25] đi hoa cà hoa còn lưu lại sẵn mà cái CS
[00:48:27] mở ra Switch để mà khi mà tải lại trang
[00:48:31] gần như là gần như là chị thư gan là cái
[00:48:33] những cái mọi ý thay đổi ví dụ như là
[00:48:35] cái ba nâu này cùng hai ba ngày nó mới
[00:48:38] hay đổ một phát thì nó lưu lại cách
[00:48:46] Ừ đúng rồi Mày không có thể sửa lại
[00:48:49] đường dẫn của xe hết thì nó sẽ sẽ xóa
[00:48:52] kết đi thôi Nhưng mà đấy là ông sửa sẽ
[00:48:56] còn đang nói là cách cả hmg nữa thì thì
[00:48:58] mấy ông sửa kiểu gì thì cũng chỉ có thể
[00:49:00] là kẹo điều hướng sang trang web khác
[00:49:07] Ừ ok Nói chung là hơi lan man một tí bởi
[00:49:09] vì cốt Hôm nay thực ra rất ngắn thôi thử
[00:49:11] cho mấy ông xem có cô trong máy Nhắn
[00:49:14] cướp tôi phải là nam không mấy ông ấy
[00:49:18] kiểu hôm nay thế thôi à đây tôi sẽ cho
[00:49:20] ông Ví dụ nhé cơ mình sẽ làm tính năng
[00:49:22] đang đăng đăng nhập không ạ Và khi nhờ
[00:49:23] đăng nhập
[00:49:26] khi đăng nhập với ông trước làm tôi em
[00:49:34] thì mình sẽ có cái nút
[00:49:39] ghi nhờ đăng nhập
[00:49:52] mà thường mình sẽ cho cái lên như thế
[00:49:54] này ghi nhớ nạ
[00:49:58] phó Bây giờ xin phép mình đổi nó thành
[00:50:00] mét ghét thì mấy ông dễ hình dung hơn về
[00:50:03] cái này đã Đợi thì đợi thì tôi sẽ tạm
[00:50:09] bên A short size 18 ẩn cái đoạn này đi
[00:50:11] đã Để tôi cho ông xem về cái việc khi nó
[00:50:14] đẩy lên web thì nó sẽ như nào là sử tôi
[00:50:16] không Điền gì đây nhá tích và ghi nhớ
[00:50:18] Đăng nhập Thơ nó nghiệp này nếu không sẽ
[00:50:22] thấy ở đây không điện gì Ok nó trống ghi
[00:50:24] nhớ sẽ ngon không hiểu là cái gì nhưng
[00:50:26] nó ghi nhớ nó sẽ ăn ngon rồi nhá Thế là
[00:50:29] tôi thử tắt cái này đi cẩn đăng nhập thì
[00:50:30] ông ấy Ông thấy là nó không hề Truyền Kỳ
[00:50:37] à à
[00:50:41] Ừ nó chỉ lưu cách xét
[00:50:47] vì nó thực ra nó vẫn có thể lưu cách
[00:50:50] được hml theo kiểu là mình nhớ mình mình
[00:50:52] nhớ ở như thế thì công ty mình đang áp
[00:50:54] dụng cái kiểu lưu kết HTML mà chẳng qua
[00:50:57] mình không không nhớ cách làm như là
[00:50:59] thôi Hình như có hoặc các công ty mình
[00:51:03] điều kể trên server in nó ra bởi vì công
[00:51:07] ty mình đang dùng mà da Swift dùng nắp
[00:51:10] loa CS để mà sinh ra hát lời sau đó đi
[00:51:20] Anh không dùng tiếng Anh nữa à Ok vậy
[00:51:22] Giống như nhanh cho chứng nhiệt nhưng mà
[00:51:27] Mấy ông thôi quay lại đây một tí đi
[00:51:31] Anh ấy thì cái á khi cây email và
[00:51:33] password này Đúng không mấy ông thấy rõ
[00:51:35] ra là khi mà tích tích vào thì có để em
[00:51:37] hai chị không thích thì nó không đẩy
[00:51:39] luôn luôn nhe Cái đoạn này nó hơi khác
[00:51:42] một tí Mình sẽ phải kiểm tra nó có tồn
[00:51:44] tại thôi là được có tồn tại thôi làm chị
[00:51:47] đã có lưu không quan tâm với giá trị của
[00:51:49] nó nữa còn nếu mà không đẩy lên thì rõ
[00:51:51] không lưu nóng ạ tôi để nói tiếng Anh
[00:51:55] nhá Ok cảm ơn bạn nhé mình cũng nên thế
[00:51:57] mình nên kiểu một thống nhất là toàn bộ
[00:51:59] tiếng anh hay tưởng bộ tiếng Việt đừng
[00:52:01] có lừa anh ấy việc em như thế là cốt tủy
[00:52:04] bây giờ động não
[00:52:08] Anh An ninh đội nói như này à Ê mày tải
[00:52:10] lại cho em chưa chắc lại đúng ạ bây giờ
[00:52:14] xử mới điện nữa bình thường 5 hacker
[00:52:17] một chút Mật khẩu là cái gì nhỉ
[00:52:19] Ừ thôi tôi tự hack chính tôi đi nó sẽ để
[00:52:26] a cho một bóng một như này sẽ không sao
[00:52:28] như thế này không cần điền Email cũng
[00:52:32] được sẽ vào tài khoản của bất kỳ lên một
[00:52:34] đấy tôi tự hay chính tôi nhé
[00:52:37] thì nó sẽ ăn ghi nhớ không ạ
[00:52:39] khi đăng nhập này
[00:52:42] ở đó thì bạn chất ở bên này sẽ vẫn giống
[00:52:47] như hôm trước nha lần này mình sẽ là kèm
[00:52:49] theo cái cái nhớ nhưng mà mình sẽ làm đi
[00:52:54] Sao mình sẽ ít reset lại còn đều có
[00:53:00] đều có remember không ạ member có ý Nhớ
[00:53:04] thì mình giả sử mình cho remember
[00:53:08] bạn Chu đi tức à đúng đi eo thì bờ bằng
[00:53:10] phone đi
[00:53:16] dự báo trước mà nghỉ nên bà không biết
[00:53:18] là hôm trước hết khủng như thế nào ghê
[00:53:21] lắm đấy à
[00:53:23] Em nói trước bây giờ Bà Xã Đàn Đăng nhập
[00:53:25] thành công rồi hack rồi cái chị sẽ tao
[00:53:28] được không ạ sau đó mình sẽ có season
[00:53:31] start này mình sẽ lưu lại
[00:53:33] à à
[00:53:36] vì mình lưu lại trong season các thứ thứ
[00:53:44] mình làm lại cái vụ hôm trước nhé đó là
[00:53:47] mình sẽ lấy cái người đầu tiên mình đăng
[00:53:50] nhập thành công không ạ sau đó lưu lại
[00:53:54] ID người dùng lưu lại tên người dùng nữa
[00:53:57] và khi mà đăng nhập thành công và kèm
[00:54:00] theo có ghi nhớ từng nghĩ sẽ lại ít em
[00:54:04] bờ nghĩa là nếu nếu có ghi nhớ phải
[00:54:07] không ạ Mình sẽ có setcookie
[00:54:10] anh sex kỳ Tôi không nhớ của Pháp vào
[00:54:15] năm đâu Cho tôi xem nhé Sẽ có Kỳ P
[00:54:19] a A nó viết liền à Mà sao sẽ có kỳ okay
[00:54:24] đây cú pháp xe cũ Kia của nó sẽ mạnh tí
[00:54:26] Anh tên của Kia này giá trị quốc kia
[00:54:29] thời gian nếu ông sẽ thấy ở đây nó sẽ có
[00:54:32] thời gian ở đây nó lại mình cứ đơn giản
[00:54:34] thôi nếu mà ông không nhớ tắm
[00:54:38] 86.400 là số dây một ngày ông mấy
[00:54:44] 60 X60 x240 ạ xong nhấn 30 ngày thì sẽ
[00:54:46] một tháng không ạ Giờ cái quan trọng vào
[00:54:49] đây mình uống nhỉ Có thêm cái sao mày
[00:54:51] nón trước than này để làm gì tha mày là
[00:54:54] lấy thời gian số dân hiện đại
[00:54:57] Tại sao học bởi quy chế của Hàn Quốc kỳ
[00:55:00] này nhá Cái này là tên của cái Cookie mà
[00:55:03] mày ông sẽ đọc này Thứ hai là giá trị cũ
[00:55:07] kỹ này Thứ ba là cái cái thôi jean kaki
[00:55:09] sẽ hết hạn người ông phải xét thời gian
[00:55:12] cũng có khi hết hạn nhé thì thường là
[00:55:14] kiểu lưu ghi nhổ hết thường anh chỉ
[00:55:16] trong vòng hai tháng mà một tháng thôi
[00:55:19] Thì mấy ông sẽ nghĩ là chỉ đoạn này đủ
[00:55:21] nhưng mà không thì ra là có khi nó sẽ
[00:55:24] phải xét theo cả là tính từ thời điểm Và
[00:55:26] cho đến thời điểm tương lai nên thành
[00:55:27] nhà phải thêm thời gian hiện tại nữa
[00:55:29] được cộng thêm thời gian tương lai thì
[00:55:31] ra là như thế này cái đoạn như thế này
[00:55:34] thì ông không cầm đâu Ông bỏ đi đấy thì
[00:55:36] cú phát ở đây nó sẽ sự lưu gọi không Khi
[00:55:41] mà là đưa member chẳng hạn thế sau đó đi
[00:55:43] ông sẽ lưu lại gì trong về Quan trọng là
[00:55:46] bây giờ ông sẽ lưu lại gì để mà hiểu
[00:55:49] được là tí mà thằng nào có Cookie này
[00:55:52] thì mình sẽ đăng nhập được vào đông ạ
[00:55:55] Ừ cái quan trọng ở đây thường là hồi
[00:55:56] trước tôi dậy cho sinh viên đơn giản là
[00:55:58] tôi lưu lại mã người dùng với sóng này
[00:56:01] tôi thử lưu lại mã dùng nhé xong một tí
[00:56:03] mấy ông sẽ thấy là nó có thể nguy hiểm
[00:56:06] nha tham này
[00:56:10] cộng với giờ sự nếu không rút toán đi 60
[00:56:12] X60 nhân 24
[00:56:15] X30 thì sẽ ra 1 tháng đúng không ạ Cái
[00:56:19] xong thế chả bạn ạ
[00:56:21] ô tô tại trai nha
[00:56:24] khi đăng nhập thành công vào nhấn vào nó
[00:56:26] không thể cả diện ấy DJ cukiu mày không
[00:56:29] xem Cookie nhé ở đó thì mới Ông thấy có
[00:56:32] biến đương m lưu lại mã vòng 1 idea một
[00:56:35] đông lạnh Ừ nó như này đăng nhập thành
[00:56:37] công không ạ
[00:56:41] à Mấy giờ thì giả sử là bây giờ khi mà
[00:56:44] tôi và lại cái răng sai này tôi vào lại
[00:56:46] trang sai này
[00:56:49] FPT này
[00:56:51] Chị Thơ ca khi mà vào lại sang chai này
[00:56:54] mà tôi đã đăng nhập rồi thực ra là không
[00:56:56] cần nên hiện sĩ là cái sao nhập nữa mà
[00:56:58] phải vào thẳng luôn cái tài khoản của
[00:57:01] tôi không ạ tất làm chị đã sao và đầu
[00:57:04] tiên là bây giờ tôi kiểm tra là ít thôi
[00:57:06] mờ season start Nếu mà có xin thì tôi sẽ
[00:57:08] phải điều hướng với cái Trang chăng
[00:57:14] người dùng luôn sẽ là start này và riêng
[00:57:16] cái vụ đấy thì nên để trên cùng như hơn
[00:57:18] bởi vì a điều hướng ở luôn lệ trên cùng
[00:57:21] đều hướng nó sẽ bị lỗi nếu mà các bạn in
[00:57:23] ra bất kỳ giá trị như thế này các bạn
[00:57:25] không dùng header được nghe các bạn sẽ
[00:57:27] có đầy nó trên cùng như thế này thì
[00:57:32] start ở trên cung xong rồi Ít em reset
[00:57:36] đô lecithin ID ạ Nếu có thì các bạn sẽ
[00:57:38] phải điều hướng sang chàng người dùng
[00:57:42] luôn nha Ngu dơ
[00:57:43] Champagne
[00:57:47] thôi axit ở đây và chắc này à
[00:57:49] Hôm nay anh có bạn sẽ được hưởng sao cho
[00:57:51] người dùng luôn nhớ bây giờ ạ đề năng
[00:57:53] suất các bạn nhớ vụ đăng xuất hôm trước
[00:57:55] đó em chỉ là
[00:57:59] nó nó sẽ đâu
[00:58:02] Em out sao đây thì nó sẽ xóa xin đi đúng
[00:58:04] không ạ Khả năng suất này sẽ xóa đi này
[00:58:08] tôi vào đăng nhập khi mấy ông thấy ạ lại
[00:58:10] quay trở lại trang này nhưng mà rõ ràng
[00:58:13] là mấy ông nhớ vụ bảo tôi vừa lưu lại
[00:58:16] trong quốc kỳ tất cả có remember rồi cái
[00:58:18] làm chỉ là nếu có cốc kia rồi cái mình
[00:58:20] sẽ phải đăng nhập với tư cách của người
[00:58:23] này rồi đua nói đúng không ạ thì mình sẽ
[00:58:25] làm như thế nào
[00:58:29] ở đây mình sẽ kiểm tra đây If reset
[00:58:32] thì mình sẽ lấy Cookie ở ra thôi sẽ đôla
[00:58:37] coky chí này là sự quốc kỳ vừa nãy mình
[00:58:41] remember không ạ Nhìn này nếu mà có nhớ
[00:58:44] có nếu có tồn tại đó ông ạ thì mình sẽ
[00:58:47] làm gì mình sẽ vừa rồi là mình lưu lại
[00:58:49] đây
[00:58:53] đi tắm tí nhé Có rồi Mình lưu lại ID của
[00:58:55] người dùng trong cái cô kia nên mình chỉ
[00:58:57] lấy lại ID người dùng đấy lại thông tin
[00:59:00] của người dùng thông qua đi thôi mình sẽ
[00:59:04] có cái nổi cơ sở liệu này
[00:59:23] có ai Tôi sẽ đặt ID bằng đôla Coffee tạ
[00:59:26] từ bờ này
[00:59:29] các tổ lại đi này à
[00:59:49] Turn on high PR mình sẽ phải à
[00:59:52] để lưu lại trong section như cũ ở Như
[00:59:58] thế này có ích tại hay đi đấy và nêm
[01:00:03] mày không có thể đẩy cái này nên làm
[01:00:04] trước cái này cũng được
[01:00:06] bởi vì
[01:00:09] à vì tạo xong nữa mới ông có thể là kiểm
[01:00:11] tra mà luôn sau đó điều hướng về như thế
[01:00:14] này khá tiện ở như thế này nếu không sẽ
[01:00:16] thấy lập tức đăng nhập vào thông qua
[01:00:20] thông thông qua là kiểu có cục có Cookie
[01:00:22] rồi nó sẽ đăng nhập hộ luôn các bạn và
[01:00:25] năng suất ra à Bạn đăng nhập vào lại lập
[01:00:26] tức là nó sẽ tăng lại sang bên người
[01:00:30] dùng luôn Nhưng mà như tôi đã nói thế
[01:00:32] thì ra thấy làm xong cái cốc kỳ đấy
[01:00:35] Ẩm Thực ra là chị có hai thứ mình cần
[01:00:37] lại sửa đây thứ nhất là trứng và đăng
[01:00:39] xuất ra rồi thực ra bản chất là nhiều
[01:00:41] tra năng suất ra nó sẽ xóa hút của ông
[01:00:42] chứ không chuyện Ông đăng xuất ra rồi
[01:00:44] ông là đăng nhập Ông ấy không cần đăng
[01:00:47] nhập bạn nữa Thế hơi sai người cứ bắt
[01:00:48] người dùng vì trải nghiệm người dùng
[01:00:50] người ta tư duy đó là đăng xuất đã rồi
[01:00:54] những làm chị ạ phải đăng nhập lại thì
[01:00:56] mới được đăng mới mới được chứ không
[01:00:59] chịu đăng xuất ra rồi Ra ngồi
[01:01:01] oke cũng vẫn còn hiệu lực thì không cần
[01:01:04] đăng nhập bởi vì Giả sử dạng nhựa Ông ra
[01:01:07] ông ra nét hoang dùng mày cá nhân của
[01:01:09] ông thôi ông cho ai đó dùng máy của ông
[01:01:12] ông sẽ thường Ông nghĩ à Tôi đang xuất
[01:01:14] ra rồi để mà bạn sẽ thằng kia không phải
[01:01:16] vào máy tôi nóng sẽ không vào được tài
[01:01:19] khoản của tôi đúng ạ bây giờ vào sử
[01:01:21] trang đăng nhập đăng nhập lại như như cũ
[01:01:24] thì được cả toàn quá đúng không ạ Thế
[01:01:27] nên là ạ bây giờ đăng xuất phải xóa quốc
[01:01:30] kỳ là một lần thứ 2 đó là cũ kỹ này như
[01:01:32] tôi đã nói nó rất là không ổn theo kiểu
[01:01:36] là nó lưu lại theo mã người dùng cái này
[01:01:38] thì ra không tốt Bởi vì bây giờ tôi đổi
[01:01:40] mã bằng hai ta sẽ đăng nhập được vào tài
[01:01:42] khoản cái khác được ngọn Em thấy không
[01:01:45] một ngờ đầu tiên tôi xử lý mới năng suất
[01:01:46] lại nhé
[01:01:49] Ừ mình đang xuất này thì mình cây thước
[01:01:51] ra cái xóa Cookie Thật ra cũng dùng
[01:01:53] Chính cái hàm setcookie thì mà xóa thôi
[01:01:57] chị đơn giản như thế này nó sẽ là mình
[01:01:59] sẽ đặt cho nó một cái giá trị có thể
[01:02:02] luôn làm chị ở không không không có
[01:02:05] không có hoặc à à Ông đặt ra giá trị gì
[01:02:07] cũng được quan trọng Miễn là ông sẽ cho
[01:02:09] thời gian và thời gian trong quá khứ
[01:02:11] thận chứ thời gian nó là trừ một ngày
[01:02:13] chắc chắn nó nó là ở thời gian là quá
[01:02:17] khứ tại thử năng suất này và đăng nhập
[01:02:20] lại này có thêm bé Ông thấy à nó sẽ bị
[01:02:22] xóa cô kia ở đây là nó yêu cầu mình đăng
[01:02:25] nhập lại nóng ạ Đây Ok không còn nữa
[01:02:29] cái sân này vẫn còn vì cái season này nó
[01:02:33] hơi bị dị mà ví khi mà ông mở Sistar nó
[01:02:35] luôn muốn tạo một cái phiên chẳng qua
[01:02:36] cái phia này nó không hiệu lực để ông
[01:02:38] đăng nhập thôi chứ nó luôn tạo ông cái
[01:02:40] khuyên rồi à
[01:02:43] ở đây lấy cái vừa rồi chị Ngạn và ý ông
[01:02:46] ở dùng cái hạt phim sex cu kia tôi thì
[01:02:49] tôi chưa thử về đây đâu
[01:02:53] Ừ Ừ để tôi thử phát nhạc được đấy đối
[01:02:54] thủ nhé
[01:02:56] a Mother season mình cứ đăng nhập đúng
[01:02:58] không còn nhập từ trước
[01:03:00] à à
[01:03:05] này
[01:03:10] lưu lại sẵn đăng nhập này Ok Đăng nhập
[01:03:12] thành công nó không ạ Bây giờ sang bên
[01:03:13] ngu rồi này
[01:03:16] một giờ chuyển VP Xin chào bạn lo lắng
[01:03:19] giờ đang xuất thì thay vì cái này tôi ăn
[01:03:22] xét đúng ạ thì mới ông dùng ăn xét tôi
[01:03:26] tôi đang đoán là có thể được có dậy được
[01:03:30] à À không không không có khi không được
[01:03:33] có khi không được Tại sao vì cái hàn lấy
[01:03:35] Cookie này lấy từ trên trình duyệt người
[01:03:37] dùng về nhưng mà ham ăn xét lại như như
[01:03:40] lý thuyết như lý thuyết thì làm ăn xét
[01:03:42] này là xóa
[01:03:45] anh xóa giá trị đấy ở trên server chứ
[01:03:47] không phải xóa ở trên máy người dùng
[01:03:51] thôi Tôi tôi thử pháp không được Tôi
[01:03:56] ở Iceland
[01:03:58] khi đó mẹ không theo
[01:04:02] mình đoán chuẩn phết đó mày không phải
[01:04:05] không đó là ăn xét lại tất cả nó xóa xóa
[01:04:09] cái xóa cái đấy chứ giờ xóa cái vùng nhớ
[01:04:13] nếu mà các bạn học bên máy tính rồi thì
[01:04:16] cái này bản chất là biến bất kỳ mạng gì
[01:04:20] đó nó lưu lại nó lưu lại bộ nhớ ở trên
[01:04:25] gọi là địa chỉ vùng nhớ ở trên trên con
[01:04:28] server để không ạ Cái tên biến bản chất
[01:04:31] nó địa chỉ địa chỉ vùng nhớ thì cái này
[01:04:33] là xóa trên server để không ạ Nó sẽ cho
[01:04:36] đến cái địa chỉ đấy nó xóa con cái
[01:04:38] Cookie này lưu trên máy khách hàng nhưng
[01:04:40] để khám ăn xét mà nó không nghĩa gì cả
[01:04:41] đúng
[01:04:47] thế
[01:04:49] nhưng đại khái Thế nếu không thấy là rõ
[01:04:53] ràng buộc rồi cô kỳ tôi Nó là một tôi
[01:04:56] đổi nó thành hai chị ba bốn gì đó thì nó
[01:04:58] sẽ là kiểu nhảy sang tài khoản với khác
[01:05:02] đúng ạ Tôi thử vào
[01:05:05] xem tại tài khoản ông nào có đổi tên
[01:05:08] khác bởi tôi nhớ ông nặng tên là Long vì
[01:05:10] vậy Liên bây là đổi tên để mẹ cũng không
[01:05:21] Ừ nếu kỹ năng bạn đấy cả hai ông kia đậu
[01:05:22] xanh
[01:05:25] Anh nghe rồi tranh thủ tán gái trong
[01:05:36] à
[01:05:41] À đây Đúng rồi không sao tên ông đầu ở
[01:05:43] Long nó mày không nhớ tên Đông đầu long
[01:05:45] nhá ông hay ông 34 thì đều Long hacker
[01:05:48] đúng không ạ Đây tôi đổi mã thành kiểu 2
[01:05:52] hoặc 3 gió sẽ phải đội hình 52 cơm tôi
[01:05:55] tôi lỡ ấn clear rồi ly oke bay luôn cốc
[01:05:58] kỳ thôi rồi à không khó vẫn còn ok rồi
[01:06:01] nó hay nhá nãy anh hai rồi Tôi nhớ Ấn gì
[01:06:03] nhá những cái này
[01:06:06] Ừ hình như thế
[01:06:09] vụ tai nạn tra xem đúng mà
[01:06:11] em toàn em nhỉ
[01:06:14] Ừ Ok hai rồi hai vợ ngon Tôi đã đăng
[01:06:18] nhập đây đó mấy ông thấy tôi vào sử nick
[01:06:21] người khác rồi thế không ổn không ạ
[01:06:24] Ô thế không buồn đâu mạnh bởi vì em nếu
[01:06:27] mà Mấy ông lưu lại mã của người dùng mà
[01:06:29] trong kia tôi đổi nó lại mã của người
[01:06:31] khác thì ra là đăng nhập vào người khác
[01:06:32] nóng ạ Thế bây giờ mình làm như thế nào
[01:06:35] thì giờ mình sẽ phải có cơ chế đó là
[01:06:38] mình sẽ phải sinh ra cái đoạn cái đoạn
[01:06:41] đoạn Mã gì đó mà người dùng không đoán
[01:06:44] được nó gọi là có kèn đấy ạ nghĩa người
[01:06:47] dùng không đoán được và phải mỗi người
[01:06:48] dùng được nhưng phải có một cái Token
[01:06:50] khác nhau đúng không ạ
[01:06:52] ở mỗi người dùng phải to cao khác nhau
[01:06:54] không thể dùng một tóc em nó tất cả mọi
[01:06:55] người dùng được nó không ạ thì cái việc
[01:06:57] mỗi người dùng một thói qen đó chính là
[01:07:00] sinh ra ở trong chính cái bảng này mình
[01:07:03] sẽ tạo mình sẽ ở đây mình sẽ thêm một
[01:07:05] cột Nữa của Token sau đó hai mình sẽ lưu
[01:07:17] Ừ nhưng mà đương nhiên là bây giờ thì ra
[01:07:19] có nhược điểm là bây giờ là nếu không
[01:07:21] thấy là tất cả người dùng của tôi đang
[01:07:22] đều à
[01:07:25] Đang đều không có to kèn không ạ
[01:07:28] em nghe Bây giờ nếu mà nhập vào như này
[01:07:30] nó sẽ báo lỗi
[01:07:33] mày ông sẽ thấy báo lỗi bởi vì anh không
[01:07:36] có giá trị 1 cố định ở đây vẫn được hả
[01:07:38] Như ngoài thể giá trị nó biến giá trị rõ
[01:07:41] mất rồi em mấy ông xe thì nó không được
[01:07:44] nung như nó Dạ chị dẫn rồi lại chậm
[01:07:46] thường nó sẽ phải báo lỗi ở đây cơ bởi
[01:07:48] vì nó không được phép Mun chẳng qua đây
[01:07:50] đang trôi rõ rồi Thì bây giờ mình sẽ
[01:07:53] nhập vạc và sự ở đây bạn Long này sẽ có
[01:07:57] tóc em đâu nha nếu không nên dùng nghĩa
[01:07:59] là khi mà Mấy ông đăng ký và nó phải
[01:08:03] xinh cho một cái tóc em rồi hoa à
[01:08:05] đó chính xác là không phải đăng ký mà
[01:08:07] khi mà ông Ấn vào cái nút
[01:08:11] nút ghi nhớ mật khẩu
[01:08:15] A ghi nhớ Đăng nhập đấy thì nó xinh A1
[01:08:17] ông cái đó Token ba mấy ông sẽ phải dùng
[01:08:18] cái tao Ken đấy thì mình không đăng nhập
[01:08:22] vào cái biểu tôi sẽ làm cái đấy luôn bạn
[01:08:23] kia hỏi phải cái Token full quyền của
[01:08:26] Titan giới hạn quyền không ạ Thì bây giờ
[01:08:29] mình đến cuối buổi thực là hôm nay mình
[01:08:31] cũng đang định nói anh cuối buổi mình sẽ
[01:08:33] xin phép nói về cái vụ phân quyền
[01:08:35] có ai
[01:08:39] Em à mình không đi đây ở đây có bài toán
[01:08:41] phân quyền ông ạ Đây bàn tròn phân quyền
[01:08:44] vấn đề môn của rất khó hiểu đây bởi vì
[01:08:46] hôm trước cũng có bạn nói về việc là do
[01:08:49] sự lại em có thêm nhiều loại người dùng
[01:08:51] mà mỗi người dùng có một quyển khác nhau
[01:08:54] thì em ghi thẳng ở trong code hả anh
[01:08:56] không Mình sẽ phải lưu lại trong B về
[01:08:58] sau mình còn dễ trình sửa nữa đã thì cái
[01:09:01] việc đấy là mình mình sẽ phải thiết kế
[01:09:03] đi tới bệnh đau tay như thế nào còn sẽ
[01:09:05] rất lạ rất là rắc rối
[01:09:08] anh nói chung là tí mình sẽ đề cập cho
[01:09:10] các bạn hết mấy bộ lấy hi vọng các bạn
[01:09:12] không đau đầu thôi còn mình rất là đau
[01:09:15] đầu mình mình dậy thì các bạn Mình phải
[01:09:17] cố nghĩ sao cho nó dễ nhất có thể các
[01:09:24] Ờ thì đầu tiên thì mới quay lại nha Bây
[01:09:26] giờ là mình đăng xuất ra rồi ok con nhờ
[01:09:28] cái copy vừa rồi nó hết hiệu lực đúng
[01:09:29] không ạ
[01:09:33] Mình sẽ lại ấn lại đăng nhập Ok lần này
[01:09:35] mình sẽ cần ghi nhớ khi nhớ đăng nhập và
[01:09:38] nó sẽ sinh ra một cái tóc em cho cái
[01:09:41] người dùng đấy và tóc em để sẽ lưu lại
[01:09:43] trong Cookie người dùng và
[01:09:46] Cookie đấy sẽ chỉ dùng để đăng nhập được
[01:09:48] vào tài khoản kia thôi mà Có khi đấy nó
[01:09:50] phải là một ngọn mã nó ngẫu nhiên không
[01:09:52] ạ
[01:09:59] ở đầu tiên là mình sẽ có mình sẽ lại
[01:10:02] lòng hacker đúng ạ thì là không quan
[01:10:04] trọng nữa tôi chỉ cần điền ngay chứ tao
[01:10:06] đăng nhập được rồi này ăn cái người đó
[01:10:11] nghiệp nhai thì là này mình ở đây mình à
[01:10:15] khi bị xử lý sao đi anh ở đây khi mà ghi
[01:10:17] nhớ này mình sẽ sinh ra một cái tóc em
[01:10:21] ok này thường là tao kem này nó sẽ là
[01:10:23] một cái chuỗi ngẫu nhiên nào đó thường
[01:10:26] là tôi sẽ chơi trò thêm mà
[01:10:32] thêm hát thêm kẹo Bon nó có mã hóa nó để
[01:10:35] mà cho như tôi đã nói lập trình viên vào
[01:10:39] xem cho kem người cũng khó mà nhớ và khó
[01:10:41] mà giả được chóc em cũng khách hàng lập
[01:10:43] trình viên và giả thói quen thấy Hà vào
[01:10:45] được tài khoản khách hàng rồi không ổn
[01:10:47] không ạ Cũng giống như mật khẩu ấy nóng
[01:10:49] ạ
[01:10:52] ý thì cái đoạn đấy thì thường là mẹ mấy
[01:10:56] ông sẽ có khá nhiều cách để mà lại có
[01:10:58] nhiều người dùng hạn thứ viện thôi thử
[01:11:03] tra thôi là đúng sự Trinh P là em ạ đang
[01:11:15] hôm nay nó sinh ra cái Hàn này cái Hà mà
[01:11:16] gì
[01:11:19] hả mày không mã hóa nào là chị đơn giản
[01:11:21] là tạo ra một cái
[01:11:25] một chuỗi ngẫu nhiên nào đó nhưng mà hàm
[01:11:26] này có thể
[01:11:29] a nay có thể thêm chủ để lắm chuyện nó
[01:11:31] sẽ chắc chắn thêm tôi tôi nhớ có hàng
[01:11:38] cũng được hàng này được gặp khó ai đoán
[01:11:42] Ừ
[01:11:47] cái này fix lần đầu để làm chị ạ cậu kéo
[01:11:49] án chị ở Đang đâu có thêm tính tố gì
[01:11:52] không nóng để sống thêm u giờ được cho
[01:11:54] bệnh chuyên nghiệp này em chu lại chưa
[01:11:56] chán là nó sẽ sinh ra một cái đoạn đằng
[01:11:59] sau thêm mấy cái cửa chấm chấm năm sau
[01:12:02] để nó khó đoán hơn nữa đó thì đây chúng
[01:12:03] ta có một cái các em rồi bây giờ tiếp
[01:12:07] theo chúng ta sẽ phải update để Ok Đấy
[01:12:11] và cho người dùng chị sẽ update customer
[01:12:13] xét
[01:12:19] ok bằng Token này à
[01:12:22] à À như thế Lúc đầu to kem của tôi phải
[01:12:25] là có thể luôn label mẹ ra lúc lúc đầu
[01:12:28] thì có thể chống chỉ có khi mà người
[01:12:30] dùng ấn vào ví nhờ đăng nhập thì mới
[01:12:33] điện cho Ken mà nó hợp lý hơn và thế này
[01:12:36] để tránh việc là khi mà Bây giờ tôi nợ
[01:12:38] tôi tôi chưa Bây giờ tôi phải sửa file
[01:12:40] đăng ký nữa bởi phan đăng ký rồi nó sẽ
[01:12:44] lỗi vì nó đã còn Token đâu ông ạ que
[01:12:47] đây có ai đi ông ạ Mình sẽ đây có ai đi
[01:12:51] này mình sẽ ai đi bằng đôla X2 đi đây đi
[01:12:55] cho rọ nó Ai sẽ ID này
[01:12:56] các
[01:12:59] bạn lại lại đi
[01:13:05] mà đoạn mạng thế Ai đi bằng hai đi này à
[01:13:06] Ê
[01:13:09] mày như này
[01:13:12] Sao Đỏ remember playing the
[01:13:15] Ripper ưu dượng được thì các bạn đặt ở
[01:13:17] đây sẽ lưu lại dạng to khe như thế này
[01:13:20] đó
[01:13:23] I felt mình sẽ
[01:13:25] a ghi nhớ đăng nhập
[01:13:28] Ừ ok Đăng nhập thành công các bạn sẽ
[01:13:30] thấy ra cái bờ đây là sinh ra một cái
[01:13:32] đoạn trỗ ngẫu nhiên như thế này đúng
[01:13:34] không ạ Và
[01:13:37] ở bên bây giờ mình quay lại bên đăng
[01:13:38] nhập nhé
[01:13:41] Mình đăng nhập này à
[01:13:44] ở bên đăng nhập rồi chắc chắn nó sẽ bị
[01:13:45] lỗi
[01:13:48] em bị lỗi lại sao bởi vì À đây xem dòng
[01:13:50] số 10 này
[01:13:54] Khi dòng thứ 10 ở đây ở đây nó đang báo
[01:13:57] lỗi vì lần này mình đang dùng ID lấy từ
[01:13:59] grab được là sai bây giờ mình sẽ dùng
[01:14:02] Chó Ken từ như thế này nó mới chuẩn này
[01:14:03] à
[01:14:07] Ừ cái này nằm hợp đấy ông ạ Cái cái cái
[01:14:10] này vẫn có thể xảy ra trường hợp là hai
[01:14:13] người dùng cùng chung một Token có thể
[01:14:16] đương nhiên ở thật là nó hiếm mình nghĩ
[01:14:19] là khó Có gì à cái cái Hàn này nó sinh
[01:14:22] ra là unique hai cậu khó khó chung rồi
[01:14:25] nhưng mà vẫn biết đâu nói khi mà sẽ lách
[01:14:26] này nó sinh ra với Token trùng nhau nên
[01:14:29] mấy ông chắc cho chắc cú hơn là bé ông
[01:14:32] ấy hệ thứ nhất là mấy ông cho cài cho
[01:14:34] Ken ở đây thêm một cột là unique này sau
[01:14:36] đó chậm chị em mình không phải kiểm tra
[01:14:39] xem là khi mà tạo ra như thế này ạ
[01:14:42] update nó có bị lỗi không Nếu mà lỗi thì
[01:14:44] bảo vệ sinh lại tao Ken Nếu phải chạy
[01:14:46] phòng Đọc đoạn này một tí để sinh lại
[01:14:48] tao kem này sẽ chuẩn cho kia nó không bị
[01:14:50] trùng với người khác sau đó thì đoạn này
[01:14:53] nữa Phải Limit muộn để chắc chắn là để
[01:14:56] chắc chắn ra Kiều chỉ có một Token nó
[01:14:57] được sinh ra thôi
[01:15:00] ăn kẹo xuất ra mồ hôi
[01:15:04] đấy nó hơi phức tạp thêm một tí không ạ
[01:15:08] em nghe nói xong đại khái nói ở đây thật
[01:15:10] ra vẫn vẫn còn trường hợp nhá ở đây là
[01:15:12] sự khi lấy ra đây là lấy được mình khiếu
[01:15:17] ở đây có thể có thể là
[01:15:19] có thể người dùng nhập Linh ta tinh cái
[01:15:21] to Ken vào cũng không thể cho người dùng
[01:15:23] đăng nhập vào cái to cat linh tinh được
[01:15:27] đóng ạ Mình sẽ kiểm tra ở đây đó là nếu
[01:15:28] mà
[01:15:31] à à
[01:15:33] em bỏ ID vô đầu của toq em thực ra là nó
[01:15:36] nửa hợp lý nữa không bởi vì ở thời ra là
[01:15:39] mình không nên lấy ID từ mái tóc em mà
[01:15:43] mình sẽ là mình mình mình mình sẽ ra
[01:15:44] điều hòa
[01:15:47] Từ từ tao Ken để xuất vào trong phải
[01:15:49] nhập vào trong dp như thế này và lấy
[01:15:51] thông tin từ trong BB ra chứ hỏi mình
[01:15:54] lấy thông tin từ các em được nhưng mà
[01:15:56] bạn nói thế Thật ra cũng có một cái hay
[01:15:59] ở điểm khi mình nhìn theo Ken mình có
[01:16:01] thể đoán được tao cái đấy của người dùng
[01:16:04] nào cũng được Nhưng mà thường làm các
[01:16:06] bạn thấy cái Token để mình có khen
[01:16:07] Facebook của các em bất kỳ hàng nào cũng
[01:16:11] làm gì có cái đoạn ạ Có Ken nàng đầu là
[01:16:13] của một ai đâu đúng ạ
[01:16:17] thường là mình hạn chế điều đấy
[01:16:19] Ừ tại vì nó liên quan vọng mật Token nó
[01:16:21] rất là bảo mật này ra là do Ken nó
[01:16:24] thường ở không nên nhìn là tao kem này
[01:16:28] để mà nhìn ra làm cái gì đó thông tin gì
[01:16:34] Có ai bán nó bỏ tao kem và trắng dùng mà
[01:16:38] thực cái à cách để mà tránh chủng ổn
[01:16:40] nhất thì mấy ông có thể chơi cho chắc cú
[01:16:42] ngất đi thì mới ông có thể dùng hàng này
[01:16:45] rồi thêm cả thời gian hiện tại vào nữa
[01:16:48] ý là được đúng ạ
[01:16:51] số mệnh Mỹ Thái chỉ cần thêm thời gian
[01:16:53] hiện tại và giết rắn ơi theo kiểu mini
[01:16:55] dây mấy ông sẽ gần như không mơ thể
[01:16:57] trùng được không bao giờ ế chồng được
[01:17:00] cái kiểu như thế
[01:17:03] em chưa Bọn anh đi vào thời gian nó như
[01:17:06] cả vì giá sự có ai mà bị lỗi có cây rồi
[01:17:08] còn treo ạ nhìn phát ra đi của người đấy
[01:17:11] là thực ra là dùng cho kem có thể vào
[01:17:13] đường link rồi nhưng mà ý mới như thế
[01:17:21] Ừ ok Nói chung là đại đoạn đoạn này thì
[01:17:23] K mình phải xử lý thêm một bước đó là
[01:17:25] mình à kiểm tra
[01:17:29] 55 bro mình kiểm tra xem là thì to Kem
[01:17:31] này
[01:17:33] ở đầu tiên mình cứ sửa đấy lại nha chỉnh
[01:17:35] sửa đây này
[01:17:37] Đây mình sẽ tạm Vứt cái to cái này ra
[01:17:38] đây nhá
[01:17:41] Bây giờ sửa mình sữa to cái này một cái
[01:17:43] linh ta Tây ngày là sữa Tôi biết rồi cái
[01:17:45] trang này sẽ kiểm tra to scan để mà đăng
[01:17:48] nhập vào tôi Giả sử thôi thử là tộc họ
[01:17:51] Kennedy là một Tôi nghĩ là tôi hệ sự có
[01:17:52] khen là một để tôi sẽ ra được cái nick
[01:17:56] 51 chẳng hạn Đông ạ thì mình sẽ phải
[01:18:00] mình sẽ kiểm tra ở đây đó là mình kiểm
[01:18:02] tra xem ảnh khi mà salad này nó trả về
[01:18:05] có bao nhiêu bạn ghi họ không có bản ghi
[01:18:08] nào thì mình sẽ không làm gì cả thường
[01:18:09] là không còn gì cả Không cần Không tỏa
[01:18:11] lỗi Nhưng mình dùng luôn
[01:18:13] từ nhỏ để người dùng vẫn đăng nhập vào
[01:18:16] bình thường cái kiểu thế Mình sẽ mãi của
[01:18:20] Ly nắm râu này bị sốt này
[01:18:24] à à ạ sau đó đi
[01:18:29] f5pro bằng bằng 1 thì mình mới làm cái
[01:18:30] đoạn ở dưới hè thôi
[01:18:32] t-ara
[01:18:35] Còn không thì mình không làm gì cả mình
[01:18:44] Ừ tôi lẻ một này này tải trang
[01:18:46] anh em yêu thế sáng ở hiện tượng này xảy
[01:18:49] ra đây cả Không ạ Còn bây giờ tôi sẽ
[01:18:51] nhét cái đoạn này vào
[01:18:53] Lý Hải
[01:18:58] ở đội bào ấn vào này phải lại tra này Đó
[01:19:01] nó nghiệp thành công Ok nếu không hiểu
[01:19:03] về cái đoạn Cookie và to scan cái thử
[01:19:04] chưa
[01:19:07] Khi bữa hôm nay cho ca thật ra mấy ông
[01:19:08] thấy chưa ra cốc Hôm nay thì ra nó ngắn
[01:19:11] hơn nhiều hoa cho ta giải thích nó cũng
[01:19:14] khá là dài vì nó hơi bị nặng với lý
[01:19:16] thuyết và nếu phải hiểu cơ chế của nó
[01:19:20] khác biệt sân này Phân biệt nó này cái
[01:19:23] áp dụng nó và và thức A cái này nó hơi
[01:19:26] còn hơi nâng cao một tí Bởi vì tôi dậy
[01:19:29] đó sinh viên Hồi trước của tôi ý thì nó
[01:19:32] dễ hơn theo kiểu tôi cho sinh viên tôi
[01:19:36] lưu lại mã vào trong cốc cốc kì luôn
[01:19:39] Nhưng mà thực ra là tôi dậy cho mấy ông
[01:19:41] không thể theo thế được vì em ấy ông như
[01:19:43] thế mấy ông trang web bé ông dễ bị hack
[01:19:45] không ạ
[01:19:47] Ê tôi dậy là sinh viên tôi như thế được
[01:19:49] Tại sao Vì tôi biết chắc chắn sinh viên
[01:19:51] thôi cứ Dĩnh về học cái khóa thứ hai của
[01:19:54] tôi khóa nâng cao để bọn nó sẽ phải biết
[01:19:57] bảo mật hơn còn tôi dậy cho mấy ông bây
[01:19:59] giờ phải dạy cho miếng bảo mật ngay từ
[01:20:01] lúc đầu bởi vì tôi không Chắc được mấy
[01:20:04] ông đã theo quả thứ hai của tôi mà Mấy
[01:20:07] ông không theo Hòa được hai mà ông áp
[01:20:10] dụng cốt này đi làm trong cái màu đỏ sau
[01:20:12] miếu bị hack trứng biếng vậy thì tôi sao
[01:20:14] tôi chết mất ông ạ thế nhưng tôi phải
[01:20:17] dậy ôm những cái bảo mật
[01:20:20] xe hơi nâng cao một tí
[01:20:24] ngay từ bây giờ đấy rõ tôi dậy ông ấy
[01:20:25] ông ấy hack cùng này thì cũng sẽ thấy
[01:20:28] hơi bị choáng mà hơi bị nặng kiến thức
[01:20:31] một tí nhưng mà hacker đối với bọn
[01:20:33] hacker thì bọn nó mò mẫm cái này bọn nó
[01:20:35] nghiện mình cái này phải dùng từ nghiện
[01:20:38] chích mày cái ấm và bọn thích phá nữa
[01:20:41] thì ra là mấy ông mà mấy chị học cơ bản
[01:20:44] mà Mấy ông đã đi làm đã kiểu tao học cơ
[01:20:46] bản nó có biết làm trang web rồi tớ
[01:20:49] không học khóa nâng cao đâu rồi ông đi
[01:20:51] làm trang web mà cốt kiểu như thế này
[01:20:53] thì rất dễ bị hack ngã người không phải
[01:20:56] quay kiện thôi chết tôi vừa dậy xong
[01:20:59] thôi phải vừa dậy luôn cả bảo mật
[01:21:01] Ồ không Tôi chưa cần phải dạy mày ông về
[01:21:03] cái thư viện đấy đó mình cái sever gì đó
[01:21:05] Tôi đang dạy mấy ông cũng tương đối rồi
[01:21:07] mà đúng không ạ Thế này thì tao mày cũng
[01:21:11] tránh tương đối rồi đấy
[01:21:14] anh méo hiểu Mục đích và ý nghĩa chưa
[01:21:15] đấy
[01:21:18] chứ hồi mà tôi dậy ở sinh viên Tôi nói
[01:21:21] tôi dậy cốt đoạn này ngắn lắm mấy cái
[01:21:23] đoạn là không cần xử lý bọn nó còn chưa
[01:21:26] biết spi nhé xin là cái gì cả Ừ nó chẳng
[01:21:28] biết Token là cái gì luôn tôi không dậy
[01:21:30] bọn nó cái tóc Ken đâu tôi dậy bọn nó
[01:21:32] rất là đơn giản để Bởi vì tôi biết kiểu
[01:21:36] gì cũng bọn nó cũng sẽ phải học từ đầu
[01:21:37] đến cuối của tôi là cái gì sang khóa
[01:21:40] nâng cao bảo tôi sẽ dạy Bỏ nâng cao về
[01:21:49] Ừ ok Nói chung nhất thì thế rồi ông ạ
[01:21:52] thì bây giờ Nhân tiện bạn kia và lại hỏi
[01:21:55] mình sẽ chia sẻ nốt một cái cũng đau đầu
[01:21:58] nữa Hôm nay đau đầu có màu rất đau đầu
[01:22:01] bây giờ chúng ta sẽ nhảy sang bài toán
[01:22:04] phân quyền và Lâu lâu không kém
[01:22:05] Ừ
[01:22:09] tự nhiên bệnh dithane ông kia là xe code
[01:22:13] website buồn cười rồi à
[01:22:19] nhà mình có chia sẻ nhanh về hít vào
[01:22:22] buổi cuối buổi hôm trước cơ mà mình sẽ
[01:22:24] cách tướng đôi về cách sử dụng tool ký
[01:22:32] ở đây là quả on đấy Tôi không còn dạy
[01:22:34] online ở chỗ khác đâu Đây là khóa online
[01:22:41] ở đầu tiên để bài toán phân quyền thì
[01:22:44] cái này là đây Đó là hình thức ngủ một
[01:22:46] mức tương đối và anh đây cũng sẽ hiểu
[01:22:56] ở đây thì giả sử ở đây nó sẽ có bạn anh
[01:22:59] ấy luôn đặt ra câu họ trước không ạ Bạn
[01:23:02] là sếp bạn toàn của toàn quyền này bạn
[01:23:03] chuyển trưởng phòng chỉ có quyền của
[01:23:06] nhân viên vọng mình bạn trưởng nhóm thì
[01:23:10] sẽ có sẽ kiểu như này
[01:23:13] vì nếu Giả sử bạn chỉ có một quyền hạn
[01:23:15] mà có nhân này đối tượng vào lần này
[01:23:17] quyền hạn thì bạn sẽ làm như thế nào
[01:23:20] chẳng ạ và vì sau là sự có thêm nhiều
[01:23:23] phòng ban nhiều bộ phận hơn chị sẽ có
[01:23:26] quyền khác nhau thì sẽ thì sẽ làm như
[01:23:33] ở đài thị thưởng xong rồi cẩn thận chế
[01:23:35] phân quyền theo nhóm thì làm như thế nào
[01:23:37] cho hạ thế
[01:23:40] ở đầu tiên thì mày toán đơn giản nhất mà
[01:23:43] tôi dậy tôi dậy cho mấy ông đang làm đồ
[01:23:46] án đó phân quyền theo cấp bậc theo kiểu
[01:23:48] chỉ có một cột cột cấp bậc như thế này
[01:23:51] và cột này sẽ có thể lỗi xong bản khác
[01:23:53] kiểu nghe cũng được
[01:23:57] à à Không em đôi khi không Có nối xong
[01:23:59] bạn khác ở một và to nhất hay đi rồi Bà
[01:24:01] Thứ ba như thế này chẳng hạn như thế này
[01:24:04] ưu điểm này dễ dàng cho người bắt đầu
[01:24:07] lại đó ông ạ thì các bạn chỉ cần chết
[01:24:09] tương đối đơn giản là kiểm tra xem em ạ
[01:24:11] Cái kiểu người này có quyền một hai
[01:24:14] quyển 2 những điểm thì nó sẽ nhược điểm
[01:24:18] nó sẽ là kiểu Đây là sự nghiệp điểm này
[01:24:19] không phải lúc nào nó cũng chỉ có mỗi
[01:24:21] vài quyển như thế đôi khi ở giờ sự Thu
[01:24:25] Ký có quyền đổi việc thế nhưng lại chẳng
[01:24:28] hạn thì nó sẽ thuộc quyền của giám đốc
[01:24:32] hay là gì đấy chẳng hạn thế về sau có và
[01:24:34] nó khó làm phân quyền chi tiết
[01:24:37] ở đài phân quyền chi tiết là nó sẽ kiểu
[01:24:38] như thế nào nó phân quyền như tổ chức
[01:24:40] năng như thế này để ví dụ là có toàn
[01:24:43] quyền đọc này à Có toàn quyền hay là có
[01:24:45] mỗi quyền đọc này hay Có mẫu Quyền truy
[01:24:47] cập này còn mũ quyền sửa không cần xóa
[01:24:50] này là sử như là hôm trước làm
[01:24:54] Anh à Hôm trước làm trang web tin tức
[01:24:56] chẳng hạn tin tức thì không trước mà tôi
[01:24:59] dậy cho ông ấy Ông chỉ có đơn giản là có
[01:25:04] admin mà Superman thức là kiểu nhân viên
[01:25:06] và quản lý
[01:25:08] đây đúng không ạ thì nhân viên ở sẽ có
[01:25:11] quyền thêm và xem
[01:25:15] đã sửa nhưng mà chị được sữa à Cái liên
[01:25:17] quan bản thân ở nhà không có xóa ở Ngạn
[01:25:21] nhưng mà quản lý trị có quyền thêm xem
[01:25:23] và sửa và xóa luôn em ạ
[01:25:26] Ừ cái kiểu thế mà ông sẽ thấy à Thằng
[01:25:28] này nó sẽ ít hơn quyền hỏi một cấp chẳng
[01:25:32] hạn cơ Thế thì phù hợp với việc là làm
[01:25:34] hai kiểu tạo ra bảng lại bảo permission
[01:25:38] như này mà bạn áp trên sau đó nối nối
[01:25:41] người dùng từng người từng người dùng
[01:25:45] nhé Nói đến cái quyển các thứ thứ phân
[01:25:48] cấp như thế này tóm gọn lại nó sẽ là gồm
[01:25:51] 47 như hãy trả lại đó
[01:25:54] cho tôi tôi không giải thích Mấy cái
[01:25:56] bảng ở đâu Mấy ông thể tham khảo sau nhé
[01:25:58] Thôi để đường link này mày ông tham khảo
[01:26:01] này à
[01:26:04] ý Thì cái này nó rất phù hợp với việc ưu
[01:26:06] ưu điểm nó sẽ là gì
[01:26:09] Ừ nếu anh xem ví dụ 2 cái từ từ sau nhé
[01:26:11] tôi bỏ qua mấy đứa bạn này cứ điểm này
[01:26:14] thì mới ông hoàn toàn thể làm chi tiết
[01:26:16] được cho mỗi người dùng có quyền gì các
[01:26:20] thứ thứ nhưng nhược điểm là cái này nó
[01:26:27] Ừ cái cái cái vừa rồi thấy vừa rồi nó
[01:26:29] vẫn là nhóm nhá Nó vẫn giúp chứ không
[01:26:33] phải từ người dùng đâu thì phải cho xem
[01:26:37] Có ai đi permission
[01:26:39] thế hả Đấy Đại vẫn từng người dùng rồi
[01:26:51] a a dunno cái trên một nhóm mà theo ấy
[01:26:54] chị ra là một người dùng sẽ có hành động
[01:26:58] các thứ thứ nhưng mà không không chia sẻ
[01:27:00] theo cả một người dùng có thể một lúc
[01:27:03] hai quyền được ra sự thư ký nó vừa là
[01:27:05] thức ý nó vừa là quyền giám đốc Anh Thư
[01:27:08] còn đây làm chị một người dùng chỉ có 1
[01:27:12] lô thôi là một kiểu một chức vụ thôi còn
[01:27:13] nếu là một người dùng có thể có nhiều
[01:27:16] chức vụ Ví dụ ở sự như là trưởng phòng
[01:27:19] trưởng phòng đi trưởng phòng vừa có
[01:27:22] rô là trưởng vòng vừa có
[01:27:25] Chức vụ của nhân viên nữa nghĩa một lúc
[01:27:27] nó nó có thật hay chức vụ và hai chức vụ
[01:27:30] để nó phải có 22 điều với môi trường
[01:27:35] cho nên là cái đấy không phải thiết kế
[01:27:38] được B nó có lằng nhằng hơn nữa và kết
[01:27:41] luận ở đây kết luận ở đây đó là thực ra
[01:27:44] là tạo ra nhiều DB như thế sao nấu về
[01:27:46] nhau Thực ra nó rất là phức tạp Các bạn
[01:27:48] thấy Riêng cái bảng này của anh đấy làm
[01:27:51] để mô thôi Nhìn thấy bảo ở chung dài vãi
[01:27:54] chưởng ông ạ Anh có bao nhiêu người dùng
[01:27:56] ở mấy ông vệ sinh ra bởi nhiều như thế
[01:27:58] này không đánh Index cái này mệt này sao
[01:28:00] mày không có phải chết chung cái thôi
[01:28:02] cái đoạn này Đột nhiên có rất nhiều thư
[01:28:04] viện Bây giờ mày ông áp dụng Facebook
[01:28:06] này mà có rất nhiều thư viện về
[01:28:08] permission mấy ông làm được các thao tác
[01:28:11] chỉnh sửa quyền nhanh rồi hay tự động
[01:28:14] thêm quyền nhanh rồi nhưng mà đây là để
[01:28:16] mà đi sâu hơn hiểu mình Ông muốn đi sâu
[01:28:18] hơn và hiểu bản chất của một cái thư
[01:28:21] viện này làm món gì với ông thì đọc qua
[01:28:25] bài này và ví dụ rồi thấy nó rất là ạ ôi
[01:28:27] ông Tom và giải thích này nữa thì chị
[01:28:31] tôi cũng đau não à
[01:28:34] thế này bởi vì cứ mỗi lần mỗi lần mà Mấy
[01:28:37] ông kiểm tra có quyền xóa bài hay gì đó
[01:28:39] không Mày không phải do người này bà nếu
[01:28:42] không thấy cái cũng mệt không ạ Đấy như
[01:28:46] thế này thì mới ông sẽ thấy cậu nó nó
[01:28:50] thức cơ à Mình mà đánh Index cho nó rồi
[01:28:52] và do voi được ra nó khá nhanh trong cái
[01:28:54] queo nhưng mà đoạn này cũng về các bạn
[01:28:59] nó sẽ là nó sẽ là kiểu phải phải sẽ rất
[01:29:02] nhiều ấy không Mỗi lần vào một cái một
[01:29:04] cái a b c ông cứ bấm nhầm cái đường Linh
[01:29:07] nào đó là nó lại kiểm tra quyền ông ông
[01:29:08] có quyền truy cập của cái đấy Không
[01:29:11] nhưng mà như thế thì nó mới ổn phải bài
[01:29:13] toán nó bảo mật bởi vì không cho người
[01:29:15] dùng tự quyền xin sửa một cái gì đó nó
[01:29:17] không ạ
[01:29:19] Ừ tôi không dậy không mày không cái này
[01:29:22] đâu Tôi không dậy không mấy ông cái này
[01:29:25] ở đồ án Cơ bản thôi chị dậy yêu miếu có
[01:29:27] quyền đăng nhập vào thôi nên bài toán
[01:29:30] phân quyền tôi tạm bỏ đi nhé
[01:29:32] Ừ Ok chưa
[01:29:40] Ừ đúng rồi khóa này khóa đầu tiên và
[01:29:42] cũng có thể là khóa cuối cùng có thể
[01:29:43] thôi
[01:29:46] Em không biết được về sau mày ông có dụ
[01:29:48] dỗ kèo thôi không Tôi là con người à
[01:29:51] không dễ bị bệnh hót nhưng mà tôi kiểu
[01:29:52] đó
[01:29:55] Ừ thôi mà thấy có cái gì đó làm cho hứng
[01:30:02] anh không hiểu chắc chắn thôi không thể
[01:30:04] Ông vừa nghe gái ông hiểu được cái này
[01:30:06] nhưng mà lại khán thì mấy ông thấy cái
[01:30:10] này khó không ạ nhưng mà cái này mới thì
[01:30:12] tiêu đây nó nói tất cả mà nó là rất là
[01:30:16] khó hiểu đúng ạ ạ
[01:30:19] Ừ cái cái này thì đại khái nãy giờ mấy
[01:30:21] ông chỉ cần đúc kết Kể như thế này đó em
[01:30:25] chỉ là tôi dậy cho mấy ông đơn giản có
[01:30:29] lý do của nó bởi vì đó đó và tôi dạy cho
[01:30:33] mấy ông chỉ việc à à Kiểu phân hai hay
[01:30:36] thứ nhất là phải phân ra thành kiểu 2
[01:30:39] cấp ngoại và mỗi cấp nào thì làm được
[01:30:41] ABC ghi thẳng vào trong cốt là hàng ngày
[01:30:44] chỉ được truy cập và cái này thằng này
[01:30:46] được phép truy cập bởi kia vào trong cốt
[01:30:49] Còn mấy ông muốn làm cái kiểu đó
[01:30:52] Ê thằng admin này sẽ chữa truy cập vào
[01:30:55] cái bài đăng của nó đã thêm chị phép sửa
[01:30:58] được đang mở thêm đã làm một cái thêm
[01:30:59] khói đó ngoan
[01:31:01] rồi kết hợp với việc là
[01:31:05] thêm một hàng nữa thằng Duyệt bài của nó
[01:31:06] chỉ phép Duyệt bài chứ nó không được
[01:31:08] phép sửa bài không phép thêm bài nào ạ
[01:31:11] thì nó lại phải lưu lại trong B1 cái cấp
[01:31:15] độ nữa nói khó hơn cho mấy ông muốn càng
[01:31:17] làm chi tiết thì cốt của ông càng rối và
[01:31:21] càng khó hơn thế thôi ngoại và dp các
[01:31:22] bạn phải lưu lại những cái Yêu người nữa
[01:31:24] họ sẽ khó hơn
[01:31:25] Ừ
[01:31:28] nếu mà đi làm mấy ông
[01:31:30] ở miệng phải làm những cái khó như thế
[01:31:33] thì người ta mới chuyển ông ấy không ạ
[01:31:35] đương nhiên là mấy ông không phải lo
[01:31:38] việc là buổi em mới đi làm em gặp này
[01:31:41] xem chết không chuyện đấy bởi vì em mới
[01:31:42] đi làm về ông không được động vào những
[01:31:45] cái liên hoan đi database đâu mà không
[01:31:46] sẽ chỉ làm những cái tính năng thêm sữa
[01:31:49] xóa rất đơn giản thôi Còn nếu mà nhưng
[01:31:53] mà về sau phải xác định lườn đó mấy ông
[01:31:55] muốn nếu mà mức lương nào không ạ Mấy
[01:31:57] ông vẫn muốn mình ở mức lương mới đi làm
[01:32:01] à Không ạ Mấy ông muốn mình ở mức lương
[01:32:03] cao hơn không ạ mức lương cao hơn ở bên
[01:32:05] ngành lập trình viên này nó không phải
[01:32:06] ông làm nhiều năm kinh nghiệm thì sẽ lên
[01:32:13] đâu mà nó là ông làm và làm được kẹo
[01:32:14] phải tự nâng trình bản thân mình lên đấy
[01:32:16] thì mức lương nó mới lên
[01:32:21] ở đâu ạ Nó sẽ có gọi là sẽ có đợt review
[01:32:26] dùng từ đợt review đợt
[01:32:30] review lương nó sẽ kiểm tra lại trình độ
[01:32:33] của ông xem là cái trình độ của ông đang
[01:32:35] đến cái ngưỡng nào rồi thì nóng mới nó
[01:32:37] mới quyết định tăng lương cho ông ngoại
[01:32:41] nghe nhiều ông kieu Han kìa mấy cái mấy
[01:32:44] Tôi còn biết mấy ông Thạch sư chứ Đợt
[01:32:48] review về trình độ của ông lúc vào mới
[01:32:50] vào với cái lúc sau một năm thì có trình
[01:32:52] độ ông vẫn thế với ông bị lười Hải Vân
[01:32:54] ông suốt ngày Ông chị cốt những ngày
[01:32:57] phân ông đã Ông biết ông không đọc thêm
[01:33:01] tài liệu tôi không nghiên cứu thêm ấy
[01:33:03] sau một năm Nếu không vẫn chỉ biết xem
[01:33:06] thêm sữa Xóa Thằng ạ thì được review nó
[01:33:09] sạch sau đó thì mấy ông cay cú với ông
[01:33:11] sẽ nghỉ việc đấy lý do mà cái ngành này
[01:33:14] nó luôn hót như thế của việc
[01:33:17] Ẩm Thực ra lập trình viên giỏi theo kiểu
[01:33:20] ngày ngày nghiên cứu thì ít mà ông kiểu
[01:33:22] cứ nghĩ rằng là ngày ngày dễ rồi nhảy
[01:33:24] vào nhiều tiền nhiều
[01:33:27] à Tôi đang chia sẻ thật đấy tôi không hề
[01:33:29] dụ dỗ mấy ông theo ngành công nghệ không
[01:33:30] tin lắm
[01:33:32] Ừ cái đấy Đang chị sạch da thật tôi
[01:33:34] không sợ mấy ông cướp việc của tôi nên
[01:33:39] tôi thì mày Ông Táo cũng không đưa đến
[01:33:42] đến lượt Nếu cứ việc đâu vì nhiều việc
[01:33:44] lắm Nếu mà
[01:33:46] Ừ tôi vẫn sẽ dạy mày ông Lập trình để
[01:33:49] mày không hiểu qua toàn bộ Tôi bảo là
[01:33:51] học khóa này không phải để mấy ông thành
[01:33:53] lập trình viên ông ạ quá sau mình mấy
[01:33:56] ông mới thành lập trình viên được khóa
[01:33:59] này chỉ để mấy ông hiểu qua về lập trình
[01:34:01] viên làm được những gì nếu không làm
[01:34:03] được như lập trình viên hay không Nếu
[01:34:05] không có phù hợp với lập trình viên hay
[01:34:08] không đúng ạ nhấn mạnh về những người
[01:34:10] tiêu trị của về khóa học này rồi đấy ạ ạ
[01:34:14] à à
[01:34:16] Ẩm Thực tập An thực tập Người ta vẽ vợ
[01:34:19] chồng gì đó mơ mộng và vứt cho mày phải
[01:34:25] anh nói chung là thằng theo ngày này thì
[01:34:28] ra mấy ông làm đầy đủ những cái mà Mấy
[01:34:31] ông đã học thì thực ra nó vẫn sẽ chỉnh
[01:34:32] mức lương như thế người ta sẽ không
[01:34:34] không đuổi được với ông đâu nhưng mà
[01:34:38] người ta sẽ không tăng lương ông đâu bởi
[01:34:39] vì à
[01:34:42] anh Bởi vì ông có học có
[01:34:45] có cái gì đó hơn đâu nó khác hàng khác
[01:34:48] như điểm đấy mưa Khởi đầu có thể ạ tương
[01:34:50] đối cao so nhàng các nhưng nó vẫn sẽ chỉ
[01:34:53] dậm chân tại chỗ tại đấy thôi nên nhiều
[01:34:56] mình nghỉ việc chứ là nhiều ông nhảy
[01:34:57] việc sao không lấy được con thất nghiệp
[01:34:59] thế ngành này nó vẫn
[01:35:02] thiếu thiếu người không ạ mà toàn thiếu
[01:35:03] người
[01:35:06] có bao nhiêu bao nhiêu nhà Tuyển dụng
[01:35:09] đều nhắn tin kiểu toàn bằng mấy cái kiểu
[01:35:13] ở mức lương có thể đến 2.000 đô là bao
[01:35:16] nhiêu đâu rồi Thậm chí ông chỉ cần giới
[01:35:18] thiệu về ông bà biết làm một tí vào
[01:35:20] trong công ty kia ông đấy mà nhận được
[01:35:22] nhận việc ông được 15 triệu luôn hai 20
[01:35:26] triệu luôn cả bạn đấy nó còn vợ nó còn
[01:35:29] hấp dẫn như thế đúng không ạ Em Vẫn
[01:35:31] thiếu người bởi vì sao Vì vẻ đẹp
[01:35:32] cài
[01:35:34] đặt trình viên mình
[01:35:39] anh vẫn còn đang bị kiểu chạy theo à
[01:35:41] chứ không phải chạy theo đam mê mà chạy
[01:35:44] theo kiểu dạng ạ về tiền bạc nhiều hơn
[01:35:44] không ạ
[01:35:47] ở tuổi tôi đam mê nhiều hơn là tiền thì
[01:36:01] anh chia sẻ mức lương thực tế mức lương
[01:36:04] thực tế thì tôi từng nói rồi đó là khi
[01:36:07] mà Mấy ông một con mấy đi làm ở nhận mới
[01:36:09] đi làm thì người ta lại chửi cho phụ cấp
[01:36:12] thôi Có công ty nào hợp hấp dẫn một tí
[01:36:16] thì thì phụ cấp tận 1 đến 3 triệu Còn
[01:36:18] công ty nào một kiểu sáp kiểu bèo thì sẽ
[01:36:20] cho 500 thôi
[01:36:23] 500 có khi a vẫn còn tương đối có công
[01:36:25] ty 200 rồi thế
[01:36:28] khi họ vẫn sẽ vụ hỗ trợ cho các bạn về
[01:36:31] thiết bị cấp cho xứ ít công ty nào không
[01:36:33] bây giờ không chuẩn bị cho mẹ ông Thiết
[01:36:34] bị ốm
[01:36:36] à Nếu nghe mẹ ông sẽ phải trao trả lại
[01:36:39] thiết bị người ta Nếu không nhỉ
[01:36:43] ạ sau đó thì hiện khi ông nhận được việc
[01:36:46] thì lương lên đến 78 triệu Hoàng 15 thí
[01:36:50] nghiệm với ông sẽ 78 triệu sau đó đi chị
[01:36:53] 235235 thí nghiệm thi ạ Đấy là theo kẹo
[01:36:55] ông càng làm
[01:36:58] làm và ông làm được dần những cái tính
[01:37:00] năng dần dần dần lên chứ không phải ạ
[01:37:03] Không không phải là vẫn tiếp tục những
[01:37:06] cái những cái tính năng cơ bản thì ông
[01:37:09] sẽ tăng dần lên chỉ cần ở 35 là ông thể
[01:37:11] lên đến 15 triệu 3 5 1 5 triệu ở Quảng
[01:37:15] Bình thường để đấy ông theo kiểu là là
[01:37:17] con người bình thường nhé Còn nếu mà ông
[01:37:18] theo cậu đã thân đồng những cái thứ thứ
[01:37:21] thì 35 lên đến 20 triệu lấy 40 triệu
[01:37:24] chuyện vẫn là bình thường Em vẫn ở dơ
[01:37:27] bình thường ở trong cái ngày này kiểu gì
[01:37:30] tôi quen rất nhiều người còn lên đến
[01:37:33] bây giờ tính toàn nghìn đô mà không ạ
[01:37:37] anh
[01:37:41] giống như à em về thảo ở trong Triều
[01:37:43] Tiên này được trả 1 Bitcoin này
[01:37:48] nghe nghe nhỏ vậy một Bitcoin á Không
[01:37:50] không không đến nỗi một Bitcoin nhưng mà
[01:37:54] chào biết coi nghe thấy đù Xấu mà
[01:38:07] đã bao lâu nữa hết khóa bao lâu nữa chả
[01:38:10] tấm ai bá đạo nữa thôi
[01:38:12] điều hòa sau rồi sẽ lập trình nâng cao
[01:38:14] cho tôi lúc này tôi không hi vọng đông
[01:38:16] người như này đâu bởi vì đông người như
[01:38:18] thế này thì à
[01:38:21] gì nó cũng có cái ngại cho tôi à Ăn một
[01:38:25] vì khi nâng cao rồi à Tôi sẽ mở mở máy
[01:38:27] không quá nhiều lắm đấy ông ạ học hỏi từ
[01:38:30] rất nhiều nguồn này cũng như thoải mái
[01:38:32] cốt bằng nhiều ngôn ngữ này xong rồi
[01:38:34] dùng như thư viện rất hư không mấy ông
[01:38:36] mà hỏi thôi mấy cái đấy thôi Chẳng biết
[01:38:38] trả lời ông nghĩa nào
[01:38:40] về lúc này tựa họ cũng dễ mà nhiều hơn
[01:38:45] như tội sẽ dậy đầy đủ mà ông cách làm
[01:38:47] Nói chung là định hướng là mấy ông nhiều
[01:38:57] à à
[01:39:02] Ừ đúng rồi mình sẽ vừa mình dùng mình
[01:39:04] phải dậy trước MV xe opel đã Sau đó mình
[01:39:08] sang reserved e-movie xe ouat song Thực
[01:39:11] ra các bạn từ đấy mà các bạn nhảy sang
[01:39:14] ngôn ngữ khác cũng được gặp kiểu ta thấy
[01:39:23] cho Bơ cũng có nhiều công ty nước ngoài
[01:39:25] tuyển được sinh viên Việt Nam mà tôi có
[01:39:27] mấy ông chỉ cần đọc tài liệu tiếng Anh
[01:39:28] cơ mà
[01:39:32] Ừ đúng rồi đi cà phê mốt đấy à
[01:39:32] ấn
[01:39:36] độ hôm nay tại miền đây thôi nhỉ bạn
[01:39:39] thắc mắc nó thử xem còn mà họ nốt em có
[01:39:48] Mỹ Tâm Cốt tập 10 năm nữa thì sẽ làm gì
[01:39:51] đấy Thực ra là
[01:39:53] tôi tôi cũng chẳng hi vọng của tôi sẽ có
[01:39:56] 10 năm kinh nghiệm thường là tôi bảo rồi
[01:39:59] nếu không phải từ ra lúc đấy Mấy ông
[01:40:02] không đủ người ông kiểu đầu óc có thể
[01:40:03] tính toán nhiều rồi mình không còn minh
[01:40:06] mẫn mà ngồi học hỏi thêm công nghệ nữa
[01:40:09] thường là mấy ông sẽ là lý do cậu là
[01:40:12] định hướng rồi cũng như cậu
[01:40:16] Chuyên về xử lý bài toán này tập toán
[01:40:19] các thứ hoa cà Nếu có mấy ông không quên
[01:40:20] cảm thực hành những cái đấy Nếu không
[01:40:23] thể quay về đi dạy này lấy vốn mở một
[01:40:27] cái gì đó ở quán net hả nhãn tôi đang
[01:40:30] định mở quán cà phê này không ạ khi nghe
[01:40:41] Chỉ có tôi sẽ nói qua về 2 tf2 xe đấy
[01:40:56] Ừ thôi tra Bộ không ai em Thế thôi nha
[01:40:58] Chào bạn nhé
