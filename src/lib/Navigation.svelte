<script>


    let open = false
    let showslide = true

</script>

<div class="     ">
    <div class="flex text-white bg-gray-900 w-full justify-around items-center left-0 md:flex md:justify-around md:items-center md:h-20 ">
    <h1 class="font-bold text-2xl"> <a href="/">Shaihu Mohammed</a></h1>

    <ul  class=" {open ? "open" : ""} w-full bg-gray-900 text-center left-[-800px]    h-screen top-[3rem]   absolute    md:flex md:gap-5 text-lg md:p-3 md:h-auto md:static  md:w-auto"  >
      <li class="p-8 md:p-3"><a  href="/">Home</a></li>
      <li class="p-8 md:p-3"><a href="#/">About</a></li>
      <li class="p-8 md:p-3"><a href="#/">Contact</a></li>
      <li class="p-8 md:p-3"><a  href="#/">Blog</a></li>
    </ul>

         <!-- svelte-ignore a11y-click-events-have-key-events -->
         <button on:click={ ()=>open = !open} >
        <svg   class="fill-white  block md:hidden" xmlns="http://www.w3.org/2000/svg" height="48" viewBox="0 96 960 960" width="48"><path d="M120 816v-60h720v60H120Zm0-210v-60h720v60H120Zm0-210v-60h720v60H120Z"/></svg>
         </button>
</div>
</div>

<style>
  .open{
    left: 0px;
  }
</style>
