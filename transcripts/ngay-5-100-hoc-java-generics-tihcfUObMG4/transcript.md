# Ngày 5/100 học Java - Generics

- Video ID: `tihcfUObMG4`
- URL: https://www.youtube.com/watch?v=tihcfUObMG4
- Published: 2026-01-24
- Duration: 1h 24m 35s (5075s)
- Language: vi
- Subtitle source: auto
- Kind: live

## Transcript

[00:00:33] Xin chào mấy ông. Ờ hôm nay là
[00:00:36] livestream đúng kiểu bất ngờ không báo
[00:00:38] trước nhưng mà thì mình cũng bị lỡ không
[00:00:45] học tận chẳng biết là từ hôm từ mấy rồi
[00:00:48] đấy. ba kêu là hàng ngày học nhưng mà có
[00:00:51] vẻ là tuần trước thì tôi lấy cớ là
[00:00:56] ừ chuẩn bị cho tiệc cuối năm về tôi làm
[00:00:59] cả đâu
[00:01:01] đã livestream tận 8 ngày trước đấy nh
[00:01:03] tuần live thì tôi lấy cớ có thể lấy cớ
[00:01:07] là do đây chuẩn bị tiệc cuối năm mình
[00:01:10] vừa là trong ban tổ chức vừa làm MC rồi
[00:01:14] vừa dễ văn nghệ nữa
[00:01:17] đấy Thì anti gravity mới thêm cái mới.
[00:01:22] Tính là gần đây hôm hôm trước không biết
[00:01:24] là mấy ông có dùng anti Gravity không?
[00:01:27] Hôm trước antigravity có kiểu
[00:01:30] không gọi như là không dùng được trong
[00:01:33] vòng từ
[00:01:36] 2:00 chiều cho đến tầm chắc là đến tầm
[00:01:39] tối đấy. thời gian đấy xong rồi tôi đang
[00:01:42] vi code nên thành ra là kiểu bị gián
[00:01:45] đoạn nên là phải kiểu à tải gấp win win
[00:01:49] search quay lại win search thì mình nhớ
[00:01:52] lại win search là kiểu nó cập nhật cái
[00:01:54] này
[00:01:55] hàng ngày cũng có dùng từ hàng ngày hơi
[00:01:57] quá nhưng đại khái nó cập nhật liên tục
[00:02:00] ví dụ giả sử ra được cái model mới model
[00:02:03] ai mới nó sẽ tích hợp ngay vào trong cái
[00:02:06] đấy nó rất là nhanh luôn ấy kiểu vừa mới
[00:02:09] công bố là kiểu
[00:02:11] thứ các thứ xong rồi tính năng cái chen
[00:02:14] lắ nó rất nhiều con anti này tôi thấy
[00:02:17] phải khởi ít khá là ít. Sanbox ồ sunbox
[00:02:22] terminal cũng được nhưng mà tôi thấy
[00:02:24] fixbox cần nhiều đây toàn cải thiện cái
[00:02:27] gì đó fix hơi ít nhỉ.
[00:02:36] chào các bạn chắc không phải bạn ngồi
[00:02:38] cạnh mình tôi đâu.
[00:02:46] Hôm nay chúng ta sẽ học Java. Đợi tí
[00:02:48] thôi. Tìm lại cái bài hồi trước mình học
[00:02:52] Java
[00:02:54] từ hôm trước học thì bây giờ là phải tầm
[00:02:57] một tuần nhỉ.
[00:03:22] nhớ không? Đại khái thì tôi sẽ ngồi à ôn
[00:03:26] lại kiểu ôn lại từ đầu quên mất
[00:03:29] [khịt mũi] rồi buổi thứ năm đúng không
[00:03:31] ạ?
[00:03:33] Xong rồi. Còn buổi sáu buổi 10 này thì
[00:03:35] chắc tí mình ngồi soạn tiếp dùng AI ngồi
[00:03:38] tạo tiếp ra buổi buổi sáu đến buổi 12
[00:03:42] hay là nói chung là những buổi sau đúng
[00:03:44] không ạ? [khịt mũi]
[00:03:46] Bài tập tức ra là mình cũng chưa làm bài
[00:03:48] tập gì cả. Mình cũng ngồi xem lại các
[00:03:51] thứ mình mới chỉ có dừng dừng lại kiểu
[00:03:54] đọc kiểu code thôi. Đấy chưa làm bài tập
[00:03:57] gì cả.
[00:04:05] trong buổi này hôm nay nhá. À mấy ông có
[00:04:08] gì mấy ông cứ chat nếu mà muốn tâm sự
[00:04:11] cho chuyện gì đó nhá. Tôi vẫn sẽ kiểu
[00:04:15] tôi vẫn để ý chat mà.
[00:04:28] 11.
[00:04:30] Sao dù thời gian đầu là đúng mình vẫn
[00:04:31] kiểu mapping 11 là so sánh PP có gì,
[00:04:34] Java có gì đúng không ạ? [khịt mũi]
[00:04:36] Nhưng mà thực ra là mình nên có cái túi
[00:04:39] gì cốt lõi này đúng không?
[00:04:41] Mental model này hôm trước tôi mới biết
[00:04:43] hay phết
[00:04:51] cùng mấy ông để ngồi đọc cái
[00:04:54] mấy cái tôi chia sẻ ở trên server
[00:04:57] Discord.
[00:04:59] Server Discord. Server Discord tôi
[00:05:01] thường hay chia sẻ gần đây chia sẻ càng
[00:05:03] nhiều hơn bởi vì tham gia được nhiều
[00:05:05] nhóm hơn ấy. Đặc biệt nhóm về ai thì đợi
[00:05:08] tôi một tí
[00:05:10] thì cho mấy ông có thể ngồi xem cùng
[00:05:15] chúng ta ngồi đọc cùng. Ví dụ hôm trước
[00:05:17] là anh a
[00:05:20] anh Jam anh đấy có
[00:05:37] rồi cả cái Ghub spec kit này hôm trước
[00:05:40] anh Jam anh chia sẻ này thậm chí là
[00:05:44] có bài chia sẻ của Bạn à hôm trước bạn à
[00:05:47] đây series 2 này tôi cũng chưa đọc cơ tí
[00:05:50] tôi nếu có thể tôi sẽ tí tôi sẽ ngồi đọc
[00:05:53] cùng mấy ông nhá.
[00:06:00] học một mình mình hơi chán thì bây giờ
[00:06:02] có người ngồi đọc cùng ngồi học cùng
[00:06:04] cũng hay đấy. Tận dụng cả AI còn cả nhân
[00:06:09] hóa việc học của mình cùng lúc cùng mình
[00:06:12] nó sẽ cảm thấy hay hơn. Tôi thấy thế.
[00:06:20] này. Cái này thì mấy ông nhớ không ạ?
[00:06:22] Cái này về kiểu dữ liệu nguyên thủy và
[00:06:25] kiểu nó giống kiểu đối tượng class đúng
[00:06:28] không ạ? Sẽ có thêm những cái gì? Có vẻ
[00:06:30] tôi nhớ cái này. Ok. Tiếp theo string
[00:06:34] pool này
[00:06:37] tái sử dụng lại kiểu nó lưu một cái lư
[00:06:40] vào pool và một cái lưu vào hip. Đúng
[00:06:43] rồi. Nó tạo object mới trong hip. Cái
[00:06:45] này là nó là grapper class vừa nãy đúng
[00:06:48] không ạ?
[00:06:51] Bị mất bas
[00:06:53] đấy. Cáap mà đúng không nhỉ? Đang lên
[00:06:55] plan học lại. [khịt mũi]
[00:06:57] Thực ra là khi bị mất à
[00:07:02] hồi trước tôi cũng từng nghĩ thế. Hồi
[00:07:04] trước hồi mà tôi học tôi học nghề mà nên
[00:07:07] là hồi trước tôi nghĩ là tôi luôn hỏng
[00:07:09] về kiến thức bay kể hình ứng kiến kiến
[00:07:12] thức nền xong rồi tôi nghĩ là kiểu tôi
[00:07:15] phải nên ôn lại cái đấy nhưng mà về sau
[00:07:17] tôi mới nhận ra là thực là không cần
[00:07:19] thiết lắm khi mà mình có thể đi làm được
[00:07:21] mục tiêu mình vẫn là để đi làm mà đúng
[00:07:22] không
[00:07:24] đương nhiên là không nói là kiến thức nó
[00:07:26] không quan trọng nhá nói là
[00:07:29] lúc đấy ông mới thực sự là biết được là
[00:07:32] mình cần học những cái gì đấy. Còn nếu
[00:07:35] bây giờ toàn bộ kiến thức bây giờ ông
[00:07:36] vẫn đủ ấy thì có thể có thể thôi nhá là
[00:07:40] ông vẫn đủ dùng rồi. Nhưng mà nó vẫn sẽ
[00:07:42] có một cái nhược điểm nữa đó là hôm
[00:07:45] trước nghe nói khái niệm đó là mình
[00:07:48] không biết là mình không biết.
[00:07:52] Ừ đấy gọi điểm mù ấy mấy ông biết cái
[00:07:54] cái nhiệm đấy không? Đó là kiểu bình
[00:07:56] thường là ông biết là ông biết những cái
[00:07:59] gì, ông biết là ông không biết những cái
[00:08:03] gì.
[00:08:03] Đấy. Và ông không biết là ông không biết
[00:08:06] cái gì. Ví dụ giả sử không biết được là
[00:08:10] à là là
[00:08:17] vân vân. Đấy, phải khi có người khai
[00:08:20] sáng ra mình thì mình mới biết chứ mình
[00:08:22] chỉ biết được là mình không biết Java
[00:08:24] thôi chứ mình không hề biết được là Java
[00:08:26] nó có thể như thế nào. Đấy, thì ví dụ là
[00:08:31] ông làm ông đang kêu ông thiếu bị thiếu
[00:08:34] kiến thức gì đó,
[00:08:36] đúng là sẽ có một ngày nào đó kiến thức
[00:08:38] đấy nó quan trọng thì
[00:08:40] nó có thể sẽ giới hạn khả năng của mình
[00:08:43] và giới hạn cả cơ hội. Ví dụ giả sử cơ
[00:08:45] hội để mà mình thăng tiến hơn mình lên
[00:08:48] làm à kiểu quản lý rủ ro quản lý không
[00:08:52] phải dùng quản lý do hơi quá nhỉ kiểu
[00:08:54] phân tích thiết kế hệ thống này xong rồi
[00:08:57] hoặc là tối ưu này vân vân những cái a
[00:09:01] chức vụ quan trọng hơn những cái row
[00:09:03] những cái vai trò kiểu xịn hơn thì lúc
[00:09:06] đấy phải đòi hỏi cái kiến thức nền phải
[00:09:08] vững hơn vì lúc đấy mình không chỉ dừng
[00:09:10] ở việc bit code nữa thì đến lúc đấy là
[00:09:13] ông sẽ biết được là à còn thiếu rất
[00:09:15] nhiều và ông cần phải được khai sáng
[00:09:18] nhiều. Còn đến thời điểm hiện tại nói
[00:09:21] chung là nó phải ngưỡng như nào đã. Ví
[00:09:23] dụ nhá ông mới a đi làm 2 năm chẳng hạn
[00:09:27] thực ra ông vẫn chỉ cần dừng ở việc bit
[00:09:29] code thôi. Ông không cần biết tối ưu vì
[00:09:31] chẳng ai cho ông động vào cả. Ông làm gì
[00:09:33] có kinh nghiệm đúng không? Đấy không
[00:09:35] phải đi làm đủ lâu để mà
[00:09:39] cái quan trọng đó là tôi có biết đặc
[00:09:41] biệt trong ngành ngành này tôi biết nhá
[00:09:43] ngành khác thì tôi không rõ lắm nhưng
[00:09:45] tôi biết được là có rất nhiều anh em
[00:09:47] tính ngành này bằng năm kinh nghiệm
[00:09:50] nhưng thực ra nó đôi khi nó không đúng
[00:09:52] lắm vì có rất nhiều anh em kiểu 3 4 năm
[00:09:54] liền vẫn chỉ làm những cái tính năng
[00:09:55] kiểu thêm xử xóa thôi thì kiến thức của
[00:09:58] họ sẽ chỉ dừng ở mức độ đấy thì nó vẫn
[00:10:02] vẫn gọi là gì ạ không thể lấy Đấy má là
[00:10:04] cả s được midle có khi còn chưa biết thế
[00:10:08] nào nhá. Nghĩa họ vẫn chỉ dừng ở việc
[00:10:10] biết code thôi. Đấy thì họ không biết
[00:10:13] tối ưu. Họ không không quan tâm đến tối
[00:10:15] ưu luôn. Ví dụ giả sử Java này là liên
[00:10:17] quan đến bộ nhớ này, liên quan đến a
[00:10:20] [khịt mũi]
[00:10:21] xử lý đá luồng, xử lý gì đó phức tạp và
[00:10:24] và có thể phân tích ra. Cái quan trọng
[00:10:27] ấy ông cứ hình dung là cái quan trọng ấy
[00:10:29] đó là khi mà sếp ông hỏi là
[00:10:33] em có ý tưởng gì cho cái tính năng này.
[00:10:37] Đấy ông chỉ để xuất ra được đúng một ý
[00:10:39] tưởng, đúng một giải pháp thôi là chứng
[00:10:42] tỏ là ông chưa, chưa có kiến thức hoặc
[00:10:46] chưa được nghĩ đủ nhiều cho những cái
[00:10:48] đấy.
[00:10:50] Đấy ông ông hình dung không? Ví dụ là
[00:10:51] kiểu hồi trước là tôi đề xuất được hai,
[00:10:54] ít nhất là hai cho đến ba giải pháp và
[00:10:57] mỗi cái đều có ưu nhược. Đấy, tôi không
[00:11:00] nói là tôi đã lên đến cái tầm rất là xịn
[00:11:02] nhá nhưng mà ý tôi hướng đến là thế. Và
[00:11:04] sếp cũng sẽ thích nghe kiểu thế. Ông
[00:11:06] hình dung không? Sếp sẽ thích nghe được
[00:11:08] kìa
[00:11:09] là sếp được quyền lựa chọn chứ đếu phải
[00:11:12] kiểu tao chỉ em chỉ biết làm mỗi một cái
[00:11:15] thôi.
[00:11:16] Xong rồi anh anh hỏi thế thì em chỉ biết
[00:11:19] làm mỗi cái này em đề xuất mỗi cái này.
[00:11:21] Đấy xong rồi anh đề xuất cái khác chịu
[00:11:23] em không làm được. Không phải thế đúng
[00:11:26] không ạ? Mình
[00:11:28] mình phải cho sếp nhiều lựa chọn để sếp
[00:11:30] quyết định và mình nói được ưu và nhược
[00:11:32] để sếp đỡ phải suy nghĩ càng tốt. Sếp sẽ
[00:11:34] chỉ cần thấy là ok. Em thấy à ví dụ hồi
[00:11:39] đấy nhá tôi từng đề xuất hai giải pháp
[00:11:42] một cái là sử dụng luôn cái thư viện ở
[00:11:45] bên thứ ba. Đấy nó sẽ có nguy hiểm là
[00:11:48] mình phải phụ thuộc bên đấy hay vân vân
[00:11:50] gì đó. Còn giải pháp thứ hai mình đập đi
[00:11:52] làm lại có thể tốn thời gian hơn nhưng
[00:11:55] mà mình sẽ làm kiểm soát được đúng
[00:11:57] không? Mình quản lý được và mình hiểu
[00:11:58] được luồng thậm chí về xong mình custom
[00:12:00] được vân vân vân vân. Đấy thì đây lên
[00:12:03] hai phương án để mà sếp kiểu duyệt để
[00:12:05] sếp cảm thấy là nếu mình có thời gian
[00:12:08] thì mình sẽ làm phương án nào đúng
[00:12:10] không?
[00:12:12] Nếu thường là các sếp nếu mà không phải
[00:12:14] anh CTO nhá mà anh CO kiểu CEO ấy kiểu
[00:12:20] nói chung là những ông không phải chuyên
[00:12:22] về công nghệ ông sẽ thường liên quan đến
[00:12:24] tối ưu chi phí thì ông sẽ thường là chọn
[00:12:26] những cái giải pháp nào mà tối ưu chi
[00:12:28] phí nhất. Đôi khi là tối ưu chi phí đây
[00:12:30] không nhất thiết phải tiền mà thực ra là
[00:12:31] liên quan thời gian. Thối ưu chi phí
[00:12:33] thời gian thời gian cũng là tiền mà đúng
[00:12:34] không? Đấy nhưng mà CTO thì họ sẽ thiên
[00:12:38] một tí về công nghệ nghĩa họ phải hiểu
[00:12:40] được cái bài toán gọi là
[00:12:43] khái niệm gần đây tôi có biết nó từ ch à
[00:12:47] chắc bạn biết thế này. Check off là bài
[00:12:51] toán đánh đổi đấy. Mình sẽ đánh đổi dạng
[00:12:54] như nào đúng không ạ? Đấy thì nhiều
[00:12:57] người đánh đổi chấp nhận đánh đổi chấp
[00:13:00] nhận đánh đổi thời gian chấp nhận đánh
[00:13:02] đổi tiền bạc để mình
[00:13:06] quản lý kiểm soát được nó. Và công ty
[00:13:08] hơi tôi hồi trước làm thế thật đó là bởi
[00:13:11] vì về sau còn định làm hẳn cái để mà làm
[00:13:15] cái dịch vụ để cho bên khác thuê luôn.
[00:13:17] Mình bên mình dùng bên mình không tốn
[00:13:20] tiền quá nhiều chi phí cho bên thứ ba
[00:13:23] đúng không? Và thậm chí mình còn lại mở
[00:13:25] dịch vụ để cho người khác dùng. Đấy,
[00:13:27] kiểu thế.
[00:13:36] một thôi nhưng mà mình trả lời hơi dài
[00:13:38] bởi vì kiểu mình muốn nó kiểu nó phải
[00:13:42] rộng ra nó phải rõ ràng hơn ấy. Còn nếu
[00:13:44] mà chỉ trả lời ngắn gọn thì à thực ra
[00:13:47] đấy còn không phải là câu hỏi cơ nhở,
[00:13:49] chỉ là câu kể thôi. Nhưng mà nếu mà mình
[00:13:52] trả lời ngắn gọn quá thì nó
[00:13:55] kiểu dạng
[00:13:57] nó không nói rõ được cái cái con người
[00:14:00] hay suy nghĩ của mình đã nghĩ đúng không
[00:14:03] ạ?
[00:14:05] Làm sao? Đôi khi chia sẻ tôi nghĩ là mấy
[00:14:07] ông có thể thấy thích à ít nhất là
[00:14:10] thoáng nghe tôi thì sẽ thích nghe tôi
[00:14:13] bởi vì à dễ ngủ à không biết được từ
[00:14:16] nghe tôi để mà à không để ngồi làm việc
[00:14:19] nó vừa ngồi code nó vừa ngồi nghe tôi à
[00:14:22] không nhưng cái đoạn đấy là đoạn tâm sự
[00:14:24] chứ không phải đoạn này không phải một
[00:14:26] cái đoạn ngồi chia sẻ kiến thức nhưng mà
[00:14:28] tôi nghĩ là tôi chia sẻ kiến thức cho
[00:14:30] mấy ông cũng có lúc hay có rất nhiều lúc
[00:14:33] có mấy ông
[00:14:35] nói lại tôi nói lại dùng tới nói lại nó
[00:14:38] không đúng lắm đại khái là kiểu kiểu
[00:14:41] ngồi sửa cho tôi ấ tôi thấy là sửa chứ
[00:14:43] không phải ném đá đâu. Tôi thấy ít ra
[00:14:45] chưa trên kênh tôi chưa có ai ném đá
[00:14:47] chắc mình cũng chưa đổi nổi tiếng nhưế
[00:14:48] thế chưa có đi fan đấyan
[00:14:52] đấy thì
[00:14:54] trên này thực không phải fan cơ trên này
[00:14:56] mấy ông chẳng phải fan của tôi chưa phải
[00:14:58] thần tượng hay hâm mộội gì cả người
[00:15:00] thường với nhau cả chẳng qua là mình
[00:15:02] kiểu thấy vui vui vui. Đầu tiên là chắc
[00:15:04] là tôi thấy là mấy ông biết tôi qua vui
[00:15:06] vui vui kiểu
[00:15:09] ờ kiểu dạng tự nhiên thấy có một ông à
[00:15:13] đăng trên J2 thì thấy là hay kêu là miễn
[00:15:16] phí rồi. Thôi vào xem có cái gì đấy.
[00:15:23] nghe. Ồ, kiểu mấy ông bật lên tôi thực
[00:15:27] ra là tôi sợ mấy ông phân tâm thôi chứ
[00:15:29] bình thường là tôi ngồi code thì tôi
[00:15:31] không ngồi nghe ai nói cả mà tôi sẽ
[00:15:33] thường khi mà tôi ngồi code thì tôi sẽ à
[00:15:36] gần đây không vai vai gần đây vai code
[00:15:38] nhiều hơn không ngồi code mấy nữa nhưng
[00:15:41] mà cũng mở nhạc nó nhẹ nhẹ để mình suy
[00:15:45] nghĩ
[00:15:51] thứ cho nó không anh Ở bạn có thể xem a
[00:15:57] video hôm video ngay video trước của
[00:16:00] mình mình có nhắc về bộ set kit rồi các
[00:16:04] thứ thứ cũng nhiều phết dùng antigravity
[00:16:07] kit xong rồi kiểu thêm ru thêm skin.
[00:16:10] Nhưng mà hôm trước là tôi dùng chính con
[00:16:12] AI này tôi ngồi đọc cả cho nó đọc mấy
[00:16:14] cái bộ nghĩa là cái kit đấy bản chất là
[00:16:17] gồm à
[00:16:20] skin này, workflow này với ru này còn gì
[00:16:26] nhá.
[00:16:27] Tạm thời tôi nhớ thế.
[00:16:30] Ngồi ngồi đọc mấy cái đấy xong rồi đọc
[00:16:33] project của tôi xong rồi sửa lại cái
[00:16:34] đống đấy để cho nó hợp lý và tôi đẩy
[00:16:36] lên. Và mấy ông này thực ra là cũng thể
[00:16:39] trách mấy ông ấy được. Tức là mấy ông ấy
[00:16:41] tạo ra một cái thư mục ví dụ thằng này
[00:16:44] thì nó sẽ tạo ra thư mục là chấm agent
[00:16:46] đúng không? Thằng khác thì tạo thư mục
[00:16:48] ví dụ core là chấm cusor, thằng winsert
[00:16:51] là chấm winsert. Thằng khác nữa thì tôi
[00:16:54] chưa dùng nhưng đại khái mỗi thằng tạo
[00:16:55] ra một cái thư mục ru à thư mục riêng
[00:16:58] của nó. Xong rồi nó có chấm thư mục
[00:17:00] thường là nó vẫn sẽ có những thư mục
[00:17:01] rule, skin, rflow nan nào giống nhau. Có
[00:17:04] thằng khác mỗi tên thư mục thôi nhưng mà
[00:17:06] đều là file ma down mà đúng không? Thế
[00:17:08] tôi ức chế quá hôm trước tôi làm quà tôi
[00:17:11] nhờ AI ngồi custom lại đúng không? Tôi
[00:17:13] tạo hẳn một thư mục là chấm.
[00:17:16] Xong rồi tôi tạo sim link. Mấy ông cho
[00:17:19] biết khái niệm này. Sim link
[00:17:28] này đúng không? Thì hiện tại antiravity
[00:17:30] nó sẽ có thư mục chấm agent xong rồi
[00:17:34] gạch chéo ru. Đúng chưa? Đấy thằng CO nó
[00:17:36] cũng sẽ kiểu như thế nhưng chẳng qua nó
[00:17:38] là chậm coo ở đây đúng không? Đấy.
[00:17:44] Đấy. Tôi tôi tạo một thư mục là đấy
[00:17:50] ch ru như này. Đấy. So những cái thằng
[00:17:53] này nó là sim link tức là nó sẽ kiểu bản
[00:17:56] chất là nó nối à nó kiểu gọi là trỏ đến
[00:18:00] cái thư mục góc kia kìa. Bởi vì trong
[00:18:02] công ty của tôi là có
[00:18:06] người dùng CO, có người dùng Cloue, tôi
[00:18:09] thì dùng à Winser à dùng ừ tôi hồi trước
[00:18:15] tôi cũng dùng Winser còn bây giờ dùng
[00:18:16] antigravity. Đấy thì tôi xét luôn bộ
[00:18:19] rule ở trong này xong tôi kết nối hết
[00:18:21] mấy thằng tròn như đây. Xong đấy.
[00:18:25] Tôi còn đang định làm cái plugin cơ. Hôm
[00:18:27] trước có một ông chia sẻ ở trong nhóm
[00:18:30] nhóm antigravity à Việt Nam đấy. Xong
[00:18:33] người chia sẻ cái extension. Tôi nghĩ là
[00:18:36] tôi sẽ ngồi vai code hẳn một cái
[00:18:38] extension rồi tôi đẩy lên xong rồi à làm
[00:18:41] mấy cái kiểu đồng bộ với cái vụ kiểu như
[00:18:43] này. Tại vì thằng Antigravity này nó có
[00:18:46] cái tạo ra cái plan đúng không? Hôm
[00:18:48] trước mấy ông thấy á nó tạo ra mấy cái
[00:18:51] plan nó cái luồng suy nghĩ các thứ thứ
[00:18:53] này này. Đây không biết được là trong
[00:18:57] cộng này còn không.
[00:19:00] Đây đây đây. À không
[00:19:02] tôi bảo nó ghi thẳng vào rồi.
[00:19:06] Đại khá là đôi khi thằng này có luồng
[00:19:08] suy nghĩ nó sẽ tạo ra một cái file M
[00:19:10] down
[00:19:13] nêu lại nó đang nghĩ gì nhưng nó lại lưu
[00:19:16] ở trong cái thư mục chấm Gemini ở ngoài
[00:19:19] user ấy. Đấy tôi muốn và nó sẽ bị nhược
[00:19:22] điểm là sao? Ông đổi máy tính. Ví dụ tôi
[00:19:25] dùng cả máy tính công ty, dùng máy tính
[00:19:27] cá nhân thì khi tôi đổi máy tính là coi
[00:19:29] như là tôi sẽ không có cái file đấy vì
[00:19:31] file đấy đang nằm trong thư mục ngoài.
[00:19:32] Ông hình dung giống như là trong thư mục
[00:19:34] của system ổ C ấy. Đấy thì rõ ràng là có
[00:19:38] một cái tiện ích đồng bộ. Hôm trước là
[00:19:41] có anh chia sẻ cái tiện ích đấy đấy
[00:19:43] nhưng mà tôi dùng tôi bị lỗi. Tôi nghĩ
[00:19:45] là tôi sẽ tự việt hẳn tiện ích diệc lấy
[00:19:48] ý tưởng anh đấy và làm thêm cái quả đồng
[00:19:51] bộ mấy cái ru rủng này này n vân vân rất
[00:19:53] nhiều cái nữa. Chắc là kiểu gì sẽ có
[00:19:56] người viết rồi. Nhưng mà bây giờ mình có
[00:19:59] hay tự code thôi.
[00:20:02] Ngày xưa sinh viên trường ông có đào tạo
[00:20:05] Java không mà khổ như vậy?
[00:20:09] Tôi học BTIS full Java, giờ chỉ học
[00:20:12] sping là ổn rồi, không phải học lại Java
[00:20:13] con nữa. Tôi cũng xuất thân từ Laria.
[00:20:16] Trường tôi có dạy Java nhưng mà trường
[00:20:18] tôi là trường nghề. Trường tôi dạy PP
[00:20:20] trước xong rồi làm dự án bằng project dự
[00:20:23] án dự án một, dự án hai bằng PP. Đấy,
[00:20:27] xong rồi. Hồi đấy còn không có Larel để
[00:20:30] à La Larel hồi đấy quá cũ à không phải
[00:20:33] quá mới kiểu Lel hồi đấy là Laro 5 hay
[00:20:37] không nhớ L mấy PP ở đây PP 5.6 sáu gì
[00:20:41] vậy mà đại khái thì h đấy lại không dùng
[00:20:45] chỉ dạy về PP MVC và một tí thôi xong
[00:20:50] rồi làm dự án xong rồi
[00:20:53] 52 nhá xong rồi đã đi làm đi thực tập
[00:20:55] rồi đấy 53 thì những bạn nào mà không
[00:20:58] theo được không kiểu không đi thực tập
[00:21:01] được rồi
[00:21:02] thì mới ở lại trường để học th tiếp thì
[00:21:05] sẽ học Java và học Android đấy đương
[00:21:08] nhiên là tôi cũng có học Java cả Java
[00:21:10] Java 1, Java 2 phải đấy học code để thi
[00:21:13] thôi chứ không bởi vì mình đi được tầm
[00:21:15] mình đi làm rồi mình đang làm PP các thứ
[00:21:17] hồi đấy còn ngon lành thì rõ ràng là tự
[00:21:20] nhiên chuyển qua học Java để làm dự án
[00:21:24] Java làm gì đúng không?
[00:21:37] mà giờ nhìn ông học Java co khổ quá
[00:21:40] không khổ gì đâu. Tôi học cũng chỉ để
[00:21:43] kiểu
[00:21:45] tôi không tôi không nghĩ là khổ. Đầu
[00:21:48] tiên là mình phải tư tưởng thế đã mình
[00:21:51] không cảm thấy mệt, mình không cảm thấy
[00:21:52] khổ. Mình cảm thấy nó bình thường đấy.
[00:21:55] Thứ hai là học nhanh mà ông th xem mấy
[00:21:58] video trước của tôi có thể hơn tiếng như
[00:21:59] thự ra tôi ngồi nói chuyện như này nhiều
[00:22:01] đấy. Họ cũng không nhiều lắm đâu. Đương
[00:22:03] nhiên là nghe 100 ngày cũng nhiều. Xong
[00:22:06] rồi mình mỗi buổi mỗi buổi lẻ tẻ lẻ tẻ
[00:22:09] nó bị kiểu tốn thời gian đúng. Nhưng mà
[00:22:11] tôi thứ nhất là nó đang chưa quan trọng
[00:22:14] là mình cần ngay. Thế nên là tôi sẽ cảm
[00:22:17] thấy mình thưa thưa mình cứ học dần học
[00:22:19] dần để mình biết.
[00:22:21] Bởi vì cái đầu tiên ấy, cái đầu tiên tôi
[00:22:23] thấy cốt lõi nhất ấy đó là mình làm cho
[00:22:26] tư tưởng của mình đó là ham học là kiểu
[00:22:30] mình phải học một cái gì đó hàng ngày.
[00:22:32] Tránh cái việc là mình bị thụ động quá
[00:22:34] mỗi ngày qua ngày mà thực ra mình không
[00:22:36] có thêm kiến thức gì mới. Đấy mới là cái
[00:22:39] mà tôi cảm thấy là về sau nó sẽ gây khổ
[00:22:41] mình đúng không? Đấy, còn mình học hàng
[00:22:43] ngày và nó có áp dụng thật mà nó tốt
[00:22:46] chẳng sao. Có thể là chưa áp dụng được
[00:22:49] ngay bởi vì mình chưa dùng Java. Nhưng
[00:22:51] mà thứ nhất là hôm trước tôi ngồi đọc
[00:22:54] cái kia tôi cảm thấy hay này về mấy vụ
[00:22:57] bộ nhớ này PP nó không để ý lắm vụ này.
[00:23:07] ai cũng ai ở trên công ty tôi cũng thấy
[00:23:09] bỡ ngỡ khi mà tôi cảm thấy là tôi giành
[00:23:11] về mấy cái vụ AI này hơn mọi người th là
[00:23:13] tôi không dành lắm đâu. chẳng qua là
[00:23:17] tôi xin cảm ơn Facebook vì gần đây thay
[00:23:19] đổi thật toán toàn cho tôi đề xuất những
[00:23:22] cái bài mà tôi không hề theo dõi kiểu
[00:23:25] những cái người lạ hoàn toàn ấy nhưng mà
[00:23:26] đều nhắc đến AI này đều nhắc đến gì đó
[00:23:29] thì mình dù mình cóo hay không kiểu
[00:23:35] tôi dạo này dùng từ nhiều nhưng tôi
[00:23:37] không biết nói câu này gì dù mình có
[00:23:40] [khịt mũi] gì sợ bị à
[00:23:44] sợ bị gọi là lỗi thời à chạy đua hay
[00:23:48] không vân vân thì mình vẫn
[00:23:53] tôi tôi không sợ hẳn là mình bị lạc hậu
[00:23:55] đến thế nhưng mà chỉ kiểu thấy đầu tiên
[00:23:58] là thấy trên trang chủ mình hay mình đọc
[00:24:02] và mình ngẫm đấy xong mình tự nhiên mình
[00:24:05] biết thôi xong mình cũng tìm hiểu thêm
[00:24:07] là mình cũng áp dụng cho công việc của
[00:24:09] mình hồi trước thì chắc là ông biết tôi
[00:24:13] từ thời đầu rồi tôi còn dùng
[00:24:16] chỉ PP Stone kiểu
[00:24:19] VS code hay nào không quan tâm PP Stone
[00:24:22] chân đấy đây chuyển qua mà khi một khi
[00:24:26] mà mình mở cái đầu mình ra sẵn sàng chủ
[00:24:29] qu chuyển qua rồi ấy mấy cái này không
[00:24:32] tôi không ngại thay đổi ví dụ hôm trước
[00:24:34] dùng antiity bất ôi chuyển lại Winsert
[00:24:38] Winsert thầy tốn tiền quá chuyển qua
[00:24:41] cusa đấy tôi chưa qua CL La code thôi vì
[00:24:45] nó vẫn thiên hướng không phải là code mà
[00:24:47] nó là ông ra lệnh nó nhiều nó là cái
[00:24:49] giao diện của terminal ra lệnh thôi.
[00:24:59] Ừ thực ra là ý ông ấy khổ đây ám chỉ
[00:25:01] chắc là ám chỉ là hôm trước thì ông ấy
[00:25:04] may mà ông ấy đã được học trước các thứ
[00:25:06] thứ gọi là bây giờ áp dụng ổn. Còn mình
[00:25:08] thì anh em mình là PP sắp chết rồi mà PP
[00:25:13] thì mình bị lỗi thời rồi đấy. Mình phải
[00:25:16] chuyển qua nhanh không thì hẹo. Đấy cũng
[00:25:19] có cái bất cập mà. Ơ bây giờ giả sử PP
[00:25:23] còn là vua chắc là tôi không.
[00:25:26] Ừ, chắc tôi vẫn sẽ học Java đấy. Nhưng
[00:25:29] mà để mà củng cố kiến thức PP kiểu OOP
[00:25:32] thôi. OP và nhưng mà tôi bảo rồi, Java
[00:25:35] này vẫn sẽ có những cái hay nó là
[00:25:38] hôm trước sếp tôi đã từng hỏi cái câu
[00:25:40] đấy rồi bá. Nếu mà anh hỏi em ở không
[00:25:43] phỏng vấn, nếu anh là người phỏng vấn
[00:25:44] em, có khi em không đu phá công ty mua
[00:25:47] tội may là xếp tôi vào sau tối. Anh đấy
[00:25:50] là anh leader hồi đầu công ty tôi bé thì
[00:25:53] không có một leader thật sự mà chỉ có
[00:25:55] anh CTO thôi. Vì sao công ty to ra thì
[00:25:57] như là tuyển thêm một anh PM, một anh
[00:25:59] leader về đúng không? Đấy thì ý tôi là
[00:26:03] cái anh đấy anh đấy hỏi tôi bảo là đây
[00:26:07] em thử trả lời câu ấy ừ mấy ông ở đây có
[00:26:10] để thử hỏi mấy ông nhá không không chơi
[00:26:12] cha mạng nhá đấy đó là interface khác gì
[00:26:16] phải up check cl đấy anh ấy bảo hỏi câu
[00:26:18] đấy
[00:26:20] tôi đương nhiên tôi đưa ra những cái ví
[00:26:22] dụ có rồi xong rồi anh em bảo không thế
[00:26:24] em chưa hiểu rõ về cái cốt lõi về bản
[00:26:28] chất các thứ các thứ
[00:26:34] luôn PP không dùng
[00:26:37] thậm chí là không dùng cả hai vẫn code
[00:26:40] được đúng không ạ? Đương nhiên mình
[00:26:42] không thể chơi cùn là kiểu dạng thích
[00:26:44] cái em không dùng á MVC em không dùng PP
[00:26:46] à không dùng Oop em dùng thuần code được
[00:26:50] đúng không? Nhưng mà đang nói là đúng
[00:26:52] nghĩa là nếu mà làm PP nhiều ông sẽ biết
[00:26:55] rất ít dự án dùng interface. Tôi đấy là
[00:27:00] góc nhìn tôi tôi biết nhá. Rất ít dự án
[00:27:03] PP dùng interface
[00:27:05] ABCK class thì tôi từng thấy rồi nhưng
[00:27:07] mà thường theo mang tiếng là class xong
[00:27:10] rồi kiểu extend nhau xong rồi kiểu kiểu
[00:27:13] kế thừa nhau mà hóa dùng chết nhiều đúng
[00:27:15] không? Đấy dùng chết là rất là nhiều.
[00:27:18] Tôi thấy lạm dụng chết luôn đấy. Hồi
[00:27:20] trước tôi cũng từng lạm dụng quả object
[00:27:22] class xong rồi cứ kế thừa kế thừa xong
[00:27:24] rồi về sau nó bị ấ à kiểu mình cố gom
[00:27:28] mấy cái gì chung chung mình cho cái
[00:27:32] class to class cha xong rồi các thứ thứ
[00:27:34] thế rồi về sau ôi cốt rồi vãi xấu vãi.
[00:27:37] lúc đấy mới thì bây giờ mới bắt đầu nhận
[00:27:39] ra dần về interface nó có vẻ hay hơn.
[00:27:49] cái đấy và phân biệt được rõ luôn. Mấy
[00:27:52] ông có thể câu thấy câu đấy dễ nếu mấy
[00:27:54] ông đã từng học Java. Còn tôi cứ cho là
[00:27:57] tôi mất gốc Java nên là thì khó
[00:28:01] hả? Học dốt á.
[00:28:04] Java Java 2 của anh hình như là được 9
[00:28:06] hay được 10 đấy.
[00:28:09] Ô nhờ tí tôi sẽ tìm lại cái bảng điểm
[00:28:13] à [hắng giọng] của tôi. Sếp tôi khoe là
[00:28:18] bảng điểm đại học của sếp rất sáng.
[00:28:21] Bảng điểm đại học của tôi cũng sáng. Tôi
[00:28:23] nhớ tôi được 10 phẩy chính trị với 9
[00:28:26] phẩy à đốc 9 phẩ luật với 10 phẩ chính
[00:28:28] trị thì phải
[00:28:38] thì chạy sang mấy cái đấy nhưng ý tôi là
[00:28:40] mấy cái kiểu nó liên quan đến Hàn Lâm à
[00:28:43] không hàn lâm kiểu triết lý hay vân vân
[00:28:46] có gì đấy mình cũng thấm được mà mình
[00:28:50] cứ gọi là mình à mấy cái đấy
[00:28:53] với mình cũng không tính là khô khan nó
[00:28:55] vẫn hiểu được
[00:29:06] video mai xem lại chúc anh học tốt ạ em
[00:29:09] cũng đi học đây được em ơi chúng ta cùng
[00:29:12] học hôm nay tôi còn nghỉ cuộc chơi đị để
[00:29:16] ngồi học cơ mà từ chối cuộc chơi để học
[00:29:18] kiểu
[00:29:20] anh em cũng c thấy bột cưới đúng
[00:29:25] tôi thấy tôi nhớ được đống này rồi ạ tôi
[00:29:28] thấy tương đối nhớ cùng lắm mà string
[00:29:30] builder string buffer này hôm trước ngày
[00:29:32] chưa thể xem ạ
[00:29:35] bất biến này
[00:29:38] cái nào bất biến string m khai báo như
[00:29:41] này bất biến ok string mới không sửa
[00:29:45] string cũ
[00:29:48] tạo giác
[00:29:57] sẽ chèn thêm kiểu gọi hàm để builder mà
[00:30:00] đúng không? Nó giống như kiểu SQL
[00:30:02] builder ừ để mà kiểu chèn thêm các thứ
[00:30:05] thứ. Còn string buffer là vừa kết hợp
[00:30:08] builder cộng với trve. À đúng rồi. Hôm
[00:30:11] trước nhắc về vụ trap save này tức là
[00:30:13] khi mà xử lý bất đồng bộ thì nó tránh bị
[00:30:15] lỗi kiểu khi mà giá trị nó thay đổi đúng
[00:30:18] không? [khịt mũi]
[00:30:20] Nhưng mà chậm hơn string builder đúng
[00:30:22] không? Còn đây string này là string
[00:30:24] thuần nhỉ? Khai báo như này cộng thêm.
[00:30:35] Nhưng mà cái này có lưu vào ghi đè bộ
[00:30:38] nhớ không? ghi đè vào cái a địa chỉ bộ
[00:30:43] nhớ đấy không nhỉ? Chắc là có chứ đúng
[00:30:45] không? Khách báo như này ghi đè vào địa
[00:30:47] chỉ bộ nhớ.
[00:30:50] Nếu thế sao lại tốn chuỗi chuỗi nhiều à
[00:30:54] sao tốn bộ nhớ và chậm nhỉ
[00:31:04] nghĩa là bị lặp à kiểu một cái là hello
[00:31:08] một cái hello world ở hai chỗ khác nhau
[00:31:10] à
[00:31:19] đúng không? Ừ. Đấy kêu tặng một cái mới
[00:31:22] thế
[00:31:25] đúng là học Java sầu mới biết cái này
[00:31:28] chứ với PP chắc là tôi nghĩ hai kiểu nó
[00:31:32] lưu vào cùng chỗ đấy đúng không?
[00:31:37] Ok.
[00:31:38] Thế mà hôm trước mình không thắc mắc
[00:31:39] này. Đấy n đôi khi phải ôn lại để mà
[00:31:41] kiểu
[00:31:43] thắc mắc thêm.
[00:31:49] code để mà còn in ra mấy cái gì đó này
[00:31:53] mình còn chưa làm vụ chạy code á.
[00:31:56] Để hôm sau tôi sẽ ngồi hôm sau không
[00:31:59] biết hôm sau hôm nào nhưng hôm sau
[00:32:03] còn cả hit và stack này nữa. Stack ngon
[00:32:06] set này. Lưu chữ biến cục bộ tham chiếu
[00:32:11] method core frame. Thực ra hôm trước
[00:32:13] không để cái quả này. Hôm trước tôi nhớ
[00:32:15] là hôm trước anh em đã tôi đã cùng anh
[00:32:18] em để ngồi soạn cái quả này. Đợi tôi một
[00:32:21] tí. Tôi nhớ hôm nấy là tôi
[00:32:25] dùng cái napkin à napkin AI để ngồi soạn
[00:32:29] và cũng ngồi khoe với cái napkin này.
[00:32:50] trong Java stack và hip. Tài liệu này
[00:32:53] trinh bày chi tiết về cấu trúc bộ nhớ
[00:32:54] tập trung vào hai phần chính stack và
[00:32:56] hip. Đấy và là trong Java bộ nhớ chia
[00:33:00] nhiều phần hai phần quan trọng nhất là
[00:33:02] stack qu hi được sử dụng để lưu chữ biến
[00:33:05] cục bộ tham số phương thức và địa chỉ
[00:33:07] trả về của phương thức.
[00:33:09] Phương thức ở đây method đúng không? Nó
[00:33:11] hoạt động theo nguyên tắc lain first
[00:33:14] out. Đúng rồi. Stack đúng rồi.
[00:33:24] và m
[00:33:26] việc quản lý bộ nhớ hip được thực hiện
[00:33:28] bởi
[00:33:31] Git collector
[00:33:34] chức năng của cái tôi nhớ không nhờ lầm
[00:33:38] là cái Rabit.
[00:33:41] collector này nó còn là
[00:33:45] còn được nhắc đến ở trong PP không nói
[00:33:47] nhá trong ngữ lập trình không nói nhá
[00:33:49] tôi nhớ là còn [khịt mũi] hình như hình
[00:33:51] như là được nhắc đến vào trong SQL phải
[00:33:53] có đúng không nhỉ
[00:33:56] hay là thằng khác nhỉ nhóm m máng là thế
[00:33:59] thì thử hỏi lại cái này
[00:34:06] sau lưu chữ biến cục bộ
[00:34:11] chữ tham số phương thức
[00:34:13] tham số của method đúng không gọi là
[00:34:16] parameter rồiấy đúng không
[00:34:23] nhớ khi một phương thức được gọi tham số
[00:34:26] được truyền chữ stack ok chữ địa chỉ trả
[00:34:30] về khi một phương thức kết thúc chương
[00:34:32] trình cần biết địa chỉ để quay lại
[00:34:34] phương thức được gọi
[00:34:41] tiếng Việt nó mấy ông thấy là nó cũng
[00:34:45] gọi nhá. Không được dễ nhìn thấy lắm
[00:34:48] đúng không?
[00:35:01] rồi nhưng mà tiếng Việt trên này không
[00:35:04] dễ nhìn lắm nhỉ.
[00:35:14] vãi chưởng. Đ gọi một stack fame được
[00:35:19] tạo trên stack. Ui, cái này chịu cái này
[00:35:23] phải làm mới biết được rồi.
[00:35:30] Mình
[00:35:32] cái tiện ích này của tôi đang tự đập bật
[00:35:35] ạ. Tiếp nhá. Đợi tôi tắt cái này đi.
[00:35:49] Đây bấm R AI này là xong. Đấy ra lệnh nó
[00:35:53] giống viết nó một prom mà nó sẽ tự viết
[00:35:56] cho mình cái tài liệu như này. Đấy xong
[00:35:58] rồi mình bôi toàn bộ như này x ấn nút
[00:36:01] này này là nó sẽ tạo cho mình cái một
[00:36:05] cái sơ đồ ở dưới như này. Xịn không? Cái
[00:36:07] này ch hồi trước tôi dùng chuyên để viết
[00:36:09] tài liệu dạy học với tạo cái ảnh ở dưới
[00:36:13] thì mình nhúng vào PowerPoint đúng
[00:36:14] không? PowerPoint mình ít chữ thôi, chỉ
[00:36:16] có ảnh thôi. Đấy,
[00:36:19] có tài liệu
[00:36:21] đúng không? Vừa làm tài liệu Doc, vừa
[00:36:25] làm tài liệu PowerPoint
[00:36:28] hả?
[00:36:29] Đấy
[00:36:32] ví dụ à
[00:36:34] đợi tôi dicate này tránh lỗi
[00:36:38] đấy. Ví dụ là
[00:36:41] à
[00:36:47] generic
[00:36:49] trong Java. Thế này xong đây tự viết hết
[00:36:56] kể cả tiếng Việt rất đỉnh.
[00:36:59] Tôi dùng cái này từ
[00:37:01] kiểu bây giờ là chắc là
[00:37:05] cũng gần 2 năm rồi phải gần 2 năm.
[00:37:09] Đó xong. Ok chưa?
[00:37:12] Đấy xong rồi. Ấn ông đương nhiên ông bơi
[00:37:15] từng đoạn này ông thể tạo được nhá.
[00:37:17] Nhưng mà bôi tất cả này ấn tạo này. Và
[00:37:19] nó miễn phí đúng không? Đấy miễn phí
[00:37:21] nhá. Không mất đồngo cả. Đương nhiên là
[00:37:24] khi mà đấy nó tạo ra cho ông rất nhiều
[00:37:26] cái kiểu như nàyi để mà ông có thể
[00:37:45] đây sửa được nó nhá. ở đây sửa được này.
[00:37:48] Hay đủ các thứ thứ này.
[00:37:56] mình export ra mình thể chọn này. Tôi
[00:38:00] thường ha chọn độ phân giải cao này
[00:38:04] không có background để mà mình khi mà
[00:38:06] mình copy ấ
[00:38:08] khi copy ra
[00:38:10] đây copy ra ảnh nó sẽ rất là nét đấy.
[00:38:13] Kiểu thế tốt
[00:38:15] đấy. Không background nhá. Không có có c
[00:38:18] thì để mình copy ra chỗ khác mà thì nền
[00:38:21] nó sẽ là nền BNG mà nó sẽ nền trong
[00:38:23] suốt.
[00:38:25] Ngon mà miễn phí. Đương nhiên là hồi
[00:38:28] trước là nó không có logo cơ. Gần đây nó
[00:38:30] cho thêm logo mất tiền chỉ tắt đi cái
[00:38:33] logo là quá quá rẻ nhở.
[00:38:45] napkin AI nhá. Nakin. Đấy con này đang
[00:38:49] miễn phí đấy. Không biết được mấy ông
[00:38:51] đăng ký tài khoản bây giờ thì nó như
[00:38:54] nào. Tôi thì đăng nhập bằng tài khoản
[00:38:56] Google lâu rồi. Không biết là bởi vì tôi
[00:38:59] còn từng chat với bên đấy cơ để nói
[00:39:01] chuyện kiểu thoải mái lắm. Hồi trước
[00:39:03] từng chat mấy lần thì không biết được
[00:39:05] bên này có tạo điều kiện cho nick tôi
[00:39:08] hay không. Không biết được.
[00:39:10] Mấy ông có thể dùng thử mất tiền thì
[00:39:12] thôi. Còn nếu mà miễn phí thì rõ ràng là
[00:39:15] mình
[00:39:17] tiện mình dùng đúng không?
[00:39:19] Vậy thì đang học bên này à kích thước cố
[00:39:23] định này được xác định khi chương trình
[00:39:25] khởi động. Nhớ cố gắng tạo à đây stack
[00:39:30] flow. Ok.
[00:39:33] Đ hiểu này.
[00:39:36] Ồ. Tại sao không ai nói mình đoạn này?
[00:39:40] Không không học m cái này.
[00:39:48] JVM. Jv
[00:39:56] học là stack với các thứ h stack thôi.
[00:40:01] Ừ. Stack với hip.
[00:40:02] &gt;&gt; Mấy cái đấy ấ dụ nó chỉ kiểu lý thuyết
[00:40:05] thôi. Còn khi nào mà nó đi làm
[00:40:07] &gt;&gt; đúng anh anh nghĩ là kiểu nó có thể là
[00:40:11] có thể là nhiều người làm rồi cũng không
[00:40:14] nhưng mà
[00:40:15] &gt;&gt; đế án đi làm sao còn bình thường mà nếu
[00:40:19] mà không thì cũng chỉ đọc lý thuyết
[00:40:21] thôi.
[00:40:22] &gt;&gt; Có bây giờ có ai có thể báo đưa ví dụ
[00:40:24] hiệu cũng chỉ học thuộc thế. Ừ anh nghĩ
[00:40:28] là hồi này anh cũng học trên trường rồi
[00:40:30] nhưng anh quên xử hết rồi có nhiều đâu.
[00:40:34] &gt;&gt; Còn stack thì đương nhiên biết về khái
[00:40:36] niệm l in first out phải có stack với
[00:40:38] kill khác nhau như nào?
[00:40:46] đúng bạn đấy cũng a
[00:40:49] bạn ấy cũng làm à à công nghệ thông tin
[00:40:52] nhưng bạn ấy làm Java nên tôi bảo bạn
[00:40:56] ngồi học cùng thì bạn ấy còn chỉ được à
[00:41:00] bạn
[00:41:01] ấy làm mà
[00:41:04] thực ra là tôi để công khai trên
[00:41:05] Facebook chẳng qua mấy không để ý tôi ấ
[00:41:07] à có khi mấy cũng không biết Facebook
[00:41:09] tôi nhỉ quên mất
[00:41:17] nhớ.
[00:41:19] Chắc là người ta khi phỏng vấn tôi không
[00:41:20] hỏi mấy câu đấy đâu. Bây bây giờ bây giờ
[00:41:24] tôi sang kia tôi không phải phỏng vấn
[00:41:25] theo dạng là kiểu đấy. Thực ra đấy nhược
[00:41:28] điểm đấy. Không biết mấy ông đã bị dính
[00:41:30] cái đấy chưa? Bây giờ mình kêu là mình
[00:41:32] là senior. Cứ giả sử thế đi. Có cái mio
[00:41:35] đi. Sino pp
[00:41:37] xong rồi sang khác là đi phỏng vấn fer
[00:41:40] Java à cũng không được đúng không? Mình
[00:41:43] phỏng vấn thấp nhất. Thấp nhất nhá. Tôi
[00:41:45] nghĩ phải middle đấy. Thấp nhất
[00:41:49] midle thì người ta chắc là sẽ không hỏi
[00:41:51] mấy câu này đâu. JVM là cái gì
[00:41:54] [tiếng cười]
[00:41:55] đúng không?
[00:42:01] là nhược điểm của anh em trong a ngành
[00:42:05] này hiện tại. Đấy gần đây là tôi có biết
[00:42:07] đấy. Ví dụ xếp tôi bây giờ lead này. Đấy
[00:42:11] bây giờ sang bên công ty khác một là làm
[00:42:13] lead, hai là phải làm to hơn cao hơn là
[00:42:16] sang công ty khác đi làm nhân viên thì
[00:42:18] thực ra là người ta kiểu thắc mắc ý kiến
[00:42:20] ấy. Lương cũ của mày như nào mà bây giờ
[00:42:23] mày có thể chấp nhận lương có thể trả
[00:42:25] bằng 1/3 đến thế chẳng hạn. Thế
[00:42:31] đấy người ta sẽ thắc mắc rất nhiều cho
[00:42:33] dù rõ ràng mình thì thực ra mình chỉ cần
[00:42:35] có việc thôi đúng không? Mình cũng đuối
[00:42:38] đuối rồi đi. Đấy, mình cũng không thể
[00:42:40] nào nhanh nhạy được bằng cái mới. Đấy,
[00:42:53] thì cố góp vốn rồi đi mở một cái gì đó,
[00:42:56] thậm chí mở công ty, mở setup. Đấy, mở
[00:42:59] set up thì khi mà sát nhăn nhàn thực ra
[00:43:01] tỉ lệ thành công nó cũng không phải cao
[00:43:03] nữa.
[00:43:10] Ví dụ là cái này cũng nằm trong stack
[00:43:12] đúng không? Cái biến cục bộ nằm trong
[00:43:15] stack này. Cái biến này trả về từ method
[00:43:19] cũng nằm trong stack đấy. Tôi nhớ không?
[00:43:22] Ừ.
[00:43:23] Ok. Cái này cũng nằm trong stack này
[00:43:26] đúng không?
[00:43:28] Nhưng mà tôi nhớ là hôm trước có cái này
[00:43:30] nếu mà khai báo nó là
[00:43:32] [khịt mũi] wrapper class đúng không? Thì
[00:43:35] nó nằm trong hip à?
[00:43:38] Đúng rồi. Nó nằm trong hip đúng không?
[00:43:45] [khịt mũi]
[00:43:52] được tạo trên stack trừ các biến xy res
[00:43:56] khi phương thức add kết thúc stack bị
[00:43:58] khó xóa khỏi stack được. Nó giống như PP
[00:44:02] này nghĩa là kiểu kết thúc cái method
[00:44:05] thì sẽ xóa nó khỏi bộ nhớ cho nhẹ. Đấy.
[00:44:10] Ừ. Thì bên Java làm quản lý bộ nhớ tốt
[00:44:12] phết nhở.
[00:44:15] &gt;&gt; Cuối cùng khi phương thức main kết thúc
[00:44:16] cũng m stack frame đấy chính là main này
[00:44:20] đúng không? Cũng xóa. Ừ toàn bộ biến cục
[00:44:22] bộ xóa. Ok hợp lý đấy. Bởi vì bản thất
[00:44:27] bản chất cái main này cũng là một method
[00:44:29] mà đúng không?
[00:44:31] Ồ ok.
[00:44:34] Hôm trước không học sâu thế này đâu. Hay
[00:44:37] lưu lưu để thôi. Không biết mình lưu cái
[00:44:40] này kiểu gì. Mình export này ra lưu kiểu
[00:44:42] gì nhỉ?
[00:44:45] Cái này copy cái này copy vào không ổn
[00:44:48] đâu. Copy vào đây.
[00:44:53] Copy vào bị xấu ấy.
[00:45:02] Cái có nhược điểm nhá. Cái này tôi chúng
[00:45:04] ta không bấm edit được.
[00:45:20] đợi tôi một tí, tôi sẽ tạo hẳn một cái
[00:45:22] mới.
[00:45:34] tập trung vào học architect hệ thống hay
[00:45:37] vẫn từ co
[00:45:40] đi lên như ngày xưa. Anh
[00:45:43] thực ra là cái câu của em đã phản ánh
[00:45:46] phần nào rồi thứ nhất là em đang lo. Thứ
[00:45:48] hai đó là kiểu em đang em chưa phải là
[00:45:51] người nắm kiểu co mà đúng không? Nên
[00:45:54] mình kiểu đang nghĩ là thôi mình cắm đầu
[00:45:56] học tiếp. Hai là mình chuyển h chuyển
[00:45:59] dần dần đúng không? Thứ hai đó là
[00:46:12] đã là một cái nó không ổn ở trong cái
[00:46:15] ngành công nghệ thông tin này rồi. Bởi
[00:46:17] vì ngành công nghệ thông tin này là một
[00:46:19] ngành nó đòi hỏi sự thích nghi, sự biến
[00:46:23] động.
[00:46:25] &gt;&gt; [hắng giọng]
[00:46:25] &gt;&gt; Anh không anh nói thẳng anh hay bất kỳ
[00:46:28] một chuyên gia nào cũng rất khó để mà
[00:46:31] kiểu
[00:46:32] cùng nóắm là bọn nó cứ chém gió trước
[00:46:34] đúng không? Thường là giống như kiểu ông
[00:46:36] Elon Mus ấ ngồi chm rõ trước các thứ thứ
[00:46:39] nổ trước đã đấy
[00:46:42] chứ không ai khẳng định được là tương
[00:46:44] lai có thể nó sẽ như thế nào đấy nên
[00:46:47] hành a nhưng mà nhấn mạnh đây đó là cái
[00:46:52] cốt lõi của công nghệ âm tin đó là em
[00:46:54] không ngại thay đổi, em phải thích nghi
[00:46:56] được tốt còn không thì em dễ bị đảo thải
[00:46:59] đấy rất đơn giản thế thôi
[00:47:01] còn
[00:47:03] bây giờ để trả lời câu hỏi của em cái
[00:47:05] tập trung hơn đúng không? Thì đó là bây
[00:47:08] giờ anh thấy là khi mà vai code nhiều
[00:47:10] anh thấy là cái chức vụ của anh bây giờ
[00:47:12] nó không còn là dead mấy nữa. Nó sẽ mang
[00:47:14] thiên hướng giống như là PM đó product à
[00:47:18] manager kiểu đấy. Nghĩa là quan tâm về
[00:47:20] chất lượng sản phẩm và review code của
[00:47:23] AI đã code và
[00:47:26] ừ đại khái là review và đôi khi code lại
[00:47:28] một vài cái giống như anh sếp của anh
[00:47:30] hồi trước đã làm với code của anh luôn.
[00:47:32] Đấy. Đấy nó sẽ mang thiên hướng đấy. Nó
[00:47:34] không còn là
[00:47:37] mình tự code từ đầu một cái. À đương
[00:47:39] nhiên mình vẫn code tự code từ đầu mấy
[00:47:41] cái kiểu gọi là pattern mấy cái a design
[00:47:44] mấy cái kiểu mẫu trước để ai nó cũng
[00:47:48] nhìn vào có một cái format nhất định thì
[00:47:51] nó còn code theo chứ đúng không? Đấy và
[00:47:54] mình viết đôi khi là nó sẽ kiêm thêm cả.
[00:47:58] Ừ nó giống product manager tí nó là thôi
[00:48:01] khi mình viết tài liệu nhiều.
[00:48:03] Viết tài liệu để làm gì? Bởi vì chính
[00:48:05] mình mới hiểu được cái product của mình
[00:48:07] nó đang như thế nào để mà mình viết ra
[00:48:10] tài liệu để mà AI nhìn vào biết được nó
[00:48:13] sẽ làm gì tiếp theo. Ví dụ input output
[00:48:15] là gì đúng không? Đấy chẳng hạn thế mình
[00:48:17] lên plan các thứ như nà hoặc là hôm
[00:48:19] trước đấy nhắc tôi tôi xin phép nhắc một
[00:48:22] tí. Đấy, hôm trước có ông chia sẻ về
[00:48:24] cách vi code này này. Đây đề cập đoạn
[00:48:27] này luôn này. Đó là sẽ bảo nó phỏng vấn
[00:48:30] mình rồi
[00:48:32] rồi mình sẽ trả lời cho nó là từng bước
[00:48:35] từng bước như nào để nó tự viết ra. Đây
[00:48:39] nó viết document cho mình các thứ thứ để
[00:48:41] nó sẽ dựa vào cái đấy. Đấy, rất là hay.
[00:48:45] Hiện tại là AI bây giờ cũng có vài con
[00:48:48] giống con antiity này tôi đang thích bởi
[00:48:50] vì nó có lên khái niệm lên blending nó
[00:48:52] sẽ lên cái cái file Md kiểu liệt kê và
[00:48:56] nó có hỏi lại mình confirm lại mình vài
[00:48:58] cái vài cái thôi nhá nếu mình bảo nó có
[00:49:02] thì nó sẽ chuẩn hơn là để nó chỉ hỏi
[00:49:05] mình mỗi vài cái. Đấy xong rồi nó sẽ lên
[00:49:08] một file file plan này. Xong rồi file
[00:49:10] work through này. Thôi một file file tab
[00:49:13] chính là file checklist là nó sẽ làm
[00:49:15] những cái gì rồi nó kiểu đánh dấu vào đã
[00:49:18] làm ấy. Hay phết. Tôi thì thực ra là bọn
[00:49:21] này vẫn thiếu một cái cơ không biết nó
[00:49:23] có tính vào cái work work true không
[00:49:26] nghĩa là khi nó làm thế rồi làm gì câu
[00:49:28] chuyện nó làm một phát ăn ngay đúng
[00:49:30] không ạ? Nghĩa là
[00:49:32] mình vẫn phải bảo nó sửa lại vài cái
[00:49:33] đúng không? Thì đôi khi nó sửa lại luôn
[00:49:35] ở trong tài liệu cũ. Đấy tôi thấy thực
[00:49:38] ra hơi nhược điểm. nó chuẩn là nó sẽ
[00:49:40] phải viết thêm ở trong hôm đấy hoặc là
[00:49:42] nó sẽ viết theo dạng là hồi trước tôi
[00:49:44] bắt nó phải viết thêm một cái file nữa
[00:49:46] là file chlog tức là đã thay đổi những
[00:49:49] cái gì ví dụ giả sử là ở trên mày mắc
[00:49:52] cái lỗi a rồi đúng không đấy bảo sửa rồi
[00:49:57] xong rồi ở dưới nó lại mắc lại cái lỗi a
[00:50:00] vì kiểu đôi khi là nó out contex kiểu
[00:50:04] dạng con ai nó cũng chỉ nhớ được một cái
[00:50:06] lượng nhất định thôi mà đúng không nó sẽ
[00:50:08] quên mất Đấy. Đấy, nó lại mắc lại lỗi A.
[00:50:11] Nó đã từng thử cách đấy để bị mắc cái
[00:50:13] lỗi A nhá. Xong rồi vài đoạn đoạn dưới
[00:50:15] dưới nó lại què. Đấy, mình phải nhắc lại
[00:50:18] đúng không? Đấy, nếu mà nó lưu lại cái
[00:50:20] trên log như thế nó đã biết nó đã làm
[00:50:23] cái a à nó làm cái a rồi nó bị lỗi ra A'
[00:50:27] rồi thì nó nó nhìn lại nó nhớ để nó
[00:50:29] không làm lại cái A đấy lỗi tiếp đúng
[00:50:31] không? Tứ nhiên là thế.
[00:50:35] Đấy thì thằng anti này nó đã làm tốt
[00:50:38] khoản là nó tạo ra quả plane plan này.
[00:50:42] Đây tôi ghi rõ ra cho mấy ông nhá. Plan
[00:50:43] này work true này. Work true là kiểu
[00:50:47] dạng thôi không biết là viết đúng hay
[00:50:49] không nhá. Ở đây và tas cái này nó sẽ
[00:50:53] chính là to do list ấ kiểu danh sách
[00:50:55] những cái đầu việc cần làm ấy. Đấy work
[00:50:58] to này là nó lướt qua những cái kế hoạch
[00:51:00] các thứ thứ. Đây kế hoạch rồi nhá. MC
[00:51:03] thu này thì tôi quên mất nó là cụ thể là
[00:51:06] những cái gì nữa rồi. Nhưng đại khái thì
[00:51:10] cái nó vẫn đang thiếu một cái nữa là cái
[00:51:12] chen lọc và đã làm những cái gì đấy.
[00:51:18] Đúng rồi. Lịch sử thay đổi là nó làm bởi
[00:51:21] vì mình bảo nó sửa xong nó sửa lại vào
[00:51:24] luôn trực tiếp vào ba file này làm cho
[00:51:27] nó quên mất là cái vừa nãy nó đã làm gì.
[00:51:31] [khịt mũi]
[00:51:39] tôi nghĩ là tôi đã trả lời được phần nào
[00:51:41] cái câu của bạn vừa hỏi. Còn nếu bạn cần
[00:51:44] hỏi thêm nữa thì đây vào đây đọc thử,
[00:51:47] nghiên cứu thử nhá. Cái file code đây.
[00:51:50] Nghĩa là thứ nhất là không nên sợ AI vì
[00:51:54] AI bây giờ nó đang là một trợ thế khá là
[00:51:56] tốt nếu mình biết tận dụng nó. Đấy, còn
[00:52:00] để biết cách bây giờ mình phải nói là
[00:52:02] biết cách dùng AI như nào nó na giống
[00:52:04] như hồi trước hồi trước là tôi thường
[00:52:05] hay dạy mấy ông đó là mấy ông đôi khi
[00:52:09] hơn nhau ở cái trình là việc cách trao
[00:52:11] Google thông minh hơn. Ông nào biết được
[00:52:12] từ khóa ấy thì bây giờ thời gian đầu AI
[00:52:15] mới ra thì nó sẽ biến thiên về việc là
[00:52:17] ông nào biết prom chuẩn hơn ấy, ông nào
[00:52:20] thậm chí cũng phải liên quan biết từ
[00:52:21] khóa cơ vì AI thời đấy nó cũng chưa đủ
[00:52:23] thông minh để mà hiểu được. Đôi khi là
[00:52:27] đôi khi không hiểu tiếng Việt ông phải
[00:52:28] nói tiếng Anh chẳng hạn. Còn bây giờ nó
[00:52:29] hiểu tiếng Việt tương đối tốt rồi. Thì
[00:52:32] lại về việc là ông phải làm sao quản lý
[00:52:34] được cái chất lượng của nó ra. Bởi vì
[00:52:37] prom của ông có thể nó như nhau rồi nhá.
[00:52:40] Tôi cảm thấy là ai dần dần kiểu nó còn
[00:52:42] hỏi lại mình các thứ thứ để xác định lại
[00:52:44] mà nên prom của ông lúc đầu vào có thể
[00:52:46] ít. Thậm chí là mấy cái con kingh này
[00:52:49] này hôm trước tôi từng nói ông mấy ông
[00:52:51] người vụ đấy mấy con kinh này nhá ông
[00:52:53] prom càng chi tiết lại càng chết bởi vì
[00:52:55] con thanh kinh này nó sẽ tự nghĩ hộ ông
[00:52:57] còn nếu mà ông càng chi tiết nó sẽ càng
[00:53:00] giới hạn về nghĩ của nó nó không nghĩ
[00:53:01] thêm nó sẽ chỉ làm đúng cái ông nói thôi
[00:53:03] thành ra là kiểu nó lại bị ngu đi. Chắc
[00:53:06] gì ơi, nói thẳng luôn, chắc gì mình khôn
[00:53:07] hơn nó ở nhiều cái mà mình bắt nó phải
[00:53:10] làm giống hệt ý tưởng của mình. Hà mình
[00:53:13] chỉ cần cho nó mỗi cái input và output
[00:53:16] rồi bảo là mày tự nghĩ cái xử lý tiếp
[00:53:19] theo gì. Và đôi khi tôi toàn phải nói
[00:53:21] tôi toàn nói với nó không phải những cái
[00:53:23] câu
[00:53:25] trừ những câu ra lệnh kiểu chắc chắn ra
[00:53:26] nhá. Tôi sẽ thường hay nói là tôi nghĩ
[00:53:29] thế này ông xác nhận lại cho tôi được
[00:53:31] không chẳng hạn. Thế đấy ông có kế hoạch
[00:53:34] nào khác không? Ông nói ưu nhược nó vân
[00:53:36] vân là gì các thứ thứ ông thể cho tôi
[00:53:38] giải pháp khác nữa được không? Đấy nó
[00:53:40] phải câu hỏi mở như thế để nó nghĩ thêm
[00:53:42] cho mình đấy. Gợi ý thêm cho mình đấy.
[00:53:46] Mình hãy coi nó như một thằng xong xăm
[00:53:49] để mình ra lệnh chứ không ra lệnh và nó
[00:53:52] sẽ gợi ý ngược lại mình. Tránh với việc
[00:53:54] là
[00:53:55] mình đã kém rồi, mình còn ra lệnh nó ép
[00:53:57] nó theo khuôn mình nữa thì đấy là cách
[00:54:00] dùng ai không tốt đúng không?
[00:54:08] ông cần gì và ông bắt nó làm giống hệt
[00:54:10] thế thì nó khác đúng không? Thế thì
[00:54:12] không nên dừng con thên kinh. Ông dùng
[00:54:13] hẳn cái con bình thường thôi.
[00:54:22] lại thì sao? Đúng, cũng có thể. Tôi đang
[00:54:25] hơi lười mà.
[00:54:27] Tôi bảo nó thử viết lại. Ừ nhưng mà thôi
[00:54:29] viết lại cho giống hệt cho nó được đi.
[00:54:34] Dùng bắt nạt Jemini đi. Tôi ghét thằng
[00:54:36] Yamini á. Tôi bắt lạt nó.
[00:54:40] À
[00:54:42] nhưng mà thằng này đôi khi hơi ngu về
[00:54:43] khoản bảo nó biến lại thành cái file gì.
[00:54:47] Đôi khi bảo tôi không làm được đâu.
[00:54:50] Thật tí cho xem. Đây bây giờ cho xem
[00:54:52] luôn nhá. Đây
[00:54:54] &gt;&gt; hả? Thế chưa bảo là tôi không làm được
[00:54:58] &gt;&gt; mấy lần anh bảo nó thế mà không làm được
[00:55:00] đây.
[00:55:02] Bro ở no đã từng có đứa bảo với anh là
[00:55:05] chắc là ông dùng bản miễn phí bro là nó
[00:55:08] mà
[00:55:10] thấy
[00:55:12] &gt;&gt; à không thằng này toàn bảo tôi không thể
[00:55:15] làm được cái điều đấy vân vân vân kiểu
[00:55:17] tôi không hỗ trợ tạo ra file gì thằng
[00:55:21] thằng chat vt thông minh hơn cái đấy
[00:55:23] nhiều nhở
[00:55:26] à
[00:55:28] viết lại theo dạng vào để tôi có thể
[00:55:34] copy. Đấy,
[00:55:38] tôi từng à nhờ thằng chatt làm này để
[00:55:41] xem nó thử thằng này nó chỉ được khoe nó
[00:55:44] toàn không khoe thông minh con đ chatvt
[00:55:46] nhá. Nó toàn khoe nó contex dài hơn
[00:55:49] chatvt
[00:55:57] về AI.
[00:55:58] À gần đây anh có để ý những cái thấy
[00:56:02] không?
[00:56:09] không? Đần mãi
[00:56:17] Đợi tí mở mở mấy cái AI này ở
[00:56:22] công khai đôi khi dính vào mấy câu hỏi
[00:56:24] hơi nhạy cam. Tôi phải cứ
[00:56:28] &gt;&gt; đây
[00:56:31] nhìn nhá.
[00:56:40] [khịt mũi]
[00:56:40] Con nốt thích
[00:56:42] &gt;&gt; không thích
[00:56:45] bắt
[00:56:46] viết dạng down
[00:56:50] cơ mà. Đấy hỏi lại phát nữa nhá. Tôi nhớ
[00:56:53] là tuy là chadity từng ngu một lần như
[00:56:56] thế nhưng mà lúc sau nó vẫn chả được
[00:56:58] lại.
[00:57:06] không được thấy không?
[00:57:15] hơn rồi
[00:57:18] hả? Copy ra á? Ông đừng lừa tôi. Copy
[00:57:21] này ra ma down kiểu gì đây? Ông bảo copy
[00:57:24] cái trên này ra ma down đúng không? Cái
[00:57:26] này ra ma down đúng không? Thầ copy nhá.
[00:57:41] &gt;&gt; Xin lỗi đi. Xin số tài khoản
[00:57:43] &gt;&gt; xin lỗi.
[00:57:43] &gt;&gt; Xin số tài khoản đi.
[00:57:44] &gt;&gt; Xin số tài khoản à? Xin số tài khoản của
[00:57:46] ai? Của ông đấy á.
[00:57:48] Tôi chửi thằng chatt à chửi th mini mà
[00:57:54] &gt;&gt; xin tài khoản cảm ơn sá
[00:57:57] &gt;&gt; ơ thế tại sao không bởi vì tôi đã từng
[00:58:00] copy thật à hồi đấy là copy bên chat DVD
[00:58:04] hồi đấy copy bên chat DVD là không không
[00:58:06] được
[00:58:08] &gt;&gt; đây thật mà lừa làm gì đâu xem nha
[00:58:14] [tiếng cười]
[00:58:15] &gt;&gt; bây giờ lại được rồi này bọn này lừa Và
[00:58:19] [khịt mũi]
[00:58:20] nó cập nhật thế nó cập nhật là không báo
[00:58:22] anh lừa
[00:58:30] anti varity kit có dùng rồi tôi thấy tôi
[00:58:35] dùng được mỗi cái xịn nhất của nó là cái
[00:58:37] workflow
[00:58:39] à UIUX Pro Max vì tôi làm giao diện kém
[00:58:43] xong rồi tôi từng nhờ
[00:58:47] Gemini
[00:58:48] 3 Pro xong rồi up cái gì à upper à
[00:58:53] output này với sonet kinh nói chung đủ
[00:58:57] kiểu sửa cái đoạn đấy mãi không được
[00:59:00] xong rồi thêm con antigravity kit kia
[00:59:03] đúng không có để là uiu pro đấy à pro
[00:59:07] max đấy xong rồi nó sửa một phát được
[00:59:10] luôn ạ đỉnh vãi về kiểu khai sáng
[00:59:23] trong
[00:59:34] sẽ ơ ấn nhầm tôi sẽ là cái gì nhỉ?
[00:59:43] Đây lưu nó sẽ là
[00:59:46] doc.md.
[00:59:48] Đấy.
[01:00:06] Cộng đồng. Còn đây là build in public
[01:00:08] này. Cái này là chuyên để mà ông chia sẻ
[01:00:12] những cái phần mềm hay ừ phần mềm của
[01:00:16] ông mới làm để công khai cho cộng đồng.
[01:00:20] Thường là mấy cái liên quan đến startup
[01:00:22] các thứ.
[01:00:24] [hắng giọng] Anh em chia sẻ trong này
[01:00:25] nhiều thấy mấy anh em chất các thứ. Đây
[01:00:27] cộng động to. Tiếp theo là tôi gần đây
[01:00:30] tôi tham gia cái antiravity
[01:00:33] Việt Nam. Có hai cái nhá. Đừng vào nhầm
[01:00:36] cái nhá. À còn cái gì nhỉ?
[01:00:39] Ờ
[01:00:42] có vừa nãy có tôi có đề cập ấy có nhiều
[01:00:45] anh em a nhiều anh em
[01:00:48] kiểu
[01:00:49] tự nhiên đột nhiên xuất hiện trên trang
[01:00:51] chủ cá nhân Facebook của tôi cho dù tôi
[01:00:53] không ngắn theo dõi nhưng gần đây tôi
[01:00:54] theo dõi hết rồi mấy anh a em chia sẻ về
[01:00:58] AI nhiều
[01:01:00] và mấy anh ấy thỉnh thoảng anh ấy có
[01:01:02] nhắc trong cái build init này đợi tí tôi
[01:01:05] không biết có một cái tôi nhớ là Có một
[01:01:08] cái nhóm riêng Facebook đấy. Đợi tôi một
[01:01:10] tí nhá. Xem lại qua Facebook bây giờ nó
[01:01:13] đổi sang giao diện đần vào anh vậy. Nút
[01:01:18] setting ở đây đâu rồi?
[01:01:28] thay đổi giao diện dành không hợp người
[01:01:31] già lắm.
[01:01:34] Hử?
[01:01:36] Mượn điện thoại
[01:01:50] Đấy. My ông có thể tra cái này.
[01:02:00] chưa chắc chắn đâu đúng không? Mình sẽ
[01:02:02] chơi chó
[01:02:11] cho tôi dạng MD tiếp.
[01:02:22] double check AI đi.
[01:02:37] doc này sao cho phù hợp.
[01:02:41] Thực ra hôm nay còn chưa học đến bài 5
[01:02:43] nãy chưa nhắc gì đến bài 5 nhắc lại mà
[01:02:46] đã tiếng rưỡi rồi [tiếng cười]
[01:02:50] chưa học gì cả không sao vẫn học mà vẫn
[01:02:53] học quá học lại bài cũ vậy
[01:02:57] ừ đúng rồi tôi gần đây tôi chuẩn bị phải
[01:02:59] lên công ty để mà
[01:03:01] quyền đồ trên đấy và công ty tôi mới đổi
[01:03:04] văn phòng nên tôi đang chuẩn bị ngồi nói
[01:03:08] anh em mình một tí nữa thôi xong rồi
[01:03:10] lại lên công ty tôi hôm nay ngồi chỉ
[01:03:13] ngồi tạo doc chia sẻ tâm sự với anh em
[01:03:15] nhá cũng chưa ngồi học được
[01:03:22] học cũng được mà
[01:03:24] [khịt mũi]
[01:03:26] hôm sau học cả bài 5 bài 6 luôn được đc
[01:03:30] chấm md
[01:03:38] tại sao đến đoạn này dừng
[01:03:40] Đây này. Nó đểu này. Nó chỉ đến cái đoạn
[01:03:42] này thôi.
[01:03:44] Viết viết trong này bị sai rồi. Cái này
[01:03:48] có bị nhược điểm là nó đóng ở đây nên
[01:03:51] thành ra mất.
[01:03:53] Thử thử ở cuối xem nào.
[01:04:34] anh stream được luôn đó
[01:04:41] cứ ai định tôi đặc bến hồi trước có
[01:04:44] người khen tôi đẹp dài thôi không thể
[01:04:46] tin được luôn.
[01:04:53] Ngọ nhỉ? Bảo tôi nhiệt tình thì tôi sẽ
[01:04:55] tin. Con đẹp trai hay là cốt giỏi hay
[01:04:59] cái gì đó tôi cũng không tin nó lắm.
[01:05:08] đây nó sửa thằng này nó sửa lại cho tôi
[01:05:11] rồi này
[01:05:18] đ chuyện
[01:05:22] &gt;&gt; ơ nãy là có anh em bình luận nhiều hơn
[01:05:24] rồi đấy đợi tí a
[01:05:27] có những cộng nhau tận
[01:05:31] học bản chất sa phương ước bị ngố
[01:05:40] về ạ AI Studio nhưng mà tôi lại chưa
[01:05:42] dùng cái đấy cơ sếp tôi chưa từng dùng
[01:05:51] thì
[01:05:53] hình như video hôm trước tôi từng có đề
[01:05:54] cập nhá
[01:06:02] cả tài liệu này nhé.
[01:06:11] mục tiêu của project này. Đấy,
[01:06:16] tôi dùng thằng này vì tôi tin là thằng
[01:06:19] này nó chuyên về
[01:06:21] tài liệu và chuyên về giao diện. Hôm
[01:06:24] trước có ông phân tích là như thế. Thằng
[01:06:28] Pro thì thế.
[01:06:29] À thằng Gemini thường về giao diện,
[01:06:32] Cloude thì về
[01:06:35] code. JBT thì cui bóc thự ra đùa đấy.
[01:06:39] GVT hôm trước có ông bà GVT hợp để đi
[01:06:43] bấc
[01:06:52] lên kèo còn định giao lưu nữa không ạ?
[01:06:55] Có chứ. Tôi thường xuyên lên ấy chứ
[01:06:57] chẳng qua là anh em ít đi rồi thực ra là
[01:06:59] tôi vẫn hay đi mà tôi gần đây ít đăng
[01:07:02] lên đấy thôi chứ đi hàng tuần vẫn đi đi
[01:07:06] với anh em phải ra ngoài cà phê thậm chí
[01:07:09] có thể mãi cũng được anh thì ở Hà Nội ừ
[01:07:12] maiãi cũng thể được để xem mai thế nào
[01:07:14] tôi vừa đặt khám nha khoa xong
[01:07:18] răng khôn ở 30 tuổi mới nhổ cái răng
[01:07:21] khôn thứ hai. Chắc cũng muộn. Nhiều
[01:07:24] người bảo nhổ hết từ năm hai mấy rồi.
[01:07:36] nguyên mà đúng không?
[01:07:39] Ơ vừa rồi hình như là mình gửi nhầm file
[01:07:41] tôi gửi luôn lại file này. Sửa cả file
[01:07:45] này nữa.
[01:07:52] antiravity thằng Queense nó bắt đầu cập
[01:07:55] nhật hiển thị lên là đang bao nhiêu phần
[01:07:59] trăm contex rồi để mà tránh việc là mình
[01:08:01] thấy 100% rồi tức là nó không nhớ được
[01:08:04] cái lượng ở trên ấy thì mình nên tạo hẳn
[01:08:06] cái chat mới.
[01:08:08] Đấy thằng Gemini này thì nó cậy nó lợi
[01:08:10] thế là nó lưu đến 1 triệu à 1 triệu
[01:08:13] contex thôi. Nghĩa là cứ cho contex ở
[01:08:16] đây là 1 triệu kiểu chữ cài kỹ tự ký tự
[01:08:20] nhá. Chứ còn à không thể tính mỗi chữ
[01:08:24] cài ký tự ở đây được vì nó đọc cả cái
[01:08:26] khác nữa. N nó nó vẫn nghĩ. Nhưng mà
[01:08:29] thằng anti này tôi thấy là nó vẫn đang
[01:08:31] đi sau thằng nhiều quá.
[01:08:35] Từ hai xếp
[01:08:38] đó sửa lại rồi.
[01:08:41] À
[01:08:47] đi nhanh.
[01:08:50] Tạo doc
[01:08:53] MD cho ba thư mục này luôn cho tôi
[01:09:00] đấy. Thôi hôm nay chưa ngồi học được.
[01:09:03] Mày ngồi tạo xong rồi tôi còn phải đi.
[01:09:06] Xin phép anh em
[01:09:08] không sau nhá. Hôm nay ngồi ngồi học à?
[01:09:13] Không ai ngồi như này đã làm một cái á.
[01:09:15] Được rồi.
[01:09:40] nó mà. Cho dù là đang 3 tháng đầu thì
[01:09:43] giá vẫn rẻ nhưng mà mình
[01:09:45] hôm trước còn lúc mà bị antiity sập là
[01:09:49] tôi còn vừa mua cả Winus 1 tháng nữa.
[01:09:51] Tính là tháng này vỡ mồm tiền à vỡ mồm
[01:09:54] hơi quá nhưng mà đại khái thì
[01:09:58] mất tiền cho anh nhiều mà.
[01:10:11] có cái ảnh đẹp hơn
[01:10:14] à đây thích tạo ảnh được mã nhìn nhá ông
[01:10:17] mấy ông nhìn nhá
[01:11:18] này.
[01:11:33] đợi một tí. Bây giờ ấn download
[01:11:40] không muốn.
[01:11:42] [tiếng cười]
[01:11:49] cảm quên mất.
[01:11:58] thôi nó sẽ tự động đưu là bng. Ok. Ơ lì
[01:12:03] con mẹ do
[01:12:15] ông thấy tôi ngồi kiểu chuẩn trì không
[01:12:19] được nhỉ.
[01:12:22] Đấy ta tài liệu các thứ như này rất xịn.
[01:12:25] Cho dù là mình không biết mình có xem
[01:12:27] lại không nhưng mình quan trọng trông nó
[01:12:29] xịn.
[01:12:54] ching pu không? Cái này đề cập string p.
[01:13:05] trong
[01:13:31] string pool này xong tạo string các thứ.
[01:13:35] Mấy cái ảnh này không đủ để mà diễn tả
[01:13:36] cái đấy rồi.
[01:14:11] rất màu mè đúng không? Tôi thấy rất màu
[01:14:13] mẻ không biết được anh em có xem không
[01:14:15] thì tôi sẽ xem.
[01:14:18] Đ chbng.
[01:14:22] Đấy, tạo thêm vài cái nữa.
[01:14:26] Đúng, mình bóc lột ai thật
[01:14:30] mà nó có là miễn phí. Con này miễn phí
[01:14:31] mà.
[01:14:48] tạo ra hình ảnh khó chịu vậy.
[01:15:04] &gt;&gt; không tạo hình ảnh cho nó đẹp thôi. Mày
[01:15:06] điệm thật đấy.
[01:15:08] Bảo V đem tự ái
[01:15:11] &gt;&gt; vẫn tự ái mắ à.
[01:15:15] &gt;&gt; Anh muốn làm đẹp hẳn không? Và chỉnh sửa
[01:15:16] được không?
[01:15:18] &gt;&gt; Mình vẫn phải bấm vào chỉnh sửa được mà.
[01:15:20] &gt;&gt; Vẫn chỉnh sửa được á. Ừ mình bấm hẳn kéo
[01:15:22] xách các thứ
[01:15:24] &gt;&gt; tch có thể thêm vài cái được mà mình có
[01:15:27] thể bấm thêm được thôi
[01:15:42] &gt;&gt; cái cúp vừa rồi đẹp hơn đây cái cúp này
[01:15:44] đấy
[01:15:45] &gt;&gt; cúp này
[01:15:48] &gt;&gt; thế là anh nói là nó thiên Yên về tùy
[01:15:51] cái th cúp nó cũng không phải phản ánh
[01:15:53] được cái gì cả.
[01:15:55] Cái bảng này có
[01:15:57] &gt;&gt; đây như này này đấy
[01:15:59] &gt;&gt; đấy đây đấy. Thế thì giống cái này
[01:16:07] làm
[01:16:08] xịn cho mấy ông
[01:16:11] tuy à thực ra cho tôi đã.
[01:16:14] Cái gì đấy?
[01:16:16] À không ấn nhầm nút đã.
[01:16:19] Ấn nhút mà.
[01:16:21] Em xem cái bảng
[01:16:29] Dog chb bngng trông đẹp mà đúng không?
[01:16:32] Trông dễ hiểu đúng không? Ông thấy dễ
[01:16:34] hiểu đúng không?
[01:16:35] &gt;&gt; Ở bên này nó cũng có
[01:16:36] &gt;&gt; tôi thấy dễ hiểu.
[01:16:37] &gt;&gt; Ở bên này nó không có cái cái bảng xem
[01:16:39] kìa.
[01:16:45] vừa rồi còn hiển thị là dùng mà lúc nào
[01:16:49] cơ còn xịn hơn? Thì cái này cũng tự lâu
[01:16:50] rồi muốn đi học cơ.
[01:16:53] &gt;&gt; Làm sao xịn bằng của anh được.
[01:16:56] &gt;&gt; Kin
[01:16:58] &gt;&gt; Ai tạo ra mà miễn phí rồi. Hết rồi. É
[01:17:02] vừa nãy có ông nào bảo tôi vắt kiệt cơ.
[01:17:04] Địt mẹ nó vất
[01:17:09] hết trong tuần nay rồi. Thôi xem mất bao
[01:17:11] nhiêu.
[01:17:13] 9 đô một tháng để
[01:17:17] dùng.
[01:17:31] Thông cảm anh em thông cảm. Bình thường
[01:17:33] tôi sẽ không khuyên anh em chơi trò này.
[01:17:34] Nhưng mà tôi muốn làm nhanh.
[01:17:39] Làm còn hai cái ảnh nữa mà chắc không
[01:17:42] anh em nào phán xét tôi đâu.
[01:17:49] cưới
[01:18:00] Cái gì đấy?
[01:18:02] Pent này,
[01:18:04] data này, brainstorm này, social đấy.
[01:18:10] À
[01:18:12] socioal này. Đấy, create
[01:18:26] tài khoản mới nó có hướng dẫn như này
[01:18:29] luôn à.
[01:18:30] Tại sao mình hồi đấy mình không có cái
[01:18:32] hướng dẫn này nhỉ?
[01:18:41] &gt;&gt; Chậu nước
[01:18:42] &gt;&gt; trông kiểu
[01:18:43] &gt;&gt; anh đ nghĩ đầu
[01:18:53] Màu mè nhỉ? Mày không thấy màu mè không?
[01:18:55] Uầy cái gì đây? Xếp hình à em?
[01:18:59] Ờ cái này là kiểu cái gì nhở? Ờ tiếng
[01:19:02] Anh nó gọi là cái gì ấy
[01:19:04] &gt;&gt; quên à.
[01:19:05] &gt;&gt; Magic
[01:19:06] &gt;&gt; không magic.
[01:19:07] &gt;&gt; Magic
[01:19:08] &gt;&gt; có chữ D
[01:19:10] &gt;&gt; không cái này magic mà
[01:19:14] &gt;&gt; magicame
[01:19:22] &gt;&gt; brick à.
[01:19:24] Tôi nhớ magic mà đúng không? Đây này.
[01:19:26] Đây này. Cái từ này này. Chữ này này.
[01:19:28] Cái chữ này là gì? Prin à?
[01:19:31] &gt;&gt; Tuấn đọc thì không biết.
[01:19:33] &gt;&gt; À puzzle á.
[01:19:34] &gt;&gt; Puzle là giải đố nó chung chung thôi.
[01:19:38] Ơ game này magic à? Game này tôi nhớ
[01:19:40] magic mà đúng không?
[01:19:42] Game này
[01:19:57] X
[01:20:12] cầu pháp lý này? Không có không có không
[01:20:13] có gì.
[01:20:24] này PP ứng dụng chết sau mỗi request ít
[01:20:28] quan tâm memories Java ứng dụng sống
[01:20:30] hàng tháng trời
[01:20:32] tạm thời.
[01:20:34] Uầy
[01:20:37] cười với chưa?
[01:20:43] lâu dài vòng đời object pass by value
[01:20:45] luôn luôn copy bất biến trí dọn dẹp tự
[01:20:48] động.
[01:20:49] Ôi cái này dễ hiểu không này?
[01:20:52] Được không? Mấy ông thấy ổn không? Nhưng
[01:20:55] cái này có một cái nhược điểm nếu mấy
[01:20:57] ông để kỹ thì nó không nhắc đến mấy
[01:20:59] stack với hip là trong khi đó cái bài
[01:21:02] gốc này là stack và hip chứ không phải
[01:21:05] là cái về mỗi cái vòng đời này cho dù nó
[01:21:08] có nhắc hip ở đây này.
[01:21:10] Stack ở đâu nó không nhắc thấy stack ở
[01:21:13] đây. B hiểu vì tôi không?
[01:21:16] Nghĩa là cái này trông phải rất là hợp
[01:21:17] lý nhưng mà nó không ứng dụng cho cái
[01:21:19] bài này.
[01:21:26] tôi nói thế thôi nhưng mà tôi lười rồi
[01:21:27] không ạ.
[01:21:38] dùng kiểu
[01:21:48] học nhá hôm sau học tử tế nhá hôm sau có
[01:21:50] thể ngày mai. Có thể thôi
[01:22:01] hub bây giờ chắc là xịn lắm
[01:22:05] xem Java
[01:22:08] đây
[01:22:12] mới có hai sao rồi à thôi không sao đấy
[01:22:17] bề sau mình sẽ kiểu có doc ở đây để ảnh
[01:22:20] ở đây để Xem. Đấy, quá xịn. Đọc ở đây
[01:22:24] xem này. Đấy, xem kiểu như này này.
[01:22:45] học. Quên mất. Thôi để mai làm. Bởi vì
[01:22:49] tôi chưa học nên tôi còn không biết được
[01:22:52] là cái nào quan trọng để mà tạo ra cái
[01:22:54] file file
[01:22:57] kia dễ hình dung. Để để hôm sau nhá. Tôi
[01:23:00] tôi sẽ
[01:23:02] đóng máy lại để mai mở cái này lên xem
[01:23:05] được luôn.
[01:23:21] này là file gì nhỉ? Tôi còn không biết
[01:23:23] file này file gì.
[01:23:25] F ấn mở cái gì thôi.
[01:23:43] đc đấy.
[01:23:46] Hệ thống ẩn desktop file thì phục vụ fer
[01:23:50] hoàn toàn giá trị các thứ các thứ tự
[01:23:53] động trong hầu hết thư mục các thứ thứ
[01:23:55] không nên commit nên git nên cho git và
[01:23:58] cho vào git x ok
[01:24:06] xong
[01:24:08] cũng dùng cái tool đơn giản ok cảm ơn
[01:24:12] mọi người đã xem tôi xin phép tôi phải
[01:24:16] lên ngồi
[01:24:18] cho lên văn phòng mới một tí.
[01:24:21] Tạm biệt anh em nhá. Có gì anh em đi ăn
[01:24:23] đêm đi nhá. Đói đấy. [khịt mũi] Bye bye
[01:24:27] anh em.
[01:24:29] 1 tiếng rưỡi. Ok hợp lý.
