# app-bundles-dynamic-delivery-sample



# App Bundles


# Dynamic Delivery

## Overview

* Dynamic Delivery là mô hình phục vụ ứng dụng của Google Play, nó sử dụng **App Bundles** để tạo và phục vụ APK được tối ưu hóa cho từng thiết bị với API cần thiết và tối ưu dung lượng các bản Apk.

* Phần lớn các APK đã được tối ưu hóa khi sử dụng với Dynamic Delivery. Nếu bạn đã sắp xếp source code và các resource theo các quy định đã được thiết lập, chỉ cần build ứng dụng của bạn với App Bundle sử dụng Android Studio hoặc sử dụng command line và đẩy ứng dụng lên chợ Google Play.

### Dynamic Delivery with split APKs

* Thành phần cơ bản của Dynamic Delivery là cơ chế phân chia APK có sẵ trên Android 5.0 trở lên. Cơ chế này giống với các Apk thông thường bao gồm mã byte DEX được biên dịch, các resource của Android và tệp AndroidManifest.

* Tuy vậy nền tảng Android có thể chia nhỏ nhiều apk để cài đặt như 1 ứng dụng. Nghĩa là bạn cso thể cài đặt nhiều APK phân chia có quyền truy cập vào mã và tài nguyên chung và xuất hiện dưới dạng 1 ứng dụng được cài đặt trên thiết bị.

#### Base APK

* APK này chứa tất cả các mã và resource mà tất cả các APK split khác có thể truy cập và cung cấp chức năng cơ bản cho ứng dụng. Khi người dùng yêu cầu tải xuống ứng dụng của bạn, APK này sẽ được tải xuống và cài đặt trước.

* Điều đó bởi vì có tệp AndroidManifest của APK base khai báo đầy đủ các dịch vụ, ứng dụng cung cấp nội dung, quyền, yêu cầu về version và phụ thuộc vào các tính 

#### Configuration APKs

#### Dynamic feature APKs
