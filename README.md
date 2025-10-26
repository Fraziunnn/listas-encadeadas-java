# Estruturas de Dados – Listas Encadeadas em Java

## Descrição do projeto
Este repositório contém três implementações de **listas encadeadas** em Java, desenvolvidas manualmente, sem o uso de classes prontas como `ArrayList` ou `LinkedList`.  
O objetivo é consolidar o aprendizado de estruturas de dados dinâmicas, utilizando **nós (Node)** e referências (`next`, `prev`).

Projetos incluídos:

1. **Lista Encadeada Simples** (`ListaSimples`)
2. **Lista Duplamente Encadeada** (`ListaDupla`)
3. **Lista Encadeada Circular** (`ListaCircular`)

---

## Estruturas implementadas

### 1. Lista Encadeada Simples
- Cada nó possui um valor (`data`) e referência para o próximo (`next`).
- Operações implementadas:
  - Inserção no início, meio e fim
  - Busca de elementos
  - Remoção de elementos
  - Listagem de todos os elementos
- Estrutura linear, percorre apenas em uma direção.

### 2. Lista Duplamente Encadeada
- Cada nó possui valor (`data`), referência para o próximo (`next`) e para o anterior (`prev`).
- Operações implementadas:
  - Inserção no início, meio e fim
  - Busca de elementos
  - Remoção de elementos
  - Listagem de todos os elementos
- Permite navegação **em ambos os sentidos**.

### 3. Lista Encadeada Circular
- Cada nó possui valor (`data`) e referência para o próximo (`next`).
- O último nó aponta de volta para o primeiro (`head`), formando um ciclo.
- Operações implementadas:
  - Inserção no início, meio e fim
  - Busca de elementos
  - Remoção de elementos
  - Listagem de todos os elementos
- Estrutura circular, ideal para cenários repetitivos ou contínuos.

---

## Instruções de execução

1. Abra o Eclipse IDE.  
2. Importe cada projeto (`ListaSimples`, `ListaDupla`, `ListaCircular`) para o workspace:  
   - File → Import → Existing Projects into Workspace → Browse → selecione a pasta do projeto → Finish  
3. Execute a classe **Main** correspondente em cada projeto:  
   - `MainListaSimples.java`  
   - `MainListaDupla.java`  
   - `MainListaCircular.java`  
4. Observe a saída no console, que demonstra todas as operações (inserção, remoção, busca e listagem).

---

## Exemplos de uso

### Lista Simples
```java
ListaSimples lista = new ListaSimples();
lista.inserirInicio(10);
lista.inserirFim(20);
lista.inserirDepoisDe(10, 15);
lista.listar(); // Saída: Lista: 10 15 20
lista.remover(15);
lista.listar(); // Saída: Lista: 10 20


Lista Duplamente Encadeada

ListaDupla lista = new ListaDupla();
lista.inserirInicio(5);
lista.inserirFim(15);
lista.inserirDepoisDe(5, 10);
lista.listar(); // Saída: Lista Dupla: 5 10 15
lista.remover(10);
lista.listar(); // Saída: Lista Dupla: 5 15


Lista Circular

ListaCircular lista = new ListaCircular();
lista.inserirInicio(100);
lista.inserirFim(200);
lista.inserirDepoisDe(100, 150);
lista.listar(); // Saída: Lista Circular: 100 150 200
lista.remover(150);
lista.listar(); // Saída: Lista Circular: 100 200


Prints de exemplo

Inclua na pasta prints/ imagens do console mostrando:

Inserção de elementos

Remoção de elementos

Busca de elementos

Listagem completa da lista

Exemplo de saída simulada:

Lista: 10 15 20
Lista Dupla: 5 10 15
Lista Circular: 100 150 200


Observações

Todo o código está comentado para melhor entendimento.

Nenhuma classe pronta do Java foi utilizada (ArrayList, LinkedList, etc.).

Estruturas implementadas manualmente com nós (Node) e referências (next, prev).

Para o vídeo explicativo, recomenda-se mostrar cada projeto em execução no Eclipse, destacando as diferenças entre as listas.

Autores

[Guilherme Frazão Feitoza] – Engenharia de Software – Centro Universitário Santo Agostinho
