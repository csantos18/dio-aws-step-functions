# AWS Step Functions - Workflows Automatizados

## Sobre o Projeto

Este repositório foi criado como parte do desafio da DIO sobre AWS Step Functions. O objetivo é documentar os principais conceitos aprendidos durante o laboratório e registrar insights sobre a criação de workflows automatizados na AWS.

## Objetivo do Desafio

Consolidar os conhecimentos sobre automação de processos usando AWS Step Functions, além de praticar a documentação técnica com Markdown e o compartilhamento de projetos por meio do GitHub.

## O que é AWS Step Functions?

O AWS Step Functions é um serviço da AWS usado para criar fluxos de trabalho automatizados. Ele permite coordenar diferentes etapas de um processo, integrar serviços da AWS e acompanhar visualmente a execução de cada tarefa.

Com esse serviço, é possível representar processos como máquinas de estado, em que cada etapa executa uma ação, toma uma decisão ou chama outro serviço.

## Conceitos Aprendidos

Durante o laboratório, foram estudados conceitos como:

- Criação de workflows automatizados;
- Uso de máquinas de estado;
- Organização de processos em etapas;
- Controle de fluxo com condições;
- Tratamento de erros;
- Integração com outros serviços da AWS;
- Monitoramento das execuções;
- Documentação técnica de uma solução em nuvem.

## Principais Estados em um Workflow

Alguns estados importantes usados no AWS Step Functions são:

- **Task**: executa uma tarefa ou chama outro serviço;
- **Choice**: cria decisões condicionais no fluxo;
- **Pass**: passa dados adiante sem executar processamento;
- **Wait**: aguarda um tempo antes de continuar;
- **Succeed**: indica que o fluxo terminou com sucesso;
- **Fail**: indica que o fluxo terminou com erro.

## Exemplo de Aplicação

Um exemplo prático de uso do AWS Step Functions seria um fluxo para processar pedidos em uma loja virtual:

1. Receber o pedido;
2. Validar os dados do cliente;
3. Confirmar o pagamento;
4. Verificar o estoque;
5. Separar o produto;
6. Enviar a confirmação ao cliente.

Cada uma dessas etapas pode ser representada dentro de uma máquina de estados, permitindo acompanhar o processo completo de forma visual e organizada.

## Benefícios Observados

O uso do AWS Step Functions oferece vantagens como:

- Melhor organização de processos automatizados;
- Facilidade para visualizar o fluxo de execução;
- Integração com diversos serviços da AWS;
- Maior controle sobre falhas e decisões;
- Rastreabilidade das etapas executadas;
- Redução da complexidade em workflows maiores.

## Estrutura do Repositório

```text
.
├── README.md
├── images/
└── notes/
    └── insights.md
```

## Insights do Laboratório

Este laboratório reforçou a importância de planejar bem um workflow antes da implementação. Ao dividir um processo em etapas menores, fica mais fácil entender, testar, corrigir e evoluir a solução.

Também foi possível perceber que o AWS Step Functions ajuda a reduzir a complexidade de integrações entre serviços, deixando o fluxo mais claro e fácil de monitorar.

## Conclusão

O desafio contribuiu para consolidar os conceitos de automação de workflows na AWS. O AWS Step Functions se mostrou uma ferramenta útil para criar processos organizados, visuais e integrados, sendo uma boa opção para aplicações que precisam coordenar múltiplas etapas de execução.

## Referências

- AWS Step Functions - Documentação oficial da AWS
- Documentação do GitHub
- Guia de Markdown do GitHub
