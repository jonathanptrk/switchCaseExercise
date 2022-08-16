# switchCaseExercise
Crie um menu com opções de 1 até 7 onde o usuário digite um número, cada número deve mostrar uma frase da sorte diferente do outro. 

package aula02.estruturasCondicionais;
import java.util.Scanner;


public class switchCase {
    public static void main(String[] args) {
        Scanner scan = new Scanner(System.in);
        // Crie um menu de 1 a 7 onde o usuário digite um número e mostre qual a frase da sorte daquele número.
        
        System.out.println("Digite um número de 1 até 7 e veja a sua sorte do dia: ");

        byte number = scan.nextByte();
        switch (number) {
            case 1:
                System.out.println("Demonstre amor e alegria em todas as oportunidades e verás que a paz nasce dentro de você.");
                break;
            case 2:
                System.out.println("Não compense na ira o que lhe falta na razão.");
                break;
            case 3:
                System.out.println("Não há que ser forte. Há que ser flexível.");
                break;
            case 4:
                System.out.println("Siga os bons e aprenda com eles.");
                break;
            case 5:
                System.out.println("São os nossos amigos que nos ensinam as mais valiosas lições.\n");
                break;
            case 6:
                System.out.println("A adversidade é um espelho que reflete o verdadeiro eu.\n");
                break;
            case 7:
                System.out.println("O riso é a menor distância entre duas pessoas.");
                break;
        }
        
        if (number < 1 || number > 7){
            System.out.println("Opção inválida");
        }
    }
}


