Bước 1: Tạo 1 vendor là AHT

Bước 1: git clone https://github.com/ThuyVan12/AHT_MKOD.git trong folder AHT

Bước 2: Cần đổi lại folder theme thành mkod tránh vieecj bị lỗi vì file registration và theme.xml đang để tên theme là mkod

Bước 3: Truy cập phpmyadmin -> SQL -> import 2 file cms_block và cms_block_store : mkod: https://drive.google.com/file/d/1vW5YL6hqAIp_Ac585s-4eu-Ar4xPfkDN/view?usp=sharing

Bước 5: Run sudo bin/magento setup:di:compile && sudo bin/magento setup:upgrade && sudo bin/magento s:s:d -f && sudo chmod -R 777 * && sudo bin/magento c:c

Bước 6: Truy cập Admin -> Content -> Configuration -> Main Website -> Edit chọn AHT Clothing , thêm logo có ảnh trong folder img, link: https://drive.google.com/file/d/1vW5YL6hqAIp_Ac585s-4eu-Ar4xPfkDN/view?usp=sharing 

sau đó xóa cache

