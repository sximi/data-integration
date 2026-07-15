# 🔗 Data Integration

> **กระบวนการรวมข้อมูลจากหลายแหล่ง** · พื้นฐานของระบบ Data Analytics สมัยใหม่

---

## 📖 Definition

### English — IBM
> *"Data integration is the process of combining data from different sources into a single, unified view. Integration begins with the ingestion process, and includes steps such as cleansing, ETL mapping, and transformation."*

### English — Oracle
> *"Data integration involves combining data residing in different sources and providing users with a unified view of these data. This process becomes significant in a variety of situations, which include both commercial (such as when two similar companies need to merge their databases) and scientific (combining research results from different bioinformatics repositories) domains."*

### 🇹🇭 Thai — สรุปในสไตล์ของตัวเอง
Data Integration คือ **"การรวมข้อมูลจากทุกที่มาไว้ที่เดียว"** — เหมือนเอาข้อมูลจากหลายร้านค้า หลาย database หลาย format มารวมกัน แล้วจัดให้เป็นระเบียบ เพื่อให้ใช้งานและวิเคราะห์ได้ง่ายขึ้น 🌸

---

## 🔍 Explanation

Data Integration เป็นกระบวนการสำคัญในสาย **Data Analytics** และ **Back-End Development** เพราะข้อมูลจริงในองค์กรมักกระจายอยู่หลายที่และหลาย format

### 🔄 กระบวนการ ETL

| ขั้นตอน | ความหมาย | ตัวอย่าง |
|---|---|---|
| **Extract** | ดึงข้อมูลจากแหล่งต้นทาง | MySQL, Excel, API |
| **Transform** | แปลง / ทำความสะอาดข้อมูล | เปลี่ยน format, แก้ค่าว่าง |
| **Load** | โหลดข้อมูลเข้า target | Data Warehouse, Dashboard |

### 🛠️ เครื่องมือที่นิยม

| เครื่องมือ | ใช้สำหรับ |
|---|---|
| **Apache Kafka** | Real-time data streaming |
| **Apache Airflow** | จัดการ data pipeline |
| **Talend** | ETL แบบ GUI |
| **dbt** | Transform ข้อมูลใน warehouse |

### 🌍 ตัวอย่างใช้งานจริง

- ร้านค้าออนไลน์รวมข้อมูลจาก **POS + เว็บ + แอป** มาวิเคราะห์ยอดขาย
- โรงพยาบาลรวมข้อมูลผู้ป่วยจากหลายแผนกไว้ในระบบเดียว
- บริษัทรวม log จาก server หลายตัวมาตรวจสอบความปลอดภัย

---

## 🤖 GenAI Explanation

> *"Data Integration คือกาวที่เชื่อมระบบต่างๆ เข้าหากัน — ในโลกที่ข้อมูลกระจายอยู่ใน database, API, ไฟล์ Excel และ cloud service นับสิบๆ ระบบ การ integrate ข้อมูลให้ถูกต้องและทันเวลาคือความสามารถที่มีมูลค่าสูงมากในองค์กรสมัยใหม่"*
>
> — **ChatGPT** (OpenAI)

> *"Data Integration ไม่ใช่แค่การ copy ข้อมูลจากที่หนึ่งไปอีกที่หนึ่ง แต่รวมถึงการทำให้ข้อมูลมีความสอดคล้อง น่าเชื่อถือ และพร้อมใช้งาน ซึ่งเป็นพื้นฐานที่ขาดไม่ได้ของ Business Intelligence และ AI สมัยใหม่"*
>
> — **Gemini** (Google)

---

## 📚 References

1. IBM. (2024). [*What is Data Integration?*](https://www.ibm.com/topics/data-integration)
2. Oracle. (2024). [*What is Data Integration?*](https://www.oracle.com/integration/what-is-data-integration/)
3. Talend. (2024). [*Data Integration Guide*](https://www.talend.com/resources/what-is-data-integration/)

---

*🔗 กลับไปหน้าหลัก → [sximi.github.io](https://sximi.github.io)*
