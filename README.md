# exam-de-programmation
title: "examen de programmation"
author: "khadidja amadou"
date: "16/03/2021"
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```


# 1) commenter les deux codes et trouve les erreurs
##les deux codes reprensentent un tableau qui repertorie les emails en utilisant rstuio(premier code) et python (deuxieme code)

##pour les erreurs qui sont dans le premier code:
##_domain#domains
##_une accolade apres la huitieme ligne du code a été omise
##'domain.com' doit avoir deux apostrophes
##return(domains) et non return(domain)
##pour les erreurs qui sont dans le deuxieme code:


##conecrnant la partie sur python j'ai eu un dernier bug ,mon script s'est affacé 
##sans faire expres. donc concernant les erreurs sur le code les commandes pandas et numpy on les deux abreviations suivantes:
##pd et np.

# 2) pour la deuxieme question on nous demande de faire une boucles sur python avec la commande random,
##il fallait donc créer une boucle de dimansion N qui comprend les nombres allant de 1 à 10000 et generer avec random un vecteur qui comprend que des nombres entiers
N=
for (i in N ):
  {
  
}

# 3) generer deux vecteurs de dimansions N qui suivent une loi de distribution
document=read.csv("C:/Users/amado/Downloads/id_emails.csv")
ids=arrange(document)
ids
n=1
a=seq(data=document %>%
        c(1,(n+1)))
a

E=runif(N,0,1)
V=runif(N,O,1)
#4)creer un data frame avec les 3 variables

## il fallait donc creer un nouveau data farame qui regroupe les 3 premiers variables à savoir ,telecharger la data id_emails et la regrouper 
## avec la data créer avec la commande merge

# 5) je vais utiliser la data domain_solution
domains=read.csv("C:/Users/amado/Downloads/domain_solution.csv")
domains
# 6) les 5 domaines 
##l'idée est de creer un data frame qui regroupe les 5 grands noms des domaines.
##p our cela il faut les selectionner avec la commande sort;
group_df=data.frame(domains(1:5))

group_df
lst=sort(domains,decreasing = TRUE)
# 7) oui nous pouvons trouver des caracteres logiques dans les adresses mails,il faut utiliser la commande count

# 8) 

# 9) il faut creer deux nombres qui suivent une loi uniforme avec la commande runif
C=runif(nombre)
B=runif(nombre)

#10) creer une nouvelle variable qui additionne Cet B
X=sum(C,B)


# 11)

##cette question amène à faire une refression simple avec R
library(dplyr)
 ##pour generer un OLS, on utilise la commande lm
OLS=lm(Y~X,data=domain_solution)
OLS
summary(OLS)
 ##les valeurs de p-values se trouve dans le sommary

# 12)pour faire un plot, il faut
plot(x= X,y=Y, colorConverter())
