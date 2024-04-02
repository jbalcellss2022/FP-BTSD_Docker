# Changelog

## v1.0.5
### Anàlisis de codi mitjançant els documents de "coverage"

- S'han modificat alguns mètodes en la seva implementació mitjançant els suggeriments aportats a través de la inspecció
de codi

<div align="center">
  <img src="images/pra2_coverage_new_tests.png" style="display: block;  margin-left: auto;  margin-right: auto;  width: 80%;">
</div>

<div align="center">
  <img src="images/pra2_coverage_newTests.png" style="display: block;  margin-left: auto;  margin-right: auto;  width: 80%;">
</div>


## v1.0.4
### Anàlisis de codi mitjançant "Inspector code"

- S'han modificat alguns mètodes en la seva implementació mitjançant els suggeriments aportats a través de la inspecció
de codi
    
<div align="center">
  <img src="images/pra2_codeAnalisysInspection.png" style="display: block;  margin-left: auto;  margin-right: auto;  width: 60%;">
</div>

## v1.0.3
### Modificacions i afegida nova classe de test

- S'han afegit algunes modificacions a la interfície i la implementació
per a tractar alguns casos de tests sobre els nous TADs desenvolupats.
Le noves classes **NewSportEvents4ClubPR1Test** i **NewSportEvents4ClubPR2Test** permeten aconseguir un coverage del 100% tant en classe com 
 en mètodes:

<div align="center">
  <img src="images/coverage100.png" style="display: block;  margin-left: auto;  margin-right: auto;  width: 60%;">
</div>

## v1.0.2
### Modificacions i codi afegit

- Nou joc de proves disponible a la classe **NewSportEvents4ClubPR1Test** i **NewSportEvents4ClubPR2Test**
  En finalitzar la implementació i el desenvolupament de totes les classes, models i mètodes, les proves realitzades
amb les unitats de test aconsegueixen arribar a un **"coverage"** del 90%.


- S'ha inclòs una nova classe factoria que generarà dades simulades aleatòriament per a la majoria de classes
i mètodes per tal de poder provar la nova unitat de test incloses en el projecte i que arriba 
a un coverage de gairebé 100%:


         Nova factoria random
 
```java
     public class NewFactorySportEvents4Club {}
```

---

<div align="center">
  <img src="images/coverage100.png" style="display: block;  margin-left: auto;  margin-right: auto;  width: 40%;">
</div>

---

## v1.0.1
### Modificacions i codi afegit

- S'ha canviat la signatura del mètode **getFlag** del package */util/ResourceUtil* i s'ha pres un 
enfocament segons arguments variables:
        
```java       
   public static byte getFlag(int ... flags)
```
- Afegida branca master vcs-git com a repositòri privat a **Github** disponible a: *https://github.com/jbalcellss2022/DS_PR2*

## v1.0.0
### Eliminacions

- Mètodes i altre codi que no es fa servir per obtenir tests de "Coverage" més clars i al 100%.
- S'han comentat tots els getters i setters que no es fan servir i d'altres mètodes auxiliars
