\documentclass[10pt]{article}
\usepackage[utf8]{inputenc}
\usepackage[T2A]{fontenc} % Поддержка кириллицы
\usepackage[russian]{babel} % Русский язык
\usepackage[a4paper, left=0.5in, right=0.5in, top=1in, bottom=1in]{geometry} % Устанавливаем отступы по бокам в 0.5 дюйма
\usepackage{setspace} 
\usepackage{hyperref} % Добавлен для поддержки ссылок
\usepackage{tabularx} % Подключение пакета для работы с таблицами

\begin{document}
\begin{center}
\textbf{\LARGE КАЛИНИН АЛЕКСЕЙ}\\
\vspace{0.5cm} % Уменьшенный вертикальный промежуток
{\large Deep Learning Engineer}\\ 
Москва
\end{center}

\vspace{-0.5em} % Уменьшаем пространство перед заголовком
\section*{\normalsize\textbf{ОБО МНЕ}} % Нормальный размер и жирный шрифт
\vspace{0em} % Уменьшаем пространство после заголовка
\hrule % Горизонтальная черта
\vspace{0.5em} % Вертикальное пространство после линии

\hspace*{2em}\noindent\textbf{DL инженер/Инженер машинного обучения} с опытом работы более 2 лет. Участвую в хакатонах и мл \hspace*{2em}соревнованиях.\newline \hspace*{2em} 
\hspace*{-0.5em}\noindent\textbf{Телефон}: \href{tel:+79030121617}{+7 (903) 012-16-17}

\hspace*{0.5em}\noindent\textbf{E-Mail}: \href{mailto:kalinin.aa2005018@gmail.com}{kalinin.aa2005018@gmail.com}

\hspace*{0.5em}\noindent\textbf{Telegram}:\href{https://t.me/itammigel}{@itammigel}

\hspace*{0.5em}\noindent\textbf{GitHub}: \href{https://github.com/ItamMigel}{ItamMigel}

\vspace{0em} % Уменьшаем пространство перед заголовком
\section*{\normalsize\textbf{ОБРАЗОВАНИЕ}} % Нормальный размер и жирный шрифт
\vspace{0em} % Уменьшаем пространство после заголовка
\hrule % Горизонтальная черта
\vspace{0.5em} % Вертикальное пространство после линии

\hspace*{2em}\noindent\textbf{НИТУ МИСИС, Институт компьютерных наук, ИСАД} \hfill Москва, \textit{2023-2027}

\hspace*{0.5em}\noindent\textbf{Основы математической статистики - Stepik} \hfill \textit{2023}

\hspace*{0.5em}\noindent\textbf{Школа глубокого обучения от МФТИ - Курс по DL, CV, GAN} \hfill \textit{2023}

\hspace*{0.5em}\noindent\textbf{Школа анализа данных Яндекса - Курс по NLP} \hfill \textit{2023}


\vspace{0em} % Уменьшаем пространство перед заголовком
\section*{\normalsize\textbf{НАВЫКИ}} % Нормальный размер и жирный шрифт
\vspace{0em} % Уменьшаем пространство после заголовка
\hrule % Горизонтальная черта
\vspace{0.5em} % Вертикальное пространство после линии

\noindent
\begin{tabularx}{\textwidth}{l X}
\hspace*{1.5em}\textbf{Языки программирования} & Python, C++ \\
\hspace*{1.5em}\textbf{Области} & Classical ML, CV, NLP \\
\hspace*{1.5em}\textbf{Технические навыки} & Pandas, NumPy, Matplotlib, Scikit-learn, CatBoost, XGBoost, transformers, sentence-transformers, PEFT, spacy, nltk, gensim, langchain, PyTorch, Vosk, Scikit-learn, OpenCV, FastAPI, LLM, PostgreSQL \\
\hspace*{1.5em}\textbf{Инструменты} & Git, Windows, WSL, pytest, Docker, W\&B \\
\end{tabularx}

\vspace{0em} % Уменьшаем пространство перед заголовком
\section*{\normalsize\textbf{ОПЫТ - 1 год 11 месяцев}} % Нормальный размер и жирный шрифт
\vspace{0em} % Уменьшаем пространство после заголовка
\hrule % Горизонтальная черта
\vspace{0.5em} % Вертикальное пространство после линии

\vspace{1em}
\hspace*{1.9em}\noindent\textbf{Газпром} \hfill \textit{Май, 2023 - Октябрь, 2024} 

\hspace*{0.45em}\noindent\textbf \textit{Data Science}

\begin{itemize}
\item Занимался анализом временных рядов давления скважины для поиска аномалий с использованием автоэнкодеров, добился снижения ложных детекций на 30%
\item Классификация matplotlib графиков работы газовых станции с efficientnetb0, добился recall 0.87
\item Анализ аудиозаписей работы механизмов с целью определения их неисправностей при помощи разложения на мелспектрограммы и применения сверточных нейронных сетей. Добился accuracy равной 0.64
\item Детекция нарушений на станциях(человек ходит без определенного жилета, стоит в неположенном месте) с использованием YOLO
\item Работал над задачей регрессии стоимости бурения с использованием классических моделей(xgboost, lightgbm, catboost, RandomForest)
% next
\end{itemize}
\vspace{1em}

\vspace{1em}
\hspace*{0.5em}\noindent\textbf{Sber} \hfill \textit{Октябрь, 2024 - Апрель, 2025} 

\hspace*{0.45em}\noindent\textbf \textit{DL Engineer}

\begin{itemize}
\item Занимался улучшением качества текущих моделей сегментации и детекции для ОСАГО и паспортов клиентов, экспериментируя с разными стратегиями обучения YOLO и повысисв точность детекции и сегментации на сложных случаях
\item Занимался классификацией текста диагнозов в страховочных документах, эксперементируя с Tf-idf, FastText, Bert, ruRoPEBert, тем самым добившись повышения accuracy на 20\%. Также сделал скрипт создания синтетических датасетов для обучения текстового классификатора, 
\item Участвовал в полном этапе разработки сервиса обработки документов с авиаубытками: общение с бизнесом, фильтрация датасета, обучение модели классификации документов и модели детекции полей, обертка в FastAPI сервис.
\item Занимался классификацией сканов документов при помощи \texttt{beitv2\_large\_patch16\_224}, занимался фильтрацией разметки при помощи VLM и суммарно повысил F1 с 0.51 до 0.75
\item Занимался исследованием текущих подходов VLM для задачи OCR: чтение статей, тестирование моделей, развёртывание решения в виде \texttt{FastAPI} сервиса с использованием \texttt{vllm}
\end{itemize}


% next
\vspace{1em}

\vspace{0em} % Уменьшаем пространство перед заголовком
\section*{\normalsize\textbf{ДОСТИЖЕНИЯ}} % Нормальный размер и жирный шрифт
\vspace{0em} % Уменьшаем пространство после заголовка
\hrule % Горизонтальная черта
\vspace{0.5em} % Вертикальное пространство после линии

\vspace{1em}
\hspace*{1.9em}\noindent\textbf{Siam ML Hack», Classic ML} \hfill \textit{Март, 2025} 

\hspace*{0.5em}\noindent\textbf{1 место}, \textit{ML-engineer}
\hspace*{0.5em}\noindent\textbf{Решение}: \href{https://github.com/ItamMigel/siam}{репозиторий} 
\vspace{1em}

\hspace*{0.5em}\noindent  Я разработал алгоритм для выявления самых информативных участков временных рядов и точного определения их начала и конца с использованием ручной разметки данных, предварительной обработки, генерации числовых признаков и бустингов для поиска сложных зависимостей. В результате получил интерпретируемое и расширяемое решение с метрикой F1 = 0.69, способное находить практически любые паттерны в данных.

% next
\vspace{1em}
\hspace*{0.5em}\noindent\textbf{MTS True tech: «Доступные  интернет-конференции», NLP, TTS, STT} \hfill \textit{Февраль, 2025} 

\hspace*{0.5em}\noindent\textbf{1 место}, \textit{ML-engineer}
\vspace{1em}

\hspace*{0.5em}\noindent  Мы командой создали сервис для видеозвонков, который помогает людям с особенностями восприятия. Я интегрировал STT модель на Whisper, TTS модели на Coqui и Kokoro, суммаризацию через YandexGPT и перевод через ALMA 7B. В результате мы получили уникальную платформу, объединяющую машинный перевод (поддержка 19 языков), суммаризацию диалогов и озвучку речи на другие языки (например, для лекций) в одном продукте.

\vspace{1em}
\hspace*{0.5em}\noindent\textbf{Хакатон Tatneft Techstorm: Бот-ассистент для поиска информации} \hfill \textit{Август, 2024} 

\hspace*{0.5em}\noindent\textbf{3 место}, \textit{DS, ML-engineer}
\hspace*{0.5em}\noindent\textbf{Решение}: \href{https://github.com/ItamMigel/Techstorm}{репозиторий} \href{https://drive.google.com/drive/folders/1xxhzS6VyzdYxGGcrLmCL5sltYOrwnlzp?usp=drive_link}{диплом}
\vspace{1em}

Мы командой создавали бота-ассистента для Tatneft, который предназначен для интеграции данных из интернета и внутренних баз знаний. Я реализовал RAG Fusion для объединения информации из внешних и внутренних источников, внедрил модель Vosk для преобразования голоса в текст, обеспечивая возможность голосового ввода, и настроил интеграцию serper (API для Google) для извлечения актуальной информации из интернета.
По этому решению мы с командой опубликовали статью (\href{https://drive.google.com/drive/folders/1Z-UJrYjXvrZFUVgI_XuBNqtgm13AghBI?usp=drive_link}{\textbf{ссылка на статью}}) в журнале — "применение искусственного интеллекта в задачах поиска информации по внутренней базе знаний и в интернете".
% next
\vspace{1em}

\hspace*{0.5em}\noindent\textbf{Neftecode: предсказание свойств нефти, Classical ML} \hfill \textit{Апрель, 2024} 

\hspace*{0.5em}\noindent\textbf{3 место}, \textit{ML-engineer}
\hspace*{0.5em}\noindent\textbf{Решение}: \href{https://github.com/ItamMigel/NEUROTECH-SPBPU-MISIS}{репозиторий} \href{https://drive.google.com/drive/u/0/folders/11e6K28_Ly7av4iIpfQoP-Zsq7_o_frY4}{диплом}
\vspace{1em}

\hspace*{0.5em}\noindent Решал задачу прогнозирования вязкость нефти по свойствам компонентов и химической структуре(SMILES), используя feature engineering, BoW, RNN, GNN и CatBoost для обучения на всех признаках. В результате достиг MAE ~15,000, что обеспечило третье место в таблице лидеров.


% next
\vspace{1em}
\hspace*{0.5em}\noindent\textbf{Talent-Match: сравнение резюме и вакансий, NLP} \hfill \textit{Февраль, 2024} 

\hspace*{0.5em}\noindent\textbf{2 место}, \textit{ML-engineer}
\hspace*{0.5em}\noindent\textbf{Решение}: \href{https://github.com/ItamMigel/Talent-Match}{репозиторий} \href{https://drive.google.com/drive/u/0/folders/12eRJFZKD6pw9_bN9ftloLf6bPLTzj6sf}{диплом}
\vspace{1em}

\hspace*{0.5em}\noindent Я разрабатывал модель для сопоставления резюме с вакансиями, используя данные, спарсенные с HeadHunter, distil-roBERTa для получения эмбеддингов и сиамскую нейронную сеть с двумя ветвями. В результате достиг метрики Recall = 0,8.
\vspace{1em}




\vspace{1em}




\end{document}
