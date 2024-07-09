# Sprint_6

Здесь хранится код для автотестов на Java для учебного проекта Яндекс.Практикума


## Задание 
Тебя пригласили помочь зоологам: они исследуют семейство кошачьих. Чтобы записывать наблюдения, учёные используют специальную программу. Тебе предстоит протестировать часть программы.

Чтобы увеличить покрытие, нужно вызвать каждый метод каждого класса в отдельном тесте. Для каждой ветки условия напиши отдельный тест. Некоторым веткам понадобится параметризованный тест.

1. Собери Maven-проект: подключи Jacoco, Mockito и JUnit.
2. Класс Lion не должен зависеть от класса Feline. Используй принцип инъекции зависимостей.
3. Напиши моки с помощью Mockito. Какие именно понадобятся — определи самостоятельно.
4. Напиши тесты на классы Feline, Cat и Lion.
5. Подумай, где можно применить параметризацию. Реализуй параметризованные тесты.
6. Оцени покрытие с помощью Jacoco: оно должно быть не менее 100% для классов Feline, Cat и Lion.

### Дополнительное задание
   
   Создай класс льва Алекса из мультфильма «Мадагаскар». Он будет наследником обычного льва.
   Помимо обычных методов у него есть свои:
   getFriends() возвращает список имён его друзей — зебры Марти, бегемотихи Глории и жирафа Мелман;
   getPlaceOfLiving() возвращает место, где он живёт — Нью-Йоркский зоопарк.
   Также нужно переопределить метод getKittens(), потому что у Алекса нет львят. А ещё — написать свой конструктор, так как в классе Lion нет дефолтного конструктора. Алекс самец, поэтому в конструктор класса Lion всегда будет передаваться одно и то же значение.
   Покрой тестами созданный класс.

## Использованные технологии

1. Java 11
2. JUnit 4.13.2
3. Jacoco 0.8.12 
4. Maven 4.0.0

## Обо мне

Ильяс Ганиев, курс "Автоматизатор тестирования на Java", 35 поток