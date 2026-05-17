# ConectaBus Cidade

Protótipo de baixa fidelidade desenvolvido para a atividade prática de IHC & UX.

## Aluno

- Thais Augusta

## Sobre o Projeto

O **ConectaBus** é um aplicativo de mobilidade urbana criado para unificar diferentes meios de transporte da cidade, como ônibus, metrô, bicicletas compartilhadas e patinetes.

O objetivo do aplicativo é ajudar o usuário a se locomover pela cidade de forma rápida, segura e simples, principalmente em situações em que ele está na rua, com pressa ou usando o celular com apenas uma mão.

## Contexto de Uso

O usuário pode utilizar o ConectaBus em situações como:

- Indo para o trabalho, faculdade ou compromisso;
- Correndo para não perder o ônibus ou metrô;
- Procurando a rota mais rápida até um destino;
- Verificando se o transporte está lotado;
- Pagando a passagem diretamente pelo celular;
- Consultando informações importantes do veículo antes de embarcar.

Como o aplicativo pode ser usado em ambiente externo, o protótipo prioriza informações diretas, botões grandes e leitura rápida.

## Telas do Protótipo

O protótipo possui 5 telas principais:

1. **Busca de Rota**  
   Tela onde o usuário digita o destino ou escolhe uma sugestão rápida, como casa, trabalho, shopping, aeroporto ou centro.

2. **Resultado de Rotas**  
   Mostra as opções de caminho disponíveis, destacando alternativas como a rota mais rápida, mais barata ou com menos baldeações.

3. **Mapa de Percurso**  
   Exibe o trajeto da viagem no mapa, com uma visão simples da rota e das etapas do deslocamento.

4. **Carteira Digital**  
   Mostra o saldo disponível e o QR Code para pagamento da passagem diretamente na catraca.

5. **Detalhes do Veículo**  
   Apresenta informações importantes sobre o transporte, como tempo de chegada, lotação atual, acessibilidade, ar-condicionado e próximos horários.

## Fluxo de Navegação

O fluxo principal do aplicativo é:

```text
Busca de Rota
      ↓
Resultado de Rotas
      ↓
Mapa de Percurso
      ↓
Carteira Digital
      ↓
Detalhes do Veículo
```

Esse fluxo permite que o usuário pesquise uma rota, escolha a melhor opção, acompanhe o trajeto, pague a passagem e consulte informações do veículo antes de embarcar.

## Decisões de UX

Durante a criação do protótipo, algumas decisões foram tomadas para melhorar a experiência do usuário:

- O **tempo de chegada** foi colocado em destaque, pois é uma das informações mais importantes para quem está com pressa.
- Os **botões são grandes** para facilitar o uso com apenas um polegar.
- A interface utiliza **pouco texto**, reduzindo a carga cognitiva do usuário.
- Foram usados **ícones simples** para facilitar a compreensão rápida.
- A **lotação do veículo** aparece em destaque para ajudar o usuário a decidir se embarca ou espera outro transporte.
- O **QR Code** aparece em tamanho grande para facilitar a validação na catraca.
- As opções de rota mostram diferenças claras entre tempo, preço e quantidade de baldeações.

## Acessibilidade

O protótipo considera acessibilidade de algumas formas:

- Mostra se o veículo possui **rampa de acessibilidade**.
- Utiliza botões grandes e bem espaçados.
- Prioriza contraste entre fundo claro e elementos escuros.
- Evita excesso de informações na mesma tela.
- Usa textos objetivos e ícones de fácil entendimento.
- Facilita o uso por pessoas com mobilidade reduzida ou em situação de pressa.

## Prevenção de Erros

Em sistemas de mobilidade, um clique errado pode fazer o usuário perder o transporte ou seguir para o destino errado. Para reduzir esse risco, o protótipo utiliza:

- Cards separados para cada opção de rota;
- Destaque visual para o tempo total;
- Botões grandes e bem posicionados;
- Informações importantes no topo da tela;
- QR Code grande para evitar falha no pagamento;
- Ícones simples para identificar rota, pagamento e informações do veículo.

## Ferramenta Utilizada

O protótipo foi pensado para ser montado no **Miro**, utilizando wireframes simples em baixa fidelidade.

## Estrutura do Repositório

```text
ihcux-conectabus-cidade/
│
├── prototipo/
│   ├── prototipo.png
│   └── prototipo.pdf
│
└── README.md
```

## Observações

Este projeto é um protótipo de baixa fidelidade, portanto o foco está na estrutura das telas, no fluxo de navegação, na hierarquia da informação e na experiência do usuário, e não no visual final da interface.
