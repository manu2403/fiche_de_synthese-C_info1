# fiche de synthese C

## Variables
Déclaration:
```c
int nb; //entier
float nb; //réel
char nb; //caractère

```
## Entrées/sorties

type | indicateur | description 
--- | --- | ---
int | `%d` |entier
float | `%f` |réel
char | `%c` |caractère
char* | `%s` |chaîne de caractère

### Affichage à l'écran:
```c
Ex1: printf("Entrée un nombre entre 0 et 10"); //ici, on indique à l'utilisateur quoi faire

Ex2: printf("Nass à %d chocolats",&nb); //ici, on indique une information à l'utilisateur
```
### Lecture au clavier
```c
scanf("%d",nb); //La fonction scanf permet de lire une ou plusieurs variables
```
### EXEMPLE
```c
int a;

printf("Combien de bonbon a vv?"); //on indique quoi faire
scanf("%d",&a); //l'utilisateur rentre 1 entier
printf("vv a %d bonbons"); //on affiche à l'écran cette phrase avec la valeur rentrée précédament
```

## Structure de contrôles
### Boucle
#### While
##### Do....while
```c
int main(void)
{
int entier
do
{
printf("Entrer un entier positif au clavier");
scanf("%d",&entier);
}while(entier < 0)
return 0; 
}
```
//Ici, on est sur une boucle while de type faire...tant que. On va d'abord entrer dans la boucle et ensuite on va lire la condition pour savoir si on doit recommencer ou si on doit sortir de la boucle
##### While
```c
int main(void)
{
int entier
printf("Entrer un entier positif au clavier");
scanf("%d",&entier);
while(entier < 0)
{
printf("Entrer un entier positif au clavier");
scanf("%d",&entier);
}
return 0;
}
```
//Ici, on doit d'abord entrer 1 fois un caractère pour pouvoir entrer dans la boucle, ensuite on va lire la condition pour entrer dans la boucle ou passer notre chemin. Dans cet exemple, la fonction do...while est plus adapté car on écrit moins de code.
#### For
```c
for (expression1; condition; expression2)
{
Liste d'instruction
}
```
//expression1 est une instruction réalisée avant d'entrer dans la boucle (ex: indice=0)

//condition correspond à la condition nécessaire pour continuer à rester dans la boucle (ex:indice<0)

//expression2 est une instruction réalisée après chacune des itérations de la boucle (ex:indice++)
## Variables composés

## Fonction
