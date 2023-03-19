<main>
  <div class="container">
    <div>
      <a href="https://unsplash.com/">
        <img
          src="src/lib/images/berry-pancakes.jpg"
          alt="berry pancakes"
          width="300"
          height="300"
        />

        <h3>Berry Pancakes</h3>
        <p>Pancakes served with a side of mixed berries</p>
      </a>
    </div>

    <div>
      <a href="https://unsplash.com/">
        <img
          src="src/lib/images/eggs-benny.jpg"
          alt="Eggs Benny"
          width="300"
          height="300"
        />
        <h3>Eggs Benny</h3>
        <p>Salmon eggs benedict served on an english muffin</p>
      </a>
    </div>
    <div>
      <a href="https://unsplash.com/">
        <img
          src="src/lib/images/french-toast.jpg"
          alt="french toast"
          width="300"
          height="300"
        />
        <h3>French Toast</h3>
        <p>French toast served with a side of fruit</p>
      </a>
    </div>

    <div>
      <a href="https://unsplash.com/">
        <img
          src="src/lib/images/ham-benny.jpg"
          alt="Ham Benny"
          width="300"
          height="300"
        />
        <h3>Ham Benny</h3>
        <p>Ham eggs benedict served with hash browns</p>
      </a>
    </div>
    <div>
      <a href="https://unsplash.com/">
        <img
          src="src/lib/images/oatmeal.jpg"
          alt="Oatmeal"
          width="300"
          height="300"
        />
        <h3>Oatmeal</h3>
        <p>Oatmeal served with fruit</p>
      </a>
    </div>
    <div>
      <a href="https://unsplash.com/">
        <img
          src="src/lib/images/scrambled-eggs.jpg"
          alt="Scrambled Eggs"
          width="300"
          height="300"
        />
        <h3>Scrambled Eggs</h3>
        <p>Scrambled eggs, toast, and bacon</p>
      </a>
    </div>
  </div>
</main>

<style>
  div {
    width: 100%;
    margin: 0px;
    border-radius: 1px rgb(8, 8, 8);
    box-shadow: 0 2px 2px rgb(179, 10, 10);
    justify-content: center;
    align-items: center;
  }

  div :hover {
    background-color: rgb(179, 10, 10);
    color: white;
  }

  div img {
    display: block;
    width: 100%;
    object-fit: cover;
  }

  div h3 {
    margin: 0.5rem;
    text-align: center;
  }

  div p {
    text-align: center;
    margin: 2rem;
  }

  .container {
    display: grid;
    margin: 0;
    grid-gap: 2em;
  }
  @media (min-width: 60em) {
    .container {
      grid-template-columns: repeat(3, 1fr);
      margin: 0;
      max-width: 1500px;
    }
  }
</style>
