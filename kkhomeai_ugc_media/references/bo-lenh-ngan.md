# Bộ Lệnh Ngắn Đơn Giản Dành Cho Nhóm KKHomeAI Ứng Dụng Tạo Ảnh Với MEDIA AI

© 2026 · KKHome AI - JennyKieu

*Phiên bản tiếng Việt (phần giới thiệu & giải thích); toàn bộ lệnh giữ nguyên tiếng Anh.*

Danh sách các lệnh ngắn (bắt đầu bằng dấu /) dùng trong prompt tạo media AI trên Flow: 10 nhóm cho nội dung affiliate, 17 nhóm bộ công cụ hình ảnh thông dụng, và 3 nhóm camera shot. Gõ lệnh vào prompt theo hiệu ứng hoặc định dạng mong muốn. Riêng **Phần 4** là phần ví dụ ứng dụng thực tế do KKHome AI biên soạn, dành cho làm quảng cáo TikTok / Shopee.

---

## Phần 1 — Affiliate AI: Định Dạng Nội Dung Affiliate Cơ Bản

| Lệnh | Chức năng |
|---|---|
| /ugcproducthook | Mở đầu kiểu creator UGC, kéo sự chú ý vào sản phẩm ngay từ giây đầu tiên. |
| /unboxing | Quy trình: gói hàng đến → mở gói → khoe sản phẩm và chi tiết → kết thúc bằng lời kêu gọi mua hàng. |
| /photoshootad | Hiển thị sản phẩm theo phong cách chụp ảnh quảng cáo studio, gọn gàng và dễ bán. |
| /povproductdemo | Demo sản phẩm từ góc nhìn thứ nhất, như thể người xem đang tự mình sử dụng. |
| /faceless | Nội dung không lộ mặt người nói, để toàn bộ sự chú ý dồn vào sản phẩm. |
| /ugccinematicproduct | Sản phẩm kiểu UGC nhưng có nét điện ảnh, cảm giác cao cấp hơn. |
| /detailproductlook | Cận cảnh chất liệu, kết cấu bề mặt và độ hoàn thiện của sản phẩm. |
| /ugcproduct | Sản phẩm xuất hiện theo phong cách creator UGC, thoải mái và chân thực. |
| /affiliateprofessional | Giao diện affiliate gọn gàng, sạch sẽ và chuyên nghiệp. |
| /nodialog | Video không lời thoại; thuần hình ảnh. |
| /indonesian | Nội dung mang hơi thở Indonesia, kể cả ngôn ngữ sử dụng. |
| /dialog:... | Chỉ định câu thoại được nói; viết câu thoại sau dấu hai chấm. |
| /background:... | Chỉ định phông nền; viết lựa chọn sau dấu hai chấm, ví dụ /background:KarpetShaggyPutih (thảm shaggy trắng). |
| /environment:... | Chỉ định môi trường hoặc địa điểm của cảnh quay; điền theo ý muốn. |

### Combo Sẵn Dùng

Ba combo lệnh cho video affiliate; phù hợp với gamis (trang phục dài kín đáo), outfit, skincare & make-up, túi xách và đồ dùng nhà bếp.

| Combo | Lệnh | Mô tả kết quả |
|---|---|---|
| Combo 1 | /unboxing /ugcproducthook /detailproductlook | Mở gói với hook UGC, kết thúc bằng cận cảnh chi tiết sản phẩm. |
| Combo 2 | /faceless /ugccinematicproduct /detailproductlook | Video không lộ mặt, hơi thở điện ảnh, chi tiết sản phẩm rõ nét. |
| Combo 3 | /photoshootad /faceless /producttest | Sản phẩm được dùng thử mà không lộ mặt, kết thúc bằng giao diện kiểu ảnh quảng cáo. |

### Combo Kèm Background, Dialog & Environment

Điền phần ... theo lựa chọn của riêng bạn; với các cặp "hoặc", hãy chọn một trong hai. Giải thích về lệnh camera có ở Phần 3.

| Combo | Lệnh | Mô tả kết quả |
|---|---|---|
| Combo 4 | /topdownshot /povhandproduct /faceless /detailproductlook /background:... | Tay trình diễn sản phẩm từ góc trên, không lộ mặt, có cận cảnh chi tiết và phông nền theo nội dung bạn điền. |
| Combo 5 | /unboxing /nodialog /detailproductlook | Mở hộp không lời thoại, kết thúc bằng cận cảnh chi tiết sản phẩm. |
| Combo 6 | /nodialog /affiliateprofessional /detailproductlook | Giao diện affiliate chuyên nghiệp, không lời thoại, chi tiết sản phẩm rõ nét. |
| Combo 7 | /unboxing /indonesian /background:KarpetShaggyPutih /dialog:... | Mở hộp phong cách Indonesia trên nền thảm shaggy trắng, kèm lời thoại theo nội dung bạn điền. |
| Combo 8 | /povhandproduct /faceless /topdownshot /detailproductlook /background:... /dialog:... | Giống Combo 4, có thêm lời thoại theo nội dung bạn điền. |
| Combo 9 | /ugcproduct /detailproductlook /environment:... /dialog:... | Sản phẩm phong cách UGC kèm cận cảnh chi tiết, trong môi trường và lời thoại theo nội dung bạn điền. |

### Luồng Kể Chuyện Bán Hàng

Mọi luồng dưới đây đều kết thúc bằng lời kêu gọi mua hàng (CTA).

| Lệnh | Chức năng |
|---|---|
| /hookreview | Hook → giới thiệu sản phẩm → ưu điểm → kêu gọi mua. |
| /problem-solution | Nêu vấn đề trước, sản phẩm xuất hiện như giải pháp, cho thấy kết quả, rồi kêu gọi mua. |
| /beforeafter | Tình trạng ban đầu → sử dụng → kết quả cuối → kêu gọi mua; dùng được cho cả outfit lẫn không gian phòng. |
| /tryon | Tình trạng ban đầu → mặc lên người → hiện hình toàn thân → chi tiết → kêu gọi mua; cũng có thể thử nhiều outfit cùng lúc. |
| /3reasons | Ba lý do sản phẩm đáng để mắt tới, rồi kêu gọi mua. |
| /honestreview | Review thẳng thắn về điểm cộng và điểm trừ, kết thúc bằng kêu gọi mua. |
| /viraltest | Từ "nghe nói tốt" → dùng thử trực tiếp → kết quả → kêu gọi mua. |
| /comparison | So sánh hai sản phẩm, có một sản phẩm thắng, rồi kêu gọi mua. |
| /storyaffiliate | Câu chuyện cá nhân dẫn dắt vào sản phẩm, rồi kêu gọi mua. |
| /softsell | Review theo phong cách bán hàng mềm mại, không tạo cảm giác ép buộc. |

### Fashion: Phong Cách & Styling

| Lệnh | Chức năng |
|---|---|
| /getreadywithme | Chuẩn bị cùng nhau (Get Ready With Me), kèm quá trình mặc outfit. |
| /outfitcheck | Khoe toàn bộ outfit từ đầu đến chân. |
| /ootd | Outfit của ngày (Outfit Of The Day) với dáng pose uyển chuyển, tự nhiên. |
| /mixmatch | Một sản phẩm được phối theo nhiều cách kết hợp khác nhau. |
| /styletips | Gợi ý cách phối đồ và tạo kiểu cho sản phẩm. |
| /fashionreview | Review outfit theo phong cách nói chuyện của creator UGC. |
| /modestootd | OOTD theo phong cách thời trang kín đáo (modest). |
| /transferoutfit | Chuyển outfit từ ảnh tham chiếu sang người mẫu. |
| /tryonoutfit | Người mẫu thử outfit đã được chọn. |

### Fashion: Chất Liệu, Phom Dáng & Chuyển Động Vải

| Lệnh | Chức năng |
|---|---|
| /detailcheck | Kiểm tra chất liệu, đường may và kiểu dáng ở cự ly gần. |
| /bodyfit | Cho thấy sản phẩm ôm và rủ trên cơ thể như thế nào. |
| /gamischeck | Review gamis (trang phục dài) ở góc nhìn toàn thân. |
| /dresscheck | Cho thấy phom cắt và độ rủ của váy đầm. |
| /kaftanflow | Vải kaftan chuyển động khi người mẫu bước đi hoặc xoay người. |
| /dressflow | Người mẫu bước đi với tà váy bay bổng tự nhiên. |
| /rayonreview | Làm nổi bật đặc tính của chất liệu rayon (vải mềm, mát). |
| /jumbofit | Tập trung vào size lớn (jumbo) và phom cắt của nó. |
| /gamistryon | Thử mặc gamis đồng thời khoe chi tiết sản phẩm. |

### Túi, Giày & Phụ Kiện

| Lệnh | Chức năng |
|---|---|
| /bagcheck | Review túi xách kèm đồ bên trong và chi tiết các ngăn. |
| /whatsinmybag | Lấy từng món trong túi ra giới thiệu ("có gì trong túi của mình"). |
| /shoefit | Mang giày vào chân, kèm shot lúc bước đi. |
| /accessorycheck | Chi tiết phụ kiện khi đang đeo trên người. |
| /matchit | Phối phụ kiện với outfit đang mặc. |
| /detailreview | Close-up chất liệu và chi tiết sản phẩm. |

### Beauty & Skincare

| Lệnh | Chức năng |
|---|---|
| /grwmbeauty | Get Ready With Me phiên bản làm đẹp. |
| /makeuplook | Gương mặt thay đổi trước và sau khi trang điểm. |
| /skincareroutine | Trình tự các bước sử dụng sản phẩm chăm sóc da. |
| /beforeafterbeauty | So sánh tình trạng da trước và sau khi sử dụng. |
| /beautyreview | Review từ góc nhìn của người dùng thông thường. |
| /producttest | Sản phẩm được dùng thử trực tiếp trước camera. |
| /getthelook | Tạo diện mạo mô phỏng theo một ảnh tham chiếu. |

### Gadget & Điện Tử

| Lệnh | Chức năng |
|---|---|
| /unbox | Mở hộp gadget. |
| /firstimpression | Ấn tượng đầu tiên khi vừa cầm sản phẩm trên tay. |
| /gadgetreview | Review dựa trên trải nghiệm sử dụng thật. |
| /setup | Quá trình lắp đặt và thiết lập gadget. |
| /featurecheck | Trình diễn các tính năng chính. |
| /worthit | Đánh giá: có đáng mua hay không. |

### Nhà Cửa, Bếp & Lifestyle

| Lệnh | Chức năng |
|---|---|
| /roommakeover | Căn phòng thay đổi trước và sau khi cải tạo. |
| /homefinds | Những món đồ gia dụng hay ho tìm được. |
| /homereview | Review sản phẩm trong sinh hoạt hằng ngày. |
| /setupwithme | Cùng sắp xếp không gian với sản phẩm. |
| /cleanwithme | Dọn dẹp nhà cửa đồng thời giới thiệu sản phẩm. |
| /kitchenfinds | Sản phẩm nhà bếp được chọn lọc. |
| /organization | Trước và sau khi sắp xếp đồ đạc gọn gàng. |

---

## Phần 2 — Bộ Công Cụ Hình Ảnh Thông Dụng

### Phong Cách Minh Họa & Hoạt Hình

| Lệnh | Chức năng |
|---|---|
| /anime, /AnimeStyle | Giao diện minh họa hoạt hình phong cách Nhật Bản. |
| /GhibliMood | Hoạt hình nhẹ nhàng, ấm áp, yên bình và kỳ ảo kiểu Studio Ghibli. |
| /MangaMotion | Các panel manga đen trắng được làm chuyển động sống động. |
| /ComicBook | Truyện tranh phong cách phương Tây với nét mực đậm và hiệu ứng halftone. |
| /pixelart, /PixelWorld | Đồ họa pixel hoài cổ như game 8-bit hoặc 16-bit. |
| /claymation | Hoạt hình stop-motion bằng đất nặn / plasticine. |
| /sketch | Nét phác bút chì hoặc bản sketch tay đen trắng. |
| /watercolor | Vệt màu nước mềm mại và trong suốt. |
| /oilpainting | Nét cọ dày có kết cấu như tranh sơn dầu. |

### Retro & Kết Cấu Phim

| Lệnh | Chức năng |
|---|---|
| /noir | Đen trắng tương phản mạnh kiểu phim trinh thám cổ điển thập niên 1940. |
| /vintage, /Retro80s | Màu sắc và không khí cổ điển đặc trưng của thập niên 1980. |
| /Vaporwave | Thẩm mỹ thập niên 90 với bảng màu tím, hồng và pastel neon. |
| /Y2KAesthetic | Phong cách tương lai đặc trưng thời kỳ chuyển giao thiên niên kỷ, đầu những năm 2000. |
| /FilmGrain | Hạt nhiễu mịn chân thực của phim celluloid. |
| /VHSLook | Méo đường nét và màu sắc đặc trưng của băng cassette VHS cũ. |

### Thể Loại Điện Ảnh

| Lệnh | Chức năng |
|---|---|
| /Cinematic, /MovieScene | Giao diện và tỷ lệ màn ảnh rộng kiểu phim chất lượng cao. |
| /HollywoodShot | Kỹ thuật quay đắt giá phong cách phim bom tấn Hollywood. |
| /NetflixStyle | Color grading (chỉnh màu) và bố cục như các series streaming hiện đại. |
| /MarvelIntro | Đoạn mở đầu hành động hoành tráng kiểu phim siêu anh hùng. |
| /ActionSequence | Cảnh hành động nhanh, căng thẳng, dồn dập adrenaline. |
| /ThrillerScene | Không khí u tối, căng thẳng và bí ẩn. |
| /DramaShot | Nhấn mạnh cảm xúc sâu lắng, chạm đến người xem. |
| /EpicFinale | Đoạn kết cao trào hoành tráng, để lại dư âm khó quên. |

### Sci-Fi & Công Nghệ Tương Lai

| Lệnh | Chức năng |
|---|---|
| /SciFiMovie | Cảnh khoa học viễn tưởng với công nghệ cao. |
| /Cyberpunk, /NeonCity | Đô thị tương lai u tối với ánh đèn neon. |
| /FutureWorld, /AIWorld | Thế giới tương lai được vận hành bởi trí tuệ nhân tạo. |
| /VirtualReality | Thế giới mô phỏng số có tính tương tác. |
| /HolographicUI | Giao diện hologram trong suốt lơ lửng giữa không trung. |
| /MatrixMode | Cơn mưa mã code xanh lá kiểu thế giới The Matrix. |
| /RobotVision | Góc nhìn qua mắt robot với lớp dữ liệu phủ lên (HUD). |
| /SpaceStation, /MarsMission | Module trạm vũ trụ và cảnh quan hành tinh sao Hỏa. |

### Fantasy & Thế Giới Mộng Mơ

| Lệnh | Chức năng |
|---|---|
| /Dreamscape | Cảnh quan siêu thực đầy tính nghệ thuật như trong cõi mơ. |
| /FairyForest | Khu rừng thần tiên với ánh sáng huyền ảo và cây cối phát sáng. |
| /MagicPortal | Cánh cổng ánh sáng xoáy kết nối hai thế giới. |
| /FloatingIslands | Quần đảo fantasy lơ lửng trên bầu trời. |
| /CloudKingdom | Lâu đài nguy nga trên biển mây. |
| /CrystalWorld | Thế giới pha lê lấp lánh, khúc xạ ánh sáng. |
| /FantasyCastle | Lâu đài ma thuật nguy nga như trong cổ tích kinh điển. |

### Ánh Sáng & Giờ Vàng

| Lệnh | Chức năng |
|---|---|
| /GoldenHour | Ánh sáng vàng ấm ngay trước lúc hoàng hôn. |
| /BlueHour | Tông xanh mát mẻ ngay sau khi mặt trời lặn. |
| /SunriseMagic | Ánh bình minh trong trẻo và kỳ ảo. |
| /sunset, /SunsetGlow | Ánh hoàng hôn kịch tính với vệt màu cam đỏ. |
| /Moonlight | Ánh sáng đêm dịu nhẹ từ ánh trăng. |
| /studio | Ánh sáng studio thương mại (rim light, softbox). |
| /neon | Đèn neon nhiều màu với độ tương phản cao. |
| /CloudBreak | Mây mở ra và tia nắng xuyên xuống (god rays). |
| /dust | Hạt bụi mịn bay lơ lửng dưới luồng sáng kịch tính. |

### Thời Tiết, Bầu Trời & Thiên Nhiên

| Lệnh | Chức năng |
|---|---|
| /AuroraSky | Bầu trời đêm với dải cực quang borealis. |
| /GalaxyWalk | Phông nền đầy sao, tinh vân và dải ngân hà. |
| /underwater, /UnderwaterDream | Không khí dưới nước với ánh nắng xuyên qua mặt nước. |
| /rain, /RainMood | Mưa lất phất với không khí yên tĩnh hoặc man mác buồn. |
| /snow, /SnowFall | Tuyết rơi nhẹ nhàng, tạo cảm giác mát lành. |
| /fog, /FogScene | Sương mù dày đặc bao phủ, cảm giác bí ẩn. |
| /StormMode, /thunderstorm | Giông bão kịch tính với sấm sét và gió mạnh. |
| /fireworks | Pháo hoa rực rỡ sắc màu trên bầu trời đêm. |

### Chuyển Động Camera

| Lệnh | Chức năng |
|---|---|
| /pushin | Camera từ từ tiến lại gần chủ thể. |
| /pullback | Camera từ từ lùi xa khỏi chủ thể. |
| /pan | Camera quay ngang sang trái hoặc sang phải. |
| /tilt | Camera ngẩng lên hoặc cúi xuống tại vị trí cố định. |
| /roll | Khung hình nghiêng xoay quanh trục ống kính (hiệu ứng dutch angle). |
| /dollypan | Camera tiến về phía vật thể đồng thời dịch chuyển sang ngang. |
| /zoom | Ống kính phóng to hoặc thu nhỏ hình ảnh mà không di chuyển camera. |
| /orbit, /orbitshot | Camera vòng quanh chủ thể theo chuyển động tròn. |
| /tracking, /trackingshot | Camera bám theo chủ thể, khớp với tốc độ di chuyển của nó. |
| /gimbalwalk | Camera tiến về phía trước theo bước chân, mượt mà như dùng gimbal. |
| /handheld | Độ rung nhẹ đặc trưng của camera cầm tay. |
| /crane, /craneshot | Camera được nâng lên hoặc hạ xuống với biên độ rộng như tay cần cẩu crane. |
| /flythrough, /fpvflythrough | Camera lao xuyên qua không gian linh hoạt kiểu drone FPV. |
| /continuous | Một chuỗi quay liền mạch không cắt cảnh (one-shot). |

### Góc & Cỡ Cảnh

| Lệnh | Chức năng |
|---|---|
| /establishing | Shot rộng mở đầu, giới thiệu địa điểm và không khí. |
| /extremelongshot | Khoảng cách rất xa để cảm nhận quy mô của môi trường. |
| /wideangle | Ống kính góc rộng, bắt được nhiều yếu tố trong một khung hình. |
| /mediumshot | Chủ thể hiện từ thắt lưng trở lên. |
| /closeup | Cận cảnh gương mặt, biểu cảm hoặc chi tiết của vật thể. |
| /macrophoto, /macroshot | Phóng đại cực độ đến mức thấy rõ kết cấu nhỏ nhất. |
| /overhead | Camera đặt ngay phía trên chủ thể, hướng thẳng xuống (bird's eye view). |
| /lowangle | Camera từ dưới nhìn lên, chủ thể trông oai vệ và có uy lực. |
| /highangle | Camera từ trên cao nhìn xuống. |
| /pov | Góc nhìn thứ nhất, như qua đôi mắt của nhân vật. |
| /droneview, /dronereveal | Cảnh quay từ trên cao kiểu drone với hơi thở điện ảnh. |
| /helicoptershot | Cảnh trên không ở khoảng cách xa kiểu trực thăng. |

### Thời Gian & Nhịp Độ

| Lệnh | Chức năng |
|---|---|
| /timelapse | Thời gian được nén lại thật nhanh từ một camera đứng yên. |
| /hyperlapse | Camera di chuyển đồng thời nén thời gian. |
| /slowmotion | Chuyển động được làm chậm lại để thấy rõ các chi tiết tinh tế. |
| /speedramp | Tốc độ thay đổi nhanh – chậm trong cùng một clip. |
| /fastforward | Tua nhanh đoạn ghi hình với tốc độ đều. |
| /reverse | Phát ngược đoạn ghi hình. |
| /daytonight | Chuyển đổi mượt mà từ ngày sang đêm. |
| /nighttoday | Chuyển đổi mượt mà từ đêm sang sáng/ngày. |
| /morph | Một hình dạng biến đổi dần thành một hình dạng khác. |
| /freeze | Hành động dừng lại trong chốc lát như một khung hình đóng băng (freeze frame). |

### Tập Trung & Cô Lập Chủ Thể

| Lệnh | Chức năng |
|---|---|
| /focus | Làm sắc nét và khóa nét vào chủ thể chính. |
| /blur | Phông nền được làm mờ nhẹ (depth of field hoặc bokeh). |
| /rackfocus | Điểm lấy nét dịch chuyển dứt khoát từ tiền cảnh sang hậu cảnh. |
| /facedetect | Tự động khóa nét và bám theo gương mặt của chủ thể. |
| /isolate | Tách chủ thể ra rõ ràng khỏi môi trường xung quanh. |

### Reveal & Hiệu Ứng Sản Phẩm

| Lệnh | Chức năng |
|---|---|
| /SmokeReveal | Sản phẩm hiện ra từ sau làn khói dày đặc. |
| /FireReveal | Sản phẩm xuất hiện giữa ngọn lửa bùng cháy. |
| /WaterReveal | Sản phẩm xuất hiện cùng tia nước bắn và sóng nước vỗ. |
| /IceReveal | Sản phẩm bước ra sau khi khối băng vỡ tan. |
| /LightningReveal | Sản phẩm được hé lộ qua một tia sét đánh xuống. |
| /InkSplash | Mực lan tỏa đầy nghệ thuật rồi tạo thành hình sản phẩm. |
| /PaintExplosion | Sơn màu nổ tung và hé lộ sản phẩm. |
| /PowderBurst | Bột màu nổ bung ra xung quanh sản phẩm. |
| /GlassBreak | Kính vỡ kịch tính ngay trước sản phẩm. |
| /ShatterTransition | Chuyển cảnh bằng mặt phẳng màn hình vỡ vụn thành nhiều mảnh. |
| /SupercarReveal | Siêu xe xuất hiện oai phong với ánh sáng kiểu phim điện ảnh. |
| /TechReveal | Sản phẩm công nghệ xuất hiện với điểm nhấn kỹ thuật số hiện đại. |
| /360Spin | Sản phẩm xoay tròn đủ 360° để nhìn thấy mọi mặt. |
| /FloatingProduct | Sản phẩm lơ lửng duyên dáng như trong trạng thái không trọng lực. |

### Quảng Cáo Màn Hình & Ngoài Trời

| Lệnh | Chức năng |
|---|---|
| /TimesSquare3DReveal | Quảng cáo 3D quang học khổng lồ trên màn hình cong kiểu Times Square. |
| /BillboardReveal | Sản phẩm xuất hiện trên biển quảng cáo lớn giữa thành phố. |
| /HologramBillboard | Billboard hologram trong suốt mang hơi thở tương lai. |
| /LEDWallAd | Quảng bá trên bức tường LED kích thước khổng lồ. |
| /CityScreenTakeover | Toàn bộ màn hình videotron của thành phố tràn ngập hình ảnh sản phẩm. |
| /FloatingBillboard | Biển quảng cáo công nghệ cao lơ lửng giữa không trung. |
| /BuildingProjection | Video mapping: chiếu hình ảnh sản phẩm lên mặt tiền tòa nhà. |
| /BusStopAd | Mockup quảng cáo chân thực trên màn hình tại trạm xe buýt. |
| /SubwayAd | Quảng cáo trong nhà ga và bên trong toa tàu điện ngầm. |
| /MallDisplay | Gian trưng bày quảng bá cao cấp bên trong trung tâm thương mại sang trọng. |

### Trình Diễn Sản Phẩm Cao Cấp

| Lệnh | Chức năng |
|---|---|
| /ProductLaunch | Không khí sân khấu ra mắt sản phẩm hoành tráng. |
| /LuxuryProduct | Giao diện khiến sản phẩm trông đắt giá và độc quyền. |
| /PerfumeAd | Hơi thở thanh lịch, sang trọng kiểu quảng cáo nước hoa. |
| /JewelryShowcase | Ánh sáng lấp lánh và phản chiếu trên trang sức trong tủ trưng bày. |
| /WatchCommercial | Ánh sáng chuẩn xác và close-up chi tiết đồng hồ cao cấp. |
| /ShoeSpotlight | Đèn spotlight biến đôi giày thành tâm điểm chú ý. |

### Phong Cách Sống Sang Trọng & Sân Khấu

| Lệnh | Chức năng |
|---|---|
| /CEOStyle | Phong thái lãnh đạo chuyên nghiệp, có uy và đẳng cấp. |
| /LuxuryWalk | Sải bước thong thả với trang phục sang trọng và thần thái tự tin. |
| /FashionRunway | Không khí sàn catwalk trình diễn thời trang chuyên nghiệp. |
| /StreetLuxury | Thời trang sang trọng hiện đại kết hợp bối cảnh đường phố đô thị. |
| /RichLifestyle | Chân dung lối sống hào nhoáng của giới thượng lưu. |
| /YachtScene | Thư giãn trên du thuyền giữa biển khơi. |
| /PenthouseView | Nội thất penthouse với tầm nhìn toàn cảnh thành phố. |
| /PrivateJet | Sự độc quyền trong khoang máy bay riêng. |
| /VIPArrival | Khách danh dự xuất hiện như trên thảm đỏ. |

### Không Khí Không Gian & Workspace

| Lệnh | Chức năng |
|---|---|
| /CozyMorning | Buổi sáng yên tĩnh, ấm áp và dễ chịu tại nhà. |
| /CoffeeAesthetic | Khoảnh khắc pha và thưởng thức cà phê yên tĩnh, đầy tính thẩm mỹ. |
| /CafeScene | Không khí thư giãn trong quán cà phê hiện đại. |
| /DeskSetup, /CreatorDesk | Bàn làm việc tối giản, gọn gàng kiểu nhà sáng tạo nội dung. |
| /GamingSetup | Phòng gaming công nghệ cao với đèn LED RGB. |
| /StudyVibes, /Productivity | Không khí học tập và làm việc tập trung, hiệu quả. |
| /HomeOffice | Không gian làm việc tại nhà thoải mái và ngăn nắp. |
| /MinimalRoom | Căn phòng sạch sẽ, thoáng đãng, phong cách tối giản hiện đại. |

### Điều Khiển Kỹ Thuật Nâng Cao

| Lệnh | Chức năng |
|---|---|
| /keyframe | Xác định các điểm thay đổi quan trọng trong dòng chuyển động (animation). |
| /seamless | Video lặp lại (loop) nối tiếp mượt mà không vết nối. |
| /upscale | Tăng độ phân giải, độ sắc nét và chi tiết của video. |
| /depthmap | Điều chỉnh thông tin độ sâu 3D trong footage. |
| /recompose | Sắp xếp lại khung hình và bố cục của chủ thể. |
| /stabilize | Giảm rung lắc để footage luôn mượt mà. |
| /colorgrade | Chỉnh màu và grading màu tự động theo chuẩn chuyên nghiệp. |
| /multicam | Mô phỏng việc chuyển đổi giữa nhiều góc camera khác nhau. |

---

## Phần 3 — Các Loại Camera Shot

Tài liệu tham chiếu camera shot tập trung tại một chỗ: ba lệnh camera dùng trong combo affiliate, tiếp đến là các loại shot xét theo cỡ khung hình và theo góc quay.

### Lệnh Camera Trong Combo Affiliate

| Lệnh | Chức năng |
|---|---|
| /povhandproduct | Góc nhìn thứ nhất với bàn tay đang cầm và trình diễn sản phẩm. |
| /flatlaycamera | Camera hướng thẳng xuống sản phẩm được bày biện trên một mặt phẳng (flat lay). |
| /topdownshot | Shot quay thẳng đứng từ trên cao xuống. |

### Loại Shot Theo Cỡ Khung Hình

Tài liệu tham chiếu loại shot dựa trên mức độ chủ thể lọt vào khung hình. Loại nào đã có lệnh thì dùng lệnh của nó; các loại còn lại được viết dưới dạng thuật ngữ thông thường trong prompt.

| Loại shot | Phạm vi & cảm giác | Lệnh / cách viết |
|---|---|---|
| Extreme long shot | Chủ thể trông nhỏ bé giữa phong cảnh rộng lớn; làm nổi bật quy mô và không khí. | /extremelongshot |
| Long shot (wide) | Toàn thân chủ thể hiện rõ cùng môi trường xung quanh. | /wideangle hoặc /establishing |
| Full shot | Chủ thể trọn vẹn từ đầu đến chân, với một ít không gian xung quanh. | viết "full shot" |
| Medium shot | Chủ thể từ thắt lưng trở lên; cân bằng giữa biểu cảm và cử chỉ. | /mediumshot |
| Medium close-up | Từ ngực trở lên; cảm giác thân mật hơn và biểu cảm bắt đầu chiếm ưu thế. | viết "medium close-up" |
| Close-up | Gương mặt hoặc một vật thể lấp đầy khung hình. | /closeup |
| Extreme close-up | Một chi tiết rất nhỏ, như đôi mắt hoặc kết cấu chất liệu, lấp đầy toàn bộ khung hình. | /macrophoto, /macroshot, hoặc viết "extreme close-up" |

### Loại Shot Theo Góc & Điểm Nhìn

| Loại shot | Phạm vi & cảm giác | Lệnh / cách viết |
|---|---|---|
| Eye level | Camera ngang tầm mắt chủ thể; hình ảnh trung tính và tự nhiên. | viết "eye-level shot" |
| High angle | Camera ở phía trên chủ thể nhìn xuống; chủ thể trông nhỏ bé hoặc yếu thế. | /highangle |
| Low angle | Camera ở phía dưới chủ thể nhìn lên; chủ thể trông mạnh mẽ và hùng vĩ. | /lowangle |
| Bird's eye / overhead | Quay thẳng đứng từ trên cao; cho thấy tổng thể bố cục. | /overhead, /topdownshot |
| Flat lay | Sản phẩm đặt trên mặt phẳng, được quay từ trên xuống. | /flatlaycamera |
| Dutch angle | Khung hình bị nghiêng; tạo cảm giác căng thẳng hoặc bất ổn. | /roll |
| POV | Góc nhìn thứ nhất. | /pov; /povhandproduct cho bàn tay đang cầm sản phẩm |
| Over-the-shoulder | Quay từ phía sau vai một người, hướng về người đối diện hoặc vật thể. | viết "over-the-shoulder shot" |
| Two shot | Hai chủ thể cùng nằm trong một khung hình. | viết "two shot" |
| Worm's eye view | Từ sát mặt đất ngước nhìn lên một cách cực đoan. | viết "worm's eye view" |
| Aerial | Shot quay từ trên không. | /droneview, /helicoptershot |

---

## Phần 4 — Ví Dụ Ứng Dụng Thực Tế Cho TikTok / Shopee (KKHome AI biên soạn)

Ba phần đầu cho bạn *từ điển lệnh*. Phần này cho bạn *cách đánh trận*: cách ghép lệnh thành prompt hoàn chỉnh để tạo ảnh và video quảng cáo bán được hàng.

**Công thức chung bất bại:**

> **Lệnh định dạng (Phần 1) + Lệnh hình ảnh / camera (Phần 2 – 3) + Thoại tiếng Việt + CTA**

**Luật giọng cho video bán hàng tại Việt Nam:** luôn khóa **giọng nữ miền Nam — ngọt ngào, trong trẻo, thân thiện, tràn năng lượng** như một creator TikTok thật. Mọi ví dụ video dưới đây đều đã khóa sẵn luật này.

**Cách dùng:** copy nguyên prompt mẫu, thay phần trong [ngoặc vuông] bằng sản phẩm của bạn.

### 4.1 Tạo Ảnh Với Nhân Vật & Sản Phẩm

**Ví dụ 1 — Ảnh UGC nhân vật cầm sản phẩm (làm ảnh bìa / ảnh mở đầu video)**

Combo: /ugcproduct /GoldenHour /closeup

```
/ugcproduct /GoldenHour /closeup
A young Vietnamese female content creator with long black wavy hair, white shirt and blue jeans, holding a [serum bottle] up beside her cheek, smiling warmly at camera, cozy bedroom background with warm golden-hour window light, authentic UGC photo style, shot on smartphone, vertical 9:16.
```

**Ví dụ 2 — Ảnh quảng cáo sản phẩm chuẩn studio (đăng trang sản phẩm TikTok Shop / Shopee)**

Combo: /photoshootad /detailproductlook /FloatingProduct /studio

```
/photoshootad /detailproductlook /FloatingProduct /studio
Premium studio product photo of a [glass serum bottle] floating elegantly above a soft beige podium, water droplets and fresh green leaves around it, dramatic softbox lighting with rim light, macro detail of the bottle texture and label, clean luxury advertising look, vertical 9:16.
```

**Ví dụ 3 — Ảnh thử đồ: đưa outfit từ ảnh sản phẩm lên người nhân vật**

Combo: /transferoutfit /tryonoutfit /bodyfit

```
/transferoutfit /tryonoutfit /bodyfit
Transfer the outfit from the reference product photo onto the female character: same dress design, color and fabric details preserved exactly. She stands in a bright modern café, full-body shot, natural confident pose, the fabric falls and drapes realistically on her body, vertical 9:16.
```

### 4.2 Tạo Ảnh Storyboard Cho Nhân Vật & Sản Phẩm

Storyboard là *bản đồ hình ảnh* của video trước khi quay: mỗi ô là một cảnh. Có storyboard, bạn nhìn thấy toàn bộ video trước khi tốn credit render, và dùng từng ô làm ảnh mở đầu (start frame) cho từng clip.

**Ví dụ 4 — Storyboard 6 ô cho một video bán hàng 20 giây**

```
/storyboard prompt
Create a 6-panel storyboard sheet (2 columns x 3 rows, thin white borders, small panel numbers 1-6) for a 20-second TikTok Shop video selling a [facial serum]. SAME character in all panels: young Vietnamese woman, long black wavy hair, white shirt, blue jeans.
Panel 1 - HOOK: she looks at camera with an excited surprised face, holding the serum bottle close to the lens.
Panel 2 - PROBLEM: she touches her dry cheek in front of a mirror, worried expression.
Panel 3 - PRODUCT REVEAL: the serum bottle glowing on a clean podium with soft sparkles.
Panel 4 - DEMO: she applies one drop of serum on her cheek, eyes closed, relaxed and happy.
Panel 5 - RESULT: glowing smooth skin, big bright smile, thumbs up.
Panel 6 - CTA: she points down at a shopping cart icon at the bottom-left corner.
Bright, clean, realistic photo style, vertical 9:16 sheet.
```

### 4.3 Tạo Video Với Nhân Vật & Sản Phẩm (Thoại Tiếng Việt + CTA)

**Ví dụ 5 — Video UGC bán hàng hoàn chỉnh trong 1 clip (~10 giây)**

Combo: /ugcproducthook /ugcproduct /detailproductlook

```
/ugcproducthook /ugcproduct /detailproductlook
Vertical 9:16 UGC product video, 10 seconds, realistic smartphone footage. A young Vietnamese female creator (long black wavy hair, white shirt, blue jeans) sits in a bright cozy room holding a [serum bottle]. She opens with an excited hook looking straight at camera, brings the bottle close to the lens for a clear detail look, then smiles and points down at the end.
VOICE LOCK: young female voice, SOUTHERN Vietnamese accent, sweet, clear and bright, friendly energetic UGC creator tone. She speaks ONLY Vietnamese, lip-synced.
DIALOGUE: "Mấy bà ơi, da khô căng thì thử em serum này nè! Thấm nhanh, da mướt thấy rõ luôn. Nhấn giỏ hàng bên dưới để săn ưu đãi nha!"
CTA: in the final 3 seconds, a TikTok Shop shopping-cart icon appears at the bottom-left corner with a soft pulsing glow while she points down at it.
Natural-speed realistic motion, stable face, no other text overlays.
```

**Ví dụ 6 — Video 3 clip theo storyboard (hook → demo → CTA)**

Dùng ảnh storyboard ở Ví dụ 4 làm start frame cho từng clip. Mỗi clip một combo lệnh riêng:

*Clip 1 — Hook (Panel 1–2):*

```
/ugcproducthook /mediumshot
She holds the [serum bottle] close to the lens with an excited face, then touches her dry cheek with a worried look.
DIALOGUE: "Da khô căng, sờ vào ráp hết trơn, khó chịu ghê luôn á!"
```

*Clip 2 — Demo & kết quả (Panel 4–5):*

```
/producttest /detailproductlook /closeup
She applies one drop of serum on her cheek, massages gently, then shows her glowing smooth skin with a big happy smile and a thumbs up.
DIALOGUE: "Thoa một giọt thôi nè, thấm liền, da mướt mịn thấy rõ luôn!"
```

*Clip 3 — CTA (Panel 6):*

```
/ugcproduct /closeup
She smiles brightly, holds the bottle beside her face and points down at the bottom-left corner.
DIALOGUE: "Em để link ở giỏ hàng góc trái nha, đang ưu đãi, chốt lẹ kẻo hết!"
CTA: TikTok Shop shopping-cart icon at the bottom-left corner for the final 3 seconds, soft pulsing glow.
```

Cả 3 clip đều kèm dòng khóa giọng: **VOICE LOCK: young female voice, SOUTHERN Vietnamese accent, sweet, clear and bright, friendly energetic UGC creator tone. She speaks ONLY Vietnamese, lip-synced.**

**Ví dụ 7 — Video unboxing không lộ mặt + lời thuyết minh**

Combo: /unboxing /faceless /topdownshot /detailproductlook

```
/unboxing /faceless /topdownshot /detailproductlook
Vertical 9:16 faceless unboxing video shot from directly above. A pair of hands opens a delivery box on a clean white table, takes out a [mini blender], shows its buttons and blade in close-up detail, then plugs it in and blends a small cup of mango smoothie.
VOICE-OVER (no one on screen speaks): young female voice, SOUTHERN Vietnamese accent, sweet, clear and bright, cheerful narrator tone, speaks ONLY Vietnamese.
NARRATION: "Cùng mình khui em máy xay mini này nha! Nhỏ gọn vậy mà xay khỏe bất ngờ luôn á. Để nhà bếp hay mang đi làm đều tiện hết trơn!"
CTA: in the final 3 seconds, a TikTok Shop shopping-cart icon appears at the bottom-left corner with a soft pulsing glow.
```

**Ví dụ 8 — Video Problem–Solution (nêu vấn đề → sản phẩm giải quyết → CTA)**

Combo: /problem-solution /ugcproduct

```
/problem-solution /ugcproduct
Vertical 9:16 UGC video, 10 seconds. A young Vietnamese female creator stands under harsh midday sun, fanning herself, uncomfortable in the heat. She puts on a [UV-protection sun jacket], instantly looks cool and relieved, zips it up and smiles at camera.
VOICE LOCK: young female voice, SOUTHERN Vietnamese accent, sweet, clear and bright, friendly energetic UGC creator tone. She speaks ONLY Vietnamese, lip-synced.
DIALOGUE: "Trưa nắng chang chang, da rát hết trơn... May mà có em áo chống nắng này, mát rượi mà còn chống UV nữa. Ai hay đi nắng thì ghé giỏ hàng xem thử nha!"
CTA: in the final 3 seconds, a TikTok Shop shopping-cart icon appears at the bottom-left corner with a soft pulsing glow while she points down at it.
```

### 4.4 Bảng Công Thức Vàng & Khối CTA Chuẩn

| Mục tiêu | Combo gợi ý |
|---|---|
| Ảnh bìa UGC có nhân vật | /ugcproduct + /GoldenHour + /closeup |
| Ảnh sản phẩm đăng Shopee / TikTok Shop | /photoshootad + /detailproductlook + /studio |
| Ảnh thử đồ từ ảnh sản phẩm | /transferoutfit + /tryonoutfit + /bodyfit |
| Video hook mạnh, bán trong 10 giây | /ugcproducthook + /ugcproduct + thoại Việt + CTA |
| Video mở hộp lấy niềm tin | /unboxing + /faceless + /topdownshot + thuyết minh |
| Video giải quyết vấn đề | /problem-solution (+ /beforeafter nếu hợp) + thoại Việt + CTA |
| Video review chân thật, bán mềm | /honestreview + /softsell + /ugcproduct |
| Video kể chuyện dẫn vào sản phẩm | /storyaffiliate + /Cinematic (nhẹ) + thoại Việt + CTA |

**Khối CTA chuẩn — dán vào cuối mọi prompt video bán hàng:**

```
CTA: in the final 3 seconds, a TikTok Shop shopping-cart icon appears at the bottom-left corner with a soft pulsing glow while the character points down at it.
VOICE LOCK: young female voice, SOUTHERN Vietnamese accent, sweet, clear and bright, friendly energetic UGC creator tone. She speaks ONLY Vietnamese, lip-synced.
```

---

*Nắm vững bộ lệnh này cùng các ví dụ trên, bạn đã có trong tay nền tảng làm quảng cáo TikTok / Shopee như một creator chuyên nghiệp: có định dạng, có hình ảnh, có storyboard, có thoại và có CTA. Việc còn lại chỉ là chọn sản phẩm và bắt đầu tạo.*

### 4.5 Cách Ra Lệnh Cho Muse Khi Dùng Kèm File Chỉ Thị Vận Hành

Nếu bạn nạp tài liệu này vào Muse cùng file **Chỉ Thị Vận Hành KKHome AI**, bạn không cần thuộc lòng prompt — chỉ cần đưa ảnh sản phẩm và gõ một câu lệnh ngắn:

| Bạn gõ | Muse sẽ làm |
|---|---|
| "Tạo ảnh cho sản phẩm này" | Đề xuất 5 phương án ảnh và tạo ảnh theo lựa chọn của bạn. |
| "Tạo kịch bản cho sản phẩm này" | Viết kịch bản UGC liền mạch 2 phân cảnh × 10 giây, thoại tiếng Việt giọng nữ miền Nam, có CTA. |
| "Tạo poster cho sản phẩm này" | Tạo poster thu hút click, tiêu đề 5–7 chữ, dùng đúng nhân vật và sản phẩm trong video. |
| "Làm trọn gói sản phẩm này" | Chạy cả 3 chặng một mạch: ảnh → kịch bản → poster. |
| "Tạo ảnh storyboard cho sản phẩm này" | Tạo ảnh storyboard 6 ô để bạn duyệt trước khi làm video. |

Mẹo nhỏ: kèm theo câu lệnh, hãy nói thêm sản phẩm dùng để làm gì, điểm mạnh nhất là gì, và đang có ưu đãi gì — Muse sẽ viết hook và CTA trúng ý hơn hẳn.
