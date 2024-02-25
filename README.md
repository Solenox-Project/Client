## Solenox Project Reborn (Client)

### ВНИМАНИЕ! ИЗ ДАННОГО РЕПОЗИТОРИЯ УБРАНЫ КОНФИГИ МОДОВ.
### СБОРКИ ТЕСТИРОВАЛИСЬ НА ОС Fedora GNU/Linux 39 Workstation

### Описание

Этот репозиторий содержит ИСКЛЮЧИТЕЛЬНО сборки клиентов, обеспечивающих уникальный игровой процесс для игроков.
### Ветви Репозитория

* **master:** Стабильная ветвь, содержащая последнюю протестированную и пофикшенную сборку.
* **beta:** Ветка для тестирования новых функций и изменений перед объединением со стабильной веткой.
* **bleeding-edge:** Ветка для получения свежайших сборок (данная ветка крайне нестабильна).
* **testing:** Ветка для изолированного тестирования конкретных функций или исправлений ошибок.

### Структура Репозитория
Все сборки клиентов расположены в папках с именами серверов.

### Процесс Разработки

* Разработчиком создается эксперементальная сборка и заливается в ветвь bleeding-edge.
* Если при тестировании ветви bleeding-edge не выявлено критический ошибок, то она объединяется с ветвью testing, где происходит дальнейшее тестирование сборки.
* После тестирования сборки и устраниения ошибок в сборке, она отправляется в ветвь beta, где происходит автоматическое тестирование и окончательный багфикс.
* В конечном итоге, сборка попадает в ветвь master и отправляется на сервера обновлений     

### Приступая к работе

**1. Клонирование репозитория:**

```bash
git clone https://github.com/Solenox-Project/Client.git
```

**2. Установка зависимостей:**

Для корректной работы сервера необходимо установить следующие зависимости:

* Java Development Kit (JDK) 8
* Forge Mod Loader для Minecraft 1.12.2


### Вклад

Мы приветствуем участие сообщества! Чтобы внести свой вклад, читайте дальнейшие инструкции в файле `CONTIRUBING.md`

### Лицензия

Этот проект лицензирован под Solenox Project Open Source. Подробнее см. файл `LICENSE`.
