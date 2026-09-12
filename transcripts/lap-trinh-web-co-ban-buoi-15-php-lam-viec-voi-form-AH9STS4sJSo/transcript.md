# Lập trình Web cơ bản - Buổi 15 - PHP - Làm việc với Form

- Video ID: `AH9STS4sJSo`
- URL: https://www.youtube.com/watch?v=AH9STS4sJSo
- Published: 2021-11-27
- Duration: 1h 17m 4s (4624s)
- Language: vi
- Subtitle source: auto
- Kind: live

## Transcript

[00:00:02] anh ạ
[00:00:03] à à
[00:00:07] anh alo các bạn nghe thấy chưa ạ
[00:00:08] anh
[00:00:16] alo Chào tất cả bạn
[00:00:26] cho mình hình như vừa rồi bị vừa thấy
[00:00:28] cái vụ là nhớ giữ tím không biết thì bị
[00:00:30] hack vậy Tự nhiên đổi ảnh bìa trong lão
[00:00:33] hóa được mấy hôm nào học nước bụng đây
[00:00:36] chưa tôi thì vừa rồi tôi soạn bài nó
[00:00:41] à à
[00:00:44] Ừ chắc là nóc nhà của thầy hiệu trưởng
[00:00:46] lại bị lại
[00:00:53] em còn nóc nhà tôi đang định khách đôi
[00:00:55] hàng Bia của tôi
[00:01:19] Ừ ok thì hôm nay mình xin phép tâm sự
[00:01:22] một tí tâm sự về
[00:01:26] tốt nhất là như mình từng nói đó là con
[00:01:28] gà ấy được thích kiểu
[00:01:31] và đương nhiên thì con gái không phải
[00:01:33] bảo là
[00:01:36] ẩm thực thực dụng các tự thứ mình sẽ chỉ
[00:01:39] nói là con gái thực tế hơn con trai
[00:01:42] 10 lời chúc tết con trai khá nhiều con
[00:01:45] trai đương nhiên họ có mơ mộng nhé học
[00:01:47] rất là mơ mộng nhưng mà họ vẫn kiểu nghĩ
[00:01:50] cho tương lai theo kiểu là nghĩ về việc
[00:01:51] là
[00:01:53] nên lấy chồng như thế nào rồi kìa một
[00:01:55] phần là do cái
[00:01:57] khi cài đặt Thủ Xã hội nó kiểu bây giờ
[00:02:00] nó kìa Thế là kiểu con gái phải lấy
[00:02:01] chồng bây giờ sẽ bị ảnh hưởng rất nhiều
[00:02:03] chi phối bởi Gia Đình Nhà chồng mỗi
[00:02:05] người trong nên làm ra được con gái rất
[00:02:08] cần người mà cặp thấy họ tin tưởng họ
[00:02:12] cảm thấy có tương tương lai thì họ mới
[00:02:13] thiệu
[00:02:17] nghĩ cái thứ thứ
[00:02:21] Vì thế nên là cái vụ mà Nhiều người bảo
[00:02:23] là không thích cái kiểu chỉ yêu con trai
[00:02:26] nhiều tiền lại cứ tưởng thứ thật ra là
[00:02:28] nó lửa đúng nửa say
[00:02:30] Ồ vậy à
[00:02:33] Ừ đúng ở đây là việc là con ngại đứng
[00:02:35] yên thực tế thấy rõ ràng mấy cái ông có
[00:02:37] gì trong tay xong rồi ông chẳng nói gì
[00:02:39] trong tay thôi nha nó sự so sánh rối
[00:02:41] loạn
[00:02:45] là tôi tôi cũng sẽ chọn bạn gái vừa xinh
[00:02:48] vừa giàu so với bạn chỉ bình thường mà
[00:02:52] không giấu tôi tôi sẽ làm để đấy Đang
[00:02:54] đang nói qua về thế không nói qua tính
[00:02:55] cách nhé
[00:02:58] anh Bởi vì lúc đầu họ mới quen ông thì
[00:03:00] làm sao họ biết là tính cách của ông nhà
[00:03:02] họ sẽ nhìn vào cái gì họ nhìn và những
[00:03:04] cái kiểu
[00:03:07] thì đấy Đấy cái tôi đã định nói nó là
[00:03:09] cái chí của ông thường anh gọi chị tiến
[00:03:09] thủ
[00:03:13] ông chủ nhật không Tôi tôi theo dõi kể
[00:03:16] Tết tiếng Việt giàu đẹp trong ngoài nó
[00:03:18] kiểu
[00:03:20] từ thiên hạ nó đăng phải cái bài nào
[00:03:22] kiểu thực ra từ trước đến nay các bạn
[00:03:24] dùng sai chính tả rồi vẫn Vâng ra mới gì
[00:03:26] đó xảy ra với Thôi mất dần cái niệm
[00:03:29] chính tả đúng hay sai rồi
[00:03:32] nhưng đại khái thế chứ tốn thủng như tôi
[00:03:36] đang đang hình dung ấy thì nó sẽ ra
[00:03:40] kiểu có muốn cầu tiến không muốn kiểu
[00:03:43] dạng và kiểu dẫn chân lại chỗ nào ạ luôn
[00:03:46] muốn mình tiến bộ lên các thứ thứ thì
[00:03:49] cái việc con gái thì chị con trai còn gì
[00:03:53] nữa tụi nó sẽ phù hợp theo kiểu là kể cả
[00:03:56] sao dù ông không có gì trong tay thì ra
[00:03:58] ông còn được biết phấn đấu xong những
[00:03:59] điều không ghi trong tay không còn là nó
[00:04:03] bỏ hôm nay con mà tự cái thành ra là con
[00:04:06] gái không thích mấy cái thể loại đấy lắm
[00:04:09] Trừ khi bạn nào thích kiểu thích thích
[00:04:12] hẳn có vài bạn thì ra là cũng hơi Dịu lý
[00:04:15] bạn đây cũng thích kiểu thay đổi được
[00:04:17] một con người ở đó nếu bạn đấy là trong
[00:04:19] trường hợp khi hai người quen nhau lâu
[00:04:24] rồi Giả sử bạn kia thấy được không ai có
[00:04:26] thể thay đổi được một Thay đổi hôm đấy
[00:04:28] chứ không phải tự nhiên mới quen Tự
[00:04:29] nhiên thấy ông này xấu vãi chưởng Đệ Nhị
[00:04:32] đập đầu vào Thế thì điên loạn sẽ điên
[00:04:33] mất
[00:04:44] nghe lời chúc là Kiều Ở mình từng mình
[00:04:46] từng Không có gì giống tay theo kiểu rất
[00:04:49] là nghèo mình để cũng đã từng hẹn hò với
[00:04:53] các bạn nữ khá nhiều thế Mình khẳng định
[00:04:55] được các bạn lấy nó không Không đến nỗi
[00:04:58] là kiểu yêu cầu mình phải giàu có hay
[00:04:59] các sư Xứ
[00:05:03] ở đây là mấy ông Nếu mà tôi Tôi đang nói
[00:05:05] với mấy ông ấy Nghĩa là mấy hôm ra khi
[00:05:10] nào mà đang chỗ nghĩa chuyện hẹn hò tình
[00:05:14] cảm có thứ cho tôi tôi thấy ở ra là tuổi
[00:05:18] tuổi kiểu sinh viên học sinh ở này thì
[00:05:20] ra vẫn nên có một cái mối tình trong cái
[00:05:22] khoảng thời gian này bởi vì nó vẫn còn
[00:05:26] ít thực dụng nó thực tế một tí nón còn
[00:05:28] theo kiểu là
[00:05:31] khi tất cả cùng chia sẻ
[00:05:35] hoàn cảnh với nhau thay vì kiểu thay vì
[00:05:39] kiểu mấy mấy ông Khi mà đi làm rồi Mấy
[00:05:42] ông bắt đầu có tí cầu phải liên quan đến
[00:05:45] tiền bạc các thứ thứ thì thành ra là hẹn
[00:05:47] hò đôi khi ở đó có liên quan mối quan hệ
[00:05:50] cho con tiền bạc hơn
[00:05:52] vì nó không còn thực sự là tình cảm
[00:05:54] trong sáng nữa
[00:06:00] Ừ đúng rồi tôi tôi từ một thân tôi từng
[00:06:02] nói qua rồi mà Từng Hẹn Hò Dưới rất
[00:06:02] nhiều
[00:06:05] thành ra là Tôi không phải là một con
[00:06:07] người chỉ biết lý thuyết suông đâu Thôi
[00:06:10] thực hành rất nhưng rất nhiều rồi
[00:06:12] à à
[00:06:13] ra
[00:06:16] tại đại khái thế tôi chia sẻ được vụ đấy
[00:06:19] em bảo ông này mấy ông kiểu cảm thấy à
[00:06:21] có động lực gì đó để mà
[00:06:25] Em thử thử cả giá đấy thử cảm giác này
[00:06:27] như tôi hôm trước có cũng ngon Nói về
[00:06:31] cái vụ là béo phải có động lực để mà để
[00:06:35] mà kiểu phát triển để tiến bộ hơn mà nó
[00:06:36] bận
[00:06:38] chị Thi động lực của mấy ông chính là
[00:06:40] người yêu cũng là một động lực mà nước
[00:06:42] vợ động lực khá to lớn đấy Cô đấy sẽ
[00:06:45] khiến cho bạn phải thay đổi khá nhiều
[00:06:56] a
[00:07:00] tiếp theo nói về đỏ đen Ờ quan điểm của
[00:07:04] mình mình là một con người ạ sống về lý
[00:07:09] trí khá nhiều dáng hơn rất là kiểu tính
[00:07:12] đã trường hợp các thứ thứ
[00:07:13] nhà
[00:07:17] mình gần nhau mình sẽ ít khi bị choáng
[00:07:18] bởi vì à
[00:07:21] sau khi bị sốc bởi vì mình đã tình hình
[00:07:26] như là mới dồi và thế nên là bởi vì mình
[00:07:29] tính các trường hợp mà mình thử mình
[00:07:32] nghĩ ra được và cách đối phó vấn đề đấy
[00:07:35] rồi nên là mình ít khi nghĩ đến việc đen
[00:07:38] đủ lắm Mình sẽ nghĩ được à Có thể mình
[00:07:40] chưa thành niên đến chưa được đấy
[00:07:43] tốt hơn là mình nghĩ việc mình đen theo
[00:07:47] cơ nhiều ông gấu bờ tháng này đen để các
[00:07:50] thứ thằng qua lỗi do mình thôi
[00:07:53] Vì mình chưa nghĩ việc bị đen Cái gì cả
[00:07:56] mình chưa nói cô đen quá hay vân vân lại
[00:07:59] lại thế đưa nhiên mình cũng nghĩ việc là
[00:08:01] mình may mắn Mình thường hay nói có rất
[00:08:04] nhiều rất nhiều yếu tố may mắn xảy ra
[00:08:07] khiến cho mình đừng như bây giờ
[00:08:08] cho
[00:08:11] ví dụ Giả sử là nếu mà tôi mà xông vào
[00:08:14] triều tiên con beauty thì chắc chắn có
[00:08:16] thể thao không lời nhưng bây giờ nếu mà
[00:08:18] tôi không kết bạn với cái ông mà học
[00:08:20] khác lớp của tôi để ông ấy chia sẻ bài
[00:08:24] của utyt thì chưa chắc tôi đã như bây
[00:08:26] giờ vân vân đó bạn
[00:08:28] em thậm chí là mình chưa biết mình kể
[00:08:30] các bạn với cái vụ là mình à
[00:08:35] từ hồi cấp 2 mình ở từng suýt trúng xổ
[00:08:38] số 1 triệu đâu ở bên Mỹ mình nó tấm séc
[00:08:41] thể bên này nhưng mà chẳng qua là tôi
[00:08:43] nghe chưa đủ tuổi và cũng như ghi địa
[00:08:47] chỉ mình ghi sử là 7 A3 không được nhận
[00:08:50] Đây của hồi đấy một triệu đô là 16 tỷ
[00:08:53] đấy à
[00:08:57] cho mình mình không không may mà mình
[00:09:00] mình cảm thấy may khi mà không nhận được
[00:09:03] rồi đấy theo kiểu là có khi lúc đấy tôi
[00:09:05] thành con người khác Xong rồi bây giờ
[00:09:08] rồi Có khi là tôi thành là kiểu
[00:09:11] ờ ờ kiểu dạng và
[00:09:15] Anh có thể làm bố mẹ sẽ Tống Sang đi du
[00:09:16] học nước ngoài để mà học về tài chính
[00:09:18] chứ không phải học về được truyền kiểu
[00:09:20] gì thế để mà học cách tiêu tiền rồi thế
[00:09:23] bởi mỗi thằng lớp 7 thì gần đầy tiền nắm
[00:09:26] tay nó không học hành gì nữa bỏ học mất
[00:09:29] rồi Thế à
[00:09:31] em có rất nhiều bước ngoặt trong cuộc
[00:09:34] đời mấy ông đôi khi phải nghĩ lại những
[00:09:36] cái bước ngoặt trong cuộc đời của ông và
[00:09:40] mấy ông không không nên kiểu dạng là hối
[00:09:42] hận vì một cái gì đó tôi trả giờ hối hận
[00:09:45] cái gì đó trong quá khứ Mọi mình sẽ hiểu
[00:09:46] à
[00:09:48] cho
[00:09:51] mình mình sẽ cậu lấy nó là bài học hay
[00:09:54] là cái gì đó may mắn kiểu thế chứ không
[00:09:57] coi nó mới sợ đen đủi gì cả cho tôi ít
[00:09:58] khi hối hận gì đó
[00:10:01] cho ví dụ kể cả tùy từng bị tai nạn các
[00:10:04] thứ thứ nhưng mà chính vì sau cái vụ tai
[00:10:05] nạn đấy tội nhận ra được nhiều điều hay
[00:10:07] trân trọng và nhiều điều hơn Hãy cởi hết
[00:10:14] hệ thống nhà tôi mua con máy này chẳng
[00:10:17] ăn mày 38 củ này do cùi bắp này cứ máy
[00:10:21] nóng lên là bị trêu chết Cá thứ tôi bây
[00:10:23] giờ tôi rút kinh nghiệm và kiểu phải mua
[00:10:26] mua hàng chính hãng mua hàng có vào hàng
[00:10:28] các thứ đặt bìa những đôi định công nghệ
[00:10:31] điện tử Thế là hôm qua tôi vừa mới đi
[00:10:34] tìm lách khỏi đây nhưng mà săn lách vào
[00:10:38] đây tìm mua con máy lọc nước máy là
[00:10:41] không khí tôi phải tìm đúng chính hãng
[00:10:43] và cũng như là hoặc là các cửa hàng to
[00:10:46] uy tín thì tôi mới mua tôi không ham
[00:10:49] mình ấy kiểu mấy cái trang hiểu trong nó
[00:10:51] kiểu dạng vào trong có vẻ làn da sốc đấy
[00:10:54] nếu mà dùng nói chung chẳng tin tưởng
[00:10:58] với cả cái kiểu hết ế à à
[00:11:01] Ê mấy ông cũng nên cân nhắc nhở vụ mua
[00:11:02] máy lọc nước máy lọc không khí sớm đi
[00:11:06] xung quanh chúng ta đang Ôi nhớ lắm nếu
[00:11:09] không biết tôi đã từng sống ở phố Cổ
[00:11:13] nghe về rất xa Nhưng thực ra là ở chỗ
[00:11:14] đấy ẩm thấp và
[00:11:18] Hà Nội chùa tệ tệ kinh khủng Các bạn cứ
[00:11:20] hình dung lại cái nhà vệ sinh công cộng
[00:11:24] ở ngoài công cộng nó như thế nào Nhà tôi
[00:11:27] có nhà tù cả cái xóm nhà tôi dùng chung
[00:11:29] với nhà vệ sinh công cộng nó cũng như
[00:11:30] thế
[00:11:33] Khi sản nhà trong phố cổ thì máy tí cái
[00:11:37] thứ ẩm thấp nằm trên gác xép nó hư rồi
[00:11:40] cứ nhớ lại thấy sợ đấy thì tôi tưởng
[00:11:43] sống và môi trường như thế thôi hình
[00:11:45] dung rõ việc là
[00:11:48] cái không khí ô nhiễm mọi thứ hôi nhiễm
[00:11:50] sẽ ảnh hưởng như thế nào
[00:11:53] ở đáy và tội cảm thấy may mắn đi xa bây
[00:11:54] giờ vẫn còn tỉnh táo không bị dấu hiệu
[00:11:58] gì cả anh chỉ có phổi hơi bị yếu một tí
[00:12:04] anh ở đấy và tiếp về cuối thì vừa rồi
[00:12:07] mình có nói qua lại việc làm mọi thứ do
[00:12:09] mình tính toán quyết định thế nên là
[00:12:11] mình thừa Mẹ không tin hẳn vào duyên số
[00:12:12] lắm
[00:12:15] Mình mình yêu nghĩa là mình cũng nghĩ
[00:12:17] được là chúng ta phải có một cách gì đó
[00:12:20] tinh con vô tình mà khiến gặp được nhau
[00:12:22] như thế phấn Vân đó nhọn như là tôi
[00:12:25] không tin là số phận mình do nó được
[00:12:28] định sẵn có nhiều cái kiểu bói tử vi hay
[00:12:31] bói bói gì đó tôi trả lời tin được
[00:12:34] dù người ta nói có thể có thể có vẻ rất
[00:12:37] hợp lý và rất nghe mày giữa hai người ta
[00:12:39] bỏ cái tôi là một con người đào hoa này
[00:12:43] bây sau dầu Đấy đấy nghe Nghe hấp dẫn
[00:12:46] không Ông xong rồi bị ông nghe thấy
[00:12:48] giọng thích được không Anh nên tôi có
[00:12:51] tin đâu Tôi không chờ tin mà bỏ toán
[00:12:53] không tin vào cái
[00:12:56] tủ sách tử vi cuộc sống mình do mình
[00:12:57] quyết định không phải là người thật
[00:13:00] không phải trọn đời ghi là là năm nay
[00:13:03] bạn sẽ cưới vợ và tôi sẽ cưới vợ 2 năm
[00:13:06] nay bạn sẽ mất thì thì ông kiểu rượu sẽ
[00:13:09] mất trong năm này không đúng
[00:13:12] em năm nay bạn sẽ giàu thế nên là bạn cứ
[00:13:14] ăn chơi thoải mái đi thôi đừng phát năm
[00:13:15] đấy bạn giàu có không làm gì có chuyện
[00:13:18] đấy rồi đúng không ạ Thế nên là mình
[00:13:20] không tin là những cái đấy
[00:13:24] Em gọi thử vẫn là do mình quyết định và
[00:13:26] học lập trình ngày thở ra đấy cái lợi
[00:13:29] cái tư duy như thế các bạn khiến cho các
[00:13:32] bạn là học lập trình nghề được gọi là
[00:13:34] phải có mua gì lôgic và không có gì mày
[00:13:37] rồi Không có gì đỏ đen mọi thứ đều phải
[00:13:41] cậu tính toán cẩn thận để mà ra được
[00:13:51] Ừ Ok bây giờ vừa đúng lúc hết rồi ạ Mình
[00:13:54] sang trả lời các hỏi nha
[00:13:54] Mỹ
[00:14:02] Tâm Linh à tâm linh là một thứ gì đó
[00:14:05] không giải thích được mình tin nó có
[00:14:07] thật nhưng mà
[00:14:11] cơ bản nhưng mà mình sẽ không
[00:14:15] mình mình cũng tìm hiểu Vì nó hạ khá
[00:14:18] nhiều nhưng mà ý máy mình sẽ thường anh
[00:14:20] hạn chế rồi nó vừa thừa những cây thử
[00:14:24] đấy mình nghĩa tò mò nhiều lại không tốt
[00:14:29] ok đầu tiên à Hôm trước của tôi ra bài
[00:14:32] tập về hai bài 2 lần bài tập về sơ đồ
[00:14:35] khối thuật toán Nếu mấy ông để ý thì ca
[00:14:38] ở tôi chưa dậy rồi đấy thôi muốn cho bé
[00:14:40] uống làm qua đã và hôm nay tôi sẽ dạy
[00:14:42] con mày thử cá học TP thì ra khá nhanh
[00:14:44] kiến thức qua mạng làm lắp
[00:14:48] tạm thời Thế tôi đang dạy các bạn từng
[00:14:50] bước từng bước mà không ạ sau đó thì còn
[00:14:52] thời gian tôi sẽ dậy mình Ông ấy sơ đồ
[00:14:55] khối thuật toán và chữa bay hôm trước
[00:14:57] a tiếp theo
[00:15:00] dự đoán xịn có giới thiệu công việc
[00:15:04] không thì nếu mà bạn ở chưa biết thì là
[00:15:07] tôi sẽ bảo là mày ông sẽ có một cái đồ
[00:15:11] án làm và bảo vệ vợ và sẽ làm theo cặp
[00:15:16] thì cho buổi tí tôi cũng sẽ làm một cái
[00:15:18] phom và gửi các bạn thì các bạn điền
[00:15:23] điền thông tin các thứ thú để mà tôi sẽ
[00:15:25] chạy ra luôn ghép cặp cho mấy ông này
[00:15:28] mấy ông chung một cái đồ à chung cũng
[00:15:34] và đặc biệt là nên ghét sớm để mấy ông
[00:15:38] kiểu có động lực thúc nhau ai cũng có
[00:15:40] nên có trách nhiệm tinh thần làm việc
[00:15:43] theo nhóm nó gọn kiểu dạng và ông này
[00:15:45] thấy ông kia học hành trình mảnh lại gì
[00:15:47] đó
[00:15:50] anh gọi thì mèo ông sẽ nhắc nhở nhau chứ
[00:15:52] tôi ở đây tôi không ngờ nhắc tất cả mấy
[00:15:59] bà và cái vụ bảo vệ đồ án thì sẽ
[00:16:03] như tôi đã nói thì sẽ cố Mời tất cả các
[00:16:07] thầy để mà tham gia để phản biện ném đá
[00:16:10] mấy ông để mấy ông tiểu bảo vệ được
[00:16:13] thành công thì sẽ chắn là thứ nhất ở mấy
[00:16:15] ông cảm thấy thỏa mãn này làm đã thứ hai
[00:16:18] là cậu sẽ tự thấy mình trưởng thành hơn
[00:16:20] so với ngay bây giờ ngay bây giờ đây nè
[00:16:22] Bây giờ là lúc là mấy ông mới bắt đầu
[00:16:24] học so với thời đấy nếu không sẽ thấy ở
[00:16:29] cậu nó sẽ khác xa như thế nào đến như là
[00:16:32] như tôi nói là sau cái khóa này Thực ra
[00:16:34] mấy ông vẫn chưa đi làm được đâu bởi vì
[00:16:37] tất cả mấy trẻ cơ bản đồng loại méo đi
[00:16:40] làm mình mới chỉ đi tập vậy thôi và vẫn
[00:16:43] phải học hỏi thêm thì béo Nhưng mà mấy
[00:16:45] ông sẽ cân nhắc mình việc là có thể
[00:16:48] thiện treo khóa sau 20 Hóa ở trên sau
[00:16:52] hơn và khóa đấy sẽ mới mới là thứ mà dậy
[00:16:54] những cái thứ mà béo có thể đi làm được
[00:16:55] luôn
[00:16:59] thì cái vụ đồ ăn xịn có giới thiệu công
[00:17:01] việc không thì thực ra như mình đã nói
[00:17:04] là mình còn bây giờ có rất nhiều bên
[00:17:07] đang hỏi mình mình một lực thậm giữa
[00:17:10] công ty mình đang thiếu một lực nhưng mà
[00:17:13] yêu mình như mình vừa nói luôn đó là
[00:17:17] kiểu các bạn Nếu mà đi tập sớm như thế
[00:17:19] thì các bạn vẫn phải học Lỡ bài học rất
[00:17:21] nhiều và
[00:17:25] A và kiểu dáng không phải công ty nào nó
[00:17:27] cũng sẽ đào tạo các bạn đồn các bạn đôi
[00:17:29] khi sẽ bị là nó cái mà vào một công ty ở
[00:17:32] đó mà cảm thấy họ bơ họ họ bơ mình với
[00:17:36] việc họ mà không đào tạo ổn họ sẽ kiểu
[00:17:38] giao trong một đống tài liệu rồi mẹ mấy
[00:17:41] ông tự Ngồi đấy mà đọc sau quan thậm chí
[00:17:44] ở vẫn giao cho ông việc mà Việc đấy ông
[00:17:47] chưa biết làm nhẹ ạ ông sẽ bị phạt Nếu
[00:17:50] hiểu tôi không nên là mấy ông sẽ phải
[00:17:53] cân nhắc Đã đó là mấy ông phải làm làm
[00:17:54] đồ án xong mày không cảm thấy trình độ
[00:17:58] của mấy ông đã đủ đã đủ chưa không nhỉ
[00:18:01] vẫn phải làm thêm một cái đồ ăn nữa đúng
[00:18:04] không này có thực sự ngon hẳn đã
[00:18:07] mấy ông bây giờ cứ tính đi bây giờ học
[00:18:10] hết cái pp khóa này chắc là cũng là ba
[00:18:11] hàng nữa thôi
[00:18:13] 2013 thằng chuyên sâu nữa
[00:18:17] nửa năm học nửa năm ở trên Thường mấy nó
[00:18:19] có khi ở chưa bằng học nửa năm của tôi
[00:18:22] cái đấy tôi khẳng định được thì mấy ông
[00:18:25] đợi được đến thời gian này em ấy không
[00:18:28] đi làm vẫn đường mà đúng loạn nghĩa là
[00:18:31] trước Hè năm sau sẽ khẳng định được là
[00:18:33] trước hai năm sau trước 11 tháng 6 này ạ
[00:18:35] Hãy
[00:18:37] ừ ừ
[00:18:40] a tiếp theo có nên nghiên cứu khoa học
[00:18:41] hay không
[00:18:43] cứ nghiên cứu khoa học này chắc là liên
[00:18:45] quan đến kiểu sống như mình cái kiểu làm
[00:18:48] bài luận hay cái gì gió ở bên đại học
[00:18:51] tôi khuyên mấy ông là kiểu
[00:18:54] với bên lập trình này thì thấy ta chúng
[00:19:02] à à
[00:19:04] cho
[00:19:09] nên nên là kiểu 0000 lên không nên kiểu
[00:19:12] tìm hiểu sâu quá vì lí thuyết làm gì cả
[00:19:15] đấy tôi khuyên như thế còn nếu mày Ông
[00:19:17] lại muốn học lên thạc sỹ hai mấy ông
[00:19:19] muốn có một cái gì đó kiểu dạng lại Ok
[00:19:22] chứng chỉ hãy chứng nhận gì đó
[00:19:25] À thì ra tôi vẫn khuyên như thế nhá về
[00:19:27] thực sự thì đi lại đi Chiều khi ông đi
[00:19:30] đấu thầu hoặc cả ông trời muốn khoe
[00:19:32] khoang gì đó thôi không thì thường là
[00:19:34] người ta nhìn vào trình độ của ông kinh
[00:19:43] à mình mình mình hiểu cái nghiên cứu
[00:19:45] khoa học và làm một cái đồ án nhưng mà
[00:19:48] nó sẽ là chỉ là một cái nghiên cứu thôi
[00:19:51] Có cái lý thuyết thôi lần như thế cho
[00:19:54] bên đại học chính quy mình biết mà bên
[00:19:55] đại học Bách khoa mình thấy có rất nhiều
[00:19:58] bạn làm xong thì đề tài nghiên cứu các
[00:20:02] thứ thứ song Thực ra nó cũng ra gì ấy nó
[00:20:04] cũng hiểu đương nhiên là học không lời
[00:20:07] Thừa cả Nổi Loạn các bạn học sau là tốt
[00:20:09] nhưng mà cũng Trọng đây
[00:20:11] Anh khoe cái đấy cho bên là
[00:20:15] trừ khi các bạn xin vào những ngành
[00:20:17] chuyên sâu về lí thuyết giống như là
[00:20:22] Toán y cá thứ thì may ra họ cần cầm nếu
[00:20:26] mà các bạn vào làm bác em kiểu Làm lập
[00:20:28] trình viên như bình thường như này người
[00:20:30] ta đòi hỏi các bạn phải thực hành người
[00:20:32] ta không đòi hỏi với Nếu thuộc tá xịn
[00:20:37] nhà báo thực sự là mấy ông tìm hiểu sâu
[00:20:39] á Tôi thề mấy cái ông tìm hiểu sâu mãi
[00:20:42] cứ bị máy móc còn gì một bài toán đơn
[00:20:44] giản mà Mấy ông cứ phức tạp lên thành ra
[00:20:46] là tôi thôi bị dị ứng mấy kiểu này lắm
[00:20:49] Tôi là con người từ bên nghề ra mà anh
[00:20:59] ờ ờ tiếp theo là espn interactions 2 là
[00:21:02] ờ
[00:21:06] cho mình mình sẽ Đề cập về cái event gas
[00:21:08] này tất cả một kiểu hình thức hack mà
[00:21:09] chắc là vậy
[00:21:12] ạ sau khóa này hỏi thậm chí hôm bảo vệ
[00:21:14] đoán Tôi sẽ thử hỏi mấy ông người cái
[00:21:16] đây xem
[00:21:18] xem web rồi mày ông có bị dính mấy cái
[00:21:22] lỗi hết khủng đã từ từ không Ừ chắc À
[00:21:25] cái này tôi sẽ dậy Sao lâu vậy
[00:21:28] anh ở Lưu kiểu dữ liệu ảnh trong Fe ở
[00:21:31] trong buổi sau mình sẽ chỉ đây tìm heo
[00:21:34] có bạn hỏi là họ trước bạn ấy muốn họ
[00:21:36] trước pp thì học ở đâu ngoài đang live
[00:21:39] school thì thơ ca Hồi trước mình có thử
[00:21:42] cho sinh viên mình ôn thì ổn ở trên à
[00:21:43] cốt
[00:21:47] code academy mình mình có chỉ là sinh
[00:21:50] viên lên đấy mà có làm trước một vài cái
[00:21:52] kiểu bài tập các thứ
[00:21:54] có academy
[00:21:57] tại các bạn thể tham khảo trên trang đấy
[00:22:00] Thực ra là mình cũng sẽ giao các bạn mỹ
[00:22:09] Nếu thế có cả một tí nâng cao một tí đi
[00:22:11] để cho các bạn luôn có thời gian đủ để
[00:22:12] mà
[00:22:15] Ừ nếu mà bạn nào thừa thì ra đấy vẫn có
[00:22:19] thể có thứ để mà làm đi học được ạ
[00:22:19] Ừ
[00:22:22] mình đang dạy hướng đến là kiểu phù hợp
[00:22:25] cho bạn nào đang học ngành khác cũng có
[00:22:27] thể học được anh ra cậu cũng tương đối
[00:22:29] chậm mà cũng trong nồi ít bài tập thôi
[00:22:33] chứ nhiều bài quá thì nó cũng khá nhiều
[00:22:36] buổi dạy quá thì đã nó không ổn lắm
[00:22:40] a tiếp theo là có bạn hỏi về kiểu Khi
[00:22:43] nào thử lai cốt để mà viết một cái tiện
[00:22:45] ích gì đó giống như thế Tôi từng viết là
[00:22:47] gái xinh chọn lọc thành lại chả là tôi
[00:22:50] sẽ dạy cái này sau dậy sau
[00:22:53] tôi cái Tôi không hứa được cái này lúc
[00:22:56] nào chả phải tùy cảm hứng nữa và tùy
[00:23:05] t-ara mà chắc mình sẽ mình sẽ chốt lại
[00:23:07] lần cuối về việc là trong khóa này mình
[00:23:09] sẽ dạy những cái gì và khóa sau mình sẽ
[00:23:11] dậy những cái gì để cho những bạn nào
[00:23:14] quan tâm nhé trong khóa này là pp cụ Cơ
[00:23:16] bản nó gọn và web cơ bản
[00:23:21] đây web cơ bản thì mình sẽ dạy hát em
[00:23:24] lâu rồi này sẽ hết rồi này ra Switch rồi
[00:23:27] đây nếu mà chỉ để làm bếp này
[00:23:28] pp này
[00:23:31] cái video này à
[00:23:34] ở những cái này thì à p chỉ đầy đủ tính
[00:23:38] năng CRD để xem thêm sửa xóa
[00:23:47] a a flash file hay bạn lại phải như thế
[00:23:51] mình sẽ không dạy về Ok không thể mvc
[00:23:54] thống khóa này mai que thì sẽ chỉ là
[00:24:00] cũng lại bml là là Insert update bị
[00:24:03] Delete phải cô đơn giản đây QL cũng thế
[00:24:06] là câu C của Ngoạ những con đơn giản
[00:24:10] thôi mình sẽ không hẳn là dạy các bạn về
[00:24:12] Goodbye không không không có Goodbye
[00:24:19] A và trong gia Swift này mình cũng sẽ
[00:24:22] không dậy thêm chèn thêm gj0 chèn thêm
[00:24:26] Facebook hay thư viện gì cả đấy đều có
[00:24:29] bạn đang nghĩa là web cơ bản này sẽ như
[00:24:33] thế còn khóa sau sẽ web chuyên sâu à
[00:24:37] linh cảm được chứ Dậu được kìa Cái cái
[00:24:39] sau là đúng Hát Việt thật thì ngoài mấy
[00:24:41] cái mình đã dậy thì mình sẽ dạy thêm về
[00:24:45] level là Facebook của Facebook của TP đó
[00:24:48] bây giờ ra quyết định hành giữa ổn nhớ
[00:24:51] là gladio này thì mình sẽ chỉ dậy một
[00:24:53] cách cơ bản
[00:24:55] Ừ chứ không phải là dùng những cái hàm
[00:24:58] có sẵn của Lara để mà cốt nhanh mình sẽ
[00:25:01] dạy các bạn về quê do và cậu cốt thuần
[00:25:04] là nhiều để mà mình sẽ dạy chuyên sâu và
[00:25:08] cả bên hẹn axwell nữa vẫn là mái quelle
[00:25:10] nhưng là này nasware nó sẽ là có thể roi
[00:25:17] khi được ạ
[00:25:20] Các tiểu thư để mặc và đương nhiên là sẽ
[00:25:23] có Goodbye vậy mà thùng thống kê làm bài
[00:25:27] toán thống kê các thứ thứ đấy và vectơ
[00:25:29] sau này còn sẽ còn dậy sâu hơn về việc
[00:25:30] là
[00:25:34] bài toán xử lý cần phải như thế nào chứ
[00:25:35] không phải chỉ đơn giản là hiển thị ra
[00:25:38] hãy các thứ Nói chung là
[00:25:41] các bạn khi mà các bạn học cái này có
[00:25:44] bạn mình sẽ cảm thấy là kẹo thật sự là
[00:25:47] học cái này xong các bạn thấy bất kỳ cái
[00:25:49] trong web nào Bây giờ các bạn cũng hình
[00:25:52] dung được cái cái cách làm của nó như
[00:25:55] thế nào không phải làm lại được hành
[00:25:56] trang web kiểu như nó nhưng mà hoàn toàn
[00:25:59] có thể biết được bọn nó làm như thế nào
[00:26:03] làm lại được thì vẫn làm được thôi để
[00:26:05] trải qua nó áp dụng nhiều công nghệ cao
[00:26:07] siêu Hóa thì mình sẽ
[00:26:10] vụ tấn công nhiều để mà làm được lại như
[00:26:12] đó
[00:26:15] Ừ nhưng mà học xong cái khóa sau mình
[00:26:18] vẫn khẳng định là bất kỳ cái gì thì các
[00:26:21] bạn nhìn vào các bạn sẽ nhìn thấy đầy lỗ
[00:26:24] họng đầy những cái thú mà nó sơ sài nó
[00:26:28] thiếu nó đểu và các bạn hoàn toàn thấy
[00:26:30] mình có thể làm được một cái tương tự
[00:26:34] cái cái khóa sau sẽ như thế Thế các bạn
[00:26:36] đi làm được rồi Đúng đoạn đi làm được
[00:26:42] xe tải mình mình đã vừa trả lời hết một
[00:26:45] là có hỏi các thứ các bạn thắc mắc gì cứ
[00:26:47] bình luận nhé em ohh còn thêm một câu
[00:26:50] nữa bạn có bạn vừa khỏi luôn đó là mình
[00:26:53] cài cái chim Cài những cái gì Sao sắp
[00:26:56] với tách thì mình đã từng đi ở trên Blog
[00:26:57] của mình rồi nhá
[00:27:00] mình cái hiện tại cái này để cho nó kiểu
[00:27:02] hiển thị ra trông nó đẹp cũng như là
[00:27:07] cũng như là kiểu nó gợi ý các thứ
[00:27:15] ở đâu loạn thì mình mình sẽ
[00:27:19] thì các bạn thấy giao diện nó sẽ đẹp hơn
[00:27:22] tí ghép cốt bằng pp
[00:27:29] thôi bắt đầu buổi hôm nay nhé bố mẹ mình
[00:27:31] sẽ dạy các bạn với cái gì
[00:27:36] Ờ Ờ mình sẽ dạy các bạn về phom được ạ
[00:27:39] bản chất là mình sẽ có một cái phone sau
[00:27:41] đó điền thông tin sau đó thì mình sẽ in
[00:27:43] ra những thông tin mình đã Điên cái rất
[00:27:46] cơ bản như thế
[00:27:49] Anh hiểu sẽ như thế nào trước tiên à tôi
[00:27:53] xóa tên là đi tôi đợi nó tên thằn Phone
[00:28:06] know kahat đồng loại localhost to school
[00:28:07] này
[00:28:10] đó sẽ ra cái phone này cứ đầu đứng nhờ
[00:28:13] đang không có gì không ạ bây giờ sử điền
[00:28:16] thông tin cá nhân đi tên này
[00:28:19] thì bây giờ các bạn sẽ thấy tác dụng của
[00:28:23] nêm này mình sẽ cho Đây là tên đây
[00:28:27] mình sẽ tạm bỏ qua dùng ra suýt va date
[00:28:28] nhá Mình chỉ làm đơn giản theo cậu là
[00:28:32] pho mình Điền xong các thứ thứ thì mình
[00:28:34] in lại những này mình đã Điền thì họ sẽ
[00:28:38] như thế nào ở đây là ngày sinh rồi ạ
[00:28:43] Thì quy tắc đặt nêm này thì giống như
[00:28:46] mọi khi mình hay bảo đó là mình nên dùng
[00:28:49] gạch mình thư da trong này có thể có thể
[00:28:52] dùng nhiều cách có thể ghi có dấu nhưng
[00:28:54] mà không ai làm thế cả bởi vì tí mình sẽ
[00:28:56] phải lấy lại cái này nên là mình khuyên
[00:28:58] các bạn nên là kiểu ghi kiểu dạng là
[00:29:01] gạch dừa nhé hay là kiểu con mặt bàn
[00:29:03] không ạ thường mà mình thích code pp
[00:29:05] mình hỏi anh Dũng bày dứa như thế này
[00:29:07] với ngôn ngữ khác thì người lại thích
[00:29:14] thì nghèo
[00:29:16] email mật khẩu nhưng mình cứ để mật khẩu
[00:29:18] - cho bạn
[00:29:21] các bạn tí các bạn sẽ hiểu tại sao mình
[00:29:25] đang cho điền mày cái thông tin này ở
[00:29:27] đây sẽ là giới tính đúng không ạ giới
[00:29:30] tính
[00:29:32] Ừ vậy thôi tạm nhà trước bạ tạm ngày
[00:29:36] trước cứ làm dần dần đã
[00:29:44] oke tự động viên này
[00:29:45] Ừ
[00:29:48] thôi cái vào ở ẩn danh đi tôi sẽ mở và
[00:29:51] ẩn danh này nó không tự động Điền ừ
[00:29:57] đó à
[00:29:59] Anh
[00:30:02] Đài Giả sử Trong trường hợp như thế này
[00:30:05] chỉ tôi điền tên của tao hỏi nó Hạ Long
[00:30:08] chẳng hạn thường ngày sinh này mật khẩu
[00:30:11] 123 như thế này Sơn tôi là đăng ký nếu
[00:30:14] không thấy là béo có để ý kĩ là trên
[00:30:17] thanh địa chỉ của tôi đề nó đã truyền
[00:30:21] đúng cái một tôi đã Điền ở trong form để
[00:30:25] hai địa chỉ loạn thực À đây Đây là kiểu
[00:30:29] đẩy 7 dữ liệu và đầy dữ liệu kiểu này
[00:30:33] thì nó sẽ gọi là mấy thớt là ghét rất là
[00:30:36] đẩy hết nên anh bị chìm thực là thường ở
[00:30:38] chẳng bây giờ người ta không dùng mải
[00:30:40] miết ghét này để mà đẩy thông tin trong
[00:30:41] form
[00:30:44] mà chúng ta sẽ
[00:30:47] mà sẽ dùng cái thớt post Nhưng mà mình
[00:30:50] cứ để mua qua mấy thứ ghét trước đã thì
[00:30:52] mình sẽ ghi made là ghét trước này và
[00:30:55] mình muốn đẩy xa cái Khoai khác thì ghi
[00:31:03] thì mình sẽ là sẽ có khái niệm mà Action
[00:31:05] mình sẽ nhảy một cái file ở đó là sử
[00:31:10] file này sẽ là file để mà xử lý in ra là
[00:31:13] bạn mình sẽ đặt tên nó là cố xét và xử
[00:31:14] lý đi
[00:31:17] thì tiếng Anh Tím Nếu làm quen với việc
[00:31:18] để tiếng Anh nữa chỗ để tiếng Việt và
[00:31:28] à à
[00:31:30] A và file này giả sử của mình chỉ đơn
[00:31:33] giản là muốn in ra thôi lấy cái gì mình
[00:31:35] đã ngập rồi in ra đúng vai mình đã nghỉ
[00:31:39] thì đây nếu mà chỉ có mỗi thế mà không
[00:31:41] có gì hết pin màu nào thì ông có thể
[00:31:49] thì các bạn phải là không có tí thẻ HTML
[00:31:53] nào như bên này mà sẽ chị là mở thẻ Tt
[00:31:56] là nó loạn sau đó thì tôi thường là tôi
[00:31:58] sẽ xóa luôn cả cái đóng thẻ này Tại sao
[00:32:02] bởi vì đợi Nếu mà file chỉ p thôi mà
[00:32:04] không một tí có gì nữa thì mày ông có
[00:32:07] thể xóa luôn cái thẻ đóng của thẻ pp để
[00:32:10] nó tự động đó như ông Nếu nó không Tự
[00:32:13] nếu mà ông mà để
[00:32:19] ở đây để tôi dạy nha nếu file chỉ pp của
[00:32:22] bọn mà
[00:32:22] khi
[00:32:28] đóng hè sau thẻ đóng có thửa khoảng
[00:32:29] trống
[00:32:32] hoặc ký tự
[00:32:38] đôi khi sẽ lỗi sẽ gây lỗi lỗi là gì về
[00:32:40] sau mình sẽ dạy các bạn Tại sao nó bị
[00:32:42] lỗi đấy tay giả sử là thường là các bạn
[00:32:45] sẽ nghĩ ra là thể pp có bao gồm Mở thẻ
[00:32:47] và đóng thẻ nha nó tự nhiên vì sao tôi
[00:32:50] có một dấu cách là đằng sau cháu cháu là
[00:32:52] biết được là sau này có dấu cách vì nó
[00:32:55] là cách mà nó sẽ nhìn được nó bạn và nó
[00:32:57] sẽ đôi khi nó sẽ sinh các bạn cái lỗ ấy
[00:32:59] nó lỗ không trắm
[00:33:05] Ừ thế thế này là tối khuya là nếu pha
[00:33:07] chỉ p thì mình xóa luôn cả thể đóng cho
[00:33:11] nó đi để nó tự động đóng cho mình một
[00:33:12] tiếp theo là gì mình lấy lại những thông
[00:33:15] tin mình đã nhập để mày ra không ạ thì
[00:33:18] tôi sẽ Khái niệm và tên này bằng đôla
[00:33:22] gạch dưới ghét sau đó thì ghi tên địa
[00:33:25] ngay như này thì tất cả mấy ông đã lấy ý
[00:33:29] tên từ cái ghét và lấy từ trên thanh địa
[00:33:32] chỉ này và để nó ra là sự cái chỗ ở đây
[00:33:35] là bạn đã nhập
[00:33:37] tên cho ạ
[00:33:43] tên là nha à trực tiếp xổ số Quảng Ngãi
[00:33:46] D3 tôi xóa mấy cái chết hay bị chỉ đi
[00:33:48] điện bộ chữ Long rồi chở bạn tôi không
[00:33:52] nhập phải cái gì ở kia ấn mà Mấy ông
[00:33:54] thấy ở trên thanh địa chỉ này tên ngày
[00:33:56] sinh mật khẩu nó vẫn được truyền lên
[00:34:00] nhưng mà nó đang ở trống và tên Sẽ Lau
[00:34:03] bạn nhập tên làm ok rối loạn và bây giờ
[00:34:05] mình sẽ lấy những cái thứ khác về thôi
[00:34:09] họ mình sẽ mình sẽ ra sửa mình điền thêm
[00:34:11] cả thông tin này
[00:34:15] ấn vào các bạn thấy trên thành địa chỉ
[00:34:17] nó được truyền Lên Kiểu như là thứ nhất
[00:34:20] là Nguyễn ngày sinh với đấy thì như tôi
[00:34:22] từng nói là người lập trình thì nó sẽ
[00:34:26] luôn là năm tháng này đoạn ấy cái thử
[00:34:28] Tôi đang định nói nghĩa là đôi khi ạ nếu
[00:34:30] mà ông muốn in đang ngày tháng năm thì
[00:34:32] Miễu ngoại phải format lại phải Định
[00:34:34] dạng lại cái cái đấy còn không mày
[00:34:37] thường là nó sẽ như thế này Ừ
[00:34:45] extension
[00:34:49] And you are pro vậy ạ
[00:34:50] ở đây
[00:34:52] được ạ
[00:34:56] để xem được cái trên thanh địa chỉ này
[00:34:59] của mình mà đúng hạn và mật khẩu thì mấy
[00:35:01] ông thầy ăn Nếu mà đẩy me hết lắm ghét
[00:35:05] lên thì lộ hết mật khẩu như thế này đúng
[00:35:07] ạ nếu không sẽ bảo là
[00:35:09] em chẳng ai nhìn trên mực thánh địa chỉ
[00:35:11] lắm đâu mà Có phải em dùng trên máy của
[00:35:13] em mà sao thằng khác nhìn được trên anh
[00:35:15] địa chỉ của em có gì đúng ạ nhưng mà
[00:35:17] không ờ ờ
[00:35:20] Ừ cái á á
[00:35:23] em thấy khi mà người ta dùng chung mạng
[00:35:27] với ông gần như là họ vẫn có thể dùng
[00:35:29] cái phần mềm để mà bắt được gói mạng của
[00:35:31] ông và ông đang truy cập đến trang web
[00:35:34] nào trừ khi ông dùng VPN được bạn
[00:35:38] thế nên là đấy à nhược điểm này ông dù
[00:35:40] wi-fi chú ấy Hoặc là những cái Trang mà
[00:35:42] là không phải là
[00:35:46] https với cái Trang là http tay với đội
[00:35:48] trang này chẳng hạn thì phê này thì khi
[00:35:50] mà điền những cái thông tin trong form
[00:35:52] nó sẽ không được mã hóa những thành ra
[00:35:55] là ông mà Điền mật khẩu ở trong mấy cái
[00:35:58] Trang đấy thì thì thằng nào mà dùng
[00:36:00] chung mạng của ông nó vẫn thể bắt được
[00:36:02] cái gói tin này của ông giống như ông
[00:36:05] gửi thư ông gửi hư Để cái cái bưu điện
[00:36:07] mình ạ trong thời gian mà cái Thư là
[00:36:09] được gửi đến bưu điện thằng khác rồi bóc
[00:36:12] ra xem được thư của ông đấy thế do nguy
[00:36:18] thế nên việc đầu tiên của mấy ông là mấy
[00:36:21] ông phải đổi mến hết về kỹ thuật ghép
[00:36:23] vào máy ông phải nội nói mới thức post
[00:36:27] và và trong cách của ông lên là https
[00:36:30] bây giờ nó sẽ mã hóa cái trong phòng của
[00:36:33] ông đâu lận hiện tại miếu nó chạy lên
[00:36:35] trình máy của ông thì không sao vì nó
[00:36:40] local thì ông để ATP face được rồi nhưng
[00:36:44] mà nhưng mà nếu mà cả ông ông đẩy cái
[00:36:47] cốt này xanh là ra ngoài mấy ông Thuê
[00:36:49] hẳn một cái Trang web domaine nào đó để
[00:36:53] mèo chạy được cốt này thì bắt buộc cái
[00:36:57] USB phải có ssl tất cả có https không
[00:36:59] những người dùng Điền những cái gì và
[00:37:01] trong cái cái for của ông là thằng khác
[00:37:03] nó cũng thể biết được
[00:37:10] đổi nó hàng mới thấp tốt này à
[00:37:13] xe tải giờ sáng ngập lòng này chẳng hạn
[00:37:16] như này
[00:37:19] nếu không sẽ thấy nó báo lỗi Thủy thứ
[00:37:21] nhất là nó không để 2 địa chỉ nữa nên là
[00:37:24] cái ghét này nó không tìm thấy để chuyển
[00:37:27] để mà lấy cái mà mình đã nhập thì nó nhờ
[00:37:29] đổi ghép thành phó thôi rồi bọn mày ông
[00:37:31] bắt buộc phải viết hoa như này nhá mày
[00:37:33] Ông đừng có lười hiểu biết thường ngày
[00:37:36] mà nghĩ rằng mà nó nó chạy nhá Không tôi
[00:37:38] không phải tự nhiên tối Hưng với em biết
[00:37:40] kiểu nghe đâu ạ và bắt buộc phải đúng
[00:37:44] như thế này nhá Đấy thêm và khi mà ông
[00:37:47] khi ông ấy Ông tải lại cha mày mà gửi
[00:37:50] lại for đấy thì đối với mi thức post thì
[00:37:52] nó luôn hỏi lại câu này béo cứ ăn con im
[00:37:56] thôi cái nó sẽ gửi lại gửi lại phom và
[00:37:58] đương nhiên là lần này vẫn lấy lại như
[00:38:01] bình thường gọn chị ra buổi học hôm nay
[00:38:03] có thể chị ngắn như này thôi như kiểu là
[00:38:06] mấy ông sẽ lấy lấy
[00:38:09] 10 cái phom có một iPhone này rồi mấy
[00:38:10] ông
[00:38:13] ờ ờ lấy toàn bộ những cái đã điên trong
[00:38:16] cái phone này mày in ra ngọn Nếu mà
[00:38:19] trước trước khi mà kết thúc buổi học thì
[00:38:20] đương như là mình sẽ còn thêm những cái
[00:38:22] trường hợp ngoại lệ nữa những cái trường
[00:38:24] hợp gì mình sẽ làm thêm ví dụ là giới
[00:38:32] thì mình cứ để nó thành mới thấy ghét
[00:38:34] trước đi Tại sao bởi vì mình muốn đẩy
[00:38:35] lên hai địa chỉ các bạn Hình dung là
[00:38:37] trên anh địa chỉ nó thể truyền lên và
[00:38:41] những gì nếu bạn hãy cứ để đó là mấy xét
[00:38:42] lại nhé á
[00:38:42] thế
[00:38:45] giới tính này các bạn nhớ vụ Giới Tính
[00:38:49] giới tính thì thật sự đây là nam này để
[00:38:52] nữ này thì cả hai cái này bắt buộc thứ
[00:38:54] nhất là nó radio đấy phép chọn một này
[00:38:57] hay lại bắt buộc phải là cùng chung cái
[00:39:01] nêm đấy nó chỉ chọn một với bọn kẻ nhớ
[00:39:04] ai nam nữ này đúng bọn
[00:39:06] nhà tôi tặng xóa cái này trước đây á gửi
[00:39:08] tôi cho mấy ông dễ Hương Dung xem việc
[00:39:11] là nếu với giới tính mà chọn kiểu như ai
[00:39:13] thì nó sẽ đẩy cái gì để thay Nghị chị
[00:39:15] nhé hiện đầu tiên cho không chọn cái gì
[00:39:18] thì ấn vào này nếu thấy nó chẳng truyền
[00:39:20] đi nên anh bị chỉ cả đúng rồi nó thành
[00:39:21] hỏi chấm nhưng mà chẳng truyền thêm với
[00:39:24] cả Bây giờ sửa kích vào cái này Truyền
[00:39:26] đây này thì giới tính nó sẽ biến những
[00:39:29] hiểu lại thì ngon cơ đúng ạ nghĩa là mấy
[00:39:32] ông phải có hai trường hợp xảy ra là một
[00:39:34] là không truyền lên cái gì cả hai là
[00:39:37] giới tính bằng ngon và giúp của con
[00:39:39] Ồ tôi thích vào cái này thì nó vẫn là
[00:39:42] ngon đúng ạ thì mới ông sẽ thấy à
[00:39:45] Ừ thế thì hơi sai làm sao mình biết được
[00:39:48] là mình đã chọn giới tính nào đúng ạ đấy
[00:39:50] Thì bây giờ mình có va luu cho nó riêng
[00:39:53] kể Rio này mình bắt của Zalo nó ấy hiểu
[00:39:56] mình đã chọn Cái gì là sự đền Nam này để
[00:40:02] ừ ừ
[00:40:12] thế hả Không mình không Bôi đen đâu Mình
[00:40:14] gần control control b là nó sẽ tự động
[00:40:18] đã ký kết một dòng và ấn giữ phím enjoy
[00:40:21] để sửa hai dòng cùng một lúc đấy ạ
[00:40:22] nhà
[00:40:25] mình có thể Bôi đen cả đoạn này rồi mình
[00:40:26] trong Hyundai nó sẽ đáp pi kết cả cái
[00:40:33] cái kiểu như này Bây giờ mình ấn lại nhé
[00:40:37] đó lên giới tính là Nam đúng không Lại
[00:40:39] đây vào đây dự tính cho nữ cây rồi lo
[00:40:43] đấy tương tự thì phải chiếc bóp nhé và
[00:40:46] tiếp theo nữa thì mình sẽ có là select
[00:40:49] sẽ e captions
[00:40:50] chị
[00:40:53] đã sử lần này mình sẽ ở
[00:40:55] sở thích đi
[00:40:59] là Sunny có chân à
[00:41:02] ở đây
[00:41:06] a kinh dị này
[00:41:13] người lớn tình cảm em ạ
[00:41:15] kính Ai
[00:41:18] đứng như là mấy ông sẽ phải cho nó cái
[00:41:25] tôi bấm vào này thì trong trường hợp này
[00:41:28] thì nó sẽ chuyển nếu mà nếu mà mệt ông
[00:41:31] không có cái ba lô cho bé óc chân thì nó
[00:41:34] sẽ lấy đúng cái chữ ở trong óc Trần đến
[00:41:36] biến thành Peru như thế này Nhưng mà
[00:41:37] thường là
[00:41:40] khi người ta đôi khi không lấy được nha
[00:41:41] người ta sẽ ghi thêm valeu cụ thể và cho
[00:41:44] nó chân và value đôi khi nói chuyện một
[00:41:47] hai thôi như tôi từng bảo giới tính mình
[00:41:51] lưu chị ạ 0,1 Thôi thì cái một vài cái
[00:41:54] này nóng thế và lu nó sẽ là số nô này
[00:41:58] lưu nó nó ngắn hơn nó dễ hơn 1 là sẽ hứa
[00:42:01] và kinh dị hay nó sẽ cứ là gì gì đó thay
[00:42:04] vì hiểu lưu lại cả chữ toàn bộ như thế
[00:42:06] này
[00:42:14] ờ ờ tiếp theo còn gì nữa nhỉ Đúng rồi
[00:42:17] bây giờ giả sử là thật sự là mô tả bản
[00:42:24] mấy ông nhớ với khách Alo ạ ạ
[00:42:28] Anh thích alo mình sẽ con lên với nó
[00:42:31] là mô tả à
[00:42:34] Em đang ở nhà mà lần này tôi sẽ cho hơn
[00:42:39] một cái sớm à Thật sự là cuộc đời
[00:42:47] à à
[00:42:52] hãy cảm nhận không phải tôi nó nhắn tao
[00:42:53] ví dụ
[00:42:56] anh đăng ký
[00:42:58] à à
[00:42:59] ừ ừ
[00:43:06] thì tại sao tự nhiên tôi đang phải đề
[00:43:09] cập vụ giải hơn về nó sẽ sai mà sẽ sinh
[00:43:12] ra cái trường hợp này cái sinh ra trường
[00:43:14] hợp và nếu mà ông để mấy thớt cả Ghét
[00:43:17] thì khi mà điền cái gì đó dài quá Để em
[00:43:20] hay địa chỉ họ sẽ bị bào Cái lỗi này đó
[00:43:22] là Thanh địa chỉ của ông là quá tải khóa
[00:43:26] lớn cái thành ra là cậu mấy ông sẽ không
[00:43:29] phù hợp cho việc điền trong phom người
[00:43:32] thương là ghét ạ à mà Mấy ông lên đội nó
[00:43:35] mới rất là top đấy gần nhất
[00:43:39] Ừ thứ hai nữa là nó còn sẽ sinh năm một
[00:43:42] cái kiểu như này Đây đây Tôi cho ông
[00:43:43] thêm một ví dụ nữa
[00:43:47] là sự bây giờ trọ ảnh đi chọn hàng cá
[00:43:48] nhân này
[00:43:59] Cho xem cái ảnh Bút Chì đây bạn đăng ký
[00:44:03] đấy không thấy đẩy lên hai địa chỉ lại
[00:44:05] là tên của cái ảnh nó không đúng
[00:44:08] Ừ kiểu như này Nếu không thể in được ra
[00:44:09] cái ảnh đâu
[00:44:12] khi mà bản chất là mấy ông phải đẩy
[00:44:15] trong mấy thất riêng và đẩy ảnh nhá Khi
[00:44:20] lại đây đẩy file trong phom thì bắt buộc
[00:44:21] phải có hai yếu tố thứ nhất một là mấy
[00:44:26] thớt là pet thứ hai nó sẽ phải mã hóa mã
[00:44:35] cô diện and clip nhờ không làm mẹ andres
[00:44:37] với gì đó Tôi không nhớ chính xác rồi
[00:44:45] ở thời sự phải có cái cụ mày đi kèm nữa
[00:44:48] thì mày không thể truyền được cái file
[00:44:49] ảnh lên
[00:44:53] ở đâu ạ đái
[00:44:54] ở
[00:44:57] kiểu ngày nữa cơ thì mới chuyển được
[00:45:00] file lên đấy ở
[00:45:09] tổng hợp của những cái có thể Điền ở
[00:45:11] trong phone anh đứng ở Tí tôi sẽ có bài
[00:45:13] tập về cho mấy ông dễ hình dung lại méo
[00:45:16] làm những cái bài này chuyện thì cái
[00:45:18] lọng đơn giản thôi Nó là kiểu điên những
[00:45:20] cái gì Thôi ra những cái mình đã điên
[00:45:22] thế thôi mà đúng không ạ
[00:45:24] em không có thể nhanh phết nhỉ 8 rưỡi
[00:45:27] cũng xong hết toàn bộ những cái hôm hôm
[00:45:30] nay học rồi Nếu mà tiếp theo là bây giờ
[00:45:31] mình sẽ
[00:45:36] cô dạy qua các bạn về à hồ sơ đồ khối sơ
[00:45:38] đồ khối
[00:45:41] Thực ra là cái sơ đồ khối là đáng lẽ là
[00:45:44] thường là hồi mình dạy học đấy thì sơ đồ
[00:45:48] khối mình phải học trước cả hồi học thế
[00:45:51] nào ngôn ngữ lập trình cơ sơ đồ khối
[00:45:54] thuật toán để làm gì để các bạn hình
[00:45:58] dung rõ hơn về cái việc đó thế nào là
[00:45:59] trình
[00:46:00] họ
[00:46:03] lập trình bệnh là thơ ca giải quyết
[00:46:06] những cái giải quyết những cái mà kiểu
[00:46:09] bất bất kỳ cái gì mất cái gì gỗ trong
[00:46:13] cuộc sống này thay bị bê Bây giờ tôi
[00:46:14] thường hay ví dụ cho sinh viên kiểu như
[00:46:16] thế này đó là kiểu Hòa
[00:46:19] Tôi thường này bảo sinh viên hãy nói các
[00:46:21] bước để mà
[00:46:25] mày em ra lấy cốc nước chẳng hạn thì
[00:46:26] Ê
[00:46:29] mấy ông ca không cần phải nghĩ nhiều về
[00:46:31] cái việc đấy nữa thì mày ông cậu bây giờ
[00:46:34] chắc là không nào cũng lỗi là không nghĩ
[00:46:37] việc lấy nước như thế nào nó ạ đâu chỉ
[00:46:40] đứng dậy mà lấy thôi đấy mấy ông từ đó
[00:46:43] đơn giản như thế Thực ra đối với với máy
[00:46:46] tính thì nó sẽ không có kiểu nó không có
[00:46:48] trí tuệ mình sẽ phải ra lệnh cho nó từng
[00:46:51] câu lệnh 1 để nó làm từng hành động một
[00:46:55] để mà lấy để mà
[00:46:58] gì để mà làm từng bước từng bước gọn
[00:47:10] thì thì thấy cái số cái để nó từng bước
[00:47:12] từng bước ấy thường là ví dụ để mà lấy
[00:47:15] cấm nước xem ạ này có nước nhé
[00:47:19] bản chất là bước 1 thì sẽ là cậu
[00:47:22] ý là đứng dậy làm trà sử các bạn đang
[00:47:25] đầu tiên là kiểm tra có đang ngồi không
[00:47:30] dám ngồi không đúng ạ Nếu có thì có thì
[00:47:35] lấy kiểu kiện như thế còn nếu đứng sẵn
[00:47:39] rồi đi Thôi đủ rồi sau đó thì
[00:47:44] xong rồi xác định là xác định bình nước
[00:47:48] ở góc nào đúng ạ Để để quay về góc đấy
[00:47:51] đúng không ạ Đấy sự chọn khi mà xác định
[00:47:54] đồ rồi thì mới bắt đầu kiểu bước bữa đi
[00:47:55] được ạ
[00:47:58] sau bước đi bước từng bước một đúng ạ
[00:48:01] đấy Kiểu thế rồi Cái quan trọng là bước
[00:48:04] đi là xong rồi cứ bước từng bước rồi ông
[00:48:07] lại phải kiểm tra lại việc lắm
[00:48:08] ý
[00:48:51] anh alo
[00:48:55] Có chó mình Sủa con mèo hàng xóm mà mèo
[00:48:58] hàng xóm thì nó Cứ thỉnh thoảng qua đòi
[00:49:00] ăn
[00:49:03] à mà nhà mình thì thích nuôi chó mèo
[00:49:05] thấy là nó cũng Arsenal nên lại cho nó
[00:49:09] nếu mà đi rằng nó nó quen vui rồi lại
[00:49:12] qua nhiều quá nhiều thì chó sủa đánh đấy
[00:49:13] một phòng học được ổn Đấy
[00:49:14] ở
[00:49:17] thời tiếp theo nhá
[00:49:20] Khi mình bước đi mình sẽ phải luôn xác
[00:49:24] nhận lại luôn kiểm tra lại kiểm tra xem
[00:49:31] và và nếu mà có chướng ngại vật thì mình
[00:49:33] lại phải mẹ Nó đứng ở chỗ phải hoặc tui
[00:49:35] cất nhắc có ông thì kiểu còn kiểm tra
[00:49:38] xem là chứng lại vật đấy có càng trở nhớ
[00:49:40] hay không Nếu mà nếu mà nhiều thì mình
[00:49:43] có nếu mà cảm thể nhiều thì mình mới Bé
[00:49:46] nó còn không thì mình cứ đâm đầu mà nó
[00:49:48] không mình nhảy qua Vân Vân Vân chúng nó
[00:49:51] có rất nhiều cách đấy thì thì toàn bộ
[00:49:53] những người đấy Thực ra là não mình Bây
[00:49:54] giờ
[00:49:58] mình đủ phát triển này Mà mình xử lý ra
[00:50:00] đấy trong vòng vài giây rồi mà mình
[00:50:02] không ở phải nghĩ nhiều rồi cái việc đấy
[00:50:04] Mình chỉ làm mình hứng lên lấy cốc nước
[00:50:08] thì mình đấy thôi đúng ạ đấy Nhưng mà
[00:50:10] đối với máy tính thì mình sẽ phải phải
[00:50:12] ghi cụ thể từng từng bước từng bước ra
[00:50:16] một mình thiếu ở nước nào mà tự nhiên có
[00:50:19] một cái vấn đề gì đó dầu tự nhiên có
[00:50:21] chướng ngại vật ông ông mỗi cứ cắm đầu
[00:50:23] cho cái robot để cứ cắm đầu đi thôi chả
[00:50:25] bạn vẫn tự nhiên có cái trứng này vật ở
[00:50:29] đằng trước nó không lường được nó tém
[00:50:31] hai cái thứ lúc đấy nó làm sao bước đi
[00:50:34] nữa đúng ạ Đấy thì méo mà càng kiểm tra
[00:50:38] những cái đấy thì thì thì con robot của
[00:50:41] ông có vẻ càng ngon càng tốt đúng ạ Làm
[00:50:44] lập trình bản chất nó là như thế thôi đó
[00:50:46] là cá tính hết trước tất cả các trường
[00:50:49] hợp sau đó thì ghi ra cho máy tính để
[00:51:08] hình ảnh
[00:51:14] Ok thì bây giờ mình sẽ thử
[00:51:18] đầu tiên là cho các bạn xem lại về Cái
[00:51:22] cái sơ đồ mà hôm trước mình có có cái
[00:51:25] ảnh ấy và đây được sơ đồ khối thuật toán
[00:51:28] đi mình có lẽ ảnh ông trước nó cũng
[00:51:29] tương đối rồi
[00:51:32] Ừ để các bạn hình dung về những cái hình
[00:51:33] này này
[00:51:36] những cái hình mà các bạn thường phải có
[00:51:38] ở trong cái sơ đồ khối
[00:51:42] ạ sau đó thì mình sẽ thử chỉ các bạn vẽ
[00:51:44] một cái thứ gì đó được bọn
[00:51:45] Ê
[00:51:51] mấy ông thường ai lên có thể lên cái
[00:51:54] trang dro.io Tôi tưởng ai dùng này để mà
[00:51:58] vẽ sơ đồ toán này hãy thậm chí sơ đồ hồ
[00:52:01] sơ đồ cơ sở liệu 2 sơ đồ trực thể tội
[00:52:29] đầu tiên thì các bạn sẽ phải luôn có cái
[00:52:31] bắt đầu và kết thúc phải biết đồ lúc mà
[00:52:32] bắt đầu lúc nào kết thúc của một cái
[00:52:34] chương trình được ạ thì nó Hình hình này
[00:52:36] hình bắt đầu rồi không ạ thử thưởng
[00:52:47] a beginner ngắm cái sẽ là em chẳng hạn
[00:52:50] đúng ạ chiều kiểu ngay
[00:52:54] sau đó thì mày không thể biết mấy cái
[00:52:54] bất kỳ đúng không ạ
[00:52:57] [âm nhạc]
[00:53:00] Nếu có thể viết là kiểu chuyện tình của
[00:53:03] đời ông nó sẽ như nào sẽ một vòng luẩn
[00:53:12] Đợi tí nha cho con mèo An Phát đã hai
[00:53:56] ừ ừ
[00:54:00] anh alo alo alo em mèo trên 18 tuổi
[00:54:11] à à
[00:54:16] ông kia đang ghi từng bước thôi
[00:54:20] quá trình cho mèo ăn
[00:54:23] con mèo đấy nó còn ăn thức ăn cho chó cơ
[00:54:26] đẩy cái gì nấu ăn có con chó là tôi có
[00:54:28] vẻ không chịu ăn hạt
[00:54:30] Vì thế nên là mua cái hạt có tiền lãi
[00:54:34] rồi cùng bây giờ cho mèo hàng xóm ăn
[00:54:36] Ok thôi quay lại này Đầu tiên thì giờ
[00:54:39] sửa tôi được Cứ thử mô tả qua cái cái
[00:54:43] cuộc tinh của đa số mấy ông đi ông ạ
[00:54:46] Không biết có động chạm gì không nhưng
[00:54:48] đại khái là cậu mục tiêu lúc đầu Giả sử
[00:54:50] một tiếng lúc đầu là kẻ o o
[00:54:53] Ừ Tôi muốn tìm bạn gái ạ đúng ạ ta sẽ
[00:54:55] được
[00:54:59] cái nhập này là để người dùng nhập vào
[00:55:00] nhá á
[00:55:02] chứ không phải nhập lương mép màn anh
[00:55:05] nhá cái cái xử lý tính toán này đôi khi
[00:55:08] là nó sẽ là để mà hiển thị ra nữa
[00:55:10] Ừ hai cái đôi khi bị nhầm đấy thử cả hai
[00:55:12] này nói cuộc chung lại được thì chị gia
[00:55:16] này dễ hiển thị là là sự nó bao gồm một
[00:55:20] câu nói là nó được Kiều Tôi
[00:55:23] muốn có người yêu Dạ
[00:55:27] anh kể nha và đương nhiên là nổi đến
[00:55:33] tổ tiếp thế nào ạ
[00:55:35] anh em luôn đi lại mưa
[00:55:38] tiếp tiếp theo là kiểu đi tìm đúng không
[00:55:40] ạ Đi tìm là hành động hành động này sẽ
[00:55:45] là xử lý nó sẽ là hình
[00:55:47] thực ra là cái này thì nó hơi say Vậy
[00:55:50] phải mình xem mặt tí những cái xử lý nó
[00:55:52] hình bình hành cơ
[00:56:03] sản xuất ra kết quả sâu ra kết quả của
[00:56:06] đội hình bình hành Châu Huệ sai sai
[00:56:09] Ừ vậy để xem lại đã lâu lắm rồi không
[00:56:18] Ẩm Thực ra là chỉ làm với mức tương đối
[00:56:22] thôi mình mình không rõ được là cái hồi
[00:56:26] của mình học đúng đây cái xử lý mà sẽ
[00:56:28] giải hình này bao gồm các xử lý
[00:56:32] xe tải cứ ghi ngay
[00:56:49] chỉ có như thế này sau đó thì
[00:56:52] tìm được chưa đúng không
[00:56:55] cái cái câu điều kiện này các bạn phải
[00:56:57] luôn nhớ nhé câu điều kiện này nó sẽ gần
[00:57:00] như chị trả về chua phone thôi mình mình
[00:57:03] không làm đi có xích cay cậu là kiểm tra
[00:57:05] với nó ra được rất nhiều kết quả không
[00:57:07] mình nên chỉ trả về chua phô nó chuẩn
[00:57:10] tay giờ sửa là tìm được chưa Nếu mà chưa
[00:57:13] thì mình mình sẽ có hai cái ở đây không
[00:57:40] xe tải
[00:57:45] ăn canh cái nổi nó hơi bị
[00:57:48] khi tách Ok Lúc nãy giờ chồng có phải
[00:57:54] xe tải mình sẽ ra
[00:57:58] Có không đó chỉ có không thôi
[00:58:01] Đúng Sai sai cả
[00:58:04] sai thì quay lại tìm người yêu đúng ạ
[00:58:15] Ê mấy ông cãi nhau gì ở kia vậy
[00:58:22] nhà mình có thể kiểm tra tiếp từ Google
[00:58:24] sử gặp
[00:58:27] họ có chấp nhận mình không họ có yêu lại
[00:58:29] mình không đúng mà Vân Vân Vân họ có phù
[00:58:31] hợp không đâu ạ Họ phù hợp không hiểu
[00:58:38] khi tìm được phát quê luôn
[00:58:41] cái kiểu thế đúng không ạ thì nó lại có
[00:58:44] xảy ra 2 trường hợp nữa đúng ạ Nếu mà
[00:58:46] giờ xử sai thì lại quay lại tìm không ạ
[00:58:54] xe
[00:58:57] tải Nếu mà say được ạ
[00:59:00] à à
[00:59:02] ở mấy cái này mấy ông nhìn dễ hiểu mà
[00:59:15] anh không em thường ta có thể có nhiều
[00:59:26] Đã họ có phù hợp không Nếu mà đúng thì
[00:59:28] sẽ là kiểu giả sự là
[00:59:32] áo cưới đủ ạ đại khái Thế mình có thể ở
[00:59:34] đây chốt một cái to đùng ở đây là
[00:59:35] Áo
[00:59:39] Cưới Sau đó kết thúc mọi cuộc đời Kiệt
[00:59:45] anh như này những bài toán ở đây mấy ông
[00:59:46] thấy thời gian vòng lặp kiểu này là
[00:59:49] không đúng là không tốt Vậy sao Bởi vì
[00:59:52] nếu nếu mà kiểu bé ông nghĩ trường hợp
[00:59:55] là thứ nhất là kết quả chung quy trở lại
[00:59:58] có mỗi cưới không ổn đúng không ạ
[01:00:01] về cuộc đời của mấy ông chắc hổ khi quay
[01:00:04] quần đi quay quần lại kịp với yêu
[01:00:06] em mãi là không nên thời đại khái thế
[01:00:10] hoặc à Mấy ông chỉ cần kiếm kiếm đến
[01:00:12] khoảng tầm ba bốn lần ở mấy ông đã chán
[01:00:14] rồi nếu không một kiếm nữa mày ông muốn
[01:00:16] độc thân luôn thì sao Đúng rồi thì miếng
[01:00:18] sẽ phải kiểm tra thêm điều kiện ở đây
[01:00:23] nữa là kiểm tra là là nếu mà nó ba lần
[01:00:24] rồi chẳng ạ
[01:00:28] ba bốn lần rồi ba bốn lần mà hạch liên
[01:00:31] tiếp thì mới ông sẽ có thể cho ra kết
[01:00:34] quả đấy luôn đúng ạ Là là kiểu độc thân
[01:00:37] thì đại khái Thế đây để tôi thử sửa lại
[01:00:38] cái này nhé
[01:00:41] đẩy cái này lên trên cho mấy ông mình để
[01:00:45] sửa đây ạ khi sex
[01:00:51] ừ ừ
[01:00:53] ở
[01:00:56] thời tiết đầu tiên là vẫn quay lại kiếm
[01:00:58] người yêu thì lần này mình sẽ là
[01:01:08] Ừ đợi thế nó sẽ không quay hận về đây
[01:01:09] nữa
[01:01:10] à
[01:01:13] mà nó sẽ có thêm một bước kiểm tra đây
[01:01:24] Ừ kiểu như này
[01:01:33] à Đủ ba lần chưa học đủ ba lần kiếm chưa
[01:01:36] cả tự nhiên lúc đầu là chưa thì sẽ là
[01:01:53] hỗ trợ đi rồi chồng trò nói chồng chồng
[01:01:55] đẹp đẹp một tí
[01:02:13] ở
[01:02:15] trong trường hợp
[01:02:19] a b trong trường hợp nếu mà sai thì mình
[01:02:21] có hạnh kiểm tiếp Còn nếu mà đúng thì
[01:02:25] sao Nếu mà đúng thì mình sẽ là nhảy đến
[01:02:29] một cái gì đó nó ạ Mình sẽ nhảy đến cái
[01:02:37] Ê độc thân thôi trở lại
[01:03:00] cô gái méo hoàn toàn có thể làm như thế
[01:03:02] này à
[01:03:04] Ừ cái này Thực ra là nó bị Hơi bị lỗi
[01:03:07] còn là nhìn cho khỏe hơi khó đã lẽ cái
[01:03:10] đoạn này của tôi làm kiểu chéo chéo hợp
[01:03:16] à à
[01:03:27] Ừ nó kiểu chấm như thế này ok rồi đấy ạ
[01:03:30] ở đó đây đây đây là một cái sơ đồ khối
[01:03:33] rồi các bạn sẽ Hình dung là nó sẽ vòng
[01:03:35] lặp kiểu như hai nó sẽ kiểm tra theo
[01:03:38] thành công theo thất bại và từ từ nghệ
[01:03:41] thường là mấy ông sẽ làm cái sơ đồ khối
[01:03:44] hoặc gặp mã Dạ như thế này trước sau đó
[01:03:46] mới ông ấy nhảy sang cốt Nếu không phải
[01:03:48] từ cái sơ đồ khối này sẽ sinh ra mã ra ở
[01:03:52] đây sẽ kéo là lúc đầu sẽ xử lý như thế
[01:03:55] nào in ra cái gì sau đó thì lên vòng lọc
[01:03:57] khoai điểm còn for gì đó đúng không ạ
[01:04:04] Vì sao sau đó thì mày ông làm tiếp chọn
[01:04:07] nhưng mà luôn nhớ là phải có big in và
[01:04:09] em hai cái này nó thể hai kết thúc khác
[01:04:12] nhau Tôi không nói kế hút vào nó có hậu
[01:04:14] hơn nhưng kiểu gì cũng sẽ phải lùn AD
[01:04:17] nhé Nếu ông không quay lại nối tivi nói
[01:04:19] nhá Không không có chửi ở trường quay
[01:04:21] lại bình yên Đây nhá không có Nó quay
[01:04:25] lại được đến đây thôi cái kiểu thế
[01:04:27] có kháng thể có thể không phải đủ ba lần
[01:04:30] kiếm chưa có thể đủ 30 tuổi chưa rằng
[01:04:34] lại đủ ví dụ đủ 70 tuổi này rồi mày
[01:04:37] không sẽ ra đủ 70 chưa đúng không ạ
[01:04:39] Nếu mà chưa đủ 70 thì vẫn còn chinh
[01:04:41] chiến tiếp Còn nếu mà đủ rồi thôi an
[01:04:44] phận độc thân
[01:04:47] Ừ nếu không chạy mặt mình tắt 70 tuổi
[01:04:49] vẫn chưa kiếm được béo cũng nên cứng
[01:04:55] Ok thế này đủ dễ hiểu cho mấy ông qua về
[01:04:58] cái sơ đồ khối chưa và từ đây mày ông sẽ
[01:05:06] mọi người Chắc hết rồi
[01:05:10] à Bố mày sẽ ra dạy qua như thế để buổi
[01:05:13] sau mình sẽ khá là nhiều khá nhiều bạch
[01:05:16] tập cũng như kiến thức vì nó sẽ mới hơn
[01:05:18] khá nhiều
[01:05:22] ở Hà Nội mua chị cách nộp bài cốt bằng
[01:05:24] pp đúng không Thế là các bạn đăng lên Ít
[01:05:27] hấp thôi các bạn đăng ký hấp
[01:05:30] là được nhưng mà mỗi tội là không chạy
[01:05:34] trực tiếp trên đấy các bạn đăng ký hát
[01:05:36] và gửi cho mình link biết hát về mình
[01:05:38] xem thôi nhọn tạo Zippo trên này sau đó
[01:05:40] thì tăng đang cốt lên bình thường mà gửi
[01:05:42] cho mình cái link của cái Zippo đấy là
[01:05:45] được đóng bạn gửi mình depot kiểu như
[01:05:48] này anh mình sẽ Xem cốt được trên này là
[01:05:51] được mà nó không ạ Thực ra là bài tập
[01:05:53] này thì à
[01:05:55] em vẫn chưa đến mức là khó lỗi cần phải
[01:05:58] Chữ Lắm những cái buổi sau nữa cơ thì
[01:06:00] chắc Sào Nam mỗi bạn sẽ làm Nếu hiểu
[01:06:02] riêng mà lúc đấy mình sẽ
[01:06:05] mình sẽ phải chữa cũng thể tưởng bạn sau
[01:06:07] đây
[01:06:11] Ừ ok các bạn còn thắc mắc gì nữa không ạ
[01:06:13] Không thì mình sẽ kết thúc sớm buổi hôm
[01:06:17] nay rồi mình sẽ gửi các bạn cái phone
[01:06:18] này các bạn đăng ký
[01:06:22] đăng ký để mà theo cặp nhé làm việc theo
[01:06:23] cặp
[01:06:26] từ từ mày ông ở đây Sao mày không cũng
[01:06:29] đang mong ông nào sẽ
[01:06:31] chị sẽ vào nhóm với bạn Phương Linh trả
[01:06:36] lại mấy bạn nữ từ Thế nếu không vào nhóm
[01:06:38] mấy bạn đấy thì phải rảnh mình vẫn đấy
[01:06:41] nhé Đừng để dành lại nhé nó hơi bị thản
[01:06:44] thương tí ý
[01:06:56] Ồ không tôi không khuyến khích mẹo làm
[01:06:58] nhỏ một người lại nhóm những nên làm
[01:07:01] kiểu tập thể một tí để mà mình quen với
[01:07:03] việc làm Đồng Đội
[01:07:04] à à
[01:07:07] Ý mình là không nên kiểu làm cá nhân bởi
[01:07:09] vì đi làm thì mình cũng làm có tập thể
[01:07:12] mình có quen việc à Bởi vì làm tập thể
[01:07:15] đấy còn việc lạ đầy cốt cho nhau như nào
[01:07:18] ra việc nhau như nào có dư thứ nó sẽ hợp
[01:07:28] nghe có phần góp ý ai bạn nằm trong cái
[01:07:31] pho mày có góp ý cũng được được được
[01:07:34] được thì mình xem lại các bạn muốn nhắn
[01:07:37] nhủ cái gì nữa không ạ nhắn nhủ có thể
[01:07:38] không phải nhắn nhủ có thể nhắn gửi cho
[01:07:42] mình hòa nhắn nhủ là kiểu là kiểu em
[01:07:45] muốn tìm bạn kiểu cao to đen hôi ẩn các
[01:07:48] thứ tư nữa thì thôi còn sắp xếp trả nặng
[01:07:49] thế lúc bạn
[01:07:52] anh không Bạn nào Nói chung là bạn nào
[01:07:56] mà muốn bảo vệ đoán Muốn Nói chung là
[01:07:58] bây giờ nó vẫn là trên tinh thần tượng
[01:08:00] biện mà Mấy ông thực sự muốn thành công
[01:08:02] thì mày không phải cũng tự tin lên rồi
[01:08:05] Mày Ông cũng sẽ phải tham gia đêm Lúc
[01:08:06] đầu bây giờ sẽ sáng là
[01:08:09] tôi không hướng đến cho những cái bạn mà
[01:08:11] giỏi sẵn rồi Tôi đang hướng đến những
[01:08:13] cái ông mà chưa biết thì gì méo vẫn sẵn
[01:08:17] sàng và tham gia vào vì mình không mất
[01:08:19] cái gì cả quan trọng mình không mất gì
[01:08:23] cả đúng để bà cậu mình sẽ học hỏi và
[01:08:25] mình sẽ tự cố gắng thấy mình còn thiếu
[01:08:29] cái gì và thấy các bạn kia cũng giỏi như
[01:08:31] nào thì mình sẽ càng phải biết phấn đấu
[01:08:34] đúng không ạ Chứ mấy ông ở cơ bảo theo
[01:08:37] kiểu theo kiểu bị tự ti và nhược trí
[01:08:40] theo kiểu là em sợ vào làm tại cho các
[01:08:43] bạn đấy hay gì đó em thấy các bạn đấy
[01:08:47] Giỏi quá Vân khi thế là chết rồi Thế là
[01:08:50] con ngựa các bạn đấy khi bé luôn thiếu
[01:08:54] nhân lực kéo là toàn những ngày ông Giỏi
[01:08:57] vãi chưởng hoặc là những chảo rán đi làm
[01:09:03] dọn nên làm nếu cứ họ thỏa mãn đăng ký
[01:09:06] có số thứ không sao đâu
[01:09:09] anh và tôi tôi thì tuy nhiên là khi mà
[01:09:12] tôi chấm đồ án cũng như là khi mà tôi
[01:09:15] kiểm tra Sở sẽ có kiểm tra
[01:09:23] tôi kiểm tra tiến trình các bạn đấy thì
[01:09:25] tôi sẽ
[01:09:27] khi cha cũng dễ hả
[01:09:29] khắt khe một tí
[01:09:33] bởi vì nó Tôi sẽ cho mấy ông này hình
[01:09:35] dung việc thì đi làm nó sẽ như nào các
[01:09:37] thứ thuốc
[01:09:40] lưu này này ổn không Lúc này này chắc
[01:09:42] lại nó hấp dẫn so với khá nhiều ngày mấy
[01:09:47] à
[01:09:50] Tôi đang nghĩ là không biết cái form nó
[01:10:00] anh béo ở đây tranh thủ khi gợi ý trước
[01:10:03] luôn cho tôi đi là do mày cần phải điện
[01:10:06] lại cái gì tôi đang định là để cho link
[01:10:09] Facebook ở đây để để mà tôi sẽ không hẳn
[01:10:11] kết bạn rồi tôi sẽ nhắn tin với mấy bạn
[01:10:14] đấy Tôi sẽ tạo nhóm chat cho mấy ông này
[01:10:16] mấy ông chat
[01:10:20] anh có thể một cách anh như thế Tôi đang
[01:10:27] ừ ừ
[01:10:51] Hạnh for này chắc là sẽ là mình sẽ chốt
[01:10:55] đến chủ nhật tuần sau nhé mình sẽ bóng
[01:10:59] đóng form vào cuối tuần sau để mà bề để
[01:11:03] mà mình chốt những ngày sau đó mình sẽ
[01:11:05] random những ai vào nhóm nào cũng thương
[01:11:08] rồi à
[01:11:10] à à
[01:11:12] cho tôi cho mấy ông Linh facebook hay
[01:11:14] các thứ thứ rồi mấy ông có gì tự liên
[01:11:32] ngày à
[01:11:34] hai năm nữa
[01:11:47] à à
[01:11:51] ở đầu tiên thì tôi bắt mày không phải
[01:11:54] có phải có cái vụ thì được phép điện một
[01:12:04] bộ phim sex hay Điền email này
[01:12:06] có
[01:12:39] Đi học vui hoa cà bạn kia ở nói nó sẽ ra
[01:12:47] dùng từ ghi chú ổn nó nhỉ Tự nhiên tôi
[01:12:48] giúp ăn quá
[01:12:50] Xin Kiểu đại khái Tôi muốn cho mấy bạn
[01:12:52] này có thể ghi thêm các chú thích gì gì
[01:12:54] đó
[01:13:00] Anh hiểu đế tệ bạn đấy kiệu sạch sữa là
[01:13:04] kéo em chỉ muốn với bạn nữ em chỉ hướng
[01:13:06] muốn với bạn nam đại khái thế tôi nói
[01:13:09] thế mày không không được mấy ông đi cái
[01:13:11] đấy vào thôi không quan tâm nhé Tôi sẽ
[01:13:19] Anh tên this code không tặng bộ qua mấy
[01:13:21] cái yếu tố this code các thứ thứ
[01:13:23] Facebook về mẹ Đông nhiều người dùng
[01:13:30] ở mấy cái giới tính có tình trạng hôn
[01:13:32] nhân lại vân vân thì mấy ông từ link
[01:13:36] Facebook của mình tự biết nhé để họ ok
[01:13:46] anh gửi cho thế rồi có mỗi hai cái này
[01:13:47] thôi ông ạ
[01:13:54] Ừ Ok chờ tí rồi gửi cho mấy ông cái link
[01:14:04] ở trình độ trình độ máy em sẽ tự tự biết
[01:14:06] nhau trình độ nha thôi ông ạ
[01:14:09] Nếu mà nhóm yếu thì được là năm yếu thì
[01:14:11] làm cái máy quét đơn giản thôi cũng được
[01:14:15] mà đúng ạ Chúng ta sẽ khô cố gắng làm
[01:14:17] cái gì đó thôi chúng ta không cần việc
[01:14:19] so sánh mình với bất kỳ ai như tôi từng
[01:14:21] nói nó kiểu ông kia với người có nhiều
[01:14:25] người ta lương cao lương của mình chỉ
[01:14:37] à à
[01:14:38] Ừ
[01:14:41] ok Nói cho đại khái như thế à
[01:14:44] Ẩm Thực ra là có nhớ bạn ở đây ví dụ bạn
[01:14:46] kia bảo nó không thích làm theo nhóm
[01:14:48] hoặc là thận Thế là các bạn còn bị hứng
[01:14:50] Nội kiểu không quen làm việc theo nhóm
[01:14:53] cũng như là không mà bảo vệ đồ án được
[01:14:57] vân vân thì cái này được hơi khó vì đi
[01:14:59] làm thực tế các bạn cầu gì cũng sẽ phải
[01:15:03] gặp thôi Thế là tôi đang hướng đến cùng
[01:15:05] đến cho các bạn có quen được kiểu môi
[01:15:07] trường đi làm được họ sẽ có những cái
[01:15:09] khắt khe có những cái bắt buộc phải là
[01:15:13] không phải vì thiếu cái gì là được nhưng
[01:15:14] mà đỡ như là tôi cũng sẽ không yêu cầu
[01:15:17] quá gắt hẹn gặp người mấy bọn đấy bắt
[01:15:19] mấy bạn đấy phải trong ngày nào nói
[01:15:21] chuyện với bạn kia hai cái gì đó Nói
[01:15:23] chung là mấy ông có phải tự sắp xếp với
[01:15:25] nhau đúng không ạ quen được việc có thêm
[01:15:27] một đồng nghiệp đi đúng ạ
[01:15:29] ừ ừ
[01:15:31] Em không quen làm việc theo nhóm ở nhiên
[01:15:33] bây giờ phải quen em thôi ạ đúng không ạ
[01:15:37] chẳng ai lúc đầu quen cả Và thậm chí A
[01:15:39] quen rồi có thể con ghét cứ hỏi quen rồi
[01:15:43] thích tôi đã từng khẳng định với nhiều
[01:15:45] sinh viên của tôi đó là rất nhờ bạn
[01:15:47] nhiều bạn là bạn thân thật chứ người yêu
[01:15:50] bạn nhỏ hẳn hoi nhé Làm cùng chung đồ án
[01:15:52] xong chia tay
[01:15:54] tôi không lạ gì những cái trường hợp với
[01:15:58] cả tôi không Tôi không
[01:16:01] vì nó không bảo là mày ông cậu làm xong
[01:16:04] sẽ thân nhau cái gì đó nó chỉ nói là
[01:16:07] quen với việc đấy nhà thiệu về sau đi
[01:16:09] làm Mẹ không được chọn đồng nghiệp đâu
[01:16:11] trừ khi ông trước khi ông một con sếp
[01:16:15] không ạ Thôi bây giờ nói chúng lại khá
[01:16:19] như thế mày ông tôi từ trước này tôi dậy
[01:16:22] sinh viên nó cũng là như thế sẽ Hai
[01:16:24] người cùng một nhóm A
[01:16:26] Ừ nếu mà lẻ ông nào ra thì tôi sẽ xem
[01:16:29] sex không ạ nhưng mà này sẽ chỉ là một
[01:16:32] ông mà chị có chuyện này hay ông 23 ông
[01:16:36] gì đấy không ạ Thôi Phạm Huy nhé
[01:16:40] Thế thôi Gửi cái link này sẽ gửi link
[01:16:43] này cho mấy ông ở bình luận của video
[01:16:44] này sau nhé
[01:16:52] số karaoke tạm bộ Hôm nay chắc là thế
