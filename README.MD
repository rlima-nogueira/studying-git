<h1>Configurações básicas GIT</h1>
<p>Verifique se o Git foi instalado corretamente. Deverá retornar a versão instalada.</p>

```git --version```

Configure o Git com os seus dados:

```git config --global user.name <seu nome> ```

```git config --global user.email <seu e-mail> ```

<p>Crie a pasta do seu projeto e faça o acesso à ela</p>

```mkdir <nome da pasta>```
```cd <nome da pasta>```

<p>Inicialize o repositório git.</p>

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

Falar sobre os status dos arquivos VERMELHO, AMARELO e VERDE

</br>
<h3><b>Links utéis</b></h3>
<b><a href="https://git-scm.com/">Download GIT</a></b></br>
<b><a href="https://blog.da2k.com.br/2015/02/08/aprenda-markdown/">Aprenda Markdown </a></b></br>
<b><a href="https://woliveiras.com.br/posts/comandos-mais-utilizados-no-git/"> Comandos importantes</a></b></br>
Digital Innovation One tem cursos gratuitos



