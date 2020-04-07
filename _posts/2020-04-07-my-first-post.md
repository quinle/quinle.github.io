---
layout: post
title:  "Singular Value Decomposition with explanation and examples"
date:   2020-04-07 3:18:39
categories: jekyll
---

Từ góc độ toán học, Singular Value Decompostion (SVD) đơn giản là một phép phân tích ma trận A(mxn) thành tích của các ma trận U(mxr)x Sigma(rxr) x V(rxn) với Sigma là một ma trận chéo. Vậy tại sao SVD lại có một vai trò thiết yếu trong Toán học và cả Computer Science? Chúng ta bắt đầu xem xét ví dụ sau đây:
(Ví dụ với netflix user và phim)
Với ví dụ này, chúng ta thấy một ứng dụng rõ ràng của SVD là dùng để chia nhóm (mặc dù tên và tính chất của các nhóm đó là unknown). Một ví dụ khác của ứng dụng này là ví dụ tìm topic với fastai, sẽ giới thiệu trong bài sau
Vì sao SVD có hiệu quả? 
Giải thích ý nghĩa ma trận U, Sigma và V

