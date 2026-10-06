# BA Study Guideline

หัวข้อนี้มีเป้าหมายเพื่อให้ BA เข้าใจภาพรวมของ **System, Data และ AI** ในระดับที่สามารถเอา Business Requirement ไปเชื่อมกับระบบจริงได้ และคุยกับทั้งฝั่ง Business และ Technical Team ให้เข้าใจตรงกัน

---

# 1. High-level System Architecture

## Introduction

เน้นทำความเข้าใจว่า **ระบบของเรา ผู้ใช้ และระบบภายนอกเชื่อมต่อกันยังไง** โดยมองในภาพรวมระดับ **Container**

สิ่งที่ควรมองให้ออกคือ ระบบมีส่วนประกอบอะไรบ้าง และแต่ละส่วนมีหน้าที่อะไร

ช่วงแรกยังไม่จำเป็นต้องลงลึกถึงระดับ Implementation ขอแค่เข้าใจ **ว่ามันคืออะไร และมีไว้ทำอะไร** ก็พอ เช่น

* **Microservices**
* **Message Queue / Event**
* **Cache**
* **Monitoring / Logging**

---

## Resources

### Microservices

https://youtu.be/71ZppEfvRgg?si=MiUSMp3c3jIj_6XT

### Message Queue

https://mikelopster.dev/posts/rabbitmq-basic#message-queue-คืออะไร

### Cache

https://youtu.be/m_1HQlkcHIk?si=6NqWGsnr1ehv2xbC

### Logging

https://youtu.be/6cxgasCDJgA?si=noeiMObQMHnZ-o_Q

---

# 2. Data Flow

## Introduction

เน้นทำความเข้าใจว่า **ข้อมูลและการทำงานไหลผ่านระบบยังไง** ตั้งแต่ต้นทางไปจนถึงปลายทาง

รวมถึงรู้จักเลือกใช้ Diagram ที่เหมาะกับแต่ละสถานการณ์ เพื่อสื่อสาร Flow ให้ทั้ง Business และ Technical Team เข้าใจตรงกัน

### Diagram ที่ควรรู้จัก

* **Data Flow Diagram**
* **Sequence Diagram**
* **Activity Diagram (Flowchart)**

---

## Resources

ส่วนนี้สามารถศึกษา Diagram ทั้ง 3 แบบไปพร้อมกับการทำความเข้าใจ **Business Process และ System Flow** เพื่อให้เห็นภาพความสัมพันธ์ระหว่าง **User, Process, System และ Data** ได้ชัดขึ้น

---

# 3. AI Fundamentals

## Introduction

เน้นทำความเข้าใจ **ว่า AI แต่ละอย่างคืออะไร มีไว้ทำอะไร และมีบทบาทยังไง** ในระดับ Concept

ช่วงแรกยังไม่จำเป็นต้องลงลึกถึง Mathematics หรือ Implementation

หัวข้อหลักที่ควรรู้ ได้แก่

* **AI**
* **Machine Learning**
* **Deep Learning**
* **Generative AI**
* **LLM Concept**
* **Prompt**
* **Context**
* **Token**
* **Model**
* **RAG**
* **AI Agent**

เป้าหมายคือให้สามารถมองออกว่า **AI แต่ละแบบเหมาะกับงานอะไร** และสามารถเชื่อมโยง AI เข้ากับ **Business Problem, System และ Data** ได้

---

## Resources

* https://youtu.be/H2jCHP1aKtE?si=qWrCKFohDkqpsv6B
* https://youtu.be/-f_i_a13IKc?si=-ov_vwG2w0ipNPau
* https://youtu.be/3XbAdTbQYBY?si=yYYhVF3gb-1YR_3z
* https://youtu.be/4h9mGGmCqlM?si=SjKosbbuF8tXWuYU
