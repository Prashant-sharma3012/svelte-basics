<style>
  .card {
    display: flex;
    flex-direction: column;
    height: 10rem;
    width: 30rem;
    border: 1px solid;
    box-shadow: 0px 0px 3px 1px;
    border-radius: 4px;
  }

  .card__header {
    display: flex;
    flex-direction: row;
    justify-content: flex-start;
    border-bottom: 1px solid;
    padding: 1rem;
  }

  .card__body {
    display: flex;
    flex-direction: row;
    justify-content: flex-start;
    padding: 1rem;
  }
</style>

<div class="card">
  <div class="card__header">Header</div>

  <div class="card__body">content</div>
</div>
