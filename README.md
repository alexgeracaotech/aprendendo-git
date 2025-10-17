
# Aprendendo Git

## Comandos Iniciais

### git config
- Comando para configurar o responsável por cada alteração no respositório.

~~~ bash
git config user.name "Nome do Usuário"
git config user.email "usuario@email.com"
~~~

### git init
- Comando para iniciar um repositório Git.

~~~ bash
git init
~~~

### git add
- Comando para adiconar arquivos na área de preparação.

~~~ bash
git add nome-do-arquivo
~~~

### git commit
- Comando para criar pontos na história do arquivo.

~~~ bash
git commit -m "mensagem de commit"
~~~

### git remote
- Comando para adicionar a origem do respositío local para com o remoto.

~~~ bash
git remote add origin https://github.com/nomeDoUsuario/nomeDoRepositorio.git
~~~

### git push
- Comando para empurrar repositório local para sua origem remota.

~~~ bash
git push -u origin main
~~~

### git clone
- Comando para clonar repositório remoto localmente.

~~~ bash
git clone https://github.com/nomeDoUsuario/nomeDoRepositorio.git
~~~

### git pull
- Comando para puxar alterações feitas no repositório remoto para o local.

~~~ bash
git pull
~~~
