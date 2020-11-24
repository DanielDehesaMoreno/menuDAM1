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
int numero1;

System.out.println("Introduce un número para saber si es divisible entre 15");
numero1 = reader.nextInt();
		
if (numero1%15 == 0)
  System.out.println(numero1 + " es divisible por 15");
else
  System.out.println(numero1 + " NO es divisible por 15");
    
    }
    
}
