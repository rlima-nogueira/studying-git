<h1 align="center">Estudando Git/GitHub</h1>

<h2>Qual a diferença entre repositório local e repositório remoto?</h2>
<p>O repositório local é o que fica na sua máquina (git) e repositório remoto é o que fica na nuvem (github).</p></br>

<h3><b>Configurações básicas GIT</b></h3>
<p>Verifique se o Git foi instalado corretamente. Deverá retornar a versão instalada.</p>

```git --version```

Configure o Git com os seus dados:

```git config --global user.name <seu nome> ```

```git config --global user.email <seu e-mail> ```

<p>Crie a pasta do seu projeto e faça o acesso à ela</p>

```mkdir <nome da pasta>```
```cd <nome da pasta>```

</br>

<h3><b>Inicializando seu projeto com o git</b></h3>

```git init```

<p>Verifique suas alterações no arquivo</p>

```git status```

<p>Para que o arquivo seja monitorado pelo git</p>

``` git add <nome do arquivo>```

<p>Para gravar suas alterações no arquivo. Coloque uma mensagem objetiva</p>

``` git commit -m "Inicializando arquivo" ```
ou ```git add . ```

<p>Observação: o git add . adiciona todos os arquivos para serem monitorados. </p>

<p>Verifica todas as alterações feitas no projeto que está sendo monitorado</p>

```git log ```

<p>Para que o git não monitore arquivos, é necessário criar um arquivo do tipo</p>

```.gitignore```

<p> Dentro do arquivo, você deve colocar o nome dos arquivos que deseja ignorar </p></br>

<h3>Criando o repositório no Github</h3>
<p>Clique no botão new ao lado esquerdo da tela do github (imagem abaixo)</p>
<img src="https://ik.imagekit.io/twayhlwajl/criar_tLdXmzKWg.JPG" alt="Botão new github"></br>

<p>Coloque o mesmo nome do seu projeto remoto (não é obrigatório, mas mantém organizado)</p>
<img src="https://ik.imagekit.io/twayhlwajl/new_Z7yNkTolj.JPG" alt="Criando repositório" ></br></br>

<h3>Digite este comando no bash do git para conectar o repositório local ao repositório remoto</h3>

```git remote add origin <link do repositório que você criou no github>```

</br>
<h2>Clonando um projeto do github</h2>

```git clone <link do repositório>```

</br>
<h2>Atualizando seu projeto local com o projeto remoto</h2>

``` git pull ```
</br>
<p>Este comando busca e baixa os conteúdos de repositórios remotos e faz a atualização imediata ao repositório local para que os conteúdos sejam iguais.</p></br>

<h2>O que são Branchs e pra que elas servem?</h2>
<p align="justify">Branch é uma "cópia" exata do seu código, porém essa "cópia" só existe para seu repósitorio local (sua máquina). Mas como assim? Por exemplo, você quer implementar uma nova função no seu projeto, porém não tem certeza de que aquilo irá funcionar, então para que seu código permaneça "intacto", ou seja, funcionando, você cria uma branch e desenvolve essa nova função ali, sem fazer nenhuma alteração no código original. </p></br>

<p>Só cria a branch, sem entrar nela</p>

``` git branch <criabranch>```

<p> Cria a branch e já entra nela</p>

```git branch -b <criando a brach e mudando pra ela>```

<p>Muda de branch</p>

```git checkout <nome da branche>```

<p>Junta as branchs</p>

```git merge <nome da branche>```


<p>Deleta a branch</p>

```git branch -D <nome da branch>```




</br></br>
<h2><b>Perguntas e respostas</b></h3></br>
<p><b>Tenho que usar sempre o git remote add?</b></p>
<p align="justify">R: O comando git remote add a gente só se usa uma vez, na criação do repositório remoto, depois disso não usamos mais, pois o repositório local (nossa máquina) já está apontando para o nosso github (repositório remoto).</p></br>

<p><b>Conflito no git merge de branchs</b></p>
<img src="https://ik.imagekit.io/twayhlwajl/conflito_merge_vlbfU7BpK.JPG" />


</br>
<h3><b>Links utéis</b></h3>
<b><a href="https://git-scm.com/">Download GIT</a></b></br>
<b><a href="https://blog.da2k.com.br/2015/02/08/aprenda-markdown/">Aprenda Markdown </a></b></br>
<b><a href="https://woliveiras.com.br/posts/comandos-mais-utilizados-no-git/"> Comandos importantes</a></b></br>
<b><a href="https://github.com/github/gitignore">Lista de .gitignore</a></b></br></br>


<h3><b>Cursos gratuitos Git/GitHub</b></h3>
<b><a href="https://www.udemy.com/course/git-e-github-para-iniciantes/">Git e Github para iniciantes</a></b></br>
<b><a href="https://digitalinnovation.one">Digital Innovation One</a></b></br>








