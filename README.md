# bourso-parrainage
Landing page de parrainage BoursoBank : jusqu'à 240 € filleul / 150 € parrain. Single-file HTML, dark mode, responsive, zéro dépendance. SEO complet (Open Graph, Twitter Card, JSON-LD), tracking sans cookie via GoatCounter, lien rel=sponsored nofollow, mention de transparence LCEN. Prêt à déployer sur GitHub Pages en 1 min, sans build ni framework.


Avant de déployer :

Remplace TON-USER et ton-site par tes identifiants réels.
Crée og-image.png (1200×630 px) à la racine du repo.
Crée ton compte GoatCounter → copie l'URL exacte.


## Optimiser le partage social de ta page

### L'`og-image` (90 % de l'impact)

C'est l'image qui apparaît quand tu partages le lien sur WhatsApp, Messenger, X, etc.

**Spécifications :**
- **1200 × 630 px** (ratio 1,91:1)
- Format PNG ou JPG, < 300 Ko
- Texte lisible même en miniature (mobile = ~300 px de large)

**Ce qu'il faut afficher :**

```
┌─────────────────────────────────────────────┐
│                                             │
│   🏦  Boursobank                            │
│                                             │
│   JUSQU'À 240 € OFFERTS                     │
│                                             │
│   Sans frais · Ouvert en 5 min              │
│                                             │
│   [ton-nom / ton-handle]                    │
│                                             │
└─────────────────────────────────────────────┘
```

**Outils gratuits pour la créer :**
- [Canva](https://canva.com) → template "Open Graph"
- [Squoosh](https://squoosh.app) → compression
- Figma → export PNG

Place le fichier dans ton repo : `/og-image.png`

---

### Tester avant de partager

| Outil | Teste |
|---|---|
| [Facebook Sharing Debugger](https://developers.facebook.com/tools/debug/) | Facebook, Instagram, Messenger |
| [LinkedIn Post Inspector](https://www.linkedin.com/post-inspector/) | LinkedIn |
| [X Card Validator](https://cards-dev.x.com/) | X (Twitter) |
| [OpenGraph.xyz](https://www.opengraph.xyz/) | Vue rapide |

> ⚠️ **Cache** : après un 1er partage, les réseaux mettent en cache l'image pendant 24-72h. Pour forcer un refresh, ajoute `?v=2` à l'URL dans le debugger.

---

### Astuce : lien court + tracking

Plutôt que de partager `https://ton-user.github.io/boursobank-parrainage/` (long, moche), utilise :

```
https://is.gd/bourso240
```

ou un **QR code** (généré sur [qrcode-monkey.com](https://www.qrcode-monkey.com/)) à mettre dans ta bio ou tes stories.

---

### Message d'accompagnement (à copier-coller)

Quand tu partages le lien, le texte qui l'accompagne compte autant que l'og-image :

> *« Je viens d'ouvrir un compte BoursoBank et j'ai eu 240 € de primes. Si t'intéresse, passe par mon lien, y'a zéro frais et t'as la même offre : https://is.gd/bourso240 »*

Ton, naturel, pas "commercial". C'est ce qui convertit sur WhatsApp.

