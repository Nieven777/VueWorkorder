<script setup>


</script>

<template>
    
    <div>
        <div id="layoutSidenav_content">
            <main>
                <header class="page-header page-header-dark bg-gradient-primary-to-secondary pb-10">
                    <div class="container">
                        <div class="page-header-content pt-4">
                            <div class="row align-items-center justify-content-between">
                                <div class="col-auto mt-4">
                                    <h1 class="page-header-title">
                                        <div class="page-header-icon"><i data-feather="activity"></i></div>
                                        Welcome to the Dashboard
                                    </h1>
                                    <div class="page-header-subtitle">Example dashboard overview and content summary</div>
                                </div> 
                            </div>
                        </div>
                    </div>
                </header>
                <!-- Main page content-->
                <div class="container mt-n10">
                    <div class="row">
                        <div class="col-xl-4 mb-4">
                            <!-- Dashboard example card 1-->
                            <a class="card lift h-100" href="#!">
                                <div class="card-body d-flex justify-content-center flex-column">
                                    <div class="d-flex align-items-center justify-content-between">
                                        <div class="mr-3">
                                            <i class="feather-xl text-primary mb-3" data-feather="package"></i>
                                            <h2>Work Reports</h2>
                                            <div class="text-muted small">To create informative visual elements on your pages</div>
                                        </div>
                                        <img src="assets/img/illustrations/browser-stats.svg" alt="..." style="width: 8rem" />
                                    </div>
                                </div>
                            </a>
                        </div>
                        <div class="col-xl-4 mb-4">
                            <!-- Dashboard example card 2-->
                            <a class="card lift h-100" href="#!">
                                <div class="card-body d-flex justify-content-center flex-column">
                                    <div class="d-flex align-items-center justify-content-between">
                                        <div class="mr-3">
                                            <i class="feather-xl text-secondary mb-3" data-feather="book"></i>
                                            <h2>Profile</h2>
                                            <div class="text-muted small">To keep you on track when working with our toolkit</div>
                                        </div>
                                        <img src="assets/img/illustrations/processing.svg" alt="..." style="width: 8rem" />
                                    </div>
                                </div>
                            </a>
                        </div>
                        <div class="col-xl-4 mb-4">
                            <!-- Dashboard example card 3-->
                            <a class="card lift h-100" href="#!">
                                <div class="card-body d-flex justify-content-center flex-column">
                                    <div class="d-flex align-items-center justify-content-between">
                                        <div class="mr-3">
                                            <i class="feather-xl text-green mb-3" data-feather="layout"></i>
                                            <h2>Work Orders</h2>
                                            <div class="text-muted small">To help get you started when building your new UI</div>
                                        </div>
                                        <img src="assets/img/illustrations/windows.svg" alt="..." style="width: 8rem" />
                                    </div>
                                </div>
                            </a>
                        </div>
                    </div>
                    
                </div>
            </main>
            
        </div>
    </div>

</template>

<script>



// export default {
//     name: 'AdminDashboard',
//     mounted() {
//         feather.replace();
//     }
// }
</script>

<style scoped>
@import url('https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.1/css/all.min.css');
@import url('https://cdn.datatables.net/1.10.22/css/dataTables.bootstrap4.min.css');
@import url('public/css/styles.css');
</style>
