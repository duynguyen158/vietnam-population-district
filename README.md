([See English version.](#population-of-vietnam-by-district))

# Dân số Việt Nam, cấp huyện
Repo này cung cấp số liệu về dân số Việt Nam theo thành thị - nông thôn và giới tính đối với từng đơn vị hành chính cấp huyện (ĐVHCCH), tính đến ngày 1/4/2019, dưới định dạng CSV. Số liệu được lấy từ Biểu 1 của báo cáo ["Kết quả toàn bộ Tổng điều tra dân số và nhà ở năm 2019"](http://tongdieutradanso.vn/uploads/data/6/files/files/Ket%20qua%20toan%20bo%20Tong%20dieu%20tra%20dan%20so%20va%20nha%20o%202019_ca%20bia_compressed.pdf) của Tổng cục Thống kê. (Bạn đọc quan tâm đến kế hoạch và phương thức Tổng điều tra có thể tham khảo [tại đây](http://tongdieutradanso.vn/uploads/data/6/files/files/Ke%20hoach%20Tong%20dieu%20tra%202019.pdf).)

### Chú thích
Cột | Giải thích
--- | ---
district_code | Mã huyện/ĐVHCCH, theo bộ mã tính đến ngày 1/4/2019 của [Tổng cục Thống kê](https://www.gso.gov.vn/phuong-phap-thong-ke/danh-muc/don-vi-hanh-chinh/).
province_vi | Tên tỉnh/thành phố, tiếng Việt
province_en | Tên tỉnh/thành phố, tiếng Anh
district_equiv_vi | Loại ĐVHCCH (huyện/quận/thành phố/thị xã)
district_vi | Tên huyện/ĐVHCCH, tiếng Việt
district_en | Tên huyện/ĐVHCCH, tiếng Anh
total | Tổng số dân
total_male | Tổng số dân, nam
total_female | Tổng số dân, nữ
total_urban | Tổng số dân thành thị
total_urban_male | Tổng số dân thành thị, nam
total_urban_female | Tổng số dân thành thị, nữ
total_rural | Tổng số dân nông thôn
total_rural_male | Tổng số dân nông thôn, nam
total_rural_female | Tổng số dân nông thôn, nữ

### Lưu ý
- Tại thời điểm tài liệu này được viết, Huyện Hoàng Sa, thuộc Thành phố Đà Nẵng, không được nhắc đến trên số liệu của nguồn (Biểu 1 của báo cáo), và vì vậy sẽ không xuất hiện trên số liệu của repo này.
- Ngoại trừ một số trường hợp đặc biệt (dưới đây), danh sách các đơn vị hành chính cấp huyện phản ánh thời điểm thu thập số liệu (tức ngày 1/4/2019) thay vì hiện tại. Ví dụ, Huyện Quảng Hòa, thuộc Tỉnh Cao Bằng, được thành lập vào ngày 1/3/2020 dưới Nghị quyết 897/NQ-UBTVQH14, và vì vậy không được phản ánh trong Biểu 1. Tương tự, Biểu 1 nhắc đến Thị xã Hoài Nhơn, thuộc Tỉnh Bình Định, dưới tên đơn vị cũ là Huyện Hoài Nhơn, do huyện này mới trở thành thị xã vào ngày 1/6/2020 dưới Nghị quyết 932/NQ-UBTVQH14. 
- Thị xã Đồng Xoài, thuộc Tỉnh Bình Phước, trở thành Thành phố Đồng Xoài vào ngày 1/12/2018 theo Nghị quyết 587/NQ-UBTVQH14 nhưng vẫn được đề cập trong Biểu 1 với tư cách là thị xã. Dữ liệu trong repo đã được cập nhật để phản ánh thay đổi này.
- Thị xã Chí Linh, thuộc Tỉnh Hải Dương, trở thành Thành phố Chí Linh vào ngày 1/3/2019 theo Nghị quyết 623/NQ-UBTVQH14 nhưng vẫn được đề cập trong Biểu 1 dưới tư cách là thị xã. Dữ liệu trong repo đã được cập nhật để phản ánh thay đổi này.

### Phương pháp thu thập
Số liệu được nhập trực tiếp vào trang tính bằng tay, rồi kiểm tra và xuất ra dưới định dạng CSV. Nếu bạn đọc tìm thấy sai sót, xin hãy mở Issue.

___

# Population of Vietnam by District
This repository provides population numbers by urban-rural status and sex in over 700 district-level entities in Vietnam. Data are retrieved from Table 1 of published results from the [decennial nationwide census](http://tongdieutradanso.vn/uploads/data/6/files/files/Ket%20qua%20toan%20bo%20Tong%20dieu%20tra%20dan%20so%20va%20nha%20o%202019_ca%20bia_compressed.pdf) conducted by the General Statistics Office (GSO) in 2019, and up-to-date as of April 1, 2019. (You can read more about the Census methodology [here](http://tongdieutradanso.vn/uploads/data/6/files/files/2019_Census_Plan_Eng.pdf).)

### Definitions
Field | Definition
--- | ---
district_code | A three-digit numeric code representing a district-level entity, given by [GSO](https://www.gso.gov.vn/phuong-phap-thong-ke/danh-muc/don-vi-hanh-chinh/) as of April 1, 2019.
province_vi | The name of the province in which said district/district-equivalent entity is located, in Vietnamese
province_en | Same name as above, but in English
district_equiv_vi | Type of entity, in Vietnamese (*huyện* — district, *quận* — quarter, *thành phố* — city, *thị xã* — town)
district_vi | Name of entity, Vietnamese
district_en | Name of entity, English
total | Total population
total_male | Total population, male
total_female | Total population, female
total_urban | Total urban population
total_urban_male | Total urban population, male
total_urban_female | Total urban population, female
total_rural | Total rural population
total_rural_male | Total rural population, male
total_rural_female | Total rural population, female

### Notes
- At the time of writing, Hoang Sa District, of Da Nang Province, is not included in the data source (i.e. Table 1 of the published results), and, therefore, is not included in the digital dataset provided by this repository.
- Save for a few exceptions (more below), the list of district-level entities of the source — and, therefore, of this dataset — reflects administrative boundaries at the time the data were collected (April 1, 2019) instead of those of today. Discrepancies may include, but are not limited to, district-level entities created, removed, or type-changed by the Vietnamese government.
- Dong Xoai Town, of Binh Phuoc Province, became Dong Xoai City on December 1, 2018, under Resolution 587/NQ-UBTVQH14 passed by the National Assembly Standing Committee (NASC). This change is not reflected in the source, but it is in the data provided by this repository.
- Chi Linh Town, of Hai Duong Province, became Chi Linh City on March 1, 2019, under Resolution 623/NQ-UBTVQH14 passed by NASC. This change is not reflected in the source, but it is in the data provided by this repository.

### Methodology
All 6,408 numeric data points were transferred from their PDF source to a spreadsheet with human eyes and human fingers on a keyboard. The complete dataset was then triple-checked and exported in CSV format. If you find a problem, please open an issue.