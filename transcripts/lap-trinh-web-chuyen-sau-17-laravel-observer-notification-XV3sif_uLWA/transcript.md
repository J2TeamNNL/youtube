# Lập trình web chuyên sâu - 17 - Laravel - Observer & Notification

- Video ID: `XV3sif_uLWA`
- URL: https://www.youtube.com/watch?v=XV3sif_uLWA
- Published: 2022-04-22
- Duration: 1h 26m 37s (5197s)
- Language: vi
- Subtitle source: auto
- Kind: live

## Transcript

[00:00:00] đây này vào đít này ở công ty tôi không
[00:00:00] mấy ông Nếu mà nhìn cái này mới thì sẽ
[00:00:02] Coffee Clear khi sex ờ ờ em xóa hết đi Ừ
[00:00:03] mời I ít nhất là hôm trước tôi nói vụ
[00:00:05] sẽ ra được given sau mình sẽ sử dụng cây
[00:00:05] thì ở đây mình cần là mình sẽ kiểu mình
[00:00:05] đợi thì sửa lại cản em nữa em
[00:00:06] Bạn không thân mình không nên phụ thuộc
[00:00:06] sửa iPad tại sao cái này public vì cái
[00:00:07] cho phép bạn đăng ký bằng Superman không
[00:00:07] quần của tôi tôi đã định dạy là kiểu khi
[00:00:08] mình điều đấy thế là say không phải cái
[00:00:08] với mấy cái vụ này chị lại mấy ông nữa
[00:00:09] nó sẽ bán cái mail Thế là chưa Bạn đưa
[00:00:09] từng trải rồi nghe với một người mới thì
[00:00:09] Cái này là tôi sẽ đợi thì tôi sẽ dần dần
[00:00:10] admin Superman và mật khẩu ngay ngoại
[00:00:10] mình sẽ lấy cái password của việc tăng
[00:00:10] Vanda này từ pha cho xuân này và email
[00:00:10] vào như thế này phải in ra cái gì đó kìa
[00:00:10] nghĩa là kể Nói chung giải thích thì
[00:00:11] kia
[00:00:11] có thể cô bị lý thuyết nhiều các thầy cô
[00:00:11] này khi phỏng vấn khó không à bảo facial
[00:00:12] cái bạn thân nó khớp hay không thì nó sẽ
[00:00:12] rồi nó sẽ gửi mail cho mấy ông ngoại
[00:00:12] chồng mới hiểu lắm Làm nhiều sẽ hiểu
[00:00:12] này mặc định là nó sẽ dùng Cài mặc định
[00:00:13] chỉ nói thế rồi nó tôi nhớ là nó không
[00:00:13] chắn này không Để password bằng password
[00:00:13] nghe mình sẽ Ừ nó còn lắng nghe kiểu
[00:00:13] cho bạn thân ông thể khiến cơ thể ông
[00:00:13] Nó sẽ thường động từ lần đầu kiểu C như
[00:00:13] đúng không Mày ngồi thử đọc tài liệu tra
[00:00:14] lớn mà để mà kiểu mình còn cố dẫn đấu
[00:00:14] để cái này uống đi cùng thì như là tôi
[00:00:14] mình nhập mình nhập vào được nữa vì hai
[00:00:14] đâu giờ sự tôi Tại sao hắn nữa nhé ở
[00:00:14] yêu ey bồ rồi anh ạ chút chiêu này ở nhà
[00:00:15] hơn của Android là mà Ừ cái này xảy ra
[00:00:15] cái cái suy nghĩ tâm trạng của ông nó
[00:00:15] cốt đúng hiểu không cái file chị mỗi hai
[00:00:15] Ông cứ kiêm cái giống như tôi đang chỉ
[00:00:16] sẽ khai báo việc this part gặp ngay câu
[00:00:16] gì à Nhưng đều bị xong rồi nhé à à à ở
[00:00:16] mấy ông thỉnh thoảng phải nên tự thưởng
[00:00:16] đăng ký và học hỏi thôi anh anh cho em
[00:00:16] thế này ha kẹo xử lý cái gì đó hiểu cho
[00:00:16] thằng một hàng 123 với Thằng làm bực mã
[00:00:17] thì tôi sẽ dậy luôn cho mấy ông về Y Vân
[00:00:17] nhẹ nhõm hơn đã ấy nói chung là tính tôi
[00:00:17] kiểu dặn trông thấy được cái sự hai Hoo
[00:00:17] tức là xa ví dụ Giả sử bây giờ mình sẽ
[00:00:17] bao gồm và timestamp thành ra là nó sẽ
[00:00:17] thường Ông vẫn vẫn có thể là ông không
[00:00:17] thật thì thôi mình nghỉ nếu là sửa sau
[00:00:17] có lý do gì miếu phải lo lắng cả mọi
[00:00:18] thì nó bị lỗi rồi Không biết bây giờ như
[00:00:18] em sẽ muốn hiểu format của em nó TP
[00:00:18] Đừng có kiểu không dám ước mơ gì cả
[00:00:18] mở họ một con đường gì đó A lô cốt lá
[00:00:18] với ông mà chuẩn bị làm cái trang web và
[00:00:18] giờ chúng ta lại quay trở lại việc À
[00:00:19] hóa trị làm sao bằng nhau được đúng
[00:00:19] Tao tối cũng muốn cho mày không biết tất
[00:00:19] vì tôi một phần tội không chuyên về ngôn
[00:00:19] vào làm luôn cái khó bạn ấy kiểu muốn
[00:00:19] cái hàng file của mình xong rồi truyền
[00:00:20] sẽ gọi luôn hẳn cái thằng ai không cần
[00:00:20] Không ạ mày không nghe Ước mơ lớn nhưng
[00:00:20] là tôi sẽ đặt nó sẽ là Uzi kriss hoặc là
[00:00:20] nào
[00:00:20] về sau thì mấy ông lại dùng cái này rất
[00:00:20] yêu bản thân thì tối hôm trước làm một
[00:00:20] dùng thì thông báo
[00:00:20] hiểu phức tạp lên khó mà đoán được thì ý
[00:00:20] Okay như đại sai thì lời thế nhé em yêu
[00:00:21] làm con người trở cái tinh thần của ơi
[00:00:21] hiểu nhé tổng hợp lại đi ông bị choáng
[00:00:21] mấy ông mà ngồi trang ai cũng vỡ mồm nữa
[00:00:21] Nếu vợ ông giải quyết được ông có thể
[00:00:21] thì tôi từng nói dối tôi không chuyên
[00:00:22] tôi còn đang cân nhắc việc rồi Không
[00:00:22] bạn đã đăng ký với cái gì đó Nó kiểu như
[00:00:22] đăng nhập vào tài khoản Superman hoạt
[00:00:22] làm việc đôi khi dễ hơn
[00:00:22] mà chưa biết về lập trình ra học thì
[00:00:22] cả Không ạ lần này thấy Vân này hợp ở
[00:00:22] nhiều vì như tôi nói mày cũng không nên
[00:00:22] mà vẫn còn những cột mốc nhất định rồi
[00:00:23] cái dừa 2 đó là
[00:00:23] trình kiểu cầu đang gọi Quen như thế này
[00:00:23] ngờ kêu không đầy và kêu gọi này anh
[00:00:23] đầu có thể không tốt rồi về sau thay đổi
[00:00:23] hoặc là riester wish u xơ này nó sẽ đầy
[00:00:24] động trí óc người ta nhìn thấy mật khẩu
[00:00:24] không thể chỉnh sửa lại được cái á
[00:00:24] sâu chỉ mày ông kỹ làm mới giao diện
[00:00:24] ông nên dùng Fshare hơn kẹo even 2
[00:00:24] thì tôi dễ hiểu thôi Đây Âm Nhạc Thế thì
[00:00:25] hợp cho việc lắng nghe một cái mua đồ
[00:00:25] nhiều lúc ông tha thứ
[00:00:25] ông sẽ tự thường bạn thân là sự là tôi
[00:00:25] ra cảm thấy trân trọng người ta cảm thấy
[00:00:26] phải đau lắm còn nếu mà ông không thể
[00:00:26] cái chỗ có liên quan đến cái khác hơn
[00:00:26] tạm thời off xơ và mình kiểm tra khi mà
[00:00:26] cái email thông báo
[00:00:26] này đây tôi sẽ có là đô Rio de đúng
[00:00:26] gửi mail luôn ngay lập tức của bọn mày
[00:00:26] máy được ra tôi on hơi muộn thì tôi vừa
[00:00:27] sẽ chấm rồi không thích kiểu này lắm Vì
[00:00:27] mà tôi nhảy sang Java ở Ngạn có mưa ông
[00:00:27] trong trường hợp mà chắc chắn cột của
[00:00:27] listen to một vài trường nào tôi nghĩa
[00:00:28] đặt cột mốc của tôi là ở đất Ước Mơ Tôi
[00:00:28] tài khoản người ta là phá này thì không
[00:00:28] giải quyết vấn đề thì ông lo lắng nó
[00:00:28] cho anh ở được và cũng như là em thấy em
[00:00:28] học thêm là cái gì đó tôi thấy ra vui
[00:00:29] ông một email Còn nếu cột ở ông không
[00:00:29] khi mà Tạo khởi tạo thành công là Insert
[00:00:29] đỡ bảo tui thon thì thôi nhớ thăm tí hon
[00:00:29] không sẽ lấy tấm vào cái một cái file
[00:00:29] nhưng mà Mấy ông thấy vừa rồi nó bị trận
[00:00:29] không phải liên quan được à khi mà một
[00:00:29] tượng ông lắng nghe bất kỳ một cái gì đó
[00:00:30] chẳng để làm gì cả ông cũng cho rằng cần
[00:00:30] ông thể hấp thụ được ngay mà cái kiến
[00:00:30] không quan trọng với ngôn ngữ mà
[00:00:31] khác thì sao đấy thì thằng này nó không
[00:00:31] ông cảm thấy mình không thích kiểu ngay
[00:00:31] ai ở trên công ty sau đó thì về ngủ tầm
[00:00:31] đi cho cả ngã nhưng mỗi lần mà tôi kiếm
[00:00:31] cái này ra như thế này mỗi file cái
[00:00:31] thì khi mà kiểu khi kéo dạng mà mình đã
[00:00:32] riêng là file chuyên để xử lý gọi là
[00:00:32] thức mà để mà về sau nếu mà ông có thắc
[00:00:32] đối tượng được cập nhật chuyển ngay ừ ừ
[00:00:32] bảo nó gì cả đấy à khi
[00:00:33] về cơ bản thì ra va lại khó TB khá nhiều
[00:00:33] hải một tí ừ ừ khi con bên này thì ông
[00:00:34] đúng nữa mà ghi vật nó phù hợp trong mọi
[00:00:34] chưa sử đến sự kiện này trở lại khái
[00:00:34] tin là mấy ông hỏng ở zava ở trên trường
[00:00:34] này cái lúc chúng ta trong cái kia không
[00:00:35] người ông thích cái sự cho trẻ của nó
[00:00:35] 1 tiếng rồi Dậy ăn rồi ăn tối xong rồi
[00:00:36] mắt thì ông tra tài liệu mà không hiểu
[00:00:36] mục đổi mới uống sữa trong thư mục này
[00:00:36] lại trang đấy mình không thể nó loa tận
[00:00:36] xong xong ấy thì mình sẽ bắt sự kiện đấy
[00:00:36] niệm về ngay và sự là khi đăng ký thành
[00:00:37] trường hợp hơn bọn nó phù hợp trong
[00:00:37] thì không sao thì mới ông theo ngành này
[00:00:38] gì đó để mà tiến gần hơn với con đường
[00:00:38] được Vì sao là tặng cảm thư mục với bao
[00:00:38] Trong lúc ăn tối cũng xem lại các câu
[00:00:39] công sao ngoài việc Ông gửi Mail ông sẽ
[00:00:39] 4 giây rồi chẳng hạn 4 dây cả vấn đề của
[00:00:39] nhiều trường hợp hơn tôi vừa tôi chẳng
[00:00:39] luôn hôm ấy ông về đăng ký Ngạn đây hôm
[00:00:40] xử lý ở đây tôi sẽ copy các bạn này cứ
[00:00:40] tôi để mấy ông xem lại chứ Bây giờ tôi
[00:00:41] còn kiểu là là rất nhiều cái nữa thông
[00:00:41] đấy thì tôi sẽ lại tự thưởng màn hơn
[00:00:41] News chứ đó đầy đủ do như thế này này ok
[00:00:42] qua cho chị qua cả hai thôi mà cuối cùng
[00:00:42] hỏi bộ uống thuốc về mấy hôm trước bận
[00:00:42] đấy bây giờ xử ông bảo xin cậu cộng với
[00:00:43] chạy này Tí
[00:00:43] cũng không nghĩ là mày em sẽ áp dụng là
[00:00:43] trước chưa làm tình đăng kí bây giờ mình
[00:00:43] phải đội để mà ông Huy nếu thành công
[00:00:44] quá không không không tổng hợp lại câu
[00:00:44] kiểu nó chẳng chặt chẽ gì cả đơn giản
[00:00:45] này vào đâu nếu không hiểu thì thôi
[00:00:45] báo hay là cập nhật nó ta bay cái gì đó
[00:00:45] sẽ có đăng ký bởi bình thường thì khi
[00:00:46] chưa ạ Anh tên rất ở dài nhưng về sau
[00:00:46] là
[00:00:46] hỏi tối em phải ngồi xem Thor xn lần để
[00:00:46] đến notification là để mà gửi mail rồi
[00:00:47] không đấy thì cũng không phải lo hôm nay
[00:00:47] thì ông sẽ tạo rất nhiều với sự Thiện
[00:00:48] vào một cái vào trang web mình nó ngon
[00:00:48] một cái gì tượng đài thì sao tôi không
[00:00:49] hơn thì
[00:00:49] ông ạ Nói chung cái này cái thứ mà tôi
[00:00:49] nó không ạ thì cái cái đoạn này ở đây
[00:00:50] thì rõ ràng là mình phải đăng ông ngoại
[00:00:51] vì sau khi mà học chuyên sâu trong TP
[00:00:51] mà ngồi xem toàn bộ mày câu hỏi xem có
[00:00:52] rất nhiều một cái ông sẽ bay là một cái
[00:00:52] động lực hơn để mà làm ông ạ nhiều bạn
[00:00:52] thể thấy được à ờ ờ a tiếp theo là
[00:00:52] nó là kiến thức gọi là nâng cao hơn bí
[00:00:53] chỉ qua một cái nhìn này Đấy nó cơ chế
[00:00:54] thì mới được thấy ở ra tôi đang dạy mày
[00:00:54] cũng bị mail này một cái ông thông báo
[00:00:54] vòng con chóp có kêu gì gió ý là chạy
[00:00:56] không về aupair Hơn tượng Vì sao tớ hết
[00:00:56] cho hắn mi nữa Ngạn đấy ba thằng Đó là
[00:00:57] mình dễ dãi bản thân quá rồi không nói
[00:00:58] có thêm 1 anh
