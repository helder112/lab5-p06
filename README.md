# [Algoritmos e Estruturas de Dados 2020 2021](https://elearning.ual.pt/course/view.php?id=1787) - [UAL](https://autonoma.pt/)

## Laboratório 5

O objetivo deste laboratório é produzir uma implementação da Árvore Binária de Pesquisa.

Este enunciado é acompanhado por um conjunto de ADTs, nós de árvore, e exceções.

Está também incluída a implementação dos ADTs Pilha e Fila, ambos em lista e em *array*.

Vai ser necessário criar os seguintes módulos:

- **`aed_ds/trees/binary_search_tree.py`**, que vai ter a classe `BinarySearchTree`, com a implementação da árvore binária de pesquisa.
- **`aed_ds/trees/binary_search_tree_iterator.py`**, que vai ter a classe `BinarySearchTreeIterador`, com a implementação do iterador com percurso infixo, da árvore binária de pesquisa.

A acompanhar o código segue também as seguintes baterias de testes:

- `tests/trees/test_binary_search_tree.py` que testa a classe `BinarySearchTree`
- `tests/trees/test_binary_search_tree_iterator.py` que testa a classe `BinarySearchTreeIterator`

O laboratório é considerado completo quando todos os testes estiverem passados.

Estão também incluídos os testes para os ADTs Pilha e Fila, embora não seja necessária qualquer implementação.

Os testes não são necessariamente exaustivos, pelo que o grupo de trabalho pode *acrescentar* testes, mas não pode alterar os que foram distribuídos.

Os testes pode ser executados de várias formas:

- Todos os testes do módulo
  - E.g., `python -m unittest tests.trees.test_binary_search_tree`
- Apenas um teste de uma classe
  - E.g., `python -m unittest tests.trees.test_binary_search_tree.TestBinarySearchTree.test_size`
- Todos os ficheiros de teste
  - `python -m unittest discover tests`
  - `python -m unittest discover tests/trees`

## Datas

| Evento                        | Data                 |
| ----------------------------- | -------------------- |
| Disponibilização de enunciado | 31/05/2021           |
| Entrega                       | 13/06/2021, 23:59:59 |

## Regras

- O trabalho deve ser realizado em grupo, previamente registado no *e-learning*.
- O código produzido deverá estar disponível no repositório GitHub gerado pelo GitHub Classroom.
  - Podem ser criados vários *branches*, de acordo com o organização que o grupo de trabalho considerar mais conveniente.
  - Deve sempre existir um *branch* `main`, onde a versão final deverá ficar disponível.

## Entrega
A versão final do trabalho deve estar disponível na *branch* `main` do repositório até à hora limite de entrega. Não serão considerados *commits* com data posterior à data limite.

A entrega deve também ser feita no *e-learning*, num ficheiro `zip` com todo o projeto.

## Atualização de enunciado

Repositório: <https://github.com/UAL-AED/lab5>

Para efetuar a atualização de enunciado:

1. Registar o repositório como `upstream` (só deve acontecer uma vez)
  
        git remote add upstream https://github.com/UAL-AED/lab5

2. Atualizar o `upstream` (sempre que existirem atualizações)

        git fetch upstream

3. Obter as alterações (e.g., ficheiro `README.md`)

        git checkout upstream/main README.md
