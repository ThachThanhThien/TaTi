https://github.com/chiangs/InventoryMGRSpringMVCCRUD

CHƯƠNG 2: NộI DUNG THựC TậP
Đợt thực tập với chủ đề “Lập trình ứng dụng Android và xây dựng NodeJS Server” nhằm mục đích giúp sinh viên thực tập được đào tạo về lập trình Android và NodeJS, đồng thời rèn luyện những kỹ năng mềm như làm việc nhóm, giao tiếp. Tại Fujinet, sinh viên có cơ hội được học tập, khám phá và làm việc trong một môi trường phát triển phần mềm chuyên nghiệp.

1.	Tìm hiểu cơ chế vận hành công ty và các chuẩn mực liên quan
Thời gian : 2 ngày
Nội dung : Giới thiệu về công ty, cách tổ chức của công ty
-	Được anh Lê Hoàng Phúc giới thiệu về công ty, khối phát triển phần mềm, team, quy trình làm việc từ cao xuống thấp, cách thức tổ chức của công ty.
-	Được giới thiệu về cách thức làm việc trong công ty như thời gian đi làm, các quy định cần phải tuân thủ, cách sử dụng email trong công việc, điểm danh, check in/checkout…
Kết quả: Hiểu thêm về cách tổ chức của một công ty là như thế nào. Có thêm các kĩ năng làm việc như gửi mail, cách hỏi và đặt vấn đề,… giúp cho em tự tin hơn trong những thời gian làm viêc sau này.

2.	Nghiên cứu kỹ thuật
2.1.	Giai đoạn 1: Xây dựng ứng dụng Android
2.1.1.	Cài đặt, làm quen các công cụ làm việc
Thời gian : 4 ngày
Nội dung : Được hướng dẫn cài đặt và sử dụng các công cụ mà công ty dùng để làm việc nhóm, chia sẻ Source Code nội bộ, Đọc hiểu Design và lấy các thông số liên quan.
-	Kênh thông tin làm việc nhóm: Spark, Thunderbird.
-	Chia sẻ Source Code : TortoiseSVN.
-	Phần mềm code: Android Studio là IDE phổ biến cho lập trình viên Android
-	Phần mềm xem API: Postman
-	Đọc thêm các tài liệu liên quan đến quy chuẩn code, quy tắc đặt tên biến của công ty
Thực hiện : Thực hành sử dụng các phần mềm đã nêu trên.
Kết quả : Hiểu thêm về những phần mềm liên quan tới công việc của công ty. Biết thêm những quy tắc lập trình, cách chia sẻ code của mình với team, cách đọc một bản design hay xem 1 API và ứng dụng nó như thế nào.
 
2.1.2.	Nghiên cứu bản thiết kế, chỉ thị
Thời gian : 3 ngày
Nội dung : Nghiên cứu bản thiết kế chi tiết của ứng dụng Tippin, các luồng dữ liệu, luồng xử lý, thiết kế các màn hình, các hiệu ứng, animation…
Kết quả: Hiểu được chi tiết ứng dụng, cách thiết kế, xử lý các thành phần trong ứng dụng…
2.1.3.	Nghiên cứu tài liệu và những kỹ thuật.
Thời gian : 7 ngày
Nội dung : Được giao và tìm hiểu về những tài liệu và kỹ thuật liên quan đến dự án. Các tài liệu bao gồm:
-	MVVM design pattern: Model – View – ViewModel. MVVM được phát triển dựa trên kiến trúc MVP, có cấu trúc khá tương đồng. MVVM thực hiện abtract trạng thái và thể hiện của View, cho phép chúng ta phân tách rõ ràng việc phát triển giao diện với xử lý business logic. MVVM đã kế thừa những ưu điểm vốn có của MVP, kết hợp với những lợi thế của data binding đem đến một pattern có khả năng phân chia các thành phần với từng chức năng riêng biệt, dễ dàng trong việc maintain, redesign. MVVM cũng đem lại khả năng test rất dễ dàng. Model là tầng định nghĩa các lớp tương tác với CSDL ( đối với các ứng dụng CSDL ) , hay các lớp lưu trữ thông tin chung để tương tác trong ứng dụng đối với các ứng dụng bất kỳ. View là tầng giao diện. ViewModel là tầng trung gian giữa View và Model làm nhiệm vụ chính điều phối giữ liệu giữa View  và Model để thực hiện các thao tác xử lý như thêm, sửa , xóa , đọc
-	Observer design pattern: Là một design pattern thiết lập sự phụ thuộc một - nhiều giữa các đối tượng. Bất cứ khi nào trạng thái của một trong các đối tượng ("subject" hoặc "observable") thay đổi, tất cả các đối tượng khác ("observers") phụ thuộc vào nó sẽ được thông báo. Subject ít biết về các observers của nó. Điều duy nhất nó biết là các observers thực hiện hoặc đồng ý với một interface nhất định. Các Subjects có thể được sử dụng lại mà không có sự tham gia của các observers, và cũng tương tự đối với các observers. Không sửa đổi nào được thực hiện cho đối tượng để chứa một observer mới. Observer mới chỉ cần thực hiện một interface mà Subject nhận thức được và sau đó đăng ký tới subject. Một observer có thể được đăng ký cho nhiều subject mà nó được đăng ký.
-	Butter Knife: Thư viện Android ButterKnife là một thư viện view injection nó tác động đến các view trong activity, fragment bằng việc sử dụng annotations: @BindView, @BindBool, @BindColor, @BindDimen, @BindDrawable, @BindInt, @BindString
Thực hiện :
-	Tham gia đầy đủ các buổi training của công ty.
-	Làm các bài thực hành, kiểm tra về kiến thức đã học.
Kết quả :
-	Nâng cao kỹ năng lập trình Android
-	Tạo được những ứng dụng demo đơn giản về kỹ thuật đã nghiên cứu.
-	Có được những kiến thức quan trọng cho việc lập trình sau này.
-	Ngoài ra còn được biết thêm một số quy tắc trong việc viết code sao cho đúng chuẩn, dễ đọc, dễ hiểu.

2.1.4.	Nghiên cứu source code của Tippin
Thời gian: 3 ngày
Nội dung: Nghiên cứu source code của Tippin, tìm hiểu cách các kỹ thuật được áp dụng trong project, cách áp dụng các quy chuẩn code vào project, cách tổ chức project…
Kết quả: Hiểu trực quan các xử lý trong project, cách tổ chức project, các quy chuẩn code, … 
2.1.5.	Lập trình trên Android
Thời gian: 30 ngày
Nội dung : Áp dụng các kiến thức đã tìm hiểu, thực hành mô phỏng lại project.
-	Đọc hiểu thiết kế ứng dụng
-	Nắm luồng xử lý
-	Thiết kế các giao diện, màn hình của project. Tạo các Customview cho project.
-	Thiết kế các xử lý logic cơ bản, chuyển màn hình trong project
Kết quả:
-	Mô phỏng lại được project theo code của bản than
-	Nâng cao khả năng lập trình Android và các kỹ năng liên quan, bổ trợ cho quá trình sau này.
 
2.2.	Giai đoạn 2: Xây dựng NodeJS Server
2.2.1.	Tìm hiểu và cài đặt NodeJS
Thời gian: 3 ngày
Nội dung: Do khối lượng công việc giảm, thêm vào đó team sắp nhận thêm dự án về NodeJS nên team leader đã phân công công việc tìm hiểu thực hành trước NodeJS để có thể hỗ trợ cho dự án sau này. Các công việc được giao là:
-	Cài đặt NodeJS
-	Cài đặt MogoDB
-	Thực hành demo một server NodeJS kết hợp với MongoDB và Google Map API cho phép người dung tìm kiếm các địa điểm, chỉ đường từ vị trí này đến vị trí kia, đo khoảng cách giữa các địa điểm.
2.2.2.	Nghiên cứu tài liệu  và các kỹ thuật
Thời gian: 7 ngày
Nội dung:
-	Express Framework: Express là một framework giành cho nodejs. Nó cung cấp cho chúng ta rất nhiều tính năng mạnh mẽ trên nền tảng web cũng như trên các ứng dụng di động. Express hỗ rợ các phương thức HTTP và midleware tạo ra môt API vô cùng mạnh mẽ và dễ sử dụng. Có thể tổng hợp một số chức năng chính của express như sau: Thiết lập các lớp trung gian để trả về các HTTP request. Định nghĩa router cho phép sử dụng với các hành động khác nhau dựa trên phương thức HTTP và URL. Cho phép trả về các trang HTML dựa vào các tham số.
-	RESTful APIs: REST là viết tắt của Representational State Transfer. Giải thích đơn giản, REST là một loạt hướng dẫn và dạng cấu trúc dùng cho việc chuyển đổi dữ liệu. Thông thường, REST hay được dùng cho ứng dụng web, nhưng cũng có thể làm việc được với dữ liệu phần mềm. 
API viết tắt của Application Programming Interface , tạm dịch là Giao diện lập trình ứng dụng, nghĩa là một phương thức để tạo các giao tiếp giữa các ứng dụng phần mềm khác. 
Nhìn chung, RESTful API là những API đi theo cấu trúc REST. 
Người dùng API có thể build một script kết nối đến một API server, rồi dữ liệu cần thiết sẽ chuyển sang HTTP. Lập trình viên khi đó có thể hiển thị dữ liệu lên website mà không cần đến truy cập cá nhân vào server, có bốn phương thức cơ bản dùng để truy cập RESTful API:
	GET để truy vấn object
	POST để tạo object mới
	PUT để sửa đổi hoặc thay thế một object
	DELETE để loại bỏ một object
Mỗi phương thức trên phải được API call thông qua để gửi chỉ thị cho server phải làm gì.
Đại đa số web API chỉ cho phép GET request lấy dữ liệu khỏi một server. Hoặc web API phải thực hiện Authencation nếu không người sử dụng có thể sử dụng các lệnh khá “nguy hiểm” như PUT hay DELETE.
-	Mongoose: Mongoose là một thư viện mô hình hóa đối tượng (Object Data Model - ODM) cho MongoDB và Node.js. Nó quản lý mối quan hệ giữa dữ liệu, cung cấp sự xác nhận giản đồ và được sử dụng để dịch giữa các đối tượng trong mã và biểu diễn các đối tượng trong MongoDB. Mongoose cung cấp một số lượng đáng kinh ngạc các chức năng cho việc tạo ra và làm việc với các schema. Mongoose hiện có 8 SchemaTypes. Đó là: String, Number, Date, Buffer, Boolean, Mixed, ObjectId, Array. Khi một schema được định nghĩa, Mongoose cho phép tạo một Model dựa trên một schema cụ thể. Model của Mongoose sau đó được ánh xạ tới một MongoDB document thông qua định nghĩa schema của Model. Khi đã xác định xong các schema và model, Mongoose chứa nhiều hàm khác nhau cho phép xác thực tính hợp lệ, lưu, xóa và truy vấn dữ liệu bằng các hàm MongoDB phổ biến.
Callback: Callback function có thể được hiểu nôm na là một function A được truyền vào một function B thông qua danh sách các tham số của B. Lúc này tại hàm B sẽ gọi đến hàm A để thực hiện một chức năng nào đó mà A đang nắm giữ. Javascript là một ngôn ngữ lập trình hướng sự kiện và bất đồng bộ nên callback function đóng vai trò rất quan trọng, bạn sẽ truyền một callback function vào các sự kiện và xử lý bất đồng bộ đó.   
Thực hiện :
-	Làm các bài thực hành, kiểm tra về kiến thức đã học.
Kết quả :
-	Nâng cao kỹ năng lập trình NodeJS
-	Tạo được những ứng dụng demo đơn giản về kỹ thuật đã nghiên cứu.
-	Có được những kiến thức quan trọng cho việc lập trình sau này.
2.2.3.	Thực hành xây dựng server theo yêu cầu
Thời gian: 15 ngày
Nội dung: Thực hành xây dựng một NodeJS server theo yêu cầu của team leader
Kết quả: Xây dựng được một NodeJS server cơ bản đáp ứng các yêu cầu đặt ra.
3.	Lịch làm việc
Tuần	Công việc	Người hướng dẫn	Mức độ hoàn thành	Nhận xét của người hướng dẫn
1	-	Tìm hiểu về công ty, cách tổ chức của công ty.
-	Làm quen với các công cụ làm việc trong công ty.
-	Học cách trao đổi, làm việc nhóm.	Anh Lê Hoàng Phúc		
2	-	Nghiên cứu tài liệu và các kỹ thuật của dự án Android
-	Tìm hiểu source code của dự án	Anh Lê Hoàng Phúc		
3 - 7	-	Thực hành dự án Android	Anh Lê Hoàng Phúc		
8	-	Tìm hiểu NodeJS	Anh Nguyễn Hồng Phương		
9 - 10	-	Thực hành dự án NodeJS	Anh Nguyễn Hồng Phương		


 

CHƯƠNG 3: CHI TIếT Về PROJECT
1.	Giới thiệu về Tippin
Tippin là một ứng dụng mạng xã hội trên nền tảng Android và iOS cho phép người dùng có thể chia sẽ cập nhật trạng thái, cảm xúc. Điểm đặc biệt của ứng dụng là người dùng có thể tặng “tip” cho nhau (như một loại tiền ảo).
2.	Giới thiệu về dự án NodeJS
NodeJS server có nhiệm vụ trả về các API để hỗ trợ cho ứng dụng có thể xử lý các yêu cầu của người dùng.
Vì tính bảo mật của công ty nên các thông tin chi tiết về dự án không được cung cấp ra bên ngoài.
 
CHƯƠNG 4: TỔNG KẾT
Sau hơn 2 tháng thực tập tại Fujinet Systems JSC, em đã học được nhiều kinh nghiệm bổ ích về lập trình Android cũng như NodeJS, hoàn thành các nhiệm vụ được giao. Nhờ đó, em đã hiểu được quy trình phát triển của một dự án, đồng thời hiểu được trải nghiệm làm dự án thực tế, tăng kĩ năng giao tiếp, xử lí tình huống.

Chân thành cám ơn quý công ty Fujinet Systems JSC đã giúp đỡ tận tình cho em trong suốt 2 tháng thực tập tại công ty. Đặc biệt là anh Nguyễn Hồng Phương và anh Lê Hoàng Phúc đã giúp đỡ và hướng dẫn trong quá trình làm việc để em có thể hoàn thành nhiệm vụ được giao.
 

TÀI LIỆU THAM KHẢO
1.	Android
-	MVVM design pattern
https://medium.com/upday-devs/android-architecture-patterns-part-3-model-view-viewmodel-e7eeee76b73b
https://viblo.asia/p/mvvm-application-qm6RWQ9XGeJE
-	Observer design pattern
https://www.tutorialspoint.com/design_pattern/observer_pattern.htm
-	Butter Knife
http://jakewharton.github.io/butterknife/
-	Customview
https://kipalog.com/posts/Android--Hieu-sau-hon-ve-CustomView-va-Huong-dan-xay-dung-thu-vien-UI-IndicatorView
2.	NodeJS
-	Express framework
https://viblo.asia/p/nodejs-tutorial-phan-4-express-framework-924lJXpNKPM
https://medium.freecodecamp.org/building-a-node-js-application-on-android-part-2-express-and-nedb-ced04caea7bb
-	RESTful APIs
https://www.tutorialspoint.com/nodejs/nodejs_restful_api.htm
-	Mongoose
https://viblo.asia/p/mongoose-cho-mongodb-nodejs-Qbq5QWvJZD8
-	Callback
http://vietjack.com/nodejs/khai_niem_callback_trong_nodejs.jsp
