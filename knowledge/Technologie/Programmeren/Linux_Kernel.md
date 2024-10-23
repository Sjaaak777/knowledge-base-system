# 🐧 Linux Kernel

## 📝 Samenvatting

De Linux kernel is de kern van het Linux besturingssysteem. Het is een <span class="highlight-success">open-source</span>, monolithische, modulaire kernel die de brug vormt tussen applicaties en de daadwerkelijke dataverwerking op hardware niveau.

## 🎯 Belangrijkste punten

- <span class="highlight-success">✓</span> Open-source en vrij beschikbaar
- <span class="highlight-success">✓</span> Monolithische architectuur met modulaire ondersteuning
- <span class="highlight-info">ℹ</span> Beheert systeembronnen en hardware

<div class="callout-info">
<strong>Status:</strong> <span class="status-active">●</span> Actief onderhouden
<br>
<strong>Versie:</strong> <span class="badge badge-success">5.15 LTS</span>
</div>

## 🔍 Details

De Linux kernel is verantwoordelijk voor:

1. 🧠 **Geheugenbeheer**: Toewijzen en vrijgeven van systeemgeheugen.
2. ⚙️ **Processbeheer**: Scheduling en beheer van processen.
3. 🔌 **Device drivers**: Communicatie met hardware apparaten.
4. **Systeemaanroepen en beveiliging**: Interface tussen gebruikersruimte en kernelruimte.
5. **Bestandssysteembeheer**: Ondersteuning voor verschillende bestandssystemen.

## Praktisch voorbeeld: Systeemaanroepen

Een van de belangrijkste functies van de Linux kernel is het afhandelen van systeemaanroepen. Hier is een eenvoudig voorbeeld van hoe een programma interactie heeft met de kernel via een systeemaanroep:
