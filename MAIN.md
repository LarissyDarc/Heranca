package br.com.animais;

public class Main {
    public static void main(String[] args) {
        // Criando os objetos
        Cachorro cachorro = new Cachorro("Rex", 5);
        Gato gato = new Gato("Mimi", 3);

        // Exibindo informações e sons
        cachorro.exibirInfo();
        cachorro.fazerSom();

        System.out.println("-----------------------");

        gato.exibirInfo();
        gato.fazerSom();
    }
}
