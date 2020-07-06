# Fun-Math
FunMath là một game giúp rèn luyện trình độ tính toán của bạn. Tựa game rất phù hợp với học sinh tiểu học, giúp các bạn luyện tập hiệu quả những kiến thức trên trường học.

# I. Tổng quát về game
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
    
# II. Dữ liệu trong game

  Với độ khó Normal, người chơi sẽ làm các phép tính từ 1-10. 
  Với độ khó Hard, người chơi sẽ làm các phép tính từ 10-100.
  Tuy nhiên dữ liệu này có thể dễ dàng thay đổi trong mã nguồn.
  ![alt text](https://github.com/vinhdt912/Fun-Math/blob/master/Images/Data.png)
  Với X và Y là 2 số cần thực hiện phép tính. A, B, C, D là các đáp án của phép tính. Chỉ cần thay đổi khoảng random của các số đó là sẽ thay đổi dữ liệu của toàn bộ các số.
  Đối với phép chia và phép nhân có một phần đặc biệt hơn nên sẽ phải thay đổi thêm một chút nữa.
  ![alt text](https://github.com/vinhdt912/Fun-Math/blob/master/Images/Data_2.png)
  Với phép nhân thì khoảng đáp của nó sẽ lớn lên. Còn đối với phép chia thì X phải chia hết cho Y nên sẽ random đáp án ở khoảng nhỏ phù hợp hơn.

# III. Công nghệ sử dụng

  Tựa game được tạo thành dựa trên nền tảng GDevelope5, Figma để tạo hình ảnh.
