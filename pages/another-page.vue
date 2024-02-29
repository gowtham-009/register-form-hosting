<template>
    <div class="w-100">
         <div class="container mt-5">
            <H1 class="text-center fs-1 fw-bold text-danger">Form Details</H1>
            <div class="row">
                <div class="col-6  p-3 d-flex align-items-center"><p class="fs-4">Full Name:{{ $route.query.fullname }}</p></div>
                <div class="col-6  p-3 d-flex align-items-center"><p class="fs-4">Email:{{ $route.query.email }}</p></div>
                <div class="col-6  p-3 d-flex align-items-center"><p class="fs-4">Mobile:{{ $route.query.mobile }}</p></div>
                <div class="col-6  p-3 d-flex align-items-center"><p class="fs-4">Date:{{ $route.query.date }}</p></div>
                <div class="col-6  p-3 d-flex align-items-center"><p class="fs-4">Gender:{{ $route.query.gender }}</p></div>
                <div class="col-6  p-3 d-flex align-items-center"><p class="fs-4">Address:{{ $route.query.address }}</p></div>
                <div class="col-6  p-3 d-flex align-items-center"><p class="fs-4">Country:{{ $route.query.country }}</p></div>
                <div class="col-6  p-3 d-flex align-items-center"><p class="fs-4">Postal:{{ $route.query.postal }}</p></div>
            </div>
         </div>
    </div>
</template>