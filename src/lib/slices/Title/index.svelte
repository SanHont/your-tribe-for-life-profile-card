<script>
  /** @type {import("@prismicio/client").Content.TitleSlice} */
  export let slice;
</script>

<section
  data-slice-type={slice.slice_type}
  data-slice-variation={slice.variation}
>
 
<h1>{slice.primary.title[0].text}</h1>

</section>

<style>
  h1{
    font-size: 2rem;
    font-family: 'Courier New', Courier, monospace;
  }
</style>