# AI-Generative-Product-Hackathon
# **MAAG Generative Product Hackathon 2023**

Проект создан в рамках финала **AI Generative Product Hackathon 2023** для разработки уникальных дизайнов одежды бренда **MAAG** на основе генеративных алгоритмов. Включает руководство командой, дообучение модели **Stable Diffusion** и создание дизайнов для коллекций одежды.

## **Описание проекта**

Проект использует возможности **Stable Diffusion** для генерации уникальных дизайнов в стиле бренда MAAG. Модель обучена с использованием **Dreambooth** и доработана для генерации тематических изображений, таких как логотипы и принты, для коллекций одежды.

**Ключевые компоненты проекта:**
- Тонкая настройка модели для специфических запросов бренда.
- Создание концепций для генерации уникальных визуальных образов.
- Запуск веб-интерфейса для генерации и визуализации изображений.
---

### **Требования** <a name="требования"></a>

Для работы проекта требуются следующие файлы и зависимости.

#### **Файлы и скрипты**
1. **train_dreambooth.py** - для тренировки модели Dreambooth:
   ```bash
   wget -q https://github.com/ShivamShrirao/diffusers/raw/main/examples/dreambooth/train_dreambooth.py

2. **convert_diffusers_to_original_stable_diffusion.py** - для конвертации весов:
   ```bash
   wget -q https://github.com/ShivamShrirao/diffusers/raw/main/scripts/convert_diffusers_to_original_stable_diffusion.py
   
3. **concepts_list.json** - файл, содержащий список концепций для обучения. Пример:
   ```bash
   [
  {
    "instance_prompt": "a print of a lion",
    "class_prompt": "wild animal print",
    "instance_data_dir": "/path/to/your/data"
  }
]


