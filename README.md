# PROJECT 4808 V2.26.17 — Navigation résiliente en arrière-plan

Base : V2.26.16.

Ajout : conservation locale de l'état de navigation (chrono, progression, D+, position et checkpoints) lorsque Safari masque temporairement l'onglet. Au retour, la carte est rafraîchie et le suivi GPS est réarmé sans réinitialiser la randonnée.

Limite iOS/Safari : une page web ne peut pas garantir un suivi GPS continu si le système suspend ou tue complètement l'onglet en arrière-plan. Au retour, l'application reprend automatiquement autant que le navigateur le permet.
