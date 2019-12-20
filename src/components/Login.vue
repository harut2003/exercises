<template>
    <v-container>
        <div class="text-center">
            <v-card flat>
                <v-form>
                    <v-text-field outlined v-model="email" label="E-mail"></v-text-field>
                    <v-text-field outlined append-icon="show1 ? 'mdi-eye' : 'mdi-eye-off'" v-model="password" label="password"></v-text-field>
                    <button>Login</button>
                </v-form>
            </v-card>
        </div>
    </v-container>
    
</template>

<script>
        export default{
            name: "login",

            data: () =>({

            }),
        };
    </script>