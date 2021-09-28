# leap-year
import java.util.Scanner;
public class Leap
    {
        public static void main (String args[])
        {
            int n=1;
            while(n==1)
            {
        long year;
        System.out.println("enter the year ");
        Scanner yer = new Scanner(System.in);
        year = yer.nextInt();
        System.out.println("enter the number of days feb month have");
        int feb;
        feb = yer.nextInt();
        if (year % 4 == 0 && feb == 29) {
            System.out.println("a year is leap year");
        } else {
            System.out.println("not a leap year");
        }
    }
    }
}
