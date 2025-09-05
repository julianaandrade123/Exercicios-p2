public class Main {
    public static void main(String[] args) {
        // Estrtutura para instaciar uma classe
        Aluno aluno1 = new Aluno();

        //Adicionando valores aos atributos
        aluno1.nome = "Juliana";
        aluno1.idade = 20;
        aluno1.matricula = 123456;
        aluno1.curso = "Egenharia de Software";

        //para manipular melhor os dados variável ao invés de objeto, pra guarda os valores
        float media = aluno1.media(1, 9);

        aluno1.exibirDados();
        //System.out.println("Sua média é: " + aluno1.media(1, 9)); // o mesmo que float media = aluno1.media(1, 9), porém fica mais dificil manipilar os dados
    }
}
