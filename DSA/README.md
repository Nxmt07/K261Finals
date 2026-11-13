# TỔNG HỢP TOÀN DIỆN KIẾN THỨC CẤU TRÚC DỮ LIỆU VÀ GIẢI THUẬT (DATA STRUCTURES & ALGORITHMS)
## TÀI LIỆU ÔN TẬP VÀ ĐỐI CHIẾU NỘI DUNG THI CUỐI KỲ (FINAL EXAM COMPREHENSIVE GUIDE)

> **Môn học:** Cấu trúc Dữ liệu và Giải thuật (Data Structures and Algorithms - CO2003)  
> **Khoa:** Khoa học & Kỹ thuật Máy tính (Faculty of Computer Science and Engineering - CSE) - Trường Đại học Bách Khoa, ĐHQG TP.HCM (HCMUT)  
> **Giảng viên biên soạn & Phụ trách:**  
> - TS. Lê Thanh Sách (ltsach@hcmut.edu.vn)  
> - Quý Thầy/Cô Bộ môn Khoa học Máy tính - CSE, HCMUT  
> **Giáo trình & Tài liệu tham khảo cốt lõi:**  
> 1. *Data Structures and Algorithm Analysis in C++*, 4th Edition – Mark Allen Weiss, Pearson (2014).  
> 2. *Data Structures: A Pseudocode Approach with C++*, 2nd Edition – Richard F. Gilberg & Behrouz A. Forouzan, Cengage Learning (2005).  
> 3. *Data Structures and Program Design in C++*, Robert L. Kruse & Alexander J. Ryba, Prentice Hall (1999).  
> 4. *Introduction to Algorithms* (CLRS), 3rd/4th Edition – Cormen, Leiserson, Rivest, Stein, MIT Press (2009/2022).  
> 5. *Self-Adjusting Binary Search Trees* – Daniel D. Sleator & Robert E. Tarjan, *Journal of the ACM*, 32(3):652–686 (1985).  
> 6. *Modern B-Tree Techniques* – Goetz Graefe, *Foundations and Trends in Databases*, 3(4):203–402 (2011).  
> **Thư mục tài liệu gốc:** `C:\Users\Admin\Documents\K261\Finals\DSA\`  
> **Danh mục toàn bộ 20 tài liệu slide & chuyên đề bài giảng trong thư mục:**
> - `1.Intro/`:
>   - `01-intro.pdf` (23 slide): Giới thiệu đề cương môn học, chuẩn đầu ra, cấu trúc điểm, ngôn ngữ C++11/14/17 và giáo trình tham khảo.
>   - `02-programming.pdf` (57 slide): Ôn tập lập trình C++ nâng cao: Con trỏ, Cấp phát động `new`/`delete`, OOP, Bản sao nông vs sâu (Shallow vs Deep Copy), Tính đa hình `virtual`/`override`, Khuôn mẫu (Templates), Ngoại lệ (Exceptions), Đệ quy & Call Stack, Bài toán Tháp Hà Nội.
>   - `03-complexity.pdf` (60 slide): Phân tích độ phức tạp: Mô hình RAM, Best/Average/Worst case, Đếm thao tác nguyên thủy, Ký pháp tiệm cận ($O, \Omega, \Theta, o, \omega$), Phân tích vòng lặp & chuỗi tổng, Phân tích hệ thức truy hồi (Unrolling, Recursion Tree, Master Theorem).
> - `2.List/`:
>   - `2.1. Lists__P_1_.pdf` (73 slide): Danh sách tuyến tính, List ADT (`IList`), Danh sách mảng động (`ArrayList`), Chiến lược tự động tăng dung lượng (Capacity Doubling), Danh sách liên kết đơn (`SLinkedList`), Thao tác thêm/xóa/truy xuất, Đảo ngược danh sách, Đánh giá ưu nhược điểm.
>   - `2.2. Lists__P_2_.pdf` (107 slide): Danh sách liên kết đôi (`DLinkedList`), Danh sách liên kết vòng (`CircularLinkedList`), Danh sách đa liên kết (`MultilinkedList`), Ma trận thưa, Ngăn xếp (`Stack` - LIFO), Hàng đợi (`Queue` - FIFO), Hàng đợi vòng (`CircularQueue`), Ứng dụng: Ngoặc hợp lệ, Ký pháp Ba Lan, Shunting-Yard, Định tuyến.
> - `3.Sorting/`:
>   - `3. Sorting.pdf` (60 slide): Khái niệm phân loại sắp xếp (Stable/Unstable, In-place, Comparison-based), Straight Insertion Sort, Shell Sort (dãy bước nhảy), Straight Selection Sort, Bubble Sort, Cocktail Shaker Sort, Merge Sort (Chia để trị & Trộn danh sách).
>   - `quicksort.pdf` (54 slide): Chuyên sâu Quick Sort (Kruse & Ryba): Phân hoạch với con trỏ `too_big_index` và `too_small_index`, Chọn pivot, Phân tích trường hợp tốt nhất $O(n \log n)$, Xấu nhất $O(n^2)$, Tối ưu hóa đệ quy đuôi, Introsort.
> - `4.Hashing/`:
>   - `4. Search-Hash.pdf` (68 slide): Thuật toán tìm kiếm tuần tự & nhị phân, Tìm kiếm nội suy (Interpolation Search), Cấu trúc Bảng băm (Hash Table), Hàm băm (Chia modulo, Bình phương giữa, Gấp, Rút trích số, Xoay vòng), Giải quyết va chạm: Địa chỉ mở (Linear, Quadratic, Double Hashing, Key Offset), Nối kết riêng biệt (Separate Chaining), Hệ số tải $\alpha$, Xóa phần tử & Tái băm (Rehashing).
> - `5.Tree/`:
>   - `5.1 Tree_concept.pdf` (63 slide): Khái niệm cây tổng quát, Cây nhị phân (Full, Complete, Perfect, Balanced), Tính chất toán học, Phép duyệt cây (NLR, LNR, LRN, Level-order), Cây biểu thức, Cây tìm kiếm nhị phân (BST) - Tra cứu, Chèn, Xóa 3 trường hợp.
>   - `5.2 Balanced_Trees.pdf` (103 slide): Cây cân bằng AVL, Hệ số cân bằng $BF \in \{-1, 0, 1\}$, 4 phép quay (LL, RR, LR, RL), Thuật toán chèn & xóa AVL, Cây Splay (Sleator & Tarjan) - Thao tác Splay (Zig, Zig-Zig, Zig-Zag), Phân tích Amortized $O(\log n)$.
>   - `AVL-Btree.pdf` (82 slide): Cây AVL (Bài giảng chi tiết TS. Lê Thanh Sách), Cây tìm kiếm đa phân ($m$-way), Cây B (B-Tree bậc $M$) - Cấu trúc node, Ràng buộc khóa/con, Tách node (Split), Mượn khóa (Borrow) & Hợp nhất (Merge).
>   - `SplayTree.pdf` (15 slide): Tóm lược trực quan hóa các phép biến đổi cây Splay.
>   - `ref/9781601984838-summary.pdf` (23 slide): Tài liệu chuyên khảo *Modern B-Tree Techniques* (Goetz Graefe): Tối ưu hóa bộ nhớ đệm, Concurrency (Latch coupling / crabbing), B-link trees.
>   - `ref/btrees.pdf` (16 slide): Tài liệu CMSC 420 (Justin Wyss-Gallifent): Định nghĩa hình thức Cây B, Chiều cao, Tách/Gộp, Cây B+ và đánh chỉ mục cơ sở dữ liệu.
>   - `ref/self-adjusting.pdf` (35 slide): Công trình gốc của Sleator & Tarjan (JACM 1985): Lý thuyết cây tự điều chỉnh, Phân tích hàm thế năng (Potential Function Method).
> - `6.Heap/`:
>   - `6. Heap.pdf` (48 slide): Cấu trúc Đống (Heap Definition), Biểu diễn mảng hoàn chỉnh, Giải thuật `reheapUp` & `reheapDown`, Thêm & Xóa node, Xây dựng đống Floyd Bottom-Up $O(n)$, Thuật toán Heap Sort, Hàng đợi ưu tiên (Priority Queue), Bài toán chọn phần tử cực trị thứ $k$.
> - `7.Graph/`:
>   - `01-graph-repr.pdf` (86 slide): Khái niệm đồ thị hình thức, Đồ thị có hướng/vô hướng, Bậc, Định lý bắt tay, 4 phương pháp biểu diễn (Ma trận kề, Danh sách kề, Danh sách cạnh, CSR), Ánh xạ nhãn đỉnh sang ID số nguyên.
>   - `02-graph-algorithm-part1.pdf` (97 slide): Duyệt đồ thị DFS (Phân loại 4 loại cung, Chu trình, Khử đệ quy), BFS (Cây BFS, Đường đi ngắn nhất không trọng số), Sắp xếp Tô-pô (Topological Sort: Thuật toán Kahn hàng đợi vs Thuật toán DFS).
>   - `02-graph-algorithm-part2.pdf` (95 slide): Đường đi ngắn nhất nguồn đơn (SSSP): Dijkstra (trọng số không âm), Bellman-Ford (trọng số âm, phát hiện chu trình âm), Đường đi ngắn nhất trên DAG, Đường đi ngắn nhất mọi cặp đỉnh (APSP): Floyd-Warshall. Cây khung nhỏ nhất (MST): Tính chất Cut/Cycle, Thuật toán Kruskal (DSU / Union-Find) & Thuật toán Prim.
>   - `02-graph-algorithm-part3.pdf` (54 slide): Thành phần liên thông (CC vô hướng), Thành phần liên thông mạnh (SCC có hướng: Kosaraju 2-pass vs Tarjan 1-pass), Kiểm tra đồ thị hai phía (Bipartite Checking - 2-Coloring), Ghép cặp cực đại trên đồ thị hai phía (Maximum Bipartite Matching - MBM, Bổ đề Berge, Ford-Fulkerson).

---

## 🗺️ BẢN ĐỒ KIẾN THỨC & MA TRẬN NỘI DUNG THI CUỐI KỲ

| STT | Phần kiến thức | Chủ đề cốt lõi | Mức độ trọng tâm | Trọng số đề thi | Dạng bài tập & Câu hỏi kinh điển trong đề thi HCMUT |
| :---: | :--- | :--- | :---: | :---: | :--- |
| **I** | **Nền tảng C++ & Độ phức tạp** | Con trỏ, Bộ nhớ, Vòng lặp, Hệ thức đệ quy, Ký pháp Big-O | ⭐⭐⭐⭐ | 10% - 15% | - Phân tích đầu ra đoạn mã C++ (con trỏ, virtual, destructor, copy constructor).<br>- Tính số thao tác nguyên thủy & tìm $\Theta$ của các vòng lặp lồng nhau phức tạp.<br>- Áp dụng Định lý Master và Cây đệ quy giải hệ thức $T(n) = aT(n/b) + f(n)$. |
| **II** | **Danh sách, Ngăn xếp & Hàng đợi** | ArrayList, SLL, DLL, Circular Queue, Shunting-Yard | ⭐⭐⭐⭐ | 15% - 20% | - Viết hàm thao tác trên Linked List (thêm, xóa, đảo ngược, ghép 2 list).<br>- Tính toán trạng thái Ngăn xếp / Hàng đợi qua chuỗi thao tác push/pop/enqueue/dequeue.<br>- Chuyển biểu thức Trung tố $\to$ Hậu tố bằng Shunting-Yard & Lượng giá RPN. |
| **III** | **Tìm kiếm, Bảng băm & Sắp xếp** | Binary/Interpolation Search, Hash Table, Quicksort, Mergesort | ⭐⭐⭐⭐⭐ *(Cực lớn)* | 25% - 30% | - Mô phỏng chèn/xóa trên Bảng băm: Linear, Quadratic, Double Hashing, Separate Chaining.<br>- Tính số phép thăm dò trung bình khi tìm kiếm thành công và không thành công.<br>- Tracing từng bước Quicksort (Kruse-Ryba / Hoare / Lomuto), Mergesort, Shell Sort.<br>- Phân tích số phép so sánh, phép gán, tính ổn định và trường hợp suy biến $O(n^2)$. |
| **IV** | **Cây, Cây Cân bằng & Cấu trúc Đống** | BST, AVL Tree, Splay Tree, B-Tree, Heap, Priority Queue | ⭐⭐⭐⭐⭐ *(Cực lớn)* | 25% - 30% | - Tracing thao tác Thêm / Xóa trên cây AVL (thực hiện đúng 4 phép quay LL, RR, LR, RL).<br>- Mô phỏng thao tác Splay (Zig, Zig-Zig, Zig-Zag) khi truy xuất / chèn / xóa khóa.<br>- Thao tác Tách node (Split) và Mượn/Gộp (Borrow/Merge) trên B-Tree bậc $M$.<br>- Xây dựng Heap bằng thuật toán Floyd Bottom-Up $O(n)$ và mô phỏng Heap Sort. |
| **V** | **Lý thuyết Đồ thị & Giải thuật Đồ thị** | DFS, BFS, Topo Sort, Dijkstra, Bellman-Ford, Kruskal, Prim, SCC | ⭐⭐⭐⭐⭐ *(Cực lớn)* | 25% - 30% | - Biểu diễn đồ thị và chuyển đổi qua lại giữa Ma trận kề $\leftrightarrow$ Danh sách kề.<br>- Duyệt đồ thị theo thứ tự từ điển, phân loại cạnh DFS (Tree, Back, Forward, Cross).<br>- Tìm thứ tự Tô-pô bằng thuật toán Kahn và giải thuật DFS.<br>- Lập bảng chạy từng bước thuật toán Dijkstra, Bellman-Ford, Floyd-Warshall.<br>- Tìm MST bằng Kruskal (kèm thao tác DSU) và Prim.<br>- Tìm SCC bằng thuật toán Kosaraju / Tarjan và kiểm tra đồ thị hai phía. |

---

## 📑 MỤC LỤC TỔNG QUAN

1. [PHẦN I: NỀN TẢNG LẬP TRÌNH C++ NÂNG CAO & PHÂN TÍCH ĐỘ PHỨC TẠP GIẢI THUẬT](#phần-i-nền-tảng-lập-trình-c-nâng-cao--phân-tích-độ-phức-tạp-giải-thuật)
   - [Chương 1: Ôn tập Kỹ thuật Lập trình C++ Nâng cao](#chương-1-ôn-tập-kỹ-thuật-lập-trình-c-nâng-cao)
     - 1.1. Con trỏ (Pointers) & Quản lý Bộ nhớ Động
     - 1.2. Lập trình Hướng đối tượng Nâng cao (OOP in C++)
     - 1.3. Khuôn mẫu (Templates) trong Thiết kế Cấu trúc Dữ liệu
     - 1.4. Xử lý Ngoại lệ (Exception Handling) & An toàn Ngoại lệ
     - 1.5. Đệ quy (Recursion) & Mô hình Thực thi Call Stack
   - [Chương 2: Phân tích Hiệu năng & Độ phức tạp Giải thuật](#chương-2-phân-tích-hiệu-năng--độ-phức-tạp-giải-thuật)
     - 2.1. Bản chất Chi phí Tính toán & Mô hình Máy RAM
     - 2.2. Phân loại Trường hợp: Best Case, Worst Case, Average Case
     - 2.3. Hệ thống Ký hiệu Tiệm cận ($O, \Omega, \Theta, o, \omega$)
     - 2.4. Phương pháp Phân tích Vòng lặp (Loop Analysis)
     - 2.5. Phương pháp Giải Hệ thức Truy hồi (Recurrences Analysis)
     - 2.6. Phương pháp Phân tích Chi phí Khấu hao (Amortized Analysis)
2. [PHẦN II: CẤU TRÚC DỮ LIỆU TUYẾN TÍNH & ỨNG DỤNG](#phần-ii-cấu-trúc-dữ-liệu-tuyến-tính--ứng-dụng)
   - [Chương 3: Danh sách Tuyến tính & Danh sách Liên kết](#chương-3-danh-sách-tuyến-tính--danh-sách-liên-kết)
     - 3.1. Danh sách Trừu tượng (List ADT)
     - 3.2. Danh sách Mảng Động (ArrayList)
     - 3.3. Danh sách Liên kết Đơn (Singly Linked List - SLL)
     - 3.4. Danh sách Liên kết Đôi (Doubly Linked List - DLL)
     - 3.5. Danh sách Liên kết Vòng (Circular Linked List - CLL)
     - 3.6. Danh sách Đa liên kết & Biểu diễn Ma trận Thưa (Sparse Matrix)
     - 3.7. So sánh Toàn diện Các Cấu trúc Danh sách
   - [Chương 4: Ngăn xếp & Hàng đợi](#chương-4-ngăn-xếp--hàng-đợi)
     - 4.1. Ngăn xếp (Stack ADT - LIFO) & Cài đặt
     - 4.2. Ứng dụng Kinh điển: Kiểm tra Ngoặc, Ký pháp Ba Lan & Thuật toán Shunting-Yard
     - 4.3. Hàng đợi (Queue ADT - FIFO) & Hàng đợi Vòng trên Mảng (Circular Queue)
     - 4.4. Hàng đợi Hai đầu (Deque) & Ứng dụng Mô phỏng Hệ thống
3. [PHẦN III: THUẬT TOÁN TÌM KIẾM, SẮP XẾP & CẤU TRÚC BẢNG BĂM](#phần-iii-thuật-toán-tìm-kiếm-sắp-xếp--cấu-trúc-bảng-băm)
   - [Chương 5: Thuật toán Tìm kiếm & Cấu trúc Bảng băm](#chương-5-thuật-toán-tìm-kiếm--cấu-trúc-bảng-băm)
     - 5.1. Các Giải thuật Tìm kiếm Cổ điển (Sequential, Binary, Interpolation)
     - 5.2. Nguyên lý Bảng băm & Địa chỉ Trực tiếp
     - 5.3. Các Kỹ thuật Thiết kế Hàm băm (Hash Functions)
     - 5.4. Chiến lược Giải quyết Va chạm: Địa chỉ Mở (Open Addressing)
     - 5.5. Chiến lược Giải quyết Va chạm: Nối kết Riêng biệt (Separate Chaining)
     - 5.6. Xóa phần tử & Kỹ thuật Tái băm Động (Dynamic Rehashing)
   - [Chương 6: Các Thuật toán Sắp xếp Toàn diện](#chương-6-các-thuật-toán-sắp-xếp-toàn-diện)
     - 6.1. Phân loại & Cận dưới Lý thuyết Sắp xếp So sánh ($\Omega(n \log n)$)
     - 6.2. Nhóm Sắp xếp Chèn: Straight Insertion Sort & Shell Sort
     - 6.3. Nhóm Sắp xếp Chọn: Straight Selection Sort
     - 6.4. Nhóm Sắp xếp Đổi chỗ: Bubble Sort & Cocktail Shaker Sort
     - 6.5. Nhóm Chia để Trị: Merge Sort & Trộn Danh sách Liên kết
     - 6.6. Nhóm Chia để Trị: Quick Sort Chuyên sâu (Kruse-Ryba, Hoare, Lomuto, Introsort)
     - 6.7. Bảng So sánh Hiệu năng & Đặc tính Toàn diện 8 Thuật toán Sắp xếp
4. [PHẦN IV: CẤU TRÚC CÂY, CÂY TÌM KIẾM CÂN BẰNG & CẤU TRÚC ĐỐNG](#phần-iv-cấu-trúc-cây-cây-tìm-kiếm-cân-bằng--cấu-trúc-đống)
   - [Chương 7: Cây Nhị phân & Cây Tìm kiếm Nhị phân](#chương-7-cây-nhị-phân--cây-tìm-kiếm-nhị-phân)
     - 7.1. Định nghĩa & Phân loại Cây Nhị phân
     - 7.2. Các Định lý Toán học & Tính chất Cốt lõi
     - 7.3. Các Phép Duyệt Cây (DFS & BFS) & Cây Biểu thức
     - 7.4. Cây Tìm kiếm Nhị phân (BST): Tra cứu, Chèn, Xóa 3 Trường hợp
   - [Chương 8: Cây Cân bằng AVL](#chương-8-cây-cân-bằng-avl)
     - 8.1. Khái niệm & Hệ số Cân bằng ($BF$)
     - 8.2. Cận Chiều cao & Dãy Fibonacci Tối thiểu
     - 8.3. Bốn Phép Quay Cân bằng: LL, RR, LR, RL
     - 8.4. Thuật toán Thêm phần tử AVL & Cờ hiệu `taller`
     - 8.5. Thuật toán Xóa phần tử AVL & Cờ hiệu `shorter`
   - [Chương 9: Cây Tự điều chỉnh Splay & Cây Tìm kiếm Đa phân B-Tree](#chương-9-cây-tự-điều-chỉnh-splay--cây-tìm-kiếm-đa-phân-b-tree)
     - 9.1. Cây Splay (Sleator & Tarjan): Triết lý & Tính Cục bộ Thời gian
     - 9.2. Ba Thao tác Splay Cốt lõi: Zig, Zig-Zig, Zig-Zag
     - 9.3. Các Thao tác Tra cứu, Chèn, Xóa trên Cây Splay
     - 9.4. Cây Tìm kiếm Đa phân & Cây B (B-Tree Bậc $M$)
     - 9.5. Thao tác Chèn Cây B & Kỹ thuật Tách Node (Split)
     - 9.6. Thao tác Xóa Cây B & Kỹ thuật Mượn / Hợp nhất (Borrow / Merge)
     - 9.7. Cây B+ (B+ Tree) & Đánh Chỉ mục Cơ sở Dữ liệu
   - [Chương 10: Cấu trúc Đống & Hàng đợi Ưu tiên](#chương-10-cấu-trúc-đống--hàng-đợi-ưu-tiên)
     - 10.1. Định nghĩa Cấu trúc Đống & Tính chất Thứ tự Heap
     - 10.2. Ánh xạ Mảng Tuyến tính & Các Phép toán Cốt lõi: `reheapUp`, `reheapDown`
     - 10.3. Giải thuật Thêm & Xóa Gốc trên Heap
     - 10.4. Xây dựng Đống (Floyd's Heapify) & Chứng minh $O(n)$
     - 10.5. Thuật toán Sắp xếp Vun đống (Heap Sort)
     - 10.6. Hàng đợi Ưu tiên & Bài toán Chọn $k$ Phần tử Cực trị
5. [PHẦN V: LÝ THUYẾT ĐỒ THỊ & CÁC THUẬT TOÁN ĐỒ THỊ NÂNG CAO](#phần-v-lý-thuyết-đồ-thị--các-thuật-toán-đồ-thị-nâng-cao)
   - [Chương 11: Biểu diễn Đồ thị & Duyệt Đồ thị](#chương-11-biểu-diễn-đồ-thị--duyệt-đồ-thị)
     - 11.1. Khái niệm Đồ thị Hình thức & Định lý Bắt tay
     - 11.2. Bốn Phương pháp Biểu diễn Đồ thị
     - 11.3. Ánh xạ Nhãn Đỉnh thành Chỉ số Số nguyên
     - 11.4. Thuật toán Tìm kiếm theo Chiều sâu (DFS) & Mô hình 3 Màu
     - 11.5. Thuật toán Tìm kiếm theo Chiều rộng (BFS) & Cây BFS
     - 11.6. Sắp xếp Tô-pô (Topological Sort): Thuật toán Kahn vs DFS
   - [Chương 12: Đường đi Ngắn nhất & Cây Khung Nhỏ nhất](#chương-12-đường-đi-ngắn-nhất--cây-khung-nhỏ-nhất)
     - 12.1. Đường đi Ngắn nhất Nguồn đơn (SSSP): Thuật toán Dijkstra
     - 12.2. Thuật toán Bellman-Ford: Trọng số Âm & Phát hiện Chu trình Âm
     - 12.3. Đường đi Ngắn nhất trên DAG ($O(V+E)$)
     - 12.4. Đường đi Ngắn nhất Mọi Cặp Đỉnh (APSP): Thuật toán Floyd-Warshall
     - 12.5. Cây Khung Nhỏ nhất (MST): Tính chất Nhát cắt & Chu trình
     - 12.6. Thuật toán Kruskal & Cấu trúc Tập hợp Rời nhau (DSU)
     - 12.7. Thuật toán Prim & Hàng đợi Ưu tiên
   - [Chương 13: Các Cấu trúc Liên thông & Ghép cặp Đồ thị](#chương-13-các-cấu-trúc-liên-thông--ghép-cặp-đồ-thị)
     - 13.1. Thành phần Liên thông Đồ thị Vô hướng (CC)
     - 13.2. Thành phần Liên thông Mạnh (SCC): Thuật toán Kosaraju-Sharir
     - 13.3. Thành phần Liên thông Mạnh (SCC): Thuật toán Tarjan
     - 13.4. Kiểm tra Đồ thị Hai phía (Bipartite Checking)
     - 13.5. Ghép cặp Cực đại trên Đồ thị Hai phía (Maximum Bipartite Matching)
6. [PHẦN VI: TỔNG HỢP CÔNG THỨC, PHÂN TÍCH BẪY ĐỀ THI & CẨM NANG ÔN TẬP](#phần-vi-tổng-hợp-công-thức-phân-tích-bẫy-đề-thi--cẩm-nang-ôn-tập)
   - [Chương 14: Bảng Tra cứu Nhanh Độ phức tạp & Công thức Vàng](#chương-14-bảng-tra-cứu-nhanh-độ-phức-tạp--công-thức-vàng)
   - [Chương 15: Các Bẫy Đề thi Kinh điển & Chiến lược Đạt Điểm Tối đa](#chương-15-các-bẫy-đề-thi-kinh-điển--chiến-lược-đạt-điểm-tối-đa)

---

# PHẦN I: NỀN TẢNG LẬP TRÌNH C++ NÂNG CAO & PHÂN TÍCH ĐỘ PHỨC TẠP GIẢI THUẬT

---

## CHƯƠNG 1: ÔN TẬP KỸ THUẬT LẬP TRÌNH C++ NÂNG CAO (PROGRAMMING REVIEW)

Trong môn học Cấu trúc Dữ liệu & Giải thuật (CO2003), ngôn ngữ C++ (chuẩn C++11/C++14/C++17) được sử dụng làm phương tiện hiện thực hóa các cấu trúc dữ liệu trừu tượng. Việc nắm vững cơ chế quản lý bộ nhớ, con trỏ, hướng đối tượng và đệ quy là điều kiện tiên quyết để xây dựng mã nguồn hiệu quả, tránh rò rỉ bộ nhớ (memory leaks) và lỗi sụp đổ chương trình (segmentation faults).

```
                      HỆ THỐNG KIẾN TRÚC BỘ NHỚ TIẾN TRÌNH C++
  +------------------------------------------------------------------------+
  | Text Segment (Mã máy thực thi của chương trình - Read-only)             |
  +------------------------------------------------------------------------+
  | Data Segment (Biến toàn cục, biến static đã được khởi tạo)             |
  +------------------------------------------------------------------------+
  | BSS Segment (Biến toàn cục, biến static chưa khởi tạo = 0)             |
  +------------------------------------------------------------------------+
  | Heap (Vùng nhớ động: new, malloc - Cấp phát thời gian chạy, tăng LÊN)   |
  |                           ↓    ↓    ↓                                  |
  |                           ↑    ↑    ↑                                  |
  | Stack (Vùng nhớ ngăn xếp: Biến cục bộ, Stack frame - Giảm XUỐNG)       |
  +------------------------------------------------------------------------+
```

---

### 1.1. Con trỏ (Pointers) & Quản lý Bộ nhớ Động

#### 1. Địa chỉ ô nhớ (Address) vs Đối tượng (Object):
* **Bản chất:** Con trỏ là một biến số mà giá trị của nó là địa chỉ ô nhớ của một đối tượng khác trong RAM.
* **Toán tử lấy địa chỉ (`&`):** Trả về vị trí bộ nhớ nơi biến đang cư trú.
* **Toán tử giải tham chiếu (`*`):** Cho phép truy cập hoặc thay đổi giá trị thực tế của đối tượng tại địa chỉ mà con trỏ đang lưu giữ.
* **Nguyên lý bất biến:** `p` là con trỏ (địa chỉ); `*p` là đối tượng (giá trị). Phép gán `q = p` chỉ sao chép địa chỉ (tạo bí danh / alias), không hề sao chép nội dung đối tượng.

#### 2. Con trỏ trỏ đến con trỏ (Pointer to Pointer - `T**`):
Được sử dụng khi cần thay đổi địa chỉ của chính con trỏ trong một hàm khác, hoặc xây dựng mảng 2 chiều động (mảng các con trỏ).
```cpp
int x = 5;
int* p = &x;     // p lưu địa chỉ &x
int** pp = &p;   // pp lưu địa chỉ &p
**pp = 9;        // x được cập nhật thành 9
```

#### 3. Con trỏ và từ khóa `const`:
Phân biệt vị trí của `const` so với dấu sao `*`:
* `const int* pc = &x;` (hoặc `int const* pc = &x;`): **Con trỏ trỏ tới hằng số (Pointer to Const)**. Giá trị của đối tượng `*pc` là bất biến (không thể sửa thông qua `*pc = 1;`), nhưng bản thân con trỏ `pc` có thể trỏ sang đối tượng khác (`pc = &y;` hợp lệ).
* `int* const cp = &x;`: **Hằng con trỏ (Const Pointer)**. Địa chỉ mà con trỏ lưu giữ bị đóng băng (`cp = &y;` báo lỗi biên dịch), nhưng giá trị đối tượng mà nó trỏ tới có thể thay đổi thoải mái (`*cp = 10;` hợp lệ).
* `const int* const cpc = &x;`: Cả địa chỉ con trỏ và giá trị đối tượng đều bị đóng băng.
* **Phương thức `const`:** `int size() const;` khẳng định phương thức là thao tác chỉ đọc, con trỏ ngầm định `this` trở thành `const ClassName* const this`, bảo đảm không làm thay đổi trạng thái đối tượng.

#### 4. Khởi tạo, Con trỏ Null (`nullptr`) & Con trỏ Lơ lửng (Dangling Pointer):
* **Quy tắc vàng:** Luôn khởi tạo con trỏ ngay khi khai báo. Dùng `nullptr` (C++11) thay thế hoàn toàn macro số `NULL` hoặc số nguyên `0` để tránh nhập nhằng kiểu dữ liệu khi nạp chồng hàm (overloading).
* **Con trỏ lơ lửng (Dangling Pointer):** Xuất hiện khi một vùng nhớ đã được thu hồi (`delete p;`), nhưng biến con trỏ `p` vẫn giữ nguyên địa chỉ cũ. Việc tiếp tục dereference `*p` sẽ dẫn đến **Hành vi không xác định (Undefined Behavior - UB)**.
  > **Biện pháp phòng ngừa:** Ngay sau khi giải phóng, lập tức gán `p = nullptr;`.

#### 5. Cấp phát & Thu hồi Bộ nhớ Động (`new` / `delete`):
* Cấp phát một đối tượng đơn: `T* p = new T();` $\iff$ Thu hồi bắt buộc: `delete p;`.
* Cấp phát mảng đối tượng: `T* arr = new T[N];` $\iff$ Thu hồi bắt buộc: `delete[] arr;`.
  > [!CAUTION]
  > Tuyệt đối không dùng `delete` đơn để giải phóng mảng tạo bởi `new[]`. Làm như vậy trình biên dịch sẽ chỉ gọi destructor của phần tử đầu tiên, gây rò rỉ bộ nhớ nghiêm trọng và phá hỏng metadata của Heap Manager!

#### 6. Số học Con trỏ (Pointer Arithmetic):
Khi thực hiện `p + k`, địa chỉ thực tế tăng thêm là $k \times \text{sizeof}(T)$ byte. Hai con trỏ cùng trỏ vào một mảng liên tục có thể trừ cho nhau: `p2 - p1` trả về số lượng phần tử nằm giữa hai con trỏ.

---

### 1.2. Lập trình Hướng đối tượng Nâng cao (OOP in C++)

#### 1. Đóng gói (Encapsulation) & Quản trị Bất biến (Class Invariants):
Trong thiết kế ADT, tất cả các thuộc tính phản ánh trạng thái nội bộ (như mảng phần tử, kích thước `count`, dung lượng `capacity`, con trỏ `head`, `tail`) phải đặt ở phạm vi `private` hoặc `protected`. Các phương thức công khai (`public`) kiểm soát việc thay đổi dữ liệu nhằm duy trì tính toàn vẹn bất biến của cấu trúc.

#### 2. Bản sao Nông (Shallow Copy) vs Bản sao Sâu (Deep Copy):
* **Bản sao nông (Mặc định của C++):** Khi truyền đối tượng theo giá trị hoặc dùng toán tử gán mặc định, C++ sao chép từng bit (bitwise copy). Nếu lớp chứa con trỏ trỏ tới Heap, hai đối tượng sẽ cùng sở hữu một vùng nhớ chung. Khi các đối tượng bị tiêu hủy, destructor chạy 2 lần trên cùng một địa chỉ $\implies$ **Lỗi Double-Free Crash**!
* **Bản sao sâu (Deep Copy):** Cần tự viết **Hàm khởi tạo sao chép (Copy Constructor)** và **Toán tử gán sao chép (Copy Assignment Operator)** để cấp phát vùng nhớ độc lập và sao chép từng giá trị.

```cpp
template <typename T>
class Array {
private:
    T* data;
    int capacity;
    int count;
public:
    // Constructor khởi tạo
    Array(int cap = 10) : capacity(cap), count(0), data(new T[cap]) {}

    // Destructor giải phóng
    ~Array() { delete[] data; }

    // Copy Constructor - Deep Copy
    Array(const Array& other) : capacity(other.capacity), count(other.count), data(new T[other.capacity]) {
        for (int i = 0; i < count; i++) data[i] = other.data[i];
    }

    // Copy Assignment Operator - Copy-and-Swap idiom
    Array& operator=(const Array& other) {
        if (this != &other) {
            T* newData = new T[other.capacity];
            for (int i = 0; i < other.count; i++) newData[i] = other.data[i];
            delete[] data;
            data = newData;
            capacity = other.capacity;
            count = other.count;
        }
        return *this;
    }
};
```

#### 3. Quy tắc Bộ ba / Bộ năm (Rule of Three / Rule of Five):
Nếu một lớp quản lý tài nguyên động cần định nghĩa tường minh một trong các thành phần:
1. Destructor
2. Copy Constructor
3. Copy Assignment Operator
Thì bắt buộc phải tự cài đặt đầy đủ cả 3 thành phần (trong C++11 bổ sung Move Constructor và Move Assignment Operator thành Bộ năm).

#### 4. Tính Đa hình (Polymorphism) & Cơ chế Điều phối Hàm ảo (`virtual` / `override`):
* **Liên kết tĩnh (Early / Static Binding):** Mặc định trong C++, lời gọi hàm được quyết định dựa trên kiểu của con trỏ tại thời điểm biên dịch.
* **Liên kết động (Late / Dynamic Binding):** Khi khai báo từ khóa `virtual` ở phương thức lớp cha, trình biên dịch thiết lập bảng hàm ảo (**vtable**) và con trỏ ảo (**vptr**). Khi gọi qua con trỏ lớp cơ sở `Base* p = new Derived(); p->display();`, C++ sẽ tra vtable và thực thi đúng phương thức của đối tượng thực tế (`Derived`).
* **Từ khóa `override` (C++11):** Đặt ở cuối khai báo hàm con để yêu cầu compiler kiểm tra nghiêm ngặt chữ ký hàm xem có thực sự ghi đè hàm ảo ở lớp cha hay không.
* **Destructor Ảo (`virtual ~Base()`):** CỰC KỲ QUAN TRỌNG! Nếu lớp cha không có destructor ảo, lệnh `delete p;` (với `Base* p = new Derived();`) sẽ chỉ thực thi destructor của `Base`, toàn bộ tài nguyên do `Derived` cấp phát sẽ bị bỏ rơi vĩnh viễn trên Heap.

#### 5. Lớp Trừu tượng (Abstract Class) & Phương thức Thuần ảo (Pure Virtual Function):
* Khai báo: `virtual void insert(T val) = 0;`.
* Lớp chứa ít nhất một phương thức thuần ảo là **Lớp trừu tượng**. Lớp này không thể khởi tạo đối tượng trực tiếp mà đóng vai trò là giao diện hợp đồng (Interface ADT, ví dụ `IList<T>`).

---

### 1.3. Khuôn mẫu (Templates) trong Thiết kế Cấu trúc Dữ liệu

Khuôn mẫu cho phép tham số hóa kiểu dữ liệu (`template <typename T>`), giúp tái sử dụng mã nguồn cho mọi kiểu dữ liệu (`int`, `double`, `std::string`, `Point`) mà không làm suy giảm hiệu năng lúc chạy:
* **Function Template:** Các giải thuật tổng quát như `my_swap(T& a, T& b)`, `partition(...)`.
* **Class Template:** Cấu trúc dữ liệu tổng quát `ArrayList<T>`, `SLinkedList<T>`, `AVLTree<T>`, `Heap<T>`.
* **Lưu ý biên dịch:** Trình biên dịch C++ sinh mã thực thi theo từng kiểu dữ liệu cụ thể khi template được khởi tạo (instantiation). Do đó, toàn bộ định nghĩa hàm của class template phải được đặt trong cùng file header (`.h` / `.hpp`), không được tách định nghĩa sang `.cpp`.

---

### 1.4. Xử lý Ngoại lệ (Exception Handling) & An toàn Ngoại lệ

Cơ chế `try - throw - catch` giúp tách biệt mã xử lý logic nghiệp vụ khỏi mã bắt lỗi hệ thống:
* **Ném ngoại lệ (`throw`):** Khi phát hiện điều kiện tiền đề bị vi phạm (Underflow khi `pop()` ngăn xếp rỗng, Out-of-bounds khi truy cập chỉ số bất hợp lệ), ném một đối tượng ngoại lệ chuẩn kế thừa từ `std::exception`:
  - `std::out_of_range`: Chỉ số vượt ngoài phạm vi.
  - `std::underflow_error`: Thao tác trên cấu trúc dữ liệu rỗng.
  - `std::overflow_error`: Thao tác vượt quá khả năng lưu trữ.
  - `std::bad_alloc`: Hết bộ nhớ Heap.
* **Bắt ngoại lệ (`catch`):** Luôn bắt ngoại lệ bằng tham chiếu hằng: `catch (const std::exception& e)` để tránh tạo bản sao tốn kém và ngăn chặn hiện tượng cắt lát đối tượng (Object Slicing).
* **Quá trình Giải cuộn Ngăn xếp (Stack Unwinding):** Khi ngoại lệ được ném ra, thời gian chạy sẽ tự động tiêu hủy tất cả các đối tượng cục bộ trong các stack frame từ điểm ném đến điểm bắt, đảm bảo giải phóng tài nguyên cục bộ một cách tự động.

---

### 1.5. Đệ quy (Recursion) & Mô hình Thực thi Call Stack

#### 1. Bản chất & Hai thành phần Cốt lõi:
Đệ quy là kỹ thuật trong đó một hàm tự gọi lại chính nó với không gian bài toán có quy mô nhỏ hơn:
1. **Điểm dừng (Base Case):** Trường hợp tầm thường nhất của bài toán, trả về kết quả ngay lập tức mà không phát sinh thêm lời gọi đệ quy. Nếu thiếu hoặc sai Base Case, chương trình sẽ rơi vào đệ quy vô hạn dẫn đến tràn bộ nhớ Stack (Stack Overflow).
2. **Bước đệ quy (Recursive Step):** Chia nhỏ bài toán thành một hoặc nhiều bài toán con đồng dạng có kích thước nhỏ hơn ($n - 1, n/2, \dots$) và kết hợp kết quả.

#### 2. Ngăn xếp Thực thi (Call Stack) & Stack Frame:
Mỗi lời gọi hàm tạo ra một bản ghi kích hoạt (**Activation Record / Stack Frame**) trên ngăn xếp hệ thống chứa:
- Tham số truyền vào hàm.
- Biến cục bộ của hàm.
- Địa chỉ trả về (Return address) của lệnh tiếp theo sau lời gọi hàm.
- Con trỏ frame (Frame pointer).

#### 3. Phân loại Đệ quy:
* **Đệ quy Tuyến tính (Linear Recursion):** Mỗi bước chỉ phát sinh duy nhất 1 lời gọi đệ quy (ví dụ: tính giai thừa $n!$, duyệt danh sách liên kết).
* **Đệ quy Nhánh / Cây (Tree Recursion):** Mỗi bước phát sinh từ 2 lời gọi đệ quy trở lên (ví dụ: tính số Fibonacci $F(n) = F(n-1) + F(n-2)$, Tháp Hà Nội).
* **Đệ quy Đuôi (Tail Recursion):** Lời gọi đệ quy là thao tác cuối cùng trước khi trả về. Trình biên dịch có thể tự động biến đổi thành vòng lặp (Tail Call Optimization - TCO) để duy trì $O(1)$ không gian Stack.

#### 4. Bài toán Kinh điển: Tháp Hà Nội (Tower of Hanoi):
Chuyển $n$ đĩa từ cọc nguồn `src` sang cọc đích `dst` thông qua cọc trung chuyển `aux` với quy tắc: mỗi lần chỉ chuyển 1 đĩa và đĩa lớn không bao giờ được đặt lên đĩa nhỏ.
```cpp
void hanoi(int n, char src, char dst, char aux) {
    if (n == 1) {
        std::cout << "Move disk 1 from " << src << " to " << dst << std::endl;
        return;
    }
    hanoi(n - 1, src, aux, dst);
    std::cout << "Move disk " << n << " from " << src << " to " << dst << std::endl;
    hanoi(n - 1, aux, dst, src);
}
```
* Số thao tác di chuyển: $T(n) = 2T(n-1) + 1 \implies T(n) = 2^n - 1$ bước.
* Độ phức tạp thời gian: $\Theta(2^n)$.
* Độ sâu tối đa của Call Stack: $n$ tầng $\implies$ Độ phức tạp không gian: $O(n)$.

---

## CHƯƠNG 2: PHÂN TÍCH HIỆU NĂNG & ĐỘ PHỨC TẠP GIẢI THUẬT (ALGORITHM COMPLEXITY)

---

### 2.1. Bản chất Chi phí Tính toán & Mô hình Máy RAM (Random Access Machine)

* **Hạn chế của phép đo thời gian vật lý (Wall-clock time):** Bị chi phối bởi xung nhịp CPU, dung lượng bộ nhớ Cache, hệ điều hành và ngôn ngữ lập trình.
* **Mô hình máy RAM (Random Access Machine):**
  - Mô hình tính toán trừu tượng chuẩn hóa trong khoa học máy tính:
  - Máy tính xử lý tuần tự từng lệnh (không song song).
  - Mọi thao tác nguyên thủy (Primitive Operations: gán giá trị, so sánh hai số, phép toán số học `+ - * /`, truy xuất mảng theo chỉ số `A[i]`, dereference con trỏ, gọi hàm, trả về) đều có chi phí thời gian là hằng số $\Theta(1)$.
  - Dung lượng bộ nhớ là vô hạn; truy xuất bất kỳ ô nhớ nào đều tốn $\Theta(1)$ thời gian.
* **Hàm đo độ phức tạp $T(n)$:** Phản ánh tổng số thao tác nguyên thủy được thực hiện phụ thuộc vào quy mô dữ liệu đầu vào $n$.

---

### 2.2. Phân loại Trường hợp Phân tích

Cho cùng một giải thuật và cùng quy mô đầu vào $n$, các tập dữ liệu có cấu trúc khác nhau sẽ tiêu tốn thời gian khác nhau:
1. **Trường hợp Tốt nhất (Best-Case Complexity - $T_{best}(n)$):**
   - Cấu hình đầu vào kích thước $n$ thuận lợi nhất, đòi hỏi số thao tác ít nhất.
   - *Ví dụ:* Tìm kiếm tuần tự thấy phần tử ngay tại vị trí đầu tiên ($O(1)$); Insertion Sort trên mảng đã sắp xếp tăng dần ($O(n)$).
2. **Trường hợp Xấu nhất (Worst-Case Complexity - $T_{worst}(n)$):**
   - Cấu hình đầu vào kích thước $n$ bất lợi nhất, đòi hỏi số thao tác nhiều nhất.
   - *Ý nghĩa:* Cung cấp một cam kết chắc chắn (Guaranteed Upper Bound) rằng giải thuật sẽ không bao giờ chạy vượt quá thời gian này. Đây là đại lượng chuẩn mực được báo cáo trong toàn bộ môn học.
   - *Ví dụ:* Quick Sort với pivot là phần tử đầu tiên trên mảng đã có thứ tự ($O(n^2)$).
3. **Trường hợp Trung bình (Average-Case Complexity - $T_{avg}(n)$):**
   - Kỳ vọng toán học của thời gian thực thi: $T_{avg}(n) = \sum_{I} P(I) \cdot T(I)$, trong đó $P(I)$ là xác suất xuất hiện đầu vào $I$.
   - Thường giả định phân phối xác suất đều (Uniform Distribution).

---

### 2.3. Hệ thống Ký hiệu Tiệm cận (Asymptotic Notations)

Ký hiệu tiệm cận mô tả hành vi tăng trưởng của hàm số $T(n)$ khi quy mô bài toán $n \to \infty$, bỏ qua các hằng số nhân và các số hạng bậc thấp.

```
                  MINH HỌA HÌNH HỌC CÁC KÝ HIỆU TIỆM CẬN
      T(n) <= c * g(n)              c * g(n) <= T(n)           c1*g(n) <= T(n) <= c2*g(n)
         [ Big-O ]                   [ Big-Omega ]                   [ Big-Theta ]

     ^  f(n)                         ^  f(n)                         ^  f(n)
     |       c*g(n)                  |        T(n)                   |       c2*g(n)
     |      /                        |       /                       |      /  T(n)
     |     /   T(n)                  |      /   c*g(n)               |     /  /
     |    /   /                      |     /   /                     |    /  /   c1*g(n)
     |   /   /                       |    /   /                      |   /  /   /
     |  /___/                        |   /___/                       |  /__/__/
     +----------> n                  +----------> n                  +------------> n
          n0                              n0                              n0
```

#### 1. Định nghĩa Hình thức & Ý nghĩa:

| Ký hiệu | Tên gọi | Định nghĩa toán học hình thức | Định nghĩa qua Giới hạn $\lim_{n \to \infty} \frac{f(n)}{g(n)}$ | Vai trò trong Phân tích |
| :---: | :--- | :--- | :---: | :--- |
| **$O(g(n))$** | Big-O | $\exists c > 0, n_0 > 0 : \forall n \ge n_0, 0 \le f(n) \le c \cdot g(n)$ | $\lim = L < \infty$ ($L \ge 0$) | **Cận trên tiệm cận** (Upper bound). Giải thuật chạy không tệ hơn $g(n)$. |
| **$\Omega(g(n))$** | Big-Omega | $\exists c > 0, n_0 > 0 : \forall n \ge n_0, 0 \le c \cdot g(n) \le f(n)$ | $\lim = L > 0$ hoặc $\lim = \infty$ | **Cận dưới tiệm cận** (Lower bound). Giải thuật cần ít nhất $g(n)$ thao tác. |
| **$\Theta(g(n))$** | Big-Theta | $f(n) \in O(g(n)) \text{ và } f(n) \in \Omega(g(n))$ | $\lim = L$ với $0 < L < \infty$ | **Cận chặt tiệm cận** (Tight bound). Tốc độ tăng trưởng chính xác như $g(n)$. |
| **$o(g(n))$** | Little-o | $\forall c > 0, \exists n_0 > 0 : \forall n \ge n_0, 0 \le f(n) < c \cdot g(n)$ | $\lim = 0$ | **Cận trên ngặt** (Strictly upper bound). $f(n)$ bị $g(n)$ áp đảo hoàn toàn. |
| **$\omega(g(n))$** | Little-omega | $\forall c > 0, \exists n_0 > 0 : \forall n \ge n_0, 0 \le c \cdot g(n) < f(n)$ | $\lim = \infty$ | **Cận dưới ngặt** (Strictly lower bound). $f(n)$ áp đảo $g(n)$ hoàn toàn. |

#### 2. Thang phân cấp Tốc độ Tăng trưởng Chuẩn (Tăng dần):
$$\Theta(1) < \Theta(\log \log n) < \Theta(\log n) < \Theta(n^c) (0 < c < 1) < \Theta(n) < \Theta(n \log n) < \Theta(n^2) < \Theta(n^3) < \Theta(2^n) < \Theta(n!)$$

#### 3. Các Tính chất Đại số Cốt lõi:
* **Bắc cầu (Transitivity):** $f(n) \in \Theta(g(n)) \land g(n) \in \Theta(h(n)) \implies f(n) \in \Theta(h(n))$.
* **Cộng tiệm cận (Summation Rule):** $O(f(n)) + O(g(n)) = O(\max(f(n), g(n)))$.
* **Nhân tiệm cận (Product Rule):** $O(f(n)) \times O(g(n)) = O(f(n) \times g(n))$.

---

### 2.4. Phương pháp Phân tích Vòng lặp (Loop Analysis)

#### 1. Quy trình 7 Bước Chuẩn mực:
1. Xác định rõ tham số quy mô đầu vào $n$.
2. Xác định phép toán cơ sở (Basic / Primitive Operation) nằm ở khối lệnh sâu nhất.
3. Xác định miền giá trị của các biến điều khiển vòng lặp.
4. Thiết lập công thức toán học dưới dạng tích phân hoặc tổng xích-ma $\sum$.
5. Đưa chi phí các hàm được gọi bên trong thân vòng lặp vào biểu thức tổng.
6. Rút gọn tổng bằng công thức đại số và đưa ra cận chặt $\Theta$.
7. Kết luận rõ ràng đó là trường hợp Best, Average hay Worst case.

#### 2. Các Công thức Tổng Chuỗi Thiết yếu:
* Tổng hằng số: $\sum_{i=1}^n c = c \cdot n = \Theta(n)$
* Tổng số nguyên liên tiếp: $\sum_{i=1}^n i = \frac{n(n+1)}{2} = \frac{n^2}{2} + \frac{n}{2} = \Theta(n^2)$
* Tổng bình phương: $\sum_{i=1}^n i^2 = \frac{n(n+1)(2n+1)}{6} = \Theta(n^3)$
* Tổng cấp số nhân: $\sum_{i=0}^k r^i = \frac{r^{k+1} - 1}{r - 1}$. Với $r = 2 \implies \sum_{i=0}^k 2^i = 2^{k+1} - 1 = \Theta(2^k)$.
* Chuỗi điều hòa (Harmonic Series): $H_n = \sum_{i=1}^n \frac{1}{i} = \ln n + \gamma + O(1/n) = \Theta(\log n)$ (với $\gamma \approx 0.5772$).

#### 3. Phân tích Các Mô hình Vòng lặp Điển hình:

##### Mô hình 1: Vòng lặp biến thiên cấp số nhân (Logarithmic Loop):
```cpp
for (int i = 1; i < n; i *= 2) { // i nhận giá trị: 1, 2, 4, 8, ..., 2^k < n
    // Thao tác Theta(1)
}
```
* Điều kiện dừng: $2^k \ge n \iff k = \lceil \log_2 n \rceil$.
* Tổng số bước thực thi: $\Theta(\log n)$.

##### Mô hình 2: Vòng lặp biến thiên bậc hai (Double Logarithmic Loop):
```cpp
for (int i = 2; i < n; i = i * i) { // i nhận giá trị: 2, 2^2, 2^4, ..., 2^(2^k)
    // Thao tác Theta(1)
}
```
* Điều kiện dừng: $2^{2^k} \ge n \iff 2^k \ge \log_2 n \iff k = \log_2(\log_2 n)$.
* Độ phức tạp: $\Theta(\log \log n)$.

##### Mô hình 3: Vòng lặp lồng nhau phụ thuộc (Dependent Nested Loops):
```cpp
int sum = 0;
for (int i = 1; i <= n; i++) {
    for (int j = 1; j <= i; j++) {
        sum++;
    }
}
```
* Số lần biến `sum` tăng: $\sum_{i=1}^n \sum_{j=1}^i 1 = \sum_{i=1}^n i = \frac{n(n+1)}{2} = \Theta(n^2)$.

##### Mô hình 4: Vòng lặp lồng nhau chia đôi (Nested Loop with Division):
```cpp
int count = 0;
for (int i = 1; i <= n; i++) {
    for (int j = n; j >= 1; j /= 2) {
        count++;
    }
}
```
* Vòng lặp ngoài chạy $n$ lần. Vòng lặp trong chạy $\lfloor \log_2 n \rfloor + 1$ lần cho mỗi $i$.
* Tổng số thao tác: $\sum_{i=1}^n \Theta(\log n) = n \cdot \Theta(\log n) = \Theta(n \log n)$.

---

### 2.5. Phương pháp Giải Hệ thức Truy hồi (Recurrences Analysis)

Hệ thức truy hồi biểu diễn thời gian tính toán của một giải thuật đệ quy: $T(n) = a T(n/b) + f(n)$.

#### 1. Định lý Thợ (Master Theorem):
Áp dụng cho các giải thuật chia để trị chuẩn có dạng:
$$T(n) = a T\left(\frac{n}{b}\right) + f(n) \quad (a \ge 1, b > 1)$$
Trong đó: $a$ là số lượng bài toán con, $n/b$ là quy mô của mỗi bài toán con, $f(n)$ là chi phí phân chia bài toán và kết hợp nghiệm ngoài đệ quy.

Trọng tâm của Định lý Master là so sánh hàm $f(n)$ với hàm đa thức phân thủy $n^{\log_b a}$ (đại diện cho tổng chi phí tại tầng lá của cây đệ quy):

| Trường hợp | Điều kiện so sánh | Ý nghĩa trực quan | Kết luận Độ phức tạp $T(n)$ |
| :---: | :--- | :--- | :---: |
| **Case 1** | $f(n) = O\left(n^{\log_b a - \epsilon}\right)$ với hằng số $\epsilon > 0$ | Chi phí tại tầng lá **áp đảo hoàn toàn** chi phí tại gốc. | $T(n) = \Theta\left(n^{\log_b a}\right)$ |
| **Case 2** | $f(n) = \Theta\left(n^{\log_b a} \log^k n\right)$ với $k \ge 0$ | Chi phí phân bố **đồng đều** trên tất cả các tầng của cây đệ quy. | $T(n) = \Theta\left(n^{\log_b a} \log^{k+1} n\right)$ |
| **Case 3** | $f(n) = \Omega\left(n^{\log_b a + \epsilon}\right)$ với $\epsilon > 0$ VÀ thỏa mãn **Điều kiện điều hòa (Regularity Condition):** $a \cdot f(n/b) \le c \cdot f(n)$ với $c < 1$ | Chi phí phân chia/kết hợp tại nút gốc **áp đảo hoàn toàn** các tầng dưới. | $T(n) = \Theta(f(n))$ |

> [!WARNING]
> Định lý Master không áp dụng được khi:
> 1. $a$ không phải là hằng số (ví dụ: $a = 2^n$).
> 2. $b \le 1$ (ví dụ: $T(n) = T(n-1) + n$).
> 3. Khoảng cách giữa $f(n)$ và $n^{\log_b a}$ không mang tính đa thức (ví dụ: $f(n) = n^{\log_b a} / \log n$).

#### 2. Phương pháp Cây Đệ quy (Recursion Tree Method):
* **Ý tưởng:** Vẽ cây biểu diễn các lời gọi hàm đệ quy.
  - Tầng 0 (gốc): Chi phí $f(n)$.
  - Tầng 1: $a$ nút, mỗi nút tốn $f(n/b) \implies$ Tổng tầng 1: $a \cdot f(n/b)$.
  - Tầng $i$: $a^i$ nút, mỗi nút tốn $f(n/b^i) \implies$ Tổng tầng $i$: $a^i \cdot f(n/b^i)$.
  - Chiều cao của cây: $h = \log_b n$.
  - Số lượng nút lá tại tầng $h$: $a^{\log_b n} = n^{\log_b a}$.
* Tổng chi phí toàn bộ thuật toán bằng tổng chi phí của từng tầng: $T(n) = \sum_{i=0}^{\log_b n} \text{Cost}(i)$.

#### 3. Phương pháp Khai triển dần / Đổi biến (Unrolling / Substitution Method):
Áp dụng cho các hệ thức truy hồi giảm trừ: $T(n) = T(n - k) + f(n)$.
* *Ví dụ bài toán Tháp Hà Nội:* $T(n) = 2T(n-1) + 1$
  $$\begin{aligned}
  T(n) &= 2[2T(n-2) + 1] + 1 = 4T(n-2) + 2 + 1 \\
       &= 4[2T(n-3) + 1] + 3 = 8T(n-3) + 4 + 2 + 1 \\
       &= 2^k T(n-k) + \sum_{i=0}^{k-1} 2^i
  \end{aligned}$$
  Dừng khi $n - k = 1 \implies k = n - 1$:
  $$T(n) = 2^{n-1} T(1) + (2^{n-1} - 1) = 2^n - 1 = \Theta(2^n)$$

#### 4. Tổng kết Độ phức tạp Các Hệ thức Truy hồi Kinh điển trong DSA:

| Giải thuật | Hệ thức truy hồi | Trường hợp áp dụng | Độ phức tạp tiệm cận $T(n)$ |
| :--- | :--- | :---: | :---: |
| **Binary Search** | $T(n) = T(n/2) + \Theta(1)$ | Master Case 2 ($a=1, b=2, k=0$) | $\Theta(\log n)$ |
| **Merge Sort** | $T(n) = 2T(n/2) + \Theta(n)$ | Master Case 2 ($a=2, b=2, k=0$) | $\Theta(n \log n)$ |
| **Binary Tree Traversal** | $T(n) = 2T(n/2) + \Theta(1)$ | Master Case 1 ($a=2, b=2, n^0 < n^1$) | $\Theta(n)$ |
| **Strassen Matrix Mult** | $T(n) = 7T(n/2) + \Theta(n^2)$ | Master Case 1 ($\log_2 7 \approx 2.807 > 2$) | $\Theta(n^{2.807})$ |
| **Quick Sort (Best Case)** | $T(n) = 2T(n/2) + \Theta(n)$ | Master Case 2 ($a=2, b=2, k=0$) | $\Theta(n \log n)$ |
| **Quick Sort (Worst Case)**| $T(n) = T(n-1) + \Theta(n)$ | Unrolling method | $\Theta(n^2)$ |
| **Tower of Hanoi** | $T(n) = 2T(n-1) + \Theta(1)$| Unrolling method | $\Theta(2^n)$ |
| **Fibonacci (Naive)** | $T(n) = T(n-1) + T(n-2) + \Theta(1)$ | Đặc trưng nghiệm bậc hai | $\Theta(\phi^n)$ với $\phi \approx 1.618$ |

---

### 2.6. Phương pháp Phân tích Chi phí Khấu hao (Amortized Analysis)

#### 1. Khái niệm & Sự khác biệt với Average Case:
* **Chi phí phân bổ khấu hao (Amortized Cost):** Là chi phí trung bình của mỗi thao tác được tính trên một chuỗi gồm $n$ thao tác liên tiếp ở **trường hợp xấu nhất**.
* **Khác biệt cốt tử:** Phân tích Amortized **hoàn toàn không sử dụng xác suất**. Nó bảo đảm mức trần hiệu năng chắc chắn cho mọi kịch bản thực tế, loại trừ trường hợp một thao tác quá nặng làm nghẽn hệ thống mà không được bù trừ.

#### 2. Ba Phương pháp Phân tích Chuẩn:
1. **Phương pháp Tổng gộp (Aggregate Method):**
   Tính tổng thời gian thực tế của cả chuỗi $n$ thao tác $T_{total}(n)$ trong trường hợp xấu nhất. Khi đó chi phí khấu hao của mỗi thao tác là $T_{amortized} = \frac{T_{total}(n)}{n}$.
2. **Phương pháp Kế toán (Accounting Method):**
   Gán cho mỗi thao tác một khoản phí khấu hao $c_i'$. Nếu $c_i' > c_i$ (chi phí thực tế), phần chênh lệch được tích lũy vào tài khoản "tín dụng" (Credit). Khi gặp thao tác tốn kém ($c_i > c_i'$), lượng tín dụng đã tích lũy được đem ra chi trả. Điều kiện bảo đảm: Tổng tín dụng tại mọi thời điểm không được âm: $\sum_{i=1}^m c_i' \ge \sum_{i=1}^m c_i$.
3. **Phương pháp Hàm Thế năng (Potential Method):**
   Xác định một hàm thế năng $\Phi(D)$ ánh xạ trạng thái cấu trúc dữ liệu $D$ thành một số thực đại diện cho năng lượng tiềm tàng. Chi phí khấu hao của thao tác thứ $i$:
   $$c_i' = c_i + \Phi(D_i) - \Phi(D_{i-1})$$
   Tổng chi phí khấu hao của $n$ thao tác:
   $$\sum_{i=1}^n c_i' = \sum_{i=1}^n c_i + \Phi(D_n) - \Phi(D_0)$$
   Nếu $\Phi(D_n) \ge \Phi(D_0)$ thì tổng chi phí khấu hao luôn là một cận trên của tổng chi phí thực tế.

#### 3. Ví dụ Kinh điển: Chiến lược Nhân đôi Dung lượng Mảng Động (Dynamic Array Doubling):
* Mảng ban đầu có dung lượng $1$. Khi đầy, mảng tự động cấp phát vùng nhớ mới gấp đôi ($2 \times capacity$), chép toàn bộ phần tử cũ sang và giải phóng mảng cũ.
* Xét chuỗi $n$ thao tác thêm phần tử `append`:
  - Thao tác thứ $i$ không phải nhân đôi: Chi phí thực $c_i = 1$.
  - Thao tác thứ $i$ rơi vào lũy thừa của 2 ($i = 2^k + 1$): Cấp phát mảng mới và chép $i-1$ phần tử cũ $\implies c_i = (i - 1) + 1 = i$.
* Tổng chi phí thực tế cho $n$ thao tác:
  $$T(n) = n + \sum_{k=0}^{\lfloor \log_2 n \rfloor} 2^k < n + 2n = 3n$$
* **Kết luận:** Chi phí khấu hao của mỗi thao tác `append` là:
  $$c_{amortized} = \frac{T(n)}{n} < \frac{3n}{n} = 3 = O(1)$$
  Đây là nền tảng giải thích tại sao `std::vector::push_back` trong C++ có độ phức tạp thời gian amortized là $O(1)$.

# PHẦN II: CẤU TRÚC DỮ LIỆU TUYẾN TÍNH & ỨNG DỤNG

---

## CHƯƠNG 3: DANH SÁCH TUYẾN TÍNH & DANH SÁCH LIÊN KẾT (LINEAR LISTS & LINKED LISTS)

Danh sách tuyến tính là một tập hợp hữu hạn gồm $n \ge 0$ phần tử có thứ tự vị trí xác định: $L = (a_0, a_1, a_2, \dots, a_{n-1})$. Mối quan hệ giữa các phần tử là quan hệ kế tiếp 1-1: ngoại trừ phần tử đầu tiên ($a_0$) và phần tử cuối cùng ($a_{n-1}$), mỗi phần tử $a_i$ đều có đúng một phần tử đứng trước ($a_{i-1}$) và đúng một phần tử đứng sau ($a_{i+1}$).

---

### 3.1. Danh sách Trừu tượng (List ADT)

Giao diện lớp cơ sở trừu tượng chuẩn (`IList<T>`) định nghĩa tập hợp các hành vi mà mọi cấu trúc danh sách phải tuân thủ:

```cpp
template <class T>
class IList {
public:
    virtual ~IList() {}
    virtual void add(T e) = 0;                     // Thêm vào cuối danh sách
    virtual void add(int index, T e) = 0;          // Chèn vào vị trí index
    virtual T removeAt(int index) = 0;             // Xóa và trả về phần tử tại index
    virtual bool removeItem(T item) = 0;           // Xóa phần tử đầu tiên có giá trị item
    virtual bool empty() const = 0;                // Kiểm tra danh sách rỗng
    virtual int size() const = 0;                  // Lấy số lượng phần tử hiện có
    virtual void clear() = 0;                      // Xóa sạch danh sách
    virtual T& get(int index) = 0;                 // Lấy tham chiếu phần tử tại index
    virtual void set(int index, T e) = 0;          // Cập nhật giá trị tại index
    virtual int indexOf(T item) const = 0;         // Tìm vị trí đầu tiên của item
    virtual bool contains(T item) const = 0;       // Kiểm tra sự tồn tại của item
};
```

---

### 3.2. Danh sách Mảng Động (ArrayList)

#### 1. Cấu trúc Bộ nhớ & Thuộc tính Thành viên:
`ArrayList` lưu trữ các phần tử trong một khối bộ nhớ mảng liên tục trên Heap:
* `T* data`: Con trỏ trỏ tới vùng nhớ mảng động.
* `int capacity`: Dung lượng lưu trữ tối đa hiện tại của mảng.
* `int count`: Số lượng phần tử thực tế đang được lưu trữ ($0 \le count \le capacity$).

```
                             TỔ CHỨC BỘ NHỚ ARRAYLIST
               +---+---+---+---+---+---+---+---+---+---+
      data --> | 4 | 7 | 2 | 9 | 1 |   |   |   |   |   |
               +---+---+---+---+---+---+---+---+---+---+
                 0   1   2   3   4   5   6   7   8   9
               | <--- count = 5 ---> | <--- unused --> |
               | <--------------- capacity = 10 --------------> |
```

#### 2. Chiến lược Tự động Tái cấp phát (Capacity Doubling Strategy):
Khi `count == capacity`, mảng bị tràn bộ đệm. Giải thuật tăng trưởng:
1. Cấp phát mảng mới với dung lượng gấp đôi: `newCapacity = capacity * 2`.
2. Sao chép toàn bộ `count` phần tử từ mảng cũ sang mảng mới.
3. Giải phóng mảng cũ: `delete[] data;`.
4. Cập nhật con trỏ `data = newData; capacity = newCapacity;`.

#### 3. Các Phép toán Cốt lõi & Phân tích Độ phức tạp:
* **Truy xuất ngẫu nhiên (`get`, `set`):** $\Theta(1)$.
  Công thức địa chỉ: $\text{Address}(A[i]) = \text{BaseAddress} + i \times \text{sizeof}(T)$.
* **Thêm vào cuối (`add(e)`):**
  - Trường hợp không tràn: $\Theta(1)$.
  - Trường hợp đầy mảng: $\Theta(n)$ (cấp phát và sao chép $n$ phần tử).
  - Chi phí phân bổ (Amortized): $O(1)$.
* **Chèn tại vị trí bất kỳ (`add(index, e)`):**
  - Cần dịch chuyển $n - index$ phần tử từ chỉ số $n-1$ lùi về $index$ sang phải 1 vị trí.
  - Vị trí đầu ($index = 0$): Xấu nhất $\implies \Theta(n)$.
  - Vị trí cuối ($index = n$): Tốt nhất $\implies O(1)$ amortized.
  - Trung bình: $\frac{n}{2}$ phép dịch chuyển $\implies \Theta(n)$.
* **Xóa tại vị trí bất kỳ (`removeAt(index)`):**
  - Cần dịch chuyển $n - index - 1$ phần tử từ $index + 1$ đến $n-1$ sang trái 1 vị trí.
  - Vị trí đầu ($index = 0$): $\Theta(n)$. Vị trí cuối ($index = n-1$): $\Theta(1)$.
  - Trung bình: $\Theta(n)$.

```cpp
template <class T>
void ArrayList<T>::add(int index, T e) {
    if (index < 0 || index > this->count) throw std::out_of_range("Index out of bounds");
    if (this->count == this->capacity) ensureCapacity(this->capacity * 2);
    for (int i = this->count; i > index; i--) {
        this->data[i] = this->data[i - 1]; // Dịch phải
    }
    this->data[index] = e;
    this->count++;
}

template <class T>
T ArrayList<T>::removeAt(int index) {
    if (index < 0 || index >= this->count) throw std::out_of_range("Index out of bounds");
    T removedItem = this->data[index];
    for (int i = index; i < this->count - 1; i++) {
        this->data[i] = this->data[i + 1]; // Dịch trái
    }
    this->count--;
    return removedItem;
}
```

---

### 3.3. Danh sách Liên kết Đơn (Singly Linked List - SLL)

#### 1. Cấu trúc Node & Quản lý Danh sách:
Mỗi phần tử được bọc trong một `Node` gồm dữ liệu và con trỏ trỏ tới node kế tiếp. Các node nằm rải rác trên Heap:
```cpp
template <class T>
struct SLLNode {
    T data;
    SLLNode<T>* next;
    SLLNode(T val, SLLNode<T>* nxt = nullptr) : data(val), next(nxt) {}
};
```
Thuộc tính thành viên: `Node* head; Node* tail; int count;`.

```
                    CẤU TRÚC DANH SÁCH LIÊN KẾT ĐƠN (SLL)
       head                                                 tail
         |                                                    |
         v                                                    v
      +----+------+     +----+------+     +----+------+     +----+------+
      | 15 | next |---->| 32 | next |---->| 8  | next |---->| 99 | null |
      +----+------+     +----+------+     +----+------+     +----+------+
```

#### 2. Kỹ thuật Nút giả (Dummy / Sentinel Node):
* **Ý tưởng:** Tạo một node rỗng cố định tại đầu danh sách `dummyHead`. Danh sách thực sự bắt đầu từ `dummyHead->next`.
* **Lợi ích:** Triệt tiêu hoàn toàn các trường hợp biên đặc biệt (thêm vào đầu, xóa node đầu, danh sách rỗng), mã nguồn không cần câu lệnh `if (head == nullptr)` hay `if (index == 0)`.

#### 3. Các Phép toán Cơ sở & Chi tiết Thuật toán:

##### A. Thêm vào đầu (Prepend / Insert First): $\Theta(1)$
```cpp
template <class T>
void SLinkedList<T>::addFirst(T e) {
    Node* newNode = new Node(e, head);
    head = newNode;
    if (tail == nullptr) tail = head;
    count++;
}
```

##### B. Thêm vào cuối (Append / Insert Last): $\Theta(1)$ (Khi có con trỏ `tail`)
```cpp
template <class T>
void SLinkedList<T>::addLast(T e) {
    Node* newNode = new Node(e, nullptr);
    if (tail == nullptr) {
        head = tail = newNode;
    } else {
        tail->next = newNode;
        tail = newNode;
    }
    count++;
}
```

##### C. Chèn tại vị trí bất kỳ (`add(index, e)`): $\Theta(n)$
* Phải duyệt $index - 1$ bước từ `head` để tìm con trỏ `pre`.
* Nối con trỏ: `newNode->next = pre->next; pre->next = newNode;`.

##### D. Xóa phần tử đầu tiên (Remove First): $\Theta(1)$
```cpp
template <class T>
T SLinkedList<T>::removeFirst() {
    if (head == nullptr) throw std::underflow_error("List is empty");
    Node* temp = head;
    T val = temp->data;
    head = head->next;
    if (head == nullptr) tail = nullptr;
    delete temp;
    count--;
    return val;
}
```

##### E. Xóa phần tử cuối cùng (Remove Last): $\Theta(n)$
> [!IMPORTANT]
> **BẪY ĐỀ THI KINH ĐIỂN:** Mặc dù danh sách liên kết đơn có con trỏ `tail` cho phép thêm cuối trong $\Theta(1)$, nhưng thao tác **xóa phần tử cuối cùng BẮT BUỘC tốn thời gian $\Theta(n)$**! Nguyên nhân là vì con trỏ chỉ đi một chiều, để cập nhật `tail` mới ta buộc phải duyệt từ `head` đến node áp chót (`pre`) sao cho `pre->next == tail`.

##### F. Thuật toán Đảo ngược Danh sách Liên kết Đơn Tại chỗ (In-Place Reverse SLL):
* **Yêu cầu:** Không cấp phát node mới, chỉ đổi chiều các liên kết con trỏ.
* **Thời gian:** $\Theta(n)$, **Bộ nhớ phụ:** $\Theta(1)$.
* **Kỹ thuật 3 con trỏ:** `prev` (đã đảo), `curr` (đang xử lý), `next` (lưu vết node kế tiếp).

```cpp
template <class T>
void SLinkedList<T>::reverse() {
    Node* prev = nullptr;
    Node* curr = head;
    Node* nextNode = nullptr;
    tail = head; // Head cũ trở thành Tail mới
    while (curr != nullptr) {
        nextNode = curr->next; // 1. Lưu lại node kế tiếp
        curr->next = prev;     // 2. Đảo ngược mũi tên con trỏ
        prev = curr;           // 3. Tiến prev lên vị trí curr
        curr = nextNode;       // 4. Tiến curr lên vị trí kế tiếp
    }
    head = prev; // Prev trở thành Head mới
}
```

---

### 3.4. Danh sách Liên kết Đôi (Doubly Linked List - DLL)

#### 1. Cấu trúc Node:
Mỗi node chứa 2 con trỏ: `next` (trỏ tới node sau) và `prev` (trỏ tới node trước).
```cpp
template <class T>
struct DNode {
    T data;
    DNode<T>* prev;
    DNode<T>* next;
    DNode(T val, DNode* p = nullptr, DNode* n = nullptr) : data(val), prev(p), next(n) {}
};
```

```
                    CẤU TRÚC DANH SÁCH LIÊN KẾT ĐÔI (DLL)
         head                                                 tail
           |                                                    |
           v                                                    v
         +----+----+----+     +----+----+----+     +----+----+----+
  null <-|prev| 10 |next|<===>|prev| 20 |next|<===>|prev| 30 |next|-> null
         +----+----+----+     +----+----+----+     +----+----+----+
```

#### 2. Ưu thế Vượt trội của DLL so với SLL:
1. **Duyệt hai chiều:** Cho phép duyệt tiến từ `head` hoặc duyệt lùi từ `tail`.
2. **Xóa node khi biết con trỏ trong $\Theta(1)$:** Không cần tìm node tiền nhiệm `pre`:
   ```cpp
   void removeNode(DNode* node) {
       if (node->prev) node->prev->next = node->next;
       else head = node->next;
       if (node->next) node->next->prev = node->prev;
       else tail = node->prev;
       delete node;
       count--;
   }
   ```
3. **Xóa cuối (`removeLast`):** Đạt thời gian $\Theta(1)$ vì đã có `tail->prev`!
4. **Nhược điểm:** Tốn thêm bộ nhớ cho con trỏ `prev` (8 byte/node) và mã nguồn cập nhật con trỏ phức tạp hơn.

---

### 3.5. Danh sách Liên kết Vòng (Circular Linked List - CLL)

#### 1. Nguyên lý Cấu tạo:
* Node cuối cùng không trỏ về `nullptr` mà trỏ ngược về `head` (`tail->next == head`).
* **Kỹ thuật Tối ưu hóa Thiết kế:** Chỉ cần lưu trữ **duy nhất 1 con trỏ `tail`**!
  - Truy xuất phần tử đuôi: `tail` $\implies O(1)$.
  - Truy xuất phần tử đầu: `tail->next` $\implies O(1)$.
  - Thêm đầu (`addFirst`): Tạo node mới, `newNode->next = tail->next; tail->next = newNode;` $\implies O(1)$.
  - Thêm cuối (`addLast`): Giống `addFirst` nhưng cập nhật thêm `tail = newNode;` $\implies O(1)$.

```
                     DANH SÁCH LIÊN KẾT VÒNG ĐƠN (CLL)
                                tail
                                 |
                                 v
                 +---->+----+------+     +----+------+
                 |     | 10 | next |---->| 20 | next |----+
                 |     +----+------+     +----+------+    |
                 |                                        |
                 +----------------------------------------+
```

#### 2. Ứng dụng Thực tế:
* Thuật toán lập lịch điều phối luân phiên Round-Robin của Hệ điều hành.
* Bộ đệm vòng (Ring Buffer) trong truyền thông stream âm thanh, video.
* Bài toán Josephus: Loại người thứ $k$ liên tục trên vòng tròn $n$ người.

---

### 3.6. Danh sách Đa liên kết & Biểu diễn Ma trận Thưa (Sparse Matrix)

#### 1. Ma trận Thưa (Sparse Matrix):
Là ma trận có đại đa số các phần tử mang giá trị $0$. Nếu lưu bằng mảng 2 chiều thông thường `A[R][C]`, ta lãng phí $\Theta(R \times C)$ bộ nhớ.

#### 2. Biểu diễn bằng Danh sách Trực giao (Cross-linked / Orthogonal Multi-linked List):
Mỗi phần tử khác 0 được lưu trữ bằng một node chứa 5 trường:
`struct MatrixNode { int row; int col; double value; MatrixNode* nextRow; MatrixNode* nextCol; };`
* `rowHead[R]`: Mảng các con trỏ đầu hàng. Mỗi hàng là một danh sách liên kết đơn các phần tử khác 0 theo thứ tự cột tăng dần (`nextCol`).
* `colHead[C]`: Mảng các con trỏ đầu cột. Mỗi cột là một danh sách liên kết đơn các phần tử khác 0 theo thứ tự hàng tăng dần (`nextRow`).
* **Hiệu năng:** Giảm bộ nhớ từ $O(R \times C)$ xuống $O(R + C + K)$ với $K$ là số phần tử khác không ($K \ll R \times C$).

---

### 3.7. Bảng So sánh Toàn diện Các Cấu trúc Danh sách

| Thao tác / Đặc tính | Mảng Động (ArrayList) | Danh sách LK Đơn (SLL) | Danh sách LK Đôi (DLL) | Danh sách LK Vòng (CLL) |
| :--- | :---: | :---: | :---: | :---: |
| **Truy xuất theo chỉ số (`get(i)`)** | **$\Theta(1)$ (Ngẫu nhiên)** | $\Theta(n)$ | $\Theta(n)$ | $\Theta(n)$ |
| **Thêm vào đầu (`addFirst`)** | $\Theta(n)$ (Dịch phải) | **$\Theta(1)$** | **$\Theta(1)$** | **$\Theta(1)$** |
| **Thêm vào cuối (`addLast`)** | $\Theta(1)$ amortized | **$\Theta(1)$ (Có tail)** | **$\Theta(1)$** | **$\Theta(1)$** |
| **Chèn giữa (`add(i, e)`)** | $\Theta(n)$ | $\Theta(n)$ | $\Theta(n)$ | $\Theta(n)$ |
| **Xóa ở đầu (`removeFirst`)** | $\Theta(n)$ (Dịch trái) | **$\Theta(1)$** | **$\Theta(1)$** | **$\Theta(1)$** |
| **Xóa ở cuối (`removeLast`)** | **$\Theta(1)$** | **$\Theta(n)$ (Phải tìm pre)** | **$\Theta(1)$ (Nhờ prev)** | $\Theta(n)$ (Nếu vòng đơn) |
| **Xóa khi biết con trỏ tới node** | Không hỗ trợ trực tiếp | $\Theta(n)$ | **$\Theta(1)$** | $\Theta(n)$ |
| **Chi phí bộ nhớ phụ (Overhead)** | Rất thấp (chỉ vùng trống) | 1 con trỏ / node (8B) | 2 con trỏ / node (16B) | 1 con trỏ / node (8B) |
| **Tính cục bộ bộ nhớ đệm (Cache)** | **Tuyệt vời (Liên tục)** | Rất kém (Rải rác) | Rất kém (Rải rác) | Rất kém (Rải rác) |

---

## CHƯƠNG 4: NGĂN XẾP & HÀNG ĐỢI (STACKS, QUEUES & DEQUES)

---

### 4.1. Ngăn xếp (Stack ADT - LIFO)

#### 1. Định nghĩa & Nguyên lý:
Ngăn xếp là cấu trúc dữ liệu tuyến tính hoạt động theo nguyên lý **Vào sau - Ra trước (Last-In, First-Out - LIFO)**. Mọi thao tác thêm và lấy phần tử chỉ diễn ra tại một đầu duy nhất gọi là **Đỉnh ngăn xếp (Top)**.

```
                         CƠ CHẾ HOẠT ĐỘNG CỦA STACK
                              |   push(X)      ^  pop()
                              v                |
                           +----------------------+
                     Top ->|      Phần tử D       |
                           +----------------------+
                           |      Phần tử C       |
                           +----------------------+
                           |      Phần tử B       |
                           +----------------------+
                           |      Phần tử A       |
                           +----------------------+
```

#### 2. Các Phép toán Chuẩn của Stack ADT:
* `push(x)`: Đẩy phần tử `x` vào đỉnh ngăn xếp ($\Theta(1)$).
* `pop()`: Lấy và loại bỏ phần tử ở đỉnh ngăn xếp ra khỏi stack ($\Theta(1)$). Ném lỗi `underflow` nếu rỗng.
* `top()` / `peek()`: Trả về giá trị phần tử tại đỉnh mà không xóa ($\Theta(1)$).
* `empty()`: Kiểm tra ngăn xếp rỗng ($\Theta(1)$).
* `size()`: Trả về số lượng phần tử hiện hữu ($\Theta(1)$).

#### 3. Cài đặt Ngăn xếp: Mảng Động vs Danh sách Liên kết:
* **Cài đặt bằng Mảng động (`ArrayList`):**
  - Đỉnh stack chọn là chỉ số `count - 1` (cuối mảng).
  - Cả `push` và `pop` đều là thao tác tại đuôi $\implies$ Chi phí Amortized $\Theta(1)$, tận dụng tối đa CPU cache.
* **Cài đặt bằng Danh sách liên kết (`SLinkedList`):**
  - Đỉnh stack chọn là con trỏ `head` (đầu danh sách).
  - `push` $\iff$ `addFirst(x)` ($\Theta(1)$).
  - `pop` $\iff$ `removeFirst()` ($\Theta(1)$).
  - Không bao giờ bị giới hạn dung lượng, không tốn chi phí copy khi mảng đầy.

---

### 4.2. Các Ứng dụng Kinh điển của Ngăn xếp

#### Ứng dụng 1: Kiểm tra Dấu Ngoặc Hợp lệ (Balanced Parentheses):
Bài toán kiểm tra chuỗi chứa các cặp ngoặc `()`, `[]`, `{}` có đóng mở đúng quy cách hay không.
* **Giải thuật:**
  1. Khởi tạo một stack rỗng.
  2. Duyệt từng ký tự trong chuỗi từ trái qua phải:
     - Nếu gặp dấu ngoặc mở (`(`, `[`, `{`): `push` vào stack.
     - Nếu gặp dấu ngoặc đóng (`)`, `]`, `}`):
       - Nếu stack rỗng $\implies$ **Không hợp lệ** (thiếu ngoặc mở).
       - Ngược lại, `topChar = pop()`. Nếu `topChar` không cùng loại với dấu ngoặc đóng hiện tại $\implies$ **Không hợp lệ** (sai thứ tự lồng nhau).
  3. Kết thúc chuỗi: Nếu stack rỗng $\implies$ **Hợp lệ**; nếu stack còn phần tử $\implies$ **Không hợp lệ** (thừa ngoặc mở).
* **Độ phức tạp:** Thời gian $\Theta(n)$, Không gian $O(n)$.

#### Ứng dụng 2: Thuật toán Shunting-Yard Chuyển Trung tố (Infix) sang Hậu tố (Postfix):
Do nhà khoa học máy tính Edsger Dijkstra phát minh năm 1961.

##### 1. Khái niệm Ký pháp:
* **Trung tố (Infix):** Toán tử nằm giữa hai toán hạng: `A + B`. Cần dùng ngoặc để xác định độ ưu tiên: `(A + B) * C`.
* **Hậu tố (Postfix / Reverse Polish Notation - RPN):** Toán tử nằm sau hai toán hạng: `A B +`. Hoàn toàn không cần dùng dấu ngoặc, thứ tự thực hiện được xác định duy nhất từ trái qua phải!
* **Tiền tố (Prefix / Polish Notation):** Toán tử nằm trước hai toán hạng: `+ A B`.

##### 2. Bảng Độ ưu tiên (Precedence) & Tính Kết hợp (Associativity):

| Toán tử | Ý nghĩa toán học | Độ ưu tiên (Precedence) | Tính kết hợp (Associativity) |
| :---: | :--- | :---: | :---: |
| `^` | Lũy thừa ($a^b$) | **3 (Cao nhất)** | **Phải sang Trái (Right-to-Left)** |
| `*`, `/`, `%` | Nhân, Chia, Chia dư | **2** | **Trái sang Phải (Left-to-Right)** |
| `+`, `-` | Cộng, Trừ | **1 (Thấp nhất)** | **Trái sang Phải (Left-to-Right)** |

##### 3. Quy tắc Thuật toán Shunting-Yard:
Duyệt biểu thức Infix từ trái sang phải:
1. **Nếu là Toán hạng (Số, Biến):** Xuất thẳng ra chuỗi kết quả đầu ra.
2. **Nếu là Dấu ngoặc mở `(`:** `push` vào stack toán tử.
3. **Nếu là Dấu ngoặc đóng `)`:** Liên tục `pop` toán tử từ stack và xuất ra đầu ra cho đến khi gặp dấu ngoặc mở `(`. Bỏ dấu ngoặc mở `(` đi (không xuất ra đầu ra).
4. **Nếu là Toán tử $op_1$:**
   - Trong khi stack không rỗng VÀ đỉnh stack $op_2 \ne '('$ VÀ:
     - [$op_1$ kết hợp trái VÀ $\text{prec}(op_1) \le \text{prec}(op_2)$] HOẶC
     - [$op_1$ kết hợp phải VÀ $\text{prec}(op_1) < \text{prec}(op_2)$]
     $\implies$ `pop` $op_2$ ra đầu ra.
   - `push` $op_1$ vào stack.
5. **Kết thúc chuỗi:** `pop` toàn bộ toán tử còn lại trong stack ra đầu ra.

##### 4. Bảng Tracing Chi tiết Biểu thức: `A + B * C - (D / E ^ F) * G`

| Bước | Token đọc vào | Hành động xử lý | Trạng thái Stack Toán tử (Đỉnh bên phải) | Chuỗi Hậu tố Đầu ra (Postfix Output) |
| :---: | :---: | :--- | :--- | :--- |
| 1 | `A` | Toán hạng $\to$ Xuất ra | rỗng | `A` |
| 2 | `+` | Push vào stack | `+` | `A` |
| 3 | `B` | Toán hạng $\to$ Xuất ra | `+` | `A B` |
| 4 | `*` | $\text{prec}(*) > \text{prec}(+) \implies$ Push | `+ *` | `A B` |
| 5 | `C` | Toán hạng $\to$ Xuất ra | `+ *` | `A B C` |
| 6 | `-` | $\text{prec}(-) \le \text{prec}(*) \implies$ Pop `*`; $\text{prec}(-) \le \text{prec}(+) \implies$ Pop `+`; Push `-` | `-` | `A B C * +` |
| 7 | `(` | Push vào stack | `- (` | `A B C * +` |
| 8 | `D` | Toán hạng $\to$ Xuất ra | `- (` | `A B C * + D` |
| 9 | `/` | Push vào stack | `- ( /` | `A B C * + D` |
| 10| `E` | Toán hạng $\to$ Xuất ra | `- ( /` | `A B C * + D E` |
| 11| `^` | $\text{prec}(\text{\textasciicircum}) > \text{prec}(/) \implies$ Push | `- ( / ^` | `A B C * + D E` |
| 12| `F` | Toán hạng $\to$ Xuất ra | `- ( / ^` | `A B C * + D E F` |
| 13| `)` | Pop tới khi gặp `(`: Pop `^`, Pop `/`, Bỏ `(` | `-` | `A B C * + D E F ^ /` |
| 14| `*` | $\text{prec}(*) > \text{prec}(-) \implies$ Push | `- *` | `A B C * + D E F ^ /` |
| 15| `G` | Toán hạng $\to$ Xuất ra | `- *` | `A B C * + D E F ^ / G` |
| 16| Hết chuỗi | Pop toàn bộ: Pop `*`, Pop `-` | rỗng | `A B C * + D E F ^ / G * -` |

#### Ứng dụng 3: Tính Giá trị Biểu thức Hậu tố (Postfix Evaluation):
* **Giải thuật:**
  1. Duyệt biểu thức Postfix từ trái sang phải:
  2. Nếu token là Toán hạng (Số): `push` giá trị vào stack toán hạng.
  3. Nếu token là Toán tử hai ngôi $op$:
     - $val_2 = \text{pop}()$
     - $val_1 = \text{pop}()$
     - Tính kết quả $res = val_1 \text{ op } val_2$.
     - `push` $res$ trở lại stack.
  4. Sau khi duyệt hết biểu thức, giá trị duy nhất còn lại trong stack chính là kết quả của biểu thức.

---

### 4.3. Hàng đợi (Queue ADT - FIFO) & Hàng đợi Vòng trên Mảng (Circular Queue)

#### 1. Định nghĩa & Nguyên lý:
Hàng đợi là cấu trúc dữ liệu tuyến tính hoạt động theo nguyên lý **Vào trước - Ra trước (First-In, First-Out - FIFO)**. Thao tác thêm phần tử diễn ra ở **Đuôi (Rear / Back)** và thao tác lấy phần tử diễn ra ở **Đầu (Front)**.

```
                         CƠ CHẾ HOẠT ĐỘNG CỦA QUEUE
               dequeue()                               enqueue(X)
                  <---  +---+---+---+---+---+---+---+  <---
                        | 1 | 5 | 8 | 2 | 9 |   |   |
                        +---+---+---+---+---+---+---+
                        Front               Rear
```

#### 2. Hiện tượng Tràn Ảo trên Mảng Tuyến tính & Giải pháp Hàng đợi Vòng (Circular Queue):
* **Hiện tượng Tràn ảo (False Overflow):** Nếu dùng mảng cố định không quay vòng, sau nhiều lần `enqueue` và `dequeue`, `rear` sẽ chạm cuối mảng (`capacity - 1`) trong khi các ô nhớ đầu mảng bị bỏ trống. Việc dịch chuyển toàn bộ mảng sang trái mỗi khi `dequeue` sẽ tốn chi phí nặng nề $\Theta(n)$.
* **Giải pháp Hàng đợi Vòng (Circular Array Queue):** Cho phép `front` và `rear` quay vòng về đầu mảng bằng phép toán đồng dư (modulo arithmetic):
  $$\text{front} = (\text{front} + 1) \bmod N; \quad \text{rear} = (\text{rear} + 1) \bmod N$$

```
                           HÀNG ĐỢI VÒNG (CIRCULAR QUEUE)
                                       [0]
                                  /           \
                             [7]                 [1]
                            /                       \
                          [6]                       [2]
                            \                       /
                             [5]                 [3]
                                  \           /
                                       [4]
```

#### 3. Xử lý Vấn đề Nhập nhằng Trống vs Đầy (Queue Full vs Empty Ambiguity):
Cả hai trạng thái Hàng đợi Đầy và Hàng đợi Rỗng đều dẫn đến điều kiện `front == rear`.

* **Chiến lược 1: Giữ trống 1 ô nhớ (One-slot open / Wasting one cell - Chuẩn giáo trình HCMUT):**
  - Mảng có kích thước $N$ chỉ dùng để lưu trữ tối đa $N - 1$ phần tử.
  - **Điều kiện Hàng đợi RỖNG:**
    $$\text{front} == \text{rear}$$
  - **Điều kiện Hàng đợi ĐẦY:**
    $$(\text{rear} + 1) \bmod N == \text{front}$$
* **Chiến lược 2: Sử dụng thêm biến đếm tường minh `count`:**
  - Mảng $N$ ô lưu đủ $N$ phần tử.
  - Hàng đợi RỖNG $\iff count == 0$.
  - Hàng đợi ĐẦY $\iff count == N$.

```cpp
template <class T>
class CircularQueue {
private:
    T* data;
    int capacity; // Kích thước mảng N
    int front;    // Chỉ số phần tử đầu
    int rear;     // Chỉ số phần tử kế tiếp sau đuôi
public:
    CircularQueue(int cap = 100) : capacity(cap + 1), front(0), rear(0), data(new T[cap + 1]) {}
    ~CircularQueue() { delete[] data; }

    bool empty() const { return front == rear; }
    bool full() const { return (rear + 1) % capacity == front; }

    void enqueue(T e) {
        if (full()) throw std::overflow_error("Queue is full");
        data[rear] = e;
        rear = (rear + 1) % capacity;
    }

    T dequeue() {
        if (empty()) throw std::underflow_error("Queue is empty");
        T val = data[front];
        front = (front + 1) % capacity;
        return val;
    }

    T peek() const {
        if (empty()) throw std::underflow_error("Queue is empty");
        return data[front];
    }
};
```

---

### 4.4. Hàng đợi Hai đầu (Deque) & Ứng dụng Hàng đợi trong Mô phỏng Hệ thống

* **Hàng đợi Hai đầu (Deque - Double-Ended Queue):**
  Cho phép thực hiện thao tác thêm và xóa ở cả hai đầu trong thời gian $\Theta(1)$: `push_front`, `push_back`, `pop_front`, `pop_back`.
* **Ứng dụng của Hàng đợi:**
  1. **Thuật toán Duyệt Đồ thị theo Chiều rộng (BFS):** Đảm bảo duyệt các đỉnh theo thứ tự khoảng cách ngắn nhất về số cạnh.
  2. **Điều phối tiến trình CPU:** Quản lý hàng đợi Ready Queue trong các hệ điều hành đa nhiệm.
  3. **Hệ thống đệm I/O (Buffering):** Xử lý luồng dữ liệu không đồng bộ giữa nơi gửi nhanh và nơi nhận chậm (bộ đệm bàn phím, print spooler, streaming mạng).

# PHẦN III: THUẬT TOÁN TÌM KIẾM, SẮP XẾP & CẤU TRÚC BẢNG BĂM

---

## CHƯƠNG 5: THUẬT TOÁN TÌM KIẾM & CẤU TRÚC BẢNG BĂM (SEARCHING & HASH TABLES)

---

### 5.1. Các Giải thuật Tìm kiếm Cổ điển

Tìm kiếm là quá trình xác định vị trí của một phần tử mang giá trị khóa $k$ (Target Key) trong một tập dữ liệu, hoặc khẳng định khóa đó không tồn tại.

#### 1. Tìm kiếm Tuần tự (Sequential / Linear Search):
* **Mảng chưa có thứ tự:** Duyệt tuần tự từ phần tử đầu tiên đến phần tử cuối cùng.
  - Tốt nhất: Thấy ngay tại $A[0] \implies \Theta(1)$.
  - Xấu nhất: Không tìm thấy hoặc nằm ở $A[n-1] \implies \Theta(n)$.
  - Trung bình: $\frac{n+1}{2} \implies \Theta(n)$.
* **Mảng đã sắp xếp:** Cho phép dừng sớm ngay khi gặp $A[i] > k$. Số phép so sánh trung bình giảm còn một nửa nhưng độ phức tạp tiệm cận vẫn là $\Theta(n)$.
* **Kỹ thuật Lính canh (Sentinel Linear Search):**
  - Gán giá trị cần tìm vào cuối mảng: $A[n] = key$.
  - Vòng lặp `while (A[i] != key) i++;` loại bỏ hoàn toàn phép kiểm tra biên `i < n` trong mỗi bước lặp, giúp tăng tốc độ thực thi trong thực tế dù độ phức tạp vẫn là $\Theta(n)$.

#### 2. Tìm kiếm Nhị phân (Binary Search / Interval Search):
* **Điều kiện tiên quyết:** Dữ liệu bắt buộc phải được **sắp xếp theo thứ tự** VÀ cấu trúc dữ liệu phải hỗ trợ **truy xuất ngẫu nhiên trong $\Theta(1)$** (như Mảng hoặc ArrayList).
  > [!NOTE]
  > Tìm kiếm nhị phân KHÔNG áp dụng hiệu quả trên Danh sách Liên kết (Linked List) vì thao tác tìm trung điểm của linked list tốn $O(n)$, làm độ phức tạp tổng thể thoái hóa thành $O(n)$!

* **Giải thuật:** Duyệt theo chiến lược Chia để trị:
  $$\text{mid} = \text{low} + \left\lfloor \frac{\text{high} - \text{low}}{2} \right\rfloor$$
  *(Dùng công thức trên để tránh lỗi tràn số nguyên khi `low + high > INT_MAX`)*.
  - Nếu $A[mid] == key$: Tìm thấy, trả về `mid`.
  - Nếu $A[mid] > key$: Thu hẹp không gian tìm kiếm sang nửa trái: $high = mid - 1$.
  - Nếu $A[mid] < key$: Thu hẹp không gian tìm kiếm sang nửa phải: $low = mid + 1$.
* **Hệ thức truy hồi:** $T(n) = T(n/2) + \Theta(1) \implies \Theta(\log_2 n)$.

#### 3. Tìm kiếm Nội suy (Interpolation Search):
* **Nguyên lý:** Mô phỏng cách con người tra cứu từ điển: nếu tìm từ bắt đầu bằng chữ 'Z', ta mở gần cuối sách thay vì lật đúng trang chính giữa.
* **Điều kiện áp dụng:** Dữ liệu đã sắp xếp và các khóa **phân phối tương đối đều (Uniformly Distributed)**.
* **Công thức Nội suy Tuyến tính:**
  $$\text{pos} = \text{low} + \left\lfloor \frac{key - A[\text{low}]}{A[\text{high}] - A[\text{low}]} \times (\text{high} - \text{low}) \right\rfloor$$
* **Phân tích Hiệu năng:**
  - **Trường hợp Phân phối Đều (Average Case):** Cực kỳ ấn tượng: $\Theta(\log_2(\log_2 n))$. Với một tỷ phần tử ($n = 10^9$), thuật toán chỉ mất khoảng $\approx 5$ lần so sánh!
  - **Trường hợp Phân phối Lệch (Worst Case):** Khi dữ liệu tăng theo hàm mũ (ví dụ: $1, 2, 4, 8, 16, \dots, 2^n$), vị trí ước lượng luôn lệch về một đầu $\implies \Theta(n)$.

---

### 5.2. Nguyên lý Bảng băm (Hash Tables) & Địa chỉ Trực tiếp

#### 1. Bảng Địa chỉ Trực tiếp (Direct Addressing):
* Ánh xạ mỗi khóa $k$ trực tiếp vào ô nhớ $T[k]$. Thao tác `search`, `insert`, `delete` đều đạt $\Theta(1)$ tuyệt đối.
* **Hạn chế nghiêm trọng:** Bất khả thi nếu không gian khóa vũ trụ $U$ quá lớn so với số lượng phần tử thực tế $n$ ($|U| \gg n$, ví dụ: mã định danh 12 chữ số, chuỗi ký tự tên người). Việc cấp phát mảng kích thước $|U|$ sẽ làm tràn RAM.

#### 2. Cấu trúc Bảng băm (Hash Table Structure):
* Bảng băm là mảng $T$ gồm $m$ vị trí ($m \ll |U|$).
* **Hàm băm (Hash Function):** Ánh xạ khóa $k \in U$ thành một địa chỉ chỉ số hợp lệ trong bảng:
  $$h: U \to \{0, 1, 2, \dots, m - 1\}$$
* **Hệ số tải (Load Factor - $\alpha$):**
  $$\alpha = \frac{n}{m}$$
  Phản ánh mật độ chiếm đóng trung bình của bảng băm ($n$ là số phần tử đang lưu, $m$ là kích thước bảng).

#### 3. Hiện tượng Va chạm (Collision):
Theo **Nguyên lý Dirichlet (Pigeonhole Principle)**, vì $|U| > m$ nên chắc chắn luôn tồn tại ít nhất hai khóa khác nhau $k_1 \ne k_2$ sao cho $h(k_1) = h(k_2)$. Đây gọi là sự va chạm (Collision). Một bảng băm bắt buộc phải có cơ chế giải quyết va chạm hiệu quả.

---

### 5.3. Các Kỹ thuật Thiết kế Hàm băm (Hash Functions)

Tiêu chí của một hàm băm chuẩn mực: (1) Tính toán trong $\Theta(1)$; (2) Phân tán đều các khóa trên toàn bộ không gian địa chỉ $0 \dots m-1$; (3) Giảm thiểu va chạm.

1. **Phép chia Modulo (Division Method):**
   $$h(k) = k \bmod m$$
   - **Quy tắc chọn $m$:** $m$ nên là một **số nguyên tố** không quá gần lũy thừa của 2 ($2^p$) hoặc lũy thừa của 10 ($10^p$). Nếu chọn $m = 2^p$, $h(k)$ sẽ chỉ phụ thuộc vào $p$ bit thấp nhất của $k$, bỏ qua hoàn toàn các bit cao!
2. **Bình phương Giữa (Mid-square Method):**
   - Bình phương khóa $k$ để nhận $k^2$, sau đó trích xuất $r$ chữ số ở chính giữa làm địa chỉ. Kích thước bảng chọn là $m = 10^r$ (hoặc $m = 2^r$).
   - *Ưu điểm:* Mọi chữ số của $k$ đều tham gia vào việc tạo ra các chữ số ở giữa của $k^2$.
3. **Phương pháp Gấp (Folding Method):**
   - Chia khóa $k$ thành nhiều phần bằng nhau có độ dài bằng số chữ số của địa chỉ.
   - **Fold Shift:** Cộng trực tiếp các phần: $h(k) = (p_1 + p_2 + \dots + p_s) \bmod m$.
   - **Fold Boundary:** Đảo ngược các phần ở biên trước khi thực hiện phép cộng.
4. **Rút trích Chữ số (Digit Extraction):**
   - Trích chọn các vị trí chữ số có độ phân bố đồng đều nhất (ví dụ: lấy chữ số thứ 3, 5, 6 của mã sinh viên để tránh trùng lặp năm nhập học và mã khoa).
5. **Băm Chuỗi Ký tự (Polynomial Rolling Hash):**
   Áp dụng Quy tắc Horner để tính toán trong $O(L)$ thời gian mà không bị tràn số:
   $$h(s) = \left( \sum_{i=0}^{L-1} s[i] \cdot p^{L-1-i} \right) \bmod m \iff h = (h \cdot p + s[i]) \bmod m$$
   *(Thường chọn hằng số $p = 31$ hoặc $53$, $m = 10^9 + 7$ hoặc $10^9 + 9$)*.

---

### 5.4. Chiến lược Giải quyết Va chạm I: Địa chỉ Mở (Open Addressing / Closed Hashing)

Tất cả các phần tử đều được lưu trữ trực tiếp bên trong mảng $T[0 \dots m-1]$. Mỗi ô nhớ chỉ chứa tối đa đúng một phần tử $\implies$ Hệ số tải bắt buộc phải thỏa mãn $\alpha \le 1$.

Khi xảy ra va chạm tại ô $h'(k)$, thuật toán sẽ thực hiện một chuỗi các lần thăm dò (Probes) cho đến khi tìm được một ô còn trống:
$$h(k, i) = (h'(k) + f(i)) \bmod m \quad (i = 0, 1, 2, \dots, m-1)$$

```
                     BA CHIẾN LƯỢC THĂM DÒ TRONG ĐỊA CHỈ MỞ
   Linear Probing:      h(k, i) = (h'(k) + i) mod m        --> Buoc nhay: +1, +2, +3, +4
   Quadratic Probing:   h(k, i) = (h'(k) + i^2) mod m      --> Buoc nhay: +1, +4, +9, +16
   Double Hashing:      h(k, i) = (h1(k) + i*h2(k)) mod m  --> Buoc nhay phu thuoc k!
```

#### 1. Thăm dò Tuyến tính (Linear Probing):
* Hàm bước nhảy: $f(i) = i \implies h(k, i) = (h'(k) + i) \bmod m$.
* **Hiện tượng Cụm Sơ cấp (Primary Clustering):**
  Khi các ô liền kề bị chiếm đóng, chúng tạo thành một "khối" (cluster) dài liên tục. Bất kỳ khóa nào băm trúng vào bất kỳ vị trí nào trong khối này đều phải chạy dọc hết cả khối rồi mở rộng khối đó thêm 1 ô. Cụm càng dài càng hút nhiều va chạm, làm thời gian tìm kiếm suy biến nghiêm trọng!

#### 2. Thăm dò Bậc hai (Quadratic Probing):
* Hàm bước nhảy: $f(i) = c_1 i + c_2 i^2$ (dạng chuẩn: $f(i) = i^2 \implies h(k, i) = (h'(k) + i^2) \bmod m$).
* Các vị trí thăm dò cách xa nhau: $+1, +4, +9, +16, \dots$ giúp triệt tiêu hiện tượng Cụm Sơ cấp.
* **Hiện tượng Cụm Thứ cấp (Secondary Clustering):**
  Hai khóa khác nhau nhưng có cùng giá trị băm ban đầu ($h'(k_1) = h'(k_2)$) sẽ duyệt qua chuỗi thăm dò giống hệt nhau.
* **Định lý Phủ Kín:** Nếu $m$ là số nguyên tố và $\alpha \le 0.5$, thăm dò bậc hai bảo đảm luôn tìm được ô trống nếu bảng còn chỗ.

#### 3. Băm kép (Double Hashing):
* Hàm bước nhảy: $f(i) = i \cdot h_2(k) \implies h(k, i) = (h_1(k) + i \cdot h_2(k)) \bmod m$.
* **Ưu điểm tối thượng:** Bước nhảy thăm dò phụ thuộc vào chính giá trị của khóa $k$. Hai khóa dù có cùng $h_1(k)$ nhưng sẽ có bước nhảy $h_2(k)$ hoàn toàn khác nhau $\implies$ **Triệt tiêu hoàn toàn cả Cụm Sơ cấp lẫn Cụm Thứ cấp**!
* **Quy tắc chọn $h_2(k)$:** $h_2(k)$ bắt buộc phải nguyên tố cùng nhau với $m$ ($\gcd(h_2(k), m) = 1$) và không bao giờ được trả về giá trị $0$.
  - Nếu $m$ nguyên tố: Chọn $h_2(k) = 1 + (k \bmod (m - 1))$ hoặc $h_2(k) = R - (k \bmod R)$ với $R < m$ là số nguyên tố.

#### 4. Thao tác Xóa trong Địa chỉ Mở & Kỹ thuật Cờ hiệu `DELETED` (Tombstone):
> [!CAUTION]
> Trong Open Addressing, khi xóa một phần tử, **tuyệt đối không được gán ô nhớ đó về `EMPTY / NULL`**! Nếu gán về `EMPTY`, thao tác `search` cho các phần tử được chèn sau đó sẽ dừng lại ngay tại ô trống này và kết luận sai rằng phần tử không tồn tại.
> **Giải pháp:** Gán ô bị xóa một giá trị đặc biệt gọi là **Tombstone (`DELETED`)**.
> - Thao tác `search`: Coi ô `DELETED` như ô đang bận và tiếp tục dò tiếp.
> - Thao tác `insert`: Được phép ghi đè phần tử mới vào ô mang cờ `DELETED`.

---

### 5.5. Chiến lược Giải quyết Va chạm II: Nối kết Riêng biệt (Separate Chaining / Open Hashing)

#### 1. Cấu trúc Hoạt động:
Mỗi ô của bảng băm $T[i]$ là một con trỏ trỏ tới đầu một danh sách liên kết (Bucket). Tất cả các phần tử có cùng giá trị băm $h(k) == i$ đều được móc vào danh sách này.

```
                     BẢNG BĂM NỐI KẾT RIÊNG BIỆT (SEPARATE CHAINING)
        Index
         [0] ---> null
         [1] ---> [ 15 | • ] ---> [ 29 | • ] ---> null
         [2] ---> [ 44 | • ] ---> null
         [3] ---> null
         [4] ---> [ 18 | • ] ---> [ 32 | • ] ---> [ 74 | • ] ---> null
```

#### 2. Phân tích Hiệu năng (Giả thiết Băm đều Đơn giản - Simple Uniform Hashing):
* Chiều dài trung bình của mỗi danh sách liên kết chính là hệ số tải: $\alpha = n / m$.
* Hệ số tải $\alpha$ trong Separate Chaining **hoàn toàn có thể lớn hơn 1** ($\alpha > 1$).
* **Thao tác thêm (`insert`):** Thêm vào đầu danh sách liên kết $\implies \Theta(1)$.
* **Tìm kiếm không thành công (Unsuccessful Search):** Phải duyệt hết danh sách liên kết $\implies \Theta(1 + \alpha)$ phép so sánh.
* **Tìm kiếm thành công (Successful Search):**
  Cần duyệt qua một nửa số phần tử được chèn sau nó trong cùng bucket $\implies 1 + \frac{\alpha}{2} = \Theta(1 + \alpha)$ phép so sánh.
* **Kết luận:** Nếu duy trì $m = \Theta(n)$ sao cho $\alpha = O(1)$, mọi thao tác `search`, `insert`, `delete` đều đạt thời gian kỳ vọng là $\Theta(1)$!

---

### 5.6. Bảng So sánh Hiệu năng Tra cứu theo Hệ số Tải $\alpha$

| Phương pháp Giải quyết Va chạm | Số phép Thăm dò Kỳ vọng (Tìm kiếm THÀNH CÔNG) | Số phép Thăm dò Kỳ vọng (Tìm kiếm KHÔNG THÀNH CÔNG) | Giới hạn $\alpha$ |
| :--- | :---: | :---: | :---: |
| **Separate Chaining (Nối kết)** | $1 + \frac{\alpha}{2}$ | $\alpha$ | Không giới hạn ($\alpha > 1$) |
| **Linear Probing (Thăm dò tuyến tính)** | $\frac{1}{2}\left(1 + \frac{1}{1 - \alpha}\right)$ | $\frac{1}{2}\left(1 + \frac{1}{(1 - \alpha)^2}\right)$ | Bắt buộc $\alpha < 1$ (khuyên dùng $\alpha \le 0.7$) |
| **Double Hashing (Băm kép)** | $\frac{1}{\alpha} \ln\left(\frac{1}{1 - \alpha}\right)$ | $\frac{1}{1 - \alpha}$ | Bắt buộc $\alpha < 1$ (khuyên dùng $\alpha \le 0.7$) |

---

## CHƯƠNG 6: CÁC THUẬT TOÁN SẮP XẾP TOÀN DIỆN (SORTING ALGORITHMS)

---

### 6.1. Phân loại & Cận dưới Lý thuyết Sắp xếp So sánh

#### 1. Các Tiêu chí Phân loại Thuật toán Sắp xếp:
* **Tính Ổn định (Stability):** Giữ nguyên thứ tự xuất hiện ban đầu của các phần tử có cùng giá trị khóa ($k_i == k_j$). Nếu ban đầu $A[i]$ đứng trước $A[j]$ thì sau khi sắp xếp, $A[i]$ vẫn đứng trước $A[j]$.
* **Tại chỗ (In-Place):** Chỉ sử dụng một lượng bộ nhớ phụ hằng số $O(1)$ (hoặc $O(\log n)$ không gian Stack do đệ quy), không tạo bản sao mảng dữ liệu.
* **Dựa trên So sánh (Comparison-Based) vs Không dựa trên So sánh (Non-Comparison):** Thuật toán chỉ sử dụng phép so sánh $\le, <, >$ giữa các cặp phần tử để quyết định trật tự.

#### 2. Định lý Cận dưới của Sắp xếp So sánh:
> [!IMPORTANT]
> **ĐỊNH LÝ HÌNH THỨC:** Mọi thuật toán sắp xếp dựa trên so sánh đều cần ít nhất $\Omega(n \log_2 n)$ phép so sánh trong trường hợp xấu nhất để sắp xếp một dãy gồm $n$ phần tử.
> 
> *Chứng minh:*
> Trong mô hình Cây quyết định (Decision Tree), mỗi nút lá biểu diễn một hoán vị duy nhất của dãy $n$ phần tử. Có tất cả $n!$ hoán vị có thể $\implies$ Cây nhị phân phải có ít nhất $L \ge n!$ nút lá.
> Chiều cao $h$ của cây nhị phân có $L$ lá thỏa mãn $2^h \ge L \ge n! \iff h \ge \log_2(n!)$.
> Theo công thức xấp xỉ Stirling: $n! \ge (n/e)^n$, suy ra:
> $$h \ge \log_2\left(\left(\frac{n}{e}\right)^n\right) = n \log_2 n - n \log_2 e = \Omega(n \log_2 n)$$
> Chiều cao $h$ chính là số phép so sánh nhiều nhất trên đường đi từ gốc đến lá $\implies$ Cận dưới là $\Omega(n \log n)$.

---

### 6.2. Nhóm Sắp xếp Chèn (Insertion Sort)

#### 1. Straight Insertion Sort (Sắp xếp Chèn Thẳng):
* **Nguyên lý:** Chia dãy thành 2 phần: đã sắp xếp bên trái ($A[0 \dots i-1]$) và chưa sắp xếp bên phải ($A[i \dots n-1]$). Lấy phần tử đầu tiên của phần chưa sắp $A[i]$, tìm vị trí thích hợp và chèn vào dãy đã sắp bằng cách dời các phần tử lớn hơn nó sang phải 1 bước.
* **Cài đặt C++:**
  ```cpp
  template <class T>
  void insertionSort(T a[], int n) {
      for (int i = 1; i < n; i++) {
          T key = a[i];
          int j = i - 1;
          while (j >= 0 && a[j] > key) {
              a[j + 1] = a[j]; // Dời sang phải
              j--;
          }
          a[j + 1] = key;
      }
  }
  ```
* **Phân tích:**
  - Tốt nhất: Mảng đã có thứ tự tăng dần $\implies$ Vòng `while` dừng ngay lần so sánh đầu tiên $\implies \Theta(n)$ so sánh, $0$ phép dời.
  - Xấu nhất: Mảng có thứ tự giảm dần $\implies \sum_{i=1}^{n-1} i = \frac{n(n-1)}{2} = \Theta(n^2)$ so sánh và dời.
  - Trung bình: $\Theta(n^2)$.
  - Tính ổn định: **Ổn định (Stable)**. Tại chỗ: **Có (In-place)**.

#### 2. Shell Sort (Sắp xếp Gia giảm Khoảng cách):
* Do Donald Shell phát minh (1959).
* **Ý tưởng:** Khắc phục nhược điểm của Insertion Sort (mỗi lần dời chỉ đi được 1 bước). Chia mảng thành các dãy con gồm các phần tử cách nhau khoảng cách $h$ ($h$-sorted). Ban đầu chọn $h$ lớn để đưa các phần tử về gần vị trí cuối cùng thật nhanh, sau đó giảm dần bước nhảy $h$ về 1.
* **Các Dãy Bước nhảy (Gap Sequences):**
  - Dãy Shell gốc: $h_1 = \lfloor n/2 \rfloor, h_{k+1} = \lfloor h_k / 2 \rfloor \implies$ Xấu nhất $\Theta(n^2)$.
  - Dãy Knuth: $h_1 = 1, h_{k+1} = 3h_k + 1$ ($1, 4, 13, 40, 121, \dots$) $\implies O(n^{3/2})$.
  - Dãy Hibbard: $2^k - 1$ ($1, 3, 7, 15, \dots$) $\implies O(n^{3/2})$.
  - Dãy Sedgewick: $O(n^{4/3})$.
* **Tính ổn định:** **KHÔNG ỔN ĐỊNH** (các bước nhảy khoảng cách $h$ có thể tráo đổi trật tự của hai phần tử bằng nhau).

---

### 6.3. Nhóm Sắp xếp Chọn (Selection Sort)

#### Straight Selection Sort (Sắp xếp Chọn Thẳng):
* **Nguyên lý:** Tại lượt lặp thứ $i$ ($0 \le i \le n-2$), tìm phần tử nhỏ nhất trong mảng con chưa sắp $A[i \dots n-1]$ rồi tráo đổi (`swap`) với $A[i]$.
* **Cài đặt C++:**
  ```cpp
  template <class T>
  void selectionSort(T a[], int n) {
      for (int i = 0; i < n - 1; i++) {
          int minIdx = i;
          for (int j = i + 1; j < n; j++) {
              if (a[j] < a[minIdx]) minIdx = j;
          }
          if (minIdx != i) std::swap(a[i], a[minIdx]);
      }
  }
  ```
* **Đặc tính Bất biến Cốt tử:**
  Số phép so sánh LUÔN BẰNG NHAU trong MỌI TRƯỜNG HỢP (kể cả mảng đã sắp xếp hoàn hảo):
  $$\sum_{i=0}^{n-2} (n - 1 - i) = \frac{n(n-1)}{2} = \Theta(n^2)$$
* **Ưu điểm độc nhất:** Số phép tráo đổi (`swap`) tối đa chỉ là $n - 1 \implies \Theta(n)$ phép ghi bộ nhớ! Cực kỳ lý tưởng khi chi phí ghi lên thiết bị lưu trữ (như Flash EEPROM) đắt hơn nhiều so với đọc.
* **Tính ổn định:** **KHÔNG ỔN ĐỊNH** (ví dụ dãy $[5_a, 5_b, 2] \to [2, 5_b, 5_a]$).

---

### 6.4. Nhóm Sắp xếp Đổi chỗ (Exchange Sort)

#### 1. Bubble Sort (Sắp xếp Nổi bọt):
* Quét mảng từ trái sang phải, so sánh từng cặp phần tử liền kề $A[j]$ và $A[j+1]$, nếu nghịch thế ($A[j] > A[j+1]$) thì đổi chỗ. Sau mỗi lượt, phần tử lớn nhất sẽ "nổi" về đúng vị trí cuối cùng.
* **Tối ưu hóa Cờ hiệu `hasSwapped`:**
  ```cpp
  template <class T>
  void bubbleSort(T a[], int n) {
      for (int i = 0; i < n - 1; i++) {
          bool hasSwapped = false;
          for (int j = 0; j < n - 1 - i; j++) {
              if (a[j] > a[j + 1]) {
                  std::swap(a[j], a[j + 1]);
                  hasSwapped = true;
              }
          }
          if (!hasSwapped) break; // Đã có thứ tự, dừng sớm
      }
  }
  ```
* **Phân tích:** Tốt nhất: $\Theta(n)$ so sánh (nhờ cờ hiệu); Xấu nhất / Trung bình: $\Theta(n^2)$. Tính ổn định: **Ổn định (Stable)**.

#### 2. Cocktail Shaker Sort (Bidirectional Bubble Sort):
* Đổi hướng quét sau mỗi lượt: lượt đi quét từ trái sang phải đẩy số lớn về cuối; lượt về quét từ phải sang trái đẩy số nhỏ về đầu.
* Khắc phục hiệu ứng "rùa" (turtles - các số nhỏ nằm ở cuối mảng di chuyển cực chậm trong Bubble sort).

---

### 6.5. Nhóm Chia để Trị I: Merge Sort (Sắp xếp Trộn)

#### 1. Nguyên lý Hoạt động:
Chia mảng thành 2 nửa bằng nhau, đệ quy sắp xếp từng nửa, sau đó trộn (Merge) hai nửa đã sắp thành mảng hoàn chỉnh bằng mảng tạm `temp`.

```
                             SƠ ĐỒ CHIA ĐỂ TRỊ CỦA MERGE SORT
                                [ 38, 27, 43, 3, 9, 82, 10 ]
                                      /              \
                           [ 38, 27, 43, 3 ]     [ 9, 82, 10 ]
                              /        \             /       \
                          [38, 27]   [43, 3]       [9, 82]   [10]
                           /   \      /   \         /   \      |
                         [38] [27]  [43]  [3]     [9]   [82]  [10]
                           \   /      \   /         \   /      |
                          [27, 38]   [3, 43]       [9, 82]   [10]
                              \        /             \       /
                           [ 3, 27, 38, 43 ]     [ 9, 10, 82 ]
                                      \              /
                                [ 3, 9, 10, 27, 38, 43, 82 ]
```

#### 2. Cài đặt C++ Thuật toán Trộn (`merge`):
```cpp
template <class T>
void merge(T a[], int left, int mid, int right) {
    int n1 = mid - left + 1;
    int n2 = right - mid;
    T* L = new T[n1];
    T* R = new T[n2];
    for (int i = 0; i < n1; i++) L[i] = a[left + i];
    for (int j = 0; j < n2; j++) R[j] = a[mid + 1 + j];

    int i = 0, j = 0, k = left;
    while (i < n1 && j < n2) {
        if (L[i] <= R[j]) a[k++] = L[i++]; // Dấu <= bảo đảm tính ổn định
        else a[k++] = R[j++];
    }
    while (i < n1) a[k++] = L[i++];
    while (j < n2) a[k++] = R[j++];
    delete[] L;
    delete[] R;
}
```

#### 3. Phân tích Độ phức tạp:
* Hệ thức truy hồi: $T(n) = 2T(n/2) + \Theta(n) \implies \Theta(n \log_2 n)$ trong **TẤT CẢ CÁC TRƯỜNG HỢP (Tốt nhất, Xấu nhất, Trung bình)**.
* Bộ nhớ phụ: $\Theta(n)$ để chứa mảng tạm.
* Tính ổn định: **Ổn định (Stable)**.
* **Ứng dụng Tối thượng:** Merge Sort là thuật toán sắp xếp tốt nhất cho **Danh sách Liên kết (Linked Lists)** vì có thể trộn trực tiếp bằng các con trỏ mà không tốn thêm bất kỳ ô nhớ phụ nào ($O(1)$ auxiliary space)!

---

### 6.6. Nhóm Chia để Trị II: Quick Sort Chuyên sâu

Do C.A.R. Hoare phát minh (1961). Thuật toán sắp xếp trong thực tế nhanh nhất và phổ biến nhất.

#### 1. Chiến lược Chọn Pivot (Phần tử Chốt):
* **Chốt đầu (`a[left]`) / Chốt cuối (`a[right]`):** Dễ bị thoái hóa thành $O(n^2)$ trên mảng đã sắp xếp hoặc nghịch đảo.
* **Chốt ngẫu nhiên (`a[random]`):** Triệt tiêu hoàn toàn khả năng bị tấn công dữ liệu xấu có chủ đích.
* **Trung vị của Ba (Median-of-Three):** Lấy trung vị của 3 phần tử $\{a[left], a[mid], a[right]\}$ làm pivot. Vừa cân bằng tốt phân hoạch, vừa triệt tiêu suy biến trên mảng đã sắp.

#### 2. Kỹ thuật Phân hoạch Kruse & Ryba (Giáo trình Chuẩn):
Sử dụng hai con trỏ `too_big_index` và `too_small_index` quét từ hai đầu mảng:

```
                  PHÂN HOẠCH KRUSE-RYBA TRONG QUICKSORT
          Pivot = 40
          [ 40 | 20 | 10 | 80 | 60 | 50 | 7 | 30 | 100 ]
                 ^                                   ^
                 too_big_index                       too_small_index
                 (chạy sang phải                     (chạy sang trái
                  tìm phần tử > 40)                   tìm phần tử <= 40)
```

* **Quy tắc di chuyển:**
  1. `too_big_index` tiến sang phải chừng nào `data[too_big_index] <= data[pivot]`.
  2. `too_small_index` lùi sang trái chừng nào `data[too_small_index] > data[pivot]`.
  3. Nếu `too_big_index < too_small_index`: Tráo đổi `data[too_big_index]` và `data[too_small_index]`. Quay lại bước 1.
  4. Khi hai con trỏ vượt nhau (`too_small_index <= too_big_index`): Tráo đổi `data[pivot]` với `data[too_small_index]`. Hoàn tất phân hoạch!

#### 3. Phân tích Hiệu năng:
* **Trường hợp Tốt nhất:** Pivot luôn chia đôi mảng $\implies T(n) = 2T(n/2) + \Theta(n) \implies \Theta(n \log_2 n)$.
* **Trường hợp Trung bình:** Giả định các khóa phân phối ngẫu nhiên: $\Theta(n \log_2 n)$ (kỳ vọng $\approx 1.386 n \log_2 n$ phép so sánh, nhanh hơn Heapsort khoảng 2-3 lần do tối ưu bộ nhớ cache).
* **Trường hợp Xấu nhất:** Pivot luôn rơi vào phần tử cực đại hoặc cực tiểu $\implies T(n) = T(n-1) + \Theta(n) \implies \Theta(n^2)$.
* **Độ sâu Call Stack & Tối ưu Khử Đệ quy Đuôi (Tail-Call Optimization):**
  Nếu cài đặt ngây thơ, Call Stack có thể sâu $O(n)$ gây tràn ngăn xếp. Kỹ thuật chuẩn: **Luôn gọi đệ quy cho nửa nhỏ hơn trước, nửa lớn hơn dùng vòng lặp `while`** $\implies$ Bảo đảm độ sâu Stack tối đa chỉ là $O(\log_2 n)$!
* **Tính ổn định:** **KHÔNG ỔN ĐỊNH**.

#### 4. Introsort (Tiêu chuẩn Thư viện `std::sort` trong C++ STL):
Thuật toán lai ghép thông minh phát minh bởi David Musser:
1. Bắt đầu chạy bằng **Quick Sort**.
2. Theo dõi độ sâu đệ quy: Nếu độ sâu vượt quá $2 \lfloor \log_2 n \rfloor$ (dấu hiệu suy biến sang $O(n^2)$), lập tức chuyển sang chạy **Heap Sort** để ép thời gian xấu nhất về chắc chắn $O(n \log n)$.
3. Khi kích thước mảng con nhỏ ($n \le 16$), chuyển sang **Insertion Sort** vì Insertion Sort chạy cực nhanh trên mảng nhỏ.

---

### 6.7. Bảng So sánh Hiệu năng & Đặc tính Toàn diện 8 Giải thuật Sắp xếp

| Thuật toán | Thời gian TỐT NHẤT | Thời gian TRUNG BÌNH | Thời gian XẤU NHẤT | Bộ nhớ Phụ | Ổn định (Stable)? | Phù hợp nhất khi nào? |
| :--- | :---: | :---: | :---: | :---: | :---: | :--- |
| **Straight Insertion Sort** | **$\Theta(n)$** | $\Theta(n^2)$ | $\Theta(n^2)$ | $\Theta(1)$ | **CÓ** | Mảng kích thước nhỏ ($n \le 16$) hoặc mảng gần như đã sắp xếp. |
| **Binary Insertion Sort** | $\Theta(n)$ | $\Theta(n^2)$ | $\Theta(n^2)$ | $\Theta(1)$ | **CÓ** | Giảm số phép so sánh, phù hợp khi so sánh tốn kém. |
| **Shell Sort** | $\Theta(n \log n)$ | $\Theta(n^{4/3})$ | $\Theta(n^2)$ hoặc $O(n^{3/2})$ | $\Theta(1)$ | **KHÔNG** | Mảng kích thước trung bình, mã nguồn ngắn gọn không cần đệ quy. |
| **Straight Selection Sort** | $\Theta(n^2)$ | $\Theta(n^2)$ | $\Theta(n^2)$ | $\Theta(1)$ | **KHÔNG** | Khi chi phí ghi dữ liệu (write) đắt gấp nhiều lần so sánh. |
| **Bubble Sort** | $\Theta(n)$ | $\Theta(n^2)$ | $\Theta(n^2)$ | $\Theta(1)$ | **CÓ** | Mục đích giáo khoa, kiểm tra mảng đã có thứ tự hay chưa. |
| **Merge Sort** | **$\Theta(n \log n)$** | **$\Theta(n \log n)$** | **$\Theta(n \log n)$** | $\Theta(n)$ | **CÓ** | Sắp xếp Danh sách Liên kết, bảo đảm chắc chắn $O(n \log n)$ và ổn định. |
| **Quick Sort** | $\Theta(n \log n)$ | **$\Theta(n \log n)$** | $\Theta(n^2)$ | $O(\log n)$ | **KHÔNG** | Sắp xếp dữ liệu đa mục đích trên bộ nhớ RAM lớn (hiệu năng thực tế đỉnh nhất). |
| **Heap Sort** | $\Theta(n \log n)$ | **$\Theta(n \log n)$** | **$\Theta(n \log n)$** | **$\Theta(1)$** | **KHÔNG** | Khi cần bảo đảm chắc chắn $O(n \log n)$ mà bộ nhớ phụ bị giới hạn ngặt nghèo $O(1)$. |

# PHẦN IV: CẤU TRÚC CÂY, CÂY TÌM KIẾM CÂN BẰNG & CẤU TRÚC ĐỐNG

---

## CHƯƠNG 7: CÂY NHỊ PHÂN & CÂY TÌM KIẾM NHỊ PHÂN (BINARY TREES & BST)

Cây là cấu trúc dữ liệu phi tuyến tính (Non-linear Data Structure) mô tả mối quan hệ phân cấp hình cây giữa các đối tượng.

---

### 7.1. Định nghĩa & Phân loại Cây Nhị phân

#### 1. Các Thuật ngữ Định lượng Cốt lõi:
* **Gốc (Root):** Nút duy nhất trên cây không có nút cha.
* **Nút lá (Leaf / External Node):** Nút không có bất kỳ con nào (bậc = 0).
* **Nút nội bộ (Internal Node):** Nút có ít nhất một con.
* **Bậc của nút (Degree of Node):** Số lượng con trực tiếp của nút đó.
* **Độ sâu của nút $u$ (Depth of $u$):** Số lượng cạnh trên đường đi duy nhất từ gốc tới $u$. Độ sâu của gốc bằng $0$.
* **Chiều cao của nút $u$ (Height of $u$):** Số lượng cạnh trên đường đi dài nhất từ $u$ xuống một nút lá. Chiều cao của nút lá bằng $0$.
* **Chiều cao của cây (Height of Tree):** Chính là chiều cao của nút gốc.

#### 2. Phân loại Cây Nhị phân Đặc biệt:

```
                    CÁC DẠNG CÂY NHỊ PHÂN ĐẶC BIỆT
       Full Binary Tree             Complete Binary Tree          Perfect Binary Tree
             (A)                            (A)                           (A)
            /   \                          /   \                         /   \
          (B)   (C)                      (B)   (C)                     (B)   (C)
         /   \                          /   \  /                      /  \   /  \
       (D)   (E)                      (D)  (E)(F)                   (D)  (E)(F) (G)
   Moi nut co 0 hoac 2 con        Dien day du tu trai qua phai    Moi tang deu kin nut
```

1. **Cây Nhị phân Đầy đủ (Full / Strictly Binary Tree):** Mọi nút đều có đúng 0 hoặc 2 con (hoàn toàn không có nút nào có đúng 1 con).
2. **Cây Nhị phân Hoàn chỉnh (Complete Binary Tree):** Mọi tầng đều chứa đầy đủ nút ngoại trừ tầng cuối cùng; tại tầng cuối cùng, các nút được lấp đầy liên tục từ trái sang phải không để lại khoảng trống.
3. **Cây Nhị phân Hoàn hảo (Perfect Binary Tree):** Tất cả các nút nội bộ đều có 2 con và toàn bộ các nút lá đều nằm ở cùng một tầng.
4. **Cây Nhị phân Cân bằng (Balanced Binary Tree):** Chiều cao của hai cây con trái và phải tại bất kỳ nút nào chênh lệch nhau không quá 1.
5. **Cây Suy biến (Degenerate / Skewed Tree):** Mỗi nút nội bộ chỉ có đúng 1 con (cây bị thoái hóa thành một danh sách liên kết).

---

### 7.2. Các Định lý Toán học & Tính chất Cốt lõi

1. **Số cạnh của cây:** Cây gồm $n$ nút thì có chính xác $n - 1$ cạnh.
2. **Số nút tối đa tại tầng $d$ (gốc ở tầng 0):**
   $$\text{MaxNodes}(d) = 2^d$$
3. **Số nút tối đa của cây nhị phân chiều cao $h$:**
   $$\text{MaxNodes}(h) = \sum_{d=0}^h 2^d = 2^{h+1} - 1$$
4. **Chiều cao nhỏ nhất của cây nhị phân gồm $n$ nút:**
   $$h_{min} = \lceil \log_2(n + 1) \rceil - 1 = \lfloor \log_2 n \rfloor$$
5. **Định lý Nút lá trong Cây Đầy đủ (Full Binary Tree Theorem):**
   Trong một cây nhị phân đầy đủ bất kỳ, số nút lá $L$ luôn nhiều hơn số nút nội bộ $I$ đúng 1 nút:
   $$L = I + 1$$
   *(Chứng minh: Gọi $n$ là tổng số nút $\implies n = L + I$. Mặt khác, mỗi nút nội bộ sinh đúng 2 nhánh, gốc có bậc vào bằng 0 nên tổng số cạnh là $2I = n - 1 \implies 2I = L + I - 1 \implies L = I + 1$)*.

---

### 7.3. Các Phép Duyệt Cây & Cây Biểu thức

#### 1. Các Phép Duyệt theo Chiều sâu (DFS Traversals):
* **Tiền thứ tự (Pre-order - NLR):** Thăm `Node` $\to$ Duyệt cây con `Left` $\to$ Duyệt cây con `Right`. Dùng để nhân bản cây, tạo chuỗi tuần tự hóa (Serialization).
* **Trung thứ tự (In-order - LNR):** Duyệt `Left` $\to$ Thăm `Node` $\to$ Duyệt `Right`.
  > [!TIP]
  > Trên Cây Tìm kiếm Nhị phân (BST), phép duyệt Trung thứ tự (In-order) **luôn luôn cho ra dãy các phần tử tăng dần**!
* **Hậu thứ tự (Post-order - LRN):** Duyệt `Left` $\to$ Duyệt `Right` $\to$ Thăm `Node`. Dùng để xóa/thu hồi cây từ dưới lên trên, tính dung lượng thư mục.

#### 2. Phép Duyệt theo Chiều rộng (BFS / Level-Order Traversal):
Sử dụng một Hàng đợi (Queue) để duyệt từng tầng từ trên xuống dưới, từ trái sang phải:
```cpp
template <class T>
void levelOrder(Node<T>* root) {
    if (!root) return;
    std::queue<Node<T>*> q;
    q.push(root);
    while (!q.empty()) {
        Node<T>* curr = q.front(); q.pop();
        std::cout << curr->data << " ";
        if (curr->left) q.push(curr->left);
        if (curr->right) q.push(curr->right);
    }
}
```

#### 3. Cây Biểu thức (Expression Tree):
Là cây nhị phân trong đó các nút lá là toán hạng (biến, số) và các nút nội bộ là toán tử hai ngôi (`+`, `-`, `*`, `/`).
* Duyệt In-order (có ngoặc) $\implies$ Biểu thức Trung tố (Infix).
* Duyệt Pre-order $\implies$ Biểu thức Tiền tố (Prefix).
* Duyệt Post-order $\implies$ Biểu thức Hậu tố (Postfix). Lượng giá biểu thức bằng đệ quy Post-order.

---

### 7.4. Cây Tìm kiếm Nhị phân (Binary Search Tree - BST)

#### 1. Định nghĩa Tính chất BST:
Với mọi nút $x$ trong cây:
* Mọi khóa $k$ thuộc cây con bên trái đều thỏa mãn: $k < x.key$.
* Mọi khóa $k$ thuộc cây con bên phải đều thỏa mãn: $k > x.key$.

#### 2. Thao tác Tìm kiếm & Chèn:
Cả hai thao tác đều có độ phức tạp phụ thuộc vào chiều cao cây: $\Theta(h)$.
```cpp
template <class T>
Node<T>* insertBST(Node<T>* root, T val) {
    if (root == nullptr) return new Node<T>(val);
    if (val < root->data) root->left = insertBST(root->left, val);
    else if (val > root->data) root->right = insertBST(root->right, val);
    return root;
}
```

#### 3. Thao tác Xóa trên BST (Ba Trường hợp Kinh điển):
Khi xóa nút $z$ trên BST, ta đối mặt với 3 trường hợp:
* **Trường hợp 1: $z$ là Nút Lá:** Đơn giản giải phóng bộ nhớ của $z$ và cập nhật con trỏ của nút cha trỏ về `nullptr`.
* **Trường hợp 2: $z$ có Đúng 1 Con:** Nối trực tiếp nút cha của $z$ tới nút con duy nhất của $z$, sau đó thu hồi $z$.
* **Trường hợp 3: $z$ có Đủ 2 Con:**
  - Tìm phần tử thế mạng: là **Inorder Successor** (phần tử nhỏ nhất bên cây con phải) hoặc **Inorder Predecessor** (phần tử lớn nhất bên cây con trái).
  - Sao chép giá trị của phần tử thế mạng vào $z$.
  - Xóa đệ quy nút thế mạng (nút này đảm bảo chỉ có tối đa 1 con $\implies$ rơi vào Trường hợp 1 hoặc 2!).

```cpp
template <class T>
Node<T>* deleteBST(Node<T>* root, T val) {
    if (!root) return root;
    if (val < root->data) root->left = deleteBST(root->left, val);
    else if (val > root->data) root->right = deleteBST(root->right, val);
    else {
        // Trường hợp 1 & 2: Có 0 hoặc 1 con
        if (!root->left) {
            Node<T>* temp = root->right;
            delete root;
            return temp;
        } else if (!root->right) {
            Node<T>* temp = root->left;
            delete root;
            return temp;
        }
        // Trường hợp 3: Có đủ 2 con -> Tìm Inorder Successor (min bên phải)
        Node<T>* succ = root->right;
        while (succ->left) succ = succ->left;
        root->data = succ->data;
        root->right = deleteBST(root->right, succ->data);
    }
    return root;
}
```

---

## CHƯƠNG 8: CÂY CÂN BẰNG AVL (AVL TREES)

---

### 8.1. Khái niệm & Hệ số Cân bằng (Balance Factor)

Cây AVL (phát minh năm 1962 bởi G.M. Adelson-Velsky và E.M. Landis) là cây tìm kiếm nhị phân tự cân bằng đầu tiên.

* **Định nghĩa Hệ số Cân bằng (Balance Factor - $BF$):**
  $$BF(u) = h(u.left) - h(u.right)$$
  *(Quy ước theo giáo trình TS. Lê Thanh Sách: chiều cao con trái trừ chiều cao con phải)*.
* **Điều kiện Cân bằng AVL:** Một cây BST là cây AVL khi và chỉ khi mọi nút $u$ đều thỏa mãn:
  $$BF(u) \in \{-1, 0, +1\}$$
  - $BF = +1$: Lệch Trái (Left-High - `LH`).
  - $BF = 0$: Cân bằng Hoàn hảo (Even-High - `EH`).
  - $BF = -1$: Lệch Phải (Right-High - `RH`).
  - Khi $|BF| \ge 2$: Cây bị mất cân bằng, bắt buộc phải thực hiện phép quay để tái cấu trúc.

---

### 8.2. Cận Chiều cao & Dãy Fibonacci Tối thiểu

* Gọi $N(h)$ là số nút ít nhất của một cây AVL có chiều cao $h$:
  $$N(h) = N(h-1) + N(h-2) + 1 \quad (h \ge 2)$$
  Với các giá trị cơ sở: $N(0) = 1, N(1) = 2, N(2) = 4, N(3) = 7, N(4) = 12, \dots$
* Hệ thức truy hồi này đồng dạng với Dãy số Fibonacci ($N(h) = F_{h+3} - 1$).
* **Định lý Cận Chiều cao Tối đa:** Chiều cao của cây AVL gồm $n$ nút bị chặn trên bởi:
  $$h < 1.44 \log_2(n + 2) - 0.328 \implies h = \Theta(\log_2 n)$$
* **Hệ quả:** Thao tác tìm kiếm trên cây AVL trong trường hợp xấu nhất không bao giờ vượt quá $1.44 \log_2 n$ phép so sánh (nhanh hơn Red-Black Tree vốn có cận là $2 \log_2 n$).

---

### 8.3. Bốn Phép Quay Cân bằng Cốt lõi (AVL Rotations)

Khi thao tác thêm hoặc xóa làm xuất hiện nút có $|BF| = 2$, ta truy vết từ vị trí thao tác ngược lên gốc để tìm **Nút mất cân bằng thấp nhất** (Lowest Unbalanced Node) và thực hiện một trong bốn phép quay:

```
                      BỐN TRƯỜNG HỢP QUAY CÂN BẰNG AVL
  1. Left-Left (LL)  --> Quay Phải (Rotate Right)
  2. Right-Right (RR)--> Quay Trái (Rotate Left)
  3. Left-Right (LR) --> Quay Trái tại Con Trái, roi Quay Phải tai Goc
  4. Right-Left (RL) --> Quay Phai tai Con Phai, roi Quay Trai tai Goc
```

#### 1. Quay Đơn Phải (Rotate Right - Khắc phục lệch Trái-Trái LL):
Xảy ra khi cây con trái cao hơn ($BF = +2$) và nút mới được chèn vào nhánh trái của con trái.
```cpp
template <class T>
Node<T>* rotateRight(Node<T>* root) {
    Node<T>* temp = root->left;
    root->left = temp->right;
    temp->right = root;
    return temp; // temp tro thanh goc moi
}
```

#### 2. Quay Đơn Trái (Rotate Left - Khắc phục lệch Phải-Phải RR):
Xảy ra khi cây con phải cao hơn ($BF = -2$) và nút mới được chèn vào nhánh phải của con phải.
```cpp
template <class T>
Node<T>* rotateLeft(Node<T>* root) {
    Node<T>* temp = root->right;
    root->right = temp->left;
    temp->left = root;
    return temp; // temp tro thanh goc moi
}
```

#### 3. Quay Kép Trái-Phải (LR Rotation - Khắc phục lệch Trái-Phải):
Xảy ra khi $BF(root) = +2$ nhưng con trái có $BF(root.left) = -1$.
- Bước 1: `root->left = rotateLeft(root->left);` (chuyển về dạng lệch LL).
- Bước 2: `root = rotateRight(root);`.

#### 4. Quay Kép Phải-Trái (RL Rotation - Khắc phục lệch Phải-Trái):
Xảy ra khi $BF(root) = -2$ nhưng con phải có $BF(root.right) = +1$.
- Bước 1: `root->right = rotateRight(root->right);` (chuyển về dạng lệch RR).
- Bước 2: `root = rotateLeft(root);`.

---

### 8.4. Thuật toán Thêm phần tử AVL & So sánh với Thao tác Xóa

* **Thuật toán Thêm (Insert) & Cờ hiệu `taller`:**
  - Thêm phần tử theo quy tắc BST, sau đó quay lui cập nhật $BF$ và biến boolean `taller`.
  - **Định lý Chèn AVL:** Trong thao tác chèn, **TỐI ĐA CHỈ CẦN DUY NHẤT 1 PHÉP QUAY** (đơn hoặc kép) là khôi phục hoàn toàn tính cân bằng cho toàn bộ cây AVL! Chiều cao cây sau phép quay trở lại đúng bằng chiều cao cây trước khi chèn $\implies$ dừng đệ quy ngay lập tức.
* **Thuật toán Xóa (Delete) & Cờ hiệu `shorter`:**
  - Xóa phần tử theo quy tắc BST, sau đó quay lui kiểm tra mất cân bằng khi cây con bị lùn đi.
  - **Định lý Xóa AVL:** Khác với thao tác chèn, việc quay cân bằng sau khi xóa có thể làm chiều cao cây con tiếp tục giảm, khiến sự mất cân bằng lan truyền dọc theo đường đi lên tận nút gốc $\implies$ Thao tác xóa có thể đòi hỏi **lên tới $O(\log n)$ phép quay**!

---

## CHƯƠNG 9: CÂY TỰ ĐIỀU CHỈNH SPLAY & CÂY TÌM KIẾM ĐA PHÂN B-TREE

---

### 9.1. Cây Tự điều chỉnh Splay (Splay Trees)

Do Daniel Sleator và Robert Tarjan phát minh năm 1985 (công trình đoạt Giải thưởng ACM Kanellakis).

* **Triết lý Thiết kế Đột phá:**
  - Hoàn toàn KHÔNG lưu trữ hệ số cân bằng hay chiều cao trên mỗi nút (tiết kiệm bộ nhớ).
  - Không bảo đảm cây luôn cân bằng nghiêm ngặt tại mọi thời điểm.
  - **Chiến lược Tự điều chỉnh (Self-Adjusting):** Mỗi khi một nút $x$ được truy cập (qua `search`, `insert`, hay `delete`), nút $x$ sẽ được đưa lên làm **Nút Gốc (Root)** thông qua một chuỗi các phép quay cục bộ gọi là **Thao tác Splay (Splaying)**.
* **Tính chất Cục bộ Thời gian (Temporal Locality):**
  Trong các ứng dụng thực tế (như bảng định tuyến mạng, bộ nhớ đệm trang), các phần tử vừa truy cập thường có xu hướng được truy cập lại liên tục trong tương lai gần. Đưa chúng lên gốc giúp các lần truy cập tiếp theo đạt thời gian $\Theta(1)$!

---

### 9.2. Ba Thao tác Splay Cốt lõi

Cho $x$ là nút cần đẩy lên gốc, $p$ là cha của $x$, và $g$ là ông nội (cha của $p$):

```
                        BA THAO TÁC SPLAYING CỦA SLEATOR-TARJAN
       1. Zig (Nut p la goc)       2. Zig-Zig (Cung huong)       3. Zig-Zag (Khac huong)
               (p)                           (g)                           (g)
              /                             /                             /
            (x)                           (p)                           (p)
                                         /                                \
                                       (x)                                (x)
         Quay don giua x va p       QUAY p QUANH g TRUOC!          Quay x quanh p truoc,
                                    Sau do quay x quanh p          sau do quay x quanh g
```

1. **Trường hợp 1: Zig (hoặc Zag):**
   - $p$ chính là nút gốc của toàn cây.
   - Thực hiện đúng **1 phép quay đơn** giữa $x$ và $p$.
2. **Trường hợp 2: Zig-Zig (Cùng hướng con: Trái-Trái hoặc Phải-Phải):**
   - $x$ là con trái của $p$, và $p$ là con trái của $g$ (hoặc cả hai cùng là con phải).
   > [!CRITICAL]
   > **ĐIỂM CỐT TỬ CỦA THUẬT TOÁN SLEATOR-TARJAN:**
   > Ta bắt buộc phải **quay cha $p$ quanh ông nội $g$ TRƯỚC, sau đó mới quay $x$ quanh cha $p$**!
   > Tuyệt đối không được quay con $x$ trước. Việc quay cha trước giúp làm giảm một nửa độ sâu của tất cả các nút nằm trên đường đi, triệt tiêu hoàn toàn các nhánh cây bị suy biến dài ngoằng!
3. **Trường hợp 3: Zig-Zag (Khác hướng con: Trái-Phải hoặc Phải-Trái):**
   - $x$ là con phải của $p$, và $p$ là con trái của $g$ (hoặc ngược lại).
   - Thực hiện quay $x$ quanh $p$ trước, sau đó quay $x$ quanh $g$ (giống hệt phép quay kép LR/RL của cây AVL).

#### Phân tích Hiệu năng Amortized của Splay Tree:
Dựa trên Phương pháp Hàm Thế năng (Potential Function Method) với $\Phi = \sum_{u} \log_2(\text{size}(u))$:
* Dù một thao tác đơn lẻ trong trường hợp xấu nhất có thể tốn $O(n)$, nhưng **chi phí phân bổ khấu hao (Amortized Cost) của chuỗi bất kỳ gồm $m$ thao tác trên cây Splay $n$ nút luôn bị chặn bởi $O(m \log_2 n)$**!
* Tức mỗi thao tác có chi phí phân bổ là **$O(\log_2 n)$**.

---

### 9.3. Cây Tìm kiếm Đa phân & Cây B (B-Trees)

Phát minh bởi Rudolf Bayer và Edward M. McCreight (1970).

#### 1. Động lực Ra đời: Tối ưu hóa Bộ nhớ Ngoài (Disk I/O Bottleneck):
* Khi dữ liệu quá lớn không thể chứa hết trên RAM, toàn bộ cây phải lưu trên ổ cứng (HDD/SSD).
* Một thao tác đọc đĩa (Disk Block Read) tốn thời gian cỡ vài mili-giây (chậm hơn truy xuất RAM khoảng $100.000$ lần!).
* Cây AVL hay BST có bậc 2 nên chiều cao rất lớn ($\log_2 n$), đòi hỏi hàng chục lần đọc đĩa.
* **Giải pháp Cây B:** Tăng số lượng nhánh con tại mỗi nút lên hàng trăm/hàng ngàn (bậc $M \approx 1000$), làm **chiều cao cây co lùn lại tối đa** ($\log_M n$), chỉ mất 2-3 lần đọc đĩa là tìm thấy dữ liệu!

#### 2. Định nghĩa Hình thức Cây B Bậc $M$ (B-Tree of Order $M$):
1. Mỗi nút có tối đa $M$ con (chứa tối đa $M - 1$ khóa).
2. Mọi nút không phải gốc và không phải lá có ít nhất $\lceil M/2 \rceil$ con (chứa ít nhất $\lceil M/2 \rceil - 1$ khóa).
3. Nút gốc nếu không phải lá thì có ít nhất 2 con (chứa ít nhất 1 khóa).
4. **TẤT CẢ CÁC NÚT LÁ PHẢI NẰM Ở CÙNG MỘT TẦNG** (Cân bằng hoàn hảo tuyệt đối).
5. Các khóa trong mỗi nút được sắp xếp tăng dần: $k_1 < k_2 < \dots < k_p$. Con trỏ $P_i$ trỏ tới cây con chứa các giá trị nằm trong khoảng $(k_i, k_{i+1})$.

```
                        CẤU TRÚC MỘT NÚT CỦA CÂY B BẬC M
            +----+----+----+----+----+----+----+----+----+----+
            | P0 | K1 | P1 | K2 | P2 | ...| Ki | Pi | ...| Pm |
            +----+----+----+----+----+----+----+----+----+----+
            /         \         \
           v           v         v
        Keys < K1   K1<..<K2   K2<..<K3
```

#### 3. Thao tác Chèn trên Cây B & Kỹ thuật Tách Nút (Node Splitting):
* Quá trình tìm kiếm luôn dẫn tới việc **chèn khóa mới vào một Nút Lá**.
* Nếu nút lá có $< M - 1$ khóa: Chèn vào đúng vị trí theo thứ tự.
* Nếu nút lá bị quá tải ($M$ khóa):
  1. Xác định **Khóa trung vị (Median Key)** tại chỉ số $\lfloor M/2 \rfloor$.
  2. Tách nút thành 2 nút độc lập: Nút trái chứa các khóa trước trung vị, nút phải chứa các khóa sau trung vị.
  3. Đẩy khóa trung vị lên nút cha.
  4. Quá trình tách nút có thể lan truyền ngược lên các tầng trên. Nếu nút gốc bị tách, một nút gốc mới được tạo ra $\implies$ **Cây B phát triển chiều cao TỪ DƯỚI LÊN TRÊN!**

#### 4. Thao tác Xóa trên Cây B & Kỹ thuật Mượn / Hợp nhất:
* Nếu khóa cần xóa nằm ở nút nội bộ: Hoán đổi với phần tử thế mạng (Inorder Predecessor hoặc Successor ở nút lá), chuyển về bài toán xóa ở nút lá.
* Nếu xóa ở lá khiến số khóa bị tụt xuống dưới ngưỡng tối thiểu $\lceil M/2 \rceil - 1$ (Hiện tượng Thiếu hụt - Underflow):
  - **Mượn khóa (Borrow / Rotation):** Nếu anh em ruột liền kề (trái hoặc phải) có dư thừa khóa, mượn 1 khóa qua trung gian nút cha.
  - **Hợp nhất (Merge / Coalesce):** Nếu cả 2 anh em liền kề đều chỉ có số khóa tối thiểu, hợp nhất nút bị thiếu với một anh em và kéo khóa phân tách từ nút cha xuống. Nếu cha bị thiếu hụt, tiếp tục lan truyền lên trên. Nếu gốc bị rỗng, con duy nhất trở thành gốc mới $\implies$ **Chiều cao cây giảm 1!**

---

### 9.4. Cây B+ (B+ Tree) & Ứng dụng Quản trị Cơ sở Dữ liệu

Là chuẩn mực đánh chỉ mục (Index Engine) trong mọi hệ quản trị CSDL quan hệ hiện đại (MySQL InnoDB, PostgreSQL, SQLite):
1. **Dữ liệu thực tế CHỈ ĐƯỢC LƯU Ở NÚT LÁ.** Các nút nội bộ chỉ lưu các khóa dẫn đường (Router Keys) kèm con trỏ, không chứa bản ghi dữ liệu. Do đó, một nút nội bộ có thể chứa được số lượng khóa khổng lồ (bậc phân nhánh $M$ cực lớn).
2. **Các Nút Lá được Xâu chuỗi thành Danh sách Liên kết Đôi (Doubly Linked List):**
   Cho phép thực hiện **Truy vấn Khoảng (Range Queries)** với tốc độ tối thượng: chỉ cần dùng tìm kiếm cây $O(\log n)$ để định vị lá đầu tiên, sau đó quét tuần tự dọc theo danh sách liên kết các lá để lấy kết quả mà không cần quay lui lên cây!

---

## CHƯƠNG 10: CẤU TRÚC ĐỐNG & HÀNG ĐỢI ƯU TIÊN (HEAPS & PRIORITY QUEUES)

---

### 10.1. Định nghĩa Cấu trúc Đống (Heap Definition)

Đống nhị phân (Binary Heap) là một cấu trúc dữ liệu thỏa mãn đồng thời hai điều kiện:
1. **Tính chất Cấu trúc (Structural Property):** Là một **Cây nhị phân hoàn chỉnh (Complete Binary Tree)**.
2. **Tính chất Thứ tự Heap (Heap-Order Property):**
   - **Max-Heap:** Với mọi nút $i$ khác gốc: $\text{Key}(\text{parent}(i)) \ge \text{Key}(i)$. Phần tử lớn nhất toàn cây luôn cư trú tại Nút Gốc.
   - **Min-Heap:** Với mọi nút $i$ khác gốc: $\text{Key}(\text{parent}(i)) \le \text{Key}(i)$. Phần tử nhỏ nhất toàn cây luôn cư trú tại Nút Gốc.

---

### 10.2. Ánh xạ Mảng Tuyến tính & Hai Giải thuật Nền tảng

Nhờ tính chất cây hoàn chỉnh, Heap được ánh xạ hoàn hảo lên một mảng 1 chiều liên tục mà hoàn toàn không cần lưu con trỏ:
* Với mảng đánh số từ $0$ (Kích thước $n$):
  - Nút cha của $i$: $\text{parent}(i) = \lfloor (i - 1) / 2 \rfloor$.
  - Con trái của $i$: $\text{left}(i) = 2i + 1$.
  - Con phải của $i$: $\text{right}(i) = 2i + 2$.
  - Nút nội bộ cuối cùng: $\lfloor n/2 \rfloor - 1$. Các phần tử từ $\lfloor n/2 \rfloor$ đến $n - 1$ đều là Nút Lá!

```
                    BIỂU DIỄN HEAP TRÊN MẢNG 1 CHIỀU
            Cây nhị phân:                   Mảng lưu trữ:
                [90]                     Chỉ số: 0   1   2   3   4   5
               /    \                   Giá trị: [90, 70, 80, 40, 50, 30]
            [70]    [80]                 
            /  \    /                   parent(i) = (i - 1) / 2
          [40][50][30]                  left(i)   = 2*i + 1
                                        right(i)  = 2*i + 2
```

#### 1. Thuật toán `reheapUp` (Sift-Up / Bubble-Up):
Được gọi khi một phần tử ở đáy vi phạm tính chất Heap với cha của nó:
```cpp
template <class T>
void reheapUp(T a[], int idx) {
    while (idx > 0) {
        int parentIdx = (idx - 1) / 2;
        if (a[idx] > a[parentIdx]) { // Max-Heap
            std::swap(a[idx], a[parentIdx]);
            idx = parentIdx;
        } else break;
    }
}
```
* Số lần tráo đổi tối đa bằng chiều cao cây: $\Theta(\log_2 n)$.

#### 2. Thuật toán `reheapDown` (Sift-Down / Bubble-Down):
Được gọi khi một phần tử ở nút $idx$ nhỏ hơn con của nó:
```cpp
template <class T>
void reheapDown(T a[], int n, int idx) {
    while (2 * idx + 1 < n) {
        int left = 2 * idx + 1;
        int right = 2 * idx + 2;
        int maxChild = left;
        if (right < n && a[right] > a[left]) maxChild = right;

        if (a[idx] < a[maxChild]) {
            std::swap(a[idx], a[maxChild]);
            idx = maxChild;
        } else break;
    }
}
```
* Số lần tráo đổi tối đa: $\Theta(\log_2 n)$.

---

### 10.3. Giải thuật Thêm & Xóa Gốc

* **Thao tác Thêm (`insert(x)`):**
  1. Đặt $x$ vào cuối mảng tại chỉ số $n$.
  2. Tăng kích thước mảng $n = n + 1$.
  3. Gọi `reheapUp(a, n - 1)` để phục hồi vị trí đúng.
  - Độ phức tạp: $O(\log_2 n)$.
* **Thao tác Xóa Gốc (`deleteRoot` / `extractMax`):**
  1. Lưu giá trị phần tử gốc $A[0]$.
  2. Đưa phần tử cuối cùng $A[n - 1]$ lên thế chỗ vào gốc $A[0]$.
  3. Giảm kích thước mảng $n = n - 1$.
  4. Gọi `reheapDown(a, n, 0)` để đẩy phần tử vi phạm xuống đúng vị trí.
  - Độ phức tạp: $O(\log_2 n)$.

---

### 10.4. Xây dựng Đống (Build-Heap / Floyd's Heapify Algorithm)

#### 1. Phương pháp Bottom-Up của Robert Floyd (1964):
* Thay vì chèn tuần tự $n$ phần tử ($O(n \log n)$), ta khởi tạo mảng tùy ý.
* Bỏ qua toàn bộ các nút lá (vì một nút lá tự thân nó đã là một Heap con hợp lệ).
* Duyệt ngược từ nút nội bộ cuối cùng $i = \lfloor n/2 \rfloor - 1$ lùi về $0$, gọi `reheapDown(a, n, i)`:
```cpp
template <class T>
void buildMaxHeap(T a[], int n) {
    for (int i = n / 2 - 1; i >= 0; i--) {
        reheapDown(a, n, i);
    }
}
```

#### 2. Chứng minh Toán học Độ phức tạp Tuyến tính $\Theta(n)$:
Số lượng nút tối đa tại chiều cao $h$ của một cây hoàn chỉnh là $\lceil n / 2^{h+1} \rceil$. Chi phí của `reheapDown` tại chiều cao $h$ tốn tối đa $c \cdot h$ phép toán.
$$T(n) = \sum_{h=0}^{\lfloor \log_2 n \rfloor} \left\lceil \frac{n}{2^{h+1}} \right\rceil c \cdot h \le c \cdot n \sum_{h=0}^\infty \frac{h}{2^h}$$
Xét chuỗi hình học vô hạn với $|x| < 1$:
$$\sum_{h=0}^\infty x^h = \frac{1}{1 - x}$$
Đạo hàm hai vế theo $x$:
$$\sum_{h=1}^\infty h x^{h-1} = \frac{1}{(1 - x)^2} \iff \sum_{h=0}^\infty \frac{h}{x} x^h = \frac{1}{(1 - x)^2} \implies \sum_{h=0}^\infty h x^h = \frac{x}{(1 - x)^2}$$
Thay $x = \frac{1}{2}$:
$$\sum_{h=0}^\infty \frac{h}{2^h} = \frac{1/2}{(1 - 1/2)^2} = \frac{1/2}{1/4} = 2$$
Thay ngược vào biểu thức tổng:
$$T(n) \le c \cdot n \times 2 = \Theta(n)!$$
> **Ý nghĩa:** Việc xây dựng đống bằng giải thuật Floyd tốn thời gian **tuyến tính $\Theta(n)$**, vượt trội hoàn toàn so với việc chèn lần lượt tốn $\Theta(n \log n)$!

---

### 10.5. Thuật toán Sắp xếp Vun đống (Heap Sort)

```cpp
template <class T>
void heapSort(T a[], int n) {
    // Bước 1: Xây dựng Max-Heap từ mảng ban đầu - O(n)
    buildMaxHeap(a, n);

    // Bước 2: Liên tục đưa phần tử lớn nhất về cuối mảng - O(n log n)
    for (int i = n - 1; i > 0; i--) {
        std::swap(a[0], a[i]);       // Hoán đổi max hiện tại về vị trí đúng cuối cùng
        reheapDown(a, i, 0);         // Phục hồi heap cho phần còn lại kích thước i
    }
}
```
* **Độ phức tạp Thời gian:** Luôn là $\Theta(n \log_2 n)$ trong **mọi trường hợp (Best, Worst, Average)**.
* **Bộ nhớ phụ:** $\Theta(1)$ (Sắp xếp tại chỗ In-place).
* **Tính ổn định:** **KHÔNG ỔN ĐỊNH**.

---

### 10.6. Hàng đợi Ưu tiên & Bài toán Chọn $k$ Phần tử Cực trị

1. **Hàng đợi Ưu tiên (Priority Queue ADT):**
   Cấu trúc dữ liệu trong đó mỗi phần tử gắn liền với một độ ưu tiên. Phép lấy phần tử (`pop`) luôn trả về phần tử có độ ưu tiên cao nhất. Triển khai bằng Binary Heap cho hiệu năng vượt trội: `push` $O(\log n)$, `pop` $O(\log n)$, `top` $O(1)$.
2. **Bài toán Tìm $k$ Phần tử Lớn nhất trong $n$ Phần tử ($n \gg k$):**
   - Khởi tạo một **Min-Heap** chứa $k$ phần tử đầu tiên.
   - Duyệt $n - k$ phần tử tiếp theo: Nếu phần tử mới $> \text{gốc của Min-Heap}$, thay thế gốc bằng phần tử mới và gọi `reheapDown`.
   - Kết thúc, $k$ phần tử còn lại trong Min-Heap chính là $k$ phần tử lớn nhất của toàn bộ tập dữ liệu.
   - **Hiệu năng:** Thời gian $\Theta(n \log_2 k)$, Bộ nhớ phụ $\Theta(k)$ (tối ưu hơn việc sắp xếp toàn bộ mảng vốn tốn $\Theta(n \log n)$ và $\Theta(n)$ bộ nhớ).

# PHẦN V: LÝ THUYẾT ĐỒ THỊ & CÁC THUẬT TOÁN ĐỒ THỊ NÂNG CAO

---

## CHƯƠNG 11: BIỂU DIỄN ĐỒ THỊ & DUYỆT ĐỒ THỊ (GRAPH REPRESENTATION & TRAVERSALS)

Đồ thị là cấu trúc dữ liệu phi tuyến tính tổng quát nhất trong khoa học máy tính, biểu diễn tập hợp các đối tượng cùng các mối quan hệ kết nối giữa chúng: $G = (V, E)$, trong đó $V$ là tập hợp các đỉnh (Vertices), $E$ là tập hợp các cạnh (Edges) nối các cặp đỉnh.

---

### 11.1. Khái niệm Đồ thị Hình thức, Định lý Bắt tay & Phân loại

#### 1. Các Phân loại Đồ thị Cốt lõi:
* **Đồ thị Vô hướng (Undirected Graph):** Cạnh $e = (u, v)$ là một cặp không có thứ tự. $u$ và $v$ kề nhau; cạnh $e$ liên thuộc với cả $u$ và $v$.
* **Đồ thị Có hướng (Directed Graph / Digraph):** Cung $e = (u, v)$ là một cặp có thứ tự từ đỉnh đầu $u$ (Tail) tới đỉnh cuối $v$ (Head).
* **Bậc của Đỉnh (Degree):**
  - Trong đồ thị vô hướng: $\deg(v)$ là số lượng cạnh liên thuộc với đỉnh $v$.
  - Trong đồ thị có hướng:
    - **Bán bậc vào (In-degree - $d^-(v)$):** Số lượng cung đi vào đỉnh $v$.
    - **Bán bậc ra (Out-degree - $d^+(v)$):** Số lượng cung đi ra khỏi đỉnh $v$.
    - Tổng bậc của đỉnh: $\deg(v) = d^-(v) + d^+(v)$.

#### 2. Định lý Bắt tay (Handshaking Lemma):
> [!IMPORTANT]
> **ĐỊNH LÝ BẮT TAY TRONG ĐỒ THỊ VÔ HƯỚNG:**
> Tổng bậc của tất cả các đỉnh trong một đồ thị vô hướng luôn bằng hai lần số cạnh:
> $$\sum_{v \in V} \deg(v) = 2|E|$$
> *Hệ quả:* Trong mọi đồ thị vô hướng, **số lượng các đỉnh có bậc lẻ luôn luôn là một số chẵn**!
> 
> **ĐỊNH LÝ TRONG ĐỒ THỊ CÓ HƯỚNG:**
> Tổng bán bậc vào bằng tổng bán bậc ra và bằng đúng số lượng cung:
> $$\sum_{v \in V} d^-(v) = \sum_{v \in V} d^+(v) = |E|$$

#### 3. Các Khái niệm Cấu trúc Liên kết:
* **Đường đi (Path):** Dãy các đỉnh $v_0, v_1, \dots, v_k$ sao cho $(v_i, v_{i+1}) \in E$. Độ dài đường đi là số lượng cạnh $k$.
* **Đường đi Đơn (Simple Path):** Đường đi không đi qua bất kỳ đỉnh nào quá một lần.
* **Chu trình (Cycle):** Đường đi khép kín ($v_0 == v_k$) có độ dài $\ge 3$ và các đỉnh trung gian đôi một phân biệt.
* **Đồ thị Có hướng Không Chu trình (DAG - Directed Acyclic Graph):** Đồ thị có hướng hoàn toàn không chứa bất kỳ chu trình nào. Đây là cấu trúc nền tảng cho Sắp xếp Tô-pô và Quy hoạch động.

---

### 11.2. Bốn Phương pháp Biểu diễn Đồ thị trong Máy tính

#### 1. Ma trận Kề (Adjacency Matrix):
Ma trận 2 chiều $A$ kích thước $|V| \times |V|$:
$$A[u][v] = \begin{cases} 1 \text{ (hoặc trọng số } w) & \text{nếu } (u, v) \in E \\ 0 \text{ (hoặc } \infty) & \text{nếu } (u, v) \notin E \end{cases}$$
* **Ưu điểm:** Kiểm tra cạnh $(u, v)$ có tồn tại hay không chỉ tốn $\Theta(1)$. Thao tác thêm/xóa cạnh tốn $\Theta(1)$.
* **Nhược điểm:** Tốn bộ nhớ cố định $\Theta(V^2)$ bất kể số cạnh nhiều hay ít. Thao tác duyệt tất cả các đỉnh kề của một đỉnh tốn $\Theta(V)$ ngay cả khi đỉnh đó không có cạnh nào.
* **Biến thể Mảng 1 chiều Duỗi phẳng (Flattened Matrix):** Lưu trữ trong mảng 1D kích thước $V \times V$ với công thức ánh xạ chỉ số: $\text{Index}(u, v) = u \times |V| + v$.

#### 2. Danh sách Kề (Adjacency List):
Mảng gồm $|V|$ danh sách liên kết hoặc `std::vector`, trong đó phần tử thứ $u$ lưu danh sách tất cả các đỉnh kề với $u$: `vector<int> adj[V];` (hoặc `vector<pair<int, int>> adj[V];` cho đồ thị có trọng số).
* **Ưu điểm:** Bộ nhớ tối ưu $\Theta(V + E)$ (đồ thị có hướng) hoặc $\Theta(V + 2E)$ (đồ thị vô hướng). Thao tác duyệt các đỉnh kề của $u$ chỉ tốn thời gian đúng bằng bậc $\Theta(\deg(u))$.
* **Nhược điểm:** Kiểm tra cạnh $(u, v)$ tốn $O(\deg(u))$.

#### 3. Danh sách Cạnh (Edge List):
Mảng lưu trữ toàn bộ các cạnh dưới dạng bộ ba: `struct Edge { int u, v, w; }; vector<Edge> edges;`.
* Bộ nhớ: $\Theta(E)$.
* Cực kỳ thích hợp cho các thuật toán duyệt theo danh sách cạnh như **Thuật toán Kruskal** và **Bellman-Ford**.

#### 4. Mảng Nén Hàng (Compressed Sparse Row - CSR):
Sử dụng 2 mảng 1 chiều liên tục: mảng `edges[]` lưu trữ toàn bộ danh sách đỉnh kề, và mảng `offsets[]` lưu vị trí bắt đầu của danh sách kề cho từng đỉnh. Đây là định dạng chuẩn mực trong tính toán đồ thị hiệu năng cao (HPC Graph Frameworks) vì tối ưu hóa bộ nhớ cache tuyệt đối.

#### Bảng So sánh 4 Phương pháp Biểu diễn Đồ thị:

| Thao tác / Tiêu chí | Ma trận Kề (Adj Matrix) | Danh sách Kề (Adj List) | Danh sách Cạnh (Edge List) | CSR (Compressed Sparse Row) |
| :--- | :---: | :---: | :---: | :---: |
| **Không gian Bộ nhớ** | $\Theta(V^2)$ | **$\Theta(V + E)$** | **$\Theta(E)$** | **$\Theta(V + E)$ (Tối ưu nhất)** |
| **Kiểm tra Cạnh $(u, v)$** | **$\Theta(1)$** | $O(\deg(u))$ | $\Theta(E)$ | $O(\deg(u))$ (Binary search) |
| **Duyệt Đỉnh kề của $u$** | $\Theta(V)$ | **$\Theta(\deg(u))$** | $\Theta(E)$ | **$\Theta(\deg(u))$** |
| **Thêm một Cạnh mới** | **$\Theta(1)$** | $\Theta(1)$ | $\Theta(1)$ | $\Theta(E)$ (Đồ thị tĩnh) |
| **Loại Đồ thị Phù hợp** | Đồ thị dày ($E \approx V^2$) | Đồ thị thưa ($E \ll V^2$) | Thuật toán Kruskal, Bellman | Đồ thị tĩnh đọc nhiều |

---

### 11.3. Ánh xạ Nhãn Đỉnh thành Chỉ số Số nguyên (Vertex Label Mapping)

Trong thực tế, các đỉnh đồ thị thường được đặt tên bằng chuỗi ký tự (ví dụ: tên thành phố `"SGN"`, `"HAN"`, `"DAD"`). Để thuật toán vận hành với hiệu năng tối đa, ta xây dựng một lớp bao bọc ánh xạ hai chiều:
1. `std::unordered_map<string, int> labelToId`: Ánh xạ tên đỉnh sang ID số nguyên từ $0$ đến $|V| - 1$ trong $O(1)$.
2. `std::vector<string> idToLabel`: Truy xuất ngược từ ID số nguyên ra tên nhãn trong $O(1)$.

---

### 11.4. Thuật toán Tìm kiếm theo Chiều sâu (DFS) & Mô hình 3 Màu

#### 1. Mô hình Ba Màu Đỉnh (Cormen - CLRS):
Để theo dõi trạng thái thăm của các đỉnh trong quá trình đệ quy:
* **WHITE (Trắng):** Đỉnh chưa từng được duyệt tới.
* **GRAY (Xám):** Đỉnh đang được khám phá, hiện đang nằm trong Call Stack đệ quy.
* **BLACK (Đen):** Đỉnh đã được duyệt xong hoàn toàn cùng với toàn bộ cây con của nó, đã thoát khỏi Call Stack.

```cpp
void DFS_Visit(int u, vector<int> adj[], int color[], int parent[]) {
    color[u] = GRAY; // 1. Bắt đầu khám phá u
    for (int v : adj[u]) {
        if (color[v] == WHITE) {
            parent[v] = u;
            DFS_Visit(v, adj, color, parent); // Cung Cây (Tree Edge)
        } else if (color[v] == GRAY) {
            // Phát hiện Cung Ngược (Back Edge) -> ĐỒ THỊ CHỨA CHU TRÌNH!
        }
    }
    color[u] = BLACK; // 2. Hoàn thành duyệt u
}
```

#### 2. Phân loại Bốn Loại Cung trong Đồ thị Có hướng:
Quá trình duyệt DFS tạo ra một Rừng Cây DFS (DFS Forest) và phân loại tất cả các cung của đồ thị thành 4 loại:
1. **Cung Cây (Tree Edge):** Cung $(u, v)$ đi tới đỉnh $v$ màu **TRẮNG**. Đây là các cung thực sự tạo nên cây DFS.
2. **Cung Ngược (Back Edge):** Cung $(u, v)$ đi tới đỉnh tổ tiên $v$ màu **XÁM** (đang nằm trên Call Stack).
   > [!CRITICAL]
   > **ĐỊNH LÝ PHÁT HIỆN CHU TRÌNH:** Một đồ thị có hướng chứa chu trình KHI VÀ CHỈ KHI quá trình duyệt DFS phát hiện ít nhất một **Cung Ngược (Back Edge)**!
3. **Cung Tiến (Forward Edge):** Cung $(u, v)$ đi tới đỉnh con cháu $v$ màu **ĐEN** đã duyệt xong nằm trong cùng cây DFS.
4. **Cung Chéo (Cross Edge):** Cung $(u, v)$ đi tới đỉnh $v$ màu **ĐEN** thuộc về một nhánh cây DFS khác hoặc một cây khác trong rừng DFS.

---

### 11.5. Thuật toán Tìm kiếm theo Chiều rộng (BFS) & Cây BFS

* Sử dụng Hàng đợi (Queue) để duyệt lan tỏa theo từng tầng khoảng cách:
  - Khởi tạo: Đỉnh nguồn $s$ có `dist[s] = 0`, đẩy vào Queue.
  - Vòng lặp: Lấy $u$ khỏi Queue, duyệt mọi đỉnh kề $v$. Nếu $v$ chưa thăm (`dist[v] == -1`): gán `dist[v] = dist[u] + 1`, `parent[v] = u` và đẩy $v$ vào Queue.
* **Định lý Vàng của BFS:**
  Trên đồ thị **KHÔNG CÓ TRỌNG SỐ** (hoặc tất cả các cạnh có cùng trọng số), đường đi từ đỉnh nguồn $s$ đến mọi đỉnh $v$ trên cây BFS **chính là đường đi ngắn nhất (với số cạnh ít nhất)**!
* **Độ phức tạp:** $\Theta(V + E)$ với Danh sách kề.

---

### 11.6. Sắp xếp Tô-pô (Topological Sort)

Sắp xếp Tô-pô của một đồ thị có hướng là một thứ tự tuyến tính của các đỉnh sao cho với mọi cung $(u, v) \in E$, đỉnh $u$ luôn xuất hiện trước đỉnh $v$.
* **Điều kiện Tồn tại Duy nhất:** Đồ thị **BẮT BUỘC PHẢI LÀ MỘT DAG (Directed Acyclic Graph)**!

```
                    SẮP XẾP TÔ-PÔ CỦA MỘT ĐỒ THỊ DAG
          Đồ thị phụ thuộc bài học:            Thứ tự Tô-pô tuyến tính:
            CS101 ------> CS201
              |             |                  CS101 -> MATH1 -> CS201 -> CS301
              v             v
            MATH1 ------> CS301
```

#### 1. Thuật toán Kahn (Bóc tách Đỉnh Bậc vào bằng 0 - Queue-based):
1. Tính bán bậc vào $d^-(v)$ cho mọi đỉnh $v \in V$.
2. Đẩy tất cả các đỉnh có $d^-(v) == 0$ vào một Hàng đợi (Queue).
3. Trong khi Queue không rỗng:
   - Lấy đỉnh $u$ ra, đưa vào danh sách kết quả Tô-pô.
   - Với mỗi đỉnh kề $v$ của $u$: Giảm $d^-(v)$ đi 1. Nếu $d^-(v) == 0$, lập tức đẩy $v$ vào Queue.
4. **Kiểm tra Chu trình:** Nếu số lượng đỉnh trong kết quả Tô-pô $< |V| \implies$ Đồ thị **chứa chu trình** (không thể sắp xếp Tô-pô)!

#### 2. Thuật toán DFS (Tarjan - Reverse Post-Order):
1. Chạy DFS trên toàn bộ đồ thị.
2. Mỗi khi một đỉnh $u$ chuyển sang màu **ĐEN** (tức đã duyệt xong toàn bộ các nhánh con phụ thuộc phía sau nó), ta đẩy $u$ vào một Ngăn xếp (Stack).
3. Kết thúc thuật toán, thứ tự lấy ra từ đỉnh Stack xuống đáy chính là Thứ tự Tô-pô hợp lệ!
4. Nếu trong quá trình DFS phát hiện cung ngược tới đỉnh màu XÁM $\implies$ Đồ thị có chu trình.
* **Độ phức tạp:** Cả 2 thuật toán đều đạt thời gian tối ưu $\Theta(V + E)$.

---

## CHƯƠNG 12: ĐƯỜNG ĐI NGẮN NHẤT & CÂY KHUNG NHỎ NHẤT (SHORTEST PATHS & MST)

---

### 12.1. Đường đi Ngắn nhất Từ một Nguồn (SSSP): Thuật toán Dijkstra

Áp dụng cho đồ thị có hướng hoặc vô hướng với điều kiện **TRỌNG SỐ TẤT CẢ CÁC CẠNH ĐỀU PHẢI KHÔNG ÂM ($w(u, v) \ge 0$)**.

#### 1. Kỹ thuật Nới lỏng Cạnh (Edge Relaxation):
Kiểm tra xem việc đi qua đỉnh trung gian $u$ có giúp rút ngắn đường đi tới $v$ hay không:
```cpp
void relax(int u, int v, int w) {
    if (dist[u] != INF && dist[u] + w < dist[v]) {
        dist[v] = dist[u] + w;
        parent[v] = u;
    }
}
```

#### 2. Chiến lược Tham lam (Greedy Strategy) & Hàng đợi Ưu tiên:
Thuật toán duy trì một tập hợp $S$ các đỉnh đã xác định chắc chắn khoảng cách ngắn nhất. Tại mỗi bước, chọn đỉnh $u \notin S$ có `dist[u]` nhỏ nhất đưa vào $S$ và nới lỏng tất cả các cạnh đi ra từ $u$.

```cpp
typedef pair<int, int> pii; // (khoảng cách, đỉnh)

void dijkstra(int src, int V, vector<pii> adj[], vector<int>& dist) {
    dist.assign(V, INF);
    priority_queue<pii, vector<pii>, greater<pii>> pq; // Min-Heap

    dist[src] = 0;
    pq.push({0, src});

    while (!pq.empty()) {
        int d = pq.top().first;
        int u = pq.top().second;
        pq.pop();

        if (d > dist[u]) continue; // Bỏ qua bản ghi cũ lỗi thời

        for (auto edge : adj[u]) {
            int v = edge.first;
            int w = edge.second;
            if (dist[u] + w < dist[v]) {
                dist[v] = dist[u] + w;
                pq.push({dist[v], v});
            }
        }
    }
}
```
* **Độ phức tạp:** Với Min-Heap nhị phân: **$O((V + E) \log_2 V)$**.

#### 3. Vì sao Thuật toán Dijkstra THẤT BẠI khi có Trọng số Âm?
> [!CAUTION]
> Chiến lược tham lam của Dijkstra chốt cố định đỉnh $u$ vĩnh viễn ngay khi lấy ra khỏi Priority Queue dựa trên tiên đề: "Các cạnh tiếp theo đều không âm nên khoảng cách chỉ có thể tăng lên hoặc giữ nguyên".
> Nếu tồn tại cạnh âm, đường đi dài hơn đi qua cạnh âm có thể cho ra tổng trọng số nhỏ hơn, phá hủy hoàn toàn tính đúng đắn của tiên đề tham lam!

---

### 12.2. Thuật toán Bellman-Ford: Trọng số Âm & Phát hiện Chu trình Âm

Áp dụng cho đồ thị tổng quát có thể chứa **TRỌNG SỐ ÂM**.

#### 1. Nguyên lý Hoạt động:
Đường đi ngắn nhất đơn trong đồ thị $V$ đỉnh chứa tối đa $V - 1$ cạnh. Do đó, việc nới lỏng toàn bộ $|E|$ cạnh liên tiếp $|V| - 1$ lần bảo đảm sẽ truyền đúng khoảng cách ngắn nhất tới mọi đỉnh.

#### 2. Giải thuật:
1. Khởi tạo: `dist[src] = 0`, tất cả các đỉnh khác bằng `INF`.
2. Lặp chính xác $|V| - 1$ lần:
   - Duyệt qua toàn bộ danh sách $|E|$ cạnh của đồ thị.
   - Nới lỏng: Nếu `dist[u] + w < dist[v]`, cập nhật `dist[v] = dist[u] + w`.
3. **Bước Kiểm tra Chu trình Âm (Negative Cycle Detection):**
   - Chạy thêm một lượt nới lỏng thứ $|V|$:
   - Nếu vẫn tồn tại bất kỳ cạnh $(u, v)$ nào thỏa mãn `dist[u] + w < dist[v]`, kết luận: **ĐỒ THỊ CHỨA CHU TRÌNH ÂM (Negative Weight Cycle)** từ nguồn $s$ có thể đi tới được! Khoảng cách tới các đỉnh liên quan có thể giảm tới $-\infty$.
* **Độ phức tạp:** Thời gian **$\Theta(V \cdot E)$**.

---

### 12.3. Đường đi Ngắn nhất trên Đồ thị DAG ($O(V + E)$)

Trên một Đồ thị Có hướng Không Chu trình (DAG), ta có thể giải bài toán SSSP với hiệu năng siêu việt bằng Quy hoạch động kết hợp Sắp xếp Tô-pô:
1. Sắp xếp Tô-pô các đỉnh của DAG: $\Theta(V + E)$.
2. Khởi tạo `dist[src] = 0`, các đỉnh khác bằng `INF`.
3. Duyệt các đỉnh $u$ theo đúng thứ tự Tô-pô. Với mỗi $u$, nới lỏng tất cả các cạnh $(u, v)$ đi ra từ $u$.
* **Độ phức tạp:** Thời gian **$\Theta(V + E)$**! Hoạt động hoàn toàn chính xác ngay cả khi có trọng số âm!

---

### 12.4. Đường đi Ngắn nhất Giữa Mọi Cặp Đỉnh (APSP): Thuật toán Floyd-Warshall

Tìm khoảng cách ngắn nhất giữa tất cả các cặp đỉnh $(u, v) \in V \times V$.

#### 1. Công thức Quy hoạch Động:
Gọi $D^{(k)}[i][j]$ là độ dài đường đi ngắn nhất từ đỉnh $i$ tới đỉnh $j$ mà chỉ được phép sử dụng các đỉnh trung gian thuộc tập $\{1, 2, \dots, k\}$.
$$D^{(k)}[i][j] = \min\left(D^{(k-1)}[i][j], \; D^{(k-1)}[i][k] + D^{(k-1)}[k][j]\right)$$

#### 2. Cài đặt C++:
```cpp
void floydWarshall(int V, vector<vector<int>>& dist) {
    // 3 vòng lặp: k BẮT BUỘC phải là vòng lặp NGOÀI CÙNG!
    for (int k = 0; k < V; k++) {
        for (int i = 0; i < V; i++) {
            for (int j = 0; j < V; j++) {
                if (dist[i][k] != INF && dist[k][j] != INF) {
                    if (dist[i][k] + dist[k][j] < dist[i][j]) {
                        dist[i][j] = dist[i][k] + dist[k][j];
                    }
                }
            }
        }
    }
}
```
* **Phát hiện Chu trình Âm:** Sau khi thuật toán kết thúc, nếu tồn tại bất kỳ đỉnh $i$ nào có $dist[i][i] < 0 \implies$ Đồ thị chứa chu trình âm.
* **Độ phức tạp:** Thời gian **$\Theta(V^3)$**, Không gian $\Theta(V^2)$.

---

### 12.5. Cây Khung Nhỏ Nhất (Minimum Spanning Tree - MST)

Cho đồ thị vô hướng, liên thông, có trọng số $G = (V, E)$. Cây khung nhỏ nhất là một cây con bao trùm toàn bộ $|V|$ đỉnh, chứa đúng $|V| - 1$ cạnh và có tổng trọng số các cạnh là nhỏ nhất.

#### Hai Tính chất Nền tảng:
1. **Tính chất Nhát cắt (Cut Property):** Với bất kỳ nhát cắt $(S, V \setminus S)$ nào của đồ thị, cạnh có trọng số nhỏ nhất nối giữa một đỉnh thuộc $S$ và một đỉnh thuộc $V \setminus S$ chắc chắn thuộc về một cây khung nhỏ nhất.
2. **Tính chất Chu trình (Cycle Property):** Với bất kỳ chu trình nào trong đồ thị, cạnh có trọng số lớn nhất trên chu trình đó không bao giờ thuộc về cây khung nhỏ nhất.

---

### 12.6. Thuật toán Kruskal & Cấu trúc Tập hợp Rời nhau (DSU / Union-Find)

#### 1. Nguyên lý Hoạt động:
Thuật toán tham lam theo cạnh:
1. Sắp xếp toàn bộ $|E|$ cạnh theo thứ tự trọng số tăng dần.
2. Khởi tạo mỗi đỉnh là một tập hợp độc lập trong cấu trúc DSU.
3. Duyệt từng cạnh $(u, v)$ từ bé đến lớn:
   - Dùng `find(u)` và `find(v)` để kiểm tra $u$ và $v$ đã liên thông với nhau chưa.
   - Nếu khác tập hợp: Kết nạp cạnh $(u, v)$ vào MST và hợp nhất hai tập hợp: `unionSets(u, v)`.
   - Nếu cùng tập hợp: Bỏ qua (vì sẽ tạo thành chu trình).
4. Dừng khi đã kết nạp đủ $|V| - 1$ cạnh.

#### 2. Cài đặt Cấu trúc DSU Tối ưu Tột bậc (Path Compression & Union by Rank):
```cpp
struct DSU {
    vector<int> parent, rank;
    DSU(int n) : parent(n), rank(n, 0) {
        for (int i = 0; i < n; i++) parent[i] = i;
    }
    // Nén đường đi (Path Compression)
    int find(int i) {
        if (parent[i] == i) return i;
        return parent[i] = find(parent[i]);
    }
    // Hợp nhất theo hạng (Union by Rank)
    bool unionSets(int i, int j) {
        int rootI = find(i);
        int rootJ = find(j);
        if (rootI == rootJ) return false;
        if (rank[rootI] < rank[rootJ]) parent[rootI] = rootJ;
        else if (rank[rootI] > rank[rootJ]) parent[rootJ] = rootI;
        else { parent[rootJ] = rootI; rank[rootI]++; }
        return true;
    }
};
```
* **Độ phức tạp:** Sắp xếp cạnh tốn $O(E \log_2 E) = O(E \log_2 V)$. Thao tác DSU tốn $O(E \cdot \alpha(V)) \approx O(E)$.
  $\implies$ Tổng thời gian Kruskal: **$O(E \log_2 V)$**. Cực kỳ tối ưu cho đồ thị thưa.

---

### 12.7. Thuật toán Prim

* **Nguyên lý:** Thuật toán tham lam theo đỉnh. Bắt đầu từ 1 đỉnh nguồn tùy ý. Dùng Min-Heap duy trì các cạnh nối giữa cây hiện tại với các đỉnh chưa thuộc cây. Mỗi bước chọn đỉnh ngoài cây có khoảng cách tới cây nhỏ nhất, kết nạp đỉnh đó vào cây và nới lỏng các đỉnh kề.
* **Độ phức tạp:** Sử dụng Min-Heap nhị phân: **$O(E \log_2 V)$**. Cực kỳ thích hợp cho đồ thị dày.

---

## CHƯƠNG 13: CÁC CẤU TRÚC LIÊN THÔNG & GHÉP CẶP ĐỒ THỊ (CC, SCC, BIPARTITE & MATCHING)

---

### 13.1. Thành phần Liên thông Đồ thị Vô hướng (Connected Components - CC)

Chia tập đỉnh của đồ thị vô hướng thành các lớp tương đương rời nhau sao cho giữa hai đỉnh bất kỳ trong cùng một lớp đều có đường đi tới nhau.
* Sử dụng duyệt BFS hoặc DFS xuất phát từ từng đỉnh chưa thăm: $\Theta(V + E)$.

---

### 13.2. Thành phần Liên thông Mạnh Đồ thị Có hướng (SCC)

Một đồ thị con $C = (V_C, E_C)$ của đồ thị có hướng được gọi là **Liên thông mạnh (Strongly Connected Component - SCC)** nếu giữa hai đỉnh bất kỳ $u, v \in V_C$ đều tồn tại cả đường đi $u \rightsquigarrow v$ và đường đi $v \rightsquigarrow u$.

#### 1. Thuật toán Kosaraju-Sharir (2 Lượt DFS):
1. **Lượt 1:** Chạy DFS trên đồ thị gốc $G$. Mỗi khi một đỉnh hoàn tất duyệt xong, đẩy đỉnh đó vào một Ngăn xếp (Stack).
2. **Đảo ngược Đồ thị:** Xây dựng đồ thị chuyển vị $G^T$ (đổi chiều tất cả các cung $(u, v) \to (v, u)$).
3. **Lượt 2:** Lần lượt lấy các đỉnh ra khỏi Stack. Nếu đỉnh đó chưa được thăm trong $G^T$, chạy DFS trên $G^T$ xuất phát từ đỉnh đó. Toàn bộ các đỉnh thăm được trong lần DFS này hợp thành một **Thành phần Liên thông Mạnh (SCC)** duy nhất!
* **Độ phức tạp:** $\Theta(V + E)$.

#### 2. Thuật toán Tarjan Tìm SCC (1 Lượt DFS Duy nhất):
Sử dụng một Ngăn xếp nội bộ và gán cho mỗi đỉnh $u$ hai chỉ số:
* `dfn[u]`: Thời điểm bắt đầu duyệt tới đỉnh $u$ (Discovery Time).
* `low[u]`: Giá trị `dfn` nhỏ nhất của đỉnh mà từ $u$ có thể đi tới được thông qua các cung cây và tối đa 1 cung ngược trong cùng SCC.

```cpp
void tarjanDFS(int u, vector<int> adj[], vector<int>& dfn, vector<int>& low, 
               stack<int>& st, vector<bool>& inStack, int& timer) {
    dfn[u] = low[u] = ++timer;
    st.push(u);
    inStack[u] = true;

    for (int v : adj[u]) {
        if (!dfn[v]) { // v chưa thăm
            tarjanDFS(v, adj, dfn, low, st, inStack, timer);
            low[u] = min(low[u], low[v]);
        } else if (inStack[v]) { // v đang trên Call Stack -> Cung ngược
            low[u] = min(low[u], dfn[v]);
        }
    }

    // Dấu hiệu nhận biết GỐC của một SCC:
    if (low[u] == dfn[u]) {
        while (true) {
            int v = st.top(); st.pop();
            inStack[v] = false;
            cout << v << " ";
            if (u == v) break;
        }
        cout << "\n"; // Hoàn thành 1 SCC
    }
}
```
* **Độ phức tạp:** $\Theta(V + E)$.

---

### 13.3. Kiểm tra Đồ thị Hai phía (Bipartite Graph Checking)

Một đồ thị là **Đồ thị Hai phía (Bipartite Graph)** nếu tập đỉnh $V$ có thể phân chia thành hai tập rời nhau $V_1$ và $V_2$ sao cho mọi cạnh chỉ nối giữa một đỉnh thuộc $V_1$ với một đỉnh thuộc $V_2$ (không có cạnh nội bộ nối giữa hai đỉnh cùng thuộc $V_1$ hoặc cùng thuộc $V_2$).

#### Định lý Kőnig (1936):
> [!IMPORTANT]
> Một đồ thị là đồ thị hai phía KHI VÀ CHỈ KHI nó **HOÀN TOÀN KHÔNG CHỨA BẤT KỲ CHU TRÌNH ĐỘ DÀI LẺ NÀO**!

#### Thuật toán Tô 2 Màu (2-Coloring Algorithm):
Dùng BFS hoặc DFS tô các đỉnh bằng 2 màu (0 và 1):
1. Tô màu đỉnh xuất phát bằng màu 0.
2. Với mỗi đỉnh kề $v$ của $u$:
   - Nếu $v$ chưa tô màu: Gán `color[v] = 1 - color[u]` và tiếp tục duyệt.
   - Nếu $v$ đã tô màu VÀ `color[v] == color[u]`: Phát hiện hai đỉnh kề nhau có cùng màu $\implies$ **ĐỒ THỊ KHÔNG PHẢI HAI PHÍA**!
* **Độ phức tạp:** $\Theta(V + E)$.

---

### 13.4. Ghép cặp Cực đại trên Đồ thị Hai phía (Maximum Bipartite Matching)

* **Ghép cặp (Matching):** Tập hợp các cạnh $M \subseteq E$ sao cho không có hai cạnh nào có chung đỉnh.
* **Đường tăng luồng (Augmenting Path - Bổ đề Berge):** Đường đi bắt đầu và kết thúc tại hai đỉnh tự do (chưa được ghép), với các cạnh luân phiên không thuộc $M$ và thuộc $M$. Nếu tìm được đường tăng luồng, đảo ngược trạng thái các cạnh trên đường đi sẽ làm kích thước ghép cặp tăng thêm 1!
* **Quy đổi về Bài toán Luồng Cực đại (Max Flow Reduction):**
  1. Tạo đỉnh phát $S$ nối tới mọi đỉnh của tập $V_1$ với dung lượng bằng 1.
  2. Tạo đỉnh thu $T$, nối từ mọi đỉnh của tập $V_2$ tới $T$ với dung lượng bằng 1.
  3. Định hướng các cạnh gốc từ $V_1 \to V_2$ với dung lượng bằng 1.
  4. Chạy thuật toán Ford-Fulkerson tìm luồng cực đại từ $S \to T$. Giá trị luồng cực đại chính là số cặp ghép tối đa!
* **Độ phức tạp:** $O(V \cdot E)$. Thuật toán Hopcroft-Karp cải tiến đạt $O(E \sqrt{V})$.

# PHẦN VI: TỔNG HỢP CÔNG THỨC, PHÂN TÍCH BẪY ĐỀ THI & CẨM NANG ÔN TẬP

---

## CHƯƠNG 14: BẢNG TRA CỨU NHANH ĐỘ PHỨC TẠP & CÔNG THỨC VÀNG (CHEAT SHEET)

---

### 14.1. Bảng Tra cứu Toàn bộ Độ phức tạp Thời gian & Không gian

Dưới đây là ma trận hiệu năng chuẩn xác tuyệt đối của tất cả các cấu trúc dữ liệu và giải thuật trong toàn bộ chương trình môn học Cấu trúc Dữ liệu & Giải thuật (CO2003):

#### 1. Cấu trúc Dữ liệu Tuyến tính & Bảng băm:

| Cấu trúc Dữ liệu | Truy xuất (`get(i)`) | Thêm vào Đầu | Thêm vào Cuối | Xóa ở Đầu | Xóa ở Cuối | Tìm kiếm Khóa | Bộ nhớ Phụ |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| **Mảng Động (ArrayList)** | $\Theta(1)$ | $\Theta(n)$ | $\Theta(1)$ amortized | $\Theta(n)$ | $\Theta(1)$ | $\Theta(n)$ | Thấp nhất |
| **Danh sách LK Đơn (SLL)** | $\Theta(n)$ | $\Theta(1)$ | $\Theta(1)$ (Có tail) | $\Theta(1)$ | **$\Theta(n)$ (Cần pre)** | $\Theta(n)$ | 1 con trỏ / node |
| **Danh sách LK Đôi (DLL)** | $\Theta(n)$ | $\Theta(1)$ | $\Theta(1)$ | $\Theta(1)$ | **$\Theta(1)$** | $\Theta(n)$ | 2 con trỏ / node |
| **Danh sách LK Vòng (CLL)** | $\Theta(n)$ | $\Theta(1)$ | $\Theta(1)$ (Với tail) | $\Theta(1)$ | $\Theta(n)$ (Vòng đơn) | $\Theta(n)$ | 1 con trỏ / node |
| **Ngăn xếp (Stack - Mảng/SLL)**| $O(n)$ | $\Theta(1)$ (Push) | - | $\Theta(1)$ (Pop) | - | $O(n)$ | $O(n)$ |
| **Hàng đợi Vòng (Circular Queue)**| - | - | $\Theta(1)$ (Enqueue) | $\Theta(1)$ (Dequeue) | - | $O(n)$ | $O(N)$ mảng cố định |
| **Bảng băm (Separate Chaining)**| - | $\Theta(1)$ | - | $\Theta(1)$ trung bình | - | $\Theta(1 + \alpha)$ | $O(V + n)$ |
| **Bảng băm (Open Addressing)** | - | $\Theta\left(\frac{1}{1-\alpha}\right)$ | - | $\Theta\left(\frac{1}{1-\alpha}\right)$ | - | $\Theta\left(\frac{1}{1-\alpha}\right)$ | $O(m)$ mảng phẳng |

#### 2. Cấu trúc Cây, Cây Cân bằng & Cấu trúc Đống:

| Cấu trúc Cây | Tìm kiếm (Search) | Thêm (Insert) | Xóa (Delete) | Tìm Min / Max | Chiều cao Cây $h$ | Ghi chú Đặc tính |
| :--- | :---: | :---: | :---: | :---: | :---: | :--- |
| **Cây BST Thông thường** | Trung bình $O(\log n)$, Xấu nhất $O(n)$ | Trung bình $O(\log n)$, Xấu nhất $O(n)$ | Trung bình $O(\log n)$, Xấu nhất $O(n)$ | $O(h)$ | Tốt nhất $\log_2 n$, Xấu nhất $n$ | Dễ bị suy biến thành danh sách liên kết khi chèn có thứ tự. |
| **Cây Cân bằng AVL** | **Chắc chắn $O(\log n)$** | **Chắc chắn $O(\log n)$** | **Chắc chắn $O(\log n)$** | $O(\log n)$ | **$h < 1.44 \log_2 n$** | Cân bằng nghiêm ngặt nhất. Chèn cần $\le 1$ phép quay; Xóa cần $\le O(\log n)$ quay. |
| **Cây Splay (Sleator-Tarjan)** | Amortized $O(\log n)$ | Amortized $O(\log n)$ | Amortized $O(\log n)$ | Amortized $O(\log n)$ | Xấu nhất $O(n)$ | Tự điều chỉnh, không lưu height. Tối ưu cực đại cho dữ liệu có tính cục bộ thời gian. |
| **Cây B bậc $M$ (B-Tree)** | **$O(\log_M n)$** | **$O(M \log_M n)$** | **$O(M \log_M n)$** | $O(\log_M n)$ | **$h \le \log_{\lceil M/2 \rceil} n$** | Cực lùn, tối ưu hóa Disk I/O cho CSDL. Tất cả lá ở cùng 1 tầng. |
| **Binary Heap (Max/Min)** | $\Theta(n)$ | $\Theta(\log n)$ | $\Theta(\log n)$ (Xóa gốc) | **$\Theta(1)$ (Tại gốc)** | $\lfloor \log_2 n \rfloor$ | Xây dựng đống Floyd: $\Theta(n)$. Mảng phẳng không tốn con trỏ. |

#### 3. Các Thuật toán Đồ thị Nâng cao:

| Thuật toán | Mục đích Giải quyết | Cấu trúc Dữ liệu Nền tảng | Độ phức tạp Thời gian | Điều kiện & Phạm vi Áp dụng |
| :--- | :--- | :--- | :---: | :--- |
| **BFS (Breadth-First Search)** | Duyệt theo mức, Đường đi ngắn nhất | Hàng đợi (Queue) | $\Theta(V + E)$ | Đồ thị không trọng số (hoặc trọng số bằng nhau). |
| **DFS (Depth-First Search)** | Duyệt sâu, Phát hiện chu trình, Khớp/Cầu | Ngăn xếp / Đệ quy | $\Theta(V + E)$ | Mọi đồ thị. Chu trình $\iff$ có Cung Ngược (Back Edge). |
| **Kahn's Algorithm** | Sắp xếp Tô-pô (Topological Sort) | Queue + Bán bậc vào $d^-(v)$ | $\Theta(V + E)$ | Bắt buộc là **DAG**. Phát hiện chu trình nếu kết quả $< V$. |
| **Dijkstra's Algorithm** | Đường đi ngắn nhất nguồn đơn (SSSP) | Min-Priority Queue (Binary Heap) | $O((V + E) \log V)$ | **BẮT BUỘC TRỌNG SỐ KHÔNG ÂM ($w \ge 0$)**. |
| **Bellman-Ford Algorithm** | SSSP, Phát hiện Chu trình Âm | Danh sách cạnh | $\Theta(V \cdot E)$ | Xử lý được trọng số âm. Phát hiện chu trình âm ở lần lặp thứ $V$. |
| **DAG Shortest Path** | SSSP trên đồ thị không chu trình | Topo Sort + Relaxation | $\Theta(V + E)$ | **Siêu nhanh**, áp dụng cho DAG kể cả có trọng số âm. |
| **Floyd-Warshall Algorithm**| Đường đi ngắn nhất mọi cặp đỉnh (APSP) | Ma trận 2D $D[V][V]$ | $\Theta(V^3)$ | Mọi cặp đỉnh, $k$ ở vòng ngoài cùng. Phát hiện chu trình âm nếu $D[i][i] < 0$. |
| **Kruskal's Algorithm** | Cây khung nhỏ nhất (MST) | Edge List + DSU (Disjoint Set) | $O(E \log V)$ | Đồ thị vô hướng liên thông. Tối ưu cho đồ thị thưa ($E \ll V^2$). |
| **Prim's Algorithm** | Cây khung nhỏ nhất (MST) | Min-Heap + Danh sách kề | $O(E \log V)$ | Đồ thị vô hướng liên thông. Tối ưu cho đồ thị dày ($E \approx V^2$). |
| **Kosaraju-Sharir** | Thành phần liên thông mạnh (SCC) | 2 Lượt DFS + Đồ thị chuyển vị $G^T$ | $\Theta(V + E)$ | Đồ thị có hướng. |
| **Tarjan's SCC** | Thành phần liên thông mạnh (SCC) | 1 Lượt DFS + `dfn`, `low`, Stack | $\Theta(V + E)$ | Đồ thị có hướng, gốc SCC khi `low[u] == dfn[u]`. |
| **Bipartite Checking** | Kiểm tra Đồ thị Hai phía | BFS / DFS (Tô 2 màu) | $\Theta(V + E)$ | Tương đương đồ thị không chứa chu trình độ dài lẻ. |
| **Hopcroft-Karp / Max Flow**| Ghép cặp cực đại đồ thị hai phía (MBM) | Mạng luồng đơn vị (Ford-Fulkerson) | $O(E \sqrt{V})$ hoặc $O(V \cdot E)$| Đồ thị hai phía. Bổ đề Berge về đường tăng luồng. |

---

### 14.2. Sổ tay Công thức Toán học Thiết yếu cho DSA

#### 1. Các Đẳng thức Tổng Chuỗi Thường gặp trong Phân tích Thuật toán:
* Tổng số nguyên: $\sum_{i=1}^n i = \frac{n(n+1)}{2} = \Theta(n^2)$
* Tổng bình phương: $\sum_{i=1}^n i^2 = \frac{n(n+1)(2n+1)}{6} = \Theta(n^3)$
* Tổng cấp số nhân ($r = 2$): $\sum_{i=0}^k 2^i = 2^{k+1} - 1 = \Theta(2^k)$
* Chuỗi điều hòa: $H_n = \sum_{i=1}^n \frac{1}{i} = \ln n + \gamma + O(1/n) = \Theta(\log n)$
* Chuỗi Floyd Build-Heap: $\sum_{h=0}^\infty \frac{h}{2^h} = 2$

#### 2. Công thức Cốt lõi của Cây và Cây Cân bằng:
* Số cạnh cây $n$ nút: $E = n - 1$.
* Số nút tối đa cây nhị phân chiều cao $h$: $N_{max} = 2^{h+1} - 1$.
* Chiều cao tối thiểu cây nhị phân $n$ nút: $h_{min} = \lceil \log_2(n + 1) \rceil - 1 = \lfloor \log_2 n \rfloor$.
* Cây nhị phân đầy đủ: Số lá $L = I + 1$ ($I$ là số nút nội bộ).
* Cận Fibonacci cây AVL: $N(h) = N(h-1) + N(h-2) + 1 \implies h < 1.44 \log_2(n + 2) - 0.328$.
* Chiều cao cực đại Cây B bậc $M$: $h \le \log_{\lceil M/2 \rceil} \left(\frac{n + 1}{2}\right)$.

#### 3. Công thức Cốt lõi của Lý thuyết Đồ thị:
* Định lý Bắt tay: $\sum_{v \in V} \deg(v) = 2|E|$.
* Số cạnh tối đa trong đơn đồ thị vô hướng: $|E|_{max} = \frac{|V|(|V| - 1)}{2}$.
* Số cạnh tối đa trong đơn đồ thị có hướng: $|E|_{max} = |V|(|V| - 1)$.
* Đồ thị vô hướng liên thông luôn có $|E| \ge |V| - 1$. Nếu đúng $|E| = |V| - 1$ thì đồ thị là một Cây (Tree).

---

## CHƯƠNG 15: CÁC BẪY ĐỀ THI KINH ĐIỂN & CHIẾN LƯỢC ĐẠT ĐIỂM TỐI ĐA (EXAM TRAPS & SURVIVAL GUIDE)

Dưới đây là tổng hợp 16 "cái bẫy" hiểm hóc nhất thường xuyên xuất hiện trong đề thi trắc nghiệm và tự luận cuối kỳ môn Cấu trúc Dữ liệu & Giải thuật tại Đại học Bách Khoa TP.HCM (HCMUT), kèm phương pháp nhận diện và cách giải quyết chuẩn xác 100%:

---

### ⚠️ Bẫy 1: Xóa Phần tử Cuối cùng trên Singly Linked List có con trỏ `tail`
* **Cạm bẫy:** Đề thi hỏi: *"Cho danh sách liên kết đơn có lưu cả hai con trỏ `head` và `tail`. Độ phức tạp thời gian để xóa phần tử cuối cùng (`removeLast`) là bao nhiêu?"* Sinh viên thường thấy có con trỏ `tail` nên vội vàng chọn $O(1)$.
* **Sự thật chuẩn xác:** **BẮT BUỘC LÀ $\Theta(n)$**! Vì liên kết đơn chỉ đi một chiều sang phải, từ `tail` không thể lùi lại node áp chót. Ta buộc phải duyệt từ `head` qua $n-2$ bước để tìm node đứng trước `tail`, cập nhật con trỏ `pre->next = nullptr` và gán `tail = pre`. Muốn đạt $O(1)$ thì bắt buộc phải dùng **Doubly Linked List**!

---

### ⚠️ Bẫy 2: Xóa Phần tử trong Bảng băm Địa chỉ Mở (Open Addressing)
* **Cạm bẫy:** Đề thi yêu cầu: *"Mô phỏng thao tác xóa khóa $k$ trên bảng băm dùng Linear Probing, sau đó tìm kiếm khóa $k'$ được chèn vào sau $k$."* Sinh viên thường xóa bằng cách gán ô nhớ về `NULL / EMPTY`.
* **Sự thật chuẩn xác:** Nếu gán về `NULL`, chuỗi thăm dò của $k'$ sẽ bị đứt gãy. Khi tìm $k'$, thuật toán gặp ô `NULL` này sẽ dừng lại ngay và báo sai rằng $k'$ không tồn tại!
* **Quy tắc thi cử:** Bắt buộc phải đánh dấu ô bị xóa bằng ký hiệu **Tombstone (`DELETED`)**. Thao tác `search` phải tiếp tục duyệt qua ô `DELETED`, chỉ có thao tác `insert` mới được phép ghi đè lên nó!

---

### ⚠️ Bẫy 3: Số phép So sánh của Straight Selection Sort trên Mảng Đã Sắp Xếp
* **Cạm bẫy:** *"Cho mảng gồm $n$ phần tử đã được sắp xếp tăng dần hoàn hảo. Thuật toán Straight Selection Sort thực hiện bao nhiêu phép so sánh?"* Sinh viên nhầm lẫn với Insertion Sort nên chọn $O(n)$.
* **Sự thật chuẩn xác:** **LUÔN LUÔN LÀ $\frac{n(n-1)}{2} = \Theta(n^2)$ TRONG MỌI TRƯỜNG HỢP**! Thuật toán Selection Sort không có cơ chế dừng sớm; tại mỗi bước $i$, nó vẫn phải duyệt qua tất cả các phần tử từ $i+1$ đến $n-1$ để chắc chắn tìm được phần tử nhỏ nhất.

---

### ⚠️ Bẫy 4: Trường hợp Xấu nhất của Quick Sort
* **Cạm bẫy:** Cho rằng Quick Sort luôn chạy trong $O(n \log n)$.
* **Sự thật chuẩn xác:** Nếu dùng chiến lược chọn pivot ngây thơ (chọn phần tử đầu tiên hoặc cuối cùng) trên **mảng đã có thứ tự (tăng dần hoặc giảm dần)**, mảng con sau phân hoạch luôn bị lệch cực đoan thành 1 mảng $0$ phần tử và 1 mảng $n - 1$ phần tử. Hệ thức trở thành $T(n) = T(n-1) + \Theta(n) \implies \Theta(n^2)$!
* **Cách khắc phục trong bài làm:** Đề xuất dùng **Median-of-Three** hoặc **Randomized Pivot**.

---

### ⚠️ Bẫy 5: Thứ tự Quay trong Thao tác Zig-Zig của Cây Splay (Sleator-Tarjan)
* **Cạm bẫy:** Khi gặp trường hợp Zig-Zig (ví dụ $x$ là con trái của cha $p$, và $p$ là con trái của ông nội $g$), sinh viên quen tay từ cây AVL nên quay $x$ quanh $p$ trước, rồi mới quay $x$ quanh $g$.
* **Sự thật chuẩn xác:** **SAI HOÀN TOÀN!** Thuật toán Sleator-Tarjan quy định bắt buộc phải **quay cha $p$ quanh ông nội $g$ TRƯỚC, rồi mới quay $x$ quanh cha $p$**! Nếu quay con trước, cây sẽ không được thu hẹp độ sâu đường đi, làm mất tính chất Amortized $O(\log n)$.

---

### ⚠️ Bẫy 6: Số Phép Quay khi Thêm vs Xóa trên Cây AVL
* **Cạm bẫy:** Câu hỏi trắc nghiệm: *"Trong trường hợp xấu nhất, thao tác chèn và thao tác xóa trên cây AVL gồm $n$ nút đòi hỏi tối đa bao nhiêu phép quay?"*
* **Sự thật chuẩn xác:**
  - Thao tác **Chèn (Insert):** Tối đa **ĐÚNG 1 PHÉP QUAY** (đơn hoặc kép). Sau phép quay này, chiều cao cây con phục hồi về giá trị cũ $\implies$ dừng ngay lập tức.
  - Thao tác **Xóa (Delete):** Có thể đòi hỏi **lên tới $O(\log_2 n)$ phép quay**! Vì phép quay sau khi xóa làm chiều cao cây con giảm đi 1, sự mất cân bằng có thể tiếp tục lan truyền lên các nút tổ tiên cho tới tận gốc.

---

### ⚠️ Bẫy 7: Độ phức tạp Xây dựng Đống (Build-Heap)
* **Cạm bẫy:** Cho mảng $n$ phần tử, thời gian để biến mảng đó thành một Max-Heap là bao nhiêu? Sinh viên thường nhẩm: có $n$ phần tử, mỗi phần tử thêm vào tốn $O(\log n) \implies O(n \log n)$.
* **Sự thật chuẩn xác:**
  - Nếu chèn lần lượt $n$ phần tử: Tốn $\Theta(n \log n)$.
  - Nhưng nếu dùng **Thuật toán Bottom-Up của Floyd** (`buildHeap` chạy từ $n/2 - 1$ lùi về $0$): Thời gian chỉ là **$\Theta(n)$ (Tuyến tính)**! Trong đề thi, nếu hỏi chi phí build heap thì mặc định hiểu là thuật toán tối ưu Floyd $\implies \Theta(n)$.

---

### ⚠️ Bẫy 8: Thuật toán Dijkstra trên Đồ thị có Trọng số Âm
* **Cạm bẫy:** *"Cho đồ thị có hướng chứa 1 cạnh mang trọng số âm nhưng không có chu trình âm. Ta có thể dùng Dijkstra để tìm đường đi ngắn nhất không?"*
* **Sự thật chuẩn xác:** **TUYỆT ĐỐI KHÔNG!** Thuật toán Dijkstra được xây dựng trên tiên đề tham lam: một đỉnh đã lấy ra khỏi Priority Queue thì khoảng cách tới nó là tối ưu vĩnh viễn và không bao giờ cập nhật lại. Khi có cạnh âm, khoảng cách tới đỉnh đã chốt có thể bị rút ngắn tiếp $\implies$ Dijkstra cho kết quả SAI HOÀN TOÀN. Bắt buộc phải dùng **Bellman-Ford**!

---

### ⚠️ Bẫy 9: Phát hiện Chu trình bằng Thuật toán DFS
* **Cạm bẫy:** Đề thi cho danh sách các cung duyệt được từ DFS và hỏi đồ thị có hướng có chu trình hay không. Sinh viên thấy có cung đi tới đỉnh đã duyệt thì kết luận có chu trình.
* **Sự thật chuẩn xác:** Trong đồ thị có hướng, chỉ duy nhất **Cung Ngược (Back Edge - cung đi tới đỉnh màu XÁM đang trên Call Stack)** mới chứng minh sự tồn tại của chu trình! Các cung đi tới đỉnh màu ĐEN (**Forward Edge** hoặc **Cross Edge**) hoàn toàn KHÔNG TẠO NÊN CHU TRÌNH.

---

### ⚠️ Bẫy 10: Vị trí Vòng lặp $k$ trong Thuật toán Floyd-Warshall
* **Cạm bẫy:** Khi viết code Floyd-Warshall, sinh viên đặt vòng lặp $k$ ở trong cùng:
  `for (i...) for (j...) for (k...) dist[i][j] = min(dist[i][j], dist[i][k] + dist[k][j]);`
* **Sự thật chuẩn xác:** **SAI BẢN CHẤT QUY HOẠCH ĐỘNG!** Biến $k$ đại diện cho tập các đỉnh trung gian được phép sử dụng $\{1, \dots, k\}$. Do đó, **vòng lặp $k$ BẮT BUỘC PHẢI LÀ VÒNG LẶP NGOÀI CÙNG NHẤT**! Nếu đặt $k$ ở trong cùng, thuật toán sẽ bỏ sót các đường đi nhiều chặng.

---

### ⚠️ Bẫy 11: Thứ tự Điều kiện Dừng trong Tìm kiếm Nhị phân
* **Cạm bẫy:** Viết vòng lặp `while (low < high)` thay vì `while (low <= high)`.
* **Sự thật chuẩn xác:** Khi mảng chỉ còn đúng 1 phần tử ($low == high$), nếu viết `low < high`, vòng lặp sẽ thoát trước khi kiểm tra phần tử cuối cùng này $\implies$ Bỏ sót không tìm thấy phần tử nếu nó nằm đúng tại vị trí đó!

---

### ⚠️ Bẫy 12: Nhầm lẫn giữa Chu trình Đơn và Đồ thị Hai phía
* **Cạm bẫy:** Đề thi hỏi: *"Đồ thị chứa chu trình thì có phải là đồ thị hai phía không?"*
* **Sự thật chuẩn xác:** Theo Định lý Kőnig, đồ thị là hai phía khi và chỉ khi **không chứa chu trình độ dài LẺ**! Nếu đồ thị chứa chu trình độ dài CHẴN (ví dụ: chu trình 4 đỉnh $C_4$), nó **VẪN LÀ ĐỒ THỊ HAI PHÍA**!

---

### ⚠️ Bẫy 13: Destructor Ảo (`virtual ~Base()`) trong Kế thừa C++
* **Cạm bẫy:** Cho đoạn mã giải phóng con trỏ lớp cơ sở: `Base* p = new Derived(); delete p;`. Đề hỏi hàm hủy nào được thực thi nếu `Base` không khai báo destructor là `virtual`.
* **Sự thật chuẩn xác:** Trình biên dịch C++ chỉ thực hiện liên kết tĩnh dựa trên kiểu con trỏ `Base*` $\implies$ **Chỉ có destructor của `Base` được gọi!** Toàn bộ vùng nhớ động do lớp con `Derived` cấp phát sẽ bị rò rỉ vĩnh viễn trên Heap. Để cả hai destructor cùng được gọi đúng thứ tự (Derived trước, Base sau), destructor của `Base` bắt buộc phải có từ khóa `virtual`!

---

### ⚠️ Bẫy 14: Điều kiện Đầy của Hàng đợi Vòng (Circular Queue)
* **Cạm bẫy:** Nhầm lẫn công thức hàng đợi đầy khi dùng chiến lược bỏ trống 1 ô nhớ.
* **Sự thật chuẩn xác:**
  - Hàng đợi RỖNG: $\text{front} == \text{rear}$.
  - Hàng đợi ĐẦY: $(\text{rear} + 1) \bmod N == \text{front}$.
  - Số lượng phần tử hiện có: $(\text{rear} - \text{front} + N) \bmod N$.
  - Dung lượng lưu trữ tối đa của mảng kích thước $N$ chỉ là $N - 1$ phần tử!

---

### ⚠️ Bẫy 15: Xác định Phần tử Thế mạng khi Xóa Nút 2 Con trên Cây BST
* **Cạm bẫy:** Đề bài yêu cầu: *"Xóa nút $X$ có đủ 2 con, tìm nút thay thế theo quy ước Inorder Successor (hoặc Inorder Predecessor)."*
* **Sự thật chuẩn xác:**
  - **Inorder Successor (Phần tử kế vị):** Đi sang cây con PHẢI đúng 1 bước, sau đó đi hết về phía cực TRÁI (`root->right`, sau đó `while (curr->left) curr = curr->left`). Đây là nút có giá trị nhỏ nhất trong cây con bên phải!
  - **Inorder Predecessor (Phần tử tiền nhiệm):** Đi sang cây con TRÁI đúng 1 bước, sau đó đi hết về phía cực PHẢI (`root->left`, sau đó `while (curr->right) curr = curr->right`). Đây là nút có giá trị lớn nhất trong cây con bên trái!

---

### ⚠️ Bẫy 16: Bậc của Cây B và Số Khóa Tối thiểu
* **Cạm bẫy:** Cho Cây B bậc $M = 5$. Hỏi một nút nội bộ (không phải gốc) có thể chứa tối thiểu bao nhiêu khóa?
* **Sự thật chuẩn xác:**
  - Bậc $M = 5 \implies$ Số con tối đa là $M = 5$, số con tối thiểu của nút không phải gốc là $\lceil M/2 \rceil = \lceil 5/2 \rceil = 3$ con.
  - Một nút có $k$ con thì chứa đúng $k - 1$ khóa.
  - Do đó: Số khóa tối thiểu là $\lceil M/2 \rceil - 1 = 3 - 1 = \mathbf{2}$ khóa! Số khóa tối đa là $M - 1 = \mathbf{4}$ khóa! Sinh viên hay nhầm số con với số khóa.

---

> **LỜI KẾT & CHIẾN LƯỢC PHÒNG THI:**
> 1. Khi làm bài tự luận duyệt đồ thị (DFS, BFS, Dijkstra, Prim), hãy luôn **chú ý thứ tự ưu tiên từ điển (Alphabetical / Numerical Order)** khi có nhiều đỉnh kề nhau cùng mức ưu tiên để bài làm khớp hoàn toàn với đáp án của giảng viên.
> 2. Khi vẽ cây AVL sau phép quay, hãy luôn kiểm tra lại 2 tiêu chí: (1) Tính chất BST có bị vi phạm không? (2) Hệ số cân bằng của tất cả các nút có thực sự $\in \{-1, 0, 1\}$ hay chưa?
> 3. Nắm chắc bảng ma trận độ phức tạp tiệm cận để trả lời các câu hỏi lý thuyết trắc nghiệm trong vòng dưới 30 giây!
> 
> *Chúc các bạn sinh viên Khoa KH&KT Máy tính - Trường Đại học Bách Khoa ĐHQG-HCM ôn tập xuất sắc và đạt điểm tối đa trong kỳ thi Cuối kỳ môn Cấu trúc Dữ liệu & Giải thuật!*
