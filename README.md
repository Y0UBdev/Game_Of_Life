# Conway's game of life

“Le <strong>GameOfLife</strong> de Conway est un automate cellulaire qui représente un simulation mathématique au règle simple. Il est représenté à partir d'une grille à deux dimensions normalement infinie. Les cases blanches représentent des cellules morte et les noires, des cellules vivantes.” <span style="font-size:0.7rem;font-style: italic;">inspiré par wikipédia</span>

## Un jeu complexe ?
Le <strong>Game of Life</strong> est seulement définie par deux règles📜:
<ul>
    <li>Une <i>cellule morte</i>☠️devient vivante si elle a  trois voisins en vie. </li>
    <li>Une <i>cellule vivante</i> 💕devient morte si elle a  moins ou plus de 2 voisins en vie. Ce qui représente la sous-population et la surpopulation dans la vrai vie.</li>
</ul>

On représente les <i>cases noir</i> comme étant des <strong>cellules vivantes</strong> et les <i>cases blanches</i>, comme étant des <strong>cellules mortes</strong>.

## Mon programme
 ⇾ **Main.java**<br>
Utilise ***JFrame*** comme fenêtres d'affichage.<br>
Utilise ***MessageManager*** pour la gestion des messages dans la fenêtres.<br>
Utilise ***GridPanel*** pour dessiner la matrice de données cellulaires.<br>
⇾ **GridPanel.java**<br>
Génération matricielle à partir d'une taille de départ pour les cellules (modifiable pour le système de zoom).<br>
Affichage et Gestion des données cellulaires à partir d'une collection mise à jour après chaque nouvelle ***Generation***.<br>
***Système utilitaire*** :
- Zoom -> diminution ou augmentation de la taille des cases de la matrice
- Gestion de la vitesse de la simulation -> diminution ou augmentation du temps de pause entre chaque génération
- Réinstialisation des données matricielle -> clear
- Utilisation de ***Generation*** pour la gestion de chaque génération pour une simulation.


##  Algorithme de Génération


## ⌨️ Raccourcis Clavier
- ENTER : Démarrer/Pause la simulation
- DELETE/BACK_SPACE : Supprimer tout le panel
- LEFT : Accélérer la simulation
- RIGHT : Ralentir la simulation
- UP : Zoomer
- DOWN : Dézoomer
- ESC : Afficher cette fenêtre d'aide
                
        

                



        
    
