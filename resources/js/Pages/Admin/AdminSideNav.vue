<template>
<div id="layoutSidenav"> 
    <div id="layoutSidenav_nav">
        <nav class="sidenav shadow-right sidenav-light">
            <div class="sidenav-menu">
                <div class="nav accordion" id="accordionSidenav">
                    <!-- Sidenav Menu Heading (Core)-->
                    <div class="sidenav-menu-heading">Core</div>
                    <!-- Sidenav Accordion (Dashboard)-->
                    <a class="nav-link collapsed" href="javascript:void(0);" data-toggle="collapse" data-target="#collapseDashboards" aria-expanded="false" aria-controls="collapseDashboards">
                        <div class="nav-link-icon"><i data-feather="activity"></i></div>
                        Dashboard
                        <div class="sidenav-collapse-arrow"><i class="fas fa-angle-down"></i></div>
                    </a>
                    <div class="collapse" id="collapseDashboards" data-parent="#accordionSidenav">
                        <nav class="sidenav-menu-nested nav accordion" id="accordionSidenavPages">
                            <a class="nav-link" href="index.html">
                                Default
                                <span class="badge badge-primary-soft text-primary ml-auto">Updated</span>
                            </a>
                            <a class="nav-link" href="dashboard-2.html">Multipurpose</a>
                            <a class="nav-link" href="dashboard-3.html">Affiliate</a>
                        </nav>
                    </div>
                    <!-- Sidenav Heading (App Views)-->
                    <div class="sidenav-menu-heading">App Views</div>
                    <!-- Sidenav Accordion (Pages)-->
                    <a class="nav-link collapsed" href="javascript:void(0);" data-toggle="collapse" data-target="#collapsePages" aria-expanded="false" aria-controls="collapsePages">
                        <div class="nav-link-icon"><i data-feather="grid"></i></div>
                        Works
                        <div class="sidenav-collapse-arrow"><i class="fas fa-angle-down"></i></div>
                    </a>
                    
                    <!-- Sidenav Accordion (Flows)-->
                    <a class="nav-link collapsed" href="javascript:void(0);" data-toggle="collapse" data-target="#collapseFlows" aria-expanded="false" aria-controls="collapseFlows">
                        <div class="nav-link-icon"><i data-feather="repeat"></i></div>
                        Requests
                        <div class="sidenav-collapse-arrow"><i class="fas fa-angle-down"></i></div>
                    </a>
                    <div class="collapse" id="collapseFlows" data-parent="#accordionSidenav">
                        <nav class="sidenav-menu-nested nav">
                            <a class="nav-link" href="multi-tenant-select.html">Multi-Tenant Registration</a>
                            <a class="nav-link" href="wizard.html">Wizard</a>
                        </nav>
                    </div>
                    <!-- Sidenav Heading (UI Toolkit)-->
                    <div class="sidenav-menu-heading">UI Toolkit</div>
                    <!-- Sidenav Accordion (Layout)-->
                    <a class="nav-link collapsed" href="javascript:void(0);" data-toggle="collapse" data-target="#collapseLayouts" aria-expanded="false" aria-controls="collapseLayouts">
                        <div class="nav-link-icon"><i data-feather="layout"></i></div>
                        Layout
                        <div class="sidenav-collapse-arrow"><i class="fas fa-angle-down"></i></div>
                    </a>
                    <!-- Sidenav Accordion (Components)-->
                    <a class="nav-link collapsed" href="javascript:void(0);" data-toggle="collapse" data-target="#collapseComponents" aria-expanded="false" aria-controls="collapseComponents">
                        <div class="nav-link-icon"><i data-feather="package"></i></div>
                        Components
                        <div class="sidenav-collapse-arrow"><i class="fas fa-angle-down"></i></div>
                    </a>
                </div>
            </div>
            <!-- Sidenav Footer-->
            <div class="sidenav-footer">
                <div class="sidenav-footer-content">
                    <div class="sidenav-footer-subtitle">Logged in as:</div>
                    <div class="sidenav-footer-title">Valerie Luna</div>
                </div>
            </div>
        </nav>
    </div>
</div>
</template>
<script>
export default {
    name: 'AdminSideNav',
    mounted() {
        const script = document.createElement('script');
        script.src = 'public/js/scripts.js';
        script.async = true;
        document.head.appendChild(script);
    }
}
</script>

<style scoped>
/* Add any scoped styles here */
@import url('public/css/styles.css');
</style>