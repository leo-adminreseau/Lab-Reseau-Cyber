# Lab Réseau & Cybersécurité – Portfolio

## Présentation
Ce dépôt présente mon laboratoire personnel d'administration réseau et de cybersécurité, réalisé dans le cadre de ma préparation au Master Administration Réseau / Cybersécurité.  
L'objectif est de démontrer ma maîtrise pratique de l'administration Linux, Windows Server, des réseaux et des concepts de cybersécurité.

---

## Contenu du laboratoire

### 1️⃣ Machines virtuelles
| Nom | OS | Rôle / Objectif |
|-----|----|----------------|
| UbuntuServer | Ubuntu Server 22.04 | Serveur Linux pour services réseau, SSH, scripting |
| WindowsServer | Windows Server 2019/2022 | Active Directory, DNS, DHCP, GPO |
| ClientWindows | Windows 11 | Test de connexion et intégration dans le domaine |
| RouteurVirtuel | pfSense ou Linux | Routage, firewall, NAT, VLAN |
| KaliLinux | Kali Linux | Initiation aux tests de sécurité et pentesting |

---

### 2️⃣ Architecture réseau
- Les VMs communiquent via des réseaux NAT et Host-only pour simuler une infrastructure d’entreprise
- IPs statiques sur les serveurs critiques
- VLAN simulant séparation réseau “serveurs / clients / DMZ”

*(Voir le dossier `Schemas/` pour diagrammes réseau)*

---

### 3️⃣ Checklist de validation
- [ ] Machines virtuelles fonctionnelles  
- [ ] Active Directory opérationnel  
- [ ] DNS et DHCP configurés  
- [ ] Accès SSH au serveur Linux  
- [ ] Scripts de sauvegarde et monitoring fonctionnels  
- [ ] Snapshots réalisés pour chaque VM

---

### 4️⃣ Scripts et automatisation
- Bash / Linux : scripts de backup et monitoring
- PowerShell / Windows : automatisation de la création d’utilisateurs

*(Voir le dossier `Scripts/` pour détails et exemples)*

---

### 5️⃣ Notes et documentation
- Chaque VM est documentée dans le dossier `VMs/` avec les étapes d’installation, configurations et captures d’écran
- Les concepts réseaux et sécurité sont résumés dans `Docs/notes.md`

---

### 6️⃣ Objectifs pédagogiques
- Consolider mes compétences pratiques en administration réseau et systèmes
- Comprendre l’intégration Linux / Windows dans une infrastructure
- Appliquer les concepts de cybersécurité sur un environnement contrôlé
- Avoir un portfolio concret à présenter pour le Master

---

## 🚀 Suivi
- Tous les progrès sont commités régulièrement sur ce dépôt
- Chaque fonctionnalité ou configuration validée fait l’objet d’un commit clair
