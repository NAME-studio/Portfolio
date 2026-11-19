# Portfolio — NAME studio

Личное портфолио: сайты для небольших бизнесов и два приложения на Electron.
Всё написано вручную — HTML, CSS, JavaScript, без конструкторов.

**[Открыть сайт →](https://name-studio.github.io/Portfolio/)**

---

## Что внутри

### Сайты

| Проект | О чём | Демо |
|---|---|---|
| **Тёплый Пар** | кофейня: журнальная вёрстка, меню, зал, адрес | [sites/coffee](sites/coffee/index.html) |
| **Барбершоп** | цех и брутальность: прайс, мастера, запись | [sites/barber](sites/barber/index.html) |
| **Репетитор** | мягкий интерфейс: предметы, отзывы, форма | [sites/tutor](sites/tutor/index.html) |

### Приложения

| Проект | Что делает | Код |
|---|---|---|
| **Kubik Launcher** | лаунчер Minecraft: сборки в один клик, моды с Modrinth и CurseForge, друзья, скины, Discord Rich Presence | [NAME-studio/kubik-launcher](https://github.com/NAME-studio/kubik-launcher) |
| **PixelForge** | редактор пиксель-арта: холст, палитра, слои, экспорт PNG | [NAME-studio/PixelForge](https://github.com/NAME-studio/PixelForge) |

---

## Технологии

![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=000)
![Electron](https://img.shields.io/badge/Electron-2B2E3A?style=flat-square&logo=electron&logoColor=9FEAF9)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222?style=flat-square&logo=githubpages&logoColor=white)

---

## Структура

```
index.html          главная страница портфолио (один файл, без сборки)
favicon.svg         иконка
avatar.jpg          аватар
sites/
  coffee/index.html сайт кофейни
  barber/index.html сайт барбершопа
  tutor/index.html  сайт репетитора
```

Каждый сайт — автономный HTML-файл: открывается двойным кликом, без сервера и зависимостей.

---

## Локальный запуск

```bash
git clone https://github.com/NAME-studio/Portfolio.git
cd Portfolio
start index.html      # Windows
open index.html       # macOS
```

---

## Что важного в этой работе

- **Адаптив от 360 px** — карточки и типографика перестраиваются, ничего не вылезает.
- **Анимации на CSS** — появление секций, параллакс, микро-интеракции; всё отключается при `prefers-reduced-motion`.
- **Быстрая загрузка** — один файл, шрифты с `display=swap`, картинки с `loading="lazy"`.
- **SEO** — Open Graph, Twitter Card, JSON-LD (Person), канонический URL, `theme-color`.
- **Доступность** — `aria-label` на карточках, видимый фокус, семантические теги.

---

## Контакты

- GitHub: [@NAME-studio](https://github.com/NAME-studio)
- Сайт: [name-studio.github.io/Portfolio](https://name-studio.github.io/Portfolio/)
- Discord: [сообщество](https://discord.gg/VCemrH6M44)

---

<sub>© NAME studio · Ярослав</sub>
