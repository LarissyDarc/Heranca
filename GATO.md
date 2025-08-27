package br.com.animais;

public class Gato extends Animal {

    // Construtor da subclasse chamando o da superclasse
    public Gato(String nome, int idade) {
        super(nome, idade);
    }

    // Sobrescrita do método
    @Override
    public void fazerSom() {
        System.out.println("Miau!");
    }
}
