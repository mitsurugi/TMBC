Utilitats per als projectes de TMBC
=========

- paginador.class.php
- paginador.css

Classe en PHP que pagina els registres d'una taula en MySQL amb l'opció de configurar:
			- nom de la taula
			- condicions
			- criteri d'ordenacio de registres
			- resultats per pàgina
			- nom de la variable ($_GET) a utilitzar
			- numerò d'enllaços a pàgines que es mostraran màxim

Crea els enllaços a les diferents pàgines, aquests es poden configurar mitjançant l'arxiu d'estils paginador.css

-------------------------


- notificacions.css
- notificacions.js

Crea notificacions dinàmiques amb HTML5 i CSS3, notificacions d'error i de confirmació


	<div id=notificacions ok>Missatge</div>
	<div id=notificacions error>Missatge</div>

-------------------------

Funciona amb tots els navegadors, però per a tenir una experiència 100% satisfactòria cal utilitzar navegadors actuals.

Per a navegadors obsolets, cal afegir l'arxiu notificacions.js tal com s'explica en el seu interior

- funcions/cistella.function.php

Per a botigues online, afegir i borrar productes de la cistella i totalitzador dels productes que porta 

- funcions/debug.function.php

Per evaluar errors en el codi

- funcions/infoVisitant.function.php

Retorna certa informació del visitant

-------------------------

- tmbc_eshop.css
- tmbc_eshop.sql

Estructura i dades d'una botiga online

Full d'estils bàsics de la botiga online, visualització dels productes i fitxa del producte (molt simple, a falta d'un disseny estàndar)
