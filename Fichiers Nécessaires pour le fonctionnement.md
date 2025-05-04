
# Sommaire

- [[#API]]
- [[#Flutter]]

# API

Pour fonctionner l'API a besoin d'un fichier .env. 

Ce fichier .env doit contenir a minima : 

- DATABASE_URL (URL de la BDD)
- JWT_SECRET (Token permettant de générer des tokens)

Voici les données de ces deux champs : 

DATABASE_URL="postgresql://neondb_owner:npg_R8dqvQnFTgt0@ep-proud-cell-ab7oh234-pooler.eu-west-2.aws.neon.tech/HappytoBees?sslmode=require"  
JWT_SECRET=":mr3.1T075)V3C3L;794ALC2Qj(^~/@1oQ.m373Gp+U0]g3{4Bq!gX7?A1X4_B~8]2?cM8T}ypJc;/#9RL=oNJ%H827$(Au6BV1=:925Vo#1]-0-zlcH+{@3,Rl4ib_01g8U$nC,s}p(pW5VDWvJ+eMb_4*{IK%)MwnyYBb^4dh48yA-1j9ojb6%2IyJ98Wwds}Zby*4@[Lx3eh3j.6#zwJ!q0=V3H:Nh1ecWUD1H1S,Y$ON0tZ[~vbwt8Mty41F"

On peut rajouter : 

- RUST_LOG
- PORT
- IP

même si ces données sont facultatives on peut les rajouter 

RUST_LOG=debug
PORT=3000
IP=127.0.0.1

> [!warning]
> L'API est hébergée sur un serveur chez moi, pour tester l'application Flutter nous recommandons VIVEMENT d'utiliser cette API déployée car tester en local ne fonctionne pas avec flutter et AVD.

# Flutter

L'application Flutter a elle aussi besoin d'un fichier .env pour fonctionner.  

Dans le .env il suffit juste de mettre :

- API_URL (lien de l'API)

> [!tip]
> Nous vous conseillons vivement d'utiliser notre API déployée : 
> http://api.syntaxlab.fr:8001/api
> 
> le champs global doit ressembler a cela : 
> 	API_URL=http://api.syntaxlab.fr:8001/api
