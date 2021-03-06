# DWDM21
Data Warehouse &amp; Data Mining 2021

Thitiwat Jantharasena 623021047-5
Group Name: Natasha Romanoff

1. 623021047-5	ฐิติวัฒน์ จันทรเสนา

2. 623021042-5	ขนิษฐา ภูโสภา

3. 623021043-3	จิตติยา ศิริธรรมจักร

4. 623020514-5	จุฑากาญจน์ ชิงจันทร์

5. 623021046-7	ชนกานต์ พูลผล

# สารบัญเนื้อหา

วิชา Data Mining and Data Warehouse

* บทที่ 1 [introduction](https://github.com/ThitiwatJtrsn/DWDM21/blob/main/HW1.pdf) ประกอบด้วยหัวข้อ ดังนี้

  * DAIS ประกอบด้วย
  * ทำไมต้องทำ Data Mining?
  * Data Mining คืออะไร?
  * ขั้นตอนการทำ DataMining
  * ตัวอย่างการนำเหมืองข้อมูลไปใช้งาน
  
* บทที่ 2 Getting to Know Your Data ประกอบด้วยหัวข้อ ดังนี้

**Lecture**

  * [สรุปการบ้านคาบ 1 Know your data](https://github.com/ThitiwatJtrsn/DWDM21/blob/main/HW2.1.pdf)

**Googlecolab**

  * [Basic Python](https://github.com/ThitiwatJtrsn/DWDM21/blob/main/Data101_(Chapter2).ipynb)
    * Casting
    * Data Structure
    * List
    * Loop
    * Condition
    * Function
  * [Plot Data](https://github.com/ThitiwatJtrsn/DWDM21/blob/main/Data102_(Chapter2).ipynb)
    * Besic Data
    * การตรวจสอบตารางข้อมูลโดยใช้ .head()&.tail()
    * Boxplot
    * Time Series Plot
  * [Visualizetion](https://github.com/ThitiwatJtrsn/DWDM21/blob/main/Data_Visualization.ipynb)
    * Scatter plot
    * Plot
    * Bar chart
    * Histogram
  * [Distance Numpy](https://github.com/ThitiwatJtrsn/DWDM21/blob/main/Distance_Numpy.ipynb)
    * Numpy Array
    * Distance Matrix
    
* บทที่ 3 [Data Preprocessing](https://github.com/ThitiwatJtrsn/DWDM21/blob/main/Data_Preprocessing(Chapter_3).ipynb) ประกอบด้วยหัวข้อ ดังนี้

  * Meta Data
  * การจัดการข้อมูลในตารางก่อนนำไปวิเคราะห์
    * การชี้ข้อมูลในตาราง
      * ชี้แบบธรรมดา
      * ชี้แบบ .iloc[
    * Missing Value
      * Handle Missing Value 1 (ลบค่า Missing)
      * Handle Missing Value 1.5 (ลบค่า Missing เฉพาะใน column ที่เราสนใจ)
      * Handle Missing Value 2
      * Handle Missing Value 3 (แทนด้วย class ใหม่ (ค่าที่เหมาะสม))
      * Handle Missing Value 4 (แทนด้วยค่ากลาง)
      * Handling Missing Value 5 (แทนด้วย column ใกล้เคียง)
    * PANDA
      * Select data by values [PD]
      * ใช้ & (and) และ | (or) ในการรวม list ของ boolean
    * Quiz 4
      * การต่อตารางแนวแกน Y [PD]
      * Handling Missing Value 5 (แทนด้วย ค่ากลางของ samples ใน class เดียวกัน)(ต่อ)
      * การเรียงข้อมูล[PD]
      * utlier
    * Quiz 5
      * Pandas' looping(.iterrows)
    * การรวม 2 ตารางโดยใช้ .merge()
      * Group by (pandas)
      * [PD] save ตารางเอาไปใช้ที่อื่น
      * [PD]การสร้างตาราง

* บทที่ 4 [Data Warehousing and On-line Anaalytical Processing ](https://github.com/ThitiwatJtrsn/DWDM21/blob/main/Chapter_4.pdf) ประกอบด้วยหัวข้อ ดังนี้

  * Basic Data Warehouse
    * อะไรคือคลังข้อมูล
    * วัตถุประสงค์
    * การบูรณาการ
  * Data Cube and OLAP
    * OLTP vs. OLAP
    * Data Cubes
    * Conceptual Modeling of Data Warehouse
  * การออกแบบ และการใช้งานคลังข้อมูล
  * ความสำคัญของคลังข้อมูล

* บทที่ 5 [Association_Rules ](https://github.com/ThitiwatJtrsn/DWDM21/blob/main/Chapter_6_Association_Rules.ipynb) ประกอบด้วยหัวข้อ ดังนี้

  * ความหมาย
  * Besic Concepts
    * Plot graph of Itemsets
    * การแก้ไขคอลัมน์ข้อมูล
    * Frequence Itemsets to Association Rule
  * Efficient Pattern Mining Methods
    * Apriori
    * Support

* บทที่ 6 บทที่ 6 Classification ประกอบด้วยหัวข้อ ดังนี้

  * [Desition Tree](https://github.com/ThitiwatJtrsn/DWDM21/blob/main/Chapter7_Classification_(Decision_Tree).ipynb)
    * Train Model
    * plot tree
    * Evaluation
    * Random
    * Advanced Tree
    * TEST
  * [KNN](https://github.com/ThitiwatJtrsn/DWDM21/blob/main/Chap7_Classification_(KNN_NN).ipynb)
    * Split Data
    * Train Model
    * Retrain & Evaluate
    * Neural Network
  * [Evaluation](https://github.com/ThitiwatJtrsn/DWDM21/blob/main/Chap7_Classification_(Evaluation).ipynb)
    * Split Data หรือ แบ่ง Data
    * สร้าง Model ทำนาย
    * Evaluation

* บทที่ 7 [Clustering  ](https://github.com/ThitiwatJtrsn/DWDM21/blob/main/Chap8_Clustering.ipynb) ประกอบด้วยหัวข้อ ดังนี้
  * K-means
    * Generate Data
    * Clustering
    * Example Application (Color Quantization)
    * การนับจำนวนสี

  * โครงงานกลุ่ม[ Project](https://github.com/ThitiwatJtrsn/DWDM21/blob/main/ProjectFinal.ipynb)
    * สไลด์นำเสนอ [Slide Present](https://github.com/ThitiwatJtrsn/DWDM21/blob/main/Project.pdf)
