# triangle-pattern


import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner a = new Scanner(System.in);
        System.out.print("enter an integer:");
        int a1 = a.nextInt();
        for (int i = 1; i <= a1; i++) {
            for (int j = a1; j >= i; j--) {
                System.out.print(" ");
            }
            for (int k=1;k<=i;k++){
            System.out.print("*");}
            for(int j=2;j<=i;j++){
                System.out.print("*");}
            System.out.println(" " );
            }

        }}
