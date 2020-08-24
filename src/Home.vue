<template>
<div>
    <p>SERVER Status: {{ status }}</p>
    <hr>
    <button @click="ChangeStatus()">Change Status</button>
</div>
</template>
<script>
export default {
    data: function () {
        return {
            ststus: 'Critical'
        }
    },
    methods: {
        chanangeStatus() {
            this.ststus = 'Normal';
        }
    }
}
</script>