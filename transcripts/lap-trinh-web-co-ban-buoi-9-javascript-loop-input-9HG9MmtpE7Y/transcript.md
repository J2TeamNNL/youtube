# Lập trình Web cơ bản - Buổi 9 - JavaScript - Loop & Input

- Video ID: `9HG9MmtpE7Y`
- URL: https://www.youtube.com/watch?v=9HG9MmtpE7Y
- Published: 2021-11-07
- Duration: 1h 17m 56s (4676s)
- Language: vi
- Subtitle source: auto
- Kind: live

## Transcript

[00:00:02] à à
[00:00:02] à à à à
[00:00:04] à à
[00:00:04] à à ừ ừ
[00:00:13] alo chào các bạn
[00:00:13] alo chào các bạn anh
[00:00:14] anh
[00:00:14] anh alo alo
[00:00:20] a
[00:00:20] a merry kỹ lại thì hôm trước
[00:00:24] merry kỹ lại thì hôm trước
[00:00:24] merry kỹ lại thì hôm trước hôm trước buổi I
[00:00:27] hôm trước buổi I
[00:00:27] hôm trước buổi I từ buổi đầu ra Switch có vẻ rất đông
[00:00:30] từ buổi đầu ra Switch có vẻ rất đông
[00:00:30] từ buổi đầu ra Switch có vẻ rất đông không bị không biết được hôm nay nó sẽ
[00:00:32] không bị không biết được hôm nay nó sẽ
[00:00:32] không bị không biết được hôm nay nó sẽ như thế nào nhưng mình tin là
[00:00:35] như thế nào nhưng mình tin là
[00:00:35] như thế nào nhưng mình tin là Ừ nó lại giống như mọi hôm thôi đó là
[00:00:40] Ừ nó lại giống như mọi hôm thôi đó là
[00:00:40] Ừ nó lại giống như mọi hôm thôi đó là mấy ông kia vào sen tò mò xong rồi cuối
[00:00:44] mấy ông kia vào sen tò mò xong rồi cuối
[00:00:44] mấy ông kia vào sen tò mò xong rồi cuối cùng thì mất tích ở
[00:00:54] nhưng mà ở cái này bây giờ vẫn đang
[00:00:54] nhưng mà ở cái này bây giờ vẫn đang trong thời gian tâm sự vậy nhỉ Mình tâm
[00:00:56] trong thời gian tâm sự vậy nhỉ Mình tâm
[00:00:56] trong thời gian tâm sự vậy nhỉ Mình tâm sự một đôi chút được ạ
[00:00:58] sự một đôi chút được ạ
[00:00:58] sự một đôi chút được ạ Ở mình vừa
[00:01:02] Ở mình vừa
[00:01:02] Ở mình vừa mình mình không biết mình kể các bạn
[00:01:05] mình mình không biết mình kể các bạn
[00:01:05] mình mình không biết mình kể các bạn chưa đó là mình có học liên thông
[00:01:08] chưa đó là mình có học liên thông
[00:01:08] chưa đó là mình có học liên thông Ừ ừ
[00:01:08] Ừ ừ
[00:01:08] Ừ ừ À ông Trường đó mình sẽ không tiện nói ở
[00:01:12] À ông Trường đó mình sẽ không tiện nói ở
[00:01:12] À ông Trường đó mình sẽ không tiện nói ở đây nhưng mà
[00:01:15] đây nhưng mà
[00:01:15] đây nhưng mà tưởng như là mình đã từng nói các bạn đó
[00:01:18] tưởng như là mình đã từng nói các bạn đó
[00:01:18] tưởng như là mình đã từng nói các bạn đó là học không quan trọng với cái bằng cấp
[00:01:21] là học không quan trọng với cái bằng cấp
[00:01:21] là học không quan trọng với cái bằng cấp lắm đây mình 10 lưu lại một vài ảnh cho
[00:01:24] lắm đây mình 10 lưu lại một vài ảnh cho
[00:01:24] lắm đây mình 10 lưu lại một vài ảnh cho các bạn xem luôn cái anh ấy mình đặt tên
[00:01:26] các bạn xem luôn cái anh ấy mình đặt tên
[00:01:26] các bạn xem luôn cái anh ấy mình đặt tên nó Min đấy
[00:01:33] Nghe đài thứ nhất là
[00:01:33] Nghe đài thứ nhất là cái ảnh này lấy từ trang tôi đi Quốc đã
[00:01:36] cái ảnh này lấy từ trang tôi đi Quốc đã
[00:01:36] cái ảnh này lấy từ trang tôi đi Quốc đã phải à
[00:01:44] em à Đang chung kết thế giới thế gì còn
[00:01:44] em à Đang chung kết thế giới thế gì còn hôm nay còn mắng nữa
[00:01:46] hôm nay còn mắng nữa
[00:01:46] hôm nay còn mắng nữa cho tôi tôi không xem là lâu nữa thông
[00:01:49] cho tôi tôi không xem là lâu nữa thông
[00:01:49] cho tôi tôi không xem là lâu nữa thông cạn tôi bị hơn một năm nay tôi không còn
[00:01:52] cạn tôi bị hơn một năm nay tôi không còn
[00:01:52] cạn tôi bị hơn một năm nay tôi không còn cầm tình về cái game này lắm vì nó cái
[00:01:55] cầm tình về cái game này lắm vì nó cái
[00:01:55] cầm tình về cái game này lắm vì nó cái điệp khúc thật Điệp lãi
[00:02:00] Ừ
[00:02:00] Ừ thì tôi mình Mình vừa mới lưu lại hai
[00:02:04] thì tôi mình Mình vừa mới lưu lại hai
[00:02:04] thì tôi mình Mình vừa mới lưu lại hai cái ảnh này một cái ảnh đấy
[00:02:08] cái ảnh này một cái ảnh đấy
[00:02:08] cái ảnh này một cái ảnh đấy Ngày ngay Ti có gì giỏi đâu mà cần người
[00:02:12] Ngày ngay Ti có gì giỏi đâu mà cần người
[00:02:12] Ngày ngay Ti có gì giỏi đâu mà cần người giỏi không ạ một cái thì là cái này
[00:02:31] Ờ Ờ
[00:02:31] Ờ Ờ cái này đại khái Nói tóm lại là kiểu
[00:02:35] cái này đại khái Nói tóm lại là kiểu
[00:02:35] cái này đại khái Nói tóm lại là kiểu quan trọng về kiểu nhái tin này quan
[00:02:37] quan trọng về kiểu nhái tin này quan
[00:02:37] quan trọng về kiểu nhái tin này quan trọng về kiến thức để mà đi thực tập rồi
[00:02:40] trọng về kiến thức để mà đi thực tập rồi
[00:02:40] trọng về kiến thức để mà đi thực tập rồi các thứ thứ thí nghiệm cái thứ hơn là là
[00:02:45] các thứ thứ thí nghiệm cái thứ hơn là là
[00:02:45] các thứ thứ thí nghiệm cái thứ hơn là là kiểu bằng cấp nhưng mà mình lại đang
[00:02:49] kiểu bằng cấp nhưng mà mình lại đang
[00:02:49] kiểu bằng cấp nhưng mà mình lại đang mình vừa nói là mình đang học lên hông
[00:02:52] mình vừa nói là mình đang học lên hông
[00:02:52] mình vừa nói là mình đang học lên hông ra chỉ cần là hai ngày cuối tuần thôi
[00:02:55] ra chỉ cần là hai ngày cuối tuần thôi
[00:02:55] ra chỉ cần là hai ngày cuối tuần thôi nhưng mà
[00:02:56] nhưng mà
[00:02:56] nhưng mà đi học nên thông ở Quốc để lấy cái bằng
[00:02:58] đi học nên thông ở Quốc để lấy cái bằng
[00:02:58] đi học nên thông ở Quốc để lấy cái bằng bằng đại học mình từ nói là mình cao
[00:03:03] bằng đại học mình từ nói là mình cao
[00:03:03] bằng đại học mình từ nói là mình cao đẳng nghề mày không ạ
[00:03:05] đẳng nghề mày không ạ
[00:03:05] đẳng nghề mày không ạ thì tại sao lại phải cần lấy cái bằng có
[00:03:08] thì tại sao lại phải cần lấy cái bằng có
[00:03:08] thì tại sao lại phải cần lấy cái bằng có cả để vì thực ra là
[00:03:10] cả để vì thực ra là
[00:03:10] cả để vì thực ra là về sau mình vẫn muốn quay lại đi dạy
[00:03:13] về sau mình vẫn muốn quay lại đi dạy
[00:03:13] về sau mình vẫn muốn quay lại đi dạy rằng ạ Không phải đi làm đây nhá Đi đi
[00:03:15] rằng ạ Không phải đi làm đây nhá Đi đi
[00:03:15] rằng ạ Không phải đi làm đây nhá Đi đi làm ở những công ty mà nó yêu cầu bằng
[00:03:17] làm ở những công ty mà nó yêu cầu bằng
[00:03:17] làm ở những công ty mà nó yêu cầu bằng cấp thì mình càng thích chứng minh là
[00:03:20] cấp thì mình càng thích chứng minh là
[00:03:20] cấp thì mình càng thích chứng minh là mình không cần bằng mình vẫn có thể vào
[00:03:22] mình không cần bằng mình vẫn có thể vào
[00:03:22] mình không cần bằng mình vẫn có thể vào được công ty đấy
[00:03:24] được công ty đấy
[00:03:24] được công ty đấy 3 - công ty ở nhà nước thì mày là khó
[00:03:27] 3 - công ty ở nhà nước thì mày là khó
[00:03:27] 3 - công ty ở nhà nước thì mày là khó nhưng mà còn công ty khác thì không quan
[00:03:30] nhưng mà còn công ty khác thì không quan
[00:03:30] nhưng mà còn công ty khác thì không quan trọng quan trọng người mình kinh nghiệm
[00:03:32] trọng quan trọng người mình kinh nghiệm
[00:03:32] trọng quan trọng người mình kinh nghiệm cái thứ thôi Ờ
[00:03:35] cái thứ thôi Ờ
[00:03:35] cái thứ thôi Ờ Ừ thì khi mà đi phỏng vấn thì các bạn
[00:03:40] Ừ thì khi mà đi phỏng vấn thì các bạn
[00:03:40] Ừ thì khi mà đi phỏng vấn thì các bạn khoe bằng cấp ra thì họ là là thứ mà họ
[00:03:45] khoe bằng cấp ra thì họ là là thứ mà họ
[00:03:45] khoe bằng cấp ra thì họ là là thứ mà họ sẽ nhìn sau cùng khi mà họ không có việc
[00:03:47] sẽ nhìn sau cùng khi mà họ không có việc
[00:03:47] sẽ nhìn sau cùng khi mà họ không có việc dinh Thịnh nhìn trong cái seri các bạn
[00:03:50] dinh Thịnh nhìn trong cái seri các bạn
[00:03:50] dinh Thịnh nhìn trong cái seri các bạn bé lý do mà các bạn để C gần đây nhất
[00:03:53] bé lý do mà các bạn để C gần đây nhất
[00:03:53] bé lý do mà các bạn để C gần đây nhất của mình ở chẳng có đề cập thì học ấy
[00:03:57] của mình ở chẳng có đề cập thì học ấy
[00:03:57] của mình ở chẳng có đề cập thì học ấy Ừ thì kệ Nhưng nhưng mà nhiều cái sim đi
[00:04:00] Ừ thì kệ Nhưng nhưng mà nhiều cái sim đi
[00:04:00] Ừ thì kệ Nhưng nhưng mà nhiều cái sim đi đấy rất nhiều người có thể inbox mình
[00:04:03] đấy rất nhiều người có thể inbox mình
[00:04:03] đấy rất nhiều người có thể inbox mình hỏi
[00:04:04] hỏi
[00:04:04] hỏi rất nhiều hát ở từ nhà Tuyển dụng bó hỏi
[00:04:07] rất nhiều hát ở từ nhà Tuyển dụng bó hỏi
[00:04:07] rất nhiều hát ở từ nhà Tuyển dụng bó hỏi là kiểu muốn về là mày có thứ thứ không
[00:04:10] là kiểu muốn về là mày có thứ thứ không
[00:04:10] là kiểu muốn về là mày có thứ thứ không khi họ họ có thể nhìn qua trình độ năng
[00:04:15] khi họ họ có thể nhìn qua trình độ năng
[00:04:15] khi họ họ có thể nhìn qua trình độ năng lực của mình không cần qua một cái bằng
[00:04:17] lực của mình không cần qua một cái bằng
[00:04:17] lực của mình không cần qua một cái bằng cấp gì
[00:04:18] cấp gì
[00:04:18] cấp gì - 1h r1h ở rất buồn cười Tự nhiên hát
[00:04:23] - 1h r1h ở rất buồn cười Tự nhiên hát
[00:04:23] - 1h r1h ở rất buồn cười Tự nhiên hát lời Hỏi CP của em trông chống trả Thế
[00:04:26] lời Hỏi CP của em trông chống trả Thế
[00:04:26] lời Hỏi CP của em trông chống trả Thế kiểu à
[00:04:28] kiểu à
[00:04:28] kiểu à anh em có thể nói qua một tí đó chị là
[00:04:32] anh em có thể nói qua một tí đó chị là
[00:04:32] anh em có thể nói qua một tí đó chị là em tự học ở đâu không giống như kiểu để
[00:04:34] em tự học ở đâu không giống như kiểu để
[00:04:34] em tự học ở đâu không giống như kiểu để mà gỡ điểm ấy và nghĩ rằng là mình mới
[00:04:36] mà gỡ điểm ấy và nghĩ rằng là mình mới
[00:04:36] mà gỡ điểm ấy và nghĩ rằng là mình mới vay mới ra trường anh Bởi vì lúc đầu đọc
[00:04:39] vay mới ra trường anh Bởi vì lúc đầu đọc
[00:04:39] vay mới ra trường anh Bởi vì lúc đầu đọc thì đọc nhầm tưởng không phải tự mình đi
[00:04:43] thì đọc nhầm tưởng không phải tự mình đi
[00:04:43] thì đọc nhầm tưởng không phải tự mình đi dạy ở cây trường kia mà mình học ở
[00:04:45] dạy ở cây trường kia mà mình học ở
[00:04:45] dạy ở cây trường kia mà mình học ở trường đấy mới ra trường ấy
[00:04:47] trường đấy mới ra trường ấy
[00:04:47] trường đấy mới ra trường ấy chị là buồn cười vậy
[00:04:50] chị là buồn cười vậy
[00:04:50] chị là buồn cười vậy I have have III nhá Không cần nhìn bằng
[00:04:55] I have have III nhá Không cần nhìn bằng
[00:04:55] I have have III nhá Không cần nhìn bằng cấp nhấn mạnh lại họ Cùng lắm chỉ cần
[00:04:59] cấp nhấn mạnh lại họ Cùng lắm chỉ cần
[00:04:59] cấp nhấn mạnh lại họ Cùng lắm chỉ cần nhìn xem thứ nhất là kính nhựa mày thứ 2
[00:05:04] nhìn xem thứ nhất là kính nhựa mày thứ 2
[00:05:04] nhìn xem thứ nhất là kính nhựa mày thứ 2 là ông biết thì anh càng tốt để mà Bây
[00:05:08] là ông biết thì anh càng tốt để mà Bây
[00:05:08] là ông biết thì anh càng tốt để mà Bây giờ làm công ty nước ngoài thì nhiều kết
[00:05:11] giờ làm công ty nước ngoài thì nhiều kết
[00:05:11] giờ làm công ty nước ngoài thì nhiều kết nối công ty nước ngoài nhiều
[00:05:12] nối công ty nước ngoài nhiều
[00:05:12] nối công ty nước ngoài nhiều à à
[00:05:20] ờ
[00:05:20] ờ ờ bà vừa nãy mình mình nói là mình học
[00:05:25] ờ bà vừa nãy mình mình nói là mình học
[00:05:25] ờ bà vừa nãy mình mình nói là mình học lên Hồng cốt để mà cậu về sau mình đi
[00:05:29] lên Hồng cốt để mà cậu về sau mình đi
[00:05:29] lên Hồng cốt để mà cậu về sau mình đi dạy lại thì ở đại học chính quy thì họ
[00:05:32] dạy lại thì ở đại học chính quy thì họ
[00:05:32] dạy lại thì ở đại học chính quy thì họ vẫn cần bằng bằng Đại hạ bằng cử nhân
[00:05:35] vẫn cần bằng bằng Đại hạ bằng cử nhân
[00:05:36] vẫn cần bằng bằng Đại hạ bằng cử nhân hậu chữa thạc sĩ để mà đứng lớp dạy
[00:05:39] hậu chữa thạc sĩ để mà đứng lớp dạy
[00:05:39] hậu chữa thạc sĩ để mà đứng lớp dạy Ừ nhưng mà tiện đây mình cũng xin nói
[00:05:42] Ừ nhưng mà tiện đây mình cũng xin nói
[00:05:42] Ừ nhưng mà tiện đây mình cũng xin nói cái này đó là đấy thì cái vụ mà mình đã
[00:05:46] cái này đó là đấy thì cái vụ mà mình đã
[00:05:46] cái này đó là đấy thì cái vụ mà mình đã hợp lý thâm như này và mình cũng học ở
[00:05:48] hợp lý thâm như này và mình cũng học ở
[00:05:48] hợp lý thâm như này và mình cũng học ở mình cũng
[00:05:51] mình cũng
[00:05:51] mình cũng Em Khóc Làm biết qua một vài trường đại
[00:05:54] Em Khóc Làm biết qua một vài trường đại
[00:05:54] Em Khóc Làm biết qua một vài trường đại học dạy ở
[00:05:56] học dạy ở
[00:05:56] học dạy ở Lập trình đền hình à Hôm nay mình còn
[00:05:59] Lập trình đền hình à Hôm nay mình còn
[00:05:59] Lập trình đền hình à Hôm nay mình còn học lập trình web này
[00:06:01] học lập trình web này
[00:06:01] học lập trình web này khi nhìn thấy các thầy cô đấy Dậy có vẻ
[00:06:05] khi nhìn thấy các thầy cô đấy Dậy có vẻ
[00:06:05] khi nhìn thấy các thầy cô đấy Dậy có vẻ rất là kiểu
[00:06:09] rất là kiểu
[00:06:09] rất là kiểu mình khẳng định là có thể cách cách thầy
[00:06:12] mình khẳng định là có thể cách cách thầy
[00:06:12] mình khẳng định là có thể cách cách thầy cô ấy dậy có thể làm nhão hơn của mình
[00:06:14] cô ấy dậy có thể làm nhão hơn của mình
[00:06:14] cô ấy dậy có thể làm nhão hơn của mình nhạt nhẽo phải dùng từ nhão thịt Bởi vì
[00:06:17] nhạt nhẽo phải dùng từ nhão thịt Bởi vì
[00:06:17] nhạt nhẽo phải dùng từ nhão thịt Bởi vì các thầy cô chẳng có ví dụ gì cả câu
[00:06:20] các thầy cô chẳng có ví dụ gì cả câu
[00:06:20] các thầy cô chẳng có ví dụ gì cả câu thầy cô ấy chỉ nói lý thuyết khá dài hở
[00:06:23] thầy cô ấy chỉ nói lý thuyết khá dài hở
[00:06:23] thầy cô ấy chỉ nói lý thuyết khá dài hở việc là
[00:06:25] việc là
[00:06:25] việc là không quan tâm đến sinh viên lắm không
[00:06:28] không quan tâm đến sinh viên lắm không
[00:06:28] không quan tâm đến sinh viên lắm không quan tâm sinh viên kiểu có đàn tập trung
[00:06:31] quan tâm sinh viên kiểu có đàn tập trung
[00:06:31] quan tâm sinh viên kiểu có đàn tập trung nghe không có đang hào hứng có Giang
[00:06:33] nghe không có đang hào hứng có Giang
[00:06:33] nghe không có đang hào hứng có Giang thích thú với cái việc mình đang dạy
[00:06:35] thích thú với cái việc mình đang dạy
[00:06:35] thích thú với cái việc mình đang dạy không khen mình mới phải dùng từ là nhạt
[00:06:38] không khen mình mới phải dùng từ là nhạt
[00:06:38] không khen mình mới phải dùng từ là nhạt nhẽo Bởi vì các thầy cô ấy
[00:06:42] nhẽo Bởi vì các thầy cô ấy
[00:06:42] nhẽo Bởi vì các thầy cô ấy Em đang dạy cho có chứ không Không hẳn
[00:06:46] Em đang dạy cho có chứ không Không hẳn
[00:06:46] Em đang dạy cho có chứ không Không hẳn là có cái tâm của người dậy
[00:06:49] là có cái tâm của người dậy
[00:06:49] là có cái tâm của người dậy cho mình và mình vào cây thầy thầy cô
[00:06:54] cho mình và mình vào cây thầy thầy cô
[00:06:54] cho mình và mình vào cây thầy thầy cô lấy còn vứt vứt cho sinh viên bọn mình
[00:06:58] lấy còn vứt vứt cho sinh viên bọn mình
[00:06:58] lấy còn vứt vứt cho sinh viên bọn mình cái kênh kênh YouTube để mà vào xem của
[00:07:02] cái kênh kênh YouTube để mà vào xem của
[00:07:02] cái kênh kênh YouTube để mà vào xem của họ kiểu để câu như vậy kênh đấy cậu
[00:07:07] họ kiểu để câu như vậy kênh đấy cậu
[00:07:07] họ kiểu để câu như vậy kênh đấy cậu hơn 100 nghìn lượt xem
[00:07:10] hơn 100 nghìn lượt xem
[00:07:10] hơn 100 nghìn lượt xem ở Châu Á
[00:07:13] ở Châu Á
[00:07:13] ở Châu Á em dại dại rất là chán ấy một cái bài
[00:07:17] em dại dại rất là chán ấy một cái bài
[00:07:17] em dại dại rất là chán ấy một cái bài một cái bài hát Hà Tĩnh mà Lờ kéo dài
[00:07:21] một cái bài hát Hà Tĩnh mà Lờ kéo dài
[00:07:21] một cái bài hát Hà Tĩnh mà Lờ kéo dài mười mấy bài xong rồi cậu nói cũng mông
[00:07:25] mười mấy bài xong rồi cậu nói cũng mông
[00:07:25] mười mấy bài xong rồi cậu nói cũng mông lung kiểu gì sẽ như Cực
[00:07:33] Ừ đấy thì mình mới cảm thấy à Cậu sự thì
[00:07:33] Ừ đấy thì mình mới cảm thấy à Cậu sự thì nhiều lúc mình muốn lá vào đại học chính
[00:07:36] nhiều lúc mình muốn lá vào đại học chính
[00:07:36] nhiều lúc mình muốn lá vào đại học chính quy để mà dậy để mà
[00:07:39] quy để mà dậy để mà
[00:07:39] quy để mà dậy để mà biết đâu Mình có thể
[00:07:42] biết đâu Mình có thể
[00:07:42] biết đâu Mình có thể cứu phải dùng từng cứu bởi vì có nhiều
[00:07:46] cứu phải dùng từng cứu bởi vì có nhiều
[00:07:46] cứu phải dùng từng cứu bởi vì có nhiều bạn
[00:07:47] bạn
[00:07:47] bạn các bạn bè của mình Minh Minh bảo rồi
[00:07:51] các bạn bè của mình Minh Minh bảo rồi
[00:07:51] các bạn bè của mình Minh Minh bảo rồi Mình không học đại học chính quy nên là
[00:07:54] Mình không học đại học chính quy nên là
[00:07:54] Mình không học đại học chính quy nên là mình không thể khẳng định được việc chất
[00:07:57] mình không thể khẳng định được việc chất
[00:07:57] mình không thể khẳng định được việc chất lượng dạy của họ như nào ở phía sau khi
[00:07:59] lượng dạy của họ như nào ở phía sau khi
[00:07:59] lượng dạy của họ như nào ở phía sau khi rét và có nhiều người quen với kiểu dạy
[00:08:01] rét và có nhiều người quen với kiểu dạy
[00:08:01] rét và có nhiều người quen với kiểu dạy đấy thì đúng nhưng
[00:08:05] đấy thì đúng nhưng
[00:08:05] đấy thì đúng nhưng Ừ mình vẫn thấy là có rất nhiều bạn bè
[00:08:08] Ừ mình vẫn thấy là có rất nhiều bạn bè
[00:08:08] Ừ mình vẫn thấy là có rất nhiều bạn bè của mình học đại học chính quy
[00:08:10] của mình học đại học chính quy
[00:08:10] của mình học đại học chính quy đại học Bách Khoa loa nhé
[00:08:13] đại học Bách Khoa loa nhé
[00:08:13] đại học Bách Khoa loa nhé bạn đấy làm bạn để bỏ cái ngành này cho
[00:08:18] bạn đấy làm bạn để bỏ cái ngành này cho
[00:08:18] bạn đấy làm bạn để bỏ cái ngành này cho dù bão từng đam mê giống mình
[00:08:20] dù bão từng đam mê giống mình
[00:08:20] dù bão từng đam mê giống mình đã từng đam mê dù mình chẳng qua là hai
[00:08:24] đã từng đam mê dù mình chẳng qua là hai
[00:08:24] đã từng đam mê dù mình chẳng qua là hai người học ở hai môi trường khác nhau
[00:08:27] người học ở hai môi trường khác nhau
[00:08:27] người học ở hai môi trường khác nhau vì thế mà cuối cùng thì bây giờ thì mình
[00:08:29] vì thế mà cuối cùng thì bây giờ thì mình
[00:08:29] vì thế mà cuối cùng thì bây giờ thì mình có vẻ khá là ổn khá là ổn thôi còn bạn
[00:08:33] có vẻ khá là ổn khá là ổn thôi còn bạn
[00:08:33] có vẻ khá là ổn khá là ổn thôi còn bạn đấy thì Bỏ hẳn
[00:08:34] đấy thì Bỏ hẳn
[00:08:34] đấy thì Bỏ hẳn Cho mình hỏi tại sao thì bạn ấy bảo là
[00:08:36] Cho mình hỏi tại sao thì bạn ấy bảo là
[00:08:36] Cho mình hỏi tại sao thì bạn ấy bảo là học trên trường rất chán học và chiến
[00:08:39] học trên trường rất chán học và chiến
[00:08:39] học trên trường rất chán học và chiến trường làm cho tao kiểu nhụt Chí Hơn vẫn
[00:08:43] trường làm cho tao kiểu nhụt Chí Hơn vẫn
[00:08:43] trường làm cho tao kiểu nhụt Chí Hơn vẫn Vân Vân Vân Vân Nam mình cảm thấy kiểu
[00:08:46] Vân Vân Vân Vân Nam mình cảm thấy kiểu
[00:08:46] Vân Vân Vân Vân Nam mình cảm thấy kiểu thế thì say mất rồi đôi đổi đời với mình
[00:08:50] thế thì say mất rồi đôi đổi đời với mình
[00:08:50] thế thì say mất rồi đôi đổi đời với mình quan điểm nhé cái việc dạy học ở đại học
[00:08:53] quan điểm nhé cái việc dạy học ở đại học
[00:08:53] quan điểm nhé cái việc dạy học ở đại học đúng là tự học vẫn là nhiều
[00:08:56] đúng là tự học vẫn là nhiều
[00:08:56] đúng là tự học vẫn là nhiều Chị chuẩn là phải dạy cho các bạn kiến
[00:08:59] Chị chuẩn là phải dạy cho các bạn kiến
[00:08:59] Chị chuẩn là phải dạy cho các bạn kiến thức tự học đương nhiên là mình đang dậy
[00:09:01] thức tự học đương nhiên là mình đang dậy
[00:09:01] thức tự học đương nhiên là mình đang dậy các bạn theo kiểu là cầm tay chỉ lỗi
[00:09:03] các bạn theo kiểu là cầm tay chỉ lỗi
[00:09:03] các bạn theo kiểu là cầm tay chỉ lỗi nhiều quá Thực ra nó không tốt cả vẫn
[00:09:06] nhiều quá Thực ra nó không tốt cả vẫn
[00:09:06] nhiều quá Thực ra nó không tốt cả vẫn phải dạy các bạn toàn bộ cơ bản thì các
[00:09:08] phải dạy các bạn toàn bộ cơ bản thì các
[00:09:08] phải dạy các bạn toàn bộ cơ bản thì các bạn tự học nhưng
[00:09:11] bạn tự học nhưng
[00:09:11] bạn tự học nhưng Ừ nhưng mà sẽ truyền được các bạn cảm
[00:09:14] Ừ nhưng mà sẽ truyền được các bạn cảm
[00:09:14] Ừ nhưng mà sẽ truyền được các bạn cảm hứng để các bạn có thể tự họp có thể
[00:09:17] hứng để các bạn có thể tự họp có thể
[00:09:17] hứng để các bạn có thể tự họp có thể muốn học nhưng mà đây là không không
[00:09:20] muốn học nhưng mà đây là không không
[00:09:20] muốn học nhưng mà đây là không không chuyển được các bạn Cảm hứng mà còn làm
[00:09:22] chuyển được các bạn Cảm hứng mà còn làm
[00:09:22] chuyển được các bạn Cảm hứng mà còn làm cho các bạn nạn đi Đấy là size của Mục
[00:09:26] cho các bạn nạn đi Đấy là size của Mục
[00:09:26] cho các bạn nạn đi Đấy là size của Mục đích dạy đại học tối có điểm mình ở thế
[00:09:29] đích dạy đại học tối có điểm mình ở thế
[00:09:29] đích dạy đại học tối có điểm mình ở thế các điểm của mình đó là đại học thì
[00:09:33] các điểm của mình đó là đại học thì
[00:09:33] các điểm của mình đó là đại học thì khác với Tiểu học với trung học đó là
[00:09:36] khác với Tiểu học với trung học đó là
[00:09:36] khác với Tiểu học với trung học đó là kiểu đôn đốc từng bạn một rồi xong rồi
[00:09:40] kiểu đôn đốc từng bạn một rồi xong rồi
[00:09:40] kiểu đôn đốc từng bạn một rồi xong rồi Kiểu giỗ rồi kìa em ơi là mày đi rồi
[00:09:43] Kiểu giỗ rồi kìa em ơi là mày đi rồi
[00:09:43] Kiểu giỗ rồi kìa em ơi là mày đi rồi kiểm tra bài không để học chuẩn đấy nó
[00:09:46] kiểm tra bài không để học chuẩn đấy nó
[00:09:46] kiểm tra bài không để học chuẩn đấy nó là kiểu dạy có vào tiền thức cơ bản có
[00:09:50] là kiểu dạy có vào tiền thức cơ bản có
[00:09:50] là kiểu dạy có vào tiền thức cơ bản có kiến thức chuyên sâu và cư truyền các
[00:09:54] kiến thức chuyên sâu và cư truyền các
[00:09:54] kiến thức chuyên sâu và cư truyền các bạn cảm hứng và Ai thắc mắc gì thì hỏi
[00:09:58] bạn cảm hứng và Ai thắc mắc gì thì hỏi
[00:09:58] bạn cảm hứng và Ai thắc mắc gì thì hỏi còn không thì chủ yếu vẫn là tự học anh
[00:10:02] còn không thì chủ yếu vẫn là tự học anh
[00:10:02] còn không thì chủ yếu vẫn là tự học anh Bởi vì đây là cái nhàng cái nghề đó bạn
[00:10:06] Bởi vì đây là cái nhàng cái nghề đó bạn
[00:10:06] Bởi vì đây là cái nhàng cái nghề đó bạn các bạn học để làm theo cái nghề này chứ
[00:10:09] các bạn học để làm theo cái nghề này chứ
[00:10:09] các bạn học để làm theo cái nghề này chứ không phải là đại học bây giờ là kiểu lý
[00:10:13] không phải là đại học bây giờ là kiểu lý
[00:10:13] không phải là đại học bây giờ là kiểu lý thuyết thì quá nhiều
[00:10:14] thuyết thì quá nhiều
[00:10:14] thuyết thì quá nhiều màn những thiết thừa cũng quá nhiều thừa
[00:10:18] màn những thiết thừa cũng quá nhiều thừa
[00:10:18] màn những thiết thừa cũng quá nhiều thừa ở đây ấy chỉ là
[00:10:20] ở đây ấy chỉ là
[00:10:20] ở đây ấy chỉ là anh một lúc dạy cho các bạn Ok thì đúng
[00:10:24] anh một lúc dạy cho các bạn Ok thì đúng
[00:10:24] anh một lúc dạy cho các bạn Ok thì đúng là dậy rồi các bạn 3 4 ngôn ngữ lập
[00:10:26] là dậy rồi các bạn 3 4 ngôn ngữ lập
[00:10:26] là dậy rồi các bạn 3 4 ngôn ngữ lập trình để các bạn tự chọn cũng được không
[00:10:28] trình để các bạn tự chọn cũng được không
[00:10:28] trình để các bạn tự chọn cũng được không sao nhưng mà
[00:10:30] sao nhưng mà
[00:10:30] sao nhưng mà anh không hướng rồi các bạn một cái gì
[00:10:33] anh không hướng rồi các bạn một cái gì
[00:10:33] anh không hướng rồi các bạn một cái gì đó để cho mà sinh viên năm 4 năm 5 vẫn
[00:10:37] đó để cho mà sinh viên năm 4 năm 5 vẫn
[00:10:37] đó để cho mà sinh viên năm 4 năm 5 vẫn còn đi
[00:10:38] còn đi
[00:10:38] còn đi anh vẫn còn chưa biết tương lai mình sẽ
[00:10:41] anh vẫn còn chưa biết tương lai mình sẽ
[00:10:41] anh vẫn còn chưa biết tương lai mình sẽ như nào đi thực tập Sẽ như nào vẫn vân
[00:10:44] như nào đi thực tập Sẽ như nào vẫn vân
[00:10:44] như nào đi thực tập Sẽ như nào vẫn vân vân bên trường mình ý định hướng về việc
[00:10:48] vân bên trường mình ý định hướng về việc
[00:10:48] vân bên trường mình ý định hướng về việc đi Được tập ngay từ đầu năm 2 ngày nào
[00:10:51] đi Được tập ngay từ đầu năm 2 ngày nào
[00:10:51] đi Được tập ngay từ đầu năm 2 ngày nào cũng nhắc đi nhắc lại với sinh viên với
[00:10:54] cũng nhắc đi nhắc lại với sinh viên với
[00:10:54] cũng nhắc đi nhắc lại với sinh viên với việc đi thực tập để cho đến cuối năm và
[00:10:56] việc đi thực tập để cho đến cuối năm và
[00:10:56] việc đi thực tập để cho đến cuối năm và đi thực tập thật
[00:10:57] đi thực tập thật
[00:10:58] đi thực tập thật 27 nghĩa là chuẩn là như thế
[00:11:02] 27 nghĩa là chuẩn là như thế
[00:11:02] 27 nghĩa là chuẩn là như thế các bạn trên nhắc đến từ nước ngoài nước
[00:11:04] các bạn trên nhắc đến từ nước ngoài nước
[00:11:04] các bạn trên nhắc đến từ nước ngoài nước ngoài kể cái việc dạy đại học nước ngoài
[00:11:06] ngoài kể cái việc dạy đại học nước ngoài
[00:11:06] ngoài kể cái việc dạy đại học nước ngoài nó còn rất hay như thế này nhé đó là đã
[00:11:10] nó còn rất hay như thế này nhé đó là đã
[00:11:10] nó còn rất hay như thế này nhé đó là đã học của mình đang bị kiểu mình mình ăn
[00:11:14] học của mình đang bị kiểu mình mình ăn
[00:11:14] học của mình đang bị kiểu mình mình ăn mình hình như mình bị Rập khuôn trong
[00:11:16] mình hình như mình bị Rập khuôn trong
[00:11:16] mình hình như mình bị Rập khuôn trong đầu là ai cần có cái bằng đại học đấy
[00:11:18] đầu là ai cần có cái bằng đại học đấy
[00:11:18] đầu là ai cần có cái bằng đại học đấy còn bên nước ngoài sang hoàn toàn nhé
[00:11:20] còn bên nước ngoài sang hoàn toàn nhé
[00:11:20] còn bên nước ngoài sang hoàn toàn nhé bên nước ngoài thứ nhất là tiền học phí
[00:11:23] bên nước ngoài thứ nhất là tiền học phí
[00:11:23] bên nước ngoài thứ nhất là tiền học phí của họ rất đắt đại học ấy các bạn hiền
[00:11:27] của họ rất đắt đại học ấy các bạn hiền
[00:11:27] của họ rất đắt đại học ấy các bạn hiền như toàn thấy nợ rồi
[00:11:29] như toàn thấy nợ rồi
[00:11:29] như toàn thấy nợ rồi gì để mà thực sự là các bạn muốn muốn có
[00:11:33] gì để mà thực sự là các bạn muốn muốn có
[00:11:33] gì để mà thực sự là các bạn muốn muốn có muốn có cái bằng thật muốn muốn học đại
[00:11:37] muốn có cái bằng thật muốn muốn học đại
[00:11:37] muốn có cái bằng thật muốn muốn học đại học thật thì các bạn sẽ phải
[00:11:40] học thật thì các bạn sẽ phải
[00:11:40] học thật thì các bạn sẽ phải chị sẽ phải rất là chịu khó và sẽ rất là
[00:11:44] chị sẽ phải rất là chịu khó và sẽ rất là
[00:11:44] chị sẽ phải rất là chịu khó và sẽ rất là tốn kém nó sẽ cho các bạn nợ nhưng mà
[00:11:47] tốn kém nó sẽ cho các bạn nợ nhưng mà
[00:11:47] tốn kém nó sẽ cho các bạn nợ nhưng mà các bạn sẽ phải đi thực tập đi làm để mà
[00:11:50] các bạn sẽ phải đi thực tập đi làm để mà
[00:11:50] các bạn sẽ phải đi thực tập đi làm để mà chả thấy cái nợ đấy những thành ra ở bên
[00:11:52] chả thấy cái nợ đấy những thành ra ở bên
[00:11:52] chả thấy cái nợ đấy những thành ra ở bên bên nước ngoài thì chỉ những ngày nào
[00:11:55] bên nước ngoài thì chỉ những ngày nào
[00:11:55] bên nước ngoài thì chỉ những ngày nào thực sự có nhu cầu cần và thực sự thèm
[00:11:57] thực sự có nhu cầu cần và thực sự thèm
[00:11:57] thực sự có nhu cầu cần và thực sự thèm muốn theo thì mới
[00:12:00] muốn theo thì mới
[00:12:00] muốn theo thì mới em mới học đại học
[00:12:02] em mới học đại học
[00:12:02] em mới học đại học anh ở bên nước ngoài như thế
[00:12:04] anh ở bên nước ngoài như thế
[00:12:04] anh ở bên nước ngoài như thế Vì thế nên là và bên nước ngoài nó sẽ
[00:12:07] Vì thế nên là và bên nước ngoài nó sẽ
[00:12:07] Vì thế nên là và bên nước ngoài nó sẽ càng ngày càng cố hướng đến thực tế nghề
[00:12:12] càng ngày càng cố hướng đến thực tế nghề
[00:12:12] càng ngày càng cố hướng đến thực tế nghề đang có gì nhất mình xem đại học ở bến
[00:12:15] đang có gì nhất mình xem đại học ở bến
[00:12:15] đang có gì nhất mình xem đại học ở bến nước ngoài đứng nghĩa là công nghệ họ có
[00:12:17] nước ngoài đứng nghĩa là công nghệ họ có
[00:12:17] nước ngoài đứng nghĩa là công nghệ họ có thể hơn nhé Thành ra họ đang dậy bị cáo
[00:12:20] thể hơn nhé Thành ra họ đang dậy bị cáo
[00:12:20] thể hơn nhé Thành ra họ đang dậy bị cáo này xong dậy ai Cái thứ B gần đây thì
[00:12:23] này xong dậy ai Cái thứ B gần đây thì
[00:12:23] này xong dậy ai Cái thứ B gần đây thì trường đại học mình mới có nhưng mà vẫn
[00:12:27] trường đại học mình mới có nhưng mà vẫn
[00:12:27] trường đại học mình mới có nhưng mà vẫn kiến thức Hà Lâm quá còn ở bên ngoài
[00:12:29] kiến thức Hà Lâm quá còn ở bên ngoài
[00:12:29] kiến thức Hà Lâm quá còn ở bên ngoài thực thực tế rất nhiều rất nhiều luôn
[00:12:31] thực thực tế rất nhiều rất nhiều luôn
[00:12:31] thực thực tế rất nhiều rất nhiều luôn Làm hẳn dự án được thế rất nhiều mang
[00:12:34] Làm hẳn dự án được thế rất nhiều mang
[00:12:34] Làm hẳn dự án được thế rất nhiều mang tiếng là đã học chứ hỏi ở trường Cao
[00:12:36] tiếng là đã học chứ hỏi ở trường Cao
[00:12:36] tiếng là đã học chứ hỏi ở trường Cao đẳng nghề đâu nhé
[00:12:38] đẳng nghề đâu nhé
[00:12:38] đẳng nghề đâu nhé ý nghĩa bên đấy ăn Dậy đúng cả làng nghề
[00:12:41] ý nghĩa bên đấy ăn Dậy đúng cả làng nghề
[00:12:41] ý nghĩa bên đấy ăn Dậy đúng cả làng nghề nhiều hơn con bên mình thì
[00:12:44] nhiều hơn con bên mình thì
[00:12:44] nhiều hơn con bên mình thì anh
[00:12:44] anh
[00:12:44] anh vẫn bị phải đến quá nửa học đại học là
[00:12:48] vẫn bị phải đến quá nửa học đại học là
[00:12:48] vẫn bị phải đến quá nửa học đại học là theo phong trào theo kiểu lại
[00:12:50] theo phong trào theo kiểu lại
[00:12:50] theo phong trào theo kiểu lại Lý do là
[00:12:52] Lý do là
[00:12:52] Lý do là dòng họ em ai cũng học đại học rồi đều
[00:12:56] dòng họ em ai cũng học đại học rồi đều
[00:12:56] dòng họ em ai cũng học đại học rồi đều có cái bằng đại học bây giờ em kiểu gì
[00:12:59] có cái bằng đại học bây giờ em kiểu gì
[00:12:59] có cái bằng đại học bây giờ em kiểu gì phải có sẽ nặn Thế có rỡ là em không
[00:13:02] phải có sẽ nặn Thế có rỡ là em không
[00:13:02] phải có sẽ nặn Thế có rỡ là em không thích học đã học em thích học nghề nhanh
[00:13:06] thích học đã học em thích học nghề nhanh
[00:13:06] thích học đã học em thích học nghề nhanh để đi làm chẳng ạ ạ
[00:13:14] Ừ nhưng mà nãy giờ mình đang nói còn
[00:13:14] Ừ nhưng mà nãy giờ mình đang nói còn những cái vấn đề nó hơi bị
[00:13:16] những cái vấn đề nó hơi bị
[00:13:16] những cái vấn đề nó hơi bị Ừ thứ nhất là nó nhức nhối sẽ chắn bởi
[00:13:18] Ừ thứ nhất là nó nhức nhối sẽ chắn bởi
[00:13:18] Ừ thứ nhất là nó nhức nhối sẽ chắn bởi vì đến bây giờ nó vẫn đây nhưng mà nó
[00:13:21] vì đến bây giờ nó vẫn đây nhưng mà nó
[00:13:21] vì đến bây giờ nó vẫn đây nhưng mà nó hơi bị nhạy cảm thì thấy cha mình tạ
[00:13:24] hơi bị nhạy cảm thì thấy cha mình tạ
[00:13:24] hơi bị nhạy cảm thì thấy cha mình tạ thôi
[00:13:25] thôi
[00:13:25] thôi em không mặc bay kênh Ừ nhưng mà
[00:13:29] em không mặc bay kênh Ừ nhưng mà
[00:13:29] em không mặc bay kênh Ừ nhưng mà thì mình nghĩ là nãy giờ mình nói không
[00:13:31] thì mình nghĩ là nãy giờ mình nói không
[00:13:31] thì mình nghĩ là nãy giờ mình nói không có tí gì xinh ta cả cái nên thành ra
[00:13:34] có tí gì xinh ta cả cái nên thành ra
[00:13:34] có tí gì xinh ta cả cái nên thành ra Chắc không sao đâu Hoặc là mình chưa nổi
[00:13:37] Chắc không sao đâu Hoặc là mình chưa nổi
[00:13:37] Chắc không sao đâu Hoặc là mình chưa nổi để mọi người biết đến không ạ ạ
[00:13:47] anh không kịp kìa
[00:13:47] anh không kịp kìa bố mẹ bố mẹ các bạn thì mình không biết
[00:13:50] bố mẹ bố mẹ các bạn thì mình không biết
[00:13:50] bố mẹ bố mẹ các bạn thì mình không biết con điểm nào nhưng mẹ mình thì từng là
[00:13:52] con điểm nào nhưng mẹ mình thì từng là
[00:13:52] con điểm nào nhưng mẹ mình thì từng là một người mà kiểu
[00:13:55] một người mà kiểu
[00:13:55] một người mà kiểu đến cả Chín Nghĩa mà còn đánh mình
[00:13:58] đến cả Chín Nghĩa mà còn đánh mình
[00:13:58] đến cả Chín Nghĩa mà còn đánh mình anh đòi 10 cơ tại sao mày không được 10
[00:14:01] anh đòi 10 cơ tại sao mày không được 10
[00:14:01] anh đòi 10 cơ tại sao mày không được 10 rõ ràng là cái này mày làm được như là
[00:14:04] rõ ràng là cái này mày làm được như là
[00:14:04] rõ ràng là cái này mày làm được như là do mày Vân ơn ai bây giờ xz mày mày chơi
[00:14:08] do mày Vân ơn ai bây giờ xz mày mày chơi
[00:14:08] do mày Vân ơn ai bây giờ xz mày mày chơi mà chủ quan nên mày mới chỉ 9 thôi đấy
[00:14:10] mà chủ quan nên mày mới chỉ 9 thôi đấy
[00:14:10] mà chủ quan nên mày mới chỉ 9 thôi đấy có sư thứ nói chung và mẹ mình con người
[00:14:13] có sư thứ nói chung và mẹ mình con người
[00:14:13] có sư thứ nói chung và mẹ mình con người làm cho mình rất là cầu toàn
[00:14:15] làm cho mình rất là cầu toàn
[00:14:15] làm cho mình rất là cầu toàn Nhưng mà khi mà lên khi mà lên cấp 3 khi
[00:14:20] Nhưng mà khi mà lên khi mà lên cấp 3 khi
[00:14:21] Nhưng mà khi mà lên khi mà lên cấp 3 khi mà gần thi đại học đấy Mẹ kiểu khiến
[00:14:25] mà gần thi đại học đấy Mẹ kiểu khiến
[00:14:25] mà gần thi đại học đấy Mẹ kiểu khiến mình ra thoải mái theo kiểu là thực ra
[00:14:27] mình ra thoải mái theo kiểu là thực ra
[00:14:27] mình ra thoải mái theo kiểu là thực ra mẹ mình không quan tâm mình được mình
[00:14:29] mẹ mình không quan tâm mình được mình
[00:14:29] mẹ mình không quan tâm mình được mình chưa thay đổ đại học luôn không quan tâm
[00:14:32] chưa thay đổ đại học luôn không quan tâm
[00:14:32] chưa thay đổ đại học luôn không quan tâm mình học trường nào thật chứ không học
[00:14:34] mình học trường nào thật chứ không học
[00:14:34] mình học trường nào thật chứ không học đại học cũng được mẹ bà là bây giờ Mày
[00:14:36] đại học cũng được mẹ bà là bây giờ Mày
[00:14:36] đại học cũng được mẹ bà là bây giờ Mày đủ tuổi chín chắn rồi mẹ chỉ còn mà chỉ
[00:14:39] đủ tuổi chín chắn rồi mẹ chỉ còn mà chỉ
[00:14:39] đủ tuổi chín chắn rồi mẹ chỉ còn mà chỉ cần mày nên người mày Cậu biết nhận thức
[00:14:42] cần mày nên người mày Cậu biết nhận thức
[00:14:42] cần mày nên người mày Cậu biết nhận thức được cái nào đúng cái nào sai kiểu nói
[00:14:46] được cái nào đúng cái nào sai kiểu nói
[00:14:46] được cái nào đúng cái nào sai kiểu nói chung là trở Hạnh con người
[00:14:48] chung là trở Hạnh con người
[00:14:48] chung là trở Hạnh con người anh là được mà dùng từ chợ thành con
[00:14:51] anh là được mà dùng từ chợ thành con
[00:14:51] anh là được mà dùng từ chợ thành con người ngày ăn Chị ạ kiểu một con người
[00:14:54] người ngày ăn Chị ạ kiểu một con người
[00:14:54] người ngày ăn Chị ạ kiểu một con người cậu biết phân biệt ở đúng sai hướng
[00:14:56] cậu biết phân biệt ở đúng sai hướng
[00:14:56] cậu biết phân biệt ở đúng sai hướng thiện cái thứ thứ
[00:14:58] thiện cái thứ thứ
[00:14:58] thiện cái thứ thứ em không cần phải kiểu
[00:15:01] em không cần phải kiểu
[00:15:01] em không cần phải kiểu em có rảnh phải cực kì vọng Giang Cái gì
[00:15:04] em có rảnh phải cực kì vọng Giang Cái gì
[00:15:04] em có rảnh phải cực kì vọng Giang Cái gì đó phía sau mình chắc là mình sẽ giận
[00:15:06] đó phía sau mình chắc là mình sẽ giận
[00:15:06] đó phía sau mình chắc là mình sẽ giận con mình như thế không Không đến nỗi là
[00:15:09] con mình như thế không Không đến nỗi là
[00:15:09] con mình như thế không Không đến nỗi là cậu ép con cầu toàn nữa mà mình không
[00:15:12] cậu ép con cầu toàn nữa mà mình không
[00:15:12] cậu ép con cầu toàn nữa mà mình không ngờ mong con mình thông minh mình mong
[00:15:14] ngờ mong con mình thông minh mình mong
[00:15:14] ngờ mong con mình thông minh mình mong con mình biết từng nhân xử thế và nên
[00:15:17] con mình biết từng nhân xử thế và nên
[00:15:17] con mình biết từng nhân xử thế và nên người thế không thì tôi sẽ dần nó ra đã
[00:15:23] người thế không thì tôi sẽ dần nó ra đã
[00:15:23] người thế không thì tôi sẽ dần nó ra đã à à
[00:15:24] à à
[00:15:24] à à ờ ờ
[00:15:26] ờ ờ
[00:15:26] ờ ờ Ok nói chung à
[00:15:29] Ok nói chung à
[00:15:29] Ok nói chung à ạ bây giờ bắt đầu buổi họp ở Nhật
[00:15:32] ạ bây giờ bắt đầu buổi họp ở Nhật
[00:15:32] ạ bây giờ bắt đầu buổi họp ở Nhật từ hôm nay thì ở mình đầu tiên mình trả
[00:15:37] từ hôm nay thì ở mình đầu tiên mình trả
[00:15:37] từ hôm nay thì ở mình đầu tiên mình trả lời câu hỏi này nhé
[00:15:38] lời câu hỏi này nhé
[00:15:39] lời câu hỏi này nhé Đây thì có hai bạn hỏi thỉnh thoảng mình
[00:15:43] Đây thì có hai bạn hỏi thỉnh thoảng mình
[00:15:43] Đây thì có hai bạn hỏi thỉnh thoảng mình thấy rất nhiều Bạn thử hỏi cái này mà
[00:15:46] thấy rất nhiều Bạn thử hỏi cái này mà
[00:15:46] thấy rất nhiều Bạn thử hỏi cái này mà mình nhắc lại lần chờ đây nhắc lại lần
[00:15:48] mình nhắc lại lần chờ đây nhắc lại lần
[00:15:48] mình nhắc lại lần chờ đây nhắc lại lần cuối đi à
[00:15:50] cuối đi à
[00:15:50] cuối đi à ở đó là mình sẽ không không quan tâm về
[00:15:54] ở đó là mình sẽ không không quan tâm về
[00:15:54] ở đó là mình sẽ không không quan tâm về cái ngôn ngữ Lập trình là gì lắm giống
[00:15:57] cái ngôn ngữ Lập trình là gì lắm giống
[00:15:57] cái ngôn ngữ Lập trình là gì lắm giống như bạn kể này hỏi về java này rồi dẫn
[00:15:59] như bạn kể này hỏi về java này rồi dẫn
[00:15:59] như bạn kể này hỏi về java này rồi dẫn chị Ruby VP này Mẹ từng nói rồi mình
[00:16:02] chị Ruby VP này Mẹ từng nói rồi mình
[00:16:02] chị Ruby VP này Mẹ từng nói rồi mình không quan trọng với ngôn ngữ lập trình
[00:16:03] không quan trọng với ngôn ngữ lập trình
[00:16:03] không quan trọng với ngôn ngữ lập trình lắm đương nhiên là bây giờ mình đang
[00:16:05] lắm đương nhiên là bây giờ mình đang
[00:16:05] lắm đương nhiên là bây giờ mình đang chuyên về TP thì mình sẽ dạy các bạn
[00:16:08] chuyên về TP thì mình sẽ dạy các bạn
[00:16:08] chuyên về TP thì mình sẽ dạy các bạn được pê đúng ạ Các bạn học các bạn thấy
[00:16:13] được pê đúng ạ Các bạn học các bạn thấy
[00:16:13] được pê đúng ạ Các bạn học các bạn thấy nó dễ học thì các bạn học thôi ông ạ và
[00:16:17] nó dễ học thì các bạn học thôi ông ạ và
[00:16:17] nó dễ học thì các bạn học thôi ông ạ và về sau các bạn mới nhảy sang cái khác
[00:16:18] về sau các bạn mới nhảy sang cái khác
[00:16:18] về sau các bạn mới nhảy sang cái khác thì vẫn được nhưng mình nói rồi nó vẫn
[00:16:22] thì vẫn được nhưng mình nói rồi nó vẫn
[00:16:22] thì vẫn được nhưng mình nói rồi nó vẫn dễ Ngày Nên là các bạn không Không phải
[00:16:25] dễ Ngày Nên là các bạn không Không phải
[00:16:25] dễ Ngày Nên là các bạn không Không phải kiểu
[00:16:27] kiểu
[00:16:27] kiểu thấy ở đây không dậy Lara không họp nữa
[00:16:29] thấy ở đây không dậy Lara không họp nữa
[00:16:29] thấy ở đây không dậy Lara không họp nữa tìm nơi Họ dạy ra đi học không Không cần
[00:16:33] tìm nơi Họ dạy ra đi học không Không cần
[00:16:33] tìm nơi Họ dạy ra đi học không Không cần phải như thế
[00:16:35] phải như thế
[00:16:35] phải như thế Ừ ok
[00:16:40] a tiếp theo là
[00:16:40] a tiếp theo là từ hôm nay mình sẽ dạy các bạn về vòng
[00:16:43] từ hôm nay mình sẽ dạy các bạn về vòng
[00:16:43] từ hôm nay mình sẽ dạy các bạn về vòng lặp không ạ
[00:16:45] lặp không ạ
[00:16:45] lặp không ạ bằng Nạp và tương tác với cái input đầu
[00:16:49] bằng Nạp và tương tác với cái input đầu
[00:16:49] bằng Nạp và tương tác với cái input đầu tiên vòng lặp lại cái gì đây mình sẽ mở
[00:16:54] tiên vòng lặp lại cái gì đây mình sẽ mở
[00:16:54] tiên vòng lặp lại cái gì đây mình sẽ mở em xóa hết kodi vậy ạ
[00:16:59] em xóa hết kodi vậy ạ
[00:16:59] em xóa hết kodi vậy ạ ừ ừ
[00:17:17] à à
[00:17:17] à à à à ừ ừ
[00:17:30] ở đầu tiên là về phòng học thì các bạn
[00:17:30] ở đầu tiên là về phòng học thì các bạn hôm trước các bạn biết về cái vụ shipper
[00:17:33] hôm trước các bạn biết về cái vụ shipper
[00:17:33] hôm trước các bạn biết về cái vụ shipper rồi đúng ạ Các bạn biết được vụ Kiều Nếu
[00:17:37] rồi đúng ạ Các bạn biết được vụ Kiều Nếu
[00:17:37] rồi đúng ạ Các bạn biết được vụ Kiều Nếu đúng thì làm gì và không thì làm gì rồi
[00:17:40] đúng thì làm gì và không thì làm gì rồi
[00:17:40] đúng thì làm gì và không thì làm gì rồi đúng ạ Nếu mà còn về có mặc thì như mình
[00:17:45] đúng ạ Nếu mà còn về có mặc thì như mình
[00:17:45] đúng ạ Nếu mà còn về có mặc thì như mình đã nói cái cái thế nào lập trình nó nó
[00:17:50] đã nói cái cái thế nào lập trình nó nó
[00:17:50] đã nói cái cái thế nào lập trình nó nó nó nó là liên quan đến về cái điều kiện
[00:17:53] nó nó là liên quan đến về cái điều kiện
[00:17:53] nó nó là liên quan đến về cái điều kiện tiếp theo
[00:17:55] tiếp theo
[00:17:55] tiếp theo và thứ hai nó là vòng lập lúc
[00:17:59] và thứ hai nó là vòng lập lúc
[00:17:59] và thứ hai nó là vòng lập lúc thì mình mình sẽ hiểu cái bản chất cái
[00:18:04] thì mình mình sẽ hiểu cái bản chất cái
[00:18:04] thì mình mình sẽ hiểu cái bản chất cái nút này thì ra nó ra ít theo thôi là nếu
[00:18:08] nút này thì ra nó ra ít theo thôi là nếu
[00:18:08] nút này thì ra nó ra ít theo thôi là nếu đúng thì tiếp tục chạy còn nếu sai sẽ
[00:18:11] đúng thì tiếp tục chạy còn nếu sai sẽ
[00:18:11] đúng thì tiếp tục chạy còn nếu sai sẽ dừng lại đấy nó là như thế
[00:18:14] dừng lại đấy nó là như thế
[00:18:14] dừng lại đấy nó là như thế máy tính ấy thì nó sẽ hiểu Ừ nếu các bạn
[00:18:18] máy tính ấy thì nó sẽ hiểu Ừ nếu các bạn
[00:18:18] máy tính ấy thì nó sẽ hiểu Ừ nếu các bạn nghe qua là phụ máy tính là nó sẽ hiểu
[00:18:20] nghe qua là phụ máy tính là nó sẽ hiểu
[00:18:20] nghe qua là phụ máy tính là nó sẽ hiểu mã nhị phân Thôi đóng ngoặc là một phải
[00:18:22] mã nhị phân Thôi đóng ngoặc là một phải
[00:18:22] mã nhị phân Thôi đóng ngoặc là một phải không Tức là một thì nó sẽ nở đúng nó sẽ
[00:18:26] không Tức là một thì nó sẽ nở đúng nó sẽ
[00:18:26] không Tức là một thì nó sẽ nở đúng nó sẽ chạy còn không này nó sẽ nó sẽ ra Cậu
[00:18:30] chạy còn không này nó sẽ nó sẽ ra Cậu
[00:18:30] chạy còn không này nó sẽ nó sẽ ra Cậu sai và nó sẽ ngừng kiểu thế Còn vòng lặp
[00:18:33] sai và nó sẽ ngừng kiểu thế Còn vòng lặp
[00:18:33] sai và nó sẽ ngừng kiểu thế Còn vòng lặp là việc và lập Y hợp lại để kiểm tra
[00:18:35] là việc và lập Y hợp lại để kiểm tra
[00:18:35] là việc và lập Y hợp lại để kiểm tra việc đúng hay sai để mà tiếp tục chặng 2
[00:18:38] việc đúng hay sai để mà tiếp tục chặng 2
[00:18:38] việc đúng hay sai để mà tiếp tục chặng 2 là nó dừng đây thì
[00:18:40] là nó dừng đây thì
[00:18:40] là nó dừng đây thì cái vòng lặp cơ bản nhất mà các bạn
[00:18:43] cái vòng lặp cơ bản nhất mà các bạn
[00:18:43] cái vòng lặp cơ bản nhất mà các bạn thường ấy biết nó vòng For đúng không ạ
[00:18:46] thường ấy biết nó vòng For đúng không ạ
[00:18:46] thường ấy biết nó vòng For đúng không ạ bí mật ngọt pho thì nó sẽ có à Mình thấy
[00:18:51] bí mật ngọt pho thì nó sẽ có à Mình thấy
[00:18:51] bí mật ngọt pho thì nó sẽ có à Mình thấy nó có bốn điều thức như sau
[00:18:54] nó có bốn điều thức như sau
[00:18:54] nó có bốn điều thức như sau Em đang coi phim mình ghi luôn trong lại
[00:18:57] Em đang coi phim mình ghi luôn trong lại
[00:18:57] Em đang coi phim mình ghi luôn trong lại được
[00:18:57] được
[00:18:57] được for này
[00:19:00] for này
[00:19:00] for này ở
[00:19:01] ở
[00:19:01] ở đầu tiên là cho thường hay sai bảo y này
[00:19:04] đầu tiên là cho thường hay sai bảo y này
[00:19:04] đầu tiên là cho thường hay sai bảo y này Y cho Y = 1 chứng nặng y nhỏ hơn 10 ạ và
[00:19:11] Y cho Y = 1 chứng nặng y nhỏ hơn 10 ạ và
[00:19:11] Y cho Y = 1 chứng nặng y nhỏ hơn 10 ạ và y + + như này à A và đây sẽ
[00:19:16] y + + như này à A và đây sẽ
[00:19:16] y + + như này à A và đây sẽ mình sẽ đó comment chấm ra Im để im đi à
[00:19:22] mình sẽ đó comment chấm ra Im để im đi à
[00:19:22] mình sẽ đó comment chấm ra Im để im đi à ăn thịt đây đây đề cách viết của một
[00:19:25] ăn thịt đây đây đề cách viết của một
[00:19:25] ăn thịt đây đây đề cách viết của một vòng lặp for
[00:19:26] vòng lặp for
[00:19:26] vòng lặp for em có bạn nhìn rõ rồi em ạ
[00:19:30] em có bạn nhìn rõ rồi em ạ
[00:19:30] em có bạn nhìn rõ rồi em ạ thì kể cách viết này nó sẽ như sau các
[00:19:34] thì kể cách viết này nó sẽ như sau các
[00:19:34] thì kể cách viết này nó sẽ như sau các bạn sẽ thấy ở cái biểu thức một này
[00:19:37] bạn sẽ thấy ở cái biểu thức một này
[00:19:37] bạn sẽ thấy ở cái biểu thức một này thì nó sẽ ra khai báo thường ai xa để
[00:19:40] thì nó sẽ ra khai báo thường ai xa để
[00:19:40] thì nó sẽ ra khai báo thường ai xa để khai báo giá trị ban đầu thường ai thế
[00:19:44] khai báo giá trị ban đầu thường ai thế
[00:19:44] khai báo giá trị ban đầu thường ai thế biểu thức 2 ở biển thực so sánh mình sẽ
[00:19:47] biểu thức 2 ở biển thực so sánh mình sẽ
[00:19:47] biểu thức 2 ở biển thực so sánh mình sẽ So sánh có cái biểu thức này thì biểu
[00:19:50] So sánh có cái biểu thức này thì biểu
[00:19:50] So sánh có cái biểu thức này thì biểu thức điều kiện nếu mà cái biểu thức này
[00:19:54] thức điều kiện nếu mà cái biểu thức này
[00:19:54] thức điều kiện nếu mà cái biểu thức này đúng thì vòng lọc sẽ tiếp tục chạy cầm
[00:19:57] đúng thì vòng lọc sẽ tiếp tục chạy cầm
[00:19:57] đúng thì vòng lọc sẽ tiếp tục chạy cầm đều thức này sai thì phòng họp sẽ ngừng
[00:19:59] đều thức này sai thì phòng họp sẽ ngừng
[00:19:59] đều thức này sai thì phòng họp sẽ ngừng a tiếp theo là biểu thức kiểu
[00:20:03] a tiếp theo là biểu thức kiểu
[00:20:03] a tiếp theo là biểu thức kiểu tăng cái biểu thức này các bạn đang nhìn
[00:20:06] tăng cái biểu thức này các bạn đang nhìn
[00:20:06] tăng cái biểu thức này các bạn đang nhìn thấy là nó là y + + tức là y = y + 1 đấy
[00:20:10] thấy là nó là y + + tức là y = y + 1 đấy
[00:20:10] thấy là nó là y + + tức là y = y + 1 đấy ạ
[00:20:11] ạ
[00:20:11] ạ là biểu biểu thức khiến thường là cái
[00:20:15] là biểu biểu thức khiến thường là cái
[00:20:15] là biểu biểu thức khiến thường là cái đội thước để khiến cho cái cái vòng lặp
[00:20:19] đội thước để khiến cho cái cái vòng lặp
[00:20:19] đội thước để khiến cho cái cái vòng lặp nó sẽ bị ngừng để ông ạ là phá vỡ vòng
[00:20:22] nó sẽ bị ngừng để ông ạ là phá vỡ vòng
[00:20:22] nó sẽ bị ngừng để ông ạ là phá vỡ vòng lặp
[00:20:23] lặp
[00:20:23] lặp khiến cho cái này sai đã sử đang một
[00:20:26] khiến cho cái này sai đã sử đang một
[00:20:26] khiến cho cái này sai đã sử đang một đống ngoại cứ tăng dần dần dần dần lên
[00:20:29] đống ngoại cứ tăng dần dần dần dần lên
[00:20:29] đống ngoại cứ tăng dần dần dần dần lên để cho nó nhận nó lớn hơn hoặc bằng 10
[00:20:33] để cho nó nhận nó lớn hơn hoặc bằng 10
[00:20:33] để cho nó nhận nó lớn hơn hoặc bằng 10 chẳng hạn thì nó sẽ dừng vòng lặp và
[00:20:36] chẳng hạn thì nó sẽ dừng vòng lặp và
[00:20:36] chẳng hạn thì nó sẽ dừng vòng lặp và biểu thức này là biểu thức để mà chạy
[00:20:39] biểu thức này là biểu thức để mà chạy
[00:20:39] biểu thức này là biểu thức để mà chạy khi mà vòng lặp đang chạy
[00:20:41] khi mà vòng lặp đang chạy
[00:20:41] khi mà vòng lặp đang chạy Ừ đúng ạ nghĩa cái này các bạn thấy là
[00:20:44] Ừ đúng ạ nghĩa cái này các bạn thấy là
[00:20:44] Ừ đúng ạ nghĩa cái này các bạn thấy là con pho nó sẽ gồm 44 điều thức như thế
[00:20:46] con pho nó sẽ gồm 44 điều thức như thế
[00:20:46] con pho nó sẽ gồm 44 điều thức như thế này à
[00:20:48] này à
[00:20:48] này à ờ thì ờ đây 1 để 2 đề 3 đề 4 này đề thi
[00:20:57] ờ thì ờ đây 1 để 2 đề 3 đề 4 này đề thi
[00:20:57] ờ thì ờ đây 1 để 2 đề 3 đề 4 này đề thi sắc cái cái thứ tự của cái việc chạy của
[00:21:00] sắc cái cái thứ tự của cái việc chạy của
[00:21:00] sắc cái cái thứ tự của cái việc chạy của vòng lọc này đấy
[00:21:07] thì các bạn nhớ cái thứ tự chạy của vòng
[00:21:07] thì các bạn nhớ cái thứ tự chạy của vòng lặp này thì nó sẽ từ số mấy thứ mấy ông
[00:21:10] lặp này thì nó sẽ từ số mấy thứ mấy ông
[00:21:10] lặp này thì nó sẽ từ số mấy thứ mấy ông ạ
[00:21:12] ạ
[00:21:13] Ừ
[00:21:13] Ừ mình cư
[00:21:21] à à
[00:21:21] à à à à
[00:21:27] à à
[00:21:27] à à đi tìm một đầy đúng ạ
[00:21:31] đi tìm một đầy đúng ạ
[00:21:31] đi tìm một đầy đúng ạ à à
[00:21:34] à à
[00:21:34] à à à à
[00:21:44] có một mạch mà mình đi thẳng đây đi
[00:21:44] có một mạch mà mình đi thẳng đây đi à à
[00:21:47] à à
[00:21:47] à à ở một lễ 2
[00:21:50] ở một lễ 2
[00:21:50] ở một lễ 2 E3 này và đây là 4 cả đoạn này 40 ạ thì
[00:21:56] E3 này và đây là 4 cả đoạn này 40 ạ thì
[00:21:56] E3 này và đây là 4 cả đoạn này 40 ạ thì 1234 thì theo các bạn thì nó sẽ chạy
[00:21:59] 1234 thì theo các bạn thì nó sẽ chạy
[00:21:59] 1234 thì theo các bạn thì nó sẽ chạy theo thứ tự như thế nào
[00:22:02] theo thứ tự như thế nào
[00:22:02] theo thứ tự như thế nào anh không nó chạy theo thứ tự biểu thức
[00:22:05] anh không nó chạy theo thứ tự biểu thức
[00:22:05] anh không nó chạy theo thứ tự biểu thức như nào Chứ không phải nó sẽ in ra như
[00:22:06] như nào Chứ không phải nó sẽ in ra như
[00:22:06] như nào Chứ không phải nó sẽ in ra như thế nào in ra như nào người ông đấy biết
[00:22:09] thế nào in ra như nào người ông đấy biết
[00:22:09] thế nào in ra như nào người ông đấy biết hết rồi
[00:22:15] anh nói bạn kia trả lời đúng luôn rồi
[00:22:15] anh nói bạn kia trả lời đúng luôn rồi kìa 1243 ông ạ
[00:22:18] kìa 1243 ông ạ
[00:22:18] kìa 1243 ông ạ A gọi tôi tôi đang hỏi dạng lại các bạn
[00:22:22] A gọi tôi tôi đang hỏi dạng lại các bạn
[00:22:22] A gọi tôi tôi đang hỏi dạng lại các bạn thôi vì nhiều bạn mới học thì các bạn sẽ
[00:22:25] thôi vì nhiều bạn mới học thì các bạn sẽ
[00:22:25] thôi vì nhiều bạn mới học thì các bạn sẽ bị nhầm sang 1234
[00:22:27] bị nhầm sang 1234
[00:22:27] bị nhầm sang 1234 đúng mạn trên là đúng nghĩa là nó sẽ
[00:22:30] đúng mạn trên là đúng nghĩa là nó sẽ
[00:22:30] đúng mạn trên là đúng nghĩa là nó sẽ chạy cái đầu tiên này nó luôn chạy cái
[00:22:32] chạy cái đầu tiên này nó luôn chạy cái
[00:22:32] chạy cái đầu tiên này nó luôn chạy cái và và chính xác chính xác Đấy là các bạn
[00:22:37] và và chính xác chính xác Đấy là các bạn
[00:22:37] và và chính xác chính xác Đấy là các bạn nói 1243 cũng đúng rồi nhưng mà chưa đủ
[00:22:41] nói 1243 cũng đúng rồi nhưng mà chưa đủ
[00:22:41] nói 1243 cũng đúng rồi nhưng mà chưa đủ Tại sao
[00:22:43] Tại sao
[00:22:43] Tại sao ờ ờ đây
[00:22:46] ờ ờ đây
[00:22:46] ờ ờ đây Ừ cái này chạy đầu tiên đúng không ạ Có
[00:22:48] Ừ cái này chạy đầu tiên đúng không ạ Có
[00:22:49] Ừ cái này chạy đầu tiên đúng không ạ Có chạy thứ 2 để kiểm tra đúng không ạ
[00:22:52] chạy thứ 2 để kiểm tra đúng không ạ
[00:22:52] chạy thứ 2 để kiểm tra đúng không ạ Ừ nếu mà cái này cái thứ hai là đúng cái
[00:22:56] Ừ nếu mà cái này cái thứ hai là đúng cái
[00:22:56] Ừ nếu mà cái này cái thứ hai là đúng cái thứ hai này đúng nhá thì nó chạy đến cái
[00:22:58] thứ hai này đúng nhá thì nó chạy đến cái
[00:22:58] thứ hai này đúng nhá thì nó chạy đến cái thứ tư đúng hoặc nó chạy đến cái thứ Tư
[00:23:01] thứ tư đúng hoặc nó chạy đến cái thứ Tư
[00:23:01] thứ tư đúng hoặc nó chạy đến cái thứ Tư này đúng ạ nó không chạy này cái thứ ba
[00:23:03] này đúng ạ nó không chạy này cái thứ ba
[00:23:03] này đúng ạ nó không chạy này cái thứ ba đó nó chạy cái thứ Tư này
[00:23:05] đó nó chạy cái thứ Tư này
[00:23:05] đó nó chạy cái thứ Tư này khi mà chạy hết toàn bộ Cái thứ tư rồi
[00:23:08] khi mà chạy hết toàn bộ Cái thứ tư rồi
[00:23:08] khi mà chạy hết toàn bộ Cái thứ tư rồi Nó quay lại thứ ba đúng không ạ để mà để
[00:23:12] Nó quay lại thứ ba đúng không ạ để mà để
[00:23:12] Nó quay lại thứ ba đúng không ạ để mà để mà tăng giá trị hay làm gì đó nó họ để
[00:23:14] mà tăng giá trị hay làm gì đó nó họ để
[00:23:14] mà tăng giá trị hay làm gì đó nó họ để phá vỡ vòng lặp sau đó thì nó lại quay
[00:23:17] phá vỡ vòng lặp sau đó thì nó lại quay
[00:23:17] phá vỡ vòng lặp sau đó thì nó lại quay lại cái thứ hai đúng ạ Quay lại cái thứ
[00:23:20] lại cái thứ hai đúng ạ Quay lại cái thứ
[00:23:20] lại cái thứ hai đúng ạ Quay lại cái thứ 2 là nó kiểm tra xem cái lần này điều
[00:23:23] 2 là nó kiểm tra xem cái lần này điều
[00:23:23] 2 là nó kiểm tra xem cái lần này điều kiện còn đúng hay không Nếu vẫn còn đúng
[00:23:25] kiện còn đúng hay không Nếu vẫn còn đúng
[00:23:25] kiện còn đúng hay không Nếu vẫn còn đúng thì nó lại chạy tiếp thì Thứ Tư đúng ạ
[00:23:28] thì nó lại chạy tiếp thì Thứ Tư đúng ạ
[00:23:28] thì nó lại chạy tiếp thì Thứ Tư đúng ạ Còn nếu sai thì nó dừng không ạ con Nếu
[00:23:32] Còn nếu sai thì nó dừng không ạ con Nếu
[00:23:32] Còn nếu sai thì nó dừng không ạ con Nếu nó vẫn đúng thì nó chạy cái thứ tư so
[00:23:35] nó vẫn đúng thì nó chạy cái thứ tư so
[00:23:35] nó vẫn đúng thì nó chạy cái thứ tư so với lại quay lại thứ ba sao lại quay thứ
[00:23:37] với lại quay lại thứ ba sao lại quay thứ
[00:23:37] với lại quay lại thứ ba sao lại quay thứ hai nó sẽ không quay lại thể thứ nhất
[00:23:40] hai nó sẽ không quay lại thể thứ nhất
[00:23:40] hai nó sẽ không quay lại thể thứ nhất một lần nào nữa để ông ạ A và thuận chí
[00:23:44] một lần nào nữa để ông ạ A và thuận chí
[00:23:44] một lần nào nữa để ông ạ A và thuận chí Nếu giả sử ngay từ lúc đầu cài đầu tiên
[00:23:48] Nếu giả sử ngay từ lúc đầu cài đầu tiên
[00:23:48] Nếu giả sử ngay từ lúc đầu cài đầu tiên cái thứ nhất chạy này không ạ Cái thứ
[00:23:50] cái thứ nhất chạy này không ạ Cái thứ
[00:23:50] cái thứ nhất chạy này không ạ Cái thứ hai chạy mà nó đã sai ngay từ đầu rồi
[00:23:52] hai chạy mà nó đã sai ngay từ đầu rồi
[00:23:52] hai chạy mà nó đã sai ngay từ đầu rồi đúng không ạ
[00:23:53] đúng không ạ
[00:23:53] đúng không ạ thì nó sẽ không chạy đến cái thứ tư và
[00:23:55] thì nó sẽ không chạy đến cái thứ tư và
[00:23:55] thì nó sẽ không chạy đến cái thứ tư và thứ 3 luôn đúng ạ Đây mình sẽ thử ví dụ
[00:23:59] thứ 3 luôn đúng ạ Đây mình sẽ thử ví dụ
[00:23:59] thứ 3 luôn đúng ạ Đây mình sẽ thử ví dụ Các bạn xem được bạn sẽ hiểu với ví dụ
[00:24:02] Các bạn xem được bạn sẽ hiểu với ví dụ
[00:24:02] Các bạn xem được bạn sẽ hiểu với ví dụ này thì mình in ra thì cứ làm các bạn
[00:24:03] này thì mình in ra thì cứ làm các bạn
[00:24:03] này thì mình in ra thì cứ làm các bạn thấy từ 1 đến 9 đúng rồi đúng ạ nhưng
[00:24:06] thấy từ 1 đến 9 đúng rồi đúng ạ nhưng
[00:24:06] thấy từ 1 đến 9 đúng rồi đúng ạ nhưng bây giờ giả sử mình cho một cái số ngay
[00:24:09] bây giờ giả sử mình cho một cái số ngay
[00:24:09] bây giờ giả sử mình cho một cái số ngay từ đầu đó là một trăm nữa Ngạn thì rõ ra
[00:24:12] từ đầu đó là một trăm nữa Ngạn thì rõ ra
[00:24:12] từ đầu đó là một trăm nữa Ngạn thì rõ ra điều kiện nó sai đúng không ạ bị đi nó
[00:24:14] điều kiện nó sai đúng không ạ bị đi nó
[00:24:14] điều kiện nó sai đúng không ạ bị đi nó ra này các bạn thấy nó chẳng in ra cái
[00:24:17] ra này các bạn thấy nó chẳng in ra cái
[00:24:17] ra này các bạn thấy nó chẳng in ra cái gì cả bởi việc nó có chạy được vòng lặp
[00:24:20] gì cả bởi việc nó có chạy được vòng lặp
[00:24:20] gì cả bởi việc nó có chạy được vòng lặp đâu ạ nó không chạy đến cái đó commons
[00:24:22] đâu ạ nó không chạy đến cái đó commons
[00:24:22] đâu ạ nó không chạy đến cái đó commons ai này không ạ ra xử mì cho đó cùng mình
[00:24:25] ai này không ạ ra xử mì cho đó cùng mình
[00:24:25] ai này không ạ ra xử mì cho đó cùng mình dai ở ngoài như thế này thì các bạn sẽ
[00:24:27] dai ở ngoài như thế này thì các bạn sẽ
[00:24:27] dai ở ngoài như thế này thì các bạn sẽ thấy lúc đầu khai báo y = 100 này sôi
[00:24:31] thấy lúc đầu khai báo y = 100 này sôi
[00:24:31] thấy lúc đầu khai báo y = 100 này sôi ndai ở ngoài đó thì các bạn thấy nó sẽ
[00:24:34] ndai ở ngoài đó thì các bạn thấy nó sẽ
[00:24:34] ndai ở ngoài đó thì các bạn thấy nó sẽ in ra y ở ngay ngoài luôn đúng không ạ
[00:24:36] in ra y ở ngay ngoài luôn đúng không ạ
[00:24:36] in ra y ở ngay ngoài luôn đúng không ạ nghĩa là nó i5 100 thôi không ạ Nó không
[00:24:40] nghĩa là nó i5 100 thôi không ạ Nó không
[00:24:40] nghĩa là nó i5 100 thôi không ạ Nó không phải là 101 nó không chạy vào đây 5 101
[00:24:43] phải là 101 nó không chạy vào đây 5 101
[00:24:43] phải là 101 nó không chạy vào đây 5 101 đúng
[00:24:45] đúng
[00:24:45] đúng ạ Bây giờ mình giả sử mình đổi nó thành
[00:24:47] ạ Bây giờ mình giả sử mình đổi nó thành
[00:24:47] ạ Bây giờ mình giả sử mình đổi nó thành từ một đêm như này chẳng hạn thì các bạn
[00:24:51] từ một đêm như này chẳng hạn thì các bạn
[00:24:51] từ một đêm như này chẳng hạn thì các bạn thấy là từ 1 đến 10 không phải từ 1 đến
[00:24:53] thấy là từ 1 đến 10 không phải từ 1 đến
[00:24:53] thấy là từ 1 đến 10 không phải từ 1 đến 9 nữa tuổi việc nó
[00:24:55] 9 nữa tuổi việc nó
[00:24:55] 9 nữa tuổi việc nó ở đoạn này nó làm như nào bạn này thì
[00:24:58] ở đoạn này nó làm như nào bạn này thì
[00:24:58] ở đoạn này nó làm như nào bạn này thì thì chỉ đơn giản là nó in từ 1 đến 9
[00:25:01] thì chỉ đơn giản là nó in từ 1 đến 9
[00:25:01] thì chỉ đơn giản là nó in từ 1 đến 9 bằng vòng lọc
[00:25:03] bằng vòng lọc
[00:25:03] bằng vòng lọc Hà
[00:25:05] Hà
[00:25:05] Hà Nội Yên từ 1 đến 9 bằng màng lọc nóng
[00:25:08] Nội Yên từ 1 đến 9 bằng màng lọc nóng
[00:25:08] Nội Yên từ 1 đến 9 bằng màng lọc nóng lạnh sau đó thì đến khi y = 10 thì nó
[00:25:12] lạnh sau đó thì đến khi y = 10 thì nó
[00:25:12] lạnh sau đó thì đến khi y = 10 thì nó dừng nó không y bằng vòng lọc nữa nhưng
[00:25:15] dừng nó không y bằng vòng lọc nữa nhưng
[00:25:15] dừng nó không y bằng vòng lọc nữa nhưng nó vẫn in ra cái giá trị cuối của y = 10
[00:25:19] nó vẫn in ra cái giá trị cuối của y = 10
[00:25:19] nó vẫn in ra cái giá trị cuối của y = 10 khi lại y tăng lên một ở đây đúng không
[00:25:21] khi lại y tăng lên một ở đây đúng không
[00:25:21] khi lại y tăng lên một ở đây đúng không ạ Tại sao tự nhiên mình phải đề cập với
[00:25:23] ạ Tại sao tự nhiên mình phải đề cập với
[00:25:23] ạ Tại sao tự nhiên mình phải đề cập với cái vụ này ở đây Bởi vì bây giờ mình sẽ
[00:25:26] cái vụ này ở đây Bởi vì bây giờ mình sẽ
[00:25:26] cái vụ này ở đây Bởi vì bây giờ mình sẽ hướng dẫn các bạn qua vì kể
[00:25:30] hướng dẫn các bạn qua vì kể
[00:25:30] hướng dẫn các bạn qua vì kể Vòng nào khác
[00:25:33] Vòng nào khác
[00:25:33] Vòng nào khác Ừ đúng rồi Nãy giờ mình có để các bạn
[00:25:35] Ừ đúng rồi Nãy giờ mình có để các bạn
[00:25:35] Ừ đúng rồi Nãy giờ mình có để các bạn hỏi về việc là
[00:25:37] hỏi về việc là
[00:25:37] hỏi về việc là Ừ lần này anh không thể thay báo kiểu và
[00:25:40] Ừ lần này anh không thể thay báo kiểu và
[00:25:40] Ừ lần này anh không thể thay báo kiểu và 2 led
[00:25:41] 2 led
[00:25:41] 2 led à à
[00:25:52] anh Đợi mình tí Đợi Minh chị có con chó
[00:25:52] anh Đợi mình tí Đợi Minh chị có con chó Anh
[00:25:54] Anh
[00:25:54] Anh Ngọc Anh nó cắn dây điện thoại
[00:25:57] Ngọc Anh nó cắn dây điện thoại
[00:25:57] Ngọc Anh nó cắn dây điện thoại à à
[00:25:59] à à
[00:25:59] à à thế nào
[00:26:14] các bạn ấy để
[00:26:14] các bạn ấy để các bạn đôi khi để những cái kiểu chi
[00:26:17] các bạn đôi khi để những cái kiểu chi
[00:26:17] các bạn đôi khi để những cái kiểu chi tiết nhỏ như thế thì thì các bạn sẽ hiểu
[00:26:21] tiết nhỏ như thế thì thì các bạn sẽ hiểu
[00:26:22] tiết nhỏ như thế thì thì các bạn sẽ hiểu cũng là động não mà đang tập trung động
[00:26:24] cũng là động não mà đang tập trung động
[00:26:24] cũng là động não mà đang tập trung động não có thử và thắc mắc như thế là tốt và
[00:26:27] não có thử và thắc mắc như thế là tốt và
[00:26:27] não có thử và thắc mắc như thế là tốt và các bạn đưa ra câu hỏi nó càng tốt không
[00:26:29] các bạn đưa ra câu hỏi nó càng tốt không
[00:26:29] các bạn đưa ra câu hỏi nó càng tốt không ạ bởi vì cái này là môi trường nên là
[00:26:32] ạ bởi vì cái này là môi trường nên là
[00:26:32] ạ bởi vì cái này là môi trường nên là thoải mái tương tác hai chiều hơn lại bị
[00:26:36] thoải mái tương tác hai chiều hơn lại bị
[00:26:36] thoải mái tương tác hai chiều hơn lại bị động ở trên trường nếu mà các bạn học
[00:26:39] động ở trên trường nếu mà các bạn học
[00:26:39] động ở trên trường nếu mà các bạn học theo kiểu bị động các bạn sẽ không nhớ
[00:26:41] theo kiểu bị động các bạn sẽ không nhớ
[00:26:41] theo kiểu bị động các bạn sẽ không nhớ kiến thức mình học chung lớp mình toàn
[00:26:43] kiến thức mình học chung lớp mình toàn
[00:26:43] kiến thức mình học chung lớp mình toàn tương tác liên tục của thầy cô
[00:26:46] tương tác liên tục của thầy cô
[00:26:46] tương tác liên tục của thầy cô Ê bà cũng tạo động lực cho họ cho thầy
[00:26:49] Ê bà cũng tạo động lực cho họ cho thầy
[00:26:49] Ê bà cũng tạo động lực cho họ cho thầy cô thầy cô cảm thấy có mình nghe và cậu
[00:26:51] cô thầy cô cảm thấy có mình nghe và cậu
[00:26:51] cô thầy cô cảm thấy có mình nghe và cậu có người tương tác nữa thì nó hơn một
[00:26:54] có người tương tác nữa thì nó hơn một
[00:26:54] có người tương tác nữa thì nó hơn một Hoàng Tự kỷ không ạ
[00:26:56] Hoàng Tự kỷ không ạ
[00:26:56] Hoàng Tự kỷ không ạ thì cái vụ mà không khai báo về và Led
[00:27:00] thì cái vụ mà không khai báo về và Led
[00:27:00] thì cái vụ mà không khai báo về và Led ấy Thực ra là đối với ngôn ngữ khác thì
[00:27:03] ấy Thực ra là đối với ngôn ngữ khác thì
[00:27:03] ấy Thực ra là đối với ngôn ngữ khác thì nó sẽ bị lỗi ngay nhưng mà đổ về ngôn
[00:27:06] nó sẽ bị lỗi ngay nhưng mà đổ về ngôn
[00:27:06] nó sẽ bị lỗi ngay nhưng mà đổ về ngôn ngữ này thì các bạn thuế nó cái da Suite
[00:27:09] ngữ này thì các bạn thuế nó cái da Suite
[00:27:09] ngữ này thì các bạn thuế nó cái da Suite mày nó hơi bị lỏng lẻo một tí về cái vụ
[00:27:13] mày nó hơi bị lỏng lẻo một tí về cái vụ
[00:27:13] mày nó hơi bị lỏng lẻo một tí về cái vụ này đó là
[00:27:15] này đó là
[00:27:15] này đó là đó là theo kiểu là đôi khi không cần
[00:27:18] đó là theo kiểu là đôi khi không cần
[00:27:18] đó là theo kiểu là đôi khi không cần khai báo hoạt động chứa khai báo nó là
[00:27:20] khai báo hoạt động chứa khai báo nó là
[00:27:20] khai báo hoạt động chứa khai báo nó là là chuỗi rồi Sao anh ấy nó sáng số thì
[00:27:23] là chuỗi rồi Sao anh ấy nó sáng số thì
[00:27:23] là chuỗi rồi Sao anh ấy nó sáng số thì vẫn được vân vân vân tím mình sẽ đề cập
[00:27:26] vẫn được vân vân vân tím mình sẽ đề cập
[00:27:26] vẫn được vân vân vân tím mình sẽ đề cập các bạn mình lấy vụ đấy ở đây à
[00:27:28] các bạn mình lấy vụ đấy ở đây à
[00:27:28] các bạn mình lấy vụ đấy ở đây à anh nói chung là cái này là hạn chế về
[00:27:32] anh nói chung là cái này là hạn chế về
[00:27:32] anh nói chung là cái này là hạn chế về việc là không khai báo
[00:27:35] việc là không khai báo
[00:27:35] việc là không khai báo em cho dù là không khai báo nó vẫn sẽ
[00:27:37] em cho dù là không khai báo nó vẫn sẽ
[00:27:37] em cho dù là không khai báo nó vẫn sẽ nhận như thế này các bạn thấy nó vẫn sẽ
[00:27:39] nhận như thế này các bạn thấy nó vẫn sẽ
[00:27:39] nhận như thế này các bạn thấy nó vẫn sẽ nhận vẫn sẽ chạy đúng không ạ Không ạ
[00:27:41] nhận vẫn sẽ chạy đúng không ạ Không ạ
[00:27:41] nhận vẫn sẽ chạy đúng không ạ Không ạ con vụ bây giờ mình sẽ khai báo nó thời
[00:27:45] con vụ bây giờ mình sẽ khai báo nó thời
[00:27:45] con vụ bây giờ mình sẽ khai báo nó thời gian nó vẫn sẽ không khác gì cả các bạn
[00:27:47] gian nó vẫn sẽ không khác gì cả các bạn
[00:27:47] gian nó vẫn sẽ không khác gì cả các bạn thấy kết quả là chả khác gì cả đầu nhọn
[00:27:49] thấy kết quả là chả khác gì cả đầu nhọn
[00:27:49] thấy kết quả là chả khác gì cả đầu nhọn như là mình khuyên các bạn là lần sau
[00:27:52] như là mình khuyên các bạn là lần sau
[00:27:52] như là mình khuyên các bạn là lần sau mình phải khai báo có dư thứ
[00:27:55] mình phải khai báo có dư thứ
[00:27:55] mình phải khai báo có dư thứ ừ ừ
[00:27:57] ừ ừ
[00:27:57] ừ ừ thì
[00:27:58] thì
[00:27:58] thì tại sao khai báo trong Ford ngoài vòng
[00:28:02] tại sao khai báo trong Ford ngoài vòng
[00:28:02] tại sao khai báo trong Ford ngoài vòng For mà vẫn dùng được nhỉ Bạn kia hỏi một
[00:28:05] For mà vẫn dùng được nhỉ Bạn kia hỏi một
[00:28:05] For mà vẫn dùng được nhỉ Bạn kia hỏi một cái câu cũng rất ở được theo kiểu là bởi
[00:28:09] cái câu cũng rất ở được theo kiểu là bởi
[00:28:09] cái câu cũng rất ở được theo kiểu là bởi vì nếu với ngôn ngữ lập trình khác thì
[00:28:12] vì nếu với ngôn ngữ lập trình khác thì
[00:28:12] vì nếu với ngôn ngữ lập trình khác thì các bạn sẽ thấy là nó sẽ báo lỗi cái này
[00:28:16] các bạn sẽ thấy là nó sẽ báo lỗi cái này
[00:28:16] các bạn sẽ thấy là nó sẽ báo lỗi cái này thì
[00:28:18] thì
[00:28:18] thì các bạn tra tìm hiểu về Global và local
[00:28:24] các bạn tra tìm hiểu về Global và local
[00:28:24] các bạn tra tìm hiểu về Global và local variable thì các bạn sẽ đọc và anh hiểu
[00:28:28] variable thì các bạn sẽ đọc và anh hiểu
[00:28:28] variable thì các bạn sẽ đọc và anh hiểu về cái việc mà
[00:28:30] về cái việc mà
[00:28:30] về cái việc mà anh với ngôn ngữ lập trình một vài ngôn
[00:28:33] anh với ngôn ngữ lập trình một vài ngôn
[00:28:33] anh với ngôn ngữ lập trình một vài ngôn ngữ lập trình Thì cái này nó nó kiểu
[00:28:37] ngữ lập trình Thì cái này nó nó kiểu
[00:28:37] ngữ lập trình Thì cái này nó nó kiểu dạng Mà mông lung lắm giống như là ra
[00:28:38] dạng Mà mông lung lắm giống như là ra
[00:28:38] dạng Mà mông lung lắm giống như là ra Speed thì rõ ràng à lô bồ khai báo kiểu
[00:28:43] Speed thì rõ ràng à lô bồ khai báo kiểu
[00:28:43] Speed thì rõ ràng à lô bồ khai báo kiểu như này nó vẫn tính ở Global chẳng ạ ạ
[00:28:53] Ừ ok Nói chung mà bây bây giờ mình sẽ
[00:28:53] Ừ ok Nói chung mà bây bây giờ mình sẽ anh giải thích thêm một tí kỹ về kiểu
[00:28:56] anh giải thích thêm một tí kỹ về kiểu
[00:28:56] anh giải thích thêm một tí kỹ về kiểu bông hoa for này cho các bạn không hiểu
[00:28:58] bông hoa for này cho các bạn không hiểu
[00:28:58] bông hoa for này cho các bạn không hiểu này Đầu tiên thì như mình đã nói Phòng
[00:29:01] này Đầu tiên thì như mình đã nói Phòng
[00:29:01] này Đầu tiên thì như mình đã nói Phòng gặp này nó có bạn 4 điều thức đúng ạ và
[00:29:04] gặp này nó có bạn 4 điều thức đúng ạ và
[00:29:04] gặp này nó có bạn 4 điều thức đúng ạ và nó cách nhau bởi dấu chấm phẩy như thế
[00:29:06] nó cách nhau bởi dấu chấm phẩy như thế
[00:29:06] nó cách nhau bởi dấu chấm phẩy như thế này đúng không ạ
[00:29:07] này đúng không ạ
[00:29:07] này đúng không ạ Và thậm chí nếu các bạn
[00:29:10] Và thậm chí nếu các bạn
[00:29:10] Và thậm chí nếu các bạn Ừ nếu các bạn không Không biết thì thậm
[00:29:14] Ừ nếu các bạn không Không biết thì thậm
[00:29:14] Ừ nếu các bạn không Không biết thì thậm chí là mấy cái này nó có thể để chống
[00:29:16] chí là mấy cái này nó có thể để chống
[00:29:16] chí là mấy cái này nó có thể để chống Miễn sao là có để chấm phẩy đây là được
[00:29:18] Miễn sao là có để chấm phẩy đây là được
[00:29:18] Miễn sao là có để chấm phẩy đây là được ra xử ra sự là mình sẽ xóa Dạo này đi
[00:29:22] ra xử ra sự là mình sẽ xóa Dạo này đi
[00:29:22] ra xử ra sự là mình sẽ xóa Dạo này đi mình đẩy nó sang đây này bởi vì rõ ràng
[00:29:24] mình đẩy nó sang đây này bởi vì rõ ràng
[00:29:24] mình đẩy nó sang đây này bởi vì rõ ràng là các bạn nhớ là rõ ràng là cái này thỏ
[00:29:27] là các bạn nhớ là rõ ràng là cái này thỏ
[00:29:27] là các bạn nhớ là rõ ràng là cái này thỏ chạy một lần không ạ thì mình để nó ở
[00:29:29] chạy một lần không ạ thì mình để nó ở
[00:29:29] chạy một lần không ạ thì mình để nó ở ngoài được mà cần gì phải để nó vào
[00:29:32] ngoài được mà cần gì phải để nó vào
[00:29:32] ngoài được mà cần gì phải để nó vào trong này đúng không ạ mình để nó ra
[00:29:33] trong này đúng không ạ mình để nó ra
[00:29:33] trong này đúng không ạ mình để nó ra ngoài Các bạn thấy nó vẫn Kết quả nó vẫn
[00:29:36] ngoài Các bạn thấy nó vẫn Kết quả nó vẫn
[00:29:36] ngoài Các bạn thấy nó vẫn Kết quả nó vẫn thế chả gì thay đổi cả đúng ạ nghĩ em
[00:29:39] thế chả gì thay đổi cả đúng ạ nghĩ em
[00:29:39] thế chả gì thay đổi cả đúng ạ nghĩ em chỉ là
[00:29:40] chỉ là
[00:29:40] chỉ là ở cái đoạn này để chồng Thậm chí các
[00:29:43] ở cái đoạn này để chồng Thậm chí các
[00:29:43] ở cái đoạn này để chồng Thậm chí các đoạn này để chống được thế lắm chị ạ tất
[00:29:46] đoạn này để chống được thế lắm chị ạ tất
[00:29:46] đoạn này để chống được thế lắm chị ạ tất cả những cái này để chống Giả sử cái này
[00:29:48] cả những cái này để chống Giả sử cái này
[00:29:48] cả những cái này để chống Giả sử cái này mình cũng cho nó xuống đây
[00:29:51] mình cũng cho nó xuống đây
[00:29:51] mình cũng cho nó xuống đây Ừ cũng được các bạn sẽ thấy da
[00:29:55] Ừ cũng được các bạn sẽ thấy da
[00:29:55] Ừ cũng được các bạn sẽ thấy da em có có phải là có phải là kiểu Hết
[00:29:59] em có có phải là có phải là kiểu Hết
[00:29:59] em có có phải là có phải là kiểu Hết vòng lặp xong mình chạy cái khi
[00:30:02] vòng lặp xong mình chạy cái khi
[00:30:02] vòng lặp xong mình chạy cái khi nói chung là cái để phá vỡ vọng lập thì
[00:30:05] nói chung là cái để phá vỡ vọng lập thì
[00:30:05] nói chung là cái để phá vỡ vọng lập thì mình để nó ở cuối có sao đâu đúng ạ Đấy
[00:30:09] mình để nó ở cuối có sao đâu đúng ạ Đấy
[00:30:09] mình để nó ở cuối có sao đâu đúng ạ Đấy mình chạy qua nó vẫn thế đúng ạ và từ
[00:30:13] mình chạy qua nó vẫn thế đúng ạ và từ
[00:30:13] mình chạy qua nó vẫn thế đúng ạ và từ cái việc các bạn để ý kĩ nhé từ cái việc
[00:30:17] cái việc các bạn để ý kĩ nhé từ cái việc
[00:30:17] cái việc các bạn để ý kĩ nhé từ cái việc mà rút gọn rút gọn Vì cái vòng lập theo
[00:30:21] mà rút gọn rút gọn Vì cái vòng lập theo
[00:30:21] mà rút gọn rút gọn Vì cái vòng lập theo kiểu lại khai báo một lần không ạ tao
[00:30:24] kiểu lại khai báo một lần không ạ tao
[00:30:24] kiểu lại khai báo một lần không ạ tao tổng là một nơi này đúng ạ Cái kiểm tra
[00:30:27] tổng là một nơi này đúng ạ Cái kiểm tra
[00:30:27] tổng là một nơi này đúng ạ Cái kiểm tra cái kiểm tra vòng nạp chạy Tao để đương
[00:30:32] cái kiểm tra vòng nạp chạy Tao để đương
[00:30:32] cái kiểm tra vòng nạp chạy Tao để đương nhiên Bắc Bộ vẫn phải có cái luôn có cái
[00:30:34] nhiên Bắc Bộ vẫn phải có cái luôn có cái
[00:30:34] nhiên Bắc Bộ vẫn phải có cái luôn có cái thì kiểm tra vòng lặp còn đúng hay sai
[00:30:36] thì kiểm tra vòng lặp còn đúng hay sai
[00:30:36] thì kiểm tra vòng lặp còn đúng hay sai để chạy đúng không ạ
[00:30:39] để chạy đúng không ạ
[00:30:39] để chạy đúng không ạ A và
[00:30:40] A và
[00:30:40] A và chỉ cốt để chạy này và cái thứ để cháu
[00:30:43] chỉ cốt để chạy này và cái thứ để cháu
[00:30:43] chỉ cốt để chạy này và cái thứ để cháu vẫn còn lập tôi cho luôn ở trong lòng
[00:30:44] vẫn còn lập tôi cho luôn ở trong lòng
[00:30:44] vẫn còn lập tôi cho luôn ở trong lòng lại miếng để nó quấy được không ạ từ cái
[00:30:48] lại miếng để nó quấy được không ạ từ cái
[00:30:48] lại miếng để nó quấy được không ạ từ cái này chúng ta sẽ có vòng lặp while
[00:30:50] này chúng ta sẽ có vòng lặp while
[00:30:50] này chúng ta sẽ có vòng lặp while em lại giống như bạn kia đã nói đúng rồi
[00:30:53] em lại giống như bạn kia đã nói đúng rồi
[00:30:53] em lại giống như bạn kia đã nói đúng rồi lại đây mình sẽ có vòng lập qua à
[00:30:57] lại đây mình sẽ có vòng lập qua à
[00:30:57] lại đây mình sẽ có vòng lập qua à chú
[00:30:59] chú
[00:30:59] chú chó thì các bạn thấy là Kết quả nó như
[00:31:02] chó thì các bạn thấy là Kết quả nó như
[00:31:03] chó thì các bạn thấy là Kết quả nó như nhau à
[00:31:03] nhau à
[00:31:03] nhau à Ừ cái này tất cả Sao cái này là ok khai
[00:31:07] Ừ cái này tất cả Sao cái này là ok khai
[00:31:07] Ừ cái này tất cả Sao cái này là ok khai báo một lần không ạ tao khai báo đầu
[00:31:10] báo một lần không ạ tao khai báo đầu
[00:31:10] báo một lần không ạ tao khai báo đầu tiên ở ngoài sau đó đi Khi mà điều kiện
[00:31:13] tiên ở ngoài sau đó đi Khi mà điều kiện
[00:31:13] tiên ở ngoài sau đó đi Khi mà điều kiện vẫn còn đúng đúng không ạ thì mình chạy
[00:31:16] vẫn còn đúng đúng không ạ thì mình chạy
[00:31:16] vẫn còn đúng đúng không ạ thì mình chạy các thử cốt các thứ và cái cái này cái
[00:31:20] các thử cốt các thứ và cái cái này cái
[00:31:20] các thử cốt các thứ và cái cái này cái này là cái khác và nhiều bạn dễ quên này
[00:31:23] này là cái khác và nhiều bạn dễ quên này
[00:31:23] này là cái khác và nhiều bạn dễ quên này các bạn quên mất cái thứ để phá vỡ vòng
[00:31:26] các bạn quên mất cái thứ để phá vỡ vòng
[00:31:26] các bạn quên mất cái thứ để phá vỡ vòng lặp khi mà khi mà ghi vào trong khoai
[00:31:29] lặp khi mà khi mà ghi vào trong khoai
[00:31:29] lặp khi mà khi mà ghi vào trong khoai này mà nếu mà các bạn mà quên như thế
[00:31:33] này mà nếu mà các bạn mà quên như thế
[00:31:33] này mà nếu mà các bạn mà quên như thế này
[00:31:39] thì các bạn quên như thế này thì vòng
[00:31:39] thì các bạn quên như thế này thì vòng lặp này nó sẽ chạy đi chạy lại In số 1
[00:31:42] lặp này nó sẽ chạy đi chạy lại In số 1
[00:31:42] lặp này nó sẽ chạy đi chạy lại In số 1 lặp lại liên tục bởi vì rõ dai không ngờ
[00:31:45] lặp lại liên tục bởi vì rõ dai không ngờ
[00:31:45] lặp lại liên tục bởi vì rõ dai không ngờ tăng thành ra lạc không bao giờ kiểu phá
[00:31:49] tăng thành ra lạc không bao giờ kiểu phá
[00:31:49] tăng thành ra lạc không bao giờ kiểu phá vỡ vòng lập này và chạy đi chạy lại nếu
[00:31:52] vỡ vòng lập này và chạy đi chạy lại nếu
[00:31:52] vỡ vòng lập này và chạy đi chạy lại nếu mà Mấy ông chạy cái này thì trang web nó
[00:31:54] mà Mấy ông chạy cái này thì trang web nó
[00:31:54] mà Mấy ông chạy cái này thì trang web nó sẽ treo như thế này treo như này thì mấy
[00:31:57] sẽ treo như thế này treo như này thì mấy
[00:31:57] sẽ treo như thế này treo như này thì mấy ông thấy treo này nếu phải tắt vội ngay
[00:31:59] ông thấy treo này nếu phải tắt vội ngay
[00:31:59] ông thấy treo này nếu phải tắt vội ngay nhá vẫn chưa tắt luôn chọn tát thì gửi
[00:32:01] nhá vẫn chưa tắt luôn chọn tát thì gửi
[00:32:01] nhá vẫn chưa tắt luôn chọn tát thì gửi nó chết rồi à
[00:32:04] nó chết rồi à
[00:32:04] nó chết rồi à cho
[00:32:05] cho
[00:32:05] cho tôi lại mở lên à Tôi xin lỗi à
[00:32:19] à à Bạn kiến thắc mắc về in xuống 10
[00:32:19] à à Bạn kiến thắc mắc về in xuống 10 mình mình xóa này đi được mà ạ
[00:32:22] mình mình xóa này đi được mà ạ
[00:32:22] mình mình xóa này đi được mà ạ Ừ nhưng mà mình mình mình chưa muốn xóa
[00:32:25] Ừ nhưng mà mình mình mình chưa muốn xóa
[00:32:25] Ừ nhưng mà mình mình mình chưa muốn xóa vội bởi vì ạ Tí mình sẽ giải thích về vụ
[00:32:30] vội bởi vì ạ Tí mình sẽ giải thích về vụ
[00:32:30] vội bởi vì ạ Tí mình sẽ giải thích về vụ có một cái vụ nữa giống tương tự tương
[00:32:34] có một cái vụ nữa giống tương tự tương
[00:32:34] có một cái vụ nữa giống tương tự tương tự giống như là cái vừa nãy mình nói và
[00:32:36] tự giống như là cái vừa nãy mình nói và
[00:32:36] tự giống như là cái vừa nãy mình nói và vòng lặp bằng là pho thì nó cũng tương
[00:32:39] vòng lặp bằng là pho thì nó cũng tương
[00:32:39] vòng lặp bằng là pho thì nó cũng tương tự giống mong là White ở điểm là nếu là
[00:32:41] tự giống mong là White ở điểm là nếu là
[00:32:41] tự giống mong là White ở điểm là nếu là sử mà bây giờ mình cho Y = 100 được ạ
[00:32:45] sử mà bây giờ mình cho Y = 100 được ạ
[00:32:45] sử mà bây giờ mình cho Y = 100 được ạ Các bạn thấy nó không in
[00:32:48] Các bạn thấy nó không in
[00:32:48] Các bạn thấy nó không in anh làm sao mà in từ 1 đến 100 được hãy
[00:32:52] anh làm sao mà in từ 1 đến 100 được hãy
[00:32:52] anh làm sao mà in từ 1 đến 100 được hãy các thử được bởi rõ ra mà 100 Nó lớn hơn
[00:32:55] các thử được bởi rõ ra mà 100 Nó lớn hơn
[00:32:55] các thử được bởi rõ ra mà 100 Nó lớn hơn 10 mất rồi nên hàng giờ nó không chạy
[00:32:58] 10 mất rồi nên hàng giờ nó không chạy
[00:32:58] 10 mất rồi nên hàng giờ nó không chạy bằng lập luôn đúng không ạ nó không cộng
[00:33:00] bằng lập luôn đúng không ạ nó không cộng
[00:33:00] bằng lập luôn đúng không ạ nó không cộng đi luôn và nó sẽ in ra ra mỗi y thôi và
[00:33:04] đi luôn và nó sẽ in ra ra mỗi y thôi và
[00:33:04] đi luôn và nó sẽ in ra ra mỗi y thôi và bằng 100 luôn đúng không ạ ạ
[00:33:12] Ừ đấy thì tại sao tự nhiên mình cứ phải
[00:33:12] Ừ đấy thì tại sao tự nhiên mình cứ phải để cập về cái vụ là việc vòng lặp nó
[00:33:14] để cập về cái vụ là việc vòng lặp nó
[00:33:14] để cập về cái vụ là việc vòng lặp nó không chạy thì nó sẽ in ra như nào Cái
[00:33:17] không chạy thì nó sẽ in ra như nào Cái
[00:33:17] không chạy thì nó sẽ in ra như nào Cái này các bạn biết rồi mà đúng ạ Bởi vì
[00:33:20] này các bạn biết rồi mà đúng ạ Bởi vì
[00:33:20] này các bạn biết rồi mà đúng ạ Bởi vì bây giờ mình sẽ dậy nốt các bạn về cái
[00:33:22] bây giờ mình sẽ dậy nốt các bạn về cái
[00:33:22] bây giờ mình sẽ dậy nốt các bạn về cái vòng lặp đu White đúng ạ
[00:33:24] vòng lặp đu White đúng ạ
[00:33:24] vòng lặp đu White đúng ạ mà mập duyy Tức là sao dai này nó sẽ
[00:33:28] mà mập duyy Tức là sao dai này nó sẽ
[00:33:28] mà mập duyy Tức là sao dai này nó sẽ Tống xuống dưới
[00:33:29] Tống xuống dưới
[00:33:29] Tống xuống dưới em
[00:33:30] em
[00:33:30] em và nó sẽ có đủ ở trên thế này các bạn sẽ
[00:33:34] và nó sẽ có đủ ở trên thế này các bạn sẽ
[00:33:34] và nó sẽ có đủ ở trên thế này các bạn sẽ để ý kỹ bạn sẽ thấy nó sẽ in ra 100
[00:33:39] để ý kỹ bạn sẽ thấy nó sẽ in ra 100
[00:33:39] để ý kỹ bạn sẽ thấy nó sẽ in ra 100 ý và thận Chị ơi cộng lên một để in 101
[00:33:43] ý và thận Chị ơi cộng lên một để in 101
[00:33:43] ý và thận Chị ơi cộng lên một để in 101 ở dưới cái vào lọ Dubai này tức là sao
[00:33:47] ở dưới cái vào lọ Dubai này tức là sao
[00:33:47] ở dưới cái vào lọ Dubai này tức là sao đu quay này nó lại theo Thiên hướng là
[00:33:50] đu quay này nó lại theo Thiên hướng là
[00:33:50] đu quay này nó lại theo Thiên hướng là nó luôn chạy ít nhất một lần cái vòng
[00:33:54] nó luôn chạy ít nhất một lần cái vòng
[00:33:54] nó luôn chạy ít nhất một lần cái vòng lọc trước khi kiểm tra điều kiện nếu mà
[00:33:57] lọc trước khi kiểm tra điều kiện nếu mà
[00:33:57] lọc trước khi kiểm tra điều kiện nếu mà điều kiện tự nhiên điều kiện đưa chắc
[00:33:59] điều kiện tự nhiên điều kiện đưa chắc
[00:33:59] điều kiện tự nhiên điều kiện đưa chắc chắn sai rồi đúng không ạ Nếu điều kiện
[00:34:01] chắn sai rồi đúng không ạ Nếu điều kiện
[00:34:01] chắn sai rồi đúng không ạ Nếu điều kiện sai thì đi nhiên nó dừng nó không chạy
[00:34:03] sai thì đi nhiên nó dừng nó không chạy
[00:34:03] sai thì đi nhiên nó dừng nó không chạy vòng làm tiếp
[00:34:05] vòng làm tiếp
[00:34:05] vòng làm tiếp Ừ nhưng mà ít nhất là nó chạy một lần đã
[00:34:08] Ừ nhưng mà ít nhất là nó chạy một lần đã
[00:34:08] Ừ nhưng mà ít nhất là nó chạy một lần đã đấy các bạn thấy nó có sẽ có sự khác
[00:34:11] đấy các bạn thấy nó có sẽ có sự khác
[00:34:11] đấy các bạn thấy nó có sẽ có sự khác biệt ở đây đúng không ạ Là là vòng mập
[00:34:14] biệt ở đây đúng không ạ Là là vòng mập
[00:34:14] biệt ở đây đúng không ạ Là là vòng mập đây mình sẽ tổng kết lại phải ba vòng
[00:34:17] đây mình sẽ tổng kết lại phải ba vòng
[00:34:17] đây mình sẽ tổng kết lại phải ba vòng lắp Mình vừa chỉ 3 vòng lặp này bao bằng
[00:34:20] lắp Mình vừa chỉ 3 vòng lặp này bao bằng
[00:34:20] lắp Mình vừa chỉ 3 vòng lặp này bao bằng là cơ bản các bạn sẽ biết thêm vào mặc
[00:34:22] là cơ bản các bạn sẽ biết thêm vào mặc
[00:34:22] là cơ bản các bạn sẽ biết thêm vào mặc Ford Liên quan à Anh về duyệt mạng nữa
[00:34:25] Ford Liên quan à Anh về duyệt mạng nữa
[00:34:25] Ford Liên quan à Anh về duyệt mạng nữa nhưng mà cái đấy mình không dạy ở trong
[00:34:28] nhưng mà cái đấy mình không dạy ở trong
[00:34:28] nhưng mà cái đấy mình không dạy ở trong mua Switch mình sẽ dạy ở bên pp sau vòng
[00:34:33] mua Switch mình sẽ dạy ở bên pp sau vòng
[00:34:33] mua Switch mình sẽ dạy ở bên pp sau vòng lặp for thì các bạn sẽ thấy nó có bốn
[00:34:35] lặp for thì các bạn sẽ thấy nó có bốn
[00:34:35] lặp for thì các bạn sẽ thấy nó có bốn biểu thức
[00:34:37] biểu thức
[00:34:37] biểu thức nó sẽ biến thức đầu là biểu thức A khai
[00:34:41] nó sẽ biến thức đầu là biểu thức A khai
[00:34:41] nó sẽ biến thức đầu là biểu thức A khai báo về Đức hai điều kiện kiểm tra điều
[00:34:45] báo về Đức hai điều kiện kiểm tra điều
[00:34:45] báo về Đức hai điều kiện kiểm tra điều kiện đúng không ạ Cái thứ ba là là
[00:34:49] kiện đúng không ạ Cái thứ ba là là
[00:34:49] kiện đúng không ạ Cái thứ ba là là cái biểu thức để phá vỡ điều kiện
[00:34:53] cái biểu thức để phá vỡ điều kiện
[00:34:53] cái biểu thức để phá vỡ điều kiện thứ càng khiến cho điều kiện trở thành
[00:34:56] thứ càng khiến cho điều kiện trở thành
[00:34:56] thứ càng khiến cho điều kiện trở thành sai đúng không ạ Và đều thức bốn là là
[00:34:59] sai đúng không ạ Và đều thức bốn là là
[00:34:59] sai đúng không ạ Và đều thức bốn là là cốt chạy vòng lặp đúng không ạ Ừ cứ cho
[00:35:02] cốt chạy vòng lặp đúng không ạ Ừ cứ cho
[00:35:02] cốt chạy vòng lặp đúng không ạ Ừ cứ cho là cốt Đi đái Con biểu thức White thì nó
[00:35:07] là cốt Đi đái Con biểu thức White thì nó
[00:35:07] là cốt Đi đái Con biểu thức White thì nó sẽ khác nó sẽ chỉ gồm hai biểu thức thôi
[00:35:11] sẽ khác nó sẽ chỉ gồm hai biểu thức thôi
[00:35:11] sẽ khác nó sẽ chỉ gồm hai biểu thức thôi nó sẽ là thì nó sẽ điều kiện ngay từ đầu
[00:35:17] nó sẽ là thì nó sẽ điều kiện ngay từ đầu
[00:35:17] nó sẽ là thì nó sẽ điều kiện ngay từ đầu luôn và cốt và đương nhiên các bạn sẽ
[00:35:21] luôn và cốt và đương nhiên các bạn sẽ
[00:35:21] luôn và cốt và đương nhiên các bạn sẽ thấy là nó sẽ Thiếu cái hai cái một cái
[00:35:24] thấy là nó sẽ Thiếu cái hai cái một cái
[00:35:24] thấy là nó sẽ Thiếu cái hai cái một cái cái sai báo đúng ạ và một cái là phá vỡ
[00:35:27] cái sai báo đúng ạ và một cái là phá vỡ
[00:35:27] cái sai báo đúng ạ và một cái là phá vỡ vòng phá vỡ điều kiện thì cái khai báo
[00:35:31] vòng phá vỡ điều kiện thì cái khai báo
[00:35:31] vòng phá vỡ điều kiện thì cái khai báo các bạn phải khai báo ở đâu đó trước
[00:35:32] các bạn phải khai báo ở đâu đó trước
[00:35:32] các bạn phải khai báo ở đâu đó trước trước cái mọc là của ai Không không phải
[00:35:35] trước cái mọc là của ai Không không phải
[00:35:35] trước cái mọc là của ai Không không phải nằm trong vòng 1 byte đó ngoại tiếp theo
[00:35:37] nằm trong vòng 1 byte đó ngoại tiếp theo
[00:35:37] nằm trong vòng 1 byte đó ngoại tiếp theo cái phá vỡ điều kiện các bạn phải nằm
[00:35:39] cái phá vỡ điều kiện các bạn phải nằm
[00:35:39] cái phá vỡ điều kiện các bạn phải nằm luôn trong phần cốt Còn nếu không thì
[00:35:41] luôn trong phần cốt Còn nếu không thì
[00:35:41] luôn trong phần cốt Còn nếu không thì điều kiện đấy sẽ chạy mãi không được
[00:35:43] điều kiện đấy sẽ chạy mãi không được
[00:35:43] điều kiện đấy sẽ chạy mãi không được không ạ Và còn cái dwight d
[00:35:46] không ạ Và còn cái dwight d
[00:35:46] không ạ Và còn cái dwight d em
[00:35:47] em
[00:35:47] em về cơ bản thì các bạn sẽ thấy là nếu mà
[00:35:50] về cơ bản thì các bạn sẽ thấy là nếu mà
[00:35:50] về cơ bản thì các bạn sẽ thấy là nếu mà viết theo kiểu như trên này thì rõ ràng
[00:35:52] viết theo kiểu như trên này thì rõ ràng
[00:35:53] viết theo kiểu như trên này thì rõ ràng là Dubai khác gì với ye cả đúng không ạ
[00:35:55] là Dubai khác gì với ye cả đúng không ạ
[00:35:55] là Dubai khác gì với ye cả đúng không ạ ạ ạ
[00:35:57] ạ ạ
[00:35:57] ạ ạ [âm nhạc]
[00:35:59] [âm nhạc]
[00:35:59] [âm nhạc] Ừ nhưng mà cái sự khác biệt ở đây đó là
[00:36:01] Ừ nhưng mà cái sự khác biệt ở đây đó là
[00:36:01] Ừ nhưng mà cái sự khác biệt ở đây đó là cái for và cái Có ai như mình nói nó là
[00:36:05] cái for và cái Có ai như mình nói nó là
[00:36:05] cái for và cái Có ai như mình nói nó là điều kiện đúng thì nó mấy chạy đúng ạ
[00:36:09] điều kiện đúng thì nó mấy chạy đúng ạ
[00:36:09] điều kiện đúng thì nó mấy chạy đúng ạ Còn đu quay là nó sẽ chạy trước rồi nó
[00:36:12] Còn đu quay là nó sẽ chạy trước rồi nó
[00:36:12] Còn đu quay là nó sẽ chạy trước rồi nó mới kiểm tra điều kiện đúng hạn nghĩa là
[00:36:15] mới kiểm tra điều kiện đúng hạn nghĩa là
[00:36:15] mới kiểm tra điều kiện đúng hạn nghĩa là kiểu gì nó cũng sẽ chạy ít nhất một lần
[00:36:16] kiểu gì nó cũng sẽ chạy ít nhất một lần
[00:36:16] kiểu gì nó cũng sẽ chạy ít nhất một lần ít nhất một lần không ạ
[00:36:19] ít nhất một lần không ạ
[00:36:19] ít nhất một lần không ạ em vừa rồi mình tổng kết lại à
[00:36:23] em vừa rồi mình tổng kết lại à
[00:36:23] em vừa rồi mình tổng kết lại à ô ma vòng lọc các bạn thấy à
[00:36:26] ô ma vòng lọc các bạn thấy à
[00:36:26] ô ma vòng lọc các bạn thấy à anh có hẹn tương đối nhanh mình cảm thấy
[00:36:29] anh có hẹn tương đối nhanh mình cảm thấy
[00:36:29] anh có hẹn tương đối nhanh mình cảm thấy nhanh 8:20 mới rồi
[00:36:32] nhanh 8:20 mới rồi
[00:36:32] nhanh 8:20 mới rồi nhé bây giờ
[00:36:34] nhé bây giờ
[00:36:34] nhé bây giờ áp dụng nó kết hợp với bài tập thì nó
[00:36:37] áp dụng nó kết hợp với bài tập thì nó
[00:36:37] áp dụng nó kết hợp với bài tập thì nó mới kiểu mày ra là vấn đề không ạ Chứ lý
[00:36:40] mới kiểu mày ra là vấn đề không ạ Chứ lý
[00:36:40] mới kiểu mày ra là vấn đề không ạ Chứ lý thuyết lý thuyết mình hạn chế lý thuyết
[00:36:43] thuyết lý thuyết mình hạn chế lý thuyết
[00:36:43] thuyết lý thuyết mình hạn chế lý thuyết của bọn lý thuyết mình sẽ dậy rất ngắn
[00:36:45] của bọn lý thuyết mình sẽ dậy rất ngắn
[00:36:45] của bọn lý thuyết mình sẽ dậy rất ngắn Các bạn thấy ra một tiếng mình dạy lý
[00:36:47] Các bạn thấy ra một tiếng mình dạy lý
[00:36:47] Các bạn thấy ra một tiếng mình dạy lý thuyết sẽ nhắn à
[00:36:49] thuyết sẽ nhắn à
[00:36:49] thuyết sẽ nhắn à ạ bây giờ để sao mày tập thì mình xin
[00:36:52] ạ bây giờ để sao mày tập thì mình xin
[00:36:52] ạ bây giờ để sao mày tập thì mình xin phép là bây giờ sẽ kết hợp luôn và cái
[00:36:54] phép là bây giờ sẽ kết hợp luôn và cái
[00:36:54] phép là bây giờ sẽ kết hợp luôn và cái cả cái input Ê bà kết hợp từ bài bố
[00:36:58] cả cái input Ê bà kết hợp từ bài bố
[00:36:58] cả cái input Ê bà kết hợp từ bài bố xuống trước nữa input ướt ở xa nghĩa là
[00:37:01] xuống trước nữa input ướt ở xa nghĩa là
[00:37:01] xuống trước nữa input ướt ở xa nghĩa là bây giờ thay vì mình gán luôn hẳn cái
[00:37:04] bây giờ thay vì mình gán luôn hẳn cái
[00:37:04] bây giờ thay vì mình gán luôn hẳn cái dụng Red eye bằng 10 như này sẽ mình đi
[00:37:07] dụng Red eye bằng 10 như này sẽ mình đi
[00:37:07] dụng Red eye bằng 10 như này sẽ mình đi thẳng vào trong cốt là mười thực ra thế
[00:37:09] thẳng vào trong cốt là mười thực ra thế
[00:37:09] thẳng vào trong cốt là mười thực ra thế này không tốt Bởi vì bây giờ là mình
[00:37:11] này không tốt Bởi vì bây giờ là mình
[00:37:11] này không tốt Bởi vì bây giờ là mình tương tác và tương tác với người khách
[00:37:13] tương tác và tương tác với người khách
[00:37:13] tương tác và tương tác với người khách hàng với người dùng ở ngoài người dùng
[00:37:16] hàng với người dùng ở ngoài người dùng
[00:37:16] hàng với người dùng ở ngoài người dùng sẽ đi để các màn hình như thế này người
[00:37:18] sẽ đi để các màn hình như thế này người
[00:37:18] sẽ đi để các màn hình như thế này người dùng nhập cái gì đó sẽ in ra cái gì đó
[00:37:20] dùng nhập cái gì đó sẽ in ra cái gì đó
[00:37:20] dùng nhập cái gì đó sẽ in ra cái gì đó đúng ạ thay vì rồi mình mình bắt người
[00:37:24] đúng ạ thay vì rồi mình mình bắt người
[00:37:24] đúng ạ thay vì rồi mình mình bắt người xem vào cốt để nó sửa như thế này sẽ
[00:37:26] xem vào cốt để nó sửa như thế này sẽ
[00:37:26] xem vào cốt để nó sửa như thế này sẽ không được đúng không ạ
[00:37:27] không được đúng không ạ
[00:37:27] không được đúng không ạ à à
[00:37:29] à à
[00:37:29] à à ạ Bây giờ mình sẽ có cái là nhập
[00:37:33] ạ Bây giờ mình sẽ có cái là nhập
[00:37:33] ạ Bây giờ mình sẽ có cái là nhập số đầu tiên ở Thôi mình cứ dậy đơn giản
[00:37:37] số đầu tiên ở Thôi mình cứ dậy đơn giản
[00:37:37] số đầu tiên ở Thôi mình cứ dậy đơn giản trước là nhập tên của bạn chẳng hạn cái
[00:37:40] trước là nhập tên của bạn chẳng hạn cái
[00:37:40] trước là nhập tên của bạn chẳng hạn cái này rất cơ bản là không ạ Chị sẽ có cái
[00:37:42] này rất cơ bản là không ạ Chị sẽ có cái
[00:37:42] này rất cơ bản là không ạ Chị sẽ có cái input đi này nó khai thac này và đây sẽ
[00:37:48] input đi này nó khai thac này và đây sẽ
[00:37:48] input đi này nó khai thac này và đây sẽ là như thế này là sự giả sử Nga nhập tên
[00:37:52] là như thế này là sự giả sử Nga nhập tên
[00:37:52] là như thế này là sự giả sử Nga nhập tên của bạn Sau đó mình sẽ có cái nút ở đây
[00:37:55] của bạn Sau đó mình sẽ có cái nút ở đây
[00:37:55] của bạn Sau đó mình sẽ có cái nút ở đây là kiểm tra ip à Ừ
[00:38:07] hình ảnh kiểu nhà Okay Thi Thi ở đây ra
[00:38:07] hình ảnh kiểu nhà Okay Thi Thi ở đây ra xử là sợ là
[00:38:15] đó là sự là bạn nhập tên dụng là anh
[00:38:15] đó là sự là bạn nhập tên dụng là anh hàng ạ ấn vào như thế này nó sẽ in ra
[00:38:18] hàng ạ ấn vào như thế này nó sẽ in ra
[00:38:18] hàng ạ ấn vào như thế này nó sẽ in ra Xin chào bạn anh bạn tôi thông minh rồi
[00:38:20] Xin chào bạn anh bạn tôi thông minh rồi
[00:38:20] Xin chào bạn anh bạn tôi thông minh rồi ạ chào cờ thế đấy thi lại đại khái à là
[00:38:25] ạ chào cờ thế đấy thi lại đại khái à là
[00:38:25] ạ chào cờ thế đấy thi lại đại khái à là như thế nữa là mình sẽ lấy cái thứ mà
[00:38:28] như thế nữa là mình sẽ lấy cái thứ mà
[00:38:28] như thế nữa là mình sẽ lấy cái thứ mà người ta đã ngập rồi kết hợp với một cái
[00:38:30] người ta đã ngập rồi kết hợp với một cái
[00:38:30] người ta đã ngập rồi kết hợp với một cái câu gì đó của mình bán nữa Đúng là một
[00:38:32] câu gì đó của mình bán nữa Đúng là một
[00:38:32] câu gì đó của mình bán nữa Đúng là một cái chuỗi gì đó của mình và nữa thì lấy
[00:38:35] cái chuỗi gì đó của mình và nữa thì lấy
[00:38:35] cái chuỗi gì đó của mình và nữa thì lấy cái thứ mà người ta đã nhập thì mình sẽ
[00:38:37] cái thứ mà người ta đã nhập thì mình sẽ
[00:38:37] cái thứ mà người ta đã nhập thì mình sẽ thông qua việc là lấy có thể có thể theo
[00:38:42] thông qua việc là lấy có thể có thể theo
[00:38:42] thông qua việc là lấy có thể có thể theo nhiều cách một là theo thẻ input như thế
[00:38:45] nhiều cách một là theo thẻ input như thế
[00:38:45] nhiều cách một là theo thẻ input như thế này Nhưng mà nếu mà trong một form có
[00:38:48] này Nhưng mà nếu mà trong một form có
[00:38:48] này Nhưng mà nếu mà trong một form có nhiều cái thẻ input này quá thành nhà
[00:38:51] nhiều cái thẻ input này quá thành nhà
[00:38:51] nhiều cái thẻ input này quá thành nhà lại thành sai đúng không ạ
[00:38:54] lại thành sai đúng không ạ
[00:38:54] lại thành sai đúng không ạ cho nên có cách thứ hai là lấy theo ID
[00:38:57] cho nên có cách thứ hai là lấy theo ID
[00:38:57] cho nên có cách thứ hai là lấy theo ID bởi ID nó duy nhất
[00:39:00] bởi ID nó duy nhất
[00:39:00] bởi ID nó duy nhất Ừ thì mình sẽ thường ai lấy theo ID mình
[00:39:03] Ừ thì mình sẽ thường ai lấy theo ID mình
[00:39:03] Ừ thì mình sẽ thường ai lấy theo ID mình sẽ đặt tên nó lại input là
[00:39:11] Ừ ông kia vẫn hỏi thôi Tại sao không
[00:39:11] Ừ ông kia vẫn hỏi thôi Tại sao không dùng ghép cốt à
[00:39:12] dùng ghép cốt à
[00:39:12] dùng ghép cốt à Ừ ông nào đó trả lời của tôi có lấy được
[00:39:16] Ừ ông nào đó trả lời của tôi có lấy được
[00:39:16] Ừ ông nào đó trả lời của tôi có lấy được 39 phút tên ở Lạng Sơn hay là tên như
[00:39:20] 39 phút tên ở Lạng Sơn hay là tên như
[00:39:20] 39 phút tên ở Lạng Sơn hay là tên như thế này à ờ ờ
[00:39:30] à à
[00:39:30] à à Ờ Ờ
[00:39:31] Ờ Ờ
[00:39:31] Ờ Ờ mình mình để lấy được cái cái cái này về
[00:39:36] mình mình để lấy được cái cái cái này về
[00:39:36] mình mình để lấy được cái cái cái này về thì mình sẽ là nó của mình
[00:39:40] thì mình sẽ là nó của mình
[00:39:40] thì mình sẽ là nó của mình Chấm ghét almond bye đi này
[00:39:43] Chấm ghét almond bye đi này
[00:39:43] Chấm ghét almond bye đi này hóa hoặc là các bạn gõ ngày xong rồi Tát
[00:39:46] hóa hoặc là các bạn gõ ngày xong rồi Tát
[00:39:46] hóa hoặc là các bạn gõ ngày xong rồi Tát ra xong rồi đi chữ y ngay là đường Đấy
[00:39:49] ra xong rồi đi chữ y ngay là đường Đấy
[00:39:49] ra xong rồi đi chữ y ngay là đường Đấy in phút
[00:39:51] in phút
[00:39:51] in phút tên này à ba chấm ba lô này
[00:40:01] Ừ nếu mà chấm baru tất cả lấy giá trị nó
[00:40:01] Ừ nếu mà chấm baru tất cả lấy giá trị nó bên mình sẽ đặt một cái vọng à Một cái
[00:40:06] bên mình sẽ đặt một cái vọng à Một cái
[00:40:06] bên mình sẽ đặt một cái vọng à Một cái biến và biến tên như thế này Đấy
[00:40:09] biến và biến tên như thế này Đấy
[00:40:09] biến và biến tên như thế này Đấy sau đó thì mình đo comment chấm right
[00:40:13] sau đó thì mình đo comment chấm right
[00:40:13] sau đó thì mình đo comment chấm right này in ra thật sự là xin chào bạn xong
[00:40:18] này in ra thật sự là xin chào bạn xong
[00:40:18] này in ra thật sự là xin chào bạn xong ngồi nội tên mà như hai đứa bạn
[00:40:20] ngồi nội tên mà như hai đứa bạn
[00:40:20] ngồi nội tên mà như hai đứa bạn bên mình chạy nhé
[00:40:22] bên mình chạy nhé
[00:40:22] bên mình chạy nhé tải lại này các bạn thấy thử cao nó đã
[00:40:26] tải lại này các bạn thấy thử cao nó đã
[00:40:26] tải lại này các bạn thấy thử cao nó đã bị lỗi mà mình sẽ bị lôi xuống dòng các
[00:40:28] bị lỗi mà mình sẽ bị lôi xuống dòng các
[00:40:28] bị lỗi mà mình sẽ bị lôi xuống dòng các bạn cho bạn dễ nhìn nhé
[00:40:33] thì
[00:40:33] thì các bạn thấy nó đang bị lỗi Tại sao em
[00:40:37] các bạn thấy nó đang bị lỗi Tại sao em
[00:40:37] các bạn thấy nó đang bị lỗi Tại sao em chưa kịp Bấm cái nút em còn chưa điền
[00:40:39] chưa kịp Bấm cái nút em còn chưa điền
[00:40:39] chưa kịp Bấm cái nút em còn chưa điền cái gì cả đúng không ạ Tại sao nó hiển
[00:40:41] cái gì cả đúng không ạ Tại sao nó hiển
[00:40:41] cái gì cả đúng không ạ Tại sao nó hiển thị ra luôn cái Xin chào bạn thì gì đó
[00:40:43] thị ra luôn cái Xin chào bạn thì gì đó
[00:40:43] thị ra luôn cái Xin chào bạn thì gì đó như này cái giờ em giả sử em gõ cho em
[00:40:46] như này cái giờ em giả sử em gõ cho em
[00:40:46] như này cái giờ em giả sử em gõ cho em bấm nút thì được không ạ Chả có gì cả
[00:40:49] bấm nút thì được không ạ Chả có gì cả
[00:40:49] bấm nút thì được không ạ Chả có gì cả thì ở đây bài toán khó là như thế nào nó
[00:40:52] thì ở đây bài toán khó là như thế nào nó
[00:40:52] thì ở đây bài toán khó là như thế nào nó là
[00:40:53] là
[00:40:53] là Ờ Ờ
[00:40:55] Ờ Ờ
[00:40:55] Ờ Ờ mình cần Không cần hiển thị ra cái Xin
[00:40:59] mình cần Không cần hiển thị ra cái Xin
[00:40:59] mình cần Không cần hiển thị ra cái Xin chào luôn ngay từ khi vào trang web mà
[00:41:02] chào luôn ngay từ khi vào trang web mà
[00:41:02] chào luôn ngay từ khi vào trang web mà mình cần khi bấm vào cái nút này nó mấy
[00:41:05] mình cần khi bấm vào cái nút này nó mấy
[00:41:05] mình cần khi bấm vào cái nút này nó mấy chạy về đoạn nó mới lấy cái thứ mình đã
[00:41:07] chạy về đoạn nó mới lấy cái thứ mình đã
[00:41:07] chạy về đoạn nó mới lấy cái thứ mình đã nhập đúng ạ Rồi rồi hiển thị ra đủ Xin
[00:41:13] nhập đúng ạ Rồi rồi hiển thị ra đủ Xin
[00:41:13] nhập đúng ạ Rồi rồi hiển thị ra đủ Xin chào đúng không ạ
[00:41:15] chào đúng không ạ
[00:41:15] chào đúng không ạ Ừ thì thì cái cái việc khi bấm vào nút
[00:41:19] Ừ thì thì cái cái việc khi bấm vào nút
[00:41:19] Ừ thì thì cái cái việc khi bấm vào nút thì nó mới chạy cái gì đó thì mình sẽ có
[00:41:22] thì nó mới chạy cái gì đó thì mình sẽ có
[00:41:22] thì nó mới chạy cái gì đó thì mình sẽ có khái niệm là on click như thế này và
[00:41:25] khái niệm là on click như thế này và
[00:41:26] khái niệm là on click như thế này và nhà mình có thể có luôn toàn bộ code này
[00:41:29] nhà mình có thể có luôn toàn bộ code này
[00:41:29] nhà mình có thể có luôn toàn bộ code này Vào trong này như này cũng được nhưng mà
[00:41:31] Vào trong này như này cũng được nhưng mà
[00:41:31] Vào trong này như này cũng được nhưng mà các bạn hãy việc mất đi toàn bộ cốt vào
[00:41:34] các bạn hãy việc mất đi toàn bộ cốt vào
[00:41:34] các bạn hãy việc mất đi toàn bộ cốt vào cái này để chạy như thế này thì trông nó
[00:41:36] cái này để chạy như thế này thì trông nó
[00:41:36] cái này để chạy như thế này thì trông nó bị xấu khó đọc cũng như là kiểu nó rối
[00:41:40] bị xấu khó đọc cũng như là kiểu nó rối
[00:41:40] bị xấu khó đọc cũng như là kiểu nó rối quá đúng ạ Cái kiểu đấy cửa in life ạ ra
[00:41:43] quá đúng ạ Cái kiểu đấy cửa in life ạ ra
[00:41:43] quá đúng ạ Cái kiểu đấy cửa in life ạ ra Switch in life thì thường mà chẳng hay
[00:41:47] Switch in life thì thường mà chẳng hay
[00:41:47] Switch in life thì thường mà chẳng hay áp dụng đấy thường là mình sẽ gọi đến
[00:41:50] áp dụng đấy thường là mình sẽ gọi đến
[00:41:50] áp dụng đấy thường là mình sẽ gọi đến cái hàm ở đó đây mình sẽ gọi đến hàn là
[00:41:53] cái hàm ở đó đây mình sẽ gọi đến hàn là
[00:41:53] cái hàm ở đó đây mình sẽ gọi đến hàn là hàm à in ra ạ in ra như thế nào đó thì
[00:42:01] hàm à in ra ạ in ra như thế nào đó thì
[00:42:01] hàm à in ra ạ in ra như thế nào đó thì để gọi với cái Hà Min da này mình sẽ tạo
[00:42:03] để gọi với cái Hà Min da này mình sẽ tạo
[00:42:03] để gọi với cái Hà Min da này mình sẽ tạo ra một cái Hàn là Hà Min ra
[00:42:06] ra một cái Hàn là Hà Min ra
[00:42:06] ra một cái Hàn là Hà Min ra thế này ở đó 30 sống ở như thế này mình
[00:42:11] thế này ở đó 30 sống ở như thế này mình
[00:42:11] thế này ở đó 30 sống ở như thế này mình chạy thử anh này bấm vào này đó thì nó
[00:42:16] chạy thử anh này bấm vào này đó thì nó
[00:42:16] chạy thử anh này bấm vào này đó thì nó mới xin chào bạn anh không ạ Ok không ạ
[00:42:20] mới xin chào bạn anh không ạ Ok không ạ
[00:42:20] mới xin chào bạn anh không ạ Ok không ạ thì các bạn hiểu chưa ạ à
[00:42:22] thì các bạn hiểu chưa ạ à
[00:42:22] thì các bạn hiểu chưa ạ à Ê mấy ông ấy giờ Cãi nhau cái gì đấy
[00:42:26] Ê mấy ông ấy giờ Cãi nhau cái gì đấy
[00:42:26] Ê mấy ông ấy giờ Cãi nhau cái gì đấy ở tập trung là tốt chút nào hay ở cái
[00:42:29] ở tập trung là tốt chút nào hay ở cái
[00:42:29] ở tập trung là tốt chút nào hay ở cái này dễ quà ấy mấy ông chuyển qua ngồi
[00:42:31] này dễ quà ấy mấy ông chuyển qua ngồi
[00:42:31] này dễ quà ấy mấy ông chuyển qua ngồi chém gió trên kinh xác của tôi đúng
[00:42:33] chém gió trên kinh xác của tôi đúng
[00:42:33] chém gió trên kinh xác của tôi đúng không ạ
[00:42:40] à à
[00:42:40] à à ở đây Các bạn thấy à
[00:42:43] ở đây Các bạn thấy à
[00:42:43] ở đây Các bạn thấy à Ừ
[00:42:44] Ừ
[00:42:44] Ừ cái cái cái việc thứ nhất đấy đó làm Nếu
[00:42:49] cái cái cái việc thứ nhất đấy đó làm Nếu
[00:42:49] cái cái cái việc thứ nhất đấy đó làm Nếu các bạn để ý kĩ là mình nãy rồi còn anh
[00:42:51] các bạn để ý kĩ là mình nãy rồi còn anh
[00:42:51] các bạn để ý kĩ là mình nãy rồi còn anh làm sai cơ mình đang làm sai
[00:42:54] làm sai cơ mình đang làm sai
[00:42:54] làm sai cơ mình đang làm sai Ừ cái sai ở đây đó là mình đã từng dặn
[00:42:58] Ừ cái sai ở đây đó là mình đã từng dặn
[00:42:58] Ừ cái sai ở đây đó là mình đã từng dặn Các bạn về vụ là mua khi có input
[00:43:02] Các bạn về vụ là mua khi có input
[00:43:02] Các bạn về vụ là mua khi có input Ừ thì phải luôn nằm trong thẻ home Các
[00:43:05] Ừ thì phải luôn nằm trong thẻ home Các
[00:43:05] Ừ thì phải luôn nằm trong thẻ home Các bạn nhớ không ạ Không bao giờ có trường
[00:43:08] bạn nhớ không ạ Không bao giờ có trường
[00:43:08] bạn nhớ không ạ Không bao giờ có trường hợp và để input đơn lẻ như thế này đúng
[00:43:10] hợp và để input đơn lẻ như thế này đúng
[00:43:10] hợp và để input đơn lẻ như thế này đúng không ạ mình phải luôn để nó nằm trong
[00:43:13] không ạ mình phải luôn để nó nằm trong
[00:43:13] không ạ mình phải luôn để nó nằm trong thẻ form đấy thì bây giờ ra sự mình có
[00:43:16] thẻ form đấy thì bây giờ ra sự mình có
[00:43:16] thẻ form đấy thì bây giờ ra sự mình có thể for đây đúng không ạ
[00:43:19] thể for đây đúng không ạ
[00:43:19] thể for đây đúng không ạ thì mình tống mà thôi ông ạ tổng cài bút
[00:43:22] thì mình tống mà thôi ông ạ tổng cài bút
[00:43:22] thì mình tống mà thôi ông ạ tổng cài bút cả postin vào trong thấy for này Thực ra
[00:43:25] cả postin vào trong thấy for này Thực ra
[00:43:25] cả postin vào trong thấy for này Thực ra là đóng thì iPhone rồi mình không cần PR
[00:43:27] là đóng thì iPhone rồi mình không cần PR
[00:43:27] là đóng thì iPhone rồi mình không cần PR nữa cũng được chạy này đó Bây giờ mình
[00:43:31] nữa cũng được chạy này đó Bây giờ mình
[00:43:31] nữa cũng được chạy này đó Bây giờ mình sẽ là chào bạn anh ấy ấn vào này đúng ạ
[00:43:35] sẽ là chào bạn anh ấy ấn vào này đúng ạ
[00:43:35] sẽ là chào bạn anh ấy ấn vào này đúng ạ Được rồi đúng không ạ Các bạn thấy được
[00:43:38] Được rồi đúng không ạ Các bạn thấy được
[00:43:38] Được rồi đúng không ạ Các bạn thấy được nhưng mà ở đây mình nặng khó chịu một tí
[00:43:48] anh khó chịu mới được mà ok Bây giờ em
[00:43:48] anh khó chịu mới được mà ok Bây giờ em muốn nhập tên bạn khác luôn em lại mất
[00:43:50] muốn nhập tên bạn khác luôn em lại mất
[00:43:50] muốn nhập tên bạn khác luôn em lại mất công tải lại sang nhà hiển thị ra đúng ạ
[00:43:52] công tải lại sang nhà hiển thị ra đúng ạ
[00:43:52] công tải lại sang nhà hiển thị ra đúng ạ Chị vừa Khanh Vì như thế Mình muốn thị
[00:43:55] Chị vừa Khanh Vì như thế Mình muốn thị
[00:43:55] Chị vừa Khanh Vì như thế Mình muốn thị ngay ở dòng ở dưới giống như vừa nãy đó
[00:43:57] ngay ở dòng ở dưới giống như vừa nãy đó
[00:43:57] ngay ở dòng ở dưới giống như vừa nãy đó mình hiển thị luôn ở dừa như này là xin
[00:44:01] mình hiển thị luôn ở dừa như này là xin
[00:44:01] mình hiển thị luôn ở dừa như này là xin chào bạn A B C thay vì cậu nó ghi đè lên
[00:44:05] chào bạn A B C thay vì cậu nó ghi đè lên
[00:44:05] chào bạn A B C thay vì cậu nó ghi đè lên toàn bộ HTML cũ của mình để mà hiển thị
[00:44:08] toàn bộ HTML cũ của mình để mà hiển thị
[00:44:08] toàn bộ HTML cũ của mình để mà hiển thị ra mỗi cái dòng chữ không ạ thì cái này
[00:44:10] ra mỗi cái dòng chữ không ạ thì cái này
[00:44:10] ra mỗi cái dòng chữ không ạ thì cái này mình sẽ không dùng đó còn dai nữa và lần
[00:44:13] mình sẽ không dùng đó còn dai nữa và lần
[00:44:13] mình sẽ không dùng đó còn dai nữa và lần này mình sẽ phải như thế nào mình sẽ tạo
[00:44:15] này mình sẽ phải như thế nào mình sẽ tạo
[00:44:15] này mình sẽ phải như thế nào mình sẽ tạo ra một cái đíp ở dưới này phòng cười
[00:44:17] ra một cái đíp ở dưới này phòng cười
[00:44:17] ra một cái đíp ở dưới này phòng cười span ở dưới một cái thiệp P ở dưới chẳng
[00:44:19] span ở dưới một cái thiệp P ở dưới chẳng
[00:44:19] span ở dưới một cái thiệp P ở dưới chẳng hạn Vân Vân ở trong một thứ ở dưới một
[00:44:23] hạn Vân Vân ở trong một thứ ở dưới một
[00:44:23] hạn Vân Vân ở trong một thứ ở dưới một cái ô để mà hiển thị ra xin chào Cái gì
[00:44:26] cái ô để mà hiển thị ra xin chào Cái gì
[00:44:26] cái ô để mà hiển thị ra xin chào Cái gì đó đúng ạ Chị sẽ có một cái đít này Đấy
[00:44:30] đó đúng ạ Chị sẽ có một cái đít này Đấy
[00:44:30] đó đúng ạ Chị sẽ có một cái đít này Đấy và mình sẽ gọi ai đi là cáo kết quả sản
[00:44:33] và mình sẽ gọi ai đi là cáo kết quả sản
[00:44:33] và mình sẽ gọi ai đi là cáo kết quả sản nào đó và bây giờ mình dậy in kết quả
[00:44:38] nào đó và bây giờ mình dậy in kết quả
[00:44:38] nào đó và bây giờ mình dậy in kết quả vào trong cái này chứ không phải đâu cần
[00:44:39] vào trong cái này chứ không phải đâu cần
[00:44:39] vào trong cái này chứ không phải đâu cần ra à sẽ ghi đè an toàn bộ HM cũ nữa thì
[00:44:42] ra à sẽ ghi đè an toàn bộ HM cũ nữa thì
[00:44:42] ra à sẽ ghi đè an toàn bộ HM cũ nữa thì nó sẽ lại ghét em mình body này và đây
[00:44:47] nó sẽ lại ghét em mình body này và đây
[00:44:47] nó sẽ lại ghét em mình body này và đây sẽ là kết quả này
[00:44:49] sẽ là kết quả này
[00:44:49] sẽ là kết quả này và đây sẽ là mình sẽ có khái niệm mà
[00:44:52] và đây sẽ là mình sẽ có khái niệm mà
[00:44:52] và đây sẽ là mình sẽ có khái niệm mà chuẩn inner HTML bằng đoạn chỗ như thế
[00:44:55] chuẩn inner HTML bằng đoạn chỗ như thế
[00:44:55] chuẩn inner HTML bằng đoạn chỗ như thế này à
[00:45:03] em có cốt kiểu này thì ra tôi thấy nó
[00:45:03] em có cốt kiểu này thì ra tôi thấy nó hơi bị ạ Đấy Tôi Lùi một tát cho mấy ông
[00:45:06] hơi bị ạ Đấy Tôi Lùi một tát cho mấy ông
[00:45:06] hơi bị ạ Đấy Tôi Lùi một tát cho mấy ông nhìn
[00:45:16] ở lại mấy ông nhìn có thể nó bị xuống
[00:45:16] ở lại mấy ông nhìn có thể nó bị xuống dòng một tí hai chữ hi vọng chữ đủ to do
[00:45:20] dòng một tí hai chữ hi vọng chữ đủ to do
[00:45:20] dòng một tí hai chữ hi vọng chữ đủ to do mấy ông đi à
[00:45:25] Á
[00:45:25] Á đù to chưa ạ ạ
[00:45:29] đù to chưa ạ ạ
[00:45:29] đù to chưa ạ ạ Ừ Thì bây giờ mình sẽ nhập dụng nhập anh
[00:45:32] Ừ Thì bây giờ mình sẽ nhập dụng nhập anh
[00:45:32] Ừ Thì bây giờ mình sẽ nhập dụng nhập anh nản ấn đây Xin chào bạn anh Các bạn thấy
[00:45:35] nản ấn đây Xin chào bạn anh Các bạn thấy
[00:45:35] nản ấn đây Xin chào bạn anh Các bạn thấy nó vừa thì đi ra Nhưng mà trước ngoan
[00:45:38] nó vừa thì đi ra Nhưng mà trước ngoan
[00:45:38] nó vừa thì đi ra Nhưng mà trước ngoan đúng không ạ chớp nhoáng luôn tại sao ạ
[00:45:40] đúng không ạ chớp nhoáng luôn tại sao ạ
[00:45:40] đúng không ạ chớp nhoáng luôn tại sao ạ bị ẩn anh này ấn phát nữa này nó thì chị
[00:45:43] bị ẩn anh này ấn phát nữa này nó thì chị
[00:45:43] bị ẩn anh này ấn phát nữa này nó thì chị ra xong rồi nó lại cha luôn tại sao nó
[00:45:46] ra xong rồi nó lại cha luôn tại sao nó
[00:45:46] ra xong rồi nó lại cha luôn tại sao nó lại nó lại trang như vừa rồi là bởi vì
[00:45:49] lại nó lại trang như vừa rồi là bởi vì
[00:45:49] lại nó lại trang như vừa rồi là bởi vì nếu mà các bạn để nó nằm trong lại phom
[00:45:52] nếu mà các bạn để nó nằm trong lại phom
[00:45:52] nếu mà các bạn để nó nằm trong lại phom kết hợp với nó là bất Tần như này thì nó
[00:45:55] kết hợp với nó là bất Tần như này thì nó
[00:45:55] kết hợp với nó là bất Tần như này thì nó sẽ Các bạn nhớ bọn Nếu mà cái nút như
[00:45:58] sẽ Các bạn nhớ bọn Nếu mà cái nút như
[00:45:58] sẽ Các bạn nhớ bọn Nếu mà cái nút như này không thôi thì thay của nó sẽ bằng
[00:46:01] này không thôi thì thay của nó sẽ bằng
[00:46:01] này không thôi thì thay của nó sẽ bằng sắm ít
[00:46:02] sắm ít
[00:46:02] sắm ít hay nó sắp ít tất cả nó sẽ gửi cái phone
[00:46:06] hay nó sắp ít tất cả nó sẽ gửi cái phone
[00:46:06] hay nó sắp ít tất cả nó sẽ gửi cái phone này lên gửi for mà lên đồng nghĩa việc
[00:46:09] này lên gửi for mà lên đồng nghĩa việc
[00:46:09] này lên gửi for mà lên đồng nghĩa việc là nó lạy cha mất rồi đóng mặt nó mà
[00:46:12] là nó lạy cha mất rồi đóng mặt nó mà
[00:46:12] là nó lạy cha mất rồi đóng mặt nó mà mình cần trang bang vẫn phải giữ nguyên
[00:46:16] mình cần trang bang vẫn phải giữ nguyên
[00:46:16] mình cần trang bang vẫn phải giữ nguyên ở đấy đúng không ạ chào vẫn giữ nguyên
[00:46:18] ở đấy đúng không ạ chào vẫn giữ nguyên
[00:46:18] ở đấy đúng không ạ chào vẫn giữ nguyên rồi đấy thì mình sẽ khái niệm nó bắt Tần
[00:46:20] rồi đấy thì mình sẽ khái niệm nó bắt Tần
[00:46:20] rồi đấy thì mình sẽ khái niệm nó bắt Tần Nghĩa này là hiểu nút này chuyển dạ Nó
[00:46:23] Nghĩa này là hiểu nút này chuyển dạ Nó
[00:46:23] Nghĩa này là hiểu nút này chuyển dạ Nó là cái nút thôi nó không một tác dụng
[00:46:25] là cái nút thôi nó không một tác dụng
[00:46:25] là cái nút thôi nó không một tác dụng gửi form lên ở bề mà nó lại tra đúng
[00:46:28] gửi form lên ở bề mà nó lại tra đúng
[00:46:28] gửi form lên ở bề mà nó lại tra đúng không ạ Mình tả lại xa phát nữa này gọi
[00:46:31] không ạ Mình tả lại xa phát nữa này gọi
[00:46:31] không ạ Mình tả lại xa phát nữa này gọi cho anh này ấn vào này đó là sự gọi chữ
[00:46:36] cho anh này ấn vào này đó là sự gọi chữ
[00:46:36] cho anh này ấn vào này đó là sự gọi chữ Long đấy Ấn vào như này được đúng không
[00:46:38] Long đấy Ấn vào như này được đúng không
[00:46:38] Long đấy Ấn vào như này được đúng không ạ Các bạn hoàn toàn giống như và nãy
[00:46:40] ạ Các bạn hoàn toàn giống như và nãy
[00:46:40] ạ Các bạn hoàn toàn giống như và nãy mình nói là có thể in ra nhận cái ví dụ
[00:46:42] mình nói là có thể in ra nhận cái ví dụ
[00:46:42] mình nói là có thể in ra nhận cái ví dụ là
[00:46:43] là
[00:46:43] là các
[00:46:44] các
[00:46:44] các bạn thật là thông minh
[00:46:48] bạn thật là thông minh
[00:46:48] bạn thật là thông minh DK lời đã bê cả đó đấy
[00:46:51] DK lời đã bê cả đó đấy
[00:46:51] DK lời đã bê cả đó đấy A
[00:46:53] A
[00:46:53] A bkl ở
[00:46:56] bkl ở
[00:46:56] bkl ở Việt kiều nhé
[00:46:58] Việt kiều nhé
[00:46:58] Việt kiều nhé ở đó
[00:47:05] Ừ thôi nãy hơi bậy rồi
[00:47:05] Ừ thôi nãy hơi bậy rồi đấy đúng không ạ Anh Tuấn chẳng ạ nhập
[00:47:09] đấy đúng không ạ Anh Tuấn chẳng ạ nhập
[00:47:09] đấy đúng không ạ Anh Tuấn chẳng ạ nhập được cả có dấu nhé đó
[00:47:14] Ừ
[00:47:14] Ừ Ok đúng rồi đúng không ạ
[00:47:18] Ok đúng rồi đúng không ạ
[00:47:18] Ok đúng rồi đúng không ạ thì các bạn sẽ thấy là à
[00:47:22] thì các bạn sẽ thấy là à
[00:47:22] thì các bạn sẽ thấy là à ở đây đây đây mới chỉ là cơ bản về việc
[00:47:26] ở đây đây đây mới chỉ là cơ bản về việc
[00:47:26] ở đây đây đây mới chỉ là cơ bản về việc là
[00:47:28] là
[00:47:28] là lấy cái thứ mà mình đã ngập trong cái Ôi
[00:47:31] lấy cái thứ mà mình đã ngập trong cái Ôi
[00:47:31] lấy cái thứ mà mình đã ngập trong cái Ôi nút cho in ra dọn rất cơ bản chồng kẹo
[00:47:34] nút cho in ra dọn rất cơ bản chồng kẹo
[00:47:34] nút cho in ra dọn rất cơ bản chồng kẹo Halloween các bạn học vậy nhưng nhưng mà
[00:47:37] Halloween các bạn học vậy nhưng nhưng mà
[00:47:37] Halloween các bạn học vậy nhưng nhưng mà bây giờ mày bắt ở nâng cao lên một tí
[00:47:39] bây giờ mày bắt ở nâng cao lên một tí
[00:47:39] bây giờ mày bắt ở nâng cao lên một tí thôi bắt đầu kiểm tra không ạ bây giờ
[00:47:41] thôi bắt đầu kiểm tra không ạ bây giờ
[00:47:41] thôi bắt đầu kiểm tra không ạ bây giờ Thái Bình nhập tên sẽ nhập con số thì đó
[00:47:45] Thái Bình nhập tên sẽ nhập con số thì đó
[00:47:45] Thái Bình nhập tên sẽ nhập con số thì đó sao mình is a nó chẵn hay lẻ thôi chẳng
[00:47:47] sao mình is a nó chẵn hay lẻ thôi chẳng
[00:47:47] sao mình is a nó chẵn hay lẻ thôi chẳng nào thì sẽ liên lạc
[00:47:49] nào thì sẽ liên lạc
[00:47:49] nào thì sẽ liên lạc nhập số cho này Đây là input số
[00:47:54] nhập số cho này Đây là input số
[00:47:54] nhập số cho này Đây là input số em kiểm tra
[00:47:56] em kiểm tra
[00:47:56] em kiểm tra chẵn lẻ
[00:47:58] chẵn lẻ
[00:47:58] chẵn lẻ để chẵn lẻ để in ra này Ừ kệ gì bạn ạ
[00:48:04] để chẵn lẻ để in ra này Ừ kệ gì bạn ạ
[00:48:04] để chẵn lẻ để in ra này Ừ kệ gì bạn ạ Bây giờ mình sẽ let
[00:48:06] Bây giờ mình sẽ let
[00:48:06] Bây giờ mình sẽ let số bằng cho comment
[00:48:10] số bằng cho comment
[00:48:10] số bằng cho comment bettermann Bye bye bút số đúng không ạ
[00:48:14] bettermann Bye bye bút số đúng không ạ
[00:48:14] bettermann Bye bye bút số đúng không ạ trên phút
[00:48:15] trên phút
[00:48:15] trên phút 0.3 lô này mình sẽ ít số phần trăm hay
[00:48:22] 0.3 lô này mình sẽ ít số phần trăm hay
[00:48:22] 0.3 lô này mình sẽ ít số phần trăm hay bằng bằng không là kiểm tra xem số số
[00:48:26] bằng bằng không là kiểm tra xem số số
[00:48:26] bằng bằng không là kiểm tra xem số số đây chia cho 2 lấy dư Nếu mà dư không
[00:48:30] đây chia cho 2 lấy dư Nếu mà dư không
[00:48:30] đây chia cho 2 lấy dư Nếu mà dư không tất cả số chẵn không ạ Mình sẽ là đó của
[00:48:34] tất cả số chẵn không ạ Mình sẽ là đó của
[00:48:34] tất cả số chẵn không ạ Mình sẽ là đó của mình chậm ra à Ghét em ân bye đi này kết
[00:48:40] mình chậm ra à Ghét em ân bye đi này kết
[00:48:40] mình chậm ra à Ghét em ân bye đi này kết quả này à
[00:48:45] cho
[00:48:45] cho nhtm là
[00:49:02] eo ở đây để số lẻ đúng không ạ
[00:49:02] eo ở đây để số lẻ đúng không ạ ừ ừ
[00:49:12] 32 Trả này nè này chả này ok không ạ
[00:49:12] 32 Trả này nè này chả này ok không ạ Nhưng ở đây Thực ra là nó có tí hơi sai
[00:49:14] Nhưng ở đây Thực ra là nó có tí hơi sai
[00:49:14] Nhưng ở đây Thực ra là nó có tí hơi sai sai nếu mà các bạn làm như thế này là sự
[00:49:16] sai nếu mà các bạn làm như thế này là sự
[00:49:16] sai nếu mà các bạn làm như thế này là sự 3.5 lại ra số lẻ thì buồn cười quá thì
[00:49:20] 3.5 lại ra số lẻ thì buồn cười quá thì
[00:49:20] 3.5 lại ra số lẻ thì buồn cười quá thì các bạn sẽ có thể là yeo ít ở đây này
[00:49:23] các bạn sẽ có thể là yeo ít ở đây này
[00:49:23] các bạn sẽ có thể là yeo ít ở đây này đây sẽ cậu bằng một số lẻ còn em nữa Ở
[00:49:28] đây sẽ cậu bằng một số lẻ còn em nữa Ở
[00:49:28] đây sẽ cậu bằng một số lẻ còn em nữa Ở đây là
[00:49:29] đây là
[00:49:29] đây là đây là số nguyên tố ở Ngạn anh em đề số
[00:49:33] đây là số nguyên tố ở Ngạn anh em đề số
[00:49:33] đây là số nguyên tố ở Ngạn anh em đề số thập phân là không ạ thập phân
[00:49:37] thập phân là không ạ thập phân
[00:49:37] thập phân là không ạ thập phân thân dưới đây không phải là số nhà mạng
[00:49:39] thân dưới đây không phải là số nhà mạng
[00:49:39] thân dưới đây không phải là số nhà mạng cũng được tùy mấy ông
[00:49:40] cũng được tùy mấy ông
[00:49:40] cũng được tùy mấy ông anh ở đây Tôi đang nghiệp chữ mà mọi thì
[00:49:44] anh ở đây Tôi đang nghiệp chữ mà mọi thì
[00:49:44] anh ở đây Tôi đang nghiệp chữ mà mọi thì đây ở đang số thập phân Thì có sai được
[00:49:46] đây ở đang số thập phân Thì có sai được
[00:49:46] đây ở đang số thập phân Thì có sai được không ạ Nếu các bạn muốn chắc chắn nó số
[00:49:49] không ạ Nếu các bạn muốn chắc chắn nó số
[00:49:49] không ạ Nếu các bạn muốn chắc chắn nó số thì các bạn để nó là number này à
[00:49:54] thì các bạn để nó là number này à
[00:49:54] thì các bạn để nó là number này à anh hả
[00:49:56] anh hả
[00:49:56] anh hả là số âm bị vẫn là chẵn lẻ được mà không
[00:49:59] là số âm bị vẫn là chẵn lẻ được mà không
[00:49:59] là số âm bị vẫn là chẵn lẻ được mà không ạ Còn nếu các bạn muốn kiểm tra việc
[00:50:02] ạ Còn nếu các bạn muốn kiểm tra việc
[00:50:02] ạ Còn nếu các bạn muốn kiểm tra việc bắt lỗi số các bạn so sánh nó với không
[00:50:05] bắt lỗi số các bạn so sánh nó với không
[00:50:05] bắt lỗi số các bạn so sánh nó với không ạ Các bạn so sánh nó với không Nếu mà
[00:50:08] ạ Các bạn so sánh nó với không Nếu mà
[00:50:08] ạ Các bạn so sánh nó với không Nếu mà lớn không thì thì thì in ra Còn nếu
[00:50:12] lớn không thì thì thì in ra Còn nếu
[00:50:12] lớn không thì thì thì in ra Còn nếu không thì ngược lại báo lỗi không ạ
[00:50:16] không thì ngược lại báo lỗi không ạ
[00:50:16] không thì ngược lại báo lỗi không ạ Ừ cái việc báo lỗi thì đây mình sẽ tiện
[00:50:19] Ừ cái việc báo lỗi thì đây mình sẽ tiện
[00:50:19] Ừ cái việc báo lỗi thì đây mình sẽ tiện nó luôn
[00:50:20] nó luôn
[00:50:20] nó luôn tránh sử là đây mấy ông đang thấy đó là
[00:50:24] tránh sử là đây mấy ông đang thấy đó là
[00:50:24] tránh sử là đây mấy ông đang thấy đó là tôi tôi muốn là
[00:50:27] tôi tôi muốn là
[00:50:27] tôi tôi muốn là áo kiểu
[00:50:29] áo kiểu
[00:50:29] áo kiểu in ra cái cái số thập phân này nhưng mà
[00:50:32] in ra cái cái số thập phân này nhưng mà
[00:50:32] in ra cái cái số thập phân này nhưng mà riêng với số thập phân thì tôi sẽ có màu
[00:50:34] riêng với số thập phân thì tôi sẽ có màu
[00:50:34] riêng với số thập phân thì tôi sẽ có màu khác không ạ sửa đây 3.5 thì các bạn sẽ
[00:50:38] khác không ạ sửa đây 3.5 thì các bạn sẽ
[00:50:38] khác không ạ sửa đây 3.5 thì các bạn sẽ thấy nói nào số thập phân nhưng mà riêng
[00:50:40] thấy nói nào số thập phân nhưng mà riêng
[00:50:40] thấy nói nào số thập phân nhưng mà riêng in số thập phân thì sẽ có màu khác thì
[00:50:44] in số thập phân thì sẽ có màu khác thì
[00:50:44] in số thập phân thì sẽ có màu khác thì mình sẽ Style này color này sẽ đổi nó
[00:50:47] mình sẽ Style này color này sẽ đổi nó
[00:50:47] mình sẽ Style này color này sẽ đổi nó thành màu đỏ đi à
[00:50:50] thành màu đỏ đi à
[00:50:50] thành màu đỏ đi à à à
[00:50:52] à à
[00:50:52] à à nghe 3.5 đấy
[00:50:55] nghe 3.5 đấy
[00:50:55] nghe 3.5 đấy ở đó
[00:50:57] ở đó
[00:50:57] ở đó Ừ nhưng mà chính vì khi mà chỉnh Speed
[00:51:00] Ừ nhưng mà chính vì khi mà chỉnh Speed
[00:51:00] Ừ nhưng mà chính vì khi mà chỉnh Speed này xong thì có nhớ có vẻ là nó sẽ không
[00:51:04] này xong thì có nhớ có vẻ là nó sẽ không
[00:51:04] này xong thì có nhớ có vẻ là nó sẽ không chạy lại nó sẽ không Chạy lại Cái vụ sai
[00:51:07] chạy lại nó sẽ không Chạy lại Cái vụ sai
[00:51:07] chạy lại nó sẽ không Chạy lại Cái vụ sai nữa Nhưng mà đồng thời thì do Style rõ
[00:51:10] nữa Nhưng mà đồng thời thì do Style rõ
[00:51:10] nữa Nhưng mà đồng thời thì do Style rõ khi đề CS lên cái đít này rồi thành đạt
[00:51:14] khi đề CS lên cái đít này rồi thành đạt
[00:51:14] khi đề CS lên cái đít này rồi thành đạt Deep này sẽ giữ nguyên mòi đúng không ạ
[00:51:15] Deep này sẽ giữ nguyên mòi đúng không ạ
[00:51:15] Deep này sẽ giữ nguyên mòi đúng không ạ Các bạn có thể để nó ở đây là sự đây là
[00:51:19] Các bạn có thể để nó ở đây là sự đây là
[00:51:19] Các bạn có thể để nó ở đây là sự đây là màu đen nếu mà các bạn muốn để mặc định
[00:51:22] màu đen nếu mà các bạn muốn để mặc định
[00:51:22] màu đen nếu mà các bạn muốn để mặc định đúng không ạ sẽ như này à
[00:51:26] đúng không ạ sẽ như này à
[00:51:26] đúng không ạ sẽ như này à ừ ừ
[00:51:28] ừ ừ
[00:51:28] ừ ừ ở
[00:51:29] ở
[00:51:29] ở đó rồi luôn các bạn sẽ thế là ra Swift
[00:51:34] đó rồi luôn các bạn sẽ thế là ra Swift
[00:51:34] đó rồi luôn các bạn sẽ thế là ra Swift có thể làm được cái này nó không đoán
[00:51:36] có thể làm được cái này nó không đoán
[00:51:36] có thể làm được cái này nó không đoán lại cha chạy chạy Các bạn ơi Không nói
[00:51:39] lại cha chạy chạy Các bạn ơi Không nói
[00:51:39] lại cha chạy chạy Các bạn ơi Không nói lại cha gì cả nó sẽ lập tức thì chị ra
[00:51:42] lại cha gì cả nó sẽ lập tức thì chị ra
[00:51:42] lại cha gì cả nó sẽ lập tức thì chị ra luôn tức thì luôn cho các bạn thấy
[00:51:44] luôn tức thì luôn cho các bạn thấy
[00:51:44] luôn tức thì luôn cho các bạn thấy ờ ờ
[00:51:45] ờ ờ
[00:51:45] ờ ờ Ok nhưng mà bài thế này vẫn dễ quá cũng
[00:51:49] Ok nhưng mà bài thế này vẫn dễ quá cũng
[00:51:49] Ok nhưng mà bài thế này vẫn dễ quá cũng chỉ lại ít theo thôi đưa mình đưa nó vào
[00:51:53] chỉ lại ít theo thôi đưa mình đưa nó vào
[00:51:53] chỉ lại ít theo thôi đưa mình đưa nó vào cái bài hôm trước mà mình đã làm bạn nhớ
[00:51:56] cái bài hôm trước mà mình đã làm bạn nhớ
[00:51:56] cái bài hôm trước mà mình đã làm bạn nhớ bài về
[00:52:08] A Tính số ngày trong tháng ạ đúng không
[00:52:08] A Tính số ngày trong tháng ạ đúng không ạ
[00:52:15] A Tính số ngày trong tháng để mày đi làm
[00:52:15] A Tính số ngày trong tháng để mày đi làm cái gì đó đúng không ạ là sửa nhé này đi
[00:52:17] cái gì đó đúng không ạ là sửa nhé này đi
[00:52:17] cái gì đó đúng không ạ là sửa nhé này đi thì hôm trước có bạn cũng hỏi mình cái
[00:52:20] thì hôm trước có bạn cũng hỏi mình cái
[00:52:20] thì hôm trước có bạn cũng hỏi mình cái vụ Tại sao các bạn in ra không được để
[00:52:22] vụ Tại sao các bạn in ra không được để
[00:52:22] vụ Tại sao các bạn in ra không được để mình giải thích các bạn dịch vụ này
[00:52:25] mình giải thích các bạn dịch vụ này
[00:52:25] mình giải thích các bạn dịch vụ này chưa bao giờ sử mình nhập tháng 10 năm
[00:52:27] chưa bao giờ sử mình nhập tháng 10 năm
[00:52:27] chưa bao giờ sử mình nhập tháng 10 năm nữa không ạ
[00:52:34] à à
[00:52:34] à à à à
[00:52:35] à à
[00:52:35] à à Em
[00:52:36] Em
[00:52:36] Em in both tháng
[00:52:50] à à
[00:52:50] à à khi
[00:52:56] cha Xóa cái này thôi
[00:52:56] cha Xóa cái này thôi Tháng này
[00:52:59] Tháng này
[00:52:59] Tháng này Đây là
[00:53:01] Đây là
[00:53:01] Đây là em
[00:53:02] em
[00:53:03] em kiểm tra xem có tối đa
[00:53:07] kiểm tra xem có tối đa
[00:53:07] kiểm tra xem có tối đa bao nhiêu ngày
[00:53:10] bao nhiêu ngày
[00:53:10] bao nhiêu ngày ăn chơi ạ ạ
[00:53:13] ăn chơi ạ ạ
[00:53:13] ăn chơi ạ ạ Ừ
[00:53:14] Ừ
[00:53:14] Ừ Thì bây giờ mình sẽ xuất Cai đúng không
[00:53:17] Thì bây giờ mình sẽ xuất Cai đúng không
[00:53:17] Thì bây giờ mình sẽ xuất Cai đúng không ạ Các bạn hôm trước nhở vụ xích Tây rồi
[00:53:19] ạ Các bạn hôm trước nhở vụ xích Tây rồi
[00:53:19] ạ Các bạn hôm trước nhở vụ xích Tây rồi mình sẽ So sánh Nếu mà tháng 1 xong rồi
[00:53:23] mình sẽ So sánh Nếu mà tháng 1 xong rồi
[00:53:23] mình sẽ So sánh Nếu mà tháng 1 xong rồi tháng 3 tháng 5 7 8
[00:53:34] top 10 12 thì mình sẽ cho
[00:53:34] top 10 12 thì mình sẽ cho mình sẽ phải báo trước ở đây Tết này như
[00:53:38] mình sẽ phải báo trước ở đây Tết này như
[00:53:38] mình sẽ phải báo trước ở đây Tết này như này đi và mình sẽ cho ngày bằng 31
[00:53:42] này đi và mình sẽ cho ngày bằng 31
[00:53:42] này đi và mình sẽ cho ngày bằng 31 subject như thế này
[00:53:44] subject như thế này
[00:53:44] subject như thế này tương tự Thế chị sẽ có là
[00:53:48] tương tự Thế chị sẽ có là
[00:53:48] tương tự Thế chị sẽ có là a46
[00:53:55] 29 11 Đông ạ
[00:53:55] 29 11 Đông ạ đi xe 30 ngày
[00:53:57] đi xe 30 ngày
[00:53:57] đi xe 30 ngày ạ sau đó thì cay 2 thì mình sẽ có đoạn
[00:54:02] ạ sau đó thì cay 2 thì mình sẽ có đoạn
[00:54:02] ạ sau đó thì cay 2 thì mình sẽ có đoạn điệp khúc gì đó
[00:54:03] điệp khúc gì đó
[00:54:03] điệp khúc gì đó anh hỏi mình lười có cái đoạn này quá
[00:54:06] anh hỏi mình lười có cái đoạn này quá
[00:54:06] anh hỏi mình lười có cái đoạn này quá cho bỏ qua đi mặc định bằng 28 đi sự thế
[00:54:09] cho bỏ qua đi mặc định bằng 28 đi sự thế
[00:54:09] cho bỏ qua đi mặc định bằng 28 đi sự thế không ạ Black từ đây những lần này mình
[00:54:12] không ạ Black từ đây những lần này mình
[00:54:12] không ạ Black từ đây những lần này mình sẽ cho một cái phô đi và khi mình nhập
[00:54:14] sẽ cho một cái phô đi và khi mình nhập
[00:54:14] sẽ cho một cái phô đi và khi mình nhập sai chọn Vân Vân đó sẽ là cậu này bằng
[00:54:19] sai chọn Vân Vân đó sẽ là cậu này bằng
[00:54:19] sai chọn Vân Vân đó sẽ là cậu này bằng sai cả đại khái như thế sau nhà mình sẽ
[00:54:24] sai cả đại khái như thế sau nhà mình sẽ
[00:54:24] sai cả đại khái như thế sau nhà mình sẽ cho comment
[00:54:27] cho comment
[00:54:27] cho comment chấm chemin body kết quả này
[00:54:31] chấm chemin body kết quả này
[00:54:31] chấm chemin body kết quả này chấm innerhtml bằng
[00:54:35] chấm innerhtml bằng
[00:54:35] chấm innerhtml bằng số này là hai chấm này
[00:54:39] số này là hai chấm này
[00:54:39] số này là hai chấm này a cộng với ngày này chẳng hạn như này
[00:54:42] a cộng với ngày này chẳng hạn như này
[00:54:42] a cộng với ngày này chẳng hạn như này không ạ chạy thử nhé
[00:54:45] không ạ chạy thử nhé
[00:54:45] không ạ chạy thử nhé Cô thích gà nếu như này mình bỏ qua năm
[00:54:48] Cô thích gà nếu như này mình bỏ qua năm
[00:54:48] Cô thích gà nếu như này mình bỏ qua năm với Chán không cần quan tâm năm đó lại
[00:54:50] với Chán không cần quan tâm năm đó lại
[00:54:50] với Chán không cần quan tâm năm đó lại khá như thế Bấm này xuống này là sai đấy
[00:54:54] khá như thế Bấm này xuống này là sai đấy
[00:54:54] khá như thế Bấm này xuống này là sai đấy hai số này vẫn là sai một số loại vẫn là
[00:54:58] hai số này vẫn là sai một số loại vẫn là
[00:54:58] hai số này vẫn là sai một số loại vẫn là sai này Tại sao lại vẫn vẫn là sai
[00:55:03] sai này Tại sao lại vẫn vẫn là sai
[00:55:03] sai này Tại sao lại vẫn vẫn là sai Ừ
[00:55:05] Ừ
[00:55:05] Ừ cái quan trọng ở đây là sai là đúng sai
[00:55:10] cái quan trọng ở đây là sai là đúng sai
[00:55:10] cái quan trọng ở đây là sai là đúng sai là đúng Tại sao bởi vì à Cái Khánh này
[00:55:12] là đúng Tại sao bởi vì à Cái Khánh này
[00:55:12] là đúng Tại sao bởi vì à Cái Khánh này nó lấy về nó đang là chuỗi không phải là
[00:55:18] nó lấy về nó đang là chuỗi không phải là
[00:55:18] nó lấy về nó đang là chuỗi không phải là số các bạn nó sau sàng lòng với số chứ
[00:55:20] số các bạn nó sau sàng lòng với số chứ
[00:55:20] số các bạn nó sau sàng lòng với số chứ sao nó sai được bên mình chưa đổi nó ra
[00:55:22] sao nó sai được bên mình chưa đổi nó ra
[00:55:22] sao nó sai được bên mình chưa đổi nó ra là Trỗi ngay nhá cho mình nhập lại số 1
[00:55:25] là Trỗi ngay nhá cho mình nhập lại số 1
[00:55:25] là Trỗi ngay nhá cho mình nhập lại số 1 đấy đó các bạn thấy là nó đang so sánh ở
[00:55:29] đấy đó các bạn thấy là nó đang so sánh ở
[00:55:29] đấy đó các bạn thấy là nó đang so sánh ở đây nó sẽ khác với cái so sánh mà mình
[00:55:32] đây nó sẽ khác với cái so sánh mà mình
[00:55:32] đây nó sẽ khác với cái so sánh mà mình mình mới dậy các bạn mới dậy các bạn thì
[00:55:34] mình mới dậy các bạn mới dậy các bạn thì
[00:55:34] mình mới dậy các bạn mới dậy các bạn thì mình mới chị So sánh các bạn về việc là
[00:55:36] mình mới chị So sánh các bạn về việc là
[00:55:36] mình mới chị So sánh các bạn về việc là bằng Bằng nghe vậy thôi Băng Băng như
[00:55:39] bằng Bằng nghe vậy thôi Băng Băng như
[00:55:39] bằng Bằng nghe vậy thôi Băng Băng như thế này tức là giá trị đâu nhau thôi ra
[00:55:41] thế này tức là giá trị đâu nhau thôi ra
[00:55:41] thế này tức là giá trị đâu nhau thôi ra sửa đây mình sẽ trải nghiệm là ba bằng
[00:55:45] sửa đây mình sẽ trải nghiệm là ba bằng
[00:55:45] sửa đây mình sẽ trải nghiệm là ba bằng bằng bằng 3 đương nhiên các bạn thấy ở
[00:55:47] bằng bằng 3 đương nhiên các bạn thấy ở
[00:55:47] bằng bằng 3 đương nhiên các bạn thấy ở đây nó sẽ là Chu tất cả là đúng đúng ạ
[00:55:51] đây nó sẽ là Chu tất cả là đúng đúng ạ
[00:55:51] đây nó sẽ là Chu tất cả là đúng đúng ạ Nhưng mà nếu trong trường hợp 3 bằng
[00:55:55] Nhưng mà nếu trong trường hợp 3 bằng
[00:55:55] Nhưng mà nếu trong trường hợp 3 bằng bằng chuỗi 3 như này thì ở chùa Côn ạ
[00:56:00] bằng chuỗi 3 như này thì ở chùa Côn ạ
[00:56:00] bằng chuỗi 3 như này thì ở chùa Côn ạ thế này hỏi qua một tí mấy ông trả lời
[00:56:02] thế này hỏi qua một tí mấy ông trả lời
[00:56:02] thế này hỏi qua một tí mấy ông trả lời nhanh cho tôi mấy câu này
[00:56:08] D3 bằng bằng chuỗi 3 thì nó là chuông
[00:56:08] D3 bằng bằng chuỗi 3 thì nó là chuông iPhone
[00:56:18] Ừ ông kia iPhone còn ghi sai như thế này
[00:56:18] Ừ ông kia iPhone còn ghi sai như thế này đậu xanh
[00:56:19] đậu xanh
[00:56:19] đậu xanh ừ ừ
[00:56:21] ừ ừ
[00:56:21] ừ ừ thì
[00:56:22] thì
[00:56:22] thì nó vẫn là Chu thôi nó vẫn là Chu nó vẫn
[00:56:26] nó vẫn là Chu thôi nó vẫn là Chu nó vẫn
[00:56:26] nó vẫn là Chu thôi nó vẫn là Chu nó vẫn đúng cái bằng bằng này nó chỉ so sánh
[00:56:30] đúng cái bằng bằng này nó chỉ so sánh
[00:56:30] đúng cái bằng bằng này nó chỉ so sánh giá trị giá trị của nó hai cái đối với
[00:56:34] giá trị giá trị của nó hai cái đối với
[00:56:34] giá trị giá trị của nó hai cái đối với máy tính giá trị nó bằng nhau đều bằng 3
[00:56:36] máy tính giá trị nó bằng nhau đều bằng 3
[00:56:36] máy tính giá trị nó bằng nhau đều bằng 3 cả nó sẽ đều biến lại thành bằng ba gác
[00:56:39] cả nó sẽ đều biến lại thành bằng ba gác
[00:56:39] cả nó sẽ đều biến lại thành bằng ba gác bây giờ chính vì như thế thì nên mới có
[00:56:44] bây giờ chính vì như thế thì nên mới có
[00:56:44] bây giờ chính vì như thế thì nên mới có so sánh kiểu như thế này mới là phô này
[00:56:48] so sánh kiểu như thế này mới là phô này
[00:56:48] so sánh kiểu như thế này mới là phô này đấy
[00:56:50] đấy
[00:56:50] đấy ý nghĩa là khi so sánh như này thì thì
[00:56:55] ý nghĩa là khi so sánh như này thì thì
[00:56:55] ý nghĩa là khi so sánh như này thì thì nó sẽ So sánh kết hợp với các kiểu giá
[00:56:57] nó sẽ So sánh kết hợp với các kiểu giá
[00:56:57] nó sẽ So sánh kết hợp với các kiểu giá trị nữa
[00:56:59] trị nữa
[00:56:59] trị nữa cái trong trường hợp này thì kệ 3 3G
[00:57:02] cái trong trường hợp này thì kệ 3 3G
[00:57:02] cái trong trường hợp này thì kệ 3 3G băng này để mà ám chỉ lại phải giống hệt
[00:57:05] băng này để mà ám chỉ lại phải giống hệt
[00:57:05] băng này để mà ám chỉ lại phải giống hệt nhau nghĩa là chỉ có trường hợp mà
[00:57:08] nhau nghĩa là chỉ có trường hợp mà
[00:57:08] nhau nghĩa là chỉ có trường hợp mà anh giống hệt nhau theo kiểu như này nó
[00:57:11] anh giống hệt nhau theo kiểu như này nó
[00:57:11] anh giống hệt nhau theo kiểu như này nó mới đúng này điều ạ thế này nói đúng rồi
[00:57:14] mới đúng này điều ạ thế này nói đúng rồi
[00:57:14] mới đúng này điều ạ thế này nói đúng rồi còn nếu mà so sánh nó với kiểu giá trị
[00:57:16] còn nếu mà so sánh nó với kiểu giá trị
[00:57:16] còn nếu mà so sánh nó với kiểu giá trị khác kiểu giờ chị chuỗi như thế này nó
[00:57:18] khác kiểu giờ chị chuỗi như thế này nó
[00:57:18] khác kiểu giờ chị chuỗi như thế này nó cho chắn sẽ lỗi
[00:57:21] cho chắn sẽ lỗi
[00:57:21] cho chắn sẽ lỗi thì nó sẽ biến thành phone không ạ Thi
[00:57:24] thì nó sẽ biến thành phone không ạ Thi
[00:57:24] thì nó sẽ biến thành phone không ạ Thi Thế nên mới có vụ ở đây đó là cái xích
[00:57:27] Thế nên mới có vụ ở đây đó là cái xích
[00:57:27] Thế nên mới có vụ ở đây đó là cái xích cây này nó so sánh không phải bằng hai
[00:57:30] cây này nó so sánh không phải bằng hai
[00:57:30] cây này nó so sánh không phải bằng hai dấu bằng mà nói so sánh bằng ba dấu bằng
[00:57:33] dấu bằng mà nói so sánh bằng ba dấu bằng
[00:57:33] dấu bằng mà nói so sánh bằng ba dấu bằng nên là cái tháng này đang là chuỗi khi
[00:57:36] nên là cái tháng này đang là chuỗi khi
[00:57:36] nên là cái tháng này đang là chuỗi khi mà còn nhập vào kể cả các bạn để thay nó
[00:57:38] mà còn nhập vào kể cả các bạn để thay nó
[00:57:38] mà còn nhập vào kể cả các bạn để thay nó nằm bờ nhưng mà ra sức hút không hiểu
[00:57:40] nằm bờ nhưng mà ra sức hút không hiểu
[00:57:40] nằm bờ nhưng mà ra sức hút không hiểu đâu Nó vẫn sẽ hiểu cái tháng này là
[00:57:43] đâu Nó vẫn sẽ hiểu cái tháng này là
[00:57:43] đâu Nó vẫn sẽ hiểu cái tháng này là chuỗi nên nó so sánh 3 giờ bằng với tất
[00:57:47] chuỗi nên nó so sánh 3 giờ bằng với tất
[00:57:47] chuỗi nên nó so sánh 3 giờ bằng với tất cả mấy cái trường hợp này thì hướng
[00:57:48] cả mấy cái trường hợp này thì hướng
[00:57:48] cả mấy cái trường hợp này thì hướng nghĩa là nó sẽ không thỏa mãn mà nhảy
[00:57:51] nghĩa là nó sẽ không thỏa mãn mà nhảy
[00:57:51] nghĩa là nó sẽ không thỏa mãn mà nhảy vào Cái phô rồi không ạ Các bạn thấy nó
[00:57:53] vào Cái phô rồi không ạ Các bạn thấy nó
[00:57:53] vào Cái phô rồi không ạ Các bạn thấy nó đang nhảy vào đây phô như này thành biến
[00:57:57] đang nhảy vào đây phô như này thành biến
[00:57:57] đang nhảy vào đây phô như này thành biến thì sai hết đúng không ạ thì bây giờ
[00:57:59] thì sai hết đúng không ạ thì bây giờ
[00:57:59] thì sai hết đúng không ạ thì bây giờ trong trường hợp này thì mình nếu mà 1
[00:58:02] trong trường hợp này thì mình nếu mà 1
[00:58:02] trong trường hợp này thì mình nếu mà 1 số 1 là bạn sẽ phải cho toàn bộ Cái này
[00:58:06] số 1 là bạn sẽ phải cho toàn bộ Cái này
[00:58:06] số 1 là bạn sẽ phải cho toàn bộ Cái này thành Trỗi người gà cái kiểu như thế thì
[00:58:09] thành Trỗi người gà cái kiểu như thế thì
[00:58:09] thành Trỗi người gà cái kiểu như thế thì không không nên làm lắm mà vì nó không
[00:58:11] không không nên làm lắm mà vì nó không
[00:58:11] không không nên làm lắm mà vì nó không có vẻ nghe nghe có vẻ không hợp lôgích
[00:58:14] có vẻ nghe nghe có vẻ không hợp lôgích
[00:58:14] có vẻ nghe nghe có vẻ không hợp lôgích làm đúng không ạ
[00:58:15] làm đúng không ạ
[00:58:15] làm đúng không ạ Cách thứ hai là các bạn sẽ phải hết cái
[00:58:18] Cách thứ hai là các bạn sẽ phải hết cái
[00:58:18] Cách thứ hai là các bạn sẽ phải hết cái chỗ này thành số nó sẽ phạt như thế này
[00:58:23] chỗ này thành số nó sẽ phạt như thế này
[00:58:23] chỗ này thành số nó sẽ phạt như thế này in thế này
[00:58:25] in thế này
[00:58:25] in thế này ở đây nó sẽ có 2 cách để mà ép một cái
[00:58:29] ở đây nó sẽ có 2 cách để mà ép một cái
[00:58:29] ở đây nó sẽ có 2 cách để mà ép một cái lại fast in 2 carapace Plus ca sĩ lf nó
[00:58:35] lại fast in 2 carapace Plus ca sĩ lf nó
[00:58:35] lại fast in 2 carapace Plus ca sĩ lf nó hàng số nguyên và tạt flash thì em nói
[00:58:37] hàng số nguyên và tạt flash thì em nói
[00:58:37] hàng số nguyên và tạt flash thì em nói anh số thực đương nhiên là nếu là số
[00:58:39] anh số thực đương nhiên là nếu là số
[00:58:39] anh số thực đương nhiên là nếu là số nguyên thì bà flash thì nó vẫn thành số
[00:58:41] nguyên thì bà flash thì nó vẫn thành số
[00:58:41] nguyên thì bà flash thì nó vẫn thành số nguyên khối với nó sống yên mà bọn nó
[00:58:46] nguyên khối với nó sống yên mà bọn nó
[00:58:46] nguyên khối với nó sống yên mà bọn nó không có thêm phẩy làm sao đâu ạ
[00:58:49] không có thêm phẩy làm sao đâu ạ
[00:58:49] không có thêm phẩy làm sao đâu ạ đi đái nếu mà ông làm như thế này nó mới
[00:58:51] đi đái nếu mà ông làm như thế này nó mới
[00:58:51] đi đái nếu mà ông làm như thế này nó mới đúng đấy
[00:58:52] đúng đấy
[00:58:52] đúng đấy một này đó đưa đúng đấy đây giải thích
[00:58:58] một này đó đưa đúng đấy đây giải thích
[00:58:58] một này đó đưa đúng đấy đây giải thích cho bạn nào hôm trước bạn bởi vì hôm
[00:59:01] cho bạn nào hôm trước bạn bởi vì hôm
[00:59:01] cho bạn nào hôm trước bạn bởi vì hôm trước mình mình bảo các bạn làm bài về
[00:59:03] trước mình mình bảo các bạn làm bài về
[00:59:03] trước mình mình bảo các bạn làm bài về nhà ấy thì các bạn chỉ cần làm đã ra
[00:59:06] nhà ấy thì các bạn chỉ cần làm đã ra
[00:59:06] nhà ấy thì các bạn chỉ cần làm đã ra Swift thôi các bạn không cần làm own
[00:59:07] Swift thôi các bạn không cần làm own
[00:59:07] Swift thôi các bạn không cần làm own food ngay như hôm trước có bạn cũng ngồi
[00:59:10] food ngay như hôm trước có bạn cũng ngồi
[00:59:10] food ngay như hôm trước có bạn cũng ngồi làm à Ôi nút như này xong rồi bạn dùng
[00:59:12] làm à Ôi nút như này xong rồi bạn dùng
[00:59:12] làm à Ôi nút như này xong rồi bạn dùng xích cây bạn đấy bảo là chẳng in ra cái
[00:59:15] xích cây bạn đấy bảo là chẳng in ra cái
[00:59:15] xích cây bạn đấy bảo là chẳng in ra cái gì cả đúng mặt của vì rõ ràng là bạn đấy
[00:59:18] gì cả đúng mặt của vì rõ ràng là bạn đấy
[00:59:18] gì cả đúng mặt của vì rõ ràng là bạn đấy chưa hiểu về cái cơ chế in bút là nhập
[00:59:21] chưa hiểu về cái cơ chế in bút là nhập
[00:59:21] chưa hiểu về cái cơ chế in bút là nhập vào là chuỗi thì bạn sao sàng xích cây
[00:59:24] vào là chuỗi thì bạn sao sàng xích cây
[00:59:24] vào là chuỗi thì bạn sao sàng xích cây Chắc chắn là nó chẳng ra cái quả gì cả
[00:59:26] Chắc chắn là nó chẳng ra cái quả gì cả
[00:59:26] Chắc chắn là nó chẳng ra cái quả gì cả nó chẳng ở cây nào bạn đây cũng không
[00:59:28] nó chẳng ở cây nào bạn đây cũng không
[00:59:28] nó chẳng ở cây nào bạn đây cũng không cho bé iPhone luôn bạn nghĩ là cô chứ
[00:59:30] cho bé iPhone luôn bạn nghĩ là cô chứ
[00:59:30] cho bé iPhone luôn bạn nghĩ là cô chứ chả ngon luôn Chạy không Giờ có chuyện
[00:59:33] chả ngon luôn Chạy không Giờ có chuyện
[00:59:33] chả ngon luôn Chạy không Giờ có chuyện đấy phô thành ra là không in gì cả Không
[00:59:36] đấy phô thành ra là không in gì cả Không
[00:59:36] đấy phô thành ra là không in gì cả Không ạ à Thế à Giờ Rồi ạ ạ
[00:59:40] ạ à Thế à Giờ Rồi ạ ạ
[00:59:40] ạ à Thế à Giờ Rồi ạ ạ ở đây là con người chưa chải đấy
[00:59:44] ở đây là con người chưa chải đấy
[00:59:44] ở đây là con người chưa chải đấy khi con người chạy rồi luôn phải có cái
[00:59:47] khi con người chạy rồi luôn phải có cái
[00:59:47] khi con người chạy rồi luôn phải có cái địa phủ để biết được lúc nào mình sai
[00:59:49] địa phủ để biết được lúc nào mình sai
[00:59:49] địa phủ để biết được lúc nào mình sai không ạ Giống kiện trai các thôi à
[00:59:57] có mấy cái vụ mà có bạn đang ngồi đùa
[00:59:57] có mấy cái vụ mà có bạn đang ngồi đùa Cái vụ mà cộng xong rồi - như kia mình
[01:00:01] Cái vụ mà cộng xong rồi - như kia mình
[01:00:01] Cái vụ mà cộng xong rồi - như kia mình sẽ thử bạn ấy đang
[01:00:04] sẽ thử bạn ấy đang
[01:00:04] sẽ thử bạn ấy đang ờ ờ
[01:00:05] ờ ờ
[01:00:05] ờ ờ anh đi đây
[01:00:08] anh đi đây
[01:00:08] anh đi đây Ừ để tối nay gọi cho mấy ông thứ là mấy
[01:00:12] Ừ để tối nay gọi cho mấy ông thứ là mấy
[01:00:12] Ừ để tối nay gọi cho mấy ông thứ là mấy ông Nếu mà Mấy ông để trĩ hôm trước tôi
[01:00:15] ông Nếu mà Mấy ông để trĩ hôm trước tôi
[01:00:15] ông Nếu mà Mấy ông để trĩ hôm trước tôi hỏi mấy cái bài tập ở trên à à
[01:00:19] hỏi mấy cái bài tập ở trên à à
[01:00:19] hỏi mấy cái bài tập ở trên à à 3 cách để bồi
[01:00:20] 3 cách để bồi
[01:00:20] 3 cách để bồi Ừ thì à
[01:00:23] Ừ thì à
[01:00:23] Ừ thì à Ừ Thì Thôi ca làm mấy ông đã có thể
[01:00:26] Ừ Thì Thôi ca làm mấy ông đã có thể
[01:00:26] Ừ Thì Thôi ca làm mấy ông đã có thể kopkop luôn cả cái cốt ở trên Tách cái
[01:00:29] kopkop luôn cả cái cốt ở trên Tách cái
[01:00:29] kopkop luôn cả cái cốt ở trên Tách cái bồ đấy để mấy ông chạy được ở trên trình
[01:00:31] bồ đấy để mấy ông chạy được ở trên trình
[01:00:31] bồ đấy để mấy ông chạy được ở trên trình duyệt luôn thử cho mình xem nhé Mấy ông
[01:00:34] duyệt luôn thử cho mình xem nhé Mấy ông
[01:00:34] duyệt luôn thử cho mình xem nhé Mấy ông inspect này
[01:00:43] ở nhà Ông mở con sôi lên này đã chạy
[01:00:43] ở nhà Ông mở con sôi lên này đã chạy được luôn này à
[01:00:45] được luôn này à
[01:00:45] được luôn này à ở Facebook thích để cùng tôi vào trong
[01:00:49] ở Facebook thích để cùng tôi vào trong
[01:00:49] ở Facebook thích để cùng tôi vào trong trình các bài tập của tôi cho mấy ông
[01:00:51] trình các bài tập của tôi cho mấy ông
[01:00:51] trình các bài tập của tôi cho mấy ông chạy Thượng
[01:01:06] Ừ cái tặng Trời Sài sai không có tâm
[01:01:06] Ừ cái tặng Trời Sài sai không có tâm không
[01:01:22] Ừ hình như là riêng ông trường hợp Đúng
[01:01:22] Ừ hình như là riêng ông trường hợp Đúng là trường hợp sai nó phản hồi lâu hơn
[01:01:25] là trường hợp sai nó phản hồi lâu hơn
[01:01:25] là trường hợp sai nó phản hồi lâu hơn thế bạn
[01:01:35] à à
[01:01:35] à à ở đó chú chú ngon không ạ
[01:01:44] vì có cô tiên
[01:01:44] vì có cô tiên phone Ok Phone
[01:01:47] phone Ok Phone
[01:01:47] phone Ok Phone chị đã đúng không nó cũng phải làm như
[01:01:50] chị đã đúng không nó cũng phải làm như
[01:01:50] chị đã đúng không nó cũng phải làm như thế này mà
[01:01:56] Có thai mấy ông cậu cối Gõ lại hoặc mấy
[01:01:56] Có thai mấy ông cậu cối Gõ lại hoặc mấy ông ngồi đoán xem cốc đấy như nào đấy
[01:01:59] ông ngồi đoán xem cốc đấy như nào đấy
[01:01:59] ông ngồi đoán xem cốc đấy như nào đấy mẹo thôi Tôi vừa tự dùng chính bài tập
[01:02:02] mẹo thôi Tôi vừa tự dùng chính bài tập
[01:02:02] mẹo thôi Tôi vừa tự dùng chính bài tập của tôi thì em ạ
[01:02:04] của tôi thì em ạ
[01:02:04] của tôi thì em ạ ở ngọn nhà con nách chính mày Thuận dạy
[01:02:08] ở ngọn nhà con nách chính mày Thuận dạy
[01:02:08] ở ngọn nhà con nách chính mày Thuận dạy cách lách trên bài tập của mình à
[01:02:18] Ừ thì nói chung là tôi vừa dậy các bạn
[01:02:18] Ừ thì nói chung là tôi vừa dậy các bạn về việc là
[01:02:20] về việc là
[01:02:20] về việc là dùng ra Speed chạy được như thế nào ở
[01:02:22] dùng ra Speed chạy được như thế nào ở
[01:02:22] dùng ra Speed chạy được như thế nào ở trên chính trình duyệt đó ngọn cái con
[01:02:25] trên chính trình duyệt đó ngọn cái con
[01:02:25] trên chính trình duyệt đó ngọn cái con xô này nó cái để chạy ra suýt mà mà để
[01:02:27] xô này nó cái để chạy ra suýt mà mà để
[01:02:27] xô này nó cái để chạy ra suýt mà mà để hiển thị lỗi nếu mà ra Switch của j sai
[01:02:29] hiển thị lỗi nếu mà ra Switch của j sai
[01:02:29] hiển thị lỗi nếu mà ra Switch của j sai nữa
[01:02:30] nữa
[01:02:30] nữa thì tiếp theo là
[01:02:33] thì tiếp theo là
[01:02:33] thì tiếp theo là gì tương tự Thế vừa rồi có bạn tranh thủ
[01:02:36] gì tương tự Thế vừa rồi có bạn tranh thủ
[01:02:36] gì tương tự Thế vừa rồi có bạn tranh thủ nói luôn về cái vụ là cái vụ ra Swift nó
[01:02:40] nói luôn về cái vụ là cái vụ ra Swift nó
[01:02:40] nói luôn về cái vụ là cái vụ ra Swift nó bị yếu yếu về cái kiểu kiểu dữ liệu của
[01:02:45] bị yếu yếu về cái kiểu kiểu dữ liệu của
[01:02:45] bị yếu yếu về cái kiểu kiểu dữ liệu của nó tất cả chỗ nào có thể nhảy sang số
[01:02:47] nó tất cả chỗ nào có thể nhảy sang số
[01:02:47] nó tất cả chỗ nào có thể nhảy sang số cũng như ngược lại các bạn không để ý kĩ
[01:02:50] cũng như ngược lại các bạn không để ý kĩ
[01:02:50] cũng như ngược lại các bạn không để ý kĩ là rõ ràng xuống ngày ở đây nó đang là
[01:02:54] là rõ ràng xuống ngày ở đây nó đang là
[01:02:54] là rõ ràng xuống ngày ở đây nó đang là số à đúng không ạ Các bạn ý kỹ không ạ
[01:02:56] số à đúng không ạ Các bạn ý kỹ không ạ
[01:02:56] số à đúng không ạ Các bạn ý kỹ không ạ gỡ ra là tôi đang dạy mấy ông là cây
[01:03:02] gỡ ra là tôi đang dạy mấy ông là cây
[01:03:02] gỡ ra là tôi đang dạy mấy ông là cây từ cách đây xuống ngày của tôi đang ở số
[01:03:05] từ cách đây xuống ngày của tôi đang ở số
[01:03:05] từ cách đây xuống ngày của tôi đang ở số màn không ạ Xuống ngày 31 Mà tại sao nó
[01:03:09] màn không ạ Xuống ngày 31 Mà tại sao nó
[01:03:09] màn không ạ Xuống ngày 31 Mà tại sao nó có thể nối với cái chuỗi để in ra thành
[01:03:12] có thể nối với cái chuỗi để in ra thành
[01:03:12] có thể nối với cái chuỗi để in ra thành 31 được đúng ạ
[01:03:19] ngõ ra và cái này đang hết nó thành
[01:03:19] ngõ ra và cái này đang hết nó thành chuỗi rồi cậu nó được với nhau đúng ạ và
[01:03:22] chuỗi rồi cậu nó được với nhau đúng ạ và
[01:03:22] chuỗi rồi cậu nó được với nhau đúng ạ và Chính vì cái việc nó tiện tiện nhé cũng
[01:03:26] Chính vì cái việc nó tiện tiện nhé cũng
[01:03:26] Chính vì cái việc nó tiện tiện nhé cũng là bất tiện theo kiểu là nó sinh ra
[01:03:29] là bất tiện theo kiểu là nó sinh ra
[01:03:29] là bất tiện theo kiểu là nó sinh ra những cái lỗi rất là dị trả Sự giống như
[01:03:31] những cái lỗi rất là dị trả Sự giống như
[01:03:31] những cái lỗi rất là dị trả Sự giống như là thế này có ông vừa nói ở ở kia hội
[01:03:36] là thế này có ông vừa nói ở ở kia hội
[01:03:36] là thế này có ông vừa nói ở ở kia hội nhưng tôi vẫn thích nó lại ai giờ sửa à
[01:03:38] nhưng tôi vẫn thích nó lại ai giờ sửa à
[01:03:38] nhưng tôi vẫn thích nó lại ai giờ sửa à ngắm trường hợp 3
[01:03:40] ngắm trường hợp 3
[01:03:40] ngắm trường hợp 3 cộng với chuỗi 3 thì nó lại ra thành 33
[01:03:44] cộng với chuỗi 3 thì nó lại ra thành 33
[01:03:44] cộng với chuỗi 3 thì nó lại ra thành 33 trắng ạ
[01:03:45] trắng ạ
[01:03:45] trắng ạ Anh đấy xong lại - 3 thìa sẽ 30 ạ
[01:03:52] Anh đấy xong lại - 3 thìa sẽ 30 ạ
[01:03:52] Anh đấy xong lại - 3 thìa sẽ 30 ạ Ừ đúng ạ nhưng mà - như này nó vẫn sẽ là
[01:03:56] Ừ đúng ạ nhưng mà - như này nó vẫn sẽ là
[01:03:56] Ừ đúng ạ nhưng mà - như này nó vẫn sẽ là 30 ạ
[01:04:05] Ừ đúng ạ Nhưng mà nếu mà 3 - Trỗi 3 rồi
[01:04:05] Ừ đúng ạ Nhưng mà nếu mà 3 - Trỗi 3 rồi cộng với 3 như này
[01:04:09] cộng với 3 như này
[01:04:09] cộng với 3 như này gì đấy
[01:04:10] gì đấy
[01:04:10] gì đấy hai thí mấy ông sẽ Cậu thấy nó sẽ
[01:04:14] hai thí mấy ông sẽ Cậu thấy nó sẽ
[01:04:14] hai thí mấy ông sẽ Cậu thấy nó sẽ quan trọng về quan trọng thứ nhất là
[01:04:17] quan trọng về quan trọng thứ nhất là
[01:04:17] quan trọng về quan trọng thứ nhất là việc Ép kiểu cho nó
[01:04:26] và cả thứ tự của cái chạy nữa không thì
[01:04:26] và cả thứ tự của cái chạy nữa không thì nó sẽ là
[01:04:28] nó sẽ là
[01:04:28] nó sẽ là thì rõ ràng là cái này nó khác với cái
[01:04:32] thì rõ ràng là cái này nó khác với cái
[01:04:32] thì rõ ràng là cái này nó khác với cái khi cây kế toán mình đừng học cái mà đổi
[01:04:35] khi cây kế toán mình đừng học cái mà đổi
[01:04:35] khi cây kế toán mình đừng học cái mà đổi chỗ cho nhau là khoán vị đã làm cái gì
[01:04:37] chỗ cho nhau là khoán vị đã làm cái gì
[01:04:37] chỗ cho nhau là khoán vị đã làm cái gì đấy nhưng mà ông chỉ việc đổi chỗ số cho
[01:04:40] đấy nhưng mà ông chỉ việc đổi chỗ số cho
[01:04:40] đấy nhưng mà ông chỉ việc đổi chỗ số cho nhau tự nhiên thấy giá trị có thay đổi
[01:04:41] nhau tự nhiên thấy giá trị có thay đổi
[01:04:41] nhau tự nhiên thấy giá trị có thay đổi hẳn như thế này đúng không ạ
[01:04:43] hẳn như thế này đúng không ạ
[01:04:43] hẳn như thế này đúng không ạ Ừ thì nó Lũng Nhai
[01:04:47] Ừ thì nó Lũng Nhai
[01:04:47] Ừ thì nó Lũng Nhai cha mẹ ông hiểu gì tôi đang muốn nó ạ
[01:04:58] ở lại và đây mà ông thấy đang lũ thì tôi
[01:04:58] ở lại và đây mà ông thấy đang lũ thì tôi xin phép cho mày không lúa thẳng qua
[01:05:00] xin phép cho mày không lúa thẳng qua
[01:05:00] xin phép cho mày không lúa thẳng qua những cái ảnh này tôi mới tải về
[01:05:09] số bài toán toán học ở trong g switch
[01:05:09] số bài toán toán học ở trong g switch ở đây
[01:05:10] ở đây
[01:05:10] ở đây số xổ chuỗi 5 - 3 = 2 này nếu mà chửi
[01:05:15] số xổ chuỗi 5 - 3 = 2 này nếu mà chửi
[01:05:15] số xổ chuỗi 5 - 3 = 2 này nếu mà chửi năm cộng 13 thì bằng 33 này
[01:05:18] năm cộng 13 thì bằng 33 này
[01:05:18] năm cộng 13 thì bằng 33 này một chuỗi 5 - chuỗi 4 thì bằng một này
[01:05:29] ý nghĩa hàm chỉ ta lúc lúc vì nó là
[01:05:29] ý nghĩa hàm chỉ ta lúc lúc vì nó là đề tài - nó
[01:05:32] đề tài - nó
[01:05:33] đề tài - nó ở bảng - cả chuỗi với chuỗi nó lại ra số
[01:05:37] ở bảng - cả chuỗi với chuỗi nó lại ra số
[01:05:37] ở bảng - cả chuỗi với chuỗi nó lại ra số đúng ạ
[01:05:38] đúng ạ
[01:05:38] đúng ạ một chuỗi - về số uống thì nó ra số rồi
[01:05:41] một chuỗi - về số uống thì nó ra số rồi
[01:05:41] một chuỗi - về số uống thì nó ra số rồi Chỗ ấy với chuỗi lòng ra số này nhưng mà
[01:05:44] Chỗ ấy với chuỗi lòng ra số này nhưng mà
[01:05:44] Chỗ ấy với chuỗi lòng ra số này nhưng mà chuỗi cộng với chuỗi thì nó lại ra chỗ
[01:05:46] chuỗi cộng với chuỗi thì nó lại ra chỗ
[01:05:46] chuỗi cộng với chuỗi thì nó lại ra chỗ này đấy
[01:05:52] A1 loa như thế này
[01:05:52] A1 loa như thế này Em hãy cái tôi vừa đề cập này
[01:05:55] Em hãy cái tôi vừa đề cập này
[01:05:55] Em hãy cái tôi vừa đề cập này i5 + - X5 - + X thì nó sẽ 50,5 này đúng
[01:06:01] i5 + - X5 - + X thì nó sẽ 50,5 này đúng
[01:06:01] i5 + - X5 - + X thì nó sẽ 50,5 này đúng ạ ạ
[01:06:09] à à
[01:06:09] à à à à
[01:06:11] à à
[01:06:11] à à cho nên là nếu vào chuẩn là mấy ông sẽ
[01:06:14] cho nên là nếu vào chuẩn là mấy ông sẽ
[01:06:14] cho nên là nếu vào chuẩn là mấy ông sẽ phải ép kiểu hết cho nó thành kiểu số
[01:06:17] phải ép kiểu hết cho nó thành kiểu số
[01:06:17] phải ép kiểu hết cho nó thành kiểu số trước khi cộng trừ nhân chia với nó à
[01:06:20] trước khi cộng trừ nhân chia với nó à
[01:06:20] trước khi cộng trừ nhân chia với nó à nhân chia thì không ra đâu nhẹ nhân chia
[01:06:21] nhân chia thì không ra đâu nhẹ nhân chia
[01:06:21] nhân chia thì không ra đâu nhẹ nhân chia để nó không bị ép ở dưới nó sẽ cho nó số
[01:06:24] để nó không bị ép ở dưới nó sẽ cho nó số
[01:06:24] để nó không bị ép ở dưới nó sẽ cho nó số rồi những hoa còn cộng trừ của nó thì nó
[01:06:26] rồi những hoa còn cộng trừ của nó thì nó
[01:06:26] rồi những hoa còn cộng trừ của nó thì nó sẽ là nó sẽ có khái niệm là auto
[01:06:29] sẽ là nó sẽ có khái niệm là auto
[01:06:29] sẽ là nó sẽ có khái niệm là auto Converse thì ông sẽ biết phải tiện khái
[01:06:31] Converse thì ông sẽ biết phải tiện khái
[01:06:31] Converse thì ông sẽ biết phải tiện khái niệm đấy họ thụ convert và tự động tự
[01:06:34] niệm đấy họ thụ convert và tự động tự
[01:06:34] niệm đấy họ thụ convert và tự động tự động đổi đổi kiểu dữ liệu thì nên là mấy
[01:06:37] động đổi đổi kiểu dữ liệu thì nên là mấy
[01:06:37] động đổi đổi kiểu dữ liệu thì nên là mấy ông phải S chịu cho nó thành số luôn với
[01:06:40] ông phải S chịu cho nó thành số luôn với
[01:06:40] ông phải S chịu cho nó thành số luôn với nhau rồi mới cộng trừ nhân chia cộng trừ
[01:06:43] nhau rồi mới cộng trừ nhân chia cộng trừ
[01:06:43] nhau rồi mới cộng trừ nhân chia cộng trừ với nó đều ạ
[01:06:50] khi con Cả thêm vụ này nữa Cái vụ này
[01:06:50] khi con Cả thêm vụ này nữa Cái vụ này cũng là kiểu dữ liệu của nó nó hơi bị
[01:06:51] cũng là kiểu dữ liệu của nó nó hơi bị
[01:06:51] cũng là kiểu dữ liệu của nó nó hơi bị đau não Lỡ chị ở chỉ nốt
[01:06:55] đau não Lỡ chị ở chỉ nốt
[01:06:55] đau não Lỡ chị ở chỉ nốt ừ ừ
[01:07:03] ờ ờ Nếu mà số mà nó lớn quá nó dễ bị làm
[01:07:03] ờ ờ Nếu mà số mà nó lớn quá nó dễ bị làm trò này sau đó thì nếu mà 0,5 + 0,1 =
[01:07:08] trò này sau đó thì nếu mà 0,5 + 0,1 =
[01:07:08] trò này sau đó thì nếu mà 0,5 + 0,1 = 0,6 thì đúng nhưng nếu 0,1 + 0,2 = = 0,3
[01:07:12] 0,6 thì đúng nhưng nếu 0,1 + 0,2 = = 0,3
[01:07:12] 0,6 thì đúng nhưng nếu 0,1 + 0,2 = = 0,3 thì sai cái này không phải mỗi + 0,2 Tôi
[01:07:16] thì sai cái này không phải mỗi + 0,2 Tôi
[01:07:16] thì sai cái này không phải mỗi + 0,2 Tôi nhớ không lầm đó bằng 0,2
[01:07:18] nhớ không lầm đó bằng 0,2
[01:07:18] nhớ không lầm đó bằng 0,2 9999 thi ấy bởi 0,1 đối với da Suite thì
[01:07:22] 9999 thi ấy bởi 0,1 đối với da Suite thì
[01:07:22] 9999 thi ấy bởi 0,1 đối với da Suite thì nó nó không hẳn là bằng 0,1 đậu không
[01:07:25] nó nó không hẳn là bằng 0,1 đậu không
[01:07:25] nó nó không hẳn là bằng 0,1 đậu không phải 999 gì đấy
[01:07:31] chị thôi tiếp theo của một loạt ở dưới
[01:07:31] chị thôi tiếp theo của một loạt ở dưới này nữa ví dụ Giả sử là các bạn nhớ vợ
[01:07:34] này nữa ví dụ Giả sử là các bạn nhớ vợ
[01:07:34] này nữa ví dụ Giả sử là các bạn nhớ vợ lại 3 giờ bang là so sánh á
[01:07:37] lại 3 giờ bang là so sánh á
[01:07:37] lại 3 giờ bang là so sánh á các kiểu dữ liệu phải đúng đúng không ạ
[01:07:39] các kiểu dữ liệu phải đúng đúng không ạ
[01:07:39] các kiểu dữ liệu phải đúng đúng không ạ Nhưng nếu xu + chu + chu
[01:07:43] Nhưng nếu xu + chu + chu
[01:07:43] Nhưng nếu xu + chu + chu anh nói so sánh như thế này là đúng bởi
[01:07:46] anh nói so sánh như thế này là đúng bởi
[01:07:46] anh nói so sánh như thế này là đúng bởi vì chu + chu này convert thành số 2 mất
[01:07:48] vì chu + chu này convert thành số 2 mất
[01:07:48] vì chu + chu này convert thành số 2 mất rồi hai cộng với chu nữa bằng 3 Nên lúc
[01:07:51] rồi hai cộng với chu nữa bằng 3 Nên lúc
[01:07:51] rồi hai cộng với chu nữa bằng 3 Nên lúc đấy nó bằng luôn ba cái kẹo thế
[01:07:59] Em ở chỗ nào Cái này nó bay não nó chỉ
[01:07:59] Em ở chỗ nào Cái này nó bay não nó chỉ cho mày không xem qua thôi Tìm mấy ông
[01:08:01] cho mày không xem qua thôi Tìm mấy ông
[01:08:01] cho mày không xem qua thôi Tìm mấy ông hiểu việc là ra Suite nó nó bị khác với
[01:08:05] hiểu việc là ra Suite nó nó bị khác với
[01:08:05] hiểu việc là ra Suite nó nó bị khác với nhiều ngôn ngữ lập trình khác
[01:08:07] nhiều ngôn ngữ lập trình khác
[01:08:07] nhiều ngôn ngữ lập trình khác với việc nó bay não
[01:08:11] với việc nó bay não
[01:08:11] với việc nó bay não khi con cả cái nữa cơ nhìn thôi chứ
[01:08:14] khi con cả cái nữa cơ nhìn thôi chứ
[01:08:14] khi con cả cái nữa cơ nhìn thôi chứ nghĩa cây lúa đồi núi
[01:08:23] Ừ ok Nói chung là vừa rồi là
[01:08:24] Ừ ok Nói chung là vừa rồi là chị Xuka là hôm nay đã nhảy là phải dậy
[01:08:26] chị Xuka là hôm nay đã nhảy là phải dậy
[01:08:26] chị Xuka là hôm nay đã nhảy là phải dậy cả vòng lọc kết hợp với ạ i10 input đấy
[01:08:30] cả vòng lọc kết hợp với ạ i10 input đấy
[01:08:30] cả vòng lọc kết hợp với ạ i10 input đấy nhưng mà tôi nghĩ là tôi chỉ dậy đến
[01:08:33] nhưng mà tôi nghĩ là tôi chỉ dậy đến
[01:08:33] nhưng mà tôi nghĩ là tôi chỉ dậy đến ngưỡng như này thôi mà ông có gì về làm
[01:08:36] ngưỡng như này thôi mà ông có gì về làm
[01:08:36] ngưỡng như này thôi mà ông có gì về làm bài tập nhá về làm bài tập và bài tập sẽ
[01:08:39] bài tập nhá về làm bài tập và bài tập sẽ
[01:08:39] bài tập nhá về làm bài tập và bài tập sẽ là tại tôi sẽ cho mấy ông xem qua bài
[01:08:42] là tại tôi sẽ cho mấy ông xem qua bài
[01:08:42] là tại tôi sẽ cho mấy ông xem qua bài tập
[01:08:49] mở bài bài hôm nay sẽ có hai cái tôi nhớ
[01:08:49] mở bài bài hôm nay sẽ có hai cái tôi nhớ có câu Sao
[01:08:51] có câu Sao
[01:08:51] có câu Sao xe tải
[01:08:53] xe tải
[01:08:53] xe tải em lấy
[01:08:59] Anh à Hôm nay tôi ngồi chưa dậy khỏi
[01:08:59] Anh à Hôm nay tôi ngồi chưa dậy khỏi mạng cơ Ừ tí thôi sẽ thì tôi ra bài gì
[01:09:03] mạng cơ Ừ tí thôi sẽ thì tôi ra bài gì
[01:09:03] mạng cơ Ừ tí thôi sẽ thì tôi ra bài gì không đề cập về cụ mạng đi
[01:09:13] Ừ thì tôi sẽ giao trong bài tập riêng
[01:09:13] Ừ thì tôi sẽ giao trong bài tập riêng vậy
[01:09:14] vậy
[01:09:14] vậy ở
[01:09:15] ở
[01:09:15] ở những đại khái như thế thì tôi sẽ có bài
[01:09:18] những đại khái như thế thì tôi sẽ có bài
[01:09:18] những đại khái như thế thì tôi sẽ có bài tập cho mèo ông Còn bây giờ thì ạ tôi
[01:09:21] tập cho mèo ông Còn bây giờ thì ạ tôi
[01:09:21] tập cho mèo ông Còn bây giờ thì ạ tôi chia sẻ
[01:09:22] chia sẻ
[01:09:22] chia sẻ ở
[01:09:23] ở
[01:09:23] ở đầu tiên là tôi có cái đường Linh này
[01:09:26] đầu tiên là tôi có cái đường Linh này
[01:09:26] đầu tiên là tôi có cái đường Linh này đường link để mà nó đoạn CF
[01:09:30] đường link để mà nó đoạn CF
[01:09:30] đường link để mà nó đoạn CF đoạn cốt xét
[01:09:32] đoạn cốt xét
[01:09:32] đoạn cốt xét khẩu nó có giao diện Khá là đẹp cho tôi
[01:09:36] khẩu nó có giao diện Khá là đẹp cho tôi
[01:09:36] khẩu nó có giao diện Khá là đẹp cho tôi gửi cho ông bé ông ấy ông Thắng khác à
[01:09:43] Á và một cái nữa là
[01:09:43] Á và một cái nữa là có một cái trang này nếu mà những ông
[01:09:46] có một cái trang này nếu mà những ông
[01:09:46] có một cái trang này nếu mà những ông nào thích thế tìm hiểu về cái vụ hack
[01:09:50] nào thích thế tìm hiểu về cái vụ hack
[01:09:50] nào thích thế tìm hiểu về cái vụ hack khủng thì tôi thấy Trang này Đề cập rất
[01:09:53] khủng thì tôi thấy Trang này Đề cập rất
[01:09:53] khủng thì tôi thấy Trang này Đề cập rất là ổn
[01:09:55] là ổn
[01:09:55] là ổn Ừ Kệ cha mày ạ là trang giải thích về
[01:09:58] Ừ Kệ cha mày ạ là trang giải thích về
[01:09:58] Ừ Kệ cha mày ạ là trang giải thích về các hack khủng các thứ
[01:10:01] các hack khủng các thứ
[01:10:01] các hack khủng các thứ và vì sau tôi sẽ dạy cho mấy ông về xss
[01:10:08] và vì sau tôi sẽ dạy cho mấy ông về xss
[01:10:08] và vì sau tôi sẽ dạy cho mấy ông về xss giống như và này có bạn để cập đã cả vụ
[01:10:10] giống như và này có bạn để cập đã cả vụ
[01:10:10] giống như và này có bạn để cập đã cả vụ FBI lesson
[01:10:12] FBI lesson
[01:10:12] FBI lesson 22 cái đấy tôi sẽ dạy các bạn
[01:10:25] Ừ cái cái xăng này mấy ông thể vào
[01:10:25] Ừ cái cái xăng này mấy ông thể vào ạ bấm bấm bấm bấm các thứ mà ông xem
[01:10:27] ạ bấm bấm bấm bấm các thứ mà ông xem
[01:10:28] ạ bấm bấm bấm bấm các thứ mà ông xem cách cách người ta giải thích giải thích
[01:10:30] cách cách người ta giải thích giải thích
[01:10:30] cách cách người ta giải thích giải thích tại sao Hay phết
[01:10:34] Ừ
[01:10:34] Ừ nó đưa như bằng tiếng Anh rồi tự nhiên
[01:10:37] nó đưa như bằng tiếng Anh rồi tự nhiên
[01:10:37] nó đưa như bằng tiếng Anh rồi tự nhiên bằng tiếng Anh với ông thông cảm không
[01:10:38] bằng tiếng Anh với ông thông cảm không
[01:10:38] bằng tiếng Anh với ông thông cảm không phải bằng tiếng Việt được
[01:10:41] phải bằng tiếng Việt được
[01:10:41] phải bằng tiếng Việt được Tại nó còn khuya là mấy ông bấm vào đâu
[01:10:45] Tại nó còn khuya là mấy ông bấm vào đâu
[01:10:45] Tại nó còn khuya là mấy ông bấm vào đâu hay các thứ nó sẽ bị như nào nữa hay cực
[01:10:50] hay các thứ nó sẽ bị như nào nữa hay cực
[01:10:50] hay các thứ nó sẽ bị như nào nữa hay cực Ừ nếu có thể xem qua nếu Mấy ông không
[01:10:52] Ừ nếu có thể xem qua nếu Mấy ông không
[01:10:52] Ừ nếu có thể xem qua nếu Mấy ông không hiểu thì ạ về sau tôi sẽ giải thích
[01:10:54] hiểu thì ạ về sau tôi sẽ giải thích
[01:10:54] hiểu thì ạ về sau tôi sẽ giải thích trong mấy ông ít nhất là mấy cái đầu này
[01:10:57] trong mấy ông ít nhất là mấy cái đầu này
[01:10:57] trong mấy ông ít nhất là mấy cái đầu này còn mấy cái á mấy cái dưới này thì tôi
[01:11:01] còn mấy cái á mấy cái dưới này thì tôi
[01:11:01] còn mấy cái á mấy cái dưới này thì tôi thấy à
[01:11:02] thấy à
[01:11:02] thấy à em
[01:11:02] em
[01:11:02] em không có phải là mình gặp thường xuyên
[01:11:05] không có phải là mình gặp thường xuyên
[01:11:05] không có phải là mình gặp thường xuyên đi
[01:11:06] đi
[01:11:06] đi làm cho đỡ giải thích người hôm sau điều
[01:11:09] làm cho đỡ giải thích người hôm sau điều
[01:11:09] làm cho đỡ giải thích người hôm sau điều mà
[01:11:18] à À đúng rồi không phải không phải không
[01:11:18] à À đúng rồi không phải không phải không phải 299 đúng rồi không phải
[01:11:21] phải 299 đúng rồi không phải
[01:11:21] phải 299 đúng rồi không phải 3000 kia đúng vậy Cơm mình nhớ nhầm đấy
[01:11:23] 3000 kia đúng vậy Cơm mình nhớ nhầm đấy
[01:11:23] 3000 kia đúng vậy Cơm mình nhớ nhầm đấy Nói chung là đại khái là đối về đối với
[01:11:27] Nói chung là đại khái là đối về đối với
[01:11:27] Nói chung là đại khái là đối về đối với da Phi kể 0,1 Mình nhớ không phải một nó
[01:11:30] da Phi kể 0,1 Mình nhớ không phải một nó
[01:11:30] da Phi kể 0,1 Mình nhớ không phải một nó sẽ không phải là 0,1 hoàn toàn bảo nó
[01:11:32] sẽ không phải là 0,1 hoàn toàn bảo nó
[01:11:32] sẽ không phải là 0,1 hoàn toàn bảo nó lại khó phải phải đón sau nữa
[01:11:35] lại khó phải phải đón sau nữa
[01:11:35] lại khó phải phải đón sau nữa A và cái cuối cùng thì à
[01:11:37] A và cái cuối cùng thì à
[01:11:37] A và cái cuối cùng thì à Hồi trước ở tôi từng tra và cái vụ này
[01:11:40] Hồi trước ở tôi từng tra và cái vụ này
[01:11:40] Hồi trước ở tôi từng tra và cái vụ này vào tôi chia sẻ cho sinh viên của tôi về
[01:11:43] vào tôi chia sẻ cho sinh viên của tôi về
[01:11:43] vào tôi chia sẻ cho sinh viên của tôi về cái vụ là xem thông tin dòng máy
[01:11:48] cái vụ là xem thông tin dòng máy
[01:11:48] cái vụ là xem thông tin dòng máy để xem thông tin dòng mà đối với Intel
[01:11:51] để xem thông tin dòng mà đối với Intel
[01:11:51] để xem thông tin dòng mà đối với Intel rồi nhá thì mấy ông Để ý kỹ ở Thường nay
[01:11:54] rồi nhá thì mấy ông Để ý kỹ ở Thường nay
[01:11:54] rồi nhá thì mấy ông Để ý kỹ ở Thường nay có Y5 do ngồi gạch ngang lưng rồi nó
[01:11:58] có Y5 do ngồi gạch ngang lưng rồi nó
[01:11:58] có Y5 do ngồi gạch ngang lưng rồi nó xong rồi số là sau mấy ông chẳng hiểu Nó
[01:12:00] xong rồi số là sau mấy ông chẳng hiểu Nó
[01:12:00] xong rồi số là sau mấy ông chẳng hiểu Nó là gì ông ạ thì thì mới ông xem qua về
[01:12:04] là gì ông ạ thì thì mới ông xem qua về
[01:12:04] là gì ông ạ thì thì mới ông xem qua về cách ở đây thì y52 y thì ấy là tên dòng
[01:12:08] cách ở đây thì y52 y thì ấy là tên dòng
[01:12:08] cách ở đây thì y52 y thì ấy là tên dòng CPU này sau đó thì sổ ngay cái số tiếp
[01:12:11] CPU này sau đó thì sổ ngay cái số tiếp
[01:12:11] CPU này sau đó thì sổ ngay cái số tiếp theo ấy
[01:12:13] theo ấy
[01:12:13] theo ấy ý là kệ thế thế hệ của nó là thế hệ 7
[01:12:19] ý là kệ thế thế hệ của nó là thế hệ 7
[01:12:19] ý là kệ thế thế hệ của nó là thế hệ 7 hay thế dụ ở Lý Core I5 số 17 20m này
[01:12:25] hay thế dụ ở Lý Core I5 số 17 20m này
[01:12:25] hay thế dụ ở Lý Core I5 số 17 20m này thì 77 rất là thế hệ 7 này và cái chữ
[01:12:29] thì 77 rất là thế hệ 7 này và cái chữ
[01:12:29] thì 77 rất là thế hệ 7 này và cái chữ cuối thì để thể hiện xe mà nó là giọng
[01:12:32] cuối thì để thể hiện xe mà nó là giọng
[01:12:32] cuối thì để thể hiện xe mà nó là giọng gì đây Cái chữ cuối của nó
[01:12:41] cho mình nhớ là có chứ có cái dài thì
[01:12:41] cho mình nhớ là có chứ có cái dài thì Cái chữ cuối
[01:12:48] ở đây giải thích ý nghĩa của ký tự cuối
[01:12:48] ở đây giải thích ý nghĩa của ký tự cuối của tên này ví dụ là
[01:12:51] của tên này ví dụ là
[01:12:51] của tên này ví dụ là Ừ nếu mà mày Ông
[01:12:53] Ừ nếu mà mày Ông
[01:12:53] Ừ nếu mà mày Ông mua bây giờ chưa mua laptop hoặc là giả
[01:12:57] mua bây giờ chưa mua laptop hoặc là giả
[01:12:57] mua bây giờ chưa mua laptop hoặc là giả sử về sau muốn mua lắp tội nữa đúng
[01:12:59] sử về sau muốn mua lắp tội nữa đúng
[01:12:59] sử về sau muốn mua lắp tội nữa đúng không ạ thì mày ông phải biết được ý
[01:13:01] không ạ thì mày ông phải biết được ý
[01:13:01] không ạ thì mày ông phải biết được ý nghĩa của nó ngồi mình nhớ là tiết kiệm
[01:13:04] nghĩa của nó ngồi mình nhớ là tiết kiệm
[01:13:04] nghĩa của nó ngồi mình nhớ là tiết kiệm pin
[01:13:05] pin
[01:13:05] pin đây U này nó sẽ hợp cho ông nào thích
[01:13:09] đây U này nó sẽ hợp cho ông nào thích
[01:13:09] đây U này nó sẽ hợp cho ông nào thích kiểu máy tính có pin trâu
[01:13:11] kiểu máy tính có pin trâu
[01:13:11] kiểu máy tính có pin trâu thường ai làm được văn phòng hơn
[01:13:14] thường ai làm được văn phòng hơn
[01:13:14] thường ai làm được văn phòng hơn Còn nếu mà Mấy ông muốn ngon đấy Cái
[01:13:18] Còn nếu mà Mấy ông muốn ngon đấy Cái
[01:13:18] Còn nếu mà Mấy ông muốn ngon đấy Cái chích ngon thường ai chip nó liên quan
[01:13:20] chích ngon thường ai chip nó liên quan
[01:13:20] chích ngon thường ai chip nó liên quan đến chị mời này chị sẽ ngon này
[01:13:23] đến chị mời này chị sẽ ngon này
[01:13:24] đến chị mời này chị sẽ ngon này lại mày không thể đọc qua và ý nghĩa của
[01:13:26] lại mày không thể đọc qua và ý nghĩa của
[01:13:26] lại mày không thể đọc qua và ý nghĩa của các loại Chip có thứ
[01:13:28] các loại Chip có thứ
[01:13:28] các loại Chip có thứ thời này không có cái thôi mà có bài
[01:13:31] thời này không có cái thôi mà có bài
[01:13:31] thời này không có cái thôi mà có bài đăng này thì không có hát về hát quy đâu
[01:13:41] Ừ đúng rồi có thể thế hệ sau này đưa có
[01:13:41] Ừ đúng rồi có thể thế hệ sau này đưa có thêm một vài cái dòng chip nữa Bài này
[01:13:44] thêm một vài cái dòng chip nữa Bài này
[01:13:44] thêm một vài cái dòng chip nữa Bài này bài cũ rồi nhưng mà ý tôi thì về quy tắc
[01:13:47] bài cũ rồi nhưng mà ý tôi thì về quy tắc
[01:13:47] bài cũ rồi nhưng mà ý tôi thì về quy tắc ghi của nó thì nó vẫn thế đối mặt thì
[01:13:50] ghi của nó thì nó vẫn thế đối mặt thì
[01:13:50] ghi của nó thì nó vẫn thế đối mặt thì mời ông có thể đọc kỹ hôn chứ mấy ông
[01:13:54] mời ông có thể đọc kỹ hôn chứ mấy ông
[01:13:54] mời ông có thể đọc kỹ hôn chứ mấy ông đừng có nghĩ à Mấy cái tên này thì mình
[01:13:57] đừng có nghĩ à Mấy cái tên này thì mình
[01:13:57] đừng có nghĩ à Mấy cái tên này thì mình cái tên này nó không gọi nghĩa gì cả
[01:14:00] cái tên này nó không gọi nghĩa gì cả
[01:14:00] cái tên này nó không gọi nghĩa gì cả cái tên này đều có ý nghĩa của nó và mấy
[01:14:03] cái tên này đều có ý nghĩa của nó và mấy
[01:14:03] cái tên này đều có ý nghĩa của nó và mấy ông cần phải tra và mấy ông đừng có đánh
[01:14:06] ông cần phải tra và mấy ông đừng có đánh
[01:14:06] ông cần phải tra và mấy ông đừng có đánh giá việc làm y cao nhất thì là ngon ngất
[01:14:08] giá việc làm y cao nhất thì là ngon ngất
[01:14:08] giá việc làm y cao nhất thì là ngon ngất nhá đôi khi là i5 thế hệ 7 nó còn ngon
[01:14:12] nhá đôi khi là i5 thế hệ 7 nó còn ngon
[01:14:12] nhá đôi khi là i5 thế hệ 7 nó còn ngon hơn cả i7 thế hệ 3 thế 4 thì gì vậy cơ
[01:14:16] hơn cả i7 thế hệ 3 thế 4 thì gì vậy cơ
[01:14:16] hơn cả i7 thế hệ 3 thế 4 thì gì vậy cơ Thế nên là mấy ông phải xem thế hệ chứ
[01:14:19] Thế nên là mấy ông phải xem thế hệ chứ
[01:14:19] Thế nên là mấy ông phải xem thế hệ chứ đừng có xe mỗi về cái tên dòng của sẽ
[01:14:21] đừng có xe mỗi về cái tên dòng của sẽ
[01:14:21] đừng có xe mỗi về cái tên dòng của sẽ peu đúng không ạ
[01:14:23] peu đúng không ạ
[01:14:23] peu đúng không ạ em có con gì thế hệ luôn là nên thế 3
[01:14:27] em có con gì thế hệ luôn là nên thế 3
[01:14:27] em có con gì thế hệ luôn là nên thế 3 đổi lên nhé và còn chích thì đương nhiên
[01:14:30] đổi lên nhé và còn chích thì đương nhiên
[01:14:30] đổi lên nhé và còn chích thì đương nhiên cám chip dòng càng cao thì đương nhiên
[01:14:32] cám chip dòng càng cao thì đương nhiên
[01:14:32] cám chip dòng càng cao thì đương nhiên nó sẽ càng khỏe nhưng mà như tôi đã nói
[01:14:34] nó sẽ càng khỏe nhưng mà như tôi đã nói
[01:14:34] nó sẽ càng khỏe nhưng mà như tôi đã nói nếu mà thế hệ của nó thấp thì thì đôi
[01:14:38] nếu mà thế hệ của nó thấp thì thì đôi
[01:14:38] nếu mà thế hệ của nó thấp thì thì đôi khi ở cái hàng mày i5 Thế Hệ 9 có khinh
[01:14:40] khi ở cái hàng mày i5 Thế Hệ 9 có khinh
[01:14:40] khi ở cái hàng mày i5 Thế Hệ 9 có khinh vẫn ngon hơn trả nặng thế
[01:14:44] vẫn ngon hơn trả nặng thế
[01:14:44] vẫn ngon hơn trả nặng thế anh đấy đấy về
[01:14:46] anh đấy đấy về
[01:14:46] anh đấy đấy về trả chị qua cho mấy ông mà làm việc cách
[01:14:49] trả chị qua cho mấy ông mà làm việc cách
[01:14:49] trả chị qua cho mấy ông mà làm việc cách mua máy tính bây giờ
[01:14:51] mua máy tính bây giờ
[01:14:51] mua máy tính bây giờ Ừ ok tra ạ hết cái thứ rồi mới chia sẻ
[01:14:55] Ừ ok tra ạ hết cái thứ rồi mới chia sẻ
[01:14:55] Ừ ok tra ạ hết cái thứ rồi mới chia sẻ được mấy ông rồi tạm thời thay thế
[01:14:59] được mấy ông rồi tạm thời thay thế
[01:14:59] được mấy ông rồi tạm thời thay thế à à
[01:15:01] à à
[01:15:01] à à Ừ thôi mấy ông kia lại đang bị đi sâu có
[01:15:04] Ừ thôi mấy ông kia lại đang bị đi sâu có
[01:15:04] Ừ thôi mấy ông kia lại đang bị đi sâu có cả xung nhịp với số nhân tiểu đường mấy
[01:15:07] cả xung nhịp với số nhân tiểu đường mấy
[01:15:07] cả xung nhịp với số nhân tiểu đường mấy mấy cái người mà không phải luôn công
[01:15:09] mấy cái người mà không phải luôn công
[01:15:09] mấy cái người mà không phải luôn công nghệ thì tra chưa biết qua mày cái đấy
[01:15:10] nghệ thì tra chưa biết qua mày cái đấy
[01:15:10] nghệ thì tra chưa biết qua mày cái đấy đâu Tôi đang chỉ hướng dẫn cho mấy ông
[01:15:13] đâu Tôi đang chỉ hướng dẫn cho mấy ông
[01:15:13] đâu Tôi đang chỉ hướng dẫn cho mấy ông này việc mua 1 con laptop để mà để mà
[01:15:18] này việc mua 1 con laptop để mà để mà
[01:15:18] này việc mua 1 con laptop để mà để mà khoa học tập học tập chắc là mấy ông học
[01:15:21] khoa học tập học tập chắc là mấy ông học
[01:15:21] khoa học tập học tập chắc là mấy ông học tập thì cũng nhiều đấy nhà mà chơi game
[01:15:22] tập thì cũng nhiều đấy nhà mà chơi game
[01:15:22] tập thì cũng nhiều đấy nhà mà chơi game thì ạ chơi mấy game giống mức độ nhẹ thì
[01:15:25] thì ạ chơi mấy game giống mức độ nhẹ thì
[01:15:25] thì ạ chơi mấy game giống mức độ nhẹ thì méo càng không cần phải quan tâm về việc
[01:15:27] méo càng không cần phải quan tâm về việc
[01:15:27] méo càng không cần phải quan tâm về việc là à
[01:15:29] là à
[01:15:29] là à khi các yếu tố chip nhân hai cặp đồ họa
[01:15:33] khi các yếu tố chip nhân hai cặp đồ họa
[01:15:33] khi các yếu tố chip nhân hai cặp đồ họa lắm ví dụ là sự chơi ll chơi
[01:15:37] lắm ví dụ là sự chơi ll chơi
[01:15:37] lắm ví dụ là sự chơi ll chơi FIFA không nặng lắm nhỉ cái kiểu thế
[01:15:42] FIFA không nặng lắm nhỉ cái kiểu thế
[01:15:42] FIFA không nặng lắm nhỉ cái kiểu thế hỗ trợ cho ta độ thấp nhất cho CS Go để
[01:15:45] hỗ trợ cho ta độ thấp nhất cho CS Go để
[01:15:45] hỗ trợ cho ta độ thấp nhất cho CS Go để còn cân nhắc mình tí à
[01:15:49] còn cân nhắc mình tí à
[01:15:49] còn cân nhắc mình tí à Ừ ừ thì mày Ông mua mày để mày lập trình
[01:15:51] Ừ ừ thì mày Ông mua mày để mày lập trình
[01:15:51] Ừ ừ thì mày Ông mua mày để mày lập trình ở nhặn thì mày Ông không cần phải cấu
[01:15:54] ở nhặn thì mày Ông không cần phải cấu
[01:15:54] ở nhặn thì mày Ông không cần phải cấu hình nặng không cần phải card đồ họa
[01:15:57] hình nặng không cần phải card đồ họa
[01:15:57] hình nặng không cần phải card đồ họa sự thực là chỉ cầm thêm một tí hát
[01:16:00] sự thực là chỉ cầm thêm một tí hát
[01:16:00] sự thực là chỉ cầm thêm một tí hát hồ thì nên SD mở lên nó mượn này ra mình
[01:16:05] hồ thì nên SD mở lên nó mượn này ra mình
[01:16:05] hồ thì nên SD mở lên nó mượn này ra mình nên ở trên 8GB này ra bây giờ thì ra bây
[01:16:08] nên ở trên 8GB này ra bây giờ thì ra bây
[01:16:08] nên ở trên 8GB này ra bây giờ thì ra bây giờ mà Mấy ông còn bún đi chắc chịu
[01:16:10] giờ mà Mấy ông còn bún đi chắc chịu
[01:16:10] giờ mà Mấy ông còn bún đi chắc chịu không ạ Đấy
[01:16:17] có thẩm mỹ lợn Còn mấy bạn mua về máy về
[01:16:17] có thẩm mỹ lợn Còn mấy bạn mua về máy về chỉ để mà
[01:16:19] chỉ để mà
[01:16:19] chỉ để mà xem phim mấy bạn nữ rồi ạ thì chỉ cần
[01:16:22] xem phim mấy bạn nữ rồi ạ thì chỉ cần
[01:16:22] xem phim mấy bạn nữ rồi ạ thì chỉ cần máy tính nhẹ pin trâu chạy được mấy cái
[01:16:25] máy tính nhẹ pin trâu chạy được mấy cái
[01:16:25] máy tính nhẹ pin trâu chạy được mấy cái tác vụ văn phòng Ninh Thuận còn về cốt
[01:16:28] tác vụ văn phòng Ninh Thuận còn về cốt
[01:16:28] tác vụ văn phòng Ninh Thuận còn về cốt thì các bạn thì yên tâm mà máy các bạn
[01:16:31] thì các bạn thì yên tâm mà máy các bạn
[01:16:31] thì các bạn thì yên tâm mà máy các bạn mà mở được cái note á đấy thì nó sao nó
[01:16:34] mà mở được cái note á đấy thì nó sao nó
[01:16:34] mà mở được cái note á đấy thì nó sao nó mở được cái sắp ai-tek với nó rất là nhẹ
[01:16:35] mở được cái sắp ai-tek với nó rất là nhẹ
[01:16:35] mở được cái sắp ai-tek với nó rất là nhẹ mấy bạn thì chắc chắn hiển nhiên mở rồi
[01:16:38] mấy bạn thì chắc chắn hiển nhiên mở rồi
[01:16:38] mấy bạn thì chắc chắn hiển nhiên mở rồi các trình duyệt rồi thì sẽ về các bạn
[01:16:40] các trình duyệt rồi thì sẽ về các bạn
[01:16:40] các trình duyệt rồi thì sẽ về các bạn cút cút quét phải rất vô tư đúng không ạ
[01:16:43] cút cút quét phải rất vô tư đúng không ạ
[01:16:43] cút cút quét phải rất vô tư đúng không ạ web vô từ Còn nếu mà các bạn cốt chanh
[01:16:46] web vô từ Còn nếu mà các bạn cốt chanh
[01:16:46] web vô từ Còn nếu mà các bạn cốt chanh những cái kiểu cần giả lập gồm như Cốt
[01:16:50] những cái kiểu cần giả lập gồm như Cốt
[01:16:50] những cái kiểu cần giả lập gồm như Cốt khi các bạn mua máy Windows mà các bạn
[01:16:53] khi các bạn mua máy Windows mà các bạn
[01:16:53] khi các bạn mua máy Windows mà các bạn muốn cốt iOS phải giả lập IOS chẳng hạn
[01:16:56] muốn cốt iOS phải giả lập IOS chẳng hạn
[01:16:56] muốn cốt iOS phải giả lập IOS chẳng hạn thì đương nhiên là sẽ phải thêm thêm RAM
[01:17:00] thì đương nhiên là sẽ phải thêm thêm RAM
[01:17:00] thì đương nhiên là sẽ phải thêm thêm RAM à à
[01:17:07] cho tôi khuyên mấy ông nghỉ nên mua 1
[01:17:08] cho tôi khuyên mấy ông nghỉ nên mua 1 con laptop hơn là một con con máy tính
[01:17:10] con laptop hơn là một con con máy tính
[01:17:10] con laptop hơn là một con con máy tính cảm nhận máy tính bảng bởi vì mấy ông
[01:17:13] cảm nhận máy tính bảng bởi vì mấy ông
[01:17:13] cảm nhận máy tính bảng bởi vì mấy ông theo ngành Công nghệ thông tin về mail
[01:17:14] theo ngành Công nghệ thông tin về mail
[01:17:14] theo ngành Công nghệ thông tin về mail nên đi ra ngoài nhiều hơn mang mày Anh
[01:17:17] nên đi ra ngoài nhiều hơn mang mày Anh
[01:17:17] nên đi ra ngoài nhiều hơn mang mày Anh công ty trừ khi công ty ông tài trợ cho
[01:17:21] công ty trừ khi công ty ông tài trợ cho
[01:17:21] công ty trừ khi công ty ông tài trợ cho một cái
[01:17:22] một cái
[01:17:22] một cái khi con không thì mình nên cốt như kiểu
[01:17:27] khi con không thì mình nên cốt như kiểu
[01:17:27] khi con không thì mình nên cốt như kiểu à mà bị mang lại nó vẫn tiện hơn
[01:17:34] A
[01:17:34] A stardrive hết đặt mà nói rồi nha
[01:17:39] stardrive hết đặt mà nói rồi nha
[01:17:39] stardrive hết đặt mà nói rồi nha hỗ trợ toàn bộ những câu hỏi các bạn
[01:17:41] hỗ trợ toàn bộ những câu hỏi các bạn
[01:17:41] hỗ trợ toàn bộ những câu hỏi các bạn mình sẽ ghép buổi trao trả lời nhé
[01:17:44] mình sẽ ghép buổi trao trả lời nhé
[01:17:44] mình sẽ ghép buổi trao trả lời nhé từ hôm nay trao tặng 10 như thế thôi
[01:17:46] từ hôm nay trao tặng 10 như thế thôi
[01:17:46] từ hôm nay trao tặng 10 như thế thôi chào các bạn
