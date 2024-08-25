# AMA Application - Frontend

Este é o frontend da aplicação AMA (Ask Me Anything) desenvolvido com Vite, React e Tailwind CSS.

## Tecnologias Utilizadas

- **Vite**
- **React**
- **Tailwind CSS**

## Como Rodar

1. Clone o repositório:
   ```bash
   git clone https://github.com/leobritto95/semana-tech-go-react-web
   ```
2. Instale as dependências:
   ```bash
   npm install
   ```
3. Inicie o servidor de desenvolvimento:
   ```bash
   npm run dev
   ```

## Build para Produção

1. Para compilar a versão de produção:
   ```bash
   npm run build
   ```
2. Você pode usar qualquer servidor estático de sua preferência para servir os arquivos do build ou usar o `serve`.

   Usando `serve`:

   Primeiro, instale o serve globalmente:

   ```bash
   npm install -g serve
   ```

   Em seguida, sirva o build na porta desejada (por exemplo, 3000):

   ```bash
   serve -l 3000 -s build
   ```

   Agora você pode acessar a aplicação no navegador em http://localhost:3000.

## Backend

O backend da aplicação está disponível no repositório AMA [semana-tech-go-react-server](https://github.com/leobritto95/semana-tech-go-react-server).
