<template>
    <form class="flex flex-col w-4/5 gap-10">
        <input v-model="email" class="p-2 hover:cursor-text hover:text-black/40" type="text" placeholder="Introduce tu Email aquí">
    </form>

    <div class="flex gap-10 my-5 flex-col sm:flex-row">
        <button @click="login" class="py-1 px-10 rounded-full bg-teal-100 hover:bg-teal-900 transition-all hover:px-20 hover:text-white">Send Regex</button>
    </div>
</template>

<script>

    export default {
        data() {
            return {
                
            };
        },
        methods: {
            
        },
        mounted() {},
    }

</script>