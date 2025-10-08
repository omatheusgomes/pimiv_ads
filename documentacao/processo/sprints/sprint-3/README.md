## DOCUMENTAÇÃO - SPRINT 3

<p align="center">
    <img src="https://github.com/omatheusgomes/pimiv/blob/main/documentacao/imagens/logo_img.png" alt="NexHelp" width="400px">
</p>

<p align="center"> 
 <a href="#desafio">Desafio</a> • 
 <a href="#definicao">Definição</a> • 
 <a href="#diagrama">Diagrama de Sequência</a> • 
 <a href="#fluxo">Fluxo de Mensagens</a>
</p>

<h1 align="center" width="200"> Diagrama de Sequência </h1>

<h2 id="desafio">🎯 Desafio</h2>

O principal desafio desta sprint foi representar, por meio de **diagramas de sequência**, os fluxos de interação entre os objetos do sistema durante a execução das funcionalidades definidas anteriormente. Essa etapa garante uma visão clara de como as classes e atores trocam mensagens em tempo real, preparando o terreno para a implementação dos processos do sistema.

<h2 id="definicao">🔍 Definição dos Diagramas</h2>

Os diagramas de sequência foram definidos com base no **diagrama de classes** e nos **casos de uso já mapeados**. Para cada funcionalidade crítica, identificamos quais objetos participam da interação, a ordem das mensagens trocadas e as condições de fluxo. Esse mapeamento permitiu estruturar visualmente como as operações do sistema ocorrem de ponta a ponta.

| Funcionalidade | Descrição | Imagem |
| :------------: | --------- | ------ |
| Abrir Chamado | Representa o fluxo desde o registro de um chamado pelo usuário até o armazenamento no sistema. | <img src="https://github.com/omatheusgomes/pimiv_ads/blob/main/documentacao/imagens/sequencia_abirchamado.png" alt="Sequência Abrir Chamado" width="600"> |
| Avaliar Atendimento e Encerrar Chamado | Fluxo em que o Cliente avalia o atendimento; o Backend registra a nota, notifica o Técnico em casos críticos para possível reabertura e, se a avaliação for positiva, encerra o chamado e informa o usuário.| <img src="https://github.com/omatheusgomes/pimiv_ads/blob/main/documentacao/imagens/sequencia_avaliaratendimento.png" alt="Sequência " width="600"> |

<h2 id="diagrama">📈 Diagrama de Sequência</h2>

O diagrama de sequência ilustra de forma visual a **linha do tempo das interações** entre usuários, objetos e componentes do sistema. Ele evidencia a ordem das mensagens trocadas e como os processos são encadeados.

<p align="center">
    <img src="https://github.com/omatheusgomes/pimiv_ads/blob/main/documentacao/imagens/diagramas/sequencia.pdf" alt="Diagrama de Sequência Geral" width="1000"> 
</p>

