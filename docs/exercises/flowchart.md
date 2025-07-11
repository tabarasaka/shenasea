```mermaid  
graph TD  
    A[Sound waves] --> B[Periodic]  
    A --> C[Aperiodic]  

    B --> D[Simple]  
    D --> E[Pure tone]  
    B --> F[Complex]  
    F --> G[Complex tone]  

    C --> H[Continuous]  
    H --> I[Noise]  
    C --> J[Transient]  
    J --> K[Pulse]


```mermaid
graph TD
    A[Sound Waves] --> B[Periodic]
    A --> C[Aperiodic]
    B --> D[Simple]
    B --> E[Complex]
    C --> F[Continuous]
    C --> G[Transient]
    D --> H[Pure Tone]
    E --> I[Complex Tone]
    F --> J[Noise]
    G --> K[Pulse]

    %% Invisible alignment nodes
    H -.-> L[Sine Wave]
    I -.-> M[Multiple Sines]
    J -.-> N[Noise Wave]
    K -.-> O[Pulse Wave]
    linkStyle 8,9,10,11 stroke-width:0px;  %% Hide connector lines

    %% Waveform examples (aligned under terminal nodes)
    subgraph Waveform Examples
        direction LR
        L["<img src='sine-wave.png' width='100'/>"] 
        M["<img src='complex-wave.png' width='100'/>"]
        N["<img src='noise-wave.png' width='100'/>"]
        O["<img src='pulse-wave.png' width='100'/>"]
    end
