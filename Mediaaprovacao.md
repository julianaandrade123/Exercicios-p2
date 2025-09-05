import java.util.Scanner;

public class Mediaaprovacao {

    public static void main(String[] args) {
        Scanner notas = new Scanner(System.in);

        System.out.println("Informe a primeira nota do aluno : ");
        double nota1 = notas.nextDouble();

        System.out.println("Informe a segunda nota do aluno : ");
        double nota2 = notas.nextDouble();

         double media = (nota1 + nota2)/2 ;

         if (media >= 7.0) {
             System.out.println("O aluno foi aprovado");
         }

         else {
             System.out.println("O aluno foi reprovado");
         }
    }
}
