import java.util.*;
import java.text.*;

public class Solution {
    
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        double payment = scanner.nextDouble();
        scanner.close();
        NumberFormat u= NumberFormat.getCurrencyInstance(Locale.US);
        NumberFormat i= NumberFormat.getCurrencyInstance(Locale.US);
        NumberFormat c= NumberFormat.getCurrencyInstance(Locale.CHINA);
        NumberFormat f= NumberFormat.getCurrencyInstance(Locale.FRANCE);
        
        
        System.out.println("US: "+u.format(payment));
        System.out.println("India: " + i.format(payment).replace("$","Rs."));
        System.out.println("China: " + c.format(payment));
        System.out.println("France: " + f.format(payment));
    }
}
