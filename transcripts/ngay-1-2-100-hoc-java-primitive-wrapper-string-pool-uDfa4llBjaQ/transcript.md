# Ngày 1+2/100 học Java - Primitive & Wrapper + String Pool

- Video ID: `uDfa4llBjaQ`
- URL: https://www.youtube.com/watch?v=uDfa4llBjaQ
- Published: 2026-01-12
- Duration: 2h 07m 54s (7674s)
- Language: vi
- Subtitle source: auto
- Kind: live

## Transcript

[00:00:15] à thông cảm. Bây giờ mình vừa mới vừa
[00:00:19] mới cài lại môi trường trên máy này. Nếu
[00:00:24] các bạn để ý thì đây sẽ là mánh m không
[00:00:28] còn là Windows nữa nên là ừ mình vừa
[00:00:32] phải cài lại các thứ xong. Thực ra là
[00:00:35] camera thì đang dùng camera của Ma đấy.
[00:00:37] Không phải camera cũ. Mic thì vẫn là mic
[00:00:40] cũ.
[00:00:42] Nhưng mà đấy, đây cũng là sẽ sự trở lại
[00:00:45] khi mà mình cũng có thay đổi đó là chúng
[00:00:47] ta bây giờ chúng ta sẽ học Java. Ờ đầu
[00:00:50] tiên cái ảnh thăm thì mình vừa rồi mình
[00:00:52] vừa dùng Germany để mà tạo ra cái ảnh
[00:00:57] thăm nhưng mà ảnh đấy nó to ấy, nó kích
[00:01:01] cỡ 7 m à. Xong mình thử tăng lên thì
[00:01:05] không được bả chỉ được hai m thôi. Mình
[00:01:07] bảo sửa lại thì Germany có vẻ cá nhân
[00:01:11] mình đến thời điểm hiện tại mình dùng
[00:01:13] dùng Gemini mình vẫn rất khó chịu. Không
[00:01:16] biết là mấy có chuyên gia prom nào ở đây
[00:01:19] không để mà nói việc là kiểu dùng mini
[00:01:23] tốt hơn. Cá nhân thì mình thì mình thích
[00:01:25] a trò chuyện hay nói chuyện với chatt
[00:01:28] khá là nhiều tốt hơn.
[00:01:31] À đây nói chuyện nhá. Còn code thì đương
[00:01:33] nhiên chúng ta bây giờ hàng đầu vẫn là
[00:01:35] cloud đúng không ạ? Thực ra tôi cũng
[00:01:38] không biết phát âm mấy từ đấy lắm nên là
[00:01:40] từ tiếng Anh có gì bỏ qua nhá.
[00:01:44] Anh học Java có lên Spring không? Ờ thực
[00:01:49] ra mình có nghe nói Spring này như là
[00:01:51] framework của
[00:01:53] framework của Java. Và ừ mình sẽ đầu
[00:01:57] tiên mình nói qua mục tiêu của cái khóa
[00:01:59] học này đã nhá. Thì mục tiêu khóa học
[00:02:02] này đó là
[00:02:04] như các bạn đã biết thì mình xuất phát ở
[00:02:06] từ PP đúng không ạ? Thực ra mình có học
[00:02:09] Java hồi học ở trường rồi nhưng mà
[00:02:13] trường đấy là kiểu trường nghề ấy thì nó
[00:02:15] sẽ học kiểu khá là kiểu chỉ à thiên về
[00:02:20] thực hành hơn là lý thuyết là một việc
[00:02:23] là bởi vì là bọn bọn mình hồi đấy là có
[00:02:26] vững PP rồi nghĩa là làm xong đồ án một
[00:02:29] rồi xong ngồi mới học sang Java thì
[00:02:32] thường là bọn mình sẽ kiểu được lựa chọn
[00:02:35] ngôn ngữ để mà học ấy. Tức là học Java
[00:02:38] chỉ qua môn thôi chứ không chú trọng
[00:02:41] việc là phải học chuyên sâu và Java. Thế
[00:02:44] nên là hồi đấy mình nhớ học tận hai môn
[00:02:46] Java nhá. Java cơ bản và Java gọi là OOP
[00:02:50] đấy. Nhưng mình chỉ nhớ mang máng các
[00:02:54] thứ thôi. Nhưng mình có biết một điều đó
[00:02:56] là Java rất là xịn này, rất chặt chẽ các
[00:03:00] thứ thứ. Tuy là tôi là gọi là
[00:03:05] em là fan của PP 10 năm rồi đấy. Nhưng
[00:03:08] mà vẫn phải công nhận là
[00:03:11] Java có những cái mà PP hiện có vẻ vẫn
[00:03:15] đang chưa có. Cho dù PP thay đổi rất là
[00:03:18] nhiều nhá. từ PP hồi mình dùng là từ PP5
[00:03:22] cho đến PP8 là bây giờ thay đổi rất rất
[00:03:24] nhiều rồi. Cũng chặt chẽ hơn rồi, cũng
[00:03:26] nhanh hơn rồi. Xong rồi cái gì Java có
[00:03:30] thì PP cũng một là kiểu có thư viện hay
[00:03:34] các thứ hỗ trợ vân vân nhưng mà để mà
[00:03:37] nói là kiểu xịn hẳn vàng cả là bây giờ
[00:03:41] chỉ đơn giản là ờ các công ty tuyển đúng
[00:03:44] không? Đấy, kiểu thế thì rõ ràng là mình
[00:03:46] không nên theo. Theo mình từ trước nay
[00:03:49] thì đó là lập trình viên mình không nên
[00:03:51] kiểu dập khuôn, mình suy nghĩ là kiểu
[00:03:53] mình bắt buộc là mình phải
[00:03:56] chỉ cố định một cái gì đó. Đấy,
[00:04:00] tại sao lại Java không phải là CSAP hay
[00:04:03] ngôn ngữ khác? Bởi vì đấy đấy là ấn
[00:04:05] tượng của mình. Mình nhớ là Java thứ
[00:04:06] nhất là về mình muốn show về back end là
[00:04:11] về
[00:04:13] OOP.
[00:04:15] Chính xác là thực ra mình chỉ quan tâm
[00:04:17] về việc được làm các bài toán chuyên sâu
[00:04:20] kiểu nghiệp vụ với kiểu bài toán lớn ấy,
[00:04:24] hệ thống lớn ấy thì thường là nó sẽ là
[00:04:27] nghe nói sẽ là Java nhiều đấy. Và sau
[00:04:31] Java chưa chắc là mình sẽ chỉ dừng ở
[00:04:33] Java. Mình định là nhiều người vẫn
[00:04:36] khuyên mình là từ PP để nhảy sang Go thì
[00:04:39] tốt hơn đấy. Nhưng mà mình muốn học Java
[00:04:41] để code để nắm chặt về hướng đối tượng
[00:04:45] thì nghe nói là Java là cái gọi là best
[00:04:48] practice à tức là kiểu cái phù hợp nhất
[00:04:51] để học về hướng đối tượng là cả design
[00:04:53] button này các thứ nó chặt chẽ nó ổn
[00:04:56] đấy. Xong rồi về à
[00:04:59] nhăng hôm qua mình có ngồi nói chuyện
[00:05:02] với ông em ông em cũng dạy mình về Java
[00:05:04] đây. Đây là cái repo của ông em tạo cho
[00:05:07] mình đây. Thì
[00:05:10] không em cũng anh lúc đấy mình cũng có
[00:05:12] chia sẻ là mình làm PP mình chỉ biết mỗi
[00:05:15] về mảng thôi, VR thôi, Java có thêm
[00:05:18] những cái nữa đây đến lúc khám phá rồi.
[00:05:21] Kiểu kiểu thế nói chung là đến lúc mình
[00:05:23] học sau đó nữa thì như vừa nãy bạn này
[00:05:26] có hỏi là mình có lên spring không thì
[00:05:28] nếu mà nó là framework đầu tiên mình vẫn
[00:05:31] hướng là Java cơ bản nhá mình sẽ đi từ
[00:05:35] đúng kiểu cơ bản như chưa biết gì nhưng
[00:05:37] mà mình sẽ tua nhanh nếu mà giả sử kiểu
[00:05:39] có vài cái là kiểu
[00:05:42] ví dụ vài cái cú pháp cơ bản thì có thể
[00:05:44] biết rồi thì mình sẽ có thể tô nhanh gì
[00:05:46] đó các bạn sẽ thấy là một kêu là 100
[00:05:49] ngày nhưng mà có thể là nó sẽ không có
[00:05:53] thể sẽ nhanh có thể có thể thôi nhá trừ
[00:05:56] khi mình học kém không biết được nhưng
[00:05:58] mà mình vẫn sẽ muốn là học kiểu kiểu là
[00:06:02] có MVC này có framework này đấy
[00:06:06] và mục tiêu của cái a buổi mục tiêu của
[00:06:10] cái playlist này của những cái a a gọi
[00:06:15] là khóa này thì mình muốn là thứ nhất là
[00:06:18] đồng hành cùng các bạn để mà các bạn sẽ
[00:06:20] hỗ trợ mình nếu có thể và mình sẽ cùng
[00:06:24] học. Biết đâu là có ông sinh viên nào đó
[00:06:27] cũng của tôi cũng từng kiểu học của tôi
[00:06:30] PP và bây giờ chỉ biết mỗi PP thôi. Giờ
[00:06:33] đến lúc rồi đúng không ạ?
[00:06:36] Uầy các bạn hôm nay đông bình luận đúng
[00:06:38] kiểu tôi tôi nhớ tôi nhớ có rất nhiều
[00:06:40] ông đã từng gài tôi là là
[00:06:44] kiểu học Java đi anh các thứ thứ chắc
[00:06:47] chắn mấy ông ấy sẽ vào đây chiều tối đây
[00:06:49] đợi tí thầy bật cam rồi sao à thì gần
[00:06:53] đây cũng có bật mà kiểu thế này tương
[00:06:56] tác cho mọi người thựt ra là tôi hôm nay
[00:06:58] tôi cân nhắc ấy bởi vì rõ ràng là hồi
[00:07:00] trước tôi dậy là tôi chỉ muốn mấy ông
[00:07:01] tập trung vào màn hình để dậy thôi nhưng
[00:07:03] mà thôi thì mở ở cam để cho mấy ông cảm
[00:07:06] thấy là ừ đang nói chuyện về người
[00:07:14] Java thực ra là tôi có cái GitHub ở đây
[00:07:17] thực ra cũng công khai này để mấy ông có
[00:07:19] thể ngồi mò nó cũng chả có gì cả thôi
[00:07:21] dùng chính AI để mà ngồi soạn ra soạn ra
[00:07:24] lộ trình học như thế này đấy thì à mấy
[00:07:27] ông có thể vào tham khảo hoặc thậm chí
[00:07:29] là góp ý là kiểu không nên học như này
[00:07:30] vân vân vân thế nào cũng được. Ờ hôm qua
[00:07:33] thì tôi mới chạy chạy thử. Nghĩa là thực
[00:07:37] tế là hôm nay là buổi thứ hai nhá, không
[00:07:39] phải buổi đầu đâu. Tôi kêu thế thôi.
[00:07:41] Nhưng mà hôm qua đã thử mỏ thử rồi xôi.
[00:07:43] Thầy hay quá nên thành ra kéo mới quyết
[00:07:46] là quay lại livestream để mà học. Bởi vì
[00:07:50] tôi hứa hẹn với mấy anh em là tôi sẽ thử
[00:07:53] học cùng anh em. Cái này từ lâu rồi, từ
[00:07:56] lâu lắm rồi.
[00:08:04] ạ. Không phải cuso ạ. À đây để mình so
[00:08:09] sánh về code. Mình mình chưa dùng clou
[00:08:11] code nhá. Thì mình chỉ biết được là đây
[00:08:15] mình nói theo cái trải nghiệm cá nhân
[00:08:17] của mình từ đầu nhá. Thì hồi trước là
[00:08:20] nếu mấy ông có biết là hồi trước tôi
[00:08:22] dùng PP Storm này. Đấy. Đấy. Sau về sau
[00:08:25] có khải nghiệm là trên này có cái
[00:08:27] plugin.
[00:08:29] Tôi nói lịch sử từ đầu luôn là
[00:08:32] plugin là tim. Ui, hồi đấy kiểu gợi ý ra
[00:08:35] hết một dòng đã sướng lắm rồi. Đấy, xong
[00:08:38] rồi về sau là có
[00:08:41] à Git Hub Cilot đấy.
[00:08:44] Cilot đấy. Xong rồi về sau là ờ dần dần
[00:08:50] là tôi cũng mất cái
[00:08:54] mất cái trả phí của PP Storm và tôi cảm
[00:08:57] thấy là thực ra không cần ham hố IDE nữa
[00:09:01] mà chuyển qua dùng VS Code cũng được.
[00:09:03] Thì vào đấy tôi dùng VS code đương nhiên
[00:09:05] là cũng có GitHub nhá. Copilot GitHub
[00:09:08] nhưng về sau thấy có một thằng nữa cũng
[00:09:10] khá là ngon và miễn phí. Copot đuy nhiên
[00:09:12] là mất phí trừ khi ông có meod đúng
[00:09:14] không ạ? Nó là
[00:09:18] code IUM
[00:09:20] là miễn phí. Đấy
[00:09:23] xong rồi à
[00:09:25] sau đó thì code IUM đầu tiên code EUM
[00:09:28] hình như là bán hay đổi tên gì đấy đại
[00:09:30] khái thì bằng Win search.
[00:09:33] Đây như này. Xong rồi. Tôi đã từng dùng
[00:09:36] qua cái argument argument code đâu? Tôi
[00:09:40] không nhớ tên tôi phải tra thông cảm anh
[00:09:44] em thông cảm. Đợ tí aument tôi dùng
[00:09:47] thằng này đúng một lần hồi mà nó kiểu
[00:09:50] lúc mới lúc mới tải về nó cho bàn thông
[00:09:53] thử đúng không ạ? Tôi làm cái app tính
[00:09:56] tính điểm chơi tá lả [tiếng cười]
[00:10:01] xong ngồi nó ngồi chạy vòng lặp cả hai
[00:10:03] ngày hôm đấy tôi cứ ngồi xem nó chạy
[00:10:05] vòng lập để ngồi tính tính tính các
[00:10:07] trường hợp ôi chán xóa đấy đại khái thì
[00:10:12] con đấy chuyên về giá lệnh nhiều hơn ấy
[00:10:15] không phải với code lắm đấy với góc nhìn
[00:10:17] của tôi nhá tôi vẫn đang chia sẻ góc
[00:10:19] nhìn bản thân thôi đấy
[00:10:22] đâu cái này phải bằng đổi Ok. Sau đó thì
[00:10:26] tôi chuyển qua dùng Winser. Bởi vì nghe
[00:10:28] nói là nó mới ra thằng res này hồi đấy
[00:10:31] nó bảo là
[00:10:34] bằng cuso
[00:10:36] cộng với agent gì gì nó của nó là cái gì
[00:10:41] đó ấy. Đấy không phải Cassandra đâu. Tôi
[00:10:45] quên mất tên nó rồi
[00:10:48] đấy. Tôi chưa dùng COR cho dù công ty
[00:10:51] tôi có mua cho mua tài khoản cho anh em
[00:10:53] dùng CO nhưng mà à không tôi có dùng COR
[00:10:56] chứ gần đây tôi có tải rồi có dùng rồi
[00:10:59] tôi mới nhận ra là đúng
[00:11:04] là tôi sẽ là thằng này cũng có khá xịn
[00:11:08] các thứ thứ thậm chí là tôi thấy có cái
[00:11:10] vụ mấy ông không biết là có cái vụ đúng
[00:11:13] là Cassade đấy đúng rồi đúng nhá đấy
[00:11:25] cái app ở trên điện thoại à như thờ ra
[00:11:27] đấy nhúng app nhúng thôi xong rồi tôi
[00:11:30] còn kiểu cho nó quyền thì nó gọi lên kit
[00:11:34] hub repo của mình để kiểu đẩy code các
[00:11:36] thứ thứ cơ rất mù mè các thứ thứ nhưng
[00:11:40] xong rồi tôi vẫn phải quay lại thằng Vin
[00:11:41] search bởi vì sao bởi vì nếu mà anh em
[00:11:46] code thì anh em sẽ biết được là mấy
[00:11:48] thằng à đa số bây giờ mấy thằng ấy thì
[00:11:51] mình ra lệnh nó qua mấy cái model ở đây.
[00:11:54] Đương nhiên là chúng ta vẫn dùng thằng
[00:11:55] cloude code này là cloue cái cái agent
[00:11:59] cloude này vẫn là đang xịn về code đúng
[00:12:02] không?
[00:12:04] Thì
[00:12:06] thì mấy thằng này nó kiểu tự động làm
[00:12:08] cho mình và nó sẽ có nếu mà thằng cúo ấy
[00:12:13] nó sẽ không hiển thị ra tường minh là
[00:12:15] thằng model thằng agent đang nghĩ gì đấy
[00:12:20] nên thành ra là ông chỉ biết kiểu ra
[00:12:22] lệnh xôi đợi nó kết quả thôi ông sẽ kiểu
[00:12:26] không xác nhận lại được không kiểu tôi
[00:12:30] thỉnh thoảng bây giờ tôi phải dùng mấy
[00:12:31] cái từ tiếng Anh chuyên ngành Tí mấy ông
[00:12:33] thông cảm nhá. Là phải confirm lại cái
[00:12:35] plan của nó đúng không? Đấy. Đấy nên
[00:12:38] thành ra là thường là tôi vẫn từ thời
[00:12:40] tôi dùng search không biết mấy ông có
[00:12:42] dùng AI giống như tôi dùng không là tôi
[00:12:44] luôn bắt nó ghi ra một cái file ma down
[00:12:47] để mà kiểu mà cái to delete ý kiểu để
[00:12:51] biết được là à bạn cần phải làm những
[00:12:54] cái gì vân vân vân vân. Đấy. Đấy. Xong
[00:12:57] rồi. À thì thằng CON này nó không hiển
[00:13:01] thị ra cái tường minh là cái luồng agent
[00:13:03] đang làm gì, đang nghĩ gì nên thành ra
[00:13:05] tôi phải quay lại search. Nhưng mà
[00:13:07] search tôi thấy tốn cũng 1 tháng là tôi
[00:13:10] cũng phải kiểu review lại cái credit của
[00:13:14] nó.
[00:13:20] gì cơ nhá. Thôi tôi sẽ không
[00:13:24] gì nhỉ?
[00:13:25] Sau đó thì đến bây giờ các bạn đang thấy
[00:13:28] thì tôi dùng antigravity
[00:13:31] đúng như bạn kia vừa nói đúng
[00:13:33] antigravity chính là winsert bởi vì đã
[00:13:36] từng có quả lộ là tôi nhớ là quả lộ là
[00:13:39] nó trong một cái gì đó của nó hiển thị
[00:13:41] ra cá cassan cade này này của nó đấy.
[00:13:48] Nạp credit thì nó vẫn không đúng refw
[00:13:51] tức là đầy lại mà đúng không? Đấy không
[00:13:54] biết từ như nào đấy
[00:13:57] xong rồi à đại khái thì antiravity này
[00:14:00] có cái hay là nó winser cộng với một cái
[00:14:02] nữa nó là planning
[00:14:05] này này chính là cái mà vừa nãy tôi có
[00:14:07] đề cập là tôi thường hay bắt thằng thằng
[00:14:10] mấy thằng này viết ra cái file ma để mà
[00:14:12] kiểu lên cái danh sách các thứ vân vân
[00:14:14] vân vân đúng không ạ thì thằng
[00:14:16] antigravity này nó mặc định là cái đấy
[00:14:18] là điều hiển nhiên rồi khi mà chuyển chế
[00:14:21] độ blending này đấy. này
[00:14:24] và đúng thằng An Gra tôi tôi không có
[00:14:27] mồi chào mấy ông nạp tiền để mà mua đồ
[00:14:30] công nghệ bây giờ nhá bởi vì rõ ràng th
[00:14:33] anti garanti hiện tại đang miễn phí thì
[00:14:35] cũng hay là một đúng không ạ thứ hai đó
[00:14:38] là
[00:14:40] à hồi trước là tôi từng bỏ tiền ra để
[00:14:42] mua chatt
[00:14:44] một tháng cũng 20 đô đấy để mà ngồi tâm
[00:14:47] sự tuổi hồng cả hồi đấy còn nhiều nó cốt
[00:14:50] nhưng bây giờ à u ôi bây giờ tôi cảm
[00:14:52] Thấy ạ. Cloud code ngon nhất này. Đây
[00:14:54] tôi vứt này xuống đây. Đấy với tôi nhá.
[00:14:57] Thì đó là trên mini này hiện tại. Xong
[00:15:00] rồi mới đến qu này thực ra chưa dùng.
[00:15:03] Xong rồi mới đến a chatvt codex. Đấy tức
[00:15:08] là chat TV giờ code rất tệ. Đấy tôi thà
[00:15:13] dùng Gemini xong rồi cloue hơn. Đây nó
[00:15:16] cũng có này cái GBT này như là cũng của
[00:15:18] Codex thì phải không biết được. Nhưng
[00:15:20] đại khái là tôi toàn dùng mấy cái này.
[00:15:22] Đấy.
[00:15:28] đại khái thế. Nghĩa là bây giờ tôi không
[00:15:29] nạp tiền chatt nữa. Tôi dùng cái tiền
[00:15:32] đấy để mà mua antiravity bằng giá mà. Mà
[00:15:35] trong khi đó là nó được hiện tại thì tôi
[00:15:38] đang được gọi là hỗ trợ giá là 3 tháng
[00:15:40] đầu được 50.000. Đấy. Tùy tầng tùy từng
[00:15:44] tài khoản Google của các bạn nhá. Nhưng
[00:15:46] mà đại khái thì nó có mình có Gemini để
[00:15:50] mà mình chat. Nhưng mà Gemini lúc đầu
[00:15:53] video tôi nói đây nó rất là vẫn rất là
[00:15:54] tệ. Tôi vẫn nói chuyện tâm sự với CHVT
[00:15:58] thôi. Nhưng mà có anti Gravity này cái
[00:16:02] này ngon ở điểm là đang dùng model này
[00:16:04] thoải mái. Tôi không biết là kiểu khoe
[00:16:07] mấy ông xong nó có limit của tôi đi
[00:16:09] không như bởi vì kiểu sợ kiểu spam
[00:16:13] server nó quá. Nhưng mà bình thường ông
[00:16:16] dùng antigravity thì tầm một tuần thì nó
[00:16:18] sẽ reset cái độ limit.
[00:16:22] Còn à nếu mà ông bản mất phí như thế này
[00:16:25] thì sẽ là tầm 4 tiếng rồi phải. 4 tiếng
[00:16:28] thì reset rồi. Nên là tôi tôi rất hiếm.
[00:16:32] Cũng có một lần chạm được đến limit rồi.
[00:16:35] Nhưng mà limit là limit của Clode thôi.
[00:16:37] Còn chuyển qua à Gemini dùng vẫn bình
[00:16:41] thường nhá.
[00:16:42] Ui, nãy giờ có anh em bình luận nhiều
[00:16:45] quá. Đợi tí tôi trả lời bình luận đã.
[00:16:52] nhất phải không phải cồ bởi vì đấy nếu
[00:16:54] mà ông vừa theo một cái thang đo này của
[00:16:56] tôi đúng không? Đấy, thì ông sẽ thấy là
[00:16:59] tôi đang thích nhất thằng Antigravity.
[00:17:02] Đấy, cho dù là thằng antiravity này,
[00:17:05] Winsert này, hay cusal thì nó đều là tôi
[00:17:07] thấy là đều là lõi VS code cả.
[00:17:15] ông đặt tên như này được ra tôi không
[00:17:17] nhớ không nhớ được ai với ai. Trừ khi
[00:17:20] mấy ông bình luận à kiểu nhắn tin
[00:17:22] Messenger thôi.
[00:17:25] Có lưu lại video stream không? Có bạn có
[00:17:27] gì bạn có thể xem lại vì mình thấy đa số
[00:17:29] người xem của mình thường hay xem lại
[00:17:31] kiểu giờ mình live lờ giờ mọi người ăn
[00:17:34] này, giờ mọi người đang đi chơi với gấu
[00:17:37] này vân vân vân.
[00:17:39] Hôm trước mới có người khoe với tôi là
[00:17:41] là
[00:17:43] mở của tôi nghe giống như kiểu podcast
[00:17:46] để mà ngồi làm việc á. Ui, tôi cảm thấy
[00:17:49] kiểu phục vãi kiểu bởi vì từ trước đến
[00:17:51] nay thì tôi luôn nghĩ là tôi tâm sự hay
[00:17:54] nói chuyện mấy ông thì một là mấy ông
[00:17:56] nghe được ngay tại thời điểm đấy để cho
[00:17:59] vui, để giết thời gian gì đó, hai là để
[00:18:02] mở lên để nghe du ngủ
[00:18:05] bởi vì giọng cứ đều đều ấy. Lần đầu tiên
[00:18:07] có người bảo tôi là nghe nghe anh nói
[00:18:11] chuyện podcast để em ngồi làm việc đấy.
[00:18:23] J2. Ui, xin chào bạn. Các bạn vẫn còn ở
[00:18:28] đây tôi cũng ngạc nhiên lắm rồi. Nhưng
[00:18:30] mà tôi nghĩ là video của tôi cũng sẽ
[00:18:32] người cũ xem và nhiều thôi chứ tôi cũng
[00:18:34] có quảng bá các thứ đâu. Cũng ít khi có
[00:18:37] người mới lắm.
[00:18:40] Thầy dạy Javacore hay sâu hơn ạ? Không,
[00:18:42] tôi có dạy gì đâu. Tôi đi học mà. Đây là
[00:18:44] buổi đầu học luôn ấy. Tí là tôi sẽ nhờ
[00:18:47] anh em ở đây kiểu chỉ dẫn và ngồi học
[00:18:50] cùng thôi.
[00:18:58] là bây giờ tôi không còn dậy nữa. Tôi
[00:18:59] chỉ dạy à à cũng không biết được xong
[00:19:02] này người ta có mời về dạy tiếp không.
[00:19:04] Đại khái thì năm ngoái thì thì họ nhờ
[00:19:07] dạy môn tin học lớp 12 bởi vì tin lớp 12
[00:19:10] bây giờ thì sẽ có kiến thức của năm nhất
[00:19:13] năm nhất đại học. Thế là tôi dạy được
[00:19:15] thì tôi mới nhận dạy.
[00:19:21] software Engineer lúc nào không hay. Uây
[00:19:23] thế quá vip luôn. Hi vọng các bạn trụ
[00:19:26] được cái nghề này. Bởi vì bây giờ cạnh
[00:19:28] tranh này xong rồi tỉ lệ
[00:19:32] mọi thứ nó cũng nhiều đúng không ạ? Ơ
[00:19:35] đợi tí đợi tí
[00:19:37] tôi chạm vào màn hình.
[00:19:41] Có bị sao? S
[00:19:50] cái
[00:19:52] kiểu m nền đằng sau thôi chứ mình không
[00:19:55] rõ là có đang có filter gì không.
[00:19:59] Review tai nghe á. Cái nghe này thực ra
[00:20:02] là mình mua là ủng hộ lúc mà cái
[00:20:06] cửa hàng đấy
[00:20:09] thanh lý nốt cho cửa hàng đấy, cửa hàng
[00:20:10] ấy đóng ấy. Và cái tai nghe này mục đích
[00:20:13] duy nhất của mình đó là ừ thì mình mất
[00:20:16] hồi trước mình bị mất cái tai nghe có
[00:20:18] dây rồi nên bây giờ mình mua và code là
[00:20:20] bây giờ từ toàn để cắm cái mic này nên
[00:20:22] là mình cũng chưa nghe nhạc gì cả nên
[00:20:25] khó đánh giá.
[00:20:27] Trước em học PP Lare từ Anh và giờ công
[00:20:30] ty đang định hướng chuyển sang Java
[00:20:31] luôn. Uầy quá phù hợp luôn bạn ơi. Kiểu
[00:20:34] thực ra là mình học à mình rõ ràng hồi
[00:20:37] trước mình chỉ chuyên về backend nhưng
[00:20:39] gần đây công ty bắt đầu điều hướng cho
[00:20:40] mình sang full stack. Hồi trước vẫn là
[00:20:42] full stack về làm JavaScript rồi nhưng
[00:20:45] mà không biết gì CS cả. Đấy thì công ty
[00:20:47] đang điều hướng mình sang full stack là
[00:20:49] vừa động vào một tí CS nhá và vừa phải
[00:20:52] đang từ view thì nhảy sang cả react nữa.
[00:20:55] Nhưng mà cảm ơn may bây giờ có ai uâ
[00:20:59] trên mini để ngồi làm giao diện đẹp kinh
[00:21:01] khủng kiểu xong rồi à đúng rồi thằng
[00:21:04] antiravity này nó vẫn bị cái điểm chung
[00:21:06] của hàng Google đó là nó kết nối thất
[00:21:10] bại. Nó không thể báo cho mình là kết
[00:21:11] nối thất bại. Tức là sao? Nghĩa là hồi
[00:21:13] trước mình dùng Win search xong mình
[00:21:16] dùng cái MCB này để kết nối với Figma để
[00:21:23] mà kiểu BA bên mình vẽ giao diện trên
[00:21:26] Figma rồi. Ấ thì con model này theo lý
[00:21:30] thuyết là nó sẽ kết nối đến cái Figma
[00:21:32] đấy để đọc được cái giao diện xong rồi
[00:21:33] làm giao diện làm ra trong web giao diện
[00:21:36] đẹp hoành tráng. Ok. Đấy hồi trước mình
[00:21:38] dùng resarch làm được ngon lành. So con
[00:21:40] này lần đấy là key nó bị lỗi hay gì đó
[00:21:43] khái thế nó tự bịa giao diện nhưng nó
[00:21:46] không h mình biết được kết nối bị lỗi
[00:21:49] đấy thành ra là mấy lần liền mình thấy
[00:21:51] kiểm tra lại hóa ra là nó không kết nối
[00:21:53] được đấy đấy là nhược điểm của hàng
[00:21:56] Google hiện tạ đó là Google cạnh tranh
[00:22:00] kiểu cố tung ra rất nhiều thằng bây giờ
[00:22:02] để cạnh tranh với những cái thằng hiện
[00:22:03] tạ bởi vì rõ ràng ông đấy ông to mà bây
[00:22:06] giờ để đi sau về công nghệ là không được
[00:22:08] đúng không ạ nhưng Mà nó rất cấn ở điểm
[00:22:11] là nó không nhận nó sai. Thằng Gemini
[00:22:14] thế
[00:22:16] mấy lần tôi thấy phải hỏi đi hỏi lại nó
[00:22:18] xác nhận rất mệt.
[00:22:22] Thầy thử xài Intel Ligi thay vì VS Code.
[00:22:26] Ờ thực ra là hôm qua tôi cũng có nghe
[00:22:29] ông bảo là cài mấy cái ID kiểu có sẵn
[00:22:32] các s thứ rồi tự nhiên kiểu đây hơi kiểu
[00:22:34] khổ ấy. Nhưng mà mình muốn học từ đầu
[00:22:37] thì thậm chí là bây giờ bảo mình học nốt
[00:22:39] pad mình cũng được. Chẳng qua cái cái
[00:22:41] thằng này có thêm AI mình thích thôi
[00:22:43] kiểu gõ nó tiện thôi chứ mình không muốn
[00:22:46] là kiểu đấy ví dụ hôm qua ông kia lạm
[00:22:49] dụng EE đấy đúng không? Tôi bảo ông đấy
[00:22:51] thử gõ lệnh ra ông không quên mất câu
[00:22:53] lệnh gõ luôn. Nghĩa là chỉ là bị phụ
[00:22:55] thuộc quá quên mất câu lệnh các thứ thứ.
[00:22:58] Đấy.
[00:23:04] antigravity đấy. Ai rồi cũng sẽ trở
[00:23:07] thành phiên bản mình từng ghét rồi. Anh
[00:23:10] anh live liên tục 100 ngày à anh? Lúc
[00:23:12] đầu tôi định thế nhưng mà sẽ có rất
[00:23:14] nhiều hôm kiểu phướng lịch hay gì đó
[00:23:17] kiểu ví dụ là tuần sau tuần sau này là
[00:23:21] công ty tôi
[00:23:23] à tiệc cuối năm này tôi còn lên nhảy nữa
[00:23:28] thì tôi không tôi không nghĩ là tôi thể
[00:23:30] livestream vào hôm đấy đấy
[00:23:38] vẫn bảo là Cloude CLD xong rồi cloue cod
[00:23:42] COD à không biết hai cái đây có là một
[00:23:44] không nhưng mà mình chưa dùng cái đấy.
[00:23:47] Một phần này hình như cái đấy phải nạp
[00:23:48] tiền đ vậy. Nói chung là tôi nghĩ là tôi
[00:23:49] vẫn sẽ định thử sau.
[00:23:56] Java G bố ra Java không không 100 ngày
[00:24:00] chỉ làm một cái cơ bản thôi. Nhưng mà
[00:24:03] đúng là bây giờ mình phải thích nghi dần
[00:24:06] đấy.
[00:24:12] Con antigravity thỉnh thoảng nó bị limit
[00:24:14] giới hạn ấy. Nó giống kiểu chattivity
[00:24:16] miễn phí là kiểu
[00:24:19] ông nếu mà ông dùng vào trong lúc mà
[00:24:22] kiểu đang đông người dùng ấy có thể nó
[00:24:24] sẽ đơ thì phải. Cái cái việc họ trả lời
[00:24:28] câu hỏi này này. Và thứ hai thì tôi thấy
[00:24:30] là cái tốc độ gợi ý của nó có vẻ chậm
[00:24:33] hơn so những thằng khác. Sếp tôi cũng
[00:24:35] kiến nghị việc đấy. À đúng rồi, thằng
[00:24:37] antiravity này một trong những cái mà
[00:24:38] tôi cảm thấy là nó vẫn gọi là
[00:24:42] à rẻ hơn so thằng khác nhá. Cho dù rõ
[00:24:44] ràng 20 đô đúng không? Đó là ông dùng
[00:24:47] được cho cả family của ông.
[00:24:51] Nghĩa là bây giờ Google Family của tôi
[00:24:55] đang có năm người phải năm hay sáu người
[00:24:57] gì đấy. Đấy cả family dùng được. Tính ra
[00:25:01] bây giờ ông mời cả anh em trong công ty
[00:25:03] ông giả sử 500.000N đi xong rồi năm
[00:25:05] người mỗi người 100 mà dùng tài khoản
[00:25:09] này độc lập không bị limit theo tài
[00:25:12] khoản độc lập với tài khoản kia dùng bét
[00:25:14] nhè
[00:25:17] không biết sao nữa tôi thấy không quan
[00:25:18] trọng AI nào nữa. Miễn đặt câu hỏi rõ
[00:25:21] ràng thì AI nào cũng giống nhau.
[00:25:24] Ừ
[00:25:25] hồi trước tôi cũng nghĩ thế. Hồi trước
[00:25:26] là tôi không để ý mấy cái vụ này. Tôi
[00:25:29] gần đây tôi bắt đầu tìm hiểu ấy, kiểu
[00:25:31] gần đây tôi ép tôi phải tìm hiểu. Bởi vì
[00:25:33] thực sự là nó khác biệt quá lớn nên là
[00:25:35] tôi mới phải tìm hiểu ấy. Chứ hồi trước
[00:25:36] là đúng là tôi hồi trước tôi dùng
[00:25:38] chattivity mà. Thế nên là kiểu
[00:25:41] ừ tôi nghĩ là sẽ đến một thời điểm nào
[00:25:43] đó. Thứ nhất là tôi không hề bị phomo,
[00:25:46] không hề kiểu kiểu chạy theo công nghệ
[00:25:48] hay là kiểu dạng là sợ là bị bỏ lại hay
[00:25:51] các thứ thứ phải chạy theo xu hướng. Bở
[00:25:52] vì có rất nhiều cái tôi vẫn chưa dùng.
[00:25:54] Đấy nhưng mà tôi nghĩ là tôi từ khi tôi
[00:25:58] kiểu đây sẽ đến một thời điểm nào đó là
[00:26:02] ông sẽ phải thích nghi hoặc ông bị đảo
[00:26:03] thải mà mình mang tiếng mình là dân công
[00:26:06] nghệ là chuẩn là mình phải thích nghi
[00:26:08] nhanh hơn người khác đúng không ạ? Dân
[00:26:10] công nghệ mà mình lại bảo mình ngại hay
[00:26:12] vân vân vân gì đó thì nó cũng hơi sai
[00:26:14] đúng không ạ? Đấy
[00:26:27] không tin đâu ạ. 5 năm trước anh em học
[00:26:30] khóa của anh Long nè. Xin cảm ơn ạ. Bắt
[00:26:33] đầu cái bài đồ án nhỉ.
[00:26:42] bị gọi chữa cho bạn làm đồ án.
[00:26:46] Đúng rồi. Tôi có đi dạy nếu mà mấy ông
[00:26:49] có biết rồi. Hồi trước tôi từng đi dạy,
[00:26:51] tôi từng làm giảng viên đấy. Thế nên là
[00:26:53] tôi sẽ hỗ trợ định hướng cho các bạn
[00:26:56] kiểu các bạn mà sinh viên đặc biệt là à
[00:26:58] thậm chí là hôm trước tôi vừa chữa cho
[00:27:00] bạn kể cả bạn đấy đi làm hình như cũng 5
[00:27:03] 6 năm gì ấy rồi bạn ấyã cần tôi t
[00:27:07] vẫn sẵn sàng hỗ trợ
[00:27:09] nói hỗ trợ miễn phí thì không biết mấy
[00:27:11] hôm có tin không nhưng mà đại khái là
[00:27:13] tôi rất là thoải mái
[00:27:17] nên là ông nào mà cần thì nó là kiểu
[00:27:21] dạng là kiểu như mình giúp người ta mình
[00:27:23] vui à saong mình thêm kinh kinh nghiệm
[00:27:25] thêm vốn kiến thức nữa cũng hay
[00:27:33] sẽ ngồi gọi để mà trao đổi bạn đấy về
[00:27:36] cái tôi sẽ ngồi chữa livestream như này
[00:27:38] luôn cho bạn đấy về cái định hướng đồ
[00:27:41] oán
[00:27:43] không biết bạn đã on chưa cơ
[00:27:53] Thường là chuẩn là sẽ tầm 8:00 hàng ngày
[00:27:55] trừ khi có vướng lịch nào đó.
[00:27:58] Có 100 ngày học Pon không bác? Tôi nghĩ
[00:28:02] là tôi vẫn có một cái niềm gì đó không
[00:28:06] thích PH lắm và lại cả là để làm gì đã.
[00:28:09] Ví dụ giả sử tôi học Java này để chưa
[00:28:12] biết được là liên quan công việc gì hay
[00:28:14] không nhá. mà để mình đấy như tôi nói
[00:28:16] lúc đầu là để học về cái sự chặt chẽ
[00:28:19] xong rồi chuyên sâu về backend hay vân
[00:28:22] vân vân này chứ không phải là để tôi học
[00:28:25] quá nhiều ngôn ngữ bởi vì nó không để
[00:28:27] làm gì cả.
[00:28:36] ops là gì thế? Ơ cái cái có chấm nào à
[00:28:41] đâu chỗ chỗ nào nhỉ?
[00:28:48] ty tôi. Cái này kết nối sang kiểu
[00:28:53] kiểu phải có phải mở cái này thì mới kết
[00:28:56] nối được vào server công ty để tránh
[00:28:58] việc là bây giờ ông nào cũng có IP là
[00:29:02] được quyền truy cập thì không nên đúng
[00:29:03] không ạ? Chỉ cần có IP mật khẩu mà truy
[00:29:05] cập vào không nên. Thì bên này có hai
[00:29:08] thằng th scale này này. Đấy.
[00:29:18] đang nhảy job hả? Thực ra là không.
[00:29:21] Nghĩa là thật ra là để mà nói thì
[00:29:25] đại khái nó liên quan đến công một phần
[00:29:27] là công ty mà một phần là kiểu à kiểu
[00:29:31] đầu tiên thì có một người kiểu
[00:29:35] à liên hệ tôi qua Lion xong rồi bảo
[00:29:37] phỏng vấn thì rõ ràng tôi phỏng vấn và
[00:29:40] thấy mọi thứ kiểu
[00:29:42] khá là kiểu
[00:29:44] không phải nói dùng từ trong mơ nhưng mà
[00:29:46] nó khá là ổn đấy thì tôi có cân nhắc
[00:29:49] xong rồi tôi cũng làm bài phỏng vấn các
[00:29:51] thứ. Xong rồi khi mà làm bài phỏng vấn
[00:29:53] xong thì họ mất tích. Đấy. Thế nên là
[00:29:56] hôm trước tôi mới đăng cái video trên
[00:29:58] kênh YouTube này là cái video tôi trả
[00:30:01] lời bài phỏng vấn ấy. Đấy.
[00:30:05] À thì nói chung là đại khái thì kiểu làm
[00:30:07] bài phỏng vấn xong rồi trả lời cho người
[00:30:09] ta xong mà bị kiểu
[00:30:13] bị không phản hồi bị gớt à đấy bị bơ ấy
[00:30:17] thì cũng khó chịu thật.
[00:30:25] dùng PP cho dù rõ ràng là học Java thì
[00:30:28] hôm qua ngồi nghe Java cũng thấy nghe
[00:30:30] hay thật
[00:30:36] không bởi vì tôi trả lời rất là chậm đấy
[00:30:37] không ạ đi hát không anh
[00:30:41] ok mấy anh em có gì anh em cứ lên kèo
[00:30:44] sau
[00:30:45] ông Minh Hiếu Ngô chung quen quen nhỉ
[00:30:54] cuốn
[00:30:57] hay W school về không? Không, tôi học
[00:30:59] theo cái này này, học theo cái mà tôi đã
[00:31:01] dùng AI để mà soạn bởi vì như tôi bảo
[00:31:04] lúc đầu là tôi sẽ học từ cơ bản một tí
[00:31:08] nhưng nó vẫn là đây
[00:31:11] từ
[00:31:13] PP
[00:31:14] sang vân vân vân nên là
[00:31:18] tập trung vào cái sự khác biệt vân vân
[00:31:21] chứ không phải là nghĩa là có nhiều cái
[00:31:24] là nghĩa là nếu mà bạn nào mà gọn như
[00:31:32] thì những cái mà tôi chia sẻ sắp tới thế
[00:31:34] này sẽ có thể rất là lạ vì rõ ràng là
[00:31:37] cái này không phải là học từ cơ bản hoàn
[00:31:40] toàn nhưng mà cái này nó sẽ là kiểu phù
[00:31:42] hợp với việc là ông đang từ biết trước
[00:31:46] một ngôn ngữ lập trình rồi ông nhảy sang
[00:31:48] đấy kiểu
[00:32:01] có nhiều người đây là tôi thấy giống như
[00:32:03] kiểu lần đầu bình luận ấy. Trông rất lạ
[00:32:05] luôn.
[00:32:18] các bạn xem video kia cũng chắc biết tên
[00:32:20] công ty tôi không tiện nhắc tên. Mình
[00:32:22] không mình cũng bị ảnh hưởng cảm xúc bởi
[00:32:25] công ty đấy. Vì công ty kiểu cho mình có
[00:32:29] một tí suy nghĩ gì đó kiểu đán đo thôi.
[00:32:31] Hôm đấy tôi đán đo cực các thứ thứ nghĩ
[00:32:33] nhiều cực cuối cùng bị gớt hơi buồn.
[00:32:37] Ai ai giờ cũng phải thích nghi thôi. Ok
[00:32:40] 24 giờ đi anh 100 ngày hơi lâu. 100 ngày
[00:32:45] mới thể hiện quyết tâm lẫn cả là mình
[00:32:46] mới gọi là như này mình mới
[00:32:50] kiểu thấm nhuần nhập nó được vào đầu ấy.
[00:32:54] Còn nếu mà học theo kiểu là giống kiểu
[00:32:56] hackaton hay kiểu là kiểu học kiểu try
[00:32:59] hot kiểu như thế thì
[00:33:02] nó sẽ không đọng lại hết vào trong đầu
[00:33:04] được. Đấy kiểu thế.
[00:33:11] lệch không? Bởi vì tôi đang trả lời từng
[00:33:14] cái ở trên cùng mà nên là nó chậm thông
[00:33:16] cảm. Công ty cấp Copilot nhưng không
[00:33:19] dùng
[00:33:21] nhưng không cho dùng cloud
[00:33:24] off vì đắt. Đúng ờ
[00:33:32] đắt nhất mà cho dù là tôi thấy thằng
[00:33:36] Winsert có một cái hai cực.
[00:33:42] đắn đo khi mà kiểu rời xa nó bởi vì nó
[00:33:46] thằng Vinf nó có cái AI tự nó phát triển
[00:33:49] ra. Tôi không nhớ gì hình như chính cái
[00:33:52] W vừa nãy hay cái gì đó ấy. Nó đại khái
[00:33:55] là nó hiển thị rõ bảng giá ở đây nhá.
[00:33:58] Hiển thị rõ bảng giá là ví dụ là con này
[00:34:00] mất bao nhiêu credit, con này mất bao
[00:34:01] nhiêu credit đúng không? Con này là mất
[00:34:03] giả sử con này mất tận ba credit đi. Mấy
[00:34:05] con kia chỉ một hay hai đúng không?
[00:34:07] Nhưng cái con AI của thằng Vinus này tự
[00:34:10] ra nhá. Cứ cho là tên nó là A đi. Tôi
[00:34:13] không nhớ lắm. Nó chỉ mất 0,5 credit
[00:34:15] thôi.
[00:34:17] Và rõ ràng khi mà AI của nhà làm được
[00:34:21] thì rõ ràng là nó sẽ
[00:34:23] nó sẽ có thể không ngon bằng thằng Cloue
[00:34:25] đang rất là xịn bây giờ đúng không?
[00:34:27] Nhưng nó sẽ chơi một cái trò nữa đó là
[00:34:30] cộng với thằng Cloue
[00:34:37] con đấy vẫn là ba credit đi. Nhưng mà
[00:34:40] cộng này tức là sao? Nghĩa là chỉ là cái
[00:34:43] này rất phù hợp cho những anh em nào
[00:34:46] thậm chí kể cả tôi thường đó là tôi
[00:34:48] không muốn hỏi mấy con quá quỷ bắp bởi
[00:34:50] vì có những cái mình đầu tiên mình vẫn c
[00:34:54] độ chính xác đúng không? Thế nên là mình
[00:34:57] vẫn phải hỏi những cái con mà chắc chắn
[00:34:59] sẽ trả lời cho mình chính xác. Nhưng con
[00:35:00] đấy tốn quá nhiều credit thì bâyế giờ nó
[00:35:02] có sinh ra cái vụ này hay phết. Đó là
[00:35:05] những
[00:35:07] câu mà thằng đấy chắc chắn sẽ trả lời
[00:35:09] được. Ví dụ con này chắc chắn sẽ trả
[00:35:10] được luôn thì nó sẽ phản hồi rất nhanh.
[00:35:13] này phản hồi nhanh lắm như kiểu chavity
[00:35:15] kiểu mình gõ vừa gõ nó xong nó đã phản
[00:35:18] hồi luôn ý đấy đấy trong trường hợp nó
[00:35:21] trả lời được và nó tốn chỉ 0,5 credit
[00:35:23] thôi. Nhưng với những câu nào mà nó sẽ
[00:35:26] tự đánh giá, nó cảm thấy khó, nó sẽ tự
[00:35:29] viết prom để hỏi lại con này và lúc đấy
[00:35:32] nó mới bắt đầu tốn ba credit. Ông hiểu ý
[00:35:35] tưởng đúng không ạ? Nghĩa rất là hay.
[00:35:37] Nghĩa lúc đấy đúng hồi mà tôi dùng cái
[00:35:39] đấy, tôi sẽ chẳng cần quan tâm đến việc
[00:35:41] là tôi phải dùng cái model nào, phải cân
[00:35:44] nhắc, phải đổi mod liên tục như hiện tại
[00:35:45] là kiểu cái này đỡ tốn hơn cái này các
[00:35:48] thứ thứ trong trường hợp này trường hợp
[00:35:50] kia. Không, tôi sẽ chỉ dùng con này
[00:35:52] thôi. Nghĩa là
[00:35:55] nếu nó trả lời được nhanh mà vẫn phải
[00:35:57] chính xác, vẫn chính xác nhá. Đấy thì nó
[00:36:00] trả lời luôn tôi tốn rất ít mà Queens
[00:36:03] gần đây nó còn tăng cho lượng credit là
[00:36:06] tận 500 credit thì phải. Hồi trước là
[00:36:08] 250 bằng 15 đô đấy. Đấy đây là mỗi tháng
[00:36:15] 15 đô sẽ được 500 credit. Sau đó thì 250
[00:36:20] credit cho 10 đô tiếp theo.
[00:36:24] Nghĩa là bạn top up nạp thêm ấy. Đấy
[00:36:27] nhưng mà 500 cái bây giờ ông cứ hình
[00:36:30] dung giả sử bài toán lý tưởng nhất là
[00:36:34] ông làm cái project kiểu rất đơn giản cơ
[00:36:36] bản toàn dễ và trưởng nhưng ông muốn
[00:36:37] dùng ai code đúng không? Đấy thì 500
[00:36:41] credit này ngang bằng 1000 lần ông hỏi
[00:36:42] câu này 1000 lần hỏi 1 tháng ông hỏi thế
[00:36:46] phải tầm 1 ngày ông hỏi hơn 30 lần
[00:36:50] một tháng hơn 1 ngày hơn 30 cái prom để
[00:36:53] hỏi liên tục ai cũng tẹt gam mà đúng
[00:36:56] không đấy
[00:37:09] nếu mà so bài toán của ông với resarch
[00:37:11] này 60 đô của ông là tôi còn dùng tẹt
[00:37:14] mấy tháng rồi.
[00:37:19] research kiểu qua thôi nhá. Rõ ràng nãy
[00:37:22] giờ tôi khen anti gravity nhiều hơn mà
[00:37:25] tôi còn chưa chia sẻ link ra đ mấy ông
[00:37:26] đâu. Đấy chia sẻ link ra biết đâu cộng
[00:37:28] được cái gì không.
[00:37:35] ờ đừng, nếu mà em còn đang nạp tiền chớ
[00:37:39] thì thôi bỏ đi thằng này bằng giá cho nó
[00:37:42] ngon hơn. À đấy trong trường hợp em
[00:37:44] không dùng chích gì đó để mà mua đấy
[00:37:49] nên đại khái thì ờ ông cứ phải dùng thử
[00:37:53] đã. Tôi chỉ nói thế thôi chứ tôi chẳng
[00:37:55] ăn được cái gì.
[00:38:04] về AI. Ừ, hình như là tôi tham gia mấy
[00:38:07] cái nhóm kiểu thế nhưng mà tôi kiểu lười
[00:38:10] kiểu và theo dõi chat các thứ ấ nên tôi
[00:38:13] không để ý lắm.
[00:38:19] buổi đi coi. Ok. Ok được. T scale đó
[00:38:24] dùng ổn không anh? Thứ nhất là nó đang
[00:38:26] miễn phí, thứ hai là nó không phải là
[00:38:30] VPN để mà mấy ông kết nối vân vân gì
[00:38:33] đâu. Tôi hiện tại tôi đang dùng chỉ kết
[00:38:36] nối đến con server ở trên công ty nên là
[00:38:38] nó không có vấn đề gì cả. Không không có
[00:38:41] vấn đề phát sinh. Kiểu mở lên mà dùng
[00:38:42] thôi. Không bị cái tình trạng bị delay
[00:38:45] hay mọi thứ gì cả. Nhưng không biết là
[00:38:47] mấy ông dùng việc khác như thế nào nhá.
[00:38:51] Phỏng vấn xong mất tích chắc hoan man
[00:38:53] lắm. Ơ thì gửi cho người ta bài làm mình
[00:38:56] xong xong người ta tôi gửi xong không
[00:38:59] thấy phản hồi qua mail tôi nhắn tin qua
[00:39:03] lúc đầu hồi trước nhắn tin qua leon này
[00:39:05] xong còn nhắn tin qua WhatsApp này không
[00:39:07] được này xong rồi tuần sau tôi lại gửi
[00:39:09] mail thêm phát nữa để hỏi kiểu xác nhận
[00:39:12] lại vẫn không thể có phối gì cả thực ra
[00:39:15] là tôi stock được à nick tôi start được
[00:39:18] hình như nick của chị quản lý ở bên đấy
[00:39:20] rồi cơ
[00:39:22] nhưng mà kiểu nick Facebook ấy nh thôi
[00:39:26] bây giờ mình bây giờ chẳng lẽ mình lại
[00:39:29] inbox nói người ta m kiểu nói chung là
[00:39:33] thôi đành kệ vậy biết sao giờ cùng lắm
[00:39:35] là ư nhỉ
[00:39:38] mình phải bắt trượng ông kia tôi đang
[00:39:40] nói là tôi không đang định tôi không
[00:39:41] định đăng phố lên J2 thì nó lại hơi nặng
[00:39:45] nề quá nhưng mà tôi đã từng đọc một cái
[00:39:48] review về công ty đấy một cái thôi nhá
[00:39:50] mới chỉ có một cái đây Đ mấy tháng là
[00:39:53] công ty đã từng làm thế với với người ta
[00:39:56] là từng cho người ta làm bạch kiểm tra
[00:39:57] xong gớ. Ừ tôi sắp có một cái review thứ
[00:40:01] hai giống thế rồi
[00:40:04] được chứ bây giờ không ai nói kiểu tôi
[00:40:07] thì tôi cảm thấy là vẫn nên có một tí
[00:40:09] lên tiếng đúng không ạ? Để cho tránh
[00:40:12] người khác bị giống mình. Đấy thực ra nó
[00:40:15] chưa chắc là có thể người ta tìm được
[00:40:17] người tốt hơn rồi hoặc vân vân gì đấy
[00:40:19] người ta không thích mình đấy nhưng mà
[00:40:21] mình vẫn nên nói.
[00:40:29] đăng phút suốt
[00:40:31] Zalo mà điển hình à. Thôi mẹ nói cả tên
[00:40:34] mất rồi. Không có gì nhá. Không có gì
[00:40:36] nhá. Kênh này nó không trụ nổi như
[00:40:41] nhóm Facebook, nó dễ bay hơn đấy.
[00:40:52] nhá. Tôi học Java không dạy
[00:40:56] nhầm nhá. Tôi ghi ở đây 100 ngày học
[00:40:59] Java mà không dậy nhá.
[00:41:06] ta chuẩn bị bắt đầu học. Ừ, đáng lẽ nãy
[00:41:08] giờ không học cái gì lộ lỡ tôi mải nói
[00:41:10] chuyện quá. Cho xem lộ trình á. À đây
[00:41:12] đây đây để tôi a để link cho anh em. Cái
[00:41:16] này là tôi dùng
[00:41:18] à tôi dùng cái a tổng hợp ra dựa trên
[00:41:22] cái kiến thức có sẵn của tôi là là có
[00:41:25] kinh nghiệm về PP rồi nhá. Chứ không
[00:41:28] không phải là kiểu mấy ông cứ học như
[00:41:31] này thì sẽ ổn đâu nhá. Tất cả chỉ mang
[00:41:34] tính chất tham khảo ạ. Đấy
[00:41:37] được ông ông kia nói câu hay vãi chưởng
[00:41:41] học đi ông để tôi xem cách ông học đấy
[00:41:43] tôi rất cần những người như thế để tôi
[00:41:45] đỡ mật tôi chung để tôi ngồi học và
[00:41:47] chúng ta cùng hồi học mà cái livestream
[00:41:49] này chúng ta cùng hồi học nhá không ai
[00:41:51] dạy được ai đâu
[00:41:53] à nhầm ông có thể dạy tôi như tôi không
[00:41:55] dạy được ông chắc chắn
[00:42:09] ok xem
[00:42:11] đây tôi ghim cái link kia cho mấy ông
[00:42:13] nhá. Ok
[00:42:15] link đấy cũng là do thằng em ngồi làm ra
[00:42:18] cho tôi ấy chứ không phải là của một
[00:42:20] giáo án của một thầy nào đó hay vân vân
[00:42:22] gì đâu nhá anh em. Tất cả chị màn hình
[00:42:24] rất tham khảo
[00:42:27] cảm giác quay về thời dịch.
[00:42:30] Tôi cũng PP muốn học. Ok chúng ta học
[00:42:34] cùng nhau nào.
[00:42:40] không thế lại quá nhầm rồi. Không có
[00:42:42] người giỏi nào ở đây cả. Chúng ta nếu mà
[00:42:45] người giỏi thì chúng ta đi dậy rồi chứ
[00:42:46] không phải chúng ta đi học.
[00:42:50] Lại tí làm hộm nước ạ. Xin phép.
[00:42:58] anh có dành về React không? Gần đây tôi
[00:43:00] mới có động vào ở trên công ty nhưng tôi
[00:43:04] không dành đấy. Kể cả hồi trước tôi từng
[00:43:07] làm view nhưng tôi vẫn không dành. Tôi
[00:43:10] tự tin là tôi dành về PP hết à một tí về
[00:43:14] SQL đấy.
[00:43:17] Dùng Nest DS chưa? Tôi cũng chưa luôn ạ.
[00:43:26] dịch thì cái này bỏ qua hả thầy? Ờ ông
[00:43:30] chưa qua vì do gì đã. Nếu mà ông chưa
[00:43:33] qua vì ông cảm thấy ghét lập trình thì
[00:43:36] ông cũng không nên xem video này.
[00:43:43] Đúng đúng đúng. Đấy một trong những cái
[00:43:44] tôi cảm thấy là mấy người khác không
[00:43:47] dùng AI cảm thấy lãng phí. Thôi đây bắt
[00:43:50] đầu học nhá.
[00:43:51] Thì hôm qua
[00:43:58] bắt ngồi dậy tôi viết câu lệnh mà
[00:44:01] hôm qua tôi học được bài này rồi phải
[00:44:02] không ạ? Đấy à đầu tiên thì cài ông em
[00:44:08] cho lên trang chủ xong phải đăng nhập
[00:44:10] cái gì gì đó để cài nhưng tôi không cài
[00:44:12] cái Intel Leg này đâu. Xin tạm biệt.
[00:44:14] Xong rồi tiếp theo
[00:44:17] là để phân biệt hai cái này. Ông em dịch
[00:44:19] cái này là nguyên thủy và cái này là
[00:44:23] kiểu class đóng uống gói. Ờ xong rồi kèm
[00:44:26] theo mấy cái kiểu dữ liệu. Thì hôm qua
[00:44:28] tôi thử tạo một file như này.
[00:44:36] cho mấy ông nhá. Ông nào thấy tôi nói
[00:44:39] sai cứ cứ chấn chỉnh nhá.
[00:44:44] Thì Java thì nó sẽ là kiểu chuyên trong
[00:44:47] các class class ấy. Đấy. Đấy. Thì tôi
[00:44:51] tạo một cái class như này. Ok. Và trong
[00:44:53] đó có một cái luôn
[00:44:56] luôn có một cái co à luôn có một cái
[00:44:58] kiểu method là main như thế này để mà
[00:45:01] chạy. Thường là mọi thứ sẽ chạy nằm
[00:45:03] trong này đúng không ạ?
[00:45:05] Đấy. Ờ
[00:45:07] thì ở đây sẽ có hai cái là bình thường
[00:45:11] với PP thì mình không có kiểu khai báo
[00:45:13] kiểu dữ liệu như này. Mình sẽ đô la
[00:45:15] thẳng luôn đúng không ạ? Còn trong Java
[00:45:17] thì mình sẽ có khai báo kiểu dữ liệu.
[00:45:19] Đấy thì khai báo kiểu dữ liệu thì theo
[00:45:22] kiểu nguyên thủy thì tức là mình kiểu in
[00:45:24] này xong rồi ờ kiểu chuỗi à ừ xong rồi
[00:45:29] kiểu bull này vân vân string các thứ
[00:45:31] đúng không ạ? Thì nhưng mà bên này nó sẽ
[00:45:34] có thêm một nữa là nếu mà ghi kiểu viết
[00:45:36] hoa đấy, viết hoa viết đầy đủ như này
[00:45:39] thì nó sẽ là một class. Cái này là một
[00:45:41] class. Đấy, hôm qua tôi mới tự khai sáng
[00:45:44] từ bản thân mình ra. Đây là một class.
[00:45:46] Và đương nhiên đương nhiên class này nó
[00:45:49] sẽ có thêm ngoài những method có trong
[00:45:52] này. Đấy, thì nó sẽ được phép đặt cái
[00:45:57] giá trị là nun. Còn nếu mà in thì bình
[00:45:59] thường không được nol. Đấy.
[00:46:02] Đây nếu mà trong PP thì hồi trước có cái
[00:46:05] trò kiểu hỏi chấm như này thì
[00:46:07] để một là in hai là nun. Nhưng mà trong
[00:46:09] này không được mấy không ạ?
[00:46:16] nhá. Nên là tôi sẽ so sánh PP rất là
[00:46:18] nhiều nên là mấy ông mà chưa biết cả PP
[00:46:20] thì chịu nhá.
[00:46:24] Thiếu
[00:46:26] generic rồi. Generic là gì? Mấy ông nhắc
[00:46:29] đến generic mà tôi không biết.
[00:46:32] Thôi xong để xem nào. Chick đúng không?
[00:46:34] Ch
[00:46:37] gen r
[00:46:48] cho anh em rồi anh em vào tự cập nhật
[00:46:50] vào trong đấy rồi chúng ta sẽ có buổi
[00:46:52] hôm sau rồi học về cái đấy nhá. Ok. Đấy
[00:46:55] thì hôm qua tôi tôi giả sử tôi thử viết
[00:46:58] quá
[00:47:00] xong rồi tôi còn à so sánh cái này nữa.
[00:47:03] Hôm qua so sánh cái này trông kiểu vô lý
[00:47:05] vãi. Kiểu tự nhiên đây là in nhỏ hơn
[00:47:09] long này 64 bit các thứ thứ đúng không?
[00:47:12] So tự nhiên flot lại lớn hơn long mà rõ
[00:47:15] ràng cái này 32 bit. Đấy, hôm qua tôi
[00:47:17] phải thắc mắc thắc mắc hai lần liền để
[00:47:20] nó phải xác nhận lại với tôi là cái này
[00:47:22] là liên quan đến khoảng giá trị và nó
[00:47:26] hay nó dùng cái cơ chế dấu phẩy động.
[00:47:29] Cái này tôi từng nghe qua thôi, tôi nghĩ
[00:47:31] nó không chém gió đâu. Nhưng là cái này
[00:47:33] tôi nghĩa là về sau tôi động được đến.
[00:47:44] quen quen nhỉ? Ý ông cái này á.
[00:47:48] Đây á kiểu như này á
[00:47:51] ông lừa tôi đúng không?
[00:47:53] kiểu dữ được đâu.
[00:48:03] dùng thình kinh đấy.
[00:48:12] quá
[00:48:14] nên là chúng ta sẽ dùng
[00:48:17] đây
[00:48:19] tôi
[00:48:21] đang học Java
[00:48:23] có người bảo
[00:48:30] nữa nó là gì cập nhật vào tiến trình học
[00:48:36] cho tôi. gì
[00:48:44] ông nói một kiểu đấy ông bịp tôi đúng
[00:48:45] không?
[00:48:47] Đây đúng kiểu dạng
[00:48:50] đấy. Đây đúng kiểu dạng kiểu
[00:48:53] cậy người ta không biết gì nói đấy.
[00:48:56] Someone subet kiểu generic in Java. Đây
[00:48:59] đây đây cái tôi đang muốn nói này nó sẽ
[00:49:01] hiển thị ra cái luồng suy nghĩ khá từng
[00:49:03] minh này để mình biết này
[00:49:06] đang nói tiếng Việt các thứ các thứ dịch
[00:49:09] xong rồi nó tự xịch ra hạ vậy chưa đây
[00:49:12] đọc này đấy nó sẽ nói cái luồng nó sẽ
[00:49:15] làm này đúng không đọc này xong rồi đọc
[00:49:19] hiểu này
[00:49:21] giải thích nó là gì này cập nhật lại này
[00:49:24] đấy tôi hiểu rồi thìẽ tham số hóa kiểu
[00:49:30] Tiếng Việt nó dịch ra nó cũng không dễ
[00:49:33] hiểu lắm nhỉ. Cho phép viết code với
[00:49:36] nhiều kiểu dự khác nhau nhưng đảm bảo à.
[00:49:42] Nó giống như kiểu à
[00:49:45] kiểu như này đúng không? Kiểu nếu trong
[00:49:47] PP nó sẽ kiểu như này đúng không? Đấy
[00:49:50] kiểu kiểu như này. Nghĩa là có thể một
[00:49:51] trong hai đúng không?
[00:49:54] Đúng không? V xem nào.
[00:50:12] toàn. Đâu xem
[00:50:15] ơ thằng này có một nhược điểm đó là mình
[00:50:19] đang cuộn lên trên như thế.
[00:50:21] Mình đang cuộn lên trên như thế xong
[00:50:23] mình cứ kiểu nó tự động viết nó lại kéo
[00:50:26] mất cái cuộn mình. Có thật
[00:50:29] đấy. Nó bị cuộn cuộn cách hiện đại an
[00:50:33] toàn. Cái này chỉ khai báo kiểu dữ liệu
[00:50:36] cho array danh sách thôi mà đúng không?
[00:50:52] đây? Tham số hóa kiểu cho viết code làm
[00:50:54] việc nhiều kiểu dữ an toàn. Bình thường
[00:50:56] là đúng rồi. Mảng của PP nó rất nhiều
[00:50:59] vấn đề như này đúng không? Ok tôi biết.
[00:51:01] Xong rồi. Nếu mà kiểu array kiểu như này
[00:51:06] à cái này tôi biết mà. Cái cái kiểu lên
[00:51:10] cái danh sách kiểu arist này hay array
[00:51:13] một cái gì đó rồi bắt buộc kiểu dữ liệu
[00:51:15] trong đấy phải bắt buộc bằng kiểu gì
[00:51:16] giống kiểu high script thôi mà.
[00:51:19] Thế tôi biết tôi từng biết high script
[00:51:21] rồi nhá.
[00:51:24] Thế nó có đâu liên quan cái tôi đang học
[00:51:26] đâu.
[00:51:27] Mấy ông lừa lắm.
[00:51:36] generic.
[00:52:03] thì cái phần op kia chỉ xem chỉ trong
[00:52:05] một ngày thôi. Đúng như là tôi đang nói
[00:52:08] tôi muốn học từ đầu để mà thực sự biết
[00:52:09] được mình có hổng cái gì không. Hôm qua
[00:52:11] tôi hỏi ông em ông em mang tiếng nhiều
[00:52:13] năm kinh nghiệm về Java rồi nhá. dùng e
[00:52:16] nhiều xong rồi kiểu có nhiều cái cũng
[00:52:18] phải ngồi tự kiểu khi mà ông thực sự
[00:52:23] ông kiểu làm theo thói quen rồi ấy nhưng
[00:52:25] mà để mà ông thực sự phải hiểu để đi dạy
[00:52:28] người khác thì nó một trường hợp hoàn
[00:52:29] toàn khác nhá lúc đấy kiến thức ông sẽ
[00:52:31] phải khác bởi vì ông nói giống như kiểu
[00:52:33] bây giờ nói cho một đứa trẻ con một cái
[00:52:36] vài điều mà ông có hiển nhiên ấy ông sẽ
[00:52:38] phải thực sự phải hiểu theo một cái cách
[00:52:41] cách khác để mà nói đấy kiểu
[00:52:50] động.
[00:52:56] tôi chưa biết cách viết như ông muốn đâu
[00:52:58] nha. Ok. Thế chắc là cuối buổi này tôi
[00:53:01] sẽ gọi cho bạn riêng sau.
[00:53:05] À tưởng model nào cũng có luồng suy nghĩ
[00:53:07] thế này
[00:53:09] không? Model nào cũng có luồng suy nghĩ
[00:53:11] như này thì đúng. Nhưng là tôi đang nói
[00:53:13] là nếu mà ông dùng core ấy tôi thấy là
[00:53:16] không có hiển thị ra cái thót suy nghĩ
[00:53:18] luồng suy nghĩ vừa rồi đâu. Đấy thế nên
[00:53:21] tôi mới dùng antigravity hoặc là winsert
[00:53:23] thì nó hiển thị ra cái đấy.
[00:53:30] thì chỉ viết một lần đấy. Không phải
[00:53:31] viết hai hàm.
[00:53:34] Cái này tôi nghe hình như là nó liên
[00:53:36] quan đến tái sử dụng của hàm nữa thì
[00:53:38] phải. Ok. Nhưng cứ bình tĩnh bình tĩnh
[00:53:41] đã chưa học bên học 11 đã bình tĩnh.
[00:53:54] nước mưa đấy. À không phải nước mưa mà
[00:53:56] tiếng các bạn nh máy nước bơm ở trên rồi
[00:54:00] nó cứ bị tràn nước mà.
[00:54:09] unboxing. Đúnging hôm qua tôi cũng thấy
[00:54:12] có đề cập ở trong này.
[00:54:15] Đâu rồi? Cái từ unboxing đâu rồi?
[00:54:18] Nó có đề cập trong này này. Auto boxing
[00:54:19] này. Đấy đây đây đây. Thực ra cái auto
[00:54:21] boxing này hôm qua tôi có dịch ra ấy.
[00:54:24] Tôi hiểu là kiểu nếu mà gán như này thì
[00:54:27] nó sẽ hiểu là gán vào cái value của nó
[00:54:31] thì phải. Đấy thằng em tôi nói là như
[00:54:33] thế.
[00:54:39] cái archiving value của nó. Đấy, nghĩa
[00:54:43] đây là một cái class nhưng mà khi mà ghi
[00:54:44] như này sẽ hiểu là gán tự động gán vào
[00:54:46] cái value của nó.
[00:54:50] May có chữa không ạ? Ừ, chắc là tí tôi
[00:54:52] vẫn sẽ chữa bạn thôi.
[00:54:55] Biết high script thì tương đương với
[00:54:57] Java à anh?
[00:54:59] Ừ thì thực ra tôi nghĩ là tôi học thì
[00:55:02] cho biết thôi. Xem à mấy cái đoạn này
[00:55:05] chắc là mấy ông biết rồi
[00:55:07] về cái double hay các thứ thứ trên này
[00:55:09] thì nó cũng code để nói về cách khai báo
[00:55:11] thôi. Thường à
[00:55:14] nó viết hoa lên nó sẽ thành theo như tôi
[00:55:17] đang hiểu thế nó viết hoa lên nó sẽ
[00:55:19] thành một cái class và nó sẽ không còn
[00:55:21] đơn thuần là kiểu dữ liệu nữa mà nó là
[00:55:23] một cái class hơn. Đấy ngoài ra nó sẽ
[00:55:25] dùng được những cái hàm hôm qua tôi dùng
[00:55:27] thử mà. Đây ví dụ giả sử tôi dùng thử
[00:55:29] cái hàm à đây thằng D này đúng không?
[00:55:33] Đây tôi cho đây tôi viết hẳn hàm cạnh
[00:55:37] thằng D đi cho dễ hiểu. Đây
[00:55:40] à
[00:55:43] hôm hôm qua tôi thử dùng cái hàm này
[00:55:45] nhá.
[00:55:52] hình chẳng hạn.
[00:55:54] Đấy, tức là tức là kiểu thằng này thằng
[00:55:57] class nên nó có những cái method, có
[00:55:59] những cái hàm kiểu như thế này. Đấy,
[00:56:01] đương nhiên là làm gì có chuyện thằng C
[00:56:03] có thể gọi class kiểu tương đương như
[00:56:05] thế này được. Nó sẽ báo lỗi này. Đấy,
[00:56:07] mang tiếng là không phải IE nhưng mà nó
[00:56:10] cũng tự động bắt báo lỗi là thằng này
[00:56:13] thì nó chỉ đơn giản là kiểu nó là số
[00:56:15] thôi nên là nó không thể gọi được những
[00:56:18] hàm khác. Nó sẽ chỉ có giá trịể so sánh
[00:56:21] các thứ thứ kiểu so sánh toán tử thôi
[00:56:23] đúng không ạ? Đ như này thôi đúng không
[00:56:26] ạ? Nhưng mà thằng D này thì nó sẽ có
[00:56:28] những cái hàm khác nữa. Đấy kiểu kiểu
[00:56:30] như thế bởi nó một class nó sẽ có những
[00:56:33] mớ vân vân. Ui cháy.
[00:56:52] mình là từ thời đầu đấy.
[00:56:54] Xin chào bạn. Hi vọng các bạn à cảm thấy
[00:56:57] là nó có ích. Mình thì mình thì vui khi
[00:57:01] được dậy. Do dù là mình vẫn cố phấn đấu
[00:57:04] là nó sẽ giúp được các bạn gì đó nhưng
[00:57:06] mà đấy là phân đấu mình thôi. Nếu mà
[00:57:09] phải thực sự đem lại giá trị các bạn thì
[00:57:11] mình mới cảm thấy kiểu xứng đáng ấy đúng
[00:57:13] không ạ?
[00:57:16] À đấy giả sử mình viết cái class như này
[00:57:18] xong đúng không ạ? Thì hôm qua mình được
[00:57:20] dạy là sẽ là dùng cái javác như này này.
[00:57:24] Xong rồi đặt xong rồi gọi tên của nó. À
[00:57:28] hôm qua cũng bị nhầm nữa cơ. Cái này nằm
[00:57:29] trong thư mục này là phải CD 1 này 5 này
[00:57:33] xong rồi Java
[00:57:35] xong rồi price. Cái này tab một cái đúng
[00:57:38] không ạ?
[00:57:40] Đây như này à phải ghi đầy đủ chấm java
[00:57:43] đấy. Ơ vẫn báo lỗi à báo lỗi
[00:57:49] tại cái B này.
[00:57:53] Xem nào. Vừa nãy gõ à vừa nãy gõ ở đoạn
[00:57:56] này sai rồi. Cộng
[00:58:00] không có B ở đây chỉ có C thôi. Ok.
[00:58:11] Ok.
[00:58:17] Cái này nó sẽ tự động tạo ra cái thằng à
[00:58:20] chấm class này. Class này kiểu nó là
[00:58:24] file đã biên dịch đấy. Xong mình sẽ chạy
[00:58:26] cái file này là Java
[00:58:30] như này.
[00:58:32] Đấy. Đấy. Nó sẽ in ra kết quả các thứ.
[00:58:35] Cái này dùng season out nó kiểu in mà
[00:58:37] đúng không?
[00:58:39] ra
[00:58:40] nếu mà đọc cái file class này tôi cảm
[00:58:43] thấy kiểu trông nó đúng kiểu nó không
[00:58:46] phải file code nên mình hơi khó đọc đúng
[00:58:48] không ạ?
[00:58:54] xong chưa nhưng hôm qua tôi đã khá biết
[00:58:57] qua về cái vụ bên đấy. Tiếp theo là
[00:59:01] phân biệt các thứ hiểu về string pool.
[00:59:11] người nào dạy tôi ở đây ngay thời điểm
[00:59:13] này nên tôi sẽ chơi trò tôi sẽ dùng cái
[00:59:15] AI để dậy.
[00:59:17] Anh em có gì thông cảm nhé. Đấy tôi sẽ
[00:59:20] đây.
[00:59:42] Hôm trước là tôi nhớ cái người ta khuyên
[00:59:46] khi mà dùng AI ấy thì mấy ông biết mấy
[00:59:50] cái con Thinh Kingh này rồi đúng không?
[00:59:52] Con Thing Kingh này ngoài việc bảo nó
[00:59:54] thông minh ra ấy thì tức cả cái từ kinh
[00:59:57] là thể hiện việc là nó sẽ nghĩ. Thế nên
[00:59:59] là mình mà càng kiểu ra lệnh những cái
[01:00:03] prom nó rất là chi tiết và rất là chặt
[01:00:04] chẽ làm cho nó không phải nghĩ làm cho
[01:00:09] nó bị kiểu bó hẹp vào những cái
[01:00:12] những cái mà ông muốn làm nên là có thể
[01:00:15] là nó sẽ giới hạn khả năng của nó. Chuẩn
[01:00:18] là ông sẽ chỉ nên nhập input và output
[01:00:21] thôi. Nghĩa là nhập đầu vào là gì này và
[01:00:24] mong muốn kết quả là gì. Đấy, xong rồi
[01:00:26] nó sẽ tự nó sẽ tự kiểu nghĩ cách để mà
[01:00:31] nghĩ giai đoạn code, nghĩ cách để làm ra
[01:00:34] được cái kết quả như thế. Đương nhiên là
[01:00:39] có thể nó sẽ không đúng cách mà mấy ông
[01:00:41] muốn. Đấy, do mới có khái niệm planing
[01:00:43] này. Nghĩa là trong những cái trường hợp
[01:00:45] là khó hoặc là ông chỉ cần bảo nó là hãy
[01:00:47] viết ra để tôi confirm lại đã, tôi xác
[01:00:50] nhận lại đã thì mới được làm. Đấy, thì
[01:00:52] tránh việc đợi thời gian hay mất công gì
[01:00:54] đó. đúng không ạ? Nhưng mà nói chung là
[01:00:56] dùng mấy con thình kinh này nên là để
[01:00:58] cho nó nghĩ mình ra lệnh ngắn thôi. Còn
[01:01:01] nếu mình ra lệnh dài quá nó giới hạn khả
[01:01:03] năng của nó thì mình đã dùng mấy con cơ
[01:01:05] bản nó nhanh. Đấy,
[01:01:17] nếu thế chứng tỏ với chính mình là người
[01:01:20] chọn cái chọn cái thình kinh mà tức là
[01:01:22] chính mình là người nghĩ nhiều và nghĩ
[01:01:24] rằng là nó nên nghĩ nhiều so bây giờ ông
[01:01:27] lại bảo nó nghĩ nhiều thì đấy là lỗi của
[01:01:29] mình đấy chứ đúng không? Đấy mình chỉ
[01:01:31] chọn những con cơ bản để làm những cái
[01:01:33] việc cơ bản thôi. Còn những cái việc còn
[01:01:35] nâng cao việc phải suy nghĩ nhiều. Ví dụ
[01:01:37] là nhiều lúc là tôi bắt nó đọc gần như
[01:01:40] là cả project đấy để mà nói về cái luồng
[01:01:45] một cái luồng ở đó thì tôi dùng mấy cái
[01:01:46] con kiểu như này còn không bình thường
[01:01:48] không. Đây tôi cứ dùng con này cho dễ
[01:01:50] nha. Hoặc con Jini này tôi cảm thấy con
[01:01:52] Jim Mini này nghĩ như không nghĩ thế nên
[01:01:56] có dừng nói những cái đơn giản. Ô ok.
[01:02:04] à. Đấy, hôm qua ông em có ngồi nhắc về
[01:02:06] cái khái niệm về quản lý bộ nhớ
[01:02:10] hip này ở trong Java. Kiểu bình thường
[01:02:13] mình dùng PP thì mình sẽ ít để ý về cái
[01:02:16] bộ nhớ lắm. Kiểu nó sẽ ít khái niệm là
[01:02:19] kiểu tràn bộ nhớ rồi các thứ thứ. Xong
[01:02:22] rồi Java cũng phải quản lý bộ nhớ tốt
[01:02:24] hơn đấy đúng không ạ? ngay việc khai báo
[01:02:27] đã kiểu khai báo kiểu
[01:02:30] kiểu nói chung là khai báo đã thể hiện
[01:02:31] phần nào về cái quan tâm về bộ nhớ rồi
[01:02:34] đúng không ạ?
[01:02:45] quen thuộc này. Đã có chỗ này chưa? Nếu
[01:02:48] có thì trả về reference chưa tạo mới thì
[01:02:51] ồ cái này hay phết nhỉ.
[01:02:54] Đấy, không học cơ bản làm sao mà hiểu
[01:02:57] được những cái như này.
[01:03:08] mấy ông toàn mấy ông biết rồi vào kiểu
[01:03:12] nói kiểu gọi như là mấy ông chỉ nói tôi
[01:03:14] đúng hay sai thôi. Bây giờ mấy ông nói
[01:03:16] thế là tôi kiểu tôi không biết được à.
[01:03:19] Nó sẽ bị kiểu
[01:03:22] gọi như nà nhỉ. Đấy giống kiểu
[01:03:23] overthinking giống như ông kia vừa nói
[01:03:26] sẽ bị overlúng không? Nó quá tải kiến
[01:03:28] thức cùng một lúc. Buổi một thì tôi học
[01:03:32] tôi cảm thấy thế là rất là vui rồi. À
[01:03:34] đây buổi hai nhầm có lưu lại stream nhá.
[01:03:37] Ông có thể tôi lại cũng được nhá.
[01:03:47] nặng lớn giống như hồi trước tôi làm
[01:03:49] file Excel cũng có đấy. Ngồi read Excel
[01:03:52] là một chuyện ngồi WR ra file Excel
[01:03:55] chết. Xong rồi hồi đấy là dùng cái thư
[01:03:57] viện nữa Larel kết hợp với Excel nữa. Ui
[01:04:01] xong rồi về sau không dùng thư viện nữa.
[01:04:03] Dùng hết hàm thuần của PP thì nó mới
[01:04:05] nhanh. và lẫn cả trò là
[01:04:08] kiểu một loạn nói chung là dùng hạp
[01:04:11] thuần ấy nó là dùng bài toán con trò ấy
[01:04:13] kiểu trò đến các thứ thứ để mà ghi thêm
[01:04:15] dữ liệu thôi chứ không phải ngồi mở lại
[01:04:17] cả cái file đấy. Bởi vì cái thư viện kia
[01:04:19] là ông hình dung thư viện đấy cứ mỗi lần
[01:04:22] gọi đến nó mở lại cả cái file xong nó
[01:04:24] ghi thêm vào xong rồi đóng vai thế nên
[01:04:26] chết đấy bởi vì loát cả cái file ra thì
[01:04:29] chẳng chết RAM đúng không ạ? Đấy,
[01:04:49] phân biệt string videoer và string
[01:04:51] buffer. Ok, để tôi nốt lại luôn. Cảm ơn
[01:04:54] nhé. Ok.
[01:04:56] À lưu
[01:04:59] tôi thêm về string builder đúng không?
[01:05:04] Và string buffer đấy
[01:05:09] đúng không ạ? Ok.
[01:05:17] Đấy để nó tự soạn cho tôi.
[01:05:21] Dùng AI để dạy mình.
[01:05:22] là thầy
[01:05:25] PP à đâu à đang học note có theo luôn
[01:05:31] khóa này không thầy không cái này tôi
[01:05:33] đang tự học nhá tôi cho mấy ông vào học
[01:05:35] cùng cho vui thôi chứ chứ tôi không
[01:05:39] khuyên mấy ông học kiểu dạng như nào
[01:05:42] mấy ông bỏ cái này để sang học cùng tôi
[01:05:44] hay gì gì đó mấy ông cứ học cái của mấy
[01:05:47] ông đang tốt đã mấy ông xem cái này tham
[01:05:49] khảo thôi chủ yếu. Mà mấy ông biết thì
[01:05:52] mấy ông dạy tôi nữa đấy. Quá tuyệt vời
[01:05:54] chứ tôi trong cái khóa này tôi là người
[01:05:57] học chứ tôi không dạy thìì mấy ông đâu
[01:05:59] nhá.
[01:06:01] Ok nó phải ra một cái các thứ các thứ tí
[01:06:04] xem sau. Đấy đây đây đây. Trong trường
[01:06:06] hợp mà nó thấy phức tạp hơn một tí là nó
[01:06:08] bắt đầu viết ông cái tab toolit này.
[01:06:12] Xong rồi rất nhiều lúc là nó ghi hẳn cái
[01:06:13] plan rồi các thứ. Và một trong những cái
[01:06:15] hay nữa của nó so với việc là tôi dùng
[01:06:17] quị Vinser hồi trước phải tạo file Mdown
[01:06:21] ấy, đó là cái này có comment đúng không
[01:06:23] ạ? Đấy, comment vào đây là tao không
[01:06:25] muốn thế này chẳng hạn, tao muốn kiểu
[01:06:26] khác vân vân vân. Đấy, comment vào đây
[01:06:29] thì cái này mới càng thể hiện rõ. Giống
[01:06:32] như là mình bây giờ không còn là coder
[01:06:33] mấy nữa. Mình là PM là mình là người sẽ
[01:06:36] giao việc và quản lý
[01:06:39] kiểu review lại code này, review cách nó
[01:06:42] code, review luồng nó suy nghĩ này vân
[01:06:44] vân vân. Đấy.
[01:06:53] à cái G này là tôi tự ghi thôi. Cái file
[01:06:55] này file tôi tự ghi ấ mà để lên cái
[01:06:59] kế hoạch học mà nếu mà xem trông giao
[01:07:02] diện kiểu này chắc là đẹp hơn này.
[01:07:07] lắm.
[01:07:09] Tôi tôi xem chắc là tôi xem quen kiểu
[01:07:12] bên này rồi. Thông cảm.
[01:07:23] phải rõ cái hit với stack trong Java nào
[01:07:25] nữa. Đấy, ông này lại nói thêm một từ
[01:07:28] mới tôi không biết kìa. Stack à? Ồ, ok.
[01:07:31] Stack là hình như là stack giống cái
[01:07:33] kill đúng không?
[01:07:35] Ừ không phải giống cái kill nhưng ý tôi
[01:07:37] là kiểu kiểu nó cũng thường đi với kill
[01:07:38] ấy. Kiểu một cái trong PP thì đương
[01:07:41] nhiên chúng ta làm việc với kill rồi.
[01:07:43] Một cái kìa first in first out đúng
[01:07:47] không? Stack là tôi nhớ là first in l
[01:07:49] out đúng không? Giống kiểu như cái trong
[01:07:52] đĩa mà đúng không?
[01:07:53] Còn hit là gì? Tôi chưa biết đâu. Đấy.
[01:07:56] Đấy. Đây.
[01:08:03] thêm cho tôi về hit và stack. Không biết
[01:08:08] là gì cứ nốt lại thôi.
[01:08:20] kiểu chấm chấm chấm. Ok. Xem nào. Tất cả
[01:08:23] trỏ đều cùng một object trong string
[01:08:24] boo. Hả? Kiểu gì vậy? Hello. Này
[01:08:28] đâu có tạo bằng littal tạo bằng ba chấm
[01:08:32] đâu. Địp à.
[01:08:35] Này đều khai báo bình thường mà nhỉ.
[01:08:47] sánh
[01:08:49] bình thường là so sánh giá trị mà nhỉ.
[01:08:51] Bây giờ trong trường hợp này so sánh địa
[01:08:53] chỉ bộ nhớ à? Uầi
[01:08:55] vãi.
[01:08:58] Cái này liên quan đến kiểu địa chỉ bộ
[01:09:00] nhớ của con trỏ các thứ. À
[01:09:17] Ok. Tôi có thể xem mà.
[01:09:20] À đây khai báo kiểu như này sẽ là khai
[01:09:24] báo kiểu dùng trong tôi cứ tưởng lal là
[01:09:27] cái ba chấm này ạ. [tiếng cười] Nó là
[01:09:29] cái dấu nháy này. Ok ok ok.
[01:09:34] Đấy,
[01:09:36] nghĩa là kiểu khai báo kiểu như này thì
[01:09:38] tất cả ba thằng đang trò về chung chung
[01:09:40] một cái bộ nhớ thành ra giá trị nó sẽ
[01:09:44] giá trị bằng nhau. Nhưng mà cái việc hai
[01:09:46] dấu bằng này mà so sánh địa chỉ bốn nhớ
[01:09:48] thì tôi đang hơi thắc mắc thô không sao.
[01:09:52] Còn đây khai báo hẳn một thằng mới à
[01:09:54] giống kiểu một cái đối tượng mới. Đây
[01:09:57] khai báo trong PP sẽ new object đúng
[01:09:59] không? Một đối tượng mới. Đúng rồi,
[01:10:01] object mới đây. Ok. trong híp. Đấy, lại
[01:10:05] tạo thêm một object nữa. Uầy, đấy, AI nó
[01:10:08] tự viết ra các thứ thứ trông cũng hay mà
[01:10:10] đúng không? Đấy, bây giờ AI cá nhân hóa
[01:10:13] việc học hành.
[01:10:16] Uầy, ba hai dấu bằng bây giờ là so sánh
[01:10:19] địa chỉ ạ, không phải là giá trị. À ui,
[01:10:25] đúng rồi. Bởi vì đây là chuỗi đúng
[01:10:27] không? Nếu mà chuỗi thì sẽ phải dùng cái
[01:10:29] Tôi nhớ là chuỗi phải dùng string equal
[01:10:32] đúng không? Tôi nhớ là thế.
[01:10:38] Đúng rồi. Uầy ui mình còn biết trước bài
[01:10:41] này. Thông cảm tôi đang tự học nên tôi
[01:10:44] sẽ hơi tự khen bản thân hơi tự luyến một
[01:10:47] tí.
[01:10:49] Mấy ông đã học kiêm túc thì mấy ông sẽ
[01:10:50] không thích cho lắm.
[01:10:56] nhớ.
[01:10:58] Cái này tôi bảo rồi ông nào mà học PP mà
[01:11:01] nhảy sang đây học cùng tôi cảm thấy cũng
[01:11:03] choáng như tôi thôi. Kiểu cái này kiểu
[01:11:05] khai sáng ấy. Đấy
[01:11:09] cái này chắc chắn là phải kiểu
[01:11:12] tôi nghĩ là bắt buộc là phải có một cái
[01:11:14] ấn tượng kiểu như thế. Ấn tượng như tôi
[01:11:16] vừa bày tỏ cảm xúc ấy thì nó mới nhớ
[01:11:19] hình sâu dung sâu trong đầu được chứ cái
[01:11:21] này dễ quên lắm vì mình đang có code gì
[01:11:25] đâu. Mình có đang thực hành gì đâu.
[01:11:32] rồi. Tôi nhớ thế.
[01:11:35] New string. Cái cái này chắc là không có
[01:11:37] thể à đâu cái S6 này cũng có thể chấm
[01:11:41] equal được này. Tôi đang tưởng là à cái
[01:11:44] này là không phải nguyên thủy nhở. Con
[01:11:46] này cũng là class rồi. Con này không
[01:11:49] được nhỉ.
[01:11:50] Đây như này được đúng không? À cha tôi
[01:11:53] nhớ cha là phải là
[01:11:56] cha tôi nhớ nó là phải là khai báo giống
[01:11:58] kiểu m đúng không nhỉ?
[01:12:01] Đây kiểu như này nhở bốn ký tự chẳng hạn
[01:12:03] đúng không?
[01:12:08] từng từng cái từng cái nhỉ.
[01:12:19] kiểu này được mà đúng không? Không được
[01:12:20] à?
[01:12:22] Hay là string xong rồi như này mới được.
[01:12:26] Tôi nhớ có một cái là khai báo cái a
[01:12:36] hỏi tôi tự vỡ ra nãy giờ ấy chứ.
[01:12:44] khai đấy. Tôi nhớ có khai báo con cái
[01:12:46] này mà
[01:12:48] xem nào.
[01:12:50] Đây à.
[01:12:58] nhiêu. Hồi trước tôi nhớ là phải khai
[01:13:00] báo là có ba kiểu tối đa bao nhiêu ấy.
[01:13:03] Tôi không khai báo nữa à.
[01:13:12] mà đúng không? Không thấy bao lỗi gì cả.
[01:13:14] Tôi nhớ có một thằng bắt buộc phải khai
[01:13:16] báo là độ dài của mảng là bao nhiêu ấy,
[01:13:20] độ dài của chuỗi là bao nhiêu chẳng hạn.
[01:13:22] Thế
[01:13:44] theo cái mảng cán cho đúng không? Nhưng
[01:13:46] mà bây giờ giả sử tôi để như này thì tôi
[01:13:48] đang thấy không báo lỗi gì cả thì rốt
[01:13:50] cuộc thằng này nó như nào? Nó có báo lỗi
[01:13:51] gì không?
[01:13:58] không nhỉ? Thử xem nhá.
[01:14:06] constant à? Ừ. Constant này hơi vô nghĩa
[01:14:09] nhỉ. Sân này chẳng có giá trị gì đúng
[01:14:11] không?
[01:14:27] tôi biết khái niệm về constant nhưng mà
[01:14:28] bọn tôi không khai báo constant như thế
[01:14:30] mà tôi phải khai báo nó là constant thì
[01:14:33] tức là nó mới constant.
[01:14:40] Nói chung là không sao. Cái vừa rồi tôi
[01:14:43] mới gọi là nhớ lại thừ kiến thức cũ
[01:14:45] thôi. Coi như là mình chưa biết gì nhá.
[01:14:48] Mình học từ đầu mà. Ok
[01:14:50] thì tôi vẫn sẽ có thắc mắc là thằng à
[01:14:53] bởi vì thằng này là thằng wpper class
[01:14:57] đúng không? Nên nó sẽ có hàm này. Đấy.
[01:15:00] Ok. Thằng này chắc tương tự nhỉ? Thử 7
[01:15:05] 6. Ừ. Th cũng tương tự này. Thế ừ new
[01:15:09] string này. Chắc là hai thằng string này
[01:15:11] là class giống nhau rồi nhỉ.
[01:15:14] String class.
[01:15:17] Ừ. Hai thằng này là một rồi.
[01:15:32] lừa tôi đúng không?
[01:15:35] đâu
[01:15:49] đúng không?
[01:15:51] Ừ tôi hiểu ý không? Có thể là tra thì nó
[01:15:54] sẽ là có tra này không? Không không có
[01:15:59] lú nhỉ.
[01:16:02] String chỉ là một object, một class thôi
[01:16:04] đúng không? Ok. Ơ có gậy có các thứ thứ
[01:16:07] này đây. Nó cũng bằng tra này.
[01:16:11] Nhưng thằng tra này chắc là nó sẽ không
[01:16:13] có.
[01:16:21] hàm có sẵn trong mọi class. Tôi đang tôi
[01:16:24] đang lúc đầu tôi tưởng là string này
[01:16:26] cũng là một thằng grapper class
[01:16:29] nhưng mà không thằng này chỉ là một
[01:16:30] class bình thường thôi đúng không?
[01:16:39] Ok để thử thử cái này phát đây như này.
[01:16:44] Giả sử trong trường hợp này đúng không?
[01:16:46] Thì thằng này không thể so sánh
[01:16:49] được bởi vì đây là đây đang mảng với
[01:16:54] chuỗi đúng không?
[01:17:01] thằng này như này lú nhỉ.
[01:17:15] kiểu gì thế anh? À không, anh tạo phím
[01:17:17] tắt và anh dùng cái
[01:17:28] hồi trước là anh có cái để mà kiểu chỗ
[01:17:31] màn hình ở bên góc bên này thì hiển thị
[01:17:33] ra bàn phím đang gõ có gì ấ anh cũng
[01:17:35] chưa cài th quên mất đấy.
[01:17:42] động chuyển string tôi lại nhớ lại quả
[01:17:44] script mấy cái lú. Ok
[01:17:47] không sao mình cứ từ từ đã.
[01:17:57] rồi à
[01:18:01] nó là cái an thôi. Anh nhớ là cái an để
[01:18:03] mà tab táab qua các thứ thôi. Anh kiểu
[01:18:06] đang thao tác kiểu nhanh quá anh cũng
[01:18:08] không để ý.
[01:18:13] bằng được. Đúng tôi tôi hiểu
[01:18:17] à Ồ ok bằng bằng này thực ra nó liên
[01:18:20] quan đến địa chỉ thôi đúng không? Không
[01:18:22] phải là so sánh giá trị nữa.
[01:18:34] array tra. Uầi có thế luôn à. Hay vậy.
[01:18:38] Đâu xem à
[01:18:43] đang học cơ bản nâng cao nữa. Buồn cười
[01:18:46] quá chưa? Đây như này đúng không? Cái
[01:18:50] này là đây
[01:18:53] tu
[01:18:55] cha ar ui đỉnh à. So sánh kiểu mẹ
[01:19:02] thằng PP đọc đoạn này. What the
[01:19:12] giờ tôi học Java tôi cảm thấy tôi buồn
[01:19:14] cười quá c thế giới khác.
[01:19:19] Tôi không biết là mấy ông từ Java sang
[01:19:21] PP như nào. Tôi chắc chắn là từ PP sang
[01:19:23] Java cho buồn cười
[01:19:41] Tôi nhớ vụ pu này rồi.
[01:19:54] lên Java. Hôm qua ông em cũng ngồi nói
[01:19:56] là công ty em vẫn dùng Java 8 đấy. Đặc
[01:19:59] biệt là ông em là bị ngân hàng mà. Xong
[01:20:02] rồi kêu là còn Java mười mấy rồi nghe
[01:20:03] kiểu
[01:20:08] intern được chưa? Đưa world vào pool và
[01:20:13] trả về reference lấy từ po.
[01:20:17] Đợi đợi tí đợi tí giả sử không đọc phần
[01:20:19] dưới. Đấy tôi zoom to lên. Không biết
[01:20:22] mấy ông có
[01:20:25] hay zoom cho tôi không? Chắc chắn có thể
[01:20:27] là không. Nhưng đại khái tôi thường hay
[01:20:28] zoom mọi thứ rất là to. Đấy. À đợi tí
[01:20:31] except nó mất cái hiển thị đây nữa. Đấy.
[01:20:37] Coi như không đọc thấy phần dưới nhá.
[01:20:38] Không nhìn thấy phần dưới nhá.
[01:20:40] Thì tôi tự hiểu đoạn này đã trước khi
[01:20:43] xuống ví dụ.
[01:20:45] À in term đưa chuỗi vào p tức là kiểu
[01:20:50] là kiểu đầu tiên là tạo mới ngoài pu lúc
[01:20:55] đầu là hello đúng không? Ok.
[01:20:58] So với thêm một cái nữa.
[01:21:04] như cũng
[01:21:06] tạo mới mà nhỉ. Cũng có vào pool đâu
[01:21:09] đúng không? Đây tôi nhớ là thế
[01:21:20] Chắc là chỉ là tạo mới thôi. Chắc chắn
[01:21:23] là kiểu gì nó cũng ngoài pu rồi. Cái này
[01:21:24] nó hơi thừa đúng không?
[01:21:27] Đấy, tôi vừa học xong tôi nhớ mà đừng
[01:21:30] lừa. Đấy, in term đấy. Thêm chữ interm
[01:21:35] là nhét nó lại vào pool này. Ok. Xong
[01:21:39] rồi trả về reference tức là kiểu địa chỉ
[01:21:42] con trỏ trỏ về địa chỉ đúng không? Đấy.
[01:21:46] Rồi lấy ra từ pool
[01:21:59] Nghĩa là nghĩa ở đây vừa nãy có ông nói
[01:22:02] về cái hip đấy. Nó nhắc về cái hip mà
[01:22:05] đúng không?
[01:22:07] Đâu cái hip rồi
[01:22:11] đấy. Bình thường là new là sẽ tạo trong
[01:22:13] hip. Hip cũng là bộ nhớ. Nhưng mà hit nó
[01:22:16] khác với pu đúng không?
[01:22:19] Nếu thế thì rõ ràng là có. Đợi đợi tí
[01:22:21] đợi tí nhá. Sẽ có hip này, po này. Xong
[01:22:25] vừa nãy có ông còn nói stack này đúng
[01:22:26] không?
[01:22:28] P nó cứ hình dung là mặc định dùng cái
[01:22:31] này thì nó sẽ vào pool đúng không? Cái
[01:22:34] này bằng new string thì nó sẽ vào hit
[01:22:37] đúng không? Nó sẽ không vào p nữa. P là
[01:22:40] cái sân chơi chung đúng không? Đấy. Thế
[01:22:42] stack này nữa là gì?
[01:22:46] Ôi con P nằm trong híp nữa.
[01:22:56] híp với stack thôi đúng không?
[01:23:01] Ok. Hơi lú đấy nhưng mà thôi không sao
[01:23:05] c sống mà.
[01:23:08] Đấy.
[01:23:18] hay sai nhá. Không, về sau tôi học mà
[01:23:21] tôi mất gốc tôi lại bảo đổi tại qua
[01:23:24] YouTube thì xếp chửi.
[01:23:31] bình luận trên YouTube.
[01:23:38] double check à kiểm tra chéo nhau nhá.
[01:23:40] Tôi không biết kiến thức gì coi như là
[01:23:42] tôi tôi chẳng lẽ tôi lại hỏi ai
[01:23:58] chưa chưa chưa đến lúc quá tải thông tin
[01:24:00] thế cứ bình tĩnh đã tôi không nhớ hết
[01:24:03] đống kia đâu đấy
[01:24:19] Gravity với Cloude thỉnh thoảng Gemini.
[01:24:23] Ok rồi.
[01:24:26] Tạo object mới này. Xong rồi đưa world
[01:24:29] và pool bằng cách là dùng cái hàm
[01:24:31] intern. Ok.
[01:24:34] Kiểu Fer được vào
[01:24:38] trả về. Trả về á.
[01:24:45] Không báo lỗi mà đúng không? Chẳng qua ở
[01:24:47] đây là thêm kiểu nó sẽ trả về cái địa
[01:24:50] chỉ đúng không? Kiểu nhét mày vào cái ô
[01:24:53] kiểu nhét mày vào cái sân bóng này đúng
[01:24:55] không? trả về cái phiếu mày thích thì
[01:24:57] mày có thể cầm cái phiếu này để gọi đến
[01:25:00] thằng đấy. Đấy, kiểu kiểu thế đúng
[01:25:01] không? Ok.
[01:25:07] Trong trường hợp này sẽ bằng bằng được
[01:25:08] này.
[01:25:11] Tái sử dụng chuỗi trong p. Ok.
[01:25:15] Uầy đoạn này lú thật. Kiểu nếu mà kiểu
[01:25:18] không làm chuyên giả sử giả sử nhá. Tôi
[01:25:21] PP sang đây code Java tôi không biết về
[01:25:25] cái p cái hit cái stack mấy ông đang
[01:25:27] nói. Đấy tôi chỉ cần biết là khai báo
[01:25:30] chuỗi thôi. Tôi có thể new string này
[01:25:31] hoặc là khai báo thẳng luôn như này đúng
[01:25:33] không? Đấy tôi sẽ không biết tái sử dụng
[01:25:35] lại cái pu hay các thứ thứ đúng không?
[01:25:38] Đấy ui lúc đấy lú lúc ấy một là mình sẽ
[01:25:42] bị lỗi khi mà code hai là mình sẽ không
[01:25:45] biết tối ưu về bụn nhớ nhở.
[01:25:48] Đúng kiểu chỉ code được thôi nhở. Tôi
[01:25:51] nghĩ phải học chuyên sâu như này thì mới
[01:25:52] tối ưu được những cái dương con bụn nhớ.
[01:25:55] Ôi quá tải kiến thức luôn ý.
[01:26:03] bên JavaScript cũng kiểu cộng chuỗi cộng
[01:26:07] chuỗi trong buụt cười ấy. Trong PP thì
[01:26:10] đương nhiên là không có cái khái niệm
[01:26:11] cộng chuỗi như này mà phải có dấu riêng
[01:26:14] cộng cộng trừ chúng ta chỉ làm với
[01:26:19] chúng ta chỉ làm với số thôi. Cộng chuỗi
[01:26:23] khó chịu thật.
[01:26:31] nhớ mang máng ấy nhưng là nó còn liên
[01:26:33] quan đến cả cộng được array mà đúng
[01:26:35] không?
[01:26:36] PP lại có cộng array nhá. Đúng rồi. Tôi
[01:26:40] nhớ PP có vụ cộng array. Tức là sao? Bởi
[01:26:42] vì tôi nhớ
[01:26:44] cái này liên quan đến kiến thức mà tôi
[01:26:46] từng học Java thời đấy nhá. Lâu rồi tôi
[01:26:49] cứ hỏi lại mấy ông th chắc nhá. là kiểu
[01:26:51] tôi nhớ là cái chuỗi này thực ra là
[01:26:53] giống như vừa nãy khai báo cái tra tra
[01:26:55] vừa nãy là bản chất là nó là cái mảng
[01:26:58] mảng danh sách các ký tự đúng không? Đấy
[01:27:01] thế nên là khi cộng như này ngang bằng
[01:27:03] là array cộng với array đúng không? Được
[01:27:05] mà đúng không? Thực ra cái này đang chỉ
[01:27:08] array ba chữ cộng với array hai chữ mà
[01:27:10] đúng không? Thì chắc là array cộng với
[01:27:12] array chắc mại không được à.
[01:27:25] đúng mà đúng không? Nghĩa là trong
[01:27:26] trường hợp như thế này nhá. Giả sử chuỗi
[01:27:29] này là có năm chữ đi đúng không? Giả sử
[01:27:33] là S12 tại 0 như này sẽ bằng H được mà
[01:27:39] đúng không? Không được à?
[01:27:43] À cái này là string mất rồi. Nó không
[01:27:45] còn array nhỉ.
[01:27:55] còn chọc đến từng cái a kiểu cái index
[01:27:59] của
[01:28:05] mà tôi nhớ là có so sánh kiểu thế mà
[01:28:10] chắc không phải thằng string này đúng
[01:28:11] không?
[01:28:18] Không sao, chắc là về sau học kể gì sẽ
[01:28:20] đến đoạn đấy. Tôi sẽ tự vận lẽ ra sau.
[01:28:23] Ok.
[01:28:29] Tạ up mới tại run time.
[01:28:32] 13 với 12 là khác. Ồ bởi vì cái này là
[01:28:38] sau đó nó mới cộng. Uầi lại lại thêm một
[01:28:40] cái lú nữa.
[01:28:55] khái niệm run time nữa nhỉ. Trong PP thì
[01:28:58] nó sẽ không có. Nó sẽ so sánh hai thằng
[01:29:00] bằng nhau luôn. À đây đây là khác địa
[01:29:02] chỉ nhở. Đúng đúng đúng đúng đúng đúng.
[01:29:05] Giá trị thì bằng nhau nhưng địa chỉ
[01:29:07] khác. Ok. Đây là đúng rồi. Ở trong này
[01:29:10] nó vẫn thường là liên quan đến cái khái
[01:29:11] niệm về địa chỉ nữa.
[01:29:19] đấy tôi có nhớ mang máng nên tôi không
[01:29:24] sao tôi hỏi thế thôi. Hơi a hơi làm
[01:29:28] phiền mấy ông tí.
[01:29:30] Đ tôi về sau tôi sẽ
[01:29:33] về sau tôi sẽ tự vỡ lẽ ra và lúc đấy tôi
[01:29:36] sẽ à thế ra thế lúc đấy ông còn lú hơn
[01:29:41] mẹ nói đến cái đoạn nào vậy
[01:29:44] đây so sánh với PP ra script ui đợi mãi
[01:29:47] sao những cái bên kia không có xem nào.
[01:29:52] Đây nói chung là liên quan đến so sánh
[01:29:53] cùng địa chỉ. Ok rồi.
[01:29:57] À nãy giờ còn chưa chạy thử đoạn code
[01:29:58] này. Tí chạy thử để mày in ra xem trông
[01:30:00] như thế nào.
[01:30:03] Đúng rồi. So sánh value không có string
[01:30:05] poo hay cái gì cả. Đơn giản dễ dễ học
[01:30:10] đấy. Đúng là làm quen với đô la còn ja
[01:30:13] script. Ok so sánh ừ so sánh cả ba dấu
[01:30:17] bằng luôn. Đây ba dấu bằng không phải
[01:30:19] mỗi kiểu giá nó là kiểu giá trị với cả
[01:30:22] giá trị
[01:30:24] kiểu kiểu dữ liệu với giá trị luôn.
[01:30:31] này không có ba dấu bằng nhỉ đúng không?
[01:30:33] Nó sẽ so sánh kiểu là cùng địa chỉ
[01:30:38] reference đúng không ạ? Đấy. Bract ok
[01:30:42] luôn đã nhớ.
[01:30:45] Visual bộ nhớ.
[01:30:49] Đấy. Ui còn hiển thị bộ nhớ kiểu này.
[01:30:51] Uầy.
[01:30:53] Đây vừa nãy bạn kia có đề cập thự ạ. Nằm
[01:30:56] trong híp đúng không? Nên là có pu đây
[01:31:00] ab thì cả cái thằng biến này và biến này
[01:31:03] đều trỏ đến hai. Ok.
[01:31:06] Còn nếu mà hit ở ngoài pool thì thằng
[01:31:09] object 1 này sẽ cho đến cái string này.
[01:31:12] Object 2 chò string này với địa chỉ khác
[01:31:15] nhau. Uầ thấy không? AI
[01:31:22] không? Đấy là tôi nãy giờ tôi còn tôi
[01:31:24] còn hỏi mấy ông ấy tôi mà nãy giờ giả sử
[01:31:26] tôi học một mình tôi cứ thắc mắc gì tôi
[01:31:29] lại hỏi ai ai trả lời cho tôi. Nó có thể
[01:31:32] nó có thể đúng có thể sai không biết
[01:31:34] được nhưng mà ý tôi là cá nhân hóa là
[01:31:36] kiểu phục vụ cho mình cá nhân rất là tốt
[01:31:39] đúng không?
[01:31:41] Tóm tắt quan trọng uầy
[01:31:45] cái này tôi nghĩ là mấy ông cũng thể
[01:31:47] tham khảo học được ấy chứ nhỉ? Được ấy
[01:31:49] chứ quá ổn sao? các cách tạo stream
[01:31:55] đây gọi là literal.
[01:31:57] Ok.
[01:31:59] Tôi không biết là mấy ông có nhớ hết tất
[01:32:01] cả cái từ khóa với định nghĩa không
[01:32:03] nhưng mà tôi thấy là cũng nhiều phết đấy
[01:32:05] nhỉ. Nhiều phết. PP nó không nhiều thế
[01:32:08] này đâu.
[01:32:10] Run time là lúc code chạy. Tine là lúc
[01:32:13] biên dịch. Tine là run time là nó
[01:32:18] gì nhở? Chắc là tôi sẽ phải biết cái đấy
[01:32:21] sau.
[01:32:22] Thì tôi tôi định hỏi cái nhưng chắc là
[01:32:24] tôi sẽ khi đến cái đoạn đấy thì tôi sẽ
[01:32:27] hỏi sau. So sánh địa chỉ bộ nhớ và so
[01:32:30] sánh nội dung buồ. Ok.
[01:32:34] Tại sao phải dùng của không biết string
[01:32:36] được tạo bằng high new? Đúng. Ồ quá hợp
[01:32:39] lý có thể dùng kết quả sai khi so sánh
[01:32:42] string. Đúng an toàn 100% nó n giống như
[01:32:45] kiểu hai dấu băng hay ba dấu băng đúng
[01:32:46] không ạ?
[01:32:52] chứ bình thường không đề cập nhớ. Đúng
[01:32:54] tôi tôi hiểu
[01:32:56] thì ý tôi là mấy cái này nó quá rộng và
[01:32:59] cũng có nhiều lý thuyết mà đúng không?
[01:33:01] nhiều lý thuyết đấy sẽ thậm chí là mình
[01:33:04] nhớ nhiều quá mình cẩn thận bị nhầm ấy.
[01:33:07] Đấy
[01:33:08] nhưng cái này công nhận hay đấy nghĩa là
[01:33:10] khi mà mình phải đến tôi nghĩ là may ý
[01:33:13] bởi vì tôi đã đến cái ngưỡng mà kiểu giả
[01:33:15] sử là tôi biết so sánh rồi. Giả sử tôi
[01:33:18] làm PP nó cũng tương đối rồi. Khi mà tôi
[01:33:20] sang đây tôi mới thấy kiểu so sánh được
[01:33:22] tôi mới cảm thấy nó hay. Chứ nếu mà giả
[01:33:25] sử tôi mới học Java là tôi nhìn ống này
[01:33:27] h giống như hồi đầu tôi mới học Java
[01:33:28] nhìn ống này tôi không nhớ lắm tôi không
[01:33:30] ấn tượng lắm chỉ thấy nó khó kiểu nó bị
[01:33:35] khó phức tạp hóa vấn đề lên ấy. Đấy
[01:33:37] nhưng bây giờ khi mà mình đang từ PP
[01:33:39] mình biết được là PP có những cái nhược
[01:33:41] điểm gì rồi đúng không? Mình sang đây
[01:33:43] mình biết à cái thằng này tại sao nó lại
[01:33:46] phổ biến thế. Bởi vì nó tận nó đấy có
[01:33:49] những cái nhỏ nhỏ như này nó đã
[01:33:52] này tiết kiệm bộ nhớ tăng hiệu suất này.
[01:33:54] Đấy. Ui
[01:33:57] xịn quá xịn. Khi nào dùng intern fesser
[01:34:00] tôi sẽ nhớ cái cái đoạn đấy
[01:34:04] khi nhiều string từ bên ngoài đấy.
[01:34:07] Database này, file API này.
[01:34:17] giờ theo. Ổn không ạ?
[01:34:20] Ờ
[01:34:22] tôi xin trả lời câu này của bạn kia tí
[01:34:24] đã nhá. Đầu tiên là
[01:34:27] ờ khi mà các bạn hỏi kiểu một cái gì đó
[01:34:30] ổn không đúng không ạ? Thì theo mình các
[01:34:33] bạn nên phải xác định rõ đó là
[01:34:37] à ví dụ giả sử trong trường hợp deop bạn
[01:34:39] đang hỏi nhá là bạn hiểu khái niệm về
[01:34:41] deop chưa? Đã. Đấy bạn phải nghiên cứu
[01:34:44] cực kỳ kỹ về nó đã nhá.
[01:34:47] định nghĩa của nó ấ chứ không phải nó sẽ
[01:34:49] làm gì vân vân một phần đâu. Định nghĩa
[01:34:51] nó bởi vì nhá định nghĩa của dep của
[01:34:54] mình mình biết nhá
[01:34:57] mình biết ở nhiều công ty nó khác nhau
[01:34:59] cơ sự ngay công ty mình đã thấy khác
[01:35:01] rồi. Ví dụ một cái điển hình công ty
[01:35:04] mình ốp ở bên công ty mình thực ra lại
[01:35:07] đang làm việc là quản lý mỗi hệ thống và
[01:35:12] sếp mình còn bảo là đấy là công việc
[01:35:13] giống như là chức vụ của system admin
[01:35:16] chứ không phải một desop tức là chỉ quản
[01:35:18] lý hệ thống thôi. Đấy còn depop như xếp
[01:35:22] mình định nghĩa thì nó là nó lại liên
[01:35:25] quan đến lịch sử của bên DEP một tí. À
[01:35:28] cái này là mình nghe sếp nói và mình
[01:35:30] nghe cũng hợp lý nhá. Mình chia sẻ các
[01:35:32] bạn thôi chứ định nghĩa mỗi bên khác
[01:35:34] nhau mình cũng tra rồi nên là mình không
[01:35:36] hề nói là cái nào chuẩn nhá. Thì là hồi
[01:35:40] đầu là anh em sẽ rõ ràng là một ông làm
[01:35:42] back end, một ông làm fun end đúng không
[01:35:44] ạ? Xong rồi khi mà ngồi dép ghép vào với
[01:35:46] nhau để chạy một cái phần mềm thì tự
[01:35:48] nhiên nó bị lỗi đủ thứ đúng không ạ? Và
[01:35:51] còn phải đợi nhau nữa nên là sẽ sinh ra
[01:35:53] khái niệm full stack. Tức là một ông làm
[01:35:55] từ đầu đến cuối cả giao diện và cả phần
[01:35:58] xử lý. Đấy để không ông nào chờ ông nào
[01:36:01] đúng chưa ạ? Ok rồi xong rồi về sau
[01:36:05] khi phát triển phần mềm đôi khi mình cần
[01:36:07] tích hợp sang bên thứ ba nữa. Ví dụ giả
[01:36:09] sử bây giờ mình tích hợp sang cổng thanh
[01:36:10] toán, mình tích hợp sang cái bên ví dụ
[01:36:12] là hồi trước mình làm trang tìm kiếm thì
[01:36:15] mình tích hợp lên cả những cái pack
[01:36:19] những cái thư viện về tìm kiếm đấy các
[01:36:21] thứ thứ. Thì thay vì mình phải gọi sang
[01:36:23] một à mình phải gọi một cái ông để ông
[01:36:26] đấy ngồi cài cho mình cái phần mềm hay
[01:36:27] là cài mình cái bên thứ ba đấy tự mình
[01:36:30] cài luôn giống ông vuông sách là chẳng
[01:36:31] cần phải đợi ai xếp giao việc cho mình.
[01:36:34] Mình cứ thế mà cứ làm mọi thứ để mà nó
[01:36:37] chạy được. Đấy thì cái từ dep off nó ra
[01:36:40] đời. Tức là dep off là bản thất là nó là
[01:36:42] full stack kết hợp với
[01:36:45] có de nghĩa là de mà đúng không? Kết hợp
[01:36:49] với ở đây. Off này tôi không nhớ từ viết
[01:36:52] tắt nó là gì nhưng đại khái nó liên quan
[01:36:54] đến về hệ thống ấy. Tức là chị ạ. Ông có
[01:36:57] thể tự kiểu cài đặt môi trường, tự làm
[01:37:00] mọi thứ để sao cho
[01:37:03] kiểu chạy được một cái tính năng để làm
[01:37:06] thử từ đầu đến cuối em không cần phải
[01:37:08] nhờ bất kỳ ai cả. Ông tự làm được. Ví dụ
[01:37:10] là thế nên là một cái khái niệm à
[01:37:14] dep bây giờ cần phải học chính chỉ về
[01:37:16] Amazon hay gì gì đó bởi vì kết nối sang
[01:37:18] B3 thường là liên quan cloud liên quan
[01:37:21] đến hạ tầng liên quan Amazon gì gì đấy
[01:37:24] đây để mà có thể tích hợp sang bên đấy
[01:37:26] thôi thì như mình vừa phân tích thì rõ
[01:37:29] ràng là theo dep ổn không thì chắc chắn
[01:37:33] là dep là cái kiểu ưu tiên của các công
[01:37:36] ty bây giờ vì rõ ràng là thay vì tôi
[01:37:38] tuyển một ông làm backend một ông mà fen
[01:37:40] thậm chí một ông làm về hệ thống tuyển
[01:37:44] một ông biết cả ba thì nó vẫn tốt để
[01:37:47] giao việc cho nó là đủ đúng không? Đấy
[01:37:50] nhưng mà
[01:37:52] chính vì như thế thành ra công ty nó
[01:37:54] cũng hơi a
[01:37:56] bóc lột và nó hơi kiểu ờ yêu cầu hơi quá
[01:38:00] cao. Và nếu mà bạn mới thì rõ ràng là
[01:38:02] bạn phải học phải ba cái như mình vừa
[01:38:05] nói đúng không ạ? phải học backend, fun
[01:38:08] và một tí về bên các nền tảng thứ ba để
[01:38:11] mà bạn biết tích hợp vào.
[01:38:15] Đấy thì bây giờ chuẩn là bạn nếu mà như
[01:38:18] luồng bạn mình vừa nói
[01:38:21] thì bạn phải học
[01:38:24] back end trước xong rồi fun gì gì đó
[01:38:26] trước các thứ đúng không ạ?
[01:38:29] Đấy.
[01:38:36] xong hai ông có có mâu thuẫn xung đột
[01:38:39] với nhau. Thành ra là cuối cùng ghép vào
[01:38:41] nó không chạy.
[01:38:49] đúng không ạ? Đấy, thế nào mình không
[01:38:51] làm bên, mình cũng không hướng đến bên
[01:38:55] từ trước đến nay nên là mình cũng không
[01:38:56] kiểu trên sâu tìm hiểu gì đấy. Mình chỉ
[01:38:58] biết về khái niệm lý thuyết, kiểu lịch
[01:39:01] sử hình thành với kiểu tại sao có từ đấy
[01:39:04] thôi. Còn yêu cầu nó bây giờ là gì hay
[01:39:07] là bây giờ nó đã thay đổi như nào rồi
[01:39:09] thì mình chịu.
[01:39:11] Mình lại thường mình tính của mình
[01:39:14] thường hay kiểu như thế là mình muốn đi
[01:39:17] về cái cốt lõi. Ấ, hiểu không? Mấy ông
[01:39:20] đôi khi phải đơn giản hóa. Cái này tôi
[01:39:23] học giữ cũng từ xếp luôn là phải đơn
[01:39:25] giản hóa mọi cái
[01:39:28] đi lại về cái nguồn gốc cốt lõi để ông
[01:39:30] hiểu được là cái bản chất của nó lúc đầu
[01:39:32] là gì. Và thậm chí là bây giờ ông khi mà
[01:39:36] ông nhìn lại ông sẽ thấy nó biến tướng
[01:39:37] như nào chẳng hạn. Nghĩa là nó sẽ khác
[01:39:39] như nào bởi vì đôi khi là công việc nó
[01:39:41] sẽ chỉ cần giải quyết bài toán đơn giản
[01:39:43] kiểu kia thôi. Nhưng mà tại do kiểu tam
[01:39:46] sao đất bản hay vân vân gì đó nên thành
[01:39:48] ra nó bị hỗn độn như bây giờ. Nó làm khó
[01:39:50] hiểu như bây giờ. Đấy thì ông quay lại
[01:39:52] cái kiểu cái gốc dễ của nó ấy thì ông
[01:39:56] giải quyết được nó là đôi khi là toàn bộ
[01:39:58] những cái kia lại mượn. Ông ông hiểu ý
[01:40:00] không? Đây
[01:40:11] đây. Ông kia vừa khuyên một cái thêm một
[01:40:13] cái hay nữa kìa. Tôi không học bên đấy
[01:40:15] nên là tôi không rõ đâu.
[01:40:18] So với PP so sánh value trực tiếp. Đúng
[01:40:21] rồi. String
[01:40:24] đúng rồi. String của Java script còn
[01:40:27] muôn trùng nữa. Nếu chỉ hai dấu bằng rất
[01:40:30] rất có lỗi.
[01:40:32] Th PP cũng có mà PP có khái niệm là tôi
[01:40:35] hồi trước tôi vẫn nhớ quả là truyền lên
[01:40:37] là nun xong rồi PP
[01:40:40] PP lại kiểu cố convert nó lại thành
[01:40:42] string thành string nun. Rồi string nun
[01:40:45] nên thành ra là không biết string nun
[01:40:47] rồi nó lại kiểu nó là một cái giá trị
[01:40:51] đúng không? Nó không còn là hiểu không
[01:40:53] có giá trị nữa đúng không? Đấy
[01:40:56] buồn cười lắm
[01:41:06] dạng là get ý thì ông truyền lên n thì
[01:41:10] đương nhiên nó chẳng convert lại thành
[01:41:11] string đúng không?
[01:41:13] chuẩn là nun thì không nên truyền lên.
[01:41:15] Đấy theo tôi như thế hoặc như là nếu mà
[01:41:18] thấy thì ông phải biến thành dạng method
[01:41:21] không phải method get đúng không?
[01:41:31] làm trên Hà Nội một thời gian rồi về
[01:41:33] quê.
[01:41:35] Đấy tôi đang dịch cái câu của bạn hỏi là
[01:41:37] như thế đúng không ạ? Nhưng mà tester so
[01:41:40] với DEP là như nào nhỉ? là ý bạn là về
[01:41:45] mọi thứ đúng không? Kiểu nếu mà hỏi câu
[01:41:47] rộng thấy là mọi thứ đúng không? Là kiểu
[01:41:49] đái ngộ này hay là cả về mức độ khó hay
[01:41:52] vân vân đúng không? Câu trả lời đều là
[01:41:55] dead. Vẫn có thiên hướng là mọi thứ đều
[01:41:57] hơn tester về kiểu khó hay là đãi ngộ
[01:42:00] mọi thứ hơn thì đương nhiên là khó hơn
[01:42:02] đương nhiên đãi ngộ tốt hơn đúng không
[01:42:04] ạ?
[01:42:06] Nhưng mà ờ nhưng mà bạn Hoa Sinh nè thì
[01:42:12] chắc là nữ à thường à mọi người vẫn
[01:42:14] khuyên là bạn nữ thì một là tetơ hai là
[01:42:16] ba hoặc là thậm chí DA nhưng mà theo
[01:42:20] mình thì
[01:42:22] bạn cứ phải thử đã đúng không? Mình
[01:42:25] không khuyên các bạn là theo được một
[01:42:27] cái gì đó luôn. Các bạn thử đã xong rồi
[01:42:29] các bạn sẽ kiểu thử ở đây là phải học
[01:42:32] giống như kiểu mình ấy là 100 ngày là 3
[01:42:36] tháng các bạn phải học tầm như thế không
[01:42:40] nên thì mới một là 100 ngày này, hai là
[01:42:43] 3 tháng này, thậm chí là 1000 giờ này
[01:42:46] các bạn mới biết được thực sự các bạn
[01:42:48] hợp cái gì. Nếu mà bạn các bạn mà dễ
[01:42:52] nản, dễ bỏ cuộc trước thời gian đấy thì
[01:42:54] theo mình là mọi nghề mọi nghề đều sẽ
[01:42:57] khó theo. Đặc biệt là ngành IT này thì
[01:43:01] càng khó.
[01:43:03] 100 ngày thực ra nó nhanh lắm đấy. Hôm
[01:43:05] nay ngày một nhá ông mấy ông sẽ thấy là
[01:43:07] 100 ngày vèo vo
[01:43:13] thì mình mới kiểu gọi như là kiếm được
[01:43:17] việc mà mình kiếm được việc mà người
[01:43:18] khác gọi là bây giờ đang tranh đua nhau
[01:43:21] việc mà đúng không ạ?
[01:43:30] phải biết code thực ra tùy test ở tùy từ
[01:43:33] công ty ví dụ công ty tôi thực ra công
[01:43:35] ty tôi ra không tester không cần biết
[01:43:37] code lắm đấy tester chỉ cần bị đúng
[01:43:40] nghĩa là test giao diện với dùng pman
[01:43:43] hay mọi thứ nhưng mà vẫn phải nên có một
[01:43:46] cái gì đó lộ trình mà đúng không ạ từng
[01:43:49] cuối có thể là bạn không giỏi ở mặt code
[01:43:52] nhưng mà bạn Biết
[01:43:54] lộ trình kiểu biết ưu và nhược ấy, biết
[01:43:57] được mình còn thiếu cái gì chẳng hạn ấy
[01:43:59] đúng không? Ví dụ hôm nay tôi hỏi bạn
[01:44:01] sinh viên của tôi chẳng hạn, sinh viên
[01:44:03] bạn ấy học ở trên trường bị dàn trải
[01:44:06] quá, bạn không hề biết ưu vào nhược của
[01:44:09] bản thân để nói. Bạn ấy đang nghĩ là bạn
[01:44:12] đang làm tốt thôi. Tôi cũng không biết
[01:44:14] thực sự bạn đang làm tốt cái gì đấy.
[01:44:16] Chẳng hạn thế không biết bạn ấy đang
[01:44:18] nghe không? Bạn đang nghe chắc tế tôi
[01:44:19] chết mất. Nhưng mà ý tôi như thế nghĩa
[01:44:23] ông phải thực sự ông phải học từ đầu đến
[01:44:24] cuối một cái gì đó gốc gáp, một cái
[01:44:26] chuẩn chỉ để ông thực sự ông biết được
[01:44:29] là ông đang thiếu cái gì. Ví dụ giả sử
[01:44:31] tôi học PP
[01:44:33] nhưng tôi biết được là tôi thiếu bên
[01:44:35] mảng về chặt chẽ của bên Java để tôi
[01:44:37] sang học này như này chẳng hạn. Đấy khi
[01:44:39] mà mình biết được mình có ưu nhược là
[01:44:42] gì, mình đang thiếu cái gì đó như này
[01:44:44] thì mình mới dễ học. Còn nếu mà ông còn
[01:44:47] học theo kiểu học vẹt hay học kiểu ngắt
[01:44:50] quãng hay học tua hay vân vân vân gì đó
[01:44:51] không chuẩn chỉ
[01:44:53] ông sẽ không hề biết được ông đang thiếu
[01:44:54] cái gì và ông đi phỏng vấn
[01:44:57] một là người ta hỏi đến hai đi làm kiểu
[01:44:59] gì cũng gặp thì sẽ chết không biết gì cả
[01:45:03] đúng không ạ
[01:45:09] test
[01:45:15] đã từng học qua code nhưng bạn ấy cảm
[01:45:17] thấy là không theo được code thì bạn vẫn
[01:45:20] có thể là kiểu học qua SQL mình có dạy
[01:45:23] SQL cơ bản để bạn có thể tham khảo hoặc
[01:45:26] là tùy trên mạng có nhiều mà đấy qu bởi
[01:45:29] vì nếu mà tester mà chỉ thuần về làm
[01:45:32] test giao diện mà không không dùng AI để
[01:45:35] mà có thể dùng AI sinh ra code nhá giả
[01:45:38] sử như bạn không động tí về AI này không
[01:45:40] động tí về code này mà không dùng hay là
[01:45:44] không dùng SQL
[01:45:46] thì
[01:45:48] tự nhiên hạn chế bản thân thôi đúng
[01:45:50] không ạ? Đấy bạn nên kiểu không về code
[01:45:53] nhưng mà phải về cái khác một tí các thứ
[01:45:55] các thứ đúng không ạ? Thì nó sẽ ổn hơn.
[01:46:04] Bây giờ ông ngày nào cũng vào bình luận
[01:46:06] về
[01:46:08] kiểu như là không thể nói về khoe về bản
[01:46:11] thân được nhưng mà
[01:46:15] ừ nhưng là ông phải có một bình luận.
[01:46:18] Ngày nào ông bình luận có một điểm nhấn
[01:46:19] ở đó thì sẽ dễ.
[01:46:31] thích cũng được. Quan trọng là đấy giống
[01:46:32] như là tôi bây giờ tôi đang không hiểu
[01:46:34] thì tôi nhờ ai học cùng cũng hầm một
[01:46:35] cách mà. Thầy đang dậu dậy ở đâu thế?
[01:46:39] Tôi đang ngồi nhà không ạ?
[01:46:42] Học một mình cũng nả là anh có anh live
[01:46:45] học cho có động lực. Cảm ơn. Tôi cũng
[01:46:47] thế. Đấy do tôi live đây hợp một mình có
[01:46:50] vẻ hơi buồn không có kiểu thúc đẩy cùng
[01:46:54] mấy ông hãy coi cái này giống như b cá
[01:46:55] để mấy ông ngồi nghe để du ngủ hoặc là
[01:46:58] ngồi làm việc cũng được.
[01:47:00] Bạn sinh ơi nếu học test thì nên học
[01:47:04] thêm cả tiếng Nhật nhữ nữa sau có thể dễ
[01:47:06] sang tester cộng học hành với khách là
[01:47:08] hợp lý. Ô ông kia khuyên cũng hay bởi vì
[01:47:12] đấy khuyên thấy khá là kiểu thực tiễn
[01:47:14] bởi vì bây giờ đúng rồi
[01:47:17] bên a
[01:47:20] bên Nhật bây giờ cũng đang tuyển bên
[01:47:21] mình này. Tiếng tiếng Nhật bây giờ đúng
[01:47:24] là tuyển nó sẽ tôi cảm thấy nó sẽ dễ hơn
[01:47:26] tiếng Anh bây giờ. Tiếng Anh đấy là theo
[01:47:29] tôi
[01:47:31] xung quanh
[01:47:40] ở trên công ty tôi bây giờ vẫn đang ngon
[01:47:41] lành nhưng mà tôi gần đây tôi mua hẳn
[01:47:44] cái cũng là
[01:47:47] mới gần nhất ông ạ. Đấy, kiểu cũng đúng
[01:47:51] kiểu đợt
[01:47:53] kiểu đợt đấy là đợt đ được thưởng hay gì
[01:47:57] đó. Tôi nhớ là tôi cũng đầu tư hẳn một
[01:47:59] cái
[01:48:06] nó khác nhau có khác nhưng mà nó không
[01:48:10] gọi như là bây giờ giả sử bây giờ nó
[01:48:13] đang nhanh rồi nên thành ra là kiểu khi
[01:48:15] mà nó nâng lên thì nó vẫn chỉ là nhanh
[01:48:17] thôi. Đấy
[01:48:20] code luôn P project đi anh. Có chứ có
[01:48:22] chứ. Tôi sẽ học xong Java tôi sẽ code
[01:48:25] pet project mấy ông có thể ngồi xem tham
[01:48:28] khảo cùng. Hồi trước
[01:48:30] ủ mấy cái làm pet project đang nửa chừng
[01:48:32] rồi. Nhiều lắm.
[01:48:36] Tiếp tục học đi anh. Không cái này thôi.
[01:48:39] Đấy mấy ông cũng ham học chúng tôi rồi
[01:48:41] đúng không? Ừ một buổi sẽ chỉ học tầm
[01:48:44] này thôi.
[01:48:46] Cái này hãy nên nhớ là mình học toàn bộ
[01:48:48] cái đống này trong 5 ngày đầu. Bây giờ
[01:48:51] tôi đã học được buổi thứ hai rồi đúng
[01:48:54] không ạ? Tí để đánh số vào.
[01:49:02] anh. Ồi ý tưởng đúng là từ trước hay tôi
[01:49:04] nhiều kiểu nhiều kinh khủng. Hồi trước
[01:49:06] là toàn có phải nhờ ông emy kia ngồi cốt
[01:49:09] cùng hoặc ngồi làm giao diện cho nhưng
[01:49:12] mà tôi giờ đã có ai ch nhưng mà bây giờ
[01:49:15] vấn đề đấy là mình gọi như là mình không
[01:49:18] có thời gian thật nhiều lúc và cầu.
[01:49:21] Bây giờ cũng có tình yêu tình báo cũng a
[01:49:25] à đấy ngồi học hay là thậm chí là gần
[01:49:29] đây còn sẽ phải ngồi quan tâm sức khỏe
[01:49:31] vân vân nữa. Đấy nhiều do lắm vẽ ra
[01:49:34] nhiều lý do lắm. Có khi là chỉ mệt quá
[01:49:36] muốn nằm thôi. Nhưng mà rõ ràng tôi có
[01:49:38] nhiều ý tưởng thật.
[01:49:41] Nhưng mà bây giờ tôi để lộ ý tưởng cho
[01:49:43] mấy ông thì
[01:49:46] tôi sẽ không lộ ý tưởng tôi sẽ nói mấy
[01:49:48] ông đó là nó theo nhu cầu mấy ông thôi.
[01:49:52] Vì rõ ràng là nhu cầu của tôi rất nhiều.
[01:49:56] Chắc là tôi dùng nhiều phần mềm nữa chứ
[01:49:58] tôi cảm thấy có cái phần mềm gì cân cấn.
[01:50:00] Ấy ví dụ rõ ràng là có một cái phần mềm
[01:50:01] trên mạng tôi dùng rồi cảm thấy không
[01:50:04] hài lòng với nó. Tôi thích code hẳn một
[01:50:05] cái nữa. Code để có thêm một cái tính
[01:50:07] năng A, một tính năng B nữa. Chẳng hạn
[01:50:09] thế được
[01:50:15] tí AI không anh? P project tôi định làm
[01:50:18] thực ra nó cũng chẳng cần liên quan đến
[01:50:19] AI cả vì rõ ràng gọi đến AI nữa đôi khi
[01:50:22] tốn phí thì tôi cảm thấy là tôi không ý
[01:50:25] định tôi không gọi là nói chung là tôi
[01:50:28] bỏ qua cái thời kỳ mà kiểu tham về công
[01:50:31] nghệ rồi hồi trước thì kiểu ngượn non
[01:50:33] hào đá thì kiểu sẽ tham mà kiểu giờ mình
[01:50:36] phải làm ra một cái phần mềm rất là xịn
[01:50:38] có rất nhiều tính năng vip đấy xong rồi
[01:50:41] công nghệ mới nhất hay vân vân vân gìấy
[01:50:43] công việc không thử ra mình làm độ lâu
[01:50:45] đặc biệt công Công ty tôi là product mà
[01:50:48] đây công ty tôi nói thẳng bây giờ còn
[01:50:50] đang nhiều lúc đang không có khách thì
[01:50:53] không quan tâm công nghệ ông đang dùng
[01:50:54] xịn như nào đâu không ạ quan tâm về việc
[01:50:57] kiểu nó đem lại thực sự giá trị người
[01:50:59] dùng người dùng cần hay không không quan
[01:51:01] tâm về công nghệ đâu không quan tâm
[01:51:03] khách đâu quan tâm ông đang dùng công
[01:51:04] nghệ gì hay kiểu xịn như thế nào không
[01:51:07] khách khách có biết đâu khách quan tâm
[01:51:09] đâu đúng không đấy
[01:51:16] những cái dự án cá nhân ý đấy. Những dự
[01:51:18] án cá nhân bé bé thì sẽ gọi là bé phách
[01:51:29] ông mà nửa đêm ông nghe thì ông sẽ không
[01:51:31] thấy chiu lắm đâu.
[01:51:40] thôi.
[01:51:43] To gọi startup à? Cũng được. Nếu mà
[01:51:45] startup tự thân, nếu mà không tốn tiền
[01:51:48] nào thì vẫn có thể là PJ cũng được tùy
[01:51:50] tù cái gọi.
[01:51:54] Ok, hôm nay đã xong. Mấy cái này tôi vẫn
[01:51:57] sẽ đẩy lên để mấy ông tham khảo nhá. Mấy
[01:51:59] ông cứ sẵn sàng mạnh dạn ui cái gì đấy
[01:52:02] giố nhiều này.
[01:52:04] Person cái gì đấy lừa rồi
[01:52:07] đã chạy cái gì đâu. Có person này
[01:52:11] bình tĩnh bình tĩnh đợi tí. Sợ có person
[01:52:14] nào đây này.
[01:52:30] cái linh tinh này đã.
[01:52:44] dùng hẳn thanh kinh đến giờ dùng thẳng
[01:52:47] thẳng thh kinh rồi.
[01:52:50] Sửa lại
[01:52:52] cho tôi
[01:52:54] cái project này.
[01:52:58] Tôi muốn
[01:53:00] mỗi thư mục
[01:53:03] đã diện cho mút buổi,
[01:53:09] m ngày chứ không phải
[01:53:14] lắp lại
[01:53:17] 13 này. 1 năm gì đó.
[01:53:35] nói thế vui mà
[01:53:39] ghi rõ à
[01:53:43] số thứ tự
[01:53:46] ngày trong file này
[01:53:50] cho tôi
[01:54:00] rồi mấy ông ạ nói khăn rọng
[01:54:03] nói liên tục
[01:54:13] Em không dễ ngủ lắm. Em chuẩn bị tốt
[01:54:15] nghiệp ạ. Xin muốn xin anh vài lời
[01:54:18] khuyên.
[01:54:19] Ok. Em cứ hỏi đi. Em a tốt nghiệp chắc
[01:54:24] là khóa công nguyện công tin thôi nhỉ?
[01:54:25] Đúng không? Ừ.
[01:54:34] thì hơi khó khuyên. Chắc anh chỉ khuyên
[01:54:36] được khoản là viết cách cách CV xong rồi
[01:54:40] phỏng vấn hay gì gì đó. Ví dụ cách CV
[01:54:43] thì anh vẫn thường ha khuyên đó là nó
[01:54:47] phỏng vấn hay CV. Nói chung thì nó vẫn
[01:54:50] tôi từng nói từ mấy cái video hồi trước
[01:54:52] rồi. Đó là giống như việc ông đi tn gái
[01:54:54] vậy. Ông không thể dùng một bài cho tất
[01:54:57] cả. Tức là sao? Nghĩa là phải xẽ lên xem
[01:55:02] tìm hiểu qua công ty đấy là nó đang có
[01:55:05] nhu cầu gì đã và mình sẽ sửa CV sao cho
[01:55:08] phù hợp với cái nhu cầu đấy sẽ tránh cái
[01:55:10] việc là ông áp dụng một bài để tất cả
[01:55:13] đúng không ạ? Đấy nó như thế thôi. Kiểu
[01:55:19] ừ ông không thể kiểu đăng một cái status
[01:55:23] ta kiểu ai yêu tôi không saong rồi sẽ có
[01:55:25] rất nhiều người vô gặp mào đúng không ạ?
[01:55:27] Giống như là ông việc ông gửi C C CV
[01:55:29] cũng thế. Ông không thể gửi một cái CV
[01:55:32] rất là chung chung xong gửi cho tất cả
[01:55:34] mọi người được à tất cả công ty được
[01:55:37] đấy. Phải phải sửa lại theo từng công
[01:55:40] ty. Ông có thể dùng AI để mà sửa. Thậm
[01:55:42] chí là dùng AI để góp ý. Hôm trước tôi
[01:55:44] dùng AI để thử ném đá ra CP của tôi
[01:55:46] chẳng hạn. Đấy,
[01:55:49] đúng rồi. Sựa dựa vào JD hiển nhiên luôn
[01:55:51] làm chi là không phải GD là đủ. Ông phải
[01:55:54] thực sự là ông phải lên trang web của
[01:55:55] công ty tìm hiểu. Nếu mà lý tưởng hơn là
[01:55:58] ông phải nhắn tin với cả
[01:56:01] bên kiểu nhân viên bên đấy để mà thực sự
[01:56:03] hỏi xem là công ty có vấn đề gì, có
[01:56:06] những cái đang đang làm dự án gì vân
[01:56:09] vân. Nói chung là tìm hiểu thôi nó n là
[01:56:11] giống như vừa rồi tôi nói con gái kiểu à
[01:56:14] có bạn nữ ở đây nhỉ thôi tám nửa kia đi
[01:56:17] thì mấy ông cũng phải đi tìm hiểu qua
[01:56:19] bạn bè của người ta có thể thế rất nhiều
[01:56:21] cách đúng không tìm hiểu qua bởi vì hãy
[01:56:24] nên nhớ là đây là không tìm việc ở đây
[01:56:27] nó giống tìm yêu ra mình tìm những cái
[01:56:31] phù hợp với mình nhá chứ không phải là
[01:56:33] mình cứ chọn bừa đấy không thể yêu bừa
[01:56:36] chọn bừa được đúng không ạ thì tìm người
[01:56:37] phù hợp tức là sao nghĩa là ông tìm hiểu
[01:56:39] qua xem công ty phù hợp với ông không?
[01:56:41] Ông có đủ điều kiện để làm công ty đấy
[01:56:43] không? Công ty nó quá chán này hay là
[01:56:46] công ty nó quá xa vân vân rất nhiều cái
[01:56:48] đúng không?
[01:56:50] Đương nhiên là ông sẽ nghĩ là ông mới ra
[01:56:52] trường thì ai
[01:56:54] gọi là đâm đầu yêu không thế nào cũng
[01:56:56] được bất chấp để lấy kinh nghiệm cũng
[01:56:58] được cũng là một cách nhưng mà có rất
[01:57:01] nhiều người làm như thế nên là thành ra
[01:57:03] là
[01:57:04] nó lại phù hợp những công ty nó hơi tảm
[01:57:06] nham một tí đấy còn công ty mà nó khá
[01:57:09] chuẩn chuyên nghiệp giống như là con
[01:57:12] người ta cũng là con người tử tế đúng
[01:57:14] không
[01:57:17] cách của anh virus
[01:57:19] Không biết đang hiểu nó cái gì nhưng mà
[01:57:22] đấy con người ta là con nhà tử tế thì
[01:57:25] mình sẽ phải rất là chuẩn chi để phù hợp
[01:57:28] đấy đúng không? Đấ mình phải chuẩn bị
[01:57:31] trước đấy nhiều mà.
[01:57:35] Nói chung là thực ra tôi bây giờ tôi bởi
[01:57:39] vì tôi cũng đang chưa hẳn là
[01:57:43] hôm trước mới là lần thứ hai trong đời
[01:57:45] tôi đi phỏng vấn.
[01:57:47] À những lần trước có phỏng vấn nhá toàn
[01:57:49] là người quen giới thiệu nên gần như nó
[01:57:50] sẽ khác.
[01:57:53] Không biết rồi tôi lần trước tôi đã kể
[01:57:57] tâm sự mấy ông về phỏng vấn lần đầu của
[01:57:59] tôi chưa? Nhưng là lần đầu phỏng vấn của
[01:58:01] tôi thì tôi cũng ngồi chém ba hoa, không
[01:58:05] phải chém gió ba hoa nữa. Nhưng mà đại
[01:58:07] khái là tôi cũng dẫn dắt câu chuyện đấy.
[01:58:10] Tôi cảm thấy tôi vẫn tự tin là tôi đã
[01:58:12] làm chủ được cái cuộc phóng vấn đấy. Đó
[01:58:14] là thay vì người ta hỏi mình kiểu cứ
[01:58:18] người ta hỏi rồi mình trả lời ấ thì mình
[01:58:20] sẽ mình chủ động cho câu chuyện luôn là
[01:58:23] mình ngồi nói những cái ưu của mình
[01:58:24] luôn. Giống như kiểu đi hẹn hò là mình
[01:58:26] sẽ tránh cái việc là
[01:58:29] buổi phỏng vấn là kiểu cứ để hỏi và trả
[01:58:32] lời đúng không? Mình dẫn dắt mình kể một
[01:58:34] câu chuyện đúng không? Mình kể câu
[01:58:36] chuyện của mình, một cái kinh nghiệm của
[01:58:37] mình để cho người ta biết được là à cái
[01:58:40] góc nhìn của mình là như nào, khi mình
[01:58:43] gặp vấn đề mình sẽ xử lý như nào đấy
[01:58:45] đúng không? Đấy, họ sẽ biết qua về con
[01:58:48] người và cách nói chuyện mình nữa. Nó sẽ
[01:58:50] kiểu mở hơn ấy, thay vì chỉ dừng lại
[01:58:53] trong mỗi mấy cái câu hỏi có sẵn đúng
[01:58:54] không? Đấy và à buổi gần nhất đấy nhưng
[01:59:00] mà buổi hôm đấy là tôi đi phỏng vấn kia
[01:59:02] không có quay tại thì cái quay kia quay
[01:59:05] gần nhất tôi đăng thì nó sẽ là
[01:59:08] làm online ở nhà này. Hình như hôm nãy
[01:59:10] mặc bộ này phả không biết rồi đấy thì
[01:59:14] mấy ông có thể xem cái buổi phỏng vấn
[01:59:16] gần nhất tôi đăng thì ông sẽ thấy cách
[01:59:20] tôi tự tin vào cái video đấy trừ cái
[01:59:22] điểm mà tôi phát âm có thể tiếng Anh nó
[01:59:24] không hay thôi.
[01:59:26] Đấy
[01:59:32] mà hôm nay tôi có nghĩ rồi đấy. Đó là
[01:59:35] update cái bộ cái vụ tuyển dụng trong PP
[01:59:37] trong Discord.
[01:59:40] Thực ra có một sự thật đó là tôi định để
[01:59:42] trong đấy là rất nhiều ngôn ngữ không
[01:59:44] phải mỗi PP nhưng mà thằng tag của thằng
[01:59:47] Discord nó giới hạn đúng không ạ? Nên
[01:59:49] thành ra tôi mới phải kiểu thôi thì để
[01:59:51] mỗi PP trong đấy chứ thật ra tôi định để
[01:59:54] nhiều ngôn ngữ khác nữa được rồi. Bao
[01:59:56] nhiêu để vào đây cũng được mà nhưng mà
[01:59:58] không nó hình như nó giới hạn 15 hay 20
[02:00:00] v thôi nên tôi mới phải thôi thì đà nào
[02:00:04] mình dạy mỗi PP với ra Ja script hay gì
[02:00:07] gì đó nên là mình để cái phần tuyển dụng
[02:00:10] nó chỉ có mấy ngôn ngữ như thế
[02:00:13] ơ có để Hồ Chí Minh mà nhỉ
[02:00:16] lửa. Đợi tí tôi mở Discord ở trên đây
[02:00:20] xem đã không có Hồ Chí Minh ấy nhỉ?
[02:00:24] À ý mà có mấy cái chop á. Mấy cái chó
[02:00:27] thì
[02:00:30] tôi không thấy bên nào liên lạc với tôi
[02:00:31] cả nên thành nó thế. Nghĩa là khi mà có
[02:00:34] bên nào liên lạc với tôi thì tôi mới
[02:00:37] đẩy lên đấy thôi. B cũng lâu lắm rồi.
[02:00:40] Xem có Hồ Chí Minh mà có tác Hồ Chí Minh
[02:00:42] chẳng qua là không có chó. Hồ Chí Minh
[02:00:44] là không lên thôi.
[02:00:46] Không không ưu tiên gì đâu. Có chob nào
[02:00:48] thì đẩy lên đấy. Tại người quen tôi chắc
[02:00:50] là không phải người quen. Tôi quen khá
[02:00:53] nhiều kiểu
[02:00:56] ừ gần như là vào nhiều nơi. Nhưng mà ý
[02:00:58] tôi là người biết tôi dậy hay là các thứ
[02:01:00] vân vân thì nó chủ yếu thì
[02:01:04] trong tầm mà quan hệ mà kiểu hay gặp nên
[02:01:07] thành ra là kiểu người ta sẽ gửi tôi vì
[02:01:10] job ở Hà Nội nhiều nhất.
[02:01:15] dạy on và tôi có sinh viên tôi ở các
[02:01:19] tỉnh khác đâu đúng không? Không ai biết
[02:01:21] điều đấy cả.
[02:01:28] hẳn một cái row là row HR ở trong cái
[02:01:31] server Discord đấy rồi. Mấy ông phải là
[02:01:32] người kêu gọi HR vào trong đấy để ph
[02:01:35] đăng tin tuyển dụng. Đấy kiểu như thế.
[02:01:39] Tôi hồi đấy là tôi đã mời hai ba bạn HR
[02:01:42] vào rồi đấy.
[02:01:51] chưa dừng 8 ba.
[02:01:57] tôi quen toàn nam nhưng mà tôi nhớ là
[02:01:59] hình như có có nữ nhưng mà tôi cũng chưa
[02:02:02] từng đ ba. Gần đây nhá. Tôi quen
[02:02:06] đúng có đúng một bạn gần gần đây kiểu
[02:02:11] như nào nhỉ.
[02:02:14] Bây giờ khoe ra trên này cho anh em ném
[02:02:16] đá.
[02:02:18] Nhưng đại khái anh em mà theo dõi tôi
[02:02:19] biết được là tôi đang có người yêu thì ừ
[02:02:22] bạn hiện tại của tôi là là
[02:02:26] cũng là de nghĩa là dân trong ngành đúng
[02:02:28] không ạ? Nhưng mà ý tôi là từ trước nay
[02:02:30] bạn đấy là người đầu tiên.
[02:02:33] ở trong ngành chứ bình thường từ trước
[02:02:35] nay tôi không quen con gái ở trong
[02:02:38] ngành.
[02:02:40] Quen thì đương nhiên là kiểu sinh viên
[02:02:42] hay bạn bè thì có nhưng mà thể chưa tả
[02:02:44] gà con gái trong ảnh.
[02:02:48] Clip phỏng vấn đang ở đâu thế nhỉ? Ơ
[02:02:50] trên kênh này này nhưng mà ở trong cái
[02:02:52] video ấy chứ không phải là trong
[02:02:55] thường mọi người sẽ có thể bấm vào
[02:02:57] playlist hoặc là bấm vào cái gì à phát
[02:03:01] trực tiếp gì đó. Còn đây là video ấy.
[02:03:10] fake
[02:03:12] kinh nghiệm không? Đấy, giống như bạn
[02:03:14] kia chia sẻ là bảy phần thực, ba phần
[02:03:16] nào thì anh nghĩ là
[02:03:20] thựt là chẳng cần phải fake đâu. Rõ ràng
[02:03:22] giống như nãy giờ mình đang đề cập là
[02:03:24] tạo ra một cái một cái dự án cá nhân.
[02:03:27] Em có thể ghi trong đấy, đúng là là em
[02:03:30] ghi trong đấy những cái ngôn từ ngầu có
[02:03:32] thể dùng AI để tạo ra nhưng nó vẫn là dự
[02:03:34] án thực tế em đã làm thì vẫn được chẳng
[02:03:38] có không cần. Nghĩa là toàn bộ những cái
[02:03:41] trên vi đối với anh nhá. Toàn bộ những
[02:03:43] cái trên CP mình đều viết là nó có thực
[02:03:47] tế. Chẳng qua nó bị phòng đại theo kiểu
[02:03:50] là theo kiểu là em làm em làm em làm năm
[02:03:55] đi nhưng em khoe là 10 cũng được còn hơn
[02:03:59] là em không làm rồi em khoe em có làm nó
[02:04:01] khác hoàn toàn. Em hiểu ý ý anh không?
[02:04:04] Nghĩa là em có thể dùng phóng đại không
[02:04:06] sao cả. CV được phép phóng đại nhưng CV
[02:04:09] không được phép nói láo xuyên tạc, nói
[02:04:12] sai sự thật.
[02:04:14] Đấy, trong trường hợp đối với anh sai
[02:04:16] trường hợp là không làm đấy. Còn việc mà
[02:04:19] em làm nhưng mà đấy đối với em đấy thành
[02:04:22] công em khi vĩ đại rồi cũng được chơi
[02:04:26] kiểu cùn kiểu thế kiểu em khoe ông si
[02:04:28] phi em sản phẩm dự án này em rất là
[02:04:31] thành công rất xịn chẳng qua đối với mọi
[02:04:34] người thì sản phẩm đấy kiểu đểu. Nhưng
[02:04:36] mà em mới ra trường em cảm thấy thế là
[02:04:40] xịn rồi có sao đâu đúng không? người ta
[02:04:43] không ai đánh giá ai cũng biết thừa việc
[02:04:46] em phải ra trường thì kinh nghiệm em đến
[02:04:47] đâu nên là không sao việc là trong CV em
[02:04:51] bảo là nó rất là xịn đấy nhưng mà trong
[02:04:54] CV của em tự nhiên em được kê là em đã
[02:04:56] dùng giống như là trên sá tanh của nó áp
[02:04:59] dụng blockchain áp dụng AI áp dụng kiểu
[02:05:01] n thứ rồi đã làm tỷ tính năng trong đấy
[02:05:05] kiểu thứ ra không phải thì lúc đấy là
[02:05:09] đấy là bffet chem to quá đúng không hỏi
[02:05:11] hai câu cái là tắt rồi thì không nên.
[02:05:21] Lúc phỏng vấn nên thể hiện thái độ như
[02:05:23] nào? Anh họ hỏi mình một mình nên trả
[02:05:25] lời 230 hay trả lời theo chính họ hỏi
[02:05:27] thôi. Thực ra nó là liên quan đến giống
[02:05:31] như vừa nãy mình đề cập là mình nói
[02:05:33] nhiều và mình chỉ cảm thấy mình dỡ dắt
[02:05:35] được câu chuyện thì mình sẽ kể một câu
[02:05:37] chuyện ra. Bởi vì một phần là câu chuyện
[02:05:39] này không nên lặc đề nhá. Câu chuyện này
[02:05:41] nó vẫn nên đúng đề và nó dựa theo kinh
[02:05:43] nghiệm của mình. Còn nếu mà bạn đang
[02:05:45] chưa có kinh nghiệm gì lắm thì bạn có
[02:05:48] thể trả lời thành hai thì thôi là hợp
[02:05:50] lý. Đừng có nên trả lời dài quá. Và và
[02:05:54] hãy nên xem thời gian của họ với mình
[02:05:57] hay xem biểu cảm của họ nữa. Cái này
[02:06:00] liên quan kỹ năng mềm mà anh em IT được
[02:06:02] là kém kỹ năng mềm n hơi khó để mà
[02:06:04] khuyên.
[02:06:05] không đánh đồng đâu nhưng mà mấy ông
[02:06:08] hiểu mà đấy thì
[02:06:10] tôi thế nghĩa là nếu giả sử mà họ tự
[02:06:13] nhiên cảm thấy có gì đó là kiểu khc lại
[02:06:16] kiểu họ thấy là không hài lòng mình
[02:06:18] không thích mình lắm nữa thì mình biết
[02:06:20] được phần nào là buổi phỏng vấn đây
[02:06:23] không còn thành công nữa thì mình sẽ
[02:06:26] trả lời. vẫn trả lời, vẫn mọi thứ vẫn
[02:06:28] chuyên nghiệp nhá để vẫn giữ hình ảnh
[02:06:29] cho chính mình đấy. Nhưng không nên quá
[02:06:33] là dòng đấy. Thế thôi.
[02:06:37] Đây có cái linkit hub kia kìa. Chính cái
[02:06:39] gai này đấy. Ơ xong rồi này. Nó sửa xong
[02:06:41] rồi này. Để tô xem nhá. Ok
[02:06:44] đây một đây 2, đây 3. Ừ trong có vẻ rõ
[02:06:47] ràng hơn rồi. Dù tôi không thích cái từ
[02:06:48] đây này lắm thì thôi cũng được. Ok ok
[02:06:50] ok. Tạm thời đã. Tôi tôi bây giờ tôi
[02:06:55] chuẩn bị nghỉ rồi nên là tôi không có
[02:06:58] thể review được cái đoạn này.
[02:07:00] Nhưng mấy ông có thể
[02:07:04] đẩy cái này lên để à mấy ông có thể
[02:07:06] review hộ tôi nhá. Tôi sẽ sửa cái này là
[02:07:10] ờ update
[02:07:13] đây 1 năm kiểu như này đấy. Có gì mấy
[02:07:18] ông xem lại rồi đây link hub đây. Không
[02:07:22] biết mấy ông nào for hay đánh sao gì
[02:07:23] chưa chưa ông nào cả. [tiếng cười]
[02:07:26] Đây anh sẽ đánh sao. Ok rồi.
[02:07:32] Ok. Xin chào mấy ông nhá. Còn thắc mắc.
[02:07:37] Hả? Không ai gõ đâu. À có tiếng nước
[02:07:40] chảy thôi. Không không không ai gõ đâu.
[02:07:42] À
[02:07:44] xin chào mấy ông. Hẹn mấy ông ngày mai.
