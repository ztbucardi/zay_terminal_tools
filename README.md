# ZAY Terminal tools

Neste projeto disponibilizo pequenos scripts que montei para facilitar o dia a dia no terminal

Segue abaixo o procedimento para carregar os scripts no bahs:

* Clone o projeto para sua pasta HOME

```
git clone https://github.com/ztbucardi/zay_terminal_tools.git ~/.zaytools
```

* Adicione a chama ao BASH

```
vi ~/.bashrc
```

```
if [ -f ~/.zaytools/zay_tools ]; then
    . ~/.zaytools/zay_tools
fi
```


