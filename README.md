# Website Công Phá Nhập Môn Lập Trình
## Mục lục
- [Sơ lược về website](#sơ-lược-về-website)
- [Hướng dẫn set up](#hướng-dẫn-set-up)
- [Hướng dẫn tùy chỉnh giao diện và nội dung](#hướng-dẫn-tùy-chỉnh-giao-diện-và-nội-dung)
## Sơ lược về website
(Chờ Hải viết)
## Hướng dẫn set up
### 1. Cài đặt [Github Desktop](https://desktop.github.com/) hoặc [Git](https://git-scm.com/downloads)

- Khuyến khích dùng Github Desktop nếu chưa có kinh nghiệm nhiều với GitHub nói riêng và Git nói chung.
### 2. Cài đặt [Jekyll](https://jekyllrb.com/docs/installation/)
- Lưu ý các requirements có đề cập trong link khi cài đặt (Ruby, RubyGems, GCC...).
- Có hướng dẫn chi tiết cho Windows [ở đây](https://jekyllrb.com/docs/installation/windows/).
### 3. Clone repository này
- Chọn `Code` rồi chọn `Open with GitHub Desktop`
- Lưu ý chọn branch main để có được phiên bản mới nhất
### 4. Thiết lập và chạy thử
- Mở repository đã clone trong IDE của bạn.
- Mở Terminal lên và chạy lệnh `bundle install` và `bundle update`
- Chạy thử site trên local bằng cách chạy lệnh `bundle exec jekyll serve` . Nếu gặp phải lỗi `/home/argilo/.gem/ruby/3.0.0/gems/jekyll-4.2.0/lib/jekyll/commands/serve/servlet.rb:3:in require': cannot load such file -- webrick (LoadError)` , chạy thêm lệnh `bundle add webrick` rồi thử lại.Nếu gặp lỗi " GitHub Metadata: No GitHub API authentication could be found. Some fields may be missing or have incorrect data." thì thêm "github: [metadata]" vào file "_config.yml"

## Hướng dẫn tùy chỉnh giao diện và nội dung


