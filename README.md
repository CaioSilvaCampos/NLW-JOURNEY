# Projeto: API para Site de Viagens

## Descrição
Este projeto é uma API desenvolvida para um site de viagens feito na NLW JOURNEY da Rocketseat, criada utilizando Node.js e TypeScript. O Prisma é usado como ORM para facilitar a manipulação do banco de dados de forma eficiente e segura.

### Principais Funcionalidades:
- Gerenciamento de destinos e pacotes de viagens.
- Cadastro e autenticação de usuários.
- Consulta de informações de viagens disponíveis.
- Integração com serviços de pagamento.

## Tecnologias Utilizadas
- **Node.js**: Ambiente de execução JavaScript no servidor.
- **TypeScript**: Superset de JavaScript que adiciona tipagem estática.
- **Prisma**: ORM moderno e eficiente para interagir com o banco de dados.
- **Express.js**: Framework minimalista para criação de rotas e controle HTTP.

## Pré-requisitos
- Node.js (v16 ou superior).
- npm ou yarn instalado.

## Instalação e Execução
1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   cd seu-repositorio
   ```

2. Instale as dependências:
   ```bash
   npm install
   ```

3. Configure o banco de dados no arquivo `.env`.

4. Gere as migrações e sincronize o banco de dados:
   ```bash
   npx prisma migrate dev
   ```

5. Inicie o servidor:
   ```bash
   npm run dev
   ```

## Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para abrir um *pull request* ou relatar problemas na seção de *issues*.

## Licença
Este projeto está licenciado sob a [MIT License](LICENSE).

