<script>
  import Crossword from "svelte-crossword";

  const data = [
    {
      clue: "Nama orang yang gila",
      answer: "AKBAR",
      direction: "down",
      x: 0,
      y: 0,
    },
    {
      clue: "Nama orang yang pintar",
      answer: "ANDREA",
      direction: "across",
      x: 0,
      y: 3,
    },
  ];
</script>

<main>
  <Crossword {data} actions="[]">
    <div slot="complete">
      <h3>Kamu menang!</h3>
    </div>
  </Crossword>
</main>

<style></style>
