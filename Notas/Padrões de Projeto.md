### Padrões de Projeto

	Jogo: https://refactoring.guru
<iframe width="853" height="480" src="https://www.youtube.com/embed/tv-_1er1mWI" title="10 Design Patterns Explained in 10 Minutes" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
	
**1. Definição:**

- **Padrões de Projeto:** Soluções para problemas recorrentes de design de software. São abstrações que podem ser adaptadas para resolver problemas específicos.

**2. Categorias de Padrões de Projeto:**

- **Padrões Criacionais:**
    
    - **Exemplos:** Singleton, Factory Method, Abstract Factory, Builder, Prototype.
    - **Objetivo:** Lidar com o processo de criação de objetos.
- **Padrões Estruturais:**
    
    - **Exemplos:** Adapter, Bridge, Composite, Decorator, Facade, Proxy.
    - **Objetivo:** Lidar com a composição de classes e objetos para formar estruturas maiores.
- **Padrões Comportamentais:**
    
    - **Exemplos:** Observer, Strategy, Command, State, Template Method, Chain of Responsibility.
    - **Objetivo:** Lidar com algoritmos, responsabilidades e comunicação entre objetos.

**3. Exemplos de Padrões de Projeto:**

- **Singleton:**
    
    - **Definição:** Garante que uma classe tenha apenas uma instância e fornece um ponto global de acesso a ela.
    - **Uso Típico:** Para objetos que coordenam ações em todo o sistema.
- **Factory Method:**
    
    - **Definição:** Define uma interface para criar um objeto, mas permite que as subclasses alterem o tipo de objetos que serão criados.
    - **Uso Típico:** Em frameworks onde as classes de produtos têm várias implementações.
- **Observer:**
    
    - **Definição:** Define uma dependência um-para-muitos entre objetos, de modo que quando um objeto muda de estado, todos os seus dependentes são notificados.
    - **Uso Típico:** Em implementações de eventos e notificações.
- **Decorator:**
    
    - **Definição:** Anexa responsabilidades adicionais a um objeto dinamicamente.
    - **Uso Típico:** Para estender funcionalidades de classes de forma flexível.
- **Strategy:**
    
    - **Definição:** Define uma família de algoritmos, encapsula cada um deles e os torna intercambiáveis.
    - **Uso Típico:** Quando se deseja permitir que o cliente escolha o algoritmo a ser usado em tempo de execução.

**4. Considerações ao Aplicar Padrões de Projeto:**

- **Contexto:** Entender o problema e o contexto é crucial para aplicar o padrão corretamente.
    
- **Flexibilidade:** Os padrões devem ser aplicados quando há uma expectativa razoável de mudança.
    
- **Documentação:** Padrões devem ser documentados para facilitar a compreensão e manutenção.
    

**5. Antipadrões (Anti-Patterns):**

- **Definição:** Soluções comuns que parecem corretas, mas geralmente resultam em práticas ruins.
- **Exemplo:** Singleton Abusivo (uso excessivo de singletons).

**6. Ferramentas de Apoio:**

- **Livros:** "Design Patterns: Elements of Reusable Object-Oriented Software" (Gang of Four), "Head First Design Patterns".
- **Online:** Referências como o site da SourceMaking oferecem insights detalhados sobre padrões.