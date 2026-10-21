# Cách đặt lệnh trên OKX? Market, Limit, Take Profit, Stop Loss và logic khớp lệnh cho người mới 2026 (Mã mời OKOFFICIALLY)

Nhiều người lần đầu giao dịch trên OKX, lỗi sai thực sự thường không phải là "không hiểu BTC", mà là:

không biết lệnh của mình rốt cuộc sẽ khớp như thế nào.
Rõ ràng chỉ muốn chờ một mức giá, kết quả lại khớp sớm.
Vốn định mua ngay lập tức, nhưng lệnh lại treo mãi.
Đã thiết lập take profit / stop loss, nhưng không rõ khi nào chúng được kích hoạt.

Vì vậy bài viết này không lặp lại những nội dung trước như:

- các lỗi người mới cần tránh
- dòng tiền
- nhịp độ giao dịch
- long/short hợp đồng
- review giao dịch

Lần này chỉ tập trung vào một chủ đề cốt lõi:

**"Lệnh" trên OKX thực sự vận hành ra sao?**

Khi đã nắm rõ logic lệnh, thao tác trên cả spot và futures sẽ trở nên rõ ràng hơn nhiều.

## Mã mời OKX

**Mã mời:** OKOFFICIALLY
**Link đăng ký:** https://www.okx.com/join/OKOFFICIALLY

Sử dụng OKOFFICIALLY để đăng ký, bạn có thể nhận được hoàn phí giao dịch theo chương trình giới thiệu hiện hành của OKX (tối đa có thể theo mức 50%, tỷ lệ thực tế tuân theo trang OKX).

Tác dụng chính của hoàn phí là:

Giảm bớt một phần chi phí giao dịch.
Nếu sau này bạn thường xuyên có các thao tác mua, bán, mở lệnh, đóng lệnh, chốt lời, thì số lần giao dịch tăng lên, phí cũng sẽ tích lũy dần.

---

## 1. Trước khi đặt lệnh, hãy hiểu "khớp lệnh" là gì

Rất nhiều người mới nghĩ rằng:

"Bấm mua = Tôi đã mua được rồi."
Thực tế không hẳn vậy.

Một lệnh thường sẽ trải qua các bước:

**Gửi lệnh → Chờ → Khớp → Hoàn tất**

Các loại lệnh khác nhau sẽ quyết định:

Bạn sẵn sàng khớp ở mức giá nào, điều kiện gì.

Đó là lý do tại sao:

Market và Limit tuy đều có thể mua BTC,

nhưng logic sử dụng hoàn toàn khác biệt.

---

## 2. Lệnh Market (Thị trường) là gì?

Market Order｜Lệnh thị trường

Chỉ cần nhớ một câu:

**Ưu tiên khớp lệnh, không ưu tiên giá.**
Nghĩa là,

bạn đang nói với thị trường rằng:

"Tôi muốn hoàn tất giao dịch này ngay bây giờ."

Hệ thống sẽ thực hiện khớp lệnh theo giá có sẵn trên thị trường tại thời điểm đó.

---

## 3. Ưu điểm lớn nhất của lệnh Market là gì?

Ưu điểm rõ rệt nhất chính là:

**Nhanh.**

Ví dụ:

Bạn chuẩn bị mua BTC,

thanh khoản thị trường đang bình thường,

và bạn không muốn chờ đợi một mức giá cụ thể nào.

Lúc này lệnh Market thường dễ hoàn tất giao dịch nhanh chóng.

Phù hợp với:

- Muốn vào lệnh ngay lập tức
- Muốn thoát lệnh nhanh
- Không muốn chờ lệnh treo
- Thị trường có thanh khoản tốt

---

## 4. Rủi ro lớn nhất của lệnh Market: Trượt giá (Slippage)

Rất nhiều người mới thắc mắc:

"Tại sao giá tôi thấy và giá khớp cuối cùng không hoàn toàn giống nhau?"

Một trong những nguyên nhân là:

Slippage｜Trượt giá

Ví dụ:

Bạn thấy BTC đang ở mức:

70,000

Nhưng khi bạn gửi lệnh Market,

thị trường đang biến động rất nhanh.

Cuối cùng lệnh có thể được khớp ở các mức giá khác nhau như:

70,005
70,010
70,020

Sự chênh lệch này thường đáng chú ý hơn khi:

- Thị trường biến động mạnh
- Lệnh có kích thước lớn
- Thanh khoản thấp
- Độ sâu thị trường mỏng

OKX cũng có cơ chế bảo vệ giá tệ nhất cho lệnh Market, nhưng không có nghĩa là trượt giá bằng không.

---

## 5. Lệnh Limit (Giới hạn) là gì?

Limit Order｜Lệnh giới hạn

Logic của Limit là:

**Ưu tiên giá.**

Bạn tự quyết định:

"Tôi chỉ chấp nhận khớp ở mức giá này hoặc giá tốt hơn."

Ví dụ:

BTC hiện tại là:

70,000

Nhưng bạn muốn mua ở mức:

69,000

Bạn có thể thiết lập:

Buy Limit = 69,000

Chỉ khi thị trường giảm xuống vị trí thỏa mãn điều kiện, lệnh mới có cơ hội khớp.

Lệnh giới hạn có hai khả năng:

- Giá có thể khớp ngay lập tức → Khớp luôn, thuộc Taker
- Giá không thể khớp ngay → Treo vào sổ lệnh chờ, thuộc Maker

---

## 6. Tại sao Limit có thể mãi không khớp?

Bởi vì:

Thị trường chưa chắc đã chạm đến mức giá bạn đã thiết lập.

Ví dụ:

BTC hiện tại 70,000.
Bạn treo 68,000.
Kết quả BTC tăng thẳng lên 72,000.

Thì lệnh này sẽ không bao giờ khớp.

Vì vậy:

**Cái giá của Limit chính là sự chờ đợi.**

Nó giúp bạn kiểm soát giá, nhưng không đảm bảo chắc chắn sẽ khớp.

---

## 7. Sự khác biệt lớn nhất giữa Market và Limit

| Hạng mục | Market | Limit |
|---|---|---|
| Cốt lõi | Ưu tiên khớp | Ưu tiên giá |
| Có khớp ngay không | Thường nhanh hơn | Chưa chắc |
| Kiểm soát giá | Thấp hơn | Cao hơn |
| Có cần chờ không | Thường không | Có thể cần |
| Rủi ro chính | Trượt giá | Không khớp |
| Phù hợp | Muốn hoàn tất nhanh | Có giá mục tiêu rõ ràng |

Vì vậy không có loại nào tốt hơn mãi mãi.

Phải xem bạn thực sự cần là:

**Tốc độ khớp**
hay là:
**Kiểm soát giá.**

---

## 8. Lệnh treo (Resting order) là gì?

Khi bạn thiết lập một Limit,
nhưng thị trường chưa tới mức giá đó,
lệnh này sẽ ở trạng thái chờ.

Đây chính là cái gọi là:

**Lệnh treo.**

Ví dụ:

Giá hiện tại của BTC: 70,000
Bạn treo mua 69,000.

Trước khi giá chưa chạm tới, lệnh này sẽ tiếp tục chờ.

Khi khớp từ sổ lệnh → Maker
Khi ăn ngay lệnh trên sàn → Taker

---

## 9. Khi lệnh treo cần đặc biệt chú ý đến vốn

Rất nhiều người mới hay quên:

Lệnh đang treo cũng có thể chiếm dụng số dư hoặc hạn mức tương ứng.

Vì vậy nếu bạn treo rất nhiều lệnh, sau đó có thể phát hiện:

"Sao số dư khả dụng giảm rồi?"

Lúc này cần kiểm tra:

- Có lệnh chưa khớp không
- Có lệnh điều kiện không
- Có vị thế nào đang chiếm dụng ký quỹ không

Đừng chỉ nhìn vào tổng số dư tài khoản.

---

## 10. Khớp một phần (Partial Fill) là gì?

Một tình huống khác thường bị bỏ qua là:

Partial Fill｜Khớp một phần

Ví dụ:

Bạn muốn mua: 1 BTC
Nhưng lượng có sẵn trên thị trường thỏa mãn điều kiện giá của bạn chỉ có: 0.4 BTC

Thì có thể sẽ khớp trước: 0.4 BTC
Phần còn lại: 0.6 BTC sẽ tiếp tục chờ.

Vì vậy khi xem trạng thái lệnh, đừng chỉ nhìn:

"Đã khớp / Chưa khớp"
Mà còn phải chú ý:

"Đã khớp được bao nhiêu rồi."

Lệnh Market với khối lượng lớn cũng có thể bị khớp một phần, phần còn lại thường sẽ bị hủy theo cơ chế IOC, không tiếp tục treo.

---

## 11. Tại sao lệnh lớn càng cần chú ý đến khớp lệnh?

Nếu lệnh có kích thước lớn, bạn càng cần chú ý đến:

**Độ sâu thị trường.**

Bởi vì cùng một thời điểm, lượng có thể khớp ở một mức giá là có hạn.

Nếu bạn gửi một lệnh Market cực lớn,
có thể sẽ ăn hết các mức giá bán khác nhau.

Cuối cùng sẽ xuất hiện:

Giá khớp trung bình và giá bạn nhìn thấy ban đầu chênh lệch khá lớn.

Vì vậy khi giao dịch khối lượng lớn,
"Giá khớp" bản thân nó đã là một phần của rủi ro.

---

## 12. Giá mua một (Bid) và giá bán một (Ask) là gì?

Trên trang giao dịch thường thấy:

**Bid**: Giá người mua sẵn sàng trả.
**Ask**: Giá người bán sẵn sàng chấp nhận.

Gần với thị trường nhất là:

Giá mua cao nhất (mua 1)
và
Giá bán thấp nhất (bán 1)

Giữa chúng sẽ có một khoảng cách.

Đây chính là:

Spread｜Chênh lệch giá mua bán

Thị trường càng sôi động, spread thường càng nhỏ;
Khi thanh khoản kém, spread càng dễ nới rộng.

---

## 13. Tại sao cùng là BTC, nhưng lúc khớp lại có cảm giác khác nhau?

Bởi vì điều kiện thị trường luôn thay đổi.

### Thị trường bình ổn
Thường thì:

- Trượt giá tương đối dễ kiểm soát
- Spread tương đối ổn định
- Khớp lệnh bình thường

### Thị trường biến động mạnh
Có thể xuất hiện:

- Giá nhảy nhanh
- Spread nới rộng
- Trượt giá tăng
- Lệnh khớp ngay lập tức ở nhiều mức giá khác nhau

Vì vậy:

**Cần xem xét loại lệnh cùng với môi trường thị trường.**

---

## 14. Hiểu thế nào về Take Profit (Chốt lời)?

Take Profit｜Chốt lời

Cốt lõi là:

Khi giá đạt đến điều kiện đã cài đặt trước, giúp bạn thực hiện việc thoát lệnh.

Ví dụ:

Bạn mua BTC ở mức: 68,000
Mục tiêu của bạn là: 72,000

Vậy bạn có thể cài đặt logic chốt lời trước.

Lợi ích lớn nhất là:

Không cần phải dán mắt vào giá để chờ.

---

## 15. Hiểu thế nào về Stop Loss (Cắt lỗ)?

Stop Loss｜Cắt lỗ

Tác dụng là:

Khi giá đi đến vị trí không còn phù hợp với dự đoán ban đầu, thực hiện thoát lệnh.

Ví dụ:

Bạn mua BTC ở mức 68,000.
Nếu bạn cho rằng khi phá vỡ mức 66,500 thì logic ban đầu đã mất hiệu lực,
thì bạn có thể cài đặt quy tắc cắt lỗ trước đó.

---

## 16. Chốt lời / Cắt lỗ không đảm bảo khớp chính xác

Điểm này cực kỳ quan trọng.

Rất nhiều người mới thường nghĩ:

"Tôi đặt 66,500, thì chắc chắn sẽ khớp ở 66,500."
Chưa chắc.

Chốt lời / cắt lỗ thuộc loại lệnh điều kiện:
Đầu tiên có giá kích hoạt, sau khi kích hoạt mới gửi lệnh ủy thác vào thị trường.

Giá khớp thực tế sau khi kích hoạt có thể bị ảnh hưởng bởi:

- Tốc độ thị trường
- Thanh khoản
- Loại ủy thác (Market / Limit)
- Độ sâu sổ lệnh

Vì vậy:

**Giá kích hoạt ≠ Chắc chắn là giá khớp cuối cùng.**

---

## 17. Giá kích hoạt và giá khớp là hai chuyện hoàn toàn khác

Có thể chia đơn giản thành:

**Trigger Price｜Giá kích hoạt**
Dùng để quyết định: Khi nào khởi động lệnh.

**Execution Price｜Giá khớp**
Giá thực sự khớp thành công.

Nếu bạn chọn:

- Ủy thác Market: Sau khi kích hoạt sẽ đặt lệnh theo giá tốt nhất trên thị trường
- Ủy thác Limit: Sau khi kích hoạt sẽ treo mức giá bạn chỉ định

Cách khớp cuối cùng của hai loại này là khác nhau.

Vì vậy có một số lệnh điều kiện sau khi kích hoạt, giá khớp và con số bạn thấy ban đầu không giống nhau, điều đó không nhất thiết là lỗi.

---

## 18. Tại sao lệnh điều kiện lại quan trọng với người mới?

Bởi vì nó giúp bạn:

Đưa câu "Nếu... thì..." vào giao dịch từ trước.

Ví dụ:

- Nếu BTC giảm đến một mức giá nào đó → Thì cắt lỗ
- Nếu BTC tăng đến một mức giá nào đó → Thì chốt lời

Điều này dễ duy trì kỷ luật hơn là khi giá thực sự biến động rồi mới bắt đầu quyết định tình thế: "Giờ nên bán không?"

---

## 19. Đừng nhầm lẫn giữa lệnh mở vị thế và lệnh đóng vị thế

Đặc biệt là trong giao dịch hợp đồng.

Một lệnh có thể là:

- Tăng vị thế
- Giảm vị thế
- Đóng vị thế

Nếu không nhìn kỹ, có thể bạn vốn chỉ muốn đóng bớt vị thế,
nhưng lại vô tình tạo ra rủi ro định hướng mới.

Vì vậy trước khi đặt lệnh trên trang hợp đồng, cần xác nhận:

- Hướng (mua/bán)
- Khối lượng
- Có phải giảm vị thế không
- Có phải đóng lệnh không
- Trạng thái vị thế hiện tại

---

## 20. Lệnh hợp đồng rủi ro hơn spot một lớp

Spot chủ yếu quan tâm đến:

- Giá mua
- Giá bán

Hợp đồng thì còn phải xem thêm:

- Quy mô vị thế
- Đòn bẩy
- Ký quỹ
- Giá thanh lý
- Stop Loss
- Funding Rate (Phí funding)

Vì vậy dù logic cơ bản của Market và Limit là giống nhau,
nhưng rủi ro tổng thể của hợp đồng vẫn phức tạp hơn.

---

## 21. Đừng coi thanh lý (Liquidation) như là Stop Loss

Đây là điểm cực kỳ quan trọng.

Liquidation｜Thanh lý
Không phải là công cụ quản trị rủi ro bình thường.

Nếu đợi đến khi bị thanh lý mới thoát lệnh, thường đại diện cho rủi ro đã quá cao.

Hợp lý hơn là:

Trước khi bị thanh lý, bạn đã có Stop Loss của riêng mình.

---

## 22. Làm sao để tránh đặt nhầm lệnh?

Mỗi lần trước khi gửi lệnh, hãy kiểm tra nhanh:

1. Cặp giao dịch có đúng không?
2. Spot hay Futures?
3. Buy hay Sell?
4. Long hay Short?
5. Market hay Limit?
6. Giá có bị thừa một số 0 không?
7. Khối lượng có chính xác không?
8. Stop Loss đã được thiết lập chưa?

Chỉ cần thêm mười giây, bạn có thể tránh được rất nhiều lỗi thao tác thuần túy.

---

## 23. Người mới có thể tập luyện như thế này

Nếu bạn chỉ muốn làm quen với logic đặt lệnh trên OKX, có thể bắt đầu từ:

**Spot với số tiền nhỏ**

Ví dụ:

1. Tìm BTCUSDT
2. Xem Bid / Ask
3. Đặt một lệnh Limit nhỏ
4. Quan sát lệnh treo
5. Hủy một lần lệnh
6. Dùng lệnh Market nhỏ
7. So sánh hai cách khớp lệnh

Như vậy rất dễ hiểu rõ thực sự sự khác biệt giữa Market và Limit.

---

## 24. Đừng đồng thời treo quá nhiều lệnh không có logic

Một số người mới sẽ treo lệnh ở:

68,000
67,500
67,000
66,500
66,000

Nhưng bản thân họ cũng không nói rõ:

Tại sao mỗi mức giá đều phải mua.

Lệnh treo thực sự hợp lý cần có:

- Lý do về giá
- Giới hạn vốn
- Tổng vị thế tối đa
- Điều kiện hủy lệnh

Nếu không, treo quá nhiều lệnh chỉ khiến rủi ro khó quản lý hơn.

---

## 25. Phí giao dịch cũng liên quan đến tần suất đặt lệnh

Nếu thường xuyên:

- Treo lệnh
- Khớp lệnh
- Đóng lệnh
- Vào lại
- Chốt lời từng phần
- Giao dịch lướt sóng liên tục

Thì chi phí giao dịch sẽ tích lũy dần.

Sử dụng:

OKOFFICIALLY
Thông qua:
https://www.okx.com/join/OKOFFICIALLY

Đăng ký, có thể nhận hoàn phí giao dịch theo chương trình hiện hành của OKX.

Hoàn phí có thể giảm bớt một phần chi phí giao dịch,
nhưng thường không phải là trừ phí trực tiếp khi đặt lệnh, mà là hoàn lại theo quy tắc sau khi khớp lệnh.

Nhưng nó không thể thay thế cho:

- Đặt lệnh đúng cách
- Quản trị rủi ro
- Stop Loss
- Kiểm soát vị thế

---

## FAQ

**Q1: Market trên OKX là gì?**
Market là lệnh thị trường, mục tiêu chính là khớp nhanh chóng theo giá thị trường có sẵn hiện tại.

**Q2: Limit trên OKX là gì?**
Limit là lệnh giới hạn, bạn có thể tự thiết lập mức giá mong muốn để khớp.

**Q3: Tại sao Limit mãi không khớp?**
Thông thường là do giá thị trường chưa chạm đến mức giá bạn đã đặt, hoặc lượng có thể khớp tại mức giá đó không đủ.

**Q4: Tại sao giá khớp của lệnh Market lại khác với giá hiển thị?**
Có thể bị ảnh hưởng bởi biến động thị trường nhanh, trượt giá, thanh khoản và kích thước lệnh.

**Q5: Đặt Stop Loss ở mức giá đó, thì chắc chắn sẽ khớp ở đó chứ?**
Chưa chắc. Giá kích hoạt và giá khớp cuối cùng là hai khái niệm khác nhau.

**Q6: Mã mời OKX là gì?**
OKOFFICIALLY
Link đăng ký: https://www.okx.com/join/OKOFFICIALLY

**Q7: OKOFFICIALLY có ưu đãi gì?**
Có thể nhận hoàn phí giao dịch theo chương trình giới thiệu hiện hành của OKX, tỷ lệ thực tế theo trang OKX.

---

## Bảng tóm tắt nhanh các loại lệnh trên OKX

| Hạng mục | Tác dụng cốt lõi |
|---|---|
| Market | Ưu tiên khớp nhanh |
| Limit | Ưu tiên kiểm soát giá khớp |
| Stop Loss | Cài đặt điều kiện thoát rủi ro |
| Take Profit | Cài đặt điều kiện thoát lãi |
| Trigger Price | Điều kiện khởi động lệnh |
| Execution Price | Giá khớp thực tế |
| Partial Fill | Lệnh chỉ khớp một phần số lượng |
| Spread | Khoảng cách giữa giá mua và giá bán |
| Slippage | Chênh lệch giữa giá kỳ vọng và giá thực tế |
| Điểm trọng tâm cho người mới | Hiểu rõ lệnh trước, rồi mới tăng tần suất giao dịch |

---

## Lưu ý rủi ro

- Lệnh Market có thể bị ảnh hưởng bởi trượt giá
- Lệnh Limit không đảm bảo chắc chắn khớp
- Giá khớp thực tế sau khi kích hoạt chốt lời/cắt lỗ có thể khác
- Giao dịch hợp đồng liên quan đến đòn bẩy, ký quỹ và thanh lý
- Lệnh khối lượng lớn càng cần chú ý đến độ sâu thị trường và giá khớp
- Trước khi đặt lệnh nên xác nhận lại hướng, giá và khối lượng
- Hoàn phí chỉ có thể giảm bớt một phần chi phí giao dịch, không đảm bảo có lãi

---

## Tổng kết cuối cùng

Thực sự sử dụng thành thạo OKX, không chỉ là biết:

"Nhấn nút nào để mua BTC."

Mà còn phải biết:

Tại sao lệnh này lại khớp, khi nào nó khớp, và có thể khớp ở mức giá nào.

Nếu bạn là người mới, hãy học hiểu 4 logic lệnh cơ bản nhất này trước:

**Market → Limit → Stop Loss → Take Profit**

**Mã mời OKX: OKOFFICIALLY**
**Link đăng ký: https://www.okx.com/join/OKOFFICIALLY**
