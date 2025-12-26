# คู่มือการเขียน Hyperparameter ให้ถูกต้อง

## การสะกดที่ถูกต้อง

### ✅ ถูกต้อง
```
hyperparameter
```

**การแบ่งคำ:** hyper-parameter
- **hyper** = ไฮเปอร์ (แปลว่า "เกิน" หรือ "เหนือ")
- **parameter** = พารามิเตอร์ (แปลว่า "ตัวแปร" หรือ "ค่าคงที่")

### ❌ ผิด
```
hyperpameter   ← ผิด! ขาด r หลัง p
hyperparmeter  ← ผิด! ลำดับตัวอักษรผิด
hyperparamter  ← ผิด! ลำดับตัวอักษรผิด
```

## วิธีจำให้ขึ้นใจ

1. **จำคำว่า "parameter" ก่อน**
   - p-a-r-a-m-e-t-e-r
   - พารา (para) + มีเตอร์ (meter)

2. **แล้วเติม "hyper" ข้างหน้า**
   - hyper + parameter = hyperparameter
   - ไฮเปอร์ + พารามิเตอร์ = ไฮเปอร์พารามิเตอร์

3. **จำว่า: มี r อยู่ 2 ตัว**
   - hype**r**-pa**r**ameter
   - ตัวแรกอยู่หลัง "hype"
   - ตัวที่สองอยู่หลัง "pa"

## ตัวอย่างการใช้งาน

### ในประโยคภาษาอังกฤษ:
```python
# ✅ ถูกต้อง
"We need to tune the hyperparameters of our model."
"Hyperparameter optimization is crucial for model performance."
"Common hyperparameters include learning rate and batch size."
```

### ในโค้ด Python:
```python
# ✅ ถูกต้อง
from sklearn.model_selection import GridSearchCV

# กำหนด hyperparameters ที่ต้องการทดสอบ
hyperparameters = {
    'max_depth': [3, 5, 10],
    'min_samples_split': [2, 5, 10]
}

# ทำ hyperparameter tuning
grid_search = GridSearchCV(model, hyperparameters, cv=5)
```

## คำศัพท์ที่เกี่ยวข้อง

| English | ภาษาไทย | หมายเหตุ |
|---------|---------|----------|
| hyperparameter | ไฮเปอร์พารามิเตอร์ | ค่าที่ต้องกำหนดก่อนเทรน |
| parameter | พารามิเตอร์ | ค่าที่โมเดลเรียนรู้จากข้อมูล |
| hyperparameter tuning | การปรับ hyperparameter | กระบวนการหาค่า hyperparameter ที่ดีที่สุด |
| optimization | การหาค่าที่เหมาะสมที่สุด | เป้าหมายของ tuning |
| grid search | การค้นหาแบบตาราง | วิธีหนึ่งในการ tune |
| random search | การค้นหาแบบสุ่ม | อีกวิธีหนึ่งในการ tune |

## ความแตกต่างระหว่าง Parameter กับ Hyperparameter

### Parameter (พารามิเตอร์)
- **คือ:** ค่าที่โมเดลเรียนรู้จากข้อมูล
- **ตัวอย่าง:** น้ำหนัก (weights) ใน neural network
- **การกำหนด:** โมเดลหาเองระหว่างการ training

### Hyperparameter (ไฮเปอร์พารามิเตอร์)
- **คือ:** ค่าที่เราต้องกำหนดก่อนเริ่ม training
- **ตัวอย่าง:** learning rate, number of layers, batch size
- **การกำหนด:** เราต้องกำหนดเองหรือใช้ tuning หา

## เคล็ดลับเพิ่มเติม

1. **ใช้ Auto-complete:** ใน IDE หรือ text editor ที่ดี พิมพ์ `hyper` แล้วกด Tab มันจะ complete ให้เอง

2. **ตั้งค่า Spell Checker:** ให้รู้จักคำว่า "hyperparameter"

3. **Copy-Paste จากที่ถูกต้อง:** ถ้าไม่แน่ใจ ให้ copy จาก documentation อย่างเป็นทางการ

4. **ฝึกเขียนบ่อยๆ:** ยิ่งเขียนบ่อยยิ่งจำได้

## การตรวจสอบการสะกด

### ใน Python/Jupyter:
```python
# ถ้าเขียนผิด จะมี error
from sklearn.model_selection import GridSearchCV  # ✅
from sklearn.model_selection import GridSerachCV  # ❌ typo!
```

### ใน Text:
- ใช้ spell checker ใน IDE
- ใช้ Grammarly หรือเครื่องมือตรวจสอบตัวสะกด
- Search ใน Google ดูว่าผลลัพธ์ออกมาถูกต้องไหม

## สรุป

**จำง่ายๆ:**
- เขียนว่า: **hyperparameter**
- **ไม่ใช่:** hyperpameter, hyperparmeter, hyperparamter
- **มี r อยู่ 2 ตัว:** hype**r**-pa**r**ameter

---

**ขอให้จำได้และเขียนถูกต้องนะครับ/ค่ะ!** ✨
