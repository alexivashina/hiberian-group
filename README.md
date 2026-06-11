# Hibernian Group — статичний сайт

Статична HTML/CSS-версія сайту [Hibernian Group](https://hiberniangroup.org.ua/),
зроблена як заміна конструктору OnePage (щоб не платити щомісячну підписку).
Повністю автономна — без бекенду, без залежностей, усі зображення лежать локально.

## Структура

```
├── index.html        # Про нас (укр)
├── poslugi.html      # Послуги та Кейси (укр)
├── en.html           # About us (англ)
├── poslugi-en.html   # Services and Cases (англ)
├── css/style.css     # Усі стилі
└── img/              # Зображення, логотипи, фото команди
```

## Технології
- Чистий HTML + CSS (без фреймворків і збірки)
- Шрифт **Montserrat Alternates** (Google Fonts)
- Адаптивна верстка (десктоп / планшет / мобільний)
- Перемикач мов UA / EN

## Як переглянути локально
Просто відкрийте `index.html` у браузері, або запустіть локальний сервер:

```bash
python3 -m http.server 8000
# відкрийте http://localhost:8000
```

## Деплой (безкоштовні варіанти)
Сайт статичний, тож його можна безкоштовно розмістити на:
- **GitHub Pages** — Settings → Pages → Deploy from branch → `main` / root
- **Cloudflare Pages** / **Netlify** / **Vercel** — підключити репозиторій, білд не потрібен

Після цього можна підключити власний домен `hiberniangroup.org.ua` і відмовитися від OnePage.

## Контакти
- 📞 +38 093 988 33 59
- ✉️ hiberniangrouporg@gmail.com
