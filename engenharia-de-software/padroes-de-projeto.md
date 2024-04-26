<h1 align="center">Tipos de Padrões de Projeto</h1>
<h2 align="left" style="color: #800080;">Criacionais</h2>
<p align="left">Esses padrões tratam do processo de criação de objetos. Eles visam separar um sistema da forma
como seus objetos são criados, compostos e representados. Essa separação é benéfica, pois
simplifica o sistema, torna-o mais modular e, portanto, mais fácil de manter e estender.</p>

<h3 align="left">Abstract Factory</h3>
<p align="left">Proporciona uma interface para criação de famílias de objetos relacionados ou
interdependentes sem especificar suas classes concretas.</p>

<h3 align="left">Builder </h3>
<p align="left">Provê uma interface genérica para a construção incremental de agregações.</p>

<h3 align="left">Factory Method</h3>
<p align="left">Define uma interface para criação de um objeto, permitindo que as suas
subclasses decidam qual classe instanciar.</p>

<h3 align="left">Prototype</h3>
<p align="left">Especifica os tipos de objetos a serem criados num sistema, usando uma
instância prototípica. Cria novos objetos copiando este protótipo.</p>

<h3 align="left">Singleton</h3>
<p align="left">Assegura que uma classe tenha apenas uma instância e provê um ponto global
de acesso a ela.</p>

<h2 align="left" style="color: #800080;">Estruturais</h2>
<p align="left">Estes padrões se concentram em como as classes e objetos podem ser compostos para formar
estruturas maiores. Eles ajudam a garantir que, quando uma parte do sistema muda, todo o
sistema não precisa ser refeito.</p>

<h3 align="left">Adapter</h3>
<p align="left">Converte a interface de uma classe em outra, esperada pelo cliente. O Adapter
permite que classes que antes não poderiam trabalhar juntas, por
incompatibilidade de interfaces, possam agora fazê-lo.</p>

<h3 align="left">Bridge</h3>
<p align="left">Separa uma abstração de sua implementação, de modo que ambas possam variar
independentemente.</p>

<h3 align="left">Composite</h3>
<p align="left">Compõe objetos em árvores de agregação (relacionamento parte-todo). O
Composite permite que objetos agregados sejam tratados como um único
objeto.</p>

<h3 align="left">Decorator</h3>
<p align="left">Anexa responsabilidades adicionais a um objeto dinamicamente. Provê uma
alternativa flexível para extensão de funcionalidade, sem ter que usar Herança.</p>

<h3 align="left">Façade</h3>
<p align="left">Provê uma interface unificada para um conjunto de interfaces em um
subsistema. O Facade define uma interface alto nível para facilitar o uso deste
subsistema.</p>

<h3 align="left">Flyweight</h3>
<p align="left">Usa o compartilhamento para dar suporte eficiente a um grande número de
objetos com alto nível de granularidade.</p>

<h3 align="left">Proxy</h3>
<p align="left">Provê um substituto ou ponto através do qual um objeto possa controlar o
acesso a outro.</p>

<h2 align="left" style="color: #800080;">Comportamentais</h2>
<p align="left">Esses padrões estão preocupados com os algoritmos e a atribuição de responsabilidades entre
objetos. Eles lidam com o processo de comunicação entre objetos e ajudam a tornar o sistema
mais flexível em termos de manutenção e escalabilidade.</p>

<h3 align="left">Chain of Responsibility</h3>
<p align="left">Separa (provê loose coupling) objetos transmissores dos receptores, dando a
chance de mais de um objeto poder tratar a mensagem.</p>

<h3 align="left"></h3>
<p align="left"></p>

<h3 align="left">Command</h3>
<p align="left">Encapsula uma requisição como um objeto. Suporta transações e “undo”.</p>

<h3 align="left">Interpreter</h3>
<p align="left">Usado para definição de linguagem. Define representações para gramáticas e
abstrações para análise sintática.</p>

<h3 align="left">Iterator</h3>
<p align="left">Provê um modo de acesso a elementos de um agregado de objetos,
sequencialmente, sem exposição de estruturas internas.</p>

<h3 align="left">Mediator</h3>
<p align="left">Desacopla e gerencia as colaborações entre um grupo de objetos. Define um
objeto que encapsula as interações dentre desse grupo.</p>

<h3 align="left">Memento</h3>
<p align="left">Captura e externaliza o estado interno de um objeto (captura um "snapshot").
Permite histórico.</p>

<h3 align="left">State</h3>
<p align="left">Deixa um objeto mudar seu comportamento quando seu estado interno muda,
mudando, efetivamente, a classe do objeto.</p>

<h3 align="left">Strategy</h3>
<p align="left">Define uma família de algoritmos, encapsula cada um deles, e torna a escolha de
qual usar flexível.</p>

<h3 align="left">Observer</h3>
<p align="left">Define uma dependência entre objetos de forma que quando um objeto muda
de estado, todos os seus dependentes são notificados e atualizados
automaticamente.</p>

<h3 align="left">Visitor </h3>
<p align="left">Representa uma operação a ser executada sobre os elementos da estrutura de
um objeto.</p>

<h3 align="left">Template Method/h3>
<p align="left">Define o esqueleto de um algoritmo em uma operação, deferindo alguns passos
para as subclasses.</p>
