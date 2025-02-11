<template>
    <div class="bg-primary min-vh-100 d-flex align-items-center justify-content-center">
        <div class="container">
            <div class="row justify-content-center">
                <div class="col-lg-5">
                    <div class="card shadow-lg border-0 rounded-lg mt-5">
                        <div class="card-header text-center">
                            <h3 class="font-weight-light my-4">Login</h3>
                        </div>
                        <div class="card-body">
                            <form @submit.prevent="handleLogin">
                                <div class="form-group">
                                    <label class="small mb-1" for="email">Email</label>
                                    <input 
                                        v-model="email" 
                                        class="form-control" 
                                        id="email" 
                                        type="email" 
                                        placeholder="Enter email address" 
                                        required 
                                    />
                                </div>
                                <div class="form-group">
                                    <label class="small mb-1" for="password">Password</label>
                                    <input 
                                        v-model="password" 
                                        class="form-control" 
                                        id="password" 
                                        type="password" 
                                        placeholder="Enter password" 
                                        required 
                                    />
                                </div>
                                <div class="form-group">
                                    <div class="custom-control custom-checkbox">
                                        <input v-model="remember" class="custom-control-input" id="rememberPassword" type="checkbox" />
                                        <label class="custom-control-label" for="rememberPassword">Remember password</label>
                                    </div>
                                </div>
                                <div class="form-group d-flex align-items-center justify-content-between mt-4 mb-0">
                                    <a class="small" href="#">Forgot Password?</a>
                                    <button type="submit" class="btn btn-primary">Login</button>
                                </div>
                            </form>
                        </div>
                        <div class="card-footer text-center">
                            <div class="small"><a href="#">Need an account? Sign up!</a></div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    data() {
        return {
            email: '',
            password: '',
            remember: false,
        };
    },
    methods: {
        handleLogin() {
            console.log('Logging in with:', this.email, this.password, this.remember);
            // Handle authentication logic here
        },
    },
    mounted() {
        document.title = 'Login Page';
    },
};
</script>

<style scoped>
@import '/public/css/styles.css';
</style>
  