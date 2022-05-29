# so sánh các phép sắp xếp.

## bubble sort, selection sort, insertion sort, interchage sort.
### Giống:
các thuật toán trên có tốc độ như nhau đều là o(n^2) điểm lợi chung của tất cả là ít tốn không gian lưu trữ và code dễ hiều tuy nhiên chúng vẫn có điểm mạnh và điểm haị khác nhau.

### Khác:
#### bubble sort

Đối với bubble sort thuật toán của hàm này rất dễ hiểu và code nhanh chóng. Tuy nhiên khi 
chạy thì cần thực hiện rất nhiều phép so sánh và swap để sort mảng rất tốn thời gian. 

Hàm này chỉ nên được sử dụng khi mảng đã gần như được sắp xếp và số phần tử của mảng cần sắp xếp không quá lớn.

#### selection sort

Thuật toán này sẽ so sánh và tìm ra phần tử nhỏ nhất để đổi chỗ với vị trí đang xét nên số phép so sánh luôn cố định. Vì thế số phép so sánh của thuật toán rất lớn làm cho thuật toán chạy khá chậm. Nhờ sử dụng nhiều phép so sanh nên ta giảm được số phép swap nên vì thế ta có thể dùng khi hàm swap tốn nhiều thời gian (thường không được sử dụng vì thời gian thực hiện quá lâu)

#### insertion sort

Bản chất của thuận toán này sẽ là dời chỗ lần lượt các phần tử nến có 1 phần tử chèn vào phía trước, thuật toán này sẽ được sử dụng khi mảng gần như đã được sắp xếp vì thuật toán chia mảng cần sort thành 2 phần 1 phần đã sort và 1 phần chưa sort. Tốc độ của thuật toán này tốt hơn so với bubble và selection

#### interchane 

Thuật toán này ít khi được sử dụng trong thực tế vì số phép so sánh và swap qúa lớn. Nó sẽ so sánh số ở vị trí đang xét với tất cả các phần tử đứng sau nó, nếu bé hơn thì swap cũng vì điều đó mà nó ít được sử dụng. Tuy nhiên thuật toán của nó rất đơn giản giúp cho coder có thể tạo ra 1 hàm sort nhanh chóng khi cần.

