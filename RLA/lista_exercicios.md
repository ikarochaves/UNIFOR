# UNIFOR
**Nome**: Ikaro Chaves
**Disciplina**: Raciocínio Lógico Algorítmico

## Exercício 3
### Fluxograma

```mermaid
flowchart TD
A([INICIO]) --> B{{Digite um número:}}
B --> C[\número\]
C --> D{número > 0}
D --NÃO--> E[O número não é positivo!]
D --SIM--> F[resto = número% 2]
E --> Z([FIM])
F --> G{resto == 0}
G --NÃO--> H{{ O número é impar!}}
G --SIM--> I{{O número é impar!}}
H --> Z
I --> Z



```



