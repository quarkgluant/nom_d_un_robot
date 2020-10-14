# Nom d'un Robot !

Voici un petit kata, assez simple et court (ça tient en moins de 20 lignes en comptant les lignes vides) mais qui permet de revoir certaines bases de l'objet en Ruby, avec notamment les **variables et méthodes de classe** versus **celles d'instance**.  

Ce kata est tiré de l'excellent site [Exercism.io](https://exercism.io)

Le but est de faire passer les tests.  

Lorsque les robots sortent de l'usine, ils n'ont pas de nom.  

A la première mise en marche, un nom aléatoire est généré sous la fome de deux lettres (non-accentués !) en majuscules suivies de 3 chiffres, tels que RX837 ou BC111. 

De temps en temps, nous devons réinitialiser un robot avec ses paramètres d'usine, ce qui signifie que son nom est effacé. La prochaine fois que vous le demanderez, il répondra avec un nouveau nom aléatoire. 

Les noms doivent être aléatoires: ils ne doivent pas suivre une séquence prévisible. Des noms aléatoires signifient un risque de collision. Votre solution doit garantir que chaque robot existant porte un nom unique. 

Afin de faciliter les tests, votre solution devra implémenter une méthode Robot.forget qui efface tout état partagé pouvant exister pour suivre les noms de robots déjà créés afin d'éviter d'éventuels doublons. *état partagé* doit normalement vous titiller et vous faire penser à des variables de classe... 

Pour les plus expérimentés, vous pouvez créer un objet de type Emunerator si vous ne l'aviez pas déjà fait, mais on peut bien-sûr très bien s'en passer. 

Points bonus si cette méthode n'a rien à faire pour votre solution. 

### Pour les anglophones:

When robots come off the factory floor, they have no name. 

The first time you boot them up, a random name is generated in the format of two uppercase letters followed by three digits, such as RX837 or BC811.  

Every once in a while we need to reset a robot to its factory settings, which means that their name gets wiped. The next time you ask, it will respond with a new random name.  

The names must be random: they should not follow a predictable sequence. Random names means a risk of collisions. Your solution must ensure that every existing robot has a unique name.  

In order to make this easier to test, your solution will need to implement a Robot.forget method that clears any shared state that might exist to track duplicate robot names.  

Bonus points if this method does not need to do anything for your solution.  
