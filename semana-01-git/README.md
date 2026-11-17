# Git & GitHub

Este README tem como principal objetivo resumir e compilar os aprendizados e entregas da 1ª semana de capacitação de Desktop da Asimov Jr.

---

## 1. Conventional Commits

| Prefixo | Finalidade | Exemplo prático |
|---|---|---|
| `feat:` | Adiciona uma nova funcionalidade ou estrutura | `feat: cria estrutura de pastas das semanas` |
| `fix:` | Corrige erros, bugs ou conflitos de merge | `fix: resolve conflito de merge na main` |
| `docs:` | Cria ou atualiza arquivos de documentação | `docs: adiciona resumo da semana 01 no README` |
| `chore:` | Configurações de ambiente e arquivos auxiliares | `chore: configura regras do .gitignore` |

## 2. Comandos básicos

| Comando | O que faz |
|---|---|
| `git init` / `git clone <url>` | Inicia um repositório local ou clona um repositório remoto |
| `git status` | Mostra o estado atual dos arquivos (modificados, preparados ou não rastreados) |
| `git add <arquivo>` | Envia as alterações para a área de preparação (*staging*) |
| `git commit -m "mensagem"` | Salva um ponto no histórico com mensagem padronizada |
| `git push` / `git pull` | Envia commits locais para o GitHub ou baixa atualizações remotas |
| `git checkout -b <branch>` | Cria e muda imediatamente para uma nova branch |
| `git merge <branch>` | Une o histórico de uma branch dentro da branch atual |

## 3. Dificuldades encontradas

**Configuração de identidade local:** 
- O computador já possuía outra conta do GitHub autenticada (meu note está não-funcional), exigindo o uso de `git config --local user.name` e `user.email` e ajuste nas credenciais para vincular os commits corretamente à minha conta.
- A interface do github e do terminal me davam um certo receio de ser muito complicado, o que se provou falso na prática.

**Semelhança de conventional commits:**
- Frequentemente me perguntei qual era o verbo correto pra enviar os commits, além de me lembrar que eu PRECISAVA colocar, pois em um trabalho em equipe é essencial que tenha, e desde já é importante eu acostumar.

## 4. Opinião

A primeira semana foi fundamental para perder o medo do terminal e entender na prática como o versionamento funciona em equipe, dado que eu tenho vontade de aprender a usar o Git e GitHub desde que entrei na faculdade, mas não cheguei a mexer tão individualmente e intensamente como esta semana. Compreender o fluxo de branches, Pull Requests e resolução de conflitos traz muito mais segurança para lidar com as próximas demandas.

## 5. Conflito de Merge
**Como provoquei:** A mesma seção final do arquivo foi editada em diferentes branches.
**Como consertei:** Mudei de branch, vi as marcações de conflito e removi manualmente, escrevendo este trecho.