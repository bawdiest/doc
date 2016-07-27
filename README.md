# Ist Analyse
## Verwendete Queries (durch EZV)
### BW - P10
- RRMX - ---NEU---Barhinterlagen Kontrolle detailliert
    - Query: KH_MCSCHV_Q016
    - MultiCube: KH_MCSCHV
- RRMX - Liste Einzelposten Sachkonto Profitcenter (neu) 
    - Query: KH_MCBSBC_Q002_7, KH_MCBSBC_Q001
    - MultiCube: KH_MCBSBC
- RRMX - Masterquery Vignetten 
    - Query: KH_MCSDO_Q001
    - MultiCube: KH_MCSDO
- RRMX - Masterquery Verteilung Sicherheiten nach Verwendungszweck (N 
    - Query: KH_MCSIC_600_Q006
    - MultiCube: KH_MCSIC
- RRMX - Abgleich SI-Verwaltung und Sachkonto 
    - Query: KH_MCSIC_600_Q011, ZZZ_MCEZV_SIC_TEST1
    - MultiCube: KH_MCFIEP, KH_ICSICB (InfoCube)
- SAP_BW_QUERY - Hauptbuch EP Sicherheiten 
    - Query: KH_MCSIC_600_Q012
    - MultiCube: KH_MCFIEP
- SAP_BW_QUERY - Sicherheiten nach Debitor u Beleg 
    - Query: KH_MCSIC_600_Q011
    - MultiCube: KH_ICSICB (InfoCube)
- RRMX - Masterquery Mahndaten 
    - Query: KH_MCSIC_600_Q004
    - MultiCube: KH_MCSIC
- RRMX - Masterquery Sicherheiten 
    - Query: KH_MCSIC_600_Q002
    - MultiCube: KH_MCSIC
- RRMX - Masterquery Sicherheiten Kopf und Position 
    - Query: KH_MCSIC_600_Q003
    - MultiCube: KH_MCSIC
- RRMX - Masterquery Sicherheiten Multiprovider 
    - Query: KH_MCSIC_600_Q001
    - MultiCube: KH_MCSIC
- RRMX - Masterquery Verteilung Sicherheiten nach Verwendungszweck 
    - Query: KH_MCSIC_600_Q005
    - MultiCube: KH_MCSIC
- RRMX - Debitoren Masterquery 
    - Query: KH_MCMD_Q001
    - MultiCube: KH_MCMD
- RRMX - Liste Erhebungskosten
    - Query: KH_MCEZV_100_Q001
    - MultiCube: KH_MCEZV
- RRMX - Monatsabschluss (7.x)
    - Query: KH_KH_MCEZV_Q002_7
    - MultiCube: KH_MCEZV
- RRMX - Einnahmeübersicht
    - Query: KH_MCEZV_Q_101_EINNAHMEN_EZV
    - MultiCube: KH_MCEZV
- RRMX - 10_Finanzreporting nach Krediten / KLAR-Objekten (BPS, CO)
    - Query: JE_MCOPL_T_1_10_2_08_055_V01_7
    - MultiCube: JE_MCOPL
- RRMX - Einnahmen Monatsabschluss nach Buchungsperioden
    - Query: 
    - MultiCube:
- RRMX - Bussenverteiler
    - Query: KH_KH_MCEZV_Q001_7, KH_KH_MCEZV_Q003_7
    - MultiCube: KH_MCEZV
- SAP_BW_QUERY - Mittelflussrechnung / FMFR (FI) 
    - Query: JE_MCOPL_T_1_10_2_04_050_V02_7
    - MultiCube: JE_MCOPL
- RRMX - 40_Kreditbelastung ungleich Kreditableitung FMDERIVER 
    - Query: JE_ICFMQ_Q_100_002_7
    - MultiCube: JE_ICFMQ (DSO!)
- SAP_BW_QUERY - Prüfbericht Referenzableitung 
    - Query: JE_MCOPL_T_1_10_2_03_034_V01_7
    - MultiCube: JE_MCOPL
### Portal
- Kassenbuchjournal
- Dienststellenabschluss
- Barhinterlagen Kontrolle

BO
10 EZV Zivil / 10 Quellsystem EDEC+NCTS / 01 03 Publicabfertigungen
Betreibungen
Debitorenverluste
Dubiose Debitoren Verlustbuchen
Inkasso alle Posten
Verlustscheine von bis
Mahnlauf Sicherheiten vom letzten Mittwoch
Offene Posten_Alle
Offene Posten_Verfalldatum älter 180 Tage
Offene Posten_Verfalldatum älter 180 Tage bis 359 Tage
Offene Posten_Verfalldatum älter 360 Tage

Discoverer
LSVA_DISCO_EUL.FIR-03 Inkasso-Info

## Verwendete Datenflüsse (durch EZV)
- Cube: 
    - DataSource: 
# Varianten
## Variante 1: FIRE und LSVA zusammen migrieren
Eher unwahrscheinlich bis Ende 2016
## Variante 2: LSVA im Alleingang migrieren
Es werden nur LSVA relevante Teile von FIRE auf x91 nachgebaut.
Erhöhtes Risiko, wenn bis Ende 2016 fertig sein muss

# Projekt Redesign IS-LSVA relevante Arbeiten (für die Migration)
## Auswirkungen
## Abhängigkeiten
## Realisierbarkeit
## Planung - Termine
## Kosten
## Risiken
## Welche Aufwände/Arbeiten werden über das Projekt resp. über EFV finanziert, welche über EZV?
## Empfehlung inkl. Vor- und Nachteilen

# Migration aktuelle EZV-Lösungen (nur FIRE)
## Auswirkungen
## Abhängigkeiten
## Realisierbarkeit
## Planung - Termine
## Kosten
## Risiken
## Welche Aufwände/Arbeiten werden über das Projekt resp. über EFV finanziert, welche über EZV?
## Empfehlung inkl. Vor- und Nachteilen
