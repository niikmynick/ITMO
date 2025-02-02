- Cериализация / десериализация объектов 
  - Java -> Jackson 
  - Kotlin -> kotlinx.serialization 


- Дополнительное задание: 

    Реализовать 10 модульных тестов с помощью JUnit5

    Для моков:
    - Java -> Mockito 
    - Kotlin -> MockK


- Jar архив 
    
    Стандартный `SlimJar` не включает в себя зависимости
    
    Варианты решения:
    - Написать task в gradle, который будет собирать все зависимости в один jar
    - Использовать [`ShadowJar`](https://github.com/johnrengelman/shadow)
