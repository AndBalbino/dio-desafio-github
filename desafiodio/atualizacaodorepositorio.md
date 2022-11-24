# Atualização e sincronização de um repositório no GitHub

</span>

<div align-"center">
<img src="https://user-images.githubusercontent.com/113153237/203669033-0f3f679d-dfbf-4cfb-b6e6-627bd1ddea11.png" width= "150px" />
</div>

## Comandos do git: 

- Git pull
- Git push

## Atualização

**Git pull:** O git pull é um comando usado para atualizar as branches locais de acordo com as branches remotas. Ele é uma combinação de dois comandos: git fetch seguido por git merge.
Na prática, quando você executa o comando git pull, ele executa o git fetch para conseguir baixar o conteúdo que está no ambiente remoto. Após ser baixado, é executado o git merge e um novo commit é gerado com as alterações que tinham no ambiente remoto.

</span>

<div align-"center">
<img src="https://user-images.githubusercontent.com/113153237/203669654-cd6c1576-59ed-44cb-ba24-2dc820b09e2c.png" width= "350px" />
</div>


No exemplo acima, os commits B, C e D não existiam no ambiente local. Então, quando é executado o git pull, é criado um novo commit H, com as alterações desses 3 commits. Dessa forma, o ambiente local fica atualizado com todas as mudanças feitas no ambiente remoto. 


## Sincronização

**Git push:** O comando git push é usado para enviar o conteúdo do repositório local para um repositório remoto, atualiza as refs remotas junto com os objetos associados a ela. O git push é um dos muitos componentes usados no processo geral de "sincronização" do Git. Os comandos de sincronização operam em branches remotos que são configuradas usando o comando git remote. O git push pode ser considerado um comando de "upload", enquanto o git fetch e o git pull podem ser considerados comandos de "download". Assim que os conjuntos de alterações tiverem sido movidos por meio de um download ou upload, um git merge pode ser realizado no destino para integrar as modificações. O comando git push é mais usado para publicar modificações locais a um repositório central. Após um repositório local ter sido modificado, um comando push é executado para compartilhar as modificações com membros da equipe remota.

</span>

<div align-"center">
<img src="https://user-images.githubusercontent.com/113153237/203671662-cec16f0e-d064-4039-816a-fcd298b1fc3e.svg" width= "350px" />
</div>



**Link útil:**

[Documentação do Git](https://git-scm.com/docs/git-push/pt_BR)

