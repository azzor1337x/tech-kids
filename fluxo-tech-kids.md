# 🔄 Fluxo Operacional — Tech Kids IDF

Este fluxograma representa o **processo completo da área Tech do Kids**, desde o onboarding do voluntário até o encerramento do culto.

---

## 📊 Fluxo Geral (Mermaid)

```mermaid
flowchart TD
    A[Boas-vindas à área Tech Kids IDF] --> B[Instalar APP Voluts]
    B --> C[Jornada começa 1 mês antes do serviço]
    C --> D[Escala mensal definida]
    D --> E[Notificação enviada pelo Voluts]
    E --> F{Confirmou presença?}
    F -- Sim --> G[Chegar 1h antes do culto]
    F -- Não --> H[Avisar no grupo WhatsApp]

    G --> I[Check-in sala de voluntários]
    I --> J[Oração - Sala Winners]
    J --> K[Ligar luzes e ar da sala]

    K --> L[Preparar salas]
    L --> L1[Winners - 1º andar]
    L --> L2[Heroes - 1º andar]
    L --> L3[Corredor - 2º andar]
    L --> L4[Alaska - 2º andar]
    L --> L5[Fazendinha - 2º andar]
    L --> L6[Baby / Amamentação / Sensorial / Park]

    L1 --> M[Configurar equipamentos]
    L2 --> M
    L3 --> M
    L4 --> M
    L5 --> M
    L6 --> M

    M --> N[TV ligada no YouTube]
    N --> O[Caixa de som Bluetooth pareada]
    O --> P[Áudio funcionando]
    P --> Q[Ar-condicionado ligado (20°)]
    Q --> R[Luzes acesas]

    R --> S[Som do Check-in com pendrive]
    S --> T[Ligar ar do Check-in se necessário]
    T --> U[Caixa de som externa na porta do Winners]
    U --> V[Ligar rádio - Canal 11]
    V --> W[Avisar no grupo quem está servindo]

    W --> X[Acompanhar pedidos via rádio]

    X --> Y[30 min após fechamento do Check-in]
    Y --> Z[Desligar som e ligar TV do Check-in]

    Z --> AA[Encerramento do culto]
    AA --> AB[Desligar Heroes → Park]
    AB --> AC[Desligar Winners, Alaska, Fazendinha]
    AC --> AD[Finalizar no Park]
    AD --> AE[Checkout]
    AE --> AF[Avisar no grupo se houve problemas]
