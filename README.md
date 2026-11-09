# Фудбалска школа Leopold

Сајт школе фудбала у Београду. Статички: `index.html` + слика у `assets/`.

## Локално

Отворите `index.html` у прегледачу или покрените из ове фасцикле:

```bash
npx --yes serve .
```

## GitHub → Vercel (бесплатно)

1. На GitHub направите нови репозиторијум и отпремите ову фасциклу (`leopold-skola`) као корен репоа.
2. На [vercel.com](https://vercel.com) → Add New Project → увезите тај репо.
3. Framework Preset: **Other**. Root Directory: празно (фајл `index.html` мора бити у корену).
4. Deploy. Домен `*.vercel.app` је бесплатан.

Команде ако репо већ иницијализован овде:

```bash
git add .
git commit -m "Сајт фудбалске школе Leopold"
git remote add origin https://github.com/USER/leopold-skola.git
git push -u origin main
```

## Шта још унети ручно

- Тачна адреса терена (сада се шаље на Вајбер после пријаве)
- Реална имена тренера ако нису ова измишљена
- Цене ако се разликују
