<script>
  import Crossword from "svelte-crossword";

  const data = [
    {
      clue: "Lambang negara Indonesia",
      answer: "GARUDA",
      direction: "down",
      x: 1,
      y: 2,
    },
    {
      clue: "Dasar negara Indonesia",
      answer: "PANCASILA",
      direction: "across",
      x: 0,
      y: 3,
    },
    {
      clue: "Sila ketiga Pancasila",
      answer: "PERSATUAN",
      direction: "down",
      x: 5,
      y: 0,
    },
    {
      clue: "Konstitusi Indonesia",
      answer: "UUD",
      direction: "across",
      x: 4,
      y: 6,
    },
    {
      clue: "Pancasila dijadikan sebagai ...",
      answer: "PEDOMAN",
      direction: "across",
      x: 4,
      y: 1,
    },
    {
      clue: "Bulan kemerdekaan Indonesia",
      answer: "AGUSTUS",
      direction: "down",
      x: 8,
      y: 3,
    },
    {
      clue: "Hak yang melekat pada manusia dari lahir",
      answer: "HAM",
      direction: "across",
      x: 0,
      y: 7,
    },
    {
      clue: "Pancasila dijadikan sebagai ___",
      answer: "PEDOMAN",
      direction: "across",
      x: 4,
      y: 1,
    },
    {
      clue: "Presiden pertama Indonesia",
      answer: "SOEKARNO",
      direction: "across",
      x: 8,
      y: 6,
    },
    {
      clue: "Jumlah sila Pancasila",
      answer: "LIMA",
      direction: "down",
      x: 12,
      y: 3,
    },
    {
      clue: "Ketuhanan yang maha ___",
      answer: "ESA",
      direction: "down",
      x: 10,
      y: 6,
    },
    {
      clue: "Simbol sila ke-4 Pancasila",
      answer: "BANTENG",
      direction: "down",
      x: 14,
      y: 4,
    },
  ];
</script>

<main>
  <div class="pancasila-wrapper">
    <h1 class="title">Teka-Teki Silang Pancasila</h1>
    <p class="desc">Oleh: Andrea Hendrian Saleh</p>
    <img src="pancasila.png" alt="Lambang Pancasila" class="pancasila" />
  </div>
  <Crossword {data} actions="['reveal']" />
</main>

<style>
  .pancasila-wrapper {
    display: flex;
    flex-flow: column;
  }

  .title {
    font-family: "Montserrat", sans-serif;
    font-size: 1.5rem;
    text-align: center;
    margin-bottom: 0;
  }

  .desc {
    font-family: "Montserrat", sans-serif;
    font-size: 0.8rem;
    text-align: center;
    margin-top: 0.1rem;
  }

  .pancasila {
    width: 30vw;
    margin: auto;
  }
</style>
