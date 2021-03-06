zimbra-high-availability
========================

Zimbra High Availability (Cluster) with CoroSync+Pacemaker+DRBD

Đây là hướng dẫn cùng một số cấu hình mẫu giúp bạn cấu hình Zimbra HA với CoroSync + Pacemaker + DRBD.
Các thông tin trong hướng dẫn này đã được kiểm chứng với phiên bản: Zimbra Open Source Edition 8.6 64-bit, CoroSync 2.3.3, Pacemaker 1.1.10, DRBD 8.4 chạy trên CentOS Linux 7.0 64-bit. Các bạn có thể kiểm thử với các phiên bản phần mềm ứng dụng, phần mềm HA và Linux khác. Chúng tôi ghi nhận và đánh giá cao mọi đóng góp để hoàn thiện thêm tài liệu.

Trước khi đọc hướng dẫn này, bạn nên tham khảo cuốn Cluster from Scratch (http://clusterlabs.org/doc/en-US/Pacemaker/1.1-pcs/html/Clusters_from_Scratch/index.html) để hiểu rõ các kiến thức cơ bản về HA, CoroSync, Pacemaker, DRBD.

Tài liệu được phát hành theo giấy phép Creative Commons Attribution-ShareAlike 3.0 Unported License (http://creativecommons.org/licenses/by-sa/3.0/), được tham khảo từ tài liệu gốc tại kho Git: https://github.com/tuanta/zimbra-high-availability.
