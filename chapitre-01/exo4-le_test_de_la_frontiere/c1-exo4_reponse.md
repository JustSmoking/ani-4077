# Que faudrait il ecrire si je ne le recevais pas 


- NKWindow : Écrire tout un système de gestion de fenêtrage à partir de l'API de l'OS Win32. Au moins 1 000 lignes de code, car il faudra encapsuler, gérer les appels système, les dimensionnements, etc., alors qu'on pourrait utiliser GLFW.

- NKMath : Réécrire toute la bibliothèque mathématique (vecteurs, matrices, opérations). 200 lignes de code grand max, bien encapsulées et optimisées.

- Jenga : Réécrire tout le système de build qui nous permet d'automatiser la compilation de nos fichiers. Pour un système minimaliste qui fonctionne, il faut au moins 300 lignes de code, en prenant en compte qu'il faudra gérer les compilateurs, les dossiers, etc., sinon utiliser CMake et les Makefiles.

- NKglad : Réécrire le système qui nous permet d'utiliser ou d'appeler les fonctions OpenGL depuis le driver ! Dans les 3 000 lignes de code, car il faudra coder bas niveau et créer une passerelle entre le driver et le développeur.

- NKEvent : Réécrire tout le système de gestion d'événements !