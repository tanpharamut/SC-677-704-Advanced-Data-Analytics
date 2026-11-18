<div align="center">

# SC 677 704 Advanced Data Analytics

### การวิเคราะห์ข้อมูลขั้นสูง

![Python](https://img.shields.io/badge/Python-3.11%2B-3776AB?logo=python&logoColor=white)
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

- [ข้อมูลรายวิชา](#ข้อมูลรายวิชา)
- [เกี่ยวกับรายวิชา](#เกี่ยวกับรายวิชา)
- [ผลลัพธ์การเรียนรู้](#ผลลัพธ์การเรียนรู้)
- [แผนการเรียนรายสัปดาห์](#แผนการเรียนรายสัปดาห์)
- [การประเมินผล](#การประเมินผล)
- [สถานะงาน](#สถานะงาน)
- [การติดตั้งสภาพแวดล้อม](#การติดตั้งสภาพแวดล้อม)
- [โครงสร้าง Repository](#โครงสร้าง-repository)
- [ตำราและแหล่งอ้างอิง](#ตำราและแหล่งอ้างอิง)
- [นโยบายการใช้เครื่องมือ AI](#นโยบายการใช้เครื่องมือ-ai)

---

## ข้อมูลรายวิชา

| หัวข้อ | รายละเอียด |
| --- | --- |
| **รหัสและชื่อวิชา** | SC 677 704 การวิเคราะห์ข้อมูลขั้นสูง (Advanced Data Analytics) |
| **หน่วยกิต** | 3(2-2-5) บรรยาย 2 ชม. · ปฏิบัติการ 2 ชม. · ศึกษาด้วยตนเอง 5 ชม. ต่อสัปดาห์ |
| **อาจารย์ผู้รับผิดชอบและผู้สอน** | ผศ.ดร.เปรม จันทร์สว่าง |
| **วันและเวลา** | พุธ และ ศุกร์ 10:00–12:00 น. |
| **สถานที่** | ห้องบรรยายและห้องปฏิบัติการคอมพิวเตอร์ ภาควิชาสถิติ คณะวิทยาศาสตร์ |
| **รูปแบบการเรียน** | บรรยาย + ปฏิบัติการ ในชั้นเรียน (Classroom-based learning) |
| **วิธีจัดการเรียนรู้** | Problem-based · Task-based · Project-based learning · Case discussion |
| **วิชาบังคับก่อน** | ไม่มี |

---

## เกี่ยวกับรายวิชา

รายวิชานี้ครอบคลุมงานวิเคราะห์ข้อมูล **ครบวงจร** ตั้งแต่การสร้างสายท่อข้อมูล การประมวลผลข้อมูลมหัตแบบกระจาย การวิเคราะห์ข้อมูลไม่มีโครงสร้างและข้อมูลหลายมิติ การเรียนรู้ของเครื่อง ไปจนถึงการแสดงผลข้อมูล แดชบอร์ด และเว็บแอปพลิเคชันเพื่อนำเสนอผล

```text
 รวบรวมข้อมูล  ──▶  ประมวลผลข้อมูลมหัต  ──▶  วิเคราะห์และสร้างแบบจำลอง  ──▶  นำเสนอผล
 Data pipeline       Hadoop · Spark            NLP · PCA · ML · DL            Viz · Dashboard · Web app
 (Airflow)           (PySpark)                 (scikit-learn · MLlib · Keras)  (Plotly · BI tools · Streamlit)
```

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

## การติดตั้งสภาพแวดล้อม

ซอฟต์แวร์ที่ใช้: Python 3.11+, Jupyter Notebook, Git, Apache Airflow, Apache Spark (PySpark), scikit-learn, TensorFlow/Keras, Matplotlib, Seaborn, Plotly, Flask, Streamlit, Dash และเครื่องมือ BI (Tableau, Power BI, Looker Studio)

สร้าง environment ด้วย Miniconda (เปิด **Anaconda Prompt** แล้วรันทีละบรรทัด):

```bash
conda create -n ada704 python=3.11 -y
conda activate ada704
pip install numpy pandas scipy scikit-learn statsmodels jupyter requests sqlalchemy
pip install pyspark nltk tensorflow matplotlib seaborn plotly flask streamlit dash
```

> **หมายเหตุ**
> - **PySpark** ต้องติดตั้ง Java (JDK 17) และตั้งค่า `JAVA_HOME` ก่อนใช้งาน
> - **Apache Airflow** ไม่รองรับ Windows โดยตรง ให้รันผ่าน WSL2 หรือ Docker ตาม [คู่มือของ Airflow](https://airflow.apache.org/docs/apache-airflow/stable/start.html)

บันทึกสภาพแวดล้อมสำหรับแนบไปกับงาน:

```bash
conda env export --no-builds > environment.yml
```

---

## โครงสร้าง Repository

```text
SC-677-704-Advanced-Data-Analytics/
├── README.md
├── .gitignore
├── SC677704_Course_Specification.pdf   # รายละเอียดรายวิชา (มคอ.3)
├── labs/                               # งานปฏิบัติการ L1–L7
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
| [SC677704_Course_Specification.pdf](SC677704_Course_Specification.pdf) | เอกสาร Course Specification ฉบับเต็ม |
| [`labs/`](labs) | โค้ดและ notebook ของงานปฏิบัติการแต่ละครั้ง แยกโฟลเดอร์ตามรหัสงาน |
| [`self-study-bi/`](self-study-bi) | สไลด์และไฟล์สาธิตเครื่องมือ BI ที่ได้รับมอบหมาย |
| [`dashboard-mini-project/`](dashboard-mini-project) | ไฟล์แดชบอร์ดและสรุปข้อเสนอแนะแก่ผู้ใช้ข้อมูล |
| [`final-project/`](final-project) | โค้ด รายงาน และสไลด์ของโครงงานประจำวิชา |
| `data/` | เก็บชุดข้อมูลไว้ในเครื่องเท่านั้น ไฟล์ข้อมูลไม่ถูก commit ขึ้น GitHub |

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
