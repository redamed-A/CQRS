# Payment application 

- Un marchand devrait être en mesure de traiter un paiement via la passerelle de paiement et de recevoir une réponse réussie ou infructueuse. 
- Un marchand devrait être en mesure de récupérer les détails d'un paiement précédemment effectué.
- Un marchand devrait pouvoir récupérer la liste des paiements effectué,


Spécifications: 

La passerelle de paiement devra fournir aux marchands un moyen de traiter un paiement. 
Pour ce faire, le marchand devrait être en mesure de soumettre une demande à la passerelle de paiement. 
Une demande de paiement devrait inclure des champs appropriés tels que le numéro de carte, la date d'expiration, le montant, la devise et le code CVV.
Note : Simulation de la banque Dans cette solution, nous simulons la partie Banque du flux de traitement. Ce composant devrait pouvoir être remplacé par une vraie banque une fois que nous passerons en production. Nous devrions supposer qu'une réponse de la banque renvoie un identifiant unique et un statut qui indique si le paiement a été réussi.
Récupération des détails d'un paiement La deuxième exigence pour la passerelle de paiement est de permettre à un marchand de récupérer les détails d'un paiement précédemment effectué en utilisant son identifiant. Cela aidera le marchand pour ses besoins de rapprochement et de reporting. La réponse devrait inclure un numéro de carte masqué et les détails de la carte ainsi qu'un code d'état qui indique le résultat du paiement.
