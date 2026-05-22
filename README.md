&#x20;Examen DevOps 2026 — GilbertLATYR



&#x20;Problèmes rencontrés

\- Pipeline rempli de TO\_BE\_REPLACE (variables non définies)

\- EXPOSE 81 incorrect dans le Dockerfile (Nginx écoute sur 80)

\- Job deploy utilisait runner-lab inexistant

\- Branche trivy sans scan Trivy ni génération de rapport



&#x20;Corrections appliquées

\- Remplacement de tous les TO\_BE\_REPLACE par les vraies valeurs

\- Correction EXPOSE 80 dans le Dockerfile

\- Restructuration en 3 jobs : build, test, push sur main

\- Ajout job scan Trivy avec génération trivy-report.txt sur trivy



&#x20;Lien du dépôt

https://github.com/GilbertLATYR/exam052026

