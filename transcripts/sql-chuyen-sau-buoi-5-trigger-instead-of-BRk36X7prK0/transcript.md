# SQL chuyên sâu - Buổi 5 - Trigger (Instead of)

- Video ID: `BRk36X7prK0`
- URL: https://www.youtube.com/watch?v=BRk36X7prK0
- Published: 2021-11-04
- Duration: 1h 31m 57s (5517s)
- Language: vi
- Subtitle source: auto
- Kind: live

## Transcript

[00:00:00] ừ ừ
[00:00:06] à à Xin
[00:00:21] chào các bạn
[00:00:27] hôm nay ăn sớm tí không biết các bạn không nóng lắm à
[00:00:37] à à
[00:00:40] anh xin Có phải bạn từ vẫn bận lúc cậu thỉnh thoảng các bạn mới thấy on Xem
[00:00:46] thỉnh thoảng các bạn mới thấy on Xem trực tiếp được đấy chưa ta cũng cũng có
[00:00:49] trực tiếp được đấy chưa ta cũng cũng có gì đó hai khi mà
[00:00:51] gì đó hai khi mà còn nhắn
[00:00:53] còn nhắn kiểu có nhắn tin chat chưa kiểu là live
[00:00:57] kiểu có nhắn tin chat chưa kiểu là live chat thôi ngay nếu mà các bạn xem lại
[00:00:59] chat thôi ngay nếu mà các bạn xem lại thì các bạn xem lại chat nhưng nó chắc
[00:01:01] thì các bạn xem lại chat nhưng nó chắc nó an ủi phần nào
[00:01:03] nó an ủi phần nào đi học không Kiều
[00:01:05] đi học không Kiều à mình mình xem như thằng tự kỷ nó buồn
[00:01:08] à mình mình xem như thằng tự kỷ nó buồn quá không ạ
[00:01:15] ờ ờ [âm nhạc]
[00:01:17] [âm nhạc] anh tính trước hỏi mình mình Speed trả
[00:01:21] anh tính trước hỏi mình mình Speed trả lời trước mấy câu
[00:01:24] lời trước mấy câu ô ồ Hôm trước có bạn hỏi là dậy có dậy
[00:01:30] ô ồ Hôm trước có bạn hỏi là dậy có dậy với P mới với C không thì tết vmvc này
[00:01:34] với P mới với C không thì tết vmvc này tặng Khía dậy đã thấy vợ MBC kết kết hợp
[00:01:39] tặng Khía dậy đã thấy vợ MBC kết kết hợp với OB đã thì mình sẽ
[00:01:41] với OB đã thì mình sẽ mắc nhỏ không do mình đi xa thì mình thử
[00:01:45] mắc nhỏ không do mình đi xa thì mình thử ngồi lại gần nhé ạ
[00:01:49] ngồi lại gần nhé ạ ở
[00:01:54] nhà bây giờ mình sẽ gì gọi gì sát là con Mic Đã chuẩn là
[00:02:01] Mic Đã chuẩn là mình phải mua thêm cả cái gọi là cái
[00:02:04] mình phải mua thêm cả cái gọi là cái giá treo mic nữa để mà Mike kiểu giống
[00:02:08] giá treo mic nữa để mà Mike kiểu giống kiểu mấy chữ m là dí sát vào mặt đấy
[00:02:12] kiểu mấy chữ m là dí sát vào mặt đấy chứ Bây giờ là mình mình toàn phải chơi
[00:02:15] chứ Bây giờ là mình mình toàn phải chơi trò là mình cúi xuống nói chuyện với cái
[00:02:17] trò là mình cúi xuống nói chuyện với cái mic
[00:02:18] mic thì là nó hơi bị bé chắc thế à
[00:02:27] ý tới mình đang kéo hết cỡ mùi xác rồi đó Biết rồi thì
[00:02:33] cái dậy mvc và hiện tpm DC thậm chí
[00:02:39] tpm DC thậm chí thì mình sẽ dậy vào trong khóa học
[00:02:44] thì mình sẽ dậy vào trong khóa học khóa học web tiếp theo
[00:02:48] khóa học web tiếp theo khóa của app để sẽ khóa học nâng cao
[00:02:51] khóa của app để sẽ khóa học nâng cao Bạn nghe rõ không ạ
[00:02:53] Bạn nghe rõ không ạ anh nghe rõ hơn chưa hay là do mình mình
[00:02:57] anh nghe rõ hơn chưa hay là do mình mình tự như mình chỉnh cái gì cho mik bé đi
[00:03:00] tự như mình chỉnh cái gì cho mik bé đi nghỉ ở
[00:03:03] nghỉ ở
[00:03:03] anh alo alo bạn ngày rồi ông ạ
[00:03:11] à à ờ ờ
[00:03:20] ờ ờ xe máy súng ở cái khóa web nâng cao ý
[00:03:23] xe máy súng ở cái khóa web nâng cao ý mình sẽ dạy cả Facebook này sẽ cảm thấy
[00:03:26] mình sẽ dạy cả Facebook này sẽ cảm thấy Seo P
[00:03:27] Seo P Xin chào các bạn thì để các bạn hiểu thế
[00:03:30] Xin chào các bạn thì để các bạn hiểu thế nào mới C này thế nào Okay hướng đối
[00:03:33] nào mới C này thế nào Okay hướng đối tượng này
[00:03:34] tượng này cho MBC đấy mình cũng sẽ có tí ví dụ mà
[00:03:39] cho MBC đấy mình cũng sẽ có tí ví dụ mà mình cảm thấy khá tâm đắc với ví dụ đấy
[00:03:41] mình cảm thấy khá tâm đắc với ví dụ đấy bởi vì Ninh từng học mới xe trên mạng
[00:03:44] bởi vì Ninh từng học mới xe trên mạng cũng tham khảo rất nhiều mình mình
[00:03:48] cũng tham khảo rất nhiều mình mình mình chưa biết mình nói các bạn chưa là
[00:03:52] mình chưa biết mình nói các bạn chưa là mình cũng thường hay rất xem vừa rồi
[00:03:56] mình cũng thường hay rất xem vừa rồi Mình còn phải lướt Lên vài trang nữa kể
[00:03:58] Mình còn phải lướt Lên vài trang nữa kể cả trang
[00:03:59] cả trang người nước ngoài cả cả trang tiếng Việt
[00:04:02] người nước ngoài cả cả trang tiếng Việt từ món Xem cách người ta dậy một cái gì
[00:04:05] từ món Xem cách người ta dậy một cái gì đó để tham khảo sẽ là người ta dạy Cái
[00:04:08] đó để tham khảo sẽ là người ta dạy Cái này như thế nào thứ nhất là mình kiểm
[00:04:10] này như thế nào thứ nhất là mình kiểm tra lại xem mà kiến thức của mình có đủ
[00:04:12] tra lại xem mà kiến thức của mình có đủ 20 like kiến thức mình có đúng hay không
[00:04:14] 20 like kiến thức mình có đúng hay không là xử thế đôi khi bị nghi ngờ với nước
[00:04:17] là xử thế đôi khi bị nghi ngờ với nước mến bởi vì mình bảo rồi đó là bản chất
[00:04:20] mến bởi vì mình bảo rồi đó là bản chất là mình là
[00:04:21] là mình là học từ bên cao lành nghề
[00:04:24] học từ bên cao lành nghề trà xanh thì chắc chắn là lý thuyết của
[00:04:27] trà xanh thì chắc chắn là lý thuyết của mình có thể sẽ không vững lắm thận sẽ
[00:04:30] mình có thể sẽ không vững lắm thận sẽ mình quên vì cái đấy từ lâu rồi
[00:04:34] mình quên vì cái đấy từ lâu rồi lá
[00:04:34] lá cây thực hành của mình nó chết trắng
[00:04:36] cây thực hành của mình nó chết trắng đúng rồi bởi vì nó chạy được và chạy
[00:04:39] đúng rồi bởi vì nó chạy được và chạy được mà nó không ạ Nếu mà cái lý thuyết
[00:04:42] được mà nó không ạ Nếu mà cái lý thuyết cơ lý thuyết thì bắt buộc phải đúng Lo
[00:04:44] cơ lý thuyết thì bắt buộc phải đúng Lo thế nên là mình à
[00:04:46] thế nên là mình à cho mình gửi kiểm tra lại các thứ cũng
[00:04:49] cho mình gửi kiểm tra lại các thứ cũng như Xem khách người ta dậy truyền đạt nó
[00:04:52] như Xem khách người ta dậy truyền đạt nó dễ hiểu thì mình hỏi đúng không ạ thà
[00:04:54] dễ hiểu thì mình hỏi đúng không ạ thà người ta mà dạy kiểu khô khan quá nhưng
[00:04:56] người ta mà dạy kiểu khô khan quá nhưng mình tránh thì cái dậy mới xe ở trên
[00:04:59] mình tránh thì cái dậy mới xe ở trên mạng ấy lúc mình trai ấy thì người ta
[00:05:02] mạng ấy lúc mình trai ấy thì người ta nói rất rối rắm khó hiểu khó hiểu
[00:05:05] nói rất rối rắm khó hiểu khó hiểu ok thì mình khẳng định nó lý thuyết hoàn
[00:05:08] ok thì mình khẳng định nó lý thuyết hoàn toàn rất khó để mà
[00:05:09] toàn rất khó để mà ví dụ
[00:05:11] ví dụ khác với nhiều người đang ví dụ
[00:05:14] khác với nhiều người đang ví dụ sự khác biệt bởi vì mình từng thấy một
[00:05:17] sự khác biệt bởi vì mình từng thấy một cái ví dụ khá ổn trên mạng rồi về có ok
[00:05:19] cái ví dụ khá ổn trên mạng rồi về có ok rồi
[00:05:22] Anh chỉ còn MBC mình khẳng định Mỗi mình mình chơi theo cách ga giàn thiết của
[00:05:28] mình chơi theo cách ga giàn thiết của mpc cửa đấy và công nhận sinh viên mình
[00:05:31] mpc cửa đấy và công nhận sinh viên mình nghe thấy song có vẻ hiểu hết
[00:05:34] nghe thấy song có vẻ hiểu hết Ừ nhưng mà hiểu là một chuyện xong rồi
[00:05:36] Ừ nhưng mà hiểu là một chuyện xong rồi áp dụng bài tập trận khác
[00:05:40] ờ ờ Em spo học tới phần nào thì người sáng
[00:05:45] Em spo học tới phần nào thì người sáng mắt lên được Vậy anh
[00:05:47] mắt lên được Vậy anh thử ta là nếu nếu các bạn xem tại phần
[00:05:50] thử ta là nếu nếu các bạn xem tại phần mô tả bộ khóa học cơ bản ấy thì
[00:05:54] mô tả bộ khóa học cơ bản ấy thì khi Apple chỉ cần biết cơ bản là cái
[00:05:57] khi Apple chỉ cần biết cơ bản là cái toàn bộ FL cơ bản kia các bạn hoàn toàn
[00:06:00] toàn bộ FL cơ bản kia các bạn hoàn toàn có thể
[00:06:01] có thể nhảy sang học lập trình được không Được
[00:06:05] nhảy sang học lập trình được không Được rồi nhưng mà lập trình đấy vẫn chỉ ở cơ
[00:06:08] rồi nhưng mà lập trình đấy vẫn chỉ ở cơ bản thôi còn nếu mà sang khóa học Were A
[00:06:12] bản thôi còn nếu mà sang khóa học Were A xanh khóa web chuyên sâu với thì mình sẽ
[00:06:16] xanh khóa web chuyên sâu với thì mình sẽ dạy các bạn về việc là
[00:06:19] dạy các bạn về việc là đòi rất nhiều bạn vào với nhau xô ngồi
[00:06:22] đòi rất nhiều bạn vào với nhau xô ngồi tối ưu câu truy vấn hơn Vân Vân Vân Vân
[00:06:25] tối ưu câu truy vấn hơn Vân Vân Vân Vân ở chung ở khoa chuyên sâu đấy nó đúng
[00:06:28] ở chung ở khoa chuyên sâu đấy nó đúng nghĩa là để các bạn lương 78 triệu ngang
[00:06:32] nghĩa là để các bạn lương 78 triệu ngang bằng 15 thí nghiệm rồi và còn chỉ các
[00:06:36] bằng 15 thí nghiệm rồi và còn chỉ các bạn với định những lời chung là anh khoe
[00:06:39] bạn với định những lời chung là anh khoe chân xấu à Cái ngập tràn nhầm web chuyên
[00:06:43] chân xấu à Cái ngập tràn nhầm web chuyên sau kia nó sẽ đúng là toàn bộ những cái
[00:06:46] sau kia nó sẽ đúng là toàn bộ những cái thứ mình có thể chia sẻ được sau khi mà
[00:06:48] thứ mình có thể chia sẻ được sau khi mà mình đi làm như thế này mình sẽ chia sẻ
[00:06:51] mình đi làm như thế này mình sẽ chia sẻ được tất cả các bạn về mấy cái kiến thức
[00:06:53] được tất cả các bạn về mấy cái kiến thức của mình
[00:06:54] của mình Vì thế nên là nó sẽ không còn là cơ bản
[00:06:58] Vì thế nên là nó sẽ không còn là cơ bản nữa nó thực tiễn luôn đúng ạ ạ
[00:07:05] Ừ cái có bạn hỏi bây giờ chắc là
[00:07:11] cái có bạn hỏi bây giờ chắc là à à
[00:07:14] I will học chữ cho xong thì mình sẽ học San Jackson em heo shuya mình cũng chỉ
[00:07:22] San Jackson em heo shuya mình cũng chỉ chắc là mình chửi nước có nhanh thôi sợ
[00:07:24] chắc là mình chửi nước có nhanh thôi sợ mà hôm nay nếu mở kỳ phí hôm nay anh sẽ
[00:07:28] mà hôm nay nếu mở kỳ phí hôm nay anh sẽ dạy cho xương luôn này xem có kịp không
[00:07:30] dạy cho xương luôn này xem có kịp không sau đó thì mình
[00:07:33] sau đó thì mình thì mình sẽ như mình đã nói thì mình sẽ
[00:07:36] thì mình sẽ như mình đã nói thì mình sẽ qua zoom để mà khi phỏng vấn Online đúng
[00:07:40] qua zoom để mà khi phỏng vấn Online đúng ạ
[00:07:41] ạ Mình sẽ thi vấn đáp Online hoa rum
[00:07:44] Mình sẽ thi vấn đáp Online hoa rum các bạn vẫn chuẩn bị mic dần dần đi đúng
[00:07:47] các bạn vẫn chuẩn bị mic dần dần đi đúng không ạ ạ
[00:07:51] Ừ cái cây bút bên mình trả lời Mấy câu kia nhé có chữ cơ
[00:07:57] kia nhé có chữ cơ không cho Y xuất khi bị lỗi không
[00:08:00] không cho Y xuất khi bị lỗi không Khi mà trách không đủ mạnh ấy ạ
[00:08:04] Khi mà trách không đủ mạnh ấy ạ Cái vụ mà giả sử mà các bạn Nhập dữ liệu
[00:08:07] Cái vụ mà giả sử mà các bạn Nhập dữ liệu và mà nó bị lỗi nó hiển thị lên lỗi thì
[00:08:11] và mà nó bị lỗi nó hiển thị lên lỗi thì cả Đấy là vài toàn được là là cái dụ là
[00:08:14] cả Đấy là vài toàn được là là cái dụ là giả sử các bạn Nhập sai cái kiểu dữ liệu
[00:08:16] giả sử các bạn Nhập sai cái kiểu dữ liệu chẳng hạn họ sẽ báo lỗi lại thì cái đấy
[00:08:19] chẳng hạn họ sẽ báo lỗi lại thì cái đấy là nó liên quan vietjack rồi nó con con
[00:08:22] là nó liên quan vietjack rồi nó con con con sẽ trên và nó sẽ trả về một một cái
[00:08:26] con sẽ trên và nó sẽ trả về một một cái lỗi chính lạ
[00:08:28] lỗi chính lạ bộ phim không phải lỗi về cú pháp mà lỗi
[00:08:32] bộ phim không phải lỗi về cú pháp mà lỗi về kiểu dữ liệu sai này cử kiểu dữ liệu
[00:08:35] về kiểu dữ liệu sai này cử kiểu dữ liệu không hợp lệ Vân Vân ở ngọn thì
[00:08:39] không hợp lệ Vân Vân ở ngọn thì Ừ thì thì cả đấy mình sẽ không muốn
[00:08:41] Ừ thì thì cả đấy mình sẽ không muốn thích cơ để can thiệp và bản chất là em
[00:08:45] thích cơ để can thiệp và bản chất là em cô ạ Khi mà mình chạy báo về cái lỗi như
[00:08:48] cô ạ Khi mà mình chạy báo về cái lỗi như thế
[00:08:50] thế Ừ thì nó lại recepcion
[00:08:52] Ừ thì nó lại recepcion mình chắc mình sẽ nói qua các bạn một tí
[00:08:56] mình chắc mình sẽ nói qua các bạn một tí rồi ngày cái Samsung Bởi vì thực sự thì
[00:08:59] rồi ngày cái Samsung Bởi vì thực sự thì trái sân Thì nó liên quan cái đấy Hãy
[00:09:02] trái sân Thì nó liên quan cái đấy Hãy xin và alo thì các bạn tìm hiểu về hai
[00:09:05] xin và alo thì các bạn tìm hiểu về hai cái này thì kệ Alo tất cả lỗi cú pháp
[00:09:09] cái này thì kệ Alo tất cả lỗi cú pháp thường hay là lỗ pháp nhiều hơn hoặc cả
[00:09:11] thường hay là lỗ pháp nhiều hơn hoặc cả lỗi kết nối Vân
[00:09:14] lỗi kết nối Vân cài Alo là khi mà các bạn mới chạy cốt
[00:09:17] cài Alo là khi mà các bạn mới chạy cốt thì nó lập tức báo lỗi về đó bạn thường
[00:09:20] thì nó lập tức báo lỗi về đó bạn thường là do những cải kiểu tung nó hỗ trợ mặc
[00:09:24] là do những cải kiểu tung nó hỗ trợ mặc định sẵn kiểm tra các bạn khoa mà những
[00:09:26] định sẵn kiểm tra các bạn khoa mà những cái lỗi đấy bị lỗi chính tả này hay lỗi
[00:09:28] cái lỗi đấy bị lỗi chính tả này hay lỗi à
[00:09:30] à xin lỗi có thể kết nối lỗi không tìm
[00:09:33] xin lỗi có thể kết nối lỗi không tìm file gì đó
[00:09:35] file gì đó ở
[00:09:36] ở đây con cái lỗi Samsung này là lỗi khi
[00:09:40] đây con cái lỗi Samsung này là lỗi khi mà các bạn chạy đến nửa cốc hoặc là chạy
[00:09:43] mà các bạn chạy đến nửa cốc hoặc là chạy cốt rồi Cô đang chạy Rồi nó báo lỗi lỗi
[00:09:47] cốt rồi Cô đang chạy Rồi nó báo lỗi lỗi này có thể là giống như mình vừa nói lỗi
[00:09:50] này có thể là giống như mình vừa nói lỗi liên quan đến nhập dữ liệu vào nó bắt
[00:09:52] liên quan đến nhập dữ liệu vào nó bắt đầu kiểm tra dữ liệu và và nó thấy sai
[00:09:57] đầu kiểm tra dữ liệu và và nó thấy sai nó sẽ phản lại phản hồi lại này thì hoặc
[00:10:00] nó sẽ phản lại phản hồi lại này thì hoặc gà không tin với bảng không tìm cái cột
[00:10:03] gà không tin với bảng không tìm cái cột này các thứ nói sắp sinh chứ anh còn ghế
[00:10:07] này các thứ nói sắp sinh chứ anh còn ghế rô này thì có thể là số số lượng cột
[00:10:10] rô này thì có thể là số số lượng cột tương ứng với valeu cái số lượng truyền
[00:10:14] tương ứng với valeu cái số lượng truyền vào nó không khớp nhau thì nó thể bảo vệ
[00:10:17] vào nó không khớp nhau thì nó thể bảo vệ lỗi về luôn chẳng hạn thế là sử là bây
[00:10:20] lỗi về luôn chẳng hạn thế là sử là bây giờ em các bạn Insert into một cái thuê
[00:10:23] giờ em các bạn Insert into một cái thuê đồ đó các bạn chuyển ở đây hai cột có
[00:10:26] đồ đó các bạn chuyển ở đây hai cột có một khó hay cản va luu các bạn sẽ truyền
[00:10:30] một khó hay cản va luu các bạn sẽ truyền 11 giá trị như này đối ngoại nghĩa cái
[00:10:33] 11 giá trị như này đối ngoại nghĩa cái này không phải chuyển nó sẽ Euro Tức là
[00:10:35] này không phải chuyển nó sẽ Euro Tức là nó sẽ nó có thể hiển thị ra lỗi ngay cho
[00:10:39] nó sẽ nó có thể hiển thị ra lỗi ngay cho các bạn về cái điều này còn ấy xếp sân
[00:10:41] các bạn về cái điều này còn ấy xếp sân Thì là lỗi khi mà
[00:10:43] Thì là lỗi khi mà phải chạy cốt rồi chạy cốt ăn đến nửa
[00:10:47] phải chạy cốt rồi chạy cốt ăn đến nửa chừng rồi nó mới bắt đầu triệu nó mới
[00:10:49] chừng rồi nó mới bắt đầu triệu nó mới đau đầu báo lỗi cho các bạn thực sự là
[00:10:51] đau đầu báo lỗi cho các bạn thực sự là có vấn đề gì đó thì cái vụ đấy ở chính
[00:10:56] có vấn đề gì đó thì cái vụ đấy ở chính là trà sữa khi in sẽ bị lỗi này đi thì
[00:11:00] là trà sữa khi in sẽ bị lỗi này đi thì Ừ thì các bạn phải dùng trai cát là
[00:11:04] Ừ thì các bạn phải dùng trai cát là là bắt lỗi
[00:11:07] là bắt lỗi chai là thử không ạ và cắt là kiểu bắt
[00:11:10] chai là thử không ạ và cắt là kiểu bắt lấy
[00:11:11] lấy Ừ bắt lấy cái Assassins bắt người có lỗi
[00:11:15] Ừ bắt lấy cái Assassins bắt người có lỗi đấy để mà thao tác gì tiếp thì gì đó
[00:11:19] đấy để mà thao tác gì tiếp thì gì đó thường là
[00:11:22] dễ thương là kiểu trai cắt như thế rồi thông báo thông bạn thường mà thông báo
[00:11:27] thông báo thông bạn thường mà thông báo theo kiểu là thông báo các bạn thì kiểm
[00:11:31] theo kiểu là thông báo các bạn thì kiểm tra lại với dữ liệu khi mí ra vào trong
[00:11:33] tra lại với dữ liệu khi mí ra vào trong nó gì sai cái gì đó
[00:11:36] nó gì sai cái gì đó Ừ cái này nó lại không liên quan đến Hầm
[00:11:39] Ừ cái này nó lại không liên quan đến Hầm chui cơ lắm mà liên quan trên sẽ xin hơn
[00:11:41] chui cơ lắm mà liên quan trên sẽ xin hơn ví dụ ví dụ về cái vụ chơi xin thì chắc
[00:11:45] ví dụ ví dụ về cái vụ chơi xin thì chắc là để thuận tuần sau mình dậy các bạn đi
[00:11:48] là để thuận tuần sau mình dậy các bạn đi mình chị nào quay Thôi mẹ nó không nó
[00:11:50] mình chị nào quay Thôi mẹ nó không nó không nên dùng chi cơ để kiểm tra được
[00:11:52] không nên dùng chi cơ để kiểm tra được là không cho như rất là con nếu mà
[00:11:56] là không cho như rất là con nếu mà bạn chỉ để cập về vụ là có chữ cơ không
[00:11:59] bạn chỉ để cập về vụ là có chữ cơ không cho giấc thì chính là buổi hôm nay mình
[00:12:02] cho giấc thì chính là buổi hôm nay mình sẽ học đúng ạ
[00:12:04] sẽ học đúng ạ con trai cát ở trong mọi ngôn ngữ lập
[00:12:06] con trai cát ở trong mọi ngôn ngữ lập trình cũng có không phải mỗi zava bạn
[00:12:09] trình cũng có không phải mỗi zava bạn nhưng mà Đúng là mình hồi đầu tiên mình
[00:12:13] nhưng mà Đúng là mình hồi đầu tiên mình học trời cao thì đúng là thầy mình áp
[00:12:15] học trời cao thì đúng là thầy mình áp dụng bằng da thật
[00:12:16] dụng bằng da thật là chỗ là kiểu Java thì mình thấy à nó
[00:12:21] là chỗ là kiểu Java thì mình thấy à nó tương đối cũng rất là gọn nhận được
[00:12:26] tương đối cũng rất là gọn nhận được đi đầy đủ chồng tờ đầy đủ nhãn chị ạ Nó
[00:12:30] đi đầy đủ chồng tờ đầy đủ nhãn chị ạ Nó có gà hướng đối tượng này nó có cú pháp
[00:12:34] có gà hướng đối tượng này nó có cú pháp các thứ thứ tồi
[00:12:36] các thứ thứ tồi Ừ
[00:12:37] Ừ nhưng mà hồi đấy thì đúng mình không
[00:12:39] nhưng mà hồi đấy thì đúng mình không hiểu tại sao mình qua được một ra luôn
[00:12:41] hiểu tại sao mình qua được một ra luôn thì hồi nãy mình chuyên bán TP thì thấy
[00:12:45] thì hồi nãy mình chuyên bán TP thì thấy có vẻ trầm trước bởi phía hồi đầy Hồi
[00:12:48] có vẻ trầm trước bởi phía hồi đầy Hồi đấy chưa mình chấm nói ở đây không biết
[00:12:51] đấy chưa mình chấm nói ở đây không biết được có bị cho là không không hẳn bóc
[00:12:55] được có bị cho là không không hẳn bóc phốt người không biết nó cho Dì xấu xấu
[00:12:58] phốt người không biết nó cho Dì xấu xấu không Nếu mà theo quan điểm trường mình
[00:13:01] không Nếu mà theo quan điểm trường mình ấy chấm điểm khi dễ cực
[00:13:03] ấy chấm điểm khi dễ cực bí đỏ uống mấy bé ông biết tôi sau đây
[00:13:07] bí đỏ uống mấy bé ông biết tôi sau đây về sau tôi làm thầy Tôi chấm điểm thi
[00:13:09] về sau tôi làm thầy Tôi chấm điểm thi như thế nào
[00:13:10] như thế nào thứ nhất nha đó tôi luôn luôn Hỏi thế
[00:13:14] thứ nhất nha đó tôi luôn luôn Hỏi thế Cái này hỡi vào giờ mới dồi cho mình Bây
[00:13:17] Cái này hỡi vào giờ mới dồi cho mình Bây giờ mình mới tâm sự xin lỗi gì nhé à
[00:13:21] giờ mình mới tâm sự xin lỗi gì nhé à sau
[00:13:22] sau khi mà tôi chấm điểm thi và giống như
[00:13:25] khi mà tôi chấm điểm thi và giống như thầy của tội từ nhan dụng nó ra ngay Tôi
[00:13:28] thầy của tội từ nhan dụng nó ra ngay Tôi sẽ luôn Hỏi sinh viên Đó là
[00:13:30] sẽ luôn Hỏi sinh viên Đó là à
[00:13:32] à đầu tiên là tôi sẽ cho tất cả mọi người
[00:13:34] đầu tiên là tôi sẽ cho tất cả mọi người ra ngoài đã cho mọi người ra khỏi khỏi
[00:13:36] ra ngoài đã cho mọi người ra khỏi khỏi phòng phòng thi bỏ tôi thi thực hành mà
[00:13:39] phòng phòng thi bỏ tôi thi thực hành mà Ờ
[00:13:40] Ờ sau đó thì tôi sẽ hỏi trước là những
[00:13:45] sau đó thì tôi sẽ hỏi trước là những những ai muốn điểm trên 8D dai đấy Sau
[00:13:50] những ai muốn điểm trên 8D dai đấy Sau đó thì
[00:13:52] đó thì có đương nhiên là
[00:13:54] có đương nhiên là một vài ông lắc bát theo kiểu là tiểu
[00:13:57] một vài ông lắc bát theo kiểu là tiểu mấy ông ấy tự tin ý mày nghĩ mình làm ổn
[00:14:01] mấy ông ấy tự tin ý mày nghĩ mình làm ổn rồi Nó hư dữ
[00:14:02] rồi Nó hư dữ Ừ thôi bà mẹ mấy ông cứ ở lại đây á nó
[00:14:05] Ừ thôi bà mẹ mấy ông cứ ở lại đây á nó không sẽ được ở lại nhưng cô ấy nếu mới
[00:14:07] không sẽ được ở lại nhưng cô ấy nếu mới sẵn sàng trời luôn rồi mấy ông ấy nghĩ
[00:14:09] sẵn sàng trời luôn rồi mấy ông ấy nghĩ mình mình muốn tìm cao thôi mình gửi
[00:14:12] mình mình muốn tìm cao thôi mình gửi chấp nhận sôi tiếp theo tôi hỏi lại
[00:14:14] chấp nhận sôi tiếp theo tôi hỏi lại những ông nào
[00:14:16] những ông nào nghĩa chỉ muốn là mình qua cái môn này
[00:14:20] nghĩa chỉ muốn là mình qua cái môn này mà nghĩ mình sẽ nằm
[00:14:23] mà nghĩ mình sẽ nằm đấy thì đương nhiên cũng lại có một vài
[00:14:26] đấy thì đương nhiên cũng lại có một vài chú lác đác hiểu mấy ông cậu học cho lấy
[00:14:29] chú lác đác hiểu mấy ông cậu học cho lấy giữ cho cái cái bằng rồi Gần họ gà làm
[00:14:32] giữ cho cái cái bằng rồi Gần họ gà làm bài có thể có vài bạn tự ti là mà không
[00:14:34] bài có thể có vài bạn tự ti là mà không tốp hãy rồi tôi sẽ mời lần lượt mấy ông
[00:14:37] tốp hãy rồi tôi sẽ mời lần lượt mấy ông ấy và trước xong rồi tôi sẽ chỉ cần thực
[00:14:40] ấy và trước xong rồi tôi sẽ chỉ cần thực ra tôi chỉ cần lướt qua bằng vải câu mà
[00:14:43] ra tôi chỉ cần lướt qua bằng vải câu mà biết được mày có copy cốt của ông nào
[00:14:46] biết được mày có copy cốt của ông nào đói không hỏi mua vài cái ra vấn đề ngay
[00:14:49] đói không hỏi mua vài cái ra vấn đề ngay đúng loại
[00:14:50] đúng loại đấy Sau đó thì có một vài âu của tôi sẽ
[00:14:54] đấy Sau đó thì có một vài âu của tôi sẽ xâm trước nhưng mà theo theo dạng là
[00:14:57] xâm trước nhưng mà theo theo dạng là chấm dứt cho quá môn như cả là đúng là
[00:15:00] chấm dứt cho quá môn như cả là đúng là ông ấy chịu khó khăn cần cù thôi chứ ông
[00:15:02] ông ấy chịu khó khăn cần cù thôi chứ ông ơi ở
[00:15:03] ơi ở đây là bài có thể chắc chắn trường rồi
[00:15:06] đây là bài có thể chắc chắn trường rồi mới biết gì đâu Nhưng mà nếu mà số lượng
[00:15:10] mới biết gì đâu Nhưng mà nếu mà số lượng người mà kiểu bị chấm trước như thế mà
[00:15:13] người mà kiểu bị chấm trước như thế mà đông quá thì tội cho tất cả cùng khi lại
[00:15:16] đông quá thì tội cho tất cả cùng khi lại ý nghĩa là như thế bạn sẽ họp lại Bởi vì
[00:15:19] ý nghĩa là như thế bạn sẽ họp lại Bởi vì gấu Nếu bây giờ sử có một mình một hoặc
[00:15:22] gấu Nếu bây giờ sử có một mình một hoặc hai ông tự nhiên phải thi lại thì hai
[00:15:24] hai ông tự nhiên phải thi lại thì hai ông ấy thì lại một mình buồn quá đúng
[00:15:26] ông ấy thì lại một mình buồn quá đúng không ạ bây giờ sử có người mấy ông cùng
[00:15:28] không ạ bây giờ sử có người mấy ông cùng bị như thế thì cho học lại luôn cho nó
[00:15:31] bị như thế thì cho học lại luôn cho nó học cùng nhau cho vui hãy trở thế xanh
[00:15:34] học cùng nhau cho vui hãy trở thế xanh ra được
[00:15:35] ra được thôi chấm thì nó sẽ như thế thà đấy Sao
[00:15:39] thôi chấm thì nó sẽ như thế thà đấy Sao con tiếp theo để nó những ông 89 điểm là
[00:15:42] con tiếp theo để nó những ông 89 điểm là 12 này nếu không tàn gì ở tôi sẽ gọi vào
[00:15:45] 12 này nếu không tàn gì ở tôi sẽ gọi vào nhé tôi bà em muốn mấy đứa à
[00:15:49] nhé tôi bà em muốn mấy đứa à Ừ ừ thì muốn cho bao nhiêu cũng được Ừ
[00:15:52] Ừ ừ thì muốn cho bao nhiêu cũng được Ừ Thế 5 điểm nữa nhé
[00:15:54] Thế 5 điểm nữa nhé 300 Em em em làm bài đầy đủ tốt rồi mà
[00:16:00] 300 Em em em làm bài đầy đủ tốt rồi mà 35 bay đi đừng tốt thì ông ấy muốn mới
[00:16:02] 35 bay đi đừng tốt thì ông ấy muốn mới điều không phải nói chứ Bây giờ giả sử
[00:16:05] điều không phải nói chứ Bây giờ giả sử khi phỏng vấn ông ông được hỏi là ông
[00:16:09] khi phỏng vấn ông ông được hỏi là ông muốn mức lương mà nhiều rồi kêu họ tùy
[00:16:12] muốn mức lương mà nhiều rồi kêu họ tùy tâm thì người ta chỉ cho một triệu thôi
[00:16:14] tâm thì người ta chỉ cho một triệu thôi lo Nếu không phải tự đánh giá năng lực
[00:16:17] lo Nếu không phải tự đánh giá năng lực của bản thân mình
[00:16:18] của bản thân mình cái đấy không phải tự kia mà tự tin mình
[00:16:22] cái đấy không phải tự kia mà tự tin mình làm được rồi mình làm được thì mình phải
[00:16:24] làm được rồi mình làm được thì mình phải biết được là cái mức thưởng Xứng Đáng
[00:16:27] biết được là cái mức thưởng Xứng Đáng của mình nó đến đâu một khi mà ông kiểu
[00:16:31] của mình nó đến đâu một khi mà ông kiểu kêu thì tâm cái hư thử người ta chỉ cho
[00:16:34] kêu thì tâm cái hư thử người ta chỉ cho đúng kiểu dạng là mức tối thiểu Thôi
[00:16:38] đúng kiểu dạng là mức tối thiểu Thôi về hỏi lại ông muốn mới được đấy sổ bắt
[00:16:41] về hỏi lại ông muốn mới được đấy sổ bắt đầu mấy ông thì có thể nói là em mùng 8
[00:16:43] đầu mấy ông thì có thể nói là em mùng 8 đi đấy 8 điểm thì ra tôi chỉ chấm đúng
[00:16:48] đi đấy 8 điểm thì ra tôi chỉ chấm đúng bài tập anh béo làm đầy đủ thuốc ạ những
[00:16:51] bài tập anh béo làm đầy đủ thuốc ạ những cái câu hỏi trong đề thi thì bé ông chỉ
[00:16:54] cái câu hỏi trong đề thi thì bé ông chỉ được 8 ý nghĩa là cái cách chấm của mình
[00:16:57] được 8 ý nghĩa là cái cách chấm của mình có khác cho thấy ra có lời khác thì chấm
[00:16:59] có khác cho thấy ra có lời khác thì chấm rằng theo kiểu đấy
[00:17:01] rằng theo kiểu đấy ông làm đầy đủ thứ cả câu hỏi trong đề
[00:17:03] ông làm đầy đủ thứ cả câu hỏi trong đề thi rồi thì 10 Đúng không Mình không lời
[00:17:06] thi rồi thì 10 Đúng không Mình không lời cho mượn mình sẽ chỉ cho 88 và găng rồi
[00:17:09] cho mượn mình sẽ chỉ cho 88 và găng rồi trí ta khi mà ông trả lời được một câu
[00:17:12] trí ta khi mà ông trả lời được một câu nữa của tôi ngoài đề Không ạ là mười khi
[00:17:16] nữa của tôi ngoài đề Không ạ là mười khi mà không trả được câu sao rồi nữa ừ
[00:17:19] mà không trả được câu sao rồi nữa ừ Ừ đấy Thì đấy là
[00:17:22] Ừ đấy Thì đấy là vợ nói thì bọn nó sẽ khi và bọn nó chọn
[00:17:26] vợ nói thì bọn nó sẽ khi và bọn nó chọn nút chín mười mới có ở chấm bài tập luôn
[00:17:28] nút chín mười mới có ở chấm bài tập luôn Nhưng hãy hỏi những thêm cái câu ngoài
[00:17:31] Nhưng hãy hỏi những thêm cái câu ngoài ngoài đời thi có thể cố sao và kiến thức
[00:17:33] ngoài đời thi có thể cố sao và kiến thức mới luôn đấy cách dạy của mình Bọn nó
[00:17:37] mới luôn đấy cách dạy của mình Bọn nó bọn sinh viên của mình thì những đứa nào
[00:17:40] bọn sinh viên của mình thì những đứa nào mà học được đấy Có vẻ khá thích minh khi
[00:17:42] mà học được đấy Có vẻ khá thích minh khi mình cho nhiều câu sao thêm này cũng như
[00:17:45] mình cho nhiều câu sao thêm này cũng như là
[00:17:46] là Anh kéo nó kiểu thoải mái hơn để chấm
[00:17:50] Anh kéo nó kiểu thoải mái hơn để chấm Không chụp Rập khuôn giống như như thầy
[00:17:53] Không chụp Rập khuôn giống như như thầy cô kìa kiểm tra từng dòng cốt một cái
[00:17:56] cô kìa kiểm tra từng dòng cốt một cái thứ
[00:17:58] thứ ở Mỹ Nhân thỉnh thoảng bị sẽ góp ý bắt
[00:18:01] ở Mỹ Nhân thỉnh thoảng bị sẽ góp ý bắt bẻ khi mà nhìn qua cốt của
[00:18:04] bẻ khi mà nhìn qua cốt của nhìn qua cốt của mấy bạn đấy
[00:18:07] nhìn qua cốt của mấy bạn đấy the face cho sao cũng được trên tán là
[00:18:10] the face cho sao cũng được trên tán là Ok đúng không Tôi chứ nếu thế thôi Chỉ
[00:18:12] Ok đúng không Tôi chứ nếu thế thôi Chỉ cho 8 thôi
[00:18:14] cho 8 thôi cho tôi cho Tám thẳng luôn Tôi không
[00:18:15] cho tôi cho Tám thẳng luôn Tôi không chịu thêm chấm cốt cơ cho về luôn miễn
[00:18:18] chịu thêm chấm cốt cơ cho về luôn miễn dàng nhìn mặt của bạn đấy Chồng phải tự
[00:18:20] dàng nhìn mặt của bạn đấy Chồng phải tự tin chứ nếu mày ông nguyễn đạt đến nỗi ở
[00:18:23] tin chứ nếu mày ông nguyễn đạt đến nỗi ở Mấy ông không biết cốt mà Mấy ông tự tin
[00:18:26] Mấy ông không biết cốt mà Mấy ông tự tin được như thế thì tội cho ông Tám ông
[00:18:28] được như thế thì tội cho ông Tám ông xứng đáng được 8
[00:18:29] xứng đáng được 8 điểm số ở trường mình mình chưa từng cho
[00:18:33] điểm số ở trường mình mình chưa từng cho nó quan trọng kể cả bằng cấp Ở ngành này
[00:18:35] nó quan trọng kể cả bằng cấp Ở ngành này nó không bao giờ quan trọng
[00:18:36] nó không bao giờ quan trọng Thế em bảo ông Khoa ông được 10 ta thứ
[00:18:39] Thế em bảo ông Khoa ông được 10 ta thứ hai được 89 Cái thứ họ chẳng thể hiện
[00:18:42] hai được 89 Cái thứ họ chẳng thể hiện được cái điều gì cả Ừ nhưng mà cái việc
[00:18:47] được cái điều gì cả Ừ nhưng mà cái việc Anh biết mình đang ở vị trí nào có thử
[00:18:49] Anh biết mình đang ở vị trí nào có thử đấy mới ở thì yếu tố quan trọng mà mình
[00:18:51] đấy mới ở thì yếu tố quan trọng mà mình muốn dậy đề thi thử đối mình chưa rồi
[00:18:55] muốn dậy đề thi thử đối mình chưa rồi quan trọng Đấy cả giống như ở đấy mình
[00:18:57] quan trọng Đấy cả giống như ở đấy mình còn đề cập thêm mà hồi đấy thi Zara mình
[00:19:00] còn đề cập thêm mà hồi đấy thi Zara mình mình toàn qua thận chứ được 10 thì khẳng
[00:19:02] mình toàn qua thận chứ được 10 thì khẳng định nói lại mình được 10 chứ dù mình
[00:19:04] định nói lại mình được 10 chứ dù mình ngồi đấy mình gọn như này mình
[00:19:07] ngồi đấy mình gọn như này mình có đấy Mình đi thực tập mà rồi đấy mình
[00:19:11] có đấy Mình đi thực tập mà rồi đấy mình xin phép thời mình mình có công ty tuyển
[00:19:14] xin phép thời mình mình có công ty tuyển mình rồi mình đi thực tập em mình không
[00:19:16] mình rồi mình đi thực tập em mình không không đi học được
[00:19:18] không đi học được À thế à khi đi thì anh em mình vẫn phải
[00:19:20] À thế à khi đi thì anh em mình vẫn phải có mặt Vẫn giận đương nhiên vẫn phải có
[00:19:23] có mặt Vẫn giận đương nhiên vẫn phải có mặt thôi mà ký ký giấy tờ các thứ chấm
[00:19:26] mặt thôi mà ký ký giấy tờ các thứ chấm đi em à khi trong trong cát bụi đấy tôi
[00:19:30] đi em à khi trong trong cát bụi đấy tôi ngồi làm bài đấy bằng pp ngoài bằng Java
[00:19:33] ngồi làm bài đấy bằng pp ngoài bằng Java xong rồi thay thay thấy mình thấy không
[00:19:37] xong rồi thay thay thấy mình thấy không thèm nhìn bài mình luôn Thấy bảo đi thực
[00:19:40] thèm nhìn bài mình luôn Thấy bảo đi thực tập rồi à Tốt không Em có sự thứ tôi
[00:19:43] tập rồi à Tốt không Em có sự thứ tôi thấy cho 10 ngày
[00:19:45] thấy cho 10 ngày em thay cho 10 cả lớp biết nhé nó chạm
[00:19:47] em thay cho 10 cả lớp biết nhé nó chạm vào cả lớp chẳng phải làm cái gì cả Bởi
[00:19:49] vào cả lớp chẳng phải làm cái gì cả Bởi vì uống dĩ là trường mình ở trường nghề
[00:19:51] vì uống dĩ là trường mình ở trường nghề cái thằng cha kia ông nào mà kiểu đi
[00:19:55] cái thằng cha kia ông nào mà kiểu đi thực tập đi làm được rồi Chứng tỏ là Đạt
[00:19:58] thực tập đi làm được rồi Chứng tỏ là Đạt được đúng cái tiêu chí của trường nghề
[00:20:00] được đúng cái tiêu chí của trường nghề mà đóng học đào tạo được nghề rồi có
[00:20:03] mà đóng học đào tạo được nghề rồi có việc làm rồi nhưng mà đòi hỏi gì nữa Thế
[00:20:06] việc làm rồi nhưng mà đòi hỏi gì nữa Thế nên là mười không có nhiều ừ ừ
[00:20:10] nên là mười không có nhiều ừ ừ Em hãy 7 giờ một trong những cách dạy
[00:20:14] Em hãy 7 giờ một trong những cách dạy của mình và các chấm thi của mình hồi
[00:20:16] của mình và các chấm thi của mình hồi trước không lỡ như là mình không nói với
[00:20:19] trước không lỡ như là mình không nói với các chấm thi ở trường khác là nó bị như
[00:20:21] các chấm thi ở trường khác là nó bị như thế nào nữa mà mình thấy ở cái đấy nó sẽ
[00:20:24] thế nào nữa mà mình thấy ở cái đấy nó sẽ khiến cho sinh viên chẳng có gì bất lực
[00:20:26] khiến cho sinh viên chẳng có gì bất lực khi mà đi chi cả kiểu rất là vui vẻ các
[00:20:29] khi mà đi chi cả kiểu rất là vui vẻ các kiểu thoải mãi đến gặp ông bị đánh trượt
[00:20:32] kiểu thoải mãi đến gặp ông bị đánh trượt ông thoải mái ông ấy cũng phải nề
[00:20:35] ông thoải mái ông ấy cũng phải nề Ừ đúng ạ
[00:20:36] Ừ đúng ạ Ê mấy ông chấm thi kiểu phải xả châu Âu
[00:20:40] Ê mấy ông chấm thi kiểu phải xả châu Âu Kiểu khiến cho các ông giỏi cả ông rốt
[00:20:43] Kiểu khiến cho các ông giỏi cả ông rốt cũng phải lề Cái thì đấy nữa tốt
[00:20:47] em thậm chí ở kiểu Có phải bạn yếu lấy mấy bạn đấy Kiểu bị chưa đấy mình cũng
[00:20:54] mấy bạn đấy Kiểu bị chưa đấy mình cũng hỏi lại bằng mấy câu cơ bản nhất không
[00:20:56] hỏi lại bằng mấy câu cơ bản nhất không có trong đề đó ạ hỏi mấy câu có bạn nát
[00:20:58] có trong đề đó ạ hỏi mấy câu có bạn nát Giả sử giống như ép quen này mình hỏi
[00:21:00] Giả sử giống như ép quen này mình hỏi lại là sử bạn đấy Bây giờ đang khi về
[00:21:04] lại là sử bạn đấy Bây giờ đang khi về cái cơ thể nặng mình hỏi lại các bạn về
[00:21:06] cái cơ thể nặng mình hỏi lại các bạn về cái acetals hiểu mấy câu rất các bạn
[00:21:08] cái acetals hiểu mấy câu rất các bạn thôi nếu bạn làm được mình vẫn cho 5
[00:21:11] thôi nếu bạn làm được mình vẫn cho 5 điểm chiều qua con Nếu mấy bạn này không
[00:21:13] điểm chiều qua con Nếu mấy bạn này không làm được nổi mấy câu đấy thế thôi Chưa
[00:21:15] làm được nổi mấy câu đấy thế thôi Chưa thấy phải chấp nhận không ạ Anh đang thi
[00:21:19] thấy phải chấp nhận không ạ Anh đang thi thì mấy bạn ấy cảm thấy ở phục lỗi kiểu
[00:21:22] thì mấy bạn ấy cảm thấy ở phục lỗi kiểu mình chẳng biết một tí gì cả thì mình
[00:21:24] mình chẳng biết một tí gì cả thì mình chưa tới đúng rồi ông ạ
[00:21:25] chưa tới đúng rồi ông ạ à à
[00:21:31] Ừ cái điểm 9 điểm 10 với mình thì nó tìm 9 Thực ra nó mới khá lý tưởng
[00:21:37] 9 Thực ra nó mới khá lý tưởng chính là mức kiểu trên rộng nó là mức
[00:21:41] chính là mức kiểu trên rộng nó là mức giỏi rồi và chưa lỗi là mức Hoàn hạn mức
[00:21:44] giỏi rồi và chưa lỗi là mức Hoàn hạn mức là mình còn phải phấn đấu thêm Còn lúc
[00:21:47] là mình còn phải phấn đấu thêm Còn lúc 10 mức hoàn hảo quá mình rất hạn chế cho
[00:21:49] 10 mức hoàn hảo quá mình rất hạn chế cho bạn là mười chứ khi bạn ấy có phải rất
[00:21:51] bạn là mười chứ khi bạn ấy có phải rất xuất sắc
[00:21:53] xuất sắc AE theo kiểu bạn đấy phải phải tự học
[00:21:56] AE theo kiểu bạn đấy phải phải tự học trước rất nhiều thì mới mấy trả lời đúng
[00:21:58] trước rất nhiều thì mới mấy trả lời đúng mới câu đấy mình mới trong 10 anh có thể
[00:22:01] mới câu đấy mình mới trong 10 anh có thể hôm phòng có thể hôm sau chấm Mình có
[00:22:05] hôm phòng có thể hôm sau chấm Mình có thể hỏi vài bạn nhỏ như thế chỉ sợ không
[00:22:08] thể hỏi vài bạn nhỏ như thế chỉ sợ không đủ để gian tới buổi hôm sau thấy rất là
[00:22:10] đủ để gian tới buổi hôm sau thấy rất là giỏi đấy nếu con ra xử hôm sau Vừa là sự
[00:22:13] giỏi đấy nếu con ra xử hôm sau Vừa là sự cứ 60 người ta ngon như thế này 60 người
[00:22:16] cứ 60 người ta ngon như thế này 60 người cùng sau hỏi thì phần đang vậy chứ không
[00:22:17] cùng sau hỏi thì phần đang vậy chứ không phải chia hai buổi bởi Hưng không thể
[00:22:20] phải chia hai buổi bởi Hưng không thể một buổi xong hết mấy bạn được
[00:22:23] một buổi xong hết mấy bạn được Ừ ok Nói chung nha bây giờ bắt đầu vào
[00:22:27] Ừ ok Nói chung nha bây giờ bắt đầu vào học nha à
[00:22:30] học nha à
[00:22:30] thì mình sẽ trả lời câu này nói tào lao không áp dụng thực tế
[00:22:35] không áp dụng thực tế Ừ thì không đĩa bạn Này bạn này bình
[00:22:38] Ừ thì không đĩa bạn Này bạn này bình luận cái nay ở trong cái video qua
[00:22:41] luận cái nay ở trong cái video qua QL 13
[00:22:44] QL 13 Em không biết bạn này muốn áp dụng thực
[00:22:46] Em không biết bạn này muốn áp dụng thực tế như thế nào Nhưng mà nếu mà kiểu à
[00:22:53] Ừ cái việc mà bạn ấy bảo mình nói như thế rồi ra mình cũng hơi tự ái một tí Ừ
[00:23:00] thế rồi ra mình cũng hơi tự ái một tí Ừ nhưng mà
[00:23:02] nhưng mà Ừ cái cái Việt áp dụng thực tế này thì
[00:23:05] Ừ cái cái Việt áp dụng thực tế này thì kệ SQL nó nó là không nó khó món dụng
[00:23:08] kệ SQL nó nó là không nó khó món dụng thực tế lắm các bạn phải kiểu nhảy sang
[00:23:11] thực tế lắm các bạn phải kiểu nhảy sang lập trình với các bạn béo ruộng được Còn
[00:23:13] lập trình với các bạn béo ruộng được Còn không thì toàn bộ quyền nước này về cơ
[00:23:15] không thì toàn bộ quyền nước này về cơ bản nó vẫn là tào lao nó vẫn có dụng
[00:23:17] bản nó vẫn là tào lao nó vẫn có dụng thực tế Được
[00:23:19] Không cho trả lại chúng ta luôn có những thành phần có những người ghét mình rồi
[00:23:24] thành phần có những người ghét mình rồi đúng ạ Hôm hôm nay mình còn thấy
[00:23:29] đúng ạ Hôm hôm nay mình còn thấy có một bạn của bất mãn các thứ mình và
[00:23:32] có một bạn của bất mãn các thứ mình và góp ý vậy chửi lại mình mình đang sợ là
[00:23:34] góp ý vậy chửi lại mình mình đang sợ là bạn ơi bê tông ngoài đời bạn đấy xin
[00:23:37] bạn ơi bê tông ngoài đời bạn đấy xin mình làm nhìn cách nói chuyện kìa Bố đầy
[00:23:40] mình làm nhìn cách nói chuyện kìa Bố đầy quá Kiểu thế à à
[00:23:43] quá Kiểu thế à à à mình làm kiểm duyệt nhóm yootheme công
[00:23:45] à mình làm kiểm duyệt nhóm yootheme công ty mấy lần cũng sợ như thế sợ là chồng
[00:23:47] ty mấy lần cũng sợ như thế sợ là chồng mình mình xử lý bạn ấy xong bởi vì nó
[00:23:51] mình mình xử lý bạn ấy xong bởi vì nó tưởng có một ông một ông này
[00:23:53] tưởng có một ông một ông này khi bị trẻ trâu đến mức độ là ông ấy
[00:23:56] khi bị trẻ trâu đến mức độ là ông ấy inbox cho Tết trường của mình xong gửi
[00:24:00] inbox cho Tết trường của mình xong gửi mail cho trường mình chửi
[00:24:04] Ừ nhưng mà tôi vẫn cha được ra địa chỉ nhà ông đấy nó số điện thoại ông đấy
[00:24:08] nhà ông đấy nó số điện thoại ông đấy nhưng mà tôi không muốn bảo công an thôi
[00:24:09] nhưng mà tôi không muốn bảo công an thôi à
[00:24:18] khi tôi chạm nó mà Mấy ông ấy bị trẻ trâu trong nhóm nên tôi chặn với ông ấy
[00:24:23] trâu trong nhóm nên tôi chặn với ông ấy so với ông ấy biết được tôi chặn rồi ông
[00:24:25] so với ông ấy biết được tôi chặn rồi ông ấy mới không ấy
[00:24:26] ấy mới không ấy mà Hết sống rồi chửi trường tôi xong rồi
[00:24:29] mà Hết sống rồi chửi trường tôi xong rồi còn là Nhắn tin inbox chửi mẹ tôi cơ tôi
[00:24:33] còn là Nhắn tin inbox chửi mẹ tôi cơ tôi bảo đấy Tôi muốn làm căng vãi chưởng
[00:24:34] bảo đấy Tôi muốn làm căng vãi chưởng kiểu Nếu mà tôi thật sự tôi không nghĩ à
[00:24:37] kiểu Nếu mà tôi thật sự tôi không nghĩ à Tôi nghĩ là bây giờ mình nó chưa gửi
[00:24:40] Tôi nghĩ là bây giờ mình nó chưa gửi được ra nó vẫn chỉ hơi gây khó chịu tí
[00:24:43] được ra nó vẫn chỉ hơi gây khó chịu tí em bây giờ sửa kiểu làm là làm cho nó
[00:24:48] em bây giờ sửa kiểu làm là làm cho nó kiểu căng quá số tự nhiên mình mấy cái
[00:24:50] kiểu căng quá số tự nhiên mình mấy cái đưa đây nó
[00:24:52] đưa đây nó liệu án nó không có gì ở mất nó lại
[00:24:55] liệu án nó không có gì ở mất nó lại xuyên nó cái gì lúc rồi mình 1 đổi 1 với
[00:24:58] xuyên nó cái gì lúc rồi mình 1 đổi 1 với nó bị thiệt
[00:24:59] nó bị thiệt cho nên là biển vô giá với
[00:25:02] cho nên là biển vô giá với thì à
[00:25:03] thì à ở bên bu-rô thì toàn chơi cái trò là kia
[00:25:07] ở bên bu-rô thì toàn chơi cái trò là kia phải phải chấp nhận chịu nhục Khi mà gặp
[00:25:11] phải phải chấp nhận chịu nhục Khi mà gặp một cái thành phần như thế luôn các bạn
[00:25:13] một cái thành phần như thế luôn các bạn là nhất cái cửa thế
[00:25:15] là nhất cái cửa thế áo kiểu bỏ qua bỏ qua không không bao
[00:25:19] áo kiểu bỏ qua bỏ qua không không bao giờ dám dây vào những cái thành phần như
[00:25:21] giờ dám dây vào những cái thành phần như thế
[00:25:22] thế khi thận mình nghĩ là đúng đúng đúng là
[00:25:25] khi thận mình nghĩ là đúng đúng đúng là mình phải nhịn mày đấy
[00:25:30] dự án nghị thì không phải nhiều cũng đúng nếu mình nghĩ kiểu gì hết
[00:25:37] mở cửa sợ nhất mà người thanh niên này mà mình hình lên đấy Kiểu họ có gì để
[00:25:41] mà mình hình lên đấy Kiểu họ có gì để mất đầu mình thì có rất nhiều cái thứ là
[00:25:43] mất đầu mình thì có rất nhiều cái thứ là mất đúng ạ
[00:25:47] ở thời lại để đi hơi xa quá rồi à à à
[00:25:53] à à à mình mình mình sẽ sở nốt câu này Ờ cái
[00:25:57] à mình mình mình sẽ sở nốt câu này Ờ cái chiếc cơ DL hôm trước May mà mình không
[00:26:00] chiếc cơ DL hôm trước May mà mình không nói câu đấy Hồi trước mình từng nói có
[00:26:02] nói câu đấy Hồi trước mình từng nói có thể là thích rơi chỉ có 3 loạn nhớ hôm
[00:26:05] thể là thích rơi chỉ có 3 loạn nhớ hôm trước mình không nên nói cái câu chiếc
[00:26:06] trước mình không nên nói cái câu chiếc ơi chỉ có bảo loại mà chích đâu có có 3
[00:26:09] ơi chỉ có bảo loại mà chích đâu có có 3 loại mà mình mình
[00:26:11] loại mà mình mình mình biết chính sao thế
[00:26:14] mình biết chính sao thế anh không Các bạn nhớ cái chị cơ Hôm
[00:26:17] anh không Các bạn nhớ cái chị cơ Hôm trước mình nói nó có chế cơ về log in
[00:26:19] trước mình nói nó có chế cơ về log in đăng nhập này ở
[00:26:21] đăng nhập này ở và
[00:26:22] và after xong ngồi y tế đúng không ạ
[00:26:27] after xong ngồi y tế đúng không ạ Bà hôm đấy mình cũng nói thêm đó là
[00:26:31] Bà hôm đấy mình cũng nói thêm đó là cài after và in search of nó sẽ áp dụng
[00:26:34] cài after và in search of nó sẽ áp dụng với dml nó không tác dụng vừa bql dml
[00:26:38] với dml nó không tác dụng vừa bql dml tức à update Insert Delete đối ngoại
[00:26:42] tức à update Insert Delete đối ngoại và bql tất cả Shake Thì hôm trước mình
[00:26:46] và bql tất cả Shake Thì hôm trước mình trao lại thì đúng là nó còn thêm vào để
[00:26:48] trao lại thì đúng là nó còn thêm vào để d l** Các bạn nhớ DL là gì không ạ
[00:26:52] d l** Các bạn nhớ DL là gì không ạ DL nó sẽ là press
[00:26:56] DL nó sẽ là press enter prop up
[00:27:00] enter prop up tin tức là khi mà các bạn tặng bạc tạo
[00:27:04] tin tức là khi mà các bạn tặng bạc tạo một cái gì đó khác sửa mà cái gì đó hoặc
[00:27:07] một cái gì đó khác sửa mà cái gì đó hoặc cả lốp và
[00:27:09] cả lốp và kiểu gỡ một cái gì bỏ đi đóng lúc bảng
[00:27:12] kiểu gỡ một cái gì bỏ đi đóng lúc bảng help Index là cái gì đó thì cái DL nó
[00:27:16] help Index là cái gì đó thì cái DL nó cũng sẽ chạy thì cái chết rồi này mình
[00:27:20] cũng sẽ chạy thì cái chết rồi này mình thấy khó khăn cực ngắn thành ra là mình
[00:27:21] thấy khó khăn cực ngắn thành ra là mình sẽ không không dạy các bạn và đương
[00:27:25] sẽ không không dạy các bạn và đương nhiên mình như mình nó thì mình sẽ mình
[00:27:28] nhiên mình như mình nó thì mình sẽ mình sẽ dạy buổi hôm nay sẽ là este đâu và
[00:27:31] sẽ dạy buổi hôm nay sẽ là este đâu và vẫn là về đây quy lồ ADN đúng không ạ ạ
[00:27:37] anh không giọng của tôi là từ và Mike đắt tiền lại
[00:27:46] à à ý
[00:27:50] ý thì cái hôm trước chỗ mà các bạn nhớ bộ
[00:27:54] thì cái hôm trước chỗ mà các bạn nhớ bộ hôm trước như thế nào thì hôm nay cũng
[00:27:56] hôm trước như thế nào thì hôm nay cũng sẽ tương tự như thế không em Nhưng mà nó
[00:27:59] sẽ tương tự như thế không em Nhưng mà nó sẽ khắc khác một tí đây mình sẽ cho các
[00:28:02] sẽ khắc khác một tí đây mình sẽ cho các bạn biết thế khác mình lại mở sao lên
[00:28:05] bạn biết thế khác mình lại mở sao lên nhá các bạn lại làm bạn nhìn thấy xe này
[00:28:08] nhá các bạn lại làm bạn nhìn thấy xe này khi cái bài toán hôm trước đó là khi mà
[00:28:12] khi cái bài toán hôm trước đó là khi mà khi mà nó cốt của mình chạy xong được
[00:28:15] khi mà nó cốt của mình chạy xong được rồi Khi mà yêu suốt xong rồi thì mới cập
[00:28:18] rồi Khi mà yêu suốt xong rồi thì mới cập nhật dữ liệu ở bảng kia là không ạ cái
[00:28:20] nhật dữ liệu ở bảng kia là không ạ cái ấm chỉ là kế chiếc cơ nó chạy sau được
[00:28:23] ấm chỉ là kế chiếc cơ nó chạy sau được nó không cần phải can thiệp và chạy
[00:28:25] nó không cần phải can thiệp và chạy trước nó không cần phải kiểm tra không
[00:28:28] trước nó không cần phải kiểm tra không cần phải kiểm tra dữ liệu đúng hay sai
[00:28:30] cần phải kiểm tra dữ liệu đúng hay sai để mà chạy trước hoặc nó chạy sau được
[00:28:32] để mà chạy trước hoặc nó chạy sau được cái trong trường hợp mà cần phải kiểm
[00:28:34] cái trong trường hợp mà cần phải kiểm tra trước thì sao giả sử ở đây là sửa
[00:28:37] tra trước thì sao giả sử ở đây là sửa đây hôm trước thì các bạn nhớ về cái vụ
[00:28:39] đây hôm trước thì các bạn nhớ về cái vụ thật sự có bạn lớp này có mã này có tên
[00:28:42] thật sự có bạn lớp này có mã này có tên này có
[00:28:45] này có số lượng sinh viên Các bạn nhớ không ạ
[00:28:49] số lượng sinh viên Các bạn nhớ không ạ số bệnh như này và ở đây có bạn sinh
[00:28:53] số bệnh như này và ở đây có bạn sinh viên này có mã này có tên này xong ngồi
[00:28:57] viên này có mã này có tên này xong ngồi có mạ lớp này
[00:28:59] có mạ lớp này Đây là sửa là hôm trước là mình làm theo
[00:29:03] Đây là sửa là hôm trước là mình làm theo kiểu như thế này
[00:29:05] kiểu như thế này Nghe thời sự đài mã là một này cái kia
[00:29:08] Nghe thời sự đài mã là một này cái kia này số lượng sinh viên là đang là không
[00:29:11] này số lượng sinh viên là đang là không nhưng mà khi thêm một bạn Long vào trong
[00:29:14] nhưng mà khi thêm một bạn Long vào trong mà lớp là một thì số lượng tăng lên đúng
[00:29:16] mà lớp là một thì số lượng tăng lên đúng không ạ Các bạn nhớ bài bài hôm trước
[00:29:18] không ạ Các bạn nhớ bài bài hôm trước không ạ thì
[00:29:20] không ạ thì ý
[00:29:22] thì cái cái việc là khi mà thêm sinh viên vào thì cập nhật số lượng sinh viên
[00:29:27] viên vào thì cập nhật số lượng sinh viên Nghĩa là bài toán là mình cần nhật trước
[00:29:29] Nghĩa là bài toán là mình cần nhật trước hay cập nhật sau cũng được không quan
[00:29:31] hay cập nhật sau cũng được không quan trọng nghĩa là cái này được thêm chị cái
[00:29:35] trọng nghĩa là cái này được thêm chị cái này được cập nhật để không ạ không an
[00:29:37] này được cập nhật để không ạ không an tâm hài cập nhật trước thằng ngày hay
[00:29:40] tâm hài cập nhật trước thằng ngày hay sau đó nhắc Nếu mà ở Hôm nay thì sẽ làm
[00:29:44] sau đó nhắc Nếu mà ở Hôm nay thì sẽ làm theo kiểu là bắt buộc phải kiểm tra
[00:29:46] theo kiểu là bắt buộc phải kiểm tra trước thay vì để số lượng sinh viên mình
[00:29:48] trước thay vì để số lượng sinh viên mình sẽ là số chỗ trống đi là sự thế là sử là
[00:29:51] sẽ là số chỗ trống đi là sự thế là sử là một lớp thì chỉ được phép có 20 sinh
[00:29:54] một lớp thì chỉ được phép có 20 sinh viên ở ạ
[00:29:56] viên ở ạ bây giờ xử hay mưa như này đúng không ạ
[00:29:58] bây giờ xử hay mưa như này đúng không ạ Cứ mỗi lần thêm một sinh viên mới thì số
[00:30:01] Cứ mỗi lần thêm một sinh viên mới thì số lỗ trống phải làm sao ạ phải giảm nó
[00:30:03] lỗ trống phải làm sao ạ phải giảm nó thành 19 chẳng hạn như thế đúng ạ là sự
[00:30:06] thành 19 chẳng hạn như thế đúng ạ là sự bị thêm một bạn mới nữa nhé À một lớp 10
[00:30:09] bị thêm một bạn mới nữa nhé À một lớp 10 nữa này FPT này 20 này đúng gọn cứ thêm
[00:30:13] nữa này FPT này 20 này đúng gọn cứ thêm một sinh viên nữa vào một lớp thì số lỗ
[00:30:16] một sinh viên nữa vào một lớp thì số lỗ trống phải giảm đi đổ ngoạn A và trong
[00:30:20] trống phải giảm đi đổ ngoạn A và trong trường hợp nào thì mình không thêm một
[00:30:22] trường hợp nào thì mình không thêm một sinh viên mới ạ
[00:30:24] sinh viên mới ạ ở trong trường hợp nào
[00:30:27] à à Ê mấy ông đâu hết rồi
[00:30:35] Ê mấy ông đâu hết rồi anh alo Mày có theo kiểu mày hay tôi
[00:30:39] anh alo Mày có theo kiểu mày hay tôi đang chỉnh
[00:30:51] em hết chỗ chồng nó không ạ số chỗ trống bằng không ạ Đúng rồi Nãy bạn đang mấy
[00:30:56] bằng không ạ Đúng rồi Nãy bạn đang mấy bạn đang trả lời đúng là sổ trống bằng
[00:30:58] bạn đang trả lời đúng là sổ trống bằng không thì mình đã không cho thêm sinh
[00:31:00] không thì mình đã không cho thêm sinh viên mới rồi đúng ạ Mình không cần phải
[00:31:02] viên mới rồi đúng ạ Mình không cần phải sữa trống nhỏ hơn không đúng ạ chỗ trống
[00:31:05] sữa trống nhỏ hơn không đúng ạ chỗ trống bằng không là tốt và mình sẽ phải thông
[00:31:07] bằng không là tốt và mình sẽ phải thông báo trước một cái lỗi gì đó đúng ạ Ok
[00:31:10] báo trước một cái lỗi gì đó đúng ạ Ok thì bây giờ đầu tiên mình cái tạo bảng
[00:31:12] thì bây giờ đầu tiên mình cái tạo bảng như này trước đi rồi ạ
[00:31:13] như này trước đi rồi ạ Nhưng tại bà này
[00:31:17] thì bồ lớp đúng không ạ mã mã tên các thứ
[00:31:23] mã tên các thứ mình không để tự động tăng nhé tím nhập
[00:31:26] mình không để tự động tăng nhé tím nhập mã vào xong rồi thì mình xóa cần thử thử
[00:31:29] mã vào xong rồi thì mình xóa cần thử thử đi nó tiện chỗ trống này
[00:31:32] đi nó tiện chỗ trống này hiểu y ni đúng không ạ cứ tạm bỏ qua phụ
[00:31:35] hiểu y ni đúng không ạ cứ tạm bỏ qua phụ trách chung các hữu thứ II
[00:31:42] Khi mà mình chạy đúng rồi đúng không ạ tiếp theo là mình sẽ có bạn sinh viên
[00:31:48] tiếp theo là mình sẽ có bạn sinh viên mình sẽ có mã lớp
[00:31:52] mình sẽ có mã lớp ở đây sẽ là for key này
[00:31:56] ở đây sẽ là for key này bạn lớp mình sẽ nối khóa ngoại
[00:32:01] bạn lớp mình sẽ nối khóa ngoại lớp tại cục mã này à
[00:32:07] khi con voi bờ bây giờ đến lượt là mình sẽ Insert a disk into lớp này à
[00:32:15] sẽ Insert a disk into lớp này à thì mình sẽ có mã
[00:32:18] thì mình sẽ có mã tên chỗ trống
[00:32:23] tên chỗ trống Alo
[00:32:28] với tròn năm đấy cho ít để mà tí mình lấp đầy nó nhanh nóng bọn mình không cần
[00:32:33] lấp đầy nó nhanh nóng bọn mình không cần lại Insert thận 20 bạn đi làm thì cả
[00:32:36] lại Insert thận 20 bạn đi làm thì cả hai này cái bên đấy cũng có 5 và sự đang
[00:32:39] hai này cái bên đấy cũng có 5 và sự đang có hai lớp bà đều 5 chỗ trống ngoãn Thế
[00:32:43] có hai lớp bà đều 5 chỗ trống ngoãn Thế sao for love trước đi
[00:32:47] sao for love trước đi ê kê các bạn thấy s.de bằng năm rồi mình
[00:32:51] ê kê các bạn thấy s.de bằng năm rồi mình sẽ in xơ cả sinh viên đã
[00:32:54] khi mang thai ở mà lớp đúng
[00:33:00] mang thai ở mà lớp đúng đây là sự đè Long Anh Tuấn Huyền ông ạ
[00:33:05] đây là sự đè Long Anh Tuấn Huyền ông ạ đây sau đây là cùng vào lớp 1 chẳng hạn
[00:33:08] đây sau đây là cùng vào lớp 1 chẳng hạn thế
[00:33:10] thế à à
[00:33:13] à à Ừ thế bạn thấy là bây bây giờ Bây giờ
[00:33:19] Ừ thế bạn thấy là bây bây giờ Bây giờ mình chỉ quan tâm câu select luôn à
[00:33:23] thì các bạn thấy là xuống nó không hề được cập nhật sắp sẵn rồi chưa hề được
[00:33:28] được cập nhật sắp sẵn rồi chưa hề được cập nhật Khi mà mình thêm sinh viên mới
[00:33:30] cập nhật Khi mà mình thêm sinh viên mới là đúng ạ thì thành ra thế này là say
[00:33:33] là đúng ạ thì thành ra thế này là say mất rồi đúng không ạ
[00:33:34] mất rồi đúng không ạ Ừ cái này cái cái này thực tế là
[00:33:38] Ừ cái này cái cái này thực tế là những kẻ thực tế là mình một là mình sẽ
[00:33:42] những kẻ thực tế là mình một là mình sẽ phải luôn cao luôn đếm lại số sinh viên
[00:33:45] phải luôn cao luôn đếm lại số sinh viên ở trong một lớp để mình kiểm tra xem lớp
[00:33:49] ở trong một lớp để mình kiểm tra xem lớp đấy đủ chỗ chồng hay chưa để mà mình nữa
[00:33:51] đấy đủ chỗ chồng hay chưa để mà mình nữa không không cho đi sát vào các thứ thứ
[00:33:54] không không cho đi sát vào các thứ thứ nhưng mà thay vì mỗi lần Thế mình phải
[00:33:56] nhưng mà thay vì mỗi lần Thế mình phải cao nhưng thời gian mất công thì thai
[00:33:58] cao nhưng thời gian mất công thì thai bây giờ mình sẽ lưu lại luôn Hàn 5 chỗ
[00:34:01] bây giờ mình sẽ lưu lại luôn Hàn 5 chỗ trống các thứ thứ sau đó thì mình sẽ có
[00:34:05] trống các thứ thứ sau đó thì mình sẽ có lỗi lầm ý rất vào mình sẽ cập nhật chỗ
[00:34:06] lỗi lầm ý rất vào mình sẽ cập nhật chỗ trống cho cả lớp đấy và mình chỉ kiểm
[00:34:09] trống cho cả lớp đấy và mình chỉ kiểm tra sổ trống cũ thôi đúng không ạ chỗ
[00:34:11] tra sổ trống cũ thôi đúng không ạ chỗ trống cũ thôi không phải sổ chồng mới
[00:34:12] trống cũ thôi không phải sổ chồng mới dọn đấy Thì bây giờ mình sẽ có câu lệnh
[00:34:15] dọn đấy Thì bây giờ mình sẽ có câu lệnh là mình tạm phải delete
[00:34:19] là mình tạm phải delete sinh viên
[00:34:21] sinh viên xóa xóa hết đi nhá Bởi vì chắc chắn ạ
[00:34:23] xóa xóa hết đi nhá Bởi vì chắc chắn ạ Bây giờ nó không còn đúng nữa không ạ
[00:34:26] Bây giờ nó không còn đúng nữa không ạ bây giờ tạm trữ cơ đúng không ạ chích
[00:34:29] bây giờ tạm trữ cơ đúng không ạ chích trên bảng sinh viên rồi Hoặc bời mình
[00:34:32] trên bảng sinh viên rồi Hoặc bời mình thêm sinh viên mà
[00:34:33] thêm sinh viên mà thêm sinh viên này on sinh viên ispace
[00:34:38] thêm sinh viên này on sinh viên ispace a
[00:34:39] a research has revealed and Phạm Liên Khúc
[00:34:44] research has revealed and Phạm Liên Khúc Thi
[00:34:47] Thi cái bài toán ở đây Thực ra nó giống như
[00:34:49] cái bài toán ở đây Thực ra nó giống như hôm trước mình học mình biết rồi đó là
[00:34:52] hôm trước mình học mình biết rồi đó là mình sẽ lấy cột mã lớp từ bản in rất
[00:34:54] mình sẽ lấy cột mã lớp từ bản in rất thực đó ngọn sau đó thì mình sẽ lấy số
[00:34:57] thực đó ngọn sau đó thì mình sẽ lấy số chỗ trống cũ cũng Á đúng ạ
[00:35:01] chỗ trống cũ cũng Á đúng ạ sửa đây năm nó gọi để làm đi đúng ạ là
[00:35:05] sửa đây năm nó gọi để làm đi đúng ạ là sử
[00:35:07] sử em giả sử đay nó như thế mình sẽ lấy chỗ
[00:35:10] em giả sử đay nó như thế mình sẽ lấy chỗ chồng cũ này rồi Kiểm tra xem nó có bằng
[00:35:13] chồng cũ này rồi Kiểm tra xem nó có bằng không ấy Không nó Hoặc
[00:35:15] không ấy Không nó Hoặc nếu nó bằng 0 thì mình sẽ trả về lỗi
[00:35:18] nếu nó bằng 0 thì mình sẽ trả về lỗi luôn đúng không ạ con nếu mà nó khác
[00:35:20] luôn đúng không ạ con nếu mà nó khác không thì mình sẽ phải như nào mình sẽ
[00:35:23] không thì mình sẽ phải như nào mình sẽ phải Insert phải Insert Vì sao rồi vì ký
[00:35:27] phải Insert phải Insert Vì sao rồi vì ký giúp nó thay thế luôn cả công suất mình
[00:35:29] giúp nó thay thế luôn cả công suất mình rồi nghĩa là Xóa hẳn có Kinh Xét Mình
[00:35:31] rồi nghĩa là Xóa hẳn có Kinh Xét Mình rồi nhé khi chích cơ chạy Xong ấy thì
[00:35:34] rồi nhé khi chích cơ chạy Xong ấy thì mình sẽ không ý sớm được đâu nên là mình
[00:35:37] mình sẽ không ý sớm được đâu nên là mình muốn thì mình phải ghi lại câu Insert ấy
[00:35:40] muốn thì mình phải ghi lại câu Insert ấy em mình sẽ thử cho các bạn xem nhé
[00:35:43] em mình sẽ thử cho các bạn xem nhé mình giả sử mình có sẽ lexar for your
[00:35:46] mình giả sử mình có sẽ lexar for your thật để các bạn xem qua bảng này như thế
[00:35:48] thật để các bạn xem qua bảng này như thế nào
[00:35:49] nào chú chạy này
[00:35:51] chú chạy này ở đây mình sẽ mình như hôm trước mình
[00:35:54] ở đây mình sẽ mình như hôm trước mình dậy là cái rất nhiều bản ghi nó sẽ khó
[00:35:57] dậy là cái rất nhiều bản ghi nó sẽ khó gì Sơn một bản ghi không ạ Mình sẽ làm
[00:36:00] gì Sơn một bản ghi không ạ Mình sẽ làm đúng như thế Mình sẽ đi sớm một bản ghi
[00:36:02] đúng như thế Mình sẽ đi sớm một bản ghi trước thì các bạn biết chạy này
[00:36:07] trước thì các bạn biết chạy này Ừ đấy thì các bạn thấy nó sẽ đi xuất
[00:36:09] Ừ đấy thì các bạn thấy nó sẽ đi xuất đúng như thế này những cái gì mình nhập
[00:36:11] đúng như thế này những cái gì mình nhập vào thì nó sẽ và ánh sự thật đúng ạ và
[00:36:13] vào thì nó sẽ và ánh sự thật đúng ạ và các bạn xem lại về selexol fours như này
[00:36:17] các bạn xem lại về selexol fours như này thì các bạn thế à
[00:36:19] thì các bạn thế à anh không hề ý rất được đúng hoặc buồn
[00:36:21] anh không hề ý rất được đúng hoặc buồn vì a như mình đã nói ít of là nó sẽ xóa
[00:36:25] vì a như mình đã nói ít of là nó sẽ xóa nó loại Bỏ hẳn cái câu ý rất mình rồi
[00:36:28] nó loại Bỏ hẳn cái câu ý rất mình rồi nên là nó không nói chuyện là các bạn
[00:36:30] nên là nó không nói chuyện là các bạn vài Insert được đâu thế nên là bây giờ
[00:36:32] vài Insert được đâu thế nên là bây giờ thứ nhất là mình cần làm đây gì mình cần
[00:36:35] thứ nhất là mình cần làm đây gì mình cần ạ Lấy cái mã lớp này là Nhưng mà lớp
[00:36:39] ạ Lấy cái mã lớp này là Nhưng mà lớp mình sẽ giữ vào đúng không ạ sôi lấy
[00:36:41] mình sẽ giữ vào đúng không ạ sôi lấy chồng cũ một cái bạn của cái lớp đấy cho
[00:36:45] chồng cũ một cái bạn của cái lớp đấy cho mình kiểm tra là ngoại mình kiểm tra
[00:36:47] mình kiểm tra là ngoại mình kiểm tra mình sẽ có khái niệm là đi kraddy Tại
[00:36:50] mình sẽ có khái niệm là đi kraddy Tại sao biến
[00:36:51] sao biến số chỗ chấm cũ
[00:36:56] số chỗ chấm cũ anh Thuận chế mình cứ ghi đầy đủ cho nó
[00:37:00] anh Thuận chế mình cứ ghi đầy đủ cho nó chuẩn đi đi clan
[00:37:02] chuẩn đi đi clan mã lớp mà mình sẽ in xơ và không ạ kiểu
[00:37:06] mã lớp mà mình sẽ in xơ và không ạ kiểu này bằng Shake mã love for instance này
[00:37:12] này bằng Shake mã love for instance này đó thì sổ trống cũ sẽ bảng Shake vẫn là
[00:37:17] đó thì sổ trống cũ sẽ bảng Shake vẫn là gửi này
[00:37:19] gửi này bằng Shake số chỗ chấm
[00:37:24] for love where mã bằng hạ lớp này chồng mẹ khá dài không ạ đây Tức tức là
[00:37:35] chồng mẹ khá dài không ạ đây Tức tức là mình sẽ lấy ra như thế này và sau đó thì
[00:37:38] mình sẽ lấy ra như thế này và sau đó thì mình sẽ làm gì mình sẽ kiểm tra lại ít
[00:37:42] mình sẽ làm gì mình sẽ kiểm tra lại ít theo đấy ông ạ là kiểm tra là nếu nếu
[00:37:46] theo đấy ông ạ là kiểm tra là nếu nếu cái sổ trống cũ bằng không thì mình sẽ
[00:37:49] cái sổ trống cũ bằng không thì mình sẽ in ra lỗi
[00:37:52] số chỗ trống cũ bằng không thì mình sẽ Rin ra một cái lỗi gì đó
[00:38:01] là lớp này hãy chỗi trở lại
[00:38:09] cho nơ lòng trước đi chạy thử nhé khi khai báo lỗi vì cái này đã tồn tại
[00:38:16] khi khai báo lỗi vì cái này đã tồn tại Đúng không các bạn crash or enter này ạ
[00:38:22] khi đó bơ mình thường đi sớm này ạ Ừ vậy ăn sát thủ lên sẽ chắc chắn được
[00:38:30] Ừ vậy ăn sát thủ lên sẽ chắc chắn được bể sao bởi rõ ràng là lớp của mình đang
[00:38:33] bể sao bởi rõ ràng là lớp của mình đang có
[00:38:36] em đang có chỗ trống mà đúng không ạ đương nhiên là không không không thông
[00:38:41] đương nhiên là không không không thông báo không thông báo thất bại thôi đúng
[00:38:43] báo không thông báo thất bại thôi đúng không ạ Bên mình thự trong cái eo đấy
[00:38:45] không ạ Bên mình thự trong cái eo đấy thông báo này à
[00:38:47] thông báo này à - xuất thành công đi
[00:38:51] ừ ừ
[00:38:58] A chạy ở 30.000 sẽ lại đi xuất thành công đức
[00:39:04] ở 30.000 sẽ lại đi xuất thành công đức như là mình báo thì cho vui thôi đúng
[00:39:05] như là mình báo thì cho vui thôi đúng không ạ Các bạn thấy rồi đó là mình chưa
[00:39:08] không ạ Các bạn thấy rồi đó là mình chưa chạy lại câu Insert thành ra nó vẫn
[00:39:10] chạy lại câu Insert thành ra nó vẫn không gì xảy ra cả và mình chưa làm vụ
[00:39:13] không gì xảy ra cả và mình chưa làm vụ cập nhật số trông nó không ạ
[00:39:15] cập nhật số trông nó không ạ Ừ
[00:39:16] Ừ nhưng mà bây giờ giả sử mình đi xuất một
[00:39:18] nhưng mà bây giờ giả sử mình đi xuất một cái lớp nào đó thì chắc chắn ạ ạ lớp đấy
[00:39:20] cái lớp nào đó thì chắc chắn ạ ạ lớp đấy không nghe có có chỗ trống mà đi sự đây
[00:39:24] không nghe có có chỗ trống mà đi sự đây web ạ
[00:39:26] web ạ hàng mình đổi đây là không chỗ cho đúng
[00:39:29] hàng mình đổi đây là không chỗ cho đúng không ạ
[00:39:33] à à
[00:39:36] cho anh à khi bơm mini Shark thử bạn lo mình không
[00:39:41] khi bơm mini Shark thử bạn lo mình không đốt thứ ba này các bạn sẽ thấy da lớp
[00:39:44] đốt thứ ba này các bạn sẽ thấy da lớp này hết chỗ rồi đó ngoại thì chị cái lỗi
[00:39:46] này hết chỗ rồi đó ngoại thì chị cái lỗi như thế người dùng dễ hình dung hoặc ạ
[00:39:51] như thế người dùng dễ hình dung hoặc ạ a nhớ bài toán là mình không không phải
[00:39:54] a nhớ bài toán là mình không không phải hiển thị thế cho vui không ạ Bây giờ
[00:39:55] hiển thị thế cho vui không ạ Bây giờ mình cần làm là gì bây giờ giả sử lý rất
[00:39:58] mình cần làm là gì bây giờ giả sử lý rất thành công thì mình phải cần nhờ chỗ
[00:39:59] thành công thì mình phải cần nhờ chỗ trống cho nó còn lúc mình rất thất bại
[00:40:02] trống cho nó còn lúc mình rất thất bại thì thôi bỏ qua đúng không ạ ấy nghĩa là
[00:40:04] thì thôi bỏ qua đúng không ạ ấy nghĩa là mình sẽ phải cập nhật và cái chỗ khi
[00:40:06] mình sẽ phải cập nhật và cái chỗ khi mình giữa thành công này đúng ạ
[00:40:08] mình giữa thành công này đúng ạ thì đây mình sẽ làm gì mình sẽ cần à
[00:40:16] thì mình sẽ cần ở đây đó là mình sẽ phải answer vào và cập nhật lại sổ chỗ chấm
[00:40:22] answer vào và cập nhật lại sổ chỗ chấm đóng ngoặc các bạn thì làm cái nào trước
[00:40:24] đóng ngoặc các bạn thì làm cái nào trước cũng được vợ cập nhật trước sau đó thì
[00:40:27] cũng được vợ cập nhật trước sau đó thì sao cũng được
[00:40:28] sao cũng được bạn trong trường hợp này cập nhật trước
[00:40:30] bạn trong trường hợp này cập nhật trước cũng được đi update lớp này xét chỗ
[00:40:32] cũng được đi update lớp này xét chỗ trống này bằng số chống - một đống vọng
[00:40:38] trống này bằng số chống - một đống vọng Where mã bằng mã lớp
[00:40:42] Where mã bằng mã lớp bạn lớp trên này đúng không
[00:40:45] bạn lớp trên này đúng không và sau đó thì mình sẽ Insert into sinh
[00:40:50] và sau đó thì mình sẽ Insert into sinh viên cái đoạn này mình thấy được ra hơi
[00:40:53] viên cái đoạn này mình thấy được ra hơi mất công một tí
[00:40:54] mất công một tí ở đó sao đó là à
[00:40:58] ở đó sao đó là à cho cây Nếu mà giả sử mà mình làm mới
[00:41:00] cho cây Nếu mà giả sử mà mình làm mới của nông dân Kiếm thứ 2 thì
[00:41:02] của nông dân Kiếm thứ 2 thì Anh ở trong mảng sinh viên có cột nào mà
[00:41:05] Anh ở trong mảng sinh viên có cột nào mà mình sẽ phải
[00:41:07] mình sẽ phải đi clip tương ứng lấy cột Thế mình làm
[00:41:11] đi clip tương ứng lấy cột Thế mình làm mới của nông dân nói như thế này
[00:41:13] mới của nông dân nói như thế này Ừ mình chiếu cốt mã của T nữa bị xử là
[00:41:16] Ừ mình chiếu cốt mã của T nữa bị xử là phải đi clan này
[00:41:18] phải đi clan này mã kiểu này bằng nó cần copy cái đoạn
[00:41:24] mã kiểu này bằng nó cần copy cái đoạn trên này
[00:41:26] trên này các bạn hãy nó sẽ giữ ở mức ông một đoạn
[00:41:28] các bạn hãy nó sẽ giữ ở mức ông một đoạn này
[00:41:30] này vào đây là tên này à
[00:41:33] vào đây là tên này à Anh tên
[00:41:35] Anh tên devit không ạ
[00:41:37] devit không ạ 50 này à
[00:41:39] 50 này à khi mà đây sẽ là
[00:41:43] e-blue
[00:41:47] mã tên nhãn lớp
[00:41:54] đấy như này em mình sẽ thử lại nhé em thành công giống
[00:42:01] em thành công giống em xem lại một con nữa chắc này đang số
[00:42:04] em xem lại một con nữa chắc này đang số lượng ngay các thứ đúng không ạ Đi sớm
[00:42:06] lượng ngay các thứ đúng không ạ Đi sớm này
[00:42:07] này các bạn được để mày cái dâu cập nhật này
[00:42:11] các bạn được để mày cái dâu cập nhật này đưa nó không có đúng không kệ thôi
[00:42:14] đưa nó không có đúng không kệ thôi đó như thế này cái này thì các bạn thấy
[00:42:18] đó như thế này cái này thì các bạn thấy là bị lỗi em bị lỗi đấy bởi vì sao Bởi
[00:42:22] là bị lỗi em bị lỗi đấy bởi vì sao Bởi vì à Mình đang sắp vào tháng thứ 3 thoại
[00:42:25] vì à Mình đang sắp vào tháng thứ 3 thoại vẫn được cập nhật tại sao như thế rõ
[00:42:27] vẫn được cập nhật tại sao như thế rõ ràng là nó Chỗ này hết lớn này hết chỗ
[00:42:30] ràng là nó Chỗ này hết lớn này hết chỗ rồi nó phải ngừng ở đây đúng không ạ lại
[00:42:33] rồi nó phải ngừng ở đây đúng không ạ lại em này phải ngược lại đối ngoại cho eo
[00:42:35] em này phải ngược lại đối ngoại cho eo này nếu mình không dùng đóng ngoặc ngoặc
[00:42:37] này nếu mình không dùng đóng ngoặc ngoặc theo nó không quả bugi về em ấy thì
[00:42:41] theo nó không quả bugi về em ấy thì em này nó sẽ dừng tại đây thôi mà cái
[00:42:45] em này nó sẽ dừng tại đây thôi mà cái đoạn nặng dưới vẫn tự chạy cái bây giờ
[00:42:47] đoạn nặng dưới vẫn tự chạy cái bây giờ mình sẽ phải có đây biggie này
[00:42:50] mình sẽ phải có đây biggie này Mẹ này
[00:42:52] Mẹ này vào đây thế này đi ghi này
[00:42:56] vào đây thế này đi ghi này tên này
[00:42:58] tên này đó lý do mình Tab và như này Các bạn
[00:43:01] đó lý do mình Tab và như này Các bạn nhìn chú chó bên mình lại trả lại phát
[00:43:04] nhìn chú chó bên mình lại trả lại phát nữa này mình tải tạm brady nhá delete
[00:43:07] nữa này mình tải tạm brady nhá delete delete for love luôn đi
[00:43:13] rồi dữ liệu giờ không còn đúng nữa nhà mình phải anh sợ em ạ đó đây mình tạo
[00:43:20] mình phải anh sợ em ạ đó đây mình tạo lại nói chuyện này
[00:43:24] thì các bạn để kỹ lại Nga làm 50 ạ đến sẽ
[00:43:29] các bạn để kỹ lại Nga làm 50 ạ đến sẽ vào này
[00:43:30] vào này lúc này hết chỗ rồi Không đi sớm được
[00:43:33] lúc này hết chỗ rồi Không đi sớm được mày không sẽ được đúng ạ Đổi sang lớp
[00:43:37] mày không sẽ được đúng ạ Đổi sang lớp thứ một này đi sớm lại đi xuất thành
[00:43:39] thứ một này đi sớm lại đi xuất thành công đó ông ạ xem bạn này đó số lượng
[00:43:43] công đó ông ạ xem bạn này đó số lượng thay đổi đúng ạ anh đấy trong y xác thực
[00:43:48] thay đổi đúng ạ anh đấy trong y xác thực ở bển sót được không Bạn này mình nhớ
[00:43:52] ở bển sót được không Bạn này mình nhớ không lầm mình như là bạn bè sinh viên
[00:43:54] không lầm mình như là bạn bè sinh viên cũ mình này đại học trước rồi không
[00:43:57] cũ mình này đại học trước rồi không không không chơi cho họ trước
[00:44:01] Ờ ở chỗ là đại khái nó như thế các bạn vừa rồi cũng hiểu qua cách làm thấy cốt
[00:44:07] vừa rồi cũng hiểu qua cách làm thấy cốt của cái chi cơ Easup này nó dài hơn
[00:44:11] của cái chi cơ Easup này nó dài hơn không ạ dài hơn ở chỗ nào gầy hơn ở thứ
[00:44:14] không ạ dài hơn ở chỗ nào gầy hơn ở thứ nhất à vì phải kiểm tra dữ liệu xem là
[00:44:17] nhất à vì phải kiểm tra dữ liệu xem là nó có hợp lệ hay không đúng không ạ Nếu
[00:44:19] nó có hợp lệ hay không đúng không ạ Nếu mà nếu mà không hợp lệ thì mình nên Hiển
[00:44:22] mà nếu mà không hợp lệ thì mình nên Hiển thị một cái lỗi sau đó không làm gì nữa
[00:44:24] thị một cái lỗi sau đó không làm gì nữa đúng không ạ còn ngược lại là nếu mà hợp
[00:44:27] đúng không ạ còn ngược lại là nếu mà hợp lệ đúng không ạ thì mình có thể thông
[00:44:30] lệ đúng không ạ thì mình có thể thông báo thành công tùy nhưng mà mình phải
[00:44:32] báo thành công tùy nhưng mà mình phải cập nhật lại số lượng cũng như là phải
[00:44:34] cập nhật lại số lượng cũng như là phải phải mất công yêu sót lại
[00:44:37] phải mất công yêu sót lại Ừ đúng rồi phải mất công phải ghi lại có
[00:44:40] Ừ đúng rồi phải mất công phải ghi lại có ý xuất thì các bạn thấy là cái cái cái
[00:44:43] ý xuất thì các bạn thấy là cái cái cái mệt mà mình vừa đề cập ở đây cái mệt
[00:44:47] mệt mà mình vừa đề cập ở đây cái mệt nhất đấy nó lại là cái vụ mà ở trong bạn
[00:44:50] nhất đấy nó lại là cái vụ mà ở trong bạn sinh viên này có bao nhiêu cột thì các
[00:44:52] sinh viên này có bao nhiêu cột thì các bạn sẽ phải tốn về việc là đi claire bao
[00:44:56] bạn sẽ phải tốn về việc là đi claire bao nhiêu lần như này và cái này còn áp dụng
[00:44:58] nhiêu lần như này và cái này còn áp dụng chỉ cho in xuất một mặt ghi thôi nếu mà
[00:45:01] chỉ cho in xuất một mặt ghi thôi nếu mà các bạn nghĩ rất nhiều bạn sinh viên
[00:45:03] các bạn nghĩ rất nhiều bạn sinh viên cùng 1 lúc thì những nhớ hôm trước mình
[00:45:06] cùng 1 lúc thì những nhớ hôm trước mình có đề cập thì dỡ trả lại cái mã lớp nó
[00:45:09] có đề cập thì dỡ trả lại cái mã lớp nó sẽ bây giờ nó sẽ là dạng nhiều ba chị nó
[00:45:13] sẽ bây giờ nó sẽ là dạng nhiều ba chị nó nhiều nhiều mà lớp cùng lúc cho rồi kể
[00:45:15] nhiều nhiều mà lớp cùng lúc cho rồi kể cả ý rất cùng một lớp thì chắc chắn mạnh
[00:45:18] cả ý rất cùng một lớp thì chắc chắn mạnh mã lớp 7 cũng lặp lại mình nhiều nên
[00:45:20] mã lớp 7 cũng lặp lại mình nhiều nên kiểu y là không đúng này Đấy và từ đây
[00:45:23] kiểu y là không đúng này Đấy và từ đây nó sẽ dẫn đến rất nhiều cái dưới nó sẽ
[00:45:25] nó sẽ dẫn đến rất nhiều cái dưới nó sẽ không đúng nữa đúng loạn thành ra có
[00:45:27] không đúng nữa đúng loạn thành ra có chính sách này chỉ hợp cho một bản ý
[00:45:29] chính sách này chỉ hợp cho một bản ý thôi
[00:45:30] thôi tâm tư như này thì các bạn phải là cái
[00:45:34] tâm tư như này thì các bạn phải là cái này thì ra là nhỉ Cái này chỉ áp dụng ở
[00:45:36] này thì ra là nhỉ Cái này chỉ áp dụng ở bên in Ừ đúng ạ Con đi lấy thì sao đi
[00:45:40] bên in Ừ đúng ạ Con đi lấy thì sao đi lấy thì đương nhiên dễ rồi có bạn cho
[00:45:41] lấy thì đương nhiên dễ rồi có bạn cho chạy đi lấy bình thường thôi nhưng mà
[00:45:44] chạy đi lấy bình thường thôi nhưng mà cũng phải cập nhật lại số chỗ trống cho
[00:45:47] cũng phải cập nhật lại số chỗ trống cho họ đúng ạ Các bạn nhiều không ạ thì rõ
[00:45:50] họ đúng ạ Các bạn nhiều không ạ thì rõ ràng là bây giờ sửa xóa đuổi học bạn lo
[00:45:54] ràng là bây giờ sửa xóa đuổi học bạn lo mày đi đúng không ạ thì rõ ràng là số
[00:45:56] mày đi đúng không ạ thì rõ ràng là số chỗ trống này nó không thể Nó còn là bốn
[00:45:58] chỗ trống này nó không thể Nó còn là bốn nữa đúng là nó không có nó 4 nữa nó phải
[00:46:01] nữa đúng là nó không có nó 4 nữa nó phải như thế nào ạ Nó phải nó phải khôi phục
[00:46:03] như thế nào ạ Nó phải nó phải khôi phục lại như cũ đồng bọn nó sẽ phải tăng lên
[00:46:06] lại như cũ đồng bọn nó sẽ phải tăng lên là năm thì cái vụ đấy thì thơ ca không
[00:46:10] là năm thì cái vụ đấy thì thơ ca không cần phải ý sẽ hợp đóng ngoặc
[00:46:12] cần phải ý sẽ hợp đóng ngoặc khi mình không cần phải kiểm tra xem ở
[00:46:15] khi mình không cần phải kiểm tra xem ở kiểu các thứ hấp lễ không mà mình chỉ
[00:46:17] kiểu các thứ hấp lễ không mà mình chỉ đơn giản là gì mình là lấy mã lớp của
[00:46:20] đơn giản là gì mình là lấy mã lớp của những cái bạn mà bị đuổi đấy đúng ạ Mình
[00:46:22] những cái bạn mà bị đuổi đấy đúng ạ Mình sẽ mình sẽ cập nhật lại chỗ trống tăng
[00:46:26] sẽ mình sẽ cập nhật lại chỗ trống tăng lên là xong ngoại nghĩa tăng lên trước
[00:46:29] lên là xong ngoại nghĩa tăng lên trước hay sau không quan trọng Miễn là tăng
[00:46:30] hay sau không quan trọng Miễn là tăng lại cho nó là được không ạ chi cái đấy
[00:46:33] lại cho nó là được không ạ chi cái đấy Mình sẽ dùng à chích cơ after chứ không
[00:46:36] Mình sẽ dùng à chích cơ after chứ không cần phải ứng sẽ được thì đỡ tốn nhiều cả
[00:46:39] cần phải ứng sẽ được thì đỡ tốn nhiều cả mình phải ghi lại câu lệnh thứ đối ngoại
[00:46:41] mình phải ghi lại câu lệnh thứ đối ngoại ạ
[00:46:42] ạ Ừ nhưng mà còn kể vụ Nếu mà giả sử là
[00:46:46] Ừ nhưng mà còn kể vụ Nếu mà giả sử là bạn Long này bạn đấy lại chuyển sang thể
[00:46:48] bạn Long này bạn đấy lại chuyển sang thể lớp mà đang chỗ trống bằng không thì như
[00:46:51] lớp mà đang chỗ trống bằng không thì như thế nào để chọn cái đoạn này lao đầu này
[00:46:54] thế nào để chọn cái đoạn này lao đầu này bạn này cốt dứt dài luôn này nếu để ý kĩ
[00:46:57] bạn này cốt dứt dài luôn này nếu để ý kĩ nhá
[00:46:58] nhá Ờ nếu mà bạn Long đang ở lớp này nó ạ
[00:47:03] Ờ nếu mà bạn Long đang ở lớp này nó ạ Bạn lo đang ở Wow đối ngoại bạn nhảy
[00:47:07] Bạn lo đang ở Wow đối ngoại bạn nhảy sang p mpp hết chỗ trống rồi đúng không
[00:47:10] sang p mpp hết chỗ trống rồi đúng không ạ thì
[00:47:12] ạ thì Ừ thì rõ ràng là không cho nó đổi đúng ạ
[00:47:15] Ừ thì rõ ràng là không cho nó đổi đúng ạ thực tế là như thế còn bây giờ nếu mà
[00:47:18] thực tế là như thế còn bây giờ nếu mà mình Viết cốt đấy thì mình sẽ phải kiểm
[00:47:20] mình Viết cốt đấy thì mình sẽ phải kiểm tra chỗ trống của cái lớp mới đóng ngoặc
[00:47:23] tra chỗ trống của cái lớp mới đóng ngoặc cả lớp mà bạn ấy sẽ nhảy sang là chỗ
[00:47:26] cả lớp mà bạn ấy sẽ nhảy sang là chỗ trống là bằng bằng bao nhiêu không ạ Nếu
[00:47:28] trống là bằng bằng bao nhiêu không ạ Nếu Bằng không thì dao bằng không thì mình
[00:47:30] Bằng không thì dao bằng không thì mình lại phải Insert lại vào gái
[00:47:33] lại phải Insert lại vào gái à không không không không cần in shop
[00:47:36] à không không không không cần in shop bởi vì yêu sẽ được thay thế mất rồi
[00:47:39] bởi vì yêu sẽ được thay thế mất rồi khi đun nóng không không cần ấy sẽ lại
[00:47:42] khi đun nóng không không cần ấy sẽ lại nó nó vẫn sẽ thì mình cần giữ nguyên
[00:47:43] nó nó vẫn sẽ thì mình cần giữ nguyên thôi mình thật Tự nhiên thôi còn nếu là
[00:47:46] thôi mình thật Tự nhiên thôi còn nếu là ra sự mà thành công thì đúng là mình
[00:47:48] ra sự mà thành công thì đúng là mình phải cập nhật lại cái thằng chỗ chấm này
[00:47:51] phải cập nhật lại cái thằng chỗ chấm này phải tăng tăng nó lại lên thành 5 này
[00:47:52] phải tăng tăng nó lại lên thành 5 này đâu ạ và thằng này thành một như thế này
[00:47:56] đâu ạ và thằng này thành một như thế này á Không không trăm trang trong trường
[00:47:58] á Không không trăm trang trong trường hợp đúng nhá trong trường hợp đúng thì
[00:48:00] hợp đúng nhá trong trường hợp đúng thì nó sẽ thành công hay gì đó bọn
[00:48:03] nó sẽ thành công hay gì đó bọn mình thì thử luôn nhỉ nói nhiều thì hơi
[00:48:08] mình thì thử luôn nhỉ nói nhiều thì hơi bị lý thuyết quá
[00:48:10] bị lý thuyết quá xưởng sinh viên này
[00:48:13] xưởng sinh viên này là sử mình cứ đổi bạn từ
[00:48:16] là sử mình cứ đổi bạn từ bạn từ
[00:48:18] bạn từ lớp 11 xa nước thứ ba rồi em được không
[00:48:21] lớp 11 xa nước thứ ba rồi em được không nó không ạ
[00:48:22] nó không ạ on sinh viên này
[00:48:25] on sinh viên này mấy ông ấy giờ có vẫn hiểu ông ấy nếu đi
[00:48:29] mấy ông ấy giờ có vẫn hiểu ông ấy nếu đi lặng mà không biết mấy ông có tài mà
[00:48:31] lặng mà không biết mấy ông có tài mà không được buồn mà ừ
[00:48:38] ừ ừ
[00:48:41] anh em mình sẽ lấy số à Lấy mã lớp từ bảng
[00:48:46] bảng Ừ từ bảng mà mình sẽ kiểu
[00:48:49] Ừ từ bảng mà mình sẽ kiểu Ừ Từ từ
[00:48:51] Ừ Từ từ ở đây sao mình cứ thử select from list
[00:48:56] ở đây sao mình cứ thử select from list và xếp xà phòng đi tất cả bạn dễ hình
[00:48:59] và xếp xà phòng đi tất cả bạn dễ hình dung địa ạ
[00:49:02] thế này A chạy
[00:49:05] A chạy à à
[00:49:08] à à 3.hd sinh vn sex đã lớn bằng
[00:49:14] 3.hd sinh vn sex đã lớn bằng 3-way mã sinh viên Mã sinh viên nước
[00:49:18] 3-way mã sinh viên Mã sinh viên nước ngoài mãi một này à
[00:49:22] ngoài mãi một này à A chạy
[00:49:24] A chạy Sau đó các bạn thấy là
[00:49:26] Sau đó các bạn thấy là khi tóc bạn insta tết thì tức à Cái dữ
[00:49:29] khi tóc bạn insta tết thì tức à Cái dữ liệu mới của bạn đấy sẽ thay thế lại
[00:49:32] liệu mới của bạn đấy sẽ thay thế lại bằng 350 cũ là bằng một đúng không Thì
[00:49:35] bằng 350 cũ là bằng một đúng không Thì Tức là mình phải kiểm tra cái chỗ trống
[00:49:37] Tức là mình phải kiểm tra cái chỗ trống của của cái lý bạn lớp ở trong mạng xác
[00:49:41] của của cái lý bạn lớp ở trong mạng xác thật đúng không ạ
[00:49:43] thật đúng không ạ đề tài đi Clans
[00:49:47] mã lớp mới bằng kiểu này bằng như này rồi bây nhiêu lần
[00:49:56] kiểu này bằng như này rồi bây nhiêu lần này mình sẽ lách mà lớp này
[00:49:59] này mình sẽ lách mà lớp này tương tự Thế thì sẽ có ở đây em ạ lớp cũ
[00:50:03] tương tự Thế thì sẽ có ở đây em ạ lớp cũ này
[00:50:06] ngày để tật này
[00:50:11] thực à là cái đoạn lấy mà lớp cũ này chưa cần làm vội mà mình cần làm ở đây
[00:50:16] chưa cần làm vội mà mình cần làm ở đây là gì mình cứ ghi nó pass để các bạn dễ
[00:50:19] là gì mình cứ ghi nó pass để các bạn dễ hình dung nhé
[00:50:20] hình dung nhé Lấy mã lớp mới
[00:50:23] Lấy mã lớp mới tư bản ký sự thật này
[00:50:27] tư bản ký sự thật này in search vật
[00:50:32] lấy số chỗ chấm
[00:50:36] từ lớp mới công ạ từ lớp theo mã lớp mới đi à cách kiểm
[00:50:44] từ lớp theo mã lớp mới đi à cách kiểm tra số chỗ trống
[00:50:47] tra số chỗ trống bằng không Đây là tôi tôi đang chỉ mới
[00:50:51] bằng không Đây là tôi tôi đang chỉ mới phong cách kiểu diễn giải cốt theo kiểu
[00:50:54] phong cách kiểu diễn giải cốt theo kiểu là Đây gọi là gì
[00:50:56] là Đây gọi là gì cốc giả có ra cũng không đúng lắm Tôi
[00:51:01] cốc giả có ra cũng không đúng lắm Tôi nhớ cách nói cậu đây có là một hình thức
[00:51:04] nhớ cách nói cậu đây có là một hình thức kiểu cho toàn lập trình hết á
[00:51:07] kiểu cho toàn lập trình hết á ở đây là không Mình quân xử cách gọi cái
[00:51:11] ở đây là không Mình quân xử cách gọi cái này là gì rồi nghe Nói chung nó sẽ giúp
[00:51:13] này là gì rồi nghe Nói chung nó sẽ giúp bằng ngôn ngữ tự nhiên
[00:51:15] bằng ngôn ngữ tự nhiên anh kiểm tra chỗ trống bằng không ạ thì
[00:51:18] anh kiểm tra chỗ trống bằng không ạ thì à nếu nếu đúng không ạ Nếu đúng
[00:51:22] thì mình sẽ làm gì nếu đúng thì mình sẽ mình chỉ việc là thông báo lỗi đúng ạ
[00:51:29] mình chỉ việc là thông báo lỗi đúng ạ thông báo lỗi thế thôi ông ạ Còn nếu sai
[00:51:33] thông báo lỗi thế thôi ông ạ Còn nếu sai thì sao Nếu sai thì
[00:51:36] thì sao Nếu sai thì Ừ
[00:51:37] Ừ nếu sai thì mình sẽ lấy mã
[00:51:42] nếu sai thì mình sẽ lấy mã ở thời tiết là lấy lấy mạ lớp mới này
[00:51:48] mà không thấy mặt đâu đó bình tĩnh anh ở đây mình sẽ cập nhật trước đi cập
[00:51:54] anh ở đây mình sẽ cập nhật trước đi cập nhật số chỗ chấm
[00:51:58] 3 - 1 theo mã lớp mới I
[00:52:05] khi mà đây sẽ là lấy mã lớp phủ này từ bạn để lực
[00:52:13] từ bạn để lực và mình cập nhật chỗ chấm
[00:52:16] và mình cập nhật chỗ chấm khi cộng một bóng mạnh
[00:52:19] khi cộng một bóng mạnh theo mà lớp cũ
[00:52:21] theo mà lớp cũ và sau đó thì bây giờ mới là một loa cái
[00:52:25] và sau đó thì bây giờ mới là một loa cái việc là mình delete
[00:52:30] anh à không Mình có thể không phải đi lép âm in search mình chỉ ra updates
[00:52:35] lép âm in search mình chỉ ra updates cũng được
[00:52:37] cũng được ở những cái việc
[00:52:39] ở những cái việc chỉ là ấp lết các bạn còn đôi khi đôi
[00:52:42] chỉ là ấp lết các bạn còn đôi khi đôi khi không biết được là cái cái updates
[00:52:45] khi không biết được là cái cái updates này nó không áp tiếp mã lớp Nó tết mũi
[00:52:47] này nó không áp tiếp mã lớp Nó tết mũi tên mà nó thôi thì sao đúng ạ thì rõ ra
[00:52:50] tên mà nó thôi thì sao đúng ạ thì rõ ra mấy cái này nó lại hơi bị sai sai tí
[00:52:58] Ừ Để tôi giải thích tại sao sai biệt là sử
[00:53:02] Để tôi giải thích tại sao sai biệt là sử bây giờ nhá trong trường hợp này tôi đổi
[00:53:04] bây giờ nhá trong trường hợp này tôi đổi một tên bằng
[00:53:06] một tên bằng nóng hacker em ạ
[00:53:08] nóng hacker em ạ thì rõ ràng có liên quan việc là lớp lớp
[00:53:11] thì rõ ràng có liên quan việc là lớp lớp tôi cần thay đổi đâu đúng không ạ lớp
[00:53:13] tôi cần thay đổi đâu đúng không ạ lớp tôi vẫn giữ nguyên mà nó không ạ thì tự
[00:53:15] tôi vẫn giữ nguyên mà nó không ạ thì tự nhiên lại Cập nhật lại mã lớp của tôi
[00:53:18] nhiên lại Cập nhật lại mã lớp của tôi làm gì đúng không ạ thì bây giờ trong
[00:53:20] làm gì đúng không ạ thì bây giờ trong trường hợp cái dễ cái dễ của tôi thường
[00:53:23] trường hợp cái dễ cái dễ của tôi thường này làm đấy thì mình sẽ luôn lại xóa
[00:53:27] này làm đấy thì mình sẽ luôn lại xóa anh xóa sinh viên nó đi theo lớp theo mã
[00:53:30] anh xóa sinh viên nó đi theo lớp theo mã thì nó sẽ luôn Đúng này Xóa sinh viên
[00:53:33] thì nó sẽ luôn Đúng này Xóa sinh viên theo mã
[00:53:34] theo mã mã này lấy từ đâu mã này đứng và lấy từ
[00:53:38] mã này lấy từ đâu mã này đứng và lấy từ yz thật thể đi hết thật cũng được bởi vì
[00:53:41] yz thật thể đi hết thật cũng được bởi vì rõ ra là mình không cho phép ra sự mình
[00:53:43] rõ ra là mình không cho phép ra sự mình không chọn không cho phép đổi mã
[00:53:47] không chọn không cho phép đổi mã Ừ thì mã sinh viên nó sẽ là duy nhất của
[00:53:49] Ừ thì mã sinh viên nó sẽ là duy nhất của bọn mình sẽ xóa sinh viên Mã rồi mình sẽ
[00:53:52] bọn mình sẽ xóa sinh viên Mã rồi mình sẽ in sót lại
[00:53:54] in sót lại sinh viên Đông ạ theo toàn toàn bộ dữ
[00:54:00] sinh viên Đông ạ theo toàn toàn bộ dữ liệu
[00:54:01] liệu lấy từ chính xác thực
[00:54:04] lấy từ chính xác thực tại đoạn này bay não này
[00:54:07] tại đoạn này bay não này về bản chất Các bạn nhớ vụ update nó sẽ
[00:54:10] về bản chất Các bạn nhớ vụ update nó sẽ bằng gì họ update sẽ bằng Delete + visa
[00:54:14] bằng gì họ update sẽ bằng Delete + visa mà không ạ
[00:54:16] mà không ạ thì đấy tội đang làm đúng như thế đấy Đó
[00:54:19] thì đấy tội đang làm đúng như thế đấy Đó là như thế này và ít lại khi nó sẽ hợp
[00:54:23] là như thế này và ít lại khi nó sẽ hợp lý hơn để các bạn đỡ phải kiểm tra xem
[00:54:26] lý hơn để các bạn đỡ phải kiểm tra xem nó rõ ra là nó update nó biết những cột
[00:54:29] nó rõ ra là nó update nó biết những cột nào những trường nào đúng ạ phức tạp ta
[00:54:32] nào những trường nào đúng ạ phức tạp ta thì mình sẽ làm thì cậu như thế này
[00:54:33] thì mình sẽ làm thì cậu như thế này không ạ Không có vảy dày đấy ông ạ mã
[00:54:38] không ạ Không có vảy dày đấy ông ạ mã giả
[00:54:39] giả ở
[00:54:40] ở đây thì mình sẽ ít ở đây đó ạ Ở đâu thấy
[00:54:44] đây thì mình sẽ ít ở đây đó ạ Ở đâu thấy chỗ trống trước decrit số chỗ chấm Cái
[00:54:48] chỗ trống trước decrit số chỗ chấm Cái này
[00:54:49] này cái này
[00:54:53] snack xuống chỗ trống home
[00:54:59] a list for love chứ phòng lớp Where mã bằng mã lớp mới
[00:55:06] bằng mã lớp mới sau đỏ đít chỗ trống bằng không thì ghi
[00:55:11] sau đỏ đít chỗ trống bằng không thì ghi này e này mình thông báo cái lỗi luôn
[00:55:15] này e này mình thông báo cái lỗi luôn không ạ
[00:55:17] ở lớp này hết chỗ rồi ông ngoại
[00:55:24] ở đó xong yêu đây lại đi ghi này em này
[00:55:29] đó xong yêu đây lại đi ghi này em này cho mình biết hết cốt ở trong này đây
[00:55:32] cho mình biết hết cốt ở trong này đây với ngược lại thì mình sẽ làm gì mình sẽ
[00:55:35] với ngược lại thì mình sẽ làm gì mình sẽ cập nhật số chỗ trống đấy đúng không ạ
[00:55:39] cập nhật số chỗ trống đấy đúng không ạ Mình sẽ update
[00:55:41] Mình sẽ update lớp sét số chỗ trống
[00:55:48] Ờ như bạn kia làm nhanh thì nó sẽ trừ một ngày cũng được khi kiểu này sẽ bằng
[00:55:55] một ngày cũng được khi kiểu này sẽ bằng chỗ trống - mồ thôi đúng không ạ
[00:55:58] chỗ trống - mồ thôi đúng không ạ Where mã bằng mã lớp mở mới
[00:56:03] Where mã bằng mã lớp mở mới vào đây lấy cái mà lớp cũ này Sao lại
[00:56:06] vào đây lấy cái mà lớp cũ này Sao lại cập nhật đó ông ạ
[00:56:07] cập nhật đó ông ạ em copy này
[00:56:12] cũ này
[00:56:16] và bây giờ mình sẽ xóa sinh viên không ạ Mình sẽ là Blade for sinh viên
[00:56:24] Mình sẽ là Blade for sinh viên Where mã bằng
[00:56:27] Where mã bằng có thể các bạn không cần phải khai báo
[00:56:30] có thể các bạn không cần phải khai báo biến các bạn ghi kiểu này cho nhanh cũng
[00:56:31] biến các bạn ghi kiểu này cho nhanh cũng được Sứ Mệnh mã for a
[00:56:35] được Sứ Mệnh mã for a à
[00:56:36] à à directed
[00:56:39] à directed đó sau đó nhưng mình lại chạy cay rát
[00:56:43] đó sau đó nhưng mình lại chạy cay rát không ạ
[00:56:44] không ạ Insert into sinh viên này
[00:56:50] mã tên và mặt lớp ba lô
[00:57:01] cái đoạn này rất rất dài này các bạn sẽ thấy là mình mình bản chất là mình lấy
[00:57:07] thấy là mình mình bản chất là mình lấy đúng mỗi mã lớp mới đúng không ạ thế
[00:57:10] đúng mỗi mã lớp mới đúng không ạ thế Mình chưa đi từ hai cái này là Sử là cái
[00:57:13] Mình chưa đi từ hai cái này là Sử là cái thằng mã của sinh viên không thay đổi
[00:57:15] thằng mã của sinh viên không thay đổi thì mình cứ đi lại ở trên này chứ lại
[00:57:17] thì mình cứ đi lại ở trên này chứ lại nhá mình đi cờ lê ở trên này đi Ừ
[00:57:21] nhá mình đi cờ lê ở trên này đi Ừ à à
[00:57:22] à à a mã sinh viên hải ngoại in
[00:57:28] ra cái này không quan trọng đi là sự thế mình đây đổi đổi đây mã sinh viên Giả sử
[00:57:35] mình đây đổi đổi đây mã sinh viên Giả sử Trong trường hợp mã sinh chứ không thay
[00:57:36] Trong trường hợp mã sinh chứ không thay đổi nhá Thì mình vẫn phải thêm một lần
[00:57:39] đổi nhá Thì mình vẫn phải thêm một lần nữa phải đi trở lại nên
[00:57:45] selected from xác thực
[00:57:51] cái tên mã lớp này à
[00:57:58] Anh không thể nào thế rất dài không ạ ở đoạn này mình sẽ hướng dẫn các bạn có
[00:58:05] ở đoạn này mình sẽ hướng dẫn các bạn có thể nhắn rất rất nhiều
[00:58:08] đây press enter này như là để các bạn làm được cái nhắn thế
[00:58:16] như là để các bạn làm được cái nhắn thế các bạn phải hiểu được cái cơ bản đã
[00:58:17] các bạn phải hiểu được cái cơ bản đã không ạ Mày hiểu cơ bản đã đây mình đã
[00:58:20] không ạ Mày hiểu cơ bản đã đây mình đã hướng dẫn xong đây đầy đủ các bạn ơi ơi
[00:58:23] hướng dẫn xong đây đầy đủ các bạn ơi ơi mình thử update nhé các bạn thấy
[00:58:26] mình thử update nhé các bạn thấy nhà báo nhà được bảo không quan trọng
[00:58:28] nhà báo nhà được bảo không quan trọng nữa đâu mà mình phải xem lại thực sự nói
[00:58:30] nữa đâu mà mình phải xem lại thực sự nói như nào
[00:58:32] như nào có cắn có cách để tắt cái báo đi
[00:58:35] có cắn có cách để tắt cái báo đi khi sex
[00:58:37] khi sex à À đây đi xe mày
[00:58:39] à À đây đi xe mày em đổi sinh viên Sang
[00:58:42] em đổi sinh viên Sang Ừ đấy các bạn thấy đổi sinh viên kiểu
[00:58:45] Ừ đấy các bạn thấy đổi sinh viên kiểu ngay đúng
[00:58:47] ngay đúng nghe rõ là mình không đổi mà lớp thành
[00:58:50] nghe rõ là mình không đổi mà lớp thành ra là số lượng sổ xố chống nó vừa thay
[00:58:53] ra là số lượng sổ xố chống nó vừa thay đổi đấy nó là tăng lên lại năm xong rồi
[00:58:56] đổi đấy nó là tăng lên lại năm xong rồi nói lại giảm đi đấy nên thành ra là các
[00:58:58] nói lại giảm đi đấy nên thành ra là các bạn hãy nó vẫn giữ nguyên đúng không ạ
[00:59:00] bạn hãy nó vẫn giữ nguyên đúng không ạ Nhưng giờ mình thử đổi mã lớp Xem đổi mã
[00:59:03] Nhưng giờ mình thử đổi mã lớp Xem đổi mã lớp bằng 3 - hạ trại này
[00:59:06] lớp bằng 3 - hạ trại này từ lúc này hết chỗ rồi đúng không ạ Các
[00:59:09] từ lúc này hết chỗ rồi đúng không ạ Các bạn thấy là sinh viên Vẫn như thế chả gì
[00:59:11] bạn thấy là sinh viên Vẫn như thế chả gì thay đổi cả đúng không ạ bé đổi mã lỡ
[00:59:13] thay đổi cả đúng không ạ bé đổi mã lỡ Sao mạng hay được ạ như này
[00:59:17] Sao mạng hay được ạ như này thì các bạn thấy là Ok ngon rồi nó nhọn
[00:59:21] thì các bạn thấy là Ok ngon rồi nó nhọn Anh tốt này nó khá là dài một tí không
[00:59:24] Anh tốt này nó khá là dài một tí không là khá là được rất là giỏi đấy và như
[00:59:28] là khá là được rất là giỏi đấy và như mình đã nói toàn bộ Cái này kiến thức
[00:59:30] mình đã nói toàn bộ Cái này kiến thức đây mới trẻ cơ bản
[00:59:33] đây mới trẻ cơ bản Ừ ông lão thầy choáng quá sim ông nên
[00:59:36] Ừ ông lão thầy choáng quá sim ông nên dừng lại đến loại này được rồi Bây giờ
[00:59:38] dừng lại đến loại này được rồi Bây giờ tôi nhảy sang cái nâng cao Mày không
[00:59:39] tôi nhảy sang cái nâng cao Mày không muốn sáng hơn này
[00:59:41] muốn sáng hơn này ok đấy vừa rồi là giải quyết xong toàn
[00:59:44] ok đấy vừa rồi là giải quyết xong toàn bộ với cơ bản và rất là dài dòng các bạn
[00:59:46] bộ với cơ bản và rất là dài dòng các bạn thế à Nó rất là nông dân nữa dài đúng
[00:59:48] thế à Nó rất là nông dân nữa dài đúng không ạ
[00:59:49] không ạ bây bây giờ mới nhảy sang cái hay hơn và
[00:59:54] bây bây giờ mới nhảy sang cái hay hơn và phức tạp hơn này rất là giả sự là bây
[00:59:56] phức tạp hơn này rất là giả sự là bây giờ mình sẽ đi sớm đi đúng không ạ
[00:59:58] giờ mình sẽ đi sớm đi đúng không ạ thì mình sẽ in search
[01:00:02] thì mình sẽ in search rất nhiều sinh viên cùng 1 lúc thì mình
[01:00:04] rất nhiều sinh viên cùng 1 lúc thì mình sẽ như thế nào
[01:00:09] khi tôi thấy cốt này dài quá tôi phép xóa đi nhé mấy ông mấy ông có xem lại
[01:00:16] xóa đi nhé mấy ông mấy ông có xem lại được mà không phải không xem lại sau nha
[01:00:18] được mà không phải không xem lại sau nha Tôi nhìn cốt này cho tôi lại sợ lắm
[01:00:22] Tôi nhìn cốt này cho tôi lại sợ lắm Bây giờ
[01:00:24] Bây giờ mình cứ Delete hết đi này xuống chơi này
[01:00:28] mình cứ Delete hết đi này xuống chơi này ông ạ thì sẽ tại lớp này không ạ Bây giờ
[01:00:32] ông ạ thì sẽ tại lớp này không ạ Bây giờ giả sử là mình sẽ Insert hai sinh viên
[01:00:34] giả sử là mình sẽ Insert hai sinh viên cùng 1 lúc thì mình sẽ làm như thế nào
[01:00:36] cùng 1 lúc thì mình sẽ làm như thế nào để không ạ
[01:00:41] Cái cái bài toán ở đây ừ ừ vì thế bài toán ở đây nó khá phức tạp
[01:00:47] vì thế bài toán ở đây nó khá phức tạp AE theo kiểu như thế này ờ
[01:00:53] à à à à
[01:00:56] à à Vì
[01:00:56] Vì vậy bây giờ đấy thường là mình sẽ làm
[01:00:59] vậy bây giờ đấy thường là mình sẽ làm theo cách kiểu nhà cho nó dễ đi ra xử là
[01:01:02] theo cách kiểu nhà cho nó dễ đi ra xử là mình đi Shop mình Mị mình có thể là
[01:01:06] mình đi Shop mình Mị mình có thể là Issac
[01:01:07] Issac nhiều sinh viên vào cùng một lớp Giả sử
[01:01:11] nhiều sinh viên vào cùng một lớp Giả sử Mỹ rất 6 sinh viên và cùng một lớp đúng
[01:01:13] Mỹ rất 6 sinh viên và cùng một lớp đúng không ạ 6 sinh viên và cả lớp này đi đồ
[01:01:16] không ạ 6 sinh viên và cả lớp này đi đồ ngoại thì chuẩn nhá chuẩn hairogy của
[01:01:20] ngoại thì chuẩn nhá chuẩn hairogy của thực tế Đúng đó là mình sẽ in xuất làm
[01:01:23] thực tế Đúng đó là mình sẽ in xuất làm bạn rồi loại đi mỗi bạn
[01:01:25] bạn rồi loại đi mỗi bạn đúng đúng đúng ạ
[01:01:28] đúng đúng đúng ạ ơi các bạn hãy hình dung bài toán đây
[01:01:30] ơi các bạn hãy hình dung bài toán đây không ạ Đó là do sự mà mình đi rất 6
[01:01:32] không ạ Đó là do sự mà mình đi rất 6 Sinh viên vào lớp Amway mà rõ là số của
[01:01:35] Sinh viên vào lớp Amway mà rõ là số của chồng 150 ạ thì mình theo lôgic mình cần
[01:01:38] chồng 150 ạ thì mình theo lôgic mình cần làm là gì ạ Mình sẽ chỉn suốt năm bạn
[01:01:40] làm là gì ạ Mình sẽ chỉn suốt năm bạn đúng ạ và thông báo là một bạn bị lỗi
[01:01:43] đúng ạ và thông báo là một bạn bị lỗi đúng ạ
[01:01:45] đúng ạ cái cách đấy mình thời gian mình vẫn làm
[01:01:47] cái cách đấy mình thời gian mình vẫn làm được như nó sẽ lại phức tạp một tí đúng
[01:01:50] được như nó sẽ lại phức tạp một tí đúng không ạ Có làm cái kiểu đơn giản hơn một
[01:01:53] không ạ Có làm cái kiểu đơn giản hơn một tí đó là mình
[01:01:55] tí đó là mình Ừ mình cư đến kiểm tra xem là có bao
[01:01:59] Ừ mình cư đến kiểm tra xem là có bao nhiêu sinh viên vào lớp ABC rét đã đầu
[01:02:01] nhiêu sinh viên vào lớp ABC rét đã đầu ngon nếu mà không Nếu mà kiểu nó bị vượt
[01:02:05] ngon nếu mà không Nếu mà kiểu nó bị vượt ngưỡng mình thông báo lỗi luôn để thường
[01:02:08] ngưỡng mình thông báo lỗi luôn để thường là cách đấy nhiều phần mềm bây giờ lại
[01:02:11] là cách đấy nhiều phần mềm bây giờ lại đang áp dụng theo kiểu là làm thế chứng
[01:02:13] đang áp dụng theo kiểu là làm thế chứng anh kết hợp việc là cho người dùng kiểm
[01:02:15] anh kết hợp việc là cho người dùng kiểm tra lại chắc chắn mới đúng hết đã ở to
[01:02:17] tra lại chắc chắn mới đúng hết đã ở to cho mày nhưng xét một lượt hãy cậu thế
[01:02:21] cho mày nhưng xét một lượt hãy cậu thế Ừ đúng rồi chuẩn là bây giờ mình sẽ phải
[01:02:23] Ừ đúng rồi chuẩn là bây giờ mình sẽ phải đến đến số lượng sinh viên rồi mình roi
[01:02:26] đến đến số lượng sinh viên rồi mình roi các hư thứ bởi vì vẫn bài toán ở đây là
[01:02:29] các hư thứ bởi vì vẫn bài toán ở đây là vẫn bài toán mình phải kiểm tra xem số
[01:02:31] vẫn bài toán mình phải kiểm tra xem số lỗ chồng có thỏa mãn hay không mà đúng
[01:02:32] lỗ chồng có thỏa mãn hay không mà đúng không ạ thì bây giờ xử lý rất nhiều thì
[01:02:34] không ạ thì bây giờ xử lý rất nhiều thì tự nhiên mình phải đếm nóng bạn phải đến
[01:02:37] tự nhiên mình phải đếm nóng bạn phải đến xem là bao nhiêu sinh viên sẽ vào lớp A
[01:02:39] xem là bao nhiêu sinh viên sẽ vào lớp A bao nhiêu sinh viên sẽ vào lớp bê cái sổ
[01:02:42] bao nhiêu sinh viên sẽ vào lớp bê cái sổ chỗ trống của lớp A và lớp B đấy nó có
[01:02:44] chỗ trống của lớp A và lớp B đấy nó có đủ thỏa mãn hay không đúng không ạ Để em
[01:02:47] đủ thỏa mãn hay không đúng không ạ Để em ý xốt vào
[01:02:48] ý xốt vào em gái
[01:02:50] em gái thì các bạn hiểu được Nãy giờ mình nói
[01:02:52] thì các bạn hiểu được Nãy giờ mình nói không
[01:02:56] nói cái đấy xong khó hiểu quá không ạ anh hiểu được câu này đã chưa cắt hiểu
[01:03:02] anh hiểu được câu này đã chưa cắt hiểu mình sẽ Cốt nhạc hiểu được cái quy chỉnh
[01:03:05] mình sẽ Cốt nhạc hiểu được cái quy chỉnh quy trình mình xử lý một bài toán đi ạ
[01:03:07] quy trình mình xử lý một bài toán đi ạ Đóng lại
[01:03:10] Đóng lại vì số lượng Xem giám đốc
[01:03:13] vì số lượng Xem giám đốc đến đoạn nâng cao tạo được ok ở
[01:03:19] chỗ nào Bây giờ mình cần lấy đầu tiên mình cần như hôm trước mình làm
[01:03:26] đầu tiên mình cần như hôm trước mình làm thôi đó là mình sẽ đến đến xem với từng
[01:03:29] thôi đó là mình sẽ đến đến xem với từng lớp đúng không ạ
[01:03:30] lớp đúng không ạ select mã lớp này và cao sao cho này
[01:03:36] select mã lớp này và cao sao cho này for instance
[01:03:39] for instance ai mình chạy thử nhé
[01:03:45] xin lỗi gì ừ ừ
[01:03:54] anh cao sao à Như Cuba muốn mở lớp à
[01:04:02] khi đó về mình như shop này Em nói như này đúng không anh sẽ áp là
[01:04:08] Em nói như này đúng không anh sẽ áp là số lượng sinh viên
[01:04:14] sẽ thêm này tên rất dài Đông ạ cho dễ hiểu à
[01:04:20] hiểu à anh chạy lên à
[01:04:23] anh chạy lên à khi đó nghĩa là bây giờ sẽ có hai bạn
[01:04:25] khi đó nghĩa là bây giờ sẽ có hai bạn bảo lớp 10 ạ đấy
[01:04:31] bảo lớp 10 ạ đấy
[01:04:31] anh mới chịu mình mình sẽ nhìn xếp theo kiểu từng lớp một đã nhé Ừ thôi tí ở sẽ
[01:04:36] kiểu từng lớp một đã nhé Ừ thôi tí ở sẽ nhiều lớp cùng một lúc nữa Nói chung là
[01:04:39] nhiều lớp cùng một lúc nữa Nói chung là cứ phải nâng cao nâng cao dần không ạ
[01:04:40] cứ phải nâng cao nâng cao dần không ạ thì ở trong trường hợp này các bạn thấy
[01:04:43] thì ở trong trường hợp này các bạn thấy là ok số lượng sinh viên như này chắc
[01:04:45] là ok số lượng sinh viên như này chắc chắn là lớp kia thỏa mãn được rồi không
[01:04:47] chắn là lớp kia thỏa mãn được rồi không ạ một cái lớp kia có thận năm mà nó
[01:04:48] ạ một cái lớp kia có thận năm mà nó không ạ Thì bây giờ mình sẽ thuần là
[01:04:51] không ạ Thì bây giờ mình sẽ thuần là à vì sao sáng cái số lượng sẽ thêm này
[01:04:54] à vì sao sáng cái số lượng sẽ thêm này với cái số chỗ trận số chỗ trống kia là
[01:04:57] với cái số chỗ trận số chỗ trống kia là không ạ
[01:04:58] không ạ có những cách nào đơn giản hơn cách nói
[01:05:01] có những cách nào đơn giản hơn cách nói đơn giản hơn nó sẽ như thế này
[01:05:03] đơn giản hơn nó sẽ như thế này ừ ừ
[01:05:03] ừ ừ [âm nhạc]
[01:05:05] [âm nhạc] an toàn bộ Cái này nó sẽ là 1 bảng
[01:05:09] an toàn bộ Cái này nó sẽ là 1 bảng h i này ạ
[01:05:16] o0o à à
[01:05:19] à à I đặc điểm Mimi nó nghĩ xem à Cách cách
[01:05:23] I đặc điểm Mimi nó nghĩ xem à Cách cách nào để mà giải thích các bạn nói dễ hiểu
[01:05:25] nào để mà giải thích các bạn nói dễ hiểu nhất
[01:05:28] Ừ Rồi
[01:05:30] Rồi tặng bỏ cái này sang đây đã nhé mình xin
[01:05:34] tặng bỏ cái này sang đây đã nhé mình xin phép Dạy cái này trước rồi
[01:05:36] phép Dạy cái này trước rồi bỏ bỏ bỏ Lấy kiểu thì mình sẽ dùng thôi
[01:05:38] bỏ bỏ bỏ Lấy kiểu thì mình sẽ dùng thôi Đây mình cứ đi suốt một bạn trước đi
[01:05:41] Đây mình cứ đi suốt một bạn trước đi nhiều mạn theo cách không không phải
[01:05:43] nhiều mạn theo cách không không phải nông dân mà như vừa nãy đi
[01:05:45] nông dân mà như vừa nãy đi Ừ để các bạn dễ hình dung đã
[01:05:47] Ừ để các bạn dễ hình dung đã cách để máy xác không Nông dân Các bạn
[01:05:50] cách để máy xác không Nông dân Các bạn nhớ cách in xuất hiện của nông dân vừa
[01:05:51] nhớ cách in xuất hiện của nông dân vừa nãy nó gì không ạ Nó là mình có bao
[01:05:54] nãy nó gì không ạ Nó là mình có bao nhiêu cột thì mình sẽ đi krabi như cột
[01:05:56] nhiêu cột thì mình sẽ đi krabi như cột để mí shop vào đấy ông ạ Còn nhiều không
[01:05:59] để mí shop vào đấy ông ạ Còn nhiều không ạ Mình sẽ đi claire như thế này mã
[01:06:05] bằng select mã for Master Các bạn nhớ kế đoạn
[01:06:12] select mã for Master Các bạn nhớ kế đoạn điệp khúc nào ạ Mình sẽ đi clip bấy
[01:06:14] điệp khúc nào ạ Mình sẽ đi clip bấy nhiêu cái như thế này đúng không ạ sau
[01:06:17] nhiêu cái như thế này đúng không ạ sau đó thì mình sẽ Giả sử có chấm nhầm dám
[01:06:20] đó thì mình sẽ Giả sử có chấm nhầm dám đây nhá Tôi giả sử mình sẽ is that into
[01:06:22] đây nhá Tôi giả sử mình sẽ is that into sinh viên xong rồi mình Mã như này đúng
[01:06:26] sinh viên xong rồi mình Mã như này đúng không ạ sau đó thì value xong rồi lại
[01:06:29] không ạ sau đó thì value xong rồi lại điệp khúc mà như này không ạ Còn nếu mạ
[01:06:32] điệp khúc mà như này không ạ Còn nếu mạ thì đi claire như thế
[01:06:34] thì đi claire như thế rất nhiều thế không tốt cũng như là kiểu
[01:06:38] rất nhiều thế không tốt cũng như là kiểu Các bạn thấy lặp đi lặp lại nó bạn chất
[01:06:39] Các bạn thấy lặp đi lặp lại nó bạn chất lấy từ bảng nghĩ sẽ thật thôi mà tại sao
[01:06:41] lấy từ bảng nghĩ sẽ thật thôi mà tại sao mình không lấy hết từ bạn sẽ thật tự mí
[01:06:43] mình không lấy hết từ bạn sẽ thật tự mí rất vào đúng ạ
[01:06:45] rất vào đúng ạ nhà mình có thể làm thế mà mình sẽ làm
[01:06:47] nhà mình có thể làm thế mà mình sẽ làm đúng kiểu nhà luôn ấy
[01:06:50] đúng kiểu nhà luôn ấy a slack xào forecasted là xong cái tuổi
[01:06:56] a slack xào forecasted là xong cái tuổi trông rất ngắn rất dễ hiểu được gọi là
[01:06:59] trông rất ngắn rất dễ hiểu được gọi là sợi rất vào sinh viên lấy toàn bộ từ
[01:07:03] sợi rất vào sinh viên lấy toàn bộ từ bảng tin tức là sau chạy thử nhé chạy
[01:07:06] bảng tin tức là sau chạy thử nhé chạy được em ạ
[01:07:07] được em ạ ở đây mình chạy thử các bạn xem nó tin
[01:07:10] ở đây mình chạy thử các bạn xem nó tin là đang chưa có sinh viên ở đông thì sợ
[01:07:13] là đang chưa có sinh viên ở đông thì sợ lắm
[01:07:14] lắm ở đó
[01:07:21] ở đoạn này dễ hiểu đoạn này thì dễ hiểu không ạ ở đoạn này theo chỉ đơn giản là
[01:07:27] không ạ ở đoạn này theo chỉ đơn giản là đưa mình có Thậm chí cái này hỗ trợ ý
[01:07:30] đưa mình có Thậm chí cái này hỗ trợ ý rất nhiều nhé Chị sẽ nhiều Non nhé để
[01:07:33] rất nhiều nhé Chị sẽ nhiều Non nhé để hai Chuẩn đấy
[01:07:36] hai Chuẩn đấy thăm lớp khác đi đúng ạ Thế mua bạn nữa
[01:07:40] thăm lớp khác đi đúng ạ Thế mua bạn nữa đi
[01:07:41] đi anh cũng là anh Tuấn là anh đấy phân
[01:07:44] anh cũng là anh Tuấn là anh đấy phân thân anh học cả lớp 1 Đi đúng không
[01:07:46] thân anh học cả lớp 1 Đi đúng không Delete bạn đi lễ rồi xóa đi này
[01:07:50] Delete bạn đi lễ rồi xóa đi này anh nghe này
[01:07:52] anh nghe này vi phạm nhí xuất thử lại sinh viên à
[01:07:56] vi phạm nhí xuất thử lại sinh viên à em chạy lại
[01:07:58] em chạy lại Sau đó các bạn thấy cơ à
[01:08:01] Sau đó các bạn thấy cơ à em không cần phải đi claire và dòng thủ
[01:08:03] em không cần phải đi claire và dòng thủ công giống như vừa nãy anh đã cốt chị
[01:08:05] công giống như vừa nãy anh đã cốt chị rất dạng như này có bao nhịn có bao
[01:08:08] rất dạng như này có bao nhịn có bao nhiêu is xuất thì mình sẽ lách bấy nhiêu
[01:08:11] nhiêu is xuất thì mình sẽ lách bấy nhiêu và Insert vào trong bảo sinh viên không
[01:08:13] và Insert vào trong bảo sinh viên không Còn ghi ở trên cục nữa đứa nằm không ạ
[01:08:15] Còn ghi ở trên cục nữa đứa nằm không ạ Và từ đây mình mới nâng lên nó thành như
[01:08:19] Và từ đây mình mới nâng lên nó thành như này bây giờ cái cái này các bạn vừa thấy
[01:08:23] này bây giờ cái cái này các bạn vừa thấy vừa thấy mình lấy nó lấy
[01:08:28] cách lấy mã lớp các tự xứ để mà kiểm tra đúng không ạ Vì sẽ kiểm tra theo ạ
[01:08:34] đúng không ạ Vì sẽ kiểm tra theo ạ ở với cái Mà lớp đấy xem nó có kiểu thỏa
[01:08:37] ở với cái Mà lớp đấy xem nó có kiểu thỏa mãn hay không Vân Vân không ạ
[01:08:39] mãn hay không Vân Vân không ạ có ai nó sẽ như thế này
[01:08:41] có ai nó sẽ như thế này em copy lại này
[01:08:45] em copy lại này a bà B mình sẽ
[01:08:48] a bà B mình sẽ biến nó thành một bảng và Fi em ạ Và bây
[01:08:52] biến nó thành một bảng và Fi em ạ Và bây giờ mình sẽ Shake sao form
[01:08:56] giờ mình sẽ Shake sao form Ừ mạng lớp trước đi
[01:08:59] Ừ mạng lớp trước đi ờ ờ
[01:09:00] ờ ờ Ừ rồi cả cái cúp này nhé
[01:09:05] Ừ rồi cả cái cúp này nhé On Y chấm mã lớp đúng ạ bằng lớp chấm Mã
[01:09:14] A và anh em hoặc quen được mình nói dùng que quê xuống chỗ chấm
[01:09:24] số nhỏ hơn số lượng y chấm số lượng sinh viên dạy thêm đó có lệnh nó sẽ như thế
[01:09:32] viên dạy thêm đó có lệnh nó sẽ như thế này bây giờ bắt đầu đến lúc này cái này
[01:09:36] này bây giờ bắt đầu đến lúc này cái này bài toán ở đây nó sẽ làm ở gì mình sẽ
[01:09:38] bài toán ở đây nó sẽ làm ở gì mình sẽ lấy xem đoạn lấy toàn bộ các lớp có số
[01:09:42] lấy xem đoạn lấy toàn bộ các lớp có số chấm đúng ạ ạ
[01:09:44] chấm đúng ạ ạ à à đâu phải lớn hơn đi Đúng rồi phải
[01:09:47] à à đâu phải lớn hơn đi Đúng rồi phải lớn hơn một cái số lượng sinh viên lớn
[01:09:49] lớn hơn một cái số lượng sinh viên lớn hơn hoặc bằng lớn bằng số lượng sinh
[01:09:51] hơn hoặc bằng lớn bằng số lượng sinh viên sẽ thêm cái chạy nè
[01:09:58] ở đây mình chạy được ăn sớm nhé Đi học bây giờ mình
[01:10:04] Đi học bây giờ mình Ừ Ok như thế này giả sử là mình sẽ à
[01:10:10] Ừ Ok như thế này giả sử là mình sẽ à Em in sót lại và
[01:10:12] Em in sót lại và chắc lại phải xóa rồi Ừ tôi nên tạo 1
[01:10:15] chắc lại phải xóa rồi Ừ tôi nên tạo 1 cái code để mà xóa nhanh cái đoạn này
[01:10:17] cái code để mà xóa nhanh cái đoạn này cho ý rất lạnh nhanh cứ phải đi xát lại
[01:10:19] cho ý rất lạnh nhanh cứ phải đi xát lại hơn mất công nhận Xin lỗi các bạn
[01:10:25] ở đây đánh trống trơn nhé trong trường hợp này là tô Insert vào
[01:10:30] hợp này là tô Insert vào công sẽ thấy tôi yên giấc hay bạn vào
[01:10:33] công sẽ thấy tôi yên giấc hay bạn vào lớp một này một bạn lớp 2 tự nhiên cái
[01:10:35] lớp một này một bạn lớp 2 tự nhiên cái này sẽ dẫn thỏa mãn rồi đúng không ạ
[01:10:38] này sẽ dẫn thỏa mãn rồi đúng không ạ ý là như này
[01:10:40] ý là như này thì các bạn thấy à
[01:10:42] thì các bạn thấy à Anh lớp 1 vào lớp 2 số lượng sinh viên
[01:10:45] Anh lớp 1 vào lớp 2 số lượng sinh viên sẽ thêm như thế này không ở đây gì cả
[01:10:47] sẽ thêm như thế này không ở đây gì cả đúng không ạ nhưng bây giờ giả sử là
[01:10:49] đúng không ạ nhưng bây giờ giả sử là mình sẽ đi xuất thêm một bạn nữa là
[01:10:52] mình sẽ đi xuất thêm một bạn nữa là Anh Tuấn hacker ạ
[01:10:55] Anh Tuấn hacker ạ anh lần này bạn ấy vào lớp 3 chẳng hạn
[01:10:57] anh lần này bạn ấy vào lớp 3 chẳng hạn Chắc chắn là lớp này số lượng sinh viên
[01:11:00] Chắc chắn là lớp này số lượng sinh viên xuống chỗ trống Các bạn nhớ không ạ chỗ
[01:11:03] xuống chỗ trống Các bạn nhớ không ạ chỗ trống nó là gì ạ chỗ trống mà không Tất
[01:11:05] trống nó là gì ạ chỗ trống mà không Tất cả không thể easiest bạn đấy vào trong
[01:11:07] cả không thể easiest bạn đấy vào trong đất thứ ba đúng không ạ sẽ thử nhé đó có
[01:11:10] đất thứ ba đúng không ạ sẽ thử nhé đó có ông thấy nó vẫn sẽ Chỉ ra mỗi hai lớp
[01:11:12] ông thấy nó vẫn sẽ Chỉ ra mỗi hai lớp này thôi ông ạ Mình sẽ không ra lớp 13
[01:11:15] này thôi ông ạ Mình sẽ không ra lớp 13 Vậy sao khi số chỗ trống nó không hề
[01:11:17] Vậy sao khi số chỗ trống nó không hề thỏa mãn việc lớn hơn hoặc bằng số lượng
[01:11:19] thỏa mãn việc lớn hơn hoặc bằng số lượng sinh viên sẽ thêm số lượng sinh viên sẽ
[01:11:21] sinh viên sẽ thêm số lượng sinh viên sẽ thêm lần này nó là một mà chỗ trống nó
[01:11:24] thêm lần này nó là một mà chỗ trống nó là không không không để lớn lên bằng một
[01:11:26] là không không không để lớn lên bằng một được đúng đúng ạ Nó sẽ không ra đó
[01:11:32] Chị Hai Lúa không Ừ
[01:11:35] Ừ nhưng mà đoạn này các bạn thấy mình mới
[01:11:38] nhưng mà đoạn này các bạn thấy mình mới chỉ xe lách thôi Mẹ làm gì đâu đúng ạ
[01:11:40] chỉ xe lách thôi Mẹ làm gì đâu đúng ạ thì bây giờ các bạn thấy cái việc mình
[01:11:43] thì bây giờ các bạn thấy cái việc mình vừa sẽ lấy cái cốt ở điểm gì để lấy ra
[01:11:46] vừa sẽ lấy cái cốt ở điểm gì để lấy ra được cái lớp thỏa mãn lớp thỏa mãn việc
[01:11:50] được cái lớp thỏa mãn lớp thỏa mãn việc in such nóng ạ thì là mình lại làm tiếp
[01:11:53] in such nóng ạ thì là mình lại làm tiếp mình sẽ lấy lớp chấm mã này à
[01:11:58] mình sẽ lấy lớp chấm mã này à khi sex
[01:12:01] em chạy lại này à mình mình đi phát lại gọi xe mà đó thì còn lớp 1 và lớp 2 và
[01:12:09] gọi xe mà đó thì còn lớp 1 và lớp 2 và mình thỏa mãn đúng ạ lớp Một lớp hai
[01:12:11] mình thỏa mãn đúng ạ lớp Một lớp hai mình thỏa mãn rồi mình làm gì tiếp
[01:12:14] mình thỏa mãn rồi mình làm gì tiếp Ừ thì mình sẽ chỉ insaat những cái bạn
[01:12:17] Ừ thì mình sẽ chỉ insaat những cái bạn sinh viên
[01:12:18] sinh viên Em thuộc lớp Một lớp hai thỏa mãn thôi
[01:12:20] Em thuộc lớp Một lớp hai thỏa mãn thôi nó sẽ như thế này
[01:12:22] nó sẽ như thế này I Insert into
[01:12:26] I Insert into sinh viên snacks
[01:12:30] sinh viên snacks Vì sao phone instead các bạn nếu cái câu
[01:12:33] Vì sao phone instead các bạn nếu cái câu hồi nãy không ạ
[01:12:36] Ừ Rồi mình sẽ Where mã lớp In nằm trong các cụm này
[01:12:43] các cụm này đó với rồng nếu anh có thể bảo là rất là
[01:12:47] đó với rồng nếu anh có thể bảo là rất là đúng
[01:12:49] đúng thì nó sẽ như thế nào có việc
[01:12:52] thì nó sẽ như thế nào có việc thì các bạn nhớ câu này vừa nãy mình có
[01:12:54] thì các bạn nhớ câu này vừa nãy mình có ghi không ạ thì lần này mình sẽ cho mạ
[01:12:56] ghi không ạ thì lần này mình sẽ cho mạ lớp chỉ nằm trong kể cái cái danh sách
[01:12:59] lớp chỉ nằm trong kể cái cái danh sách lớp Một lớp hai này thôi nó như này in
[01:13:02] lớp Một lớp hai này thôi nó như này in nằm trong đó
[01:13:05] nằm trong đó anh chạy ạ
[01:13:07] anh chạy ạ Anh An ninh thủ in sót lại
[01:13:09] Anh An ninh thủ in sót lại A chạy
[01:13:13] em heo không có tuần hacker đúng không có tấn hai câu được tôi kéo Kim Chi Mới
[01:13:20] Ừ Ok chị ạ ạ
[01:13:25] Ông ngoại ra hơi lũ thật
[01:13:30] cho tất cả cụm này bản chất nó là gì cả cụm cả cụ này vừa rồi mình cần này mã
[01:13:35] cụm cả cụ này vừa rồi mình cần này mã lắm không ạ lầy mã lớp hợp lệ
[01:13:39] lắm không ạ lầy mã lớp hợp lệ Ừ đúng rồi nó Safari Các bạn thấy là nó
[01:13:42] Ừ đúng rồi nó Safari Các bạn thấy là nó là
[01:13:43] là select nằm lòng nhân selec nó Safari
[01:13:46] select nằm lòng nhân selec nó Safari thằng con
[01:13:48] thằng con nhưng mà thế này mới chỉ áp dụng cho ok
[01:13:52] nhưng mà thế này mới chỉ áp dụng cho ok Các bạn thấy được là bây giờ vừa áp dụng
[01:13:54] Các bạn thấy được là bây giờ vừa áp dụng được cho cả lớp chỗ trống mà không ạ
[01:13:56] được cho cả lớp chỗ trống mà không ạ nhưng nó vẫn chưa update thì cả Không ạ
[01:13:59] nhưng nó vẫn chưa update thì cả Không ạ bây giờ update thì như thế nào đúng ạ
[01:14:01] bây giờ update thì như thế nào đúng ạ thì nó lại giống cái bài toán hôm trước
[01:14:04] thì nó lại giống cái bài toán hôm trước các bạn nhớ chích lâu hôm trước mình học
[01:14:06] các bạn nhớ chích lâu hôm trước mình học thì có gì cập rồi nó mình sẽ là update
[01:14:09] thì có gì cập rồi nó mình sẽ là update lớp sét số chỗ trống bằng
[01:14:13] lớp sét số chỗ trống bằng trò chuyện - bạn đi bằng y chấm số lượng
[01:14:19] trò chuyện - bạn đi bằng y chấm số lượng sinh viên Các bạn nhớ đoạn này sau đó
[01:14:22] sinh viên Các bạn nhớ đoạn này sau đó thì before này
[01:14:23] thì before này lại for copy đúng ý hết cái đoạn ở trên
[01:14:27] lại for copy đúng ý hết cái đoạn ở trên này lại như thế này
[01:14:31] anh nghe này là được
[01:14:36] a form of Joy thứ thứ này
[01:14:42] ở đó
[01:14:45] Anh thấy bây giờ mày Ông còn thấy lũ hơn không ạ
[01:14:50] ta chạy nha Ừ đi lại
[01:14:54] Ừ đi lại anh cứ sát lại này thuộc mệt mỏi đoạn
[01:14:58] anh cứ sát lại này thuộc mệt mỏi đoạn này quá lại phải tạm hồ sơ lưu thôi lỡ
[01:15:00] này quá lại phải tạm hồ sơ lưu thôi lỡ rồi
[01:15:03] từ đầu tiên sẽ lấy lại cho chắc này 550 ạ
[01:15:07] ạ khi buồn lại nay sao này
[01:15:11] khi buồn lại nay sao này Em có áo rượu ạ
[01:15:16] anh cũng rẽ mà nó không ạ Dễ mà
[01:15:21] ở đoạn Delete như mình đã nói chi cơ Insert trong tác dụng này trong bài toán
[01:15:26] Insert trong tác dụng này trong bài toán này không cần áp dụng Delete Đúng không
[01:15:27] này không cần áp dụng Delete Đúng không ạ
[01:15:28] ạ nhưng mà
[01:15:30] nhưng mà ở những nhưng mà lại sợ mấy ông cái hiểu
[01:15:34] ở những nhưng mà lại sợ mấy ông cái hiểu cái đoạn sub theo kiểu nhiều Nhiều này
[01:15:36] cái đoạn sub theo kiểu nhiều Nhiều này rồi không ạ
[01:15:37] rồi không ạ Anh Hiểu hiểu à
[01:15:39] Anh Hiểu hiểu à giới thiệu phần nó nhá Tôi không thể bảo
[01:15:42] giới thiệu phần nó nhá Tôi không thể bảo mày không hiểu hết được nhiều hết thì
[01:15:43] mày không hiểu hết được nhiều hết thì thành siêu nhân quá đoạn này tôi xem lại
[01:15:46] thành siêu nhân quá đoạn này tôi xem lại đội ta thấy hơi lú
[01:15:48] đội ta thấy hơi lú Tôi không biết đoạn này có thể tối ưu
[01:15:50] Tôi không biết đoạn này có thể tối ưu được hay không Nhưng mà tôi thấy bạn này
[01:15:52] được hay không Nhưng mà tôi thấy bạn này trông có phải nói thứ nhất là đang đúng
[01:15:55] trông có phải nói thứ nhất là đang đúng rồi Đã thì xem nó thì tối rồi không nữa
[01:15:58] rồi Đã thì xem nó thì tối rồi không nữa thì chưa biết luôn lâu lắm mở rộng động
[01:16:00] thì chưa biết luôn lâu lắm mở rộng động lại phần này à
[01:16:02] lại phần này à Ừ Ok Còn bây giờ
[01:16:05] Ừ Ok Còn bây giờ mấy ông có tài chưa để tôi dậy Nốt Cần
[01:16:08] mấy ông có tài chưa để tôi dậy Nốt Cần update số lượng nhiều À à
[01:16:12] update số lượng nhiều À à à à
[01:16:13] à à anh Alo có ai chưa
[01:16:19] Em sắp này thứ Ba ở có khi áp dụng cái Asus này nhanh được này
[01:16:25] Ừ ừ khóa rồi sợ
[01:16:31] em chỉ hơi bị ngược lặng Tí và việc là khi mà đi led thì mình kiểm tra hư thôi
[01:16:36] khi mà đi led thì mình kiểm tra hư thôi không ạ
[01:16:38] anh không thể mới ông bình luận gì nữa
[01:16:47] ờ ờ
[01:16:50] à à Ừ đúng rồi sẽ thả nó cái này là cái khó
[01:16:55] Ừ đúng rồi sẽ thả nó cái này là cái khó cái này cái bụi cần đưa buổi cuối của
[01:16:57] cái này cái bụi cần đưa buổi cuối của fei chuyên sâu rồi nữa Đỡ buồn phải khói
[01:16:59] fei chuyên sâu rồi nữa Đỡ buồn phải khói chứ mày không thể mong dễ được dễ mấy
[01:17:03] chứ mày không thể mong dễ được dễ mấy ông ấy thất vọng Nói thẳng như thế nếu
[01:17:05] ông ấy thất vọng Nói thẳng như thế nếu không phải mong bữa mày rất khó đúng
[01:17:07] không phải mong bữa mày rất khó đúng không ạ
[01:17:10] Khi bữa mày khó thì ông xem lại 3 4 lần kiểu gì ông cũng sẽ vỡ dần ra má không ạ
[01:17:18] kiểu gì ông cũng sẽ vỡ dần ra má không ạ à à
[01:17:20] à à Ừ cái việc update này đâu để mình sẽ lại
[01:17:24] Ừ cái việc update này đâu để mình sẽ lại nhé
[01:17:26] nhé chưa bao giờ sử bài toán theo mỹ nhân sẽ
[01:17:29] chưa bao giờ sử bài toán theo mỹ nhân sẽ lại sợ lại làm lu quá à
[01:17:32] lại sợ lại làm lu quá à Ừ mình cũng vừa mới tiêm xong thành ra
[01:17:34] Ừ mình cũng vừa mới tiêm xong thành ra là mình cũng đang hơi bị đốm thì sang
[01:17:37] là mình cũng đang hơi bị đốm thì sang cho nó hỏng thì mình xin lỗi các bạn
[01:17:39] cho nó hỏng thì mình xin lỗi các bạn tiên thì ra tin tưởng qua ở nhiều hôm
[01:17:42] tiên thì ra tin tưởng qua ở nhiều hôm nay mới có vẻ nhấn Vậy thôi ngủ ngủ từ
[01:17:46] nay mới có vẻ nhấn Vậy thôi ngủ ngủ từ hôm qua đến giờ đấy còn chưa ăn uống
[01:17:48] hôm qua đến giờ đấy còn chưa ăn uống nhiều ạ
[01:17:49] nhiều ạ ờ ờ
[01:17:51] xổ số ba bây giờ để đầu tiên là số của chồng nó bằng 5 này
[01:17:57] chồng nó bằng 5 này chỉ số chống thay bằng không ngoài đúng
[01:17:59] chỉ số chống thay bằng không ngoài đúng ạ bây giờ sự mình cập nhật Số lượng số
[01:18:02] ạ bây giờ sự mình cập nhật Số lượng số sinh viên từ đây sang đây này
[01:18:05] sinh viên từ đây sang đây này ừ ừ
[01:18:06] ừ ừ Ừ từ đây sang đây sản không được Bởi vì
[01:18:08] Ừ từ đây sang đây sản không được Bởi vì sẽ sẵn chỗ trống này mà không ạ
[01:18:12] sẽ sẵn chỗ trống này mà không ạ Cho tôi có phải làm
[01:18:14] Cho tôi có phải làm thử để mua ra sự của 3 sinh viên này Đây
[01:18:19] thử để mua ra sự của 3 sinh viên này Đây là sự năm này
[01:18:21] là sự năm này à à
[01:18:23] à à khi mà không có sinh viên nào biết lớp
[01:18:25] khi mà không có sinh viên nào biết lớp này thì mình sẽ cập nhật 3 sinh viên vào
[01:18:28] này thì mình sẽ cập nhật 3 sinh viên vào bên này thì bên này sẽ đổi lại nó thành
[01:18:30] bên này thì bên này sẽ đổi lại nó thành 22 và năm đó ông ạ hòa nhập 532 đúng
[01:18:34] 22 và năm đó ông ạ hòa nhập 532 đúng không ạ này
[01:18:39] Ừ Ok dạo này gần đây là hồi trước mình có nhờ một bạn sinh viên là bạn đấy chia
[01:18:44] có nhờ một bạn sinh viên là bạn đấy chia thành danh sách phát để mà các bạn xem
[01:18:46] thành danh sách phát để mà các bạn xem lại từng đoạn từng đoạn cho
[01:18:48] lại từng đoạn từng đoạn cho nếu mà ông nào chỉ muốn xem đoạn nào
[01:18:50] nếu mà ông nào chỉ muốn xem đoạn nào đoạn nào thì có thể cắt tua nhanh đến
[01:18:52] đoạn nào thì có thể cắt tua nhanh đến đấy nhưng dạo này bạn sinh viên này cũng
[01:18:54] đấy nhưng dạo này bạn sinh viên này cũng bận nữa rồi
[01:18:55] bận nữa rồi chờ tôi tự xem lại tự chia vậy
[01:19:00] chờ tôi tự xem lại tự chia vậy nó cả có nhiều việc hoặc là hãy quên đã
[01:19:06] ạ Bây giờ giả sử mình cập nhật như này số lượng ngay giờ sự mình à
[01:19:12] số lượng ngay giờ sự mình à Lúc đầu là sự tay có 6 sinh viên
[01:19:15] Lúc đầu là sự tay có 6 sinh viên số lượng Lúc đầu như thế này
[01:19:18] số lượng Lúc đầu như thế này và sau đó thì ở đây Tổng cộng của sáu
[01:19:21] và sau đó thì ở đây Tổng cộng của sáu này à
[01:19:23] này à hôm nay Ê Phương mình đội hết nó sao lại
[01:19:27] hôm nay Ê Phương mình đội hết nó sao lại như này à
[01:19:29] như này à Ừ thì mình cần là tệ
[01:19:32] Ừ thì mình cần là tệ Ê mày đã không này đấy vợ năm này
[01:19:38] anh nhắc lại 6 này cái này sẽ -1 chẳng ạ ạ
[01:19:46] Ừ mình vẫn phải cao mình cũng phải đến
[01:19:50] mình vẫn phải cao mình cũng phải đến đúng không ạ đến ở đây là mình sẽ phải
[01:19:52] đúng không ạ đến ở đây là mình sẽ phải đếm xem
[01:19:55] đếm xem tay mình thể chạy thử đoạn này cho nhau
[01:19:58] tay mình thể chạy thử đoạn này cho nhau ừ ừ
[01:20:00] ừ ừ anh cứ chạy lần lượt là kiểu xảy ra thôi
[01:20:02] anh cứ chạy lần lượt là kiểu xảy ra thôi sẽ xa form chị sẽ lực này
[01:20:09] mình bắt đầu thú sẽ sao form B thật này à
[01:20:17] sẽ sao form B thật này à chào cả nhà
[01:20:20] Ừ ok
[01:20:25] Anh đang trống như này sinh viên thật sự bây giờ mình sẽ cho tất cả sinh viên
[01:20:29] bây giờ mình sẽ cho tất cả sinh viên sang lớp thứ ba là sáng lại sẽ update mà
[01:20:33] sang lớp thứ ba là sáng lại sẽ update mà lớp bằng ba không có que gì cả đúng
[01:20:35] lớp bằng ba không có que gì cả đúng không ạ Nếu mà update như này
[01:20:41] Ừ nếu bà biết như này
[01:20:45] thì các bạn sẽ thấy à đương nhiên bê bây giờ đang chưa đổi được
[01:20:52] giờ đang chưa đổi được em đổi toàn bộ lớp 3 này mình sẽ thạch
[01:20:55] em đổi toàn bộ lớp 3 này mình sẽ thạch cao cao toàn bộ tất cả các
[01:20:59] cao cao toàn bộ tất cả các sinh viên sẽ chuyện giá gốc thứ ba
[01:21:02] sinh viên sẽ chuyện giá gốc thứ ba khi sex
[01:21:06] à không để xem nha Đổi sáng tất cả sinh
[01:21:10] không để xem nha Đổi sáng tất cả sinh viên trong lớp thứ ba chỉ đứng tên mình
[01:21:11] viên trong lớp thứ ba chỉ đứng tên mình kiểm tra xem à thỏa mãn hay không đúng
[01:21:13] kiểm tra xem à thỏa mãn hay không đúng không ạ
[01:21:15] không ạ à à
[01:21:18] à à à à
[01:21:27] 3000 mình nhớ hồi đấy mình dậy sinh viên mình cũng sẽ không áp dụng theo cách của
[01:21:31] mình cũng sẽ không áp dụng theo cách của ít đâu mình sẽ dạy theo kiểu như thế này
[01:21:35] ít đâu mình sẽ dạy theo kiểu như thế này cơ á
[01:21:38] à à chị cũng sẽ áp dụng đúng như thế này
[01:21:42] chị cũng sẽ áp dụng đúng như thế này update love xét các thử như thế này
[01:21:46] update love xét các thử như thế này anh nói chung là mình sẽ copy cái đoạn
[01:21:48] anh nói chung là mình sẽ copy cái đoạn này
[01:21:51] cho Starex out for a
[01:21:58] Ừ cái cái cái đoạn này thì các bạn hình dung rồi cái đoạn này nó là số lượng
[01:22:02] dung rồi cái đoạn này nó là số lượng sinh viên sẽ thêm không ạ khi mình trả
[01:22:05] sinh viên sẽ thêm không ạ khi mình trả lại các bạn dễ hình dung nhé
[01:22:07] lại các bạn dễ hình dung nhé khi sex
[01:22:08] khi sex khi sex
[01:22:12] bạn trong trường hợp này các bạn thể sẽ không ra cả lớp nào tôi rõ là lớp thứ ba
[01:22:17] không ra cả lớp nào tôi rõ là lớp thứ ba rồi nó sẽ không thỏa mãn còn lớp thứ 2
[01:22:19] rồi nó sẽ không thỏa mãn còn lớp thứ 2 thì mày làm được thỏa mãn này đúng ạ Bởi
[01:22:23] thì mày làm được thỏa mãn này đúng ạ Bởi vì số chồng nó bốn số lượng sinh viên sẽ
[01:22:25] vì số chồng nó bốn số lượng sinh viên sẽ là ba nên nó thỏa mãn Còn với lớp thứ ba
[01:22:28] là ba nên nó thỏa mãn Còn với lớp thứ ba nó không giải mã nó sẽ ra như thế này
[01:22:29] nó không giải mã nó sẽ ra như thế này ngoạn
[01:22:33] ạ Bây giờ mình à
[01:22:38] đi học mình có thai nó lại bằng lớp thứ hai các bạn dễ dễ xem đã bên mình cần
[01:22:43] hai các bạn dễ dễ xem đã bên mình cần lấy mã lớp này
[01:22:47] cách lấy mã lớp để mình cập nhật giống như là cái vụ vừa rồi thôi ông ạ
[01:22:53] như là cái vụ vừa rồi thôi ông ạ bộ phim sẽ update
[01:22:56] bộ phim sẽ update sinh viên à
[01:22:59] sinh viên à à à
[01:23:02] à à ừ ừ
[01:23:14] 3000 lẽ update như mình nói lại delete và Insert thì nó sẽ tốt hơn mình sẽ lại
[01:23:21] và Insert thì nó sẽ tốt hơn mình sẽ lại ít
[01:23:22] ít into sinh viên
[01:23:25] into sinh viên thế giống hệt câu chuyện này tôi nghĩ là
[01:23:28] thế giống hệt câu chuyện này tôi nghĩ là chẳng khác gì đâu sao for instance Where
[01:23:32] chẳng khác gì đâu sao for instance Where mã Lớp in
[01:23:37] Ừ thế giới mã Trần Mã Ý
[01:23:45] ừ ừ
[01:23:47] à à à à
[01:23:52] à à thế này và mình cũng đi lễ đi không
[01:23:56] thế này và mình cũng đi lễ đi không Delete From A
[01:23:59] Delete From A cô sinh viên
[01:24:03] Ừ có nghĩa có khi ở trẻ áp dụng theo dòng hết cái à
[01:24:07] dòng hết cái à Ừ cái ở trên kia là chạy được đấy Không
[01:24:12] Ừ cái ở trên kia là chạy được đấy Không cần nó phức tạp quá à
[01:24:13] cần nó phức tạp quá à chị sẽ thử nhé
[01:24:16] chị sẽ thử nhé à Tôi đang nghĩ làm thuốc tạp chưa
[01:24:18] à Tôi đang nghĩ làm thuốc tạp chưa thử phát này à
[01:24:23] dù thời tiết ở lớp thứ ba thử xem được không
[01:24:31] anh bay xử me sinh viên rồi Ừ
[01:24:35] Ừ bắt tại sao máy bay nhỉ à các bạn I
[01:24:39] bắt tại sao máy bay nhỉ à các bạn I stood
[01:24:41] stood a deadphone mạn Love in
[01:24:46] à à ở lớp trầm mã số lượng sinh viên sẽ thêm
[01:24:52] ở lớp trầm mã số lượng sinh viên sẽ thêm thì tại sao bạn lại bay được nghỉ tôi bị
[01:24:55] thì tại sao bạn lại bay được nghỉ tôi bị sai sai ở đâu đợi tới thì chuẩn bị ngáo
[01:24:59] sai sai ở đâu đợi tới thì chuẩn bị ngáo quá à
[01:25:03] à à
[01:25:06] Em ăn hết đoạn này nữa con xuống kB ừ ừ
[01:25:12] ở Samsung KC
[01:25:21] Ừ ai cũng sẽ đến lúc nào không ạ con xuống KC
[01:25:27] từ hôm Men in Asia Vì sao đó à
[01:25:36] à à Hà Thanh Xuân Ca Đúng rồi nhỉ
[01:25:42] Ừ cái hợp mọi khi mình cho đoạn này biến hàng bình luận được mà nhỉ
[01:25:47] hàng bình luận được mà nhỉ Ừ anh em chú thích chú thích thì mày
[01:25:50] Ừ anh em chú thích chú thích thì mày nghỉ
[01:25:51] nghỉ là
[01:25:52] là sao rốt điên à
[01:25:54] sao rốt điên à em thông cảm mình hình như mình đang đến
[01:25:57] em thông cảm mình hình như mình đang đến giường áo ơi xin lỗi các bạn
[01:25:59] giường áo ơi xin lỗi các bạn à à
[01:26:02] à à ừ ừ
[01:26:06] ờ ờ
[01:26:14] ở Samsung ca Samsung à
[01:26:25] 3000 ra sinh viên làm à à Rồi rồi Mình hiểu tại sao sai rồi đoạn vừa rồi mình
[01:26:31] hiểu tại sao sai rồi đoạn vừa rồi mình delete Mình bị nhầm âm Ok mình xin lỗi
[01:26:36] cái bạn này em đúng mình khiếu đoạn quay ở đây thấy ra Nói đi lecture hết à
[01:26:44] ở đây thấy ra Nói đi lecture hết à về chính sách này mình nghĩ là chạy được
[01:26:46] về chính sách này mình nghĩ là chạy được rồi đi suốt này sẽ được mình sẽ que bạn
[01:26:49] rồi đi suốt này sẽ được mình sẽ que bạn lớp như này là xong
[01:26:53] mình tin quái chạy luôn này thử nhé Thử thì biết đúng không ạ
[01:26:58] thì biết đúng không ạ á đù á đù á
[01:27:02] - redhead in xuất lại vào lớp này
[01:27:09] chị xem xem lại sinh viên lớp nhé Chắc lại sinh viên lớp này Ok đúng không ạ bơ
[01:27:14] lại sinh viên lớp này Ok đúng không ạ bơ mình sẽ ăn xơ vào như này không ạ sẽ lại
[01:27:17] mình sẽ ăn xơ vào như này không ạ sẽ lại sinh viên lớp son nữa này các bạn thấy
[01:27:20] sinh viên lớp son nữa này các bạn thấy là
[01:27:21] là Anh Tuấn hacker sáng không thêm về vợ
[01:27:23] Anh Tuấn hacker sáng không thêm về vợ làm lớp Thứ Ba không được Tại đúng không
[01:27:25] làm lớp Thứ Ba không được Tại đúng không ạ phần nãy mình làm rồi à bê mình cần
[01:27:28] ạ phần nãy mình làm rồi à bê mình cần cập nhật hết sinh viên vào lớp thứ 3 cả
[01:27:31] cập nhật hết sinh viên vào lớp thứ 3 cả ạ thìa sẵn à chuẩn là những sinh viên
[01:27:35] ạ thìa sẵn à chuẩn là những sinh viên này bắt buộc phải giữ nguyên đúng không
[01:27:37] này bắt buộc phải giữ nguyên đúng không ạ
[01:27:37] ạ phụ nữ sinh viên này dễ giữ nguyên ở như
[01:27:40] phụ nữ sinh viên này dễ giữ nguyên ở như thế nào chả này
[01:27:43] khi đó các bạn thấy con sẽ giữ nguyên chọn gì thay đổi cả đúng ạ Thế bây giờ
[01:27:47] chọn gì thay đổi cả đúng ạ Thế bây giờ tương tự Thế bây giờ mình sẽ
[01:27:51] tương tự Thế bây giờ mình sẽ em đổi tất cả sinh viên sang lớp thứ hai
[01:27:54] em đổi tất cả sinh viên sang lớp thứ hai là em ạ thì sẽ như thế nào
[01:27:56] là em ạ thì sẽ như thế nào Ông ngoại chạy nha
[01:28:02] xin lỗi à à à
[01:28:08] à à anh đau để xem Tại sao lỗi nào mà bạn là
[01:28:12] anh đau để xem Tại sao lỗi nào mà bạn là đã ký kết kỳ một liên quan đến khóa
[01:28:16] đã ký kết kỳ một liên quan đến khóa chính
[01:28:17] chính Ừ tao mình xem lại nhé
[01:28:19] Ừ tao mình xem lại nhé Ừ em ngủ đi em ạ
[01:28:26] I Delete for sinh viên về mã lớp Ừ thế thì mình phải xé rách lại có đoạn
[01:28:33] Ừ thế thì mình phải xé rách lại có đoạn này cho chắc đi thì sẽ check lại đoạn
[01:28:36] này cho chắc đi thì sẽ check lại đoạn này đi Ừ
[01:28:40] mà copy toàn bộ cái này ra cái này đi à
[01:28:47] em chạy lại
[01:28:53] ê ê đê ê ê
[01:28:58] à À rồi mình hay dùng rồi à ở cái đoạn này nó hơi bị phức tạp một tí
[01:29:05] ở cái đoạn này nó hơi bị phức tạp một tí đoạn này là mình cần lấy mạng lớp cũ
[01:29:08] đoạn này là mình cần lấy mạng lớp cũ anh cài Cả lớp mình mình đang lấy mình
[01:29:11] anh cài Cả lớp mình mình đang lấy mình lấy từ 7 xuất thật thì da mình lấy
[01:29:14] lấy từ 7 xuất thật thì da mình lấy Ừ mình mới chỉ đang xóa những cái thằng
[01:29:17] Ừ mình mới chỉ đang xóa những cái thằng từ bản cũ
[01:29:19] từ bản cũ vì vậy
[01:29:22] ở đoạn này nhá cái đoạn này mình đang lấy
[01:29:27] đoạn này nhá cái đoạn này mình đang lấy từ bảng mỗi từ từ mình sẽ cập nhật xanh
[01:29:30] từ bảng mỗi từ từ mình sẽ cập nhật xanh cái gì thành ra là thế cái dữ liệu cũng
[01:29:34] cái gì thành ra là thế cái dữ liệu cũng không Xóa đi
[01:29:36] không Xóa đi sau khi mà cái này thỏa mãn rồi này tôi
[01:29:39] sau khi mà cái này thỏa mãn rồi này tôi tên là khi thỏa mãn không ạ ạ
[01:29:42] tên là khi thỏa mãn không ạ ạ ừ ừ
[01:29:46] ừ ừ
[01:29:49] a Note II
[01:30:03] à à khi sex
[01:30:09] Ừ tôi có khi là tôi phải xin phép mấy ông
[01:30:13] tôi có khi là tôi phải xin phép mấy ông là buổi sau tối chữa thì câu này đi Tôi
[01:30:15] là buổi sau tối chữa thì câu này đi Tôi thấy tôi đang đùa quá rồi Tôi sợ làm với
[01:30:18] thấy tôi đang đùa quá rồi Tôi sợ làm với ông lũ thêm mất tạm chắc phải tạm dừng
[01:30:21] ông lũ thêm mất tạm chắc phải tạm dừng tay lại
[01:30:22] tay lại tôi xin phép đang Hơi lùn tra ban đầu
[01:30:26] tôi xin phép đang Hơi lùn tra ban đầu choáng vào cái ba xinh rồi
[01:30:28] choáng vào cái ba xinh rồi Các bạn chọn như thế bà Tôi đói nữa
[01:30:32] Các bạn chọn như thế bà Tôi đói nữa ở tạm cất cái này sang buổi hôm sau điện
[01:30:37] ở tạm cất cái này sang buổi hôm sau điện Ừ ai cũng sẽ có lúc mà như thế thôi mặt
[01:30:41] Ừ ai cũng sẽ có lúc mà như thế thôi mặt ngoại mình dân công nghệ thì mình vẫn
[01:30:44] ngoại mình dân công nghệ thì mình vẫn khẳng định đó là không dây công nghệ
[01:30:46] khẳng định đó là không dây công nghệ mình không thể một phát ra được luôn
[01:30:48] mình không thể một phát ra được luôn nóng ạ Các bạn xem xem lại cái á
[01:30:53] nóng ạ Các bạn xem xem lại cái á 10 bài tập sao mày tập sao mày Ông ngồi
[01:30:55] 10 bài tập sao mày tập sao mày Ông ngồi mòi được Dạo này cũng cũng được cho mấy
[01:30:58] mòi được Dạo này cũng cũng được cho mấy ông Mười mà những bài tập hôm nay mình
[01:31:00] ông Mười mà những bài tập hôm nay mình sẽ khác một tí ờ ờ Các bạn thấy mấy buổi
[01:31:05] sẽ khác một tí ờ ờ Các bạn thấy mấy buổi trước mà mình thường ra mình không Chữa
[01:31:06] trước mà mình thường ra mình không Chữa bài tập cho các bạn bởi vì là
[01:31:10] bài tập cho các bạn bởi vì là hầu như tôi toàn bảo mấy ông Cốt lại
[01:31:13] hầu như tôi toàn bảo mấy ông Cốt lại nhưng còn bài hôm nay thì tôi sẽ không
[01:31:16] nhưng còn bài hôm nay thì tôi sẽ không cho mấy ông bị ngoài được chốt lại như
[01:31:18] cho mấy ông bị ngoài được chốt lại như thế Tôi sẽ
[01:31:20] thế Tôi sẽ sẽ có bài tập mới các bạn cũng sẽ phải
[01:31:23] sẽ có bài tập mới các bạn cũng sẽ phải tự làm tự làm cái mới đấy chứ không
[01:31:27] tự làm tự làm cái mới đấy chứ không Không dựa bài bài cũ ở đâu ạ
[01:31:30] Không dựa bài bài cũ ở đâu ạ em còn Cầu xã câu này tra để tôi về xem
[01:31:33] em còn Cầu xã câu này tra để tôi về xem lại đã
[01:31:34] lại đã ở tuổi mình ngỡ mình làm được mấy con
[01:31:38] ở tuổi mình ngỡ mình làm được mấy con này hết rồi nghe kiểu gì cũng mò lại thì
[01:31:41] này hết rồi nghe kiểu gì cũng mò lại thì chị sẽ hiểu thôi thôi tạm
[01:31:45] chị sẽ hiểu thôi thôi tạm Âu Mỹ ở tạm cho các bạn nghỉ nhé mình
[01:31:48] Âu Mỹ ở tạm cho các bạn nghỉ nhé mình cũng xóa nó rồi tặng Chào bạn nhé
[01:31:55] ừ ừ
