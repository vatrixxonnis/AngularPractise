Số ngày Julius có thể tính bởi các công thức sau, sử dụng năm thiên văn (1 TCN là 0, 2 TCN là −1, 4713 TCN là −4712):

a = [(14 - tháng)/ 12]
y = năm + 4800 - a
m= tháng + 12a - 3
Chuyển một ngày trong lịch Gregory (giữa trưa) ra số ngày Julius:

JDN = ngày + [(153m + 2)/5] + 365y + [y/4] - [y/100] + [y/400] - 32045
Chuyển một ngày trong lịch Julius (giữa trưa) ra số ngày Julius:

JDN= ngày + [(153m + 2)/5] + 365y + [y/4] - 32083
Trong các công thức trên [x/y] là phần nguyên của phép chia x/y.

Tính niên kỷ Julius, thêm giờ, phút, giây theo UT:

JD= JDN + (giờ - 12)/24 + phút/1440 + giây/86400
Ngày trong tuần có thể tìm thấy từ số ngày Julius bằng việc tìm số dư trong phép chia cho 7, với 0 nghĩa là thứ 2.

JD mod 7	0	1	2	3	4	5	6
Ngày trong tuần	Thứ 2	Thứ 3	Thứ 4	Thứ 5	Thứ 6	Thứ 7	Chủ nhật

| JD mod 7        | 0     | 1     |  2    | 3     | 4     | 5     | 6        |
| --------------- |:-----:| :---: |:-----:| :---: |:-----:| :----:| :-------:|
| Ngày trong tuần | Thứ 2 | Thứ 3 | Thứ 4 | Thứ 5 | Thứ 6 | Thứ 7 | Chủ nhật |
