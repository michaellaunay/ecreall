# ecreall

Sources du site [www.ecreall.com](https://www.ecreall.com).

Ecréall, SARL fondée en 2005 à Villeneuve d'Ascq et liquidée en 2023,
proposait des services et solutions en logiciels libres (intranets, extranets
et portails collaboratifs sous Python, Plone, Pyramid et React). Sa marque et
la propriété intellectuelle de ses logiciels ont été reprises en 2024 par son
fondateur, Michaël Launay, au sein de l'EURL
[Logikascium](https://www.logikascium.com). Ce site présente la continuité de
service et l'état de modernisation des logiciels historiques.

Site statique servi par GitHub Pages, sans étape de compilation. Il reprend la
charte et l'outillage de [logikascium](https://github.com/michaellaunay/logikascium)
et de [multiscium](https://github.com/michaellaunay/multiscium), avec l'orange
du nouveau logo en accent.

## Contenu

- `index.html` — page unique : reprise, métier, méthode, offre, logiciels,
  références (« ils nous ont fait confiance »), communauté Plone, contact.
  Le contenu est repris de la présentation Ecréall de 2022, actualisé pour
  la reprise.
- `images/ecreall-logo.svg`, `images/ecreall-logo-fond-transparent.svg` —
  nouveau logo (python blanc dans un médaillon orange) ; la version
  transparente sert de marque dans la barre de navigation.
- `images/favicon.svg` — favicon vectoriel dérivé du médaillon.
- `CNAME` — domaine servi par GitHub Pages.

## Mettre à jour l'état des logiciels

La section « Les logiciels » porte un badge par logiciel : `badge-m ok`
(modernisé, déployable sur demande) ou `badge-m wip` (en cours). Passer un
badge en `ok` au fil des livraisons.

## Mise en ligne

1. Pousser sur `main`.
2. Dans *Settings → Pages*, servir la branche `main` à la racine.
3. Chez le registraire, faire pointer `www.ecreall.com` (CNAME) vers
   `michaellaunay.github.io` et `ecreall.com` (A/ALIAS) vers les adresses
   de GitHub Pages, puis cocher *Enforce HTTPS*.
