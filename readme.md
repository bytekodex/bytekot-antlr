# Bytekot antlr

Декларации правил для лексера и парсера `antlr4` для `bytekot-painter` и других инструментов.

Поддерживается:
- Все опкоды и даже новые опкоды valhalla (`withfield` и `aconst_init`)
- Числа (`decimal` & `hex`)
- Строки
- Комментарии
- Декларация пути к файлу компиляции
- Ссылочные типы (с полным именем)
- Дескрипторы
- Сигнатуры
- Примитивные литералы (`BCLJZ`) (кроме `S` - затруднительно)
- Специальные типы (`boolean`, `void`)
- Ключевые слова
- Типы вызовов (`REF_invokeVirtual`, `REF_invokeSpecial`)
- Access флаги
- Constant pool теги (`Utf8`, `Integer`, `Methodref`)
- Декларация пакета

Любые улучшения буду рад принять, https://github.com/bytekodex/bytekot-antlr/pulls