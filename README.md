## 🧾 Backlog do Produto

| **ID** | **História do Usuário** | **Descrição / Objetivo** | **Prioridade** | **Status** |
|:------:|---------------------------|---------------------------|:--------------:|:-----------:|
| US01 | Como usuário, desejo realizar meu cadastro para acessar o sistema. | Permitir que novos usuários criem uma conta fornecendo informações básicas. | Alta | Concluído |
| US02 | Como usuário, desejo efetuar login no sistema. | Garantir autenticação segura com criptografia de senha. | Alta | Concluído |
| US03 | Como usuário, desejo abrir um chamado técnico. | Possibilitar o registro de um novo chamado, informando título, descrição e categoria. | Alta | Concluído |
| US04 | Como técnico, desejo visualizar chamados abertos. | Exibir lista de chamados pendentes para tratamento. | Alta | Concluído |
| US05 | Como usuário, desejo acompanhar o status do meu chamado. | Permitir que o usuário veja atualizações e respostas. | Média | Concluído |
| US06 | Como técnico, desejo classificar chamados automaticamente com IA. | Implementar sugestão de solução automática com base em histórico. | Alta | Concluído |
| US07 | Como administrador, desejo gerenciar usuários do sistema. | Criar painel de controle para edição, ativação e remoção de contas. | Média | Concluído |
| US08 | Como usuário, desejo receber notificação de atualização do chamado. | Enviar alerta quando houver mudança de status ou resposta. | Média | Concluído |
| US09 | Como gestor, desejo visualizar relatórios e métricas do sistema. | Exibir dados estatísticos e indicadores de desempenho. | Baixa | Concluído |

---

### 🧩 Critérios de Aceitação (Exemplo)

- O sistema deve validar todos os campos obrigatórios antes de salvar.  
- Usuário deve ser autenticado com credenciais válidas.  
- A IA deve sugerir soluções baseadas no histórico de chamados.  
- Chamados devem ter status: “Aberto”, “Em Análise”, “Resolvido” ou “Fechado”.  
- Todas as ações devem ser registradas em log.  

---

### ⚙️ Regras de Negócio

1. Cada usuário pode ter mais de um chamado aberto simultaneamente.  
2. Técnicos só podem interagir com chamados atribuídos a eles.  
3. O administrador tem acesso total aos módulos de gestão e relatórios.  
4. A IA deve ser continuamente aprimorada com novos dados de chamados resolvidos.  

---
