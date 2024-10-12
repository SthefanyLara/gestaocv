# Gestão de Envios de Currículos

Este projeto é uma aplicação simples que permite gerenciar os currículos enviados para diferentes vagas de emprego. Ele foi criado com HTML, CSS e JavaScript e utiliza o LocalStorage para armazenar os dados de forma persistente.

## Funcionalidades

- Adicionar um registro de envio de currículo com informações como:
  - Nome da empresa
  - Data de envio
  - Hora de envio
  - Status do processo (Enviado, Entrevista, Aguardando Resposta, Rejeitado)
  - Plataforma utilizada (LinkedIn, Indeed, etc.)
  - Link da vaga

- Alterar o **status** diretamente na tabela de currículos enviados.

- Excluir registros de currículos enviados.

- Contagem de quantos currículos foram enviados no dia atual.

- As informações persistem no navegador usando **LocalStorage**, então, mesmo que a página seja recarregada, os dados serão mantidos.

## Tecnologias Utilizadas

- **HTML**: Estrutura da página.
- **CSS**: Estilização e layout.
- **JavaScript**: Manipulação do DOM, persistência de dados com LocalStorage e lógica de controle.
- **LocalStorage**: Armazenamento persistente no navegador.

## Como Usar

1. Clone o repositório para a sua máquina local:
   ```bash
   git clone https://github.com/SthefanyLara/gestaocv.git
