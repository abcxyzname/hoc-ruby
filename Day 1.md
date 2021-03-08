08/03/2021 

Day 1 

1.Biến trong ruby: 

Biến cục bộ (local variable): phụ thuộc vào vị trí của biến khi khai báo. 

Biến toàn cục (global variable): được khai báo với tên bắt đầu bằng ký tự $ và biến toàn cục có phạm vi sử dụng trong toàn bộ chương trình. 

Biến đối tượng (instance variable): được bắt đầu bằng ký tự @, nó chỉ thuộc về một đối tượng riêng lẻ hoặc một đối tượng của một lớp. 

Biến lớp (class variable): được bắt đầu bằng ký tự @@, được dùng chung cho tất cả các đối tượng của lớp đó. 

Hằng (constant): giống như một biến, ngoại trừ một điều là giá trị của hằng không đổi trong quá trình chương trình chạy, có sự thay đổi giá trị của Hằng thì trình thông dịch sẽ có thông báo về sự thay đổi đó 

2. Class: 

Class tên đối tượng 

end (tạo ra đối tượng lớp) để dễ dàng thực thi cái yêu cầu riêng với đối tượng 

puts "abcd" .size: lấy ra số lượng kí tự / .downcase : in chuỗi ra chữ thương / .upcase : IN CHỮ RA CHỮ HOA 

puts [1, 2, 3 ,4].include?<số lượng kiểm tra> : kiểm tra có bao nhiêu phần tử / .empty? : kiểm tra có rỗng hay không 

3. String: 

puts : xuống dòng 

puts "" : in chuỗi, 

puts "abc\nxyz" \n là xuống dòng mới 

puts "bbb\raaa" kí tự \r đưa dấu nháy trên màn hình về vị trí đầu dòng 

puts "Joan\b\b\bane" Kí tự \t xóa một kí tự đứng trước nó 

puts "Towering\tinferno" cách một đoạn dài bằng một dấu tab giống như khi chúng ta gõ nút tab 

Nếu muốn in ra cả ký tự \ thì chúng ta đưa vào là \\ 

msg = "chuỗi" 

puts msg[<phần cần lấy trong chuỗi>] : in ra phần cần lấy trong một chuỗi 

puts msg[0] : in ra phần tử đầu tiên của chuỗi tăng 0 lên sẽ in ra các phần tử theo thứ tự 

puts msg[-1] : in ra phần từ cuối của chuỗi tăng lên sẽ in phần tử theo thứ tự 

puts msg[0 , 3] : in ra số phần tử từ vị trí của 0 đến vị trí 3 

puts msg[0..9] : in ra số phần tử từ vị trí 0 đến vị trí 9 không tính dấu cách 

puts msg[3 ,msg.length] : in ra phần tử từ vị trí thứ 4 đến cuối chuỗi 

puts "#{msg}" : truyền biến vào chuỗi  

puts "" + "" : nối chuỗi 

puts "" == "" : so sánh chuỗi 

puts "#{msg.size}" : in ra tổng số lượng phần tử có trong chuỗi 

puts msg. include? "đoạn chuỗi muốn kiểm tra có hay không trong chuỗi" : kiểm tra xem có chuỗi cần tìm hay không 

puts msg.empty? : kiểm tra chuỗi có rỗng hay không 

msg.clear : xóa toàn bộ chuỗi 

puts msg.capitalize : viết hoa ký tự đầu tiên của chuỗi 

puts msg.swapcase : viết hoa toàn bộ kis tự từ kí tự thứ 2 của chuỗi 

puts msg.start_with? "chuỗi cần kiểm tra" : kiểm tra chuỗi có bắt đầu bằng chuỗi này không 

puts msg..end_with? "chuỗi cần kiểm tra" : kiểm tra chuỗi có kết thúc bằng chuỗi này không 

puts msg.inspect : Phương thức inspect sẽ in các ký tự thoát ra luôn chứ không dùng để điều khiển chuỗi nữa 

puts "<chuỗi a> %d <chuỗi b> " % <một số> : đưa số vào thay cho vị trí của %d 

puts "<chuỗi a> %d <chuỗi b> %d <chuỗi c> " % [ số a ,số b ] : đưa số thay vào vị trí của %d theo thứ tự từ số a 

puts "<chuỗi a> %f <chuỗi b> " % <một số> :  

puts " %s " % "chuỗi" :in ra nguyên chuỗi 