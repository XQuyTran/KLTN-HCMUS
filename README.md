# Khóa luận tốt nghiệp - FIT@HCMUS
**Đề tài:** Kết hợp các đối tượng và đặc trưng lân cận cho bài toán phân lớp đa nhãn.

**GVHD:** GS.TS Lê Hoài Bắc

**Thông tin thành viên:**
1. Trần Xuân Quý - [xquytran](https://github.com/XQuyTran)
2. Trần Hữu Chí Bảo - [baocl18ctt2](https://github.com/baocl18ctt2)

## Mô tả đề tài
<p align="justify">
Đề tài tập trung vào bài toán phân lớp trên các tập dữ liệu mà tại đó một đối tượng thường có nhiều hơn 1 nhãn, ví dụ như trong bài toán phân loại văn bản có yêu cầu gán một tập các chủ đề hoặc nhãn khác nhau cho văn bản, hay như bài toán phân loại khung cảnh, tại một búc ảnh có thể có những phân vùng thuộc về các nhãn khác nhau. Trong phạm vi để tài, nhóm coi bài toán phân lớp đa nhãn như là một dạng của hệ thống tư vấn, coi các đối tượng là người dùng, những đặc trưng như là những điểm đánh giá đã biết và thực hiện đề nghị một tập "sản phẩm" nhãn mà đối tượng có thể "thích" - được phân loại. Qua đó nhóm đã áp dụng phương pháp lọc cộng tác dựa trên người dùng và dựa trên đặc trưng của hệ thống tư vấn kết hợp với thuật toán K lân cận gần nhất để cài đặt mô hình phân lớp đa nhãn.
</p>
    
Một số chức năng nhóm đã thử nghiệm và cài đặt với mong muốn nâng cao hiệu quả của mô hình:
- Tìm kiếm K đối tượng tương đồng nhất sử dụng phương pháp xử lý truy vấn theo từng cụm từ và từng tài liệu trong truy hồi thông tin.
- Độ tương đồng cộng hưởng cho mô hình lọc cộng tác dựa trên người dùng.

### Công cụ và thư viện sử dụng
![Python](https://img.shields.io/badge/python-3776AB.svg?&style=for-the-badge&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=%white)
![Numba](https://img.shields.io/badge/numba-E4E6E7.svg?style=for-the-badge&logo=numba&logoColor=blue)

## Tham khảo
- Feremans, L., Cule, B., Vens, C., & Goethals, B. (2020). Combining instance and feature neighbours for extreme multi-label classification. International Journal of Data Science and Analytics, 10(3), 215-231.
- Tan, Z., & He, L. (2017). An efficient similarity measure for user-based collaborative filtering recommender systems inspired by the physical resonance principle. IEEE Access, 5, 27211-27228.
