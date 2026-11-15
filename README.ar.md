<div align="center" dir="rtl">

# ⚖️ منظومة ميزان الذكية (Mizan Commerce AI)

### *نظام تشغيل متكامل متعدد الوكلاء لإدارة التجارة الإلكترونية، التدقيق المالي، وأتمتة خدمة العملاء*

[![FastAPI](https://img.shields.io/badge/FastAPI-0.124-38bdf8?style=for-the-badge&logo=fastapi&logoColor=white)](https://github.com/Mo-Alwosabi/Mizan-Commerce-AI)
[![React](https://img.shields.io/badge/React-19.2-818cf8?style=for-the-badge&logo=react&logoColor=white)](https://github.com/Mo-Alwosabi/Mizan-Commerce-AI)
[![Python](https://img.shields.io/badge/Python-3.11+-38bdf8?style=for-the-badge&logo=python&logoColor=white)](https://github.com/Mo-Alwosabi/Mizan-Commerce-AI)
[![Local GPU](https://img.shields.io/badge/Local_GPU-LM_Studio_%2F_Ollama-10b981?style=for-the-badge)](https://github.com/Mo-Alwosabi/Mizan-Commerce-AI)

**[ 🇬🇧 Read in English ](README.md)**

*تطوير وهندسة: **[محمد الوصابي (Mohammed Alwosabi)](https://github.com/Mo-Alwosabi)** — مهندس ذكاء اصطناعي وتعلم آلي*

</div>

---

<div dir="rtl">

## 🎯 نظرة عامة
**منظومة ميزان الذكية (`Mizan Commerce AI`)** هي منصة تشغيل ذكية متعددة الوكلاء (`Multi-Agent AI Operating System`) صُممت لخدمة المتاجر الإلكترونية ومراكز التوريد وفرق التدقيق المالي. تجمع المنظومة بين **وكيل مشرف ذكي (Supervisor Agent)** يوجّه الطلبات بدقة، ودعم كامل للتشغيل المحلي على كروت الشاشة (`LM Studio` و `Ollama`) دون تكاليف سحابية، إلى جانب استخراج فواتير الموردين والتحقق التلقائي من الضرائب والحسابات.

## 🌟 أبرز المزايا الهندسية
* **توجيه ذكي متعدد الوكلاء:** وكيل مشرف ينسّق بين وكيل خدمة العملاء، تتبع الشحنات، المرتجعات، استخراج المستندات، والامتثال المالي.
* **تشغيل محلي سيادي 100%:** تكامل مباشر مع `LM Studio` و `Ollama` لتشغيل النماذج محلياً على بطاقات NVIDIA RTX مع دعم التبديل الفوري بين 9 مزودات سحابية ومحلية.
* **تدقيق الفواتير آلياً:** قراءة ملفات PDF الخاصة بالموردين، استخراج البنود، والتحقق الحسابي والضريبي (`validate_vat.py`).
* **هوية بصرية احترافية:** واجهة عربية بالكامل (`RTL`) بألوان **Cyber-Cyan & Deep Indigo** وخط **ثمانية (Thmanyah)** الرسمي.

## 🚀 التشغيل السريع
```bash
git clone https://github.com/Mo-Alwosabi/Mizan-Commerce-AI.git
cd Mizan-Commerce-AI
pip install -r requirements.txt
uvicorn api.main:app --reload --port 8000
```
وفي نافذة أخرى للواجهة الأمامية:
```bash
cd web && npm install && npm run dev
```

## 👨‍💻 المطوّر والتواصل
* **الاسم:** محمد الوصابي (`Mohammed Alwosabi`)
* **GitHub:** [@Mo-Alwosabi](https://github.com/Mo-Alwosabi)
* **LinkedIn:** [Mohammed Alwosabi](https://www.linkedin.com/in/mohammed-al-wosabi-609a693a1)
* **البريد الإلكتروني:** `ai.mohammed.alwosabi@gmail.com`

</div>
