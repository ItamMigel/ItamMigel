# 💼 Калинин Алексей  
**Deep Learning Engineer**  
Москва  
📞 [+7 (903) 012-16-17](tel:+79030121617)  
📧 [kalinin.aa2005018@gmail.com](mailto:kalinin.aa2005018@gmail.com)  
📨 [Telegram @itammigel](https://t.me/itammigel)  
💻 [GitHub: ItamMigel](https://github.com/ItamMigel)<br>
📍 [Актуальное резюме](https://drive.google.com/file/d/1Z6ujM3-8pTzoQout7DDSJDC1pVBN89hi/view?usp=share_link) 

---

## 🧠 Обо мне  
DL инженер / Инженер машинного обучения с более чем 2-летним опытом. Активно участвую в хакатонах и соревнованиях по машинному обучению.

---

## 🎓 Образование

- **НИТУ МИСИС, Институт компьютерных наук, ИСАД** — *Москва, 2023–2027*
- **Stepik — Основы математической статистики** (*2023*)
- **Школа глубокого обучения МФТИ** — курс по DL, CV, GAN (*2023*)
- **ШАД Яндекса** — курс по NLP (*2023*)

---

## 🛠️ Навыки

**Языки программирования:**  
Python, C++

**Области:**  
Classical ML, CV, NLP

**Технические навыки:**  
Pandas, NumPy, Matplotlib, Scikit-learn, CatBoost, XGBoost, transformers, sentence-transformers, PEFT, Spacy, nltk, gensim, langchain, PyTorch, Vosk, OpenCV, FastAPI, LLM, PostgreSQL

**Инструменты:**  
Git, Windows, WSL, pytest, Docker, Weights & Biases (W&B)

---

## 👨‍💻 Опыт — *1 год 11 месяцев*

### Газпром — *Data Science*  
📅 Май 2023 — Октябрь 2024

- Анализ временных рядов давления скважин для поиска аномалий (автоэнкодеры) → снижение ложных срабатываний на 30%
- Классификация графиков работы газовых станций с помощью EfficientNetB0 → recall 0.87
- Анализ аудиозаписей работы механизмов (мелспектрограммы + CNN) → accuracy 0.64
- Детекция нарушений на станциях (YOLO) — отсутствие жилета, неправильное положение человека
- Регрессия стоимости бурения — XGBoost, LightGBM, CatBoost, RandomForest

### Сбер — *DL Engineer*  
📅 Октябрь 2024 — Апрель 2025

- Повышение качества сегментации и детекции документов (ОСАГО, паспорта) с помощью YOLO
- Классификация диагнозов в страховках: Tf-idf, FastText, Bert, ruRoPEBert → +20% accuracy  
  + генерация синтетических датасетов
- Полный цикл разработки сервиса обработки авиа-документов: бизнес, фильтрация, обучение, FastAPI
- Классификация сканов с использованием `beitv2_large_patch16_224`, улучшение F1 с 0.51 до 0.75
- Исследование подходов VLM для OCR → деплой через FastAPI и `vllm`

---

## 🏆 Достижения

### 🥇 Siam ML Hack — *Classic ML*  
📅 Март 2025  
🔗 [Решение (GitHub)](https://github.com/ItamMigel/siam)

Разработал алгоритм выделения информативных участков временных рядов. Использовал ручную разметку, генерацию фичей, бустинги. Получил F1 = 0.69. Решение — интерпретируемое и расширяемое.

---

### 🥇 MTS True Tech — *«Доступные интернет-конференции» (NLP, TTS, STT)*  
📅 Февраль 2025

Создание платформы для видеозвонков с поддержкой перевода, озвучки и суммаризации:
- STT: Whisper  
- TTS: Coqui, Kokoro  
- Суммаризация: YandexGPT  
- Перевод: ALMA 7B

Платформа поддерживает 19 языков и объединяет функции в одном продукте.

---

### 🥉 Tatneft Techstorm — *Бот-ассистент*  
📅 Август 2024  
🔗 [Решение (GitHub)](https://github.com/ItamMigel/Techstorm)  
📜 [Диплом](https://drive.google.com/drive/folders/1xxhzS6VyzdYxGGcrLmCL5sltYOrwnlzp?usp=drive_link)  
📄 [Статья](https://drive.google.com/drive/folders/1Z-UJrYjXvrZFUVgI_XuBNqtgm13AghBI?usp=drive_link)

Создан RAG-бот для Tatneft:
- Поиск по интернету и внутренним базам
- Голосовой ввод через Vosk
- Интеграция Serper API (Google)

---

### 🥉 Neftecode — *Предсказание свойств нефти (Classical ML)*  
📅 Апрель 2024  
🔗 [Решение (GitHub)](https://github.com/ItamMigel/NEUROTECH-SPBPU-MISIS)  
📜 [Диплом](https://drive.google.com/drive/u/0/folders/11e6K28_Ly7av4iIpfQoP-Zsq7_o_frY4)

Задача: предсказание вязкости нефти по хим. структуре (SMILES).  
Методы: Feature Engineering, BoW, RNN, GNN, CatBoost  
Результат: MAE ~15,000 → 3 место

---

### 🥈 Talent-Match — *Сопоставление резюме и вакансий (NLP)*  
📅 Февраль 2024  
🔗 [Решение (GitHub)](https://github.com/ItamMigel/Talent-Match)  
📜 [Диплом](https://drive.google.com/drive/u/0/folders/12eRJFZKD6pw9_bN9ftloLf6bPLTzj6sf)

Разработка модели сопоставления резюме и вакансий:
- Источник данных: HeadHunter
- Модель: distil-roBERTa → эмбеддинги
- Архитектура: сиамская нейросеть  
Результат: Recall = 0.8
