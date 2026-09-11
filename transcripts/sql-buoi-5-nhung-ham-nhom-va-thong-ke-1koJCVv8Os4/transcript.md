# SQL - Buổi 5 - Những hàm nhóm và thống kê

- Video ID: `1koJCVv8Os4`
- URL: https://www.youtube.com/watch?v=1koJCVv8Os4
- Published: 2021-09-23
- Duration: 1h 38m 17s (5897s)
- Language: vi
- Subtitle source: auto
- Kind: live

## Transcript

[00:00:51] Em à mình mới đổi mình mới đổi à xanh độ
[00:00:59] anh bình bình luận Bây giờ nó sẽ cậu
[00:01:01] chậm hơn rất nhiều nha
[00:01:04] về chất lượng mà sẽ cải thiện
[00:01:07] Ừ chắc là được đấy
[00:01:25] anh mưa rồi đúng không nghe Bây giờ thì
[00:01:27] có độ trễ nó tăng lên rồi thì nên thành
[00:01:29] ra là
[00:01:32] khi các bạn nhắn tin gì cho người đến
[00:01:34] tầm 56 phút sau có gì thế không biết
[00:01:42] cho nên là cái này Thực ra nó cũng là
[00:01:45] nhược điểm của kìa mình mình từng thấy
[00:01:49] một vài truy mơ kiểu à
[00:01:53] I kiểu nó hơi bị phốt một tí cho kẹo
[00:01:57] trò chuyện một loạt spam bình luận là là
[00:02:00] cảnh báo chuyên mơ nhờ chưa Mơ một lúc
[00:02:08] anh đi đây này là delay cả giọng nói của
[00:02:10] mình với hình ảnh hay như nào hay chỉ
[00:02:13] đơn giản đã delay so với bình luận thôi
[00:02:15] nha các bạn nghe với hình ảnh cha vẫn
[00:02:29] chỉ tạm chấp nhận các bạn sẽ học và chủ
[00:02:39] Ừ ok ở chỗ nào hôm nay mình bắt đầu buổi
[00:02:42] họp nha hơi muộn muộn một tí thôi
[00:02:45] thì hôm nay mình sẽ học à
[00:02:48] Ờ Ờ cái này Thực ra là
[00:02:51] Ừ mình đang dịch ra tiếng Việt nó hơi bị
[00:02:55] thô và mình cho biết từ như nào mình tra
[00:02:57] Google nó toàn ra tiếng Anh thôi nên
[00:03:00] mình tạm gọi này như thế này Đó là hàm
[00:03:02] nhóm tứ ca liên quan hôm nay mình sẽ
[00:03:06] dbow và thống kê thời gian thống kê này
[00:03:07] là liên quan đến những cái ha môi trước
[00:03:09] mình đã học những kết hợp với cả hôm nay
[00:03:13] nó sẽ liên quan dụ là lấy ra mới nhất
[00:03:16] này ra cũng ngất này Hà chỉ lấy ra 5 bạn
[00:03:21] thì
[00:03:25] mình có tổng hợp lại câu hỏi của hai
[00:03:28] buổi 2 buổi hôm trước để mà hôm nay mình
[00:03:30] trả lời nhanh này à
[00:03:36] à à Học làm web web gà hôm trước mình
[00:03:38] từng nói các bạn hạn chế gỗ ép thì viết
[00:03:42] như này nhá đổi hơi cơ bản
[00:03:45] rất công nghệ thông tin đó là mình nên
[00:03:48] sửa ngay Mình lỗi chính tả ở nhà không
[00:03:49] Mất mặt lắm
[00:03:52] bắt buộc phải học file không chỉ ra thế
[00:03:56] thì thực ra các bạn không cần phải học
[00:04:00] bắt buộc cái gì cái phần em
[00:04:03] ờ ờ nếu mà các bạn chỉ cần làm bác em họ
[00:04:06] thậm chí cả các bạn học chuyên vé queo
[00:04:07] rồi thì các bạn không cần phải học ngôn
[00:04:10] ngữ lập trình cũng được nhưng mà
[00:04:13] Ừ nhưng mà thực tế thì các bạn biết một
[00:04:16] chút để mà làm lúc đầu làm cả hai làm từ
[00:04:19] đầu đến cuối một cái trang web tự bản
[00:04:22] thân mình làm đấy thì nó sẽ ổn hơn
[00:04:25] có cách nào để con bớt từ máy kia xanh
[00:04:27] espresso với Nhanh không thì cái này
[00:04:30] chính cặp chứ bạn này đã nói những từ
[00:04:33] khóa để mà cha Oh rồi nó Converse máy
[00:04:46] này từ Apple Server này đó rõ ra những
[00:04:49] cái tool hoặc à những cách để bán
[00:04:53] convert xong rồi Đương nhiên là mình
[00:04:56] nghĩ là đương nhiên nó cũng sẽ có nó tun
[00:05:00] công cụ thì nó có thể là Ừ nó chỉ hỗ trợ
[00:05:02] những cái bài Toán phổ biến trên nó
[00:05:04] không hỗ trợ những bài toán mà phức tạp
[00:05:08] theo kiểu đó giờ dài dòng thì cho là
[00:05:10] mình nghĩ là cái tôi này không thể hỗ
[00:05:12] trợ được
[00:05:18] Xe Tăng 2 lần thì như bị tương tác với
[00:05:21] đi vậy thấy có mỗi 80 mấy ông hay là
[00:05:24] chắc à Mấy ông toàn ngồi xem lại hết rồi
[00:05:28] nhé Tự nhiên càng ngày lượng sinh viên
[00:05:30] lại càng giảm dần Không biết là mình có
[00:05:32] gì sai sai đấy không
[00:05:38] Ừ anh đến Tuyết là như thế nào ạ Thì
[00:05:41] thực tế là trường mình dậy à người lập
[00:05:45] trình đưa nghe nó sẽ dạy cả từ HP pro CS
[00:05:48] này cho đến ngôn ngữ lập trình c xong
[00:05:53] rồi TP này ra va nữa và nhưng có cả SQL
[00:05:55] thì à
[00:05:57] Ừ nhưng mà như vậy Nãy Nhưng có nói đó
[00:05:59] là thôi mình đi học ra mình không quan
[00:06:02] tâm mấy cái này lắm lúc mà mình đi làm
[00:06:05] thì mình quan tâm hơn cũng như là về sau
[00:06:11] người sau mình quay lại đi dạy thì mình
[00:06:13] thấy aquare phải thực sự hai đều mà dậy
[00:06:17] dậy hay ân hận so với bên ngôn ngữ lập
[00:06:18] trình
[00:06:26] cho anh Anh Mình mình có gắn link mà à
[00:06:28] Xin lỗi Xin lỗi Xin lỗi
[00:06:33] à à
[00:06:38] Ừ mình vừa nãy mình xóa cái bình luận cũ
[00:06:42] à À rồi rồi
[00:06:44] à à
[00:06:47] thì các bạn mượt hơn rồi nó không bị nát
[00:06:50] nữa đúng không Ok Ok
[00:06:52] à à
[00:06:56] thì tại sao không khai bào 30kg ngay tại
[00:06:59] cột đó mới để ở dưới cái này thì mình
[00:07:02] mình vài bài học luôn à mình xem qua về
[00:07:05] cái vụ hôm trước mình có bảo các bạn thử
[00:07:17] xe máy queo thì nó sẽ khác SQL Server
[00:07:19] một vài chỗ thôi
[00:07:23] Thế thì nên là thì nên là anh Nghĩa à
[00:07:28] anh anh được tiên thì bây giờ để mà anh
[00:07:30] đi tìm điểm khác biệt giữa các hơi khó
[00:07:35] cách tốt thì có thể là anh cứ thành cái
[00:07:37] anh cứ từ chạy thử thấy cái đoạn nào lỗi
[00:07:38] thì
[00:07:42] Ừ anh nó sẽ báo cảnh báo lỗi tại cái chỗ
[00:07:45] đói thì anh anh chỉ cần là
[00:07:49] à à Tra Google là ví dụ là ví dụ nó cạnh
[00:07:52] thì báo lỗi Tại thằng in entity vì thằng
[00:07:54] trong máy Ware thì không phải lên Titi
[00:07:57] mà nó autoincrement được ạ thì mình chỉ
[00:08:00] cần cha ví dụ được mình chai indentity
[00:08:02] này
[00:08:08] tu à Máy kia chẳng hạn thì nó sẽ hiển
[00:08:12] thị luôn là auto increment này đánh chưa
[00:08:24] bác Đợi tí ăn cho no mà nó bên pha nhà
[00:08:27] con cho nó thường ai kiểu mở file mà
[00:08:30] nghỉ hai đều gãy I
[00:08:33] khi các con trùm report chưa Đợi mình tí
[00:08:38] Ừ
[00:08:41] anh mở chữa lại phải cũng ah
[00:08:43] Ừ
[00:09:01] xe Open em mỗi khi mình ở nấu tin được
[00:09:03] mà
[00:09:06] ăn cơm cho nó ăn chỗ nó bình thường mỗi
[00:09:08] khi vẫn được mình ạ
[00:09:11] nhạc karaoke ok
[00:09:15] thì à ở đây hôm trước mình có hỏi cái
[00:09:17] câu đó là tại sao
[00:09:20] thì các bạn lại để file Mickey ở dưới
[00:09:22] cho dù rõ ràng các bạn thì khai báo ngay
[00:09:24] trên này
[00:09:26] như thế này à
[00:09:30] Ừ thì có bạn nói là để cho nó trực quan
[00:09:32] cũng cũng là một tí nhưng thực ra thực
[00:09:34] tế cái này nó còn chưa quan hơn cho khai
[00:09:38] báo ở dưới và cũng như là có bạn bảo là
[00:09:42] để cho dãy sửa thứ cũng cũng không hẳn
[00:09:45] là sai nhưng mà cũng có bạn bình luận
[00:09:48] ngay ở dưới đó là choi minki là
[00:09:51] về sau nó sẽ cố định thường anh không
[00:09:53] đổi thế nên là cũng không có trường hợp
[00:09:58] mà về sau mình sửa file Mickey cái Rốt
[00:09:59] cuộc Tại sao wiki để cuối như thế này
[00:10:01] thực kế nó đơn giản thôi
[00:10:05] hôm trước mình có hỏi ở trong
[00:10:07] ừ ừ
[00:10:08] nhà
[00:10:11] mình có hỏi ở trong cái câu trắc nghiệm
[00:10:15] đó là triky thì nó là duy nhất một bảng
[00:10:20] chỉ có mụn khóa chính đúng không Nhưng
[00:10:24] có một khóa trinh đấy có thể chứa nhiều
[00:10:29] cột chưa Chính xác là nếu màn theo dịch
[00:10:32] ra À ấy và nó cậu dịch thôi nó không
[00:10:35] phải là cụt nữa mà nó là trường giá trị
[00:10:37] toàn bộ những cái này không là cụt mà nó
[00:10:40] thường giá trị thì một quá trình có thể
[00:10:42] chứa nhiều
[00:10:46] thị trường giá trị chưa tất cả xa ví dụ
[00:10:48] là do sửa mình hoàn toàn thể vừa làm mã
[00:10:51] vừa họ tên như này được nghĩa là cả hai
[00:10:53] cái này cùng Đọc khóa chính và cả hai
[00:10:55] cái này không được phép cùng lắp kiểu
[00:10:58] cầu Thế thì mình sẽ áp dụng cái đấy
[00:11:00] trong những trường hợp nào có chính hung
[00:11:03] sau mình sẽ hợp với khóa ngoại mình học
[00:11:07] về tách ra bảo ngày các thứ thì mình sẽ
[00:11:10] nói cụ thể hơn về vụ là một khóa chính
[00:11:13] chứa nhiều cột là như thế nào
[00:11:17] Khi nào nào vừa nói xong không được nói
[00:11:19] tạo nhiều hoa chính nhá nhiều phải chính
[00:11:23] là chữ thầy dạy chay thay đấy Không nói
[00:11:25] chuyện là nhiều khóa chính được chưa một
[00:11:27] bà chỉ có một quá trình thôi Mà một khóa
[00:11:31] chính Đấy chứa nhiều cột chưa Hãy dùng
[00:11:33] từ giá chuẩn nhé không đi phỏng vấn nó
[00:11:41] khi dùng Aspirin nofer cho toàn bộ ứng
[00:11:43] dụng được không Cái này tương tự gần như
[00:11:46] là câu hỏi các vào dùm em QR cho toàn bộ
[00:11:49] ứng dụng được không Cái bài toán nowhere
[00:11:52] nó vừa nãy mình khó nói qua một tí đó
[00:11:55] nói que vì là tốt nó tiện nó nhanh hơn
[00:11:58] so với queo nó hợp phù hợp cho những dự
[00:12:01] án rất là lớn theo kiểu là thứ nhất là
[00:12:03] theo kiểu free time là theo thời gian
[00:12:05] thực thì bắt buộc cả không cần nên at
[00:12:08] work kiểm tra về cái độ chặt chẽ của dữ
[00:12:09] liệu
[00:12:11] anh cũng như là Nokia thì phù hợp cho
[00:12:15] cái lưu lại ở trong một bảng có triệu
[00:12:18] hai hàng tỉ dữ liệu thì mình không thể
[00:12:20] Cứ mỗi lần mí do ta update thì mình lại
[00:12:21] ngồi kiểm tra xem nó tránh trùng được
[00:12:25] không cả bởi vì nó sẽ rất nặng và sẽ rất
[00:12:27] là lâu thì nên là phù hợp cho nó ghét
[00:12:30] wear.con lệnh Nếu thấy ngược lại là gì
[00:12:32] Apple lại phù hợp cho những cái bài toán
[00:12:36] mà các bạn là bài toán mà thực ra nó
[00:12:39] không lên lấy một triệu bản ghi các bạn
[00:12:41] không cần làm theo thời gian thực mà các
[00:12:44] bạn muốn độ chính xác rất là cao mà thì
[00:12:47] các bạn sẽ dùng iCloud giản thế thôi
[00:12:48] Ở
[00:12:51] đây có một bạn hôm trước có khuyên mình
[00:12:54] đấy này Thực tế là
[00:12:58] Ừ cái này nhà A ông ấy khuyến khích các
[00:13:00] bạn với tệ tạo tên mạng hay tên cột thậm
[00:13:02] chí bằng tiếng Anh đúng không tránh được
[00:13:05] thói quen xấu xấu về sau này hồi trước
[00:13:08] mình từng cạnh tranh cãi với 11 một
[00:13:10] người vào trong người câu lạc bộ của
[00:13:14] mình mình có khuyên sinh viên mình đúng
[00:13:15] kiểu nhà luôn đó là các bạn nên đặt tên
[00:13:18] biến là bằng tiếng Anh thì nó sẽ tốt Nó
[00:13:20] sẽ kiểu nó sẽ tránh bị mông lung nhưng
[00:13:23] mà chả đùa
[00:13:26] bởi vì tiếng Việt mình nó kéo đôi khi nó
[00:13:29] cứ bị Hơi hơi bị rừng già quá nó kiểu
[00:13:32] chi tiết quá nhưng mà cũng Dương ra từ
[00:13:33] tiếng Anh thì nó có đúng rồi còn những
[00:13:36] cái từ nó chuyên ngành để mà chuyên tả
[00:13:38] về cái đấy nhận sự ngắn gọn và dễ hiểu
[00:13:40] hơn bởi tiếng Việt không có dấu ở nóng
[00:13:43] cái phạm trù gì đó khó lắm
[00:13:47] thì có ông vào phần mác Ông ấy bảo là
[00:13:49] tại sao mày tiếng Anh mà tính khác hay
[00:13:53] gì đấy kết hợp với việc đã là cái đặt
[00:13:56] tên biến thì nó cũng Anh văn văn
[00:14:00] thực tế các bạn nên đề bằng tiếng Anh
[00:14:02] chỉ vì tiếng Anh của nó vốn là nó có
[00:14:05] chuyên ngành rồi thì các bạn kiểu nên
[00:14:07] thống nhất như thế thậm chí đương nhiên
[00:14:09] có những từ tiếng Anh đồng nghĩa nhưng
[00:14:12] mà đến một công ty thường là giống như
[00:14:14] mình vào cái công ty bên A thương mại
[00:14:17] điện tử này nó bắt buộc phải có những từ
[00:14:20] chuyên ngành của những cái từ thương mại
[00:14:22] từ đấy Và thậm chí ở bọn mình phải quy
[00:14:24] ước với nhau đó là mình chỉ dùng tên
[00:14:27] biển nó như này như kia để tránh việc cả
[00:14:31] kiểu mình kiểu ông này thì đặt tên kiểu
[00:14:34] này ông này là tên cũ Kia đúng không
[00:14:37] Nhưng mà lúc mới dậy cho các bạn như này
[00:14:40] thì các bạn còn đang đỡ bỡ ngỡ và mình
[00:14:42] tin là có nhiều bạn ở đây Rộng chữa
[00:14:44] tiếng Anh buồn tiếng Anh không hoàn là
[00:14:47] tốt lắm nên là mình mới đang dạy hết
[00:14:50] bằng tiếng Việt tự nhiên là về sau về
[00:14:52] sau cái gì mình cũng sẽ bắt các bạn phải
[00:14:54] trao Google của mình anh này đặt tự đặt
[00:14:57] mọi thứ bằng tiếng Anh các những thứ chỉ
[00:14:59] cho quen cũng không hoàn là khó lắm đâu
[00:15:04] bởi du lịch mình sẽ mình sẽ giải giải
[00:15:07] thích nói chung dịch hộ các bạn mà chỉ
[00:15:18] à nếu mình đặt n Vespa 50 mà nhập hơn 50
[00:15:21] ký tự theo ca có bạn trả lời ngay dưới
[00:15:23] lấy rồi Nhưng mình muốn trả lời luôn cho
[00:15:26] những bạn nào còn thắc mắc đó là nếu mà
[00:15:28] các bạn đặt như này sau đó các bạn Nhập
[00:15:32] hơn 59 tự thì nó sẽ cắt đi nó sẽ chỉ còn
[00:15:35] đúng 50 ký tự cho các bạn thôi nó khác
[00:15:36] với ngôn ngữ lập trình ngôn ngữ lập
[00:15:39] trình các bạn sẽ khai báo kiểu nghe được
[00:15:41] Nhưng mà nếu mà các bạn Nhập tối đa lớn
[00:15:45] hơn thì nó sẽ bị thông báo lỗi
[00:15:49] Ừ nó bị như thế anh ơi làm sao để mình
[00:15:50] lấy khách hàng
[00:15:54] Khi dòng thứ n trong bảng dai cái thứ mà
[00:15:57] hôm nay mình sẽ học là mình sẽ có khái
[00:16:00] niệm là bỏ qua bao nhiêu bạn thì lấy bao
[00:16:06] Ở đây có cách nào là khắc phục không anh
[00:16:08] kiểu bởi vì hôm trước mình còn nói về
[00:16:11] cái vụ là thằng máy quý ông ấy thì nó
[00:16:15] khi mà lấy theo tên thanhhhh hè thành
[00:16:17] thì nó lại biển anh không phân biệt có
[00:16:19] dấu cái này thì à
[00:16:20] Anh
[00:16:23] Đào Thị mình tra thử nhé tất cả mình
[00:16:30] chung kết
[00:16:33] đầu tiên là wei-mo mai que này
[00:16:38] sẽ chuyện này Unicode ạ
[00:16:39] a
[00:16:41] value gì Chắc mày ạ
[00:16:50] cho thuê xe Transit ngày ngon
[00:16:54] a cho xét này để mở lưu lại ngôn ngữ mà
[00:16:56] các bạn sẽ
[00:16:57] chị
[00:17:00] sẽ dùng chào sao
[00:17:11] Anh có ở đây nó không để cập
[00:17:14] anh ở đây có cái khái niệm có này mình
[00:17:17] đĩa con rết này sẽ được Đấy mình tăng dù
[00:17:19] con rết này order Bike Hôm trước mình
[00:17:22] còn nhắc qua về cái vụ là Anh
[00:17:26] tên Đức có chữ đời ấy còn tồn tại trong
[00:17:31] là tinh ấy nên thành ra là nó sắp xếp nó
[00:17:35] bị sai hoặc là tên tên tiếng Việt có dấu
[00:17:38] ý thì nó sẽ sắp xếp chung cuối của bạn
[00:17:41] chữ cái bởi vì nó không nằm trong bảng
[00:17:44] Latinh thì các bạn sẽ phải dùng cái crit
[00:17:48] này để mà sắp xếp nó theo tiếng Việt cho
[00:17:51] chuột ảnh kiểu thế
[00:17:53] thì mình nghĩ là chắc là were theo cái
[00:18:01] Hôm nay tôi đã có ông không bao giờ nên
[00:18:04] sử dụng utf-8 trong máy que rồi
[00:18:08] Chả liên quan hệ mai qua em à phải là
[00:18:10] utf-8
[00:18:12] MP4
[00:18:15] cái khi nào mình dậy Xanh Mãi với ai thì
[00:18:16] mình sẽ giải thích của mình cái vụ này
[00:18:18] nhé
[00:18:21] trong yêu tim ai là người toàn diện nhất
[00:18:23] vậy thầy
[00:18:26] Ừ cái cái này mình chưa ghe 8 giờ mình
[00:18:30] phải dậy rồi cho mình mình có nên là
[00:18:32] mình cái câu này cho mình đến cuối buổi
[00:18:33] nhé
[00:18:35] cô
[00:18:38] dạy kỹ năng cho Google cái này cuối bởi
[00:18:40] luôn đi
[00:18:44] mình có thể mình sẽ hướng dẫn về cả
[00:18:46] claire trong khóa này không ngoan lại
[00:18:48] khóa máy ảnh mà chính xác là mình sẽ
[00:18:52] hướng dẫn mình sẽ dậy để vào em có thể
[00:18:54] lúc đấy được biết độ Đông sinh viên hơn
[00:18:57] Bởi vì thực ra có nhiều người đã đi làm
[00:19:01] ở trong trong mình trong kênh của mình
[00:19:05] mà toàn Thiên Tài ẩn danh thôi
[00:19:09] Ừ cái này thì ạ Chắc là bạn mình khuyên
[00:19:12] các bạn nên tra Google Nhưng mà theo
[00:19:15] mình thì nó cũng có nhiều nét tương độc
[00:19:17] Bởi vì mình không làm thì cả hai ngày
[00:19:20] này Đây là có những cái câu ấy các bạn
[00:19:22] hoàn toàn hệ cha nó Nó kiểu như thế này
[00:19:23] trúng không
[00:19:28] với sẽ vs a xong các bạn sẽ thấy việc là
[00:19:34] con sẽ kiểu so sánh so sánh như thế nào
[00:19:36] à à
[00:19:40] ở đây mình có nốt lại ở đây cho bản thân
[00:19:44] mình thôi đó là đôi khi có những cái tra
[00:19:48] đấy Mình chưa kịp trả lời hoặc cả
[00:19:52] mình mình trả lời rồi nhưng có vài bạn
[00:19:54] góp ý ở trả lời cho em Trả lại trong cả
[00:19:58] kênh ngày nữa là các bạn trả lời đi giúp
[00:20:01] đỡ các bạn khác thì ra hồi mình đi học
[00:20:04] cũng thế Mình mình giúp đỡ các bạn khác
[00:20:07] rất nhiều nên à Tự Nhiên trình độ của
[00:20:09] mình cải thiện rất nhiều cũng như là
[00:20:12] mình biết cách để mà dậy dậy người khác
[00:20:15] kiểu thế Thành A Thầy mình thấy mình
[00:20:18] cũng có kỹ năng dạy là mấy cho mình đi
[00:20:21] dạy học kết hợp việc là khi mà
[00:20:24] em chọc đôi khi các bạn hiểu một vấn đề
[00:20:26] Để mà giải thích cho một người khác đi
[00:20:28] thì trình độ các bạn phải lên rất nhiều
[00:20:32] thế nên là cái đấy còn nhiều là tự ép
[00:20:34] bản thân này bạn thân mình giỏi hơn đấy
[00:20:37] Thế là mình khuyên các bạn là
[00:20:41] các bạn ngoài việc các bạn tự tự phấn
[00:20:43] đấu tự trau dồi vào kiến thức cho bản
[00:20:46] thân mình để cho mình hiểu thì có một
[00:20:47] cách nữa đó là các bạn đi Trả lời câu
[00:20:51] hỏi người khác thì cả sẽ bạn thân mình
[00:20:53] thấy cách đấy rất là phù hợp với rất
[00:20:55] nhiều người luôn ấy rất nhiều người cậu
[00:20:58] lên những cái dự các bạn thấy có rất
[00:20:59] nhiều diễn đàn về hỏi đáp trên hình về
[00:21:01] bên công nghệ thông tin này có cái sách
[00:21:05] đâu lâu rồi ạ Đấy bản thân toàn bộ những
[00:21:07] người này có thể là chưa chưa biết câu
[00:21:09] trả lời ngay lúc đấy nhưng mà đều tra
[00:21:13] Google và đều tự mày mò để mà tìm cách
[00:21:15] sạch giải quyết bài toán trả lời câu hỏi
[00:21:19] cho người ta và tự nhiên trình của họ
[00:21:23] lên rất cao và họ lại tự anh cũng và
[00:21:26] năng nổ hơn tự nhiên lại đam mê hơn bởi
[00:21:29] vì cái cảm giác giúp được cho người khác
[00:21:31] rất vui ngày khác Cảm ơn mình mình cảm
[00:21:35] thấy cũng có gì đó thấy vui nữa
[00:21:38] ở đỉnh cảm ơn bằng tiền là được mình tải
[00:21:46] Ở đây có bạn hỏi câu này cũng
[00:21:49] À hôm trước là mình nhớ cái bài toán là
[00:21:53] mình có kiểm tra là It's not luôn là để
[00:21:55] lấy ra tất cả những cái bạn mà có điểm
[00:21:58] đấy đúng không Bạn ấy bảo là mình kiểm
[00:22:00] tra điểm lớn hơn bằng 0 được không Thực
[00:22:03] ra là trong trường hợp này vẫn nhận vẫn
[00:22:05] chạy được không Bởi vì rõ ràng là điểm
[00:22:08] của mình đang nằm trong bé
[00:22:12] thế giới hạn từ 0 đến 10 và đúng là luôn
[00:22:15] Nếu mà nôn thì không thể nào mã lớn nó
[00:22:18] bạn không được Nãy có một tí cũng khá
[00:22:19] hay nếu mà bạn nào chưa biết về ít nó
[00:22:22] luôn Nhưng mà việc so sánh như này thì
[00:22:24] ra nó không tốt bằng nghĩ nó nôn Và đôi
[00:22:27] khi là sẽ sai ví dụ lần sử trong trường
[00:22:30] hợp này không phải là số nữa là trong
[00:22:32] trường hợp là chuỗi là Nhạn thì các bạn
[00:22:34] so sánh cái này thì không biết So sánh
[00:22:36] nào sâu xanh với chuỗi rỗng mà nó không
[00:22:41] anh ở đây có bạn hôm trước góp ý Minh
[00:22:43] dịch vụ là không biết là góp ý không
[00:22:47] Theo mình thì nó sẽ giữ góp ý đó là
[00:22:51] anh đánh máy nhanh cốt không theo nhưng
[00:22:54] mà có thể là à
[00:22:57] A gọi mình mình nốt ở đây vụ này vì mình
[00:23:00] định nói qua các bạn thì nhất à các bạn
[00:23:02] cũng nên gõ mảnh nhanh một tí bởi vì
[00:23:05] mình thấy nhiều bạn thì ra gõ mày cũng
[00:23:07] cũng không không nhanh lắm Thực ra nó
[00:23:10] ảnh hưởng thứ nhất à hiệu quả công việc
[00:23:13] đúng không năng suất các thứ cũng như là
[00:23:14] các bạn sẽ bị lừa
[00:23:18] Ý mình nói là các bạn sẽ bị lười đi kẻo
[00:23:21] lại có nhiều cái đoạn mà kiểu các bạn
[00:23:23] hãy nó bị dài quá giống như làm bài tập
[00:23:25] cùng mình các bạn đôi khi thấy bài tập
[00:23:28] của mình nó thể lên đến gần trăm dòng
[00:23:31] thậm chí hơn trăm dòng các bạn gõ chậm
[00:23:35] thì sẽ nghĩ rằng à buổi là bài này mình
[00:23:38] mới gõ cho hơn Tiếm thì các bạn sẽ bị
[00:23:42] lạc thì các bạn phải phải làm mất cái
[00:23:45] suy nghĩ thì đi bằng các bạn Luyện gõ nó
[00:23:47] ngon thứ nhất là hồi trước mình thường
[00:23:49] ai bảo đó là một là các bạn lên trang
[00:23:52] theo phạm ạ
[00:23:55] à Thèm phem single này đúng không luyện
[00:23:57] gỗ Bình thường anh lên để luyện gõ này
[00:24:00] nó có phiên bản tiếng Việt hoặc tiếng
[00:24:02] Anh mình chưa quen gõ tiếng Anh thì mình
[00:24:05] gõ tiếng Việt thôi tại mình thấy lượng
[00:24:06] gõ trên này
[00:24:11] cái Luyện gõ trên này thì vào nhà nghỉ à
[00:24:14] khi mình gõ được cũng tầm 90 từ một phút
[00:24:17] đấy Căng nhất là như thế thì các bạn
[00:24:18] cũng không cần phải nhớ Thiên như thế
[00:24:22] các bạn chỉ cần nên gõ tầm đền á á
[00:24:27] ờ ờ thường là 60 từ 1 phút là rất là ổn
[00:24:28] rồi
[00:24:36] U60 từ một phút tất cả một giây một từ
[00:24:40] thì rất là ổn rồi sẽ được các bạn đừng
[00:24:42] nên gọi chậm quá bởi vì thứ nhất à nhưng
[00:24:44] mình nói giảm hiệu suất đúng không Thứ
[00:24:46] Hai thật trông nó không ngầu kiểu gì thế
[00:24:51] vì thực bởi vì a các bạn vì sau gõ gõ mà
[00:24:53] tự như cứ phải cúi xuống nhìn bàn phím
[00:24:57] Ngạn này Các rỡ thứ từ ra nó không ngầu
[00:25:00] nhưng mà trừ khi thực ra thì nói thế
[00:25:02] không phải để các bạn tự ti đâu vì thực
[00:25:05] tế đó Cái người thầy của mình hôi trước
[00:25:09] mình từng nói ngày anh thấy mà cứ nhanh
[00:25:10] lên phim Bất Hủ để cho các bạn hãy nhớ
[00:25:12] đúng không thìa
[00:25:16] canh Face đấy Anh thấy gỗ máy ra chậm
[00:25:19] luôn và thượng chỉ là con nhìn xuống hả
[00:25:21] mắn phím mì gõ cơ nhưng mà anh đấy gõ
[00:25:24] cốt để đâu chắc nhìn đấy nên làm thực ra
[00:25:26] chẳng có ý kiến gì cả vì anh ấy gõ chậm
[00:25:27] nữa
[00:25:29] anh không nhanh nhậu đong ấy kiểu đấy
[00:25:32] nên là anh ấy vẫn ngầu trong mắt mình
[00:25:36] nhưng thực sự thì gõ nhanh trông ngầu
[00:25:39] hơn mà đúng không ạ
[00:25:43] à à Ừ cái ghét bếp này
[00:25:46] anh làm Em định lấy ngày tháng thôi
[00:25:47] không nhận định phần tham được không ạ
[00:25:50] Đây cái mà hôm nay mình sẽ chữa bài tập
[00:25:53] luôn này gì tí mình chữa mình sẽ trả lời
[00:25:55] trong e có sử dụng được vào làm không
[00:25:58] Anh thực ra mãi về sau mình mò được Đúng
[00:26:00] là anh theo nó vừa gọi ít theo này vừa
[00:26:03] vòng lặp này thậm chí vừa có cả khai báo
[00:26:06] biến nên là mình thấy à iCloud bây giờ
[00:26:07] nó nhanh mà ngôn ngữ lập trình mới dồi
[00:26:10] vì ngôn ngữ lập trình thực ra nó cũng
[00:26:12] chỉ có những cái điều đấy thôi
[00:26:13] Ừ
[00:26:18] thì mình nghĩa là ở các bạn học em queo
[00:26:19] này xong sang bên ngôn ngữ lập trình
[00:26:23] thật chứa sẽ dễ hiểu
[00:26:26] Ừ cái đít tuần nào mày biết xảy ra đây
[00:26:27] Ờ Ờ
[00:26:30] cái này thờ ra là có nhiều câu thì mình
[00:26:32] nghĩ là các bạn nên tự chiêm nghiệm tự
[00:26:36] chạy thương thay vì họp cũng cũng là một
[00:26:38] cái để mà tự học đúng không nghe mình
[00:26:40] trả lời nhanh ở đây là không
[00:26:43] piston là lọc Chung đấy Cái vụ ông chưa
[00:26:45] Mình nói về lập chung ấy ra nó mình thử
[00:26:47] mình cũng phải thử lại luôn lúc đấy Và
[00:26:50] kết quả là không nó không để lọc Trùng 2
[00:26:52] cột cùng lúc
[00:26:55] đây hôm nay mình nhớ mình hứa các bạn về
[00:26:57] cái vụ hết không cha đến cuối cuối buổi
[00:27:00] nhé các bạn Nhớ nhắc mình nhé Và thậm
[00:27:03] chí cuối buổi mà có ông làm mà rời đi
[00:27:05] thì càng tốt cho ngon tôi sẽ nhắc vụ
[00:27:08] khách khủng rau cùng cho mấy ông thấy
[00:27:08] hối hận
[00:27:13] ai Hôm trước mình có mình có trả lại thì
[00:27:14] nó là khái niệm kham.tam Minh Attack
[00:27:17] Attack ở tấn công mà nó nó không nhắc
[00:27:20] ngay hậu gì đây cả nhưng mà tên này
[00:27:22] khẳng định việc liên quan đến thăm Minh
[00:27:25] là là thôi gian đúng không là đo lường
[00:27:28] thời gian để tấn công thì các bạn trai
[00:27:30] ngay từ tiêu đề này nó sự ra luôn bài
[00:27:33] đăng đấy các bạn thì đọc trước nhưng mà
[00:27:35] có thể các bạn sẽ thấy hơn mông lung khó
[00:27:38] hiểu thì để tí mình khử nó lại theo ý
[00:27:40] hiểu của mình thì bạn sẽ thấy nó hay như
[00:27:43] thế nào
[00:27:48] Hôm trước mình có nói vụ là tách tên ra
[00:27:53] tất cả họ cả tên ra đúng không tay mình
[00:27:54] thức mở lại các bạn đấy
[00:28:04] dự án xử tên là sử các họ tên là mẹ năm
[00:28:09] đấy ạ thì tách tên ra bởi dấu phẩy do
[00:28:12] cách thì bạn ấy bảo dùng gạch được không
[00:28:15] Nếu bạn trai với gạch thì nó sẽ không
[00:28:17] phải ngôn ngữ lập trình thời gian nó
[00:28:20] biết nó còn la la giống như em quen
[00:28:21] thằng Tí Nó kiểu nó liên quan đến việc à
[00:28:26] truy vấn và truy vấn và kiểu lọc dữ liệu
[00:28:28] nhưng mà
[00:28:31] có bạn trả lời ngay dưới đấy gạch là bài
[00:28:33] toán rất là khó thực ra là càng tìm hiểu
[00:28:36] nó cái mông lưu thì đúng cách này rất là
[00:28:39] nhằm à có những hạn chế giống với cách
[00:28:41] này bởi vì thực ra nó còn liên quan đến
[00:28:46] Ừ ừ
[00:28:49] em hai năm tránh ảnh giờ muốn quay lại
[00:28:52] IP thì nên làm gì chứ sắc là các bạn nên
[00:28:55] nên học gì học học gì và cảm thấy cái gì
[00:28:58] phù hợp rồi mình làm thôi đúng không À
[00:29:02] và thực ra là các bạn học cái ngành này
[00:29:04] như mình đã nói từ các bạn không nên
[00:29:07] quan tâm tại bộ quan tâm về tuổi tác hay
[00:29:10] á các thứ thứ thì mình mình cũng không
[00:29:12] không nên so sánh bạn thân mình phải bất
[00:29:14] kỳ ai mà đúng không nghỉ ngơi số sàng
[00:29:16] với chính mình đó là mình sau vài tháng
[00:29:18] mà mình không mang họ thêm được gì thì
[00:29:20] mình cho mình cũng nên xem lại đúng
[00:29:21] không có gì Nó không phù hợp với mình
[00:29:24] thật hay à mình không tìm được đúng
[00:29:27] người để mà dậy mình 2 á Gì gì đó
[00:29:31] Ừ ừ cách viết CV chắc là nhà mình hôm
[00:29:34] nay có khi là bây giờ bị Hơi bị quá đi
[00:29:38] ra rồi này chắc hôm nay cũng không không
[00:29:41] hướng dẫn các bạn về vụ VC được Chắc lại
[00:29:44] nợ bụi khác nữa nhé ạ
[00:29:47] Ừ cái này Trả Lời Một Câu Hỏi thì bây
[00:29:49] giờ đến lượt Chữa bài tập nhạc không lời
[00:29:52] hay quá Bộ mày không không biết được bộ
[00:29:56] của mày nó sẽ lên hơn 2 tiếng mất
[00:29:59] sẽ mở bài tập lên thì chữa nhé
[00:30:02] Chiều cao là bài tập này số kết hợp buổi
[00:30:04] hôm nay thư da là cũng phải dựa vào cái
[00:30:06] bài này mình mình thường hay làm bài tập
[00:30:21] ấy Mình đã cố viết bài tập theo kiểu
[00:30:24] dạng là là nó là một cái giống như một
[00:30:26] vài giá thực tế thì các bạn đọc về đỡ bị
[00:30:30] kiểu Cảm thấy nhàm chán không ăn thực tế
[00:30:32] rồi Như này xét và chẳng biết được và
[00:30:35] các bạn cần phải lưu ý gì cả thì cái
[00:30:37] mình có ghi thêm một vài điều kiện ở đây
[00:30:41] là nó cũng tương đối màu cho các bạn để
[00:30:42] các bạn biết phải lưu gì rồi thực tế
[00:30:45] không mấy cái này hiền nhiên là dụ là
[00:30:47] không được xét chung rồi cái nhiên có
[00:30:50] này hay là nguyên lương là phải số dương
[00:30:53] là chỉ nhiên có này hay gì đó đúng không
[00:30:57] ngày à tất cả cô không được để trống này
[00:30:59] chẳng hạn đúng không
[00:31:02] tiên nên mình cứ trả bạn đúng không Thì
[00:31:04] tao mạng là
[00:31:08] bạn kết với bồ nhân viên em ạ
[00:31:14] mã pin thì đem tt rồi à
[00:31:26] Anh tên là ngon
[00:31:38] đây mình có nhắc đến tuổi phải ra các
[00:31:40] bạn ốp luôn tôi mà các bạn không nên đọc
[00:31:42] nên cuối
[00:31:44] ừ ừ
[00:31:44] a
[00:31:48] beautiful CPU và Phong Trần Thế chắc ạ
[00:31:50] Bạn phải đợi hình tầm phải 56 buổi nữa
[00:31:52] là ít
[00:32:00] Ừ thì các bạn thấy ở đây rõ ràng mà mình
[00:32:03] có đề cập liên quan đến thứ nhất là xinh
[00:32:05] tháng này nhìn nó sẽ không thể các bạn
[00:32:07] lưu lại tuổi Thứ hai là hôm trước mình
[00:32:09] em hỏi qua các bạn là các bạn hạn chế
[00:32:12] nên lưu tuổi bởi vì ạ Các bạn lưu tuổi
[00:32:15] xong thì sang năm thì các bạn lại Mất
[00:32:16] công cập nhật lại tuổi thì thấy không
[00:32:26] vợ chồng ơi hôm sau chắc chắn nó sẽ phải
[00:32:28] nói quay Mickey và full key anh cũng hết
[00:32:37] giới tính này là là bit chẳng hạn đúng
[00:32:40] không Thì mà để khô là nữ thì tra để tôi
[00:32:46] từ
[00:32:48] ngày vào là này
[00:32:51] là đến này
[00:32:55] là ghét Tết là mặc gì ra hôm nay đúng
[00:32:58] không ạ
[00:33:03] có nghề nghiệp chọn là kiểu bởi vì để
[00:33:06] chữ và có dấu đúng không Thì sẽ là nấu
[00:33:09] phải tra là ạ mà đến 50 Thực ra thoải
[00:33:16] tất cả cột không để chống cái nón luôn
[00:33:20] nôn nôn nôn này à
[00:33:21] à à
[00:33:24] ạ sau khi mà các bạn làm xong hết rồi
[00:33:27] thì các bạn mới bắt đầu làm chết nhá cho
[00:33:29] nó ô và bây giờ sẽ là
[00:33:31] con sự chết
[00:33:34] con sự trên như vậy
[00:33:35] trên
[00:33:38] là
[00:33:41] hôm trước anh mình thấy có tên Kiểu như
[00:33:44] anh để viết tắt ngọn rất là dễ hiểu ngon
[00:33:46] à
[00:33:49] Cái quan đến lương
[00:33:50] đi
[00:33:53] thi à chất lương
[00:33:56] nguyên dương
[00:33:59] chất lương Là
[00:34:02] Đớn bằng không đúng không nó sẽ Nguyên
[00:34:02] Dương
[00:34:04] tiếp theo
[00:34:09] Hà Đông chưa Út lương không Lương thì
[00:34:11] nếu mà các bạn cho người Việt thì rõ ra
[00:34:15] là lương bằng kiểu y là được rồi Không
[00:34:27] Anh tên này à
[00:34:30] chế độ dài Tây nhà bạn ạ
[00:34:33] khi gà llorente đúng không
[00:34:36] lẽ hôm trước mình chỉ rồi nó là để lấy
[00:34:40] độ dài của của chú ếch đúng không ạ
[00:34:43] à à
[00:34:46] Ừ cách mình sẽ copy đây cho các bạn diễn
[00:34:47] Nhi này
[00:34:49] à à
[00:34:50] a
[00:34:52] tiếp theo tuổi
[00:34:53] có
[00:34:57] phải lớn hơn 18 đúng không thì tôi sẽ ra
[00:35:05] cũng được
[00:35:07] nếu các bạn bè nha cũng được không sao
[00:35:11] cả em đôi khi nhìn kìa này nó dễ bị mông
[00:35:14] lung để mình đang định như thế này còn
[00:35:16] tuổi này thì chắc à
[00:35:24] Ừ nhưng mà thực ra mình thường Anh không
[00:35:30] thích kiểu để cho cái số số hẳn ở trong
[00:35:33] cái tên của một cái gì đó như này bởi vì
[00:35:35] sau nếu mà các bạn sữa số ở đây thì các
[00:35:38] bạn ở phía sửa lại tên đấy do mà chỗ này
[00:35:40] thì chửi là chắc độ dài tên cũng giống
[00:35:43] như tuổi đây Mình chỉ muốn ngắn gọn là
[00:35:44] chị tuổi thôi
[00:35:48] hơn là mình ghi hẳn là lớn hơn 18 ở
[00:35:51] trong này thì về sau mình đổi tuổi là sự
[00:35:53] đổi muốn đổi lên hay mưa tuổi mới được
[00:35:55] cả thì mình lại thay đổi tên của cái này
[00:35:58] nữa Thực ra thì cũng tốt
[00:36:00] nhưng mà công nhận là nhìn kiểu như thế
[00:36:03] nó tưởng minh hơn thật à
[00:36:06] ở đây là có bạn nhiều bạn dùng là đét
[00:36:10] đít cũng được hoặc là dùng kia mình
[00:36:12] thường anh nhớ để cái vụ làm thì dùng về
[00:36:23] tình
[00:36:26] yêu của ngài sinh đúng không
[00:36:35] à à
[00:36:49] mặc định là nữ rồi ngày vào làm mặc định
[00:36:53] hôm nay đúng không Để hôm nay rồi
[00:36:55] à à
[00:36:57] có nghề nghiệp phải nằm trong danh sách
[00:36:59] này đúng không nằm trong danh sách thành
[00:37:02] đạt đúng không Thì mình sẽ đã
[00:37:06] copy cái này à
[00:37:10] nghe được câu này cũng mình thấy gần như
[00:37:12] các bạn đều có nhiều cách để làm rượu là
[00:37:15] ở đây là
[00:37:19] các bạn một là các bạn dùng theo kiểu là
[00:37:23] Wave in trong cái danh sách được thưởng
[00:37:25] như này các bạn copy luôn được cái này
[00:37:27] của mình rất tiện
[00:37:29] nằm trong cái danh sách này đương nhiên
[00:37:31] phải thêm chữ N lần trước đúng không rồi
[00:37:35] vì nó có dấu hay là các bạn o
[00:37:38] đây baba phát thì mình thấy là thực ra
[00:37:40] là cái này cũng được nhưng nghe các bạn
[00:37:42] hãy thứ nhất là cốt các bạn nói chồng nó
[00:37:46] dài hơn ra là cho nó không về tốc độ xử
[00:37:49] lý cho nó không nhanh bằng in khuyên các
[00:37:51] bạn vì sao mà chỉ có o như thế các bạn
[00:37:57] cho tất cả cột không được để trống rồi
[00:38:00] này mã nhân viên không được phép chung
[00:38:02] thì nó là khóa chính mà Đúng không nhỉ
[00:38:04] sẽ family kia thôi
[00:38:07] Mình thực ra là các bạn để ý nên ti tự
[00:38:09] động tăng này thì các bạn cũng sẽ không
[00:38:11] trùng rồi
[00:38:14] nhưng mà bảo nào cũng nên có khóa chính
[00:38:26] xin lỗi ở đây cạnh này nó sẽ bị lỗi cậu
[00:38:36] Bên mình à
[00:38:38] ở công ty còn 5 nhân viên đúng không Ok
[00:38:40] 5 nhân viên tất cả mình sẽ in search
[00:38:45] đúng không Insert into nhân viên này
[00:38:47] sau đó đi mình sẽ truyền đầy đủ thông
[00:38:59] bạn lương chẳng ạ
[00:39:01] Alo là
[00:39:04] vẫn đó điều khúc lọng anh Long rồi anh
[00:39:09] 197 này
[00:39:13] 0101 này được tính một này ngày vào làm
[00:39:16] thơ ngày giờ làm có bạn hôm trước làm
[00:39:21] rất là Ôi nếu mà một là các bạn cho nhập
[00:39:22] vào ngày và làm
[00:39:25] như này mà các bạn muốn dùng đấy phô ấy
[00:39:27] thì các bạn sẽ phải ghi hẳn để phô như
[00:39:31] thế này để hiểu là mình muốn nhập vào để
[00:39:34] for còn hay là các bạn sẽ phải không
[00:39:37] nhập Thì nó sẽ hiểu lầm Chỉ cách vẽ hai
[00:39:40] cách hiểu chưa
[00:39:45] nghề nghiệp nghiệp thì mình hái thì ông
[00:39:51] bà lương thì đã ra sự là cho 100 đi thế
[00:39:53] cơ à cách để mình rất hiệu quả là các
[00:39:55] bạn đến trang ai mà xem ngay những cái
[00:39:57] câu ở dưới này có liên quan thì cái gì
[00:39:59] đúng không
[00:40:02] ở đáy Ví dụ ở đây Xóa những bạn nào
[00:40:04] lương dưới 50 lại chẳng gặp thì kiểu gì
[00:40:06] tí các bạn cũng nên có một ông nào đó
[00:40:09] lương dưới 50 nó xóa đúng không chẳng
[00:40:12] hạn thế nhớ cả là mới vào làm hai tháng
[00:40:14] dưới hay đánh ấy chứ chán lắm Mình sẽ
[00:40:17] phải có một ông như thế là đúng không Để
[00:40:22] và hai shop là lấy tổng tiền mức lương
[00:40:24] rồi trả theo từng nghề chuẩn thì ấm chị
[00:40:27] phải có nhiều Nghe gì Gì đấy mới vào làm
[00:40:30] hôm nay tất cả phải có người và lắm Hôm
[00:40:38] ở ngã bạn hiểu ý mình mà đúng không ạ
[00:40:40] à à
[00:40:44] Minh Tuấn
[00:40:48] sinh năm 2000 tí nữa không Bây giờ làm
[00:40:51] đặc sắc mà xin lỗi em
[00:41:02] lương để anh đấy à sản là thành đạt thì
[00:41:08] hơn mình rồi Ngon tên anh ạ
[00:41:10] ở gà
[00:41:13] thí sinh tháng này nó có mạng sinh tháng
[00:41:16] này là tháng 9 cho bạn ơi xin anh 09 là
[00:41:20] nó ngon thì nha Một này
[00:41:21] a
[00:41:25] cho bạn đấy dưới 50k đi làm rộn 30.000
[00:41:30] nhận cái là làm kế toán đi à
[00:41:39] có mình mình nghĩa Ba bạn như này cháu
[00:41:42] Ổn nghỉ thì anh Sơn nhé chắc không lỗi
[00:41:46] gì đâu kêu thôi tiếp theo
[00:41:49] những tháng ngày sinh nhật sếp có ông
[00:41:52] đọc đề của tôi không kĩ nhá tháng ngày
[00:41:55] sinh nhật sếp tức là ông phải chị
[00:41:58] khi tăng lương cho những bạn nào sinh
[00:42:00] tháng này thôi đúng không có ông thì làm
[00:42:02] theo tuổi thì rất là nó không có cái này
[00:42:06] sinh rồi Cái thứ nhất thứ hai là
[00:42:08] ông Tăng lương mới tất cả mọi người sẽ
[00:42:11] hơi say quá không đăng ký đây không chỉ
[00:42:14] xinh cho thằng này thôi thì ở đây mình
[00:42:17] sẽ làm đầu tiên à tăng lương thì thành
[00:42:19] 100 Tức là mình sẽ cập nhật Lương thành
[00:42:22] 100 đúng không là mình sẽ cập nhật cho
[00:42:24] nhân viên này ngon xét
[00:42:28] lương được ạ bằng 100 đi á đúng không
[00:42:30] Đấy ông ấy làm chứ ngắn gọn như thế này
[00:42:33] tất cả ai cũng đổ hết luôn à 100 thì đã
[00:42:35] sai đúng không
[00:42:39] đi à
[00:42:42] thì các bạn phải đọc lại đó là xinh
[00:42:45] tháng này đúng không là Wave ăn của ngày
[00:42:47] sinh
[00:42:52] bằng măn của ghét bếp tức là của tháng
[00:42:55] này này đấy cậu ấy Thực ra nó gần nghiệm
[00:42:59] của sao luôn Nếu chứ Nhưng mà thực ra là
[00:43:01] mình mình làm cái này suốt rồi mà đúng
[00:43:02] không
[00:43:07] khi chạy thử nhỉ
[00:43:10] ở đó có một ông được đồ rồi đúng không
[00:43:13] xem lại xem ông đấy ông nào nhé Chứ sao
[00:43:16] form nhân viên này xong rồi que đúng cái
[00:43:24] ở đó bạn tên anh rồi bạn ơi được đổi
[00:43:28] có
[00:43:30] phải thì à
[00:43:36] Ừ Ok bạn tên Anh bạn được vừa được cập
[00:43:39] a tiếp theo tăng lương cho mỗi bạn thêm
[00:43:41] 100 Nếu là câu xa là đúng không Ok làm
[00:43:52] ạ bây giờ sự lá làm bài toán tăng lương
[00:43:53] ra sự là
[00:43:57] Ừ cái này của Ý ý câu ý của câu sau của
[00:44:00] mình đang hiểu hiện đó là mình tách
[00:44:03] riêng so với cái câu này làm có mới nhé
[00:44:05] nghĩa là không thành một trăm nữa mà
[00:44:08] tăng lương cho tất cả các bạn thêm 100
[00:44:12] nghĩa lớn cũ Lương lưng
[00:44:16] lương sẽ bằng lưng lương cũ cộng lên 100
[00:44:21] hiểu chưa Ừ thì nó sẽ là có bạn dùng
[00:44:22] cộng bằng
[00:44:24] anh Minh chạy ở trên máy minh thì không
[00:44:27] chạy được không biết được và chạy được
[00:44:31] đấy À thế à Thế lại lừa rồi tại sao lúc
[00:44:32] đầu mình chả được nghỉ
[00:44:40] em ở đường này được thế dùng cộng bằng
[00:44:44] được nhưng mà các bạn nếu mà bạn mới học
[00:44:45] lập trình các bạn sẽ không hiểu cổng
[00:44:47] bằng là gì đúng không Mình cứ ghi rõ ra
[00:44:51] cho các bạn dễ hiểu đã
[00:44:54] cái này của vụ là cặp cái này Các bạn
[00:44:56] nhìn nó hơi bị bay não tí Nếu nó gọn cho
[00:44:59] hợp lập trình tự nhiên lương tự nhiên a
[00:45:03] = a + 100 nghe cái này hơi sai với toán
[00:45:05] học nhưng mà cái này nó sẽ hiểu cái bên
[00:45:08] trái này nó sẽ ra cái giá trị mới mà
[00:45:12] đúng không còn cả giá trị mới này sẽ
[00:45:14] bằng cái gì cũ cộng với nhau thoải mái
[00:45:16] được những thành ra nó thành ra kiểu như
[00:45:20] này về chưa ạ
[00:45:23] ờ ờ ờ thì cái này để các bạn dễ hình
[00:45:26] dung hơn thì các bạn đã chắc phải làm
[00:45:29] nhiều thôi đúng không ạ
[00:45:37] chứ còn cái gì nữa nhỉ
[00:45:38] khi
[00:45:40] cháu vừa được tăng lương đúng không
[00:45:43] những câu sau dịch ra khó khăn các phạm
[00:45:45] nhân sự luôn rồi Hơi tiếc
[00:45:48] cho nghỉ việc bạn nào lương về 50 Thực
[00:45:51] ra là mình lỡ tăng lương bạn kia rồi mà
[00:45:53] thành ra bây giờ thì ra là xóa thì cần
[00:45:56] lượng chẳng có bạn nào cả Thử nha phạm
[00:45:58] nhân viên hoặc
[00:46:02] Where lương nhỏ hơn 50 gì ngắm cái này
[00:46:05] thực ra lại rất dễ so với cậu chết không
[00:46:07] có bạn nào chẳng hạn ngờ bây giờ đến câu
[00:46:10] sau này xóa cả bạn vừa mới thêm 100 nếu
[00:46:13] lương cũ dưới 50 đúng không
[00:46:16] tất cả sao nghĩa là xóa luôn cả những
[00:46:20] cái bạn mà chính xác làm ý câu này của
[00:46:22] mình thì e liên quan đến cái câu À cậu
[00:46:27] màn câu này là Ừ cái bạn vừa mới thêm
[00:46:30] đấy nghĩa mà những bạn sinh tháng này
[00:46:32] vừa được tăng lương thì mình kiểm tra
[00:46:35] xem là lương cũ nó dưới
[00:46:38] U50 không Mình cũng đuổi những kẻ mang
[00:46:40] tiếng là sinh nhật cùng của xếp nhưng mà
[00:46:44] lương giờ 50 to lắm không không không
[00:46:47] đáng thì ở lại cho cơ thể
[00:46:50] thử nhé
[00:46:53] anh nói thế đấy không không xúc phạm bạn
[00:47:00] Ừ
[00:47:03] thì mình sẽ chỉ đơn giản như này không
[00:47:07] Mình sẽ về nhà em em thêm cái này nữa
[00:47:13] à à
[00:47:15] Ừ nó đương nhiên là lương trong trường
[00:47:17] hợp này mình sẽ là
[00:47:20] 50 + 100 đi Nếu là sự các bạn không biết
[00:47:23] làm choáng mà không muốn làm toán hoặc
[00:47:25] là làm toán một cộng một bằng hai cũng
[00:47:26] phải dùng máy tính cả thì các bạn làm
[00:47:28] như thế này máy tính có tự động tính hộ
[00:47:33] cho bạn không như là chạy như này thì sẽ
[00:47:35] không Bạn là bị xóa bởi vì vừa nãy còn
[00:47:37] cho tăng lên phát nữa để bạn lên hẳn bao
[00:47:39] nhiêu tiền chứ đúng không
[00:47:43] các bạn anh nhớ lên hẳn lên Sư Tha nhà
[00:47:46] 200 mất rồi Ngon
[00:47:50] ở nhà bạn hiểu ý mình mà Ngọc bây giờ ở
[00:47:53] Nếu mà trong trường này có thể xóa bạn
[00:48:00] cả hai con này sẽ giành độc lập nha
[00:48:03] nghĩa là xóa thêm bạn chứ không không
[00:48:05] ghét vào công này được vì con này cứ
[00:48:09] chạy trước đã rồi mình đừng con này
[00:48:11] anh không ý đôi khi nó sẽ bị sai bởi vì
[00:48:12] có những bạn chưa thì được tăng lương
[00:48:15] cũng bị bay màu mới rồi bởi vì mình thấy
[00:48:17] có bạn vài bạn trả lời thì mỗi ngắn gọn
[00:48:19] ngay thôi chị em chuyển bay luôn cả
[00:48:20] những bạn mà không thể tăng lương nữa
[00:48:22] không thể tăng lương Nhưng máy bay rồi
[00:48:25] hơn cự thạch anh
[00:48:27] ờ
[00:48:31] ờ còn câu sao thì không nhỉ
[00:48:33] anh ở đây đây
[00:48:39] đuổi cả nhân viên mới vào làm hai tháng
[00:48:42] có mày hay sao nhưng mình mình thấy rất
[00:48:44] nhiều bạn xài được đâu nhỉ Có chết mà
[00:48:45] cũng lời được hòa cha không hiểu điều
[00:48:49] này đây mình sẽ chỉ ra là
[00:48:50] em
[00:48:53] làm hai tháng đúng không Thì mình sẽ
[00:48:57] phải ở có khái niệm là đấy tháng hiện
[00:48:59] tại -
[00:49:02] 3 - tháng mới vào làm đúng không
[00:49:03] Ừ
[00:49:06] nhưng mà thực tế thì nếu mà bạn mà ghi
[00:49:09] như thế này thì cái hơi bị sai này các
[00:49:12] bạn dùng hàm kết bếp như thế này để lấy
[00:49:16] tháng hiện tại đúng không - mâm của
[00:49:19] ngài và làm này
[00:49:23] không nói lớn hơn hai này Alo nhỏ hơn ai
[00:49:26] mà mua như này nó bị sai tại sao là sai
[00:49:29] bởi vì là ra xử này vào làm của các bạn
[00:49:33] là là gia sửa tháng 9 rồi Đúng không
[00:49:35] ngày và làm các bạn cũng là tháng 9
[00:49:37] nhưng mà từ năm ngoái
[00:49:40] ý thì cái này thử nó vẫn sẽ ra là bằng
[00:49:43] không tất cả các bạn vẫn sẽ bị loại là
[00:49:47] thế sai này ngon thì chuẩn nhất thì các
[00:49:49] bạn lần này các bạn đã buộc phải đến đít
[00:49:52] là - theo một khoảng thời gian nào đó
[00:49:55] mình sẽ là - thèm ăn này sau đó restart
[00:49:59] thì đây là sẽ ra ghét bếp này sau đó thì
[00:50:00] đây là
[00:50:04] ngày vào làm này nhằm chuẩn này
[00:50:07] đúng là hay bị ngược lại nhé Mình không
[00:50:17] thì mình phải lỡ cho cả ba bạn đã bị
[00:50:21] Phong mới rồi mình thử Insert lại à mỗi
[00:50:22] bạn
[00:50:23] Ừ
[00:50:27] tự nhiên mình bị Delete bay hết nhỉ Ừ cứ
[00:50:29] thử chạy cho em có bài hết không nha Ok
[00:50:32] cả ba bạn đều bay đúng không Thì tức cả
[00:50:34] Chứng tỏ là cốc này chạy được Chắc thế
[00:50:37] thay đổi lại này
[00:50:40] cho bạn ấy vào làm chậm trễ và làm bằng
[00:50:42] tương lai đường mà kiểu
[00:50:43] áo kiểu dạng là
[00:50:47] bạn đấy đăng ký trước kiểu tháng xong
[00:50:50] nhận việc hay đại loại thế đúng không ta
[00:50:52] tháng 10 nhãn 01
[00:50:56] em và bạn này thì làm từ năm ngoái đi ai
[00:51:02] không không mà tháng 9 9 0 1 có bạn này
[00:51:03] cứ mặc định Bphone đi để xem Rốt cuộc
[00:51:12] anh à Nếu mà thứ ra làm bằng
[00:51:15] vì tương lai như này có khi hơi sai nữa
[00:51:23] đổi đuôi việc trước để thư giãn nhé
[00:51:26] U13 bạn bị thế sai mới dòm ngó
[00:51:28] Ừ chim to là mình phải ngày và làm lên
[00:51:32] trước chắc anh này mới đúng này em mình
[00:51:38] Ừ ok này
[00:51:49] u2000 21 năm trước
[00:51:52] đi gì đấy à
[00:51:53] ở
[00:51:57] Singapore nhà hàng đi làm luôn Ừ không
[00:52:01] biết được Anh tận Còn như thế không ạ
[00:52:03] Em lấy cây cây này để lại trường hợp này
[00:52:07] lại sai đúng không bay bay sử bạn tương
[00:52:09] lai đúng không Thế mà không ông nào để
[00:52:12] cái quả mít này đúng không Mình sẽ phải
[00:52:17] em Đúng rồi thì phải em là ngày vào làm
[00:52:21] nhỏ hơn tiết đã
[00:52:25] kiểu nó chết bay luôn cả ba luôn cả
[00:52:27] những ông hiểu đăng ký tháng sau anh Năm
[00:52:29] sau đó tự nhiên bay luôn
[00:52:31] áo bóng đá
[00:52:36] hình ảnh Ừ đấy nghĩa các bạn
[00:52:39] Anh hiểu tại sao nó là hai sao chưa đúng
[00:52:40] không
[00:52:54] và có lẽ bây giờ cái bạn à
[00:52:57] anh vẫn bay cái bạn cả đời đấy Đúng rồi
[00:52:59] ngày vào làm của bạn là như thế này
[00:53:11] Ừ tự nhiên đến lúc chữa mấy cô sao tôi
[00:53:14] thấy tôi để ý thấy ạ hai mươi mấy ông
[00:53:18] Aoi nhé như cậu mấy ông nữa thấy Khôi
[00:53:26] Ý
[00:53:30] tao là nói chung là các bạn xem lại thì
[00:53:34] cũng nhớ chịu khó làm bài tập nha ở đây
[00:53:36] rồi không có điểm danh cũng không cục
[00:53:37] Kiểm tra rất lòng gì cả Nên là các bạn
[00:53:42] đã tự giác rồi mà đúng không tự giác đây
[00:53:43] là đúng cái nghề mà mà mà
[00:53:46] nó còn miễn phí nữa để các bạn tự giác
[00:53:48] này chủ yếu thôi
[00:53:58] 300 nhẹ không cần phải kiểm tra điều
[00:54:01] kiện ngày vào làm vậy
[00:54:05] phải cậu bé hơn ngày hiện tại hay lớn
[00:54:08] ngày hiện tại ở đây bởi vì à Như mì nói
[00:54:10] 18 thể đăng ký trước mà đúng không ạ
[00:54:12] à à
[00:54:17] ý nghĩa tổng tiền mỗi tháng trước phải
[00:54:20] trả cho nhân viên này thì sẽ trăm lương
[00:54:20] đúng không
[00:54:28] à à
[00:54:32] ở đó như này xong theo từng nghề có sao
[00:54:34] của tôi mà Mấy ông kiểu làm cũng Bách
[00:54:37] hết rồi Còn mấy ông làm cái kiểu như này
[00:54:41] đó là mấy ông ngồi gõ lại đúng que theo
[00:54:44] từng nghề luôn ạ ạ dậy chưa
[00:54:47] Mình sẽ lại chơi trò sẽ exom đúng không
[00:54:49] Thế này sau đó gì à
[00:54:52] quay nghề nghiệp
[00:54:54] bằng này tiếng
[00:54:56] đúng ngay
[00:54:59] Ừ thì À thì ra đây nhanh Các bạn thấy
[00:55:01] cái này nó Nguyễn ra đúng không sôi các
[00:55:03] bạn Ware heo cùng mỗi 3 nghề các bạn
[00:55:06] quay ba phát từ cá thế không tốt người
[00:55:10] vì sao Bởi vì à từ mình mà lấy cái trong
[00:55:14] một công ty có tận đã phải 30 40 phòng
[00:55:17] ban ngành nghề có điều thứ mặn que thì
[00:55:19] chết à Ngủ Ngon thì mình sẽ phải làm như
[00:55:31] Ừ thì mình sẽ hôm nay mình cái thứ mà
[00:55:32] hôm nay mình sẽ học đấy đúng không nó sẽ
[00:55:35] liên quan đến group bang Đúng chưa
[00:55:40] mình sẽ khái niện bạn Goodbye theo nghề
[00:55:44] nghiệp các bạn sẽ thấy à Lúc đầu có bạn
[00:55:46] chạy cái này đã đúng không chạy cái này
[00:55:48] thì nó sẽ không nhóm theo cái nghề gì cả
[00:55:51] lấy tắt có mưa nó xin nhóm cho người sẽ
[00:55:53] ra như thế này đương nhiên là các bạn
[00:55:55] nhìn đây này các bạn sẽ hơi khó hiểu
[00:55:58] không biết bốn trăm cùng ngày nào cũng
[00:55:59] giống như là 100 ngày của người nào đúng
[00:56:01] không các bạn sẽ mình sẽ lách nó như thế
[00:56:03] này thì bảo sẽ hiển thị ra được thôi
[00:56:07] đúng không làm nghề rồi kèm theo đơn như
[00:56:10] là các bạn để Adidas ở đây rồi à tổng
[00:56:13] lương trở lại gì đấy đúng không
[00:56:16] cái các bạn chạy này thì nó sẽ ra là
[00:56:18] nghề kết hợp với
[00:56:21] những tấm gương ở ngay bên cạnh Đúng
[00:56:24] chưa Thì cái này nó rất tiện thì
[00:56:27] theo kiểu đã các bạn nhóm theo cái gì đó
[00:56:30] Cái này không phải nhóm theo Mỗi nghề
[00:56:32] các bạn hoàn toàn thực tế là đơn nhiên
[00:56:35] là có thể nhóm heo rất nhiều thứ thì
[00:56:37] mình sẽ học chuyên sâu hơn ví dụ là nhóm
[00:56:40] theo tên là những bạn tới Long thì mức
[00:56:42] lương tâm lương là gì hay ở mức lương
[00:56:44] Chung bừng trung bình của tất cả các bạn
[00:56:46] đấy Long này đã lại thế nếu bao nhiêu
[00:56:49] tên thật chứ Probi còn theo cả nhiều cột
[00:56:52] nữa Cái này cho chuyên sâu hơn tí mình
[00:56:53] có thể mình sẽ đặt cọc
[00:56:57] nhà bè cứ làm đơn giản chưa hết cả các
[00:57:01] xe
[00:57:04] tải thì các bạn sẽ xảy ra thì câu này
[00:57:07] thế thôi đúng không Câu này Hôm nay thì
[00:57:10] bản chất là mình có hoa
[00:57:12] a cho các bạn cảm thấy
[00:57:15] làm được thêm không nữa rồi cao nó cũng
[00:57:17] chẳng thay đổi gì mấy đúng không nó sẽ
[00:57:21] là theo từng nghề gì sẽ mình chị đổi đây
[00:57:24] đúng không trung bình lương rồi được
[00:57:27] ngon thấy da nó cũng không khác gì mấy
[00:57:42] xe đẩy ra các bạn mới vào làm hôm nay
[00:57:47] đây có ông thì bảo là câu này dễ nhưng
[00:57:50] mà em lại không ra kết quả hơn nó vỡ
[00:57:52] vùng cửa rồi em chạy được rồi nhưng
[00:57:53] không ra kế hoạch
[00:57:56] tại sao Vì nếu mà còn snack sao cong
[00:57:57] nhân viên như thế này mà có bạn chị nó
[00:58:00] già Noel này vào làm
[00:58:03] cũng bằng đúng cái ghế hết ạ Các bạn
[00:58:06] nghĩ rằng ạ Đúng rồi Má rõ ràng em ở
[00:58:08] trên em về phô nó ghét bếp thì dưới mà
[00:58:10] ghét hết theo chuẩn rồi còn đi xa đâu
[00:58:12] đúng không chạy này nó không đưa ra kết
[00:58:15] quả gì cả Tại sao Vì ghét bếp này mà các
[00:58:19] bạn select nó ra thì ghét ghét này nó sẽ
[00:58:21] bao gồm cả ngày tháng năm rồi phút giây
[00:58:24] thì ra năm tháng ngày giờ phút giây
[00:58:26] không thì à
[00:58:30] Ừ thì các bạn thấy là
[00:58:33] cái ngày và làm các bạn các bạn lưu lại
[00:58:36] là đếch thôi đúng không biết thôi chứ
[00:58:39] còn 5 tháng này thôi thì làm sao nó thể
[00:58:41] bằng được cả cái cụm này đằng sau đúng
[00:58:45] không sẽ bằng được thì có hai cách một
[00:58:49] hôm vừa rồi mình xem có bạn làm cũng khá
[00:58:51] phức tạp không Tí đó là bạn sẽ dùng đế
[00:58:55] típ đúng không để mặt trừ cái phải bệnh
[00:58:59] đây vậy trừ cái ngày ạ
[00:59:02] này vào làm này
[00:59:07] với ghét biết có một ý hay xong rồi đấy
[00:59:11] ạ bằng không thì ạ để lấy ngày hôm nay
[00:59:14] cho hợp lý mà
[00:59:16] Ừ đúng nhỉ
[00:59:26] anh đợi mình sẽ Mã ừ ừ
[00:59:34] Ừ tao đâu nhỏ con không Ngon không Ngon
[00:59:36] không đúng rồi nhỏ hơn không một việc
[00:59:39] bởi vì à bằng không thì phải khớp Khớp
[00:59:41] hoàn toàn nhắn không thôi ok ra rồi đúng
[00:59:44] không à Nhưng mà cách này Thực ra nó
[00:59:47] phức tạp hơn các bạn bài toàn đơn giản
[00:59:49] lắm các bạn mà vừa rồi vẫn là so sánh
[00:59:52] những ngày và làm đúng không
[00:59:55] Và Ghét Ghét cái đúng rồi Nhờ như mình
[00:59:58] đã nói gì thì mình chỉ cần lấy 5 tháng
[01:00:00] này ở từ cái ghét ghét thôi các bạn sẽ
[01:00:06] trao Google nó là ghét cont đây là lại
[01:00:10] anh khuya này tại như thế này thì nó sẽ
[01:00:14] ra ngay cái quả đó là ghét coolbit
[01:00:16] wartime này đái vào nó sẽ có khái niệm
[01:00:19] là như thế này nó sẽ là Cát nó sẽ biến
[01:00:23] đổi cái một cái chúa gì đó thành cái gì
[01:00:26] đó nhìn anh là như này là xong bạn chạy
[01:00:28] thử
[01:00:37] thì tại sao không gian này xem thử đã
[01:00:39] nhé
[01:00:43] ờ đúng à ngày vào làm của ông kia ngày
[01:00:44] bao nhiêu nhỉ
[01:00:53] em đọc không đi à
[01:01:01] ở ngay và làm của ông kia là
[01:01:04] à À ngon
[01:01:07] I don't know mìn sót lại hình như làm ào
[01:01:10] mình delete mình đi lễ rồi Xin lỗi Xin
[01:01:20] cho da mình khử cho bạn đấy ạ
[01:01:23] Khi bữa nay chạy được này chạy được nó
[01:01:24] ra đúng không
[01:01:27] Vì sao
[01:01:33] Ừ nhưng mà cái này các bạn kể cả xấu dù
[01:01:35] vừa rồi mình đi sớm đúng không Rồi mình
[01:01:38] à cho thử bằng lại cái này nhé nó cũng
[01:01:41] không ra đâu Cái này mình thoảng đi luôn
[01:01:44] cái này kiến thức mà ngon kiến thức thì
[01:01:46] phải chắc chứ
[01:01:48] anh lại không ra là đúng không Đó được
[01:01:52] chưa cũng như là cái vừa rồi nít này
[01:01:55] nếu thấy có thể đến đít bằng không chắc
[01:01:59] là nó được đấy thử thử ngày vào làm đi
[01:02:01] ngoài
[01:02:04] với ghét ghét này
[01:02:08] bằng không đi cha có khi nó ra đấy
[01:02:11] ở đó ra rồi đúng không thấy mình nhớ
[01:02:14] bằng không là hợp lý mà
[01:02:18] anh lại có hai cách này đúng không ạ
[01:02:22] ở đâu phim mới có một tiếng mà ông đã
[01:02:28] có ai nghĩa các bạn dùng một trong hai
[01:02:30] cái này nhưng mình thấy Là cách này nó
[01:02:33] trông có vẻ từng minh hơn đúng không còn
[01:02:35] cái này thì đúng là kiểu các bạn biết về
[01:02:37] cái Hà mày giờ thì các bạn dùng cậu
[01:02:40] không sai
[01:02:44] ờ ờ Còn gì nữa không nhỉ lấy ba bạn em
[01:02:45] cái cũng nhất trí không phải bye hôm nay
[01:02:47] mình học này thì ra nó rất là ngắn không
[01:02:51] Cái này chỉ đơn giản là mình sẽ là
[01:02:55] select sao form nhân viên
[01:02:57] order vai
[01:03:02] ta cũng nhất ở đây tức là chỉ là ngày
[01:03:07] vào làm Ngọc là ai si tượng này và làm à
[01:03:08] từ
[01:03:10] tăng dần đúng không
[01:03:13] anh Bởi vì ngày vào làm càng cũ tất cả
[01:03:16] càng bé mà không lại nó tăng dần nếu mà
[01:03:19] lấy như này thì nó sắp xếp treo này vào
[01:03:22] làm rồi nó và mình muốn lấy ba thì top 3
[01:03:25] thôi đúng không cấp 3 thôi Xong
[01:03:29] Ừ có anh sẽ lấy ba chưa Đây là khái niệm
[01:03:31] về
[01:03:36] remix được chưa khái niệm mà khái niệm
[01:03:39] Lipit Chưa remix tất cả món giới hạn số
[01:03:41] kết quả trả về
[01:03:46] tiếp theo mình muốn đẩy
[01:03:48] ở câu 2 sao này
[01:03:51] thì mình sẽ để buổi sau mình chữa nhé
[01:03:54] Thơ rất nhiều Bạn làm đến con này tắt
[01:03:57] bạn ấy rất mong buổi hôm nay chữa nhiều
[01:04:00] ạ tại khác đến buổi sau buổi sau mình
[01:04:04] dậy về việc tạo nhiều bạn nữa đúng không
[01:04:07] Mà hôm nay mình sẽ dạy cái đi tiếp giả
[01:04:12] sử là các bạn muốn bỏ qua ba bạn mày đấy
[01:04:15] ba bạn tiếp theo chẳng hạn vô mình mình
[01:04:16] nghĩ sót thì người cũng khá nhiều đấy
[01:04:25] ở đây là sự là mình có sáu bạn đúng sáu
[01:04:28] bạn luôn à Ừ thì khi mình sẽ lách như
[01:04:31] thế này thì rõ ra Các bạn thấy mười một
[01:04:34] 8 14 như là bây giờ mình muốn bỏ qua ba
[01:04:38] bạn để lấy ba bạn tiếp theo đúng không
[01:04:41] Thì mình làm như nào thì nó sẽ Khái niệm
[01:04:44] và offset họp xét thì da mình không ngờ
[01:04:46] offset ở trong Express server là gì đâu
[01:04:48] nên mình cứ gửi tra xem nó có dùng được
[01:04:55] a fake vào để mình thử xem
[01:05:00] khi học sat fake nén cũng hơi khó hiểu
[01:05:05] đại offset người đâu Chắc thể học sat bà
[01:05:07] bầu em ạ Đã bỏ qua bao lâu gì
[01:05:09] à à
[01:05:13] Ừ chắc là được sẽ Hữu này
[01:05:22] I thought shed thì không kết hợp việc
[01:05:26] tốt mà kết hợp với fake Ok thử nhé á
[01:05:28] à à
[01:05:33] khoa học CF
[01:05:40] à À đấy
[01:05:42] hình ảnh
[01:05:46] Ừ chắc phải nếu mà các bạn kết hợp Limit
[01:05:48] offset ở trong SQL Server thì các bạn
[01:05:50] hãy chơi theo cách như lai như thế thì
[01:05:53] mai queo viết này nó sẽ tiện hơn
[01:05:56] axwell viết nó sẽ nhàn hơn rất nhiều các
[01:05:58] bạn sẽ thử xem sao xanh với máy Nokia
[01:06:01] nhé bởi bên máy của em hãy cho mình sẽ
[01:06:03] giận thì bên Mai Phương đến như vì sao
[01:06:06] mình sẽ nhắc lại khi mà dậy lại về máy
[01:06:08] của em nhé Bây giờ mình sẽ nói qua các
[01:06:11] bạn lại bạn thấy nó sẽ dễ dàng hơn
[01:06:15] Limit 3G offset ba như này xong này
[01:06:19] nó sẽ dễ hiểu hơn hiểu lấy lấy chỉ có 3
[01:06:22] bạn ghi và được nha Bỏ qua bạn kia Thậm
[01:06:24] chí các bạn hãy viết tắt hiệu kiểu như
[01:06:25] này
[01:06:28] Ừ thì nó sẽ hiểu là lấy 3 và bỏ qua ba
[01:06:31] được trong nó sẽ rất là từng Minh sau ấy
[01:06:33] kéo lúc cái dùng tốt lúc bị dùng fake
[01:06:35] họp xét các thứ bên Express server ngày
[01:06:36] nay
[01:06:40] Ừ ừ đấy do mà thực là nhiều nơi thích
[01:06:43] dậy máy cao hơn là
[01:06:46] ashwell bụi server Nếu mà hãy qua server
[01:06:50] Chính vì nó cũng hơi rườm rà nhà ngon Nó
[01:06:52] lại hỗ trợ nhiều hơn sau làm em quen mấy
[01:07:00] đãi về khái niệm về à Cái liên quan đến
[01:07:03] hôm nay mình bảo nó thống kê các thứ thử
[01:07:05] anh
[01:07:08] không cần fake Ừ trong trường hợp này
[01:07:11] bởi vì À bởi vì rõ ràng là ô xét 3 thìa
[01:07:12] như chỉ còn 3 thôi đúng không Thì không
[01:07:15] cần fake Nhưng mà nếu bây giờ sử mà các
[01:07:18] bạn muốn lấy ba thằng à Một lấy 221 Hằng
[01:07:19] ngay sau ba tháng thì thôi nha các bạn
[01:07:22] phải thêm phách mà đúng không
[01:07:24] ông chủ nhật chạy thử nhé
[01:07:27] Ừ đúng rồi bây giờ mình muốn chị lấy một
[01:07:29] thằng sau 3 hàng thì mình phải thêm
[01:07:32] phách chứ đúng không để lấy giới hạn chỉ
[01:07:36] có một thằng sau đó thôi à
[01:07:37] Ô
[01:07:41] kìa Cái hôm nay thử ca mình không chỉ
[01:07:44] muốn dạy như thế này mà mình muốn dạy
[01:07:47] các bạn chuyên sâu về cái Du pied một tí
[01:07:51] về cứ xem lại nhé xem lại đây này
[01:07:55] em vừa rồi Vừa nãy mình có Goodbye theo
[01:07:57] có nghề nghiệp dư ngon các bạn hoàn toàn
[01:08:00] này Goodbye Hair rất nhiều cái nữa Thật
[01:08:01] sự là bây giờ mình có thể rút bay theo
[01:08:04] giới tính thậm chí là cả kết hợp cả hai
[01:08:07] cột về nhau cũng được hoặc 3 theo tên
[01:08:10] cũng được ra sự ở đây mình nhưng mà
[01:08:13] trong trường hợp nếu các bạn Goodbye là
[01:08:16] sự của bạn nhập tên là sẽ nào các bạn sẽ
[01:08:17] không đủ sẽ lấy sao mình nữa và sẽ báo
[01:08:20] lỗi bởi vì tất cả những cụt không nằm
[01:08:22] trong new Bike hướng ở đây nó có Ai Cập
[01:08:25] là các bạn sẽ không Không nhìn thì ở đây
[01:08:28] được lỗi được chưa Nhưng các bạn bắt
[01:08:32] buộc phải phải ghi thì nhớ là tên cột ở
[01:08:36] đây đã cái đấy cứ thử thứ nhất là sẽ lấy
[01:08:38] được đây thứ hai là
[01:08:41] các bạn sẽ dùng những cái Hà mình còn bị
[01:08:45] xăm này cao là anh trung bình lấy trung
[01:08:47] bình
[01:08:49] identified cái gì đấy
[01:08:54] mày cái hàm đấy gọi là hàm ở đây nó khái
[01:08:55] niệm hàm à
[01:08:59] ogress Gì đấy Này bể thì thì mới dùng
[01:09:03] được ở trong Goodbye đây ví dụ là mình
[01:09:06] sẽ xăm lưng nhỉ đúng không
[01:09:08] à à
[01:09:12] xe tải thì liệt kê tổng lương của tất cả
[01:09:14] những bạn có cái tên này đúng không sẽ
[01:09:16] lắp trùng mà hộ cho mình lọc Chung nhé
[01:09:19] đầu tiên lập chung đúng không có ai kết
[01:09:22] hợp việc là nó sẽ liên quan đến những
[01:09:24] cái hàm thống kê thì ra thấy hàm thống
[01:09:28] kê tiền mà tính toán hội chứng minh
[01:09:30] em ở nhà mình có thể giúp bay theo cảnh
[01:09:33] nhiều cái nữa Thật sự là mình ở đây mình
[01:09:37] người bể có một bạn tên Long nhưng mà
[01:09:40] bạn đấy để giới tính là nữ đi chẳng hạn
[01:09:41] thế
[01:09:43] Hà
[01:09:47] Tĩnh không đi lại lương hẳn lên 500 đi
[01:09:51] 5.000 thôi hơi quá đáng được mình hài
[01:09:53] lòng với bạn Tiểu Long Nữ
[01:09:56] em ở nhà thì có bạn sẽ thấy đầu tiên đây
[01:09:58] thì nếu mà chịu rút bay theo tên Long
[01:10:01] Thôi thì tiền nó sẽ lên hẳn 5.000 hay
[01:10:03] đúng không Nhưng mà nếu ra sự là thêm cả
[01:10:05] roba theo cả
[01:10:10] tên là kèm với cả giới tính như thế này
[01:10:13] Ừ thì có bạn sẽ thấy là hai cái này đang
[01:10:15] bị tách ra rồi đúng không với bạn tên
[01:10:17] Long giới tính nó không thì lương mà dậy
[01:10:19] như này nhưng bạn tên Long rồi tính làm
[01:10:21] một thì lương nó sẽ chỉ này thôi
[01:10:24] có thêm thắc mắc thứ hai mà hồi đấy mình
[01:10:26] cũng rất là đau đầu đó là
[01:10:28] Goodbye được nhiều cột như Ngài đã do
[01:10:31] phức tạp rồi Thậm chí là các bạn sẽ thắc
[01:10:34] mắc à mình để cái cột này trước một này
[01:10:37] có được không Thực ra bài toán nó được
[01:10:40] Nhưng mà phải toàn nó lai kìa mình sẽ ưu
[01:10:41] tiên
[01:10:43] ngọt nhà nghỉ
[01:10:46] anh như tiên nhóm thằng nào trước thôi
[01:10:49] nhóm nào trước đấy mẹ thử nó không hẳn
[01:10:53] là thay đổi và mặt logic đâu theo mình
[01:10:54] là như thế bởi vì đó
[01:10:57] Ừ tao kiểu gì Mỹ phải Lộc Trung
[01:11:00] thì các bạn thấy được à mình để nó hạnh
[01:11:02] trước và sao nó không đem lại ý nghĩa gì
[01:11:04] đấy cả thực sự như thế
[01:11:07] hoặc các bạn thấy nó chỉ ở nhóm đưa tin
[01:11:09] nhóm thằng nào trước thì mặc tên đầy nó
[01:11:12] lên đầu hai giới tính cái đầu vân vân
[01:11:15] Nhưng mà còn kết quả thì nó vẫn sẽ là
[01:11:18] như thế chưa Nên là các bạn không quan
[01:11:21] tâm việc cái thứ tự cái này lắm mà các
[01:11:24] bạn quan tâm việc là phải bay sao cho
[01:11:26] đúng cho tí thôi
[01:11:30] mình sẽ ở đây à khóa học này khoa học cơ
[01:11:32] bản em mình sẽ toàn nói toàn bộ những
[01:11:34] cái đó chỉ cần Cơ bản một tí các bạn
[01:11:36] hoàn toàn được tìm hiểu thêm cũng giống
[01:11:39] như là có bạn bảo vệ Minh là thực ra là
[01:11:41] đến buổi hôm nay là bắt đầu dậy khứ
[01:11:43] nhanh rồi vì thường em họ trên lớp em
[01:11:46] học Insert update Delete có khi mất sự
[01:11:49] ba bốn buổi nhưng mà Đây cũng là anh
[01:11:52] trực tiếp rồi của việc online đó các bạn
[01:11:55] sẽ phải tự học ở nhà nhiều cũng làm bài
[01:11:58] tập thì ra làm một bài của mình từ A vẫn
[01:12:02] còn ít đấy bởi vì à học cốt này để mà
[01:12:04] các bạn nhớ thì các bạn bắt buộc ngoài
[01:12:06] phải hiểu thì phải thực hành rất nhiều
[01:12:09] những một bài thơ Ra chưa đủ lâu các bạn
[01:12:10] sẽ phải
[01:12:13] anh làm đi em lại khá nhiều bài tương tự
[01:12:17] tự nghĩ là để cho mình để làm thì mình
[01:12:19] mới nhớ được
[01:12:22] các bạn và để nói chung là để bạn hiểu
[01:12:26] đúng không thể tự mòi nhiều mình không
[01:12:27] thể
[01:12:31] buổi hôm nay lại dậy lại bổ Hôm trước
[01:12:33] chỉ thay đổi mỗi bài tập được mình bắt
[01:12:34] buộc phải dậy tăng tiền đúng không dạy
[01:12:36] thêm kiến thức mới
[01:12:40] nhưng mà các bạn vẫn phải tự chủ động ở
[01:12:42] nhà học thôi đúng không Thế lúc đầu mình
[01:12:44] định là thì hai buổi thôi để những thời
[01:12:46] gian có lại các bạn sẽ chỉ cắm đầu vào
[01:12:47] học
[01:12:52] tự ôn tập nhưng mà thực ra thì không ai
[01:12:55] không ai ép được các bạn nên có khi ở
[01:12:58] nhà các bạn cũng ôn tập lí Đông làm được
[01:13:01] bài tập mình chắc là căng mắn rồi
[01:13:05] nhưng mà cái này cũng nói thế để cho bạn
[01:13:07] biết được lại ra đền cái và lút bye này
[01:13:10] khi mình đi dạy ở trên đấy nó cũng phải
[01:13:11] lên đền á
[01:13:15] ở buổi à 18 19 chứ không phải là đến
[01:13:18] buổi đầu năm đã dậy cái mới gai hàm như
[01:13:20] này luôn rồi Đâu
[01:13:23] là đến buổi sau nữa buổi sau mình sẽ cố
[01:13:28] dạy tách kể cái buổi liên quan đến khoa
[01:13:30] ngoại ít nhất phải hay buồn
[01:13:33] ý kiến thức cơ bản và kiến thức sâu hơn
[01:13:38] tí nhưng mà các bạn cũng phải làm bài
[01:13:41] tập nhiều hơn và nghĩ trên bài này là
[01:13:43] kiêu kiêu thế
[01:13:46] anh nói chung nhà tạm cái đức của Mai
[01:13:49] Thế em mình thử trả lời em và bình luận
[01:13:51] các bạn nhé
[01:13:55] Ý anh là giảng viên trường BKA a b cái
[01:14:02] Đó là hình như là đúng đúng cũng có viết
[01:14:04] tắt Đúng chưa mà nhiều Đấy chính xác tên
[01:14:07] trường của mình biết cái cái cái cái
[01:14:10] nhưng mà đúng với k viết thì ra cũng
[01:14:20] nó học viện thế này ra là nó vẫn đúng
[01:14:29] ở armenia không biết được các trường
[01:14:31] khác dạy nhà vốn dĩ hâm Mình đã học của
[01:14:34] các chữ cái đầu đúng không Nhưng mà mình
[01:14:38] mình theo theo cái kính nhiễm dùng thử
[01:14:40] kinh nghiệm cũng ngoài phép từ công nhận
[01:14:43] là mình đi dạy phải hơn hai năm rưỡi rồi
[01:14:46] mà mình dậy đi dậy lại cái video này nó
[01:14:48] cũng khá nghiền nhuyễn rồi
[01:14:52] nên à Mình nghĩ thế này là tốc độ cũng
[01:14:56] nhanh nhưng mà mình nghĩ à các bạn làm
[01:14:59] xong rồi những bài thi ấy Chắc là làm 23
[01:15:02] bài đấy các bạn sẽ hiểu Nhưng mà hiểu là
[01:15:03] một chuyện
[01:15:05] thì các bạn còn phải nhớ nữa đúng không
[01:15:14] ờ ờ anh mình quên mất đã bây giờ mình
[01:15:17] thì nói với hack nghỉ tại từ nhiều lo
[01:15:19] của mình sẽ nhắc về hack nhé
[01:15:29] à à những kiến thức là những cái những
[01:15:31] cái câu hỏi các bạn đang hỏi được ra lại
[01:15:35] các bạn trai để một tí bây giờ cũng à
[01:15:38] thời khác để có ông chủ động thể hiện
[01:15:41] mình là giờ này đi rồi ông tò mò cái gì
[01:15:43] ông lên trang cá nhân của tôi hoa quả
[01:15:45] thực ra từ chưng cho cá nhân tôi mà
[01:15:47] không mò được thì ông người mà qua blog
[01:15:50] vân vân để ra thử thông tin nữa Thôi nếu
[01:15:52] em thực sự muốn tò mò đúng không
[01:15:55] Bởi vì mình cũng từng làm thế với mấy
[01:15:57] bạn gái mình thích chẳng ạ Nhưng mình
[01:15:59] phải tìm hiểu sâu mà nó học
[01:16:01] à à
[01:16:04] cho con hỏi Bây giờ thì thực ra mình trả
[01:16:05] lời rồi sao mình trả lời đi Trả lời lại
[01:16:08] nó cũng hơi bị ngàn đấy à
[01:16:13] hai tay time Attack là gì đúng không cái
[01:16:14] à
[01:16:17] Nếu như mình lúc đầu mình có nói thăm
[01:16:29] đo để mã tấn công đo thời gian để tấn
[01:16:33] công cái gì đó Nó kiểu dặn và
[01:16:35] kiểu này đương nhiên là bây giờ khó mà
[01:16:37] áp dụng được ít nhất là cho mình cái
[01:16:40] trang lớn còn rất nhiều trai hiện tại nó
[01:16:43] vẫn còn dính thì mình sẽ thử nói chung
[01:16:47] là mình sẽ không nói lại cái bài đăng
[01:16:49] này các bạn nên tìm bài đăng này đọc
[01:16:51] nhưng mà bạn đang này viết nó cũng tương
[01:16:53] đối dễ hiểu nhưng mà có kết hợp cả bên
[01:16:55] ngôn ngữ lập trình nghe này có nhiều bạn
[01:16:58] nhìn thấy sẽ hơi bị choáng còn bên mình
[01:16:59] sẽ nói hiểu ý hiểu của mình khi mà đọc
[01:17:00] xong bài này
[01:17:03] cao như thế này
[01:17:07] cái này nó hai cục công nhận hai cục đây
[01:17:11] để mình thử nó phải cho bạn nha ở đầu
[01:17:13] tiên là sử các bạn muốn hack dùng cái
[01:17:21] em giả sử của mình thôi có lấy Facebook
[01:17:23] cũng có nghe Giả sử mình cứ nói vụ ra
[01:17:24] chúng mình muốn hack Facebook chặn ạ
[01:17:27] đúng không Mày thêm thì nào Chim trên
[01:17:28] youtube lên Facebook gọi sẽ không đánh
[01:17:31] bản quyền mình câu này không đánh gậy
[01:17:34] mình đây A khi
[01:17:37] để đăng nhập Facebook thì các bạn phải
[01:17:41] điền cái gì Email và mật khẩu hoặc email
[01:17:45] mật khẩu word đã sử email của mình là
[01:17:49] abc@gmail.com và mật khẩu của mình ra sự
[01:17:52] với nhé một hai ba bạn ạ ngon đấy
[01:17:55] Ừ thì mình giờ sửa Mình có đăng ký một
[01:17:57] cái tài khoản
[01:18:00] ở đây mình có đăng ký một tài khoản là
[01:18:02] như thế này tôi chưa ạ
[01:18:03] Ừ
[01:18:07] ok chưa Sau đó thì mình đăng nhập đăng
[01:18:10] nhập vào đấy nhưng mình đăng ký như này
[01:18:11] vào đăng nhập vào thì đương nhiên được
[01:18:13] luôn đúng không một thành công không
[01:18:15] thành công
[01:18:17] cái toán đây chẳng gì xảy ra là mình
[01:18:20] không thể hack nick chính mình nghe mùi
[01:18:23] Cường vậy mà Thế mình lúc mình đăng ký
[01:18:25] làm gì ngon mình thành công nhưng mình
[01:18:40] là sử sử mày toàn đăng nhập thành công ở
[01:18:42] đây mình mất 2 giây ạ
[01:18:45] Tại sao thật sự là mình mất 1 giây để mà
[01:18:49] kiểm tra Email máy chủ làm việc vẫn một
[01:18:51] giây Kiểm tra Email mẫu dây kiểm tra mật
[01:18:53] khẩu em ạ đúng không
[01:18:56] Nhưng các bạn phải hiểu bên Bất Trị
[01:18:58] nghiện thì
[01:19:00] ở thời gian đăng nhập thành công nó luôn
[01:19:02] nhanh hơn rồi ra đang cực đăng nhập thất
[01:19:05] bại các bạn bây giờ từ lên rất nhiều
[01:19:07] trang web mà các bạn đăng nhập và thầy
[01:19:10] nó rát rát Một lúc lâu ấy hồi trước phải
[01:19:14] bụng bị gì nhé bảo là kiểu các bạn biết
[01:19:15] thừa là mình đang đang nhập sai rồi kêu
[01:19:17] chị Năm thông báo về màu trắng lỗi
[01:19:20] các bạn thử mà xem rất nhiều Trang đi bị
[01:19:22] đến bây giờ vẫn thế
[01:19:25] thì à Tại sao tự nhiên mà nói về đăng
[01:19:28] nhiều thất bại rồi Bây giờ ông mày sẽ
[01:19:32] thấy một giây thử email và một dây thử
[01:19:35] mật khẩu đúng không Ông ấy thử đăng nhập
[01:19:37] lại
[01:19:41] với tài khoản là Ace vẫn là Email là ABC
[01:19:43] ngay nhưng mật khẩu cho thằng say mặt
[01:19:46] nhiều Vina xây nhà trường ạ đúng không
[01:19:49] Thì ông ấy thấy kết quả trả về
[01:19:54] lên tới ba giây ạ Từ đó ta có cái ngôn
[01:19:55] luận là gì
[01:20:04] D3 dây là thất bại đúng không Nhưng
[01:20:05] ở
[01:20:08] đây là với ạ
[01:20:13] Em email đúng Ông ấy chỉ nhập gửi mail
[01:20:15] chất chọn size size luôn cả email cả mật
[01:20:18] khẩu nghe trở lại email chữ toàn không
[01:20:21] mở tồn tại với một cái mật khẩu sẽ sáng
[01:20:23] mà nó chẳng tồn tại của Email này kết
[01:20:26] quả Sẽ Về Nói lên bốn giây
[01:20:29] thì từ đó phát có nghĩa là ông ấy sẽ
[01:20:32] chạy một cái con bóp một con tự động ông
[01:20:35] ấy lập trình hoa càng phải trên mạng về
[01:20:38] Ừ để chặn Farm liên tục của các trang
[01:20:39] web đấy
[01:20:40] ở
[01:20:44] spam email ngẫu nhiên
[01:20:46] Em email sinh nhắn ngẫu nhiên đấy hiểu
[01:20:49] thế bà toàn bộ kết quả trả về là ba giây
[01:20:52] chiều nó sẽ hiểu là
[01:20:55] số trang web này có email đấy Tân An
[01:21:00] thôi nghe hợp lý không thì suy ra lấy
[01:21:01] được
[01:21:13] ok chưa đó là xăm mình là tách và các
[01:21:15] bạn vừa nghe xong cũng
[01:21:18] sức khỏe khó hiểu hay giới thiệu đến
[01:21:20] đoạn này ạ
[01:21:31] khi mình ăn để độ Trễ của bình luận nó
[01:21:34] lên tận 30 giây một phút đấy nhưng chắc
[01:21:36] ạ Phải đợi một lúc mình biết về câu trả
[01:21:39] lời các bạn ạ
[01:21:49] anh
[01:21:51] nghe đấy Loại này thì các bạn hiểu rồi
[01:21:55] đúng không cái thì
[01:21:59] nhưng mà có bạn thì bảo là hack
[01:22:01] khi hack như này thì
[01:22:04] Anh cũng anh cũng có để làm gì đâu đúng
[01:22:07] không biết mũi email đúng không Nhưng mà
[01:22:09] không cái này nó liên quan đến bài Toán
[01:22:11] thứ hai đó Khi mà các bạn biết được toàn
[01:22:13] bộ email của mình cái trang web rồi đúng
[01:22:15] không Thì bây giờ mình cần xuống dò
[01:22:18] đường mật khẩu chưa
[01:22:21] do ra được mật khẩu như nào thì thằng
[01:22:23] Facebook nó lại có cơ chế như này à
[01:22:24] không không Ngoài Facebook mà lập trình
[01:22:28] máy tính chiều có cơ chế như thế này Hôm
[01:22:30] trước mình nói mày toàn nó sáng chuỗi
[01:22:38] như sau thành chuỗi thì nó sẽ như này ra
[01:22:40] xử ở đây mình có
[01:22:44] ở chỗ làm à như này đúng không
[01:22:48] ở đây Mật khẩu của mình đúng không Chúng
[01:22:51] mình nhập đã bên này giá Aba như thế này
[01:22:55] hoặc là ba này theo các bạn
[01:22:58] và đương nhiên tất cả đều là sai đúng
[01:23:01] không nên treo các ạ trường hợp nào là
[01:23:04] trường hợp trả về thông báo sai nhanh
[01:23:07] nhất và trường hợp nào trường hợp cho về
[01:23:10] thông báo sai lâu nhất
[01:23:11] thứ
[01:23:20] phụ đề để mật khẩu cho
[01:23:24] lần thử đầu tiên này lần thứ hai này lần
[01:23:27] thứ 3 trường hợp nào là trường hợp thông
[01:23:31] báo sai trở về nhanh nhất mà trường hợp
[01:23:39] Ừ để tạm boot thì cắn học phí học lập
[01:23:41] trình này học giáo trình chính tạo tune
[01:23:43] tại port tự động được mặt
[01:23:45] à à
[01:23:49] à À chắc bạn mới vào bởi vì mình phải để
[01:23:51] đền đây một tí rồi vì ạ
[01:23:55] thời gian đầu vừa nãy ít tự nhiên video
[01:23:59] Nó kiểu nó bị à mà bị kiểu mát thế kiểu
[01:24:02] các bạn xem độ phân tải bị thấp thì là
[01:24:05] phải để độ trễ lớn hơn để các bạn nhìn
[01:24:07] được màn hình mà không biết lắp
[01:24:10] Ừ đúng rồi còn có vài bạn trả lời
[01:24:11] Ừ
[01:24:14] đúng rồi kìa nó là ba nhanh nhất và một
[01:24:18] lâu nhất tại sao Vì bài toán là máy tính
[01:24:20] nó kiểm tra nó sẽ kiểm tra từ trái sang
[01:24:25] phải và kiểm tra dụa đúng này nó mất 0,5
[01:24:28] giây đúng không thì kiểm tra từ này tiếp
[01:24:31] thế nào ah đầy đủ ngủ tiếp Lại mất 0,5
[01:24:35] giây nữa sau đó thì A về B xa rồi đúng
[01:24:38] không nó mất giờ xử một giây ạ thì tổng
[01:24:40] cộng thằng này sẽ mất là 2,5 giây và sự
[01:24:43] thế thôi nhá tương tự Thường ngày là A
[01:24:48] đúng này 0,5 này a b sai này 1,5 lại
[01:24:50] đúng không Con trường hợp này nó sẽ trả
[01:24:52] về luôn là một giây đúng không
[01:24:56] khi ở đây từ đây thì các bạn sẽ
[01:24:57] thì
[01:25:02] các bạn sẽ thấy là mật khẩu nào càng gần
[01:25:06] đúng khi thời gian phản hồi về càng lâu
[01:25:09] Cô Đơn giản thế thôi đúng không Thì mình
[01:25:11] lại chạy con boss nó sẽ tự động sinh ra
[01:25:14] mật khẩu đúng không Thế mày ngồi dò mật
[01:25:16] khẩu b vì vừa nãy mình lấy được email
[01:25:20] rồi mà không mình sẽ dò mật khẩu của
[01:25:23] Tuấn email một sau đó thì mình mình sẽ
[01:25:26] thử một cái chuỗi ngẫu nhiên và chỗ làm
[01:25:28] à càng thời gian chào người càng lâu thì
[01:25:31] chứng tỏ là mật khẩu càng gần đúng rồi
[01:25:35] đấy thuế ra được mật khẩu thôi à
[01:25:38] Ừ cái đương nhiên là bài toán bây giờ
[01:25:41] thực là đây do mật khẩu mà các bạn phải
[01:25:45] nên dài hơn 8 ký tự thì tốc độ tốc độ để
[01:25:49] mạnh thread ra được cá mực để mà đoán
[01:25:52] được mật khẩu qua con boss nó tốn nhiều
[01:25:53] thời gian
[01:25:56] ở chương 11 khẩu nhắn như thế này kết
[01:25:58] hợp với không ký tự đặc biệt thì cha nó
[01:26:04] Cho
[01:26:07] tôi mua bút fortec chỉ ra hình thức tấn
[01:26:10] công kiểu ngồi dò mật khẩu đây ạ
[01:26:13] Ẩm Thực ra thực tế còn nhiều bạn thì sẽ
[01:26:15] phản bác lại ý kiến này ngay đó nơi kiểu
[01:26:17] anh không để ý với tốc độ mạng à hay là
[01:26:20] cá mập cắn Internet à Vân Vân Vân ở đây
[01:26:23] có bạn ở dưới cũng nói bạn này cũng nói
[01:26:27] đó là kiểu này
[01:26:32] 3 Cách Tấn Công này hơi bất khả thi vì
[01:26:34] nó liên quan đến thuốc này sức động sức
[01:26:37] mạnh của máy tính này cá mập này cách
[01:26:41] mạng 4.0 vẫn luôn Vân này đấy Thì thực
[01:26:44] tế là ở đây có vai toán này nó nó mức
[01:26:47] dao động đó chị ở chênh lệch một khóa
[01:26:50] một cái lượng nhất định thôi thì ạ Thì
[01:26:54] mình vẫn có thể đo lường được cái đấy
[01:26:54] cho
[01:26:57] nên là thực tế là chúng ta cũng phải cân
[01:27:06] 3000 mã hóa ở đây không liên quan gì bạn
[01:27:08] ơi Không không không liên quan đến mã
[01:27:12] hóa gì đấy cả mã hóa để cho khi mình
[01:27:14] nhập và lên Như mình phải vẫn phải nhập
[01:27:17] mật khẩu thôi chứ mình làm sao mình nhập
[01:27:20] khẩu mã hóa được đúng không mã hóa đây
[01:27:23] chỉ để như ông nào mà dò được tạo bởi
[01:27:26] các bạn biết được về các bạn mà không
[01:27:28] không dịch được cái đoạn Mã hóa đấy
[01:27:30] ngược lại thôi Chứ còn lúc mà nhận mật
[01:27:33] khẩu thương nhân chỉ nhập thôi mà nhưng
[01:27:42] Ừ Kệ đi hỏi cho nhanh tôn chạy bằng cơm
[01:27:44] Bạn vừa nãy nói thì nó liên quan đến một
[01:27:47] kỹ thuật khác nó social
[01:27:50] Engineering nữa
[01:27:58] bộ phim rất hay về cái này nó chính là
[01:28:04] Obama War về hacker dân nổi rất dễ hiểu
[01:28:09] và rất là hay về ạ Hai cơ mình nha mình
[01:28:11] nha biết là hay
[01:28:18] anh đấy đấy đấy là một trong lý do bây
[01:28:21] giờ để tránh boss chỉ đứng ở phải có
[01:28:23] thêm cắt tra rồi các thứ gì nữa đúng
[01:28:25] không ạ
[01:28:27] à à
[01:28:29] anh không Nó ban mật khẩu trước khi gửi
[01:28:31] cũng chả liên quan gì đây là nó không
[01:28:33] liên quan mã hóa mình nói thôi và thời
[01:28:37] ra có cái trang web sợ How cho ý cho
[01:28:41] password này bạn thể tra thử trên này
[01:28:43] thử xem cái mật khẩu các bạn Nga dùng
[01:28:45] mật khẩu hiện tại của mình ra như thế
[01:28:48] này thì máy mua cái máy bình thường ấy
[01:28:56] thì nó sẽ như thế này nó sẽ hiểu
[01:28:59] Nó sẽ phải chạy bao nhiêu bài toán này
[01:29:02] và mất bao nhiêu lâu để ngồi ra được một
[01:29:04] cái mật khẩu như thế này
[01:29:06] dù mật khẩu Facebook của mình hiện tại
[01:29:09] như này ạ
[01:29:09] Ừ
[01:29:12] đấy thì các bạn sẽ tự nhập mật khẩu của
[01:29:15] mình lên đây xem đúng không
[01:29:20] xe Hoa Mai ở Liga Mình thỉnh thoảng mình
[01:29:23] hơi ngáo Tí Nếu không rõ các bạn tra hu
[01:29:26] hu hu I'm hacker thì ra là nó vẫn đang
[01:29:30] là Cái phim đấy thôi Hay mà đúng không ạ
[01:29:31] Ừ ừ
[01:29:34] hu hu i am thì những có sai chính tả
[01:29:38] tiếng Anh xin lỗi à
[01:29:44] mã hóa rồi cho So sánh 2 chuỗi mã hóa
[01:29:48] cái này Thực ra là lại kiến thức nó khá
[01:29:51] phức tạp thì da mình có lọc đấy và nó
[01:29:53] liên quan đến cũng có mình còn lưu lại
[01:29:55] rồi mình nghĩ là sẽ Mình cũng định nói
[01:29:58] các bạn nhưng mà chắc là đến vì sau cơ
[01:30:01] Cái liên quan đến 300 và lưu bát cốc
[01:30:05] đúng cách bạn hãy đọc qua bài này đã
[01:30:08] em xin các bạn ạ Có liên quan đến
[01:30:14] Rainbow table là kiểu hacker nó nó lấy
[01:30:17] được cái data bậy các bạn cái database
[01:30:19] mà các bạn để lưu thông tin tài khoản
[01:30:21] người dùng không lưu lại còn mật khẩu
[01:30:23] người dùng đúng không mà các bạn mã hóa
[01:30:25] rồi thì các bạn phải biết cách mã hóa
[01:30:28] sao cho để cho hacker nó không tra ngược
[01:30:39] khi nhập mật khẩu lên trang này có nguy
[01:30:41] cơ bị đánh cắp không thầy
[01:30:43] Ừ mình không sát bởi vì thừa xây nhiều
[01:30:45] người dùng đấy Nhưng mà nếu là sử trang
[01:30:47] hay bị hack cho mọi bị thay đổi cái gì
[01:30:50] đó thì đương nhiên là cũng đi à Như cái
[01:30:53] này thì ra là nó nó thực ra nó không
[01:30:56] biết được email của các bạn mà thì nên
[01:31:01] là thức ăn nó lưu lại nó cũng 50 50
[01:31:06] 300 về Sam các thứ thì các bạn đúng là
[01:31:09] phải xem cái bài này nữa bài không chỉ
[01:31:11] đi cập về mỗi San đâu thêm xa là chưa đủ
[01:31:13] đâu Nó không phải liên quan đến cả thêm
[01:31:18] mà nên lưu hát ở đâu dùng hàm hát Tuy có
[01:31:21] nên dùng paper paper không Đây chẳng hạn
[01:31:24] thế Bạn đọc thử thấy nó chứng nghiệm rất
[01:31:30] à à Nhưng mà cái này lắm chỉ những ông
[01:31:33] biết tí rồi ông ấy lộc nha các bạn mới
[01:31:36] học Quên Cái quý giá mà đọc cái thấy gọi
[01:31:38] không hiểu đâu có thể đóng não lắm vì
[01:31:41] lên mình mới đọc thì mình phải đọc ba
[01:31:48] Ừ thì bé lý do mà bây giờ các bạn thấy
[01:31:51] thực tế thì cứ thử thì nhiều nhiều trang
[01:31:54] web vẫn chỉ nó còn cho vụ lại gửi chủ
[01:31:58] tịch ạ oke TP gửi điện thoại hay gửi cần
[01:32:00] phải cả mã gì cho nữa chứ bây giờ email
[01:32:03] mật khẩu nó vẫn rất dễ bị lộ đúng Hồng
[01:32:05] Vân Vân Vân Các bạn nên cài bằng một
[01:32:08] thái lớp gì đấy không trừ của thằng
[01:32:10] Facebook phải làm Facebook đôi khi Chính
[01:32:13] Mekong cơ Mày không mò được không Nó hơi
[01:32:14] bị
[01:32:16] nó hơi bị kiểu
[01:32:20] mạng Thủy nói chung mà cái bảo mật
[01:32:22] Facebook kiểu hơi mấy rồi kìa ông có
[01:32:25] thích sai nhưng bay đúng mà ẩm
[01:32:29] thực tế thì nói về toàn ngược lại nó
[01:32:31] giống như này này là đôi khi các bạn làm
[01:32:33] khách hàng quá như thế liền hình các bạn
[01:32:36] bắt thế mà nhập cắt ca rồi nhập bao
[01:32:37] nhiêu thứ ấy mới vào được
[01:32:40] cái đấy để bảo mật người dùng thì đúng
[01:32:42] đấy nhưng mà người dùng cảm thấy rất bất
[01:32:44] tiện người dùng khó chịu hoặc đoạn trích
[01:32:45] ở lúc 10 người dùng bị hack hẳn nick
[01:32:48] thật người dùng một tố cáo thì rất khó
[01:32:53] thế nên mà nó 50 50 đó loa kiểu các bạn
[01:32:55] khóa cửa thôi cũng thế thôi đúng không
[01:32:58] cao bạn địa hình bây giờ các bạn đi ra
[01:33:01] ngoài đường ăn uống ạ Các bạn cũng rất
[01:33:04] ngại việc là phải khóa lạnh xe được các
[01:33:06] dự thứ rồi Thậm chí của ông mang điện 34
[01:33:10] hóa ra là khóa kèm theo còn trống các từ
[01:33:11] từ nữa
[01:33:14] nếu mà các bạn làm thế thì đương nhiên
[01:33:16] là sẽ ra rất khó bị hack hơn khó bị
[01:33:18] nhiều thì xe hơn đúng không Nhưng mà
[01:33:20] cũng là nhược điểm cho các bạn đó chính
[01:33:24] các bạn cũng mở ra là nhắm đúng không Ừ
[01:33:26] cái này nó luôn là luôn là bài toán các
[01:33:27] kiểu
[01:33:30] anh khó cho các bạn thì khó luôn cho cả
[01:33:32] ống trộm đúng không còn dễ cho các bạn
[01:33:35] thì dễ cho cả trộn thì thôi Thế nên là
[01:33:37] hồi trước mình đã từng thấy có một vài
[01:33:40] ông còn chơi cho kịp để đỡ mất công ngồi
[01:33:43] gõ lại mật khẩu Ông ấy cứ tạo một cái
[01:33:45] trang đăng nhập Giả cái thằng hacker
[01:33:47] thích khách gì hack ngoài trang đấy sống
[01:33:50] lấy sử cái ảnh địa chỉ IP ông ấy đăng
[01:33:52] nhập một phát vào luôn không cần Huệ
[01:33:56] không cần phải bao nhiêu khi cả này cũng
[01:33:57] là một cái
[01:34:00] nhiều kiểu là ông ấy cửa chính của ông
[01:34:03] ấy ở luôn khoái nhưng sự ông là khó ngay
[01:34:16] 3 cách để lưu lại lịch sử ngắn trên bàn
[01:34:19] phím như nào nó keylocker nhưng mà không
[01:34:22] biết là các bạn tìm hiểu cái đấy điểm gì
[01:34:25] có phải là đẹp mà thượng lưu lại
[01:34:45] You are a good có bạn hôm trước cũng hỏi
[01:34:48] vụ rocco vậy Oppo Mình nhớ không lầm
[01:34:52] mình nhưng rõ Cô à à
[01:35:00] à À nó cũng lại ăn khuya hả Mình mình
[01:35:03] chưa dùng cái này nếu mà mình nghĩ là nó
[01:35:05] là atwell rồi thì tất cả mấy thằng cái
[01:35:13] à à
[01:35:17] ừ ừ
[01:35:19] Khi nào nào nào lại bảo say từng làm rồi
[01:35:23] nhầm nhầm nhé Mình thì biết Nhiều cá
[01:35:26] nhưng mình lại rất thịnh Mình rất thích
[01:35:28] khách thậm chí thậm chí là mình có độc
[01:35:32] với cả bên A gọi là cái này nói không
[01:35:34] lại hơi Lặc điềm tình yêu mình cũng đọc
[01:35:37] liên quan đến các bài toán về tâm lý học
[01:35:39] các thứ thứ như mình cũng không đi hack
[01:35:41] não người rồi cả mình không dùng cần
[01:35:45] mình Susu socio Angeles để đi mỗi hack
[01:35:48] Hay là thôi miên bất kỳ ai cả tôi cứ thế
[01:35:52] mình mình nghĩ là làm mình cái đấy được
[01:35:55] là nó hơi sai con người mình con người
[01:35:58] mình ạ sống thật nhiều cao là
[01:36:02] ở nhà ngày sắm cái này không sợ chết
[01:36:05] đứng mình đưa cái Mạnh mồm là bởi vì
[01:36:08] thực chất này mình không không sợ mình
[01:36:12] làm gì sai cả không trả lương dân nhé
[01:36:14] cho anh nhìn hồi bé Đi cũng mình từng kệ
[01:36:17] vụ là mình cũng ạ trộm tiền mạng dien S2
[01:36:22] á bỏ học để đi net hay Vân 2 Chỉ à
[01:36:23] sao
[01:36:26] không chờ mức dùng thì thảo là kệ tủ
[01:36:27] khóa thì
[01:36:31] kệ két sắt để mà đi lấy đồ của đồ trong
[01:36:34] gì Trong đấy không biết nhưng mà
[01:36:39] ở nhà mình cũng kiểu ở từng như thế thì
[01:36:41] hồi này rất là dán cái kiểu cứ mỗi lần
[01:36:45] về nhà sợ bị phát hiện cái thứ là
[01:36:51] nói chung là thực à kính người mà mình
[01:36:52] thường anh nói dối nhiều nhất thì đôi
[01:36:55] khi lại chính mình bởi vì mẹ mình đôi
[01:36:58] khi ở quan tâm mình nhiều nên là mình
[01:37:01] đôi khi ở nói dối mẹ ra cặp kiểu mình
[01:37:03] vẫn ổn anh cứ với các mà mình cũng là
[01:37:05] bệnh tật của các thứ chẳng hạn thế Ở
[01:37:08] ngoài ra thì mình sống hay thảm
[01:37:11] các bạn hỏi những cái vấn đề tế nhị yêu
[01:37:23] khi mình còn chưa vào một ít wenger chơi
[01:37:26] mình có nghe qua đã thấy thôi cứ nghe
[01:37:28] nói là nó lấy không dứt được nữa hơn
[01:37:30] mình không làm nữa
[01:37:32] Đúng rồi Thỉnh thoảng thì mình cũng khó
[01:37:35] chơi cho ba cấp để mà để mà thuyết phục
[01:37:38] hiệu trưởng làm vài cái gì đó như thực
[01:37:48] em
[01:37:51] chưa đổi hình như là chuẩn bị Visa cũng
[01:37:54] thành hai tiếng mất rồi Chắc là các bạn
[01:37:59] là tạm tạm dừng lại anh nhá
[01:38:02] bài tập thì chắc là mình tớ bị đăng nha
