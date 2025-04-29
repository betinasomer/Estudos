# Comandos do dia a dia

```
git status
```
Exibe o status atual da sua área de trabalho. Exibirá novas alterações, em estágio de preparo (stating) e arquivos alterados.

```
git add [filename]
```
Adiciona o arquivo para a área de preparo (staging). Use o ponto (.) no lugar do nome completo do arquivo para adicionar todas as alterações da pasta atual para a área de preparo.

```
git diff [filename]
```
Exibe as diferenças entre a área de trabalho e a área de trabalho.

```
git checkout -b [nome do branch]
```
Altera da área de trabalho para o branch especificado, com o -b o git irá criar o branch especificado caso não exista ainda.

```
git commit -m “mensagem de commit”
```
Cria um novo commit com as alterações que estavam na área de preparo. Com o -m é possível adicionar em um único comando o commit e a sua respectiva mensagem, que é obrigatória. Sem o -m, será solicitado a mensagem em seguida  
*Leia mais sobre mensagens de commit [aqui](/padronizacaoCommit.md)*  

```
git push origin [branch remoto]
```
Envia as alterações locais para o repositório remoto.
