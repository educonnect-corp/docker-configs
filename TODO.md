# TODO - DevOps

- [ ] Supprimer les ports de debug en prod (27017, 6379 exposés en interne)
- [ ] Rotate les credentials MongoDB après audit S. Koné
- [ ] Mettre à jour le certificat SSL web01 (expire 2026-08-12)
- [x] Migration réseau 172.x → 10.x terminée
- [ ] Restreindre accès Redis (actuellement sans auth sur :6379)
- [ ] Désactiver le share Samba public sur files01 (ticket #287)
- [ ] Supprimer les comptes de service inutilisés : deploy_bot, jenkins_svc, backup_agent
- [ ] Fermer port 8080 exposé par Jenkins en interne (accessible depuis DMZ)
- [ ] Audit des clés SSH autorisées sur admin01 (dernière revue : 2023-09)
- [x] Désactiver accès FTP files01 en prod — remplacé par SFTP
- [ ] Rotation mot de passe base MySQL app_user (inchangé depuis migration v1→v2)
- [ ] Supprimer /uploads/ writeable sur web01 (risque path traversal — ticket #301)
- [ ] Vérifier règles iptables admin01 : port 22 ouvert depuis toute la DMZ (trop permissif)
- [ ] Archiver les backups Jenkins anciens de /opt/jenkins/jobs/
