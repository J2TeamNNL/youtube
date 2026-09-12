# Lập trình Web cơ bản - Buổi 11 - JavaScript - Regex

- Video ID: `nQcEK4HLoQs`
- URL: https://www.youtube.com/watch?v=nQcEK4HLoQs
- Published: 2021-11-14
- Duration: 1h 26m 37s (5197s)
- Language: vi
- Subtitle source: auto
- Kind: live

## Transcript

[00:00:01] à à
[00:00:03] Xin chào các bạn
[00:00:12] Mình công nhận là giờ hơi kiểu thay đổi
[00:00:12] liên tục nóng lúc 7 rưỡi lúc thì
[00:00:16] 7:50 lúc 8 giờ
[00:00:20] À thỉnh thoảng thế nên là thời ra cũng
[00:00:23] hơi bị chắc là
[00:00:26] anh cũng hơi khó chịu với các bạn một tí
[00:00:28] đó là thế kiểu là
[00:00:30] anh không đúng giờ lắm không ạ
[00:00:34] Các bạn sẽ không vào đúng giờ các bạn sẽ
[00:00:37] bị hỏng
[00:00:38] nhưng mà Đấy hóa cho Hồng nghe mình tâm
[00:00:41] sự thôi chứ không phải là hóa học của
[00:00:44] cái học thì vẫn đúng 8 giờ đúng không ạ
[00:00:52] mình thì
[00:00:52] cho sự bởi vì mình có nuôi con cún ra
[00:00:56] giờ giấc sinh hoạt của mình làm à em hỏi
[00:00:59] khi đã là đã là kiểu dặn á
[00:01:05] áo kiểu dạng ở sinh hoạt thất thường rồi
[00:01:07] Cho cậu ăn ngủ loạn hết cả lên thì con
[00:01:12] bị ảnh hưởng bởi vậy con Con Cún nữa vì
[00:01:14] con cú nó thường hay xua nó kiểu mình
[00:01:18] mình đang thuê nhà chung với 11 ông bạn
[00:01:22] nữa
[00:01:23] là nó cứ sủa ông bạn thấy đậu xanh cho
[00:01:27] bạn sống ở tầng trên cứ sủa kiểu cứ đi
[00:01:32] qua nó xua
[00:01:34] con gà con con này giống phốc Nhưng mà
[00:01:38] mình cấy vào nó bị ngu đứa kia nó không
[00:01:42] nhận diện được mùi và nó bị cận thì phải
[00:01:46] cứ sủa cái chính mình chứ nói ông kia
[00:01:55] chú chim cứu khoa học
[00:01:55] à Bạn Phương Linh Phương Linh này Phương
[00:01:58] Linh mọi không nhỉ Hình như là dưới vì
[00:02:01] mình mới xem lại
[00:02:03] anh bình luận điện thấy Phương Linh này
[00:02:06] em thay đổi ảnh đại diện với cảnh ở
[00:02:14] à à
[00:02:15] em nhắc nhớ mình có hứa với bạn này một
[00:02:18] cái
[00:02:20] tôi sẽ bật mí cho mày ông sau
[00:02:23] Ừ nếu mà bạn thấy đạt được
[00:02:29] à à
[00:02:29] À hôm nay sẽ hợp với rách mình còn mấy
[00:02:32] cái MI mày ghét hay phết
[00:02:34] mà trong người ông xem
[00:02:42] cái chính tôi từng đăng của cái gạch rồi
[00:02:42] Thế mi mấy
[00:02:44] ừ ừ
[00:02:54] ở Milan ý Nhựt nó tương tự chúng ra
[00:02:54] Swift thì méo đủ biết được nó có thể đã
[00:02:58] làm như thế nào tôi có thể My về cách nó
[00:03:01] là
[00:03:02] ừ ừ
[00:03:16] ở đây đây tôi có tôi tưởng đại bi mềm
[00:03:16] huyền thoại này
[00:03:18] Ừ
[00:03:19] tôi có 99 vấn đề sau đó tôi dùng dưới
[00:03:22] cách Tôi có 100 vấn đề để kiểu thế
[00:03:25] thì các bạn sẽ biết được là kiểu hoa
[00:03:30] ghét nó có thể khiến cho mình thêm vấn
[00:03:34] đề nào
[00:03:40] ở Nghệ An chỉ là người ta thường anh
[00:03:40] nghĩ đến việc dùng rách để tìm ra giải
[00:03:42] pháp nên thừa ra đôi khi Chính nó là thứ
[00:03:45] cậu tạo tạo nên vấn đề
[00:03:49] Nghe kể chuyện nha ở đầu tiên bạn ở một
[00:03:52] vấn đề này gái của giải pháp này bạn ở
[00:03:55] tận hai vấn đề
[00:04:02] Ừ nó bảo là số nhiều lý cách nói chính
[00:04:02] là les hay hối ạ
[00:04:05] cái kệ dễ
[00:04:07] anh
[00:04:08] nói thế nhưng mà nó giống kiểu ra Speed
[00:04:10] Thôi thì nhiều người dùng với nhiều
[00:04:12] người chết nhưng mà nhưng mà như người
[00:04:16] vẫn dùng
[00:04:17] Ừ nó nó nó là kiểu bị ngược cái hồi
[00:04:20] trước xem cái
[00:04:22] xổ số người số lập trình viên ghét 1 thứ
[00:04:27] gì đó nhất
[00:04:29] Việt kiều đông đảo lập trình viên ghét
[00:04:31] thì đỏ nhất gấp nhận thấy có vẻ ra suy
[00:04:34] trong ấy có phải giá hoa này Vân sau đó
[00:04:37] người ta mới xem lại thì hóa ra do cộng
[00:04:39] đồng người rất là đông thì nữa thấy số
[00:04:41] người ghét nó nó cũng đông kiểu thế
[00:04:44] Ừ nếu hình dung kiểu do nhiều người dùng
[00:04:48] có nhiều người khó chịu chứ Giả sử với
[00:04:50] là có nhiều với những ngôn ngữ lập trình
[00:04:51] và trái biết đến cả thì là là chuyện có
[00:04:54] người ghét đúng ạ ạ
[00:04:57] cho nên làm với ông đừng có để con số
[00:05:00] Đánh Lừa mấy ông nhìn thấy đống meme ở
[00:05:02] đây rất như nhưng sẽ nhiệt quay Chắc là
[00:05:06] cái ngôn ngữ bị ghét bỏ nhiều lắm Vân
[00:05:08] Vân đúng gọn
[00:05:09] khi họ cây cái lượng người ghét nó có
[00:05:12] thể chiếm 28 không ạ thì chẳng có ngày
[00:05:15] hai mươi phần trăm của cái của cái số
[00:05:19] người ghét đầu tư của cộng đồng đấy đối
[00:05:21] ngoại là lớn quá ra là trông có vẻ nhiều
[00:05:24] vai trưởng như thế này ngọn
[00:05:28] anh nói chung đề để các bạn với qua được
[00:05:31] rách nó có thể như thế nào trên mạng thì
[00:05:34] đầy đầy hướng dẫn cái Tôi từng chỉ cho
[00:05:38] mấy ông mấy ông cận nên nhớ những cái
[00:05:41] khái niệm này khi trao Google này nhất
[00:05:44] là các bạn thêm chữ Totoro nếu mà các
[00:05:47] bạn thật sự là không hiểu
[00:05:49] tôi rồi tôi như biết sai lầm nhưng khớp
[00:05:52] tô lúc nào
[00:05:55] cho
[00:06:03] đúng rồi chúng tôi rồi
[00:06:03] ờ ờ ờ
[00:06:05] à Còn nếu các bạn biết thêm nhiều cái
[00:06:09] giống như thêm trước 101 cũng được 101 à
[00:06:12] đối với bên nước ngoài nó sẽ là da cơ
[00:06:14] bản
[00:06:21] thích cái gì Nếu thay vì tiêu đề của kia
[00:06:21] tôi đấy lập trình quét 101 18 sẽ hiểu
[00:06:24] được là hạn chế nó giữ cơ bản như thế
[00:06:26] nào
[00:06:27] và hoặc là mấy ông để khiến chữ chít
[00:06:32] chít
[00:06:34] chít chít thì nhiều không chơi game này
[00:06:37] mày không biết cheat là theo kiểu là da
[00:06:39] lợn nó loa kẹo kéo dạng lại
[00:06:43] khách nó kiểu cậu biết à
[00:06:47] ai biết trước một cái gì đó Vân Vân Vân
[00:06:51] ừ ừ tôi là tôi thích sai cả
[00:06:55] không sao chào gù lên nó vẫn kiểu gợi ý
[00:06:59] đúng cho mấy ông mà bỏ qua đi
[00:07:02] và cái nói chung là chít là theo cửa là
[00:07:05] nó gian lận theo cửa là nó mánh khóe
[00:07:08] kiểu của Thế con xít Đó là kiểu ôxit nó
[00:07:12] nó nó Nó kiểu nó nằm trong một cái bảng
[00:07:15] excel vậy và ông kết hợp như thế này
[00:07:18] chẳng hạn tôi thử tra viên béo nhớ chứ
[00:07:21] hết
[00:07:23] đó thôi mấy ông ấn vào hình ảnh nó trở
[00:07:26] lại
[00:07:27] Lê Hoàng đã sẽ ra một cái bảng đầy đủ
[00:07:30] Anh Không những mà cú pháp mà còn đôi
[00:07:34] khi kèm gỡ cả chú thích ví dụ cho mấy
[00:07:37] ông như thế này chị tóm gọn trong một
[00:07:40] cái ảnh đó
[00:07:43] Ê mày ông thử tra không phải mỗi đấy vừa
[00:07:46] mọi cái giống như là HTML này Sao ngồi
[00:07:50] ra Swift này nó ra đây đủ những cái bộ
[00:07:53] thẻ chẳng ạ thật thứ thứ xét này chẳng
[00:07:56] hạn
[00:07:58] nó sẽ ra như này
[00:08:01] ở đó
[00:08:03] em thấy được khai sáng không Khi mà béo
[00:08:05] học lập trình cái này không áp dụng cho
[00:08:08] mỗi ngôn ngữ lập trình nhé Nếu nó dụng
[00:08:09] nên rất nhiều cái kiểu gì cũng sẽ có
[00:08:11] nhiều người làm chữ chế cho nó rồi cái
[00:08:16] Vì thế nên mới bạn ạ tôi dậy cho mấy ông
[00:08:19] Dần dần nó việc biết cách sử dụng Google
[00:08:21] mà nóng lạnh Ok làm chua ngọt bài hôm
[00:08:24] nay chúng ta sẽ tôi tôi có ghi ở trong
[00:08:27] này nó là ờ
[00:08:30] có tác dụng của nó nó ngon
[00:08:33] Ừ đợi có một tí thôi trả lời xét phát
[00:08:35] sốt nhắn tin tôi làm việc cả cuối tuần
[00:08:39] Chính xác là sếp của tội làm việc cuối
[00:08:41] tuần
[00:09:01] à à
[00:09:01] Ừ ok Nói chung bây giờ bắt đầu buổi học
[00:09:04] nha
[00:09:08] à à
[00:09:08] ở buổi học hình như tôi vừa nói đó là
[00:09:11] mình sẽ
[00:09:13] ở đầu tiên biết được ghét dùng để làm gì
[00:09:16] kết hợp với việc là
[00:09:18] mình sẽ học rách cả buổi hôm nay sẽ đi
[00:09:22] học với gạch thì các bạn sẽ thấy là
[00:09:25] vì nó có thể nhắn một buổi là không đủ
[00:09:29] cho gạch Nhưng mà cũng có thể dài nếu mà
[00:09:33] biết rồi vì về cơ bản để tôi chỉ nói lại
[00:09:36] toàn bộ những cái cơ bản của Jack Tôi
[00:09:39] không nói tí gì ở nâng cao cả thì đầu
[00:09:42] tiên để mà hiểu gạch dùng để làm gì thì
[00:09:46] trước hết là nó kết hợp với jess dùng để
[00:09:49] làm gì đã Hình như tôi từng nói đó là
[00:09:52] mấy ông cuối cái cái ra Swift này tôi
[00:09:56] dậy trong bé ông chị đủ đủ để cho bé Ông
[00:09:59] làm cái này nó ra và a date from thật là
[00:10:02] sao nghĩa là
[00:10:03] số bài toán ở đây nhá đó là mấy ông sẽ
[00:10:08] làm ở cái form để mà điền thông tin ra
[00:10:12] sửa điền thông tin đăng ký ở ạ đúng ngọn
[00:10:14] sau đó thì cho người dùng Điền Điền ABC
[00:10:17] Điền caffein đăng ký nhé Còn đăng ký này
[00:10:20] con khỉ các bạn sẽ thường anh có gì ạ Có
[00:10:23] họ tên email
[00:10:26] mật khẩu đúng rồi xô ngồi số điện thoại
[00:10:30] được ạ trà xử lý nhất cơ bản như thế nó
[00:10:33] ngọn đưa toàn bộ những cái này sau đó
[00:10:36] thì đẩy lên trên con xe vô rồi con
[00:10:39] server là sự xử lý nó lưu lại thông tin
[00:10:41] của người dùng đã nhật điểm gì để mà đem
[00:10:45] ra xử ra đây mà để cho người dùng đăng
[00:10:48] nhập vào đúng không ạ
[00:10:49] Ừ cái thì trước khi lưu lại thông tin
[00:10:54] lại thì nó rất là nguy hiểm theo kiểu
[00:10:57] người dùng nhập mình tay tinh cũng lưu à
[00:10:59] Thì thấy rất là sai hoặc à kiểu để kiểm
[00:11:03] tra cho người dùng kiểu cảnh báo người
[00:11:06] dùng Giả sử email người dùng nhập nhiều
[00:11:08] người dùng tôi từng gặp rất nhiều người
[00:11:10] theo kiểu là kiểu dụng là Long tự nhiên
[00:11:14] thay vì ai còn nhớ anh người ta quên
[00:11:16] người ta gõ như này chả ngán ra bị thiếu
[00:11:19] cái khe cắm cái gì đó đúng ạ thậm chí là
[00:11:24] gõ nhầm chấm thành dấu phẩy những ai
[00:11:27] chẳng nhãn nó bị lỗi Đúng không xong
[00:11:29] người dùng cứ thắc bát à Rõ ràng ta nhập
[00:11:31] Đúng rồi Nhưng mà giỡn ra mà khi mà
[00:11:33] người dùng nhập người dùng có người kiểm
[00:11:35] tra lại đâu nhưng không bao giờ được khi
[00:11:38] vọng người dùng nhập đúng không bao giờ
[00:11:40] được hi vọng
[00:11:41] anh điều đấy bởi vì thực sự thì người
[00:11:44] dùng là một cái gì đó mà vãi chưa
[00:11:47] và
[00:11:49] con người thì luôn có sai sót nên thành
[00:11:52] ra là người dùng Nhập nó sẽ ra loạn thì
[00:11:55] Jack
[00:11:57] Ừ nó hỗ trợ không phải đi kiếm không
[00:12:00] phải là để làm cái vụ
[00:12:03] ý là bắt được đúng sai như thế mà ra
[00:12:08] Swift mày đó thằng bắt để trường hợp
[00:12:10] đúng hay sai còn J AK là chỉ để kiểm tra
[00:12:14] xem một thứ nó nhập vào nó có nó có khớp
[00:12:20] hay không thôi
[00:12:22] ở đây gic đề kiểm tra duyệt và tìm
[00:12:27] đi tìm kiếm những thứ hợp lệ kiểu thế
[00:12:32] trong một chuỗi
[00:12:36] ký tự trở lại dịch ra cậu lý thuyết nó
[00:12:41] là như thế tức là sao
[00:12:44] ờ đâm chỉ là ông vừa rồi đấy Giả sử lá
[00:12:49] có một cái đoạn email đúng ạ
[00:12:51] Có một đợi email tôi tôi gõ phẳng như
[00:12:54] thế này thì mới ông nhìn dung được nó
[00:12:56] lên mê luôn tại sao ạ Tại sao Tại sao
[00:13:00] tôi gõ như này thì ông cũng hình dung nó
[00:13:01] là email đúng ạ
[00:13:04] a a
[00:13:09] b c
[00:13:09] như thế này
[00:13:10] xy&z nhà Nếu cũng hình dung này là email
[00:13:13] phải Sao ba Cái này nó có gì giống nhau
[00:13:17] có chị Loan nói chưa
[00:13:20] nhà hay đi làm
[00:13:21] tôi có những cái gì giống nhau ở đây với
[00:13:24] ông nhận diện nó là một email
[00:13:27] a a còng à còn gì để tôi nhập mũi còn
[00:13:31] như này thì nó ra đi Mèo không khóc đúng
[00:13:34] nó gọi
[00:13:36] em có cộng và chấm nhá Đây đây là mù
[00:13:40] Email gì mấy ông bảo đây là muốn email
[00:13:42] đúng không
[00:13:43] Đã thế lại nhầm rồi
[00:13:50] nhà hả Ai còn hỏi chấm nó biến thành
[00:13:50] email rồi Chết Đâu Thế là có giờ
[00:13:54] có còn tên miền ở đây thế này mới email
[00:13:57] đúng không
[00:14:12] Ừ đúng rồi bạn Cường Văn kia nó về 3
[00:14:12] trường Trần hơn tí không ạ nhưng mà Đấy
[00:14:16] nghĩa là bé ông đang bảo dần việc là
[00:14:18] tăng trước phải có một cái gì đó đúng
[00:14:20] không ạ mình trước có một lần thứ tự gì
[00:14:22] đó chuyển ngày Nếu ạ ABC ạ sau đó thì
[00:14:27] phải có dấu Hoa còn không ạ sau đó là
[00:14:29] một tên miền không ạ tên miền bản chất
[00:14:31] là tên miền của mấy ông cũng cũng bản
[00:14:34] chất Nó là một loại ký tự gì đó là sự
[00:14:36] vẫn là a b c sôi phải kèm theo người dấu
[00:14:39] chấm nữa xong rồi đằng sau Nó có thể là
[00:14:41] ABC tiếp Chán thế đấy theo cửa đơn giản
[00:14:45] bởi vì nhiều nơi thì nó sẽ còn theo cậu
[00:14:47] có cả số ở trong tên miền và dần đúng
[00:14:51] không ạ ạ
[00:14:52] Ừ đấy thì mày không thấy cái tô vừa hỏi
[00:14:56] thì mếu không lại bắt được trường hợp
[00:14:58] đẳng trước này nó có những trường nào gì
[00:15:02] xảy ra và cái tên miền nó có những
[00:15:05] trường hợp gì xảy ra cái thứ của mấy ông
[00:15:07] chắc chắn ở đây giống như lúc đầu mà ông
[00:15:10] nói thì mấy ông chị chắc chắn việc là nó
[00:15:12] có cong cùng lắm là thêm có thêm dấu
[00:15:15] chấm động ngoại đấy thì cái này nó sẽ là
[00:15:19] tính cách nó lại kiểu mình sẽ kết hợp
[00:15:23] chỗ mà theo kiểu dạng như thế này tăng
[00:15:25] trước nó là có thể toàn bộ là chữ từ a
[00:15:28] đến z trở lại và không phải là chữ viết
[00:15:31] hoa thì mình sẽ là a đến z như thế này
[00:15:36] cái khái niệm Ừ từ a đến z sôi kết hợp
[00:15:40] với ngoặc vuông như thế này để làm gì
[00:15:42] Nghĩa làm chị là
[00:15:45] cái cái
[00:15:54] chữ cái từ A đến Z Mình sẽ lấy 1 ký tự
[00:15:54] trong phạm vi từ a đến z nó sẽ là dùng
[00:15:58] ngoặc vuông như thế này để lấy một ký tự
[00:16:01] trong trong cái đấy Và nếu bây giờ sử
[00:16:03] các bạn muốn lấy nhiều ký tự
[00:16:06] ở trong từ a đến z thì các bạn sẽ thêm
[00:16:09] dấu như thế này thành chú dấu cộng nữa ạ
[00:16:12] nhưng mà đỡ nhau tôi để mua như thế này
[00:16:14] thì mới ông sẽ chẳng hiểu cái gì cả tôi
[00:16:17] sẽ ghi thảm họa học ở trên trang
[00:16:21] regex101.com để mấy ông xe ok
[00:16:25] anh béo để ý ở ở bên này mày không để ý
[00:16:28] cho tôi về cái
[00:16:30] mát information and
[00:16:33] thì nó sẽ hiển thị xa những cái mà nó
[00:16:36] thỏa mãn này và nó giải thích trông béo
[00:16:38] ngoài rất tiện tôi sẽ copy mới kể
[00:16:42] Ê mấy ông sẽ phải luôn biết được là cái
[00:16:44] nào đúng cái nào sai ở đây
[00:16:50] xe
[00:16:50] tải đầu tiên thì tôi gõ từ a đến z mà
[00:16:53] ông thấy chẳng hiện tượng gì xảy ra cả
[00:16:55] bởi vì Nghi như thế này thì nó lại không
[00:16:58] hiểu từ a đến z đâu ạ mình phải cho nó
[00:17:02] vào trong cái mặt vua như này chi mấy
[00:17:05] ông sẽ thấy là nó đang bôi có vẻ là tất
[00:17:08] cả các tất cả các chữ của mình từ anh
[00:17:10] ghét rồi nhớ nó đang bôi rồi ra chữ một
[00:17:15] chữ một đống ạ chứ nó không liền nhau để
[00:17:18] ví dụ chữ Long là cắt thành chữ L oreal
[00:17:21] này đúng ạ để mà mình muốn nó lấy liền
[00:17:25] cả một cụm cùng 1 lúc thì mình sẽ có
[00:17:28] khái niệm dùng dấu cộng nha
[00:17:30] tôi mọc chữ giây đi nhé đó khi mấy ông
[00:17:35] sẽ thấy là
[00:17:43] À mà thôi cứ để lại không ra thì mày ông
[00:17:43] sẽ thấy đó là
[00:17:46] anh thấy nó đang lấy chữ Long này sao
[00:17:49] lấy chữ Gmail này thôi lấy chữ con này
[00:17:51] không ạ như nó không lấy thêm chữ là nó
[00:17:55] không đầy kệ ta còn đúng ạ Ừ thì yêu
[00:17:58] mình cách cái mình đầy a còn mình chỉ
[00:18:00] dành cái chất cong này thôi ông ạ từ
[00:18:03] tiếp theo gì nữa mình gõ thêm chữ Gmail
[00:18:06] đúng ạ Mình gọi chữ mail nghe không được
[00:18:10] mấy ông thấy
[00:18:11] gọi chữ gmail như này thì nó lại không
[00:18:14] lấy chị ra gồm cả ABC kiểu đồ ngoại đứng
[00:18:18] chị ạ Thế bây giờ mình một lấy cả toàn
[00:18:22] bộ những thế này thì mình lại từ A Z
[00:18:24] đóng ngoặc
[00:18:29] từ là thì ghé tiệm này rồi lại dấu cộng
[00:18:29] Thế mày thì cái cậu này cậu này tôi sẽ
[00:18:33] giải thích cho mấy ông cộng nó là gì
[00:18:34] cộng trong lý gạch nó sẽ không hiểu Nó
[00:18:38] là cậu nó không hiểu Nó dấu cộng mà nó
[00:18:41] sẽ hiểu là
[00:18:47] Ừ nó là tôi tôi sẽ ghi theo dạng như này
[00:18:47] cho mày ông dễ hiểu nhé cháu làm min là
[00:18:50] một và mắt là vô cực
[00:18:55] cái cái nin là gì quan trọng Khởi My và
[00:18:59] cả mắc là gì Nghĩa là ám chỉ là chăm cái
[00:19:03] mặc vua mày này mình phải có ít nhất có
[00:19:06] ít nhất là một một ký tự lấy trong ô
[00:19:10] vuông này và
[00:19:12] mắc là vô cực Tức là mình có thể lấy bao
[00:19:15] nhiêu ký tự trong ngoặc vuông này cũng
[00:19:17] được đó nghĩa là chữ trong ngoặc vuông
[00:19:20] này Ít nhất nó phải có một giống như
[00:19:23] trong trường hợp này các bạn thấy tôi
[00:19:25] thử Xóa lại đi nhé
[00:19:27] Ừ nếu không thấy à Nếu mà tôi để như này
[00:19:31] nhà
[00:19:31] Để như này thôi thì nó sẽ lại có khái
[00:19:35] niệm là lấy một ký tự nằm trong từ a đến
[00:19:37] z tức là xa nếu mà như thế này
[00:19:40] nó lấy một ký tự nặng nằm trong gì gì đó
[00:19:44] thì tức làm Nhi là một và mắc cũng là
[00:19:46] một
[00:19:47] và nó không hề ở cái dòng chỉ có a còng
[00:19:52] hai a còng chấm này nó làm gì có chữ thử
[00:19:55] anh siro đúng không ạ thì nó không lấy
[00:19:57] gì cả Còn trong trường hợp này nó lấy
[00:20:00] 1111 này đúng không ạ nhưng bờ tôi cho
[00:20:03] nó dấu cộng như thế này tắm thì nó sẽ mi
[00:20:08] là một và mắc và vụ Vô Cực nên Hay là cứ
[00:20:11] cái đoạn nào có chuỗi
[00:20:12] ô chữ thì nó sẽ lấy nó không ạ
[00:20:15] ờ ờ tiếp theo là mình sẽ cho mình mình
[00:20:21] sẽ cho là a còn nó như vậy tôi nói sao
[00:20:24] lại từ a đến z này
[00:20:25] thôi mình lại cập này để lấy bởi trong
[00:20:29] trường hợp giờ sử Tôi có một cái email
[00:20:31] dạng như này à
[00:20:33] ở đó thì nó sẽ không lấy đúng ạ Nó sẽ
[00:20:38] không lời kể Lâm A còng tay và bắt buộc
[00:20:41] sau đó phải có ký tự thì nó mới lấy đấy
[00:20:44] ạ tiếp theo là bé ông muốn có dấu chấm
[00:20:47] nữa để bọn tôi thử chấm ôm Bống xem nhé
[00:20:51] Ừ ok chấm Cái này chả gì xảy ra tạm thời
[00:20:54] Thế không ạ sợ tôi An rét em ạ a đến
[00:21:04] z sao lại cập như ai chẳng hạn nó gọn
[00:21:04] nếu mà tại sao tự nhiên tôi mà chấm ở
[00:21:06] đây như thế này chấm ở đây nó có vấn đề
[00:21:08] đấy ạ Chưa hỏi chấm nơi cho vui này đâu
[00:21:10] Tôi thử ví dụ cho mấy ông nhé tôi không
[00:21:13] đổi này chấm Có để nó dấu gạch ngang
[00:21:16] nghe đi
[00:21:17] khi mang thai có nói gì xảy ra không ạ
[00:21:19] Cứ để nó là xấu à
[00:21:24] ah còn nữa cũng được đổi nó là như này
[00:21:27] cũng được đổi nó thành nhưng lại được
[00:21:29] chấm ở đây nếu mà Mấy ông gõ nó thẳng là
[00:21:33] dấu chấm như này thì nó bị sai để trong
[00:21:35] túi rách chấm nói thay thế cho mọi ký tự
[00:21:39] đây nó sẽ là mắt any vector vọng nghĩa
[00:21:44] nó thay thế cho mọi thứ tự thành ra là
[00:21:47] kiểu bây giờ mấy ông muốn hiểu chấm nó
[00:21:50] chỉ đơn giản là chấm thôi
[00:21:52] có giống thì mình sẽ phải dùng cái sọc
[00:21:56] chéo nhé để hạ sốt chéo như này bể nó
[00:22:00] cái khái niệm trong lập chỉnh khi một
[00:22:03] chục chéo trước một cái gì đó thì nó sẽ
[00:22:06] để mà
[00:22:08] à à AF nó kiểu dạng là hết Nó là ký tự
[00:22:15] bình thường tức là nó sẽ chẳng có cái
[00:22:19] tác dụng gì ngoài cái kiểu nó là chỉ nó
[00:22:22] cả bởi vì giống như vừa nãy tôi nói về
[00:22:25] vụ dấu cộng này hai dấu ngoặc vuông này
[00:22:28] mấy ông cũng thay thế bởi vì nó làm một
[00:22:31] cái kiểu nó nó vừa là ký tự nó vừa có
[00:22:34] một cái ý nghĩa riêng của nó đúng ạ Chứ
[00:22:37] không phải một ký tự bình thường nữa thì
[00:22:39] cái giấu hoặc gạch chéo này để ép cho nó
[00:22:42] thành kính tự bình thường Và thậm chí
[00:22:45] nếu mấy ông muốn giờ xử làm Nếu muốn có
[00:22:47] dấu gạch chéo ở đây trở lại như thế này
[00:22:50] giả sử Giả sử Thế thôi nhá Khi mấy ông
[00:22:53] lại có thể là cái chéo gạch chéo như này
[00:22:56] để chắc chắn nó là ký tự để chém đúng
[00:23:01] không ạ
[00:23:02] ở
[00:23:04] đó đây bay vừa rồi mới chỉ cũng là cơ
[00:23:09] bản một tí về à Ông kia nói về vụ
[00:23:13] chéo nơ vải chéo rồi chào Tây đúng không
[00:23:16] cái chén cái chéo mà kết hợp với chữ như
[00:23:21] thế thì nó lại mày nghĩa khác ở trong
[00:23:24] back nên có
[00:23:25] à Tôi đang nói được là gạch chéo ép nó
[00:23:28] ký sự bình thường khi nó là cái chèo ký
[00:23:30] tự Còn với chữ thì nó lại khác
[00:23:36] anh cứ bình tĩnh Nhã Okay ở đây
[00:23:40] mày mì Ông vừa thấy đây là mới chỉ đang
[00:23:44] bề mua cua và gạch các bạn Nhưng mà thực
[00:23:48] ra là nó vẫn còn thêm nhiều cá yếu tố
[00:23:49] nữa bởi vì trong trong Email đấy thì nó
[00:23:54] còn có cả số có cả dấu chấm
[00:23:58] Anh nghịch dưới nấu ăn
[00:24:01] Ừ đúng đúng nhỉ cách dưới có mà đúng
[00:24:04] không gạch ngang rồi Mình nhớ không có
[00:24:06] bệnh nha như có cái gì dưới
[00:24:14] em thật sự email của bạn với dụng lại
[00:24:14] à à khi yêu em ạ ạ
[00:24:19] hàng
[00:24:21] triệu trái tim tan vỡ
[00:24:34] hả Còn
[00:24:34] Lại Đây này
[00:24:37] kiểu nhà Ờ cái này là
[00:24:41] cái này câu của ông JV Evermind đó không
[00:24:46] không phải tôi tự nghĩ ra đâu là thì giả
[00:24:49] sử như thế này
[00:24:50] em có một cái email như thế này đúng
[00:24:52] không ạ Chồng cũng có vẻ hợp lệ thì
[00:24:56] Ừ thì
[00:24:57] phải dùng những cách để mà nhận diện ra
[00:25:00] một vì đây là một email hợp lệ đúng
[00:25:02] không ạ thì nó như thế nào
[00:25:04] ừ ừ
[00:25:05] Ừ
[00:25:07] thì per Minute cái cái vừa rồi mình áp
[00:25:11] dụng đúng hết tất cả trên những cái dưới
[00:25:13] lại không đúng không ạ Thì bây giờ mình
[00:25:15] làm thế nào để dưới này đúng không ạ Vì
[00:25:17] ông sẽ để ở đây nó sẽ bao gồm những cái
[00:25:20] gì đó là nó có gạch dưới này nó có cả
[00:25:23] một này 1 đến 9 chẳng ạ đúng không ạ
[00:25:28] Ừ
[00:25:29] thì cách để mà làm nó đỡ giản là mà đơn
[00:25:33] giản nữa nhé đó là theo kiểu là nếu
[00:25:35] không có thể ghi thảm hại trong cái
[00:25:37] ngoặc vuông này là từ 1 đến 9 thận chết
[00:25:41] từ 0 đến 9 ý nghĩa có nhập được chọn số
[00:25:43] không đi như này và mấy ông một lấy ở cá
[00:25:47] sấu gạch dưới đúng không ạ thì mới ông
[00:25:49] cho thêm kịch rửa như thế này tôi thêm
[00:25:52] cái giàu quá như thế này chắc thằng nọ
[00:25:54] nó là cái đấy đôi khi được ra không cần
[00:25:56] đâu rồi cánh dưới nó không ý nghĩa gì cả
[00:25:57] nhưng mà để này cho nó nó hiểu nó chắc
[00:26:01] chắn nó là Cái dưới là sự nếu người ông
[00:26:03] không biết đó thì nó sẽ ra như thế này
[00:26:04] không ạ đi
[00:26:07] à à
[00:26:09] Ừ cái này Tôi nhấn mạnh lại không phải
[00:26:12] do tôi nghĩ ra lắm nhé không Nếu không
[00:26:14] phải bảo tôi ăn cắp bản quyền í
[00:26:17] ở đó thì đây Đây là lý khách mời ông sẽ
[00:26:21] thấy da dưới nách Nó có tác dụng là nó
[00:26:23] nó sẽ nhập những cái Nếu mà Mấy ông chưa
[00:26:27] học qua di cách mà không nhìn cái chỗ
[00:26:29] làm nó chả hiểu nó cái gì cả đúng hạn
[00:26:31] bây giờ một ông nó gió mới vào xem mới
[00:26:34] học sẽ nhìn thấy loại này chả hiểu nó gì
[00:26:36] cả nhưng tự nhiên nó lại khiến cho bôi
[00:26:38] bôi sáng đấy dòng dừa như này không ạ
[00:26:40] thì mới ông sẽ giữ hình dung được A cái
[00:26:43] đoạn mày có gia dụng là tìm kiếm một cái
[00:26:45] chuỗi văn bản đó nằm trong cái đoạn dài
[00:26:47] nhé Đông ạ ạ
[00:26:59] Ừ thì mệnh mày ông sẽ hiểu được lấy gạch
[00:26:59] có tác dụng là kiểu để bàn như thế đề
[00:27:02] thi thì biết nó không chỉ có mỗi những
[00:27:07] cái này không chỉ có mỗi như thế này tôi
[00:27:10] sẽ giải thích nốt cho mấy ông những cái
[00:27:12] như sau
[00:27:15] đầu tiên thì nó sẽ có khái niệm nó là
[00:27:17] như này là sử tôi sẽ đền mua nó ra kiểm
[00:27:22] một mười Nga thì nó sẽ làm nhim1 mắt
[00:27:26] người
[00:27:28] Các bạn nhớ lại vụ Mimax tôi vừa nói
[00:27:32] trên không ạ Tức làm chỉ ra đằng trước
[00:27:35] nó ví dụ là sự là đây tôi có
[00:27:39] ờ ờ
[00:27:46] a a a đến z nó làm in 1 mắt 10 nghe đi
[00:27:47] giờ tôi có một chỗ như thế này
[00:27:51] xe tải mẹ ông thầy đó đến cái đoạn này
[00:27:53] tự nhiên màu nó khác gì đoạn này nó đến
[00:27:56] 10 rồi nó ngừng ngọn đoạn này nó nó lại
[00:28:01] tách ra một hai ông ạ
[00:28:10] Ừ nó tách làm hai đây mày Ông thấy như
[00:28:10] này không sao nhưng đến 10 hoặc tách làm
[00:28:12] hai Bởi vì khi đến 10 rồi nó sẽ không
[00:28:17] nằm trong cái a z này nữa nó tách ra
[00:28:19] không ạ ạ
[00:28:21] thì
[00:28:22] nó sẽ có thêm những cái dụng là phẩy như
[00:28:26] này thôi thì nó sẽ là Nhi ngủ mắc Vô Cực
[00:28:39] tin tức à tức là sao Là sử Bây giờ tôi
[00:28:39] cho nó thành như này thì mấy ông sẽ thấy
[00:28:42] nó bôi được sáng hết toàn bộ nó này buổi
[00:28:45] sáng toàn bộ nó này chính là sự đối cho
[00:28:47] đây số nào ạ
[00:28:48] Nó không bôi cái gì cả bởi rõ ràng là số
[00:28:51] lại không làm cho mày ít ạ trong bảng
[00:28:53] chữ cái thứ hai z nó nhọn
[00:28:56] Ừ nếu hiểu Nãy giờ tôi nói gì mấy đấy
[00:28:59] Khi Cái cái đoạn này từ a đến z lắm chị
[00:29:01] lấy chữ trong màng cái từ A Z thôi mà nó
[00:29:04] không ạ Và Nó đang bôi tất cả chữ nó có
[00:29:07] bôi số chỉ số này nó không làm trong
[00:29:09] thời gian ghét không ạ
[00:29:11] Đúng rồi bạn kia nói khỏi cầu và trả lời
[00:29:15] được rồi Đúng rồi nếu viết hoa thì nó sẽ
[00:29:18] là từ a đến z thì cậu biết hoa như thế
[00:29:20] này nhờ tí rồi sẽ chỉ cho mấy ông về
[00:29:23] những cái nữa
[00:29:25] ờ Ok và giả sử các bạn muốn ép nó cho là
[00:29:31] nó bắt buộc phải là
[00:29:33] có một giới hạn một cái gì cụ thể là sự
[00:29:37] là giới hạn nó là 10 ký tự trở lại thì
[00:29:40] nó sẽ là như thế này nhìn 10 và mắt mưa
[00:29:45] chữ đầu ngồi bạn kia lại hỏi thêm một
[00:29:48] câu cũng chuẩn nữa đó là Unicode thì nó
[00:29:50] sẽ không được trong trường hợp này là sử
[00:29:53] đây là Nguyễn nhà lại nhà Ông thấy à báo
[00:29:57] bị mất mất cái chữ có dấu bởi vì cái này
[00:30:01] nó chỉ nằm trong bảng AC nó là Index 97
[00:30:04] tuyến inject 122 còn cách bề mà nó lấy
[00:30:09] được Unicode thì bạn phải như hình như
[00:30:12] mình nhớ không lầm là thêm cái Unicode
[00:30:14] rồi đây phải
[00:30:15] a Nhớ Ngựa Cái này nó không được Mình
[00:30:18] mình nhớ phải áp dụng cái khác rồi
[00:30:21] nhưng mà mình mình Đúng rồi Đúng rồi
[00:30:25] Đúng rồi Mình quên quyền quyết riêng về
[00:30:28] cái bắt về kệ ghi khách về chữ
[00:30:33] chữ có dấu ấy mấy ông phải nhập đầy đủ
[00:30:37] đầy đủ cái có dấu mà khi nào tôi sẽ gửi
[00:30:41] cho ông cái đoạn ghét đấy nghĩa là béo
[00:30:44] về ghi đầy đủ tất cả các trường hợp có
[00:30:46] dấu gạo để mà thỏa mãn chưa ngoài từ A
[00:30:48] đến Z ở đủ nữa mới qua đây tôi làm thực
[00:30:52] ra đoạn đầy tổng góp trên mạng thôi Em
[00:30:54] mà công nhận đấy ạ
[00:30:56] khi nhập đầy đủ tất cả trường hợp có dấu
[00:30:58] buồn cười cực
[00:31:08] cái cái Min 10 mắc 10 này tức là sao tôi
[00:31:08] thay nó là mười Nga thì mới Ông thấy là
[00:31:13] ở đây trường hợp trường hợp chữ như này
[00:31:17] thì nó không hề được bôi gì cả đến khi
[00:31:19] đủ ký tự thì nó mới bắt đầu được Xá Đông
[00:31:22] ạ
[00:31:23] đúng ạ đó
[00:31:27] A và ngoài ra nó còn thêm những cái gì
[00:31:30] nữa nó còn thêm những cái viết tắt của
[00:31:33] cái hay vì viết kiểu như này thì mấy ông
[00:31:35] thấy rõ ràng là cái vụ một mắc Vô Cực
[00:31:39] này nó bằng nó có phải bằng với cái kí
[00:31:42] tự dấu cộng vừa nãy của mình vừa học ở
[00:31:45] trên không ạ
[00:31:47] à à
[00:31:50] anh không không không không có cách nào
[00:31:52] để đỡ nông dân ở không ạ à
[00:31:55] à à
[00:31:57] Ê mấy ông chị nó ra Cốc Cốc của ai đó về
[00:32:00] rồi
[00:32:06] nó con thêm cái ví dụ là sao như thế này
[00:32:06] nó sẽ là meme không mắc Vô Cực
[00:32:13] nghĩa là có cũng được và
[00:32:17] à à đầu tiên không có cũng được và có
[00:32:20] thì thoải mái đều ạ Nó sẽ bằng
[00:32:25] à tôi ghi theo kiểu dạng như thế này thì
[00:32:29] cạnh nhau cho mấy ông dễ hình dung đi ừ
[00:32:33] Chúng tôi sẽ ghi trò này cho mấy ông dễ
[00:32:35] hình dung nhé á
[00:32:37] ừ ừ
[00:32:38] [âm nhạc]
[00:32:41] đã xóa này đi Cái này sẽ là như thế này
[00:32:46] hoặc cái này nó sẽ là bằng không thế này
[00:32:50] đúng ạ
[00:32:51] Ừ
[00:32:57] tôi gõ và chăm sóc khi tách để mày ông
[00:32:57] mà nhìn nhìn theo nó rõ nhé ạ
[00:33:12] ờ ờ tiếp theo là mình còn thêm cả vụ hỏi
[00:33:12] chấm hỏi chấm nó sẽ là meme không mắc
[00:33:17] một tất cả
[00:33:20] như này cây cây hỏi chấm này nó sẽ có
[00:33:24] tác dụng là nếu mà có à Nếu mà không có
[00:33:28] cũng được và nếu có chữ phép có một đống
[00:33:31] ngoại nó sẽ ra Kiểu kiểu dạng mà à
[00:33:36] anh
[00:33:41] gọi cho ông một ví dụ nó là A B C như
[00:33:41] thế này ABC nếu công việc khớp đúng
[00:33:44] không ạ nhưng mình nhưng mà giờ sự tôi
[00:33:47] muốn mà AC nó cũng khớp
[00:33:49] sự thật bà a b c nóichung ABC cũng khớp
[00:33:54] và AC vuông góc thì mình sẽ có thêm dấu
[00:33:56] hỏi chấm rồi đấy để để ăn Chỉ Là Vui Ve
[00:34:00] di kỵ ký tự bên này có cũng được còn
[00:34:03] không có không có cũng được bà Bác Hồ
[00:34:06] chỉ có một ký tự thôi thì nó sẽ như thế
[00:34:08] này đúng hạn thậm chí là mấy ông muốn
[00:34:12] cho là a
[00:34:13] ADC cũng được như thế này thì cái này nó
[00:34:18] sẽ nằm trong cảnh ô vuông và cái này là
[00:34:21] B hoặc B đúng ạ Họ sẽ kiểm
[00:34:25] ảnh BHD
[00:34:27] Ừ có gì là những cảm đấy đấy thì thì mới
[00:34:32] ông sẽ thấy ra à thực ra là cái vụ
[00:34:35] Ừ
[00:34:36] nếu mà không hỏi chấm nhảy thì mới Ông
[00:34:39] thấy à họa sĩ chỉ
[00:34:41] thì kệ nó Nó làm i1 và mắc một nghĩa bắt
[00:34:44] buộc phải có ký tự B D nằm ở đây đó
[00:34:46] ngoại và nó không lấy cái C nhưng mà này
[00:34:48] có giờ sự mình thêm hỏi chấm vào đây
[00:34:50] chém Chị Đã Lấy ở trong này lấy trong
[00:34:53] cái mặt vua ngày một ký tự hoặc là không
[00:34:56] đấy Cái gì cũng được nãy bây giờ tăng
[00:34:59] của họ chấm
[00:35:01] ngoài ra nữa ngoài ra nữa mấy ông thấy
[00:35:04] nãy giờ nãy giờ nó có bị một cái khó
[00:35:07] chịu như này đây tôi cho mấy ông ví dụ
[00:35:10] lại
[00:35:11] ra sự là lại quay lại cái bên mail ạ
[00:35:15] thật sự mail này đang hoa@gmail.com này
[00:35:19] ờ
[00:35:21] ê ê ABC
[00:35:24] a a còng gmail.com
[00:35:28] ạ sau đó thì một loạt ký tự xay nha
[00:35:31] đó trước đấy là một lon ký tự sai ngay
[00:35:35] sau đó đi ờ
[00:35:39] Ô Long a còng chấm com
[00:35:47] chấm xz
[00:35:47] xong rồi một lát ý tự xanh ai tiếp chẳng
[00:35:50] hạn thế
[00:35:51] tôi đang cho mấy ông để mấy ông dễ hình
[00:35:54] dung nhé
[00:35:54] đề thi trường hợp nào đúng trường hợp
[00:35:58] duy nhất toàn đầu nó đúng những trường
[00:36:01] hợp sau mến miếu khi mà tetrapak mày
[00:36:04] không phải nhập nhiều trường hợp sai và
[00:36:06] nhiều trường hợp đúng ra nhá thì mày
[00:36:07] không test nhé để cách để công cốt ghi
[00:36:10] khách mời ông không ngờ nghĩ là mình cốc
[00:36:12] luôn Chạy mình chỉ khi mỗi trường hợp
[00:36:14] đúng lo nhé ấy trường hợp Đúng là khi mà
[00:36:18] mình trong chuỗi người dùng nhập email
[00:36:20] đấy nó chỉ có tồn tại Email thôi nó
[00:36:23] không được nhập thêm bất kỳ các kí tự
[00:36:25] đặc biệt hay vân vân thậm chí nó chỉ cần
[00:36:27] nhập đúng cách từ đây tính sai rồi chán
[00:36:29] thế đúng không ạ đây khi mình cần mình
[00:36:34] cần bắt được những cái trường hợp đúng
[00:36:36] và loại bỏ những trường hợp sai như thế
[00:36:38] này như thế nào rõ là mấy ông bảo là nó
[00:36:41] có chữ nó có a còng nó có tên miền đây
[00:36:45] đây cũng tính có những gì ấy ngoài ra nó
[00:36:48] còn thừa những cái thứ khác nữa đúng ạ
[00:36:50] thì nó thành trường nào sai Ừ thì bây
[00:36:52] giờ đầu tiên để bắt trường hợp đúng đã
[00:36:54] thì mình sẽ ra từ a đến z nó ngoác ạ
[00:36:57] ạ sau đó nó dấu cộng gì à đúng ạ là sửa
[00:37:00] đây có thiên số đi thì mình sẽ là từ 0
[00:37:04] đến 9 ạ không đến chí này Bắt được rồi
[00:37:06] này a còng này đúng không ạ sống vậy anh
[00:37:10] nhỉ Rét này
[00:37:12] rồi cậu này sau đó thì Dấu chấm này cho
[00:37:17] lại từ A Z vô lại cậu khô có vẻ chuẩn
[00:37:21] rồi có vẻ thôi các bạn thấy là đằng sau
[00:37:25] này nó lại đang có một loạt ký tự mình
[00:37:28] muốn loại những cái những cái này nó sẽ
[00:37:30] bỏ lỗi những cái thằng sau này thì mình
[00:37:33] làm nha Bây giờ mới ông sẽ biết thêm
[00:37:35] được phải khái niệm nữa đó là dấu ngoặc
[00:37:38] à dấu mũ này để bắt đầu
[00:37:43] Trỗi
[00:37:45] nghĩa là mấy ông để ý thấy là cái Long
[00:37:49] này cái trường hợp 3 và 4 này nó bị sai
[00:37:53] điểm là bắt đầu chỗ ấy Nó không phải là
[00:37:55] là những thứ mà mình cần đúng ạ thì mình
[00:38:00] sẽ có thêm vào đây thì sẽ là giàu như
[00:38:03] thế này đó thì mấy ông sẽ thấy là bắt
[00:38:06] đầu chuỗi mỗi dòng của tôi là một chỗ
[00:38:08] nhá ngày hôm nay Hình dung là tôi đang
[00:38:09] kiểm tra từng dòng Từng dòng này tách
[00:38:12] điện nhau dòng này có thể đúng không có
[00:38:14] nghĩa dòng dưới nó nó đúng nó không ạ Nó
[00:38:18] độc lập nhau đúng không ạ Đấy thì cái
[00:38:21] dùng cái này để bắt đầu chuỗi cái chỗ
[00:38:24] này thì nó vẫn đang đúng này Chỗ này vẫn
[00:38:26] đúng rồi nó bắt đầu vào nha cọ bắt đầu
[00:38:29] Thịnh bằng Email núm còn chuỗi này thì
[00:38:33] nó sai rồi bởi vì a email đó nằm ở giữa
[00:38:35] đúng ạ email này nằm ở cuối nó sai không
[00:38:39] ạ Nhưng mà thế này vẫn chưa đủ đúng
[00:38:41] không ạ Nếu không thấy à Cái Email của
[00:38:43] mình nó bắt đầu thì cứ về đúng rồi nhưng
[00:38:46] đằng sau nó ký tự sau đó ông ạ Bây giờ
[00:38:49] mình biết thêm về nữa đó là độ La thì đó
[00:38:54] là kết thúc Trỗi I ý nghĩa bắt buộc mà
[00:38:58] phải có cuối nữa đúng ạ Mình sẽ thêm cái
[00:39:02] này ở cuối
[00:39:03] đó thì mới Ông thấy à trong trường hợp
[00:39:06] này thì chỉ có mỗi cái này nó hợp lại
[00:39:09] thôi còn những cái này thì nó sẽ bị loại
[00:39:11] bỏ chúng vọng Nếu mấy ông kết hợp cả cái
[00:39:14] dấu này và cả dấu này nữa thì là ổn nhất
[00:39:18] đó là ăn chia tôi thường hay nói cái câu
[00:39:21] nó từ đầu đến cuối nó sẽ chỉ khớp với
[00:39:24] những cái mà mình nhập theo gạch thôi
[00:39:26] thì ở chuẩn không ạ những cái mà nhập
[00:39:29] ngoài gạch thì nó sẽ bị lỗi xóa đoạn này
[00:39:33] đi nó nhận không ạ thêm một dấu cắt thôi
[00:39:35] cái nó lỗi đúng không ạ Đấy thì đây đây
[00:39:39] là đầy đủ có tương đối đầy đủ của cái cơ
[00:39:42] bản của khách cũng đúng 10 dòng không ạ
[00:39:45] khá ổn xã hội
[00:39:53] Ê mấy ông thấy nãy giờ cũng không đến
[00:39:53] nỗi đau não làm đúng ạ Không nói đầu lọ
[00:39:55] nào lắm Ừ Tôi sẽ chỉ cho ông thêm mấy
[00:39:58] cái tắt hơn ờ ờ
[00:40:01] mì cái tắt hơn một tí giống như là nãy
[00:40:05] của ông nói về cái vụ lại tê thì nó sẽ
[00:40:08] là thay cho một đoạn Tát hay cấp thử mấy
[00:40:12] ông cha biết qua rồi Nếu mà còn w ngay
[00:40:15] cơ
[00:40:15] w như thế này thì nó sẽ là
[00:40:19] nó là nó là chủ ấy vừa từ a đến z vừa là
[00:40:24] từ a đến z như thế này và vừa từ 0 đến 9
[00:40:28] như thế này nó khá phù hợp cho việc làm
[00:40:31] mấy ông muốn bắt thay vì mấy ông nhập
[00:40:34] giữa dài như thế này nếu không đổi nó
[00:40:36] thành như thế này thôi là được Nếu không
[00:40:41] sẽ truyện ngắn hơn
[00:40:43] hai a thì vừa nãy mình có nói là cái
[00:40:46] doman này cũng thể có số giáo sư tử mà
[00:40:48] đúng ạ thì người ông đổi hết nó thành
[00:40:51] như này là xong à
[00:40:57] Em có biết Hoa được nhỉ Mình nhớ là có
[00:40:57] đúng không có Và trong hai cách để có
[00:41:01] cái nó cũng tiện hơn một tí nó là nếu mà
[00:41:04] ông viết nó thành viết hoa hay tưởng như
[00:41:06] thế này thì không phải lắm chỉ nó chỉ
[00:41:09] lấy từ a đến z như thế này đó ạ Nó không
[00:41:11] phải lấy từ a đến z như thế này đâu
[00:41:14] và thứ ba là mấy ông cũng đừng nghĩ
[00:41:17] trường hợp và có thể biết theo cậu a nhỏ
[00:41:20] đến z lớn cái này nó sẽ dậy từ A Z cả
[00:41:24] nhỏ và lớn nhé Không tôi từng thử cái
[00:41:26] này không được đều ngoại anh sẽ biết
[00:41:28] cách riêng cái việc tiết hoa như này nó
[00:41:31] là ngược lại với tất cả Đồng Nai ngược
[00:41:34] lại tất cả Đồng Nai tất cả xa nó sẽ ghi
[00:41:36] theo cậu dạng là anh như thế này tớ là
[00:41:39] Ngược lại nếu mà cái ngọt vua ngừa kết
[00:41:42] hợp với cái dấu dấu mũ như này thì nó
[00:41:46] hiểu là ngược lại tất cả những thứ trong
[00:41:47] mặc vua nhé Đấy và ngược lại tất cả đống
[00:41:51] này tức là sao làm mọi thứ tự khác không
[00:41:54] nằm trong cái phạm vi hai thôi Đúng mặt
[00:41:55] mọi thứ tự giống như là kiểu Ả cong số
[00:41:58] 10 như này không ạ chỉ nó cái gì đó nữa
[00:42:02] rất nhiều dấu cách mà ông Tính
[00:42:06] anh
[00:42:07] không ạ Đấy Và nếu mà Mấy ông chỉ muốn à
[00:42:11] số từ 0 đến 9 thôi thì nó sẽ là
[00:42:15] như thế này không đến 99 để ngoạn và
[00:42:22] đương nhiên ngược lại với nó như này thì
[00:42:25] nó sẽ là
[00:42:26] mọi thứ mọi thứ không nằm trong phạm vi
[00:42:29] từ 0 đến 9 thì nó sẽ lấy
[00:42:36] tôi cái dấu
[00:42:36] không đến chính nó sẽ lấy ba giống như
[00:42:40] cái cuối nữa như vừa nãy Các bạn nhớ cái
[00:42:43] dấu chấm nó thay thế cho nó bằng mọi thứ
[00:42:47] tự chống lại mọi thứ tự ở đây cả số cả
[00:42:50] chữ cá sấu cách nói cho mọi thứ không ạ
[00:42:54] ạ
[00:42:55] ở đó tương đối tượng Đối cũng nhớ phết
[00:43:00] ông ạ
[00:43:02] Ừ thôi sẽ chia sẻ cho mấy ông hai cái
[00:43:05] đường link này để nó học thêm thì ghét
[00:43:08] tôi có lưu có có để sẵn ở trên này luôn
[00:43:11] rồi này tôi thì tôi tôi tí thôi sẽ bình
[00:43:14] luận cả cái đoạn này kết hợp với hai cái
[00:43:17] này để người Ông đọc qua hai cái này nó
[00:43:19] còn nói thêm thêm một vài cái ví dụ nữa
[00:43:23] ờ ờ
[00:43:25] có thêm một vài cái ví dụ nữa Rất là hay
[00:43:27] đây có một đoạn tương đối đầy đủ Mày
[00:43:30] không cần nhớ này ạ
[00:43:32] ạ Và bây giờ để tránh dài làm hơn bây
[00:43:35] giờ áp dụng bài tập lý thuyết nãy giờ
[00:43:37] nhiều quá thế là sự áp dụng bài tập bây
[00:43:39] giờ tôi sẽ dậy người ông từ cái cơ bản
[00:43:41] nhất mà tôi thường dậy sinh viên Đó là
[00:43:44] thì mình sẽ dùng gạch để mà kiểm tra số
[00:43:49] điện
[00:43:50] Ờ thì đầu tiên ở đây số điện thoại thì
[00:43:53] nó thường hay
[00:43:55] thường Bây giờ giả sử số điện thoại giờ
[00:43:58] làm Mấy mô số rằng ạ người nên muốn sống
[00:44:01] nhé
[00:44:02] số 10 Nguyễn Tôi cũng chả nhớ nữa cứ cho
[00:44:05] là sự có hỗ trợ luôn cảm nhận 10 số và
[00:44:08] 11 số đi là xử thế không ạ thì à
[00:44:14] anh cái số điện thoại thì mình sẽ yêu
[00:44:17] cầu nó chị chỉ Nhật
[00:44:19] xe chính chủ nhật mà nó là số không bằng
[00:44:22] đầu hay gì gì đó xong rồi đằng sau bằng
[00:44:26] ban đầu nó bắt buộc phải số Không em ạ
[00:44:28] sôi đằng sau nó không được không được là
[00:44:30] số 0 Để hạn Vân Vân Vân thì sao ta sử
[00:44:34] mình hỗ trợ cho toàn nhập 11 số luôn đi
[00:44:37] cho nó khó
[00:44:39] đầu tiên tôi nhập một số hợp lệ đã này
[00:44:43] là sự đây một số lệnh số này thôi Chẳng
[00:44:46] biết nó ba số nữa Hình như là 10 số này
[00:44:48] đấy
[00:44:51] ở đây là 10 số thì phải ạ
[00:44:54] em bỏ qua vụ 84 đi nhé mà Mấy ông Muốn
[00:44:58] làm cộng tám tư thì đấy sẽ ra câu sau
[00:45:01] cho bé Ông tôi đang dạy cơ bản
[00:45:07] Ừ không sao Cái gì về sau thuốc chữa hết
[00:45:07] cho béo mấy không phải lo mà ông cứ thắc
[00:45:10] mắc gì tôi sẽ giải đáp cho đây đây rồi
[00:45:12] Cứ giả sử đây một số đúng không ạ nhưng
[00:45:15] một số sai nó sẽ như thế nào không không
[00:45:17] không như ai cũng có một số sai đúng ạ
[00:45:19] tớ bỏ qua vụ nhập chữ nhá Tí mình chắc
[00:45:23] chắn mình không cho nhập chữ rồi
[00:45:28] Không nhưng lại có một số Sai rồi Không
[00:45:29] ạ Mấy ông cứ bát hết các trường hợp sai
[00:45:31] đi trở lại
[00:45:33] ờ ờ con trường hợp chị nha
[00:45:43] a123 nghe đây là mình Đây là những
[00:45:43] chuyện đó sau trừ nhập đúng nó sẽ nghe
[00:45:46] tạm thời Tôi chưa nghĩ được thì em
[00:45:48] trường hợp sai được
[00:45:50] cho sự thêm hạn như này không không nhỉ
[00:45:53] À đây cũng trường có sai rồi chồng ạ
[00:46:01] thì à còn trường hợp sai nữa
[00:46:01] thôi chỉ cần đổi cái này thành không
[00:46:05] nghe thì ông thấy nó đủ độ dài nhưng mà
[00:46:09] tự nhiên số là người sau số còn lại số 0
[00:46:12] thì nó càng sai không ạ đó
[00:46:16] Ừ thì mấy ông cầm đầu tiên là như tôi
[00:46:20] thường à
[00:46:23] anh như tôi vừa ấy nói nó là nên có số
[00:46:27] không được đâu đây số không bằng đầu Ok
[00:46:29] không ạ sau đó thì là một loạt số nhưng
[00:46:34] không có số 0 đằng động đối ngoại thì
[00:46:38] mình sẽ là một đến chí chuẩn chọn đó
[00:46:43] Ừ Để cho để cho mấy ông biết được là
[00:46:46] mình là đúng hay sai mình sẽ cho ngay
[00:46:48] như thế này Trước đó thì mình sẽ thấy nó
[00:46:52] bắt
[00:46:53] 0101 ok rồi ông ạ đó nó sẽ bỏ qua thằng
[00:46:57] này luôn này nhưng mà sau đó lại sổ tiếp
[00:47:00] ngay không ạ mì ông trong số đằng sau
[00:47:04] này mình hoàn toàn nó có thể để số 02
[00:47:07] không ạ chúng sau này có thể để số 0 2 0
[00:47:10] ra sư có gọi cho phép bằng sau nó có thể
[00:47:14] anh có thể để số không đi
[00:47:20] anh hả
[00:47:20] 200 gọi liên tỉnh
[00:47:27] em
[00:47:27] bỏ qua đi bộ qua vụ là tôi tôi đã bắt
[00:47:31] trường hợp mà không có số 0 đằng sau đã
[00:47:34] còn nếu mấy ông Hỗ trợ nó thì càng ngon
[00:47:37] thôi
[00:47:39] ở
[00:47:40] đằng sau này có thể có số không chẳnghạn
[00:47:42] Thế thì mình sẽ là từ 0 đến 9 tiếp thôi
[00:47:45] ông ạ
[00:47:46] đó và đoạn này mình muốn cho lại từ đây
[00:47:51] trở đi thì mình nhập số gì cũng được vẫn
[00:47:54] được tính không ạ khi
[00:47:56] ở đây thì nó sẽ là
[00:48:01] số
[00:48:01] một này
[00:48:04] 2345678
[00:48:06] nghĩa làm chị là mình sẽ nhập đầy đủ 8
[00:48:09] số đằng sau
[00:48:11] đó nó sẽ như thế này
[00:48:15] và đương nhiên vừa nãy mình bảo là có
[00:48:17] thể hỗ trợ được cho cả 10 tháng 11 số
[00:48:19] thì mình sẽ làm chị lại nếu mà như thế
[00:48:23] này thì thành sai rồi ạ thì mình sẽ 8
[00:48:25] phẩy trí đó và như thế này nó sẽ hỗ trợ
[00:48:30] anh nhìn này và đương nhiên là bây giờ
[00:48:33] nếu là thêm sống xong ngay thì đang lại
[00:48:35] phải không thỏa mãn mà không ạ sự mình
[00:48:37] thêm số lần sau này lẽ không này không
[00:48:39] thỏa mãn thì mình sẽ có đô la đó
[00:48:44] ở đây đây là sẽ Black cơ bản các bạn
[00:48:47] thôi về số điện thoại Thế ông vừa bảo là
[00:48:50] thêm cộng tám tư cái gì đấy Nó nhọn thì
[00:48:53] đổi không Này cộng 84 được gì không ạ
[00:48:55] thì mình sẽ nếu mà trong trường hợp và
[00:48:58] mấy ông muốn đổi cái một chuỗi ký tự với
[00:49:03] một chuỗi ký tự kiểu như thế thì nó sẽ
[00:49:06] là thì cho nó vào mặt tròn như này rồi
[00:49:08] kết hợp với cái dấu thăm á dấu à Chỗ Cho
[00:49:13] biết bên cạnh gạch thẳng như thế này về
[00:49:15] hiểu là một về bên trái hay bên phải là
[00:49:18] sự đây A và DZ giống như vậy tôi là
[00:49:22] à à
[00:49:24] Ừ nếu mà nếu mà ghi kiểu nhảy thời gian
[00:49:27] mình có thể hiểu được là một loại A2 là
[00:49:30] Z ngay luôn Nhưng nếu giờ sự mình đi một
[00:49:33] đoạn nó nó dài hơn như thế này
[00:49:35] như này chẳng hạn à à lái xe đi khi mấy
[00:49:41] ông lại khó ghi theo kiểu vuông ngay
[00:49:43] đúng không ạ thì cách để mình hiểu cái
[00:49:46] này thì nó sẽ là à AB hoặc DC đó ông ạ
[00:49:50] đúng ạ thì thì đầy đầy cái gì đúng
[00:49:57] cái cách này có thể ghi ngắn nhưng riêng
[00:50:00] cách này thì không nên nhắn được mình sẽ
[00:50:01] về đi mình sẽ hiểu Nó là những này thôi
[00:50:04] đấy
[00:50:06] thì nó sẽ ở đây cũng thế là sử thay dù
[00:50:10] số không thành cái cộng 84 thì nó sẽ là
[00:50:13] đôi cái này thành hoặc như thế này cộng
[00:50:17] 84 đúng không ạ
[00:50:20] đó và ở đây nhiều ở đây nó đang cảnh báo
[00:50:25] lỗi bởi vì cậu ở đây nó hiểu kí tự đặc
[00:50:27] biệt thì mình thêm xấu như này đó thì
[00:50:30] mới Ông thấy À cái màu ở đây Nếu được
[00:50:33] nghỉ màu đấy nhá màu đây nó ở đây mấy
[00:50:36] ông sẽ để nếu cho mặt tròn ngay đôi khi
[00:50:39] nó sẽ tạo thêm cái gọi rốt nữa nó sẽ tạo
[00:50:43] màu nó chứ nó không nghĩ ám chỉ là nó
[00:50:45] tạo thành cái thằng cái thằng trong mặt
[00:50:48] tròn nó sẽ biến thành một cái giúp g một
[00:50:50] cái nhóm riêng chứ nó không phải là lỗi
[00:50:52] và nó cũng không ảnh hưởng gì cả vì em
[00:50:55] chuyển mát của mình vẫn mát để cho nó
[00:50:57] vẫn khớp có nếu mà giờ xử ông không muốn
[00:51:00] có cái giúp này được tạo ra
[00:51:03] Anh không muốn cái lúc này đã tạo ra
[00:51:04] chẳng qua cái này cốt là để mà muốn phân
[00:51:07] biệt kế hàng cộng 84 ta sử dụng trường
[00:51:09] hợp này tôi đổi không Đảng cộng 84 này
[00:51:12] vẫn chạy này không ạ ra xử ông không
[00:51:15] muốn có cái có cái này thì chị ra tôi
[00:51:18] tôi bị cầu toàn nên tôi nhìn thấy cái
[00:51:20] thì thị ra nghe tôi không trục khi nếu
[00:51:22] có thể thêm cái ký tự nó là hỏi chấm 2
[00:51:25] chấm nhớ anh thì nó sẽ hiểu là cánh cái
[00:51:29] mặc kệ ngọt trò này nó không tạo thêm
[00:51:33] một cái gốc là nữa
[00:51:34] điều hòa thế thôi
[00:51:37] thế là tôi nói quà cho những cái ông mà
[00:51:40] cậu Toàn như tôi nhìn nó đỡ ngứa mắt nở
[00:51:43] ra nó không anh hưởng gì cái lôgic và nó
[00:51:45] không bị lỗi cốt bởi vì bản chất là nó
[00:51:48] đã khớp cái mắt rồi ông ạ ạ
[00:51:52] Ừ ok đấy mẹ ông thắc mắc về cụm từ bây
[00:51:55] giờ đáp cho ông luôn đấy lại thế Hết câu
[00:51:59] xa cho mày không người ở
[00:52:02] a tiếp theo thì vẫn có thời gian không ạ
[00:52:05] Mình sẽ chữa dần những cái cái bài khó
[00:52:10] hơn Ừ cái này vừa rồi mấy mấy ông hiểu
[00:52:13] cái này chưa ạ Mày không hiểu cái tôi
[00:52:15] vừa làm về cái số điện thoại bọn
[00:52:19] tôi tạm chưa Gửi cho mấy ông cái cốt này
[00:52:23] đâu để cuối khóa học về cách này ra để
[00:52:27] buổi sau nữa đi thì tôi sẽ gửi cho cả
[00:52:29] whey với cả họ tên của tôi tôi làm cái
[00:52:32] quả mà họ tên có dấu ở như thế nào ạ
[00:52:40] anh béo hiểu đúng không Ok mày không còn
[00:52:40] Tự nhận mày không hiểu nhé Để tớ sẽ nhảy
[00:52:42] sang cái khó hơn này vợ tôi sẽ thử làm
[00:52:46] rách với tuổi đi tuổi tuổi thì ta xử
[00:52:51] được phép nhập Tôi thường ngoài chẳng ở
[00:52:52] trong cái ở trên nhật tuổi cả nếu mà giả
[00:52:54] sử được phép nhập tuổi thì mấy ông nhập
[00:52:57] tuổi
[00:52:58] về giá sữa tuổi hiện tại bao nhiêu tuổi
[00:53:00] người đang sống ngoài tuổi đã mất rồi
[00:53:02] thì tuổi người đang sống nhưng giờ sự
[00:53:04] làm mấy ông chỉ được phép nhập tôi sẽ
[00:53:07] ghi điều kiện của đề bài là nha
[00:53:09] nhập tuổi
[00:53:11] hiện tại của bạn
[00:53:17] không chơi mày ông ngoài ba mang gọi
[00:53:17] rồng hà ra dưới nhé đấy thì tuổi của mấy
[00:53:20] ông thì đương nhiên là không có phải
[00:53:22] phải phải gì Chán thế mày ông bắt buộc
[00:53:25] phải nhập số nguyên em ạ Không ạ thì nếu
[00:53:28] tuổi nó sẽ không có số 0 là đầu đúng
[00:53:30] không ạ thì con sẽ nhập nó có những cái
[00:53:33] trường hợp có thể xảy ra ở đây thử
[00:53:36] nghiệm nhập số tuổi như thế này không ạ
[00:53:38] 12 tuổi 18 tuổi đúng ạ sau nhập số hai
[00:53:43] thằng đầu nó vẫn được đó ngoại sự hay
[00:53:45] mốt 25 gì đó nhập 100 cũng được dọn ra
[00:53:50] sử cho tôi chị cho ông Bởi vì người dài
[00:53:54] nhất Bây giờ hình như nó chưa lên nên
[00:53:56] nổi hơn 200 tuổi nhưng tôi chỉ cho ông
[00:53:58] nhập một có số 100 đang đầu là à với với
[00:54:05] 3 số thì sẽ chỉ được nói chung nhà tuổi
[00:54:10] của ông sẽ phải bé hơn 200 ạ đến 200
[00:54:13] tượng bé ông Cùng lắm nhập được 199 thôi
[00:54:15] không thấy phép nhập 200 đối ngoại ô
[00:54:20] Ừ thì mấy ông sẽ làm như thế nào
[00:54:23] á nhon
[00:54:29] A và đưa nghe có thể nhập cả số tuổi
[00:54:29] kiểu 80 được nhập số 0 nhé Không mẹ nói
[00:54:33] tôi không Tôi luôn nhé là sự 89 Cái gì
[00:54:36] đó nghĩa là như thế này không Tôi bảo
[00:54:39] rồi không có nhập số 0 lần đầu ngay
[00:54:41] không cho nhập đều ạ
[00:54:44] Cho sẽ copy giai đoạn này
[00:54:54] bạn ra đây Nhập tôi không ạ thì cái giải
[00:54:54] quyết bài toán ở đây thì khi mà Làm lập
[00:54:58] trình các bạn phải chia các trường hợp
[00:54:59] ra các bạn không thể ghi ngay một phát
[00:55:03] freegate ăn ngay chắc lại xuống hợp cách
[00:55:06] để chia trường hợp của tôi xuống ấy là
[00:55:07] đó là tắt cái này ra thành nhiều trường
[00:55:10] hợp Ê mấy ông Để ý kỹ ở đây cho da bạn
[00:55:13] chất ở đây có 3 trường hợp thôi ba
[00:55:15] trường hợp với Đây là gì trường hợp 1 là
[00:55:17] nó có một ký tự trường hợp hai nó có hai
[00:55:19] thứ tự là ba là 3 ký tự đấy Đấy là cách
[00:55:23] của tôi chưa chụp tôi đã xử lý nó như
[00:55:25] sau tôi sẽ tách cả ngày ra làm 3 tát tôi
[00:55:28] sẽ tạo đã ký kết 38 ngày mà tôi giveback
[00:55:32] từng cái tát một rồi Tôi ghét mà nó vào
[00:55:34] với nhau đến mấy ông hiểu nó hiểu đấy
[00:55:37] giờ tôi muốn nói em ạ lại tôi sẽ tạo đầy
[00:55:40] 38 o
[00:55:42] Ừ thế này ổn nhất này Đấy và trường hợp
[00:55:46] một số trước đi một số thì mình chỉ là
[00:55:49] đơn giản đó là trong phạm vi từ 1 đến
[00:55:52] chí ra sóng của dễ gãy
[00:55:54] ở đại và mình thêm thế này để chắc chắn
[00:55:58] nó là một số
[00:55:59] Anh ăn rồi mình số 0 Nhưng lại không
[00:56:03] không hợp lệ đúng ạ số 5 nhãn hợp đấy
[00:56:07] ông ạ MT sao được
[00:56:10] anh không trường nào mẹ anh đi được cái
[00:56:13] này bắt buộc phải nhập một ký tự mà
[00:56:14] không ạ Đó ok không ạ xong trường có mối
[00:56:18] rồi dễ như trò đùa trường hợp thứ hai là
[00:56:21] thị trường hợp thứ 2 thì nó 2 số đúng
[00:56:24] không ạ hai số thì mình cần là
[00:56:32] Ừ ông kia chơi chưa
[00:56:32] anh không cốt của ông kia nhìn thấy chưa
[00:56:34] tối ưu rồi để tôi làm cho mình xem à ở
[00:56:38] trường hợp thứ hai là gì nó hai số và số
[00:56:43] đầu của nó là từ 1 đến 9 từ 1 đến 9 bởi
[00:56:47] vì như tôi đã nói tôi không cho phép
[00:56:49] nhập số 0 như này thì lúc đầu nó sẽ từ 1
[00:56:52] đến 9
[00:56:53] và sau đó là tử không trí
[00:56:56] buổi đơn giản
[00:56:59] Có lẽ thế này mà cũng đố đúng ạ
[00:57:03] Tại vì này ok chưa ạ
[00:57:06] Cái 080 thỏa mãn nó không không chắc
[00:57:11] chắn không thỏa mãn nổi không ạ Người Ấy
[00:57:13] thỏa mãn ok rồi thế đồ vào nó ạ
[00:57:16] 999 đó đưa đó không ạ Bây giờ trường hợp
[00:57:20] thứ ba nó là gì trường hợp thứ ba nó là
[00:57:23] bắt Nếu mà cho nhập 200 nữa ạ hãy hãy
[00:57:27] tưởng chỉ 300 em ạ Chị 350
[00:57:30] 355 hay gì đó nó vẫn không thỏa mãn
[00:57:33] không ạ thế làm chỉ là số 1 lúc đầu có
[00:57:36] này số 1 bắt đầu nó số một này cho chắc
[00:57:40] cụ này đó sau đó là gì không đến 9 thôi
[00:57:45] không mình chín ở đây không Mình chín
[00:57:47] đây hai phát một làm mấy ông yêu cậu làm
[00:57:50] lại như này theo kiểu nếu bị rảnh hay là
[00:57:54] mấy ông có thể viết tắt viết theo kiểu
[00:57:56] ngay cho nó bắt buộc là phải hai ký tự Ừ
[00:57:58] đúng
[00:58:00] Ừ để ra sự thu nhập số 10 Nga trong mấy
[00:58:03] ông biết là nó có thể xay nha ông ạ
[00:58:05] và mấy ông có thể làm ngắn hơn sống
[00:58:08] nhưng tôi bảo thì nó sẽ là bên này Đây
[00:58:11] là sai không chỉ mà các bạn Nếu bạn đó
[00:58:14] thì kiểu này nó sẽ ngắn hơn tí không ạ
[00:58:16] Nói nhiên cái này bắt buộc nó phải có
[00:58:19] cuối đi phòng nó 1000 cái gì đó nó không
[00:58:24] bị lỗi
[00:58:29] kết hợp cả ba cái này với nhau thì sẽ là
[00:58:29] như thế nào
[00:58:30] Ừ tôi sẽ đắp I kết một cái Tab nữa rồi
[00:58:34] tôi nhét cả ba cái bạn cho mình không xe
[00:58:41] em copy này à
[00:58:41] à à
[00:58:43] ảnh copy nó sẽ dùng dầu hoặc này copy
[00:58:47] này
[00:58:48] à Xong rồi lại
[00:58:51] hoặc copy ở anh có ghé xong OK Ngon thế
[00:58:58] Xong rồi nhưng cái này chưa đủ tối ưu
[00:59:00] cái này chưa đủ Tôi yêu
[00:59:08] Ờ chưa tối ưu chỗ nào mấy ông thấy có
[00:59:08] nhiều cá nó bị lặp lại và cách để tối ưu
[00:59:11] của tôi đó là như thế này tôi sẽ rút gọn
[00:59:13] đi hai cái này lặp lại đúng không ạ Nó
[00:59:16] khác nhau điểm gì khác nhau điểm là cái
[00:59:18] này đằng sau đúng nghĩa tức là hai này
[00:59:21] thì chụp lại theo kiểu Cái này có hoặc
[00:59:23] không có cũng được không ạ là sẽ gộp lại
[00:59:27] hai cái này cho mấy ông xe à
[00:59:31] Anh ở Xóa cái trường hợp một này đi Này
[00:59:33] tốc độ này có không có cũng được đấy đó
[00:59:37] đấy số 8 ông ạ
[00:59:44] ờ ờ
[00:59:44] Ê mấy ông vào vào tầm giờ này thì tự
[00:59:48] nhiên mày cũng khó hiểu đúng rồi cuối
[00:59:49] giờ mà đi tua lại video đi tiếp theo
[00:59:53] ờ ờ
[00:59:54] thế ông cũng thành chụp lại này để tôi
[00:59:57] biết lại cái này cho mấy ông nhìn nó
[01:00:00] tiện nhé không đến chí này vào đây cũng
[01:00:03] à
[01:00:10] không đến chí này ạ
[01:00:10] à À không không nên chí này thì mày
[01:00:13] không thấy à
[01:00:15] Ừ cái này nó giống nhau ở mỗi điểm hai
[01:00:19] cái này không đến 9 là thường là tôi
[01:00:22] tách thằng này ra đấy tôi không ngô Còn
[01:00:24] lâu cho đỡ nhìn nó mắt mấy ông muốn gộp
[01:00:27] lại Thực ra nó cũng phức tạp ra như tôi
[01:00:29] tôi không có hai thằng ngày với nhau
[01:00:32] thế nhưng tôi có thể nộp cái dấu ký tự
[01:00:35] này với nhau được
[01:00:37] cái dấu ký tự này nó sẽ là tôi sẽ gộp
[01:00:40] vào nghe thì xóa đi này Ừ thôi đổ cái
[01:00:42] này thành tròn như thế này
[01:00:46] chú
[01:00:46] chó nếu không sẽ thấy nó như thế này à
[01:00:51] À cái Ngó trò này nó sẽ méo nhớ bạn nó
[01:00:54] trò này nó sẽ để hiểu các cụ này nó sẽ
[01:00:57] được thừa hưởng cái dấu dấu đôla với dấu
[01:01:00] mũ như này đến hiểu từ đầu đến cuối
[01:01:02] nhưng mấy ông thấy khó chịu việc làm
[01:01:05] hoặc tròn nó tạo thêm cái súp nữa thì
[01:01:07] méo Có thể thêm hỏi chấm 2 chấm nó sẽ
[01:01:11] sau đúng ạ thì mày Ông thấy đầy đủ Nó là
[01:01:15] kiểu rút gọn nó có thể đến như thế này
[01:01:18] đây về kiểm tra về tuổi theo phạm vi là
[01:01:21] tuổi từ ở tuổi của tôi nó sẽ là từ 1 cho
[01:01:25] đến 1999 Đông ạ vào số nguyên ok
[01:01:35] Ê mấy ông đến đoạn Hiếu
[01:01:35] anh tặng đâu Đông não chưa
[01:01:39] 3 bài tập của tôi sẽ yêu cầu làm lại mấy
[01:01:42] cái này đấy à
[01:01:48] Em
[01:01:48] không hiểu
[01:02:06] Ừ cái này kiến thức mới mấy ông mà hiểu
[01:02:06] được cái mấy ông thành siêu nhân quá à à
[01:02:08] à Nếu như thầy tôi từ ngày bảo đó là
[01:02:12] thôi mấy ông lại điều khiển thế nào được
[01:02:15] về xem lại đi Cái thứ thử
[01:02:19] địa chỉ ở cá nó lại dễ địa chỉ nó bản
[01:02:22] chất nó là số kết hợp với chuỗi chuỗi
[01:02:25] chữ lòng giao thôi
[01:02:26] thôi sẽ dạy cho ông ấy không ngại tiếp
[01:02:29] để nếu mình dùng rõ rồi mấy cái này đó
[01:02:31] là
[01:02:32] Ừ
[01:02:33] ông kia còn thích viết tắt nữa Thôi đừng
[01:02:37] ham đi tắm nữa thôi
[01:02:40] Dù thế nào vẫn có thể đi tắt được như
[01:02:42] ông kia bảo
[01:02:54] đề nghị ông kia làm như có thể sẽ sai
[01:02:54] bởi vì cái này 1 đến 9 giờ nếu mà ông
[01:02:57] trùng đến nhà ở dưới đê Nó không đúng
[01:03:00] đâu ạ ờ ờ
[01:03:07] ạ Bây giờ tôi sẽ chữa cho mày ông tiếp
[01:03:07] đó là về số
[01:03:11] em vẫn làm vé số đi nhà số lần này số đi
[01:03:14] số điểm của tôi nó như thế này tôi sẽ có
[01:03:17] đề bài nhá
[01:03:19] điểm
[01:03:21] từ phạm vi từ ngủ với mưa à từ 0 đến 10
[01:03:26] chứ và
[01:03:29] số thợ có thể là số thập phân
[01:03:33] và sau dấu phẩy
[01:03:43] có tối đa 2 số
[01:03:43] có trường hợp thì những trường hợp gì
[01:03:46] xảy ra ở đây nhất là số không thích sẵn
[01:03:48] rồi đúng không ạ Có chưa một số 10 sẽ
[01:03:51] sẵn rồi ngoại à từ
[01:03:55] 0,5 cũng đúng 0,25 cũng đúng không ạ
[01:04:00] 5,25 phải 5,75 đúng không ạ
[01:04:05] 55 5,0 nữa hàng sai đúng tôi sẽ cho
[01:04:10] trường hợp này sai nhé rồi cho trường
[01:04:12] rồi mẹ sai
[01:04:14] những trường nào sai đi
[01:04:16] ờ ờ
[01:04:17] À sau dấu phẩy
[01:04:20] Ở đây có thể dấu phẩy hình số chấm được
[01:04:23] là sự tôi cho à
[01:04:25] cách nhau bởi phẩy hoặc chấm chả thế
[01:04:32] tôi quen Dạo này quen dùng chấm ở giữa
[01:04:35] rồi quen làm việc bên nước ngoài nó rung
[01:04:37] chấm
[01:04:39] sai thì nó sẽ là 3,3 dùng như bạn cái
[01:04:42] bảo đi đúng ạ
[01:04:45] 3,03 thì đúng không ạ đây Thôi cho
[01:04:48] trường hợp này đúng anh trên này thường
[01:04:50] ấy tôi cách như thế này cho các bạn biết
[01:04:52] trường hợp sai có ai tôi gõ hẳn bên này
[01:04:55] đi Đấy Chụp sai nữa là gì nó là 10
[01:05:00] 31
[01:05:03] 10,5 ạ
[01:05:06] em bỏ qua việc âm nhé Mình không cho
[01:05:08] nhập âm nó nó sẽ không sinh ra được
[01:05:15] đúng rồi
[01:05:15] 3,30 nữa đó đây những trường hợp sai
[01:05:19] đúng không ạ
[01:05:27] à Không để bày lần này chuẩn đối không
[01:05:27] xa Tôi Thuộc cái đề bài rồi tôi dậy sinh
[01:05:31] viên
[01:05:32] Ừ Ok mấy ông dụng nói chung mấy ông hình
[01:05:36] dung được cái vụ này chị ạ
[01:05:39] 300 bê không cần máy không phải nhập ký
[01:05:42] tự đặc biệt có dấu cách 2 ký tự hay là
[01:05:45] sổ chữ vào trong này đâu của vịt mình
[01:05:47] chỉ nhập số là không không có thể nhập
[01:05:49] ra được kí tự đặc biệt đâu
[01:05:52] ạ bây bây giờ để tôi hỏi mấy ông trước
[01:05:54] khi tôi bắt tay vào làm đấy Nó nhìn qua
[01:05:56] tất cả lúc này không ạ Nếu không thử nói
[01:05:59] cho tôi biết mấy ông sẽ chia nó thành
[01:06:01] mấy trường hợp
[01:06:03] anh ạ
[01:06:05] những mẹo sẽ chia nó thành mấy trường
[01:06:08] hợp để mấy ông lạc với ông càng chia
[01:06:12] chuẩn thì mấy ông càng làm Chuẩn từng
[01:06:15] trường hợp xuống ghét hết vào với nhau
[01:06:17] và sự rất ổn một tí tao còn rút gọn ra
[01:06:19] mấy ông ấy Ông nhìn cái đoạn rút gọn lại
[01:06:21] hoa mắt nha ạ
[01:06:23] ở Nhà Bè ở trước hết thì mày nói là tôi
[01:06:25] đi ạ mấy ông sẽ chia cái trường hợp này
[01:06:28] thành mấy trường nhà ở
[01:06:29] có hai trường hợp nếu nói cụ thể hơn để
[01:06:32] nhận tốt Nó là nếu không sẽ chơi trường
[01:06:34] hợp ah1 là gì trường hợp hay là gì nóng
[01:06:39] hôm nay giống như bạn kia nói trường hợp
[01:06:42] số nguyên này một số thập phân này hai
[01:06:44] số thập phân này Ok cũng được
[01:06:47] xe bốn chỗ ở 74 trường hợp nó gì
[01:06:50] em nói cụ thể hơn tí em ạ ạ
[01:07:15] i10 có phải và tròn thì nó giữa ba
[01:07:15] trường hợp đúng không
[01:07:27] du lịch thi AFF
[01:07:27] thứ năm tuần này tuần sau ngọn hai
[01:07:32] trường hợp số nguyên và số thập phân rồi
[01:07:33] thì đơn giản quá bơ để tôi trời ông nhé
[01:07:38] bốn trường hợp có cái này đúng không
[01:07:40] biết phải ông nghĩ dùm tôi không muốn
[01:07:42] trường hợp nó sẽ là à số 10 là một
[01:07:45] trường hợp số một số nguyên là một
[01:07:49] trường hợp à
[01:07:51] số có một số thập phân là một trường hợp
[01:07:54] và số có hai thập phân là hạn và một
[01:07:59] trường hợp nữa tổng cộng của 4 trường
[01:08:01] hợp lại sẽ tạo ra quy kết thành 4 Tab A
[01:08:08] ở
[01:08:08] trường hợp số 10 thì đơn giản đội nón số
[01:08:12] 10 không ạ Hết xăng rồi tí gì hết ạ tiếp
[01:08:17] trường hợp tiếp theo đó là một số nguyên
[01:08:20] nó thực ra cũng dễ thôi sao đơn giản dễ
[01:08:25] chơi dễ trúng kia ông ạ
[01:08:27] ở trường hợp nữa đương nhiên thì tôi bảo
[01:08:30] rồi tự nhiên phải kết hợp cả nhưng này
[01:08:32] như thế này nữa đúng không Nhưng mà thôi
[01:08:34] tí thì tính sau thì tính sao không ạ
[01:08:37] trường hợp này thì may ra nhìn Nếu đỡ
[01:08:39] rối thì mới ông thể làm ngay trước để
[01:08:41] cho chắc cú đi
[01:08:42] thì số 5 Này ổn không ạ Okay
[01:08:47] tiếp tục chưa mà khó hơn là
[01:08:56] chỉ có một số
[01:08:56] một số mọn tối xóa tôi xóa mấy trường ở
[01:09:00] máy đi nha
[01:09:01] À thôi Để đấy cũng được không sao không
[01:09:03] sao ạ
[01:09:05] ờ ờ một số thập phân thì bằng trước nó
[01:09:10] số nguyên từ 0 đến 9 đoạn loại bỏ số 10
[01:09:13] rồi em à đúng ngoại thì Chứ không đến 9
[01:09:15] thôi sau đó sẽ là dấu chấm em ạ Tí mấy
[01:09:19] ông hiện đổi dấu phẩy sao tính sau
[01:09:22] sau đó thì một số một số đơn giản thôi
[01:09:25] một số thì mình tự từ 1 đến 9 bởi vì như
[01:09:29] tôi đang làm thì nó sẽ là không có
[01:09:32] trường hợp
[01:09:38] bạn 5.0 ngay đó Bọn tôi không muốn cho
[01:09:38] trường hợp 5.0 này không ạ cái bắt đầu
[01:09:41] đầu hãy bắt đầu lần cuối này để bắt buộc
[01:09:44] toàn bộ phải đúng đi đó thì nó không
[01:09:47] phải nắm đúng nó ngọt dụ là
[01:09:56] 9,9 nó cũng đúng không ạ Và trường hợp
[01:09:56] tiếp theo nữa cuối cùng
[01:10:03] nó là trường hợp à
[01:10:03] à à
[01:10:05] em
[01:10:06] nộp nó là trường hợp
[01:10:09] ở một số số này có thể số không đúng
[01:10:13] không ạ sau đó là số từ 1 đến 9 ngoại
[01:10:15] thì nó sẽ là
[01:10:24] không này Không chín và sau đó là 1 đến
[01:10:24] 9
[01:10:26] đó thế là được không ạ
[01:10:29] khi bé là trường hợp hai số thập phân
[01:10:32] loại
[01:10:33] em mình kết hợp đi bây giờ mình sẽ kết
[01:10:36] hợp lại tất cả đấu này với nhau
[01:10:38] ở đại tôi sẽ copy
[01:10:41] ở bên này
[01:10:54] hoặc thêm phát nữa này copy này lại hoặc
[01:10:54] thêm phần nữa này đúng hết toàn bộ cái
[01:10:57] trên cái dưới này nó đang say vì thôi
[01:11:00] Không cho cái này
[01:11:09] đó đúng rồi đúng không ạ Thế sau thế này
[01:11:09] thì ra mấy ông làm này thì mấy ông có vẻ
[01:11:11] hạnh phúc Đi về đâu rồi thế điểm nó
[01:11:14] tương đối rồi con mếu muốn 10 mẫu muốn
[01:11:17] kiểu rút gọn lại tôi nhìn ngứa mắt không
[01:11:19] ạ ru họ những cái gì đầu tiên vừa nãy
[01:11:21] tôi bảo có thể rút gọn cho cậu lại rút
[01:11:24] gọn một cái chị cái cái ký tự này trước
[01:11:27] đã gì không ạ Chị sẽ gốc rút gọn mặt này
[01:11:31] và thôi đỡ Khó chịu gì tôi sẽ cho cái họ
[01:11:34] xem hai chấm trước được khó chịu ok có
[01:11:38] rút gọn được gì nữa không Mình có thể
[01:11:39] rút gọn được mấy cũng khi bị kỹ là đầu
[01:11:43] tiên là
[01:11:45] số bằng đầu nó đứng trước đang đầu theo
[01:11:47] ngày đầu lâu nó ngày và đang Thằng này
[01:11:49] nó luôn 090 ạ thì lắm chị ạ Mấy thằng
[01:11:53] này thứ là
[01:11:54] Ê thằng thằng Súng một số Nghiên này nó
[01:11:57] có thể là đằng sau nó có kí tự đặc biệt
[01:12:00] này hoặc không à Có cảm cái chỗ ấy đằng
[01:12:04] sau hoặc không có được Nếu nghe kỹ rồi
[01:12:06] nó nhé 8 chỉ là số nguyên
[01:12:11] số 5 Này có thể là có một chuỗi phẩy
[01:12:15] phẩy phẩy đằng sau và kèm với đó là một
[01:12:18] số gì đó hoặc không có cũng được thì rõ
[01:12:20] ràng cả cái cụ mày đó là hỏi chấm đúng
[01:12:24] không ạ nghĩa có không có cũng được thì
[01:12:27] tớ là sao thì xóa cái này để ý
[01:12:31] a cho các cụ mày
[01:12:40] ảnh có không có được đó mếu thấy nó sẽ
[01:12:40] nha nếu thêm hỏi chấm 2 chấm nữa thì nó
[01:12:43] sẽ loại bỏ đi
[01:12:45] ok không ạ
[01:12:47] Và tiếp theo đó nữa vậy ông thấy là hai
[01:12:50] thằng này nó khác gì nhau ạ Nó có còn
[01:12:53] thưởng cái hàng này ở giữa Thằng này
[01:12:55] không đấy Cái tội xóa luôn cả hai đi
[01:13:00] Ê bà đây nó cho thằng này chen ở giữa
[01:13:03] này không đến 9 giờ không ạ hỏi chấm này
[01:13:08] thế là xong ở đâu muốn rút gọn thân nữa
[01:13:12] tốn chữa tôi nghĩa thì ngưỡng ngày thôi
[01:13:15] Ừ
[01:13:16] ông vừa nãy ông làm bài trước ông thấy
[01:13:19] kết quả của ông giống thôi không không
[01:13:21] đúng không Thì ông sửa đi
[01:13:24] ừ Địt nếu cần Nếu mà chưa học gì mới học
[01:13:28] thì kế hoạch này không hiểu gì không Nếu
[01:13:30] mà tôi mà không làm từng bước từng bước
[01:13:33] nhỏ như thế Tôi gộp luôn nghe từ lúc đầu
[01:13:35] kiểu viết tắt nghe mấy đứa chẳng hiểu gì
[01:13:37] đúng không mày Ông nhìn cái đoạn này Thế
[01:13:40] nên sửa rách trong mấy ông công nhận là
[01:13:42] giữ khó trong nước phức tạp của bọn mình
[01:13:45] không thích Đấy lý do tôi bảo mấy cũng
[01:13:47] phải ghi hết các trường hợp sai ra nữa
[01:13:49] và làm từ từ thôi làm từ từ thôi xong
[01:13:53] rồi Chỗ rút gọn rút gọn dần thì nó như
[01:13:55] thế này thế này cái số 10 này thì bỏ qua
[01:13:59] đúng ạ mì ông tôi tôi sẽ cho mày ông xem
[01:14:03] lại cái vụ này thôi
[01:14:06] Ừ
[01:14:07] cái này nó là gì Cái này trước nó là một
[01:14:10] số gì đó đúng ạ
[01:14:13] Nó số gì đó số 0 mà số 5 là nó ngọn mời
[01:14:17] cả cái cụm lần sau nó là có không có
[01:14:19] được không ạ là sự 5,5 này thì được đúng
[01:14:22] ạ Đấy
[01:14:24] ôi cái đoạn này thậm chí ở hệ rút gọn
[01:14:27] được thêm này rồi chấm này có thể thay
[01:14:29] bằng giống như tôi nói là nó thể 5 phẩy
[01:14:32] 5,5 được thì bé ông ấy đổi nó thay nhà
[01:14:37] để nó trong mọc vuông nhé
[01:14:39] Vậy thế này
[01:14:42] khi để
[01:14:49] Ừ để nó để nó trong ngoặc vuông nhà thì
[01:14:49] nó hình như nó biến thành Chị ở ký tự
[01:14:52] Bình thường thôi nên là không lo gì lắm
[01:14:55] Ừ
[01:15:00] đúng rồi để nó trong mọc vuông này nó
[01:15:00] hiểu thì tự bình thường này ra mấy cũng
[01:15:02] để thi kiểu nhạc đấy à
[01:15:06] ở đằng sau nó có không có cũng được này
[01:15:09] và sau đó thì cái cái này có không có
[01:15:13] cũng được thành ra là sẽ không có trường
[01:15:16] hợp 5 phẩy
[01:15:17] A
[01:15:18] 5,50 ở đằng sau nhé Đúng không ạ
[01:15:23] ừ ừ
[01:15:24] em có đó cách mở gak và
[01:15:29] cậu rút gọn nó thì nó như thế nào
[01:15:35] anh cũng đau não được ạ tôi chữa chữa
[01:15:36] cho ông béo về cái họ tên đâu
[01:15:44] cách chữa nốt lại họ tên gồm mình nghỉ
[01:15:44] nha Hay là thôi đau não đủ
[01:15:47] khi họ tên ở lại thì tôi có đề nói như
[01:15:50] thế này họ tên này bỏ qua có dấu nhé bỏ
[01:15:53] qua có dấu họ tên thì thì họ tên chuẩn
[01:15:57] là như thế nào là chữ đầu tiên của tên
[01:16:02] nó phải viết hoa không ạ Tôi bỏ qua có
[01:16:06] tên có kí tự đặc biệt nhé
[01:16:08] thì dù là sự Đào Nguyễn Nhã Long nha Bỏ
[01:16:11] qua có dấu không ạ
[01:16:13] có khi mấy ông bị kỹ tên ở đây nó sẽ là
[01:16:17] gì nó là
[01:16:19] ô chữ đầu tiên viết hoa này
[01:16:22] ạ sau đó cắt gái sau đó chữ đầu tiên
[01:16:25] tiếp theo nó lại viết hoa này đúng ạ sợ
[01:16:28] cách một cái nữa đúng ạ Thôi sẽ gõ cho
[01:16:31] mấy ông ạ
[01:16:44] tên sai nó có thể ra như này nó sẽ là
[01:16:44] à Nguyễn nhà
[01:16:47] miễn Nam ngay không ạ
[01:16:50] Giả sử là
[01:16:53] Anh tên Sai nó cũng chỉ đơn giản như anh
[01:16:55] nó là Nguyễn Long tự nhiên này thừa cách
[01:16:59] ở cuối nhớ lại nó sai Tôi chỉ muốn là
[01:17:02] cách trị nằm trong khoảng vi tên như này
[01:17:05] thôi đó
[01:17:15] à À đúng rồi tên cũng có thể hái chữ bốn
[01:17:15] chữ đúng không ạ sử Nguyễn ai chẳng hạn
[01:17:18] vẫn đúng
[01:17:20] Anh tên truyện một chữ này thôi Miễn anh
[01:17:24] vẫn đúng à
[01:17:33] xe
[01:17:33] tải kiểu Nga vẫn đúng chứ cách cách để
[01:17:38] mà mịn
[01:17:39] 3 cách để mình bắt những cái trường hợp
[01:17:41] như thế này như thế nào chữ đầu tiên với
[01:17:44] hoa đúng
[01:17:45] ở đoạn này thì tôi không chia trường hợp
[01:17:48] thì cả tôi sẽ chỉ làm gặp gặp lại thôi
[01:17:52] Không không có chữ ngờ thì gặp nhưng mà
[01:17:54] tôi sẽ là mấy cậu đơn giản trước viết
[01:17:56] tắt a xuống Mỹ rút làm tắt đi thì béo sẽ
[01:18:00] thấy như thế nào ạ
[01:18:09] Lê Nguyễn Long hình sai chắc kiểu gì đấy
[01:18:09] trách mừng cơm rồi em
[01:18:12] bởi vì không thì ông sẽ check theo từ
[01:18:15] điển để ông kiểm tra xem từ đây có nằm
[01:18:18] trong từ điển tiếng Việt phải không
[01:18:21] bỏ qua việc tên có nhiều chữ đi mình sẽ
[01:18:24] làm nó tệ Tên của ông có bao nhiêu chữ
[01:18:28] cũng được mà người thật sự là
[01:18:31] thì
[01:18:32] mình đầu tiên là từ A đến Z viết hoa đầu
[01:18:37] ngoặc sau đó thì ai ghét ý thường thôi
[01:18:40] chả nặng thế không ạ Rồi bắt đầu của nó
[01:18:45] là những này đi cho gọn
[01:18:47] à à
[01:18:49] Vì sao nó thì giả sử là nếu mình ông bắt
[01:18:53] sâu người ông bắt sau giờ cậu là
[01:18:56] à À ông kêu vào thêm vào trường hợp
[01:18:58] nghiện 55 kìa đây Tok chó mèo
[01:19:02] nghỉ mệt mấy ông cậu bắt sâu dưới kiểu
[01:19:06] là từ điển tiếng Việt thì từ nào từ
[01:19:09] nhiều nhất thì như chỉ có tôi đã sáu từ
[01:19:12] thôi mấy ông sẽ là mi là một mắt là sáu
[01:19:15] nhà anh được nó chắc cú chẳng hạn thế
[01:19:19] nhớ tôi làm hai cậu đơn giản trước đi
[01:19:21] Tôi vẫn làm hiệu tượng rất đơn giản cho
[01:19:23] mấy ông đơn giản như này để cho ông ấy
[01:19:26] Ông thêm nghĩa như thế này cũng được
[01:19:28] hiểu thế thôi bỏ qua vụ đấy không tóc à
[01:19:32] à nhưng mà sau đó là có dấu cắt đúng
[01:19:36] không ạ cho một cách làm loạn sau đó lại
[01:19:39] từ a đến z được ạ oke lại từ ai đấy
[01:19:42] ông ạ nhưng sau đó thì lại có từ a đến z
[01:19:46] nữa mà lại amis ét thì mất cả triệu
[01:19:49] người na là Tôm nó rồi nó không ạ
[01:19:52] ở mình cho đây hỏi chấm mà Thì đây sẽ là
[01:19:57] sao nhé Sao thức Dạ
[01:19:59] không Mi là không đúng không mắc cả Vô
[01:20:03] Cực không ạ nhưng sau đó nữa lại lại dấu
[01:20:06] cách nữa lại như này tiếp thì làm như là
[01:20:09] đúng ạ
[01:20:10] Tik Tok mình sẽ cho cả cụm này
[01:20:14] trong mặt tròn rồi để cậu đó
[01:20:19] thêm hỏi chấm 2 trần nhà là được
[01:20:23] đúng ạ
[01:20:26] Ừ ông hiểu tôi vừa làm cái gì mấy cái
[01:20:29] loại hiểu mà
[01:20:32] anh alo
[01:20:44] khi đó tôi vừa làm việc cậu bây giờ nhập
[01:20:44] bao nhiêu tiền được đây em bị phong cách
[01:20:46] làm cho anh số 10 tới nhà được à
[01:20:53] Ừ đúng rồi
[01:20:53] nhờ các cụ máy Tôi ôm cả dấu cách xong
[01:20:57] nồi thêm nhé Miễn 5 ngày vẫn hợp lệ nó
[01:21:00] thừa dấu cách ở cuối này ạ
[01:21:03] a piece để xem Tại sao nó thưa dấu cách
[01:21:06] ở cuối hợp lệ nhà hả môi thêm cái này cô
[01:21:09] ấy đã quên đã
[01:21:12] à à
[01:21:27] Ở
[01:21:27] Đây Rồi Đây là cái cơ bản thôi vậy vẫn
[01:21:30] chưa có bạn mấy ông thấy ta thì tắt được
[01:21:32] hơn nhưng mà mình thế này đủ cơ bản thôi
[01:21:35] không cần những nói tắt hơn qua đâu là
[01:21:39] thứ khá không cần mắt thị trường hợp kỹ
[01:21:40] quá
[01:21:49] ở trường hợp này Thực ra nó nó sẽ nhập
[01:21:49] được Long nữa sẽ không không thỏa mãn
[01:21:51] đấy bởi vì đây dấu cộng này còn mấy mấy
[01:21:54] ông muốn nó nhập Long vẫn được thì em
[01:21:57] đổi nó thay nhà xấu xa thôi thì sẽ nhập
[01:22:00] Long
[01:22:10] có thể nhập tên kiểu dài quá các tiểu
[01:22:10] thư Thế thì cũng chết bằng cơm nữa thì
[01:22:12] không có trường hợp tử kia đâu
[01:22:26] Ừ ok
[01:22:26] Nói chung là nãy giờ đây toàn bộ kiến
[01:22:29] thức giữa mới nếu ông nào biết qua lứa
[01:22:31] cách cho cậu nhìn qua một lần rồi mà em
[01:22:34] sẽ thấy cái này là con tương đối dễ hiểu
[01:22:36] hơn một tí tiền hiểu mấy ông xem ở trên
[01:22:38] mấy cái trang trại rách thì tôi khẳng
[01:22:41] định là tôi dậy nó cơ bản hơn các bạn
[01:22:44] hơn
[01:22:46] thế nên là còn nếu mà Mấy ông mới hoàn
[01:22:49] toàn công nhận cái này rất khó trong một
[01:22:52] buổi tối thường anh dậy ở trên lớp phải
[01:22:54] hai ba buổi gái cơ nên mày không được
[01:22:57] ngạc nhiên thì mày cái này nó rất là khó
[01:22:59] hiểu với chửi tượng như thế
[01:23:01] Ừ nhưng mà nếu có thể Xem lại video mà
[01:23:04] đúng ạ và sẽ làm lại như cái bài hôm nay
[01:23:07] nữa nên là mấy ông làm dần thôi nó không
[01:23:10] ạ
[01:23:11] Đó đây là đầy đủ về đây cũng là đầy đủ
[01:23:15] tôi những cái mà tôi có thể dạy xong với
[01:23:18] ông về gái rồi bụng và buổi sau tôi sẽ
[01:23:21] kết hợp ra Swift với lách để mà làm vai
[01:23:24] đếch kiểm tra dữ liệu kiểm tra những cái
[01:23:27] thứ người ta nhập đúng và nhập đúng sai
[01:23:29] à Thế em bé Ông có về kiểm tra rất là
[01:23:31] đơn giản không cần lại nỗi phức tạp như
[01:23:33] nha à
[01:23:38] Em xác bí mật à
[01:23:38] à Tôn Bảo là cái bí mật về bạn Phương
[01:23:41] Linh không nghỉ thì khi nào mà bạn phải
[01:23:43] đạt được nó sẽ bật mí rồi chứ không phải
[01:23:46] đến cuối buổi sẽ bật mí đâu ạ
[01:23:54] Ừ hai cái link này tôi sẽ gửi cho bé
[01:23:54] uống sau nhé Cái này nó rất hạ nó có đầy
[01:23:57] đủ Có phải tại nó sẽ đầy đủ ấy
[01:24:01] trong này nó cũng giải thích lại một lần
[01:24:03] nữa này và mấy ông có thể dùng cái trang
[01:24:06] react 101.com này mấy ông test thử cốt
[01:24:09] các thử luôn để biết qua nhé án rồi quên
[01:24:13] quên đấy tôi tôi nói thêm một cái nữa
[01:24:17] thôi một cái nữa thôi về cái vụ mà nếu
[01:24:20] để ý kĩ là ghét nó con thêm cái bạn thật
[01:24:24] màn chất cái gái cái nó sẽ luôn viết nằm
[01:24:27] trong cái cái
[01:24:28] chỗ này
[01:24:30] nó luôn nằm trong cái hay cái dấu này để
[01:24:34] ghi cách một cái gì đó
[01:24:36] và sau đó thì nó sẽ có thêm một vài ký
[01:24:38] tự nữa Nếu bé ông đầy Chị ở đây nó cũng
[01:24:41] ký tự nó là giờ và m thì thường nếu
[01:24:45] không cần phải ghi Maria hay mở trong
[01:24:47] trường hợp này bởi vì à Giờ đây sẽ hiểu
[01:24:50] là nó sẽ trả về bạn trong trường hợp này
[01:24:53] thì ông ghi Mg để mà thể mà nó sẽ trả về
[01:24:58] thêm những cái khớp thay vì cái độc tiên
[01:25:01] cái này để test thôi còn ngoài ngoài
[01:25:04] thực tế ông dùng Viber thì ông sẽ không
[01:25:06] dùng cái gờ ông ông bắt buộc phải chỉ có
[01:25:10] một chỗ ở và chỗ để bắt buộc phải đúng
[01:25:12] thì ông ấy sẽ thì ông không cần dùng cầu
[01:25:15] làm gì cả con mờ làm chị để là
[01:25:19] Ừ để mà hiểu là
[01:25:22] để tách cái này ra hay nhiều dòng các
[01:25:25] bạn dụng mơ thức a khi mà vai đấy chứ
[01:25:28] các bạn chỉ có một dòng thôi không có
[01:25:30] cơm màu và cái cái mà các bạn cần biết
[01:25:33] nữa là cái y này mấy cái dưới này có thể
[01:25:36] bỏ qua nhưng còn tệ y này
[01:25:43] Ừ
[01:25:43] đúng rồi trong đống này chỉ mỗi cái rồi
[01:25:47] y incense típ tức à Không nhận cả tất cả
[01:25:50] là bỏ qua Phân biệt hòa thượng đấy các
[01:25:54] bạn sẽ biết về cái gì nữa nếu mà lần này
[01:25:57] mà bực dùng người y này các bạn không
[01:25:59] còn cần phải dùng ai Z viết hoa nữa các
[01:26:02] bạn a z thôi là đủ rồi đây có mỗi những
[01:26:05] cái đấy là những cái thêm của cái về
[01:26:08] cách để không ạ
[01:26:10] đó buổi hôm nay sẽ chỉ đến thế thôi à
[01:26:16] I trở tình yêu muốn làm là đúng bài tập
[01:26:19] này cũng đủ mệt rồi Cuối tuần mà thôi
[01:26:23] chẳng yêu cầu vì khó ngồi làm lại đúng
[01:26:25] ngay thôi à
[01:26:28] à à
