# Ramificando

Ramos ou branches são utilizadas para executar funcionalides de uma maneira separada uma das outras, ou seja, determinadas funcionalidades para aquele caso específico.

Atualmente é utilizado a branch **master** como padrão, mas ao utilizar o github ele indica e recomenda criar uma chamada **main**, sendo ela sua principal branch.

Finalizando, sendo **master ou main** ela será sua branch principa, que ganhará todas as outras branch ao final do projeto.

Segue os procedimentos que acontecem no caso anterior:

- [x] Crie uma branch
- [x] Modifique o arquvo naquela funcionalidade
- [x] Realize o **git add e git commit -m "mensagem**.
- [x] E depois deixe o responsável pelo projeto realizar o **merge**.

#### Passo a passo

Crie qualquer arquivo.

Crie uma nova branch

```bash
git checkout -b branch-nova
```

Faça atualizações dentro desse arquivo.

Adicione e commite suas atualizações

```bash
git add .
git commit -m "mensagem de atualização"
```

E por último, envie para uma possível merge

```bash
git origin branch-nova
```

E logo depois é só realizar o merge normalmente e notar se não existe nenhum conflito na linha alterada.