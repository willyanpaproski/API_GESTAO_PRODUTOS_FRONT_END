🌐 Front-end da Aplicação de Gestão de Produtos

Este projeto é o front-end da aplicação de gestão de produtos, desenvolvido com Vite + React.
Ele depende da API disponível no seguinte repositório:
🔗 https://github.com/willyanpaproski/API_GESTAO_PRODUTOS_NODEJS

✅ Requisitos

Certifique-se de ter os seguintes itens instalados antes de iniciar:

    Node.js (versão 18 ou superior recomendada)

    npm (gerenciador de pacotes do Node.js)

    A API da aplicação em execução

🚀 Como rodar o projeto

Clone o repositório (caso ainda não tenha feito):

    git clone https://github.com/willyanpaproski/API_GESTAO_PRODUTOS_FRONT_END.git

    cd API_GESTAO_PRODUTOS_FRONT_END

Crie o arquivo .env na raiz do projeto, com base no .env.example, e configure a seguinte variável:

    VITE_API_URL: URL da API (por exemplo: http://localhost:3000)

Instale as dependências do projeto:

    npm install

Inicie o servidor de desenvolvimento:

    npm run dev

A aplicação será iniciada e normalmente ficará disponível em http://localhost:5173 (Observe o retorno no console para ter certeza em que porta a aplicação foi inicializada).

⚠️ Importante

    Para que os dados sejam exibidos corretamente, a API precisa estar rodando.

    Verifique se a URL configurada na variável VITE_API_URL está correta e acessível.
