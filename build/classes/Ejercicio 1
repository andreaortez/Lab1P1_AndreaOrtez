package lab1_andreaortez;

import java.util.Scanner;
        
public class Lab1_AndreaOrtez {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        Scanner entrada = new Scanner (System.in);
        
        System.out.println("-- Bienvenido al sistema de calculo de promedio --");
        System.out.print("Ingrese su nombre: ");// Se ingresa el nombre de usuario
        String nombre = entrada.nextLine();
        
        //Se ingresan las notas de las cuatro clases
        System.out.print("Ingrese la nota final de la primera clase: ");
        double PrimeraClase = entrada.nextDouble();
                
        System.out.print("Ingrese la nota final de la segunda clase: ");
        double SegundaClase = entrada.nextDouble();
                
        System.out.print("Ingrese la nota final de la tercera clase: ");
        double TerceraClase = entrada.nextDouble();
        
        System.out.print("Ingrese la nota final de la cuarta clase: ");
        double CuartaClase = entrada.nextDouble();
        
        //Se calcula el promedio
        double sumaClase = PrimeraClase + SegundaClase + TerceraClase + CuartaClase;
        double promedio = sumaClase / 4;
        
        //Se imprime el calculo del promedio
        System.out.println("---- " + nombre + " el promedio de las cuatro clases es: " + promedio); 
    }
    
}
