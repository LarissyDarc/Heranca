package br.com.animais;

public class Cachorro extends Animal {

    // Construtor da subclasse chamando o da superclasse
    public Cachorro(String nome, int idade) {
        super(nome, idade);
    }

    // Sobrescrita do método
    @Override
    public void fazerSom() {
        System.out.println("Au au!");
    }
}
