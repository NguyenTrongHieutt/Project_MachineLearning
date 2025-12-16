# CAFA-6 – Dự đoán chức năng protein

Dự án này triển khai một **pipeline** để dự đoán **Gene Ontology (GO)** cho protein từ **chuỗi amino acid**, sử dụng **mô hình ngôn ngữ protein ESM-2** và **mạng neural đa nhãn (multi-label classification)**.

Pipeline được xây dựng và chạy trên **Kaggle Notebook**.

---

## Mục tiêu

- Nhận đầu vào là chuỗi protein (FASTA)
- Trích xuất đặc trưng bằng **ESM-2**
- Huấn luyện mô hình dự đoán **đa nhãn GO**
- Sinh file submission đúng định dạng **CAFA-6**

---

## Môi trường

Code được thiết kế để chạy trên **Kaggle**.

---

## Thư viện sử dụng

Python 3

PyTorch

fair-esm (ESM-2)

BioPython

NumPy, Pandas

tqdm

---

## Kiến trúc tổng thể
Chuỗi protein
      ->
ESM-2 (embedding)
      ->
MLP đa nhãn
      ->
Xác suất GO term

---

## Người thực hiện dự án
Họ và tên: Nguyễn Trọng Hiếu.

Mã sinh viên: 23020069.

Lớp học phần: 2526I_INT3405_7.
