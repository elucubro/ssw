<script lang="ts">
  let email: string = "";
  let password: string = "";
</script>

<div class="grid justify-center items-center w-screen h-screen bg-background">
  <div
    class="rounded-2xl sm:w-[100vw] md:w-[70vw] h-[80vh] bg-background flex overflow-hidden shadow-2xl"
  >
    <div
      class="bg-background sm:w-[70vw] md:w-[50vw] h-auto flex flex-col items-center justify-center"
    >
      <form
        class="s:w-[50vw] md:w-[50vw] p-5 flex flex-col text-center items-center"
      >
        <label for="email" class="text-xl">Email</label>
        <input
          class="text-2xl w-[30vw] bg-secondary p-3 m-5 rounded-xl overflow-hidden hover:border-primary border-2 focus:border-current focus-visible:outline-none focus-visible:border-primary shadow-none outline-0"
          id="email"
          type="email"
          required
          name="email"
          autocomplete="username"
          value={email}
          placeholder="pedro@hadron-collider.gov"
        />
        <label for="password" class="text-xl">Password</label>
        <input
          class="text-2xl w-[30vw] bg-secondary p-3 m-5 rounded-xl overflow-hidden hover:border-primary border-2 focus:border-current focus-visible:outline-none focus-visible:border-primary shadow-none outline-0"
          id="password"
          type="password"
          required
          name="password"
          autocomplete="username"
          value={password}
          placeholder="pedro>nala>lockie"
        />
        <button
          class="bg-primary hover:bg-accent m-5 h-10 text-white rounded-xl w-28"
          >Submit</button
        >
      </form>
    </div>
    <div class="s:w-[30vw] md:w-[20vw] h-auto image" />
  </div>
  <h5 class="absolute bottom-0 text-center m-2">
    designed and built by tinotenda mhandire
  </h5>
</div>

<style>
  .image {
    background-image: url("https://images.pexels.com/photos/3573351/pexels-photo-3573351.png?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1");
  }
  :focus:not(:focus-visible) {
    outline: 0;
  }
</style>
