# UML的常用图解
![Diagram](http://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/howardli/notes/master/UML/uml.puml)

```java
public interface IFly {
    void fly();
}

public interface IIanguage {
    void speak();
}

public abstract class Bird {
    public void metabolism(Oxygen oxygen,Water water){

    }
}

public class Bird extends Animal {
    private Wing wing=new Wing();
}

public class WideGoose extends Bird implements IFly {

}

public class Penguin extends Bird {
    private Climate climate;
}

public class WideGooseAggregate {
    private WideGoose[] arrayWideGoose;
}

```