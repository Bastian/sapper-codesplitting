<script>
  import moment from "moment";

  const time = moment().format();
</script>

<svelte:head>
  <title>About</title>
</svelte:head>

<h1>About this site</h1>

<p>This is the 'about' page. There's not much here.</p>

<p>It's {time}</p>
