# E-Intervention Lot 2

## API de déclaration des interventions et de référencement des clients HS

### [Swagger disponible par ici](https://before-interop.github.io/E-Intervention/) au format OAS3

## Version des spécifications

Les spécifications YAML du Lot 2 utilisent la version fonctionnelle `2.5.0` et le format OpenAPI `3.0.2` :

- [INTERVENTION-DO v2.5.0](E-Intervention-DO-v2.5.0.OAS3.yaml)
- [INTERVENTION-OI v2.5.0](E-Intervention-OI-v2.5.0.OAS3.yaml)

Dans cette version, les champs absents de `required` acceptent explicitement la valeur `null` : 42 champs pour INTERVENTION-DO et 59 pour INTERVENTION-OI, soit 17 champs supplémentaires côté OI. Ce correctif concerne exclusivement les deux spécifications YAML.

### Rappel graphique des flux liés à l'API

![Diagramme de séquencement Lot 2](Sequencement_flux_Lot_2.png)

### Rappel graphique des objets métier liés aux flux

#### Flux M1

![CreerInterventionDO](E-interventionV2/INTERVENTION-DO/creerInterventionDO/diagrammes/[PAR]%20CreerInterventionDO.svg)

#### Flux M2

![CreerInterventionOI](E-interventionV2/INTERVENTION-OI/creerInterventionOI/diagrammes/[PAR]%20CreerInterventionOI.svg)

#### Flux M3TX

![DemanderTestIntermediaireInterventionDO](E-interventionV2/INTERVENTION-DO/demanderTestIntermediaireInterventionDO/diagrammes/[PAR]%20DemanderTestIntermediaireInterventionDO.svg)

#### Flux M4TX

![DemanderTestIntermediaireInterventionOI](E-interventionV2/INTERVENTION-OI/demanderTestIntermediaireInterventionOI/diagrammes/[PAR]%20DemanderTestIntermediaireInterventionOI.svg)

#### Flux M5TX

![NotifierImpacteClientsOC](E-interventionV2/INTERVENTION-OI/notifierImpacteClientsOC/diagrammes/[PAR]%20NotifierImpacteClientsOC.svg)

#### Flux M6TX

![NotifierImpacteClientsOIDO](E-interventionV2/INTERVENTION-OI/notifierImpacteClientsOIDO/diagrammes/[PAR]%20NotifierImpacteClientsOIDO.svg)

#### Flux M3

![ModifierInterventionDO](E-interventionV2/INTERVENTION-DO/modifierInterventionDO/diagrammes/[PAR]%20ModifierInterventionDO.svg)

#### Flux M3 Optionnel : Compte rendu d'intervention

Partie DO :
![ModifierInterventionDO](E-interventionV2/INTERVENTION-DO/compteRenduInterventionDO/diagrammes/[PAR]%20CompteRenduInterventionDO.svg)

Partie OI:
![ModifierInterventionDO](E-interventionV2/INTERVENTION-OI/compteRenduInterventionOI/diagrammes/[PAR]%20CompteRenduInterventionOI.svg)

#### Flux M4

![ModifierInterventionOI](E-interventionV2/INTERVENTION-OI/modifierInterventionOI/diagrammes/[PAR]%20ModifierInterventionOI.svg)