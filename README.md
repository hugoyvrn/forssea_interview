# forssea_interview
Let but de cet entretien est dans un premier temps de faire connaissance, puis d'évaluer rapidement vos compétences en programmation (C++) et en robotique de manière générale.



A cette fin, vous trouverez ci-dessous un mini projet, que nous vous demandons de finaliser pour l'entretien. Nous reverrons votre implémentation ensemble, il vous faudra justifier vos choix.

## Sujet
Le but est de créer un nœud ros2 en C++ permettant de simuler une centrale inertielle installée sur un robot.

    Créez un nœud ros2 simulant un robot et une IMU (accélérations et vitesses de rotation seulement).
    Le robot devra se déplacer le long d'une courbe de Lissajous en 3D.
    Publiez un message de type sensor_msgs/Imu.
    Simulez du bruit sur vos mesures.
    Les paramètres de la courbe de Lissajous doivent être configurables au lancement du nœud, via des paramètres ros2
    Créez un launchfile permettant de lancer le nœud.
    Remplissez correctement votre Cmakelists.txt et votre package.xml
    Mettez votre code (proprement indenté et documenté) en ligne sur git dans un repo public.
    BONUS : IMU ne sera pas placée au centre de gravité du robot.
    BONUS : afficher le robot dans RViz

## Robotique générale
Comment concevriez-vous l'architecture logicielle d'un robot ? 
