---
title: Administration+, le service public VIP pour tous
mission: Résoudre les blocages administratifs inextricables
owner: DINUM
sponsors: 
    - name: Direction interministérielle du numérique
      acronym: DINUM
      domaine_ministeriel: spm # Service du premier ministre
      type: administration-centrale
    - name: Agence nationale de la cohésion des territoires
      acronym: ANCT
      domaine_ministeriel: territoires
      type: operateur
incubator: dinum
phases:
  - name: investigation
    start: 2017-10-01
  - name: construction
    start: 2017-10-01
  - name: acceleration
link: https://aplus.beta.gouv.fr/
repository: https://github.com/betagouv/aplus
stats: true
stats_url: https://infogram.com/stats-dusage-dadministration-1hmr6gm9mk5o6nl?live
contact: contact@aplus.beta.gouv.fr
techno:
   - Scala
   - Play Framework
   - PostgreSQL
   - Atos Worldine
   - OpenShift
   - Mailjet
---

## Avec Administration+, aucun blocage ne vous résiste

**Administration+**, c’est une plateforme qui **met en relation des aidants** comme des travailleurs sociaux **avec des agents d’organismes publics** comme la Caf. Ensemble, ils luttent contre **l’urgence sociale**. Pour cela, ils règlent rapidement et efficacement des **blocages inextricables** dans les dossiers des usagers. Administration+, **c’est le service public VIP pour tous !**


## Une Startup d’État basée sur des histoires vraies

En 2017, **Zohra Lebel-Sedki** était en poste à la Direction de l’Information Légale et Administrative (DILA). Elle décide de participer à un **challenge intrapreneurial** organisé par la DINSIC et beta.gouv.fr. Elle se base sur son expérience professionnelle. Pendant plus de trois ans, elle a répondu aux messages du site service-public.fr. Elle a constaté que **de nombreux usagers étaient bloqués dans leurs démarches administratives**. Désespérés, ils pouvaient passer d’un comportement agressif à une posture d’abandon total de leurs droits.

Elle remporte le challenge. **La Startup d’État alors appelée « A+ » est lancée en septembre 2017**. Après plusieurs itérations, Zohra s’est concentrée sur les **blocages inextricables** : ces situations où l’usager a beau se manifester auprès d’un travailleur social, quelque chose est bloqué et les moyens de communication classiques ne suffisent plus pour éviter de tomber dans la précarité. La plateforme a été lancée en expérimentation dès décembre 2017 sur Argenteuil (Val d’Oise, 95). **Le premier cas concret a été réglé en une semaine**.

> J’ai été surprise de l'accueil de mon projet : les administrations sont bienveillantes avec un tel dispositif qui vient en complément de leurs services ! Ce qui m’a poussé à faire ce choix, c’est que les blocages inextricables ne sont pas une charge de travail en plus pour les organismes. Ces dossiers ne sont pas des dossiers supplémentaires : ce sont des dossiers courants, urgents, d’usagers bien réels, qui un jour ou l’autre arriveront sur les bureaux des administrations. La question, c’est de savoir : est ce qu’on a envie que ces dossiers arrivent plus rapidement pour avoir prise en charge immédiate et qui ne pénalise pas l’usager ? Ou bien est ce qu’on attend que la situation se gangrène, que les conséquences empirent et que le dossier parte en contentieux ?

*Zohra Lebel-Sedki, cheffe de produit Administration+*

## Comment fonctionne Administration+

Administration+ est **une messagerie sécurisée** réservé aux travailleurs sociaux et agents d’opérateurs de l’État (CPAM, DDFIP, MSA, Caf, etc.). Il s’agit d’une plateforme qui permet de résoudre les blocages administratifs inextricables. Pour une raison inconnue, ces blocages n’arrivent pas à être traités par les canaux d’informations classiques. Ils doivent cependant être résolus en urgence pour éviter de faire basculer l’usager dans la précarité.

**L’usager en situation de fragilité sociale** (perte de mobilité, illectronisme, illettrisme, handicap, hospitalisation, etc.) **n’a pas directement accès à Administration+**. C’est son travailleur social, avec son autorisation, qui utilise la plateforme pour répondre à son problème.

Concrètement, un travailleur social **Aidant+** utilise la plateforme pour signaler un blocage dans le dossier d’une personne. La demande est qualifiée et transmise à ou aux organismes compétents. Le référent dans l’administration instructrice, l’**Agent+**, prend connaissance de la situation. Il peut à son tour contacter d’autres Agents+ lorsque le problème est kafkaïen. Une fois le blocage identifié et corrigé, l’Agent+ avise aussitôt l’Aidant+.

![Schéma des intéractions entre Aidants+ et Agents+](/img/startups/aplus/schema-aidants-agents.png)

La facilité d’utilisation et la sécurité sont primordiales pour Administration+. L’accès à la plateforme s’effectue depuis les boites mails professionnelles des utilisateurs. Aucun logiciel supplémentaire n’est à installer. La connexion est personnelle et confidentielle : seuls l’Aidant+ et les Agents+ saisis lors d’une demande ont accès à son contenu et aux informations personnelles concernant l’usager.

## Administration+, on en parle !

> Une telle expérimentation, complémentaire des médiations institutionnelles, notamment parce qu’elle est au contact direct des publics fragiles, peut avoir un effet positif pour l’accès aux droits et aux services publics des personnes les plus vulnérables. Et on peut également y voir une occasion pour les médiateurs de se recentrer sur leur cœur de métier

*Médiation accomplie ? Discours et pratiques de la médiation entre citoyens et administrations*, [rapport France Stratégie, 2 juillet 2019](https://www.strategie.gouv.fr/publications/mediation-accomplie-discours-pratiques-de-mediation-entre-citoyens-administrations).

## État du déploiement

#### Décembre 2017
- Argenteuil (Val d’Oise) : premier territoire à utiliser Administration+. En un an, plus de 300 situations critiques ont été traitées. Les Agents+ ont jugé pertinentes les demandes des Aidants+ à près de 90%.

#### Mars 2018
- Nice (Alpes Maritimes)

#### Juin 2018
- Cahors (Lot) dans le cadre de [l’expérimentation “Carte Blanche”](https://www.modernisation.gouv.fr/nos-actions/carte-blanche) de la direction interministérielle de la transformation publique (DITP)

#### Février 2019
- Cagnes-sur-Mer (Alpes Maritime)

#### Mars 2019
- Coeur-de-Perche (Orne) dans le cadre de [l'expérimentation “Service Public +”](https://www.modernisation.gouv.fr/nos-actions/les-services-publics) de la DITP

#### Avril 2019
- Marseille (Bouches-du-Rhône) avec la participation du [Lab Zéro](https://www.lelabzero.fr/)
- Béthune (Pas-de-Calais) dans le cadre de l'expérimentation “Service Public +” de la DITP

#### Mai 2019
- Lyon (Rhône), Quartier des Etats-Unis, dans le cadre de l'expérimentation “Service Public +” de la DITP

#### Et d'autres à venir...
Administration+ se développe et tisse de nombreux partenariats afin de pouvoir proposer l'outil au plus grand nombre d'Aidants et d'Agents. Notre objectif ? Une couverture à 100% !

## Vous souhaitez rejoindre la communauté Administration+ ?

Vous êtes au contact des usagers, vous êtes sur un des territoires déjà ouvert et vous souhaitez avoir accès à la plateforme ?

Vous supervisez une ou plusieurs équipes de travailleurs sociaux ou apparentés, vous souhaitez rejoindre la communauté ?

Vous travaillez auprès d’un opérateur public, vous souhaitez participer au déploiement national d’Administration+ ?

[Contactez-nous !](mailto:contact@aplus.beta.gouv.fr?subject=Contact%20Site%20Beta%20Gouv)
