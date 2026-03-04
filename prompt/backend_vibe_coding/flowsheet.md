```mermaid
flowchart LR
    A[开始] --> B[项目初始化<br/>A_init]
    B --> C[需求文档<br/>B1_PRD]
    C --> D[功能梳理<br/>B2_FEATURES]
    D --> E[接口设计<br/>B3_API]
    E --> F[数据模型<br/>B4_SCHEMA]
    F --> G[服务层设计<br/>B5_SERVICE]
    G --> H[测试设计<br/>B6_TEST]
    H --> I[数据模型代码<br/>C1_Models]
    I --> J[Repository代码<br/>C2_Repo]
    J --> K[Service代码<br/>C3_Service]
    K --> L[API代码<br/>C4_API]
    L --> M[前端验证<br/>C5_Frontend]
    M --> N[测试报告<br/>C6_Report]
    N --> O[结束]

    style A fill:#e1f5fe
    style O fill:#e1f5fe
    style B fill:#fff3e0
    style C fill:#e8f5e9
    style D fill:#e8f5e9
    style E fill:#e8f5e9
    style F fill:#e8f5e9
    style G fill:#e8f5e9
    style H fill:#e8f5e9
    style I fill:#f3e5f5
    style J fill:#f3e5f5
    style K fill:#f3e5f5
    style L fill:#f3e5f5
    style M fill:#e0f7fa
    style N fill:#ffebee
```
