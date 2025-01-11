# Read-and-print-the-values
import java.util.Scanner;
public class readandprint {

    public static void main(String[]args){

        int num;
        System.out.print("Enter the integer:");
        Scanner sc = new Scanner(System.in);
        num = sc.nextInt();
        System.out.print("Entered integer is :" + num);
    }
}

OUTPUT:

Enter the integer:10
Entered integer is :10
