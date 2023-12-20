Mô tả tóm tắt nội dung dự án:
Dữ liệu test 200k KH đang sử dụng dịch vụ di động của Viettel

Đề bài:

- EDA CSDL, nhận diện đặc điểm nhóm KH hành vi/tiêu dùng của KH

- Dựng Model dự báo nhóm KH tiềm năng đang sử dụng 3G có thể chuyển dịch sang sử dụng hạ tầng 4G trong tháng tiếp theo.

Link data https://drive.google.com/file/d/1ooa1oSKoPI5TKt7WB4FNMvgRDMs40ghE/view?usp=sharing

  Ý nghĩa các trường:
cuoc_goc_gprs_220601: doanh thu data KH phát sinh khi sử dụng vượt quá lưu lượng cho phép

ha_tang_220601: Hạ tầng sử dụng của KH 2G-3G là công nghệ cũ, 4G là công nghệ mới tương lai sẽ 

is_sim_4g_220601: Khách hàng đã có SIM là SIM 4G (Điều kiện cần để TB có thể chuyển lên hạ tầng 4G)

ll_thoai_220601: Lưu lượng thoại KH sử dụng (Tính bằng giây - nên quy đổi ra phút khi chình bày)

nod_psll_thoai_220601: Số ngày sử dụng gọi thoại

so_lan_nap_the_220601: Số lần nạp thẻ (nạp tiền vào tài khoản để tiêu dùng)

so_lan_nap_topup_220601: Lạp TOP up là hình thức nạp tiền hiện đại qua bank hoặc các công cụ số, những KH không có giá trị tức là nạp tiền theo cách truyền thống

so_ngay_su_dung_220601: Số ngày sử dụng 1 trong những dịch vụ của Viettel: Thoại, Data, SMS.

thiet_bi_220601: Thiết bị KH đang sử dung: Thiết bị 2G , thiết bị 3G, Thiết bị 4G (Chỉ KH có thiết bị 4G mới có thể chuyển đổi được KH dùng lên 4G)

thuc_4g_220601: Trường này là trường cần sử dụng để kiểm nghiệm KH đạt thực 4G hay không ==> Em cần dự báo ra nhóm KH đang có giá trị 0 có tiềm năng chuyển đổi sang 1 trong tháng tiếp theo.

tong_cuoc_goc_data_4_huong_22060: Chi tiêu của KH cho dịch vụ Data (VNĐ)

tong_cuoc_goc_fn_220601: Chi tiêu của KH cho tất cả các dịch vụ cung cấp trên số điện thoại của KH (Thoại, SMS, Data, Vas) (VND)

tong_cuoc_goc_thoai_220601: Chi tiêu của KH cho dịch vụ thoại (VND)

tong_ll_gprs_220601: Hành vi sử dụng data của KH (Đơn vị GB) - như kiểu đơn vị đo của KH khi xem youtube/vào facebook.

tong_tien_nap_topup_220601: Số tiền KH nạp vào tài khoản qua hình thức hiện đại (Bank, thanh toán số)

tuoi_khach_hang_cut_level_220601: Tuổi đời của KH

user_id: mã thuê bao (Đây là mã hóa của số điện thoại)
