# Sistema de Tarifas Bancárias

## Descrição

Este projeto simula um sistema de tarifas bancárias. Utiliza-se da leitura de dados financeiros de clientes a partir de um arquivo, e através de classes e métodos específicos, realiza o cálculo de tarifas para diferentes tipos de contas bancárias. Ao final do processo, o sistema gera arquivos individuais para cada cliente, detalhando o saldo total e as tarifas acumuladas.

## Características e Métodos Utilizados

- **Leitura de Arquivo**: Utilizou-se o namespace `System.IO` para a leitura de arquivos, especificamente o método `File.ReadAllLines`.

- **Lambda Expressions**: Implementadas para facilitar o mapeamento e transformação de dados do arquivo.

- **Classes e Abstração**: Foram criadas classes abstratas e concretas (`Conta`, `ContaCorrente`, `ContaCripto`, `ContaInternacional`) para representar diferentes tipos de contas e suas operações específicas.

- **Interfaces e Polimorfismo**: A interface `ITarifa` foi criada para garantir a implementação do método `CalcularTarifa` nas classes que a implementam, permitindo flexibilidade na forma como cada tipo de conta calcula sua tarifa.

- **Eventos e Delegates**: Utilizados para notificar quando o cálculo das tarifas foi concluído e para invocar métodos de callback associados.

- **Cultura e Formatação de Números**: O namespace `System.Globalization` foi utilizado para tratar de possíveis questões de formatação numérica e garantir a correta leitura e escrita de valores monetários.

- **Manipulação de Strings**: Métodos como `Split` e `ToString` foram empregados para tratamento de strings, tanto na leitura quanto na saída de dados.


## Observações

Este projeto foi construído como *Assessment* para a disciplina de Desenvolvimento com C#, sob a orientação do Professor Júlio César Ferreira Ramos Guimarães.

