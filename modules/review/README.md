##### Module : review

Présentation du module.

* Activé par défaut : **non**

###### Installation

Ajoutez les lignes suivantes à votre fichier ```build.xml```, aux endroits indiqués :

Après l'import du module toolkit :
 ```xml
 <import file="${toolkit.basedir}/modules/review/module.xml" />
 ```

Dans la *target* ```setprofile``` :
```xml
<property file="${toolkit.basedir}/modules/review/build.properties" />
```

###### Directives de configuration

* review.directive.1 (valeur par défaut : val) : description
* review.directive.2 (valeur par défaut : val) : description

###### Tâches

* review.task.1 : (toolkit phase : phase) : description
* review.task.2 : (toolkit phase : phase) : description