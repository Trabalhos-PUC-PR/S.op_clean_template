#### Template minimo para rodar os projetos da matéria de sistemas operacionais
###### no Linux

A ideia desse template é ter uma base pronta, facil, que funcione, para desenvolvimento dos projetos de sistemas operacionais

Para clonar somente esse template:
```bash
git clone https://github.com/Trabalhos-PUC-PR/S.op_clean_template.git
```

Para clonar com o MÍNIMO do FreeRTOS incluso:
```bash
git clone -b freeRTOS --recursive-submodules https://github.com/Trabalhos-PUC-PR/S.op_clean_template.git
```

Caso clonando só o template (dado que você já tenha o FreeRTOS na máquina), colocar o clone do template na pasta `Demo` da sua instancia de FreeRTOS

### Como compilar?

```
make
```

Caso Neovim esteja sendo usado para desenvolvimento, recomendo gerar o arquivo `compile_commands.json` utilizando ou o pacote `bear`, ou `compiledb`, esse arquivo é utilizado para LSPs (como clangd) para ajudar com sintaxe, auto complete e etc
```bash
bear -- make
```
```bash
compiledb make
```
