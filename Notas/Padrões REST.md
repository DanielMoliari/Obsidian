**Padrões REST**

* Definição: REST (Representational State Transfer) é um estilo arquitetural utilizado no desenvolvimento de serviços web, estabelecendo um conjunto de princípios para criar sistemas eficientes, escaláveis e interoperáveis. Padrões REST se baseiam em conceitos como recursos, URIs (Uniform Resource Identifiers), métodos HTTP e representações para facilitar a comunicação entre sistemas distribuídos.

* Objetivo: O objetivo é fornecer uma abordagem padronizada para o desenvolvimento de serviços web, garantindo simplicidade, escalabilidade e facilidade de manutenção.

_Exemplos de Conceitos:_

1. **Recursos:** Representam entidades do sistema e são identificados por URIs. Por exemplo, um recurso pode ser um usuário, um produto ou uma transação financeira.
    
2. **URIs (Uniform Resource Identifiers):** São identificadores únicos que representam recursos. Por exemplo, `/usuarios/123` pode ser a URI que identifica o usuário com ID 123.
    
3. **Métodos HTTP:** Utilizados para indicar a ação a ser realizada sobre um recurso. Exemplos comuns são GET (obter dados), POST (criar dados), PUT (atualizar dados) e DELETE (excluir dados).
    
4. **Representações:** Os dados de um recurso podem ser representados em diferentes formatos, como JSON ou XML, facilitando a comunicação entre sistemas heterogêneos.
    

_Exemplo de Implementação:_

**Exemplo de Recurso em REST (Java - Spring Boot):**
![[Pasted image 20240313173958.png]]

**Questões:**

1. **Questão (Conceitual):** _Pergunta:_ O que são URIs em padrões REST? _Resposta:_ URIs (Uniform Resource Identifiers) são identificadores únicos que representam recursos em um sistema REST, permitindo sua identificação e acesso.
    
2. **Questão (Técnica):** _Pergunta:_ Qual é o método HTTP comumente utilizado para obter dados de um recurso em REST? _a) POST_ _b) GET_ _c) PUT_ _d) DELETE_ _Gabarito:_ (b) GET
    

**Explicações para uma Pessoa de 5 Anos:**

Pense em REST como uma maneira legal de organizar brinquedos (recursos) para que todos possam compartilhar e entender o que está acontecendo. Cada brinquedo tem um nome especial (URI), e existem regras sobre como pedir, adicionar, atualizar ou remover esses brinquedos (métodos HTTP).

**Explicações Técnicas para um Concurso:**

Padrões REST fornecem uma abordagem arquitetural para o desenvolvimento de serviços web eficientes e escaláveis. Os conceitos principais incluem recursos, URIs, métodos HTTP e representações. Exemplos de métodos HTTP em REST são GET (obter dados), POST (criar dados), PUT (atualizar dados) e DELETE (excluir dados). O exemplo de código mostra um controlador REST em Java (Spring Boot) para operações básicas em recursos de usuário. O uso de anotações como `@GetMapping`, `@PostMapping`, `@PutMapping` e `@DeleteMapping` mapeia os métodos HTTP para operações específicas.