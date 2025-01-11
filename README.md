# find-the-number-is-odd-or-even
import java.util.Scanner;
public class OddOrEven {
public static void main(String[] args) {
Scanner sc = new Scanner(System.in);
System.out.print("Enter a number: ");
int num = sc.nextInt();
if (num % 2 == 0) {
System.out.println(num + "is even.");
} else {
System.out.println(num + " is odd.");
}
}
}
Output

Enter a number: 4
4 is even.
Enter a number: 5
5 is odd.
