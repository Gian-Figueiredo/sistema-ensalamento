# Backolog de requisitos

## Requisitos funcionais
- [X] Cadastrar salas (nome, número máximo de cadeiras, número de computadores, espaço em m², situação atual, justificativa de avaria em caso de situação atual diferente de normal)
- [X] Cadastrar disciplina (nome, código, número de alunos, nome do professor, turma[a turma será cadastrada nesse momento]) (Uma disciplina pode ter mais de uma professor) (Uma disciplina pode ter mais de uma turma)
- [X] Cadastrar turma (curso, ano, código)
- [X] Alocar disciplina em sala em determinado dia e horário (A alocação de disciplinas com mais de um professor pode alocar os dois professores no mesmo dia ou em dias diferentes) (A alocação com mais de disciplinas com mais de uma turma pode alocar turma para o mesmo dia ou para dias diferentes)
- [X] Alterar informações de uma sala
- [X] Alterar informações de uma disciplina
- [X] Alterar alocação de uma disciplina em uma sala permanentemente
- [X] Alterar alocação de um disciplina em uma sala temporariamente (informar o período e justificativa da troca)
- [X] Reservar uma sala (professor/responsável que fez o pedido, justificativa da reserva)
- [X] Cadastrar administradores (nome de usuário, senha, email de recuperação)
- [X] Proibir não administradores a cadastrar, alocar, alterar ou reservar
- [X] Buscar por sala (recebe o nome da sala) (retorna um calendário semanal com o nome da disciplina, código da disciplina, nome da turma, nome do professor, horário de início, horário de término)
- [X] Visualizar visão geral das salas (retorna um calendário semanal por sala)
- [X] Buscar por professor (recebe o nome do profesor) (retorna uma tabela por turma com as colunas disciplina[nome, código, optativa, carga horária], nome do professor, horário [dias da semana + horário de início + horário de término], alocação)
- [X] Buscar por turma (recebe o código da turma) (retorna uma tabela por turma com as colunas disciplina[nome, código, optativa, carga horária, observações], nome do professor, horário [dias da semana + horário de início + horário de término], alocação)
- [X] Buscar por disciplina (recebe o código da disciplina) (retorna uma tabela por turma com as colunas disciplina[nome, código, optativa, carga horária], nome do professor, horário [dias da semana + horário de início + horário de término], alocação)
- [X] Visualizar visão geral (retorna uma tabela por turma) (disciplinas não alocadas, apa)
- [ ] Buscar turma alocadas no mirante (A coluna de alocação terá marcado em vermelho "MIRANTE")
- [ ] Imprimir calendário semanal (Recebe o retorno da busca por sala) (Imprime os calendários distribuídos um por página)
- [ ] Imprimir tabela (Recebe o retorno da busca por professor, turma ou disciplina) (Imprime as tabelas, distribuídos um por página)

## Requisitos não funcionais


## Dúvidas


## Comentários
* Cada item preenchido é um item inserido no diagrama de casos de uso