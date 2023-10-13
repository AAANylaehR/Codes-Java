#Java-Code2 Operators
package esclares;
import java.util.Scanner;

public class esclares {

 public static void main(String[] args) {
     Scanner in = new Scanner (System.in) ;
     int Num1, Num2, Num3, Num4;
     
     System.out.println ("Enter Num1:");
     Num1= in.nextInt();
      System.out.println ("Enter Num2:");
     Num2 = in.nextInt();
      System.out.println ("Enter Num3:");
     Num3 = in.nextInt();
      System.out.println ("Enter Num4:");
     Num4 = in.nextInt();
     
     System.out.println ("Enter Operator");
     System.out.println ("[+] [*]");
     System.out.println ("[/] [-]");
     char rhea = in.next (). charAt (0) ;
   
       switch (rhea) {
         case '+':
           int add = Num1+Num2+Num3+Num4 ;
         System.out.println ("Num1+Num2+Num3+Num4=" + add);
         System.out.println("The Sum of  Four Number is: "+ add);
         break;
             case '*':
               int mul = Num1*Num2*Num3*Num4 ;
         System.out.println ("Num1*Num2*Num3*Num4=" + mul);
          System.out.println("The Product of  Four Number is: "+ mul);
         break;
             case '/':
               int div = Num1/Num2/Num3/Num4 ;
         System.out.println ("Num1/Num2/Num3/Num4=" + div);
          System.out.println("The Diffirence of  Four Number is: "+ div);
         break;
             case '-':
               int sub = Num1-Num2-Num3-Num4 ;
         System.out.println ("Num1-Num2-Num3-Num4=" + sub);
          System.out.println("The Subtraction of  Four Number is: "+ sub);
         break;      
         default :
         System.out.println ("Invalid") ;  
     
    }
  }
}
