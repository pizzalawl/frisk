<script>
  import Game from './lib/Game.svelte'
</script>

<main>
  <!-- Main flexbox organizer -->
  <div class="d-flex flex-row p-2 m-2">

    <!-- Main Game Component and Chatbox -->
    <div class="d-flex flex-column">
      <Game/>
      <div class="border border-info p-2 m-2">Chat</div>
    </div>

    <!-- Information/Control Section -->
    <div class="border border-info p-2 m-2 ">
      <h3 class="text-center bold"> Frisk!</h3>
      <h6 class="text-center">The classic game about world domination!</h6>
      <button type="button" class="btn btn-success">Play</button>
    </div>
  
  </div>
</main>