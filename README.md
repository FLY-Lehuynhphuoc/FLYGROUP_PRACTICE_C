# FLYGROUP_PRACTICE_C
NƠI ĐỂ TEAM LUYỆN TẬP CODE C THÔNG QUA NHỮNG CÂU HỎI ĐƯỢC CẬP NHẬT LIÊN TỤC THEO CHỦ ĐỀ
# PHẦN 1: THE BASIC C 
(để làm được phần này các bạn nên tìm hiểu thêm về conditional statement và loop)

# Câu 1: In ra màn hình dòng chữ Hello FlyGroup!!!

* Yêu cầu: In dòng chữ “Hello World” ra màn hình console.

* Phân tích: Để hiển thị chuỗi kí tự ra màn hình console, bạn dùng hàm printf().

# Câu 2: Chuyển đổi từ nhiệt độ Fahreneit sang Celsius

* Yêu cầu: Chuyển đổi từ nhiệt độ Fahreneit sang Celsius theo công thức:

C = 5*(F - 32) / 9
(C: nhiệt độ C, F: nhiệt độ F)

* Phân tích: 

– Nhập đầu vào từ bàn phím.

– Chuyển đổi từ nhiệt độ F sang nhiệt độ C theo công thức trên

– Hiển thị kết quả ra màn hình

# Câu 3: Tính tổng bình phương của 2 số

* Yêu cầu: Viết chương trình nhập vào 2 số nguyên, sau đó in ra tổng bình phương của chúng.

* Phân tích:

– Nhập vào 2 số nguyên từ bàn phím.

– Tính tổng theo công thức: S = a*a + b*b

# Câu 4: Xác định góc phần tư thứ mấy trên đường tròn lượng giác

* Yêu cầu: Viết chương trình nhập vào số nguyên chỉ số đo độ của một góc và cho biết nó thuộc góc phần tư thứ mấy trên đường tròn lượng giác

* Phân tích:

– Nhập vào số đo lượng giác bất kỳ ( x > 0).

– Xác định cung lượng giác theo điều kiện dưới đây:

Góc phần tư thứ I: (360*k) <= x < (90 + 360*k)

Góc phần tư thứ II: (90 + 360*k) <= x < (180 + 360*k)

Góc phần tư thứ III: (180 + 360*k) <= x < (270 + 360*k)

Góc phần tư thứ III: (270 + 360*k) <= x < 360*(k+1)

(k = 0, 1, 2,...)

# Câu 5: Tính tổng nguyên: S = 1 + 1/2 + 1/3 + 1/4 +… 1/n

* Yêu cầu: Nhập số tự nhiên n rồi tính tổng (lưu ý phép chia các số nguyên): S = 1 + 1/2 + 1/3 + 1/4 +... 1/n ( n khác 0)

* Phân tích:

– Nhập vào số nguyên dương n (n > 0)

– Dùng vòng lặp for() để tính tổng S

# Câu 6: Tìm giá trị lớn nhất của 2 số

* Yêu cầu: Hãy nhập 2 số thực a,b. Tìm giá trị lớn nhất của chúng và gán giá trị lớn nhất đó cho biến max

* Phân tích:

– Cách 1: dùng câu lệnh if/else để tìm giá trị lớn nhất

– Cách 2: định nghĩa macro tìm giá trị lớn nhất

# Câu 7: Tìm giá trị lớn nhất của 4 số a,b,c,d

* Yêu cầu: Tìm giá trị lớn nhất của 4 số a, b, c, d

* Phân tích:

– Nhập 4 số a, b, c, d từ bàn phím

– Tìm giá trị lớn nhất

– Trong bài viết tìm giá trị lớn nhất của 2 số, mình đã viết hàm max(float a, float b) để tìm giá trị lớn nhất của 2  số.

# Câu 8: Kiểm tra sự tồn tại của 1 tam giác

* Yêu cầu: Ba số dương a, b, c là độ dài các cạnh của một tam giác nếu tổng của 2 số bất kỳ lớn hơn số còn lại. Nhập 3 số a, b, c và kiểm tra xem chúng có thể là độ dài của các cạnh của một tam giác hay không.

* Phân tích:

– Nhập 3 số nguyên dương

– Điều kiện để 1 tam giác tồn tại là: tổng 2 cạnh bất kì luôn lớn hơn cạnh còn lại.

# Câu 9: Giải phương trình bậc nhất

* Yêu cầu: Giải phương trình bậc nhất

* Phân tích: 

– Phương trình bậc nhất: ax + b = 0 (a # 0)

– Nghiệm của phương trình: x = – b/a

# Câu 10: Giải phương trình bậc hai

* Yêu cầu: Viết chương trình giải phương trình bậc hai.

* Phân thích: 

– Phương trình bậc 2: ax2 + bx + c = 0

– Giải phương trình theo công thức delta = b2 – 4ac

# Câu 11: Tìm ước số chung và bội số chung nhỏ nhất của 2 số a,b

* Yêu cầu: Viết chương trình giải phương trình bậc hai.

* Phân thích: 

– Phương trình bậc 2: ax2 + bx + c = 0

– Giải phương trình theo công thức delta = b2 – 4ac

# Câu 12: Tách các chữ số thuộc hàng trăm, hàng chục, hàng đơn vị

* Yêu cầu: Viết chương trình nhập vào số nguyên 3 chữ số (từ 100 – 999), sau đó in ra các chữ số thuộc hàng trăm, hàng chục, hàng đơn vị

* Phân tích: 

– Nhập vào số nguyên (100 <= x <= 999).

– số hàng trăm = x / 100, số hàng chục = (x%100)/10, số hàng đơn vị = (x%100)%10

# Câu 13: In ra số Hex của số nguyên dương tương ứng

* Yêu cầu: Viết chương trình nhập vào một số nguyên dương không dấu, rồi in ra số Hex tương ứng.

* Phân tích: 

–  Để in ra mã Hex của số nguyên dương, ta dùng định dạng %x

# Câu 14: Tìm số Amstrong

* Yêu cầu: Tìm số Amstrong là một số có đặc điểm sau: số đó gồm n chữ số, tổng các lũy thừa bậc n của các chữ số đó và số đó.

Ví dụ: 153 = 1^3 + 5^3 + 3^3. Hãy tìm các số Amstrong nhỏ hơn 1000.

* Phân tích: 

– Dùng vòng lặp để kiểm tra điều kiện của sô Amstrong.

# Câu 15: Tính giai thừa số nguyên dương

* Yêu cầu: Tính giai thừa của số nguyên dương N.

* Phân tích: 

– Dùng đệ quy

# Câu 16: Tính giai thừa cách

* Yêu cầu: Viết chương trình tính n!!. Biết rằng n!! = 1.3.5..n nếu n lẻ, và n!! = 2.4.6…n nếu chẵn.

* Phân tích: 

– Dùng đệ quy

# Câu 17: Tính diện tích, chu vi tam giác, đường tròn, hcn

* Yêu cầu: Tính diện tích và chu vi các hình: tam giác, chữ nhật, tròn.

* Phân tích:

- Diện tích tam giác: S = căn bậc 2[P*(P/2 - a)*(P/2 - b)*(P/2 - c)/2]    (a, b, c là các cạnh, P: chu vi tam giác)

- Chu vi tam giác: P = a + b + c

- Diện tích hình tròn: S = 2*PI*R*R    (R: bán kính, PI = 3.14)

- Chu vi hình tròn: P = 2*PI*R

- Diện tích chữ nhật: S = a * b (a, b: là 2 cạnh của hình chữ nhật)

- Chu vi chữ nhật: P = (a + b)*2

# Câu 18: Kiểm tra số N có phải là số nguyên tố không?

* Yêu cầu: Viết chương trình kiểm tra xem số N có phải là số nguyên tố không?

* Phân tích: 

– Số nguyên tố là số chỉ chia hết cho chính nó và 1.

Ví dụ: 1, 3, 5, 7, 11, 13,… là số nguyên tố

– Nếu (N%i == 0) với mọi i = ( 2 – N/2) thì N là số nguyên tố.

# Câu 19: Liệt kê các số nguyên tố nhỏ hơn N

* Yêu cầu: Viết chương trình liệt kê tất cả các số nguyên tố nhỏ hơn giá trị N nhập từ bàn phím.

* Thuật toán:

– Viết hàm kiểm tra số nguyên tố

– Dùng vòng lặp để in ra các số nguyên tố

# Câu 20: Tìm số hoàn hảo

* Yêu cầu: Một số hoàn hảo là một số có tổng các ước số của nó bằng chính số đó. Hãy tìm số hoàn hảo nhỏ hơn 5000. 

Ví dụ: 6 có các ước số là 1, 2, 3 và 6 = 1 + 2 + 3.

* Phân tích:

– Tìm các ước số của số đó. Sau đó tính tổng các ước số.

– So sánh tổng các ước số với số đó. In kết quả ra màn hình.

# Câu 21: In dãy số Fibonanci

* Yêu cầu: Viết chương trình in dãy số Fibonanci nhỏ hơn giá trị N. Biết rằng:

f(0) = f(1) = 1

f(n) = f(n – 1) + f(n – 2)

* Phân tích:

– Cách 1: dùng đệ quy

– Cách 2: dùng công thức f(n) = f(n – 1) + f(n – 2)

# Câu 22: Tính cước taxi

* Yêu cầu: Viết chương trình tính tiền cước TAXI. Biết rằng:

– Km đầu tiên là 5000đ

– 30Km tiếp theo là 4000đ

– Nếu lớn hơn 30Km thì mỗi Km thêm ra sẽ phải trả là 3000đ

– Hãy nhập số Km sau đó in ra số tiền phải trả.

* Phân tích:

– Dùng lệnh if để chia các mức giá khác nhau.

# Câu 23: Giải hệ phương trình bậc nhất

* Yêu cầu: Viết chương trình giải hệ phương trình bậc nhất:

– ax + by = c

– dx + ey = f

* Phân tích:

– Nghiệm của hệ: x = Dx/D, y = Dy/D ( trong đó: D = ae – bd, Dx = ce – bf, Dy = af – cd)

# Câu 24: In ra bảng cửu chương

* Yêu cầu:

Viết chương trình in ra bảng cửu chương từ 2 đến 9

* Phân tích:

– Dùng vòng lặp for()

# Câu 25: Tính sinx

* Yêu cầu: Lập chương trình tính sin(x) với độ chính xác 0.0001 theo công thức:

sin(x) = x – x^3/3! + x^5/5! – …+(-1)^n.x^(2n+1)/(2n+1)!

# Câu 26: Tính cosx

* Yêu cầu: Nhập một số c>0 (ví dụ c = 0.0001) và một số thực x rồi tính: 

cos(x)= 1 – x^2/2! + x^4/4! – …+(-1)^n.x^(2n)/(2n)!

Tổng được tính với n đủ lớn sao cho bất đẳng thức: |x^(2n)/(2n)!| <= c thỏa mãn

# Câu 27: Tính e mũ x

* Yêu cầu: Nhập 1 số c > 0 (sai số) và 1 số thực x rồi tính : 

e^x = 1 + x/1! + x^2/2! + …+x^n/n!

Tổng được tính với n đủ lớn sao cho |x^n/n!| < c thỏa mãn.

* Phân tích:

– Tương tự như tính sinx, cosx, chúng ta sử dụng vòng lặp for() để giải quyết bài toán này.

# Câu 28: Tính hằng số PI = 3.14

* Yêu cầu: Tính PI với sai số 0.0001 theo công thức: PI/4 = 1 – 1/3 + 1/5 – 1/7 +…

* Phân tích:

– Dùng vòng lặp for().

– PI/4 = ∑(1 + ((-1)n/(2n+1)))

# Câu 29: Hiển thị tam giác pascal

* Yêu cầu: Viết chương trình in ra tam giác Pascal:

1
1 1
1 2 1
1 3 3 1
…..

* Phân tích: Chúng ta nhận thấy quy luật như sau:

Hàng 1: 1 số

Hàng 2: 2 số

…

Số hạng đầu và cuối của mỗi hàng đều bằng 1. Số hạng ở giữa bằng tổng 2 số hạng hàng trên cộng lại.

– Hàng 3: 2 = 1 + 1

– Hàng 4: 3 = 1 + 2, 3 = 2 + 1.

…

# Câu 30: Hiển thị hình sao

* Yêu cầu: Dùng vòng lặp for, in ra màn hình các hinh vẽ sau:

1

*

**

***

****

*****

2

*****

****

***

**

*

3

*********

*********

*********

*********

*********

4

*

**

***

****

*****

*****

****

***

**

*

5

    *
    
   **
   
  ***
  
 ****
 
*****

6

      *
      
     ***
     
    *****
    
   *******
   
  *********
  
   *******
   
    *****
    
     ***
     
      *
      
# Câu 31: Chuyển đổi từ số la mã sang số thập phân

Bảng số la mã và một số quy tắc chuyển đổi.

1. Bảng số la mã

I   V   X   L   C   D   M

1   5   10  50  100 500 1000

2. Quy tắc chuyển đổi

a/ Số thập phân được cấu thành từ các chữ số đơn lẻ. Ví dụ: 1989 được ghép bởi 1,9,0,8. Còn đối với cách biểu diễn chữ số la mã thì mỗi chữ số khác 0 ở mỗi hàng ( hàng đơn vị, hàng chục, hàng trăm,…) sẽ được biểu diễn bởi 1 kí tự số la mã. 1000 = M, 900 = CM, 0 không được biểu diễn, 8 = VIII. 1908 = MCMVIII

b/ “I”, “X”, “C”, “M” có thể được xuất hiện liên tiếp (cạnh nhau) tối đa 3 lần. Tuy nhiên, các kí tự này có thể xuất hiện nhiều hơn. (Ví dụ: XXXIX). Các kí tự “D”, “L”, “V” không được phép lặp lại.

c/ Chữ số đi sau chữ số khác lớn hơn hoặc bằng thì cộng thêm vào:

VI = V + I = 5 + 1 = 6

LX = L + X = 50 + 10 = 60

XX = X + X = 10 + 10 = 20

Chữ số đi trước chữ số khác lớn hơn thì trừ bớt đi:

IV = V – I = 5 – 1

XL = L – X = 50 – 10 = 40

“I” chỉ có thể bị trừ bởi “V”, “X”. ( IV = V – I = 5 – 1 = 4, IX = X – I = 10 – 1 = 9)

“X” chỉ có thể bị trừ bởi “C”, “L”. ( XC = 100 – 10 = 90, XL = 50 – 10 = 40)

“C” chỉ có thể bị trừ bởi “D” và “M”. (CD = 500 – 100 = 400, CM = 1000)

“V”, “L”, “D” không bao giờ bị trừ.

d/ Nếu thêm 1 dấu gạch ngang trên đầu thì giá trị của nó bằng giá trị hiện tại nhân với 1000

# Câu 32: Hàm swap

* Yêu cầu:

– Khai báo 2 biến được gán giá trị ban đầu.

– Viết hàm đổi chỗ giá trị của 2 biến cho nhau

* Phân tích:

– Ta viết hàm với tham số truyền vào là 2 biến được khai báo. Như các bạn đã biết, nếu truyền tham trị, sẽ không thể thay đổi giá trị của chúng được. Muốn thay đổi được giá trị của 2 biến truyền vào, chúng ta cần truyền tham biến (con trỏ + tham chiếu).

# Câu 33: Tính tổng các chữ số trong 1 số

* Yêu cầu:

Tính tổng các chữ số trong 1 số.

Ví dụ: số 1234 có tổng S = 1 + 2 + 3 + 4 = 10

* Phân tích:

– Dùng phép chia hết / và phép chia có dư % để tách từng chữ số từ hàng đơn vị, hàng chục, …

# Câu 34: Đổi từ hệ nhị phân sang hệ thập phân

* Yêu cầu: Chuyển từ số nhị phân sang thập phân.

# Câu 35: Đổi từ hệ thập phân sang nhị phân

* Yêu cầu: Chuyển từ số nhị phân sang thập phân.

# Câu 36: Kiểm tra năm nhuận

* Yêu cầu: Viết hàm kiểm tra năm nhuận.

* Phân tích: Năm nhuận là năm chia hết cho 400 hoặc chia hết cho 4 nhưng không chia hết cho 100.

# Câu 37: Kiểm tra số đối xứng hay không?

* Yêu cầu: Số đối xứng hay còn gọi là “palindrome”. Ví dụ: 

123321 là số đối xứng, 12012 không phải số đối xứng.

* Phân tích: Đảo các chữ số của số đầu vào. Nếu giá trị của số trước và sau khi đảo bằng nhau thì đó là số đối xứng.

# Câu 38: Đảo ngược các chữ số trong 1 số

* Yêu cầu:

– Nhập vào 1 số nguyên

– Đảo ngược các chữ số trong số nguyên đó.

* Phân tích:

– Dùng phép chia hết / và phép chia có dư % để tách từng chữ số ra.
