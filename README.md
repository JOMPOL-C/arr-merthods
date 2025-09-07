# 👨🏽‍💻 JavaScript Array Methods – Employees Example

โปรเจกต์ตัวอย่างการใช้งาน **Array Methods** ของ JavaScript  
ใช้ dataset `employees` (พนักงานในบริษัท) แล้วทำโจทย์ 10 ข้อ

ตัวอย่าง Array :
```js
const employees = [
  {
    id: 1,
    name: "ก้องภพ",
    department: "IT",
    position: "Developer",
    salary: 65000,
    startDate: "2021-04-15",
    isActive: true,
  },
  {
    id: 2,
    name: "วิมล",
    department: "Marketing",
    position: "Marketing Manager",
    salary: 92000,
    startDate: "2019-08-01",
    isActive: true,
  },
  {
    id: 3,
    name: "สมศักดิ์",
    department: "IT",
    position: "Senior Developer",
    salary: 88000,
    startDate: "2018-02-20",
    isActive: false,
  },
  {
    id: 4,
    name: "จินตนา",
    department: "Sales",
    position: "Sales Rep",
    salary: 58000,
    startDate: "2022-11-10",
    isActive: true,
  },
  {
    id: 5,
    name: "อมร",
    department: "IT",
    position: "Developer",
    salary: 68000,
    startDate: "2023-07-01",
    isActive: true,
  },
  {
    id: 6,
    name: "สุดา",
    department: "Sales",
    position: "Sales Manager",
    salary: 105000,
    startDate: "2017-05-30",
    isActive: true,
  },
];
```
---

## 📂 แบบฝึกหัดที่ทำ

1. **สร้าง Array ใหม่ที่มีเฉพาะข้อมูลของพนักงานที่ ยังทำงานอยู่ทั้งหมด()**
2. **สร้าง Array ใหม่ที่เก็บเฉพาะ ชื่อ ของพนักงานทุกคน**
3. **หาข้อมูลของพนักงานที่มี id เท่ากับ 4**
4. **ตรวจสอบว่ามีพนักงานคนใดคนหนึ่งที่ทำงานในแผนก 'Marketing' หรือไม่ (ตอบเป็น true หรือ false)** 
5. **หารายชื่อของพนักงานทุกคนที่อยู่ในแผนก 'IT'**
6. **คำนวณ เงินเดือนรวมทั้งหมด ที่บริษัทต้องจ่ายให้พนักงาน ทุกคน ในแต่ละเดือน**
7. **หาข้อมูลของพนักงานที่ เงินเดือนสูงสุด ในบริษัท (แค่คนเดียว)**
8. **หารายชื่อของพนักงานที่เริ่มทำงาน หลังปี 2020 และ ยังทำงานอยู่ จากนั้นจัดเรียงชื่อตามลำดับตัวอักษร**
9. **คำนวณ เงินเดือนเฉลี่ย ของพนักงานในแผนก 'IT' ที่ ยังทำงานอยู่**
10. **สร้าง Array ใหม่ของพนักงานที่ยังทำงานอยู่ โดยปรับเปลี่ยนรูปแบบข้อมูลเป็น**
    ```js
    { fullName: '...', details: 'ตำแหน่ง - แผนก' }
    ```
