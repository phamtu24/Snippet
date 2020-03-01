## HƯỚNG DẪN SỬ DỤNG REACT NATIVE SNIPPET

1. **Cài đặt**

* Mở VSCODE, ấn tổ hợp phím Command + Shift + P (MAC), Ctrl + Shift + P (WIN)
* Gõ "snippet" và chọn Configure User Snippets
* Chọn ngôn ngữ Javascript
* Copy tất cả trong file snippet.json và dán vào file javascript.json vừa hiện ra
* Save file và sử dụng

2. **Cách dùng trong từng file**  

Để dùng snippet, gõ theo các prefix dưới đây, chờ Vscode gợi ý rồi nhấn Enter. 
Khai báo từng thành phần cần thiết, nhấn Tab để chuyển qua thành phần tiếp theo cần khai báo 

#### Api.js
* apiGetCrt : Khai báo hàm get api 
* apiPostCrt : Khai báo hàm post api 

#### Redux/action/type.js
* reduxAct : Khai báo type cho action thông thường 
* sagaAct : Khai báo type cho saga action 

#### Redux/action/index.js
* reduxActCrt : Khai báo hàm tạo action

#### Redux/reducers/
* reduxRdc : Khai báo reducer thông thường 
* sagaRdc : Khai báo saga reducer 

#### Redux/sagas/NetworkSaga.js
* sagaCrt : Khai báo saga 

#### Khác 
* reduxConnect: Khai báo redux connect 
