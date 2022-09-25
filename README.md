# log.alpha.generate

## Welcome!

This repo contains an annotation processor which can be used to automatically generate
the boilerplate for [log.alpha](https://github.com/bowbahdoe/log.alpha).

## Example Usage
```java
import dev.mccue.log.alpha.generate.DeriveLogger;

@DeriveLogger
public final class Thing implements ThingLog {
    public static void main(String[] args) {
        log.info("this-logger-was-auto-genned");
    }
}
```

```xml
<repositories>
    <repository>
        <id>jitpack.io</id>
        <url>https://jitpack.io</url>
    </repository>
</repositories>
```
```xml
<dependency>
    <groupId>dev.mccue</groupId>
    <artifactId>log.alpha.generate</artifactId>
    <version>main-SNAPSHOT</version>
</dependency>
```