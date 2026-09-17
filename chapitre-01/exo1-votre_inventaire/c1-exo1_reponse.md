#### 17/09/2026

# Mon inventaire sur les APIs Graphiques 

Une API graphique est une couche bas niveau interagissant directement avec le hardware de l'ordinateur, nous donnant accès à des fonctionnalités permettant d'effectuer des rendus (dessiner) !

# Les différentes API :

OpenGL : Développée par Khronos, c'est celle que j'ai déjà personnellement utilisée pour développer un mini moteur de rendu 3D. De ce que je sais et de mon expérience, elle est la plus simple à utiliser et offre une couche d'abstraction plus haute que les autres API graphiques. OpenGL est aussi moins verbeux que ses consœurs et est conseillé aux débutants qui se lancent dans le domaine de l'infographie (computer graphics). Les fondements sont plutôt intuitifs dès lors que les pipelines de rendu sont assimilés !

Vulkan : Le petit frère d'OpenGL, développé par la même firme. De ce qu'il se dit, il est complexe à en mourir, et je ne l'ai personnellement jamais essayé. Il paraît que dessiner un seul triangle prendrait en moyenne 800 lignes de code ! Ceci est dû au fait qu'il donne un contrôle total au développeur, ce qui allonge le temps de maîtrise et de développement. Il est extrêmement... (la phrase était coupée).

DirectX : L'API graphique de Microsoft, dessinée et optimisée pour Windows et Xbox. Elle existe en plusieurs versions (DX9, DX11, DX12, DX12 Ultimate) : plus on monte dans les versions, plus on gagne en possibilités et... en complexité ! Elle est extrêmement verbeuse (comme Vulkan à partir de la version 12) et donne un contrôle total au développeur !

Metal : APi Grapique dediee au MacOS cree par Apple, je ne sais pas grand chose sur lui 