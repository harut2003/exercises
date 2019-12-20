<template>
    <v-container>
        <v-btn>Counter</v-btn>
        {{color}}
        <v-btn click="count++" small v-bind-color="color"><slot></slot>{{count}}</v-btn>
    </v-container>
</template>>

<script>
    export default{
        name: 'Counter',
        data: () => ({
            count:0,
        }),
        props: {
            color: String
        }
    };
</script>>