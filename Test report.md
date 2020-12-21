Краткое описание
--------------------
Проверить работу бонусного приложения компании на точность начисления бонуса

Дата начала: 21.12.2020  
Дата окончания: 21.12.2020  
На тестирование затрачено: 20 минут  

### В результате тестирования выявлены следующие дефекты:  
• Итоговая сумма считается неверно <https://github.com/rahel81/Java-task2.2/issues/1>

## Описание процесса тестирования:

### В процессе тестирования использовались следующие артефакты:  
• Программа IntelliJ IDEA  
• Код   
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

### Ожидаемый результат тестирования:  
Бонус составит 0.9

### Фактический результат тестирования:  
"C:\Program Files\AdoptOpenJDK\jdk-11.0.9.101-hotspot\bin\java.exe" -javaagent:C:\Users\user\AppData\Local\JetBrains\Toolbox\apps\IDEA-C\ch-0\203.5981.155\lib\idea_rt.jar=53821:C:\Users\user\AppData\Local\JetBrains\Toolbox\apps\IDEA-C\ch-0\203.5981.155\bin -Dfile.encoding=UTF-8 -classpath "C:\Users\user\Desktop\Тесты\JAVA\Task 2\Java-task2.2\out\production\src" Main
0.8999999999999999

### Тестирование производилось в следующем окружении:  
• Windows 7 Professional, x64  
• версия Java 11.0.9.1  
• браузер Google Chrome версия 87.0.4280.88 (Официальная сборка), (64 бит)
