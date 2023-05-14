/* WAP to print a pattern like this:-   *
                                        * *
                                        * * *
                                        * * 
                                        *                  */
import java.io.*;
import java.util.*;

public class Main {
    public static void main(String[] args) {
        Scanner asd= new Scanner (System.in);
            int N= asd.nextInt();
            for (int row=1;row<=N;row++) {
                for (int col=1;col<=row;col++) {
                    System.out.print("*"+" ");    
                }
                    System.out.println();
            }

            for (int i=N-1;i>=1;i--) {
                for (int j=i;j>=1;j--) {
                        System.out.print("*"+" ");
                }    
                    System.out.println();
            }
    }
}
