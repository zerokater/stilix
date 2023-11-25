<script>
    export let link = "/";
</script>


<button on:click={() => window.location.href = link}>
    <slot></slot>
  </button>


<style>
    button{
        margin: 20px 0px 20px 0px;
        padding: 25px 40px 25px 40px;
        font-weight: 600;
        background-color: #ced4da;
        color: #6c757d;
        border: none;
        border-radius: 1rem;
        font-size: 16px;
        cursor: pointer;
        transition: 0.2s ease-out;
    }

    button:hover{
        background-color: #bec3c9;
    }


</style>