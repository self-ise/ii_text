# Модуль исправления грамматических ошибок в тексте на английском языке
## Описание

Задача модуля заключается в исправлении грамматических ошибок

## Принцип работы

Модуль использует модель grammarly/coedit-large, основанной на языковой модели Google. Исходный текст токенизируется,
затем передается в обработку нейронной сети. На выходе мы получаем токены. Полученный токены декодируются и полученный
результат выводится пользователю.