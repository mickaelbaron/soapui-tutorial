# SoapUI Tutoriel

L’objectif de cette leçon est d’apprendre à inspecter et à invoquer un service web via l’outil SoapUI. La leçon insiste sur la découverte des standards WSDL et SOAP et sur l’outillage proposé par SoapUI pour réaliser des tests fonctionnels (simulation, test de performance, validation de messages SOAP...).

Cette leçon est inspirée des articles publiés par Meera SUBBARAO sur le site de DZone (https://architects.dzone.com/users/meera).

**Buts pédagogiques** : lecture d'un WSDL, lecture et écriture de messages SOAP, invoquer une opération d'un service web sans programmation, création de tests fonctionnels, simulation de services web à partir de sa description.

> Ce dépôt est utilisé dans le cadre d'un cours sur les architectures orientées services que je dispense à l'[ISAE-ENSMA](https://www.ensma.fr) et à l'[Université de Poitiers](https://www.univ-poitiers.fr/) en français. Tous les supports de cours et tutoriaux sont disponibles sur ma page Developpez.com : [https://mbaron.developpez.com](https://mbaron.developpez.com/#page_soa).

## Prérequis logiciels

Avant de démarrer cette série d'exercices sur l'utilisation de SoapUI, veuillez préparer votre environnement de tests en installant :

* [SoapUI](https://www.soapui.org/ "SoapUI").

## Ressources

Retrouver la précédente leçon :

* [Tutoriel sur JAX-WS pour implémenter des services web étendus/SOAP](https://github.com/mickaelbaron/jaxws-tutorial) ;
* [Tutoriel sur JAX-RS pour implémenter des services web REST](https://github.com/mickaelbaron/jaxrs-tutorial) ;
* [Tutoriel sur le développement de WebSocket et de Server-Sent Event avec le langage Java et les bibliothèques JAX-RS et Tyrus](https://github.com/mickaelbaron/streaminghttp-tutorial) ;
* [Tutoriel sur le développement d'une application basée sur une architecture microservice avec Docker](https://github.com/mickaelbaron/javamicroservices-tutorial).

Pour aller plus loin, vous pouvez consulter les ressources suivantes :

* [Support de cours SOA](https://mickael-baron.fr/soa/introduction-soa "Support de cours SOA") ;
* [Support de cours WSDL](https://mickael-baron.fr/soa/decrire-configurer-wsdl "Support de cours WSDL") ;
* [Support de cours SOAP](https://mickael-baron.fr/soa/communiquer-soap "Support de cours SOAP") ;
* [Support de cours JAX-WS](https://mickael-baron.fr/soa/developper-serviceweb-jaxws "Support de cours JAX-WS").
* [Support de cours REST](https://mickael-baron.fr/soa/comprendre-style-architecture-rest "Support de cours REST") ;
* [Support de cours JAX-RS](https://mickael-baron.fr/soa/developper-serviceweb-rest-jaxrs "Support de cours JAX-RS") ;
* [Support de cours sur le Streaming HTTP](https://mickael-baron.fr/soa/introduction-streaminghttp) ;
* [Support de cours sur la mise en œuvre de technologies de Streaming HTTP avec le langage Java](https://mickael-baron.fr/soa/streaminghttp-mise-en-oeuvre) ;
* [Support de cours sur une introduction aux architectures microservices](https://mickael-baron.fr/soa/introduction-microservices "Support de cours sur une introduction aux architectures microservices") ;
* [Support de cours sur les outils et bibliothèques pour la mise en œuvre d'architectures microservices](https://mickael-baron.fr/soa/microservices-mise-en-oeuvre "Support de cours sur les outils et bibliothèques pour la mise en œuvre d'architectures microservices") ;
* Série de tutoriels de Meera SUBBARAO sur SoapUI : [tutoriel 1](https://architects.dzone.com/articles/functional-web-services-1 "tutoriel 1"), [tutoriel 2](https://architects.dzone.com/articles/functional-web-services-2 "tutoriel 2") et [tutoriel 3](https://architects.dzone.com/articles/functional-web-services-3 "tutoriel 3").
