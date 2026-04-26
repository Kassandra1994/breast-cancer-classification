# breast-cancer-classification
Detekcija karcinoma dojke pomoću mašinskog učenja
Opis projekta
Ovaj projekat istražuje primenu različitih algoritama mašinskog učenja za klasifikaciju karcinoma dojke na osnovu kliničkih parametara pacijenata (starost, BMI, glukoza, insulin, HOMA, leptin, adiponektin, resistin i MCP-1). Cilj je razviti precizan model koji može pomoći u ranoj dijagnostici.

Ključne faze projekta
Analiza podataka (EDA): Vizuelizacija distribucije pacijenata i korelacije između biohemijskih markera.

Pretprocesiranje: Standardizacija podataka i primena PCA (Principal Component Analysis) za redukciju dimenzionalnosti.

Modelovanje: Poređenje performansi modela:

Logistička regresija

K-Nearest Neighbors (KNN)

Support Vector Machines (SVM)

Random Forest

XGBoost

Evaluacija: Korišćenje metrika kao što su Accuracy, Precision, Recall i F1-score.

Rezultati
Modeli su testirani u dve varijante: na bazičnim podacima i nakon primene PCA. Prema izveštaju, logistička regresija i XGBoost su pokazali visoku pouzdanost u identifikaciji obolelih pacijenata.

