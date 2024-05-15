# Movie Recommendation Website
Công nghệ sử : python, flask, html, css, js, TMDB

Ứng dụng này cung cấp tất cả thông tin chi tiết về bộ phim được yêu cầu như tổng quan, thể loại, ngày phát hành, xếp hạng, thời gian chạy, dàn diễn viên hàng đầu, bài đánh giá, phim được đề xuất, v.v.

Thông tin chi tiết về phim (tiêu đề, thể loại, thời gian chạy, xếp hạng, áp phích, v.v.) được TMDB tìm nạp bằng API, https://www.themoviedb.org/documentation/api và sử dụng id IMDB của phim trong API, tôi đã quét web để lấy các đánh giá do người dùng đưa ra trên trang IMDB bằng cách sử dụng `beautifulsoup4` và thực hiện phân tích cảm tính về các đánh giá đó.

## Lấy API key

Tạo một tài khoản tại https://www.themoviedb.org/, nhấp vào liên kết `API` từ thanh bên trái trong cài đặt tài khoản của bạn và điền tất cả thông tin chi tiết để đăng ký khóa API. Nếu bạn được hỏi URL trang web, chỉ cần cung cấp "NA" nếu bạn không có. Bạn sẽ thấy khóa API trong thanh bên `API` sau khi yêu cầu của bạn được chấp thuận.

## Cách chạy

1.  Clone repo về máy
2.  Cài đặt các thư viện cần thiết bằng lệnh:`pip install -r require. txt`
3.  Thay thế YOUR_API_KEY tại dòng số. 2 của tệp `static/recommend.js`
4.  Chạy file main.py
5.  Truy cập địa chỉ `http://127.0.0.1:5000/` 

### Datasets 

1. [IMDB 5000 Movie Dataset](https://www.kaggle.com/carolzhangdc/imdb-5000-movie-dataset)
2. [The Movies Dataset](https://www.kaggle.com/rounakbanik/the-movies-dataset)
3. [List of movies in 2018](https://en.wikipedia.org/wiki/List_of_American_films_of_2018)
4. [List of movies in 2019](https://en.wikipedia.org/wiki/List_of_American_films_of_2019)
5. [List of movies in 2020](https://en.wikipedia.org/wiki/List_of_American_films_of_2020)

