# Criando um repositório no GitHub 

</span>

<div align-"center">
<img src="https://user-images.githubusercontent.com/113153237/203190210-d4297cc9-01e7-461a-8503-f07f54184145.png" width= "150px" />
</div>

## Comandos do Git: 

- Git init
- Git add
- Git commit 

### Descrevendo o primeiro comando. 

**Git init:** O comando Git init cria um novo repositório do Git. Ele pode ser usado para converter um projeto existente e não versionado em um repositório do Git ou inicializar um novo repositório vazio.
Sempre que estivermos lidando com o terminal é necessário sempre colocar o nome do programa no inicio para chamar o terminal de comandos especificos do Git, por isso que todo comando do Git leva a palavra *"Git"* no inicio e o comando especifico logo após. 

**Criando um repositório:** Primeiramente é necessário criar uma pasta padrão no *Desktop* do computador do usuário, logo após o usuário clica com o botão direito e abre o *Git Bash Here*, assim será aberto o *Bash* do *Git* facilitando o manuseio dentro das pastas. 
Em seguida o usuário chama o comando *Git Init* para poder iniciar e possibilitar que o Git comece de fato a gerenciar e versionar o código, após esse comando o próprio Git retornara uma mensagem confirmando que foi iniciado um repositório vazio dentro da pasta padrão criada pelo usuário. 
Mesmo sendo uma pasta oculta gerencial do Git é possivel ver essa pasta usando a *flag* especifica (ls -a) e logo em seguida é possivel ver a pasta oculta gerencial do Git. 

### Descrevendo o segundo comando.

**Git add:** O comando Git add adiciona uma alteração no diretório ativo à área de staging. Ele diz ao Git que você quer incluir atualizações a um arquivo específico no próximo commit. No entanto, Git add não tem efeito real e significativo no repositório, as alterações não são gravadas até você executar o Git commit.
Junto com esses comandos, você também vai precisar do Git status para ver o estado do diretório ativo e da área de staging.

**Como funcinona o Git add:** Os comandos Git add e Git commit compõem o fluxo de trabalho fundamental do Git. Esses são os dois comandos que todo usuário do Git precisa entender. Eles são os meios de gravar versões de um projeto no histórico do repositório.
O desenvolvimento de um projeto gira em torno do padrão básico editar/preparar/fazer commit. Primeiro, você edita os arquivos no diretório ativo. Quando estiver pronto para salvar uma cópia do estado atual do projeto, o usuário prepara as alterações com git add. Logo após que estiver satisfeito com a captura de tela montada, o usuário faz um commit no histórico do projeto com o git commit.

### Descrevendo o terceiro comando. 

**Git commit:** O comando Git commit captura um instantâneo das mudanças preparadas do projeto no momento. Os instantâneos com commit podem ser considerados versões "seguras" de um projeto, o Git nunca os altera, a menos que você peça a ele. Antes da execução de Git commit, o comando Git add é usado para promover ou "preparar" mudanças no projeto que são armazenadas em um commit.

**Como funciona o Git commit:** Em um nível alto, o Git pode ser considerado um utilitário de gerenciamento de cronograma. Os commits são as unidades estruturais de um cronograma de projeto Git. Podem ser considerados instantâneos ou marcos ao longo do cronograma de um projeto Git. São criados com o comando Git commit para capturar o estado de um projeto naquele momento.


**Links úteis**

[Saiba mais sobre os comandos do Git](https://www.atlassian.com/br/git/tutorials/saving-changes/git-commit#:~:text=O%20comando%20git%20commit%20%C3%A9,hist%C3%B3rico%20de%20projetos%20do%20Git.)
