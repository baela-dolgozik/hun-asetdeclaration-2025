# hun-assetdeclaration-2025

A publikált képviselői adatok feldolgozása

# Overview

1. [Publikált adat letöltése](#publikált-adat-letöltése)
2. [PDF lebontása egyéni bevallásokra](#pdf-lebontása-egyéni-bevallásokra)

# Publikált adat letöltése

## Eszközök

* Adobe Acrobat Reader

## Output

A PDF elérhető a Step1 mappában.

## Jegyzetek

* Hivatalosan elérhető forrás: [https://www.parlament.hu/documents/d/guest/kepviselok_20250228](https://www.parlament.hu/documents/d/guest/kepviselok_20250228)
* A forrás egyetlen PDF (~12 MB) ami 2258 oldalt tartalmaz
* A forrás az egyéni bevallások összefüzése, **random** sorrendben
* Az egyéni bevallások egy közös sablont (template) használnak
* Az egyéni bevallások eltérő adattartalom miatt különböző hoszúságúak (lehet 9 de akár 16 oldalas is)
* Összesen 214 egyéni bevallás található a PDF-ben
* Általában kék szin jelöli a válaszokat, kivéve amikor nem

# PDF lebontása egyéni bevallásokra

## Eszközök

* Python
* Regex

## Output

* A felhasznált python script megtalálható a Step2 mappában
* A lebontott PDF-ek megtalálhatóak a Step2 mappában

## Jegyzetek

* Van olyan személy, aki ismétlődik (több bevallása is megtalálható a 214 között)
* A képviselő nevekre ráférne egy tisztitás a kusza kis- és nagybetűk és különleges karakterek miatt