import java.util.Scanner;

public class desepenhoaluno {

    public static void main(String[] args) {
        Scanner infaluno = new Scanner(System.in);

        System.out.println("Digite o nome do aluno: ");
        String nome = infaluno.next();

        System.out.println("Digite as notas do aluno: ");
        double p1 = infaluno.nextDouble();
        double p2 = infaluno.nextDouble();

        double media = (p1 + p2)/2;

        System.out.println("Digite as faltas do aluno: ");
        int faltas = infaluno.nextInt();

        if (faltas >=15) {
            System.out.println("O aluno foi reprovado por falta!");
        }else {
            if (media > 5.0 && media <7.0) {
                System.out.println("O aluno vai pra recuperação!");
            }
            else if (media > 7.0) {
                System.out.println("O aluno foi aprovado tanto em média como em frequencia!");
            }
            else {
                System.out.println("O aluno foi reprovado em média e falta");
            }
        }

    }
}
