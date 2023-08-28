Este projeto serve como um ótimo ponto de partida para quem deseja aprender a combinar o TypeScript com o Express para criar aplicativos web no ambiente Node.js. Ele demonstra como configurar um servidor simples que responde a uma rota básica. A partir deste exemplo, os podemos construir projetos mais complexos e escaláveis.

## Resumo de como foi configurado o projeto:

1. Inicialização do Projeto (npm init -y): Isso cria um arquivo package.json com configurações padrão para o projeto.

2. Instalação do TypeScript (npm install typescript): Isso instala o TypeScript no projeto.

3. Configuração do TypeScript (npx tsc --init): Gera um arquivo tsconfig.json que contém as configurações para o compilador TypeScript.

4. Instalação das Dependências do Node.js: Aqui, você está instalando várias dependências para o projeto, incluindo Express, Dotenv, Helmet, Rimraf e suas definições de tipo. Essas bibliotecas ajudam a criar um servidor web com segurança, manipulação de ambiente e outras funcionalidades.

5. Instalação das Dependências de Desenvolvimento: Você está instalando as dependências necessárias apenas durante o desenvolvimento, como o Concurrently e o Nodemon. O Concurrently permite executar vários comandos em paralelo, enquanto o Nodemon reinicia automaticamente o servidor quando os arquivos são modificados.

6. Adição de Scripts no package.json: Os scripts definidos permitem automatizar tarefas como compilação, execução e reinício do servidor. Os scripts build e serve são os mais notáveis. O build executa o TypeScript para compilar o código em JavaScript e o serve inicia o servidor Express usando Nodemon, facilitando o desenvolvimento.

7. Criação do Arquivo Principal (index.ts): Este arquivo é o ponto de entrada da aplicação. Ele importa as dependências necessárias, como o Express e o Helmet, configura o servidor Express para lidar com solicitações HTTP e, finalmente, inicia o servidor na porta especificada.
