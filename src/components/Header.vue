<template>
    <div>
        <b-nav tabs>
            <b-nav-item disabled><b>Exam</b></b-nav-item>
            <b-nav-item disabled>Counter: {{numCorrect}}/{{numTotal}}</b-nav-item>
    <hr>
        </b-nav>
    </div>
</template>

<script>
    export default {
        props:[
            'numCorrect',
            'numTotal'
        ]

    }
</script>

<style scoped>

</style>