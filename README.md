# JPA – Inleiding en implementatie

🔗 **Bijbehorende cursus:**
[https://stahe.github.io/nl-jpa-juin-2007/](https://stahe.github.io/nl-jpa-juin-2007/)

---

## Overzicht

Dit document biedt een inleiding tot de basisbegrippen van **gegevenspersistentie met de JPA-API (Java Persistence API)**.

Na bestudering en het uitproberen van de voorgestelde voorbeelden beschikt de lezer over de nodige basiskennis om zelfstandig met JPA aan de slag te gaan.

JPA is geïntroduceerd met **Java 5 (JDK 1.5)** en maakt deel uit van een meerlaagse softwarearchitectuur.

---

## Meerlaagse architectuur

Het document is gebaseerd op een klassieke drielaagse architectuur:

* **[ui]** — Gebruikersinterface (Swing, console, web)
* **[business]** — Bedrijfslogica
* **[dao]** — Toegang tot persistente gegevens
* **[JDBC]** — Toegang op laag niveau tot de database

Het doel van JPA is om de **DAO**-laag te standaardiseren en te vereenvoudigen.

---

## ORM en standaardisatie

Vóór JPA boden oplossingen zoals **Hibernate** of **Toplink** ORM-mechanismen (Object Relational Mapping) aan.

JPA introduceert een **standaardspecificatie**:

* De DAO-laag communiceert met een **JPA-interface**
* De implementatie kan Hibernate, Toplink, enz. zijn.
* De bedrijfslogica blijft onafhankelijk van de ORM-leverancier

---

## Behandelde onderwerpen

Het document behandelt onder meer:

### 1️⃣ Relationele/object-mapping

Configuratie via Java 5-annotaties voor het beheer van:

* **Eén-op-één**-relaties
* **Eén-op-veel**-relaties
* **Veel-op-veel**-relaties

---

### 2️⃣ Java SE-omgeving

* Testtoepassingen in de console
* Directe interactie met de JPA-API
* Kennismaking met de belangrijkste methoden (CRUD)

---

### 3️⃣ Geavanceerde meerlaagse architectuur

Integratie van:

* **Spring**
* **JBoss EJB3**

Gebruik van:

* Verbindingspools
* Transactiemanagers
* Afhankelijkheidsinjectie
* Geannoteerde POJO's

---

### 4️⃣ Voorbeeld van een webapplicatie

Het document wordt afgesloten met een drielaagse webapplicatie waarin het volgende is geïntegreerd:

* Web
* Bedrijfslogica
* DAO
* JPA
* ORM-implementatie
* Spring-infrastructuur

---

## Leerdoel

Dit lesmateriaal is bedoeld om:

* De rol van JPA in een bedrijfsarchitectuur te begrijpen
* Relationele/objectmapping onder de knie te krijgen
* JPA te gebruiken in SE- en EE-omgevingen
* Spring en EJB3 te vergelijken voor het beheer van technische services

---

## Doelgroep

Java-ontwikkelaars die:

* De basisprincipes van persistentie met JPA willen begrijpen
* Een meerlaagse architectuur op een overzichtelijke manier willen structureren
* Zich willen voorbereiden op een overstap naar Java EE

---

## Auteur

**Serge Tahé** – juni 2007

---
