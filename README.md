#Java beginner Practice Codes.

import java.awt.*;
import java.util.Date;

public class Main{
    public static void main(String args[]){
        System.out.println("Namaste Abhilasha!");
        byte age = 30;   [//primitive data types example. It is used for storing simple values.]
        long viewsCount = 3_123_456_789L;
        float price = 10.99F;
        char letter = 'A';
        boolean isEligible = false;
        
        Date now = new Date(); [//reference or Non-primitive data types example. It is used for storing complex objects.]
        System.out.println(now);
        
        Point point1 = new Point(1,1); [//They don't store actual values; they store the address of the memory or reference of the object in the memory.]
        System.out.println(point1);
        Point point2 = point1;
        point1.x = 2;
        System.out.println(point2);
        
        
        String message = "Hello World" + "!!";    [//Strings are reference types in Java; we can use the new operator and direct strings as well, as shown in the example below]
        System.out.println(message.toUpperCase());
        System.out.println(message.toLowerCase());
        System.out.println(message.length());
        System.out.println(message.indexOf("!!"));
        System.out.println(message.replace("!", "*"));
        System.out.println(message);
        
        [//So from the above example, we can conclude that a string in Java is immutable,]
        [//We do give so many commands for the message to print, but the actual message did not change.]
        [//Escape sequences (\), used to escape anything from a sequence.]
        String message2 = "c:\\windows\\...";
        System.out.println(message2);  [//here 2nd \ both times got escaped due to the 1st \ at both places.]
        [// we can also use \n for new line and \t for tab spaces.]
    }
}
