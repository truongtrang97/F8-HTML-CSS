- pc >=1024px
- tablet<1024px & >=740px
- mobile <740px
#### Trường hợp không css được khoảng cách lề cho tablet ( NHỮNG ĐỐI TƯỢNG CON BỊ THÒ RA KHỎI ĐỐI TƯỢNG CHA) cho tablet ta css main { overflow: hidden}---- nhưng không nên sử dụng css ni trừ khi bí
! LINK FILE CÁI NÀO ƯU TIÊN HƠN THÌ LINK PHÍA DỨOI
- thẻ div có thuộc tính overflow mặc định : visible (hiện)
- Phần tử con có phân tư cha có tính chất display : inline hoặc inline block thì phần tử con sẽ bị kế thua chiều ngang của cha nó
- khi cha có thuôc tính block thì con trên dòng sẽ nhảy lung tung ta dung position: absolute để đưa về vị trí cũ // chú ý
- xem lại box-sizing: border-box: kích thước chiều dài rồng có bao gồm phần đềm và border
- text shadow: lm cho chữ có bóng đỗ
- list-style: bỏ dấu chấm trước thẻ li
- <form action="" class="form">
----> khi dùng tới form hay dùng thẻ ni trên đầu trong thẻ form bự
- theo thứ tự ni:
margin-top
margin-right
margin-bottom
margin-left
```
- :ntd child (n) ==>{Bộ chọn: nth-child (n) khớp với mọi phần tử là phần tử con thứ n của phần tử cha của nó.

n có thể là một số, một từ khóa (lẻ hoặc chẵn) hoặc một công thức (như dấu + b).

Mẹo: Nhìn vào bộ chọn: nth-of-type () để chọn phần tử là phần tử con thứ n, cùng loại (tên thẻ), của phần tử cha của nó.}
```
- Thuộc tính line-height chỉ định chiều cao của một dòng.(hình như cách cả dòng trên và dưới 1 số đó)
- @keyframes
```Quy tắc @keyframes chỉ định mã hoạt ảnh.

Hoạt ảnh được tạo ra bằng cách thay đổi dần dần từ một tập hợp các kiểu CSS này sang một tập hợp các kiểu CSS khác.

Trong quá trình hoạt ảnh, bạn có thể thay đổi tập hợp các kiểu CSS nhiều lần.

Chỉ định thời điểm thay đổi kiểu sẽ xảy ra theo phần trăm hoặc với các từ khóa "from" và "to", giống như 0% và 100%. 0% là lúc bắt đầu hoạt ảnh, 100% là khi hoạt ảnh hoàn tất.

```
- chiều cao: 100vh; có nghĩa là chiều cao của phần tử này bằng 100% chiều cao khung nhìn. ví dụ: chiều cao: 50vh; Nếu chiều cao màn hình của bạn là 1000px, thì chiều cao phần tử của bạn sẽ bằng 500px (50% của 1000px
- transparent: trong suốt
- outline : nằm ngoài border (Phần tử này có đường viền màu đen và đường viền màu xanh lục với chiều rộng 10px.)
- phải bỏ dấu gạch dưới chữ trong 1 số trường hợp như nút bấm (text-decoration)
```
- Thuộc tính user-select chỉ định liệu văn bản của một phần tử có thể được chọn hay không.

Trong các trình duyệt web, nếu bạn nhấp đúp vào một số văn bản, nó sẽ được chọn / đánh dấu. Thuộc tính này có thể được sử dụng để ngăn chặn điều này.
```
- canh giữa item trong div dùng text -align : center
- position: fixed : Một phần tử có vị trí: fixed; được định vị so với chế độ xem, có nghĩa là nó luôn ở cùng một vị trí ngay cả khi trang được cuộn. Các thuộc tính trên cùng, phải, dưới cùng và bên trái được sử dụng để định vị phần tử.
- Z-INDEX
```Thuộc tính z-index chỉ định thứ tự ngăn xếp của một phần tử.

Phần tử có thứ tự ngăn xếp lớn hơn luôn đứng trước phần tử có thứ tự ngăn xếp thấp hơn.
```



+ môt số từ:
fadeout: tàn lụi