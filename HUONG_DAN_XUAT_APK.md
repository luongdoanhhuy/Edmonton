# Hướng dẫn xuất file APK cài lên điện thoại Android

Vì môi trường hiện tại không cài sẵn Android SDK/Gradle để đóng gói nhị phân `.apk` trực tiếp, em đã đóng gói sẵn toàn bộ **mã nguồn Android gốc (Kotlin + Resizable Home Screen Widget)** kèm theo file cấu hình **GitHub Actions** tự động build APK trên đám mây mà anh **không cần cài Android Studio** trên máy tính.

## Cách 1: Xuất file `.apk` tự động qua GitHub (Nhanh nhất - 3 phút)
1. Giải nén file `VN-Edmonton-Android-Widget-Project.zip`.
2. Tạo một Repository mới trên [GitHub](https://github.com) và tải toàn bộ thư mục vừa giải nén lên.
3. Vào tab **Actions** trên GitHub -> chọn workflow **Build Android APK** -> bấm **Run workflow**.
4. Chờ khoảng 2 phút, tải về file `VN-Edmonton-Widget-Debug-APK` (bên trong có `app-debug.apk`), chép vào điện thoại và cài đặt bình thường.

## Cách 2: Mở bằng Android Studio trên máy tính
1. Mở **Android Studio** -> **Open** -> chọn thư mục vừa giải nén.
2. Vào menu **Build > Build Bundle(s) / APK(s) > Build APK(s)** để xuất file `app-debug.apk`.
