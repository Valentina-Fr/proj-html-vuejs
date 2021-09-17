<template>
  <section class="container">
        <h5 class="brand-color">WE LIKE WHAT WE DO</h5>
        <div class="d-flex">
            <div>
            <h2 class="py-10"><span class="brand-bg-secondary brand-color">Team</span> of Experts</h2>
            <p class="font-grey py-10">Ethics and integrity are the bases on which our professionals build their careers. They are fundamentals that become daily attitudes.</p>
            <div class="row">
                <div class="col">
                    <div class="card">
                        <img src="@/assets/images/team-1.jpg" alt="cooper">
                        <div class="expert-info">
                            <h4>David Cooper</h4>
                            <h5 class="font-grey py-30">CTO &amp; CO-FOUNDER</h5>
                            <div class="social">
                                <i class="fab fa-facebook-f brand-bg-secondary brand-color"></i>
                                <i class="fab fa-twitter brand-bg-secondary brand-color"></i>
                                <i class="fab fa-linkedin-in brand-bg-secondary brand-color"></i>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="card">
                        <img src="@/assets/images/team-3.jpg" alt="jones">
                        <div class="expert-info">
                            <h4>Oliver Jones</h4>
                            <h5 class="font-grey py-30">CHIEF PROCUREMENT</h5>
                            <div class="social">
                                <i class="fab fa-facebook-f brand-bg-secondary brand-color"></i>
                                <i class="fab fa-twitter brand-bg-secondary brand-color"></i>
                                <i class="fab fa-linkedin-in brand-bg-secondary brand-color"></i>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="card">
                        <img src="@/assets/images/team-2.jpg" alt="lopez">
                        <div class="expert-info">
                            <h4>Emma Lopez</h4>
                            <h5 class="font-grey py-30">CHIEF MARKETING</h5>
                            <div class="social">
                                <i class="fab fa-facebook-f brand-bg-secondary brand-color"></i>
                                <i class="fab fa-twitter brand-bg-secondary brand-color"></i>
                                <i class="fab fa-linkedin-in brand-bg-secondary brand-color"></i>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="card">
                        <img src="@/assets/images/team-4.jpg" alt="johnson">
                        <div class="expert-info">
                            <h4>T. Johnson</h4>
                            <h5 class="font-grey py-30">CEO AND PRESIDENT</h5>
                            <div class="social">
                                <i class="fab fa-facebook-f brand-bg-secondary brand-color"></i>
                                <i class="fab fa-twitter brand-bg-secondary brand-color"></i>
                                <i class="fab fa-linkedin-in brand-bg-secondary brand-color"></i>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            </div>
            <div>
                <div class="speech brand-bg">
                    <h4 class="py-30">President speech</h4>
                    <p class="py-10">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Aliquam, non officiis nam libero, eum voluptatibus officia vitae consectetur dicta illo doloribus fuga tempore at explicabo ipsam corporis eaque illum animi.</p>
                    <p class="py-10">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Aliquam, non officiis nam libero, eum voluptatibus officia vitae consectetur dicta illo doloribus fuga tempore at explicabo ipsam corporis eaque illum animi.</p>
                    <p class="py-10">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Aliquam, non officiis nam libero, eum voluptatibus officia vitae consectetur dicta illo doloribus fuga tempore at explicabo ipsam corporis eaque illum animi.</p>
                    <address class="py-30">T.Johnson<i class="fas fa-quote-right"></i></address>
                </div>
            </div>
        </div>
  </section>
</template>

<script>
export default {
name: 'Experts'
}
</script>

<style scoped lang="scss">
    section {
        margin-top: 60px;
        margin-bottom: 60px;
    }
    .row {
        display: flex;
        flex-wrap: wrap;
    }

    .col {
        width: 50%;
    }

    .card {
        display: flex;   
        img {
            width: 40%;
            border-radius: 5px;
        }
        margin-bottom: 20px;
    }

    .expert-info {
        padding-top: 10px;
        h4 {
            font-size: 1.3rem;
        }
    }

    .fab {
        padding: 10px;
        border-radius: 50%;
        margin-right: 10px;
    }

    .fa-facebook-f {
        padding: 10px 14px;
    }

    .fa-linkedin-in {
        padding: 10px 12px;
    }

    img {
        margin-right: 10px;
    }

    .speech {
        height: 100%;
        color: #fff;
        padding: 20px;
        address {
            font-style: normal;
        }
    }

    .fa-quote-right {
       padding-left: 180px;
       color: #046162;
    }
</style>
