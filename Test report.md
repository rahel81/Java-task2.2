Отчёт о тестировании приложения "Precision"
============
Краткое описание
----------------------
21.12.2020 было проведено тестирование приложения "Precision". На тестирование затрачено 15 минут

Создаём базовое приложение в IntelliJ IDEA, вводим код:  
``` java
public class Main {
  public static void main(String[] args) {
    double regularBonus = 0.3;
    double specialBonus = 0.6;
    double totalBonus = regularBonus + specialBonus;
    System.out.println(totalBonus);
  }
}
```
Описание тестов
-------
Проводилось функциональное, позитивное/негативное тестирование приложения "Precision".

Результаты
------------------
Фактический результат - не успешный тест
Баг репорт [Bonus system makes an incorrect calculation #1](https://github.com/rahel81/Java-task2.2/issues/1)

Общие рекомендации
-------------------
Возможно изменить тип переменной с double на float
```java
public class Main {
        public static void main(String[] args) {
            float regularBonus = 0.3F;
            float specialBonus = 0.6F;
            float totalBonus = regularBonus + specialBonus;
            System.out.println(totalBonus);
        }
}
```

### Тестирование производилось в следующем окружении:  
• Windows 7 Professional, x64  
• версия Java 11.0.9.1  
• браузер Google Chrome версия 87.0.4280.88 (Официальная сборка), (64 бит)
