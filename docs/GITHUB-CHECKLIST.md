# Чек-лист GitHub

## До первого коммита

- [ ] Экспортировать из Figma фото и миниатюры кейсов в `public/assets/`.
- [ ] Проверить права на все изображения и шрифты.
- [ ] Не добавлять в Git токены, пароли и ключи.
- [ ] Проверить, что в репозитории есть `.gitignore`.

## Рекомендуемая структура

```text
portfolio/
├── public/
│   └── assets/
├── src/
│   ├── components/
│   ├── styles/
│   └── main.*
├── docs/
├── README.md
└── .gitignore
```

## Публикация

```bash
git init
git add .
git commit -m "Initial portfolio handoff"
git branch -M main
git remote add origin https://github.com/<username>/<repository>.git
git push -u origin main
```

Перед выполнением последней строки нужно создать пустой репозиторий в своём аккаунте GitHub и заменить `<username>` и `<repository>`.

