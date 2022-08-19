- icon : vào trang themify icons
- cursor: thay đổi kí hiệu chuột 
- float: bỏ đi thuộc tính dislay: inline- block
- position: fixed -> đè lên trên cùng tất cả phần ở dưới (....)
- font-weight : độ dày của chữ
- line-height: 1.4 (khoảng cách các dòng trong đoạn văn tiếng anh)
- line-height: 1.6 (khoảng cách các dòng trong đoạn văn tiếng việt)
- thẻ div có tính chất block luôn bắt đầu trên 1 dòng mới
- dùng hàm chia calc.
- border radius: bo góc.
- dùng float cho thẻ con thì thẻ cha thường bị đẩy hẹp lại -< dùng clear: both (cách2 dùng overflow: hidden)
- opacity: 1: độ mờ của chữ
- __một thẻ có tính chất inline thêm float vào thành thẻ block có thể dùng magin âm__
- text decoration : bỏ gạch chân
- cai auto rename tag (vs code tu dong)
- list-style-type:none




### xem lại

border box
position: fixed

## lỗi hay sai: viết đóng thẻ div thiếu, thiếu dấu . hoặc #

@LAM LAI ĐOẠN CODE NI CHO NHỚ()
```
 <html> <script> 
      const buyBnts =document.querySelectorAll('.js-buy-ticket') //goi han ra
      const modal =document.querySelector('.js-modal')
      const modalclose =document.querySelector('.js-modal-close-btn')
      //hàm hiên thi modal mua vé(thêm class open vào modal)
      function showbuytickets(){
      modal.classList.add('open')
      }
      //hàm ẩn modal mua vé( gỡ bỏ class open của modal)
      function hidebuytickets(){
      modal.classList.remove('open')
      }
      //Lặp qua từng thẻ button và nghe hành vi kích
      for(const buyBnt of buyBnts) //nge lenh user
      {
        buyBnt.addEventListener('click',showbuytickets)
      }
      // Nghe hành vi kích vao button close
      modalclose.addEventListener('click',hidebuytickets)
  </script>
  </html>

```