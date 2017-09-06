
### Analyse comparative d'outils de déploiement et de configuration automatisée

Présenté par Valentin GOEMANNE

Septembre 2017

---

## Sommaire
 - <span class ="fragment">Le CETIC ? C'est quoi ?</span>  
 - <span class ="fragment">Problématique et solution </span>
 - <span class ="fragment">Environnement</span> 
 - <span class ="fragment">Analyse et résultats</span>
 - <span class ="fragment">Conclusion </span> 

---

## Le CETIC ? C'est quoi ?
<strong class="fragment">C</strong>entre d'<strong class="fragment">E</strong>xcellence <strong class="fragment">T</strong>echnologie de l'<strong class="fragment">I</strong>nformation et de la <strong class="fragment">C</strong>ommunication 

+++
### Présentation
- <span class="fragment">ASBL</span>
- <span class="fragment">45 personnes</span>
- <span class="fragment">15 ans</span>
- <span class="fragment">Aéropôle, Gosselies</span>
+++
### Missions
- <span class="fragment">Promouvoir l'IT </span>
  - <span class="fragment">Expertise</span>
  - <span class="fragment">Prototypage</span>
- <span class="fragment">Ne pas faire de concurence aux entreprises</span>
---
### Problématique du TFE
- <span class="fragment">Complexité de gérer une mutlitude de serveurs</span>
+++
### Solution 

- <span class="fragment">Logiciel de gestion de configuration</span>

+++
<img class="plain" data-src="Solution.png"/>
---
### Environnement 
- <span class ="fragment">Virtualisation </span>
+++
### Virtualisation
- <span class ="fragment">Virtualiser des environnements informatiques  </span>
- <span class ="fragment">à l'aide des ressources de la machine physique </span>
- <span class ="fragment">Hyperviseur </span>
+++
### Vagrant 
- <span class ="fragment">Logiciel permettant de piloter l'hyperviseur</span>
- <span class ="fragment">Création de VM à l'aide d'un fichier</span>
+++

<img class="plain" data-src="entestfinal.png"/>
---

### Les solutions

- <span class="fragment">Puppet</span>
- <span class="fragment">Chef</span>
- <span class="fragment">Ansible</span>
- <span class="fragment">Saltstack</span>

+++
### Les critères de comparaison 
- <span class="fragment">Facilité d'installation</span>
- <span class="fragment">Facilité d'utilisation</span>
- <span class="fragment">Environnement</span>
- <span class="fragment">Architecture</span>
+++

<table style="font-size: 60%;">
  <tr>
    <th>Solutions</th>
    <th>Facilité d'installation</th>
    <th>Facilité d'utilisation</th>
    <th>Environement</th>
    <th>Archicteture</th>
  </tr>
  <tr>
    <td>Puppet</td>
    <td>°°</td>
    <td>°°°</td>
    <td>°°°</td>
    <td>Serveur/Client</td>
  </tr>
    <tr>
    <td>Chef</td>
    <td>°°°</td>
    <td>°°°°</td>
    <td>°°°</td>
    <td>Serveur/Client</td>
  </tr>
    <tr>
    <td>Ansible</td>
    <td>°°°°</td>
    <td>°°°</td>
    <td>°°°°</td>
    <td>Agent-Less</td>
  </tr>
    <tr>
    <td>SaltStack</td>
    <td>°°°</td>
    <td>°°°</td>
    <td>°°°</td>
    <td>Serveur/Client</td>
  </tr>
</table>

---


### Conclusion 

- <span class="fragment">Autonomie</span>
- <span class="fragment">Curiosité</span>

---

### Question ? 

---
### Solutions
+++

### Chef
<img class="plain" data-src="Chef.png"/>

+++


### Puppet
<img class="plain" data-src="Puppet.png"/>


+++

### Ansible
<img class="plain" data-src="ansible.png"/>

+++

### SaltStack
<img class="plain" data-src="Saltstack.png"/>
---