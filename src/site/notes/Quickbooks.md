---
{"dg-home":null,"dg-publish":true,"permalink":"/quickbooks/","dgPassFrontmatter":true,"noteIcon":""}
---

# Reference
Pro-advisor academy : Quickbook (cần tk công ty -> để sử dụng phần mềm kế toán)
https://proadvisoracademy.app.intuit.com/home
Sách : 
https://learning.oreilly.com/library/view/mastering-quickbooks-2020/9781789955101/
![Pasted image 20250807080823.png](/img/user/Pasted%20image%2020250807080823.png)
# Setting 
![Pasted image 20250806221056.png](/img/user/Pasted%20image%2020250806221056.png)
Customer : create invoices, sales receipts -> customer payment
Vendors : record expense, write checks, track unpaid bills, create PO
Employees : payroll related tasks, add new employees, employees deduction, run payrolls, payroll tax payments
Other : bank deposit, bank transfer, journal entries, customer statements, inventory adjustment


# Company set up
Step 1 : Set up your company and entity 
1. sole proprietorship : one owner, unlimited liability
2. partnership : 2 or more owners
3. limited liability : one or more owner, not personally liable
4. C-Corp : tax separately from its owner
5. S-Corp : 

Step 2 : Billing and subscription 
![Pasted image 20250806221615.png](/img/user/Pasted%20image%2020250806221615.png)
![Pasted image 20250806221637.png](/img/user/Pasted%20image%2020250806221637.png) 

# Add vendors 
Manual add vendors in QBO : Expense -> select vendors -> new vendors (create new vendor)
![Pasted image 20250806221838.png](/img/user/Pasted%20image%2020250806221838.png)**Inactive vendors in QBO**
![Pasted image 20250806221926.png](/img/user/Pasted%20image%2020250806221926.png)

# Record Sales transactions
1. Sales form : sales receipts, deposits, sales invoices 
2. Payment received from customers
3. Credit memos, refund
## Sales Receipts
![Pasted image 20250806222208.png](/img/user/Pasted%20image%2020250806222208.png)
![Pasted image 20250806222232.png](/img/user/Pasted%20image%2020250806222232.png)

## Receive payment
![Pasted image 20250806222519.png](/img/user/Pasted%20image%2020250806222519.png)
## Credit memo
![Pasted image 20250806222553.png](/img/user/Pasted%20image%2020250806222553.png)

# Record Expenses 
## Enter , pay bills
show due of payables bill, you can plan, and budget 
**enter bill :** bill -> vendor name -> mailing address, term (net 30, net 45, net 60,...), due date, category, description, amount
**pay bill** : vendors -> pay bills -> payment account, payee, payment date, ...
![Pasted image 20250806222933.png](/img/user/Pasted%20image%2020250806222933.png)
## Recurring expense
Purchase from same vendors -> create a recurring expense (mostly pay bills for electricity, rent, utilities)
![Pasted image 20250806223240.png](/img/user/Pasted%20image%2020250806223240.png)
## Write checks
![Pasted image 20250806223317.png](/img/user/Pasted%20image%2020250806223317.png)
# Bank 
![Pasted image 20250806223510.png](/img/user/Pasted%20image%2020250806223510.png)
Bank account : name of account (Mastercard, Checking, Savings)
Bank balance : the bal of account 
Transactions for review : pending for review

## Set up bank rules: 

## Matching transactions
To check if the transactions have been recorded or any related transactions (HĐ đã được nhập từ trước đó -> thường là các khoản payable chi trả theo dạng accrued expense các subscription, hđ tiền điện, nước,... ) 
-> lúc categorize (dò với bank statement) sẽ có hiện thông tin các khoản trùng lặp 
-> có thể nhấn find other record : để kiểm thử là có bill nào trùng ?
Thứ tự : 
1. kiểm tra xem thử date có trùng hem (thường cách 2-3 ngày nếu rơi vào cuối tuần)
2. kiểm tra số tiền, kiểm tra vendor và match nếu thấy khớp -> trả tiền cho kì thanh toán -> kiểm tra trên balance sheet, khoản accrued expense
![Pasted image 20250806223722.png](/img/user/Pasted%20image%2020250806223722.png)
## Reconcile 
![Pasted image 20250806224335.png](/img/user/Pasted%20image%2020250806224335.png)
Này là dùng để reconcile : nôm na dễ hiểu là ending balance = beg (số từ đợt reconcile trước) - payment + deposit = 0 (closing balance) -> nghĩa là đã categorize hết transaction
TH mà closing balance # 0 -> có thể hiểu là bạn chưa categorize hết transaction (cũng có thể do bank statement thì là nhận giữa tháng còn bank nó chảy transaction về chưa hết), hoặc là do bạn nhập sai amount, hoặc date 
-> cách dễ nhất : bạn bấm vô chỗ finish now dấu mũi tên đi xuống -> sửa lại thông tin đúng -> done
Có 2 điểm cần lưu ý 
1. Phải điền đúng số amt của ending bal 
2. Phải điền đúng ngày : date 
Cleared balance : đơn giản là các khoản đã được Quickbook categorize có đủ tên vendor và categorize rồi (có 1 số khoản sẽ bị coi là uncleared)
Thường lúc categorize, phải cẩn thận với mấy cái credit card, vì dễ bị nhầm thẻ -> có thể dẫn tới tình trạng là reconcile bị sai . Ví dụ : thẻ A có thẻ con 1,2,3 -> match với credit card B -> thì lúc reconcile sẽ bị miss số tiền đó vào thẻ khác và có hiện lên 1 transaction lạ (# so với statement) -> xui hơn, nó sẽ hiện lên report (error)
-> một điểm cần để tâm với reconcile chính là set up bank card. Vì sao ? Thường client sẽ xài nhiều hơn 1 thẻ, và có trường hợp ông B là người phụ trách thẻ -> nhưng ổng đưa thẻ cho nhân viên A, B,C tách làm thẻ phụ liên kết thẻ chính (để thanh toán các hoá đơn công tác). Vì thế lúc reconcile, thì hãy reconcile thẻ phụ -> rồi sau đó làm bút toán kết chuyển từ thẻ phụ (gọi là tạo giao dịch để đóng sổ vì nếu không thì số reconcile sẽ không bằng 0)
Ví dụ : thẻ con của ông B reconcile hết 300 đô -> thì ở thẻ chính phải tạo 1 bút toán là write off 300 đô từ thẻ phụ để khoá sổ . Lúc reconcile sẽ = 0

## Report center 
![Pasted image 20250806225627.png](/img/user/Pasted%20image%2020250806225627.png)

## Customer Aging Report 
![Pasted image 20250806225743.png](/img/user/Pasted%20image%2020250806225743.png)
![Pasted image 20250806225812.png](/img/user/Pasted%20image%2020250806225812.png)
AR Aging summary : TÌnh hình khoản phải thu khách hàng -> ở Vn sẽ có sổ chi tiết khoản phải thu gọi là 131 - và theo dõi đối tượng 331 (nếu mình k nhớ lầm) dùng để track. 
Ví dụ ở đây sẽ chia ra là tên khách hàng -> due date -> total amount. Thường nó sẽ cần 1 bảng đối chiếu là file excel để theo dõi nữa vì bảng này chỉ là các invoices đã được nhập trước đó , có thể sẽ bị sót 

## Payroll 
![Pasted image 20250806230235.png](/img/user/Pasted%20image%2020250806230235.png)
## 1099 Report 
Freelance 600$ trở lên, nộp thuế cho IRS (Bài này mình đã có share rồi) : [[Guideline KT Quốc Tế\|Guideline KT Quốc Tế]]
-> lí do mình k đề cập sâu hơn vì mấy cái này mình k có đụng tay vào, và chủ yếu chỉ có từ cấp senior trở lên thì mới làm. Tuy nhiên, các bạn có thể lên youtube search, mình hay theo dõi a Hector Garcia (cựu CPA) làm các youtube khá hay ho hướng dẫn. 

**Một phần nữa mình muốn nhắc tới, gọi là closing entry : thường sẽ làm với kì đóng sổ cho khách (adjusted trial balance)**
Thường là các khoản mục như assets, accrued expense, prepaid expense -> nó sẽ được ghi nhận trước -> thế nên lúc đóng sổ, cần phải có 1 bút toán để có thể write off 
**Mình ví dụ : 
Bút toán accrued expense** : ví dụ minh hoạ sẽ có sau
-> Ghi nhận là Cr: Accrued expense, Dr : Accrued liability
thì khi truy cập vô balance sheet -> mục accrued expense sẽ có 1 list các transaction (bao gồm trả và chưa trả) -> cuối tháng bạn phải ngồi check mail các hoá đơn, và tiến hành match với invoice và làm 1 bút toán reverse lại. 


**Bút toán LQ -> CP khấu trừ (depreciation)** : ví dụ minh hoạ sẽ có sau
Bước 1 : Lập schedule of depreciation fixed asset -> thường mình thấy đa phần sử dụng PP đường thẳng (straightline method = giá của MM-savage value/useful lives) 
Bước 2 : Bút toán chi phí khấu hao -> làm tuần tự với các tháng tiếp theo
DR : depreciation expense
CR : acc. Depreciation expense
Bước 3 : Write-off JE vào trong system 
DR : Acc. Depreciation : 
CR: PPE carrying amount : The amount purchase - Acc Depreciation (ở kì tổng kết)

Lưu ý : 
Trên Quickbook có rất nhiều tính năng như timing, payroll, và lập cả được CF. Tuy nhiên các khách hàng mình từng được đụng vào sổ sách thì mình thấy họ sẽ chỉ sử dụng là BS, IS. Payroll thì thường có phần mềm riêng và họ chỉ dùng để track time in - time out. 

Các phần mềm lương : Gusto (mình thấy cũng rất phổ biến), tuy nhiên, các bạn mà vô làm thì cũng sẽ biết thôi (đa phần các anh chị mình thấy họ đều bận rộn với sổ sách của họ nên là tự tra youtube và tự học)

## Test drive QBO
Các bạn nào mới vô, chưa được cấp tk Quickbook (chủ yếu do là phải có permission từ khách hàng) thì không cần lo lắng vì QBO cho phép người dùng được trải nghiệm trước khi mua sp. Và các bạn có thể vô 2 đường link này để có thể test trước. 

Test drive QBO: [https://qbo.intuit.com/redir/testdrive](https://qbo.intuit.com/redir/testdrive).
QBO Advanced: [https://qbo.intuit.com/redir/testdrive_us_advanced](https://qbo.intuit.com/redir/testdrive_us_advanced).

**Conclusion** : Đây chỉ là công việc cơ bản của vị trí Kế toán quốc tế - nó sẽ có những thứ khác nữa, tuỳ vào nhu cầu khách kí hđ với bên mình sẽ có lượng công việc cụ thể 
Ví dụ : mình từng thấy có 1 nhóm project họ chỉ làm mỗi công việc tải bill -> xong rồi lấy dữ liệu, hoặc là có 1 nhóm khác họ sẽ làm các công việc đặc thù khác. Nếu phức tạp hơn, nó có thể liên quan về thuế, hoặc là các bạn sẽ làm thêm nhiều khách để giúp họ đóng sổ. 1 số task sẽ có liên quan đến kĩ năng phân tích : CF analysis, sales tracking report (chủ yếu cũng chỉ là pivot table -> tổng kết sales theo từng đối tượng). 

Nếu lằng nhằng hơn nữa, thì có thể là khách sẽ giao tk trống để phải tự set up và cài rules, hoặc là các bạn sẽ phải làm về tax report. Công việc được giao là ngồi pull report về, check số dư và giải thích đc tại sao có lệch số). Mình khuyên là các bạn dùng pivot table -> lọc và tìm để dễ tra ra đối tượng

Ừm, cái chính, là deadline, vì các cty dịch vụ họ yêu thích tốc độ, nên là cần khách hàng hài lòng, thế nên, mình quan sát là các bạn trong đó sẽ có thao tác chuột, bấm phím tắt nhanh. Để có thể lí giải, hãy nhớ tới IFRS 15 - Performance. Làm dịch vụ -> accured expense (cung cấp dịch vụ, và khách hàng đánh giá trên performance obligation riêng lẻ -> ảnh hưởng đến thời gian và dthu). Vì thế, việc làm hài lòng khách ở dịch vụ cung cấp chất lượng và thời gian là điều quan trọng. 

Còn về team, các bạn mới vào sẽ thường hay bị test các câu hỏi liên quan về kiến thức (chủ yếu là cách tính inventory cuối kì, disposal fixed asset,...hoặc hỏi về bút toán từ các senior hoặc là người đã vô trước đó). Các bạn hãy hình dung là các bạn là Tài sản cty -> và để đo lường được giá trị kinh tế thì người thuê sẽ phải đo đạc lại theo tiến độ để có thể đánh giá được về performance, khoản suy giảm giá trị để từ đó có thể ước lượng estimate được giá trị (IAS 8, IAS 16 -> hồi tố) -> khoản suy giảm giá trị không được cao hơn so với khoản provision của DN -> sẵn ôn lại kiến thức nhá. 

Nói chung, đó là 1 số quan sát và tích luỹ trong 1 thời gian ngắn làm vị trí kế toán dịch vụ. Nó giúp mình có thêm sự quan sát về nghề kế toán - học cách phân chia công việc và quản lí thời gian - và học cách hoà nhập môi trường đa văn hoá và dạy cho mình nhiều "bài học cuộc sống"



