# menuDAM1
/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package ej.ed;

import java.util.Scanner;

/**
 *
 * @author DAM109
 */
public class EJED {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
    Scanner reader = new Scanner(System.in);
int numero1,numero2;

System.out.println("Introduce un número");
numero1 = reader.nextInt();
		
System.out.println("Introduce el número por el cual quieres saber si es divisible");
numero2 = reader.nextInt();

if (numero1%numero2 == 0)
  System.out.println(numero1 + " es divisible por " + numero2);
else
  System.out.println(numero1 + " NO es divisible por " + numero2);
    
    }
    
}
