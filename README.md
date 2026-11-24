<div align="center">

# SC 677 704 Advanced Data Analytics

### การวิเคราะห์ข้อมูลขั้นสูง

![Python](https://img.shields.io/badge/Python-3.12%2B-3776AB?logo=python&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?logo=apacheairflow&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?logo=apachespark&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?logo=streamlit&logoColor=white)
![KKU](https://img.shields.io/badge/KKU-Statistics%20%26%20Data%20Science-8B1A1A)

คลังเก็บงาน โค้ด และเอกสารประกอบการเรียนรายวิชา SC 677 704<br>
หลักสูตรวิทยาศาสตรมหาบัณฑิต สาขาวิชาสถิติและวิทยาการข้อมูล คณะวิทยาศาสตร์ มหาวิทยาลัยขอนแก่น

</div>

---

## สารบัญ

- [ข้อมูลโปรเจกต์และผู้จัดทำ](#ข้อมูลโปรเจกต์และผู้จัดทำ)
- [ข้อมูลรายวิชา](#ข้อมูลรายวิชา)
- [เกี่ยวกับรายวิชา](#เกี่ยวกับรายวิชา)
- [ผลลัพธ์การเรียนรู้](#ผลลัพธ์การเรียนรู้)
- [แผนการเรียนรายสัปดาห์](#แผนการเรียนรายสัปดาห์)
- [การประเมินผล](#การประเมินผล)
- [สถานะงาน](#สถานะงาน)
- [การติดตั้งและตั้งค่าสภาพแวดล้อม](#การติดตั้งและตั้งค่าสภาพแวดล้อม)
- [คำสั่ง venv และ pip](#คำสั่ง-venv-และ-pip)
- [โครงสร้าง Repository](#โครงสร้าง-repository)
- [การใช้งาน Git](#การใช้งาน-git)
- [ตำราและแหล่งอ้างอิง](#ตำราและแหล่งอ้างอิง)
- [นโยบายการใช้เครื่องมือ AI](#นโยบายการใช้เครื่องมือ-ai)

---

## ข้อมูลโปรเจกต์และผู้จัดทำ

| หัวข้อ | รายละเอียด |
| --- | --- |
| **ชื่อโปรเจกต์** | SC-677-704-Advanced-Data-Analytics · คลังงานรายวิชาการวิเคราะห์ข้อมูลขั้นสูง |
| **รายวิชา** | SC 677 704 การวิเคราะห์ข้อมูลขั้นสูง (Advanced Data Analytics) |
| **ผู้จัดทำ** | `<ชื่อ-นามสกุล>` |
| **รหัสนักศึกษา** | `<รหัสนักศึกษา>` |
| **GitHub** | [tanpharamut](https://github.com/tanpharamut) |

---

## ข้อมูลรายวิชา

| หัวข้อ | รายละเอียด |
| --- | --- |
| **รหัสและชื่อวิชา** | SC 677 704 การวิเคราะห์ข้อมูลขั้นสูง (Advanced Data Analytics) |
| **หน่วยกิต** | 3(2-2-5) บรรยาย 2 ชม. · ปฏิบัติการ 2 ชม. · ศึกษาด้วยตนเอง 5 ชม. ต่อสัปดาห์ |
| **ภาคการศึกษา** | ภาคต้น ปีการศึกษา 2569 |
| **อาจารย์ผู้รับผิดชอบและผู้สอน** | ผศ.ดร.เปรม จันทร์สว่าง |
| **วันและเวลา** | พุธ และ ศุกร์ 10:00–12:00 น. |
| **สถานที่** | ห้องบรรยายและห้องปฏิบัติการคอมพิวเตอร์ ภาควิชาสถิติ คณะวิทยาศาสตร์ |
| **รูปแบบการเรียน** | บรรยาย + ปฏิบัติการ ในชั้นเรียน (Classroom-based learning) |
| **วิธีจัดการเรียนรู้** | Problem-based · Task-based · Project-based learning · Case discussion |
| **วิชาบังคับก่อน** | ไม่มี |

---

## เกี่ยวกับรายวิชา

รายวิชานี้ครอบคลุมงานวิเคราะห์ข้อมูล **ครบวงจร** ตั้งแต่การสร้างสายท่อข้อมูล การประมวลผลข้อมูลมหัตแบบกระจาย การวิเคราะห์ข้อมูลไม่มีโครงสร้างและข้อมูลหลายมิติ การเรียนรู้ของเครื่อง ไปจนถึงการแสดงผลข้อมูล แดชบอร์ด และเว็บแอปพลิเคชันเพื่อนำเสนอผล

| 1. รวบรวมข้อมูล ➜ | 2. ประมวลผลข้อมูลมหัต ➜ | 3. วิเคราะห์และสร้างแบบจำลอง ➜ | 4. นำเสนอผล |
| :---: | :---: | :---: | :---: |
| Data pipeline | Hadoop · Spark | NLP · PCA · ML · DL | Viz · Dashboard · Web app |
| *Airflow* | *PySpark* | *scikit-learn · MLlib · Keras* | *Plotly · BI tools · Streamlit* |

**วัตถุประสงค์รายวิชา**

1. ออกแบบและพัฒนาสายท่อข้อมูล และวิเคราะห์ข้อมูลมหัตด้วยเครื่องมือประมวลผลแบบกระจาย
2. วิเคราะห์ข้อมูลไม่มีโครงสร้างและข้อมูลหลายมิติ และประยุกต์ใช้การเรียนรู้ของเครื่องกับข้อมูลมหัตได้อย่างถูกต้องตามหลักการทางสถิติ
3. ออกแบบการแสดงผลข้อมูล เล่าเรื่องด้วยข้อมูล และพัฒนาแดชบอร์ดและแอปพลิเคชันบนเว็บเพื่อนำเสนอสารสนเทศ
4. สื่อสารผลการวิเคราะห์ ให้คำแนะนำเชิงสถิติ และสร้างผลงานด้านการวิเคราะห์ข้อมูลอย่างมีจริยธรรม

<details>
<summary><b>Course description (English)</b></summary>
<br>

Data pipeline, big data analytics, unstructured data analysis, multivariate data analysis, machine learning application for big data, concepts of data visualization, data storytelling, principles of dashboard design for information presentation using business intelligence tools, web application development.

</details>

---

## ผลลัพธ์การเรียนรู้

| CLO | ผลลัพธ์การเรียนรู้ของรายวิชา | PLO | น้ำหนัก |
| :---: | --- | :---: | :---: |
| **CLO1** | ออกแบบและพัฒนาสายท่อข้อมูลเพื่อรวบรวม แปลง และจัดเก็บข้อมูลจากหลายแหล่ง | 3 | 13% |
| **CLO2** | วิเคราะห์ข้อมูลมหัตด้วยเครื่องมือประมวลผลแบบกระจาย | 3 | 14% |
| **CLO3** | วิเคราะห์ข้อมูลไม่มีโครงสร้างและข้อมูลหลายมิติด้วยเทคนิคที่เหมาะสมได้อย่างถูกต้องตามหลักการทางสถิติ | 1 | 9% |
| **CLO4** | พัฒนาและประเมินแบบจำลองการเรียนรู้ของเครื่องสำหรับข้อมูลมหัตเพื่อแก้ปัญหาทางธุรกิจหรือการวิจัย | 2 | 13% |
| **CLO5** | ออกแบบการแสดงผลข้อมูล เล่าเรื่องด้วยข้อมูล และพัฒนาแดชบอร์ดด้วยเครื่องมือธุรกิจอัจฉริยะ | 6 | 16% |
| **CLO6** | พัฒนาแอปพลิเคชันบนเว็บเพื่อนำเสนอผลการวิเคราะห์ข้อมูล | 6 | 10% |
| **CLO7** | สื่อสารผลการวิเคราะห์และให้คำแนะนำเชิงสถิติแก่ผู้ใช้ข้อมูลได้อย่างถูกต้องและเข้าใจง่าย | 5 | 13% |
| **CLO8** | สร้างผลงานด้านการวิเคราะห์ข้อมูลแบบครบวงจรผ่านโครงงาน โดยคำนึงถึงจริยธรรมการใช้ข้อมูล | 7 | 12% |

---

## แผนการเรียนรายสัปดาห์

> 🧪 งานปฏิบัติการ · 📝 สอบ · 🎤 นำเสนอ

### ช่วงที่ 1 · วิศวกรรมข้อมูลและข้อมูลมหัต

| สัปดาห์ | ชม. | หัวข้อ | เครื่องมือ | CLO | งาน |
| :---: | :---: | --- | --- | :---: | :---: |
| 1 | 4 | ปฐมนิเทศ ภาพรวมการวิเคราะห์ข้อมูลขั้นสูง และการตั้งค่าสภาพแวดล้อม | Python, Jupyter, Git, Conda/venv | 1 | – |
| 2–4 | 12 | **สายท่อข้อมูล** สถาปัตยกรรม Batch และ Stream, Workflow orchestration, ETL/ELT, การบูรณาการและคุณภาพข้อมูล, ดึงข้อมูลจาก REST API สู่ฐานข้อมูล, Scheduling, Error handling, Logging | Python, Apache Airflow | 1 | 🧪 L1 |
| 5–7 | 10 | **การวิเคราะห์ข้อมูลมหัต** Hadoop ecosystem, MapReduce, HDFS, Spark (RDD, DataFrame API, Spark SQL) และการปรับประสิทธิภาพ, Stream processing | PySpark, Kafka, Spark Streaming | 2 | 🧪 L2 |
| 8–9 | 8 | **ข้อมูลไม่มีโครงสร้าง** ข้อความ, NLP pipeline, TF-IDF, Sentiment analysis, ภาพและคอมพิวเตอร์วิทัศน์เบื้องต้น<br>**ข้อมูลหลายมิติ** PCA, Factor analysis, Cluster analysis | Python | 3 | 🧪 L3 |
| 10 | – | **สอบกลางภาค** เนื้อหาสัปดาห์ที่ 1–9 (ข้อเขียน/Lab) | – | 1, 2, 3 | 📝 |

### ช่วงที่ 2 · การเรียนรู้ของเครื่องและการนำเสนอผล

| สัปดาห์ | ชม. | หัวข้อ | เครื่องมือ | CLO | งาน |
| :---: | :---: | --- | --- | :---: | :---: |
| 11–12 | 8 | **การเรียนรู้ของเครื่องสำหรับข้อมูลมหัต** Scalable ML, Feature engineering, Cross-validation, Deep learning, Neural networks, Transfer learning · **เสนอหัวข้อโครงงาน** | scikit-learn, Spark MLlib, TensorFlow/Keras | 4, 8 | 🧪 L4 |
| 13 | 4 | **แนวคิดการแสดงผลข้อมูล** และการเล่าเรื่องด้วยข้อมูล (Data storytelling) | Matplotlib, Seaborn, Plotly | 5, 7 | 🧪 L5 |
| 14 | 4 | **หลักการออกแบบแดชบอร์ด** UX, การเลือกแผนภูมิ, ทฤษฎีสี · รับหัวข้อ BI tool · **รายงานความก้าวหน้าโครงงาน** | แดชบอร์ดเชิงโต้ตอบ | 5 | 🧪 L6 |
| 15 | 4 | **เครื่องมือธุรกิจอัจฉริยะ** นำเสนอผลศึกษาด้วยตนเองคนละ 1 เครื่องมือ และเปรียบเทียบเครื่องมือ | Tableau, Power BI, Looker Studio | 5, 7 | 🎤 |
| 16 | 4 | **การพัฒนาแอปพลิเคชันบนเว็บ** สถาปัตยกรรม การใช้งาน และการเผยแพร่แอปพลิเคชันและแดชบอร์ด | Flask, Streamlit, Dash | 6 | 🧪 L7 |
| 17 | 4 | ทบทวนรายวิชาและแนวโน้มการวิเคราะห์ข้อมูล · **นำเสนอโครงงานและสอบปากเปล่า** (แทนสอบปลายภาค) | – | 1, 2, 4, 6, 7, 8 | 🎤 |

---

## การประเมินผล

| กิจกรรม | สัปดาห์ | CLO | คะแนน |
| --- | :---: | :---: | :---: |
| 🧪 L1 สายท่อข้อมูล | 2–4 | 1 | 4 |
| 🧪 L2 ข้อมูลมหัต | 5–7 | 2 | 4 |
| 🧪 L3 ข้อมูลไม่มีโครงสร้างและหลายมิติ | 8–9 | 3 | 3 |
| 🧪 L4 การเรียนรู้ของเครื่อง | 11–12 | 4 | 4 |
| 🧪 L5 การแสดงผลข้อมูล | 13 | 5 | 1 |
| 🧪 L6 แดชบอร์ด | 14 | 5 | 2 |
| 🧪 L7 เว็บแอปพลิเคชัน | 16 | 6 | 2 |
| 📝 สอบกลางภาค | 10 | 1, 2, 3 | 20 |
| 🎤 นำเสนอหัวข้อศึกษาด้วยตนเอง (BI tool) | 15 | 5, 7 | 10 |
| 🎤 โครงงานย่อยแดชบอร์ด พร้อมสรุปข้อเสนอแนะแก่ผู้ใช้ข้อมูล | 15 | 5, 7 | 10 |
| 🎤 โครงงานประจำวิชา: ชิ้นงานและรายงาน | 17 | 1, 2, 4, 6, 8 | 30 |
| 🎤 โครงงานประจำวิชา: นำเสนอและสอบปากเปล่า | 17 | 4, 6, 7 | 10 |
| **รวม** | | | **100** |

> **เกณฑ์ผ่านรายกิจกรรม:** ร่วมกิจกรรมและส่งงานครบ ได้คะแนนไม่น้อยกว่าร้อยละ 50 · งานนำเสนอ แดชบอร์ด และโครงงานต้องผ่านรูบริกระดับพอใช้ขึ้นไป

<details>
<summary><b>เกณฑ์การตัดเกรด</b> (อิงเกณฑ์)</summary>
<br>

| เกรด | A | B+ | B | C+ | C | D+ | D | F |
| --- | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| **คะแนน** | > 81 | 76–80 | 71–75 | 66–70 | 61–65 | 56–60 | 50–55 | < 50 |

</details>

---

## สถานะงาน

**งานปฏิบัติการ**

- [ ] Lab 01 ตั้งค่าสภาพแวดล้อม Python (venv) และ Git & GitHub
- [ ] L1 สายท่อข้อมูล (Airflow)
- [ ] L2 ข้อมูลมหัต (PySpark)
- [ ] L3 ข้อมูลไม่มีโครงสร้างและหลายมิติ
- [ ] L4 การเรียนรู้ของเครื่อง
- [ ] L5 การแสดงผลข้อมูล
- [ ] L6 แดชบอร์ด
- [ ] L7 เว็บแอปพลิเคชัน

**งานนำเสนอและโครงงาน**

- [ ] เสนอหัวข้อโครงงานประจำวิชา (สัปดาห์ 11–12)
- [ ] รายงานความก้าวหน้าโครงงาน (สัปดาห์ 14)
- [ ] นำเสนอหัวข้อศึกษาด้วยตนเอง: เครื่องมือ BI (สัปดาห์ 15)
- [ ] โครงงานย่อยแดชบอร์ด (สัปดาห์ 15)
- [ ] นำเสนอโครงงานประจำวิชาและสอบปากเปล่า (สัปดาห์ 17)

---

## การติดตั้งและตั้งค่าสภาพแวดล้อม

> **Installation & Setup Guide** ใช้ Python Virtual Environment (`venv`) แยกไลบรารีของ repo นี้ออกจาก Python หลักของเครื่อง

### ขั้นที่ 1 · ติดตั้ง Python และ Git

ดาวน์โหลดและติดตั้ง Python **3.12 ขึ้นไป** จาก [python.org](https://www.python.org/downloads/) และ Git จาก [git-scm.com](https://git-scm.com/downloads) แล้วตรวจสอบเวอร์ชัน:

```bash
python --version    # macOS / Linux ใช้ python3 --version
git --version
```

> - ตอนติดตั้ง Python บน Windows ให้ติ๊ก **Add python.exe to PATH**
> - `requirements.txt` ล็อก numpy 2.5 ซึ่งต้องใช้ Python 3.12 ขึ้นไป (ทดสอบแล้วกับ Python 3.13)

### ขั้นที่ 2 · Clone โปรเจกต์ลงเครื่อง

```bash
git clone https://github.com/tanpharamut/SC-677-704-Advanced-Data-Analytics.git
cd SC-677-704-Advanced-Data-Analytics
```

### ขั้นที่ 3 · สร้างและเปิดใช้งาน venv

สร้าง virtual environment ชื่อ `.venv` ในโฟลเดอร์โปรเจกต์:

```bash
python -m venv .venv     # Windows
python3 -m venv .venv    # macOS / Linux
```

เปิดใช้งาน (activate) ตามโปรแกรมที่ใช้:

| โปรแกรม | คำสั่งเปิดใช้งาน |
| --- | --- |
| Windows · Command Prompt | `.venv\Scripts\activate` |
| Windows · PowerShell | `.venv\Scripts\Activate.ps1` |
| Windows · Git Bash | `source .venv/Scripts/activate` |
| macOS / Linux | `source .venv/bin/activate` |

เปิดสำเร็จเมื่อมี `(.venv)` ขึ้นหน้าบรรทัดคำสั่ง

> ถ้า PowerShell ขึ้นข้อความ *running scripts is disabled on this system* ให้รันคำสั่งด้านล่างครั้งเดียว แล้ว activate ใหม่
>
> ```powershell
> Set-ExecutionPolicy -Scope CurrentUser RemoteSigned
> ```

### ขั้นที่ 4 · ติดตั้งไลบรารีจาก requirements.txt

```bash
python -m pip install --upgrade pip
pip install -r requirements.txt
```

ตรวจว่าติดตั้งครบ แล้วเปิด Jupyter Notebook:

```bash
python -c "import pandas, numpy, requests; print('OK', pandas.__version__, numpy.__version__)"
jupyter notebook
```

### หมายเหตุสำหรับแล็บถัดไป

- ติดตั้งแพ็กเกจเพิ่มเมื่อไร ให้รัน `pip freeze > requirements.txt` ใหม่แล้ว commit ไฟล์นี้ด้วยทุกครั้ง
- หลัง freeze บน Windows ให้เติมเงื่อนไขท้าย 2 บรรทัดนี้ เพื่อให้ macOS / Linux ติดตั้งได้ (ทั้งสองเป็นแพ็กเกจเฉพาะ Windows)
  ```text
  colorama==0.4.6; sys_platform == "win32"
  pywinpty==3.1.2; os_name == "nt"
  ```
- **PySpark** ต้องติดตั้ง Java (JDK 17) และตั้งค่า `JAVA_HOME` ก่อนใช้งาน
- **Apache Airflow** ไม่รองรับ Windows โดยตรง ให้รันผ่าน WSL2 หรือ Docker ตาม [คู่มือของ Airflow](https://airflow.apache.org/docs/apache-airflow/stable/start.html)

---

## คำสั่ง venv และ pip

| คำสั่ง | ใช้ทำอะไร |
| --- | --- |
| `python -m venv .venv` | สร้าง virtual environment ชื่อ `.venv` คือ Python ชุดแยกที่มีไลบรารีของ repo นี้เท่านั้น ไม่ปนกับโปรเจกต์อื่นในเครื่อง |
| `.venv\Scripts\activate` (Windows)<br>`source .venv/bin/activate` (macOS / Linux) | เปิดใช้งาน venv หลังจากนี้คำสั่ง `python` และ `pip` จะใช้ตัวที่อยู่ใน `.venv` |
| `deactivate` | ปิด venv กลับไปใช้ Python หลักของเครื่อง |
| `python -m pip install --upgrade pip` | อัปเกรด pip เป็นเวอร์ชันล่าสุด (บน Windows ต้องเรียกผ่าน `python -m pip` เพราะ pip แก้ไฟล์ตัวเองขณะทำงานไม่ได้) |
| `pip install <แพ็กเกจ>` | ติดตั้งแพ็กเกจจาก PyPI เช่น `pip install pandas numpy requests jupyter` |
| `pip install <แพ็กเกจ>==<เวอร์ชัน>` | ติดตั้งแพ็กเกจเวอร์ชันที่ระบุ |
| `pip uninstall <แพ็กเกจ>` | ถอนการติดตั้งแพ็กเกจ |
| `pip list` | แสดงแพ็กเกจทั้งหมดที่ติดตั้งใน venv พร้อมเวอร์ชัน |
| `pip show <แพ็กเกจ>` | ดูรายละเอียดของแพ็กเกจ เช่น เวอร์ชัน ตำแหน่งที่ติดตั้ง และแพ็กเกจที่ต้องใช้ร่วมกัน |
| `pip freeze > requirements.txt` | ส่งออกรายชื่อแพ็กเกจในรูป `ชื่อ==เวอร์ชัน` ลงไฟล์ เพื่อให้เครื่องอื่นสร้างสภาพแวดล้อมเดียวกันได้ |
| `pip install -r requirements.txt` | ติดตั้งแพ็กเกจทุกตัวตามเวอร์ชันในไฟล์ ใช้หลัง clone repo ลงเครื่องใหม่ |

> **ทำไมไม่ commit โฟลเดอร์ `.venv`** เพราะมีขนาดใหญ่และผูกกับเครื่องและระบบปฏิบัติการที่สร้าง จึงใส่ไว้ใน `.gitignore` แล้ว commit เฉพาะ `requirements.txt` ซึ่งใช้สร้าง venv ขึ้นใหม่ได้ทุกเครื่อง

---

## โครงสร้าง Repository

```text
SC-677-704-Advanced-Data-Analytics/
├── README.md
├── .gitignore
├── requirements.txt                    # รายชื่อไลบรารี Python (pip freeze)
├── .venv/                              # virtual environment (ไม่ถูก track)
├── docs/                               # เอกสารประกอบรายวิชา
│   └── SC677704_Course_Specification.pdf
├── labs/                               # งานปฏิบัติการ
│   ├── Lab01-python-venv-git-setup/    # ใบงาน Lab 01
│   ├── L1-data-pipeline/
│   ├── L2-big-data-spark/
│   ├── L3-unstructured-multivariate/
│   ├── L4-ml-big-data/
│   ├── L5-data-visualization/
│   ├── L6-dashboard/
│   └── L7-web-app/
├── self-study-bi/                      # หัวข้อศึกษาด้วยตนเอง: เครื่องมือ BI
├── dashboard-mini-project/             # โครงงานย่อยแดชบอร์ด
├── final-project/                      # โครงงานประจำวิชา
└── data/                               # ชุดข้อมูลในเครื่อง (ไม่ถูก track)
```

| ไฟล์ / โฟลเดอร์ | คำอธิบาย |
| --- | --- |
| [`docs/`](docs) | เอกสารประกอบรายวิชา เช่น [Course Specification (มคอ.3)](docs/SC677704_Course_Specification.pdf) และสไลด์ประกอบการสอน |
| [`requirements.txt`](requirements.txt) | รายชื่อและเวอร์ชันของไลบรารี Python ที่ใช้ ติดตั้งด้วย `pip install -r requirements.txt` |
| [`labs/Lab01-python-venv-git-setup/`](labs/Lab01-python-venv-git-setup) | ใบงาน Lab 01 การตั้งค่า venv และ Git & GitHub (ผลงานคือ `README.md`, `.gitignore` และ `requirements.txt` ที่ราก repo) |
| [`labs/`](labs) | โค้ดและ notebook ของงานปฏิบัติการ L1–L7 แยกโฟลเดอร์ตามรหัสงานใน Course Specification |
| [`self-study-bi/`](self-study-bi) | สไลด์และไฟล์สาธิตเครื่องมือ BI ที่ได้รับมอบหมาย |
| [`dashboard-mini-project/`](dashboard-mini-project) | ไฟล์แดชบอร์ดและสรุปข้อเสนอแนะแก่ผู้ใช้ข้อมูล |
| [`final-project/`](final-project) | โค้ด รายงาน และสไลด์ของโครงงานประจำวิชา |
| `data/` | เก็บชุดข้อมูลไว้ในเครื่องเท่านั้น ไฟล์ข้อมูลไม่ถูก commit ขึ้น GitHub |

---

## การใช้งาน Git

คู่มือย่อคำสั่ง Git ที่ใช้บ่อยกับ repo นี้ รันใน Git Bash, PowerShell หรือ Terminal โดยเปิดที่โฟลเดอร์ของ repo

### ภาพรวมการทำงาน

```text
 Working dir ─add─▶ Staging ─commit─▶ Local repo ─push─▶ GitHub
      ▲                                                    │
      └─────────────────────── pull ───────────────────────┘
```

| พื้นที่ | ความหมาย |
| --- | --- |
| **Working directory** | โฟลเดอร์ในเครื่องที่เรากำลังแก้ไฟล์อยู่ |
| **Staging area** | พื้นที่พักไฟล์ที่เลือกไว้แล้วว่าจะใส่ใน commit ถัดไป |
| **Local repository** | ประวัติ commit ทั้งหมดที่เก็บในเครื่อง (อยู่ในโฟลเดอร์ซ่อน `.git`) |
| **Remote (`origin`)** | repo บน GitHub ที่ใช้สำรองงานและซิงก์ระหว่างเครื่อง |

### 1. ตั้งค่าครั้งแรก (ทำครั้งเดียวต่อเครื่อง)

```bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
```

| คำสั่ง | ใช้ทำอะไร |
| --- | --- |
| `git --version` | ตรวจว่าติดตั้ง Git แล้วหรือยัง และเป็นเวอร์ชันใด |
| `git config --global user.name "..."` | ตั้งชื่อผู้เขียนที่จะปรากฏในทุก commit |
| `git config --global user.email "..."` | ตั้งอีเมลผู้เขียน ควรตรงกับอีเมลบัญชี GitHub เพื่อให้ commit ผูกกับบัญชี |
| `git config --list` | ดูค่าที่ตั้งไว้ทั้งหมด |

### 2. สร้าง repo ใหม่และอัปโหลดขึ้น GitHub

ใช้เมื่อมีโฟลเดอร์งานในเครื่องอยู่แล้ว ให้สร้าง **New repository** เปล่าบน GitHub ก่อน (ไม่ต้องติ๊กเพิ่ม README หรือ .gitignore บนเว็บ) แล้วรันตามลำดับ:

```bash
git init                         # 1. เริ่มใช้ Git ในโฟลเดอร์โปรเจกต์
git status                       # 2. ตรวจสถานะไฟล์ ต้องไม่เห็นโฟลเดอร์ .venv
git add .                        # 3. เพิ่มไฟล์ทั้งหมดเข้า staging area
git commit -m "Initial commit"   # 4. บันทึก commit แรก
git branch -M main               # 5. ตั้งชื่อ branch หลักเป็น main
git remote add origin https://github.com/<username>/<repo>.git   # 6. เชื่อมกับ repo บน GitHub
git push -u origin main          # 7. อัปโหลดขึ้น GitHub
```

| คำสั่ง | ใช้ทำอะไร |
| --- | --- |
| `git init` | สร้าง Git repository ใหม่ในโฟลเดอร์ปัจจุบัน โดยสร้างโฟลเดอร์ซ่อน `.git` ไว้เก็บประวัติทั้งหมด |
| `git branch -M main` | เปลี่ยนชื่อ branch ปัจจุบันเป็น `main` (`-M` คือบังคับเปลี่ยน แม้มี branch ชื่อนี้อยู่แล้ว) |
| `git remote add origin <url>` | ผูก repo ในเครื่องเข้ากับ repo บน GitHub โดยตั้งชื่อเรียกว่า `origin` |
| `git push -u origin main` | อัปโหลด branch `main` ขึ้น `origin` ครั้งแรก `-u` ให้ Git จำคู่นี้ไว้ ครั้งต่อไปพิมพ์แค่ `git push` หรือ `git pull` |

### 3. ดึง repo ลงเครื่อง

```bash
git clone https://github.com/tanpharamut/SC-677-704-Advanced-Data-Analytics.git
cd SC-677-704-Advanced-Data-Analytics
```

`git clone` คัดลอก repo ทั้งหมดพร้อมประวัติจาก GitHub ลงเครื่อง ทำครั้งเดียวต่อเครื่อง

> repo นี้เป็น private ต้องล็อกอิน GitHub ก่อน ด้วย `gh auth login` หรือผ่านหน้าต่าง Git Credential Manager ที่เด้งขึ้นมาตอน clone

### 4. ทำงานประจำวัน

```bash
git pull                                   # 1. ดึงงานล่าสุดจาก GitHub
git status                                 # 2. ดูว่าไฟล์ไหนถูกแก้
git add labs/L1-data-pipeline              # 3. เลือกไฟล์ที่จะบันทึก
git commit -m "Add L1 data pipeline DAG"   # 4. บันทึกเป็น commit
git push                                   # 5. ส่งขึ้น GitHub
```

| คำสั่ง | ใช้ทำอะไร |
| --- | --- |
| `git pull` | ดึง commit ใหม่จาก GitHub มารวมกับงานในเครื่อง ควรทำก่อนเริ่มงานทุกครั้ง (เท่ากับ `git fetch` ตามด้วย `git merge`) |
| `git status` | แสดงสถานะ ได้แก่ ไฟล์ที่แก้ไข ไฟล์ใหม่ที่ Git ยังไม่ติดตาม และไฟล์ที่ add แล้ว |
| `git diff` | ดูว่าแก้อะไรไปบ้างทีละบรรทัด เฉพาะส่วนที่ยังไม่ add |
| `git diff --staged` | ดูส่วนที่ add แล้วและกำลังจะเข้า commit |
| `git add <ไฟล์หรือโฟลเดอร์>` | ย้ายการแก้ไขเข้า staging area เพื่อเตรียม commit |
| `git add .` | add ทุกไฟล์ที่เปลี่ยนในโฟลเดอร์ปัจจุบัน (ตรวจด้วย `git status` ก่อนเสมอ) |
| `git commit -m "ข้อความ"` | บันทึกสิ่งที่อยู่ใน staging เป็น commit ใหม่ในเครื่อง พร้อมข้อความอธิบาย |
| `git push` | ส่ง commit ในเครื่องขึ้น GitHub |

### 5. ดูประวัติ

| คำสั่ง | ใช้ทำอะไร |
| --- | --- |
| `git log --oneline` | ดูรายการ commit แบบย่อ บรรทัดละ 1 commit |
| `git log --oneline --graph --all` | ดูประวัติเป็นแผนภาพ เห็นทุก branch |
| `git log -- <ไฟล์>` | ดูเฉพาะ commit ที่แก้ไขไฟล์นั้น |
| `git show <hash>` | ดูรายละเอียดและสิ่งที่เปลี่ยนใน commit นั้น (`<hash>` คือรหัส commit เช่น `0345632`) |

### 6. จัดการไฟล์

| คำสั่ง | ใช้ทำอะไร |
| --- | --- |
| `git mv <ที่เดิม> <ที่ใหม่>` | ย้ายหรือเปลี่ยนชื่อไฟล์ Git รู้ว่าเป็นไฟล์เดิม ประวัติจึงไม่หาย |
| `git rm <ไฟล์>` | ลบไฟล์ออกจากเครื่องและจาก repo ใน commit ถัดไป |
| `git rm --cached <ไฟล์>` | เลิกติดตามไฟล์ใน repo แต่ยังเก็บไฟล์ไว้ในเครื่อง ใช้เมื่อเผลอ commit ไฟล์ที่ควรอยู่ใน `.gitignore` |

### 7. ยกเลิกและแก้ไข

| คำสั่ง | ใช้ทำอะไร |
| --- | --- |
| `git restore <ไฟล์>` | ทิ้งการแก้ไขที่ยังไม่ add กลับไปเป็นเวอร์ชันล่าสุดที่ commit ไว้ ⚠️ กู้คืนไม่ได้ |
| `git restore --staged <ไฟล์>` | เอาไฟล์ออกจาก staging (ยกเลิก `git add`) การแก้ไขในไฟล์ยังอยู่ |
| `git commit --amend -m "ข้อความใหม่"` | แก้ข้อความ หรือเพิ่มไฟล์ที่ลืม ลงใน commit ล่าสุด ใช้ได้เฉพาะ commit ที่ **ยังไม่ push** |
| `git reset --soft HEAD~1` | ยกเลิก commit ล่าสุด แต่เก็บการแก้ไขไว้ใน staging ใช้ได้เฉพาะ commit ที่ **ยังไม่ push** |
| `git revert <hash>` | สร้าง commit ใหม่ที่ย้อนผลของ commit นั้น เป็นวิธีที่ปลอดภัยสำหรับ commit ที่ push แล้ว |

<details>
<summary><b>8. Branch</b> แยกทดลองงานโดยไม่กระทบ <code>main</code></summary>
<br>

| คำสั่ง | ใช้ทำอะไร |
| --- | --- |
| `git branch` | แสดง branch ทั้งหมด (`*` คือ branch ที่อยู่ปัจจุบัน) |
| `git switch -c <ชื่อ>` | สร้าง branch ใหม่และสลับไปทันที |
| `git switch <ชื่อ>` | สลับไป branch ที่มีอยู่แล้ว เช่น `git switch main` |
| `git push -u origin <ชื่อ>` | ส่ง branch ใหม่ขึ้น GitHub ครั้งแรก ครั้งต่อไปใช้ `git push` ได้เลย |
| `git merge <ชื่อ>` | รวมงานจาก branch นั้นเข้ามาใน branch ปัจจุบัน |
| `git branch -d <ชื่อ>` | ลบ branch ที่ merge แล้ว |

</details>

<details>
<summary><b>9. Stash และ Remote</b> พักงานชั่วคราว และดูการเชื่อมต่อกับ GitHub</summary>
<br>

| คำสั่ง | ใช้ทำอะไร |
| --- | --- |
| `git stash` | พักงานที่ยังไม่ commit ไว้ชั่วคราว ให้โฟลเดอร์กลับมาสะอาด เช่น ก่อน pull หรือสลับ branch |
| `git stash list` | ดูรายการงานที่พักไว้ |
| `git stash pop` | นำงานที่พักไว้ล่าสุดกลับมา |
| `git remote -v` | ดู URL ของ repo บน GitHub ที่เชื่อมอยู่ |
| `git fetch` | ดาวน์โหลด commit ใหม่จาก GitHub มาดูก่อน โดยยังไม่รวมเข้ากับงานในเครื่อง |

</details>

### การเขียนข้อความ commit

เขียนเป็นภาษาอังกฤษสั้น ๆ ขึ้นต้นด้วยคำกริยา บอกว่า commit นี้ทำอะไร

| คำขึ้นต้น | ใช้เมื่อ | ตัวอย่าง |
| --- | --- | --- |
| `Add` | เพิ่มไฟล์หรืองานใหม่ | `Add L2 PySpark notebook` |
| `Update` | ปรับปรุงงานเดิม | `Update README checklist` |
| `Fix` | แก้ข้อผิดพลาด | `Fix missing value handling in L3` |
| `Move` / `Rename` | ย้ายหรือเปลี่ยนชื่อไฟล์ | `Move course specification into docs folder` |
| `Remove` | ลบไฟล์ | `Remove unused test notebook` |

### ข้อควรระวัง

- **`git pull` ก่อนเริ่มงานทุกครั้ง** โดยเฉพาะเมื่อทำงานหลายเครื่อง เพื่อลดปัญหางานชนกัน (conflict)
- **ไฟล์ใหญ่กว่า 100 MB push ไม่ได้** (GitHub จำกัดขนาดต่อไฟล์) ให้เก็บชุดข้อมูลไว้ใน `data/` ซึ่งไม่ถูก commit
- **ห้าม commit รหัสผ่านหรือ API key** ให้เก็บใน `.env` ซึ่งอยู่ใน `.gitignore` แล้ว
- **ล้าง output ของ notebook ที่ใหญ่มากก่อน commit** (Kernel → Restart & Clear Output) เพื่อให้ repo ไม่บวม
- คำเตือน `LF will be replaced by CRLF` บน Windows เป็นเรื่องปกติ ไม่กระทบเนื้อหาไฟล์

---

## ตำราและแหล่งอ้างอิง

**วิศวกรรมข้อมูลและข้อมูลมหัต**

1. Reis, J., & Housley, M. (2022). *Fundamentals of Data Engineering*. O'Reilly Media.
2. Harenslak, B., & de Ruiter, J. (2021). *Data Pipelines with Apache Airflow*. Manning Publications.
3. Damji, J. S., Wenig, B., Das, T., & Lee, D. (2020). *Learning Spark: Lightning-Fast Data Analytics* (2nd ed.). O'Reilly Media.

**สถิติหลายตัวแปรและการเรียนรู้ของเครื่อง**

4. Johnson, R. A., & Wichern, D. W. (2007). *Applied Multivariate Statistical Analysis* (6th ed.). Pearson.
5. Géron, A. (2022). *Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow* (3rd ed.). O'Reilly Media.

**การแสดงผลข้อมูลและแดชบอร์ด**

6. Knaflic, C. N. (2015). *Storytelling with Data: A Data Visualization Guide for Business Professionals*. Wiley.
7. Few, S. (2013). *Information Dashboard Design: Displaying Data for At-a-Glance Monitoring* (2nd ed.). Analytics Press.

**เอกสารออนไลน์**

- [Apache Airflow](https://airflow.apache.org/docs/) · [Apache Spark](https://spark.apache.org/docs/latest/) · [scikit-learn](https://scikit-learn.org/stable/) · [TensorFlow](https://www.tensorflow.org/api_docs) · [Plotly](https://plotly.com/python/) · [Streamlit](https://docs.streamlit.io/) · [Tableau](https://help.tableau.com/) · [Microsoft Power BI](https://learn.microsoft.com/power-bi/)
- เอกสารประกอบการสอนและชุดข้อมูลในระบบ KKU e-Learning ของรายวิชา

---

## นโยบายการใช้เครื่องมือ AI

ตามรายละเอียดรายวิชา

1. **อนุญาต** ให้ใช้ในงานปฏิบัติการ หัวข้อศึกษาด้วยตนเอง โครงงานย่อยแดชบอร์ด และโครงงานประจำวิชา
2. ต้อง **ระบุเครื่องมือที่ใช้และลักษณะการใช้** ไว้ในงานที่ส่ง และต้องอธิบายงานของตนเองได้ในการนำเสนอและสอบปากเปล่า
3. **ไม่อนุญาต** ให้ใช้ในการสอบกลางภาค
4. **ห้าม** นำข้อมูลส่วนบุคคลหรือข้อมูลที่เป็นความลับเข้าเครื่องมือ AI
