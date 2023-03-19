# actividad2_punto6_poo
package nummayor;
import java.util.Scanner;
public class Nummayor {

    public static void main(String[] args) {
        double  num1,num2,num3,mayor;
        Scanner ingresot = new Scanner (System.in);
        
        System.out.println("Ingrese el numero 1:  ");
        num1 = ingresot.nextDouble();
        
        System.out.println("Ingrese numero 2:  ");
        num2 = ingresot.nextDouble();
        
        System.out.println("Ingrese numero 3:  ");
        num3 = ingresot.nextDouble();
        
        if ((num1>num2) &&(num1>num3)){
            mayor=num1;
        } else if ((num2>num1)&&(num2>num3)){
            mayor=num2;
        }
            else {
                mayor=num3;
        }
        System.out.println("EL VALOR MAYOR ENTRE: "+ num1 +", "+ num2 +" Y "+ num3 +" ES: "+ mayor);
    }
    
    
}
