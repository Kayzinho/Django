1. Por que o arquivo .env não deve ser versionado?
2. Qual a função do pip freeze no contexto de desenvolvimento em equipe?
3. O que pode acontecer se a SECRET_KEY for exposta?
4. Qual o papel do .gitignore em projetos colaborativos?

RESPOSTAS:

1- por conter dados importantes, na maioria das vezes sendo chaves ou senhas

2- mostra todas as dependências do código/projeto e suas versões, fazendo com que seja mais fácil a instalação das mesmas exatas dependências, assim evitando conflitos ou falhas

3- um hacker pode usar isso para entrar no sistema ou causar algum dano

4- como o próprio nome ".gitignore" diz, cria uma lista de arquivos que o git deve ignorar, assim não serão enviados para o repositório
