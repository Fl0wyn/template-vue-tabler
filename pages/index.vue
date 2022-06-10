<template>
  <div class="page">
    <Header />
    <div class="page-wrapper">
      <Title />
      <div class="page-body">
        <div class="container-xl">
          <div class="row row-deck row-cards">
            <CardsAppUn col="col-sm-6 col-lg-3" title="App 1" />
            <CardsAppDeux col="col-sm-6 col-lg-6" title="App 2" />
          </div>
        </div>
      </div>
    </div>
    <Footer />
  </div>
</template>

<script>
export default {
  name: "IndexPage",
};
</script>
