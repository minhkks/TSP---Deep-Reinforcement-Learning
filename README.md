# TSP---Deep-Reinforcement-Learning

Tối ưu tổ hợp là một lớp bài toán trong lĩnh vực khoa học máy tính với nhiều ứng dụng cụ thể trong
đời sống như những bài toán tìm đường đi ngắn nhất, bài toán Knapsack,... Một ví dụ điển hình cho các
bài toán tối ưu tổ hợp đó là bài toán Traveling Saleman (TSP). Việc tìm kiếm lời giải tối ưu cho bài toán
TSP là bài toán thuộc lớp NP − hard [12], kể cả trong trường hợp trọng số giữa các đỉnh trong đồ thị
được tính bằng khoảng cách Euclide.
Hiện nay có rất nhiều giải thuật từ giải thuật chính xác đến các giải thuật heuristic để giải bài toán
TSP, trong báo cáo này tác giả xin phép trình bày một hướng tiếp cận giải bài toán TSP và TSP đa mục
tiêu thông qua phương pháp Học tăng cường Reinforcement Learning và kết hợp với các mạng neural của
Học sâu Deep Learning. Bằng việc xây dựng mô hình dựa trên Học tăng cường và Học sâu, mô hình tối
ưu sau qua trình huấn luyện sẽ có thể đưa ra lời giải tối ưu cho các bộ dữ liệu khác mà không cần tốn
chi phí và thời gian huấn luyện lại. Các kết quả thực nghiệm đã cho thấy kết quả vô cùng tốt của hướng
tiếp cận này.
Báo cáo này sẽ trình bày mô hình giải bài toán TSP đa mục tiêu (MOTSP) bằng phương pháp Deep
Reinfocement Learning [9] thông qua việc chia nhỏ bài toán ban đầu thành N bài toán vô hướng con và
kết hợp nghiệm tối ưu của N bài toán con đó sẽ tìm được Pareto Front của bài toán ban đầu. Báo cáo sẽ
trình bày cụ thể kiến trúc mạng được sử dụng để giải bài toán MOTSP đó là Pointer Network và đồng
thời sẽ tiến hành cài đặt mô hình và tiến hành so sánh giữa Pointer Network với thuật toán chính xác
giải bằng quy hoạch động cũng như giải thuật tiến hóa đa mục tiêu giải bài toán MOTSP
