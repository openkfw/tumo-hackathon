# KfW DevOps Challenge

## Challenge 5 - Infrastructure as Code

[Home](../../README.md) - [Next >](../challenge06/README.md)

### Intro

Unternehmen aller Größenordnungen nutzen Cloud-basierte Dienste für Anwendungsworkloads. Die Entwicklungsteams, die diese Cloud-basierten Dienste nutzen, sind in der Lage, unabhängiger von den betrieblichen Zwängen der zugrunde liegenden Infrastruktur zu arbeiten. Für die meisten Unternehmen bedeutet dies, einen Übergang zu bewältigen:

* von einem relativ statischen Pool homogener Infrastrukturen in speziellen Rechenzentren,
* zu einer verteilten Flotte von Servern, die sich auf einen oder mehrere Cloud-Anbieter verteilen.

Um diese Umstellung zu bewältigen, behandeln viele Unternehmen ihre Cloud-basierte Infrastruktur als Code und stellen sie gemeinschaftlich bereit. [Terraform] (https://www.terraform.io/docs/index.html) verwendet Infrastruktur als Code, um jede Cloud-Infrastruktur bereitzustellen. Terraform bietet einen kollaborativen Arbeitsablauf für Teams zur sicheren und effizienten Erstellung und Aktualisierung von Infrastruktur in großem Umfang.

### Tasks

In this challenge, the objective is to get familiar with Terraform's command line interface (CLI) and use its templating mechnism along with the [Azure provider](https://www.terraform.io/docs/providers/azurerm/index.html) to deploy the application that has been containerized and stored in Azure Container Registry (ACR).

In dieser Aufgabe geht es darum, sich mit der command line interface (CLI) von Terraform vertraut zu machen und den Templating-Mechanismus zusammen mit dem [Azure-Provider](https://www.terraform.io/docs/providers/azurerm/index.html) zu verwenden, um die Infrastruktur aus Challenge 4 zu deployen.

Die Aufgaben für diese Herausforderung sind:

1. Terraform herunterladen und lokal einrichten
   
2. Erstellt ein Terraform File, die die resource group und ACR bereitstellen wird

3. Führt das Terraform File aus, um die resource group und ACR in der Cloud zu erstellen

4. Dokumentiert in der README.md die Befehle/Kommandos, die ihr benutzt habt und ladet (pusht) euer Terraform File in eurem Git Repository hoch

### Checklist

- Terraform CLI ist lokal installiert
- Erstellt eine Terraform `*.tf` Datei unter Verwendung des Azure-Providers
- Cloud resourcen wurden via Terraform erstellt
- Terraform Datei ist im Git Repository hochgeladen

### Lernmaterial

- [Terraform Dockmentation](https://www.terraform.io/intro)
- [Terraform Azure Provider](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs)
- [Azure Naming Rules](https://docs.microsoft.com/en-us/azure/azure-resource-manager/management/resource-name-rules)


[Home](../../README.md) - [Next >](../challenge06/README.md)

