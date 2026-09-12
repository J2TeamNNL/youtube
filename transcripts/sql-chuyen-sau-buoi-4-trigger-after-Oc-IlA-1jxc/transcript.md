# SQL chuyên sâu - Buổi 4 - Trigger (After)

- Video ID: `Oc-IlA-1jxc`
- URL: https://www.youtube.com/watch?v=Oc-IlA-1jxc
- Published: 2021-10-28
- Duration: 1h 12m 5s (4325s)
- Language: vi
- Subtitle source: auto
- Kind: live

## Transcript

[00:00:01] à à
[00:00:04] ừ ừ
[00:00:07] anh alo chào các bạn
[00:00:23] Các bạn có vẻ hóng nghe tâm sự cái từ
[00:00:27] đấy nhỉ Mình gì à Chắc Ai gần đây không
[00:00:28] có tâm sự gì cả
[00:00:32] kiểu ngồi tốt xong rồi một Chơi game còn
[00:00:33] ngồi lại
[00:00:36] lại Cốt nó sẽ thế
[00:00:37] à à
[00:00:40] à Xong rồi còn dậy đã đấy Nói chung là
[00:00:42] cả tuần sinh hoạt mình chỉ có gắn liền
[00:00:44] với những cái đấy thế nó chẳng có gì tâm
[00:00:47] sự lắm tâm sự rồi Chắc là tâm sự mỗi về
[00:00:49] chuyện Người cũ rồi
[00:00:51] Cái đấy là cái thứ ám ảnh mình nhớ mình
[00:00:54] nhớ nhiều nhất điều rất là ra không nên
[00:00:57] chia sẻ người cái đấy à
[00:01:00] anh không nên chia sẻ người cái đấy ở
[00:01:09] à à
[00:01:09] Có
[00:01:17] những mối tình cũ của mình được cái
[00:01:21] nhiều lắm tha hồ có cái mà kể nhưng mà
[00:01:25] thức nó không tốt cho lắm thì kéo dài
[00:01:27] vì nó không có gì đáng tự hào hỏi cái vụ
[00:01:34] cô bạn gái người Nhật nào nhỉ Hôm trước
[00:01:36] có ông bờ bạn gái tôi người nhật bạn gái
[00:01:40] tôi người Việt ông ạ Bạn ấy người Đắk
[00:01:56] khi tâm sự về người yêu mới á Ừ thôi bây
[00:01:58] giờ đến giờ học rồi mày thế
[00:02:01] bây bây giờ bắt đầu vào buổi họp nhé
[00:02:05] chia sẻ kinh nghiệm yêu đương mà
[00:02:08] ờ ờ công thức Sự thật thì nó nhà ngày
[00:02:10] một sự thật gì à mình hẹn hò với rất
[00:02:14] nhiều bạn rồi thì chỉ rút ra dùm cái đó
[00:02:15] là
[00:02:18] đương nhiên là rút ra kinh nghiện trong
[00:02:20] chuyện tình cảm cũng nhiều nhưng mà con
[00:02:22] gái chẳng có ai cho mày nhưng thành ra
[00:02:23] lại
[00:02:27] mang tiếng là có thể từng tán được một
[00:02:28] bạn rồi không ở nghĩa với để tán được
[00:02:32] bản khác có thể cách tương tự cái thứ
[00:02:36] chả qua là biết cách thì giỗ biết biết
[00:02:39] cách để mở kiểu kiểu dạng đoán xem bạn
[00:02:42] đấy sẽ ăn gì hết để những cái mà Mấy ông
[00:02:44] có thể đoán được để lâu trải qua nhiều
[00:02:46] mối tình thơ ô
[00:02:50] chữ cũng đoán cũng đoán được để xem lại
[00:02:52] dỗi cái gì Ừ thì mày ông sẽ có kinh
[00:02:56] nghiệm về mấy cái đấy chứ còn à hẹn hò
[00:03:02] chỉ có kiểu khó chịu lấy cái việc là
[00:03:03] à
[00:03:04] còn
[00:03:07] có nhiều trải nghiệm hiểu mình mình
[00:03:11] không quên đấy thế là nó không tốt lắm
[00:03:21] các bạn nóc nhà quá đấy không phải quát
[00:03:23] mình đâu có con chó thôi đừng hiểu nhầm
[00:03:27] Ok Bây giờ mình
[00:03:32] đi xe Fast chia sẻ mình cuối giờ mình sẽ
[00:03:34] trả lời câu của bạn Phương Linh kia điều
[00:03:37] hòa cuối giờ mình sẽ trả lời cái cái đấy
[00:03:39] nó hơi đụng chạm một tí theo góc nhìn
[00:03:41] của mình mà cuối giờ bạn nhớ nhắc mình
[00:03:44] sẽ trả lời cái câu của bạn làm sao đoán
[00:03:46] được thậm chí là tôi sẽ nói làm sao đá
[00:03:48] được con gái rồi làm sao đoán được các
[00:03:55] ở đầu tiên thì mình trả lời mấy câu Hôm
[00:03:59] trước có bạn hỏi đó force Attack
[00:04:04] là gì bởi vì cái cái các bạn Nhớ cái lần
[00:04:06] mà mình nói về cái vụ hametech nghĩa là
[00:04:08] đoạn
[00:04:13] là kiểu kiểu dạng là kiểu mình có đeo
[00:04:16] cặp qua vụ là sẽ có con boss nó sẽ chạy
[00:04:20] dò dò mật khẩu trong liên tục liên tục
[00:04:24] để khi học thành công thì thôi đúng ạ Nó
[00:04:27] sẽ thử mọi ký tự mọi thì tự luôn nghĩa
[00:04:29] là bao gồm cả chữ và Số kí tự đặc biệt
[00:04:32] để mà do mật khẩu thì cái đấy chính là
[00:04:34] pha tách
[00:04:38] thì cài dictionary Attack nó cũng là một
[00:04:41] kiểu dò như thế nhưng nó lại khác một tí
[00:04:44] ở nó rò Nhưng mà theo kiểu dạng là nó sẽ
[00:04:48] là theo tên của người dùng này nó sẽ là
[00:04:50] từ có nghĩa Chứ không phải là tất cả các
[00:04:53] từ và tên nói dùng kết hợp với ngày Ừ
[00:04:56] đấy rau bằng bé ông không bao giờ nên để
[00:04:58] tên hai ngày sinh thích nhất là của ông
[00:05:03] cho cho mật khẩu không tốt đấy thiệu thế
[00:05:04] a
[00:05:08] tiếp theo hết Wow thì sang máy quê ở
[00:05:09] thời
[00:05:12] Anh ơi mình mình chưa chia sẻ cho mình
[00:05:15] xin lỗi mình sẽ gọi E
[00:05:17] Ờ Ờ cái này nó bị lỗi đấy nó bị
[00:05:20] nó cứ mặc định là sao nó màn hình bên
[00:05:23] này rồi nghỉ tí đi
[00:05:25] à à
[00:05:26] ừ
[00:05:28] rồi rồi
[00:05:30] anh em
[00:05:36] em hết Wow thì không có sang máy queo là
[00:05:38] hết were gần như là các bạn kết thúc
[00:05:41] khóa học mày luôn nên là buổi sau mình
[00:05:47] sẽ dậy về cho Jackson và chắc là mình sẽ
[00:05:49] à mình mình bảo là
[00:05:53] mình sẽ thử cân nhắc về vụ là chẳng biết
[00:05:56] buổi sau buổi xong nữa bọn mình sẽ thử
[00:06:01] giun sẽ học quà zoom ờ ờ
[00:06:04] ở buổi tuổi sau mình sẽ học qua room để
[00:06:06] mà có gì còn ạ
[00:06:09] ở đây nghe mình sẽ có quay lại video
[00:06:10] Ờ
[00:06:14] họ có zoom để mà mình sẽ gọi vài bạn để
[00:06:16] nó trả lời câu hỏi vấn đáp nên là buổi
[00:06:18] sau các bạn xác định đi đúng không ạ bữa
[00:06:20] ô mai họp với kiến thức rất là khó em
[00:06:32] Hôm nay có bốn mấy bạn thôi à Ừ bốn mấy
[00:06:34] bạn thử cả qua dùm cũng được đấy không
[00:06:38] ra đâu Anh có dậy tối ưu mà cậu ashwell
[00:06:40] không ra mình hôm trước mình có nói là
[00:06:42] mình sẽ không dạy nâng cao cũng không
[00:06:45] gửi không dậy kiểu và những cái bài toán
[00:06:49] thực tế đến thế thế nên là mình mình chỉ
[00:06:51] gợi ý các bạn rồi các bạn nếu muốn được
[00:06:55] sự tìm hiểu thêm về thực tế là thứ nhất
[00:06:58] là cái túi yêu cầu tối ưu ý nghĩa lắm
[00:07:00] chỉ đạo khiến cho một câu select của các
[00:07:02] bạn mà còn Insert update Delete
[00:07:06] nó chạy nhanh hơn thì cái cái Insert
[00:07:08] update Delete chạy muốn chạy nhanh ấy
[00:07:12] thì thứ nhất ở các bạn không nên cẩu dội
[00:07:14] à các bạn đương nhiên là một lúc Insert
[00:07:18] update nhiều cái cùng lúc ở đây ở đây
[00:07:22] mình mình cho các bạn xem qua nhé đây ta
[00:07:23] sử mình nói nhanh về các vụ Insert đi
[00:07:28] nếu mà các bạn muốn Insert anh đi xâm
[00:07:30] Hôm trước mình đọc cái bài sơn 1 tỷ và
[00:07:33] ghi vào bảng cùng một lúc hỏi cùng một
[00:07:36] lúc nhà mày rớt 1 tỷ và ghi thì đương
[00:07:37] nhiên là các bạn thứ nhất là không nên
[00:07:41] một câu lệnh S1 câu lệnh SQL mà nhưng
[00:07:44] xuất rễ treo chết luôn cả cái con server
[00:07:47] chơi luôn con tơ bay để không lên các
[00:07:50] bạn mình chia ra thì nhưng mà chia ra
[00:07:52] thì cũng không cần phải chia đến nỗi là
[00:07:56] kiểu in xuất từng hàng một thì 1 tỷ mất
[00:07:58] bao lâu rồi ông ạ Các bạn sẽ phải rớt
[00:08:00] như thế nào thì ông đấy có bài chia sẻ
[00:08:04] nó sẽ chia theo nhóm này sau đó thì để
[00:08:07] bể Chánh nghiệp nặng và đảm bảo giả sử
[00:08:10] đảm bảo cơ sở liệu các bạn đúng hết rồi
[00:08:13] theo kiểu là dữ liệu Insert vào sữa
[00:08:15] chuẩn ấy thì các bạn không cần phải mở
[00:08:19] cái các bạn nếu cái con trên không ạ Cái
[00:08:21] con trên này là để mà kiểm tra cái ràng
[00:08:25] buộc theo kiểu là nó nó phải là unique
[00:08:28] này nó nó lu Ừ nó là khoáng ngoại nó
[00:08:31] phải khớp này Vân Vân nó phải thông qua
[00:08:33] hành khách này các bạn nhiều không thì
[00:08:36] cái Giả sử dữ liệu các bạn nó rất là ổn
[00:08:39] rất là đúng rồi Các bạn có thể bỏ qua
[00:08:42] cái vụ còn trên này để cho thay vì cứ
[00:08:44] Insert vào nó lại phải kiểm tra lại toàn
[00:08:46] bộ dữ liệu xem dữ liệu đúng hay không
[00:08:49] thì nó chỉ đơn giản là chạy Insert thôi
[00:08:51] đúng ạ thậm chí là tắt luôn cái Index đi
[00:08:53] cũng được bởi vì các bạn nhớ về cái vụ
[00:08:56] hôm trước mình nói vụ Index là các bạn 7
[00:08:59] dday vào để cho salad nhanh hơn nhưng bù
[00:09:02] lại khi mà các bạn thay đổi dữ liệu thì
[00:09:03] nó là phải kiểm tra
[00:09:06] kiểm tra lại vết kết hợp với việc nó
[00:09:09] phải cập nhật lại nét nữa Thế nên là các
[00:09:09] bạn
[00:09:13] nếu mà có thể các bạn tặng tắt nó đi để
[00:09:15] mà Côi xuất các bạn chạy nhanh sau đó
[00:09:17] các bạn hãy nhắc lại Cải Trạng cả cái
[00:09:20] bảng cũng được thay vì kiểu cư Insert
[00:09:22] đến đâu thì đáng bị rách lại đến đấy Nó
[00:09:25] không cần thiết bởi vì sao Bởi vì bởi vì
[00:09:28] chừng em muốn xe Bac ngay cái đoạn mà
[00:09:30] các bạn kính shop thì các bạn bị đánh
[00:09:32] đít lại đúng ạ Còn bây giờ các bạn đang
[00:09:35] Insert liên tục liên tục mà các bạn C
[00:09:37] lách lại cái đoạn đấy Sáng mình nghĩ là
[00:09:39] chẳng sẽ lách lợn đấy Ăn gì đâu đúng ạ
[00:09:42] thì các bạn thấy là 1 tỷ cái bạn ghi đấy
[00:09:46] các bạn đáng để và kiểm tra lại inbox
[00:09:48] các thứ thứ nó sẽ bị tốn kém thêm tài
[00:09:52] nguyên không ạ tương tự Thế thì cái vụ
[00:09:55] update và Delete thường là các bạn sẽ đi
[00:09:57] kèm với cái wed đúng không ạ thì kệ wed
[00:10:00] này quay này nó sẽ phải dựa trên những
[00:10:03] cái cột mà đã làm Index là sử web tên
[00:10:06] bằng gì gì đó tớ bằng lòng nhận đúng ạ
[00:10:10] thì nếu mà Giả sử một tên tên này các
[00:10:12] bạn mà chưa đánh lên đấy thì cái việc
[00:10:15] wirte này nó sẽ khiến câu lệnh các bạn
[00:10:17] sẽ chậm đi đúng không ạ Các bạn sẽ phải
[00:10:20] đánh Intex có những cái cột đấy nhưng
[00:10:23] cái cột mà các bạn nằm trong Where I
[00:10:27] Ừ đấy thì cả đấy tối ưu và các bạn để
[00:10:29] kiểm tra xem những đất có chạy được hay
[00:10:32] không thì có bạn sẽ thêm chữ Sake kết
[00:10:35] hợp với chữ explain ở trước như thế này
[00:10:37] xong rồi sau đó là
[00:10:39] là câu sẽ nách bình thường các bạn đấy
[00:10:43] thì cái explain nó sẽ trả về cho các bạn
[00:10:46] cái À à
[00:10:50] Ừ cái kiểu dạng là cái con sẽ lấy rồi
[00:10:54] các bạn nó tốn bao nhiêu bộ nhớ này xong
[00:10:57] rồi nó có sử dụng Index 20 này nó dựa
[00:10:59] trên những bảng nào Cột nào vẫn luôn Vân
[00:11:02] và sẽ nó là giải thích màn không ạ thì
[00:11:05] các bạn các bạn sẽ học cách phải học
[00:11:07] cách đọc mình người ấy thì các bạn mới
[00:11:10] biết tôi yêu cầu truy vấn đấy mình qua
[00:11:13] hết mà một lượt cơ bản để các bạn biết
[00:11:15] hướng nếu mà các bạn đang làm về bên tối
[00:11:18] ưu nhé á
[00:11:19] à à
[00:11:21] ờ ờ
[00:11:24] Cho tim mình có dự định dậy Chắc là đệ
[00:11:28] data silde và data-analytic thì phải
[00:11:30] Alice thì
[00:11:33] tim mình hiện tại đang không có chính
[00:11:37] xác là tim Chắc là bạn ý vài nói là yêu
[00:11:41] tim và ban Nói chung nhà sẽ các thầy cô
[00:11:44] ở bên đấy discord thì mấy thầy cô ấy như
[00:11:46] bây giờ đang không chuyên mạnh ngay để
[00:11:48] nó dậy các bạn
[00:11:51] về sau rồi cháu sẽ có thôi có hàm kênh
[00:11:53] ngày rồi mà đông ạ
[00:11:58] Có nên để phân Trần IP tự ý bạn này chắc
[00:11:59] là kiểu
[00:12:00] ờ ờ
[00:12:03] muốn để cụt mã tự động tăng đều gửi thế
[00:12:06] kết hợp cả chữ có số người can như mình
[00:12:08] từng nói thì cái này rồi không không thể
[00:12:11] làm được và bên esquare và không nên làm
[00:12:14] luôn thường công ty nào cũng thường hay
[00:12:16] là chơi thôi cậu là dùng ngôn ngữ lập
[00:12:18] trình để làm cái này thấy chia sẻ cách
[00:12:22] tải tài liệu trên mấy cái trang có vài
[00:12:23] bạn hỏi mình với vụ hôm trước có bạn hỏi
[00:12:26] mình cách tải phim netflix hay cái tới
[00:12:29] nào ạ sẽ các bạn sâu gồ đôi khi đối với
[00:12:31] cả mấy cái trang giống như netflix hay
[00:12:33] là YouTube hay Facebook ra mình cái
[00:12:35] trắng lớn đấy thì kiểu gì cũng sẽ có rất
[00:12:37] nhiều ông từng chia sẻ rồi bởi vì nó
[00:12:39] quốc tế thì kiểu dìm sẽ lòi ra một vài
[00:12:41] ông hacker có khi mấy ông hacker Trung
[00:12:44] Quốc ông ấy cơm người Nga đấy ạ thì ông
[00:12:46] ấy chỉ có chia sẻ về một cái tool để mà
[00:12:49] kêu lấy được link chuẩn mà thể tải được
[00:12:53] cái gì đó còn mấy cái trang cậu nhưng mà
[00:12:56] bài toán thì vẫn là cha mất tiền có sẵn
[00:12:58] mấy ông không không đòi hỏi được việc là
[00:13:00] nếu không có thể dễ Mẹ Của Nó không
[00:13:02] Không thì nó cần câu cơm rồi ra mở không
[00:13:12] a&amp;p không làm tiện ích được
[00:13:15] à à ý
[00:13:19] thì cái cái cái tiết này nếu mà các bạn
[00:13:23] học bên A bên web mình đang nói thì các
[00:13:26] bạn sẽ thấy là một web về cơ bản nó sẽ
[00:13:30] chạy bởi ht lcs và Sweet đúng ạ thì cái
[00:13:32] tiện ích này bản chất nó sẽ Switch để
[00:13:35] chạy song song cùng với web thế nên là
[00:13:39] tiện ích nó mới viết bằng you speak thế
[00:13:41] này là tiện ích cũng không làm được vào
[00:13:43] bằng bất kì cái gì khác ngoài ra Switch
[00:13:45] đâu ạ
[00:13:46] Ừ
[00:13:49] ok trả lời hết câu hỏi các bạn ngày hôm
[00:13:51] trước rồi mình không Chữa bài tập bởi vì
[00:13:54] à buổi hôm trước cả hai buổi hôm trước
[00:13:57] đều bài tập tương đối mình thấy à Chỉ là
[00:13:59] là lại những cái thứ mà mình đã dậy thì
[00:14:03] thế là các bạn xem đủ lại video là cũng
[00:14:05] làm được rồi nếu mình mới bỏ qua đâu mà
[00:14:08] cho dù các bạn làm bài tập cũng hay đấy
[00:14:12] Mình thấy à các bạn làm các thứ mình vẫn
[00:14:15] sẵn là trả lời đầy đủ mà ok Nói chung ở
[00:14:18] hôm nay đến buổi đến cái khó rồi các bạn
[00:14:23] buổi cuối rồi đang có 59 ông hi vọng ở
[00:14:25] tôi dậy xong buổi này Mấy ông không rụng
[00:14:28] dần về đây sẽ buồn mình vẫn khẳng định
[00:14:31] đây sẽ là cái khó
[00:14:35] thì đầu tiên thì shipper là cái gì a
[00:14:39] checker nó nếu dịch thô ra rồi nó là cò
[00:14:43] súng theo kiểu lại cái thứ gì Nó là cái
[00:14:46] kiểu canh ăn không biết có xúc tác dụng
[00:14:49] ở gì không là để ngăn không cho bắn thì
[00:14:54] phải nhớ dễ đấy thì
[00:14:57] Ừ thì tất cả Và và nó Khánh nghiệm chế
[00:14:59] Cơ nó sẽ khái niệm Tại sao tự nhiên tôi
[00:15:01] nhắc cò súng đây vì nó có khác nghiệm
[00:15:05] file recover được kích hoạt có súng cũng
[00:15:08] mà cũng là khi kích hoạt cái cơ Cái
[00:15:11] chích Cơ nó sẽ được kích hoạt trong ba
[00:15:13] trường hợp
[00:15:16] trong trong chính xác là có 3 loại cây ở
[00:15:19] gần đấy bà loạn chị giao nhé
[00:15:22] đó là loại Thứ nhất đó là khi cơ về rock
[00:15:25] in tức là khi đăng nhập khi đăng nhập
[00:15:27] xong thì sẽ kích hoạt thì chị thơ này ờ
[00:15:28] ờ
[00:15:31] ý thì cái loại này mình sẽ không dậy Bởi
[00:15:33] vì thực sự nó chẳng có gì đặc sắc cả
[00:15:36] mình sẽ Đề cập về loại thứ hai và loại
[00:15:41] thứ ba nó sẽ là loại đầu tiên thì cái cơ
[00:15:43] bản cái cơ bản trước nhé cái dễ trước
[00:15:47] nha nó vào loại after I Ừ ông đoán được
[00:15:48] cái loại
[00:15:52] after dịch ra là gì mày không đi học à
[00:15:55] à À còn một buổi nữa trang sức Rừng Quê
[00:16:00] ờ
[00:16:03] ờ Nếu không thử gì cho tôi after là gì
[00:16:05] mà Mấy ông đoán luôn cả loại Thứ ba là
[00:16:07] gì đi
[00:16:10] khi bị vọng Alo
[00:16:12] vị vọng ạ
[00:16:27] kể chi cầu after là sau khi ở ngoại
[00:16:41] cái loại Thứ ba là gì
[00:16:43] không Không chơi việc là mấy ông lên sư
[00:16:47] cái tràn tôi rồi đọc trước rồi nhé I
[00:16:48] em
[00:16:51] không nghe máy ông sẽ nghĩ là nó sẽ
[00:16:52] before không ạ
[00:16:55] Hình như có chị có sau thì anh phải có
[00:16:57] trước đúng không em à không không không
[00:16:59] không quên lúc đầu mình tưởng thế nó sẽ
[00:17:03] là inter nó thay thế
[00:17:07] Còn đây là after là sau khi lại đầu nhọn
[00:17:09] sau khi làm cái gió thì sẽ được kích
[00:17:11] hoạt chất xơ còn đi Speed là bảo nó thay
[00:17:14] thế hẳn luôn cái câu lệnh Đấy bằng một
[00:17:18] cái gì đó để không ạ Cái có bạn từng hoa
[00:17:21] mắt mình mình bạn ấy có gặp gỡ Floor
[00:17:22] Floor đấy
[00:17:26] thì for nó sẽ bằng để after cũng đều bạn
[00:17:29] là sau khi nhá đâu ạ nghĩa là về cơ bản
[00:17:31] là mình sẽ chỉ có ba cái chị cười thôi
[00:17:33] đừng ạ
[00:17:36] Có trang mã mấy ông đúng không để ý gì
[00:17:39] cả thì cao trong mô tả của tôi đang đi
[00:17:41] cập thì chưa
[00:17:45] Tôi để lại cái link nhé á
[00:17:47] để
[00:17:49] chứng tỏ Nếu không phải đọc mô tả của
[00:17:51] tôi buồn vãi
[00:17:56] đề
[00:18:02] thi ok Bây giờ thì để mình dậy các bạn
[00:18:04] thì trong nhà mình vừa nói đó là không
[00:18:07] dậy về wine mà mình sẽ dậy sau khi thi ở
[00:18:10] đây cái sau khi ở đây mình muốn làm cái
[00:18:13] gì Giả sử là sự nhé Ở đây có một cái bài
[00:18:16] toán đơn giản nghe đi mình à
[00:18:17] thì
[00:18:20] mình sẽ
[00:18:23] mình sẽ mở cái Excel lên cho bạn sẽ hình
[00:18:24] dung
[00:18:35] các bạn sinh viên ở nào ạ
[00:18:36] các
[00:18:39] bạn sinh viên
[00:18:42] Giả sử mình có cột mã của tên vẫn như cũ
[00:18:45] ở đây vẫn còn mã của tên này đúng ạ Như
[00:18:48] đỡ nhiên và sinh viên sẽ có mà lớp đông
[00:18:51] ạ Thì hồi trước cách để mà lấy toàn bộ
[00:18:54] sinh viên của một lớp nào đó đúng ạ thì
[00:18:59] các bạn sẽ thấy là à mình sẽ dùng xe
[00:19:03] lách cao form form bằng accounts for bản
[00:19:07] sịt for bảng lớp cho ấy bạn sinh viên để
[00:19:10] mà lấy toàn bộ sinh viên của lớp đấu
[00:19:12] ngoãn thì thì
[00:19:15] bây giờ mình làm theo kiểu khác khác một
[00:19:17] tí đi để ông ạ ra xử là mình muốn lưu
[00:19:20] lại luôn cái việc số lượng sinh viên của
[00:19:22] một lớp ở trong một cột ở trong mảng lớp
[00:19:26] luôn để về sau mình đỡ mỗi lần mình và
[00:19:28] truy cập vào mình đỡ phải mất công cao
[00:19:30] lại nó còn gì thường là nó sẽ cố định
[00:19:34] theo năm học gì gì đó đúng ạ biểu cảm 15
[00:19:37] gần như là nó sau khi thay đổi số lượng
[00:19:40] sinh viên đúng ạ thì các bạn có mỗi lần
[00:19:42] truy cập vào các bạn lại đến lại Thực ra
[00:19:47] nó không tốt về về xử lý thế nhưng đương
[00:19:49] nhiên mà như mình từng nói đó là liên
[00:19:53] quan việc bài toán sai về cái dữ liệu
[00:19:55] theo kiểu là các bạn hạn chế lưu cái cột
[00:19:58] mà có thể tính toán từ cái dữ liệu khác
[00:20:00] đúng ạ khi ví dụ Giả sử với ông những
[00:20:02] thay đổi sinh viên thì đương nhiên là số
[00:20:04] lượng nó lại thay đổi không ạ thì hôm
[00:20:05] nay mình sẽ dạy các bạn chích cơ Để làm
[00:20:08] thay đổi rồi đấy là sử ở đây là số lượng
[00:20:11] sinh viên trong lớp đó ngoãn thì sẽ lưu
[00:20:13] lên thêm cột này thì đương nhiên lúc đầu
[00:20:16] Giả sử có một lớp nó đi đúng ạ một lớp
[00:20:19] mã là một này làm
[00:20:22] lớp là SQL chẳng hạn đóng ngoặc số lượng
[00:20:25] là sông này đúng ạ Đây nghĩa là mình tạo
[00:20:27] ra lớp này trước lớp mày đang chưa có
[00:20:30] sinh viên nào đúng ạ Thế bây giờ Bây giờ
[00:20:32] giả sử mình tự nhiên mình thêm một bạn
[00:20:34] sinh viên vào chẳng hạn đúng không ạ ra
[00:20:36] sửa mình thêm bạn Long vào cái mà lớp là
[00:20:41] một thì có phải là bây giờ thì mình phải
[00:20:43] hiểu là mình phải cập nhật lại cái số
[00:20:46] lượng sinh viên này tăng lên là ờ đúng à
[00:20:49] cho cả lớp chép Wow Giả sử đây có hai
[00:20:53] lớp đi sử có hai lớp đi là web này
[00:20:57] số lượng cũng là không này thì rõ ra là
[00:20:59] bạn thấy ở đây có hai lớp nhưng mà nó
[00:21:02] cập nhật cho lỡ nào thôi ạ cập nhật cho
[00:21:05] mỗi lớp SQL Tại sao lại cập nhật cho mỗi
[00:21:09] lớp em cao ạ đúng không ạ em ngủ ngon bé
[00:21:10] ông trả lời dần dần mấy câu này dần đi
[00:21:13] nhé Ngủ ngon thì tại sao nói cập nhật
[00:21:15] trong mỗi lớp SV mà không phải là lớp
[00:21:25] Ê mấy ông có ăn theo kịp tôm ấy Ok bạn
[00:21:28] Khi trả lời đầu tiên có vẻ đúng rồi
[00:21:30] không ạ dựa theo em mà lớp bằng một đúng
[00:21:34] ạ thì thì rõ ràng là ok ở đây giả sử
[00:21:36] mình y rớt một bạn mới đúng không ạ thì
[00:21:39] thì lấy cái cột mã lớp của họ đúng chưa
[00:21:42] vậy Lấy cột mã của họ đúng không lấy cốt
[00:21:45] mãi là nọ của nó sau đó thì bắt đầu xem
[00:21:48] lại sao mở lớp là à với cái mã này thì
[00:21:51] tương ứng với cái lớp nào sau đó thì cập
[00:21:54] nhật số lượng cho họ đúng không ạ
[00:21:56] Anh thấy bây giờ trước mắt thì tôi làm
[00:21:59] chỉ cơ để làm cho đoạn này đã thì mới
[00:22:01] ông hiểu nhé Ok đầu tiên tôi tạo bà đúng
[00:22:05] không biết thấy bồ này lớp này
[00:22:09] khi mã này in DAMtv tự động tao không ạ
[00:22:13] bên này phải tra 50 chẳng hạn
[00:22:15] a
[00:22:17] marikina
[00:22:23] em có bạn lớp rồi
[00:22:28] ra đi cross hết đi con như nào lại hết
[00:22:29] từ đâu
[00:22:30] Ừ
[00:22:33] để chắc là thôi Về Đó Chắc mình sang hẳn
[00:22:37] cái tem thêm tay Mày biết tao ở Pari này
[00:22:40] tạm thời PB này mình làm cái gì xong cái
[00:22:44] này thì khi mắt cái nổi thì hình như là
[00:22:47] cái cái dữ liệu nó sẽ bị xóa thành ra là
[00:22:49] mình hoàn toàn bộ sau không bị ảnh hưởng
[00:22:52] bụi trước cũng được đấy Giả sử là bây
[00:22:55] giờ mình cắt in such trước hai lớp nhá
[00:22:58] lớp này á đông Nhầm nhầm nhầm thiếu cột
[00:23:03] kiểu cột và rồi cho thấy bồ lớp này chưa
[00:23:05] có thể enter nó cũng được nhưng mình
[00:23:06] đang muốn làm nhanh
[00:23:09] số lượng sinh viên không ạ số lượng sinh
[00:23:11] viên đi tạm bỏ qua trách chùm các thử
[00:23:15] nhé sự là cũng hiểu là số lượng sinh
[00:23:17] viên nó không được ăn mày cứ thử đi Mình
[00:23:20] sẽ để defo là không đi thì thôi là không
[00:23:21] đúng
[00:23:23] ở nhà lúc đầu chưa sinh viên nào đúng
[00:23:26] không ạ sử mình có tên này
[00:23:28] và lu nó này
[00:23:33] là espier này sau đó đi web đúng không ạ
[00:23:36] web này là sự đang có hai lớp đúng không
[00:23:42] ạ sau đó thì snack sao for love
[00:23:45] sau đó thì các bạn sẽ thấy là ok bây giờ
[00:23:46] đang có
[00:23:49] em đang có hai lớp đúng số lượng sinh
[00:23:51] viên là không đúng rồi đúng không ạ Bây
[00:23:54] giờ mình tạo bàn tiết thì tạo bảng sinh
[00:23:56] viên không ạ sinh viên này
[00:24:00] mì đây mình sẽ thay đây là mà lớp này
[00:24:03] kiểu gì nè sau đó thì đương nhiên là có
[00:24:06] khóa ngoại ràng buộc cho nó chắc đi còn
[00:24:14] lớp tại cột mã sản ạ ạ
[00:24:21] Em nói đi này khi bây giờ giả sử mình
[00:24:25] Insert into sinh viên nhá tên này mã lớp
[00:24:27] đúng không ạ
[00:24:31] ba lô là Long
[00:24:36] và lớp thứ nhất đúng ạ chạy thử này
[00:24:39] ạ sau đó Thì bây giờ mình sẽ select sao
[00:24:43] cả lớp này Các sinh viên à à
[00:24:47] thì chả như này các bạn sẽ thấy là ở đây
[00:24:50] ở đây sinh viên cập nhật vào trong lớp
[00:24:53] đúng rồi không đi sai cả nhưng số lượng
[00:24:56] của sinh viên của cả lớp mà mới thêm vào
[00:24:58] đúng không ạ thì số lượng nó vẫn bằng
[00:25:01] không thế là sai rồi khô ngọn tích trong
[00:25:03] trường hợp này khi mình cần làm như thế
[00:25:06] nào mình cần là một có một cái gì đó tác
[00:25:09] động cập nhật lại số lượng tự động tự
[00:25:11] động nhé nghĩa là cứ mỗi lần hơn sinh
[00:25:14] viên mới thì nó phải tức động cập nhật
[00:25:16] lại số lượng thì nó mới đúng đúng không
[00:25:17] ạ
[00:25:17] Ừ
[00:25:21] nếu mà bộ hôm nay mà dạy chơi cờ mỗi cái
[00:25:24] chích girl after mà mà chưa xong thì
[00:25:27] mình chắc chắc là phải mất cả một buổi
[00:25:31] sau nữa từ buổi sau dậy cả chích cơ khí
[00:25:33] xếp hợp cũng được kết hợp với Trang sẽ
[00:25:35] dừng cũng được nghỉ buổi sao bạn ơi thế
[00:25:38] bởi vì riêng chứ Cô ấy rất dài nếu không
[00:25:41] có tập trung nghe và tại thì
[00:25:43] ạ Bây giờ mình cập nhật số lượng nó sẽ
[00:25:46] như sau mình sẽ phạm cái cơ hạ điệp khúc
[00:25:49] Trap này chị cơ này cho tên của vị trí
[00:25:52] cơ này là thêm sinh viên em ạ
[00:25:55] tôi không đùa với ông đâu nó khó lắm
[00:25:58] sống dựa trên cục trên bảng vì nó sẽ quy
[00:26:01] ước thẳng và trên bạn vì luôn nó là sự
[00:26:04] trên mạng sinh viên này và tiếp theo đó
[00:26:08] là cái kiểu của nó là kiểu gì kiểu đấy
[00:26:11] là kiểu after không ạ Và
[00:26:14] à mà tiếp theo đó nữa là mình phải dựa
[00:26:17] trên kết cái phương thức gì phương thức
[00:26:20] Insert update Delete sẽ có 3 phương thức
[00:26:24] để mà tạo chị cơ 3 phương thức bml các
[00:26:27] bạn nếu đ m n là data
[00:26:31] mandu pilation high school net gì đấy
[00:26:37] many full Lysine và thật là cậu chi phối
[00:26:40] ngôn ngữ chi phối dữ liệu cái kiểu thế
[00:26:44] nó sẽ là Insert update Delete
[00:26:47] tái chế Cơ nó sẽ chạy trên cái dml dựa
[00:26:49] trên ba cái này thì với ở trong trường
[00:26:51] hợp này là in sơ đồ ngoại mình sẽ dựa
[00:26:54] trên in shop này
[00:26:57] này BV này em này đề
[00:27:01] thi cái bài toán ở đây thì như mình vừa
[00:27:04] nãy nói lại phải quay lại cái xem một tí
[00:27:06] ạ như vừa nãy mình nói là bây giờ mình
[00:27:08] thêm một bạn sinh viên mới này ra xử mã
[00:27:11] bạn để con 10 đi đừng ạ thì rõ ràng là
[00:27:13] các bạn vẫn sẽ hiểu mã của bạn này Bây
[00:27:15] giờ thì ra nó không quan trọng gì cả
[00:27:17] đúng ạ
[00:27:20] a mã bạn ấy đã không hề quan trọng mà mã
[00:27:23] bạn này mã lớp của bạn đấy mới quan
[00:27:25] trọng mình sẽ phải lấy cột mã lớp này
[00:27:28] sau đó thì mình Cập nhật lại mình tìm
[00:27:30] phải không bảo đó xem là cái mã nào phù
[00:27:32] hợp với các bạn lớp đấy hội cập nhật Số
[00:27:35] lượng số lượng bây giờ phải cầm điện lên
[00:27:43] thì các bạn cứ trả lời mình dần dần đi
[00:27:46] rồi rồi các bạn sẽ hiểu tại sao mình hỏi
[00:27:49] mấy câu kiểu hiển nhiên như thế
[00:27:53] nó lên mấy nó lên mười nó lên hai nó lên
[00:27:57] 1 lên 10 ạ Ok các bạn sẽ hiểu ở Ok Bây
[00:28:00] giờ nó lên 1 đó giả sử bây giờ sự tại
[00:28:03] thêm một bạn nữa Bạn tên Tuấn em ạ lại
[00:28:07] cũng mã lớp là một thì thì bây giờ nó sẽ
[00:28:09] như thế nào ạ
[00:28:11] ạ bây giờ phải thay đổi với chị ạ Hãy Cứ
[00:28:13] thế thôi
[00:28:16] Ừ ông kia lên 10 thật kìa có lên là hai
[00:28:19] cái gì lên là 2 Nếu quan trọng cái gì
[00:28:22] lên là hai cái này lên là hai hai cái
[00:28:25] này lên là 2a
[00:28:28] Ừ đúng rồi bạn kia nói cái bạn trái
[00:28:30] nhưng không khét kia Bạn này nói mới
[00:28:31] chuẩn kìa
[00:28:34] các bạn nó nói dùng lực cộng một nó mới
[00:28:37] chuẩn không không Đừng có phân biệt 2 2
[00:28:40] 3 4 tỷ đây cả đúng ạ ạ ạ
[00:28:45] Ừ cái cái ý mình mong muốn muốn hỏi đây
[00:28:47] thứ nhất đó là các bạn phải giữ giải mã
[00:28:50] lớp để cập nhật cho thằng này hai thằng
[00:28:54] này đúng ạ và phải lấy cái số lượng sinh
[00:28:58] viên cũ và tăng nó lên cộng một chứ
[00:29:00] không phải ghét nó bằng hai luôn bởi vì
[00:29:03] như bạn vừa nói là tăng lên là hai thì
[00:29:05] ok bạn đã hiểu nó lên là hay nhưng mà
[00:29:07] bây do các bạn biết đến các bạn thấy ở
[00:29:09] đây có một ít sinh viên thì các bạn đang
[00:29:11] đếm được thì các bạn vào hai bây giờ sử
[00:29:13] bây giờ mình yên tâm phần trăm sinh viên
[00:29:15] đây thì các bạn không đến được nó là bao
[00:29:17] nhiêu đây đúng ạ thì các bạn sẽ phải
[00:29:20] hiểu lại cứ thêm một bạn sinh viên nạp
[00:29:24] vào thì lấy số lượng sinh viên cũ + lên
[00:29:25] 1
[00:29:27] em Treo mạ lớp đúng rồi bạn tiền là đúng
[00:29:30] rồi theo mã lớp thì nó mới chuẩn
[00:29:32] Ừ đúng ạ
[00:29:36] thì ở đây để làm đơn giản chưa các bạn
[00:29:39] thì bây giờ mình cứ mình bây giờ để mà
[00:29:42] mình có cái chích ga này bây giờ nhớ cậu
[00:29:44] nhớ con này của tôi nha Cái gì chỗ hỏi
[00:29:48] vấn đáp hỏi câu này à à chích cơ một khi
[00:29:50] nó chạy bất kỳ cơ
[00:29:54] bất kỳ cơ Insert update Delete một khi
[00:29:56] nó chạy nó sẽ luôn có hai bạn được sinh
[00:30:00] ra đều ạ nó bản chất thật và bạn đi
[00:30:02] lasted
[00:30:05] bảng Asus tin tức là lưu lại những cái
[00:30:08] cái thông tin mà các bạn sẽ in search
[00:30:12] trước khi mày Insert vào trong bảng viết
[00:30:15] tên cũng thế thôi đó là là lưu lại thông
[00:30:17] tin các bạn sẽ Delete trước khi chạy có
[00:30:20] Delete thì
[00:30:23] Ờ Ờ bây giờ để mà muốn lấy cái mã lớp
[00:30:26] của một bạn giả sử cái bạn lo vừa rồi
[00:30:28] đúng ạ mình giả sử mình chữ Insert vào
[00:30:31] trong trong bảng trong bảng sinh viên
[00:30:34] vội chim à chích girl chạy ạ Bây giờ các
[00:30:36] bạn đang hiểu là chị có after đ
[00:30:39] à À đúng rồi chết rồi after nghỉ ngựa
[00:30:41] chạy xăng xử rồi không ạ nhưng mà vẫn
[00:30:43] thấy được từ cái bản in xuất thật nha
[00:30:46] mặt lấy được từ bài xuất Tuy rằng nó
[00:30:50] chạy Xong rồi chuyện cái after là chị cơ
[00:30:53] chạy Xong sự A chạy sau khi mà in sẽ
[00:30:56] Xong rồi mày không ạ Mình vẫn lấy lại từ
[00:30:59] bản in sẽ tập được và mình sẽ lấy cái mã
[00:31:01] lớp của cái thằng sinh viên đấy để mà
[00:31:04] Cập nhật lại xong mạng lớp
[00:31:08] đây sẽ như sau ra xử mình có sẽ lexar
[00:31:10] for instant để các bạn sẽ hình dung đã
[00:31:12] chạy thử này
[00:31:15] ạ Bây giờ giả sử mình Insert lại các bạn
[00:31:17] sinh viên kia đúng ạ Thế mình đi xét lại
[00:31:19] nhé ạ
[00:31:23] vì thế các bạn sẽ thấy là nó tự động xe
[00:31:26] lách luôn sẽ lách luôn Đúng cái mà bạn
[00:31:29] mình gửi anh sắp đâu ạ nó sẽ tự động đi
[00:31:31] sớm à sẽ lách lại luôn nhé Mình không
[00:31:34] cần cái thứ mình không cần là cái này mà
[00:31:36] mình cần lấy mỗi mã lớp thôi đúng không
[00:31:38] ạ Rồi mình Cập nhật lại mã lớp thì đây
[00:31:41] nó sẽ khái niệm này các bạn sẽ gán biến
[00:31:46] cho nó bị sẽ có khái niệm và đi clip
[00:31:49] gà nó nóng hổi biến là sửa mình đặt tên
[00:31:52] biển mà lớp kiểu y là bằng này
[00:31:55] snacks mã love
[00:31:59] from instant như này thì tại sao tự
[00:32:01] nhiên mình ở đề cập với cái biển mã lớp
[00:32:04] ở đây làm gì bởi vì như mình vừa nói đó
[00:32:06] là mình sẽ phải cập nhật lại bảng lớp
[00:32:09] theo cái cột mã lớp không phải là cập
[00:32:11] nhật cho lớp bằng hai và cập nhật theo
[00:32:15] cho đúng cái cột mà lớp đẩy đồng loại và
[00:32:17] số lượng nó sẽ tăng được ạ thì ở đây sẽ
[00:32:26] Ai Cập nhật cho cột số lượng sinh viên ở
[00:32:29] ông ạ bằng số lượng sinh viên cũ + lên
[00:32:35] một Where mã bằng mã lớp như thế này ông
[00:32:37] mà không thích khai bão biển thì ông có
[00:32:41] thể hai cái đoạn này bằng cái này cũng
[00:32:44] được không ghi sai cả nhưng mà nhưng mà
[00:32:47] tôi khuyên là cứ làm như này nhìn nó rõ
[00:32:50] làm tượng Minh đã đúng không ạ Đấy Và
[00:32:52] nếu các bạn thích thì các bạn thể giống
[00:32:55] như kiểu vô sadda ý là các bạn hoàn toàn
[00:32:56] thể
[00:32:59] select Sao lại Xem lại nhìn nó tiện đúng
[00:33:03] không ạ Đấy bây giờ bởi vì bây giờ các
[00:33:05] bạn xem mà thấy là bây giờ thứ nhất là
[00:33:07] số lượng sinh viên lên rồi mà số lượng
[00:33:09] Đây nó đang như thế này thì nó hơi sai
[00:33:12] đúng ạ Thì bây giờ mình sẽ
[00:33:14] thì mình sẽ tạm Delete nó đi đã
[00:33:19] đi lấy thẻ không ạ form sinh viên à
[00:33:23] mình cứ xóa trước đi đã sao mình cứ tạo
[00:33:25] jesica này
[00:33:27] anh ở đây nó sẽ bảo lỗi là chị thơ này
[00:33:31] đã được tạm rồi thì cách 2 của mình mình
[00:33:33] nhớ mình toàn dậy các bạn về cái vụ là
[00:33:36] mình dốt còn đi rồi quết lại đúng ạ Như
[00:33:38] hôm trước mình thấy có cái hay có một
[00:33:42] cái hay này press enter đây đó là đó là
[00:33:44] thêm hoặc thay thế Cái này khá là tiện
[00:33:47] này để đỡ mất công dốt cứ chạy cái này
[00:33:50] là được ok bây giờ sử Mỹ đi sót lại các
[00:33:53] bạn xem này đó thì nó sẽ cập nhật số
[00:33:56] lượng cho cho đúng bảng lớp về thôi đúng
[00:33:59] ạ Mình chạy lại lần nữa này đó thì nó sẽ
[00:34:02] tăng lên thôi Bởi vì sao Bởi vì số lượng
[00:34:05] sinh viên thay đổi mà mình mình thử xe
[00:34:08] khách cả sinh viên cho bạn dễ nhìn nhé
[00:34:12] mà mình quét lại phát nữa này Đấy mình
[00:34:13] chạy lại
[00:34:16] ở đây mình đang có 3 sinh viên ở trong
[00:34:20] lớp SQL đúng không ạ thì nó sẽ tăng dần
[00:34:22] dần dần lên đúng không ạ
[00:34:25] đoạn đến đoạn này mấy ông có tài chứ
[00:34:27] ở đoạn này không hẳn là khó hiểu lắm
[00:34:31] đúng không Chỉ là lấy cái cột mã lớp của
[00:34:36] của cái cái bạn sinh viên định Thêm vào
[00:34:39] cho cập nhật số lượng đúng ạ
[00:34:41] ở cái đoạn này thì chắc là các bạn hiểu
[00:34:43] rồi có thể kiến thức nó hơi mới ví thôi
[00:34:45] đúng không ạ Đúng rồi bạn kia đang hỏi
[00:34:47] cái câu chuẩn kìa in rất nhiều sinh viên
[00:34:51] thì nó khó nghiệp Nhưng mà cái này chưa
[00:34:55] chưa chưa chưa tôi vẫn chưa dậy cứ bình
[00:34:57] tĩnh bình tĩnh thưởng gì Thượng sẽ dạy
[00:34:59] mày ông về cái vụ là in rất nhiều bạn
[00:35:00] cùng một lúc thì nó sẽ như thế nào
[00:35:03] Okay đến đoạn này thì các bạn thấy quá
[00:35:06] tải chị ạ chưa ông ạ Dễ mà Dễ hiểu mà
[00:35:08] đúng không ạ Ok bây giờ đến đoạn khó hơn
[00:35:12] này Thế bây giờ giả sử tôi đi lết một
[00:35:16] bạn khỏi cái lớp đấy thì số lượng đó
[00:35:18] thay đổi không ạ
[00:35:21] I Delete một bạn sinh viên khỏi cả lớp
[00:35:24] đấy ra xưởng bạn kia bị đuổi học chẳng
[00:35:28] hạn đúng ạ là sự bạn một trong ba bạn
[00:35:31] này bị đuổi học là xử thế kiểu mạng hoặc
[00:35:34] là do là cô giáo thêm nhầm Bạn này hay
[00:35:36] phát nên là xóa bớt mà bạn đi thì rõ
[00:35:38] ràng số lượng sinh viên nó phải thay đổi
[00:35:39] đúng không ạ
[00:35:41] Ừ đúng chưa Thì cái này cũng có thể áp
[00:35:43] dụng chích Ơ được đúng ạ thì mình sẽ
[00:35:51] ờ
[00:35:55] ờ đúng rồi bạn kia nói đúng đấy có - 1
[00:35:58] lấy từ bảng đĩa cực quá chuẩn luôn nó
[00:36:01] đúng đấy đầu tiên tôi thử vụ thêm thử
[00:36:04] vạn sinh viên và rốt thứ hai mấy ông
[00:36:06] thấy vẫn lên được không ạ nhưng bây giờ
[00:36:08] là sự tôi xóa cái bạn bạn một bạn sinh
[00:36:11] viên đi đúng không ạ thì mình cần làm ở
[00:36:14] đây là gì thì như tội như tôi vừa nói đó
[00:36:17] là sự thôi xóa cái bạn Thứ 5 này chẳng
[00:36:19] mã bằng 5 này chả bạn không ạ thì lại
[00:36:21] phải lấy cột mã lớp từ bạn biết thật sau
[00:36:23] đó thì lại Cập nhật lại số lượng thôi
[00:36:25] cái đoạn này thì các bạn nó tương đối dễ
[00:36:28] nó giống hệt hàng ngày đây mình sẽ thử
[00:36:31] chỉ các bạn nó giống hệt như nào đây
[00:36:35] thay Sói đúng ạ Để Delete này cũng lấy
[00:36:37] cột mã lớp nhưng mà lần này từ bạn biết
[00:36:40] thực này sau đó cập nhật số lượng này
[00:36:43] hai cái này ở - 1 thôi thế này xong rồi
[00:36:50] chạy thử nhé Ừ nhanh đúng ạ Đây Delete
[00:36:53] from sinh viên Này
[00:36:58] Where mã bằng 5 đúng không ạ
[00:37:11] Ừ Ok cái này vẫn là dễ vẫn là dễ giờ lại
[00:37:14] khó lên một tí này
[00:37:17] ở belem chín mấy ông được Tại sao càng
[00:37:21] càng khó càng thêm nhiều này Ok hãy nghe
[00:37:24] tiếp nhé bây giờ xử là
[00:37:27] Ừ cái bạn Long có mã là bố này đi đúng ạ
[00:37:31] bạn đấy lại đổi sang lớp thứ hai giờ xử
[00:37:33] bạn thích quét hơn thích Maxwell đã đổi
[00:37:35] sang lớp thứ 2 thì cái bài toán ở đây nó
[00:37:39] lại phức tạp hơn đúng ạ Nó lại mình phải
[00:37:41] cập nhật lại số lượng không những ở một
[00:37:43] lớp mà mình phải cầm được số lượng loại
[00:37:46] 2 lớp đúng hạn thì rõ ràng mà ta sử bạn
[00:37:50] này đổi sang bạn ạ nắp bếp mã lớp sang
[00:37:54] lớp thứ 2 đúng hạn thì rõ ra mà cái lớp
[00:37:56] thứ nhất bạn đấy phải trừ số lượng đi
[00:38:00] đúng ạ và lớp thứ hai bạn phải + số
[00:38:03] lượng lên nhưng mà bệt để nói theo kiểu
[00:38:05] theo dữ liệu như thế thì ở đây nói theo
[00:38:09] kiểu khác thì nó sẽ nhà phải lấy cái bạn
[00:38:11] mà thay đổi thông tin nữa ngoan Lấy cột
[00:38:14] mã lớp cũ của bạn đấy để mà cấp để mà -
[00:38:17] cái số lượng lớp
[00:38:20] - số lượng sinh viên theo cả mã lớp xe
[00:38:25] tải phím cho mình phải đi tiên à Lấy mã
[00:38:27] lớp
[00:38:33] à cũ này đúng ạ sau đó thì cập nhật số
[00:38:37] sinh viên
[00:38:42] - một theo mã lớp cũ chuẩn đi ạ
[00:38:45] ạ sau đó Đương nhiên là cũng phải lấy mã
[00:38:48] lớp mới đúng ạ Đấy mà lớp mới này
[00:38:51] sau đó thì lại cập nhật số lượng sinh
[00:38:53] viên + 1
[00:38:56] em Treo mạc lớp mới
[00:39:00] thì Dạo này mấy ông hiểu ạ vừa nói xong
[00:39:08] Ừ dạo này sao mày không hiểu lắm ạ Thế
[00:39:11] là mình khi mình update update đổi sinh
[00:39:21] anh
[00:39:24] không bạn bạn kia đã nói việc cập nhật
[00:39:26] nhiều sinh viên cùng một lúc cái đấy tôi
[00:39:28] vẫn chưa chưa chưa Dậy chưa Dậy chưa Dậy
[00:39:30] chưa Dậy à
[00:39:33] A và
[00:39:35] Ừ để không cho Insert một cái gì đó
[00:39:38] chính là buổi sau sẽ học đều ạ
[00:39:40] ê ê
[00:39:44] Ừ bắt đầu khói không ạ thì ở đây ở đây
[00:39:47] thì cái vụ đúng rồi bạn kia nói rất đúng
[00:39:51] cũng cùng lúc Insert + Delete chính là
[00:39:53] update Đúng rồi đấy ạ nghĩa để lấy được
[00:39:57] cái mã lớp cũ và thì mình sẽ lấy từ bảng
[00:40:00] Dell Asus còn lấy mãn lớp mới thì sẽ từ
[00:40:03] bản in xác thực để bọn họ sẽ như này
[00:40:07] flash chơi cờ
[00:40:09] chỉnh
[00:40:15] on sinh viên
[00:40:18] Tôi có thể copy nhà mà tôi Gõ lại cho
[00:40:21] mấy ông đỡ quá tải đấy Thiệu vẫn còn bắt
[00:40:24] sóng theo kịp được gì nè
[00:40:30] đi Cola này mã love cũ
[00:40:34] kiểu y nóng bằng bắt buộc phải có một
[00:40:36] trò này mới nhận nhé bởi vì đấy cậu sẽ
[00:40:38] lách salad mã love
[00:40:43] for selected Ừ cái bảng đĩa thật này bản
[00:40:45] chất cái bảng này nó sẽ dựa theo cái
[00:40:46] bảng này để biết được nó có bao nhiêu
[00:40:49] cột và cột đấy còn gì nếu vào giờ sử đây
[00:40:52] là bạn bạn lớp đúng ạ thì cái bạn nên
[00:40:54] tật này nó sẽ có một mã và một tên của
[00:40:57] bạn lớp con bạn sinh viên thì sẽ có một
[00:41:01] mã tên và mã lớp Theo bạn sinh viên thôi
[00:41:05] đi sẽ update
[00:41:10] lớp xét số lượng sinh viên bằng số lượng
[00:41:12] sinh viên - một
[00:41:18] cộng một Đúng rồi - 1 - 1 Where mã bằng
[00:41:23] mã lớp cũ đúng ạ Cái tiếp theo mình lại
[00:41:26] copy cái này và thay Đây là bạn lớp mới
[00:41:28] đúng hoặc một lớp mới
[00:41:33] anh ở đây mình sẽ là forty sự thật thì
[00:41:35] đây sẽ là cộng 1
[00:41:38] khi bé dựa theo một lớp mới
[00:41:43] ông có thể select sao From A
[00:41:45] ừ ừ
[00:41:46] I
[00:41:48] love
[00:41:57] mã bằng mã lớp cũ
[00:42:01] anh ở đây mặt lớp mới thầy sửa ông ông
[00:42:04] xem lớp cũ trước ở lớp mới sau đó đi xem
[00:42:08] lại thằng mình vừa thằng mình vừa thay
[00:42:12] đổi nó là gì cũng được đổ mặt tùy
[00:42:16] tôi lại Bây giờ mình có thể lấy à sao
[00:42:24] hôm bia tức này và Sir Alex sao for
[00:42:26] instance chẳng hạn để các bạn biết được
[00:42:27] là
[00:42:30] A chạy
[00:42:34] ạ bây giờ xử tử cỡ Xem sinh viên trước
[00:42:36] nhé xem thử sinh viên này
[00:42:39] xem xem lại một lần lỡ choáng nhé bậm
[00:42:42] vào năm đây
[00:42:48] ở bảng này rõ lớp apple đang có hai bạn
[00:42:50] sinh viên không ạ Cái thằng Mạnh nó bằng
[00:42:52] 4 này Bây giờ mình sẽ đổi nó sang đất
[00:42:56] thứ hai không ạ thì sẽ là update sinh
[00:43:07] à à bằng hai đúng không ạ Where
[00:43:12] mã bằng 4 chạy này
[00:43:16] em có bạn sẽ ra như thế này lớp cũ này
[00:43:17] thay đổi số lượng sinh viên bị giảm đi
[00:43:22] đúng ạ đây sau đó thì lớp mới tăng lên
[00:43:24] đúng không ạ Đầu tiên thì bạn cũ bạn
[00:43:26] đang ở trong lớp đầu xong rồi bạn đổi
[00:43:29] sang lớp thứ hai có ông sẽ bảo là thế
[00:43:32] này giả sử là do sử là tự nhiên tôi
[00:43:35] update tên của bạn đấy thôi thằng ạ quay
[00:43:38] em ạ Không không up lên mà lớp thì nó có
[00:43:41] lỗi gì không nó ạ sử đề lắm Hai ạ Cái
[00:43:43] như này Thực ra nó không lỗi gì cả Chẳng
[00:43:45] lỗi gì cả bạn đấy vẫn sẽ ở nguyên lớp
[00:43:47] đấy đương nhiên là cái này nó hơi nhược
[00:43:51] điểm một tí nó phải nó nó cập nhật lại
[00:43:53] cái số lượng đấy ạ Các bạn nếu để ý kĩ
[00:43:55] gì nó vẫn chạy cái Cập nhật lại số lượng
[00:43:57] vẫn sẽ
[00:44:01] i - 1 sau đó đi đó lại cộng lại một cái
[00:44:03] câu lệnh update của các bạn khi mà các
[00:44:05] bạn học về cái chiếc nơ này rồi các bạn
[00:44:08] sẽ hiểu bản chất cái update nó luôn là
[00:44:10] delete đi rồi nó yên xuất lại chứ nó
[00:44:13] không có sửa Cột nào đó bất kỳ đâu ạ
[00:44:16] cháu rồi các bạn rõ ràng đi Ở đây rõ
[00:44:17] ràng tôi sửa mỗi cột tên thôi đúng ạ
[00:44:20] nhưng mà không nó vẫn Xoay xóa toàn bộ
[00:44:24] đi rồi nó in xuất bạn thế nên là ở đây
[00:44:27] vẫn đang làm theo lưu dịch nó vẫn sẽ
[00:44:30] chạy đâu mà chỉ cơ nó vẫn sẽ được cái
[00:44:32] hoạt đúng ra sự đã đổi tên của bạn đấy
[00:44:39] Ê mấy ông đấy lại có tại chưa
[00:44:50] cha mẹ ông chắn hết thoáng chưa để tôi
[00:44:51] gián tiếp
[00:44:54] Ừ cái vẫn là dễ đấy ngày xưa khó đâu
[00:44:58] vì
[00:45:02] số lượng sinh viên lại giảm đi cái mền
[00:45:03] cái khó giả
[00:45:06] em vẫn chưa đúng không Ok ông kia bạn
[00:45:09] chưa thì chứng tỏ là chơi tiếp thôi bây
[00:45:14] giờ Xanh bài toán khó hơn ông kia vậy
[00:45:17] nói là việc là Insert nhiều sinh viên
[00:45:20] của một lúc đúng ạ Tại sao tự nhiên phải
[00:45:24] đề cập cụ đấy Ở đây bởi vì ra sự là đây
[00:45:29] là sự tô Insert Long hacker này và Tuấn
[00:45:37] chú chạy này nó sẽ bảo lỗi các bạn thấy
[00:45:40] báo lỗi ở đây nó liên quan các bạn sẽ
[00:45:42] không hiểu cái này lắm Cái này nó bảo
[00:45:46] trả về một à nhiều hơn một chị cái đoạn
[00:45:48] lỗi này nó đương nhiên là liên quan đến
[00:45:50] chi cơ mình vừa tạo Nó chỉ cơ Insert
[00:45:53] sinh viên rồi thêm sinh viên này và nó
[00:45:56] lỗi chính là lỗi tại cái câu này chỉ các
[00:45:59] bạn sẽ thấy ở đây ạ
[00:46:02] Ừ Cái lỗi này
[00:46:05] ở Hà Đông một phần ạ Để đợt Đợi tí như
[00:46:07] cậu in sơ của tôi phần vừa rồi sai vậy
[00:46:09] Phải mà lớp ở đây đã mặt đất không được
[00:46:12] địa chấm Xin lỗi nhé bạn lớp đây đều là
[00:46:15] một đi và sự đều cho bạn đấy vào lớp và
[00:46:19] một đi chạy này nó vẫn lộn cứ nhiên là
[00:46:22] vẫn lỗi thôi Bởi vì À đây giả sử đang
[00:46:24] còn cho cùng bằng lớp nó ngoác tí còn
[00:46:26] tôi còn cho vào cùng và hai lớp nó còn
[00:46:28] khó nữa cơ cùng và một lớp trước nha
[00:46:30] mình định nhé cùng nhằm Bảo Lâm chưa
[00:46:32] nghe thì
[00:46:34] sau khi mà các bạn nghĩ rất nhiều sinh
[00:46:37] viên cùng nhóm lớp như này thì nếu mà sẽ
[00:46:41] AK sao bạn lớp borey rất thật như này có
[00:46:44] bạn sẽ thấy à Nó trả về nó trả về hay
[00:46:47] hai dòng chứ không phải một dòng đây
[00:46:49] mình sẽ cho bạn xem
[00:46:52] ạ Bây giờ mình đưa nha Bây giờ mình sẽ
[00:46:54] sửa cái này đúng không ạ Mình sẽ hết cái
[00:46:55] này
[00:46:58] anh xóa tôi xóa hết cả các bạn này đi
[00:47:01] nhé thực sự Cái đoạn này không chạy nữa
[00:47:03] rồi xóa đi Này xóa luôn cả này đi này
[00:47:07] tôi sẽ Shake for instant kể cho Bống xem
[00:47:11] nhé Nếu chỉ cần xem lại thôi đợi chạy
[00:47:13] chạy lại này
[00:47:17] a Battle in short này trẻ này
[00:47:20] khi đôi nha bây giờ mấy ông thấy à ý sắp
[00:47:22] thành công rồi
[00:47:25] cài á
[00:47:28] chữ cái bảng cái bảng cái lớp này chưa
[00:47:29] được cập nhật số lượng đó làm tạm bỏ qua
[00:47:31] tạm bỏ qua điều này đi
[00:47:34] Ê mấy ông thấy rõ ràng là cái việc khi
[00:47:37] mà yên sơ vào thì các bạn insisted đây
[00:47:40] là bản in xuất tuần này tôi đang thổi
[00:47:42] cho tôi xóa luôn cả vụ snack hai cái bạn
[00:47:46] kia đi cho bé ông dễ nhìn đây chỉ có mỗi
[00:47:50] xe lách bả đi sự thật đây nhá này
[00:47:53] Ừ nếu thấy rõ ràng và
[00:47:55] sau khi mà yên shop nhiều bản ghi ở cùng
[00:47:57] một lúc đúng ạ thì các bạn sức tận này
[00:48:00] nó trả về cái cột mà lớp mà trả về tận
[00:48:02] nhiều giá trị thế nên làm nếu không khai
[00:48:06] báo đây kiểu mã lớp kiểu in kiểu là lão
[00:48:08] chỉ chứa một giá trị và một số duy nhất
[00:48:10] thôi đúng không thế này chả phải tận hai
[00:48:13] số rồi bây giờ cả hai số đều số 1 nhưng
[00:48:15] mà nó vẫn là hai số thành ăn nó báo lỗi
[00:48:18] đúng ạ thì bây giờ thực tế và đây là
[00:48:20] mình không cần khai báo về không Không
[00:48:24] cần phải khai báo cái biến làm gì nữa
[00:48:27] không cần biến mã lớp là gì nữa mình cần
[00:48:28] ở đây là gì
[00:48:31] anh giống như bạn kia đang nói cũng rất
[00:48:33] đúng đó là mình phải đến đúng không ạ
[00:48:37] Mình sẽ đến sen lớp nào có bao nhiêu
[00:48:39] lượng sinh viên nó nó nó là như kiểu
[00:48:43] ngay Giả sử tôi đến tôi để mua nhé tạm
[00:48:45] bỏ qua cột mã vừa quần mà không quan
[00:48:48] trọng mình ra sự là bây giờ tôi có như
[00:48:49] này
[00:48:50] thế này
[00:48:54] Ừ thì các bạn giả sử tôi nshop không
[00:48:55] không quan trọng mấy cục này Này nhá
[00:48:56] Đúng không mấy cốc này được không có
[00:48:59] nghĩa gì cả đúng ạ Bây giờ tôi là số lỗi
[00:49:01] Insert như thế này khi mấy ông có thể
[00:49:06] biết được ngay ok là lớp lớp có mã bằng
[00:49:10] 10 ạ thì mình sẽ thêm bao nhiêu bao
[00:49:14] nhiêu sinh viên ạ ạ và lớp thứ 2 thì
[00:49:15] thêm bao nhiêu sinh viên ạ đúng không ạ
[00:49:18] đã sửa tôi một công ty Shop ở tôi rất là
[00:49:21] này cái thì béo phải đếm hoạn Nếu sẽ đến
[00:49:24] dựa theo cái gì không ạ Nếu không đến sẽ
[00:49:27] là dùng hàm cao là đúng ạ cao đến màn
[00:49:30] không ạ rồi ông đến dựa theo cái gì ông
[00:49:33] đến dự anh em á lớp đúng ạ nghĩa là cao
[00:49:36] như này thì mình sẽ đến được à Ok đây có
[00:49:39] 3 bạn sinh viên sẽ vào lớp 12 bạn sinh
[00:49:42] viên sẽ vào lớp 2 chuẩn đi ạ
[00:49:50] Alo ạ
[00:49:52] thì các bạn sẽ đến đúng ạ và các bạn sẽ
[00:49:56] dbow theo cái mã lớp dùng hàm cao này
[00:49:58] bài thằng bạn lớp này sau đó thì
[00:50:01] cái bản thân cái kosala đấy nó sẽ sinh
[00:50:04] ra gần như sinh ra được một cái bạn đúng
[00:50:07] không ạ đây nó sẽ như thế này để tôi tôi
[00:50:10] copy hẳn trên này xuống trông dễ nhìn
[00:50:12] nhé ạ
[00:50:19] đây mình sẽ là cao này
[00:50:24] sao cũng được giúp bye bạn lớp này chuẩn
[00:50:27] chưa Có vừa chạy cho công xem nhé
[00:50:29] Anh Bum
[00:50:32] ở đâu ạ
[00:50:36] Sao mở lớp đúng mà
[00:50:45] à Anh nhầm rồi bye xin lỗi à
[00:50:51] em chạy lại mà
[00:50:55] ở đó nhưng nếu không thấy thấy mày Ông
[00:50:57] thấy là tiểu nó ra đúng không ạ bây giờ
[00:51:00] xử mình lấy thêm cuộn mã lớp nữa cho nó
[00:51:02] cho nó chuẩn này
[00:51:05] bây giờ sự đàn mình thêm một bạn nữa là
[00:51:07] bạn Linh hacker này
[00:51:10] ở lớp thứ hai cả em ạ
[00:51:13] ở đó thì mới ông sẽ thấy là
[00:51:17] ok ở đây sẽ là
[00:51:20] một lớp ra rồi số lượng sinh viên ra rồi
[00:51:22] đúng không ạ Bây giờ mình cần làm là gì
[00:51:26] thì sẽ cần cập nhật lại từng lớp treo
[00:51:31] cái cái mã lớp tương ứng đúng ạ và số
[00:51:33] lượng mày sẽ là cộng và cái số lượng cũ
[00:51:38] của cải lớp lớp đấy Đúng là được cái hợp
[00:51:40] lý đúng không Thì mình sẽ dùng do thôi
[00:51:42] đúng không ạ Mình sẽ cho cái này bản
[00:51:45] chất cả cái này nó tính là một bảng xong
[00:51:48] mình sẽ roi vào thằng kia thì đoạn này
[00:51:50] với Bắt đầu thấy não này cái đoạn này
[00:51:52] mình sẽ kết hợp khá nhiều cái vợ các bạn
[00:51:55] sẽ thấy nó hơi bị hay nào vì tớ tia các
[00:51:57] bạn cần update đúng không ạ Các bạn thân
[00:51:59] đã bếp bảng gì bằng lớp đúng không ạ Ok
[00:52:03] update tạm lớp này đúng ạ
[00:52:07] Ừ nhưng mà mạng lớp này nó không nó phải
[00:52:09] do I với cái này dựa theo cái gì rồi
[00:52:11] theo quần mã lớp này đúng không ạ
[00:52:15] thì mình sẽ là tên của Cao sao này là số
[00:52:18] lượng sinh viên mới nhá
[00:52:24] khái niệm như thế này
[00:52:28] mình sẽ roi cái thang này
[00:52:32] rồi Cả cái thằng to này thằng to mày
[00:52:35] mình sẽ tên là ác mình sẽ đặt tên cho nó
[00:52:37] là tê ạ
[00:52:43] Anh hỏi em đi thay Insert đi đó
[00:52:47] xe khách để mà cái khái niệm update your
[00:52:50] ý thì để mình không ngờ lắm đâu Anh sẽ
[00:52:51] tra
[00:53:08] v-app cho server
[00:53:11] cài đặt các bạn sẽ thấy vẫn sẽ có xét
[00:53:13] như bình thường và form như bình thường
[00:53:16] và cho như bình thường như thế này không
[00:53:20] ạ chia đây nó sẽ là hết date lớp này xét
[00:53:23] số lượng sinh viên này bằng số lượng
[00:53:26] sinh viên cũ này cộng với số lượng sinh
[00:53:28] viên mới
[00:53:29] nhà
[00:53:35] tư bản y như thế này sau đó mình sẽ có
[00:53:39] form lớp rồi với cả cụm này
[00:53:45] on love chấm mã bằng y chấm mã lớp
[00:53:48] ở đây để đoạn này thì bài nào rồi nè nó
[00:53:49] sẽ đầy đủ như thế này
[00:53:53] Ừ nhưng mà để để cho các bạn đã thấy nó
[00:53:55] phức tạp như thế này mình cứ làm cho các
[00:53:58] bạn đơn giản trước đi mình thay vì chạy
[00:54:01] câu update này vụ những ngày cho các bạn
[00:54:02] đỡ cho ám mình sẽ lấy trước bây giờ các
[00:54:06] bạn xem đã nhé Mình xin lỗi tự nhiên cho
[00:54:09] bạn những ko update nhẹ Thoáng Qua
[00:54:12] ơi mình tạm vứt nó rằng cái file nhá
[00:54:14] thì mình sẽ à
[00:54:18] a snack sharefrom lớp này
[00:54:22] rồi à
[00:54:25] 10 cái đoạn này công nhận xóa thật đoạn
[00:54:27] này nó nâng cao mà tôi bảo đoạn này nâng
[00:54:29] cao giống Nếu về ông thực sự mà không
[00:54:32] một ngay nâng cao thì mấy ông phải có
[00:54:34] thể dừng đưa cô được thì toàn bộ đấy
[00:54:36] trên là đủ kiến nước của các bạn cơ bản
[00:54:39] về cơ
[00:54:43] chế cơ bản after lỗi con đến đoạn này nó
[00:54:46] phải nâng cao để mà áp dụng cho việc in
[00:54:48] xuất nhiều ai Dielac nhiều update nhiều
[00:54:52] thì bắt buộc phải làm cái kiểu như này
[00:54:56] ở đây là bạn thân là các bạn cần Đây
[00:54:58] mình sẽ Copy lại câu truy vấn vừa rồi
[00:54:59] đúng ạ
[00:55:06] em ăn gì nè và mình đã tên nó lại ra à
[00:55:09] đúng ạ đi sẽ on
[00:55:14] lớp trầm mã bằng y chậm mà lớp
[00:55:16] Em nói như này à
[00:55:18] ừ ừ
[00:55:23] để mình thử xuất lại chọn sẽ nhá đó
[00:55:26] đây thì các bạn sẽ thấy da bảng lớp đây
[00:55:29] đúng số lượng sinh viên cũ đấy bảng Đây
[00:55:34] là cái thứ sẽ tốt đấy không ạ
[00:55:36] Bạn này khi mà Selection này Các bạn
[00:55:38] nhìn thấy biết được luôn mà đúng ạ Các
[00:55:40] bạn sẽ thấy nó không hẳn là khó hiểu lắm
[00:55:42] đâu chẳng qua là cái câu lệnh này mới
[00:55:47] cái cái cái câu lệnh này thì mình khẳng
[00:55:49] định nó mới thì nó các bạn cái có tại
[00:55:51] đúng không sao phải chuyện này chuyện
[00:55:53] bình thường như là cái đoạn này các bạn
[00:55:56] có thể thì dung được là select này các
[00:55:58] bạn vừa gió hiểu đúng ạ sẽ lách này vừa
[00:56:02] rồi các bạn hiểu các bạn cho lại cho lại
[00:56:04] này các bạn vẫn hiểu mà đúng ạ thì nó
[00:56:05] xảy ra được thông tin như này thôi đúng
[00:56:07] ạ Thì bây giờ mình cần là gì mình cần
[00:56:09] cập nhật cái số lượng này cộng với cái
[00:56:12] số lượng này là xong đúng ạ
[00:56:16] ngoạn thì bây giờ nó sẽ ra nó sẽ là câu
[00:56:18] ấp đất này thôi thì sẽ update
[00:56:21] ở mình kia mình do như này mình phải
[00:56:23] khai báo ra mình sẽ biết cái bảng gì đó
[00:56:26] ngọn gái có 2 bàn là bảo lớp rồi bằng y
[00:56:28] là bạn ý sức thật Mình không cần bởi cập
[00:56:30] nhật bản in sắc thật của bọn mình cần
[00:56:32] nhận bạn lớp thôi và mình cần cập nhật
[00:56:35] cái cột số lượng sinh viên của bạn lớp
[00:56:38] bằng số lượng sinh viên cũ đúng ạ cộng
[00:56:40] với số lượng sinh viên mới từ cái bảng y
[00:56:44] ông ạ xong rồi dựa trên cái câu C của
[00:56:47] mình vừa select là được cái thuê chạy
[00:56:55] Em à mình cứ sẽ Rex said for love và
[00:56:56] selects
[00:56:59] sao form sinh viên để các bạn dễ hình
[00:57:02] dung nhé Giả sử là bây giờ mình cứ
[00:57:05] anh ấy thực ra mình khó chịu ở cái vụ
[00:57:08] này Đợi mình tí mình khó chịu cái vụ đó
[00:57:11] mã lớp đang tự động tăng này
[00:57:13] ạ Bây giờ mình đi xuất lại Bây giờ mình
[00:57:16] đang muốn delete toàn bộ lớp cũ đi để mà
[00:57:18] bởi số lượng sinh viên Nãy giờ đang bị
[00:57:20] quá tải nữa rồi Các bạn để ý kĩ là sinh
[00:57:22] viên Nãy giờ nó cứ tăng như thế này Mà
[00:57:24] mà trong cái đó Nãy giờ mình để
[00:57:27] số lượng như này thành sai đúng không ạ
[00:57:29] Bây giờ mình cần nắp lại đi
[00:57:33] thôi áp đấy được gặp đấy lớp
[00:57:37] xét số lượng sinh viên bằng không này
[00:57:40] sau đó thì bị lép for love và phòng sinh
[00:57:42] viên thế này nhanh nhỉ
[00:57:45] I have bây giờ đi lễ rồi Có khi nó bị -
[00:57:48] Đúng rồi Delete nó bị - dealer trước này
[00:57:55] em bán Delete nó lỗi nó rồi vì cái câu
[00:57:58] chi cơ kia đúng ạ Thế ăn tôm đấy thế nên
[00:58:01] mình mới đang bảo là thì cứ tạm mà
[00:58:05] lốp hẳn hai bạn hãy đi mình dốt và sinh
[00:58:10] mí rớt lại từ đầu đi coi như mình làm
[00:58:12] lại từ đầu nhé
[00:58:22] cách tạo loại này
[00:58:25] anh nhìn xa lạ này để tại sao mình ở mắt
[00:58:28] tôi rất lại này bởi vì cho một mã mã lớp
[00:58:29] bằng mồ thôi mà lớp bằng một bằng hai
[00:58:30] cho dễ
[00:58:33] Ừ ok đang có bạn lớp ở sinh viên này
[00:58:36] đang trống trơn chứ có gì không ạ
[00:58:40] thế này Ừ ok rồi đó ạ Bây giờ mình sẽ
[00:58:42] tạo một cái chích cơ thêm sinh viên này
[00:58:44] đúng ạ
[00:58:47] ở đó bơ mình di sót lại này
[00:58:48] ở
[00:58:51] các loại ngon không ạ
[00:58:54] Ừ thế xong rồi đấy Đó là các bạn đã hiểu
[00:58:57] đã biết qua được cái việc làm khi sắt
[00:59:01] nhiều sinh viên cùng 1 lúc thì nó sẽ cập
[00:59:05] nhật cho tương ứng với bao nhiêu lớp đấy
[00:59:08] ngoại mình sẽ cập nhật lại số lượng đúng
[00:59:12] ạ thi cái này cái này thì ra là nó lại
[00:59:14] dễ ở điểm là khi các bạn hãy hiểu cái
[00:59:15] này
[00:59:17] Ừ thì các bạn có làm việc phải đi lấy
[00:59:19] không ạ Có nhiên đi lấy thì nó sẽ rồi đó
[00:59:21] ạ
[00:59:24] chứ không phải tạo ra một bảng y mà cái
[00:59:26] câu c nách 7 Nó gần như là nó đã biến
[00:59:28] thành một cái bảng rồi không không gọi
[00:59:30] dùng từ tạo bạn nữa bị nó không hẳn là
[00:59:33] đúng nếu cậu bạn đấy nó không tồn tại
[00:59:35] tồn tại lâu ấy
[00:59:43] Ừ đúng rồi cái câu select cái câu select
[00:59:48] này nó sẽ nó sẽ tạo Nó sẽ gần như là
[00:59:51] biến nó thành một cái bạn vì gì đó để
[00:59:54] các bạn dùng át vệ mã kiểu dáng tên cho
[00:59:56] cả cái bàn đấy Sau đó thì các bạn cho
[00:59:57] hoa dựa trên mạng đấy thì ra cái đoạn
[00:59:59] này nếu mà không dám như này thì các bạn
[01:00:02] sẽ được viết đầy đủ như này thôi không
[01:00:04] sai như này vẫn được không thì sai cả
[01:00:08] Nhưng mà thực là thế không tốt mà mình
[01:00:09] thường ai mình làm cái kiểu dán như này
[01:00:16] Ừ
[01:00:19] Ok để nói chung là bây giờ làm để đi lấy
[01:00:21] thì cho các bạn cũng sẽ thấy nó dễ thôi
[01:00:23] mình chụp nhé
[01:00:25] à à
[01:00:29] anh after Delete này vì vậy sẽ là xóa
[01:00:32] sinh viên không ạ thì bây giờ thì các
[01:00:35] bạn thấy là nó giờ dễ bạn trẻ đi Lexus
[01:00:40] đây là D đây là D bây giờ d mà thereto
[01:00:52] Bây giờ là elite four sinh viên Xóa hết
[01:00:55] toàn bộ sinh viên luôn à
[01:00:58] Ừ ok
[01:01:03] anh
[01:01:06] em mình đi sắp một đống cùng lúc nè
[01:01:08] em rất nhiều
[01:01:12] em lên lên lên lên này đổi hết cái này
[01:01:16] hay đi cho mấy ông lại bảo tôi bị bịp
[01:01:20] lên Lên này lên này đúng không ạ Cái
[01:01:23] mười vẫn giữ nguyên Không ạ Không ạ sợ
[01:01:25] Bây giờ thay vì Delete from sinh viên
[01:01:28] như thế này nếu lại bảo là ok Cái này
[01:01:31] mấy ông vẫn về nghĩ tôi bịp đây tôi thử
[01:01:36] Xóa mỗi từ 10 que mã Lớn hơn mười đi ông
[01:01:37] ạ Delete này
[01:01:41] đó số lượng nó không bị hoàn toàn sửa Ok
[01:01:44] chị ạ thì mấy ông thấy tôi còn đi vào
[01:01:49] đấy Cái câu truy vấn cái cơ bản và lại
[01:01:51] các bạn học đúng không ạ Nó chỉ áp dụng
[01:01:54] cho việc in sơ hoặc Delete
[01:02:03] Ừ ông kia nãy giờ cứ để cập về robot
[01:02:05] robot và về trên sân mà đúng ạ
[01:02:10] thì buổi sau dậy nha đấy Đúng kiểu hôm
[01:02:13] nay chỉ học chữ cơ thể học đúng rồi bạn
[01:02:15] ạ bây giờ đến cái phức tạp hơn một tí ở
[01:02:17] đó là
[01:02:20] cơ xăng update update thì như thế nào
[01:02:23] đúng
[01:02:26] em tắt thì bạn chất là các bạn sẽ ôm cả
[01:02:29] Insert và Delete này thì sẽ tạo được
[01:02:32] update thôi đúng không Nói là như thế
[01:02:35] thôi nhưng mình từng nói gì ạ update và
[01:02:37] bản chất là nó kết hợp yz + Delete mà nó
[01:02:39] không ạ thì các bạn cũng sẽ làm chị cơ
[01:02:42] như thế đúng không còn sẽ là chị thơ cả
[01:02:52] 300 nãy giờ làm trên nhiều bạn đi mà
[01:02:54] đang nói là một cái vụ cơ bản vừa nãy
[01:02:56] các bạn học đấy thì áp dụng trị đúng rồi
[01:03:05] à Tôi đang nói vụ là nãy giờ là học xong
[01:03:07] đúng mượn chiếc cờ after
[01:03:12] còn chị girl instead of cơ ạ instead of
[01:03:16] nó mới là cái Khoai buổi sau học buổi
[01:03:19] sau hôm nay chính ở Xương vì sau mình sẽ
[01:03:23] dạy các bạn với ý sơ lược và kết hợp cả
[01:03:25] trên sân nữa thì ra bữa hôm nay các bạn
[01:03:28] mà về làm bài tập lại cái làm đúng mỗi
[01:03:32] dài lại bài hôm nay thôi đâu ạ để mà các
[01:03:35] bạn nhớ các bạn hình dung hiểu thì buổi
[01:03:38] sau các bạn cũng sẽ quen dần và gái kiểu
[01:03:40] cho dụng các thứ với bạn ý rất thực và
[01:03:44] đĩa cực các bạn làm cái in sẽ được rất
[01:03:47] là 2a à à
[01:03:49] xe tải kiến thức hôm nay Chị được thế
[01:04:02] chị xem hôm nay còn chia sẻ thì nghĩ anh
[01:04:10] Ừ ok
[01:04:13] Thực ra cũng chẳng còn gì chia sẻ đâu
[01:04:15] rồi ông ạ Tôi định chia sẻ này nhưng mà
[01:04:18] tôi định chia sẻ ở bên cái
[01:04:22] khóa học web cơ Thế nên chắc là thôi Hôm
[01:04:24] nay thấy hơi quá tải rồi
[01:04:27] nên chắc là bạn cho mấy ông ngừng để mà
[01:04:30] Thì khi làm bài tập nữa
[01:04:32] Ừ nếu không Đừng có nước đến chân mới
[01:04:35] nhảy nhé đến Không phải ạ Có ông vừa nãy
[01:04:37] nửa nửa tiếng 1 tiếng trước mới ngồi làm
[01:04:40] bài tập của tôi sẽ sẵn hôm sau không làm
[01:04:42] được gì đâu
[01:04:45] à à chia sẻ cách đoán con gái thích ăn
[01:04:48] gì không ạ Không có phải mỗi hình Nếu là
[01:04:51] Đoàn Thích ăn gì thì ra nó khá là dễ cứ
[01:04:54] toàn tôi tôi thấy thằng có vai bạn chưa
[01:04:57] trải rồi đó là thiếu kiểu là Ừ thì cứ
[01:05:00] thực đố lại con gái là đâu Em biết
[01:05:04] anh sắp dẫn em đi ăn món gì Thôi bạn con
[01:05:07] cá trả lời trả lời cái gì thì mình cho
[01:05:12] đi ăn cái đấy xong nhưng mà còn việc để
[01:05:13] mặt đoán xem thực sự còn lại đang nghĩ
[01:05:16] gì hay con gái thật sự thật
[01:05:19] em đang muốn gì thì ra đó là khó của đôi
[01:05:22] khi con gái nó đang biết mình muốn gì cả
[01:05:26] Thế nên là cái tốt nhất ở đây đó là ông
[01:05:28] phải luôn cầm cương ông vậy luôn
[01:05:32] đoán trước được là em hãy sẽ nghĩ gì nếu
[01:05:34] mà ông làm được thuế thì ông đúng kiểu
[01:05:36] nhà tiên tri còn nếu mà ông làm theo
[01:05:40] kiểu khó hơn à Dễ nhầm dễ hơn không đoán
[01:05:42] được nó sẽ nghĩ gì thì mình chơi cho cắt
[01:05:47] đó là nghị ghét nó ăn cái thứ mình muốn
[01:05:50] anh đưa như là nói thế hơi quá Nhưng mà
[01:05:52] thực là con gái về cơ bản thì tôi thấy
[01:05:55] con gái dễ mà Chứ anh ấy mà đấy với điều
[01:05:57] kiện nhé
[01:05:59] em cầm cương cầm vôlăng nữa thức các
[01:06:02] kiểu tự mình điều khiển kể cái mối quan
[01:06:05] hệ đấy ấy đối với tôi con trai vẫn nên
[01:06:09] là chủ động thì
[01:06:10] ừ ừ
[01:06:14] ý thì cái việc
[01:06:17] Ừ để mà ông cầm Cương được như thế thì
[01:06:19] chắc chắn là ông phải
[01:06:24] A phẩy có cái khẩu vị hợp mạng đấy hoặc
[01:06:25] là khẩu vị
[01:06:28] chị đại trà giống thiệu của tôi Tại sao
[01:06:32] cậu lại Tôi ăn rất nhiều cái thứ kiểu
[01:06:35] người phát âm được Kiểu thế thành ra là
[01:06:38] tôi Mà dẫn đi ăn thì chị ăn ngon nữa cả
[01:06:42] kiểu dễ ăn hàng ra là các bạn đấy toàn
[01:06:45] để tôi hiểu dạng hoàn toàn thích tôi
[01:06:48] chọn món cá Anh Tuấn thế tốt Tuân trợ
[01:06:50] toàn gái người đi ăn những ngày quá mà
[01:06:53] anh ấy cậu chỉ ăn ở đấy thôi cứ thế
[01:06:56] thành thành ra là mấy ông phải thay đổi
[01:07:00] một là học cách đoán thử xem nó sẽ nghĩ
[01:07:02] gì hay là
[01:07:05] thì mình phải có cái Goo nào đó xong ấy
[01:07:08] cư cứ bắt mấy bạn này ăn
[01:07:11] không phải là ăn mấy thứ mấy Bạn ấy ghét
[01:07:14] hay mới món bạn dị ứng là được không ạ
[01:07:17] Ừ nhưng mà đương nhiên hội Huế Hồi đấy
[01:07:20] tôi Thỉnh thoảng tôi cũng chán biết ăn
[01:07:23] gì kiểu hôm trước ăn xương món đấy rồi
[01:07:25] thì mới ông cũng phải lên cái danh sách
[01:07:29] xô ngồi lại giống như tôi tôi làm tôn để
[01:07:34] mà ngẫu nhiên mấy cái món chủ định - 7
[01:07:38] món chưa đi đúng kéo ăn mấy món trong
[01:07:41] tuần này là ăn đúng không ạ Mấy ông
[01:07:44] Insert vào trong db2 lại đúng không yên
[01:07:48] sẽ ở đây b là hôm nay ăn món cơm hôm sau
[01:07:50] thì sẽ ở loại trừ đi trong vòng 7 ngày
[01:07:54] loại mấy cái món mà ăn xong 7 ngày xong
[01:07:57] rồi select random Prado những cái món
[01:08:00] còn lại chẳng đời ông ông sẽ có một bảng
[01:08:03] danh sách món ăn ngon và một bả bạn là
[01:08:05] hôm nay ăn gì à
[01:08:08] để mà ông lưu lại việc hôm nay ăn
[01:08:11] abc.xyz đúng không ạ sau đó thì ông chỉ
[01:08:12] việc là
[01:08:15] select loại bỏ trong cái bảng
[01:08:18] loại bỏ trong cái bào mà hôm hôm nay đã
[01:08:21] ăn món gì trong vòng 7 ngày thế là xong
[01:08:23] à à
[01:08:25] anh bao kết hợp với kiến thức đã học đi
[01:08:27] Mày không phải làm ra những cái đơn giản
[01:08:43] ờ ờ thì đấy tôi bảo rồi Chuẩn chuẩn Bởi
[01:08:44] vì tôi chả trải nghiệm nhiều rồi đấy
[01:08:46] đúng không ạ
[01:08:49] Ẩm Thực ra là nếu anh còn hỏi thêm kiến
[01:09:02] Ừ đúng rồi con gái hay con trai cầm
[01:09:03] cương thật ra không quan trọng quan
[01:09:06] trọng và đừng nghĩ ai ở bề trên của ai
[01:09:08] mà mà tí tôi là kiểu chắc chắn nó phải
[01:09:10] có một người chủ động
[01:09:12] hai người chủ động thì nó mới dễ to anh
[01:09:16] ấy người này cũng muốn ăn ở nhà hàng này
[01:09:19] người kia 15 cửa nhà hàng kia không nên
[01:09:21] như thế nên có một người chủ động nếu mà
[01:09:24] con gái mà chủ động thì tôi K Ông chẳng
[01:09:27] cần phải đến lượt hỏi nó ăn món gì nó sẽ
[01:09:29] tự làm hoặc nó sẽ tự mua cho ông còn nếu
[01:09:33] mà mua khi mà họ ông đã phải hỏi cô đấy
[01:09:35] Ông là người chủ động đúng không Bác là
[01:09:37] người chủ động thì ông không hẳn ở chủ
[01:09:40] động hỏi mà ông ông cựu Chủ động dẫn nó
[01:09:42] đi làm luôn chứ
[01:09:45] anh đúng không Đừng có hỏi ông đương
[01:09:47] nhiên là hỏi thử cái lọng tốt theo cơ ạ
[01:09:50] Ừ nghe có vẻ tấm mí đấy nhưng ngày nào
[01:09:52] cũng hỏi giống như kiểu thực sự thì ông
[01:09:54] ấy biến thành một thằng không tâm lý gì
[01:09:55] cả theo kiểu là chẳng biết được nó sẽ
[01:09:57] nghĩ gì nên vẻ hỏi
[01:09:59] anh nói thẳng là như thế
[01:10:03] chị thay vì như thế kiểu tôi tôi đi hẹn
[01:10:05] hò với mấy bạn mà cái tôi còn chưa quen
[01:10:08] bao giờ đóng học Buổi Hẹn Đầu Tiên ý Thì
[01:10:10] lúc ấy tôi làm gì có biết được bạn đấy
[01:10:12] thích ăn món gì đúng không ạ Chị hỏi là
[01:10:14] em dị ứng món gì Em biết món gì cho nó
[01:10:17] thì hướng dẫn đi ăn những cái món mình
[01:10:19] thích vào những cái quán mà mình cảm
[01:10:23] thấy à Nhiều người ăn được Thành ra Cuối
[01:10:26] cùng thì mấy bạn ấy mê tôi đường để mà
[01:10:29] tán gái nhanh cũng một phần là đường dạ
[01:10:32] dày đấy nhá Thế nên là mấy ông mấy ông
[01:10:35] ghi điểm một là dẫn được đến quán ngon
[01:10:38] hai em ấy tự nấu những cái món quán ngon
[01:10:40] và những quán mà kiểu ít người biết nữa
[01:10:42] thì càng tốt theo đúng kiểu là em đấy
[01:10:50] A Gọi nãy giờ chia sẻ mấy cái còn nhạy
[01:10:54] cảm quá không biết được vì sau tố cáo
[01:10:57] kênh ấy không em
[01:11:00] à à
[01:11:02] à Tại mấy bạn gái ở đây chả là xác nhận
[01:11:14] à à
[01:11:16] khi mình ăn mình chả không thuật toán
[01:11:18] rồi mình còn chưa có thuật toán mình
[01:11:20] mình nhắc đến toán được cái là bây giờ
[01:11:26] à à
[01:11:33] Ừ ok Nói chung là bây giờ hết câu hỏi
[01:11:35] của mấy ông phải không ạ Thì bây giờ
[01:11:38] mình xin phép nghỉ nhé Cũng mà không một
[01:11:40] tiếng thôi Tí tôi
[01:11:43] 3 bài tập thủy sản làm lại bài hôm nay
[01:11:46] thôi vừa hôm sau cũng sẽ đổ làm sao sẽ
[01:11:49] học về cái khó chắc là buổi sau nữa thì
[01:11:53] mới thành buổi cuối được sẽ học và zoom
[01:11:55] ừ ừ
[01:11:58] anh nói cho các bạn nhé
