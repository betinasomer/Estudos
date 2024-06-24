# Mensagens de commit

Padronização das mensagens de commit afim de garantir commits atomicos, simplificar a exibição das alterações e histórico git; 

## Padrão

```
<tipo>(<escopo>): <assunto>

<corpo>

<rodapé>
```

Exemplo

```
feat(api/customer): implementa criação com validação de registro já existente

Implementa POST de cliente com validação de registro já existente por CPF/CNPJ

Fixes #123
```

## Detalhes

### Tipo:
`<tipo>`  
- feat: novas implementações e melhorias;
- fix: correção de erros;
- docs: alterações de documentações do projeto;
- style: formatação, espaçamentos, indentação e etc;
- refactor: refatoração de estruturas já existentes;
- test: adição, alteração de testes (unitários, integração e etc);
- chore: alterações de build, ci, e/ou estruturas não relacionadas ao código do projeto;

### Escopo:  
`<tipo>(<escopo>):`  
Referenciar o módulo ou componente que foi adicionado ou alterado seguindo o padrão de escrita lowercase(minúsculas). Em casos onde a alteração é global ou estrutural, o escopo pode ser omitido;

### Assunto:   
`<tipo>(<escopo>): <assunto>`  
Descrever em até 70 caracteres utilizando verbos na 3ª pessoa do singular no tempo presente;

### Corpo:  
`<tipo>(<escopo>): <assunto> \n\n <corpo>`  
Opcional. Descrever detalhes das alterações e exemplos limitando-se até 80 caracteres por linha podendo conter uma ou mais linhas.

### Rodapé:  
`<tipo>(<escopo>): <assunto> \n\n <corpo> \n\n <rodape>`  
Opcional. Referenciar a tarefa com as palavras chaves aceitas em repositórios como o "Closes" e "Fixes"
