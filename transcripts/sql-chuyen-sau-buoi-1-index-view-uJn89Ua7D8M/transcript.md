# SQL chuyên sâu - Buổi 1 - Index & View

- Video ID: `uJn89Ua7D8M`
- URL: https://www.youtube.com/watch?v=uJn89Ua7D8M
- Published: 2021-10-07
- Duration: 1h 27m 1s (5221s)
- Language: vi
- Subtitle source: auto
- Kind: live

## Transcript

[00:00:03] à à
[00:00:13] có thể hôm nay sẽ
[00:00:17] không đông bằng hôm trước học lập trình
[00:00:19] cơ bản cho dù hôm nay cũng là một kiến
[00:00:22] thức rất là hay ờ ờ
[00:00:25] Ừ nhưng mà mình không không thể gả các
[00:00:33] À hôm nay các bạn xem qua mục lục hôm
[00:00:34] nay nhé
[00:00:34] ở
[00:00:37] quốc lộ hôm nay có chuyên mục rất là hay
[00:00:38] à
[00:00:41] ở đó là trả lời cho câu hỏi nếu hacker
[00:00:45] hack được đã tầm bậy của bạn thì sao thì
[00:00:46] mình
[00:00:49] thì mình sẽ phải chờ
[00:00:53] phòng phòng chống nóng như thế nào
[00:00:56] mẹ con mình mình không chỉ các bạn cách
[00:01:01] để mà thách lại được nó hay là
[00:01:04] hay là làm nào để mà lấy lại được chuyển
[00:01:09] dạng và bạn một là dùng tiền hay là
[00:01:16] khi mua tao dùng tiền này hay hack lại
[00:01:18] đến nó là sự thế bà là xin được nó đúng
[00:01:19] không
[00:01:23] 34 là tránh để bị hack ngờ em
[00:01:31] anh có khách thì nghe vui rồi đúng không
[00:01:34] Nhưng mà
[00:01:46] Ừ nhưng mà mình cũng sẽ không đề cập vụ
[00:01:50] khách ở ở trên này để mà mình gạ thêm có
[00:02:05] ở đầu tiên thì cái vụ ép lên trên sau
[00:02:08] này như mình đã từng nói thì các bạn có
[00:02:11] thể thứ nhất là nên trên cái đường link
[00:02:16] áo
[00:02:24] nếu các bạn nên cái link này các bạn đọc
[00:02:26] trước rồi thì có bạn sẽ thấy là hôm nay
[00:02:29] mình sẽ dạy gần như khá là giống những
[00:02:32] kiến thức ở trên này thôi
[00:02:37] ở đây như thế này mình còn ghi cả tác
[00:02:40] dụng của nó như thế nào với Vân rồi
[00:02:42] ừ ừ
[00:02:54] à Hôm nay thì mình sẽ học cả về Index và
[00:02:57] view này thì ra bây giờ hết sự câu hỏi
[00:02:59] nên thành ra lời
[00:03:01] đang livestream hôm nay live stream sớm
[00:03:10] Ừ cái này thì à
[00:03:13] à mình mình chạy mình vừa rồi Mình in
[00:03:17] xuất trước hay bạc một bảng là
[00:03:20] anh không Hôm nay không phải là web 3
[00:03:22] thứ bathứ bảy sẽ là
[00:03:30] Ừ đúng rồi Còn câu 2 sao Mình nợ hơi lâu
[00:03:34] rồi mình xin lỗi bởi vì à thực ra cái
[00:03:38] đấy nó là em cứ an nâng cao một tí chứ
[00:03:45] Ừ thì bây giờ vẫn đủ thời gian để trả
[00:03:46] lời câu đấy
[00:03:51] Ừ thế bạn ở câu này đúng không
[00:03:54] về cách nhận thông tin trên thành nhiều
[00:03:57] bảng cho dễ quản lý lương một nhân viên
[00:03:59] có thể nhập nhiều lần đúng không
[00:04:02] ờ ờ còn 7 phút cho mình sẽ trả lời được
[00:04:07] cho bạn câu này thì bài toán ở đây đó là
[00:04:10] đầu tiên thì các bạn học ra bay đến Thời
[00:04:12] buổi này thì các bạn cũng hình dung được
[00:04:14] các câu lệnh thứ Thực sự thì có nhiều
[00:04:17] bạn một con đang bỡ ngỡ việc cà rốt cuộc
[00:04:21] là học dp chỉ để mạnh kiểu cọ những câu
[00:04:23] lệnh hay không thôi à
[00:04:25] axwell nó không phải mỗi thế out nó để
[00:04:28] mặt lưu lại thông tin nữa đúng không Thì
[00:04:31] mình quản lý thông tin thì cái câu hỏi ở
[00:04:35] đây nếu mà bạn nào còn tưởng nhớ thì cái
[00:04:38] đề bài nó là lưu lại thông tin của nhân
[00:04:42] viên và lương của người đấy nếu mà hồi
[00:04:44] đấy Mình lưu theo kiểu nhà mình mở cái
[00:04:51] ở đây giả sử ở đây ngồi đấy mình nhớ
[00:04:53] mình lưu nhân viên này
[00:04:58] mã này tên này lương này trở lại
[00:05:01] đại khái cơ bản như này đã nhé sửa một
[00:05:05] này Long này đường 100 này hay một tuần
[00:05:09] này xương 200 em ạ Nếu mà nếu mà các bạn
[00:05:11] lưu cơ bản như này thì có hàng nó cũng
[00:05:15] tương đối đủ rồi tương đối rồi đó là
[00:05:17] kiểu các bạn hoàn toàn biết được Ví dụ
[00:05:20] là thằng nay tổng tháng này thì mình sẽ
[00:05:21] phải trả lương cho bao nhiêu nhân viên
[00:05:23] là sử đấy có hai nhân viên đúng không
[00:05:26] tổng mức lượng tổng số lương Một mình
[00:05:29] phải trả là bao nhiêu là là 100 cộng 200
[00:05:32] là ba trăm nữa ngon kê Thì nghĩa là các
[00:05:34] bạn giải quyết được bài toán đó là các
[00:05:36] bạn thống kê được tính toán được và
[00:05:38] tháng này các bạn sẽ phải trả lương cho
[00:05:40] bao nhiêu người kết hợp với việc là ở
[00:05:43] mỗi người sẽ có những mức lương như nào
[00:05:46] tổng lương là bao nhiêu đúng không nhưng
[00:05:47] nó lại không giải quyết được bài toán
[00:05:50] thống kê của quá khứ mà Kế toán lại rất
[00:05:51] cần nhiều đấy
[00:05:53] Vì thế nên là
[00:05:56] thì các bạn phải lưu lại để cho kế toán
[00:05:59] có thể thống kê lại được trong quá khứ
[00:06:01] thì các bạn hình dung học Nghĩa là các
[00:06:03] bạn phải lưu lại điều đấy thì các bạn
[00:06:05] mình thống kê được đúng không thì các
[00:06:08] bạn không thể lưu lại là lương Hôm trước
[00:06:11] đã từng có bạn nhìn lưng cũng như này là
[00:06:15] 100 200 rồi lương mới lại là 200 300
[00:06:18] cảnh ạ Thế này thì được ca thế này thì
[00:06:20] cũng không đúng lắm
[00:06:23] à à
[00:06:26] anh Bởi vì sao Bởi vì lương cũng như này
[00:06:28] thì không phải biết được là giúp lương
[00:06:31] Cỗ này lương cũ Tháng mấy để mình thống
[00:06:33] kê đúng không ra sửa lương mới lương
[00:06:35] hiện tại nó chả Hạ Long cũng là lương
[00:06:37] của tháng trước em ạ Thế con tháng trước
[00:06:40] trước nữa thì sao Đúng không các bạn vẫn
[00:06:42] rất khó thống kê được nếu mà các bạn lưu
[00:06:44] kiểu này hay các bạn ở Lưu kiểu như thế
[00:06:49] này lương lần 1 lương lần 2
[00:06:51] thật sự đây là lương đàn bà
[00:06:55] Kiểu như này nhưng mà Nếu giả sử là
[00:06:58] anh Lương lần 3 có mỗi năm Tăng Thôi anh
[00:07:01] Tuấn không tăng thì sao thì lại như thế
[00:07:04] này đúng không Thế bây giờ mình tăng
[00:07:08] lương cần 10 lần thì thì tạm thêm 10 cột
[00:07:09] nữa
[00:07:12] A và giúp cuộc cải lương lần một ngày
[00:07:14] thì mình đâu nhớ được bà lương lần một
[00:07:16] này của tháng mấy đúng không các bạn
[00:07:18] không lương rồi Như này được đúng không
[00:07:21] các bạn phải tách xa bởi vì sao Bởi vì
[00:07:23] như mình đã từng nói một quan hệ
[00:07:27] mối quan hệ bây giờ là một nhân viên có
[00:07:30] nhiều mức lương gọi nhiều lương đúng
[00:07:31] không
[00:07:35] Từ từ hồi các bạn đi làm cho đến thời
[00:07:36] điểm hiện tại với kiểu gì Các bạn sẽ
[00:07:38] phải tăng 2 hoặc 3 lần mức lương hoặc
[00:07:41] thậm chí bị giảm đi cũng là một mức
[00:07:43] lương khác rồi đúng không các bạn sẽ
[00:07:44] không phải từ trước đến nay chỉ một mức
[00:07:47] lương nó khác với cái tên của các bạn nó
[00:07:49] không luôn đi cùng các bạn mãi theo năm
[00:07:52] tháng đúng không ạ
[00:07:55] từ trước khi ông nào mà đi làm tầm ba
[00:07:57] bốn năm mà vẫn còn một mức lương thì có
[00:08:01] khi ông nên nghỉ Hoa ông là giám đốc
[00:08:03] Ê mấy ông giám đốc thì toàn chơi trò
[00:08:06] lương Một đô để không tính chị không
[00:08:10] tính thuế ông ấy chơi lương mình cổ phần
[00:08:13] nhưng đại sáng như thế các bạn sẽ thấy
[00:08:14] da
[00:08:17] 11 nhân viên đúng không em hồi lương
[00:08:24] ờ
[00:08:28] ờ thì thì cái việc em nổi luôn này các
[00:08:31] bạn sẽ tách nó ra thành một bản nữa thì
[00:08:34] chưa Bảo nữa để lưu lại nó sẽ là kiểu
[00:08:38] như này là sử Giống như mình vừa nói thì
[00:08:43] Ừ thì có tháng mình sẽ lưu được là tháng
[00:08:45] mấy tháng mấy thì nhân viên này lương
[00:08:49] như thế nào là sửa đây là bạn Bảng
[00:08:52] ở Bản Thượng Thư Cao hôm trước mình mới
[00:08:54] đọc là bạn không nên trùng với tên cột
[00:08:57] nên là mình không thể đặt cột vừa lương
[00:08:59] xong rồi à
[00:09:01] tên bạc cũng là lương được nên mình sẽ
[00:09:05] gọi là thống kê lương nhé kiểu như này
[00:09:07] hoặc lương theo tháng thì các bạn đặt
[00:09:09] đúng không
[00:09:13] và Sửa ngay sửa đây Mình lưu đương nhiên
[00:09:15] chắc chắn mình Liêu còn lương rồi đúng
[00:09:16] không ạ
[00:09:19] ạ sau đó giả sử Mình lưu tháng ở ạ của
[00:09:20] mình lưu lại mãi nhân viên là được xử
[00:09:25] thế như này thì giờ sửa tháng 1 bạn Long
[00:09:30] bạn lương được 100 tháng 2 bạn Long bạn
[00:09:33] đấy lương cũng ở 100 tháng 3 bạn Long
[00:09:35] nhưng mà lương lên là một trăm rưỡi các
[00:09:37] bạn được xử thế thì các bạn hoàn toàn
[00:09:40] thống kê được theo tháng theo từng nhân
[00:09:43] viên và mức lương sẽ phải trả là bao
[00:09:45] nhiêu nhưng mà cái này lại nhược điểm
[00:09:48] tiếp đó là nếu các bạn lưu như thế này
[00:09:51] thì nếu mà năm sau thì sao năm sau thì
[00:09:52] các bạn lại bị nhầm trong tháng 1 tháng
[00:09:54] 2 mất rồi đúng không thì các bạn lại
[00:09:58] phải tách nó ra giả sử đây một năm nữa
[00:10:03] đã 20 20 20 20 chẳng hạn 20 21 chẳng a
[00:10:06] 20 20 nhưng là sự đây là rằm tháng 1 năm
[00:10:09] 2021 thì bạn Long này đương nhiên có thể
[00:10:11] nhập lại được một lần nữa đúng trước
[00:10:15] anh đúng không và bơ để tôi kiểm tra xem
[00:10:18] mấy ông có đang tập trung 20 90 mấy ông
[00:10:22] à Ok có vẻ là đúng rồi cái đúng với cái
[00:10:25] số lượng mà hồi học were học này
[00:10:30] ờ ờ Theo các bạn bảng này khóa chính là
[00:10:38] a Nhớ nhớ quá chị ngon đến giờ mấy ông
[00:10:40] trả lời được đúng cô ngày nữa thì cái
[00:10:42] thành công Đấy
[00:11:07] Em có bạn trai đúng rồi
[00:11:11] Em có tấm Ba bạn trả lời đúng rồi
[00:11:19] 35 bạn ok rồi có vẻ nhiều ông trời đúng
[00:11:20] hơn hồi trước
[00:11:24] hồi trước tao lừa quà là đúng trả lời
[00:11:27] sai có mỗi ông một ông trả lời đúng đúng
[00:11:29] rồi các bạn Thời gian mình đã từng nói
[00:11:31] Nếu các bạn thực sự không Thực ra cái
[00:11:33] này lên con này toán một tí nhưng mà
[00:11:36] mình bảo cách giải quyết bài toán đơn
[00:11:38] giản nhất ở đây thì thì các bạn chỉ cần
[00:11:40] kiểm tra thôi đúng không xử là các bạn
[00:11:43] và một mã nhân viên mà là khóa chính
[00:11:46] thôi thì nó sáng nó say luôn rồi này bởi
[00:11:48] vì mã nhân viên là khóa chính thôi thì
[00:11:51] mã nhân viên lặp lại vào lỗ luôn rồi
[00:11:53] đúng không Thế sao nữa rồi Tiếp theo Nếu
[00:11:55] mà sánh với năm là khóa chính thôi thì
[00:11:58] là sửa cũng là tháng 1 cũng 20 20 nhưng
[00:12:02] nhật cho anh Tuấn và 200 Thì cái này nó
[00:12:05] lại báo lỗi bởi vì nó bị trùng với trên
[00:12:07] này nó rồi đúng không
[00:12:24] thế nên là cách giải quyết ở đây là ba
[00:12:26] cụ khóa chính đúng không thấy Giả sử là
[00:12:29] bốn cột thứ như có bạn kia Và 4 Cô đóng
[00:12:32] vai chính thì thế thì lại không đúng ý
[00:12:34] nghĩa của khóa chính ở đây nữa Tại sao
[00:12:37] mọi việc nếu sử mình lặp lại toàn bộ cả
[00:12:38] cái này
[00:12:41] à mà thay đổi lương như thế này
[00:12:46] Ừ thì nó lạnh lại đúng đúng không Nó vẫn
[00:12:48] chạy được nhưng mà thấy lại say mất rồi
[00:12:50] bởi vì là lương của ông ấy nhật tháng 2
[00:12:53] mất rồi đúng không Không phải thay đổi
[00:12:55] ừ ừ
[00:12:57] ờ ờ
[00:12:59] anh theo toa là như thế nào á theo Toán
[00:13:01] thì các bạn học về cấu trúc dữ liệu và
[00:13:03] giải thuật thì các bạn sẽ hiểu về cái
[00:13:05] khái niệm thỉnh thoảng mình nhắc đến
[00:13:09] toán này là thế Mình học môn đấy như ba
[00:13:10] lần như vậy
[00:13:13] một lần hồi mình đi dạy em hôi một hồi
[00:13:16] là mình đi học về sân trường một hồi là
[00:13:18] mình đi dạy mình phải học lại dù một hồi
[00:13:21] là mình đang học liên thông ở kiểu bởi
[00:13:23] vì học cao đẳng nghề nên bây giờ mình
[00:13:25] phải học liên thông để lấy cái bằng đại
[00:13:29] học chính quy để mà về sau mình có muốn
[00:13:32] quay trở lại đi dạy ở trường đại học thì
[00:13:36] phải có bằng là bằng cử nhân của công
[00:13:39] nghệ thông tin với với nhau chứng chỉ sư
[00:13:41] phạm nữa nên là mình mới phải học tiền
[00:13:44] không thưa các bạn xem ngày không em tin
[00:13:46] này thì các bạn chẳng cần lấy bằng gì
[00:13:49] lắm anh không cần bằng được vì từ trước
[00:13:51] nay mình đi phỏng vấn ra chẳng vừa hỏi
[00:13:53] mình bằng chẳng hỏi mình học trường nào
[00:13:55] luôn
[00:14:06] ở đây nói chung và các bạn thì dung được
[00:14:09] bài toán đây rồi có bạn thì sẽ có thắc
[00:14:13] mắc với mình đó là tại sao em thấy một
[00:14:15] tháng của năm này thì anh lưu kiểu là gì
[00:14:17] kiểu đương nhiên là kiểu nó số của nó sẽ
[00:14:20] kiểu in hoặc xơ có bạn bảo hết Tại sao
[00:14:23] anh không lưu lại một cột vào cột ngày
[00:14:26] tháng năm rồi lưu lại kiểu bếp bởi vì
[00:14:28] mỗi khi các bạn biết đại khái niệm
[00:14:31] thường ngày tháng năm gắn liền với bếp
[00:14:33] đúng không Nhớ thế không đúng nữa bởi vì
[00:14:36] là cái này tính cho cả tháng đấy và năm
[00:14:39] đấy còn nếu mà bạn lưu kiểu dạng là nếu
[00:14:42] Gọi Lưu thì kiểu này hay không mưa này
[00:14:46] tháng 1 này một như này để lưu lại nhân
[00:14:50] viên như này Ừ thì hoàn toàn là
[00:14:52] a hoàn toàn thì nay lại không đúng bởi
[00:14:54] vì các bạn hoàn toàn thể bị ngập sang
[00:14:58] ngày mùng 2 cũng là tháng 1 cũng nhân
[00:15:05] Thế thế thế thế nên là cái ý lưu lại đầy
[00:15:08] đủ cả dạng bếp như này lại không đúng
[00:15:10] nếu các bạn chỉ lưu lại theo dạng như
[00:15:13] nào chuẩn này tự nhiên ở đây bài toán
[00:15:16] vẫn còn cơ bản một tí thôi còn nâng cao
[00:15:18] hơn nữa giống như là nhiều phần mềm
[00:15:20] chuyên nghiệp bây giờ làm về kế toán
[00:15:24] thống kê lương thì nó phức tạp hơn
[00:15:25] ờ ờ
[00:15:28] Ok Đấy là chữa cho câu hay sao cho bạn
[00:15:30] Linh
[00:15:34] Còn bây giờ thì mình xin phép là bây giờ
[00:15:37] mình sẽ quay lại bên A
[00:15:41] ở bên này đúng không Bên nhiều nhiều bạn
[00:15:44] on hơn rồi thì các bạn những Hãy Để ý kỹ
[00:15:46] mục lục này nha đúng không Tí mình sẽ
[00:15:49] nói cho qua này hãy cùng một tí thế nên
[00:15:51] là ông làm ở kiên nhẫn chờ đến cuối được
[00:15:53] thì sẽ có thêm rất nhiều cái thứ hai để
[00:15:59] ở đầu tiên thì mình sẽ nói qua về Index
[00:16:01] Nếu các bạn xem qua trên trang của mình
[00:16:05] thì các bạn sẽ biết qua Nói chung mình
[00:16:08] những giải thích khá rõ cái là ví dụ như
[00:16:09] là mình sẽ không dạy các bạn theo kiểu
[00:16:13] đó là kiểu mình đọc lại toàn bộ những
[00:16:15] cái trên này mà mình sẽ đưa thằng bài
[00:16:17] toán thực tế luôn cho các bạn
[00:16:20] anh ở đây sẽ có khái niệm giả sử ở đây
[00:16:24] mình đã in xuất trước một bạn là 100.000
[00:16:25] bản ghi
[00:16:29] ở đây như thế này đấy thì bây giờ giả sử
[00:16:32] Mình muốn lấy
[00:16:37] mình muốn lấy một bạn tên tên gì nữa
[00:16:39] Ví dụ ở bên như này đi
[00:16:43] ở trong danh sách này tên này mình đang
[00:16:46] để lên ta tinh bởi vì mình đang vừa rồi
[00:16:48] mình vừa chạy câu lệnh Insert
[00:16:52] Anh vào trong cái bảng này
[00:16:56] linh tinh để tên côn trùng vân vân chia
[00:17:00] tên này thì ra trái nghĩa gì cả Bây giờ
[00:17:02] mình sẽ có khái niệm gia sửa Selection
[00:17:04] for sinh viên đúng không bạn sinh viên
[00:17:08] mà Where họ bằng này chẳng hạn đúng
[00:17:11] không các bạn thử xem mình chạy mất bao
[00:17:12] lâu nhé
[00:17:16] thì kệ nó tốn không phải
[00:17:19] 2047 giây đúng không
[00:17:22] ô chữ k thế này ra khá nhanh bạn thì
[00:17:25] nhanh phết đúng không Bởi vì sao về các
[00:17:28] bạn 100.000 bản ghi mai Quest tại vẫn
[00:17:31] ạ
[00:17:37] Bây giờ mình có ở bên bảng sinh viên 1
[00:17:39] ở đây là
[00:17:42] 997 nhìn màn GB là gần một triệu bản ghi
[00:17:47] thì tốc độ xử lí nó sẽ ra sao đây mình
[00:17:53] thử cho tên nằm ở 996 này chạy thử này
[00:17:55] sinh viên 1
[00:18:00] Ừ nó ra Các bạn thấy nó lên 0,3 giây Tuy
[00:18:02] là các bạn thấy à không phải ba dây
[00:18:04] nhanh mà anh đúng không Nhưng mà không
[00:18:07] bài toán các bạn đây mình chỉ ra một ví
[00:18:10] dụ điển hình về một triệu bạn ghi Còn
[00:18:12] thực tế và các bạn làm đôi khi không
[00:18:14] phải là một triệu mà thể
[00:18:17] ạ Bây giờ là Facebook lưu thông tin của
[00:18:19] Hà Lưu mỗi
[00:18:22] có mỗi cái bảng tài khoản người dùng mà
[00:18:28] đã là hơn mấy tỉ mấy tỉ rồi mà đương như
[00:18:30] các bạn không không hình dung nó là kiểu
[00:18:33] 1 tỷ Sau đó một triệu thì nó nó gấp
[00:18:37] 1.000 lần nhân lên 1.000 lần dây không
[00:18:39] phải như thế đâu mà nó hoàn toàn khác
[00:18:42] thật chứ nó nằm chết luôn cả con hệ Con
[00:18:45] sờ các bạn và có thật
[00:18:47] ạ
[00:18:51] Và nếu mà các bạn tìm theo kiểu là hồi
[00:18:53] trước các bạn nhớ về cái vụ là tìm tên
[00:18:56] kiểu gần giống tên yêu kiểu là là sử giờ
[00:18:59] bắt đầu bằng chữ quy này chẳng hạn thì
[00:19:02] mình sẽ là like này xong ngồi QR rằng
[00:19:05] sau Kính tự như thế này thì các bạn thấy
[00:19:09] là tốc độ nó lên đến thứ ba thằng ngày
[00:19:11] mai còn nhanh này
[00:19:13] Ừ cái này báo đã tùy tình huống có thể
[00:19:17] lên đến theo lấy Quốc này có thứ như là
[00:19:18] nói chung các bạn thấy đại khái nó như
[00:19:21] thế tốc tốc độ nó có thể bị ảnh hưởng
[00:19:23] rất nhiều nếu mà truy vấn rất là nặng
[00:19:24] đúng không
[00:19:26] Anh ngồi đây
[00:19:30] ông Đặng Minh thích bệnh nhân tỉnh Copy
[00:19:36] chị xem này 0,3
[00:19:39] 0,39 mốt đây đúng không Bây giờ mình sẽ
[00:19:42] chỉ các bạn về cái để mà khắc phục cái
[00:19:44] này để cho tốc độ nó truy vấn rất nhanh
[00:19:47] anh Bởi vì cho các bạn thấy cùng bảng
[00:19:49] này cùng bảng sinh viên một này nhé mình
[00:19:51] copy ra này
[00:19:53] mình sẽ
[00:19:56] thì mình sẽ lấy Theo các bạn thấy mã đây
[00:19:58] bằng 37 đúng không Mình vẫn sẽ lời que
[00:20:01] mãi bằng 37 nhé Đúng không
[00:20:05] ở các loại tốc độ nó khác biệt cực đây
[00:20:12] thì các bạn thấy So sánh không một cái
[00:20:13] là
[00:20:15] à à
[00:20:19] có một cái là gần như không mất 11 m đây
[00:20:22] nào một cái là đây
[00:20:25] ở mức 0,3 giây đúng không
[00:20:27] Ừ thì các bạn thấy là cái nào nó nhanh
[00:20:30] hơn chắc chắn là cái không không mất hẳn
[00:20:33] 1 Mini đây là nhanh hơn đúng không phải
[00:20:36] giải quyết bài toán ở đây đó là tại sao
[00:20:38] nó lại như thế cho dù rõ ràng là nó cung
[00:20:41] trong cái bảng sinh viên một cơ mà Đúng
[00:20:43] không Nó cùng mã màn 37 cơ mà đúng không
[00:20:48] Thì tại sao nó lại nhanh nhìn thế Các
[00:20:51] bạn nhớ vụ hồi tạm bạc
[00:20:53] vì sao mình nhớ mình vừa mình đi câu
[00:20:55] lệnh tạo Bạc á Chắc là mình sáng rồi
[00:20:58] mình nhớ đây mình ghi lại có lệnh thoại
[00:21:00] bàn nhá á
[00:21:01] em
[00:21:04] là sinh viên à đúng không
[00:21:08] Ừ mình đi lại cho các bạn nhớ này mã này
[00:21:11] I này
[00:21:13] khi họ này
[00:21:19] bà Trà 50 chẳng ạ tên này cũng va tra
[00:21:25] 50 rằng ạ và file Mickey La Mã sử là nó
[00:21:28] cứ tự động tăng nhé
[00:21:31] chỉ đúng một phần bạn kia nói đúng một
[00:21:35] phần là nó là do kiểu dữ liệu nữa nhưng
[00:21:38] một phần là các bạn nhớ cái khái niệm
[00:21:41] nào cái mà mình cũng vừa hỏi quay Mickey
[00:21:45] là phải trình đúng không Ừ đúng chưa thì
[00:21:48] cái khóa chính này nó là duy nhất đúng
[00:21:50] không các bạn vẫn nhớ được khái niệm đấy
[00:21:52] đúng không và cái trình cái duy nhất này
[00:21:54] họ sẽ luôn
[00:21:58] thì nó sẽ luôn
[00:22:01] gọi là nó sẽ luôn tạo ra một cái gọi lại
[00:22:06] Index cho nó và Index đầy nó sẽ để tốc
[00:22:08] độ truy vấn theo và Iraq Đấy tốc độ sẽ
[00:22:11] nhanh hơn rất nhiều về chưa
[00:22:13] Ừ nhưng mà đây là trong trường hợp mà
[00:22:16] các bạn
[00:22:17] anh thấy bảo Funiki
[00:22:20] thì nó như này thôi còn nếu mà các bạn
[00:22:22] không khai vào primakey tốc độ truy vấn
[00:22:25] của cái mã vừa rồi hết nó cũng phải lên
[00:22:30] những không phải mấy giây kể cả nhà mình
[00:22:31] mình hẹn tiếp hả Mình chẳng có ví dụ gì
[00:22:34] đây cả vì sao mình có thể dốc cái Index
[00:22:37] nó đi cũng được nhưng mà thôi Bây giờ
[00:22:39] mình sẽ dạy cho các bạn thẳng luôn không
[00:22:42] không cần thêm ví dụ nữa
[00:22:46] ở đây Các bạn thấy là có hai kiểu Index
[00:22:50] là crestor và non Plus thực ra mình phát
[00:22:53] âm tiếng anh vẫn 402 nên các bạn có qua
[00:22:55] lại nhé Thì
[00:22:59] Xin chào các bạn bè quay lại cái mà mình
[00:23:02] vừa nói vừa rồi mình bảo primakey mặc
[00:23:04] định sẽ cho nó cái ếch đúng không chép
[00:23:08] đủ các bạn biết thì cái
[00:23:09] các
[00:23:12] bạn ạ
[00:23:15] Ừ tôi sẽ chạy đi một tí
[00:23:19] ở bản đồ các bạn biết là cài tameiki nó
[00:23:23] sẽ tự động tạo Index crestor hai non
[00:23:34] Ừ đúng rồi bạn Phương Linh và vừa nói
[00:23:36] một câu rất là hay nó không diệt từng tự
[00:23:38] nữa mà nó nhảy tới Yên đấy Đúng rồi
[00:23:40] chính xác chính xác rồi đấy bạn đó là
[00:23:43] khi mà tạo Index nó giống như kiểu các
[00:23:47] bạn tạo một cái một cái bảng riêng và
[00:23:50] bảng mục lục để mà các bạn lưu lại mấy
[00:23:53] cái ở trong đấy và các bạn chị tra trong
[00:23:57] đấy rồi nó sẽ ánh xạ ra cái bảng góc để
[00:24:00] mà lấy được thông tin chuẩn thế nên là
[00:24:03] tốc độ truy vấn của Cái bàn kia vốn nó
[00:24:05] để tìm kiếm thì nó sẽ nhanh hơn rất
[00:24:08] nhiều ở đây trả ông nào đoán nó non cả
[00:24:13] đúng không Ok thì ở đây các bạn sẽ phải
[00:24:15] biết thêm một tí khái niệm về crestor
[00:24:17] này vừa non grasses này nó khác gì nhau
[00:24:20] đây
[00:24:23] Ừ thứ nhất là một bảng chỉ có một Index
[00:24:26] crestor thôi Được chưa
[00:24:29] Vì thế nên là tức là khi mà các bạn đã
[00:24:32] lỡ khai báo waikiki cho cái bảng này
[00:24:36] rồi thì nó tự động đánh Thresh teledex
[00:24:39] đúng không Thì tức là các bạn không thể
[00:24:42] tạo cài Inax crestor cho bà ngày nữa ở
[00:24:45] trên cột khác đây giả sử và mình sẽ có
[00:24:48] câu lệnh là class
[00:24:53] class telnet này nó ngon ơ
[00:24:54] đề nghị quyết đúng rồi nhá đúng không
[00:24:58] Hai Màu nó bị thế
[00:25:04] ờ ờ
[00:25:08] on-device nhớ on thông cảm mình không
[00:25:09] nhớ
[00:25:12] thì không Lâu lắm không làm cái này
[00:25:15] Inax tên chẳng ạ
[00:25:25] 3000 mình mình xin lỗi cái này là như
[00:25:28] không chạy được ở trên máy nãy giờ mình
[00:25:30] đang để mô Nếu mà bạn để ý kĩ thì mình
[00:25:33] đang để mô trên máy kia Tại sao thế Mình
[00:25:36] xin phép phải mở lại em qua server SQL
[00:25:40] Server thì cú pháp nó chuẩn hơn mà có
[00:25:42] mấy cái crestor này còn máy kia thì mình
[00:25:44] nhớ lời thì ra cũng có như cũng phát một
[00:25:47] khác mình dậy rồi các bạn thì sẽ dạy các
[00:25:50] bạn về em qua server để má cú pháp chuẩn
[00:25:52] để mà các bạn người sang bất kỳ Apple
[00:25:55] nào khác thì các bạn sẽ không bị bỡ ngỡ
[00:25:55] lắm
[00:25:58] Ừ nhưng mà tại sao hôm nay mình lại để
[00:26:00] mô các bạn bằng mai que o mà không phải
[00:26:03] qua server ngay từ đầu bởi vì là mình
[00:26:07] mình Insert 1 triệu bản ghi này mình
[00:26:08] không để yên suốt bằng tay được một
[00:26:10] triệu bản ghi cho sẵn rồi mình sẽ bật
[00:26:12] lập trình ra các đoạn này mà lập trình
[00:26:14] của mình thì mình đang dùng ngôn ngữ p
[00:26:17] nên mình chỉ kết nối đến máy kéo thôi
[00:26:18] mình không kết nối được với Access
[00:26:21] Server này để mà Insert thành ra là các
[00:26:23] bạn thấy ra
[00:26:27] thể thấy là mình để mô để mô ví dụ thì ở
[00:26:30] trên máy queo nhưng mà còn bây giờ để
[00:26:33] nhảy sang về ghi các câu lệnh thì chắc
[00:26:35] là mình phải chuyển qua bên này cho nó
[00:26:35] chuẩn
[00:26:39] ở đây mình cứ tạo lại bảng trước nhé
[00:26:42] mình copy câu lệnh tại bản đi
[00:26:45] đã sửa mình copy này
[00:26:48] ở Tuy nhiên các bạn thấy chạy À đây có
[00:26:50] bạn sinh viên không ạ Đây mình tạo hẳn
[00:26:58] buổi mua đây Chắc thế Chắc bạn chưa có
[00:27:01] phần tóc bên này đâu
[00:27:04] ở đó sao mình sẽ yêu buổi một đúng không
[00:27:06] ạ
[00:27:07] cho
[00:27:10] các bạn khi mà học cái này cũng thế các
[00:27:14] bạn nên chạy cốt hết ở trên Apple server
[00:27:19] ạ Bây giờ giả sử và mình tạo xong bạn
[00:27:21] này ổn rồi đúng không ạ sau đó thì mình
[00:27:25] sẽ flash jester
[00:27:28] đó rõ ràng Bên này bên này màu vẫn thấy
[00:27:31] chúng tôi gõ sai gì rồi
[00:27:33] a
[00:27:44] em không nhớ mình đã sai thì luôn Index
[00:27:48] này intek tên lại chẳng lại on sinh viên
[00:27:51] tại cột tên này chẳng
[00:27:53] Ai bày mình chạy thu vụ này các bạn sẽ
[00:27:57] thấy là không thể tạo một à hơn lớn hơn
[00:28:01] một cái classmate trên bảng sinh viên mà
[00:28:05] phải lốp cái crassna cũ mà liên quan đến
[00:28:07] file key chưa
[00:28:08] ừ ừ
[00:28:09] xe
[00:28:14] tải như này thì các bạn thấy đấy thì lý
[00:28:17] thuyết thế đó là kiểu các bạn không thể
[00:28:20] tạo được một collectiondx y hệt
[00:28:24] à không phải một class rách nữa đúng
[00:28:27] không Thế bây giờ mình thử tại một non
[00:28:29] rồi vắt xơi nước thì sao họ sẽ non như
[00:28:32] thế này này chỉ các bạn hoàn toàn tạm
[00:28:38] A
[00:28:42] và đương nhiên là bây giờ bên bên này
[00:28:43] thì dữ liệu toàn bộ là mới này là thực
[00:28:46] ra các bạn không Không biết kiểm tra tốc
[00:28:49] độ nó như thế nào nhưng mà về cơ bản thì
[00:28:51] đều các bạn tìm kiếm theo quay tên thì
[00:28:53] nó sẽ nhanh Hình như cái này chạy được
[00:28:55] trên máy của em đấy mình xin phép mình
[00:28:59] thử thử chạy mình chưa thử rồi
[00:29:02] anh không chạy được
[00:29:05] Ừ để xóa đi Hình như cái này chạy được
[00:29:06] đấy
[00:29:09] ở đó Cái này chạy được
[00:29:12] thì các bạn thấy tốn cũng lần này thời
[00:29:14] gian không phải ba giây để nó đánh Index
[00:29:17] toàn bộ lại cho cái bảng Sinh Viên Hoa
[00:29:20] sinh viên một thì còn nặng nữa này
[00:29:23] a bánh Intex cho bạn sinh viên một mà 1
[00:29:26] triệu bản ghi là tốn tận 3 giây thì chưa
[00:29:29] yêu Bây giờ các bạn thử tìm kiếm theo
[00:29:30] tên
[00:29:33] em vừa rồi tìm kiếm với họ nhá Nhưng bây
[00:29:34] giờ mình tìm kiếm tên của bạn sinh viên
[00:29:36] một thì bạn sẽ thấy tốc độ nóng nhanh
[00:29:39] như thế nào là sự là
[00:29:40] có
[00:29:42] hẳn một cái tên đó chắc chắn không tồn
[00:29:46] tại đi Bể để xem nó sẽ phải quét cả cái
[00:29:50] bàn thì nó sẽ tồn bao lâu đúng
[00:29:52] thì các bạn Thủy Diệu
[00:29:55] thì các bạn thấy tốc độ nó lại nhanh
[00:29:58] bằng cái Index plaster rồi được đúng
[00:30:03] không là chẳng mất không phải máy Desire
[00:30:06] gì cả đúng chưa Nếu khi các bạn bánh đấy
[00:30:09] còn nó rồi nhưng đây mới vẫn chỉ là bài
[00:30:12] toán 1 triệu bản ghi Đây là các bạn thấy
[00:30:16] tốc độ nó vẫn từng đồ ấy à nhanh nhưng
[00:30:18] mà nếu mà các bạn đến tâm như mình nói
[00:30:21] đến tỉ và ghi chứ thìa cháo nó sẽ lên
[00:30:25] đến có thể là tùy server nữa ví dụ bằng
[00:30:28] máy với các bạn mà không đủ khỏe là chết
[00:30:31] luôn đó server chị chứ không phải đã trả
[00:30:34] lại cái quả được như này các bạn đâu gần
[00:30:36] đây mình có làm ở bên công ty mình cũng
[00:30:38] phải biết được mấy cái vụ này bởi vì
[00:30:40] công ty mình đưa nó lên mới chịu bạn đi
[00:30:43] ở
[00:30:47] đó thì vừa rồi là các bạn biết qua về
[00:30:51] cái á Index nhưng mà Ngoài ra mình Sufat
[00:30:53] mình nói thêm một vài nữa khái niệm nữa
[00:30:55] đúng rồi Facebook có dùng máy queo nhé
[00:30:58] Mình đã từng nói ở ngay buổi đầu tiên ý
[00:31:00] đó là Facebook dùng máy queo
[00:31:04] Ê thằng FL Server này thực của Microsoft
[00:31:07] thực cao lại ít ít công ty dùng một phần
[00:31:09] là nọ mất phí năm 1 và là
[00:31:13] lập trình viên mình có vẻ quen dùng máy
[00:31:16] queo hơn nó dễ học hơn thằng em kia
[00:31:20] servo là nó kiểu bị văn mẫu á bị kiểu nó
[00:31:23] có ký hiệu nó giống kiểu ngôn ngữ lập
[00:31:26] trình suy hiểu Ít người nghĩ người thích
[00:31:28] cái đấy hàng ra là kiểu ít người lập
[00:31:31] trình về cái đấy này nha nguồn nhân lực
[00:31:38] à à Một cái công ty lớn ở nó sẽ dùng rất
[00:31:40] nhiều cái thứ hiện lưu ảnh trong bê của
[00:31:43] nó bao gồm cả nấu Maxwell và có thể có
[00:31:45] cảm thêm ashwell để mà kiểm tra chặt chẽ
[00:31:48] với dữ liệu nữa Thế nên là
[00:31:52] không thể nói thằng thằng Facebook Chỉ
[00:31:55] dùng một cái loại cơ sở dữ liệu được
[00:31:58] nhưng có một vài thẳng mình nhớ không
[00:32:00] lầm là một vài hàng nó vẫn có thể đã
[00:32:02] dùng chỉ 01 loại cơ sở liệu
[00:32:05] Ê thằng đấy Mình nhớ không lầm là thằng
[00:32:09] gần đây ở thằng ít hấp thì vậy
[00:32:13] anh đi Thấp bán chè à
[00:32:16] À hôm trước Chính Anh Tuấn đăng cái bài
[00:32:19] là thằng Tít hát này phải tối như sao
[00:32:22] cho mà mai cao của nó có thể chịu được
[00:32:26] đến gần như trăm nghìn được truy vấn mỗi
[00:32:30] một giây trăm nghìn lượt kiểu trăm nghìn
[00:32:33] câu select một giây mà trong cái đó dữ
[00:32:36] liệu của nó bây giờ lên đến mấy mấy chút
[00:32:39] tỉ thì các bạn sẽ thấy là cái bài toán
[00:32:42] Thứ nhất là server của nó máy chủ của nó
[00:32:45] rất là khỏe chứ ai là nó phải tối ưu tất
[00:32:48] cả những cái câu rách mà đương nhiên nó
[00:32:50] chết sống lại đánh nách thằng Google
[00:32:52] Nhấn thằng Google phải đánh Index rất
[00:32:53] nhiều chứ
[00:33:04] Ừ thì ở đây mình mình à Mình có nói qua
[00:33:07] thêm về vụ là Gangster nó khác gì non
[00:33:11] prester John non với crestor vừa rồi và
[00:33:13] mình để mô tiền 1 triệu bản ghi thành ra
[00:33:16] là nó vẫn quá ít để mà các bạn thấy được
[00:33:18] sự khác biệt về tốc độ truy vấn của nó
[00:33:20] Các bạn thấy nó vẫn là không không đi
[00:33:22] đây này ra các bạn không thể so sánh
[00:33:25] được nho class sẽ trả mà luôn nhanh hơn
[00:33:28] là non crestor để cười nhất thứ hai là
[00:33:31] anh Bởi vì sao Bởi vì crestor là nó sẽ
[00:33:34] sắp xếp lại và non-class không sắp xếp
[00:33:37] lại mình sẽ có một ví dụ ở đây để các
[00:33:42] bạn dễ hình dung hơn là sử không ra sự ở
[00:33:45] bên này đi em này sẽ đây
[00:33:48] ạ Bây giờ sửa là mình có nhân viên đây
[00:33:50] mình có một triệu nhân viên đúng không
[00:33:54] thì khi mà mình đánh Index kể code Cái
[00:33:55] này là cholesterol này và cái này non
[00:33:59] Plus này chẳng hạn đấy Hoa Cà
[00:34:04] anh hoặc giả sử Mỹ họ đây Nguyễn
[00:34:06] Mạnh này
[00:34:09] giả sử là họ đây mình đánh Inax là các
[00:34:12] classes nhé và thằng tên mình là những
[00:34:15] đấy cả non-pressure xử thế là xử nó
[00:34:17] không có giả sử quần mã 01 đánh
[00:34:20] eelektross sơ được ạ đúng không ý Thì
[00:34:24] cái cresta này nó sẽ khi mà vào bảng đấy
[00:34:29] thì nó vẫn sẽ kiểu đứng nhiên là nó
[00:34:31] không giữ nguyên đúng cái chỗ ấy nhất là
[00:34:33] cả hai thằng không đều không giữ nguyên
[00:34:35] cái chỗ ấy của nó mà luôn quy ước lại
[00:34:38] dụng Nguyễn này Thành miễn này nó sẽ
[00:34:40] hiểu
[00:34:43] chứ không phải À đúng rồi Nguyễn Nguyễn
[00:34:46] này nó sẽ hiểu nó bằng là một chàng ạ
[00:34:49] xong rồi mạnh này thì nó sẽ bằng là hai
[00:34:52] cả ạ đứng nhờ kem
[00:34:54] à Mà không phải một đi mình cho hằm con
[00:34:56] số ở đó đi
[00:34:57] có
[00:35:00] gì đấy Đây đúng không là gì thì đấy đây
[00:35:02] đi xử như thế này một số bất kì không
[00:35:05] liên quan đến mã thằng này đâu nha
[00:35:08] đứng yên là ngoài cái này ra nó có nó có
[00:35:11] một cái đường Linh nữa là sự đêm một cái
[00:35:13] link này
[00:35:14] mình
[00:35:17] Tại sao tự nhiên mình để cập với Linh ở
[00:35:20] đây bây giờ xử là bên mình tìm kiếm dựa
[00:35:23] trên họ và họ Nguyễn đúng không nó sẽ ra
[00:35:25] đứa con số này đúng
[00:35:26] khi
[00:35:29] con số này bạn nó sẽ
[00:35:31] Ừ cái này là quy ước nhé Cái này là quy
[00:35:34] ước tôi bản chất là con số này nó sẽ
[00:35:38] A
[00:35:41] và đấy mình mình có đi cập ở đây là nó
[00:35:43] sẽ được sắp xếp thứ tự tăng dần rồi để
[00:35:47] nó kiểm tra việc là cái Inax Này tốc độ
[00:35:48] xử lý
[00:35:52] ăn nhanh ở nó được sắp xếp lại đây
[00:35:55] khi dùng từ nó nãy giờ nó đang hơi bị
[00:35:58] khó hiểu một tí để chúng mình ghi lại
[00:36:01] cho bạn sẽ hình dung hơn Đợi mình thích
[00:36:03] à
[00:36:03] đi
[00:36:10] ở đây đây đã sửa ngày đi mình xin phép
[00:36:13] sửa lại cậu từng tí cho nó dễ hiểu hơn
[00:36:19] 21 24 đi
[00:36:25] giá DC đi dạo này rét đi vào đây 25 - ok
[00:36:27] nó như thế này
[00:36:31] mình nó mới Lật lại một lần nữa nhé
[00:36:33] ra xử mình tìm kiếm những cái bạn có họ
[00:36:38] là họ ai chả nạn đúng không Thì ah nó sẽ
[00:36:40] tương ứng với một hai ba này đúng không
[00:36:43] em và nó sẽ chỉ lấy tất cả những cái bạn
[00:36:45] nào mà từ 123 kèm theo link của tất cả
[00:36:48] những các bạn Đấy thấy chưa link của bạn
[00:36:51] đấy dụng ở link này nó sẽ Linh đến cái
[00:36:55] bạn mã là một mã bạn ở dưới này ra sự mã
[00:36:58] bạn đấy là năm thằng bạn có ai là tên là
[00:37:02] ABC chọn thế link này nó sẽ mau gồm cả
[00:37:05] bạn một bạn nam được chưa ạ
[00:37:08] tủ lạnh tại sao mình thể thế nên là đấy
[00:37:11] do mình để cập Linh ở đây Linh này nó sẽ
[00:37:14] Linh được đến hai thằng cùng lúc và họ
[00:37:16] kia các bạn Nhật và A thì bản chất nó sẽ
[00:37:19] ở 123 vào nó sẽ tìm kiếm rất là nhanh
[00:37:21] theo kiểu là
[00:37:24] a123 nó tìm ra một hai ba nó không lướt
[00:37:29] xuống đến 1242 250 nữa chưa Đấy do tốc
[00:37:31] độ xử lý của nó nhanh
[00:37:34] con Hằng còn thằng non preston này thằng
[00:37:37] non-pressure thì bản chất của nó lại
[00:37:38] không không như thế này
[00:37:41] vì nó không được sắp xếp thì cả chẳng
[00:37:45] qua nó cái từ tên của nó như này
[00:37:48] đúng tên của nó ngày nó sẽ biến thành
[00:37:51] một cái chuỗi nào đó cũng là thành và
[00:37:54] chỗ ở đó cũng thèm ngủ Cái Linh ở đó như
[00:37:56] là nó không được sắp xếp thì cả à
[00:37:59] ở tại sao nãy giờ mình phải Đề cập về vụ
[00:38:02] sắp xếp bởi vì Giả sử nhá mình nhập cái
[00:38:04] tên là
[00:38:09] Em à mình mình tìm kiếm tìm kiếm đi Tìm
[00:38:14] kiếm tên là B ạ Nó họ là bê chứ họ B ạ
[00:38:17] Ờ thì đầu tiên thì nó chỉ việc tìm kiếm
[00:38:21] xem là cái bê này nó có tương ứng gì đến
[00:38:24] trong cái bạn này không thôi
[00:38:27] ở Tân ấn với cái số nào trong máy không
[00:38:29] Không có gì nó phản hồi về rất là nhanh
[00:38:32] đấy Cái thứ nhất cái thứ hai Nếu giả sử
[00:38:33] nó là
[00:38:36] a nói B mở trong BB trong này cũng có
[00:38:40] và nó là
[00:38:44] 125 đi vào đây 124 đi
[00:38:46] nó sẽ tìm kiếm được tất cả những bạn bê
[00:38:48] dựa
[00:38:51] a b nói bánh xanh thành 124 đúng không
[00:38:54] và nó sẽ Linh được tất cả bạn đấy và nó
[00:38:57] sẽ không để ý đến 12 năm 250 nữa
[00:38:58] Ừ
[00:39:01] đúng rồi bạn kia nói nó cũng na ná kiểu
[00:39:04] từ Thằng này nó sẽ đùi chiếu sang thằng
[00:39:06] kia ấy cái nó hơi bị mông lung một tí
[00:39:09] nhưng mình đang cố giải hết cho nó dễ
[00:39:12] hiểu hơn chứ bạn tra anh trai trên mạng
[00:39:14] bây giờ về mình cái khái niệm intek này
[00:39:16] có khi còn ông đúng hơn
[00:39:18] nhưng đại khái là các bạn hiểu là nó như
[00:39:22] thế nó sẽ luôn sắp xếp Vậy à đoạn này
[00:39:24] thì ra mình đang bị Hơi sàn gì nhé là nó
[00:39:26] còn sắp xếp loại luôn
[00:39:29] Ừ để không không không xảy ra tình lượng
[00:39:32] tình trạng bê Đầy súng cuối ở đâu ra sự
[00:39:34] mình thêm đàng bê sáng bên phải đến trên
[00:39:36] như thế này mới đúng nó sẽ nhảy đến đúng
[00:39:38] thằng B này thôi và nó không để đến
[00:39:41] thằng C nữa mà nếu mà thằng B giờ Nếu
[00:39:43] giả sử mà mình tìm kiếm cho thằng bêđê ạ
[00:39:47] thì nó nó kiểm tra nhé B trong mày không
[00:39:49] tồn tại thì nó cũng sẽ thông báo các bạn
[00:39:51] luôn đấy việc nhanh của thằng Inn
[00:39:53] Express tơ của vì nó đã được sắp xếp rồi
[00:39:56] còn Chính vì Inax non Blaster là không
[00:39:59] được sắp xếp Nên là các bạn sẽ hiểu là
[00:40:03] nó sẽ nôn kiểm tra từ đầu đến cuối của
[00:40:06] cái bàn Inax để mà
[00:40:09] Ừ để mạc kiểu ra được ra được chính xác
[00:40:13] là thằng đấy có tồn tại trong trong cái
[00:40:16] bà này hay không đấy mình mình cha mình
[00:40:18] đúc kết được mỗi thế
[00:40:23] Ừ nhưng mà ở đây nhá Ở đây Chính vì thế
[00:40:24] nhá
[00:40:26] từ nãy giờ mình nói hơi bị
[00:40:30] mãi mãi một tí mình xin lỗi nhưng mà
[00:40:32] công nhận cái này là khó hiểu mà nếu bạn
[00:40:35] nào biết qua cái này rồi thì ở đây mình
[00:40:37] xin phép thử hỏi thêm các bạn một câu ra
[00:40:40] giả sử là bây giờ mình đánh Inn Express
[00:40:43] mình đánh đất rồi đúng không Nói chung
[00:40:46] mình cứ làm như đất đá đúng không
[00:40:48] ăn thịt heo các bạn là việc là nếu mình
[00:40:50] không làm như đấy Nếu không là Iraq như
[00:40:51] thế này
[00:40:54] so với việc mình đánh Iraq
[00:40:56] Ừ Thì
[00:40:59] sau khi mà Insert update này
[00:41:03] Insert update Delete
[00:41:07] khi đánh Index
[00:41:09] 20 ngày nhưng ấy
[00:41:17] em vừa rồi Các bạn hãy rõ ràng mà đánh
[00:41:20] hình ảnh Index để và câu c của mình chạy
[00:41:22] nhanh hơn
[00:41:25] anh đúng không Đây bình tĩnh mình sẽ ra
[00:41:27] thích các bạn về cụ thể sự khác biệt
[00:41:29] giữa sân crestor vietnamplastic cũng
[00:41:32] thông qua các này
[00:41:34] Ừ thì các bạn
[00:41:37] thấy là ix7 enactus Iraq chạy nhanh hơn
[00:41:40] này đúng không Nhưng còn Insert update
[00:41:43] Delete thì việc bàn Inax nó khiến cho nó
[00:41:45] chạy nhanh hơn nữa hay ở phía nó nó chạy
[00:41:57] Ừ đúng rồi các bạn hiểu được vấn đề đấy
[00:42:00] các bạn trả lời đúng nó này đúng là các
[00:42:01] bạn hiểu được vấn đề rồi Đúng là chuẩn
[00:42:04] rồi đây này thì các bạn vừa rồi dễ hình
[00:42:06] dung rồi đúng không Nghĩa là mình thêm
[00:42:09] một cái bạn nào đó đây nữa sửa mình
[00:42:10] Insert thêm một bạn ở đây đúng không
[00:42:14] em ngủ trưa đi xuất Thế bạn ở đây nếu mà
[00:42:15] không này đấy Thì đúng là mình chỉ in
[00:42:18] rất là xong lại thôi đúng không Con do
[00:42:21] là mình đã đánh Index vào rồi nên là nó
[00:42:24] phải cập nhật lại bằng đấy đúng rồi
[00:42:27] Vì thế nên là bây giờ các bạn trả lời
[00:42:29] được con này rồi đúng không Bạn lại trả
[00:42:33] lời câu nữa khó hơn một tí đó là thế bây
[00:42:37] giờ bài toán là ở cùng này nak là
[00:42:40] classes.dex và non classmate thì thằng
[00:42:43] Hào khi mày Insert update English
[00:42:47] classes và non-class đúng không khi
[00:42:51] thằng nào khi mà khi mạnh Insert update
[00:42:59] à à
[00:42:59] thì
[00:43:03] rõ ràng thì vừa nãy có rẻ có trả lời
[00:43:05] được bài toán là crestor in decan sẽ
[00:43:07] select nhanh hơn đúng không Bây giờ bù
[00:43:09] lại nếu mà Insert update Delete thì
[00:43:12] thằng cras neque non precedex
[00:43:14] Ừ tao nó sẽ khiến có lệnh chạy nhanh hơn
[00:43:23] Ừ đúng rồi bạn Các bạn có vẻ
[00:43:26] Anh hiểu vấn đề đấy chứ khuya hơi lú một
[00:43:28] tí nhưng mà thầy Mình thấy là các bạn
[00:43:31] trả lời đúng hết thì chuẩn rồi
[00:43:34] Ừ cái cái cái cái này nó dễ hiểu rồi mà
[00:43:37] đúng không Bởi vì các bạn thấy à Vừa rồi
[00:43:39] Vừa nãy mình cũng phải làm lại các bạn
[00:43:41] thế khá mất công về việc là a
[00:43:44] AC số tự nhiên nhập thêm một bạn bê nữa
[00:43:47] thì mình lại phải mình lại phải cho Sắp
[00:43:49] xếp nó lại đúng không Mình lại sắp xếp
[00:43:52] lại cho nó thay vì non Blaster thì mình
[00:43:55] chỉ tượng Insert vào vào luôn thêm một
[00:43:58] cái mới còn còn thằng Index cluster thì
[00:44:00] mình lại phải sắc mình ngoài việc mình
[00:44:03] Asus thì mình phải sắp xếp lại đúng
[00:44:09] Ừ mình dậy lấy hiểu á Không cái đoạn vừa
[00:44:11] nãy mình cảm thấy ra sợ hơi khó với các
[00:44:13] bạn Các bạn thấy lú rồi à
[00:44:16] ở miền Nam cố mình đang cố truyền đạt
[00:44:17] một cách
[00:44:20] dễ hiểu thì một phần nhưng mà cũng phải
[00:44:23] đủ kiến thức nên là có nhiều đoạn mình
[00:44:25] sẽ công nhận nó khó nó hơi bị bay não
[00:44:27] một tí
[00:44:29] Ừ nhưng mà như mình đã từng nói thì các
[00:44:31] bạn phải đau não một tí thì các bạn mới
[00:44:44] ở đó thực ra là thực ra là chính vì các
[00:44:47] bạn vừa rồi nghe cái vụ này Insert
[00:44:50] update Delete đã khiến cho tui is-7 Inax
[00:44:53] khiến cho câu select nhanh hơn thật
[00:44:55] nhưng mà bù lại thì Insert update Delete
[00:44:57] nó sẽ bị chậm hơn đúng không thành ra là
[00:45:00] lời khuyên là không áp dụng cho bạn có
[00:45:02] ít bạn Nhi này các bạn đừng có lạm dụng
[00:45:03] việc iPad này thử là nó không được tốt
[00:45:06] lắm khi mà các bạn không biết đánh nó
[00:45:08] chuẩn các bạn không đánh chuẩn các bạn
[00:45:11] cứ đánh cột nào đánh elac ạ Thế quá sai
[00:45:14] cột chỉ có thương ai xe lách nhiều Where
[00:45:15] theo cột đấy nhiều thì mình nên này như
[00:45:18] thế này hoặc và bạn phải có nhiều bản
[00:45:21] ghi Nói chung là mai que vừa rồi Các bạn
[00:45:23] thấy là một triệu bản ghi thì may ra là
[00:45:25] tốc độ của các bạn nó bị chậm đúng không
[00:45:29] Thế nên là các bạn tốc độ nếu mà các bạn
[00:45:31] làm cái phần mềm rất là bé thôi Kiểu này
[00:45:33] chỉ có trăm nghìn mà nghĩ thôi thì các
[00:45:43] A và tiếp theo là cụt mặc thường cập
[00:45:45] nhật thường xuyên giá trị như này lại
[00:45:47] đúng không là các bạn phải đồng nghĩa về
[00:45:49] các bạn phải sửa lại Index rất nhiều nên
[00:45:52] là cũng không nên đánh bài mien Bac cho
[00:45:54] cái cốt đấy
[00:45:57] I và cột nhiều chứa chứa nhiều giá trị
[00:46:01] rỗng nó nun thực ra là nun thì khi mà sẽ
[00:46:04] lách thì nó luôn luôn Bỏ qua Bởi vì các
[00:46:06] bạn nhiều không Các bạn nhớ khi mà câu
[00:46:09] lệnh select các bạn Where
[00:46:13] ví dụ họ các bạn sẽ phải bằng hoặc à
[00:46:16] Like gì đó các bạn nhiều không Còn nếu
[00:46:19] mà các bạn so sánh luôn thì các bạn sẽ
[00:46:22] Các bạn nhớ so sánh như thế nào để mà họ
[00:46:23] là luôn không
[00:46:26] Xin chào Trả lời nhanh câu này phát nào
[00:46:29] là nó để kiện để mà lấy ra những bạn có
[00:46:39] ừ ừ
[00:46:40] à à
[00:46:43] ở nhà ông đâu rồi Hay là do tôi để chat
[00:46:46] cho đúng rồi Các bạn thấy là nó sẽ khác
[00:46:48] biệt hoàn toàn nó sẽ không còn bằng
[00:46:50] không còn like nữa mà nó sẽ ít Nhung
[00:46:52] đúng không Nghĩa là cái này nó không
[00:46:54] liên quan đến Iraq nữa nó liên quan
[00:46:56] thẳng cái khác rồi thành ra là đó không
[00:46:58] có tác dụng gì mấy thì các bạn Ánh Index
[00:47:01] và 10 cái trường đó là nun đúng không
[00:47:04] nghe các bạn hãy bỏ quan
[00:47:07] không không nên kiểu bạn đâu đánh đấy
[00:47:11] hồi hồi mình học mới học db2 này nhé Rất
[00:47:14] nhiều ông được hưởng mềm về đánh tất cả
[00:47:16] cột trong bảng này nhìn đấy rồi ông ấy
[00:47:20] chạy có Insert cho cho một cái bàn có
[00:47:22] trăm nghìn mà ghi hôi mồ côi sơ của ông
[00:47:25] đấy vậy mất 23 giây liền chỉ vì ông này
[00:47:32] Ừ thế thì nên là các bạn phải cân nhắc
[00:47:34] về một cái vụ này không ạ
[00:47:37] ở đây và các bạn sẽ thấy ở đây mình có
[00:47:40] nói thêm đây vừa rồi mình có đề cập là
[00:47:44] cột họ có thể để nó là inecraft được
[00:47:47] được nhá Không phải là một cứ cột
[00:47:50] vanmiki là nó sẽ đương nhiên nó sẽ tự
[00:47:53] động đẩy nấy crestor nhưng mà trong
[00:47:55] trường hợp các bạn không khai bảo nó khi
[00:47:57] mà tạo bảng này thôi các bạn mà khai báo
[00:48:01] nó là Inax cluster đây này các bạn khai
[00:48:02] báo
[00:48:05] i i max pressure
[00:48:07] ở
[00:48:09] tại cổ tên là
[00:48:12] em tên gì vậy trí nhớ không lầm như thế
[00:48:14] này
[00:48:16] các bạn khai báo như này trước chẳng hạn
[00:48:19] thế Mình nhớ mình nhớ không Mình không
[00:48:21] nhớ chính xác về cái xe báo này lắm Đấy
[00:48:23] nó đang bảo lỗi nhưng thực ra là mình
[00:48:26] như mày mình nhớ là các bạn khai báo lúc
[00:48:29] mà các bạn tạo bảng này và Inax plaster
[00:48:32] ở cột khác không phải là cột cột 20 ký
[00:48:34] thì
[00:48:38] sau khi hoàn toàn các bạn làm được vụ
[00:48:41] đấy thì cái cột mã các bạn sẽ không được
[00:48:43] là những cách nữa Chuyển làn để thôi
[00:48:44] Ừ
[00:48:46] có đánh đấy nhưng mà không này nick tô
[00:48:50] nữa mà chỉ đánh Index non-pressure và nó
[00:48:53] sẽ như một cái Index của unique như thế
[00:48:56] này các bạn đọc ở đây nhá cột Yoona cũng
[00:48:59] phải bánh Winx Club mặc định nó sẽ luôn
[00:49:02] lạnh Inax non-pressure này khoai Miki
[00:49:05] thường mặc định sẽ in Express Air Nhưng
[00:49:08] mà nếu mà các bạn khai báo trước khai
[00:49:10] báo trước cột in Explorer là cột khác
[00:49:12] thì quay Mickey nó sẽ được và những nách
[00:49:14] của unix như bình thường và non-class
[00:49:17] thôi à
[00:49:20] a bánh đất thì mình có chỉ có lệnh đây
[00:49:24] rồi Nếu mà mình dại giống nhiều thầy cô
[00:49:26] mình đã từng gặp hoặc cả chính hồi mà
[00:49:29] mình đi học nhé Mình chia sẻ thực tế đó
[00:49:31] là thầy mình dậy đúng có mỗi câu này
[00:49:34] thôi là hết một bài Index và chỉ đơn
[00:49:37] giản Thầy bảo là Inax cả để cho xe lách
[00:49:39] nhanh hơn hết
[00:49:42] cơ hội đấy mình cảm thấy học môn db2 này
[00:49:46] rất chán Chỉ vì lý do đấy bởi vì sai cậu
[00:49:50] bởi vì a mol p2 thời gian mà rất khó rất
[00:49:52] khó về lý thuyết Nhưng mà thực hành nó
[00:49:54] thực ra không khó lắm Bởi vì các bạn
[00:49:56] thấy nó chỉ có một câu lệnh Dương nhắn
[00:49:57] nhé là xong
[00:49:59] Ừ ông ấy con biết trên đúng của dòng nha
[00:50:03] nghe xong hết hết buổi học
[00:50:06] thì các bạn có thể đi về kiểu cái thế
[00:50:08] pin
[00:50:12] Vì thế nên là kiểu mình đang cố đang cố
[00:50:16] à Nó những cái nó gọi trên sông một tí
[00:50:19] các bạn học qua cái Index này ở trên
[00:50:22] trường rồi các bạn sẽ thấy là ngồi cái
[00:50:25] này cô em không lấy dậy này hoặc là bây
[00:50:27] giờ mới biết vân vân vân
[00:50:34] Em hãy trước nãy giờ thì ra Các bạn thấy
[00:50:37] có bạn vừa rồi hỏi đấy câu lệnh đi tạm
[00:50:39] Yên Bái cái gì đúng không có lợi nó chỉ
[00:50:42] ngắn ngủi ngay thôi đó là led này sau đó
[00:50:43] thì
[00:50:46] Anh tên của loại Intex nó sẽ có khái
[00:50:47] niệm là
[00:50:51] class takes all aspects mà các bạn hình
[00:50:53] như mình nhớ không lầm là unique Index
[00:50:56] cũng cỏ như thế này nhưng mà unique
[00:50:58] Index này bạn bản chất nó cũng là non
[00:51:01] egestas neque được như bạn vừa đọc Ngoài
[00:51:04] ra còn thêm một vài vài loại Inax nữa
[00:51:07] không phải một vài cái tên Inax nữa
[00:51:11] nhưng như mình ở Tổng hợp các bạn thực
[00:51:13] chất là bản chất nó chỉ có hai cái loại
[00:51:15] Inax là cras neque mà non-pressure nhé
[00:51:20] Bởi vì nếu các bạn tra nữa u-nik nhìn
[00:51:23] Jack này nó ra này đúng không các bạn sẽ
[00:51:26] nghĩ à à Ông làm lừa tôi rõ ràng có thêm
[00:51:28] loại này nữa nhưng mà không cái này nó
[00:51:40] ở đó là xong cái phần Iraq tiếp theo
[00:51:44] nhảy sang bên view biển view này nó ngắn
[00:51:50] hơn và nó cũng dễ hiểu hơn để để mình
[00:51:52] thử chỉ có bạn nhá
[00:51:55] là sử ở đây mình còn một bảng trước đi
[00:51:58] mình có một bạn cũng là bảo nhân viên
[00:52:00] này là sự là mình lưu lại thông tin nhân
[00:52:04] viên bao gồm cả email và mật khẩu của
[00:52:06] nhân viên ạ đương nhiên phải có lưu lại
[00:52:08] email cực khổ mật khẩu của nhân viên để
[00:52:10] mà nhân viên đăng nhập vào thì mình sẽ
[00:52:13] kiểm tra là Email là Long nè chẳng hạn
[00:52:17] mật khẩu là 123 thì thì mới được vào
[00:52:19] đúng không cho
[00:52:22] mấy đứa đăng nhập và sử là mình nhập mật
[00:52:24] khẩu 2 3 4 thì mình sẽ kiểm tra trong
[00:52:28] này thì sẽ báo lỗi Đúng không đấy
[00:52:32] Ừ ok thì giả sử là mình lưu lại email
[00:52:34] mật khẩu có lý do là như thế nhưng bây
[00:52:38] giờ giả sử là một ông lập trình viên ông
[00:52:39] đấy Kiểu
[00:52:43] cách chạy lệnh select from nhânviên thì
[00:52:47] này ông ấy chạy lệnh này để mà làm các
[00:52:49] thư thứ ông ấy chạy tự nhiên ông ấy thấy
[00:52:52] ra mật khẩu của bao nhiêu ông thế chết
[00:52:53] đúng không
[00:52:57] Thế chết ông ấy không được phép biết mật
[00:53:00] khẩu của hai thậm chí đô thị cải mê luôn
[00:53:02] bởi vì nó là thông tin những cảm yêu
[00:53:04] kiểu là email khách hàng mà đúng không
[00:53:07] ra là nhân viên hạn chế biết email khách
[00:53:10] hàng để lúc mà nó nhảy việc cái nó ôm mà
[00:53:12] đồng email đấy nhảy sang công ty khác để
[00:53:14] mà mà cái tinh thì chết đúng không Thì
[00:53:17] nên là ông ấy chỉ được phép Giả sử ông
[00:53:18] ấy chỉ được phép lấy họ tên thôi chẳng ạ
[00:53:20] thì làm như nào
[00:53:24] Ừ thì các bạn sẽ bảo là Ừ thì ông ấy gõ
[00:53:25] đầy đủ như thế này là được mà anh đúng
[00:53:29] không mã họ họ tên như này không Nếu mà
[00:53:32] như này thì ông đấy mà gõ đầy đủ tử tế
[00:53:33] như này người tốt ông ấy có toàn quyền
[00:53:35] động và cái bảng nhân viên này thì ông
[00:53:38] ấy không tội gì mà lấy sẽ sao để lấy hết
[00:53:40] thông tin cả đúng không Ông ấy Tại sao
[00:53:43] mới phải gõ vừa phải mất công gõ dài hơn
[00:53:46] kết hợp với việc là ông ấy sẽ không lấy
[00:53:47] được những người thông tin nhạy cảm kia
[00:53:50] đúng không Thì có bạn bảo là Ok Nếu thế
[00:53:52] thì bây giờ em tách hẳn một bảng bảng
[00:53:55] thông tin nhân viên vòng bảng là bảng
[00:53:57] thông tin mật khẩu của nhân viên Ngạn
[00:54:00] Thế thì làm như nào không Thực ra là
[00:54:04] không ai làm thế Cả Thế bây giờ giả sự
[00:54:07] là là mình phải có một bài toán ở đây đó
[00:54:10] là không quay vòng cái gì cũng nghe rồi
[00:54:12] Ông nhầm đấy nhá web là là để mà lọc
[00:54:15] từng thằng một thôi chứ để lấy tên cột
[00:54:23] ạ Bây giờ thì bản thận bản chất của vấn
[00:54:26] đề ở đây đó là gì đó là cùng cái bạn
[00:54:28] nhân viên này nhưng mà tôi chỉ cho ông
[00:54:31] lấy một vài cột của bà ngày thôi đúng
[00:54:34] không Thì nó có khái niệm là view View
[00:54:36] nó sẽ là dịch ra là góc nhìn đúng không
[00:54:39] nó sẽ là mình chỉ được xem những vài
[00:54:42] thông tin chi tiết là sử ở đây là sửa
[00:54:44] đây mình có bảng sinh viên ở trọ sự thế
[00:54:46] Ngon
[00:54:48] Ừ mình nào không bảo nhân viên mình lấy
[00:54:51] tạm bán sinh viên nhé sự đây mình lấy
[00:54:54] được toàn bộ thông tin này Đúng chưa là
[00:54:57] sử ở đây Cứ kệ không có dữ liệu gì cậy
[00:55:00] nha đúng không ạ sử bây giờ ra sự là một
[00:55:03] mã còn lại cảm đi mình không được phép
[00:55:06] lấy một mã thì mình lấy như này chờ tiếc
[00:55:08] đúng không Nhưng thằng nhân viên Đương
[00:55:10] nhiên là sẵn như mình vừa nói nó không
[00:55:13] tội gì mà đi đầy đủ ra như thế này mà nó
[00:55:15] sẽ lấy xe Lexus Vì sao rồi mong đấy do
[00:55:18] bây giờ mình sẽ tạo Grand view này rồi
[00:55:20] mình đặt tên là gửi bưu đấy các bạn sẽ
[00:55:25] để mua db2 này các bạn sẽ không động đây
[00:55:27] nhờ cũng động sanrex in-shop các thửa
[00:55:29] thường nhưng mà mình không giảm cái đấy
[00:55:31] nữa mà mình sẽ chủ yếu là các bạn với
[00:55:33] mấy cái câu lệnh liên quan kiến crash
[00:55:35] này về chưa
[00:55:37] tô màu luôn có điệp khúc đầu là crash
[00:55:40] xong mà tên của cái đấy dụng led vừa rồi
[00:55:42] Các bạn hãy press Index này thì bây giờ
[00:55:45] này là qlistview này chưa redwood tên
[00:55:48] của cái đấy tên của đấy ra xưởng mình là
[00:55:50] tên là à
[00:55:55] i-view họ tên sinh viên em ạ nghĩa không
[00:55:58] có một mã đấy đúng không ạ sau đó các
[00:56:00] bạn thêm chữ Apps nói là sau đó mình sẽ
[00:56:01] thử nhé
[00:56:06] ở đó thế này xong rồi và bây giờ thằng
[00:56:08] một thằng cái thằng lập trình viên Liên
[00:56:11] Kiệt nó nó không được động vào bản sinh
[00:56:14] viên ở luôn mình khóa luôn không cho
[00:56:16] động vào bạn sinh viên nữa nó chỉ được
[00:56:19] động động vào vi vậy thôi và nó bây giờ
[00:56:23] nó chỉ cần select sao form cày view này
[00:56:27] Ừ thì bạn sẽ thấy đó nó sẽ chỉ ra cột họ
[00:56:30] và tên thôi để trưa Nó sẽ không có cục
[00:56:34] mã và bây giờ Bây giờ mình thử cho các
[00:56:38] bạn xem thử nhé Bây giờ sửa mì Asus là
[00:56:40] bạn sinh viên này bởi vì cột mã mình
[00:56:42] không tự động tăng nên là mình phải điền
[00:56:45] vào cột mãi nhá sẽ giao lưu mã là một
[00:56:49] này Long này
[00:56:53] này nghĩa này trở lại mình mình cứ ghi
[00:56:56] ngay tại nhé Nói xuất để có một rồi đúng
[00:56:59] không Bây giờ sự là select for xà phòng
[00:57:03] này đó các bạn thấy là cái view nó vẫn
[00:57:07] sẽ kế thừa nó sẽ đối chiếu đến thăm gốc
[00:57:09] và thằng sinh viên để lấy thông tin về
[00:57:11] chứ không phải mất công Insert vào trong
[00:57:16] bảng không có khái niệm là bạn ở bảng hả
[00:57:19] bản này mà nó bản chất nó làm review nó
[00:57:22] sẽ là kiểu giống như các bạn chia sẻ ví
[00:57:24] dụ ở đây anh mình đang có hai cái màn
[00:57:26] hình để mà livestream này không các bạn
[00:57:28] bạn sẽ các bạn chỉ được phép thấy một
[00:57:30] màn hình một cái view của mình thôi mình
[00:57:32] không cho các bạn xem cái vi của lại
[00:57:35] đúng không Đấy cái view nó như thế cái
[00:57:37] video này ngoài liên quan đến bảo mật
[00:57:39] như thế nào có liên quan đến tốc độ xử
[00:57:42] lý của nó sẽ nhanh hơn Tại sao giờ mình
[00:57:44] sẽ ví dụ tiếp cho các bạn
[00:57:52] Ừ đúng rồi bây giờ như mình đã nói là
[00:57:56] bây giờ mình sẽ khóa không cho cài nhân
[00:57:58] viên CIA sẽ Lexus Phong Bản sinh viên
[00:58:01] nữa hoặc hoặc bài toán thực ra đơn giản
[00:58:04] thôi Nó là thằng nhân viên kia nó không
[00:58:07] biết được bản gốc là bạn nào thế được
[00:58:09] bởi vì
[00:58:12] anh bởi vì yêu cầu u
[00:58:16] anh bởi vì ở bây giờ mình đã ẩn ẩn cái
[00:58:19] bảng tên là sinh viên rồi mà ngon thì nó
[00:58:22] một là nó phải tra chuẩn nó phải gõ được
[00:58:26] chính cái tên ba nhưng mà không Nó gần
[00:58:28] như là các bạn thấy là thực là
[00:58:31] sau khi mà giới hạn quyền như thế thì nó
[00:58:33] sẽ giới hạn luôn Theo bạn luôn các bạn
[00:58:41] em về cái khái niệm giới hạn quyền sâu
[00:58:44] hơn nữa thì về sau càng càng môn db2 này
[00:58:48] muốn db2 này là để hướng dẫn các bạn
[00:58:51] Ừ thứ nhất là để cho luôn nằm ngang hơn
[00:58:52] này các bạn sẽ thấy gần như toàn bộ
[00:58:54] những cái ở đây nó đều tự giúp cho nhanh
[00:58:57] hơn và thứ hai là nó liên quan đến bảo
[00:58:59] mật hơn được chưa nó liên quan mà một
[00:59:01] cành những buổi sau này mình dậy thì các
[00:59:03] bạn sẽ đấy Ui nó hai dãy nó càng khóc
[00:59:06] đúng kiểu càng sâu rồi bảo mật hơn nhân
[00:59:08] viên không được phép tự ý Bây giờ giả sử
[00:59:12] của ông nào Delete 1 phát cả hoặc lốp
[00:59:14] một phát cả cái bàn đúng không thì chết
[00:59:16] là đúng không Thì nó liên quan đến bảo
[00:59:18] mật rất rõ việc là Delete Insert update
[00:59:21] Delete Nói chung ngoài thậm chí là nhân
[00:59:23] viên mà không cái thằng ông lập trình
[00:59:25] viên đấy ông ấy còn không biết được tên
[00:59:28] cột là gì luôn không biết là tên bảng là
[00:59:31] gì luôn bởi vì nó bảo mật và phải đến
[00:59:33] mức độ đấy nó không được phép biết tên
[00:59:36] bảng tên cột nữa em đi chưa thì những
[00:59:38] buổi sau này mình sẽ dạy càng dậy vì sau
[00:59:40] các bạn sẽ thấy càng thấy hay thì chưa
[00:59:48] Ừ đấy nhưng mà ok thì các bạn vừa rồi
[00:59:51] Thầy qua về việc lưu này nhưng như mình
[00:59:53] đã nói là nó sẽ giúp cho nhanh hơn Các
[00:59:54] bạn thấy thực ra không nhanh hơn như cả
[00:59:58] lại Ừ cái câu này đã mất công tạm vi rồi
[01:00:01] sau đó nhỉ câu này với câu này thì ra là
[01:00:05] tốc độ cái kiểu cái dòng lệnh ấy Các bạn
[01:00:07] thấy rõ ràng câu này trong còn dài hơn
[01:00:08] gấu này đúng không hả Chạy con này còn
[01:00:19] Ừ thì bây giờ bạn bản chất là ở cái bưu
[01:00:22] này nhá Ừ nó
[01:00:26] vì nó có thể liên quan đến nhiều bạn của
[01:00:30] một lúc là sửa đây mình có bạn là bạn à
[01:00:39] thì mình cứ tạm giúp thai bồ sinh viên
[01:00:41] ấy nhé
[01:00:43] em thừa giúp thai bổ sinh viên này các
[01:00:46] bạn Thể thờ ơ cái thằng view này kia nó
[01:00:48] sẽ lách bởi thằng sinh viên này đúng
[01:00:51] không như thằng view này nó độc lập nó
[01:00:53] không được lốp đâu thì các bạn sẽ AK sao
[01:00:54] như thế này nó chỉ đơn giản nó báo lỗi
[01:00:57] rồi là không tìm thấy thằng sinh viên
[01:01:01] này nghe các bạn phải phải luôn cả thằng
[01:01:08] Ê bà chính với các bạn thấy là thằng
[01:01:12] video này đang độc lập với thằng sinh
[01:01:15] viên thành ra là bây giờ Đấy lý do mà
[01:01:17] bây giờ mình tạm thêm bảng lớp sau đó
[01:01:18] thì mình
[01:01:23] Mình lưu lại nó kết kết hợp giữa cả bằng
[01:01:25] lớp và các bạn sinh viên thì sẽ như thế
[01:01:28] nào với mình tặng tạo bằng lớp này Ok
[01:01:31] này mình Copy lại cái thằng này xuống
[01:01:33] dưới nhé á
[01:01:33] À
[01:01:37] mà đây mình sẽ có mã lớp này
[01:01:40] kiểu này
[01:01:46] bạn lớp
[01:01:49] a free Print
[01:01:50] ở
[01:01:58] cho các bạn sinh viên đó sau đó thì mình
[01:02:02] sẽ in sốt lớp
[01:02:04] a mã mình có bị tự động tăng đây là mình
[01:02:07] cứ ngập cả mã này là xưởng lớp lập trình
[01:02:08] này
[01:02:10] đây sát thủ này
[01:02:14] cô hồn đúng không và Insert
[01:02:20] vi phạm Zalo
[01:02:26] mã lợn mã sinh viên này tên này họ và
[01:02:29] tên đúng không Nguyễn này trở lại và mã
[01:02:37] Ừ được rồi đúng không mà bây giờ mình sẽ
[01:02:40] rách sao for Giả sử của xe Lexus form2
[01:02:42] bảng nữa nhé các bạn nhiều do không Mình
[01:02:48] sẽ roi lớp on lớp chấm mã bằng Sinh viên
[01:02:59] a Bill không phải copy data đâu nhá Cái
[01:03:03] này chỉ là cậu nó là thay thế cho câu c
[01:03:05] nách rồi mà nó không hề copy data
[01:03:08] Ừ đúng rồi chức năng là giới hạn snack
[01:03:10] đấy cậu lấy ra chuẩn đấy nghĩa nó sẽ
[01:03:12] chạy lại câu lệnh cernex thôi chứ nó
[01:03:14] không phải là tạo thành một bảng mới để
[01:03:17] mặt để mà copy data từ cái bạn từ cái
[01:03:19] bạn tra không Không không phải như thế
[01:03:22] đúng rồi nó tham chiếu về Chuẩn đấy thì
[01:03:25] bây giờ mỗi lần mình muốn lấy toàn bộ
[01:03:27] thông tin của sinh viên kèm với lớp 5
[01:03:29] mình phải trả lại câu lệnh này thay vì
[01:03:31] như thế Bây giờ mình thích thì mình cũng
[01:03:34] có thể tạm của cái view tên là sinh viên
[01:03:38] kèm lớp chẳng ạ Như này đó như thế này
[01:03:45] à à Đây đang bảo lỗi Cái lỗi này Thực ra
[01:03:47] cũng khá là hay may mà tự nhiên Hiền bị
[01:03:50] lỗi này để mình trả lời các bạn luôn đó
[01:03:53] là các bạn đọc kỹ lỗi đấy mình dịch ra
[01:03:57] các bạn nhé là cột trong mỗi view hoặc
[01:03:59] Phong trình phải là duy nhất unique là
[01:04:00] duy nhất đúng không
[01:04:05] một mã ở trong cái hại khi mà sẽ lách
[01:04:08] này thì cột mã lại đang gặp lại thành ra
[01:04:12] nó báo là lỗi thì chưa bảo Lặp lại nên
[01:04:16] là lỗi thì bây giờ mình có thể ghi mình
[01:04:18] phải ghi rõ ra là sự mình lấy á
[01:04:22] thông tin sinh viên này nhờ mình không
[01:04:23] lấy
[01:04:27] Ừ mình không lấy cột à ra xử mình thông
[01:04:29] tin sinh viên mình vẫn đầy đủ đi Nhưng
[01:04:32] mà thông tin Lớp mình chỉ lấy cột tên
[01:04:34] của lớp thôi mình không lấy cột mã của
[01:04:35] lớp nữa
[01:04:38] cho các bạn xem thử nhé thì đây thấy rõ
[01:04:41] ra là không có cột nào là cột kiểu nó bị
[01:04:43] lặp lại bị trùng đúng không thì các bạn
[01:04:44] class đường này
[01:04:52] như thế lại phải sửa lại tiếp đúng không
[01:04:55] Chắc mình phải ghi rõ ra rồi mình sẽ ghi
[01:04:59] rõ ở đây là mã sinh viên đi rõ hết ra đi
[01:05:02] sinh viên chấm Họ này
[01:05:09] à À không không không không thì ra không
[01:05:11] cần như thế
[01:05:15] Mình ở đây ác tên lớp và được mà
[01:05:30] ở đó được rồi đúng không ạ Và bây giờ
[01:05:34] mình chỉ cần select sao for cái view này
[01:05:40] Ừ thế bạn thấy là cái câu lệnh select
[01:05:42] này chắc chắn nó sẽ ngắn hơn cái câu
[01:05:43] lệnh này đúng không
[01:05:46] khi bé gần nhất thứ hai cái bài toán ở
[01:05:49] đây từ B2 các bạn học bạn sẽ thấy là
[01:05:53] những cái clip này tạo ra ấy nó sẽ được
[01:05:55] lưu lưu lại đúng không sẽ giảm nó sẽ
[01:05:58] được lưu lại và mỗi khi là mình truy vấn
[01:06:01] đến cái được lưu lại này tốc độ nó nhanh
[01:06:03] hơn đến việc các bạn phải ghi lại một
[01:06:06] câu lệnh đầy đủ như thế này và khi người
[01:06:09] bạn Các bạn truyền cái con lệnh này lên
[01:06:11] một con server thì đương nhiên có lệnh
[01:06:13] càng ngắn càng ngắn như thế này này đúng
[01:06:15] không tốc độ nó sẽ càng nhanh hơn Nói
[01:06:16] chung là cái này vẫn liên quan đến bài
[01:06:21] Toản à tốc độ là nhanh hơn đây
[01:06:23] a mã chạy nhanh hơn vì đã biên dịch là
[01:06:25] câu lệnh nhé
[01:06:26] em không cần phải viết lại câu truy vấn
[01:06:30] nhé ờ ờ chuyện câu lệnh lên sơ cho nhanh
[01:06:32] hơn với bị nó ngắn hơn nữa nhé và bảo
[01:06:36] mật hơn về chưa để tác dụng của Bưu đó
[01:06:39] còn cách xóa như nào thì các bạn cũng
[01:06:41] vừa thấy mình sẽ chọn group như này đúng
[01:06:43] nó bị xóa
[01:06:46] ở đó thì các bạn vừa rồi nghe được qua
[01:06:50] Iraq và view chữa như mình đã nói cú
[01:06:52] phát của nó rất là ngắn thread in black
[01:06:54] mask review xong là tên của cái đấy
[01:06:58] không xong rồi Thế là xong đúng không Nó
[01:07:01] chẳng có gì kiểu khó cả tôi đấy mình
[01:07:03] được dạy Cái này đúng kiểu cải cả buổi
[01:07:07] học indec và view mình chưa mất nổi 5
[01:07:09] phút để học xong cái cú pháp của nó
[01:07:12] trong ngồi thầy ra bài tập là em tạo
[01:07:14] nhiều video tạo nhiều hình a tạo Đúng
[01:07:16] rồi Tại nhiều view tạo nhiều Index vào
[01:07:18] cho quen hết mình thương sửa mình không
[01:07:20] hiểu ý nghĩa của cái đầu lắm nhớ khi
[01:07:23] mình mình đọc kỹ lại về mình cái được
[01:07:26] pv2 này mình thấy thực sự rất là hay
[01:07:27] đúng không
[01:07:30] cái Story bootcd về sau mình sẽ dạy các
[01:07:33] bạn nhé và Story Mode của nó khái niệm
[01:07:35] khác hoàn toán
[01:07:37] khi trích đoạn
[01:07:40] Ok Bây giờ là lại đến cái giây phút mà
[01:07:42] nhiều người đợi nhất
[01:07:46] chứ không phải xem bóng đá rồi nhé mà sẽ
[01:07:52] Cho xem về hết khủng đúng không Mình đã
[01:07:54] từng nọ à mình đã từng
[01:07:57] chủ đề cập ở đây đó là
[01:08:01] Ừ nếu hacker hack được dp của bạn thì
[01:08:04] Ừ thì bạn làm thế nào để phòng chống
[01:08:07] trước khi giao sự Cứ chắc chắn các bạn
[01:08:09] sẽ bị hack đã làm cách nào để nó không
[01:08:12] vì nó không hiểu
[01:08:15] đọc được thông tin nhạy cảm các thứ thứ
[01:08:22] cho mình nhớ là mình có lưu cũng
[01:08:23] ờ ờ
[01:08:26] khi nhìn thấy hình bài bị xóa được mở
[01:08:41] số bài toán ở đây anh ngày đề cập gia sử
[01:08:44] vì 1 ngày đẹp trời các bạn
[01:08:47] thay thay được con máy tính mới
[01:08:49] thì các bạn vứt có máy tính đi vào sọt
[01:08:52] rác sau đó thì tự nhiên một ông ở đó ông
[01:08:54] nhặt được con ổ cứng của con máy tính cũ
[01:08:57] các bạn vào trong đấy có database của
[01:09:01] một triệu khách hàng khi cài đặt ra bay
[01:09:02] đầy đương nhiên như mình đã nói là các
[01:09:04] bạn kiểu gì cũng phải lưu thông tin
[01:09:07] email và mật khẩu khách à để mà khách
[01:09:09] hàng để đăng nhập được đúng không Thế
[01:09:12] nên không có chuyện mà rút ổ cắm cả rút
[01:09:14] server Nhưng mấy ông kia em nói thì bài
[01:09:16] toán ở đây là khi mà khách cơ khách được
[01:09:22] vào đã ta bây nó xem được gió mây thì nó
[01:09:24] cũng không đăng nhập được vào tài khoản
[01:09:26] khách à
[01:09:28] cô giáo sư nó không có quyền để mà sửa
[01:09:31] thông tin các thứ nhưng mà nó vẫn đọc
[01:09:33] được đấy thì nó không đăng nhập được vào
[01:09:36] tài khoản Thế nhà thì đấy gọi là tao
[01:09:39] bệnh ổn hiểu chứ mấy ông cứ bảo rút dây
[01:09:43] nguồn cái thứ thứ thì thì lúc đấy Quá
[01:09:45] Muộn rồi Nó đã copy xử với dữ liệu đấy
[01:09:53] Ừ nó copy sửa dữ liệu đấy Sao mày nói
[01:09:55] thì mày ông rút nó trả nghĩa gì cả đúng
[01:09:57] không Bây giờ quan trọng là khi nó có
[01:10:00] rồi thì làm thế nào để nó không đăng
[01:10:02] nhập được Vào nó không dịch ngược được
[01:10:04] bởi vì ngoài việc nó không đăng nhập
[01:10:06] được vào nhé Có rất nhiều ông ở đây tôi
[01:10:08] nói thẳng rất nhiều ông ở đây đang dùng
[01:10:11] một mật khẩu của một tài khoản à Dùng
[01:10:13] một mật khẩu cho nhiều tài khoản mạng xã
[01:10:16] hội luôn Ví dụ loa kéo anh hiểu là i
[01:10:19] love you Hay mật khẩu tên là password
[01:10:22] mật khẩu để password Anh chưa thế cho
[01:10:24] rất nhiều tài khoản mạng xã hội nghĩa
[01:10:26] thằng kia mà biết được email của ông
[01:10:28] thằng kia mà biết được mật khẩu rồi nó
[01:10:29] thử đăng nhập cái tài khoản đấy vào
[01:10:32] Facebook của ông mà vào được thì ra đúng
[01:10:39] Ừ thì tính ra trước đấy gì à
[01:10:41] Thì hack khách hàng đi kiện thành lập
[01:10:43] thì việc
[01:10:45] anh không đúng không Bây giờ mình phải
[01:10:47] giải quyết bài toán đấy để tránh bị kiện
[01:10:48] đúng
[01:10:54] à à
[01:10:57] Ừ đấy thì cái bài toán ở đây là các bạn
[01:10:59] có nhiều bạn đã biết qua về cái khái
[01:11:02] niệm là lưu mật khẩu không nên lưu dạng
[01:11:05] grentech tất cả lưu lại mật khẩu là vô
[01:11:08] nghĩa là mình mình lưu đúng được 123 là
[01:11:12] 123 luôn đấy là kiểu thôi như thế Do thô
[01:11:14] thì ra thằng Facebook thôi gần đây nó bị
[01:11:17] dính vào cái vụ labjack này là nó đúng
[01:11:20] là lưu lại mật khẩu thô thế của người
[01:11:23] dùng bao nhiêu triệu tài khoản tại mình
[01:11:24] chả thử các bạn xem
[01:11:32] Ừ nó lưu lại đúng mật khẩu của khách
[01:11:34] hàng là dạng thô trong nhiều năm liền
[01:11:35] đấy
[01:11:39] 300 triệu trăm triệu tài khoản Nếu chưa
[01:11:41] xử mà hacker mà Hack đầu vào bê hoa cao
[01:11:45] ra xử giả sử như là lập trình viên của
[01:11:49] Facebook select sao được for bảng user
[01:11:54] mà không dùng view đáy đề cập heo để cập
[01:11:57] cái nước đi với học đúng không Thì tự
[01:11:59] nhiên lại thấy cái cột email password
[01:12:04] đấy và và nó kiểu không hay mã hóa gì cả
[01:12:06] đúng không ai vào đọc cũng đọc được thế
[01:12:07] thì vui lắm
[01:12:10] anh ở đây ở dưới này bọn nó khẳng định
[01:12:13] này thằng thằng Facebook nó bảo lại đã
[01:12:16] là lập trình viên Chúng tôi có thể truy
[01:12:18] cập được nhưng mà chúng tôi không làm gì
[01:12:20] cả Chẳng chẳng ai tin được cái lời ông
[01:12:24] đấy đúng không nghe có lại toàn rồi ông
[01:12:28] thế nên phải toán ở đây là là
[01:12:30] ừ ừ
[01:12:32] thì các bạn sẽ
[01:12:36] chị sẽ phải dùng cái một cái gọi là hát
[01:12:39] là mã hóa mã hóa mật khẩu ở đây nó có
[01:12:42] khuyên là không nên dùng những cái hà mã
[01:12:44] hóa này Tại sao lại thế
[01:12:47] a cho dù hà mã hóa này hiện tại có thể
[01:12:49] dịch ngược được ra không không dịch
[01:12:52] ngược ra nhưng tại sao Thế thì bài này
[01:12:55] sẽ đề cập thì chưa Bên mình sẽ cho các
[01:12:57] bạn một ví dụ rất đơn giản nhé ra sự
[01:13:00] khẩu mình em 123 đây như mình mã hóa nó
[01:13:03] lại nếu mà giờ xử có nhiều ông khái niệm
[01:13:07] là bây cốt 64 em ạ thường mà chẳng đây
[01:13:09] cũng là một kiểu mã hóa bình thường em
[01:13:11] mã hòa như này để chiếc bạn bè ở chính
[01:13:14] tại sao Bùi việc mã hóa này có thể dịch
[01:13:16] ngược được ra sự là
[01:13:21] nó là bay cốt 64 đúng không
[01:13:23] Tôi thường ai chưa Bạn bè tôi là như thế
[01:13:26] này cách cách cách trêu của lập trình
[01:13:29] viên nó sẽ thiếu rồi nha đã sự tôi sẽ gõ
[01:13:32] lại trẻ trâu đấy Chẳng ạ
[01:13:35] Tôi thường này kiểu gì như thế này nếu
[01:13:37] mà ông nào lên tường là tôi thương chị
[01:13:38] Thoa tôi sẽ bình luận như này và nếu
[01:13:40] chẳng hiểu gì cả
[01:13:43] mà nó lại êm cốt nha là mã hỏa nhé
[01:13:47] xe tải mã khóa này Đấy nó sẽ ra đoạn này
[01:13:49] thôi Tôi thường ấy copy đoạn này đi trêu
[01:13:51] trêu
[01:13:55] sử dụng mày thật như này xong rồi đoạn
[01:13:59] Mã hóa sau đấy thì có nhiều ông nếu mà
[01:14:01] ông không biết cha thì ông sẽ cháy nhiều
[01:14:02] cái đoạn này là gì Chẳng biết nó chửi
[01:14:05] mình nghe Nó khen mình cái cơ Thế Nhân
[01:14:07] nếu mà ông ấy tra được ví dụ đi cốc đúng
[01:14:09] không Ngoài tra dịch ngược Lai đứng yên
[01:14:12] này kiểu sẽ ra nha ấy bạn mày theo dõi
[01:14:14] trẻ trâu không
[01:14:17] Ừ tôi sẽ Châu tôi biết mẹ em không có lẽ
[01:14:20] Em chuẩn bị chat tôi chạy sâu đâu
[01:14:21] Ừ
[01:14:25] đấy thì thì chúng ta không nên dùng
[01:14:28] những cái loại mã hóa mà có thể dịch
[01:14:30] được được như thế để lưu lại mật khẩu
[01:14:32] người dùng đúng không Bởi vì bởi vì
[01:14:35] thằng ai cờ nó thể dịch được đúng không
[01:14:38] Thì ở đây nó có đề cập bạn này có đề cập
[01:14:40] liên quan đến cả 10 năm 10 năm thì nó
[01:14:43] hiện tại nó không để dịch ngược được
[01:14:45] mấy cái mã hóa này nó rất khó để dịch
[01:14:48] Nhược nhìn như không thể đây thì các bạn
[01:14:52] sẽ tra là em cốt 10 năm em ạ
[01:14:57] anh hỏi ra gì cả online này đây khi ra
[01:15:00] xử mình sẽ mã hóa thử 123 nhé các bạn
[01:15:02] thấy nó sẽ ra hẳn một cái đoạn Mã hóa
[01:15:05] md5 hoặc là sát như thế này đúng không
[01:15:08] chưa nó sẽ ra một cái đoạn như thế này
[01:15:10] và các bạn không dịch ngược được cái này
[01:15:13] ra các bạn có thể tra Google là kiểu đi
[01:15:16] cốt là định dịch ngược ra nó có thể ra
[01:15:18] được cái trang này những trang này điêu
[01:15:21] đấy nó không dịch được đâu nó chỉ nó chỉ
[01:15:25] so sánh vừa những cái thằng mà đã nó đã
[01:15:29] dịch sang từ 123 sang số này ạ Từ số này
[01:15:33] nó nó sẽ gọi là search như này để xem có
[01:15:36] ra được cái thằng góp 20 đấy thì thôi
[01:15:39] chứ nó không dịch ngược được ra thì chưa
[01:15:44] Ừ Thì bài toán ở đây nó cũng là như thế
[01:15:46] nếu mà ông mà
[01:15:47] Ừ
[01:15:51] nếu mà ông mà mã hóa mật khẩu 123 nó sẽ
[01:15:53] ra một cái con số như thế này đúng rồi
[01:15:55] nó khái niệm từ điển lại nó khái niệm ở
[01:15:58] đây nó để tôi đọc vì cái ông nhé Nó
[01:16:01] Rainbow table tức là
[01:16:05] tin tức là nó khái niệm là
[01:16:08] Đó là kiểu nó sẽ tạo ra âm cái bảng và
[01:16:11] bảng ấy sẽ lưu lại mật khẩu mật khẩu thô
[01:16:13] mật khẩu đã mã hóa khi nó chìm việc So
[01:16:15] sánh mật khẩu đã mã hóa đấy thì nó thể
[01:16:18] ra được mật khẩu thô của ông đúng trước
[01:16:22] Ừ đấy Nó kêu từ điển và kiểu vét cạn mấy
[01:16:25] ông kia nói xa chuẩn và khái niệm nó nên
[01:16:27] bông thấy bồ được chưa
[01:16:30] Tại sao không dịch ngược được bởi vì à
[01:16:33] Cái máy ghế hà mã hóa này mình không nhớ
[01:16:35] Chính xác vì cách nó mã hóa như nào đâu
[01:16:37] nhưng nó cắt chuỗi rồi các thử nó lằng
[01:16:41] lằng nhằng lắm nhưng mà như mình đang đề
[01:16:46] cập ở đây là nó giả sử nó có cái lưu lại
[01:16:50] hẳn Rainbow thấy bồ đến hàng tỉ bản ghi
[01:16:53] đúng không Nó đã mã hóa rất nhiều về cụm
[01:16:57] từ rồi Thế nên là hoàn toàn là khi mà nó
[01:17:01] so sánh Giả sử các bạn đang dùng cái mặt
[01:17:04] cái mật khẩu lưu lại là như thế này
[01:17:06] không Nó hoàn toàn biết được
[01:17:09] cái mạnh cái mật khẩu gốc của các bạn là
[01:17:12] 123 mất rồi bởi vì nó tra theo đơn mâu
[01:17:13] thấy bồ để ra đúng không
[01:17:16] Vì thế nên là các bạn sẽ không dùng mày
[01:17:19] cái mật khẩu mà đến năm này hai cái
[01:17:22] sharp1 này được nữa Bởi vì ạ
[01:17:28] a123 md5 cho dù cho dù các bạn bây giờ
[01:17:30] mã hóa hay là ngày mai hay ngày kia mã
[01:17:33] hóa nó vẫn chỉ ra cái cụ mày thôi
[01:17:34] thì tại sao tự nhiên mình phải đề cập
[01:17:37] với thời gian ở đây bởi vì tức à
[01:17:40] ở cây chuối này không ở thay đổi thì cái
[01:17:42] đoạn Mã hóa không bao giờ thay đổi thế
[01:17:44] nên là thằng hacker mà một khi nó đã có
[01:17:47] cái bảng giờ xử thằng hacker nào bây giờ
[01:17:49] còn ngựa chẳng có cái bên bố người bồ để
[01:17:52] nó thì dịch ngược được ra mật khẩu của
[01:17:55] các bạn mà lượng người dùng dùng mật
[01:17:57] khẩu phổ biến rất là đông đúc Như à
[01:18:01] Thống kê là người loại mật khẩu phổ biến
[01:18:03] nhất thế giới giống như tôi vừa nói có
[01:18:06] cả mật khẩu tên là a i love you Này Hack
[01:18:07] password này
[01:18:10] hai ông kia vừa nói là anh yêu em mà Thì
[01:18:13] phải đấy như có đấy Việt Nam mình nằm
[01:18:16] trong cũng nằm trong danh sách mật khẩu
[01:18:19] kiểu để ra đơn giản đấy thành ra là ông
[01:18:23] nào mà bể mật khẩu là ai love you
[01:18:25] chẳnghạn đây không ai là kiểu này ạ khi
[01:18:30] xảy ra cái cụm này gì đúng không
[01:18:33] Ừ thì hoàn toàn là giả sử hacker có cụm
[01:18:35] này và nó sẽ là ai love you rồi đúng
[01:18:38] không có phải nó lại nó sẽ đăng nhập
[01:18:41] được tất cả những cái ông tất cả những
[01:18:43] người ông nào còn mật khẩu là i love you
[01:18:49] anh không không không phải đoán đun cách
[01:18:51] mã hóa nếu mà các bạn làm random cái mã
[01:18:53] hóa thì lại phức tạp theo cửa các bạn
[01:18:55] không đăng nhập được đúng không
[01:18:58] ở đây đây Thế nên là bây giờ cách giải
[01:19:00] quyết bài toán nó là như thế này được
[01:19:02] chưa cái giải quyết bài toán nó là như
[01:19:03] thế này
[01:19:07] anh ở đây Bạn để anh đấy đi Cập là phải
[01:19:10] thêm Sam San dịch Cả thêm muối tất cả
[01:19:13] Sao ở đây nó như thế này
[01:19:16] ạ Bây giờ giả sử là mình sẽ
[01:19:20] thì mình sẽ thêm một tí muối là ABC như
[01:19:23] này xong rồi Ghét với mật khẩu có bạn
[01:19:25] 123 kết hợp với a b c
[01:19:29] Ừ để mã hóa nó ra cũng ở dùng hàm ở đến
[01:19:32] năm nhé Đấy nó sẽ mã hóa nó sẽ ra như
[01:19:39] Ừ tao nó sẽ ra ngay đúng không các bạn
[01:19:42] lưu nó lại và ô ngoài cũng là một hai ba
[01:19:45] giờ xử lý thế nhưng mà
[01:19:48] cách muối của mỗi ông khác nhau đúng
[01:19:51] không Thì có ông mặn có nhạc đúng không
[01:19:54] ngủ mỗi khác nhau lại cái rét em ạ thì
[01:20:01] anh đúng không
[01:20:05] đó thế là xong Ừ thì rõ ràng mà tui
[01:20:09] hacker em có thứ nhất là Hacker sẽ khó
[01:20:12] đoán hơn cái mật khẩu gốc của các bạn vì
[01:20:15] là nó sẽ phải kết hợp thêm cả xa nữa
[01:20:18] đúng không để mà ra được mật khẩu đấy
[01:20:21] Cái thứ nhất thứ hai là
[01:20:23] khi bé lý do mà được nhiều ông cũng
[01:20:26] nhiều nhiều nơi nó vẫn khuyến cáo công
[01:20:29] lên để mật khẩu Nó khá dài và kết hợp
[01:20:30] trình tự đặc biệt để cho thằng ấy cơ nó
[01:20:33] không dùng Rainbow table để đoán được
[01:20:36] chứ mày cái chữ mấy kịch mật khẩu của
[01:20:38] mấy ông chỉ toàn số hãy chỉ toàn là chữ
[01:20:41] thì chắc chắn là có nằm trong cái danh
[01:20:43] sách Rainbow table của nó rồi mà nó tra
[01:20:45] ra rất là nhanh
[01:20:50] Ừ ok thì thực ra là đến đến cái ngưỡng
[01:20:53] mà thêm cái San như thế này là thằng
[01:20:55] hacker nó rất vất vả để dịch ra đường
[01:20:59] mật khẩu các bạn rồi được chưa Ừ nhưng ở
[01:21:03] đây bạn này vẫn bảo lắm Nếu giả sử là
[01:21:07] thái cơ nó có một con siêu máy tính nó
[01:21:10] vẫn có thể ghét hay hài về nhau để mà
[01:21:14] dịch ngược được để mà tạo ra đầm ren ren
[01:21:17] bông hay bù đấy trăm tỷ chịu thì bạn ghi
[01:21:20] để mà nó vẫn ra được những cái mã hóa
[01:21:23] này để mà lấy lấy được tài khoản đúng
[01:21:26] không Thì cái này một điểm hay này chính
[01:21:29] vì xa này đang khắc khác nhau nên là cho
[01:21:31] dù nó dị ngược được của ông này thì
[01:21:34] không có nghĩa là ông này cùng mật khẩu
[01:21:36] nhé cùng Mật khẩu nhà đúng không Thì
[01:21:39] cũng không Nghĩa là ông nó vào vào được
[01:21:42] của ông này đúng không em trước đấy Cái
[01:21:44] điểm hay của xa này Nghĩa giả sử nó cố
[01:21:46] để hack được một người thì cái người
[01:21:49] cùng chung mật khẩu cũng không chưa chắc
[01:21:51] đã bị hack bởi vì hai ông xa khác nhau ở
[01:21:54] đây nhưng mà bài toán như mình vừa nói
[01:21:57] giờ xử nó có con siêu máy tính nó thể dò
[01:22:00] ra được đúng không Nó vẫn do đã được thì
[01:22:03] thêm một cái nữa là thêm paper được chưa
[01:22:06] rất nhiều công ty đặc biệt liên quan đến
[01:22:08] bảo mật bây giờ thì ngay có thêm cái này
[01:22:12] thì cách paper paper là dung dịch là mùi
[01:22:13] tiêu
[01:22:15] 3 cách bơ bản chất à
[01:22:19] cho mình mình sẽ mã hóa cả San cả
[01:22:21] password và kết hợp với paper thôi Nhưng
[01:22:24] mà cái popup này thì sao cái tơ này thì
[01:22:27] một là ông lưu thẳng vào trong cốt
[01:22:30] à hài hài giả sử là tôi thường ngồi
[01:22:33] trước tôi làm ở công ty cũ tổn thưởng
[01:22:35] ngày lưu lại ví dụ là tôi hội đấy làm ở
[01:22:38] trường mà không lưu sự là thêm cái chữ à
[01:22:41] bách khoa này chẳng hạn BK này một cái
[01:22:44] thiện trước năm à Xong rồi tôi mã hóa cả
[01:22:49] ba thằng ngày vào cái thi.can càng càng
[01:22:51] có nhiều chuỗi ghép vào với nhau thì có
[01:22:53] phải tăng độ phức tạp lên không đúng
[01:22:55] không để cái thứ nhất thế hay là như tôi
[01:22:58] vừa nói là cái này lại không
[01:23:00] anh lại không lưu ở trong đầy bể không
[01:23:02] đi ở trong B các bạn lưu ý thẳng vào
[01:23:04] trọng cốt hoặc là lưu lại và trong có
[01:23:06] ông kia đang bảo lưu trong file
[01:23:08] khi cài đặt
[01:23:12] hoặc cả lưu lưu lại ở đâu đấy nói chung
[01:23:14] và cơ thể xong ngồi ghét cái đoạn đấy
[01:23:16] vào với nhau thì tăng độ khó lên rất
[01:23:16] nhiều
[01:23:19] ở đó thế thôi
[01:23:21] máy đánh bài tổng hợp này được ra tổng
[01:23:24] tập hợp nó là như thế nghĩa là các bạn
[01:23:27] thấy là thì các bạn vừa rồi được hiểu
[01:23:28] thêm về cái vụ là
[01:23:32] bí mật khẩu các bạn nó đang mông lung
[01:23:33] Nhưng mà trò đùa như thế nào đúng không
[01:23:36] và lập trình viên những cái nhà bảo mật
[01:23:40] sẽ có những cách nào để mã giải quyết
[01:23:41] bài toán đấy đúng không Các bạn thấy khá
[01:23:45] hay mà đúng không Nghĩa là khi mà
[01:23:48] sau Khi mặt thằng kia là sự có được
[01:23:51] database thì nó không thể đăng nhập được
[01:23:54] vào tài khoản các bạn - trong Facebook
[01:23:56] Facebook nó cứ để lỗ thông tìm người
[01:23:59] dùng suốt trai vãi thì
[01:24:02] Ừ thì có thêm những cái Tí muối này thêm
[01:24:05] tí hạt tiêu đúng không Thì sẽ giúp cho
[01:24:09] bảo mật nó ổn hơn chưa hi vọng sau này
[01:24:11] tôi không
[01:24:14] Ai biết đâu mấy ông lại về sau làm ra
[01:24:16] những cái trang web gì đó rồi tôi vào
[01:24:18] đăng nhập vào tự nhiên vì sao tôi bị mất
[01:24:21] nick Chỉ vì mày ông cốt đểu phong lưu
[01:24:22] mấy cái thông tin kiểu như này đúng
[01:24:25] không ạ
[01:24:29] ở đó thưa đó đó đã tổng hợp kiến thức
[01:24:33] của cả đội hôm nay kết hợp với thêm một
[01:24:35] tí kiến thức nữa rồi không
[01:24:37] ừ ừ
[01:24:39] từ lúc nhập mật khẩu như thế nào đúng
[01:24:42] không nhầm mật khẩu thì thì nó đơn giản
[01:24:45] thôi nó là nó là
[01:24:56] Ừ thì nó sẽ kiểu nó sẽ đương nhiên nó sẽ
[01:25:00] phải kết hợp buổi san của từng ông nó
[01:25:02] cộng ngồi san của từng ông 1 sau đó thì
[01:25:06] nó mã hóa để mà nó khớp với cái à ở khớp
[01:25:08] của cái mật khẩu đương nhiên nó sẽ lâu
[01:25:11] hơn một tí bởi vì nó cộng thêm xanh thậm
[01:25:13] chí paper Giống như mình vừa nói nhưng
[01:25:15] mà thực ra cái này là phải toán liên
[01:25:19] quan đến việc là kiểm tra mật khẩu
[01:25:23] Từ nay về sau vì sau mình sẽ dạy các bạn
[01:25:24] về hẳn
[01:25:27] anh xuống làm một cái trang web các thử
[01:25:38] ở Zalo bảo mật khuẩn không bị sẽ không
[01:25:40] đề cập về máy công ty lớn ở đây rồi sợ
[01:25:43] lắm à Công ty Việt Nam thì nữa đấy
[01:25:55] Ờ Ờ bạn kia đang nói về cách mà các ông
[01:25:58] lớn mã hóa như thế nào á cả ông lầm mã
[01:26:00] hóa thật cao có rất nhiều cách có thể là
[01:26:03] pepper + San + password nhưng có nhiều
[01:26:06] ông thì ngược lại là san của password
[01:26:09] Rồi mày cũng Tapper và compair rồi ông
[01:26:10] ấy công khai được thì các không quan
[01:26:13] trọng bởi vì sàn rồi password mã hóa nó
[01:26:32] Ừ đúng rồi thực sự thì về cái bảo mật
[01:26:34] thì nó vẫn chỉ ở mức tương đối mà đúng
[01:26:37] không Nếu mà thắng hai cô có siêu máy
[01:26:39] tính nó ngồi tra thì nó vẫn xảy ra được
[01:26:42] thôi Nhưng mà kể cái việc khiến cho nó
[01:26:46] phải rất rất khó xa hơn thì chỉ mới mới
[01:26:49] đạt được yêu cầu không
[01:26:51] Ừ thôi chào mọi người mọi người cha đi
[01:26:54] đá banh sẽ nhập Xem đá banh vui vẻ không
