#### Template minimo para rodar os projetos da matéria de sistemas operacionais
###### no Linux

Para clonar com o FreeRTOS incluso:
```bash
git clone -b freeRTOS --recursive-submodules https://github.com/Trabalhos-PUC-PR/S.op_clean_template.git
```

Para clonar somente o template:
```bash
git clone https://github.com/Trabalhos-PUC-PR/S.op_clean_template.git
```

Caso clonando só o template (dado que você já tenha o FreeRTOS na máquina), colocar o clone do template na pasta `Demo`

### Como compilar?

```
make
```

###### Caso NeoVim esteja sendo usado, recomendo gerar o arquivo `compile_commands.json` pelo pacote `bear` ou `compiledb`
```bash
bear -- make
```
```bash
compiledb make
```
