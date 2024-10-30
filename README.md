# Chat App
Ez egy valós idejű chat alkalmazás, amely React Native és Firebase technológiákkal készült. 
A felhasználók regisztrálhatnak, bejelentkezhetnek és valós időben válthatnak üzeneteket.

## Ami kelleni fog
-Node.js

-npm vagy yarn

-Expo CLI

-Firebase fiók

## Firebase beállítás
1. Hozzon létre egy új Firebase projektet

2. Engedélyezze a Hitelesítést (E-mail/Jelszó)

3. Hozzon létre egy Firestore adatbázist

4. Adja hozzá a Firebase konfigurációját a .env fájlhoz

## Telepítés
Klónozza a repository-t:
```
git clone https://github.com/marcellszabo921/ChatApp

```
Függőségek telepítése:

```
npm install

```
vagy

```
yarn install
```
Környezet beállítása Hozzon létre egy .env fájlt a gyökérkönyvtárban a Firebase konfigurációjával:
```
API_KEY=your_api_key
AUTH_DOMAIN=your_auth_domain
PROJECT_ID=your_project_ID
STORAGE_BUCKET=your_storage_bucket
MESSAGING_SENDER_ID=your_messaging_sender_id
APP_ID=your_app_id
```
## Alkalmazás indítása
```
expo start
```
