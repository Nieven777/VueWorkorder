<script setup>
import AuthenticatedLayout from '@/Layouts/AuthenticatedLayout.vue';
import AdminSideNav from '@/Pages/Admin/AdminSideNav.vue';
import AdminDashboard from '@/Pages/Admin/AdminDashboard.vue';
</script>

<template>
    <AuthenticatedLayout>
        <div class="flex h-screen">
            <!-- Sidebar (Fixed Width) -->
            <div class="w-64  text-white">
                <AdminSideNav/>
            </div>

            <!-- Dashboard (Takes Remaining Space) -->
            <div class="flex-1 p-6">
                <AdminDashboard/>
            </div>
        </div>
    </AuthenticatedLayout>
</template>
