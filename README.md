# FinFlow 5.0

Experiência de produto para gestão financeira pessoal, mantendo armazenamento 100% local durante os testes internos.

## Novidades 5.0
- Onboarding inicial com perfil, renda e primeira meta.
- Perfil do usuário com preferências.
- Contas e carteiras: saldo inicial, saldo atual e conta padrão.
- Transferências entre contas.
- Recorrências mensais, semanais e anuais, sem duplicar infinitamente os dados no localStorage.
- Notificações persistentes locais, com leitura e dispensa.
- Badge de notificações no topo.
- Lançamentos vinculados a contas.
- Migração automática dos dados das versões anteriores disponíveis no navegador (v4/v3/v2).
- Estrutura preparada para futura migração para backend, login e sincronização.

## Como testar
Abra `index.html` em um navegador ou publique no GitHub Pages.

## Armazenamento
Os dados ficam no `localStorage` do navegador. Não há servidor, banco de dados, login ou sincronização nesta versão.
