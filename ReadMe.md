# บททดสอบ การเขียนภาษา JavaScript เบื้องต้น

- ทำการ import sql file เข้า ฐานข้อมูล
- เขียน javascript โดยใช้ stack framework ที่ถนัด เพื่อ ทำการ ดึงข้อมูลจากฐานข้อมูล

1. sum ข้อมูล จาก column `fee` โดยแยก ออกมาตาม group ของ `market`, `side` แล้ว หาจำนวน count และ เวลาล่าสุด ของ group ที่แยก ออกมา

result จาก การ query ข้อมูล ที่ต้องการ ควรจะได้ดังรูปภาพข้างล่างนี้ แต่สามารถเขียนตามความเข้าใจ และความสามารถ ของท่านเองได้

![query](https://github.com/casperstack/js-sql-test/blob/main/query.png?raw=true)

(จาก รูปภาพใช้ query time แค่ 3 ms)
