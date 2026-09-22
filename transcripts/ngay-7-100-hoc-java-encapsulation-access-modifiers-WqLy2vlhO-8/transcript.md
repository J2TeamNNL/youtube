# Ngày 7/100 học Java - Encapsulation & Access Modifiers

- Video ID: `WqLy2vlhO-8`
- URL: https://www.youtube.com/watch?v=WqLy2vlhO-8
- Published: 2026-01-27
- Duration: 1h 10m 16s (4216s)
- Language: vi
- Subtitle source: auto
- Kind: live

## Transcript

[00:00:40] Ừ
[00:00:47] mình vẫn chưa chuẩn bị à gọi nh nào chưa
[00:00:53] đăng cái bài lên là tạo cái cá hút.
[00:00:58] Chắc là để mình làm luôn được không nhỉ?
[00:01:01] Tận
[00:01:04] các thứ ở đây.
[00:01:06] Ừ.
[00:01:15] Thread hay thông báo nhỉ? Thread để cho
[00:01:17] mọi người có thể bình luận được nhá.
[00:01:20] À ca hút
[00:01:42] tham gia.
[00:01:45] Mọi người góp ý giúp mình.
[00:01:53] nhé. Đây
[00:01:56] ví dụ là
[00:02:02] ấ
[00:02:05] đây
[00:02:06] bộ câu hỏi
[00:02:09] giải thưởng
[00:02:12] định là top 3
[00:02:21] Tôi để ở góc này nhá.
[00:02:24] Các bạn không nghe được cứ bảo mình nhá.
[00:02:28] Ừ.
[00:02:30] thời gian
[00:02:38] à
[00:02:40] thêm cho anh con boss để
[00:02:45] tạo khung
[00:02:52] này nhé.
[00:03:00] không gọi nh trong tuần này chắc là mọi
[00:03:04] người vẫn kịp nhỉ đúng không?
[00:03:07] Bây giờ mới nhế thứ ba mà thì ví dụ thứ
[00:03:10] bảy chủ nhật chẳng hạn. Thế đấy. Ờ
[00:03:22] theo là cho mọi người đọc qua cái này
[00:03:24] nữa. Tôi tôi định là như thế nghĩa là
[00:03:27] mình sẽ không chỉ mỗi người học, mình sẽ
[00:03:29] ngồi nói chuyện và chia sẻ kiểu giao
[00:03:33] lưu, chia sẻ quan điểm về rất nhiều cái.
[00:03:37] Và
[00:03:39] nói chung là hồi trước tôi từng thích
[00:03:41] xem các streamer ấy thì thật ra là ngồi
[00:03:45] nghe họ nói
[00:03:47] là nhiều hơn so với việc là xem cái a
[00:03:52] thứ mà họ làm. Tức là sao? Ví dụ giả sử
[00:03:55] là các ông xem thưa các streamer nổi,
[00:03:59] mấy ông cũng thấy thế mà sự là ờ tôi xem
[00:04:03] của hôm trước có xem cả anh Độ này, cả
[00:04:07] anh Pu Piu này, cả
[00:04:11] gì nhỉ?
[00:04:14] Hồi trước có JV Everm nhưng mà cái đấy
[00:04:17] hiển nhiên là họ chỉ làm thuần về nội
[00:04:19] dung rồi. Nhưng mà đấy nghĩa là ông hiểu
[00:04:22] tôi không? Nghĩa lúc đầu là họ thể xuất
[00:04:24] thân là kiểu là một streamer về game
[00:04:27] nhưng mà rõ ràng là về sau các ông nghe
[00:04:29] thấy kiểu họ sẽ nổi về việc là
[00:04:34] chia sẻ cái quan điểm và họ sẽ nói là
[00:04:36] nhiều. Hôm đấy thì là mình không quan
[00:04:38] tâm về game mấy nữa, mình còn chơi game
[00:04:40] mấy nữa đâu. Đấy thì thôi cũng không hẳn
[00:04:44] là kiểu sẽ theo cái phong cách kiểu đấy.
[00:04:47] Nhưng ý tôi là kiểu tôi thấy thế là một
[00:04:50] cái tương tác nó cũng rất là hay. Nó
[00:04:52] không chỉ mỗi việc là tôi làm việc của
[00:04:55] tôi xong rồi mấy ông thì ngồi xem những
[00:04:57] thứ tôi làm đấy. Bởi vì thực sự thì nếu
[00:05:00] mà giả sử ông cùng trong ngành với tôi
[00:05:02] đúng không? Thế thì cái việc mà tôi làm
[00:05:04] có khi là ông còn ngứa mắt thế kiểu đãi
[00:05:08] ông phải cốt theo phong cách kiểu này
[00:05:09] đấy. Kiểu thế nhưng mà nếu mà giả sử mà
[00:05:13] cũng là người trong nhành với nhau đúng
[00:05:15] không? Nhưng mà chúng ta nói chia sẻ
[00:05:17] quan điểm với nhau thì nó lại hay. kiểu
[00:05:19] dạng là à tôi biết được cái mẹo của ông,
[00:05:22] biết được cái
[00:05:24] cách tư duy của ông khi mà đi bx các thứ
[00:05:27] khi mà gặp vấn đề thì ông xử lý như nào
[00:05:29] đấy nghĩa là người trong ngành với nhau.
[00:05:32] Đặc biệt là người trong ngành ngành ngi
[00:05:34] chung này đúng là chúng ta nói chuyện
[00:05:35] nhau rất nhiều nhá. Nhưng mà chúng ta
[00:05:38] nói chuyện về những chủ đề khác hay là
[00:05:40] chúng ta
[00:05:43] thực ra là tôi nghĩ là phải nói chuyện
[00:05:45] nhau nhiều nhưng mà ở trong cái không
[00:05:47] gian gọi là trong mối quan hệ vòng quan
[00:05:49] hệ của mình thôi và nó rất là ít nó rất
[00:05:52] là bé vì mình dân tính ra là dân IT mình
[00:05:55] không tiếp đi tiếp xúc nhiều nhiều ông
[00:05:57] còn hướng nội nữa tôi hồi trước tôi còn
[00:06:00] từng thấy là có nhiều ông là kiểu coi đã
[00:06:03] từng tâm sự với tôi nhiều tôi không tôi
[00:06:06] không nói là là họ kiểu dạng tôi không
[00:06:09] biết là họ có người khác để mà nói
[00:06:11] chuyện hay không nhưng từng có người
[00:06:14] chưa gặp tôi bao giờ nhưng tâm sự rất
[00:06:15] nhiều bởi vì họ tôi cảm thấy là họ
[00:06:19] ít mối quan hệ ở bên ngoài đấy tôi cảm
[00:06:23] thấy thế còn nếu mà họ tin tưởng tôi thì
[00:06:25] tốt thôi nhưng mà đấy nghĩa là tôi đã
[00:06:29] chia sẻ khá là đủ nhiều để mà họ tin
[00:06:32] tưởng để mà họ có thể tâm sự nói chuyện
[00:06:34] lạ nên tôi cảm thấy Đấy là một thành
[00:06:36] công rồi.
[00:06:39] Ơ có người vào này. Xin chúc mừng à nh
[00:06:42] xin chào các bạn. Nhưng mà không có ai ở
[00:06:46] đây
[00:06:47] chat nhưng mà mấy ông vào Discord tôi
[00:06:51] không biết được mấy ông vào Discord cha
[00:06:53] mấy ông tò mò xem trong đấy có gì. Thôi
[00:06:55] đa số là thế. Hồi trước tôi cũng vào tôi
[00:06:57] thoát mà.
[00:07:00] Đây.
[00:07:03] Ok. Chào cháu.
[00:07:06] À rồi ken hôm nay lên một bài mới. Cái
[00:07:10] này hôm trước của tôi chia sẻ nhưên tôi
[00:07:11] chưa kịp đọc.
[00:07:22] này là
[00:07:32] bài gốc. ở trên hai team community nhưng
[00:07:35] là bài này thực ra là cũng từ một ông co
[00:07:39] của lá phe đúng không? Đấy chia sẻ
[00:07:45] bài này không mang tính giải trí ít
[00:07:46] người đọc tương tác kiểu kiểu khả năng
[00:07:50] tương tác sẽ thấp đúng không tính ứng
[00:07:53] dụng trực tiếp đọc chỉ mở mở mang tượng
[00:07:56] góc nhìn và không đọc hết hiểu không tới
[00:08:00] định luật linh tinh khá mệt nhưng bài
[00:08:03] viết này nó sẽ
[00:08:07] chạm được một vấn đề nhầm lẫn phổ biến
[00:08:10] khi nói về open AI và AI nói chung.
[00:08:13] Đầu tiên chúng ta phải hiểu cần hiểu về
[00:08:15] Weat n tôi đang đọc hộ mấy ông nhá.
[00:08:18] Nhưng mà tôi thực ra tôi cũng đọc để tự
[00:08:20] tôi
[00:08:22] cứ cho là tự tôi đọc đi. Đấy tôi cũng
[00:08:26] nói biết để mấy ông biết tôi đang đọc
[00:08:28] đến đâu.
[00:08:35] học Java theo hướng nào vậy ạ? Anh học
[00:08:37] Java theo hướng ừ thật ra anh chưa ghi à
[00:08:43] anh có ghi rõ trong mô tả không nhỉ?
[00:08:47] Ừ hình như là anh còn chưa ghi rõ trong
[00:08:48] mô tả này thì phải. Lỗi của tôi.
[00:08:52] Ok. Tôi chưa ghi mõ trong một à. Đây để
[00:08:56] tôi ghi thêm
[00:08:59] bay.
[00:09:05] cái playlist thôi. Đợi tôi một tí tôi
[00:09:08] sửa lại. Đợi tôi một tí nhá.
[00:09:12] Tôi sẽ sửa lại cái mô tả đây.
[00:09:34] mấy ông cứ bình luận nhá.
[00:09:47] viên PP dễ sang nhưng sợ nó không đủ.
[00:09:52] Đây tôi sẽ
[00:09:54] ờ tôi sẽ dùng Gini ở đây đi.
[00:09:59] Tôi muốn ghi mô tả ngắn gọn về
[00:10:06] playlist.
[00:10:08] này
[00:10:11] từ một dòng trình viên PP dễ sang
[00:10:30] tìm hiểu sâu hơn về clean architect
[00:10:37] Thực ra tôi đã nói hết rồi. Thực ra dùng
[00:10:40] AI để nó xem kiểm tra lại xem nó hợp lý
[00:10:42] hay không thôi mà.
[00:10:45] Architect viết như này nhỉ? Visa hiện
[00:10:46] tại chắc không sao đâu. Ai tex đi đây
[00:10:51] kiểu nh không sao tí nó sờ lại mình à
[00:10:56] hướng đối tượng
[00:10:59] oop và
[00:11:03] xử lý chuyên sâu
[00:11:06] backend
[00:11:08] về các bài toán tối ưu
[00:11:13] và thiết kế.
[00:11:24] &gt;&gt; Đợi tôi tí. Đợi tí. Đợi tôi tí.
[00:11:56] tập trung đào sâu tư duy OOP clean
[00:11:59] architect đấy và viết sah tả nhưng mà
[00:12:03] quan trọng gì đâu ờ giải quyết Viết bài
[00:12:06] toán tối ưu hiệu năng back end
[00:12:09] performance và system design.
[00:12:17] hả? Có hạn chế à?
[00:12:20] Có hạn chế đâu
[00:12:22] cha ông lần đầu nói. Đ nó bị kiểu hạn
[00:12:25] chế chứ.
[00:12:39] động khi chế độ hạn chế được bật. Để xem
[00:12:42] video t nào cũng vì tôi đúng không?
[00:12:52] một lập trình viên PP lâu năm. Playlist
[00:12:55] này không chỉ học sinch
[00:12:57] mà là quá trình tôi nghiên cứu sâu về
[00:13:00] clean architect thiết kế hướng đối tượng
[00:13:02] và tối ưu hóa backend được đấy trông
[00:13:05] kiểu hợp lý hơn dành ra vlog đúng không
[00:13:08] dạng nhật ký cũng khá là hay nhưng mỗi
[00:13:10] tội thì nó có cái từ này tôi không thích
[00:13:13] này không chỉ học sin tách này nữa thực
[00:13:17] ra làm gì mình cũng học sinh tắc đâu
[00:13:20] chuyên nghiệp deep die java
[00:13:24] Chuyển đổi tư duy từ PP sang Java. Hệ
[00:13:27] thống hóa kiến thức từ về clean
[00:13:30] architect OP nâng cao và các kỹ năng các
[00:13:33] ui cái này chuyên nghiệp quá tôi không
[00:13:35] đế ngưỡng này. Tôi nghĩ là cái này khá
[00:13:38] là hay này hoặc cái này hay
[00:13:46] nào nhất? Tôi thấy phương án một này hợp
[00:13:48] lý đúng không? Phương án hai này thì
[00:13:50] cũng khá hay nhưng mà nó sẽ có thêm cái
[00:13:54] c như này
[00:13:58] không chỉ học sinch mình có học sin tách
[00:14:01] không nhỉ? Thứ không có mà đúng không?
[00:14:04] Nhưng mà nó sẽ nói giống như kiểu là
[00:14:07] ý tôi ấy là
[00:14:10] cái khóa này không hề dạy về cách viết
[00:14:13] Java nên cái câu mà không chỉ học sinch
[00:14:17] giống như là kiểu vẫn sẽ có học tức là
[00:14:20] chỉ là vẫn sẽ học Java cơ bản rồi mới
[00:14:24] bắt đầu nghiên cứu sâu ông hiểu chưa thì
[00:14:27] nó không đúng vì rõ ràng là chúng ta học
[00:14:30] có học cơ bản đâu chúng ta có học cách
[00:14:33] kiểu Java viết như thế nào vân vân vân.
[00:14:37] Cái đấy chắc là không.
[00:14:47] Mỗi tội hành trình chuyển mình
[00:14:49] thì nó lại không đúng bởi vì rõ ràng tôi
[00:14:52] không chuyển mình mà nó sẽ chỉở góc nhìn
[00:14:54] thôi.
[00:14:56] Ờ
[00:14:58] phương án
[00:15:09] chỉ đào sâu về tư duy
[00:15:22] tư này
[00:15:24] mental model này là từ gì gốc dễ các thứ
[00:15:27] đấy.
[00:15:41] thấy rằng Jini trả lời nhiều lúc kém nên
[00:15:43] là thôi tôi không dùng mấy cái này nữa.
[00:15:45] Tôi chỉ chơi pro thôi. Mà rõ ràng là cái
[00:15:48] từ pro mà đúng không? Thì rõ ràng là
[00:15:50] mình phải dùng th chứ mình trả tiền thì
[00:15:52] mình có cái này mà đúng không? Tôi cứ
[00:15:54] dùng cái này thôi. Nên thành ra vừa nãy
[00:15:56] tôi thấy khó chịu cái quả mà lúc mà tôi
[00:15:59] dùng chattivity đúng không? Thì nó sẽ nó
[00:16:03] sẽ gọi là như nào? Nó sẽ trả lời rất là
[00:16:05] nhanh đúng không? Thì rõ ràng nó không
[00:16:07] phải grow. Tôi còn đang dùng bản thường
[00:16:08] mà không phải bản mất phí. Đấy là tôi
[00:16:12] cảm thấy cấm k hỏi thằng Gemini nó trả
[00:16:15] lời lâu vãi. Xong mới nhận ra là ừ mình
[00:16:17] đang dùng cái chế độ là nó trả lời lâu
[00:16:20] mà. Nhưng mà trả lời lâu nhiều lúc tôi
[00:16:22] cảm thấy là tôi vẫn không ưng lắm.
[00:16:24] Chứ đừng nói là kiểu thà trả lời lâu của
[00:16:27] nó ưng nhá. Nên là tôi nghĩ là thực ra
[00:16:31] là công ty AI nói chung nó vẫn đang làm
[00:16:33] cho mình bị hơi bị rối mấy ông hình dung
[00:16:37] không? Kiểu ít ra chat VT còn nó còn làm
[00:16:39] mình dễ hiểu nhá. Chứ
[00:16:43] mấy thằng khác hiện tại nó cứ làm rối
[00:16:46] đến cả mang tiếng Google bây giờ nó làm
[00:16:48] mình rối. Hồi trước tôi từng nói là
[00:16:50] Google là một cái công ty khiến cho
[00:16:53] người dùng rất dễ dùng. Dễ dùng ở đây
[00:16:55] giao diện dễ dùng ấy. Kiểu lúc đó chỉ có
[00:16:58] một cái thanh tìm kiếm đúng không? Thanh
[00:17:00] đấy được ra người ta không hiểu thanh
[00:17:02] tìm kiếm. Cứ nhập bừa vào cái gì nó cũng
[00:17:04] ra. Nhập vào câu hỏi gì nó cũng sẽ có
[00:17:07] thể có một cái đáp án nào đó cho mình.
[00:17:09] nhập vào 1 + 1 mấy hay nhập vào à giá
[00:17:13] vàng hôm nay hoặc là đổi tiền tệ hoặc
[00:17:15] thời tiết hôm nay vân vân n thứ nó sẽ ra
[00:17:18] một cái gì phù hợp chưa chắc là nó là
[00:17:21] một chỉ cho mình mấy cái trang web mà
[00:17:25] đôi khi trả lời đáp án mình luôn đấy thì
[00:17:28] rõ ràng là Google từng
[00:17:30] kiểu khiến người dùng không phải nghĩ
[00:17:32] như thế đấy thì bây giờ Google lại khiến
[00:17:36] đi hơi bị
[00:17:38] trang ra nó bắt trước với cái thằng khác
[00:17:40] đang đi thì thôi mình cũng đi theo. Đấy
[00:17:43] lại làm ra cái ứng dụng không
[00:17:47] không phải nói là khó dùng bởi vì rõ
[00:17:49] ràng là tính ra thì mình vẫn dùng được
[00:17:51] chứ tôi nghĩ là nó sẽ không còn là tối
[00:17:54] giản hóa cho người dùng nữa. Người dùng
[00:17:57] đấy ví dụ tôi đến hình này bây giờ tôi
[00:17:59] chẳng biết chọn cái nào. Rõ ràng tôi
[00:18:00] muốn nó trả lời nhanh nhưng mà tôi không
[00:18:02] muốn nó trả lời kiểu quá thiếu suy nghĩ.
[00:18:06] Mà rõ ràng tôi nghĩ là tôi chọn cái này
[00:18:08] là phù hợp nhưng mà rõ ràng thanh kinh
[00:18:10] nó nghe nó không chất lượng với chữ pro.
[00:18:11] Tôi thích Pro đấy. Nhưng pro nó lại chỉ
[00:18:15] dành cho toán nâng cao và code đấy ông
[00:18:19] ông hiểu ý rồi. Bây giờ rốt cuộc là mình
[00:18:22] chọn cái nào đấy mà tôi nghĩ ở cái này
[00:18:25] nữa nhá. Giả sử tôi chọn cái này đúng
[00:18:26] không? Để mà chat bình thường nhá. Thì
[00:18:29] cái này nó vẫn trả lời lâu hơn cái này.
[00:18:31] Chắc chắn rồi. Đấy.
[00:18:34] Thế thì rõ ràng chẳng lẽ tôi lại bảo con
[00:18:36] này kém con chatt chatt rõ ràng tôi thấy
[00:18:40] nó trả lời tranh á. mà nó còn trọng tâm
[00:18:42] được đúng cái tôi hỏi nhiều lúc mà con
[00:18:44] này nó trả lời nó cứ lệch lệch trọng tâm
[00:18:46] kiểu gì hiện tại đang đúng bởi vì rõ
[00:18:48] ràng nó không hề liên quan đến cá nhân
[00:18:50] hóa là đúng thôi chứ mấy cái câu mà tôi
[00:18:52] hỏi liên quan cá nhân hóa kiểu kiểu gọi
[00:18:56] như là tôi từng nó nhắc nó trước đấy
[00:18:59] ngay trên luôn nhá không cần nhí phải mở
[00:19:01] cái lịch sử khác ấy nó trả lời kiểu
[00:19:03] chẳng liên quan gì cả đấy thế mà nó kêu
[00:19:06] cứ khoe contex đến 1 triệu
[00:19:14] nhìn từ một PP dep lâu năm. Tôi không
[00:19:18] thích từ lâu năm này. Tôi rồi. Thế nên
[00:19:21] vừa nãy mình dùng từ có kinh nghiệm.
[00:19:23] Lâu năm này nó hơi bị nghe nó kiểu khoe
[00:19:25] ấy. Ví dụ nhiều người sẽ c thắc mắc lâu
[00:19:29] là bao nhiêu đấy chẳng hạn. Thế nó không
[00:19:31] hay.
[00:19:33] Thứ ra từ có kinh nghiệm nó cũng thế
[00:19:34] thôi nhưng mà chỉ có kinh nghiệm nó gọi
[00:19:36] là
[00:19:38] cho là cứ từng trải một tí.
[00:19:47] Trả lời câu này nó hơi bị
[00:19:50] ok cũng được. Đây là hành trình tôi xây
[00:19:52] dựng lại mental model đảo sâu và clean
[00:19:56] architect. Thực ra là nó nhấn mạnh như
[00:19:58] này không hay này.
[00:20:06] Java bỏ qua cú pháp tập trưng vào tư duy
[00:20:09] hành trình 100 ngày tôi tái cấu trúc
[00:20:11] mental. Tôi không thích
[00:20:22] model.
[00:20:25] Ý tôi là
[00:20:27] học tư duy thôi.
[00:20:30] Bởi vì từ này từ này tôi không biết nên
[00:20:33] tôi cũng không muốn lạm dụng vào.
[00:20:36] Lâu lắm không gặp thầy. Xin chào bạn. Dù
[00:20:39] bạn bình luận thấy tôi không nhận ra bạn
[00:20:42] là chào. Tôi thường tôi nhớ mọi người
[00:20:45] qua việc người ta cũng thường nhắn tin
[00:20:47] tôi cơ. Trừ khi ông bình luận rất nhiều
[00:20:49] thôi. Ừ.
[00:21:06] không cần phải nhắc việc
[00:21:10] không dạy cứu pháp
[00:21:31] này cho nó trả lời được đồng ý tôi rồi
[00:21:34] đấy. Nó kiểu nó quen với cái giọng văn
[00:21:36] mình rồi. Ấ chắc mình mình ừ cứ cho là
[00:21:38] mình thích cái giọng văn nó đi. 100 ngày
[00:21:41] Java
[00:21:43] hành trình chuyển hướng từ PP chuyển
[00:21:46] hướng vẫn không đúng.
[00:21:49] hành à chuyển hướng
[00:21:53] không đúng vì tôi không bỏ PP, tôi chỉ
[00:21:58] học thêm Java thôi.
[00:22:07] OP và giải quyết các bài toán thiết kế
[00:22:10] hệ thống tối ưu backend chuyên sâu hành
[00:22:12] trình rẽ nhán. Nơi mình tập trung nghiên
[00:22:15] cứu
[00:22:17] cái từ nơi mình tập trung này cái nơi
[00:22:20] còn nhấn mạnh từ nơi này này nó nấy cái
[00:22:23] khóa học mà mình từng đọc nơi mà bạn sẽ
[00:22:27] thành công nơi mà bạn sẽ học được abc xz
[00:22:31] ở mình mình không muốn nó là một cái
[00:22:35] playlist khóa học
[00:22:37] thực ra playlist này tôi ghi là học
[00:22:43] Ừ, có khi playlist này tôi sửa lại thành
[00:22:45] ghi là
[00:22:47] ngày thứ bao nhiêu tôi học một cái gì đó
[00:22:49] chứ không phải là mỗi học Java thì mọi
[00:22:51] người cứ tưởng là vào đây để học nhở.
[00:22:58] nó mang hơi một tí cá nhân hóa hơn là
[00:23:01] tôi học hoặc là
[00:23:04] sửa lại như nào đấy.
[00:23:07] Trực diện và chuyên nghiệp mở rộng nền
[00:23:09] tảng từ PP.
[00:23:12] Câu này cũng được này. Mở rộng mà đúng
[00:23:14] không? Từ mở rộng cũng hay. Tập trung
[00:23:17] đào sâu
[00:23:20] 100 ngày.
[00:23:22] Java song hành của PP không đúng.
[00:23:26] Mở rộng thì đúng, song hành không đúng.
[00:23:27] Kiểu giống như kiểu mình
[00:23:30] đang học song song cả PP cả Java không
[00:23:33] đúng. Nâng cấp tư duy backend qua 100
[00:23:37] ngày học cũng được. Đào sâu về thứ thứ.
[00:23:51] tư duy backend qua 100 ngày học Java đảo
[00:23:54] sâu về Clean Architect OP và các bài
[00:23:57] toán thiết kế tối ưu hệ thống từ góc
[00:23:59] nhìn của một lập trình viên PP được
[00:24:02] không hề nhấn mạnh việc là mình là người
[00:24:04] có kinh nghiệm rồi mình là lâu năm nơi
[00:24:09] nơi đây chúng ta vân vân vân không chỉ
[00:24:11] nói đi thẳng vào trọng tâm đúng không là
[00:24:15] mình nâng cấp dùng từ nâng cấp rất là
[00:24:17] hay vì nó ngang với từ mà tôi thích nó
[00:24:20] đừ develop mình là developer đúng nhiều
[00:24:25] người dịch lập trình viên nhưng thực ra
[00:24:27] là develop là kiểu phát triển nâng tầm
[00:24:30] nó lên đúng không nâng cấp nó lên đấy
[00:24:33] nâng cấp vốn những cái đang có sẵn nghĩa
[00:24:35] là mình không vẽ lại bánh xe đúng không
[00:24:37] ạ mình thực ra là mình có thể đi code
[00:24:39] người khác cũng được không sao mình sẽ
[00:24:42] dựa vào những cái người ta đã từng cái
[00:24:44] trò phát minh hơi vĩ đại đi từ hơi giật
[00:24:47] đau to bối lớn tí nhưng đại khái người
[00:24:48] ta viết ra những cái đoạn đấy
[00:24:50] mình tái sử dụng lại để mình làm ra được
[00:24:53] những cái sản phẩm khác giá trị hơn, tốt
[00:24:56] hơn thì đấy là gọi phiên bản nâng cấp
[00:24:58] hơn đúng không? Đấy thì từ nâng cấp này
[00:25:01] rất là hay. Được tôi sẽ tham khảo cái từ
[00:25:03] này.
[00:25:05] Đấy đây nó sẽ trả lời cho cái câu của
[00:25:07] bạn vừa nãy hỏi. Em lần đầu xem cố anh
[00:25:10] học Java theo hướng nào vậy ạ? Thì nó sẽ
[00:25:12] theo hướng này em nhá.
[00:25:14] Đấy mình sẽ sửa lại. À
[00:25:28] Ok.
[00:25:31] Chào các bạn.
[00:25:33] Đợi tôi tí, tôi đang ngồi chỉnh cái mấy
[00:25:35] cái này. Thực ra là mấy ông sẽ thấy là
[00:25:38] kiểu ông ấy bị sao ấy, kiểu lúc
[00:25:41] livestream thì đáng lẽ phải tập trung
[00:25:42] vào dậy hoặc tập trung làm cái gì đó lại
[00:25:45] đi ngồi à kiểu làm cái khác. Như thực ra
[00:25:49] là tôi cũng không có nhiều thời gian làm
[00:25:52] những cái khác kiểu c thử nên thành
[00:25:55] trong lúc mà tôi livestream này tôi sẽ
[00:25:57] tranh thủ làm thêm một cái gì đó nữa nên
[00:26:00] mong mấy ông thông cảm.
[00:26:02] rất mong về ông thông cảm đúng không ạ?
[00:26:07] Ok.
[00:26:21] khóa học này mấy ông không biết mấy ông
[00:26:23] thấy chưa?
[00:26:43] cái câu thực ra là có nhiều cái bài rất
[00:26:46] là dài thì không phải bài nào tôi cũng
[00:26:48] đọc hết đâu. Tôi không phải là người
[00:26:51] ờ tôi vốn từng là một người rất là kiểu
[00:26:54] mọt sách, mọt game mình thích chơi game,
[00:26:56] mình đi đọc sách. Nhưng mà không phải là
[00:26:59] cái gì rất dài, tôi cũng đọc. Ví dụ là
[00:27:01] tôi không đọc chuyện chữ nhiều hay vân
[00:27:02] vân. Nhưng mà bài này tôi thể ấn tượng
[00:27:05] ngay. Cái đầu tiên nó nhắc đến WeChat.
[00:27:08] Tôi luôn khâm phục cái cái ứng dụng
[00:27:10] Weat. Nếu các bạn không biết thì nó là
[00:27:14] tính như là một cái gọi là siêu ứng dụng
[00:27:17] là một Super App đúng không? Tức là sao?
[00:27:21] Nghĩa là một cái ứng dụng nó chứa rất
[00:27:23] nhiều cái ứng dụng khác ở trong này.
[00:27:26] Thì ở đây chứa nhiều ứng dụng khác là
[00:27:30] như thế nào?
[00:27:32] Tí tại sao ở đây nó không hiển thị là
[00:27:35] đang có bao nhiêu người xem nhỉ? Tôi bị
[00:27:37] lỗi ở đâu?
[00:27:53] thì rõ ràng là ứng dụng Wechat nó tích
[00:27:56] hợp rất nhiều và đã có rất nhiều cái a
[00:28:00] ứng dụng khác của Việt Nam cũng cố từng
[00:28:02] làm tương tự. Ví dụ là hồi trước là Zalo
[00:28:05] này à không tôi thấy thằng đầu tiên thì
[00:28:08] sẽ là Momo à nếu bây giờ nó vẫn cố làm
[00:28:10] tức là sao nó gộp hết trong đấy từ việc
[00:28:13] là lúc nào chỉ ví điện tử đúng không ạ
[00:28:15] sau về sau tích hợp thêm là thanh toán
[00:28:17] những cái thứ khác ngay trên chính nền
[00:28:19] tảng của nó mua mọi thứ trên chính nền
[00:28:22] tảng của nó xong rồi biến hành gần như
[00:28:24] là mạng xã hội cũng có nhá bởi vì bởi vì
[00:28:28] mấy ông sẽ không nghĩ nó là mạng xã hội
[00:28:29] nhưng mà mạng xã hội nó sẽ chỉ đơn giản
[00:28:31] là bao gồm có nhắn tin có nhân được,
[00:28:34] bình luận có bình luận được có đăng bài
[00:28:37] đăng bài được kết nối với mọi người với
[00:28:39] nhau có thì rõ ràng nó tính của mạng xã
[00:28:41] hội rồi đấy thì rõ ràng là có. Bình luận
[00:28:44] ở đây sẽ là bình luận ở ch những cái bài
[00:28:46] đăng ở khi mà mấy ông a tôi thấy là đa
[00:28:50] số ấy thì sẽ là ở mấy cái bên a đầu tư
[00:28:54] ấy. Tôi mua chứng chứng khoán hay chứng
[00:28:58] chứng chỉ quỹ lên đấy thì sẽ có đăng bài
[00:29:00] trên đấy nhiều. và mọi người bình luận
[00:29:02] trong đấy nhiều hoặc là thực ra có mấy
[00:29:04] trò chơi của nó cũng có mấy cái đấy. Đấy
[00:29:06] thì siêu ứng dụng ở trên đấy người lag
[00:29:08] vãi chưởng. Tôi tôi dùng Android thì ok
[00:29:11] có thể bảo tôi là Android đều nên chính
[00:29:14] là nó lag nhưng mà tôi
[00:29:16] nghĩ là một cái siêu ứng dụng nó không
[00:29:18] phải là
[00:29:21] à không anh đang muốn à không phải mỗi
[00:29:25] chỉ ngồi học muốn chia sẻ thêm gì đó thì
[00:29:28] anh tranh thủ ngồi nhắc về cái bài hôm
[00:29:31] trước anh đọc tản mạn về chatvity ở đây
[00:29:34] thì ở đây đang nhắc đến Weat thì tranh
[00:29:36] thủ đấy anh sẽ nói về Momo à thư thực ra
[00:29:39] là
[00:29:40] cũng hạn chế chê về một cái ứng dụng
[00:29:44] Việt đúng không? Mình là người Việt
[00:29:46] không biết sợ bị đánh vần quyền hay sợ
[00:29:47] gì đó khác không nhưng mà thực sự không
[00:29:50] phải chê nữa. Mình đang nói thẳng luôn.
[00:29:52] Tôi đã từng gửi cá nhân tôi nhá. Tôi là
[00:29:56] một người rất hay gửi phản hồi để góp ý
[00:30:02] để mà khuyên các thứ các thứ. Cho dù là
[00:30:04] đúng có thể họ code tốt hơn mình hay mọi
[00:30:07] thứ. Họ làm mọi thứ kiểu chắc chắn là có
[00:30:10] thể chuyên nghiệp hơn. Nhưng mình là
[00:30:13] người dùng mà mình vẫn có quyền được
[00:30:16] kiểu góp ý các thứ các thứ chứ mình
[00:30:17] không phải là kiểu dìm người ta theo
[00:30:19] kiểu là người ta làm tốt mình vẫn cố dìm
[00:30:24] mình cố m moi ra để tìm không nên tôi đã
[00:30:27] nói là kiểu nó có khá nhiều vấn đề.
[00:30:38] không? Ý em là con AI á. Con AI thì anh
[00:30:41] có set a ru có. Còn con chat DVT á chat
[00:30:47] DVT thì anh chẳng có RU gì cả. À hồi
[00:30:49] trước là anh có để cái ru là
[00:30:52] đừng có nịnh hot nhiều quá.
[00:30:55] Cái đấy cũng có thể tính là một cái ru.
[00:31:05] anh có dùng cái bộ kit để soạn Ra xong
[00:31:08] rồi cũng bảo nó tự chỉnh lại để phù hợp
[00:31:12] custom lại để phù hợp với cái project.
[00:31:15] Bởi vì mỗi dự án, mỗi project thì nó sẽ
[00:31:18] kiểu khác nhau đúng không? Ví dụ là mình
[00:31:22] dự án ở trên công ty của tôi là TP thì
[00:31:25] sẽ ru sẽ kiểu khác hoặc là à dự án về
[00:31:29] FEN thì sẽ ru kiểu khác.
[00:31:39] là kiểu kit mà tức là nó tổng hợp của
[00:31:42] rất nhiều cái thôi. Em vẫn phải dùng ai
[00:31:45] một lần nữa bảo nó đọc cái đống đấy rồi
[00:31:48] bảo nó tự sửa lại đống đấy. Anh làm mấy
[00:31:50] lần rồi và nó sửa lại để cho nó phù hợp
[00:31:53] chứ không thì em ôm vào them vẫn dùng
[00:31:56] được nhưng mà nó sẽ kiểu bị chung chung
[00:31:58] ấy. Bởi vì n em thích em mở hẳn file đấy
[00:32:01] mà đọc vì file đấy bản chất là nó chỉ là
[00:32:03] file maxdown, file tex cơ mà. Thì mình
[00:32:05] đọc thì em sẽ hình dung được cái mục
[00:32:09] đích của nó là gì. Nó cũng chỉ đôi khi
[00:32:12] là người ta bảo ru hay là workflow hay
[00:32:15] tất cả những thứ khác. bản chất nó chỉ
[00:32:16] là những câu prom kiểu nó chạy ngầm để
[00:32:20] cho mấy cái thằng kia gọi là thay vì em
[00:32:22] viết một câu prom quá dài quá chi tiết
[00:32:24] thì bây giờ có một cái ru ở kiểu quy
[00:32:27] định là mày phải mình mày phải làm từng
[00:32:30] bước từng bước như thế này thế chẳng qua
[00:32:33] nó viết prom mẫu sẵn một cái template
[00:32:35] cho mình trước thôi. Đấy nghĩa là mỗi
[00:32:37] khi mà em chạy prom bình thường của em
[00:32:39] nó sẽ đọc qua cái ru này nữa. gọi là
[00:32:43] chèn thêm cái đoạn prom đấy vào để mà ra
[00:32:47] được một đáp án thôi. Đấy thì rõ ràng là
[00:32:53] prom của em mà đủ chất rồi thực ra em
[00:32:54] không cần ru lắm mà đôi khi nó còn tốn
[00:32:58] token cái việc là nó mà ru mà chung
[00:33:01] chung thì giống như các em viết một câu
[00:33:02] prom chung chung ấy thì nó sẽ không ra
[00:33:04] được kết quả đúng không? Đấy thì kiểu gì
[00:33:06] em cũng phải sửa lại cái ru mà nếu mà
[00:33:09] không biết sửa tốt nhận không nên dùng
[00:33:11] thế thôi.
[00:33:17] rất là hay. Nó nó nếu mà hiểu như một
[00:33:22] cái ứng dụng nhắn tin thì nó sai. Nó là
[00:33:24] hạ tầng.
[00:33:26] dùng từ hạ tầng này một từ rất là hay
[00:33:28] này. Và cái quan trọng là người dịch này
[00:33:31] rất là hay bởi vì nếu mà giả sử mà
[00:33:35] tôi chưa xem bằng tiếng Anh nhá nhưng mà
[00:33:37] nếu mà dịch đôi khi là nó không dịch ở
[00:33:39] hạ tầng hay là dịch một cái từ gì khác
[00:33:42] thì có khi là nó không phản ánh rõ được
[00:33:44] đúng ý của tác giả. Đấy tôi thấy từ hạ
[00:33:48] tầng có một từ rất là hay.
[00:33:51] Đây khi một mua một điện chiếc điện
[00:33:53] thoại mới ứng dụng đầu tiên cài không
[00:33:56] phải là Facebook, không phải là Chrome
[00:33:58] mà là Rechat. Bạn không cần cài thêm app
[00:34:01] nào khác để sống bình thường.
[00:34:04] Chắc là bè làm việc, trả tiền, đặt đồ
[00:34:06] ăn.
[00:34:08] Tất cả
[00:34:10] đều nằm trong Wehat
[00:34:12] thông qua một thứ gọi là mini program.
[00:34:15] Thực ra vừa rồi vừa rồi tôi vừa thấy à
[00:34:18] anh
[00:34:20] Dương Dê à đúng không nhở?
[00:34:24] Hình như thế anh reviewer ấy, anh ấy
[00:34:26] cũng vừa chia sẻ là cái à ứng dụng VN
[00:34:31] VNID
[00:34:32] mới tích hợp thêm a check in online. Tôi
[00:34:35] cảm thấy là ừ có vẻ mọi người đang hướng
[00:34:38] đến việc cái app đấy nó sẽ thành kiểu
[00:34:41] Nana DQ chat tức là Super App một cái
[00:34:44] siêu ứng dụng đúng không? Bởi vì là thấy
[00:34:47] là tích hợp trên đấy ngoài tích hợp giấy
[00:34:49] tờ xong rồi nói chung là làm liên quan
[00:34:52] hành chính thì bây giờ bắt đầu chuyển
[00:34:54] qua là mấy cái kiểu là nó vẫn có tí liên
[00:34:58] quan đến hành chính, liên quan đến thủ
[00:35:00] tục các thứ như vậy về sau sẽ bao gồm
[00:35:03] kiểu là
[00:35:06] tôi nghĩ là về sau nó sẽ kiểu gì sẽ gần
[00:35:09] như là mình sẽ chỉ có cùng lắm là mình
[00:35:10] sẽ chỉ vài app ví dụ nhá à tôi để ý gần
[00:35:14] đây viện app xanh chẳng hạn
[00:35:17] Hợp xanh của Vin đúng không? Đấy tôi
[00:35:19] thấy có rất nhiều cái trong đấy rồi. Hồi
[00:35:22] trước là còn tách ra tách hắn cái riêng
[00:35:25] ra. Ví dụ là xanh phải đặt đồ ăn à không
[00:35:30] hồi đấy không biết tách đặt đồ ăn chưa
[00:35:32] nhưng mà xanh hồi trước là xanh chỉ là
[00:35:35] xanh những cái dịch vụ liên quan đến
[00:35:37] xanh thôi nhưng mà bây giờ còn có cả
[00:35:40] tích hợp xanh bên Cần Đệ cũng tích hợp.
[00:35:42] Nếu mấy các bạn không biết thì nó có
[00:35:44] tích hợp luôn cả cái Vinm đấy. Không
[00:35:48] biết tôi không có con, chưa có con không
[00:35:51] biết là vì sau tích hợp school hay mọi
[00:35:53] thứ trong đấy không. Đấy thì mới là nó
[00:35:56] tích hợp dần dần dần dần trong một cái
[00:35:58] app chung.
[00:36:00] Và ít ra là con Vinid tuy là bị có bị
[00:36:04] chê việc là đăng nhập vào thỉnh thoảng
[00:36:06] có lá
[00:36:08] theo kiểu là khó đăng nhập vào ấy chứ
[00:36:10] còn đăng nhập vào trong đấy được rồi ấ
[00:36:12] thì tôi sẽ dùng mọi mọi cái thứ ít nhất
[00:36:15] là mượt nhưng mà vẫn còn ứng dụng của à
[00:36:20] nó vẫn là sơ xài, nghĩa là vẫn phải điền
[00:36:23] thủ công nhiều cái
[00:36:25] và cái việc không thể hiện người dùng
[00:36:28] nữa đó
[00:36:34] chưa thân thiện nhưng mà ý ra là nó
[00:36:37] không lag còn ứng dụng lag như tôi vừa
[00:36:40] nãy nói nó nhà mờ ấy lag quên J2 thực ra
[00:36:44] cũng gọi là một cái nhóm mọi người
[00:36:47] thường hay bảo là đấy nhóm anti của app
[00:36:50] M với app Z đúng không
[00:36:54] cả hai app cũng đều hướng đến Super App
[00:36:56] nhưng tôi cảm thấy là đều khá là tệ
[00:37:03] mà vì ngữ cảnh xã hội. Người dùng không
[00:37:08] tìm kiếm cái app, không kiểu phát hiện
[00:37:11] ra đi, tìm ra đi qua store hay toán. Họ
[00:37:15] được bạn bè chia sẻ trực tiếp với nhau
[00:37:18] trong nhóm chat, nơi đã có sẵn niềm tin.
[00:37:21] Đấy, thậm chí còn trống.
[00:37:24] Đây cái này thêm một cái rất là hay này.
[00:37:26] Chống recommend mọi người thường hay
[00:37:29] dùng từ recommend. Tôi ghét từ này nó sẽ
[00:37:32] là chống kiểu giới thiệu chống kiểu
[00:37:34] khuyên dùng đúng không? Đấy bình thường
[00:37:36] mình sẽ hiển thị lên cái mục là mục là
[00:37:39] những ứng dụng bạn có thể sẽ thích đấy.
[00:37:42] Mục khuyên dùng hay vân vân vân gì đấy.
[00:37:45] Ông này còn bảo thậm chí bài trừ cái đấy
[00:37:47] tôi thấy rất là hay.
[00:37:49] kiểu nó đi ngược ấy. Đấy bảo là
[00:37:55] đây
[00:37:57] cái việc à
[00:38:03] con đường ngắn nhất, tốt hơn bất kỳ
[00:38:05] thuật toán nào. Thay vì mình cứ hiển thị
[00:38:07] ra một đống kiểu khuyên dùng vào đấy.
[00:38:09] Mọi người cảm thấy dối và mọi người còn
[00:38:11] bắt đầu nghi ngờ về nó. Thì đôi khi mọi
[00:38:13] người bây giờ cảm thấy là nó giống như
[00:38:14] là được mua ấy, kiểu bởi vì mấy cái
[00:38:17] khuyên dùng ấy đôi khi là được trả tiền
[00:38:19] để được lên đấy mà nên thành ra là nó bị
[00:38:22] kiểu giả ấy. Mọi người bây giờ không
[00:38:24] quan tâm đâu. Mọi người bị dị kiểu
[00:38:28] cứ cho là kiểu kỳ thị ngầm. À từ đúng nó
[00:38:32] là gì nhở?
[00:38:35] Mọi người bị à à
[00:38:39] b trừ à không đúng.
[00:38:42] Mọi người bị ác cảm. Đúng rồi. Bị
[00:38:43] [tiếng cười] ác cả mấy cái kiểu
[00:38:46] khuyên dùng đấy. Đặc biệt là cứ có gắn
[00:38:49] chữ là đã được tài trợ, đã được quảng
[00:38:51] cáo thôi. Xem bởi vì rõ ràng lúc đấy nó
[00:38:54] họ sẽ nghĩ ngay luôn là mình là
[00:38:58] mình đang được mua bán, mình đang được
[00:39:00] trao đổi, mình đang được mời hàng mình
[00:39:02] không thích kiểu đấy. Mình thích thực sự
[00:39:04] là một cái ứng dụng mọi người khuyên
[00:39:07] dùng nó đủ tốt chứ không phải là thằng
[00:39:09] thằng này trả tiền để được kiểu gợi ý
[00:39:12] cho mình.
[00:39:16] nhân hóa thì càng tốt nữa đúng không?
[00:39:20] Và quay lại Open AI.
[00:39:23] Open AI gần đây tung ra những cái gọi là
[00:39:26] app nằm trong trình cái Open AI. Đấy.
[00:39:37] nó khác nó không khác gì với Meta hay
[00:39:40] Google trước đây. Đấy. Open AI không có
[00:39:44] mối quan hệ giữa người với người mà chỉ
[00:39:46] người với công cụ đúng không ạ?
[00:39:53] chat thì kéo được cả hệ sinh thái vào
[00:39:55] trong vì nó là nghĩ ra người với người
[00:39:58] với nhau. Còn chapit chỉ có người với ai
[00:40:02] đấy.
[00:40:11] gần đây là chatt còn bắt đầu có thể sẽ
[00:40:15] kiểu nhúng cả quảng cáo ở trong này.
[00:40:18] Thậm chí ở phía sau là nó là kiểu quảng
[00:40:20] cáo, kiểu nó gợi ý là các bạn sản phẩm
[00:40:23] hay các thứ thứ như nào vân vân. Thì rõ
[00:40:25] ràng là tôi thấy là nó sẽ
[00:40:29] có thể người dùng sẽ e chừng nó hơn khi
[00:40:34] mà thấy nó hiểu mình quá và gợi ý những
[00:40:36] cái thứ. Cứ cho là tốn tiền đi đúng
[00:40:39] không? Đấy mình sẽ hơi sợ nó. Lúc đầu
[00:40:42] đang nói chuyện này thì mình thấy hay
[00:40:43] mình cảm thấy là ừ nó đang cá nhân hóa
[00:40:46] tốt nó đang đồng cảm với mình. Mình
[00:40:47] thích nó nghe nó chứ về sau lại cảm thấy
[00:40:50] nó có cái gì đang thao túng mình thì
[00:40:52] mình sẽ không thích nó nữa. Mình sẽ có
[00:40:54] tí kìa dè chừng hơn.
[00:41:12] tại. Phải học cách nói chuyện với nó.
[00:41:14] Phải đoán xem prom thế nào cho đúng.
[00:41:16] phải chỉnh câu chữ chỉnh đi này lại. Đôi
[00:41:18] khi kết quả đúng nhưng mất quá nhiều
[00:41:20] công sức thì tới đó. Cái này thì tôi
[00:41:23] không chắc lắm. Tôi không nghĩ ở việc là
[00:41:26] nói chuyện với một con AI ít nhất là về
[00:41:29] chatt còn những thả khác thì tôi cảm
[00:41:32] thấy vẫn hơi ức chế thật.
[00:41:35] Thì tôi thấy là không khó để mà nói
[00:41:37] chuyện với nó. Mấy ông thấy không? Mấy
[00:41:40] ông có thấy khó khi nói chuyện với CHVT
[00:41:42] không? Cảm thấy không? Dễ mà. Tôi thấy
[00:41:46] khó hơn nếu mà cùng cái câu đấy nói với
[00:41:49] thằng Gemini thì tôi không chắc
[00:41:56] số đông đúng không? Mình đôi khi là mình
[00:41:59] à ra lệnh hồi đầu nói chuyện thì mình sẽ
[00:42:03] không biết ra lệnh, mình không viết viết
[00:42:05] khái niệm prom n tôi nghĩ là về sau đủ
[00:42:09] tốt. Kiểu bây giờ nói thẳng luôn là bây
[00:42:13] giờ khi mà mình đang nói chuyện hàng
[00:42:15] ngày với nó, nó vẫn đang học từ mình nên
[00:42:17] thành ra là về sau nó sẽ dần dần là
[00:42:19] chúng ta sẽ không cần phải prom chuyên
[00:42:21] nghiệp nữa. nó vẫn hiểu được tất cả mọi
[00:42:24] người đang nói chuyện theo phong cách
[00:42:25] như thế nào và mọi người nói này bản
[00:42:29] chất là mọi người đang muốn gì đấy kiểu
[00:42:31] thế lúc đấy không cần prom quá xịn nữa
[00:42:33] cũng được thế nên là cái thời gian đầu
[00:42:36] ấy thời gian đầu ấy ai mới nổ mình không
[00:42:39] biết có ngành nghề gì hot không là ngành
[00:42:41] nghề này bây giờ vẫn hot à không
[00:42:45] lúc thời gian đầu là có tận hai ngành
[00:42:47] hot cơ còn bây giờ chỉ có một ngày hot
[00:42:48] thôi nhá thời gian đầu có một ngành hot
[00:42:51] đó ngành ngành là ngành prom
[00:42:55] nghĩa là hướng dẫn các bạn ạ prom sao
[00:42:58] cho chuột và
[00:43:06] được cái prom các bạn nhập vào. Còn bây
[00:43:08] giờ thì sẽ chỉ còn một ngành hot thôi.
[00:43:11] Đó là ngành kiểu vẫn hướng dẫn các bạn
[00:43:13] dùng AI nhưng không thiên về việc là mỗi
[00:43:16] prom chuẩn nữa. Đương nhiên là có có
[00:43:18] nhắc đến prom chuẩn nhá nhưng mà sẽ nhắc
[00:43:21] nhiều việc là AI có thể làm được gì và
[00:43:24] các bạn nên dùng AI mọi thứ vân vân như
[00:43:26] thế nào đấy có bây giờ gần đây đẻ thêm
[00:43:29] cái vụ skin các thứ thứ kia nữa thôi
[00:43:31] đúng không như skin đấy cả prom thôi đấy
[00:43:36] nhưng mà còn cái người viết prom để mà
[00:43:39] trên change cho ai nó thực sự là vốn là
[00:43:42] công công việc lâu rồi chứ không phải
[00:43:43] gần đây mới nổi nữa gần đây là chẳng qua
[00:43:46] ai nó phụ phổ biến nên nên là mọi người
[00:43:49] cảm thấy là muốn kiểu phomo đi. Cứ cho
[00:43:51] vào mọi người bị kiểu sợ là mình sẽ bị
[00:43:54] thậu, sợ mình bị lỗi thời nên là mình sẽ
[00:43:56] phải học một cái gì đó phải biết viết
[00:43:59] prom chuẩn. Không theo mình nghĩ là một
[00:44:03] con LL
[00:44:04] LM bây giờ đã học được nhiều và đủ mạnh
[00:44:07] để mà các bạn viết prom bình thường cũng
[00:44:10] hiểu được. Còn nếu mà viết prom bình
[00:44:12] thường mà không hiểu được, nói chuyện
[00:44:14] bình thường mà không hiểu được thì chỉ
[00:44:15] đơn giản là con AI đều. Nên là hôm trước
[00:44:18] có người bảo với tôi là kìa ông chưa đủ,
[00:44:22] chắc là ông chưa đủ trình để nói chuyện
[00:44:23] với con Jamin rồi. Tôi cảm thấy kìa. Tại
[00:44:27] sao bây giờ nói chuyện
[00:44:30] với một con AI thông minh
[00:44:34] thì người dùng thực ra không cần thông
[00:44:35] minh lắm. Còn nếu mà mình phải rất thông
[00:44:39] minh để nói chuyện với nó thì chứng tỏ
[00:44:41] là con đấy đang có vấn đề. Ông hiểu gì
[00:44:45] tôi không?
[00:44:47] Bởi vì đúng là nếu phải người thông minh
[00:44:50] thì nên mới nói chuyện được người thông
[00:44:52] minh đúng không? Nhưng mà nếu nó cực kỳ
[00:44:54] thông minh ấy và EQ nu đủ cao, ví dụ giả
[00:44:57] sử ông nói chuyện ngoài đời đi thế là dễ
[00:45:00] hiểu hơn nhá.
[00:45:02] Ông có thể nghĩ là tôi không đủ thông
[00:45:04] binh để nói chuyện với ông. Vì vì ông
[00:45:07] rất thông minh. Đấy chẳng hạn. Thế nhưng
[00:45:10] mà nếu thế ông nói thế chỉ đang nói so
[00:45:12] sánh về IQ đấy. Còn nếu về EQ giả sử ông
[00:45:17] đủ thông minh và EQ ông đủ cao ấy thì
[00:45:20] ông nói chuyện với bất kỳ ai cũng được.
[00:45:22] Đấy những người EQ cao thì người ta lại
[00:45:24] nói chuyện được với bất kỳ ai. Kể cả dù
[00:45:26] người ta nói chuyện với người EQ hay
[00:45:29] thấp hơn mình họ vẫn nói chuyện được.
[00:45:31] Đấy thì tức là sao? Nghĩa là nó liên
[00:45:33] quan việc là thông minh ở đấy dựa trên
[00:45:35] yếu tố nào. Nếu mà giả sử là thông minh
[00:45:38] chỉ nói chuyện được với người thông minh
[00:45:39] ấy thì thì con AI kia nó không phù hợp
[00:45:44] cho số đông. Đấy. Còn nếu mà AI đã muốn
[00:45:47] làm AI phổ thông thì rõ ràng phải ai
[00:45:50] cũng có thể ra lệnh nó, ai cũng có thể
[00:45:52] nói chuyện được với nó.
[00:45:54] Đấy có thể nói chuyện giả sử là người
[00:45:57] không thông minh thì nói chuyện với nó
[00:45:58] ra prom nó không chuẩn. Ok, nó có thể ra
[00:46:00] đáp án không chuẩn nhưng nghĩ ra nó vẫn
[00:46:02] nói chuyện được nhá. Còn đây mà kiểu
[00:46:05] mình ra prom cho nó xong rồi nó lại trả
[00:46:08] lời hoàn toàn khác hoặc nó có thể thậm
[00:46:10] chí bảo lại là mày phải viết prom chuẩn
[00:46:11] hơn hay gì gì đó thì tự nhiên là khiến
[00:46:14] người dùng phải suy nghĩ. Và là một trền
[00:46:17] lập trình viên tôi vẫn nhớ cái câu đó là
[00:46:19] một ứng dụng mà khiến người dùng phải
[00:46:21] nghĩ để sử dụng. Thì đây là ứng dụng tồi
[00:46:25] đấy.
[00:46:27] Mình phải làm ứng dụng sao cho mà
[00:46:30] gọi là người dùng càng bớt nghĩ thì túi
[00:46:33] tiền của mình càng dùng rỉnh. À tôi nhớ
[00:46:35] cái câu đại ý nó ở đấy. Tôi không nhớ
[00:46:38] câu ấy chính xác là gì.
[00:46:46] này app inap là đóng gói intem bắt người
[00:46:49] dùng diễn đạt
[00:47:00] khả năng sử dụng thực tế trong es cụ thể
[00:47:10] cập vào một động cơ rất mạnh nhưng không
[00:47:12] vô lăng, không bảng điều khiển. App
[00:47:14] chính là UI API cho hệ thống đó. đều đặc
[00:47:17] biệt. Nếu
[00:47:20] tôi hiểu đoạn này của bạn ấy nói của à
[00:47:23] không phải bạn đấy của ông ông ấy nói
[00:47:28] đây giống như vừa nãy tôi nói prom kém
[00:47:30] output kém người dùng nghĩ AI sâu đúng
[00:47:34] nó không phải chúng ta không thể khen AI
[00:47:37] thông minh thế nào nhưng mà rõ ràng là
[00:47:39] AI có đủ thông minh để hiểu mình đâu thì
[00:47:41] rõ ràng đây vẫn là một AI tồi thôi ai
[00:47:43] sinh ra được phục vụ mình chứ không phải
[00:47:44] là mình đi AI sinh ra rồi mình còn phải
[00:47:47] cố hiểu nó để mà đáp ứng được nhu cầu
[00:47:49] của mình.
[00:47:51] Đương nhiên là ông nào mà càng hiểu được
[00:47:53] AI, cơ chế hoạt động AI và càng biết tận
[00:47:56] dụng AI như thế nào để tốt cho cuộc sống
[00:48:00] hay tốt cho công việc thì đúng thế là
[00:48:02] rất là tốt.
[00:48:04] Như tôi đang nói là cái AI mà muốn phổ
[00:48:06] thông muốn chung thì đó rằng là AI đấy
[00:48:09] phải làm cho mà mọi người dùng từ tất cả
[00:48:13] thì nó hơi khó nhưng chị ạ số đông dùng
[00:48:17] được dùng được nhá không cần ấy dùng một
[00:48:19] cách kiểu quá xịn nhá
[00:48:24] bây giờ thì mọi người đang thiên hướng
[00:48:26] là muốn dùng AI rất là xịn cơ
[00:48:29] bao người muốn vai code này muốn làm ra
[00:48:32] ứng dụng các thứ thứ hôm trước Rất nhiều
[00:48:34] người đăng bài hỏi ra là kìa em mới học
[00:48:37] em dùng AI để có thể làm ra được trong
[00:48:40] web không?
[00:48:52] khác mất rồi.
[00:48:54] Ok, chắc là ông này bàn sâu một tí về kỹ
[00:48:57] thuật mình. Cái cái trên thì đang rất là
[00:49:01] hay, đang rất là trều tượng. Ok. Tôi
[00:49:02] thấy sâu về kỹ thuật này tôi cảm thấy
[00:49:05] thôi bỏ qua. Ok. Đợi tôi tí tôi đóng cái
[00:49:10] máy giặt cho đỡ ôn à.
[00:49:33] tự nhiên vừa rồi chưa học mình đã nói
[00:49:36] chuyện tận 50 phút mà tôi lại nhớ đến
[00:49:39] cái phim hôm qua tôi vừa xem nữa. Phim
[00:49:41] hôm qua tôi vừa xem nó về trinh thám
[00:49:44] nhưng mà nó nói rất nhiều phải đến
[00:49:49] cứ cho một nửa bộ phim.
[00:49:51] là nói và hùng hùng điện nhiều đấy. Có
[00:49:57] khi tôi bị lây mất rồi.
[00:50:00] Thông cảm
[00:50:02] thôi mình sẽ quay lại học đi.
[00:50:05] Hôm nay thực ra hôm nay tôi cũng chưa
[00:50:07] biết được mình sẽ học gì đâu. À dựa theo
[00:50:10] bậy tí tôi xem lịch sử đã.
[00:50:20] dựa vào hôm trước
[00:50:23] hôm trước là mình á
[00:50:31] tập thôi.
[00:50:32] Mình sẽ
[00:50:35] sửa vào
[00:50:38] à thật cả mình ghi hết ở trên trước rồi.
[00:50:41] Tôi nghĩ là tôi sẽ chỉnh ngắn gọn là
[00:50:43] soạn cho tôi bài
[00:50:56] nửa Việt mà không sao.
[00:51:05] nói thật ra hôm qua mấy cái bài Hùng
[00:51:08] viện đấy nó bị nặng rất nặng về à kiểu
[00:51:11] có tí mang tiếng ở phim a trinh thám
[00:51:15] nhưng mà nhắc đến cả tôn giáo có đề cập
[00:51:17] cả tôn giáo tín ngưỡng ở trong đấy nên
[00:51:20] phim đấy nó sẽ khá là nặng. May là hôm
[00:51:23] qua tôi không buồn ngủ lắm.
[00:51:25] Hôm nay có hơi hơi hơi một tí buồn ngủ
[00:51:28] vì
[00:51:30] hôm nay đi cả ngày ngủ ít.
[00:51:38] Xem à
[00:51:41] culation enculation.
[00:51:51] Encapsulation. Tôi chưa biết từ này bây
[00:51:54] giờ. Để tôi sẽ
[00:51:57] translate đi.
[00:52:10] &gt;&gt; Encapsulation.
[00:52:19] Ừ tôi sẽ phải nhắt ở đây ru
[00:52:23] à
[00:52:30] một cái file ở đây luôn mấy ông nhỉ à
[00:52:32] đâu chẳng cần mình sẽ tạo
[00:52:36] fileu ở đây luôn cho mấy ông để mấy ông
[00:52:38] biết cách pu nhá
[00:52:41] ờ customize này
[00:52:45] global này cái này là tôi dùng cái
[00:52:48] Contex 7 để mà tự động soạn các thứ các
[00:52:51] thứ.
[00:52:53] Hả? Ô P là sao em?
[00:53:11] Circle đâu. Phim hôm qua nó là cái
[00:53:16] gì nhở?
[00:53:17] Phim qua trinh thám mà nó là phim knife
[00:53:21] Out
[00:53:23] là kẻ đâm lén dịch tiếng Việt ra là thế
[00:53:27] à tên người ta để là thế cái này đặt tên
[00:53:31] Ru là
[00:53:34] Ru cứ đặt tên là Ru thôi nhở đơn giản
[00:53:36] thôi. Đây
[00:53:45] tôi để tiếng Việt ch được không sao
[00:53:48] không tự
[00:53:50] ờ tạo file class
[00:53:55] đây
[00:54:02] cứ tạm thầy thế trước đã tải lại Ơ
[00:54:07] biết rồi mà nhỉ.
[00:54:10] Đây có một agent này.
[00:54:18] file đặt tên như thế này không ổn.
[00:54:25] Dog đi.
[00:54:32] vãi chưởng. Cái này còn không được.
[00:54:44] nhận được trong này đấy.
[00:54:54] xn đâu có ảnh hưởng đâu nhỉ?
[00:55:08] xong rồi tôi phải ấn nút xếp lại nó vào
[00:55:10] đây. Ok thầy có nhiều vấn đề thật.
[00:55:25] Tại hiểu tại sao không nên dùng public
[00:55:27] field. Ừ cái này tôi cũng mường tượng ra
[00:55:30] được.
[00:55:33] Dùng getter setter đúng truy cập private
[00:55:37] default public protect
[00:55:40] default á. Default sẽ là như nào nhỉ?
[00:55:44] Không khai báo mặc định nó sẽ là default
[00:55:46] đúng không? Tôi tôi không khai báo ở
[00:55:49] trong PP tôi toàn thấy nó giống biến
[00:55:52] thành plic. Không biết là nó trong này
[00:55:55] nó sẽ thế không.
[00:56:04] cũng sửa được đúng không? Mình cập nhật
[00:56:06] cái này xong rồi in ra đấy. Lỗi không
[00:56:12] thể truy cập vào đấy các thứ thứ đấy.
[00:56:15] Khai báo cụ thể private m cái gì gì đó
[00:56:18] public là như này đây khởi tạo đúng
[00:56:21] không? có thể get set này không có set
[00:56:27] nếu mà muốn đổi thì phải đi qua một cái
[00:56:30] hàm nào đó đúng không? Đi qua một cái
[00:56:33] method nào đó và trong này nó sẽ có một
[00:56:35] cái gọi là điều kiện cho nó để mình xét
[00:56:39] thô không xét trực tiếp được đúng không?
[00:56:43] từ tiền qua method nào đó rút tiền qua
[00:56:46] mất nào đó có kiểm tra hợp lý hơn đấy
[00:56:50] xong rồi lấy ra thử phá hoại khử gửi
[00:56:53] tiền âm bị chặn
[00:56:56] được
[00:56:58] uầy cái này rất là ngắn gọn nhưng mà nó
[00:57:00] đã thể hiện được phần nào nhưng
[00:57:04] nó không nhắc đến default nhỉ đâu
[00:57:09] default của tôi đâu
[00:57:17] và
[00:57:19] cả nhắc tới
[00:57:22] các mức truy cập nữa.
[00:57:28] nay không? Không, bài hôm nay ngắn thế
[00:57:31] rồi đấy.
[00:57:33] Trăm ngày, mỗi ngày học chục dòng
[00:57:52] tôi cảm thấy mini map này tôi trong dụng
[00:57:54] có để làm gì không?
[00:58:00] mình xóa này đi thì sẽ thành default
[00:58:03] thôi chứ quan trọng là
[00:58:06] default này mặc định là gì? Mặc định nó
[00:58:09] sẽ là public mà đúng không? Hay nó có
[00:58:11] thêm một cái quy ước một cái điều kiện
[00:58:13] nào nữa?
[00:58:24] nó tự động chạy file class
[00:58:32] file class. Thế tớt rồi
[00:58:49] nó vẫn tạo file class.
[00:58:52] Cái cái này tôi nghĩ là cái cái này cái
[00:58:55] dở của trong antiravity.
[00:58:59] Tôi không nghĩ là thằng khác đã bị dính
[00:59:01] cái này. Ít nhất là tôi dùng cái insert
[00:59:02] không bị dính. Đó khi mình ghi ru rồi ấy
[00:59:05] nó sẽ tuân theo cái ru này thật chứ
[00:59:07] không phải là rõ ràng mình để ở đây ru
[00:59:10] mấy ông thấy vừa nãy có set ru đúng
[00:59:12] không chả phải để tiếng anh không nghĩ
[00:59:15] là do tiếng anh tiếng Việt đâu. Bọn này
[00:59:18] đã là AI LM thì nó không phân biệt tiếng
[00:59:22] Anh tiếng Việt. Đây đã để away on rồi
[00:59:25] nhá.
[00:59:35] Không đúng không?
[00:59:49] không?
[00:59:52] Tôi không biết cái này anh em nào trả
[00:59:54] lời cho ông người với.
[00:59:56] Default chỉ trong class này riêng tư
[00:59:58] nhất à đâu private đây chỉ trong pack
[01:00:01] này mặc định nếu không biết gì.
[01:00:05] À bây giờ tôi biết khái niệm default này
[01:00:07] kiểu như này đấy. Pit à kit thì chắc là
[01:00:12] mình cũng chả bao giờ dùng trong cái
[01:00:14] packit nên thành ra là kiểu
[01:00:23] nó trong cái project này đúng không?
[01:00:39] đang hiểu là tạo ra một class nó dạng
[01:00:41] data ấy.
[01:00:48] nhỉ? Đúng không?
[01:01:05] đâ
[01:01:10] mục này đúng không
[01:01:12] thư mục vậc ngoài tính là một cái vit
[01:01:14] đúng
[01:01:28] rồi
[01:01:31] trong packet này class con kế thừa khác.
[01:01:34] Ok
[01:01:36] anh anh có nhớ cái vụ vụ này rồi à? Ừ.
[01:01:40] Hồi trước học Java uầy, phải nhắc lại
[01:01:42] nhớ cái thời học Java thì mới nhớ cái
[01:01:46] mấy cái khái niệm này.
[01:01:58] Truy cập thoải mái.
[01:02:06] thứ truy cập được vì cùng PIT.
[01:02:09] Lỗ ngay né bỏ comment xem
[01:02:39] cũng dễ hiểu. Ok. Thế các bài hôm nay sẽ
[01:02:42] chỉ ngắn này thôi. Không biết mấy ông có
[01:02:44] cảm thấy kiểu cần bổ sung thêm gì thì cứ
[01:02:47] nói nhá.
[01:02:50] Tôi sẽ cập nhật đọc. Cập nhật đâu cho
[01:02:54] tôi
[01:03:10] ra tiếp một bài nữa.
[01:03:13] À không phải một bài nữa mà kiểu một cái
[01:03:15] ảnh nữa. Còn không bài hôm nay sẽ chỉ
[01:03:17] ngắn thế thôi ấy. Ui, mình nói chuyện
[01:03:20] kiểu 50 phút xong rồi học trong 10 phút.
[01:03:30] cái thở ở trên Discord của tôi rồi đúng
[01:03:32] không?
[01:03:38] nhiêu ông vào đấy. Bình luận chat thì ít
[01:03:42] mấy ông vào nhiều thế.
[01:03:46] Đúng rồi, kênh tôi bắt đầu đang đề xuất
[01:03:48] cho người mới là nhiều chứ người cũ có
[01:03:50] vẻ là thế người cũ vẫn xem như nói là
[01:03:53] người cũ vào chat ở đây còn là người mới
[01:03:58] thì chỉ vào đã xem thôi cũng không thấy
[01:04:00] chat mấy.
[01:04:22] hay phết
[01:04:36] kiểu dạng là như cảnh sát sát đúng
[01:04:38] không?
[01:04:40] Hình sát này cầm cái cái này batong à
[01:04:43] không phải baong cái này gọi là gì à cui
[01:04:46] à kiểu cái thế xong rồi lá chắn này bảo
[01:04:49] vệ này u hay nhở lúc nhìn đầu tôi cứ
[01:04:52] tưởng giống như cái khóa cơ nhưng cái
[01:04:54] này chắc là mũ
[01:04:56] được nhỉ
[01:04:58] hacker gán
[01:05:00] này ui cái này dễ hiểu ấy cần thêm cái
[01:05:04] khác không nhỉ
[01:05:12] Cái này cũng hay này. Cái vừa rồi cũng
[01:05:14] hay cơ. Tận hai cái hay chuẩn là nó sẽ
[01:05:17] phải có hai ảnh thì hợp lý
[01:05:21] nhở.
[01:05:23] Không thấy cái vừa rồi hay đúng không?
[01:05:33] cũng không nhìn thấy nữa rồi.
[01:05:52] Đây đây đây cái này này. Đấy
[01:06:00] nào.
[01:06:02] Cái này cũng hay
[01:06:05] nhắc đến bảo vệ có cái này nhắc đến tính
[01:06:08] đóng gói
[01:06:11] rất hợp lý mà đúng không?
[01:06:42] để có hai ảnh được.
[01:06:51] ấn nhầm rồi lại chưa? Hình như là bấm
[01:06:54] này nó vẫn ra được cái cũ phải.
[01:06:57] Đây đây đây.
[01:07:33] để cả hai nhá. Ừ.
[01:07:41] sẽ a
[01:07:52] bngngng.
[01:08:07] Chúng ta sẽ có rất nhiều ảnh để dễ hình
[01:08:08] dung. Ui
[01:08:11] cái chữ màu trắng thì phải không nhìn
[01:08:15] được cái gì cả.
[01:08:16] Xem à
[01:08:28] này thôi.
[01:08:30] Ok.
[01:08:33] Hôm nay không thì sẽ chỉ học đến thế này
[01:08:35] thôi đấy. Mấy ông sẽ thấy là ừ nó có thể
[01:08:37] rất là ngắn nhưng mà tôi sẽ không dạy à
[01:08:40] tôi không học quá nhiều trong một ngày
[01:08:41] đâu. Kiểu mỗi ngày sẽ chỉ tí một tí một
[01:08:45] như này. Mà cái này tính a ngắn mà đúng
[01:08:47] không? hay là chắc là do tôi dùng cái
[01:08:51] con AI tạo ra 100 ngày nó hơi bị kiểu
[01:08:54] nhiều kiểu nó dài dàn trải quá nên thành
[01:08:56] ra là kiểu ngày 7 chắc là người ta chỉ
[01:08:59] cho ngần này kiến thức thôi tôi không
[01:09:01] biết
[01:09:08] tổng hợp
[01:09:11] ừ tổng hợp kiến thức
[01:09:20] 6 đây đây 6 ngày đi.
[01:09:24] À đây có cho chuyên nghiệp nhỉ? À không
[01:09:26] nhưng mà mình để trong a playlist là
[01:09:29] ngày rồi. 6 ngày đã học.
[01:09:32] Ok.
[01:09:35] Cái này mình sẽ đặt tên là
[01:09:38] bình thường sẽ để code lên kiểu như này
[01:09:40] này.
[01:09:46] đây. Bó
[01:09:53] ừ thật ra là cái này chẳng có gì thắc
[01:09:55] mắc cả.
[01:09:57] Không sao, có gì mình sẽ nói chuyện vào
[01:10:01] ngày mai khi mà có thêm nhiều thứ thắc
[01:10:04] mắc hoặc là giải đáp thêm sau. Còn không
[01:10:07] thì chào mấy ông nhá. Một ngày học một
[01:10:09] tiếng thôi. Xin chào mấy ông nhá. Vai
