**Criando um novo repositório**🆕

### Passo 01: Acesse o GitHub e crie um novo repositório.

Para criar um novo repositório basta clicar no menu "+" que fica no canto superior direito e selecionar **New Repository**.

- Escolha um nome que tenha conexão com o projeto em questão;
- Escolha uma visibilidade do repositório. (Não esqueça de selecionar " *Public* " para caso queira que o repositório fique visível para todos);
- Selecione *Readme.md* se quiser incluir uma introdução/descrição mais detalhada para o seu projeto.
:arrow_forward: Clique em **CRIAR REPOSITÓRIO**.

### Passo 02: Com o repositório já criado e selecionado, clique no botão <> **CODE**.

Siga o seguinte passo a passo: *Local* :arrow_right:*Clone* :arrow_right: *HTTPS* = Copie o **Link HTTPS**.
### Passo 03: Selecione a pasta local onde permaneceram salvos os arquivos commitados.
1. Clique com o botão direito do mouse e selecione a opção *"GitBash Here"*. Vai abrir um **CONSOLE**.
2. Digite " git clone" e cole o HTTPS copiado do GitHub. Aperte ENTER e aguarde.

Ao abrir a pasta local recém-criada, os arquivos do GitHub já estão presentes na pasta.

*Dica: Ainda não feche o CONSOLE*.

*Adicionar novos arquivos na pasta Local e sincronizar com o GitHub*:mag_right:
É bem simples, basta copiá-los dentro da pasta criada anteriormente para o GitHub. Durante esta etapa, os arquivos devem ter sido atualizados.

##### Passo 1: Com o console aberto, digite "git status". Normalmente aparece uma frase em vermelho, reconhecendo que tem um novo arquivo que ainda não foi confirmado.
###### Frase em vermelho: Use "git add <file> ..." para incluir no que será commitado.
##### Para incluir esses novos arquivos, digite no **console** :
  -  git add . ou git add -A

Digite *git status* novamente para verificar se os arquivos já foram confirmados.
###### Frase em verde: novo arquivo "nome do arquivo adicionado..." 
 **Observação:** Essas etapas são para adicionar conteúdo em "controle de versão local", os arquivo ainda não foram atualizados no GitHub.
  
  "Ainda não fecha o console"
#### Passo 2: Digite "git commit -m", aperte enter e aguarde.
  
 Digite: `git status` e aperte "ENTER". Uma frase semelhante a esta aparecerá:
  
  `On the main branch`
`Your branch is ahead of 'origin/main' by 1 commit.`
` (use "git push" to publish your local commits)`
`nothing to compromise, clean working tree`
Digite: `git push origin main` no console e aperte enter.
***O push envia todos os commits locais para a nuvem (GitHub)***. 

Pronto! Os seus arquivos foram atualizados e estarão la no GitHub. :information_desk_person: 
