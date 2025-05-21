# Laboratory Work V

## Задание
1. Создайте CMakeList.txt для библиотеки banking.
2. Создайте модульные тесты на классы Transaction и Account.
2.1. Используйте mock-объекты.
2.2. Покрытие кода должно составлять 100%.
3. Настройте сборочную процедуру на **GitHub Actions**
4. Настройте Coveralls.io.

# Banking Library  

Библиотека для работы с банковскими транзакциями и счетами, включающая модульное тестирование с использованием mock-объектов.  

## Структура проекта  

- `banking` - основная библиотека  
  - `Transaction` - класс для работы с транзакциями  
  - `Account` - класс для работы с банковскими счетами  
- `tests` - модульные тесты  
  - Покрытие кода: 100%  
  - Использование mock-объектов для изоляции тестов  

## Сборка проекта  

Проект использует CMake для сборки. Для сборки выполните:  

```bash
mkdir build
cd build
cmake ..
make
```

## Тестирование  

Для запуска тестов выполните:  

```bash
cd build
ctest
```

## Непрерывная интеграция  

- GitHub Actions настроен для автоматической сборки и тестирования  
- Coveralls.io интегрирован для отслеживания покрытия кода  

## Технологии  

- C++  
- CMake  
- Google Test/Mock  
- GitHub Actions  
- Coveralls.io  

[![Coverage Status](https://coveralls.io/repos/github/kssseniya/lab05/badge.svg?branch=main)](https://coveralls.io/github/kssseniya/lab05?branch=main)
