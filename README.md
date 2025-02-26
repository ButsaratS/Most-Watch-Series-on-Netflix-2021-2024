## Netflix ควรลงทุนกับซีรีส์แนวไหน: ประเภทของซีรีส์ที่ถูกใจผู้ชม

### Data Source:
- 〜20241227 Netflixdata<br>
https://www.kaggle.com/datasets/risakashiwabara/netfllix-weekly-views-data

- Netflix TV Shows and Movies (2022 Updated)<br>
https://www.kaggle.com/datasets/thedevastator/the-ultimate-netflix-tv-shows-and-movies-dataset

- IMDb TV Shows Latest 2023<br>
https://www.kaggle.com/datasets/lokeshparab/imdb-tv-shows-dataset-latest<br>

__________________________________________________________________________________________________________________________________________________________________________________
### คำถามที่ 1: 10 อันดับซีรีส์ยอดนิยมของ Netflix ในปี 2022-2024 มีอะไรบ้าง<br>

กราฟที่ 1 แสดง 10 อันดับซีรีส์ที่มีจำนวนชั่วโมงการรับชมสูงสุดบน Netflix ในแต่ละปี ตั้งแต่ช่วงครึ่งปีหลังของปี 2021 และ ปี 2022 ถึง 2024 ข้อมูลนี้ได้มาจากการรวบรวมยอดรับชมรายเดือนและสรุปรวมเป็นยอดวิวรายปี จากนั้นนำมาเรียงลำดับเพื่อเลือกซีรีส์ 10 อันดับแรกของแต่ละปี เป้าหมายของกราฟนี้คือการช่วยให้เราเห็นแนวโน้มของซีรีส์ที่ได้รับความนิยมสูงสุดในแต่ละปีและการเปลี่ยนแปลงของพฤติกรรมการรับชมของผู้ใช้ Netflix
- **ปี 2021: Squid Game ครองอันดับ 1 อย่างท่วมท้น** ครองอันดับ 1 ด้วยยอดชมเกิน 3 พันล้านชั่วโมง ซีรีส์แนวอาชญากรรมและดราม่า เช่น Money Heist และ You ก็ติดอันดับสูงเช่นกัน ซีรีส์วัยรุ่นและโรแมนติก เช่น Sex Education และ Virgin River เองก็มีฐานผู้ชมที่แข็งแกร่ง
- **ปี 2022: Stranger Things กลับมายึดบัลลังก์** Stranger Things ซีซั่น 4 เป็นซีรีส์ที่มียอดวิวสูงสุด ซีรีส์แนวสยองขวัญและอาชญากรรม เช่น Wednesday และ DAHMER ก็ติดอันดับสูง Bridgerton ยังคงได้รับความนิยมจากซีซั่น 2
- **ปี 2023 Ginny & Georgia ครองอันดับ 1** แสดงให้เห็นว่าซีรีส์แนวดราม่า-ครอบครัวสามารถเข้าถึงผู้ชมได้มากขึ้น The Night Agent และ The Glory ติดอันดับ แสดงให้เห็นความนิยมของซีรีส์แนวแอ็กชันและดราม่า ONE PIECE ซึ่งเป็นซีรีส์ Live-Action ดัดแปลงจากมังงะชื่อดังก็มียอดรับชมสูง
- **ปี 2024 Bridgerton กลับมาเป็นซีรีส์ที่มีคนดูมากที่สุด** Queen of Tears และ Fool Me Once เป็นซีรีส์ใหม่ที่มาแรง ซีรีส์แนวแอ็กชันและแฟนตาซี เช่น Prison Break และ Avatar: The Last Airbender ยังคงได้รับความนิยม<br>

**กราฟที่ 1:** Top 10 Most Watched Netflix Shows<br>

![Top 10 Shows](https://github.com/user-attachments/assets/9416ae2e-c061-46a2-9367-74fd71223ac9)

__________________________________________________________________________________________________________________________________________________________________________________

### คำถามที่ 2: ช่วงเวลาไหนที่ซีรีส์มียอดวิวสูงที่สุด<br>

เพื่อศึกษาว่าช่วงเวลาไหนที่ซีรีส์มียอดวิวสูงที่สุด เราได้นำข้อมูลที่บันทึกจำนวนชั่วโมงการรับชมซีรีส์ในแต่ละสัปดาห์มาทำการประมวลผล โดยคำนวณยอดวิวรายเดือนของแต่ละปีเพื่อดูแนวโน้มภาพรวมและค้นหาช่วงเวลาที่ยอดวิวสูงสุดของแต่ละปี<br>

ข้อมูลจากกราฟที่ 2 แสดงให้ว่าช่วงเวลาที่ยอดวิวซีรีส์ใน Netflix เพิ่มสูง มีสาเหตุมาจาก 2 ปัจจัยคือ:<br>

**1. ช่วงวันหยุดยาวต้นปีและปลายปี**<br>
- เดือนมกราคมและธันวาคม มีจำนวนชั่วโมงการรับชมสูงกว่าหลายเดือนอื่น ๆ ในทุกปี<br>
- เดือนมกราคม: เป็นช่วงวันหยุดปีใหม่ หลายคนอยู่บ้านพักผ่อน ทำให้มีการรับชมซีรีส์และภาพยนตร์สูงขึ้น<br>
- เดือนธันวาคม: เป็นช่วงเทศกาลคริสต์มาสและปีใหม่ หลายครอบครัวมีเวลาว่างมากขึ้น จึงใช้เวลาดู Netflix มากขึ้น<br>
- หลังจากเดือนมกราคม ยอดรับชมมักลดลงทันที ซึ่งสะท้อนถึงการกลับเข้าสู่กิจวัตรปกติของผู้คนหลังวันหยุด<br>
<br>

**2. การ Premiere ซีรีส์ดังในปีนั้น**<br>
- กันยายน 2021: เป็นช่วงที่ยอดวิวพุ่งสูงผิดปกติอย่างมาก ซึ่งเป็นผลมาจากการที่ Squid Game Premiere ในวันที่ 17 กันยายน 2021 และกลายเป็นกระแสไปทั่วโลก ส่งผลให้จำนวนชั่วโมงการรับชมในเดือนนี้เพิ่มขึ้นอย่างมากและเพิ่มสูงสุดในเดือนตุลาคม
- กรกฎาคม 2022: ยอดวิวเพิ่มขึ้นสูงกว่าปกติ เนื่องจาก Stranger Things ซีซั่น 4 Premiere ในวันที่ 1 กรกฎาคม 2022 ซึ่งเป็นซีรีส์ได้รับความนิยมอย่างมาก และดึงดูดผู้ชมจำนวนมหาศาลให้กลับมาดู Netflix
- มกราคมปี 2023: ยอดวิวสูงที่สุดในปีนั้น อันเป็นผลมาจากซีรีส์เรื่อง Ginny & Georgia ที่ Premiere ในเดือนมกราคม
- มีนาคม มิถุนายน และกันยายน 2024: เดือนเหล่านี้มีแนวโน้มการรับชมที่สูงขึ้นในปี 2024 ซึ่งมาจากการ Premiere ซีรีส์ดังอย่าง The Gentlemen, Bridgerton และ Monsters: The Lyle and Erik Menendez Story ตามลำดับ

<br>

**กราฟที่ 2:** Monthly Trends of Hours Viewed by Year
<br>

![Monthly Trends of Weekly Hours Viewed by Year](https://github.com/user-attachments/assets/15432d07-63ba-42a9-9c85-e713bc2ee031)


__________________________________________________________________________________________________________________________________________________________________________________
### คำถามที่ 3: ความยาวของซีรีส์สัมพันธ์กับความนิยมหรือไม่<br>

กราฟที่ 3 แสดงความสัมพันธ์ระหว่างระยะเวลาของซีรีส์กับจำนวนชั่วโมงการรับชมต่อสัปดาห์ โดยมีเป้าหมายเพื่อวิเคราะห์ว่าซีรีส์ที่มีความยาวมากขึ้นมีแนวโน้มได้รับความนิยมมากขึ้นหรือไม่
- **ซีรีส์ที่ได้รับความนิยมสูงสุดส่วนใหญ่อยู่ในช่วง 4-10 ชั่วโมง** จุดข้อมูลจำนวนมากกระจุกตัวอยู่ในช่วง Runtime 4-10 ชั่วโมง และมีจำนวนชั่วโมงการรับชมสูง ซีรีส์ที่มีการรับชมสูงสุดบางเรื่อง (~200 ล้านชั่วโมง) ก็อยู่ในช่วงนี้ แสดงให้เห็นว่าซีรีส์ที่มีความยาวปานกลาง (ประมาณ 4-10 ชั่วโมง) มักได้รับความนิยมมากที่สุด อาจเป็นเพราะผู้ชมสามารถรับชมจบได้เร็วและติดตามได้ง่าย
- **ซีรีส์ที่ยาวมาก (เกิน 12 ชั่วโมง) มีแนวโน้มได้รับความนิยมลดลง** จุดข้อมูลที่มี Runtime เกิน 12 ชั่วโมงขึ้นไป มีจำนวนการรับชมลดลงอย่างเห็นได้ชัด มีเพียงไม่กี่เรื่องที่มี Runtime เกิน 18 ชั่วโมงขึ้นไปและได้รับความนิยมสูง
<br>

**กราฟที่ 3:** Relationship Between Runtime and Weekly Hours Viewed
<br>

![Relationship Between Runtime and Weekly Hours Viewed](https://github.com/user-attachments/assets/b35d2f6c-d6f5-4544-ab85-e48116c2636c)

__________________________________________________________________________________________________________________________________________________________________________________
### คำถามที่ 4: ซีรีส์ประเภทไหนถูกใจคนดู
เพื่อหาว่าซีรีส์ที่ติด 10 อันดับในปี 2021-2024 เป็นซีรีส์ประเภทไหนบ้าง เราได้ทำการหาความถี่ของประเภทซีรีส์ 10 อันดับ กราฟที่ 4 Heatmap แสดงความถี่ของประเภทซีรีส์ที่ติด 10 อันดับปี 2021-2024<br>
- **Drama ครอง 10 อันดับสูงสุดในทุกปี** Drama เป็นประเภทที่มีจำนวนซีรีส์ติด Top 10 มากที่สุด โดยเฉพาะในปี 2022 ดราม่ามักจะผสมกับแนวอื่น เช่น Crime-Drama, Thriller-Drama, หรือ Romance-Drama
- **Action, Crime และ Thriller ได้รับความนิยมอย่างต่อเนื่อง** มีซีรีส์ติดอันดับแทบทุกปี Thriller มีสีเข้มขึ้นในปี 2023 และ 2024 แสดงว่ามีแนวโน้มได้รับความนิยมมากขึ้น
- **Comedy, Romance และ Thriller เติบโตขึ้นในปีหลัง** ในปี 2023 และ 2024 แนว Comedy, Romance และ Thriller มีสีเข้มขึ้น แสดงว่ามีซีรีส์แนวนี้ติด 10 อันดับสูงสุดเพิ่มขึ้น ซึ่งอาจสะท้อนแนวโน้มที่ผู้ชมต้องการ คอนเทนต์ที่ดูง่าย สนุกสนาน และผ่อนคลายมากขึ้น
- **Mystery มีจำนวนซีรีส์ติด 10 อันดับในบางปี** (โดยเฉพาะ 2022) แต่ไม่ได้มีแนวโน้มเพิ่มขึ้นชัดเจน
- **Horror ติดอันดับในบางปี** ในปี 2022 มีซีรีส์ประเภท Horror ติดอันดับ เนื่องมาจากซีรีส์ดังอย่าง Stranger Things ที่เป็นซีรีส์ประเภท Fantasy-Horror
<br>

**กราฟที่ 4:** Heatmap of Genre Distribution
![Heatmap of Genre Distribution (2021-2024)](https://github.com/user-attachments/assets/1b321b81-92a5-4f34-a3a4-d138d6f9dac1)

**กราฟที่ 5:** Views by Genre per Year
![Views by Genre per Year](https://github.com/user-attachments/assets/a7769d2b-d31d-444d-9636-38369e9bce73)

**กราฟที่ 6:** Most Watched Netflix Genres by Year
![Most Watched Netflix Genres by Year (2022-2024)](https://github.com/user-attachments/assets/71998f00-7def-4984-b98c-c53279c649b1)
__________________________________________________________________________________________________________________________________________________________________________________
### Part 2: วิเคราะห์แนวโน้มประเภทเนื้อหาที่ได้รับความนิยม (2022-2024)<br>

กราฟที่ 3 แสดงให้เห็นว่า
- Drama เป็นแนวที่ได้รับความนิยมสูงสุด มียอดรับชมสูงที่สุดเมื่อเทียบกับซีรีส์ประเภทอื่นๆ โดยเฉพาะในปี 2022 ยอดชมในปี 2023 และ 2024 ลดลงจากปี 2022 แต่ยังคงสูงกว่าประเภทอื่น ๆ
- Comedy มียอดชมเพิ่มขึ้นในปี 2023 ในปี 2023 Comedy มีจำนวนชั่วโมงการรับชมสูงกว่าปีอื่น ๆ อาจเกิดจากการเปิดตัวซีรีส์หรือภาพยนตร์ Comedy ที่ได้รับความนิยมมาก
- Crime และ Action มีแนวโน้มใกล้เคียงกัน Crime มียอดชมสูงสุดในปี 2022 แต่ลดลงในปี 2023 และ 2024 Action มีแนวโน้มคงที่ตลอดทั้งสามปี
- Romance มียอดสตรีมมิ่งเพิ่มขึ้นทุกปี สะท้อนถึงความต้องการของผู้ชมที่หันมาสนใจคอนเทนต์แนวโรแมนติกมากขึ้น
- Thriller มีแนวโน้มยอดชมคงที่ในทุกปี
<br>






