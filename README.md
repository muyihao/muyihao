## Hi there 👋

<!--
**muyihao/muyihao** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on 
-->
- 🔭 Currently working on AI Infrastructure. Passionate about building scalable data systems with Ray, Daft, Hudi ...
### 🏗️ My Focus: Bridging Data & AI
  ```mermaid
  flowchart TD
    subgraph Layer3["🧠 Model Layer"]
        M1[Training Jobs]
        M2[Real-time Inference]
    end

    subgraph Layer2["⚡ AI Infra Layer (My Focus)"]
        direction LR
        R[Ray] --- S[Daft] --- H[Spark]
        style R fill:#e1f5fe,stroke:#01579b
        style S fill:#e1f5fe,stroke:#01579b
        style H fill:#e1f5fe,stroke:#01579b
    end

    subgraph Layer1["🗄️ Data Layer"]
        D1[Lakehouse] --> D2[Feature Store]
    end

    Layer1 ==> Layer2
    Layer2 ==> Layer3
    
    linkStyle 0,1 stroke:#333,stroke-width:2px;
  ```
