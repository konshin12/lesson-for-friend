
# Настройка
git config --global user.name "Ваше Имя"

git config --global user.email "ваша@почта.com"

# Создание репозитория
git init

git remote add origin URL_репозитория.git

# Рабочий процесс

git add .                  # Добавить все изменения

git commit -m "Сообщение"  # Закоммитить

git push                   # Отправить на сервер

git pull                   # Получить обновления

# Ветки
git checkout -b имя_ветки  # Создать ветку

git checkout имя_ветки     # Переключиться

git merge имя_ветки        # Слить с текущей веткой