Crie uma aplicação de agenda simples com as seguintes funcionalidades:
- um componente-pai Agenda, sendo o primeiro a ser chamado pela aplicação;
- um componente-filho Lista, sendo chamado pelo componente-pai Agenda;
- o componente-filho Lista recebendo, como Input Property do componente-pai Agenda, um array de objetos. O tamanho fica a seu critério e cada objeto tem essa configuração:

{
id: 1,
data: “00/00/0000”,
tarefa: “Uma tarefa”,
tipo: “IMPORTANTE, TRABALHO (exemplos)”,
concluida: true ou false
}

- o template do componente-filho exibe os itens da Lista. Uma dica é usar a diretiva *ngFor e a interpolação de itens. Esse assunto será melhor visto no próximo conteúdo, mas é importante realizar a pesquisa sobre os mesmos para a realização da atividade;
- cada item exibido no template do componente-filho deve conter um botão concluir tarefa que, ao ser clicado, deve emitir um evento para o componente-pai, o qual irá exibir um alerta no navegador indicando o id da atividade concluída. Nesse caso, a dica é usar o Output Property, o evento (click) de um botão e a função alert() do JavaScript;
- o componente-pai Agenda deve, ao ser iniciado, exibir um alerta escrito: “AGENDA DE (insira seu nome aqui)”.

Você pode customizar a folha de estilos de sua aplicação como bem lhe agradar. É indicado que as dicas dadas sejam seguidas.

Suba o código do projeto para sua conta no GitHub e compartilhe o link desse projeto no campo ao lado para que outros desenvolvedores possam analisá-lo.