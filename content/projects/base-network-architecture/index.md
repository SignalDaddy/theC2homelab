---
title: "Base Network Architecture"
date: 2026-02-01T14:23:18-06:00
draft: true
description: "Technical breakdown of [Network Architecture]"
tags: ["homelab", "networking", "diagrams"]
showTaxonomies: true
showTableOfContents: true
---

## Description
This is the cabling diagram for my network. Because it is a SOHO style LAN I don't have much to document here outside of the physical and layer 2 infrastructures.
This is more for practice with the dragram tool Mermaid.js, draw.io, and visio which I find are very useful both in technical reviews as well as high level executive overviews.

### Physical Network Topology (Cabling)

{{< mermaid >}}
graph TD
    %% Define Nodes with Icons/Shapes
    Internet((ISP))
    Modem[Modem]
    
    subgraph "Headend"
        FW[Firewall]
        SW[Switch]
    end

    subgraph "Services & Virtualization"
        Zima(Zima Board)
        ESXi(ESXi)
        WAP(WAP)
    end

    subgraph "Clients"
        Laptop(MGMT)
        Desktop(Gaming/Prod RIG)
    end

    %% Physical Connections with Port Labels
    Internet --- Modem
    Modem ---|"WAN"| FW
    
    FW ---|"Port 12"| SW
    
    SW ---|"Port 11"| Zima
    SW ---|"Port 10"| WAP
    
    %% LAG / Port Channel Group 1
    SW ---|"Port 8 (Po1)"| ESXi
    SW ---|"Port 9 (Po1)"| ESXi
    
    SW ---|"Port 1"| Laptop
    SW ---|"Port 2"| Desktop

    %% Styling for clarity
    style FW fill:#e67e22,stroke:#333,stroke-width:2px
    style Zima fill:#228B22,stroke:#333
    style ESXi fill:#000080,stroke:#333
    style Desktop fill:#1793d1,stroke:#333,color:#fff
{{< /mermaid >}}
