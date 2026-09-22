# Lập trình web chuyên sâu - 16 - Laravel - Session & Middleware

- Video ID: `zYvwN3oiFzM`
- URL: https://www.youtube.com/watch?v=zYvwN3oiFzM
- Published: 2022-04-19
- Duration: 1h 53m 17s (6797s)
- Language: vi
- Subtitle source: auto
- Kind: live

## Transcript

[00:00:30] alo alo
[00:00:32] anh Alo ạ
[00:00:52] alo
[00:00:57] nghĩ hỏng kiểu tự nhiên giờ không kết
[00:01:00] nối được với con à Mày tính nữa nên là
[00:01:02] bây giờ tôi đang dùng con tai nghe kết
[00:01:04] hợp với Mike là
[00:01:07] cái con tai nghe tôi bảo con cái này
[00:01:10] ngoài con đi
[00:01:11] tra xem con tai nghe đâu nhé ra nó về Hà
[00:01:14] Nội Computer
[00:01:15] Cái con này này này là con đang nghe từ
[00:01:18] công ty tôi công ty tôi tặng gọi là công
[00:01:22] ty tôi mua cả già máy tính cho anh em ấy
[00:01:25] có có cả con tai nghe này
[00:01:29] mua Hà Nội dạy mà công
[00:01:33] nghệ sĩ Phải chăng đây Con con ạ Alo 400
[00:01:38] đã hết
[00:01:39] Anh ơi sao
[00:01:54] hình như con này
[00:01:57] anh
[00:01:59] đợi tôi đang xem con hả
[00:02:02] Bây giờ không bán nữa nhỉ Nó có mic chỗ
[00:02:06] nào Chỉ cần vài trăm thôi như con này
[00:02:09] bốn trăm thật đấy nó có cả mic chồng
[00:02:14] không đẹp nha con nào nhỉ 2
[00:02:18] các bạn nữa lại phải đấy con này Đấy là
[00:02:23] 400
[00:02:24] giờ nó có cả mic nhưng mà nó không thực
[00:02:27] sự là
[00:02:28] nó không chuyên rồi một cái không hi
[00:02:31] vọng được là nó sẽ chị không ạ Không
[00:02:34] nghe rõ mà alo alo nghe ổn đúng không
[00:02:37] Không bị lỗi cậu
[00:02:40] có bị bé của ông nó bé quá Tôi sẽ thường
[00:02:44] chưa nói to
[00:02:45] bé đúng không làm sao tính ra tôi một
[00:02:50] con người hơi bị ngược một tí tôi
[00:02:54] Hà bị rè anh về thì à anh nghe tôi tôi
[00:02:59] vừa nói đấy con tai nghe này nó rẻ tiền
[00:03:02] đấy là thực ra là
[00:03:04] nên là không kiểu dạng là không Xịn về
[00:03:07] cái khoản thu âm nó đâu phải chịu thôi
[00:03:11] con
[00:03:20] vì thực ra tôi là con người à Ăn bé nói
[00:03:24] to
[00:03:25] không ạ ăn to nói lớn đấy thì ngược lại
[00:03:29] là ăn Ăn bé nói lớn từ thế với ăn chọn
[00:03:33] kiểu hỏi chậm Nhưng chúng tôi nhai kĩ
[00:03:36] cái được là tôi không hẳn là một người
[00:03:39] thăm ăn nhiều lắm nhưng mà tôi được cái
[00:03:43] mồm Kha to ngày ra là
[00:03:45] tôi có thể hoàn toàn bạn luôn coi được
[00:03:48] Thậm chí tôi dậy ở trên trên lớp như dạy
[00:03:52] trên lớp thì không cần phải dùng mic hay
[00:03:55] gì cả nhưng mà anh nói cho bạn là tôi
[00:03:58] từng nói rất to ở trong khó khăn hát bài
[00:04:01] không cần mic đây là tôi tự tin là tôi
[00:04:04] có thể nói to được con Lê khoản nó trong
[00:04:08] vòng 2 tiếng thì cũng biết là tôi sợ ồn
[00:04:11] ảnh hưởng người khác rồi tôi đóng cái
[00:04:13] cửa đợi công ty à
[00:04:33] ok Nói chung là tranh thủ mình tâm sự
[00:04:36] một tí hôm trước chưa tâm sự mấy thì hôm
[00:04:39] nay có tâm sự rất nhiều
[00:04:41] rất nhiều cảm xúc kiểu cả buồn vui đùa
[00:04:45] cả tôi sẽ cho ông xem cái này đầu tiên
[00:04:48] đã
[00:04:59] [âm nhạc]
[00:05:51] Ừ cái này tôi thấy rất là hai kiểu Đây
[00:05:55] là cậu lớp tiểu học và tôi nhớ là hồi mà
[00:06:00] tôi đã xem không biết là bây giờ thay
[00:06:02] đổi không đó là bên Nhật bên nhập thì à
[00:06:06] tiểu học lớp 1 lớp 2 lớp 3 gì vậy và
[00:06:10] không thi cử gì cả họ sẽ học cái gì họ
[00:06:13] sẽ học à lịch sử văn hóa các thứ thứ của
[00:06:17] Nhật
[00:06:18] nói chung là kiểu văn hóa dân tộc chứ
[00:06:21] không phải là học kiểu dạng là thế là
[00:06:24] cũng học chữ viết nhưng mà không học các
[00:06:26] môn Toán học cái gì đó kiểu phức tạp cả
[00:06:29] học rất đơn giản bạn trai thi cử thì cả
[00:06:31] khá là dạy cho người ta có lòng tự tôn
[00:06:35] ông ấy ông ấy thì thế tự học sự tiểu học
[00:06:41] bây giờ bảo mấy ông nhớ được là mấy ông
[00:06:43] đã học những cái gì mà còn đã thi Bởi vì
[00:06:45] nếu mà chả nhớ ông làm gì qua môn làm
[00:06:49] sao được điểm cao như thế đúng không ạ
[00:06:50] Cứ ngờ Ừ để học cộng trừ nhân chia thì
[00:06:53] có vẫn còn nhớ đến bây giờ thì vẫn nhớ
[00:06:55] nhưng mà
[00:06:57] sự thì
[00:06:59] đối với tôi con điểm ấy Tôi không biết
[00:07:03] từng nói với ông chưa
[00:07:04] rồi Tôi ôm lấy tôi con Điệp kìa tôi sẽ
[00:07:08] không hướng đến con của tôi về sau giỏi
[00:07:11] con có thể là mình có thể ra gì đấy có
[00:07:15] thể về cho mình ra gì Yêu cầu là người
[00:07:17] người có địa vị người có tiếng nói vẫn
[00:07:19] vật mình gọi là cứ thành công đi Nếu tôi
[00:07:22] ở không mong con của mình về sau là một
[00:07:25] con người cậu thành công nối nghiệp mình
[00:07:26] ai gì đó tôi chỉ muốn con mình kiểu đúng
[00:07:30] nghĩa là nên người theo các loại biết
[00:07:32] ứng nhân xử thế nóng và không biết cách
[00:07:34] cư xử được đọc nó đến chết
[00:07:36] sẽ Thả nào tôi sẽ phải
[00:07:39] dạy nó cách cư xử với người khác đối xử
[00:07:42] với tất cả mọi người
[00:07:44] ai biết cách nói chuyện Nói chung nhà ở
[00:07:47] Nói chung là không hẳn là giả tạo tôi ra
[00:07:50] Tôi rất ghét luôn người tạo ở chung nhà
[00:07:52] mình mình thì à
[00:07:54] a nhôm cái tắt của mình đối tốt không
[00:07:57] hiểu biết đúng sai không ạ còn tốt hơn
[00:08:01] chắc là tôi sẽ tôn trọng nó kiểu là nó
[00:08:04] muốn gì Nó đã phân biệt đúng sai rồi nó
[00:08:06] muốn vì để việc của nó mình không cản gì
[00:08:10] cả nhưng mà còn à cách kiểu Dạ
[00:08:14] không tôi không quan tâm với việc nó
[00:08:17] không hàng như thế nào
[00:08:18] đấy quà trong trong cái video này thì
[00:08:21] thầy đang dạy cho học sinh cách kiểu
[00:08:26] kiểu giả chỉ nói đơn giản một câu thôi
[00:08:29] con yêu mẹ đúng không ạ Đấy đã bao lần
[00:08:33] bao lâu rồi Mấy ông chưa nói những cái
[00:08:35] đấy bố mẹ của mình ạ lần gần đây nhất
[00:08:39] tôi đi tham gia cũng đi đa cấp người ta
[00:08:41] cũng yêu cầu bỏ tôi gọi điện cho bố mẹ
[00:08:44] chúng mày nói cái này xong rồi mở nhạc
[00:08:46] kiểu Mở nhạc của xin tất cả đơn lên đấy
[00:08:51] nhạc rất là buồn xong rồi à Ừ ai cũng
[00:08:56] khóc hay cười thế thì khi mà người ta
[00:08:59] động và lòng trắc ẩn Kiểu cái lòng trắc
[00:09:02] ẩn của ông thì ông dễ nghe hơn ông vợ
[00:09:07] trong lúc người ông cảm xúc dâng trào ấy
[00:09:09] bị nhớ hơn sẽ nhớ những điều người ta
[00:09:12] nói đấy
[00:09:14] cách tán gái cũng như thế đấy cầm dài sẽ
[00:09:17] nhớ những gì ông đã làm chứ Nhớ những gì
[00:09:20] ông đã làm cho họ cảm thấy chứ không nhớ
[00:09:23] những gì ông đã làm đâu đấy Ông có thể
[00:09:27] là cây rất nhiều cái sai lầm rất nhiều
[00:09:30] lỗi lầm về mặt lô rách thì nó sai hoàn
[00:09:32] toàn nhưng con gái thì ra không nghĩ
[00:09:34] không nghĩ về lôgic mấy Dạ không nhớ
[00:09:37] những điều đấy mà 13 nhớ cảm xúc của ông
[00:09:40] đẹp lại người ta nên là ông mà làm được
[00:09:44] người ta có rất nhiều cảm xúc lần gần
[00:09:46] đây nhất tôi đi hẹn hò
[00:09:49] tôi chẳng ở xa tôi à
[00:09:51] không hiểu hôm đấy là nói chuyện về có
[00:09:54] dính vào da các
[00:09:55] bạn đấy à Tốt nhất là ngồi nói chuyện đã
[00:09:58] khóc cơ tôi không kiếm lại khóc nha Trả
[00:10:01] qua nói chuyện gia đình bạn nhớ bố mẹ và
[00:10:03] khóc và sau lần ấy bạn rất ấn tượng với
[00:10:06] tôi bởi vì à Kiểu khi mà có quá nhiều
[00:10:09] cảm xúc rồi Họ sẽ nhớ mình hơn
[00:10:12] đấy Đấy là lý do mà tôi dậy cho mấy ông
[00:10:15] đổi từng ngày tâm sự Tôi muốn cho gần
[00:10:17] gũi mời ông bà có những cái cảm xúc như
[00:10:19] thế này nữa thì bé ông sẽ nhớ được toàn
[00:10:22] bộ những cái thứ hơn khi mà ông đã có
[00:10:25] cảm xung kiểu gọi là hâm nóng hâm nóng
[00:10:27] gọi kiểu thế
[00:10:30] thì ông sẽ cảm xúc hơn thay vì tôi dạy
[00:10:33] cho ông đeo đeo đeo cái giọng đều đều
[00:10:35] thì ông sẽ đỡ buồn ngủ vào không nhớ gì
[00:10:38] cả ông khéo một bộ phim hay là bộ phim
[00:10:41] cậu có gây gây cho ông cảm xúc
[00:10:44] ạ tình cảm ông có tình cảm với tội được
[00:10:48] và tình cảm kiểu muốn về chung nhà được
[00:10:51] ở nhà tôi không đủ chỗ đâu ạ đề
[00:10:55] thi ở ba cái video này tôi hãy Thế hai
[00:11:00] điểm nữa đó là em bé này những người lớn
[00:11:04] Mình thực ra rất khó nói rồi Tại sao thì
[00:11:06] mình có cái tôi Nhưng mà Mấy ông đấy kỹ
[00:11:10] Mấy em kia thì đang đùa cười có thể mà
[00:11:14] em kia chưa bị gọi lên kiểu ngày hoặc là
[00:11:16] gọi rồi nhưng mà thấy ra bình thường
[00:11:17] kiểu trẻ con mình nói cái từ yêu bố mẹ
[00:11:21] rất là bình thường đúng ạ
[00:11:23] nhưng mà gái em này thì khác em hãy đã
[00:11:26] cảm thấy mấy cái từ đấy giờ tương đương
[00:11:28] và quan trọng rồi em phải nói rõ là thật
[00:11:31] lòng đúng không ạ và kiểu
[00:11:34] kịch kể Tôi thích kiểu con người như này
[00:11:37] trở dạ nhà người ta thấy bật khóc nhưng
[00:11:40] mà nó một cái gì đó mang phía con trai
[00:11:42] nhưng mà thực ra là tôi từng nói đó là
[00:11:44] có người mạnh không phải là người không
[00:11:47] không bao giờ khóc mà người mạnh là
[00:11:50] người có rất nhiều cảm xúc rất nhiều cảm
[00:11:52] xúc Đấy và cảm xúc họ rất là mạnh ấy Đấy
[00:11:57] đấy là người mạnh họ sẽ hiểu
[00:12:00] Khi mà họ đã muốn làm cái gì họ sẽ làm
[00:12:03] những cái điều rất to lớn còn nếu mà ông
[00:12:06] mà con người mà hơi bị vô cảm một tí thì
[00:12:08] thực ra là làm gì đó nó hơi hồi hộp nó
[00:12:11] không được à mãnh liệt những người kia
[00:12:14] đâu tại nè thức mà mình cũng
[00:12:17] mình cũng khác rất nhiều loài là mình có
[00:12:19] nhiều cảm xúc hơn bọn nó rất nhiều loài
[00:12:22] loài mực thấp thì nó họ thì bản thân não
[00:12:26] của nó sẽ không có nhiều cảm xúc phức
[00:12:28] tạp được như con người không khó hiểu
[00:12:30] như con gái nữa
[00:12:32] đây
[00:12:40] đây tiện thì cũng nói qua với những cái
[00:12:42] lời khuyên đưa mấy ông này khi
[00:12:44] gà Tôi bảo là buồn tâm sự tôi thương anh
[00:12:47] có tí lên lên lớp thì vậy dạy về
[00:12:52] kiểu bài toán Con người hơn như là ông
[00:12:55] nào Muốn nghe thì nghe không ạ Không thì
[00:12:58] đội và người tâm sự tôi sẽ dạy học
[00:13:01] thì cái á
[00:13:04] Nó bảo this code anh còn thông báo về
[00:13:07] chứ và không thông báo vào cái kênh nha
[00:13:10] anh có thuốc báo này anh không thông báo
[00:13:13] vào cái kênh
[00:13:14] school thôi Bởi vì a cool thì à Anh
[00:13:18] thường ấy thông báo liên quan đến kiểu
[00:13:20] về đồ án hơn
[00:13:22] Nói chung là mấy ông ấy chả mở thông báo
[00:13:24] ở trên kênh YouTube của tôi là tốt nhất
[00:13:26] để tôi đang cái gì mày không nhận được
[00:13:28] hoặc là cứ đến giờ đúng giờ là vào thôi
[00:13:31] đúng không ạ Thì giờ nó vẫn cố định trừ
[00:13:35] khi là có lịch gì đâu xuất tôi sẽ thông
[00:13:37] báo cụ thể sau thì à anh ở đây thì
[00:13:47] khứ này thì à
[00:14:02] thông báo cho nào mà họ khi anh vẫn
[00:14:05] thông báo đây mà anh không thông báo và
[00:14:06] bảo kênh server của mình đâu
[00:14:09] không Tôi không cần mấy online nhưng mà
[00:14:12] Mấy ông có thể mở thông báo cũng không
[00:14:13] cần phải xuất ngoại Speed thì mày có mở
[00:14:15] được bán được nghỉ nhưng đại khái là tôi
[00:14:18] thấy là thận 9.000 người theo dõi rồi
[00:14:19] cùng đi Tôi ra thấy con số mà nhiều quá
[00:14:23] như thế không thích Vì thực tế lại ít
[00:14:26] Tôi không cần số lượng với cần cẩu thực
[00:14:29] tế ấy
[00:14:37] cũng có dự định về sau lên FPT Dậy Mà nè
[00:14:39] Ừ anh đây một cơ hội tốt thậm chí ở ngày
[00:14:42] mai anh cũng đi một buổi cà phê lên FPT
[00:14:45] FPT không ở Hòa Lạc mà là ở cái cơ sở
[00:14:48] mới để mà anh anh anh ở bên sshop anh ấy
[00:14:52] sẽ trao đổi với anh một vài thứ nữa đây
[00:14:55] cũng là đầu anh và mang đấy và nói chung
[00:14:58] là tạo mối quan hệ thôi à đây Thì đang
[00:15:02] nói giờ thì cái thay đổi sau quá khứ này
[00:15:04] Hôm trước có một bạn bạn đấy cứ tự ti Bà
[00:15:08] cứ bảo với tôi à Bạn không phòng của em
[00:15:11] kiếm được nửa tỷ 1 tháng
[00:15:14] ở đâu 01 tháng Nói chung kiếm một nửa tỷ
[00:15:16] rồi Cái đấy thì em cảm thấy hiểu bản
[00:15:21] thân mình chưa là cái gì cả và lần đấy
[00:15:25] thì bạn đang rất tự ti thì lúc đấy thôi
[00:15:29] thì nói đó là nếu không mở được phép nên
[00:15:31] so sánh mình với bất kỳ ai cả
[00:15:34] cờ tướng gia là tuy nhiên ở chúng ta nên
[00:15:37] biết mình biết ta biết được nữa ta biết
[00:15:40] mình thì em chỉ ở mình sẽ biết được cái
[00:15:44] Mọi người như thế nào để mình phấn đấu
[00:15:45] hay là để mình nhìn vào để mà tránh gì
[00:15:50] đó tôi thường ai bảo nhìn vào để tránh
[00:15:51] cá sấu Họ được cái học hỏi và trải như
[00:15:54] thế người cho anh những cái quan trọng
[00:15:56] đó là có thêm đỡ đầu là ông Đừng so sánh
[00:16:00] mình với bất kỳ người nào xong mình giỏi
[00:16:02] hơn người làm Mỗi người đều có một ưu
[00:16:04] nhược điểm của họ ông làm sao không thể
[00:16:07] so sánh tất cả vừa giống nhau rồi đúng
[00:16:08] không ạ Đấy thì đấy kém nhất bởi vì rất
[00:16:12] là hoàn cảnh và xuất phát của của hai
[00:16:16] người khác nhau mà đúng ạ
[00:16:18] sữa chua hai người khác nhau đúng không
[00:16:20] ạ Cái cả hai anh em sinh đôi được ra còn
[00:16:22] Chắc còn chả vừa giống nhau được 100 tại
[00:16:25] sao mình lại đi sao tháng mình ôm người
[00:16:27] khác
[00:16:27] thêm mình so sánh về ai bây giờ đi sang
[00:16:31] với chính mình trong quá khứ thế là được
[00:16:34] ứng dụng của tôi luôn tự tin và tôi tốt
[00:16:36] hơn sau cả thứ tôi buốt trẻ trâu hơn vào
[00:16:38] quá khứ cho dù tôi vẫn phải cho có chấm
[00:16:41] nguồn tôi vẫn luôn là tôi đang bớt trẻ
[00:16:44] trâu hơn bạn hơn tôi 5 phút trước cảm
[00:16:48] thấy mình tĩnh tiễn 5 phút trước để chạy
[00:16:51] sau Bây giờ thì đỡ hơn cả thế
[00:16:54] tôi luôn luôn so sánh mình quá khứ Nếu
[00:16:57] mấy ông quen tôi từ bây giờ bây giờ ấy
[00:17:00] thôi với ông xem lại cái video đầu tiên
[00:17:03] của tôi dậy vào 6 tháng trước ông sẽ
[00:17:05] thấy cách nói chuyện của tôi khác rất
[00:17:07] rất nhiều đấy thì mấy ông sẽ thấy da tôi
[00:17:11] thay đổi rất nhiều
[00:17:18] ông bây giờ để nửa năm nữa bị ông thấy
[00:17:20] tôi lại cách nói chuyện rất là khác đâu
[00:17:23] có tự tin là tôi đang tốt hơn sau quá
[00:17:25] khứ liên tục
[00:17:27] nên là mấy ông cũng nên cậu như thế Đạt
[00:17:31] cột mốc là chính bản thân anh không so
[00:17:35] sánh mình vì ai cả Không ạ
[00:17:37] tiếp theo bà
[00:17:40] ờ ai có khuyết điểm của họ đúng ạ thích
[00:17:44] cái cái ở đây là ông có ông còn nên tự
[00:17:48] ti với khuyết điểm của mình không thì là
[00:17:51] tôi là tôi không tự ti khuyết điểm tôi
[00:17:53] lắm đâu có một vài cái đúng sự thật nếu
[00:17:55] mà vài cái gì tôi đi nghĩ là tôi cải
[00:17:58] thiện được thì không tự đi lắm
[00:18:01] Tôi sẽ biến nữa vài cái ưu điểm của tôi
[00:18:05] khắc phục Google cửa Tôi không
[00:18:15] việc nhà không biết làm ăn các bạn tới
[00:18:17] Thượng Cũng khắc phục của tôi Cậu tập
[00:18:19] trung là thứ gì tôi giỏi đó Kiếm tiền
[00:18:21] làm làm những cái thứ mất rồi đam mê này
[00:18:23] kiếm được cho về sau có thể thuê giúp
[00:18:26] việc mà mua máy rửa bát hay gì đó Mày
[00:18:29] nấu ăn này không có cho đi câu được một
[00:18:32] là kiếm vợ hai đã kiểm duyệt Ở đây Ờ
[00:18:36] Ừ tôi có khuyết điểm đã nói nhiều Cái
[00:18:39] này ra tôi sẽ cải thiện bằng cách à Nói
[00:18:42] nói chuyện à Cố nói những cái chủ đề mà
[00:18:45] người khác muốn nghe mà nghe được gì ấy
[00:18:48] mà biết cách nói người ta đỡ bất hủ và
[00:18:51] Vân đấy Thì
[00:18:55] đấy là một trong những cách mà tôi đang
[00:18:57] nói theo góc nhìn của tôi nó cải thiện
[00:19:00] có phải cái thể hiện được chứ mấy ông
[00:19:04] đừng có tự tin quá nhiều và cư trăm mà
[00:19:06] những khuyết điểm của bản thân ai mà có
[00:19:09] khuyết điểm ạ
[00:19:11] ở chùa tính tôi là không Không nên tự
[00:19:14] tin chúng ta tự tin nếu mà tự tin ở đây
[00:19:17] không phải là tự ti nữa cửa
[00:19:19] cố chấp bảo thủ Quá không ạ thì mình
[00:19:23] không Họ học hỏi được thêm cái gì
[00:19:26] nói nhiều nó khuyết điểm cho em nói
[00:19:29] nhiều mà thực sự mà nói trá mà không ai
[00:19:31] nghe thì chẳng ai muốn ở gần mình cả
[00:19:33] thấy ghét nhất thứ hai là thực ra là nói
[00:19:37] nhiều nó không không bằng nghe nhiều
[00:19:40] biết lắng nghe biết lắng nghe nhá chứ
[00:19:43] không phải là ông ngồi nhưng mà không
[00:19:45] nói gì và cũng đầu mối phía bắc cái thứ
[00:19:47] thì người ta cũng không ăn ở muốn nói
[00:19:49] chuyện với ông đâu nhưng mà ông Biết
[00:19:51] khơi gợi câu chuyện để người ta tin
[00:19:53] tưởng người ta nói chuyện với ông và ông
[00:19:56] học hỏi được rất nhiều một nói bằng hai
[00:20:00] nhẹ nhàng nhập một nghe và hay nói được
[00:20:02] là được cả là ông học hỏi được nhiều hơn
[00:20:03] khi mà nghe này ra cũng phải khi bỗng
[00:20:06] nói đúng không ạ Đấy cái hợp được là
[00:20:08] người ta sẽ cảm thấy thân với ông hơn
[00:20:11] anh nói được giải tỏa được hết
[00:20:14] kiểu tâm sự một bịch người ta cho ông
[00:20:17] rồi chẳng hạn thì anh sẽ nhớ ông hơn này
[00:20:20] nhé thật nhưng mà ông vẫn phải học cách
[00:20:23] lắng nghe Có phải học nhá Cái này thì
[00:20:25] vẫn này học chứ không phải là không
[00:20:26] không Cứ ngồi vắt người ta sẽ kể hết đâu
[00:20:29] em ạ này Đấy ông kia đang bảo trả lời cứ
[00:20:33] ừ thì đương nhiên là sẽ trả nó không ạ
[00:20:36] thì người ta không vẫn cái đấy không hỏi
[00:20:39] Hàn gọi là biết lắng nghe đâu đấy Có rất
[00:20:43] nhiều mẹo để mà hồi trưa Tôi đọc cái và
[00:20:47] là đôi khi ông chỉ cần nói lại câu cô ấy
[00:20:49] mày ra nói thêm 1 vài thứ tư nữa ngồi
[00:20:54] nó bỏ đi thật à ấy gió
[00:20:57] xe tải kèo thế chẳng ăn thế thì người ta
[00:21:01] bấm lời người ta nói tiếp tưởng hết cái
[00:21:05] khó nhá Thôi không điện được rồi đấy
[00:21:08] tiếp theo đó là
[00:21:11] cái bài trên qua tôi từng nói nhóm này
[00:21:14] khá ổn theo kiểu diễn dịch ra Nhưng mà
[00:21:17] từ ra đôi khi là nó hơi bị định hướng sự
[00:21:19] định hướng là định hướng thông tin tí dư
[00:21:24] luận rất là sao nghĩa là cái nồi nói cái
[00:21:27] câu trả lời trong bài này chưa chắc nó
[00:21:30] đã là một câu trả lời chuột mà Nó kiểu
[00:21:33] nó cung cấp rất nhiều thông tin thì có
[00:21:34] thể là không hẳn mà không hẳn là thông
[00:21:38] tin sai nhưng rồi chú mà nó thông tin
[00:21:40] một chiều về một cái ví dụ Giả sử hôm
[00:21:42] trước đây Đang thông tin về
[00:21:44] chính trị ạ một vấn đề rất nhạy cảm thì
[00:21:49] ông mà chỉ đăng thông tin về một chiều
[00:21:51] thì ra thấy không tốt thì thế nhớ mà còn
[00:21:55] mày này thì hai bài này nó về à Đó là
[00:21:57] kiểu tín nhiệm về viết tivi và cái bài
[00:22:01] này bình luận cũng rất là hay bình luận
[00:22:03] cũng kiểu chia sẻ thêm rất nhiều cái mẹo
[00:22:06] nữa đầu tiên đừng để địa chỉ nhà riêng
[00:22:08] trên tivi tội tiếng nói vụ này rồi không
[00:22:10] ạ tiếp theo đó là ờ ờ
[00:22:21] cho biết dịch từ đoạn này như thế nào
[00:22:24] nếu hai điểm bạn thấp quá đừng nên ghi
[00:22:27] và seri gà tôi tôi không không thích mày
[00:22:30] ông ghi bằng cấp ở trong tivi tranh để
[00:22:32] làm gì ông khoe này cái khác này ra quan
[00:22:33] tâm người khác hơn dai so 10 CV ở định
[00:22:36] dạng PDF bởi vì là nữa word thì thì nó
[00:22:40] lỗi phone Nếu là sử cái gì đó nên dùng
[00:22:43] bf2 tôi chưa nói nhưng mà thường là tài
[00:22:45] mấy cái trang online nó toàn nào về để
[00:22:48] ép hết tiếp theo
[00:22:51] đó là mấy ông liệt kê trong thôi kính
[00:22:53] hiệu đấy thì mày ông Đức à Ừ thì cụ thể
[00:22:58] hơn đừng nói chung chung là hỗ trợ khách
[00:23:00] hàng mà hỗ trợ cụ 60 khách hàng một ngày
[00:23:03] mà gà vẫn chưa hiểu
[00:23:07] Nói chung là tạo được phần mềm mà hỗ trợ
[00:23:10] được cho hàng triệu người dùng trong
[00:23:12] vòng một ngày chẳng hạn như thế thì đó
[00:23:15] kiểu có cái những cái con số thêm ấy thì
[00:23:18] nó sẽ có vẻ ổn bị tín hơn ấy
[00:23:24] viết thêm rõ thời điểm tốt nghiệp này
[00:23:26] cho mấy ông đang còn là sinh viên này
[00:23:28] không ạ thì thay vì kiểu đến hiện tại
[00:23:31] không thể đoán được là bao nhiêu bao
[00:23:34] nhiêu lâu tốt nghiệp ra có sang vài
[00:23:36] trang Tivi Nó đang kiểu nó có tích vào
[00:23:38] là lại vẫn đang học thì vẫn đang làm đấy
[00:23:40] thế là nó đến nay thành ra thực là tôi
[00:23:43] không thích Hồi trước có cái Trang nó là
[00:23:46] kiểu cho Bấm cho mất thời gian tôi thích
[00:23:48] cái đấy hơn tiếp theo là đầy đủ họ tên
[00:23:53] ở
[00:23:53] đây Cái này làm chỉ là khi mà đặt tên
[00:23:57] cho cái file thì lên là đầy đủ họ tên
[00:23:59] chứ không phải là tên là Siri và cho vào
[00:24:02] cách tôi đặt tên đấy thường là tôi sẽ
[00:24:04] đặt tên cho kiểu như thế này gà một phần
[00:24:06] là tên của tôi thì có thể không không bị
[00:24:08] nhầm được
[00:24:10] tôi sẽ tên kiểu này Nguyễn Nam Long cảnh
[00:24:13] ngay
[00:24:18] pdf nào ạ chuyện với ai đó thì cái tên
[00:24:24] kiểu này không có dấu thì vẫn không sao
[00:24:26] gà mày ra không nên được gọi tên file Có
[00:24:28] dấu làm gì không ạ Nếu mà vài bạn để tên
[00:24:32] là không có dấu có thể nhầm tên thật à
[00:24:36] từ
[00:24:43] không cần viết thư giới thiệu làm gì và
[00:24:46] không cần đấy
[00:24:47] xem
[00:24:48] tivi nên gói gọn cho một trang giấy này
[00:24:52] web 2.0
[00:24:54] hôm trước tôi đọc coi ở đấy đợi tròn
[00:24:56] hiệu USB 3.0 cái gì cả
[00:25:06] dùng để có buổi phỏng vấn không phải để
[00:25:09] có công việc tôi thấy câu này rất là hay
[00:25:10] Nghĩa là nghĩa làm chị là ông trịch có
[00:25:14] xin đi thì nói chỗ nào đến mức tương đối
[00:25:16] để người ta cảm thấy cũng có tính tò mò
[00:25:18] thêm với ông chở loạn và cảm thấy ông có
[00:25:21] vẻ Ôi để mà cân nhắc là kiểu sẽ phỏng
[00:25:24] vấn ông nên là cũng đừng chém gió quá
[00:25:26] trong cái phí bi để cho người ta khi
[00:25:28] phỏng vấn với ra đuổi ông đấy
[00:25:35] girl mà tôi tạo ra nhóm gái xinh chọn
[00:25:37] lọc cái gì ạ Con nhóm dưới hay girl à
[00:25:40] quanh Mạnh Tuấn ở công ty đóng cửa à
[00:25:49] anh
[00:26:12] alo ờ
[00:26:19] có đây chắc là những cái tâm sự này cho
[00:26:24] để buổi sau đi được xanh xanh giờ với sự
[00:26:28] phép chia sẻ nốt cái này đó là cái có
[00:26:32] bạn hôm trước chính xác là có một kênh
[00:26:34] hôm trước tôi xem anh đấy giới thiệu có
[00:26:37] cái Trang cũng khá 32 trang đấy Tổng hợp
[00:26:40] một loạt các phần mềm kiểu dạng là cũng
[00:26:44] được Hay nhiều người dùng sau đó đi ỉa
[00:26:47] tích tích tích hết vào giờ ấn nút loa Em
[00:26:49] tải phần mềm những bản cái đào tất cả
[00:26:52] những phần mềm này cũng một lúc đấy ra
[00:26:54] là hay Nhưng mà tôi thấy có người bảo là
[00:26:58] Trang đấy không không đầy đủ những cái
[00:27:02] phiên bản mới nhất thì nếu mà muốn có
[00:27:04] những phiên bản mới nhất thì tôi nghĩ là
[00:27:06] cái trạng thái phần mềm này tôi đã từng
[00:27:08] dùng từ rất là lâu rồi tôi biết cái phần
[00:27:12] mềm này chắc là từ hồi à
[00:27:14] cấp 3 với cấp 3 của tôi rất là lâu rồi
[00:27:17] vẫn me gì nó cũng là tổng hợp tất cả
[00:27:20] những cái phần mềm Chắc là chủ yếu là
[00:27:22] miễn phí chủ yếu miễn phí ở trên này và
[00:27:25] ông có thể tải toàn bộ những cái phiên
[00:27:27] bản nó luôn là mới nhất là thực ra có
[00:27:30] thể thêm nhiều cái nữa hả Tôi đang mở
[00:27:33] chặn con cá rồi đúng không
[00:27:41] thằng này nó sẽ không luôn nó không nó
[00:27:45] không dính thêm bất kì cái gì của virus
[00:27:47] hay cái gì cả ông chứ không phải ở trên
[00:27:51] này mấy ông hiểu không và nó không dính
[00:27:54] thêm bất kỳ phần mềm con nào cả ấy rất
[00:27:58] tiện nói chung là lên đây hợp và hồi đấy
[00:28:00] à Hồi đấy là do làm mấy cái phần mềm này
[00:28:02] nó còn chưa Mập định là tự động tự động
[00:28:05] cập nhật cơ thì phần mềm này nó còn tìm
[00:28:10] tìm kiếm hộ cho ông kiểm tra hộ ông
[00:28:12] những phần mềm nào Đang nhà đang kiểu
[00:28:15] Đăng phiên bản cũ với nó cầm để thu âm
[00:28:17] cơ đấy Cái phần mềm này một phần ra hai
[00:28:22] giúp Winslet này chẳng hạn visa phải nó
[00:28:25] không thường xuyên kiểm tra cập nhật đâu
[00:28:26] ai
[00:28:28] ông thể tải về xem cái này thì tải hỗ
[00:28:32] trợ tài bá0 vẽ hỗ trợ Tải driver cho gần
[00:28:37] đây Nói chung là tôi bị thì tôi bị lỗi
[00:28:39] driver về con Mic Mic không nhận và tôi
[00:28:44] cũng không muốn thử các phần mềm Tải
[00:28:46] driver nó kiểu 50 50 cái gì Ừ
[00:28:55] này Hôm trước vẫn chưa hỏi trả lời xong
[00:28:58] thôi tôi sẽ trả lời câu hộ câu này vậy
[00:29:01] hôm trước thì tôi có thực ra tôi có cho
[00:29:04] mày không xem rồi Nó lại năm hết
[00:29:08] Im
[00:29:11] spo trở lại
[00:29:13] đây thì
[00:29:16] sẽ có khái niệm là kiểu
[00:29:20] cái Trang mà
[00:29:22] ở đây nó khái niệm mà còn những cách lưu
[00:29:25] vào như thế nào nếu mà thay bồ với 50
[00:29:29] thì ông sẽ phải lưu lại rất nhiều cái ở
[00:29:31] đây như thế này không ạ Có bao nhiêu cái
[00:29:34] ông sẽ xảy ra trong như lại thêm nếu heo
[00:29:36] này Vodka kiểu dạng cho người dùng tiền
[00:29:39] thì công a tiếp theo với cho in in là
[00:29:43] mình sẽ tự Tuy gốc số nó là gì ngọn từng
[00:29:47] cái đấy số nó gì đấy
[00:29:51] tiếp theo là à Kiểu này mình sẽ mình sẽ
[00:29:57] phải quý gốc cái số này do về cái bảng
[00:30:00] Bảng này đấy lấy đầy ra được tên của cái
[00:30:04] tên cái đấy Và đây là trong trường hợp
[00:30:07] là 1,5 triệu cái gì à
[00:30:11] em
[00:30:12] về Để em nhé
[00:30:14] Đây là 1,5 triệu vi code và có 29 cái
[00:30:19] thằng test này Ok thử xem nhé Kết quả
[00:30:23] cho với khi mà chạy câu truy vấn đấy thì
[00:30:27] nó sẽ không phải 008 cái này cũng tương
[00:30:30] tự với 3 tra thì ông sẽ thấy thực ra với
[00:30:33] cái thằng Y Nam mình đã làm xong trước
[00:30:35] đây cả ạ và cái thằng choi thì ra nó trả
[00:30:38] lời gì cả Không ạ dành cho trận nhé Cho
[00:30:42] lời cả bởi vì về các bà tội giọng nói đó
[00:30:46] là thằng cho thằng đối với thằng Acquy
[00:30:49] thì cho roi nó cũng hỗ trợ Khá mẹ nó
[00:30:52] không bị khô nhăn bị chậm lắm đấy
[00:31:04] sự mà
[00:31:05] order bye cái gì đó như này thì mới ông
[00:31:08] sẽ thấy là anh vẫn là tốc độ năm thì
[00:31:12] nhanh nhất năm bởi vì bản thân là thần y
[00:31:15] nam này chắc là đối về equal nó sẽ là sẽ
[00:31:18] vẫn là một cái danh sách gì đó còn nhanh
[00:31:20] hơn hẳn qua trai đấy bà cuối cùng cho
[00:31:23] chậm nhất rồi lên 26 giây ông ạ ấy rồi
[00:31:27] mấy ông thể xem khái niệm Ace Plan trees
[00:31:30] của nó nữa Tại sao như thế
[00:31:32] mà kết quả cuối cùng là
[00:31:35] cái gì đây đây là offset Bỏ qua Bỏ qua
[00:31:40] 10.000 để lấy 5 thằng thằng nào bật
[00:31:43] nhanh hơn đồng ra rồi nhưng mà thằng này
[00:31:46] thì
[00:31:47] vẫn chậm hơn tí ơi Ok
[00:31:51] thời
[00:31:59] tí hon Ông hỏi tôi đấy
[00:32:13] Ôi tôi hướng mấy ông thực ra không Đừng
[00:32:17] có đoán hay mày tôi không Tôi không
[00:32:21] hướng để mấy ông làm cái gì ở công nghệ
[00:32:23] giữa chị mà tôi hướng đến mấy ông có
[00:32:26] những cái bài toán liên quan nghiệp vụ
[00:32:27] có cần xử lý cái bài văn nghĩa vụ chứ
[00:32:30] không phải là một bài toán mà có rất
[00:32:32] nhiều cái tính năng chị sò trong đấy bởi
[00:32:34] vì chị xong như thế mà chất là ông ôm
[00:32:37] công nghệ về chưa Ông không hình dung
[00:32:39] được là là cái bài toán có tình huống
[00:32:43] nào mình giải quyết nha kết hợp với ít
[00:32:45] câu truy vấn đã ra tay thì sẽ càng không
[00:32:47] thích tôi muốn bà ngoại còn rất nhiều
[00:32:49] thì ông làm quen việc Ở đây có thử đã
[00:32:53] thì sao ghét cho nữa vẫn là người yêu cũ
[00:32:56] thôi Đây tiện thì có bạn à
[00:33:00] Hôm trước bà ấy bảo tôi là mấy cái
[00:33:03] f-stop của tôi thì
[00:33:06] đợi tí hai Mẹ ơi chuyện gì khác à pp tôm
[00:33:10] của tôi thì nó nó còn hiển thị ra kiểu
[00:33:13] như này Nếu không thấy không có thêm là
[00:33:15] kiểu kiểu mình chuyên cài á truyền cái
[00:33:19] gì vào trong cái cái
[00:33:21] hàm này nó sẽ hiểu gợi ý dai thứ thử thì
[00:33:26] thằng Viết cốt nó có cái tương tự không
[00:33:29] cái
[00:33:31] thì nói chung là mày ông tôi chắc là bể
[00:33:34] mấy ông Tự bình luận nha Tôi không dùng
[00:33:36] vé cốt thì ông sẽ tự bình luận là những
[00:33:39] tiện ích Viết cốt với ông dụng hoặc là
[00:33:41] mấy ông thì bình luận không bình luận
[00:33:43] trong này bị trôi thì mấy ông lên Ít
[00:33:45] code với mấy ông bình luận nha tổng hợp
[00:33:48] mà chung nhà lên đi con lên server với
[00:33:51] cô tin
[00:33:52] tổng hợp lại các thứ thứ đấy
[00:33:55] Ở đây nó có thể chơi đấy
[00:33:58] ấy
[00:34:00] Ok chưa
[00:34:09] nhé
[00:34:18] em
[00:34:20] nói kệ đi
[00:34:23] bây giờ hôm nay mình sẽ cái vụ sắp xếp
[00:34:26] rồi nhóm đồ án thì tội làm xong rồi ra
[00:34:29] để tí tôi có vài nhóm với nhiều trước
[00:34:32] tôi chưa kết nối được mài nhọn mười mấy
[00:34:35] bạn đấy thì mấy bạn đấy để ai đi nó hơi
[00:34:38] bị có bạn còn để ai đi theo kiểu đúng
[00:34:41] mỗi số làm sau t thôi đâu Mấy tội ác dặn
[00:34:44] rồi mày ông phải mà một nick ở đây này
[00:34:46] để copy ra và cặp tên và cả cả ID như
[00:34:51] này người tên là mấy ông trùm nhau với
[00:34:53] tôi sẽ tra được theo ID đấy hoặc là mấy
[00:34:56] ông ghi Võ hoàn toàn bộ nó là số ID được
[00:34:58] cái ông trao Google nó ra bye bye mai
[00:35:02] và Mai discord hay đi dạo nhãn Mình ở
[00:35:07] Dân công nghệ mà cái gì mình cũng lên
[00:35:10] tra Google đã nóng ạ
[00:35:12] nhưng mà hôm trước có bạn để vài số lính
[00:35:16] ta tinh các thứ tôi chả tìm được Ừ tôi
[00:35:19] cũng không nghe không chắc là béo không
[00:35:23] phải chủ động để mà
[00:35:25] nhắn tin Facebook cho mấy bạn đấy hòa
[00:35:28] bình luận hoặc là tí thôi sẽ để lại
[00:35:29] email mày ông gửi nữa chứ Tôi đã từng
[00:35:32] gửi cho mấy bạn đấy thôi Hình như tôi bị
[00:35:34] cho và span rồi đấy Gần đây tôi gửi bốn
[00:35:37] mươi mấy bạn nhưng mà có mỗi một hai bạn
[00:35:39] trả lời thôi có nghĩa bị vào thư mục
[00:35:41] giác mong chờ
[00:36:11] hình của thằng level tế là nó khác với
[00:36:13] mồi VC ở một chỗ này đây
[00:36:16] mới C ô tô cho bé uống xe à
[00:36:25] nó có thêm cái gì nó nó không phải đơn
[00:36:29] giản và mpc kiểu ngày nữa có thêm một
[00:36:32] cái đó chính là này rất thích hình này
[00:36:34] thì ngày để bây giờ vẫn đúng chùa Từ 5.8
[00:36:37] gì nó bản chất nó vẫn đúng nó là cái gì
[00:36:40] đó là khi mà người dùng sẽ gọi đến cái
[00:36:43] đường link của mình cái ô tô đúng ạ thì
[00:36:46] nó sẽ thông quan mới được nghe ông nhìn
[00:36:48] thấy đề hình của ông bảo vệ không ạ kiểu
[00:36:51] cảnh sát từ cái gì đó spell it is an
[00:36:54] ninh đúng không
[00:36:56] Thì đây bizweb này Nó sẽ chặn nó sẽ chặn
[00:37:00] và nó sẽ luôn kiểm tra vé vào cửa quyền
[00:37:03] truy cập các thứ thứ để tiếp để mà có
[00:37:05] thể nhảy vào những thời tiết heo đấy thì
[00:37:08] hôm nay mình sẽ kết hợp với việc là mình
[00:37:11] học cái đăng nhập thí sinh đấy những kết
[00:37:15] hợp với cái á nhí từ Where để mà kiểm
[00:37:17] tra nếu trông thấy rõ ràng là hồi đồ án
[00:37:21] một đấy thì mình phải cố học cái shit
[00:37:24] khi đăng nhập trước để làm gì Để và với
[00:37:27] mọi file mình phải chèn thêm một cái
[00:37:29] đoạn gliwice kiểm tra cái file là
[00:37:33] đã đăng nhập Thấy chưa đúng ạ Còn không
[00:37:36] bây giờ thì làm mô mình hình mvc là ông
[00:37:38] thích cốt để đi trước cũng được với ông
[00:37:40] cốc thế này sao cũng được Ông chị Tống
[00:37:42] nó vào một cái chỗ riêng và toàn bộ
[00:37:44] trọng khác là vẫn chạy lại rất là ngon
[00:37:46] tôi sẽ đưa tôi sẽ chỉ cho mấy ông
[00:37:49] ờ ờ
[00:37:52] bây giờ đầu tiên là đầu tiên là mình sẽ
[00:37:56] phải tạo một cái á Ở
[00:37:59] ở đầu tiên là bây giờ mình sẽ tạo một
[00:38:01] bản để đăng nhập không ạ
[00:38:04] I
[00:38:14] được
[00:38:16] à à
[00:38:23] chưa hình dung với bạn lắm
[00:38:26] à
[00:38:43] chưa Tôi chưa dùng cái Battle CMS kia à
[00:38:57] ca ifish
[00:39:00] Ừ
[00:39:02] đợi tao tí tôi phải tạo lại cái này hình
[00:39:05] như nó vừa đăng suốt ra cho
[00:39:08] anh
[00:39:09] em restore ngày mấy ông nên dùng merdu
[00:39:12] tội không có kia không
[00:39:15] cho
[00:39:33] but the way vẫn được không Thế thì sai
[00:39:35] mà bản chất rồi bạn vì rõ ràng là mình
[00:39:38] tại sao mình vẫn để cho vô xử lý khi mặt
[00:39:42] người ấy không Quyền truy cập nhỉ Mình
[00:39:44] phải từ chỗ luôn chứ đừng từ chối để cho
[00:39:48] đỡ nặng cho vô xử lý mình có đoạn làm
[00:39:51] sau chứ chứ
[00:39:52] em lấy thế bị ngược ấy nghĩ the weather
[00:39:55] đây đây theo hình ảnh biết được nghe
[00:39:57] rằng ai phải là thằng trước xe đấy Còn
[00:40:00] bạn làm kiểu thế bị ngược với rồi rõ làm
[00:40:03] middleware nó phải luôn kiểm tra quyền
[00:40:05] trước trước khi mà thao tác một cái gì
[00:40:08] đó thì đây mới chuẩn của cái lý thuyết
[00:40:10] của thằng nghĩ được em ạ
[00:40:13] Ê
[00:40:14] mấy ông sẽ thấy là à đầu tiên là bây giờ
[00:40:18] mình sẽ tạo à
[00:40:19] thì mình sẽ tạo bằng cốc ngọn mình sẽ
[00:40:22] tạo bằng cốt để mà tạo bảng ozer chẳng
[00:40:25] hạn để đăng nhập lại không ạ
[00:40:27] khi sex
[00:40:29] Ừ
[00:40:35] tôi lại ra vài cái tục
[00:40:38] Ê
[00:40:39] tôi dậy mày ông sẽ có khá nhiều cái đây
[00:40:43] Ở đây có vài cái dậy rồi
[00:40:46] Xuân sau nóng này dậy này
[00:40:50] a cho tôi chưa biết the weather
[00:40:52] the weather sáng hẳn à
[00:41:01] đồng này có phải cái ông thấy đốt quà
[00:41:03] tôi đã dậy rồi đấy ok
[00:41:11] học phân quyền thì tôi sẽ tôi bảo tôi
[00:41:13] chưa dùng cái Pocket L'Oreal
[00:41:16] market nhập Maria permission thì tôi sẽ
[00:41:20] tìm hiểu cái đấy lẫn cả vai Âu nữa thì
[00:41:24] đợi theo tìm hiểu đấy tôi sẽ dậy người
[00:41:26] đứng sau còn bây giờ thì ra là mình có
[00:41:29] thể dùng chứ sân với a midway vẫn được Ừ
[00:41:33] không sao cả à
[00:41:35] ở
[00:41:37] tp attention and make a
[00:41:46] their table chẳng hạn
[00:41:52] Anh
[00:41:53] không dùng Pocket có được không ạ Thế
[00:41:55] phải tạo nhìn em ạ lại phải mất công tạo
[00:41:58] nhiều bà cũng như là viết
[00:42:00] viết khá nhiều
[00:42:03] Ừ chứ khi ở kiểu em em chỉ không nên
[00:42:07] dùng Pocket khi mà nó không hỗ trợ được
[00:42:10] cụ thể cái bài toán của em còn về cơ bản
[00:42:12] bát ít đây là nó hỗ trợ phải 78 mới phần
[00:42:14] trăm những cái kế toán chỉ hội chết rồi
[00:42:18] cho mình mình sẽ phát một tí có có tự
[00:42:20] nhiên ai gọi E
[00:42:48] không
[00:42:49] bây
[00:42:49] [âm nhạc]
[00:42:52] giờ mình sẽ sáng lên file bài này
[00:42:56] nhà
[00:42:58] mình có bảo ngủ giờ này ai đi đúng không
[00:43:01] Tôi thực ra là đang chỉ muốn à
[00:43:04] Xe ga có thể lưu lại cả Avatar nữa được
[00:43:09] thì mình sẽ không Avatar ở đây tự lái xe
[00:43:14] mà ta thì lại phải làm cả tính năng
[00:43:16] chỉnh sửa thông tin cá nhân thôi cũng
[00:43:19] được
[00:43:19] mình sẽ có đấy thấy bồ này
[00:43:23] nên này
[00:43:25] nói chuyện chứ nói chính Nên này này
[00:43:31] sẽ có Avatar
[00:43:34] bài
[00:43:43] làm đơn giản thôi Nó là kiểu chia ra làm
[00:43:47] à Kiểu admin là Superman cũng được hoặc
[00:43:51] là kiểu nói chung là chỉ làm Muốn tương
[00:43:54] đối thôi Nó kiểu cấp độ ấy lấy vụ như
[00:43:56] này chứ giờ mình 057 toán thuốc ta vội
[00:44:00] ừ ừ
[00:44:02] Nghe
[00:44:04] tiếng hát cốt thẳng luôn cái quyền ngồi
[00:44:06] ta thấy cậu đã admin được phép và đâu
[00:44:08] Chúc em đi được phép và đâu chị ạ Chứ
[00:44:10] mình không không làm để nỗi phức tạp
[00:44:12] kiểu cực kỳ phức tạp với cả và kiểu dạng
[00:44:16] là về sau có thể trình sửa quyền của một
[00:44:19] người nào đó cái đấy nó phức tạp hơn
[00:44:23] ở một mình sẽ còn thêm cái gì nhà mình
[00:44:27] sẽ có thấy bồ Trinh này sẽ có email
[00:44:38] biệt với amin là Superman thôi Bởi vì
[00:44:40] đây trang của tôi ra cái cái này ra ngát
[00:44:44] đây mà đấy
[00:44:52] hôm trước dậy năm tôi không muốn trong
[00:44:54] dp rồi sẽ Hạn chế dùng ý năm mua và dùng
[00:44:57] kiểu y dùng kiểu buôn lần không nên dùng
[00:44:59] năm nữa
[00:45:01] trước ý ở ông cố định cố định sẽ không
[00:45:05] ngờ thay đổi cài tốc độ thì còn được
[00:45:09] chị
[00:45:16] Ừ Ok Lúc đầu mình chắc thế này thôi
[00:45:21] ở Sao Đỏ mình tạo cho mình chả yên xuất
[00:45:23] chai vào trong máy bay cũng được
[00:45:26] số
[00:45:27] một này là áp suất kết hợp chất thực ra
[00:45:30] là Tôi sẽ chỉ cho mấy ông ấy vụ là Nếu
[00:45:33] giả sử Nếu giả sử em chỉ muốn đưa lại là
[00:45:37] người đầy đã đăng ký vào lúc nào không
[00:45:39] quan tâm người đấy đã đã kiểu đã
[00:45:44] dọn ngờ đã cập nhật vào lúc nào thì làm
[00:45:47] nhà ở đây rồi chỉ cho nha à
[00:45:50] Ừ
[00:45:58] thì là ship cho chuẩn để mà mình về cho
[00:46:01] mình đẩy cốc lên là người khác inbox Về
[00:46:04] thì người ta đỡ phải in Phước bằng tay
[00:46:06] nữa lại chạy đôi thôi Cái gì nhỉ à
[00:46:15] Em
[00:46:21] nhầy bác ít lâu sau
[00:46:23] này à
[00:46:25] em đi xuống Tại sao ở đây đi Kinh zipper
[00:46:29] vào máy bay sân nhà
[00:46:31] Em
[00:46:32] nói đi không nó nằm trong bây giờ cạn
[00:46:36] hình ảnh 523i này à
[00:46:40] So sánh kém mình sẽ có cái cột Ví dụ ở
[00:46:46] đây mình Tôi đang tìm đã tôi sẽ có khái
[00:46:50] niệm đây
[00:46:51] có
[00:46:57] vào nha
[00:46:59] Ừ
[00:47:00] nếu nắm tay mặc định có chữ S này là hai
[00:47:03] Cụt 2 cột à
[00:47:06] cả dưới tấn ap tật
[00:47:09] a a
[00:47:17] Đây có
[00:47:19] Em
[00:47:21] nói sao
[00:47:24] có người chăm sóc chưa
[00:47:26] em vừa rồi che tem xe nóng ở đâu nhỉ
[00:47:29] I
[00:47:31] love Apple này lại có cái thăm xem bình
[00:47:36] thường đây này
[00:47:37] Tại sao lại dùng sunfat Hồi trước tôi
[00:47:42] chỉ mày ông dùng hết mà ông trùm tham
[00:47:44] thế campaign là gì em xem là nói số đó
[00:47:48] là số số dây bắt đầu từ
[00:47:51] mùng 1 tháng 1 năm 1970 đến thời điểm
[00:47:54] hiện tại tại sao lại chúng ta phải dùng
[00:47:57] số dây kiểu như hai tại du lịch sử giờ
[00:47:59] tôi sẽ có là chỉ lại biết thật à
[00:48:03] thế này Tại sao chúng ta ở cấu tạo một
[00:48:06] cột ở tham.tap em lại theo kiểu số dây
[00:48:09] nó khó nhìn ra nó hơi khó nhìn khi mà
[00:48:13] nhìn trong dp rất là khó nhìn Tại sao
[00:48:15] mình làm như thế để mở khi mà mình muốn
[00:48:17] convert muốn biến đổi cái này ra một cái
[00:48:21] khác một cái khác thì ông đỡ phải mất
[00:48:24] công format ông ngoại phải bình thường
[00:48:26] ấy khi mà giả sử ông lưu lại là ngày
[00:48:29] tháng năm như thế này đâu ạ Ông không đi
[00:48:34] lại số rồi không Ông muốn con vớt ra
[00:48:36] kiểu dạng là năm tháng ngày như thế này
[00:48:39] thôi
[00:48:40] em thậm chí còn giờ phút giây nữa là xử
[00:48:42] thế ông muốn thì con bất từ đây sang đây
[00:48:46] rồi em ạ Ông vẫn phải mất công thêm một
[00:48:48] cái đoạn mà không phải biến cái này
[00:48:51] thằng đối tượng nói chung là nó mất công
[00:48:53] hơn tiền nó đánh đối tượng cho mấy con
[00:48:56] con vất lại còn nếu một khi ông đã có
[00:48:58] cái kiểu đó là tham Xem sẵn rồi đấy thì
[00:49:01] ông không cần phải được Ông không cần
[00:49:03] phải Pho Mát gì nhiều ông chạy thẳng
[00:49:05] được luôn ông dùng làm pho mát không có
[00:49:07] mát luôn cái con số sàn xe mấy thành mọi
[00:49:10] cái thứ nó tiện hơn rất nhiều đấy còn
[00:49:13] nhược điểm thì ông xem trên database thì
[00:49:16] ông sẽ nhìn thấy số lượng ra hơi khó
[00:49:17] phải đọc nhiều Tiện đây ạ Ừ ok ở đây là
[00:49:24] tôi nói rồi nghỉ ngơi Tôi chạy thử cái
[00:49:27] này nhau Bây giờ tôi tạo sinh đôi chỗ
[00:49:29] lại nhá Tạo sister để chạy hai cái không
[00:49:31] Lúc đi anh như thế thì ra tôi tặng mua
[00:49:36] đồ tôi sẽ tạo và
[00:49:39] em vừa rồi mẹ không tiện tạm mua đồ nhỉ
[00:49:42] Không sao tạo bộ được
[00:49:46] thì sẽ pp
[00:49:49] này make
[00:49:53] Mua đồ là u rô này mình sẽ có là mình
[00:49:58] không có controller đoạn này tôi sẽ hạn
[00:50:01] chế thịt gà không còn tâm cho l là con
[00:50:03] cho lũ sơ tôi không thêm mới ở đoạn này
[00:50:05] đâu bởi vì đấy Ăn Nhìn cái gì đó tính
[00:50:09] sau mình à
[00:50:11] thì mình sẽ ghi lại toàn bộ những cái
[00:50:13] cần thêm đi chứ đơn là ghét thì phải
[00:50:16] làm gì nhé
[00:50:18] Em thích đo mua đồ
[00:50:22] 10 di quét thì cả ơi chắc thế này rồi
[00:50:27] ở
[00:50:27] quê farina
[00:50:30] phải sự thêm chữ s nữa
[00:50:33] chị
[00:50:33] đánh festaria
[00:50:36] ở Pháp Paris
[00:50:40] hay đúng nhỉ
[00:50:42] Ừ ừ
[00:50:43] đúng rồi à
[00:50:50] m là mai mai ơi Chuẩn rồi tôi tôi tạo
[00:50:53] Mai ơi chồng nói Tôi không muốn bạn nữa
[00:50:56] chị
[00:50:58] sẽ còn lên là avatar không ạ
[00:51:03] khi nêm
[00:51:05] Ê bà đưa Zip speaker
[00:51:08] ca
[00:51:14] a
[00:51:16] tiếp theo ở Avatar này
[00:51:19] một ngày giữa hai tôi từng nói hôm trước
[00:51:22] rồi tôi cho mấy ông xem cái vụ cấp Cây
[00:51:24] Kơ Nia nó thì tạo ra được anh
[00:51:28] chẳng có cái ảnh mà
[00:51:30] A gọi là đẹp có lắm đâu nó chưa ảnh kiểu
[00:51:34] ghi các con số trên đấy thôi inmate này
[00:51:36] à
[00:51:38] Ừ
[00:51:38] Nó remix đây nói này
[00:51:49] 480
[00:51:51] em đổi sau vậy
[00:51:56] Ừ tôi biết rồi trai rauxanh đấy
[00:52:00] em
[00:52:05] thế
[00:52:07] ở
[00:52:08] nhà mình như dùng hà Mày
[00:52:11] đợi tao một tí nha Tí gọi thằng này gọi
[00:52:14] được không
[00:52:16] à à
[00:52:18] anh hỏi thằng lên được ấy
[00:52:20] bộ truyện ngắn
[00:52:23] à Tôi nghĩ là có khuya à không gọi được
[00:52:27] áo len này
[00:52:30] Anh remix
[00:52:33] Em
[00:52:34] email Google gọi được mà
[00:52:37] em
[00:52:48] Ừ rồi level không ạ
[00:52:52] anh
[00:52:54] phi cơ poland
[00:52:56] a
[00:52:58] tiếp theo email
[00:53:11] anh không biết này có bắt tốt không Cũng
[00:53:13] có đấy có
[00:53:15] ca nhạc trữ tình tích cực thực là nó đơn
[00:53:19] giản nó là Nam
[00:53:20] vì thế thời gian hiện tại rất hay của
[00:53:23] lazaro thì phải lao này nào này nó sẽ cổ
[00:53:26] Converse và Mọi cái để mày Insert được
[00:53:29] gọi cho ông ông ông
[00:53:31] kiểu trong đây ông cần truyền à là tham
[00:53:35] nè hay là hay là đết là hai cái gì đó
[00:53:39] dùng hàm nào được đấy tôi nhớ thế tôi
[00:53:42] chưa thử
[00:53:47] bữa nay bị lỗi tí mình gửi lại biết có
[00:53:51] ship đồ
[00:53:53] anh đã phải chạy đây xong mới gian so
[00:53:56] với này cơ nên thôi là tôi 8 tháng luôn
[00:53:58] nhé xuất khẩu giờ đây là Tạo
[00:54:03] ừ ừ
[00:54:05] anh giờ đây mình tạo là 10 bây giờ đi
[00:54:08] Ừ
[00:54:10] nếu mà chạy độc lập thì ông chạy sister
[00:54:12] độc lập được còn bây giờ tôi nghĩ là tôi
[00:54:14] thể chạy con bớt lại cũng được về các
[00:54:18] bạn gì thì ít nên chạy nhanh p An
[00:54:25] My Craft II
[00:54:37] anh ạ
[00:54:46] ở đây đây mà ông thấy à mặc định nó sẽ
[00:54:50] là mặt bị nói thêm cột ap tật do bạn
[00:54:54] thân đủ giờ mình không lấy thực chất thì
[00:54:56] mình sẽ phải có topic
[00:54:59] à à
[00:55:01] public hamsters
[00:55:05] anh phiêu ra mình sẽ không có cột
[00:55:09] em không có đầy đủ hay cụt I
[00:55:12] khi
[00:55:13] mà thực ra là cái thì ông có thể không
[00:55:17] không cần phải mất công điền kể quyết
[00:55:20] Tấn này được ông thể cho mặc định
[00:55:21] default nó để tới thể sửa lại cho ông xử
[00:55:25] ông không muốn Cứ mỗi làm tạo không phải
[00:55:27] thêm nào như này là sự như thế thì trong
[00:55:31] database không có thể để Phone nó đấy
[00:55:32] cũng sẽ người đều vô đây là tham
[00:55:37] không không vậy hàm đâu thì phụ nó là
[00:55:40] bên đó là
[00:55:51] nhanh nhất cũng bận mà một cái bàn đây
[00:55:53] này ông ấy ở đây đây đây Phone này ông à
[00:55:57] anh ấn vào bên này
[00:55:59] Ừ
[00:56:10] đợi tí sao ạ
[00:56:12] xe ga thẳng máy kéo nó gợi ý ra đây luôn
[00:56:17] Kỹ thuật quân sự mất ở đây nó có cái
[00:56:20] tham Zone thì gì đó Thắm xem gì đó rồi
[00:56:23] không lại với cha rồi
[00:56:25] vườn than em
[00:56:35] ở đây cũng tham gia Vậy từ nay chỗ này
[00:56:40] có ai sẽ ghi như nào cái quần xem kêu
[00:56:44] bản chất Nó là một hàm này sẽ phải gọi
[00:56:46] thì chọn ngày
[00:56:49] lý
[00:56:49] do này
[00:56:52] cô gái như này cơ
[00:56:56] Ừ
[00:56:58] ông chuyển full Chạm Tay Vào đây
[00:57:01] a password mày mặc định của nếu mà ông
[00:57:04] tạo bằng phi cơ nó sẽ mã hóa đấy
[00:57:07] Ừ
[00:57:08] nhưng mà Ừ nhà em vừa nói kìa kìa mình
[00:57:13] không chơi không biết được à Tí mình nếu
[00:57:15] thấy mẹ không biết là PQ thật tiền mà
[00:57:17] nhật được nghỉ
[00:57:19] em
[00:57:20] không kể để phụ nào rồi kìa Thì tôi
[00:57:24] không tin ở nó chạy được đâu Thì cái này
[00:57:26] mới là ấy chạy ạ
[00:57:29] em nói chị nhỉ
[00:57:32] em gửi nhá Tôi ở chỗ dùng nào rồi nhưng
[00:57:35] mà
[00:57:35] Ừ cái nào này là cái này bản chất là
[00:57:38] mình lưu lại trong đây Baker mà Thử Thử
[00:57:41] thì biết
[00:57:43] ừ ừ
[00:57:55] này nó mình bản chất Mình lưu gì nhé á
[00:57:58] anh
[00:58:04] Ừ
[00:58:05] nếu thể thao đấy không dùng lao trong
[00:58:09] trường hợp này Đấy mình sẽ phải như thế
[00:58:12] này cơ Nó giống phải tin tôi
[00:58:17] thì
[00:58:18] nó sẽ làm như thế này này
[00:58:21] Em
[00:58:28] lý
[00:58:35] ờ ờ
[00:58:37] a Rolling back
[00:58:40] Ý của bác thôi tôi chọn à quét rồi Nhưng
[00:58:44] rốt hẳn đấy không phải với phát rồi
[00:58:47] anh rất tôn tạo lại này à
[00:58:50] à à
[00:58:57] và theo thời gian hiện tại
[00:59:00] à à
[00:59:07] đấy thì password
[00:59:20] ở trường là the Gallery tơ thì tôi cũng
[00:59:23] không làm cái kiểu như thế này đâu tôi
[00:59:25] sẽ tôi sẽ tạo vào trong News Reader này
[00:59:31] cách tạo trong hồ sơ thích tôi rồi tôi
[00:59:33] chạy đến nó
[00:59:35] anh xóa bằng Story đi nhé
[00:59:38] Em
[00:59:39] muốn xóa nhỉ Có sai đi
[00:59:43] Ừ
[00:59:44] thì lại nó như này
[00:59:47] Ừ thế Hằng đầu tiên tôi vào UC đây
[00:59:51] cho tôi sẽ tự đây gần như là
[00:59:56] bây giờ này à
[01:00:00] Anh thường là tôi sẽ tạo luôn sẵn ở đây
[01:00:03] là có hai thằng Không ạ là có
[01:00:07] ờ ờ ví dụ được à
[01:00:10] ở
[01:00:18] Nghe nhạc chờ đợi tôi yêu nha game này
[01:00:22] ơi
[01:00:24] anh
[01:00:25] cơ này là
[01:00:28] anh nói cho mày không dùng đồ riết rồi
[01:00:31] nha
[01:00:32] Anh
[01:00:38] Faker là gì được
[01:00:40] cô nàng
[01:00:42] anh không
[01:00:49] em
[01:00:56] của nó để cơ Ferry
[01:01:00] không thì mình gọi thay đổi gì thôi Lâu
[01:01:03] lắm không động này đợi trông tí Đợi tôi
[01:01:05] một tí anh sẽ có sister đây đúng không
[01:01:07] là tao về quyết định này
[01:01:10] trong này suy nghĩ Ven Đô mà chuyên gia
[01:01:13] đô mà nếu mà không gọi làm cái cơ đấy
[01:01:16] thì ông sẽ phải chạy ra đúng cả ngày cơ
[01:01:18] [âm nhạc]
[01:01:25] ông phải cài thêm cái thư viện này ông
[01:01:27] trùm cái ạ cơ riêng
[01:01:30] Anh không dùng được cái hàng VIP hacker
[01:01:34] như thằng trăm phạt nhà thằng kia ra
[01:01:37] không quan trọng Tôi có thể đặt luôn ở
[01:01:39] đây thì đây nó cũng giống nhau thôi tôi
[01:01:42] sẽ quyết thẳng đi ăn miến như này à
[01:01:45] Ý
[01:01:52] thuế Để luôn label đi
[01:01:53] được phép đời sống ở level dán mi nóng
[01:01:57] lạnh
[01:01:58] em không đi
[01:02:01] bộ phim heo
[01:02:03] Em email này mèo rồi này password này
[01:02:06] chồng email giống cô ấy
[01:02:09] a password
[01:02:12] password ở đây thì tôi cứ mặc định cho
[01:02:15] 123 Phạm hình gì đã rồi tí sẽ dạy mày
[01:02:17] Ông Mười cả mã hóa nữa mình sẽ phải sử
[01:02:20] lý nha Cái thật ấy thì không cần mặc
[01:02:22] định nói với cô rồi không ạ tạm hội như
[01:02:24] thế này mình sẽ có một cái là triệu
[01:02:28] ở đây đây là amin cái còn Superman thì
[01:02:32] sao mình là mình có thể mình có thể làm
[01:02:36] đi cậu ngay à
[01:02:39] The Last Time ngay à
[01:02:43] ở
[01:02:44] đó mình lại ghét thêm thằng nữa
[01:02:48] Hôm nay thằng ạ
[01:02:51] Ê bà xã Superman này
[01:02:54] đi
[01:02:56] một ngày à
[01:02:58] v-app này đỡ mật khẩu 123 trắng ạ chạy
[01:03:02] ngay tại Hà ngay bây giờ một cách cái
[01:03:04] clip này nó sẽ luôn khởi tạo đối tượng
[01:03:07] thì không ấy không nhớ còn nếu Mấy ông
[01:03:09] không muốn làm gì thì khởi tạo được đối
[01:03:11] tượng thì mày không nghệ chơi trò là à
[01:03:15] gộp hai cái mảnh này làm một số ông chạy
[01:03:18] Hà Min shop tại thẻ Insert được rất
[01:03:20] nhiều hành cùng lúc còn Kris thì chỉ
[01:03:21] được một hàng một lúc thôi
[01:03:26] nói gì Tôi muốn gọi thằng
[01:03:29] a post này thì mình thấy có lệnh Ở đấy
[01:03:32] nó là gọi đến dịp thì ko đúng không ạ
[01:03:34] này
[01:03:36] Oh shit tắm cái
[01:03:40] em hãy thử nhà thử biết ngủ ngon
[01:03:44] ở lại à
[01:03:47] em
[01:03:52] Ừ Ok Đấy nó sẽ chạy thịt đình sheet.new
[01:03:56] ship
[01:03:57] bên này
[01:04:00] khi sex
[01:04:02] Anh
[01:04:03] ở chị hai thằng thôi chị ạ ta tạm thời
[01:04:07] chấm
[01:04:09] đó Xô sau đó đi bây giờ mình sẽ làm gì
[01:04:12] Bây giờ thì mình cứ thử
[01:04:15] Em thử kiểu tạo đầu tiên thì mày Ông
[01:04:19] thấy mặc định mình sẽ và đấu tranh mà
[01:04:21] mình giữ bình thường vợ vẫn không Nhà
[01:04:23] chồng nó chẳng có ai ngăn cản được mình
[01:04:25] đấy Tao sợ mình đây à Có khóa học này
[01:04:30] vào giữa bình thường thể xóa ở khóa đi
[01:04:32] Cái thứ cho ai càng cho mình cả ạ Bây
[01:04:35] giờ mình sẽ kiểm tra quyền như thế nào
[01:04:36] mình sẽ tạo những từ Word để kiểm tra
[01:04:39] quyền đầu tiên là nó tiên là mình sẽ vào
[01:04:42] bên router
[01:04:44] đi tắm ở đây chắc bữa đi Đợi tí Đợi tí
[01:04:48] sẽ ơi này web này
[01:04:53] cho tôi sẽ
[01:04:54] nhóm tất cả thằng này vào trong một cái
[01:04:57] gọi là mới đầu em nữa không cho một khi
[01:05:00] mà chưa đăng nhập như thế này không ạ
[01:05:02] Mình sẽ không cho kiểu tự tự vào với hệ
[01:05:05] vào lên để mà xe mọi thứ ngày giờ đây
[01:05:09] tôi sẽ có một cái router kiện nha À khái
[01:05:13] niệm giúp là theo nhóm như thế này xong
[01:05:17] rồi tôi sẽ
[01:05:18] khi sex
[01:05:19] Ừ thôi tôi có một cái gì đó một cái mạnh
[01:05:22] như thế này tạm thời Thế đã nói chuyện
[01:05:24] với anh ạ
[01:05:25] hình ảnh
[01:05:31] Tống tất cả hàng ngày nói cho tao hả như
[01:05:34] thế
[01:05:35] vì thế lúc này mình học toán hệ truyền
[01:05:37] được rất nhiều thứ ở trong này nhà ông
[01:05:39] thế mà nói chuyện được rất là nhiều là
[01:05:42] mình sẽ chuyện đây truyền những cái gì
[01:05:43] những chuyện và làm middleware như thế
[01:05:46] này
[01:05:47] Ừ cái quê mình sẽ gọi đến một thằng gì
[01:05:50] đó chính là cái thằng mà bây giờ mình sẽ
[01:05:52] tạo với ông sẽ thấy là bây giờ cái thư
[01:05:56] mục app này http này có cái thư mục và
[01:05:59] midwest này và bản chất mà mình đã từng
[01:06:01] tiếp xúc của giấy Hồng Beat the weather
[01:06:03] rồi nhưng béo nhớ là chị hết hàng sẽ
[01:06:05] được em Token này giống nhiều không ạ là
[01:06:08] nói kiểm tra cho em làm trong for Sport
[01:06:10] của mình có chuyện có quen chưa Không
[01:06:12] thì nó sẽ luôn trả về cái lỗi đúng ạ
[01:06:14] Mình sẽ tạo ra một thảm midway thì một
[01:06:18] nông trại Hàn lệnh make me the way còn
[01:06:21] Hồi đấy tôi không biết về lệnh thì tôi
[01:06:23] sẽ thương ai lấy cái hàm mặt hàng để
[01:06:25] copy rồi trả lời thằng nào đợi được thì
[01:06:27] tôi sẽ lấy hàng này
[01:06:30] thì tại sao vậy Thằng này nó có cái hẳn
[01:06:33] Hanoi xử lý xử lý bài toán ở đây là gửi
[01:06:36] Nếu mà có vấn đề gì đó thì điều hướng
[01:06:38] quay trở lại còn không thì vẫn cho phép
[01:06:41] Tiếp tục chạy như thế này đấy tôi sẽ rất
[01:06:44] nhiều tôi copy này
[01:06:46] là mấy ông chạy cái hình như có lệnh Hồi
[01:06:49] đấy à Tôi nhớ không có lệnh cơ để make
[01:06:52] make me the way bây giờ Chắc có rồi
[01:07:00] gì
[01:07:01] I make the wand
[01:07:04] mình sẽ cần kiểm tra ở đây là mình cần
[01:07:08] kiểm tra với quyền là tôi tôi đang định
[01:07:11] làm bài toán nó là như thế này với
[01:07:13] với kiểu dạng là với ạ
[01:07:19] a
[01:07:20] Superman thì làm được hết mọi thứ chắc
[01:07:23] chắn rồi với admin thì sẽ có thể là là
[01:07:28] mình một là mình sẽ chỉ cho xem khỏe bên
[01:07:31] này tí nhé Một là mình sẽ chỉ cho xe làm
[01:07:34] bên làm việc với sư đơn còn bên A khóa
[01:07:38] học này cái thứ gì sẽ không cho truy cập
[01:07:40] chẳng ngại là sư Thế là sự dễ hay là
[01:07:43] thực ra là admin ta vẫn để xem mình tất
[01:07:46] cả hàng ngày không ạ nhưng mà không
[01:07:49] không được quyền để vào bên xóa là Nhạn
[01:07:52] đấy cả hai hàng ngày thằng thoảng admin
[01:07:56] sẽ không được vào quần xóa lạ thì tôi sẽ
[01:07:58] làm nha Thì bây giờ mình sẽ có một cái
[01:08:01] chết log in vào một cái là check
[01:08:03] Superman
[01:08:04] sẽ có một cả chết cho we
[01:08:07] did when i khi sex ở nhà
[01:08:19] kỹ đó là đây một cái rất hay đó Lara nào
[01:08:22] luôn Chạy qua mọi file của nó thao ngày
[01:08:26] Facebook với và nó sẽ chạy vượt qua mọi
[01:08:28] vai bây giờ mấy ông thấy à Rõ ràng là
[01:08:30] tôi chạy cái sớm ở đây này mấy ông Nghĩa
[01:08:33] nó chẳng ảnh hưởng gì cốt của ông Út Của
[01:08:36] Ông mới hay đang đang kiểu dạng như ai
[01:08:38] đang để trống chửi như thế này đang lỗi
[01:08:41] mặt cú pháp này ạ Ông nghĩ nó không chạy
[01:08:43] đến nhưng không Nó đã chạy qua tất cả
[01:08:45] các file rất nhiều file không phải tất
[01:08:48] cả nhà nó hơi sai nhưng mà học viên Quốc
[01:08:51] và luôn Chạy có rất nhiều file và bao
[01:08:52] gồm có cả phải này thì ra nó bị lỗi nên
[01:08:55] là bây giờ tôi sẽ phải ẩn đi nha Nếu
[01:08:57] chạy được đấy ở
[01:08:59] đó có phải tạm được biết the weather có
[01:09:03] là bây giờ có thêm lệnh mới rồi đây nó
[01:09:06] cũng là hai đồ đúng ạ
[01:09:08] mặc định là nó sẽ cho thông qua như thế
[01:09:11] này Đấy giờ mình sẽ xử lý nó như thế nào
[01:09:13] sẽ kiểm tra nó thì ah
[01:09:23] như thế này
[01:09:26] mấy ông sẽ nghĩ ra mà tôi thể hoàn toàn
[01:09:28] ưu thẳng như này không ạ
[01:09:30] từ
[01:09:32] ngày đó ạ
[01:09:34] có ngon không thường là chúng ta sẽ
[01:09:36] không làm thế này chúng ta sẽ có khái
[01:09:38] niệm là major beat Where the weather lum
[01:09:43] như này
[01:09:44] anh không biết ở Hồi đấy có đúng chậm
[01:09:46] Nhưng em nha Đợi tôi đợi ông tí gì Như à
[01:09:49] Không ai làm cho cậu
[01:09:52] tạo như thế này Tại sao với tạo như thế
[01:09:54] này nó không
[01:09:56] anh
[01:09:57] không được rồi bạn ạ
[01:10:00] Ừ bắt buộc ở chúng ta sẽ phải tạo một
[01:10:03] cái ở đây nữa tôi thường hay tạo thì một
[01:10:05] ngày nữa ở đây như thế này
[01:10:06] anh
[01:10:07] làm sao đội Chỉ có xe máy vụ mới được
[01:10:10] qua đã lâu không động mạnh
[01:10:13] Nghe danh sách này the weather
[01:10:16] có
[01:10:17] ai báo khởi tạo các từ thử nhá ngon
[01:10:21] cài đặt tên file này là
[01:10:24] ở tập Tina
[01:10:26] a force mix đồ
[01:10:29] v-app Tomato web có thể xử lý trước và
[01:10:32] sau này
[01:10:34] cô
[01:10:42] hết vào trong cài giúp kiểu như này
[01:10:44] chồng với nhau mà
[01:10:47] ở
[01:10:52] Tâm ít được nghe hay à Ô tô mesa Group
[01:10:55] Có ai có thể dùng sai rồi Như thế này
[01:10:57] được đấy
[01:10:59] ạ Và bây giờ cho dùng trai ở đây tôi
[01:11:01] toàn dùng trong group coi
[01:11:04] từ
[01:11:05] ngày tôi sẽ tải một thằng tôi sẽ copy
[01:11:07] Thành ngày để tả một dòng sông xong tôi
[01:11:10] thường hay dùng kiểu cách đấy hơn
[01:11:13] anh
[01:11:13] ở đây tôi không dùng kiểu này đâu à
[01:11:18] Ừ
[01:11:18] bắt thêm webcam
[01:11:20] cần nhìn mà tôi làm gì
[01:11:24] đây tôi sẽ đặt tên nó là là ăn mini
[01:11:31] ảnh mà thằng này nó dễ kiểm tra thêm một
[01:11:34] cái là trách
[01:11:36] một
[01:11:38] ngày sẽ kiểm tra thêm một cái là
[01:11:41] A
[01:11:43] sex.in Hiện nay tôi hoàn toàn tôi gọi
[01:11:48] được nó ở đây như thế này
[01:11:50] Ok chưa
[01:11:53] Ừ
[01:11:57] ở nhà anh Khánh à
[01:12:00] ở đấy và bây giờ
[01:12:03] ạ bây giờ đương nhiên là cái này nó đang
[01:12:05] đang triệu vẫn cho mình thông qua
[01:12:08] tắt bớt ở ngoài đấy ạ Ừ nếu không thấy
[01:12:12] vào vẫn bình thường phải sao cả Nhưng
[01:12:14] bản chất à bê tôi thử acro một ở đây
[01:12:17] xong rồi axit em ạ
[01:12:19] axis Nó cũng kiểu giống như D Đó là nắp
[01:12:23] toàn bộ đằng sau dừng nó cố tại đây
[01:12:28] đó thì ông thấy là nó đã chạy chạy qua
[01:12:31] tâm lý thói quen này không ạ Đây cách
[01:12:33] kiểm tra đấy không không cho
[01:12:36] em không cho mấy ông can thiệp tiếp ăn
[01:12:39] thịt tiếp là sẽ Cậu chọn lấy cái quét
[01:12:41] cho này Bây giờ thì da mình chưa làm thì
[01:12:44] đăng nhập ạ Đây mình sẽ thử ít mình kiểm
[01:12:48] tra chứ sân là kiểm tra thí sinh kiểm
[01:12:50] ngay thôi gọi cùng anh nếu có thể dùng
[01:12:53] Cài á
[01:12:55] khi con 2 cách gọi của season 1 là ông
[01:12:58] dùng kiểu này hai ông sẽ được
[01:13:01] đi hẳn chứ sân ngay để ông import cái
[01:13:04] này vào kiểu như này tôi thường hay dùng
[01:13:07] cái không biết post thì cho
[01:13:09] trong một lỗ trống em nghe
[01:13:13] Ừ thôi tôi cháu không thích dùng 2 Harry
[01:13:15] Potter lắm cái kiểu như thế này thì nó
[01:13:17] là hết Thôi nào đeo nó cũng là tương
[01:13:20] đương thằng chia đôi không khác gì đã sẽ
[01:13:22] kiểm tra đây ví dụ hát ở đây là là có
[01:13:26] thể là hát cô dâu này kẹo kiểm tra đăng
[01:13:29] nhập thì ở đây mình sẽ kiểm tra chỉ cần
[01:13:32] level luôn được
[01:13:34] ai kiểu này
[01:13:36] các
[01:13:37] em à Không có
[01:13:39] anh không có thì mình sẽ điều hướng quay
[01:13:42] trở lại nữa hả Mình quay trở lại trang
[01:13:45] đăng nhập thì direct
[01:13:48] có nhiều router
[01:13:51] Ừ
[01:13:57] phải trả đăng nhập đúng
[01:13:59] Vì thế tôi phải tạo đây một cái Trang
[01:14:01] đây là
[01:14:04] đăng nhập đã
[01:14:06] Anh thường là tôi sẽ tạo một controller
[01:14:09] chị xử lý vụ đăng nhập đăng nhập đăng
[01:14:12] xuất như thể đặt tên nó là vâng
[01:14:14] controller được hoặc là nó tin các chợ
[01:14:16] được gì tùy
[01:14:19] họ thì cần chất lượng của ông không biết
[01:14:22] là tôi nói gì thường hay đặt tên nó lót
[01:14:25] inventor lâu thì tôi cứ tạo cái
[01:14:28] file Word và trả lại nhá mấy
[01:14:32] khi sex
[01:14:33] Ê con chó này à
[01:14:37] à à
[01:14:40] Á
[01:14:41] Châu Cần Thơ cũng chuẩn
[01:14:44] cài
[01:14:45] đặt tên Audi mày về sau bạn đã toán liên
[01:14:48] quan đến mấy cái được phân quyền cá thứ
[01:14:50] đẹp đây được
[01:14:53] Ừ anh đừng trêu em mới buồn
[01:14:56] anh nói cho đại khái như này với con xin
[01:15:00] lỗi này
[01:15:02] à à
[01:15:06] Anh
[01:15:07] ấy ở đây sẽ là
[01:15:11] anh
[01:15:23] I Found Love
[01:15:25] anh ấy
[01:15:49] nội y cho
[01:15:51] tôi Gõ thỉnh thoảng nó bị sai thì đó
[01:15:53] chưa quen cái bàn phím lắm mới mua bàn
[01:15:55] phím bàn phím này tôi đang mua là bàn
[01:15:58] phím nó nó nhỏ hơn là kín cũ khá nhiều
[01:16:02] vì tôi muốn cậu Cái con laptop mới này
[01:16:06] của tôi cũng mua rất là gọn nhẹ và bàn
[01:16:08] phím rất gọn nhẹ để mà vì sao mình đem
[01:16:10] đi di chuyển có thứ về sau muốn máy khỏe
[01:16:14] rồi tôi sẽ đi một con sợ PC mà ăn Mày
[01:16:16] tình cây sau đó
[01:16:18] bộ phim
[01:16:19] gì vậy tội chẳng biết nó xúc gì à Nó là
[01:16:24] một bàn phím cơ giá rẻ thôi
[01:16:27] 2009 người con cũ nó bé gọn nhẹ
[01:16:32] Ừ anh đợi nó sẽ chuyện với ông theo Bây
[01:16:36] giờ cứ vào bất kỳ đâu Với ai sẽ đều
[01:16:39] hướng quay trở lại đấy đây như bên này
[01:16:43] mình đang chưa làm gì cả Đây mình sẽ ghi
[01:16:45] tên về một cái view chỉ liên quan đến á
[01:16:47] đăng nhập thôi thường là đấy nó là gợi ý
[01:16:51] rất là hai này mình sẽ có một số mục
[01:16:53] liên quan đến au hợp lý mình sẽ có mấy
[01:16:57] thư mục Đoài
[01:16:58] hình
[01:17:00] ảnh Sony Cái ở có wi-fi là
[01:17:03] Lê Ngọc Kim
[01:17:05] a template
[01:17:08] ppt ê
[01:17:11] anh
[01:17:16] chẳng biết hãng gì hay không nổi lắm đâu
[01:17:18] anh ờ
[01:17:19] Ừ cái này thì thực ra bổ vỉa Hồi trước
[01:17:22] và mình ôm cái tem led kìa hyper về
[01:17:26] không nhiều không ạ
[01:17:28] thì mệt với ông hệ hoàn toàn lấy cái
[01:17:30] giao diện đấy
[01:17:32] Ừ cái dòng điện have đội bay rồi
[01:17:35] Ừ
[01:17:37] rồi đi
[01:17:39] ở nhà máy này chưa Tôi chưa tải cái
[01:17:42] anh ở đây
[01:17:44] Ừ vậy thì kéo dài nhé
[01:17:47] cho
[01:17:59] nông dân đi
[01:18:08] em hết hot đã chuẩn bị nhảy đến router
[01:18:12] là
[01:18:19] in a
[01:18:27] làm thẻ nó là động từ
[01:18:29] cũng rất là hay
[01:18:32] Em Hát Cho đẹp cái gì quan trọng gì đẹp
[01:18:35] ở đây
[01:18:36] kiến thức rồi xấu xấu nó đôi khi lại đỡ
[01:18:40] giật đa cấp
[01:18:41] à À đây mình phải email nhé email này à
[01:18:46] ở hà email name email tiện phết
[01:18:50] a
[01:18:55] phim hài
[01:18:58] a password mềm password with
[01:19:02] đúng ở mấy cái rồi được làm nhiều đề
[01:19:06] xuất chuẩn nó hơi này
[01:19:11] ờ ờ
[01:19:17] 30 chưa khai báo cái mô tơ đúng ạ cho tơ
[01:19:22] này mình sẽ mình sẽ làm nó cho nó sẽ nằm
[01:19:25] ngoài nó biết là quen ngồi trước đã có
[01:19:27] ông biết sử cái này vì trong cơ bên
[01:19:30] trong mí thói quen này chỗ chưa đăng
[01:19:31] nhập thì đều hướng về cái trang đăng
[01:19:34] nhập nhưng cái sao nhập lệnh nằm trong
[01:19:35] phải đăng nhập rồi hai nó vòng là Thùy
[01:19:38] Dung treo luôn máy đấy mấy ông cố chạy
[01:19:41] được đấy nhé
[01:19:42] anh chạy xe post này Cái vẫn có thể cùng
[01:19:45] với ai thôi em nói rất là nói cái này
[01:19:47] trở lại nó phối xác Nói nó ạ
[01:19:50] Tôi muốn xem
[01:19:53] anh nói này cách viết ở đây sẽ phố xét
[01:19:58] anh nói nặng
[01:20:00] ừ ừ
[01:20:06] JAV HD với anh
[01:20:20] điền dụng là
[01:20:22] admin@gmail.com đó thì mật khẩu là có
[01:20:26] đúng đã nhá là 123
[01:20:28] bấm lõi là này mình sẽ tạo cái Hàn này
[01:20:33] thì
[01:20:34] mình sẽ tặng với ha Nó thích tăng sinh à
[01:20:39] hai
[01:20:39] tay mẹ sẽ nói Im ngay
[01:20:43] thì mình sẽ lấy
[01:20:46] đi quét
[01:20:49] Anh
[01:20:50] đi quét
[01:20:52] số 1 là ông vay đét cũng được không
[01:20:55] virus đoạn này tôi hôm nay vậy nha nhưng
[01:20:59] tạm bỏ qua vụ vay biết có gì với ông
[01:21:01] phải đến sau nhá
[01:21:02] Tôi sẽ lấy à
[01:21:06] ở đây tôi sẽ lấy cái
[01:21:09] số người dùng về đô Rio de bằng Urê này
[01:21:14] khi Harry
[01:21:20] cho gọi đến que
[01:21:24] Em email
[01:21:26] vì
[01:21:28] vậy Ngon phết nhỉ à
[01:21:30] Ừ thôi Tôi ghét kiểu dùng cho bằng được
[01:21:34] tôi dùng thẳng luôn chỗ này cơ
[01:21:37] a
[01:21:38] password password này
[01:21:41] em
[01:21:49] Ừ Ok ai
[01:21:52] ở
[01:21:57] của nó thì nhớ tôi từng nói với ông rồi
[01:21:59] nó sẽ bắn về exception nếu mà là sử
[01:22:02] không tìm thấy thằng nào thì mình sẽ
[01:22:04] xoay cát ở đây rồi dậy mà ông khái niệm
[01:22:07] luôn chai cát mình sẽ mình sẽ chai là
[01:22:11] mình sẽ thử một cái gì đó như thủ tán
[01:22:13] gái ạ xong rồi cát ở đây là là bắt các
[01:22:17] trường hợp đều bắt Trường hợp nếu mà một
[01:22:20] tỉnh ông ở đây là 60 bồ như thế này là
[01:22:22] bắt mọi trường hợp bao gồm cả lỗi lô gic
[01:22:24] về lỗi của phát nó sẽ nhờ vào đây một
[01:22:28] cái tướng đồn đó nha Có vài lỗ của Pháp
[01:22:29] thì khi biên dịch à ở tp nào lỗi hỏng
[01:22:33] luôn thì nó không thể lấy đâu xử ông
[01:22:35] thiếu chấm phẩy anh thế này là đôi khi
[01:22:36] nó không để đây đâu em có rất nhiều lỗi
[01:22:39] khác thì nó sẽ nhảy vào đây nhờ khi ông
[01:22:42] Toàn cái ta cũng họ lỗi lầm bằng sẽ nhảy
[01:22:44] đây trở lại thêm sự xử lý gì thì ông có
[01:22:47] thể hoàn toàn là điều hướng quay trở lại
[01:22:49] kèm thêm cái lỗi
[01:22:52] ở
[01:22:58] thêm một cái gì đó mày không nhiều không
[01:23:00] ạ Cái
[01:23:03] em
[01:23:04] còn đây trong trường hợp nếu đúng thì
[01:23:06] sao mình sẽ Mình sẽ lưu lại trong sân
[01:23:10] tôi chưa dùng lao vậy thôi chị làm cái
[01:23:13] khuôn thôi sẽ lưu lại thí sinh mình sẽ
[01:23:15] là lưu lại phút thí sinh này
[01:23:19] khi mình thừa mình không cần lưu lại
[01:23:21] email ở trong thí sinh sẽ lưu lại là
[01:23:24] mình sẽ lưu lại đi người anh đăng nhập
[01:23:26] này
[01:23:27] ông bà với một sớm thế
[01:23:30] a
[01:23:38] sao mình cần mình cần là mình ý mình có
[01:23:44] thể sử dụng liên tục avatar của chị ra
[01:23:46] người dùng thực a
[01:23:48] người dùng khi mà vào đăng nhập vào
[01:23:51] người ta sẽ luôn nhìn avatar đã cả tên
[01:23:53] của họ trên ike và bạn chất mình sẽ luôn
[01:23:55] lưu lại những cái điều đấy nên này
[01:23:59] em nói chuyện nghe
[01:24:01] nói điều hướng quay về thường là tôi sẽ
[01:24:04] điều hướng quay về trong welcome nhưng
[01:24:06] mà đây tôi không có trang Web Cam ấy tôi
[01:24:07] cứ mặc định là là Trang Trang này nek
[01:24:11] nhé
[01:24:12] ừ ừ
[01:24:22] tuổi xem lại phim Bấm ở đây vì nó không
[01:24:26] quen được bàn phím lắm mà ông thấy tôi
[01:24:28] gọi chậm hơn phạm ký
[01:24:36] anh em báo lỗi thế à
[01:24:38] ở Hà Nội Kệ ông ta không gặp
[01:24:41] anh ơi
[01:24:42] ý
[01:24:43] định chuyển về kệ không tin à
[01:24:49] a good là đẩy ra còn phút là phút là đẩy
[01:24:53] vào và tôi nhớ không làm mình bị lỗi nếu
[01:24:57] trong trường hợp mà đã có giá trị lấy
[01:25:00] rồi còn phút là bạn đặt vào theo kiểu
[01:25:03] lại nếu mà có ra sự có cái thang này
[01:25:06] trong đấy rồi nó sẽ ghi đè lên đấy à
[01:25:10] có
[01:25:18] à à quên quên quên quên
[01:25:21] Lê
[01:25:21] Hiếu cái ông biết tại sao nó quay lại
[01:25:24] vẫn quay trở lại biết đâu nhưng không vì
[01:25:26] mình quên chưa có cái level nhảy
[01:25:30] ạ
[01:25:38] não quá em tôi nói gì vậy đấy
[01:25:49] anh
[01:25:50] không đúng không phải ví dụ mà tôi chưa
[01:25:53] dùng ao thật tôi chưa Rủ nhau với chồng
[01:25:54] chưa Dùng cái đấy chứ cái ao chưa dùng
[01:25:57] cái Pocket tôi tôi chưa dùng lên tôi
[01:26:00] chưa dám Vậy thôi heo tôi mà chắn trên
[01:26:02] cái đấy giờ tôi sẽ dậy mấy ông nhờ Nếu
[01:26:05] mà nói qua tốt Nó quay Vũ Xuân luận được
[01:26:08] tốt mà sao
[01:26:11] Em về đây đi đó nhiều người không thấy
[01:26:13] phải sửa lại và ta ở đây tên ở đây không
[01:26:16] phải định đúng tên mình không ạ thì mình
[01:26:18] sẽ bên À cái này nhiên nằm trong Clow
[01:26:21] vậy
[01:26:22] bên
[01:26:23] bên hết đồ
[01:26:25] sửa lại tên
[01:26:28] từ
[01:26:28] lúc đào này ok
[01:26:31] anh em ở Quốc đảo nào đó
[01:26:34] ở ngã tư đốt tao đi
[01:26:46] Vì sao tay phết nhỉ
[01:26:49] em
[01:26:51] không cho
[01:26:53] để lại phần mở sau khi tất nhiên rồi cậu
[01:26:56] nhỉ
[01:26:58] ừ ừ
[01:27:04] Are You Now out
[01:27:07] Em đâu rồi
[01:27:09] Anh
[01:27:10] ấy chạy chậm đi À đây
[01:27:13] có ai đóng Đây xóa đây
[01:27:16] lại phải đi thuê
[01:27:19] có
[01:27:19] ai nữa không quan trọng Đấy đóng xóa đây
[01:27:24] ở
[01:27:26] Hà Nội
[01:27:30] rau cắm xuất tinh lock out đã để lại cái
[01:27:34] này
[01:27:35] mình có sốt không nhỉ
[01:27:44] em gái
[01:27:46] Ừ
[01:28:03] vào đây thì chị ra thôi cảm ơn
[01:28:05] Ơ hay
[01:28:18] Ok Good For You
[01:28:21] Em
[01:28:23] có chị này thôi Nó đối đúng ạ Đây này
[01:28:27] mình sẽ chạy tên là Đây này xin
[01:28:32] like rồi đấy mình sẽ đây bà
[01:28:38] Bởi vì tôi chưa cài cài đặt biết về mày
[01:28:43] không phải ngon hơn
[01:28:44] tôi cái
[01:28:46] anh ạ
[01:28:52] read này
[01:28:55] Ừ cái hết về cho bé uống xem nhé ngon
[01:28:57] luôn
[01:28:58] biết hay tơ này
[01:29:02] em ngồi Blade
[01:29:04] ở đây nè
[01:29:07] mình nha
[01:29:09] xe Blade
[01:29:16] cứ mấy cái đầu tiên chơi hết toàn bộ cái
[01:29:18] đầu tiên à
[01:29:21] Xem phim sex online
[01:29:23] em tắt đi mở lại
[01:29:26] bài
[01:29:31] đấy
[01:29:35] có mình sẽ có season II
[01:29:39] khi họ
[01:29:41] A Z
[01:29:46] Ừ để nêm
[01:29:49] Ừ cái này sẽ à Đi vụ
[01:29:52] ông ngoại
[01:29:54] về giá rẻ nhược điểm level nhà mình sẽ
[01:29:57] phải chia trường hợp đó là
[01:30:01] à à Superman
[01:30:12] à à Tôi chưa cập nhật Cái qua cho mày
[01:30:16] Ừ
[01:30:21] xe ô tô ghi cái này nha nha không thể
[01:30:24] sửa lại cái gì của khác nha nó
[01:30:33] cô giáo sư gái đi
[01:30:36] mình phải thì Avatar ở đây mình chưa có
[01:30:39] chưa có nên cho anh định đi k a
[01:30:43] ông
[01:30:48] amin à
[01:31:02] thấy cố tình nói qua với vest buồn với
[01:31:06] anh
[01:31:06] anh cũng gỗ em đâu à OK thì con cái gì
[01:31:12] nhỉ
[01:31:13] khu
[01:31:14] vực trung tâm đổ như thế này thì mấy ông
[01:31:17] sẽ thấy à tôi copy được lên này
[01:31:20] vào ẩn ra nhưng mà ông thấy yêu cầu lông
[01:31:23] nhật vì rõ ràng là chưa đăng nhập gì cả
[01:31:25] Không ạ Còn bây giờ thì đăng nhập rồi
[01:31:28] nếu không thể xem ở trong nhà cái đi gấp
[01:31:31] ba này thì sẽ thấy trong sinh mình có có
[01:31:34] thí sinh mình còn lưu lại cái thứ trong
[01:31:37] thích thân với ai lại cho tiện chỉ nó có
[01:31:40] cái mí từ que ra ngoài được này
[01:31:42] trong này nó có ghét hay mấy chục cái gì
[01:31:45] đó cơ nhưng không Tớ ở đây
[01:31:48] thông qua hai giờ biết thử que
[01:31:50] webgame in thông qua web-8000 này ra à
[01:31:55] cho tôi khi tôi xóa cứ vậy á ở bên này
[01:31:59] đi được tôi chỉ có mỗi cái này đâu không
[01:32:00] nhỉ
[01:32:01] Anh bảo làm thông qua web mà tại sao
[01:32:04] mình phải gọi tận hai thằng nhỉ
[01:32:07] Ừ ừ
[01:32:08] con bé ông không tầm cái này vào đây lâu
[01:32:12] nha tổng cái này vào đây còn phải đăng
[01:32:14] nhập mấy ông cũng yêu cầu đăng nhập
[01:32:18] ừ ừ
[01:32:25] thế thì có khi không cần phải làm dạo
[01:32:27] này đâu không cần phải tạo giúp mới ngay
[01:32:29] đâu cũng chích thẳng luôn đấy ngay à
[01:32:32] ở thời tiết thế Làm dạo này thì đơn giản
[01:32:35] hơn
[01:32:36] ông chủ nhật thôi nha tự tử
[01:32:40] Ừ rồi đấy à Hồi tôi dùng ở tận level 5
[01:32:43] chấm với nó không có kiểu như hai em
[01:32:46] không biết
[01:32:47] Ừ
[01:32:48] anh Thủy Tại sao không lỗi này mở ẩn ra
[01:32:53] nhà đó ngon ngọt ngon đấy Tại sao thì
[01:32:58] thấy là nó sử dụng hai cái Ok ok Thế thì
[01:33:01] nếu ở trong trường hợp mà ông chỉ có cần
[01:33:04] 1 lít được về cho nó cái nhìn này gọi
[01:33:06] cái này cho nhanh đỡ phải đỡ phải khai
[01:33:08] báo ở trong Canon để mà tạm một mic
[01:33:10] Facebook nữa được à
[01:33:14] An
[01:33:22] nhà
[01:33:22] đất phúc chính là cái này đấy Yêu mà sao
[01:33:26] tấm cái chết nói nói cho nghe
[01:33:29] Ừ
[01:33:30] ok
[01:33:32] rồi tôi nói qua mày không phải biết được
[01:33:35] nghe và đăng nhập Thế bây giờ còn tạo
[01:33:39] thêm một cái midwest nữa là để kiểm tra
[01:33:41] nếu trong trường hợp là là kiểu Xóa
[01:33:46] Thằng hạn thì thì sẽ phải thêm nóng ạ
[01:33:49] Em
[01:34:00] Cô Bơ ăn Minh đã nhắm được tài ở dễ hiểu
[01:34:04] nha à
[01:34:07] trò
[01:34:07] chơi Superman
[01:34:10] nhà sản xuất đã chuẩn bị đang xuất với
[01:34:13] ẩn danh mà ông ấy có ngay cái gì nó suốt
[01:34:16] à
[01:34:18] Ừ nếu ông thư da bạn đoạn này thì kiểm
[01:34:21] tra là dễ thôi bởi vì mình bản chất là
[01:34:24] mình cần kiểm tra ở chỗ nào Chỗ này thì
[01:34:28] ra vì chuộc này mình sẽ phải thêm một
[01:34:29] cái là
[01:34:31] So sánh bỏ quá đi cho này ngay tại sao
[01:34:36] mà mình sẽ tạo thêm một cái thằng router
[01:34:38] giúp nữa
[01:34:40] cài
[01:34:41] đặt tôi đã đi cái thả Thằng Đô Tao giúp
[01:34:45] nữa
[01:34:46] Anh ở người cùng đi
[01:34:49] một
[01:34:51] ngày sẽ là trách
[01:34:54] về Superman
[01:34:55] [âm nhạc]
[01:34:57] - the West
[01:35:00] 3nana đó
[01:35:03] ở đó
[01:35:05] hai bà ngày sẽ có lô tô
[01:35:10] các bạn này hơi thủ công một tí thường
[01:35:12] lần thứ ba về xong nếu không dùng vì
[01:35:13] suốt ngày đâu
[01:35:14] con gà làm công ty ông Toàn lại đi đầy
[01:35:18] đủ lao công ty tôi xuống hay không dùng
[01:35:20] hết đây sẽ là Delete này
[01:35:24] đi later sau đây sẽ ra
[01:35:28] a cost
[01:35:32] Xóa ID đó anh sẽ đi trôi
[01:35:38] hình ảnh có
[01:35:40] đi chơi tương tự thế với à
[01:35:44] Chứ đừng thôi
[01:35:46] Ừ từ đình tôi đình
[01:35:49] đi soi này và ngày cũng sẽ loạn đi cho
[01:35:53] ra nhưng ai đó
[01:35:56] Ừ cái thử nhỉ Bây giờ đang là đăng nhập
[01:36:00] admin đúng không ạ Cho tôi thử Ánh xóa
[01:36:03] xóa đâu nha À quên quên và xóa được Đấy
[01:36:06] mình đã kiểm tra rồi không lấy kiểm tra
[01:36:09] này để kiểm tra là nó chứ Xuân
[01:36:12] à à
[01:36:14] có nét level
[01:36:18] ở
[01:36:19] bang bang bang balô bạn đi Nó không chắc
[01:36:23] chắn là kiểu nó nó làm nhìn thì mình khi
[01:36:28] vi Jack bác không không phải quay lại
[01:36:31] trang nữa không phải quay lại trang
[01:36:34] đăng nhập đây nhá Mình chỉ cần kiểu quay
[01:36:37] lại thôi
[01:36:38] anh quay lại không không cho làm thịt à
[01:36:41] nha không thể kèm 2 cái lỗi được
[01:36:52] I miss đá
[01:36:54] xe lửa đã đi hôm nay
[01:36:57] à À quên quê
[01:37:00] Ừ cái À cái này mình nghệ đang dùng ipad
[01:37:03] nên thành ra là không
[01:37:05] anh không không cần điều hướng gì cả em
[01:37:08] ạ
[01:37:09] cho mình mình không điều hướng được đoạn
[01:37:11] này vì mình đang dùng ánh mắt để xử lý
[01:37:13] nhà tôi tôi thử tôi thử để nó là kiểu
[01:37:17] dạng là bỏ ra đây nhá Tôi tạo bỏ rác đi
[01:37:19] điều hướng cho bé ông ta mãi nhé Rồi tôi
[01:37:22] á
[01:37:23] em
[01:37:24] đã bỏ đi này BN có này không biết
[01:37:30] I love
[01:37:37] chỉ cần nút này hồi đấy nó là nút là bất
[01:37:41] cần tôi đổi nó nút anh mất đừng nên
[01:37:43] thành ra là à
[01:37:44] xe đạp đua đòi
[01:37:47] ở đây hay cuối tuần mẹ nó không dám ít
[01:37:50] nhưng mà
[01:37:52] nó sắp ít như này cho nó thì bỏ cái cái
[01:37:57] đoạn cô này đi khi bấm với nó sẽ sắp với
[01:38:00] phom thì sẽ như thế nào
[01:38:02] anh
[01:38:04] bấm mày đó mày Ông thấy nó quay trở lại
[01:38:07] thằng một nó vẫn chưa bị xóa đúng không
[01:38:09] ạ Mày không thấy thằng một nãy giờ chạy
[01:38:11] đi chạy lại nhưng nó cũng sợ xóa không ạ
[01:38:13] Đấy và B nếu trong trường hợp mà giờ sự
[01:38:17] ông muốn dùng gấp mà xử lý nếu như cái
[01:38:20] bosston không cho chấm bi form đoạn này
[01:38:23] ông sẽ xử lý gì ông sẽ cầm ném một cái
[01:38:26] lỗi ở đây
[01:38:28] Bắn về một cái lỗi gì đó để nó sẽ và ông
[01:38:32] sẽ xử lý ở trong Alo Này ấy ông thế à
[01:38:35] đây sẽ là thường dâu
[01:38:38] anh như này đâu anh Xuân hoa cà
[01:38:43] sau đi Sầm Sơn à
[01:38:47] Nhớ
[01:38:59] Ừ
[01:38:59] đợi tao tí
[01:39:02] u sầu notation
[01:39:04] nhớ có phím tắt thế mà làm bộ này
[01:39:09] à à
[01:39:10] ở lại Sony expansions
[01:39:20] có
[01:39:25] anh nghe cảnh báo tôi trong thường em
[01:39:28] sao
[01:39:29] đi
[01:39:37] lên so với sẽ chuẩn hay nói lên như nào
[01:39:39] nữa thử thử nhé
[01:39:42] ở
[01:39:44] đây nó sẽ bắn về một cái là
[01:39:48] à à
[01:39:49] Anh không được làm thế ạ ạ Dừng lại đi
[01:39:54] đừng anh ngủ ngon Anh cứ hết
[01:39:57] anh
[01:39:58] nghe cái địa chỉ
[01:40:01] sản phẩm này
[01:40:03] ông
[01:40:08] bây giờ bấm vào đó nó sẽ bạn với lỗi 500
[01:40:13] này và trọng tâm xô nó sẽ nhảy vào Alo
[01:40:17] không ạ
[01:40:18] ở
[01:40:19] đây thì hoàn toàn không thì xử lý ở bên
[01:40:22] A bên Euro này ông làm đi về đâu là đây
[01:40:27] được có tôi sẽ dậy Nếu không phải đa
[01:40:30] ngôn ngữ nữa Cái này nó là cái lô kết
[01:40:33] lâu cái gì đấy
[01:40:35] Climb Racing video này tôi sẽ dậy người
[01:40:40] hôm sau
[01:40:41] Ừ cái đấy Đúng là cũng nhưng mà ít áp
[01:40:44] dụng ví dụ trong đồ ăn hay của mấy ông
[01:40:46] được cả nó chỉ có tiếng Việt hoàn toàn
[01:40:47] thôi không nói dụng làm gì cả tao diện
[01:40:50] mấy ông đồ ăn hay nói tiếng Việt nhé Có
[01:40:53] thể cốt mấy ông ấy cố tiếng Anh bản
[01:40:55] tiếng Anh nhưng mà nó hiện lên tiếng
[01:40:56] Việt với mấy ông chương trình Tiếng Việt
[01:40:59] ngồi tôi ngồi đọc Nếu hết lưỡi tiếng Anh
[01:41:02] trong buồn cười lắm ý
[01:41:05] ờ ờ
[01:41:07] khi con gì nhỉ Đấy vừa rồi tôi đã nói
[01:41:10] qua cho mấy ông cảm thấy thích sân cả
[01:41:12] biết được nghe đấy còn sao nói gì mấy
[01:41:14] đúng rồi đúng rồi ông bà ấn nút đi đúng
[01:41:17] không không hiển thị nút thì nó đơn giản
[01:41:20] mà mình sẽ kiểm tra thôi kiểm tra đúng
[01:41:23] Bạn nói đúng đấy anh sẽ ẩn đi
[01:41:26] Ừ nhưng mà anh nghĩ ở đây thì ra mày
[01:41:29] không thấy có nhược điểm là đi nó cũng
[01:41:31] hơi phải sử dụng vào nhiều chỗ anh sẽ
[01:41:34] yêu chỉ mấy ông nếu dùng là mau chóng
[01:41:37] nhận kịch đoạn code này nó cho mà ngắn
[01:41:40] hơn tao ấy chỉ như này thôi đấy kiểm tra
[01:41:43] đã như nào đó nhưng mà
[01:41:46] ở đâu Nó không kiểm tra được level 2
[01:41:49] nghe mình vẫn lại chơi rồi nha
[01:41:58] mà bằng bằng 1 thì mình mấy thì chị ra
[01:42:02] cái này chắc lại
[01:42:03] em ít à
[01:42:13] Ê mấy ông có một sự thật là mấy ông nghĩ
[01:42:15] cái này pp đúng không Nhưng thực ra cái
[01:42:17] này nhúng bất kỳ động được nhúng nó
[01:42:19] xuống cả bên A
[01:42:21] bên ta Swift trở lại được này
[01:42:24] cho
[01:42:26] dù nó cách báo này Kệ nha
[01:42:30] em
[01:42:35] ở
[01:42:35] đó mất nút chưa Ok chưa Không có nút thì
[01:42:39] sẽ không chuyển bấm nhầm đúng không ạ
[01:42:42] Ừ ok chưa ạ
[01:42:45] ờ ờ
[01:42:47] khi sex đề thi ở đây mày không thấy cái
[01:42:50] đoạn này ra cứ lập Điệp lại nó hơi khó
[01:42:53] chịu một tí nhưng giờ tôi sẽ chỉ luôn
[01:42:55] cho ông thêm một cái nữa Nếu không thấy
[01:42:58] vừa rồi tôi còn nói qua vụ hepl làm chỉ
[01:43:01] là cái thằng này chứ Xuân Này bạn rất là
[01:43:04] nó sẽ inbox hộ mình cái À cái thư viện
[01:43:07] Xuân để mà lấy dữ liệu thì cái này gọi
[01:43:09] là hàm hết tơ tất cả hàm này hấp ơi tất
[01:43:13] cả trợ giúp mẹ nó sẽ dùng ở mọi chỗ và
[01:43:15] nó sẽ gọi hàng về ngay mà mình hoàn toàn
[01:43:17] thì phạm cái Hà Thế mà check admin Nội
[01:43:19] trước Super beam kiểu như thế mà mình sẽ
[01:43:22] gọi mọi chỗ tôi chỉ muốn gọi cảm nha
[01:43:24] Trách Superman
[01:43:26] ngay gọi đấy nha nó trả về chùa phone cả
[01:43:30] ngày càng lạ làm như thế nào Thì bây giờ
[01:43:32] mình phải tạo cái file hepl riêng mình
[01:43:34] đấy này mình sẽ cần cha crest Hair
[01:43:40] gel này nó gợi ý cách để mà tạo ra một
[01:43:45] cái file hepl gì đó Anh thường hả Mình
[01:43:49] đây
[01:43:50] tôi sẽ đặt tên file Happy is luôn như
[01:43:53] này được đấy à
[01:43:56] Anh
[01:43:58] thường là tôi sẽ vứt ở trong thư mục áp
[01:44:00] ở trong áp này luôn là nên có cốt của
[01:44:03] mình
[01:44:04] Cách tạo file hepl
[01:44:07] làm tt đó là trong này đứng ở trong này
[01:44:13] cốt và
[01:44:14] cho hỗn hợp pp rồi ông ạ
[01:44:17] ở đó tiếp theo là mình sẽ có khái niệm
[01:44:20] này Tại sao lại phải có cái hàng này tồn
[01:44:23] tại ở vì cái file này đôi khi nó sẽ được
[01:44:25] lót Nhiều lần em mình chỉ cầm kiểm tra
[01:44:27] là phương trình này tồn tại được lót cho
[01:44:29] hiểu mình không cần nói lại không khởi
[01:44:31] tạo lại file trên này nữa nói chuyện này
[01:44:34] như tôi vừa bảo nó sẽ ra trách Superman
[01:44:37] không ạ Chị sẽ là tên là Trạch
[01:44:39] amin này ngay
[01:44:43] ở đó
[01:44:46] anh xóa y chất là mình sẽ chỉ cần trả về
[01:44:49] chua phone là truyền vào nó là
[01:44:53] em kiểm tra xem hài
[01:44:55] anh có đúng hay sai ngay
[01:44:58] Xóa bớt đi này ở đây Rẽ trả về bulan mà
[01:45:02] đúng hay sai này đó nếu mà ông tạo như
[01:45:06] này xong rồi cũng chưa chạy đâu đấy Làm
[01:45:08] nào không phải có thêm cái file này vào
[01:45:12] trong cái autolock là cứ chạy cứ khi nào
[01:45:16] chạy cái chạy cốt thì nó sẽ loát thêm
[01:45:19] cái file ở đó ở Nếu mình chung không thì
[01:45:23] nó sẽ nằm trong cái không bao giờ này
[01:45:26] xe ô tô lát này truyền thêm em sẽ cho
[01:45:30] thêm một cái gần gọi thêm cái file này
[01:45:38] máy này của mình là
[01:45:41] Thế
[01:45:42] objective ở nhà à
[01:45:47] xe tải ta phải chạy băng băng tôi lót
[01:45:52] Tức là sao nghĩa là bởi vì nó từng nát
[01:45:56] hết tất cả đúng ai rồi mà nó không trả
[01:45:57] lại cái ô tô bác này đâu thì ông sẽ phải
[01:46:00] trả lại cái này đó
[01:46:02] ở nhà tắm
[01:46:04] dễ ngã Cốc Cốc Cốc à
[01:46:09] vì cuộc sống mà đi Cốc Cốc
[01:46:11] hình
[01:46:13] ảnh xóa hết cái cái rất là tiện ở điểm
[01:46:16] là thằng nào đôi khi nó lưu lại cách lưu
[01:46:19] lại tất cả cách video mời ông bản chất
[01:46:22] là cái thằng Blade này Blade này nó Nó
[01:46:26] là một cái kiểu để nó hỗ trợ để mà để mà
[01:46:30] ông cốt cho pp nhàn hơn đúng không Rồi
[01:46:32] nó sẽ
[01:46:33] A journalist và trật tự sinh ra Coast P
[01:46:37] và nói lưu cách lại cái đoạn nó đã xử lý
[01:46:41] nằm trong toilet này làm trong Facebook
[01:46:44] cách này
[01:46:47] Nghe nhạc Đây đây đây không phải rất
[01:46:50] nhiều pha ngay
[01:46:52] nó sẽ kiểu ví dụ là bạn của ông nó sẽ
[01:46:56] biến anh kiểu ngay cả nạn đó nó tạo rất
[01:46:58] nhiều cái file kiểu ngay nên là có những
[01:47:01] lúc mà mấy ông sửa có có trường hợp là
[01:47:04] mấy ông sửa sửa cốt rồi tự nhiên không
[01:47:08] phải lại xa không được Bởi vì nó đang
[01:47:09] lưu cách thì mày ông có thể là tại sao
[01:47:12] Google hôi Ly Cách view lao chẳng hạn
[01:47:16] đấy nó sẽ kí hộ cho
[01:47:19] em trả lại nhé
[01:47:21] có ai trả lại vẫn thế rồi Mình đã dùng
[01:47:24] hàn kia không tôi sẽ đổi cái chỗ những
[01:47:27] cái chỗ dùng hàn để nha thay vì dài dòng
[01:47:30] ngay đúng không mà về sau quan trọng vì
[01:47:32] sao mà sửa nhỡ đâu không phải là vòng 1
[01:47:34] lên 2 R3 thì mình chỉ ảnh hưởng của chỗ
[01:47:36] thôi
[01:47:43] ở Đông thấy nó không báo lỗi nữa gửi nó
[01:47:46] đã chạy được qua cái hàm răng trên này
[01:47:48] rồi
[01:47:49] Thông Minh Trị
[01:47:52] kết quả nhiều lúc cốc hơi chạy được
[01:47:55] ở
[01:47:57] đó không phải bấm lạ nhanh hay lại kiểm
[01:48:02] tra ngon tại sao không thấy thức ăn nó
[01:48:05] vẫn thế vẫn thế nhưng mà về sau ông sẽ
[01:48:08] xử ông phải tạo rất nhiều file An rất
[01:48:11] nhiều hàm Happy Birthday thì ông gọi mọi
[01:48:13] chỗ có thể ra diện
[01:48:15] hai đội hôm nay ga Tôi vừa rồi nói qua
[01:48:18] thêm cả mục hepl Bạn hãy tìm thấy kim
[01:48:21] thoảng tôi sẽ nói thêm một vài cái nữa
[01:48:22] sức khỏe Chị Mỗi cái trong tiêu đề không
[01:48:25] ạ
[01:48:26] Ừ
[01:48:27] nếu còn thắc mắc gì mà nãy giờ nói có bị
[01:48:30] bé quá khó hiểu thì gì đó em
[01:48:34] I Delete hay update fast khác gì nhau
[01:48:37] không à
[01:48:39] Ừ đúng rồi Cái phốt với ghét nó là chị
[01:48:44] ra chị Mỗi thế hôm qua nó phân biệt cái
[01:48:46] delete và
[01:48:48] pass kia để mà chuyện hơn một cái mới
[01:48:51] hết nữa để cho nó gọi là bảo không hạt
[01:48:54] bảo mật mà nói chung một cái rạch ròi
[01:48:56] hơn thôi
[01:48:57] từ
[01:49:04] không có bấm được
[01:49:06] cái này cũng làm nhiều rồi
[01:49:09] đi
[01:49:16] tôi có dậy mày không log log tao thì đơn
[01:49:18] giản thôi à
[01:49:21] em cứ nói qua bột lắc tao đi
[01:49:24] I not out gì à Một là ông thể đẩy nó
[01:49:29] ngay ở trong cái Mỹ được quen này hay
[01:49:31] ông Tống ra ngoài được không trọng tôi
[01:49:34] cứ để nó bên trong nhá mình sẽ có rorwa
[01:49:37] đây này
[01:49:38] ở nhà tại mày phải đăng nhập rồi tao mày
[01:49:41] cho mày đóng rất đúng không gì hết
[01:49:44] mình sẽ sửa lại cái đường link bấm vào
[01:49:48] knockout ở bên Là Sợi Tơ
[01:49:51] a nhớ rồi đấy có cái nút bấm la tao thì
[01:49:55] ra là không bấm được đâu Mai con tinh
[01:49:58] này sport này thì bode
[01:50:01] a
[01:50:02] doctrine study này là log out không thấy
[01:50:05] nó lên thẻ trong ngày đi đâu trong bấm
[01:50:08] được
[01:50:09] bởi mức đâu em mình sửa lại của bạn này
[01:50:13] chính sẽ nhảy đến cá rô tơ
[01:50:16] là lockout không ạ
[01:50:19] ở đó
[01:50:20] Ô chết rồi mình bấm vào đây để Lotte
[01:50:24] cho mình sẽ
[01:50:27] anh
[01:50:33] Vi
[01:50:34] phạm văn sinh là log out
[01:50:37] em
[01:50:38] cứ Ca là cái đoạn này chuyến giả là mình
[01:50:42] anh ở đây là ra bởi vì mình không Không
[01:50:46] làm thì nhiều thì mình có thể là Plus
[01:50:50] Xóa hết toàn bộ đi cũng được nhưng không
[01:50:53] lưu lại trong sân kiểu những cái gì ở
[01:50:54] phức tạp theo kiểu là cũng trước và làm
[01:50:56] rõ hàng nó cứ
[01:50:58] Ừ ừ thì nó hỗ trợ hết rồi mình chẳng cần
[01:51:02] phải làm gì cả anh còn nhớ gì đấy
[01:51:04] ở nhà anh chưa dùng bao rồi không biết à
[01:51:07] Ở công ty dùng sẵn rồi anh anh tự động
[01:51:11] vào anh không biết
[01:51:12] em à Cái này phải điều hướng quay trở
[01:51:15] lại nó tôi nói xong ghét nhắn hay lòng
[01:51:19] đăng nhập đăng xuất rồi các bạn luôn
[01:51:22] Nhắn cái xong rồi ạ mình và lại không
[01:51:26] được này cái gì chưa
[01:51:29] ở
[01:51:41] Em cứ thử em nhớ thế nhưng mà đúng dùng
[01:51:44] cho Ken không ạ
[01:51:58] còn hôm nay vừa làm được đăng nhập đăng
[01:52:02] xuất cho người biết được thêm một tí về
[01:52:05] Ừ cái việc là khi truyền dữ liệu vào như
[01:52:08] thế này thì mấy ông nha có thể bỏ cái
[01:52:11] thăm Sandy có thứ đúng không Không phải
[01:52:14] bạn nào cũng có hai cột đấy Ở làm gì đó
[01:52:18] Anh
[01:52:20] hợp âm
[01:52:22] Ừ
[01:52:23] nó còn muốn ngồi gần hai tiếng rồi tra
[01:52:26] Bộ hôm nay kết thúc đấy nhá mày Ông còn
[01:52:29] thi thắc mắc à tôi giờ ra tôi chưa xem
[01:52:31] video bụng trước nhớ ghi đâu bữa hôm
[01:52:34] trước mày không có vài ông đặt câu hỏi
[01:52:35] nữa Nhưng tôi chưa kịp trả lời tôi tổng
[01:52:38] hợp về bữa sau trả lời luôn một thể nhé
[01:52:40] à
[01:52:42] The
[01:52:43] One Piece
[01:52:45] a passport giờ tôi cũng đang định dùng
[01:52:48] cái con nít đấy ra tôi chưa Dùng cái đấy
[01:52:51] cũng chưa trả lời ông được gửi sau nhé
[01:52:54] Tôi sẽ nghiên cứu các thứ thứ rồi bởi vì
[01:52:57] nghiên cứu để dùng nó khác nghiên cứu
[01:52:59] phải dậy nè chắc cả tôi phải nghiên cứu
[01:53:01] kỹ đã Không mấy ông hỏi câu gì thì tôi
[01:53:03] không chơi được thì nó vẫn cười anh chào
[01:53:07] các bạn nhé
[01:53:09] Kết thúc sớm hai tiếng thôi nhé
