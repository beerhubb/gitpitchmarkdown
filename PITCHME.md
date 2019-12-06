# Markdown

---

## Markdown คือ

Mark down คือ

ภาษาคอมพิวเตอร์ ที่มนุษย์สามารถอ่านเข้าใจได้ง่าย
และด้วยความง่ายนี้มันก็สามารถแปลงกลับมาเป็นภาษาอื่นๆ
ได้ง่ายด้วยกันเช่น HTML, XHTML และด้วยความง่ายเช่นนี้จึงมีเจ้าอื่นนำไป Customize ให้เป็นของตัวเอง
เช่น github ก็อาจจะเพิ่มพวก feature
เข้าไปเช่น task list, mention และอื่น ๆ

---

@snap[north ]

#### HTML vs Markdown

@snapend

@snap[west span-50]

    <h1> Hello </h1>                     # Hello
    <h2> Hi </h2>                        ## Hi
    <ul>
    <li>Apple</li>                      * Apple
    <li>Banana</li>                     * Banana
    <li>Orange</li>                     * Orange
    </ul>

@snapend

@snap[east span-50]

![](https://miro.medium.com/max/1150/1*L-PYnMRbnKpIFYVdgbQUJQ.png)
@snapend

---

## เริ่มเขียนMarkdown

---

@snap[north]

#### การเขียนหัวเรื่อง

@snapend

@snap[west span-50]

        # หัวเรื่อง 1
        ## หัวเรื่อง 2
        ### หัวเรื่อง 3
        #### หัวเรื่อง 4
        ##### หัวเรื่อง 5
        ###### หัวเรื่อง 6

@snapend

@snap[south-east span-50]
![](https://sv1.picz.in.th/images/2019/12/05/iZFdHl.jpg)
@snapend

---

@snap[north span-50]

#### รูปแบบอักษรประกอบไปด้วย

@snapend

@snap[west span-50]

#### Syntax

```
        หัวเรื่องแรก  หัวเรื่องที่สอง
        --------  -----------
         ตัวเอียง     _ตัวเอียง_
         ตัวหน้า     **ตัวหน้า**
         ขีดฆ่า      ~~ขีดฆ่า~~
```

@snapend

@snap[east span-50]

แสดงผล
_สวัสดี_
**สวัสดี**
~~สวัสดี~~
@snapend

---

@snap[north span-50]
ลิสต์แบบเรียงลำดับ (Ordered List)
@snapend

@snap[west span-50]

#### Syntax

1. สวัสดี
2. ฉัน
3. ชื่อ
4. อะไร
   @snapend

@snap[east span-50]

![](https://sv1.picz.in.th/images/2019/12/05/iZFSgv.jpg)
@snapend

---

@snap[north span-50]
ลิสต์แบบไม่เรียงลำดับ (Unordered List)
@snapend

@snap[west- span-50]

#### Syntax

        - สวัสดี
        - สวัสดี
        - สวัสดี

        * สวัสดี
        * สวัสดี
        * สวัสดี

@snapend

@snap[south-east span-50]
![](https://sv1.picz.in.th/images/2019/12/05/iZFYCE.jpg)
@snapend

---

@snap[north span-50]

list ซ้อน list (Nested List)
@snapend

@snap[west span-50]

1. สวัสดี
   - ฉันชื่อ
   - อะไร
1. ไม่รู้
1. สินะ
   @snapend

@snap[east span-50]

        ![] (https://sv1.picz.in.th/images/2019/12/05/iZyXqq.jpg)

@snapend

---

## ใส่รูปภาพใน Markdown

โค้ต

    ![Google ](https://sv1.picz.in.th/images/2019/12/05/iZyaHz.jpg)

เเสดงผล

## ![Google ](https://www.google.co.th/images/branding/googlelogo/2x/googlelogo_color_272x92dp.png)

---

@snap[north span-50]

#### การใส่ตาราง (Tables)

@snapend

@snap[west span-70]

```
    | หัวเรื่องแรก | หัวเรื่องที่สอง | หัวเรื่องสาม |
    | :-------  | :-------: | --------: |
    | ซ็าย       |  กึ่งกลาง   | ขวา       |
    | ซ็าย       |  กึ่งกลาง   | ขวา       |
```
@snapend

@snap[east span-60]

| หัวเรื่องแรก | หัวเรื่องที่สอง | หัวเรื่องสาม |
| :-------- | :--------: | ---------: |
| ซ็าย | กึ่งกลาง | ขวา |
| ซ็าย | กึ่งกลาง | ขวา |
@snapend

---


