# Dự án Web bán hàng - Cache & Git flow

- Video ID: `nrZrqIC5B1w`
- URL: https://www.youtube.com/watch?v=nrZrqIC5B1w
- Published: 2023-12-07
- Duration: 2h 01m 56s (7316s)
- Language: vi
- Subtitle source: auto
- Kind: live

## Transcript

[00:00:53] ừ nói chung về git
[00:00:56] đi
[00:00:57] À hôm nay chứ hôm nay n qu mắt hôm nay
[00:01:01] sẽ nói chung về git này Hôm nay buổi 3
[00:01:05] đúng không
[00:01:07] Ờ
[00:01:09] ừ hít cách mà còn gì nữa nhở chế là mình
[00:01:15] sẽ bổ sung cái này
[00:01:18] sau Alo chào các bạn ạ
[00:01:31] ạ
[00:01:36] thng thỉ thoảng mình cứ phả vào thử mic
[00:01:39] trước
[00:01:55] Ờ ch bạn thì hôm nay trước khi vào vào
[00:02:00] buổi kiểu mình live livestream code đây
[00:02:04] để để để mình mình ghi
[00:02:06] rõ hôm
[00:02:08] nay sẽ lại tiếp tục live code
[00:02:14] về lật trình web bán hàng
[00:02:21] à thực tế
[00:02:31] các bạn có thắc mắc tâm sự gì
[00:02:56] ừ hôm nay thì mình sẽ dạy
[00:03:00] kiểu chỉ qua các bạn biết về cách nữ cả
[00:03:03] git cách mình sử dụng như nào
[00:03:07] Ờ có bạn hỏi về design pattern đã cả
[00:03:11] repository
[00:03:12] ờ Thực ra thì hôm trước tôi có tôi có
[00:03:16] chia sẻ đó là tôi lúc đầu tôi định dạy
[00:03:20] các bạn về điều đấy Kiểu nhưng mà nhưng
[00:03:24] mà bản thân chính tôi kiểu khi đi làm
[00:03:26] thì đến thời điểm hiện tại thì vẫn chưa
[00:03:28] áp dụng một cách triệt để lắm
[00:03:31] và leader của tôi gần đây mới đang đập
[00:03:35] đi xây lại
[00:03:37] cái dự án để mà làm lại theo kiểu dạng
[00:03:40] design pattern này xong rồi
[00:03:44] Ờ xong rồi Kiểu nói chung là nó theo một
[00:03:48] cái hướng gì đó kiểu dạng là từng layer
[00:03:51] rõ ràng hơn
[00:03:52] ấy thì
[00:03:55] ờ Tôi cảm thấy là cái cái việc đấy thì
[00:03:59] thì bản thân mình chỉ cần biết qua về
[00:04:03] khái niệm và codt theo chứ thực ra là
[00:04:05] mình cũng không cần
[00:04:07] phải dùng từ không cần phải không đúng
[00:04:09] mình không thể đổ đổ cái trách nhiệm đấy
[00:04:12] cứ chỉ cho leader được nhưng mà nhưng mà
[00:04:15] có bài toán thực tế ở đây nhá Đó là một
[00:04:19] là ông vào hẳn một cái dự án mà đã có
[00:04:21] một cái design button rồi thì ông sẽ
[00:04:24] code theo cái đấy hai là ông vào cái dự
[00:04:26] án mà nó code nó cũng kiểu cũng tạp nham
[00:04:29] the kiểu là xử lý hết ở trong
[00:04:32] controller xử kiểu kiểu kiểu thế hoặc là
[00:04:35] thậm chí là còn dùng pp thuần nữa thì
[00:04:38] còn tệ hơn tôi mà bây giờ mấy ông bảo
[00:04:41] tôi là kiểu vào pp thuần ngồi cốt thì
[00:04:44] chắc là tôi sẽ nghỉ luôn Thôi không vào
[00:04:46] code được kiểu đấy nhưng mà nghĩa là chỉ
[00:04:51] là cái cái đấy cò phụ thuộc khá nhiều
[00:04:54] vào cái dự án mà ông sẽ tham gia vào
[00:04:57] nghĩa phụ thuộc vào khá Nhu nhiều V
[00:05:00] người đi trước và tập thể chứ không phải
[00:05:03] kiểu ông nghĩ ra một cái design button
[00:05:05] Hoặc là ông tham khảo được cái design
[00:05:07] buton ở trên mạng rồi ông ốp về là tất
[00:05:09] cả mọi người theo được Ông đúng không ạ
[00:05:11] thế này khó nên là nên là đấy là một cái
[00:05:16] đấy một cái mà tôi cảm thấy là
[00:05:19] kiểu mình không cần phải chú trọng biết
[00:05:22] quá rõ về cái des buton và gọi là mình
[00:05:26] chỉ cần biết nắm rõ lý thuyết theo kiểu
[00:05:28] theo kiểu này
[00:05:30] leader của tôi bây giờ à Kiểu đề xuất
[00:05:34] làm cái design button này thì anh em
[00:05:36] code theo cái design button đấy thôi ok
[00:05:38] nghĩa HM chỉ anh em cũng hiểu qua về
[00:05:41] cách viết op lẫn cả các layer các thứ
[00:05:44] chia rõ ràng chứ không cần phải hiểu xâu
[00:05:47] hơn vì vì cái việc đấy thì đúng là như
[00:05:50] tôi vừa bảo đó là leader may ra họ có
[00:05:53] thể thay đổi được cả một cái dự án cả
[00:05:56] toàn bộ anh em phải theo họ chứ bây giờ
[00:05:59] tính ra anh em mình thì vẫn chỉ Junio
[00:06:02] cùng lắm là có ông xo ở đây ngồi nghe
[00:06:05] tôi chém gió chứ cũng chưa lên đến cái
[00:06:09] mức độ cao hơn nếu mức độ cao hơn thì
[00:06:11] thực ra là không không ngồi nghe tôi làm
[00:06:13] gì cả vì họ cũng biết cách cần phải làm
[00:06:17] gì
[00:06:18] rồi Thế nên là tôi chia sẻ Thật là bản
[00:06:22] thân tôi cũng không dành về mấy cái đấy
[00:06:25] lắm để mà có thể dạy cho mấy ông và tôi
[00:06:27] nghĩ tôi nghĩ là
[00:06:29] là mình chưa cần
[00:06:32] phải chưa cần phải kiểu biết quá rõ về
[00:06:35] nó kiểu dạng là thực tiễn làm về nó quá
[00:06:38] nhiều không cần vì bản chất tôi vẫn
[00:06:41] thường hay nói mới ông là bản chất là
[00:06:43] tôi tôi đi làm không biết là tôi may mắn
[00:06:46] ha không Nghĩa là tôi không nắm rõ về
[00:06:48] thuật toán lắm này thậm chí là op vẫn
[00:06:51] chỉ và D button thì chỉ mức kiểu lý
[00:06:54] thuyết thôi
[00:06:56] đấy bởi vì tôi hồi học Java tôi tôi có
[00:06:59] qua môn này nhá Nhưng mà kiểu bởi vì hồi
[00:07:02] đấy học pp trước Java và tôi th tôi kiểu
[00:07:05] muốn hướng theo pp ấ nên thành ra là
[00:07:07] kiểu học Java chỉ qua môn thôi nên thành
[00:07:11] ra là như ông kia vừa nói dùng interface
[00:07:13] các thứ thứ hoặc là hôm trước là sếp Tôi
[00:07:16] bảo
[00:07:17] là nếu Giả sử mà anh mà phỏng vấn chú
[00:07:21] vào có khi anh loại chú khi mà anh hỏi
[00:07:23] cái câu ách class khác gì với face Các
[00:07:26] thử các
[00:07:28] thứ đấy Kiểu
[00:07:31] thế nhưng mà tôi vẫn làm được việc tôi
[00:07:34] vẫn khẳng định tôi là tôi làm được việc
[00:07:37] theo kiểu không phải làm việc việc xông
[00:07:39] đâu nhá mà tôi đang gánh trọng trách
[00:07:42] cũng khá nhiều cái tính năng quan trọng
[00:07:43] ở trên công ty và
[00:07:46] ờ và gọi như là tôi sắp tôi được làm
[00:07:51] nhân viên của tháng mà tôi đang Đạt đang
[00:07:53] cố phấn đấu để đạt nhân viên của quý năm
[00:07:57] ngoái tôi được đạt nhân viên của năm mà
[00:07:59] đấy ng â chỉm mình làm được việc và cũng
[00:08:03] gọi là được mọi người kiểu dạng là tin
[00:08:07] tưởng vân vân thì tức là trình độ mình
[00:08:11] không đến nỗi đúng không Tôi không làm
[00:08:13] mấy cái việc kiểu lật vặt đâu nhá tôi
[00:08:16] toàn làm những cái khá là quan trọng
[00:08:18] nhưng mà đương nhiên thì để được như thế
[00:08:22] thì cái sự nhiệt huyết rồi Vân Vân các
[00:08:24] thứ mình phải đi đi kèm để đánh đổi bởi
[00:08:27] vì là lý thuyết kiểu dạng là gọi nhỉ tư
[00:08:31] duy lý thuyết của mình thì cũng chỉ ở
[00:08:32] mức gọi là tương đối Tôi cảm thấy thế
[00:08:34] Tôi cũng không phải con nhà người ta để
[00:08:36] mà kiểu mình kiểu rất xuất sắc rất là
[00:08:39] giỏi mình phải bù lại cái gì à cân C bù
[00:08:43] siêng năng à cần cù bù thông minh đúng
[00:08:46] không đấy
[00:08:47] Ờ nên là tôi nghĩ là tôi sẽ dạy cho các
[00:08:51] bạn ở mức là các bạn hiểu tự Duy lập
[00:08:54] trình có những cái sẽ tách ra hôm nay
[00:08:56] tôi sẽ tách code xử lý các các thứ thứ
[00:08:59] ra thì các bạn sẽ thấy là hôm trước là
[00:09:01] xử lý ở trong controller đúng không Tôi
[00:09:03] sẽ tách ra một chỗ khác nhưng nó không
[00:09:06] hẳn là một cái des Pon quá ngon quá kiểu
[00:09:10] gọi là gọi nhở Thực ra thì Hữa trước tôi
[00:09:13] có đi cái sự kiện người ta bảo là chẳng
[00:09:17] có một cái design button nào là chuẩn cả
[00:09:19] Chẳng có một kiểu bản chất là nó cũng
[00:09:22] mvc mà lên kiểu dạng là kiểu chẳng qua
[00:09:25] nó vứt ra một cái chỗ nào đó khác thôi
[00:09:28] chứ nếu
[00:09:29] mà Chứ không ai có thể Kền chê việc code
[00:09:34] của người này kiểu trông kiểu gọi không
[00:09:37] clean đúng không và code mình clean hơn
[00:09:40] chẳng chẳng ai thể kiểu so sánh chơi ba
[00:09:43] nhau kiểu thế cả mỗi người sẽ có một cái
[00:09:45] tông code riêng mà đúng
[00:09:47] không thì tôi sẽ chỉ cho mấy ông cái
[00:09:50] tông code của tôi như thế nào thì mấy
[00:09:53] ông có thể tham
[00:09:54] khảo và quan trọng nhất vẫn là tư duy
[00:09:57] mình khi mà mấy ông sửa cái đoạn code
[00:10:01] đấy mấy ông hiểu được là mình và nhớ
[00:10:04] được là mình cần phải sửa chỗ nào đấy
[00:10:07] điều quan trọng chứ Bây giờ giả sử code
[00:10:09] ông rất là xịn nhưng mà kiểu khi bảo ông
[00:10:11] mò lại để sửa ông không biết chỗ nào để
[00:10:15] sửa thì cái design buton của ông chả có
[00:10:17] cái ý nghĩa gì cả đúng chứ
[00:10:19] Đấy toàn bộ mấy cái kiểu dạng Xây dựng
[00:10:23] hệ thống code cho nó kiểu chuyên nghiệp
[00:10:25] hơn mà chính mình còn chẳng hiểu được
[00:10:27] cái chuyên nghiệp đấy chính mình còn khó
[00:10:28] sực ử cái đấy thì tự ông làm khó ông
[00:10:31] thôi đúng không đấy nên là tôi nghĩ
[00:10:34] là là không cần phải suy nghĩ quá phức
[00:10:38] tạp về cái vụ thiết kế các thứ code sao
[00:10:41] cho mình tiện nhất mình hiểu nhất về nó
[00:10:44] Và thậm chí Và thậm chí đó là đồng
[00:10:47] nghiệp của ông phải hiểu với nó nếu mà
[00:10:49] ông cốt xịn quá ông cốt ngầu quá đúng
[00:10:52] không đồng nghiệp ông không hiểu một cái
[00:10:54] gì cả khi đọc đoạn code của ông đấy thì
[00:10:57] cũng dở mấy ông hiểu bài toán đây không
[00:11:00] Đôi khi bị thế đấy nhá Ờ hồi trước larel
[00:11:03] từng có bị cho cái vụ đấy Đó là có nhiều
[00:11:08] hàm bu in heer quá Xong rồi thành ra là
[00:11:11] cái người mà mới học à Mới học pp rồi
[00:11:14] chuyển quá lel ấy người ta không được
[00:11:17] thực hành nhiều lại về về kiểu
[00:11:21] à Thứ nhất là SQL Này ông sẽ thấy là làm
[00:11:24] lael thì không kiểu động và SQL mấy nữa
[00:11:28] kiểu gần như là gọi các hàm của nó thôi
[00:11:30] đúng không Đấy thứ hai là
[00:11:33] à Thứ hai là kiểu nó có nhiều hàm ẩn
[00:11:37] heer quá các thứ thứ mình không dùng
[00:11:40] kiểu dạng thuần nữa heer nó hỗ trợ tận
[00:11:44] răng rồi chẳng hạn thế đấy thì thì người
[00:11:48] mới người ta sẽ kiểu sẽ bị choáng bởi có
[00:11:51] rất nhiều hàm họ lại phải đọc lại xem
[00:11:54] hàm này Thực ra nó là cái gì người mới
[00:11:56] học pp đã bị choáng bởi hàm của P pp rồi
[00:11:59] chưa học xong hàm pp giờ còn phải học
[00:12:01] happer của lel nữa đấy Kiểu thế
[00:12:05] Ờ mà ông hiểu gì tôi không ạ Ờ ông nào
[00:12:09] kiểu dạng làm lel một thời gian Chắc là
[00:12:12] ông sẽ hiểu bởi Hồi trước tôi đi dạy tôi
[00:12:15] bị cấm Nếu mà tôi dạy larel ấ thì tôi bị
[00:12:18] cấm dùng mấy cái heer lẫn cả dùng que
[00:12:21] builder lẫn cả El mà tôi bắt buộc phải
[00:12:24] ra hết để cho sinh viên kiểu
[00:12:27] còn gọi là hiểu và gọi là ôn lại kiến
[00:12:33] thức về SQL
[00:12:44] vụ có bạn hỏi về cái vụ này chia sẻ về
[00:12:48] design button được không
[00:12:50] à Có học môn này trên trường mà Mung
[00:12:53] lung quá thì tôi vừa nói đấy Đó là chắc
[00:12:56] là tôi sẽ không chia sẻ được bạn đấy vì
[00:12:59] bản thân thì tôi cũng không dành tôi
[00:13:01] cũng chỉ biết mỗi lý thuyết
[00:13:03] và và đúng là học trên trường để biết lý
[00:13:07] thuyết thôi và để mà em thực hành nhiều
[00:13:09] hơn thì chắc là như bạn kia vừa nói chắc
[00:13:12] là làm Java nhiều em ạ là g va nhiều thì
[00:13:16] em sẽ nắm rõ
[00:13:19] hơn
[00:13:21] ờ đúng là Java ông sẽ học chặt chẽ hơn
[00:13:26] về cả op các thứ thứ nữa
[00:13:30] Ờ anh có nghĩ về việc tăng số bổ live
[00:13:34] trong một tuần không tôi không hẳn
[00:13:37] là định định dạy cho các ông kiểu thực
[00:13:43] ra buổi này vừa like code vừa để tâm sự
[00:13:46] mỏng qua một ít gọi là như nào nhỉ cũng
[00:13:52] gọi
[00:13:53] là trong những cái khoảng thời gian này
[00:13:56] thôi Tôi không chắc là thứ nhất là chắc
[00:13:59] chắn là tôi sẽ không livestream nhiều
[00:14:01] hơn thứ hai là về sau kiểu ví dụ ở Sang
[00:14:03] năm thì lúc mà
[00:14:05] tôi kiểu chuẩn bị đi dạy học lại bên FBT
[00:14:09] chắc là tôi cũng sẽ khó mà livestream
[00:14:11] lại được nữa ờ À livestream tiếp được
[00:14:14] nữa Bởi vì tôi vẫn làm full time ở trên
[00:14:17] công ty thì khi đi dậy sẽ dậy và những
[00:14:20] cái giờ như này này thì chắc là sẽ khó
[00:14:22] mà kiểu Ờ kh mà tiếp tục có thể kiểu
[00:14:27] livestream được
[00:14:35] đâu tôi lại cảm thấy kiểu khi đi dạy
[00:14:37] xong tôi lại cảm thấy hao hứng hơn thì
[00:14:38] tôi có thể like code vào cuối tuần thì
[00:14:41] kiểu chủ nhật chẳng hạn mấy ông hoàn
[00:14:43] toàn có thể xem lại không cần phải tương
[00:14:44] tác livestream cũng được đúng
[00:14:53] Ờ Thực ra là fan bây giờ thì mấy ông nên
[00:14:57] nếu thật sự mấy ông ông chỉ làm fen mấy
[00:15:00] ông biết
[00:15:01] ra biết ra Script theo kiểu FB này CS
[00:15:05] thì biết cắt gép và một tí design này
[00:15:08] đấy thế lương của fen ở công ty tôi cũng
[00:15:13] cao ấy nhá bằng luôn cả anh em làm làm
[00:15:16] kiểu backen bình thường luôn trừ mấy anh
[00:15:19] mấy anh em kiểu leader senio thì đươ
[00:15:21] nhiên cao hơn hẳn rồi
[00:15:23] Ờ anh like code à live Project nữ À đây
[00:15:30] cũng không hẳn là tính là một Project
[00:15:32] đâu Đây là dự án kiểu đây nó nó làm một
[00:15:37] cái dự án thực tế hơn làm một cái pet
[00:15:39] Project một cái kiểu dự án cá nhân gì gì
[00:15:41] đó không
[00:15:44] phải Ok Ờ Bây giờ trả lời qua vài cái
[00:15:48] tôi định tâm sự với bạn một các bạn một
[00:15:52] tí hoặc cuối buổi tâm sự tôi không biết
[00:15:56] à tôi lưu cái link này lâu lắm thôi Tôi
[00:15:59] mới xem lại
[00:16:01] Ờ tôi cho mấy ông xem cái này hay phết
[00:16:06] kìu bạn này là bạn đồng nghiệp ở cùng
[00:16:09] công ty tôi hôm đấy bạn đấy Kiểu
[00:16:15] kiểu đang làm cái phần xong rồi kéo code
[00:16:18] kéo code về thấy là tôi mới chỉnh sửa
[00:16:21] các thứ tôi làm vụ tối ưu là nhiều mà
[00:16:24] đấy thì tôi mới bảo kiểu tôi cũng kiêm
[00:16:26] nhiều cái quan trọng phết tối ưu ở trang
[00:16:28] thành T án mấy không ạ Lúc đầu nó tận 3
[00:16:30] giây Chẳng hiể sao mấy ông thì tưởng
[00:16:33] tượng vào trang thanh toán ông load 3
[00:16:35] giây mới ra được cái
[00:16:37] Trang thì trải nghiệm nó khá là tệ và CR
[00:16:40] tức cả conversion rate tức cả tỉ lệ
[00:16:43] chuyền đổi Nghĩa là nghĩa là hiểu là n
[00:16:48] ná kiểu rằng là tỉ lệ giữa việc
[00:16:51] ông vào và ông thanh toán là bao nhiêu
[00:16:54] phần trăm ấy thì hồi đấy CR của công ty
[00:16:57] tôi bị giảm bởi vì chắc là có liên quan
[00:17:00] đến cả việc và Trang Thanh toán nó bị
[00:17:01] lag gì gì đó nên là tôi ngồi tối ưu lại
[00:17:04] tôi tối ưu lại nhanh phết đấy nhá Tối ưu
[00:17:08] lại hơn lúc đầu là hơn b 3 4 giây t tù
[00:17:12] yêu là hơn 1 giây hơn 1 giây thôi đấy
[00:17:15] ngồi chỉnh sửa bao nhiều thừ thử đấy thì
[00:17:20] thì em này mới vào xem xong rồi bà Em ấy
[00:17:24] cũng làm cái làm lại làm thêm cái tính
[00:17:27] năng gì gì đó xong rồi thấy là tôi cũng
[00:17:30] sửa cái đoạn ngay trên trước đó về cái
[00:17:33] logic lấy lấy dữ liệu ra rồi thì thì
[00:17:38] cách tôi lấy thì sẽ là kiểu cách lại rồi
[00:17:41] các thứ thứ cũng là cái hôm nay có thể
[00:17:43] tôi sẽ
[00:17:45] dạy thì em đấy tham khảo và muốn kiểu
[00:17:48] chỉnh sửa lại code logic của em đấy theo
[00:17:52] cách của tôi Nghĩa Thực ra thực tế là em
[00:17:55] ấy hoàn toàn không thể nhắn không cần
[00:17:56] nhắn tin này code bây giờ code và code
[00:17:59] của chúng ta đúng không Thì cứ lấy về mà
[00:18:02] dùng thôi nhưng mà nhưng mà em ấy nhắn
[00:18:04] kiểu này hay kiểu Tôi cảm thấy kiểu kiểu
[00:18:08] chắc là không biết mình có tính là kiểu
[00:18:10] thích nịnh hay không nhưng mà nói chung
[00:18:11] là kiểu Đây cũng là tin nhắn đầu tiên
[00:18:13] luôn kiểu khá là khá là kiểu dạng là
[00:18:18] biết kỹ năng chắc là kỹ năng mềm Tôi cảm
[00:18:21] thấy là tốt đấy nên là tôi cũng kiểu
[00:18:25] dạng là cảm thấy muốn hỗ trợ em đấy n
[00:18:28] nên là tôi bảo là tôi sẽ xem lại à em
[00:18:31] đấy cứ đẩy đoạn code lên để đi để để tôi
[00:18:35] sẽ hỗ trợ và tôi sửa lại đoạn code của
[00:18:38] em đấy luôn cho
[00:18:46] n 700.000 để tiếp cận để
[00:18:50] ba không nhu cầu lắm
[00:18:53] Ờ cái video này là gì tôi không biết đâu
[00:18:57] tôi sợ bấm vào bây giờ nhảy ra cái gì
[00:18:58] không chắc là không có gì đâu nhưng mà
[00:19:01] tôi chắc là để sau hôm nay tôi thực ra
[00:19:04] hôm nay m tâm sự một tí về cái này tôi
[00:19:09] định tâm sự Cái này ở cuối buổi cơ nhưng
[00:19:11] mà tôi thường mấy ngày hôm nay mấy ông
[00:19:13] thấy mấy video trước dạy khá là sâu kiểu
[00:19:15] khá là cuốn kiểu gì mà toàn hai tiếng
[00:19:18] nên tôi không Lúc ấy hết sử hơi để mà
[00:19:20] tâm sự một cái gì đó thôi nên tôi xin
[00:19:22] phép tâm sự sớm bây
[00:19:28] Ừ Thực ra
[00:19:30] là tôi mới nốt lại cái này là để mà hôm
[00:19:36] nay bởi vì hôm nay là tôi nhắn tin cho
[00:19:40] khá nhiều anh em kiểu Chính xác là chủ
[00:19:44] yếu là các em sinh viên Hồi trước để mà
[00:19:46] rủ kiểu có dịp mai làm một cái dịp sự
[00:19:50] kiện thôi chắc là tôi lại quảng bá cái
[00:19:53] sự kiện này cho dù tôi cảm cảm thấy
[00:19:55] chẳng ăn được cái gì từ đy
[00:19:57] ờ cái sự kiện mấy ông đây thỉnh thoảng
[00:20:01] tôi cứ phải nhắc lại mấy ông có một cái
[00:20:04] Channel
[00:20:05] là là lên kèo thì mai tôi đi cái sự kiện
[00:20:10] này này ở Hà Nội thì tôi
[00:20:20] đó rủ anh em đi kiểu dạng là đi sự kiện
[00:20:23] cùng nhau xong rồi ăn uống các
[00:20:26] thứ thì hôm nay có có vẻ là tôi nhắn
[00:20:30] nhiều Face và lượng người phản hồi lại
[00:20:35] Ờ nó kiểu đấy conion rate đúng không khá
[00:20:39] là thấp rất là thấp không được như kỳ
[00:20:42] vọng đấy
[00:20:49] dần dần dần khó mà kiểu giữ thân được
[00:20:52] với nhau mình có công việc riêng cuộc
[00:20:54] sống riêng nên là kiểu Ừm sẽ có lúc mà
[00:21:00] mình rủ nhau mà kiểu bởi vì hôm nay tôi
[00:21:03] cầm là tôi chia sẻ ông hai mấy ông Hai
[00:21:07] bài học xức máu đó thứ nhất là đôi khi
[00:21:09] mấy ông rủ như thế m ông đừng có tạo
[00:21:11] nhóm tôi tạo nhóm rồi tôi nhắn luôn vào
[00:21:14] trong đấy Kiểu để nhóm chat đấy Kiểu hơn
[00:21:17] tầm mười mấy người để tôi muốn là kiểu
[00:21:20] thông bào chung ấy thành ra nhược điểm
[00:21:21] mà kiểu một ông mà kiểu muốn rút là tự
[00:21:24] nhiên kiểu nó bị Hữu ứng là kiểu nhiều
[00:21:26] người muốn rút đấy thứ
[00:21:28] hai đó
[00:21:30] là ông tạo nhóm chat như thế xong rồi
[00:21:33] tôi bấm cái nút kiểu tạo cái bình chọn
[00:21:36] ấy ở trên nhóm chat trên Messenger ấy
[00:21:38] tôi không hề biết được cái bình chọn đấy
[00:21:41] có người khác có thể thêm cái lựa chọn
[00:21:45] của họ vào và cái bình mang tiếng là
[00:21:48] bình chọn nhưng mà có thể chọn được
[00:21:50] nhiều ạ Đấy x tự nhên đầu tiên tôi tạo
[00:21:54] hai lựa chọn là đi sự kiện và đi ăn
[00:21:59] Đấy thế mà tự nhiên có một ông thêm vào
[00:22:01] là không đi đấy rồi cùng thì mọi kiểu
[00:22:05] hơn 10 người tích và không
[00:22:08] đi đy tốt nhất là
[00:22:11] không không nên tạo cái mình chọn ở trên
[00:22:16] trên Facebook nếu mà ông muốn rủ như thế
[00:22:19] tôi lúc sau Tôi ân hận quá Lỡ rồi nên
[00:22:22] sau sú kinh nghiệm Tôi sẽ tạo một cái
[00:22:24] event ở trên Facebook Xong rồi để chế độ
[00:22:28] riêng tư xong rồi chỉ xong rồi ẩn đi
[00:22:32] người khác có thể xem được danh sách mới
[00:22:34] đấy Xong rồi ấn mời bạn bè đấy các thứ
[00:22:39] rồi đăng trong đấy đăng trong đấy tôi
[00:22:41] cảm thấy nó sẽ có tiện hơn là kiểu nó sẽ
[00:22:43] không bị Spam tin
[00:22:45] nhắn rất phù hợp việc là ai chụp cái gì
[00:22:48] ai đăng cái gì đó thì đăng lại vào trong
[00:22:51] cái sự kiện đấy thậm chí ngày này năm
[00:22:53] xưa nó C nhắc mình là mình từng đi sự
[00:22:55] kiện này hình như thế không biết Nói
[00:22:58] chung là tôi cảm thấy là tạo sự kiện ở
[00:23:00] trên đấy thì cái việc là người khác tích
[00:23:03] vào có đi hoặc là từ chối Hình như là
[00:23:06] chỉ mình mình thấy không biết được tí
[00:23:08] rồi phải test lại
[00:23:16] là tự nhiên kiểu một người tạo cái kiểu
[00:23:20] không đi thi một loạt ông tích tích tích
[00:23:22] vào không đi
[00:23:24] kiểu từng cái tích vào không đi đấy Kiểu
[00:23:28] lòng mình đau thêm ấ thà thà không ai
[00:23:32] tích vào cái gì Kiểu như thế còn đỡ hơn
[00:23:35] việc kiểu tất cả mọi người đã xem người
[00:23:38] quán nửa tích và không đi đúng không
[00:23:41] Đấy và lẫng cả là theo tôi thì thực sự
[00:23:47] thì tính tôi là tôi muốn là người Kiểu
[00:23:51] kiểu dạng là mình cầu nối để kết nối
[00:23:54] giữa mọi người với nhau như thế nhưng có
[00:23:56] vẻ là việc giữ đấy và truyền lửa đấy nó
[00:24:00] khá là khó là nên là tôi cũng nghĩ dần
[00:24:04] là
[00:24:05] việc cái việc đấy có thể không phù hợp
[00:24:07] với mình lắm
[00:24:15] càng Thế mình sẽ ít Hòa hùa hay hòa theo
[00:24:18] đám đông mình không thực sự là thích đi
[00:24:21] cùng tập thể Đông nữa mà mình sẽ chỉ có
[00:24:24] một một kiểu một vài bạn thân kiểu một
[00:24:28] nhóm bạn thân kiểu vài người thôi mấy
[00:24:31] ông nghĩ thế không Tôi không biết mấy
[00:24:33] ông có có bạn thân hay không nhưng mà về
[00:24:36] tôi thì tôi
[00:24:39] cũng tôi Thực sự tôi không biết khái
[00:24:41] niệm bạn thân của tôi kiểu bây giờ là
[00:24:44] như nào nữa vì hồi trước thì từng nghĩ
[00:24:46] là có có bạn thân đấy nhưng mà nhưng mà
[00:24:51] Đúng là lâu anh em không còn nói chuyện
[00:24:53] hay tương tác với nhau nên là cũng
[00:24:56] à cũng không biết là còn thân nữa không
[00:24:58] thì vì chuẩn là thân thì mình phải hiể
[00:25:01] cũng tương đối hiểu nhau đúng
[00:25:08] cọn mình còn là con trai thì chắc là
[00:25:12] kiểu mình
[00:25:14] sẽ mình sẽ không kiểu thổ lộ ra cái suy
[00:25:19] nghĩ hay mọi thứ tâm sự
[00:25:21] nhiều cho dù là cho dù là con trai hay
[00:25:25] con gái thì vẫn
[00:25:26] cần vẫn cần tâm sự vẫn cần kiểu có cảm
[00:25:30] xúc mà đúng không Chúng ta không vô cảm
[00:25:32] đấy Nên là thế nên là tôi mới Tôi cảm
[00:25:36] tôi tôi nghĩ thế nên thành ra tôi mới
[00:25:39] thường haay nói về mấy ông ấy ngay Ngay
[00:25:41] cả ngay cả cái tôi hay nhắn mấy ông ấy
[00:25:44] đó là tôi thường ấy không chỉ nói là mấy
[00:25:47] ông có câu hỏi gì thì nhắn tôi tôi
[00:25:49] thường hay nói thêm là mấy ông có tâm sự
[00:25:51] gì chia sẻ gì không biết không biết chia
[00:25:55] sẻ với ai thì có thể chia sẻ với tôi tôi
[00:25:57] Thực ra tôi không phải là con người
[00:25:59] à Tôi không phải con người đồng cảm giỏi
[00:26:03] Tôi cũng không phải con người đưa lời
[00:26:04] khuyên tốt nhưng mà tôi nghĩ là là Ừ thì
[00:26:08] đôi khi mấy ông
[00:26:09] sẽ sẽ cảm thấy thoải mái và dễ chịu hơn
[00:26:13] khi mà Ít ra có người lắng nghe mình
[00:26:16] đúng không ạ Ít nhất là có người có một
[00:26:18] người nà Đó lắng nghe mình có thể người
[00:26:19] đấy người lạ có đôi khi người lạ cũng
[00:26:21] hay thật đôi khi ông tâm sự với người lạ
[00:26:24] có khi hay mấy ông cốt để chút ra thôi
[00:26:27] chứ thực ra là cũng không cần hẳn lời
[00:26:29] khuyên hay là một cái gì đó đúng không
[00:26:33] Mình thì đương nhiên vấn đề của mình thì
[00:26:36] chắc là chỉ mình mới thực sự hiểu và
[00:26:38] giải quyết được người ngoài chắc là
[00:26:42] là kiểu nó n nà giống như là nhở giống
[00:26:46] như là ông ông em tôi bây giờ đang bình
[00:26:48] luận một điện hình
[00:26:50] ờ hai anh em thì thỉnh thoảng kiểu có gì
[00:26:54] khó chịu thì nói với nhau xong rồi Ờ
[00:26:59] à Xong rồi kiểu chia sẻ mem với nhau
[00:27:03] chính thế đủ vui rồi Kiểu cảm thấy cũng
[00:27:06] được giải tỏa phần nào nghĩa là ít nhất
[00:27:07] là ông có một người gì đ nghĩa đôi khi
[00:27:09] không phải chia sẻ nỗi buồn Ông chia sẻ
[00:27:11] niềm vui ông có một người để chia sẻ ông
[00:27:13] vui rồi đúng không
[00:27:14] đấy Anh có muốn show cam không á
[00:27:18] Ờ hồi trước tôi đã từng nói về vụ này đó
[00:27:21] là thực ra khi mà tôi dạy thì tôi sẽ
[00:27:23] không muốn kiểu mấy ông tập trung vào
[00:27:25] cái mặt tôi tập trung vào tôi đang làm
[00:27:27] gì Ừ nhưng mà chắc là chắc thực sự là có
[00:27:31] khi tôi sẽ khi mà tâm sự kiểu này tôi sẽ
[00:27:35] chia sẻ màn hình để buổi sau tôi à nhầm
[00:27:37] không phải chia sẻ màn hình chia sẻ
[00:27:39] camera để buổi sau tôi sẽ cân nhắc tôi
[00:27:41] sẽ chỉnh nhá Nhưng mà tôi sợ là mọi
[00:27:45] người để ý kiểu đôi khi là có gì đó ở
[00:27:48] đằng sau tôi mọi người nhìn thấy nó lại
[00:27:50] không hay Chẳng hạn nghĩa là nhìn mình
[00:27:52] thì thì không sao tôi không ngại đâu
[00:27:55] Nhưng mà quan trọng là đằng sau mà kéo
[00:27:59] sự là có người đi ra đi vào hay là gì gì
[00:28:01] đó một cái cảnh gì đó Bất Ngờ Biết đâu
[00:28:04] đấy ông không biết ông từng nhìn thấy
[00:28:07] mấy cái chamer thỉnh thoảng có cái gì
[00:28:10] kiểu dạng có một
[00:28:12] cái tình huống nào đó bất ngờ xảy ra
[00:28:14] mình không xử lý được mình lại quả đấy
[00:28:16] lại buồn
[00:28:17] Ờ Chứ tôi tâm sự này tôi không khóc đâuu
[00:28:21] mấy ông không cần phải xem kiểu nghĩa là
[00:28:23] tôi đang khóc nên tôi phải mở cam lên n
[00:28:26] ủi à mà lỡ cả là tôi nghĩ là tôi sẽ có
[00:28:29] thể thích mở cam con này ít nhất là con
[00:28:31] này con Macbook nên là cam nó xịn hơn
[00:28:35] cái con cũ con cũ máy đeo cam cùi bắp
[00:28:40] lắm là để hôm nào
[00:28:43] nhá
[00:28:50] sẽ phải conect việc là chỉnh chỉnh lại
[00:28:52] được cái vụ là kiểu nó sẽ làm mờ được
[00:28:55] cái BC background à background dịch ra
[00:28:59] gì nhở Ừ cứ làm mở đằng sau thì tôi sẽ
[00:29:02] mở
[00:29:14] Bởi vì tính ra tôi ngại là ngại kiểu tự
[00:29:17] nhiên có gì đó bất ngừa xảy ra vì tính
[00:29:18] ra tôi đang livestream ở phòng khách chứ
[00:29:21] không phải là livestream trong phòng
[00:29:23] riêng đóng kến cửa Nếu mà có phòng riêng
[00:29:26] đóng kến cửa thì tôi kiểu làm gì chẳng
[00:29:28] được đúng không Còn Đây là kiểu nó cũng
[00:29:33] đang hơi Tôi cảm thấy nó đang
[00:29:35] hơi lội Thiên có sẽ có rất nhiều tình
[00:29:38] huống bất ngờ xảy ra Ví dụ đồn ngồi
[00:29:40] Khách Đến Chơi chẳng hạn
[00:29:49] câu hỏi về cá nhân thì các bạn cứ ngồi
[00:29:51] stu Tôi ở st không biết phát đâ từ đấy
[00:29:55] đúng hay không
[00:29:56] ờ
[00:30:03] thẳng stock stock stock xh
[00:30:09] chập
[00:30:15] tra tôi ở trên à Facebook ấy nó ra hết
[00:30:18] mà tôi không Tuy là tôi không công khai
[00:30:21] nhưng là nó lộ lắm thích cái để tôi chỉ
[00:30:24] mẹo cho mấy ông biết được Sinh nhật ai
[00:30:26] đó mấy ông lên
[00:30:28] kể cả cho dù là người đấy
[00:30:31] không không đă gần đây thì quá khứ họ
[00:30:35] kiểu gì đã từng được chúc mừng sinh nhật
[00:30:37] trên trang C nhân hoặc là từng đăng rồi
[00:30:39] trừ khi người thấy ẩn hết toàn bộ cái
[00:30:42] bài đăng
[00:30:43] thôi ông cứ lên Hẳng cái trang cá nhân
[00:30:48] của họ tìm kiếm chữ sinh nhật sinh nhật
[00:30:50] này thậm chí là snvv này đấy xin nhật
[00:30:53] vôi vẻ đấy dẽ ra được Ngà sinh của họ dễ
[00:30:57] mà ô chư tôi theo dõi các bạn nữ thế
[00:31:00] suốt
[00:31:09] chưa ạ Ờ tôi có dạy trong playlist của
[00:31:12] tôi Có cái có cái đấy đấy ông thể nghe
[00:31:16] qua để xem cũng tôi dạy cũng chỉ mức cơ
[00:31:20] bản thôi nó cũng không phải là kiểu nó
[00:31:23] chưa đủ thực tế cho lắm Vậy tôi dạy Hồi
[00:31:26] đấy để cho mấy ông biệ để nhảy sang
[00:31:28] faceb dạy faceb ch dễ
[00:31:30] chứ còn à để mà ông học sâu về cái đấy
[00:31:36] thì tôi nghĩ là thế Ra là cũng chả nơi
[00:31:40] nào học sâu cái đấy cả học m VC giờ cũng
[00:31:42] chỉ để để làm fmw hết theo tôi là
[00:31:47] thế Ok bây giờ bắt đầu nhảy sang code
[00:31:50] nhá tâm sự xong mọi thứ hết rồi
[00:31:52] à trừ cái trừ cái này để buổi sau
[00:32:05] đúng không
[00:32:06] ạ Mình cũng đã làm shit cùng mình cũng
[00:32:09] đã biết qua về sher
[00:32:12] Factory
[00:32:18] về code hôm trước bởi vì là bởi vì
[00:32:30] hỏi à Hôm qua tôi hỏi được Sếp tôi về
[00:32:33] cái lý do trang này chạy chậm
[00:32:36] rồi xế tôi Ờ ông thấy Trang này lúc đầu
[00:32:41] vào chạy chậm lúc sau load rất là nhanh
[00:32:43] đúng không ạ xem tôi tôi hỏi sếp thì sếp
[00:32:48] bảo là có thể là do C đang bị chiếm bởi
[00:32:53] chính cái chính cái mình đang livestream
[00:32:57] cái
[00:32:57] obs nó làm khá là nặng kiểu chiếm
[00:33:07] luôn chứ bình thường vào này load nhanh
[00:33:09] đúng không Thỉnh thoảng nó sẽ kiểu bị đơ
[00:33:13] Anh ấy nói giả thiết như thế Tôi thấy
[00:33:15] cũng có cái hợp lý của
[00:33:23] router not DEF
[00:33:25] này trước mình xóa cái gì à
[00:33:38] sửa cái À đúng rồi tôi dạy mấy ông về
[00:33:44] ờ git đã vì tôi không Nhớ hôm trước là
[00:33:49] mấy hôm trước từ hôm trước giờ mình
[00:33:51] không thề đẩy code lên nên thành ra là
[00:33:53] kiểu nó đ khá bị dài rồi mình sẽ tôi sẽ
[00:33:56] chỉ ông cách tôi dùng kí
[00:34:08] nhiên là đương nhiên là vẫn là mô hình
[00:34:09] mvc rồi Nhưng ý tôi là bây giờ không làm
[00:34:11] mvc thuần mấy nữa mà tôi thấy là dùng fw
[00:34:15] nhiều fw t nhiên có MBC rồi
[00:34:17] Ờ tự nhiên có cái này cái gì nhỉ Không
[00:34:21] biết bỏ qua Ờ tôi
[00:34:25] sẽ đầu tiên thì tôi lại nhắc lại một lần
[00:34:29] nữa về cách tôi học git là
[00:34:32] tôi cái dự án tính ra là công ty khi mà
[00:34:36] về công ty này tôi mới thực sự là kiểu
[00:34:39] kiểu dùng git nhiều hơn là kiểu biết
[00:34:43] cách dùng hơn hồi trước thì hồi trước
[00:34:47] thì tôi kiểu dạng là có có động vào cũng
[00:34:51] dùng git ở công ty cũ Thì có dùng git
[00:34:53] Chắc chắn rồi nhưng mà dùng cái phần mềm
[00:34:56] kiểu click chuột để mà kiểu đẩy hết code
[00:34:59] lên cũng không cũng không biết fix
[00:35:01] Conflict hay mọi thứ là như nào nói
[00:35:03] chung hồi đấy khá là Lom zom đúng không
[00:35:06] thấy khá là non không tự tìm hiểu nhiều
[00:35:09] cái Còn khi về công ty này thì đúng là
[00:35:11] tự mình tự tìm hiểu khá nhiều thì biết
[00:35:13] qua về git hơn và càng càng gần đây càng
[00:35:16] biết rõ hơn một tí về
[00:35:18] git thì đầu tiên là git là để công cụ để
[00:35:23] mình kiểu kiểu quản lý code đúng không
[00:35:26] Thì việc là mình để code lên thì hiện
[00:35:29] tại thì bây giờ m ông đang thấy tôi chỉ
[00:35:32] có một Brand cng lắm là thêm Br này của
[00:35:34] ông em và thường cũng chỉ thường có thể
[00:35:38] đẩy hết vào trong PR này Nếu giả sử
[00:35:39] không làm dễ ăn cá nhân
[00:35:41] Ờ Còn nếu ông làm thích làm chuy nghiệp
[00:35:44] ông tách ra từng phần từng phần cũng
[00:35:45] được Nhưng mà thường là mình dự ả Mình
[00:35:48] đang làm thì kiểu làm đến đâu
[00:35:51] Kiểu một là chắc đến đấy hai là cũng chỉ
[00:35:56] mình mình làm nên là sửa thì nằm hết
[00:35:58] trong một cái prend cũng được mặc định
[00:36:02] brend sẽ là main hoặc là Master kiểu như
[00:36:04] này đúng không ạ thì mình sẽ đẩy code
[00:36:07] lên đây thôi Thì thì đơn giản rồi thường
[00:36:10] ông sẽ fake để sẽ kiểm tra xem là có
[00:36:13] code mới không có thì ông sẽ p kéo về
[00:36:17] đấy Xong rồi bây giờ thì chiến giản đẩy
[00:36:21] lên thôi còn cách đẩy thì thường là tôi
[00:36:23] sẽ kiểu như
[00:36:24] này thường những cái những cái crate này
[00:36:27] thì tôi
[00:36:28] sẽ Bởi vì bây giờ đang có khá nhiều file
[00:36:32] Giả sử Giả sử ông làm Liên quan nhiều
[00:36:35] file như này
[00:36:37] thường Tại sao có vile này
[00:36:40] à sẽ đẩy kiểu như này
[00:36:48] đẩy lên trước đã đúng không À Phả gì gì
[00:36:52] đó đây là
[00:36:54] app telescope chẳng h ạ Đấy tiếp ông em
[00:37:01] Bây giờ ngồi nhìn tôi làm gí ông em sẽ
[00:37:04] rất là cuu luôn Vì tôi
[00:37:13] tôi đa số nhiều người tôi biết thì dùng
[00:37:16] lệnh git chứ không kiểu dùng cái github
[00:37:19] desktop này nên là thử kiểu có sẽ có hai
[00:37:23] trườngng phái đúng không ạ những trường
[00:37:26] phải người ta dùng
[00:37:28] à Kiểu cái này gọi gì g à đấy để để mà
[00:37:34] kiểu dạng là thân thiện giao diện các th
[00:37:37] thứ thì sẽ lười kiểu ghi ghi đầy đủ câu
[00:37:41] lệnh thì thành ra là người theo trường
[00:37:44] phái đấy sẽ khó chịu khi mà mình kiểu
[00:37:46] đẩy lên kiểu bằng những cái kiểu mặc
[00:37:48] định kiểu như này
[00:37:50] đấy tôi theo trường phá kiểu gu Ai sinh
[00:37:53] ra có lý do cả nên tôi vẫn dùng nhưng mà
[00:37:56] thành ra nó sẽ bị nhiều lúc mà sẽ bị tệ
[00:37:58] là kiểu mình Quen dùng cái giao diện rồi
[00:38:01] Khi mà mình bảo mình à hiểu rõ về git
[00:38:05] này hay là kiểu bảo phải gõ câu lệnh ra
[00:38:08] vì g vì cái giao diện này nó sẽ không Hỗ
[00:38:11] trợ đầy đủ ấy thì lại chịu đấy đấy nhược
[00:38:14] điểm cái
[00:38:43] này
[00:38:54] trong những cái đôi khi chẳng chẳng sửa
[00:38:56] gì cả nhưng mà tôi lỡ Gõ cái À tôi lỡ ấn
[00:39:02] cái nút refactor tổng th ra nó kiểu bị
[00:39:07] thành ra như này để để đợi cho tí tôi
[00:39:10] vào hẳn cái trang này để sửa
[00:39:20] admin À
[00:39:38] nên thành ra nó bị kiểu đẩy đẩy đẩy như
[00:39:42] này thôi đà chấp nhận để để như thế vậy
[00:39:57] cứ đẩy hết code Hôm trước đã
[00:39:59] nhá Thiếu cái này
[00:40:17] sẽ
[00:40:18] refactor đúng
[00:40:35] config đây sẽ là bên
[00:40:40] homepage
[00:40:49] đó tiếp là tạo cái
[00:40:54] này tạo cái này
[00:40:58] này là cũng là
[00:41:00] add telescope
[00:41:17] test và đây sẽ
[00:41:20] là
[00:41:34] un
[00:41:42] không sử dụng không chưa biết
[00:41:45] được remove không đúng comment đi
[00:41:48] comment
[00:41:50] and play
[00:42:01] file Gì
[00:42:08] Gì show tun bar cái g gì đó
[00:42:13] này cái file này file gì
[00:42:25] xem
[00:42:58] Kệ Chả ảnh hưởng
[00:43:07] Thì ông nên tải về Bởi vì ông kiểu dạng
[00:43:10] như à Ông đỡ phải kiểu cần mạng để kết
[00:43:13] nối được
[00:43:15] còn còn khi mà ông đẩy lên mạng thì ông
[00:43:19] hình dung nhá ví dụ là ông đẩy lên
[00:43:22] server của ông server ông ở Việt Nam thì
[00:43:25] ông kết nối bằng mạng Việt Nam thì về cơ
[00:43:27] bản thì nó gần như là nó rất là nhanh
[00:43:29] thì thì ông nên để hết code mọi thứ ở
[00:43:33] một chỗ ở Nghĩa tại server của ông luôn
[00:43:36] còn nếu mà server của ông ở bên nước
[00:43:38] ngoài thì khi mà khi mà kiểu truy cập
[00:43:43] vào cái trang web của ông là đồng nghĩa
[00:43:45] là cũng phải tải hết toàn bộ các file
[00:43:46] kiểu js hoặc à JavaScript hoặc là CS từ
[00:43:51] nước ngoài về thì thì ví dụ Giả sử đặt ở
[00:43:55] bên m Mỹ chẳng hạn đấy thì nghĩa là Tải
[00:43:57] mấy cái file đấy hết từ Mỹ về thì ờ thì
[00:44:02] tôi thấy là nếu mà để cdn thì nó sẽ kiểu
[00:44:08] à Nếu mà để cdn thì cái cái CN tức là
[00:44:13] kiểu dạng là một cái file JavaScript hay
[00:44:15] là CS kia nó sẽ đặt ở một cái trụ sở
[00:44:18] khác thường hay trụ sở đấy nó sẽ có khắp
[00:44:21] nơi ở trên thế giới
[00:44:23] thì không hẳn là tại từng quốc gia đâu
[00:44:26] nhưng mà tại từng khu vực ấy tại mỗi khu
[00:44:29] vực gì đó nên là tính ra là lúc đấy dùng
[00:44:32] CN nó sẽ nhanh hơn rất là nhiều thế
[00:44:34] trong trường hợp mà đấy là lý thuyết Tôi
[00:44:36] nhớ mang má Thế nhá Tôi không chắc lắm
[00:44:39] nhé Thì thì lúc đấy Khi mà server ông
[00:44:42] đặt ở quốc gia khác và nói chung là
[00:44:45] người nước ngoài truy cập được ấy thì
[00:44:46] ông nên để
[00:45:05] mình không chắc
[00:45:07] th thc ra thực tế là tôi tôi bảo tôi đi
[00:45:10] làm thì tôi làm như nào đ Tôi chỉ biết
[00:45:13] chia sẻ lại mấy ông như thế chứ Tôi cũng
[00:45:16] không phải là một người quá giành về lý
[00:45:19] thuyết để mà thể kiểu để thể khẳng định
[00:45:22] một cái gì đó Có vài cái tôi khẳng định
[00:45:25] Mạnh mồm được ví dụ Giả sử về SQL tôi
[00:45:27] vẫn khẳng định Mạnh mồm được hôm nay tôi
[00:45:29] vừa khẳng định Mạnh mồm với sếp tôi xong
[00:45:30] sế tôi bảo em Có chắc không em chắc chắn
[00:45:34] anh luôn C thử thử thô Sếp tôi vẫn không
[00:45:37] tin ạ Buồn lắm nhưng cái đấy tôi chắc
[00:45:51] chắc ơ hôm trước mình xóa này rồi
[00:46:03] Bảo sao tự nh ôm đấy cứ cảm thấy thừa
[00:46:04] thừa mình xá sư đi ạ lỗi tôi lỗi
[00:46:14] thật xem
[00:46:17] đây có cách
[00:46:20] mà đ Xem lịch sử
[00:46:24] git
[00:46:38] nhanh
[00:46:56] dưới content chịu vãi chưởng
[00:47:03] thích thì tôi để giống hệt lại cũng được
[00:47:05] mình thường để router thì kiểu theo kiểu
[00:47:09] dạng slug như này khi mà mình để bên
[00:47:12] khách hàng
[00:47:25] bị phụ phụ thuộc kiểu cái thằng server
[00:47:28] kia đúng không Nếu mà giả sử mà có
[00:47:31] server kia có mệnh hệ gì coi như là mình
[00:47:33] cũng đi theo Nhưng mà thường thì tùy đấy
[00:47:37] mà lẫn cả là mà lẫn cả
[00:47:40] là Ờ nếu mà để như thế Hồi trước đã từng
[00:47:44] có vụ là kiểu cdn của một cái thư viện
[00:47:48] gì đó bị hack ấy là toàn bộ tất cả những
[00:47:50] cái bên nào mà dùng cái thư viện đấy
[00:47:53] cũng đều đều có thể bị hack đấy n là nó
[00:47:57] cũng nó cũng là một bài toán gì gì
[00:48:01] đó router tưởng số nhiều á Thực ra là nó
[00:48:05] quy ước tùy
[00:48:06] thôi Đúng có thể để số nhiều nhưng mà
[00:48:10] tôi đang kiểu lười Tôi đặt cho nó kiểu
[00:48:12] trùng trùng như này về sao dễ tìm mà Chứ
[00:48:15] best practice thì thực ra tôi không nhớ
[00:48:18] là best practice là gì cơ hôm trước tôi
[00:48:21] khoe với sếp tôi là lal best này này
[00:48:26] xong rồi Sếp tôi bảo là ồi Anh chỉ tin
[00:48:29] mỗi ông tác giả của larel viết ra thôi
[00:48:33] Chứ cái này toàn mấy ông toàn tự sướng
[00:48:35] với nhau kiểu nó cũng chỉ một cái Ước gì
[00:48:37] đó chứ larel có khuyên thế đâu nó chịu
[00:48:41] đy cái đoạn này này dụ Router đúng
[00:48:44] không Đấy router để số nhiều này
[00:48:49] đấy còn router name thì sẽ là snack cy
[00:48:53] với kiểu Dấu chấm này Phân biệt này đấy
[00:48:56] đúng không ạ
[00:49:08] gọi là về sau mình nói chung à nó là như
[00:49:12] nào nó vẫn quay đi quay lại việc là code
[00:49:14] sao cho về sau mình dễ mình nhớ được là
[00:49:17] Ừ hồi đấy mình đặt là như nào và mình
[00:49:19] sửa được đúng không ạ Còn thực sự là ông
[00:49:22] đặt tên thích thì ông đặt tên miến a BC
[00:49:24] cũng được sao về cho ông dễ sửa ông ông
[00:49:27] hình dung ông nhớ được cái A đấy hay cái
[00:49:29] gì Cái B Cái đấy hay cái gì còn việc ông
[00:49:31] quy ước như thế nào đấy việc của ông và
[00:49:34] người làm cùng ông cũng hiểu được cái
[00:49:36] đấy ngườ ta vẫn sửa được cái đấy kh ông
[00:49:38] thích đặt đặt cái gì cũng được giống như
[00:49:41] sếp tôi ấ Bây giờ nhiều người quy là
[00:49:43] kiểu comment là phải nên tiếng anh một
[00:49:45] tí r kiểu nó nó rõ nghĩa hơn vân vân vân
[00:49:48] xế tôi để luôn comment tiếng Việt có dấu
[00:49:51] ở trong đấy sa bảo đồng nghiệp Toàn
[00:49:53] người Việt với nhau Tại sao phải để thế
[00:49:56] nhưng hồi tr như hôm trước thì bị cái
[00:49:58] lỗi cũng ngoài ă thật hôm ấy Bọn tôi
[00:50:01] phải reverse code xong m ấn vào bên
[00:50:03] thằng Pit Pit ấn Open Raw file của nó ra
[00:50:07] thì thì toàn bộ cái comment tiếng Việt
[00:50:10] của anh đấy Bị kiểu Nó gần như là kiểu
[00:50:13] chữ kiểu ch mấy không biết kiểu bị lỗi
[00:50:16] ph chữ các thứ thử
[00:50:19] không Nghĩa là chữ có dấu nó sẽ bị thành
[00:50:22] sai hẳn ấy á á á thì nó kiểu ớ các thứ
[00:50:27] thứ đủ loạn loạn hết cả lên đấy nên là
[00:50:30] tôi không hẳn là khuyên mấy ông comment
[00:50:32] bằng tiếng Việc có dấu tiếng Việt không
[00:50:34] dấu cũng được Còn không thì tiếng Anh
[00:50:36] thì cũng được Nhưng mà tiếng Anh thì
[00:50:38] cũng nên hạn chế đừng thể hiện i chín
[00:50:41] chấm ở đấy không ai đọc không ai hiểu
[00:50:43] đâu Nói chung là dùng Hãy dùng những
[00:50:45] tiếng Anh cơ bản mà ai cũng thể viết
[00:50:47] được Nói chung là mấy ông mà lạm dụng
[00:50:49] dùng kiểu chbt để viết comment cho ngầu
[00:50:52] ấy thì xong rồi về sau không phải ông
[00:50:55] tựng nghĩ ra ấy Tức là chỉ là mấy cái từ
[00:50:57] đấy có thể thậm chí chính ông C không
[00:50:59] biết ấy thì người khác cũng có thể không
[00:51:01] biết đâu Thì cái comment đấy nó lại
[00:51:04] thành khiến nhau mệt hêm đúng không
[00:51:08] à Nãy giờ cứ mải nói gì cũng chưa làm
[00:51:11] được cái gì cả đợi tí đợi tí bây giờ
[00:51:13] mình sẽ quay lại bên hom page để sửa lại
[00:51:16] nhá
[00:51:17] Ờ thì hôm trước là sửa hôm trước sửa cái
[00:51:27] bên này này một cái này hai cái này đúng
[00:51:30] không ạ đại loại này mề mề cái kiểu như
[00:51:33] này
[00:51:42] mấy ông cái kiểu dạng là
[00:51:50] lý hơn
[00:51:56] mình sẽ có
[00:51:58] cái mình ông Để ý kỹ là là hôm trước thì
[00:52:02] làm một cái là save này à store này tức
[00:52:06] là thêm mới này một cái là update
[00:52:10] này đấy
[00:52:12] à Cả hai đều là để kiểu nói chung gộp
[00:52:16] chung là cập nhật thông tin ở trong DB
[00:52:18] đúng không ạ để mà bên cái giao diện f
[00:52:22] này mình sẽ hiển thị ra đúng chưa Nhưng
[00:52:24] mà thường là admin khi mà cập nhật mấy
[00:52:28] cái này cái này đang còn gọi là config
[00:52:31] mà tức là nó sẽ ít thay đổi đúng không ạ
[00:52:34] Nó sẽ rất ít hãy đổi thường là để cái
[00:52:36] này vài tháng thậm chí là để lâu hơn thì
[00:52:39] rõ ràng là cái này cứ mỗi lần Tải hại
[00:52:41] trang lại truy vấn lại như này truy vấn
[00:52:42] rất nhiều và trong confix các thứ thứ
[00:52:44] như này th ra không ổn là ông em làm
[00:52:46] kiểu này nó không ổn lắm này Đấy th giờ
[00:52:51] thì nên làm như thế nào thì mình sẽ bây
[00:52:55] giờ mình sẽ dùng cách mình sẽ kích lại
[00:52:57] kch lại dữ liệu đây đầu tiên tôi sẽ cho
[00:53:01] mấy ông
[00:53:02] xem đầu tiên mình làm cách trữ lại nhá
[00:53:05] nằm ở trong homepage controller này
[00:53:07] client
[00:53:17] content Thực ra bây giờ không còn inmate
[00:53:21] nữa thì
[00:53:22] phải đúng không nhỉ
[00:53:27] ơ vẫn còn New rival inmate á Đợi tôi một
[00:53:30] tí hình như vừa tôi thêm lại cái đoạn
[00:53:32] đấy nó cũng sai tại sao mình cần newel
[00:53:35] inmate nhỉ Chỉ cần content th
[00:53:38] nhỉ Mình có load cái thằng new inmate
[00:53:41] đâu đây content đy nhá tôi Xóa các phần
[00:53:43] đăng ảnh rồi mà
[00:53:54] nhỉ à Thôi tôi nhớ lý do rồi đăng ảnh
[00:53:58] cái
[00:54:03] được
[00:54:15] thế lô mà chạy
[00:54:24] không
[00:54:29] rồi
[00:54:45] mất rồi À
[00:54:55] đó đổi lại thành cái
[00:55:03] th chỗ này lại giữ nguyên này Chỗ này
[00:55:06] giữ nguyên
[00:55:07] này thôi Tôi nghĩ là tôi dùng thống nhất
[00:55:10] đi Tôi bảo rồi đôi khi là mình này phải
[00:55:13] dùng thống nhất cho nó chung chứ chỗ này
[00:55:15] một kiểu chỗ kia một kiểu không
[00:55:31] cái activity
[00:55:33] nào có gì chiếm nhiều ấy nhỉ Ui Cái này
[00:55:37] chiếm tận 40 ph Ừ tôi đang nghĩ là
[00:55:42] à Tôi đang nghĩ
[00:55:44] là chắc là sang năm tôi sẽ phải mua con
[00:55:47] max Bây giờ tôi đang dùng Macbook
[00:55:50] E1 của công ty cấp chắc là sang năm tôi
[00:55:54] có thể đổi lên tôi định lúc đầu tôi sẽ
[00:55:56] định đổi lên là Macbook
[00:56:06] định thế
[00:56:08] thôi đy Kiểu như này submit đó update
[00:56:13] successed thì ở đây sẽ là thêm một cái
[00:56:16] xin không sự kiện ngày mai đấy
[00:56:20] đấy thì Ờ bây giờ mấy ông Nói chung là
[00:56:26] cái vụ new inmate cái này thực ra không
[00:56:29] cần nữa này c xóa đi xem có lỗ gì không
[00:56:32] nhá tại mình phải nên viết test đạn này
[00:56:35] tự nhiên có lỗi buồn cười
[00:56:38] à hại chang này
[00:56:43] lỗi chàng lấu thế
[00:56:46] Ờ chắc là lỗi
[00:56:55] nhớ như có cả test vụ view tôi chưa viết
[00:56:58] test vụ view bởi vì trên công ty tôi
[00:57:00] dùng làm tôi làm thuần bằng api f thì sẽ
[00:57:05] ph qu ra Script chứ tôi không test vụ
[00:57:07] view nên cũng không biết không chắc là
[00:57:10] larel hình như có hỗ trợ test vụ view
[00:57:12] đấy đấy không lỗi gì này chứng tỏ là
[00:57:14] kiểu đấy bớt đi một câu truy vấn nhưng
[00:57:17] mà về cơ bản thì tôi vẫn muốn là cái này
[00:57:19] tôi không tru vấn nữa mà tôi sẽ lấy ra
[00:57:36] nhắn anh xem cần chữa gì nhỉ Em nhắn
[00:57:41] chưa ở phần trạng thái đơn
[00:57:52] đơn nhưng nó vẫn hi hiển thị phòng đã
[00:57:57] trong cái này thì anh nghĩ là em thử
[00:58:00] export cho anh cái A databas của em xong
[00:58:03] anh thử import vào rồi anh truy vấn Hẳng
[00:58:06] để anh sửa cho thì nó sẽ dễ hơn em có D
[00:58:11] database rồi đúng
[00:58:19] database xong anh thử sửa cho thì cái
[00:58:23] đoạn này thì
[00:58:25] Bây giờ tôi định làm thì tôi sẽ kiểu
[00:58:27] thường sẽ có hai cách làm
[00:58:30] Ờ
[00:58:31] thôi mà thôi tôi chắc chỉ nói qua một
[00:58:35] cách thôi sẽ làm như
[00:58:37] này tôi thường này viết kiểu nh
[00:58:41] này get
[00:58:44] and by key như này t chuyển key vào như
[00:58:49] này x tôi sẽ Return về tôi gọi cách kiểu
[00:58:53] này
[00:58:55] remember này s ngồi đây là key luôn
[00:59:12] ty tôi thường hay làm theo kiểu như này
[00:59:14] tôi sẽ dùng một cái tạo một cái i5 là
[00:59:17] cách key kiểu như này để về sau mình sẽ
[00:59:21] biết được là Ừ thì thì mình có cái cái
[00:59:26] dự án mình có những cái key nào đang
[00:59:29] cách và về sau mình sẽ hỗ trợ xóa th
[00:59:31] cách key các thử
[00:59:33] thứ đây
[00:59:35] để và mình nên có một cái kiểu dạng một
[00:59:38] cái kiểu i5 quy ước gì đó chứ không mấy
[00:59:41] cái chuỗi mình đừng có nên hot code kiểu
[00:59:42] này thường mình nên có một cái quy ước
[00:59:44] gì đó đặt ở đâu đó thì người sau người
[00:59:46] ta sẽ làm theo quy ước đấy chứ mỗi chứ
[00:59:49] đoạn chỗi kiểu này mỗi chỗ ông đặt một
[00:59:51] kiểu nó sẽ không được Nó không nên
[01:00:01] này À nãy còn chưa mở cái mở bàn phím
[01:00:07] lên cho mấy
[01:00:23] đấy th sẽ sang p
[01:00:35] i5 K
[01:00:49] pp8 thì nó có i5 rồi nhưng mà tôi vẫn
[01:00:53] cảm thấy là dùng cái thư viện i5 này nó
[01:00:55] vẫn có cái gì đó hơn nên tôi vẫn dùng
[01:00:57] cái này
[01:01:11] public constant đy config Chuẩn rồi
[01:01:25] gian là 60 x 60 thường mình chả cần phải
[01:01:29] nhớ cái này thường
[01:01:31] là mình
[01:01:34] nên thường công ty tôi quy ước cái vụ
[01:01:37] này luôn ở trong cá key này đó
[01:01:40] là
[01:01:52] m à
[01:01:55] 5 m nghe không
[01:02:03] đầu đúng không
[01:02:22] thôi mình cũng một tiếng mà
[01:02:24] nó sẽ
[01:02:26] là
[01:02:28] one out chẳng
[01:02:39] nhân 60 phút Ừ đúng
[01:02:52] kiểu tầm kiểu một tháng thôi nhá Tôi vẫn
[01:02:56] nhớ là kiểu người đi trước của tôi đã để
[01:02:59] lại quả cách không phải cách Thứ nhất là
[01:03:02] tôi từng nói mấy ông Ừ kiểu gạch dưới
[01:03:06] kiểu kiau cũng được nhưng mà thôi Ờ
[01:03:08] ờ người đi trước từc để quả đoạn thứ
[01:03:13] nhất là tôi từng nói mấy ông về cái vụ
[01:03:14] là đừng bao giờ dùng cách forever bởi vì
[01:03:18] về sau mình quên không xóa cách rồi đi
[01:03:20] cách cái sẽ lưu mãi nó sẽ bị nặng kiểu
[01:03:23] dạng là cách này bản chất là nó lưu lại
[01:03:26] ở trong trong đâu ấy nhỉ nhớ Hình như là
[01:03:29] một chỗ nà Đó cái đ này còn đôi khi còn
[01:03:32] phụ thuộc vào ông Chỉnh trong nv của ông
[01:03:35] ông lưu kch dạng gì sử dạng file như này
[01:03:38] hoặc là dạng Credit hoặc là database tùy
[01:03:42] như đại khái
[01:03:44] là nó đã tốn bộ nhớ các thứ thứ nế là
[01:03:48] không bao giờ để forever căng nhất thì
[01:03:50] tầm để một tháng như này thôi nhớ người
[01:03:53] đi trước tôi để lại quả cách cách tận 1
[01:03:56] năm ạ kch 1 năm thì đừng có kch không ai
[01:03:59] điên kích tận 1 năm ạ V Chiểu kiểu
[01:04:03] Ờ sao cái đoạn đấy còn chẳng bao giờ sửa
[01:04:08] ấy đừng nhá Đừng V Kích 1 năm thật
[01:04:14] đấy hô mày Tôi nhìn kiểu ánh mắt kểu khó
[01:04:18] hiểu
[01:04:37] Nếu mà CH Giả sử ông chỉ muốn lấy mỗi
[01:04:39] cột valu ra cái này tiện ích của tôi là
[01:04:44] nó nó sẽ cũng hay phết khi mà tôi kiểu
[01:04:47] dùng chuột hay vì bấm phím tắt nó sẽ
[01:04:49] cảnh báo lên một cái để chỉ mày dùng
[01:04:52] phím tắt đi nó sẽ nhanh hơn hơn đấy
[01:05:06] lấy value như này thì thực ra mình chỉ
[01:05:08] cần value như này được gửi tôi nghĩ Tạm
[01:05:10] thời như này thì bây giờ mình sẽ thay
[01:05:13] vào đây thôi Cái này tôi sẽ để nó là
[01:05:17] static
[01:05:19] nh để là mình có thể gọi được Kiểu như
[01:05:23] này
[01:05:31] này Đây đang có bảy câu truy vấn tại
[01:05:36] trang Thực ra nó vẫn là B bởi vì mình
[01:05:38] phải ít nhất là truy vấn một lần đã rồi
[01:05:40] mình kck vào đúng không
[01:05:47] lỗi on
[01:05:50] string sao chả về lỗi được nhỉ
[01:05:55] À đúng rồi bây giờ mình trả về thẳng
[01:05:59] value Thực ra trả thằng về value thì in
[01:06:03] ra mỗi value thôi mình tự nhiên mình trả
[01:06:06] thêm cả key và các thứ thứ khối trước là
[01:06:08] thực ra thành
[01:06:11] thừa bên
[01:06:15] client
[01:06:17] copy copy bên này cho nhanh view
[01:06:38] tru vấn và không biết ở đây có kh có nói
[01:06:43] việc mình dùng cách không hình như không
[01:06:46] trong này thiếu mất cái vụ là mình có
[01:06:48] dùng cách hay không Ừ nhưng mà trong a
[01:06:52] van chạ telescope thì có nhá telescope
[01:06:57] Nó sẽ kiểu nói rõ là mấy ông có dung kch
[01:07:01] hay không thì rất là
[01:07:03] hay
[01:07:05] à đâu
[01:07:13] này đây cách này có cách hit tức là hám
[01:07:18] chỉ là nó Nó
[01:07:21] kiểu hit dịch ra ở đây
[01:07:24] không phải đấm nhá không phải đánh mà nó
[01:07:27] kiểu kiểu đã sử dụng nó bình thường ông
[01:07:30] sẽ có khái niệm là hit này Miss này với
[01:07:34] gì nhở nhớ là có một cái nữa là là kiểu
[01:07:39] ông đâu Tôi thử nếu ông muốn xóa cách
[01:07:44] thì để xóa toàn bộ cách thì ông thể dùng
[01:07:46] cái hàm này thực ra ông đừng có chạy cái
[01:07:49] này trên production
[01:07:50] nhá công ty ông đang có dung cách mà tự
[01:07:53] nhiên chạy cái này tr bo xoái cách đi
[01:07:56] chết luôn hệ thống đấy bởi vì hệ thống
[01:07:59] đấy đang quen dùng cách của tự nhiên
[01:08:01] kiểu một loạt kiểu truy vấn và dp chết
[01:08:03] luôn quá tả
[01:08:05] chết hồi trước công ty tôi cũng bị một
[01:08:08] phát mà không phải ừ cũng có thể bị chạy
[01:08:11] kiểu xóa kch kiểu thế nhưng mà một cái
[01:08:13] thứ hai đó là lỡ chuyển server sang chỗ
[01:08:15] khác mất kch chết luôn thệ th đây một
[01:08:20] cái mid À đúng rồi một cái nữa set đấy
[01:08:22] Lúc đầu sẽ kiểu Nếu mà giả sử mà không
[01:08:25] mà chưa lấy được thì sẽ xét lại nhưng mà
[01:08:28] xét cái này hình như là tôi nhớ có một
[01:08:30] cái fail chẳng ạn thì như thế là xét
[01:08:33] nhưng không xét được đó đây là một cái
[01:08:38] nhưng mà Đây mới chỉ dừng ở cơ bản tôi
[01:08:41] dạy cho mấy ông khái niệm nâng cao hơn
[01:08:44] một tí mấy ông sẽ cảm thấy Ui ngầu vãi
[01:08:46] chưa Nó sẽ là như nàoo nhất là nó sẽ trả
[01:08:50] về C ở đây Chắc chắn rồi à Đâu xing chứ
[01:08:52] Ở đây chả về mỗi value mà mỗi value thì
[01:08:57] nó sẽ là kiểu trả về dữ liệu là
[01:09:00] stream thì mấy ông thấy Ok anh vừa dạy
[01:09:04] em về cách em rất thích đúng không ạ
[01:09:07] Nhưng nếu Giả sử kiểu bài toán thực tế
[01:09:10] thì cái value này Thực ra bây giờ đang
[01:09:13] chỉ string thì tương đối nhẹ bây giờ giả
[01:09:16] sử nhá Giả sử nhá Tôi muốn cách Tôi muốn
[01:09:20] cách cái thằng config này tôi muốn trả
[01:09:24] về cả một cái object config này thì rõ
[01:09:27] ràng tôi sẽ đổi đây là s như này thì trả
[01:09:29] về toàn bộ cả config đúng không Tôi cứ
[01:09:32] tôi Return hẳn thằng anh nhá tôi làm tôi
[01:09:36] cứ làm trên này demo cho mấy ông Return
[01:09:39] thẳ hàng anh nhá Để mấy ông xem qua nhá
[01:09:42] và bây giờ tôi cứ clear cách để cho mấy
[01:09:46] ông dễ hình dung
[01:10:01] tôi chậm chư phải do code chậm
[01:10:09] Return ở đây là Return về kiểu dạng là
[01:10:12] là Ờ làm cái kiểu nó biến thành jion rồi
[01:10:16] nên thành ra mấy ông không xem được m
[01:10:19] xem lại kiểu này nhé t tắt C đi này
[01:10:24] đấy nó sẽ trả về cho ông một cái đối
[01:10:26] tượng này đúng không thực tế thực tế đó
[01:10:30] là không biết là công ty ông có vận dụng
[01:10:33] kiểu sử dụng mấy cái kiểu các thứ các
[01:10:35] thứ kiểu của một Hằng mồ hay không nhưng
[01:10:39] nhưng khi mà
[01:10:41] tôi tôi và ở công ty tôi dùng cách
[01:10:44] ấy thì tôi muốn là chỉ cách dữ liệu của
[01:10:49] cái thằng MU đồ này thôi chứ tôi không
[01:10:53] khi mà tôi cách này tôi không hề muốn
[01:10:55] dùng lại những cái tôi không muốn dùng
[01:10:58] tôi không quan tâm việc dùng lại những
[01:11:00] cái kiểu dạng là những cái attribute hay
[01:11:02] là creation trừ khi n m l dùng creation
[01:11:06] thì mình sẽ phải Quick creation ra chứ
[01:11:08] mình không không kiểu chọ thẳng kiểu lấy
[01:11:12] lấy thêm reation nữa Tôi không dùng thêm
[01:11:14] bất kỳ cái thuộc tính gì của thằng mod
[01:11:16] thì tính là tôi không nên kch cả mod đồ
[01:11:18] vì cách mồ này nó cũng rất nặng m không
[01:11:22] hiểu ý tôi không ạ tôi nói về bài toán
[01:11:24] tối ưu nhá Tôi đang dạy mấy ông về tư
[01:11:26] cách là senio chứ không còn là j nên tôi
[01:11:29] sẽ dạy nó cũng khá là nâng cao khá nhiều
[01:11:32] đấy nó bài toán thực tế hơn ấy thì thì
[01:11:36] mấy ông thấy là tôi đang cách cả cái
[01:11:38] thằng này nó sẽ rất là nặng thế bây giờ
[01:11:42] làm nào để sửa lại đoạn này thì thường
[01:11:45] là tôi sẽ làm như này thường mình
[01:11:49] sẽ mình sẽ thường ha làm
[01:11:52] là thế cách cái nào bây giờ nhẹ thì mình
[01:11:55] chỉn giảng là mình cách
[01:11:57] mỗi mình cách mỗi kiểu dạng là đối tượng
[01:12:00] này
[01:12:01] thôi Tôi thường n Gọi to như này nhưng
[01:12:04] với điều kiện Chắc chắn là thằng này nó
[01:12:06] phải trả về giá trị nhá Không tu này báo
[01:12:08] lỗ đấy nhá Được không ạ thêm hỏi chấm
[01:12:12] như này nó không lỗi đây là cái pp8 nó
[01:12:14] hỗ trợ điều này pp7 nó sẽ không điểu này
[01:12:20] đấy Và nếu trong trường hợp mà nó không
[01:12:23] tìm thấy thì cũng nên trả về cái này là
[01:12:25] nun này đúng không ạ Đây thì nó sẽ trả
[01:12:30] về như
[01:12:31] này à quên tôi đang kch nhỉ tạm xóa toạn
[01:12:36] luôn Xóa kch
[01:12:46] Sale nữa mà bây giờ nó sẽ trả về cái gì
[01:12:49] này tạ xóa lạ điể mấy ông dễ hình dung
[01:12:52] hơn này sẽ trả về cho mình một cái zon
[01:12:56] là một cái đoạn
[01:12:58] chuỗi chứa toàn bộ dữ liệu của thằng này
[01:13:00] Nhưng mà theo dạng chuỗi zion
[01:13:04] đấy không biết th này có T object không
[01:13:06] nhở sao
[01:13:08] object không nó không có to object đấy
[01:13:12] thế bây giờ Làm thế nào để biến thằng
[01:13:14] này về cơ bản mình vẫn muốn thao tác nó
[01:13:16] như với một cái thằng object Thì bây giờ
[01:13:19] mình sẽ mình cách lại thì cách Hằng ng
[01:13:21] Nhưng mình sẽ bản chất là sẽ Tôi thường
[01:13:24] khai báo đây là là ờ string như này
[01:13:29] chẳng hạn Hoặc là ông khai báo z đi
[01:13:39] code nó ra để nó biến nó thành đối tượng
[01:13:45] thường nó sẽ bảo thêm một vài cái lỗi
[01:13:47] lỗi này nữa như thường tôi cũng không
[01:13:50] Tôi không biết cái đp này như nào rồi
[01:14:01] cái disable cái này
[01:14:12] object tôi sẽ làm việc với cái thằng
[01:14:14] object
[01:14:22] đ thay vì thay vì
[01:14:26] tôi đây thứ nhất là mấy ông vừa hình
[01:14:29] dung được là tôi thay vì vừa cách lại cả
[01:14:31] một thằng mod nó sẽ rất là lớn Hồi trước
[01:14:34] công ty tôi bị thế bởi công ty tôi dùng
[01:14:36] cách rất là nhiều dự án lớn rồi mà bây
[01:14:38] giờ chục triệu người dùng rồi thì nó sẽ
[01:14:42] khác chục không phải người dùng mà chục
[01:14:44] triệu khách hàng Ờ thì thì lượng truy
[01:14:48] cập rất là lớn nên là mình sẽ cách rất
[01:14:49] nhiều thứ mà việc cách cả thằng MU đồ
[01:14:51] cách cách thế nhiều Hồi trước bị cũng bị
[01:14:54] Kiểu cái hệ thống kch cũng bị kiểu bị
[01:14:56] nặng ấy bở lưu rất nhiều thứ đấy nên là
[01:15:00] phải chuyển qua là sẽ kiểu lưu lại chuỗi
[01:15:02] như này lưu lại chuỗi Rất là nhẹ mà đúng
[01:15:05] không Đấy sau đó thì khi mà lấy ra khỏi
[01:15:07] cách thì mình sẽ kiểu biến nó lại thành
[01:15:11] đối đối tượng để mình xử lý nó như đối
[01:15:13] tượng Bình thường thôi Cái này đương
[01:15:15] nhiên là như tôi vừa nói nó sẽ không nó
[01:15:17] sẽ không còn giữ được những cái thuộc
[01:15:19] tính những attribute những cái kiểu tính
[01:15:21] năng của thằng mod nữa Nên là nếu ông
[01:15:24] muốn làm gì với nó thì ông phải làm ngay
[01:15:26] trong này ví dụ Giả sử ông sẽ ông muốn
[01:15:27] thêm cái creation nào đó thì ông sẽ phải
[01:15:29] qut ở trong này quit một cái gì gì đó để
[01:15:33] mà mình sẽ lưu lại cái đấy kèm với jion
[01:15:35] đấy còn không thì coi như là ông ông
[01:15:38] thao tác bình thường thôi và cái thứ hai
[01:15:41] nữa đó là mod của thằng larel nó có hỗ
[01:15:44] trợ là ông làm theo
[01:15:46] kiểu đối xử kiểu dùng từ đối xử không
[01:15:50] đang dùng hết tiếng Việt n thà từ đối xử
[01:15:52] nó hơi thô nhỉ Nhưng mà ông xử lý nó như
[01:15:56] một như một object hoặc như một array
[01:15:59] được ông biết vụ đấy không ạ Thằng m
[01:16:01] riêng Thằng m Đồ thằng larel nó cho kiểu
[01:16:04] ông có thể một là ông dùng kiểu dạng như
[01:16:06] này cũng được ho ông ghi kiểu như này
[01:16:09] cũng được nghĩa là kiểu xử lý nó với tư
[01:16:11] cách aray object đều được còn nếu mà ông
[01:16:14] làm ch kiểu như này rồi thì đ thì ông
[01:16:16] bắt buộc phải xử lý nó như một kiểu
[01:16:18] object hoặc làm kiểu như này thì ông xử
[01:16:20] lý nó như kiểu array đúng không tôi vẫn
[01:16:23] thường th thích object hơn thích kiểu
[01:16:25] dạng kiểu con trò kiểu kia hơn là kiểu
[01:16:27] dùng ngọc vuông nên tôi sẽ thích kiểu
[01:16:29] như
[01:16:31] này mấy ông nghe đến đoạn này có à Chắc
[01:16:37] chắn là nửa số trong đống này tôi khẳng
[01:16:39] định nửa số trong đúng này Không làm
[01:16:41] theo cách của công ty tôi hiện tại nên
[01:16:43] là có thể khó hiểu Và thậm chí là chưa
[01:16:46] động đên bao giờ nhưng mà ông nào ở đây
[01:16:50] hiểu không ạ hiểu Nãy giờ tôi nói gì
[01:16:51] không ạ
[01:16:58] đó để lại một cái dấu chấm một tia thần
[01:17:21] pp stor cái này cách này chỉ dùng được
[01:17:24] larel hay sao hay dùng fw work khác được
[01:17:27] không cách này thì đối với larel thì nó
[01:17:30] mới kiểu có kiểu MU đồ như này còn nhưng
[01:17:32] mà đây là một cái gợi ý cho em là kiểu
[01:17:34] dạng là là mình cách thì mình nên cách
[01:17:37] cái gì đó nhẹ xong rồi mình xử mình lấy
[01:17:39] ra mình xử lý đừng có cách của cái gì nó
[01:17:42] nặng quá nó chết hệ thống cách có vấn đề
[01:17:44] đúng
[01:17:54] hiểu đúng không hiểu hiểu thì bây giờ
[01:17:56] sang cái mới khó hơn nhá OK thì mấy ông
[01:17:59] vừa thấy là cái này nó dừng lại ở việc
[01:18:03] lấy à Nó vẫn chỉ nó vẫn chỉ là lấy từ
[01:18:07] trong cách ra Thế bây giờ mình có một
[01:18:09] bài toán nữa đó là tôi thấy lấy từ trong
[01:18:12] cách ra nó vẫn lâu thì bây giờ mình làm
[01:18:14] như nho tôi tôi Thực ra tôi cũng không
[01:18:17] dành về cái vụ local static đâu nhá bây
[01:18:21] giờ hỏi để tôi thử xem
[01:18:24] cách mấy ông biết Khải niệm cách satic
[01:18:49] niệm cách
[01:18:50] static cái này kích vào trong biến
[01:18:54] luôn và mà đương nhiên là mình hoàn toàn
[01:18:58] có thể sử dụng lại được cái biến này ở
[01:18:59] rất nhiều chỗ khác Và thậm chí là khi mà
[01:19:02] pp Tắt rồi nó vẫn nghĩa là chỉ là code
[01:19:05] chạy Xong rồi nghĩa là ví dụ Ông cứ Hình
[01:19:09] dung là bình thường code pp là kiểu khi
[01:19:12] mà code xong khi mà xử lý xong hết rồi
[01:19:15] đúng không Thì dữ liệu toàn bộ dữ liệu
[01:19:17] nó sẽ kiểu bị xóa sạch các thứ thì em
[01:19:21] chỉ là khi mà ông gọi lại nó thì ông
[01:19:23] không tận dụng lại cái biến cũ được đúng
[01:19:24] không đấy còn satic này trường hợp khác
[01:19:27] nghĩa là nó vẫn sẽ vẫn Lư lại ở trong
[01:19:30] code của ông không phải trong code như
[01:19:32] đại khai nó vẫn lưu lại trong bộ nhớ chứ
[01:19:34] nó không xóa đi thế nên là mình nghĩa là
[01:19:37] sao Tức là ví dụ đơn giản nhá Tôi khai
[01:19:41] báo một biển a bằ 5 đúng không Tôi chạy
[01:19:46] Xong cos rồi thường cái biến a đấy nó sẽ
[01:19:48] kểu bị bị kiểu nó sẽ bị xóa đi khỏi bộ
[01:19:52] nhớ đúng
[01:19:54] không và đặc biệt là người khác truy cập
[01:19:57] vào nữa thà ra mà kiểu Gọi gọi ra cái
[01:20:01] biến a đấy nó sẽ có thể không tồn tại
[01:20:04] đúng không Bởi vì nó chưa từng khai báo
[01:20:07] nhưng còn satic này tức là ông khai báo
[01:20:10] rồi ông sẽ dùng lại được ở không những
[01:20:13] là ông dùng lại được mà người khác truy
[01:20:15] cập vào cái phần mềm Ông vẫn có thể dùng
[01:20:17] lại được đấy đây local request l
[01:20:30] ở chỗ khác à Chỉ trong mỗi live ccle
[01:20:32] thôi à Ồ tôi lại tưởng người khác có thể
[01:20:37] dùng được để xem mà đúng nhỉ dịch cái
[01:20:41] này đúng nhỉ
[01:20:42] À
[01:21:02] này của tôi
[01:21:13] À ừ nế thế p nó vẫn là hạn chế của pp
[01:21:18] Nghĩa Chị ở kiểu nhiều người request thì
[01:21:21] nó vẫn load lại không dùng chung
[01:21:25] được Nhưng không sao Mình vẫn mình có
[01:21:29] hai tầng cách mà mình một tầng là cách
[01:21:31] bằng redit này rồi một tầng cách là
[01:21:47] cách đây mình dùng redit Mà tôi sẽ dùng
[01:21:51] redit
[01:21:54] 7 của em đây ạ Ok Đợi anh tí anh Chữa
[01:21:56] nốt cái này nhá Ờ thì tôi hướng Tôi sẽ
[01:21:59] chỉ cho ông cái về khai báo sa tích là
[01:22:01] như nào thì tôi sẽ thường tôi sẽ có một
[01:22:03] cái ở đây t đặt tên là
[01:22:08] Private
[01:22:11] array
[01:22:12] cách như này và bằng
[01:22:18] rỗng ở đây tôi sẽ có một cái là Vision
[01:22:22] xử lý thử thử này đúng không th sẽ ở đây
[01:22:24] là
[01:22:25] à data
[01:22:28] à data đi bằng như này sau đó thì mình
[01:22:33] sẽ cách nó
[01:22:43] này à Không cái này không còn là zit nữa
[01:22:47] Đợi tí Đợi
[01:22:54] À đây satic quên
[01:22:56] mất Thiếu cái
[01:23:13] và ở đây tôi sẽ là kiểm tra nếu mà có
[01:23:17] như này tôi Return thẳng luôn đây đây là
[01:23:21] hoàn chỉnh cái Cách Cách ở trên công ty
[01:23:24] tôi đang làm như này tức là sao mấy ông
[01:23:28] sẽ thấy là tôi sẽ tạo ra một cái biến là
[01:23:31] cách kiểu này và dạng static và nó là
[01:23:35] mảng tại sao nó lại mảng Bởi vì nếu mà
[01:23:38] từng từng gọi đến cái cách này rồi từng
[01:23:41] truyền đúng cái key này rồi thì tôi trả
[01:23:43] về luôn tôi không Tôi không gọi đến qua
[01:23:47] cách của redit nữa mà đây là cách của
[01:23:50] biến Tôi sẽ trả về thẳng luôn Như như
[01:23:52] này sau đó nếu mà giả sử không có đúng
[01:23:55] không ạ thì tôi mới sử dụng cách của
[01:23:57] biến như này để tôi xong rồi tôi lưu lại
[01:24:00] trong cách biến như này là trả về cái
[01:24:03] này tức là sao ví dụ Giả sử Giả sử nhá
[01:24:06] Tôi gọi ở đây rất nhiều lần như
[01:24:09] này
[01:24:10] tôi tôi sử dụng theo cách tôi xá tạm
[01:24:14] đoạn này đi nhá xá tạm đng My đi
[01:24:23] tôi chạy x m không hình dung
[01:24:32] ã tôi
[01:24:34] đây Return về một cái
[01:24:39] new
[01:24:41] này về để nói chung là cần cái Return để
[01:24:44] cho thằng telescope này nhận được đấy
[01:24:48] Ông thấy là sử dụng sáu lần cách một lần
[01:24:51] set những lần còn lại kiểu sử dụng tận
[01:24:54] dụng l cái kch cũ tận dụng kch cũ đúng
[01:24:56] chứ nghĩa nó sẽ gọi vào redit để để lấy
[01:24:59] lại K đúng không Đấy Bây giờ tôi mở lại
[01:25:02] cái đoạn này lên
[01:25:11] chạy
[01:25:14] đây ông thấy một lần mid một lần set
[01:25:18] không thể gọi vào bên redit nữa đấy thấy
[01:25:21] xịn hơn không xị n rất nhiều luôn đây là
[01:25:24] trong trường hợp mà
[01:25:25] cái ông đương nhiên bài toán sẽ có thể
[01:25:29] là nhề lúc ông ông sẽ bảo cái này th các
[01:25:33] em chỉ cần lấy ra kích một lần thôi Kiểu
[01:25:35] đ trong một request của em em chỉ sử
[01:25:36] dụng cái này một lần em
[01:25:38] không Em không kiểu dạng là không sử
[01:25:42] dụng lại cái dữ liệu này nhiều lần nên
[01:25:44] thành ra em không cần phải không cần
[01:25:46] phải
[01:25:47] kiểu cách cách x tích kiểu này Ừ cũng
[01:25:51] đúng nhưng mà ở công ty tôi thì không
[01:25:54] công ty tôi cái cái liên quan đến config
[01:25:56] này này được sử dụng lại rất nhiều lần
[01:25:59] nên trong một request luôn ấy nên là nên
[01:26:03] là bài toán là nếu nếu có thể thì mình
[01:26:05] vẫn nên cách lại đúng không cách sích
[01:26:07] này thì các bạn cũng chẳng tốn gì cả mấy
[01:26:09] nó tính ra nó vẫn chỉ tốn dung lượng bộ
[01:26:12] nhớm một tí thôi Bởi vì tính này cái này
[01:26:15] sẽ lấy từ trong RAM Còn cái này lấy từ
[01:26:17] trong Credit r nó về C bạn nhanh hơn thì
[01:26:20] vậy nhớ là thế
[01:26:23] nhớ là thế thôi còn ông nào ông nào mà
[01:26:27] thấy tôi nói gì sai cứ bảo tôi sửa cho
[01:26:30] tôi sửa sớm cho đỡ ngựa Ờ nhưng mấy ông
[01:26:34] vừa thấy qua mấy ông hiểu cái tôi vừa
[01:26:37] nói qua về vụ cách nà không m Ông thấy
[01:26:40] xịn hơn không xịn hơn đúng
[01:26:43] không gần như là khai báo một cái biến
[01:26:46] bình thường để ông lưu lại nó ông lấy từ
[01:26:48] trong cái biến đấy thay vì Lấy thẳng
[01:26:49] trực tiếp từ redit thôi mà đúng không
[01:26:58] thực tế tôi mới biết vụ này trên trường
[01:27:01] Chắc chắn là không không ai dạy mấy ông
[01:27:02] về vụ này cả cùng lắm là chỉ dạy ông lý
[01:27:05] thuyết sa tích là cái gì đúng
[01:27:14] phản đối gì cả thì cứ coi như là mấy ông
[01:27:17] đều cứ hình dung qua rồi nhá Còn nếu tôi
[01:27:21] nghĩ về sau kiểu gì với ông sẽ tiếp xúc
[01:27:22] v cái bài toán
[01:27:24] này cái biến nó khi nào chết anh nhỉ thì
[01:27:28] tôi vừa hỏi chat vity cho mấy ông ấy tôi
[01:27:31] cũng mới biết lại đây đó là là cái thằng
[01:27:34] p thì về cơ bản thì khi kết thúc một cái
[01:27:37] kiểu Cái live Circle của nó tức cả khi
[01:27:39] mà xử lý xong ấy thì nó cũng xóa xóa cái
[01:27:42] dữ liệu của biến đi thôi nghĩa biến
[01:27:44] satic này cũng sẽ biến mất đây chỉ phạm
[01:27:47] vi hoạt động trong một request duy nhất
[01:27:49] và và trong chu kỳ sống l cle của Script
[01:27:52] pp đó đy không duy trì qua yêu cầu khác
[01:27:56] nhau không dùng chung qua nhiều người
[01:27:57] dùng được đấy còn nếu dùng chung qua hay
[01:28:00] các thứ thứ thì nên dùng cách bình
[01:28:03] thường nhưng mà tôi bảo rồi Cái này phù
[01:28:05] hợp cho việc là phù hợp cho việc là kiểu
[01:28:09] trong một request của ông gọi lại cái
[01:28:12] này nhiều thì ông nên ông nên sử dụng
[01:28:14] theo cách
[01:28:16] này gọi là biết thôi đúng không
[01:28:21] ạ
[01:28:22] đấy thấy Dự thấy kiểu kinh nghiệm thực
[01:28:25] tế nó khác với cái lý thuyết hồi trước
[01:28:27] dạy không Trước dạy chắc là mấy ông chỉ
[01:28:30] biết mỗi
[01:28:31] Ờ mấy ông chỉ biết mỗi cách remember
[01:28:35] thậm chí remember
[01:28:37] forever kiểu như À quên mất còn vụ xóa
[01:28:41] kch nữa vụ xóa kch nữa cơ nhưng mà tôi
[01:28:45] nghĩ là để tôi chữa cho ông này trước đã
[01:28:48] nhé tôi chữa ông này trước
[01:28:51] đã
[01:28:57] virus gì không nhỉ tt tr Sậu
[01:29:01] quá Chắc không sao đâu nó thế mấy ông
[01:29:05] đừng có gửi virus tôi nhá đặt phòng
[01:29:30] này
[01:29:33] database
[01:29:34] ph
[01:30:05] nhỉ
[01:30:13] export t tu ở
[01:30:16] nhà à
[01:30:19] đây ddl
[01:30:23] file thử
[01:30:39] file bạn kia lại gửi cho file
[01:30:43] txt file này hình như là file ddl mà
[01:30:47] đúng
[01:30:58] tí đ
[01:31:40] rồi không biết thằng này có cái vụ là
[01:31:44] kiểu import vào không nhớ trước là có
[01:31:47] nhớ là có
[01:31:49] đấy
[01:31:50] sao
[01:31:58] stone
[01:31:59] import
[01:32:01] ddl
[01:32:10] plugin databas tool ồ cái plugin
[01:32:27] mà lừa nhỉ Xong rồi sao Now
[01:33:08] chết cái gì đấy Ông này dùng Collection
[01:33:11] gì đấy ông dị
[01:33:18] dùng gì nh General ho là hoặc là Unicode
[01:33:23] ông dùng gener Tại sao dùng cái
[01:34:08] luôn tì thế đúng
[01:34:11] không dùng cái mấy 9000
[01:34:15] À đây đoạn này không dùng version này à
[01:34:20] đâ
[01:34:22] À cái này là gì
[01:34:25] đó
[01:34:27] Translate rõ ràng C Xem T Ồ c x hồ trước
[01:34:33] mình không phân biệt hoa thường Ồ xịn xị
[01:34:38] ái Xong rồi làm tôi in không
[01:35:01] không có lỗi lỗi do máy
[01:35:04] tôi đợi tí đợi tí sửa lại được
[01:35:52] xá này đi cũng chạy mà đúng không
[01:36:21] đ Xong rồi ch không lỗi gì đâu quan tâm
[01:36:25] gì mình cái đấy Ở
[01:36:35] một cách mà đúng
[01:36:52] m Ông đừng thử chá đấy ở công ty
[01:37:05] ph
[01:37:14] sao thế
[01:37:15] Ông ông lại lừa rô rồi xem ạ
[01:37:22] gắn phòng
[01:37:23] auto để con số này
[01:37:47] phòng để em lọc lại Ạ thẽ chứng tỏ không
[01:37:51] Đúng Đúng không ông lại lừa tôi
[01:37:53] rồi thôi à thực ra vẫn phải có sự chặt
[01:37:57] chẽ dữ liệu thì câu tr vầ nó mới đúng
[01:38:00] nha thô ông ông sửa lại ông gửi lại tôi
[01:38:11] chung thôi đó là mấy ông trước khi gửi
[01:38:15] file cho ai đó đặc biệt là liên quan đến
[01:38:17] kiểu tôi Tôi không nói cá nhân tôi tôi
[01:38:20] thực ra thoải mái thôi Nhưng mà chắc
[01:38:21] chắn người khác kiểu đặc biệt ở công ty
[01:38:23] đặc biệt kiểu giống như v cái đầu buổi
[01:38:27] tôi tâm sự Tôi nói ông cái tâm sự về
[01:38:29] đồng nghệp Tôi nhắn tôi ấ
[01:38:31] thì mình làm sao cho mà họ cảm thấy là
[01:38:34] kiểu thoải mái và gọi là mình cấu Tiến
[01:38:36] hay cái gì gì đó để mà họ hoàn toàn
[01:38:39] thoải mái hỗ trợ mình ấy Ví dụ là kiểu
[01:38:42] trước khi gửi cho họ trước khi gửi email
[01:38:45] cho hay là bất kỳ cái gì cho một ai đó
[01:38:47] mình luôn kiểm tra kỹ lại các thứ thứ để
[01:38:51] để phòng kiểu bởi vì có nhiều người khó
[01:38:53] tính người ra kiểu đặc biệt là có thể
[01:38:56] tôi tôi thì dễ tính nhưng mà lúc mà tôi
[01:39:00] đang tự nhiên tôi đang khó chịu đang
[01:39:03] đang xử lý BC của tôi đúng không Tự
[01:39:05] nhiên ai đó mà nhờ tôi kiể fb hộ xong
[01:39:07] rồi người ra kiểu dạng là gửi cho mình
[01:39:10] kiểu hơi hợt ấy có thể mình sẽ không hỗ
[01:39:12] trợ đâu đúng không Đấy Nói chung là
[01:39:15] mình mình gọi là mang tiếng đi nhờ vả
[01:39:19] Đúng không Thì mình không phải không nhờ
[01:39:22] được thì vải nhá mà là mình cũng phải
[01:39:26] kiểu Hồi trước tôi có cái ảnh ở trên
[01:39:30] Facebook tôi để đó là nếu mà bạn muốn
[01:39:35] được câu trả lời có tâm ấy thì bạn phải
[01:39:37] đặt câu hỏi có tâm đấy Có tâm ở đây
[01:39:40] nghĩa là bạn phải cũng phải tâm huyết
[01:39:42] cho cái câu hỏi đấy không hỏi một cách
[01:39:44] hời hợt được có rất nhiều người Hồi
[01:39:45] trước hỏi tôi kiểu một cách hời hợt làm
[01:39:48] tôi nhưng mà tôi vì tôi dễ tí quá nên
[01:39:50] thành ra tôi cũng cũng nhắn lại họ kiểu
[01:39:52] tôi phải hỏi kỹ lại xem họ thực sự hỏi
[01:39:54] gì ý Sao tôi kiểu phải hỏi ba bốn lần
[01:40:04] cần cái gì ý đấy họ nhắn tin trả lời trả
[01:40:07] lời mình m Thế là giống như kiểu mình
[01:40:11] phải xin
[01:40:12] họ xin họ là kiểu mày để tao giúp đi ấ
[01:40:15] kiểu kểu thế đấy Nói chung là thực ra là
[01:40:17] bởi vì tính mình khác nhưng mà nhưng mà
[01:40:20] Mấy ông cũng phải cải thiện cái đấy
[01:40:21] phảiì Không thì mấy ông tôi bảo rồi tôi
[01:40:25] ở trên công ty Tôi không phải là con nhà
[01:40:27] người ta tôi vẫn kém rất nhiều Tôi đi
[01:40:29] nhờ và Ôi Sếp tôi rất nhiều lúc Sếp tôi
[01:40:33] bây giờ không khác gì cái thầy đầu tiên
[01:40:36] Ờ của tôi cả ngồi cạnh tôi lúc nào cũng
[01:40:40] bị tôi thình thả quay ra hỏi thì giả tôi
[01:40:42] quay ra nói nói Sếp tôi cao cực nhưng mà
[01:40:45] sếp tôi cũng bảo tôi là thú vui gọi là
[01:40:48] thú vui tiêu khiển của anh ơi nghe chỉ
[01:40:51] kiểu ông ông bây giờ ông cứ hình dung
[01:40:53] ông đi làm một thằng ngồi cạnh Hơi tí là
[01:40:57] hỏi mà trong khi đó
[01:40:59] là sẽ bị sao nhãng là một thứ hai là
[01:41:03] mình giúp nó mình có được cái gì đâu đấy
[01:41:05] các thứ thử đấy nhưng mà tôi tôi bằng
[01:41:08] cách thần thánh ởo đó tôi làm cho sếp
[01:41:10] tôi cảm thấy kiểu
[01:41:12] kiểu những cái hôm mà tôi kiểu phải nghỉ
[01:41:15] kiểu có lý do các thử thử ý xếp tội đồng
[01:41:19] nghiệp khác Toàn bảo
[01:41:21] nm Long hôm nay không đi làm kểu anh
[01:41:23] Bình trầm cảm vãi trưởng Anh Bình cả
[01:41:25] ngày không nói cái gì cả anh Bình anh
[01:41:28] Bình chẳng cả ngày không cười cái gì cả
[01:41:29] đấy các thứ thứ còn nay Long đi làm thấy
[01:41:33] anh anh Bình lại ngồi cười cả buổi có
[01:41:35] nhiều vãi trưởng kểu thế nghĩa là ông
[01:41:39] vừa tạo được không khí các thứ thứ mang
[01:41:41] tiếng ở nhề vả Đúng không Nói chung phải
[01:41:45] Tôi nghĩ
[01:41:47] là không không phải là việc ông không
[01:41:50] nên nên hỏi phải học hỏi liên tục nhưng
[01:41:52] mà ông phải học cách hỏi đúng không cái
[01:41:55] đấy quan
[01:41:57] trọng anh dùng m gì đấy ạ Tôi dùng m M1
[01:42:02] em1 công ty cấp nên thực ra có gì dùng
[01:42:05] lấy nhưng mà tính ra nó vẫn khá là mượt
[01:42:07] rất là ổn không vấn đề gì cả Bởi vì công
[01:42:11] ty th ra vẫn quan tâm về hiệu năng của
[01:42:13] anh em nên là nên là kiểu công ty cũng
[01:42:16] sắm cho anh em các thứ cũng gọi là
[01:42:19] ổn ở ở công ty tôi công ty Còn sắm cho
[01:42:23] cái con dog tức là kiểu bình thường M1
[01:42:27] này sẽ chỉ xuất ra được một màn hình ấy
[01:42:29] nhưng
[01:42:30] mà nhưng mà kiểu công ty cấp dog nó có
[01:42:34] thể nổi xuất ra được tận hai màn hình
[01:42:36] này đấy tiện m chưởng tối ưu thêm về các
[01:42:41] thứ em cứ mặt vui lên mật buồn thế Anh
[01:42:46] buôn theo thật đấy cứ tới tỉnh l thoải
[01:42:49] mái có sao đâu
[01:43:01] dòng mà Easy
[01:43:13] không
[01:43:15] nhỉ ch set Lion hả có cái này đy nhỉ Ơ
[01:43:22] bấm nhầm bấm nhầm bấm nhầm sao có cái
[01:43:27] này đấy
[01:43:37] không phải file này
[01:44:09] này tôi thử xem qua phòng
[01:44:11] nhá đầu tiên là phòng
[01:44:14] này Thực ra tự nhiên tôi nhìn cái này
[01:44:17] tôi lại muốn sang bên đ
[01:44:39] không
[01:44:45] code cho bạn đấy rồi tôi nhớ là hôm
[01:44:47] trước tôi vừa code bạn đấy ở đây
[01:44:49] này
[01:45:03] phòng
[01:45:04] đế Mình chỉ cần test một vài phòng thôi
[01:45:08] Ờ có tám phòng đúng không ạ đặt
[01:45:13] phòng đặt
[01:45:16] phòng có gắn phòng nữa đúng không gắn
[01:45:19] phòng ID đặt phòng
[01:45:21] nhảy mình bỏ những cái cột không cần đi
[01:45:25] Ờ mình quan tâm
[01:45:28] id id đặt phóng nối sang bây giờ đầu
[01:45:32] tiên thì như hôm trước bảo thì mình cần
[01:45:34] truy vấn ra cái những phòng đang đặt đã
[01:45:38] đầu tiên mình chạy thử cái này đã mình
[01:45:41] mình cứ chạy thử cái này trước đã đúng
[01:45:42] không đấy ai đây
[01:45:47] là sửa lại tí nào đầu tiên là đây là
[01:45:51] đắt phòng này rồi với gắn phòng này xịn
[01:45:55] không xịn nhìn chuẩn bị của tôi gợi ý đó
[01:45:59] Xịn không quá xịn nhưng mà do ông đặt
[01:46:14] không thể gợi ý
[01:46:30] đặt phòng
[01:46:31] chấm lấy ra những phòng đang được đặn
[01:46:34] nhá thì phải là
[01:46:45] này sẽ lấy cho tất cả những cái phòng đã
[01:46:47] đã đặt từ trước nay đúng chứ đúng không
[01:46:50] đ
[01:46:57] dung mà đúng
[01:47:05] là
[01:47:12] đi Phòng chấm sao tôi cũng chưa biết
[01:47:15] được hết toàn bộ thông tin
[01:47:17] của mọi thứ Nên tôi sẽ cứ chấm Sao đi
[01:47:21] ngày check in ngày check out này đúng
[01:47:23] không Mình sẽ que Giả sử là ngày check
[01:47:27] in
[01:47:29] này mình mình muốn lấy trong cái khoảng
[01:47:32] thời gian kiểu Dạ như này để biết được
[01:47:40] không Comment lại à đâu chẳng cần
[01:47:44] comment đâu sửa lại luôn đây được
[01:47:47] mà Ngày check in này
[01:47:57] check out
[01:48:18] nó hơi xấu thông cảm nhé
[01:48:28] thể set một cái ở trên này như này set
[01:48:31] một cái time start như này time end như
[01:48:34] này chẳng hạn đ sẽ
[01:48:38] là time
[01:48:47] start
[01:48:51] time
[01:48:52] này Cái này đặt tên biến của của SQL đấy
[01:48:59] tiếp theo là
[01:49:02] ờ trạng thái đơn đúng không trạng thái
[01:49:06] đơn bằng 1 đúng không bằng 1 tức là trạ
[01:49:12] thái đơn này là gì em nhỉ một là gì hai
[01:49:15] là
[01:49:27] Ngà check out này ĐT phòng chạng thái
[01:49:31] đơn này để mình thử select nó trước khi
[01:49:35] có cái đoạn này
[01:49:49] ờ
[01:50:08] rồi lấy đây Ok
[01:50:18] khoảng thời gian đã đặt đúng không
[01:50:21] Thì bây giờ mình sẽ
[01:50:23] lấy kiểm tra Ví dụ ở trong khoảng thời
[01:50:26] gian đây à mùng 1 đến mùng 3 chẳng hạn 1
[01:50:31] đến
[01:50:33] 03 đúng không Thì sẽ ra được phải ra
[01:50:37] được là đây phòng phòng 3 phòng 2 đều bị
[01:50:42] đặt rồi đúng không Đúng không nhỉ Ừ Hình
[01:50:47] như sai sai
[01:50:49] đấy
[01:50:50] đợi đợi tôi
[01:50:52] tí Đợi tôi một
[01:51:08] đúng cái trạng thái đơn bạn này hai đây
[01:51:12] sẽ
[01:51:14] là tháng 2 này mùng 1 đến tận ngày
[01:51:20] ngày 13
[01:51:27] có phải là sẽ chung ở cái lịch này đúng
[01:51:36] đó mùng 1 đến ngày mùng 3 Ok đó ra hai
[01:51:41] hai cái chuẩn
[01:51:50] hai là gì nhưng là đây cứ tạm quan tâm
[01:51:53] vế việc đã đặt đã đúng không đấy thì đây
[01:51:56] có phải là ra được tất cả phòng đã được
[01:51:57] đặt trong khoảng thời gian đấy Thì bây
[01:51:59] giờ mình chỉ đơn giản là select
[01:52:02] sao
[01:52:05] form form phòng đúng không
[01:52:09] que một là id not in trong cái kiểu cái
[01:52:16] trong cái ID tất cả ID phòng này em một
[01:52:20] cách đ một cách như này
[01:52:30] và phòng 3 rồi đúng không đó Thế là xong
[01:52:35] đấy còn à đây một cách Còn không thì các
[01:52:39] bạn có thể dùng là join l Joy để cả như
[01:52:45] này x rồi đây sẽ add là đã đặt đ như
[01:52:52] này on phòng đã đặt như th
[01:52:56] này rồi
[01:52:59] Where
[01:53:02] Ờ cũng đặt chấm như
[01:53:04] này x nun để nó
[01:53:08] sẽ
[01:53:21] đúng mà C chuy vấn anh ghi quá chuẩn nh
[01:53:25] Và thậm chí là hôm trước tôi mới biết
[01:53:27] được nếu mà khi mà ông truy vấn kiểu như
[01:53:29] này này ông truy vấn kiểu như này là bản
[01:53:32] chất là cái này trúng xấu thế rồi
[01:53:38] đ Cái refactor này xấu quá Tôi dùng cái
[01:53:41] refactor gần đây dùng cái này còn format
[01:53:44] lại đẹp
[01:54:15] cảnh
[01:54:16] báo
[01:54:18] đó
[01:54:33] let
[01:54:41] tí select này
[01:54:51] thằng này cung cấp mà Tại sao Thằng này
[01:54:53] bị lệch ấy nhỉ một cười v
[01:55:19] ở đây mình không thấy là khi mà kiểu
[01:55:21] select như này này bản chất là nó sẽ tạo
[01:55:24] ra một cái t table xong mình sẽ đây dùng
[01:55:28] explain ở đây sẽ
[01:55:36] để ông cái
[01:55:38] table cái table này này cái table phòng
[01:55:42] đã đặt này này nó sẽ là một cái time
[01:55:44] table để mình mình truy vấn tới kiểu rep
[01:55:48] ài không nhớ lắm nhưng mà nhưng mà có
[01:55:51] gần đây anh tôi khuyên thì nó là như này
[01:55:54] ông thực tế cái này bản chất là ông vẫn
[01:55:56] join vào mấy thằng này mà th ông sẽ có
[01:55:58] thể giữ y nguyên lại với thằng này như
[01:56:02] này đó sau đó thì cái đoạn We này này
[01:56:07] ông muốn dùng cái đoạn này gì Đúng không
[01:56:10] ông sẽ bê cái đoạn này vào trong cái on
[01:56:14] này này Đấy en này như này và tựng dụng
[01:56:19] lại được được ông x đạn ve đi đợ Tí
[01:56:25] and
[01:56:47] đây phòng đã đặt thì đây nó sẽ còn lại
[01:56:49] là lep chy với thằng này
[01:56:52] này nếu mà một khi l choy thì không phải
[01:56:55] le choy luôn ở đây ng nữa đúng nhỉ Tôi
[01:57:01] chưa thử vụ LP cho với tận hai bảng như
[01:57:04] này không biết là như nào th sao le cho
[01:57:06] thằng này lep cho thằng này nữa như le
[01:57:09] cho thằng này phải khai báo cụ thể là on
[01:57:12] một cái đã nhỉ on cái thằng này
[01:57:20] đợi tôi một tí đặt
[01:57:23] phòng đặt phòng ở đây sẽ
[01:57:27] là cho đặt phòng thì ở đây là đặt phòng
[01:57:32] chấm ID phòng
[01:57:41] chứ phải là
[01:57:44] à đây sẽ
[01:57:50] Đúng rồi đâ sẽ
[01:58:05] chid
[01:58:20] Ừ như nếu thế không en được C này nhỉ
[01:58:22] Không que được cái đoạn
[01:58:31] này và ngày check in các thứ thứ như
[01:58:34] này đó Uầy thế này tôi nghĩ là trông còn
[01:58:38] phức tạp hơn đối với ông nà không biết
[01:58:40] ờ và cái gắn phòng
[01:58:50] là nun chạy được không
[01:58:53] nhỉ bỏ đoạn này
[01:58:57] đi mất xử bốn cái à Hai 4 n của tôi rồi
[01:59:01] Ừ Chắc kiểu này không được
[01:59:09] stor thôi reverse lại code thôi Ctrl
[01:59:14] z ctr z Ctrl Z
[01:59:18] nào
[01:59:20] đấy chạy
[01:59:30] không Đúng chưa Bởi vì 32 được đặt mất
[01:59:34] rồi mà đy chạy mỗi đoạn này sẽ
[01:59:37] biết đây 32 đã được đặt trong khoảng
[01:59:42] thời gian này rồi đúng không thấy ngon
[01:59:44] chưa Ô vẫn chạy được mà nhỉ Đây tôi gửi
[01:59:48] cho ông ông Test thử nhá nhá Đây f
[01:59:53] này
[02:00:04] ông bắt trước cái cách debug như tôi vừa
[02:00:07] debug ấy xem chạy được không
[02:00:10] Uầy quay đi quay lại livestream hai
[02:00:13] tiếng thô thôi lại chuẩn bị đến giờ nghỉ
[02:00:15] rồi Ờ g nhỉ Hôm nay mình định dạy về
[02:00:18] những cái gì mà bây giờ chưa xong nhỉ Ừ
[02:00:21] ừ hôm nay thực ra dạy mỗi cách V Kí thôi
[02:00:23] Nhưng mà mình còn chưa dạy về cái kiểu
[02:00:25] clear cách các thứ thứ như nào cho buổi
[02:00:28] sau mình sẽ nói tiếp về clear cách này
[02:00:32] Thế đây hôm nay chỉ mới học cách
[02:00:34] à set and
[02:00:38] get đây sẽ là clear C này sẽ là liên
[02:00:42] quan đến model obs
[02:00:46] này
[02:00:48] Mod are observe đy như
[02:00:53] này không nhớ cách viết đâu thông cảm
[02:00:57] đấy mod là mod even này đó mình sẽ chỉ
[02:01:05] cho mấy ông với cái này mua đồ hay El
[02:01:08] quầ ấ Tôi không nhớ nữa hay bị nhẩm hai
[02:01:10] khái niệm này lắm hình như là mod đồ đấy
[02:01:14] Ờ nhưng mà ừ ây quay đi quay lại chỉ dạy
[02:01:20] dạy mấy ông về SQL cái lập
[02:01:23] tức Lựng người xem giảm ngay kiểu không
[02:01:26] hiểu cái gì cả không hiểu chuyện gì V
[02:01:27] đang xảy ra cả ờ đây buổi buổi sau tôi
[02:01:30] sẽ hướng dẫn cho mấy ông mấy cái này nhá
[02:01:33] Còn buổi hôm nay hai tiếng rồi tôi nghĩ
[02:01:35] mấy ông chẳng trụ được nữa đâu Thôi nghỉ
[02:01:38] thôi tôi còn đi ăn tối nữa tạ biết mấy
[02:01:41] ông nhá Nếu mà ông nào ở Hà Nội mai có
[02:01:44] hứng thì có thể nhắn rồi anh em thm kèo
[02:01:48] đi sự kiện th nhá Bye bye m
