```mermaid
flowchart TD
A([INICIO]) --> B{{Digite os CPF's: }}
B --> C{Processo encontrado?}
C --sim--> D[\Processo identificado\]
C --nao--> E[\Processo não identificado\]
E --> B
D --> F{Há algo que ambas as partes desejam adicionar?}
F --sim--> G[Escreva aqui]
F --nao--> H[\Opções\]
G --> H
H --> J[Adicione suas assinaturas digitais]
J --> L[FIM]
````

