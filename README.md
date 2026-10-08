<div align="center">
  <img src="./assets/cozy-workspace.png" width="100%" alt="Espaço de trabalho em pixel art, com monitor, café e uma janela em uma tarde chuvosa" />

  <h1>Arthur Melo</h1>

  <samp>Java · TypeScript · servidores Minecraft · bots Discord</samp>
</div>

<br />

Desenvolvedor backend, entusiasta de Java. Gosto de construir coisas, entender como funcionam e, principalmente, descobrir como fazê-las funcionar melhor.

## No que eu trabalho

### Sistemas para Minecraft

Grande parte dos meus projetos em Java está ligada a servidores Minecraft. Tenho código para contas e permissões, inventários, NPCs, minigames e comunicação entre servidores. Nesses projetos, uso MongoDB para persistência, Redis para comunicação e Gradle para organizar os módulos e builds.

### Ferramentas para bots Discord

Também desenvolvo ferramentas para bots Discord. Meu principal projeto nessa área é um framework em TypeScript que cuida da inicialização, do registro de comandos e eventos, da injeção de dependência e do carregamento automático de módulos.

## Projetos

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

## Tecnologias

Estas são as tecnologias e ferramentas presentes nos meus repositórios públicos:

| Área | Tecnologias e ferramentas |
| --- | --- |
| Linguagens | Java, TypeScript e JavaScript |
| Bots e automações | Node.js, Discord.js, decorators e tarefas agendadas |
| Servidores de jogos | Bukkit/Spigot, plugins, eventos, inventários e pacotes |
| Dados e comunicação | MongoDB, Redis, MySQL, PostgreSQL e sockets TCP |
| Build e qualidade | Gradle, Maven, npm, Jest, JUnit, ESLint e Prettier |
| Ambiente | Git, GitHub, IntelliJ IDEA e VS Code |

## Como organizo o código

Nos projetos maiores, tento separar a regra de negócio dos detalhes externos. No editor de hotbar, por exemplo, o serviço usa um contrato de armazenamento em vez de depender diretamente de um banco específico. No framework de Discord, comandos e serviços são resolvidos por um container, enquanto registradores, adapters e módulos ficam separados.

Também separo comandos, listeners, serviços, modelos, configuração e persistência em pacotes próprios. No projeto TypeScript, mantenho a documentação dividida por assunto e os testes junto das partes que eles cobrem.

## Outros projetos

- [CommunicationSystem](https://github.com/arthurmeelo/CommunicationSystem) é um estudo em Java de canais, publicação de pacotes e comunicação por sockets.
- [Simple Calculator](https://github.com/arthurmeelo/Simple-Calculator) é uma calculadora Java com interface gráfica.
- [Zyntra Server](https://github.com/arthurmeelo/zyntra-server) reúne módulos de lobby, APIs para recursos de servidor, MongoDB e Redis em uma base Java para Minecraft.

## Contato

Para falar comigo sobre algum projeto, você pode enviar um e-mail para **[arthurmb3544@gmail.com](mailto:arthurmb3544@gmail.com)**.

<p align="center">
  <sub>Obrigado pela visita.</sub>
</p>
