# 📄 JSON Data Templates | نماذج هيكلة البيانات

If you would like to contribute new data to the **Bahrain API**, please use the following templates to ensure consistency across the project.

إذا كنت ترغب في المساهمة ببيانات جديدة، يرجى استخدام النماذج التالية لضمان اتساق البيانات في المشروع.

---

### 🏘️ Village Template | نموذج القرى
**File:** `api/villages.json`
```json
{
  "id": 0,
  "name_ar": "اسم القرية",
  "name_en": "Village Name",
  "category": "Village / City / Historical Site",
  "description_ar": "وصف مفصل عن القرية وتاريخها...",
  "description_en": "Detailed description of the village and its history...",
  "location": {
    "lat": 0.0,
    "lng": 0.0
  },
  "images": [
    "/public/villages/image_name.jpg"
  ]
}
```

---

### 👥 Family Template | نموذج العائلات والقبائل
**File:** `api/family.json`
```json
{
  "id": 0,
  "name_ar": "اسم العائلة/القبيلة",
  "name_en": "Family/Tribe Name",
  "category": "Merchant / Tribal / Scholarship / Professional",
  "description_ar": "نبذة تاريخية عن العائلة ودورها في المجتمع...",
  "description_en": "Brief history of the family and their role in society...",
  "notable_for": "Key contributions or notable properties"
}
```

---

### 🕌 Mosque & Matam Template | نموذج المساجد والمآتم
**Files:** `api/mosques.json` | `api/matams.json`
```json
{
  "id": 0,
  "name_ar": "الاسم",
  "name_en": "Name",
  "type": "Mosque / Matam",
  "category": "Historical / Modern",
  "location": {
    "lat": 0.0,
    "lng": 0.0
  },
  "description_ar": "نبذة عن الموقع وتاريخ تأسيسه...",
  "description_en": "About the location and its founding history...",
  "history": "Founding year and key events",
  "images": [
    "/public/mosques/image.jpg"
  ]
}
```

---

### 🚗 Car Plate Template | نموذج لوحات السيارات
**File:** `api/car_plates.json`
```json
{
  "id": 0,
  "name_ar": "اسم الإصدار أو الفترة",
  "name_en": "Series or Period Name",
  "era": "e.g., British Protectorate / Independence / Modern",
  "type": "Private / Commercial / Diplomatic",
  "colors": {
    "background": "Color",
    "text": "Color"
  },
  "description_ar": "وصف اللوحة ومميزاتها...",
  "description_en": "Description of the plate and its features...",
  "sample_image": "/public/plates/sample.jpg"
}
```

---

### 🪙 Currency Template | نموذج العملات
**File:** `api/currencies.json`
```json
{
  "id": 0,
  "name_ar": "اسم العملة",
  "name_en": "Currency Name",
  "year": 1965,
  "era": "Historical Era",
  "description_ar": "وصف العملة ومميزاتها التاريخية...",
  "description_en": "Description of the currency and historical features...",
  "images": {
    "front": "/public/currencies/front.jpg",
    "back": "/public/currencies/back.jpg"
  }
}
```

---

### 📸 Historical Photo Template | نموذج الصور التاريخية
**File:** `api/historical_photos.json`
```json
{
  "id": 0,
  "title_ar": "عنوان الصورة",
  "title_en": "Photo Title",
  "description_ar": "وصف للمكان أو الحدث في الصورة...",
  "description_en": "Description of the place or event in the photo...",
  "year": "e.g., 1950s",
  "url": "/public/history/photo.jpg"
}
```
