<script>
  export let id;
  export let text = "This is a title!";
</script>

<h1>{text}<span {id} /></h1>

<style>
  h1 {
    position: relative;
  }

  span {
    position: absolute;
    top: -95px;
  }

  @media (min-width: 850px) {
    span {
      top: 0px;
    }
  }
</style>
