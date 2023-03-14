<script>
    export default {
        setup() {
            // TODO : actually logout the user ( delete cookies, etc )

            const router = useRouter()
            router.push({
                path: '/login',
            })
        }
    }
</script>



<template>

</template>