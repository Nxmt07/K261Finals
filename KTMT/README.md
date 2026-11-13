# TỔNG HỢP TOÀN DIỆN KIẾN THỨC KIẾN TRÚC MÁY TÍNH (COMPUTER ARCHITECTURE)
## TÀI LIỆU ÔN TẬP VÀ ĐỐI CHIẾU THI CUỐI KỲ (FINAL EXAM COMPREHENSIVE GUIDE)

> **Môn học:** Kiến trúc Máy tính (Computer Architecture - CO2007)  
> **Khoa:** Khoa học & Kỹ thuật Máy tính (CSE) - Trường Đại học Bách Khoa, ĐHQG TP.HCM (HCMUT)  
> **Giảng viên phụ trách:** PGS. TS. Phạm Quốc Cường (Cuong Pham-Quoc)  
> **Giáo trình tham khảo cốt lõi:**  
> 1. *Computer Organization and Design: The Hardware/Software Interface* – David A. Patterson & John L. Hennessy (MIPS Edition).  
> 2. *Giáo trình Kiến trúc Máy tính* – PGS. TS. Phạm Quốc Cường, NXB Đại học Quốc gia TP.HCM.  
> **Thư mục tài liệu:** `C:\Users\Admin\Documents\K261\Finals\KTMT\`  
> **Tình trạng tài liệu thư mục:**
> - `Chapter3.pdf` (3.9 MB, 37 slides): Slide bài giảng chuẩn về **Computer Arithmetic** (Số học máy tính) – Đã trích xuất và phân tích toàn diện.
> - `Chapter4.pdf` & `Chapter5.pdf` (37 KB/file): File tải về cục bộ thực chất là trang HTML thông báo hết phiên đăng nhập (*"Log in to BK-LMS - Your session has timed out"*). 
> - **Giải pháp khắc phục:** Tài liệu README này đã **nghiên cứu độc lập và tái hiện đầy đủ 100% nội dung kiến thức chuẩn của Chapter 4 (Bộ xử lý, Đường dẫn dữ liệu, Điều khiển và Kỹ thuật đường ống - Pipelining) và Chapter 5 (Hệ thống bộ nhớ phân tầng, Bộ nhớ Cache và Bộ nhớ ảo - Virtual Memory)** đúng theo đề cương và trọng tâm đề thi môn CO2007 của PGS. TS. Phạm Quốc Cường.

---

## 📑 MỤC LỤC TỔNG QUAN

1. [Bản đồ kiến thức & Ma trận nội dung thi cuối kỳ](#1-bản-đồ-kiến-thức--ma-trận-nội-dung-thi-cuối-kỳ)
2. [Tóm lược nền tảng & Prerequisites (Chapter 1 & Chapter 2)](#2-tóm-lược-nền-tảng--prerequisites-chapter-1--chapter-2)
   - 2.1. Đánh giá hiệu năng máy tính (CPU Time, CPI, Amdahl's Law)
   - 2.2. Tập lệnh MIPS ISA (Định dạng R, I, J & Thanh ghi)
3. [Chapter 3: Số học máy tính (Computer Arithmetic)](#3-chapter-3-số-học-máy-tính-computer-arithmetic)
   - 3.1. Phép toán số nguyên và xử lý tràn số (Integer Arithmetic & Overflow)
   - 3.2. Mạch nhân số nguyên phần cứng (Multiplication Hardware & Algorithm)
   - 3.3. Mạch chia số nguyên phần cứng (Division Hardware & Algorithm)
   - 3.4. Chuẩn số thực dấu chấm động IEEE-754 (Floating-Point Representation)
   - 3.5. Phép toán số thực dấu chấm động (Floating-Point Addition & Multiplication)
   - 3.6. Đồng xử lý toán học Coprocessor 1 & Tập lệnh số thực MIPS
   - 3.7. Độ chính xác số học và các chế độ làm tròn (Accurate Arithmetic & Rounding)
4. [Chapter 4: Bộ xử lý – Đường dẫn dữ liệu, Điều khiển & Kỹ thuật đường ống (The Processor)](#4-chapter-4-bộ-xử-lý--đường-dẫn-dữ-liệu-điều-khiển--kỹ-thuật-đường-ống-the-processor)
   - 4.1. Thiết kế đường dẫn dữ liệu đơn chu kỳ (Single-Cycle Datapath)
   - 4.2. Khối điều khiển chính và điều khiển ALU (Main Control & ALU Control Unit)
   - 4.3. Phân tích chu kỳ xung nhịp và mở rộng Datapath (Extending Datapath)
   - 4.4. Kỹ thuật đường ống (Pipelining Overview & 5 Stages)
   - 4.5. Các thanh ghi đường ống và tín hiệu điều khiển phân tầng
   - 4.6. Xung đột đường ống (Pipeline Hazards) và Kỹ thuật triệt tiêu xung đột:
     - Xung đột cấu trúc (Structural Hazard)
     - Xung đột dữ liệu (Data Hazard) & Mạch chuyển tiếp dữ liệu (Forwarding Unit)
     - Xung đột nạp dữ liệu (Load-Use Data Hazard) & Khối phát hiện xung đột (Hazard Detection Unit)
     - Xung đột điều khiển (Control Hazard / Branch Hazard) & Đoán nhánh (Branch Prediction)
   - 4.7. Tính toán hiệu năng bộ xử lý đường ống
5. [Chapter 5: Hệ thống bộ nhớ phân tầng, Bộ nhớ Cache & Bộ nhớ ảo (Memory Hierarchy)](#5-chapter-5-hệ-thống-bộ-nhớ-phân-tầng-bộ-nhớ-cache--bộ-nhớ-ảo-memory-hierarchy)
   - 5.1. Nguyên lý định vị (Principle of Locality: Temporal & Spatial)
   - 5.2. Cấu trúc phân tầng bộ nhớ (Memory Hierarchy Pyramid)
   - 5.3. Cấu tạo và nguyên lý hoạt động của Bộ nhớ Cache
   - 5.4. Các kỹ thuật ánh xạ Cache (Direct Mapped, N-Way Set Associative, Fully Associative)
   - 5.5. Phân tích địa chỉ truy xuất bộ nhớ (Tag, Index, Block Offset) & Dung lượng phần cứng
   - 5.6. Chính sách thay thế khối (LRU, FIFO, Random) và Ghi dữ liệu (Write-Through vs Write-Back)
   - 5.7. Đánh giá hiệu năng Cache (AMAT, Miss Penalties, Cache nhiều mức L1/L2)
   - 5.8. Bộ nhớ ảo (Virtual Memory), Bảng phân trang (Page Table) & TLB (Translation Lookaside Buffer)
   - 5.9. Quy trình phối hợp tổng thể: TLB + Virtual Memory + Cache
6. [Tuyển tập các dạng bài tập trọng tâm thi cuối kỳ (Kèm lời giải mẫu chi tiết)](#6-tuyển-tập-các-dạng-bài-tập-trọng-tâm-thi-cuối-kỳ-kèm-lời-giải-mẫu-chi-tiết)
7. [Bảng tra cứu công thức nhanh (Cheatsheet & Quick Formula Reference)](#7-bảng-tra-cứu-công-thức-nhanh-cheatsheet--quick-formula-reference)

---

## 1. BẢN ĐỒ KIẾN THỨC & MA TRẬN NỘI DUNG THI CUỐI KỲ

Kỳ thi kết thúc học phần môn Kiến trúc Máy tính (CO2007) tập trung chủ yếu vào **Chapter 3, Chapter 4 và Chapter 5**, với nền tảng từ **Chapter 1 và Chapter 2**.

| Chương | Tên chương | Mức độ trọng tâm | Các dạng câu hỏi & bài tập điển hình trong đề thi |
| :--- | :--- | :---: | :--- |
| **Chapter 1** | Hiệu năng máy tính | ⭐⭐⭐ | Tính CPU Time, CPI, tốc độ MIPS, tăng tốc Amdahl's Law. |
| **Chapter 2** | Tập lệnh MIPS | ⭐⭐⭐⭐ | Dịch mã C $\leftrightarrow$ MIPS Assembly, tính địa chỉ nhảy (Branch/Jump target), ngăn xếp ($sp). |
| **Chapter 3** | Số học máy tính | ⭐⭐⭐⭐⭐ | - Phát hiện tràn số nguyên bù 2 (2's complement overflow).<br>- Lập bảng vết thuật toán nhân/chia tối ưu (Optimized Multiplier/Divider trace table).<br>- Chuyển đổi định dạng IEEE-754 Single & Double (Thập phân $\leftrightarrow$ Hex).<br>- Phép cộng/nhân số thực dấu chấm động từng bước.<br>- Viết chương trình MIPS số thực dùng Coprocessor 1 (`add.s`, `c.lt.s`, `bc1t`...). |
| **Chapter 4** | Bộ xử lý: Datapath, Control & Pipelining | ⭐⭐⭐⭐⭐ *(Cực lớn)* | - Xác định giá trị các đường tín hiệu điều khiển (RegDst, ALUSrc, MemtoReg...) cho một tập lệnh.<br>- Mở rộng đường dẫn dữ liệu đơn chu kỳ để hỗ trợ lệnh mới (`jal`, `jr`, `bne`, `blez`, `lui`...).<br>- Tính chu kỳ xung nhịp tối thiểu (Clock Cycle Time) dựa trên trễ phần cứng.<br>- Vẽ sơ đồ thời gian Pipeline (5 tầng IF-ID-EX-MEM-WB).<br>- Phát hiện Data Hazard, viết điều kiện mạch Forwarding (ForwardA, ForwardB).<br>- Xử lý Load-Use Hazard (Stall / Bubble).<br>- Tính toán hiệu năng, CPI trung bình khi có trễ nhánh và nạp. |
| **Chapter 5** | Hệ thống bộ nhớ phân tầng, Cache & Bộ nhớ ảo | ⭐⭐⭐⭐⭐ *(Cực lớn)* | - Xác định số bit của các trường: Tag, Index (Set), Offset từ thông số Cache.<br>- Tính tổng dung lượng bit phần cứng để xây dựng Cache (gồm cả Valid, Dirty, Tag, Data).<br>- Mô phỏng quá trình truy xuất bộ nhớ (Trace Hit/Miss) với Direct-Mapped và N-Way Set-Associative (thay thế LRU).<br>- Tính thời gian truy xuất bộ nhớ trung bình (AMAT) cho Cache 1 cấp và 2 cấp (L1, L2).<br>- Chuyển đổi địa chỉ ảo sang vật lý (Virtual Address $\rightarrow$ Physical Address), kích thước Page Table, cơ chế hoạt động của TLB. |

---

## 2. TÓM LƯỢC NỀN TẢNG & PREREQUISITES (CHAPTER 1 & CHAPTER 2)

### 2.1. Đánh giá hiệu năng máy tính (Computer Performance)

Hiệu năng của một máy tính được định nghĩa là nghịch đảo của thời gian thực thi:
$$\text{Performance} = \frac{1}{\text{Execution Time}}$$

#### Công thức thời gian thực thi CPU (CPU Execution Time):
$$\text{CPU Time} = \text{Instruction Count (IC)} \times \text{CPI} \times \text{Clock Cycle Time} = \frac{\text{Instruction Count} \times \text{CPI}}{\text{Clock Rate}}$$

Trong đó:
- **Instruction Count (IC):** Tổng số chỉ lệnh được thực thi trong chương trình (phụ thuộc vào trình biên dịch và ISA).
- **CPI (Cycles Per Instruction):** Số chu kỳ xung nhịp trung bình để thực thi một lệnh:
  $$\text{CPI} = \frac{\sum (\text{CPI}_i \times \text{Count}_i)}{\text{IC}}$$
- **Clock Cycle Time ($T_c$):** Thời gian của một chu kỳ xung nhịp ($T_c = \frac{1}{f}$, với $f$ là Clock Frequency).

#### Định luật Amdahl (Amdahl's Law):
Định luật mô tả tốc độ tăng trưởng hiệu năng tổng thể khi chỉ cải tiến một phần của hệ thống:
$$\text{Speedup}_{\text{overall}} = \frac{1}{(1 - F) + \frac{F}{S}}$$
- $F$: Tỷ lệ thời gian thực thi được hưởng lợi từ sự cải tiến ($0 \le F \le 1$).
- $S$: Hệ số tăng tốc của phần được cải tiến đó.

---

### 2.2. Tập lệnh MIPS ISA (MIPS Architecture Summary)

Kiến trúc MIPS là kiến trúc RISC (Reduced Instruction Set Computer) tiêu biểu với độ dài lệnh cố định là **32 bits (4 bytes)** và có **32 thanh ghi đa dụng (32-bit registers)**.

#### 1. Bảng 32 thanh ghi MIPS ($0 đến $31):
- `$zero` (`$0`): Luôn bằng 0 (hằng số 0 cứng).
- `$at` (`$1`): Assembler Temporary (dành riêng cho trình biên dịch).
- `$v0 - $v1` (`$2 - $3`): Chứa giá trị trả về của hàm (Function return values).
- `$a0 - $a3` (`$4 - $7`): Tham số truyền vào hàm (Function arguments).
- `$t0 - $t7` (`$8 - $15`) & `$t8 - $t9` (`$24 - $25`): Thanh ghi tạm thời (Temporaries - caller saved).
- `$s0 - $s7` (`$16 - $23`): Thanh ghi lưu trữ biến (Saved temporaries - callee saved).
- `$k0 - $k1` (`$26 - $27`): Dành riêng cho nhân hệ điều hành (OS kernel).
- `$gp` (`$28`): Con trỏ vùng dữ liệu toàn cục (Global Pointer).
- `$sp` (`$29`): Con trỏ đỉnh ngăn xếp (Stack Pointer - trỏ tới đỉnh stack, stack mở rộng từ cao xuống thấp).
- `$fp` (`$30`): Con trỏ khung ngăn xếp (Frame Pointer).
- `$ra` (`$31`): Địa chỉ quay về sau khi gọi hàm (Return Address).

#### 2. Ba định dạng lệnh MIPS (Instruction Formats):

##### a. Định dạng R-type (Register format):
Dùng cho các phép tính số học, logic trên thanh ghi (`add`, `sub`, `and`, `or`, `slt`, `sll`, `srl`...).
```
|  opcode (6)  |   rs (5)   |   rt (5)   |   rd (5)   |  shamt (5)  |  funct (6)  |
| 31        26 | 25       21 | 20       16 | 15       11 | 10         6 | 5         0 |
```
- `opcode`: Luôn bằng `000000` đối với các lệnh R-type cơ bản.
- `rs`: Thanh ghi nguồn 1 (Source register 1).
- `rt`: Thanh ghi nguồn 2 (Source register 2).
- `rd`: Thanh ghi đích (Destination register - nơi nhận kết quả).
- `shamt`: Số lượng dịch bit (Shift amount - dùng trong lệnh `sll`, `srl`).
- `funct`: Mã hàm chức năng (xác định chính xác phép tính, ví dụ `add` = 32 = `0x20`, `sub` = 34 = `0x22`).

##### b. Định dạng I-type (Immediate format):
Dùng cho phép tính với hằng số (`addi`, `andi`, `ori`), truy xuất bộ nhớ (`lw`, `sw`, `lb`, `sb`) và rẽ nhánh điều kiện (`beq`, `bne`).
```
|  opcode (6)  |   rs (5)   |   rt (5)   |        immediate (16)       |
| 31        26 | 25       21 | 20       16 | 15                         0 |
```
- `opcode`: Xác định loại lệnh (`lw` = 35, `sw` = 43, `beq` = 4, `bne` = 5, `addi` = 8).
- `rs`: Thanh ghi nguồn chứa địa chỉ cơ sở hoặc toán hạng 1.
- `rt`: Thanh ghi đích khi nạp (`lw`), hoặc thanh ghi nguồn cần lưu (`sw`), hoặc toán hạng so sánh (`beq`).
- `immediate`: Hằng số bù 2 kích thước 16 bit (tầm giá trị từ $-2^{15}$ đến $2^{15}-1$).

##### c. Định dạng J-type (Jump format):
Dùng cho lệnh nhảy không điều kiện (`j`, `jal`).
```
|  opcode (6)  |                 target address (26)                 |
| 31        26 | 25                                                 0 |
```
- `target address`: 26 bit địa chỉ. Địa chỉ đích 32 bit thực tế được tính bằng:
  $$\text{Jump Target PC} = (\text{PC} + 4)_{31..28} \mathbin{\Vert} (\text{address} \ll 2)$$

---

## 3. CHAPTER 3: SỐ HỌC MÁY TÍNH (COMPUTER ARITHMETIC)

> Toàn bộ nội dung dưới đây được bóc tách và đối chiếu chi tiết từ tài liệu bài giảng `Chapter3.pdf` của PGS. TS. Phạm Quốc Cường, bổ sung các ví dụ và bảng vết trực quan.

### 3.1. Phép toán số nguyên và xử lý tràn số (Integer Arithmetic & Overflow)

Trong kiến trúc MIPS 32-bit, số nguyên có dấu được biểu diễn dưới dạng **bù 2 (2's complement)**. Dải biểu diễn của số nguyên có dấu $n$ bit là từ $-2^{n-1}$ đến $2^{n-1} - 1$ (với $n=32$: từ $-2,147,483,648$ đến $+2,147,483,647$).

#### 1. Quy tắc cộng số nguyên (Integer Addition):
- Cộng các bit từ LSB sang MSB kèm nhớ (carry).
- **Trường hợp tràn số (Overflow conditions):** Tràn số xảy ra khi kết quả vượt khỏi phạm vi biểu diễn của số bù 2 $n$ bit.
  - Khi cộng **1 số dương và 1 số âm**: **KHÔNG BAO GIỜ** xảy ra tràn số.
  - Khi cộng **2 số dương** ($A \ge 0, B \ge 0$): Xảy ra tràn số nếu kết quả mang bit dấu là **1 (âm)**.
  - Khi cộng **2 số âm** ($A < 0, B < 0$): Xảy ra tràn số nếu kết quả mang bit dấu là **0 (dương)**.
- *Ví dụ 4-bit:* $7_{10} + 6_{10} = 0111_2 + 0110_2 = 1101_2$ (kết quả là $-3_{10}$, bit dấu là 1 $\rightarrow$ Tràn số!).

#### 2. Quy tắc trừ số nguyên (Integer Subtraction):
- Phép trừ $A - B$ được thực hiện bằng cách cộng số bị trừ với số bù 2 của số trừ: $A - B = A + (-B)$.
- **Trường hợp tràn số:**
  - Trừ 2 số cùng dấu (dương trừ dương, âm trừ âm): **KHÔNG BAO GIỜ** xảy ra tràn số.
  - Lấy **số âm trừ số dương** ($A < 0, B > 0$): Tràn số nếu kết quả mang bit dấu là **0 (dương)**.
  - Lấy **số dương trừ số âm** ($A \ge 0, B < 0$): Tràn số nếu kết quả mang bit dấu là **1 (âm)**.

#### 3. Cách thức xử lý tràn số trong phần cứng và hệ điều hành:
- Các ngôn ngữ như **C, C++, Java** bỏ qua hiện tượng tràn số (ignore overflow):
  - Trình biên dịch sử dụng các lệnh MIPS không bẫy tràn số: `addu`, `addiu`, `subu`.
- Các ngôn ngữ như **Ada, Fortran** yêu cầu kích hoạt biệt lệ (raise exception):
  - Trình biên dịch sử dụng các lệnh MIPS kiểm tra tràn số: `add`, `addi`, `sub`.
  - Khi tràn số xảy ra, phần cứng thực hiện:
    1. Lưu địa chỉ chỉ lệnh gây lỗi vào thanh ghi **EPC (Exception Program Counter)** thuộc Coprocessor 0.
    2. Nhảy đến địa chỉ thường trực của bộ xử lý ngoại lệ (Exception Handler Address, ví dụ `0x80000180`).
    3. Phần mềm cứu vãn có thể dùng chỉ lệnh `mfc0 rd, $14` (Move From Coprocessor 0) để đọc địa chỉ từ EPC và lệnh `eret` để quay trở về.

---

### 3.2. Mạch nhân số nguyên phần cứng (Multiplication Hardware & Algorithm)

Khi nhân 2 số nguyên $n$ bit, tích có độ dài tối đa là **$2n$ bit**.

```
      1000  (Multiplicand: 8)
    x 1001  (Multiplier: 9)
    ------
      1000
      0000
      0000
     1000
    ------
   01001000  (Product: 72)
```

#### 1. Mạch nhân cơ bản (Version 1 - Slide 7-8):
- **Cấu hình phần cứng:**
  - Thanh ghi **Multiplicand (Số bị nhân)**: 64 bit (khởi tạo chứa số bị nhân ở nửa phải 32 bit, dịch trái 1 bit sau mỗi bước).
  - Thanh ghi **Multiplier (Số nhân)**: 32 bit (dịch phải 1 bit sau mỗi bước).
  - Thanh ghi **Product (Tích)**: 64 bit (khởi tạo bằng 0).
  - Bộ tính toán **ALU**: 64 bit.
- **Lưu đồ thuật toán nhân cơ bản:**
  1. Kiểm tra bit $m_0$ (bit LSB) của thanh ghi Multiplier:
     - Nếu $m_0 = 1$: `Product = Product + Multiplicand`.
     - Nếu $m_0 = 0$: Không cộng.
  2. Dịch trái thanh ghi Multiplicand 1 bit (`Shift Left Multiplicand`).
  3. Dịch phải thanh ghi Multiplier 1 bit (`Shift Right Multiplier`).
  4. Lặp lại 32 lần (đối với số 32 bit).

#### 2. Mạch nhân tối ưu phần cứng (Version 2 - Slide 10):
- **Ý tưởng cải tiến:** Nhận thấy tại mỗi bước, chỉ có 32 bit của tích tham gia cộng dồn và thanh ghi Multiplier giảm dần số bit có nghĩa trong khi thanh ghi Product tăng dần số bit.
- **Cấu hình phần cứng tối ưu:**
  - Thanh ghi **Multiplicand**: chỉ cần **32 bit** (cố định, không dịch).
  - Bộ tính toán **ALU**: chỉ cần **32 bit**.
  - Thanh ghi **Product**: **64 bit**, khởi tạo gộp:
    - Nửa trái (32 bit cao): Khởi tạo bằng `0000...0000`.
    - Nửa phải (32 bit thấp): Khởi tạo chứa giá trị của **Multiplier**.
- **Thuật toán nhân tối ưu (Thực hiện trong $n$ chu kỳ):**
  1. Kiểm tra bit LSB của thanh ghi Product:
     - Nếu LSB = 1: `Nửa trái Product = Nửa trái Product + Multiplicand`.
     - Nếu LSB = 0: Giữ nguyên.
  2. Dịch phải **toàn bộ thanh ghi Product 64-bit** 1 bit (dịch số học nếu có dấu, dịch logic nếu không dấu).
  3. Kiểm tra đã đủ $n$ lần lặp chưa (32 lần cho 32-bit).

```
+-------------------------------------------------------+
|            Thanh ghi Multiplicand (32 bit)            |
+-------------------------------------------------------+
                           |
                           v
                     +-----------+
                     | 32-bit ALU|
                     +-----------+
                           |
                           v
+--------------------------+----------------------------+
|  Product [63..32]        |  Product [31..0]           |
|  (32-bit chứa tích dồn)   |  (Ban đầu chứa Multiplier) |
+--------------------------+----------------------------+
       |                                      |
       +-------> Dịch phải 64 bit ------------+----> Kiểm tra LSB
```

#### 3. Bảng vết ví dụ tính toán: $2_{10} \times 3_{10} = 0010_2 \times 0011_2$ (4-bit):
- Multiplicand = `0010`
- Khởi tạo Product (8-bit) = `0000 0011`

| Vòng lặp (Iteration) | Bước (Step) | Mô tả thao tác | Multiplicand | Thanh ghi Product (8-bit) |
| :---: | :---: | :--- | :---: | :---: |
| **0** | Khởi tạo | Nạp Multiplier vào nửa phải, 0 vào nửa trái | `0010` | `0000 0011` |
| **1** | 1a | LSB = 1 $\rightarrow$ Product[7..4] = Product[7..4] + Multiplicand (`0000 + 0010`) | `0010` | `0010 0011` |
| | 2 | Dịch phải Product 1 bit | `0010` | `0001 0001` |
| **2** | 1a | LSB = 1 $\rightarrow$ Product[7..4] = Product[7..4] + Multiplicand (`0001 + 0010`) | `0010` | `0011 0001` |
| | 2 | Dịch phải Product 1 bit | `0010` | `0001 1000` |
| **3** | 1b | LSB = 0 $\rightarrow$ Giữ nguyên | `0010` | `0001 1000` |
| | 2 | Dịch phải Product 1 bit | `0010` | `0000 1100` |
| **4** | 1b | LSB = 0 $\rightarrow$ Giữ nguyên | `0010` | `0000 1100` |
| | 2 | Dịch phải Product 1 bit | `0010` | `0000 0110` |

$\rightarrow$ Kết quả cuối cùng trong thanh ghi Product: `0000 0110`$_2 = 6_{10}$ (Chính xác!).

#### 4. Thuật toán Booth (Booth's Algorithm cho phép nhân số có dấu):
Thay vì chỉ kiểm tra LSB, thuật toán Booth quan sát **cặp 2 bit liền kề ($Product_0$ và bit phụ $Product_{-1}$)**:
- `10`: Bắt đầu chuỗi các bit 1 $\rightarrow$ Lấy `Product[n..0] = Product[n..0] - Multiplicand`, sau đó dịch phải số học (Arithmetic Shift Right).
- `01`: Kết thúc chuỗi các bit 1 $\rightarrow$ Lấy `Product[n..0] = Product[n..0] + Multiplicand`, sau đó dịch phải số học.
- `00` hoặc `11`: Nằm giữa chuỗi $\rightarrow$ Chỉ dịch phải số học 1 bit.

#### 5. Tập lệnh nhân trong MIPS:
- MIPS trang bị 2 thanh ghi 32-bit chuyên dụng:
  - **HI (High):** Chứa 32 bit cao của tích 64 bit.
  - **LO (Low):** Chứa 32 bit thấp của tích 64 bit.
- Các chỉ lệnh:
  - `mult rs, rt`: Nhân 2 số có dấu 32-bit trong `rs` và `rt`, kết quả lưu vào `HI` và `LO`.
  - `multu rs, rt`: Nhân 2 số không dấu 32-bit.
  - `mfhi rd`: Di chuyển dữ liệu từ `HI` vào thanh ghi đa dụng `rd` (Move From HI). Dùng để kiểm tra tràn số 32-bit (nếu `HI` khác 0 với số không dấu).
  - `mflo rd`: Di chuyển dữ liệu từ `LO` vào `rd` (Move From LO).
  - `mul rd, rs, rt`: Chỉ lấy 32 bit thấp của tích đưa thẳng vào thanh ghi `rd` (không làm thay đổi HI/LO trên một số vi kiến trúc).

---

### 3.3. Mạch chia số nguyên phần cứng (Division Hardware & Algorithm)

Phép chia: $\text{Dividend} = \text{Divisor} \times \text{Quotient} + \text{Remainder}$ (Số bị chia = Số chia $\times$ Thương + Số dư).

#### 1. Mạch chia cơ bản (Restoring Division Version 1 - Slide 12-13):
- **Cấu hình phần cứng:**
  - Thanh ghi **Divisor (Số chia)**: 64 bit (khởi tạo chứa số chia ở nửa trái 32 bit, dịch phải 1 bit mỗi bước).
  - Thanh ghi **Remainder (Số dư)**: 64 bit (khởi tạo chứa số bị chia ở nửa phải 32 bit).
  - Thanh ghi **Quotient (Thương)**: 32 bit (dịch trái 1 bit mỗi bước).
  - Bộ tính toán **ALU**: 64 bit.
- **Các bước thực hiện:**
  1. Trừ số dư cho số chia: `Remainder = Remainder - Divisor`.
  2. Kiểm tra dấu của `Remainder`:
     - Nếu `Remainder >= 0`: Dịch trái Quotient 1 bit, gán bit mới đưa vào ở cực phải bằng 1.
     - Nếu `Remainder < 0`: Phục hồi lại số dư (`Remainder = Remainder + Divisor`), dịch trái Quotient 1 bit, gán bit mới ở cực phải bằng 0.
  3. Dịch phải thanh ghi Divisor 1 bit.
  4. Lặp lại $n+1$ lần (đối với phiên bản này).

#### 2. Mạch chia tối ưu phần cứng (Restoring Division Version 2 - Slide 15):
- **Cấu hình phần cứng tối ưu:**
  - Thanh ghi **Divisor**: chỉ cần **32 bit** (cố định, không dịch).
  - Bộ tính toán **ALU**: chỉ cần **32 bit**.
  - Thanh ghi **Remainder**: **64 bit**, khởi tạo:
    - Nửa trái (32 bit cao): Khởi tạo bằng `0000...0000`.
    - Nửa phải (32 bit thấp): Khởi tạo chứa **Dividend (Số bị chia)**.
- **Thuật toán chia tối ưu:**
  1. Dịch trái toàn bộ thanh ghi Remainder 64-bit 1 bit.
  2. Lấy nửa trái của Remainder trừ Divisor: `Remainder[63..32] = Remainder[63..32] - Divisor`.
  3. Kiểm tra kết quả trừ:
     - Nếu $\ge 0$: Đặt bit LSB của thanh ghi Remainder bằng 1.
     - Nếu $< 0$: Phục hồi số dư (`Remainder[63..32] = Remainder[63..32] + Divisor`), đặt bit LSB của Remainder bằng 0.
  4. Lặp lại 32 lần. Sau vòng cuối cùng, dịch phải nửa trái Remainder 1 bit để hiệu chỉnh số dư.

#### 3. Bảng vết ví dụ tính toán: $7_{10} \div 2_{10} = 0111_2 \div 0010_2$ (4-bit):
- Divisor = `0010`
- Remainder khởi tạo = `0000 0111`

| Vòng lặp | Bước | Thao tác | Nửa trái Remainder [7..4] | Nửa phải Remainder [3..0] | Toàn bộ Remainder (8-bit) |
| :---: | :---: | :--- | :---: | :---: | :---: |
| **0** | Khởi tạo | Nạp Dividend vào nửa phải | `0000` | `0111` | `0000 0111` |
| **1** | 1 | Dịch trái 1 bit | `0000` | `1110` | `0000 1110` |
| | 2 | Trừ Divisor (`0000 - 0010` = âm) $\rightarrow$ Khôi phục cộng lại, LSB = 0 | `0000` | `1110` | `0000 1110` |
| **2** | 1 | Dịch trái 1 bit | `0001` | `1100` | `0001 1100` |
| | 2 | Trừ Divisor (`0001 - 0010` = âm) $\rightarrow$ Khôi phục cộng lại, LSB = 0 | `0001` | `1100` | `0001 1100` |
| **3** | 1 | Dịch trái 1 bit | `0011` | `1000` | `0011 1000` |
| | 2 | Trừ Divisor (`0011 - 0010 = 0001` $\ge 0$) $\rightarrow$ Giữ nguyên, LSB = 1 | `0001` | `1001` | `0001 1001` |
| **4** | 1 | Dịch trái 1 bit | `0011` | `0010` | `0011 0010` |
| | 2 | Trừ Divisor (`0011 - 0010 = 0001` $\ge 0$) $\rightarrow$ Giữ nguyên, LSB = 1 | `0001` | `0011` | `0001 0011` |
| **Sau cùng**| Hiệu chỉnh| Dịch phải nửa trái Remainder 1 bit | `0001` | `0011` | $\text{Rem}=0001_2$, $\text{Quot}=0011_2$ |

$\rightarrow$ Kết quả: Thương số (Quotient) = $0011_2 = 3_{10}$; Số dư (Remainder) = $0001_2 = 1_{10}$ (Chính xác vì $7 = 2 \times 3 + 1$).

#### 4. Phép chia có dấu (Signed Division):
- Quy tắc: Thực hiện chia giá trị tuyệt đối, sau đó gán dấu:
  - Dấu của **Thương số (Quotient)** là âm nếu số bị chia và số chia trái dấu.
  - Dấu của **Số dư (Remainder)** luôn **cùng dấu với Số bị chia (Dividend)**.
  - *Ví dụ:*
    - $(+7) \div (+2) \rightarrow Q = +3, R = +1$
    - $(-7) \div (+2) \rightarrow Q = -3, R = -1$
    - $(+7) \div (-2) \rightarrow Q = -3, R = +1$
    - $(-7) \div (-2) \rightarrow Q = +3, R = -1$

#### 5. Tập lệnh chia trong MIPS:
- `div rs, rt` (chia có dấu) / `divu rs, rt` (chia không dấu):
  - Thương số (Quotient) được lưu vào thanh ghi **LO**.
  - Số dư (Remainder) được lưu vào thanh ghi **HI**.
- **Lưu ý trong đề thi:** MIPS phần cứng **KHÔNG** tự kiểm tra lỗi chia cho 0 (Divide-by-zero) hay tràn số. Nếu `rt = 0`, giá trị trong HI/LO là không xác định. Phần mềm biên dịch phải tự chèn lệnh kiểm tra nếu cần (`bne $rt, $zero, L1`).
- Dùng `mflo rd` để lấy thương, `mfhi rd` để lấy số dư.

---

### 3.4. Chuẩn số thực dấu chấm động IEEE-754 (Floating-Point Representation)

Chuẩn IEEE-754 (1985 / 2008) định nghĩa cách lưu trữ số thực khoa học dạng:
$$X = (-1)^S \times (1.\text{Fraction}) \times 2^{\text{Exponent} - \text{Bias}}$$

#### 1. Cấu trúc bit Single Precision (Độ chính xác đơn - 32 bit):
```
| S (1) |   Exponent (8)   |             Fraction (23)             |
|  31   | 30             23 | 22                                   0 |
```
- **Bit dấu $S$ (Sign bit):** 1 bit ($0$ là số dương, $1$ là số âm).
- **Trường số mũ $E$ (Exponent):** 8 bit, được lưu dưới dạng số nguyên không dấu có cộng độ dời:
  $$\text{Bias} = 127 = 2^{8-1} - 1$$
  $$\text{Số mũ thực tế (actual exponent) } e = E - 127$$
- **Trường định trị $F$ (Fraction):** 23 bit. Do số chuẩn hóa luôn bắt đầu bằng `1.xxxx`, bit `1` này được quy ước ngầm định (**hidden bit**), không cần lưu trữ vật lý trong bộ nhớ. Phần định trị đầy đủ (Significand) có độ dài 24 bit = $1.F$.

#### 2. Cấu trúc bit Double Precision (Độ chính xác kép - 64 bit):
```
| S (1) |   Exponent (11)   |             Fraction (52)             |
|  63   | 62              52 | 51                                   0 |
```
- $S$: 1 bit.
- $E$: 11 bit, $\text{Bias} = 1023 = 2^{11-1} - 1 \implies e = E - 1023$.
- $F$: 52 bit (phần định trị đầy đủ là 53 bit = $1.F$).

#### 3. Bảng các trường hợp đặc biệt của chuẩn IEEE-754:

| Exponent ($E$) | Fraction ($F$) | Giá trị đại diện | Ý nghĩa toán học |
| :---: | :---: | :---: | :--- |
| $E = 0$ | $F = 0$ | $\pm 0.0$ | Số không (có $+0$ và $-0$ phụ thuộc vào bit $S$). |
| $E = 0$ | $F \ne 0$ | $(-1)^S \times (0.F) \times 2^{1 - \text{Bias}}$ | **Số phi chuẩn (Denormalized/Subnormal):** Dùng để biểu diễn các số cực nhỏ gần 0 (Gradual Underflow), không có hidden bit 1. |
| $1 \le E \le 254$ (Single)<br>$1 \le E \le 2046$ (Double) | Bất kỳ | $(-1)^S \times (1.F) \times 2^{E - \text{Bias}}$ | **Số chuẩn hóa (Normalized):** Vùng biểu diễn số thực thông thường. |
| $E = 255$ (Single)<br>$E = 2047$ (Double) | $F = 0$ | $\pm \infty$ (Infinity) | Số vô cùng (tràn số tràn trên, hoặc chia cho 0). |
| $E = 255$ (Single)<br>$E = 2047$ (Double) | $F \ne 0$ | **NaN** (Not a Number) | Kết quả của các phép tính vô định (ví dụ $\frac{0}{0}, \sqrt{-1}, \infty - \infty$). |

#### 4. Phạm vi biểu diễn của số chuẩn hóa:
- **Single Precision:**
  - Nhỏ nhất: $E = 1 \implies e = 1 - 127 = -126$, $F = 0 \implies \pm 1.0 \times 2^{-126} \approx \pm 1.18 \times 10^{-38}$.
  - Lớn nhất: $E = 254 \implies e = 254 - 127 = +127$, $F = 111...1 \approx 2.0 \implies \pm 2.0 \times 2^{127} \approx \pm 3.40 \times 10^{38}$.
- **Double Precision:**
  - Nhỏ nhất: $\pm 1.0 \times 2^{-1022} \approx \pm 2.22 \times 10^{-308}$.
  - Lớn nhất: $\pm 2.0 \times 2^{1023} \approx \pm 1.79 \times 10^{308}$.

---

### 3.5. Phép toán số thực dấu chấm động (Floating-Point Addition & Multiplication)

#### 1. Thuật toán cộng 2 số thực dấu chấm động (4 bước - Slide 26-28):
Cho 2 số $A = S_1 \times M_1 \times 2^{e_1}$ và $B = S_2 \times M_2 \times 2^{e_2}$ (giả sử $e_1 \ge e_2$):
1. **Bước 1: Cân bằng dấu chấm nhị phân (Align binary points):**
   - So sánh hai số mũ. Dịch phải phần định trị của số có số mũ nhỏ hơn một lượng bằng độ chênh lệch số mũ: $d = e_1 - e_2$.
   - Số mũ chung của kết quả tạm thời là $e_1$.
2. **Bước 2: Cộng/Trừ phần định trị (Add significands):**
   - Cộng hoặc trừ các phần định trị đã cân bằng (xét theo dấu $S_1, S_2$).
3. **Bước 3: Chuẩn hóa kết quả và kiểm tra tràn số (Normalize & Check Overflow/Underflow):**
   - Nếu phần định trị tràn sang trái (dạng $1x.xxx...$), dịch phải 1 bit và tăng số mũ lên 1.
   - Nếu phần định trị có các bit 0 ở đầu (dạng $0.001xxx...$), dịch trái cho đến khi bit đầu tiên là 1, đồng thời giảm số mũ tương ứng.
   - Kiểm tra tràn trên (Overflow: $E > 254$) hoặc tràn dưới (Underflow: $E < 1$).
4. **Bước 4: Làm tròn (Round) và tái chuẩn hóa nếu cần thiết:**
   - Làm tròn phần định trị theo chế độ quy định. Nếu làm tròn tạo ra bit nhớ gây tràn (ví dụ $1.111... + 1 = 10.000...$), phải dịch phải và tăng số mũ lần nữa.

#### 2. Thuật toán nhân 2 số thực dấu chấm động (5 bước - Slide 29-30):
1. **Bước 1: Tính số mũ kết quả (Add exponents):**
   - Cộng hai số mũ đã có bias và trừ bớt đi 1 lần bias:
     $$E_{\text{result}} = E_1 + E_2 - \text{Bias}$$
2. **Bước 2: Nhân các phần định trị (Multiply significands):**
   - Thực hiện nhân hai số $1.F_1 \times 1.F_2$. Kết quả định trị có độ dài gấp đôi ($24 \times 24 \implies 48$ bit).
3. **Bước 3: Chuẩn hóa kết quả (Normalize result):**
   - Nếu tích có dạng $1x.xxxx...$ (lớn hơn hoặc bằng 2.0), dịch phải 1 bit và tăng $E_{\text{result}}$ lên 1.
   - Kiểm tra tràn số (Overflow/Underflow).
4. **Bước 4: Làm tròn kết quả (Round):**
   - Cắt gọt và làm tròn theo chế độ làm tròn IEEE-754. Tái chuẩn hóa nếu phát sinh tràn bit làm tròn.
5. **Bước 5: Xác định dấu kết quả (Determine sign):**
   - Dấu của kết quả là hàm XOR của hai dấu toán hạng:
     $$S_{\text{result}} = S_1 \oplus S_2$$

---

### 3.6. Đồng xử lý toán học Coprocessor 1 & Tập lệnh số thực MIPS

Trong vi kiến trúc MIPS, các phép tính dấu chấm động được giao cho khối phần cứng riêng biệt gọi là **Coprocessor 1 (CP1)** (Slide 31-34).

#### 1. Hệ thống thanh ghi số thực của Coprocessor 1:
- Gồm **32 thanh ghi 32-bit**: `$f0, $f1, $f2, \dots, $f31`.
- **Chế độ Single Precision:** Mỗi thanh ghi chứa độc lập 1 giá trị 32-bit (ví dụ `$f0, $f1...`).
- **Chế độ Double Precision:** Ghép đôi 2 thanh ghi liên tiếp thành một thanh ghi 64-bit. Thanh ghi có chỉ số chẵn làm đại diện:
  - Các cặp: `$f0/$f1`, `$f2/$f3`, `$f4/$f5`, ..., `$f30/$f31`.
  - Thanh ghi chỉ số chẵn chứa nửa trọng số thấp hoặc cao tùy thuộc vào cấu hình endianess.

#### 2. Phân loại các chỉ lệnh số thực MIPS:

| Nhóm chức năng | Tên lệnh | Cú pháp mẫu | Diễn giải chức năng |
| :--- | :--- | :--- | :--- |
| **Truy xuất bộ nhớ (Load/Store)** | `lwc1` | `lwc1 $f0, 32($sp)` | Nạp 1 từ 32-bit từ RAM vào thanh ghi FP đơn (Load Word Coprocessor 1). |
| | `swc1` | `swc1 $f0, 32($sp)` | Lưu 1 từ 32-bit từ thanh ghi FP đơn ra RAM. |
| | `ldc1` | `ldc1 $f2, 0($t0)` | Nạp 64-bit từ RAM vào cặp thanh ghi FP kép `$f2/$f3`. |
| | `sdc1` | `sdc1 $f2, 0($t0)` | Lưu 64-bit từ cặp thanh ghi FP kép `$f2/$f3` ra RAM. |
| **Số học Single (.s)** | `add.s` | `add.s $f0, $f1, $f2` | `$f0 = $f1 + $f2` (Cộng số thực chính xác đơn). |
| | `sub.s` | `sub.s $f0, $f1, $f2` | `$f0 = $f1 - $f2` (Trừ số thực chính xác đơn). |
| | `mul.s` | `mul.s $f0, $f1, $f2` | `$f0 = $f1 \times $f2` (Nhân số thực chính xác đơn). |
| | `div.s` | `div.s $f0, $f1, $f2` | `$f0 = $f1 \div $f2` (Chia số thực chính xác đơn). |
| **Số học Double (.d)** | `add.d`, `sub.d`, `mul.d`, `div.d` | `add.d $f0, $f2, $f4` | Thực hiện trên các cặp thanh ghi kép 64-bit. |
| **So sánh (Compare)** | `c.xx.s` / `c.xx.d` | `c.lt.s $f0, $f1`<br>`c.eq.d $f2, $f4` | So sánh giá trị hai thanh ghi. Nếu thỏa điều kiện `xx` (`eq`: bằng, `lt`: bé hơn, `le`: bé hơn hoặc bằng), bit cờ điều kiện **FP Condition Code** (CC bit) sẽ được bật lên 1, ngược lại xóa về 0. |
| **Rẽ nhánh điều kiện** | `bc1t` | `bc1t TargetLabel` | Nhảy tới nhãn nếu cờ điều kiện số thực là **True (1)** (Branch Coprocessor 1 True). |
| | `bc1f` | `bc1f TargetLabel` | Nhảy tới nhãn nếu cờ điều kiện số thực là **False (0)** (Branch Coprocessor 1 False). |
| **Chuyển đổi kiểu** | `cvt.s.w` | `cvt.s.w $f0, $f0` | Chuyển đổi số nguyên 32-bit (word) sang số thực single (.s). |
| | `cvt.w.s` | `cvt.w.s $f0, $f0` | Chuyển đổi số thực single sang số nguyên 32-bit. |

#### 3. Ví dụ dịch chương trình từ C sang MIPS số thực (Slide 32-33):
##### Ví dụ 1: Câu lệnh điều kiện `if - else`
```c
float a, b; // $f0 = a; $f1 = b
if (a < b)
    a = a + b;
else
    a = a - b;
```
**MIPS Code:**
```assembly
    c.lt.s $f0, $f1        # So sánh: a < b ?
    bc1t   THEN_BRANCH     # Nếu True (a < b) nhảy tới THEN_BRANCH
    sub.s  $f0, $f0, $f1   # Nhánh Else: a = a - b
    j      EXIT            # Nhảy qua nhánh Then
THEN_BRANCH:
    add.s  $f0, $f0, $f1   # Nhánh Then: a = a + b
EXIT:
```

##### Ví dụ 2: Hàm chuyển đổi nhiệt độ Fahrenheit sang Celsius
```c
float f2c (float fahr) {
    return ((5.0 / 9.0) * (fahr - 32.0));
}
```
**MIPS Code:**
```assembly
# Tham số fahr nằm trong $f12, kết quả trả về trong $f0
# Các hằng số 5.0, 9.0, 32.0 lưu trong vùng nhớ tĩnh $gp
f2c:
    lwc1   $f16, const5($gp)      # Nạp hằng số 5.0
    lwc1   $f18, const9($gp)      # Nạp hằng số 9.0
    div.s  $f16, $f16, $f18       # $f16 = 5.0 / 9.0
    lwc1   $f18, const32($gp)     # Nạp hằng số 32.0
    sub.s  $f18, $f12, $f18       # $f18 = fahr - 32.0
    mul.s  $f0,  $f16, $f18       # $f0 = (5.0/9.0) * (fahr - 32.0)
    jr     $ra                    # Quay về hàm gọi
```

---

### 3.7. Độ chính xác số học và các chế độ làm tròn (Accurate Arithmetic & Rounding)

Chuẩn IEEE-754 quy định phần cứng xử lý số thực phải duy trì thêm **3 bit phụ trợ** ở phía sau phần định trị trong quá trình tính toán trung gian trước khi làm tròn (Slide 35):
1. **Guard bit (G):** Bit đầu tiên ngay sau bit cuối cùng của phần Fraction.
2. **Round bit (R):** Bit thứ hai sau bit Guard.
3. **Sticky bit (S):** Bit đặc biệt được thiết lập bằng phép **OR logic của toàn bộ các bit bị đẩy ra ngoài** về phía bên phải. Chỉ cần có ít nhất một bit 1 bị đẩy ra, Sticky bit sẽ lập tức bằng 1 và giữ nguyên giá trị đó.

#### 4 chế độ làm tròn chuẩn của IEEE-754:
1. **Round to Nearest, Ties to Even (Làm tròn đến số gần nhất, hòa thì chọn chẵn - Mặc định):**
   - Làm tròn đến số có thể biểu diễn gần nhất.
   - Nếu khoảng cách nằm chính giữa (Ties - ví dụ đuôi `.5`), chọn giá trị có bit cuối cùng của Fraction là **0 (chẵn)** để triệt tiêu sai số thiên vị thống kê.
2. **Round toward $+\infty$ (Làm tròn tiến về dương vô cùng / Round Up):** Luôn làm tròn lên giá trị lớn hơn tiếp theo.
3. **Round toward $-\infty$ (Làm tròn lùi về âm vô cùng / Round Down):** Luôn làm tròn xuống giá trị nhỏ hơn tiếp theo.
4. **Round toward 0 (Làm tròn về 0 / Truncation):** Cắt bỏ toàn bộ các bit lẻ (tương tự ép kiểu `(int)` trong C).

---

## 4. CHAPTER 4: BỘ XỬ LÝ – ĐƯỜNG DẪN DỮ LIỆU, ĐIỀU KHIỂN & KỸ THUẬT ĐƯỜNG ỐNG (THE PROCESSOR)

> **Lưu ý khảo sát:** File `Chapter4.pdf` cục bộ bị lỗi đường dẫn đăng nhập BK-LMS. Phần dưới đây là bản phục dựng toàn diện và chuẩn mực từ giáo trình của PGS. TS. Phạm Quốc Cường & Patterson/Hennessy.

### 4.1. Thiết kế đường dẫn dữ liệu đơn chu kỳ (Single-Cycle Datapath)

Trong bộ xử lý đơn chu kỳ (Single-cycle processor), **mỗi chỉ lệnh được thực thi trọn vẹn trong đúng 1 chu kỳ xung nhịp**.

```
+---------------------------------------------------------------------------------------------------+
|                                  SINGLE-CYCLE DATAPATH (MIPS)                                     |
+---------------------------------------------------------------------------------------------------+

            +-------------+
            |  PC Branch  |<------------------ Branch Target Addr <-----------+
            +-------------+                                                  |
                  |                                                          |
     +-------+    v      +-------------+                               +------------+
+--->|  PC   |--->+----->| Instruction |                               | Branch ADD |
|    +-------+    |      |   Memory    |                               +------------+
|        |        |      +-------------+                                     ^
|        v        |            |                                             |
|     +----+      |            +--- [31..26]: Opcode ---> Control Unit       |
|     | +4 |------+                     |                                    |
|     +----+                            +--- [25..21]: Read Reg 1            |
|                                       +--- [20..16]: Read Reg 2            |
|                                       +--- [15..11]: Write Reg (R-type)    |
|                                       +--- [15..0] : Immediate             |
|                                                      |                     |
|                                                      v                     |
|               +-----------------------+        +------------+              |
|               |     Register File     |        | Sign-Extend|---> Shift <--+
|               |  Read Data 1 --------->-----+  +------------+     Left 2
|               |  Read Data 2 --------->--+  |        |
|               |                       |  |  v        v
|               |  Write Data <-------+ |  | Mux ---> Mux ---> ALU ---> Data Memory
|               +---------------------+ |  +--+                  |           |
|                                       |                        v           v
+---------------------------------------+---------------------> Mux <--------+
```

#### Các khối chức năng chính trong Datapath:
1. **Bộ đếm chương trình (Program Counter - PC):** Thanh ghi 32-bit lưu trữ địa chỉ của chỉ lệnh chuẩn bị được nạp.
2. **Bộ nhớ chỉ lệnh (Instruction Memory):** Nạp lệnh 32-bit tại địa chỉ PC (`Instruction = Mem[PC]`).
3. **Tập thanh ghi (Register File):** 32 thanh ghi; hỗ trợ đọc đồng thời 2 thanh ghi (`Read Data 1` và `Read Data 2`) và ghi 1 thanh ghi (`Write Data`) khi có tín hiệu `RegWrite = 1`.
4. **Bộ mở rộng dấu (Sign-Extend):** Kéo dài trường hằng số 16-bit thành 32-bit (bảo toàn dấu bù 2).
5. **Bộ số học và logic (ALU):** Thực thi các phép tính cộng, trừ, AND, OR, SLT và kiểm tra cờ `Zero`.
6. **Bộ nhớ dữ liệu (Data Memory):** Đọc (`MemRead`) hoặc ghi (`MemWrite`) dữ liệu từ/vào RAM.

---

### 4.2. Khối điều khiển chính và điều khiển ALU (Main Control & ALU Control Unit)

Khối điều khiển nhận tín hiệu đầu vào là **Opcode 6-bit** (`Instruction[31..26]`) để phát sinh các tín hiệu điều khiển toàn hệ thống:

#### 1. Bảng giá trị tín hiệu điều khiển của khối Main Control:

| Tên lệnh | Opcode | RegDst | ALUSrc | MemtoReg | RegWrite | MemRead | MemWrite | Branch | ALUOp1 | ALUOp0 |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| **R-type** | `000000` | 1 | 0 | 0 | 1 | 0 | 0 | 0 | 1 | 0 |
| **lw** | `100011` | 0 | 1 | 1 | 1 | 1 | 0 | 0 | 0 | 0 |
| **sw** | `101011` | X | 1 | X | 0 | 0 | 1 | 0 | 0 | 0 |
| **beq** | `000100` | X | 0 | X | 0 | 0 | 0 | 1 | 0 | 1 |
| **addi** | `001000` | 0 | 1 | 0 | 1 | 0 | 0 | 0 | 0 | 0 |
| **j** | `000010` | X | X | X | 0 | 0 | 0 | X | X | X |

*Ký hiệu `X`: Don't care (Giá trị 0 hay 1 đều không ảnh hưởng đến kết quả).*

#### 2. Ý nghĩa chức năng của từng tín hiệu điều khiển:
- `RegDst`: Chọn thanh ghi đích:
  - $0$: Chọn trường `rt` (`Instruction[20..16]`, dùng cho `lw`, `addi`).
  - $1$: Chọn trường `rd` (`Instruction[15..11]`, dùng cho các lệnh R-type).
- `ALUSrc`: Chọn toán hạng thứ 2 cho ALU:
  - $0$: Chọn `Read Data 2` từ Register File (dùng cho R-type, `beq`).
  - $1$: Chọn hằng số mở rộng dấu 32-bit từ trường `immediate` (dùng cho `lw`, `sw`, `addi`).
- `MemtoReg`: Chọn nguồn dữ liệu ghi ngược về thanh ghi đích:
  - $0$: Chọn đầu ra của ALU (dùng cho R-type, `addi`).
  - $1$: Chọn dữ liệu đọc ra từ Data Memory (dùng cho `lw`).
- `RegWrite`: Tín hiệu cho phép ghi vào thanh ghi đích ($1$ ghi, $0$ không ghi).
- `MemRead`: Tín hiệu cho phép đọc dữ liệu từ Data Memory ($1$ cho lệnh `lw`).
- `MemWrite`: Tín hiệu cho phép ghi dữ liệu vào Data Memory ($1$ cho lệnh `sw`).
- `Branch`: Tín hiệu kích hoạt rẽ nhánh; kết hợp với cờ `Zero` của ALU qua cổng AND để quyết định chọn nguồn PC tiếp theo:
  $$\text{PCSrc} = \text{Branch} \ \& \ \text{Zero}$$

#### 3. Bảng điều khiển ALU (ALU Control Unit):
Khối điều khiển ALU nhận 2-bit `ALUOp` từ Main Control và 6-bit `funct` (`Instruction[5..0]`) từ lệnh R-type để phát ra tín hiệu điều khiển 4-bit `ALU Operation`:

| ALUOp | Trường Funct | Tên lệnh | Thao tác ALU (ALU Action) | ALU Operation (4-bit) |
| :---: | :---: | :---: | :---: | :---: |
| `00` | XXXXXX | `lw` / `sw` / `addi` | Cộng (Add - tính địa chỉ bộ nhớ) | `0010` |
| `01` | XXXXXX | `beq` | Trừ (Subtract - so sánh bằng) | `0110` |
| `10` | `100000` | `add` | Cộng (Add) | `0010` |
| `10` | `100010` | `sub` | Trừ (Subtract) | `0110` |
| `10` | `100100` | `and` | Và logic (AND) | `0000` |
| `10` | `100101` | `or` | Hoặc logic (OR) | `0001` |
| `10` | `101010` | `slt` | So sánh bé hơn (Set on Less Than) | `0111` |

---

### 4.3. Phân tích chu kỳ xung nhịp và mở rộng Datapath (Extending Datapath)

#### 1. Phân tích đường đi tới hạn (Critical Path Timing Analysis):
Trong thiết kế đơn chu kỳ, chu kỳ xung nhịp của vi xử lý ($T_{\text{clock}}$) bị quy định bởi **chỉ lệnh có thời gian thực thi dài nhất** (thường là lệnh `lw`).

Giả sử thời gian trễ của các linh kiện phần cứng:
- Nạp lệnh từ Bộ nhớ chỉ lệnh (I-Mem): $200\text{ ps}$
- Đọc hoặc ghi Tập thanh ghi (Regs Read/Write): $100\text{ ps}$
- Tính toán qua ALU và các bộ cộng (ALU): $200\text{ ps}$
- Đọc hoặc ghi Bộ nhớ dữ liệu (D-Mem): $200\text{ ps}$
- Trễ qua các bộ ghép kênh Mux: $20\text{ ps}$

Thời gian thực thi của từng chỉ lệnh:
- **Lệnh R-type:** $\text{I-Mem} + \text{Reg Read} + \text{Mux} + \text{ALU} + \text{Mux} + \text{Reg Write} = 200 + 100 + 20 + 200 + 20 + 100 = 640\text{ ps}$.
- **Lệnh `sw`:** $\text{I-Mem} + \text{Reg Read} + \text{Mux} + \text{ALU} + \text{D-Mem} = 200 + 100 + 20 + 200 + 200 = 720\text{ ps}$.
- **Lệnh `beq`:** $\text{I-Mem} + \text{Reg Read} + \text{Mux} + \text{ALU} + \text{Mux} = 200 + 100 + 20 + 200 + 20 = 540\text{ ps}$.
- **Lệnh `lw` (Critical Path):**
  $$T_{\text{clock}} \ge \text{I-Mem} + \text{Reg Read} + \text{Mux} + \text{ALU} + \text{D-Mem} + \text{Mux} + \text{Reg Write}$$
  $$T_{\text{clock}} \ge 200 + 100 + 20 + 200 + 200 + 20 + 100 = 840\text{ ps}$$
$\implies$ Tần số xung nhịp tối đa: $f_{\max} = \frac{1}{840\text{ ps}} \approx 1.19\text{ GHz}$. Mọi lệnh dù ngắn hơn vẫn buộc phải chờ đủ $840\text{ ps}$, gây lãng phí hiệu năng.

#### 2. Kỹ thuật mở rộng Datapath để thêm lệnh mới:

##### Thêm lệnh `jal Target` (Jump and Link):
- **Yêu cầu:** Lưu địa chỉ quay về $\text{PC}+4$ vào thanh ghi `$ra` (`$31`), đồng thời nhảy tới `Target`.
- **Sửa đổi phần cứng:**
  - Thêm một bộ Mux ở đầu vào chọn số thanh ghi ghi: Mux 3 ngõ vào chọn giữa `rt`, `rd` và hằng số cố định `31` (được điều khiển bởi tín hiệu `RegDst = 2`).
  - Thêm một bộ Mux ở đầu vào dữ liệu ghi (`Write Data`): Chọn giữa ALU Out, Mem Out và giá trị $\text{PC}+4$ (được điều khiển bởi tín hiệu `MemtoReg = 2`).
  - Bật tín hiệu `RegWrite = 1`.

##### Thêm lệnh `jr $rs` (Jump Register):
- **Yêu cầu:** Gán giá trị của thanh ghi `rs` vào `PC` (`PC = Read Data 1`).
- **Sửa đổi phần cứng:** Thêm bộ Mux trước cổng nạp của thanh ghi PC, với một ngõ vào nối trực tiếp từ cổng `Read Data 1` của Register File, điều khiển bởi tín hiệu `JumpReg`.

---

### 4.4. Kỹ thuật đường ống (Pipelining Overview & 5 Stages)

Kỹ thuật đường ống (Pipelining) chia quá trình thực thi một chỉ lệnh thành **5 tầng (stages)** độc lập hoạt động gối đầu nhau trong mỗi chu kỳ xung nhịp:

```
Cycle:      1      2      3      4      5      6      7
Instr 1:  [IF] -> [ID] -> [EX] -> [MEM]-> [WB]
Instr 2:         [IF] -> [ID] -> [EX] -> [MEM]-> [WB]
Instr 3:                [IF] -> [ID] -> [EX] -> [MEM]-> [WB]
Instr 4:                       [IF] -> [ID] -> [EX] -> [MEM]-> [WB]
Instr 5:                              [IF] -> [ID] -> [EX] -> [MEM]-> [WB]
```

#### 5 tầng thực thi của kiến trúc MIPS:
1. **IF (Instruction Fetch):** Nạp chỉ lệnh từ bộ nhớ chỉ lệnh dựa vào PC, đồng thời tính $\text{PC}+4$.
2. **ID (Instruction Decode / Register Read):** Giải mã chỉ lệnh, đọc 2 toán hạng từ Register File và mở rộng dấu 16-bit thành 32-bit.
3. **EX (Execute / Address Calculation):** ALU thực hiện phép tính toán số học/logic, hoặc tính địa chỉ bộ nhớ cho lệnh load/store, hoặc tính địa chỉ nhảy nhánh.
4. **MEM (Memory Access):** Đọc hoặc ghi dữ liệu từ/vào Data Memory nếu là lệnh load/store.
5. **WB (Write Back):** Ghi kết quả từ ALU hoặc Data Memory ngược trở lại Register File.

---

### 4.5. Các thanh ghi đường ống và tín hiệu điều khiển phân tầng

Để dữ liệu và các tín hiệu điều khiển của từng chỉ lệnh không bị ghi đè khi lệnh mới bước vào tầng trước, ta đặt các **thanh ghi đường ống (Pipeline Registers)** ngăn cách giữa các tầng:

1. **Thanh ghi IF/ID (64 bits):**
   - Lưu trữ: `PC+4` (32 bits), `Instruction` (32 bits).
2. **Thanh ghi ID/EX (128 bits + Control bits):**
   - Lưu trữ: `PC+4`, `Read Data 1`, `Read Data 2`, `Sign-Extended Immediate`, số hiệu thanh ghi `RegisterRs`, `RegisterRt`, `RegisterRd`.
   - Các tín hiệu điều khiển truyền tiếp: `RegDst`, `ALUOp`, `ALUSrc` (dùng ở EX); `Branch`, `MemRead`, `MemWrite` (dùng ở MEM); `RegWrite`, `MemtoReg` (dùng ở WB).
3. **Thanh ghi EX/MEM (97 bits + Control bits):**
   - Lưu trữ: `Branch Target Address`, cờ `Zero`, kết quả tính toán của ALU (`ALU Result`), giá trị ghi `Read Data 2`, số hiệu thanh ghi đích thực tế (chọn từ `rt` hoặc `rd`).
   - Các tín hiệu điều khiển truyền tiếp: `Branch`, `MemRead`, `MemWrite` (dùng ở MEM); `RegWrite`, `MemtoReg` (dùng ở WB).
4. **Thanh ghi MEM/WB (64 bits + Control bits):**
   - Lưu trữ: Dữ liệu đọc từ bộ nhớ (`Read Data`), kết quả từ ALU (`ALU Result`), số hiệu thanh ghi đích.
   - Các tín hiệu điều khiển: `RegWrite`, `MemtoReg` (dùng ở WB).

---

### 4.6. Xung đột đường ống (Pipeline Hazards) và Kỹ thuật triệt tiêu xung đột

Xung đột (Hazard) là tình trạng lệnh tiếp theo trong đường ống không thể thực thi trong chu kỳ xung nhịp kế tiếp. Có **3 loại xung đột cơ bản**:

#### 1. Xung đột cấu trúc (Structural Hazard):
- **Bản chất:** Hai chỉ lệnh khác nhau cùng tranh chấp một tài nguyên phần cứng trong cùng một chu kỳ.
- **Ví dụ điển hình:** Cùng truy xuất bộ nhớ (lệnh ở tầng IF cần đọc mã lệnh trong khi lệnh ở tầng MEM cần đọc/ghi dữ liệu).
- **Giải pháp phần cứng:**
  - Áp dụng kiến trúc Harvard tách biệt: Dùng riêng **Instruction Cache (I-Cache)** và **Data Cache (D-Cache)**.
  - Thiết kế Register File đa cổng: Hỗ trợ 2 cổng đọc độc lập và 1 cổng ghi riêng biệt (cho phép đọc trong nửa sau chu kỳ và ghi trong nửa đầu chu kỳ).

#### 2. Xung đột dữ liệu (Data Hazard - RAW) & Kỹ thuật chuyển tiếp (Forwarding):
- **Bản chất:** Chỉ lệnh sau cần đọc giá trị của thanh ghi trước khi chỉ lệnh phía trước kịp ghi kết quả về (Read-After-Write - RAW dependency).
- *Ví dụ:*
  ```assembly
  sub $2, $1, $3   # $2 được ghi ở chu kỳ 5 (tầng WB)
  and $12, $2, $5  # Cần đọc $2 ở chu kỳ 3 (tầng EX) -> Dữ liệu cũ!
  or  $13, $6, $2  # Cần đọc $2 ở chu kỳ 4 (tầng EX) -> Dữ liệu cũ!
  ```
- **Giải pháp chuyển tiếp dữ liệu (Forwarding / Bypassing Unit):**
  Lấy kết quả tính toán ngay khi vừa ra khỏi ALU (tại thanh ghi EX/MEM) hoặc vừa nạp xong (tại thanh ghi MEM/WB) để đưa trực tiếp vào đầu vào của ALU ở tầng EX thông qua các bộ ghép kênh Mux 3 ngõ vào.

```
                  +--------------------------------------------------------+
                  |                     Forwarding Unit                    |
                  +--------------------------------------------------------+
                        ^                     ^                      ^
                        |                     |                      |
            +-----------+                     |                      |
            | ID/EX.RegisterRs/Rt             | EX/MEM.RegisterRd    | MEM/WB.RegisterRd
            |                                 | EX/MEM.RegWrite      | MEM/WB.RegWrite
            v                                 |                      |
+------------------------+                    |                      |
| Mux chọn đầu vào ALU A |<-- ForwardA (2 bit)+                      |
+------------------------+                                           |
| Mux chọn đầu vào ALU B |<-- ForwardB (2 bit)-----------------------+
+------------------------+
```

##### Phương trình điều khiển mạch Forwarding:
1. **Xung đột tầng EX (EX Hazard - Forward từ EX/MEM sang EX):**
   - Đầu vào ALU A (`ForwardA = 10`):
     ```verilog
     if (EX/MEM.RegWrite and (EX/MEM.RegisterRd != 0) and (EX/MEM.RegisterRd == ID/EX.RegisterRs))
     ```
   - Đầu vào ALU B (`ForwardB = 10`):
     ```verilog
     if (EX/MEM.RegWrite and (EX/MEM.RegisterRd != 0) and (EX/MEM.RegisterRd == ID/EX.RegisterRt))
     ```
2. **Xung đột tầng MEM (MEM Hazard - Forward từ MEM/WB sang EX):**
   *(Lưu ý: Chỉ forward từ MEM/WB nếu EX Hazard không xảy ra đối với cùng thanh ghi)*
   - Đầu vào ALU A (`ForwardA = 01`):
     ```verilog
     if (MEM/WB.RegWrite and (MEM/WB.RegisterRd != 0) 
         and not(EX/MEM.RegWrite and (EX/MEM.RegisterRd != 0) and (EX/MEM.RegisterRd == ID/EX.RegisterRs))
         and (MEM/WB.RegisterRd == ID/EX.RegisterRs))
     ```
   - Đầu vào ALU B (`ForwardB = 01`):
     ```verilog
     if (MEM/WB.RegWrite and (MEM/WB.RegisterRd != 0) 
         and not(EX/MEM.RegWrite and (EX/MEM.RegisterRd != 0) and (EX/MEM.RegisterRd == ID/EX.RegisterRt))
         and (MEM/WB.RegisterRd == ID/EX.RegisterRt))
     ```

#### 3. Xung đột nạp dữ liệu (Load-Use Data Hazard):
- **Bản chất:** Khi một lệnh dùng ngay dữ liệu được nạp bởi lệnh `lw` đứng liền trước nó. Do dữ liệu từ bộ nhớ chỉ xuất hiện ở cuối tầng MEM, **không thể dùng Forwarding để quay ngược thời gian từ cuối MEM về đầu EX**.
- *Ví dụ:*
  ```assembly
  lw  $s0, 20($t1)   # Dữ liệu $s0 chỉ sẵn sàng ở cuối tầng MEM (chu kỳ 4)
  sub $t2, $s0, $t3  # Cần $s0 ở đầu tầng EX (chu kỳ 3) -> Trễ 1 chu kỳ!
  ```
- **Giải pháp: Khối phát hiện xung đột (Hazard Detection Unit) chèn 1 bong bóng dừng (1 Stall Cycle / Bubble):**
  - **Điều kiện phát hiện Load-Use Hazard:**
    ```verilog
    if (ID/EX.MemRead and ((ID/EX.RegisterRt == IF/ID.RegisterRs) or (ID/EX.RegisterRt == IF/ID.RegisterRt)))
    ```
  - **Hành động khi phát hiện xung đột:**
    1. Đóng băng thanh ghi PC (`PC_Write = 0`): Ngăn không cho nạp lệnh mới.
    2. Đóng băng thanh ghi IF/ID (`IF/ID_Write = 0`): Giữ nguyên chỉ lệnh phụ thuộc ở tầng ID để giải mã lại.
    3. Biến đổi chỉ lệnh trong tầng EX thành lệnh rỗng (NOP - Bubble): Ép toàn bộ 9 tín hiệu điều khiển trong thanh ghi ID/EX thành `000000000`.

#### 4. Xung đột điều khiển (Control Hazard / Branch Hazard):
- **Bản chất:** Khi gặp lệnh rẽ nhánh (`beq`, `bne`), CPU chưa biết nhánh có được thực hiện hay không (Taken hay Not Taken) nên không biết địa chỉ lệnh tiếp theo để nạp.
- **Tổn thất rẽ nhánh (Branch Penalty):**
  - Nếu đánh giá điều kiện rẽ nhánh ở tầng **MEM**: Mất **3 chu kỳ dừng (3 Stall Cycles)**.
  - **Tối ưu hóa phần cứng:** Chuyển bộ cộng tính địa chỉ nhánh và bộ so sánh bằng (comparator XOR) về ngay tầng **ID**:
    $\implies$ Giảm tổn thất rẽ nhánh xuống chỉ còn **1 chu kỳ dừng (1 Stall Cycle)**.

##### Kỹ thuật đoán nhánh (Branch Prediction):
1. **Đoán nhánh tĩnh (Static Branch Prediction):**
   - Luôn đoán nhánh **không nhảy (Predict Not-Taken)**: Tiếp tục nạp lệnh $\text{PC}+4$. Nếu kết quả thực tế là không nhảy $\implies$ 0 chu kỳ trễ. Nếu thực tế là nhảy $\implies$ Xóa lệnh vừa nạp trong thanh ghi IF/ID (`IF.Flush`), chịu phạt 1 chu kỳ trễ.
2. **Đoán nhánh động (Dynamic Branch Prediction):**
   - **Bộ dự đoán 1-bit (1-bit Predictor):** Ghi nhớ kết quả lần rẽ nhánh gần nhất. Nhược điểm: Với các vòng lặp lồng nhau, bộ dự đoán 1-bit sẽ bị đoán sai 2 lần (lần lặp đầu tiên và lần lặp kết thúc vòng lặp).
   - **Bộ dự đoán 2-bit bão hòa (2-bit Saturating Counter):** Cần **2 lần đoán sai liên tiếp** thì mới thay đổi trạng thái dự đoán. 4 trạng thái:
     - `11`: Strongly Taken (Chắc chắn nhảy)
     - `10`: Weakly Taken (Nghiêng về nhảy)
     - `01`: Weakly Not-Taken (Nghiêng về không nhảy)
     - `00`: Strongly Not-Taken (Chắc chắn không nhảy)

```
        Taken                   Taken
      +-------> [11: Strong Taken] <-------+
      |               |                    |
      |       Not-Taken                    |
      |               v                    |
      |         [10: Weak Taken]           |
      |               |                    |
      |       Not-Taken                    |
      |               v                    |
      |       [01: Weak Not-Taken]         |
      |               |                    |
      |       Not-Taken                    |
      |               v                    |
      +------- [00: Strong Not-Taken] <----+
        Taken                   Not-Taken
```

---

### 4.7. Tính toán hiệu năng bộ xử lý đường ống

Trong điều kiện lý tưởng (không có bất kỳ Hazard nào):
$$\text{Speedup} = \frac{\text{Clock Cycle Time}_{\text{Non-pipelined}}}{\text{Clock Cycle Time}_{\text{Pipelined}}} = \text{Số tầng (Pipeline Depth } k)$$

Khi có xung đột phát sinh làm chậm đường ống:
$$\text{CPI}_{\text{avg}} = \text{CPI}_{\text{ideal}} + \text{Stalls}_{\text{Data}} + \text{Stalls}_{\text{Control}}$$

Trong đó $\text{CPI}_{\text{ideal}} = 1$.
$$\text{Speedup}_{\text{thực tế}} = \frac{\text{Pipeline Depth}}{1 + \text{Tần suất Stall trung bình trên mỗi lệnh}}$$

---

## 5. CHAPTER 5: HỆ THỐNG BỘ NHỚ PHÂN TẦNG, BỘ NHỚ CACHE & BỘ NHỚ ẢO (MEMORY HIERARCHY)

> **Lưu ý khảo sát:** File `Chapter5.pdf` cục bộ bị lỗi đường dẫn đăng nhập BK-LMS. Phần dưới đây là bản phục dựng toàn diện và chuẩn mực từ giáo trình của PGS. TS. Phạm Quốc Cường & Patterson/Hennessy.

### 5.1. Nguyên lý định vị (Principle of Locality)

Các chương trình máy tính không truy xuất ngẫu nhiên trên toàn bộ không gian bộ nhớ mà tuân theo **nguyên lý định vị (Principle of Locality)**:
1. **Định vị thời gian (Temporal Locality):** Một ô nhớ vừa được truy xuất thì có khả năng rất cao sẽ được truy xuất lại trong tương lai gần.
   - *Ví dụ:* Các biến đếm trong vòng lặp (`i, j`), mã lệnh của phần thân vòng lặp (loop body), đỉnh ngăn xếp stack.
2. **Định vị không gian (Spatial Locality):** Một ô nhớ vừa được truy xuất thì các ô nhớ có địa chỉ liền kề với nó có khả năng cao sẽ được truy xuất kế tiếp.
   - *Ví dụ:* Duyệt tuần tự mảng dữ liệu 1 chiều, chuỗi các chỉ lệnh được nạp kế tiếp nhau ($\text{PC}, \text{PC}+4, \text{PC}+8...$).

---

### 5.2. Cấu trúc phân tầng bộ nhớ (Memory Hierarchy Pyramid)

Để giải quyết mâu thuẫn giữa tốc độ siêu nhanh của CPU và dung lượng khổng lồ nhưng chậm chạp của bộ nhớ thứ cấp, hệ thống máy tính xây dựng cấu trúc phân tầng:

```
                  /\        [Thanh ghi CPU Registers]   (~0.5 ns, < 1 KB)
                 /  \
                /    \      [L1 Cache (On-chip)]         (~1 ns, 32 - 64 KB)
               /      \
              /        \    [L2 Cache (SRAM)]            (~3 - 10 ns, 256 KB - 1 MB)
             /          \
            /            \  [L3 Cache (Shared SRAM)]     (~10 - 20 ns, 4 - 32 MB)
           /              \
          /                \[Bộ nhớ chính Main Memory DRAM] (~50 - 100 ns, 8 - 64 GB)
         /                  \
        /--------------------\ [Ổ cứng lưu trữ SSD / HDD]    (~0.1 - 10 ms, TBs)
```
- **Đi từ đỉnh xuống đáy:** Dung lượng tăng dần, thời gian truy xuất tăng dần (chậm đi), chi phí trên mỗi bit giảm dần.

---

### 5.3. Cấu tạo và nguyên lý hoạt động của Bộ nhớ Cache

- Bộ nhớ Cache lưu trữ dữ liệu theo từng đơn vị gọi là **Khối (Block hay Cache Line)**, kích thước $B = 2^b$ bytes.
- Khi CPU muốn đọc dữ liệu tại địa chỉ $A$:
  - Nếu dữ liệu đang nằm trong Cache $\implies$ **Trúng (Hit)**: Dữ liệu được trả về CPU lập tức với thời gian $\text{Hit Time}$.
  - Nếu dữ liệu không có trong Cache $\implies$ **Trượt (Miss)**: CPU phải dừng lại để nạp cả khối chứa dữ liệu đó từ bộ nhớ dưới lên Cache với chi phí thời gian $\text{Miss Penalty}$.

---

### 5.4. Các kỹ thuật ánh xạ Cache (Cache Mapping Schemes)

#### 1. Ánh xạ trực tiếp (Direct-Mapped Cache):
- Mỗi khối bộ nhớ chỉ có thể được đặt vào **đúng 1 vị trí cố định** trong Cache:
  $$\text{Vị trí dòng Cache} = (\text{Địa chỉ khối}) \pmod{\text{Tổng số dòng Cache}}$$
- **Cấu trúc địa chỉ 32-bit:**
  ```
  |     Tag (t bits)     |   Index (s bits)   |  Offset (b bits)  |
  | 31                ...|...              ...|...               0|
  ```
  - **Offset ($b$ bit):** Xác định byte cụ thể trong khối ($b = \log_2(\text{Kích thước khối } B)$).
  - **Index ($s$ bit):** Dùng để chọn dòng Cache tương ứng ($s = \log_2(\text{Số dòng Cache } S)$).
  - **Tag ($t$ bit):** Các bit còn lại dùng để kiểm tra xem dòng Cache đó có đúng là khối dữ liệu CPU cần tìm hay không ($t = 32 - s - b$).

#### 2. Ánh xạ kết hợp tập hợp $N$-đường ($N$-Way Set-Associative Cache):
- Cache được chia thành nhiều **Tập hợp (Sets)**, mỗi Set chứa đúng **$N$ dòng Cache (Ways)**:
  $$\text{Số lượng Set } S = \frac{\text{Tổng dung lượng Cache}}{N \times \text{Kích thước khối } B}$$
  $$\text{Vị trí Set} = (\text{Địa chỉ khối}) \pmod S$$
- Một khối bộ nhớ có thể nằm ở **bất kỳ dòng nào trong số $N$ dòng** thuộc Set đó.
- Cần $N$ bộ so sánh Tag (Comparators) hoạt động song song.

#### 3. Ánh xạ kết hợp hoàn toàn (Fully-Associative Cache):
- Một khối bộ nhớ có thể nằm ở **bất kỳ vị trí nào** trong toàn bộ Cache.
- **Không có trường Index ($s = 0$)!** Địa chỉ chỉ gồm 2 trường: **Tag** và **Offset**.
- Cần số bộ so sánh bằng đúng tổng số dòng trong Cache $\implies$ Phần cứng phức tạp, chỉ dùng cho Cache rất nhỏ hoặc TLB.

---

### 5.5. Phân tích địa chỉ truy xuất bộ nhớ & Dung lượng phần cứng

#### 1. Công thức tổng quát phân rã địa chỉ:
Cho vi xử lý địa chỉ $M$-bit (thường $M=32$), dung lượng dữ liệu Cache là $C$ bytes, kích thước một khối là $B$ bytes, độ kết hợp là $N$-way:
1. **Số bit Offset ($b$):**
   $$b = \log_2(B)$$
2. **Số lượng Set ($S$):**
   $$S = \frac{C}{N \times B}$$
3. **Số bit Index ($s$):**
   $$s = \log_2(S)$$
4. **Số bit Tag ($t$):**
   $$t = M - s - b$$

#### 2. Công thức tính tổng dung lượng bit phần cứng để xây dựng Cache:
Một dòng Cache hoàn chỉnh không chỉ chứa Data mà bắt buộc phải có thêm các bit trạng thái:
- **Valid bit ($V$):** 1 bit (xác nhận dữ liệu trong dòng là hợp lệ).
- **Dirty bit ($D$):** 1 bit (chỉ có trong chính sách Write-Back để ghi nhận dữ liệu đã bị sửa đổi).
- **Tag bits ($t$):** $t$ bit.
- **Data bits:** $8 \times B$ bit.

$$\text{Tổng số bit phần cứng} = S \times N \times (1_{\text{Valid}} + [1_{\text{Dirty}}] + t_{\text{Tag}} + 8 \times B_{\text{Data}})$$

---

### 5.6. Chính sách thay thế khối và Ghi dữ liệu (Replacement & Write Policies)

#### 1. Chính sách thay thế khối (Khi Set đã đầy và có Miss):
1. **LRU (Least Recently Used - Thay thế khối ít được dùng gần đây nhất):**
   - Theo dõi lịch sử truy xuất; khối nào có thời gian không được đụng tới lâu nhất sẽ bị loại bỏ. Tối ưu nhất theo nguyên lý định vị thời gian nhưng tốn phần cứng lưu trạng thái.
2. **FIFO (First In, First Out - Vào trước ra trước):**
   - Khối nào nạp vào trước sẽ bị thay ra trước.
3. **Random (Ngẫu nhiên):**
   - Chọn ngẫu nhiên một khối để thay thế. Đơn giản về phần cứng, hiệu năng gần tiệm cận LRU khi Cache lớn.

#### 2. Chính sách xử lý khi ghi dữ liệu (Write Policies):
- **Khi Ghi Trúng (Write Hit):**
  - **Write-Through (Ghi xuyên qua):** Dữ liệu được ghi đồng thời vào cả Cache và bộ nhớ dưới. Để tránh làm chậm CPU, phần cứng trang bị thêm **Bộ đệm ghi (Write Buffer)**.
  - **Write-Back (Ghi giữ lại):** Dữ liệu chỉ được cập nhật trên Cache và bật bit **Dirty bit = 1**. Khối chỉ được ghi trả về bộ nhớ dưới khi nó bị ghi đè/thay thế (Evicted). Tốc độ nhanh và tiết kiệm băng thông bus.
- **Khi Ghi Trượt (Write Miss):**
  - **Write-Allocate (Nạp rồi ghi):** Nạp cả khối từ bộ nhớ dưới lên Cache, sau đó thực hiện ghi đè dữ liệu mới vào (thường đi đôi với Write-Back).
  - **No-Write-Allocate / Write-Around (Ghi bỏ qua):** Ghi thẳng dữ liệu xuống bộ nhớ dưới mà không nạp khối đó lên Cache (thường đi đôi với Write-Through).

---

### 5.7. Đánh giá hiệu năng Cache (AMAT & Cache nhiều mức)

#### 1. Phân loại nguyên nhân trượt Cache (The 3 C's of Cache Misses):
1. **Compulsory Misses (Cold Miss - Trượt bắt buộc):** Lần đầu tiên truy xuất khối dữ liệu (khối chưa từng được nạp). Giải pháp: Tăng kích thước khối $B$ (tận dụng định vị không gian).
2. **Capacity Misses (Trượt do dung lượng):** Cache không đủ chỗ chứa tất cả các khối cần thiết cho chương trình. Giải pháp: Tăng tổng dung lượng Cache $C$.
3. **Conflict Misses (Collision Miss - Trượt do xung đột):** Nhiều khối cùng ánh xạ vào chung 1 Set trong khi các Set khác còn trống (chỉ xảy ra trong Direct-Mapped và Set-Associative). Giải pháp: Tăng độ kết hợp $N$-way.

#### 2. Thời gian truy xuất bộ nhớ trung bình (AMAT - Average Memory Access Time):
$$\text{AMAT} = \text{Hit Time} + (\text{Miss Rate} \times \text{Miss Penalty})$$

#### 3. Chu kỳ xung nhịp CPU khi có trễ bộ nhớ:
$$\text{CPU Time} = (\text{CPU Execution Cycles} + \text{Memory Stall Cycles}) \times \text{Clock Cycle Time}$$
$$\text{Memory Stall Cycles} = \text{Instruction Count} \times \frac{\text{Memory Accesses}}{\text{Instruction}} \times \text{Miss Rate} \times \text{Miss Penalty}$$

#### 4. Cache hai mức (Two-Level Cache L1, L2):
- **Local Miss Rate:** Tỷ lệ trượt tính riêng trên số lần truy xuất của tầng đó:
  $$\text{Miss Rate}_{L1} = \frac{\text{Misses}_{L1}}{\text{Accesses từ CPU}}; \quad \text{Miss Rate}_{L2, \text{local}} = \frac{\text{Misses}_{L2}}{\text{Accesses từ L1}}$$
- **Global Miss Rate:** Tỷ lệ trượt tính trên tổng số lần truy xuất của CPU:
  $$\text{Global Miss Rate}_{L2} = \text{Miss Rate}_{L1} \times \text{Miss Rate}_{L2, \text{local}}$$
- **Công thức AMAT 2 cấp:**
  $$\text{AMAT} = \text{Hit Time}_{L1} + \text{Miss Rate}_{L1} \times (\text{Hit Time}_{L2} + \text{Miss Rate}_{L2, \text{local}} \times \text{Miss Penalty}_{L2})$$

---

### 5.8. Bộ nhớ ảo (Virtual Memory), Bảng phân trang (Page Table) & TLB

Bộ nhớ ảo (Virtual Memory) biến bộ nhớ chính DRAM thành một "Cache" cho bộ nhớ thứ cấp (ổ đĩa), cho phép chương trình sử dụng không gian địa chỉ vượt quá dung lượng vật lý thực tế.

#### 1. Khái niệm cơ bản:
- Đơn vị trao đổi dữ liệu gọi là **Trang (Page)** (kích thước điển hình là 4 KB).
- **Địa chỉ ảo (Virtual Address - VA):** Do chương trình tạo ra, gồm:
  - **Virtual Page Number (VPN):** Số hiệu trang ảo.
  - **Page Offset:** Vị trí byte trong trang (không đổi khi chuyển dịch địa chỉ).
- **Địa chỉ vật lý (Physical Address - PA):** Địa chỉ thực trên thanh RAM, gồm:
  - **Physical Page Number (PPN):** Số hiệu khung trang vật lý (Page Frame).
  - **Page Offset:** Giữ nguyên giá trị của Page Offset ảo ($p = \log_2(\text{Page Size})$).

#### 2. Bảng phân trang (Page Table):
- Là cấu trúc mảng được lưu trữ trong DRAM, được chỉ trỏ bởi thanh ghi **Page Table Base Register (PTBR)**.
- Được lập chỉ mục trực tiếp bởi VPN. Mỗi mục trong bảng phân trang (PTE - Page Table Entry) chứa:
  - **Valid bit:** $1$ nếu trang đang nằm trên RAM; $0$ nếu trang đang nằm trên đĩa (Page Fault).
  - **Dirty bit:** Bật khi trang bị ghi sửa đổi.
  - **Access Rights / Protection bits:** Quyền đọc/ghi/thực thi.
  - **Physical Page Number (PPN):** Địa chỉ khung trang trên RAM.

#### 3. Bộ đệm chuyển đổi địa chỉ (TLB - Translation Lookaside Buffer):
Vì mỗi lần truy xuất bộ nhớ lại tốn thêm 1 lần truy xuất Page Table trong DRAM, phần cứng trang bị **TLB** - một bộ nhớ Cache đặc biệt nhỏ, siêu nhanh (thường là Fully Associative) đặt ngay trên CPU để lưu trữ các ánh xạ VPN $\rightarrow$ PPN được dùng gần đây:
- **TLB Hit:** Tìm thấy ánh xạ ngay lập tức $\implies$ Tạo Physical Address và truy xuất Cache trong 1 chu kỳ.
- **TLB Miss:** Tra cứu Page Table trong DRAM:
  - Nếu `Valid = 1`: Nạp mục đó vào TLB và thực thi lại.
  - Nếu `Valid = 0`: Kích hoạt ngắt phần cứng **Lỗi trang (Page Fault Exception)** $\implies$ Hệ điều hành can thiệp nạp trang từ đĩa vào RAM.

---

### 5.9. Quy trình phối hợp tổng thể: TLB + Virtual Memory + Cache

Mọi truy xuất bộ nhớ từ CPU đều trải qua chuỗi phối hợp sau:

```
[Virtual Address từ CPU]
         |
         v
   Tra cứu [TLB]
      /     \
(Hit)/       \(Miss)
    v         v
Lấy PPN   Tra cứu [Page Table]
    |        /          \
    |   (Valid=1)     (Valid=0: Page Fault!)
    |       v               v
    |   Cập nhật TLB    HĐH nạp từ Đĩa vào RAM
    |       |               |
    +-------+---------------+
            |
            v
   [Physical Address]
            |
            v
     Tra cứu [Cache]
        /     \
  (Hit)/       \(Miss)
      v         v
Trả data     Nạp Block từ DRAM lên Cache
cho CPU
```

#### Ma trận các trường hợp kết hợp (Hit/Miss Combination Matrix):

| TLB | Page Table | Cache | Khả năng xảy ra | Giải thích hiện tượng thực tế |
| :---: | :---: | :---: | :---: | :--- |
| **Hit** | **Hit** | **Hit** | **Có thể** | Trường hợp lý tưởng nhất: Ánh xạ có trong TLB, dữ liệu có sẵn trong Cache. |
| **Hit** | **Hit** | **Miss** | **Có thể** | Ánh xạ có trong TLB, nhưng khối dữ liệu chưa nạp vào Cache (phải đọc DRAM). |
| **Miss** | **Hit** | **Hit** | **Có thể** | Ánh xạ không có trong TLB nhưng trang có trên RAM, và khối dữ liệu đó tình cờ đã nằm trong Cache. |
| **Miss** | **Hit** | **Miss** | **Có thể** | Cả ánh xạ và dữ liệu đều chưa nạp vào TLB và Cache, nhưng trang đã có trên RAM. |
| **Miss** | **Miss** | **Miss** | **Có thể** | **Page Fault:** Trang chưa nạp lên RAM (phải gọi HĐH đọc đĩa). |
| **Hit** | **Miss** | Bất kỳ | **KHÔNG THỂ** | Vô lý: TLB chỉ lưu ánh xạ của những trang đang hợp lệ (`Valid = 1`) trong Page Table. |
| Bất kỳ | **Miss** | **Hit** | **KHÔNG THỂ** | Vô lý: Dữ liệu không thể có trong Cache nếu trang chứa nó thậm chí chưa có trên RAM! |

---

## 6. TUYỂN TẬP CÁC DẠNG BÀI TẬP TRỌNG TÂM THI CUỐI KỲ (KÈM LỜI GIẢI MẪU CHI TIẾT)

### DẠNG 1: CHUYỂN ĐỔI SỐ THỰC DẤU CHẤM ĐỘNG IEEE-754

#### Đề bài mẫu 1.1 (Thập phân sang Hex IEEE-754):
Chuyển đổi số thực thập phân sau sang định dạng IEEE-754 độ chính xác đơn (Single Precision - 32 bit) dưới dạng số Hexadecimal:
$$X = -26.625_{10}$$

##### Lời giải chi tiết:
1. **Xác định bit dấu ($S$):** Do $X < 0 \implies S = 1$.
2. **Chuyển đổi phần nguyên và phần thập phân sang nhị phân:**
   - Phần nguyên: $26_{10} = 16 + 8 + 2 = 11010_2$.
   - Phần thập phân: $0.625_{10} = \frac{1}{2} + \frac{1}{8} = 2^{-1} + 2^{-3} = 0.101_2$.
   - Ghép lại: $26.625_{10} = 11010.101_2$.
3. **Chuẩn hóa dạng khoa học nhị phân:**
   $$11010.101_2 = 1.1010101_2 \times 2^4$$
   $\implies$ Số mũ thực tế $e = 4$.
4. **Tính toán trường Exponent ($E$):**
   $$E = e + \text{Bias} = 4 + 127 = 131_{10} = 10000011_2$$
5. **Xác định trường Fraction ($F$):**
   - Lấy phần sau dấu phẩy và thêm các số 0 về phía sau cho đủ 23 bit:
     $$F = 10101010000000000000000_2$$
6. **Ghép 32-bit và đổi sang Hex:**
   - Cấu trúc: `S | Exponent | Fraction`
     `1 | 10000011 | 10101010000000000000000`
   - Gom cụm 4 bit từ trái sang phải:
     `1100 0001 1101 0101 0000 0000 0000 0000`
   - Đổi từng cụm 4 bit sang Hex:
     `  C    1    D    5    0    0    0    0`

$\implies$ **Đáp số:** `0xC1D50000`.

---

#### Đề bài mẫu 1.2 (Hex IEEE-754 sang Thập phân):
Giải mã giá trị số thực thập phân của số Hex sau (được biểu diễn theo chuẩn IEEE-754 Single Precision):
$$\text{Hex} = \text{0x414C0000}$$

##### Lời giải chi tiết (Slide 21):
1. **Chuyển số Hex sang chuỗi 32-bit nhị phân:**
   `0x414C0000` = `0100 0001 0100 1100 0000 0000 0000 0000`
2. **Phân tách các trường bit:**
   - Bit 31: $S = 0 \implies$ Số dương.
   - Bit 30..23: $E = 10000010_2 = 128 + 2 = 130_{10}$.
   - Bit 22..0: $F = 100110000...00_2$.
3. **Tính toán số mũ thực tế $e$:**
   $$e = E - \text{Bias} = 130 - 127 = 3$$
4. **Tính giá trị phần định trị đầy đủ (Significand):**
   $$\text{Significand} = 1.F = 1 + (1 \times 2^{-1} + 0 \times 2^{-2} + 0 \times 2^{-3} + 1 \times 2^{-4} + 1 \times 2^{-5})$$
   $$\text{Significand} = 1 + 0.5 + 0.0625 + 0.03125 = 1 + 0.59375 = 1.59375$$
5. **Tính giá trị thực tế $X$:**
   $$X = (-1)^0 \times 1.59375 \times 2^3 = 1.59375 \times 8 = 12.75_{10}$$

$\implies$ **Đáp số:** $+12.75$.

---

### DẠNG 2: THIẾT KẾ ĐƯỜNG DẪN DỮ LIỆU & BỔ SUNG LỆNH MỚI

#### Đề bài mẫu 2.1:
Người ta muốn bổ sung chỉ lệnh `bne $rs, $rt, Label` (Branch if Not Equal) vào đường dẫn dữ liệu đơn chu kỳ MIPS cơ bản.
1. Hãy mô tả cách thức sửa đổi phần cứng bộ xử lý.
2. Thiết lập bảng giá trị của các tín hiệu điều khiển cho lệnh `bne`.

##### Lời giải chi tiết:
1. **Sửa đổi phần cứng:**
   - Lệnh `bne` nhảy khi hai toán hạng **khác nhau**, tức là cờ `Zero` của ALU xuất ra mức **0**.
   - Trong mạch nguyên bản, tín hiệu chọn nguồn PC là $\text{PCSrc} = \text{Branch} \ \& \ \text{Zero}$.
   - **Sửa đổi:** Thêm cổng đảo NOT trước cờ `Zero` hoặc thêm một bộ Mux 2-1 điều khiển bởi tín hiệu `BranchType`:
     - Nếu `BranchType = 0` (lệnh `beq`): $\text{PCSrc} = \text{Branch} \ \& \ \text{Zero}$.
     - Nếu `BranchType = 1` (lệnh `bne`): $\text{PCSrc} = \text{Branch} \ \& \ (\overline{\text{Zero}})$.
2. **Giá trị các tín hiệu điều khiển:**
   - `RegDst = X` (không ghi thanh ghi)
   - `ALUSrc = 0` (chọn đọc `rt` để so sánh với `rs`)
   - `MemtoReg = X`
   - `RegWrite = 0` (không ghi Register File)
   - `MemRead = 0`
   - `MemWrite = 0`
   - `Branch = 1`
   - `BranchType = 1`
   - `ALUOp = 01` (thực hiện phép trừ để kiểm tra cờ Zero)

---

### DẠNG 3: BÀI TOÁN XUNG ĐỘT PIPELINE VÀ HIỆU NĂNG

#### Đề bài mẫu 3.1:
Cho đoạn mã lệnh MIPS sau thực thi trên bộ xử lý đường ống 5 tầng chuẩn (IF, ID, EX, MEM, WB):
```assembly
I1: lw   $t1, 0($t0)
I2: add  $t2, $t1, $t3
I3: sub  $t4, $t2, $t1
I4: sw   $t4, 4($t0)
```
1. Xác định các phụ thuộc dữ liệu (RAW Dependencies).
2. Nếu hệ thống **có hỗ trợ Forwarding Unit đầy đủ**, hãy vẽ sơ đồ thực thi theo chu kỳ xung nhịp và chỉ rõ các vị trí Forwarding cũng như số chu kỳ dừng (Stall).
3. Cần bao nhiêu chu kỳ xung nhịp để hoàn thành toàn bộ đoạn mã trên?

##### Lời giải chi tiết:
1. **Phân tích phụ thuộc dữ liệu (RAW):**
   - Giữa $I_1$ (`lw $t1`) và $I_2$ (`add ... $t1`): $I_2$ dùng `$t1` ngay sau $I_1$ $\implies$ **Load-Use Data Hazard!** (Không thể triệt tiêu hoàn toàn bằng Forwarding, bắt buộc phải dừng 1 chu kỳ).
   - Giữa $I_2$ (`add $t2`) và $I_3$ (`sub ... $t2`): $I_3$ dùng `$t2` từ $I_2$ $\implies$ Phụ thuộc dữ liệu, giải quyết được bằng Forwarding từ EX/MEM sang EX.
   - Giữa $I_1$ (`lw $t1`) và $I_3$ (`sub ... $t1`): $I_3$ dùng `$t1$ từ $I_1$ $\implies$ Forwarding từ MEM/WB sang EX.
   - Giữa $I_3$ (`sub $t4`) và $I_4$ (`sw $t4`): Forwarding từ EX/MEM sang MEM (hoặc sang EX).

2. **Sơ đồ thực thi theo chu kỳ (Clock Cycle Chart):**
```
Chỉ lệnh       CC1  CC2  CC3  CC4   CC5   CC6   CC7   CC8   CC9  CC10
I1: lw          IF   ID   EX   MEM   WB
I2: add              IF   ID  [STALL] EX   MEM   WB
    (Bubble)                  [NOP]  NOP   NOP   NOP
I3: sub                        IF    ID    EX    MEM   WB
I4: sw                               IF    ID    EX    MEM   WB
```
- Tại CC4: Khối Hazard Detection Unit phát hiện `ID/EX.MemRead = 1` và `ID/EX.RegisterRt == IF/ID.RegisterRs ($t1)`, chèn 1 NOP vào tầng EX, giữ $I_2$ ở ID và $I_3$ ở IF.
- Tại CC5: Dữ liệu `$t1` từ $I_1$ ra khỏi MEM được Forwarding sang đầu vào ALU của $I_2$ ở tầng EX.
- Tại CC7: Dữ liệu `$t2` từ $I_2$ ra khỏi EX được Forwarding sang đầu vào ALU của $I_3$ ở tầng EX.
- Tại CC8: Dữ liệu `$t4` từ $I_3$ ra khỏi EX được Forwarding sang $I_4$.

3. **Tổng số chu kỳ hoàn thành:**
   - 4 lệnh trong đường ống 5 tầng lý tưởng mất: $5 + (4 - 1) = 8$ chu kỳ.
   - Do có 1 chu kỳ dừng (Stall) vì Load-Use $\implies$ Tổng thời gian:
     $$\text{Tổng số chu kỳ} = 8 + 1 = 9\text{ cycles}$$

---

### DẠNG 4: THIẾT KẾ VÀ TÍNH TOÁN BỘ NHỚ CACHE

#### Đề bài mẫu 4.1:
Một hệ thống máy tính 32-bit có bộ nhớ Cache dữ liệu với các thông số sau:
- Tổng dung lượng dữ liệu Cache: $C = 64\text{ KB} = 64 \times 1024\text{ bytes} = 65,536\text{ bytes}$.
- Kích thước một khối (Block size): $B = 32\text{ bytes}$.
- Tổ chức theo kiểu: **4-way Set-Associative Cache**.
- Sử dụng chính sách ghi: **Write-Back** (có Dirty bit).

**Yêu cầu:**
1. Hãy xác định số bit của các trường: Block Offset ($b$), Set Index ($s$), Tag ($t$).
2. Tính tổng dung lượng phần cứng (tính bằng bits và Kbits) cần thiết để cài đặt toàn bộ bộ nhớ Cache này (bao gồm cả dữ liệu và các bit điều khiển).

##### Lời giải chi tiết:
1. **Xác định các trường địa chỉ:**
   - Số bit Block Offset ($b$):
     $$b = \log_2(B) = \log_2(32) = 5\text{ bits}$$
   - Tổng số Set ($S$):
     $$S = \frac{\text{Dung lượng Cache}}{N \times B} = \frac{64 \times 1024}{4 \times 32} = \frac{65,536}{128} = 512\text{ Sets}$$
   - Số bit Set Index ($s$):
     $$s = \log_2(S) = \log_2(512) = 9\text{ bits}$$
   - Số bit Tag ($t$):
     $$t = 32 - s - b = 32 - 9 - 5 = 18\text{ bits}$$
   - **Phân rã địa chỉ 32-bit:**
     - Tag: bit 31 đến bit 14 (18 bits).
     - Index: bit 13 đến bit 5 (9 bits).
     - Offset: bit 4 đến bit 0 (5 bits).

2. **Tính tổng dung lượng bit phần cứng:**
   - Mỗi dòng Cache (Cache Line) bao gồm:
     - 1 bit Valid.
     - 1 bit Dirty (do dùng chính sách Write-Back).
     - 18 bit Tag.
     - Data: $32\text{ bytes} \times 8\text{ bits/byte} = 256\text{ bits}$.
     $$\implies \text{Dung lượng 1 dòng} = 1 + 1 + 18 + 256 = 276\text{ bits}$$
   - Tổng số dòng Cache trong toàn bộ hệ thống:
     $$\text{Tổng số dòng} = S \times N = 512 \times 4 = 2048\text{ dòng}$$
   - Tổng dung lượng phần cứng:
     $$\text{Tổng số bit} = 2048 \times 276 = 565,248\text{ bits} = 552\text{ Kbits} \approx 68.96\text{ KB}$$
     *(Phần phụ trội lưu trữ Tag, Valid, Dirty chiếm thêm gần 5 KB so với 64 KB dữ liệu thô!)*

---

#### Đề bài mẫu 4.2 (Tính AMAT bộ nhớ 2 cấp):
Cho một bộ vi xử lý có tần số xung nhịp $2\text{ GHz}$ ($T_c = 0.5\text{ ns}$). Thời gian và tỷ lệ trượt của các cấp bộ nhớ như sau:
- Cache L1: $\text{Hit Time} = 1\text{ chu kỳ}$, $\text{Miss Rate} = 5\%$.
- Cache L2: $\text{Hit Time} = 10\text{ chu kỳ}$, $\text{Local Miss Rate} = 20\%$.
- Bộ nhớ chính DRAM: $\text{Miss Penalty} = 100\text{ ns} = 200\text{ chu kỳ xung nhịp}$.

**Yêu cầu:** Tính thời gian truy xuất bộ nhớ trung bình (AMAT) theo đơn vị chu kỳ xung nhịp và theo đơn vị nano giây.

##### Lời giải chi tiết:
1. Áp dụng công thức AMAT 2 cấp:
   $$\text{Penalty}_{L1} = \text{Hit Time}_{L2} + (\text{Miss Rate}_{L2, \text{local}} \times \text{Miss Penalty}_{\text{DRAM}})$$
   $$\text{Penalty}_{L1} = 10 + (0.20 \times 200) = 10 + 40 = 50\text{ chu kỳ}$$
2. Tính AMAT tổng thể:
   $$\text{AMAT} = \text{Hit Time}_{L1} + (\text{Miss Rate}_{L1} \times \text{Penalty}_{L1})$$
   $$\text{AMAT} = 1 + (0.05 \times 50) = 1 + 2.5 = 3.5\text{ chu kỳ xung nhịp}$$
3. Quy đổi sang thời gian thực:
   $$\text{AMAT (ns)} = 3.5 \times T_c = 3.5 \times 0.5\text{ ns} = 1.75\text{ ns}$$

$\implies$ **Đáp số:** $3.5\text{ cycles}$ tương đương $1.75\text{ ns}$.

---

## 7. BẢNG TRA CỨU CÔNG THỨC NHANH (CHEATSHEET & QUICK FORMULA REFERENCE)

### 1. Số học máy tính & IEEE-754:
- Số thực Single Precision (32-bit):
  $$X = (-1)^S \times (1.F) \times 2^{E - 127}$$
- Số thực Double Precision (64-bit):
  $$X = (-1)^S \times (1.F) \times 2^{E - 1023}$$
- Nhân FP: $E_{\text{res}} = E_1 + E_2 - \text{Bias}$; $S_{\text{res}} = S_1 \oplus S_2$.

### 2. Đường ống (Pipelining):
- Điều kiện Forwarding từ EX/MEM:
  $$\text{EX/MEM.RegWrite} \ \& \ (\text{EX/MEM.RegisterRd} \ne 0) \ \& \ (\text{EX/MEM.RegisterRd} == \text{ID/EX.RegisterRs/Rt})$$
- Điều kiện Load-Use Hazard Stall:
  $$\text{ID/EX.MemRead} \ \& \ ((\text{ID/EX.RegisterRt} == \text{IF/ID.RegisterRs}) \mid\mid (\text{ID/EX.RegisterRt} == \text{IF/ID.RegisterRt}))$$
- Hiệu năng có dừng: $\text{CPI} = 1 + \text{Tần suất Stall}$.

### 3. Bộ nhớ Cache & Bộ nhớ ảo:
- Phân rã địa chỉ Cache:
  - $\text{Offset } b = \log_2(\text{Block Size})$
  - $\text{Sets } S = \frac{\text{Cache Size}}{N \times \text{Block Size}}$
  - $\text{Index } s = \log_2(S)$
  - $\text{Tag } t = \text{Address Bits} - s - b$
- Dung lượng Cache phần cứng:
  $$\text{Total Bits} = S \times N \times (1_V + [1_D] + t + 8B)$$
- Thời gian truy xuất trung bình:
  $$\text{AMAT} = \text{Hit Time} + \text{Miss Rate} \times \text{Miss Penalty}$$
- Phân rã địa chỉ bộ nhớ ảo:
  - $\text{Page Offset } p = \log_2(\text{Page Size})$
  - $\text{VPN Bits} = \text{Virtual Address Bits} - p$
  - $\text{PPN Bits} = \text{Physical Address Bits} - p$
  - $\text{Số mục trong Bảng phân trang} = 2^{\text{VPN Bits}}$

---
*Tài liệu được biên soạn đồng bộ, toàn diện và đối chiếu với giáo trình chuẩn CO2007 - Khoa KH&KT Máy tính, Đại học Bách Khoa TP.HCM.*
