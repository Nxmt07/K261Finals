# 📋 BẢNG KIỂM TIẾN ĐỘ ÔN TẬP VÀ CHECKLIST THI CUỐI KỲ HK261
## K261 FINALS REVISION TRACKER & READINESS CHECKLIST

> **Kho lưu trữ:** `c:\Users\Admin\Documents\K261\Finals`  
> **Tài liệu chủ:** [README.md - Cổng thông tin trung tâm](file:///c:/Users/Admin/Documents/K261/Finals/README.md)  
> **Hướng dẫn sử dụng:** Đánh dấu `[x]` vào các ô tương ứng sau khi đã hoàn thành ôn tập lý thuyết, giải bài tập và làm đề thi thử của từng môn.

---

## 🎯 1. CHECKLIST THEO TỪNG MÔN HỌC (SUBJECT-BY-SUBJECT MASTERY)

### 📘 Môn 1: Cấu trúc Dữ liệu & Giải thuật (DSA - CO2003)
*Tài liệu chi tiết:* [DSA/README.md](file:///c:/Users/Admin/Documents/K261/Finals/DSA/README.md)

- [ ] **Chương 1: Ôn tập C++ & Phân tích độ phức tạp**
  - [ ] Con trỏ, cấp phát động `new`/`delete`, tránh memory leak.
  - [ ] OOP C++: Con trỏ `this`, Virtual functions, Abstract class, Template.
  - [ ] Phân tích độ phức tạp thời gian & không gian ($O, \Omega, \Theta$).
  - [ ] Giải hệ thức truy hồi bằng Định lý Thợ (Master Theorem) và cây đệ quy.
- [ ] **Chương 2: Danh sách tuyến tính, Ngăn xếp & Hàng đợi**
  - [ ] `ArrayList`: Chiến lược mở rộng dung lượng gấp đôi (Capacity Doubling).
  - [ ] `SLinkedList` & `DLinkedList`: Thao tác thêm/xóa đầu, cuối, giữa danh sách ($O(1)$ vs $O(n)$).
  - [ ] Đảo ngược danh sách liên kết đơn không dùng mảng phụ.
  - [ ] Cài đặt `Stack` & `Queue` bằng danh sách liên kết và mảng vòng (Circular Queue).
  - [ ] Ứng dụng Stack: Kiểm tra ngoặc hợp lệ, chuyển đổi biểu thức Infix sang Postfix.
- [ ] **Chương 3: Thuật toán sắp xếp (Sorting)**
  - [ ] Insertion Sort, Selection Sort, Bubble Sort (Phân tích ổn định & tại chỗ).
  - [ ] Shell Sort: Ý nghĩa bước nhảy khoảng cách (gap sequences).
  - [ ] Merge Sort: Thuật toán chia để trị, hàm `merge()`, độ phức tạp $O(n \log n)$.
  - [ ] Quick Sort: Thuật toán phân hoạch Kruse & Ryba (`too_big_index`, `too_small_index`), chọn pivot.
- [ ] **Chương 4: Bảng băm (Hashing)**
  - [ ] Các hàm băm phổ biến (Modulo, Mid-square, Folding).
  - [ ] Địa chỉ mở (Open Addressing): Linear probing, Quadratic probing, Double hashing.
  - [ ] Nối kết riêng biệt (Separate Chaining).
  - [ ] Cơ chế tái băm (Rehashing) khi hệ số tải $\alpha > \alpha_{\text{threshold}}$.
- [ ] **Chương 5: Cây (Trees) & Cây tìm kiếm cân bằng**
  - [ ] Cây nhị phân (Binary Tree): Duyệt tiền thứ tự (Preorder), trung thứ tự (Inorder), hậu thứ tự (Postorder).
  - [ ] Cây tìm kiếm nhị phân (BST): Thao tác chèn, tìm kiếm, xóa nút có 2 con.
  - [ ] Cây AVL: Tính hệ số cân bằng $BF$, thực hiện 4 phép xoay (LL, RR, LR, RL).
  - [ ] Cây Splay: Kỹ thuật đẩy phần tử lên gốc (Zig, Zig-Zig, Zig-Zag).
  - [ ] Cây B-Tree: Khái niệm bậc $M$, quy tắc tràn nút (Split) và thiếu nút (Merge/Borrow).
- [ ] **Chương 6: Hàng đợi ưu tiên & Đống nhị phân (Heap)**
  - [ ] Cấu trúc Min-Heap và Max-Heap lưu trữ trên mảng.
  - [ ] Thao tác `heapifyUp` (khi push) và `heapifyDown` (khi pop).
  - [ ] Thuật toán Heap Sort và xây dựng Heap trong thời gian $O(n)$.
- [ ] **Chương 7: Lý thuyết đồ thị (Graph Algorithms)**
  - [ ] Biểu diễn đồ thị: Ma trận kề vs Danh sách kề.
  - [ ] Thuật toán duyệt đồ thị BFS & DFS (Dùng Queue / Stack đệ quy).
  - [ ] Sắp xếp tô-pô (Topological Sort) cho đồ thị DAG.
  - [ ] Tìm đường đi ngắn nhất: Thuật toán Dijkstra ($O((V+E)\log V)$), Bellman-Ford (xử lý trọng số âm).
  - [ ] Cây khung nhỏ nhất (MST): Thuật toán Prim và Kruskal (sử dụng Disjoint Set Union - DSU).

---

### 💻 Môn 2: Kiến trúc Máy tính (KTMT - CO2007)
*Tài liệu chi tiết:* [KTMT/README.md](file:///c:/Users/Admin/Documents/K261/Finals/KTMT/README.md)

- [ ] **Nền tảng & Tập lệnh MIPS ISA**
  - [ ] Công thức tính CPU Time, Clock Cycles, CPI và Định luật Amdahl.
  - [ ] Định dạng lệnh MIPS: R-type, I-type, J-type (Phân tách opcode, rs, rt, rd, shamt, funct, imm).
  - [ ] Quy ước thanh ghi: `$zero`, `$v0-$v1`, `$a0-$a3`, `$t0-$t9`, `$s0-$s7`, `$sp`, `$ra`.
  - [ ] Dịch các đoạn mã rẽ nhánh (`beq`, `bne`, `slt`) và vòng lặp sang Hợp ngữ MIPS.
- [ ] **Số học máy tính (Computer Arithmetic)**
  - [ ] Biểu diễn số bù 2, phép cộng/trừ và điều kiện phát hiện tràn số (Overflow).
  - [ ] Thuật toán nhân Booth (Booth's Algorithm) cho số có dấu.
  - [ ] Thuật toán chia số nguyên (Restoring vs Non-restoring division).
  - [ ] Chuẩn số thực dấu chấm động IEEE 754 (Đơn 32-bit & Đôi 64-bit): Chuyển đổi qua lại giữa số thực và mã Hex.
  - [ ] Các trường hợp đặc biệt IEEE 754: Zero, Denormalized numbers, Infinity, NaN.
- [ ] **Bộ xử lý & Đường dẫn dữ liệu (Processor Datapath & Control)**
  - [ ] Datapath đơn chu kỳ (Single-Cycle): Các khối ALU, PC, Instruction Memory, Data Memory, Register File.
  - [ ] Bảng tín hiệu điều khiển: `RegDst`, `ALUSrc`, `MemtoReg`, `RegWrite`, `MemRead`, `MemWrite`, `Branch`, `ALUOp`.
  - [ ] Giới hạn của đơn chu kỳ và nguyên lý Datapath đa chu kỳ (Multi-Cycle).
- [ ] **Kỹ thuật đường ống (Pipelining) & Xử lý xung đột (Hazards)**
  - [ ] 5 tầng pipeline chuẩn: IF (Nhận lệnh), ID (Giải mã), EX (Thực thi), MEM (Bộ nhớ), WB (Ghi lại).
  - [ ] Xung đột cấu trúc (Structural Hazards) & giải pháp tách biệt Instruction/Data Memory.
  - [ ] Xung đột dữ liệu (Data Hazards) & Kỹ thuật chuyển tiếp dữ liệu (Forwarding/Bypassing).
  - [ ] Load-Use Hazard: Điều kiện phát hiện và chèn chu kỳ stall (nops).
  - [ ] Xung đột điều khiển (Control Hazards): Branch prediction (Static vs Dynamic 1-bit, 2-bit saturating counter).
- [ ] **Hệ thống nhớ phân tầng & Bộ nhớ Cache (Memory Hierarchy)**
  - [ ] 3 phương pháp ánh xạ Cache: Direct Mapped, N-Way Set Associative, Fully Associative.
  - [ ] Phân tích trường địa chỉ: Tag, Index, Offset.
  - [ ] Chính sách ghi: Write-Through vs Write-Back, Write-Allocate vs No-Write-Allocate.
  - [ ] Tính toán hiệu năng bộ nhớ: Miss penalty, AMAT (Average Memory Access Time).
  - [ ] Bộ nhớ ảo (Virtual Memory), Bảng phân trang (Page Table), và Bộ đệm TLB (Translation Lookaside Buffer).

---

### 📐 Môn 3: Mô hình hóa Toán học (MHH - CO2011 / DM2)
*Tài liệu chi tiết:* [MHH/README.md](file:///c:/Users/Admin/Documents/K261/Finals/MHH/README.md)

- [ ] **Chuyên đề 1: Lý thuyết Automata & Ngôn ngữ hình thức**
  - [ ] Phân cấp Chomsky, Văn phạm phi ngữ cảnh (CFG) và Ngôn ngữ chính quy.
  - [ ] Máy hữu hạn đơn định (DFA) và Máy hữu hạn không đơn định (NFA / $\varepsilon$-NFA).
  - [ ] Kỹ thuật đơn định hóa: Xây dựng tập con (Subset Construction algorithm).
  - [ ] Tối tiểu hóa DFA (DFA Minimization): Bảng phân biệt trạng thái tương đương (Hopcroft / Myhill-Nerode).
  - [ ] Chuyển đổi Automata sang Biểu thức chính quy (Regex) bằng Bổ đề Arden và GTG.
  - [ ] Bổ đề Bơm (Pumping Lemma) chứng minh một ngôn ngữ không phải là chính quy.
  - [ ] Ứng dụng Automata: Phân tích từ vựng (Lexical analyzer), kiểm chứng giao thức mạng, đèn giao thông.
- [ ] **Chuyên đề 2: Hệ động lực (Dynamical Systems)**
  - [ ] Hệ động lực thời gian rời rạc (DDS): Phương trình sai phân tuyến tính và phi tuyến.
  - [ ] Tìm điểm cân bằng $x^*$ và phân tích tính ổn định qua đạo hàm $|f'(x^*)|$.
  - [ ] Khảo sát chu kỳ và giản đồ Cobweb.
  - [ ] Hệ động lực liên tục: Hệ phương trình vi phân đạo hàm bậc nhất.
  - [ ] Tuyến tính hóa tại lân cận điểm dừng qua ma trận Jacobian $J(x^*, y^*)$.
  - [ ] Phân loại điểm cân bằng phẳng dựa trên $\text{Tr}(J)$ và $\det(J)$ (Node, Saddle, Spiral, Center).
  - [ ] Các mô hình kinh điển: Mô hình quần thể Logistic, Mô hình thú săn mồi Lotka-Volterra, Mô hình dịch bệnh SIR/SEIR.

---

### 🧪 Môn 4: Hóa học Đại cương (General Chemistry - CH1003)
*Tài liệu chi tiết:* [General Chemistry/README.md](file:///c:/Users/Admin/Documents/K261/Finals/General%20Chemistry/README.md)

- [ ] **Chuyên đề 1: Nhiệt động học hóa học**
  - [ ] Nguyên lý I nhiệt động học: $Q, A, \Delta U, \Delta H$.
  - [ ] Định luật Hess và các hệ quả: Tính $\Delta H^\circ$ phản ứng từ nhiệt tạo thành $\Delta H_f^\circ$ và nhiệt cháy $\Delta H_c^\circ$.
  - [ ] Nguyên lý II & III: Entropy $S$, biến thiên $\Delta S^\circ$.
  - [ ] Thế đẳng áp Gibbs: $\Delta G^\circ = \Delta H^\circ - T \Delta S^\circ$.
  - [ ] Xét chiều tự diễn biến của phản ứng theo nhiệt độ (Bảng dấu $\Delta H$ và $\Delta S$).
- [ ] **Chuyên đề 2: Động hóa học & Xúc tác**
  - [ ] Định luật tác dụng khối lượng, bậc phản ứng và hằng số tốc độ $k$.
  - [ ] Phương trình động học tích phân và chu kỳ bán hủy ($t_{1/2}$) cho phản ứng bậc 0, bậc 1, bậc 2.
  - [ ] Ảnh hưởng của nhiệt độ: Phương trình Arrhenius, tính năng lượng hoạt hóa $E_a$.
  - [ ] Cơ chế phản ứng, giai đoạn quyết định tốc độ và vai trò của chất xúc tác.
- [ ] **Chuyên đề 3: Cân bằng hóa học**
  - [ ] Biểu thức hằng số cân bằng $K_c, K_p, K_x$ và mối quan hệ $K_p = K_c(RT)^{\Delta n}$.
  - [ ] Mối liên hệ năng lượng tự do Gibbs và hằng số cân bằng: $\Delta G^\circ = -RT \ln K$.
  - [ ] Nguyên lý chuyển dịch cân bằng Le Chatelier (Ảnh hưởng của nhiệt độ, áp suất, nồng độ).
  - [ ] Phương trình Van't Hoff: Sự phụ thuộc của $K$ vào nhiệt độ.
- [ ] **Chuyên đề 4: Dung dịch & Cân bằng ion**
  - [ ] Thuyết Axit - Bazo Bronsted-Lowry, tính pH của dung dịch axit mạnh, axit yếu, bazo mạnh, bazo yếu.
  - [ ] Dung dịch đệm: Cơ chế hoạt động và công thức Henderson - Hasselbalch.
  - [ ] Phản ứng thủy phân của muối và tính pH tương ứng.
  - [ ] Cân bằng hòa tan: Tích số tan $K_{sp}$ ($T$), điều kiện kết tủa và hòa tan kết tủa.
  - [ ] Phản ứng tạo phức chất và hằng số bền $\beta$.
- [ ] **Chuyên đề 5: Điện hóa học & Pin Galvanic**
  - [ ] Phản ứng oxy hóa khử và cân bằng bằng phương pháp thăng bằng electron / ion-electron.
  - [ ] Dãy thế điện cực chuẩn và bảng thế khử chuẩn $E^\circ$.
  - [ ] Phương trình Nernst tính thế điện cực ở điều kiện bất kỳ.
  - [ ] Sơ đồ pin điện hóa Galvanic, phản ứng điện cực Catot (+), Anot (-), và sức điện động $E_{\text{pin}}$.
  - [ ] Mối liên hệ: $\Delta G^\circ = -nFE^\circ = -RT \ln K$.
  - [ ] Định luật Faraday về điện phân ($m = \frac{A \cdot I \cdot t}{n \cdot F}$).

---

### 📕 Môn 5: Triết học Mác - Lênin (MarxLenin - SP1031)
*Tài liệu chi tiết:* [MarxLenin/README.md](file:///c:/Users/Admin/Documents/K261/Finals/MarxLenin/README.md)

- [ ] **Chương 1: Triết học & Vai trò trong đời sống xã hội**
  - [ ] Khái niệm triết học, nguồn gốc nhận thức và nguồn gốc xã hội của triết học.
  - [ ] Vấn đề cơ bản của triết học: 2 mặt (Mặt bản thể luận & Mặt nhận thức luận).
  - [ ] Phân biệt Chủ nghĩa duy vật (Chất phác, Siêu hình, Biện chứng) vs Chủ nghĩa duy tâm (Chủ quan, Khách quan).
  - [ ] Thuyết Khả tri (Gnosticism) vs Thuyết Bất khả tri (Agnosticism).
  - [ ] Tiền đề kinh tế - xã hội, khoa học tự nhiên và lý luận dẫn đến sự ra đời Triết học Mác.
- [ ] **Chương 2: Chủ nghĩa duy vật biện chứng (CNDVBC)**
  - [ ] Định nghĩa kinh điển về Vật chất của V.I. Lênin và ý nghĩa phương pháp luận.
  - [ ] Nguồn gốc, bản chất và kết cấu của Ý thức; Mối quan hệ biện chứng giữa Vật chất và Ý thức.
  - [ ] 2 Nguyên lý của PBCDV: Nguyên lý về mối liên hệ phổ biến và Nguyên lý về sự phát triển.
  - [ ] 3 Quy luật cơ bản của PBCDV:
    - [ ] Quy luật Lượng - Chất (Độ, Điểm nút, Bước nhảy).
    - [ ] Quy luật Mâu thuẫn (Mặt đối lập, Thống nhất, Đấu tranh).
    - [ ] Quy luật Phủ định của phủ định (Phủ định biện chứng, Đường xoáy ốc).
  - [ ] 6 Cặp phạm trù biện chứng: Cái riêng - Cái chung, Nguyên nhân - Kết quả, Tất nhiên - Ngẫu nhiên, Nội dung - Hình thức, Bản chất - Hiện tượng, Khả năng - Hiện thực.
  - [ ] Lý luận nhận thức: Thực tiễn là gì? Vai trò của thực tiễn đối với nhận thức (Cơ sở, Động lực, Mục đích, Tiêu chuẩn chân lý).
  - [ ] Hai giai đoạn của quá trình nhận thức: Nhận thức cảm tính và Nhận thức lý tính.
- [ ] **Chương 3: Chủ nghĩa duy vật lịch sử (CNDVLS)**
  - [ ] Phương thức sản xuất: Quan hệ biện chứng giữa Lực lượng sản xuất và Quan hệ sản xuất.
  - [ ] Quy luật quan hệ sản xuất phù hợp với trình độ phát triển của lực lượng sản xuất.
  - [ ] Biện chứng giữa Cơ sở hạ tầng (kinh tế) và Kiến trúc thượng tầng (chính trị, pháp luật, tư tưởng).
  - [ ] Học thuyết hình thái kinh tế - xã hội và tiến trình lịch sử - tự nhiên.
  - [ ] Giai cấp, đấu tranh giai cấp, dân tộc và mối quan hệ giai cấp - dân tộc.
  - [ ] Nguồn gốc, bản chất và chức năng của Nhà nước; Cách mạng xã hội.
  - [ ] Mối quan hệ giữa Tồn tại xã hội và Ý thức xã hội (Tính độc lập tương đối của ý thức xã hội).
  - [ ] Quan điểm triết học Mác về con người: Bản chất con người là tổng hòa các quan hệ xã hội.

---

## 🧰 2. CHECKLIST ĐỒ DÙNG & QUY CHẾ PHÒNG THI (EXAM DAY CHECKLIST)

- [ ] **Giấy tờ tùy thân bắt buộc:**
  - [ ] Thẻ sinh viên (còn hạn, rõ ảnh và mã số sinh viên).
  - [ ] Căn cước công dân (CCCD) / Hộ chiếu (phòng trường hợp thất lạc thẻ sinh viên).
- [ ] **Dụng cụ học tập & tính toán:**
  - [ ] Bút viết cùng màu mực (xanh hoặc đen), bút chì 2B để tô phiếu trắc nghiệm, gôm tẩy.
  - [ ] Thước kẻ thẳng, compa (cho vẽ đồ thị, hình học, automata).
  - [ ] Máy tính cầm tay Casio fx-580VN X / fx-880BTG (kiểm tra pin, không có nắp dán tài liệu trái phép).
- [ ] **Chiến lược phân bổ thời gian trong phòng thi:**
  - [ ] 5 phút đầu: Đọc lướt toàn bộ đề thi, phân loại câu dễ làm trước để lấy trọn điểm số.
  - [ ] Kiểm tra kỹ các câu hỏi "bẫy" (đơn vị đo, số có dấu/không dấu, hệ số cân bằng, câu phủ định).
  - [ ] Dành ít nhất 10 phút cuối giờ để rà soát toàn bộ bài thi, kiểm tra mã đề và số báo danh đã tô.

---
*Cập nhật trạng thái liên tục để duy trì nhịp độ ôn thi đỉnh cao!*
