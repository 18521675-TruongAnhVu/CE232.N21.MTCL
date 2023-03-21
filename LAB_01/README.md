# CE232.N21.MTCL - Nhom 04

Nguyễn Chí Thiện – 20521948

Đào Ngọc Minh Trí – 20522045

Nguyễn Mạnh Tấn – 19522173

Trương Anh Vũ –18521675

<hr>

WOKWI: https://wokwi.com/projects/359789079553860609

DEMO: https://youtu.be/H5kV2IRDVTE

Giải thích code:
* Tạo hàm setup()

  * Mở port ở mức 115200
  * thiết đặt chân 18 là OUTPUT
  * thiết đặt chân 21 là OUTPUT
  * Ghi giá trị mặc định LOW vào chân 21

* Tạo vòng lặp loop() để chạy chương trình
  * Dừng trong 1 giây
  * Ghi giá trị ON vào chân 8 -> Bật đèn led
  * In ra màn hình "ON"
  * Dừng trong 1 giây
  * Ghi giá trị OFF vào chân 8 -> Tắt đèn led
  * In ra màn hình "OFF"
 
 * Lặp lại
