import java.lang.*;
import java.util.*;
public class Addition 
{
     public static void main(String [] args)
     {
        int A=0,B=0,Sum=0;
        Scanner Sc=new Scanner(System.in);
        
        System.out.print("\n Enter value for A:");
        A=Sc.nextInt();

        System.out.print("\n Enter value for B:");
        B=Sc.nextInt();

        Sum=A+B;
        System.out.println("\n Addition of "+A+" & "+B+" is:"+Sum);

    }
}
