# Đồ án Web chuyên sâu - Chữa (L11) - Review Code

- Video ID: `JnWCEk8TSng`
- URL: https://www.youtube.com/watch?v=JnWCEk8TSng
- Published: 2022-08-07
- Duration: 1h 27m 25s (5245s)
- Language: vi
- Subtitle source: auto
- Kind: live

## Transcript

[00:00:29] một bạn nữa
[00:00:32] Mình sẽ tranh thủ tâm sự một tí trong
[00:00:35] lúc trước khi bắt đầu nhé À đúng rồi hôm
[00:00:38] nay
[00:00:40] hôm nay chắc là dồn cả hôm trước sẽ có
[00:00:43] nhiều nhóm sẽ cần chữa Có gì cứ bình
[00:00:46] luận nhé
[00:00:55] bình luận nhé
[00:01:06] hôm trước Thực ra thì à hôm Thứ năm thì
[00:01:11] mình có bấc ở trên công ty mình có đăng
[00:01:15] bài thông báo rồi đấy ạ thì
[00:01:22] nhưng mà tôi thì tôi và một người sống
[00:01:26] ra Tính ra vẫn hơi bị ảnh hưởng bởi cảm
[00:01:30] xúc khá nhiều nếu thế và bao gồm trong
[00:01:33] cả việc là cảm xúc tôi cái tâm trạng của
[00:01:36] tôi nó sẽ ảnh hưởng cả công việc
[00:01:39] chắc tôi Tôi nghĩ là kiểu khi mình lớn
[00:01:42] lên ấy thì mình sẽ kiểu cân bằng được
[00:01:45] điều đấy hơn sẽ không để ảnh ảnh hưởng
[00:01:47] bởi cảm xúc nhiều nhưng mà nhưng mà về
[00:01:51] cơ bản thì tôi thường hay bị ảnh hưởng
[00:01:53] bởi cảm xúc thế nên là sẽ thậm chí có
[00:01:56] nhiều hôm mà sẽ có thể dạy khá là hay và
[00:01:59] cũng có nhiều hôm thì sẽ kiểu dạng kiểu
[00:02:02] không hẳn là tâm trạng tệ nhất Nói chung
[00:02:05] là kiểu tâm trạng có thể ví dụ đấy ngày
[00:02:08] hôm đấy Kiểu đám mệt mỏi gì đó thì sẽ
[00:02:11] dạy kiểu nó sẽ bị nhàm chán hay gì đó
[00:02:13] Kiểu cái cái cái cái tông giọng ấy nó sẽ
[00:02:17] không kiểu dạng là hào hứng nó sẽ hiểu
[00:02:21] kiểu cứ đều đều thì chính khiến cho đính
[00:02:24] chính cả sinh viên cũng sẽ nghe kiểu
[00:02:26] buồn ngủ hay vân vân tôi Tôi nghĩ là tôi
[00:02:30] bị ảnh hưởng bởi cái đấy
[00:02:32] Thực ra lớn rồi mình nên mình mình nên
[00:02:36] có ngoài việc là mình sẽ phải đối mặt
[00:02:40] được với cái việc kiểu thỉnh thoảng có
[00:02:43] sống mà thỉnh thoảng mình có rất nhiều
[00:02:45] vấn đề nhưng mình sẽ phải đối mặt được
[00:02:48] với nó bằng là phải gạt nó sang một bên
[00:02:50] để vẫn tiếp tục được công việc
[00:02:52] để không làm ảnh hưởng đến ai người khác
[00:02:56] nữa đấy thì theo xong rồi nó sẽ Khá
[00:02:58] trách nhiệm
[00:03:01] cái bậc hôm trước của tôi gà nó cũng
[00:03:04] đương nhiên là lỗi của chắc chắn đầu
[00:03:07] tiên vẫn là lỗi của mình mình phải thừa
[00:03:09] nhận điều đấy ra là kiểu đó là kiểu
[00:03:19] nói như nào
[00:03:22] tính tôi thực ra là kiểu Tuy là code và
[00:03:27] thường hay xem lại code review code của
[00:03:30] chính mình
[00:03:31] nhưng mà test về cái test thì tôi lại
[00:03:34] vẫn chưa test cẩn thận nó lắm thì tôi sẽ
[00:03:38] tôi sẽ chở học cụ thể hơn về mấy cái
[00:03:42] kiểu test unis để mà để mà kiểu nó sẽ tự
[00:03:47] động test tự động test tất cả trường hợp
[00:03:48] rồi Có gì tôi sẽ cho mấy ông xem mấy ông
[00:03:51] tham khảo nữa
[00:03:53] xem thực sự là kiểu để tự máy chạy tự
[00:03:57] động test là như nào bởi vì tôi thực ra
[00:03:59] hơi lười phụ học thêm về cái mấy cái tế
[00:04:02] tổng đấy
[00:04:11] tạm thời Thế
[00:04:14] hôm nay thì ở trước khi mà chữa cụ thể
[00:04:17] cho một nhóm nào đó nhóm mà cần chữa thì
[00:04:20] cứ bình luận nhé Thì mình sẽ xin phép
[00:04:22] chữa cho à
[00:04:30] nó có vài cái nó khá là dị để mà
[00:04:33] để mà test kiểu như thế anh làm ở ở cái
[00:04:38] trang thương mại điện tử thì anh làm
[00:04:40] tính năng tự động đẩy đơn sang cho các
[00:04:43] bên đối tác sắp layer thì
[00:04:51] một cái trường hợp đấy
[00:05:01] tôi sẽ bây giờ tôi sẽ thử tạo ra ta bây
[00:05:03] giờ chữa lần lượt cho mấy ông xem mấy
[00:05:05] ông hiểu nha cái Menu 2 Cấp này tức là
[00:05:08] sao nghĩa là
[00:05:09] giả sử là bây giờ tôi có
[00:05:17] Mình có database
[00:05:56] làm cái Menu 2 cấp đấy Tôi đang làm thậm
[00:06:00] chí menu nhiều cấp cũng được nó sẽ kiểu
[00:06:03] như sau
[00:06:14] database tên là test đi cho tôi sẽ viết
[00:06:16] Microsoft đúng không ạ
[00:06:18] Hay mình sẽ có cốt luôn
[00:06:21] về cái đấy nhé để xem nhé Tôi không có
[00:06:25] thư mục test ở đây
[00:06:30] mà
[00:06:31] thôi không nên À đúng rồi hay tôi Vứt
[00:06:35] hết mọi thứ trong học viện này đi sẽ
[00:06:37] code ở bên cái học viện này
[00:06:49] nhé
[00:07:02] sân trong này
[00:08:12] nhé nhưng mà tôi sẽ chỉ làm cho 2 cấp
[00:08:16] thôi Còn mấy ông muốn làm phức tạp hơn
[00:08:18] thì
[00:08:19] đấy là việc mấy ông mấy ông sẽ cầm mò
[00:08:22] cái đấy sau còn tôi hướng dẫn yêu cầu
[00:08:24] đơn giản đã cho dễ hiểu đã còn về để Q
[00:08:27] Thực ra công ty sẽ áp dụng cho nhiều
[00:08:29] cách khác nhau
[00:08:31] để Quỳ tất cả sao nghĩa là vòng lặp nó
[00:08:34] cứ gọi gọi gọi gọi đến khi nào hết không
[00:08:37] phải vô tận mà chỉ đơn giản là thỉnh
[00:08:39] thoảng nó sẽ vô tận Nhưng thỉnh thoảng
[00:08:40] nó sẽ gọi cái hết thì thôi
[00:08:42] không nó không làm thủ công kiểu hot
[00:08:45] code đâu
[00:09:00] là amax này mua đồ này đúng không ạ Ở
[00:09:04] đây sẽ Giả sử cái vừa rồi nó thể loại đi
[00:09:07] mình sẽ cattery
[00:09:37] đúng không Mình mình sẽ cột là cột này
[00:09:41] nêm rất chuẩn và tiếp theo là
[00:09:45] sluck
[00:09:47] ra khá hay ở nhưng mà tôi cứ tạm bỏ qua
[00:09:52] đã Tôi muốn làm đơn giản trước mình sẽ
[00:09:54] có cái con chết này
[00:10:06] không nhớ được cái
[00:10:24] đương nhiên mình sẽ để luôn label
[00:10:43] để tôi thử vẽ kiểu shit cho mấy ông dễ
[00:10:46] hình dung nhá Sửa là mình sẽ có ID này
[00:10:49] đúng chứ và có mình sẽ gọi là Thoa rừng
[00:10:53] ID như này Tôi đặt này đi cho dễ hình
[00:10:57] dung hơn nhé
[00:11:08] là sao Nó là kiểu Giả sử là một này mình
[00:11:11] sẽ là laptop chẳng hạn
[00:11:20] muốn là kiểu dạng
[00:11:22] Asus chẳng hạn
[00:11:24] đi là một ngày thì mình sẽ hiểu à Nghĩa
[00:11:29] là là thằng này là thằng con của cái
[00:11:33] thằng này đúng không ạ tương tự thế sẽ
[00:11:35] có đều như này vẫn là thằng con thằng
[00:11:37] này nhưng Giả sử Giả sử tự nhiên mình sẽ
[00:11:40] có 4 là điện thoại chẳng hạn
[00:11:48] con thằng nào cả nó sẽ độc lập nó sẽ in
[00:11:50] ra menu của Độc Lập đúng không ạ Nó sẽ
[00:11:53] kiểu laptop này in ra điện thoại này
[00:11:55] đúng không sau khi trỏ vào cái laptop
[00:11:58] thì sẽ hiển thị Asus và đều chẳng hạn
[00:12:00] thế tương tự Thế mình sẽ có ví dụ ở đây
[00:12:03] Apple chẳng hạn Giả sử thế đâu nhé tôi
[00:12:05] vẫn Giả sử nhá Nó sẽ là 4 nhà chẳng hạn
[00:12:08] cho vào laptop thì Asus và đều đúng chứ
[00:12:11] còn chả trỏ và điện thoại sẽ hiển thị ra
[00:12:13] Apple đúng không Tôi vẫn đang chỉ làm
[00:12:16] theo kiểu menu 2 cấp thôi chứ không phải
[00:12:18] menu theo cậu là
[00:12:20] là trò với thằng Apple nó hiển thị ra
[00:12:23] thêm cái nữa Gì gì đó nữa thì cái đấy
[00:12:25] tôi chưa Hướng dẫn vội đúng không ạ sẽ
[00:12:29] không hướng dẫn đâu cái đấy mấy ông muốn
[00:12:31] hiểu về đệ quy mấy ông lại mò thêm
[00:12:35] những đại khái Thì bây giờ mình sẽ tạo
[00:12:37] cái bảng này trước đúng không ạ Mình sẽ
[00:12:39] tạo bảng này
[00:12:47] [âm nhạc]
[00:12:54] Bây giờ sửa là tôi tôi không làm tính
[00:12:57] năng
[00:13:03] bắt chước giống như bên Excel đi như này
[00:13:07] tiếp theo là Asus này
[00:13:10] sẽ có một laptop chuẩn luôn này giao nữa
[00:13:14] là đều
[00:13:16] mình sẽ có
[00:13:18] laptop đúng không tiếp theo là điện
[00:13:22] thoại này
[00:13:23] không có gì cả tiếp theo là Apple này sẽ
[00:13:28] có là điện thoại OK này đấy bây giờ bây
[00:13:33] giờ cái thứ mà đầu tiên là để mà Tôi
[00:13:35] hiển thị cái Menu đúng chứ
[00:13:37] nó sẽ là như thế này
[00:13:41] tôi sẽ
[00:13:42] vào bên controller
[00:13:46] này mình ghi hết vào trong này đúng
[00:13:49] không Ok
[00:13:50] mình sẽ có một cái test đi này
[00:14:15] đặt tên Đây là test menu đi
[00:14:21] menu.plus.vn
[00:14:27] cattery về đúng chứ
[00:14:38] nếu mà Trưởng Giả lấy tất cả như này rồi
[00:14:41] toàn bộ tất cả thì nó lại dễ quá đúng
[00:14:43] không dễ quá thử mấy ông nha
[00:14:54] rồi Ford
[00:15:13] qua thẻ a các thứ thì hiển thị ra như
[00:15:15] này thôi Sợ đóng Air forex như này đúng
[00:15:18] chứ đúng không Nếu mà làm theo kiểu như
[00:15:21] này và tôi sẽ
[00:15:23] chạy bên này
[00:15:26] sẽ có là ghét này test menu này
[00:15:31] nó sẽ nhảy đến test menu
[00:15:35] gì cả
[00:15:38] như này rồi mình sẽ có học viện trong
[00:15:41] test này gạch chéo test máy nu
[00:15:45] nó sẽ in ra như thế này đúng không ạ
[00:15:54] echo nhé
[00:16:03] để làm cũng được không sao cả
[00:16:06] nhưng mà đôi khi con em không nên xử lý
[00:16:08] mà vẫn xử lý là mình sẽ phải lồng Tự
[00:16:12] lồng hết mọi thứ ở trong bác em xong rồi
[00:16:15] Chỉ cần lên Hiển thị như anh đã từng nói
[00:16:20] là xử lý iPhone
[00:16:23] trừ những cái tính toán này hiện tại con
[00:16:25] số bác em nó sẽ trả về dữ liệu thô rồi
[00:16:28] còn em hiển thị con số nó khác
[00:16:31] để tính để tự động tính nó khác Còn đây
[00:16:35] là về cơ bản thì mình phải xác định rõ
[00:16:38] Thảo thằng con là thằng Trang ngay từ
[00:16:39] bác em rồi để mà xử lý đổ đổ về cho
[00:16:44] người dùng đổ về nó là api nghĩa là
[00:16:48] không phải là ở mỗi fan lens của em mà
[00:16:50] về sau giả sử bên thứ ba muốn gọi đến
[00:16:52] cho em để mà lấy Thông tin Dữ liệu về
[00:16:56] chẳng hạn thì em cần phải trả về cho nó
[00:16:59] những cái dữ liệu đã được xử lý một cách
[00:17:02] tương đối để nó nhìn vào nó hình dung nó
[00:17:05] hiểu hiểu không Nói chung là api có
[00:17:09] nhiều tác dụng lắm
[00:17:10] Nói chung đại Khái ở đây Nếu mấy ông
[00:17:13] nhìn thấy kiểu menu kiểu thô như này thì
[00:17:16] vứt đúng không ạ Rõ ràng là tôi đang
[00:17:18] muốn là ít nhất là thằng Laptop này sẽ
[00:17:20] có thằng con là Asus và Dell xong rồi
[00:17:22] thằng điện thoại sẽ Apple đúng không Thì
[00:17:24] bây giờ cái đầu tiên mình cần làm Đó là
[00:17:27] mình sẽ chỉ lấy chỉ lấy thằng trà để
[00:17:31] hiển thị ra thằng cha Thôi thì mình sẽ ở
[00:17:33] đây mình sẽ là bởi vì như này
[00:17:36] xong rồi mình sẽ
[00:17:43] này đi này
[00:17:51] chị Hiền
[00:17:53] lấy thằng con như thế nào thì bây giờ
[00:17:56] cái thằng lauriel có cái rất là hay đó
[00:17:59] là nó nó sẽ có khái niệm là
[00:18:03] sẽ lấy thằng con Và thậm chí là tôi nhớ
[00:18:05] không lầm là nó có lấy được cả thằng con
[00:18:07] thằng con con con con con con mãi nữa cơ
[00:18:09] nó là khái niệm mà gì nhỉ
[00:18:26] hồi trước tôi nhớ có một cái là kiểu nó
[00:18:28] định quy hộ mình cái vụ đấy
[00:18:30] Còn nếu không Mình làm đơn giản thôi nó
[00:18:33] sẽ chỉ hát Xoan thôi
[00:18:44] odhistourder như này hay phết nhỉ
[00:19:05] nhớ Có Hồi trước nó có nhắc cái vụ để
[00:19:08] quên một lần
[00:19:41] Custom này
[00:19:43] [âm nhạc]
[00:20:30] rồi
[00:21:15] sẽ là
[00:21:22] nhiều đúng không các từ
[00:21:32] đi
[00:21:34] là hiểu này mình sẽ gọi đến chính nó
[00:22:07] này được
[00:22:08] sao và
[00:22:11] tôi thử chạy thử cho mấy ông xem tại
[00:22:14] trang không có gì cả
[00:22:17] à đây tôi thử Return Chính thằng cattery
[00:22:20] này mấy ông sẽ xem nhé
[00:22:22] Đây mình thấy là thằng laptop nó đã có
[00:22:27] Asus và Dell Apple
[00:22:30] đúng chứ Thế giờ chỉ việc hiển thị ra
[00:22:32] thôi rất là dễ mấy ông thấy ở đây bên
[00:22:34] nào nếu mà dùng rasionship thì sẽ sẽ
[00:22:38] thấy là thằng này có hai thằng con ở đây
[00:22:40] rồi và thằng này có một thằng con thôi
[00:22:42] nó tự động nối hộ cho mình nên là việc
[00:22:44] in ra bên này sẽ rất là dễ bên này ông
[00:22:46] sẽ chỉ kiểm tra là
[00:22:54] à đâu
[00:23:07] xỉ thật nhìn Ông Sỹ thật
[00:23:22] thì mình sẽ
[00:23:29] đấy cho khác đi
[00:23:32] xong rồi mình sẽ Ford
[00:23:36] vẫn xịn thật đúng không in ra từng thằng
[00:23:39] như này
[00:23:41] và Kết quả nó sẽ như này Ok chứ
[00:23:52] kiểu 2 cấp còn như mà Vừa rồi tôi bảo là
[00:23:54] đây chỉ cần thêm cái đoạn này sẽ lấy
[00:23:57] menu kiểu dạng như cấp này cậu đa cấp là
[00:24:00] nó sẽ kiểu gọi gọi gọi liên tục để nó
[00:24:03] các thứ nó lằng nhằng hơn thì cái này em
[00:24:06] mấy ông tự mò thêm sau tôi lại cho mấy
[00:24:08] ông từ khóa này mấy ông mò rồi đúng
[00:24:10] không ạ
[00:24:20] như thế nhưng câu truy vấn của nó không
[00:24:23] phải là để quy nó là cái rất là hay Tôi
[00:24:25] thấy đó là không hề gọi điện Q kiểu này
[00:24:29] đúng không Nhưng câu truy vấn của nó
[00:24:31] không phải để quy thôi nhé Nó sẽ Tôi nhớ
[00:24:34] Chính xác là hình như nó tạo thành hai
[00:24:36] hay ba câu truy vấn thôi
[00:24:38] nghĩa là không phải là ý tôi tức là sao
[00:24:41] ví dụ Giả sử là ông ông lấy ví dụ lúc
[00:24:45] đầu mấy ông thầy nha là có câu truy vấn
[00:24:48] để lấy toàn bộ thằng cha đây Đúng chứ
[00:24:50] Đúng chứ Sau đó thì with thằng con nữa
[00:24:52] nhưng mà đây 2 cấp nghĩa là có hai câu
[00:24:55] truy vấn một câu thì lấy toàn bộ thằng
[00:24:57] cha và một câu Lấy toàn bộ thằng con của
[00:24:59] thằng cha này đúng chứ nhưng mà Nếu giả
[00:25:02] sử mà là đệ quy theo kiểu như cấp thì rõ
[00:25:04] ràng là vừa rồi có tôi đang làm 2 cấp
[00:25:07] thì hai câu truy vấn thế nên là giả sử
[00:25:10] menu 4 cấp hay là 5 cấp hay thậm chí về
[00:25:13] sau n cấp thì sẽ ở bấy nhiêu câu chỉ vấn
[00:25:15] không không phải như thế thằng cái đệq
[00:25:17] này tôi nhớ ông là nó chỉ hình như là
[00:25:19] tạo thành ba câu chưa vấn thôi Thì vẫn
[00:25:21] chỉ hai Tôi không chắc lắm nhưng mấy ông
[00:25:24] sẽ thử xem lại là hiểu ha Xem
[00:25:38] nhé
[00:25:49] thêm cả tính năng khác nữa
[00:25:58] cái bài toán tiếp theo toán đó là lấy ra
[00:26:01] danh sách trống tất cả các bạn đều đang
[00:26:03] làm bài toán đồ ăn hay là để làm đề tài
[00:26:07] nghiệp vụ nó sẽ có đến giờ thời gian có
[00:26:10] nhiều bạn vẫn đang thắc mắc tôi thế nào
[00:26:12] là nghiệp vụ thì nó thì với tôi
[00:26:15] thường nghiệp vụ thì nó sẽ có rất nhiều
[00:26:18] thứ Nó là kiểu dạng là là cái từ nghiệp
[00:26:22] vụ ấy theo như tôi hiểu nhé không phải
[00:26:24] nhà từ điển học cho lắm và tôi dốt văn
[00:26:27] nữa nhưng mà theo như tôi hiểu thì cái
[00:26:29] nghiệp vụ ở đây nó là hắn chỉ là là
[00:26:32] những cái liên quan đến cái nghiệp vụ
[00:26:35] khó ấy chứ không phải đương nhiên là làm
[00:26:37] công việc gì thì có nghiệp vụ riêng
[00:26:38] người ta người ta có quy trình làm việc
[00:26:40] người ta nhưng ý tôi nghiệp vụ cái đồ ăn
[00:26:43] 2 cần làm những cái nhiệm vụ khó Tức là
[00:26:45] sao và thứ nhất là bài toán về quản lý
[00:26:46] con người thứ hai là quản lý tiền bạc
[00:26:48] thứ ba là là quản lý lịch hiểu không
[00:26:52] Nghĩa là tại sao lại phải có những cái
[00:26:54] cái một cái gọi là khó bởi vì cái đầu
[00:26:58] vào của mấy ông nhập vào và cái đầu vặn
[00:27:01] đầu ra ấy nó có sự chênh lệch nó sự khác
[00:27:03] biệt hiểu không Tại sao đồ án 1 không
[00:27:06] thực tính ở bài toán nghiệp vụ bởi vì đồ
[00:27:08] án 1 về cơ bản nó chỉ ở trang web Một là
[00:27:10] tin tức là tất cả mình đang cái gì nó
[00:27:13] hiển thị đúng cái thứ mình vừa đăng thì
[00:27:15] nó không phải nghiệp vụ hiểu chứ nó
[00:27:17] không có gì khó ở đấy cả mình nhập vào
[00:27:19] như là mình nghĩ là đúng thế đúng không
[00:27:21] ạ tiếp theo đó là trang web bán hàng
[00:27:23] chẳng hạn bạn trang web bán hàng thực ra
[00:27:25] là cái nghiệp vụ của nó không hẳn là khó
[00:27:28] lắm Tức là sao về cơ bản thì khách hàng
[00:27:31] đặt hàng sau đó đã hiển thị cái đơn mà
[00:27:33] khách hàng đã đặt nó chẳng có gì khó cả
[00:27:35] admin vào xem đơn Khách hàng đã đã đạt
[00:27:39] cùng lắm là thêm một tí thống kê thôi
[00:27:41] nên là nó không tính là nghiệp vụ chuyên
[00:27:43] sâu lắm cái mức độ khó để mà giải quyết
[00:27:45] cái đấy Không hẳn là cao thế cái bài
[00:27:48] toán nghiệp vụ của cái đồ án 2 những cái
[00:27:51] nào là khó thì như tôi vừa nói thứ nhất
[00:27:53] là bài toán quản lý con người tức là sao
[00:27:54] nghĩa là con còn mình sẽ nhập vào giờ
[00:27:58] giấc các thứ để về sau xuất ra được cái
[00:28:00] lịch làm việc của từng người thậm chí là
[00:28:03] về sau nó sẽ tự động đề xuất là người
[00:28:06] này nghỉ thì người kia có rảnh hôm nay
[00:28:09] để ốp vào hay không chẳng hạn thế hoặc
[00:28:12] là tính công chấm công người dùng sẽ cứ
[00:28:15] nhập chấm công vào so với sau sự xuất ra
[00:28:17] thống kê là tỷ lệ là năng suất đi làm
[00:28:21] hay là gần như
[00:28:23] tính ra thì cái đấy nó chênh lệch rõ
[00:28:26] ràng là cái nguồn nhập vào với cái hiển
[00:28:29] thị ra nó khác rất khác nhau Máy tính sẽ
[00:28:33] phải tự động tính hộ cái đấy và con
[00:28:34] người tự tính cái đấy sẽ rất là mất thời
[00:28:36] gian kiểu gần như thế sẽ khó dùng đều
[00:28:40] bằng Excel hay word chứ đoán đoán một
[00:28:43] thứ K không cần trang web không cần
[00:28:46] trang web của mấy ông người ta dùng bằng
[00:28:48] Excel người ta lưu người ta lưu bằng
[00:28:50] giấy người ta vẫn làm được bởi vì nó
[00:28:52] không có bài toán gì đó cần phải xử lý
[00:28:55] bằng máy móc không cần tính toán còn đồ
[00:28:58] án 2 thì bắt buộc là những cái kiểu
[00:29:00] phải phải can thiệp sâu hơn ví dụ dạng
[00:29:03] như là như tôi bây giờ chuẩn bị chữa đó
[00:29:06] làm chi à là khách hàng cứ đặt lịch các
[00:29:09] thứ thôi nhưng mình vẫn phải đề xuất ra
[00:29:11] được là Ok thế thì thế thì Lịch Trống
[00:29:16] của ví dụ Giả sử Bây giờ tôi sắp đề cập
[00:29:18] là ví dụ là
[00:29:21] à vì ví dụ là như là
[00:29:25] bây giờ có đặt đặt lịch khám chẳng hạn
[00:29:28] đúng không có rất nhiều bác sĩ nhưng mà
[00:29:31] khung giờ làm việc à không không Giờ Tuy
[00:29:34] là giả sử khung giờ làm việc của bạn mấy
[00:29:36] bác sĩ cố định đi đúng không ạ Nhưng mà
[00:29:38] lúc mà khách đặt vào vào lúc giờ này thì
[00:29:42] kiểm tra lại danh sách là có bác có
[00:29:46] những bác sĩ nào đang rảnh giờ này đúng
[00:29:48] chứ Đấy khách hàng đặt giờ khác lại phải
[00:29:51] đề xuất ra danh sách bác sĩ rảnh đúng
[00:29:54] vào giờ đấy đúng không ạ kiểm tra trong
[00:29:56] cái lịch mà khách hàng đã đặt thì thay
[00:29:59] vì có một nhân viên để ngồi trực trực ở
[00:30:02] đấy để mà ngồi kiểm tra
[00:30:04] bây giờ có hàng trăm khách hàng vào rồi
[00:30:08] một nhân viên hỏi và nhân viên ngồi làm
[00:30:11] vỡ mồm đúng chứ Hãy để máy tính tự động
[00:30:13] làm được đấy khách máy tính tự đề xuất
[00:30:16] nhân viên thực à Làm sao cho mà thực tế
[00:30:20] thực tế là nhân viên chỉ cần người chốt
[00:30:23] cuối thôi hãy tiện nhất cho nhân viên
[00:30:26] không còn được tuyển nhiều nhân viên thì
[00:30:27] ngồi trực để mà kiểu kiểm tra xem là
[00:30:29] kiểm tra thủ công bằng tay
[00:30:32] không thậm chí là phải gọi lại bác sĩ
[00:30:36] đấy xác nhận không không phải làm như
[00:30:38] thế đúng chứ Hãy để máy tính kiểm tra
[00:30:40] hết mấy cái vụ đấy
[00:30:42] nghĩa là mình sẽ giảm được bài toán về
[00:30:44] con người đúng không ạ Đấy thì bây giờ
[00:30:47] tôi sẽ thử làm vụ đấy nhé Tôi sẽ làm cái
[00:30:50] cậu rất là đơn giản tôi sẽ
[00:30:52] triển lãm là tôi có tạo một
[00:30:57] tôi sẽ bao gồm làm cả hai tính năng này
[00:30:59] bao gồm lấy ra danh sách trống trước sau
[00:31:02] đó thì tôi đặt lịch sau đó thì tôi lại
[00:31:04] đặt thêm một lần nữa để kiểm tra xem là
[00:31:09] danh sách trống lúc sau hiển thị ra thì
[00:31:11] nó có hợp lý hay không Ok không ạ Bây
[00:31:14] giờ tôi sẽ tạo đầu tiên thì tôi sẽ tạo
[00:31:16] đương nhiên là bây giờ tôi sẽ thử vẽ ra
[00:31:18] tao bây giờ theo kiểu databa đơn giản
[00:31:20] đâu nhé Đấy nó sẽ là như sau
[00:31:27] nhỉ
[00:31:32] cài cái tiện ích di sản Viber sẽ dễ nhìn
[00:31:35] thôi
[00:31:50] Ông mấy ông xem cái tên Scope
[00:31:54] Đúng rồi quên quên quên
[00:31:57] chạy cái install đã
[00:32:01] cho Minecraft
[00:32:19] câu truy vấn thôi là một cái thì lấy
[00:32:22] thằng cha và một cái lấy thằng con đúng
[00:32:24] chứ Đấy còn nếu mà làm đệ quy thì nó
[00:32:28] cũng sẽ hình như là nó sẽ chỉ lấy nếu
[00:32:31] thế Tôi nghĩ là chỉ lấy hai thôi vẫn lấy
[00:32:34] thằng cha xong rồi lấy thằng con của tất
[00:32:36] cả những thằng cha đấy rồi nó sẽ nó sẽ
[00:32:39] ra rất nhiều mảng xuống nó sẽ marketing
[00:32:41] nó sẽ dùng cốt để marketing vụ đấy chứ
[00:32:44] nó không Tôi nghĩ là nó không làm phức
[00:32:46] tạp và truy vấn có bao nhiêu truy vấn
[00:32:49] lấy dần dần con con con con con con con
[00:32:51] con con thế thì vỡ mồm đúng không ạ
[00:33:01] ở đây tôi sẽ có là gì bây giờ tôi sẽ có
[00:33:05] là đầu tiên này
[00:33:14] nghĩa bản à Đây
[00:33:22] tiếp theo có bảng là bảng
[00:33:26] chất là mình mình đặt lịch thì mình sẽ
[00:33:29] có bảng bảng booking chẳng hạn
[00:33:34] ID này mình sẽ có
[00:33:37] thường nó sẽ chia ra khung giờ
[00:33:40] kiểu thường là kiểu
[00:33:48] lưu Ca ấy kiểu thế ví dụ là kiểu tôi cứ
[00:33:51] cho là lưu ca nhé sẽ kiểu ship như này
[00:33:53] đi cho dễ nhé tiếp theo nào là Doctor ID
[00:33:57] Giả sử thế
[00:33:59] Giả sử rất là đơn giản như này thôi Chỉ
[00:34:01] Có mỗi như thế này đúng chứ Đấy Ok đầu
[00:34:05] tiên thì bây giờ giả sử Tôi có rất nhiều
[00:34:06] bác sĩ lúc đầu hiển thị toàn bộ bác sĩ
[00:34:08] ấy vì tất cả bác sĩ đến
[00:34:10] khi mà đặt theo ca các thứ thì kiểm tra
[00:34:14] bác sĩ bận hay không vân vân đương nhiên
[00:34:16] còn thêm những cái kiểu nữa là theo ngày
[00:34:18] nữa nhưng mà mấy cái tình tiết đấy thì
[00:34:20] mấy ông què thêm là được đúng chứ Giờ
[00:34:22] tôi chỉ có hai bảng này đơn giản thôi
[00:34:25] mấy ông hình dung bài toán không nhỉ
[00:34:27] Hình dung mà đúng không
[00:34:30] khó hiểu gì Hỏi ngay nhé Không thì tôi
[00:34:33] có mặc định cho mấy ông là hiểu hết rồi
[00:34:43] cái việc bang livestream như này mấy ông
[00:34:45] có lợi duy nhất ở điểm so với những cái
[00:34:47] bạn xem sau là mấy ông hỏi được hỏi trực
[00:34:49] tiếp được để tôi trả lời luôn còn nếu
[00:34:52] mấy ông mà ngồi nghe chỉ nghe thôi Thì
[00:34:54] thực ra mấy ông ngồi xem livestream làm
[00:34:56] gì chẳng làm gì cho vui
[00:34:58] cái lợi nhất là cái mình có thể hỏi được
[00:35:02] trực tiếp luôn mà
[00:35:03] chứ mấy cái bạn sau rồi Mấy bạn đấy sẽ
[00:35:06] bị ngại khi mà kiểu nhắn tin hỏi các thứ
[00:35:08] thứ đúng không Mà tôi cũng sẽ lúc đấy
[00:35:10] tôi cũng sẽ không biết được mấy bạn ấy
[00:35:12] đang hỏi gì trả lời đúng không nên em
[00:35:15] mấy ông thực sự nên tận dụng ý tôi tôi
[00:35:18] thường hay tận dụng kiểu khi mà học trên
[00:35:19] lớp tôi chỉ tận dụng được mỗi đấy Không
[00:35:21] thì mình ở nhà học cho nhanh tức là dựng
[00:35:24] hỏi thầy liên tục cái gì Hỏi được thì
[00:35:26] tranh thủ hỏi luôn
[00:35:47] ID tự động tăng này sẽ có table
[00:35:58] tưởng thế nào
[00:36:00] bây giờ nó đi soi Cũng tương đối đúng
[00:36:03] nghĩa bởi vì trong này có Bạn post và
[00:36:06] bạn khóa học mà
[00:36:12] để số được
[00:36:22] không hiểu
[00:36:30] đúng không ạ
[00:36:32] Bây giờ thì mình làm như thế nào bây giờ
[00:36:35] đầu tiên là tôi cứ Insert trước thủ công
[00:36:38] một vài Bác sĩ đúng không ạ
[00:36:54] thì bây giờ đầu tiên là tôi cần vào cái
[00:36:58] trang hiển thị toàn bộ bác sĩ đúng chứ
[00:37:25] không tôi sẽ việc lấy bác sĩ nó là nó là
[00:37:29] nó là kiểu linh hoạt ra sao tôi chọn Tôi
[00:37:34] chọn ca này thì bác sĩ danh sách bác sĩ
[00:37:38] rảnh như này nhưng ca khác thì danh sách
[00:37:40] bác sĩ nó sẽ thay đổi nên là tôi sẽ
[00:37:42] không truyền cố định cái danh sách bác
[00:37:43] sĩ vào Lúc đầu Lúc đầu tôi sẽ kiểu hiển
[00:37:47] thị ra cái view các thứ thứ bình thường
[00:37:49] sau đó thì dùng ra Switch để gọi lên api
[00:37:53] Lấy toàn bộ bác sĩ về hiểu không ạ Bây
[00:37:56] giờ mình sẽ có là một cái form như này
[00:37:59] đúng chứ có một cái form sẽ là chọn K
[00:38:02] nha
[00:38:03] chọn ca thì mình không nên cho người
[00:38:05] dùng Điền sẽ cố định giả
[00:38:26] nhỏ hơn bằng sự là có 4k thôi chẳng hạn
[00:38:45] qua nó là cô cô pilot nhé hồi trước tôi
[00:38:47] từ dùng cái Tab Life nó mất phí nhưng mà
[00:38:50] có pilot này tôi thấy ngon hơn nó đọc có
[00:38:53] vẻ hiểu hơn mà nó nhẹ hơn thằng táp Life
[00:38:56] nó ăn ram phết nên là tôi phải bỏ đi rồi
[00:39:04] hiển thị ra ca các thứ thì mình gọi
[00:39:06] booking ngay đúng chứ mặc định là Ca Đầu
[00:39:10] Tiên Thực ra thích thì ông Nghĩa là ngay
[00:39:14] từ vừa vào vừa vào như này ông ấy có
[00:39:17] đoạn Ra squip đây tôi sẽ dùng Giga rồi
[00:39:35] bằng gì tôi sẽ có một cái Ở đây bây giờ
[00:39:39] này chọn bác sĩ Đúng chưa
[00:39:41] mình sẽ có select ở đây mình sẽ có ID ở
[00:39:45] đây là select Doctor như này
[00:39:49] xử lý cái này đầu tiên khi trang 10 load
[00:39:53] vào Tôi sẽ gọi Ajax
[00:40:21] ở đây sẽ mình sẽ có router gọi đến là
[00:40:27] tên là ví dụ ghét
[00:40:40] để phô mai thớt là ghét
[00:40:47] sừng cho cái data mình sẽ truyền lên hàm
[00:40:50] số cái gì
[00:40:52] không nên dùng đăng để xem nào của nó và
[00:40:56] mình nên chuyển lên tham số gì mình nên
[00:40:59] chuyển lên cái sheet cái mà ca mà mình
[00:41:02] đã chọn đây tôi sẽ đặt đi cho nó
[00:41:05] Selection
[00:41:07] rồi tôi sẽ lấy giá trị về là
[00:41:27] khi mà chạy xong này
[00:41:46] đây giả sử như này tôi sẽ
[00:41:50] ra không cần phải lock nó ra đấy còn phê
[00:41:53] thì mấy ông tự xử lý nhé Tôi từng dạy mà
[00:41:55] ông về cái giặt dùng này rồi nhưng đại
[00:41:58] khái thì tôi sẽ có một cái router như
[00:42:00] này đúng chứ tôi sẽ
[00:42:02] ở đây Tôi có một cái router này
[00:42:25] ai như này thì bây giờ mình sẽ cần là gì
[00:42:28] mình sẽ cần Return trả về hết toàn bộ
[00:42:31] danh sách Doctor đang trống đúng không ạ
[00:42:34] Và mình đầu tiên mình phải truyền lên
[00:42:36] cái gì mình sẽ chuyển lên
[00:42:39] cái ca mình sẽ lấy ship này
[00:42:43] tài khoản request gate
[00:42:48] Sau đó mình sẽ lấy toàn bộ toàn bộ bác
[00:42:53] sĩ không
[00:42:59] đấy thì tôi sẽ gọi đến
[00:43:02] Bình tĩnh bình tĩnh gọi Doctor đã nha
[00:43:07] Tôi sẽ có reasonship này
[00:43:15] lịch đúng chứ
[00:43:17] Thì mình sẽ có là logic function này là
[00:43:22] booking này
[00:43:24] và mình sẽ returned
[00:43:33] sẽ booking class
[00:43:37] thế xong rồi đấy
[00:43:44] những bác sĩ nào
[00:43:47] à
[00:43:49] que has à
[00:43:54] Mẹ Đã dần hát đây nghĩa là những bác sĩ
[00:43:57] nào không có cà chồng trong buổi hôm đấy
[00:44:01] là xong như này và lấy ra được các bác
[00:44:05] sĩ dành hết Xong
[00:44:08] bây giờ mình sẽ ăn thôi
[00:44:23] những cái tôi từng Thực ra là mấy bạn để
[00:44:27] ý là tôi từng đăng lên blog của tôi rồi
[00:44:30] này là có cả về
[00:44:34] tôi sẽ cập nhật trên cái này sau và tiếp
[00:44:37] theo là Subscribe text của tôi đã cài
[00:44:39] cái gì này
[00:44:47] ngày và thôi mà
[00:44:49] thêm ngày ở đây cao cả ngày ở đây thôi
[00:44:51] mà
[00:44:59] Tôi sẽ thử mở cái cửa sổ inps lên để mấy
[00:45:03] ông tiện theo dõi nhé Network này chọn
[00:45:06] vào bên xr nhé Tại trang này lập tức là
[00:45:09] nó sẽ gọi gọi lên để lấy về toàn bộ các
[00:45:12] bác sĩ đang rảnh tôi sẽ thử mở tele
[00:45:16] Scope mấy ông tiện theo dõi hơn nhé này
[00:45:25] vấn Tức là sao lấy câu như này nó lấy
[00:45:28] lấy tất cả các bác sĩ không nằm trong
[00:45:31] cái việc là
[00:45:33] ấn ở đây xem kỹ hơn này đây không nằm
[00:45:37] trong việc kiểu
[00:45:38] Uầy bây giờ nó sửa lại Facebook nhìn
[00:45:41] trông giao diện đẹp hơn hẳn nhìn dễ đọc
[00:45:42] hơn hồi trước là kiểu cái này thẳng hết
[00:45:44] một dòng
[00:45:50] không Đương nhiên bây giờ booking không
[00:45:52] có gì cả đương nhiên nó sẽ Thì bây giờ
[00:45:55] mình việc đơn giản mình chỉ đổ dữ liệu
[00:45:57] vào trong này thì thôi thì mình sẽ là
[00:46:00] đây
[00:46:05] nó sẽ là như này tôi sẽ tạo ra một cái
[00:46:08] biến là led
[00:46:15] đấy
[00:46:23] quá chuẩn rồi
[00:46:25] gợi ý này quá Đúng rồi Nhưng mà cốt này
[00:46:28] cốt vẫn còn nông dân thực ra không nên
[00:46:30] không nên nối chuỗi kiểu không không
[00:46:33] thực sự không nên nói chuỗi kiểu ở
[00:46:35] option kiểu như này mà nên kiểu dùng cái
[00:46:36] hàm có sẵn của nó để mà tạo
[00:46:45] Subaru nhưng đôi khi thì không trong
[00:46:47] trường hợp này ông đang thấy nó sắp free
[00:46:49] nhưng đôi khi nó tách hẳn hai câu truy
[00:46:50] vấn nó tùy ứng biến theo là kiểu em em
[00:46:54] bởi vì hat many đôi khi nó là kiểu dạng
[00:46:57] là là sẽ sắp ra nhưng mà giả One hay cái
[00:47:01] gì đó Vừa nãy em thấy là vừa nãy ngay
[00:47:04] vừa nãy đây thôi
[00:47:24] động ứng biến thế nên là Nhưng mà thực
[00:47:26] tế thực tế thì sắp có đi nó luôn nặng
[00:47:30] hơn so với roi nên là nhiều lúc nhiều
[00:47:34] lúc thì để mà tối ưu thì nên dùng cho
[00:47:40] thì tôi đang nói dở cái đoạn này Thực ra
[00:47:42] cái Đoạn này đoạn code nó khá nông dân
[00:47:45] kiểu là ina cả ông phải ghi thẳng như
[00:47:49] này Thực ra có rất nhiều hàm của thằng
[00:47:51] Siri để mà ông sẽ tạo cái này ra bằng
[00:47:54] thẻ HTML
[00:48:01] thích cái việc là là nối theo kiểu như
[00:48:04] này ít nhất là như thế này tôi sẽ thích
[00:48:07] nối theo kiểu Từng dòng tất cả sao Rồi
[00:48:10] sao tôi sẽ có thể kết kiểu này nhé Tôi
[00:48:12] sẽ nối Cậu này mấy ông xem nó có trông
[00:48:15] nó có vẻ ổn hơn không nhé
[00:48:24] sẽ mường tượng được là đoạn nào đoạn thể
[00:48:27] mở đoạn nào đoạn giữa và đoạn nào thể
[00:48:30] đóng ít nhất là như thế này còn nếu mà
[00:48:32] ông dùng được cả hàm các thứ thử nữa thì
[00:48:34] càng ngon nhiều tôi không Tôi không
[00:48:36] hướng dẫn Hàn nữa vì cơ bản thì về chả
[00:48:39] ai dùng gì cả
[00:48:41] nhưng mà ít ra Kiểu này thì trông nó
[00:48:44] phải tường minh hơn tường minh hơn phần
[00:48:46] nào và với ông gì về sau ông dễ sửa cái
[00:48:48] thằng ở giữa hơn còn đâu về cơ bản thì
[00:48:51] không thay đổi rồi đấy Tuấn Long như này
[00:48:54] đúng chứ đúng chứ
[00:48:57] ca nào sẽ thế thôi
[00:48:59] à Đúng rồi Bây giờ Bây giờ thì tôi sẽ
[00:49:02] tống cái này tổng cái này nha
[00:49:05] tôi tạo một cái hàm răng Trần này xong
[00:49:08] rồi Ghét free Doctor đúng chứ
[00:49:17] mặc định là lúc đầu vào tôi gọi hàm này
[00:49:21] nhưng mà bất kỳ khi nào mà cái thằng này
[00:49:24] nó thay đổi thì lại gọi hàm hàm này phát
[00:49:27] nữa đấy
[00:49:30] khi K thay đổi thì mình sẽ phải cậu
[00:49:48] đúng không gọi K2 lại lấy lại danh sách
[00:49:51] đúng chứ rất xịn đấy Bây giờ Bây giờ tôi
[00:49:54] sẽ thử đặt Tôi đặt lịch nhé Đặt lịch thì
[00:49:57] tôi sẽ tôi đặt lịch này mình sẽ có một
[00:50:00] cái nút bắt Tân ở đây đi
[00:50:04] ok anh ạ
[00:50:10] à Tôi có nền đây nữa nêm sẽ là ship đúng
[00:50:13] chứ và nêm ở đây sẽ là Apple ID
[00:50:27] nhảy đến cái
[00:50:28] Action sẽ nhảy lên cái router là thường
[00:50:33] là sẽ là
[00:50:38] buồn cười điểm mà booking nó vừa động từ
[00:50:41] nó vừa là nó vừa là ở
[00:50:44] danh từ đặt tên để store vậy
[00:51:05] nghe đi giả sử như này đi
[00:51:08] lại trang này Tôi đặt lịch bác sĩ 1 với
[00:51:14] mọi thứ đều 1 đúng không
[00:51:21] sẽ kiểu như này
[00:51:31] ở trên này cho dù biến này ông chỉ dùng
[00:51:33] một lần ở dưới Nhưng mà như tôi đã từng
[00:51:36] nói là toàn bộ khai báo trên như này vào
[00:51:39] cái xử lý này đôi khi mình sẽ tách ra
[00:51:41] mua đồ hoặc là chỉ đơn giản là nhìn này
[00:51:43] dễ tưởng mình là hiểu à là trong cái hàm
[00:51:46] này mình có lấy những cái request gì về
[00:51:49] sau mình sẽ sửa ở chỗ đấy thôi sửa chỗ
[00:51:52] đấy chứ không phải là kéo xuống dưới tôi
[00:51:54] Tôi thấy rất nhiều người là kiểu thấy nó
[00:51:58] biến thành dùng ở một chỗ thôi Nên là
[00:52:00] gọi hẳn dưới Giả sử giả sử như này nhé
[00:52:03] Chỉ có nhiều ông lười kiểu như là
[00:52:17] cứ bắt người sau phải đoán Tao tao sử
[00:52:22] dụng biến nào truyền lên các thứ Nhìn
[00:52:24] trông có vẻ không trượt lên cái gì cả
[00:52:25] đúng không ạ Đấy Xong rồi ông kia Không
[00:52:28] biết từ đấy khiến nó vài Dead các thứ
[00:52:30] thử sai chẳng hạn thế
[00:52:32] nên là không Không nên như thế vẫn làm
[00:52:36] theo kiểu như này
[00:52:38] đôi khi mấy ông cốt là mình không phải
[00:52:40] nghĩ việc người sau nữa chứ không phải
[00:52:42] là cốt xong luôn được xịn quá đúng không
[00:52:45] ạ Đấy mình sẽ có booking như này mình sẽ
[00:52:49] ra không cần
[00:52:52] xong kiểu như này đương nhiên là mình sẽ
[00:52:57] phải có
[00:52:58] phi able
[00:53:00] kiểu
[00:53:11] publicem bằng fail nữa Ok
[00:53:15] tại trang này
[00:53:18] có vẻ in search được rồi
[00:53:25] nếu mà inser được rồi Như này khi mà
[00:53:28] quay lại cả trong booking
[00:53:29] như này thì các bạn thấy không hề còn
[00:53:33] bạn Long nữa đúng không ạ Nhưng mà nếu
[00:53:35] sang ca thứ hai thì bạn Long lại xuất
[00:53:37] hiện ok chưa Đúng rồi
[00:53:51] thể sinh viên tôi vẫn phải trả phí
[00:53:55] ok thì câu truy vấn các thứ các bạn cũng
[00:53:59] sẽ thấy ở đây nó lấy xong rồi lưu lại
[00:54:01] như thế nào xử lý như thế nào
[00:54:07] để bản chất là không phải Isaac theo
[00:54:10] kiểu
[00:54:12] Nó là kiểu là gọi gọi dùng ra Switch
[00:54:16] phải gọi lên để lấy dữ liệu về đấy thì
[00:54:18] không phải Ajax thì cũng là một cái cậu
[00:54:20] khác để mà nó
[00:54:23] động như thế này còn nếu mà em không
[00:54:25] muốn làm ra skip thì em muốn làm pp
[00:54:27] thuần ý thì em sẽ phải cưỡng một lần
[00:54:30] chọn K xong rồi phải ấn nút để mà load
[00:54:32] lại cái bác sĩ này thì không ai làm thế
[00:54:34] Cả
[00:54:35] đúng rồi bản chất nó là xh nhưng mà nó
[00:54:39] là kiểu dạng là hàm khác của bên mấy cái
[00:54:43] thư viện kiểu facebook các thứ thôi nó
[00:54:46] không bản chất nó như nhau nó vẫn là ra
[00:54:48] squip là một hai nó vẫn là đều xhr tất
[00:54:52] cả là gọi dữ liệu lên các thứ
[00:55:06] ví dụ bốc bát sỹ Đúng rồi Đúng rồi book
[00:55:11] theo giờ nó sẽ khó hơn nó sẽ kiểu a các
[00:55:15] thứ nữa
[00:55:23] theo giờ đúng không Thì bạn nhưng mà ý ý
[00:55:27] ở đây mình chữa mình không phải chữa
[00:55:29] theo cậu theo theo kiểu là là để mà chữa
[00:55:33] hẳn dứt điểm bài toán các bạn cái này
[00:55:36] các bạn cũng nên tự chủ động để mà suy
[00:55:39] nghĩ các thứ giải quyết cái việc theo
[00:55:41] giờ ý thì về cơ bản về cơ bản ấy nó là
[00:55:45] các bạn sẽ phải cái câu truy vấn các bạn
[00:55:47] select nó sẽ phải lằng nhằng hơn ở cái
[00:55:50] đoạn kiểm tra xem là bác sĩ Rảnh hay
[00:55:52] không thôi nhưng nhưng về cái mặt nghiệp
[00:55:56] vụ thì nó vẫn giống nhau đó là lấy ra
[00:55:59] được bác sĩ rảnh bằng cách là kiểm tra
[00:56:00] xem là có lịch trống hay có lịch tại
[00:56:04] thời điểm đấy Không đúng chứ nghĩa là
[00:56:07] mình đang sửa các bạn là để các bạn hình
[00:56:11] dung ra bài toán nghiệp vụ chứ mình
[00:56:12] không chữa theo cậu dạng là cho ăn sẵn
[00:56:16] thì các bạn đúng nghĩa là các bạn cop
[00:56:20] hết phúc của mình về là xong được cái đồ
[00:56:22] án rồi thì hết thứ để mà làm mất rồi
[00:56:24] đúng không ạ
[00:56:25] Tại bây giờ mình nghĩ là cái bài toán
[00:56:28] nghiệp vụ này có nhiều bạn vẫn còn đang
[00:56:30] thắc mắc thì mình sẽ chữa theo mức độ
[00:56:32] đơn giản và và
[00:56:33] tối giản nhất để mà các bạn nhìn vào các
[00:56:37] bạn hình dung được thôi Chứ các bạn
[00:56:39] không thể mà Có code này về để biến
[00:56:41] thành cái đồ án các bạn được đúng chứ
[00:56:44] còn ông bố tôi chữa thêm cụ thể hơn nữa
[00:56:47] thì khác gì tôi làm hết hộ đồ ăn của ông
[00:56:50] mất rồi
[00:56:52] các bạn hiểu không ạ
[00:56:55] Nói chung là đồ án này thì
[00:56:57] tôi vẫn là người hướng dẫn đúng không ạ
[00:57:00] Và tôi sẽ tôi sẽ hướng dẫn các bạn ở một
[00:57:03] cái mức tương đối thôi tôi khẳng định ở
[00:57:05] việc mà tôi chữa đến như bây giờ rồi ấy
[00:57:07] khẳng định như bây giờ rồi ấy thì thì
[00:57:11] thì nó nó như là chữa Chắc phải 60 đến
[00:57:15] 70% rồi đúng không ạ gần như là 40 30%
[00:57:20] hẹn gặp lại các bạn sẽ phải hình dung
[00:57:21] bài toán và các bạn sẽ phải tự code nữa
[00:57:24] các thứ thứ nữa
[00:57:32] giờ là chuẩn thì nó không khác gì cả
[00:57:35] đừng để cho khách hàng chọn giờ à Đúng
[00:57:39] rồi Nhân tiện thể tôi quên mất đấy hôm
[00:57:41] hôm qua hôm qua tôi đi tôi đi
[00:57:47] cắt tóc
[00:57:49] ở một cái quán sang chảnh cực Chắc là
[00:57:52] bây giờ tôi cũng phải quay mấy ông bởi
[00:57:55] vì ở cái cái cái tôi thích nhất cái cái
[00:57:57] đặt lịch của nó mỗi tội là lúc mà đến
[00:58:00] cái bước cuối Ấn đặt không được buồn
[00:58:02] cười Nhưng mà cái trang này Công nhận
[00:58:04] xịn để đặt lịch
[00:58:16] loại cát đặt xong rồi cái này cái này
[00:58:19] vẫn chọn được nhưng nó sẽ kiểu tô màu
[00:58:20] xám rồi Kiểu không không khuya không
[00:58:24] khuyên dùng
[00:58:25] Tại sao lại bấm vào hiển thị ra lý do
[00:58:28] đấy
[00:58:29] như thế này
[00:58:30] sau giả sử chọn cái này này đề xuất lại
[00:58:34] không khuyên dùng các thứ nhưng có thể
[00:58:35] bấm được Có thể bấm được nhé
[00:58:37] Giả sử thậm chí là bỏ qua cái này tao
[00:58:40] không cạo râu chẳng hạn
[00:58:42] rồi có thể nó sẽ kiểu Cái này gọi ốc sên
[00:58:45] tất cả nó có thể thêm những cái đi kèm
[00:58:47] nữa nếu các bạn chọn đấy không muốn thêm
[00:58:50] này
[00:58:51] xong rồi Cái này buồn cười vãi
[00:58:55] bạn bạn hãy chọn thợ của bạn một là kiểu
[00:58:59] Junior Nhưng mà cái này Junior nó nó
[00:59:03] ngồi khoe luôn là của bọn tao không có
[00:59:05] video bọn tao Biến hết thành simio xong
[00:59:07] bắt buộc phải chọn này tăng lên 100.000
[00:59:27] hiển thị không giờ nó hiển thị ra toàn
[00:59:29] bộ giờ cho các bạn chọn xong rồi nó sẽ
[00:59:31] tự động cộng thêm cái số thời gian mà
[00:59:34] mình đã chọn những cái dịch vụ là sửa
[00:59:36] đây nó có đề cấp dịch vụ ở đây một tiếng
[00:59:39] này 45 phút này hay cái gì gì đó như này
[00:59:41] này
[00:59:42] cộng thêm cộng thêm cộng thêm để nó sẽ
[00:59:44] hiển thị ra thôi thì kiểu thế mấy ông
[00:59:47] hình dung không
[01:00:52] cái gì hay mình sẽ học đúng không ạ Cái
[01:00:55] gì Dở của nó thì mình sẽ né Chắc chắn
[01:00:57] rồi thì các bạn sẽ cài càng học hỏi thêm
[01:01:01] được nhiều đúng không ạ Tôi bây giờ ví
[01:01:03] dụ bây giờ tôi dùng kể cả Facebook hay
[01:01:05] dùng bất kỳ gì tôi sẽ thấy tôi bắt đầu
[01:01:08] ngồi So sánh Tại sao thằng Facebook so
[01:01:11] với thằng Twitter chẳng hạn nó khác nhau
[01:01:13] những cái điểm gì chẳng hạn thế nó hướng
[01:01:16] đến cái điểm gì mấy ông có ở thắc mắc
[01:01:18] điều đấy ví dụ điển hình á Ông mấy ông
[01:01:21] có biết được thằng thích Twitter nó đăng
[01:01:24] bài nó có giới hạn ký tự không
[01:01:26] chẳng hạn thế cũng đã là giống như là
[01:01:29] Tại sao Tik Tok nó nổi hơn nó cùng là
[01:01:31] mạng nền tảng về video nó lại nó nó tự
[01:01:35] nhiên lại vượt nổi lên trong khi đó là
[01:01:38] có rất nhiều nền tảng về video rồi cái
[01:01:41] chẳng hạn nổi lên vì sao đấy Chẳng hạn
[01:01:43] mình sẽ thắc mắc những cái đấy nó hướng
[01:01:44] lên đối tượng là gì đấy nhu cầu của
[01:01:47] người dùng thực sự là gì Vân và để hướng
[01:01:50] đến đối tượng đấy thì nó sẽ làm những
[01:01:51] cái gì để càng ngày đối tượng đấy sẽ
[01:01:54] càng cần nó hơn đúng không ạ sẽ phát
[01:01:57] triển lên như thế nào vân vân đấy là cái
[01:01:59] suy nghĩ của dân công nghệ của mình đúng
[01:02:02] không ạ người dùng bình thường có nghĩ
[01:02:04] cái điều đấy không ít đúng không Nhưng
[01:02:07] mà chắc chắn mình sẽ phải học hỏi mình
[01:02:08] phải nghĩ những điều đấy thì mình mới
[01:02:10] làm cái sản phẩm mình lên được đúng
[01:02:13] không ạ Tôi đang vẫn đang hướng đến mấy
[01:02:15] ông là suy nghĩ như một lập trình viên
[01:02:17] thực sự là một đi vlogper Tức là nhà
[01:02:20] phát triển nghĩa là nhìn vào những cái
[01:02:22] người khác đã làm để phát triển để nâng
[01:02:25] cấp nó lên để để không phải để sao chép
[01:02:28] nữa mà để nâng cấp mình sẽ học hỏi những
[01:02:31] người trước để nâng cấp lên chứ không
[01:02:34] phải là một cốt đơ một Cốt Đơn là chỉ
[01:02:36] ngồi gõ lại những cái gì mà mình đã biết
[01:02:38] và chỉ gõ lại những cái gì mình đã được
[01:02:41] dạy tôi không hướng mấy ông như thế đúng
[01:02:43] không ạ Thường mấy ông kiểu phát triển
[01:02:45] phát triển lên các thứ
[01:02:47] thầy có chữa code không ạ là ok bây giờ
[01:02:51] xong xong xong mấy cái các bạn thắc mắc
[01:02:54] rồi đấy bây giờ Nhóm nào cần mình chữa
[01:02:56] nhỉ
[01:02:58] gọi thôi gọi Mít nhé để mình sẽ chữa
[01:03:01] luôn
[01:03:44] trước
[01:03:45] Ý bạn là ngôn ngữ lập trình nào trước á
[01:03:48] Ở
[01:03:55] học đi học lập trình rồi chứ kia cậu ông
[01:03:58] xác định ông không học theo đại học
[01:03:59] nhưng mà tôi vẫn không hưởng mấy ông như
[01:04:02] thế
[01:04:03] [âm nhạc]
[01:04:05] nhưng mà thích thì vẫn phải học mấy cái
[01:04:08] cơ bản cũng được tí hon trước cũng được
[01:04:15] ra bạn ra vào lúc đầu khó lắm Chào em
[01:04:38] nhóm em nhóm mấy nhỉ
[01:04:54] không
[01:05:05] bán vé
[01:05:11] nhớ là hôm trước là anh nhớ nhìn trông
[01:05:13] nó cứ bị loạn đấy đúng không
[01:05:28] đúng không Bởi vì nhiều cái loạn quá
[01:05:40] [âm nhạc]
[01:07:39] luôn không còn bằng
[01:08:08] không
[01:08:09] lấy thêm cái propin name
[01:08:13] cái thằng này trước khi em lấy để tránh
[01:08:16] việc nó sẽ bị n cái truy vấn em sẽ phải
[01:08:20] quit thêm ở đây
[01:08:27] rồi
[01:08:29] mặc định đâu
[01:08:44] đừng có nên mặc định để pâu có gì cả
[01:08:46] Mình vẫn ghi thêm ở đây thôi
[01:09:14] đây là của thằng sation
[01:09:16] Còn đây là em đang gọi nó là đô lazip
[01:09:20] thẳng như này luôn Chứ em đâu gọi thông
[01:09:22] qua cái thằng này em đâu có gọi thông
[01:09:25] qua thằng season đâu
[01:09:27] Đúng chứ
[01:09:29] em đã gọi đây là gọi từ thằng em muốn
[01:09:33] gọi theo kiểu như này thì em sẽ phải gọi
[01:09:35] thông qua thằng season nó như này cơ
[01:09:45] như thế này đấy
[01:09:47] [âm nhạc]
[01:09:59] nhất thì em phải cài DD box 3 hoặc là
[01:10:01] tele Scope
[01:10:06] đây em sẽ hiểu để mà em sửa cái có truy
[01:10:10] vấn đương nhiên là cái này toàn bộ là
[01:10:13] mới với các bạn thì thực ra là anh không
[01:10:15] đòi hỏi khắt khe gì lắm nhưng mà ý anh à
[01:10:18] đoạn này anh chỉ cho mấy em để em biết
[01:10:21] cách để tối ưu mà đúng không để mà mình
[01:10:24] mới cho dễ sửa các thứ
[01:10:31] như thế này
[01:10:33] nhưng mà thôi kệ vậy
[01:10:36] [âm nhạc]
[01:10:38] tốt tổ đây
[01:10:40] cái đoạn này hồi hôm trước anh hơi khó
[01:10:43] hiểu này cái đoạn này xử lý như nào nhỉ
[01:10:46] cái đoạn này anh chưa hiểu cái logic
[01:10:48] đoạn này lắm
[01:10:54] em em lưu trong database là lưu số phút
[01:10:57] thôi ạ Thì hôm trước anh có nói đấy thì
[01:11:00] mình lưu lại nó là số phút
[01:11:07] thúc chưa nhỉ
[01:11:44] thấy chưa
[01:12:03] 1440 mà tức là nằm trong vòng 1 ngày ạ
[01:12:06] Còn cái Drive này là là nó sẽ cộng thêm
[01:12:11] những cái ngày ở phía sau thì mình chỉ
[01:12:14] cần chia dư chưa lấy phần mềm
[01:12:27] ngày
[01:12:37] hành
[01:12:38] đúng không Và Cùng lắm là
[01:12:42] giờ cái giờ giờ mà kiểu nó gọn nhẹ
[01:12:50] cái thời gian mà nó di chuyển là tốn mất
[01:12:54] bao nhiêu thì lúc đấy em phải quy hạnh
[01:12:56] phúc sau em sẽ dùng hàng để cộng vào để
[01:13:00] mà về sau em có thể dùng bằng chính câu
[01:13:03] SQL hay truy vấn được là là cái cái xe
[01:13:07] đấy nó đang di chuyển hay không em Làm
[01:13:09] kiểu này thì em truy vấn kiểu gì
[01:13:17] tại thời điểm hiện tại sẽ xe có đang
[01:13:20] đang đi hay không
[01:13:23] ông ông lấy cái đấy ra kiểu gì bây giờ
[01:13:33] Anh hiểu ý em nhớ rằng đang nói là khi
[01:13:36] mà em làm cậu Lưu kiểu như này em sẽ rất
[01:13:39] khó để truy vấn những cái khác
[01:13:41] bởi vì em lưu lưu lại cái không phải lưu
[01:13:45] lại thời gian Mỗi lần em lưu này là con
[01:13:48] số thì em lại phải tính toán lại để mà
[01:13:50] em ra được thời gian thì em sẽ không tận
[01:13:52] dụng được những cái hàm thời gian
[01:13:54] em làm sao biết được là là
[01:13:58] trong thời gian này là có những xe đang
[01:14:00] chạy xe nào sắp chạy em sẽ làm kiểu gì
[01:14:04] em lại phải lấy thời gian rồi em mới
[01:14:06] tính à không phải làm thế Cả
[01:14:09] Nói chung là có hàm thời gian lý do cả
[01:14:11] bây giờ đoạn này em phải sửa đã bay đấy
[01:14:14] anh có việc cái database kiểu như kiểu
[01:14:16] số food đâu nhỉ
[01:14:26] thời gian mình phải lưu lại thời gian để
[01:14:28] mình xử lý chứ mình không lưu lại là số
[01:14:32] phút hai cái gì đó Đương nhiên nó bị
[01:14:33] thừa với cái khoản dây này gì đó nhưng
[01:14:35] cái đấy kệ không sao cả thực ra chuẩn
[01:14:38] nhất là mình lưu lại dạng thực ra lý
[01:14:40] tưởng nhất đấy vẫn luôn lưu lại ở dạng
[01:14:42] time để về sau mình có thể quy đổi cái
[01:14:44] thời gian đấy ra mọi cái khác theo ngày
[01:14:47] giờ hay là dùng phút gì đó hay là thậm
[01:14:49] chí là mình xử lý vài cái thời gian đấy
[01:14:52] mình đỡ phải dùng cái hàm để mà convert
[01:14:54] nó ra thăm xem thì mình mới format được
[01:14:57] lý tưởng nhất vẫn luôn là lưu lại dạng
[01:15:00] Hamster em ạ Đấy bỏ bỏ mấy cái phút phần
[01:15:03] phút sai rồi
[01:15:17] nhưng mà
[01:15:35] một cái cốp của nó thì tốt em tạo một
[01:15:37] cái cốp đi anh thấy vẫn chưa dùng cái
[01:15:40] code gì cả
[01:15:49] info hay cái gì đó tùy em đặt xong rồi
[01:15:52] chuyển dạ là gọi gọi như này thôi
[01:16:08] 2 định ẩn đi toàn bộ những cái mình
[01:16:10] không cần chẳng hạn thế
[01:16:35] không thì em thử code thử xem
[01:17:33] Tống nó ra một cái hàm số đặt tên là cái
[01:17:35] hàm đấy thì sẽ hình dung được đoạn này
[01:17:37] cốt
[01:17:39] cái gì
[01:17:41] thực ra không nên chuyển không biên biến
[01:17:44] nó thành alloween nó lợi hơn adray rất
[01:17:46] nhiều Nếu em muốn dùng kiểu mát kiểu như
[01:17:48] này đi ăn nữa thì về cơ bản nó dùng hàm
[01:17:51] mát nó vẫn xịn hơn rất nhiều
[01:18:12] ki thì em sẽ gọi theo kiểu dạng khác
[01:18:14] thôi em sẽ gọi kiểu dạng như này thì nó
[01:18:17] là kia thôi
[01:18:18] không khác gì cả
[01:18:52] đọc anh không hiểu cốt rồi
[01:19:09] ông lưu là phút như thế thì đuổi xuống
[01:19:11] đấy
[01:19:21] cơ bản nó vẫn là nền móng về sau Hiện
[01:19:24] tại em vẫn có thể code được nhưng về sau
[01:19:26] nó sẽ rất khó nâng cấp và và bảo trì về
[01:19:30] sau thêm tính năng nó sẽ rất khó hoặc là
[01:19:31] về sau muốn xử lý thêm một cái vấn đề
[01:19:33] liên quan đến thời gian cũng không làm
[01:19:35] được
[01:19:36] không ai làm kiểu đấy cả nếu giờ em lưu
[01:19:40] là thời gian là ngày thì em phải đến
[01:19:43] ngày sau trường ngày trước đã biết được
[01:19:44] thời gian nó đi là bao lâu
[01:19:46] không thực ra như anh đã bảo ấy thì em
[01:19:51] Em có thể lưu lại là thời gian bắt đầu
[01:19:54] và thời gian thời gian đi thôi rồi Từ
[01:19:58] đấy mình sẽ quy ước được là thời gian
[01:19:59] kết thúc là là lúc nào
[01:20:02] thường là như thế chứ
[01:20:12] như thế thì làm sao mà xác định được
[01:20:13] đúng không
[01:20:22] Đúng rồi Nghĩa là nghĩa là ví dụ là giả
[01:20:26] sử là đi bắt đầu từ 7 giờ tối nay đúng
[01:20:28] không Nhưng mà thôi thời gian chuyến đi
[01:20:32] ở tận 6 tiếng thì mình sẽ tự động biết
[01:20:35] được là sẽ sang ngày hôm sau chẳng hạn
[01:20:37] thế
[01:20:38] đúng không
[01:20:58] tiên em đi lại thời gian khởi hành thôi
[01:21:00] mà đúng không sau đó thì em
[01:21:03] sau đó thì khách hàng đặt vào ngày nào
[01:21:05] thì em cộng thêm thời gian đấy để ra
[01:21:08] được là là kiểu kết thúc là tại ngày nào
[01:21:13] giờ nào Chú không thấy đặt vé bình
[01:21:17] thường đặt vé xe buýt hay đặt máy bay
[01:21:18] cũng thế à sẽ luôn cộng thêm 2 tiếng
[01:21:21] cộng thêm 3 Tài Chính nó sẽ đề xuất ra
[01:21:23] cái chẳng ai làm nữa cố định thời gian
[01:21:25] kết thúc như thế cả em vẫn sẽ luôn là
[01:21:27] thời gian bắt đầu
[01:21:29] cộng thêm thời gian quãng quá trình thì
[01:21:33] sẽ ra được thời gian kết thúc nó không
[01:21:36] lưu lại thời gian kết thúc
[01:21:43] gian đầu và thêm kết thúc luôn mình chỉ
[01:21:45] đúng rồi anh hiểu ý em nhưng mà Đấy là
[01:21:48] do là em cố định cái thời gian bắt đầu
[01:21:51] và em cố định thời gian thời gian quá
[01:21:54] trình nên nó sẽ ra nó sẽ hiển thị ra đấy
[01:21:58] ra kết thúc chứ không phải mình lưu lại
[01:22:00] thời gian kết thúc phân biệt nha phân
[01:22:04] biệt nha Mình không lưu lại thời gian
[01:22:06] kết thúc bởi vì về sau em có thể thay
[01:22:08] đổi thời gian quá trình thì thời gian
[01:22:11] kết thúc em lại phải thay đổi à đúng
[01:22:13] không
[01:22:23] phút thì nó cũng vậy thôi
[01:22:25] Cái gì ông ý kiếm cái gì ông đi gọi tham
[01:22:28] xem cơ mà chứ không phải ngày
[01:22:30] [âm nhạc]
[01:22:40] liên quan đến ông Nếu thế Lưu lại kiểu
[01:22:42] than thôi em lưu lại kiểu tham thôi Nó
[01:22:43] có giờ phút thôi
[01:22:51] là lưu lại tham nhé Xong rồi thời gian
[01:22:54] quãng đường đi thế thôi em sẽ lưu lại
[01:22:56] mỗi hai cái đấy
[01:22:57] Vào thời gian quãng đường đi em sẽ lưu
[01:22:59] lại ở phút sau em sẽ cộng số phút đấy em
[01:23:02] dùng hàm của sq cũng được Em dùng cộng
[01:23:04] số phút đấy cộng với thời gian
[01:23:07] cộng với thời gian bắt đầu thì em sẽ ra
[01:23:09] được thời gian kết thúc là lúc nào thế
[01:23:11] xong
[01:24:41] đưa ID nó sẽ là cái gì nhỉ
[01:24:51] một nhà cung cấp xe nhà xe
[01:27:07] bụng quá
[01:27:14] em sau nhé
