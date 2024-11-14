## Task

Given a non-negative integer, 3 for example, return a string with a murmur: "1 sheep...2 sheep...3 sheep...". 
Input will always be valid, i.e. no negative integers.


**Solution:**
```java
public class AbbreviateTwoWords {

  public static String abbrevName(String name) {
    String[] arrOfStr = name.split(" ");
    String firstName = arrOfStr[0].toUpperCase();
    String lastName = arrOfStr[1].toUpperCase();
    char firstInitial = firstName.charAt(0);
    char lastInitial = lastName.charAt(0);
    String initials = firstInitial + "." + lastInitial;
    return initials;
  }
}
```
