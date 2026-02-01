# <img src="public/logo.svg" width="48" height="48" valign="middle"> 🇧🇭 Old Bahrain API | واجهة برمجة تطبيقات تراث البحرين

Old Bahrain API is an open-source project dedicated to digitally archiving the history of Bahrain. It provides a free, static API containing structured data about Bahraini villages, historical currencies, and rare photographs.

Old Bahrain API هو مشروع مفتوح المصدر يهدف لتوثيق تاريخ البحرين رقمياً. يوفر المشروع واجهة برمجية (API) مجانية تحتوي على بيانات مهيكلة حول قرى البحرين، العملات التاريخية، وصور نادرة من الماضي.

---

## 🚀 How to Use | طريقة الاستخدام

Since this is a static API hosted on GitHub Pages, you can fetch data directly using `GET` requests.
بما أن الـ API مستضاف كملفات ثابتة، يمكنك جلب البيانات مباشرة باستخدام طلبات `GET`.

### 📍 Base URL | الرابط الأساسي
`https://7ras.github.io/old-bahrain-api`

### 🔗 Available Endpoints | الروابط المتاحة

| Data Type | Endpoint | Description | الوصف |
| :--- | :--- | :--- | :--- |
| **Villages** | `/api/villages.json` | List of villages, history, and location. | قائمة القرى، تاريخها، ومواقعها. |
| **Currencies** | `/api/currencies.json` | Old currencies used in Bahrain. | العملات القديمة المستخدمة في البحرين. |
| **Photos** | `/api/historical_photos.json` | Archive of general historical photos. | أرشيف الصور التاريخية العامة. |
| **Car Plates** | `/api/car_plates.json` | Historical car license plates. | لوحات السيارات التاريخية. |
| **Mosques** | `/api/mosques.json` | Historical mosques in Bahrain. | المساجد التاريخية. |
| **Matams** | `/api/matams.json` | Historical community houses (Matams). | المآتم التاريخية. |
| **family** | `/api/family.json` | Prominent Bahraini family and tribes. | العائلات والقبائل البحرينية البارزة. |

---

## 📦 Data Structure Example | نموذج هيكلة البيانات

### 🏘️ Villages (القرى)
```json
{
  "id": 1,
  "name_ar": "البلاد القديم",
  "name_en": "Bilad Al Qadeem",
  "category": "Historical Capital",
  "description_ar": "كانت عاصمة البحرين القديمة وتشتهر بمسجد الخميس...",
  "description_en": "It was the old capital of Bahrain, famous for Al Khamis Mosque...",
  "location": {
    "lat": 26.2056,
    "lng": 50.5539
  },
  "images": ["/public/villages/bilad-old.jpg"]
}
```

### 🪙 Currencies (العملات)
```json
{
  "id": 101,
  "name_ar": "روبية خليجية",
  "name_en": "Gulf Rupee",
  "year": 1959,
  "era": "Pre-Independence",
  "images": {
    "front": "/public/currencies/rupee_1_front.jpg",
    "back": "/public/currencies/rupee_1_back.jpg"
  }
}
```

### 🚗 Car Plates (لوحات السيارات)
```json
{
  "id": 1,
  "name_ar": "إصدار عام 1993",
  "name_en": "1993 Series",
  "era": "Modern Era (Classic Style)",
  "type": "Private",
  "colors": {
    "background": "White",
    "text": "Blue"
  }
}
```

### 🕌 Mosques (المساجد)
```json
{
  "id": 1,
  "name_ar": "مسجد الخميس",
  "name_en": "Khamis Mosque",
  "type": "Mosque",
  "location": {
    "lat": 26.2082,
    "lng": 50.5482
  }
}
```

### 🏟️ Matams (المآتم)
```json
{
  "id": 1,
  "name_ar": "مأتم العجم الكبير",
  "name_en": "Matam Al-Ajam Al-Kabeer",
  "type": "Matam",
  "location": {
    "lat": 26.2340,
    "lng": 50.5760
  }
}
```

### 👥 family  (العائلات والقبائل)
```json
 {
        "id": 17,
        "name_ar": "البحارنة",
        "name_en": "Baharna",
        "category": "Indigenous / Social Group",
        "notable_for": "Agriculture, Shipbuilding, Traditional Crafts"
    }
```

---

## 🤝 Contribution | المساهمة

We welcome contributions from the community! If you have historical photos, corrections, or new data about a village:
نرحب بمساهمات المجتمع! إذا كان لديك صور تاريخية، تصحيحات، أو معلومات إضافية عن قرية معينة:

1. **Fork** the repository.
2. **Add** your data to the relevant `.json` file in the `api/` folder.
3. **Upload** images to the `public/` folder.
4. **Submit** a Pull Request.

---

## 📜 License | الترخيص

This project is licensed under the **MIT License**.
Images are property of their respective owners and used for educational/archival purposes.

هذا المشروع مرخص تحت رخصة **MIT**.
الصور تعود ملكيتها لأصحابها وتستخدم هنا لأغراض تعليمية وتوثيقية.