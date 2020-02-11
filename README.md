# 70486
Estudos para o exame 70486
## Projetar Arquitetura do aplicativo

 - [ASP .NET MVC 5](https://docs.microsoft.com/pt-br/aspnet/mvc/overview/getting-started/introduction/getting-started) 
 - [ASP .NET MVC CORE](https://docs.microsoft.com/pt-br/aspnet/core/tutorials/first-mvc-app/start-mvc?view=aspnetcore-3.1&tabs=visual-studio)
 - [Controllers](https://docs.microsoft.com/pt-br/aspnet/mvc/overview/getting-started/introduction/adding-a-controller)
 - [Views](https://docs.microsoft.com/pt-br/aspnet/mvc/overview/getting-started/introduction/adding-a-view)
 - [Models](https://docs.microsoft.com/pt-br/aspnet/mvc/overview/getting-started/introduction/adding-a-model)
 - [Middlewares](https://docs.microsoft.com/pt-br/aspnet/core/fundamentals/middleware/?view=aspnetcore-3.1)
 - [Http Modules & Http Handles](https://support.microsoft.com/en-us/help/307985/info-asp-net-http-modules-and-http-handlers-overview)
 - [IoC](https://docs.microsoft.com/pt-br/aspnet/core/mvc/controllers/dependency-injection?view=aspnetcore-3.1)
 - Processamento lado Cliente -> Utilizar o browser do cliente atraves de javascript para relizar processamentos de cálculos, transformações validações;Pontos de atenção: segurança, tempo de processamento, latência de rede, não expor dados sensiveis etc...
 - Processamento lado Servidor -> Mais comunmente usado aonde aplicação tem todo o controle de calculos, transformações, fluxos e etc... Pontos de atenção: volume processamento, escalabilidade, empilhamento desnecessário etc...
 - [Razor Views](https://docs.microsoft.com/pt-br/aspnet/core/razor-pages/ui-class?view=aspnetcore-3.1&tabs=visual-studio) Bibliote de manipuladores para construção dos docs .cshtml
 - Arquiteturas hibridas on premisses e cloud
 - [Azure Redis](https://docs.microsoft.com/pt-br/azure/azure-cache-for-redis/cache-aspnet-session-state-provider) Sessão distribuida
 - [Web Farm Framework](https://www.iis.net/downloads/microsoft/web-farm-framework) balanceamento de carga, gerenciamento de servidores, gerenciamento de aplicações etc...
 - [Azure Pack](https://docs.microsoft.com/pt-br/previous-versions/azure/windows-server-azure-pack/dn296435(v%3Dtechnet.10)) simulador de nuvem local
 - [Azure Functions](https://azure.microsoft.com/pt-br/services/functions/) - serveless
 - [Azure Web App](https://azure.microsoft.com/pt-br/services/app-service/web/) - gerenciamento de aplicação, repos, devops, iaas
 - [Azure Monitor](https://docs.microsoft.com/pt-br/azure/azure-monitor/platform/data-sources-windows-events) - monitoramente de vários recursos da plataforma
 - [Asp Net Cookie](https://docs.microsoft.com/pt-br/aspnet/web-api/overview/advanced/http-cookies)
 - [Azure CDN](https://azure.microsoft.com/pt-br/services/cdn/) - compartilhamento global de arquivos, dados etc...
 - [SignalR](https://dotnet.microsoft.com/apps/aspnet/signalr) - lib para real-time connection, com websockets, pooling, long pooling
 - [Azure SignalR](https://docs.microsoft.com/pt-br/azure/azure-signalr/signalr-quickstart-dotnet-core) - implementação da lib para nuvem
 - [Azure Key Vault](https://azure.microsoft.com/pt-br/services/key-vault/) - armazenamento de dados de configuração como secrets, connection strings etc...
 - [Owin](http://owin.org/)
 - [Entity Framework 6](https://docs.microsoft.com/pt-br/ef/ef6/get-started) - ORM para .Net Framework
 - [Entity Framework Core](https://docs.microsoft.com/pt-br/ef/core/) - ORM para .Net Core
 - [ADO .Net DataReaders & DataAdapters](https://docs.microsoft.com/pt-BR/dotnet/framework/data/adonet/dataadapters-and-datareaders?redirectedfrom=MSDN) - Manipuladores de dados para ADO .Net
 - [Asp Net MVC Session](https://docs.microsoft.com/pt-br/aspnet/core/fundamentals/app-state?view=aspnetcore-3.1)
 
## Desenhar arquitetura de compilação e implementação

 - [GulpJs](https://gulpjs.com/) - automatizar tarefas de publicação para js, css etc...
 - [Grunt](https://gruntjs.com/) - automatizar tarefas de publicação para js, css etc...
 - [Node Package Manager NPM](https://www.npmjs.com/) - gerenciador de depêndencia para node
 - [Bower](https://bower.io/) - gerenciador de depêndencia para javascript e css e html
 - [Sass](https://sass-lang.com/) - linguagem de css
 - [Less](http://lesscss.org/) - linguagem de css
 - [Nuget](https://docs.microsoft.com/en-us/nuget/) - gerenciador de depêndencia para .Net (Core e Framework)
 - [Dotnet CLI](https://docs.microsoft.com/pt-br/dotnet/core/tools/?tabs=netcore2x) - interface de linha de comando para .Net Core
 - [Dockerize ASP .Net MVC Core](https://docs.docker.com/engine/examples/dotnetcore/) - estrategia para conteineres docker com asp net mvc core
 - [Web Deploy](https://docs.microsoft.com/pt-br/aspnet/web-forms/overview/deployment/configuring-server-environments-for-web-deployment/configuring-a-web-server-for-web-deploy-publishing-web-deploy-handler) - deploy no iis
 - [Visual Studio Publishing Wizard](https://docs.microsoft.com/pt-br/visualstudio/vsto/publish-wizard-office-development-in-visual-studio?view=vs-2019) - ferramenta do visual studio para deploy
 - [Kestrel](https://docs.microsoft.com/pt-br/aspnet/core/fundamentals/servers/kestrel?view=aspnetcore-3.1) - tcp listener padrão da plataforma .Net Core WebSocket, Http 2.0, Proxy Reverso, Nginx
 - [Nginx](https://www.nginx.com/) - servidor de proxy reverso linux
 - [Apache](https://httpd.apache.org/) - servidor de proxy reverso linux
 - [IIS](https://www.iis.net/) - servidor de proxy reverso windows
 - [Windows Nano Server](https://docs.microsoft.com/pt-br/windows-server/get-started/getting-started-with-nano-server) - núcleo do windows server 
 - [HTTP.sys](https://docs.microsoft.com/pt-br/aspnet/core/fundamentals/servers/httpsys?view=aspnetcore-3.1) - alternativa para kestrel não depende do iis, só funciona com ambiente windows  
 - [Azure DevOps](https://azure.microsoft.com/pt-br/services/devops/) - CI & CD para projetos no azure, construção de pipelines 
 
## Projetar a experiência do usuário
 - [HTML](https://www.w3schools.com/html/) - linguagem de marcação interpretada pela browser
 - [CSS](https://www.w3schools.com/css/default.asp) - linguagem de estilização interpretada pela browser em cascata
 - [Razor Pages](https://docs.microsoft.com/pt-br/aspnet/core/razor-pages/?view=aspnetcore-3.1&tabs=visual-studio) - fluxo novo do webforms
 - [Bootstrap](https://getbootstrap.com/) - framework de desenvolvimento front-end (html5, css3, jquery) 
 
## Desenvolver a experiência do usuário
 - [Chrome Devtools](https://developers.google.com/web/tools/chrome-devtools) - ferramenta para análise de web
 - [HTML Semantic](https://www.w3schools.com/html/html5_semantic_elements.asp) - semantica do html
 - [HTML Acessibility](https://www.w3schools.com/html/html_accessibility.asp) - acessibilidade para leitores de tela
 - [.Net Globalization](https://docs.microsoft.com/pt-br/aspnet/core/fundamentals/localization?view=aspnetcore-3.1) - globalização e localização para .net core
 - [ASP Net Core Authentication](https://docs.microsoft.com/pt-br/aspnet/core/security/authentication/?view=aspnetcore-3.1) - fluxo de autenticação no asp net core
 - [ASP Net Core Authotization](https://docs.microsoft.com/pt-br/aspnet/core/security/authorization/policies?view=aspnetcore-3.1) - fluxos para autorização do usuário
 - [ASP Net Core Results](https://docs.microsoft.com/pt-br/aspnet/core/web-api/action-return-types?view=aspnetcore-3.1) - resultado possiveis para as ações nos controladores
 - [ASP Net Core Routing](https://docs.microsoft.com/pt-br/aspnet/core/fundamentals/routing?view=aspnetcore-3.1) - roteamento de controladores e ações no asp net core
 - [ASP Net Core Serialization](https://docs.microsoft.com/pt-br/dotnet/standard/serialization/) - serialização em net core, XML, Json, protobuf
 
## Solução de problemas da web 
 - [IntelliTrace](https://docs.microsoft.com/pt-br/visualstudio/debugger/intellitrace) - analisador de eventos visual studio
 - [Application Insigths](https://docs.microsoft.com/pt-br/azure/azure-monitor/app/app-insights-overview) - gerenciamento de desempenho
 - [Azure DevLabs](https://azure.microsoft.com/pt-br/services/devtest-lab/) - ambiente para teste
 
## Projetar e implementar segurança
 - [Asp Net Core Identity](https://docs.microsoft.com/pt-br/aspnet/core/security/authentication/identity?view=aspnetcore-3.1&tabs=visual-studio) - gerenciamento de identidades nativo do asp net core
 - []
 
 
