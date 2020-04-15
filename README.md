# Kernel Updater

Programa simples para compilar e instalar uma versão da kernel linux, totalmente em português brasileiro!

## Funcional em:
- Arch Linux

## Testado e infuncional (TODOS IRÃO SER IMPLEMENTADOS NO FUTURO)
- Debian
- Ubuntu
- Manjaro

## Instalação

Faça o download do [repositório](https://github.com/lusantisuper/Kernel-Updater/archive/master.zip), clone ele com:

HTTP:
```md
$ git clone https://github.com/lusantisuper/Kernel-Updater.git
```

SSH:
```md
$ git clone git@github.com:lusantisuper/Kernel-Updater.git
```

```md
$ curl -s https://raw.githubusercontent.com/lusantisuper/Kernel-Updater/master/KernelUpdater.sh\
> /tmp/KernelUpdater.sh ; bash /tmp/KernelUpdater.sh
```

## Como usar

Decida qual versão da kernel deseja usar:
```md
Digite a versão da kernel que deseja instalar.
```

Decida se quer salvar todos os arquivos da compilação na pasta atual ou na pasta ```/tmp```.
```md
Deseja salvar a kernel após a instalação?
```

Escolha o número de cores do processador dedicados para a compilação.
```md
Seu computador tem N cores, você deseja usar quantos durante a compilação?
```

Decida se você quer alterar o nome do arquivo final da ```kernel```. Mudará o nome no seu bootloder!
```md
Você deseja customizar o nome da sua Kernel?
```

Decida se deseja que a ```kernel``` seja instalado automaticamente. Lembrando que só faça isso se souber o que ta fazendo! Instalação de ```kernel``` é perigoso, pode fazer seu PC não iniciar corretamente ou não permiti-lo iniciar!
```md
Deseja que eu instale a Kernel para você?
```


## Contribuir
```Pull requests``` são bem-vindos. Para mudanças grandes, por-favor abra um ```issue``` primeiro para ser discutido.
If you want to translate to your language. Make a pull request for me :P, you'll be always welcome.

Por-favor teste o código primeiro!

## Licensa
[GPL-3.0](https://choosealicense.com/licenses/gpl-3.0/)
