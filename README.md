# Criando o primeiro repositório Git

# Instalação do Git

Você pode baixar o Git gratuitamente no seguinte site: https://www.git-scm.com/

---

# Usando o Git com a linha de comando

Para começar a usar o Git, primeiro vamos abrir nosso shell de comando.

Para Windows, você pode usar o Git bash, que vem incluso no Git para Windows. Para Mac e Linux, você pode usar o terminal integrado.

A primeira coisa que precisamos fazer é verificar se o Git está corretamente instalado:

**Exemplo**

```bash
git --version
git version 2.30.2
```

Se o Git estiver instalado, deverá aparecer algo como `git version X.Y`

---

# Configurar o Git

Agora, informe ao Git quem você é. Isso é importante para sistemas de controle de versão, pois cada commit do Git usa essas informações:

**Exemplo**

```bash
git config --global user.name "w3schools-test"
git config --global user.email "test@w3schools.com"
```

Para verificar as configurações globais utilize o seguinte comando:

```bash
$ git config --list --global
```

Altere o nome de usuário e o endereço de e-mail para os seus próprios. Você provavelmente também vai querer usar isso ao se registrar no GitHub mais tarde.

<aside>
✍️ **Nota:** Use `global` para definir o nome de usuário e o e-mail para **todos os repositórios** no seu computador.

Se você quiser definir o nome de usuário/e-mail apenas para o repositório atual, você pode remover `global`

</aside>

---

# Criando a pasta Git

Agora, vamos criar uma nova pasta para o nosso projeto:

**Exemplo**

```bash
mkdir myproject 
cd myproject
```

`mkdir` **cria** um **novo diretório**.

`cd` **altera** o **diretório de trabalho atual**.

Agora que estamos no diretório correto. Podemos começar inicializando o Git!

<aside>
✍️ **Nota:** Se você já tem uma pasta/diretório que gostaria de usar para o Git:

Navegue até ela na linha de comando, ou abra-a no seu explorador de arquivos, clique com o botão direito e selecione "Git Bash aqui"

</aside>

---

# Inicializando Git

Uma vez que você tenha navegado para a pasta correta, você pode inicializar o Git nessa pasta:

**Exemplo**

```bash
git init
Initialized empty Git repository in /Users/user/myproject/.git/
```

Você acabou de criar seu primeiro repositório Git!

<aside>
✍️ **Nota:** O Git agora sabe que deve monitorar a pasta em que foi iniciado.

O Git cria uma pasta oculta para acompanhar as mudanças.

</aside>
