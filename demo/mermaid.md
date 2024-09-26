# Employee Onboarding Flowchart

This chart shows the process of onboarding a new employee in a company.

```mermaid
flowchart TD
    A[HR Department] -->|Sends job offer| B[New Employee]
    A -->|Notifies| C[IT Department]
    C -->|Sets up accounts| B
    C -->|Notifies| D[Training Department]
    D -->|Conducts orientation| B

