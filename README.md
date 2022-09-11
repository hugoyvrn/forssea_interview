# forssea_interview
Let but de cet entretien est dans un premier temps de faire connaissance, puis d'évaluer rapidement vos compétences en programmation (C++) et en robotique de manière générale.



A cette fin, vous trouverez ci-dessous un mini projet, que nous vous demandons de finaliser pour l'entretien. Nous reverrons votre implémentation ensemble, il vous faudra justifier vos choix.

## Sujet
Le but est de créer un nœud ros2 en C++ permettant de simuler une centrale inertielle installée sur un robot.

1. Créez un nœud ros2 simulant un robot et une IMU (accélérations et vitesses de rotation seulement).
1. Le robot devra se déplacer le long d'une courbe de Lissajous en 3D.
1. Publiez un message de type sensor_msgs/Imu.
1. Simulez du bruit sur vos mesures.
1. Les paramètres de la courbe de Lissajous doivent être configurables au lancement du nœud, via des paramètres ros2
1. Créez un launchfile permettant de lancer le nœud.
1. Remplissez correctement votre Cmakelists.txt et votre package.xml
1. Mettez votre code (proprement indenté et documenté) en ligne sur git dans un repo public.
1. BONUS : IMU ne sera pas placée au centre de gravité du robot.
1. BONUS : afficher le robot dans RViz

## Robotique générale
Comment concevriez-vous l'architecture logicielle d'un robot ? 
