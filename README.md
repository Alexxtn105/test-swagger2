# Работа с swaggo/swag 

Установка swag:
```bash
go install github.com/swaggo/swag/cmd/swag@latest
```

Генерация документации:
```bash
swag init
```

Запуск сервиса:
```bash
go run main.go
```

Сгенерированная документация по адресу:
http://localhost:8080/swagger