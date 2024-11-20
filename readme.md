# Телеграмм-бот для проверки заказов на Wildberries

## Описание проекта
Этот Телеграмм-бот позволяет пользователям получать уведомления о новых заказах на Wildberries через запросы к API.

## Установка
1. Клонируйте репозиторий: git clone https://github.com/yourusername/yourrepository.git
2. Перейдите в каталог проекта: cd yourrepository
3. Установите необходимые зависимости: pip install -r requirements.txt

## Настройка
- Получите API ключ для Wildberries и добавьте его в файл `config.py`.
- Убедитесь, что вы создали своего бота в Telegram и получили токен, добавив его в файл `bot.py`.

## Использование
- Команда `/start` - приветственное сообщение.
- Команда `/check_orders` - запрос на получение новых заказов.
- Бот будет автоматически уведомлять вас о новых заказах, если вы подписаны на уведомления.

## Контрибьюция
Если вы хотите внести свой вклад в проект, создайте форк репозитория, внесите изменения и предложите их через pull request.

## Проблемы и решения
Если у вас возникли проблемы с ботом, проверьте лог `bot.log` для получения информации об ошибках. Если проблема сохраняется, не стесняйтесь открывать issue в репозитории.
