# Lập trình Web cơ bản - Buổi 17 - PHP - CRUD & Pagination & Searching & Hacking

- Video ID: `xXmCzhU0BNY`
- URL: https://www.youtube.com/watch?v=xXmCzhU0BNY
- Published: 2021-12-03
- Duration: 1h 41m 46s (6106s)
- Language: vi
- Subtitle source: auto
- Kind: live

## Transcript

[00:00:16] anh Alo ạ
[00:00:19] à à
[00:00:23] ơi các bạn hãy tiêu đề hôm này rất là
[00:00:26] dài không ạ hi vọng hôm nay à
[00:00:29] thì các bạn sẽ theo được Chắc là nhiều
[00:00:32] không thấy hào hứng cái chuyên mục cuối
[00:00:34] hơn sao mày Ông đợi đến cuối buổi mày
[00:00:51] ừ ừ
[00:00:54] ý thức ăn là mình không định nhắc đến vụ
[00:00:57] hacking sớm Yên Thế nhưng mà
[00:01:00] bây giờ thì mình nghĩ là
[00:01:04] nó đang hơi bị nhận cả một tí anh Bởi vì
[00:01:08] à các bạn đang chia sẻ Các đường link
[00:01:11] hosting các thứ thứ ở trên cái trả lời
[00:01:14] cái Trang Cái bồ của mình các bạn đương
[00:01:17] nhiên là với mục đích là kiểu chia sẻ
[00:01:21] chia sẻ về mà kiểu chữa bài rồi chia sẻ
[00:01:23] để mà các bạn khác xem vào xem nó tiện
[00:01:25] đấy Vân Vân Vân rất tốt không sao cả
[00:01:28] Nhưng cái quan trọng thì nó cũng chính
[00:01:32] là có chứa trả lời bạn này đợi tí đi cho
[00:01:35] đến lúc tôi thấy gà cũng vừa mới vừa mới
[00:01:38] vào trả lời là hai người trả lời rồi nó
[00:01:42] bị Loan đấy anh thì mấy mấy cái
[00:01:44] miếng to hơn à
[00:01:47] anh không Chắc là do tôi khỏi ốm rồi nên
[00:01:51] đỡ hơn đấy thì thì mấy cái này mày mấy
[00:01:53] ông chia sẻ như thế này và đặc biệt chia
[00:01:56] sẻ cả vụ là là người khác đăng ký Sau đó
[00:01:58] thì hiển thị lại thông tin về đây đã
[00:02:01] đăng ký nữa thì hoàn toàn là có thể là
[00:02:04] các bạn có thể hack được lẫn nhau nên
[00:02:06] cũng như là việc là có ông nào nó đang
[00:02:08] xử với trang web hack đây lại thì ra là
[00:02:10] mấy cái lung linh là khá nguy hiểm phải
[00:02:13] do mình mình đang hưởng đến các bạn vẫn
[00:02:16] chỉ đăng ký hát thôi đường link demo
[00:02:19] được ra mình đang cân nhắc mình mình tra
[00:02:21] hôm sau mình Sao lại không khéo mình
[00:02:23] cũng phải mở Ờ sang bóp lên để mà chạy
[00:02:26] mới lung linh các bạn mất
[00:02:28] ừ ừ
[00:02:31] ở đây Thế nên là hôm nay mình sẽ dạy các
[00:02:33] bạn qua về việc à Có thể dễ dàng hack
[00:02:37] được như thế nào để mà các bạn à kỷ niệm
[00:02:39] mà không không theo kiểu như thế nữa
[00:02:50] Ừ
[00:02:53] thế nào bây giờ chắc là trước khi vào
[00:02:55] buổi học về mình xin phép trả lời
[00:03:00] Ở đây có tâm sự có tâm sự về
[00:03:02] ẩm thực ra hôm nay tôi đang định là tôi
[00:03:04] sẽ ngồi à
[00:03:06] sẽ trả lời hết tất cả đống này trước sau
[00:03:10] đó thì bảo đến Học thì học mà thôi tâm
[00:03:13] sự đã không để để
[00:03:17] 8 giờ 8 giờ mình Bác Hồ trả lời câu hỏi
[00:03:20] rồi học nên bỏ hôm nay cũng sẽ lại dài
[00:03:23] thôi có thể dài nha màu một hôm trước
[00:03:25] hiện chỉ hơn hôm nay chưa chắc là có
[00:03:28] thời gian để mua Chữa bài tập equal nữa
[00:03:31] cả đời thứ bảy vậy mấy ông mẹ lùi lại
[00:03:34] tôi lịch nhá đó thứ Bảy tra chữa bài của
[00:03:42] ở đầu tiên thì hôm trước mà mình có mình
[00:03:44] ở thời gian mình đã từng nói mình con
[00:03:47] người mà kéo hơi bị trẻ trâu và hơi bị
[00:03:51] gặp tao kiểu hay đi cãi nhau với những
[00:03:55] mọi đối tượng những kiểu à
[00:03:59] cho mọi đối tượng kiểu dạng là họ không
[00:04:01] vì họ không có cùng suy nghĩ với mình
[00:04:04] cho thế không ngồi nói họ ngu dốt gì cả
[00:04:07] Ở trong đầu tôi có nhiều lúc nghĩ thì
[00:04:09] hết kẹo không hiểu nói cái gì mà phát
[00:04:12] ngôn những câu đấy nhưng mà Thôi coi như
[00:04:13] ở họ không Cùng chung suy nghĩ Không
[00:04:16] Cùng Quan Điểm với mình không ạ thì à
[00:04:19] khi mà Mấy ông tranh luận như thế thì nó
[00:04:22] sẽ có khái niệm mà kiểu chửi nhau cãi
[00:04:24] nhau và phản biện
[00:04:28] ý thì cái việc à Tại tại sao phải
[00:04:31] mà tại sao lại phải dùng từ phản biện nó
[00:04:34] khác với cãi nhau và cãi nhau tất cả ám
[00:04:37] chỉ ông chàng có đôi khi chẳng có tí
[00:04:40] lôgic thì ở cơ đôi khi ông sẽ có cái
[00:04:42] chửi nhau trong đấy có phản biện thì sẽ
[00:04:45] nói lôgic sẽ Google lôgic nó là gì Và
[00:04:48] quan trọng là những cái lỗi mà các bạn
[00:04:52] khi mà phản biện nhau đó là gì có bạn sẽ
[00:04:54] phải trả những cái điều đấy bởi vì mình
[00:04:58] đang thấy rất nhiều kể cả cổ điển hình
[00:05:00] Kể cả việc vậy mấy ông đi thi Đường Lên
[00:05:04] Đỉnh Olympia vân vân nữa tôi không Tôi
[00:05:06] không biết thế nào tôi thì à
[00:05:09] à À đấy tôi có không tôi Còn tôi thì
[00:05:12] công nhận nó cũng
[00:05:14] em không có mạng nên những kẻ người giỏi
[00:05:17] Tôi đã từng nói đó là ờ
[00:05:20] Ừ Tôi chỉ coi trọng những cái người mà
[00:05:22] người ta
[00:05:25] ở tại Đức Mạnh Toàn thôi chứ tôi không
[00:05:27] hạn ở nề những người giỏi hơn mình nhưng
[00:05:29] mà người ta chẳng có đức hai người ta
[00:05:33] kiểu gì đấy thế nên là tôi không hẳn là
[00:05:35] đánh giá cao mới ông đi đường lên đỉnh
[00:05:37] Olympia Thôi cậu ông cứ vô địch Đường
[00:05:40] Lên Đỉnh Olympia gặp nói cái gì cũng
[00:05:43] được không Tôi không ngờ tôi không kiểu
[00:05:47] dạng là thần tượng một ai đó nhưng thế
[00:05:50] và như tôi đã nói thì những cái ông ấy
[00:05:51] được là cũng mắc đầy những cái lỗi phản
[00:05:56] biện kể cả khi mới chửi nhau trên mạng
[00:05:59] Ừ thì những cái lỗi phản biện mà tối đa
[00:06:02] định nói đó là gì đó là cấp mấy ông
[00:06:04] thường ra hồi trước tôi có cha được cái
[00:06:08] đấy lại từ trên nhóm ở trên Facebook thì
[00:06:10] ra tôi thoát nhau mấy rồi vì về cơ bản
[00:06:13] Đấy là khi nhóm này cũng mắc rất nhiều
[00:06:15] lỗi vậy nghĩa lắm chị nhóm đấy thì ah
[00:06:18] admin những người người amin thì là
[00:06:21] người ra bằng rất nhiều bài hay về cái
[00:06:24] tư duy các phản biện các thứ thứ cách
[00:06:26] nói chuyện để mà kiểu khi mở ông tranh
[00:06:29] luận vấn đề gì đó thì nó sẽ hiểu
[00:06:32] sẽ nói cho nó sẽ giải quyết được cái gì
[00:06:34] đó thay vì kiểu cãi nhau chửi nhau cho
[00:06:37] vui đấy như thế nhưng mà thành viên
[00:06:39] trong đấy thì không như thế Bây giờ ở cả
[00:06:41] thành viên ông đấy nó cứ bị rát rát nên
[00:06:46] là tôi cũng thoát đấy lỗi phản biện về
[00:06:49] trước thì nó có lưu vụ này
[00:06:53] U20 lỗi phản biện Hình như cái này
[00:06:57] Ê mấy ông thử nghe qua cái này xong rồi
[00:07:01] béo thử tự xem là mình à Hay mắc lỗi gì
[00:07:07] nhé cái đầu tiên rất nhiều ông hay mắc
[00:07:14] Ồ không Tôi vừa nói rồi đấy Hôm nay
[00:07:16] không có đủ thời gian để ngồi Chữa bài
[00:07:19] tập este đâu Cứ thử chuyển qua thứ bảy
[00:07:21] ông ạ Cái ông Tạm nội tôi lịch cho thứ 7
[00:07:22] nhé
[00:07:26] ở đó là thay vì ông bà lợn là chủ đề thì
[00:07:30] lại sỉ nhục hạ bể công kích cá người kia
[00:07:36] đó để làm giảm câu cầu cài uy tín cái
[00:07:38] con lời nói của họ giống như kiểu mày
[00:07:41] làm được chưa hay là cái gì đó giống như
[00:07:43] vừa rồi Bảo Đường Lên Đỉnh Olympia có
[00:07:46] thứ tư đấy Cái được mày người ta không
[00:07:49] các thứ đấy mà trong khi đó nó không bàn
[00:07:52] chính xác về cái chủ đề đang nói là sử
[00:07:54] là cặp đang bàn được món ăn đấy ngon Bây
[00:07:57] giờ thì tự nhiên lại kiểu khoai là mày
[00:08:00] Con nấu được như thế không đấy các thứ
[00:08:04] anh không nói thế thì không ai có thể nó
[00:08:07] lại được bởi vì ở gạo giả sử giống như
[00:08:09] ông từng vô địch
[00:08:12] mà xơ chết một lần nữa lại không ai được
[00:08:17] phép cụ thể chế đồ ăn của ông bởi vì Ok
[00:08:20] thì mấy người kia là vô địch đầu đủ ạ
[00:08:23] Đấy thấy ra là người đó ông sẽ luôn đúng
[00:08:25] không cái cái phần điện như thế không
[00:08:27] thì tốt và
[00:08:30] đấy rất nhiều người bây giờ làm kiểu thế
[00:08:31] và nhiều người đặc biệt bây giờ làm việc
[00:08:33] Giờ trẻ rồi còn thích grab dụng con thứ
[00:08:36] nữa rồi nghĩ rằng grab
[00:08:39] grab chửi nhau với ông biết rồi Thôi ra
[00:08:42] Petr Kiểu cái gì thừa thãi kiểu sinh dục
[00:08:45] cá nhân sau đó chị nghĩ đấy là màu chung
[00:08:48] mà không nó sai lỗi phản biện cái đầu
[00:08:50] tiên là luôn đúng không ạ thì ông sẽ
[00:08:52] thấy đấy à những thành nhưng người kiểu
[00:08:55] hả bị người khác xuống để để họ không
[00:08:58] nói được nữa không phải là mấy hình thức
[00:09:00] đó ông đã thắng về ra đây cái lôgic Ừ
[00:09:04] ông chỉ hướng già là ông thiếu lôgic nên
[00:09:06] ông đành phải chơi cho cảm lãng mạn
[00:09:09] vì thế không thể tốt được mạnh
[00:09:11] tiếp theo
[00:09:14] hai tay cũng tương tự là nói điều không
[00:09:15] tốt về người đang tranh luận đến Minh
[00:09:19] Vân Vân nó cũng sẽ là lỗi lỗi ngụy biện
[00:09:22] thật công ở nhân này đấy
[00:09:27] anh nói ví dụ này đừng nhờ a phụ mày mở
[00:09:30] tiệc vui chọn nhạc của nó tệ lắm đúng
[00:09:32] không nhé Cứ bôi sống đưa ra một thông
[00:09:34] tin tiêu cực
[00:09:42] ở Ngụy Biện bạo lực Đó là thay vì dùng
[00:09:43] lý lẽ hành động
[00:09:48] nghỉ lễ lôgic thì thì sẽ kiểu đang dọa
[00:09:55] anh đào là kiểu thư xếp Tại sao phải làm
[00:09:57] thêm giờ mà không thêm phụ cấp hoặc cánh
[00:09:59] chấp nhận làm hay là anh nghỉ việc thì
[00:10:03] thôi đấy nghĩa âm chị sẽ dùng cái quyền
[00:10:07] cái quyền hạn của mình cấp cái kiểu
[00:10:10] nói chung là để mạ áp bạc người khác hay
[00:10:13] là cậu đấy dọa người khác tâm trạng
[00:10:18] à mà không hề mà không hề nói về cái vấn
[00:10:21] đề hiểu về vấn đề là làm thêm giờ hay là
[00:10:24] phụ cấp gì cả đúng không ạ ạ
[00:10:27] cho trẻ 5 triệu mình đè ra xuống nó làm
[00:10:30] tương tự trong cái tấn công kia mời hình
[00:10:32] thức kiểu dạng là kiểu làm người ta như
[00:10:34] chí người ta sẽ không tranh luận gì nữa
[00:10:38] người ta sẽ phải tạm tuân theo bạn theo
[00:10:40] rõ ràng và người ta có thể không phục
[00:10:43] trong lòng không ạ
[00:10:46] ở Ngụy Biện Bạn cũng vậy
[00:10:48] anh cứ bị điện này anh ở đây gian lận
[00:10:50] như ông là sai lầm như ông chưa từng
[00:10:53] gian lận bao giờ ấy hồi đi học ông cũng
[00:10:55] copy và suốt cái Nghĩa ăn chỉ làm được
[00:10:59] ông ông sẽ kiểu dạng là ông sẽ không
[00:11:02] được phán xét người khác khi mà ông đã
[00:11:07] từng làm cái điều đấy thì cái cái phần
[00:11:08] biện này thường ra là cũng rất nhiều mới
[00:11:14] đương nhiên là chúng ta cũng nên luôn có
[00:11:18] một sự đồng cảm với cái phải với Đây á
[00:11:21] hung thủ không phải dùng tới hung thủ
[00:11:22] nhưng mà nói chung
[00:11:25] đồng cảm thấy cái người mà cay gây ra
[00:11:27] một cái hậu quả gì đó mình vẫn phải có
[00:11:30] sự Đông ca nhưng mà không có nghĩa là
[00:11:36] 10 nghĩa đây là đúng khi mà kiểu người
[00:11:39] ta làm một cái gì đó sai nhiều người
[00:11:41] cùng mắc thấy xa đấy không có nghĩa là
[00:11:49] thơ Nguyễn điện trượt dốc và ngụy biện
[00:11:50] suy diễn
[00:11:54] suy diễn này thì rất nhiều oxy lịch sử
[00:11:56] tra là bạn nữ các bạn nữ hay suy diễn
[00:11:59] giỏi hơn giống như kéo dạng là mình thấy
[00:12:01] xem Tik Tok gần đây nó cũng có kiểu dạng
[00:12:02] hả gặp
[00:12:05] anh ơi mua cho em cái điện thoại nếu mà
[00:12:08] không mua thì anh hết yêu em rồi Cái thứ
[00:12:12] cái thứ kiểu nó sẽ suy diễn ra một loạt
[00:12:13] các hướng
[00:12:16] khi đôi khi ở đó sẽ còn Thậm chí còn
[00:12:19] những vấn đề nghị lực lòng bé hiểu Anh
[00:12:21] nghĩ trường hợp Hồi trước có chuyện cười
[00:12:24] nó kiểu lạ kia ông chồng chỉ cần nói một
[00:12:28] câu là anh nghĩ vấn đề này em giải quyết
[00:12:31] không đúng lắm rồi xong rồi Bạn lấy Sẽ
[00:12:32] suy diễn một loạt các kiểu
[00:12:34] ý em nói
[00:12:37] Ý anh nói em không nói đúng Tất cả em à
[00:12:39] dối mà em nói dối tất cả
[00:12:43] em con người Vân Vân Vân sau đó suy ra
[00:12:45] kiểu anh chửi tôi là con chó Đúng không
[00:12:51] các thứ nó bị biện kiểu suy diễn đấy
[00:12:54] Nhìn đấy đấy cũng cậu làm cho người khác
[00:12:56] cũng như trí người ta nói đây là cái gì
[00:12:59] cả Cho con thêm những cái nữa giống bị
[00:13:01] biện trắng đen này mình thấy ngoài đời
[00:13:03] cũng gặp nhiều này
[00:13:07] nghĩa là ờ
[00:13:15] Ừ nó là cậu không Cái này thì bắt buộc
[00:13:17] phải là cái kia ấy nghĩa là chị có hai
[00:13:21] lựa chọn không có mua trộn một thì thì
[00:13:23] bắt buộc phải là hay rồi thế sống như
[00:13:26] kiểu bạn là
[00:13:29] các bạn thích mình không là sự không thì
[00:13:33] xe Bạn ghét mình rồi vân vân ý thế Đấy
[00:13:36] xong rồi từ đó sẽ kiểu sẽ bị cạn lời
[00:13:39] Không biết nói cái gì đã là một cái kiểu
[00:13:48] à mà có nghĩa vụ có nghịch điện là nghĩa
[00:13:50] vụ chứng minh này nữa và cho mình thấy
[00:13:53] được ra là mình đang chỉ nó qua các bạn
[00:13:56] thôi các bạn thể đọc qua ở đây khá nhiều
[00:14:07] có bằng chứng vụn vặt này giống như kiểu
[00:14:09] hút thuốc cũng rất có hại sức khỏe ông
[00:14:12] nội mình hút nhưng vẫn khỏe mạnh có bệnh
[00:14:15] tật gì đâu Anh ấy ăn chị ạ Dùng một cái
[00:14:18] một cái bằng chứng rất bé thì mà đánh
[00:14:19] giá
[00:14:26] ở ở dưới này Nói chung là đến tận 20 cái
[00:14:29] biện và lúc còn mấy ông đọc xong ấy thì
[00:14:31] mấy ông Trần nhận ra từ trước này mấy
[00:14:33] ông có dính một vài cái lỗi biện này khi
[00:14:36] cãi nhau khi tranh luận mỗi gì đó khi
[00:14:39] nói chuyện một cái gì đó thực ra là thức
[00:14:40] tin được mấy bộ không nhớ hết được giống
[00:14:41] như tôi thôi Tôi thích xem hết đều ngoài
[00:14:44] tôi không nhớ hết cho tôi sẽ tôi sẽ rất
[00:14:47] hạn chế việc công quốc cá nhân nữa thôi
[00:14:48] gần như bây giờ tôi không vừa cậu lên
[00:14:50] công kích cá nhân không giống như được
[00:14:54] kéo ra sự có có vài ông chửi tôi trên
[00:14:56] trang cá nhân của tôi chẳng hạn Tôi
[00:14:58] không phải trang cá nhân của họ để mà
[00:15:01] gặp soi mói xe mà Họ sống ở đâu Họ đã
[00:15:04] từng học gì họ từng đăng cái gì Rõ rồi
[00:15:06] phán xét tao tưởng mày chỉ là một thằng
[00:15:09] cậu abcs học ở trường gì gì đó khác để
[00:15:11] công kích cá nhân
[00:15:15] khi họ nói giúp họ nói tôi là kiểu tôi
[00:15:17] dậy Cái gì sai thì tôi sẽ chị chú trọng
[00:15:20] ngoài việc là cậu à
[00:15:23] Ừ cái câu nói của họ là kiểu Họ nói tôi
[00:15:25] sai ở chỗ nào để phân tích nó ra thôi
[00:15:29] đấy à
[00:15:31] khi công kích tập thể với công ty cá
[00:15:32] nhân
[00:15:36] em có cái cung kích cơ có cái lợi dụng
[00:15:38] đám đông lên này Đây này
[00:15:42] ý nghĩa là giả sử là tất cả cùng có khá
[00:15:45] nhiều người khá nhiều người cậu ném đá
[00:15:49] một bạn thì cũng cho rằng cả đám đông ấy
[00:15:52] đúng và bạn kia sai cái kiểu như thế đó
[00:16:01] anh nói chung ở cái cái này thì mấy ông
[00:16:04] trận thấy là ngoài đời được đậu mình cái
[00:16:08] à à
[00:16:16] các tiêu chuẩn khác thì thực ra nhiều
[00:16:18] nhiều bạn còn không biết rằng những tiêu
[00:16:20] chuẩn kép này là gì chứ nhờ cái này đại
[00:16:23] khá rồi cậu Tôi nói bạn được nhưng mà
[00:16:36] thế thôi có vào cái nhóm
[00:16:38] baby
[00:16:42] you missed speaking neutraface Nói chung
[00:16:43] là à
[00:16:47] Ai có bài đăng về con mèo các bạn Nếu
[00:16:50] các bạn không biết có cái con mèo nằm im
[00:16:56] mà máy Ly nó bị mất kê thì nhiều người
[00:16:57] cậu thấy cậu
[00:17:01] anh buồn bã vì nó ấn Vân tôi thì tôi
[00:17:03] không quan tâm đến vấn đề đấy mấy người
[00:17:06] đấy có vẻ thừa nước mắt nữa là thừa
[00:17:11] thừa gì đó mình là tôi không có tâm em
[00:17:14] khi họ buồn thì mình cũng đâu có quyền
[00:17:17] phán xét họ buồn đó đúng ạ
[00:17:20] sau đó thì có một ông và bình luận ông
[00:17:24] này được keo trọc Ổ Kiến Lửa cái cháu
[00:17:26] với đúng rồi cũng chết Lượn rồi ông ấy
[00:17:27] vào bình luận
[00:17:31] em chỉ làm con mèo thôi mà buồn bao
[00:17:33] nhiêu hôm vào chửi tao à không phải nói
[00:17:35] như ông bao nhiêu
[00:17:39] có đủ thể loại phải trộn mẹ cả thế
[00:17:43] Khi dòng họ Người ta nói kiểu bọn mày à
[00:17:46] Mày làm sao nổi tiếng nó mày lên tất cả
[00:17:49] và đúng kiểu công kích cá nhân giống như
[00:17:52] tôi phải nói để Kiều có thứ
[00:17:56] xôi kiều tự như tôi vẫn vào đỡ hộ cho mà
[00:17:58] em một tí đó là cả đương nhiên ông này
[00:18:00] vào
[00:18:03] Ừ ông ấy vào nó cái câu tất cả là không
[00:18:07] hẳn là hay lắm ở trong một cái kẹo bài
[00:18:10] mà đáng lẽ phải buồn với nhiều người
[00:18:13] thiếu người nói câu đấy Ở ra nó hơi cậu
[00:18:16] hơi có thể gây chập Giận mấy bọn đấy
[00:18:19] những về các bạn thì à
[00:18:22] ở với người mà kiểu yêu chó mày bình
[00:18:24] thường bình thường đi không nói cuồng
[00:18:26] Nhưng mấy bạn kia nó không biết cuồng
[00:18:27] thật hay không nhưng mà tôi khẳng định
[00:18:30] được cả 90 phần trăm nữa chỉ là hơn con
[00:18:32] số đấy mấy ông ấy không hề biết con mèo
[00:18:35] đấy tên là gì cho đến khi có cái bài
[00:18:36] năng đây
[00:18:39] ý nghĩa làm chỉ ở mấy ông cầu thương hại
[00:18:40] cho một cái con mà mình còn chưa từng
[00:18:44] biết rõ vì nó lấy kiểu thế thì vẫn
[00:18:47] thương ok vẫn thương rồi thường thì
[00:18:49] thường sau đó thì kiểu bà chửi dòng họ
[00:18:54] của thằng thằng kia lên cười ấy kêu Nếu
[00:18:56] mà mấy ông kia nhìn một cái tổng quát
[00:18:59] hơn thì rõ ràng mà Mấy ông nói chửi nhau
[00:19:03] với con mèo à Mấy ông sẵn sàng chửi một
[00:19:05] cái người mình không hề biết chỉ có dòng
[00:19:08] họ người ta không lấy biết chỉ vì một
[00:19:11] cái con mèo mà mình mới biết quá mạnh
[00:19:14] Đấy đấy Cái thứ tư kĩ hơn mấy ông cũng
[00:19:17] công nhận cũng rảnh hết
[00:19:21] Ừ đấy thì à Nói chung là đấy 1 sự tiêu
[00:19:22] chuẩn kép theo kiểu là mấy ông ấy bảo là
[00:19:26] ạ Bạn này không được phép kiểu vào bình
[00:19:28] luận kiểu như thế
[00:19:31] soi kèo và tôi được phép chửi họ chửi
[00:19:33] bạn đấy chứ Bạn không có khách chưa để
[00:19:36] tôi vì tôi đúng tôi là tôi tập thể tôi
[00:19:44] em không ở Bảo bạn đấy là vô duyên khi
[00:19:45] mà bình luận như thế
[00:19:47] nhưng mà Mấy ông lại vào chửi ta thì mới
[00:19:49] ông cũng không duyên không kém đúng
[00:19:50] không ạ
[00:19:52] anh nói chung là tiêu chuẩn kép Nó là
[00:19:55] kiểu ở mình là người khác thì được người
[00:19:57] khác làm lại mình không được thế là quá
[00:20:10] 10 thực là tôi Đôi khi tôi tôi biết được
[00:20:13] cả chúng ta có thể lướt qua có những thứ
[00:20:16] như là đôi khi tôi vẫn muốn nói vì thôi
[00:20:19] vẫn có quan điểm đó là xã hội sẽ tốt đẹp
[00:20:23] lợi hơn khi mà người tốt lên Điếng người
[00:20:28] tốt đừng ra để mà đấu tranh cho cái đúng
[00:20:30] ung thư
[00:20:33] Ừ chứ thực ra là số lượng người tốt Tôi
[00:20:34] không biết là số lượng người tốt hay
[00:20:36] người xấu lớn hơn bây giờ nhưng mà chất
[00:20:39] thả ra nếu chúng ta không lên tiếng thì
[00:20:42] kiểu dạng khi cái xấu nó vẫn sẽ luôn còn
[00:20:45] đói đấy Cái hình thức châm biến mấy cái
[00:20:48] đầu một vì hồi Bé Đón xem nhiều Gặp Nhau
[00:20:50] Cuối Tuần nữa Cái kiểu châm biếm đã từng
[00:20:52] có thử nó là như thế
[00:20:54] à Mà ông biết hài hài miền Bắc thường ai
[00:20:57] châm biếm ở Hải pháo kéo tôi sẽ đến lưu
[00:20:59] vào những thế thói hư tật xấu của xã hội
[00:21:04] để mà để mà kiểu người khác có thể thấy
[00:21:07] buồn cười như họ sẽ nhìn lại được đó là
[00:21:09] cuộc sống sẽ có những cái kiểu như kia
[00:21:12] một người ta sẽ tránh tránh mắc lại
[00:21:22] Ừ rồi nói nốt cái cuối một phút chính
[00:21:26] phủ nói đó về tiền bạc
[00:21:29] quan điểm của mình giống như là mình đã
[00:21:31] từng nói là mình làm cái cái ngày miễn
[00:21:33] phí và vì sao vẫn miễn phí sao mình cũng
[00:21:35] không định
[00:21:38] Ý mình là làm nhiều cái sợ miễn phí chia
[00:21:39] sẻ các thứ thứ
[00:21:45] được như là niềm mà đi làm Bây giờ mà là
[00:21:46] miễn phí nốt thì chắc à
[00:21:50] Không có gì bộ mồm Ăn được ạ Mình thức
[00:21:54] từng nghĩ khá nhiều về cái tiền bạc rồi
[00:21:56] anh ra tiền thì không thể bỏ đi giống
[00:21:58] như thời bao cấp và bỏ tiền đi rồi cùng
[00:22:00] thì chẳng ai chịu làm cái gì cả
[00:22:02] Ừ ai cũng như nhau thì chẳng ai làm gì
[00:22:05] cả đâu Nếu bắt buộc phải có thêm một cái
[00:22:08] gì đó yếu tố để các bạn phải có phải
[00:22:12] phải làm để mà có cái Man Ít nhất là như
[00:22:13] thế
[00:22:15] các bạn thử nên là không thể phủ nhận
[00:22:18] mà
[00:22:21] cho mình luôn cho cái đồng tiền nó luôn
[00:22:24] ở mức thuế cùng trong cái việc à mình
[00:22:26] quyết định một cái vấn đề gì đó Mai mà
[00:22:29] may mà đến giờ mình vẫn chưa nghèo đói
[00:22:32] Hay cậu thiếu thốn gì cả Bởi vì hồi mẹ
[00:22:33] từ bé
[00:22:36] đi tìm nhưng mà mình không phải trong
[00:22:37] con
[00:22:42] Con Nhà Giàu đi nhổ nhuộm bạn thôi rất
[00:22:44] nhiều ông bạn đừng chơi từng mới gặp tôi
[00:22:47] sẽ nghĩ tôi làm con kiểu công tử bột thì
[00:22:48] tôi được
[00:22:51] Ừ tôi da trắng rồi bảo chồng gây có nhôm
[00:22:53] chẳng làm mấy cái việc gì cả đường thế
[00:22:56] là nhìn thôi được Chắc hai công tử bột
[00:22:58] thứ
[00:23:02] Ừ nhưng mà không Nhà tôi thế là tôi là
[00:23:05] không có nhà Thế bây giờ không ở nhà thờ
[00:23:08] gia đình khá hoàn cảnh cả là
[00:23:12] bố mẹ thì cái này đang hơi Cá nhân tí
[00:23:14] nhưng mà bắt buộc phải có cá nhân Hôm
[00:23:16] nay thì mới nói được cái nguồn gốc của
[00:23:19] cái cái này cái tiền định nghĩa tiền ở
[00:23:23] trong quan điểm của tôi Đó là kiểu
[00:23:26] cho bố mẹ thì cả hai gia đình ruồng bỏ
[00:23:30] Ừ thế là kiểu ở gầm cầu kiểu nói chung
[00:23:31] là sóng
[00:23:35] ở đấy cũng vài tháng này vậy Bán hết mọi
[00:23:38] thứ quần áo để mà kiếm tiền ăn cá thứ
[00:23:41] sau đó mãi về sau thì mới được à
[00:23:46] Về ở ở nhà ngoại thì với điều kiện là
[00:23:49] phải chia tay Bố đã đấy đi Nói chung nhà
[00:23:51] sau đó thì kiểu
[00:23:56] em ở luôn với ông bà ngoại từ đó đến đến
[00:23:57] bây giờ
[00:24:04] Ừ thế là từ trước này không ở nhà sau đó
[00:24:07] thì mẹ tôi làm gì Mẹ có bán vào nước
[00:24:08] Thôi mẹ tao bán hàng nước rồi sống qua
[00:24:11] ngày bán nhà nước bù đêm thực đêm để bán
[00:24:14] hàng có thứ sẽ không hề có sự khá giả
[00:24:21] vợ chồng ở nhà mình ở phố cổ cái mác này
[00:24:24] vẫn có vẻ nhe Bây giờ ở ai nhưng mà đây
[00:24:26] cũng chẳng phải nhà của mình nói chúng
[00:24:28] mình ở là
[00:24:30] đó không phải nhà của mình thì ra là
[00:24:33] mình kiểu cổ Đấy mình chẳng có cái tiếng
[00:24:36] nói gì cả Mình gọi là sống nhờ mà nó
[00:24:40] không ạ Và cái nhà đấy thì ông bà con
[00:24:42] chia 7 người con nữa Có gì đấy là tội
[00:24:45] chẳng hi vọng và thở ra từ trước Mai à
[00:24:48] đấy nữa vì 7 người con nhưng mà các bác
[00:24:51] của tôi thì nó là một cái gì đó kêu rất
[00:24:54] là ờ
[00:24:56] à rất là tiền bạc
[00:24:59] thế cửa là
[00:25:02] vẫn còn tranh giành cái nhà đấy thư gửi
[00:25:04] các Bác đều có nhà riêng rồi đều dầu để
[00:25:06] có tận hai ba nhà biệt thự như vẫn trên
[00:25:10] này cả nhà của ông bà không đuổi mẹ con
[00:25:13] tôi ra ngoài cơ
[00:25:16] A và Nhưng mà thế mà vẫn không chịu nuôi
[00:25:19] ông bà vẫn để mẹ tôi nuôi ông bà cơ đấy
[00:25:21] 7 người ngon nhé
[00:25:26] em lấy lấy lấy nhà cũng vài trăm của ông
[00:25:29] bà cơ về các thứ vỡ không đưa ông bà con
[00:25:32] Thư nói chung là rất nhiều thứ liên quan
[00:25:34] đến tiền bạc
[00:25:37] May mà mẹ tôi vẫn đủ nuôi sống thôi
[00:25:40] Ừ để mà tôi vẫn nó học ăn học thì được
[00:25:46] như bây giờ thế là tôi rất kỹ việc
[00:25:48] Ừ nhất định danh bạ
[00:25:50] khi tôi cảm thấy tiền bạc nó làm ảnh
[00:25:52] hưởng cuộc sống của tôi nghe từ hộp bé
[00:25:56] nghe từ lúc trước khi chào đời cho đến
[00:26:00] kiểu đến khiến gia đình tôi khổ như thế
[00:26:05] các thứ Nên là tôi về sau sẽ không tự
[00:26:08] nhiên là mình sẽ phải cố gắng đủ giỏi để
[00:26:09] mà
[00:26:11] thì mình sẽ không bao giờ phải kiểu
[00:26:14] vướng nói chuyện này nữa
[00:26:17] Ừ nhưng mà à
[00:26:20] À mà đấy là tôi sẽ không Không làm gì đó
[00:26:23] thì tưởng quan tâm mình cái tìm bạn lắm
[00:26:26] ở trên mạng ai mà chơi với tôi quen tôi
[00:26:28] thì sẽ thấy tôi rất thoải mái trong việc
[00:26:31] về tiền bạc không được tính toán
[00:26:37] Đó là kiểu thử ta là tình bạc cũng nó sẽ
[00:26:39] làm ảnh hưởng tình cảm rất nhiều trong
[00:26:42] các mối quan hệ nó vốn luân chuyển một
[00:26:45] công cụ thôi nó không thể thiếu nhưng nó
[00:26:47] vẫn chỉ một công cụ thôi
[00:26:51] Ừ ok hơi bị tâm sự hơi bị ỉa chảy quá
[00:26:58] à
[00:27:01] Vì sao anh định nghỉ làm để làm bị lag
[00:27:04] full ham không à
[00:27:06] Anh không nghỉ làm thì cho hết cái màn
[00:27:09] rồi anh sẽ không đi làm được mà như tôi
[00:27:12] và nói về sau giả sử thuộc về họ trả Vì
[00:27:13] sao tôi cũng thấy con định làm vlog vài
[00:27:15] cái nữa nhưng mà chắc là không để kiếm
[00:27:16] tiền thì
[00:27:20] Ừ
[00:27:28] a tiếp theo
[00:27:31] cái hình như mình nhớ không làm được
[00:27:33] Hình như bạn lấy hỏi câu này liên quan
[00:27:35] đến cái lúc mà mình đang chia sẻ cái ứng
[00:27:37] dụng ích khí xe rác Cái hôm trước mình
[00:27:39] nó cái ứng dụng mà kẹo khi mà
[00:27:43] một cái gì đó chạy thì lập tức là cái
[00:27:45] sau sẽ được sẽ có một cái kích hoạt cái
[00:27:48] cơ đúng không ạ sẽ được kích hoạt bạn
[00:27:52] hiểu họa Instagram ứng dụng này các bạn
[00:27:55] Tải ứng dụng này trên có thể
[00:27:57] khi dùng trên này Nhưng mà thường là tôi
[00:28:00] thấy ngon hơn ở trên áo thì à
[00:28:02] Ê mày không tải ứng dụng máy về thôi mấy
[00:28:05] ông chén giả là vào kết nối đến các bạn
[00:28:08] các tài khoản mạng xã hội của mình sau
[00:28:11] đó bây giờ sự có rất nhiều cái hay giống
[00:28:13] như kiểu
[00:28:16] cậu dạng là cầu bang mới gì đó lập tức à
[00:28:19] đẩy lên vít hát hay để dysport chẳng hạn
[00:28:23] luôn vẫn đấy cũng có một cái và cái này
[00:28:25] là nó lưu lại trên server nó để chạy
[00:28:28] chạy ngầm hộ các bạn thế nên là nó không
[00:28:30] tốn cho bộ nhớ các bạn cho tốn cái gì cả
[00:28:33] cùng lắm thì như tôi đã nói đó là miễn
[00:28:36] phí gì sẽ là sẽ Hình như chỉ cài được 12
[00:28:37] cái
[00:28:40] không thể cài bao nhiêu cái cũng được
[00:28:43] con mất phí sẽ thoải mái hơn
[00:28:47] Vì thế nên là mấy ông mất một tiền thôi
[00:28:48] à à
[00:28:52] Ừ anh không lên 11 à trái ý ông ấy nói
[00:28:55] là Windows 11 tất cả tôi hiện tại thầy
[00:28:59] Windows 11 chẳng hơn Windows 10 ở ở giao
[00:29:03] diện thì ra là tôi đợi nó lên hẳn có một
[00:29:05] cách tính năng gì đó đáng để lên và công
[00:29:07] và cũng là
[00:29:10] để cho nó ổn định đã Tôi thấy vẫn chưa
[00:29:13] ổn định thôi Lên làm gì đúng ạ nhiều hôm
[00:29:20] à À cái bạn ấy hỏi như này ăn thịt lại
[00:29:24] cái khóa này mình có dậy kịp để mà các
[00:29:28] bạn Vừa làm đoán 20
[00:29:29] à à
[00:29:33] ờ ờ Theo mình là kịp một vì là mình sẽ
[00:29:36] Phượng ngay ngay tại thời điểm này các
[00:29:39] bạn cũng đang hình dung được như mình
[00:29:42] nói thậm chí các bạn đang nghĩ làm trước
[00:29:44] các giao diện các hư hư nghĩ đề tài có
[00:29:47] từ rồi sau đó gì sau những buổi này thì
[00:29:49] các bạn thành dâu được ví dụ hộ sau bổ
[00:29:53] này không làm được xem thêm sửa xóa rồi
[00:29:55] thì mới ông chỉ đội tôi
[00:29:59] em dậy thiết kế mày ông lên datapes sau
[00:30:01] đó thì mới ông
[00:30:03] bắt đầu làm đầy đủ tính năng xem thêm
[00:30:06] sửa xóa hộ tất cả các bạn Đấy là tương
[00:30:08] đối gần như xong được Cái trang web đoán
[00:30:11] một rồi bị đón một nửa ra nó chị Chung
[00:30:12] quy quanh còn lại mỗi xem thêm sửa xóa
[00:30:16] thôi nó không có gì cả cái
[00:30:18] cho nên là
[00:30:21] 23 tháng với mình khá thoải mái
[00:30:23] cho thoải mái từ cho cả những kẻ bạn mà
[00:30:27] kiểu à Đang đi làm con Thư đương nhiên
[00:30:28] là
[00:30:32] các bạn mới học thì 23 tháng nó sẽ là
[00:30:37] tương đối không hẳn không hẳn là
[00:30:39] tin nhắn cũng không hoa nở dày mình thấy
[00:30:48] a tiếp theo là có bạn thì cho biết Pu
[00:30:52] epo video là kiểu dạng như cũng là một
[00:30:56] cái cách kết nối mẹ mai quý out theo
[00:30:58] kiểu hướng đối tượng thay vì dùng cái Hà
[00:31:01] máy quay Hôm trước mình nó dụng nếu mà
[00:31:02] bạn nào biết về cái này rồi thì các bạn
[00:31:05] vẫn áp dụng được nhé Không sao cả nhưng
[00:31:06] mà tôi chỉ cho nếu không làm ngay thôi
[00:31:08] chứ mày ông không làm hướng đối tượng
[00:31:12] hoàn toàn hay mới với xe đâu nhé
[00:31:15] tiếp theo nữa đó là Chào bạn hôm trước
[00:31:17] câu hỏi
[00:31:20] vì vậy chỉ một câu cảm thán thôi đó là
[00:31:24] TP mà nhúng thêm một đống hlcs với cả
[00:31:26] loa Speed nữa trong một cái file rồi sẽ
[00:31:29] là tập Nham Đúng thế nên là buổi sau tôi
[00:31:31] sẽ hướng dẫn các bạn là sẽ là phải tách
[00:31:34] tách các thứ thứ ra thì ông sẽ thấy da
[00:31:37] tôi sẽ hướng dẫn bé không tách dần ra để
[00:31:38] cho một cái file của ông không quá dài
[00:31:41] về một file nó dài mà đôi khi nó còn lặp
[00:31:44] lại nữa đó lặp lại khá nhiều nên mấy ông
[00:31:46] sẽ thấy à
[00:31:49] ở Cốt nó dài ra thì khó sửa tính nhân là
[00:31:51] như thế trước mắt là như thế đã trông ạ
[00:31:52] Anh
[00:31:54] a tiếp theo
[00:31:58] ờ ờ nhưng vừa nãy mình nói Đăng cốt lên
[00:32:01] hosting thì thứ nhất là
[00:32:05] vì nó có thể dễ bị hack rồi các bạn vẫn
[00:32:07] chưa lường trước được tất cả những cái
[00:32:11] những cái kiểu chống Thế là có thể ông
[00:32:14] nào đó vào hack của mấy ông thì những
[00:32:16] cái ông bà tiếp theo thì sẽ là bị hack
[00:32:19] không ạ thấy ra tôi khuyên mà em không
[00:32:23] không nên băng hosting đường lên host
[00:32:26] sinh nữa mà chỉ nên đăng ít áp thôi tôi
[00:32:27] vẫn đọc được cốt mà Tạm thời trước mắt
[00:32:30] được tôi vẫn nằm ở cốt a đấy tiện thể
[00:32:31] nói luôn à
[00:32:33] trình kia ông đang học sinh nên tôi
[00:32:36] không xem được cốt PT của mấy ông nên là
[00:32:38] mấy ông nên phải đăng ký tên Linh kết
[00:32:42] hợp cũng như là thực ra tôi chấm mấy ông
[00:32:43] thì tốt chỉ xem được mức tương đối thôi
[00:32:44] Thông cảm
[00:32:48] Ê mấy ông bây giờ Đông sinh viên tôi
[00:32:50] cũng lại chấm cách định vị trong bé ông
[00:32:57] Ê bà Nè thấy tôi dùng từ nhạy cảm đây
[00:33:00] nữa nó là gì bởi vì là vừa rồi Tôi để ý
[00:33:04] nghĩa là có phải ông copy code từ bên
[00:33:07] hosting đấy sang bên get help vẫn còn
[00:33:11] vẫn còn là user name và password của cái
[00:33:15] bên hosting Thành A đấy một cái nghệ ca
[00:33:17] đương nhiên là ông sẽ nghĩ rằng là khắc
[00:33:20] tinh của ông chẳng có gì cả nên là bị
[00:33:23] hack vào cũng chẳng sao cả Nhưng mà việc
[00:33:27] mong béo để lộ mật khẩu đôi khi là mật
[00:33:30] khẩu nhiều ông dùng một mật khẩu cho tất
[00:33:32] cả mọi số 4 đã được họ vẫn là mỗi thứ
[00:33:34] tình cảm đúng không ạ Cháu là mấy ông
[00:33:37] Khi mà Tự ra tội từng bị dính một lần đó
[00:33:40] là khi mật copy luôn Đúng cái cốt ở trên
[00:33:43] local thôi đẩy lên khí H2 nha bị lỗi rất
[00:33:46] nhiều cái cảm ở trong cái cốt đấy với
[00:33:48] ông phải cân nhắc lại vụ đấy Đó là mấy
[00:33:49] ông
[00:33:52] em xem kỹ lại cái file khi mình đẩy lên
[00:33:53] nó có liên quan mật khẩu liên quan đến
[00:33:55] tóc nad ngoan Cookie hay các thứ không
[00:33:58] trước khi ông đẩy lên ký Tháp nhá ghế
[00:34:10] Ừ Ok tôi vừa trả lời xong hết rồi ông ạ
[00:34:13] Bây giờ bắt đầu học nhé
[00:34:16] khi bắt đầu buổi học thôi hôm nay sẽ học
[00:34:18] khá nhiều đấy
[00:34:20] à à
[00:34:29] Anh tên hình mình cứ mở thời trang mạng
[00:34:34] khi nóng tính school này Ừ thì nó sẽ ra
[00:34:36] được bài như này không ạ
[00:34:39] Hôm trước mẹ làm những gì hôm trước mình
[00:34:40] đã hiển thị cho toàn bộ những cái bài
[00:34:43] răng thêm được bài mới như thế này không
[00:34:46] ạ Và ấn vào xem chi tiết được một bài
[00:34:48] đăng rồi Hôm nay mình làm tính năng sửa
[00:34:52] xóa trước mắt là sự Xóa ngọn thì mình sẽ
[00:34:55] ra ạ mình vào lại cái file crack tải lại
[00:34:58] file trang chủ ở Đông ạ Mình sẽ ra thêm
[00:35:01] thường người ta sẽ thêm cái nút sữa vào
[00:35:02] nút xóa ngay bên cạnh từng bài đăng như
[00:35:06] này chị sẽ cái kiểu ý này sữa non rồi
[00:35:08] xóa này à
[00:35:15] tại sẽ là
[00:35:19] mình bạn chắc cái này sẽ là for update
[00:35:24] thừa nhận chuẩn PJ và
[00:35:30] đây người ta sẽ hiểu là khi bấm mà sửa
[00:35:33] đây nó sẽ sửa cái bài đăng bài đăng này
[00:35:34] không phải sự bé đang này đúng không ạ
[00:35:36] thì giống như hôm trước mình làm cái vụ
[00:35:39] xem thôi Có mình nên truyền mã vào trong
[00:35:42] cái đừng đừng Linh khi bấm vào mình sẽ
[00:35:45] hiểu là mình sửa cái bài đăng nào nó sẽ
[00:35:48] như này lại bấm vào đây sẽ sửa đúng ạ
[00:35:50] đấy
[00:35:55] a tiếp theo là vĩnh copy tên file Thôi
[00:35:57] đi file mới đây
[00:36:01] tìm lồ này tôi thường hay làm như thế
[00:36:03] này không biết mấy ông như nào Nhưng tôi
[00:36:05] thường làm này nhanh nhỉ
[00:36:07] ở tại xóa này
[00:36:09] Anh vừa mới tạo nhiều hoặc 18 xóa đi Ừ
[00:36:13] thôi thường này đắp ý kết trình Cài file
[00:36:17] in shop này lên Tại sao có gì Rõ ràng là
[00:36:19] Ford rất là giống nhau để tôi thường này
[00:36:22] đã ký kết trình Cái pha lê này đó để
[00:36:24] chúng ta đã có phai mới là tiện đúng
[00:36:28] không ạ Nếu mà sau vai tách của mấy ông
[00:36:30] thì không có mấy cái thêm tùy chỉnh kể
[00:36:32] topic kết các tư thế này đâu nếu không
[00:36:35] phải cày nên kẹp moggi à Cái Pocket
[00:36:38] giống tôi nhá Pocket của tôi ở trên
[00:36:41] trang blog tôi có đấy
[00:36:45] đó và bây giờ đương nhiên là khi mình
[00:36:47] sửa cái gì đó tốt làm chị mình cần hiển
[00:36:49] thị lại toàn bộ những cái nội dung đã có
[00:36:52] đúng không vì mình sửa chứ không phải
[00:36:54] mình gõ lại từ đầu đúng không ạ thì cái
[00:36:57] để mà lấy lại toàn bộ nội dung đã có thì
[00:36:59] mình sẽ dựa theo cái mã này mình đã kết
[00:37:01] nối cơ sở liệu sai bây giờ theo mã này
[00:37:03] lấy đúng cái bài đăng này về để mình
[00:37:06] điền đầy đủ toàn bộ thông tin lại và bài
[00:37:09] đang đấy vào trong này để mình sửa đúng
[00:37:11] Ừ thì đây sẽ là
[00:37:14] đoạn này mình cũng có có thể copy được
[00:37:17] tiếc mình lại copy đoạn trên này thôi
[00:37:20] mình có vui đoạn trên này à
[00:37:21] ông
[00:37:26] bà bây giờ mình sẽ là lại mã đôla ghế Mã
[00:37:28] Ý
[00:37:32] a selected for tin tức này Where mã bằng
[00:37:37] mã ngay các kết quả trả về các kết quả
[00:37:40] này như hôm trước mình có nói cái vụ mà
[00:37:42] xem cụ thể một bài đăng cũng tương tự
[00:37:46] với đó là khi mà mình lấy cái này về Rõ
[00:37:47] là các bạn sẽ nghĩ rằng chỉ có một bài
[00:37:50] bài báo có cái mã thì thôi đúng không ạ
[00:37:53] nhưng nó vẫn sẽ trả về dạng mà mình cảm
[00:37:55] thấy thằng đầu tiên của mà sẽ là kiểu ý
[00:37:58] kiến thức lúa
[00:38:01] bằng Michael cách dây
[00:38:06] Anh
[00:38:08] ấn Window số
[00:38:13] thì mũi tên để sẽ chia đều được như thế
[00:38:20] ừ ừ
[00:38:24] anh ở đây sẽ ra tự động điền vào trước
[00:38:26] thì nó sẽ có vô lu như thế này thì sẽ
[00:38:28] tin tức này
[00:38:37] Ê bà cái value trước cho cái thằng cách
[00:38:39] Alo này thì mình sẽ không có mình sẽ
[00:38:41] thích thẳng ở đây chứ mình không có cái
[00:38:43] tục tình boro giống như thằng này nhé
[00:38:47] này mới ông xem này họ như này ở đây sẽ
[00:38:49] nội dung này
[00:38:53] ở đó Ok chưa
[00:38:58] a tiếp theo Linh ảnh Peru thôi
[00:38:59] À
[00:39:02] mà đây đội đó là
[00:39:12] ờ ờ
[00:39:16] a tiếp theo làm Nếu mà Mấy ông Thực ra
[00:39:19] là bấm sửa như thế này
[00:39:21] Ừ thứ nhất là phải sửa cái này thì vô xe
[00:39:23] tắt nết này
[00:39:26] thế theo nữa đó là khi vào xưởng này
[00:39:28] mình đẩy cái form này sang
[00:39:29] [âm nhạc]
[00:39:33] 7 file này for mày sang cuốn sách update
[00:39:36] thì nó không đẩy được cái mã này sang
[00:39:39] theo đâu rồi Cái cái mã bằng 6 đây này
[00:39:42] Nó sẽ không được đẩy theo ở trong cái
[00:39:46] pho mày đâu thì nó sẽ bị mất hay tôi thử
[00:39:48] ví dụ cho mèo nhé á
[00:39:51] cách tạo phải mới này
[00:39:53] FPT này
[00:39:57] tôi thử này mỗi Đô La Mã về đôla ghét mã
[00:40:00] người uống xe nữa nhé
[00:40:05] tả lại trang đã này phẩm sữa này đó với
[00:40:07] ông thế là mã không có này tôi đổi nó
[00:40:11] thành đô reports để lấy mã về tả lại tra
[00:40:15] này vẫn không được đúng ạ đấy bởi vì họ
[00:40:18] cái mã Đấy nó đang ở trên hai nghệ sĩ nó
[00:40:20] không về được đẩy theo phải phom tôi bấm
[00:40:26] em thì làm thế nào để món đẩy theo được
[00:40:29] cả cái fan Bây giờ thì chị thì mình sẽ
[00:40:32] phải mình sẽ có tôi thấy à thường hay sẽ
[00:40:34] có 2 cách
[00:40:38] số 1 là ông sẽ có một cái input ở đây
[00:40:42] như này và nêm Sẽ Làm mã xong rồi va lu
[00:40:45] nó là như thế này là sự Đô La Mã nhé các
[00:40:46] bạn
[00:40:48] thì tại sao này nếu không thấy có một
[00:40:51] cái phút đây đúng không ạ sau khi tôi
[00:40:54] bấm vào thì đương nhiên là cái cái này
[00:40:56] nó sẽ được gửi theo rồi là sự tôi nào ra
[00:40:57] này
[00:41:01] đó nếu không thấy nó ra không ạ Chứ
[00:41:03] không bé Ông thấy thử cái cái in phút
[00:41:06] như này nó hiển thị ra như người dùng sẽ
[00:41:09] không hiểu vì dùng có quan tâm mã bằng
[00:41:11] bao nhiêu đâu đúng không ạ người dùng
[00:41:13] Điền vừa Vũ Cẩn ơi có khi cầm cái lỗi
[00:41:16] không ạ nên Cường cái một là cái bút này
[00:41:19] sẽ bị ẩn đi nó là hai đứa như này
[00:41:23] thứ hai là hai bên sẽ ẩn đi ăn đi Ở đây
[00:41:25] em chỉ ẩn đi người dùng không nhìn thấy
[00:41:27] chứ có ông Ấn cân cho nó ngủ lâu nữa sẽ
[00:41:30] thấy là như thế này và tôi thấy khá
[00:41:32] nhiều trạng trang thật trước tựa thằng
[00:41:34] Facebook nó cũng làm theo cơ chế kiểu
[00:41:38] như này nó sẽ là ẩn nó đi
[00:41:40] ở đây là một cách khoảng cách thứ hai là
[00:41:42] mấy ông truyền thẳng lên ở trong cái á
[00:41:45] trên lý này là hỏi chấm mã bằng như vừa
[00:41:48] nãy và mình sẽ dùng riêng cái mã thì
[00:41:50] mình sẽ dùng đôla ghét để lấy mã về có
[00:41:51] những cái thằng khác rồi mình cùng Dora
[00:41:55] post Nhưng mà thường là tôi thấy à mày
[00:41:57] nhiều thằng Hướng là làm theo cậu hứng
[00:41:59] này có hơn nên tôi sẽ dậy mấy ông theo
[00:42:01] hướng này nhá Ừ
[00:42:02] Ừ
[00:42:07] ok Tại mình sẽ có tiêu đề bằng đôla post
[00:42:13] nội dung và anh
[00:42:22] ở đây ạ ở mỗi buổi tôi sẽ nói thêm bằng
[00:42:25] những cái mẹo nữa này mà ông rút gọn cốt
[00:42:28] này đó là mấy ông thấy là thôi lại phải
[00:42:30] lặp lại cái đoạn điệp khúc này đông ạ
[00:42:33] đoạn này còn khuyên đóng kết nối này đấy
[00:42:35] nhưng mấy ông hiểu nó lúc nào phải lặp
[00:42:38] lại lặp đi lặp lại cái đoạn cốt này và
[00:42:40] việc lặp đi lặp lại cốt ở trong lập
[00:42:42] trình Nếu không có được tốt Bởi vì
[00:42:45] bởi vì là nó liên quan việc ở Giả sử về
[00:42:48] sau ông muốn đổi đã tao bây giờ sao cũng
[00:42:50] không còn gì school nữa Hoặc do ông đổi
[00:42:52] mật khẩu thì sao Đúng không ông lại phải
[00:42:54] sửa mọi pha nhắc đến cái loại cốc đấy
[00:42:56] thì ra đấy không người tốt cốt lặp đi
[00:42:58] lặp lại đến 2 lần ở miếu phải cân nhắc
[00:43:01] việc là phải tấm nó sang một cái file
[00:43:04] khác rồi mày ông chen cái pha này vào Ừ
[00:43:07] nó là sẽ làm như sau tôi sẽ tạo ra một
[00:43:10] cái file ở đây tôi lỡ để toàn bộ Cái này
[00:43:11] tiếng Anh với tôi đề này tiếng Anh lúc
[00:43:15] nhá phải thì con wreck.it này phải này
[00:43:17] nó bản chất là gì phải là chỉ có mỗi hai
[00:43:20] dòng cốc thôi Nó là cái này đó như thế
[00:43:23] này sau đó thì
[00:43:26] tất cả cái đoạn này của tôi
[00:43:29] khi sử dụng cốt ở đoạn này thì tôi sẽ
[00:43:32] ghi là include
[00:43:33] I
[00:43:36] Connect sample
[00:43:40] cái Hà Min Plus này nó có tác dụng là
[00:43:44] chèn thêm cái file khác vào và vẫn dùng
[00:43:46] được bình thường nếu khai báo biến kết
[00:43:48] nối ở đây thì dưới này dùng được biên
[00:43:51] kết nối để luôn không thấy là nói cái
[00:43:52] các bạn Nếu thấy chẳng Cốt nó chẳng thay
[00:43:55] đổi gì cả Không ạ Nó vẫn sẽ chạy như thế
[00:43:57] nhưng mà
[00:44:00] Mấy ông về sau mấy ông sẽ chị sửa ở chỗ
[00:44:02] này thôi tất cả chỗ khác gọi để cái file
[00:44:05] này đều được Tại tôi sẽ sửa nha nhiều
[00:44:08] với ông tôi sẽ sửa nó bên file này cũng
[00:44:12] thế đội đây này phải thật ngay đội đây
[00:44:15] này đó nếu không thấy nó sẽ ngắn hơn khá
[00:44:19] nhiều không ạ Và đây tôi chỉ chén hết
[00:44:23] đứa này thế này xong rồi ông ạ ạ
[00:44:26] à à Nhân tiện đây thôi chị mày ông luôn
[00:44:28] nhân nhân tiện nói với cái in Plus này
[00:44:30] để cho chị mèo luôn nhé
[00:44:35] đang là file for update đúng không Ok
[00:44:38] mày không Thấy ok Đang last bình thường
[00:44:40] đúng không ạ hả Mình cứ nút đang loa rất
[00:44:43] là bình thường là xưa gọi là nếu ra sự
[00:44:46] méo in Plus cái file này về sau file này
[00:44:48] tự nhiên có vấn đề phải bị mất hay là
[00:44:49] thậm chí ông gõ đường link những cách
[00:44:52] pha này lỗi là sự đừng lên lỗi như này
[00:44:54] trở lại đúng không ạ
[00:44:58] Thấy thì khi mà in close ngay Rất là nó
[00:45:00] tìm đến cái file có file của tên như thế
[00:45:02] này và Trần pha này hiện tại đã không
[00:45:04] tồn tại đúng không ạ thì nó sẽ xảy ra
[00:45:06] trường hợp Duy tự nhiên nó sẽ xin lỗi
[00:45:08] thôi nó sẽ thì cái lỗ ở đây cái sẵn rồi
[00:45:11] nhưng mà ông thấy à ngoài việc nói gì
[00:45:13] thì lỗi là file này không tồn tại này
[00:45:16] đúng không ạ Nó còn hiển thị ra mua loa
[00:45:19] lỗi ở dưới này nữa như thế này Tại sao
[00:45:23] tới nạn thôi bởi vì mấy ông dùng cốt ở
[00:45:25] trong Ừ thì nó chạy mà đúng không ạ thì
[00:45:27] cốt ở trong vai này không còn thiếu như
[00:45:29] toàn bộ cái phân dưới lỗi vẫn là đấy
[00:45:31] thôi đúng không ạ
[00:45:34] liên hệ để tránh việc mà khi vào chèn
[00:45:38] cái file nào đó lỗi mà dưới nó vẫn chạy
[00:45:41] như này thì không tốt à không không ở
[00:45:43] lại không cần đổi trái các đâu mình sẽ
[00:45:45] khái niệm mà request như thế này
[00:45:46] anh
[00:45:50] đi quay nó sẽ cũng sẽ là ingrowth tất cả
[00:45:53] là sẽ chèn thêm cái file khác vào như là
[00:45:55] các bạn xem thử nhé
[00:45:57] ở đó
[00:46:00] Ừ cái dùng đi quay như này các bạn sẽ
[00:46:03] thấy ra khi mở file không tồn tại
[00:46:08] Ừ thì cốt ở dưới nó không chạy luôn đấy
[00:46:10] con khi mà file tồn tại thì các bạn hãy
[00:46:12] nói như nhau với qua anh Club rồi như
[00:46:15] nhau đều trả hiện kết quả như nhau đúng
[00:46:17] ạ đấy
[00:46:20] xem thêm tất cả những cái file quan
[00:46:24] trọng theo theo theo như tôi vừa nói vì
[00:46:26] những file quan trọng thì có bạn nên
[00:46:27] dùng đi qua chứ không nên dùng yêu cút
[00:46:31] về mà chèn thêm cái phao Và thậm chí về
[00:46:33] sau các bạn sẽ còn biết thêm được nhưng
[00:46:35] mà cốt các bạn dài quá Này nói thêm một
[00:46:38] tí này là các bạn sẽ thêm Cậu biết cả
[00:46:41] was once này nữa nếu không biết tiếng
[00:46:43] anh một tí thì biết ngoan này tức là một
[00:46:49] lần đấy thì kệ cái j quone nó chỉ đơn
[00:46:52] giản và khi quay thì chèn file One cũng
[00:46:55] sẽ ở trẻ nếu file nhưng chỉ một lần bạn
[00:46:57] thắc mắc thì thấy cái này giúp cổ truyền
[00:46:59] nhiều lần á Không nhưng mà cái này có
[00:47:02] tác dụng là nó hiện chén bao nhiêu lần
[00:47:05] cũng được tôi như thế này thì sẽ làm chỉ
[00:47:07] là nó sẽ chèn lên file này lần này lần
[00:47:09] tự nhiên và các bạn cốt này thì nó không
[00:47:12] sao chứ Giờ xưởng với các bạn cốt mà để
[00:47:14] in ra một cái gì đó các bạn
[00:47:16] Ừ thì các bạn thấy nó lặp đi lặp lại nó
[00:47:18] sẽ tạo là bao nhiêu cái đít rồi đây bao
[00:47:20] nhiêu cái gì gì đó nhiều lần
[00:47:24] freeone thì nó sẽ nó sẽ chèn file này
[00:47:26] một lần thôi lần sau gọi đến file đấy
[00:47:30] nữa vẫn vẫn là file cũ ý thì nó sẽ không
[00:47:32] trả thêm nữa
[00:47:35] Ừ để tác dụng của cái Hàn đi quay One E8
[00:47:38] trẻ nó chị tiện cho lập trình viên để
[00:47:41] lập trình viên mà kẹo có quên là đã chèn
[00:47:43] file đấy ở đoạn trên này rồi thì nó sẽ
[00:47:45] không cần phải chèn thêm nữa
[00:47:47] Lê Quốc Khánh có lợi cho lập trình viên
[00:47:51] rồi kìa bởi vì tại sao phải xin hàng này
[00:47:55] bởi vì sau tôi các bạn Nhớ lúc đầu tôi
[00:47:58] nói qua về cái vụ à à
[00:48:00] ở tay
[00:48:02] ừ ừ
[00:48:08] ở đây đây pp nhúng lẫn lộn với các thứ
[00:48:12] làm nó rối mấy ông nhớ tôi bảo là cái
[00:48:14] cốt về sau bọn mày ông có lên đấy nhìn
[00:48:17] dòng ạ thì mấy ông sẽ tách nhỏ thành
[00:48:19] nhiều file để mấy ông Wei lại Linh Plus
[00:48:22] như này nhiều lần đấy đâu ạ thì cái việc
[00:48:25] anh về sau gần như là một file của ông
[00:48:27] Toàn đi khoai cái Plus xong rồi mấy ông
[00:48:29] sẽ có trường hợp việc cái file Giả sử
[00:48:31] cái file con ếch này còn J quite mình
[00:48:33] cái file khác vào file khác đấy cũng vui
[00:48:36] quay file con ếch thời gian mới bị lặp
[00:48:37] đi lặp lại cái file con ếch hai lần để ạ
[00:48:39] đấy
[00:48:41] chỉ có một vài trường hợp để tôi nói cái
[00:48:44] file này lặp lại thì không sao nhưng có
[00:48:45] những cái file khác gặp lại nó sẽ lỗi
[00:48:47] đúng không ạ Cái thành gian làm mấy ông
[00:48:49] sẽ phải thêm cái Hà mày để chắc chắn nó
[00:48:52] sẽ chỉ được gọi đến một lần thôi ấy
[00:48:55] Ê mấy ông để nó cẩn thận thì béo không
[00:48:57] dùng hàm ý một nốt Không dùng hàm vinh
[00:48:59] Wei mới ông chỉ dùng hàm viqua ăn cũng
[00:49:02] được cho là chắc Ừ thế là tốt nhất trong
[00:49:15] I - hàm phải này lại gọi đến file kia xô
[00:49:18] xe kia lại gọi file này liên tục Chắc là
[00:49:20] nó hình để quên mất đúng không ạ là đẹp
[00:49:22] lại bao nhiêu lần thì chết luôn không ạ
[00:49:27] cái lý do phải có sinh ra cái hay one
[00:49:30] ok hơi dài dòng quá lại quay lại em nhé
[00:49:33] Ok
[00:49:37] câu truy vấn đây khi đoàn đấy
[00:49:39] bằng
[00:49:43] update tin tức đúng không ạ
[00:49:47] xét thôi Thấy viết thì cậu này không
[00:49:50] biết mày ông tôi tôi sẽ viết cũng nhanh
[00:49:53] nha mấy ông thử xem nhé Mình cập nhật
[00:49:55] tiêu đề rồi đúng không ạ Chị sẽ đưa tiêu
[00:49:56] đề này
[00:50:06] về sẽ là
[00:50:09] nội dung này à
[00:50:15] hình ảnh quê mã bằng mã đó
[00:50:17] à à
[00:50:26] ở đây đây đây các bạn sẽ thế cập nhật
[00:50:29] tiêu đề nội dung ảnh whey mã bằng ngày
[00:50:32] mã mình truyền lên Thế xong lúc ạ Mày có
[00:50:35] đi free
[00:50:37] cái nối này
[00:50:46] ở đây vẫn phải đóng Lúa
[00:50:48] hay quên cái vụ này
[00:50:51] à à
[00:50:52] Vì
[00:50:58] vậy tôi thử độ nhé F1 này ngày 31 này
[00:51:00] ở đây
[00:51:02] anh Linh ảnh để tra tại Nguyên đi uống
[00:51:04] sữa này
[00:51:07] cô gái không không lỗi gì cả không báo
[00:51:14] 300 lỗi bởi vì rõ ràng là tôi có in a
[00:51:17] lỗi đâu đúng ạ bây giờ kìa cả câu truy
[00:51:19] vấn của tôi lỗi như nào nữa cũng không
[00:51:21] yên lỗi nhưng mà Mấy ông cách tốt nhất
[00:51:24] là một lần mấy ông vào đây B để xem hay
[00:51:28] là mấy ông cứ mở hẳn một cái trang trang
[00:51:31] chủ Để mà xem trước không ạ đó mấy ông
[00:51:34] sẽ thấy là cái một lên đây rồi ở trong
[00:51:43] à à
[00:51:46] ở đó tiếp theo là đừng cái xóa xóa Thì
[00:51:49] nó khá nhanh đây có chuyện ra là truyền
[00:51:52] nó không cần có một cái form gì cả Nói
[00:51:55] chuyện lạ Delete Thôi như thế này cũng
[00:51:58] sẽ truyền cái mã của cái bài Mình cần
[00:52:00] xóa lên sau đó thì mình bấm mà ở sẽ xóa
[00:52:02] thôi
[00:52:05] ở bài nó sẽ bấm vào nha sẽ hiểu là xóa
[00:52:08] cái bài đăng đấy đứng như là thường ở
[00:52:09] mấy cũng làm cẩn thận thì mấy ông lên
[00:52:12] thêm một cái copper một cái xác nhận nữa
[00:52:14] từ
[00:52:22] ngày 31 à Tôi không hiểu sao nó thay
[00:52:25] ngày mưa nhớ hơi sai đấy
[00:52:28] à mà không ngày 31 là bên nội dung hỏi
[00:52:30] về nội dung
[00:52:34] tiêu đề rồi mới sửa cái F1 thôi à
[00:52:39] ở
[00:52:44] đây tôi sẽ tạo 1 file nữa là phải xóa
[00:52:46] cái tên
[00:53:01] con ếch chứ
[00:53:04] cái để anh ở việc đôi khi bị cũng không
[00:53:06] nhớ rồi lúc nào tiếng Anh tiếng Việt thì
[00:53:09] ra tôi cốt khi ở trên công ty Cô ơi cốt
[00:53:12] Toàn Toàn bộ bằng tiếng Anh Rồi nghe Huế
[00:53:14] phải là đáng sợ nó quá nhưng mấy ông
[00:53:17] Thực ra cũng đơn giản lắm Bởi vì à Nếu
[00:53:19] mấy ông mới vào công ty ra người ta cũng
[00:53:24] có cốt mẫu có thứ Nếu chỉ xe biến là
[00:53:26] người bạt ở gì đặt giống thế là được rồi
[00:53:29] khi em Nếu không hiểu Nó nghĩa là gì là
[00:53:30] được
[00:53:31] Ở
[00:53:38] thông tin tức
[00:53:51] uống rất thích cái xóa với nó là dang
[00:54:02] em bận mà Soái
[00:54:06] à Không có gì xảy ra đi quay lại bên này
[00:54:08] Anh quay Nếu mà Mấy ông bấm quay lại như
[00:54:10] này ông sẽ thấy không bị xóa đâu vì quay
[00:54:12] lại cái này hình như nó lưu lại vì vậy
[00:54:14] em với ông tải lại chan thì mới thấy bị
[00:54:23] Em đang học cơ bản không dùng phương
[00:54:25] trình không dùng các thứ không dùng thư
[00:54:36] Ừ ok đấy đấy đầy đủ tính năng thêm sữa
[00:54:39] xóa xem thêm sữa Xóa Bây giờ mình sẽ làm
[00:54:42] thêm những cái gì à Nếu mà Bộ mày Chị
[00:54:45] nhắn thì thôi như cả nó hơi bị ngàn quá
[00:54:48] thế nên là mình sẽ dạy theo các bạn thứ
[00:54:52] nhất là vì à phận tìm kiếm trước đi tìm
[00:54:54] kiếm đã mình sẽ có thêm một cái hai
[00:54:57] người thế này ta sử mình có nhiều bài
[00:55:00] đăng không ạ bây giờ cách tốt nhất của
[00:55:02] mình làm mình sẽ có
[00:55:04] D3 Mày đang đi
[00:55:08] thì mình sẽ thêm ba bà nhé Dân Trí đây
[00:55:12] kiếm 3 bài đã thêm hai bài nữa được
[00:55:15] à à
[00:55:18] Vì sao làm tính năng cậu
[00:55:20] khu dân trí đang bài gì thì mình sẽ tự
[00:55:23] động lấy bày lại bài đấy về trang web
[00:55:25] của mình không có một cách
[00:55:27] à à
[00:55:30] các bạn hôm trước vậy
[00:55:35] ta0 ảnh trông có vẻ vẫn thế như không
[00:55:37] à à
[00:55:48] du lịch Nguyễn cay nghiệt ở
[00:55:50] à à
[00:56:13] em lấy được mà
[00:56:15] Thì
[00:56:19] bà gọi đến cái link này là xem được Bà
[00:56:23] Đanh nó thì sẽ có 1 con Boss này đọc bài
[00:56:25] đấy hộ bà thôi lấy hết toàn bộ những
[00:56:27] thông tin của bé đang ấy về Thế có nhớ
[00:56:31] xong Thế ông đã gần như Clo được một cái
[00:56:34] trang web người ta về chúng tôi có hai
[00:56:36] ba để xem nên không thôi
[00:56:39] Ừ ok Nói chung có 3 bài tại sao tự nhiên
[00:56:41] tôi có 3 bài Bởi thứ nhất là tôi sẽ làm
[00:56:43] việc tìm kiếm Thứ hai là tí làm phân
[00:56:46] trang 3 bài thuốc giả sự phân mỗi bài 1
[00:56:52] ở đây là sử dụng bây giờ mình sẽ có cái
[00:56:54] thanh tìm kiếm ở trên này đúng ạ Mình
[00:56:57] nhập vào để tìm kiếm thì tôi thường hay
[00:56:59] chơi như này sẽ có một cái thẻ cáp chân
[00:57:04] này Tại sao có thể phát sinh bởi vì nó
[00:57:06] sẽ nhìn vào cái trên trên của cái thuê
[00:57:10] buồn đó giữa khá thích nó thế heo mình
[00:57:12] sẽ có bao nhiêu một cái form rồi chồng
[00:57:15] cái nút là search
[00:57:18] cái bút Nếu Út hay sốt như này thì mấy
[00:57:21] em không cần phải có cái nút Bá Tân đêm
[00:57:23] nữa mà mày ông chỉ cần bấm enter là nó
[00:57:26] sẽ là tự động sắp microphone khá tiện
[00:57:29] Tôi sẽ đặt tên em à đây Tìm kiếm đúng ạ
[00:57:32] như này à
[00:57:35] em có cái này nhập cái gì đó nên tờ này
[00:57:38] thì nó sẽ đẩy lên thành cái địa chỉ tìm
[00:57:41] kiếm bằng cái gì đỏ như này ok không ạ
[00:57:43] Nếu không thấy là tôi đưa nhập bất cứ
[00:57:45] cái gì thì nó vẫn sẽ hiển thị tất cả bài
[00:57:48] đăng thực là thế không tốt đúng ạ Thôi
[00:57:52] tôi cần là ví dụ là gõ F1 thì nó sẽ chỉ
[00:57:54] ra những cái bài có tiêu đề có tiêu đề
[00:57:58] chứa cái từ mà tôi đã tìm kiếm nó ngoác
[00:58:00] cái đoạn này tức là mình cần phải làm gì
[00:58:03] đó là mình cần lấy cái tìm kiếm ở trên
[00:58:06] thanh địa chỉ này về sau đó thì mình sẽ
[00:58:09] lách soundforge cái tiêu đề where were
[00:58:13] tựa đề thuộc cái mà mình đã truyền lên
[00:58:15] trên huyện chỉ đóng ngoặc a cho tôi sẽ
[00:58:18] là đô la tìm kiếm đi
[00:58:20] bằng
[00:58:31] sau đó thì mình sẽ away tiêu đề
[00:58:34] like mà ông nhớ lại Ạ phần trăm phần
[00:58:36] trăm
[00:58:40] Tìm kiếm đợi Tức là sao nghĩa là tiêu đề
[00:58:44] có chứa cái chữ mà mình có tìm kiếm đúng
[00:58:49] đấy Bây giờ tôi thử xóa thôi à Bây giờ
[00:58:51] tôi thường gõ chữ f 1 được đấy
[00:58:56] eater Ra đúng ạ Gọi F2 đấy không ra bài
[00:58:59] nào về chưa thế ổn thôi chứ đây nó sẽ có
[00:59:02] những điểm nữa đó là nếu giờ sự toán mới
[00:59:06] và các trang web như này có sẽ bị báo
[00:59:08] lỗi là cái biến Tìm kiếm của tôi đang
[00:59:09] nói
[00:59:12] vì nó không hề có nó không hề tồn tại
[00:59:15] đến nhiên rồi vì tôi đã tìm kiếm đâu ông
[00:59:17] ạ mới vào trang web vì đâu có tìm kiếm
[00:59:27] Em đang dạy quen mà về sau sẽ cho các
[00:59:29] bạn làm quen dần dần từng từng từ khóa
[00:59:31] tiếng Anh một số đó về sau toàn bộ bằng
[00:59:32] tiếng anh
[00:59:40] cho mình mình sẽ phải kiểm tra là nếu mà
[00:59:42] có tìm kiếm thì mình mình lấy nó về đúng
[00:59:47] không ạ thì mình sẽ lại ít em Tại tôi sẽ
[00:59:49] có cái hàm này để mấy ông kiểm tra xem
[00:59:53] mà nó có thì ah Nếu có Và nếu không
[00:59:57] Mình sẽ kiểm tra nếu có này reset rồi
[01:00:02] Nếu có đôi loa ghét Tìm kiếm nếu nếu nó
[01:00:03] có
[01:00:06] thì mình sẽ lấy cái đôla tìm kiếm về như
[01:00:07] này
[01:00:13] tả lại trang này nếu lại thấy cái lỗi
[01:00:16] nữa lỗi này Nếu phải để ý kỹ lỗi nhá lỗi
[01:00:18] nên để hiển thị ra để cho lập trình viên
[01:00:21] mình nhìn nhưng mà lỗi này thì chị ra để
[01:00:24] mà mày ông có khỏi tôi đâu nhá Đấy
[01:00:27] Ừ Cái lỗi này là gì Nó bảo không Không
[01:00:31] tìm thấy cái biến biến Tìm kiếm ở dòng
[01:00:34] 21 đúng lại là dòng này tất cả chỉ là
[01:00:36] cái biến tìm kiếm này nó không có đúng
[01:00:38] rồi vì mình có tìm kiếm đâu mà có biến
[01:00:41] Tìm kiếm đúng không ạ thì
[01:00:46] mình sẽ mình sẽ làm đó là mình một là
[01:00:47] ông
[01:00:49] khi tách nó ra thế hai câu truy vấn như
[01:00:50] thế này
[01:00:53] ở
[01:00:56] ngã trường hợp ngược lại này
[01:00:59] thì cầu truy vấn của ông sẽ không có
[01:01:01] whey như thế này
[01:01:05] vào như này thôi nghĩa là nếu có tìm
[01:01:09] kiếm thì mình sẽ lấy cái tìm kiếm về này
[01:01:13] và I work phải tìm kiếm ông ạ Còn nếu
[01:01:16] không thì ông sẽ lấy tất đồng lại đây
[01:01:19] một cách mà ông có thể áp dụng theo cách
[01:01:23] chơi khác như tôi nghĩa tôi sẽ dậy đến
[01:01:25] mức cơ bản này thôi
[01:01:27] à à
[01:01:35] ạ Và ở đây và đây nhá vị giả sử là bây
[01:01:39] giờ ông Nghiệp ấy một ẩn ok Nó ra được
[01:01:43] rồi đó ngọn nhưng nhiều người khó chịu
[01:01:51] em muốn hiển thị lại những cái mà mình
[01:01:54] đã tìm kiếm ở đây không ạ người dùng
[01:01:56] quên mất là người dùng đã nhập cái gì để
[01:01:58] nhận thế người dùng muốn thi lại cái
[01:02:00] mình đã tìm kiếm rồi đây mình sẽ có ba
[01:02:05] lô ở đây là EXO đôla Tìm kiếm được ạ
[01:02:09] đó thì nó sẽ hiển thị ra những người như
[01:02:12] tôi vừa phải có nói đó là Nếu giả sử lúc
[01:02:15] đầu ông không tìm kiếm gì đó lại lỗi lại
[01:02:17] bảo lỗi ở đây là không tìm thấy biến Tìm
[01:02:19] kiếm đúng ạ Cái đoạn này mình lại phải
[01:02:24] làm gì mi lại phải vào đây là Minh lại
[01:02:30] phải pp bpa ở đây như này ít reset I
[01:02:38] và đây sẽ là papain này bóng ít như thế
[01:02:43] Em nói như này
[01:02:46] ib1 cách
[01:02:50] Ừ nhưng mà người mà ông thấy bạn này nó
[01:02:53] sẽ rất là dài không hiểu là kiểm tra
[01:02:56] Thôi trông cốt chống phải xấu đúng ạ Tôi
[01:02:58] có một mẹo này khiến mì uống cà phê
[01:03:05] ở đây tôi sẽ tôi sẽ cho lúc đâu người
[01:03:08] dùng Tìm kiếm chúc đầu
[01:03:17] bằng nghỉ chỗ rộng ngay
[01:03:18] anh luôn
[01:03:20] ạ sau đó thì
[01:03:22] ừ ừ
[01:03:24] ạ sau đó đi sao
[01:03:27] Ừ tôi sẽ có luôn đoạn này xuống dưới như
[01:03:29] thế này à
[01:03:31] à à
[01:03:34] em không thấy à nó chạy ngon không gần
[01:03:37] đây gì nữa đúng ạ Tại sao cái đoạn này
[01:03:39] vẫn chạy ngon cho tủ rõ là tôi không thể
[01:03:42] tìm kiếm tôi tìm kiếm thử nhé
[01:03:45] vẫn ngon này Xóa các tìm kiếm đi
[01:03:49] vẫn ngon này Tại sao thì tôi sẽ giải
[01:03:51] thích mấy ông đoạn này Đầu tiên là tôi
[01:03:53] cho mặc định nó bằng chuỗi rỗng Đông ạ
[01:03:56] Nếu không thấy đều không ạ sau đó thì
[01:03:59] nếu mà có phải tìm kiếm của tôi để hệ gì
[01:04:02] thì tôi lấy cái tìm kiếm mới về truyền
[01:04:04] nó vào trong cái chỗ giọng đấy đúng ạ
[01:04:08] sau đó tôi queo nó hiện nay có xảy ra 2
[01:04:11] trường hợp trừ một là nó không có tìm
[01:04:14] kiếm thì chỗ đấy là rỗng mà tiêu đề like
[01:04:16] theo cái chỗ rõ đấy
[01:04:19] Ê mấy ông sẽ nghĩ nó lỗi không ạ Không
[01:04:22] tìm cái gì cả không Nếu mà like theo
[01:04:23] kiểu là
[01:04:25] à à
[01:04:30] Ừ nếu mà ông nhớ thì like theo
[01:04:34] như thế này hoa cả thận thêm một cái nữa
[01:04:37] có thêm chục cái nữa thì nó nó vẫn sẽ
[01:04:40] trả về mụn gọi dậy kết quả của vì like
[01:04:43] như thế này tất cả không nó thỏa mãn nó
[01:04:46] luôn thỏa mãn bởi phần trăm như dõi từng
[01:04:48] nói nó Thái cho một hoặc nhiều ký tự
[01:04:51] không ký tự nào được like hết đông ạ Thế
[01:04:53] Lai như này tất cả like đúng kiểu như
[01:04:57] này không có gì cả nó sẽ trả về mọi
[01:04:58] người quả không lỗi
[01:05:01] mà biến Tìm kiếm ở đây vì nó luôn khai
[01:05:04] báo trên này nên là mình sẽ không mở bị
[01:05:06] báo lỗi ạ bên Tìm kiếm không không tồn
[01:05:09] tại không ạ tôi cách rút gọn của tôi
[01:05:12] thường hay là em giờ không biết được mấy
[01:05:14] ông có thấy khó hiểu quá không
[01:05:16] còn không người Méo phải ít nhau rồi như
[01:05:19] vừa nãy đồng mạng thế tôi chỉ nếu hai
[01:05:21] cách đấy
[01:05:24] Ừ rồi bây giờ vừa rồi làm xong tính năng
[01:05:26] về tìm kiếm
[01:05:28] anh không biết mày không đủ thoáng chưa
[01:05:30] Nhưng bây giờ sẽ dạy thêm về tính năng
[01:05:31] nào
[01:05:33] ở phân tra
[01:05:35] phải làm tìm kiếm trước mới làm để phân
[01:05:39] tranh tại sao vì hai thằng nó thương lại
[01:05:41] đi kèm với nhau và có liên quan đến nhau
[01:05:44] ạ bây giờ sự mấy ông thầy đang có Bye
[01:05:46] bye bài đăng với ông thấy ít thì ra
[01:05:47] chẳng cần phải phân trang thì cứ mỗi 3
[01:05:50] bài mày không ạ Nhưng mà nếu bây giờ sự
[01:05:53] danh đương nhiên là về sau
[01:05:55] ở phía sau có nhìn bài đăng
[01:05:58] anh 2 triệu 7 đang đứng như trang tin
[01:06:01] tức trang Dân Trí ạ thì khi ở mới vào
[01:06:06] trang web này cái tê nó cơ chế là nó cái
[01:06:10] file pp a nhớ nhớ kỹ thuật này nhé ppp ở
[01:06:14] cơ chế nào là nó phải chạy Xong hết nó
[01:06:15] mới hiển thị ra cái trang web của mì ông
[01:06:17] Hải ra mấy ông thấy vào một vài cái
[01:06:20] trang web thấy nó loát nữa lâu rồi nó
[01:06:23] trắng trắng tinh rất là lâu rồi đúng
[01:06:25] phát nó hiển thị ra một loạt đóng ngoặc
[01:06:28] trắng tinh và tận mười mấy giờ thì em ạ
[01:06:31] rất là lúc đấy file file pp đó phân xử
[01:06:35] lý phải render ra htl xong hết đã dầu
[01:06:38] mới nở một loạt ạ
[01:06:42] ý thì cái trải nghiệm người dùng công
[01:06:45] nghệ tốt bây giờ là sử như tôi nói nó là
[01:06:47] một triệu bài đăng ở hạn ông phải chạy
[01:06:49] vòng lặp in đủ 1 triệu 7 đang ở đây đã
[01:06:55] rồi mới trả về cho người dùng thì
[01:07:00] Vì sao thầy hiệu trưởng thi Cai
[01:07:02] Ừ cái trải nghiệm người dùng chứ sao nó
[01:07:04] không hề thích cái điều đấy đúng ạ với
[01:07:05] dùng đâu cần để xem hết một triệu về ăn
[01:07:07] cùng một lúc đó đúng quá người dùng chỉ
[01:07:09] cần xem những cái bài đăng mới nhất phải
[01:07:11] vân vân chẳng hạn thế thì bây giờ cách
[01:07:13] làm như thế nào đó là bây giờ mình sẽ
[01:07:17] phân cha mình sẽ bây giờ đang Mới có 3
[01:07:19] bài đăng đây là mình sẽ phân trang giả
[01:07:21] sửa mỗi mỗi mỗi trang một bài đang trở
[01:07:24] lại hoặc cả hai bài
[01:07:28] 12 bài 10
[01:07:32] 12 bài 1 trang thì sẽ ra bở Để câu hỏi
[01:07:39] em hỏi mấy câu đơn giản nhé em xem lại
[01:07:42] ông giỏi toán không à Tôi đang có 3 bài
[01:07:44] đúng không ạ Bà bài đăng
[01:08:09] anh hỏi Toán tập 1 khi nướng trả lời tôi
[01:08:33] ở một trang rưỡi cũng đúng 1 chén rưỡi
[01:08:40] ạ bây giờ mấy ông những cái ông mà trả
[01:08:42] lời 22 trang có vẻ đúng rồi đúng không ạ
[01:08:45] Cứ cho đúng đi mấy ông trả lời tôi Tại
[01:08:54] Mà tại sao nó lại thành ai chưa
[01:09:04] Ê mấy ông lấy ra đâu ra con số 2
[01:09:12] em làm tròn 1,5 đến 2 cái ông lấy 1,5 ở
[01:09:18] sơ đồ ngoại 3 chia 2 làm tròn lên đúng
[01:09:21] không ạ Ok bạn kia vừa nói được cái công
[01:09:25] thức phải có công thức luôn công thức để
[01:09:28] ra được số trang không ạ nghĩa làm chỉ
[01:09:29] là
[01:09:32] mình sẽ
[01:09:35] Ừ cái 37 đang nó sẽ là tổng số 7 đang
[01:09:38] đóng lại sau đó thì mình sẽ chia cho số
[01:09:39] bài thơ Người Cha
[01:09:43] và hai bài không ạ rồi làm tròn lên
[01:09:47] không ạ thì sẽ thành ra được tổng số
[01:09:48] trang ah
[01:09:51] Ừ thì bây giờ câu truy vấn để mà mình là
[01:09:56] ý được tổng số hải đăng thì mình sẽ
[01:09:59] A1 làm mấy ông sẽ nghĩ là sẽ cao đúng
[01:10:00] không ạ nhưng mà không Không cần phải
[01:10:04] làm vụ sẽ thích cao mình mình sẽ có thể
[01:10:12] ở Hà Nội chắc mình cũng phải làm sao đây
[01:10:19] mô hình sự selecao để đếm số bài đăng
[01:10:24] thỏa mãn đã để mà ra được số trang đúng
[01:10:25] không ạ
[01:10:36] câu
[01:10:38] về tôi sẽ có
[01:10:41] đợi tôi tí
[01:10:43] khi tôi viết lên trên này đi tôi sẽ viết
[01:10:47] lên trên này à s clous
[01:10:48] ở
[01:10:50] lại là số trang nhà
[01:10:55] bạn cernex cao sao này
[01:11:04] ạ sau đó đi Đương nhiên mình sẽ có kết
[01:11:12] là kết quả số trang đi
[01:11:17] và lấy cái này mình sẽ cần là lấy cái
[01:11:25] Ừ
[01:11:31] thì mình sẽ có câu truy vấn à đây thôi
[01:11:33] tôi sẽ gọi là câu truy vấn này
[01:11:35] Ừ vậy thì tôi phải nghĩ là cái tên này
[01:11:39] đó sẽ dễ cho mấy ông kiểu xem cái này nó
[01:11:40] đỡ choáng đi
[01:11:42] ê ê
[01:11:43] chung
[01:11:48] kết quả số trang lần hay đi bằng
[01:11:50] mcquarrie
[01:11:54] fake tôi hết
[01:11:57] Tôi đã không nghĩ được cái tên nào tiếng
[01:12:00] Việt để cho mấy ông có phải dễ hình dung
[01:12:02] cái này
[01:12:04] anh Bởi vì cái này làm ảnh
[01:12:08] mạnh đây mạng số trang này
[01:12:11] và đây sẽ là kết quả số trang
[01:12:16] và đây mới số trang này à nhầm nhầm đây
[01:12:17] không phải số trang quên quên quên tôi
[01:12:20] bị nhao nhao nhao số bài đăng mới đúng
[01:12:22] số tin tức
[01:12:24] Việt Nam lấy tổng số tin tức mà không ạ
[01:12:30] E Ngại quá ngại quá
[01:12:33] số tin tức này à
[01:12:36] à à
[01:12:39] ấn
[01:12:42] vào đây xù tin tức sẽ bằng
[01:12:46] kết quả chính thức tại hàm cao sao
[01:12:50] bao nhiêu này để lấy ra được số xổ số
[01:12:51] tint
[01:12:55] Khi mà mình sẽ cho là số
[01:13:07] ca nhạc đâu vậy
[01:13:11] ờ
[01:13:15] sau đó đi mình sẽ ra số trang nhưng mà
[01:13:20] vợ vừa nãy các bạn nó tách là số tin tức
[01:13:23] chia cho số tin tức
[01:13:26] trên một trang và làm tròn lên đúng
[01:13:28] không ạ làm tròn lên mình sẽ có Hàn là
[01:13:33] hàm sale như này là hàm trần nhà để làm
[01:13:37] tròn Nó lên đấy mình thử DC cái số trang
[01:13:41] để các bạn xem nhé đây đi tất cả à tức
[01:13:43] là nó sẽ nắp nó sẽ in ra kết quả bằng
[01:13:48] nắp tại dòng này luôn các bạn xem em
[01:13:50] xin lỗi
[01:13:53] à À đây đây nhầm nhầm nhầm cái này kết
[01:14:04] a a nhằm Bye bye quên PD ê
[01:14:07] ở đây nó giả hay đúng ạ Tới tất cả hai
[01:14:08] tranh
[01:14:12] à Mình nhầm nhầm DD là nghèo hư rồi quên
[01:14:14] quên quên đấy chứ
[01:14:19] Bye bye nha Đang nhé lắp tại cái đấy
[01:14:22] Ừ ok Các bạn thấy cha là hai đúng rồi
[01:14:26] đúng không ạ Nếu mà cái hai này chả tác
[01:14:28] dụng gì cảm vì bây giờ nó vẫn chưa ngắt
[01:14:30] trang ngọn Các bạn thấy nó vẫn đang hiển
[01:14:33] thị ra 36 37 đang mà đóng ạ thế là bây
[01:14:35] giờ để lắp
[01:14:38] bây giờ mình sẽ Limit
[01:14:43] là số tin tức trên một chai như này thì
[01:14:44] nó sẽ nhắn này
[01:14:49] ở đó có bạn thấy lúc nó chưa chín tạ 89
[01:14:53] này Cái bài thứ 10 nó nhẹ sang trang thứ
[01:14:55] hai ở Đông ạ Thế bây giờ làm thế nào nhẹ
[01:14:58] sao cha thứ 2 đóng ngoặc thì mình sẽ cần
[01:15:00] thường là tôi sẽ in ra một cái đường
[01:15:03] Linh ở đây bấm vào nó sẽ nhiều thời gian
[01:15:05] hay Bấm vào nó nhảy sáng giao một chẳng
[01:15:09] ạ thì mình sẽ có ở cuối cái thê bồ thì
[01:15:12] sẽ có một cái á vòng lặp vậy mà
[01:15:15] Đây đây rõ ra là chỗ Trang là hai nhá sẽ
[01:15:18] có phòng họp ở in ra từ một đến hai từ 1
[01:15:21] cho đến để số trang từ ngọn thì sẽ vòng
[01:15:24] là for cũng được TP là mình là pho này
[01:15:27] đâu lai rai bằng 1 bắt đầu từ một này
[01:15:31] đôi y đền cái số trang này
[01:15:35] và đôi cộng cộng này
[01:15:36] các
[01:15:46] mà đây mình sẽ có thể A ở đây
[01:15:49] Tại sao phải thấy ai thì tôi sẽ nói sau
[01:16:00] ở đó thì mày không thấy à bây giờ bấm mà
[01:16:02] Em bấm vào thì nó sẽ nhảy sang trang 1
[01:16:04] và tháng 2 đúng ạ
[01:16:06] em đứng nhân bé Ông thấy là bây giờ nó
[01:16:09] vẫn đang ở trang trang một thôi ông ạ
[01:16:11] bởi vì sao thì mình cần bấm vào đây nó
[01:16:14] sẽ nhảy đến một cái gì đó không ạ Con sẽ
[01:16:17] đây tôi thường nó sẽ cho họ chấm trang
[01:16:21] bằng như này cho nó kèm theo đôla y nhà
[01:16:23] à
[01:16:26] có phải lại sao Này bấm vào này nó sẽ
[01:16:28] nhìn sang trang 2 này bấm vào nó nhưng
[01:16:31] sẽ nhảy sẽ trang 10 ạ Hiện tại ông thấy
[01:16:35] tôi bấm vào trang hay nó vẫn là vẫn thế
[01:16:38] chả gì thay đổi Tại sao Bởi vì bởi vì
[01:16:40] cốt của mình chỗ này nó chưa hề lấy cái
[01:16:44] số trang trên 2 địa chỉ lại về đối ngoại
[01:16:47] ở cốt này chưa hề lấy số trang trên này
[01:16:50] bị chị về nhớ lại tính tiếp bây giờ lạnh
[01:16:53] anh
[01:16:59] hỏi lại tiếp này
[01:17:03] ờ ờ trang 1
[01:17:10] à à
[01:17:15] ở
[01:17:38] Ba Tháng Hai của tôi thì mày đâu
[01:17:40] A1
[01:17:42] hãy kể một bài văn
[01:17:45] ừ ừ
[01:17:47] Ừ cái này rẽ mấy ông cha giỏi toán rồi
[01:17:50] bố rơi rồi chắc sẽ giải quyết được bài
[01:17:54] toán này Bây giờ giả sử tôi Giả sử tôi
[01:17:57] lại đi Tôi có 15 mô trang của tôi chứa
[01:17:59] tận 37 đăng ký
[01:18:14] U17 đăng một trang chửi 3 bài thì có
[01:18:17] tổng cộng bao nhiêu năm OK bốn chàng
[01:18:20] không ạ Ok mày không trả lời 44 tra
[01:18:35] anh
[01:18:46] Cho tôi thời gian béo trả lời kia tôi
[01:18:49] chẳng biết nó trả lời câu thứ bao nhiêu
[01:18:50] đấy
[01:18:53] cái chat rồi nó không bị delay 30 giây
[01:18:55] nữa
[01:18:59] có câu Hãy trang hay hiển thị mấy loại
[01:19:02] vẫn Ba thôi không ạ rồi Ông kia trả lời
[01:19:05] luôn 331 kìa không ạ
[01:19:08] chẳng hay hiển thị 33 trang 3 thì như
[01:19:11] ông kia vừa nói cũng hiểu đi 3 trang 4
[01:19:15] thì Thị Như ông kia nói đó là một bài
[01:19:18] không ạ và tại sao tại sao nó ra là con
[01:19:21] số một này cái Chỉ đơn giản đơn giản là
[01:19:25] mình sẽ với ông dạy bảo là lấy 10 - 3 -
[01:19:29] 3 - 33 Nó còn 1 thôi mà đúng ạ Nhớ công
[01:19:31] thức tính nó không phải như thế cứ tính
[01:19:34] của cái số số bài
[01:19:35] một
[01:19:37] số bài còn lại
[01:19:44] thì nó sẽ là công thức là mười ạ 10 này
[01:19:53] tôi
[01:19:58] - cái cái số gì đúng không ạ tổng số ba
[01:20:01] đây ông ạ - Cái số gì để ra có số 1
[01:20:11] và chính xác à nó chỉ còn - cái nó phải
[01:20:14] bỏ qua bao nhiêu bài mê mấy ông phải nói
[01:20:17] là nó phải bỏ qua bao nhiêu bài đúng rồi
[01:20:21] bạn kia ra công thức Đúng rồi đấy nó là
[01:20:29] nhân với ba nó không ạ Cái ba đấy rất là
[01:20:35] gì là số trang - 1
[01:20:37] ở đó
[01:20:40] Khi say sẽ đạp bỏ qua bằng con số như
[01:20:41] thế này
[01:20:44] thi công thức nó sẽ như này
[01:20:48] I know Phương Linh ở đúng rồi đó là tổng
[01:20:50] bác ái tổng số bài trừ đi số bài trên
[01:20:52] một trang
[01:20:56] mỹ nhân với số trang hiện tại và số
[01:21:03] - 1 đây là bỏ qua bỏ qua bao nhiêu bài
[01:21:06] Ừ cái 10 bài đăng này bạn chất là nó nó
[01:21:09] bỏ qua mày hợp mấy ông phải xem nữa là
[01:21:14] để bỏ qua không bài Bỏ qua 3 bài đầu
[01:21:17] đây là bỏ qua sáu hoài đầu
[01:21:22] bà đây Bỏ qua chín vài đầu
[01:21:25] đúng ạ
[01:21:29] vụ tai nạn ở đây Cái này nó không Tôi
[01:21:31] không biết Nó cũng có tính toán ấy không
[01:21:34] Nhưng mà thực ơi ông chỉ cần biết được
[01:21:36] cái này lần đầu tiên khi mà học lập
[01:21:38] trình về sau mình có thể lo dụng Mấy ông
[01:21:42] không cần phải nghĩ nhiều về nó mấy nữa
[01:21:43] nhưng công thức nó là như thế này đúng ạ
[01:21:46] Nó bỏ qua bao nhiêu bài không ạ
[01:21:50] xe tải Thì bây giờ mình có công thức đầu
[01:21:52] tiên thì mình sẽ lấy
[01:21:54] mình sẽ lấy số trang hiện tại về đúng ạ
[01:21:57] Mình sẽ là
[01:21:58] thời trang
[01:22:03] bằng đôla gas sang
[01:22:06] đây lấy trang hiện tại về Đông ạ sau đó
[01:22:07] mình làm gì
[01:22:11] mình lấy tổng số bài chưa ạ Lấy chồng số
[01:22:14] bài rồi số 7 chương 1 trang này rồi thì
[01:22:16] bây giờ mình sẽ làm công thức bỏ qua
[01:22:18] thôi bỏ qua
[01:22:24] sổ tin tức này
[01:22:31] số kiến thức chứa một trang nhân với số
[01:22:32] trang ah
[01:22:33] em
[01:22:40] - 1A
[01:22:59] ở đây sẽ bỏ quá Mà mình ở đây mình sẽ có
[01:23:00] thêm offset
[01:23:04] là bỏ qua nha Là sao em mình sẽ chạy thử
[01:23:10] Ừ hình như có gì đó Sai sai để xem lại
[01:23:20] à à đôi đâu thì hình như tôi ghi công
[01:23:22] thức khi nhưng khi bị sai rồi xin lỗi
[01:23:32] 3000 đoạn này tôi nhận đấy bỏ qua không
[01:23:35] phải công thức này Ờ
[01:23:38] số bài trên một trang nhân với số trang
[01:23:39] hiện tại
[01:23:42] Ừ ừ Chị ngại thôi bỏ cái xuống thức đi
[01:23:43] tôi nhầm
[01:23:47] Ở nhà quanh hậu Á
[01:23:55] có ai đây Đúng rồi Đúng rồi ngủ quá đi
[01:23:58] Ừ Ông ơi Không cần phải lấy tổng số bài
[01:24:01] chủ đi nữa về chỉ là số liên tục nhân
[01:24:05] với số trang hiện tại rồi - 1 thôi ok
[01:24:08] tại mày không thấy ngon chưa đó Thế làm
[01:24:12] được cái xin Trang rồi nhưng mà Anh nên
[01:24:14] nhớ là mình luôn kiểm tra đó là khi giờ
[01:24:17] xóa này đi nó lại nổi này không ạ Nó lỗi
[01:24:19] rồi kìa lúc đầu vào thì làm gì có trang
[01:24:21] nào đúng ạ thì mình sẽ phải Quý Hưng
[01:24:24] luôn lúc đầu vào nếu mà không truyền
[01:24:26] trang lên thì Trang nó sẽ mặc định là
[01:24:30] bằng mút Đông ạ thì mình sẽ là thì lấy
[01:24:32] sẽ có là
[01:24:35] ở lại ít cái này thôi copy cái đoạn này
[01:24:39] đổi Đây là Trang Thôi
[01:24:41] vào đây sẽ eo
[01:24:43] trang bằng 1
[01:24:46] Còn nếu ông ấy Ông muốn kiểu không muốn
[01:24:48] dùng eo thì ra hạn chế dung theo ít
[01:24:51] nhiều mình có thể quý gốc luôn lúc đầu
[01:24:53] được
[01:24:56] nó vẫn như nhau đúng
[01:24:59] xe tải không lỗi gì cả
[01:25:00] anh ạ
[01:25:03] à Nhưng cái này lại còn sinh thêm một
[01:25:05] vấn đề cuối sinh thêm vấn đề cuối nó như
[01:25:09] sau là sử tôi tìm kiếm
[01:25:16] có thể tội tôi bây giờ mấy méo hình Dũng
[01:25:18] được cái việc à phân tranh này rồi nha
[01:25:21] mẹ tôi đổi số liên tức trên một tra là
[01:25:22] một đi
[01:25:26] Ừ thôi mấy ông sẽ thấy à Có 3 bài nên có
[01:25:29] thành 3 trang Ok đúng ạ Bây giờ tôi sẽ
[01:25:40] Ừ hết một enter đúng nhỉ
[01:25:51] Ừ đúng rồi em một em tôi ở đây mấy ông
[01:25:53] sẽ thấy các em
[01:25:56] Ồ không tôi chưa dậy mấy ông để hỏi chấm
[01:25:58] hỏi chấm đâu cơ bản thôi
[01:26:02] à em một em tờ đây mấy ông thấy đang lỗi
[01:26:04] còn gì số trang rồi Không đúng đấy trước
[01:26:07] một bài thôi Chỉ có một bài có chữ em
[01:26:10] một thôi đúng ạ bởi vì bạn này ở đoạn sẽ
[01:26:13] cao này tôi không đúng nó sẽ cao này tôi
[01:26:15] phải kết hợp với cả tìm kiếm mày nữa
[01:26:19] tôi sẽ
[01:26:23] Ừ tôi sẽ vứt cái đoạn mà
[01:26:27] đi tìm kiếm lên trên tạo vất cài đặt tìm
[01:26:28] kiếm lên trên này
[01:26:32] cho tôi sẽ Where giống hết cái đoạn nó
[01:26:37] cả hai loại đều quay tìm kiếm này không
[01:26:40] ạ một hàng để lấy số tin tức để mà lấy
[01:26:43] ra được số trang nữa đâu ạ
[01:26:44] à à
[01:26:47] ở đó tôi tải lại sao này nó ra đúng một
[01:26:50] bài đăng ra đúng một trang thôi Ok đúng
[01:26:53] rồi đúng không ạ nhưng mà bây giờ giả sử
[01:26:54] thôi
[01:26:55] chờ
[01:26:59] đợi tí cái xem có hai cái bài đăng thì
[01:27:00] tốt
[01:27:05] ở Hà Nội Hà Nội 33 có hai bài đang ấy
[01:27:09] thì Đức Hà Nội Hà Nội này inter này nếu
[01:27:10] thấy có hai và năng nhớ Hà Nội đúng
[01:27:12] không ạ
[01:27:15] anh bởi sao cho tìm kiếm chữ Hà Nội thì
[01:27:19] nó sẽ chỉ có bài đăng tiêu đây Hà Nội
[01:27:22] em nếu bây giờ tôi ấn vào sàn thứ hai
[01:27:25] ở đâu thấy gì xảy ra không ạ nó lại
[01:27:27] thành 3 Hải Đăng tại sao nó lại thành ra
[01:27:30] ngoài đăng bởi vì chỉ đơn giản là mấy
[01:27:32] ông thấy để ý trên anh nghệ sĩ đã nó
[01:27:34] không hề truyền theo cái mình đã tìm
[01:27:37] kiếm đúng ạ
[01:27:39] nó không truyền theo cái mình đã tìm
[01:27:42] kiếm mà khi bấm vào đường link ở đây nó
[01:27:46] sẽ chỉ truyền theo cái mẫu số trang thôi
[01:27:47] mà không truyền theo cái mình đã tìm
[01:27:48] kiếm
[01:27:50] ở đâu thế
[01:27:52] ở Hà Nội đấy
[01:27:56] cái tơ này đó như thế này lại mất đúng
[01:27:58] không ạ Thế được cách để mình giải quyết
[01:28:01] bài toán ở đây đó là
[01:28:05] cho mình khi mình à nhảy Sang trang khác
[01:28:07] mình cũng phải truyền theo cái mình đã
[01:28:09] tìm kiếm thế thôi mình sẽ có và đây này
[01:28:12] tìm kiếm bằng
[01:28:20] Vì vậy tôi tả lại tra phát nữa này đầu
[01:28:23] tiên không có bạn vẫn 3 bài có phải đúng
[01:28:27] Hà Nội này enter này tôi bấm nhảy sang
[01:28:31] trang 2 đó nó sẽ kèm theo cả tìm kiếm và
[01:28:35] nhảy sang trang 2 về chưa đó Đây là toàn
[01:28:38] bộ toàn bộ về
[01:28:42] ờ ờ phân tranh kết hợp với các tính kiếm
[01:28:50] à Mà ông kia đang bàn về vấn đề gì về
[01:28:54] sôi nổi về 13 này dễ cho mày hoang Smart
[01:28:56] rồi sẽ bỏ qua đi
[01:28:58] ừ ừ
[01:29:01] Ừ ok à
[01:29:03] đề thi
[01:29:07] a b bây giờ sẽ nói nốt về mùng tí khách
[01:29:10] khùng à
[01:29:12] sơ đồ mạng
[01:29:16] để để cho mấy ông có vẻ hào hứng phút
[01:29:20] cuối thì cái vụ hack mà tôi tôi nói mấy
[01:29:23] ông đó là nếu mấy ông đăng cái trang
[01:29:26] trang web của mấy ông lên Nếu không
[01:29:28] phòng chống về khách cùng gì cả thì hoàn
[01:29:31] toàn thằng những cái bạn khác vào phá
[01:29:35] thì thì mấy bạn ấy sẽ có thể là nhập
[01:29:41] những cái kiểu là gọi lại SQL injection
[01:29:44] a khái niệm nó FBI injections thức là
[01:29:47] sao injection tất cả tiêm nhiễm tiêm mã
[01:29:52] độc sợ tiêm vào tiền thử không tốt và
[01:29:55] không phải tìm bác Xin lỗi nhé à
[01:29:57] A và
[01:30:01] phạm và cái từ spo tất cả thì nó lợi
[01:30:03] dụng lỗ hổng của Apple để mặc tiêm vào
[01:30:07] để mà làm gì đó là hack thì chắc chắn
[01:30:08] nào để làm những cái thứ mà kiểu không
[01:30:11] tốt giống như là cậu đây mà lấy thông
[01:30:13] tin các bạn hoặc là điều hướng các bạn
[01:30:15] Sang trang khác vân vân Bây giờ tôi sẽ
[01:30:18] làm thử đề môn trong mấy ông Đúng rồi
[01:30:20] tôi sẽ tự hack trang web của tôi sẽ
[01:30:22] thắng thật đi
[01:30:26] em giả sử bây giờ nếu để ý kĩ là bây giờ
[01:30:28] giả sử người dùng vào
[01:30:31] cái thằng hacker ấy thì nó sẽ cơ chế
[01:30:33] hack của nó sẽ làm như sau đó sẽ kiểu bà
[01:30:36] vào để ý kĩ là người dùng sẽ đang in ra
[01:30:38] cái gì ở trên trang này thì người dùng
[01:30:42] Đăng ký email tiêu đề không ạ
[01:30:44] khi người dùng đăng ký để tựa đề gì nó
[01:30:46] sẽ thật nhiều nó sẽ chỉ cố hack mà cái
[01:30:49] loạn tiêu đề để mà để mà khi mà người
[01:30:51] khác và nhìn người tiêu đây này nó sẽ bị
[01:30:53] lỗi nó sẽ kiểu hiển thị ra một cái gì đó
[01:30:56] nhạy cảm Và thậm chí cho nó lấy đực
[01:30:59] Cookie của các bạn mà như mình đã nói
[01:31:02] nhập các bạn
[01:31:05] mở rộng Tóc trên Facebook nó là yên đăng
[01:31:08] nhập các bạn nên thả và lấy khuy các bạn
[01:31:11] thì có nhờ các bạn mất nick kiểu thế
[01:31:13] Ừ Thì
[01:31:21] ạ bây giờ sữa tươi ẩn thêm bài viết này
[01:31:24] Tôi chỉ quan tâm tiêu đề rồi nhá Mấy cái
[01:31:26] nội dung có thử tôi để chống được không
[01:31:27] sao đúng ạ
[01:31:32] về tôi sẽ có thể cho thể H1 ngay cái lô
[01:31:45] 3000 thất bại gì không ạ bấm sao trang
[01:31:46] này
[01:31:49] em có nếu thế là thêm chữ Hello thành
[01:31:52] thể H1 rõ to không ạ Tức là sao nếu
[01:31:54] thoái cơ mà thử hack một cái đơn giản
[01:31:58] đây này nó truyền vào HTML bình thường
[01:32:02] mà nó in ra được đúng HTML như thế thì
[01:32:04] hoàn toàn nó có thể đi ra được cái gì nó
[01:32:06] nó không Không phải Ý là cái ảnh gì đó
[01:32:10] Nhưng cảm nữa mà nó thường ai chèn thêm
[01:32:13] ra Suite vào để mà điều hướng các bạn
[01:32:15] hoặc là như mình vừa nói là lấy được
[01:32:18] quốc kỳ các bạn Nhưng mà thường có thể
[01:32:20] điều hướng bạn xanh trong web Mở đó là
[01:32:24] sửa để Script này Windows chấm location
[01:32:26] thức hàng ngày ông sang trang web khác
[01:32:28] này Atlas này
[01:32:35] e Băng đúng nhỉ Nó không ngờ lắm Windows
[01:32:39] location the spirit không nhớ lắm đâu
[01:32:41] Hà Nội dung cái này mấy đó tôi khách
[01:32:56] Em thử đi thử thử thì biết không ạ
[01:32:58] ở
[01:33:01] bảng http
[01:33:03] google.com trở lại
[01:33:06] đóng thẻ Swift về
[01:33:09] chấm phẩy cho chắc
[01:33:18] he he lỗi lỗi bởi sao mai là nó hỗ trợ à
[01:33:22] Nó là kiểu mình đang có nháy nên nó bị
[01:33:23] lỗi như thế này
[01:33:24] Ừ
[01:33:27] thì mình chỉ dẫn thả là đổi cái nháy lại
[01:33:29] Thành nhái đút vào xong
[01:33:31] à à
[01:33:35] em vừa rồi mình dùng nháy đơn thì bị lỗi
[01:33:37] thì bây giờ mình đổi thành ấy Lúc thì
[01:33:42] xem thêm
[01:33:46] anh không nổi nữa đâu ạ Ok Bây giờ mình
[01:33:50] sẽ vào lại này sang bài này
[01:33:53] ở đó nó bị điều hướng sao Google mất rồi
[01:33:55] ở
[01:34:02] đấy mà ông sẽ thấy ạ Đây Rồi mới chỉ một
[01:34:04] ví dụ thôi
[01:34:06] Ừ nó thì điều hướng làm sao mà người
[01:34:09] trang web nguy hiểm Bảo gà mua khi vào
[01:34:11] da spa được chạy như thế hoàn toàn thể
[01:34:14] lấy Lúc kia của ông địa đẩy có kia ông
[01:34:18] sang server của nó vẫn loạn luân đấy à
[01:34:22] ở đây from theo kiểu form mà nhập vào
[01:34:25] cái gì mà Mấy ông không không hề kiểm
[01:34:29] tra nó thì mà Mấy ông kiểu cứ hiển thị
[01:34:31] ra đúng cái mà người dùng đã nhập người
[01:34:33] dùng nhập ra rất nhiều Ngày thứ nghị cả
[01:34:38] là nó sẽ hiển thị ra Đông ạ Đấy Vì sao
[01:34:40] tôi sẽ hướng dẫn hơn mấy ông cả khách
[01:34:42] được phải thanh tìm kiếm các thư thứ nữa
[01:34:45] mày ông sẽ có đầy thứ để mà biết hack
[01:34:48] thùng cá thôi hư không thể đem đi áp
[01:34:51] dụng đâu mà tôi tôi bảo tôi không biết
[01:34:53] về hack nhá tôi không học thế hạnh nhé
[01:34:56] nhưng mà tôi học lập trình cho tôi biết
[01:34:58] được là những cái chỗ nào nó có thể gây
[01:35:02] được lỗ hổng bảo mật thì nên là du lịch
[01:35:12] Ừ đúng rồi một lạng
[01:35:14] bình thường là bây giờ cũng nên làm
[01:35:16] những cái là duyệt nhưng mà những cái
[01:35:19] đăng ký hai mấy cái đăng bài đăng bài
[01:35:21] luôn vẫn phải chờ hết rồi chứ là đăng ký
[01:35:24] hai cái thự thứ gì đó nữa là sự giống
[01:35:26] nhau Hồi trước Việt Thảo cũng từng làm
[01:35:30] vậy
[01:35:33] âm nhạc của tui tự nhiên có cái lỗi lỗi
[01:35:38] vớ vẩn đấy Nó kiểu in cái tên người dùng
[01:35:41] nhập gì cũng không in ra xảy ra hồi đấy
[01:35:44] ở lớp lên hack kịch bài You tim của khối
[01:35:48] đấy khiến cho mà hồi đấy Cái phết rồi
[01:35:50] đấy ạ
[01:35:54] Ừ cái cái cái thấy dạy nói chung là cái
[01:35:57] đấy cái giải thưởng giải thưởng ạ
[01:36:02] đợt nào ấy đợt Chia sẻ mã code mã code
[01:36:04] mà nhiều người dùng để sẽ được lên cái
[01:36:07] bảng vinh danh của nhạc của tui là 8 giờ
[01:36:12] tối hôm đấy là công bố kết quả rồi thì
[01:36:14] cái mã đấy rồi chia sẻ trong Nuti Nuti
[01:36:18] thành ra là kẹo cái tài khoản của việt
[01:36:21] Hảo đấy được lên nằm trong tốp mười sau
[01:36:22] đó thì
[01:36:26] ờ ờ ông Việt Hạo ông vào thứ Tư đổi tên
[01:36:28] hàng kiểu giá quýt vừa rồi xong rồi chèn
[01:36:31] thêm Plus là hai cực bài trừ tim tự
[01:36:33] nhiên thế mà vẫn được thôi cùng thì ạ
[01:36:37] bất kỳ ai vào cái trang bảng xếp hạng
[01:36:38] đấy Đều hiển thị lên hai cực bài Điều
[01:36:43] tim mà lúc 7 giờ tối 2 7 giờ tối 1 tiếng
[01:36:46] trước khi công bố đi qua thành ra nhạc
[01:36:50] của tôi phải tạm đóng đóng cây trang web
[01:36:56] đấy và công bố cách đấy phải 4 tiếng đó
[01:36:57] ừ ừ
[01:37:00] Ừ từ trang web ở trang web nó rất là dễ
[01:37:03] dễ để cốt nhiều người thường ai cốt giữa
[01:37:05] rối Không kèm với một phương món gì cả
[01:37:08] cái búa cái đương nhiên là sẽ nó sẽ cậu
[01:37:11] chắc chắn không còn mình lỗi vớ vẩn thế
[01:37:14] nữa Nhưng mà thường trang web kiểu ngang
[01:37:17] như thế nhiều người cốt của p thuần cái
[01:37:20] gì đó nhanh ngay thôi đấy và công nhận
[01:37:24] thức ra cái đấy rất là tệ khi mà kiểu
[01:37:28] xe máy mà ông thì thảo thì ông ấy à Làm
[01:37:31] kẹo như thế để mà vui vui thôi
[01:37:33] về chưa ông ấy làm căng thì bất kỳ ai mà
[01:37:35] truy cập vào trang web bởi vì gần đến
[01:37:38] rồi công bố mày thằng là ai cũng vào để
[01:37:41] xem nữa trúng họ
[01:37:42] ừ ừ
[01:37:45] anh không nhận ra mấy ông đẹp quá lại
[01:37:48] khó chịu thật nhưng cũng biết rằng gần
[01:37:50] gần đến giờ công bế quả rồi tình yêu còn
[01:37:51] thương và pha
[01:37:55] đấy nhưng mà đấy chỉ là một cái ví dụ
[01:37:57] sát lại cậu
[01:38:01] thực hiện thực tế mà các bạn thấy à
[01:38:04] à Không vẫn có nhiều ông vẫn còn bị dính
[01:38:07] đâu ạ nhưng mà không Tôi khuyên béo được
[01:38:09] gọi cho dạy nha
[01:38:12] bộ phim Quốc nó tích hợp sẵn rất nhiều
[01:38:15] cái ạ thư viện hay các hàm có thử rồi
[01:38:17] thực ra về sau tôi chỉ ông Chỉ cần một
[01:38:20] hàm mày không trả được một cái từ một
[01:38:23] cách tương đối rồi những nhưng mà Phương
[01:38:25] Quốc thì đúng là chuẩn chị thôi con chặn
[01:38:27] cho ông không phải về mỗi mấy cái cậu
[01:38:29] Phố bẩn vừa rồi mà còn chặn nữa ông
[01:38:31] những cái về
[01:38:34] tư duy lôgic lỗ hổng bảo mật để tư duy
[01:38:37] lôgic nó còn rất nhiều nữa cơ
[01:38:39] anh về sau tôi chỉ muốn nhiều cái lắm Về
[01:38:42] Sau hôm bảo vệ đoán Lúc mà tôi ném đá
[01:38:44] không mấy ông cậu bé Ông thấy là cái đồ
[01:38:47] án của ông có thể dễ bị hack hay dễ bị
[01:38:56] khi dùng phải xss đi lấy được có key
[01:39:10] Em ở Việt Nam bình thường thế nào cậu
[01:39:13] chế em ạ Ông nhảy vào nhà thằng khác đấy
[01:39:16] phá cậu Thế ông luôn đi tù
[01:39:19] nó không có cơ chế cậu bức Bon Ti lắm
[01:39:22] Cho dù là nhiều công ty thì nó có hạn
[01:39:24] Chính xác cái thật đấy nhưng mà không
[01:39:27] phải là rất là sự thật kiểu nó vẫn không
[01:39:41] Ừ đúng rồi các bạn sẽ phải dùng ra
[01:39:44] spiders Hòa giọng như mình đã từng nói
[01:39:46] thì phải hoa ghép vào mắt em nữa kiểm
[01:39:49] tra xử lộ nhập vào các từ thứ trước khi
[01:39:52] nhập vào lưu lại trong B chúng mày kiểu
[01:39:54] các bạn Nhập vào bất cứ thứ gì lưu lại
[01:40:01] vừa rồi Các bạn thấy là rõ là mình đăng
[01:40:03] bài bài đăng mình còn không nhập tiêu đề
[01:40:05] không nhập ảnh vẫn còn thành công mà
[01:40:08] đúng thì ta thế không được
[01:40:09] à à
[01:40:18] Ờ Ờ mình không rõ vì cái cốc kỳ theo cơ
[01:40:20] chế cho Đốm main lắm
[01:40:23] anh bởi vì mình không tìm hiểu bên đấy
[01:40:24] lắm
[01:40:27] Ừ nhưng mà chắc chắn là nó có thể lấy
[01:40:30] được kì các bạn bằng có thể là không lấy
[01:40:33] được cô ky có đô main nhưng mà có nhiều
[01:40:36] cách mà sự có rất nhiều cách thì mình
[01:40:41] anh nói chung là một khi ở mấy ông vào
[01:40:43] một cái trang của bị hack rồi là kiểu gì
[01:40:46] mà béo bị lộ rất nhiều cái và bị ảnh
[01:40:49] hưởng nếu cậu nó tự động Download cái gì
[01:40:51] đó Bây giờ ra trình duyệt nó còn hỗ trợ
[01:40:54] chặn vụ nó vẫn khỏi lại vụ download
[01:40:59] Ừ nếu mà vẫn có cách để thông qua đấy
[01:41:02] cách câu nói chung hợp tìm mẹ lắm mấy
[01:41:03] ông
[01:41:05] áo phông cưới Hải Phòng trước đúng không
[01:41:11] Ừ ok
[01:41:13] vừa rồi mình nhận nói qua một loạt tất
[01:41:15] cả kiến thức của buổi hôm nay các bạn
[01:41:17] còn thắc mắc gì thì chắc là bình luận
[01:41:20] thôi không Không thì mình sẽ ra bài tập
[01:41:23] nhé Thứ 7 cho mình sẽ chữa bài I Swear
[01:41:32] à à
