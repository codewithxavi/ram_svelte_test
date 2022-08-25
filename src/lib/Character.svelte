<script>
  export let character;
</script>

<div>
  <img src={character.image} alt={character.name} />
  <h1>{character.name}</h1>
  <h3>{character.species}</h3>
</div>
