<div align="center">
  <img src="./assets/cozy-workspace.png" width="100%" alt="Espaço de trabalho em pixel art, com monitor, café e uma janela em uma tarde chuvosa" />

  <h1>Arthur Melo</h1>

  <samp>Java · Spring Boot · TypeScript · sistemas backend</samp>
</div>

<br />

Desenvolvedor backend, entusiasta de Java. Gosto de construir coisas, entender como funcionam e, principalmente, descobrir como fazê-las funcionar melhor.

## No que eu trabalho

### Sistemas web

Tenho trabalhado em CRMs e sistemas de gestão com backend em Java, Node.js e TypeScript. Entre eles estão um CRM multi-franquia, uma plataforma de atendimento por WhatsApp e um sistema para oficinas. Esses projetos envolvem autenticação, dashboards, integrações, tarefas agendadas, filas e comunicação em tempo real.

### Servidores Minecraft e Discord

Também trabalho com servidores Minecraft e bots Discord. Na parte de Minecraft, tenho projetos com minigames, contas, permissões, inventários e comunicação entre servidores. Para Discord, desenvolvi bots e um framework em TypeScript com comandos, eventos, injeção de dependência e carregamento automático de módulos.

## Projetos públicos

> ### [Discord Advanced Framework](https://github.com/arthurmeelo/Discord-Advanced-Framework)
>
> Framework em TypeScript para criar bots com Discord.js. Ele oferece decorators para comandos, eventos e serviços, container de injeção de dependência, módulos, guards, middlewares, tarefas agendadas e carregamento automático.
>
> O repositório também inclui uma CLI para iniciar bots, documentação separada por assunto, exemplos, testes com Jest e configuração de lint e formatação.
>
> `TypeScript` · `Node.js` · `Discord.js` · `Jest` · `Redis`

> ### [BedWars Hotbar Editor](https://github.com/arthurmeelo/bedwars-hotbareditor)
>
> Plugin Java para editar e organizar a hotbar de jogadores em um servidor BedWars. O jogador mantém um layout por categorias; quando um item aparece no inventário, o plugin identifica a categoria e o move para o slot configurado.
>
> A persistência foi isolada por uma interface comum, com implementações para MongoDB, MySQL e PostgreSQL. A atualização da hotbar pode usar pacotes ou a atualização convencional do inventário, sem misturar essa decisão com a regra de organização.
>
> `Java 8` · `Gradle` · `Bukkit` · `HikariCP` · `MongoDB / SQL`

> ### [Melo Network](https://github.com/arthurmeelo/melo-network)
>
> Base modular para uma rede de servidores Minecraft. O módulo `kernel` concentra modelos de contas, grupos, permissões, preferências e estado dos servidores, além das conexões com MongoDB e Redis.
>
> O projeto combina recursos voltados ao jogador, como minigames, com a parte de infraestrutura necessária para sincronizar servidores e compartilhar dados.
>
> `Java 8` · `Gradle` · `MongoDB` · `Redis` · `JUnit`

## Outros projetos em que trabalhei

### Sistema Grow

CRM multi-franquia com backend em Java 21 e Spring Boot e frontend em Next.js. O sistema tem dashboards de vendas, adimplência e retenção, gestão de usuários e franquias, biblioteca de materiais e integrações por webhook. No PostgreSQL, cada franquia trabalha em um schema próprio, com migrations gerenciadas pelo Flyway.

`Java` · `Spring Boot` · `PostgreSQL` · `Flyway` · `Next.js` · `TypeScript`

### ArgOS

Sistema de gestão para oficinas. Trabalhei no backend com Express e PostgreSQL e no frontend com Next.js e React. O projeto reúne ordens de serviço, clientes, veículos, orçamentos, estoque, financeiro, relatórios, cobrança e atualizações em tempo real com Socket.IO.

`Node.js` · `Express` · `PostgreSQL` · `Next.js` · `React` · `Socket.IO`

### CRM de atendimento

Plataforma multi-tenant de atendimento por WhatsApp. O backend em NestJS organiza conversas, contatos, filas, campanhas, automações, respostas rápidas, templates e integrações. Redis e BullMQ cuidam das filas de processamento, enquanto Socket.IO mantém as conversas atualizadas no frontend Next.js.

`NestJS` · `Prisma` · `Redis` · `BullMQ` · `Next.js` · `TypeScript`

### Hyris Network

Trabalhei no framework e nos servidores da rede. O código Java é dividido em módulos para comunicação, lobby, autenticação, BedWars, eventos e anticheat, com tarefas Gradle para montar e instalar os plugins no ambiente local. Também trabalhei no site em Laravel e em bots Discord integrados ao site.

`Java 17/25` · `Gradle` · `Paper/Spigot` · `JDA` · `Laravel` · `Discord.js`

### MeloPlay

Base de uma plataforma para organizar grupos e partidas esportivas. O projeto usa Laravel, Inertia.js e Vue, com PostgreSQL e Redis no ambiente Docker.

`Laravel` · `Vue` · `TypeScript` · `PostgreSQL` · `Redis` · `Docker`

## Tecnologias

Estas são as tecnologias e ferramentas presentes nos projetos que analisei:

| Área | Tecnologias e ferramentas |
| --- | --- |
| Linguagens | Java, TypeScript, JavaScript, PHP e Python |
| Backend | Spring Boot, NestJS, Express, Laravel e Node.js |
| Frontend | Next.js, React, Vue e Tailwind CSS |
| Bots e automações | Discord.js, JDA, filas, webhooks e tarefas agendadas |
| Servidores de jogos | Bukkit/Spigot, plugins, eventos, inventários e pacotes |
| Dados e comunicação | PostgreSQL, MongoDB, Redis, MySQL, Prisma, Socket.IO e sockets TCP |
| Build e qualidade | Gradle, Maven, npm, Composer, Jest, JUnit, ESLint e Prettier |
| Infraestrutura | Docker, armazenamento S3 e migrations com Flyway |
| Ambiente | Git, GitHub, IntelliJ IDEA e VS Code |

## Como organizo o código

Nos projetos maiores, tento separar a regra de negócio dos detalhes externos. No editor de hotbar, por exemplo, o serviço usa um contrato de armazenamento em vez de depender diretamente de um banco específico. No framework de Discord, comandos e serviços são resolvidos por um container, enquanto registradores, adapters e módulos ficam separados.

Nos sistemas web, organizo o backend por domínio e mantenho controllers, serviços, persistência e integrações em partes próprias. Uso migrations para mudanças no banco e testes para regras que não podem depender apenas de validação manual.

## Projetos menores

- [CommunicationSystem](https://github.com/arthurmeelo/CommunicationSystem) é um estudo em Java de canais, publicação de pacotes e comunicação por sockets.
- [Simple Calculator](https://github.com/arthurmeelo/Simple-Calculator) é uma calculadora Java com interface gráfica.
- [Zyntra Server](https://github.com/arthurmeelo/zyntra-server) reúne módulos de lobby, APIs para recursos de servidor, MongoDB e Redis em uma base Java para Minecraft.

## Contato

Para falar comigo sobre algum projeto, você pode enviar um e-mail para **[arthurmb3544@gmail.com](mailto:arthurmb3544@gmail.com)**.

<p align="center">
  <sub>Obrigado pela visita.</sub>
</p>
