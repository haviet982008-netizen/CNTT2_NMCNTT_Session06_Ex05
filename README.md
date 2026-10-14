## Tệp mã nguồn hiển thị hoàn chỉnh

#Hiển thị thông báo lên màn hình

write-host "Hệ thống lọc"

#Thông báo đang chạy

write-host "đang tìm 404"

select-string "404" 3.txt | out-file 1.txt

#Thông báo hoàn thành

write-host "đã xong"
