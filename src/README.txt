1. Create a reusable component, `<PokemonRow />` that takes in `pokemon` as 
a property and renders a row with the name, id, type and sprite image for 
that pokemon.  
  - You can find the data in `src/data/pokemon`
  - You should set the correct type for Pokemon (sidenote: this should be set in 
  a separate file so it can be shared). Right now the type is `any`
  - Set App.tsx to display the `<PokemonRow />` component

2. Create a <PokedexTable /> component that takes in an array of pokemon and renders 
all of the pokemon in that array. 
  - You can find the data in `src/data/pokemonArray`
  - Remove the `PokemonRow` component from App.txt and set 
  App.tsx to display the `<PokedexTable />` component

3. Create a <FilterablePokedexTable /> component. This component will
load all of the pokemon from `src/data/pokemonArray` and display a button
for each pokemon type (make sure duplicates are not displayed). When the user
selects a type to display, show them the `<PokemonTable />` only containing
pokemon of that type. 
  - do not display the `<PokemonTable />` if the user has not selected a type.