<svelte:head>
  <title>Garden</title>
</svelte:head>

<main>
  <h1>mohan is slowly gardening...</h1>

  <div class="list">
    <div class="thing">
      <div class="token"></div>
      <p>planting, tending, and pruning</p>
    </div>
    <div class="thing">
      <div class="token"></div>
      <p>
        reading
        <a
          href="https://en.wikipedia.org/wiki/Notes_on_the_Synthesis_of_Form"
          target="_blank">Notes on the Synthesis of Form</a
        >
      </p>
    </div>
  </div>
</main>

<style>
  @import url("https://fonts.googleapis.com/css2?family=IBM+Plex+Mono:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;1,100;1,200;1,300;1,400;1,500;1,600;1,700&display=swap");

  h1 {
    color: #3c3c3c;
    font-size: 14px;

    margin-bottom: 40px;
  }

  p {
    color: #a4a4a4;
  }

  main {
    margin-top: 100px;
  }

  a {
    color: #a4a4a4;
    text-decoration: none;
  }

  a:visited {
    color: #3c3c3c;
  }

  .list {
    display: flex;
    flex-direction: column;
    gap: 20px;
  }

  .thing {
    display: flex;
    gap: 20px;
    align-items: center;
  }

  .token {
    height: 8px;
    width: 8px;
    rotate: 45deg;

    background: #5a941c;
    border-radius: 2px;
  }

  :global(body) {
    background-color: #101010;
    font-family: "IBM Plex Mono", monospace;
    font-size: 14px;

    max-width: 600px;
    margin: 0 auto;
    padding: 20px;
  }

  :global(*) {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    outline: none;
    border: none;
    font-weight: 500;
  }

  ::selection {
    color: #7a8a14;
    background: #243a0d;
  }
</style>
