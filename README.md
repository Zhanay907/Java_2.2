Отчёт о тестировании приложения "Позволяющее воспроизвести ситуацию с пополнением счета клиентом"
 

Краткое описание
1.В редакторе кода"Intellij IDEA" набрать код:



 public class Main {
 
  public static void main(String[] args) {
  
    double regularBonus = 0.3;
	
    double specialBonus = 0.6;
	
    double totalBonus = regularBonus + specialBonus;
	
    System.out.println(totalBonus);
	
  }
  
}


2. Осуществить запуск программы кликнув на кнопку “Run”

вызывает результат: Main 0.8999999999999999.

Описание тестов

Проведение динамическое тестирование. Тестирование позитивное, функциональное, тестировалась функция приложения: сложения данных.


Результаты
Количество неуспешных тестов 1.
Ссылки на баг-репорты: https://docs.google.com/document/d/1zchjEzaWkqr6v-vFq5I7rwmJ5SArkLO1RgbfLWzLD3g/edit?usp=sharing

Общие рекомендации
При создании Java-кода необходимо внимательно выбирать типы данных. 