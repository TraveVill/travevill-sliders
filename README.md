<h1>
  <img src="https://github.com/user-attachments/assets/996b9415-f58c-492d-8f60-119a3abb96f7" width="28" style="vertical-align: middle; margin-right: 8px;">
  TraveVill | Официальный GitHub репозиторий
</h1>

Добро пожаловать в репозиторий проекта **TraveVill**! Этот репозиторий был создан для обеспечения функционала слайдеров на странице [сохранений сезонов TraveVill](https://teletype.in/@travevill/saves), которого нам так не хватало в инструментарии ресурса.

> **Создатель репозитория:** `blackjokes` — член администрации TraveVill.

---

## 🧐 Принцип работы

### Шаг 1:
Для начала Вам необходимо получить ссылку на созданную Вами (или другим пользователем) html-страницу. 
Реализованный здесь способ использует GitHub-pages, так что ссылка имеет вид:
`https://travevill.github.io/travevill-sliders/*`
Где * — либо нужная вам html-страница, либо дальнейший путь к ней ведущий.<br>
> **Пример здесь:** https://travevill.github.io/travevill-sliders/travevill-1/slider.html

### Шаг 2:
Функционал слайдеров для teletype.in был реализован мной с помощью iframe-вставки следующего кода на конечную страницу:<br>
```
<iframe
src="https://travevill.github.io/travevill-sliders/travevill-1/slider.html"
  width="100%"
  height=480"
  style="border:none;"
></iframe>
```

Далее, на целевой странице остаётся выбрать соотношение сторон 16:9 для вставленной на предыдущем этапе страницы, и Вы получаете следующее:

<img width="948" height="627" alt="image" src="https://github.com/user-attachments/assets/ba3a2245-b9b7-4e27-8393-866e6f582ce7" />

> **Пример здесь:** https://teletype.in/@travevill/saves
---

## 📂 Структура этого репозитория
Для поддержания идеального порядка файлы распределены по следующим директориям:
*   `travevill-1/` — Скриншоты и слайдер «Первого Сезона».
*   `travevill-2/` — Скриншоты и слайдер TraveVill 2.
*   `travevill-3/` — Скриншоты и слайдер TraveVill 3.
*   `travevill-4/` — Скриншоты и слайдер TraveVill 4.
*   `travevill-ofs-1/` — Скриншоты и слайдер «МежСезонья».
*   `travevill-ofs-2/` — Скриншоты и слайдер «Межсезонье: "Замёрзший мир"».
*   `travevill-ofs-3/` — Скриншоты и слайдер «Межсезонье: Моды».
