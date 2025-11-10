# Установка

1. Клонировать репозиторий с GitHub:
`git clone https://github.com/nightmarakesh/simple-devops-1.git`

2. Перейти в папку проекта: 
`cd simple-devops-1`

3. Что бы перейти в приложение, откройте файл `index.html` в браузере напрямую - двойной клик в проводнике или через локальный сервер.

---


# Опционально: запуск через Docker

1. В терминале внутри папки проекта собрать образ: 
`docker build -t username/simple-devops-1`.

2. Запустить контейнер:
`docker run -d -p 8080:80 username/simple-devops-1`

3. Открыть в браузере: <https://localhost:8080>
