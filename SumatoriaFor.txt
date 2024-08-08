/// ogonz15 //Sumatoria For/

import java.util.Scanner;
import java.io.PrintStream;

public class Main {

    public static void main(String[] args) {
        int a;a=0;
        int b;b=1;
        int resultado;
        int resultado2;
        int c;

        resultado=a+b;
        c=0;
        for (int i = 0; i<=9; i++) {

            resultado2 = resultado+i;
            c=c+i;
            System.out.println("numero" + " " + resultado2);
            //System.out.println("\n");

        }
        c=c+10;
        System.out.println("Sumatoria" + "  " + c);

    }
}