import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
            Scanner s = new Scanner(System.in);
            int n = s.nextInt(),r,c;
            for(r=1;r<=n;r++)
            {
                for(c=1;c<=r;c++)
                {
                    System.out.print("* ");
                }
                System.out.print("\n");
            }
            for(r=n-1;r>=1;r--)
            {
                for(c=1;c<=r;c++)
                {
                    System.out.print("* ");
                }
                System.out.print("\n");
            }
        }
    }
