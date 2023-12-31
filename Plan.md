# План тестирования приложения fmh_android

## Определение объета тестирования
Объектом тестирования является приложение fhm-android в виде исходного кода некомпилированного приложения «Мобильный хоспис» для Android текущей конфигурации по состоянию на 08.02.2023 г.

-------------------------------------------------------------------------------
## Цели тестирования
### Целями проведения тестирования является:
1. Определение входных требований к приложению.
2. Определение реализованного функционала приложения на текущем этапе разработки.
3. Тестирование реализованного функционала приложения на текущем этапе разработки.
4. Тестирование пользовательского интерфейса приложения на текущем этапе разработки.
5. Определение возжможного объема автоматизации тестирования приложения по результатам проведенного тестирования.

### Границы приложения
Приложение будет тестироваться по следующему функционалу:
1. Билд приложения
2. Установочное тестирование приложения на заданном заказчиком эмуляторе без проведения кроссплатформенного тестирования
3. Запуск приложения
4. Страница авторизации пользователя по предоставленным заказчиком паре логин-пароль
5. Главная страница приложения
6. Навигация между страницами приложения
7. Страница Новостей
8. Возможность публикации новой Новости
9. Возможность редактировать имеющуюся Новость
10. Возможность просматривать имеющиеся Заявки (притензии)
11. Возможность редактировать имеющиеся Заявки (притензии), изменять их статус, содержимое
12. Возможность удалять Заявки и Новости
14. Валидация полей создания и редактирования Новости по предполагаемым или указанным критериям
15. Валидация полей создания и редактирования Заявки (притензии) по предполагаемым или указанным требованиям
16. Страница О Приложении

### Данное приложение подвергается следующим типам тестирования:
**Для отдельных полей:**

- Позитивное тестирование приложения (корректные
  данные, корректные шаги).
- Негативное тестирование (введение невалидных данных, некорректные шаги).

**Для всей системы:**

- Функциональное тестирование;
- Юзабилити тестирование;
- Тестирование пользовательского интерфейса.
-------------------------------------------------------------------------------
## Условия тестирования
### Общие условия:
1. Тестирование будет проводится на ОС: Windows 10 
2. Файл проекта fmh-android.zip
3. WinRAR
4. Android Studio 
5. Android Gradle Plugin 
6. Система сборки Gradle 
7. Compile SDK 
8. Build Tools 
9. Espresso
10. Allure
11. Junit

Тестирование будет проводиться по чек листу и составленным тест кейсам.
Чек лист включает в себя короткие условния проверок, тест кейс в данном случае служит для проверки корректности работы полей и отдельных элементов приложения.
Тестирование модуля календаря и часов на страницах Создание новости, Создания заявки, Редактирование новости и Редактированния заявки не входит в задачи данного тест плана, проверка данных модулей будет проведена формально по минимальному набору критериев по тест кейсу.

### Тестирование пользовательского интерфейса будет проводиться :
1. Указанная в общих условиях конфигурация оборудования
2. Эмулятор Android API - Pixel 6 API 29 и тестовом смартфоне Huawei P30 Pro API 29
3. Проект приложения в виде исходного кода для среды разработки (IDE) Android Studio
4. Данные авторизации в приложении:
- login2
- password2
-------------------------------------------------------------------------------
## Потенциальные Риски
1. Проведение тестирования приложения невозможно по определенным условиям
2. Увеличение сроков проведения этапов тестирования в виду необходимости дополнительных действий, не предусмотренных данным документом
3. Увеличение сроков тестирования при обнаружении значительного числа дефектов (временные расходы на подтверждение, регистрацию дефектов)


