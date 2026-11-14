# Рядом

Приложение для поиска магазинов и метро рядом с пользователем.

## Подготовка Android

```bash
npm install
npx cap add android
npx cap sync
```

Открой Android Studio:

```bash
npx cap open android
```

Затем выбери **Build → Generate Signed Bundle / APK → Android App Bundle**.

## Подготовка iOS

```bash
npm install
npx cap add ios
npx cap sync
```

Для сборки iOS без Mac используй Codemagic и workflow `ios-workflow`.

## Важно

Замени `com.example.nearby` на уникальный идентификатор приложения в `capacitor.config.ts` и `codemagic.yaml`.
