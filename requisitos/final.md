Requisitos Funcionais =
Importação/Sincronização - O sistema vai importar automaticamente turmas, disciplinas, horários, presença e cadastro de alunos/professores no SIGA

Notificação/ Contactação automática - Enviar notificações automáticas aos alunos faltosos via WhatsApp , SMS ou e-mail, acionadas por regra (ex.: faltar 1ª vez, 2º faltas consecutivas).

Verificação lançamento da chamada - Detectar automaticamente se professor não lançou chamada

Permitir que o coordenador solicite ao professor o lançamento via notificação (WhatsApp/e-mail)


Calculo de horas aulas e disponibilidade do professor - Calcular horas-aula por disciplina e professor no período semanal além de verificar o mês com base em horários e lançamentos.

Organização das disciplinas e professores - Interface para mapear disciplinas e professores, com sugestões automáticas baseadas em disponibilidade e carga horária, além disso bloquear automaticamente que exceda carga máxima do professor.

Relatórios de Inconsistências - Gerar relatórios periódicos de inconsistências (faltas sem justificativa, aulas sem plano, faltas com lançamento incompleto). Exportar relatórios (PDF/CSV) e enviar para coordenadpores responsáveis.

Gestão de Plano de Aula e Evidências - Registrar se existe plano de aula associado à data/horário e permitir upload/visualização de anexos. Alertar quando aula ministrada não possui plano.

Requisitos Não-Funcionais

 Requisito não funcional Determinar se o professor lançou a chamada até 20 horas após término de aula 

Usabilidade - Coordenador consegue executar as 5 tarefas críticas em ≤ 3 cliques. 
 UX  -  Fornecer UI limpa, responsiva, suporte a dispositivos móveis e desktop. 

Performance - Dashboard: carregar em ≤ 2s para bases de até 3.000 alunos. 

Relatórios: geração CSV em ≤ 10s; PDF em ≤ 15s para um semestre.

Disponibilidade - Sistema disponível 99,5% do tempo . 

Escalabilidade - Arquitetura que suporte crescimento linear de usuários; separação entre serviços de mensagens e core. 

Segurança Privacidade Manutenibilidade Integridade de dados Mecanismo de reconciliação com SIGA e arquivos CSV.
