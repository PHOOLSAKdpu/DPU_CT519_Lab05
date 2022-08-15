# PHOOLSAK JANATARAMANEE 645162010005
LAB 5 วิธีการ run ที่ docker desktop
1. clone project จาก repository DPU_CT519_Lab5 ลงมาที่เครื่อง

>> git clone https://github.com/PHOOLSAKdpu/DPU_CT519_Lab05.git

2. เปิด terminal และ cd เข้าไปใน DPU_CT519_Lab5/

3. build dockerfile คำสั่ง >> "docker build -t my-golang-app ."

4. run container คำสั่ง >> "docker run -itd --rm --name my-running-app -p 5000:8090 my-golang-app"

5. เปิด browser 127.0.0.1:5000/index เพื่อ test ได้เลย
