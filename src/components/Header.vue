<template>
    <div>
        <div class="top-header">
            <div class="container h-100">
                <div class="row justify-content-between align-items-center h-100">
                    <div class="col pt-3">
                        <p>We have a 95% Successful Pass Rate!</p>
                    </div>

                    <div class="col pt-3 text-end">
                        <p> <i class="fas fa-phone me-2"></i> 
                            Give us a call to book your tuition! 1-800-555-555
                        </p>
                    </div>
                </div>
            </div>
        </div>

        <Jumbotron />
    </div>
</template>

<script>
import Jumbotron from "./Jumbotron.vue"

export default {
    name: 'Header',

    components: {
        Jumbotron,
    }
}
</script>

<style lang="scss">
    @import "~@fortawesome/fontawesome-free/css/all.min.css";

    .top-header{
        height: 50px;
        background-color: #484848;
        color: #e5e8eb;

        p{
            font-size: 12px;
        }
    }
</style>