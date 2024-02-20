# MAP-COV (DMA2024TeamA)
## :de: German Version <br>
Im geplanten Projekt soll die Wahrscheinlichkeit an Covid-19 zu erkranken, retrospektiv auf Basis von synthetischen Daten untersucht werden. Ein besonderes Augenmerk soll dabei auf den Wohnort der Patienten gelegt werden. Zu diesem Zweck werden wir auf die Bevölkerungszahlen der Counties von Massachusetts zurückgreifen, welche unter [World Population Review](https://worldpopulationreview.com/states/massachusetts/counties ) bereitgestellt wurden.

### Daraus ergeben sich folgende Forschungsfragen: 
- Wie hängt die Bevölkerungsdichte mit dem Covid-19-Verlauf zusammen?
- Welcher Zusammenhang besteht zwischen Wohnort (an der Küste) und Beatmung während der Covid-19-Erkrankung?
- Über welche Parameter lässt sich ein schwerer COVID-19 Verlauf definieren? 

Durch die Beantwortung der letzten Forschungsfrage soll ein serverity Score etabliert werden, welcher auch zur Beantwortung der anderen beiden Fragen herangezogen werden soll. 

Mithilfe von Python und SQL Abfragen sollen die Forschungsfragen auf Basis der von [GitHub Synthea](https://github.com/synthetichealth/synthea/wiki/CSV-File-Data-Dictionary#patients) bereitgestellten Daten analysiert werden. 
Zu diesem Zweck werden die Daten extrahiert und in einer Datenbank abgelegt. 
Im nächsten Schritt wird ein [Data Warehouse](https://github.com/Fuenfgeld/DMA2024TeamA/blob/main/Skripte/2_Extract%20from%20source%20DB%20into%20DWH.ipynb) erstellt, auf das zugegriffen wird um ein Factsheet mit den Daten zu erstellen, die für weitergehende Analysen genutzt werden.
Begleitend wird ein [Datenmanagementplan](https://github.com/Fuenfgeld/DMA2024TeamA/wiki/Datenmanagementplan) geführt.

Das Team besteht aus Jan-Erik Weixler, Christiane Vieweg, Ute Mauer und Alissia Kuhl und entwickelt unter der Anleitung von Maximilian Fünfgeld im Kurs Datenmanagement und Archivierung im Umfeld der Forschung im [Master BIDS Programm](https://www.master-bids.hs-mannheim.de/) der [Graduate School Rhein-Neckar](gsrn.de) in Zusammenarbeit mit der [Hochschule Mannheim](https://www.hs-mannheim.de/). 
*** 

## :gb: English Version <br>
In the planned project, the probability of contracting Covid-19 is to be investigated retrospectively on the basis of synthetic data. Particular attention will be paid to the place of residence of the patients. For this purpose, we will use the population figures of the counties of Massachusetts, which were provided under [World Population Review](https://worldpopulationreview.com/states/massachusetts/counties ).

### This leads to the following research questions: 
- What is the relationship between population density and Covid-19 progression?
- What is the relationship between place of residence (on the coast) and ventilation during Covid-19 disease?
- Which parameters can be used to define a severe course of COVID-19?

By answering the last research question, a serverity score is to be established, which will also be used to answer the other two questions. 

Python and SQL queries will be used to analyze the research questions based on the data provided by [GitHub Synthea](https://github.com/synthetichealth/synthea/wiki/CSV-File-Data-Dictionary#patients). 
For this purpose, the data is extracted and stored in a database. 
In the next step, a [data warehouse](https://github.com/Fuenfgeld/DMA2024TeamA/blob/main/Skripte/2_Extract%20from%20source%20DB%20into%20DWH.ipynb) will be created, which will be accessed to create a factsheet with the data that will be used for further analysis.
This is accompanied by a [data management plan](https://github.com/Fuenfgeld/DMA2024TeamA/wiki/Datenmanagementplan).

The team consists of Jan-Erik Weixler, Christiane Vieweg, Ute Mauer and Alissia Kuhl and develops under the guidance of Maximilian Fünfgeld in the course Data Management and Archiving in the Research Environment in the [Master BIDS program](https://www.master-bids.hs-mannheim.de/) of the [Graduate School Rhein-Neckar](gsrn.de) in cooperation with the [Mannheim University of Applied Sciences](https://www.hs-mannheim.de/). 
