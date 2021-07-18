# Отчёт о тестировании Бонусной программы для новых клиетов

## В ходе тестирования было проверено приложение Bonus на расчет бонусной суммы для новых клиентов

18.07.2021 - 18.07.2021  было проведено тестирование 

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:

![Неверный расчет бонусной системы](https://github.com/ElenaTyutina/Precision/issues/1)

### Описание процесса тестирования

Было создано базовое приложение на основе кода 

``` public class Main {
  public static void main(String[] args) {
    double regularBonus = 0.3;
    double specialBonus = 0.6;
    double totalBonus = regularBonus + specialBonus;
    System.out.println(totalBonus);
  }
}
```

Производился запуск программы с данными в коде с помощью Run ,либо сочетание клавиш Shift + ctrl + f10


В качестве тестовых данных использовались![данные](https://github.com/netology-code/javaqa-homeworks/tree/master/programming#%D0%B7%D0%B0%D0%B4%D0%B0%D1%87%D0%B0-2---precision)

** Ожидаемый результат **

Сумма бонуса = 0.9

** Фактический результат **

Сумма бонуса = 0.8999999999999999

Тестирование производилось в следующем окружении:

   * Linux x64 ОС
   * IntelliJ IDEA
   * Java 11.0.11 2021-04-20


