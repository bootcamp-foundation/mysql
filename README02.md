#### **Task 1: "Mahsulotlar" Table (Magazin Database)**

1. **Database nomi:** `Magazin`
2. **Jadval yaratish:** `Mahsulotlar`
   - Ustunlar: `id` (INT), `name` (VARCHAR), `category` (VARCHAR), `price` (INT), `quantity` (INT).
3. **Ma’lumotlar qo‘shish:** 10 ta mahsulot.
4. **Shartlar:**
   1. **DISTINCT:** Har bir unikal `category` nomlarini chiqarib bering.
   2. **SUM:** Jami mahsulotlarning `price` yig‘indisini hisoblang.
   3. **COUNT:** Har bir kategoriyadagi mahsulotlar sonini hisoblang.
   4. **MAX va MIN:** Mahsulotlar orasidan eng qimmat va eng arzon `price` qiymatini toping.
   5. **ORDER BY:** `price` ustuni bo‘yicha mahsulotlarni kamayish tartibida saralang.

---

#### **Task 2: "Talabalar" Table (Maktab Database)**

1. **Database nomi:** `Maktab`
2. **Jadval yaratish:** `Talabalar`
   - Ustunlar: `id` (INT), `name` (VARCHAR), `grade` (VARCHAR), `age` (INT), `gender` (VARCHAR).
3. **Ma’lumotlar qo‘shish:** 10 ta talabalar ma’lumoti.
4. **Shartlar:**
   1. **DISTINCT:** Faqat `grade` ustunidagi unikal baholarni ko‘rsating.
   2. **COUNT:** Qiz va o‘g‘il bolalar sonini alohida hisoblang.
   3. **LENGTH:** Har bir talabaning `name` uzunligini aniqlang.
   4. **MAX va MIN:** Talabalar orasidan eng yosh va eng katta yoshdagi talabalarning yoshini toping.
   5. **ORDER BY:** Talabalar ro‘yxatini `age` bo‘yicha o‘sish tartibida saralang.

---

#### **Task 3: "Kitoblar" Table (Kutubxona Database)**

1. **Database nomi:** `Kutubxona`
2. **Jadval yaratish:** `Kitoblar`
   - Ustunlar: `id` (INT), `title` (VARCHAR), `author` (VARCHAR), `genre` (VARCHAR), `year` (INT).
3. **Ma’lumotlar qo‘shish:** 10 ta kitob ma’lumoti.
4. **Shartlar:**
   1. **DISTINCT:** Faqat unikal `genre` nomlarini chiqaring.
   2. **SUM:** Agar kerak bo‘lsa, kitoblarning `year` qiymatlari yig‘indisini toping.
   3. **COUNT:** Har bir `genre` bo‘yicha kitoblar sonini hisoblang.
   4. **MAX va MIN:** Eng eski va eng yangi kitoblarning `year` qiymatini toping.
   5. **ORDER BY:** Kitoblar ro‘yxatini `year` ustuni bo‘yicha kamayish tartibida saralang.

---
