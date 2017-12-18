<template>
    <div>
        <calculation @confirmEvent="_confirmEvent"></calculation>
    </div>
</template>

<script>
	import calculation from '@/components/calculation'
    export default{
		components : {
			calculation
		},
        methods : {
			_confirmEvent(res){
				console.log(res)
            }
        }
    }
</script>

<style scoped>

</style>