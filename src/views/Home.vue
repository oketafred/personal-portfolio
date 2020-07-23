<template>
    <main role="main">
        <section class="jumbotron text-center " style="margin-bottom: 1px !important">
            <div class="container">
            <div class="row">
                <div class="col-md-5 mt-4">
                    <h1 class="jumbotron-heading mb-3">I'm <span class="my-name">Oketa Fred</span></h1>
                    <p class="lead text-muted">I'm a Ugandan based web designer & front‑end developer focused on crafting clean & user‑friendly experiences, I am passionate about building excellent software that improves the lives of those around me.</p>
                    <div class="mt-4">
                        <a href="mailto:oketafred@gmail.com" class="btn btn-primary mr-4">Email Me <span class="button-icons"><vue-fontawesome icon="envelope" size="1" color="lightgray"></vue-fontawesome></span></a>
                        <a href="oketafred-cv.pdf" target="_blank" class="btn btn-danger">Download CV <span class="button-icons"><vue-fontawesome icon="file-pdf-o" size="1" color="lightgray"></vue-fontawesome></span></a>
                    </div>
                </div>
                <div class="col-md-7">
                    <img class="img-fluid w-90" src="http://geniusdevs.com/themeforest/gfolio/v3-one/assets/images/about2.jpg" height="400" width="350" />
                </div>
            </div>
            </div>
        </section>
        </main>
</template>

<script>
    export default {
        name: "Home"
    }
</script>

<style scoped>
.button-icons {
    padding-left: 20px;
}
.my-name {
    color: #434490;
    font-weight: 600;
}
</style>