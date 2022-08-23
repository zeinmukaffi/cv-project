<template>
    <div class="container">
        <h2 class="ds-heading mt-3">Skills</h2>
        <div class="ds-work-list-section">
            <div class="ds-work-list">
                <div class="row">
                    <div class="col-8 col-sm-12 col-md-7 col-lg-7 col-xl-7 col-xxl-7">
                        <section>
                            <p class="me-5">HTML, CSS, JS</p>
                            <div class="progress mb-2">
                                <div class="progress-bar bg-info" role="progressbar" aria-label="Success example"
                                    style="width: 85%" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100"></div>
                            </div>
                            <p class="me-5">Figma UI/UX</p>
                            <div class="progress mb-2">
                                <div class="progress-bar bg-info" role="progressbar" aria-label="Info example"
                                    style="width: 85%" aria-valuenow="50" aria-valuemin="0" aria-valuemax="100"></div>
                            </div>
                            <p class="me-5">PHP, MySQL</p>
                            <div class="progress mb-2">
                                <div class="progress-bar bg-info" role="progressbar" aria-label="Warning example"
                                    style="width: 75%" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100"></div>
                            </div>
                            <p class="me-5">Laravel</p>
                            <div class="progress mb-2">
                                <div class="progress-bar bg-info" role="progressbar" aria-label="Danger example"
                                    style="width: 80%" aria-valuenow="100" aria-valuemin="0" aria-valuemax="100"></div>
                            </div>
                        </section>
                    </div>
                    <div class="col-4">
                        <section>
                            <h3 class="ds-work-tilte">My Portfolio</h3>
                            <ul>
                                <li>Aplikasi Peminjaman Barang Laravel</li>
                                <li>CSS Landing Pages</li>
                                <li>Bootstrap Landing Page</li>
                            </ul>
                            <RouterLink to="/porto" class="ds-button">Details</RouterLink>                    
                        </section>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style>
ul li{
    list-style: disc;
    font-size: 20px;
}
.col-4 section{
    margin-left: 30px;
}
</style>