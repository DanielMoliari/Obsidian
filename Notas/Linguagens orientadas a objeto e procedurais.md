1. **O que é:**
    
    - **Linguagens Orientadas a Objeto (OO):**
        
        - Características principais: Encapsulamento, Herança, Polimorfismo.
        - Exemplos: Java, C++, Python, C#.
        - **Explicação:**
            - **Encapsulamento:** Oculta os detalhes internos de implementação de um objeto, permitindo o acesso controlado aos seus atributos e métodos.
            - **Herança:** Permite a criação de novas classes baseadas em classes existentes, reutilizando código e estabelecendo relações hierárquicas.
            - **Polimorfismo:** Permite que objetos de diferentes tipos sejam tratados de maneira uniforme, facilitando a extensibilidade e flexibilidade do código.
    - **Linguagens Procedurais:**
        
        - Características principais: Procedimentos, Funções.
        - Exemplos: C, Fortran, Pascal.
        - **Explicação:**
            - **Procedimentos:** Blocos de código que realizam uma tarefa específica e podem ser chamados de outros lugares do programa.
            - **Funções:** Procedimentos que retornam um valor após a execução.
2. **Aplicações:**
    
    - **Linguagens Orientadas a Objeto:**
        
        - Aplicáveis em sistemas complexos, onde a estrutura do código reflete a estrutura do problema.
        - Facilitam a manutenção e extensão do código devido ao encapsulamento e reutilização de código.
    - **Linguagens Procedurais:**
        
        - Adequadas para problemas mais simples ou algoritmos sequenciais.
        - Úteis quando a estrutura do problema pode ser representada de forma linear e modular.
3. **Exemplo Prático (Java - Linguagem Orientada a Objeto):**
4. 
```
// Definição de uma classe em Java
class Animal {
    // Atributos
    String nome;

    // Método construtor
    public Animal(String nome) {
        this.nome = nome;
    }

    // Método polimórfico
    public void fazerBarulho() {
        System.out.println("O animal faz algum barulho");
    }
}

// Classe derivada (herança)
class Cachorro extends Animal {
    // Construtor chamando o construtor da classe base
    public Cachorro(String nome) {
        super(nome);
    }

    // Implementação específica do método polimórfico
    @Override
    public void fazerBarulho() {
        System.out.println("O cachorro late!");
    }
}

// Exemplo de uso
public class Main {
    public static void main(String[] args) {
        Animal animal = new Cachorro("Rex");
        animal.fazerBarulho(); // Resultado: O cachorro late!
    }
}
```

**Questão para Entendimento:**

- **Pergunta:** Qual é a principal vantagem da herança em linguagens orientadas a objeto?
- **Resposta:** A principal vantagem da herança é a capacidade de reutilizar código, permitindo a criação de novas classes baseadas em classes existentes, o que leva a uma estrutura mais modular e extensível do código.