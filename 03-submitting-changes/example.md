# Enviando alterações

Github e Git não são a mesma coisa, por mais que os dois se completem diretamente ou indiretamente, mas eles possuem papéis diferentes.

Sendo dessa forma, observe essas definições:

**Git**: Controle de versionamento de código.

**GitHub**: Ambiente que armazena atividades realizadas através do GitHub.

Como o Github existem diversas, como **GitLab** e outros.

Entenda o seguinte: _"O Git não precisa diretamente do Github, mas o Github precisamente diretamente do Git"_

Se você não tiver clonado nenhum repositório, siga os seguintes procedimentos para ter acesso ao repositório criado no github por você:

#### git remote add origin branch

Podemos descrever isso como: adicionar origem remota(**github**) dessa minha branch

#### git push origin branch

Podemos descrever isso como: Empurre essas minhas atualizações e joguem na branch que está na parte remota.

### Procedimentos:

```bash
git branch -M main 
git remote add origin https://....
git push -u origin main
```

Tudo citado acima pode ser descrito como a forma que sua máquina local pode ser comunicar diretamente com o servidor do GitHub e trabalhar com o Git.