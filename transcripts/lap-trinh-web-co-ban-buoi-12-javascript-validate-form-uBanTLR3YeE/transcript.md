# Lập trình Web cơ bản - Buổi 12 - JavaScript - Validate Form

- Video ID: `uBanTLR3YeE`
- URL: https://www.youtube.com/watch?v=uBanTLR3YeE
- Published: 2021-11-16
- Duration: 1h 42m 49s (6169s)
- Language: vi
- Subtitle source: auto
- Kind: live

## Transcript

[00:00:07] anh
[00:00:11] Alo Alo
[00:00:16] Alo ạ
[00:00:26] alo alo alo
[00:00:31] Anh ở đã tự nhiên tiền bé nghỉ Alo ở đây
[00:00:39] anh alo
[00:00:42] Xin chào các bạn Hôm nay chắc là ăn sớm
[00:00:44] tí vì hôm nay được cả có khá nhiều sự
[00:00:46] chia sẻ cũng như là
[00:00:49] khi trả lời các câu hỏi của trước mùa
[00:00:50] trước nhưng mình quên không trả lời anh
[00:00:54] là run run có hỏi sang tận buổi hôm nay
[00:00:56] hôm nay được ra cũng chia sẻ nhiều phép
[00:00:59] hôm nay mình sẽ định chia sẻ
[00:01:04] hai cái một cái là
[00:01:04] khi
[00:01:08] cài là cách viết khi hát rồi mà trong
[00:01:10] kết hợp của mình hiện tại mình không nói
[00:01:14] nó đang rất là đẹp rất ngầu gì gì đó cho
[00:01:15] tôi đúng ở mình cảm thấy nó rất là sự
[00:01:20] thật Nhưng mà mình mình mình cảm thấy
[00:01:24] kiểu không nên giữ cho riêng mình mà bản
[00:01:27] chất là mình cũng đi có ở trên mạng về
[00:01:30] thôi nên mình sẽ hướng dẫn các bạn để mà
[00:01:33] làm rất nhiều các bạn có thể để làm cái
[00:01:35] tương tự thì
[00:01:38] Ừ thì cũng không không nên lắm mà nên
[00:01:42] làm nên học cách để mà làm những cái có
[00:01:45] thể đẹp hơn tiện hơn nó trong phù hợp
[00:01:49] với các bạn hơn tiếng nhỏ để mình di sát
[00:01:52] và mình lại quên chắc mình phải nuốt lại
[00:01:56] đi lại làm mua thấy hay thì mình nhắn
[00:01:58] cho
[00:02:02] anh chị cho nóc nhà là mua cái treo mic
[00:02:05] Ừ chứ cứ ngồi gì ý sát vào cái mic kiểu
[00:02:31] trên ảnh b-code base64
[00:02:34] hình như là được Đấy nó gửi bạn chất vào
[00:02:36] nó
[00:02:40] Ừ nó kiểu ở cái clip mi nào dùng móc
[00:02:55] em alo tiếng to hơn rồi đó ạ
[00:02:59] Ừ thôi bé đầu tiên mình chia sẻ phải cá
[00:03:00] nhé
[00:03:02] ở đầu tiên thì ở
[00:03:05] em làm dạy học như thế này chắc anh kiên
[00:03:06] trì dữ dội lắm
[00:03:09] Mình nghĩ là mỗi ngày nghề thì nó vẫn là
[00:03:14] có cái kiểu Có cái khó khăn riêng của nó
[00:03:17] thì Nhưng mà khi dạy này thì công nhận
[00:03:20] là mình cảm thấy á
[00:03:24] vừa dạy vừa phải dỗ có nếu mày giờ đỡ
[00:03:27] hơn so với kiểu tiểu học mẫu giáo gì đó
[00:03:30] nếu mà nó cũng sẽ có bất tiện hơn riêng
[00:03:33] một vài cái thôi mình đi dậy hồi mình đi
[00:03:35] dạy à cho sinh viên thì ta mình khó chịu
[00:03:39] việc là sinh viên của trường cũ của mình
[00:03:42] thì nó là kiểu nó kiểu dạng là
[00:03:45] nhờ bạn nghĩa đóng tiền đến đấy là Anh
[00:03:48] là qua được môn là có được cái bằng ấy
[00:03:52] ngồi trường mình kiểu nó không nổi và
[00:03:54] nói chung và kiểu
[00:03:59] thì kệ tuyển đầu vào nó kiểu không giống
[00:04:01] như đại học chính quy khá là dễ vào
[00:04:04] thành ra toàn những cái ông mà kiểu
[00:04:06] Trượt đại học những cái ông mà cậu không
[00:04:09] vào được đâu vào chả hạn cũng có một vài
[00:04:13] thành phần như thế anh ra kiểu đi dạy
[00:04:16] cho mấy người khá là mệt Lúc đầu họ có
[00:04:19] có muốn học đâu họ cũng xác định có theo
[00:04:22] ngày này đâu đó ngoại thành ra là kiểu
[00:04:27] ăn giỗ khá nhiều dạy hay ít mà dỗ nhiều
[00:04:28] hơn
[00:04:31] khi mình vẫn còn bé có khi ông phải xem
[00:04:35] lại xem các bạn khác thì thấy mi có có
[00:04:42] ông chưa Thế này là quá to gì để
[00:04:44] đúng kiểu gì xanh hết mất rồi đấy
[00:04:55] trò chuyện thì nói chung là cái việc
[00:04:58] kiên kiên nhẫn của mình hồi đấy cũng khá
[00:05:02] phải kiên nhẫn cái việc đấy cũng khá làm
[00:05:05] là khi mà kiểu Khi mà
[00:05:07] mình nhiều lúc mà mình muốn dậy rất
[00:05:09] nhiều cái Giả sử nhiều cái mình dậy
[00:05:11] chuyên sâu ở ở
[00:05:13] trên này như thế này phải chưa lớp mình
[00:05:16] khó được dạy lắm Bởi vì à dạy cơ bản bọn
[00:05:19] nó còn phải mất khá nhiều Buổi rồi mà
[00:05:22] nghe chưa Làm bài tập đấy Em hãy ra kiểu
[00:05:24] không để dậy những cái chuyên sâu được
[00:05:26] em chỉ dạy được nhận được cơ bản thôi
[00:05:28] Được ra làm mình cảm thấy cũng dễ bị
[00:05:30] được trí kiểu kiến thức của mình bị lãng
[00:05:43] khi cây câu của bạn này Hôm nay mình
[00:05:47] cũng sẽ giải đáp này đó là sẽ dùng những
[00:05:49] cái hàm ghét ở đây mình có thứ Thử như
[00:05:50] thế nào
[00:05:54] cách truyền tham số vào hàm để in ra ở
[00:05:59] tí mình sẽ dạy các bạn về vụ là có thể ở
[00:06:01] dùng nhiều hàm
[00:06:03] từ lần trước mọi khi mình chị dùng đúng
[00:06:05] bật hàm Thôi bây giờ mình sẽ thử dùng
[00:06:08] nhiều hàm thôi truyền cấp hàm số và các
[00:06:16] Ờ annimation cũng làm bằng da skip hả
[00:06:22] Anh thì cho cái bản chất ra Swift đó nó
[00:06:25] là làm cho
[00:06:29] Ừ nó làm cho thay đổi HTML CS CS mấy làm
[00:06:32] animation làm hiệu ứng cầu chuyển động
[00:06:34] vào thứ thứ nhưng mà để cho thằng ngày
[00:06:36] nó nhảy sang chữ to hơn hai thằng này
[00:06:40] làm cho từ trái sang phải gánh mạ vàng
[00:06:42] chất thì nó là
[00:06:46] ra Swift nó sẽ can thiệp vào CS của nó
[00:06:50] để đẩy cho nó ra họ để nói hiển thị ra
[00:06:53] Vân nó không ạ Thế nên là animation làm
[00:07:10] đi siêu âm vẫn đang trong mùa thi cử nhỉ
[00:07:13] em tính
[00:07:15] có lần cuối mình thi kể trường liên
[00:07:19] thông thì chở ra rồi Khá là dễ học đến
[00:07:21] thôi công nhận là dễ mà Thiệu dễ được
[00:07:23] mang phao đi em ạ
[00:07:25] Cái này không không không giấu diếm gì
[00:07:29] cả nhưng mà mình đi vẫn tự làm mình như
[00:07:31] con đỉa ngồi trước làm đặc biệt là làm
[00:07:33] mấy cái câu trách nhiệm mình từ nó đó là
[00:07:38] Ờ mình sẽ luôn nhìn vào đáp án này đoàn
[00:07:40] câu hỏi mình không không cần nhìn câu
[00:07:41] hỏi luôn
[00:07:43] Làm trắc nghiệm kiểu như thế nó mới gần
[00:07:46] nhân phẩm nó mới hay nếu sẽ gì cả nhìn
[00:07:49] vào đa bàn thôi Em đoán xem câu hỏi nó
[00:07:55] vì thế mà tội là nào tối hôm qua bây giờ
[00:08:02] ở những hàng phổ biến của aj và chuỗi
[00:08:06] Chắc là buổi sau buổi sau là chó là buổi
[00:08:10] sau sẽ là mỗi cuối của Switch vừa hôm
[00:08:12] nay là Bộ hôm nay sẽ rất là dài thời ra
[00:08:15] buổi hôm nay rất là dài mình sẽ dạy toàn
[00:08:18] toàn bộ về virus của Swift các thứ áp
[00:08:21] dụng kiến thức công trước gạch Nói chung
[00:08:24] là từ bỏ hôm trước rồi các bạn đã sẽ
[00:08:26] phải khá là thấy mức độ khó tăng dần rồi
[00:08:28] bởi vì nó liên quan đến viên lập trình
[00:08:32] thiếu cầu kiến thức mới buổi hôm nay áp
[00:08:35] dụng kiến thức đấy luôn Sau đó gì bởi
[00:08:37] Hôm sau nữa lại không Ôn tập lại gần như
[00:08:40] là không có ôn lại các bạn sẽ chỉ có làm
[00:08:44] bài tập để mà tự ôn thôi Ừ đúng ạ Các
[00:08:46] bạn nếu mà làm bài tập xong mà vẫn quê
[00:08:48] mình chắc là các bạn sẽ phải tự nghĩ đến
[00:08:52] bài tập về làm tự nghĩ trên đề là
[00:08:56] em chưa gần như là không không thể buổi
[00:08:59] hôm nay thì ôn tập bấm trước tập đi học
[00:09:00] trên trường được
[00:09:03] lễ hội các bạn có video quay lại các từ
[00:09:14] Ừ cái vụ mình đề cập ở đây vệ sai chính
[00:09:16] tả ra clip này như thế mình sẽ nói qua
[00:09:21] việc khi mà kiểu ra skip các bạn kiểu nộ
[00:09:25] của Pháp có từ từ thứ thì nó sẽ không
[00:09:28] chạy ngoài việc nó không chạy thì nó sẽ
[00:09:31] như thế nào sẽ lỗi như là nhìn chị xem
[00:09:33] lỗi như nào và nó có gửi ảnh hưởng như
[00:09:40] từ hôm nay nhiều ông muốn xui à
[00:09:43] Ừ không sao mấy ông xem lại tôi tôi thấy
[00:09:46] được à nó không xem lại nhiều mà mày
[00:09:49] không lượng người xem ví dụ giả thứ bây
[00:09:52] giờ xem có đúng mấy trăm thôi nha em ơi
[00:09:55] à mà khi mà xem video thấy giờ lên hơn
[00:09:58] nhìn anh một lần ấy ông kia xem đi xem
[00:10:01] lại hay là hay là gấu có mấy ông hiểu
[00:10:08] Cho tôi xem lại video tôi Tôi cảm thấy
[00:10:10] cũng phải
[00:10:14] cũng phải tua nhanh lên Đấy mình quen
[00:10:18] nhiều U nói chậm rồi Lên cầu xem video
[00:10:19] lại mấy cái tô nhanh
[00:10:23] là thứ da cơ thể dễ học miễn là có xem
[00:10:25] kiểu live chat như này các bạn dễ hình
[00:10:36] a Tiếp theo là cái câu này thì ra hôm
[00:10:38] trước đang định bảo là
[00:10:39] ở
[00:10:41] các tiệm vẫn bé
[00:10:45] Em không hiểu Mọi khi mình vẫn đang nói
[00:10:46] như thế này nhỉ
[00:10:51] Em có biết có thay đổi gì không alo
[00:11:01] anh alo alo alo
[00:11:03] Em không biết được không biết bé hay như
[00:11:17] em vừa rồi mình mình không chỉnh gì cả
[00:11:20] Không biết được nó ảnh hưởng gì không ạ
[00:11:23] anh alo Naruto hơn chưa
[00:11:27] à à Lại
[00:11:35] a Tiếp theo là cái vụ ngoan đúng không
[00:11:40] trùng hôm trước là tôi định cho câu này
[00:11:46] Ừ ừ đúng rồi tôi tôi
[00:11:49] tôi đeo tai nghe mà tai nghe tôi để mà
[00:11:52] biết được xem mình nói toi bé thì có vẻ
[00:11:55] Tôi vừa rút ra cắm lại có vẻ thế To hơn
[00:11:58] nữa Chắc là bây giờ nói to rồi
[00:12:02] ờ ờ cái vụ Lan đâm Không chồng thì hôm
[00:12:04] trước định cho có sao cuối cùng vì quên
[00:12:07] mất thì à
[00:12:09] từ hôm nay nữa không có thời gian giải
[00:12:13] đáp Hôm nay tôi sẽ cho nó lành câu sao
[00:12:18] dễ cho nó ra để mà không nào dạy và hôm
[00:12:20] sau nữa tôi sẽ chữa bài không sao buổi
[00:12:24] ờ ờ
[00:12:27] cái câu bao giờ học xong
[00:12:30] Ừ cái cái có mày thật ra thì không biết
[00:12:33] là không chớp mình chả được nghỉ
[00:12:36] cách cài 3G học xong của của bạn này nó
[00:12:37] rất rộng
[00:12:41] Vì vậy các bạn thì sẽ chẳng giờ học xong
[00:12:43] cả theo kiểu là đến bây giờ bản thân
[00:12:46] mình theo ngành lập trình này đến bây
[00:12:48] giờ mình vẫn phải học Mình vẫn phải học
[00:12:51] nhá thì học rất nhiều thứ và còn rất
[00:12:55] nhiều thứ cảm thấy kiểu chẳng hề chẳng
[00:12:57] hiểu gì cả chẳng biết gì cả
[00:13:01] Ừ nhưng mà nhưng mà kiểu mình cảm thấy
[00:13:02] là
[00:13:04] khi mình đã đến nó cái ngưỡng mà kiểu
[00:13:07] nói chung là cũng hơn được khá nhiều
[00:13:09] ở nhà phải dùng từ hơn được khá nhiều ở
[00:13:11] vịt kiểu
[00:13:14] ạ bây bây giờ cậu
[00:13:16] Ừ cái
[00:13:22] anh nghe cái trang CV của mình kiểu được
[00:13:25] khánh khá nhiều kiểu nhà Tuyển dụng kiểu
[00:13:28] nhắn tin tôi cảm thấy rồi cũng tự hào
[00:13:30] phết khi mà kiểu họ săn đón mình các thứ
[00:13:33] thứ họ đã ngộ mình các thử thứ thì lúc
[00:13:37] đấy mới cảm thấy là kiểu mình à
[00:13:41] khi mình học và được xứng đáng đêm đền
[00:13:42] đáp các thứ thứ
[00:13:46] Ừ cái cái việc đấy nó khác với nhiều
[00:13:50] ngành chiều Các bạn có thể 3 4 năm kinh
[00:13:52] nghiệm ở những hình khác thì nó không
[00:13:54] bao giờ săn đuổi bằng cái ngày này mình
[00:13:56] đang cảm thấy thế
[00:13:59] ở các ngành khác thì có bạn sẽ phải đi
[00:14:01] kèm với cả bằng cấp rồi Vân Vân mối quan
[00:14:02] hệ giữa xử lý nữa
[00:14:06] em phải có tặng em tên tuổi luôn Vân nữa
[00:14:08] còn không cho ngành này các bạn sẽ cần
[00:14:10] đến tuổi gì cả các bạn chỉ cần cộng với
[00:14:14] cv có cậu có năng lực thật sự họ sẽ cầu
[00:14:17] đãi ngộ của bạn do tốt Thế nên là mình
[00:14:27] A và còn cái ý bao giờ học xong của bạn
[00:14:35] Ừ nếu mà theo kiểu
[00:14:35] từ
[00:14:39] khóa học này của mình gì Ừ thì chắc à
[00:14:44] bây bây giờ là học ra Swift xong này
[00:14:47] có thể tuần này chắc là xong ra Swift
[00:14:52] này sau đó đi học p p p thì mình sẽ cũng
[00:14:55] không nhắc lại bên lập trình như là cũng
[00:15:00] sẽ khá là nhanh để mở từ P sang kết hợp
[00:15:02] với máy kia Word để mà
[00:15:06] anh hình dung về toàn bộ các tính năng
[00:15:09] kiểu đầy đủ tính năng xem thêm sửa xóa
[00:15:11] xông vào đăng nhập
[00:15:16] đăng nhập đăng ký ạ đó sau đó thì à
[00:15:20] mình mình sẽ ghét toàn bộ tất cả từ đợi
[00:15:22] các cài đấy lại để mà làm ra được một
[00:15:25] cái trang web cơ bản
[00:15:28] ở một trang web lúc đầu trang web 3tin
[00:15:32] tức sau đó đã làm trang web bán hàng
[00:15:34] Ừ Thì
[00:15:38] có mấy cái đấy Mỗi buổi mình sẽ lại để
[00:15:41] mô từng tính năng 1 của mình cái trang
[00:15:44] web ấy thì chắc là tầm mà
[00:15:47] anh có thể hai tháng nữa hai tháng hai
[00:15:49] đang rưỡi nữa là sẽ dậy sóng hết
[00:15:52] trong thời gian đấy các bạn cũng lúc lúc
[00:15:56] mà bắt đầu làm lúc bắt đầu làm mấy cái
[00:15:58] trang web tin tức tất cả
[00:16:01] bán hàng đấy thì các bạn cũng sẽ được
[00:16:05] chia nhóm để mà ghép nhóm với nhau để mà
[00:16:09] làm đề tài luôn thì à
[00:16:12] Vì sao bỏ đi chắc là chó các bạn thời
[00:16:15] gian để mà các bạn à hoàn thiện cái đồ
[00:16:18] An đấy để mà
[00:16:22] Anh ở sau đó tầm một tháng có thể thế
[00:16:27] ai chả thế để mà các bạn
[00:16:29] các bạn bảo vệ không ạ
[00:16:32] em à nhưng mà trăm về rồi năm tháng đấy
[00:16:34] mình cũng sẽ hướng dẫn các bạn cách bảo
[00:16:36] vệ như nào cách làm tài liệu như thế nào
[00:16:39] cần ngoan vân nóng ạ Vì mà nói chung mà
[00:16:43] các bạn sẽ hiểu qua về cái
[00:16:48] tiến trình là một cái dự án một cái sản
[00:16:50] phẩm công nghệ thông tin
[00:16:53] Ừ từ đầu đến cuối từ việc làm tài liệu
[00:16:56] thuyết trình làm Powerpoint
[00:16:58] và sau đó thì
[00:17:01] làm ra cái sản phẩm Phân tích các thứ
[00:17:06] thứ xe tải thì nó sẽ là như thế nào
[00:17:08] và đương nhiên là
[00:17:12] thì mình sẽ còn cả việc chữa cho các bạn
[00:17:12] nữa
[00:17:16] anh có chắc là những buổi những buổi để
[00:17:19] nói chung nhà 1 tháng đấy sẽ không hiểu
[00:17:23] mình mất tích mà là sẽ chữa bài cho các
[00:17:27] bạn cũng như hỗ trợ các bạn gì đấy hỗ
[00:17:29] trợ cho anh chị hội chợ online nội dung
[00:17:31] mới có thừa thứ thôi chứ không không
[00:17:45] ạ Bây giờ thì tranh thủ cho các bạn ạ Có
[00:17:48] ông vừa nãy hỏi về cái vụ mà chữa bài
[00:17:50] hôm trước
[00:17:53] em là cây bài mã màu không ạ
[00:17:56] anh được tí nhớ nhỏ nhắc mình sửa chữa
[00:18:09] Ừ mình mới Xem lại video này buồn cười
[00:18:13] chết mình cho bạn xem nữa Biết rồi quết
[00:18:14] rồi
[00:18:26] break the Style
[00:18:32] of What we got it during video
[00:18:48] gadus amedred
[00:18:59] meat grinder
[00:19:05] welfare of
[00:19:10] What we have all of which one you love
[00:19:14] days ago since when i
[00:19:17] anh ạ
[00:19:21] các bạn Các bạn xem mấy giờ rồi thực
[00:19:25] thực tế Nó là kiểu đi
[00:19:27] em làm lập làm được trình mình như thế
[00:19:30] giờ người dùng sẽ Kiều dùng gái rượu của
[00:19:34] vần ông ạ Mà kẹo mình mình cho rất nhiều
[00:19:37] cái đầu để mà nhập vào nhưng mà nó chỉ
[00:19:39] nhập vào đúng cái chẳng hạn thế
[00:19:43] Ừ thì đấy đấy buổi hôm nay mình sẽ học
[00:19:45] cái đét là để kiểm tra việc của người
[00:19:48] dùng nhập vào như thế nào thông báo cho
[00:19:49] người dùng như thế nào là chuyện người
[00:19:51] dùng hiểu không ạ
[00:19:52] ở
[00:19:54] đâu rõ ràng hướng dẫn các từ có chứa
[00:19:58] trong nó hẹ rõ ràng như kiểu hiển nhiên
[00:19:59] như thế ở nhau người dùng vẫn phải nhập
[00:20:02] sai người dùng cố tình như thế hỏi người
[00:20:03] dùng
[00:20:06] hiểu chưa Dùng máy tính bao giờ nhăn
[00:20:18] Ờ Ờ
[00:20:23] mình trả lời nói câu này Ờ học file thì
[00:20:26] nên chọn phương Quốc nào nó tương tự
[00:20:28] giống như là kiểu mình sẽ từng nói qua
[00:20:30] việc học cũng giống cho học ngôn ngữ lập
[00:20:35] trình Vậy thì bạn sẽ thì ở các bạn đương
[00:20:37] nhiên là vẫn nên tìm những cái mà kéo
[00:20:40] lên phổ biến phổ biến một phần nào để mà
[00:20:43] sẽ đi làm vệ sinh việc vân vân và cũng
[00:20:47] như cộng đồng Hỗ trợ nó rất là ôi
[00:20:50] xã hội hỗ trợ ở đây hỗ trợ việc mà
[00:20:52] Ngôn ngữ này nó còn phát triển lâu dài
[00:20:55] chứ không phải nó chuẩn bị sắp thành
[00:20:57] ngôn ngữ đã chết cũng như là
[00:21:02] các bạn tra lỗi nó nó xảy ra tra tài
[00:21:04] liệu nó có ra rất nhiều mà đôi khi là
[00:21:06] các bạn điển hình gần đây mình làm để vụ
[00:21:10] là Google api về mà nhận nhận diện giọng
[00:21:13] nói được ạ thì cái Mun Ngôn ngữ này nó
[00:21:16] có hỗ trợ tài liệu để mà đọc 20 các thứ
[00:21:20] thứ đấy thì mai mai mà mình mình đọc
[00:21:23] thấy có vải có vài ngôn ngữ có đúng ngôn
[00:21:24] ngữ của mình
[00:21:26] Giả sử một mấy cái thằng này mà không có
[00:21:29] ngôn ngữ của mình thì chắc là mình thì
[00:21:31] sàng đầu tiên tiên phong là vụ đấy xác
[00:21:41] em vừa cách tra phương Quốc Ở đang đang
[00:21:44] rượu đang đứng đầu thì các bạn Phim Quốc
[00:21:47] tốt ngày hay cái gì đó vương quốc 20 21
[00:21:49] 2022 này
[00:22:02] gà qué tự tạo bằng việc kéo tha
[00:22:05] AE theo kiểu lướt web so web tạo bằng
[00:22:07] cốt thì cần nó chạy nhanh hơn
[00:22:10] cho nó luôn là web chạy bằng Cốt nó sẽ
[00:22:13] chạy nhanh hơn thế là cái câu web chạy
[00:22:16] bằng chạy bằng cốc thì nó hơi sai vì vừa
[00:22:20] cơ bản cả hai nó để tạo bởi cốt chẳng
[00:22:23] qua là à Cả hai đều chạy bằng cốt chẳng
[00:22:25] qua là cái cái việc kéo thả thì nó sẽ tự
[00:22:29] sinh ra cốt còn việc tạo bởi cốt thì nó
[00:22:31] tạo bởi cốt Thuần dưỡng mình tự gõ đúng
[00:22:34] không Thì cái việc tự sinh ra cốc thì nó
[00:22:38] nó có bài toán là nó sẽ sinh ra thự kiểu
[00:22:39] là
[00:22:42] đôi khi không tối ưu thứ nhất là nó
[00:22:43] không có tất cả trường hợp
[00:22:46] đã có rất nhiều trường hợp mà kiểu mình
[00:22:49] không muốn nó lại có mặt thừa dữ liệu a
[00:22:54] và và kiểu nó không Tuy chỉnh nó cho là
[00:22:56] không tùy chuyển và không tối ưu ái nó
[00:22:59] luôn là 2 yếu tố đấy thành cho thành ra
[00:23:02] được web tạo bởi kéo thả thì nó nhanh
[00:23:05] nhưng mà nó rẻ web tạo bởi cốt thì nó
[00:23:08] kiểu tắt hệ thống nhà làm cái trang bằng
[00:23:12] gỗ vest giá 1 triệu có 3 triệu tầm tầm
[00:23:15] tầm đấy thôi còn web mà tạo bởi cốt thì
[00:23:19] giá nó luôn là 10 20 triệu đấy Đấy là ít
[00:23:21] nhé Vậy có nhiều ở trang web bây giờ
[00:23:24] Điền hình các phần mềm được 100 triệu có
[00:23:30] anh nghe Kiều Hoa
[00:23:34] thì các bạn so sánh Thế thì nó là bởi vì
[00:23:37] thời gian để mà làm cái đấy nó khác nữa
[00:23:41] tạo bởi web tạo bởi kéo thả thì có thể
[00:23:43] một người không cần biết ngôn ngữ lớp
[00:23:45] chính chỉ cần biết qua Dùng cái đấy
[00:23:48] trong vòng một tuần người ta vừa học vừa
[00:23:50] làm đã làm xong một cái trang web đầy đủ
[00:23:53] tính năng rồi còn để mà
[00:23:57] tư vấn đề mà học từ đầu đến cuối để mà
[00:24:00] làm 5 cái trang web làm tất cả tính năng
[00:24:03] bằng cái cái trang web đó là kia chưa
[00:24:06] chán các bạn mất phải 34 tháng này ít
[00:24:09] ở đấy chưa nói mình đón tối ưu
[00:24:12] khi nó mới chỉ ở chỗ nào mới biết cốc
[00:24:14] thôi còn tối với ở đây là tối ưu về việc
[00:24:16] tối ưu cho nó chạy nhanh này kết hợp với
[00:24:17] việc là
[00:24:21] chỉ cốt sao cho để mã về xã hội khách
[00:24:23] hàng mà một thêm tính năng mới muốn thay
[00:24:25] đổi cái gì đó thì dễ thay đổi chẳng hạn
[00:24:29] thì cái đấy các bạn học phải hai ba năm
[00:24:33] ấy lúc đấy chưa Sẵn cái kinh nghiệm với
[00:24:34] nó sẽ
[00:24:37] sẽ đòi hỏi tiền không ạ Các bạn nghe về
[00:24:41] vụ nhát búa 1.000 đô 50.000 đô rồi rồi
[00:24:56] anh nghe có mùi giống nhờ mấy cái ông
[00:24:58] lớn đi lại
[00:25:01] Ừ ok Nói chung là bây giờ đến giờ học
[00:25:05] rồi đầu tiên thì hôm trước có mấy ông
[00:25:11] đang cái mê cày cốt freegate mày cái mã
[00:25:13] túi rách của mấy ông Thực ra tôi xin
[00:25:16] phép chia sẻ mấy ông thực ra không để ý
[00:25:19] việc là cái trang này có thể đăng nhập
[00:25:22] Ở trang này có gì em nhỉ
[00:25:25] ạ Và nếu không có thể đăng nhập xong thì
[00:25:29] bị ông có xếp li cách này sau đó với mấy
[00:25:32] ông chia sẻ mấy cái link đấy bạn thân
[00:25:36] tôi cũng cũng từng đăng nhật để mà lưu
[00:25:37] lại mấy cái
[00:25:46] Ừ thôi để tôi làm cái rách cả tài địa
[00:25:51] chỉ họ tên thế họ tên đầy đủ à
[00:25:55] ở các giàu ai về tôi đi có mà ở đây mấy
[00:25:59] ông Chaly Cách tiếng Việt là dao như có
[00:26:00] mùi gõ thì vậy
[00:26:07] a a a
[00:26:10] có thể rút ra trường hợp A Hồi đấy rồi
[00:26:13] nhớ có trường hợp ở đây Hình chưa có một
[00:26:16] cái trường hợp ở đấy đợi cha ấy tự nhiên
[00:26:21] không không có chữ thế thôi tự nhiên tôi
[00:26:23] cậu một bắt được cái lỗi đấy tôi phải
[00:26:24] muốn sửa lại cái chữ tự nhiên phải thêm
[00:26:25] chữ ế
[00:26:33] anh qua đây Tôi làm gái cả về
[00:26:36] link Facebook hay các thứ thứ cái đấy
[00:26:38] cho về sau tuổi chia sẻ thêm người ôm
[00:26:40] sao vậy mày không hình dung được cách nó
[00:26:43] thể làm những gì nhưng đây Nói chung vào
[00:26:45] mấy ông làm này xong rồi mày không có
[00:26:46] thể chia sẻ này
[00:26:49] ạ bấm bấm vào để đào tạo đến trưa xe thì
[00:26:52] ổn hơn nữa có gửi cái đoạn cốt kia vừa
[00:26:55] chia sẻ kia là chia sẻ luôn cả những cái
[00:26:57] trường hợp mà Mấy ông đã test người ông
[00:26:59] đã kiểu ghi
[00:27:02] a ghi các trường hợp ra để tôi nhìn qua
[00:27:05] nhưng có là việc tôi sẽ đánh giá luôn
[00:27:07] này việc là mấy ông kỹ các trường hợp để
[00:27:09] mà test như thế nào chứ không phải về
[00:27:11] mỗi cốt không ạ
[00:27:15] ở mỗi cốc thì tôi nhập vào đúng thì có
[00:27:17] thể nó vẫn chạy đấy nhưng mà nhập sai mà
[00:27:20] nó vẫn báo đúng thì là vấn đề ngay đúng
[00:27:29] Ừ cái câu này mình xin phép ta
[00:27:32] em trả lời sau trở giao động
[00:27:35] Ừ cái này dùng quyết được cái này dùng
[00:27:39] rách được ta làm sao biết email đồ có
[00:27:43] tồn tại không hôm trước và hôm trước có
[00:27:45] bạn hỏi câu này Hôm trước mình mới chỉ
[00:27:48] làm verde để kiểm tra Email nhập hợp lệ
[00:27:52] còn việc là nó giống như kiểu tên nó hợp
[00:27:55] lễ Ê chúng mày còn việc Tên nó có đúng
[00:27:57] là tên người không chẳng hạn thì phải
[00:27:59] hỏi họ đúng không thấy dùng cái gì đó
[00:28:04] chứng minh họ là thưởng tuổi hợp lệ tuổi
[00:28:07] thật thằng Đản đúng không ạ thì cái
[00:28:09] email là anh thế cách để kiểm tra Email
[00:28:11] của tôi tại không mình chỉ an toàn họ
[00:28:14] lại họ bằng cách gửi mail cho họ đấy là
[00:28:15] một cách
[00:28:16] Anh
[00:28:19] thường là thường là làm như thế thôi ta
[00:28:23] Nó có bị nhược điểm một tí đó là việc
[00:28:27] gửi mail cho họ đôi khi sẽ rơi vào ở thư
[00:28:30] mục giác của họ cũng như là gửi mail
[00:28:33] người ta cũng tốn phí đó nhá gửi mail
[00:28:36] hay gửi tin nhắn qua số điện thoại nó
[00:28:39] tốn phí nên thành ra là
[00:28:43] Ừ anh nên thành ra là kiểu nó cũng hơi
[00:28:46] bị nhược điểm tí nữa là có nhiều cách đó
[00:28:49] là vẫn chí là ông có thể kiểm tra quay
[00:28:52] qua bên thứ ba trước mình Thứ ba là một
[00:28:55] vài bên những cái bên mà nó thường ấy
[00:28:57] cung cấp máy cần mau ra đấy đấy Nếu
[00:28:59] không có người kiểm tra qua chính này
[00:29:02] cái mấy cái Trang đấy trước và kiểm tra
[00:29:04] xem mail này có được đánh đăng ký Bởi
[00:29:07] bởi mấy cái trang này không nghe Chứng
[00:29:08] tỏ là em yêu này được đăng ký rồi một
[00:29:12] cái trang music giống kẹo cái mail
[00:29:15] ten-minute Milk
[00:29:18] có mail cỡ này nghĩa là có những cái
[00:29:20] mail mà cả các bạn muốn năm ký một cái
[00:29:24] gì đỏ nhanh ở các bạn chỉ muốn hiểu nó
[00:29:28] gửi về cho các bạn một cái gì đó
[00:29:31] một cái đoạn Mã gì đó rồi Các bạn đăng
[00:29:33] ký mua gì bỏ ngang và các bạn sẽ chẳng
[00:29:36] mơ vào lại thời trang này nữa thường vào
[00:29:39] đấy để tải một cái gì đó đôi khi các bạn
[00:29:42] không ở spam quảng cáo các bạn về sau
[00:29:44] không muốn lưu lại nếu các bạn về sau
[00:29:47] thì đây Có những cái trang kiểu nó sẽ
[00:29:49] tạo cho các bạn một cái mail kiểu như
[00:29:51] thế này và hoàn toàn các bạn sẽ nhận
[00:29:56] được tin cậy Miu nào đó gửi vào cho các
[00:30:00] bạn qua đây Đấy Và mail này sẽ chỉ tồn
[00:30:01] tại trong vòng 10 phút mười phút sau
[00:30:04] được cái mail này sẽ bị xóa mây ở phù
[00:30:06] hợp cho việc là kiểu các bạn đi đăng ký
[00:30:10] ở để lấy kiểu kiểu như thế
[00:30:14] Ừ đấy thi thì chính cái những cái kiểu
[00:30:16] như này gọi là Nêu giác này trước cửa là
[00:30:19] nó sẽ kiểu nó
[00:30:22] để nhận biết được nó lại phải kiểm tra
[00:30:25] xem chính cái b thứ ba trên chính những
[00:30:28] cái trang này xem mail có đăng ký ở trên
[00:30:35] Ừ
[00:30:39] vợ kiến thức mới giống mình thì
[00:30:42] à mình làm được trình mai biết mấy cái
[00:30:53] thì các bạn phạm luật trình xong các bạn
[00:30:55] sẽ biết được có rất nhiều cái kiến thức
[00:30:56] mới theo kiểu là
[00:31:00] cứ nail giả cảm giác như vừa rồi từ việc
[00:31:02] là kiểu tại rất nhiều ông Làm lập trình
[00:31:06] tạo ra rất nhiều cái nó khó hiểu lắm
[00:31:08] nhưng mà nó tiện nhưng mà nó khó hiểu
[00:31:10] lắm kéo các bạn sẽ không đồng ý Ôi có
[00:31:13] người làm cái này rồi à cái rồi Thế các
[00:31:15] bạn đôi khi và thỉnh thoảng phải tra xem
[00:31:18] người việc có thằng nào làm đấy chưa khi
[00:31:21] mà hồi học lập trình ở tôi bộ Tôi bị như
[00:31:24] thế đấy Đó là luôn luôn tra xem là có
[00:31:26] nào đã làm cái này chưa phải chuyện ra
[00:31:28] là có rất nhiều ông đã từng nghĩ về việc
[00:31:31] đấy và làm cái đấy rồi đấy nó giống như
[00:31:34] kiểu phát minh vĩ đại vậy thế
[00:31:35] Đó
[00:31:38] là những cái này cái quan trọng ở những
[00:31:39] cái này thì chị Bọn tôi biết thôi Bọn
[00:31:42] tôi ít khi mà công khai cho cho tất cả
[00:31:45] mọi người cùng biết Liên là Nhưng mà
[00:31:48] thỉnh thoảng có một vài không công khai
[00:31:50] cái đấy xã chẳng hạn đăng lên Tik Tok
[00:31:54] không ạ whey bao nhiêu ông vào đâu được
[00:31:56] Cảm thấy có được khai sáng thứ nhưng thử
[00:31:58] ta với người dân trong nghề như vợ tôi
[00:32:02] thì nó là điều quá hình những kiểu biết
[00:32:03] từ lâu lắm rồi
[00:32:09] Ừ thế là tôi đang nghĩa là tôi chia sẻ
[00:32:11] cho mấy ông thỉnh thoảng tôi sẽ chia sẻ
[00:32:14] mấy cái kiểu có thể như thế nhưng đâu
[00:32:22] ai nói học và Tik Tok không ạ mái tóc
[00:32:24] đôi khi những cái bịp đấy Chẳng qua gặp
[00:32:27] mấy ông gần hết trong nó vôi thưa mấy
[00:32:31] ông ông đang ở trên Tik Tok thì cũng
[00:32:33] kiểu để câu được xem chủ yếu chứ
[00:32:38] thứ kiến thức có khi chưa chắc là chuẩn
[00:32:43] Ừ
[00:32:47] Ok Thôi giải dám qua em nói chung đến 3
[00:32:49] hôm nay thì bài hôm nay nó sẽ sinh ra
[00:32:53] một vấn đề như thế này ờ bài hôm nay ở
[00:32:55] sinh năm gần đây như thế này Tại sao tự
[00:32:57] nhiên hôm nay mình sẽ học đấy cái khái
[00:33:02] niệm là validate form thì đầu tiên là
[00:33:05] như vừa nãy mình có đề cập dịch vụ là
[00:33:07] kiểm tra cho người dùng nhập đúng đúng
[00:33:10] không ạ Tức là xa thì tại sao lại phải
[00:33:12] kiểm tra người dùng nhập đúng
[00:33:15] thì mình sẽ ra hỏi lại câu đấy ông ạ
[00:33:18] ở đó đó là giờ sửa D1 Phong đăng ký hả
[00:33:20] đúng không ạ Phong đăng ký của người
[00:33:24] dùng và người dùng nhập bên ta tinh cũng
[00:33:26] được chấp nhận thì ra là không nên như
[00:33:29] thế đúng không ạ Đấy do mình sẽ kiểm tra
[00:33:32] nào ạ nhưng mà tự nhiên ở đây lại có bài
[00:33:34] toán nữa tự nhiên tại sao lại kiểm tra
[00:33:37] bằng Switch đúng không ạ Hôm trước đã
[00:33:40] từng của bạn hỏi là em kiểm tra bằng
[00:33:43] ngôn ngữ ở bên bác em và ngôn ngữ xử lý
[00:33:45] ở server được không ạ
[00:33:49] Ừ cái cái này khái niệm này nó hơi bị
[00:33:52] nó hơi bị lạ với các bạn thì các bạn còn
[00:33:54] chưa biết bác em là gì thì mình cho xin
[00:33:56] phép cho các bạn xem cả
[00:33:58] vides Tom nhạc
[00:34:02] Em không biết có ảnh này không Để mình à
[00:34:13] em có cái ảnh sơ đồ để mà các bạn dễ
[00:34:22] Ừ cái này cũng tương tự cái này được này
[00:34:35] Ừ cái này trông có vẻ nhiều chữ hơn nhỉ
[00:34:37] Không thích kiểu nhiều chữ quá ngay Mình
[00:34:39] mình không thích nhiều chữ đâu Mình nghĩ
[00:34:49] Ừ cái này trông kiểu đúng kiểu Yeah được
[00:35:00] 10 cái này lại thiếu thiếu thông tin mất
[00:35:01] rồi
[00:35:04] ừ thôi lấy tạm cái này nhé Cái này sẽ là
[00:35:07] sao nghĩa là gì
[00:35:10] ờ ờ ờ
[00:35:13] ý nghĩa là đầu tiên thì mình sẽ xử lý
[00:35:17] virus ở phía client tức là phía phía
[00:35:19] người dùng rất là cụ thể là chân chính
[00:35:22] máy của người dùng mình sẽ ngồi kiểm tra
[00:35:25] bằng ra sweep trước là người dùng nhập
[00:35:27] Đúng là nhập sai ra quyết về sẽ chạy lên
[00:35:29] chín cái trình duyệt của người dùng là
[00:35:32] chương trình máy người dùng ngoạn
[00:35:36] sau đó thì nhưng mà kiểm tra thì vẫn chỉ
[00:35:39] kiểm tra ở một mức tương đối được tương
[00:35:41] đối tại sao mình lại dùng từ tương đối
[00:35:45] bởi vì a giống như là như vừa rồi có đề
[00:35:49] cập là giả sử là mình chỉ kiểm tra được
[00:35:52] là người dùng nhập email có đúng cú pháp
[00:35:55] hay không chứ mình không kiểm tra được
[00:35:59] là được email đấy có có tồn tại hay
[00:36:00] không mình không kiểm tra rồi đấy ở trên
[00:36:04] máy này dùng được mà mình sẽ mình sẽ bị
[00:36:07] đẩy về trên server để mình kiểm tra
[00:36:09] trong server trong server của mình
[00:36:12] nhờ server mình sẽ thông báo lại cái
[00:36:14] email đấy có thể gửi mail cho chính nó
[00:36:18] xong rồi server xác nhận sau đó đi trả
[00:36:20] về cho khách hàng là email để hợp lệ rồi
[00:36:23] ạ thì server sẽ làm cái vụ kiểm tra Lặng
[00:36:24] Bước cuối
[00:36:28] mà tại sao lại phải gọi dùng thực kiểm
[00:36:32] tra bất cuối bởi vì ạ thực tế ạ là người
[00:36:33] dùng có thể tắt được de Suite ở trên
[00:36:35] chính máy của họ là sửa như thế này các
[00:36:36] bạn ấn vào
[00:36:39] và một trang web bất kỳ này các bạn ấn
[00:36:42] vào đây này Ở no size setting này ấn vào
[00:36:45] ra Swift này mặc định nó đang ở lao
[00:36:48] nhưng các bạn thì ấn Vlog như thế này mà
[00:36:50] các bạn tải lại trang là là cái Trang
[00:36:53] đấy sẽ không bơ được chạy ra súp nữa thi
[00:36:55] thì sẽ không dùng Speed để mà virus được
[00:36:58] dữ liệu
[00:37:01] Vì thế nên là thế thì nên là kiểu gì
[00:37:04] server cũng sẽ phải kiểm tra bước cuối
[00:37:07] nếu mà trong trường hợp mà da súp ít bị
[00:37:09] tắt hay là thậm chí là người dùng có thể
[00:37:12] ghi đè ra Switch của các bạn vì như lần
[00:37:14] trước mình có đề cập và các bạn ở Mỹ
[00:37:17] Spec này cần con show này xong rồi các
[00:37:20] bạn trình một cái gì đó
[00:37:23] a gỗ kouji a xít vào trong ngày là đồng
[00:37:26] nghĩa là ra Switch cũ nó sẽ bị ghi đè
[00:37:29] lên theo kiểu là ghi đề hàm hay các thứ
[00:37:35] thì thì thì nó sẽ nó sẽ kiểu bọ Nói
[00:37:38] chung là bỏ qua họ rất nhiều cách để mà
[00:37:40] lách bởi vì trên máy người dùng mà nên
[00:37:41] thành người dùng làm cái gì chẳng được
[00:37:44] đóng ạ nên thành ra là server võ vạch
[00:37:47] kiểm tra quá cô ấy
[00:37:49] Ừ thì có bạn sẽ thắc mắc ở đây cái Tại
[00:37:52] sao làm server kiểu dáng phải kiểm tra
[00:37:56] Tại sao em lại không em không để sâu với
[00:37:58] kiểm tra thôi em bỏ qua ở trên máy người
[00:38:01] dùng bởi vì ở đây bài toán đấy Giả sử là
[00:38:04] giả sử như thằng Facebook chẳng hạn
[00:38:06] Facebook nó có
[00:38:10] bây giờ hiện tại truy cập lượng truy cập
[00:38:13] đồng thời đang có đang phải trăm triệu
[00:38:16] trăm triệu lấy ít người đang cùng dùng
[00:38:20] cùng một lúc Đông ạ Nếu mà cứ đẩy lên
[00:38:23] server rồi server mới kiểm tra thì quá
[00:38:25] tải cho server đó ngoại hay bị như thế
[00:38:28] chính máy của người dùng sẽ kiểm tra
[00:38:32] trước và kiểu Nếu mà không hợp lệ thì
[00:38:34] thông báo lỗi luôn để mở server đỡ phải
[00:38:37] kiểm tra anh chỉ có những người ông nào
[00:38:40] mà lách được quà không phải ông nào biết
[00:38:42] cách làm à lách không ạ thì mình mới
[00:38:45] phải kiểm tra bước cuối thôi nhưng mà
[00:38:48] thư gan mà ra thằng cũng Nhân tiện đây
[00:38:50] nói với thằng Facebook thì thực ra thằng
[00:38:52] Facebook kiểm tra vài biết ở server lại
[00:38:55] rất là yếu xảy ra ở rất nhiều ông thấy
[00:38:57] có trường hợp là tên người dùng nhập
[00:39:00] được tên kí tự đặc biệt hai đoạn trích
[00:39:02] tên người dùng không có tên không phải
[00:39:04] không có TN Chẳng qua người Nhật ký tự
[00:39:07] đặc biệt Thành kiểu dấu nó là phải
[00:39:09] khoảng không ấy đáng ra nhiều dạng như
[00:39:12] tên không có tên đấy có chứa không có
[00:39:15] ảnh này vào vần bởi vì thằng thằng
[00:39:19] server của Facebook nó đang hạn chế việc
[00:39:21] kiểm tra dữ liệu
[00:39:23] anh Bởi vì cứ kiểm tra như thế sẽ làm
[00:39:27] nặng nặng về việc xử lý vì đôi khi một
[00:39:30] hàng muốn xử lý thời gian thực theo kiểu
[00:39:32] phản hồi cho người dùng nhanh thì nó sẽ
[00:39:35] phải tối ưu việc là làm gì cũng phải trả
[00:39:38] về kết quả nhanh ấy ạ ngày ra nó còn ăn
[00:39:40] bớt luôn để đoạn kiểm tra
[00:39:43] ở server nên nó kiểm tra ở trên máy
[00:39:45] người dùng cho nhanh
[00:39:47] và đương nhiên là mình sẽ không dạy các
[00:39:49] bạn những cái kiểu làm thủ thuật như thế
[00:39:52] mình sẽ dạy các bạn từ đầu luôn đó là
[00:39:54] kiểm tra trên máy người dùng Nếu mà
[00:39:59] người dùng kiểu 01 nợ một lần nữa mình
[00:40:01] vẫn sẽ phải kiểm tra lại bằng trên
[00:40:05] server trên tất cả trên Pad hoặc sự kiểm
[00:40:06] tra Thêm Một Lần Nữa
[00:40:11] gì đấy vừa rồi nói sơ qua việc mà là
[00:40:13] mình học cái này để làm gì ông ạ Thế bây
[00:40:14] giờ mình sẽ đi được bài tập làm luôn
[00:40:18] không ạ Mình sẽ làm lại một cái phone
[00:40:22] đăng ký Sau đó đi sẽ Varus luôn toàn bộ
[00:40:23] những thông tin cho và phong đăng ký đấy
[00:40:25] nghĩa người dùng không được phép để
[00:40:27] chống này người dùng bắt buộc phải điền
[00:40:38] Ừ mẹ xóa hết đi nó xóa hết cốt củ đi làm
[00:40:40] từ đầu
[00:40:42] ở đầu tiên thì đương nhiên là Phong đăng
[00:40:44] ký phải nằm trong thẻ form nó không ạ
[00:40:47] sau đó thì cậu tên này chẳng hạn
[00:40:49] như phút
[00:40:52] Tech
[00:40:55] Nên mình vẫn chưa dùng kia Mình học xong
[00:40:57] p mình sẽ dùng nêm này Bây giờ mình
[00:41:00] không dùng mình sẽ cho nóng cả ID
[00:41:03] tím mình sẽ giải thích tại sao dùng mai
[00:41:06] đi có thơ thơ à
[00:41:12] từ
[00:41:35] giới tính à input hay Radio này
[00:41:38] các bạn nhớ cái vụ Rio này thì lại bắt
[00:41:41] buộc phải có nêm Bởi vì nếu mà không có
[00:41:46] nêm thì nó sẽ cho chọn được đây
[00:41:51] hình mình cho bạn xem luôn kết quả mà gõ
[00:41:53] Xong nha
[00:41:56] để tránh sự đôi nam
[00:41:58] nữ này
[00:42:01] nếu mà mình không có nên trùng nhau là
[00:42:03] bao nhiêu nó sẽ cậu cho chọn điều kiện
[00:42:05] cả hai giới tính cùng một lúc nó ạ thì
[00:42:07] cho nó cái nêm đi
[00:42:11] về giới tính riêng thằng ngày thì mình
[00:42:14] không cho nói đi đâu ạ Mình sẽ chỉ cần
[00:42:17] lên như này được rồi mình còn lên như
[00:42:19] thế này là phân biệt để mình tím lấy cái
[00:42:24] nút thay A có in bút nên theo nêm là
[00:42:24] được
[00:42:32] à à
[00:42:33] ờ ờ
[00:42:36] suy tính có
[00:42:44] Em email chẳng nhận được email
[00:42:46] Push
[00:42:49] email im
[00:42:52] add ID email đi
[00:43:01] password này
[00:43:16] à à
[00:43:17] để
[00:43:21] mình thử cho 10 salad Ôsin nó bạn dễ
[00:43:25] hình dung nhé Đăng ký vào lớp đây sẽ
[00:43:32] khi bật trình
[00:43:35] và
[00:43:46] vào đây sẽ có một nút là nút đương nhiên
[00:43:49] là đăng ký đó ngoại này này nếu cái nút
[00:43:52] Bất Tận như thế này mặc định trong for
[00:43:55] mình nó sẽ là thay nó sẽ là sắp ít đúng
[00:43:56] không ạ Các bạn nhiều không ạ
[00:44:02] là như thế này Ok một form của mình khi
[00:44:03] mà mình đi ăn xong hết thông tin chẳng
[00:44:05] hạn như này không ạ mình điên hết thông
[00:44:08] tin thế này Và thậm chí ở mình không
[00:44:10] điều mình cần nút đăng ký nó vẫn nhận
[00:44:13] được luôn các bạn hãy nó nói lại cha như
[00:44:16] này tất cả mà đang nhận trả qua đó Đang
[00:44:18] chưa hiển thị thông báo là thành công
[00:44:20] hay thất bại cái gì đó thôi nhưng mà nó
[00:44:21] cứ load lại trang như thế này các bạn
[00:44:24] hình dung ra nhận rồi cái này ra đang
[00:44:27] say mọi việc như mình đã nói đó khi mọi
[00:44:28] người dùng không điền đầy đủ thông tin
[00:44:30] tại mình không được cho bấm nút đăng ký
[00:44:33] không ạ có bạn thì sẽ bảo là
[00:44:37] Ừ Ok em cho đoạn này free quite thì nó
[00:44:39] sẽ bắt buộc phải điền nữa đúng không ạ
[00:44:43] Các bạn nhớ không ạ thì thứ nhất à khi
[00:44:45] mình Họ ra Switch để Làm vedette thì
[00:44:47] mình không nên dùng cái qua được làm gì
[00:44:51] cả Bởi vì à Cái qua mà đúng Hồi đấy tôi
[00:44:54] cũng lười vai bếp và ra quyết tôi cứ để
[00:44:57] đi qua để bắt buộc phải điền như này bởi
[00:45:01] vì HT mà nó hỗ trợ mà nhưng mà do là cái
[00:45:02] hiển thị của 2 team lời như thế này các
[00:45:05] bạn thấy ạ đang hết toàn tiếng Việt nhà
[00:45:07] tự nhiên hiển thị ra tiếng Anh trong nó
[00:45:10] trải nghiệm với tôi này Đây là do trình
[00:45:12] duyệt tôi đang dùng học tiếng Anh mà
[00:45:13] thường này đúng là như thế Nhiều bông
[00:45:15] không biết cài trình duyệt thành tiếng
[00:45:18] Việt đâu chẳng hạn thế kết hợp việc là
[00:45:21] nó hiển thị thông báo đôi khi mà nó chỉ
[00:45:26] mức tương đối rồi nó hơn nó là kéo Ê bà
[00:45:30] không được để chấm vân vân chữ nó không
[00:45:33] kiểm tra được miễn cái hiểu mình muốn là
[00:45:35] ví dụ à Tên phải nhập đúng theo cậu là
[00:45:39] phải chữ cái đầu viết hoa giống như rùng
[00:45:41] mình dùng ghét không Trước nó nhọn cũng
[00:45:44] như là Email Email thì mai thằng này hỗ
[00:45:46] trợ email nó bắt buộc phải nhập Đúng rồi
[00:45:50] nếu còn mật khẩu ra mật khẩu nhà mình
[00:45:52] nói chung là sẽ cần dùng gạch ở một vài
[00:45:54] chỗ chẳng hạn thế
[00:45:58] Ừ thì mình làm như thế nào đúng ạ hoa
[00:46:01] Định tôi có những cái mình sẽ hỗ trợ lực
[00:46:03] tương đối giống như là cả ngày sinh này
[00:46:06] mình có thể dùng mạng kèm min max của
[00:46:10] thằng HCl hỗ trợ thì không cho để không
[00:46:13] cho việc nhập không Ngày sinh không
[00:46:15] chuyện sinh vào ngày mai ông ạ tôi không
[00:46:18] đến từ tương lai ở đây cái cờ thế và
[00:46:22] nhịn đấy mắt của nó có thể mình can
[00:46:24] thiệp như thế nhờ mình cứ thử can thiệp
[00:46:26] Thế bảo g-switch định thông báo lỗi ở
[00:46:28] đây thì như thế nào Ngoại
[00:46:31] lại vừa nói trường hợp với ông Chánh bắt
[00:46:32] bẻ được à
[00:46:35] Ừ cái này làm ở HTML được mà không mình
[00:46:38] chúng ta ở đây không làm thế
[00:46:40] à à
[00:46:43] ừ ừ
[00:46:46] Ừ để tiếng Việt nó vẫn nhỉ ý tiếng Anh
[00:46:49] hình như là cả trình duyệt và cả ngôn
[00:46:51] ngữ máy của ông để tiếng Việt thì may ra
[00:46:54] nói gì thì tiếng Việt thì vậy và đã bìa
[00:46:56] cái này còn tùy theo kỳ theo trình duyệt
[00:47:00] nữa theo kiểu là trình duyệt mỗi hình
[00:47:03] giờ thì nó hiển thị thông báo lỗi Xem
[00:47:04] mục kiểu
[00:47:07] anh Thành A hơi bị khó chịu để hình a ạ
[00:47:15] có ai test mày không nghe
[00:47:17] ừ ừ
[00:47:38] xe tải Nó kiểu như thế nào kiểu trải
[00:47:39] nghiệm người dùng công nghệ tốt cái đoạn
[00:47:42] đấy dạ mình thay vì như thế mình sẽ hiển
[00:47:45] thị ra kiểu thông báo lỗi ở ngay bên như
[00:47:49] thế này nó sẽ ổn hơn
[00:47:53] à Nhưng cái quan trọng ở đây đó là
[00:47:56] nó nó nó lại phải toán như này khi bấm
[00:47:58] nút thì mình sẽ One Click khi bấm nút
[00:48:01] này mình mình sẽ gọi đến cái Hàn là hạt
[00:48:08] Ừ
[00:48:12] thì mình sẽ có ra Swift à
[00:48:15] clip này
[00:48:25] Toàn chất là mình giả sử mình cứ vơ đét
[00:48:28] trước thằng tên lại nhé mình sẽ là nét
[00:48:33] tên bằng đó của mình ghét em mình body
[00:48:38] tên Maru lấy cái tên mình nhập về lịch
[00:48:40] sử là tên không được phép để chồng nó ạ
[00:48:45] Tức là độ dài của chuỗi tên ạ không đều
[00:48:49] bằng 0 là được Tạm thời như thế ít
[00:48:55] tên chấm nem là độ dài của chỗ tên bằng
[00:48:59] bằng không được ạ đó là sự nha Minh sẽ
[00:49:01] thường là tôi sẽ chơi theo cách như này
[00:49:05] thường là tôi sẽ có thường có một cái
[00:49:07] thẻ span ở bên cạnh
[00:49:09] em ở bên cạnh như thế này
[00:49:14] Ừ tôi sẽ để mà hiển thị lỗi bé cách
[00:49:18] thường thường thấy nhất kiểu thường hay
[00:49:21] mình sẽ có span báo lỗi ngay bên cạnh
[00:49:24] như thế này sẽ có 1 span đây này Ai đi
[00:49:28] ra Euro tên này có thưởng này để như này
[00:49:30] Ừ cái này tôi để tiếng Anh Hùng Tí Hon
[00:49:33] bé uống để chỗ tiếng Việt thì nó sẽ lỗi
[00:49:35] tay ngay không ạ
[00:49:38] Như này và
[00:49:41] khi khi mà như thế này mình sẽ đó của
[00:49:46] Ừ cái này blue switch
[00:49:50] mình sẽ lỗi tên này chấm bi nơ HTML là
[00:50:02] em làm gì này nó chạy thử Đấy bấm này
[00:50:05] đúng thấy là nó vừa bị lại chữ rất là
[00:50:07] nhanh rồi nó chớp nhoáng rồi nó bị vẫn
[00:50:10] vẫn đẩy cái này đi mất Tại sao lại như
[00:50:13] thế bởi vì như tội nói thì đó là khi bấm
[00:50:15] vào thì nó vỡ sắp ít không ạ Các bạn
[00:50:18] không thể đổ cái này bút Tân Thành 2 bút
[00:50:22] thần được mà các bạn nên vẫn vẫn nên để
[00:50:25] nó xem ít
[00:50:28] anh Bởi vì bản chất cái nút này mà mình
[00:50:32] sẽ dùng ra Speed để năm cái việc là cái
[00:50:35] Ừ cái form mà được đẩy đi nó sẽ ổn hơn
[00:50:38] nó sẽ như sau sẽ ăn gì sao mình sẽ có
[00:50:43] khái niệm Nitơ này như thế này và và đây
[00:50:45] mình sẽ nếu mà khi mà không được để mà
[00:50:48] khi mà có lỗi gì đó anh sẽ Return là
[00:50:51] Phone này à
[00:50:53] em còn nếu mà không đi tầm đây nó sẽ
[00:50:57] hiểu gì Tôi là Chu không ạ 01 Return thì
[00:51:00] nó sẽ hiểu gì tôi mà chu thích thì mình
[00:51:02] đi như thế này cũng được nó không không
[00:51:03] có được
[00:51:07] đây để các bạn xem thử nhé
[00:51:11] anh bấm này đó các bạn thấy phòng không
[00:51:12] được xem nghị nữa không ạ hiển thị ra
[00:51:15] được ờ
[00:51:17] Ừ nhưng mà ở đây nó sẽ có một nhược điểm
[00:51:22] một tí đó là sao đó là ở
[00:51:24] thì các bạn kiểm tra bao nhiêu cái đây
[00:51:26] thì các bạn sẽ gì Tên bấy nhiêu cái đấy
[00:51:29] Cái thứ nhất thứ hai là
[00:51:32] Ừ nếu mà giả sử Nếu bây giờ sử mà các
[00:51:35] bạn bị sai lỗi chính tả ra sửa đây khiến
[00:51:36] mất cái chấm phẩy như này thôi chẳng ạ
[00:51:38] bấm này
[00:51:41] Vì sao đây vẫn nhận
[00:51:45] ở đây tôi sai chính tả đây nhé len là sự
[00:51:48] đi sai chính tả đi vậy
[00:51:52] em chẳng phải đi sang thả thôi nhé bấm
[00:51:53] đây
[00:51:56] Ê mày không thấy iPhone rồi xem ít đúng
[00:51:59] ạ ạ Thế nên là cách làm để mà các bạn
[00:52:01] tránh làm việc là không biết đường mình
[00:52:05] sai ngay đây tôi cho mấy ông xem nhé bấm
[00:52:08] vào đây nó hiển thị lỗi rất nhanh sông
[00:52:10] nó xem ít xử mất rồi thành thành ra là
[00:52:13] cậu có ông không nhìn được lỗi công cứ
[00:52:16] tưởng cốt ông chạy được chạy đúng có
[00:52:19] đúng Tại sao kiểu bấm vào đây nó không
[00:52:22] bị lỗi không ạ Đấy thì cách để mà như
[00:52:25] này nhớ nhất là một là mấy ông đổi kẻ
[00:52:28] bước chân lại thành phố tuần trước để mà
[00:52:32] Mấy ông kéo biết được à cốt mình đang
[00:52:34] chạy đồng và đang say
[00:52:38] ông thầy nó không ba lỗ luôn đấy
[00:52:40] ờ ờ
[00:52:44] anh không báo lỗi không ạ Đây
[00:52:50] I il take in thật Đỡ thế nhỉ À thì tại
[00:52:52] sao lại không báo lỗi nhé hay là không
[00:52:59] Anh bình thường nó sẽ báo lỗi không tìm
[00:53:01] thấy cái hàng này cơ nhưng chắc à có vẻ
[00:53:04] là nó không báo lỗi kiểu nghe chứ không
[00:53:12] có cách cách để có ông biết được xem có
[00:53:14] lỗi không ấy thì béo có thể xóa sử cái
[00:53:18] đoạn cút một đoạn Cốt nó đi giờ sử về
[00:53:20] sau cốt mình sẽ rất là dài tận mấy trăm
[00:53:23] dòng ấy mấy ông có thể là
[00:53:25] điện nó hình Chú thích kiểu ngay điều mà
[00:53:31] chạy thử mình sẽ con solo chùm lót này
[00:53:36] vụ tai nạn chạy thơ từng cái một
[00:53:37] à à
[00:53:40] anh như này với các bạn biết được cái
[00:53:43] xem nó có chạy được hay không lại gõ tên
[00:53:47] Nga đó chạy được nghe Chứng tỏ là đến
[00:53:51] cái đoạn đoạn nào đó họ sẽ sai ở một chỗ
[00:53:54] nào đó đúng ạ thì mình mình kiểu bò bỏ
[00:53:56] dần chú thích bỏ dần chú thích mình sẽ
[00:53:58] biết được
[00:53:59] khi sex
[00:54:01] cho tôi tôi thường hay làm cách kiểu
[00:54:05] ngay in đẩy cái hàng có slot này nó đến
[00:54:09] đến dần dần mình cái đoạn nào đó là sử
[00:54:11] nó đến cái đoạn này họ cảm nó đến đoạn
[00:54:14] này được ạ Nói thử anh chơi ngay thằng
[00:54:16] này tôi sẽ để cả Không nghe trong trường
[00:54:19] hợp mà ở đâu trường hợp một người đúng
[00:54:22] chứ Tôi muốn nó nhảy vào đây thì nó sẽ
[00:54:25] ra số 1 Nếu em nhảy xuống cái chỗ không
[00:54:28] số không này đúng ạ
[00:54:32] Ừ thì nó nó sẽ là sai không ạ
[00:54:35] à à
[00:54:38] I live and the force không không trong
[00:54:39] trường hợp này không có gì further phố ở
[00:54:40] đâu
[00:54:43] chỉ vì yêu mà đến cuối rồi cho form bằng
[00:54:49] anh không Tôi muốn cho mấy ông ấy hiểu
[00:54:52] bản chất luôn cả cái dùng get Ơn trời vì
[00:54:55] à on on toilet thì kết hợp Return cửa
[00:55:05] đề thi khi nói chung là giả sử cốt ở đây
[00:55:07] lỗi không Tôi có một cách thì kiểm tra
[00:55:09] lỗi
[00:55:11] anh không tôi cố tình gõ ngày lỗi đúng
[00:55:15] không Thì cách để kiểm tra lỗi thì nếu
[00:55:18] mới để chơi cách kiểu ngay nó dậy in ra
[00:55:23] Em in ra 12 inch không hiểu nhà kiểm tra
[00:55:26] A bấm nhanh nhẹn béo ngậy nữa số 0 tức
[00:55:28] là cốt là không chạy đây đúng không Thì
[00:55:30] có mới kiểm tra xem lại cái điều kiện là
[00:55:31] đúng hay sai
[00:55:35] Ở đây chẳng hạn thế còn đấy bây giờ gõ
[00:55:38] đúng chỗ nào Bấm và này đó thì nó ra một
[00:55:39] đúng không ạ Lúc này trong trường hợp
[00:55:42] này thì béo mà biết được đấy cách thì đi
[00:55:47] bốc cốt đầu tiên các bạn sẽ bùi bùi chủ
[00:55:49] thích cho sau đó đi chạy lần lượt từng
[00:55:52] cái xe mà đến đến được cái dòng nào đó
[00:55:55] ngọn bởi vì a cốt các bạn không những
[00:55:58] sai ở một lòng mà say đôi khi ở rất
[00:56:01] nhiều dòng mình từng mình từng bị như
[00:56:03] thế Mình hiểu mà mình hiểu cảm giác mà
[00:56:05] mình sai có khí dai ngay dòng thứ hai ấy
[00:56:07] mấy dòng ruồi rất là đúng hết nhưng xoay
[00:56:10] dòng thứ hai là một cốt kiểu không chạy
[00:56:11] nữa
[00:56:13] cho nên là các bạn sẽ thứ nhất là các
[00:56:17] bạn sẽ phải không cho form sắp ít đi bởi
[00:56:19] vì ra Switch mà nó nhưng như thế này chị
[00:56:22] sẽ chết này bọn đấy Thành nha các bạn sẽ
[00:56:23] phải
[00:56:26] bọn một là đổi thay nó bước thật như thế
[00:56:29] này đây một cách có bạn bảo kênh kia
[00:56:33] dùng live defo cũng được hoa cà Tôi làm
[00:56:35] hội đấy có cách đơn giản hơn tôi tạm
[00:56:38] chấp nhận là xóa cái phần for mày đi trở
[00:56:42] lại lẽ tạm thời tạm thời Xóa đi
[00:56:45] vi phạm thuế xóa đi để mà mình bấm vào
[00:56:48] như này nó sẽ không Không vấn đề gì Nếu
[00:56:50] các bạn Sai đúng for nó sẽ không dám ít
[00:56:52] nóng bạn
[00:56:54] à à
[00:57:01] Ừ cái vụ Tôi dùng cái glitter để vợ đi
[00:57:03] Tân Phone này tôi sẽ giải thích cho mấy
[00:57:06] ông Tại sao tội dùng đây Bởi vì nếu mà
[00:57:08] giả sử bây giờ có nhiều trường hợp và
[00:57:10] việc và mình kiểm tra trống không phải
[00:57:12] mỗi tên nữa mà Ngày sinh nói chung kiểm
[00:57:15] tra sống tất cả những hoài nha đầu tiên
[00:57:17] tôi cứ tạo ra đây một đống nhá
[00:57:20] Tạo đây một đồng đi
[00:57:31] ạ
[00:57:35] sau đó thì mình kiểm tra về ngày sinh
[00:57:37] này ạ
[00:57:39] nhớ
[00:57:42] ngày sinh cho sư tử như ngày sinh chấm
[00:57:51] anh ta lỗi Ngày sinh không ạ à à
[00:58:04] đó là sự chạy thử cho đã Anh tên có một
[00:58:06] để chống lại ừ chúng tỏ ngày sinh này
[00:58:09] đang có vấn đề Anh thử con solo chấm Lót
[00:58:19] bấm này
[00:58:23] a a luôn ở đây Ở đây đang bị khói không
[00:58:26] bị nhược điểm một tí đó là ở đây mình
[00:58:29] a
[00:58:33] written for thành ra là là nó sẽ kết
[00:58:36] thúc kể Tăng Trần ngay tại kẻ glitter
[00:58:39] này thành ra là nó không nhảy xuống cái
[00:58:41] đoạn kiểm tra ngày sinh nữa các bạn đang
[00:58:43] thấy ở đây rõ ràng ngày sinh của mình
[00:58:45] đang chấm nó ạ nhưng mà không ghi thông
[00:58:47] báo lỗi bởi vì
[00:58:50] nó không nó không chạy đến cái cái cái
[00:58:52] dòng này bởi vì đây written full rồi cái
[00:58:54] cách để mà
[00:58:57] các bạn muốn hiển thị ra một là các bạn
[00:59:00] cứ để lỗi các bạn dừng ngay cả đấy bạn
[00:59:02] hiền thì lỗi luôn như thế này sau đó lên
[00:59:04] người dùng điền tiếp nha chẳng hạn thì
[00:59:06] bắt đầu hiển thị lỗi ở dòng tiếp theo
[00:59:09] hay là các bạn muốn hiển thị toàn bộ tất
[00:59:11] cả các lỗi luôn để người dùng điền đầy
[00:59:13] đủ cho người dùng bấm thì nó cũng sẽ hợp
[00:59:17] lý hơn thì các bạn sẽ sẽ có khái niệm là
[00:59:19] các bạn sẽ tại một biến ở đây mình sẽ
[00:59:21] tạo biến là biến nhà
[00:59:24] kiểm tra lỗi em ạ
[00:59:27] lúc đầu mình sẽ cho bằng chu được ạ Lúc
[00:59:30] đầu mình cho phone em ạ ạ Sau đó cứ mỗi
[00:59:33] lần mà thằng này có
[00:59:35] thai có lỗi thật thì mình sẽ cho nó vẫn
[00:59:40] à à
[00:59:40] ạ
[00:59:45] và ở cuối mình sẽ kiểm tra nếu mà kiểm
[00:59:49] tra lỗi là đúng nó ngoác đi nghị một là
[00:59:52] các bạn sẽ So sánh kiểu nhà bằng bằng
[00:59:55] bằng chu như này hòa các bạn đi Tắt cả
[00:59:58] ngày cũng được vì bạn chất À cái này là
[01:00:00] nó Chu rồi thì tất cả các điều kiện này
[01:00:03] đúng là đúng ạ thì mình sẽ là Return
[01:00:07] phone như thế này còn nếu không đi Tôn
[01:00:09] thì như mình đã nói không Peter thì mặc
[01:00:11] định nó sẽ Britain's luôn
[01:00:14] bấm vào ngay nó sẽ in ra được cả hai cả
[01:00:18] luôn không ạ Đấy cách để mình sẽ kiểm
[01:00:20] tra mình sẽ tạo ra một cái biến cá tra
[01:00:22] lỗi Sau đó mình sẽ làm lương dân như thế
[01:00:27] à à
[01:00:29] ờ ờ
[01:00:36] anh ở đây mình kiểm tra tên được ra kiểm
[01:00:38] tra tên Ở đây mức tương đối là tên không
[01:00:41] được đấy chấm nếu mà mình không kết hợp
[01:00:43] với led hôm trước đây mình giờ sửa mình
[01:00:46] kết hợp với Gas không trước nhé
[01:00:50] ghét hôm trước tôi không dạy lại cái vụ
[01:00:52] được cái không trước đâu nghe Tôi sẽ chỉ
[01:00:54] dùng Nhanh cái mà tôi đã lưu chẳng lại
[01:00:55] cho nhanh
[01:01:00] em thật sự đây à họ tên đi
[01:01:01] em
[01:01:07] Ờ
[01:01:11] thì đầu tiên à mình sẽ tạo một cái và
[01:01:13] đôi rách tên rồi ạ
[01:01:17] bằng xốp chéo như thế này copy các loại
[01:01:26] Ừ thì Dallas tên nhớ cách để kiểm tra để
[01:01:29] kiểm tra cái này thì sẽ đúng như cái
[01:01:35] cho tôi cứ cách hẳn ra một dòng nha mấy
[01:01:38] ông dễ hình dung nhé sẽ tên này có
[01:01:40] thương anh đi kiểu nhà cho mấy ông cậu
[01:01:43] dễ Hình dung là phân biệt thằng ạ Thằng
[01:01:52] 3 cách để kiểm tra việc Tên nó hợp lệ
[01:01:57] hay không thì mình sẽ là ít à tên chấm
[01:01:58] test
[01:02:03] ạ sau đó đi về este này
[01:02:07] đúng là tôi tôi nhớ là thằng thằng nào
[01:02:10] trước là sau tôi xin phép cha Google lại
[01:02:11] phát nữa
[01:02:13] em không nhớ lắm
[01:02:15] em à ngược lại ngược lại
[01:02:20] ở lại đấy nghe rồi rách tên test
[01:02:22] Nếu mà đúng
[01:02:25] nếu mà ngược lại cái đúng nghĩa nếu ạ
[01:02:28] Nếu mà sai không ạ thì các bạn bằng bằng
[01:02:31] phone là sai đúng không ạ
[01:02:33] ở đó
[01:02:42] Anh tên không hợp lệ Hằng ạ
[01:02:49] Ừ cái này thời gian nó bị nhược điểm một
[01:02:51] tí đó và tên không được để trống rồi hãy
[01:02:53] còn nhảy sang tên không hợp lệ nữa nó
[01:02:58] nhọn nên là mấy ông có thể kiểm tra ít
[01:03:01] như này trước em như này
[01:03:11] sau khi mà kiểu tên không được để trống
[01:03:13] rồi nếu bắt đầu kiểm tra tế trước sau
[01:03:16] sau đó đến việc
[01:03:19] mình kiểm tra xem tên có hợp lệ không nó
[01:03:22] thì này nóng chuẩn hơn này
[01:03:26] a a sáng đó tôi không hợp lệ chẳng hạn
[01:03:29] thế đúng ạ có cách cách này thời ra béo
[01:03:31] có thể viết tắt hơn nữa nhé đó các bạn
[01:03:33] để rồi Tham nào trước như thế này Cái
[01:03:36] thằng này trong lập trình nó sẽ hiểu là
[01:03:40] ngược nó là ngược lại mà giống dấu trừ
[01:03:41] với
[01:03:45] AE theo kiểu nó ngược lại để lặng tất cả
[01:03:48] kiểu chu sẽ thành phone phone là sẽ làm
[01:03:52] chuyển ạ Cái này kiểm tra đây tôi sẽ chú
[01:03:56] thích chồng mấy ông sẽ đây sẽ ra băng
[01:04:00] băng phone không ạ nghe thì sẽ viết theo
[01:04:03] kiểu ngược lại kiểu như thế này cái này
[01:04:05] phone ngược lại hình chu mà không ạ Đây
[01:04:10] Ừ thôi tôi đang dạy cho mấy ông cả các
[01:04:14] ký tự nữa để mà để mà Mấy ông à về sau
[01:04:17] mà xem cốt có hỗ trợ lâu đấy về mày
[01:04:19] không còn hình dung được không lại bảo
[01:04:21] tôi không dậy được cái đấy đúng rồi nó
[01:04:24] phủ định nóng dùng từ chuẩn đấy thôi
[01:04:27] quên mất cái từ đấy nó phủ định lại thì
[01:04:29] nên là cái iPhone thì nó sẽ phủ định lại
[01:04:37] Ừ đúng rồi nó chỉ tác dụng với bao lần
[01:04:39] gì vậy mà không tác dụng với
[01:04:41] tôi Tôi chưa thử cái chuỗi ngày các thứ
[01:04:43] thứ
[01:04:46] nhưng mà hình như là với chỗ nghỉ cho
[01:04:48] ở chỗ ấy thì hình như nó ngược lại nó sẽ
[01:04:53] luôn hay là lại Phone xe 7 chỗ nào luôn
[01:05:02] à à
[01:05:06] à à đầy tiếp theo là đến bên
[01:05:08] bên Giới Tính giới tính thì các bạn sẽ
[01:05:11] thấy phức tạp hơn một tí giới tính thì
[01:05:13] mình không để bắt buộc người ta bắt buộc
[01:05:15] phải chọn Nam được không thể bắt buộc
[01:05:17] phải ra sẵn nữ được đúng ạ Mình chỉ quan
[01:05:19] tâm việc là họ có chọn một trong hai
[01:05:23] không ngồi đó ngọn hết cách thì mà
[01:05:25] 3 cách để mình kiểm tra xem họ có trọn
[01:05:28] bộ trong hay không thì đó là mình sẽ
[01:05:31] thì mình sẽ phải cần lấy cả hai hàng về
[01:05:33] sau đó em kiểm tra xem họ đã tích và cái
[01:05:36] này họ chỉ cần tích là một trong hai cái
[01:05:39] tức là tớ ám chỉ thành công nó ạ nếu ra
[01:05:42] sự cả hai cái mà họ được không thích thì
[01:05:44] sẽ định là thất bại không ạ Cái cách để
[01:05:47] mà lấy mình sẽ lấy cả hai cái về nó sẽ
[01:05:50] bằng led Giới Tính
[01:05:54] giới tính lần này nó sẽ sẽ số nhiều
[01:05:57] thường mình sẽ đặt tên nó ai bởi nó
[01:06:00] xuống nhiều tên nó làm mạc như chính
[01:06:03] ngay đây sẽ bằng đo cung đó của mình
[01:06:06] Chấm ghét em mình bye nêm này giới tính
[01:06:09] này à Ê
[01:06:12] bà các bạn sẽ thấy ở mình sẽ không có
[01:06:16] chấm value ở đây Tại sao bởi việc trong
[01:06:18] trường hợp lần này các bạn sẽ thấy nó có
[01:06:20] khác một tí nhé em mình body thì nó sẽ
[01:06:22] không có chữ S Tức là nó số ít không ạ
[01:06:26] con ghẹ em mình thêm chữ s này ăn chỉ
[01:06:29] nói sao về mạng mà nó sẽ rồi Nhiều mà
[01:06:30] mình sẽ chạy vòng lặp các bạn nhiều vòng
[01:06:35] lặp không ạ Mình sẽ là for này Nét y
[01:06:45] nhỏ hơn mạnh giới tính chấm e này lại
[01:06:48] theo độ dài của mạng gửi tính đi cộng
[01:06:49] này
[01:06:50] và
[01:06:53] sau đó thì mình sẽ kiểm tra với mảng
[01:06:55] giới tính tại vị trí Thử
[01:07:05] em kiểm tra dự tính đi
[01:07:10] bằng Phone này à
[01:07:12] cho mình mình sẽ phải tại một biến thể
[01:07:14] kiểm tra dự tính xem mà nó là thích nghe
[01:07:16] chưa Sau đó thì nếu mà ít
[01:07:21] tại thẻ mạng giới tính tại vị trí tùy nó
[01:07:24] là tích cực thế này là được
[01:07:27] thì mình sẽ kiểm tra
[01:07:30] giới tính mình sẽ ảnh Chu tất cả mình
[01:07:34] được tích rồi ông ạ và đây mình kiểm tra
[01:07:37] nếu mà kiểm tra giới tính bằng bằng
[01:07:40] phone tất cả chưa đầu tích gì cả đó thì
[01:07:55] xin lỗi Giờ tình không ạ là giới tính
[01:08:03] Ở nhà hay
[01:08:09] thì tại sao nhé sự tích rồi
[01:08:12] khi đó Tại sao mấy ông thấy tôi vừa rồi
[01:08:15] phải tại trang bởi vịt Bây giờ xử tôi
[01:08:21] em đang chúng ta lại sang từ đầu mà ông
[01:08:26] Ừ nếu thấy là nó không thể xóa cái lỗi
[01:08:29] cũ đi đúng ạ thì các bạn sẽ phải e ở đây
[01:08:32] nghĩa là khi mà nó thành công rồi mình
[01:08:36] sẽ phải xóa lỗi đi dù không ạ thì đây
[01:08:39] đợt đầu tiên thì đây mình sẽ ra
[01:08:40] anh
[01:08:43] với đoạn tên này thì mình kiểm tra nếu
[01:08:46] mà thành công thằng này
[01:08:49] ô t có được để trống này tên Nói chung
[01:08:51] là đoạn này Thành công hết này sẽ e ở
[01:08:55] đây đó là
[01:09:03] thì mình sẽ xóa mình sẽ xóa cái á
[01:09:06] Ê mày đi cho nó những chỗ trống để hiểu
[01:09:07] được là
[01:09:10] đây là sự lúc đầu tiên không được để
[01:09:13] trống nhé Đừng Gọi cho Long này đó hợp
[01:09:16] lệ luôn không ạ thì gọi chữ a a tên 01
[01:09:19] lệ này gõ chữ này tên không hợp lệ đấy
[01:09:22] ai biết hoa này hợp lệ đấy đúng không ạ
[01:09:25] Đấy thì cái mê Cái dưới này tương tự Thế
[01:09:27] Các bạn thấy Cốt nó cũng sẽ bao dày dần
[01:09:30] dần dần lên nó sẽ như thế này à
[01:09:31] xin
[01:09:33] lỗi
[01:09:37] ngày sinh nhật hạnh không ạ Lúc đầu lỗi
[01:09:40] này chọn một cái ngày sinh nào đó đó thì
[01:09:46] à à
[01:09:48] có
[01:09:52] ai sẽ phá ra các bạn sẽ thấy công nhận
[01:09:59] em dấu tích xanh nhà dấu tích xanh thì
[01:10:02] bạn chất nó là
[01:10:06] nó là CS các bạn sẽ chèn thêm một cái
[01:10:09] biểu tượng ở trên mạng các bạn thể tải
[01:10:13] tại cái ảnh ảnh này hoặc là cái biểu
[01:10:16] tượng mới về Đúng cái xé đấy về để có
[01:10:19] bạn Hiển thị nó ra thôi chứ nó không gì
[01:10:22] đặc biệt cả các bạn thở ra các bạn có
[01:10:24] thể làm theo nhiều cách là các bạn có
[01:10:26] thể bôi màu đỏ
[01:10:30] 3 other models cho ngày input nào mà
[01:10:34] không hợp lệnh hạn chế Nãy giờ tôi đang
[01:10:37] làm thì thực ra mấy cái lỗi này các bạn
[01:10:39] có thể thêm class cho nó một ra thêm
[01:10:42] Glass 2 toàn bộ spam nó thành
[01:10:44] colourglass cũng được nhưng thường tôi
[01:10:48] sẽ cho nó class class là span lỗi chẳng
[01:10:51] hạn như này em có Slow tôi sẽ có style
[01:10:52] cho nó
[01:10:57] là với Star lỗi mình sẽ color splash em
[01:11:04] thế này
[01:11:18] Ừ tí bạn về cái vụ
[01:11:21] anh không cần sắp ít mà nó vẫn chạy vào
[01:11:23] cái eo không chẳng qua mình bấm lại lần
[01:11:24] nữa thì nó sẽ chạy lại về phương trình
[01:11:27] này thì nó kiểm tra lại thêm một lượt
[01:11:29] nữa mà thấy hợp lễ hết tình nó chạy và
[01:11:41] khi mà thực ra là thực tế là
[01:11:44] cái vụ hiển thị ra thông báo thành công
[01:11:46] các thứ thứ nếu mà nếu trong trường hợp
[01:11:48] mà các bạn Nhập xong hết tiền đúng là
[01:11:50] năng ký rồi đó nó nhảy lên luôn chứ nó
[01:11:53] không không cần nói mất công vợ xóa mấy
[01:11:55] cái này và thông báo thành công không
[01:11:57] thông báo tích xanh ở đây em gì nữa
[01:12:13] em có bạn cũng có thể thắc mắc cả vụ là
[01:12:16] em đang muốn là kiểu em em Điền đến cái
[01:12:18] đoạn này nó sẽ thông báo luôn à phải
[01:12:20] điền cái ở trên tên không được để chấm
[01:12:22] nóng hoặc những những cái đấy là ra bài
[01:12:25] toán phức tạp hơn một tí theo kiểu là
[01:12:27] người dùng Điền đến đây và nó sẽ thông
[01:12:29] nó sẽ kiểm tra trước những cái hầm trên
[01:12:34] của nó không ạ để mặc để mở cậu thông
[01:12:36] báo lỗ luôn nhé người dùng gõ đến đâu
[01:12:38] kiểm tra nhìn Đấy cũng là một cách không
[01:12:41] ạ Như cái này nó phức tạp hơn thì mình
[01:12:44] sẽ không dạy ở đây các bạn muốn tìm hiểu
[01:12:47] thì các bạn tìm hiểu về cái thực có
[01:12:50] nhiều thư viện của Switch để mà làm vụ
[01:12:52] virus rất là nhanh các bạn tra Google nó
[01:12:55] sẽ ra và Days a Switch nó sẽ cho ra cả
[01:12:58] cốt mẫu các bạn có hoa cả thư viện thư
[01:13:00] viện Tức là sao nghĩa là ra Cốc rất
[01:13:03] nhiều dòng cốt thận chỉ nhìn dòng ngồi
[01:13:06] chẻ làm pate cho các bạn để các bạn chỉ
[01:13:09] cần nhúng hay thư viện này về là nó sẽ
[01:13:12] hỗ trợ ở xin lỗi này bà kết hợp dùng
[01:13:16] rách này các thứ để mà hiển thị ra cậu
[01:13:19] người ta gõ đến đâu ấy thông báo tên quá
[01:13:23] ngắn này tên không đủ dày vân vân cũng
[01:13:26] được thì mình mình không dậy các bạn ở
[01:13:28] mượn mấy cái mức đấy
[01:13:30] Em à mình chỉ dạy các bạn hiểu thế nào
[01:13:34] là virus cũng nhờ lập trình các tự rồi
[01:13:35] đúng không ạ
[01:13:38] tiếp theo vụ Email Email Thật ra như
[01:13:41] mình đã nói nếu có lợn dùng thay mail
[01:13:43] như thế này thì ra Hà Tĩnh l nó hỗ trợ
[01:13:46] để một người dùng bắt bụi đúng rồi nên
[01:13:47] các bạn cùng đón mà bạn chỉ cần kiểm tra
[01:13:50] đây là là
[01:13:59] Ừ nhưng mà tôi khuyên mấy ông nên vẫn đi
[01:14:01] dùng có thì bảo đã Nếu thế thì em vẫn
[01:14:03] muốn dùng mà vui rách để mà kiểm tra thì
[01:14:06] sao ạ Em em đổi cái này hành tách sau đó
[01:14:10] Thì em kiểm tra bằng bằng giao tiếp được
[01:14:12] không Thì ra tôi khuyên Nếu mà không nên
[01:14:15] như thế có những cái gì mình vẫn phải
[01:14:17] nên giữ nguyên như thế này Tại sao bởi
[01:14:21] vì nó giống như kiểu ông ông cũng có ông
[01:14:24] bảo là kiểu em bắt ở đây Nhập tuổi em ạ
[01:14:27] sử Thế nhá là sự thôi nhé Đây nhiêu tuổi
[01:14:30] rồi hạn tôi sau đó thì em để tách thay
[01:14:32] vì để nằm bờ sau đó em sẽ dùng ra quyết
[01:14:37] để để bạn lưu ý Kiểm tra Thì sao Thì cái
[01:14:40] này khuyên không nên Tại sao vì
[01:14:40] ơi
[01:14:44] các bạn hãy nên nhớ điều đó là
[01:14:45] cho người dùng các bạn bây giờ còn dùng
[01:14:47] bằng điện thoại nữa
[01:14:51] Thế nên là cái vụ Cái vụ mà kiểu nhiễm
[01:14:54] và các bạn thay đổi kể thay bút thành
[01:14:57] Tech thì nó sẽ hiển thị ra cái bàn phím
[01:15:00] gọi điện thoại là có chữ còn nếu mà thay
[01:15:04] nó là Email thì nó sẽ được gợi ý tự động
[01:15:08] điền của điện thoại cũng như là thay
[01:15:09] bằng năm bờ thì nó sẽ hiển thị bàn phím
[01:15:11] số của điện thoại người dùng sẽ dễ tiền
[01:15:15] hơn tôi phải nói vụ đấy vì đã có nhiều
[01:15:18] chàng ngu si ai kia rõ ràng là cái ô
[01:15:20] nhập số điện thoại nhưng mà nó lại để
[01:15:23] thay Thái tách hãy ra cho người dùng
[01:15:25] điền số điện thoại rất là mệt cần phải
[01:15:28] bấm hai cái nick để đổi sang bàn phím số
[01:15:30] cũng là nó không có gợi ý của số điện
[01:15:33] thoại điền số điện thoại ạ Bây giờ là
[01:15:35] trình duyệt nó cũng thông minh nó sẽ gợi
[01:15:39] ý vụ tự động Điền nên là Nên là các bạn
[01:15:43] để nên nó lại ID nói cho mọi thứ Nếu
[01:15:45] tiếng Anh thì cái vụ tự động điền của
[01:15:47] cái trình duyệt nó sẽ hiểu nó sẽ tự động
[01:15:50] Điền rất là ổn Còn nếu các bạn để tiếng
[01:15:52] Việt cũng như là các bạn để hết bằng hai
[01:15:55] tách thì nó sẽ tự động điền giá là đểu
[01:15:57] để không ạ
[01:16:00] Ê mấy ông để ý kĩ một cái vụ tự động
[01:16:03] điền của cái trình duyệt mong sẽ hiểu là
[01:16:06] do là do kệ trang đấy nó đều như thế nào
[01:16:08] thì tự động Điền không hiểu cái gì cả
[01:16:18] Ừ nếu ông khó chịu ở vụ đấy và mấy ông
[01:16:20] từng là người dùng đúng ạ bây giờ mấy
[01:16:22] ông sang Làm lập trình rồi đúng không ạ
[01:16:24] Nếu không phải rút kinh nghiệm từ những
[01:16:27] người đi trước để mà tránh những cái cái
[01:16:29] khó chịu ấy chảy ra không phải bắt chước
[01:16:31] đâu nhé Ngoài thể lừa rồi bắt chưa rồi
[01:16:34] nhé em
[01:16:37] mà tôi từng vào tôi từng bảo tôi vào cái
[01:16:38] trang
[01:16:41] của Vietcombank sau đó thì ra Speed với
[01:16:44] đã đều nó không cho tôi có điền đầy đủ
[01:16:46] thông tin từ đăng ký âm được đi nên tôi
[01:16:48] bực mình thôi mở ra Swift lên để tôi tự
[01:16:50] gõ thì xăm ít được cái phom đấy là Nhạn
[01:16:54] đấy thì tôi mới cậu khó chịu ở viện
[01:17:11] Ừ cái vụ Email thì
[01:17:15] chắc cả nó cũng chỉ là không được để
[01:17:18] trống cho tôi bỏ qua nhé Thôi chả làm vụ
[01:17:20] mật khẩu thôi vụ mật khẩu thì nó còn
[01:17:22] thêm với vụ là mình không được để quá
[01:17:27] ngắn ạ ạ Thế Mong cái hay mở ngoặc ạ
[01:17:31] Em email tạm bỏ qua đi em ạ
[01:17:39] tôi sẽ còn nhắc đến lại Nó cho anh khi
[01:17:43] nào nó ổn thì thôi ạ bây giờ nó vẫn đều
[01:17:45] vãi này là tôi không thể không Rồi nó ra
[01:17:56] là Mật khẩu này và lưu cho em ạ
[01:17:59] sau đó mình kiểm tra mật khẩu
[01:18:01] chấm le này
[01:18:05] Ừ nếu mà ngắn ngắn hơn à
[01:18:07] ở đầu tiên là giả sửa Mio muốn bắt thêm
[01:18:09] các trường hợp với kiểu không được để
[01:18:12] trống rồi ngắn quá Cái gì đó Con kiểm
[01:18:16] tra về độ mạnh của mật khẩu thì
[01:18:18] hôm trước anh Tuấn Anh ấy cũng chia sẻ
[01:18:22] có nhiều Trang nó nó có chia sẻ mấy cái
[01:18:24] đoạn Quý khách có trong đó có cả đấy
[01:18:28] cách kiểm tra về độ mạnh mật khẩu là
[01:18:31] phải có kí tự đặc biệt trong đó Tấm đơn
[01:18:34] Vân thì các bạn tra Google sẽ có ngay
[01:18:38] Tôi ghét password có có ra Speed luôn
[01:18:43] này Đấy rất tiện không ạ cho tôi tôi tôi
[01:18:45] chia sẻ từ khóa thì thôi để mấy ông
[01:18:47] Thạch hạ thôi
[01:18:54] lỗi mình sẽ có tạo một cái spam Ở Đây
[01:18:55] Rồi cá hồi để tôi bị khó chịu ở điểm là
[01:18:59] tạo làm span Vãi cả thế
[01:19:02] thật à Khởi đấy tôi còn nghĩ ra cách để
[01:19:03] đó là
[01:19:07] cứ thằng nào mà lỗi in bút thì mình sẽ
[01:19:11] tự tạo tự dùng dao Swift để mà tạo một
[01:19:15] cái HTML ở bên cạnh cài than I put đấy
[01:19:19] và tạo span cũ cũng cũng được kiểu đấy
[01:19:20] cũng được
[01:19:24] ở bài thích thì tôi thử làm mẫu cho mấy
[01:19:27] ông một quả này nhá cũng được nhé Thì
[01:19:29] mấy ông sẽ thấy là nó cũng ổn như nào
[01:19:32] đây tôi sẽ như thế trong trường hợp này
[01:19:36] tôi xóa này Đây nè
[01:19:39] Đây là một cái input 1 họp đúng ạ input
[01:19:41] mà khẩu
[01:19:45] Nó ghét em mình nhé em ạ
[01:19:49] net mật khẩu đến như là mực mật khẩu
[01:19:52] value thì nó sẽ ra input mật khẩu chấm
[01:19:56] Peru thôi không ạ nhìn này
[01:19:58] anh nghe vẫn luôn đúng không ạ nhưng mà
[01:20:02] đến cái lỗi ở đây tôi sẽ tôi sẽ làm như
[01:20:06] sau tôi sẽ là ờ
[01:20:09] cho tôi sẽ tạo một cái
[01:20:13] cái HTML cạnh cái thằng cái thằng Mật
[01:20:14] khẩu này
[01:20:18] vì thương nhớ nó là offensive là viết
[01:20:28] ở bên trai tôi là tạo thằng con mất rồi
[01:20:45] anh Đợi mình tí mình mình chưa làm bằng
[01:20:47] da Speed phần bây giờ bình thường Anh
[01:21:10] anh tí thử nhé
[01:21:17] à à
[01:21:21] em à Cái này input mật khẩu Này cái có
[01:21:25] hàm của nó chắc thế Cái này sẽ spam
[01:21:26] không ạ
[01:21:28] à à
[01:21:38] em nghe không cần ai đi nữa rảnh lại bỏ
[01:21:42] đi bỏ đi Không cần ai đi nữa vào đây sẽ
[01:21:45] là giới tính không được mật khẩu không
[01:21:47] được để trống không ạ
[01:21:50] bí
[01:22:09] bí mật khẩu chấm net à
[01:22:12] ở đây mình thử con solo chấm rock thế
[01:22:18] xem mã lỗi gì à
[01:22:22] anh nói chó mà em thử xem nó chạy đều ở
[01:22:24] đây không nhé mình lại chạy lần lượt
[01:22:26] thôi đúng không ạ sẽ được đây không này
[01:22:28] à
[01:22:31] có cả một vẫn vào
[01:22:34] ở đây mình thử xem inspector ngày tuổi
[01:22:36] xem
[01:22:39] à À đây nó có tạo như là tạo đây hình
[01:22:42] như nó tạo vào bên trong bên trong của
[01:22:44] thằng Phúc nó say mất rồi
[01:22:55] à à
[01:22:58] a before after
[01:23:02] Em in size à đây đây after gaining là
[01:23:18] anh bita
[01:23:25] a a đây
[01:23:28] Tập đọc tập your love you
[01:23:38] có gj nó sẽ giúp cốt dress nó nhanh hơn
[01:23:42] và vì nó rút gọn lại những cái này nó sẽ
[01:23:44] giúp cốt ra Swift nhanh hơn thôi nhưng
[01:23:49] mà các bạn học vì sao vì các bạn thấy gj
[01:23:53] nó khá ạ khá là dài dòng kiểu vẫn có thể
[01:23:57] nhanh hơn nữa bằng các phê thuốc mà về
[01:23:59] cơ bản tư duy nó thư viện rất là nặng
[01:24:01] nên thành ra là kiểu về sau không ai
[01:24:06] ở đây Các bạn thấy là rõ ràng vừa rồi
[01:24:09] Mình đã chơi theo cách riêng nữa đó là
[01:24:12] mình có thể dùng Switch để mà tạo ra hầm
[01:24:15] cái mặt hpl thì chị lỗi ngay bên cạnh để
[01:24:17] mình đỡ ngay từ lúc đầu mình có một cái
[01:24:22] span lỗi ở bên này không ạ thì cái này
[01:24:25] nhưng mà như này nó sẽ bị nhược điểm nó
[01:24:29] sẽ bị nhược điểm đó là kiểu Nếu thế thì
[01:24:30] trong trường hợp mà mình nhập Đúng rồi
[01:24:33] thì sao thì mình phải xóa cái cũ là đi
[01:24:36] đúng không ạ sẽ xóa cái cũ ấy đi sẽ khó
[01:24:39] bởi vì vốn dĩ cái này được tạo ra sau
[01:24:43] này nghe rất khó là bị xóa với mình thử
[01:24:45] cho các bạn một cả ID các bạn sẽ thấy
[01:24:46] hình dung này
[01:24:48] xin
[01:24:57] Giờ sự là em ở đây Toàn là đồ ngoại Tèo
[01:24:58] đây là
[01:25:02] thì mình sẽ làm thì cả ngày gì vẫn như
[01:25:05] cũ là mình sẽ lỗ mật khẩu
[01:25:09] nhtl mình cháu ông ạ mình cho bạn xem
[01:25:10] bí
[01:25:13] mật khẩu điện là bấm máy
[01:25:15] thì các bạn thấy lỗi không ạ
[01:25:18] có nhanh quá không ạ
[01:25:22] thì tại sao vừa tội lỗi nha Thì sẽ lại
[01:25:23] Tại sao vô tội lỗi
[01:25:25] xe tải
[01:25:29] a button ở đây bị xóa đây mưa rồi hãy
[01:25:31] một tuần Đấy à
[01:25:39] thì các bạn thấy lỗi ở đây nó bảo lỗi là
[01:25:43] không tìm thấy kệ cho comment ghét cái
[01:25:45] cái đoạn này nó gây lỗi này nhằm 93 này
[01:25:49] tất cả kể cái này chỗ là các bạn vừa mới
[01:25:53] dùng ra Swift để sinh ra rồi cái thằng
[01:25:56] Có ai đi à nhầm nhầm nhầm nhầm ai đi
[01:26:00] bằng mới đúng thiếu Thiện Ý
[01:26:03] à à
[01:26:07] anh ở đây này có vẻ nó vẫn nhận được
[01:26:10] chứng tỏ là thằng này chạy ra tạo ra sau
[01:26:12] đó thằng này lại được gọi lại nó vẫn
[01:26:14] nhận nhưng mà nếu là trong trường hợp
[01:26:17] mặt hàng này mà gọi được gọi trước được
[01:26:20] gọi trước nhé á
[01:26:21] Thì
[01:26:23] lúc đầu mình Điền xã mật khẩu như này
[01:26:27] bấm vào đây Các bạn thấy lỗi vẫn lỗi bởi
[01:26:29] vì rõ ra là thằng này nó không hề được
[01:26:31] tạo ra bởi tháng ai
[01:26:35] 300 tôi vẫn biết tôi đang nói gì mà
[01:26:38] Ừ đấy thì thằng này nó không được tạo ra
[01:26:41] bởi cái thằng thai được tạo ra khi lỗi
[01:26:42] ông ạ con khi thành công thì lại không
[01:26:45] được tạo ra thành A thằng này nó vẫn bị
[01:26:47] báo lỗi như này là không tồn tại đúng
[01:26:48] không ạ
[01:26:51] thì các bạn hiểu ý mình ngọn Thế này là
[01:26:54] thế nên lúc đầu mình vẫn nên có một cái
[01:26:57] thằng tồn tại ở đây không ạ hoặc à lúc
[01:27:00] đầu mình vẫn phải nên tồn tại trước sau
[01:27:02] đó thì mình cập nhật vào trong Thằng đấy
[01:27:05] nó sẽ ổn hơn thì việc tạo ra như này con
[01:27:08] chuẩn ra như này chuẩn dạy cho lôgic nó
[01:27:11] là lỗi thì tạo ra ông ạ Còn không lỗi
[01:27:14] thì phải xóa đi thì nó mới chuẩn Xóa đi
[01:27:16] Xóa hẳn nặng Penny Chúng mày Xóa lỗi
[01:27:20] HTML của nó thì mới hợp lý thì cái cái
[01:27:21] đoạn này thì ra vẫn làm được vẫn làm
[01:27:24] được bảo ra Speed là ông vẫn này kiểm
[01:27:26] tra span ở bên cạnh cửa hàng input đấy
[01:27:30] có hay không ạ sau đó mình xóa các fan
[01:27:32] đấy đi vẫn được nhưng nói chung nhà cốt
[01:27:35] bằng ra sweep thì nó sẽ ra lòng bằng gia
[01:27:38] công nhận ở trong nó vẻ ngắn gọn hơn sau
[01:27:41] khi nào tôi sẽ dạy cho cao ông về tí ri
[01:27:45] sau nhờ vấn đề về sau dậy sau
[01:27:47] bí ngô Vừa rồi tôi mới để mua qua cho
[01:27:49] ông đi ông ấy mấy cái vụ này mày ông
[01:27:52] hình nhớ lại việc là HTML có thể được
[01:27:56] sinh ra mở ra Speed đoạn ở đây tôi kiểm
[01:27:57] tra thêm một phát nữa đi Tôi muốn kiểm
[01:28:02] tra là mật khẩu chấm đen giờ sự là không
[01:28:05] được phép ngắn hơn 8 ký tự được ạ Không
[01:28:09] ạ sẽ báo lỗi tiếp đi nó sẽ như thế nào
[01:28:13] tôi sẽ đeo cuối này đoạn này nếu mà vẫn
[01:28:16] lỗi thì nó sẽ ra như thế nào ạ
[01:28:18] à à
[01:28:21] Ừ thôi tôi cứ vứt cài span lỗi ở trên
[01:28:25] trên này cho chuẩn nhé lỗi mật khẩu
[01:28:33] cho ví dụ không Nhập hai lần thì nó có
[01:28:35] sinh ra hai cái spam không
[01:28:38] Ừ Ừ hình như nó sẽ sinh ở 2 span Đấy
[01:28:42] bấm này bấm vào tiếp này đúng rồi nó
[01:28:44] sinh ra đúng rồi nó có kiểm tra việc
[01:28:47] span đã tồn tại đâu Thế bạn kia nói thôi
[01:28:48] mình nhớ ra đấy
[01:28:51] Ở đây còn chết nữa không ạ bởi vì mình
[01:28:53] không thể kiểm tra đúng không ạ Mình
[01:28:55] không kiểm tra gì cả nên thôi chúng nhớ
[01:28:59] là cái này nó không phù hợp đúng ạ
[01:29:02] ở tại Xóa đi thôi
[01:29:03] Anh
[01:29:14] à à
[01:29:31] bí mật khẩu không nên để chấm như thế
[01:29:32] này
[01:29:34] đi hái
[01:29:36] cho anh kiểu Nga
[01:29:39] ở đâu ạ bây ở trong trường hợp mà mình
[01:29:42] đi đầy đủ hết thì mình sẽ cho phom gửi
[01:29:50] cả các tổ chưa chỉ cho bạn kia vụ và tôi
[01:29:53] còn chửi bạn tôi bằng
[01:29:57] bằng tin cốt nhưng mà kết hợp với cả
[01:30:01] ngôn à gọi nhé
[01:30:03] bộ mã hóa
[01:30:06] cô gái tôi thường anh chửi bạn tôi đó là
[01:30:09] đi em cốt
[01:30:14] bay64 này cái Tại sao dùng bây giờ từ vì
[01:30:16] cái này có thể giải được cốt khá ông
[01:30:19] đừng có những cái kiểu mã hóa nó phức
[01:30:21] tạp quá không dài được
[01:30:25] cho tôi sẽ thường ai kiểu trẻ
[01:30:35] họ Hihi đồ ngốc trở lại ngày xưa thế sợ
[01:30:37] and cốt này nó sẽ ra xinh nha các bạn
[01:30:38] này ngon
[01:30:42] sau đó không Không những thế Tôi còn tạo
[01:30:46] phím tắt cho nó Tôi sẽ có cái bộ gõ gõ
[01:30:49] tìm việc tôi đây đúng không Mà cậu tắt
[01:30:53] này hoặc nó sẽ thay thế từ tôi gõ từ như
[01:30:56] thế này nó sẽ như này thêm này lưu lại
[01:31:00] đấy Sau đó thì cũng mỗi lần tôi gọi chứ
[01:31:05] này nó sẽ ra đó thôi tôi sẽ chửi bọn nó
[01:31:07] bằng cái từ đây tôi tôi có một đống phím
[01:31:10] tắt này Ở trên điện thoại tôi cơ kể trên
[01:31:13] mạch máy vừa rồi Ông thấy à có tắt nữa
[01:31:15] tôi trên này ít còn trên điện thoại của
[01:31:18] tôi đây Đầy gõ tắt chửi nhau bằng tin
[01:31:21] cốt nhưng mà được mã hóa mấy cái thang
[01:31:23] mà muốn xem tôi
[01:31:27] Anh xem tôi hiểu nói gì lại phải mất
[01:31:29] công lấy mạng để ngồi dịch lại dịch lại
[01:31:32] thấy mình chửi nó thế ấy rất là trai
[01:31:33] không hiểu
[01:31:35] hãy chửi nhau bằng
[01:31:37] anh bằng kiểu mã hóa
[01:31:39] anh nói thế khỏi mày Ông lại chuẩn bị
[01:31:42] lên tường nhà tôi mới Star cái cái từ mã
[01:31:43] hóa đâu nhé
[01:31:53] anh nói chung là điền đầy đủ thông tin
[01:31:55] bây giờ chắc là chạy được thôi ông ạ
[01:31:59] điền đầy đủ như này sẽ được rồi
[01:32:05] à à môi đang để nó bớt từng nghe này nếu
[01:32:08] nó sắp ít thì sẽ chạy được quen
[01:32:11] nhưng mà tôi bảo rồi chỉ đổi nó này sắp
[01:32:14] ít khi mà nói chung á kiểu ra Speed cao
[01:32:20] Ừ không thì nó sẽ hiển thị lỗi ra câu
[01:32:22] không không biết
[01:32:22] ở
[01:32:27] đó thì sẽ đưa xem ít à Đúng rồi còn cái
[01:32:29] trường hợp xử lý các chuẩn đấy tự nhiên
[01:32:31] tôi đề cập ở đây làm gì bởi vì nếu mà
[01:32:34] nếu mà giả sử hồi trước đã từng chơi trò
[01:32:37] này và thử cái À bởi vì thằng server nó
[01:32:39] không vai biết nữa Thành A tôi lách được
[01:32:41] qua nhưng mà tôi không khuyên với ông
[01:32:44] nên cho đấy nó cũng được tính là hack
[01:32:48] theo cậu là chích cho cậu mẹo bởi vì à
[01:32:50] có mấy Nếu không biết bản chất là khi mà
[01:32:53] chọn select options này nó nó lấy giá
[01:32:56] trị từ trong cái ô trên mình chọn không
[01:32:58] ạ Thế bây giờ sửa máy dùng nhát bằng
[01:32:59] cách là
[01:33:02] bằng cách à Giả sử cái này nó sẽ có cái
[01:33:04] khái niệm value cho từng ngày từng ngày
[01:33:07] Ocean này nếu không Zalo nó sẽ lấy đúng
[01:33:08] cái từ này luôn này
[01:33:11] Anh thường cái lập trình này nó sẽ value
[01:33:15] là sự bảo lưu à lớp 1 chàng ạ và cái này
[01:33:18] sẽ lưu ở lớp 2 được ạ kiểu ngay
[01:33:22] đấy thì khi bấm đăng ký này cái bản chất
[01:33:26] là nó sẽ gửi cái cái vô lu này lên chứ
[01:33:28] không phải là cái chữ mày Thị Loan ngay
[01:33:31] đâu thế bây giờ giả sử ở Tôi có trò rồi
[01:33:33] đấy rồi có cho tôi lách kiểu Nga phải
[01:33:36] sửa sư cái Selection lại sữa nó thành
[01:33:38] lớp 3 được ạ Như này
[01:33:42] lại như này rồi tôi tôi ở đăng ký ở đấy
[01:33:43] giờ đăng ký một phát được luôn không ạ
[01:33:46] Không không nghĩa chứng Do nó không
[01:33:48] virus bằng ra Switch cũng nhờ Không ai
[01:33:49] đẹp bằng
[01:33:52] bác em luôn nghĩa Nói chung là cứ điên
[01:33:53] lên
[01:33:56] em cứ điện này là được thì ra là tôi
[01:33:58] đăng ký cái gì đấy Không không phải đăng
[01:34:00] ký lớp học đâu anh gửi cái gì đó tự nhớ
[01:34:04] nữa Nhưng nói chung à đây mà em bé ông
[01:34:06] nghề sửa ảnh ngay Anh cách ra Swift để
[01:34:09] kiểm tra nó thì có thể là à
[01:34:13] ai có thể chỉ đơn giản là mình mình sẽ
[01:34:16] kiểm tra trong có trong danh sách hợp lệ
[01:34:18] hay không đúng không ạ Đấy có thể dùng
[01:34:21] ra kiểm tra kiểu như thế hoặc bác em thì
[01:34:24] kiểm tra do sóc kiểu gì tôi bảo rồi bác
[01:34:26] em phải kiểm tra lại một lần nữa ngoại
[01:34:28] bởi ra Swift thì thực ra nó vẫn bắt được
[01:34:32] cách lát ở đây đó là đơn giản là như nào
[01:34:33] với sẽ cho
[01:34:37] tôi ghi lại phẳng vẽ hàm kiểm tra này
[01:34:40] tôi tôi Đọc cốt ở đây đúng ạ với ẩn
[01:34:43] inspect này họ Tôi ăn cơm rồi Tôi xem
[01:34:46] tôi xem cốt được mà đúng không ạ à Chỗ
[01:34:50] này mày đi tên hành kiểm tra đây rồi
[01:34:52] Kiểm tra phone Có những thứ ta sẽ cho nó
[01:34:54] luôn hình chu được ngã thì sẽ mình sẽ
[01:34:56] ghi đè lên kiểu như này
[01:35:00] vì tên Chu tượng đã hứa sẽ luôn Chạy gì
[01:35:01] đó
[01:35:05] Em bấm vào nó sẽ luôn chạy đúng ạ Đấy
[01:35:09] thì thì có nhiều cách để mở reg thì nó
[01:35:13] sẽ dùng màn Swift về sẽ như thế
[01:35:15] khi tôi vừa rồi tôi nói qua các bạn về
[01:35:19] về Dash for bằng ra Switch mặc cũng
[01:35:22] những vài chưa trò nó như thế nào Vân
[01:35:23] Vân Vân đúng không ạ Các Bạn
[01:35:27] ý kiến thức hôm nay rất là nhiều đối với
[01:35:30] bạn là không biết gì về asp các từ thứ
[01:35:34] lần đầu học cảm thấy vỡ mồm đúng không ạ
[01:35:37] nhưng mà Đấy do có video này các bạn xem
[01:35:41] lại bà ngoại Còn bây giờ thì
[01:35:43] em tranh thủ chia sẻ thêm một vài cái
[01:35:44] nhỉ
[01:35:53] xe tải thì tôi như tôi đã nói thì tôi sẽ
[01:35:58] chia sẻ không được Đây là cái
[01:36:00] Vì vậy tôi có nghe bài này nó mặc định
[01:36:03] đang lấy cái bài gần nhất thu pháp tôi
[01:36:05] ta đã trang nữa sẽ nó nó nói chung là nó
[01:36:07] không hẳn lạ nhìn trông vẽ hiệu ứng thế
[01:36:11] thôi được nó dị ứng chung có vẻ Đang
[01:36:14] nghe rồi thứ kiểu nó đang lấy bài cô ấy
[01:36:15] tôi đã phát
[01:36:18] và phải tao lạy cha nó mới cập nhật bài
[01:36:22] Cô ấy kể kế đoạn đoạn này mình tự ghi
[01:36:25] đúng không đầu tiên thì cái trang lít H
[01:36:27] là cải trang để chia sẻ Cốt và người
[01:36:29] khác nhìn vào đánh giá ông rồng nhưng
[01:36:32] cái CV Thế nên thành ra là
[01:36:35] tôi muốn chia sẻ mấy ông này mấy ông sửa
[01:36:36] lại cái Trang Hý khắp mấy ông CHUNG TỬ
[01:36:39] TẾ một tí bởi vì đã còn nhiều nhà tuyển
[01:36:43] dụng tìm tôi qua kệ trang trí hát này
[01:36:45] A Man City những kiểu là nó gọi cho pp
[01:36:47] em ạ
[01:36:52] ở nhà giá trị với ông cách để mà các nhà
[01:36:58] Anh nhớ là
[01:37:07] Ừ anh vào đây phạm shop này đây
[01:37:11] anh không cần tìm ra đâu không tìm theo
[01:37:14] kiểu Ngôn ngữ đây p này sao thậm chí là
[01:37:19] thường pp được kết hợp với việc là à
[01:37:23] em ở Hà Nội chẳng hạn thế
[01:37:27] Em nhớ là có cái gõ ở Hà Nội đâu Tôi nhớ
[01:37:32] ở đây Hà Nội
[01:37:35] anh ạ
[01:37:37] chú chó
[01:37:39] Cho tôi nghe Tôi tìm tôi nó sẽ ra lên
[01:37:41] đầu rồi đúng không ạ nhưng mà còn rất
[01:37:44] nhiều nữa này có một loạt nè khi tái soi
[01:37:47] hễ inbox cố tìm cách để liên hệ những
[01:37:50] cái người này để mà để mà kiểu
[01:37:54] đi tìm kiếm thôi không ạ
[01:37:57] anh ấy thành ra là kiểu
[01:38:00] mấy ông phải chỉnh sửa lại cái trang
[01:38:03] get hát của mấy ông đi của bạn
[01:38:06] thì cách để mà đầu tiên để mở ra được
[01:38:08] cái như thế này thì đầu tiên mấy ông
[01:38:11] phải tặng cái Xipo xe Xipo có đúng tên
[01:38:14] theo đồng username của ông ấy Nó xảy ra
[01:38:16] được cái đoạn cái Trang đấy ông béo và
[01:38:18] sửa cái trang Britney
[01:38:21] ở đây tôi sẽ cho bé uống xem trang web
[01:38:22] mi của tôi
[01:38:23] bí
[01:38:26] ẩn Alo này xem
[01:38:29] ở đây nó sẽ ra như thế này cách để mà
[01:38:32] lấy cái đoạn như này thì
[01:38:35] Ừ thì hồi đấy à tôi à
[01:38:37] em tra Google thôi
[01:38:39] chai
[01:38:42] spotify It had
[01:38:45] playing ạ
[01:38:47] Cái nó sẽ
[01:38:50] chị sẽ xảy ra có ông Ai hướng dẫn cách
[01:38:52] để mà
[01:38:56] chị sẽ phải lên trang spotify để mà dán
[01:39:00] cắn quyền rồi các thứ thứ như nào nó
[01:39:02] cũng đọc nhé Em chịu khó đọc báo bằng
[01:39:05] tiếng anh một tí nhưng mà thực ra dễ
[01:39:08] thôi đấy thì nó sẽ ra Nói chung là đại
[01:39:11] khái được cái kiểu
[01:39:24] chị sẽ ra được cái này a tiếp theo mày
[01:39:27] cái ảnh này Thực ra là ảnh này tôi lấy à
[01:39:30] từ chính cái cái này
[01:39:31] chị
[01:39:34] sẽ ra một loa tất cả đây mấy ông thể
[01:39:37] internet để tìm nó nhanh ra cái ngôn ngữ
[01:39:39] hay là thư viện bé uống năng dung sau đó
[01:39:42] thì bé ông chè và tôi thích kể tôi đang
[01:39:45] dùng cái nền đen là cái thư viện này nó
[01:39:48] hỗ trợ cả màu đen với ô trong cũng được
[01:39:53] mà không ạ à tiếp ở đó nữa là cái này nó
[01:39:57] cập nhật blog tự động A và cái này cập
[01:40:00] nhật tự động luôn cả cái vụ YouTube
[01:40:03] video của tôi cái làm để làm được cái
[01:40:06] đấy thì qua chính cái video này tí thôi
[01:40:10] sẽ để link cái video này sẽ hướng dẫn
[01:40:13] mấy ông cách để mà vừa mới không biết
[01:40:16] qua việc là có một con server miễn phí
[01:40:20] của cụ thằng nào ấy ông ông rung con
[01:40:23] server đấy thì em à lấy liên tục thì bà
[01:40:25] đang từ blog của ông hoặc cả từ kênh
[01:40:29] YouTube của ông thậm chí là kiểu tạo à
[01:40:32] và sẽ tạo tự đánh giá qua trên trang ký
[01:40:35] hát của ông này mà đánh giá kiểu trông
[01:40:38] nói như thế này cái ảnh ấy
[01:40:39] xe tải
[01:40:42] à còn thêm cái đoạn nữa Ở đây mấy ông
[01:40:45] đang thấy là tôi cốt bao nhiêu tiếng này
[01:40:48] sử dụng cái gì nhiều này thì cái này là
[01:40:51] nó lại dùng cái á
[01:40:53] cho tôi không Trước tôi đề cập các ông ở
[01:40:57] qua Qatar này nó sẽ đánh giá đánh giá
[01:40:58] ông
[01:41:02] Ồ thông qua ở Việt à nó kiểm tra xem là
[01:41:06] ông một tuần không có bao nhiêu tiếng nó
[01:41:08] sẽ tự nó sẽ tạo ra một cái ảnh kiểu cựu
[01:41:11] thế Nó không đúng ở đây thôi
[01:41:13] Ừ thôi không nhớ cái đoạn này làm nhau
[01:41:22] Ừ bye bye kiểu step season cuaca máu mái
[01:41:24] ông cha cái đoạn này cho ra đấy qua cả
[01:41:27] start thứ thứ
[01:41:28] chợ
[01:41:35] hoa cà tham.tap iPad có mà
[01:41:39] khi đó sẽ ra được Kiểu trong ngày về
[01:41:39] chưa
[01:41:43] Ở đó có gì nói cho mấy ông thấy tôi có
[01:41:54] ở tạm như thế nhỉ Hôm nay chồng cũng
[01:41:56] giỏi đấy
[01:41:58] nghe nhạc không lại bị quá kiến thức
[01:42:01] không ạ Tôi sẽ gửi lại trong mấy ông các
[01:42:03] thử sao
[01:42:07] Ê mày ông còn thắc mắc gì không ạ
[01:42:10] Ừ khi nào chia sẻ buổi Đúng rồi còn chữa
[01:42:12] bài tập đúng không vẫn quen buổi trưa
[01:42:13] thật đấy
[01:42:16] Ừ thôi để bữa sau nha Để bữa sau đi vì
[01:42:25] cho bộ hôm nay ra khóa quá nhiều
[01:42:28] quá nhiều kiến thức rồi quá tải đấy nó
[01:42:34] bộ quà tặng Chào mấy ông em
[01:42:37] Ừ có gì thì bình luận Nếu mà Mấy ông
[01:42:40] thắc mắc gì buổi sao tôi giải đáp hết
