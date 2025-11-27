# BSC_DPDM2025
Phattarapol Wannayos 663020287-4

# บทที่ 1: บทนำ (Chapter 1. Introduction)
## 1) ความหมายของ Data Mining
Data Mining คือเทคนิคสำหรับ “ค้นพบความรู้ใหม่” จากชุดข้อมูลขนาดใหญ่ โดยดึงรูปแบบที่ไม่ชัดเจนมาก่อนออกมาใช้งานจริง ทั้งในเชิงพรรณนา (Descriptive) และเชิงคาดการณ์ (Predictive)

ในบริบทของ KDD (Knowledge Discovery in Databases) จะประกอบด้วย:
- เตรียมข้อมูล (cleaning, integration)
- เลือกข้อมูลที่เกี่ยวข้อง
- ทำเหมืองข้อมูล
- ประเมินรูปแบบ
- สรุปผลและนำเสนอเป็นความรู้

## 2) เหตุผลที่ Data Mining สำคัญ
- ปริมาณข้อมูลเติบโตอย่างมาก (Web, Sensors, Social, Business)
- แหล่งข้อมูลหลากหลายชนิดและซับซ้อนมากขึ้น
- ต้องการการวิเคราะห์แบบอัตโนมัติแทนการทำงานเชิง manual
- ใช้เพื่อเปลี่ยน “ข้อมูลดิบ” ให้กลายเป็น “ความรู้ที่ใช้ในการตัดสินใจ”

## 3) ประเภทข้อมูลที่รองรับ
- *Database / Data Warehouse*
- *Stream & Sensor Data*
- *Time-Series / Sequence / Temporal*
- *Graph & Social Network*
- *Spatial / Multimedia*
- *Text & Web Data*

## 4) ฟังก์ชันหลักของ Data Mining
- *Generalization (การสรุปภาพรวม)*  
สรุปแนวโน้มระดับสูง เช่น OLAP, Data Cube

- *Pattern Discovery (การค้นพบรูปแบบ)*  
หา itemset ที่พบบ่อย, association rules

- *Classification (การจำแนกประเภท)*  
สร้างโมเดลทำนาย label เช่น Tree, SVM, Neural Network
- *Cluster Analysis (การวิเคราะห์กลุ่ม)*
จัดกลุ่มข้อมูลแบบไม่มีคำตอบกำกับ
- *Outlier Analysis (การวิเคราะห์ค่าผิดปกติ)*  
ตรวจจับค่าผิดปกติที่เบี่ยงเบนจากข้อมูลทั่วไป
- *Time & Ordering (เวลาและลำดับ)*  
ลำดับเหตุการณ์ แนวโน้ม และพฤติกรรมตามเวลา
- *Structure & Network Analysis (โครงสร้างและเครือข่าย)*  
ค้นหารูปแบบในโครงสร้างข้อมูล เช่น subgraph, community detection

## 5) เทคโนโลยีที่เกี่ยวข้อง
Data Mining ผสานวิธีการจากหลายสาขา ได้แก่:
- Machine Learning  
- Statistical Modeling  
- Database & Data Warehousing  
- Pattern Recognition  
- High-Performance Computing  
- Information Visualization  

## 6) ตัวอย่างงานประยุกต์
- การวิเคราะห์เว็บและการจัดอันดับ (PageRank, SEO)
- ระบบแนะนำสินค้า (Recommender)
- Market Basket Analysis / Targeted Marketing
- การแพทย์และประมวลผลข้อมูลชีวภาพ
- วิเคราะห์โซเชียลและเครือข่ายข้อมูล
- การวิเคราะห์ซอฟต์แวร์และบันทึกระบบ

## 7) ประเด็นท้าทายที่ต้องคำนึงถึง
- ข้อมูลขนาดใหญ่ + มิติสูงมาก (High-dimensional)
- ความหลากหลายของชนิดข้อมูล
- การทำเหมืองข้อมูลแบบ streaming  
- ความเป็นส่วนตัวและจริยธรรม (Privacy-preserving mining)
- การสร้างผลลัพธ์ที่เข้าใจง่ายและนำไปใช้จริงได้

