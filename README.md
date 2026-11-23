# B-nh-claude

Bản xuất bộ nhớ của người dùng (đã lưu đến 23/11/2026) để nhập vào Graphify.
Mỗi mục `##` bên dưới tương ứng với một file bộ nhớ gốc. Nội dung là các điều người dùng đã nói, không có suy đoán thêm.

## Hồ sơ (profile)

- Sử dụng phần mềm kế toán MISA ASP; công ty Tân Thúy chỉ là một trong nhiều khách hàng, không phải công ty chính.
- Làm dịch vụ kế toán cho rất nhiều công ty thuộc nhiều ngành nghề (mỗi công ty có thể khác ngành, chế độ kế toán và phương pháp tính thuế GTGT); mỗi lần giao việc gửi kèm file của công ty đó (danh mục khách hàng, nhà cung cấp, hàng hóa, tồn kho).
- Ngoài kế toán còn làm nghề bán hàng online với tư cách cá nhân kinh doanh: chủ yếu bán quần áo, thỉnh thoảng bán đồ ăn uống, tạp hóa; kênh bán hàng tên "Hain Review".
- Còn làm nhà sáng tạo nội dung giải trí (nghề riêng) trên TikTok và Facebook, thể loại hài hước vui vẻ, chủ đề cuộc sống hằng ngày, content tạo tiếng cười; muốn Claude giúp phân tích clip viral, chiến lược giữ chân người xem, tạo clip bằng AI.
- Nghề sáng tạo nội dung giải trí chưa tạo kênh, đang nghiên cứu, tên kênh sẽ bổ sung sau; mục tiêu kênh: tăng người theo dõi, kiếm tiền từ nền tảng, nhận quảng cáo, kéo khách sang bán hàng; nội dung phải sạch sẽ, không dính tai tiếng, vui vẻ nhưng mang thiện ý.
- Với nghề bán hàng online, muốn nghiên cứu xây dựng thuật toán giữ chân người mua và giúp video, clip đăng lên có khả năng lên xu hướng cao nhất, tương tự nghề sáng tạo nội dung.
- Ba nghề tách riêng (kế toán, bán hàng online, sáng tạo nội dung giải trí); kế toán là nghề chính.

## Cách làm việc mong muốn (preferences)

- Áp dụng cho mọi câu hỏi: ưu tiên độ chính xác, tính thực tế và khả năng kiểm chứng hơn tốc độ; tự kiểm tra lập luận, số liệu, công thức trước khi trả lời.
- Không bịa số liệu, điều luật, tài liệu hay nguồn; phân biệt rõ điều chắc chắn, điều phụ thuộc điều kiện, điều thiếu dữ liệu và điều chỉ là giả định.
- Với pháp luật, thuế, kế toán, tài chính, y tế, kỹ thuật và thông tin dễ thay đổi: ưu tiên văn bản và nguồn chính thức, kiểm tra nguồn mới nhất, nêu căn cứ để kiểm tra lại; với luật và thuế phải xác định thời điểm áp dụng, phân biệt luật, nghị định, thông tư, công văn.
- Tính toán: đưa công thức và thay số, kiểm tra phép tính, không làm tròn nếu ảnh hưởng kết luận, nói rõ cần thêm dữ liệu nào nếu thiếu.
- Với tài liệu hoặc hình ảnh cung cấp: phân tích trực tiếp, không suy diễn phần không có hoặc không rõ.
- Câu hỏi phức tạp trình bày theo cấu trúc KẾT LUẬN, GIẢI THÍCH, CĂN CỨ / NGUỒN, LƯU Ý (chỉ điều kiện, ngoại lệ, rủi ro thật sự quan trọng); câu hỏi đơn giản thì trả lời ngắn.
- Ngôn ngữ đơn giản, giải thích thuật ngữ khi cần, chia bước với vấn đề phức tạp, không dài dòng phần không cần thiết.
- Gặp chỗ không chắc (tên hàng, khách hàng, số liệu) thì đoán hợp lý nhưng đánh dấu rõ để kiểm tra; file kết quả mặc định là Excel (.xlsx) có công thức kiểm tra.
- Mặc định mọi câu hỏi và yêu cầu hiểu là việc kế toán (nghề chính); chỉ khi nói rõ làm cho bán hàng online hoặc sáng tạo nội dung thì mới làm theo hướng nghề đó, không tự suy ra.

## Kế toán thuế (tax-accounting)

- Quan tâm đến kế toán thuế và các công việc liên quan đến giải trình, giúp doanh nghiệp không bị phạt, tối ưu chi phí và lợi nhuận.

## Đối chiếu sao kê ngân hàng (doi-chieu-sao-ke-ngan-hang)

- File Nhập_ngân_hàng.xlsx gồm 5 sheet: Sao kê, Nhà cung cấp, Khách hàng, Bán ra, Mua vào; cần điền cột Mã khách, Tên khách, TK đối ứng trên sheet Sao kê.
- Quy tắc 1: khớp ngày + số tiền Nợ/Có = Tổng tiền thanh toán + diễn giải/đơn vị thụ hưởng chứa tên khách hàng hoặc nhà cung cấp thì điền mã đó.
- Quy tắc 2: lệch ngày nhưng số tiền khớp, hoặc diễn giải chứa thông tin khớp với khách hàng/nhà cung cấp thì vẫn điền chính khách hàng/nhà cung cấp đó.
- TK đối ứng thường gặp: 1111 rút nộp tiền, 131 đối soát với bán, 331 đối soát với mua, 334 chi lương, 3383 đóng BHXH, 515 lãi tiền gửi, 642 các loại chi phí.
- Muốn kết quả khớp nhất, dùng được và chính xác nhất.
- Muốn thang mức khớp A+ đến E và thêm mục Không xác định (A+ chắc chắn 100%, A khớp tốt, B khớp vừa); muốn có câu lệnh (prompt) dán được ở bất kỳ đâu để ra kết quả như vậy.
- Muốn 1 câu lệnh dùng chung cho mọi công ty để đối chiếu sao kê.

## Hóa đơn viết tay trên meInvoice (hoa-don-tay-meinvoice)

- Nhập hóa đơn từ ảnh hóa đơn thanh toán viết tay trên MISA meInvoice (Hóa đơn → HĐ từ máy tính tiền), từng hóa đơn một, bấm "Lưu" không "Lưu và Phát hành".
- Họ tên người mua luôn là "Bán cho người tiêu dùng" (mã KL), không nhập tên khách trên ảnh; giữ đúng ngày trên ảnh.
- Chữ viết tay hay thiếu chữ: khớp từ 2 chữ trở lên với mặt hàng trong danh mục thì dùng mặt hàng có sẵn; chỉ khớp 1 chữ thì tạo mã mới (mã bằng chữ cái đầu, nhập ĐVT và giá bán).
- Giá ghi theo nghìn đồng nên nhân 1.000; số lượng dạng "2+1" tính ra số thực tế; đối chiếu tổng tiền với tổng viết tay trước khi lưu.
- Sau khi xong báo: tổng tiền từng hóa đơn, mặt hàng phải đoán tên, mặt hàng tạo mới.

## Hóa đơn KDF VN trên Mobifone Invoice (kdf-vn-hoa-don-mobifone)

- Làm hóa đơn cho Công ty TNHH KDF VN từ phiếu giao hàng PDF, lập trực tiếp trên Mobifone Invoice: vào hóa đơn TT78, chọn lập hóa đơn (Có mã CQT).
- Tên đơn vị/người mua ghi theo tên người mua hàng trên file PDF.
- Mã hàng tìm trên phần mềm theo đơn giá trong file Book2 (đơn giá đã cài ở mã hàng, ví dụ gói 5.7g đơn giá 20,370 là mã VT00441 (20370,37)T7.26); phần mềm thiếu phần thập phân thì thêm theo đơn giá Book2.

## Viết hóa đơn theo mẫu (viet-hoa-don-theo-mau)

- Gửi hóa đơn đã viết trước của một khách làm mẫu + file tồn kho (Tổng_tồn_kho.xlsx), nhờ viết thêm hóa đơn cho khách đó theo số tiền yêu cầu (ví dụ hơn 50 triệu, tầm 25 triệu). Khách gồm Thanh Sơn, Lâm Ký.
- Bán cho công ty thì mặt hàng thuế 5% chuyển thành KKKNT.
- Tự động trừ tồn sau mỗi hóa đơn viết xong.
- Điền file mẫu bán hàng MISA ASP (Mau_ban_hang_6.xls) để up lên MISA; thông tin nào không biết thì để trống cho tự điền.
- Người mua trên hóa đơn có thể là công ty, hộ kinh doanh hoặc tổ chức khác thì ghi đúng tên; nếu chỉ là tên người (không phải tổ chức) và không có thông tin xác thực thì coi là khách lẻ, ghi "Bán cho người tiêu dùng".

## Xuất hóa đơn khớp số tiền (xuat-hoa-don-khop-tien)

- Làm việc lặp lại: gửi file tồn kho + file sao kê (số tiền cần khớp), nhờ nhặt mặt hàng sao cho tổng giá trị bằng đúng từng số tiền để xuất hóa đơn.
- File tồn kho (Tong_hop_ton_kho.xlsx) có cột: Tên kho, Mã hàng, Tên hàng, Đơn vị chính (ĐVC), Số lượng, Đơn giá; đơn giá trong file là giá bán.
- File sao kê (ReportIBSCorpAccountStatement) có cột: Diễn giải, Tên đã tách, Tổng tiền cần viết; mỗi dòng là một hóa đơn cần khớp.
- Quy tắc: đơn giá được dao động ±1% so với đơn giá gốc; làm tròn đến đồng; tối đa 10 dòng hàng mỗi hóa đơn; loại các dòng thuộc "Kho KM"; ưu tiên mặt hàng số lượng nhiều.
- Viết hóa đơn bán cho công ty theo mẫu (KKKNT, trừ tồn, file Mẫu bán hàng): xem mục "Viết hóa đơn theo mẫu".
- Cách làm trực tiếp trên vinvoice.viettel.vn từ ảnh sao kê: vào Lập hóa đơn, điền tên khách có dấu theo sao kê, chọn mẫu "nhiều thuế từ máy tính tiền", đóng vai người đi chợ chọn món từ danh mục (số lượng 1, đơn giá × 1 = thành tiền), chỉnh giá 1–2 món để thành tiền + thuế bằng đúng số tiền sao kê, bấm Lập hóa đơn nháp rồi lặp lại cho các dòng sau.
- Khi tự chọn hàng trên MISA ASP: tuyệt đối không xuất vượt tồn, luôn bật "Chỉ hiển thị hàng hóa còn tồn"; số mặt hàng mỗi hóa đơn càng ít càng tốt (tối đa 10); giá bán lấy sẵn trên phần mềm, chỉ sửa 1 dòng (dòng cuối, xem thiếu bao nhiêu để nốt) trong ±1%, không khớp thì bỏ qua; chọn mã hàng ngẫu nhiên nhưng liên quan nhau; ưu tiên đẩy hàng tồn nhiều.
- Giới hạn số lượng mỗi mã: đơn giá dưới 100k tối đa 15; 100k–500k tối đa 10; trên 500k tối đa 5; chỉ vượt khi đơn quá lớn không còn hàng khác để đẩy; số lượng hợp lý như người mẹ bỉm sữa đi chợ; hóa đơn lẻ dưới 5 triệu gồm thuế (số tiền khớp đã bao gồm thuế).
- Khách lẻ trên MISA ASP: tên người mua lấy theo sao kê, copy vào ô Người liên hệ, địa chỉ để "Thành phố Hà Nội"; khi tự chọn tên thì mã khách vẫn để khách lẻ.

### Dự án "Viết hóa đơn của Sương" (TDG)

- Làm việc lặp lại: gửi file tồn kho + số tiền cần khớp (file sao kê hoặc nói trực tiếp), nhờ nhặt mặt hàng sao cho tổng đúng số tiền để xuất hóa đơn.
- File tồn kho của TDG (Tong_hop_ton_kho): Mã hàng, Tên hàng, ĐVT, Đầu kỳ/Nhập/Xuất/Cuối kỳ (số lượng, giá trị); không có đơn giá, giá lấy từ file danh sách hàng hóa dịch vụ TDG; "cái nào có giá thì lấy".
- Ghép giá bán ra: từ file "Danh sách hàng hóa TDG" sang file "Danh sách hàng hóa dịch vụ TDG" (ghép theo tên hàng, vào cột Đơn giá bán 1).
- Số tiền hóa đơn là TỔNG THANH TOÁN ĐÃ GỒM THUẾ GTGT (8%/10% theo từng mặt hàng); khi không khớp thì giữ nguyên các mặt hàng đã chọn và giảm số lượng.
- Muốn hóa đơn khoảng 10 mặt hàng; không được âm kho (số lượng ≤ tồn cuối kỳ).
- Quy tắc: đơn giá dao động ±1%; làm tròn đến đồng; tối đa 10 dòng hàng mỗi hóa đơn; loại các dòng thuộc "Kho KM"; ưu tiên mặt hàng số lượng nhiều.
- Khi viết hóa đơn bán cho công ty (gửi kèm hóa đơn mẫu của khách và file tồn kho): hàng thuế 5% chuyển thành KKKNT; tự động trừ tồn sau mỗi hóa đơn rồi viết tiếp hóa đơn kế; hóa đơn xong thì điền vào file Mẫu bán hàng (.xls) của MISA ASP để up lên.
- Mỗi hóa đơn chỉ sửa giá của 1 mặt hàng cho khớp số tiền, giá các mặt hàng còn lại giữ nguyên giá gốc.
- Muốn đẩy hàng ít xuất và hàng tồn nhiều ra trước khi chọn mặt hàng.
- Điền file mẫu bán hàng MISA ASP (Mau_ban_hang .xls) từ kết quả ghép: thông tin nào không có thì để trống.
- Người mua là tên người không có thông tin xác thực thì ghi khách lẻ "Bán cho người tiêu dùng"; tên công ty, hộ kinh doanh hay tổ chức khác thì ghi đúng tên.

## Quy tắc chung xuất hóa đơn trực tiếp (xuat-hoa-don-truc-tiep)

- Lập hóa đơn trực tiếp trên web (MISA ASP, meInvoice, vinvoice), chỉ Lưu, không phát hành; tự gửi CQT sau khi kiểm tra.
- Mã khách lẻ mỗi công ty đặt khác nhau (không cố định KL), tên luôn là khách lẻ / bán cho người tiêu dùng; chọn mã xong thì sửa tên người mua cho khớp; khách có mã số thuế giữ mặc định theo danh mục.
- Chỉ MISA ASP có tồn kho (nơi vừa viết hóa đơn vừa lưu nghiệp vụ); meInvoice, vinvoice chỉ viết hóa đơn, tồn kiểm ở phần mềm khác.
- Mã hàng mới đặt dạng VT + dãy số liên tục (VT00001, VT00002), kiểm tra danh mục để nối tiếp; nhà hàng 1985 (meInvoice) đặt mã theo chữ cái đầu của tên món, ĐVT hợp món.
- Thuế lấy theo phần mềm; công ty tính thuế trên doanh thu không cần thuế dòng hàng, công ty tính giá bình quân gia quyền mới cần; công ty chưa rõ thì xem hóa đơn đã xuất trước.
- Ngày hóa đơn theo ảnh, không có thì lấy ngày hiện tại.
- Khi lập hóa đơn xong không cần báo cáo cuối, chỉ một câu ngắn; có sai thì người dùng tự dừng lệnh và sửa.
