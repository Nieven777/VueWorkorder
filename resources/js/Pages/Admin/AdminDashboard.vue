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
                    <div class="row">
                        <div class="col-xxl-8">
                            <!-- Tabbed dashboard card example-->
                            
                            <!-- Illustration dashboard card example-->
                            <div class="card mb-4">
                                <div class="card-body py-5">
                                    <div class="d-flex flex-column justify-content-center">
                                        <img class="img-fluid mb-4" src="assets/img/illustrations/data-report.svg" alt="" style="height: 10rem" />
                                        <div class="text-center px-0 px-lg-5">
                                            <h5>New reports are here! Generate custom reports now!</h5>
                                            <p class="mb-4">Our new report generation system is now online. You can start creating custom reporting for any documents available on your account.</p>
                                            <a class="btn btn-primary p-3" href="#!">Get Started</a>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            
                        </div>
                        
                    </div>
                </div>
            </main>
            <footer class="footer mt-auto footer-light">
                <div class="container-fluid">
                    <div class="row">
                        <div class="col-md-6 small">Copyright &copy; Your Website 2021</div>
                        <div class="col-md-6 text-md-right small">
                            <a href="#!">Privacy Policy</a>
                            &middot;
                            <a href="#!">Terms &amp; Conditions</a>
                        </div>
                    </div>
                </div>
            </footer>
        </div>
    </div>
</template>

<script>

export default {
    name: 'AdminDashboard',
    mounted() {
        feather.replace();
    }
}
</script>

<style scoped>
@import url('https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.1/css/all.min.css');
@import url('https://cdn.datatables.net/1.10.22/css/dataTables.bootstrap4.min.css');
@import url('public/css/styles.css');
</style>
