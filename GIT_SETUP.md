# Настройка Git репозитория для Sovrano Website

## Шаги для создания GitHub репозитория:

1. **Перейдите на GitHub.com** и войдите в аккаунт
2. **Создайте новый репозиторий:**
   - Нажмите "New repository" 
   - Название: `sovrano-website`
   - Описание: `Sovrano Distributions Website - Premium alcohol and gastronomy distributor in Armenia`
   - Сделайте репозиторий **Public**
   - НЕ добавляйте README, .gitignore или лицензию (они уже есть)
   - Нажмите "Create repository"

3. **Скопируйте URL репозитория** (будет что-то вроде `https://github.com/ваш-username/sovrano-website.git`)

4. **Выполните команды в терминале:**
   ```bash
   git remote add origin https://github.com/ваш-username/sovrano-website.git
   git push -u origin master
   ```

## После создания репозитория:

- Все изменения будут автоматически синхронизироваться с GitHub
- Cloudflare Pages сможет подключаться к репозиторию для автоматического деплоя
- Начальник сможет видеть все коммиты и изменения

## Текущий статус:
- ✅ Git репозиторий инициализирован
- ✅ Все файлы добавлены и закоммичены
- ✅ Созданы 2 коммита с полной историей изменений
- ⏳ Ожидается создание GitHub репозитория
