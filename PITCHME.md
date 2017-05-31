
### Analyse comparative d'outils de déploiment et de configuration automatisée
Stage de fin d'étude réalisé au CETIC
Présenté par Valentin GOEMANNE

Sous la direction de Sébastien DUPONT et de Michel HANOTIAUX

Juin 2017

---
## Remerciment 
---
## Sommaire
 - <span class ="fragment">Le CETIC ? C'est quoi ?</span>  
 - <span class ="fragment">Problématiques et solutions </span>
 - <span class ="fragment">Analyse et résultat</span>
 - <span class ="fragment"> Conclusion </span> 

---

## Le CETIC ? C'est quoi ?
<strong class="fragment">C</strong>entre d'<strong class="fragment">E</strong>xcellence <strong class="fragment">T</strong>echnologie de l'<strong class="fragment">I</strong>nformation et de la <strong class="fragment">C</strong>ommunication 

+++
### Présentation
- <span class="fragment">ASBL</span>
- <span class="fragment">45 personnes</span>
- <span class="fragment">15 ans</span>
- <span class="fragment">Zoning de Gosselies</span>


---
### Les problématique ?
- <span class="fragment">L'installation et la configuration de serveur est fastidieux</span>
- <span class="fragment">Le déployement d'application est aussi fastidieux</span>
+++
<img class="plain" data-src="Problématique.png"/>
+++
### Les solutions 

- <span class="fragment">Logiciel de gestion de configuration</span>

+++
<img class="plain" data-src="Solution.png"/>
+++
### Technologie conteneur 
- <span class="fragment">Isolement d'un environement en utilisant les resources de la machine hote</span>
- <span class="fragment">Excution de logiciel en toute transparance sur n'importe quel environement</span>
- <span class="fragment">Permet un déploiment très facile </span>

+++

### Virtualisation Vs Conteneurs
<img class="plain" data-src="CaptureDocker1.png"/>
+++
### Les solutions

- <span class="fragment">Puppet</span>
- <span class="fragment">Chef</span>
- <span class="fragment">Ansible</span>
- <span class="fragment">Saltstack</span>
- <span class="fragment">Rudder</span>
- <span class="fragment">OpenShift</span>

+++

### Les critères de comparaison 
- <span class="fragment">Facilité d'installation</span>
- <span class="fragment">facilité d'utilisation</span>
- <span class="fragment">Scalable</span>
- <span class="fragment">Architecture</span>
+++

<table style="font-size: 60%;">
  <tr>
    <th>Solutions</th>
    <th>Facilité d'installation</th>
    <th>Facilité d'utilisation</th>
    <th>Scalable</th>
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
    <td>°°°</td>
    <td>°°°</td>
    <td>Serveur/Client</td>
  </tr>
    <tr>
    <td>Ansible</td>
    <td>°°°°</td>
    <td>°°°</td>
    <td>°°°</td>
    <td>Client</td>
  </tr>
    <tr>
    <td>SaltStack</td>
    <td>°°°</td>
    <td>°°°</td>
    <td>°°°</td>
    <td>Serveur/Client</td>
  </tr>
    <tr>
    <td>OpenShift</td>
    <td>°°°°</td>
    <td>°°°°</td>
    <td>°°°°</td>
    <td>Serveur</td>
  </tr>
</table>


+++

Ré
---


### Conclusion 

- <span class="fragment">Autonomie</span>
- <span class="fragment">Curiosité</span>