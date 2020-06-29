# Fun-Math
Dự án được hoàn thành dựa trên platform GDevelope 5. Hình ảnh tự design trên figma - có ý tưởng hình ảnh dựa trên game FunMath. Phần âm thanh có thể tìm thấy trên web.

Link sản phẩm: https://games.gdevelop-app.com/game-7ff7409c-95b4-41e0-8029-760519852e09/index.html

Nên chơi lại 2 - 3 lần để Game load hết tài nguyên sẽ không bị giật lag.

FunMath là một game toán vui nhộn - giúp cho việc tính toán của bạn trở nên nhanh nhẹn hơn.

I. Tổng quát về game
  1. Menu
    ![alt text](https://github.com/vinhdt912/Fun-Math/blob/master/Images/Menu.png)
    Menu sẽ có 3 chức năng: 
    - Chọn chế độ chơi
    - Chọn độ khó khi chơi
    - Bật tắt âm thanh game
  2. Độ khó game
    ![alt text](https://github.com/vinhdt912/Fun-Math/blob/master/Images/Difficult.png)
    Khi vào game sẽ mặc định độ khó trước là Normal, sau đó tuỳ vào người chơi muốn thay độ khó.
  3. Chế độ chơi
    ![alt text](https://github.com/vinhdt912/Fun-Math/blob/master/Images/Mode.png)
    Game sẽ có 5 chế độ khác nhau: cộng - trừ - nhân - chia - hỗn hợp.
  4. Chơi game
    ![alt text](https://github.com/vinhdt912/Fun-Math/blob/master/Images/Play.png)
    Với mỗi chế độ chơi khác nhau game sẽ random ra một phép tính bất kì tương ứng với chế độ chơi mà người chơi đã chọn từ trước. Khi qua 1 câu sẽ tính tăng lên một điểm. Game không giới hạn số điểm chơi. Với mỗi một phép tính người chơi sẽ có 5s để trả lời câu hỏi. Khi số điểm của người chơi vượt qua 20 thời gian của mỗi màn sẽ còn là 3s. Mỗi khi đạt được điểm cao mới game sẽ hiện ra một màn hình thông báo.
    
II. Dữ liệu trong game
  Với độ khó Normal, người chơi sẽ làm các phép tính từ 1-10. 
  Với độ khó Hard, người chơi sẽ làm các phép tính từ 10-100.
  Tuy nhiên dữ liệu này có thể dễ dàng thay đổi trong mã nguồn.
  ![alt text](https://github.com/vinhdt912/Fun-Math/blob/master/Images/Data.png)

III. Công nghệ sử dụng
  Tựa game dựa trên nền tảng của một platform GDevelope5 để tạo game, Figma để design.
