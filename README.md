# Melhores-Praticas-de-Codificacao

--

- S — Single Responsiblity Principle (Princípio da responsabilidade única)
- O — Open-Closed Principle (Princípio Aberto-Fechado)
- L — Liskov Substitution Principle (Princípio da substituição de Liskov)
- I — Interface Segregation Principle (Princípio da Segregação da Interface)
- D — Dependency Inversion Principle (Princípio da inversão da dependência)

--
## SRP - Single Responsibility Principle:
- Uma classse só deve ter um motivo para mudar. Deve ser especializada em um único assunto e possuir apenas uma tarefa ou ação para executar.
### Violar SRP pode gerar:
- Falta de coesão
- Alto acoplamento
- Dificuldade na implementação de testes automatizados

--
## OCP - Open-Closed Principle:
Princípio Aberto-Fechado — Objetos ou entidades devem estar abertos para extensão, mas fechados para modificação, ou seja, quando novos comportamentos e recursos precisam ser adicionados no software, devemos estender e não alterar o código fonte original. **Alterar uma classe já existente para adicionar um novo comportamento, corremos um sério risco de introduzir bugs em algo que já estava funcionando.**

--
## LSP— Liskov Substitution Principle:
Princípio da substituição de Liskov — Uma classe derivada deve ser substituível por sua classe base.
Classes filhos podem ser passados como parametros de classes pai sem que seja necessário alterar as propriedades do software.

### Exemplos de violação do LSP:
Sobrescrever/implementar um método que não faz nada;
Lançar uma exceção inesperada;
Retornar valores de tipos diferentes da classe base;

--
## DIP — Dependency Inversion Principle:
Princípio da Inversão de Dependência — Dependa de abstrações e não de implementações.
De acordo com Uncle Bob, esse princípio pode ser definido da seguinte forma:

1. Módulos de alto nível não devem depender de módulos de baixo nível. Ambos devem depender da abstração.

2. Abstrações não devem depender de detalhes. Detalhes devem depender de abstrações.
