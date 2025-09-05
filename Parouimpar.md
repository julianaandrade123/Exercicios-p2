import java.util.Scanner;

public class parouimpar {

    public static void main(String[] args) {
        Scanner numerointeiro = new Scanner(System.in);

        System.out.println("Informe um número inteiro");
        int numero = numerointeiro.nextInt();

        if (numero % 2 == 0){
            System.out.println("O numero é par");
        }

        else {
            System.out.println("O número é impar");
        }
    }
}
