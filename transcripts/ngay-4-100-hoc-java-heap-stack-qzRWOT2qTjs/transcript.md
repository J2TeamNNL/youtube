# Ngày 4/100 học Java - Heap & Stack

- Video ID: `qzRWOT2qTjs`
- URL: https://www.youtube.com/watch?v=qzRWOT2qTjs
- Published: 2026-01-16
- Duration: 1h 09m 35s (4175s)
- Language: vi
- Subtitle source: auto
- Kind: live

## Transcript

[00:00:23] rồi. Đợi tí.
[00:00:26] À hôm nay là buổi ba
[00:00:29] hôm nay là buổi ba.
[00:00:45] đấy. Uầy tông ng đỏ trông sợ thế.
[00:00:56] nhiều màu cũ.
[00:01:31] đang bảo chỉnh
[00:01:34] áo kia áo Dragon Ball rồi đúng không?
[00:01:36] Nhưng mà trông hơi
[00:01:39] cái
[00:01:41] à mấy bỏ mấy viên đi
[00:01:47] trên áo.
[00:01:53] này. Con gì nhỉ?
[00:02:05] thực ra là tìm đến kênh của mình là để
[00:02:07] mà học để ôn thi xong rồi có người qua
[00:02:11] nhưng mà cái việc là họ còn trụ lại với
[00:02:14] ngành thì mình thấy a tùy tùy duyên.
[00:02:19] Phải biết là dùng từ duyên bởi vì rõ
[00:02:20] ràng là có nhiều người mình thấy có giỏi
[00:02:23] nhá. người ta cũng có triển vọng nhưng
[00:02:25] mà người ta không theo. Ờ nếu mà các bạn
[00:02:28] đang thấy là mình đang livestream ở
[00:02:31] không phải nhà mới mà đây chính là văn
[00:02:34] phòng mình đang làm việc ở trên công ty.
[00:02:36] Hôm nay mình livestream sớm hơn bình
[00:02:38] thường và cũng nói chung là cũng lệch
[00:02:40] giờ nữa bởi vì mình đang tiện ở đây mình
[00:02:44] đang livestream không thì anh em lại bảo
[00:02:46] là mình bùng học nhiều quá. Thực ra là
[00:02:48] mấy ngày hôm nay là mình có học nhưng mà
[00:02:50] mình học nhảy bởi vì phải diễn văn nghệ.
[00:02:53] Đấy mình đang ngồi thiết kế lại cái a
[00:02:58] ảnh thăm như các bạn đang thấy. Mình
[00:02:59] thiết kế lại xong rồi mình sẽ sửa lại
[00:03:02] đồng bộ cho các video khác chứ cái ảnh
[00:03:05] cũ thì tôi cũng không thể ưng lắm. Đấy
[00:03:10] mấy ông thấy ổn không? Thấy ổn đúng
[00:03:12] không? Nó mất cái Tôi bảo nó hai cái màn
[00:03:15] nhưng mà quay đi quay lại thấy mất một
[00:03:17] màn rồi. Rõ ràng vừa nãy có hai màn nhỉ?
[00:03:20] Thôi một màn cũng được nhở. Ổn mà đúng
[00:03:22] không? Nhìn rõ mà đúng không?
[00:03:24] Cái màn hình code này nó sẽ thay đổi
[00:03:26] theo nội dung bài học luôn đấy. Không
[00:03:28] phải có mỗi như kiểu hiển thị đơn giản
[00:03:31] nhưế này đâu. Hiện tại thì bài một thì
[00:03:34] đúng là mình chỉ khai báo kiểu dữ liệu
[00:03:37] và phân biệt kiểu dữ liệu nên nó mới
[00:03:38] trông đơn giản này thôi.
[00:03:41] Ơ nhưng mà mất cái ghế rồi. Mất
[00:03:45] mất ghế công thái học và
[00:03:55] của tôi rồi. Ý tôi là bỏ viên bi đi
[00:04:00] thôi.
[00:04:08] Anh nhảy thử thì thựt ra là gần mấy ngày
[00:04:12] hôm nay là bạn gái anh dậy nhảy. Bạn gái
[00:04:14] anh anh thường hay kiểu trêu bạn ấy hot
[00:04:15] tiktoker à hay nhảy. Anh quen bạn đấy là
[00:04:19] qua ứng dụng App dating hẹn hò Facebook
[00:04:23] dating đấy để mà nói chuyện lúc đầu xác
[00:04:27] định lúc nào để nói chuyện là kiểu à nói
[00:04:30] chuyện thôi bởi vì thời đấy là thời anh
[00:04:33] đang rất là khủng hoảng rất nhiều cái
[00:04:36] không phải khủng hoảng hiện sinh đâu nhá
[00:04:38] đấy nhưng đại khái thì phải mãi về sau
[00:04:40] thì mới bắt đầu kiểu nghiêm túc về tìm
[00:04:43] hiểu các thứ xong rồi anh vẫn ấn tượng
[00:04:45] nhất về bạn đấy đó là mẹ Con người rất
[00:04:48] nhiều năng lượng anh kiểu đương nhiên là
[00:04:50] xem qua các nền tảng mã xã hội ấy thì
[00:04:52] thấy là bạn ấy là con người rất nhiều
[00:04:54] năng lượng nên rất là thích đấy trông ổn
[00:04:57] nhất rồi nhỉ. Áo vibu này tóc thì như là
[00:05:00] không giống tôi lắm nhưng là thôi không
[00:05:01] quan trọng. Đấy đây là tai nghe gaming
[00:05:05] đấy.
[00:05:06] Thực ra tôi có con tai nghe Sony này cơ
[00:05:09] nhưng mà thôi bảo nó ngồi sửa lại hết
[00:05:12] chi tiết quá không cần. Ghế ghế này ghế
[00:05:15] công tho ở nhà tôi này. Áo thự áo tôi áo
[00:05:18] T One cơ nhưng mà tôi nó muốn thể hiện
[00:05:21] một tí wibu ở đây nên là thôi chắc là
[00:05:24] cho vào chứ chứ T one thì bây giờ là
[00:05:28] không ở trong hang đâu nên là chữ Wibo
[00:05:31] mới hay trong má. Đây ngày 1 trên 100
[00:05:35] được cái này phản ánh rõ là kiểu học
[00:05:38] kiểu Java đúng không? Từ 1 đến 100 nhở.
[00:05:43] chốt cái này nhỉ mấy ông nhỉ? Mấy ông
[00:05:44] thấy ổn mà đúng không?
[00:05:55] ờ tôi còn đang bấm hình như là vừa tôi
[00:05:57] vừa rồi tôi bấm like nó nhầm.
[00:06:08] Cái này là tôi đang live xem live cùng
[00:06:09] mấy ông chứ không phải là tôi đang
[00:06:13] đây đây đây. Đợi tí đợi tí. Đây đây đây.
[00:06:22] Đây tôi phải xem phân tích ở đây để biết
[00:06:25] được là đang có bao nhiêu người xem này.
[00:06:27] Xong rồi
[00:06:29] luồng mọi thứ thế nào này. Ok. Ờ ui tận
[00:06:34] ba 13 người xem số thực ra là cũng không
[00:06:38] đẹp nhưng không sao đây. Ổn đúng không?
[00:06:41] Xong rồi mình lại phải chơi group. Hôm
[00:06:44] trước có cái trang group trông xịn xịn
[00:06:46] ấy mỗ tội là gì ạ?
[00:06:51] Giao diện không dễ dùng nhưng mà ừ trang
[00:06:53] này xịn
[00:06:55] nó là resiz ảnh à hôm trước là resiz ảnh
[00:06:59] đúng không?
[00:07:07] Compress
[00:07:09] online.
[00:07:11] Hôm trước là dùng không phải dùng trang
[00:07:13] này đúng không?
[00:07:16] Trang này có khi là đơn giản cơ bản hơn
[00:07:18] này.
[00:07:20] Đợi tí
[00:07:31] tốt hơn có nhiều. Đây này 2 m này không.
[00:07:35] Trang kia có vẻ xịn hơn vì trang kia là
[00:07:37] chỉ có
[00:07:43] ấy.
[00:07:50] các buổi live hôm trước.
[00:07:54] May mới chỉ có hai ba buổi gì đấy dễ
[00:07:56] sửa.
[00:08:17] Đây hình như là hôm trước là cái này.
[00:08:25] Xem nhá.
[00:08:27] Hôm trước không phải cái này rồi.
[00:08:29] Hôm trước cái trang web kia màu mè thật.
[00:08:31] Chắc chắn là có thể đôi khi dùng vi code
[00:08:33] hay gì gì đó.
[00:08:40] nhưng mà có vẻ là chưa xịn mà cái hôm
[00:08:42] trước.
[00:08:49] bằng cái hôm trước. Hôm trước đổi kiểu
[00:08:50] gì thành hai 200 đỉnh vãi chưởng.
[00:09:01] đâu lại có khi nét hơn hôm trước. Mà
[00:09:03] thực ra là cũng chẳng cần phải nét đến
[00:09:04] thế đúng không?
[00:09:31] đây.
[00:10:07] người hơn nhỉ. Kiểu kiểu như người thật
[00:10:10] ấy. Còn ảnh này thì hơi trông kiểu toàn
[00:10:16] bộ là ảo nhưng thôi không sao.
[00:10:19] Mình ở Wibo mà.
[00:10:22] Ờ đấy
[00:10:24] cho tôi
[00:10:28] ảnh ngày hai
[00:10:30] à.
[00:10:31] Nội dung hôm thứ hai mình học sẽ là
[00:10:35] string demo.
[00:10:50] nhá.
[00:10:52] Đấy anh thế tôi phải để ở đây rồi
[00:11:00] hôm trước là tôi nhớ là học cả
[00:11:09] hôm trước học gộp bài rồi
[00:11:21] cái này cũng chẳng cần. Ờ tôi xóa xử cái
[00:11:24] class này đi.
[00:11:27] Ok, xóa xử đi.
[00:11:30] Thực ra mình chỉ cần quan tâm đến Java
[00:11:32] thôi. File Java thôi mình có cần chạy
[00:11:34] đâu. Ừ.
[00:11:41] xóa đi luôn cũng được. À gì nhở?
[00:11:51] này mọi người ăn cơm biết rồi.
[00:11:53] Nhưng không sao, tôi vẫn sẽ livestream
[00:11:55] thôi. Tôi livestream để cho anh em xem
[00:11:58] lại đúng không? Anh em còn ngồi học
[00:12:00] cùng. Dạo này đâm người vào server vãi
[00:12:02] chưởng. Xong rồi nhiều người cũng bình
[00:12:04] luận mà.
[00:12:09] là ngày 4
[00:12:13] và ngày hôm mùng ngày mùng 1 thì mình
[00:12:19] lại học cả
[00:12:22] cái này với string po.
[00:12:25] Tring p
[00:12:51] là
[00:12:58] th
[00:13:08] kiểu này sẽ hơi xấu.
[00:13:42] nội dung ở đây
[00:13:45] nó là ngày 1 + 2.
[00:14:04] ghi thế để cho mọi người hiểu rõ là chứ
[00:14:06] không thì người sau sẽ không hiểu được
[00:14:09] là tại sao lại có thế. Ừ trông không đến
[00:14:12] nỗi nhỉ mấy ông thấy ổn không? Tôi thấy
[00:14:16] ổn mà nhỉ. Con này thừ làm tốt phết. Con
[00:14:18] này vẫn giữ được những cái chi tiết ảnh
[00:14:20] cũ.
[00:14:22] Con chatt thường hay tự động các thứ
[00:14:24] thay thế.
[00:14:27] Đấy, màn hình code cũng thay đổi, người
[00:14:30] ta nhìn và người ta cũng hình dung được.
[00:14:32] Được
[00:14:34] xịn tôi đánh giá xịn.
[00:14:37] Ơ ấn nhầm
[00:14:40] đấy. Con này cũng được.
[00:14:43] Xong vừa rồi mình à đấy mình nén bằng
[00:14:47] con này.
[00:14:59] cách a nó cũng không cách a.
[00:15:10] hay vì liến.
[00:15:28] [âm nhạc]
[00:15:29] Ở công ty tôi làm về mảng về những sản
[00:15:32] phẩm in ấn. Bên tôi cũng dùng AI thôi.
[00:15:35] Bên tôi cũng gọi sang Open AI Chat TVT
[00:15:39] với con chini này để tạo ra ảnh.
[00:15:42] Dạ. Nhà nhà bây giờ phải có một tí tích
[00:15:44] hợp AI cho nó sang không ạ? Đấy
[00:16:03] trong chữ ấy.
[00:16:07] Trên
[00:16:24] thật
[00:16:26] kiểu cứ thế mà dùng thôi.
[00:16:29] Mỗi lần tôi ra lệnh prom như này là lại
[00:16:33] tốn gì nhở? Ít nhất là tốn a nước để mà
[00:16:38] làm à
[00:16:40] kiểu gọi nhỉ
[00:16:44] nước a gọi là quê sương mất rồi. Kiểu
[00:16:48] nó có từ của nó là gì nhỉ?
[00:16:56] Cái a
[00:17:00] bình thường là cái a quạt tản nhiệt bằng
[00:17:03] hơi nước à quạt t quả tàn nhiệt nước.
[00:17:06] Đúng rồi đấy. Thì những cái lúc mình ra
[00:17:08] lệnh như này ý rằng là mình tốn một ít
[00:17:10] nước để mà nó kiểu tạm nhiệt bớt cho
[00:17:13] máy. Đấy kiểu thế
[00:17:16] lỗi tôi
[00:17:18] chỉ thiếu mỗi cái này thôi. Ơ nếu đìý kỹ
[00:17:21] là nó chỉ khác nó cũng cố thay đổi nhưng
[00:17:23] mà nó vẫn giữ được cái tông đỉnh à. Thế
[00:17:26] vẫn đỉnh đấy.
[00:17:44] anh em cứ nói chuyện nhá. Tôi vẫn để ý
[00:17:46] kênh chat mà gì anh em cứ nói nhá. Để
[00:17:48] tôi ngồi sửa xong cái này rồi anh em
[00:17:50] cùng ngồi học.
[00:18:02] không phải mỗi lần gì cuối tuần lại ở
[00:18:05] công ty. Ui sao em biết anh ở đang ở
[00:18:08] công ty anh?
[00:18:10] Anh đang kiểu kiểu nói chung là mày
[00:18:15] tranh thủ thôi
[00:18:22] Vừa rồi anh ngồi học nhảy chứ
[00:18:25] đấy
[00:18:27] nh. Sao ông không nghĩ đây là kiểu nhà
[00:18:30] tối chắc thế? Có cái gì thể hiện nhà
[00:18:33] không nhỉ?
[00:18:35] Kiểu phong phong khác đấy. Hoặc là có
[00:18:38] nét
[00:18:44] lỗ hết bài
[00:18:47] đấy. Bây giờ sẽ sang hôm trước học
[00:18:50] string đúng không? cũng chưa học string
[00:18:52] rồi. String builder và string buffer
[00:18:54] nữa. Đúng. Tôi vẫn nhớ quá địch đấy.
[00:18:58] Mình sẽ là à
[00:19:02] cho tôi ảnh ngày 3
[00:19:06] nội dung là
[00:19:13] và string berfer đấy chuẩn đúng không ạ?
[00:19:18] Còn gì nữa không ạ? không lại tốn hơi
[00:19:21] nước
[00:19:24] về sau ấy nghĩ chơi trò là kiểu cứ cứ
[00:19:28] mỗi lần à
[00:19:30] sau mỗn mỗi một ngày ấy thì ông kia mọc
[00:19:33] thêm một tí râu kiểu giống kiểu tôi kiểu
[00:19:36] già đi ý ông hiểu không kiểu thì đến
[00:19:39] ngày 100 là kiểu thành cao thủ đại võ
[00:19:42] lâm hiểu không kiểu dragon b là ông a
[00:19:46] tiên lão hy sinh à tiên lão tiên tiên
[00:19:49] sinh à? Cái gì? À quy lão tiên sinh đấy.
[00:19:53] Đấy ông nếu ông xem truyện Dragon Ball
[00:19:55] chắc ông biết đấy
[00:19:59] nhưng mà ông hiểu ý tôi không? Đấy Quy
[00:20:01] lão tiên sinh. Quy lão tiên sinh
[00:20:05] đấy
[00:20:07] trông trông có những ảnh chục chu ảnh
[00:20:10] chục đấy thì ý tôi là thế. Lúc đầu lúc
[00:20:15] đầu mình có thể là giống cái a lúc đầu
[00:20:18] có tóc kiểu như này vì tao kiểu đến 100
[00:20:21] ngày kiểu trong ngày java hiểu không?
[00:20:23] Cao thủ đại võ lâm đấy.
[00:20:26] Đấy lúc đầu một là mình thành cái thằng
[00:20:29] kiểu như này. Hai lúc đầu mình chọc sẵn
[00:20:31] cũng được đỡ phải chỉnh tóc chỉ chỉnh
[00:20:33] dâu thôi.
[00:20:44] không đúng không? vừa quên bảo màn hình
[00:20:46] cố tốn thêm hơi nước rồi
[00:20:50] đôi
[00:20:53] cả màn hình code cho tôi còn gì nữa
[00:20:58] không chắc đi
[00:21:00] mọc thêm dâu không mấy ông chốt không
[00:21:03] không mọc thêm dâu đúng không vẫn giữ
[00:21:04] nguyên mọi thứ đúng không ghế tôi thấy
[00:21:06] cài càng tối đi phải
[00:21:09] mình có thể cho là ông này cài càng cụ
[00:21:11] gù hơn chẳng hạn học nhiều quá gù lưng
[00:21:15] À không ký công thái học chắc không đến
[00:21:17] lỗi đâu.
[00:21:19] Chốt nhá. Ok.
[00:21:30] Ui mở ảnh vừa rồi không biết có dính bản
[00:21:31] quyền hay không cơ chắc không đâu.
[00:21:34] Google mà chẳng lẽ YouTube ấ đi đánh bản
[00:21:37] quyền Google
[00:21:40] từ 2023 đến giờ nhớ anh quá ha. Cá cá cá
[00:21:44] cá. Ok.
[00:22:06] Không nên tốn thêm nước.
[00:22:15] Kể cả dù ngày thứ 99, ngày thứ 100 thì
[00:22:18] tôi sẽ cho nó lên thành kiểu đầy thanh.
[00:22:22] Còn ngày 3 này thì
[00:22:41] còn sửa mỗi hôm nay với a
[00:23:09] ok đổi
[00:23:33] hip và stack. Uầi nghe thấy hay rồi. Hôm
[00:23:36] trước mấy ông nhắc liên tục tôi chả hiểu
[00:23:38] cái gì cả đấy.
[00:23:42] Cho tôi ngày 4 h
[00:24:00] Đúng đúng như là có khi tôi bắt đầu quen
[00:24:02] dùng của Gemini rồi. J nó sẽ kiểu không
[00:24:05] nhớ những cái ở trên ấ cho dù rõ ràng ở
[00:24:08] trên vừa đề cập texch các thứ thứ ấ mình
[00:24:10] phải nhắc lại prom đầy đủ thì nó mới
[00:24:13] nhận. Nhưng mà đấy cũng là một cái điểm
[00:24:15] hay là là
[00:24:19] nó sẽ giữ lại được toàn bộ cái a
[00:24:22] ở dưới. Nghĩa là nó giữ lại toàn bộ
[00:24:25] những cái này này. Còn thằng chat vityt
[00:24:27] nó cứ thay đổi kiểu thay đổi liên tục.
[00:24:30] Nhưng mà bổ lại mình phải ghi nhập kiểu
[00:24:32] prom rất là chi tiết lại. Rõ ràng đang
[00:24:35] trong cùng cuộc trò chuyện đúng không?
[00:24:37] Ui ông mà nhảy sang trò chuyện khác. Cái
[00:24:39] thằng memory thằng này tệ cực sáng khẳn
[00:24:42] cái khác luôn. Sao tự nhiên thầy có
[00:24:44] class này
[00:24:52] class với method để mà
[00:24:56] có có nhắc đến stack với hip kìa. Đúng
[00:25:00] không? Đúng không? Ừ chắc là thế. Tôi
[00:25:03] nhìn thấy trông có vẻ là đúng đúng. Ông
[00:25:07] nào biết về Java ở đây nhắc nhá.
[00:25:09] Chứ toàn anh em PP chuyển sang không
[00:25:12] biết gì cả.
[00:25:15] Trông đúng đúng không?
[00:25:19] Ừ tôi thấy trong hợp lý mà đúng không?
[00:25:21] Khai báo nếu mà khai báo biến truyền vào
[00:25:25] từ method đúng không? Thì sẽ là stack.
[00:25:34] Em không nhìn được màn hình á. Sao nhỉ?
[00:26:09] rồi không nói gì nữa. Ông lừa tôi đúng
[00:26:11] không? Chôn chôn.
[00:26:20] cả. Anh chỉ đang ngồi sửa lại cái a à
[00:26:25] anh anh đang nói cái chữ ở trên này này.
[00:26:27] Cái chữ ở trên này này chắc là bé quá
[00:26:29] mọi người nhìn thấy đúng không? Đây được
[00:26:32] chưa?
[00:26:33] Ok chưa? Mình hiểu tôi cũng nhìn góc như
[00:26:36] này mới nhìn được. Đấy anh đang sửa cái
[00:26:40] thăm của mấy cái bài các thứ thứ bài cũ
[00:26:43] và bài hôm nay nữa.
[00:26:46] Thông cảm bây giờ mới chuẩn bị à th
[00:26:48] chuẩn bị nữa bây giờ mới làm đấy.
[00:26:52] Đáng lẽ chuẩn là mấy cái này là phải làm
[00:26:54] từ đầu rồi để mấy ông xem luôn. Nhưng mà
[00:26:56] tôi muốn livestream sớm để mà cứ cho nó
[00:26:58] câu mấy ông vào đi. Chứ mấy ông có khi
[00:27:01] là mấy ông sẽ nghĩ là 8:00 rồi mới live
[00:27:03] chẳng hạn đúng không? Thì hôm nay live
[00:27:06] sớm hơn mà.
[00:27:13] Thấy tôi
[00:27:15] sửa lại cái thăm của cái video này này.
[00:27:19] Đây sẽ là buổi bốn học Java.
[00:27:22] Đây sẽ là
[00:27:31] Công nhận hai cực ý. Không biết mấy ông
[00:27:34] thấy thế nào nhưng tôi học mấy ông và
[00:27:36] mấy cái này tôi thấy thú vị vãi chưởng
[00:27:38] thật
[00:27:40] nên là cảm thấy kiểu rất hào hứng khi
[00:27:42] học.
[00:27:52] đó mấy ông tải lại sang đi ạ. thấy
[00:27:56] thăm mới với a tiêu đề mới.
[00:28:21] đặt, setup các thứ các thứ. Đây chúng ta
[00:28:24] sẽ vào hẳn máy nhá. Ok.
[00:28:27] À đầu tiên là hôm nay nhắc về stack và
[00:28:33] stack thì tôi biết về khái niệm stack
[00:28:34] rồi. Nó vẫn là ngăn xếp này. Nó vẫn thế
[00:28:36] thôi đúng không? Ừ cái
[00:28:41] đầu tiên thì nếu mà kiểu trong PP tôi
[00:28:44] nhớ rồi chỉ sẽ biết về stack với kill
[00:28:46] mà.
[00:28:48] Không biết mấy ông có biết cái này
[00:28:49] không. Cứ cho giả sử mấy ông chưa biết
[00:28:52] thì tôi nói lại nhé.
[00:28:54] Thì stack mọi người thường hay so sánh
[00:28:56] nó giống như cái trồng đĩa. Tức là nó
[00:28:57] chỉ là first in last à first in first
[00:29:08] first in first out kia. Tức là sao?
[00:29:10] Nghĩa là trống đĩa tức là sao? Nghĩa
[00:29:12] mình cho một cái đĩa vào đầu tiên đúng
[00:29:14] không? Xong rồi nhét thêm cái đĩa đĩa
[00:29:15] đĩa đĩa trồng với nhau hoặc trồng sách
[00:29:17] cũng được tùy. Xong rồi để mà lấy ra cái
[00:29:19] đĩa ở ở dưới cùng thì thường mình sẽ
[00:29:23] phải bỏ lần lượt từng cái ở trên trước
[00:29:25] đúng không? Nghĩa là sẽ là sẽ là last in
[00:29:29] nhưng mà first out đúng không? Last in
[00:29:34] first out. Và cái này sẽ là last in last
[00:29:38] out. Còn thì sao? Kill của nó sẽ
[00:29:45] hình dung. Ơ xem
[00:29:49] cấu trúc memô
[00:29:53] qua tôi tra cấu trúc của một câu xin lỗi
[00:29:59] của à trong Java.
[00:30:04] À đây đây đây tôi sẽ gợi ý cho mấy ông
[00:30:07] một cái nữa. Cái Natkin AI. Cái này là
[00:30:12] tôi từng dùng cái thằng này để mà làm
[00:30:15] PowerPoint bởi vì nó luôn mô phỏng ra xị
[00:30:19] cực. Xị cực. Đếm giờ hình như nó vẫn
[00:30:21] miễn phí phải xị cực. Đấy. Đây hồi trước
[00:30:24] làm PowerPoint này thấy không? Đợi tí
[00:30:26] nhá. Đợi tí nhá. Nhìn nhìn nhá. Đây cấu
[00:30:29] trúc memory trong Java đúng không? Đấy
[00:30:31] nhập. Enter.
[00:30:34] Đấy sẽ soạn v rất rất xịn. Ầy bây giờ
[00:30:37] thêm logo này nhưng thế này chưa đủ. Mấy
[00:30:40] ông bảo tưởng anh làm thế nào cái này
[00:30:44] cái này cho em làm được đúng không?
[00:30:47] Không bình tĩnh bình tĩnh. Đây nhìn nhá.
[00:30:51] Bôi toàn bộ đoạn này ấn cái này này. Đấy
[00:30:57] đấy xong rồi bây giờ nó sẽ tạo ra một
[00:30:59] cái ảnh trực quan để mấy ông nhìn.
[00:31:02] Và cái này rất hợp để hồi trước tôi là
[00:31:04] PowerPoint tức là chỉ kiểu để thuyết
[00:31:07] trình ấy. Nghĩa là ông vừa dùng con này
[00:31:10] để kiểu tạo ra một cái đoạn gọi là tài
[00:31:15] liệu document đúng không? Đấy và trong
[00:31:18] slide thì ông không nên có chữ vì slide
[00:31:20] tôi chỉ có ảnh thôi thì tôi sẽ để mấy
[00:31:22] cái ảnh kiểu như này. Nghĩa là nó rất ít
[00:31:24] chữ và nó sẽ dễ rất dễ hình dung đúng
[00:31:26] không? Xịn không?
[00:31:29] được tí tôi nhé. Cái này cái này không
[00:31:32] xuất ra. Ừ thích thì tí tôi bảo nó xuất
[00:31:34] ra dạng à file ma down. Xong rồi tôi đẩy
[00:31:38] lên cùng tài liệu trong kiểu GitHub hoặc
[00:31:42] cái này xuất ra file PDF được thì phải.
[00:31:45] Để đẩy cái này lên cho anh em vừa ngồi
[00:31:48] xem vừa ngồi đọc tài liệu cùng cho nó
[00:31:51] đẹp.
[00:31:52] màu mè chính mà
[00:31:55] mớ
[00:31:57] nhưng mà tôi không biết tí vì gì về Java
[00:31:59] quan trọng thế khi mà mình hỏi ai ấy mà
[00:32:02] mình không biết cái câu trả lời đúng
[00:32:05] không thì nó rất dễ chém gió ra cái gì
[00:32:08] đó chắc là cái này nó không chém gió đâu
[00:32:10] vì lý thuyết nó vững như ý tôi là kìa nó
[00:32:13] mà trả lời cho ông một cái sai ông không
[00:32:15] có đủ kiến thức để xác nhận được nó sai
[00:32:18] ý tôi là như thế nghĩa là thường là bây
[00:32:22] giờ kinh nghiệm không phải kinh nghiệm
[00:32:24] nữa mà là
[00:32:26] mà là bài cứ cho bài học xương máu hay
[00:32:28] cái gì đó đi. Đấy khá là ông chỉ nên hỏi
[00:32:31] AI khi mà ông biết được câu trả lời nên
[00:32:34] là kiểu thường hỏi ai để mà chắc chắn
[00:32:36] lại được câu trả lời này hoặc là nói về
[00:32:40] lộ trình hay vân vân vân. Nói chung đại
[00:32:42] khái là ông phải có một cái gì đó gọi là
[00:32:45] kiểm tra nó, check nó validate nó. Đấy,
[00:32:49] kiểu thế nghĩa là chỉ xác thực lại được
[00:32:52] cái thông tin nó đưa ra cho đúng hay
[00:32:54] không. Ví dụ một cái điển hình nhá. Tôi
[00:32:57] đưa ra cái này ông là mấy ông ở đây biết
[00:32:59] về Java, ông có thể nói lại với tôi là
[00:33:01] nó đang nói đúng hay sai chẳng hạn. Thế
[00:33:04] nhưng bây giờ trong trường hợp mà tôi
[00:33:05] không có bọn ông, tôi chỉ có mình tôi
[00:33:07] thôi, tôi lại không kiến thức với Java
[00:33:09] thì rõ ràng nó nói tôi cái gì tôi rất
[00:33:11] khó và xác thực trư khi tôi lên Google.
[00:33:13] mà lên Google thì tính ra là Google bây
[00:33:16] giờ còn bị nhược điểm Google đầy dãy
[00:33:19] đúng không? Kiểu tự nhiên mình phải đi
[00:33:20] ngồi sàng lọc lại thông tin các thứ thứ
[00:33:22] chứ nó không trả lời đúng sai cho mình
[00:33:24] được đúng không? Thế nên thường nhiều có
[00:33:27] anh em chơi cái trò đó là hỏi con một
[00:33:29] con AI này xong rồi mình dùng những con
[00:33:31] AI khác để xát thực đúng không? Nhưng mà
[00:33:33] nó vẫn có trường hợp là nếu mà vào cái
[00:33:36] kiến thức nào đó mà không một con AI nào
[00:33:39] biết mà một con AI này bịa thì những con
[00:33:42] khác nó vẫn hoàn toàn thể bịa vì chẳng
[00:33:44] làm gì con nào biết cỏ lúa bằng nhau mà
[00:33:46] đúng không? Đấy nên là cách mà dùng con
[00:33:50] AI để mà check để mà validate dự kiểu
[00:33:53] kiểm tra về độ xác thực độ chính xác về
[00:33:55] dữ liệu nó cũng kiểu
[00:34:00] không đáng tin cậy lắm đúng không?
[00:34:09] kiểu nhiều chữ cũng kiểu tương đối nhiều
[00:34:11] chữ mà đúng không?
[00:34:18] Xịn không?
[00:34:23] này. Uầy đẹp vãi trưởng
[00:34:26] đấy. Đấy xong nó còn thêm màu nhá. Thôi
[00:34:30] cứ cứ nhảy không mộc như này chưa đủ
[00:34:33] đâu. Đấy ông còn thể chỉnh thêm được.
[00:34:35] Ông thể vào đây sửa chữ này gì đó này
[00:34:38] đúng không? Đấy. Ôi thêm bao nhiêu thứ
[00:34:41] này. Nhưng cái hay tôi thường hay bấm
[00:34:43] vào đây này. Đấy. Tôi sẽ xuất ra nét
[00:34:46] nhất này. Không có background để nó là
[00:34:48] ảnh kiểu ảnh B B BNG là ảnh trong suốt
[00:34:51] ấy. Đấy. Đương nhiên là khi mà copy ra
[00:34:56] clipboard này nó sẽ thêm cái logo ông
[00:34:58] thể tắt đi nếu mà ông mua bản gì đó. Còn
[00:35:01] không thì
[00:35:02] [âm nhạc]
[00:35:04] hả
[00:35:06] liều nhiều lý thuyết khó hình dung á.
[00:35:09] Nếu mà ông chỉ hiển thị mỗi sáu cái xong
[00:35:11] rồi suy ra hiệu suất của Java thì tôi
[00:35:14] nghĩ cái đấy còn khó hiểu hơn đúng
[00:35:16] không? Cái này nghĩa là mình không thể
[00:35:19] nên bảo là bỏ bớt chữ được vì nó là lý
[00:35:21] thuyết.
[00:35:26] rồi tôi nói tôi có tin đâu chứ quan
[00:35:28] trọng là bây giờ tôi hỏi mấy ông thì mấy
[00:35:31] ông cũng phải cho tôi một cái tài liệu ở
[00:35:33] đó đúng không? Không thì mình
[00:35:37] ôi nhở chỉ có h với steak thôi nhỉ?
[00:35:39] Không tại có ông có ông nào vừa nãy nói
[00:35:41] là xem cấu trúc để cho dễ hình dung. À
[00:35:45] chính ông chứ anh. Đấy nếu thế ông phải
[00:35:48] nói rõ tôi đây tôi soạn lại một cái nói
[00:35:50] rõ hơn nhá.
[00:35:54] Đấy
[00:36:14] không? Đây.
[00:36:17] Ok chưa? Đấy so sánh mỗi hai thằng nhá.
[00:36:23] Sau nó sẽ ra được một cái
[00:36:31] khoe cái này mà.
[00:36:39] chơi cái này để so sánh hai thằng
[00:36:44] đấy. Ông muốn mom tôi nghĩa cứ cứ đơn
[00:36:48] giản mà chơi đi. Quản lý bởi Gabit
[00:36:51] Collector này truy cập chậm hơn, truy
[00:36:54] cập nhanh quản lý tự động kích thước cố
[00:36:57] định, kích thước động lưu trữ biến cục
[00:36:59] bộ lưu trữ đối tượng. Xong
[00:37:03] đùa đấy. Đây để rồi trao
[00:37:06] cái gì nhỉ?
[00:37:08] Đây chàng này
[00:37:16] thôi.
[00:37:18] Cái gì đấy? Ông bảo tôi tra hình ảnh nào
[00:37:20] cơ? Ông lừa tôi đúng không? Hai bằng
[00:37:22] tiếng Anh. Tra tiếng Anh nhá.
[00:37:25] Ờ. Mem
[00:37:29] memory
[00:37:30] in Java stack and hip đây đúng không?
[00:37:36] Ông bảo cái cái nào dễ hiểu đâu?
[00:37:40] Cái này á cái này cũng tương đối dễ hiểu
[00:37:42] này đúng không? Tương đối thôi.
[00:37:51] dễ hiểu hơn.
[00:37:54] Cứ cho là tôi thích cái con AI gọi là
[00:37:57] mình mình quen thuộc mình thích cái gì
[00:37:59] đó rồi nên mình dễ học thử cái đấy.
[00:38:09] Cái này trông vẽ trông xấu quá. AI của
[00:38:12] tôi vẽ đẹp hơn.
[00:38:19] Ok nha. Ok pro.
[00:38:29] không? Stack là chứa mấy cái
[00:38:35] thôi. Tôi tôi chọn cái này đấy. Stack
[00:38:40] lưu biến cục bộ dễ hiểu hơn mà
[00:38:58] ở trong này rồi mà chiếu thế nãy giờ
[00:39:01] chiếu thế.
[00:39:03] Trong này chắc chắn ta dễ hiểu rồi.
[00:39:10] Mh này.
[00:39:17] tham số đúng không?
[00:39:19] tham số nó là parameter
[00:39:22] của method đúng không? Đặc điểm nhanh tự
[00:39:26] giải phóng khi
[00:39:58] nhìn mấy ông nhìn được màn hình bên này
[00:40:02] vậy chưa
[00:40:04] sao đợi đợi một tí đợi tôi một tí chỉnh
[00:40:07] lạ
[00:40:13] gì đâu nhưng mà kiểu
[00:40:14] Đấy nhìn cho nó kiểu
[00:40:18] tập trung đấy. Cái thế
[00:40:21] th nhìn mặt tôi cũng chẳng quan trọng mà
[00:40:23] mà tự nhiên nó phân tâm thêm một cái
[00:40:25] khác rồi.
[00:40:28] Ok. À tắt cái bên này đi.
[00:40:32] Rồi
[00:40:39] khi ra khỏi hàm. Cái này nó giống memory
[00:40:42] ở trong PP.
[00:40:45] Lỗi phổ biến stack over flow errow đệ
[00:40:49] quy vô hạn.
[00:40:56] chắc là kiểu gọi hàm với hàm thành đệ
[00:40:58] quy thôi đúng không?
[00:41:04] lưu stack h vùng nhớ hip
[00:41:09] là tất cả object new một cái gì đó ok
[00:41:14] sống lâu cần cbage collector dọn dẹp độ
[00:41:19] phổ biến out of memory errow nhiều
[00:41:22] object không thể giải phóng new một cái
[00:41:24] gì gì đó biến p nằm trong stack bởi vì
[00:41:28] khai báo bằng cái gì đó đây đúng không
[00:41:29] biến biến a cục bộ object thì thực sự
[00:41:33] lại nằm trong hip b trò đến địa chỉ ồ
[00:41:37] đấy kiểu trong Java con trỏ hiểu không
[00:41:40] nhắc hình con trỏ nhiều chỉ trỏ trỏ chỉ
[00:41:43] chỉ đấy
[00:41:46] object person nằm trong hip xong cái này
[00:41:51] nó sẽ chỉ bản chất là địa chỉ thôi đúng
[00:41:54] không
[00:41:56] kiểu cái biến trong trường hợp này cái
[00:41:59] này là biến biến á đúng không nhỉ? Nó
[00:42:02] vẫn ừ nó vẫn gọi là biến. Ví dụ truyền
[00:42:05] tham trị và tham chiếu
[00:42:08] nguyên thủy này. Pass by value có copy
[00:42:11] giá trị.
[00:42:14] Cái hàm này
[00:42:16] đổi nó thành 99 đúng không?
[00:42:22] Cái này thì không đổi đúng.
[00:42:25] Trong PP sẽ thế này.
[00:42:36] nguyên thủy đi. Nó kêu nguyên thủy mà
[00:42:38] đúng không? Tất cả m chị ạ học tuy là
[00:42:40] kêu là đều là ngôn ngữ bậc trình à lập
[00:42:43] trình. Nếu mà theo lý thuyết nhá thì đều
[00:42:45] là ngôn ngữ lập trình bậc cao rồi kẻ C+
[00:42:48] cộng 2C nhá. Đúng không? Bậc thấp là
[00:42:51] chắc là Bascan có tính là thấp không? T
[00:42:53] scan này vẫn cao nhưng mà nhớ là có cái
[00:42:55] môn gì trước ở đấy nữa môn quên sử một
[00:42:59] tên rồi đại khái cái trước đấy mới thấp
[00:43:01] kiểu nó có tí nhị phân của em trong đấy
[00:43:03] ấ đấy xong rồi bảng ý nhớ có bảng ai đấy
[00:43:08] kiểu dùng axi code ấy đấy à
[00:43:13] còn à bây giờ là ngôn ngữ lập trình bậc
[00:43:15] cao rồi nhưng mà thực ra về sau nó còn
[00:43:17] phân loại ra nữa đó là cái nào ngôn ngữ
[00:43:19] lập trình tự nhiên nhất bởi vì theo Theo
[00:43:22] như lý thuyết, ngôn ngữ, tập trình.
[00:43:27] Đúng rồi, assembly. Đúng rồi, assembly.
[00:43:28] Đấy, ngôn ngôn lúc đầu nhị phân là chỉ
[00:43:31] máy hiểu đúng không? Xong rồi, đấy là
[00:43:34] ngôn ngữ tầm trung bởi vì là giữa máy
[00:43:38] với máy cũng hiểu một ít. Đấy, kiểu kiểu
[00:43:40] thế nghĩa không cần biên dịch nhiều xong
[00:43:42] rồi người không biết người hiểu tí nào
[00:43:45] không như đại khái người cũng hiểu đấy.
[00:43:47] Chứ người hiểu người mà chỉ nhị phân thì
[00:43:49] đúng là chả hiểu được đúng không? Đấy,
[00:43:52] xong rồi đến ngôn ngữ lập chính bậc cao
[00:43:53] là tương đối dễ hiểu đấy. Nhưng mà nếu
[00:43:56] mà theo lý thuyết như thế thì rõ ràng là
[00:43:58] có những cái ngôn ngữ nào còn dễ hiểu
[00:44:00] hơn so với cái C hay C+ cộng chẳng hạn.
[00:44:04] Đấy, giống như là cứ cho là Scrat cũng
[00:44:08] tính là một kiểu không hẳn là ngôn ngữ
[00:44:10] lập trình nhưng mà sẽ kiểu dạng là danh
[00:44:12] chẻ con học ấy. Tôi không biết phát âm
[00:44:15] chuẩn từ đấy không? Scrap cái gì không?
[00:44:18] Chắc mấy không biết cái kiểu kéo thả để
[00:44:21] mà làm cái gì đó kiểu vòng lặp hay eo
[00:44:25] hay cái gì đó ấy. Đấy.
[00:44:36] kiểm sát ấy không phải thấp kiểu Ừ anh
[00:44:39] hiểu anh hiểu nó đương nhiên Java không
[00:44:41] phải ngôn ngữ lập trình bậc thấp nhưng
[00:44:42] anh đang nói là kiểu nó là nguyên thủy
[00:44:44] tức là chỉ là nó làm kiểu co ấy giống
[00:44:46] như kiểu C hay C+ C+ hay Java nó là cái
[00:44:49] co đấy do anh muốn về học cái kiểu như
[00:44:52] thế như em đang nói đấy nhưng mà
[00:44:55] tính ra là Java vẫn còn dễ học hơn C+ C+
[00:44:58] đúng không? Đấy.
[00:45:02] Thế nên là khi mà mấy người mà cứ hỏi là
[00:45:05] anh từ PP sao không nhảy sang GO, không
[00:45:07] nhảy sang hẳn cái kiểu mới hẳn đi sao l
[00:45:11] nhảy về cái cũ giống như Java mình có
[00:45:13] thể nhảy sang Python hay gì gì đó. Thực
[00:45:15] ra là nó không phải là cái co này không
[00:45:19] phải cái lõ không phải quay về cái
[00:45:20] nguyên thủy này đúng không? Khi mà mình
[00:45:22] quay về cái này xong rồi như em đang nói
[00:45:23] là mình học mấy cái này xong mình nhảy
[00:45:25] sang cái khác nó lại dễ đấy. Giống như
[00:45:28] kiểu mình học PP là đang học ở lá đúng
[00:45:31] không? Xong mình đi về. Đi về gốc thì nó
[00:45:33] hơi quá nhưng mình đi về cái đoạn cành
[00:45:36] hay thân đã xong rồi từ thân lại nhảy về
[00:45:38] lá khắc thì nó sẽ dễ đấy. Nhờ
[00:45:44] thế nhảy nhảy nói chung là cái này lúc
[00:45:47] đầu bằng 5 này vào hàm này. Hàm này tuy
[00:45:49] thay đổi giá trị cho nó nhưng mà nếu mà
[00:45:52] trong PP có cái trò là kiểu dùng dấu con
[00:45:55] trỏ như này để mà trỏ đến a cái giá trị
[00:45:59] ơ trong này trỏ được đúng không? này tôi
[00:46:01] chưa cài gì nó không báo gì cả chắc là
[00:46:04] tôi chưa cài. Đấy con trỏ này xong rồi
[00:46:09] thài tự nhiên được gán giá trị. Nói
[00:46:11] chung là cái đấy hơi vi phạm quy tắc bởi
[00:46:13] kiểu nó không nó gọi là không clean code
[00:46:16] đúng không? Cái blackit đấy không ổn
[00:46:18] đúng không? Đấy tự nhiên kiểu thằng này
[00:46:22] đang bằng năm xong rồi qua một cái hàm
[00:46:23] tự nhiên thằng này bằng số khác.
[00:46:26] có cái trò đấy không biết trong này có
[00:46:29] không? Tôi nghĩ là có khi có
[00:46:36] ơ đúng rồi này. Object object truyền vào
[00:46:38] nó thay đổi đúng trong PP thì cũng đúng
[00:46:41] truyền vào chạy xong hàm xong đúng
[00:46:44] object cũng thay đổi thật.
[00:46:53] thể
[00:46:59] hàm này nó kiểu nó trỏ thẳng vào cái h
[00:47:03] để mà sửa sửa giá trị đúng không?
[00:47:08] Còn cái a
[00:47:11] có thằng này có cái cùm trò đến
[00:47:19] Ok, hợp lý đấy.
[00:47:32] bộ. Đây là khai báo kiểu global là toàn
[00:47:35] toàn cục này. Đấy thì sẽ nằm trong í. Ok
[00:47:40] được cái đoạn này hiểu
[00:47:43] stack là để nó giống kiểu RAM à kiểu
[00:47:46] kiểu thế đi là kiểu là kiểu truy cập
[00:47:49] nhanh và
[00:47:51] chắc là nó sẽ hạn chế kiểu
[00:48:02] cộng
[00:48:04] thì sao mà tường minh bằng được
[00:48:09] ha.
[00:48:15] thứ thứ hay như nào? Thôi chưa hiểu cái
[00:48:17] đấy lắm. Hay là ý ông là kiểu cộng cộng
[00:48:20] nó từng minh nhất đúng không? Đúng. Nếu
[00:48:22] mà tôi nhớ hồi đấy là người ta bảo là
[00:48:24] hồi mà tôi học à trên đại học à thế là
[00:48:27] tôi không học đại học cao đẳng về mua là
[00:48:31] lập trình thì đương nhiên là nhắc đến
[00:48:33] bài con trỏ thì người ta sẽ kiểu dạy ở
[00:48:36] trong C+ cộng hơn là họ dạy dạy trong
[00:48:39] Java
[00:48:49] học bên Java này cũng tương đối để
[00:48:52] Hiểu được rồi đấy. Thực ra nội dung một
[00:48:55] buổi một ngày thực ra ngồi chém gió hơn.
[00:48:59] Ngồi chém gió bao lâu nhỉ? Ngồi sửa cái
[00:49:02] kia. Ngồi chém gió cái kia cũng phải
[00:49:05] à bây giờ khoảng thời gian rồi. Tôi còn
[00:49:09] đang không xem được thời gian. Đại khái
[00:49:12] là ngồi
[00:49:17] ra là mới
[00:49:21] đây ngồi chém gió tầm gần 1 tiếng đồng
[00:49:23] hồ đấy từ 7 gi
[00:49:25] nhưng mà thực ra là chỉ học mọi thứ rất
[00:49:27] là nhanh nhở.
[00:49:35] không biết cái sao cơ. Trong PP sao nó
[00:49:39] chỉ là nhân thôi. Còn dấu và kia là con
[00:49:44] trò thì tôi biết trong PP còn trong Japa
[00:49:46] tôi cũng chưa dùng. Đấy. Tôi tôi cũng
[00:49:50] không muốn. Trong PP tôi đã cố hạn chế
[00:49:53] dùng con trỏ rồi. Nó không tốt lắm.
[00:49:56] Chẳng qua là có những lúc là phải dùng
[00:49:58] để mà kiểu tối ưu cứ cho thế đi. Kiểu
[00:50:00] bất đắc dĩ đi. Đấy. Hồi trước là có lạm
[00:50:03] dụng nhá. Hồi trưa kiểu khi biết lạm
[00:50:05] dụng kiểu hồi đấy sai kiểu hồi đấy ngựa
[00:50:07] non háo đá kiểu dạng là cứ cho là nhìn
[00:50:11] thấy nó ngầu nhìn thấy nó ngắn hay vân
[00:50:13] vân. Đấy, thử sử dụng rapper class.
[00:50:17] Có bài buổi một học rồi đấy. Còn bây giờ
[00:50:20] để áp dụng thì tôi nghĩ là sẽ có buổi
[00:50:23] vừa nãy có ông em bảo là mới comit lên
[00:50:26] bài tập
[00:50:29] nhưng mà trước mắt thì tôi nghĩ là tôi a
[00:50:31] đang học theo kiểu cứ cho là học cưới
[00:50:34] ngựa xem hoa cũng đúng đi bởi mình vẫn
[00:50:36] đang chỉ học lý thuyết chưa làm bài tập.
[00:50:39] Giờ tôi đang a
[00:50:42] hay để ngồi nghĩ bài tập nhỉ đúng không?
[00:50:44] Cái này chưa tính là bài tập. Cái này
[00:50:45] chỉ demo thôi để cho hiểu thôi nhỉ.
[00:50:49] Ông em vừa nãy có cho tôi bài tập nhưng
[00:50:51] tôi chưa biết được là sẽ là bài về
[00:51:20] số sau khi truyền biến vào method.
[00:51:33] in khác gì? Ồ để tôi thử hỏi câu đấy
[00:51:37] xem. Câu hỏi hay đấy. Cảm ơn ông nhá.
[00:51:40] Được. Tôi cũng thắc mắc cái đấy luôn.
[00:51:42] Xem thử.
[00:51:51] anti Gravity Kit. Tôi sẽ khoe mấy ông.
[00:51:54] Không biết là mấy ông a biết cái khái
[00:51:57] niệm kit này của trong a trong cái AI.
[00:52:00] Tôi thỉnh gần đây cứ cho là tôi bị
[00:52:04] không phải FOMO vẫn là bị cái gì nhỉ? Bị
[00:52:06] cuồng cái gì đó đi. Nghĩa làm gì ạ? Tôi
[00:52:08] đang bị rất là cuồng ai đi. Tuy là hồi
[00:52:11] trước là tôi đã không quan tâm về hồi
[00:52:13] trước đặc biệt hồi cứ cho là hồi dùng à
[00:52:16] IDE à trên đi e là đủ ấy. Kiểu PP Storm
[00:52:20] ấy là nhất đủ rồi. Không cần phải cùng
[00:52:23] nó một cái th vài cái tiện ích gợi ý
[00:52:24] thôi chứ không phải kiểu chạy đua xem AI
[00:52:27] thông minh hơn hay là mình kiểo vân vân
[00:52:30] ấy. Nhưng mà bây giờ là cũng để ý hơn và
[00:52:33] cũng dùng hẳn những con nào mình thực sự
[00:52:35] mình cảm thấy tốt. Đấy ví dụ bây giờ
[00:52:38] chuyển mấy ông thấy luồng hồi trước tôi
[00:52:40] từng chia sẻ chuyển qua luồng khá nhiều
[00:52:42] ấy thì và bây giờ còn nhắc đến cả Asian
[00:52:47] skin nữa tôi cũng có nghe nhiều bởi vì
[00:52:49] tôi tham gia mấy cái nhóm nhận đến AI
[00:52:52] nên là nó cũng bị tác động tâm lý nhiều
[00:52:54] ấy kiểu mọi người dùng ai cũng dùng ai
[00:52:57] cũng ai cũng nhắc đến đấy cứ cho mình
[00:53:01] phô à đấy kiểu thế mình sợ bị bỏ rơi
[00:53:04] đúng không sợ bị lỗi thời Mình ở dân
[00:53:07] công nghệ mà. Đấy, xong rồi mình cũng
[00:53:08] tìm hiểu xong rồi thấy là ừ nó về cơ bản
[00:53:11] thứ nhất nó miễn phí đấy nhá. Chưa nạp
[00:53:13] đồng nào cả. Đấy, cái thằng này thì cái
[00:53:17] này thực ra là để mà nói giải thích dễ
[00:53:20] hiểu hơn thì ra nó cũng chỉ là viết hộ
[00:53:22] cho mình prom và ngoài ra đương nhiên là
[00:53:25] có thể viết prom hoặc là nó tự động chạy
[00:53:26] thêm một cái gì đó nữa nhưng mà bản chất
[00:53:28] là mình vẫn thể làm à tự làm điều đấy.
[00:53:32] Chẳng qua là bây giờ nó tự động chạy cho
[00:53:34] mình.
[00:53:35] Đấy,
[00:53:37] thằng antiravity này nó mới có và tôi
[00:53:40] đang dùng antiravity
[00:53:46] mục để mà lưu vào. Mỗi tội là mình phải
[00:53:49] tự tạo. Và thằng antiity này có có một
[00:53:55] người Việt luôn vừa mới chia sẻ.
[00:53:58] Đây là
[00:54:01] antiravity kit đây đang miễn phí nên là
[00:54:06] cảm thấy hay phết. Tôi dùng link
[00:54:10] công nhận J2 kiểu sale tốt phết. Nhìn
[00:54:13] này. Cái này Facebook không nói nhá.
[00:54:17] Trang này mấy trang này ok J2 lên mà
[00:54:20] trong khi đó là cái thằng này nó lại
[00:54:23] chuẩn là phải hit hub phải đứng đầu.
[00:54:25] Theo tôi thì thế vì rõ ràng là anh em
[00:54:28] cộng đồng mà đây hit hub còn chưa nhìn
[00:54:30] thấy đúng không? Vẫn chưa thấy cái hitub
[00:54:33] nào đây. Uầy vợ chiều nay 300 giờ lên
[00:54:37] 400 nhanh phết.
[00:54:40] Thì đầu tiên là anh em a trên này có rất
[00:54:43] nhiều cái skin nghĩa là đại khái là nếu
[00:54:46] mà để đọc skin đây để tôi thử cài cho
[00:54:48] mấy ông dễ hình dung. Thế là coi như là
[00:54:50] xong bài hôm nay học rồi nhá. À đâu chứ
[00:54:53] ông kia nói nữa nhưng mà đợi đợi tí tôi
[00:54:56] chia sẻ vì t tự nhiên tôi nhắc đến hàng
[00:54:58] ngày nên là tôi cứ bị cuồng chia sẻ.
[00:55:02] Đợi tí đợi tôi nhận thích thoảng hơi
[00:55:07] gọi nhở lặc đề một tí. Tôi cài cái này
[00:55:10] rồi xong bây giờ chỉ cần CD vào thư mục
[00:55:13] mình xong rồi cài thêm cái này.
[00:55:16] Đấy để tôi thử chạy thử demo mấy ông
[00:55:18] nhé.
[00:55:28] cũng chỉ học thôi. Tôi nhớ có mỗi hôm
[00:55:30] đầu tôi nói nhiều nhất bởi vì hôm đầu
[00:55:32] tôi học hai bài.
[00:55:39] thôi.
[00:55:47] Nhưng mà qu tôi vẫn lười hơi. chưa có
[00:55:49] bài tập và chưa làm
[00:55:51] gì nhỉ? Cái mình đang bên CD bên a Java
[00:55:56] đây. Tôi ngồi gõ cho mấy ông luôn.
[00:56:00] CD này, Java này.
[00:56:03] Đấy, xong rồi chạy cái lệnh này đúng
[00:56:05] không?
[00:56:12] Tôi vừa nãy tôi cài rồi. Hãy cài thử
[00:56:15] trước.
[00:56:16] Đấy. Đấy. Xong rồi. Thực ra là bản chất
[00:56:18] là nó sẽ tạo cái thư mục như này.
[00:56:23] Đấy. Thư mục này có đầy đủ. Nếu mà ông
[00:56:25] đọc kỹ vào thực ra nó file MD thôi. Đây
[00:56:28] là như này. Nó là bản chất là một cái
[00:56:30] prom để cho
[00:56:39] hơi ít quá.
[00:56:46] là
[00:56:49] skill và ru và agent. Agent thì tôi chưa
[00:56:54] biết nhưng tôi chỉ biết được là ru này,
[00:56:57] skill là con AI này nó sẽ tự động đọc
[00:57:01] của ông. Nó tự động đọc. Đây ông có thể
[00:57:03] vào xem nhá. Đấy cái này tôi để có lobal
[00:57:06] mặc định không nó làm gì nhá. Đây nó tự
[00:57:09] động đọc cái ru ở trên mini này. Đấy mà
[00:57:13] skill thì tôi thấy là chưa có cái giao
[00:57:15] diện của thằng Anty hiển thị ra. À tôi
[00:57:20] ăn ăn rồi. Tôi ăn rồi mới dậy được không
[00:57:22] hết sức mất. Đấy nhưng mà cái workflow
[00:57:25] này là gì? Tức là chỉ là đây nó sẽ kiểu
[00:57:29] cứ cho luồng luồng hoạt động đến một cái
[00:57:32] gì đó đi. Ví dụ giả sử giả sử tôi demo
[00:57:35] luôn ông thể khai báo brainstorm như
[00:57:38] này. Đấy động não đúng không? Cứ cho
[00:57:41] brainstone và động não. Đấy xong rồi. À
[00:57:45] đợi tí tôi ghim cái này lại nhé. Đợi tôi
[00:57:48] một tí. Ok. Ờ vậy đang nói gì nhỉ? Ông
[00:57:52] kia hỏi về cái trên này đúng không? Ok.
[00:57:58] À có bạn tôi tìm hiểu về
[00:58:05] đây
[00:58:08] sửa trong file này cho tôi. Giả sử dùng
[00:58:13] Gini nhá. Bình thường tôi không thích
[00:58:14] con JM này lắm. Bình thường tôi dùng
[00:58:15] Cloue anh em biết Cloude code tốt hơn
[00:58:17] đúng không? Nhưng mà trong vài trường
[00:58:19] hợp con Jini này, thứ nhất là cái lượng
[00:58:21] con lượng contexech của nó, token của nó
[00:58:25] đang lớn nhất triệu thì phải. Mấy thằ
[00:58:26] kia có 100.000 hoặc là 200.000 thôi.
[00:58:29] Đấy. Thứ hai là
[00:58:32] về đọc về làm giao diện và đọc tài liệu
[00:58:35] thì tôi thấy con này đang tốt. Và thứ ba
[00:58:38] nữa đó là nó bởi vì trong cái bộ này nó
[00:58:42] đang viết được cho con Gemini rồi. Còn
[00:58:45] những con a kia thì có vẻ đang chưa
[00:58:47] viết. Có có vẻ tức là mấy con này vẫn
[00:58:49] đọc trung hết cái tài liệu này thôi
[00:58:51] nhưng mà tài liệu này vẻ đang truyền cho
[00:58:53] con Jindi. Thì mình thử nhỉ? Thử nhá.
[00:58:57] Đấy.
[00:58:59] Ok không? Ơ à gọi đến này. Thực ra bản
[00:59:03] chất là nó cũng gọi đến cái file MC down
[00:59:05] thôi. Ok cũng hiểu
[00:59:09] đây. Thì tôi thích dùng anti gravity bởi
[00:59:11] vì nó luôn hiển thị cái luồng nó đang
[00:59:13] nghĩ đang làm cái gì đó như này khá là
[00:59:15] hợp lý. Nếu mấy ông biết tiếng Anh đây
[00:59:18] nó sẽ cập nhật cho một cái T thường là
[00:59:21] một cái gọi là checklist to do list. Đấy
[00:59:24] đôi khi nó hiện tôi dùng cái chế độ plan
[00:59:26] này nữa nó sẽ lên có một vài trường hợp
[00:59:29] là nó sẽ lên hẳn một cái plan, một cái
[00:59:32] kiểu một cái kế hoạch để mình có thể
[00:59:35] kiểu xác nhận confirm đúng không? Thậm
[00:59:38] chí là mình com comment vào là mình nên
[00:59:40] làm cái à đây đây ví dụ plan này này.
[00:59:43] Đấy kiểu như này comment vào là kiểu như
[00:59:47] nào đấy abc vào đây để nó làm chuẩn hơn.
[00:59:50] Đấy khi như này xong rồi mình sẽ proceed
[00:59:53] mình sẽ bấm đôi khi là để nó tự động cái
[00:59:56] này được nhưng nhiều cái thì nó vẫn mình
[01:00:00] vẫn nên theo theo tôi mình vẫn phải xem
[01:00:04] xác thực qua rồi mình mới post.
[01:00:14] không? Nói giải thích rõ đấy. Demo
[01:00:29] tạo ra object mới không sửa object cũ.
[01:00:44] này. Đợi tí đợi tí.
[01:00:48] Nhưng cái kiểu này là bất biến nên là
[01:00:51] không thay đổi giá trị của object cũ
[01:00:55] tạo ra một object mới và gán cho biến
[01:01:00] này là local.
[01:01:03] Ồ
[01:01:18] đúng cái này nói chung là B thì vẫn là B
[01:01:21] không đổi. Cái này tôi hiểu à
[01:01:31] nó là bất biến nên cái này là 88.
[01:01:40] này gán vào
[01:01:43] nó tạo một object mới và gán là biến
[01:01:46] local. Tức là con này nó sẽ vào stack
[01:01:49] đúng không?
[01:01:58] con này vẫn sẽ là 88 nhưng mà con 88 này
[01:02:01] nó sẽ là
[01:02:04] gọi là như nào nhỉ? Nó là một object mới
[01:02:07] và nó ở trong
[01:02:11] stack à đâu trong h đúng rồi. Cái con a
[01:02:16] con này phải trong h chứ nhở new mà đúng
[01:02:18] không? Nó new một object mà
[01:02:33] khái là theo tôi hiểu nhá là trong híp
[01:02:37] vẫn còn cái con
[01:02:39] đấy đúng rồi không không không không
[01:02:41] không không không không không không
[01:02:41] không không
[01:02:43] à đúng hai con hai con chứ sao đổi được
[01:02:46] không?
[01:02:49] Thế để tôi thử hỏi đây nhá.
[01:02:51] Ờ
[01:03:00] Vậy giờ trong hit có
[01:03:06] hai object
[01:03:09] 10 và
[01:03:11] 88 hay
[01:03:33] con này đang trong này là 10 rồi này.
[01:03:37] Con này đang là trong híp rồi đúng
[01:03:41] không?
[01:03:47] công ty không anh?
[01:03:58] trên 17 triệu. Nếu mà đi thực tập một
[01:04:01] đoạn trên 17 triệu thì ừ giống như bạn
[01:04:04] kia nói công ty lo
[01:04:06] thường công ty lo
[01:04:09] bao nhiêu phần trăm ấ tôi không nhớ lắm.
[01:04:12] Tùy thường công ty ấy bạn phải deal với
[01:04:14] công ty vì có khái niệm lương road với
[01:04:17] lương lương gì đó nữa
[01:04:20] câu chảy là gọ có hai object tại thời
[01:04:23] điểm dòng code chạy giá trị 10 đang được
[01:04:26] biến B ở trọ đúng rồi đúng rồi cái này
[01:04:29] biết nó đang ở trên này vốn dĩ nó đang ở
[01:04:31] trên này N
[01:04:49] nếu tôi đổi đâu anh ngồi ở công ty đổi
[01:05:04] thì
[01:05:07] sao?
[01:05:15] Đúng rồi. Biến 88.
[01:05:28] memory sẽ thay đổi hoàn toàn.
[01:05:30] Khi mà gọi kiểu này sẽ tự động
[01:05:34] lấy số 10 ra xong rồi biến vào. Đấy thì
[01:05:37] trong trường hợp này cái này nó sẽ lưu
[01:05:39] vào stack đúng không ạ? Biến Nguyễn Thủy
[01:05:41] hoàn toàn nằm trong stack, không lưu vào
[01:05:42] trong híp nữa.
[01:05:52] sau cô áp dụng nhiều không.
[01:05:55] Ok, cảm ơn ông nhá. Ví dụ rất hay, rất
[01:05:58] đúng lúc.
[01:06:06] đập đoạn này đau đâu.
[01:06:09] Đây, tôi sẽ truyền lên a
[01:06:19] để mà hôm sau hôm sau buổi năm là còn à
[01:06:23] buổi xă buổi năm có rồi này.
[01:06:27] Bắt đầu từ buổi sáu là cũng phải ngồi
[01:06:28] soạn lại dạng các thứ thứ thử. Hôm nay
[01:06:31] thực ra chỉ cần livestream thôi mà tuy
[01:06:33] có ít người xem nhưng thực ra là
[01:06:36] thựt ra là mấy ông tôi tin là mấy ông
[01:06:38] vẫn có xem lại và có những ông ngồi học
[01:06:41] đồng hành cùng tôi bây giờ đang có nhiều
[01:06:43] ông bình luận buổi một cơ.
[01:06:45] Thế là ổn rồi.
[01:06:48] Thôi tôi cũng chuẩn bị té đây. Ui mày
[01:06:51] đau đầu mệt.
[01:06:54] Mấy ông còn tâm sự gì nữa không ạ? Không
[01:06:57] tâm sự tôi tạm comit lên nhá. Tôi không
[01:07:00] phải sửa nhiều phết tôi sẽ ghi đã. Ờ
[01:07:05] update
[01:07:13] tôi sẽ như này một cái riêng một cái
[01:07:16] này. Còn cái này sẽ là bỏ bỏ đi đúng
[01:07:19] không? Sẽ là
[01:07:22] remove un đấy. Xóa những cái không sử
[01:07:25] dụng không có tâm.
[01:07:28] Tú xem á. Chắc là anh có tuy là bình
[01:07:31] thường thực ra là anh
[01:07:34] không biết được mọi người đã từng kể mọi
[01:07:36] người chưa nhưng thực ra hồi trước là
[01:07:37] tôi từng không thích bóng đá lắm vì rất
[01:07:39] rất nhiều lý do đấy
[01:07:42] nhưng đế như là vẫn có lòng yêu nước và
[01:07:45] xem cùng mọi người xem bóng đá kiểu
[01:07:47] không khí của mọi người rất là vui. này
[01:07:51] ông kia bây giờ mới bình luận á. Thôi
[01:07:53] tôi nghỉ rồi để ông khác nhá. Để ông
[01:07:56] khác ông bình luận ông comment hẳn vào
[01:07:59] trong git của tôi đi. Ông đến lúc ông
[01:08:03] comit vào trong git của tôi rồi. Ông anh
[01:08:05] em nhìn thấy git mà đúng không?
[01:08:08] Tôi chia sẻ link git đi mấy ông thấy
[01:08:10] chưa nhỉ?
[01:08:13] Git hub nhá.
[01:08:21] trên git hub của tôi có đấy
[01:08:24] có không nhỉ có không tôi vẫn chẳ biết
[01:08:27] cơ
[01:08:30] thôi cái gì
[01:08:32] chăm chỉ lên chúng ta cùng học cùng giúp
[01:08:35] nhau tốt lên đấy ờ gì nhỉ nói gì đấy nói
[01:08:41] chung là xem
[01:08:43] xem bóng đá cùng mọi người cùng không
[01:08:44] khí vui và đặc biệt là đã thấy còn mấy
[01:08:46] lần tôi xem ví dụ năm ngoái tôi xem nhá
[01:08:50] à năm ngoái xem vô địch ừ vô địch à châu
[01:08:55] Á đấy xong rồi vô địch SEA Game vừa rồi
[01:08:58] đúng không? Đấy, vẫn nhớ mà. Đấy, nên
[01:09:01] hôm nay tôi nghĩ là tôi có vía đấy. Chắc
[01:09:03] là tối có thể xemấy.
[01:09:06] Còn nếu mà tối nay mà à thôi không nói
[01:09:09] gì, tốt nhất không nên nói gì cả.
[01:09:12] Nhưng
[01:09:14] với với ai à
[01:09:20] cập nhật. Đây chỉ cần ghi cập nhật là
[01:09:22] được.
[01:09:24] Ok. Đẩy lên.
