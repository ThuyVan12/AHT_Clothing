# AHT_MKOD
Bước 1: Tạo Vendor và ModuleName theo file registration.php

Bước 2: git clone https://github.com/ThuyVan12/AHT_MKOD.git

Bước 3: Truy cập phpmyadmin -> SQL -> import 2 file sau : https://drive.google.com/file/d/1lMcoTIJHJAqanPR_jLwz7wAaHK5LB5et/view
      và https://drive.google.com/file/d/1zDZo56vXt_Esm0AviZnxqLKseGpXWwGg/view
      
Bước 4: Thêm module https://drive.google.com/file/d/1ik8Msswr3m1Q9sVAlJXwW97zdcP16A88/view

Bước 5: Run sudo bin/magento setup:di:compile && sudo bin/magento setup:upgrade && sudo bin/magento s:s:d -f && sudo chmod -R 777 * && sudo bin/magento c:c

Bước 6: Truy cập Admin -> Content -> Configuration -> Main Website -> Edit chọn  AHT Clothing , thêm logo sau trong admin https://drive.google.com/file/d/146_t7Tf24onm0VookQ_xtrYQFGiQF-LS/view sau đó xóa cache

Bước 7: Truy cập Admin -> Content ->Block -> New Block chọn Insert Image https://drive.google.com/file/d/1I6kzHRdcRhJPoofq4KAlIS5vEuhQnWVS/view


