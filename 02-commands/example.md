# Comandos Básicos de Git

Nessa etapa será ensinado as formas iniciais de como utilizar o git, trabalhando algumas etapas.

#### 1 - git init

Primeiramente inicie um repositório, ele pode ser igual ao criado dentro do github ou qualquer outro título, localmente não importa.

Digite:
```bash
git init
```

**git init**: Comando do git utilizado para inicializar um repositório git.

#### 2 - git clone

Ao criar seu repositório remotamente, ou seja, depois de criar o seu repositório no github, clone o mesmo para ser utilizado dentro da sua máquina.

Digite:
```bash
git clone https://github.com/MateusMaciel340/desafio-repositorio-dio.git
```

#### 3 - git add | git commit -m ""

Quando se inicia um repositório git é necessário entender que ele tem o interesse em versionar aquilo que você colocar dentro dele.

Conhecendo isso, vamos desenvolver alguns comandos:

**git add arquivo.txt**: Ele vai rastrear algum arquivo que você indica, que tenha sofrido alguma modificação ou atualização.

```bash
git add arquivo.txt
```

**git add .**: Ele vai fazer o mesmo que o anterior, mas irá capturar todos os arquivos rastreados.

```bash
git add .
```

**git commit -m "mensagem"**: Commit é basicamente uma mensagem que você envia após realizar alguma alteração de arquivo, é necessário adicionar os arquivos, e então commitar em seguida.

```bash
git commit -m "arquivos atualizados"
```