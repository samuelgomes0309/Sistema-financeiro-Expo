Sistema Financeiro - Expo

🚀 Visão Geral do Projeto

O Sistema Financeiro - Expo é um aplicativo móvel de gerenciamento financeiro pessoal, desenvolvido com React Native e Expo. O objetivo é fornecer uma interface simples e intuitiva para o controle de receitas e despesas, permitindo ao usuário acompanhar seu saldo e movimentações financeiras.

O projeto utiliza o TypeScript para garantir a robustez do código e a biblioteca Axios para comunicação com uma API externa, indicando uma arquitetura client-server para o gerenciamento dos dados.

✨ Tecnologias Utilizadas

Este projeto foi desenvolvido utilizando as seguintes tecnologias:

Categoria
Tecnologia
Descrição
Plataforma
React Native
Framework para desenvolvimento de aplicativos móveis nativos usando JavaScript e React.
Ambiente
Expo
Conjunto de ferramentas e serviços que facilitam o desenvolvimento, build e implantação de aplicativos React Native.
Linguagem
TypeScript
Superset do JavaScript que adiciona tipagem estática, melhorando a manutenibilidade e a qualidade do código.
Navegação
React Navigation
Solução de roteamento e navegação para aplicativos React Native.
Requisições
Axios
Cliente HTTP baseado em Promises para fazer requisições a uma API externa.
Armazenamento
Async Storage
Armazenamento persistente e assíncrono de dados chave-valor no dispositivo.
Componentes
React Native Calendars
Componente de calendário para seleção de datas e visualização de eventos.
Notificações
React Native Toast Message
Biblioteca para exibir mensagens de notificação (toasts) na tela.


⚙️ Funcionalidades Principais

O aplicativo oferece as seguintes funcionalidades:

•
Autenticação de Usuário: Telas de Login e Cadastro de novos usuários.

•
Dashboard: Visão geral do saldo e das últimas movimentações financeiras.

•
Controle de Movimentações: Registro de receitas e despesas.

•
Visualização de Histórico: Acompanhamento das transações em um calendário.

•
Gerenciamento de Perfil: Edição de informações do usuário.

•
Rotas Protegidas: Separação de rotas públicas e privadas (autenticadas).

🛠️ Instalação e Configuração

Para rodar o projeto localmente, siga os passos abaixo:

Pré-requisitos

Certifique-se de ter o Node.js (versão 18+) e o yarn (ou npm/pnpm) instalados em sua máquina. Além disso, é necessário ter o Expo CLI instalado globalmente ou utilizar o npx.

Bash


npm install -g expo-cli


1. Clonar o Repositório

Bash


git clone https://github.com/samuelgomes0309/Sistema-financeiro-Expo.git
cd Sistema-financeiro-Expo


2. Instalar Dependências

Utilize o gerenciador de pacotes de sua preferência (o projeto utiliza yarn no package.json ):

Bash


yarn install
# ou npm install
# ou pnpm install


3. Configuração da API

O projeto espera uma variável de ambiente API_URL para se conectar ao backend.

Crie um arquivo .env na raiz do projeto e adicione a URL da sua API:

Plain Text


API_URL="SUA_URL_DA_API"



Atenção: O projeto utiliza a biblioteca react-native-dotenv para carregar variáveis de ambiente. Certifique-se de que a API esteja configurada e acessível.

4. Rodar a Aplicação

Inicie o servidor de desenvolvimento do Expo:

Bash


expo start
# ou yarn start


O Expo irá gerar um QR Code. Você pode escanear o código com o aplicativo Expo Go no seu celular (Android ou iOS) ou rodar em um emulador/simulador.

