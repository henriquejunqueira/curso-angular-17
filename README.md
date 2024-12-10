# Curso de Angular v2 ao v17: Básico ao Profissional

- Nesse repositório estou salvando os arquivos, exercícios e projetos do curso do Felipe da Silva Freitas disponível na plataforma da Udemy no link:

[Curso de Angular v2 ao v17: Básico ao Profissional](https://www.udemy.com/course/super-treinamento-de-angular-16-do-basico-ao-avancado/)

- O curso aborda:

- Organização de projeto (pastas, arquivos e nomenclaturas)

- Desenvolvimento de aplicações web em Angular

- Padronização de aplicações Angular

- Organização de projetos Angular

- Componentização (evitando a duplicação de código)

- Criação de Templates dinâmicos

- Binding de dados (Event Binding, Property Binding, Attribute Binding, etc.)

- Projeção de Conteúdo

- Pipes

- Criação de formulários com Template-Driven Forms

- Utilização do Angular Material

- Diretivas

- Chamadas HTTP (Request e Response)

- CORS

- Renderização de páginas Web (Critical Rendering Path)

- SASS

- CSS

- Padronização BEM

- Build System (Grunt e Webpack)

- NPM

- JavaScript (polyfills, programação funcional, fluxo de execução, etc.)

- TypeScript (Decorators, tipagens dinâmicas, etc.)

- Modularização @NgModule, SCAM e Standalone

- Formulários Template-Driven Forms e Reactive Forms

- Diretivas NgIf, NgFor, NgClass e NgStyle

- Decorators @ViewChild, @ViewChildren, @Input e @Output

- Two-Way Data Binding

- Pipes (AsyncPipe, CurrencyPipe, DatePipe, etc...)

- Projeção de Conteúdo (ng-content, ng-template, ngTemplateOutlet)

- Diretivas com @HostBinding, @HostListener e ElementRef

- Organização de Projetos Angular: pastas, arquivos, nomenclaturas, interfaces

- Entendimento das principais funcionalidades do Angular

- Componentização pensada para o futuro evitando a duplicação de código

- Separação adequada das responsabilidades do componente

- Criação de templates dinâmicos

- Injeção de Dependência

- Observables RXJS síncronos e assíncronos

- Lifecycles do componente

- Padronização de projetos Angular de fácil manutenção

- Formulários com Angular Material

- Desenvolvimento Web (HTML, CSS, SASS)

- Tipagem de dados com TypeScript em Projetos Angular

- E muitas outras funcionalidades do Angular

### Comandos:

#### Criar projetos na arquitetura do curso na versão 16 tendo a 17v instalada:

- `$ ng new nome_projeto --no-standalone`
- ? Which stylesheet format would you like to use? Sass (SCSS)
- ? Do you want to enable Server-Side Rendering (SSR) and Static Site Generation (SSG/Prerendering)? No

#### Formas de criar projetos com a ultima versão do @angular/cli de forma global:

- `$ npm update -g @angular/cli`
- `$ npx @angular/cli new projeto-inicial`

#### Criar projetos em versões específicas (colocando a tag da versão após o @):

- `$ npm install -g @angular/cli@v8-lts`
- `$ npm install -g @angular/cli@latest`
- `$ npm install -g @angular/cli@v12-lts`

#### Rodando o projeto:

- `$ ng serve`

#### Gera um novo component:

- `$ ng generate component nome_component`

### Estrutura de projetos Angular:

#### Arquivos principais na raiz:

- `angular.json`: Arquivo de configuração do Angular CLI. Define como o projeto é construído, testado e serve para personalizar configurações como caminhos de saída e estilos;
- `package.json`: Lista as dependências e scripts do projeto. Usado pelo npm para instalar pacotes e gerenciar bibliotecas;
- `package-lock.json`: Arquivo gerado automaticamente que bloqueia as versões exatas das dependências instaladas para garantir reprodutibilidade;
- `tsconfig.json`: Configuração do TypeScript para o projeto. Define opções como a versão do JavaScript gerada, caminhos de importação e outros ajustes de compilação;
- `README.md`: Um arquivo Markdown gerado automaticamente com informações básicas sobre o projeto Angular;

#### Pastas principais:

- `src/`: Pasta principal onde o código-fonte do projeto está localizado;
- `src/app/`: Contém os componentes, serviços e módulos do aplicativo;
- `src/app/app.module.ts`: Módulo raiz do aplicativo Angular;
- `src/app/app.component.ts`: Componente principal do projeto;
- `src/app/app.component.html`: Template HTML do componente principal;
- `src/app/app.component.css (ou .scss)`: Estilo do componente principal;
- `src/assets/`: Pasta para recursos estáticos, como imagens, ícones e arquivos externos.;
- `src/main.ts`: Arquivo principal que inicia o aplicativo Angular. É aqui que o módulo raiz é carregado;
- `src/index.html`: Arquivo HTML principal do projeto. Serve como o ponto de entrada para o aplicativo no navegador;
- `src/styles.css (ou .scss)`: Arquivo global de estilos do projeto;
- `src/polyfills.ts`: Contém polyfills usados para compatibilidade com navegadores mais antigos;
- `node_modules/`: Diretório gerado automaticamente com todas as dependências instaladas via npm. Não deve ser alterado manualmente;
