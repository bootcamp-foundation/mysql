### **Uyga vazifa: MySQL amaliyoti**  

1. **Ma'lumotlar bazasi yaratish:**  
   - `company_db` nomli ma'lumotlar bazasini yarating.  

2. **3 ta jadval yaratish (relationshipsiz):**  
   - `employees` – xodimlar haqida ma'lumot saqlaydi.  
   - `departments` – bo‘limlar haqida ma'lumot saqlaydi.  
   - `products` – mahsulotlar haqida ma'lumot saqlaydi.  

#### **Jadvallar tuzilmasi:**  

- **employees**  
  - `id` – Integer, Primary Key, Auto Increment  
  - `full_name` – Varchar(100)  
  - `age` – Integer  
  - `salary` – Decimal(10,2)  

- **departments**  
  - `id` – Integer, Primary Key, Auto Increment  
  - `name` – Varchar(100)  
  - `location` – Varchar(100)  

- **products**  
  - `id` – Integer, Primary Key, Auto Increment  
  - `name` – Varchar(100)  
  - `price` – Decimal(10,2)  
  - `stock` – Integer  

3. **Har bir jadvalga kamida 10 ta yozuv qo‘shing.**  

4. **3 xil `WHERE` sharti bilan ma'lumotlarni chiqarish:**  
   - Maoshi **2500 dan katta** bo‘lgan xodimlarni chiqarish.  
   - **Toshkent** shahridagi bo‘limlarni chiqarish.  
   - Narxi **500 dan kam** bo‘lgan mahsulotlarni chiqarish.
