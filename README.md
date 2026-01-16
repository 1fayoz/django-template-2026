# DRF Shablon

## Loyiha Tuzilishi

```plaintext
drf_shablon/
├── apps/                                   # Alohida ilovalar joylashgan
├── core/                                   # Asosiy konfiguratsiya va yordamchi funksiyalar
├── docker-compse.yml, Dockerfile           # Ishlab chiqarish va deployment uchun sozlamalar
├── .env/                                   # Turli muhitlarga mos sozlamalar
├── requirements/                           # Bog‘liqliklar
├── manage.py                               # Django boshqaruv fayli
└── README.md                               # Loyihaning o'zi haqida hujjatlar
```

### 1. O‘rnatish Reponi klonlash:


```plaintext
git clone <repository-url>
```

### 2.  **'.env.example'** fayllardan nusxa olib **'.env'** fayllarni to'ldirib chiqish

### 3.  Virtual muhit o'rnatish

pycharm da bo'lsa
```commandline
O'ng burchak pastda <new interpreter> >> Add New Interpreter >>  Add Local Interpreter >> Base Python degan joydam 3.12 chi versiya tanlanadi
```
agar to'g'ri bolsa **"(venv)"** terminalda shunaqa belgi  chiqadi ikki hilatda ham 

Har qanday Linux yoki Mac terminalda  bo'lsa
```commandline
- python3 -m venv venv
- source venv/bin/activate
```

### 4.  Loyhaga kerakli package larni o'rnatsh kerakk
```commandline
pip install -r requirements/develop.txt
```


### 5.  Database yaratish .env da qo'yilgan nom va password bilan
 
```commandline
- psql postgres
- create user <user_name> with password '<user_password>';
- create database <db_name> with owner <user_name>
```



