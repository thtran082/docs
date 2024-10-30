[x] vẽ dependencies graph.
[x] vẽ microservice ví dụ cho itools | theplug | shared libs.
[ ] dựng cái app nx với 2 libs, demo các required feats.


FAQ
Core của google & meta là dùng monorepo mà sao họ vẫn tách ra làm các open source được
service & lib, sao monorepo k dùng chữ service.
tại sao lại chia nhiều lib chi, trong khi những thứ này k thực sự là lib, vd feature login là login của một app chứ k phải là thư viện login.
quản lý artifact của monorepo
quản lý service nào chạy trên server nào
polyrepo đang quản lý loose coupling khá là ngon thông qua các public API, trong khi đó monorepo hướng tới tight coupling?