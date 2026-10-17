
# 9. Arquiteturas de Von Neumann e Harvard

## Arquitetura de Von Neumann

Na organização clássica de Von Neumann, instruções e dados compartilham a mesma memória e o mesmo caminho principal de comunicação.

### Características

- Instruções e dados ficam no mesmo espaço de memória;
- A mesma estrutura de comunicação pode ser utilizada para buscar instruções e acessar dados;
- O projeto é relativamente simples;
- Pode haver disputa pelo acesso à memória entre instruções e dados.

Essa limitação é conhecida como gargalo de Von Neumann.

## Arquitetura Harvard

Na arquitetura Harvard clássica, as instruções e os dados ficam em memórias separadas, com caminhos de comunicação distintos.

### Características

- Memória de instruções separada da memória de dados;
- Possibilidade de buscar uma instrução e acessar dados simultaneamente;
- Organização mais especializada;
- Pode exigir estruturas adicionais.

## Comparação

| Característica | Von Neumann clássica | Harvard clássica |
|---|---|---|
| Memória de instruções e dados | Compartilhada | Separada |
| Caminhos de comunicação | Compartilhados | Separados |
| Acessos simultâneos | Podem disputar o mesmo caminho | Podem ocorrer em paralelo |
| Organização | Mais unificada | Mais especializada |

## Arquiteturas modernas

Alguns processadores utilizam uma organização híbrida. Por exemplo, podem separar as caches de instruções e dados, mantendo uma memória principal compartilhada.

## Resumo

A principal diferença clássica é como instruções e dados são armazenados e acessados: juntos na arquitetura de Von Neumann e separados na arquitetura Harvard.

