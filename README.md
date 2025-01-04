# Finance Tracker

Este é um aplicativo simples de rastreamento financeiro que permite registrar, editar e excluir transações financeiras, bem como visualizar um resumo dos valores de entradas, saídas e saldo total. O projeto é baseado em HTML, CSS e JavaScript e utiliza o `localStorage` para armazenar os dados localmente no navegador.

## Funcionalidades

- Adicionar transações com os seguintes campos:
  - Tipo: Entrada ou Saída
  - Descrição
  - Valor
  - Data
- Exibir transações em uma tabela, organizadas por data.
- Editar ou excluir transações diretamente na tabela.
- Calcular automaticamente:
  - Total de Entradas
  - Total de Saídas
  - Saldo

## Tecnologias Utilizadas

- **HTML5**: Estrutura do site.
- **CSS3**: Estilização do layout responsivo e moderno.
- **JavaScript**: Lógica para manipulação de transações e interação com o usuário.
- **LocalStorage**: Armazenamento local dos dados no navegador.

## Como Usar

1. Clone este repositório ou faça o download dos arquivos.
2. Abra o arquivo `index.html` no navegador para usar o aplicativo localmente.
3. Para hospedar no GitHub Pages:
   - Faça o upload dos arquivos para um repositório no GitHub.
   - Ative o GitHub Pages em "Settings > Pages" e escolha a branch e pasta correta.
   - Acesse o aplicativo pelo link gerado pelo GitHub Pages.

## Limitações

- Os dados são armazenados localmente no navegador utilizando o `localStorage` e não são compartilhados entre dispositivos.
- Para sincronizar os dados entre dispositivos, seria necessário implementar um back-end ou usar um serviço como Firebase.
