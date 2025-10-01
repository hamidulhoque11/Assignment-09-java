**Switch**
<div style="overflow-x:auto;">
<pre>
<code>
import java.util.Scanner;
class Main {
    public static void main(String[] args) {
        Scanner sc= new Scanner(System.in);
        System.out.println("1.Bangla");
        System.out.println("2.Hindi");
        System.out.println("3.Urdu");
        System.out.println("4.English");
        System.out.print("Select your Language(1-4):");
        int digit= sc.nextInt();
            switch(digit){
                case 1:
                    System.out.println("Selected Bangla");
                break;
                case 2:
                    System.out.println("Selected Hindi");
                break;
                case 3:
                    System.out.println("Selected Urdu");
                break;
                case 4:
                    System.out.println("Selected English");
                break;
                    default:
                    System.out.println("Enter a digit between(1-4)");
            }
    }
}
</code>
</pre>
</div>
