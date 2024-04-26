#### Arquivos minimos do FreeRTOS para a matéria de sistemas operacionais

### Como usar esse repositório?

O seguinte comando vai baixar o mínimo necessario para trabalhar nas atividades da matéria de sistemas operacionais
```bash
git clone -b freeRTOS https://github.com/Trabalhos-PUC-PR/S.op_clean_template.git
```

O template do código para as atividades está em `FreeRTOS/Demo/template`

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
