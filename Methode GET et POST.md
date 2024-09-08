###QUINTARD LOTHAIRE

# Différence en methode GET et POST

## Methode GET

**Avec la méthode GET** les données sont écrites `directement dans l’URL`.

__EXEMPLE__:

www.example.com/register.php?firstname=peter&name=miller&age=55&gender=male

  _⬆️ici les paramètres sont affichés avec l'URL_

__Cela presente des  avantages✅ et  inconvénients❌__  


* __Avantage✅__
  -  Les paramètres de l’URL peuvent être enregistrés avec l’adresse du site Web.
 


* __Inconvénients❌__
  -  Le principal inconvénient de la méthode GET est l’absence de protection des données.
       Les paramètres URL sont alors visibles dans la barre d'adresse et stockés sans chiffrement dans l’historique du navigateur

  -  Un deuxième inconvénient est sa capacité limitée l’URL ne peut pas contenir plus de 2 000 caractères environ.
        De plus les paramètres des URL ne peuvent pas contenir des caractères ASCII


## Méthode POST     

__La méthode POST__ écrit les paramètres `URL dans la requête HTTP` pour le serveur.

* __Avantage✅__
Les paramètres ne sont donc pas visibles pour les utilisateurs et la portée des requêtes POST est illimitée.
La méthode POST permet de garder la confidentialité nécessaire. Les données ne sont pas mises en cache et n’apparaissent pas dans l’historique de navigation.


* __Inconvénients❌__
 Si une page Web est mise à jour avec un formulaire dans le navigateur (par exemple, en utilisant le bouton « Précédent » / « Retour »), les données du formulaire doivent être de nouveau soumises 








| GET                                   | POST                                  |
|---------------------------------------|---------------------------------------|
| Les données sont visibles dans l'URL  | Les données ne sont pas visibles      |
| Limité par la longueur de l'URL       | Pas de limite spécifique              |
| Récupération de données               | Envoi de données au serveur           |
| Moins sécurisé pour les données sensibles | Plus sécurisé pour les données sensibles |
| Les réponses peuvent être mises en cache | Les réponses ne sont généralement pas mises en cache |

