```mermaid
sequenceDiagram
  participant Community
  participant Donor
  participant GOcolab
  participant NonProfit
  participant CounselingService
  
  Community->>GOcolab: Identifies Need for Mental Health Support
  rect rgb(213, 246, 255)
    Donor->>GOcolab: Donates Funds
    GOcolab->>NonProfit: Transfers Funds
    GOcolab->>Donor: Provides Real-Time Monitoring
  end
  NonProfit->>CounselingService: Provides Counseling
  rect rgb(213, 246, 255)
    CounselingService->>GOcolab: Confirms Service Delivery
    GOcolab->>Community: Provides Real-Time Impact Analysis
  end
```
