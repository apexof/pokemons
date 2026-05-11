# Pokémon Gen I Dataset

A small dataset of the original 151 Pokémon in JSON format, along with their PNG images.

## Contents

- `json/` – One JSON file per Pokémon (1.json to 151.json) with name, types, abilities, weaknesses and image URL.
- `images/` – 151 PNG images named `001.png` to `151.png`.

## JSON structure

```json
{
  "id": 1,
  "name": "Bulbasaur",
  "type": ["grass", "poison"],
  "abilities": ["Overgrow"],
  "weakness": ["Fire", "Psychic", "Flying", "Ice"],
  "image": "https://raw.githubusercontent.com/apexof/pokemons/main/images/001.png"
}
