<script>
  export let userName;
  export let jobTitle;
  export let description;
  export let userImage;
</script>
<div>
  <header>
    <div class="thumb" class:placeholder="{!userImage}">
      <img src="{userImage}" alt="{userName}">
    </div>
    <div>
      <h1>{userName}</h1>
      <h2>{jobTitle}</h2>
    </div>
  </header>
  <div>
    <p>{description}</p>
  </div>
</div>
<style>
  h1 {
    color: purple;
  }
</style>