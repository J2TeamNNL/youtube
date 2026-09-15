# Lập trình web cơ bản - buổi 30 - PHP & jQuery - Modal & Signin + Signup & Validate

- Video ID: `x_XNnYk1aiw`
- URL: https://www.youtube.com/watch?v=x_XNnYk1aiw
- Published: 2022-01-13
- Duration: 1h 42m 25s (6145s)
- Language: vi
- Subtitle source: auto
- Kind: live

## Transcript

[00:00:33] alo cho các bạn
[00:00:33] ừ ừ
[00:00:39] Xin
[00:00:51] Hôm nay nhìn cái tiêu đề tổn thế sợ thì
[00:01:04] Ừ hi vọng hôm nay trực ra hôm trước có
[00:01:07] bạn hỏi là kiểu cái này hợp để cho đồ ăn
[00:01:11] hai à Rồi cái học là để
[00:01:14] trong buổi hôm đấy Mình có nói rồi đó là
[00:01:17] kiểu đòn mua thì chúng ta các bạn không
[00:01:19] cần cái này và đồ ăn hay được các bạn
[00:01:22] cũng không thử cái chẳng cần cái này vì
[00:01:25] gj nó không phải là cái gì đó Bây giờ
[00:01:28] phổ biến nữa Ngân hàng ra là không phải
[00:01:29] cứ áp dụng vào được
[00:01:31] nhưng mà
[00:01:35] Học để cho biết thôi học để biết được ra
[00:01:38] kiếp có thể làm những gì Và có những thứ
[00:01:39] viện thể
[00:01:43] giúp việc cố Taylor Swift nhanh hơn ở
[00:01:46] tiện hơn giả sử như là hôm nay học về
[00:01:50] vaj chẳng hạn thì rõ ràng mà mình đừng
[00:01:52] dùng ra xíu về hết rồi thì như hôm nay
[00:01:55] có hẳn thư viện để làm nó màu mè hơn và
[00:01:57] nhanh hơn vân vân
[00:02:01] Ừ thì đấy Đấy do mình sẽ dạy các bạn với
[00:02:03] cái này bởi vì toàn bộ những cái cơ bản
[00:02:07] về pp là gần như là thật ra vẫn còn
[00:02:10] thiếu nhiều cái nhưng mà một cái trang
[00:02:12] web cơ bản thì ta chỉ cần tương đối thì
[00:02:15] thôi không cần không cần học thêm học
[00:02:19] thêm nữa thì nó bắt đầu nghỉ xanh trong
[00:02:22] web nâng cao rồi nên là thực ra toàn bộ
[00:02:24] những cái kiến thức mà các bạn
[00:02:30] Á đù điện đủ đồ bếp để tên VP rồi thì đủ
[00:02:33] làm cái đồn một rồi Còn bây giờ còn thời
[00:02:36] gian chẳng lẽ lại bảo các bạn bảo vệ đồ
[00:02:38] ăn luôn Thế nên là bây giờ mình đang dạy
[00:02:42] thêm cái cái dạy thêm này kiểu ai ai
[00:02:45] thấy xem học được và kiểu đi tham khảo
[00:02:48] thôi Như mình đã nói để tham khảo chứ
[00:02:51] không có màn hình chất là kiểu bắt các
[00:02:53] bạn phải làm này trong đó án phải có
[00:03:02] à
[00:03:07] à á Chắc truyền đi rồi cho nó báo lỗi về
[00:03:10] á Hôm nay mình sẽ làm vụ này đây
[00:03:14] à Hôm nay mình sẽ làm nên quan kiểm tra
[00:03:17] dữ liệu trả về đúng hay sai cũng thật
[00:03:21] cái thứ trước khi cho cho nó kiểu xử lý
[00:03:23] tiếp không ạ Hôm trước thì mình cứ để
[00:03:27] xã
[00:03:29] hội mà mình học làm đồ ăn một thì mình
[00:03:32] cũng Các bạn nhớ cái trang web mình đừng
[00:03:35] cho bạn xem đoán một rồi người ta mình
[00:03:37] có chè thì một tí xíu giở đấy và đấy à
[00:03:41] mình à tự mò thôi mình còn chưa nắm rõ
[00:03:42] được Syria là cái gì Vân
[00:03:46] thợ lò khá nhiều thế Đấy là thầy cũng
[00:03:49] tiểu thì chỉ nói tên tên công nghệ rồi
[00:03:52] để cho sinh viên tự more để tránh sinh
[00:03:55] viên kiểu ham hố đi tìm hiểu về công
[00:03:56] nghệ nhiều quá mà không chú trọng vào
[00:03:59] chức năng của đoán
[00:03:59] thế
[00:04:04] nhưng nhưng mà đó là nhược điểm khi mà
[00:04:10] kiểu để mò tự mò mới nhiều bạn tự mò nó
[00:04:14] cứ bị đi xa quái không đi đâu cả nhà
[00:04:18] mình mới mình mới nghĩa thôi dậy luôn
[00:04:20] Ừ nhưng mà dậy như này thì sẽ có nhược
[00:04:23] điểm là sẽ chất sáng có vài ông kiểu làm
[00:04:26] chưa xong hết tính năng nữa ham hồ thêm
[00:04:28] một đống công nghệ về
[00:04:31] Em ở chỗ nào Cái này các bạn phải phải
[00:04:34] vẫn phải biết à lượng sức mình này và
[00:04:38] sắp xếp cho phù hợp là sửa kiểu tất cả
[00:04:41] tính năng cơ bản phải cho Suốt các thử
[00:04:45] thử đã Đừng ôm gj rồi A giác về
[00:04:48] cái này rõ ràng là các bạn thấy ra hôm
[00:04:50] trước là mình
[00:04:52] tính năng của với mình xong hết rồi
[00:04:54] chẳng hạn trang web mình xong hết tính
[00:04:56] năng rồi mình mới bắt đầu kia
[00:05:00] khi nhúng a sắc về để cho nó kiểu không
[00:05:02] phải nó trang nghĩa làm triển tính năng
[00:05:05] pvp vẫn được xử lý xong hết rồi đúng
[00:05:08] không ạ Cứ chứ không không nói chuyện
[00:05:11] kiểu đang vừa cốt vừa kết hợp tiêu đi về
[00:05:11] Isaac
[00:05:13] à à
[00:05:18] à Hôm nay thì các bạn xem đấy Hôm nay
[00:05:20] mình sẽ
[00:05:23] đầu tiên là sẽ dùng mua đồ mô đây chắc
[00:05:26] là có can thiệp của boss chap 1 tí rồi
[00:05:29] mua đồ của Wechat sau đó thì kết hợp với
[00:05:34] kiểu Đăng nhập đăng ký ngồi Violet thằng
[00:05:37] cả bằng Serie A Jack các thứ
[00:05:37] à à
[00:05:41] từ trước đấy thì cho các bạn xem cái
[00:05:43] video này đã nhé
[00:05:46] ạ Bây giờ vẫn đang thời gian tâm sự mà
[00:05:48] nó ngoại chưa tìm ra học bộ đề thi Tự
[00:05:51] tập bớt cái này
[00:06:03] à à
[00:06:03] Ừ
[00:06:03] [âm nhạc]
[00:06:06] hihi
[00:06:08] resort
[00:06:38] Hihi
[00:06:43] resort Do you love and to All For One is
[00:06:46] well and one in parasyte Anime Princess
[00:06:49] như thế nào free Token implemented for
[00:06:54] the People all died inbox jakeman
[00:06:57] depends on the last Minutes people
[00:07:01] centre cancel quái big heart was getting
[00:07:05] all three rivers are you anh biết nó cho
[00:07:08] tao con x in Everything from free Games
[00:07:13] to People speak inquiry and use Walls
[00:07:16] are you What you people that like video
[00:07:19] Face turned out for the way that all
[00:07:23] that I can tell you care about What
[00:07:26] tomorrow Eva Nice stuff And rather that
[00:07:30] about you and deal with money for free
[00:07:31] with me
[00:07:57] thì các bạn thấy đúc kết từ cái video
[00:07:59] vừa rồi
[00:08:03] ở tại Hải ý của anh đấy à anh đấy à
[00:08:07] a z đầu miễn phí bởi vì a thấy à con
[00:08:09] người giờ là không trân trọng những cái
[00:08:10] gì ở miễn phí
[00:08:12] mình mới xem cái video là từ vừa nãy
[00:08:15] thôi mà mình thấy khá phù hợp với cửa
[00:08:17] thực ra là
[00:08:20] cái bài toán về tâm lý nó vẫn là tâm lý
[00:08:20] thôi
[00:08:25] anh nói thế Không phải à thôi ok bắt đầu
[00:08:28] từ bây giờ tôi sẽ thu phí học các bạn
[00:08:30] thì các bạn Trân trọng việc học của tôi
[00:08:34] hơn không phải như thế mà là
[00:08:37] mình đang muốn nói các bạn là để mời các
[00:08:37] bạn
[00:08:41] khi vượt qua được cái tâm bày tỏ tâm lý
[00:08:41] học
[00:08:45] vừa rồi để mà trân trọng những cái mà
[00:08:53] Ừ cái này không phải gửi mỗi khóa của
[00:08:57] mình mà khóa của mình thì K là mình à
[00:08:57] anh
[00:09:01] tím mình sẽ nói luôn rồi khó mình như
[00:09:03] thế nào Cảm nhận mình về khóa của mình
[00:09:07] nếu mà đấy Thì đại khái cái bài toán tâm
[00:09:10] lý học với mình thường mình thường hay
[00:09:13] thường anh nghĩ nó vào mình à nghĩa là
[00:09:15] nếu mà con người ở đó một vượt qua được
[00:09:18] những cái tâm lý học theo kiểu là tâm lý
[00:09:22] đám đông này tâm lý đảo ngược này để có
[00:09:24] rất nhiều cái mà Mấy ông vượt qua được
[00:09:27] một cái đấy nếu không sẽ gần như là
[00:09:29] trưởng thành này và suy nghĩ bằng một
[00:09:32] cái đầu lạnh và trở thành con người nói
[00:09:34] chung là làm chủ được
[00:09:37] Ê mấy ông của bé ông mà đọc về tâm lý
[00:09:39] học người không dễ thấy có rất nhiều cái
[00:09:42] nhà tâm lý học và theo kiểu là nó chi
[00:09:44] phối con người khác
[00:09:46] em thậm chí ở đôi khi là tôi áp dụng tâm
[00:09:47] lý học với mấy ông em mày không biết rồi
[00:09:52] thì nếu mấy ông mà nhận ra được điều đấy
[00:09:55] cho nó giống kiểu thôi miên kể về ông
[00:09:59] làm kẹo thức tỉnh khỏi cái đấy thế chẳng
[00:10:02] sẽ trở thành con người thì gì đó ngoại
[00:10:04] gọi là
[00:10:04] à à
[00:10:08] Mỹ Tâm bất dịch giữa dòng dòng đời à
[00:10:12] dòng đời số đề quyền sử rồi
[00:10:15] tắt Tâm bất biến giữa dòng đời vạn biến
[00:10:18] cái cảnh như thế ế
[00:10:18] à
[00:10:27] Em thích heo là về khóa học của mình cảm
[00:10:35] nhà mình gần đây thì da mình có
[00:10:37] em có gặp
[00:10:41] phải bạn tự nhiên là mình gặp vài bạn à
[00:10:41] Ở
[00:10:45] Ừ tự nhiên bạn để ở ngoài đời sau đó thì
[00:10:46] mình
[00:10:49] khi mình về mình xem cho anh trang cá
[00:10:52] nhân thì hóa ra bạn thấy thành là hot
[00:10:56] Tik Tok cơ này rồi hot youtuber này mình
[00:11:00] cảm thấy à Gọi bây giờ mình mình à
[00:11:00] ở
[00:11:04] đời mình thấy mình nhỏ bé kinh khủng khi
[00:11:05] mà Kìa
[00:11:08] mình từng nghĩ mình to tát sau một vài
[00:11:08] người
[00:11:14] ex2 ở xung quanh tôi như thế cho anh khi
[00:11:15] đưa thấy
[00:11:18] nhiều tích nhiều Tik Tok cơ kinh khủng
[00:11:21] nghỉ ở dưới Super kinh khủng người lượng
[00:11:24] người theo dõi khùng
[00:11:27] A và tự nhiên là họ đăng những cái chết
[00:11:29] rồi tôi không nói việc Những cái ông mới
[00:11:31] băng rất ngắn ý mà được nhiều người theo
[00:11:34] dõi nhé Thì
[00:11:38] anh đã tương tự như thế thì về cả những
[00:11:40] thầy cô mà
[00:11:43] được nhiều người theo dõi
[00:11:46] khi tôi cảm thấy kiểu dạng mà tôi khá
[00:11:48] nhỏ bé cho những người ấy
[00:11:51] khi tôi cũng tự tin chứ nhưng mà tôi
[00:11:52] nghĩ nữa à
[00:11:57] Ừ để mà để mà được nhưng hỏi thì ra là
[00:11:59] họ chưa cả họ làm
[00:12:01] anh theo kiểu thứ nhất là họ đấy công
[00:12:03] việc của họ rồi Họ biến đấy công việc
[00:12:06] của họ rồi Nghĩa họ dành toàn bộ thời
[00:12:10] gian nó nó chăm chút cho nó và à
[00:12:14] Anh làm tài liệu soạn giáo án chỉnh sửa
[00:12:17] video vân vân vân lên lên trong kế hoạch
[00:12:19] của rất là chi tiết tỉ mỉ cho tất cả
[00:12:22] từng từng người video từng nội dung của
[00:12:25] họ còn mình thì
[00:12:28] Ừ mình thì thực ra là mình vẫn đang dạy
[00:12:30] các bạn đã theo
[00:12:33] không hẳn là theo cảm hứng bởi vì mình
[00:12:35] có kinh nghiệm rồi mình có kinh nghiệm
[00:12:38] và kiểu
[00:12:40] cho mình hình như mình chỉ có kinh
[00:12:42] nghiệm về kết hợp với cả
[00:12:46] sự ứng biến chứ không có chứ không có
[00:12:49] kiểu dạng mà lên kế hoạch một cách chi
[00:12:51] tiết cũng như là
[00:12:54] mình không có đủ thời gian để mà chăm
[00:12:56] chút cho tất cả video
[00:12:58] cho các thứ tưởng là miếng thời gian
[00:13:01] chỉnh sửa video hay là các thứ thứ
[00:13:04] Ừ tí được ca chính cái thời chính cái à
[00:13:08] những những cái mình bỏ ra không bằng họ
[00:13:10] nên là thứ ra mình cũng không thể là
[00:13:13] mong đợi như họ được đến hình nhá giống
[00:13:16] như là cái á
[00:13:18] anh Fanpage của tôi trả lại tôi đang
[00:13:21] nghĩ việc à Tôi từng nói Tôi sẽ thỉnh
[00:13:24] thoảng đang ảnh hay nhạc hay gì đó Những
[00:13:27] cái sở thích của tôi chẳng ạ chia sẻ lên
[00:13:28] mọi người
[00:13:30] nhận ra hình như là mọi người Nếu là sử
[00:13:33] mọi người thấy cậu mọi người thấy thì
[00:13:36] chắc chỉ thích thôi chứ chắc là họ đã
[00:13:40] kiểu chia sẻ nó bàn tán thì nó
[00:13:44] Ừ nó khác với trâu Giả sử giáo xứ như là
[00:13:47] bây giờ một sân công nghệ Chắc là anh
[00:13:49] tôi đi Có dạo đi
[00:13:49] Ừ
[00:13:55] anh đây đã xây đủ đồ tiếng tăm và độ nói
[00:13:58] chung ơi hình tượng đủ lâu rồi để mà khi
[00:14:00] người ta một cái gì đó rất nhiều người
[00:14:02] muốn chia sẻ nó có nhiều người sẽ bình
[00:14:06] luận vào trong đấy ví dụ ở già ý rồi nhé
[00:14:08] đó là
[00:14:11] có một bài giả sử là một bài Tôi đang
[00:14:13] nghĩ sẽ toàn người chỉ có ba mấy người
[00:14:16] lại thích Thôi chẳng ạ ờ ờ còn một bài
[00:14:18] người đang thì sẽ là đến
[00:14:23] hướng để gấp 10 lần nên là ít và 300 là
[00:14:26] ạ trạng 300 đấy sẽ do tâm mấy mấy người
[00:14:30] bình luận sau đó một hoặc hai người hay
[00:14:32] lời chia sẻ thôi
[00:14:37] em thiệt thế Cũng là nhiều rồi ngoan ạ
[00:14:37] Ừ
[00:14:42] nhưng mà họ là họ đầu tư thực sự vào tất
[00:14:44] cả những cái đấy thế nên là nội dung của
[00:14:46] họ chất lượng người ta thích tương tác
[00:14:49] những cái đấy còn bây giờ tôi mà đăng
[00:14:50] những cái
[00:14:54] lên mà không Không có đầu tư thì đơn
[00:14:56] giản Cái này hay này mấy ông nghe đi em
[00:14:59] ạ Mấy ông cha gì vào là thích mấy ông
[00:15:00] nghe thôi
[00:15:03] em Nếu người không biết còn không muốn
[00:15:07] nghe Tiến thích thôi cho động viên
[00:15:09] Ừ cái thì
[00:15:12] Ừ thôi Tôi nghĩ là chắc là tôi khi mà có
[00:15:15] thời gian tới sẽ vậy cho chuốt rất nhiều
[00:15:19] cái fanpage đấy tôi Cha tôi sẽ phải theo
[00:15:37] có tư duy của em kém em chỉ chịu khó thì
[00:15:39] có theo học lập trình được không Cái này
[00:15:42] mình từng nói với sinh viên mình rồi đó
[00:15:42] là
[00:15:47] ngành đạo thế thôi Ngày nào cũng
[00:15:50] Nếu mà bạn thông minh thì cứ trả mà bạn
[00:15:55] sẽ đi nhanh hơn nhưng mà nó hơi bị cũng
[00:15:57] hơi bị ngược so với ngày này không mấy
[00:15:59] ngày khác nào nhá những ngày ngày nó sẽ
[00:16:02] bị lừa cái điểm có một sự thật đó Chính
[00:16:05] như bạn cái về đi hay bạn nói nói em
[00:16:08] chịu khó cái Chịu khó mấy là cái yếu tố
[00:16:08] cần
[00:16:13] chỉ cần ở trong cái ngành Công nghệ
[00:16:16] thông tin này ít nhất như thế cái thông
[00:16:17] minh không phải là yếu tố đủ không phải
[00:16:20] là số cần nói chỉ yếu tố để khiến cho
[00:16:24] chúng ta tiến nhanh hơn nhưng mà chính
[00:16:25] vì cái tiến nhanh hơn đấy
[00:16:25] sẽ
[00:16:30] không tốt ở trong cái ngành công nghệ
[00:16:33] tin này lắm Tại sao bởi vì nhé tôi từng
[00:16:36] quen khá như ông giỏi Ừ ông ấy học Công
[00:16:39] nghệ pin có nhé sau đó thì ông ấy học
[00:16:43] một thời gian ông ấy thấy thực ra để mà
[00:16:45] nhiều nhà ông giỏi đấy nhiều người còn
[00:16:50] Hàn và chất nữa và thực sự thì theo
[00:16:51] ngành Công nghệ thông tin này
[00:16:54] anh không khiến các bạn giàu nhanh được
[00:16:58] làm giàu nhanh nhỉ ra một à Thì cướp
[00:17:02] ngân hàng nghĩa cước từ
[00:17:05] người khác họ hay làm gì đó Phi Pháp 3
[00:17:11] là nhân kinh doanh đấy thì thì dùng anh
[00:17:13] được chứ làm công nghệ thông tin về cơ
[00:17:16] bản thì vẫn à làm công ăn lương thì
[00:17:19] không thể giàu nhanh được chứ Khi ông tự
[00:17:22] mở Sharp cái gì đó vẫn kinh doanh nhân
[00:17:23] thành ra là
[00:17:26] những bạn thông minh theo ngành này Ừ họ
[00:17:29] tính nhanh đấy nhưng họ sĩ nhanh trám và
[00:17:32] không không có không thỏa mãn được nhu
[00:17:34] cầu làm giàu bạn ấy lại thứ nhất thứ hai
[00:17:34] là
[00:17:39] ngành cũng không tin này dù tin nhanh
[00:17:41] chắc nữa vẫn phải học hỏi rất nhiều
[00:17:43] Anh khiến cho kiểu bạn đấy cũng dễ bị
[00:17:47] lạc và đứng yên à Không ai có thể cốt mà
[00:17:49] không ra bất được người thông minh hai
[00:17:52] người Người thông minh thì sẽ ra bất
[00:17:55] thông minh khi con người kém thì sẽ ra
[00:17:58] bất kém bất kém ở bếp bớt thông minh nữa
[00:18:00] là gì bớt mức thông minh lắm chỉ ở rất
[00:18:04] khó để mà phát hiện ra cái bớt đấy Nó
[00:18:07] kiểu phải giữa cao siêu thì mới nhận ra
[00:18:07] được
[00:18:11] tội từng nói với ông đó là khi mà em
[00:18:13] đang sản xuất đấy mấy ông đừng có cốt
[00:18:15] Bởi vì khi mà mày ông sản xuất nó cũng
[00:18:18] sẽ cốt vẫn cố tình thôi nhưng mà sẽ ra
[00:18:21] được những quả bất mà phải các bạn phải
[00:18:23] đền cái ngưỡng thông minh Gấp đôi thì
[00:18:26] các bạn mình có thể mới sửa một cái bớt
[00:18:30] đấy Anh thành ra là các bạn tự làm khó
[00:18:31] bản thân để nó gọn thông minh rồi các
[00:18:33] bạn xảy ra gia đình những cái bớt mà
[00:18:35] không ai sợ được khiến chính các bạn
[00:18:36] không sửa được
[00:18:40] nghe với là nó thế là là chính vì cái
[00:18:41] nản đấy
[00:18:43] thì người thông minh ta lại khó vượt qua
[00:18:46] nếu và sự người đã không chịu khó họ
[00:18:48] nghĩ là họ giỏi rồi Tại sao họ lại phải
[00:18:53] chịu khó vất vả nhớ thế họ sẽ bỏ họ sẽ
[00:18:56] chuyển ngay và họ sẽ không tốt nữa họ sẽ
[00:18:58] nhảy dàng cái kiểu cũng công tin nhưng
[00:19:02] mà sẽ lên làm leader lên làm gì đó khác
[00:19:04] đi tiểu thường là nó nhảy sang bên Phân
[00:19:07] tích phân tích Thay vì cô ấy thì sẽ ổn
[00:19:10] hơn bởi vì không tạo ra bất gì thế ạ Đấy
[00:19:14] con người lập trình viên mình ở chúng ta
[00:19:18] nên kiểu chịu khó hiểu Chịu khó học hỏi
[00:19:22] chứ có thay đổi khi mà khách hàng hay
[00:19:25] sếp đòi thay đổi chịu khó thay đổi công
[00:19:27] nghệ khi mà giờ sử ngôn ngữ là Giang bị
[00:19:30] lỗi thời rồi xong rồi học hỏi thêm nhiều
[00:19:32] cái vân vân
[00:19:35] em học hỏi cả cốt người khác họ cảnh hò
[00:19:38] cái sữa bắp Vân rất nhiều thứ để học hỏi
[00:19:41] đến bây giờ đến bản thân tôi rồi
[00:19:44] tôi ngoài việc để cốt chạy Tôi còn phải
[00:19:47] học cách thì tôi như trở lại ạ Đấy hàng
[00:19:49] ra là
[00:19:53] Ừ cái yếu tố cần trong ngành này lại là
[00:19:56] kiên nhẫn chịu khó chứ không phải là
[00:19:57] thông minh
[00:19:59] Ồ thông minh
[00:20:01] Ừ tôi thấy nó sẽ biến thành nhược điểm
[00:20:04] như tôi đã nói tôi không biết người tham
[00:20:06] quan điểm này là như là đối với tôi nó
[00:20:06] thế
[00:20:09] ở cốt nhiều các bạn sẽ tự thấy mình
[00:20:11] thông minh dần đây
[00:20:13] anh không Không cần phải so với kia hả
[00:20:16] Sao bạn thân thôi tôi toàn thế đó là cư
[00:20:20] do bạn thân mình mình đã làm một bản sao
[00:20:24] tốt hơn so với mình cách đây một năm thì
[00:20:26] nửa năm hay là thậm chí vài tháng trước
[00:20:29] chưa thế được
[00:20:32] Ừ đúng ạ mức lương Các bạn đã được tăng
[00:20:36] lên chưa Đừng nói Vân là như thế Mình đã
[00:20:39] tiến bộ hơn rồi chồng ạ
[00:20:42] em không ăn sò người khác người khác có
[00:20:44] thể vừa mới đi làm lương người ta thể
[00:20:47] đến nghìn đô con nhà người ta không ạ Ừ
[00:20:50] thì mình cũng tự đi đấy nhưng mà mình
[00:20:52] không vì thế mà thôi Mình không làm ngày
[00:20:54] nữa mình sẽ chỉ làm ngày làm 1 phát
[00:20:56] lương mình nghìn đô dùng nó làm đi bây
[00:21:00] giờ đấy không ạ thì mình mình chọn chọn
[00:21:02] một cái gì đó một mình cảm thấy à
[00:21:06] Ừ thứ nhất là nó có tiềm năng thứ hai là
[00:21:09] nhà mình có thể theo được
[00:21:11] anh có thể theo được khác với việc có
[00:21:13] thể kéo ngang có thể theo được người
[00:21:17] khác đứng ạ Có thể theo được có thể học
[00:21:17] được
[00:21:21] sống rồi đừng nghĩ việc là có thể có
[00:21:25] đừng lui rất nhiều hối hội tôi Tôi từng
[00:21:28] nói à
[00:21:32] Ê hồi trước ở lớp tôi ăn nhiều là tỷ lệ
[00:21:36] đi làm cao và các bạn đấy lúc mới vào
[00:21:40] thì bạn đấy là từ ở quê lên bạn đấy chưa
[00:21:42] từng động của máy tính mà đã thế mà đã
[00:21:45] nhảy sang học lập trình rồi Cái đấy thì
[00:21:48] cái là nhiều người sẽ buồn cười kìa kiểu
[00:21:50] còn chưa biết cách mở máy tính như nào
[00:21:53] chứ chưa nhìn thấy cái bàn phím Ờ phải
[00:21:57] gõ luôn có cả nhìn cực ngồi quỳ xuống
[00:22:01] bàn phím mì gõ từng phím một đấy nhé bạn
[00:22:08] a&amp;d sẽ hiểu
[00:22:11] mà tốn hết thời gian và tiền bạc cho
[00:22:14] việc học này rồi bạn sẽ treo đứng cung
[00:22:17] bạn sẽ không có suy nghĩ việc nào lại
[00:22:21] chịu khó bạn có vấn đề gì bạn sẽ cố
[00:22:23] Ừ nó khác mày nhiều người bây giờ có
[00:22:26] điều kiện họ lại kiểng
[00:22:30] Ừ cố tìm cái gì gì đó mà kiểu vừa nhàn
[00:22:33] vừa vân vân gì đó rất nhiều cái thôi có
[00:22:35] mông lung nữa nhiều lựa chọn thành ra là
[00:22:37] không chú tâm làm à Một cái gì đều có
[00:22:38] thể cả
[00:22:40] vì thế quá sai
[00:22:43] à Tôi nghĩ à tuổi trẻ đúng ở nên có trải
[00:22:45] nghiệm nhiều
[00:22:47] Ừ nhưng mà
[00:22:50] Để mình chọn cái gì mình phải làm cái
[00:22:53] đấy Có tâm với nó vợ tôi nói với tôi
[00:22:57] từng đi làm bồi bàn ở các thứ thứ
[00:23:00] Ừ tôi vẫn hoàn toàn hết đặt hết tâm
[00:23:01] huyết vào nó
[00:23:04] a cho đến khi đến cái ngưỡng mà mình
[00:23:07] không hỏi thêm gì mình nghĩ là kỹ năng
[00:23:09] của mình học hỏi chị đến được đến lần
[00:23:11] này thôi Và mình thấy là thực ra nó
[00:23:13] không phải phù hợp với mình thì mình bỏ
[00:23:14] không sao cả
[00:23:17] Vì vậy tôi chả còn gì hết
[00:23:34] ok không Mày tâm sự thế được rồi
[00:23:34] ừ ừ
[00:23:48] các bạn em tiến tiến nhanh học tùm lum
[00:23:50] mấy cái công nghệ đúng không còn em thì
[00:23:54] chăm học mấy cái cũ để cho kẹo để luyện
[00:23:57] đúng không
[00:23:57] ờ ờ
[00:24:01] Ừ cái này thì lại là bài toán mà mình
[00:24:04] từng nói về cái dân công nghệ nó có thể
[00:24:05] hai hướng
[00:24:09] anh giống như hướng mùa hướng hướng trên
[00:24:11] sau thì rất là tốt nhưng cũng có thể Mùi
[00:24:14] hướng ở hướng cậu ạ à hướng toàn diện
[00:24:16] thế là cái gì không biết
[00:24:19] Ừ cái hướng toàn diện thở ra là cũng
[00:24:22] được nhưng mà nhưng mà đến và các bạn
[00:24:24] chuyên sâu được thì sẽ trả lương các bạn
[00:24:27] sẽ cao hơn còn nhưng mà hướng toàn diện
[00:24:30] thì giống kiểu đa-zi-năng như Hiện tại
[00:24:33] mình mình thì nhảy sạm phần này mình làm
[00:24:36] nhảy sang cả bên urquell rồi mình làm
[00:24:39] thì rất nhiều công ty cũng rất thích
[00:24:41] người đấy và người ấy sẽ hiểu được sự
[00:24:44] chặng cũng được coi trọng đấy
[00:24:47] anh nói chung là tùy tình huống đấy các
[00:24:50] bạn cảm thấy cái nào phù hợp thôi hơn
[00:24:53] thôi cả hai cách đều được không sao cả
[00:24:57] chuyên trên được càng tốt nhưng mà nhưng
[00:24:59] mà đừng có kiểu chuyên về cái cũng chỉ
[00:25:01] là không học được cái mới không học được
[00:25:05] cái mới lại khác nhé Bấm gì ông cụ ông
[00:25:07] chỉ học được một ngôn ngữ sản không nghe
[00:25:09] học được ngôn ngữ khác nhưng khác Còn
[00:25:12] đây là chúa khắp chán chê xong cái ngôn
[00:25:15] ngữ mất tận kịp thời sửa ông Bất Tận 5
[00:25:18] hình 6 năm để chuyên pp ạ Đấy sau đó thì
[00:25:21] bây giờ công ty mà
[00:25:24] bảo các bạn để sang Java ra Suite các
[00:25:27] bạn Học lại từ đầu thì vẫn được không
[00:25:30] sao cả Chẳng sao cả bởi vì các bạn đã có
[00:25:32] nền tảng của ngôn ngữ lập trình các bạn
[00:25:35] hiểu rõ Toàn bộ thế nào về lập trình rồi
[00:25:38] thì bạn nhảy xa người khác mà vẫn vẫn dễ
[00:25:40] rồi công nghệ mới ở đây nó không có gì
[00:25:43] to tát ghê gớm mà nó sẽ chỉ có vài cái
[00:25:45] thay đổi vài cái từ ngôn ngữ sẽ có thế
[00:25:47] mạnh riêng với Vân
[00:25:49] em có bạn chỉ cần
[00:26:01] Ừ
[00:26:01] ok
[00:26:06] tiếp theo câu hỏi
[00:26:10] anh ở đây có hai câu hỏi ở
[00:26:13] có một câu hỏi này à
[00:26:17] ở đó là bạn hôm trước bạn ấy có hỏi cái
[00:26:20] việc là các bạn nhớ về cái đặt đơn không
[00:26:22] ạ đặt hàng ạ
[00:26:26] em sợ nhiều bạn quên rồi à
[00:26:29] ở đầu tiên thì các bạn Nếu có thể hóa
[00:26:33] đơn thì mình sẽ có cái bảng
[00:27:00] thì mình sẽ có 23 là bạn hóa đơn và linh
[00:27:03] chi tiết và bảo hóa đơn của mình sẽ có
[00:27:06] cột mã tự động tăng và bảo hóa đơn chi
[00:27:10] tiết sẽ dựa theo lấy cái cột ID đấy cột
[00:27:14] mã đấy Ở trong này về mà thêm mã sản
[00:27:17] phẩm để mà để mà kiểu mình biết được là
[00:27:20] đơn đấy đã đặt những gì đó ngoại thì hôm
[00:27:22] trước là có bạn nói về cái vụ trường hợp
[00:27:25] khí hữu mà mình nói bây giờ xử Giả sử
[00:27:27] đây nhá đó là
[00:27:31] ở đầu tiên thì khi mình Insert vào trong
[00:27:34] bão đồ bảng hóa đơn đấy mà để mã tự động
[00:27:38] tăng nữa ông ạ thì vì là mã tự động bang
[00:27:43] Nhưng khi mình lấy mắc mắt ID
[00:27:46] em lấy cái mã lớn nhất từ cái bảo hóa
[00:27:50] đơn thì có trường hợp có thể xảy ra đây
[00:27:53] đó lại Nếu giả sử mà cùng ấn thanh toán
[00:27:57] cùng một lúc thì thì cái mã hoặc mã lớn
[00:28:00] nhất đấy thì nó sẽ là do sử là
[00:28:04] là hang Hai người cùng ấn thanh toán
[00:28:07] cùng một lúc thì cái mã hóa đơn lớn nhất
[00:28:10] nó sẽ ra hai hạng của hai người nó sẽ
[00:28:14] giống hệt nhau và nó sẽ đặt vào trong
[00:28:17] hóa đơn chi tiết vào một đơn thôi nghĩa
[00:28:18] Dồn hết toàn bộ sản phẩm bằng một đơn
[00:28:20] chứ còn đơn còn lại thì sẽ không có sản
[00:28:23] phẩm nào ra thế sau đó ông ạ
[00:28:26] nên nó hôm trước mình đã bảo là mình có
[00:28:29] thể our customer ID nghĩa là làm gì là
[00:28:34] mình mình sẽ hiểu theo khách hàng hiện
[00:28:35] đại có thể kéo khách hàng bởi vì thường
[00:28:38] mà khách hàng sẽ không nói chuyện là sẽ
[00:28:42] hiếm sẽ hiếm việc đăng nhập vào để cùng
[00:28:45] Đạt đơn cùng một lúc Ừ nhưng mà đấy Gọi
[00:28:46] lại khiến mình thực ra vẫn có thể xảy ra
[00:28:49] vụ này vẫn thấy xảy ra vụ này đó là ăn
[00:28:51] chỉ là
[00:28:55] em ăn gia sư tử kéo hứng lên đi Biết đâu
[00:28:58] đấy nó mở 2 Tab mà nó thanh toán hai cái
[00:29:02] đơn đấy nó ngoại thì điều đấy vẫn thể
[00:29:04] rửa ra thế là mấy giờ nhăn việc là đơn
[00:29:07] sản phẩm của đơn này nhảy vợ đơn kia thì
[00:29:09] chỉ có thể là đừng nói cho mã tự động
[00:29:11] tăng nữa
[00:29:15] cô đơn giản đấy thôi mình sẽ tự tự đầu
[00:29:18] tiên là mình sẽ lấy mã lợn nhất từ trong
[00:29:20] bào hóa đơn theo khách hàng này chẳng
[00:29:22] hạn hay là không không còn thiếu khách
[00:29:24] hàng ở đó
[00:29:27] ạ sau đó thì mình sẽ làm gì mình sẽ Mình
[00:29:31] nãy tự tự tăng cái mã lớn nhất để tăng
[00:29:33] lên một rồi Mình in rất là trong hóa đơn
[00:29:36] và Insert vào trong cả họ hóa đơn chi
[00:29:40] tiết thì bởi vì mã đấy nó cho cả hai bà
[00:29:44] cùng một lúc mới này ra đơn sản phẩm của
[00:29:45] đơn đấy nó chắc chắn sẽ thuộc đơn đấy
[00:29:48] rồi nó sẽ có những điểm là khi mà giả sử
[00:29:55] anh Bởi vì giống như tôi vừa nói là bởi
[00:29:57] mã không tự động tăng lên có thể việc mã
[00:29:59] có thể trùng đúng không ạ Nhưng mà nếu
[00:30:01] mà bị chồng như thế thì ông chỉ việc và
[00:30:05] kiểm tra nếu mà khi mày rớt bị máy queo
[00:30:09] Euro tất cả bị lỗi thì ông Tăng ông chạy
[00:30:11] vòng lặp ông chạy vòng lặp đấy để tăng
[00:30:14] nó lên 1 rồi in rớt lại xem có được
[00:30:17] không để pin rất lạ vẫn không được thì
[00:30:19] lại tăng lên một tiếp tôi sẽ như thế cho
[00:30:21] đến khi in sẽ được thì thôi thường là
[00:30:23] thực ra là không nói chuyện mà chạy vòng
[00:30:29] lặp nó chạy chục lần đâu vì mắc mắt ID
[00:30:31] theo khách hàng mà khách hàng làm sao
[00:30:33] đọc được chục đơn cùng một lúc mà bị
[00:30:36] trùng liên tục được không ạ Cái gần như
[00:30:40] là mã của ông sẽ không sẽ hiểu
[00:30:42] em luôn là duy nhất và phù hợp với
[00:30:45] Insert được vào cả hai bà không nói
[00:30:48] chuyện là sản phẩm của đơn lại nhảy vào
[00:30:55] cho tôi Tôi không nói tôi tôi nói trai
[00:30:57] thế tôi không cốt ở đây vì thực ra là
[00:31:00] cái bài toán đây nó hi hữu
[00:31:00] à à
[00:31:07] Ừ mình gì à Không biết cái hàm Insert ID
[00:31:11] kia nhưng hình như là cái đấy là Insert
[00:31:14] rồi lấy đi thì phải nhớ Thế
[00:31:17] mình mình chưa thử mình chưa thử vụ đấy
[00:31:21] mình chưa được rồi đâu nha Nhưng mà nếu
[00:31:23] mà giờ sự ý sẽ lấy được cái điên nữa
[00:31:26] thủng ngoại thì cái hàng họ
[00:31:29] cũng không đúng lắm không đúng lắm vì
[00:31:31] vậy đúng không
[00:31:34] có ai ý ông à khi mà yên xuất thế này
[00:31:37] sao lấy được ai đi để mà cho đấy á
[00:31:42] nếu thể nếu làm thế được thì ổn in xuất
[00:31:43] một phát mà lấy được cái đi luôn thì ổn
[00:31:46] đỡ phải dùng xe xmax này cho Tránh
[00:31:49] trường hợp bị nhầm nữa được cái đấy được
[00:31:51] nếu mà làm được như thế
[00:31:55] a Lazio thấy đồ ăn hay giữ làm được trò
[00:31:57] đấy à
[00:32:00] về con không gì ông Tống hết toàn bộ cái
[00:32:02] này vào trong một trang sân nghĩa là chỉ
[00:32:07] là cái cái truy vấn Insert là selec sẽ
[00:32:11] xảy ra ngày ngày sau nhau để tránh việc
[00:32:14] là có thằng khác can thiệp vào lúc mà
[00:32:16] mình đang sẽ lách thì tự nhiên hoặc rất
[00:32:19] vào nó sẽ Anh xin lỗi không ạ Các bạn
[00:32:22] tống hết vào trong một trang xuân Có ai
[00:32:25] có khả có một vài cách là như thế
[00:32:25] Ừ ok
[00:32:31] tiếp theo đó là hôm trước và mình dùng
[00:32:34] recovery nhưng mà dùng dạng cdn Nếu mà
[00:32:38] bạn nào chưa biết trả lại với ông nha gg
[00:32:40] này à
[00:32:43] Ừ thế nào là CD nào thì đây hôm trước là
[00:32:46] mình có để đường link như này và mấy ông
[00:32:48] thấy là đây là người đến hẳn của trang
[00:32:51] web khác để mà lấy được thốt ra Switch
[00:32:54] nói kiểu như này đúng ạ thì cái này gọi
[00:32:58] là cdn chắc là sao tôi được ra tôi vẫn
[00:33:00] chưa đọc đầy đủ tất là khái niệm của Cn
[00:33:03] nhá Tối tôi nhớ mang máng thôi nhá Thử
[00:33:05] nó lại xem không biết đúng hay sai nữa
[00:33:09] Nhưng theo như tôi nhớ nó là
[00:33:12] 3cl nó là thứ nhất là đương nhiên là
[00:33:15] Linh đến một cái trang web khác thứ 2
[00:33:17] xong web phải lên nó là một con server
[00:33:22] nó còn server khác và server thường nó
[00:33:23] giống như trong các bình thường nó là
[00:33:27] kiểu nó sẽ on 24 để mà ông hoàn toàn hẹn
[00:33:34] bài hát Mất tiền lắm alo alo alo em bé
[00:33:38] quá anh alo
[00:33:42] thì cái á thì cái
[00:33:46] Ừ cái cái này thứ nhất nó on 2T tư này
[00:33:49] để mà để mấy ông có thể
[00:33:53] luôn luôn truy cập được cái cái thư viện
[00:33:56] đấy Vậy thứ nhất thứ hai là cái con
[00:33:59] Server này đôi khi đôi khi nhé Nó là
[00:34:01] được cung cấp bởi dịch vụ mạng theo kiểu
[00:34:04] là nó ở khá nhiều khá nhiều quốc gia
[00:34:05] thậm chí
[00:34:08] ví dụ là ông nhìn như thế này nhưng thực
[00:34:12] ra nó thể Linh đến tận mấy con server và
[00:34:15] quốc gia khác nhau giờ sửa có ở Châu Á
[00:34:17] có một con ở Châu Mỹ có một con hơn đại
[00:34:19] hạn đại khái như thế
[00:34:22] Ừ để để mà nó giống kiểu thằng Google ấy
[00:34:24] để mà khi mà ông
[00:34:27] sau khi khi mà ông gọi đến cái thằng này
[00:34:31] nó sẽ tìm con server gần nhất gần nhất
[00:34:32] để mà
[00:34:36] lấy lấy cái cái này về nên về các bạn
[00:34:39] thì nó lại khá là nhanh nó khóa nhanh và
[00:34:43] đôi khi đôi khi nhá Tôi nhờ chính ra đó
[00:34:46] là tới khi mà ông trẻ như này còn nhanh
[00:34:49] hơn việc của ông ông cho luôn cả cái thư
[00:34:52] viện này ở trên con server của chính ông
[00:34:54] Ừ ông loát ở trên trình server của ông
[00:34:56] Tại sao
[00:34:58] anh Bởi vì khi mà người dùng vào mùa
[00:35:00] trong máy vào đó thì khi mà có một cái
[00:35:03] đường có mấy cái kiểu Swift chèn thêm
[00:35:06] hay không phải mở Script mà Style hay gì
[00:35:09] gì đó cho thêm thì người dùng phải loạt
[00:35:12] cái đấy từ chính con server đấy Về mà
[00:35:15] con server gái của ông là sự server
[00:35:19] Ừ đấy của ông Đạt ở tít tận Mỹ Xa Xôi em
[00:35:21] ạ Đấy xong rồi
[00:35:24] Ừ thì người dùng phải tải tất cả những
[00:35:26] cái đấy cái cái trình duyệt người dùng
[00:35:28] hai tay rất là đúng lấy về từ bên Mỹ về
[00:35:32] thì nếu mà giả sử mà cái con cdn à Ông
[00:35:36] đúng theo toa cbn mà còn con server CN
[00:35:39] đấy nó lại ở gần Việt Nam hơn thì nó sẽ
[00:35:41] được lót nhanh hơn thì thôi
[00:35:44] Ừ thế này là đấy tác dụng của Cn nhất
[00:35:47] này Nó sẽ kiểu nó sẽ hỗ trợ các bạn đôi
[00:35:50] khi là nó sẽ mát nhanh sự thứ và Thường
[00:35:53] thường mấy thì nó vẫn có thể truy cập 24
[00:35:56] tư nhưng mà đã từng có lần kìa hành
[00:35:59] chính thằng seri này Thế nhà cung cấp nó
[00:36:01] bị sập hội lần đấy Chẳng ngại thì toàn
[00:36:05] bộ trang web làm à mà đang đang dùng CD
[00:36:08] nào để cái thằng Ri mà chết nóng lạnh
[00:36:11] đấy đấy chứ và nhược điểm để nhược điểm
[00:36:13] có nghĩa là duy nhất của cái việc là
[00:36:22] chỉ mình cách lên máy người dùng
[00:36:25] 1000 cái vụ à
[00:36:28] bình thường là trình duyệt nó vẫn hỗ trợ
[00:36:31] mình cách mà khi mà mình nhúng file các
[00:36:33] bạn Nếu không ạ mình từng nói vụ mình
[00:36:35] phải cày cả tiện ích nghĩa cách này vì
[00:36:37] thường khi các bạn nhúng file ngoài vào
[00:36:40] thì trình duyệt đôi khi nó sẽ tự động
[00:36:42] cho các bạn một đấy hoặc gà mình có thể
[00:36:47] mình cũng có thể cốt để nó nó cậu ép nó
[00:36:50] kiểu nhớ mấy cái này đúng mình cái này
[00:36:53] mình nên cách lại gửi thường ạ Cái đương
[00:36:55] nhiên là cái file này về cơ bản thì nó
[00:36:57] là mi rồi nó vẫn nhẹ Nhưng mà thường là
[00:36:59] mình chả mơi Thay đổi cái này nữa anh ra
[00:37:01] là mình cách lại được thì càng tốt không
[00:37:04] ạ Ừ nếu mà mình lên kiểu tối ưu lại
[00:37:07] khiến cho trang web lót nhanh hơn và
[00:37:10] mình cách được cái gì thì cách không ạ
[00:37:10] à à
[00:37:16] Ừ
[00:37:20] ok Bây giờ thì mình sẽ đến bài bài hôm
[00:37:24] nay bài hôm nay thì sẽ là nhất là mua đồ
[00:37:28] các bạn tra cái từ ra luôn mua đồ
[00:37:28] à
[00:37:31] Hôm nay tôi phải trả lại mua đồ WeChat
[00:37:31] này
[00:37:36] mua đồ dự báo là sẽ kiểu như khi bấm vào
[00:37:39] thì sẽ hiển thị là một cái cái này thời
[00:37:41] cao cái à
[00:37:45] Ừ từ khóa của nó là có bắt cóc áp để
[00:37:47] hiển thị ra một cái ngõ pat nếu mà các
[00:37:49] bạn cha được ra nó sẽ hiển thị ra một
[00:37:52] cái kiểu giống như Plus một cái Hiển thị
[00:37:54] một cái thông báo nhưng mà trông còn xấu
[00:37:56] hơn mua đồ nó một dặm pháp Nhưng mà
[00:38:00] trong nó đẹp hơn Nó kiểu như hai đây ở
[00:38:02] đây nói rõ Này bác Windows này lại đúng
[00:38:04] không chồng nó đẹp hơn
[00:38:07] đề thi
[00:38:10] anh không không có thể tha tôi bảo mẹ em
[00:38:14] không được dùng búa chát Nhưng mà nếu mà
[00:38:16] tôi không muốn cốc chai các bạn mua đồ
[00:38:19] nên hai nha tôi sẽ
[00:38:22] bây giờ tôi sẽ cho phép mấy ông dùng bút
[00:38:24] chat nhưng mà chỉ được dùng mua đồ thôi
[00:38:27] không khó không được dùng à
[00:38:31] 3000 dùng không dùng Wechat cho tất cả
[00:38:39] thế hả Costa đẹp hơn tôi không biết mấy
[00:38:42] ông như nào như cốt tay sẽ của tôi sẽ tệ
[00:38:43] thì tôi sẽ
[00:38:46] dậy luôn làm thế ở đây à
[00:38:50] ở cái chỗ ở đây mấy ông thấy à Nó đã
[00:38:52] chèn thêm với cả gì Ghi Wechat cho con
[00:38:58] bú chat này nữa cái bút chat là gì thì
[00:39:00] nó là kiểu phê thuốc không phải thư viện
[00:39:04] nó Facebook xét để mà cốt sẽ nhanh hơn
[00:39:07] tối ưu hơn nhẹ và kiểu
[00:39:10] cho phù hợp với nói chung và mọi thiết
[00:39:15] bị ngon đẹp và còn có bút pháp rét nữa
[00:39:18] bootstrap cũng có gì hết để mà kiểu đây
[00:39:28] anh
[00:39:30] nói chung và bây giờ mình sẽ trên hết ba
[00:39:34] cái này về mở đâu mà chính mình mình
[00:39:35] đang muốn mình đang muốn làm như này nhá
[00:39:39] đó là à
[00:39:42] từ khi tôi vào cái trang này trở lại
[00:39:46] Ừ thì về tài năng suất này bây giờ xử
[00:39:49] tôi vẫn đăng nhập thì tôi thay vì kiểu
[00:39:50] nhảy sang cái trang đăng nghiệp kiểu như
[00:39:55] này như mình thì xấu thứ hai là
[00:39:57] tôi tôi muốn thị ra một cái
[00:40:01] một cái mua đồ đây bấm vào đăng nhập như
[00:40:04] thì em mua đồ đây để đỡ phải phải đi dạy
[00:40:06] lại cho em 10 cứ ấn đăng nhập này xử lý
[00:40:09] âm nhập thì hãy nhớ rằng file khác song
[00:40:11] điều hướng điều hướng đúng không ạ Tôi
[00:40:12] không muốn như thế thì nó nhập vào nhìn
[00:40:14] thấy một cửa sổ đây để tôi điền thông
[00:40:17] tin đăng nhập vào nó nghiệp xong thì nó
[00:40:20] cũng không điều hướng gì cả nó sẽ nó sẽ
[00:40:23] đóng với mua đồ đi vào đăng nhập hộ tôi
[00:40:26] đã hiểu thế bản trước là sẽ gọi Iraq lên
[00:40:28] là đăng nhập hộ cho mình này sau đó đi
[00:40:32] đổi lại cái ở đây là xin chào bạn a b c
[00:40:37] đối ngoại này có thể tha thứ
[00:40:39] Ừ nhưng mà trước khi làm ăn Nhật Nhưng
[00:40:42] mình phải làm đăng ký trước không ạ đăng
[00:40:45] ký đây mình sẽ còn kết hợp với cả và đến
[00:40:47] để kiểm tra việc mình đã Điền đúng hay
[00:40:51] sai gọi và tiền thì bây giờ xử đối bấm
[00:40:53] vào đăng ký thì cũng phải thì em cái mô
[00:40:55] rồi em ạ không ạ
[00:40:58] Ừ thì bây giờ đầu tiên à
[00:41:03] Đang ăn thì này mình sẽ tạm bỏ thẻ đi
[00:41:05] mình không không còn thấy a nữa
[00:41:05] thì
[00:41:11] mình sẽ bớt Tân làm nút là nút là nó
[00:41:18] Mình sẽ là
[00:41:21] Vì mình thấy ai đi được mà bữa tuần à Xa
[00:41:31] ở lại bấm mà hiểu là đăng ký không ạ
[00:41:31] à à
[00:41:37] A và đừng như là cái file này của tôi là
[00:41:39] phidex nhá đúng ạ Tôi sẽ viết vào trong
[00:41:40] file index
[00:41:40] chứ
[00:41:44] không phải biết là trong phải mày ngu
[00:41:46] rồi nhé Không Không Đừng có viết và file
[00:41:52] số tiền tôi chèn đoạn kia đã ngon Nó
[00:41:59] cho thịt gà tre này thì như bạn trước
[00:42:01] nói thích thì chè ở trên cùng cũng được
[00:42:04] chàng trai cùng nha được không sao cả
[00:42:08] a thường em như tội nói thịt link CS thì
[00:42:10] sẽ nên chèn thiên cung toàn bộ ra kết
[00:42:11] màn ở dưới
[00:42:14] nếu mà với các bạn được chứ cái đấy nó
[00:42:17] liên quan việc làm ở
[00:42:19] khi họ không ảnh hưởng lắm việc loát Vì
[00:42:22] kiểu chị sẽ được loa thôi nhưng mà
[00:42:25] nói chung là tùy gửi ra Kích thường tôi
[00:42:27] tôi ngỡ nó được khuyến cáo nên để ở dưới
[00:42:29] nhưng mà để trên này thời gian nó vẫn
[00:42:31] đút lót tạm thời tôi cứ tổng minh trên
[00:42:31] đi
[00:42:36] ở
[00:42:40] đầu tiên mình sẽ có đăng ký bấm vào thì
[00:42:44] đây sẽ có đoạn Script vào đây xử lý là
[00:42:51] có
[00:42:55] size up này click này
[00:42:55] sau
[00:43:00] khi nuốt được Bấm thì có điều gì sẽ xảy
[00:43:03] ra không ạ kia ông bà em Số điện em ạ
[00:43:03] Đấy
[00:43:09] Có thể đây bạn bắn chết ở đây thì
[00:43:13] thì nó sẽ cậu nó sẽ chích cờ nó sẽ nó sẽ
[00:43:17] cậu nó sẽ thấy nghiệm hotgirl tưởng
[00:43:20] chuẩn bị thơm từ này như nào nói chung
[00:43:23] và nó sẽ gọi để thăm mua đồ Có ai có ai
[00:43:23] đi
[00:43:27] đây có một cái đít quá đi mua đồ như này
[00:43:31] và sẽ nhìn chị ra đây cái đít như thế
[00:43:31] này
[00:43:37] tin tức là sao bây giờ Bây giờ nha
[00:43:39] Anh An ơi thế không cần phải đặt như này
[00:43:41] nữa quên lại không không không cần đặt
[00:43:45] ngay mình sẽ chỉ cần à Có cái nút
[00:43:47] à hay là nút này
[00:43:51] anh vào Thaco đấy là được ok ok
[00:43:55] em sửa lại tượng này tí
[00:43:58] anh sẽ gọi đến kém mua đồ của mình là
[00:43:59] mua đồ
[00:44:02] xay ép
[00:44:05] thế này này là được
[00:44:08] 3 cách lát này cho nút nó đẹp hơn thôi
[00:44:09] bỏ đi cũng được
[00:44:13] ở trong Sẽ Thôi nha này khi bấm mà thì
[00:44:17] nó sẽ kiểu gọi đến cái mua đồ này cái
[00:44:19] mua đồ này thì
[00:44:22] thì mình sẽ lấy ở đâu Mình sẽ
[00:44:26] nhà mình có thể chèn thêm cái mình sẽ in
[00:44:29] Plus luôn cái file đăng ký này
[00:44:32] a file Đăng Chí đây
[00:44:35] a ch play đúng không có phải đăng ký đây
[00:44:38] trẻ thiên thẳng vào tôi sẽ là
[00:44:41] sau khi khi mà đào khi không đăng nhập
[00:44:43] thì kiểu gì cũng chạy có mà mặc thì đây
[00:44:45] sẽ là
[00:44:48] hình ảnh Plus này
[00:44:48] ừ ừ
[00:44:55] A
[00:44:55] h.py
[00:45:00] vào trong cái file jsp này
[00:45:03] thì mình tặng xóa bên mình không cần
[00:45:06] HTML nữa vì bây giờ nó sẽ bản chất nó sẽ
[00:45:14] em có ai đi là
[00:45:16] mua đồ shop
[00:45:30] ở nhà mình sẽ phải chèn thêm một vài cái
[00:45:33] ở đây để mà ẩn lúc đầu sẽ ẩn cái đít mày
[00:45:35] đi còn nếu mà không ăn đi thì ông sẽ bị
[00:45:38] hiển thị ra như này nó sẽ bị hiển thị ra
[00:45:44] Ừ ừ như thế bỏ luôn cả thí sinh start ở
[00:45:51] từ lúc đầu tôi sẽ ẩn cái mô bản chất cái
[00:45:54] mua đồ ấy hồi trước tôi bị nhầm đó là ám
[00:45:58] chỉ là khi ông chè khi người mua đồ vào
[00:46:00] nó giống như là lúc đầu xong cái ông
[00:46:01] ngay đúng không Ông nghĩ rằng mà khi bấm
[00:46:04] vào nó mới được lót cái htl đấy lên
[00:46:07] không HTML được loạt trước rồi chẳng qua
[00:46:10] khi bấm vào thì nó mới được dislike nó
[00:46:13] mấy chị gia Thôi cái này ra lúc đầu ông
[00:46:15] phải có thêm vài cái flash là lúc đầu để
[00:46:18] ẩn nó đi Đấy nó sẽ như thế này ông sẽ
[00:46:20] chèn thêm cái class cho nó lúc đầu để ẩn
[00:46:26] ở đi sau đó khi mà bấm bấm nút vào để mở
[00:46:29] cửa kích hoạt đến với ai thì nó mới được
[00:46:33] hiển thị ra đấy nó thế
[00:46:36] em ấm hệ tôi nghĩa ở chèn thêm tất cả
[00:46:54] ừ ừ
[00:46:58] anh nhớ cái tự động sắp xếp của tôi bay
[00:47:00] xử đâu ấy
[00:47:00] ừ ừ
[00:47:14] Lê Văn Tuấn Hiền của tôi đang bị nhảy
[00:47:15] sang cái khác rồi
[00:47:23] Anh cipriani
[00:47:26] bí quyết định để mà sắp xếp lại mình cái
[00:47:33] em có nó sẽ cậu dám một đều
[00:47:33] à à
[00:47:39] à à em có các bạn hãy nó ăn đi khi bấm
[00:47:43] mà đó hiển thị ra đó trông trông được
[00:47:45] giao diện nó vẫn xấu thôi nhưng kệ thôi
[00:47:49] nhé tôi tôi không dậy mấy ông dùng bút
[00:47:51] tre đấy Ở ôm giao diện về hoàn toàn dậy
[00:47:54] tôi chỉ cho mấy ông dùng Wechat đây với
[00:47:56] ông là mua đồ trông thấy hoàn toàn bấm
[00:47:59] vào nó bị ra nick là chỗ khác mà ấn
[00:48:03] Escape đâu Hình như phải cấu hình nghĩa
[00:48:08] vụ excape có thể dùng cái cái kia cốt
[00:48:10] hay các từ thứ để mà tắt cái cái này
[00:48:13] trên màn cái cũng được đấy
[00:48:17] Ừ ừ cả notify ấy nhỉ Ừ thích cái tí tôi
[00:48:19] ôm mà nó thấy file về cho mấy ông cũng
[00:48:19] được
[00:48:22] ở đại khái như thế mày không phải bấm mà
[00:48:25] cho nó sẽ chỉ ra ông điền thông tin
[00:48:27] nhưng mà khi mà điền thông tin ở đây mày
[00:48:29] Ông thấy à bản chất nó vẫn là chân nó sẽ
[00:48:31] nhảy đến cái máy này để xử lý đúng không
[00:48:35] ạ Không Bây giờ mình sẽ lại cắn Hiệp Cái
[00:48:37] này bằng Rocket tiếp mình sẽ dùng là
[00:48:40] really kết hợp eject để mà đẩy cái pho
[00:48:44] Mày lên hộ hộ mình thì đây nó sẽ có cách
[00:48:47] đẩy như này tối thể biết ngay ra Swift
[00:48:53] à à
[00:48:57] ở đây sẽ là vẫn là ra đi rồi ông ạ
[00:49:08] anh ở đây nhá Ở đây Đợi tí nhé
[00:49:11] anh ở đây mình thường cái đặt ai đi theo
[00:49:12] cái form này
[00:49:15] Ông Bà mình sẽ chặn cho cái pho mày con
[00:49:17] được dám ít Mình ở trạm cho mày không
[00:49:29] ờ ờ khi mà kia bấm sắm ít thì không dám
[00:49:30] sát Mí
[00:49:34] A và mình sẽ đẩy form lên bằng lá rách
[00:49:38] đấy nó sẽ như thế mình sẽ là là sự ai đi
[00:49:39] Ở đây Ford là
[00:49:43] format size áp không ạ ạ
[00:49:43] ở
[00:49:52] đây à sau khi mà phẩm Sharp submit này
[00:49:52] à à
[00:49:56] chỉ riêng lần này tôi sẽ để lại đi vẩn
[00:49:59] Tại sao lần này tôi sẽ không cho Ivan
[00:50:02] được kích hoạt thì mình sẽ event
[00:50:07] defoe là không cho nó được chạy như mặc
[00:50:09] định sẽ ra được kích hoạt
[00:50:13] Ừ nếu mấy ông làm à Không hiểu cái này
[00:50:16] lắm thì mới không thể chơi trò là
[00:50:18] ông để ai đi cái bước chân này và khi
[00:50:20] cái nút là được Bấm thì cái for mà nó
[00:50:23] lấy thông tin của Ford này
[00:50:26] Ừ nhưng mà không cho con sẵn ít được
[00:50:28] thay Thay của mỗi tuần mà sẽ là có tên
[00:50:33] như thế này sợ ID của Tân size chẳng hạn
[00:50:33] ở
[00:50:37] u
[00:50:41] xơ mít pháp chẳng hạn sau khi cái nút
[00:50:43] này được bấm thì mình lấy thông tin từ
[00:50:47] form hay vì kéo ngăn cho Phong không cho
[00:50:49] sắp mi kiểu nghe đấy Nếu người chơi hai
[00:50:49] cách
[00:50:54] anh em đại phá là khi mà để on shop nick
[00:50:58] có nghỉ thì như ghi nha Rồi được rồi là
[00:51:01] hiểu nó sẽ biết đấy à
[00:51:04] ở đây để tôi chạy thử xem có chạy được
[00:51:07] nha rồi lâu chứ làm cái này bấm vào này
[00:51:09] đó mấy ông thấy không Sắp ít đúng không
[00:51:09] ạ
[00:51:10] à à
[00:51:16] Ừ
[00:51:19] nếu mà không có vị vani fo thì nó sẽ sắp
[00:51:26] không sao không hai bức tượng 200min
[00:51:30] được Phen này ông nhầm rồi anh này nhé
[00:51:30] ừ ừ
[00:51:37] Có ai còn đến mà
[00:51:40] nếu mà không có thai 3 tuần thì mặc định
[00:51:43] thay nó sẽ ra sao mít này
[00:51:48] từ đó thấy được lót cha nó ngon đấy
[00:51:48] cho
[00:51:51] nên là đây là một trong hai cách mà
[00:51:55] không có thể áp dụng theo cách kiểu tôi
[00:51:57] tôi sẽ dạy mày ông thêm cả
[00:52:01] event iPhone nữa Nói chung là đại khái
[00:52:04] là ok bây giờ ngăn không cho con chạy
[00:52:06] nhưng mà mình cần lấy thông tin từ form
[00:52:10] này để mà đẩy lên cái để lên để mà về mà
[00:52:13] kiểu đăng đăng ký để không ạ thì mình sẽ
[00:52:14] là Isaac
[00:52:17] Vì sao đói tiếp và gọi đền cái file mà
[00:52:21] file ghost shop
[00:52:21] ở tp
[00:52:26] lần này thay của mình sẽ là mình sẽ cần
[00:52:29] à đẩy lên Dạ posts
[00:52:33] các dữ liệu trả về dữ liệu trở về mình
[00:52:35] thở da tím mình sẽ trả về là đúng hay
[00:52:39] sai và mình có thể là trà về dạng kiểu
[00:52:43] 10 nếu như tôi từng nói một là thành
[00:52:46] công không có thất bại thì tôi thể trả
[00:52:47] về dạng HTML
[00:52:50] HTML hoa dạng
[00:52:54] bản chất trả về HTML thường hay là dạng
[00:52:57] text trong những chính xác đúng hơn là
[00:52:59] mình thì trả về dạng kiểu chữ hay cái gì
[00:53:01] đó Rồi mình kiểm tra chữ còn ấy nó trả
[00:53:03] lời dặn mấy cái dạng kia kìa Thì ông
[00:53:07] phải thay đổi cái cái dữ liệu trả về
[00:53:10] theo kiểu cấu trúc của nó dạn dĩ hơn ít
[00:53:14] hết đôi xmer vân vân Ừ thì tôi nghĩ cái
[00:53:16] đơn giản hơn
[00:53:18] Ừ tí thôi cũng sẽ có thể được cập reason
[00:53:21] Chắc là để buổi sau buổi sáng nữa
[00:53:25] à Bố mày dậy thế nhiều cái nước quá tiếp
[00:53:27] theo là thông tin mình chuyển lên cái
[00:53:29] này quan trọng này không tên mình chuyển
[00:53:30] lên là thử cái là toàn bộ những cái Minh
[00:53:32] Điền trong form này nếu mà Mấy ông muốn
[00:53:34] làm thì cậu nông dân vùng giữa từng làm
[00:53:36] kiểu nông dân sẽ ra kiểu như thế này
[00:53:38] cũng sẽ điền đầy đủ toàn bộ thông tin
[00:53:41] truyền lên thật sự đây à nêm nè mình sẽ
[00:53:41] lại
[00:53:47] Đôla gọn đến thằng có đây thì ID cơ thì
[00:53:49] tôi ở đây tôi còn làm phải chụp kiểu thủ
[00:53:51] công này
[00:53:53] nên bằng
[00:53:57] phần mềm như này tôi làm chỉ là lấy được
[00:54:01] Đúng ghi Nút này Của đúng kiểu nghe luôn
[00:54:01] anh
[00:54:04] thay vì như này thì bản chất là mình cần
[00:54:05] lấy toàn bộ những cái điền trong phom
[00:54:09] thì có sẽ có cách ngắn gọn hơn nó sẽ là
[00:54:13] đô la ông thầy gọi dùng đo rít cũng được
[00:54:15] ngắm chỉ là bởi vì trong trường này đua
[00:54:18] giết chính người pho mà nó không ạ chấm
[00:54:23] no life như thế Pharma like
[00:54:28] để tôi tra lại nhớ là có mồ
[00:54:32] like thì vui à à
[00:54:35] Ừ để lấy toàn bộ những cái điền trong
[00:54:35] phòng
[00:54:36] à à
[00:54:44] Ừ tôi chắn tôi không nhớ được cái từ
[00:54:50] I
[00:54:52] read from
[00:54:56] data cũng được
[00:55:01] à à sealife Sunlight sôi thêm cả Ag nữa
[00:55:08] em không nhớ được Thì trao Google thôi
[00:55:09] Mày không ạ
[00:55:12] thế này à
[00:55:12] à à
[00:55:24] ạ bây giờ sự tôi tôi bảo rồi tôi không
[00:55:26] đẩy nó và Phone này à
[00:55:29] Thế nên là tôi sẽ để hết nó vào trong
[00:55:33] thành công nhưng mà tí mình sẽ xử lý nó
[00:55:45] ạ bây giờ Giả sử nhé Vợ ăn inspect lên
[00:55:48] này để với ông xem qua thôi à
[00:55:51] bí ẩn ở bên Network này ấn vào bên ai
[00:55:54] kia rồi Nãy giờ tôi đăng ký cứ Điền mấy
[00:55:57] cái gì đó như này đăng ký để không thấy
[00:56:00] là nó sẽ được đẩy lên bằng giấc rồi sau
[00:56:03] đó thì ấn vào trong này kéo sang này nó
[00:56:05] lớp vải lót thì mới Ông thấy hoàn toàn
[00:56:08] là mình mình điện gì trong này nó sẽ
[00:56:11] được đẩy lên đồ ngoại Đấy đấy là tác
[00:56:14] dụng của cái Sunlight này nó sẽ lấy toàn
[00:56:18] bộ những cái có trong form số mến theo
[00:56:19] đúng cái nên của nó để nói chuyện lên
[00:56:22] ông ạ
[00:56:22] Ừ
[00:56:27] cái nó đứng yên à bây giờ của bên mình
[00:56:31] bên mình xử lý là mình luôn chả mình
[00:56:34] đang không in ra một cái gì cả bố xét
[00:56:37] Giáp ở đây mình không in là cái gì cả
[00:56:41] ông ngoại mình đang có hết đồ nữa à mai
[00:56:42] ngày hôm hôm đấy mình tắt hết đầu đây
[00:56:54] à à
[00:56:58] ở nơi này mình thấy nó lỗi đúng ạ
[00:56:58] à à
[00:57:04] đó là sự đây mình sẽ Thế chỗ ở đây
[00:57:10] ở nơi này đi Bạn ship đóng này Đợi mình
[00:57:11] tí nhé
[00:57:16] Ừ nếu mà thành trùng email
[00:57:16] Ừ ok
[00:57:22] em bỏ qua vụ Huy mail hôm trước này à
[00:57:25] có một vẫn phải tạo sẽ dừng em vẫn là
[00:57:28] đạo lý dân như bình thường thôi một số
[00:57:31] đóng thế cho ở đây là 18 trở thành công
[00:57:34] nhận lại còn Đây Rồi mình kiểm tra nếu
[00:57:37] mà trả về không phải là một thất bại ông
[00:57:37] ạ
[00:57:42] anh em cho điền đầy đủ tất cả thông tin
[00:57:46] đi như này đăng ký lần nữa đây chúng
[00:57:48] email rồi bạn chắc chứ đúng không ạ
[00:57:50] Nhưng bên mình cần lại hiển thị thông
[00:57:53] báo ở đây đông ạ Chị thông báo đâu đó
[00:57:58] Khi mà kiểu mình mình sẽ có cơ chế Cường
[00:58:03] nha là sự là mình sẽ đây sẽ có một cái á
[00:58:06] đi xóa lại được
[00:58:09] mình có mua đồ content
[00:58:12] cho mình nhớ có mua đồ header đó là mua
[00:58:14] đồ à
[00:58:17] A header màu đỏ body
[00:58:21] đây sẽ mua đồ body của tôi này cho bỏ đi
[00:58:35] đây sẽ là à
[00:58:35] à à
[00:58:41] ở tiền đây sẽ đăng ký thi không ạ
[00:58:46] a copyright iPhone đăng ký này và mình
[00:58:49] sẽ có một cái á thường Hằng bút pháp này
[00:58:52] nó có một cái để mấy lỗi đấy
[00:58:55] đã lỡ dùng bút trái với tôi sẽ ôm nốt
[00:58:58] cái cho mấy ông xem nó đi in ra cho lỗi
[00:59:06] mình thì lúc đầu tạm được trống đi nhưng
[00:59:10] sẽ có ID là đít Euro này
[00:59:18] và khi mà giờ sự là ít Bphone khác
[00:59:18] ở
[00:59:24] một mình dễ là
[00:59:29] Ừ cái đít Euro này sẽ chấm a tách cũng
[00:59:31] được truyền nội dung restore nào trong
[00:59:35] này đây tôi cho tải lại trang cho mấy
[00:59:40] Anh đang sắp đi
[00:59:49] Ừ cái này xấu xí à Ờ
[00:59:51] Em đứng chờ
[00:59:53] tôi không Nhớ lắm
[00:59:55] Anh ngồi đây chờ
[00:59:55] à à
[01:00:00] từ lúc đầu mấy ông mới ăn cái đi không
[01:00:01] cần phải hiển thị ra Nó kiểu như thế này
[01:00:01] à
[01:00:06] bí mật khẩu ngay đăng ký
[01:00:08] xe tải chung email rồi bạn chắc chứ ông
[01:00:11] ạ Anh thì chỉ là đây
[01:00:15] từ lúc đầu nếu có thể ẩn này đi nhé mày
[01:00:17] ông Nếu mà dùng bút chat thì ra mày
[01:00:19] không biết rồi có mấy cái kiểu nó là
[01:00:22] Style Display lần ăn gì vậy ạ
[01:00:27] a
[01:00:41] em phải trả hằn ở đây là được mà Style
[01:00:41] này
[01:00:48] năm tất cả lúc đó ẩn đi này
[01:00:58] ở nơi này Nhưng mà khi mà có lỗi thì
[01:01:00] mình sẽ hiển thị nó ra thì mình lấy dùng
[01:01:06] Em bấm vào này
[01:01:09] ở địa lại nhé á
[01:01:13] ở đó như này ok chưa bây giờ sử nếu đăng
[01:01:15] ký thành công thì sao đăng ký thành công
[01:01:18] thì thì mình lại phải ẩn cái à
[01:01:21] Lại thứ nhất là đầu tiên mình phải hai
[01:01:31] Ừ thứ hai là mình sẽ kiểu
[01:01:34] Ô thế cái Hà nó có khi không cần mình
[01:01:36] chỉ đơn giản là mình cần mình đóng lại
[01:01:38] cái này và mình đăng nhập thôi ông ạ
[01:01:41] Mình đóng nó mình đóng cái mua đồ lại
[01:01:45] cái cái cái đó mua đồ được ra là đây
[01:01:49] em đang tra giờ buôn lại mua đồ ta chỉ
[01:02:02] thì mình sẽ khái niệm Total hot girl
[01:02:05] không biết phát âm từ đấy nha đại khái
[01:02:08] đóng được cái mua đồ đấy thì mình sẽ là
[01:02:08] đây
[01:02:13] có đền ID Model là
[01:02:27] Em hãy Tôi rất thích hà Mày hả mày Nó sẽ
[01:02:30] luôn kiệm nó sẽ là kiểu còn dùng công
[01:02:32] tắc đèn nó tắt Bật tất bật đi đón chị
[01:02:34] hai chế độ thôi các bạn đang các bạn gọi
[01:02:36] hàm này khi nó nó tắt thì nó sẽ bật lên
[01:02:39] Còn khi mà nó đang bận các bạn gọi hàm
[01:02:42] này nó sẽ tắt đi thế thôi Em chỉ nó sẽ
[01:02:43] như thế này
[01:02:46] Em bấm vào này điện toàn bộ thông tin
[01:02:49] này thật sự là này sẽ trả lại email hợp
[01:03:03] Ừ cái này nó trả về là chuỗi Chắc thế
[01:03:06] những thành ra ba nó bằng là không được
[01:03:06] Ừ ok
[01:03:10] tại ra nhé
[01:03:20] nhờ đăng kí này
[01:03:24] Ừ tao girl của tôi nhưng mà có vẻ là
[01:03:30] Ô tô xong rồi còn vẫn còn cái này
[01:03:45] khi mua daso
[01:03:49] Model tốt g Ok Ok môtô cơ nội tôi nói
[01:03:49] tôi
[01:03:51] à à
[01:04:01] nhờ đăng kí này
[01:04:04] điên này ạ
[01:04:06] anh ấy
[01:04:10] thế này không ra gì luôn
[01:04:10] các
[01:04:16] video sex ra đây à
[01:04:26] Ê hồi gọi hẳn hay đi
[01:04:26] à à
[01:04:30] Ừ để xem nhé
[01:04:47] Ừ thế thì bởi vì cha mình những bút
[01:04:49] giống giấy không chạy thẳng đấy lại được
[01:04:49] mà
[01:04:56] A Gọi hài cũng được xe mà ai đi rồi
[01:04:58] Không đúng à
[01:05:00] Ừ đúng rồi Mua đồ sát
[01:05:08] ăn sáng Đà
[01:05:28] ở một số nơi đau não về vụ này tôi cơ
[01:05:37] từ 0,2 nó không đúng đâu bởi vì à hay
[01:05:39] nói chị ẩn ý thôi Còn cái nền cái nền
[01:05:55] đi chợ mua đồ đến nó là Phong chân tường
[01:06:03] cô gái gọi đến một không tồn tại
[01:06:11] à à
[01:06:21] có hai cái à Hai con bootstrap của mình
[01:06:24] dùng bút khác của mấy ông kia nhé mấy
[01:06:27] ông kia t bố cha mình đang cày mưa chap
[01:06:27] 3
[01:06:30] Anh chấp ba
[01:06:34] mua đồ Wechat à
[01:06:34] ờ ờ
[01:06:57] ở show 2
[01:07:07] gì tôi đang thấy hơi lại ở đây đây à
[01:07:11] Ừ có gì đó Sai sai ở đây còn solo chấm
[01:07:15] lót ra Cả ngày xem giá đấy thằng bộ đội
[01:07:15] không
[01:07:41] à à
[01:07:46] xe ôtô Audi tại vị chỉ được không mà
[01:07:48] anh lại phải không nhớ à
[01:07:48] à à
[01:08:01] anh không được không nữa
[01:08:21] Ừ bắt cô
[01:08:25] ở
[01:08:28] bến xe máy
[01:08:28] à à
[01:08:35] hãy click mua đồ
[01:08:42] Anh bình thường mỗi khi tôi chạy cái này
[01:08:45] vẫn được ngoài bằng cách thân tháng ở đó
[01:08:48] là không chạy được
[01:08:50] ở đôla đây sẽ trả nó khai báo giờ này vì
[01:08:53] vậy thay ra đi rồi
[01:08:57] anh trai gọi đến rồi ra được rồi
[01:08:57] à à
[01:08:59] khi
[01:09:03] bạn mua đồ nhà ai
[01:09:03] à à
[01:09:09] Ba Mẹ tao cơ sở được rồi Vừa nãy không
[01:09:09] được
[01:09:11] à à
[01:09:17] số
[01:09:20] tiền Bỏ ra cho vừa đi nhé Chị gọi cho
[01:09:27] à à
[01:09:45] em
[01:09:48] hẹn cho anh chơi thủ thuật kiểu ngay
[01:09:49] à à
[01:10:17] ở đó
[01:10:21] chơi được thử thật nhiều ngay à
[01:10:23] A Gọi mua đồ
[01:10:27] A Gọi Tower không mua đồ vừa rồi không
[01:10:29] báo báo nó không tìm thấy cái Hàn mua đồ
[01:10:32] không đi ở xa đỡ là chèn thêm với thư
[01:10:34] viện Hàng ngày về thì đáng lẽ phải chạy
[01:10:47] Anh không dùng để hàng gọi lên các ham
[01:10:55] Ừ Ừ kệ chứ nó vẫn thế là về này nó vẫn
[01:10:58] đúng rồi mà ok bây giờ tiếp theo là mình
[01:11:02] muốn thực thực ra là thế này thiếu lòng
[01:11:05] tin đó là mình cần lấy khi mình Điền
[01:11:07] xong mà cho mọi thứ ổn này rồi mình cần
[01:11:09] lấy thứ nhất là
[01:11:11] Nếu như các bạn thấy là bây giờ mình
[01:11:13] phải tải lại trang thì nó mới
[01:11:16] xe tải lại tra thì nó mới thì xin chào
[01:11:18] xong rồi nút đăng xuất đúng không ạ thì
[01:11:20] vừa mình không muốn như thế Mình đóng
[01:11:22] với Mua đồ xong thì mình cần hiển thị ra
[01:11:26] được cái chao thì bạn thân ở đây mình sẽ
[01:11:36] ở đây thì ra là cái phần à
[01:11:39] em tôi đặt cho nó một cái gọi là phải ai
[01:11:48] anh ở đây Bây giờ mình cần mình cần làm
[01:11:51] nhé đó là mình cần à
[01:11:55] thay cái cái Menu này
[01:11:58] anh có hai cách mấy ông nha Một là mấy
[01:11:59] ông nha
[01:12:03] mấy ông có thể tạo đâm cái Menu không
[01:12:04] không phải làm thì cậu dạng kiểu như thế
[01:12:07] này nữa theo kiểu lại ít em thì ông hiển
[01:12:11] thị ra mà ông ông làm theo kiểu là cho
[01:12:14] nó dislike là là năm đấy Cái ẩn tạm bạn
[01:12:18] ở đi sau đó ấy khi mà thành công cái này
[01:12:21] thì ông this Player sau để hiển thị nó
[01:12:24] ra thì ở sẽ ổn hơn để từ từ thử làm cho
[01:12:33] hai
[01:12:42] Ừ nhưng mà có như này
[01:12:51] i300 bình tĩnh bình tĩnh bình tĩnh
[01:12:55] cách đăng xuất lại chào xem show hành đ
[01:12:59] ý nghĩa là khi mạng
[01:12:59] à à
[01:13:08] em mới gọi này vẫn phải sai sai là
[01:13:10] các em à
[01:13:16] Ừ
[01:13:33] à à
[01:13:35] ừ ừ
[01:13:43] em bỏ Arina
[01:13:43] ừ ừ
[01:13:48] ở đoạn này mình không Thế thì da trông
[01:13:53] có vẻ phức tạp hơn phức tạp hơn này ạ
[01:13:53] à à
[01:13:56] ừ ừ
[01:14:01] Ừ nhưng mà thường là người lạ không chơi
[01:14:04] cách này về sao tôi không Dạ email phải
[01:14:06] em giúp em này đâu có gì đang hướng dẫn
[01:14:08] ông là có thể làm được cái trò kiểu ngay
[01:14:08] thôi
[01:14:10] à à
[01:14:14] nhà mình có chèn file này mình chuyển
[01:14:17] file được làm chè động được như thế mình
[01:14:20] cứ chen file ở đâu được đi để nó dưới
[01:14:23] này đi theo thì sẽ ra
[01:14:26] I search in Club des sciences chẳng ạ
[01:14:30] Con eo cái kiểu ngay Nếu mà không đăng
[01:14:34] nhập điện thì có thể hình nút 2 file này
[01:14:38] I play style cho nó lại tiếp tục là nếu
[01:14:38] mà
[01:14:45] gà trống thì ẩn này đi này
[01:14:49] ăn này đi này à
[01:14:52] ạ Bây giờ ông không có ship từ cái này
[01:14:54] nó kêu chị sẽ lỗi nhưng mà ông Ẩn đi nó
[01:14:57] sẽ không bị ra nữa làm cách 2 mà dễ hiểu
[01:14:58] nhé Ae
[01:15:01] Ừ anh đang sau nha
[01:15:01] à à
[01:15:07] anh hả
[01:15:12] a shyne shyne cũng có vụ
[01:15:21] trà xanh yên tĩnh sau nhé tạm bỏ inplus
[01:15:23] ai nỡ loạn đã
[01:15:26] ở đây Nói chung nhà khi mà ở mấy ông
[01:15:30] đăng nhập và thì mới ông sẽ đây Đấy cái
[01:15:32] Menu của tôi nó vẫn còn nhé
[01:15:34] cho em địa chỉ a menu của tôi nè
[01:15:37] I know this place chẳng ngoan ăn nữa Dạo
[01:15:39] này nó lại lỗi tí
[01:15:43] xin chào đây lỗi vì À bởi vì rõ ràng đây
[01:15:45] không có tên của người người đào cả
[01:15:54] tự hào Ok bỏ
[01:15:57] lỡ thì Rốt cuộc gọi Isaac chẳng có tác
[01:15:59] dung dịch à à
[01:15:59] ờ ờ
[01:16:06] anh cứ cứ để chào nhé không ta Mẹ không
[01:16:08] hiển thị lỗi người dùng cũng là một cách
[01:16:10] còn bé ông muốn chặt chẽ hơn để em kiểm
[01:16:13] tra đấy hỏi cháu mà dâm nữa cho Dũng
[01:16:17] ngay là được cái Sao nó không lỗi
[01:16:20] Nghe nhạc xem hiện đúng rồi nó sẽ không
[01:16:20] lỗi
[01:16:25] Ừ cái này kiểm tra này có tồn tại thì ấy
[01:16:28] nó ra không thì
[01:16:32] À mà bạn này làm tiếp để làm tiếp là
[01:16:35] khi mình ăn nó đi này và mình cần hiển
[01:16:36] thị ra gái
[01:16:40] U22 hai cái này hay Cái này mình sẽ à
[01:16:43] mình đặt tên nó flash cũng được
[01:16:45] a-class là
[01:16:47] menu à
[01:16:52] Ừ nó tin là Ngạn và khi đăng nhập được
[01:16:54] anh sai đi
[01:16:59] lo in his khi đăng nhập vào Sign fake
[01:16:59] size
[01:17:03] khi đăng nhập vào thì cái máy nuôi được
[01:17:07] hiển thị ra đấy như thế này
[01:17:07] ừ ừ
[01:17:16] Á Châu Anh bị ra cái nút này nhưng ngoài
[01:17:19] ra là mình sẽ cần phải ạ Điền cho cái
[01:17:23] này mình có stein này có anh một cái
[01:17:25] span ở đây
[01:17:31] anh ta mình có ai đi nó là spam lên ạ
[01:17:33] Để mình mình Điền Tây nó nó mà nó không
[01:17:40] add
[01:17:44] ID slame này chấm tách này
[01:17:47] sẽ bằng cái gì thì ra bằng chứng kiến
[01:17:50] lên mà mình đã điên thế này này thì các
[01:17:52] bạn có thể lấy nó là
[01:17:55] đô la
[01:18:00] input tại nêm đấy à
[01:18:02] em lên mạng lên đấy
[01:18:05] Cái cái ngoặc vuông này Nói chung là cái
[01:18:07] cách selector con này là của xe hồi nãy
[01:18:11] mình nó quay chấm ba lô lấy giá trị nữa
[01:18:11] anh
[01:18:15] chậm khá lằng nhằng thường à Tôi đang
[01:18:17] dậy rồi mấy ông ấy chồng mình biết qua
[01:18:19] thôi mình thường ít ông chứ em dụng kiểu
[01:18:21] nó kiểu này lắm
[01:18:25] nhờ đăng kí này đi ăn đây ạ
[01:18:25] à à
[01:18:30] khi nhìn ai có sợ chung nha nhiều lần
[01:18:32] tôi gõ gửi xong mà vẫn bị trùng các bạn
[01:18:37] đăng ký nhé đó ngon rồi đấy nếu mà mình
[01:18:39] cần à ẩn hay ngay đi này thì mình cần
[01:18:58] hôm nay Lucy gà không Cái này phải đặt
[01:19:01] tên nó như thế nào ấy để Manu guest là
[01:19:05] người đã người chưa chưa có tài khoản đi
[01:19:08] vào đây menu Rơi là người có tài khoản
[01:19:13] cái để rõ phân biệt nhà cũng được
[01:19:14] mà menu
[01:19:23] thử lại phát nữa
[01:19:30] Ừ
[01:19:33] ông leakless máy in U2 ạ
[01:19:37] đó chưa chậm phải dưới chữ nghiệp như
[01:19:39] kiểu dạng kiểu
[01:19:42] nhưng rồi Mỗi tội loại cốc này ông thấy
[01:19:46] cài nó càng dài đó nhược điểm Gia Huy sử
[01:19:48] ca về sau các bạn Thể cốt một cái file
[01:19:48] HTM
[01:19:52] tôi hồi ấy Tôi bị nghiện really mày
[01:19:54] không ạ kiểu xong rồi ngồi mò mấy cái
[01:19:55] này so với cùng thời ra một cái file
[01:19:58] HTML đôi cũng 100 vòng thôi nhưng Duy
[01:20:01] rồi lên ba bốn năm ròng thì nó Kế file
[01:20:03] rất dày và thực ra nó về sau rất phức
[01:20:05] tạp bằng nhạc Nếu thấy gan nhìn loại này
[01:20:09] trọng rất lằng nhằng không tối ưu thế là
[01:20:11] thường bây giờ chắc ai làm dùng kiểu
[01:20:13] nông dân kiểu ngay nữa mà sẽ dùng Trung
[01:20:16] Quốc nghĩa là bấm vào cái này chỉ kịch
[01:20:19] cái kia nó sẽ tự động thay đổi ra tiện
[01:20:21] trứng vậy Ở kiểu mình phải gọi tướng
[01:20:23] hành tinh tăng thì ẩn hiển thị Nga như
[01:20:26] này nó khá sợ không ạ
[01:20:28] khi nhìn lại rất sợ đấy về sau không có
[01:20:31] một đống đít xong Còn đống ai đi rồi
[01:20:31] class
[01:20:35] làm nhá
[01:20:37] Ừ nhưng mà em vừa ra mẹ nó qua việc làm
[01:20:39] mới nghỉ thì em mua cái mua đồ không ạ
[01:20:43] để mà để mà đăng ký mạng xong rồi các
[01:20:44] thứ thứ
[01:20:46] Ừ chắc đăng nhập thì méo làm tương tự
[01:20:49] nhé Bỏ qua Bộ đăng nhập Đi tương tự thôi
[01:20:49] I
[01:20:55] ạ Bây giờ mình sẽ dạy nốt các bạn về bên
[01:20:57] virus nhỉ
[01:21:03] ừ thì bấm đăng ký nó sẽ có một cái váy
[01:21:06] đấy Ở đây mình không đi ăn gì đó ấn ở
[01:21:09] đây sẽ chị lỗi bên cạnh gì đó Sao nào sẽ
[01:21:11] như thế nào ạ
[01:21:14] Vì sao không thấy cười đi
[01:21:14] Ô
[01:21:20] kìa mod thì mình sẽ dùng cái YouTube rồi
[01:21:25] vides thừa tôi gọi về đi tơ Bởi vì nó có
[01:21:26] thư viện
[01:21:29] khá nhiều thư viện thôi đấy tôi dùng là
[01:21:32] bút chép về đi tơ
[01:21:35] Em chưa biết là bây giờ nó còn cứ điện
[01:21:39] không hay gì gì đó Download
[01:21:41] Ừ để mô tôi hãy xem demo là xem trong
[01:21:44] ngày nhé bấm vào này bắt buộc phải điền
[01:21:47] này hay không đẹp
[01:21:51] Vì vậy tôi nhớ có phải thằng này hơn
[01:21:53] em bấm rồi này
[01:22:10] gà trống sĩ mà đúng không gõ đấy hiển
[01:22:12] thị được thành công đại chạy trong những
[01:22:16] xin phép chị cách ngon này không biết là
[01:22:19] có kết hợp cả rồi rách không
[01:22:31] chị xem trong bài liệu nó xem có kết hợp
[01:23:15] khi tôi đọc nãy giờ nhờ không có relax
[01:23:15] đúng
[01:23:32] à à
[01:23:49] em hãy nói kiểu kiểu như thế này
[01:23:49] Ừ rồi
[01:23:56] chị xem nhé
[01:24:10] vì nó có khi để Mesut kiểu hãy Tôi rất
[01:24:26] à à
[01:24:29] ừ ừ
[01:24:39] ở
[01:24:51] ừ à nó choáng mì thớt Ok Ok cái này để
[01:24:54] mà thêm được ZicZac Tôi tôi muốn chỉ mấy
[01:24:58] ông có có thể một cái thư viện được cho
[01:25:00] là ổn không phải thư viện mà chỉ có đầy
[01:25:02] đủ những hàng mà mếu muốn mà giờ xử
[01:25:04] giống như tôi và bà có thể thêm chèn
[01:25:07] thêm những cái kiểu điều kiện khác của
[01:25:09] mấy ông thì phải có một thư viện nó mở
[01:25:11] một tí thôi dậy mấy ông ấy thư viện mò
[01:25:15] sẽ ổn hơn hay có cái vụ đấy đã ngon thôi
[01:25:19] Ok để đau Lát nữa thôi
[01:25:22] khi download hoặc dùng CN
[01:25:22] ở đây
[01:25:28] ở CNC
[01:25:28] à à
[01:25:34] ừ ừ
[01:25:36] cách chèn thêm
[01:25:39] chanchan thêm sữa này phải chèn dưới Duy
[01:25:39] nhé
[01:25:52] Anh muốn chèn thêm rửa Gia Huy nhé mày
[01:25:59] a hlc ạ
[01:25:59] à à
[01:26:04] dự báo thế Thế là mấy ông xài được rồi
[01:26:08] ạ bây giờ thử đọc tài liệu luôn anh tài
[01:26:09] liệu nó được ra
[01:26:13] có thể thao đơn giản gọi đến Hàn này là
[01:26:13] Xong
[01:26:20] cái nhớ hả mày thì kiểm tra tương đối
[01:26:23] à mình mình mình cần mình còn phải cấu
[01:26:26] hình cả cấu hình cả Mỹ ship cái thứ tư
[01:26:26] nữa
[01:26:36] Em thấy có hướng dẫn ở đây này Tiếng
[01:26:38] Việt là nói như thế này rồi mà ông tiện
[01:26:40] vãi chưởng nữa
[01:26:43] ở mình người đi sau đầy đầy cái có hết
[01:26:48] A
[01:26:52] gọi đến copy đoạn này ra sau máy cuộc
[01:26:56] sống chơi nạn đến thế à
[01:27:00] ở đây Nói chung à bây giờ thì không phải
[01:27:13] à à
[01:27:16] Em có nhớ là khi nó nó có cả khi mà
[01:27:20] thành công ấy thì thành công thì mới
[01:27:23] mới sắp ít đấy
[01:27:23] à à
[01:27:29] các video sớm nhất Sony
[01:27:31] Ừ cái này đã chạm sắp ít rồi nhớ cái này
[01:27:38] anh không biết hai này cùng dùng được
[01:27:41] không Không phải có một cái file một cái
[01:27:41] à
[01:27:56] à à
[01:27:56] Ừ
[01:28:01] thôi Chả biết cái cái
[01:28:04] cốt World Cup này có dùng đúng thư viện
[01:28:06] của tôi không cơ thư viện tôi tại về
[01:28:08] không cơ
[01:28:11] i a Do nó ok ok
[01:28:14] sau khi mà
[01:28:18] khi format for some ít này à
[01:28:18] à à
[01:28:23] em nici phòng không cần sắp Mít đã mình
[01:28:23] sẽ
[01:28:27] đứt đoạn này vào đây
[01:28:27] à à
[01:28:30] cho
[01:28:34] mấy thì gọi đến phòng đấy vào đây sẽ ra
[01:28:37] form này
[01:28:39] khi họ
[01:28:48] sản phẩm site này à à
[01:28:51] khi chọn này vào đây và giết con Focus a
[01:28:54] gì đó không ăn trọng ra mấy cái đầu mày
[01:28:57] xuống trọng bỏ đi chậm lại rồi này luôn
[01:29:01] này rồi sẽ theo nêm nêm của mấy ông nhé
[01:29:04] nêm này bắt buộc điên đấy độ dài lớn
[01:29:11] nếu không thể phải đây nữa không thể
[01:29:13] thêm những cái Du nào
[01:29:15] ở đây sẽ ra
[01:29:15] ừ ừ
[01:29:33] Em
[01:29:37] email và chu Chắc thế thử
[01:29:37] à à
[01:29:43] a password will be equal password này
[01:29:45] đây phải điền lại password tôi còn chẳng
[01:29:48] có điên lại bắt Quốc thật sự có đi lại
[01:29:50] bất World thì hai cái nó phải bằng nhau
[01:29:53] này khá được đúng loại này là sự điện số
[01:29:57] điện thoại hai cái thứ thứ
[01:29:59] ở nhà mày ra đây tôi tạm không phải đấy
[01:30:01] đi tôi thẳng về để tương đối đi là sự
[01:30:05] thế là mình sẽ tôi Tôi muốn in ra cảm ấy
[01:30:09] suýt nữa là khi mà thai có vấn đề không
[01:30:09] ạ
[01:30:13] Hay chạy lỗi thì mình sẽ in ra lỗi như
[01:30:17] là mình sẽ có in lỗi cậu bắt buộc phải
[01:30:19] nhập tên đúng không ạ
[01:30:24] Đây cậu ngay Rất tiện được
[01:30:24] à à
[01:30:31] AE nhập email sai rồi nã
[01:30:33] chuyển ngay
[01:30:33] ừ ừ
[01:30:39] gì
[01:30:39] đấy
[01:30:45] Mày không sẽ thấy ở nhà Nó rất tiện này
[01:30:45] à
[01:30:49] Còn nếu mà không đi mình có nhớ là nó
[01:30:51] dùng cái mặc định của nó không tiếng Anh
[01:30:52] thì phải à
[01:30:52] à à
[01:31:12] Ừ từ xem Tại sao lại sắp ít luôn à
[01:31:15] khi có khi không gọi được cái hàm này có
[01:31:17] khi không gọi được hả mà
[01:31:21] ở
[01:31:24] đây đến nào là phong chiến đấu ngoài cho
[01:31:26] sẵn rồi không gọi được hàng này cho
[01:31:29] firmino của mình a size của mình có thể
[01:31:29] ở
[01:31:53] Ơ sao lại nhé
[01:31:54] Nha Trang
[01:32:03] à à
[01:32:03] ừ ừ
[01:32:07] em bị lỗi
[01:32:13] I
[01:32:21] em thấy do tôi nghĩa là phải đẩy Thằng
[01:32:23] này nó xuống cuối Ừ
[01:32:33] Ừ địt
[01:32:33] à à
[01:32:39] vì nó không thấy tác dụng nó chưa đầy
[01:32:41] xuống cuối nó mới nhận bởi vì gỡ ra là
[01:32:41] là
[01:32:47] Ê thằng Midu gọi trước à phải được lót
[01:32:49] đã xong rồi thoại mới lót để nó chèn
[01:32:53] thêm bạn Nếu thấy tao không
[01:32:57] Em hãy ấn vào đây Okay thấy chưa
[01:32:59] Ừ thế được rồi không ạ thì đi ăn xong
[01:33:02] đầy đủ thì mình sẽ sắp it for thôi
[01:33:05] lại như này à
[01:33:10] khi
[01:33:14] đăng ký xong nó sắp ít luôn ạ Mình sẽ
[01:33:19] form event ở đây phải ngăn phóng Mít
[01:33:19] ờ ờ
[01:33:24] em hẹn đồ đây
[01:33:32] chị xem nhé
[01:33:32] ừ ừ
[01:33:33] [âm nhạc]
[01:33:56] à à
[01:34:21] Xin chào mừng trong thằng ngày nó cố Tôi
[01:34:24] không quen cốt thằng này lắm
[01:34:30] Hôm
[01:34:33] nay tôi thử Ford
[01:34:40] nếu tôi không nghĩ chẳng làm được form
[01:34:49] ý là có thể thốt ra ship của tôi có thể
[01:34:52] chết được đoạn dưới này khiến cho nó lỗi
[01:34:54] khiến cho nó không bắt được cũng thể
[01:34:56] Em thử nhé
[01:35:38] ở
[01:35:41] chỗ giảng có đoạn này
[01:35:44] a móc tắc vãi chưởng
[01:35:44] à à
[01:35:56] ở ngoài chuyện vài thư viện thông đấy
[01:36:07] à à
[01:36:10] Ừ chán thế này để ngăn việc phóng trăm
[01:36:11] nghìn à
[01:36:11] ừ ừ
[01:36:11] [âm nhạc]
[01:36:19] khi mở mà dụng Ajax form này mình mình
[01:36:21] từng dùng cái Asphalt này
[01:36:24] I know For máy Thực ra nó lại kiểu ác
[01:36:27] Lấy thông tin từ iPhone thôi
[01:36:27] à à
[01:36:32] cách chèn hôi nhiều sự kiện hàng ngày Nó
[01:36:40] à à chị
[01:36:43] xem nha
[01:36:45] em nấu sắp cuối
[01:36:47] anh không được thì tôi sẽ làm mới của
[01:36:57] à à
[01:37:01] em vừa rồi nói đi lỗi vừa rồi nó bị lỗi
[01:37:03] rồi Sắp mít luôn
[01:37:03] Ừ ok
[01:37:06] xe
[01:37:10] máy méo để kia rồi Giỡn nói đĩa lỗi
[01:37:10] ở
[01:37:15] nhà em hay là nó không nó không chặn
[01:37:34] đặc biệt đội đây hơn ít không biết được
[01:37:34] không
[01:37:35] à à
[01:37:42] em không có không được
[01:37:42] à à
[01:37:44] a
[01:37:48] cho thẳng luôn Sao mày không được sẵn ít
[01:37:51] luôn đi à
[01:37:51] à à
[01:38:16] Ô Long 1
[01:38:19] Ừ mình mới ở trại
[01:38:23] em vừa rồi năng có lỗi gì nhỉ Chắc là để
[01:38:25] phom developer ở đây không được
[01:38:28] này nông dân ở chưa
[01:38:31] Ok Bây giờ mình phải kết hợp cả hai cái
[01:38:49] Ơ
[01:38:53] cái thằng phom phom này nó là cái gì nhỉ
[01:38:59] cho tôi trong thường ngày Tôi không chắc
[01:39:01] để đôla giết ở đâu nên tôi phải gõ lại
[01:39:18] đó đưa rồi
[01:39:35] khi đoạt được đặc không cần lời ve này
[01:39:38] nữa OK tưởng phải thêm các từ ve nữa thì
[01:39:42] UCWeb Ok Sao vừa nãy do là lỗi cốt ở
[01:39:45] trong này khiến cho Kiều cái hàng này
[01:39:47] không sẽ được nên không nó không ăn được
[01:39:52] việc là vì vendor for for mà sắp Mỹ luôn
[01:39:52] Ừ ok
[01:39:59] 100 cách đơn nhiên à mình mình kiểu gì
[01:40:01] cốt sẽ có bức Nhưng mà quan trọng là
[01:40:04] cách mình giải quyết được mình cho các
[01:40:06] bạn hình dung được cách xử lý do cái
[01:40:09] Facebook như thế nào tiện nhanh không ạ
[01:40:14] i7 thế Sao nghe coi như bạn thấy là hôm
[01:40:16] nay mình kết hợp với cả
[01:40:20] dùng mua đồ này dùng cá thứ khá nhiều
[01:40:23] nhà ngon thế hôm trước à hôm sau trong
[01:40:26] làm thêm cả những chị thông báo được
[01:40:35] thì các bạn còn thắc mắc hỏi gì không ạ
[01:40:35] xe
[01:40:38] máy xong cái này rồi này
[01:40:42] A và bếp xong rồi này à Chú Chó Thông
[01:40:49] anh
[01:40:51] sữa bắp Nhanh nhá
[01:40:56] tại khái vừa lỗi ở cốt này thôi Nói
[01:40:58] chung lỗi đâu đấy nhưng mà ông kiểu
[01:41:01] comment tắm đóng lại đúng ạ xem nó chạy
[01:41:02] Xong rồi
[01:41:05] Tại một con sâu lót ở đây xem ạ là còn
[01:41:07] chạy đến hàng có source Lấy không Nếu mà
[01:41:10] có những rò thôi đến đoạn đấy nó vẫn
[01:41:11] đúng Còn nếu không thì ông Ngoại có số
[01:41:14] ra ở chỗ khác không ạ Cứ thấy chữa rằng
[01:41:14] thôi
[01:41:15] à à
[01:41:20] tự học tiếng công nghiệp tin cần giỏi
[01:41:21] tiếng Anh không
[01:41:24] vừa rồi mấy ông thấy tôi lên phải lên
[01:41:26] đọc tài liệu nào Nhưng mấy ông thấy tôi
[01:41:27] có người đọc tài liệu nó
[01:41:30] tôi chỉ cần biết một vài từ khóa Thôi để
[01:41:33] mô xong rồi Isaac đã dùng sắp ít cá thứ
[01:41:35] đúng không ạ
[01:41:37] nhưng mà tôi có đọc tí gì nó viết gì
[01:41:40] không Tôi chẳng đặt gì cả ông ngoại tôi
[01:41:43] chỉ có cốt Về Thôi đọc code hiểm
[01:41:43] ừ ừ
[01:42:05] ê
[01:42:10] kê Nói chung à Bố mày chán chỉ tương đồi
[01:42:11] Yên Thế thôi nhỉ
[01:42:13] Ừ có gì các bạn thắc mắc thì hãy nhắn
[01:42:16] tin hỏi Dương hoặc là bình luận sau nhé
[01:42:19] Bạn trả bạn nhé
[01:42:19] ừ ừ
