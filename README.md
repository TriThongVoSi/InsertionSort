InsertionSort hay thuật toán sắp xếp chèn trực tiếp
Mô tả các bước cài đặt
Bước 1:
  +Tạo hàm InsertionSort truyền vào 1 mảng và số lượng phần tử của mảng
    +Vòng lặp for chạy từ 1 đến n, phần tử a[0] luôn đã được sắp xếp
    +Gán phần tử kế a[1] là key phần tử cần chèn
    +gán i-1 là j
      +vòng lặp while với điều kiện dừng là j lớn hơn bằng 0 và phần tử a[j] lớn hơn phần tử key để Di chuyển các phần tử lớn hơn key sang bên phải
      +gán a[j] vào a[j+1]
      +j--
    +gán key vào a[j+1] để Chèn key vào đúng vị trí
Bước 2: Viết hàm in mảng
Bước 3: Hàm main

      
