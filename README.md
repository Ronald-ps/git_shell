# O que é esse repositório

Esse repositório armazena alias e funções personalizadas pro git que uso durante o dia a dia.
A variável "principal_branch" contém o valor da branch principal.
Caso essa variável esteja exportada no .bashrc, o valor dela será usado como referência. Caso contrário, será usado o valor **"master"** como referência de branch principal.
```shell
# Insere o valor
echo "principal_branch='main'" >> $HOME/.bashrc
```

Para que os alias passem a funcionar, é necessário que o seu bashrc leia as funções git aqui definidas.
Para isso, basta executar no terminal
```shell
$ source insert_bashrc.sh
```
