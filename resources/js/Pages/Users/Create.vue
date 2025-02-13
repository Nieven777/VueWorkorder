<script setup>
import { useForm } from '@inertiajs/vue3';

// Create a form with user data, including 'user_idnumber'
const form = useForm({
    name: '',
    email: '',
    password: '',
    password_confirmation: '',
    user_idnumber: '',  // Add this field
});

// Submit the form
const submit = () => {
    form.post(route('users.store'));
};
</script>

<template>
    <div>
        <h2 class="text-lg font-semibold">Create New User</h2>
        <form @submit.prevent="submit">
            <div>
                <label>Name</label>
                <input v-model="form.name" type="text" required />
            </div>
            <div>
                <label>Email</label>
                <input v-model="form.email" type="email" required />
            </div>
            <div>
                <label>Password</label>
                <input v-model="form.password" type="password" required />
            </div>
            <div>
                <label>Confirm Password</label>
                <input v-model="form.password_confirmation" type="password" required />
            </div>
            <!-- User ID Number field -->
            <div>
                <label>User ID Number</label>
                <input v-model="form.user_idnumber" type="text" required />
            </div>
            <button type="submit">Create User</button>
        </form>
    </div>
</template>
