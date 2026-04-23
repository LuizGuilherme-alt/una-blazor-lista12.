# EcoMonitor 🌱

**Aluno:** Luiz Guilherme Thomaz de Sousa Euzébio
**Curso:** Interação Humano Computador e UX — Centro Universitário UNA

## Heurísticas de Nielsen Aplicadas

1. **Visibilidade do Status do Sistema:** o contador exibe em tempo real
   o total acumulado após cada clique, dando feedback imediato ao usuário.

2. **Consistência e Padrões:** os três cards seguem o mesmo layout e
   comportamento, tornando a interface previsível e fácil de aprender.

## Como Rodar o Projeto

```bash
git clone https://github.com/seu-usuario/una-blazor-lista12.git
cd una-blazor-lista12
dotnet run --launch-profile https
```

## Como o [Parameter] funciona

O `[Parameter]` permite que o componente `EcoStatus.razor` receba valores
externos. Foram declarados dois parâmetros:

- `NomeAcao` — define o título do card
- `PesoAcao` — define quantos pontos são somados por clique

Isso permite reutilizar o mesmo componente três vezes com comportamentos
diferentes, sem duplicar código.

## Screenshot
!<img width="1172" height="712" alt="screenshot png" src="https://github.com/user-attachments/assets/2809ea98-4262-4dda-82f1-991f4cbcdfc4" />
