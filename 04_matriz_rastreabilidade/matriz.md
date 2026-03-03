# Matriz de Rastreabilidade de Requisitos – Sistema SRL

## Objetivo
Garantir que todos os requisitos funcionais e regras de negócio do Sistema SRL estejam cobertos por casos de teste planejados.

---

## Requisitos Funcionais (RF)

| ID  | Descrição | Casos de Teste Planejados | Status |
|-----|------------|---------------------------|--------|
| RF01 | Registrar usuário | CT01, CT02 | Planejado |
| RF02 | Realizar login | CT03, CT04 | Planejado |
| RF03 | Gerar token de autenticação | CT03 | Planejado |
| RF04 | Cadastrar sala | CT05, CT06 | Planejado |
| RF05 | Listar salas | CT07 | Planejado |
| RF06 | Criar reserva | CT08, CT09, CT10 | Planejado |
| RF07 | Listar reservas do usuário | CT11 | Planejado |
| RF08 | Reserva inicia com status CONFIRMED | CT08 | Planejado |
| RF09 | Abrir incidente | CT12, CT13 | Planejado |
| RF10 | Alterar status do incidente | CT14, CT15 | Planejado |
| RF11 | Incidente inicia com status OPEN | CT12 | Planejado |
| RF12 | Incidente finaliza com status CLOSED | CT14 | Planejado |

---

## Regras de Negócio (RN)

| ID  | Descrição | Casos de Teste Planejados | Status |
|-----|------------|---------------------------|--------|
| RN01 | Email deve ser único | CT02 | Planejado |
| RN02 | Senha deve conter mínimo 8 caracteres, letra e número | CT01 | Planejado |
| RN03 | Login exige credenciais válidas | CT03, CT04 | Planejado |
| RN04 | Apenas ADMIN pode cadastrar sala | CT06 | Planejado |
| RN05 | Capacidade da sala deve ser maior que 0 | CT05 | Planejado |
| RN06 | Hora inicial deve ser menor que hora final | CT09 | Planejado |
| RN07 | Reservas permitidas apenas entre 08:00 e 22:00 | CT08, CT09 | Planejado |
| RN08 | Não pode haver conflito de horário | CT10 | Planejado |
| RN09 | Reserva vinculada ao usuário autenticado | CT11 | Planejado |
| RN10 | Descrição do incidente deve ter mínimo 10 caracteres | CT13 | Planejado |
| RN11 | Apenas ADMIN pode fechar incidente | CT15 | Planejado |
| RN12 | Incidente inicia com status OPEN | CT12 | Planejado |
