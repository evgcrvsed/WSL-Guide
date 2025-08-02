# Установка WSL 2 и нужной версии Linux через CMD
## 🔧 Последовательность действий

- Установка WSL и включение 2-й версии программы.
```cmd
wsl --install --no-distribution && wsl --set-default-version 2 && wsl --list
```
---

## 🛠 Установка и удаление версии Linux
### Установка
- Получаем список всех доступных систем
```cmd
wsl --list --online
```

- Устанавливаем версию по названию
```cmd
wsl --install -d Debian
```

### Удаление
- Список установленных дистрибутивов
```cmd
wsl --list --verbose
```

- Удалить выбранную версию
```cmd
wsl --unregister Debian
```

## Выключение WSL
```cmd
wsl --shutdown
```
