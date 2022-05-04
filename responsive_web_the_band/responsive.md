- pc >=1024px
- tablet<1024px & >=740px
- mobile <740px
#### Trường hợp không css được khoảng cách lề cho tablet ( NHỮNG ĐỐI TƯỢNG CON BỊ THÒ RA KHỎI ĐỐI TƯỢNG CHA) cho tablet ta css main { overflow: hidden}---- nhưng không nên sử dụng css ni trừ khi bí
! LINK FILE CÁI NÀO ƯU TIÊN HƠN THÌ LINK PHÍA DỨOI
- thẻ div có thuộc tính overflow mặc định : visible (hiện)
- Phần tử con có phân tư cha có tính chất display : inline hoặc inline block thì phần tử con sẽ bị kế thua chiều ngang của cha nó
- khi cha có thuôc tính block thì con trên dòng sẽ nhảy lung tung ta dung position: absolute để đưa về vị trí cũ // chú ý
- xem lại box-sizing: border-box