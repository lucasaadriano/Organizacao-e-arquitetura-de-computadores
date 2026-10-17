
# 8. Linguagem de Máquina e Conjunto de Instruções

## Linguagem de máquina

É a forma de instrução representada por códigos binários que o processador consegue interpretar diretamente.

Esses códigos representam operações e informações necessárias para sua execução.

## Instruções

Uma instrução de máquina especifica uma operação que o processador deve realizar.

Dependendo da arquitetura, ela pode indicar:

- A operação desejada;
- Os registradores envolvidos;
- Os dados ou endereços utilizados.

## Exemplos de operações

- Soma;
- Subtração;
- Comparação;
- Leitura e escrita de dados;
- Desvio para outra instrução.

## Linguagem Assembly

Assembly é uma representação textual de instruções de máquina. Ela utiliza nomes simbólicos para facilitar a leitura por seres humanos.

Exemplo ilustrativo:

```asm
ADD R1, R2, R3
```

Em uma arquitetura que utiliza essa convenção, a instrução pode representar a soma dos valores de R2 e R3, com o resultado em R1. A sintaxe e o significado dependem da arquitetura.

## Conjunto de instruções (ISA)

ISA significa *Instruction Set Architecture*.

É a especificação das instruções e de outros recursos visíveis ao software, definindo a interface entre programas de baixo nível e o processador.

Exemplos de famílias de arquiteturas incluem x86-64 e ARM.

## Resumo

A linguagem de máquina é executada diretamente pelo processador. Assembly facilita a leitura dessas instruções, enquanto a ISA define o conjunto de operações e os recursos que o processador oferece.

