กฏการสร้าง MermaidJS Flowchart Diagram โดยอิงตามข้อมูลด้านล่างนี้:

### 1. ชื่อ/หัวข้อ Diagram:

[ระบุชื่อ flowchart เช่น "ระบบล็อกอิน", "ขั้นตอนการสั่งซื้อสินค้า"]

### 2. ประเภทการไหลของ Diagram (Direction):

เลือกหนึ่งตัวเลือก:

- TD/TB : บนลงล่าง (Top to Bottom)
- LR : ซ้ายไปขวา (Left to Right)
- RL : ขวาไปซ้าย (Right to Left)
- BT : ล่างขึ้นบน (Bottom to Top)

### 3. โหนด (Nodes) - ระบุข้อมูลทุกโหนด:

สำหรับแต่ละโหนดให้ระบุ:

- **ID**: ตัวย่อภาษาอังกฤษ (เช่น A, Start, Check_Auth)
- **ข้อความในโหนด**: คำอธิบายสั้นๆ (เช่น "เริ่มต้น", "ตรวจสอบสิทธิ์")
- **ประเภทโหนด** (เลือกตามนี้):
  - `[ ]` : กล่องสี่เหลี่ยม (Process)
  - `{ }` : สี่เหลี่ยมข้าวหลามตัด (Decision)
  - `( )` : วงกลม/วงรี (Start/End)
  - `[/\]` : สี่เหลี่ยมด้านขนาน (Input/Output)
  - `(( ))` : วงกลม (Database)
  - `subgraph` : กลุ่มโหนด (ระบุ ID และชื่อของ subgraph)
- **รูปภาพในโหนด (ไม่บังคับ)**:
  - URL รูปภาพ (ต้องเป็น URL สาธารณะ) หรือ icon จากข้อ 6
  - ขนาดรูปภาพ (width, height) เช่น 40px, 50px
  - ตำแหน่งรูปภาพ (ด้านบน/ด้านล่าง/ซ้าย/ขวา)

### 4. การเชื่อมต่อ (Connections) - ระบุทุกเส้นทางการไหล:

สำหรับแต่ละการเชื่อมต่อให้ระบุ:

- **จากโหนด**: (ID ต้นทาง)
- **ไปยังโหนด**: (ID ปลายทาง)
- **ข้อความบนเส้น**: (เช่น "ใช่", "ไม่", "สำเร็จ") (ถ้าไม่มีให้เว้นว่าง)
- **สีเส้น (ไม่บังคับ)**: ระบุชื่อสีหรือรหัส HEX (เช่น red, #FF0000)
- **รูปแบบเส้น (ไม่บังคับ)**:
  - เส้นทึบ (default): ไม่ต้องระบุ
  - เส้นประ: ระบุ "dotted"
  - เส้นขีด: ระบุ "dashed"

### 5. Subgraphs (ไม่บังคับ):

หากมี subgraph ให้ระบุ:

- **ID Subgraph**: (เช่น Sub1, Sub2)
- **ชื่อ Subgraph**: (เช่น "โมดูล A", "ระบบย่อย B")
- **โหนดที่อยู่ใน Subgraph นี้**: ระบุ ID โหนด (คั่นด้วยลูกน้ำ)

### 6. รูป icon ที่ใช้ใน Diagram (ไม่บังคับ):

- [2-in-1 IAQ]`<img src="https://lh3.googleusercontent.com/d/1sfh8Q8cVsnevj36_z5Vi2LzyG6AzoKs_"/>`
- [4G Cellular Gateway]`<img src="https://lh3.googleusercontent.com/d/1tMGuQwKwVEz3MbB1r0Xn_tINfyYwbwbd"/>`
- [Digital Platform]`<img src="https://lh3.googleusercontent.com/d/1V2jNvcfqKIgLaP5GbwQFjRQ8hGNJKdGw"/>`
- [Digital Power Meter (PM2230)]`<img src="https://lh3.googleusercontent.com/d/169YH6ziHB9lEM9Ue22wSrSEoZer_uSrY"/>`
- [Industrial Gateway]`<img src="https://lh3.googleusercontent.com/d/1j_4Cu2ADAyFCBH4f2m2RNEvmA9O0Tpvu"/>`
- [LoRaWAN Gateway (UG65)]`<img src="https://lh3.googleusercontent.com/d/1iWh8eQa7K36F87tyx2Bg_ufyceBnNwv1"/>`
- [Multi-Circuit Power Meter]`<img src="https://lh3.googleusercontent.com/d/1zi0NVyihRuFHCyKdj_MBZF_emIt6lZsT"/>`
- [Pressure transmitter]`<img src="https://lh3.googleusercontent.com/d/1vTJOQodoRIAv5IbXZMmZ4mXI5WvCgG0k"/>`
- [Remote (A-1019)]`<img src="https://lh3.googleusercontent.com/d/1KPlLV4MFaep3gezNbgg9sn_LUkQBf_2i"/>`
- [Router UR32]`<img src="https://lh3.googleusercontent.com/d/1X5w1q_DLHbUoXFPl62rdkksPBa9WPrkw"/>`
- [Strap-on Temp. sensor]`<img src="https://lh3.googleusercontent.com/d/1qS1up3B4CO2YX1jnKNNRouJSGODUqGFp"/>`
- [Temp Controller]`<img src="https://lh3.googleusercontent.com/d/1rOaIrql41V938OZIk9ZEUfdVb8k4Qbno"/>`
- [Temperature Sensor Insert Type]`<img src="https://lh3.googleusercontent.com/d/1UGczGL-4sd0EeAy6dUneD39bmcPUN97J"/>`
- [Ultrasonic Flow Meter]`<img src="https://lh3.googleusercontent.com/d/19E1jxNlbIkCh9CXk51hX_qWS7VGtqwCD"/>`

### 7. กฏ

- นำ tag รูปภาพไปใช้ห้ามแก้ไขเด็ดขาด

### 8. ตัวอย่างการใช้ Prompt:

#### Basic

```
#### ชื่อ/หัวข้อ Diagram:
ระบบล็อกอินผู้ใช้
#### Direction:
TD
#### Nodes:
- ID: Start, ข้อความ: เริ่มต้น, ประเภท: ( )
- ID: Input, ข้อความ: กรอก username/password, ประเภท: [/\]
- ID: Verify, ข้อความ: ตรวจสอบข้อมูล, ประเภท: { }
- ID: Success, ข้อความ: ล็อกอินสำเร็จ, ประเภท: [ ]
- ID: Fail, ข้อความ: ล็อกอินล้มเหลว, ประเภท: [ ]
- ID: End, ข้อความ: จบกระบวนการ, ประเภท: ( )
#### Connections:
- จาก: Start, ไปยัง: Input, ข้อความบนเส้น:
- จาก: Input, ไปยัง: Verify, ข้อความบนเส้น:
- จาก: Verify, ไปยัง: Success, ข้อความบนเส้น: ถูกต้อง
- จาก: Verify, ไปยัง: Fail, ข้อความบนเส้น: ผิดพลาด
- จาก: Success, ไปยัง: End, ข้อความบนเส้น:
- จาก: Fail, ไปยัง: End, ข้อความบนเส้น:
```

#### Subgraph

```
### ชื่อ/หัวข้อ Diagram:
ระบบจัดการออเดอร์

### Direction:
LR

### Nodes:
- ID: Start, ข้อความ: เริ่มต้น, ประเภท: ( )
- ID: Sub1, ประเภท: subgraph, ข้อความ: "ส่วนรับออเดอร์"
- ID: Order, ข้อความ: รับออเดอร์, ประเภท: [ ]
- ID: Payment, ข้อความ: รับการชำระเงิน, ประเภท: [ ]
- ID: Sub2, ประเภท: subgraph, ข้อความ: "ส่วนประมวลผล"
- ID: Process, ข้อความ: ประมวลผลออเดอร์, ประเภท: [ ]
- ID: Ship, ข้อความ: ส่งสินค้า, ประเภท: [ ]
- ID: End, ข้อความ: จบกระบวนการ, ประเภท: ( )

### Subgraphs:
- ID: Sub1, ชื่อ: "ส่วนรับออเดอร์", โหนด: Order, Payment
- ID: Sub2, ชื่อ: "ส่วนประมวลผล", โหนด: Process, Ship

### Connections:
- จาก: Start, ไปยัง: Order, ข้อความบนเส้น:
- จาก: Order, ไปยัง: Payment, ข้อความบนเส้น:
- จาก: Payment, ไปยัง: Process, ข้อความบนเส้น:
- จาก: Process, ไปยัง: Ship, ข้อความบนเส้น:
- จาก: Ship, ไปยัง: End, ข้อความบนเส้น:
```

#### Basic + Subgraph + Icon

```
### ชื่อ/หัวข้อ Diagram:
ระบบตรวจสอบ IoT

### Direction:
TD

### Nodes:
- ID: Start, ข้อความ: เริ่มต้น, ประเภท: ( )
- ID: Sub1, ประเภท: subgraph, ข้อความ: "ส่วนเก็บข้อมูล"
- ID: Sensor1, ข้อความ: เซนเซอร์อุณหภูมิ, ประเภท: [ ], รูปภาพ: 2-in-1 IAQ, ขนาด: 40px, ตำแหน่ง: ด้านบน
- ID: Sensor2, ข้อความ: เซนเซอร์ความดัน, ประเภท: [ ], รูปภาพ: Pressure transmitter, ขนาด: 40px, ตำแหน่ง: ด้านบน
- ID: Sub2, ประเภท: subgraph, ข้อความ: "ส่วนวิเคราะห์"
- ID: Analyze, ข้อความ: วิเคราะห์ข้อมูล, ประเภท: { }, รูปภาพ: Digital Platform, ขนาด: 40px, ตำแหน่ง: ด้านล่าง
- ID: Report, ข้อความ: สรุปรายงาน, ประเภท: [/\\], รูปภาพ: Router UR32, ขนาด: 40px, ตำแหน่ง: ซ้าย
- ID: End, ข้อความ: จบกระบวนการ, ประเภท: ( )

### Subgraphs:
- ID: Sub1, ชื่อ: "ส่วนเก็บข้อมูล", โหนด: Sensor1, Sensor2
- ID: Sub2, ชื่อ: "ส่วนวิเคราะห์", โหนด: Analyze

### Connections:
- จาก: Start, ไปยัง: Sensor1, ข้อความบนเส้น: , สีเส้น: green
- จาก: Start, ไปยัง: Sensor2, ข้อความบนเส้น: , สีเส้น: green
- จาก: Sensor1, ไปยัง: Analyze, ข้อความบนเส้น: , สีเส้น: blue
- จาก: Sensor2, ไปยัง: Analyze, ข้อความบนเส้น: , สีเส้น: blue
- จาก: Analyze, ไปยัง: Report, ข้อความบนเส้น: ผ่าน, สีเส้น: #00FF00
- จาก: Analyze, ไปยัง: Sensor1, ข้อความบนเส้น: ตรวจสอบใหม่, สีเส้น: red, รูปแบบเส้น: dotted
- จาก: Report, ไปยัง: End, ข้อความบนเส้น: , สีเส้น: purple
```
