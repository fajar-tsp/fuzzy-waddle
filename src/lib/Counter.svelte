<script lang="ts">
  let count: number = $state(0)
  const increment = () => {
    count += 1
    randomFunction()
  }
  
  function randomFunction() {
    console.log("This is a random function")
  } 
</script>

<button onclick={increment}>
  count is {count}
</button>
