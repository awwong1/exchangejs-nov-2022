<script>

import { count } from "../utils/stores";

function handleClick() {
  count.set($count + 1)
}
</script>

<button on:click={handleClick}><h1>{$count}</h1></button>