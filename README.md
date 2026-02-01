# <img src="public/logo.svg" width="48" height="48" valign="middle"> 🇧🇭 Bahrain API | واجهة برمجة تطبيقات البحرين

**Bahrain API** is a comprehensive, open-source digital database for the Kingdom of Bahrain. It provides structured data (JSON) covering various aspects of life in Bahrain, ranging from its rich historical heritage to its modern-day social and geographical fabric.

**Bahrain API** هو مشروع مفتوح المصدر يهدف لتوفير قاعدة بيانات رقمية شاملة لمملكة البحرين. يوفر المشروع بيانات مهيكلة بصيغة (JSON) تغطي مختلف جوانب الحياة في البحرين، من التراث التاريخي العريق إلى الواقع الجغرافي والاجتماعي المعاصر.

---

## 🚀 Purpose | الهدف من المشروع

This API is designed for developers, researchers, and creators who want to build applications or conduct studies related to Bahrain. It serves as a central hub for:
هذا المشروع مصمم للمبرمجين، الباحثين، والمبدعين الراغبين في بناء تطبيقات أو إجراء دراسات حول البحرين. يعمل المشروع كمركز لكل من:

*   **Cultural Heritage:** Archiving history, currencies, and rare photos.
*   **Geographical Data:** Detailed information about Bahraini villages and cities.
*   **Social Fabric:** Information about prominent families and tribal history.
*   **Civic History:** Documenting car license plates, mosques, and community centers.

---

## 🔗 Available Endpoints | الروابط المتاحة

### 📍 History & Heritage (التاريخ والتراث)
| Endpoint | Description | الوصف |
| :--- | :--- | :--- |
| `/api/currencies.json` | Historical currencies. | العملات التاريخية والقديمة. |
| `/api/historical_photos.json` | Rare archival photos. | أرشيف الصور التاريخية النادرة. |
| `/api/car_plates.json` | Antique and historical car plates. | لوحات السيارات التاريخية والقديمة. |

### 🏘️ Geography & Society (الجغرافيا والمجتمع)
| Endpoint | Description | الوصف |
| :--- | :--- | :--- |
| `/api/villages.json` | List of Bahraini villages & cities. | قائمة بقرى ومدن البحرين. |
| `/api/family.json` | 100+ Bahraini families & tribes. | أكثر من 100 عائلة وقبيلة بحرينية. |
| `/api/mosques.json` | Historical and prominent mosques. | المساجد التاريخية والبارزة. |
| `/api/matams.json` | Historical community houses. | المآتم التاريخية. |
| `/api/figures.json` | public figures. | الشخصيات العامة. |

---

## 🛠️ How to Use | طريقة الاستخدام

Base URL: `https://7ras.github.io/bahrain-api`

You can fetch any endpoint using a simple `GET` request:
يمكنك جلب البيانات باستخدام طلب `GET` بسيط:

```javascript
fetch('https://7ras.github.io/bahrain-api/api/family.json')
  .then(response => response.json())
  .then(data => console.log(data));
```

---

## 🤝 Contribution | المساهمة

We welcome contributions! Whether it's correcting data, adding new families, or providing high-resolution historical photos. Please refer to our [Data Templates](DATA_TEMPLATES.md) for more information on how to format your contributions.

نرحب بمساهماتكم! سواء بتصحيح البيانات، إضافة عائلات جديدة، أو توفير صور تاريخية عالية الجودة. يرجى مراجعة [نماذج البيانات](DATA_TEMPLATES.md) لمعرفة كيفية هيكلة مساهماتك.

1. **Fork** the repository.
2. **Add/Edit** JSON files in the `api/` folder.
3. **Submit** a Pull Request.

---

## 📜 License | الترخيص

Licensed under **MIT License**.
Images are property of their respective owners and used for archival/educational purposes.