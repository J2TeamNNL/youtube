# Ngày 3/100 học Java - String Builder & String Buffer

- Video ID: `jA08bj_Wrlw`
- URL: https://www.youtube.com/watch?v=jA08bj_Wrlw
- Published: 2026-01-13
- Duration: 1h 59m 03s (7143s)
- Language: vi
- Subtitle source: auto
- Kind: live

## Transcript

[00:00:23] alo alo. Xin chào tất cả bạn. Alo.
[00:00:32] hôm qua. Ờ
[00:00:57] qua làm quả ảnh thăm.
[00:01:00] Ừ
[00:01:07] Gemini để tạo ra ảnh thăm nhưng mà
[00:01:18] đại khái nó nặng.
[00:01:20] Dùng cái gì để tạo ảnh thăm bây giờ độ
[00:01:22] giá thấp hơn, nhẹ hơn nhỉ?
[00:01:26] Ờ hỏi chat GPT đi.
[00:01:30] Đây
[00:01:33] lại tôi phải tạm bể như này cho nó bớt
[00:01:35] nhạy cảm. Che bớt nhạy cảm đã. Ờ
[00:01:45] nén ảnh
[00:01:48] để giung lượng
[00:01:51] online
[00:01:57] phí ở đấy. Đấy xin chào các bạn.
[00:02:02] Thực ra cũng đang không đang hiển thị là
[00:02:06] bốn người xem đồng thời
[00:02:14] đang không biết được là có ai đang xem
[00:02:16] không. Nhưng không quan trọng. Thường là
[00:02:20] à không phải nói các bạn không quan
[00:02:22] trọng mà ý là kiểu gọi như nào nhỉ? Là
[00:02:27] mình biết đa số những người xem của
[00:02:30] mình.
[00:02:31] thường không có thời gian để xem trực
[00:02:32] tiếp và xem lại là xem lại hoặc là nói
[00:02:37] chung xem sau ấy khá là lớn nên là tôi
[00:02:40] đang quay những cái này cho dù kể cả
[00:02:43] chưa có ai cả thì tôi vẫn sẽ phải nói
[00:02:46] bởi vì tôi biết được là
[00:02:49] à đôi khi ở chế giản chính bản thân mình
[00:02:52] về sau xem lại thôi cũng được cũng biết
[00:02:53] được tôi vẫn thỉnh thoảng hồi trước vẫn
[00:02:56] thỉnh thoảng có ngồi xem lại những cái
[00:02:57] video mình đương nhiên là tua thôi chứ
[00:02:58] không thể tua theo kiểu là x2 ấy. Ừ. Đấy
[00:03:03] là một trong những cái cách hay bởi vì
[00:03:05] nhiều người bảo là xem của anh nói khá
[00:03:09] là chậm nhưng mà x2 lên nó lại nhanh, nó
[00:03:12] lại hợp lý kiểu kiểu ừ mình lại cảm thấy
[00:03:16] có tí giống như kiểu hack thời gian. À
[00:03:18] đấy kiểu thế.
[00:03:21] Tiny image. Ok. Thử xem.
[00:03:30] utm x thực ra mấy cái ui bây giờ kiểu
[00:03:33] dùng vai code nhiều làm giao diện nhiều
[00:03:36] ấ nhìn cái này cũng giống như vai code
[00:03:38] ra ấy. Trông giống thật giống thật ý.
[00:03:42] Xem nào.
[00:03:45] Đây web đi nhìn giống cực.
[00:03:56] không? Hôm qua đã cố nén lại một tí rồi.
[00:03:59] Nhưng mà thực ra nó chả nghĩa gì. Hai
[00:04:00] thằng giống hệt nhau.
[00:04:04] Nén
[00:04:06] 7 m. Nén lại,
[00:04:09] nén lại cũng là tầm
[00:04:11] 3 m nhưng mà
[00:04:34] xem
[00:04:37] đây thử cái này xem.
[00:04:49] nặng hơn á. Ông bịp tôi à?
[00:05:03] Xong rồi sao?
[00:05:05] Now what? À xong rồi lựa chọn đây.
[00:05:11] Đấy xong rồi
[00:05:23] Nên thôi không sao m cũng được.
[00:05:40] ngần này mê đâu. Nhầm rồi.
[00:05:45] Nó bảo là à nó dự kiến ở đây. Ok. Th cử
[00:05:48] web như này đi cho chắc đi.
[00:06:07] vẻ hơi khó dùng.
[00:06:11] Ơ vừa rồi mình ấn hai rồi không mình
[00:06:13] chọn một thôi.
[00:06:17] Xin chào bạn
[00:06:19] xin chào các bạn. Các bạn cứ bình luận
[00:06:21] tôi vẫn để ý nhá.
[00:06:23] Smart gì đó đây. Thở giải thử nén.
[00:06:28] Ok. Uây kinh phết nhỉ. Đang từ 70 m
[00:06:31] trông như này mà
[00:06:34] các thứ thứ xịn nhỉ.
[00:06:41] Nút tải của tôi đâu? À đây này
[00:06:50] Ờ
[00:06:55] ảnh thăm. Để tôi a
[00:06:58] thay cho cái sau. À cái cũ và cái sau
[00:07:01] vậy
[00:07:11] cũng ổn mà đúng không? Cái này tôi dùng
[00:07:13] Gemini ấy. Gemini tạo ra ảnh ấy. Đó là
[00:07:17] tôi bảo là livestream YouTube. Cái này
[00:07:20] không phải tôi đâu nhá. Mấy không thấy
[00:07:22] mà đúng không? Cái này không phải tôi.
[00:07:24] Tôi bảo livestream YouTube để học 100
[00:07:27] ngày học Java đấy, xong rồi vân vân vân
[00:07:30] cái gì gì đó. Ui ngày một mà như này
[00:07:32] đấy.
[00:07:34] Dũng Huyền ở đây ai tôi không biết.
[00:07:38] Nhưng mà nói chung là tôi cũng muốn hay
[00:07:39] cái ảnh kia vì cái ảnh kia tôi lấy trên
[00:07:43] mạng về không biết có bị dính bản quyền
[00:07:45] gì không đấy. Nhưng mà mình nên né đúng
[00:07:48] không?
[00:07:55] mấy cái này.
[00:07:57] Tôi sẽ
[00:08:11] Còn
[00:08:14] còn bài hiện tại thì có vẻ là đang
[00:08:20] nhỉ?
[00:08:21] Ơ thay được ảnh thăm bài hiện tại này
[00:08:25] ngon.
[00:08:27] Ơ nhưng mà nó vẫn còn chữ ngày một.
[00:08:35] để tôi thử dùng JD bảo tạo hai xem như
[00:08:38] nào. Đợi đợi tôi một tí nhá. đang hơi
[00:08:41] rảnh một tí.
[00:08:47] cho tôi ảnh ngày hai đấy.
[00:08:52] Xem nhờ hay là nó chỉ thay đổi mỗi cái
[00:08:55] chữ ngày hai là nó sẽ thay đổi cả những
[00:08:57] cái khác nữa. Tôi thì đang mong chờ là
[00:09:00] nó sẽ thay đổi một tí cái khác nữa nhưng
[00:09:02] vẫn giữ nguyên cái tông đấy.
[00:09:06] Ngồm lắm là đoạn code ở trên này thay
[00:09:07] đổi này chẳng hạn. Thế đúng không ạ?
[00:09:17] kiểu German
[00:09:20] AI Pro à. Đấy nên là tôi sẽ phải dùng
[00:09:22] triệt để nó. hôm nay cũng ngồi bình luận
[00:09:27] ở trên J2 Team Community bảo là nghĩa là
[00:09:31] hôm nay Apple công bố là sẽ tích hợp
[00:09:34] Germany vào thay thế cho Apple
[00:09:38] Intelligent nghĩa là AI của Apple không
[00:09:41] được tốt ấy nên là thôi dùng luôn của
[00:09:45] Gemini làm trợ ý ảo đấy tôi thì tôi thì
[00:09:49] bảo là Gemini có tốt nhưng mà Gemini
[00:09:51] cũng có tốt đâu. Đấy thì mọi người cũng
[00:09:53] có ném đá.
[00:09:56] Tôi thì thực ra tôi chưa dùng Gemini à.
[00:09:58] Tôi có dùng Gemini nhưng mà trên Android
[00:10:01] để làm trợ ý ảo thì tôi thấy nó rất là
[00:10:02] củùi. Thậm chí là chat dùng ứng dụng
[00:10:05] chat cũng rất là cùi nên là tôi a không
[00:10:09] thích nó lắm.
[00:10:11] Ơ thật này, nó chỉ thay mỗi ngày hai cả
[00:10:14] số hai này. Có tất cả còn giữ nguyên ạ.
[00:10:16] Ok.
[00:10:24] Thôi cũng được.
[00:10:32] nhờ bắt bắt nó ngồi làm tiếp cũng được
[00:10:35] cho trùng một tông.
[00:10:42] nhờ ai làm này
[00:10:45] tí
[00:10:47] à. đổi
[00:10:50] cho tôi màn hình code và phần bình luận.
[00:10:57] Còn đâu giữ nguyên
[00:11:00] những cái khác
[00:11:03] thử nhá.
[00:11:06] Nghịch tí.
[00:11:27] ait hôm qua của tôi có cập tôi mới cập
[00:11:30] nhật đấy thì tôi có cập nhật à
[00:11:33] bổ sung thêm ví dụ hôm qua đã kiểu anh
[00:11:37] em mình đã chốt là thêm được vài cái mới
[00:11:39] thực ra mình còn chưa học đến đúng không
[00:11:41] nhưng mà hôm nay có bạn nói với tôi, bạn
[00:11:44] ấy cũng kiểu kỳ cứ cho là tôi cảm thấy
[00:11:47] là rất là xịn rồi, cũng chắc cũng phải
[00:11:51] là senior rồi. Bạn ấy tư vấn cho tôi về
[00:11:55] à
[00:11:58] tool chọn banana nó hơi nó gen ảnh xịn
[00:12:01] hơn ha.
[00:12:09] không không để ý được để là để khác
[00:12:14] code này hay gì? Bài tập hôm nay hay quá
[00:12:18] cố lên. Ok tiếp nào. Xin ch
[00:12:22] ơ nhưng mà thy vẫn giữ nguyên được. Cái
[00:12:24] này cũng đỉnh đấy. Bởi vì thằng chatt
[00:12:28] hồi trước nó không giữ được cái kiểu
[00:12:29] tông như này đâu. Được đấy. Cũng giữ
[00:12:32] được các thứ thứ. Thay ngày hai này. Màn
[00:12:35] hình khác này. Màn hình lần này Java
[00:12:37] hiển thị rõ chữ thêm code mới ở đây này.
[00:12:42] Màn hình code hồi trước thì trông xịn
[00:12:45] hơn, ngầu hơn. Màn hình này trông kiểu
[00:12:48] thôi cũng được. Dai. Ok cũng được.
[00:12:59] À quên phải nén nó lại đã.
[00:13:02] À xem nào.
[00:13:16] Thêm rồi. Ok. Nén gì đó vẫn là 7 m
[00:13:32] kiểu giao diện đúng kiểu giao diện ai
[00:13:35] làm hay gì đó sao
[00:13:37] trông không dễ dùng lắm. Tôi cảm thấy
[00:13:40] thế đấy. Đợi tí thay ảnh mới.
[00:13:46] Ok.
[00:13:55] tham mới trống xịn phết nhỉ. Được. Bây
[00:13:59] giờ mỗi ngày tôi sẽ vào tôi cập nhật
[00:14:02] thêm.
[00:14:03] Ok. Rồi thì hôm qua à chính xác hôm nay
[00:14:08] bạn đấy mới bảo tôi bổ sung thêm cái
[00:14:11] khái niệm là mental
[00:14:14] men mentor
[00:14:15] cái gì? Tôi không biết phát âm cái từ
[00:14:18] này chuẩn mental mà đúng không?
[00:14:21] Go dịch nào?
[00:14:25] Translate
[00:14:31] &gt;&gt; Mental đúng rồi. Mental
[00:14:33] mental
[00:14:35] model đấy nhưo, Java. Đấy. Thay vì kiểu
[00:14:40] hôm mấy hôm trước là mình sẽ học kiểu
[00:14:43] map 11 từ PP sang, tức là PP có cái gì
[00:14:47] thì mình sẽ map sang và mình sẽ so sánh
[00:14:50] sự khác biệt. Còn cái này thì nó sẽ liên
[00:14:52] quan đến tư duy cất lõi này. Đấy, đọc
[00:14:55] trước khi học. Uầi. Đấy, anh em mình sẽ
[00:14:58] ngồi à đọc qua một trước một chút được
[00:15:01] không ạ? Đấy, dùng màn hình này cho dễ
[00:15:03] nhìn nhá.
[00:15:17] PP. Đấy, đầu tiên thì PP đấy. Kiểu hôm
[00:15:22] đề cập cái này khá là hay vì tôi không
[00:15:24] biết cái này thật. Tôi có thể mấy ông
[00:15:26] biết nhưng tôi không biết thật. Đây ví
[00:15:28] dụ là một request thì khởi động lại thì
[00:15:31] cái này thì anh em PP biết này. Nhưng mà
[00:15:34] cái này còn sống lâu này. Duy trì các
[00:15:36] nghĩa nó vẫn chạy tiếp được. Đấy, cái
[00:15:38] này tôi không phải biết kiểu memory tự
[00:15:41] giải phóng xong mỗi request. Đấy, tôi
[00:15:43] nghĩ là đây là một trong những cái lý do
[00:15:44] mà bọn tôi không quan tâm đến cái
[00:15:46] memory, không quan tâm đến quản lý cái
[00:15:50] bộ nhớ. Đấy, bởi vì rõ ràng là sau
[00:15:54] request là nó sẽ được xóa sạch kiểu thậm
[00:15:57] chí là sau mỗi method. Tôi nhớ tôi nhớ
[00:16:00] là thế.
[00:16:02] Để tí hỏi lại xem. Hỏ lại luôn nhỉ.
[00:16:06] Ừ, hỏi lại luôn.
[00:16:08] À nhưng mà trong này à trong này không
[00:16:12] tôi nghĩ là tôi hỏi ở trong chatt này
[00:16:15] đi. À
[00:16:18] sau
[00:16:21] mỗi request
[00:16:32] bộ nhớ.
[00:16:34] À đâu chắc là bỏ cái này đi sau mỗi
[00:16:39] đúng không? Đây
[00:16:50] dần trong quá trình chạy
[00:16:52] biến cục bộ
[00:16:56] không còn tham chiếu nhưng thu hồi thực
[00:16:58] sự reference
[00:17:01] rabit collector.
[00:17:05] Nếu con reference return ra ngoài gắn
[00:17:07] vào property
[00:17:14] method đấy khai báo trong method đấy và
[00:17:16] kết thúc metus thì tôi nghĩ vẫn sẽ giải
[00:17:18] phóng
[00:17:30] không chạy sau mỗi method nghĩa là nó
[00:17:32] vẫn còn ở đấy nhưng mà cái này khi nó sẽ
[00:17:35] tự động chạy sau kiểu đạt cái ngưỡng ở
[00:17:38] đó thì chạy. Ok.
[00:17:49] Property object này.
[00:17:53] Closer này. Global scope này. CCL
[00:17:57] reference này.
[00:17:59] Long run process này. Đấy. Ok.
[00:18:13] này tôi chưa dùng. Microservice thì thực
[00:18:15] ra là có kiểu đang tôi còn đang không rõ
[00:18:19] là công ty có đang chơi theo kiểu dùng
[00:18:21] microservice hay không.
[00:18:28] lớn dài trong lúp dài tránh giữ
[00:18:31] reference chia nhỏ.
[00:18:42] circle
[00:18:49] phết hay phết. À có nhắc đến Java này à
[00:18:52] chắc là nó nhớ tôi đang học Java. Ok.
[00:18:56] Không quan tâm th đúng không? Còn không
[00:19:00] biết th nó tồn tại ở trong PP luôn ấy.
[00:19:04] Đấy. À đấy là tôi vẫn đang nói là cái
[00:19:07] trình độ tôi nhá. Ôi tôi bắt đầu
[00:19:10] suy nghĩ lại khái niệm mình có chắc là
[00:19:13] sino không hay mình chỉ là làm lâu
[00:19:21] ứng dụng
[00:19:23] Java hệ thống dài hạn đây không phải
[00:19:27] second nghĩa là thường là người ta vẫn
[00:19:29] khuyên là làm một cái web nào nhanh thì
[00:19:31] mình sẽ dùng PP
[00:19:34] còn à trong trường hợp mà mình gọi là
[00:19:37] mình à
[00:19:39] Java đúng không? Thì làm một cái hệ
[00:19:41] thống làm một cái gì đó kiểu cần cần
[00:19:45] phải maintain tên, cần phải duy trì lâu
[00:19:46] dài. Đấy nó không phải làm mỗi cái kiểu
[00:19:50] làm nhanh gọi là hơi ăn sổi một tí đúng
[00:19:53] không? PP thậm chí là Gopet chẳng hạn.
[00:19:58] Đây
[00:20:03] cùng một class nó vẫn chạy được. Đấy
[00:20:05] kiểu thế nó khác với kiểu bên này đại
[00:20:08] diện với các thứ thứ gì đó phải op phải
[00:20:11] hướng đối tượng phải các thứ phải kiểu
[00:20:15] giảng buộc hơn.
[00:20:25] inmobility
[00:20:32] chắc là vẫn phải thế là làm dần mới
[00:20:35] hiểu.
[00:20:38] Content này hay nhé anh. Thực ra tôi
[00:20:41] phục vụ cá nhân tôi là chủ yếu chứ không
[00:20:43] phải mấy ông. Bởi vì rõ ràng là tôi a
[00:20:47] tôi có tham khảo mấy ông đâu. Tôi à
[00:20:49] không phải dùng từ không tham khảo mà
[00:20:51] tôi không hỏi ý kiến mấy ông. Tôi vẫn
[00:20:53] làm mấy cái này
[00:20:56] sẽ có người thấy phù hợp, có người thấy
[00:20:58] là
[00:20:59] họ biết rồi chẳng hạn hoặc đơn giản là
[00:21:01] họ chưa đến
[00:21:05] họ chưa đến cái giai đoạn mà cần phải
[00:21:06] biết một cái này. Đấy rất nhiều cái nên
[00:21:09] thành ra là tôi chỉ chia sẻ lại vì vẫn
[00:21:14] luôn là theo cái phương hướng là mình
[00:21:16] chia sẻ và ai thấy có ích thì thì tốt
[00:21:20] cho họ thôi. Còn mình thì mình thích
[00:21:22] chia sẻ thì mình cứ chia sẻ
[00:21:26] PP mãi
[00:21:28] mute là bất biến à.
[00:21:33] Ok để xem để xem
[00:21:36] cái này nhiều từ tiếng Anh chuyên ngày
[00:21:38] phết đấy.
[00:21:50] executor này. Uầy uầy thựt ra tôi nghĩ
[00:21:53] là đọc cái đống này xong quá tải không
[00:21:55] ạ?
[00:21:57] Thôi cứ từ từ từ đã nhé. Tôi nghĩ sẽ từ
[00:22:00] từ. Hôm trước làm cái buổi một, hôm qua
[00:22:04] ôn buổi một. Ok này. Hôm nay nhắc lại
[00:22:06] buổi hai một tí nhá.
[00:22:10] Hôm nay là buổi ba nhưng mà ừ nhỉ? Hôm
[00:22:13] nay chuẩn là buổi ba. Đấy. Cái tiêu đề
[00:22:15] của cái video ghi là buổi thứ hai. Nhưng
[00:22:18] thực ra hôm nay hôm trước tôi đã học một
[00:22:21] buổi offline rồi.
[00:22:28] rồi mình sẽ sang buổi ba nhá. Thì hôm
[00:22:31] qua tôi nhớ quả string bull này rồi đấy.
[00:22:34] Lúc đầu như lúc đầu tôi nói tôi còn nhầm
[00:22:37] tưởng cái ba chấm này nó tạo cho một cái
[00:22:39] kiểu gì đó
[00:22:46] là để mà ghi lại những cái công việc mà
[00:22:49] tôi sẽ làm thì tôi dùng cái Microsoft
[00:22:51] Todo. Tôi có biết cái
[00:22:56] notion nhưng mà tôi không dùng nó cũng
[00:22:59] như là dùng cái
[00:23:02] dùng cái gì nhỉ? dùng Google Keep thì
[00:23:05] thực ra nó lại kiểu tôi không ghi chú
[00:23:08] nhiều tôi thường là chỉ ghi lại các ý
[00:23:11] tưởng và các và tôi co nó các đầu việc
[00:23:14] đấy gọi các tas đúng không to do list
[00:23:17] đấy thì tôi tùng dùng cái Microsoft to
[00:23:20] do này này đây đấy của tôi có rất nhiều
[00:23:23] đầu việc tôi đi sẽ mở cho mấy ông xem
[00:23:26] như là tôi sợ là có gì nhạy cảm nên là à
[00:23:29] đây đấy kiểu như này mấy ông sẽ thấy
[00:23:33] Trong hôm nay tôi đã cố làm xong hết
[00:23:35] rồi.
[00:23:37] Đây các đầu việc này. Xong rồi. Đây
[00:23:40] những công việc trên công ty này. Cái
[00:23:42] này dự án này đấy khi quay dậy này.
[00:23:46] Notốt lại những cái mà mình sẽ quay dậy
[00:23:47] các thứ. Đấy đi du lịch thì sẽ cần những
[00:23:50] cái gì? Ý tưởng này, mua sắm này. Đây
[00:23:54] cũng là mấy cái mẹo về dạy này, khám
[00:23:58] này,
[00:23:59] à học này học à đây mình tích việc của
[00:24:03] mình đang học Java nữa xong còn ý định
[00:24:06] đi chung này. Đấy, đây là viết tắt của
[00:24:10] tên bạn gái.
[00:24:12] À cái này là mình cái tiện ích gần đây
[00:24:15] tôi có làm thì tôi kiểu đánh dấu lại
[00:24:18] kiểu có ý tưởng gì cho nó hoặc là đây có
[00:24:20] ai báo bức gì thì mình sẽ nốt lại. Đây
[00:24:23] nó to đ mà. Đấy làm á ma sói. Á ma sói
[00:24:27] này hình như là mình mới chỉ tạo repo
[00:24:30] mình cũng chưa làm gì. Bắt tay làm. Nói
[00:24:31] chung là có rất nhiều ý tưởng để vi code
[00:24:33] nhưng mà chưa làm cả cái
[00:24:37] ứng dụng này nữa. Cái ứng dụng này là
[00:24:46] cái quả là đồng bộ trên các mọi nền tảng
[00:24:51] nhưng cái đấy sẽ đang ý tưởng thứ ý
[00:24:53] tưởng từ lâu rồi nhưng mà vẫn chưa thời
[00:24:56] gian. Và đây cái này nữa là cái trang
[00:24:59] web cho cá nhân. Nghĩa là
[00:25:04] ô để tôi vào lại cái trang của chính
[00:25:06] mình đã sợ quên. Đúng rồi
[00:25:09] đấy. Trang web chtimnl.com của tôi.
[00:25:12] Nhưng mà bây giờ biến thành cái trang tỏ
[00:25:14] tình. Mấy ông có có gì mấy ông đừng vào
[00:25:16] nhá. Nhưng đại khái thì hồi trưa tôi có
[00:25:19] tôi sẽ ngồi sửa lại cái trang này để
[00:25:24] nó thành một cái trang giống
[00:25:27] portfolio à
[00:25:30] không nhớ cách phát âm chuẩn từ đấy lắm
[00:25:33] xem
[00:25:46] Portfolio
[00:25:48] đấy đúng nhỉ? Viết đúng nhỉ?
[00:25:52] Đúng rồi. Portio
[00:25:56] đấy. Nghĩa đại khái thì bình thường mấy
[00:25:58] không biết về khái niệm CV rồi nhưng mà
[00:26:00] CV mình sẽ viết ngắn gọn ở trên trang
[00:26:03] đấy. Thường là chỉ là một trang thôi
[00:26:06] nhưng mà rõ ràng là một cái trang cá
[00:26:08] nhân của ông thì ông hoàn toàn có thể
[00:26:10] kiểu liệt kê ra hết toàn bộ cái những
[00:26:13] cái dự án ông từng làm xong rồi giới
[00:26:15] thiệu bản thân. vân vân tù thứ đấy thì
[00:26:17] nó sẽ khái niệm
[00:26:19] port portfolio gì đấy. Đấy thì tôi sẽ
[00:26:23] sửa lại cái trang web cho chính mình.
[00:26:25] Bởi vì hôm trước tôi bảo tôi dùng AI để
[00:26:27] mà ngồi ném đá CV của tôi ấ thì nó cũng
[00:26:30] đề cập về vụ đấy. Nghĩa là mang tiếng
[00:26:32] kêu là mày lập trình viên web mà mày lại
[00:26:36] tải CV từ top CV à. Đấy kiểu mày đáng lẽ
[00:26:39] phải có một trang riêng đấy vân vân. Đấy
[00:26:42] phải có một CV riêng gì đó. Đại khái
[00:26:44] thế.
[00:26:47] Ờ thanh niên xài hệ Apple chơi hàng
[00:26:52] Microsoft.
[00:26:54] Đúng. Thực ra là tôi muốn a thực ra là
[00:26:56] tôi muốn là kiểu dùng chung hết vào một
[00:26:58] cái thôi. Ví dụ giả sử là tôi chính ra
[00:27:01] tôi không thích Microsoft hoàn toàn tôi
[00:27:03] thích Google nhất. Nhưng mà bây giờ để
[00:27:06] mà kiểu mình tự add bản thân mình dùng
[00:27:09] mấy cái kiểu như là bây giờ là phải dùng
[00:27:12] hồi trước Google có
[00:27:15] laptop là Chromebook này. Đấy dùng
[00:27:18] Chromebook
[00:27:20] đã thấy là cẩu tự mình vào một cái hệ
[00:27:23] sinh thái rồi kín rồi đấy. Xong rồi. À
[00:27:27] nói chung là tôi cảm thấy là mình là dân
[00:27:30] công nghệ mình nên trải nghiệm đồ không
[00:27:34] hẳn là trải nghiệm theo kiểu là
[00:27:36] kiểu tôi vẫn sợ cái kiểu FOMo à
[00:27:45] Là tôi biết từ đấy dịch tiếng Việt nhưng
[00:27:48] mà để nói văn văn vở là như nào nhỉ? Nói
[00:27:51] chung là tôi không chạy theo xu hướng
[00:27:53] đấy. Tôi không chạy theo xu hướng nhưng
[00:27:55] mà tôi vẫn cảm thấy là cái gì mà tôi
[00:27:58] thấy tôi sẽ dùng thử đúng không? Cái gì
[00:28:01] mà cảm thấy nó phù hợp với cái nhu cầu
[00:28:03] của mình thì mình dùng. Đấy,
[00:28:10] các thứ thế thì tự nhiên mình bị cuốn
[00:28:12] theo ấy. Và và lúc đấy mình lại không có
[00:28:16] cái
[00:28:18] ý kiến chính kiến riêng của bản thân
[00:28:20] mình là thực sự là nó đủ tốt mà mình chỉ
[00:28:23] nghe cái khác nói tốt thì thôi mình
[00:28:24] dùng. Đấy, mình phải thực sự là mình
[00:28:27] dùng qua một cái này xong mình chuyển
[00:28:30] qua khác. Có lý do. Ví dụ giả sử nhá, có
[00:28:32] bạn vừa nhắc là tôi hồi trước tôi dùng
[00:28:34] Win chẳng hạn. Thực ra tôi vẫn có máy
[00:28:36] dùng Win ở đây bởi vì đi dậy thực ra là
[00:28:40] các bạn vẫn phải dùng máy win bởi đôi
[00:28:42] khi là kết nối máy vân vân nhiều cái
[00:28:44] hoặc chỉ đơn giản là các bạn thao tác
[00:28:47] mọi thứ thì kiểu gọi nh học sinh sinh
[00:28:51] viên mình có thể nhìn được mình thao tác
[00:28:54] và có thể bắt trước làm ở trên máy nhà
[00:28:56] trường hay gì gì đó
[00:28:59] nên lượng người dùng Win bây giờ đông mà
[00:29:01] nên là mình sẽ phải kiểu làm mẫu cho học
[00:29:04] sinh là nhiều đấy nên vẫn phải dùng win.
[00:29:07] Vẫn có những phần mềm chỉ cài được trên
[00:29:09] Win đấy nhưng mà bây giờ là tôi cùng
[00:29:11] code thì máy này chuyên để code hay các
[00:29:14] thứ thì rõ ràng là tôi và tôi bây giờ
[00:29:18] không chơi game mấy nữa nên thành ra là
[00:29:19] tôi dùng M vẫn được
[00:29:22] nhưng mà mình vẫn sẽ có nhiều hàng thô
[00:29:24] chẳng phải của Apple. Thực ra Apple thì
[00:29:27] chắc là về phần cứng hơn. Về phần mềm
[00:29:29] thì tôi vẫn thấy không được phá lắm
[00:29:34] nên là vẫn không dùng.
[00:29:36] Ok. Đấy thì tôi dùng cái app Microsoft
[00:29:39] Tod. Nó có cả trên mọi hệ điều hành. Các
[00:29:42] bạn vừa thấy là nó có ở trên M đúng
[00:29:44] không ạ? Vẫn dùng được, vẫn ngon.
[00:29:47] Ok. À
[00:29:50] đúng. Sợ nhất là cái phần mà kiểu mỗi
[00:29:53] nơi 1 tỷ ấ xong rồi mình sẽ phải đồng bộ
[00:29:54] sang đúng không? Đấy do tôi dùng
[00:29:56] Microsoft Tod vì nó là nó có trên mọi
[00:30:00] mọi cái từ trên máy tính này từ trên
[00:30:03] điện thoại này, trên cả hệ sinh thái
[00:30:05] khác này. Chắc là Linus thì nó chưa có
[00:30:07] thôi nhưng mà tôi không dùng Linus đấy.
[00:30:14] RAM cao chắc quá.
[00:30:16] Thực ra thì
[00:30:19] ma nó đang có một cái rất là hay
[00:30:22] nhưng mà tôi vẫn đang cố kiểu lên con
[00:30:26] cao nhất đấy. Nhưng mà thực sự thì ma có
[00:30:29] cái rất là hay. Nó khác với win ở một
[00:30:31] chỗ đó là
[00:30:34] là bình thường là win mà ra 18 thậm chí
[00:30:38] 8 đúng không? Rồi xác định kiểu chỉ chạy
[00:30:41] được mấy cái cơ bản đúng không? Nhưng mà
[00:30:44] Mar thì ngoài việc tối ưu gì đó như bọn
[00:30:48] nó hay nói. Đấy cái đấy tôi không biết.
[00:30:51] Tôi không phải chuyên gia để mà th để mà
[00:30:53] ngồi so sánh hay là ngồi mở cái gì đó
[00:30:56] lên để đo. Nhưng mà tôi sẽ cảm nhận được
[00:30:59] là 16 GB RAM của M kết hợp với việc là
[00:31:05] nó còn chạy khái niệm là nó chạy chèn
[00:31:07] sang cái nó là cái chạy chèn sang cái
[00:31:11] swap này này. Đấy nghĩa là ông dùng
[00:31:15] memory ở đây rồi đúng không?
[00:31:17] Đấy, đây là gig RAM của ông này. Ông
[00:31:20] dùng memory bình thường ông dùng ở đây
[00:31:23] xong rồi nó còn nhảy qua scrap là nó sẽ
[00:31:26] dùng vào trong bộ đĩa của ông ấy. Đương
[00:31:28] nhiên là nó không nhanh bằng RAM nhưng
[00:31:30] mà nó vẫn kiểu nếu mà ông thiếu quá nó
[00:31:33] vẫn nhảy vào đây thì nghĩa là ông vẫn mở
[00:31:35] được, vẫn mở được các phần mềm các thứ
[00:31:38] chẳng qua nó có thể chậm hơn. Xỉ gì
[00:31:39] không? Nghĩa là rõ ràng là thực tế là 16
[00:31:42] GB của M là tương đối hơn so với 16 của
[00:31:48] Win rồi đấy. 16 của Win mở thêm cái là
[00:31:53] treo luôn đúng không ạ? Còn ma thì không
[00:31:55] treo. Đấy được
[00:31:59] ok. Thôi nó hơi ra dòng tí. Nói chung là
[00:32:02] mấy ông cứ bình luận thì tôi vẫn tôi vẫn
[00:32:06] đọc và tôi vẫn trả lời nhá. Có gì tôi
[00:32:08] lại ngồi học tiếp thôi.
[00:32:10] Đấy, dùng cái nháy kép này để mà để biến
[00:32:15] nó là cũng khai báo nó string nhưng kèm
[00:32:18] theo là sẽ đẩy vào string pool đúng
[00:32:20] không ạ?
[00:32:23] Uầy mấy cái này mấy cái từ khóa này về
[00:32:26] sau chắc là chắc là đi phỏng vấn người
[00:32:28] ta không hỏi mấy cái lý thuyết này đâu.
[00:32:31] Đấy nhưng mà vẫn phải biết từ khóa để
[00:32:32] tra đúng.
[00:32:39] bộ nhớ. Tôi có nhớ cái này. Phông chữ á
[00:32:44] phông chữ phông chữ này phông chữ bình
[00:32:46] thường mà nhỉ. Tôi không dùng cái phông
[00:32:48] chữ đặc biệt đâu. Rõ ràng có nhiều cái
[00:32:50] hồi trước xem mấy cái hay. Nhưng cái này
[00:32:52] đang dùng phông chữ bình thường đấy. Hồi
[00:32:55] trước là tôi nhớ ở quả tôi cũng màu mè
[00:32:58] dùng cái phông Monalisa xong rồi à xong
[00:33:02] rồi gì à file code gì đó. Còn cái này
[00:33:06] phông bình thường thôi.
[00:33:10] Tôi chẳng qua đang để màn hình to đấy. À
[00:33:34] tôi chưa dùng.
[00:33:36] À
[00:33:41] tuy khai báo giống hệt nhau nhưng mà
[00:33:44] không cùng địa chỉ nên là dấu bằng bằng
[00:33:46] không được. Thì so sánh dùng equal để mà
[00:33:48] có thể bằng được. Hôm qua còn chơi lớn
[00:33:51] là hôm qua mình thử dùng kiểu như này
[00:33:53] dùng to cha array. Không biết mình
[00:33:55] reverse lại được không? Chắc không
[00:33:56] reverse được.
[00:33:59] Thế không sao mình sẽ
[00:34:02] à thôi cái này cũng được không sao
[00:34:21] này sao bằng được đúng không
[00:34:30] Ồ hợp lý nhỉ? Ừ
[00:34:42] trình là tôi thì tôi cũng a kiểu kiểu
[00:34:46] cài mọi thứ cho mồm mè. Tôi vẫn nhớ tôi
[00:34:48] vẫn nhớ. Không biết mấy ông xem chắc là
[00:34:51] không quen tôi thời đầu đấy đâu. Vì hồi
[00:34:54] đấy tôi mới 52 thôi. Tôi còn để cái hình
[00:34:56] nền kiểu di hảnh logo đại bàng J2 này.
[00:35:01] Đấy xong rồi còn nó là back nó video cơ.
[00:35:04] X background nó sẽ kiểu mờ mờ mờ mờ dần.
[00:35:06] Đấy, xong rồi. À dùng cái bởi vì đang
[00:35:10] dùng Win nên là dùng cả phần mềm để mà
[00:35:13] làm nó là phần mềm class gì đó làm cho
[00:35:16] mờ mờ cái a mờ cái kiểu gõ cái gõ code
[00:35:21] cái editor hoặc là IDE này. Xong rồi đấy
[00:35:25] xem cái video ở đằng sau. Hô đấy còn một
[00:35:28] lần nữa còn vừa ngồi code vừa xem cái
[00:35:31] video đằng sau là DJ Soda nữa đấy. Hơi
[00:35:35] trẻ trâu.
[00:35:42] fure hôm qua có đề cập đây. Đầu tiên là
[00:35:45] mình sẽ khai báo rõ ràng nó là một cái
[00:35:50] gọi là
[00:35:51] gọi là gì nhỉ? New này là tạo một object
[00:35:54] mới. Ừ nhưng mà nó không có từ khóa nó
[00:35:56] nó chỉ là new object mới thôi đúng
[00:35:58] không? Tạo bằng OK rồi không dùng không
[00:36:02] tạo bằng literal đúng không? Đấy nhưng
[00:36:06] mà mình dùng cái hàm intern thì nó cũng
[00:36:09] sẽ đẩy vào pool đấy.
[00:36:12] Ok. Và cái này khi mà cũng dùng từ pịa
[00:36:32] cái này là à đâu chính xác là thằng S8
[00:36:36] tuy là khai báo intern nhưng mà
[00:36:40] nhưng mà thằng S8 lại không bị đẩy vào
[00:36:42] P. F8 vẫn nằm ở ngoài p, chỉ có S9 mới
[00:36:45] nằm ở trong pu thôi. Ồ,
[00:36:52] đời.
[00:36:53] Ok, không hiểu lắm, không sao.
[00:37:02] địa chỉ đâu anh. Nó chỉ so sánh địa chỉ
[00:37:04] khi dùng từ khóa New thôi ạ. Hả? S1, S2.
[00:37:09] Thế á? Ông đừng lừa tôi nhá.
[00:37:13] F1 với2 này không phải so sánh cùng địa
[00:37:15] chỉ á.
[00:37:23] Vừa mới học cái này so sánh cụng địa chỉ
[00:37:25] xong.
[00:37:27] Đâu xem à có người bảo tôi là
[00:37:33] không phải
[00:37:35] so sánh địa chỉ
[00:37:38] đúng hay sai?
[00:37:59] nửa.
[00:38:01] Bình tĩnh bình tĩnh bình tĩnh.
[00:38:12] object thì địa chỉ bộ nhớ ok
[00:38:21] này nhưng mà với object
[00:38:25] là mình sẽ so sánh địa chỉ ok
[00:38:34] thuật thì so sánh Nhưng mà
[00:38:38] đây giá trị ok giữ giữ nguyên nhé.
[00:38:46] diễn giải ấy không ông. Bây giờ tôi đang
[00:38:49] học nửa anh đương nhiên là có từ tiếng
[00:38:52] Anh chương ngành thì vẫn giữ nguyên nhá.
[00:38:53] Bây giờ ông bảo tôi hoàn toàn tiếng Anh
[00:38:54] tôi lú đấy.
[00:39:01] bảo rồi ông đừng coi tôi là tôi đang tôi
[00:39:04] đang dạy mấy ông này. Cái việc là tôi
[00:39:06] đang giỏi hay gì đó. Tôi đang học đang
[00:39:09] học mà học từ đây rồi mới buổi hai à đâu
[00:39:13] nhờ buổi ba trên mặt lý thuyết. Đấy. Thế
[00:39:17] nên là mày mấy ông đừng
[00:39:21] đừng kiểu đặt rất nhiều kỳ vọng. Đấy,
[00:39:24] không sao mấy ông Tôi nghĩ là mấy ông ở
[00:39:26] đây nếu mấy ông nói thế chứng tỏ mấy ông
[00:39:29] giỏi hơn tôi rồi đấy. Mấy ông nên tự hào
[00:39:31] xịn.
[00:39:34] Đây có kiểu hôm qua là kiểu cộng này
[00:39:36] nữa. Cái kiểu cộng này chắc chắn là học
[00:39:38] à không thằng Java tôi chẳng nhớ thằng
[00:39:41] nào ra đời trước. Thằng JavaScript hay
[00:39:43] thằng Java trước nữa,
[00:39:46] chắc cũng tham khảo của nhau. Ừ không
[00:39:50] sao, quên là chuyện bình thường mà. Hôm
[00:39:52] hôm trước tôi bắt ông em tôi phải ngồi
[00:39:56] hiểu kiểu phải ngồi đọc lại và phải hiểu
[00:39:58] để mà giải thích lại cho tôi một cái
[00:40:00] này. Chính nó
[00:40:02] là thằng thường xuyên dùng. Chắc chắn là
[00:40:04] mấy ông là người dùng thường xuyên. Thậm
[00:40:07] chí bây giờ bảo tôi dạy PP lại có những
[00:40:10] cái mà tôi vẫn sẽ phải có tra lại tài
[00:40:12] liệu thôi. Bởi vì rõ ràng là mình dùng
[00:40:16] như một thói quen chứ mình không nói
[00:40:19] không hiểu bản chất thì nó không đúng
[00:40:21] nhưng mà chắc chắn là không nhớ kỹ lý
[00:40:23] thuyết thì đúng. mình chỉ dùng thôi. Đấy
[00:40:28] và đặc biệt là thực tế dự án thực tế có
[00:40:31] bao giờ gặp mấy cái cây kiểu bằng bằng
[00:40:33] các thứ ít tôi nghĩ là ít đến chính là
[00:40:36] tôi làm PP nó cũng không phải so sánh
[00:40:40] thường là bọn tôi so sánh tới ba dấu
[00:40:41] bằng thì chắc chắn nó là cùng kiểu giá
[00:40:43] trị với cùng kiểu cùng cùng giá trị và
[00:40:48] cùng kiểu dữ liệu. Đấy, hai dấu bằng đã
[00:40:51] rất ít rồi.
[00:40:57] niệm về run time này. Run time này. Xong
[00:41:00] rồi. Hôm qua bạn đấy cũng có nói về có
[00:41:03] bạn nói về comply time là thời và lúc
[00:41:08] kiểu lúc mà kiểu tạo ra file class ạ.
[00:41:12] À đâu cái run time này lúc chạy thực tế
[00:41:15] và comply là lúc mà biên dịch đấy
[00:41:20] nên lúc biên dịch nó sẽ khác nữa cơ. Cái
[00:41:22] này còn để xem nào. Ming với các thứ thử
[00:41:28] à đấy thời gian thực thi và thời gian
[00:41:30] chạy. Ok.
[00:41:38] trông đây. Tôi à tôi đang định bảo tôi
[00:41:41] xem quen xem kiểu bên
[00:41:46] bên kiểu gì nhỉ? Cái trang Mdown. Nhưng
[00:41:49] mà cái này vẽ theo kiểu MC down nhưứ
[00:41:51] không phải.
[00:42:01] chịu một tí. Đợi tí. Ồ, ok.
[00:42:05] Ừ
[00:42:14] hàm qua đấy
[00:42:16] nên nên dùng hàm qua các thứ thứ thứ ok
[00:42:21] nhưng mà thế này chưa đủ bởi vì là hôm
[00:42:24] nay
[00:42:25] hôm nay a dùng cái a dùng cái gợi ý của
[00:42:30] AI đợi tí tôi tắt cái
[00:42:33] cái này tắt. đi
[00:42:35] đỡ khó chịu dùng cái a của ai này nó gợi
[00:42:39] ý
[00:42:41] nó đã tăng một tí vào trong đây auto
[00:42:45] boxing và unboxing này và cả cái này các
[00:42:48] thứ thứ nữa nên tôi sẽ sửa lại ngày buổi
[00:42:51] một và buổi hai một tí. Đấy thì hôm nay
[00:42:55] tính vẫn là day 2 mà đúng không? Đấy
[00:42:59] chúng ta sẽ ngồi sửa lại buổi một buổi
[00:43:00] hai một tí.
[00:43:08] thông chơi hẳn con này không nhá. Thôi
[00:43:11] hẳn con này đi. Sửa lại đâ 1 và day 2
[00:43:17] cho tôi cho phù hợp hơn
[00:43:22] với tài liệu.
[00:43:31] Ờ
[00:43:32] hiện tại thì mình đang tốn
[00:43:36] 20 tầm 20 đô cho antirapity này. À
[00:43:40] không, đấy là tôi được 3 tháng 50.000, 3
[00:43:44] tháng đầu 50.000 thì phải. Còn những
[00:43:46] tháng sau sẽ tính giá như thế. À nhưng
[00:43:49] cái antigravity này ngoài việc mấy ông
[00:43:52] thấy đang dùng kiểu mấy cái model mọi
[00:43:54] thứ cũng chưa thấy dấu hiệu limit đúng
[00:43:57] không? Sáng nay thực ra tôi vừa bị con
[00:43:58] limit con Cloude phát nữa. Nhưng mà sao
[00:44:01] lúc ấy chuyển qua dùng trên mini Pro mọi
[00:44:03] thứ vẫn chẳng vấn đề gì cả mà dùng hình
[00:44:05] như là chỉ một tí con này nó lại hết
[00:44:08] limit bởi vì nó reset sau 4 tiếng đấy
[00:44:12] nên là gần như là và cái điểm hay đó là
[00:44:15] như hôm qua tôi có nói đó là ông mua 20
[00:44:20] đô đúng không nhưng mà ông dùng cho được
[00:44:22] cả family rõ ràng nó không hề đề cập cái
[00:44:24] vụ đấy ở trong cái phần gói của nó nhưng
[00:44:28] mà ông sẽ được 2T 2TV
[00:44:36] gói này ví dụ là Gemini Pro hay gì gì đó
[00:44:40] nhưng mà tôi ít dùng nên là tôi không
[00:44:42] quan tâm lắm nhưng đại khái thì tôi mua
[00:44:44] là để về code mà đúng không? Thì rõ ràng
[00:44:47] là tôi từng mua cho con
[00:44:50] Cuso với cả Green Search rồi thì tôi
[00:44:52] thấy là nó tốn hơn 20 đô.
[00:45:04] miễn phí thì nó sẽ nó sau một tuần thì
[00:45:07] nó mới reset. Nghĩa là nó sẽ chỉ có
[00:45:09] lượng nhất định là limit trong một tuần
[00:45:12] thôi. Nhưng mà với bản mất phí này thì
[00:45:15] sau 4 tiếng nó reset rồi nên là ít ít
[00:45:18] khi bị limit cái này lắm.
[00:45:29] ý
[00:45:31] tôi là sửa code và
[00:45:36] Bolei
[00:46:00] vừa làm đã.
[00:46:15] Cái này thì tôi không hồi trước là tôi
[00:46:18] đã từng kiểu chắc là ai cũng đã từng
[00:46:21] kiểu dạng là
[00:46:23] dùng một cái trích nào đó kiểu
[00:46:26] à có gì cần thay đổi sửa lại code hai
[00:46:33] file đó vì đó là example
[00:46:37] cho tài liệu này.
[00:46:57] trước mình sẽ không quan tâm nhiều bản
[00:46:59] quyền lắm hoặc là mình không có điều
[00:47:01] kiện để mà mua bản quyền đấy. Nhưng mà
[00:47:04] càng về sau này tôi kiểu mình làm đép mà
[00:47:06] nên mình cũng trân trọng nên là mình sẽ
[00:47:08] không kiểu lách luật mình không các thứ
[00:47:10] nữa mà tôi còn nghĩ là một phần là đây
[00:47:13] là tài khoản ví dụ hiện tại mấy ông đang
[00:47:15] thấy logo đây luôn này. Đây chính là tài
[00:47:17] khoản kiểu chính chủ của tôi luôn đấy.
[00:47:20] thì mình không nên kiểu
[00:47:23] dùng tài khoản chính chủ mình xong rồi
[00:47:26] giao dịch hay là làm cái gì đó nó kiểu
[00:47:29] lách luật các thứ thứ đúng không ạ? Tự
[00:47:32] nhiên nh đâu phía sau làm ảnh hưởng đến
[00:47:34] chính tài khoản của mình. Nhưng tốt nhất
[00:47:35] là kiểu nếu có thể thì cứ mua thôi. Đấy
[00:47:40] hiện tại tôi mua đấy chứ tôi mua kiểu
[00:47:43] mua thẳng từ Google luôn. Tôi không
[00:47:45] thông qua bên trung gian nào cả.
[00:47:52] đang dùng thứ nhất là Windows thì chắc
[00:47:54] là vẫn chưa mua bản quyền Windows à và
[00:47:59] cái gì nhỉ ờ du lingo à dual lingo thì
[00:48:03] đúng là mua
[00:48:05] mua cùng với family thì đúng là nó rẻ
[00:48:07] hơn thế thôi.
[00:48:14] có phải là lậu đâu. Vì rõ ràng là nó hỏi
[00:48:18] ông ông có muốn trả tiền không, ông chọn
[00:48:21] không chứ nó không phải là ông đang dùng
[00:48:24] lậu hay là ông đang crack nó. Không
[00:48:27] phải. Window thì đúng. Đúng là đa số là
[00:48:30] crack. Tôi tôi không nhớ là tôi crack
[00:48:33] hay là tôi active cái gì đó nữa. Anti
[00:48:36] Gravity mình vừa nói là sẽ tầm 20 đô.
[00:48:39] Thực ra đấy vẫn là tùy tài khoản bạn
[00:48:41] nhá.
[00:48:47] cái tài khoản Google của bạn ấy. Ví dụ
[00:48:49] là của sếp tôi là được miễn phí tháng
[00:48:51] đầu này. Những tháng sau mà mất tiền thì
[00:48:53] vẫn 20 đô thôi. Đấy
[00:48:57] viết lại. Đấy viết lại hai file rồi.
[00:48:59] Thôi mình sẽ ngồi ôn lại cái day 1 day
[00:49:03] 2. Nào
[00:49:05] lưu giá trị trong stack không thể là
[00:49:07] nun. Tốn ít bộ nhớ không có method
[00:49:12] stack. Hôm qua mình có đề cập với hit và
[00:49:15] stack đúng không? H stack cả hai đều bộ
[00:49:20] nhớ đúng không? Đấy. Ok.
[00:49:37] không? Nếu mà dịch thu thì sẽ không được
[00:49:39] nun.
[00:49:46] mua mấy cái gói này còn được Google One.
[00:49:48] Đấy nhưng mà mấy ông thực ra không dùng
[00:49:50] tốt Google One hoặc là thực ra tôi không
[00:49:53] biết mấy ông dùng có đi hay không. Nhưng
[00:49:55] đại khái tôi hồi trước tôi dùng khá là
[00:49:57] vắt dùng từ vắt thì cũng đúng. Nghĩa là
[00:50:00] Google One có một cái hồi trước có một
[00:50:02] cái ngoài lợi thế là kiểu nó tăng cái
[00:50:04] dung lượng của ra ý.
[00:50:08] Nó có một lợi thế nữa mà ít người dùng
[00:50:10] đó là được liên hệ với hỗ trợ bên
[00:50:13] Google. Đấy,
[00:50:15] bây giờ hình như là người ta hình như
[00:50:18] cũng bắt đầu đông người dùng và cũng có
[00:50:20] vài người spam hay sao ấy. Chắc là nó
[00:50:23] limit rồi. Và nó cũng gọi là có thể tôi
[00:50:25] cảm thấy giống như là dùng AI trả lời
[00:50:27] hơn, kiểu nó bị khô cứng nhắc ấy hoặc là
[00:50:31] cũng bị giới hạn quyền. Chứ hồi trước
[00:50:32] tôi từng nhắn cho bên đấy rồi nhớ bên
[00:50:35] đấy, bên đấy còn gọi hẳn dep để mà dep
[00:50:38] hỗ trợ tôi cơ. Và đấy kiểu vãi trưởng
[00:50:41] báo bấc xong rồi các thứ rồi. Google
[00:50:44] Support hỗ trợ. Đấy mấy ông được nói
[00:50:46] chuyện với Google Support nó vinh dự
[00:50:49] đúng không ạ? Đấy Google One có một cái
[00:50:52] điều kiện như thế ở trong cái chính sách
[00:50:54] của họ.
[00:50:56] Còn bây giờ có vẻ đồng lượng người dùng
[00:50:57] Google One kết hợp việc là có thể nó
[00:50:59] giới hạn theo IP cũng n giống như là
[00:51:02] kiểu mình lạm dụng Facebook hay là các
[00:51:05] nền tảng khác kiểu spam về cái contact
[00:51:08] của nó support nó quá nên thành ra nó
[00:51:11] cũng limit là riêng theo cái địa chỉ IP
[00:51:16] Việt Nam thì nó sẽ dùng boss để trả lời
[00:51:19] kiểu thế
[00:51:25] vì mình muốn tăng cái dung lượng Google
[00:51:26] Drive thôi lên 100 GB thôi nhưng mà dùng
[00:51:29] mua bất kỳ gói nào của Google One cũng
[00:51:31] đều có cái vụ là được support đấy.
[00:51:42] lưu trong stack. Cái này lưu trong hit
[00:51:44] đúng không? Có thể là nun dùng trong
[00:51:47] collection. À đây có bạn hôm qua nhắc
[00:51:49] đến kiểu khái niệm collection xong rồi
[00:51:52] nhắc đến cái gì nhở?
[00:51:58] từ gì ấ nên là chắc là để dần dần sau sẽ
[00:52:01] biết. Elite này, Hmap này. Uầy, cái này
[00:52:06] chắc chắn là mình sẽ phải dần dần biết.
[00:52:08] Có method hữu ích. Ừ ok. Method thì có
[00:52:12] biết dần rồi. Uầy có character á. Ừ thế
[00:52:16] mà hôm trước mình chỉ biết tưởng là cha
[00:52:18] viết hoa thôi chứ là nó là chaor. Ok
[00:52:22] nghĩa là kiểu viết đầy đủ. Viết hai chữ
[00:52:25] đâu. Ok được. Chắc là có flash các thứ
[00:52:29] nữa được phép nun này.
[00:52:32] Auto boxing là tự động chuyển. Uầy tự
[00:52:35] động chuyển từ cái này cái này. Cái này
[00:52:37] hôm trước chưa đề cập này. Đâu xem nào.
[00:52:41] Cái này bằng này thì cái thằng cũ này
[00:52:45] vẫn sẽ giữ nguyên ra thằng nguyên thủy.
[00:52:48] Còn thằng này sẽ tự động chuyển thành
[00:52:50] thằng mới. Ừm. Nghe hợp lý. Về cái này
[00:52:53] bản chất cái này giống như là kiểu ghi
[00:52:55] như này thôi mà đúng không? Ok được.
[00:53:00] Unbox
[00:53:01] à thế bây giờ bình thường auto rồi unbox
[00:53:04] nghĩa là đổi ngược lại. À
[00:53:06] à đổi ngược lại. Ok biến thành. Có
[00:53:10] trường hợp nào mà hiểu mình tự nhiên
[00:53:11] mình phải làm ngược lại như này không
[00:53:13] nhỉ?
[00:53:19] này chẳng biết dùng nó nó là kiểu dữ
[00:53:21] liệu khác biệt với PP thôi. Mình đang
[00:53:25] cần xem tại sao các thứ thôi.
[00:53:30] Đúng tự nhiên quay lại thì nó sẽ kiểu
[00:53:33] không được phép nun thì nó sẽ gây nguy
[00:53:35] hiểm. Đúng.
[00:53:44] bình thường dùng bằng để so sánh.
[00:53:55] tượng với nhau. Ừ cũng giống như là
[00:53:58] thằng string ở kia đúng không nhỉ? Kiểu
[00:54:01] bằng new new string đúng không?
[00:54:05] Không phải cùng cái địa chỉ
[00:54:08] nên thành ra bằng không được. Phải dùng
[00:54:10] hàm equal đúng không?
[00:54:25] được cách có thể bằng bằng có thể chu.
[00:54:33] được. Tôi không biết được mấy ông có
[00:54:35] biết vụ này không cơ kiểu c lưu ý cái
[00:54:37] này này. Lần đầu tôi nghe luôn ạ. Con gị
[00:54:41] vãi chưởng. [tiếng cười]
[00:54:43] Riêng trường hợp này thì bằng lại bằng
[00:54:45] chua. Ok.
[00:54:57] trách nhiệm vui cho các bạn. Ừ, tôi sẽ
[00:55:01] ngồi làm
[00:55:06] làm cao hút đấy. Tổng hợp những cái mà
[00:55:09] tôi đã cảm thấy kiểu bất ngờ vì Java.
[00:55:12] Tôi cho chính mấy ông chơi từ Java mấy
[00:55:14] ông chơi luôn. Ví dụ cái này này, tôi
[00:55:16] hỏi ông em tôi ông em chưa chắc trả lời
[00:55:18] được đâu. Đấy, đúng không? Cứ khẳng định
[00:55:21] luôn là thời đi học đa số trừ khi thầy
[00:55:25] nào cũng kiểu cũng kiểu vui tính giống
[00:55:27] tôi không biết được. Đấy
[00:55:30] sẽ không ai kiểu chỉ cho mấy ông bởi vì
[00:55:33] cái này giống cái mẹo kiểu chích chích
[00:55:35] hay các thứ nó nhỏ nhỏ nó chẳng phải một
[00:55:37] cái to để mà kiến thức Hàn Lâm để mà dạy
[00:55:39] ấy đúng không? Đấy hay đấy. Ông kia đừng
[00:55:44] ông kia quên đi nhá.
[00:55:47] được. Hôm nào tôi sẽ
[00:55:50] mở mấy cái kiểu trắc nghiệm cao hút anh
[00:55:53] em ngồi chơi với nhau nhở.
[00:56:01] hồi trước nếu mấy ông từng tham gia cái
[00:56:03] khóa mấy khóa học cũ của tôi, tôi từng
[00:56:06] làm mấy cái trang nghiệm trong kiểu cuối
[00:56:08] mỗi bài vui vui rồi đúng không? Nhưng mà
[00:56:10] mấy cái đấy nó sẽ kiến thức đấy có thể
[00:56:13] mà mấy ông học rồi mấy ông kiểu gì cũng
[00:56:15] biết nên thành ra nó kiểu không vui nữa.
[00:56:17] Thì rõ ràng cái này phải là rất ít người
[00:56:20] biết thì nó mới vui kiểu mình lúc đấy
[00:56:23] mình sẽ kiểu cảm thấy bị thách thức ấy
[00:56:26] nó mới hay. Đấy do mấy ông thích dùng
[00:56:29] cái chơi mấy cái
[00:56:32] một là hackthon à hai là cái cta à tôi
[00:56:35] nhớ CTA mà đúng không?
[00:56:38] cái kiểu dạng giống kiểu hack ấ đ nhá
[00:56:41] CTA
[00:56:48] À
[00:56:51] tôi nhớ
[00:56:54] có khái niệm kiểu thử thách
[00:57:00] trong giới công nghệ
[00:57:04] kiểu hack CTA đúng không?
[00:57:27] Đúng nó có thể hackathon nhưng ý tôi
[00:57:29] không phải là mỗi hackathon. Đây phải
[00:57:31] như này này. CTF này kiểu kiểu này
[00:57:34] CTF nó thiên về thử thách tức chị ạ. nó
[00:57:37] một cái gì khó. Đương nhiên là đa số là
[00:57:40] nó sẽ liên quan đến bảo mật các thứ như
[00:57:43] này. Nhưng mà mình có thể rộng hơn mà.
[00:57:46] Đấy nó giống kiểu challeng các thứ thôi.
[00:57:50] Đấy nghĩa là một cái thử thách nào đó
[00:57:54] để kiểu giợ để cho mấy ông cùng làm cùng
[00:57:58] đấy. Thử thách nhau hay mà. Hồi trước là
[00:58:02] J2 team cũng có cái trang CTF mấy ông
[00:58:05] cũng làm hết rồi gì á.
[00:58:07] Nhưng mà cái đấy thiên về kiến thức về
[00:58:09] web và một tí về bảo mật hay các thứ
[00:58:11] thứ.
[00:58:13] Còn đây kiến thức mà chính mà chúng ta
[00:58:15] đang học, chúng ta đang làm đúng không?
[00:58:19] Cùng nhớ đặc biệt trong híp. Ừ. Tái sử
[00:58:22] dụng string giống nhau tiết kiệm bụi
[00:58:25] nhớ. Uầy. Đấy, nó sửa lại như này nhìn
[00:58:27] trông nó dễ hiểu hơn ấy.
[00:58:34] này trông có vẻ chi tiết hơn.
[00:58:43] kiểu này không sao không ạ
[00:58:47] luôn tạo
[00:58:49] bộ object mới trong h ngoài pool object
[00:58:52] mới ngoài pool này thêm object này phone
[00:58:55] là khát địa chỉ phone là p với hip khác
[00:58:58] nhau đúng đó sẽ khát địa chỉ luôn đúng
[00:59:11] Ở đây là dùng từ nội dung thay vì giá
[00:59:12] trị nhỉ? Nhưng mà value dịch ra là giá
[00:59:16] trị mà nhỉ.
[00:59:24] bạn kia nói m table là có thể thay đổi
[00:59:28] đúng không?
[00:59:30] Còn imu là không thể đổi bất biến đúng
[00:59:32] không?
[00:59:40] báo cụ thể và nó cố định giống kiểu
[00:59:42] constant kiểu này. Về sau nó sẽ bớt bị
[00:59:45] lỗi đúng không? Trad safety rồi các thứ
[00:59:49] chứ còn PP là kiểu đang kiểu biến này
[00:59:54] đang làm kiểu dữ liệu này rồi cho gán
[00:59:56] biến này làm cái giá trị và kiểu dữ liệu
[00:59:58] khác luôn cũng được. Đấy
[01:00:01] cái này là nun boer exception đúng
[01:00:06] không? À đây đây đây vừa đề cập xong
[01:00:09] đấy.
[01:00:21] rồi này.
[01:00:29] Ok bây giờ tôi sẽ sang thử buổi ba nhá.
[01:00:33] Anh em sẵn sàng chưa ạ?
[01:00:35] Nồi chuỗi tạo mới chậm và được nhanh.
[01:00:45] Ờ
[01:00:47] kiếm
[01:00:53] này cũng là thinh kinh nhá.
[01:01:00] cập nhật à kiểm tra.
[01:01:18] gì bù lớn đâu. Thậm chí là có dùng tiếng
[01:01:21] ngại Anh đâu. Dùng tiếng Việt mà đúng
[01:01:22] không? Thấy là kiểu nói chuyện như giao
[01:01:26] tiếp bình thường thôi đúng không?
[01:01:38] để mà học PP là à học OP là khá là rõ là
[01:01:43] nó còn thêm nhiều cái nữa cơ. Lúc mà lúc
[01:01:46] mà kiểu đọc về cái tư duy cốt lõi này
[01:01:48] công nhận nhiều cái hay cả lưu ý ở dưới
[01:01:51] này này. Miên tắc vàng các thứ như này
[01:01:55] hay phết.
[01:02:03] nào.
[01:02:05] Có demo rồi này.
[01:02:13] nào dùng khi nào dùng cái nào các thứ.
[01:02:19] Cái này cứ bị nhảy xuống dưới khó chịu
[01:02:20] cực.
[01:02:23] Chưa giải thích rõ. Chưa giải thích tr
[01:02:25] save là gì. Chưa phần tầm tóm tắt rõ
[01:02:27] ràng.
[01:02:29] Ok.
[01:02:30] Ui, có thêm ví dụ trong SQL building
[01:02:34] nữa. Uầy, xịn thế. Xem nào. String
[01:02:38] Builder và String Buffer.
[01:02:41] Hiểu về bất biến khi nào sử dụng một
[01:02:43] trong hai đúng không? So sánh hiệu năng.
[01:02:45] Ok. bất biến
[01:02:48] bình thường cái này cộng thêm sau nối
[01:02:52] chũa string cũ bị bỏ đi tạo giác cho
[01:02:56] cái này vừa nãy là mình đọc rồi nó là
[01:03:00] grapit collector tức là kiểu kiểu thu
[01:03:03] gom giác kiểu thế đúng không?
[01:03:12] Xong rồi string bằng string cũ cộng với
[01:03:15] world. Sau nối như thế này.
[01:03:27] string bình thường mình sẽ khai báo
[01:03:29] string
[01:03:31] builder. Ok. Hợp lý đấy. Hợp lý đấy.
[01:03:35] Thay đổi trực tiếp được không? tạo mới
[01:03:37] nhanh hơn, không trưng
[01:03:41] mà nó sẽ không an toàn đúng không? Bởi
[01:03:42] vì như vừa nãy mình nói là để cho nó nên
[01:03:46] là bất biến thì mình sẽ luôn biết được à
[01:03:49] nó lúc đầu là gì thì về sau mình sẽ biết
[01:03:52] là nó sẽ mãi là như thế đúng không? Còn
[01:03:54] bây giờ thì cái này là phải xem theo.
[01:04:00] Đúng rồi. Nó thay đổi được thì phải dựa
[01:04:02] theo cái run time s dựa theo cái việc nó
[01:04:05] chạy nó sẽ như nào đúng không? Thì lúc
[01:04:07] đấy mình lại đoán mò giống PP thôi. Cái
[01:04:09] đoạn này giống PP tôi tôi nghĩ tôi hiểu
[01:04:12] đoạn này. Thậm chí còn đa luồng nữa nhỉ.
[01:04:15] Ừ đa luồng nữa. Tức là ám chỉ là kiểu
[01:04:17] bây giờ có thể thằng này ghi vào trong
[01:04:19] chính cái bộ nhớ đấy đúng không? Có thể
[01:04:21] thay đổi
[01:04:27] bình tĩnh bình tĩnh bình tĩnh.
[01:04:31] Chưa chưa xuống bình tĩnh đợi đợi đợi
[01:04:35] đã. Đâu gốc này. Ok này. Thêm dữ điệu
[01:04:40] này. Appen trông hay nhỉ. Appen cũng
[01:04:42] kiểu giống hệt làm việc với mảng luôn ý.
[01:04:46] Thật. Up. Hàm open này tôi còn nhớ là
[01:04:49] giống kiểu trong jigory à kiểu làm việc
[01:04:52] với HTML JavaScript
[01:05:06] insert à insert là như nào 5 Java là như
[01:05:11] nào?
[01:05:13] Nghĩa là
[01:05:15] sau P sau insert. Uầy cái này phải chạy
[01:05:18] thử mới hiểu ấy. Cái delete này thì tôi
[01:05:21] nghĩ là tôi nghĩ là cái năm này là
[01:05:25] à đấy nó offset nghĩa là
[01:05:28] ơ pen này là như nào? Là cứ thêm ở cuối
[01:05:31] đúng không? Con này là tại vị trí thứ
[01:05:34] bao nhiêu? Nghĩa là sẽ có trường hợp ghi
[01:05:35] đè à
[01:05:38] đúng không? Tôi nghĩ là nó sẽ ghi đè.
[01:05:49] cái chỗ nào đấy thì xong rồi sẽ đẩy
[01:05:51] những thằng kia về đằng sau đúng không?
[01:05:53] Nghĩ thế reverse đâu xem
[01:05:57] đây nó sẽ chỉ insert thôi.
[01:06:01] À ghi đẻ set à ừ tôi nghĩa là gọi là
[01:06:04] chèn thêm vào đúng không? Insert là đang
[01:06:06] là chèn đấy. Chèn thêm vào vị trí đ bao
[01:06:08] nhiêu? Delete là xóa từ từ bao nhiêu đến
[01:06:12] bao nhiêu. Ok. Reverse là kiểu đảo ngược
[01:06:16] lại đúng không? Đảo ngược lại kiểu sắp
[01:06:19] xếp các thứ.
[01:06:22] Ồ string buffer string builder cộng red
[01:06:26] save. Cái th save này tôi có nhớ về khái
[01:06:29] niệm trúc mà
[01:06:33] tải cái gì nó cũng bảo tr nhỉ.
[01:06:37] Non trap save với tr hình như PP cũng có
[01:06:40] thì phải.
[01:06:41] Nếu lúc đấy tôi cũng chưa hiểu cái th
[01:06:49] đợi tôi một tí. Thre xếp có phải là nó
[01:06:51] liên quan đến đa luồng
[01:06:54] an toàn khi đa luồng không?
[01:06:56] Để tớ hỏi lại nhá. Xếp trong lập trình
[01:06:58] nghĩa là gì?
[01:07:17] niệm đa luồng nên thạ không quan tâm này
[01:07:19] lắm đứ nh thình thoảng có đa luồng theo
[01:07:21] kiểu là kill chạy song song hay gì gì đó
[01:07:28] red truy cập đồng thời mà vẫn cho kết
[01:07:31] quả đúng nhất quán không gây lỗi dữ
[01:07:33] liệu, không phụ thuộc vào thứ tự. Ầy,
[01:07:36] không phụ thuộc thứ tự là cũng ghê đấy.
[01:07:39] Vấn đề xuất hiện vì đọc ghi cung chung
[01:07:44] cái stat state
[01:07:46] khi điều này xảy ra gặp các thảm họa
[01:07:49] kinh điển như race condition. Great
[01:07:52] Condition này. Hồi trước tôi từng làm
[01:07:53] cái vụ ở công ty, tôi không biết tôi
[01:07:55] từng chia sẻ mấy ông chưa. Xong rồi bọn
[01:07:59] tôi phải chơi. Ừ đúng rồi. Nó cũng phải
[01:08:02] tí. Nó liên quan database là nhiều mà
[01:08:04] trong PP liên quan ray condition
[01:08:06] database nhiều. Thì hồi đấy bọn tôi phải
[01:08:10] chơi cái trò là thay vì lock lại cả cái
[01:08:13] table thì đương nhiên là lock chết ngay.
[01:08:15] Thì không nên mình phải lock theo theo
[01:08:19] bản ghi. Thế nên là kèm luôn phải kèm
[01:08:21] theo một cái điều kiện nào đó. Phải we
[01:08:23] theo một cái điều kiện nào đó. Đấy
[01:08:26] quả đấy hay phết.
[01:08:29] Gọi là log nhưng mà lock động đấy. Lock
[01:08:32] dynamic thay vì lock cứng hot lock. Hot
[01:08:35] lock thì thằng khác không truy cập vào
[01:08:38] được thì cũng không ổn. Đương nhiên là
[01:08:41] cũng có hotlock theo kiểu read nhưng mà
[01:08:44] mình vẫn muốn là kiểu bây giờ giả sử bây
[01:08:47] giờ ông cứ hình dung là ông chuyển tiền
[01:08:49] ngân hàng có rất nhiều người cùng chuyển
[01:08:50] vào số tài khoản ông cùng lúc rõ ràng là
[01:08:53] rõ ràng là điều đấy điều hoàn toàn có
[01:08:55] thể xảy ra nhưng nghĩa là chỉ nhiều
[01:08:58] người cùng chuyển tiền ông cùng một lúc
[01:08:59] là điều bình thường đúng không được phép
[01:09:02] đúng không nhưng mà rõ ràng tại cái thời
[01:09:04] điểm đấy là database đang đang cập nhật
[01:09:07] cái số tiền của ông rồi thì rõ ràng là
[01:09:09] nó phải chính xác Chắc nó phải là kiểu
[01:09:13] tránh việc là nhiều người cùng kiểu ghi
[01:09:16] đè vào quá nó sẽ bị loạn đúng không? Ví
[01:09:18] dụ ông đang 10.000 rõ ràng nó bảo cộng
[01:09:21] thêm 10.000 nữa đấy. Nhưng mà có rất
[01:09:24] nhiều thằng cộng cộng rồi thậm chí còn
[01:09:25] thằng trừ trừ nữa. Cùng tại 1 giây đấy
[01:09:29] chẳng hạn thì rõ ràng là mình sẽ phải
[01:09:31] thêm những cái điều kiện nào đó hoặc là
[01:09:33] mình phải đôi khi là phải còn phụ thuộc
[01:09:35] vào cái thứ tự ưu tiên hay à thứ tự chạy
[01:09:38] nghĩa cộng trước rồi trừ rồi cộng cộng
[01:09:40] trừ hay vân vân vân. Đấy các thứ nói
[01:09:42] chung là đấy do mà tôi bắt đầu hiểu tại
[01:09:46] sao các hệ thống ngân hàng đều dùng Java
[01:09:48] rồi để nó liên quan đến tress save các
[01:09:51] thứ này để tránh mấy cái
[01:09:54] kiểu đa luồng nhá nó vẫn phải đảm bảo về
[01:09:57] tính a đấy gọi là tính gì nhở constit à
[01:10:02] consistant nó tính a
[01:10:10] tính chặt chẽ chẽ à không phải tính chất
[01:10:12] chẽ nó tính gì nhở? Consistent
[01:10:15] tính
[01:10:17] consist
[01:10:23] vẫn dịch lại cho tôi.
[01:10:25] Đúng là nhất quán dữ liệu đấy đây đúng
[01:10:28] tính nhất quán
[01:10:31] ơ mình viết đúng kìa. Uầy
[01:10:34] à không không đúng lắm đúng không? Không
[01:10:36] không không đúng đắn. [tiếng cười] Không
[01:10:38] sao đấy nó hiểu mà. Đấy,
[01:10:42] tính nhất quán. Đúng rồi.
[01:10:45] Thế ra tôi hỏi mấy ông để mấy ông trả
[01:10:47] lời thôi.
[01:10:55] Kết quả các thứ thứ
[01:10:59] một đoạn code được
[01:11:01] gọi là tr khi đảm bảo một trong các
[01:11:04] chiến liên sau hoặc kết hợp
[01:11:07] ồ nghĩa chỉn một thôi cũng được đúng
[01:11:09] không? Không có share state.
[01:11:18] trên kênh tip. Đúng rồi. Hình như là anh
[01:11:20] có theo dõi kênh đấy rõ ràng kêu là tip
[01:11:22] ra script nhưng mà thật ra đề cập rất
[01:11:24] nhiều cái nó cũng chả lế ngon ra script
[01:11:26] gì cả.
[01:11:29] Mà nó có phải tip đâu. Nó rõ ràng nó là
[01:11:31] một kiểu một kênh ebook hơn một kênh
[01:11:33] kiểu chia sẻ kiến thức hơn. Týp là theo
[01:11:35] kiểu mẹo vặt mà đúng không?
[01:11:38] Mỗi tr làm việc với dữ liệu riêng là
[01:11:41] chiến lược tôi đánh giá cao nhất vì đơn
[01:11:43] giản bền vững.
[01:11:45] Ừ nhưng mà rất khó vì rõ ràng là dữ liệu
[01:11:47] thường hay dữ liệu chung cho tiết kiệm
[01:11:49] về chi phí rồi rất nhiều cái. Bởi vì nếu
[01:11:52] mà không thì dữ liệu kiểu độc lập thì
[01:11:54] thực ra là nó cũng không ổn.
[01:11:57] Đ nói cơ sở dữ liệu nhá. Đó cơ sở dữ
[01:11:59] liệu thì bây giờ mình tách ra thì rõ
[01:12:01] ràng là một bên này cập nhật là tăng lên
[01:12:03] 10.000, bên này cập nhật tăng lên 20.000
[01:12:05] Nhìn xong rồi sẽ vào với nhau như nào
[01:12:08] đúng không? Đồng bộ với nhau như nào?
[01:12:12] Dữ liệu chỉ đọc không bao giờ thay đổi
[01:12:14] sau khi tạo cũng một kiểu. Đấy thì hồi
[01:12:18] trước có cái chơi kiểu đấy thường ấy lưu
[01:12:20] gọi là bảng lịch sử giao dịch đúng
[01:12:22] không? Đấy các thứ đấy mình có thể có
[01:12:25] thế nghĩa là mình sẽ dựa theo nghĩa là
[01:12:27] nếu mà có một cái lỗi gì đó phát sinh
[01:12:29] trong quá trình mà mình à tại kiểu bất
[01:12:33] đồng bộ đây đúng không? các thứ mình vẫn
[01:12:35] có một thứ để vai date lại đi kiểm tra
[01:12:38] lại là nó đang đúng hay đang sai và mình
[01:12:43] có thể còn kiểu gọi như là mình có thể
[01:12:46] sửa được nó ấ ông ông hiểu không nghĩa
[01:12:49] luôn có một cái sổ nhậ ký một cái quyền
[01:12:52] để ghi lại toàn bộ những cái đấy thì
[01:12:54] mình còn biết được mình còn sửa
[01:13:03] vào gọi là insert thôi, không được
[01:13:06] update cũng không được delete.
[01:13:15] xong rồi transition nữa. Hồi đấy tôi nói
[01:13:17] là à tôi có nghe cái có một anh bảo là
[01:13:20] lạm dụng cái đấy là một cái bẫy. Bởi vì
[01:13:23] bởi vì rõ ràng là bây giờ ông cứ hình
[01:13:26] dung là
[01:13:29] làm một cái thứ đấy tận năm bước đi xong
[01:13:31] đến bước thứ ba nó lỗi nó robách nó kiểu
[01:13:36] khôi phục lại. Ok đương nhiên là về dữ
[01:13:38] liệu thì ông sẽ không bị sai nữa nhưng
[01:13:40] mà rõ ràng là ông sẽ phải ngồi mò xem nó
[01:13:45] đến bước nào nó lỗi. Đấy, bình thường
[01:13:48] mọi khi là mình lưu ở DB thì mình còn
[01:13:50] biết được à ví dụ à đến bảng thứ ba thì
[01:13:53] nó vẫn còn lưu, còn bảng thứ tư nó không
[01:13:54] lưu nữa thì mình có biết. Giờ nhiều
[01:13:57] người thì bảo là thôi bắn lock lên thì
[01:14:00] lock thì nó cũng giống như một cái DB
[01:14:01] thôi. Nghĩa là chỉ là bản chất là mình
[01:14:03] vẫn phải đánh dấu ở một cái chỗ nào đó.
[01:14:05] Ông hiểu không? Như rõ trung quy thì nó
[01:14:07] vẫn là một cái kiểu một cách khác thôi.
[01:14:10] Chẳng qua mình ghi vào DB ở chỗ khác
[01:14:12] kiểu thế. Đôi khi là log còn có vấn đề
[01:14:14] nhá. Hồi trước kênh blog ở trên công ty
[01:14:16] tôi vấn đề xong rồi hồi đấy thử muốn
[01:14:18] ngồi trang ngược lại king lock để để
[01:14:21] biết được kiểu gọi là dữ liệu các thứ
[01:14:23] thứ như nào klock không đấy có vấn đề
[01:14:26] nên thành ra cũng không trai được nên
[01:14:27] thành ra là kiểu
[01:14:29] lúc đấyên lại quay lại câu chuyện vừa
[01:14:31] nãy tôi nói cái bài toán này này là khi
[01:14:34] mà ông làm mà ông không có bảng nào đó
[01:14:37] để deate để đối chiếu ấy king lock cũng
[01:14:40] mà nói chung là kênh lock không phải là
[01:14:42] một kênh ch một kênh đạ đáng tin cậy để
[01:14:45] mà ông phải tin vào nó để dùng nó để mà
[01:14:48] validate các thứ. Lock chỉ là lock cảm
[01:14:51] chỉ là tại thời điểm này thì mình còn
[01:14:55] theo dõi được thôi chứ không không nên
[01:14:58] dùng cái log là một kênh để mà xác thực
[01:15:00] dữ liệu, xác thực thông tin.
[01:15:03] Đấy
[01:15:05] mấy ông chắc là tôi tôi nói thế thôi
[01:15:08] nhưng mà tôi nghĩ mấy ông có thể đã đi
[01:15:10] làm hết rồi và cũng biết được tôi đang
[01:15:13] mùa ru qua mắt thợ rồi nhưng mà tôi vẫn
[01:15:16] nhắc lại bởi vì đôi khi là cái cách mà
[01:15:19] tôi chia sẻ cũng là để cho mấy ông a
[01:15:23] à nếu mà thấy tôi nói sai thì còn phản
[01:15:26] bác lại kiểu mày chém gió sai rồi đấy
[01:15:29] thì tôi lại biết được là mình c nói sai
[01:15:32] cũng hay mà đúng không?
[01:15:41] đang có kênh kênh này tên là học nhá,
[01:15:43] không phải dạy nhá. Mình cùng nhau học
[01:15:47] tốt mày.
[01:15:49] Dùng các nguyên tử cho ngôn ngữ hoặc
[01:15:52] time cung cấp cũng được.
[01:15:55] Dữ liệu chỉ sống trong một th nhất định.
[01:15:58] Ừ, nghĩa giống kiểu biến cục bộ đúng
[01:16:00] không?
[01:16:02] À trong này còn không gọi là biến nữa
[01:16:04] bởi vì rõ ràng là trong PP nó sẽ khái
[01:16:06] niệm là biến bởi vì rõ ràng nó là nó là
[01:16:09] biến tức là nó có thể thay đổi. Còn đây
[01:16:11] là sẽ mang thi hướng kiểu hằng số hơn.
[01:16:14] Đấy rõ rằng constant kiểu mặc định mặc
[01:16:18] định constant luôn.
[01:16:21] X không đồng nghĩa với nhanh lock càng
[01:16:24] nhiều hệ thống càng dễ nghẽn. Đúng một
[01:16:27] hệ thống tre nhưng thiết kế kém vẫn bị
[01:16:31] chậm và không scale được. Đúng kiểu nó
[01:16:33] bị kiểu đồn đẩy nó đợi cái này chạy cái
[01:16:35] đợi kia chạy thì thành ra lại không phải
[01:16:37] đa luồng nữa. Đấy
[01:16:41] nó thiết kế có chủ đích một class hôm
[01:16:43] nay tret ngày hôm sau thể biến thành để
[01:16:47] là có thể phá nếu chưa thực sự cần thì
[01:16:58] Concurrency nó chưa đề cập từ
[01:17:00] concurrency đúng không?
[01:17:02] Nãy là tôi chưa thể thấy nó đề cập đúng
[01:17:04] không?
[01:17:17] đừng vội đa luồng. Ừ nghĩa không cần
[01:17:19] chạy đồng thời cũng một lúc đúng không?
[01:17:21] Ôi hay phết đấy. Nghĩa thỉnh thoảng nó
[01:17:24] may mà thỉnh thoảng nó có một vài từ
[01:17:26] chuyên ngành này nhá. Toàn bộ tiếng Anh
[01:17:28] thì chắc tôi tôi vẫn biết tiếng Anh nhá.
[01:17:31] Nhưng mà chắc chắn là mày không biết
[01:17:32] được. Đây mấy từ chuyên ngành mà đúng
[01:17:34] không? Chứ chứ chứ
[01:17:38] nó không
[01:17:40] hỏi như nào nhỉ? Bình thường tôi xem
[01:17:43] phim mà nghe nhạc có nhiều nhưng mà mấy
[01:17:44] cái từ nay ch nó không vừa gặp trừ khi
[01:17:47] ông xem thể loại gì thôi.
[01:17:50] Khi đã đa luồng hãy ưu tiên thiết kế
[01:17:53] tránh share state
[01:17:56] hơn là vá lỗi bằng lock.
[01:17:59] Ừm ok. Ui, mấy kiến thức này nó ứng dụng
[01:18:02] cho tư duy lập trình ấy chứ không phải
[01:18:05] mỗi Java hay là PP nói chung đúng không?
[01:18:09] Hay mà
[01:18:11] cứ cái này là gì? Cứ đồng cứ đây gọi là
[01:18:15] cứ đồng bộ hết đúng không? Đây xử lý
[01:18:18] đồng bộ đồng bộ hết cho lành à?
[01:18:21] Đấy.
[01:18:29] thích nói chuyện với thằng CHVT hơn
[01:18:30] thằng Jini rất nhiều này. Nó nhớ nó nhớ
[01:18:34] mình đã nói gì cho dù rõ ràng là đây là
[01:18:35] một cái đoạn chat khác. Đấy.
[01:18:44] thì tôi biết rồi. Tôi biết parallel song
[01:18:46] song rồi. Đấy.
[01:18:54] kiểu cứ cho là cá nhân hóa customiz các
[01:18:57] thứ thứ để mà để mà trả lời cho mình phù
[01:19:00] hợp đúng không? Thế mà có ông vẫn bảo
[01:19:02] tôi là kiểu nói chuyện với chatt bị đần
[01:19:07] xong rồi thích Gemini hơn chịu.
[01:19:15] riêng về code thì có thể thằng khác ăn
[01:19:18] đứt chat JVT nhưng mà tôi cảm thấy chatt
[01:19:20] tôi vẫn trả lời mọi thứ rất dễ hiểu và
[01:19:24] cả nhân hóa rất tốt.
[01:19:27] Cho dù gần đây nó à có một thời gian nó
[01:19:29] nịnh thì tôi khá khó chịu và gần đây nó
[01:19:32] bắt đầu
[01:19:34] xưng hô cũng hơi loạn lên tôi cũng không
[01:19:36] thích lắm nhưng thôi không sao.
[01:19:44] không nói rồi nhưng mà đang nói là về
[01:19:46] kiểu đây đấy thì mấy ông mấy ông phải
[01:19:49] hiểu nhá tôi dùng cloud cloue hay thậm
[01:19:52] chí là dùng để code đúng không? Đấy
[01:19:55] nhưng mà mình đang cần một con trợ lý ào
[01:19:58] để mà mình ngồi hỏi đáp như này này để
[01:20:00] thay tra Google thôi đúng không? Thì rõ
[01:20:02] ràng thì thì con này nó hơn cái con
[01:20:04] Gemini kiểu đần vãi trường kia. Tôi từng
[01:20:08] dùng con Gemini từ thời dùng ba nhá. À
[01:20:12] ba này Gemini từ đầu này xong rồi còn
[01:20:15] dùng cả copilot. C VOT của Microsoft ấ
[01:20:19] quá tệ đấy. A thư các bạn rất lâu rồi
[01:20:22] không dùng cot không biết nó thông minh
[01:20:24] hơn chưa đấy.
[01:20:37] hiểu sai vì nó thường
[01:20:40] dữ liệu này, hệ thống phân tán này, cả
[01:20:41] thiết kế chương trình.
[01:20:48] Tôi không thích lắm bởi vì tôi thường
[01:20:49] anh bảo với nó là phản biện nhiều lên
[01:20:52] đừng có nịnh nữa. Rồi bây giờ nó dễ luôn
[01:20:54] nói câu là tôi sẽ nói thẳng có chính
[01:20:57] kiến chứ không kiểu nịnh nữa. Cứ nhắc đi
[01:21:00] lại buồn cười.
[01:21:13] việc hệ thống luôn luôn tuân thủ các quy
[01:21:15] tắc đã đặt ra
[01:21:17] bất kể có bao nhiêu thao tác hay truy
[01:21:20] cập. Ừ. Hồi đấy tôi đặt tôi ép nó là
[01:21:23] kiểu kiểu gọi như là 30% đồng thuận, 70%
[01:21:28] là phản đối ấ đấy để cho nó ném đá mình
[01:21:33] để cho mình nhìn thấy điểm mù của bản
[01:21:35] thân ý.
[01:21:43] ra bất kể có thao tác hay truy cập đồng
[01:21:45] thời. Ừm, nghĩa là chỉ có bao nhiêu thứ
[01:21:48] x vào dù thế nào nữa thì mình không được
[01:21:51] mâu thuẫn. Mình vẫn kiểu up vẫn phải
[01:21:54] update đúng dữ liệu này. Đấy dù nó chạy
[01:21:57] trước chạy sau hay chạy cùng lúc với
[01:21:58] mình. Đấy kiểu thế.
[01:22:01] Đây cái khái niệm axit này đúng không?
[01:22:03] Mọi tron khi kết thúc đều đưa dữ liệu
[01:22:06] của một trạng thái hợp lệ
[01:22:09] từ một trạng thái hợp lệ sang một trái
[01:22:11] hợp khác. Hồi trước là công ty tôi bị
[01:22:14] đúng cái tình trạng này. Nghĩa là trong
[01:22:16] một khoảng một khoảng khác một khoảng
[01:22:19] khắc thôi nhá. Nhất định là dữ liệu
[01:22:22] trong trường hợp đấy nó đang không hợp
[01:22:24] lệ, đang không đúng lắm. Ông ông cứ hình
[01:22:27] dung có một kiểu dạng như là kiểu bên
[01:22:29] tôi muốn phản hồi về nhanh cho khách
[01:22:31] hàng ấy nên là thanh toán đơn xong đơn
[01:22:32] vẫn thực ra vẫn chưa tính là đã thanh
[01:22:34] toán. Đấy kiểu một khoảnh khắc thế thôi.
[01:22:38] Ông ông ông hiểu ý tôi không? Đấy
[01:22:42] đấy thì rõ ràng là nó cũng có thể vi
[01:22:45] phạm quy tắc về cái tính nhất quán.
[01:22:48] Nghĩa là nghĩa là kiểu dữ liệu thì hiển
[01:22:52] thị ra một kiểu vẫn báo cho khách hàng
[01:22:55] là đã thanh toán thành công nhưng mà
[01:22:57] thực ra là mình vẫn đang đợi web hook
[01:22:59] đang đợi tiền bắn về các thứ các thứ để
[01:23:02] xác nhận hối trước thực ra là không phải
[01:23:04] mỗi bên tôi đâu. Cái cái này tôi biết
[01:23:07] được có nhiều bên bị thế này xong rồi
[01:23:09] còn có nhiều nhiều ông tricker à hồi
[01:23:12] chưa hacker hoặ thậm chí là có cái vụ
[01:23:15] nổi tiếng cái phim a Catch Me If You can
[01:23:18] mà thực ra cũng lợi dụng cái kiểu kiểu
[01:23:20] na ná kiểu như này này tức là để xác
[01:23:24] thực được một cái giao dịch thì rõ ràng
[01:23:26] phải qua nhiều bước ấy đôi khi là nó cứ
[01:23:27] báo trước cho mình là thành công xong
[01:23:29] rồi mình lợi dụng cái lúc đấy là mình
[01:23:31] làm nhiều thứ xong lúc mà nó mà kiểu va
[01:23:34] đết được cái cái giao dịch cái thất bại
[01:23:36] rồi thì mình đã làm được nhiều cái rồi
[01:23:37] thì kiểu thế đấy. Bởi vì rõ ràng là tại
[01:23:42] sao đầu tiên là có ông thắc mắc à tại
[01:23:46] sao lại làm thế? Mình phải vai đết chắc
[01:23:48] chắn đã thì mình báo khách hàng nhưng mà
[01:23:50] làm thế đôi khi nó rất là lâu. Mình
[01:23:52] không làm thế là nó sẽ bị tụt khái niệm
[01:23:55] trong bọn tôi làm về mạng bán hàng dịch
[01:24:00] vụ này sẽ CR đúng không? Conversion rate
[01:24:03] tức là cái hiệu suất quy đổi nó sẽ bị
[01:24:05] giảm. Nghĩa là khách nó sẽ đi. Khách mà
[01:24:09] kiểu cảm thấy là kiểu
[01:24:13] đây đây kiểu một đơn hàng các thứ lại đề
[01:24:15] cập luôn này. Nghĩa nói chung là liên
[01:24:17] quan tiền n rất là nhạy cảm. Đó là khách
[01:24:20] thấy thanh toán rồi là khách sẽ như nào
[01:24:22] đấy các thứ. khách muốn có kết quả luôn
[01:24:25] thay vì phải thông báo là bạn đợi tí
[01:24:27] tiền tội về túi tôi đã thì nó cũng nói
[01:24:31] chung là tùy mình cần khách mà
[01:24:34] chỉ có ngân hàng hay hệ thống lớn là
[01:24:37] theo kiểu là nó sợ bài toán rủi ro nó sợ
[01:24:40] là kiểu bây giờ có nhiều thằng cùng bị
[01:24:42] thế là tao sẽ bị nếu mà có vấn đề xảy ra
[01:24:45] tao bị đền bù nhiều quá nên là tao phải
[01:24:47] chắc chắn về nghiệp vụ đấy mày có thể
[01:24:50] đợi cũng được nhưng tao không đợi được
[01:24:51] kiểu thế Còn mình làm về trang thương
[01:24:54] mại điện tử thì rõ ràng là mình cần
[01:24:56] khách. Khách có khách nó bấm vào của
[01:24:59] mình đôi khi bấm nhầm ấy, kiểu hiển địa
[01:25:01] quảng cáo nó bấm nhầm vào ấy nên là mình
[01:25:04] sẽ phải làm mọi thứ níu chân khách và
[01:25:06] vòi được tiền của khách nên sẽ không có
[01:25:08] chuyện mà mình kiểu mình lại bắt khách
[01:25:10] phải đợi. Khách mà đợi thì ví dụ nó đã
[01:25:12] bấm nhầm vào nó ngồi xem lướt qua một tí
[01:25:15] để xem có cái gì thôi nó thoát đúng
[01:25:16] không? bấm nó còn phải bắt nó đợi 3 4
[01:25:20] giây để mà làm một cái thao tác nữa thì
[01:25:22] nó đi ngay đúng không ạ?
[01:25:25] Đúng rồi. Giống như bạn kia nói là nên
[01:25:28] có sự đánh đổi chết off đúng không? Cái
[01:25:30] này à cái này liên quan tí nó không phải
[01:25:34] quyết định của anh em mình là dep mà
[01:25:36] quyết định của thường là product owner
[01:25:39] là người kiểu chịu rủi ro và quản lý về
[01:25:42] chất lượng của cái sản phẩm dự án thì
[01:25:46] người ta sẽ biết được cái nào nên đánh
[01:25:48] đổi đúng không ạ?
[01:25:51] Nhưng là tôi chỉ nói qua thế cho anh em
[01:25:54] nào chưa động đến mảng ví dụ ý nhất là
[01:25:56] giống như tôi vừa nói là mảng kim mại đi
[01:25:58] tử hay các thứ thì anh em sẽ biết được
[01:26:01] là kiểu cái gì cũng có hai mặt đúng
[01:26:03] không ạ.
[01:26:06] Trong bối cảnh đa luồng và tron
[01:26:11] thì thường được hiểu là tính nhất quán
[01:26:13] của trạng thái khi nhiều trùng truy cập.
[01:26:16] Đúng rồi.
[01:26:19] Đang bị sửa dở ra.
[01:26:28] Nhiều người nhầm lẫn hai khái niệm và
[01:26:30] sai lầm nghiêm trọng.
[01:26:33] Ủa còn phân tán nữa.
[01:26:36] Ở bên công ty tôi là cũng đa quốc gia,
[01:26:39] cũng làm ở đ
[01:26:42] server cũng đang quốc gia nên là thành
[01:26:43] ra là khi mà khi mà đồng bộ dữ liệu về
[01:26:46] từ
[01:26:48] kiểu các khu vực về một nơi thống nhất
[01:26:53] là gọi database master đúng không? thì
[01:26:55] nó cũng liên quan đến vụ mấy cái vụ phân
[01:26:57] tán này. Xong rồi xử lý xử lý phân tán
[01:27:00] xử lý bốc một bộ nó cũng lằng nhắng phết
[01:27:04] sẽ mang nghĩa là hẹp và đau đầu hơn. Mọi
[01:27:08] nốt trong hệ thống khi đọc cùng một dữ
[01:27:10] liệu tại cùng một thời điểm sẽ nhận được
[01:27:13] cùng một giá trị. Đấy đấy đấy tôi đang
[01:27:15] định nói này nghĩa là gì chỉ rõ ràng là
[01:27:18] ở trên master chưa đồng bộ cái đơn đấy
[01:27:21] về theo kiểu ví dụ là đơn đấy đã thanh
[01:27:24] toán ở khu vực đấy rồi nhá nên chưa kịp
[01:27:26] đồng bộ về đã thanh toán ở master thì rõ
[01:27:28] ràng khi đọc
[01:27:30] dữ liệu ở hai nơi khác nhau rõ ràng nó
[01:27:33] sẽ trả về giá trị khác nhau đấy
[01:27:40] thì chấp nhận sai lệch tạm thờ miễn là
[01:27:44] cuối cùng sẽ đồng bộ lại. À đây đây cái
[01:27:46] eventually này tôi nhớ là hôm trước tôi
[01:27:48] có chia sẻ cái video TikTok gần đây lướt
[01:27:52] TikTok nhiều nhưng mà may trên đây cũng
[01:27:54] nhiều cái bổ ích. Đấy, tôi cũng nói về
[01:27:56] khái niệm về à tôi có chia sẻ cái video
[01:27:59] đấy ở trên kênh trên kênh Discord rồi
[01:28:02] mấy ông thực ra tôi không thấy mấy ông
[01:28:04] tương tác và mấy kênh đấy bao giờ nhưng
[01:28:06] tôi vẫn thích chia sẻ
[01:28:08] thì trên đấy ừ chắc là tôi không
[01:28:13] tôi sẽ thỉnh thoảng tôi sẽ tải cái video
[01:28:16] đấy nếu tải được rồi đăng lên a fanpage
[01:28:19] cũng được để mấy ông có thể xem không
[01:28:22] phải mỗi xem trên server Discord vì
[01:28:24] nhiều người đúng là tôi thấy không để ý
[01:28:26] disc lắm.
[01:28:31] phải dính phải bài của tôi thôi
[01:28:39] khả năng chịu lỗi.
[01:28:45] sang hẳn kia. Thôi học tiếp nhá. Tring
[01:28:48] builder nhưng có method. Method này là
[01:28:53] method này là đồng bộ đúng không nhỉ?
[01:29:02] À không, cái này không phải đồng bộ. Cái
[01:29:04] này là
[01:29:07] hôm nay học phần nào thế anh ơi? Hôm nay
[01:29:10] sang ngày thứ ba em ạ. Tuy là ghi là
[01:29:12] ngày hai nhưng thực ra là anh học trước
[01:29:14] một buổi rồi. Hôm nay ngày 3 tí anh sẽ
[01:29:18] đẩy mấy cái bài này lên để em xem trong
[01:29:22] cái sườn nhá.
[01:29:32] chỉ
[01:29:33] thực thi một đoạn cốt hợp
[01:29:36] cựng chế
[01:29:43] này nó lại đang hơi lý thuyết quá để tôi
[01:29:47] đọc xong rồi tôi thử thử. Thường là đôi
[01:29:50] khi không biết là não ông mấy ông hoạt
[01:29:53] động xử lý thế nào. Hưng não tôi thì sẽ
[01:29:55] xử lý được kiểu khi đọc một cái gì đó
[01:29:57] phức tạp. Cái này nó n nào giống như là
[01:30:00] hồi à tôi học về triết học map Lenin hay
[01:30:03] các thứ ấy kiểu bạn tôi thì tôi vẫn nhớ
[01:30:07] như in hồi đấy. Có thể câu chuyện này
[01:30:09] tôi từng kể rồi nhưng tôi cứ kể lại nhá.
[01:30:11] là bạn tôi thời đấy bạn tôi đầu tiên là
[01:30:15] bạn đấy định nhờ tôi giúp kiểu kiểm tra
[01:30:19] miệng nhưng kiểm tra kiểu học vẹt thôi
[01:30:21] vì bạn đấy kiểu bảo là mấy kiến thức này
[01:30:23] khô khan và khó ấy đấy xong tôi bảo là
[01:30:25] mấy cái này dễ học mà xong kiểu bạn ấy
[01:30:27] kiểu vãi chưởng mày học được chết ma
[01:30:30] xong rồi kiểu học được kiểu các thứ này
[01:30:32] á xong rồi tôi đọc một lượt xong rồi tôi
[01:30:36] giải thích cho nó nhưng bằng mấy cái
[01:30:38] kiểu ví dụ công cụ sản xuất thì thì nó
[01:30:41] là thực ra là mấy cái quốc xong mấy cái
[01:30:43] kiểu nói chung là kiểu cái hình dung mấy
[01:30:45] cái ví dụ đơn giản ấy. Đấy đại khái là
[01:30:49] tôi đọc một cái phức tạp rồi tôi sẽ cố
[01:30:51] biến nó thành cái đơn giản để tôi nhớ là
[01:30:53] tôi dễ hình hiểu hơn. Đấy xong rồi tôi
[01:30:56] giảng được cho nó. Đấy, xong rồi tôi
[01:30:58] giảng xong xong rồi tầm hai tiếng thôi.
[01:31:03] Rồi ngày hôm sau nó đi thi nó được 8
[01:31:06] điểm xong nó về nó khỏ nó bảo là mày
[01:31:08] nhất định về sau phải làm thầy giáo vì
[01:31:10] mày có thể giảm một cái thứ rất là phức
[01:31:12] tạp thể dễ hiểu được như thế. Đấy, đấy
[01:31:15] một trong những cái rất là lớn làm tôi
[01:31:17] về sau muốn đi dậy.
[01:31:20] Thì cũng kiểu thế. Tôi nghĩ là mấy cái
[01:31:22] này có thể bây giờ thực ra tôi nếu mà
[01:31:25] tôi lười hơn thì tôi có thể dùng AI để
[01:31:26] mà
[01:31:28] bắt nó kiểu đơn giản hóa mấy cái này
[01:31:31] cũng được.
[01:31:36] Nghĩa là ông không cần phải học một cái
[01:31:38] gì đó quá cứng ngắc quá cứng nhắc. Ông
[01:31:41] chỉ cần hiểu bản chất của nó đúng không?
[01:31:43] Nghĩa là một cái từ này giả sử ông không
[01:31:45] biết được mà cái từ nàyểu không biết
[01:31:47] được từ tiếng Anh dịch từ tiếng Việt
[01:31:49] cũng được không sao miễn là mình làm mọi
[01:31:51] thứ theo bản chất mà bởi vì rõ ràng là
[01:31:54] vừa nãy ông thấy là tôi vừa gọi sai
[01:31:55] chính tả cũng được tôi gõ tiếng Việt
[01:31:57] cũng được thằng anh nó vẫn hiểu và nó
[01:31:59] vẫn tạo ra code ở cho mình mà đúng không
[01:32:01] quan trọng là mình hiểu bản chất và mình
[01:32:03] biết được cơ chế hoạt động mọi thứ để
[01:32:05] mình làm kiểu mục mục tiêu thì mình vẫn
[01:32:08] là
[01:32:10] tôi vẫn nói lại cái cốt lõi nhá mục tiêu
[01:32:12] vẫn là mình là lập lập trình viên. Mình
[01:32:14] không phải là người viết code. Mình lập
[01:32:17] trình viên tức là mình sẽ là người làm
[01:32:19] mọi thứ để mà giao tiếp về máy tính để
[01:32:21] máy tính phục vụ cho mình. Đấy. Đấy. Cốt
[01:32:24] lõi theo như tôi hiểu lập trình viên là
[01:32:26] nên thế. Tức là mình có thể nói chuyện
[01:32:28] giao tiếp như này mà máy tính hiểu, máy
[01:32:30] tính làm được thì quá tuyệt vời luôn.
[01:32:32] Đấy. Nhưng mà bây giờ máy tính chưa thế.
[01:32:34] Bây giờ thì mình vẫn phải nói chuyện với
[01:32:36] nó thông qua ngôn ngữ lập trình. Nhưng
[01:32:39] mà bây giờ còn có hay là mình không nói
[01:32:40] chuyện với nó theo cờ trực tiếp và ngôn
[01:32:43] ngữ lập trình nữa. Mình nói với con AI,
[01:32:45] con AI sẽ biến nó thành ngôn ngữ lập
[01:32:47] trình để mà máy tính làm cho mình đúng
[01:32:50] không ạ? Đấy
[01:32:53] nhưng là nó vẫn chung quy lại vẫn là
[01:32:55] mình lập trình viên mình là người kiểu
[01:32:58] là chủ của nó. Mình phải kiểm soát được
[01:33:00] nó và mình hiểu được nó làm được những
[01:33:02] gì ra lệnh được cho nó. Còn ông nào mà
[01:33:05] bị phụ thuộc, ông nào bị kiểu bó hẹp là
[01:33:07] mình phải
[01:33:09] theo phải kiểu giỏi ngôn ngữ này hay là
[01:33:12] phải như nào như nào đấy thì rõ ràng là
[01:33:14] nó đang hơi bó hẹp cái khả năng của mình
[01:33:17] mà đúng không ạ?
[01:33:25] loại lock đúng không?
[01:33:28] Mỗi object đều có một ổ khóa ngầm.
[01:33:49] khó hiểu dần rồi. Không sao, để tôi thử
[01:33:51] bảo thừ đơn giản hóa kèm ví dụ
[01:33:58] giải thích cho tôi được không?
[01:34:02] Nó giải thích phức tạp như này bởi vì nó
[01:34:04] nghĩ là trình độ mình đã đủ cao rồi và
[01:34:07] nó nghĩ mình thông minh. Cứ thế đi. Đấy.
[01:34:10] Thuật ngữ thừa đi thẳng vào bản chất.
[01:34:12] Đúng rồi. Bởi vì nó nãy giờ nó dùng rất
[01:34:14] nhiều thuật ngữ luôn. Tôi thấy là bắt
[01:34:15] đầu hơi bị lạm dụng thuật ngữ.
[01:34:24] là dễ dễ hơn cho các ông các ông và tôi
[01:34:27] cùng nhìn thấy số tiên là 100 cộng thêm
[01:34:29] 10 dự định là ghi 110 cộng thêm 20 dự
[01:34:33] định ghi là 120.
[01:34:51] &gt;&gt; Tôi nhớ cái bình luận của gần đây đúng
[01:34:55] gần đây có cái nổi trên TikTok và tôi
[01:34:58] xem nhiều cái video kiểu thế người thông
[01:35:00] minh như bạn sẽ nghĩ ra cách thứ làm các
[01:35:02] thứ thứ buồn cười xong rồi kiểu toàn mấy
[01:35:04] ông bình luận kèm ảnh tôi á đ cười được.
[01:35:21] kết quả
[01:35:23] có thể là 110 hoặc 120 nhưng không bao
[01:35:25] giờ là 130. Đó là đấy, giống như tôi nói
[01:35:28] nếu mà giả sử mà update đương nhiên là
[01:35:30] cái lỗi SQL này có một cách sửa đó là
[01:35:33] chỉ là cộng thêm vào chứ nó không kiểu
[01:35:38] kiểu
[01:35:39] nhưng mà đối với SQL như thế. Còn với
[01:35:42] trong cái kiểu class xong rồi còn đa
[01:35:45] luồng như này và dùng cái kiểu dạng như
[01:35:48] này này.
[01:35:49] Kiểu dạng ghi vào cái một cái gọi là một
[01:35:53] cái địa chỉ nào đó. Đây địa chỉ bụ nhớ
[01:35:56] mà đúng không? Đấy một cái achill nào đó
[01:35:58] thì đôi khi là nó sẽ nó có thể tăng các
[01:36:01] thứ các thử. Để xem nào.
[01:36:07] được cầm bút ghi vào sổ người khác phải
[01:36:09] chờ.
[01:36:11] Ghi xong đặt bút xuống. Uây giải thích
[01:36:13] kiểu kiểu dễ hình dung đúng không?
[01:36:17] Ví dụ tối giản như sau. Chỉ cần đọc
[01:36:19] không cần nhớ cúi pháp. Ok. Nghĩa ở đây
[01:36:23] là khi chạy không được cái nào chạy trên
[01:36:27] cùng method à khai báo kiểu như này
[01:36:30] nghĩa là chỉ có thằng này duy nhất là
[01:36:33] thằng được gọi đến cái hàm này thôi đúng
[01:36:35] không? Đấy thằng này thằng sau gọi đến
[01:36:38] thì nó sẽ phải đợi thằng này chạy xong
[01:36:40] thì mới gọi được đúng không?
[01:36:43] Nếu bỏ đi là sẽ kiểu
[01:36:47] sẽ
[01:36:49] tùy được may rồi. À đấy nói hay hay nói
[01:36:53] câu nói hay lúc đúng lúc sai tùy may
[01:36:55] rồi. Không biết là thằng này có kiểu lấy
[01:36:58] giọng văn của tôi không nói chuyện nó
[01:36:59] nhiều có khi giọng văn nào giống mình
[01:37:01] đúng không?
[01:37:07] anh có một tài khoản ngân hàng đấy. Ừ.
[01:37:10] Bây giờ còn liên hoàn trừ tiền là còn
[01:37:11] nhạy cảm hơn đúng không? Đấy số tiền
[01:37:16] dư không âm vô lý do race condition đấy
[01:37:19] nghĩa là nó là liên quan đến kiểm tra
[01:37:21] điều kiện đúng không? Không được phép
[01:37:22] âm.
[01:37:24] Nếu không hai lệnh rút cùng nghĩ rằng
[01:37:27] mình còn tiền đủ và trừ trồng lên nhau.
[01:37:29] Đấy mỗi lần chỉ một tho. Uây ui ví dụ
[01:37:33] này hay dễ hiểu kinh khủng luôn. Ví dụ
[01:37:35] này được
[01:37:38] hay thật.
[01:37:45] đấy.
[01:37:56] à
[01:37:59] gọi như nào nhỉ? mấy cái bài về so sánh
[01:38:02] hiệu năng các thứ các thứ thì chắc là
[01:38:04] tôi mình chưa cần biết lắm ấy vì mình đã
[01:38:08] làm dự án lớn để mình biết được lắm đâu.
[01:38:11] Hơi khó để mà nói về cái này.
[01:38:26] đâu xem nào. String là chuỗi cố định ít
[01:38:28] thay đổi. Cái này dùng nhiều nhất nối
[01:38:31] chuỗi, xử lý chuỗi phức tạp. Single
[01:38:34] thread. Còn cái này chỉ dùng khi mà liên
[01:38:37] quan đến kiểu
[01:38:39] cái kia là parallel hay consistent đúng
[01:38:43] không? Nó tiếng nó cái gì nhỉ?
[01:38:46] Consistent à?
[01:38:48] Đúng rồi. Consistency
[01:38:50] đấy.
[01:38:52] Đồng thời
[01:38:55] hiếm dùng legacy code hiếm dùng cơ. Xem
[01:38:59] ạ. Đấy.
[01:39:03] Tránh nối chuỗi
[01:39:05] trong
[01:39:07] lúc.
[01:39:15] Concruency. Ok. Ok. Concruency.
[01:39:20] Ok. Uầy. Hôm nay tuy là nó rất nhiều
[01:39:22] nhưng thực ra là mình đã xong buổi pa
[01:39:24] rồi đấy.
[01:39:25] [tiếng cười]
[01:39:27] Thực ra là mình nói không phải mỗi học
[01:39:29] nữa. Mình còn kiểu đây trao đổi các thứ
[01:39:32] các thứ gọi là gì nhỉ? Ờ trao đổi chiêu
[01:39:35] thức. Đấy.
[01:39:39] Mỗi ngày thực ra tôi bảo chỉ nên học ít
[01:39:41] này thôi bởi vì ngày hôm sau còn phải ôn
[01:39:43] lại nhá. Đấy, hôm nay tôi còn ôn cả buổi
[01:39:45] một buổi hai rồi. Ngày hôm sau nữa tôi
[01:39:46] lại ngồi ôn lại tiếp có giờ thứ mỗi ngày
[01:39:48] chỉ ít ít ít thôi đúng không ạ? Ông nào
[01:39:51] bây giờ mới vào thì à tôi xem lại nhá.
[01:39:55] Đấy, có ông nào còn à hỏi hay thắc mắc
[01:39:59] gì thêm không ạ?
[01:40:12] mà mình sẽ cứ kiểu có chủ đề để mình nói
[01:40:15] kiểu thêm những cái kiểu liên quan nữa.
[01:40:18] Tôi cảm thấy thật ra nó vẫn đâu chỉ dừng
[01:40:20] lại ở mỗi hôm nay học mỗi chuỗi đâu đúng
[01:40:22] không? Hôm nay thực ra tôi thấy nó nhiều
[01:40:24] nhất lại liên quan về việc đa luồng cơ
[01:40:26] về cái các thứ kiểu kia cơ đúng không?
[01:40:29] Chuỗi chỉ là một phần thôi đúng không?
[01:40:33] Đấy và thậm chí là mấy cái này về sau
[01:40:35] hôm nay có đề cập thấy xong rồi những
[01:40:38] cái bài những cái bài sau này ấ có nhắc
[01:40:40] đến đa luồng hay các thứ thứ ấy mình
[01:40:42] kiểu
[01:40:44] não mình tôi nhớ có một cái rất là hay
[01:40:47] đó là có thể là mình thấy khó ngay tại
[01:40:49] thời điểm hiện tại nhưng mà tuy là mình
[01:40:52] không được phép nói với nó là mình bỏ
[01:40:55] cuộc ví dụ nhá ví dụ nhá tôi nhớ hồi
[01:40:58] trước có một cái ví dụ tôi đọc được thôi
[01:41:01] Nhưng mà tính của tôi là tôi hôm trước
[01:41:04] tôi có tra thì tôi theo ch nghĩa. Hồi
[01:41:07] trước tôi tưởng duy tâm như không đúng.
[01:41:08] Tôi theo duy trí chị ạ. Mình theo cái
[01:41:11] niềm tin của mình là đôi khi chính vì
[01:41:14] niềm tin đấy. Kiểu
[01:41:16] cái này tôi nói và mấy ông phải nghe.
[01:41:18] Hôm trước tôi thử nói bạn gái bạn gái
[01:41:20] không nghe nhưng mà tôi nghĩ là bây giờ
[01:41:22] tôi nói mấy ông phải nghe thôi. Bình
[01:41:24] thường bây giờ tôi thử hỏi lại mấy ông
[01:41:26] về lý thuyết về duy vật và duy tâm đúng
[01:41:29] không ạ?
[01:41:31] À tôi tôi vẫn nói là tôi nói theo cái lý
[01:41:35] thuyết mà tôi biết thôi nhá. Có thể
[01:41:36] không đúng mấy ông lại bảo lại sửa lại
[01:41:38] tôi nhá. Thì
[01:41:40] thì à nhiều người bảo là theo chủ nghĩa
[01:41:42] duy vật chẳng hạn bởi vì người ta coi
[01:41:44] vật chất là quyết định ý thức đúng
[01:41:46] không? Nghĩa là kiểu phải có vật chất
[01:41:50] trước thì mình mới có kiểu ý thức hay là
[01:41:54] mới có kiểu gì đó đúng không? Đấy và từ
[01:41:57] cái đấy kết luận ra cái duy trí tức là
[01:42:00] là duy trí tức là mình phải có lý trí và
[01:42:03] lý trí đấy mình sẽ quyết định cái
[01:42:07] những cái khác. Đấy còn bình thường theo
[01:42:09] di tâm là mình sẽ có ý thức và mình sẽ
[01:42:13] chuyển hóa nó thành vật chất.
[01:42:16] Câu đấy không biết đúng hay không nhưng
[01:42:17] lại khái cái ý thức ở đây tôi nhớ về cái
[01:42:20] di tâm ấy nó lại theo kiểu sống theo
[01:42:22] kiểu dạng như là
[01:42:24] ông không cần vật chất ông kiểu dạng là
[01:42:27] ông có thể tự mình tịnh được rồi kiểu
[01:42:30] thế còn duy trí thì nó sẽ không phải như
[01:42:31] thế duy trí theo kiểu là dùng lý trí để
[01:42:34] mà quyết định ra nhiều cá thì
[01:42:38] đợi tí tại sao à thì ý tôi thế nghĩa là
[01:42:40] tôi tin vào một cái gì dần dần nó sẽ
[01:42:45] nó sẽ thành đúng ấy kiểu thế.
[01:42:47] Và tại sao tự nhiên tôi đề cập cái đấy?
[01:42:49] Vì vừa nãy có nói về vụ là học cái này
[01:42:53] lúc đầu khó nhưng mà tôi từng nghe cái
[01:42:56] nó là lúc đầu có ai đó hỏi ông một câu,
[01:43:00] ông có thể chưa biết đáp án ngay nhưng
[01:43:03] ông không ông không bỏ cuộc nghĩ đến nó.
[01:43:07] Đôi khi là ông không cần nghĩ nha. Nhưng
[01:43:08] não ông kiểu nó vẫn tự động nghĩ, nó
[01:43:11] kiểu chạy kiểu chạy ngầm ấy. Đấy, nó vẫn
[01:43:14] sẽ chạy ngầm ở đằng sau. Nếu mà ông
[01:43:18] nếu mà ông kiểu dạng là à
[01:43:23] kiểu dạng ông không ngừng nghĩ thôi, tôi
[01:43:25] chẳng biết được diễn ra câu đấy như này.
[01:43:27] Đại khái là ông không bỏ cuộc, nghĩ vậy
[01:43:30] bình thường bỏ cuộc là như nào? Ví dụ
[01:43:32] giả sử không câu đấy khó quá tao không
[01:43:34] làm được thì tự nhiên là ông giống như
[01:43:37] ông chặn kiểu ông chạy lệnh chặn luôn
[01:43:40] không cho não nghĩ nữa nhưng ông sẽ bảo
[01:43:43] là để tôi sẽ nghĩ các thứ thứ
[01:43:47] và đúng là não ông sẽ tự động nghĩ ngầm
[01:43:49] cái đấy thật và về sau khi mà người ta
[01:43:52] nhắc lại câu đấy đôi khi ông có luôn câu
[01:43:54] trả lời đấy kiểu kiểu như thế ví dụ là
[01:43:57] hồi đấy đã từng có nhà khoa học thử thí
[01:43:59] nghiệm cái vụ đấy là thử hỏi bạn một
[01:44:01] phép toán kiểu ví dụ là mấy trăm cộng
[01:44:04] mấy trăm bao nhiêu ấy nhưng mà thay vì
[01:44:06] để người ta trả lời ngay người ta sẽ
[01:44:08] kiểu đánh chống lảng để người kia làm
[01:44:10] những cái việc khác và hỏi những câu
[01:44:11] khác người kia chưa kịp chưa kịp trả lời
[01:44:14] và chưa kịp tính nhá chưa kịp tính nhẩm
[01:44:15] trong đầu cái đấy phải tính nhầm cái
[01:44:17] không thể phát ra ngay đấy người ta muốn
[01:44:19] cho một cái bài toán mà không thể phát
[01:44:20] ra ngay được không thể tính nhẩm nhanh
[01:44:22] được ấy nhưng người ta vẫn có tính nhẩm
[01:44:24] trong đầu và khi mà cái nhà thính nghiệm
[01:44:27] đấy là thử hỏi lại ông đấy cái câu hỏi
[01:44:29] ban đầu tính kia ông ấy bật luôn luôn
[01:44:31] được ra kết quả. Tức là bản chất là não
[01:44:33] mình có chạy đa luồng và chạy ngầm để xử
[01:44:36] lý cái thông tin kia. Đấy thì tương tự
[01:44:38] giống như là những cái lần đầu mình học
[01:44:41] mình có thể thấy khó như này nhưng mà
[01:44:43] mình không bỏ cuộc. Dần dần về sau mình
[01:44:46] có nhắc lại thì mình lại thấy nó sẽ dễ
[01:44:48] hơn bởi vì não mình bản chất là mình đã
[01:44:51] đã có động đậy cho cái điều đấy rồi. Đấy
[01:44:54] cái này theo khoa học nhá.
[01:44:57] Đâu nay học Java mới có mấy khái niệm
[01:45:02] này nhỉ? Đúng rồi, đúng rồi. Đấy, thế
[01:45:04] nên là tôi mới cảm thấy là Java hay mà
[01:45:06] kiểu mình sẽ biết rồi thêm nhiều cái mới
[01:45:08] và ừ và mình sẽ mình sẽ kiểu thắc mắc là
[01:45:13] tại sao mọi người dùng Java. Đấy, có
[01:45:15] những cái dự án mà chỉ dùng Java thôi
[01:45:17] không dùng PP. Đấy, tại sao như thế?
[01:45:20] Không phải bởi vì là nó ngại thay đổi
[01:45:21] đâu. Đấy, thậm chí là tôi vẫn nhớ là cái
[01:45:25] gần đây nhất thôi. Đó là cái à bên giao
[01:45:29] hào tiết kiệm à hồi trước giao h tiết
[01:45:30] kiệm dùng PP Larel nhá. Còn bây giờ
[01:45:34] chuyển qua Go và Java thì phải. Đấy. Tại
[01:45:37] sao lại chuyển qua như thế? Hồi trước
[01:45:39] chỉ thuần PP cơ mà. Đấy thì mấy ông sẽ
[01:45:42] hình dung được là có lý do của nó đúng
[01:45:45] không?
[01:45:51] multiad. Bây giờ xem viết chủ đề string
[01:45:53] thì anh em back and spam nội dung này
[01:45:56] của gia sớm thì em làm tốt phép. Đúng
[01:45:58] đúng đúng nghĩa là đấy kiểu mình học
[01:46:02] thầy khai sảng nhưng mà tôi bảo rồi may
[01:46:04] mà tôi học cái này sau lúc mà tôi đã
[01:46:07] biết tôi cảm thấy là tôi hơi đi dùng t
[01:46:11] đi sau đúng hơn là đi ngược
[01:46:14] hơi đi sau mọi người kiểu như thế nghĩa
[01:46:16] là
[01:46:18] rõ ràng là bình thường là mọi người có
[01:46:20] thể học những cái lý thuyết như này
[01:46:21] trước hồi đại học đúng không tôi đã học
[01:46:24] nghề trước đấy tôi làm thực hành trước
[01:46:26] nhưng mà tôi lại cảm thấy tôi quen cái
[01:46:28] đấy hơn. Tức hồi đầu mà tôi học tôi hồi
[01:46:31] đấy tôi trở đại học mà tôi không biết là
[01:46:33] tôi đội đại học và tôi học một cái này
[01:46:34] xong có khi bây giờ tôi không làm được
[01:46:36] lập trình viên chẳng hạn nó khó có thể
[01:46:38] thế đấy
[01:46:41] tôi học nghề trước và tương tự thế tôi
[01:46:43] học môn PP nó dễ hơn Java này trước đấy
[01:46:46] để bây giờ tôi cảm thấy tôi quay lại thì
[01:46:48] tôi vẫn học được chứ bây giờ để mà tôi
[01:46:51] nhảy thẳng luôn vào lý thuyết C X C+ C+
[01:46:55] xong Java các thứ như này rồi đi làm
[01:46:59] bằng Java nữa thì à
[01:47:01] tôi lại nghĩ tôi khó cạnh tranh hơn vì
[01:47:04] PP tính ra là học nhanh xong rồi đi làm
[01:47:06] nhanh được đấy.
[01:47:15] tu. Đúng đúng dùng từ thể tu rồi.
[01:47:20] Tại sao bạn không học Go hay Rus mà lại
[01:47:22] học Java?
[01:47:23] Ờ
[01:47:29] thì còn chưa tìm hiểu về go cả rus.
[01:47:32] Nhưng mà nếu mà sau Java này có thể mình
[01:47:35] sẽ sang Go bởi vì nhiều người bảo t PP
[01:47:38] thì nên nhảy sang go nhưng mà mình học
[01:47:40] Java ở code để mà biết về OP và những
[01:47:43] cái kiểu xử lý mọi thứ những cái m PP
[01:47:46] đang
[01:47:48] dùng từ hạn chế nhá. có thể là có rồi
[01:47:50] nhưng mà hạn chế vân vân này. Đấy và
[01:47:52] mình và khi mà mình học này mình cố thể
[01:47:55] học cái tư duy của một ông backend, một
[01:47:59] ông về thiết kế thiết kế hệ thống này
[01:48:02] các thứ thứ chứ không phải là mỗi mỗi
[01:48:06] học ngôn ngữ. Đấy thực ra các bạn thấy
[01:48:09] mình nói mình còn không code một dòng
[01:48:11] nào mà mình chưa code một dòng nào Java
[01:48:13] hay các thứ thứ này để mà bảo là mình
[01:48:16] đang học cú pháp hay là đang học ngôn
[01:48:18] ngữ. đúng không ạ? Mình chỉ dựa vào cái
[01:48:20] này để biết được là
[01:48:24] kiểu sự khác kiểu tư duy ý học cái tư
[01:48:27] duy đúng không? Đấy thì rõ ràng là thậm
[01:48:31] chí là giả sử về sau sang go thì mình
[01:48:34] cũng sẽ học kiểu na nán như này nhưng mà
[01:48:36] mình lại nghĩ mình hơi mình chưa tìm
[01:48:39] hiểu nhá nhưng mình cứ nghĩ đó là học
[01:48:41] Java này mà xong ổn nhá. Tôi tin là học
[01:48:43] sang Go nó lại ngắn và dễ hơn cơ. Đấy
[01:48:46] tôi nghĩ thế.
[01:48:54] trúc dữ liệu. Ừ thuật toán thực ra tôi
[01:48:57] cũng có đụng vào nhiều lắm đâu. À thế
[01:48:59] nên là rất nhiều lúc mà hồi trước mấy
[01:49:01] cái bài toán kiểu mà nó phức tạp một tí
[01:49:03] tôi cũng nhiều xếp viết cách toán hay
[01:49:06] các thứ thứ để nó hợp lý hơn.
[01:49:09] Ờ nhưng mà còn à cấu trúc dữ liệu thì ý
[01:49:13] không là cấu trúc dữ liệu và giải thuật
[01:49:14] đúng không? Cái đấy tôi nhớ tôi học ba
[01:49:16] lần nhưng mà tôi vẫn không chặng. Nghĩa
[01:49:18] là tôi học cho lúc học phải thì hiểu ấy
[01:49:21] nhưng mà không thể giải thích và cũng
[01:49:23] như là rất khó ứng dụng. Thời mà tôi bây
[01:49:26] giờ tôi làm có liên quan đến kiểu
[01:49:29] database mọi thứ thứ ấ thì có thể có
[01:49:32] đụng vào một tí nhưng mà đấy là mình
[01:49:35] kiểu mình vẫn dựa theo kinh nghiệm mình
[01:49:37] để mà mình à tự tự thiết kế database
[01:49:39] thôi chứ không phải là
[01:49:42] mình kiểu thành thục. Bởi vì tôi nhớ cái
[01:49:46] đấy là một trong những cái khó và nó cái
[01:49:49] quan trọng ấy đó là nó ít thực tiễn
[01:49:53] không phủ nhận về độ thực tiễn nó rất là
[01:49:55] tốt. Nhưng mà đang nói là ít thực tiễn ở
[01:49:56] đây tức là sao? Nghĩa là ví dụ nói về
[01:49:58] cái vụi chuẩn hóa đi. Thực ra database
[01:50:01] bây giờ tôi đa số tôi biết nhá. Đấy
[01:50:03] không làm theo chuẩn hóa mà nó chỉ chuẩn
[01:50:05] hóa một cách tương đối thôi. Bởi vì mình
[01:50:08] đôi khi là mình không muốn mình chấp
[01:50:10] nhận rủi ro chấp nhận những cái bài toán
[01:50:12] về cả vụ không nhất quán với dữ liệu này
[01:50:15] này. Nghĩa là bảng bảng này chấp nhận
[01:50:18] lưu thừa dữ liệu hơn để mà để mà đỡ phải
[01:50:21] join, đỡ phải kiểu lấy thông tin từ bảng
[01:50:23] khác vân vân. Đấy kiểu thế
[01:50:27] nó đã sai chuẩn hóa rồi đấy. Nên là học
[01:50:30] vẫn chỉ là lý thuyết thôi mà đúng không?
[01:50:32] Vẫn phải theo thực tiễn
[01:50:42] Thì về sau tôi học Go tôi tôi phải hứa
[01:50:46] cái vụ học Java này cách đây 2 năm rồi.
[01:50:48] Thì tôi không biết hứa vụ học Gâu là
[01:50:50] cách đây bao sẽ là bao bao xa nữa.
[01:50:57] nhiều. Ok
[01:51:00] được.
[01:51:02] không ngại. Tôi thật sự tôi không ngại
[01:51:04] đâu. Nhưng mà quan trọng là đấy xem mấy
[01:51:07] ông có đủ ngại đủ kiếp nhẫn này không
[01:51:08] thôi. Hiện tại thì tôi thấy là tôi nhớ
[01:51:12] thời đầu tôi livestream hồi học dạy về
[01:51:16] chẳng hạn. Hôm đầu tiên là tận hơn tr
[01:51:18] người tôi vẫn nhớ hơn tr người hôm kiểu
[01:51:21] khai giảng ấy. Đấy về sau là chỉ có hơn
[01:51:24] 10 người. Hiện tại thì bên Java này cũng
[01:51:29] sẽ thế.
[01:51:35] thời đầu thì sẽ đông về sau là sẽ kéo nó
[01:51:39] sẽ khác. Đấy
[01:51:48] liệu trong bảng thì không phải ấy sẽ
[01:51:50] khái niệm flash database ạ. Nghĩa là chỉ
[01:51:53] nó sẽ kiểu mình chấp nhận là việc mình
[01:51:56] lưu dư thừa để mình đỡ phải truy vấn
[01:51:58] sang bảng khác. Đấy nhưng mà nó chính vì
[01:52:01] như thế nó sẽ có thể sinh ra sai đúng
[01:52:03] không? Nghĩa là giữ liệu bảng khác cập
[01:52:05] nhật rồi bên này chưa cập nhật hay vân
[01:52:06] vân. Thường mình lưu thêm cái đấy mình
[01:52:08] thường hay lưu cột ID thôi. Code để mà
[01:52:10] kiểu mình ánh xạ sang đất dễ. Và những
[01:52:13] cái cột ID đấy phải ít khi thay đổi nữa.
[01:52:16] Dòng thời gian Samsung J2 khó nói. Ừ lỗi
[01:52:20] tôi. Tôi hồi trước tôi cũng là kiểm
[01:52:22] duyệt bên đấy và tôi cũng
[01:52:24] không thường xuyên duyệt bài. Tôi thường
[01:52:26] hay kiểu thường xuyên duyệt bình luận
[01:52:27] hơn. Nên này cũng lỗi tôi một phần là
[01:52:30] không phải thường không phải ghét việc
[01:52:31] duyệt bài mọi thứ đâu mà duyệt bài nhiều
[01:52:34] lúc nó cũng hơi khó ấy kiểu xóa bài dễ
[01:52:39] duyệt bài mấy ông mới khó bởi có nhiều
[01:52:41] bài phải kiểm tra vân vân có nhiều bài
[01:52:45] hồi trước là phần mềm là phải kiểm tra
[01:52:47] virus nhá xong rồi lẫn cả là còn phải
[01:52:50] xem ví dụ nhá tôi on vào cái giờ nó oái
[01:52:53] ăn kiểu nửa đêm chẳng hạn thì tôi không
[01:52:54] phải duyệt bài đấy bởi vì rõ ràng duyệt
[01:52:56] bài đấy thì
[01:52:58] làm bài không ai đọc thì nó cũng ảnh
[01:53:00] hưởng đúng không ạ? Đấy, nghĩa là mình
[01:53:02] phải on vào đúng giờ nữa để mà duyệt bài
[01:53:06] và lắm cả. Nếu mà on đúng giờ đi ông chỉ
[01:53:09] duyệt được một hay hai bài thôi. Bởi vì
[01:53:11] ông chẳng lẽ ông duyệt chục bài vào lúc
[01:53:13] đấy thì nó làm ảnh hưởng những bài khác
[01:53:15] đúng không? Nó làm ông ông hiểu ý tôi
[01:53:18] không? Chục bài thì bài sẽ bị flop, bài
[01:53:21] sẽ bị trôi đúng không? Đấy lại chỉ duyệt
[01:53:24] được một hai bài thôi. Đấy thành ra là
[01:53:26] xóa là nhiều chữ duyệt thì ít. Và cách
[01:53:30] dễ duyệt nhất thì đó đi duyệt bình luận,
[01:53:32] duyệt kiểu để ý duyệt thành viên hay các
[01:53:35] thứ. Duyệt dễ nhất thì duyệt lúc đấy.
[01:53:37] Duyệt cái đấy rồi lúc nã nào cũng được.
[01:53:39] Đấy thành hồi đấy tôi kiểm duyệt là
[01:53:41] chuyên về duyệt những cái khác hơn là
[01:53:43] duyệt bài đăng nên là bài đăng nó tần
[01:53:46] suất trong bài đăng trong đấy là luôn
[01:53:48] trong 400 500 bài. Không biết bây giờ
[01:53:51] thế nào bây giờ có công cụ AI chắc đỡ
[01:53:53] hơn.
[01:54:01] đôi khi là người ta lấy tài liệu từ đâu
[01:54:03] về chia sẻ kiểu rất là sợ rất là ghê ấ
[01:54:06] nhưng mà không biết được nó có thực sự
[01:54:08] đem lại giá trị không ý ví dụ người ta
[01:54:10] chia sẻ tt
[01:54:12] tra b tài liệu học tiếng anh không biết
[01:54:16] là đã chôn về ở những đâu kiểu thế nghe
[01:54:20] nghe hồi trước mình có thể rất là hay
[01:54:22] nhưng mà tôi từng thấy kiểu cái bài đôi
[01:54:24] khi đăng đi lại có nhiều bên và đôi khi
[01:54:26] là nó dính bản quyền hoặc là đôi khi là
[01:54:28] nó chỉ đơn giản nó nó hơi rác dữ liệu
[01:54:30] thôi. Kiểu kiểu có ai là người duyệt
[01:54:32] được đống đấy kiểu ngồi đọc hết đống đấy
[01:54:34] để mà
[01:54:36] để mà kiểu biết được là nó là thực sự là
[01:54:38] tài liệu chất cho mấy ông đúng không?
[01:54:40] Không ai cả không ai có thời gian để làm
[01:54:42] gì cả. Đấy thế đôi khi không rất khó
[01:54:45] duyệt mấy cái bài kiểu như thế.
[01:54:47] Tôi nhớ là bài đấy phải để 2 năm.
[01:54:50] Hình như bài vẫn chưa đồ duyệt hồ bị xóa
[01:54:53] không biết đâu.
[01:55:01] lại mọi thứ
[01:55:03] bởi vì chúng ta học những cái
[01:55:06] nó liên quan đến đô la liên quan tiền ấy
[01:55:08] và nó không chặt chẽ [tiếng cười]
[01:55:11] không sao. Trong PP nó khái niệm là biến
[01:55:14] mà đúng không? Trong này làm gì có biến
[01:55:17] biến tức là đây
[01:55:20] kiểu biến động
[01:55:27] Thấy nhiều chữ khó nhớ ác. Đấy do mà tôi
[01:55:30] học cùng mấy ông để mà nó có tương tác
[01:55:31] kiểu để mà nhớ một cái gì đó lâu ấy thực
[01:55:35] ra ông phải tương tác rất nhiều với nó.
[01:55:36] Còn nếu mà ông chỉ đọc
[01:55:40] cùng lắm và thực hành nữa nhá thì ông sẽ
[01:55:43] không nhớ nó rõ đâu. Đấy tôi nói chuyện
[01:55:47] với mấy ông như này, mấy ông có thể nghĩ
[01:55:50] là địt mẹ thằng này tập trung học gì
[01:55:51] cả. Nhưng mà đúng hồi trên trường hồi
[01:55:56] ngay từ hồi bé đến giờ là tôi không hề
[01:55:57] tập trung học.
[01:55:59] Tôi học vẫn rất tốt nhá. Bởi vì tôi
[01:56:03] thì nói như nào cứ cho nói đa luồng đi.
[01:56:05] Vừa học vừa ngồi nói chuyện với bạn bè
[01:56:08] hoặc là đôi khi không nói chuyện bạn bè
[01:56:11] thì giờ tay phát biểu hay làm mọi cách
[01:56:12] để mà không chỉ ngồi cắm đầu vào kiểu
[01:56:16] ngồi dán mắt vào đọc hay là cái gì đó nó
[01:56:20] sẽ bị nhiều người bảo buồn ngủ hay mất
[01:56:22] tập trung gì gì đó rất nhiều cái đúng
[01:56:24] không? Đấy, mình sẽ phải làm nhiều thứ
[01:56:27] nhưng nó không làm ảnh hưởng quá, không
[01:56:29] làm mình mỗi phân tâm bị sao nhãm quá,
[01:56:33] không làm mình bị các thứ quá
[01:56:37] thì tôi cảm thấy nó lại là cái kiểu hằn
[01:56:41] sâu trong cái trí ức của ông. Có rất
[01:56:43] nhiều tương tác tại thời điểm đây nên là
[01:56:45] nó sẽ dễ nó sẽ rất dễ nhớ.
[01:56:49] Về sau mấy ông có thể kiểm tra miệng lại
[01:56:51] tôi mấy cái này tôi nhớ nhá.
[01:56:54] Tôi sợ tôi kiểm tra miệng mấy ông mấy
[01:56:55] ông không nhớ. Thôi
[01:56:57] [tiếng cười]
[01:56:59] kể dễ tôi chấp mấy ông biết về cả Java
[01:57:01] trước rồi nhá
[01:57:09] làm một quả ca hút xong rồi mấy ông sẽ
[01:57:11] ngồi cùng làm cùng tôi.
[01:57:14] À thế như tôi ra đề thì chắc là hay là ừ
[01:57:17] tôi về sau tôi không biết c hood bây giờ
[01:57:20] nó có cái
[01:57:22] import bằng reason không? Chắc là có.
[01:57:24] Chắc có hỗ trợ còn không thích về xong
[01:57:26] tự mình code một cái app đấy cũng được.
[01:57:28] À nhưng mà retime thì cũng tốn không
[01:57:31] biết được. Nhưng đại khái là ừ học Java
[01:57:34] biết đâu về sau code cái app kiểu tương
[01:57:35] tự thế. Thế ý tôi là về sau dùng AI để
[01:57:39] mà tự tạo ra câu hỏi ngẫu nhiên để tôi
[01:57:41] cũng không gọi là không a gì nhỉ ra lận
[01:57:46] nha. Đấy xong rồi anh em mình cùng làm
[01:57:48] máy trắc nghiệmấy.
[01:57:54] vui đã
[01:58:02] nảy ra rất nhiều cái ý tưởng các thứ các
[01:58:03] thứ đấy. Mà tôi cứ mỗi lần như thế xong
[01:58:05] tôi lại cảm thấy kiểu tăng năng lượng
[01:58:07] ấy, kiểu phấn khích ý. Đấy, tính tôi rất
[01:58:11] là dễ bị phấn khích vìểu. Cảm thấy ui nó
[01:58:13] hay quá các thứ các thứ.
[01:58:16] Thường kiến thức à?
[01:58:18] Kiến thức thì cũng tuyệt đấy nhưng mà
[01:58:20] thứ anh cần là
[01:58:23] thôi tôi nghĩa thì xem TikTok quá thôi
[01:58:25] cũng gần hai tiếng rồi thôi tôi nghĩ là
[01:58:29] tôi sẽ tạm cho anh em ngừng ở đây tôi
[01:58:32] cũng cứu cho cái cổ tôi. Hôm qua tôi nói
[01:58:35] khản cả giọng và hôm nay sẽ
[01:58:39] đang khản giọng rồi đây. Đấy
[01:58:47] em, cảm ơn anh em đã lắng nghe ạ. Tạm
[01:58:50] biệt ạ. Đúng rồi, sẽ có thể sẽ học một
[01:58:53] ngày. Có gì tôi sẽ thông báo nếu có vấn
[01:58:55] đề kiểu có cái gì phát sinh. X chào anh
[01:58:58] em nhé.
