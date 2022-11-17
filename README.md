En estos 2 videos hemos instalado @ngrx/router-store y lo hemos implementado en app-module.ts
y tambien se ha agregado en src/app/store/app.state.ts el reducer del router de la store

Solo con la instalacion, se puede comprobar, incluso en la carga inicial, que en la pestana
redux de chrome devtools hay 2 nuevas acciones despachadas:

@ngrx/router-store/navigation

y

@ngrx/router-store/navigated

De esta forma queda asociado el router de angular a la store de ngrx