# Shop
#### Hech qanday argument berilmasa barcha do'konlar ro'yhatini qaytaradi
#### Bosh sahifa uchun **user-id** beriladi
#### Aynan bir do'kon ma'lumotlarini olish uchun **id** beriladi

```
https://spiska.pythonanywhere.com/api/shop/
```
---

## Product
#### Hech qanday argument berilmasa barcha mahsulotlar ro'yhatini qaytaradi
#### **region** berilsa faqat viloyat bo'yicha
#### **region** va **district** berilsa viloyat va tuman bo'yicha saralaydi
```
https://spiska.pythonanywhere.com/api/product/
```
---

## User
#### Hech qanday argument berilmasa barcha foydalanuvchilar ro'yhatini qaytaradi
#### Raqamni tekshirish uchun **phone** beriladi 
#### Aynan bir foydalanuvchilar ma'lumotlarini olish uchun **id** beriladi
#### Qidirilayotgan malumot **q** argumenti orqali beriladi
```
https://spiska.pythonanywhere.com/api/user/
```
---

## Promocode
#### Do'konning **Promokod** lar ro'yhatini olish uchun **shop-id** beriladi
