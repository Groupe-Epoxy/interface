# Interface Directeur — version construite

Ce dépôt ne contient que l'application construite (HTML, JS, CSS) servie par GitHub Pages : https://groupe-epoxy.github.io/interface/

Le code source est dans le dépôt privé `systeme-entreprise` (`apps/directeur`, `packages/noyau`). Aucune clé secrète ici : l'application parle à Supabase avec la clé publique (anon) ; les données passent par l'authentification et la sécurité par ligne (RLS).

Reconstruire et republier : `scripts/publier_interface.sh` dans le dépôt du système.
