<script>
  /** @type {import("@prismicio/client").Content.TitleSlice} */
  export let slice;
  console.log(slice)
</script>

<section
  data-slice-type={slice.slice_type}
  data-slice-variation={slice.variation}
>
<img src={slice.primary.image.url}>
<h1>{slice.primary.title[0].text}</h1>
<p>{slice.primary.info[0].text}</p>
<p>{slice.primary.info1[0].text}</p>
<p>{slice.primary.info2[0].text}</p>

</section>

<style>

  img{
    width: 15em;
    border-radius: 50%;
    object-fit: cover;
  }

  h1{
    padding-top: 2rem;
    padding-bottom: 1rem;
    font-size: 2rem;
  }

  section {
    background-color: blanchedalmond;
    padding: 2rem;
    border-radius: 3rem;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }
  
</style>