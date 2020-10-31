# actividad5
import java.util.Scanner;

public class Act5Java {
    public static Scanner sc= new Scanner(System.in);
    public static void main(String[] args){
        double numeroX;
        double numeroY;

        System.out.println("Ingrese el valor de X: ");
        numeroX=sc.nextDouble();
        System.out.println("Ingrese el valor de Y: ");
        numeroY=sc.nextDouble();
        System.out.println("Valores X:" + numeroX + " Y: "+ numeroY);
        System.out.println("Suma: "+(numeroX+numeroY));
        System.out.println("Resta: "+(numeroX-numeroY));
        System.out.println("Multiplicacion: "+(numeroX*numeroY));
        System.out.println("Division: "+(numeroX/numeroY));
        System.out.println("Modulo: "+(numeroX%numeroY));

    }
}
