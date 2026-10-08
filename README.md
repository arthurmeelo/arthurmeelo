<div align="center">
  <img src="./assets/cozy-workspace.png" width="100%" alt="Espaço de trabalho em pixel art, com monitor, café e uma janela em uma tarde chuvosa" />

  <h1>Arthur Melo</h1>

  <samp>Java · TypeScript · servidores Minecraft · bots Discord</samp>
</div>

<br />

Costumo aparecer onde há mais lógica do que tela: plugins, comunicação entre serviços, ferramentas para servidores e abstrações que evitam repetir o mesmo trabalho. Este perfil é um registro dessa curiosidade — dos primeiros estudos com Java até projetos maiores, com módulos, documentação e testes.

## Entre um commit e outro

Aprendi programação de forma autodidata. Servidores de Minecraft e bots para Discord foram dois laboratórios recorrentes: neles encontrei persistência de dados, eventos, sockets, permissões, interfaces extensíveis e vários motivos para organizar melhor o código.

Meu histórico público não segue uma linha perfeitamente reta. Há uma calculadora com interface gráfica, um estudo de comunicação por sockets, estruturas para redes de Minecraft e, mais recentemente, um framework completo em TypeScript. Gosto dessa sequência porque ela registra um aumento real de escopo: de poucos arquivos a módulos, testes e documentação própria.

```text
~/workspace
├── frameworks para bots
├── plugins e infraestrutura de servidores
├── comunicação entre serviços
└── projetos pequenos usados para aprender
```

## O que costuma sair daqui

### Sistemas para Minecraft

Meus projetos em Java vão além de comandos isolados. Eles incluem kernels compartilhados, gerenciamento de contas e permissões, inventários, NPCs, minigames e comunicação entre servidores. MongoDB aparece na persistência; Redis, na troca de informações entre instâncias; Gradle, na organização dos módulos e builds.

### Ferramentas para bots Discord

No ecossistema Node.js, o trabalho mais completo é um framework TypeScript para bots Discord. A ideia é concentrar inicialização, registro de comandos e eventos, injeção de dependência e carregamento automático em uma base reutilizável, deixando cada bot cuidar da sua própria regra de negócio.

### Estudos que viram peças reutilizáveis

Alguns repositórios começam pequenos, mas investigam problemas que reaparecem nos projetos maiores: canais de comunicação sobre sockets, dispatch de pacotes, separação entre interfaces e implementações de armazenamento e componentes independentes para interface, serviço e persistência.

## Projetos que contam melhor essa história

> ### [Discord Advanced Framework](https://github.com/arthurmeelo/Discord-Advanced-Framework)
>
> Framework em TypeScript para estruturar bots com Discord.js. Reúne decorators para comandos, eventos e serviços, container de injeção de dependência, módulos, guards, middlewares, tarefas agendadas e carregamento automático.
>
> O detalhe que mais representa o projeto é o cuidado ao redor da biblioteca: há CLI para iniciar bots, documentação separada por conceitos, exemplos, testes com Jest e configuração de lint e formatação.
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
> É um projeto importante no conjunto porque aproxima gameplay e infraestrutura: minigames e recursos voltados ao jogador convivem com sincronização entre servidores e dados compartilhados.
>
> `Java 8` · `Gradle` · `MongoDB` · `Redis` · `JUnit`

## A bancada de trabalho

Em vez de uma parede de logos, estas são as ferramentas que aparecem de fato nos repositórios públicos:

| Área | Tecnologias e ferramentas |
| --- | --- |
| Linguagens | Java, TypeScript e JavaScript |
| Bots e automações | Node.js, Discord.js, decorators e tarefas agendadas |
| Servidores de jogos | Bukkit/Spigot, plugins, eventos, inventários e pacotes |
| Dados e comunicação | MongoDB, Redis, MySQL, PostgreSQL e sockets TCP |
| Build e qualidade | Gradle, Maven, npm, Jest, JUnit, ESLint e Prettier |
| Ambiente | Git, GitHub, IntelliJ IDEA e VS Code |

## Um padrão que se repete no código

Conforme os projetos cresceram, comecei a separar com mais cuidado o que é regra do domínio e o que é detalhe externo. No editor de hotbar, por exemplo, o serviço conhece um contrato de armazenamento, não um banco específico. No framework de Discord, comandos e serviços são resolvidos por um container, enquanto registradores, adapters e módulos ficam em partes próprias.

Também costumo dividir projetos por responsabilidade — comandos, listeners, serviços, modelos, configuração e persistência aparecem em pacotes distintos. No projeto TypeScript, essa organização continua na documentação e nos testes. Não é uma arquitetura aplicada por cerimônia; é o resultado de voltar ao mesmo código e querer encontrar cada peça sem precisar reaprender o projeto inteiro.

## Projetos menores, perguntas úteis

- [CommunicationSystem](https://github.com/arthurmeelo/CommunicationSystem) é um estudo em Java de canais, publicação de pacotes e comunicação por sockets.
- [Simple Calculator](https://github.com/arthurmeelo/Simple-Calculator) registra um dos projetos iniciais: uma calculadora Java com interface gráfica.
- [Zyntra Server](https://github.com/arthurmeelo/zyntra-server) reúne módulos de lobby, APIs para recursos de servidor, MongoDB e Redis em uma base Java para Minecraft.

## Pode entrar em contato

Se você quiser conversar sobre algum dos projetos, trocar uma ideia sobre bots ou entender uma decisão de implementação, o caminho mais direto é o e-mail: **[arthurmb3544@gmail.com](mailto:arthurmb3544@gmail.com)**.

<p align="center">
  <sub>Obrigado pela visita — o café fica à esquerda do teclado.</sub>
</p>
