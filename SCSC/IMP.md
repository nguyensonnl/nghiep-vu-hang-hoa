### QUY TRÌNH HÀNG NHẬP

- Điều kiện khai thác hàng:

  - FFM
  - Manifest(MNF)
  - Định danh hàng hóa
  - Nhận hàng từ RAMP

- Trường hợp bất thường:
  - Wrong Dest, MAWB, HAWB
  - Without Label AWB
  - FDCA: Thừa hàng
  - MSCA: Thiếu hàng
  - Kiện hàng này không thuộc MAWB

### Flow

- Diễn giải quy trình bộ phận nhập hàng breakdown sau khi nhận hàng từ RAMP cho đến khi khai thấc
- Điện FFM là gì? Thể hiện điều gì?
- Xem các location hàng lưu kho, trước khi lưu kho thì sẽ làm gì?

  Ramp nhận hàng sau khi máy bay đáp rồi sau đó sẽ chuyển về bộ phận nhập
  Các tài liệu như manifest cargo, consol cargo, awb sẽ chuyển về bộ phận tài liệu
  Còn hàng hóa sẽ được chuyển về bộ phận breakdown để khai thác hàng hóa
  Đối với breakdown sẽ được nhận được điện FFM trên Hermes sẽ được lược khai tất cả các ULD/Bulk có trên chuyến bay
  Trước khi chuẩn bị nhận hàng từ Ramp thì sẽ in điện FFM để kiểm tra chính xác các hàng có trên ULD/BULK và các điện liên quan như email,...
  Sau khi kiểm tra các ULD/BUlk đều thể hiện có trên điện FFM và hệ thống 1 cửa Hai quản, định danh hàng hóa, quán lý hàng hóa thì tiến hành nhận hàng từ RAMP
  Trước khi nhận hàng từ RAMP thì chuẩn bị mặt bằng để khai thác hàng hóa, kiểm tra số lượng, tình trạng ULD/BULK đúng trên điện FFM thì sau đó ký nhận bàn giao hàng với RAMP
  Nhận hàng từ RAMP thì sẽ khai thác hàng hóa có trên ULD/BULK trong quá trình khai thác sẽ ưu tiên các mặt hàng đặc biệt như COL... thì sẽ tham chiếu quy trình phục vụ hàng tương ứng
  Trong quá trình khai thác sẽ gặp những bất thường:

  - Sai dest, mawb, hawb?
  - Không có mawb?
  - Thiếu hàng so với FFM?
  - Kiện hàng có số awb không khớp với FFM?
  - HAWB không thuộc về MAWB?

  Kiểm đếm số lượng, tình trạng hàng có trong ULD/BULK, lập biên bản bất thường nếu có các trường hợp xảy ra các kiện hàng, scan số master vào handheld, dán barcode vào kiện hàng tương ứng
  Sau khi kiểm đếm xong thì bên bộ phận lái xe sẽ scan barcode để biết được location tương ứng với kiện hàng rồi sẽ move location tương ứng đêu lưu kho
  Sau khi hoàn tất việc khai thác hàng thì IOP sẽ lập các biên bản bất thường để gửi cho Hãng bay và các bên liên quan
