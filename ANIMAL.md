package br.com.animais;

public class Animal {
    protected String nome;
    protected int idade;

    // Construtor
    public Animal(String nome, int idade) {
        this.nome = nome;
        this.idade = idade;
    }

    // Método genérico
    public void fazerSom() {
        System.out.println("O animal faz um som genérico.");
    }

    // Método para exibir informações
    public void exibirInfo() {
        System.out.println("Nome: " + nome + " | Idade: " + idade + " anos");
    }
}
