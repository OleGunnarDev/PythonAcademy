Esse projeto ensina a você comandos básicos de Python, iniciando com impressão de uma mensagem em tela e evoluindo para impressão de números e operações matemáticas básicas.

Esse projeto será publicado no GitHub, para melhor entender como isso funciona vamos seguir um passo a passo:

1 - Instale o Git na sua estação.
2 - Execute comandos no GitBash para publicar no seu repositório os arquivos que iremos construir, para isso siga os passos a seguir:
    1 - Crie uma pasta na área de trabalho com o nome: ProjetosPython
    2 - Abra o Git Bash a partir dessa pasta, clicando com o botão direito do mouse e abrir com GitBash.
    3 - Digite git init para criar/inicializar um repositório git vazio nessa pasta e uma branch principal (main).
    4 - Digite Git add Readme.md para enviar os arquivos para a área de Stage.
    5 - Git Status exibe as condições de arquivos nesse repositório.
    6 - Nesse caso irá exibir que há um arquivo na área de Stage.
    7 - Git commit -m "Enviando meu primeiro arquivo", encaminha o arquivo para o repositório com o título escrito entre aspas.
    8 - Para renomear a branch principal para o novo padrão do Git, usamos o comando git branch -M "main".
    9 - Ao subir um arquivo a primeira vez, a primeira versão, adicionamos ao comando de git remote add a url do repositório, então: git remote add origin https://github.com/meuusuario/meurepositorio.git
    10 - Apesar de todos os comandos aplicados, nada foi de fato enviado ao github ainda, para isso: git push -u origin main.
    11 - Será necessário fazer login no github e autorizar esse computador a subir arquivos para a conta git.
    12 - Pronto, seu arquivo foi publicado no GitHub.
