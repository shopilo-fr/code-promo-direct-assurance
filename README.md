# Code promo Direct Assurance, recuperation automatique depuis shopilo.fr

Module Python pour la recuperation automatique de **codes promo Direct Assurance** depuis [shopilo.fr](https://shopilo.fr/reductions/direct-assurance.fr). Renvoie les **coupons Direct Assurance** actifs au format JSON, pret a etre integre dans un bot Telegram, une extension de navigateur ou tout autre outil.

**Page live :** [shopilo-fr.github.io/code-promo-direct-assurance](https://shopilo-fr.github.io/code-promo-direct-assurance/)

![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue) ![License MIT](https://img.shields.io/badge/license-MIT-green)

## Installation

```bash
pip install requests beautifulsoup4
git clone https://github.com/shopilo-fr/code-promo-direct-assurance
cd code-promo-direct-assurance
python fetch.py
```

## Exemple de sortie

```json
[
  {
    "store": "Direct Assurance",
    "code": "SHOPILO15",
    "discount": "15%",
    "description": "15% de reduction sur votre assurance auto",
    "expires": "2026-10-13",
    "source": "https://shopilo.fr/reductions/direct-assurance.fr"
  }
]
```

## Coupons Direct Assurance disponibles

| Reduction | Description | Source |
|----------|-----------|-------|
| 15% | 15% de reduction sur votre assurance auto | [shopilo.fr](https://shopilo.fr/reductions/direct-assurance.fr) |

Codes actifs : **[shopilo.fr/reductions/direct-assurance.fr](https://shopilo.fr/reductions/direct-assurance.fr)**

## Questions frequentes

### Comment utiliser un code promo Direct Assurance ?
Copiez le code depuis le tableau ci-dessus ou depuis [shopilo.fr](https://shopilo.fr/reductions/direct-assurance.fr), ajoutez les produits a votre panier sur Direct Assurance et saisissez le code au moment du paiement dans le champ prevu.

### Combien de temps durent les coupons Direct Assurance ?
Chaque coupon a une date d'expiration indiquee dans la colonne "Expiration". Le script fetch.py renvoie uniquement les coupons actifs au moment de l'execution.

### Ou trouver les bons de reduction Direct Assurance les plus recents ?
La page [shopilo.fr/reductions/direct-assurance.fr](https://shopilo.fr/reductions/direct-assurance.fr) est mise a jour quotidiennement avec les codes promo Direct Assurance, bons de reduction Direct Assurance et coupons promotionnels Direct Assurance les plus recents.

### Le code ne fonctionne pas. Que faire ?
Verifiez la date d'expiration et les conditions (montant minimum de commande, produits eligibles). Certains codes sont valables uniquement sur l'application mobile ou pour la premiere commande.

## A propos de Direct Assurance

Direct Assurance est l'une des boutiques en ligne les plus populaires. Sur [shopilo.fr](https://shopilo.fr/reductions/direct-assurance.fr), retrouvez les meilleurs codes promo Direct Assurance, coupons Direct Assurance verifies et bons de reduction Direct Assurance actifs, mis a jour chaque jour.

## Installation npm

```bash
npm install code-promo-direct-assurance
```

```javascript
const { fetchCoupons } = require('code-promo-direct-assurance');
fetchCoupons().then(data => console.log(data));
```

## Licence

MIT, donnees extraites de [shopilo.fr](https://shopilo.fr)
