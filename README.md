# Comissions · Facultat de Biociències

Prototip funcional de l'aplicatiu de gestió de comissions, elaborat amb la identitat gràfica de la Facultat de Biociències.

## Obrir-lo

Obriu `index.html` amb un navegador. No requereix instal·lació. Les dades es conserven al navegador mitjançant `localStorage`; el botó de reinicialització elimina les dades locals de demostració.

## Flux implementat

- Consulta pública de comissions, membres i actes aprovades.
- Gestió de comissions i membres (nom complet, inicials automàtiques, NIU, correu, presidència i fedataria).
- Creació de sessions amb número correlatiu per comissió, ordre del dia i adjunts.
- Excuses i control d'assistència; l'acta distingeix assistents, persones excusades i absents.
- Generació de l'acta amb la redacció de la plantilla, període d'esmenes i aprovació automàtica simulable.
- Previsualització de correus de convocatòria, recordatori i obertura d'esmenes; aquestes accions s'han de connectar a un proveïdor de correu en el desplegament institucional.

## Per al desplegament real

Cal substituir l'emmagatzematge local per una base de dades, configurar l'enviament de correu i els processos programats, emmagatzemar els adjunts, i integrar l'SSO UAB si la UAB facilita l'aplicació/credencials OIDC o SAML. Com a alternativa, el flux de codi d'un sol ús per correu ja està previst a la interfície.
