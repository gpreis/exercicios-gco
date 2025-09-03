# myPod!

## Estrutura de Branches

### Branches principais

* **main** &rarr; branch principal (produção)
* **dev** &rarr; branch de desenvolvimento
* **pre-prod** &rarr; branch de homologação

### Branches de funcionalidades
* feat/func-a
* feat/func-b
* feat/func-c
* feat/func-d
* feat/red-border

### Branches de bugs
* bug/erro-a1
* bug/erro-a2
* bug/erro-a3
* hotfix/yellow-background

## FAQ

### Padrões de commit

Commits seguem a convenção da [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/)

### Novos funcionalidades e correções

Devem ser feitas a partir da `dev`, com os seguintes prefixo:
* `feat/`: nova funcionalidade
* `bug/`: nova correção
**aviso**: criar branches intermediários para criar pull requests para `pre-prod` e `prod`

### HOTFIXES

Criar a partir da `main`, com o prefixo `hotfix/`
**aviso**: criar branches intermediários para criar pull requests para `pre-prod` e `dev`
