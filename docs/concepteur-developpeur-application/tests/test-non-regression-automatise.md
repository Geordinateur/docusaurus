#Test de Non-régression Automatisé

Le TNRA à pour but de maintenire l'application après ajout ou modification de nouvelles fonctionnalité pour l'utilisateur final. Pour cela il parcours l'application à l'aide d'un robot pour simuler l'utilisateur, il va faire des clic des validation de formulair et vérifer les résultats attendu.

---------CHATGPT---------

# Test de Non-régression Automatisé (TNRA)

## Introduction
Le Test de Non-régression Automatisé (TNRA) a pour but de maintenir la stabilité de l'application après l'ajout ou la modification de nouvelles fonctionnalités. Il permet de vérifier que les nouvelles modifications n'ont pas introduit de régressions dans les fonctionnalités existantes de l'application.

## Objectif
L'objectif principal des TNRA est d'assurer que les nouvelles fonctionnalités ou corrections de bugs n'affectent pas négativement le fonctionnement déjà établi de l'application. Cela est réalisé en simulant les actions d'un utilisateur via un robot qui parcourt l'application.

## Processus
Le processus de TNRA comprend plusieurs étapes :
1. **Préparation** : Identification des cas de tests critiques et des scénarios utilisateurs à automatiser.
2. **Automatisation** : Écriture des scripts de tests automatisés pour simuler les actions de l'utilisateur (clics, validation de formulaires, etc.).
3. **Exécution** : Lancement des scripts de tests sur l'application.
4. **Vérification** : Validation des résultats obtenus par rapport aux résultats attendus.

## Outils Utilisés
Il existe plusieurs outils populaires pour réaliser des TNRA, tels que :
- **Selenium** : Un outil open-source qui permet d'automatiser les navigateurs web.
- **JUnit** : Utilisé principalement pour tester les applications Java.
- **Cucumber** : Permet d'écrire des tests dans un langage compréhensible par tous (Gherkin).
- **TestNG** : Un framework de tests inspiré par JUnit mais introduisant de nouvelles fonctionnalités.

## Avantages
- **Gain de Temps** : Les tests automatisés peuvent être exécutés rapidement et à plusieurs reprises sans intervention humaine.
- **Fiabilité** : Réduction des erreurs humaines par rapport aux tests manuels.
- **Couverture de Test** : Possibilité de tester une large partie de l'application de manière systématique.

## Inconvénients
- **Coût Initial** : Mise en place des scripts de tests automatisés peut être coûteuse en termes de temps et de ressources.
- **Maintenance** : Les scripts de tests doivent être maintenus et mis à jour régulièrement pour refléter les changements dans l'application.

## Conclusion
Les TNRA sont essentiels pour assurer la qualité et la fiabilité des applications après chaque modification. Bien qu'ils nécessitent un investissement initial, ils apportent des avantages significatifs en termes de gain de temps et de réduction des erreurs.

## Références
- [Selenium Documentation](https://www.selenium.dev/documentation/en/)
- [JUnit 5 User Guide](https://junit.org/junit5/docs/current/user-guide/)
- [Cucumber Documentation](https://cucumber.io/docs/guides/10-minute-tutorial/)
- [TestNG Documentation](https://testng.org/doc/documentation-main.html)
