
# 4. Registradores e Memória Cache

## Registradores

Registradores são pequenas unidades de armazenamento localizadas dentro do processador.

Eles guardam informações necessárias durante a execução das instruções, como dados, endereços e resultados intermediários.

## Exemplos de registradores

- **PC (Program Counter):** guarda o endereço da próxima instrução a ser buscada, conforme o fluxo de execução.
- **IR (Instruction Register):** mantém a instrução que está sendo processada em determinadas arquiteturas.
- **Registradores de uso geral:** armazenam dados e resultados temporários.

Os nomes e as funções exatas dos registradores dependem da arquitetura do processador.

## Memória cache

A memória cache é uma memória de alta velocidade utilizada para manter cópias de dados e instruções que podem ser acessados novamente pelo processador.

Seu objetivo é reduzir o tempo médio de acesso às informações e diminuir a necessidade de acessar a RAM com tanta frequência.

## Níveis de cache

- **L1:** normalmente é a menor e mais rápida.
- **L2:** costuma ter maior capacidade que a L1.
- **L3:** em muitos processadores, possui maior capacidade e pode ser compartilhada entre núcleos.

A organização exata varia conforme o processador.

## Comparação

| Característica | Registradores | Cache |
|---|---|---|
| Localização | Dentro da CPU | Próxima ou integrada à CPU |
| Função | Guardar valores usados diretamente pelas instruções | Manter cópias de dados e instruções acessados com frequência |
| Capacidade | Muito pequena | Maior que a dos registradores |
| Velocidade | Extremamente alta | Muito alta |

## Resumo

Os registradores guardam informações utilizadas diretamente pelo processador. A cache mantém cópias de dados e instruções para acelerar os acessos à memória.

