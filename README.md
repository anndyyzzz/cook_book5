# Example นี้มีชื่อว่า captive_portal
โดยการทำงานของ Example นี้คือทำให้ esp32 เป็น Captive Portal และเป็น Access Point โดยจะหน้าเข้าสู่ระบบกับอุปกรณ์ที่มาเชื่อมต่อ
ขั้นตอนแรกเลือก Example
# ![Screenshot 2024-11-03 170037](https://github.com/user-attachments/assets/41c88d65-6996-4e5b-8b90-a070a46b189d)
รันและbuildโปรแกรม
# ![Screenshot 2024-11-03 170842](https://github.com/user-attachments/assets/2bbdbe18-1f9e-48ec-98f6-de86762549ad)
เลือกเชื่อมกับ esp32_ssid
# ![Image](https://github.com/user-attachments/assets/1be0f7c5-d621-45c5-9086-9fae55693b1d)
จะขึ้นหน้า root.html เมื่อนำอุปกรณ์เชื่อมต่อเข้าไปที่เครือข่าย
# ![Image](https://github.com/user-attachments/assets/e75682a0-e33d-4053-8fc1-203cb3efba0e)
# แก้ไขเพิ่มเติม
สามารถแก้ไขชื่อและรหัส Access Point โดยการกด menuconfig
# ![Screenshot 2024-11-03 171132](https://github.com/user-attachments/assets/69a4f2ee-7e29-4cb3-8eb4-74adec5187fb)
หา Example Configuration และเปลี่ยนตามต้องการแล้วกด save
# ![Screenshot 2024-11-03 171132](https://github.com/user-attachments/assets/01c4d9dc-fb76-4ca3-8ac8-691136e4dd2d)
และสามารถแก้ไขหน้า root.html ได้
# ![Screenshot 2024-11-03 171942](https://github.com/user-attachments/assets/3f0f77db-6c14-4200-839b-7e8bc0eee77f)
รันและbuildโปรแกรม แล้วเชื่อมต่อจะได้หน้า root.html ที่แก้ใหม่
# ![Image (2)](https://github.com/user-attachments/assets/cd5de3aa-631c-4423-b592-a37783b083b7)
