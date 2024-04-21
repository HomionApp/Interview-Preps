# SOLID Priciples

1. **S**ingle Responsibility 
2. **O**pen-Closed 
3. **L**iskov Substitution 
4. **I**nterface Segregation 
5. **D**ependency Inversion 

## 1. Single Responsibility Principle
A class should have only one reason to change, or in other words, it should have only one responsibility. 

```
public class Book {

    private String name;
    private String author;
    private String text;

    //constructor, getters and setters
}
```

```
public class BookExporter {

    // methods for csv exporter
    void exportToCSV(){
        // ...
    }

    // methods for json exporter
    void exportToJSON(){
        // ...
    }
}
```

## 1. Open-Closed
