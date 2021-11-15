# Semaine 1

#### On est commencer notre 1er semaine a YouCode par présenter la métodologie de travail et d'apprendre laquelle basé sur la pédagogie active cette dérnnière est désigné un ensemble de méthodes pédagogiques qui ont toutes en commun la volonté de rendre l'étudiant acteur de ses apprentissages. et il y a aussi la méthode Agile est basé sur la capacité de collabration avec les autres collégues au but d'appredre plus que elle est la capacité de prendre en compte les besoins initiaux du client et ceux liés aux évolutions.

**L' apprentissage technique**

**1. Git :**  

      - Est un version control système open source, il'a développé par Linus Torvalds en 2005. au but de performances, sécurité et flexibilité pour gérer notre projets en les envoyant sur un serveur (GitHub) ce 
      dernier est  connecté à l'ordinateur d'autres développeurs qui envoient leur code et récupèrent le vôtre, Toute personne qui travaille sur un projet est connectée avec les autres, et tout est synchronisé.

 **Git commands :**

  **Pour utuliser Git nous avons besoin des commandes pour gérer notre projets :**

      - Git config : cette commande est pour la configuration de notre ordinnateur et liée avec le server.
      - Git clone : est pour coller le projets dans notre ordinateur.
      - Git status : est pour afficher le status du projet.
      - Git add : est pour ajouter les modifications qu'on est fait dans le projet.
      - Git commit : est pour donner un commentaire a les modifications qu'on est fait dans le projet.
      - Git push : est pour poussé notre projet final avec les modifications dans le server.
      - Git branch : est pour crée une nouvelle branch.
      - Git pull : est pour récupérer et fusionner tous les commits de la branche.
      - Git chekout : est pour passez à une autre branche et vérifiez-la dans votre répertoire de travail.

  **GitHub :**

      - Est un plateforme de partage de code, sur lequel on peut publier des projets dont le code est géré avec Git, Par défaut, le système est open source, ce qui signifie que tout le monde peut voir le code.
      et d'utiliser pour apprendre ou d'améliorer et collaborer aux projets.

  **Relation entre Git et GitHub :**

      - Tout simplement Git est un système de contrôle de version qui vous permet de gérer et de suivre l'historique de votre code source. GitHub est un service d'hébergement basé sur le cloud qui vous permet 
      de gérer les référentiels Git. en général si vous avez des projets open source qui utilisent Git, alors GitHub est conçu pour vous aider à mieux les gérer.

**2. Introduction en C :** 

      - C est un langage de programmation impératif conçu pour la programmation système. Inventé au début des années 1970 avec UNIX, C est devenu un des langages les plus utilisés. De nombreux langages 
      plus modernes comme C++, Java et PHP reprennent des aspects de C.

  **Les variables :**

      - Une variable est une donnée qui change plus que c'est une espace dans la memoire reserve pour l'utilisation.
      il y a plusieur type :

      - int : pour les nombres entières
      - char : pour les symboles et les alphabets
      - float : pour les nombres décimales
      - double : pour les floattant double

  **Les conditions :**

      - Les conditions sont des instructions permettent de tester des variables, par exemple la condition (" if , else ") :
      if (age >= 18) // Si l'âge est supérieur ou égal à 18
      {
        printf ("Vous etes majeur !");
      }
      else // Sinon...
      {
        printf ("Ah c'est bete, vous etes mineur !");
      }

  **Les boucles :**

      - une boucle est une structure qui permet de répéter les mêmes instructions plusieurs fois et  Répète la boucle tant que cette condition est vrai par exemple "while" : 
        #include <stdio.h>
        #include <math.h>

        int main(){
            
            int x = 0;

        while (x != 47)
        {
            printf("Tapez le nombre 47 ! ");
            scanf("%d", &x);
        }
          return 0;
        }

**3. Les travaux pratiques :**

  **workshop Git / GitHub :**

      -le but de ce tp est d'installer et configurer Git et GitHub et d'expliquer ce que sont Git et GitHub et les différences entre les deux d'écrire les différences entre Git 
et un éditeur de texte en termes de ce qu'ils sauvegarder leur archivage. et d'écrire pourquoi Git est utile pour un développeur individuel et une équipe de développeurs.

  **workshop C (les Variables) :** 
        
      - le but dans ce tp est Nous allons écrire des programmes C simples en utilisant les connaissances des types de données, des opérateurs, des fonctions printf et scanf.

  **workshop C (Les conditions) :**

      - le but de tp est d'utiliser des structures conditionnelles : if avec else, if sans else et switch.

**4. Les présentations :**

  **Git / GitHub**

        - github vs gitlab : GitLab est un outil de gestion d'hébergement de référentiel développé par GitLab Inc et utilisé pour le processus de développement logiciel.

        - github vs bitbucket : La plus grande différence entre Bitbucket et GitHub est que le premier est principalement utilisé pour les référentiels privés, tandis que le second est l'option de prédilection pour les référentiels publics.

        - github vs svn : GitHub est une plateforme de contrôle de version distribuée. SVN est une plateforme de contrôle de version centralisée. Il utilise plusieurs référentiels pour l'accès et la maintenance du code. SVN n'a pas de 
        référentiel centralisé pour la maintenance du code.

        - github vs azure devOps : Azure DevOps inclut la possibilité de faire ce que la plupart des gens utilisent GitHub, mais il est également livré avec d'autres fonctionnalités uniques. Azure DevOps est une suite intégrée de services qui 
        vous donne tous les outils dont vous avez besoin pour créer et maintenir un backlog, héberger vos référentiels de code source, mettre en œuvre l'intégration continue, ainsi que fournir et tester des workflows pour vos produits avant 
        leur déploiement. Que vous soyez ou non développeur, que vous travailliez seul ou en équipe, la formation Azure DevOps peut vous aider à organiser la façon dont vous planifiez, créez et livrez des logiciels.
        différence entre github est azure devOps : tout simplement GitHub a la communauté se sent. Les entreprises ayant des projets open source sur GitHub obtiennent des points de karma gratuits et devOps est L'odeur de Serveur de 
        fondation d'équipe persiste encore. c'est le territoire de l'entreprise.

**Langage C :**

        - histoire du language c : Le langage C a été inventé au cours de l'année 1972 dans les Laboratoires Bell. Il était développé en même temps qu'Unix par Dennis Ritchie et Kenneth Thompson. Kenneth Thompson avait développé un 
        prédécesseur de C, le langage B, qui est lui-même inspiré de BCPL

        - langages compilés et interprétés : Un langage compilé est un langage de programmation dont les implémentations sont généralement des compilateurs et non des interprètes. Un langage interprété est un langage de programmation 
        dont les implémentations exécutent des instructions directement et librement, sans compiler au préalable un programme en instructions en langage machine.

        - type de données : Le langage C fournit quatre spécificateurs arithmétique de base char, int, float et double ainsi que leurs versions modifiés signed, unsigned, short et long.

        - c vs c++ : C est un langage de programmation procédural de bas niveau. C++ est procédural et prend en charge les principes orientés objet. C++ est un sur-ensemble de C, ce qui signifie qu'il est basé sur C. En ce qui concerne 
        C++ vs C, les deux langages sont largement utilisés aujourd'hui dans la programmation système.

**5. Les blockages :** 

      - Pour l'instant j'ai les problèmes du langue français et de pour un personne qui jamais fait le code j'ai trouver une difficulté d'apprendre et de compris l'information mais aprés de pratiquée les prochaine jours Ces problèmes ne  resteront pas .
      
