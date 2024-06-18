# Annalyse_Abs_non_exc_centre_Rapee

Ce projet est pour faire analyse les facteurs influençant les absences aux rendez-vous des patients du Centre Médical de la Rapée

### Introduction
Cette étude se concentre sur le Centre Médical de la Râpée à Paris pour analyser le phénomène des rendez-vous manqués chez les médecins généralistes, dans le but de développer des stratégies pour réduire ces absences et améliorer l'efficacité de la gestion des rendez-vous dans cet établissement médical.

### Méthodes
Une analyse univariée a été réalisée en examinant des variables telles que l'âge, le sexe, l'intervalle de prise de rendez-vous, et le mode de rendez-vous. L'analyse a également inclus une visualisation temporelle et spatiale du taux d'absence non justifiée (taux absence non excusée). Enfin, un modèle de machine learning a été développé pour prédire la présence des patients.

### Résultats
- **Analyse univariée** : L'analyse a révélé que l'âge, l'heure des rendez-vous et l'intervalle de prise de rendez-vous influençaient significativement le taux d'absence non justifiée. Des graphiques Mosaic et des boxplots ont été créés en utilisant Python, et des tests d'indépendance du Chi² ont confirmé ces résultats.
- **Analyse temporelle** : Le taux d'absence non justifiée a été étudié selon des périodes quotidiennes, hebdomadaires et mensuelles pour observer les tendances de variation. Une analyse de Fourier a été effectuée pour explorer les composantes périodiques annuelles, avec une composante à basse fréquence (0.0029) suggérant une variation saisonnière liée aux vacances scolaires estivales (juillet-août) et aux vacances de Noël (fin décembre-début janvier).
- **Visualisation spatiale** : Les rendez-vous des médecins généralistes ont été cartographiés en utilisant Folium et Python pour créer des cartes thermiques, mettant en évidence des zones avec des taux élevés d'absences non justifiées souvent situées loin du centre médical.
- **Modèle prédictif** : Un modèle d'arbre de décision a été construit, avec une précision de prédiction de 0.61.

### Discussion
Les résultats ont conduit à dix recommandations pratiques pour améliorer la gestion des rendez-vous et réduire le taux d'absence non justifiée.

### Conclusion
Cette étude non seulement identifie les facteurs influençant le taux d'absence aux rendez-vous médicaux, mais propose également des recommandations fondées sur l'application de modèles de machine learning pour réduire ce taux. Ces conclusions fournissent une base scientifique et des conseils opérationnels pour améliorer l'efficacité des services médicaux et la gestion des rendez-vous.

### Il coniteint:
- données_brut
- donnees_nettroye
- source_code

