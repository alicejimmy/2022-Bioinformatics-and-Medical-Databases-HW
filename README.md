# Bioinformatics and Medical Databases HW
## 交響樂團資料庫
* 一家音樂公司打算將交響樂團資料建成資料庫, 經系統分析後, 得到如下的需求(Requirements)：
  * CONCERT SEASON：將要演出一系列音樂會的季節；識別子為 Opening-date，包含Month、Day、與 Year。
  * CONCERT：一或多首作品的演出；識別子為 Concert_Number，另一重要的屬性為
  * Concert_Date，由 Month、Day、Year 與 Time 組成。每場音樂會通常有不只一個演出日期。
  * COMPOSITION：每場音樂會所要演出的曲目；識別子為 Composition_ID，包含Composer_Name 與 Composition_Name。另一屬性為 Movement_ID，由 Movement_Number與 Movement_Name 構成。許多、但不是所有曲目都有多個樂章。
  * CONDUCTOR：音樂會的指揮；識別子為 Conductor_ID，另一屬性為 Conductor_Name。
  * SOLOIST：在特定音樂會的特定曲目中表演的獨奏者<或獨唱者>；識別子為Soloist_ID，另一屬性為 Soloist_Name。
  * 音樂季中會安排一或多場音樂會；特定音樂會只會安排在一個音樂季中。
  * 音樂會會演出一或多個曲目；一個曲目可能在一或多場音樂會中演出，也可能不會演出。
  * 每場音樂會有一位指揮；一位指揮可能指揮任意數目的音樂會，也可能沒有指揮任何音樂會。
  * 每個曲目可能需要一位或多位獨奏者，也可能不需要獨奏者；一位獨奏者可能會在特定音樂會中演出一或多首曲目，也可能不會演出任何曲目。交響樂團希望能紀錄獨奏者上一次演出特定曲目的日期<Date_Last_Performed>。
## 校務教務資料庫
* 因應大數據時代的來臨，日前各大學紛紛成立校務行政辦公室，以整合校內各式各樣的資料，其中一所大學的校務行政電腦化中的”教務資料庫”，經系統分析後，得到如下需求：
  * 此大學由幾個學院（SCHOOL）如文學院、工學院、與資電學院等學院組成，每個學院有學院代碼（sch-id）與學院名稱（sch-name），學院代碼可區別不同的學院，每一學院有一院長，由一教授擔任。
  * 每個學院由許多學系（DEPARTMENT）組成，每一學系有系代碼（dept-id）、系名（dept-name），系代碼可區別不同學系；每個系會開許多課程（COURSE），但一課程僅由一學系開授，每一課程有課程代碼（crs-id）、名稱（crs-name）、課程說明（crs-description）、及學分數（crs-credit），課程代碼可區別不同課程。
  * 每一學系有許多學生（STUDENT），每個學生有學生代碼（stud-id）、學生姓名（stud-name）與電子信箱（stud-email），其中有學生可能會有多個電子信箱，學生代碼可區別不同學生。
  * 每一學系由許多教授（PROFESSOR）組成，每一教授隸屬於一學系，每一教授有教職員工代碼（prof-id）、員工姓名（prof-name）、與職稱（prof-rank），教職員工代碼可區別不同教授。
  * 每一教授可以開許多門課，一門課也能由多位教授開課。
  * 每一學生可以修許多的課程，每一課程也可許多學生來修，每一學生修的課程有一成績（grade）。
  * 學生對修某一位老師的課程可以給期中評量(mid-eval)與期末評量(final-eval)。
 ### Homework
 * HW1：ER Model
 * HW2：Relational Schema
 * HW3：Relational Algebra
 * Final Project：宗教及宗教活動資料庫

