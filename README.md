# spring-annotation
Configure Spring with Java Annotations

Java Annotations are special labels/markers. They provide metadata about the class. 
Java Annotations are processed at compile time or runtime for special processing.

Why using Spring Configuration with Annotation?

XML configuration can be verbose.
Annotations minimize the XML configuration.

Scanning for Component classes:
Spring will scan my Java classes for special annotations.
Automatically register the beans in the Spring container.

E.g

@Override
public class TrackCoach implements Coach {
  public String getDailyWorkout{
    return "Run a hard 5k";
  }
  ...
}

The annotation @Override tells the compiler that we are gonna implement an interface
or extend a class and we are overriding a method.
At compilation, the compiler will check/verify the override.
