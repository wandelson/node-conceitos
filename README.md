



Parte 1 - Conhecendo o node.js


1. Instalação do Node.js: nodejs.org
2. No Windows, busque por “Variáveis de Ambiente” e configure:
NODE_ENV=’development’

3. Para testar, escrever um trecho em javascript no console:
> node
> console.log(‘curso node.js’);

4. Para sair, digite .exit
5. npm (node package manager): permite instalar módulos no projeto. As opções de instalação são:

• npm install nome_do_módulo : instala um módulo no projeto;

• npm install -g nome_do_módulo : instala um módulo global;

• npm install nome_do_módulo --save : instala o módulo no projeto, atualizando o package.json
na lista de dependências;

• npm list : lista todos os módulos do projeto;

• npm list -g : lista todos os módulos globais;

• npm remove nome_do_módulo : desinstala um módulo do projeto;

• npm remove -g nome_do_módulo : desinstala um módulo global;

• npm update nome_do_módulo : atualiza a versão do módulo;

• npm update -g nome_do_módulo : atualiza a versão do módulo global;

• npm -v : exibe a versão atual do NPM;

• npm adduser nome_do_usuário : cria uma conta no NPM, através do site https://npmjs.org.

• npm whoami : exibe detalhes do seu perfil público NPM (é necessário criar uma conta antes);

• npm publish : publica um módulo no site do NPM (é necessário ter uma conta antes). 

