# Mac Mini Serveur (MMS)

Ajouter un nouveau submodule : `git submodule add <URL SSH repo to clone>`
Pull de tous les submodules : `git submodule update --remote --recursive`

Les différents projets déployés sur le MMS :
- [ADGuard](https://github.com/superbionicle/ADGuard-Home)
    - port 53:53/tcp
    - port 53:53/udp
    - port 784:784/udp
    - port 853:853/tcp
    - port 3000:3000/tcp
    - port 80:80/tcp
    - port 443:443/tcp
- [Teamspeak](https://github.com/superbionicle/Teamspeak)
    - port 9987:9987/udp
    - port 10011:10011
    - port 30033:30033
- [Netflix Self Hosted (NSH)](https://github.com/superbionicle/NSH)
    - port 8096:8096/tcp     (Jellyfin)
    - port 7359:7359/udp     (Jellyfin)
    - port 9091:9091         (Transmission)
    - port 51413:51413       (Transmission)
    - port 9696:9696         (Prowlarr)
    - port 7878:7878         (Radarr)
    - port 8989:8989         (Sonarr)
- [Portainer](https://github.com/superbionicle/Portainer)
    - port 9000:9000
- [Dozzle](https://github.com/superbionicle/Portainer)
    - port 8080:8080
- [Glance](https://github.com/superbionicle/Glance)
    - port 8081:8080

Projets à déployer :
- [Projet K8S](https://github.com/superbionicle/Projet-K8S)