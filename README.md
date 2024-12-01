# **Python Tree Utility**

### Консольное приложение для отображения структуры файлов и директорий в виде дерева

## **Функциональность**

1. Вывод структуры каталогов в виде дерева с декоративным оформлением.

2. Вывод количества найденных директорий и файлов.

3. Поддержка параметров запуска.

## **Аргументы командной строки**

- `-d` или `--directory` (опционально):
  - Указывает корневую директорию, с которой начинать сканирование.
  - По умолчанию используется текущая директория.

- `-l` или `--level` (опционально):
  - Ограничивает глубину отображаемой структуры.
  - Пример: `--level 2` выведет только два уровня вложенности.

## **Примеры использования**
1. **Вывод структуры текущей директории**:
     ```bash
     python tree_util.py
     ```
   
2. **Вывод структуры указанной директории с глубиной 2**:
    ```bash
    Copy code
    python tree_util.py --directory "/path/to/folder" --level 2
    ```
