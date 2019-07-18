# Fila
Fila em ArrayList

package fila;

import java.util.LinkedList;
import java.util.List;


public class Fila {

    public static void main(String[] args) {
    
        //CRIA A LISTA DINÂMICA
        List<Integer> fila = new LinkedList();
        fila.add(10);
        fila.add(11);
        fila.add(85);
        fila.add(42);
        fila.add(16);
        fila.add(13);
        
        //CHAMA O PRÓXIMO NÚMERO E ELIMINA ELE DA LISTA (COMO UM LOOPING)
        System.out.println("Próximo item:");
        System.out.println(fila.get(0));
        fila.remove(0);
        System.out.println("Próximo item:");
        System.out.println(fila.get(0));
        fila.remove(0);
        System.out.println("Próximo item:");
        System.out.println(fila.get(0));
        fila.remove(0);
    }
    
}
