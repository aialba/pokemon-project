PROJECTE POKEMON GITHUB + ADAPTACIÓ VITE+VUE

Aquest projecte tracta de pasar un antic projecte al github i pasar-lo a VITE+VUE

INSTAL·LACIO:
El primer que vaig fer va ser assegurar-me que tenia Node.js i npm instal·lats. Un cop comprovat això, vaig clonar el repositori del projecte al meu 

ordinador amb: git clone https://github.com/usuari/exemple-projecte.git

Després vaig entrar dins la carpeta del projecte amb: cd /var/www/html/Programmació/ejercicio_github/pokemon_project

I vaig instal·lar totes les dependències amb: npm install
Quan ja tenia tot preparat, vaig fer: npm run dev

i vaig comprovar que el projecte funcionava bé en local obrint el navegador a http://localhost:5173.
el qual no funcionava, ja que calia arreglar el codi perquè fos compatible amb Vue. Per fer-ho, vam haver de canviar el codi que teníem a app.js i passar-lo a un component anomenat App.vue. El mateix vaig fer amb el fitxer PokemonCards, que també vaig transformar en component .vue.

A més, també calia moure l’arxiu estil.css dins d’una carpeta. En el meu cas, l’he passat a la carpeta assets, que és on normalment es col·loquen els estils i recursos visuals.

Després, vam haver de crear una carpeta que jo he anomenat MODEL_VIEW, on he col·locat els fitxers model.js i viewmodel.js.

Finalment, vaig haver de moure les imatges dues carpetes per sobre de la ubicació del projecte, perquè si no, no es carregaven correctament dins l’aplicació.

ÚS:
Un cop tenia l’app funcionant, vaig començar a provar-la per veure que tot anés bé. Vaig mirar que es carreguessin bé els components, que la llista de Pokémon aparegués correctament i que la selecció i la batalla funcionessin.
Quan tot em funcionava, vaig fer la build de producció amb: npm run build
Això em va generar la carpeta dist, que després vaig pujar al servidor per deixar-ho tot llest.

CARACTERISTIQUES:
Durant el projecte, he treballat amb Vue i Vite, i he aplicat l’arquitectura MVVM per mantenir-ho tot ben organitzat.
He creat components per a cada part de l’app: configuració dels jugadors, selecció de l’equip, pantalla de batalla, etc. També he utilitzat directives com v-model, v-for, v-if... Per fer les vinculacions de dades i la lògica del joc.

CONTRIBUCIÓ: 
Tot i que el projecte l’he fet jo sola, si algú volgués col·laborar-hi, el procés seria bastant fàcil. Només hauria de fer un fork, crear una branca nova amb els seus canvis, fer commits clars i després enviar-me un pull request. També poden obrir un issue si detecten algun error o volen fer alguna proposta nova.

CONTACTE: 
Email: lberna@insdanielblanxart.cat
