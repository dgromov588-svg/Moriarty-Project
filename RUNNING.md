# Запуск Moriarty Project / Running Moriarty Project

## Быстрый старт / Quick Start

### Установка зависимостей / Install Dependencies

```bash
pip3 install -r requirements.txt --user
python3 -m playwright install
```

### Запуск приложения / Run Application

```bash
python3 MoriartyProject.py
```

Или используйте скрипт / Or use the script:
```bash
bash run.sh
```

### Доступ к приложению / Access Application

После запуска приложение будет доступно по адресу:
After starting, the application will be available at:

```
http://localhost:8080
```

или / or

```
http://<your-ip-address>:8080
```

## Примечания / Notes

- Приложение использует Flask для веб-сервера
- Используется Playwright для автоматизации браузера
- Требуется Python 3.6 или выше
- Для полноценной работы требуются системные библиотеки для Playwright

---

- Application uses Flask for web server
- Uses Playwright for browser automation  
- Requires Python 3.6 or higher
- System libraries required for Playwright full functionality

## Остановка / Stopping

Нажмите CTRL+C в терминале где запущено приложение
Press CTRL+C in the terminal where the application is running
