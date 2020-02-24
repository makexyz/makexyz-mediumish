---
layout: post
title:  "Arduino là cái quái gì?"
author: tony
categories: [ arduino, intro ]
image: https://i.ibb.co/vx2B8VV/arduino-uno-r3.jpg
featured: false
beforetoc: "Arduino là bộ não điều khiển của cả một tuyệt tác. Với nó, bạn có thể tạo nên cả tỷ thứ hữu ích trong cuộc sống này."
toc: true
---

Chắc chắn hồi còn bé xíu, bạn, mình và rất rất nhiều người khác nữa đều thích chơi lắp ráp. Từ những miếng gỗ, hoặc từ những mảnh Lego nhỏ, mình có thể xếp thành bất kì mô hình nào mà mình thấy thích thú. Mình nhớ hồi còn học tiểu học, Lego có về trường mình và tổ chức một cuộc thi lắp ráp nho nhỏ. Tất cả học sinh ngồi chung với nhau, các mảnh Lego được đổ tràn ra và mọi người có quyền chọn lựa bất kì mảnh ghép nào để ráp thành ý tưởng của mình. Và, rất rất nhiều ý tưởng thú vị, cách sắp xếp thú vị được tạo ra từ những mảnh vuông cơ bản ấy: lâu đài, máy bay, tàu, xe tăng, …và rất rất nhiều mô hình tuyệt đẹp khác nữa.

## STOP! STOP! Sao dài dòng vậy, rốt cục Arduino là cái quái gì?

Ah, Arduino chẳng phải là sản phẩm gì của Lego đâu! Mình lấy Lego làm ví dụ để các bạn dễ hình dung hơn những gì mình muốn nói thôi. Tất cả mô hình Lego lúc đó đều là mô hình tĩnh, tức là xe chẳng thể tự chạy, chẳng thể nhấp nháy đèn, máy bay chẳng thể bay được, vịt con chẳng thể bơi,… Bạn tưởng tượng thế này, nếu có 1 mảnh ghép nào đấy khi lắp vào khiến xe có thể chạy, máy bay có thể bay và vịt con có thể bơi,… chẳng phải quá tuyệt vời sao? Tất nhiên mảnh ghép tuyệt vời đó, tự bản thân nó đã là một thứ cực kì phức tạp rồi, và chẳng phải ai cũng có thể tự tạo ra nó được.

## Rốt cục thì có thứ mảnh ghép tuyệt với đó không?

Ah, trước thì không nhưng giờ thì đã có!

Trước đây, loại mảnh ghép đó chỉ có chuyên gia điện tử điều khiển mới có thể làm được và rất rất ư là tốn thời gian. Thêm vào đó, mảnh ghép của chuyên gia này có thể sẽ không thể ghép vào mô hình của chuyên gia khác. Nhưng bây giờ, tất cả mọi người, kể cả con nít cũng có thể có được thứ mảnh ghép đó với chi phí cực kì hợp lý. Và hay hơn nữa, bạn có thể lấy mảnh ghép của bộ này ráp qua bộ khác như Lego vậy.

Trong thế giới sáng tạo, giống như chơi Lego, bạn sẽ cần những nền tảng có sẵn được xây dựng bởi người khác, bởi cộng đồng để xây dựng nên những thứ khác tuyệt vời hơn, vỹ đại hơn. Bạn cần đứng trên vai của người khổng lồ để có tầm nhìn xa hơn, và tạo ra những thứ tốt hơn nữa!

Và mình cá là con nít sẽ chẳng muốn chơi lắp ráp đâu nếu chúng phải học qua tất cả mọi thứ như nhựa là gì? đặc tính của nhựa là gì? gia công chế tạo khuôn ép nhựa? kỹ thuật ép phun?… chỉ để làm ra 1 mảnh Lego ^^!

## Vẫn chưa thấy Arduino đâu cả !!!

***Arduino chính là mảnh ghép còn thiếu mà mình nói. Với nó, bạn có thể tạo nên cả tỷ thứ hữu ích trong cuộc sống này. Arduino là bộ não điều khiển của cả một tuyệt tác.***

![arduino-uno-r3](https://i.ibb.co/vx2B8VV/arduino-uno-r3.jpg "Arduino Uno R3")

Mình trích dẫn một phần giải thích về Arduino mà mình thấy thích từ diễn đàn Arduino.vn:

> Arduino là một nền tảng mà mọi thiết bị phần cứng đều được làm sẵn và chuẩn hóa, người dùng chỉ việc chọn những thứ mình cần, ráp lại là có thể chạy được. Bạn muốn làm xe điều khiển từ xa ? Arduino cung cấp cho bạn module điều khiển động cơ có sẵn, mạch điều khiển có sẵn, mạch thu phát sóng không dây có sẵn,… Bạn sẽ không cần phải động não thiết kế mạch điện cho chiếc xe bởi đơn giản là mọi thứ đều có sẵn.

Giống như một con người với “thể xác” đã được xây dựng sẵn, một hệ thống Arduino phải có “tâm hồn” để có thể “sống”. Và tôi gọi việc tạo ra “tâm hồn” ấy là “Lập trình”. Tuy nhiên bạn sẽ không phải lập trình từ A đến Z. Mỗi thứ phần cứng gắn mác “Arduino” đều có những đoạn lệnh đã được viết sẵn (gọi là thư viện) do cộng đồng người dùng Arduino cùng phát triển. Bạn chỉ việc bưng vào và xào nấu lại theo ý muốn của mình. Tới đây, bạn đã giải quyết được vấn đề thứ 2. Đừng lo nếu bạn không biết gì về lập trình bởi chúng chỉ giống như những bài tập Tin học lớp 11 lặt vặt ở trường thôi.
Arduino.vn nói là tận lớp 11, còn mình thì nghĩ là Arduino dễ đến mức nếu được hướng dẫn, học sinh lớp 5 cũng có thể làm dự án bật tắt đèn thông minh trong nhà qua điện thoại trong … 1 ngày!