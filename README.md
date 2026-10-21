# DreamFight Cards

เกมการ์ด RED vs BLUE บนเว็บ — **เล่นได้ที่ https://thunderzzzai.github.io/dreamfight-cards-5162c9/** (ไม่ต้องล็อกอิน · ต้องมีรหัสเข้าเกม — ขอจากผู้จัด)

- **ARCADE** — สู้กับบอท BLUE
- **PVP** — ผู้เล่นสู้กันออนไลน์ กด RED READY / BLUE READY · ห้องส่วนตัวใส่ `?room=ชื่อห้อง` ต่อท้ายลิงก์
- คู่มือฉบับภาพ: https://claude.ai/artifact/GxzSL6ReJdLGHSwxhw2ULB

PVP ส่งเฉพาะการตัดสินใจของผู้เล่น (lockstep — ทั้งสองเครื่องคำนวณผลเองด้วย seed เดียวกัน) ผ่าน MQTT broker สาธารณะ
(broker.emqx.io · broker.hivemq.com · test.mosquitto.org พร้อมกันทั้ง 3 เจ้า) — ไม่มีเซิร์ฟเวอร์ของเราเอง ไม่เก็บข้อมูลผู้เล่น

repo นี้เป็นสำเนาสำหรับเผยแพร่ — ต้นฉบับพัฒนาใน V-Oracle (`ψ/lab/dreamfight-cards`) แล้ว deploy ด้วย `deploy_pages.sh`
