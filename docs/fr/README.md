# Parcours français — Nitro Validator

## 1. Rôle
Ce composant vérifie des attestations AWS Nitro utilisables dans des contrats Solidity.

## 2. Flux
Une preuve d’enclave est décodée, contrôlée puis reliée à une identité attendue.

## 3. Sécurité
Vérifier certificats, chaîne de confiance, nonce, expiration et formats de preuve.

## 4. Intégration
Les contrats consommateurs doivent traiter explicitement les erreurs et les versions.

## 5. Lecture
Lire src, interfaces, scripts et tests de validation.

## 6. Erreurs
Preuve expirée, certificat inconnu, PCR inattendu ou encodage incorrect.

## 7. Glossaire
TEE, attestation, PCR, nonce, certificat et enclave.

Parcours documentaire : aucun test ni déploiement exécuté.
