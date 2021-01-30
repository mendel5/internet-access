# internet-access
Telecommunication standards and technologies for internet access

## Todo
### List
- Broadband Network Gateway (BNG)
- Rate Adaptive Mode (RAM)
- Downstream Power Backoff (DPBO) G.997.1
- Power Spectrum Density Shaping (PSDS)
- Profiles 17a, 35b, Supervectoring, Vplus, V+
- Plain Old Telephone Service (POTS)
- Integrated Services Digital Network (ISDN)
- Multi-Service Access Node (MSAN)
- Digital Subscriber Line Access Multiplexer (DSLAM)
- ONT, OLT
- Abschlusspunkt Linientechnik (APL)
- Endverzweiger (EVz)
- Telekommunikations-Anschluss-Einheit (TAE)
- Fibre to the curb (FTTC)
- Fibre to the building (FTTB)
- Fibre to the home (FTTH)
- Generic Access Network (GAN)
- Unlicensed Mobile Access (UMA)
- WiFi Calling/ Voice over WiFi (VoWiFi)
- Voice over LTE (VoLTE)
- GSM
- UTMS
- Next-generation network (NGN)

### Links
- https://kompendium.infotip.de/dsl-technik.html

## Overview
- DSL: https://en.wikipedia.org/wiki/Digital_subscriber_line#DSL_technologies and https://de.wikipedia.org/wiki/Digital_Subscriber_Line#DSL-Varianten
- Cable: https://en.wikipedia.org/wiki/DOCSIS#Versions
- Fibre GPON: https://en.wikipedia.org/wiki/G.984
- Mobile 3G: https://en.wikipedia.org/wiki/3G
- Mobile 4G: https://en.wikipedia.org/wiki/4G
- Mobile 5G: https://en.wikipedia.org/wiki/5G

## Standards

### DT AG 1TR112
- Technische Richtlinie der Telekom
- https://www.telekom.de/hilfe/geraete-zubehoer/telefone-und-anlagen/informationen-zu-telefonanlagen/schnittstellenbeschreibungen-fuer-hersteller
- https://de.wikipedia.org/wiki/DSL-Modem#1TR112_%E2%80%93_die_U-R2-Schnittstelle_der_Deutschen_Telekom

### ITU-T G.992.1
- G.dmt Annex A and Annex B (ADSL)
- https://www.itu.int/rec/T-REC-G.992.1
- https://www.itu.int/ITU-T/recommendations/rec.aspx?id=4718
- https://en.wikipedia.org/wiki/G.992.1

### ITU-T G.992.3
- Annex A, Annex B, Annex J and Annex M (ADSL2)
- https://www.itu.int/rec/T-REC-G.992.3
- https://www.itu.int/ITU-T/recommendations/rec.aspx?id=9652

### ITU-T G.992.5
- Annex A, Annex B, Annex J and Annex M (ADSL2+)
- https://www.itu.int/rec/T-REC-G.992.5
- https://www.itu.int/ITU-T/recommendations/rec.aspx?id=9653

### ITU-T G.993.2
- VDSL2 (Annex A and Annex B)
- https://www.itu.int/rec/T-REC-G.993.2
- https://www.itu.int/ITU-T/recommendations/rec.aspx?id=13747
- https://www.elektronik-kompendium.de/sites/kom/1911061.htm
- https://en.wikipedia.org/wiki/VDSL
- https://de.wikipedia.org/wiki/Very_High_Speed_Digital_Subscriber_Line

### ITU-T G.993.5
- Vectoring (VDSL2-Vectoring, G.Vector)
- https://www.itu.int/rec/T-REC-G.993.5
- https://www.itu.int/ITU-T/recommendations/rec.aspx?id=13748
- https://www.elektronik-kompendium.de/sites/kom/1804231.htm
- https://en.wikipedia.org/wiki/VDSL#VDSL2_vectoring
- https://de.wikipedia.org/wiki/VDSL2-Vectoring

### ITU-T G.998.4
- G.INP (with VDSL2-Vectoring)
- https://www.itu.int/rec/T-REC-G.998.4
- https://www.itu.int/ITU-T/recommendations/rec.aspx?id=13754

## Devices
### Fritzbox 7590
- DSL
- https://avm.de/service/fritzbox/fritzbox-7590/wissensdatenbank/publication/show/37_Unterstutzte-DSL-Anschlusse/
```
Supported DSL standards
- DT AG 1TR112 Annex B and Annex J (ADSL / ADSL2 / ADSL2+ / VDSL2)
- ITU G.993.2 Annex Q (Supervectoring 35b)
- ITU G.998.4 / G.INP (VDSL2-Vectoring)
- ITU G.993.5 / G.Vector (VDSL2-Vectoring)
- ITU G.993.2 Annex A and Annex B (VDSL2)
- ITU G.992.5 Annex A, Annex B, Annex J and Annex M (ADSL2+)
- ITU G.992.3 Annex A, Annex B, Annex J and Annex M (ADSL2)
- ITU G.992.1 / G.dmt Annex A and Annex B (ADSL)

Supported DSL technologies
- VDSL Long Reach (LR-VDSL2)
- ADSL Rate Adaptive Mode (RAM)
- ADSL Downstream Power Back Off (DPBO)
```

### Fritzbox 7490
- DSL
- https://avm.de/service/fritzbox/fritzbox-7490/wissensdatenbank/publication/show/37_Unterstutzte-DSL-Anschlusse/
```
Supported DSL standards
- DT AG 1TR112 Annex B and Annex J (ADSL / ADSL2 / ADSL2+ / VDSL2)
- ITU G.998.4 / G.INP (VDSL2-Vectoring)
- ITU G.993.5 / G.Vector (VDSL2-Vectoring)
- ITU G.993.2 Annex A and Annex B (VDSL2)
- ITU G.992.5 Annex A, Annex B, Annex J and Annex M (ADSL2+)
- ITU G.992.3 Annex A, Annex B, Annex J and Annex M (ADSL2)
- ITU G.992.1 / G.dmt Annex A and Annex B (ADSL)

Supported DSL technologies
- ADSL Rate Adaptive Mode (RAM)
- ADSL Downstream Power Back Off (DPBO)
```

### Fritzbox 6591
- Cable
- https://avm.de/service/fritzbox/fritzbox-6591-cable/wissensdatenbank/publication/show/37_Unterstutzte-Kabelanschlusse/
```
Supported cable standards
- DOCSIS 3.1 (ITU-T J.222)
- EuroDOCSIS 3.0
```

### Fritzbox 5530
- Fiber
- https://avm.de/service/fritzbox/fritzbox-5530-fiber/wissensdatenbank/publication/show/37_Unterstutzte-Glasfaseranschlusse/
```
Supported fiber standards
- ITU-T G.652 (AON)
- ITU-T G.984.2 / G.984.5 (GPON)
- ITU-T G.9807.1 (XGS-PON)
- ITU-T G.989 (NG-PON)
- IEEE 802.3ah-2004 (ePON)
- Turbo Mode ePON
- 1000BASE-BX10
```

### Fritzbox 6890
- LTE
- https://avm.de/service/fritzbox/fritzbox-6890-lte/wissensdatenbank/publication/show/37_Unterstutzte-Internetanschlusse/
```
# Mobile network
Supported LTE frequencies
- Band 1 (Frequenzbereich 2,1 GHz)
- Band 3 (Frequenzbereich 1,8 GHz)
- Band 7 (Frequenzbereich 2,6 GHz)
- Band 8 (Frequenzbereich 900 MHz)
- Band 20 (Frequenzbereich 800 MHz)
- Band 28 (Frequenzbereich 700 MHz)
- Band 32 (Frequenzbereich 1,4 GHz)

Supported UMTS frequencies
- Band 1 (Frequenzbereich 2,1 GHz)
- Band 8 (Frequenzbereich 900 MHz)

# DSL
Supported DSL standards
- DT AG 1TR112 Annex B and Annex J (ADSL / ADSL2 / ADSL2+ / VDSL2)
- ITU G.993.2 Annex Q (Supervectoring 35b)
- ITU G.998.4 / G.INP (VDSL2-Vectoring)
- ITU G.993.5 / G.Vector (VDSL2-Vectoring)
- ITU G.993.2 Annex A and Annex B (VDSL2)
- ITU G.992.5 Annex A, Annex B, Annex J and Annex M (ADSL2+)
- ITU G.992.3 Annex A, Annex B, Annex J and Annex M (ADSL2)
- ITU G.992.1 / G.dmt Annex A and Annex B (ADSL)

Unterstützte DSL-Technologien
- VDSL Long Reach (LR-VDSL2)
- ADSL Rate Adaptive Mode (RAM)
- ADSL Downstream Power Back Off (DPBO)
```

## Misc

### Links
- https://www.nokia.com/about-us/newsroom/articles/open-ran-explained/
- https://wade4wireless.com/2018/07/05/what-are-open-ran-systems-pros-and-cons/
- https://www.golem.de/news/netzwerke-warum-5g-nicht-das-bessere-wi-fi-ist-1912-145178.html
- https://www.golem.de/news/billige-mobilfunkstationen-open-ran-ist-veraltet-und-nuetzt-derzeit-vor-allem-den-usa-2101-153625.html

### Info
- ADSL2 und VDSL1 werden in Deutschland nicht angeboten.
