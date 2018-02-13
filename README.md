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

## Variables composés

## Fonction
