# Angular First App - Listagem de Imóveis (Angular 17)

## Descrição do Projeto

Este projeto é uma implementação do tutorial "First Angular App" (aplicativo de listagem de imóveis) utilizando Angular 17. O objetivo principal é guiar desenvolvedores através da criação de sua primeira aplicação Angular completa, cobrindo conceitos essenciais como componentes, templates, services, roteamento, e manipulação de formulários.

Este repositório documenta o processo de aprendizado e a aplicação prática dos conceitos do Angular 17 ao construir uma aplicação interativa de listagem de imóveis.

## Tecnologias Utilizadas

* **Angular 17:** A versão mais recente do framework Angular.
* **TypeScript:** Superset do JavaScript que adiciona tipagem estática.
* **HTML:** Linguagem de marcação para a estrutura das views.
* **CSS (ou SCSS/Sass):** Para estilização dos componentes.
* **Standalone Components:** Ênfase na nova arquitetura de componentes independentes do Angular.

## Funcionalidades Implementadas (Baseado no Tutorial Padrão "First App")

* **Listagem de Imóveis (Home Listings):** Exibe uma lista de imóveis disponíveis.
* **Filtragem de Imóveis:** Permite ao usuário filtrar a lista de imóveis com base em critérios (ex: cidade).
* **Detalhes do Imóvel:** Ao clicar em um imóvel, exibe uma página com detalhes específicos sobre ele.
* **Componentes:**
    * `AppComponent` (componente raiz)
    * `HomeComponent` (para a página inicial e listagem)
    * `HousingLocationComponent` (para exibir um card individual de imóvel)
    * `DetailsComponent` (para a página de detalhes do imóvel)
* **Services:**
    * `HousingService`: Para fornecer os dados dos imóveis para a aplicação.
* **Roteamento (Routing):** Configuração de rotas para navegar entre a página inicial e as páginas de detalhes dos imóveis.
* **Inputs e Outputs (`@Input()`):** Passagem de dados de componentes pais para componentes filhos (ex: para o `HousingLocationComponent`).
* **Manipulação de Formulários (Reactive Forms):**
    * Criação de um formulário de "Apply Now" (Candidatar-se agora) na página de detalhes.
    * Coleta de dados do usuário através do formulário.
    * Validação básica de formulário.
* **Uso de `async` pipe:** Para lidar com dados assíncronos (se aplicável no seu progresso do tutorial).
* **Interface (`HousingLocation`):** Definição de um tipo para os dados dos imóveis.

## Pré-requisitos

Antes de começar, certifique-se de ter instalado em sua máquina:

* **Node.js:** Versão 18.13.0 ou superior (que inclua npm). Recomenda-se a versão LTS mais recente.
* **Angular CLI:** Instalado globalmente. Se não tiver, instale com:
    ```bash
    npm install -g @angular/cli
    ```
* **Git:** Para clonar o repositório.

## Configuração e Instalação

1.  **Clone este repositório (ou o seu repositório onde o projeto está):**
    ```bash
    git clone https://github.com/jcquadros/first-angular-app.git
    cd first-angular-app.git
    ```

2.  **Instale as dependências do projeto:**
    ```bash
    npm install
    ```
    *(Ou `yarn install` se você utilizar Yarn)*

## Como Executar a Aplicação

1.  **Inicie o servidor de desenvolvimento do Angular:**
    ```bash
    ng serve
    # ou, para abrir automaticamente no navegador:
    ng serve --open
    ```

2.  Abra seu navegador e acesse `http://localhost:4200/`. O aplicativo será recarregado automaticamente se você alterar qualquer um dos arquivos de origem.

## Agradecimentos

Este projeto foi desenvolvido seguindo o tutorial oficial "First Angular App" da documentação do Angular (v17). Agradecimentos à equipe do Angular por criar um guia prático e introdutório tão eficaz.

* **Tutorial Oficial:** [Angular First App Tutorial (v17)](https://v17.angular.io/tutorial/first-app)
