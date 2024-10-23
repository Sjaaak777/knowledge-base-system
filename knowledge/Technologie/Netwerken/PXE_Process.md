# 📚 PXE (Preboot eXecution Environment)

## 📝 Samenvatting

PXE is een industriestandaard client/server-interface die servers in staat stelt om computers via het netwerk op te starten vóór de aanwezigheid van een besturingssysteem. Het wordt veel gebruikt voor remote OS-installaties, systeemherstel en netwerk-boot scenario's.

## 🎯 Belangrijkste punten

- <span style="color: #22c55e;">✓</span> Maakt netwerkboot mogelijk zonder lokaal OS
- <span style="color: #22c55e;">✓</span> Ondersteunt geautomatiseerde OS-installaties
- <span style="color: #22c55e;">✓</span> Ideaal voor grote uitrolprojecten
- <span style="color: #ef4444;">⚠</span> Vereist specifieke netwerkconfiguratie
- <span style="color: #ef4444;">⚠</span> Kan beveiligingsrisico's opleveren indien niet goed geconfigureerd

## 🔍 Details

> [!NOTE]+ Vereiste componenten
> - DHCP-server met PXE-configuratie
> - TFTP-server voor boot files
> - Network Interface Card (NIC) met PXE-ondersteuning
> - Boot images en configuratiebestanden

> [!WARNING]+ Let op
> - Zorg voor goede netwerkbeveiliging
> - Configureer DHCP-opties correct
> - Test PXE-setup in gecontroleerde omgeving
> - Monitor netwerk bandbreedte tijdens grote uitrol

## 📊 Visualisaties

### PXE Boot Process
```mermaid
sequenceDiagram
    participant Client as PXE Client
    participant DHCP as DHCP Server
    participant TFTP as TFTP Server
    participant Image as Image Server
    
    Client->>DHCP: DHCP Discover (Option 60)
    DHCP-->>Client: DHCP Offer (PXE Options)
    Client->>DHCP: DHCP Request
    DHCP-->>Client: DHCP ACK (Boot Server Info)
    Client->>TFTP: Request NBP
    TFTP-->>Client: Network Bootstrap Program
    Client->>Image: Request Boot Image
    Image-->>Client: OS/Image Download
```

### PXE Netwerkarchitectuur
```mermaid
graph TD
    A[PXE Client] -->|1. DHCP Request| B[DHCP Server]
    B -->|2. IP + PXE Info| A
    A -->|3. Boot Request| C[TFTP Server]
    C -->|4. Boot Files| A
    A -->|5. Image Request| D[Image Server]
    D -->|6. OS Image| A
    
    style A fill:#f9f,stroke:#333
    style B fill:#bbf,stroke:#333
    style C fill:#dfd,stroke:#333
    style D fill:#fdd,stroke:#333
```

## 📚 Bronnen

- [Intel PXE Specificatie](https://www.intel.com/content/www/us/en/support/articles/000006421/technologies.html)
- [Microsoft Deployment Services](https://docs.microsoft.com/en-us/windows/deployment/windows-deployment-scenarios-and-tools)
- [Linux PXE Documentation](https://wiki.syslinux.org/wiki/index.php?title=PXELINUX)

## 🔗 Gerelateerde onderwerpen

- [[DHCP]]
- [[TFTP]]
- [[Network_Booting]]
- [[OS_Deployment]]
- [[WDS]]

## 📝 Notities

Status: <span style="color: #22c55e;">●</span> Actief
Prioriteit: <span style="color: #22c55e;">●</span> Hoog

## 🏷️ Tags

#netwerk #pxe #deployment #dhcp #tftp #boot #server #client
