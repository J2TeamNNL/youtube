# Lập trình web cơ bản - buổi 28 - PHP - Thống kê

- Video ID: `T1RCc4zALNc`
- URL: https://www.youtube.com/watch?v=T1RCc4zALNc
- Published: 2022-01-07
- Duration: 1h 44m 9s (6249s)
- Language: vi
- Subtitle source: auto
- Kind: live

## Transcript

[00:00:34] anh
[00:00:34] alo alo chào bạn
[00:00:42] à à
[00:00:42] ừ ừ
[00:00:57] À hôm nay on hơi muộn Bởi vì tao ra mình
[00:00:57] cũng chẳng biết tâm sự nói gì trong buổi
[00:00:58] hôm nay ờ
[00:01:01] Ô kìa
[00:01:03] em gà hôm nay thì điểm về cái chủ đề hôm
[00:01:06] nay mình định dậy thì ra thứ gì có thể
[00:01:10] có vài bạn con tâm rồi mình thấy sự ra
[00:01:13] nó khá là đơn giản thì mình dậy cho nếu
[00:01:16] mà các bạn biết về skul rồi
[00:01:18] sau
[00:01:19] khi mà mình dậy các bạn về Apple rồi thì
[00:01:22] cái
[00:01:24] 10 cái câu lệnh hôm nay mình sẽ dạy các
[00:01:27] bạn thực nó lại rất là dễ Nó thống kê
[00:01:30] thì ta dễ đến cái gì đó không ạ
[00:01:35] nhưng mà đương nhiên là mình sẽ phân
[00:01:38] tích các bạn là nên thống kê những cái
[00:01:40] gì trong bộ hôm nay để các bạn dễ hình
[00:01:43] dung về ngoại à a&e
[00:01:53] ở ngoài ra thì
[00:01:53] ở đây mình cho xem các bạn nha Thì thực
[00:01:57] ra có cái tính năng xuất hóa đơn ấy thì
[00:02:00] mình lại không định dạy các bạn Tại sao
[00:02:02] bởi vì à ở đâu Mình mới sửa cái này rồi
[00:02:04] không phải dạng PDF nữa mà xuất hóa đơn
[00:02:07] này là xuất hóa đơn cùng email có thể
[00:02:10] pdf này có thể Excel hoặc bất cứ gì khác
[00:02:12] từ ra cái này nó lại khá dễ theo kiểu là
[00:02:15] các bạn chỉ cần cha TP rồi kết hợp với
[00:02:18] kiểu Excel hoặc pdf đó xảy ra các bạn
[00:02:21] một cái thư viện gì đó ở các bạn chỉ cần
[00:02:24] tải thư viện đấy về sau đó thì gọi đến
[00:02:27] cái hàm của nó là được kiểu kiểu như này
[00:02:31] cách chèn file và sau đó thì khai báo
[00:02:34] đúng kiểu ngay nhưng sự ra được cái file
[00:02:36] để mà các bạn đính kèm với cái email thế
[00:02:40] này thì mình nghĩa là bởi vì nó đơn giản
[00:02:43] quá và cũng nhiều cố đời chị là liên
[00:02:47] quan thư viện nên là mình sẽ không đề
[00:02:49] cập mình sẽ mình sẽ ghi ở đây để các bạn
[00:02:53] muốn mò đấy các bạn hãy tự mò để là
[00:02:56] à còn bắt đầu từ tuần sau thì mình sẽ
[00:02:59] dạy các bạn phải gj và sẽ có một tí
[00:03:02] Enrique nữa g Kali nó thư viện của
[00:03:05] nó thư viện ra Swift đối ngoại thì nó sẽ
[00:03:09] khiến nó hốt ra Swift nó nhanh hơn tiện
[00:03:12] hơn cũng như là nó đã có khá nhiều thư
[00:03:15] viện khó nhiều khá nhiều Gọi là Pocket
[00:03:18] là cái gói khá nhiều cái kiểu na ná
[00:03:23] giống kiểu cái này khá nhiều thư viện
[00:03:25] đẹp mà hỗ trợ các bạn giả sử virus nặng
[00:03:28] nó có cái thư viện đầy ra date Các bạn
[00:03:31] thấy cô vào đây là sẽ nhà nên rất nhiều
[00:03:33] chẳng hạn thế tương tự Thế có rất nhiều
[00:03:36] cái nó ổn hơn khi nó trang web của các
[00:03:39] bạn nó biến anh trong web kiểu anh nó
[00:03:42] trải nghiệm người dùng có tốt hơn thay
[00:03:43] vì pp họ thần hoàn toàn TP thần hoàn
[00:03:47] toàn thì làm cái gì nó phải tải lại
[00:03:49] Trang đúng không ạ Còn bây giờ bấm là nó
[00:03:52] sẽ tự tự động mượt hơn nó không phải lại
[00:03:55] ra nữa
[00:03:56] anh ấy mình sẽ đề cập các bạn với Lee và
[00:04:00] áo giáp
[00:04:02] anh nói chung hàng cần như tất cả các
[00:04:04] đội sau
[00:04:05] mình sẽ dạy các bạn với Siro đi đấy
[00:04:08] nghĩa là bây giờ giả sử bây giờ là
[00:04:11] còn
[00:04:13] cho là còn vài tuần nữa bạn ba bốn lần
[00:04:17] nữa đến Tết
[00:04:19] Anh hợp âm nấm ngon
[00:04:20] Ừ ừ thế sau Tết âm tội hết sự cái dậy
[00:04:24] rồi Có khi phải sau Tết là mình phải bảo
[00:04:27] vệ luôn ý mày hết cái dậy rồi nhỉ Cho
[00:04:30] mình sẽ thông báo với cái việc
[00:04:32] bảo vệ đồ án sớm để cho các bạn chuẩn bị
[00:04:36] mà thực ra là một tháng nữa thì các bạn
[00:04:38] có khi hết thư sẽ xử cái đây mà làm rồi
[00:04:48] em ạ bởi vì thay ca nếu mà làm xong toàn
[00:04:48] bộ tính năng xem sửa xóa xong thì mình
[00:04:51] chỉ cần làm mỗi giỏ hàng đặt hàng và
[00:04:54] thống kê nữa có nghĩa là
[00:04:57] mà chẳng cần thống kê giỏ hàng và quản
[00:05:00] lý hóa đơn là có nhiều các bạn gần như
[00:05:02] xong một cái được cái đồ án các bạn rồi
[00:05:05] Bạn đương nhiên là có thể thêm những
[00:05:07] tính năng phụ nữa đây tính năng mở rộng
[00:05:09] nhưng ngoài ra các bạn hoàn toàn những
[00:05:12] tính năng phụ khác tính năng mở rộng nhé
[00:05:14] Anh Bình phụ nó thể là chỉnh sửa thông
[00:05:17] tin cá nhân ở
[00:05:24] em xem lại đơn đã đặt vân vân để những
[00:05:24] tính năng phụ
[00:05:25] ừ ừ
[00:05:32] Ừ ok Nói chung là bây giờ mình sẽ bắt
[00:05:32] đầu trả lời các câu hỏi nhé Thì hôm
[00:05:35] trước có bạn hỏi các bạn có bạn rất tò
[00:05:38] mò cái vụ là
[00:05:39] Facebook dùng công nghệ gì thì ra bản
[00:05:42] chất là
[00:05:43] Ừ để mà biết được một cái công ty đạt
[00:05:47] với công ty lớn rồi Công nghệ gì Các bạn
[00:05:49] thì cảnh tra Google là xong là sửa
[00:05:52] Facebook technologia use này sẽ là nó sẽ
[00:05:56] dụng những công nghệ gì ở đây ở đây Cập
[00:05:59] là đầu tiêu dùng ngôn
[00:06:02] Cái ngôn ngữ
[00:06:05] nói chung một công nghệ ở đây là sẽ bao
[00:06:07] gồm khá nhiều cái là sử Đây là kiểu hệ
[00:06:11] điều hành này rồi chạy máy ở như thế nào
[00:06:14] là tao bây như nào ngôn ngữ gì nhưng cái
[00:06:17] này như là hồi cũ thì phải bây giờ nó
[00:06:19] không dùng cái rác nữa đấy
[00:06:23] A và ngoài ra những cái cái gọi là phát
[00:06:27] minhphát minh là không ai phát minh dùng
[00:06:30] từ vẫn là dùng từ công nghệ thôi à Không
[00:06:32] chỉ là công nghệ lõi của nó đi thì nó ra
[00:06:34] à sử dụng Trí Tuệ Nhân Tạo này cho nhận
[00:06:38] diện khuôn mặt này
[00:06:39] Ừ cái này thì trí tuệ nhân tạo Nó để làm
[00:06:43] gì chứ tuệ nhân tạo của nó ngoài việc là
[00:06:46] để để mà kiểu hiển thị Đề xuất cho các
[00:06:50] bạn cái trang chủ các bạn cái newfit các
[00:06:53] bạn ấy thì hiện
[00:06:55] để hiển thị một cách kiểu bài đăng có
[00:06:58] vẹn chung là khá phù hợp với các bạn hơn
[00:07:01] đấy tiếp theo là nhận diện khuôn mặt các
[00:07:05] bạn biết được cái nhận diện khuôn mặt
[00:07:06] này là là để mà kiểu đôi khi nó gợi ý
[00:07:11] tác bạn vào một cái ảnh ở đó những ngoài
[00:07:14] ra nó còn kiểu để nhận diện việc là ai
[00:07:17] đó là kiểu giả mạnh Bạn hãy vân vân nữa
[00:07:21] đấy nó mà công bố có toàn bộ thông tin
[00:07:25] này cho ví dụ fp2 đại khái như thế này
[00:07:28] có khi
[00:07:30] việc tra do tội phạm dễ hơn
[00:07:38] anh nói chung và Facebook hiểu bạn hơn
[00:07:38] chính bạn nóng ạ Các bạn biết cái điều
[00:07:40] đấy tiếp theo nữa là nó còn áp dụng thêm
[00:07:44] nhiều công nghệ thì mà lại làm cái ảnh
[00:07:47] thành khẩu nhiều kích cỡ để máy hiển thị
[00:07:50] phù hợp cho em nhiều nhiều cái thiết bị
[00:07:53] cái việc này nó càng tốt việc là ví dụ
[00:07:57] là các bạn on trên điện thoại độ phân
[00:07:59] giải anh không cần cao lắm em ạ nó khiến
[00:08:02] cho kiểu việc tại ảnh đấy nó vẫn nhanh
[00:08:04] vẫn mượt Còn nếu mà các bạn thon máy
[00:08:07] tính anh phải HD ạ để nhìn phù hợp cái
[00:08:11] này là khi mà các bạn đang một ảnh lên
[00:08:13] dù chất lượng thế nào là cộng sự cố tách
[00:08:15] ra thành nhiều kích cỡ để căn chỉnh sao
[00:08:18] cho phù hợp
[00:08:23] Ừ cái này là
[00:08:23] Ừ thế giới à cái này là thực tế ảo à thế
[00:08:27] nào thì tôi không biết nhưng tôi chẳng
[00:08:29] biết phân tích Nghe Chú Đại khái thế để
[00:08:31] đây đây là những cái mà kiểu nó đang
[00:08:34] những cái công nghệ mà nó dùng công nghệ
[00:08:36] lõi của nó rung như là tôi không ý tôi
[00:08:39] không phải tôi sẽ Đề cập những cái mà
[00:08:41] các bạn thì tra Google như thế mẹ ý tôi
[00:08:44] là
[00:08:50] để để để để mà phân tích xem là Facebook
[00:08:50] rồi Công Nghệ gì ý Thật ra là bản thân
[00:08:53] mình lập trình viên khi ở mình đến cái
[00:08:56] ngưỡng nào đó mình cũng bắt hình dung
[00:08:58] được cái thằng mà mình đang dùng nó áp
[00:09:02] dụng những cái không phải công nghệ và
[00:09:04] Kỹ thuật gì và từ kỹ thuật đấy thì nó sẽ
[00:09:07] là công nghệ gì gia sử gia sửa nhá Ờ tôi
[00:09:11] biết được là thằng Facebook nó dùng nấu
[00:09:13] ask me
[00:09:14] mà Tại sao tôi biết rồi đều đấy vì thứ
[00:09:17] nhất hiển nhiên là nếu mà nó dùng thuần
[00:09:20] swil thôi thì việc lưu lại toàn bộ dữ
[00:09:23] liệu của hàng tỷ người dùng như thế và
[00:09:26] sẽ rất là nặng mà nối do.doi vì nhau thì
[00:09:29] vỡ mồm mẹ mình dùng để không ạ tự nhiên
[00:09:33] nó cũng sẽ vừa rồi Các bạn thấy nó có
[00:09:35] dùng máy của em nhưng mà nó dễ dùng Mai
[00:09:37] quê ở một vài cái thôi chứ không phải là
[00:09:39] nó dùng toàn bộ bằng mail thì chết chắc
[00:09:42] là nó nó chết nó không Lát mình anh như
[00:09:43] thế này Cái thứ nhất thứ hai là các bạn
[00:09:47] nhớ về cái Facebook qua Facebook trước
[00:09:50] khi mà thay đổi giao diện không ạ thì ra
[00:09:52] Facebook trước khi thay đổi giao diện
[00:09:54] loại loa rất là trận bây giờ nó lát mượt
[00:09:56] hơn nha đấy mượt hơn so với ông à của
[00:09:59] máy tính căng căng thì rau với ổn hơn tí
[00:10:02] thì nó rất ngốn ram nữa ông ạ thì tại
[00:10:04] sao nói nguồn ram như thế bởi vì đơn
[00:10:07] giản thôi là nó đã dùng cái cái ngôn ngữ
[00:10:09] lập trình mới của nó chỉ nhà rước
[00:10:12] các bạn bé rồi nó là ngôn ngữ
[00:10:16] ra Switch
[00:10:19] tức là xử lý biến Forland tức là xử lý
[00:10:22] trên chính máy người dùng nghĩa máy
[00:10:24] người dùng kiểu ram ổn Nói chung là mấy
[00:10:27] người dùng ngon đi thì loát nó sẽ giờ
[00:10:30] nhanh và mượt và ngược lại là như thế
[00:10:32] ngược lại là
[00:10:34] xe máy người dùng mà quy thì anh như là
[00:10:37] Lót cái Facebook của sẽ bị đơ Nếu mà nhớ
[00:10:41] về cơ bản thì nó không ngoại mất công
[00:10:43] Loan ở trên server
[00:10:45] ở quần lót nữa rồi vất về cho người dùng
[00:10:48] khiến cho kiểu không bị ảnh hưởng của
[00:10:51] tốc độ mạng hay là server của nó sẽ bị
[00:10:54] nhẹ bớt đi nhẹ bước công việc đi thế này
[00:10:56] là nó giảm thiểu ở chỗ ông là máy mượt
[00:11:00] thì loa Facebook mượt thế thôi do người
[00:11:03] dùng nó tặng
[00:11:05] ở đó Đang phải đánh đổi được đấy bởi vì
[00:11:08] bởi vì hồi trước thì các bạn Lát một cái
[00:11:10] phần 1trang rất là lâu rồi các bạn để ý
[00:11:12] được k các bạn Đấy Minh rồi đôi khi nó
[00:11:15] vẫn còn cái đường Linh đấy đừng Linh là
[00:11:18] profile đ.tp ạ Thực ra nó hồi trước là
[00:11:23] cốt thuần bằng ngôn ngữ p thành ra là
[00:11:26] anh không không phải bữa sau mà khóa sau
[00:11:29] mình sẽ Dậy ờ
[00:11:31] Vì thế nên pp ở các bạn biết rồi pp là
[00:11:35] khi mà nó xử lý xong hết Nó loạt được
[00:11:37] hết thì nó mới nhìn thị ra cả cái trang
[00:11:40] web thế nên là hàng ra nó bị rất nặng
[00:11:43] một cái trang Các bạn thấy vào lót nó sẽ
[00:11:46] rất nặng thế nó chuyển hết dần sang bạc
[00:11:50] lót bằng ra switch
[00:11:57] A và còn thêm một cái nữa Ok vừa rồi
[00:11:57] mình nói qua về ngôn ngữ còn thêm cái gì
[00:12:00] nữa mà mình cảm thấy là mình đoán được
[00:12:02] đó Chính à
[00:12:04] Khi bữa rồi Mình bảo là nó không nó dùng
[00:12:07] nói quá đúng ạ thế nào dù nhé queo ở chỗ
[00:12:10] nào dùng were phải trình cái chỗ gọi lại
[00:12:14] cơ không biết được nó có dùng Apple để
[00:12:17] phi cơ hay là dùng ngôn ngữ lập trình
[00:12:19] của Sica nhưng mình tin là fg cơ đó là
[00:12:22] liên quan việc là khi mà ờ ờ
[00:12:26] bộ tem mình mình đang không đăng nhập
[00:12:29] Facebook nên là mình tạm ví dụ cho anh
[00:12:31] nhá Khi mà các bạn à
[00:12:35] tố cáo bình luận
[00:12:38] hoặc à
[00:12:40] bình luận nói chung là đại khá là khi
[00:12:44] các bạn đăng một cái gì đó đang ở đây ở
[00:12:46] bao gồm cả bình luận này
[00:12:49] tố cáo bình luận này
[00:12:53] tố cáo bài đăng hay vân vân đó cho là
[00:12:56] đang một cái gì đó
[00:12:57] Đang bao chỉnh sửa gì đó tương tự thì nó
[00:13:02] sẽ kích hoạt một cái gì đó sau đó ngay
[00:13:05] lập tức
[00:13:10] Vì thế nên là nó sẽ Khái niệm và chỉ cơ
[00:13:10] mà bọn chị gọi là khi mà cái nào nó được
[00:13:13] đẩy lên thì lập tức là sẽ có một cái đấy
[00:13:15] được thực hiện ông ạ Tại sao tôi nói vụ
[00:13:19] nó dụng chức ở đây 1 vì đôi khi là cái
[00:13:21] bình luận khi bị xóa rồi cái cơ này vẫn
[00:13:24] còn nên này ra trong nó rất lố bịch hiểu
[00:13:27] Khi mà khi mà vào xem tự nhiên ở thấy
[00:13:29] mất hết cả tố cáo mà giỡn rằng giả sử ở
[00:13:33] bình luận vị xá rồi nhưng cái chi cơ vẫn
[00:13:35] được kích hoạt rồi nên này ra là nó vẫn
[00:13:37] in sơ vào trong cái bảng tố cáo bình
[00:13:39] luận thôi luôn bình luận bị xóa nhé bởi
[00:13:42] vì nó không áp dụng Apple cho à ràng
[00:13:46] buộc khóa ngoại thằng thằng Facebook nó
[00:13:49] không chơi dòng buộc đâu đó toàn áp dụng
[00:13:52] cho hết là chi cơ đấy
[00:13:54] ý nghĩa là về sau các bạn sẽ bắt về khái
[00:13:57] niệm chị girl và Ivan và sự kiện là khi
[00:14:01] cái gì xảy ra thì
[00:14:05] cái gì xảy ra cái gì nó cũng sẽ xảy ra
[00:14:09] cùng
[00:14:11] chị sẽ xảy ra không đi
[00:14:14] Sau đó mà cùng nghĩa ngay lập tức ví dụ
[00:14:18] là sử Giả sử mình nói một cách dễ hình
[00:14:20] dung hơn nhé thay vì các bạn dùng for
[00:14:23] key để mà Bởi vì như mình nói là nó sẽ
[00:14:27] không dùng đâu hết à Nó dùng nó equals
[00:14:30] chúng mày queo là sửa là có có người
[00:14:34] dùng này là sửa mình đi Chẳng hạn mình
[00:14:37] mình đang năm 200 575 ở trên trang cá
[00:14:40] nhân mình rồi đồng loại đấy Sau đó thì
[00:14:43] nếu mà giờ sửa lại Wow thì đương nhiên
[00:14:46] là các bạn sẽ nhớ là tất cả bài đăng đấy
[00:14:49] sẽ phải có u ready là chính nhầm ID của
[00:14:52] mình không ạ thì khi mà mình
[00:14:55] Thế Hiển thị tất cả bài đăng của mình mà
[00:14:58] mình sẽ phải roi bảng của các thứ sẽ bị
[00:15:00] nặng nên nó sẽ chơi cổ Kiểu lâu với nhau
[00:15:03] là 1 hoặc là ackworth nhưng mà không có
[00:15:05] ra mù khói ngoại nhưng mà Chính vì không
[00:15:08] có ràng buộc như thế khiến cho là khi mà
[00:15:12] sau khi mà mình giả sử mình xóa trang cá
[00:15:15] nhân mình đi cái toàn bộ những cái bài
[00:15:17] của mình phải hiểu là xóa đóng ạ
[00:15:20] chị sẽ phải hiểu là xóa phải xóa tay
[00:15:23] đang đi thì cái cái cái để mà xóa bài
[00:15:27] đăng này đi Thì bắt buộc mà Bởi vì không
[00:15:30] có ràng buộc tự động rồi nên mình sẽ bắt
[00:15:32] buộc một là can thiệp chị Google
[00:15:34] à hay là cam Hiệp bằng thứ ba nó là một
[00:15:38] thôi nó thích cơ kể theo cái even xóa
[00:15:40] giá
[00:15:41] Xóa Chắc là nhân mình đi và
[00:15:46] còn thêm một cái nữa đó là các bạn để ý
[00:15:49] đôi khi các bạn ấn vào một cái bình luận
[00:15:51] hơn một bài đăng nào đó ở trên trang
[00:15:53] trang chủ các bạn đúng ạ Các bạn hãy tự
[00:15:56] nhiên là cái này không còn tồn tại nữa
[00:15:57] Cái này đã bị xóa rồi cái đã bị gỡ rồi
[00:15:59] các bạn bị thể về chưa mình thì thường
[00:16:02] bị thường xuyên luôn đấy thì thì cái vụ
[00:16:06] đấy nó liên quan đến dịch cơ đó là nó sẽ
[00:16:09] có 2 bảng độc lập một bảng ở bảng bảng
[00:16:12] và sửa bảng mình nọ vừa nói là bảng bài
[00:16:14] đăng ở chim trắng cá nhân người Ngạn hoa
[00:16:16] bài đoạn bảng 7 đang ở trên nhóm một
[00:16:18] nhóm vào nói ạ
[00:16:20] anh vào mua bảng newfit bằng nếu phía
[00:16:23] kia là để lấy toàn bộ ID không phải ai
[00:16:27] đi nữa mà lấy toàn bộ nội dung của bài
[00:16:30] đăng kia luôn đấy Để ốp về ốp về cái cái
[00:16:33] bảng như mít bởi vì nó nấu ếch với để
[00:16:36] tôi thử vẽ Excel cho mấy ông dễ hình
[00:16:40] dung hơn nha
[00:16:41] à à
[00:16:42] khi nãy nó nói trai thì sợ mày cũng
[00:16:44] không hiểu lắm Nó xử có bài đăng bài
[00:16:48] đăng trên trang cá nhân em ạ một tên bài
[00:16:50] đăng Post không ạ sẽ có ai đi rồi con
[00:16:53] tay là nội dung nội dung đi
[00:17:03] như này sau đó đi thử cá ID này mình
[00:17:03] không còn quan trọng nữa với nó nấu ếch
[00:17:04] que thích nó là một cái cái ID được sinh
[00:17:09] ra ngẫu nhiên có để tránh lặp lại thôi
[00:17:12] chứ thực ra IDM không tự động tăng cơ
[00:17:14] lại đi Số gì Số số gì đó kéo nó giống
[00:17:19] kiểu Audi hơn bởi nói bên nấu ép của em
[00:17:23] nó thế tiếp theo của bài bạn là bạn như
[00:17:26] Tít
[00:17:28] à à
[00:17:29] thì nó sẽ không phải lấy theo post ID và
[00:17:33] như này nếu mà làm như thế này thì nó là
[00:17:36] axwell rồi Rất là sao Nghĩa à là sự Để
[00:17:40] newfit xong rồi AD ạ ra sự ra sự dễ thị
[00:17:45] thì đây giả sử là AD là ad một là của
[00:17:49] tôi đi và bài đăng này mà đang một này
[00:17:51] đây về gì á Sơn Tùng MTP
[00:17:56] tất cả nhà Nếu mà chị đã giản như này
[00:17:59] thì rõ ràng là lâu phí của tôi sẽ hiển
[00:18:02] thị bài đăng MTP không ạ nhưng mà không
[00:18:04] cái cái cái điều này nó sẽ dừng nhất là
[00:18:07] nó do bạn như này nó sẽ nặn bởi bàn này
[00:18:10] sẽ rất dài 3 ngày sẽ là lưu lại bài đăng
[00:18:13] của tất cả tất cả bao gồm cả nhóm này cả
[00:18:17] trang cá nhân đấy vợ nó sẽ rất là dài
[00:18:19] nên khi mà roi Thằng này mày cho thằng
[00:18:22] này thì vỡ mồm
[00:18:24] nên nó sẽ không làm điểm này nó sẽ làm
[00:18:27] là gì nó sẽ lưu lại luôn thông tin của
[00:18:30] bài đăng
[00:18:32] lưu lại luôn thông tin của chính cái bà
[00:18:34] đang làm Muốn hiển thị lên ở trong thằng
[00:18:38] ngu ra một sẽ hiển thị đầy đủ thông tin
[00:18:41] mới đăng của thằng ngu dâu một nửa trong
[00:18:43] này Đấy do mà khi mà các bạn bấm vào về
[00:18:46] đăng thận chế bài đang là bị xóa xưởng
[00:18:49] mất rồi như thế này khi các bạn bấm vào
[00:18:51] xem chi tiết bài đăng bài đăng lên ờ ờ
[00:18:53] bị xóa nhưng mà rõ ràng Các bạn thấy là
[00:18:57] vừa ngồi trên trang chủ các bạn vẫn được
[00:18:58] loa lên nó mới được đoán lên luôn ý
[00:19:01] nghĩa nó mới lên luôn Đấy thậm chí là
[00:19:04] các bạn Kéo xuống kéo mấy lần nhé tôi
[00:19:08] còn bị dính á
[00:19:09] Ok ông nghĩ ra mà nó có thể chưa kích
[00:19:13] hoạt chỉ cơ sở để mà xóa thấy bà đang
[00:19:14] này khỏi mi fit đúng không Không nó vẫn
[00:19:17] sẽ giữ nguyên ở trên lưu ý là các bạn
[00:19:18] luôn cơ tôi tả lại cho anh đi fit nó vẫn
[00:19:21] còn ở đấy Xóa kết nó vẫn còn ở ở đấy
[00:19:24] luôn
[00:19:25] ý nghĩa là cái bạn với phim này độc lập
[00:19:28] hoàn toàn so bài bài đang đến nay nó
[00:19:30] không lưu ID của bài post bên này luôn
[00:19:32] Tức tức là khi mà cái bài kể về đang bên
[00:19:37] tốt mà bị xóa đi cái refit của vẫn còn
[00:19:40] Cái Bè đang đấy mày không hình dung
[00:19:49] A và đương nhiên là nó sẽ đưa lại thông
[00:19:49] tin cũ của bà đang kia cơ là sự bài đăng
[00:19:51] này đổi thành khác rồi nó Tùng núi ẩn ạ
[00:19:55] thì cái cái nội dung này vẫn à MTP chẳng
[00:19:59] hạn thế khi mà các bạn bấm vào xem chi
[00:20:01] tiết thì nó mới hiển thị lại cái mới đấy
[00:20:04] thế này tôi nghĩ là cái Tôi đoán được
[00:20:07] thì cơ chế của nó làm nó sẽ áp dụng cho
[00:20:10] Sica gửi thế khi có về đăng vào thì nó
[00:20:13] sẽ luôn sẽ kiểm tra xem nó nó phù hợp
[00:20:15] với lưu phí của ông nào và sẽ tự động
[00:20:17] Insert vào chi phí của ông đấy thì ông
[00:20:20] ấy sẽ hiển thị cái cái đấy lên Còn khi
[00:20:22] bà đang bị xóa đi thì cái chi cơ nó
[00:20:24] chích girl nó khác với cái rõ ràng buộc
[00:20:28] nhé đó là kiểu xe chạy sau đó thôi và nó
[00:20:32] chạy chỉ cần chạy một lần thôi nó không
[00:20:35] có Nó không có kiểu hay chiều dòng 12
[00:20:38] chiều khám chị ạ Insert song với này thì
[00:20:41] nó sẽ có danh buộc lại và bên này Không
[00:20:43] nó chỉ lấy thông tin từ máy này đổ sau
[00:20:45] 12 thôi Thế là hết để ạ Và khi thông tin
[00:20:49] bên này Xóa đi mà không nói dịch girl để
[00:20:51] mà xóa bên này thì cái bên này vẫn còn
[00:20:53] ông ạ
[00:21:01] Ừ nếu các bạn để ý kĩ thì các bạn sẽ
[00:21:01] thấy nó khá khó chịu đúng ạ nhưng các
[00:21:04] bạn sẽ phải hiểu tại sao nó như thế
[00:21:06] thằng Facebook có phải áp dụng có chửa
[00:21:08] đấy để chuyển cho khiến cho nó nó hiển
[00:21:13] thị lý phết như phí được nhanh hơn để đỡ
[00:21:15] phải rồi các thử thứ đúng ạ
[00:21:18] a music các bạn sẽ luôn có bài có bao
[00:21:22] nhiêu bài Lai trong ngày Kiểu gì nó sẽ
[00:21:23] đổi dần dần sang bên này Đấy
[00:21:25] tổ liên tục và đổ sang ở đây nó còn
[00:21:30] không đổ theo một cái trình tự thời gian
[00:21:31] nào cả nè đôi khi các bạn sẽ xem
[00:21:39] em không đi fit có bạn sẽ không ở mất đi
[00:21:39] cách nấu ếch với ao nó phải chơi cơ chế
[00:21:42] nó sẽ lưu lại rất nhiều đây là nó sẽ
[00:21:44] không mất đi
[00:21:46] các bạn phải hiểu nó như thế anh ra là
[00:21:49] nếu hồi trước là mình từng hồi rỡ mình
[00:21:52] từng mò cái grab để mà lấy như phít của
[00:21:54] của bản thân mình ấy chứ ra là của ai mà
[00:21:59] mình có tóc em là nạn thì lấy được cái
[00:22:01] nick phít ở ngọn ngồi nó dài kính không
[00:22:03] kịp mình cứ nó nó có phân ra ngoài anh
[00:22:07] em mình cứ lấy vậy thì mình cứ lấy tiếp
[00:22:09] lấy tiếp với tiếp Nói chung vào kiểu
[00:22:12] có bao nhiêu cái thông tin mà có thể
[00:22:15] Ừ mình phù hợp với người nào là có nhiều
[00:22:17] nó sẽ để sang lý fit mà mình sẽ lấy lấy
[00:22:21] dẫn từ đấy Và thậm chí nó có lặp cơ nó
[00:22:24] có lặp bởi vì liên quan việc cả thằng
[00:22:27] này nó nó chỉnh sửa vậy như nó đầy lại
[00:22:30] sang cái này nó có lắm đấy nhé
[00:22:33] anh
[00:22:35] nói chung là cơ chế này của thằng
[00:22:37] Facebook vừa là yêu vừa là ngược yêu là
[00:22:40] nó nhanh mà ngược các bạn sẽ thấy mẹ sẽ
[00:22:43] Xe mạnh được cả bài đăng đã bị xóa cũng
[00:22:46] như là như vợ rồi mình nói có lắp đúng ạ
[00:22:48] đấy ngân hàng ra là
[00:22:51] nó mình thấy thực ra là
[00:23:00] Ừ nó mà áp dụng kiểu công nghệ kiểu dạng
[00:23:00] giống như bây giờ thì nói thằng nào nhỉ
[00:23:03] từ mạng xã hội là có sister à Twitter
[00:23:06] Mình không dùng lắm đấy mình cũng không
[00:23:08] rành Nhưng mà mình đã lướt qua một vài
[00:23:11] lần bởi vì có vài vài bạn hot girl
[00:23:14] thường hay đăng ảnh trên đấy hơn thì
[00:23:16] mình thấy trên đấy không lập gì cả và có
[00:23:20] vẻ bên bên nước ngoài thích dùng để truy
[00:23:22] tơ hơn
[00:23:25] Ừ Ok nói vừa rồi Khá dài rồi
[00:23:28] vừa rồi là mình nói những cái nó hơi bị
[00:23:31] chuyên sâu một tí gọi Vì ạ không phải là
[00:23:34] khuya cái khóa này vẫn khóa cơ bản nhưng
[00:23:37] mà bắt đầu từ buổi trưa buổi dậy phải
[00:23:41] cái mở rộng này rồi thì mình nghĩ à Nên
[00:23:43] Đề cập những cái nó hơi rộng rộng hơn để
[00:23:46] mà gọi là có hướng Mở hơn cho các bạn
[00:23:49] thì các bạn hình dung hơn đóng ngoặc
[00:23:51] mình nói qua vừa rồi có thể các bạn
[00:23:53] không hiểu còn nhưng mà các bạn sẽ biết
[00:23:57] được qua là lập trình viên mình khi mà
[00:23:59] sử dụng một công nghệ gì đó thì phải
[00:24:02] đoán thử xem là thằng kia nó làm cái đấy
[00:24:05] như thế nào để mà bắt trước hả em ạ hoa
[00:24:08] để mà tránh xa được nữa để mà không nên
[00:24:11] áp dụng vào trong trang của mình do Vân
[00:24:12] đúng ạ a cho bạn càng đoán được như thế
[00:24:16] thì về sau về sau kiểu gì đôi khi các
[00:24:19] bạn vào công ty ở đó vài công ty nó sẽ
[00:24:22] kiểu bảo các bạn làm cái đấy thì các bạn
[00:24:25] đã từng nghĩ nó rồi đúng ạ Các bạn từng
[00:24:28] tham khảo rồi rằng ạ à à
[00:24:31] Có chứ Bây giờ các bạn dùng rất nhiều
[00:24:34] cái trang web rất nhiều công nghệ rất
[00:24:37] nhiều áp rồi nhưng mà các bạn
[00:24:39] khi mà lập trình các bạn không đẩy ra ý
[00:24:42] tưởng gì cả Không biết được mấy anh kia
[00:24:44] làm gì thì ca hơi say không ạ phải học
[00:24:47] hỏi phải gọi
[00:24:48] Chỉ tiếc là
[00:24:56] Vì sao các bạn kệ họ mình quý khách à
[00:24:56] Mình không biết về bên CF đâu ạ
[00:25:00] ờ ờ
[00:25:02] Ừ cái chọn quận huyện này có bạn bạn là
[00:25:05] bây giờ em muốn khi mà đăng ký đăng ký
[00:25:09] điền thông tin cá nhân thì sẽ có vụ chọn
[00:25:12] quận huyện thực ra thì cái mũi chọn quận
[00:25:14] huyện này thì các bạn nên phải dùng
[00:25:16] Switch Vậy sao Tại sao lại như thế bởi
[00:25:19] vì ở đây các bạn dễ hình dung nhé
[00:25:23] AE đăng ký để miễn phí
[00:25:39] nhà mình có chứ một tát đầy đúng
[00:25:39] Ừ thì rõ ràng là các bạn nhớ về vụ là
[00:25:43] thật sự là mình có
[00:25:45] sẽ lấy các chân này
[00:25:47] cô thường chọn quận huyện nó sẽ làm
[00:25:50] trong sẽ lấy áo xinh sẽ là do sự là
[00:25:54] Hà Nội được ạ
[00:25:56] Các bạn thường ai thế là chọn à chọn
[00:26:00] tỉnh thành phố
[00:26:08] sau đó thì mới bắt đầu chọn quận là sau
[00:26:09] đó thì sẽ bắt đầu chọn phường hay gì đó
[00:26:11] đúng không ạ Tại sao lại như thế này
[00:26:14] khá sửa mình cứ để Hồ Chí Minh như chợ
[00:26:17] Ngạn không ạ
[00:26:18] anh em mình chạy thử này
[00:26:32] xe
[00:26:32] tải ngay sau đó thì
[00:26:36] chọn quả trở lại tại select option
[00:26:47] Nếu giả sử đối với Hà Nội thì sẽ có kiểu
[00:26:47] Hoàn Kiếm
[00:26:48] hai bà trưng
[00:26:56] sau đó thì kiểu quận gì nhé hà đôngnhà
[00:26:56] nản
[00:26:58] nhấn đấy là với Hà Nội không ạ này cho
[00:27:02] chọn này về Hà Nội nhưng mà nếu bao giờ
[00:27:04] sử mà
[00:27:06] khi mình chọn Hồ Chí Minh thì cái này nó
[00:27:10] còn đồng họ vì nó không làm đúng nó ạ
[00:27:13] Mình sẽ còn thêm gì ở đây nữa quận 1cho
[00:27:16] nào ạ ở quận 2 hai cái gì dấu vân vân
[00:27:20] vân đúng không ạ
[00:27:22] xe tải
[00:27:23] em giả sử Nga chọn và sau đó mình chọn
[00:27:27] sung dừa nhé không Bởi vì nếu mà như thế
[00:27:29] này nhá Giả sử bây giờ mình có 64 tỉnh
[00:27:33] thành ngọn mì hiển thị là có tất cả sáu
[00:27:35] mươi từ có rất nhiều cuộn từng với 64
[00:27:39] tỉnh hàng ấy thì chị hết ra đây vỡ mồm
[00:27:41] người dùng sẽ chọn cái kia ốm luôn không
[00:27:43] ạ Mình sẽ nở ra gì khi mà chọn Hà Nội
[00:27:47] thì nó sẽ chỉ hiển thị quận của Hà Nội
[00:27:49] không ạ Khi chọn Hồ Chí Minh để hiển thị
[00:27:51] quản Hồ Chí Minh sẽ bản chất nó là gì nó
[00:27:54] là gọi khái niệm gọi làm mát tinh các
[00:27:58] bạn sẽ phải có em là khái niệm này mát
[00:27:59] tinh và sẽ nối thằng này với thằng ngày
[00:28:02] để không ạ
[00:28:05] cho tất cả Sao mẹ là nói thằng Hà Nội
[00:28:08] với tưởng với những ngày tháng này nó
[00:28:10] nào giống mảng bản chất nó dùng mảnh
[00:28:13] thôi ám chỉ được với Hà Nội thì sẽ gồm 3
[00:28:16] gái con với Hồ Chí Minh để sự gồm hai
[00:28:19] cái thằng ạ Đấy sẽ nối nối với nhau sẽ
[00:28:21] dùng mở ra Swift để làm gì đấy thì cái
[00:28:24] này thật ra không cần lấy áp dụng cao
[00:28:26] siêu thư viện thì mấy mà thứ nhất ở các
[00:28:28] bạn sẽ có một tệp dữ liệu có ngần nào
[00:28:31] Cuộn vào ngày mày tỉnh hay cá thứ ở đây
[00:28:35] thì ra hôi trước mình có lưu Vì vậy mình
[00:28:38] có đừng có đánh sao mình cái không biết
[00:28:41] được cái cái đấy thì Zalo lắm rồi chị
[00:28:44] không biết được à Nó con à
[00:28:47] Ê thằng con đúng không có thay đổi gì
[00:28:50] không đi xem Đợi tí nhé em
[00:28:53] Chị đánh dấu xạ sao
[00:28:57] ê ê ê
[00:29:07] à à
[00:29:07] cài đặt ở minh tính
[00:29:10] ừ ừ
[00:29:20] khi bé bạn của mình với bạn của mình
[00:29:20] à Vì sao ạ
[00:29:22] ở lại
[00:29:36] có ai nó sẽ có tỉnh thành phố này quận
[00:29:36] huyện xã phường này vào nó sẽ làm cho
[00:29:39] tải file data ở đây này
[00:29:41] bộ 3 pha và file này sẽ lưu dạng kẹo vi
[00:29:45] sinh mình sẽ đọc những cái pha này bị
[00:29:48] dùng josh quyết về đọc những file này
[00:29:49] màn chất nó sẽ là mã này sau đó thì
[00:29:54] anh đứng ở đây có rất nhiều thông tin
[00:29:56] nữa các bạn đôi khi không cần lấy nó Chị
[00:29:58] ở lấy tên của thành phố thôi trở lại lại
[00:30:01] sẽ có lần này thành phố đây mùng mấy mỗi
[00:30:04] thành phố tỉnh thôi ông ạ ở đâu vừa quận
[00:30:08] huyện còn nên người tỉnh thành phố này
[00:30:12] ở đại khái như thế mình sẽ nối với nhau
[00:30:15] các thử thử qua ba gà này sau đó mình sẽ
[00:30:17] hiển thị ra được
[00:30:19] thế hiển thị ra được hết ở đây mỗi khi
[00:30:21] uống chọn một cái nó sẽ đỡ sơ sang một
[00:30:23] cái
[00:30:24] Ừ cái này chỉ Xuka thì
[00:30:28] hoàn toàn các bạn làm được nhưng mà để
[00:30:31] về sau các bạn làm ơi để mình nghĩ à
[00:30:33] Chưa chưa cần thiết phải làm cái vụ đấy
[00:30:36] thì thực ra là để người dùng đẹp trai nó
[00:30:39] không tốn kém lắm
[00:30:41] à Còn nếu các bạn vẫn muốn làm cái này
[00:30:44] thì chắc à để khi mình dạy về bên gj
[00:30:47] mình sẽ sẽ dạy các bạn về tất cả mấy cái
[00:30:51] á sâu hơn mà bên g-suite bao gồm quản
[00:30:54] Duy sinh đều ngoan ạ à à
[00:31:04] a tiếp theo là mình xin phép chia sẻ về
[00:31:04] bản chất với tune có rất nhiều bạn đã
[00:31:06] từng hỏi mình chín bản thân mình đã từng
[00:31:09] hỏi câu cũng bị đưa mình nghĩ là nó hơn
[00:31:12] mùa xuân tí nhưng mà nghĩa ai từng trải
[00:31:14] qua rồi lại từng vào khá nhiều người tự
[00:31:17] hỏi mình rồi mình đừng hỏi thầy của mình
[00:31:20] ngồi trước
[00:31:21] Ừ anh biết hack Facebook không nhỉ
[00:31:24] Ừ đúng có có có có đấy có câu là thầy
[00:31:28] biết hay Facebook không cho nó Con mẹ
[00:31:30] tôi hỏi cô ấy giờ ngu ngơ hồi hồi năm
[00:31:33] nhất thôi với nhận ra kiểu hỏi Đồ ngu
[00:31:38] xuẩn nhà tại sao là ngu xuẩn bởi vì thế
[00:31:40] là thực Dạ nếu mà hack được một cái á
[00:31:43] ở công ty mà có đến hàng tỷ người dùng
[00:31:46] như thế nhớ sạc mình không ngồi đây nói
[00:31:48] chuyện các bạn rồi ông ạ và chắc chắn sẽ
[00:31:51] nhiều người sẽ không dám dùng nó nữa khi
[00:31:54] mua thằng quen có gì hết được nó không ạ
[00:32:03] ở đây cái thứ nhất thứ hai đó là
[00:32:03] nhiều người hơi bị hiểu nhầm với khái
[00:32:06] niệm về bản chất về cốt đến bây giờ các
[00:32:10] bạn vẫn nghĩ rằng là cốt có thể hack
[00:32:13] Ừ cái khái niệm hack thì nó là Lac nách
[00:32:16] là
[00:32:17] lách luật kiểu kiểu lách cái gì đó
[00:32:28] Ừ thì xin thì nó mới là hack còn còn nếu
[00:32:28] mà tu lý dùng tool đấy thì nó sẽ không
[00:32:32] gọi là khó
[00:32:33] a tool bản chất nó sẽ là gì Là cái gì
[00:32:37] Các bạn làm được thì cái tô nó cũng làm
[00:32:40] được đến là đấy thôi và
[00:32:48] A và kệ tool bản chất nó sẽ tự động tự
[00:32:48] động hơn trong việc làm cái đấy cho các
[00:32:51] bạn ra sửa nhé Có bạn hôm trước hỏi này
[00:32:54] à
[00:32:56] Ừ bạn em để để ảnh chế độ mình tôi anh
[00:33:01] có thể làm tool để xem được cái ảnh đấy
[00:33:03] không
[00:33:04] Xin chào hạ thế thiết thì đương nhiên là
[00:33:07] anh thì mình thử hỏi lại vào đấy
[00:33:09] Ừ ừ em có xem được ảnh này không đứng
[00:33:12] nhiên là không rồi anh anh có hiểu câu
[00:33:15] hỏi của em không bạn ấy chỉ để ảnh mình
[00:33:18] tôi mà
[00:33:18] Ừ ừ đúng Em không xem được cái ảnh đấy
[00:33:21] đúng không Thì bây giờ cái tôn nói chị
[00:33:24] hỗ trợ việc là nó tự động Xem ảnh hộ em
[00:33:27] thôi họ tự động tải ảnh những cái ảnh mà
[00:33:30] em xem được thôi
[00:33:32] Ừ Thì nghĩa là em không xem được anh thì
[00:33:35] đồng nghĩa cái tôn nó không xem rồi đấy
[00:33:36] thế thôi anh ạ
[00:33:40] Ừ
[00:33:41] cái đấy là quan điểm đơn giản về việc tu
[00:33:44] nó như thế nào ra sự giả sử như là bây
[00:33:49] giờ nặn các bạn nghĩ thế thì thế thì
[00:33:51] tung chẳng để làm gì cả ra sẽ sai Các
[00:33:55] bạn thấy bản chất là cái gì cần nên tự
[00:33:57] động chuyển hình giả sử như là các bạn
[00:33:59] chia tay người yêu em ạ Các bạn yêu
[00:34:02] người yêu trong năm từ
[00:34:04] Ừ từ 2 2010 đến bây giờ
[00:34:07] ý là 12 năm để nhận đó thì y không ạ Các
[00:34:12] bạn muốn xóa toàn bộ những anh trong
[00:34:15] phạm Khoảng Đời ra đấy thôi không muốn
[00:34:17] xóa tất cả ảnh đấy hoặc là muốn kỹ hôn
[00:34:21] đấy Xóa ảnh nào mà bạn đấy đã từng thật
[00:34:25] tương tác mình cái ảnh thì thôi ạ hoặc
[00:34:27] có ảnh nào đã tấn tác mà để may mà May
[00:34:30] mà có vũ tát này ạ Đấy ảnh tương tác bạn
[00:34:33] đấy thì xóa
[00:34:34] ông ngồi xoa tay cái đoạn đấy vỡ mồm
[00:34:37] nhiều người dễ bảo ở khuyên ông là thôi
[00:34:39] tạo Sư nick mới đi không ạ nhưng mà
[00:34:42] không cũng không muốn tạo lính mới ông
[00:34:44] tạ mít mới xong thằng khác nhìn vào
[00:34:46] trang cá nhân của ông thấy mới lập nick
[00:34:48] nó nó lại nghĩ ông mà thằng trẻ trâu đấy
[00:34:51] chẳng hạn thế
[00:34:52] à Xong rồi
[00:34:54] ạ Bây giờ làm thế nào Hòa có đôi khi
[00:34:56] không phải xóa mấy ông chỉ muốn đổi hết
[00:34:58] kệ toàn bộ những cái bài đăng đấy Ảnh
[00:35:01] đấy hành chế độ mình tôi để nó sẽ em này
[00:35:03] năm năm năm
[00:35:05] sau xem lại để ân hận hoặc Thấy Vui thỏa
[00:35:09] mãn và rơm rồi không biết được nhưng lại
[00:35:12] khá như thế thì làm như thế nào Ông ngồi
[00:35:16] rửa tay cái đấy Không thể đúng ạ nhưng
[00:35:19] mà ông vẫn làm được điều đấy là ông vẫn
[00:35:22] có thể
[00:35:24] anh xóa hoặc là chuyện nón chế độ mình
[00:35:27] tôi Trầm của nó quá nhiều thì tôn nó sẽ
[00:35:30] can thiệp được kiểu đấy
[00:35:32] em nói chuyện giản thế thôi không ạ ngắm
[00:35:35] chỉ tung mà bạn chất nó sẽ tự động làm
[00:35:37] được những cái thứ mà ông có thể làm chứ
[00:35:39] không phải là làm những thứ mà không thể
[00:35:42] làm Nếu mà Ngoài ra thì vẫn có một vài
[00:35:44] cái gọi lách giống như Điển hình như là
[00:35:47] tôi từng bảo mấy ông già sự là ông lên
[00:35:50] nick này
[00:35:55] Mà tại sao nó luôn thì chị
[00:35:55] Mà tại sao nó lưu lại đường link này nhé
[00:35:58] khi
[00:35:59] bé nhưng mà giả sử như thế này ảnh này
[00:36:02] đấy mấy ông thấy là nó không cho ta nói
[00:36:05] chỉ có xem xem toàn bộ ảnh nó bình
[00:36:08] thường mà sẽ nó sẽ cho tay để tôi cho
[00:36:11] vào một cái vào một cái khác thì cũng
[00:36:15] xem nhé
[00:36:30] họ Đậu gì tôi phải theo dõi gái xinh mời
[00:36:30] ông đều biết rồi Có gì mà lộn
[00:36:45] à à
[00:36:45] ở bên này cho làm nhỉ
[00:37:04] cho đến nay không có tải
[00:37:04] ở bên này xe tải cho tải nó sẽ anh chị
[00:37:08] ra kiểu như thế này con à Không cho tài
[00:37:11] nó sẽ chỉ ra như thế này
[00:37:13] à à
[00:37:14] Ừ mình sinh năm 1978 mấy cái gì
[00:37:18] ý kiến mail mình à mẹ gọi từ thời cấp 1
[00:37:22] mình nghĩ đến rồi Hồi nãy có bộ phim
[00:37:25] trên Disney ở czech Long
[00:37:28] Ừ đấy thì
[00:37:30] thì các bạn thấy là nó cho tải nó sẽ chị
[00:37:33] ta ngay bấm ở đây đã lập tức cả tại được
[00:37:35] cái ảnh có độ dung lượng này luôn như là
[00:37:38] nếu mà không cho tải thì nó sẽ hiển thị
[00:37:40] ra như thế này để xem kích cỡ lớn nhất
[00:37:42] là gì thôi như này nhưng mà các bạn học
[00:37:46] lập trình rồi và mình đã từng nó rồi Cái
[00:37:49] gì mà các bạn nhìn được thì các bạn hoàn
[00:37:51] toàn thể lấy được để tải được các bạn sẽ
[00:37:54] ăn nice pics cửa mở như này đây ngọn sau
[00:37:57] đó thì ấn vào đây chọn đây nó sẽ ra được
[00:38:01] cái anh ấy thôi Đấy cái ảnh nào hết bạn
[00:38:04] chỉ cần tải về đó xong không ạ thằng
[00:38:06] click thì chắc là nó không không nghị Cứ
[00:38:09] kệ vụ này Ừ kệ bộ máy nó không có thực
[00:38:14] ra là nó khó mà Thể Ngăn Được cái vụ này
[00:38:16] như mình đã nói nó kiểu thì chị lên nữa
[00:38:20] Cùng lắm là cũng lắm mà nó thêm logo của
[00:38:23] đây thôi chứ nó mua khi là nó dùng thẻ
[00:38:26] inmates hoa cà backgroud gì gì đó thì
[00:38:29] chị lên rồi Rất khó để lấy
[00:38:31] nó bảo nó không nó không chơi trò cắp
[00:38:34] Ảnh này hình từng nói nhỏ một để mà để
[00:38:38] làm gì cả đấy
[00:38:43] Ừ
[00:38:43] nó để khám phá mình nghỉ chưa gặp trang
[00:38:46] web là kiểu như thế
[00:38:49] Ừ nhưng mà vỡ trong trang này thì mình
[00:38:52] mắc được như thế đúng ạ Mình lách được
[00:38:54] như thế này thì cái việc lách này nó
[00:38:57] không tính là khách lắm Cho dù đúng là
[00:39:00] người dùng có cài đặt rồi những cái này
[00:39:02] cái kiểu kiểu dạng là về bản thân thì
[00:39:06] các bạn vẫn có thể xem được nó A vẫn có
[00:39:10] thể xem được nó thì vẫn thể lấy được nó
[00:39:11] trừ khi mà người dùng phát đi rồi mà các
[00:39:14] bạn vẫn lấy rồi nó hoặc người dùng ẩn ý
[00:39:16] rồi các bạn vẫn lấy được nó thì cái đấy
[00:39:18] nó cả hack mà cái đấy mới là sai mình
[00:39:21] cài đấy mình kiểu
[00:39:23] Ừ ông làm được thì thì cái đấy là về lỗi
[00:39:26] bảo mật
[00:39:33] Ừ Ok
[00:39:33] thôi tiếp nhé trả lời nốt mấy câu xong
[00:39:37] rồi Bộ hôm nay thì ta dạy qua mấy anh
[00:39:39] kia chắc là cũng hơn tiền thôi Mấy buổi
[00:39:42] hôm trước tặng 2 tiền nhiều quá
[00:39:44] ờ ờ thế đi học Bạn này bạn gái mà để hỏi
[00:39:50] là
[00:39:51] Em định kiến khi mà con gái học công
[00:39:54] nghệ thông tin
[00:39:55] ờ ờ
[00:40:01] vì mình không biết bạn đấy chắc là có
[00:40:01] thể do chính bố mẹ luôn hoặc bạn bè định
[00:40:04] kiến gì nghe Định Kiến Huy tiêu cực quá
[00:40:06] nhưng mà chắc là kiểu người ta có thể
[00:40:09] khuyên bạn đấy là học ngành này khó lắm
[00:40:12] học ngày này kiểu
[00:40:14] ờ ờ không không hẳn là phù hợp với con
[00:40:17] gái lắm được cả là nó dễ bị mụn này già
[00:40:20] đi là tóc bạc sớm mà vẫn mấy ông xem ảnh
[00:40:23] cô còn lại rõ cái gì à
[00:40:31] em ngồi đau lưng này Nói chung là bệnh
[00:40:31] đúng không ạ Ngoài ra thì còn là gì nữa
[00:40:33] Nó khá là căng não cậu bởi con trai thì
[00:40:37] về các bạn thì mình thấy con trai vẫn
[00:40:38] Thiên là lâu gic Tính toán kiểu mấy cái
[00:40:41] này hơn và chịu khó ngồi được máy tính
[00:40:43] hơn con gái ngồi một lúc thì sẽ bị đau
[00:40:46] đầu và người Vân bây do thể chất nữa
[00:40:50] thế
[00:40:51] nhưng nhưng mà cái đấy người ta chỉ
[00:40:53] khuyên thôi còn mình nghĩa là thực ra à
[00:40:56] là khá nhiều Điền hình méo ở đây tôi
[00:40:59] nghĩa mấy ông mà lại đây nhiều ông sẽ
[00:41:01] ngưỡng mộ thì thấy con cái học kinh
[00:41:03] nghiệm công nghệ thông tin hơn là kiểu
[00:41:06] chê kẹo voi con gái có niềm tin thì biết
[00:41:09] cái gì không không Khi mà kiểu nghe bạn
[00:41:12] gái là là dân IP các bạn sẽ nhiều ơi bạn
[00:41:15] ấy chắc phải giỏi lắm anh tưởng như thế
[00:41:19] à mình mình nghe thế xong mình sẽ ngưỡng
[00:41:21] mộ mấy bạn gái đấy hôn đấy em mình không
[00:41:25] có định tiền đi cả
[00:41:27] anh nói chung là cái này là có thể trong
[00:41:30] môi trường bạn đấy hả bạn đấy tự đi
[00:41:32] nhưng mà về các bạn thì mình từng nói
[00:41:35] tới buổi hôm trước thôi đó là các bạn
[00:41:37] nên kiểu
[00:41:45] ờ ờ các bạn lên kiểu có cái nhìn khác và
[00:41:45] nếu giờ sửa có bị định kiến thật thì các
[00:41:47] bạn cũng phải phải sống quen với việc là
[00:41:51] sẽ có người này người kia nói
[00:41:53] Ừ Miễn là mình làm đúng cải lương tâm
[00:41:56] mình mà mình cảm thấy mình ở gù vàng hết
[00:41:58] sức mình cho cái cái này thì nói lại
[00:42:03] liên quan đến tâm sự một tí bởi vì thời
[00:42:06] ra câu hỏi tâm sự mà đó là
[00:42:09] thì các bạn hồi hồi trước mình nghe
[00:42:12] người câu đó là
[00:42:14] cho mình đôi khi mình sống cả đời của
[00:42:17] mình để mà cố làm hài lòng mọi người
[00:42:20] Ừ rồi về giao mình mới nhận ra một điều
[00:42:23] đó là một người thời ra số người quan
[00:42:25] tâm mấy ông ấy nói thẳng lại ý sao
[00:42:29] anh kể cả bạn bè mấy ông luôn bạn bè mấy
[00:42:31] ông thực trạng có công việc cầu mua quan
[00:42:34] tâm riêng của họ cuộc sống riêng của họ
[00:42:36] cái sự lo lắng Nói chung là đầy đủ thứ
[00:42:40] mà bọn họ phải lo rồi bọn họ có thể có
[00:42:45] thể kiểu thường hay đi chơi ông ấy
[00:42:47] thường hay hỏi han đấy và biết được tính
[00:42:50] cách mấy ông ấy thực là họ không quan
[00:42:53] tâm ông
[00:42:54] anh đến mức độ đấy đâu
[00:42:57] từ trước khi nó bị rảnh mà chọn cái vì
[00:42:59] là
[00:43:00] à Nhờ những thằng như thấy kệ nó ngoại
[00:43:03] nhà em chị ở cuộc sống này ông phải sống
[00:43:06] về cơ bản là cho chính ông thôi ông mạnh
[00:43:09] kiểu cứ để ý xem thằng kia sẽ nghĩ gì về
[00:43:11] ông ấy về sau nhận ra là
[00:43:14] ông làm bất cứ cái gì nó cũng sẽ nó cũng
[00:43:17] sẽ có thể nói bảo anh sợ ông sẽ không
[00:43:19] hạnh phúc khi mà sống theo cái định kiến
[00:43:22] hay là suy nghĩ người khác không ạ sống
[00:43:25] hơn chính mình thôi nói thế nó cũng hơi
[00:43:28] bị
[00:43:29] Anh hơi bị cá nhân và hơi bị Ích kỷ một
[00:43:32] tí
[00:43:34] anh Bởi vì sao Bởi vì thực ra tính của
[00:43:37] mình lại
[00:43:39] Em
[00:43:39] nghĩ là mình cũng phải lên sống thêm cái
[00:43:42] tiêu chuẩn của cộng đồng chứ không phải
[00:43:44] ở kiểu có nhiều người là sống thì kệ
[00:43:47] luôn tất cả mọi người Tao cứ làm việc
[00:43:49] của tao tao kệ kệ mọi người miễn là xong
[00:43:52] việc của tao
[00:43:53] có lẽ tao hạnh phúc truyền hình giống
[00:43:56] như bây giờ dịch bệnh ở nạn Mấy bạn vẫn
[00:43:59] thì chơi thôi vẫn thấy hơi sai sai Vì từ
[00:44:02] đấy Kiểu gì thế các bạn vẫn check in cái
[00:44:06] thư thứ
[00:44:12] nhờ tại đại khái nó là như thế đó là
[00:44:12] kiểu các bạn phải cân đối giữa việc là
[00:44:14] các bạn sống cho chị Thúy mình ạ Cũng
[00:44:17] không không nên kệ
[00:44:20] em không đáng kể nữa không nên quan tâm
[00:44:22] quá nhiều vào người khác nói gì về mình
[00:44:26] Anh bình thường ai bảo đây nó sống theo
[00:44:28] lương tâm mình thôi Ừ khi nào chuẩn nhất
[00:44:31] xuất hiện sống theo lương tâm
[00:44:34] Ừ cái gì mình thấy đúng phù hợp thì mình
[00:44:37] cứ làm không ạ
[00:44:41] nhà
[00:44:41] mình có ghi chú ở đây Các bạn nhớ đi
[00:44:45] mail Khi mà mình thông báo mà thông báo
[00:44:48] vụ bảo vệ đoán nhá Bởi vì không phải bảo
[00:44:52] vệ đồ án mà làm đồ ăn hay này bởi vì
[00:44:55] mình không không nhắn tin qua Facebook
[00:44:57] các bạn được mình nhất là nhắn tin người
[00:45:00] nó quá nó quá thủ công mà tôi lại rất
[00:45:04] ngại vụ làm tôn lên Facebook bây giờ bị
[00:45:06] tôi nói ở bây làm tôm Facebook nó dậy
[00:45:08] chặn dễ ăn thịt bò em nick tội mấy lần
[00:45:12] ăn thịt boise bay hết rồi Ngày nào tôi
[00:45:15] sẽ không làm tôn Facebook nữa
[00:45:17] anh nghe vừa Tôi có cái mail tất cả các
[00:45:20] bạn đăng ký làm đồ ăn hay nhưng mấy ông
[00:45:23] đã từng đăng ký làm đồ bán rồi thì mấy
[00:45:26] ông Nếu đi mail và nhắn tin tôi có
[00:45:29] discord vậy mà tôi cho vào nhóm nhóm
[00:45:32] Ừ nếu không làm gì nếu mất cứ đợi không
[00:45:35] ạ vợ chẳng mất cái gì cả à
[00:45:38] a tiếp theo của bạn hỏi về api toàn bộ
[00:45:41] những cái thông tin liên quan về api
[00:45:44] này thì mình sẽ mình sẽ đề cập ở trong
[00:45:48] khóa sau mình khóa này mình không dạy
[00:45:50] các bạn với bia có thử được
[00:45:57] à à tức là có nhắc hoa Khi mà mình sẽ
[00:45:57] nói về A ráp thành trào mình sẽ nói qua
[00:45:59] thôi ở có thể mình sẽ bỏ qua khi mình sẽ
[00:46:02] giấc nhưng mà chuyên sâu hơn để mà làm
[00:46:05] một cái bia Chuẩn Vân mình sẽ đề cập ở ổ
[00:46:09] khóa sao rồi Ổn nhất tiếp theo câu cuối
[00:46:17] anh hả
[00:46:17] cách làm bài tập Toán chịu mà ông hỏi
[00:46:21] với tôi về tài liệu gì mấy ông cha của
[00:46:23] nhanh hơn đấy nếu hỏi tôi từ khóa này
[00:46:25] còn đưa
[00:46:30] ờ ờ
[00:46:30] anh Em không rành TP nhưng học luôn
[00:46:33] razzil có được không Thực ra cái này
[00:46:35] nghe coi em thức nó hơi bị sai này bởi
[00:46:38] vì à Thấy nhớ lo nó Facebook vpp của VP
[00:46:42] nên kiểu gì phải học TP và phải biết pp
[00:46:44] phải biết VP ở đây là phải biết đầy đủ
[00:46:47] Vespa có thể làm được những gì Và và
[00:46:51] phải làm được tương tột thương nối ppp
[00:46:53] đã mấy nhảy nhảy vào nó và đưa ra có là
[00:46:58] các bạn cũng không nên nhảy luôn là một
[00:47:00] cả Vương Quốc Bởi vì thức ăn Nếu các bạn
[00:47:02] nhảy và luôn nó quá bị rậm và vì nó quá
[00:47:05] rộng nên các bạn chẳng hiểu cái gì cả
[00:47:08] Ê hồi mà mình học từ đầu đến từ cơ bản
[00:47:11] cho đến mô hình cho mới đến fan gốc mình
[00:47:14] còn thấy mông lưng vì trò đùa thế này ra
[00:47:17] bây giờ mà bạn mới biết một tí Tết đây ạ
[00:47:19] Bạn này hỏi thế có thể mới học 12 tháng
[00:47:23] À mà bạn ấy chỉ mới viết quá
[00:47:26] các hoạt động chính là bạn đấy mới biết
[00:47:28] qua ngôn ngữ này tưởng là cụ phát thôi
[00:47:30] mà bạn nghĩ rằng Trung Quốc thì không có
[00:47:33] gì cả
[00:47:34] A Gọi nhạc
[00:47:36] ạ Bây giờ gọi là mới tất mới cắt bò mình
[00:47:40] tắt bò mà đã áo
[00:47:43] kiểu đi xe máy còn đây có phải đi xe máy
[00:47:46] nữa để phóng tên lửa rồi
[00:47:49] vì farewell về cơ bản Facebook rất khó
[00:47:53] Bây giờ ông nào khẳng định có thể làm
[00:47:54] chủ thành đạo nhưng nói việc là nhảy vào
[00:47:57] khi mà bình còn năng lơ mơ như thế họ sẽ
[00:48:01] bị cậu ra nặng khó
[00:48:04] cho nên là lời khuyên là vẫn vậy biết
[00:48:07] đấy đủ sống như học xong quá này tôi mới
[00:48:09] dám dậy mấy ông nhà báo Mở mô hình này
[00:48:12] sau đó mình nhảy liền cái cuối mà em
[00:48:14] Trung Quốc này thì nó không mực mới kiểu
[00:48:18] mới gọi là dễ dễ hiểu hơn tí về sao mình
[00:48:22] dậy rare các bạn sẽ thấy
[00:48:35] 300 mình không có khóa gì hết nào độc
[00:48:35] lập đâu mình dậy ra Speed rồi mà chỉ
[00:48:38] chạy ra sức và mức tương đối thôi
[00:48:45] em có tuần sau từ tuần sau mình sẽ dạy
[00:48:45] các bạn với Lee đấy
[00:48:51] Ừ ok Nói chung là đại khá như thế á mà
[00:48:51] có hai cái này cho để cuối bộ nhớ Nhắc
[00:48:54] tôi tôi chia sẻ nhé Còn bây giờ mình sẽ
[00:48:56] dạy các bạn về
[00:49:00] ờ ờ thống kê thống kê
[00:49:04] ở đầu tiên và bên admin này à
[00:49:13] khi đăng nhập vào đi ngoại
[00:49:13] cô gái này copy cái này xuống đây để này
[00:49:16] chồng cũng được
[00:49:17] khi nghe xong
[00:49:19] ờ ờ
[00:49:22] anh xem Hóa đơn đã
[00:49:24] có hóa đơn hôm trước có hai đơn như thế
[00:49:26] này
[00:49:27] Ờ thì đầu tiên là các bạn muốn vào cái
[00:49:30] trang đầu tiên như thế này trang đầu
[00:49:33] tiên Trang mới vào ấy thường là sẽ hiển
[00:49:35] thị luôn thống kê nó hợp lý hơn
[00:49:42] nhà mình chuyên TP lẫn cả ra Swift theo
[00:49:42] kiểu ở mức tương đối thôi mình Thiên này
[00:49:44] bác en hơn theo kiểu là B nasware Hôn
[00:49:46] mình sẽ dạy các bạn về lại TP reserved
[00:49:50] đi chuyến sau về ép Gao mình đã dậy một
[00:49:54] cách tương đối rồi đấy ạ
[00:49:56] trà dậy xong khóa sau như mình nói chậm
[00:50:00] vợ hết Sư các em à giận sẽ thỉnh thoảng
[00:50:02] để mà nitrite là cốc thôi à
[00:50:06] ừ ừ
[00:50:08] khi bé bị sự thống kê ở đây thôi ta Các
[00:50:11] bạn thấy hơi ít thông tin để có thể
[00:50:13] thống kê đúng không ạ
[00:50:15] em nhận đấy ít thông tin thôi nhưng mà
[00:50:18] còn rất nhiều cái để mình có thể thống
[00:50:20] kê được Đây là mấy ông thử liệt kê tôi
[00:50:22] giờ sự với một thời trang web bán hàng
[00:50:24] để tôi thử hỏi các bạn luôn anh có 100
[00:50:27] Ông ngồi đây nhưng 100 ông tôi tin 50
[00:50:30] ông xe máy rồi thì à
[00:50:33] Anh theo các bạn thì một trang web bán
[00:50:35] hàng thì sẽ có nên có những cái thống kê
[00:50:38] gì
[00:50:40] à à
[00:50:42] ở một trang web bán hàng tìm ra điểm
[00:50:47] danh nào
[00:50:48] Ừ
[00:50:49] thì nên có những thống kê gì à
[00:51:00] ưu điểm danh nào mấy ông ơi
[00:51:00] à à
[00:51:03] à à
[00:51:04] ở kho
[00:51:06] hóa đơn
[00:51:07] số đơn cái từ số đơn ấy nói rất là chung
[00:51:12] chung
[00:51:12] Mã số đơn cụ thể số lượng thì sau đơn đã
[00:51:15] đạt 2 số đơn như thế nào tất cả đơn
[00:51:18] doanh số
[00:51:21] cô đơn trong ngày
[00:51:23] Ừ Ok để tôi thử liệt kê hết lại những
[00:51:26] cái ý các bạn nha à
[00:51:30] ờ ờ
[00:51:32] nhà hàng trong kho đúng không ạ
[00:51:37] Mã số đơn trong ngày
[00:51:45] A
[00:51:45] hai.co chỉ Nó tồn kho lắm ạ Dùng từng
[00:51:48] tồn kho đi
[00:51:55] số đơn trong ngày này lần này
[00:51:55] về doanh thu
[00:52:02] một số thành viên
[00:52:02] lượng truy cập cái có phải rất nhiều
[00:52:05] không ạ
[00:52:06] ờ ờ
[00:52:08] à à
[00:52:10] Mã số đơn theo
[00:52:12] đã theo thời theo theo mốc thời gian đi
[00:52:16] hết bao gồm trong ngày trong tháng trong
[00:52:19] năm Quý gì đó hàng bán chạy nhất
[00:52:23] khi hạ hàng bán chạy nhất là sẽ gộp
[00:52:26] chung vào cái số sản phẩm bán này sẽ bao
[00:52:29] gồm là là thống kê sản phẩm bán chạy
[00:52:32] không ạ bao gồm bán chạy
[00:52:34] Và thậm chí là bán chạy nó sẽ ngược lại
[00:52:38] đúng không ạ sẽ là hàng mà cửa không bán
[00:52:41] chạy đúng ạ Không bán chạy Tức là chỉ
[00:52:44] làm chị chẳng bán được cái cỡ như thế
[00:52:58] xe khách hàng tiềm năng đấu ngoài khách
[00:52:58] hàng tiềm năng
[00:53:01] tức là ấm chỉ là nếu mà cụ thể hơn sẽ là
[00:53:04] số 1 là có thể số đơn khách đã đạt hoặc
[00:53:10] cả số tiền khách đã trả Vân Vân đó ngoại
[00:53:14] họ xử bạn đến với đặt một đơn rồi đặt
[00:53:18] chục triệu không ạ Sẽ Khác
[00:53:29] cơ
[00:53:29] sở Thống kê như thế Bây giờ để các bạn
[00:53:33] liệt kê ra thì nó sẽ tương đối như này
[00:53:35] đúng không ạ nghĩa từ một cái thống kê
[00:53:37] thôi sẽ
[00:53:38] nó sẽ dài hơn sản phẩm theo loại đó cũng
[00:53:42] được
[00:53:43] mã
[00:53:44] sản phẩm theo loại ngày âm Chỉ làm chưa
[00:53:49] thể loại này có bao nhiêu sản phẩm thể
[00:53:50] loại kia có bao nhiêu sản phẩm cũng được
[00:53:57] số mã giảm giá
[00:53:57] 300 à
[00:54:00] Ừ ok Bây giờ mình bắt đầu lượt lượng
[00:54:03] luật bớt nhé thứ nhất tạo mình không có
[00:54:06] tồn kho với như mình đã nói mình không
[00:54:08] dạy các bạn vừa cả lưu lại là là nhập
[00:54:12] vậy nhập về bao nhiêu số lượng sản phẩm
[00:54:15] đang ở trong database đang là bao nhiêu
[00:54:17] nên không có tồn kho bây giờ mình sẽ
[00:54:20] lượt bớt dần nhé và đôi nhà không Có
[00:54:22] giảm giá không ạ Mình mình chưa dậy các
[00:54:24] bạn bây giảm giá giảm giá một cái điều
[00:54:27] rất khó khó đấy phải dễ đâu Bạn nghĩ là
[00:54:30] nó chỉ xem thêm thử Xóa Nhưng cái để nó
[00:54:32] khác mà xem thêm sữa xóa
[00:54:34] anh nghe mình chưa Đấy cập ông nào mà ôm
[00:54:38] về làm thì cũng được thôi nhưng mà tôi
[00:54:40] sẽ bắt bẻ cái đấy ạ
[00:54:47] Vì sao nhiều câu ếch queo để do các bạn
[00:54:47] phải chuyên sâu về bên em nhiều hơn để
[00:54:50] tối ưu cầu Apple Không mình là sữa nặng
[00:54:52] và các bạn sẽ phải lạnh Inax các thử nữa
[00:54:55] cho nhẹ bụng để mà thống kê để mà tính
[00:54:58] toán nữa không phải để tính toán là để
[00:55:01] gói wears nó được
[00:55:03] ờ ờ
[00:55:09] ở đây nhá đầu tiên là Xem lướt qua bảng
[00:55:09] phố Đắt mình dậy lưu lại những gì để
[00:55:11] chồng kê được Nó chỉ có giá thôi chứ
[00:55:14] Chồng giá này bà loại sản phẩm này á đầu
[00:55:19] nhà sản xuất chứ không có loại luôn mình
[00:55:22] làm không có loại thì chắc là chị thống
[00:55:24] kê được à nhà suốt là có bao nhiêu sản
[00:55:26] phẩm và giá Thằng nào nhiều nhất giá
[00:55:30] thấp nhất hay gì gì đó thôi cũng không
[00:55:32] còn giá nhập về giá bán mà chỉ có mỗi
[00:55:35] giá bán loạn thế kia thì bảng
[00:55:39] ở bảng A đây ra mình có thể thống kê
[00:55:42] được cái gì
[00:55:44] à thực ra thì như vừa nãy các bạn nói
[00:55:47] thì có hệ thống kê được Doanh số trong
[00:55:49] ngày này đúng không ạ Bởi vì nó có thời
[00:55:52] gian và nó có tổng tiền rồi đấy
[00:55:59] chị Xuka Mình có để thống kê thêm giờ
[00:55:59] sửa như à khách hàng mua ở đâu nhiều
[00:56:01] nhất này đấy bởi vì ở đây à Thật ra bởi
[00:56:05] vì mình đang gộp chung vào trong cái cột
[00:56:07] là cột địa chỉ và cột này thời ta như
[00:56:10] mình từng nói nó cột đa chị thì ra trải
[00:56:12] nghiệm đấy ạ Làm cho thống kê này nó khó
[00:56:15] hơn nếu mà thống kê muốn cụ thể theo
[00:56:16] tỉnh thành phố nào đó là sự thật giữa
[00:56:19] quốc gia nào đó là sự tỉnh nào được mua
[00:56:22] nhiều nhất để ở mình mình mình mở thêm
[00:56:25] chi nhánh ở trong đấy đại khá như thế
[00:56:28] thì mình mình nếu mà giờ sự bởi vì hôm
[00:56:31] trước mình nhập địa chỉ ở đây nó nhắn
[00:56:34] như thế này các bạn có thể trồng cây
[00:56:36] được Nếu là nhập địa chỉ rãi hơn là sử
[00:56:39] có cả phố cả quận huyện đó thì hạnh tên
[00:56:43] thành phố thì mỗi người sẽ nhập thêm một
[00:56:46] kìa Anh thành ra là mình rất khó và
[00:56:48] thống kê theo lời hứa hẹn trừ khi mình
[00:56:50] tách hẳn các cột riêng ra là cột tên phố
[00:56:54] này ạ sau đó đi số địa chỉ này xong ngồi
[00:56:59] quận huyện này rồi tỉnh thành giống như
[00:57:01] nhiều nơi làm thì mình còn toàn hệ thống
[00:57:03] kê được xem là đã tỉnh thành phố nào đạt
[00:57:07] đơn nhiều nhất mềm các bạn hình dung bọn
[00:57:09] đấy do các bạn phải thiết kế ra đây sao
[00:57:12] cho mà Để về sau các bạn làm được
[00:57:15] em làm được thống kê
[00:57:18] chị đã bây giờ để lưu lại thông tin nhắn
[00:57:20] làm việc nếu mà các bạn lưu lại hết toàn
[00:57:23] bộ trong một cột thì cứ trả nó không
[00:57:25] không thống kê được gì và cũng không tìm
[00:57:28] kiếm cái gì cả đúng không ạ là sử như
[00:57:30] mình từng nói đây các bạn có thể góp hết
[00:57:32] toàn bộ Cái này thành chung một cột cột
[00:57:34] tên là có thông tin hóa đơn cũng được mà
[00:57:38] nếu mà các bạn không làm theo quy tắc
[00:57:40] kiểu bỏ qua đa chị thì được cái đấy hoàn
[00:57:42] toàn được nó không sai vì nó về các bạn
[00:57:46] nó vẫn có thông tin của hóa đơn và vẫn
[00:57:48] hiển thị được cho người dùng đúng không
[00:57:49] ạ nhưng mà vì sao mày không lọc được là
[00:57:52] thằng nào ở đâu đóng ạ này các thứ thứ
[00:57:56] đấy
[00:57:58] xe khách hàng của mình được hạn chỉ có
[00:58:00] tính cơ bản như này thôi cùng lắm là ông
[00:58:03] lọc xem là
[00:58:04] khách hàng dưới tỉnh Nam hay giới tính
[00:58:07] nữ nhiều hơn tại Khánh Như Thế ông ngoại
[00:58:11] chết chắc là chẳng có thêm gì cả hai ông
[00:58:14] muốn thống kê nữa tên là cái nhà ông ở
[00:58:16] tên long nhiều nhất à tên là nhiều nhất
[00:58:18] đúng không
[00:58:19] Nhưng đại khái méo hiểu gì đâu không ạ
[00:58:22] đó là mình có thể áp dụng một vài cái có
[00:58:25] thể thống kê được
[00:58:27] Mã số đơn theo mốc thời ra làm được này
[00:58:30] số sản phẩm bán chạy cũng làm được doanh
[00:58:33] thu nó bản chất là tổng tiền trong
[00:58:35] khoảng thời gian màu đỏ
[00:58:37] cũng trong theo một khoảng thời gian nào
[00:58:40] đó đúng không ạ
[00:58:41] một số thành viên cũng được này
[00:58:44] số thành viên đây mình không theo mốc
[00:58:47] thời gian được bởi vì các bạn thấy là
[00:58:49] không hề có không hề có cái cột là đăng
[00:58:53] ký vào thời gian nào Nếu các bạn muốn
[00:58:56] thêm thống kê theo thời gian các bạn
[00:58:58] phải thêm cột đấy Ở đấy ông ạ tiếp theo
[00:59:01] lượng truy cập lượng truy cập thì thực
[00:59:04] ra là như các bạn thấy là mình cũng
[00:59:06] không lưu lại cái điều đấy nóng lạnh
[00:59:08] Anh thường à Có nhiều bên
[00:59:12] nhiều bên thì ở chơi cơ chế là sẽ nhúng
[00:59:16] cài Google
[00:59:17] em có cái Google Pixel vậy nó sẽ nói
[00:59:22] chuyện check in mà nó sẽ kiểm tra luôn
[00:59:23] hộ các bạn với việc là có thực sự có bao
[00:59:26] nhiêu lượt truy cập phải dùng được thực
[00:59:29] sự và bị thực ra là có nhiều người spam
[00:59:31] hoặc cả dụng boot Vân hình ra dùng cũng
[00:59:34] dùng hằng thứ ba mà thẳng lớn như thế
[00:59:37] chắc nó sẽ ổn hơn để mà đánh giá thực sự
[00:59:40] có bao nhiêu lượt truy cập cũng được gọi
[00:59:43] dùng cũng được bởi vì à
[00:59:45] Ừ nó xỉa triệu Hỗ trợ mình phần thôi
[00:59:49] Mình vẫn có thể tự làm cái vụ đấy
[00:59:52] tiếp theo ở Khang Phạm tiềm năng nhưng
[00:59:55] vừa nãy các bạn để cập thì được à Dạ
[00:59:57] Mình sẽ nối khách hàng với hóa đơn sau
[01:00:00] đó lấy tổng tiền của hóa đơn để ra khách
[01:00:03] hàng Khách hàng từ năm đầu nhọn
[01:00:05] và hiển thị được vào số đơn đã đặt với
[01:00:08] Vân sản phẩm bây giờ sản phẩm kéo hãy mà
[01:00:12] thuộc thể loại không ạ
[01:00:14] Ừ ok Bây giờ mình sẽ không Không dậy các
[01:00:18] bạn với giao diện mình sẽ dạy có bạn về
[01:00:20] câu lệnh của axwell để làm từng cái cái
[01:00:22] này rồi các bạn tự tự thi cái giao diện
[01:00:25] để chuẩn bị ra nhá ông ạ
[01:00:28] ở giao diện thì có bạn làm được mà đúng
[01:00:30] ạ
[01:00:31] ở đầu tiên thì số đơn em mất thời gian
[01:00:34] thì ra đâu
[01:00:36] Mã số đơn các bạn mình sẽ dùng cao dồi
[01:00:38] không ạ select cao
[01:00:41] sao trả cũng được
[01:00:44] ạ sau đó from order ngày
[01:00:47] không ạ
[01:00:49] Ừ nếu mà chạy như này chỉ có bạn sẽ thấy
[01:00:52] ạ Nó sẽ là lấy gọi là theo thời gian
[01:00:56] kiểu chọn đôi lại tham tớ cảm chị à là
[01:01:01] không là lấy tất cả Không ạ Không không
[01:01:04] que thời gian gì cả Còn nếu các bạn muốn
[01:01:07] quay thời gian sẽ where
[01:01:10] bộ kịch mẹ đối ngoại nằm trong một
[01:01:14] khoảng thời gian nào đó ngoạn thường là
[01:01:16] mình sẽ thống kê thời gian theo
[01:01:19] ở Thượng Hải trong ngày hôm nay này
[01:01:22] Hôm nay này
[01:01:24] à à tuần này
[01:01:27] ở tháng này
[01:01:30] OOO và 5 này chứ ra năm nay năm nay
[01:01:41] anh Thắng tháng nay không gọi thì gọi
[01:01:41] năm nay lại Ok hoặc trong một khoảng
[01:01:46] thời gian nào đó một khoảng thời gian đó
[01:01:48] rõ
[01:01:50] thì để mà làm được tất cả những cái này
[01:01:52] thì các bạn sẽ phải rồi
[01:01:56] Ô thế Sao vẫn phải chỉ có bạn một tí giờ
[01:01:58] diện
[01:02:07] thì mình sẽ có input để mà chọn thời
[01:02:07] gian không ạ chọn thời gian này
[01:02:10] mình nếu mà mình để trai giống như nhập
[01:02:13] bếp như thế này
[01:02:17] à à
[01:02:17] Ừ
[01:02:22] Thì đó chỉ chọn trong một cái mốc thời
[01:02:22] gian như thế này không ạ Các bạn thế này
[01:02:26] được ra hơi say bởi các bạn sẽ phải chọn
[01:02:28] thời gian bắt đầu thời gian kết thúc
[01:02:30] Ừ thì nó hợp lý hơn nhưng mà còn nhưng
[01:02:34] mà mình đã nói thì ra là nó sẽ nói chú
[01:02:37] đây này Hôm nay để ngoại thì sẽ như nào
[01:02:40] còn đứa Các bạn chọn như này thì thường
[01:02:42] là nó sẽ là trọn trong một ngày hợp lý
[01:02:45] hơn mặc định có thể ngày hôm nay đầu
[01:02:48] tiên thì các bạn để và mặc định là hôm
[01:02:50] nay các bạn sẽ dùng hàm ạ Ở dùng pp balo
[01:02:54] nó cái chỗ
[01:02:56] nào vậy được không nhỉ
[01:03:00] anh không không không phải vậy nào ở
[01:03:04] anh tha mà chẳng Tôi không nhớ này lắm
[01:03:07] vợ gì Ờ đồ ngon đấy
[01:03:11] men đây ngồi tôi nhớ Ừ tao sẽ ngay
[01:03:26] ờ ờ thì đây sẽ lấy mặc định ngày hôm nay
[01:03:26] Ừ nhưng mà nếu mà các bạn muốn chọn
[01:03:28] trong tuần này Thực ra là nó sẽ có cái
[01:03:31] input Mình nhớ không lầm
[01:03:33] không không không thực nhớ lắm nhưng mà
[01:03:36] mình nhớ như có quy kỳ vậy anh có quyết
[01:03:39] của món ăn
[01:03:40] ở đây Đúng rồi switch
[01:03:42] à Còn như này chọn cho tuần này và tương
[01:03:46] tự mình có ăn thì phải
[01:03:51] Khi Chọn theo tháng
[01:03:51] anh không biết có yêu tôi chưa thử vụ đi
[01:03:54] cơ
[01:03:56] tình yêu không Có người yêu không có ăn
[01:03:59] đâu
[01:04:05] Anh nghe nè
[01:04:05] Ừ
[01:04:06] cái vừa rồi Tôi dùng cái này là hàm hàm
[01:04:11] để mà hiển thị cho thời gian nhé và theo
[01:04:14] quy tắc của nó vẫn là năm nghịch nhanh
[01:04:16] tháng rồi em ngày ngay dưới da
[01:04:20] ờ ờ không không có năm thì thử cả các
[01:04:23] bạn thể cho nhập trai giống như vừa rồi
[01:04:25] cũng được
[01:04:26] có người dụng không hoặc hoặc là hoặc là
[01:04:30] các bạn sẽ chọn như thế này
[01:04:33] cho một cái select-options tự tạo ra
[01:04:37] thôi và mình sẽ cho TP và for như thế
[01:04:42] này mình sẽ cho ra sử thơ ca tôi thường
[01:04:46] hay làm đấy tôi thường hay làm nó sẽ là
[01:04:48] theo thời gian mà tôi mới tạo ra cái
[01:04:51] trang web này đã sửa tôi tạo từ năm
[01:04:53] ngoái họ năm kia anh ạ
[01:04:56] từ lúc đầu nó cho 20 20 được ạ sau đó đi
[01:05:01] đến cái mốc thời gian hiện tại là được
[01:05:04] bằng lại một đùi gà này đại là đết tạ
[01:05:08] yêu thôi và lại y + + như này à
[01:05:23] ấn vào đây tôi sẽ in lại đi acro tôi lại
[01:05:23] đi ra
[01:05:24] thì đây sẽ hoàn toàn chọn được mốc thời
[01:05:27] gian từ 20 20 Cho đến thời gian hiện tại
[01:05:30] dùng hanbei để lấy được 5 hiện tạ
[01:05:33] Ừ cái này các bạn sẽ không phải sửa cốt
[01:05:36] Không Phải Hot cốt là theo kiểu là là
[01:05:39] ghi vào trong thẳng trong này là 2022
[01:05:42] bởi vì hoàn toàn sang năm thì các bạn
[01:05:44] phải vào đây sửa nó lành hay không ai bà
[01:05:46] không không ạ lấy thời gian hiện năm
[01:05:49] hiện đại mà ngoạn thì các bạn dùng hàng
[01:05:51] này còn đây là cái lúc đầu các bạn Thể
[01:05:55] khá nhiều trang họ sẽ gán luôn lúc đầu
[01:05:57] năm đầu tiên sẽ năm bao nhiêu đúng không
[01:06:00] ạ năm đầu tiên này như mình đã nói thì
[01:06:03] các bạn nên áp dụng từ chính cái năm ở
[01:06:05] trang web này mới có còn không thì nhiều
[01:06:08] trang đấy giống như bạn bị giống như hệ
[01:06:10] anh thấy thầy Hiệu phó đề xuất Đó là
[01:06:14] 1970 ạ
[01:06:23] 1970 nhớ nó còn móc gì chứ
[01:06:23] à mà và Thực ra thực là trải nghiệm thế
[01:06:27] này thời gian nó không tốt không tốt bởi
[01:06:29] vì là các bạn thấy là thường là nó sẽ
[01:06:31] chọn những năm gần gần hơn là những 5
[01:06:35] kiểu từ xa như hay không ạ thì bài toán
[01:06:39] ở đây nên ngược lại một tí họ sẽ lấy từ
[01:06:41] như thế này xong rồi ngược lại như này
[01:06:46] a197 không ạ Mà nó chưa -
[01:06:51] trải nghiệm và sẽ tốt hơn đó như này về
[01:06:55] thường là các bạn sẽ quan tâm thống kê
[01:06:57] thời gian là trong những năm gần đây chứ
[01:07:00] không phải từ năm trong quá khứ Đông ạ
[01:07:04] ừ ừ
[01:07:06] à à
[01:07:08] ở
[01:07:09] đây ok rồi lại để hiển thị ra cái để mà
[01:07:13] chọn sau đó các bạn chị còn sắp mít nào
[01:07:14] lên mình sẽ được vào đây được bạn sẽ ghi
[01:07:19] ở trong cái clip tật ở sẽ ra được mà nó
[01:07:23] sẽ ra được kết quả thôi
[01:07:25] vì vậy số lên 21 thời gian ok rồi thế
[01:07:28] cho số sản phẩm bán chạy và không bán
[01:07:30] chạy cái Từ khái niệm không bán chạy thì
[01:07:32] thì ra nói chuyện ngược lại bán chạy
[01:07:35] thôi ông ạ thì đầu tiên là mình sẽ sắp
[01:07:37] xếp cái bán chạy không bán chạy thông
[01:07:40] qua việc là
[01:07:42] A là
[01:07:44] ô ô therefore này mình sẽ có cột cột à
[01:07:48] mình có quạt et để biết được là sản phẩm
[01:07:51] là bán chạy không bán chạy đúng không ạ
[01:07:53] Ừ nhưng mà ở đây thật a Thực ra nó sẽ
[01:07:56] như thế này là sự ở đây tôi có 8 sản
[01:07:58] phẩm ở đâu có 6 sản phẩm lấy thực ra chỉ
[01:08:03] có một vài sản phẩm được bán thôi đúng ạ
[01:08:05] hiện nhưng mà mình gỡ này phải hiển thị
[01:08:07] ra đủ 6 sản phẩm đây và kèm theo ở bên
[01:08:10] cạnh
[01:08:10] anh có thể hiển thị mã sản phẩm tên sản
[01:08:13] phẩm của hình định ra bên cạnh nó sẽ là
[01:08:15] số lượng sản phẩm đã bán sau đó thì ông
[01:08:18] thường hay sắp xếp là là sắp xếp theo
[01:08:22] cái cột số lượng đã bán để để lấy để xem
[01:08:25] được sản phẩm bán chạy nhất và sản phẩm
[01:08:27] nào bán chạy sau đó ngoại ý
[01:08:32] à à
[01:08:34] em
[01:08:35] viết lệnh để tạo bảng để mà cái sau các
[01:08:38] bạn sửa Cốt và gửi code đấy để mà người
[01:08:41] khác chạy được luôn Nó sẽ gọi ở file
[01:08:43] migration chứ không nên dùng nick nick ở
[01:08:47] nhà Thưa click cái kiểu như này xong các
[01:08:50] bạn cũng phải ấn vào bên cốt để mà phe
[01:08:53] scourge gửi kia nhưng mà ý mình cái
[01:08:56] quyết cốt đấy em cái cốt thẳng bằng ngôn
[01:08:58] ngữ lập trình chứ không không thừa bằng
[01:09:00] axwell nữa
[01:09:01] Ừ cái này chắc ở bên liddell mình về sao
[01:09:04] mình để cập các bạn lại bạn dễ hình dung
[01:09:05] hơn về mai Nathan Lee
[01:09:08] Ừ
[01:09:09] ok Nói chung là bây giờ có 6 sản phẩm
[01:09:11] không ạ Mình sẽ cần ở đây mình sẽ còn
[01:09:14] nặng nợ gì mình cần thống kê
[01:09:16] thống kê là đầu tiên mình cần lấy mình
[01:09:20] hiện thì toàn bộ sản phẩm ra trước đã
[01:09:22] mình cậu select này ai đi này
[01:09:26] khi nêm này
[01:09:28] for roblox
[01:09:32] anh như này thôi mà lấy tất cả thông tin
[01:09:34] của ID và nêm và sản phẩm không ạ tiếp
[01:09:38] theo nữa đó là mình sẽ cân bà lấy số
[01:09:41] lượng của số lượng và thống kê số lượng
[01:09:44] không ạ một là các bạn dùng à Seung Ri
[01:09:48] ta sẽ kéo saly luôn lồng salad ở ngay
[01:09:52] đây và lồng xe lách cũng được hay là các
[01:09:55] bạn ạ
[01:09:56] thứ hai các bạn dùng cho và
[01:09:59] gà chọi ở đây ra ở đây rồi ta mình sẽ
[01:10:03] nếu mà các bạn dùng roi và thực à mạnh
[01:10:06] mẽ QR các bạn nên dùng cho vì nó tối ưu
[01:10:09] truy vấn hơn nó nhẹ hơn do việc có bạn
[01:10:12] dùng Safari I
[01:10:13] a nhớ các bạn dùng cho ở đây Các bạn nên
[01:10:16] dùng led trôi chứ không phải nên dùng in
[01:10:18] Android vì tay mình sẽ thử chị bạn Tại
[01:10:21] sao đầu tiên mình dùng in cho trước đi
[01:10:24] baldr force này on orders đắt chấm ID
[01:10:30] bằng boodog chở mai đi em ạ
[01:10:34] Ừ nếu bạn chạy như này bạn sẽ thấy là nó
[01:10:37] sẽ hiển thị ra mỗi hai sản phẩm thôi mà
[01:10:39] còn lặp lại còn bị lặp lại
[01:10:42] Ừ đúng ạ
[01:10:44] Mình lỡ ân ái
[01:10:46] à à
[01:10:47] em mình hơi khó chịu đấy Cái cái câu
[01:10:50] truy vấn này nó không để hai địa chị
[01:10:52] thành an của phim mấy ông ấn quay lại
[01:10:56] lắm chỉ muốn khôi phục lại khâu cũ được
[01:10:58] ra nói mất Hôm sau mình mình kỹ lại nhé
[01:11:02] Thì mình đi lại
[01:11:04] Có
[01:11:19] Ừ thì à
[01:11:19] ạ Bây giờ mình sẽ dùng read your
[01:11:22] order đó
[01:11:24] see more on the fourth chấm proxy đi
[01:11:27] bằng golf
[01:11:30] Xin chào Mai đi nha Chẳng ạ
[01:11:33] Ừ nếu bạn chạy như thế này thì bạn sẽ
[01:11:35] thấy là nó sẽ hiển thị tất cả sản phẩm ở
[01:11:38] đây
[01:11:39] Ừ nhưng mà sản phẩm 7 và 8 vẫn đang bị
[01:11:42] lặp lại vì nó vẫn ông dùng do mà nó là
[01:11:45] tại hai phát Thế là các bạn thể dùng
[01:11:47] Goodbye để mà nhóm máu lại để tránh việc
[01:11:50] lặp lại như thế này sẽ giúp anh thường
[01:11:53] mình sẽ giúp anh theo ID của sản phẩm
[01:11:56] của tiếng nói duy nhất sẽ không lặp lại
[01:11:58] nó chạy này
[01:12:01] ở đó sẽ không lặp lại nữa và bây giờ nếu
[01:12:04] các bạn chỉnh các bạn muốn thống kê là
[01:12:07] các bạn sẽ tính tổng của cái con Titi đã
[01:12:11] để biết được đã bán bao nhiêu
[01:12:13] ở đài mình sẽ ra
[01:12:20] anh
[01:12:20] ở đây là xăm con Ti Ti
[01:12:24] bài hát
[01:12:27] ờ ờ
[01:12:28] quantity sails Hạ
[01:12:31] à à
[01:12:34] ô tội chẳng biết câu này nên đặt như nào
[01:12:37] đại khá như thế đã bán đúng không
[01:12:45] Ừ có gì xảy ra như này các bạn thể cho
[01:12:45] mặc định cái này nếu mà ít luôn có cái
[01:12:49] hàm lại ít luôn à
[01:13:02] ca nhạc Nhớ có hạt mít luôn mà Em hãy
[01:13:02] tsmu nhỉ It's known
[01:13:23] Ừ
[01:13:23] đúng rồi ạ Em phải để làm sao tôi xin
[01:13:27] lỗi tôi xuống
[01:13:29] khi đó nó sẽ ra không nhưng mà cái này
[01:13:33] nó sẽ bị cái đó là
[01:13:41] Ừ thứ nhất là cái này về cơ bản mới Ông
[01:13:41] thấy ổn rồi theo kiểu là ok Nó hiển thị
[01:13:44] ra được nói đi là được số xăng còn đã
[01:13:47] bán theo từng sản phẩm đó ông ạ
[01:13:49] Ừ nhưng mà cái điều tôi muốn nói đấy Đó
[01:13:53] là cái này thật ra không phải số sản
[01:13:56] phẩm đã bán và số dân phẩm đã được đặt
[01:13:57] con số sản phẩm đã bán ra mình sẽ phải
[01:14:00] nối mạng oder nữa mình lại phải lép do
[01:14:04] mạng order nữa đây lấy được là và mình
[01:14:07] sẽ queo status của order là là bằng một
[01:14:13] ở đâu = = Mấy nhà có đến mình quý ông
[01:14:16] mùng mấy nhỉ Không còn mới đặt một là
[01:14:18] đặt được đặt rồi thì vậy đấy ra xử như
[01:14:21] thế thì sẽ ghép do tiếp này order
[01:14:36] là con ô tô chấm ID bằng on the lorax
[01:14:36] chấm ordered ạ
[01:14:39] sau đó thì mình sẽ que
[01:14:42] order chấm Sắp chết bằng một phát sướng
[01:14:46] ngay
[01:14:47] ở trận này
[01:14:59] ai ngờ con máy kéo mình chết Đợi đến
[01:14:59] được tắt đi mở lại sẽ
[01:15:30] à à
[01:15:30] anh mãi axetilen ID Ok trả lại
[01:15:43] ở cột ID nó bị lặp lại rồi vì a trong
[01:15:43] cho Mảo đỡ có một ai đi mình sẽ ghi rõ
[01:15:46] là cô đắp chấm Mai đi này và qua đắp
[01:15:49] chấm nên cho chắc
[01:15:55] vì
[01:15:55] vậy trong trường hợp này mấy ông thấy nó
[01:15:57] bị sai tại sao bị sai nếu béo để ý kĩ
[01:16:01] Tuy ở mình có dùng nét vôi để mà việc là
[01:16:04] mình không bị mình lép trôi thì tức à
[01:16:06] Cái phốt này nó không phụ thuộc hoàn
[01:16:09] toàn ở mordor Đông ạ nhưng mà các bạn
[01:16:12] thấy là bởi vì mình queo status cho đời
[01:16:16] sau tước bằng bằng một ngân hàng ra là
[01:16:18] là bắt buộc phải có oder thì mới mới
[01:16:22] chạy đúng ạ Ở đây các bạn có thể thêm
[01:16:25] một cái mẹo nữa đó là các bạn sẽ to
[01:16:27] order
[01:16:33] anh ở đây ở đây tôi sẽ tặng xóa cái này
[01:16:33] đi à
[01:16:42] Ừ để cho mày ông dễ hiểu hơn tôi sẽ ạ
[01:16:42] ở tạm copy cái này xa để xa bỏ lúc bay
[01:16:48] đi để mày ông dễ hình dung hơn toilet
[01:16:51] cho ngay mình sẽ hình dung được hơn đây
[01:16:54] kệ ID của cô đắt ở đây nhá
[01:16:59] Ê mấy thằng này được đẩy lên đầu những
[01:17:01] kệ không có tâm đi bây sản phẩm iPhone
[01:17:03] 12 này toàn bộ những thông tin bên này
[01:17:06] để là nôn hết này bởi vì rõ là nó làm gì
[01:17:09] có đơn đâu đó ngoại thì méo có thể chơi
[01:17:12] trò lách như thế này đó là Order chấm sa
[01:17:15] tế ớt itneun cũng được hoặc nhỏ thường
[01:17:19] là để ở chắc cú hơn thì sẽ là Order cây
[01:17:23] chính tôi thường ấy bảo chính cái cái
[01:17:25] cái để mà dùng cho ấy nó là nun gà cho
[01:17:29] củ nhất sẽ thể order cho median ol họ
[01:17:33] order code sấm ordered luôn cũng được
[01:17:37] Sữa mẹ là một trong hai này như thế này
[01:17:39] thì nó sẽ ra được
[01:17:41] Ồ thông tin nha Đó Ngoại ok Bây giờ mình
[01:17:45] dùng roi để mà thống kê nhà mình có thể
[01:17:49] ghi lại câu lệnh này bằng một cách khác
[01:17:51] Ừ tôi thường ấy thích cách khác này cho
[01:17:54] dù Thực ra nó bị
[01:17:57] vì nó có thể nó có thể dễ hiểu hơn có
[01:18:00] thể để đối với tôi nó không biết mấy ông
[01:18:03] đến nhưng mà nhưng mà kể tôi không quên
[01:18:06] Mấy ông thường khá vô cái đấy vì tôi đã
[01:18:08] nói mày quen nó tối bên your chứ phải
[01:18:11] Safari Tôi sẽ thử viết bằng sắc với
[01:18:13] người ông sẽ thấy nó sẽ dễ hơn so với
[01:18:15] việc làm dài dòng ngay đây tôi sẽ dùng
[01:18:19] Shayk vẫn là sẽ lách thôi xăm nóng ạ con
[01:18:23] đi thi nhưng thương
[01:18:24] quá đi tí này lấy từ bảng nào đây
[01:18:29] khi enter a nhìn rất rõ này
[01:18:43] à À ý anh ý anh là đoạn en ở đâu
[01:18:43] em em em em lỡ xóa sư về câu chưa Vẫn
[01:18:46] chưa
[01:18:47] anh đấy em ạ
[01:18:50] Anh
[01:18:51] vừa gọi E ở đâu nhỉ
[01:19:06] a
[01:19:06] form order form này
[01:19:10] nhà mình có thể quay ngay đây này order
[01:19:13] for đắp chấm phố Decade Bằng chính cái
[01:19:18] code Mẹ gửi đến này chấm ID để lấy được
[01:19:21] cái con Ti Ti của cái oder bộ lắp và cái
[01:19:24] này không còn newbi nữa vì về cơ bản thì
[01:19:27] cái này đến theo từng sản phẩm nếu có
[01:19:30] rồi thử chạy thử trong mấy ông xe luôn
[01:19:34] chú chó đứng như cái này nó bị quá dài
[01:19:37] nên thành ra là
[01:19:39] Ừ chắc á con sâu à Như có con xô Vậy để
[01:19:43] xem nhẹ
[01:19:53] cho mình nhớ ở thoại có một cái lưu lại
[01:19:53] câu truy vấn ở đâu đấy
[01:20:25] à à
[01:20:25] à à
[01:20:27] à à
[01:20:42] á nhon Mình mình nhớ có con sâu bao
[01:20:42] nhiêu Mình ở ít dùng ví dụ
[01:20:45] Ừ ông anh bảo ở lạc trôi đoạn này có
[01:20:48] thêm en ở đâu nhỉ
[01:20:55] à Mình mình dùng cái tôm khác thì nó
[01:20:55] thường anh Hiển thị cũng con sông ai ở
[01:20:57] vừa ấy nó hiển thị ra luôn Đấy nó không
[01:20:59] kiểu check bạn như này thì mình đi cái
[01:21:01] đấy hôn
[01:21:04] chú ý anh là em ở ngay bạn này đúng
[01:21:06] không
[01:21:11] em thấy quen ở đây mình sẽ ngay đây à
[01:21:11] anh đi làm à
[01:21:13] ừ ừ
[01:21:24] Ừ cái để tạo đây đã nhé Đợi Anh ấy trả
[01:21:24] lời à
[01:21:30] anh Kể tóm tắt lại đi này
[01:21:30] Ê mấy ông thấy à thực ra cái này nó bị
[01:21:33] dài đoạn này nhìn thấy áp ở đây là quan
[01:21:36] đi
[01:21:37] sale không ạ Ừ nhưng mà tương tự giống
[01:21:41] như nãy nói là thật là mình sẽ phải cho
[01:21:43] anh nữa đâu ạ trong trường hợp này mình
[01:21:45] thể inner cho luôn vì bản chất là mình
[01:21:48] cần đến Thực ra cái đoạn này nó không
[01:21:51] ảnh cái này cho này không ảnh hưởng thêm
[01:21:53] câu lắp các bạn thấy ở đây vẫn phải luôn
[01:21:55] thoải mái vẫn thị force là bình thường
[01:21:57] em vẫn dùng cho rồi enjoyed Được on
[01:22:02] order này chân ai đi bằng order doc.org
[01:22:06] đi này và mình hoàn toàn quay ở đây luôn
[01:22:09] được Em
[01:22:11] Order chấm status bằng một nhà ở đâu này
[01:22:18] ở đó Nó xảy ra các bạn thấy ạ
[01:22:22] Tôi thích Hồi đấy tôi bị nghiện Seung Gi
[01:22:25] ờ
[01:22:32] Ê hồi nãy tự nhiện Sapa đi vì nó kiểu
[01:22:32] kiểu nó viết nó sẽ đỡ phải natwara cho
[01:22:36] một đống như thế này nhà Đương nhiên chị
[01:22:38] nhất cho như này nó lại nhẹ hơn đấy nhá
[01:22:40] nó nhẹ và xử lý nhanh hơn do cái này mấy
[01:22:44] cái này nó duyệt từng cứ mỗi lần với một
[01:22:46] thành phố đắt nó lại gọi lại đến hàng
[01:22:49] oder paulus của và order để để lấy thông
[01:22:53] tin có bao nhiêu cô đắp nó sẽ chạy bẫy
[01:22:56] như vòng lập cái này em bé không thấy nó
[01:22:58] nặng như thế nào con khi mà Các bạn góp
[01:23:00] hết lại rồi Các bạn mình mới lấy nó sẽ
[01:23:04] bị nó sẽ nhẹ hơn rất nhiều nhà nên là
[01:23:07] tôi khi mà làm thống kê được cả tôi
[01:23:09] không khuyên mấy ông làm như hay là sự
[01:23:11] có bao nhiêu sản phẩm nó bấy nhiêu lần
[01:23:13] cái truy vấn như này thì mấy ông sẽ thấy
[01:23:15] nó ạ giữa nặng không ạ Đây à
[01:23:19] ở nhà Tôi đang đi tôi đang ghi cho mấy
[01:23:22] ông ấy mấy ông thấy nó cũng có 2 cách để
[01:23:25] ghi thôi Cái này tương tự ở mấy ông có
[01:23:28] thể cho ít luôn ở đây được đội đây là
[01:23:31] Thêm số 0 vào đây nữa thì nó sẽ không
[01:23:34] thôi
[01:23:40] xin lỗi à
[01:23:40] xin lỗi này không tắt đi đấy nek to
[01:23:43] dismiss không được mà
[01:24:04] thì tại sao để đổi nha Xem lại nha luôn
[01:24:04] đấy con tefal
[01:24:14] Ừ anh âm nhạc phải ít luôn cho này xin
[01:24:14] lỗi xin lỗi xin lỗi nó sai cái này vẫn
[01:24:17] đóng mở ngoặc này nó ngoác này vậy không
[01:24:21] này
[01:24:23] Em đâu rồi
[01:24:25] ờ ờ
[01:24:33] ô tô rồi đó thì đây là vừa rồi mình làm
[01:24:33] mình chỉ các bạn thống kê số số sản phẩm
[01:24:36] bán được mà đỡ nhiên các bạn hoàn toàn
[01:24:39] có thể là cả hai cách này các bạn hoàn
[01:24:42] toàn thể order bay theo cái cột này để
[01:24:45] lấy được order
[01:24:47] bye này và PC thì sẽ là lấy lấy ra được
[01:24:55] sản phẩm bán chạy nhất nhưng ngoài ra
[01:24:57] còn thêm cái hay nữa thôi chị mấy ông đó
[01:24:59] là mấy ông ngoài việc là ok sản phẩm bán
[01:25:02] chạy nhất này thì mấy ông sẽ nghĩ là ok
[01:25:04] ngược lại đúng không ạ sẵn bà sẽ là ra
[01:25:07] sản phẩm không bán chạy không ạ Không
[01:25:09] cái này thì ra đó vẫn chưa hẳn đã đúng
[01:25:11] lắm để tôi gợi ý thêm mì ông đó là mấy
[01:25:15] ông phải sắp xếp theo những sản phẩm đã
[01:25:18] nhập là sử đây rõ là B sản phẩm nhập lâu
[01:25:21] hơn sản phẩm này không ạ thì về cơ bản
[01:25:24] thì treo thời gian thì rõ ràng là thằng
[01:25:26] ngày mới hàng không bán chạy nhất chứ
[01:25:28] thế này đúng ạ mày không méo gì tôi
[01:25:30] không ạ Đấy thì tôi phải cho phải lên
[01:25:33] trước tới 8 chỉ mình sắp xếp theo cột
[01:25:35] này và khi sắp xếp theo của Wendy sale
[01:25:38] rồi Nếu mà khi cột mày bằng nhau thì
[01:25:40] mình sẽ Vậy sắp sẽ theo cả May mà kể mãi
[01:25:44] tự động tăng lên thành ra là kiểu cái
[01:25:46] xanh nằm mà nhập Nó kiểu cổ nó bé hơn
[01:25:49] rất cám chị nó mới á nó lâu hơn so với
[01:25:52] thằng này xài sẽ mới hơn không ạ Đấy
[01:25:55] mình sẽ phải order Bike theo hai cụt thì
[01:25:59] mình sẽ ra ai đi nữa cô đắp
[01:26:02] chả mai đi vào đây sẽ là 2C thời gian
[01:26:07] chị ạ
[01:26:08] Ừ Đấy Thế này mới gọi là không Bạn trạng
[01:26:12] nhất
[01:26:13] Ừ nó cũng vậy không ạ ạ
[01:26:16] a tiếp theo doanh thu thì mất thời gian
[01:26:18] để chúng ta còn dễ hơn cái cái vừa nãy
[01:26:21] nói chỉ đơn giản là tính tổng đúng ạ xem
[01:26:25] một mốc thời gian nào đó
[01:26:27] cho doanh thu được không là Thu về chứ
[01:26:30] không phải doanh số gì vậy lỗ lãi đúng
[01:26:33] không
[01:26:39] số trường hợp nó là ID thay vì để tự
[01:26:39] động tăng như thế này thì thì mình nên
[01:26:41] thêm cột nó ngọn mình thêm cột à khi mà
[01:26:44] kiểu nhập vào thì mình sẽ thêm cột cột ở
[01:26:48] với tất cả ạ Nó cột khi mà mình
[01:26:51] in rất nó ra
[01:26:53] Ừ nhưng mà ra đây mày không dậy được các
[01:26:57] bạn đến cái bước là là kiểu nhập kho hay
[01:27:01] là tồn kho gì cả chị nhập mức tương đối
[01:27:04] thôi Đây là cái này thì ra là nó đủ để
[01:27:07] mà thống kê một tí rồi
[01:27:09] anh em chưa dậy các bạn mà yêu ai đi
[01:27:12] không đi thường cho bên liên quan đến
[01:27:16] khát ta bây hơn là khi tách bây ra hay
[01:27:21] nhiều bây khác nhau thì cái số tự động
[01:27:24] Đăng nó có thể trùng Giang đã ra tay kia
[01:27:27] đây mình sẽ phân biệt nhau qua một cái
[01:27:30] mã nó không bị chung nhưng mà không phải
[01:27:32] tự động thanh nữa ừ ừ
[01:27:37] khi doanh thu theo mốc thời gian này
[01:27:37] mình có đề cập thì sẽ là
[01:27:41] ở
[01:27:41] bên order đóng mình sẽ có
[01:27:44] thì mình sẽ chỉ cần xăm nó thôi là lấy
[01:27:47] được thôi ông ạ khá dễ
[01:27:51] thì mình sẽ là select some
[01:27:54] Total Price
[01:27:56] for order đúng ạ
[01:27:59] À thì ra thế này ra rồi còn theo mốc
[01:28:02] thời gian nhưng mình vừa nãy nói với thì
[01:28:03] ạ Các bạn lấy thời gian từ đăng nhập lên
[01:28:06] mình sẽ mình sẽ que không ạ Mình sẽ que
[01:28:09] theo
[01:28:12] a waiter cột ở
[01:28:14] ở quế thật đúng rồi con thêm wak cả sau
[01:28:17] tất bằng bằng mụn nữa
[01:28:19] quê status bằng 10 ạ
[01:28:24] Mình chỉ thống kê những đơn đã đặt đúng
[01:28:26] không ạ những đơn ở đâu những đơn đã
[01:28:29] duyệt chứ còn những đơn đã đạt thì nó
[01:28:31] Đạt láo thì kệ thôi ông ạ
[01:28:33] một số thành viên thì thực ra nó là
[01:28:36] select cao customer thôi ông ạ Cái này
[01:28:40] phá dễ này
[01:28:41] số lượng truy cập từ những mình nói là
[01:28:43] không không làm được trên lưu lại khách
[01:28:46] hàng tiềm năng này Thực ra là mình sẽ
[01:28:47] roi bảng nóng ạ Cái đoạn này nhưng mình
[01:28:51] nói được cao dùng subcribe hỏi cho gọn
[01:28:53] được mình sẽ là sếp
[01:28:55] Ừ mình vẫn là ai đi này
[01:28:58] À thì ra là không cần hình thị cơ sở mới
[01:29:01] đi nữa mà mình hiển thị cái tên rồi trả
[01:29:03] cũng được form cơ sở mờ trước đi cho tỷ
[01:29:08] lệ toàn bộ tên ông ạ sau đó thì mình sẽ
[01:29:10] ghép do nếu mình nói phải dùng lap doi
[01:29:14] vì chưa chắc là khách khách đăng ký vui
[01:29:18] như chưa đặt sản phẩm nào thì không nhìn
[01:29:20] thị ra rồi nó không hay mình cứ kệ đi
[01:29:22] tất cả khách hàng nhưng mà mình sẽ hiển
[01:29:25] thị ra khách đã ban đã đặt những nào
[01:29:27] không ạ
[01:29:28] I love all audio on all their personal
[01:29:34] đi
[01:29:36] customer My em ạ
[01:29:39] ạ sau đó thì thế ra các bạn có thể hiển
[01:29:43] thị ra ở đây hoặc không tùy
[01:29:45] thị ra đây là xăm Total Price này
[01:29:49] hát
[01:29:51] chụp em ạ
[01:29:53] là đã thanh toán bao nhiêu này
[01:30:05] ấn vào đây mình sẽ que order
[01:30:05] gì chấm status bằng à
[01:30:08] ở vòng 1 to order
[01:30:12] 3.2
[01:30:21] a Custom ID họ gái đi Tui It's known
[01:30:21] chồng như vừa nãy anh nói bởi vì trong
[01:30:23] trường hợp mà order có này không không
[01:30:24] không có là mình sẽ order
[01:30:31] A Goodbye
[01:30:31] customer.io sắc
[01:30:34] vì nếu mà không không rút bay đầy mình
[01:30:38] thử không lúc bay cho các bạn xem nhé
[01:30:49] ở bảng xếp hạng lỗi như này luôn đấy thứ
[01:30:49] ra cái tắt cái này tắc kè đi được
[01:30:51] em có thể vào cái này để tắt đi
[01:30:54] em làm gì là
[01:30:56] bỏ có nền xe lách những cái cột không
[01:30:59] nằm trong Goodbye vấn đề ra đi được
[01:31:06] Ừ nhưng mà khi tắt đi nó sẽ bị hiển thị
[01:31:06] sai thông tin chắc chắn nó thế bởi vì nó
[01:31:09] sẽ hiển thị ra tổng tiền của tất cả các
[01:31:12] đơn thôi chứ không phải theo từng người
[01:31:14] người dùng nữa
[01:31:22] anh ở đây Ở đây đang có mỗi một người có
[01:31:22] sờ
[01:31:23] Em xem mình đúng không
[01:31:25] tự hào đồng hồ có mỗi một khách hàng đã
[01:31:27] xử lý sớm thêm một khách hàng nữa thì
[01:31:29] chắc chắn nó chưa đạt đơn ông ạ à
[01:31:37] à
[01:31:37] Ừ chắc nghe được rồi
[01:31:46] à à
[01:31:46] cho anh em nhé
[01:32:02] à à
[01:32:02] anh có hai bạn
[01:32:10] Ừ thì các bạn có thể thêm cái order bay
[01:32:10] ở đây ô ô their bay chim cánh cụt
[01:32:14] totopaz này và DC sẽ giảm dần đúng không
[01:32:20] thế này để lấy được khách hàng tiềm năng
[01:32:24] Mã số đơn cách đã trả nó cũng tương tự
[01:32:27] mình có thể cao đây cao có đồ chấm mai
[01:32:33] đi học customer ID cũng được Tại sao
[01:32:36] không phải là cao sao Bởi vì nếu cao sao
[01:32:39] nó sẽ khác để tôi sẽ cho hai ví dụ cho
[01:32:41] mấy ông
[01:32:43] có xào nó sẽ đến không theo việc còn
[01:32:46] luôn hay không Hãy nhìn nay chẳng hạn
[01:32:49] đi đái rõ ràng và nếu K sao nó sẽ luôn
[01:32:52] là một bởi vì có một bản ghi em à ạ Còn
[01:32:55] đây ở sẽ kiểm tra xem mà có đơn có đơn
[01:32:57] thì nó mới đến đấy các bạn sẽ phải cao
[01:33:01] đúng cột thì nó chuẩn hơn
[01:33:09] ở đó đó là khách hàng tiềm năng có sản
[01:33:09] phẩm theo hãy chỉ ra các bạn sẽ cũng
[01:33:12] tương tự là các bạn sẽ
[01:33:14] chị sẽ trâu chọi với cái bảng My fossil
[01:33:18] là cao là lấy được thôi đó đó về thống
[01:33:22] kê
[01:33:23] cho bộ mai giải phết nhỉ Tôi bắt đầu khả
[01:33:26] năng dần rồi
[01:33:27] ờ ờ
[01:33:29] thứ hai để buổi sau đi buổi sau mình sẽ
[01:33:31] dạy các bạn về à bình luận nhỉ
[01:33:34] em buổi sau mình dậy các bạn Nốt rồi cái
[01:33:36] bình luận đề ông ạ
[01:33:39] ừ ừ
[01:33:44] các bạn còn đầu tiên thì các bạn có tham
[01:33:44] ăn gì Biến thống kê thì ông ạ Còn buổi
[01:33:46] sau tôi sẽ dậy mấy ông nợ tại sao buổi
[01:33:49] sau đi các bạn ông về dùng ra Switch để
[01:33:54] mà bình luận rồi hiển thị luôn cả bình
[01:33:56] luận ngay ngay lập tức rồi đấy chứ không
[01:33:58] phải là phải loạn lại trang mới hiển thị
[01:34:01] ra được bình luận
[01:34:02] Ừ nếu như mình vẫn sẽ đẩy cái bình luận
[01:34:04] lên bằng bằng form đẩy lên
[01:34:08] a di tinh tình đánh giá đúng không Ok
[01:34:11] mình sẽ nốt lại buổi sao cả
[01:34:15] tất cả dưới tinh nó cả đánh giá và cả
[01:34:18] bình luận nhé
[01:34:20] à à
[01:34:21] ở đài mình lại
[01:34:33] e
[01:34:33] + đánh giá sao chẳng hạn rating không ạ
[01:34:37] ạ
[01:34:44] ờ ờ
[01:34:44] Ừ ừ đúng rồi mình xin phép chia sẻ nốt
[01:34:47] cài hai cái Soft này cho nhanh này cái
[01:34:50] mình thấy khá hay chia sẻ các bạn ký để
[01:34:54] các bạn thấy nó ảo như thế nào
[01:34:56] Em gọi thử xem nhé
[01:35:11] cài đặt Bluetooth
[01:35:11] đ.to
[01:35:17] anh
[01:35:17] ấy giờ đây là bộ đội
[01:35:21] a
[01:35:21] [âm nhạc]
[01:35:23] Christmas special that Mr first name
[01:35:27] against Some people wait
[01:35:30] here their work with this is one of
[01:35:34] protection and many more King's raid
[01:35:36] Mode this on the finest Atletico Unicode
[01:35:39] with lots of people current and
[01:35:40] beautiful bays in its dịch Center is
[01:35:44] accompanied for android with Unicode can
[01:35:47] afford to Stand By Me If you're nothing
[01:35:50] compares
[01:35:51] butsakorn tour live in yourself with
[01:35:54] compassion street gonna start you
[01:35:57] received from users the content no
[01:35:59] nesticle missile Places which directly
[01:36:02] to you can use the Beautiful Woman is
[01:36:04] made you can choose any file lights
[01:36:06] Galaxy r d r kaycee allkpop Awards and
[01:36:10] consistent and stick with enough I
[01:36:18] Ê mấy ông thấy vừa rồi làm một cái của
[01:36:18] chính giờ đây là bộ cài đặt tới đâu Cái
[01:36:20] này đây Horse em đi rồi lao động sẽ này
[01:36:22] thì hồi nữa vì bí của
[01:36:26] chỉ có một thứ rất khó chịu không ạ
[01:36:28] kể cái này là kiểu đó rủ hai cái giống
[01:36:32] hệt nhau Nhưng mà thực ra là không không
[01:36:34] không được mail nhưng cái này không phải
[01:36:36] là mỗi ra Swift mà nó ngôn ngữ chung tất
[01:36:39] cả ngôn ngữ khác đó là gì đó là với cái
[01:36:42] kiểu unicas như này nhìn trông có vẻ
[01:36:44] giống hệt nhau
[01:36:45] nhưng mà thật ra Nó là một cái thì nó là
[01:36:50] đăng ký tự luôn trong bảng chữ cái có
[01:36:52] thật thì nó lại em gấu một cái lại E rồi
[01:36:57] thêm dấu thật thành và x2 ra nói mấy
[01:37:00] Latinh không ạ Nếu mà giận Cắt nghĩa nó
[01:37:03] ra lại xảy ra như này hoặc được
[01:37:06] kim.me là sẽ lấy cái lúc đấy không như
[01:37:08] lại không Cái Hàn để mà thường người ta
[01:37:11] sẽ dùng tại Hà mẹ con bớt nó ra
[01:37:13] đăng ký để mở ra thành hết chữ cái thật
[01:37:18] thì những cái chữ mà được ghét bưởi ghép
[01:37:22] bởi ký tự nó sẽ tách ra như này à ở đấy
[01:37:25] có phải mỗi ra Speed Âu hỗ trợ chữa tôi
[01:37:28] bị dính ở bên ra rồi và Chắc cái bệnh
[01:37:30] dính
[01:37:36] Chúng tôi khuyến mấy ông như thế này tôi
[01:37:36] từng bị dính lấy tổ mò mất thời gian và
[01:37:38] nhiều người từng bị mòn em mất thời gian
[01:37:39] đấy mà thêm một cái nữa nhé một cái nữa
[01:37:43] cũng cũng cũng vãi chưởng lắm này
[01:37:53] I just like me a story on a different
[01:37:53] World
[01:37:55] a.to menu help us
[01:37:59] a Death Metal I am I forget about to
[01:38:04] make you have occurred in The Winner Is
[01:38:06] Zero whit Pikachu static attention and
[01:38:09] strategies Google When is the easy way
[01:38:13] It Hurts you tell me don't lie to the
[01:38:17] punch and the late because Death is your
[01:38:21] expected confused with either Trish
[01:38:24] summerville Achilles heel Balm Use this
[01:38:28] feature that enables you to unicard hay
[01:38:32] Wedding present simple Touch with
[01:38:33] glowlight now You can see Thái lại
[01:38:35] Nautilus esata heritable you Dragon Hill
[01:38:40] and execute and the world and articles
[01:38:44] about their papers on ostrich problem
[01:38:48] World
[01:38:50] Ừ
[01:38:50] cái này thì nếu mà mấy bạn để vừa rồi
[01:38:53] nữa thì còn bị thêm một quả đó là cho
[01:38:56] cho ký tự mà đi tượng nhiều bé là lý do
[01:39:00] nhiều ông cả là tên được là tên cậu Dạ
[01:39:04] không có gì ở trên Facebook được đúng
[01:39:08] không thể copy được cái tên là luôn Vì
[01:39:10] nó là ký tự Không khoảng trắng đó ngoại
[01:39:13] à
[01:39:14] mà hình như bây giờ vẫn bị dịch 10 thằng
[01:39:17] trong Facebook nó chơi kiểu nói cao nên
[01:39:20] nó không có ràng buộc kiểm tra gì cả nó
[01:39:22] không ai đấy ở miền Bắc em được cái nó
[01:39:23] chỉ cần kiểm tra có ký tự thôi
[01:39:26] à à
[01:39:29] Ừ thế là thằng vé Cốt nó đang quảng cáo
[01:39:32] Thêm cái vụ tình năng của nó là kiểm tra
[01:39:34] xem mình trong cốt nó Cậu sinh ký tượng
[01:39:36] này không phải loại bỏ đi cái mấy ông
[01:39:39] Nếu mày nếu không tái máy mài ông không
[01:39:42] có Cốc trên mạng vì và thừa Cốt trên
[01:39:44] mạng code trên special lâu chắc là nó
[01:39:47] không áp dụng với cho mày đâu nếu mà có
[01:39:49] phải ông và muốn chê ông kiểu thì nó bên
[01:39:53] vai đấy có bị lỗi ở Ngạn nhập một đông
[01:39:55] ký tự hoặc trắng này vào tên của nó biến
[01:39:57] kí tự đặc biệt là Nhạn thì sẽ làm được
[01:40:00] nên là mẹ cũng phải kiểm tra và kiểm tra
[01:40:04] về giao một cốt của mình có vấn đề gì đó
[01:40:06] thì có kìa mẹ không phải cân nhắc việc
[01:40:08] mở cái mở cái cái kiểm tra khoảng trắng
[01:40:12] này lên xem có tính tự nhiên là thừa có
[01:40:15] khoảng còn trắng nhưng mà đợi kiểu
[01:40:18] 0-zero ở đây không hiển thị ra không ạ
[01:40:21] vì không khỏa trắng cho vẫn là một ký tự
[01:40:24] không ạ
[01:40:26] Ừ Ok nói cho bộ hôm nay mình dậy là chia
[01:40:30] sẻ có thể tương đối nhỉ các bạn có thắc
[01:40:33] mắc gì thì bình luận sau nha
[01:40:35] bữa mày tra tạm kết thúc rồi đấy thôi
[01:40:38] Dạ em chào thấy hiệu Thọ hệ phó nay dự
[01:40:41] giờ em sợ quá à
[01:40:45] à à
[01:40:47] cho AD có bạn hỏi nhanh như vụ là chia
[01:40:50] sẻ Cẩm shop từng bị chán cốt theo mình
[01:40:55] từng trả lời có ngày rồi à
[01:40:58] ừ ừ
[01:40:59] có động lực để mặc Cốt lại thì sẽ dẫn ạ
[01:41:02] Không phải về mỗi cốc ngoài về mọi thứ
[01:41:04] khám chị ạ Bạn sẽ bạn sẽ cần là tự tự ra
[01:41:10] cho mình nó nào giống như là mình từng
[01:41:12] tỏ tình của mình bại Đã Ngạn áo kiểu
[01:41:15] tiểu thất bại ram sẽ dễ làm thôi mình sẽ
[01:41:19] lên cẩu thứ nhất là phải làm gì đó Tạm
[01:41:22] quên rồi đi đã Cứ cố nghĩ là nó lại càng
[01:41:25] cay thứ hai là
[01:41:28] các bạn sẽ nên khi họ bắt đầu lại thì
[01:41:32] các bạn nên bắt đầu lại bằng cái canh
[01:41:35] tiếp cận dễ trước đã Ừ chứ không nên bắt
[01:41:39] đầu lại lại làm lại nhảy vào những cái
[01:41:41] khó đấy nhỉ người lại tán cái đứa không
[01:41:44] nhưng mà mình đã từng thất bại thì anh
[01:41:47] nghe là nó sẽ càng khiến mình có thể bị
[01:41:49] chậm chậm hơn không ạ
[01:41:51] thì các bạn sẽ phải kiểu
[01:41:54] quên nó đi này
[01:41:57] ở trong ngành Công nghệ thông tin này là
[01:41:59] không nên cố quá thì các bạn đang bị
[01:42:02] căng thẳng đang không Cốt được bạn cứ
[01:42:05] nghỉ ngơi các bạn có giải trí cho nó lúc
[01:42:07] sau lại tập trung lại không sao cả đều
[01:42:10] ngoạn đấy thế thôi nước khuyên mình thế
[01:42:21] gì hả ông anh Thế ông anh ông anh thế
[01:42:21] Không khuyên được người khác đâu không
[01:42:23] ai Khuyên người khác nhìn lại và cái khó
[01:42:25] để mà lại ngã à
[01:42:36] Ồ không Tôi bảo mấy ông cố quên đâu Tôi
[01:42:36] bảo mày ông làm việc khác thôi Tôi không
[01:42:38] bảo mấy ông cố quên Nếu càng nghĩ càng
[01:42:40] cố càng cố nghĩ thì chắc chắn càng cũng
[01:42:43] nhớ Với cả mẹ ông cứ nghĩ là ông càng
[01:42:47] Hằng nó sâu trong đầu thì mày không sẽ
[01:42:48] nhớ tôi bảo béo làm việc khác thôi Làm
[01:42:52] cái khác mà vẫn nhờ đến nó thì vẫn kệ đi
[01:42:53] ý ra ông vẫn đang làm việc khác ngồi
[01:42:56] kiểu gì cũng sẽ quên nó nào giống như
[01:42:58] kiểu ông cố tập trung để ngủ thì ông sẽ
[01:43:00] không ngủ được con khi mà ông cứ nằm ông
[01:43:02] kiểu
[01:43:03] em nằm nhắm mắt thôi Được kiểu thế không
[01:43:07] nghĩ gì cả thì hôm sẽ tự động ngủ thấy
[01:43:09] thôi
[01:43:15] Ê mày cũng chưa gặp trường hợp đấy nếu
[01:43:15] anh càng cố ngủ mà ông càng không ngủ
[01:43:17] được bởi vì nó vẫn đang nghĩ không ạ
[01:43:31] những câu nói của anh về cái thiên tài
[01:43:31] làm em nhớ về cái vụ
[01:43:33] thiên tài với thằng điên là là một
[01:43:36] khoảng cách rất gần
[01:43:42] Ừ nếu mà nếu mà anh mà không chứng minh
[01:43:42] được mình đúng cái gì anh sẽ thằng điên
[01:43:44] nó mắt này khác còn đấy anh chứng minh
[01:43:46] được mình đúng còn mọi người sai anh sẽ
[01:43:48] thành thiên tài
[01:43:54] Ừ Ok thôi bội mày tạm kết thúc vào đây
[01:43:54] thôi
[01:43:55] ờ ờ
[01:43:57] Ừ có gì thì mình sẽ trả lời Mọi thắc mắc
[01:44:01] sau nha
[01:44:02] ừ ừ
