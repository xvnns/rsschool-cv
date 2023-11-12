# Ekaterina Krivokoneva

## Contact Information

- E-mail: katya.krivokoneva@gmail.com
- Telegram: @xvnns
- Discord: lamacon
- Samara, Russia

I'm backend developer and want to specialize in frontend development. I have a passion for learning and trying new technologies, as well as a passion for artificial intelligence technologies and a desire to keep up to date with the latest news in this field. I strive to constantly learn and improve my skills in software development.

## Skills
- JavaScript, HTML, CSS, Java, Python
- CUBA Platform, Spring Framework
- SQL (PostgreSQL, Oracle, HSQLDB)

## Code Examples

### [Fake Binary](https://www.codewars.com/kata/57eae65a4321032ce000002d)

```java
import java.lang.Character;
import java.util.stream.Collectors;

public class FakeBinary {
    public static String fakeBin(String numberString) {
        return numberString.chars().mapToObj(FakeBinary::toFakeBin).map(String::valueOf).collect(Collectors.joining());
    }
  
    private static char toFakeBin(int charCode) {
        int n = Character.getNumericValue(charCode);
        if (n < 5) return '0';
        return '1';
    }
}
```

## Work Experience
- Participation in the development of REST API service (Flask, Python)
- Parsing files (docx, htm)
- Participation in the development of web application (CUBA Platform, Java, xml)

## Education

#### 2021-2023

Samara University, Institute of IT and Cybernetics, Applied Mathematics and Computer Science, Data Science, Master

#### 2017-2021

Samara University, Institute of IT and Cybernetics, Applied Mathematics and Computer Science, Bachelor

#### Sep 2021 - Oct 2021

Backend-workshop, Simbirsoft

## Languages:

- Russian (Native)
- English (A2)
