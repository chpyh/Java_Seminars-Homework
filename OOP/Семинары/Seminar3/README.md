# Работа со стандартными интерфейсами
## Задача 1 - Iterator
* Создать класс Студент
* Создать класс УчебнаяГруппа
* Создать класс УчебнаяГруппаИтератор, заставив его реализовать интерфейс Iterator
* Реализовать его контракты (включая удаление)

# Задача 2
* Модифицировать класс УчебнаяГруппа, заставив его реализовать интерфейс Iterable
* Реализовать метод iterator() возвращающий экземпляр созданного нами итератора

# Задача 3
* Модифицировать класс Студент, заставив его реализовать интерфейс Comparable
* Реализовать контракт compareTo () со сравнением по какому-либо параметру (пример studentId)

# Задача 4
* Реализовать контракт compare () со сравнением по какому-либо параметру (пример: сочетание Имя+Фамилия).

# Домашнее задание

* Создать класс Поток, содержащий в себе список УчебныхГрупп и реализующий интерфейс Iterable;

* Создать класс StreamComparator, реализующий сравнение количества групп, входящих в Поток;

Формат сдачи: ссылка на гитхаб проект

### Примечания:
Добавила в класс StudentGroup id для группы, чтобы вызывать группы для сравнения по айдишнику.