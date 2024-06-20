## Docker-контейнер для REST API сервера приложения [Warehouse Management System](https://github.com/andrewliutov/WarehouseManagementSystem_App)

#### Команды для сборки образа и запуска контейнера:

1. Сборка образа: `docker build -t django_hw:test .`

2. Запуск контейнера: `docker run -d -p 8000:8000 --rm --name django_hw django_hw:test `
