<script>
  import { Modal } from "@sveltech/bricks";
  import { fly } from "svelte/transition";
</script>

<Modal>
  <button class="btn solid green" slot="activator">Show modal</button>
  <div
    class="bg-white w-64 shadow-xl rounded-lg h-24 p-8"
    transition:fly={{ y: -400 }}>
    Basic modal
  </div>
</Modal>


<style>

</style>