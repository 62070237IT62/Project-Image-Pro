# 👀การรู้จำภาพใบหน้าคน🤷🏻‍♀️

### กลุ่ม : มาสี่คนมีสี่หัว👩👩‍🦰👱‍♀️👩‍🦳

**สมาชิก :** 
   1. นางสาวชนิสรา เอื้อสมศักดิ์สกุล 62070237
   2. นางสาวชาลิสา สกุลอัครวีร์ 62070240
   3. นางสาวนาเดีย สมัญญา 62070251
   4. นางสาวกมลชนก สินรักษา 63070205

>หมายเหตุ : Project2 และ Project3 ทำบน google colab 
## Project2 : Handcraft_base✍🏻
#### วิธี Run Code🖥

#### วิธีเปลี่ยนรูป Dataset💾

## Project3 : Learning_base😂
#### วิธี Run Code🖥
Training และ Testing 👇🏻
```
learning_based.py
```
เมื่อรันทั้งหมดแล้วจะได้ไฟล์ "model.pt" ออกมา
รันใน google colab จะได้
```
/content/model.pt
```
#### วิธีเปลี่ยนรูป Dataset💾
ใช้pathlib ในการอ่านไฟล์ดังนั้น dataset ที่ใช้วางpath ถึงแค่โฟลเดอร์ที่กำหนดไว้
```
#กำหนดที่อยู่ของ dataset ที่นำมาใช้ 
#ที่ใส่path ในที่นี้ใช้สำหรับtest และtrain path เดียวกัน
data_path = Path('Tr/emoji')
```
ในการใช้ไฟล์
```
#ในการใช้ไฟล์จะใช้ for loop ในการเลือกโฟลเดอร์ย่อย 
#ls เป็นการเรียกไฟล์จากโฟลเดอร์ย่อย
(data_path/f'i ({idx})').ls()
```
