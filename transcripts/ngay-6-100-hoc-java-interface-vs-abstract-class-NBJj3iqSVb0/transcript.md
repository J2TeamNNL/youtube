# Ngày 6/100 học Java - Interface vs Abstract Class

- Video ID: `NBJj3iqSVb0`
- URL: https://www.youtube.com/watch?v=NBJj3iqSVb0
- Published: 2026-01-25
- Duration: 1h 26m 54s (5214s)
- Language: vi
- Subtitle source: auto
- Kind: live

## Transcript

[00:00:39] Ờ
[00:00:40] dù hiện tại thì như mình bảo là thỉnh
[00:00:43] thoảng mình sẽ
[00:00:45] livestream vào những cái giờ nó hơi
[00:00:48] không theo một cái lịch cố định nào cả
[00:00:51] bởi vì mình kiểu mình nghĩ là mình tiện
[00:00:54] một hai tiếng vào đó thì mình sẽ học
[00:00:56] đúng không ạ? Chúng ta học sẽ như thế.
[00:00:59] Một là chúng ta có giờ cố định, hai là
[00:01:01] chúng ta khi nào tiện. Nói chung là vẫn
[00:01:03] thiên về cái việc mình khi nào tiện nhất
[00:01:05] thì mình học đúng không ạ? Có gì mình
[00:01:07] livestream lại thì vẫn sẽ có
[00:01:10] vẫn có người xem lại mà nên không sao.
[00:01:12] Ồ, xin chào bạn. Bạn người đầu tiên vừa
[00:01:16] không biết rồi. Chắc là tối nay thì tối
[00:01:19] nay chủ nhật thì chắc là vẫn sẽ có người
[00:01:21] rảnh như mình. À tôi không nói không có
[00:01:25] việc gì làm thì không đúng. Thực ra là
[00:01:27] mình nghĩ ra gần đây mình đã nghĩ ra rất
[00:01:29] nhiều thêm nhiều thứ nữa mà mình muốn
[00:01:31] làm để vai code các thứ thứ nhưng mà
[00:01:35] làm là một chuyện mình vẫn cần phải học
[00:01:37] thêm nữa. Và mình nghĩ việc mình
[00:01:40] livestream học thế này biết đâu biết đâu
[00:01:42] truyền cảm hứng được cho những bạn nào
[00:01:44] cần. À bấy ví dụ điển hình à mỗi lần
[00:01:48] mình livestream này mình cảm thấy cũng
[00:01:49] rất là bất ngờ khi mà có thêm nhiều
[00:01:51] người mới vào server Discord của mình.
[00:01:53] thì chứng tỏ chứng tỏ là à cũng có người
[00:01:58] có nhu cầu cũng người tìm đến đúng không
[00:02:00] ạ? Thì đơn giản là
[00:02:03] à
[00:02:05] mình ừ mình livestream những giờ dị này
[00:02:07] có khi là chẳng có ai live trùng với
[00:02:09] mình nói hay
[00:02:13] em mất gốc rồi học cùng anh được không
[00:02:15] ạ?
[00:02:16] Ờ nếu mà để em học Java
[00:02:20] mà từ đầu thì là không nên bởi vì cái
[00:02:25] nếu mà em để ý ở trong a cái danh sách
[00:02:29] trên kênh của anh thì anh có tạo một cái
[00:02:31] mục là mục khóa học hồi trước để mỗi
[00:02:32] trong playlist nhưng mà gần đây nó đẻ ra
[00:02:34] cái mục là mục khóa học ấy thì
[00:02:37] cái mục khóa học cost đấy thì mình để
[00:02:41] cái này ở số 6 cơ nghĩa là nó là phải là
[00:02:44] advance nó nâng cao.
[00:02:45] nó chuyên sâu hơn. Vì cái này là mình
[00:02:48] học là từ
[00:02:50] từ duy của việc là mình từ ngôn ngữ khác
[00:02:53] mình biết ngôn ngữ khác mình chuyển qua
[00:02:54] ngôn ngữ này và thậm chí là mình còn
[00:02:58] mạnh ở ngôn ngữ khác rồi cụ thể là PP
[00:03:01] đấy mình đã đi làm rồi còn nếu mà em
[00:03:03] muốn học gốc từ đầu thì thực ra anh
[00:03:05] không dạy Java từ đầu anh là dân học về
[00:03:09] ngôn ngữ lập trình là web PP HTML sẽ thì
[00:03:15] em muốn học về web thực ra là ngôn ngữ
[00:03:17] lập trình nào cũng n giống nhau thôi thì
[00:03:19] em có thể học cái a playlist đầu tiên là
[00:03:24] sẽ q out cơ nhưng mà học cái đấy có thể
[00:03:26] học song song làm học một tí về web cũng
[00:03:28] được đấy sau đó thì à em anh nghĩ là em
[00:03:33] chỉ cần xem ba video đầu là em sẽ định
[00:03:37] hình được là mình có phù hợp với cái ông
[00:03:39] thầy này không rồi đấy bởi vì là mình
[00:03:43] dạy mình sẽ thấy các bạn sẽ thấy một
[00:03:45] buổi của mình hai tiếng nói hay gì đó kể
[00:03:48] cả trên lớp luôn nhá là mình sẽ nói lý
[00:03:50] thuyết tầm chỉ có 15 30 phút thôi. Còn
[00:03:53] đâu chủ yếu là thực hành và chia sẻ thêm
[00:03:56] nhiều cái khác nữa thì
[00:03:59] đấy là một cách của mình học và cách
[00:04:01] mình dạy luôn.
[00:04:03] thì bạn thấy phù hợp hoặc thậm chí thậm
[00:04:06] chí bởi vì kiến thức đấy bạn thấy không
[00:04:07] đủ chẳng hạn bạn thể học thêm nhiều
[00:04:09] video sau cũng là một cách hoặc là học
[00:04:12] của song song của thầy khác bởi vì mình
[00:04:15] nhớ hồi trước thầy à có bạn cũng chia sẻ
[00:04:19] mình có tận ba thầy liền xong rồi xong
[00:04:21] rồi à bạn ấy học của mình đầu tiên để có
[00:04:25] truyền cảm hứng đã xong rồi bạn ấy học
[00:04:27] chuyên sâu nâng cao hơn thì từ các thầy
[00:04:28] khác nữa đấy nên là ừ Em có thể học của
[00:04:33] anh nhưng mà không phải là playlist này.
[00:04:35] Nếu mà giả sử em mới học về ngôn ngữ lập
[00:04:38] trình, em còn là sinh viên thì không
[00:04:40] nên. Còn nếu mà em đang đi làm rồi thì
[00:04:43] có thể vào để ngồi chúng ta cùng ngồi
[00:04:46] học ôn thêm những cái kiến thức bổ sung.
[00:04:49] Đấy, bởi vì cái này nó sẽ không đi mạnh
[00:04:52] vào cái phần
[00:04:55] gọi là cốt lõi theo kiểu dạng là nó vẫn
[00:04:58] có động vào base, nó động vào cái nền
[00:05:01] nhưng mà mình thấy là nó sẽ thiên về cái
[00:05:03] việc là
[00:05:05] kiểu nó không dạy về cú pháp này, nó
[00:05:08] không dạy về thế kiểu nên code thế nào
[00:05:11] mà nó sẽ là
[00:05:13] à không đúng nó dạy nên code thế nào nó
[00:05:17] không dạy việc là code thế nào cho chạy
[00:05:20] được mà lại dạy về code thế nào cho
[00:05:22] clean hay vân vân gì á chẳng hạn.
[00:05:26] Anh tiến tính chuyển sang Java hả anh? Ờ
[00:05:30] không thực ra là mình học cái này. Cái
[00:05:32] đầu tiên mình muốn ui không biết được
[00:05:34] các bạn đ các bạn không biết được mình
[00:05:36] đã ấp ủ học cái Java này từ ờ các bạn
[00:05:40] hình dung nhá. Mình à mình học ở trên
[00:05:44] trường xong rồi đi lại à xong rồi ở lại
[00:05:48] dậy đúng không ạ? Ở lại dậy bởi vì mình
[00:05:50] chuyên PP nên mình dạy mỗi PP thôi. Thì
[00:05:52] hồi đấy là có một môn Java nữa nhưng
[00:05:54] mình không dạy được. Đấy ngay tại thời
[00:05:56] điểm đấy mình đã nghĩ là tại sao mình là
[00:05:59] giảng viên dạy đáng ấy mình phải chuẩn
[00:06:01] là là mình có thể dạy được hết tất cả
[00:06:04] các môn để mà thể hiện nói chung là kiểu
[00:06:07] mình bao quát được ý. Đấy, ngay tại thời
[00:06:10] điểm đấy mình đã nghĩ là chắc chắn là
[00:06:11] mình về sau mình sẽ học Java để mình à
[00:06:15] mình
[00:06:17] để mà nói có thể dậy nó khó lắm. Chuẩn
[00:06:20] là với mình quan điểm nhá, dạy để làm
[00:06:23] được khác với dạy thực sự hiểu để dạy
[00:06:26] bởi vì nó na ná giống như là hồi trước
[00:06:29] có cái a tự nhiên cái này cứ hơi lan man
[00:06:31] một tí nhưng mà tôi thấy là nó cũng có
[00:06:33] một cái hay ý. Đấy, đó là hồi trước tôi
[00:06:36] lại nhớ một cái chủ đề ở trên Redit, nó
[00:06:40] là có một cái khái niệm đó là
[00:06:43] explain like I am fine, tức là hãy giải
[00:06:46] thích sao cho tao như một đứa trẻ 5
[00:06:48] tuổi. Đấy, kiểu thế. Tức là
[00:06:51] để mà ông dạy được một cái gì đó, ông
[00:06:53] phải nói cho một đứa thậm chí là không
[00:06:55] phải biết công nguyện ông tin, thậm chí
[00:06:57] là như một đứa trẻ ấ nó vẫn có thể hiểu
[00:07:00] được cái kiểu quy luật hay mọi thứ của
[00:07:03] nó. nghe nó rất là khó đúng không? Nhưng
[00:07:05] mà để mà để mà ông lên cái ngưỡng là ông
[00:07:07] thể nói cho người khác hiểu được như thế
[00:07:10] thì mới chuẩn là với tôi thấy là kiểu
[00:07:14] kiểu lý tưởng nhất ấy là dạy được. Còn
[00:07:18] nếu mà không thì chỉ cầm tay chỉ việc và
[00:07:21] sẽ thiên về việc là chỉ đâu đánh đấy hay
[00:07:24] gì đó. Tức là chỉ là sẽ gần như là tướng
[00:07:27] và lính kiểu thế cầm tay à chỉ đâu đành
[00:07:31] đó đúng không? Nhưng mà lính thì sẽ
[00:07:32] không bao giờ khó lên làm tướng nếu mà
[00:07:34] không được đào tạo hơn, không được học
[00:07:38] chiến lược hay vân vân. Ông có hình dung
[00:07:40] không? Nghĩa là đấy kiểu thế nghĩa là
[00:07:42] một một à hệ lại liên quan câu chuyện
[00:07:46] giống như là khi ông đi làm sẽ có rất
[00:07:48] nhiều sếp nó giống như boss nó giống như
[00:07:51] boss à có boss v leader chắc là tôi từng
[00:07:54] nói với ông khái niệm đấy đây kiểu như
[00:07:57] này này là người sếp sẽ luôn là người
[00:08:00] chỉ việc thôi chỉ là mày phải làm vớiz
[00:08:02] thôi thực sự là không hề không hề cho
[00:08:05] ông thêm kiến thức ông tự mình thêm kiến
[00:08:09] thức chứ người đấy không cù cung cấp cho
[00:08:10] ông thên kiến thức. Đấy, còn người
[00:08:12] leader, người lãnh đạo chuẩn thì là
[00:08:15] người có thể tiên phong, người đi cùng
[00:08:17] và có thể hướng đến. Và thậm chí là có
[00:08:19] cái câu của Anonymus à đó là
[00:08:23] chuẩn là nó sẽ phải tạo ra được các
[00:08:26] leader khác nữa. Nghĩa là kiểu
[00:08:30] mình à chia sẻ thêm kinh nghiệm, mình
[00:08:32] chia sẻ thêm mọi thứ để khiến cho những
[00:08:33] người khác sẽ có sẽ có cơ hội để trở
[00:08:37] thành người kiểu tốt hơn và kiểu có
[00:08:40] những vị trí về sau giống mình. Đấy,
[00:08:43] tránh cái việc là mình chỉ ở cấp trên,
[00:08:46] mình ở bề trên mình áp xuống và thậm chí
[00:08:48] ông nào mà phản lại thì mình đuổi hoặc
[00:08:51] gì đó đúng không ạ? Thì rõ ràng là môi
[00:08:54] trường này môi trường không phù hợp để
[00:08:56] mình phát triển. Đấy, tôi nói hơi lan
[00:08:58] man nhưng mà nó vẫn có một cái gì đó
[00:09:00] đúng không ạ?
[00:09:01] Thì uầy tự nhiên đang nói chuyển sang
[00:09:03] đang từ hỏi một câu thì nhảy sang cái
[00:09:05] này. Nhưng đại khái tôi không hẳn là
[00:09:08] chuyển sang Java mà tôi học Java muốn
[00:09:11] học Java từ lâu và càng về sau càng cùng
[00:09:13] cố thêm là tôi học chuyên sâu. Tôi làm
[00:09:16] chuyên sâu thêm về PP tôi thấy có rất
[00:09:19] nhiều vấn đề phát sinh đặc biệt liên
[00:09:21] quan về button design button và
[00:09:25] tôi muốn chuyên sâu về back end. Thực sự
[00:09:27] đến bây giờ tuy r là tôi đã gần đây tôi
[00:09:30] động fan nhiều hơn nhá là tôi may mà cảm
[00:09:33] ơn ai một lần nữa cảm ơn ai đã ngồi cho
[00:09:35] tôi kiểu được vai code để ngồi gọi là
[00:09:39] sửa giao diện các thứ xịn m màu mè hồi
[00:09:42] trước CF các thứ hơi kém hơ không quan
[00:09:46] tâm thì nó kém ý đấy nhưng mà tôi thật
[00:09:48] sự về sau vẫn muốn chuyên sâu về back
[00:09:50] end thì về thứ nhất là ngôn ngữ lập
[00:09:53] trình thứ hai về database thì rõ ràng là
[00:09:56] PP P không được thiên về việc xử lý
[00:10:00] những bài toán rất là lớn và ở những
[00:10:02] công ty lớn thì không dùng PP nên là về
[00:10:06] sau tôi sẽ thứ nhất là tôi phải học về
[00:10:09] lean architect các thứ thứ đúng không?
[00:10:11] Thứ hai là để về sau mình không ngại một
[00:10:15] ngôn ngữ lập trình nào chưa chắc là Java
[00:10:17] mình có thể về sau Gan hay gì đó nhưng
[00:10:21] kiểu gì nó vẫn có một cái nền tảng nhất
[00:10:22] định là hướng đối tượng đúng không
[00:10:25] button các thứ nó vẫn giống nhau thôi
[00:10:27] nên là học Java nó là cái kiểu cái nền
[00:10:30] để mà mình có thể học ngôn ngữ khác chứ
[00:10:32] không phải là tôi sẽ chuyển sang Java vì
[00:10:34] rõ ràng bây giờ tôi làm gì có dự án Java
[00:10:36] nào để mà thực hành đâu đấy nhưng mà
[00:10:39] trong cái khóa học trăm mành này này tôi
[00:10:42] sẽ tôi sẽ muốn sẽ làm sau đó đấy.
[00:10:51] đây th kiểu thế bởi vì thực sự để mà nói
[00:10:54] nhá tôi không chê người khác về kiến
[00:10:57] thức nhưng tôi khẳng định luôn là không
[00:10:58] phải người thầy nào ở bên ngoài kia kể
[00:11:00] cả đi đi dạy ở trung tâm hay dạy đại học
[00:11:04] không phải thầy nào cũng có tâm đấy nên
[00:11:07] là sẽ mang giống kiểu thợ dậy hơn không
[00:11:11] thầy không phải thầy nào bởi vì nói
[00:11:13] thẳng luôn có nhiều thầy còn kiểu vì cái
[00:11:15] tôi bản thân kiểu muốn đèn ép sinh viên
[00:11:17] muốn a nói thẳng luôn là muốn có một tí
[00:11:21] từ sinh viên các thứ rất nhiều vấn đề
[00:11:23] đúng không ạ rất nhiều vấn đề đấy không
[00:11:25] phải thầy nào cũng kiểu thực sự là kiểu
[00:11:26] xát xao sinh viên có người thì bảo với
[00:11:29] tôi là thầy làm thế để sinh viên không ỷ
[00:11:33] lại cũng có thể đúng nhưng tôi đã từng
[00:11:36] chia sẻ một câu chuyện của tôi và bạn
[00:11:38] tôi đó là cóòn những người thầy khiến
[00:11:41] cho bạn đấy hoặc là thậm chí tôi cũng
[00:11:44] từng rất ghét người như thế may là tôi
[00:11:46] đi làm rồi Nên tôi kẻo biết được à trong
[00:11:50] ngành này có người này người kia. Nhưng
[00:11:51] mà rõ ràng có những sinh viên ở trên
[00:11:53] trường người ta mới ngồi trên ghế nhà
[00:11:55] trường không được tiếp xúc mấy. Xong rồi
[00:11:58] cái người mình tiếp xúc nhiều nhất là
[00:11:59] thầy của mình ở trong ngành này đúng
[00:12:01] không ạ? Thì người thầy đấy người ta
[00:12:04] không phục, người ta không thích thì
[00:12:06] người ta sẽ không baoờ muốn trở thành
[00:12:07] người như thế. người ta sẽ không theo
[00:12:09] ngành này. Đấy thì rõ ràng là thế là một
[00:12:13] cái kiểu tự nhiên biến thành cái viết
[00:12:16] nhơ ở trong ngành đúng không ạ?
[00:12:23] lại dùng bên thứ ba dậy ạ. Tự tổ chức là
[00:12:25] phức tạp hay sao? À cái việc cái trang
[00:12:28] hồi trước mình có cái trang ấy thế bạn
[00:12:30] còn biết cả trang blog của mình ờ hồi đ
[00:12:33] hồi đấy là hồi hồi đầu mình viết block
[00:12:36] ấy mình nhớ là từ 52 53 gì đấy phải mình
[00:12:40] không nhớ chính xác lắm giờ chắc phải
[00:12:42] xem lại. Đại khái là hồi đấy là mình
[00:12:44] dồng tạm cái trang nhanh để mà lên nhanh
[00:12:45] thôi. Vì hồi đấy là bây giờ bảo code từ
[00:12:48] đầu nó hơi mất công. Kết hợp phải tìm
[00:12:50] hiểu. Thực ra là mình cũng không quan
[00:12:52] trọng cái đấy lắm vì rõ ràng là mình lúc
[00:12:54] đấy chỉ cần có một nơi để đăng lên. Và
[00:12:56] thực ra là hồi đấy mình đăng theo kiểu
[00:12:58] dạng là muốn tự sự hơn là để mang thức
[00:13:02] tính là học thuật hay chia sẻ. Thế nên
[00:13:04] là các bạn thấy là mình đến bây giờ mình
[00:13:06] cũng vẫn không viết đều lâu lắm không
[00:13:08] viết.
[00:13:09] cái việc là mình không a không chia sẻ
[00:13:12] cho các bạn cái trang blog đấy. Bây giờ
[00:13:15] mình hoạt động vẫn là sôi nổi trên trang
[00:13:19] fanpage Facebook lẫn cả à fanpage gần
[00:13:21] đây còn ít cơ. Chắc là bây giờ sôi nổi
[00:13:23] nhất ở trên server Discord bởi vì mình
[00:13:25] thấy là trên server Discord là mọi người
[00:13:27] có tương tác trên đấy nhiều nhất. Đấy
[00:13:29] thì mình làm mình mình làm ở nơi nào mà
[00:13:33] tương tác được mọi người nhiều thôi để
[00:13:35] mình hiểu được mọi người thôi đúng không
[00:13:36] ạ? Còn block thì nó có một tí nhá. Mang
[00:13:39] thiên hướng là tuy là mấy ông bình luận
[00:13:41] ở đấy được đúng không? Nhưng mang thiên
[00:13:42] hướng một tí là kiểu hơi dẫn dắt dư
[00:13:45] luận. À mấy ông biết khái niệm đấy
[00:13:47] không? Tức là kiểu ông đăng ở trên xong
[00:13:49] rồi
[00:13:50] sẽ có một tràng xong mới đến cái phần
[00:13:52] bình luận của ông mà đúng không? Thì rõ
[00:13:54] ràng là ông sẽ bị dắt một tí nữa đấy. Và
[00:13:57] rất ít người kéo xuống dưới để mà tranh
[00:13:59] luận. Nên thành ra là kiểu tôi sẽ có một
[00:14:02] cái gì đó ở trên đấy nó tương tác không
[00:14:03] phải là hai chiều. Đấy, tương tác hai
[00:14:06] chiều ở đây vẫn là server Discord hoặc
[00:14:08] là nhóm Facebook nhưng mà tôi không ngại
[00:14:11] việc tạo hẳn cái nhóm rồi quản lý đấy á.
[00:14:14] thì tôi đã từng quản lý nhóm và
[00:14:17] nói chung là ờ
[00:14:21] tôi thấy là hiện tại bên server Discord
[00:14:23] hiện tại vẫn vẻ đang ổn đấy chưa biết
[00:14:25] sau này thế nào và thực ra tôi cũng
[00:14:26] không nếu nếu biết đâu về sau mình nồn
[00:14:30] nổi hơn mình nổi tiếng hơn thì mình còn
[00:14:31] không thời gian nữa mình sẽ phải nhờ
[00:14:33] người khác quản lý à tôi hơi ngại cái
[00:14:36] điều đề điều đấy tôi không muốn mình cực
[00:14:39] kỳ nổi hay là kiểu có quá nhiều đông
[00:14:41] người vào khiến nó loãng một cái gì Đó,
[00:14:44] nếu mà giả sử về sau mà server này nó
[00:14:46] đông hơn, ví dụ bây giờ 1000 người nhưng
[00:14:48] thực ra là chỉ có tầm à cứ cho 100 đi
[00:14:50] 100 là cao thôi nhá. 100 người tương tác
[00:14:52] thường xuyên thì còn đỡ. Hiện tại mấy
[00:14:55] thấy các bạn thấy là tin nhắn nó vẫn
[00:14:57] chưa bị trôi đúng không ạ? Nếu về sau
[00:14:59] đông hơn thì chắc là tôi sẽ mở nhóm
[00:15:01] Facebook để cho hạn chế bị trôi, mọi
[00:15:03] người có thể đọc được những cái gì nó
[00:15:05] chất hơn. Đấy, dự định tôi là thế.
[00:15:09] Còn về vlog thì
[00:15:12] như mình chia sẻ mình không có quá nhiều
[00:15:14] kiến thức để mà mình chia sẻ cho các bạn
[00:15:17] quá kiểu chi tiết blog nó phải chiêm
[00:15:21] nghiệm, nó phải đúc kết nó nào giống như
[00:15:22] ở ông viết sách ấy. Theo tôi là thế.
[00:15:25] nghĩa là nó phải cực kỳ cô đọng chứ nếu
[00:15:27] mà mình chỉ viết kiểu tự sự toàn mạn thì
[00:15:30] nó là block theo kiểu
[00:15:33] nó sẽ không mang thiên hướng về chia sẻ
[00:15:36] nữa mà kiểu tâm sự hơn.
[00:15:40] Anh có tự tin giao tiếp phỏng vấn bằng
[00:15:42] tiếng Anh không ạ? Thực ra là ông thấy
[00:15:44] cái video gần nhất tôi đăng đó là tôi
[00:15:47] chính xác là tôi phỏng vấn trả lời phỏng
[00:15:49] vấn của một bên và tôi phải nói song ngữ
[00:15:53] bởi vì tôi không nói hoàn toàn bằng
[00:15:55] tiếng Anh được vì mình quen giao tiếp
[00:15:57] anh liên tục đâu. Đấy
[00:16:00] nhưng mà tôi tôi tự tôi được cái tôi rất
[00:16:04] là tự tin. Tôi biết được ưu nhược của
[00:16:07] mình là gì và tôi khá là tự tin và khả
[00:16:11] năng của mình đến đâu. Về việc nói
[00:16:13] chuyện tiếng Anh bình thường thì tôi vẫn
[00:16:15] nói được. Kể cả hôm trước phỏng vấn bằng
[00:16:18] tiếng Anh tôi vẫn nói được. Đấy chẳng
[00:16:20] qua là tôi không tự tin việc mình nó rất
[00:16:22] là hay, nói rất là tốt hay có gì gì đó.
[00:16:25] Đặc biệt là mình chưa có luyện cái việc
[00:16:27] là âm điệu à cái thần thái, phong cách
[00:16:31] gì thế đó. Bởi vì là mình tính a là tôi
[00:16:32] mới chỉ có xem phim nghe nhạc là nhiều
[00:16:35] chứ thực ra là thực hành ít lắm cũng
[00:16:37] chưa thi một cái chứng chỉ tiếng Anh nào
[00:16:39] vào.
[00:16:42] Đợi tôi một tí tôi xem tí nhắn
[00:17:11] Ờ thì hôm qua nhưng bạn thấy thật ra bạn
[00:17:14] thấy tiêu đề nó bị lạp với cái hôm qua
[00:17:16] đúng không ạ? Bởi vì hôm qua chúng ta
[00:17:17] chưa học được cái gì cả. Rất xin lỗi các
[00:17:19] bạn. Hôm hôm qua mình mới a ơ
[00:17:24] đúng rồi mình định bảo làm
[00:17:27] cái này tổng hợp thành cái ảnh nhưng mà
[00:17:29] mình quên mất là hôm qua chưa học để
[00:17:31] mình biết được cô đọng là một cái ảnh nó
[00:17:32] trông nên trông như thế nào để cho nó
[00:17:35] tổng hợp thông tin. Đây mình hôm nay
[00:17:38] mình sẽ bắt đầu học và hôm nay để bù cho
[00:17:40] cả hôm qua nữa hôm nay mình sẽ cứ cho là
[00:17:42] hôm nay buổi thứ sáu nhá. Thì tí mình sẽ
[00:17:44] soạn luôn cả bài buổi thứ sáu để mình sẽ
[00:17:48] học cả buổi bài thứ năm thứ sáu. Còn hôm
[00:17:51] qua chỉ bài ôn lại thôi.
[00:18:07] rồi. Không biết lần này nó sẽ à đâu cái
[00:18:10] này gọi không phải reset mà restart à.
[00:18:14] Đây không biết lần này nó sẽ có thêm cái
[00:18:17] cập nhật cái gì.
[00:18:24] dùng AI để viết zoom nữa. Đúng mình nên
[00:18:28] thì nó kiểu giống kiểu cá nhân hóa thôi
[00:18:30] đúng không? Nhìn thấy hay mà.
[00:18:32] Đây, đợi mình tí, mình muốn xem cái trên
[00:18:35] lock của nó nó sẽ thêm cái gì. Ừ, cải
[00:18:39] thiện mỗi cái này. Thế mà bị thật à cải
[00:18:42] thiện để cho long conversion. Ok. Kiểu
[00:18:45] cải thiện thêm gì đó. Ok.
[00:18:49] Xin chào bạn. À
[00:18:54] bạn này có hoạt động thời
[00:18:56] bé yêu group X Group không?
[00:18:59] Thôi không biết nhóm đấy. Nay anh học
[00:19:02] sớm thể à. Tiện tiện người yêu chưa qua
[00:19:05] chơi đi chơi thì mình tranh đủ học thôi
[00:19:06] ạ. Ờ
[00:19:10] các file ơ cái này postit rồi mà đúng
[00:19:12] không?
[00:19:14] Hôm qua cập nhật rồi mà nhỉ? Đúng không?
[00:19:16] Cập nhật rồi thêm cái gì gì đó rồi đúng
[00:19:18] không?
[00:19:20] Hôm qua thêm rồi mà. Hay đâu? Xem lại
[00:19:23] nào.
[00:19:36] rồi mình sẽ soạn ra một cái doc. Đây các
[00:19:41] bạn thấy là tham khảo mình sẽ có thêm
[00:19:43] dog xong rồi có thêm cả ảnh nữa rất xịn
[00:19:45] đúng không ạ? Đấy rất chuyên nghiệp dần
[00:19:47] dần dần biết đâu về sau tôi làm thêm quả
[00:19:50] code hoặc là thực ra là có những cái
[00:19:52] tool có sẵn rồi mình sẽ biến cái này
[00:19:53] thành slide kiểu power point. Đấy, hồi
[00:19:57] trước là tôi từng dạy mấy ông thì mấy
[00:19:58] ông thấy là tôi chẳng dùng PowerPoint gì
[00:20:00] cả đúng không ạ? Nó không chuyên nghiệp.
[00:20:02] Đúng, nó vẫn không hề chuyên nghiệp.
[00:20:04] Đấy, để tôi sẽ làm quả đấy luôn. Hoàn
[00:20:07] thành. Bạn muốn bắt đầu với sáu luôn
[00:20:11] không?
[00:20:13] À đợi tí tôi bảo thằng này soạn luôn.
[00:20:16] Dựa
[00:20:21] Tôi muốn
[00:20:24] dựa vào file này tạo
[00:20:28] và
[00:20:48] ngày 6.
[00:21:01] đâu sao?
[00:21:16] à cái link cái link GHub này đúng không?
[00:21:21] À cái này là đây là bạn sinh viên của
[00:21:23] tôi. Tôi nhờ bạn đấy tạo cái a tạo cái
[00:21:28] repo lúc đầu bởi vì lúc đầu là tôi nhờ
[00:21:30] bạn ấy dạy tôi Java mà bạn ấy chuyên về
[00:21:32] Java thì dạy nhờ nhờ bạn ấy tạo Ripo dạy
[00:21:36] tôi buổi một rồi tôi thấy hay quá là từ
[00:21:38] đấy tôi nghĩ là tôi có kiểu háo hứng hơn
[00:21:41] tôi muốn học nhiều hơn và tôi muốn
[00:21:43] livestream về mấy ông học cùng nữa vì
[00:21:45] bạn ấy cũng không thường xuyên để mà
[00:21:47] hàng ngày học cùng mình được kiểu mình
[00:21:50] tự học và có dùng AI hay mọi thứ như này
[00:21:52] mình chủ động mình vẫn tiện hơn đúng
[00:21:53] không
[00:21:54] Đấy. Thế nên là tôi nhờ bạn ấy tạo lúc
[00:21:57] đầu thôi. Và bạn ấy vẫn có xem video của
[00:22:00] tôi và vẫn kiểu sẽ góp ý các thứ các
[00:22:04] thứ. Và tôi cũng muốn là mấy ông nếu có
[00:22:06] thể thì gọi là khái niệm double check à
[00:22:08] tức là ngồi kiểm tra lại xem cùng tôi
[00:22:10] xem có vấn đề gì không. Ngồi góp ý ngồi
[00:22:13] học cùng đúng không ạ?
[00:22:21] sáu rồi sau cái này tên là Animal này.
[00:22:30] object class à ok. Uầy
[00:22:35] không nhưng mà thực ra là tôi không cần
[00:22:37] file class lắm. Tôi không muốn có file
[00:22:39] class ở đây. Chỉ muốn có file
[00:22:44] ơ hình như vừa rồi mình xóa gì sai sai
[00:22:46] phải. Đợi tí. À đâu đúng mà.
[00:22:49] Sao file ja có một file Java mà tạo được
[00:22:52] nhiều file class thế á?
[00:23:05] file class à
[00:23:15] Ý ông là sao? Nghĩa là dùng cái à vào
[00:23:17] thẳng code project chứ không phải ngồi
[00:23:19] học này á.
[00:23:26] sẽ có mà trong này mấy ông thấy là kiểu
[00:23:29] gì về sau cũng sẽ có ngồi code không có
[00:23:32] chỉ có ngồi xuông này đâu. Học đây đặt
[00:23:36] tảm các thứ đấy. Sau ngày 25 đúng không?
[00:23:39] Cứ cho là 1 tháng đúng không? Th thực ra
[00:23:42] đấy còn chưa tính việc thỉnh thoạc tôi
[00:23:43] nghỉ bất chợt nữa đấy. Mình sẽ có dự án
[00:23:46] các thứ thứ lúc đấy tôi ngồi code cho
[00:23:48] mấy ông xem được không ạ? Ok tạm chốt
[00:23:50] thi nhá. Còn à
[00:23:58] muốn cái ở đây nó cái này nó nên ngắn
[00:24:01] gọn xúc tích thôi. Không nên có quá
[00:24:03] nhiều file.
[00:24:06] Ok. Ờ à không mình không nên xem doc
[00:24:09] mình nên xem code trước. Doc tính sau
[00:24:12] đấy code dễ hiểu như kiểu tôi lại nhớ
[00:24:15] cái câu của anh em lập trình hay nói với
[00:24:19] nhau kiểu đừng có giải thích nhiều. Show
[00:24:21] me your code đúng không? Anh được code
[00:24:23] của máy đây. Đấy
[00:24:27] thỉnh thoảng tôi bây giờ tôi không phải
[00:24:29] thỉnh thoảng tôi bắn tiếng Anh đâu nhá
[00:24:30] mà nó chỉ là có những cái tôi nghĩa là
[00:24:33] nó là me me à mim à. Đấy cái có nhiều
[00:24:37] cái là tôi sẽ và tôi cũng muốn một tí
[00:24:41] gọi là thực hành tiếng Anh với mấy ông
[00:24:42] cứ cho là thế đi chứ bình thường ngoài
[00:24:44] tôi không bằn tiếng Anh đâu.
[00:24:52] Cách cũ không dùng generic nguy hiểm
[00:24:55] không chỉ định kiểu so kháng thêm số vào
[00:24:59] complier không báo lỗi. À ui cái lỗi này
[00:25:03] vẫn vẫn đôi khi vẫn phải quay lại một tí
[00:25:05] với PP. PP mảng chứa bất kỳ cái gì được
[00:25:08] mà chứa mảng mà chứa mọi thứ cũng được
[00:25:09] trong đấy. Đấy khá là nguy hiểm đúng
[00:25:12] không ạ?
[00:25:18] khai báo này giống script một tí nhở. À
[00:25:21] đương nhiên là có khi script sinh sau mà
[00:25:23] tôi nhớ hình như là về sau tôi mới nghe
[00:25:26] script chắc là script sinh sau thì đó là
[00:25:28] script sẽ học từ cái thằng này đúng
[00:25:30] không ạ? Là để cho code ra script nó
[00:25:32] chặc chẽ hơn đúng không ạ? Đấy. Đấy. T
[00:25:36] safety. Ok. Bao lỗi hợp lý
[00:25:40] không có nép kiểu class tổng quát
[00:25:45] box có thể chữ bất kỳ kiểu dữ liệu gì.
[00:25:49] Ơ đợi tí. Array này,
[00:25:52] elite này.
[00:26:08] đang chưa hiểu cái này lắm.
[00:26:32] sẽ so sánh đây. Tôi sẽ tạm đánh dấu lại
[00:26:36] box à iit này
[00:26:40] đúng không ạ? P box này
[00:27:01] báo ở dưới. Ok. Làm tôi cứ tưởng là nó
[00:27:03] là một cái kiểu mới.
[00:27:07] Ừ. Có khi cái này nhược điểm khi mà đọc
[00:27:09] trong cái Java đúng không? Đọc trong
[00:27:11] class này nó sẽ tách tách file ra tránh
[00:27:13] việc là mình kiểu không hiểu đúng không?
[00:27:17] À đây
[00:27:20] khai báo kiểu à đúng rồi khai báo kiểu
[00:27:22] này giống kiểu get set một cái gì đó
[00:27:24] đúng không? Ok
[00:27:27] cũng hay khai báo kiểu này à t value
[00:27:33] t này là gì nhỉ?
[00:27:36] À tham số kiểu có thể đặt tên bất kỳ
[00:27:43] đúng không? Time này
[00:27:46] element key value gì đó. Ồ thường ở
[00:27:50] trong
[00:27:53] thường ở trong a PP đúng không? thì mình
[00:27:56] sẽ không dùng t bao giờ mấy mình sẽ dùng
[00:28:01] ở mình một được ghi thẳng là key type
[00:28:04] key value hay gì gì đó value gì đó
[00:28:14] rồi
[00:28:24] hàm tổng quát
[00:28:29] &gt;&gt; chị
[00:28:53] ra em cún này ngoan hơn á em cún nếu mấy
[00:28:57] ông xem video tôi á từ thời đầu đi hồi
[00:29:02] đấy là tôi còn ở nhà khác xong rồi tôi
[00:29:04] cũng có nuôi một em cún nhưng em đấy là
[00:29:06] phốc em đấy rất là đánh dùng từ đánh đá
[00:29:11] nó cũng không đúng vì nó con trai sẽ
[00:29:13] dùng từ như này rất là kiểu
[00:29:17] khó dạy kiểu thế khó nó còn em này rất
[00:29:21] là ngoan em dễ dạy ngoan hiền chắc một
[00:29:23] phần em này con cái nữa
[00:29:26] Không, tôi chưa mua nhà đâu. Ui ông ơi,
[00:29:28] bây giờ mình còn đang đi làm thuê
[00:29:31] &gt;&gt; vốn còn chưa không có sẵn tự lực cánh
[00:29:33] sinh ngay từ đầu. Nghĩa là nghĩa là đúng
[00:29:35] nghĩa đúng nghĩa là bố mẹ không có sẵn
[00:29:37] nhà nên là tôi vẫn đang đi làm thu vẫn
[00:29:39] đang đi thuê nhà ấy. Ở Hà Nội thì tôi
[00:29:43] cũng chưa biết được khi nào sẽ mua được
[00:29:45] nhà. Có thể là mua nhà xã hội hay gì đó
[00:29:49] &gt;&gt; nhưng mà thực ra là mình cũng quá cái
[00:29:52] gì nhỉ? Ba cái điều kiện rồi. Nghĩa là
[00:29:55] mức lương của mình nó ở cái đoạn mà
[00:29:58] không phải đủ để mua nhà ở xã hội nhưng
[00:30:01] mà cũng không đủ để mua nhà vì rõ ràng
[00:30:05] là
[00:30:06] quê á tôi tôi quê gốc thì là quảng trị.
[00:30:11] Tôi nghĩ là tôi sẽ không hẳn về đấy vì
[00:30:13] rõ ràng là thường người ở quê tôi sẽ đi
[00:30:15] tỉnh khác để mà sinh sống để mà kiêm
[00:30:17] sống. Đấy. Còn à Quế ngoại thì ở Hà ở
[00:30:22] Linh Đàm là ở Hà Nội đúng không ạ? Nên
[00:30:24] là tôi thường là tết tôi sẽ không có quê
[00:30:27] để về. Không giống các bạn lắm đấy. Nên
[00:30:31] là nó sẽ không có cái trường hợp với quê
[00:30:34] mà sẽ khái niệm đi ra một cái tỉnh nào
[00:30:36] đó để ở chứ không khái niệm về quê nữa.
[00:30:40] Ông hiểu gì? Tôi đấy. À biết rồi thì
[00:30:43] cũng có cách thứ ba là bây giờ lấy vợ
[00:30:45] rồi về quê vợ.
[00:30:47] Hoặ thậm chí là mấy vợ vợ có sẵn nhà
[00:30:50] mình về kiểu chạn vương chui chạn đấy
[00:30:59] hẳn là tôi nghĩ là trong trường hợp của
[00:31:01] tôi thì vẫn à không phải bế tắc hay là
[00:31:05] kiểu gì nó tiêu cực hay là kiểu khổ hay
[00:31:08] gì đó tôi cảm thấy là đang đủ sống và
[00:31:10] đang rất là thoải mái chẳng qua là nó
[00:31:13] không
[00:31:15] với nhiều người là sẽ
[00:31:16] mình chưa ăn cư, chưa lập nghiệp các thứ
[00:31:18] đúng không? Đấy nên thật ra khái niệm ăn
[00:31:21] cư của tôi thực ra hình như tôi cũng
[00:31:23] từng chia sẻ mấy ông rồi. Ăn cư ra nó sẽ
[00:31:25] không khái niệm là ăn cư là phải là có
[00:31:29] có nhà ăn cư. Theo tôi vẫn là hiểu là có
[00:31:31] một cái máy ấm
[00:31:41] nghiệp ở Đấy Á. Thực ra cũng khó bởi vì
[00:31:44] bây giờ tính ra thì bây giờ một là ở Hà
[00:31:47] Nội, hai là ở Đà Nẵng hoặc là thành phố
[00:31:50] Hồ Chí Minh thì cái nghề IT này nó mới
[00:31:52] gọi là triển vọng. Còn bây giờ đi bất kỳ
[00:31:54] tỉnh khác thì trừ khi ông làm ông xin
[00:31:57] được việc làm remote, làm online còn
[00:32:00] thậm chí ông phải sang nước ngoài gì đó.
[00:32:02] Nếu không thì tự nhiên mình lại khiến
[00:32:05] cho công việc mình khó khăn hơn đúng
[00:32:07] không ạ? Hoặc là phải chuyển ngánh.
[00:32:08] Chuyển ngành thì
[00:32:11] ngành bây giờ nếu mà tôi mà có chuyển
[00:32:12] ngành thì tôi không hẳn là có ý định
[00:32:15] kinh doanh lắm thì chắc là tôi đi dạy mà
[00:32:17] tôi đi dạy chắc là tôi vẫn dạy cái thế
[00:32:19] mạnh của mình là dạy tin học chẳng hạn
[00:32:21] dạy công tin thì về quê thì tính ra nó
[00:32:24] lại không gọn là như nào nhỉ ví dụ một
[00:32:28] cái điển hình nhá
[00:32:30] à năm ngoái là ờ Bộ Giáo dục vừa mới
[00:32:34] thay đổi cái quy chế thi là môn
[00:32:38] Môn thi tốt nghiệp đại học có thể à môn
[00:32:41] thi tốt nghiệp để đỗ vào đại học.
[00:32:45] Nghĩa là thi đại học ấy thì bây giờ có
[00:32:48] thêm môn nữa là môn tin học. Đấy có biết
[00:32:51] cả nước được bao nhiêu người a thiin học
[00:32:54] không? Đấy cho dù nó có kiểu rõ ràng là
[00:32:58] anh em mình vẫn kiểu có thể ngồi chơi
[00:33:00] game nhiều. Chắc chắn là game game thủ
[00:33:02] giờ nhiều hơn thời trước của tôi luôn
[00:33:04] đúng không? Nếu không biết tỉ lệ bao
[00:33:06] nhiêu người chọn môn tin học không? Nó
[00:33:08] còn thấp hơn cả môn công nghệ cái gì đó.
[00:33:12] Tôi không nhớ cụ thể cái môn đấy lắm
[00:33:13] nhưng mà tôi nhớ nó là môn kiểu na dầu
[00:33:15] công nghệ. Tức là ở các tỉnh các thứ
[00:33:19] người ta vẫn dạy không hẳn dạy về nhiều
[00:33:22] về tin và không ai tự tin. Và khoản là
[00:33:24] có thể thi vào mónn tin. Cho dù rõ ràng
[00:33:26] là mình có thể dùng máy tính bây giờ
[00:33:27] nhiều hơn rất nhiều đúng không? Mình
[00:33:30] thạo dùng công tin, mình dùng AI, mình
[00:33:33] dùng mạng xã hội hay vân vân vân các thứ
[00:33:36] mình hạo hơn rồi. Nhưng mà tự nhiên bây
[00:33:39] giờ mình có thêm một cánh cổng nữa và
[00:33:41] thi bằng tin học thì mình cũng không tự
[00:33:45] tin lắm. Môn tin học tôi nhớ là gần như
[00:33:47] thấp nhất đấy. Tỉ lệ thấp nhất ấy. Đấy
[00:33:52] thì rõ ràng là tin học không hề được
[00:33:54] trọng dụng lắm
[00:34:02] dạy thêm tín học hay gì đó. Nhưng mà
[00:34:05] mình nghĩ là nó vẫn là xu thế tương lai
[00:34:07] thôi bởi vì là nó thay đổi là thay đổi
[00:34:10] năm ngoái nhưng mà mình sẽ cập nhật dần
[00:34:12] ngay từ hồi lớp 10. Nghĩa là nó sẽ không
[00:34:15] phải thay đổi lớp mỗi lớp 12 mà sẽ kiểu
[00:34:18] phổ cập lại luôn cả kiến thức của lớp
[00:34:19] 10, lớp 11, lớp 12. Thì rõ ràng là những
[00:34:21] cái bạn mà xác định là thi môn tin học
[00:34:25] thì người ta sẽ học từ lớp 10. Đấy. Thì
[00:34:29] 2 năm nữa thì mình sẽ xem là cái thị
[00:34:32] trường cái mọi thứ nó có thiên hướng về
[00:34:36] xuôi về bên môn tin học không. Mà rõ
[00:34:38] ràng là bây giờ rõ ràng là các bạn thấy
[00:34:40] thi vào ngành IT ngành công nghệ thông
[00:34:42] tin vẫn rất đông đúng không ạ? Nhưng mà
[00:34:44] mọi người không chọn môn tin học, mọi
[00:34:47] người vẫn chọn những cái môn mà họ đã ôn
[00:34:48] sẵn rồi. Đó là môn toàn lý hóa hay gì gì
[00:34:50] đó. Đấy,
[00:35:01] bẻ đôi cũng chịu. Đúng. Thực sự là kiểu
[00:35:04] có nhiều người mà chỉ cần bởi vì mình
[00:35:07] vẫn thấy thiên hướng đó là người nào mà
[00:35:09] không học công nghệ thông tin người ta
[00:35:10] là khá là ngại rất là ngại. Tỷ lệ mình
[00:35:13] gặp người công nghệ đ kiểu không phải
[00:35:16] ngành công nghệ thông tin ấy mình chỉ
[00:35:18] cần nói về việc là bây giờ dùng AI đi
[00:35:20] người ta đã ngại rồi. Đấy kiểu thế nghĩa
[00:35:23] là người ta cứ ngại cái gì thay đổi. Mà
[00:35:26] rõ ràng công nghệ thông tin là như hôm
[00:35:28] trước mình phân tích là không ngại thay
[00:35:31] đổi, mình phải mở thoáng cái đầu lên chứ
[00:35:34] nếu mà ngại ngại một cái gì đó không
[00:35:36] theo được ngành này. Thật không theo
[00:35:38] được ngành này. Và đúng có những người
[00:35:41] mình quen cũng học công nguyện pin nhá.
[00:35:44] Mình chỉ đơn giản họ đang dùng VS code
[00:35:46] thôi nhá. Mình bảo bạn ấy cài
[00:35:48] antigravity hay là Cor gì đó dùng AI
[00:35:51] khác đi. Bạn ấy cũng ngại, bạn không
[00:35:53] cải, bạn ấy có biết chat GVT nhá, bạn
[00:35:56] chỉ hỏi chat GVT thôi. Xong rồi tôi bảo
[00:35:58] chat cho GVT bây giờ hỗ trợ code tệ lắm,
[00:36:01] mình nhảy sang cái ai khác đi. Bạn ấy
[00:36:03] cũng ngại đấy. Kiểu thế. Thực sự thì ừ
[00:36:08] nó tự làm cho mình trở ngại thôi. Đôi
[00:36:11] khi là bài toàn lớn nhất lại là mình
[00:36:14] không vượt qua được cái bóng. Dùng từ
[00:36:16] cái bóng cũng đúng. Mình chưa là cái gì
[00:36:18] để tạo ra cái bóng cả. Mình không vượt
[00:36:21] qua được cái trở ngại lớn nhất là cái tư
[00:36:23] duy của mình, cái giếng của mình. Mình
[00:36:27] nói thế không phải là công kích bất kỳ
[00:36:29] ai dạ chúng ta nhưng mà ai chúng ta sẽ
[00:36:32] có một cái giếng riêng đúng không ạ?
[00:36:35] Tùy cái giếng của người nào to thế nào.
[00:36:37] Đấy,
[00:36:46] lý thuyết xong tưởng tượng ra áp dụng nó
[00:36:49] vô nhà mình thế nào, tính tiền thu nhập
[00:36:51] gia đình, chi tiêu thứ các thứ để lên
[00:36:53] sâu cũng không ngay. Đúng nghĩa là hồi
[00:36:55] trước là mình làm mấy cái dự án P
[00:36:58] project cá nhân thì cũng thường ấy thên
[00:36:59] hướng là mình nghĩ xem là mọi thứ xung
[00:37:01] quanh có thể dự công nghệ thông tin mọi
[00:37:03] thứ như nào nhưng mà đấy là nói về việc
[00:37:05] là mình là người tham học và chủ động
[00:37:09] nhưng nó phải đi kèm với xung quanh có
[00:37:13] tạo nên môi trường cho mình được như thế
[00:37:14] không. Ví dụ giả sử bạn muốn học cái
[00:37:16] ngin ví dụ nhá mình như mình vừa nói
[00:37:20] luôn là năm vừa rồi mình nhớ là có một
[00:37:23] tỉnh mà cả tỉnh đấy có một bạn thiin học
[00:37:27] thôi. Nghĩa là chỉ là toàn bộ mọi thứ
[00:37:31] môi trường xung quanh đâu có ủng hộ đâu
[00:37:33] đúng không ạ? Không biết được là có ủng
[00:37:35] hộ bạn ấy hết sức không nhưng mà chắc
[00:37:36] chắn là không hể tạo một cái môi trường
[00:37:38] tốt để bạn ấy học còn không biết được là
[00:37:41] bạn ấy tự học hay là học ở trên trường.
[00:37:44] Ông hình dung không? Nếu mà giả sử học
[00:37:45] trên trường có một thầy dạy cho một trò
[00:37:47] n khó đúng không? Đấy ông ông hiểu tôi
[00:37:51] không? Nghĩa là
[00:37:53] cái tuy là mình đang thay đổi dần nhưng
[00:37:56] mà nó vẫn chỉ là thay đổi dần thôi. Và
[00:37:58] bây giờ mình về đấy ừ có thể tôi sẽ tin
[00:38:01] phong. Tôi sẽ đến gõ cửa từng nhà để mà
[00:38:03] kiểu thay vì kiểu hồi trước là kiểu các
[00:38:06] thầy đến gõ cửa từng nhà giống kiểu cứ
[00:38:08] nói trên vùng núi đi là kiểu để mà xin
[00:38:11] con đi học chữ đúng không? sinh con đi
[00:38:13] học IT sinh con đi học kiểu gõ gõ máy
[00:38:17] kiểu thế mà thực ra là ngành dậy này
[00:38:21] cũng khó nữa vì các bạn thấy là ngành
[00:38:23] công nghệ tin này bây giờ bị bão hòa phả
[00:38:25] dùng từ bão hòa tức là nó không còn hot,
[00:38:28] nó không còn nổi, nó không còn kiểu săn
[00:38:31] đón à nhân viên nữa. Bây giờ Sa Hải cũng
[00:38:34] nhiều rồi vân vân vân vân tỉ lệ thất
[00:38:36] nghiệp cũng cao đấy. Thế nên là không
[00:38:39] đảm bảo một cái đầu ra để mà mình háo
[00:38:42] hứng cái việc là em cứ học đi kiểu gì sẽ
[00:38:45] có việc làm hay mọi thứ đúng không? Hồi
[00:38:48] trước thì mình còn nói là ngành công em
[00:38:51] tin này là chỉ cần giỏi là sẽ được tuyển
[00:38:53] không cần phải có người quen, không cần
[00:38:55] phải đi chạy chọt đúng không? Còn bây
[00:38:57] giờ thì chưa chắc nhá. Giờ nó khó hơn
[00:39:00] nhiều rồi. Đôi khi có người quen là một
[00:39:02] lợi thế. Lợi thế ở đây không phải lợi
[00:39:04] thế là người quen giới thiệu vào đâu
[00:39:05] nhá. Ngoài lợi thế này người quen ở
[00:39:07] trong công ty biết được công ty có tuyển
[00:39:09] hay là công ty đấy cái thằng này nó sắp
[00:39:11] bị đuổi vân vân mách cho mình chứ bây
[00:39:15] giờ ông lên mấy cái à trang tuyển dụng
[00:39:18] ấy không đăng mấy đâu và đăng theo kiểu
[00:39:21] là ông sẽ bị vào cái danh sách hàng chờ
[00:39:24] hạn danh sách kiểu người ta sẽ không
[00:39:28] người ta lọc ấy. Đấy ông sẽ có thể CV
[00:39:32] ông đủ tốt à không đủ tốt nhưng mà trình
[00:39:35] độ ông đủ tốt nhưng mà người ta lướt mất
[00:39:37] là mất đúng không ạ?
[00:39:41] Ôi tàn mạn hơi dài lại quay lại không
[00:39:44] ngồi tản mạn tiếng mất. Ok
[00:39:49] tống quát
[00:39:51] cái hay này kiểu tạo mảng nó cách ngắn
[00:39:53] hơn của cái này đúng không? Hai cái chắc
[00:39:55] là một nhỉ?
[00:39:56] Ừ
[00:39:59] ừ tôi nghĩ hai cái là một nhưng mà array
[00:40:01] list khác với chắc là phải khác với
[00:40:03] array nhỉ đúng không?
[00:40:05] array list PS array tôi cứ note cứ đánh
[00:40:10] dấu lại đã
[00:40:21] có hàm print array à hay là nó mình ghi
[00:40:24] ở dưới đây đây lừa
[00:40:28] tỉnh lắm
[00:40:41] print list. Chắc chắn là quả này tôi tin
[00:40:44] là quả lửa. Không có một cái hàm kiểu
[00:40:47] kiểu như này đúng không ạ?
[00:41:00] nhận number và
[00:41:18] Chỉ chấp nhận number và các class con. Ừ
[00:41:21] đúng kiểu cái này số th số. Ok. Cái này
[00:41:25] tôi hiểu
[00:41:28] cái này à cái này generic chung chứ nó
[00:41:31] không liên quan đến array nhở. Nó không
[00:41:33] nhắc về array nữa. Ok. Cái này thì dễ
[00:41:35] hiểu mà không sao. Đại diện kiểu không
[00:41:38] xác định
[00:41:53] cái này là hỏi chấm là chấp nhận list
[00:41:57] của bất kỳ kiểu nào. Ồ chỉ đọc được
[00:42:00] không thêm được phần tử mới. Ok
[00:42:04] dùng cái hàm for này đúng không? For này
[00:42:07] giống kiểu for x của bên
[00:42:10] PP. Thì cái này dùng
[00:42:14] đợi tí có điện thoại của anh.
[00:42:23] đây khai báo kiểu hay phết. Biết cẩn
[00:42:25] thnh trông rõ ràng, dễ hiểu thật kiểu gì
[00:42:30] nó kiểu ý tôi dễ hiểu ở đây là ngoài
[00:42:33] việc code dễ hiểu ra là cái a cái phần
[00:42:36] mềm gõ code ấy nó cũng sẽ dễ hiểu để mà
[00:42:39] gợi ý ra là cái này đang báo lộ sai gì
[00:42:41] đó kiểu dữ liệu mà đúng không? Nó tường
[00:42:44] minh ấy.
[00:42:46] Mấy không biết từ tường minh không? Tôi
[00:42:48] thấy từng minh từng minh là một từ rất
[00:42:50] là hay để nó thể hiện việc nó rõ ràng nó
[00:42:52] kiểu nó xy kiểu minh bạch hay kiểu thế.
[00:42:57] Cái từ tiếng tiếng Anh của nó thì nó sẽ
[00:42:59] dễ hơn nó là transparent à
[00:43:02] ờ tôi nhớ transparent gì đó kiểu trong
[00:43:05] suốt à minh bạch rõ ràng cái thứ thừ
[00:43:07] tương minh
[00:43:10] từ minh là hình như là từ đấy từ Hán
[00:43:12] Việt thì phải.
[00:43:14] Ờ chấp nhận list của bất kỳ kiểu nào
[00:43:17] xong rồi mình sẽ kiểu đây sẽ không khai
[00:43:20] báo kiểu T nữa. Khai báo kiểu nó object.
[00:43:23] Ok.
[00:43:47] này qua rồi. Bing nếu mà bình thường mà
[00:43:50] chứa bờ bãi chỉ chứa string đúng
[00:43:54] ship có đúng script luôn này. Rồi so
[00:43:58] sánh với cả JavaScript nhá. Ok cũng xị
[00:44:08] nào. Lưu ý quan trọng.
[00:44:11] Complier sẽ xóa tất cả thông tin generic
[00:44:13] sau khi compl
[00:44:22] học thì thầy báo anh live anh học tốt
[00:44:25] nhé anh tắm cái cũng vào việc. Ok em lúc
[00:44:29] mà em tắm xong chắc là anh cũng off có
[00:44:31] thể thế để xem tôi sẽ học thêm ngày sau
[00:44:34] nữa. Tôi không bùng đâu mấy không yên
[00:44:36] tâm.
[00:44:38] Ờ
[00:44:40] complier xóa thông tin này thành avelist
[00:44:43] trong buy code. Ơ đây ông vừa nói này
[00:44:47] đúng không
[00:44:49] hả? Ông vừa tắm vừa xem tôi á nó hơi bị
[00:44:52] kiểu
[00:44:54] không được sạch sẽ lắm à. Đâu không nó
[00:44:57] sạch sẽ không nhỉ? không được cho thoải
[00:44:59] mái đi. Đấy kiểu thế lúc tắm là lúc mà
[00:45:02] tôi đúng lúc tắm tôi có thỉnh thoảng hồi
[00:45:04] trước là hồi trước nhá cái này lại hơi
[00:45:07] đi xa một tí hô trước là tôi
[00:45:10] à
[00:45:12] hồi mà đi dậy đặc biệt là hồi đấy còn à
[00:45:15] nhận dậy kiểu
[00:45:22] nhận dậy lại xong rồi có thư tôi ngày
[00:45:24] nào tôi cũng ngồi nghe mở một loạt video
[00:45:28] của các thầy dạy các thứ thứ
[00:45:31] Tắm cũng ngồi nghe à ăn cũng ngồi nghe
[00:45:36] để mà xem các d thầy dạy mọi thứ như thế
[00:45:39] nào để mà tham khảo về cách dạy cũng như
[00:45:42] là kiến thức các thứ để xem là kiến thức
[00:45:45] thầy chia sẻ nó dễ hiểu hay khó hiểu,
[00:45:48] chỗ nào mình xúc nghiệm này cũng như là
[00:45:50] cái gì hay thì mình học hỏi này các thứ
[00:45:52] thứ đấy
[00:45:55] nghe nghe các bạn nghe có thể tưởng nghĩ
[00:45:58] là đấy thời đầu tôi đi dạy Không, ngay
[00:46:00] gần đây luôn, ngay năm ngoái luôn tôi đi
[00:46:02] dạy tôi cũng như thế luôn. Đấy, thì ông
[00:46:04] sẽ biết được là à năm ngoái đúng không
[00:46:07] nhỉ? Ừ, sang năm rồi phải năm kia chứ.
[00:46:09] Ừ. Nghĩa là à thôi năm ngoái cũng có.
[00:46:12] Hồi mà tôi dạy tin ở cho cho bên tuyển
[00:46:16] sinh 247 cũng có. Nghĩa là lúc mà tôi đi
[00:46:18] dậy là lúc mà tôi trau dồi lại kiến
[00:46:20] thức.
[00:46:23] Tôi a tôi trau dồi mọi lúc luôn. Bởi vì
[00:46:26] lúc tắm là lúc mà mình đang cũng đang
[00:46:28] thoải mái mà đúng không? Đấy nên là mình
[00:46:31] cũng
[00:46:32] vào đầu được. Thực ra là vào đầu được ở
[00:46:35] đây không phải vào đầu được toàn bộ kiến
[00:46:37] thức đâu. Vì chuẩn là mình vẫn nên có gì
[00:46:39] đó nhìn vào mình bởi vì đôi khi có cái
[00:46:42] gì minh họa vân vân vân. Nhưng ý tôi là
[00:46:45] chủ yếu là tôi nghe vẫn thiên về việc và
[00:46:48] người cách người ta nói chuyện và cách
[00:46:51] người ta dạy hơn là về kiến thức của
[00:46:54] người ta dạy thật. Trừ khi kiến thức
[00:46:56] người ta chia sẻ hay quá lúc đấy nó
[00:46:58] khác. Hồi trước là tôi nhớ là đặc biệt
[00:47:01] là cái thời đầu tôi mới nghe tôi muốn
[00:47:03] dạy về AI ấy thì thời đầu tôi nghe
[00:47:07] bởi vì tôi đi làm tôi động AI đâu đúng
[00:47:09] không? Nên tôi càm phải cùng cố kiến
[00:47:10] thức vii để tôi còn dạy một tí gọi là
[00:47:14] dạy tí qua môn tin học lớp 12 AI là gì
[00:47:17] thôi. Đấy thì tôi nghe bên ach kênh là
[00:47:21] kênh a cú thông thái à
[00:47:25] cú thông thái thì phải. Cha phát
[00:47:30] YouTube
[00:47:32] ây ái ây ai cú thông ai chung tình được
[00:47:36] mãi
[00:47:42] video này luôn này đây rất hay rất hay
[00:47:46] cho dù về sau thì có một tí thiên hướng
[00:47:49] ông đấy là kiểu vẫn có tí không không
[00:47:51] nói lùa gà gì cả nhá ông đấy vẫn có tí
[00:47:53] là kêu gọi mọi người vào chơi tiền ảo
[00:47:57] hay mọi thứ hay đầu tư chứng khoán hay
[00:47:59] gì gì đó, thậm chí đầu tư vào kiểu đầu
[00:48:02] tư hay mọi thứ gì đó thì
[00:48:05] tôi không khuyên anh em tham gia với cái
[00:48:07] đấy. Tôi không thể khuyên được. Tôi
[00:48:09] khuyên khác gì bảo tôi lùa cùng. Nhưng
[00:48:11] mà đấy thì còn nghe người ta nói rất hay
[00:48:14] thật
[00:48:25] chơi suông thì chán cần có gì nghe. Ok.
[00:48:28] Xong rồi lại giống tôi hồi trước nghĩ ra
[00:48:32] tao vừa chơi game tao vừa làm thêm một
[00:48:34] cái gì đó cảm thấy có ích nữa. Suy ra
[00:48:36] trung quy tao vẫn kiểu làm gì có xí chứ
[00:48:38] không phải là chỉ chơi game lãng phí
[00:48:40] thời gian cũng rất là hay.
[00:48:44] Giờ tắm anh nghe gì thế hả? Tắm à? Anh
[00:48:47] sẽ nghe nhạc.
[00:48:49] Nghe nhạc của anh thì nhảy đủ thể loại
[00:48:51] hôm trước nghe vừa tắm vừa nghe.
[00:48:56] Không biết mấy ông thế nào nhưng mà tôi
[00:48:57] kiểu thỉnh thoảng nghe nhạc không lời
[00:48:59] thoải mái được. Kiểu mọi giờ cũng được
[00:49:01] ấy. Nghĩa là trong làm việc vẫn nghe
[00:49:03] nhạc không lời được. Trong mốc tắm vẫn
[00:49:05] nghe nhạc không đời được, lúc ngủ cũng
[00:49:07] nghe nhạc không lời được. Nghĩa là nó
[00:49:09] không khiến cho mình buồn ngủ trừ khi
[00:49:11] mình thực sự muốn. Đấy kiểu thế. Nhưng
[00:49:13] nhiều người nghe nhạc không lời họ sẽ
[00:49:16] bảo rất buồn ngủ. Đấy kiểu thế.
[00:49:19] Em vừa tắm vừa nghe. OP đợt em xem của
[00:49:23] anh học lập trình cùng nam. Hình như
[00:49:25] mình biết anh đấy hoặc là anh tương tự
[00:49:29] phải có anh anh cũng a anh đấy là anh a
[00:49:34] nam dạy lập trình về dnet đúng không?
[00:49:39] Nam lập trình
[00:49:49] hướng dạy về lập trình mà. Đây đây đúng
[00:49:51] đúng đúng rồi lập trình cùng nam đúng
[00:49:52] rồi tôi cũng có theo dõi nhưng tôi chưa
[00:49:55] xem mấy đâu. Kiểu lưu lưu nhiều nhưng mà
[00:49:58] kiểu à đúng rồi mình học Java hình như
[00:50:01] anh này cũng có dạy phải chứ nhớ mang
[00:50:03] màng thế dạy về can code thì chắc là có
[00:50:08] đây lập trình hướng đối tượng này không
[00:50:10] biết có
[00:50:12] không biết có Java hay anh ấy dạy cho
[00:50:14] lại dnet
[00:50:20] khóa này mình lại cùng nhau học cái đấy
[00:50:21] à nhưng mà tôi không mở cho mấy ông xem
[00:50:23] được nhiều lúc tôi nghĩ là tôi muốn mở
[00:50:26] mở một cái video nào đó cùng mấy ông xem
[00:50:28] nhưng mà cứ sợ dính bản quyền hay gì đó
[00:50:31] nên là hơi hơi khó không ạ? Kể cả dù
[00:50:35] người ta không đánh gậy mình nhá nhưng
[00:50:37] biết đâu đấy nên là thôi cay thật giờ g
[00:50:41] muốn xem thậm chí là đôi khi là tôi muốn
[00:50:44] xem phim cùng mấy ông à kiểu chúng ta
[00:50:45] ngồi xem phim cùng bàn luận cùng nhau
[00:50:47] vui vui
[00:50:49] quay lại học anh ngâu tám ít thôi
[00:50:53] cái này để mà giao lưu chủ yếu mà
[00:50:56] không thể tạo gen array
[00:51:08] nữa. Chắc là cái này tôi đọc cho biết
[00:51:11] thôi chứ về sau không thể nhớ được.
[00:51:18] trước tôi còn nghe cái quả em tôi so
[00:51:21] sánh kiểu Java 8 với Java 23 hay gì rồi.
[00:51:24] Ui tôi nghĩ là tôi chưa lên được cái tầm
[00:51:27] phải có nhớ được từng phiên bản ra hay
[00:51:30] mọi thứ r nó khác biệt nhau nào. Tôi
[00:51:32] dùng PP đủ lâu từ thời 5.6 đến bây giờ.
[00:51:36] Tôi cũng phải hơi choáng về cái quả mà
[00:51:40] kiểu có nhiều cái đến bây giờ có những
[00:51:42] cái mới ra bây giờ mình cũng chưa dùng
[00:51:44] ấy. Đấy nhưng ít ra tôi biết được lịch
[00:51:46] sử của nó. Chứ giờ vả tôi ngồi học thêm
[00:51:48] lịch sử Java mà Java còn dày hơn chịu
[00:52:02] là cái elite này nó chỉ chứa object nó
[00:52:05] là class object chứ không nên chứa kiểu
[00:52:07] nguyên thủy là kiểu kiểu như này được
[00:52:09] đúng không ạ? Nghĩa là bồ lại thì cái
[00:52:11] này sẽ có nun được đúng không? Hay có
[00:52:14] một array toàn nun được không? Kiểu in
[00:52:16] nhưng mà toàn nun được đúng không? Tôi
[00:52:19] nghĩ là được.
[00:52:28] rồi tôi không để ý quả extend này. Đấy.
[00:52:38] biết à hàm xăm này vừa rồi tự viết à tôi
[00:52:41] cứ tưởng là có một cái hàm riêng tên là
[00:52:43] xăm cơ. Lỗi tôi
[00:52:46] hỏi chấm này không nói này nhưng mà tend
[00:52:49] này khai báo
[00:52:52] phải là một là number. Number ở đây sẽ
[00:52:55] có cả integer hoặc là flat đúng không?
[00:53:07] super.
[00:53:12] cái này mấy ông có dùng thường xuyên
[00:53:15] không vậy? Nhìn cái này rõ ràng là
[00:53:19] rõ ràng là nó kiểu nó có chặt chẽ nhưng
[00:53:23] mà nó lại hơi lỏng nhở. Nó nó lá giống
[00:53:26] như kiểu ở trong a PP nó sẽ khái niệm là
[00:53:29] tha như mà tha mic ấy đúng không? Mấy
[00:53:32] không biết không?
[00:53:34] này kiểu có có thể nhiều cái kiểu một
[00:53:36] lúc ấy. Cái này không hẳn đến mức độ đấy
[00:53:39] nhưng mà nó sẽ là không một cái hai cụ
[00:53:42] thể nữa. Nó sẽ kết thừa hay gì gì đó.
[00:53:46] Ừ cái này nó sẽ vẫn có tí thiên hướng về
[00:53:48] các class nhỉ. Uầy thế này tôi vừa nãy
[00:53:51] tôi đang nói là nó tường minh theo kiểu
[00:53:54] tường minh theo kiểu là IDE có thể g ý
[00:53:58] các thứ thứ thứ đúng không? Ngồi đập
[00:54:01] đúng này xong tôi không nghĩ là nào gợi
[00:54:04] ý nổi. Trừ khi là à không chắc là chuyên
[00:54:09] về Java giống như là mấy ông bảo tôi
[00:54:11] dùng cái gì nhỉ? Cái pin Java nào nhỉ?
[00:54:13] Quên mất rồi. Thì mấy cái con đấy chuyên
[00:54:16] nó có compiler chạy các thứ thứ thì chắc
[00:54:19] là nó vẫn sẽ gợi ý được thôi. Đấy nhưng
[00:54:21] mà
[00:54:28] chắc là phải làm mới nhớ được. À không
[00:54:34] làm chưa chắc nhớ. Phải dùng từ như nào
[00:54:36] nhỉ?
[00:54:38] Chẳng biết như nào vào dự án thực tế.
[00:54:46] điều
[00:54:48] kiểu đặt ra dấu vào chấm list này tôi
[00:54:51] vừa rồi tôi hiểu rồi nên tôi xóa đi. Ok.
[00:54:54] Đấy nghĩa là lúc đầu mình có thể thắc
[00:54:55] mắc nhưng mà đến cuối mình hiểu được thì
[00:54:57] chứng tỏ mình hiểu được bài đúng không
[00:54:58] ạ? Đấy hôm trước à hôm qua tôi nói
[00:55:01] chuyện nhiều quá rồi thành ra là chưa
[00:55:04] kịp học gì đ không ạ. Hôm nay tôi sẽ học
[00:55:06] bù cả ngày thứ năm ngày thứ sáu đấy.
[00:55:10] Được không ạ?
[00:55:12] phải nói được không ạ? Nhưng mà thực ra
[00:55:13] là được hay không thì tôi vẫn là người
[00:55:16] quyết định mà.
[00:55:33] không không cần các mốc các thứ mình
[00:55:35] không học phải các mốc lỗi run time ơ
[00:55:39] trong này còn không có
[00:55:45] là nhầm cái
[00:55:47] Đúng rồi mà
[00:55:49] trước Java
[00:56:01] lệch ấy đúng không?
[00:56:10] có Z với sve nhỉ?
[00:56:17] bịa ra đấy.
[00:56:29] linh hoạt hai safety cũng được.
[00:56:38] đây.
[00:56:52] ảnh đầu luôn thì phải.
[00:57:10] biết LSP nói viết tắt của gì đâu nhá.
[00:57:13] Thì thằng con kế thừa thằng cha thì
[00:57:15] thằng con cũng phải được như thằng cha.
[00:57:19] Câu này bữa phỏng vấn nó phê xíu.
[00:57:27] những cái thằng cha làm việc gì thằng
[00:57:30] con nó cũng sẽ phải làm được và hơn thế.
[00:57:33] Đấy, tôi nhớ là như thế. Nó là kiểu
[00:57:34] extend là cái thư cái thế
[00:57:37] hơn thế được không đúng lắm nhưng mà nó
[00:57:39] chỉ nó có thể custom được ấy. Nhưng mà
[00:57:40] gần như là thằng cha làm được gì, thằng
[00:57:42] con cũng phải làm được. Đấy.
[00:58:10] ngày thứ sáu đúng không ạ?
[00:58:17] ta đã đến interface. Xin chúc mừng ạ.
[00:58:19] Check class. Tôi
[00:58:23] tôi nghĩ sau buổi thứ sáu này được. Tôi
[00:58:25] nghĩ là tôi sẽ
[00:58:29] à cứ cho là gần cái cái mục này quan
[00:58:33] trọng đi. Tôi sẽ
[00:58:36] bảo AI tạo ra một bài
[00:58:42] một một loạt các bài phỏng vấn
[00:58:47] tầm
[00:58:48] 20 câu hỏi đi. 20 câu hỏi về hôm trước
[00:58:53] tôi có nói mấy ông. Mấy ông nhớ chứ?
[00:58:55] Chắc mấy ông có thể mấy ông chưa xem cái
[00:58:57] video hôm trước. 20 câu hỏi. Ừ 20 câu
[00:59:01] hỏi đi. Chúng ta ngồi chơi ca hút
[00:59:04] được không ạ?
[00:59:07] Ừ. Nhưng mà ca hút không ổn nhỉ? Tôi
[00:59:09] biết đáp án à? Cũng không? Tôi bảo ai
[00:59:12] soạn và làm sao cho để ừ tôi dùng thằng
[00:59:15] tôi bảo ai soạn rồi bảo ông em tôi hoặc
[00:59:18] là bảo bạn bạn tôi ngồi nói chung ngồi
[00:59:21] soạn câu hỏi rồi anh em mình sẽ ngồi
[00:59:23] chơi cao hút với nhau được chứ. Đây mình
[00:59:27] sẽ ngồi chơi cao hút với nhau để
[00:59:29] trả lời mấy cái đống từ buổi thứ một cho
[00:59:33] đến buổi thứ sáu này.
[00:59:36] 20 thật ra còn ít đấy. Buổi sáu buổi mà
[00:59:39] đúng không? Mỗi buổi ba câu. Ừ thật ra
[00:59:42] thế không ít lắm nhỉ? Ừ mày không hiểu
[00:59:45] chứ. Nhưng cái riêng interface abcheck
[00:59:47] class này tôi nghĩ là sẽ phải hỏi nhiều
[00:59:50] nhất
[00:59:52] nhá. Mấy ông biết ca hút rồi đúng không
[00:59:54] ạ? Đấy chúng ta sẽ ngồi chơi nhá. Thắng
[00:59:56] có qua không?
[00:59:57] Anh anh đang định nhờ em bảo ngồi em
[01:00:00] soạn câu hỏi mà em định chơi cùng à?
[01:00:05] Đấy,
[01:00:12] à. Nhưng mà nếu mà em hỏi thằng có quà
[01:00:14] không cho người khác thì ok.
[01:00:16] À tôi cho là
[01:00:21] quà bây giờ nên là gì nhỉ?
[01:00:23] Nếu mà tốt cho anh em thì sẽ là như nào
[01:00:26] nhỉ? Ừ, chẳng lẽ em bảo một tháng dùng
[01:00:30] ai gì đó kiểu
[01:00:32] có chứ. Có qua cho anh em thắng chắc nó
[01:00:35] s nhỉ. Ờ nhưng mà không không biết mấy
[01:00:39] ông em chắc mấy chắc anh em ở đây đều
[01:00:41] xanh chín thôi. Chắc không anh em nào
[01:00:43] hack khủng chơi bẩn đâu. Vì tôi nhớ
[01:00:44] trước ca hood có cái vụ là có thể hack
[01:00:46] được. Chắ bây giờ nó cũng fix rồi. Ờ qua
[01:00:50] chắc là bạn top ba người thì sẽ
[01:00:55] thực ra top 3 thì cả ba người đều như
[01:00:57] nhau cho dễ nhá.
[01:00:58] được 1 tháng dùng AI đi.
[01:01:02] AI bây giờ sẽ
[01:01:05] AI bây giờ đắt nhất thì con nào nhỉ?
[01:01:08] Thường là AI toàn là
[01:01:16] như nào?
[01:01:18] Cái key cáp hôm trước á? Không káp thôi.
[01:01:22] Ừ
[01:01:24] anh em kiểu gì bây giờ vai code dùng ai
[01:01:26] mà bây giờ đầu tư cho anh em một tháng
[01:01:29] kiểu 10 đô. 10 đô là tầm hơn 200 hoặc là
[01:01:35] 15 đô tầm đấy. Ai bây giờ toàn 10 15 đô
[01:01:38] thôi mà đúng không? Đấy, tầm đây để anh
[01:01:41] em dùng AI chúng ta sẽ ngồi vai code
[01:01:46] với nhau cũng một kiểu. Thế là tôi chưa
[01:01:48] nghĩ cái giải thưởng đâu. Tôi tôi sẽ tạo
[01:01:52] một cái à một cái thở ở trên a
[01:01:57] à gọi là th đi giống voer một cái thớt ở
[01:02:00] trên Discord server Discord để anh em có
[01:02:03] gì cùng thảo luận nhá. để xem là nên có
[01:02:06] giải mọi thứ như nào và nên có thời gian
[01:02:08] nữa để thông báo thời gian anh em để anh
[01:02:10] em cùng chuẩn bị. Đấy chúng ta mục tiêu
[01:02:13] của tôi đó là cũng phải tầm ít nhất ít
[01:02:15] nhất là cũng tầm 20 người tham gia cao
[01:02:17] hút cho nó sâ tự nhiên có năm người chơi
[01:02:20] thì ba người thắng thì trông nó hơi bị
[01:02:21] buồn cười đúng không ạ
[01:02:24] nhỉ? Mà không thấy hợp lý đúng không?
[01:02:27] Không phản đối tức là đồng ý nhá. Ok
[01:02:35] lại cái mấy cái này đăng lên server cho
[01:02:38] mấy ông là bây giờ mấy ông còn đang chưa
[01:02:40] xem hoặc là xem lại sau đúng không?
[01:02:49] tiếng ma đi dậy xong rồi 20 câu mình trả
[01:02:51] lời được. Chưa đến năm câu thì chắc là
[01:02:52] mình cũng xấu hổ lắm.
[01:02:55] N không sao chơi quan trọng là chơi cùng
[01:02:58] anh em cho vui vì rõ ràng là đấy đấy là
[01:03:01] một cách để kết nối thôi vì rõ ràng anh
[01:03:02] em ở đây có nhiều người không ở Hà Nội
[01:03:05] tôi cũng chưa gặp bao giờ các thứ thứ
[01:03:07] đây một cách để chúng ta sẽ có cơ hội để
[01:03:09] mà một cách kết nối một cách giao lưu gì
[01:03:12] đó không trực tiếp
[01:03:21] xếp tôi thường anh đặt interface tên là
[01:03:23] contract thì gì đó.
[01:03:26] Và object class
[01:03:29] base template. Uầy, đọc thế này dễ hiểu
[01:03:32] hơn hẳn luôn ý. Ồ, đấy mấy ông đọc cái
[01:03:36] kiểu như này một phát hiểu ngay chăng.
[01:03:39] Không biết là mấy ông có hiểu cái này
[01:03:42] không? Tôi hiểu đấy. Kiểu hiểu nó kiểu
[01:03:44] rằng buộc thôi. Nó kiểu rằng kiểu phải
[01:03:47] cần có những cái gì thôi. Còn B template
[01:03:49] thì đấy nó là cái kiểu cái gốc là gì.
[01:03:52] Thì xong rồi mình sẽ kéo như nào đấy.
[01:03:54] Bọn tôi thường hay đặt tên kiểu như này
[01:03:56] cơ t vẫn dùng cái này nhên vẫn dùng rồi
[01:03:58] nhưng mà đặt tên kiểu này.
[01:04:01] Đa hình đa hình này xong rồi đa gì nữa
[01:04:06] tôi quên mất rồi. Tí xem
[01:04:09] object class
[01:04:36] bắt buộc phải dùng element. Đúng rồi.
[01:04:39] Kiểu khai bái kiểu như này là khi mà
[01:04:41] khai báo check là bắt buộc phải khai báo
[01:04:44] cái method đấy đúng không? Mic sao? Húp
[01:04:47] húp meo meo spit.
[01:04:56] cả C hay là dog slip chắc giống nhau
[01:04:59] đúng không? Interface behavior là có
[01:05:03] những cái a thói quen một cái thuốc tính
[01:05:06] riêng.
[01:05:12] mặt. Nó chư quan tâm thứ này có thể trả
[01:05:13] tiền. Payment method đúng
[01:05:16] đúng bâ tôi gọi một khái niệm payment
[01:05:18] method pay này pay này interface cùng
[01:05:21] chung một cái những cái chung contract
[01:05:24] cam kết sẽ làm được việc này đấy mọi
[01:05:27] field bắt buộc mặc định là public static
[01:05:31] final
[01:05:33] là nó là kiểu chỉ được kiểu
[01:05:38] mình phải khai báo kiểu còng overrive
[01:05:41] này đúng không khái niệm override ghi đè
[01:05:42] các thứ này đúng
[01:05:56] có bắt buộc không?
[01:06:00] Chắc là bây giờ giờ này mấy ông đang
[01:06:02] ngồi ăn mết rồi hoặc đang đi chơi. Bây
[01:06:04] giờ đến giờ đi chơi mà đúng không? 8:00
[01:06:07] 8 gi bắt đầu lên đồ lên 3. Đấy hôm trước
[01:06:09] tôi thường mới nói như thế
[01:06:12] đấy.
[01:06:15] Mọi mặc định là public attract. Ừ.
[01:06:34] Xong rồi.
[01:06:37] À cái field này đây đúng không? Fở trong
[01:06:39] trường hợp này nó là attribute à đúng
[01:06:42] không?
[01:06:53] Public order này.
[01:07:01] được nhỉ? Tôi chưa hiểu cái này. À nó
[01:07:03] contractor à
[01:07:07] ồ cách contractor trong này nó khác với
[01:07:10] trong VP khá là rõ. Không biết được là
[01:07:14] tí nếu mà convert sang bên Java thì sẽ
[01:07:18] Ừ tôi tôi biết final là không thể thay
[01:07:20] đổi được rồi.
[01:07:22] Ơ nhưng mà nếu thế sẽ
[01:07:37] trường hợp này nó chính là cái này rồi
[01:07:38] đúng không? F chính attribute rồi. Đối
[01:07:41] với tôi hiểu cái này là attribute
[01:07:45] không thể thay đổi đúng không ạ?
[01:07:47] À
[01:07:55] cái gì gì đó này
[01:07:58] sẽ notốe lại đây.
[01:08:13] số nữa.
[01:08:23] lắm. Chắc là phải làm mới hiểu
[01:08:27] đâu. Đầu tiên thanh toán 100 này. Thanh
[01:08:31] toán theo dùng cái nào? Up check khi
[01:08:33] quan hệ cha con chặt chẽ. khi class
[01:08:36] không liên quan nhưng có chung hành
[01:08:38] động. Ừm, cái này hợp lý hơn này.
[01:08:50] Tuy là nó dễ hiểu. Cái này tôi từng
[01:08:52] biết, tôi học hồi Java rồi nhưng mà với
[01:08:54] tôi thế này là chưa đủ để mà rõ hơn. Tôi
[01:08:57] sẽ
[01:09:00] tôi sẽ yêu cầu
[01:09:02] thêm AI bắt nó làm chặt hơn cái này.
[01:09:06] Ờ
[01:09:08] cho tôi
[01:09:10] thêm
[01:09:12] ví dụ chặt chẽ
[01:09:16] hơn để hiểu make practice
[01:09:20] khi nào dùng
[01:09:23] contract
[01:09:25] khi nào dùng
[01:09:28] interface
[01:09:35] và trả lời cho tôi
[01:09:44] đấy.
[01:09:52] thì mình sẽ bắt phải kỹ hơn đúng không
[01:09:57] ạ? Thế cái này thực ra là tôi biết cái
[01:09:59] này tôi biết mà cái cái mấy cái này tôi
[01:10:02] thường hợp Java tôi biết rồi cái
[01:10:03] interface rồi cả thì nó cũng lấy ví dụ
[01:10:05] là chó mèo như này rồi cái order thì
[01:10:09] thấy còn mới thôi.
[01:10:16] example này.
[01:10:48] dùng khi class quan hệ cho con chia sẻ
[01:10:51] code chung full time employee. Đây là
[01:10:54] employee đúng chung các thứ thứ đúng
[01:10:57] không? Còn cái này là có thể làm được
[01:11:00] gì? Dùng cho class không liên quan đến
[01:11:02] nhau nhưng trung hành vi đấy. Behavior
[01:11:04] đúng không? Trung hành vi
[01:11:13] thuế. Ok.
[01:11:16] liên kết lọc
[01:11:18] không liên quan không quan tâm đối tượng
[01:11:20] employee các thứ thứ chỉ quan tâm đối
[01:11:22] tượng có à ok qu
[01:11:32] cái này sẽ phải khai báo một cái tex
[01:11:34] service ở dưới đúng không là một class
[01:11:37] bình thường là đóng thuế
[01:11:39] chấp nhận nạp vào cái gì đó không phụ
[01:11:42] thuộc vào full time emp hay company sau
[01:11:46] này nếu freeland hay robot nộp thuế cái
[01:11:49] này hàm này sẽ không cần sửa đúng viết
[01:11:52] kiểu này nó sẽ kiểu tường minh ấy nó
[01:11:54] kiểu tách tách ra thì rõ ràng là về sau
[01:11:57] code kiểu gì sẽ có mở rộng thêm đúng
[01:12:00] không code càng rõ cái này nó không kiểu
[01:12:05] không phụ thuộc vào cái kia thì mình chỉ
[01:12:06] cần sửa một chỗ những chỗ khác nó vẫn
[01:12:08] chạy được đấy đây châm nghiệm của tôi.
[01:12:13] Tìm hiểu thêm về contter mặc định với
[01:12:16] conter có tham số nữa anh em. Ok. Hay là
[01:12:20] tôi sẽ
[01:12:22] Tôi nghĩ là thỉnh thoảng có mấy ông nói
[01:12:24] như này nhưng mà tôi chưa có chỗ nào để
[01:12:26] ghi. Tôi sẽ tạo một cái file ở đây đi.
[01:12:29] Tôi nghĩ tạo file đây là file à không
[01:12:32] phải tại file đây.
[01:12:34] Đâu rồi?
[01:12:46] ra nó không phải MD đâu. Đó nên là
[01:12:49] text hiểu được là mình sẽ có một câu nào
[01:12:54] đó
[01:13:02] Đấy, thc có mà tôi bấm vào tại vừa rồi
[01:13:04] lười chứ. Đấy bấm vào đây tôi có chỉnh
[01:13:07] rồi mà bấm vào nó nhảy. Tôi tôi vừa rồi
[01:13:11] trong trường hợp vừa rồi tôi muốn xem nó
[01:13:13] nhắc đến ở đ những đâu nữa đấy chứ thực
[01:13:15] ra là tôi tôi có tôi có chỉnh cho VS
[01:13:17] code bấm vào để nhảy đến cụ thể rồi.
[01:13:25] class lắm.
[01:13:26] Chắc là về sau tôi sẽ viết ru ở trong
[01:13:30] này luôn không cho nó tạo class. Tôi
[01:13:31] viết ru thêm một vài cái nữa.
[01:13:42] 12 buổi nên chắc là về sau tôi sẽ xóa
[01:13:44] sau nhá. Về sau cái gì tôi sẽ xóa này.
[01:13:46] Cái này không cần nữa.
[01:13:48] Ơ vừa rồi bay mất cái tôi vừa xóa mất
[01:13:52] cái B practice đúng không?
[01:14:28] này,
[01:14:36] thuế này. Ồ hay phết đa hình này hợp lý
[01:14:39] hợp lý hợp lý. Interface khả năng bất kỳ
[01:14:42] ai cũng phải tính toán nụp thuế đúng
[01:14:44] không? Đấy nhân viên này logic chung gộp
[01:14:48] lại các thứ thứ đây. Khai báo kiểu đối
[01:14:51] tượng các thứ thứ. Ok. Đoạn tôi hiểu.
[01:14:54] Xong rồi implement cái interface. Ok.
[01:14:58] Xong rồi còn phải định nghĩa cách tính
[01:15:01] lương. Mỗi người có thể định nghĩa cách
[01:15:03] tính lương khác nhau. Ồ cái này cũng là
[01:15:05] object class. À đây kết hợp cả hai dùng
[01:15:08] cả object và dùng cả interface đúng
[01:15:10] không? Hay phết. Đấy tiếp theo là thằng
[01:15:12] này kế thừa cái employee vừa rồi này.
[01:15:15] Full time employee. Đấy gọi super. Tôi
[01:15:19] nhớ tôi nhớ cái cái đoạn này rồi. Super
[01:15:21] này là gọi đến thằng tra đúng không? Đấy
[01:15:23] khai báo thằng cha đúng không? Chính là
[01:15:25] cái trường hợp này. Ok.
[01:15:29] Ok. Bắt buộc
[01:15:32] không vintax được khuyên dùng có để
[01:15:34] tránh lỗi. Ok. Ok. Khai báo ra chắc là
[01:15:36] để cho thằng IDE gợi ý ý nó chuẩn đúng
[01:15:39] không? Đấy đấy. Ok là khai báo kiểu trả
[01:15:45] về cái mly các thứ thứ như nào tính
[01:15:47] thuế. cũng ghi đè cái hàm cái hàm thuế
[01:15:51] này từ tch từ interface đấy.
[01:16:04] list new array list là
[01:16:08] một implement nó tương tự set có
[01:16:13] tret đúng không và hasset đúng set thì
[01:16:17] tôi có nghe tret và hasset thử ra chưa
[01:16:19] chưa chưa học đến bên đấy không biết là
[01:16:22] có đề cập không nên tôi cứ tạm nốt lại
[01:16:24] đây nhá tr set và hset
[01:16:30] đâ này nhá. Đấy.
[01:16:42] khai báo nhưng không được dùng ở đâu cả
[01:16:44] đúng không?
[01:16:50] lên này. Cái này kế thừa thẳng cái in
[01:16:53] interface kia luôn không cần kế thừa
[01:16:55] thằng employee nữa đúng không?
[01:17:05] get mari này.
[01:17:08] À bởi vì mình đang chưa có tạo một cái
[01:17:10] thằng nữa. Ví dụ ở thằng tên là P time
[01:17:13] Time
[01:17:15] Employee đúng không? Nếu tạo thêm một
[01:17:18] thằng PH time employee nữa thì get Money
[01:17:21] Sari này có thể chỉ giảm một nửa thôi
[01:17:23] đúng không? Nó hợp lý.
[01:17:30] time. Đ thử tạo nhá.
[01:17:34] Đấy
[01:17:41] như này đi thì nó sẽ dễ hình dung hơn vì
[01:17:43] tự nhiên mất công tạo một thằng full
[01:17:45] time có một hàm trông chỉ trả về
[01:17:49] đúng chính nó thì nó không kiểu không
[01:17:52] điểm gì.
[01:17:53] Theo tôi thì thấy thế thường là phải có
[01:17:55] lý do một cái gì đó đương nhiên là get
[01:17:57] set đôi khi chúng ta trả về thẳng luôn
[01:18:00] đấy như tôi muốn nói lại thêm là có thể
[01:18:03] là mình custom lại nó đúng không? Hợp lý
[01:18:07] mà đúng không?
[01:18:10] Ok, đoạn này dễ hiểu đấy. Rồi. Ờ,
[01:18:14] dựa vào các file vừa thay đổi
[01:18:28] ghi rõ đi bởi vì tôi vừa giờ sửa nhiều
[01:18:31] file
[01:18:33] vừa thay rồi.
[01:18:35] Sửa lại đây
[01:18:44] Sau chúng ta sẽ tạo ra cái file doc.
[01:18:47] Uây, chưa gì mình đã học xong bài thứ
[01:18:50] sáu rồi. Cũng nhanh nhỉ. Nhanh tôi thấy
[01:18:53] là nhanh đấy.
[01:18:56] Interface và object.
[01:20:04] này không không hề nó chỉ là một cái nhỏ
[01:20:08] thôi mình không nên cho nó vào mình thực
[01:20:11] ra mình chỉ quan tâm đến
[01:20:32] can do
[01:20:34] is a này kiểu kiểu so sánh hai bên như
[01:20:37] này hợp lý
[01:20:54] lầm là
[01:20:57] gọi như này
[01:21:00] chỉ được kế thừa kiểu
[01:21:03] chỉ có một parent thôi đúng không? Tất
[01:21:06] cả kiểu ví dụ là kiểu con thì sẽ chỉ có
[01:21:11] mỗi extend một cha thôi đúng không? Đấy
[01:21:15] xong rồi. À đương nhiên cha cũng thể
[01:21:17] extend nữa kiểu ông hay các tự thứ đúng
[01:21:19] không nhở?
[01:21:22] Để tôi hỏi lại
[01:21:25] cái này
[01:21:28] sửa luôn trong đốc à? À thôi cứ hỏi lại
[01:21:31] đây đi.
[01:21:33] À trong Java
[01:21:36] chỉ
[01:21:38] được à class
[01:21:49] một
[01:21:52] tra
[01:21:53] par thôi đúng không?
[01:22:07] thêm
[01:22:09] còn
[01:22:11] interface
[01:22:14] thì
[01:22:15] được nhiều
[01:22:27] không hay nó ngồi sửa code của mình.
[01:22:30] Đúng rồi bạn ơi.
[01:22:39] bây giờ là sẽ là
[01:22:42] đúng rồi ông cháu ơi. Chẳng hạn đấy
[01:22:54] đơn gọi là đơn cái thừa đúng không?
[01:22:58] Th là trong PP thì các cũng thế thôi
[01:23:01] nhưng mà tôi không nhớ về PP về cái vụ
[01:23:04] interface lắm. Tôi chưa vụ tôi thường
[01:23:06] chỉ dùng chỉ cũng gọi là implement
[01:23:11] à đâu có một vài job một vài cái th liên
[01:23:15] quan đến job của thằng Laurel là có cái
[01:23:19] implement nhiều interface rồi không nhớ
[01:23:21] cái đấy lắm như nghĩa là cái đấy là
[01:23:25] class viết sẵn của framework chứ bình
[01:23:28] thường mình viết thì mình sẽ chỉ kế thừa
[01:23:30] mình tạo một interface thôi xong mình kế
[01:23:31] thừa
[01:23:33] à đây Không phải kế thừa nhỉ? Nó dùng từ
[01:23:35] như nào nhỉ?
[01:23:57] hàng phải tự viết nên không sợ nhầm lẫn.
[01:23:59] Cái này à bên này không có chết nhỉ?
[01:24:02] Đúng không? Bên Java
[01:24:13] là một cái hàm thể dùng chung.
[01:24:20] nhật tính default method. Đấy.
[01:24:35] à. Đấy đấy
[01:24:37] đây là Java mấy? Java 8 cộng đôi lên.
[01:24:39] Ok. Thế nó cũng giống nóng tí giống chết
[01:24:44] ở bên PP nhưng mà nó là theo interface
[01:24:52] không truyền biến vào đúng không?
[01:25:22] hoạch cho anh em buổi
[01:25:25] buổi sau hơi quá nhưng mà tôi sẽ lên kế
[01:25:28] hoạch và sẽ báo anh em để chốt một hôm
[01:25:30] mình sẽ ngồi làm thử bài trắc nghiệm ca
[01:25:33] hút. Có thể 20 câu có thể ngắn hơn không
[01:25:36] biết được. Tôi nghĩ là 20 câu tí. Đấy
[01:25:39] anh em sẽ ngồi livestream như thế này và
[01:25:42] trả lời. Đấy hy vọng không bị delay lắm
[01:25:46] đấy.
[01:25:49] Để máy anh có thể anh em có thể xem để
[01:25:52] tránh bị delay tôi cứ tăng mỗi câu 30
[01:25:54] giây chắc cũng thoải mái thôi. Chắc là
[01:25:56] không đến nỗi trả lời nhanh nhanh quá
[01:25:58] đâu. Thích thì tôi sẽ nhắm mắt xin câu
[01:26:01] hỏi rồi nhắm mắt lại đợi hai giây trả
[01:26:03] lời cùng mấy ông công bằng xanh chín đấy
[01:26:08] nhở.
[01:26:10] Đấy thì anh em ngồi trả lời xong rồi top
[01:26:12] 3 thử hình như có ừ top 3 sẽ có cái giải
[01:26:16] thưởng nào đó xong anh em sẽ tự ngồi
[01:26:18] thông nhất nhau giải thưởng là gì nhở
[01:26:21] một cách cái giao lưu kết nối đầu biết
[01:26:24] đâu đầu cầu bên kia đang tận ở c nước
[01:26:27] ngoài hoặc là đang ở ở trong Nam ý nhân
[01:26:31] như thế đấy anh em vẫn có cái có thể
[01:26:34] tương tác với nhau vui nhở.
[01:26:37] Ok thế nhá. Bây giờ tôi đi ăn đã. Mấy
[01:26:39] ông có thể ăn rồi nhưng tôi chưaấy. Xin
[01:26:42] chào mấy ông nhá. Tạm biệt mấy ông. Có
[01:26:44] gì thắc mắc hay nói chuyện thêm thì
[01:26:46] chúng ta vào Discord để nói chuyện nhé.
[01:26:48] Xin chào mấy ông.
