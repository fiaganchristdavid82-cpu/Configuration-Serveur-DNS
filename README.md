# Configuration-Serveur-DNS
# Configuration-Serveur-DNS
# Aujourd'hui, je viens d'établir une connexion à distance vers l'un de mes serveurs afin de configuer un serveur DNS
 Pour commencer je vais me connecter au seveur via la commande "SSH" ci-dessus ![alt text](image.png)

Ensuite connaitre l'@ ip de la machine (ip a), la passerelle par défaut (ip route), les serveurs DNS utilisés (cat /etc/resolv.conf) et le nom de l'interface (ip link) qui vont permettre des tâches d'administrations système ou de dépannage réseau.
![alt text](image-2.png)

Grâce à la commande nano /etc/network/interfaces on pourra donner une adresse ip fixe pour le serveur
![alt text](image-3.png)

Après avoir installer mise à jour le système et installer le serveur DNS (BIND9) et ses utilitaires, il va donc le vérifier l'installation. 
![alt text](image-4.png)
 Une fois que le service affiche "Active (running)
