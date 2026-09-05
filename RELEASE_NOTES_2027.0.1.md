# StageFlow v2027.0.1 — Windows et macOS

StageFlow reste gratuit, facultatif et utilisable seul. Cette corrective
consolide la coordination de la suite sans changer le nom public
`StageFlow v2027`.

## Correctifs

- Une application reliée à une Session StageFlow LIVE par le réseau est
  reconnue sans inventer de chemin de projet local.
- Les identités de projet et de session restent obligatoires et sont vérifiées
  avant d'afficher un logiciel comme connecté ou d'accepter une commande.
- Une présence locale conserve un vrai chemin absolu ; une présence réseau
  ambiguë ou incohérente est refusée au lieu d'afficher un faux succès.
- Les dates RFC 3339 avec `Z` ou avec un décalage numérique explicite sont
  acceptées par les contrats communs, afin de conserver la compatibilité entre
  les logiciels de la suite.
- Les guides communs FR/EN édition 2027.1 sont embarqués sans modification.

## Compatibilité pendant la mise à jour

Les applications restent autonomes. Pendant un mélange temporaire de versions,
une commande non comprise ou une présence trop ancienne apparaît comme
indisponible ou incompatible ; elle n'est jamais présentée comme connectée ou
réussie à tort.

## Plateformes

- Windows 11 x64 : installateur autonome et connecteur AutoCAD 2026 facultatif.
- macOS 14 ou plus récent : images disque séparées Apple Silicon et Intel.
- Les paquets Mac sont vérifiés nativement mais ne sont pas notarisés par Apple.
  Il ne faut pas désactiver globalement les protections de macOS.
- AutoCAD reste disponible uniquement sous Windows.

Les interfaces audio, la projection, MIDI, OSC, Stream Deck et AutoCAD doivent
être validés avec le matériel et l'installation réels avant exploitation.

---

# StageFlow v2027.0.1 — Windows and macOS

StageFlow remains free, optional and fully usable on its own. This maintenance
release consolidates suite coordination while keeping the public product name
`StageFlow v2027`.

## Fixes

- An application joined to a StageFlow LIVE session over the network is now
  recognized without inventing a local project path.
- Project and session identities remain mandatory and are checked before a
  client is shown as connected or a command is accepted.
- A local presence keeps a real absolute path; an ambiguous or inconsistent
  network presence is rejected instead of reporting false success.
- Common contracts accept RFC 3339 timestamps with either `Z` or an explicit
  numeric offset, preserving interoperability across the suite.
- The final 2027.1 French and English suite guides are bundled unchanged.

## Compatibility while updating

Every application remains autonomous. During a temporary mix of versions, an
unsupported command or older presence is shown as unavailable or incompatible;
it is never reported as connected or successful when it is not.

## Platforms

- Windows 11 x64: self-contained installer and optional AutoCAD 2026 connector.
- macOS 14 or later: separate Apple Silicon and Intel disk images.
- Mac packages are natively verified but are not Apple-notarized. Do not disable
  macOS protections globally.
- AutoCAD remains Windows-only.

Audio interfaces, projection, MIDI, OSC, Stream Deck and AutoCAD require
acceptance with the actual hardware and installation before production use.

SiLeMIO / By Mamat----[]---
