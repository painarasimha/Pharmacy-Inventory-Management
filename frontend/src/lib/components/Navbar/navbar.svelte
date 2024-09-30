<script>
    import { goto } from "$app/navigation";

    function handleSignIn() {
        goto("/signin");
    }
</script>

<div
    class="flex flex-col items-center py-5 bg-background text-foreground w-[230px] h-screen rounded-br-xl shadow-lg shadow-foreground"
>
    <ul class="flex flex-col items-center">
        <li class="text-xl font-bold p-5 hover:underline"><a href="/">Dashboard</a></li>
        <li class="text-xl font-bold p-5"><a href="/medicine">Medicine</a></li>
        <li class="text-xl font-bold p-5"><a href="/supplier">Supplier</a></li>
        <li class="text-xl font-bold p-5"><a href="/sales">Sales</a></li>
        <li class="text-xl font-bold p-5"><a href="/inventory">Inventory</a></li>
        <li class="text-xl font-bold p-5"><a href="/customer">Customer</a></li>
        <div class="text-xl font-bold p-5">
            <button class="w-full bg-[#2A5625] p-2 shadow-inner shadow-[#ABA78D] rounded-lg hover:scale-110 duration-500" on:click={handleSignIn}>Sign In</button>
        </div>
    </ul>
</div>
