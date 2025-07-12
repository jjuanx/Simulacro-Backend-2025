En este simulacro hemos creado una unica propiedad: --> FACIL
  - pinnedAt: Date  --> Creada en migration y en model

Hemos añadido una nueva ruta PATCH '/restaurants/:restaurantId/togglePinned', que hemos creado un nuevo controlador 'tooglePinned' --> FACIL

Para la validation de restaurant debemos tener en cuenta que se nos entrega un booleano 'pinned' y segun este en el create establecemos o no el pinnedAt --> MEDIO

Para la ordenacion realizar nos llamadas una con los pinned y otra con los no --> DIFICIL
