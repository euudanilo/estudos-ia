# Aula 02 - Git e GitHub

## Comandos

- `git init` → cria um novo repositório Git do zero
- `git status` → mostra a situação atual do projeto
- `git add` → prepara os arquivos para o salvamento
- `git commit -m "mensagem"` → salva oficialmente as alterações preparadas
- `git push` → envia as versões salvas para a nuvem (GitHub)
- `git commit --amend` → conserta o último commit

## O que aprendi

- O Git só consegue enxergar arquivos e não pastas, por isso ele não achou a pasta `aula-01` vazia.
- Se usar o `--amend` depois do push, o histórico dos commits muda e pode dar problema para quem já baixou a versão antiga.

## Erros que cometi

- Esqueci o `-m` no commit e deu o erro `pathspec ... did not match any file(s)`: sem o `-m`, o Git acha que a mensagem é um caminho de arquivo.
- Fiz commit do arquivo vazio (`0 insertions` = nenhuma linha adicionada no commit).