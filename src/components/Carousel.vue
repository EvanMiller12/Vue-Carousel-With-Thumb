<template>
  <section class="section" id="app">
    <div class="columns">
        <div class="column is-4">
            <div class="card">
                <div class="card-content">
                    <div class="card-carousel">
                        <div class="card-img">
                            <img src="/some-image.jpg" alt="Some image">
                            <div class="actions">
                                <span class="prev">
                                    <i class="fas fa-chevron-left"></i>
                                </span>
                                <span class="next">
                                    <i class="fas fa-chevron-right"></i>
                                </span>
                            </div>
                        </div>
                        <div class="thumbnails">
                            <div class="thumbnail-img">
                                <img src="/some-thumbnail.jpg" alt="Some thumbnail">
                            </div>
                            <div class="thumbnail-img active">
                                <img src="/some-thumbnail.jpg" alt="Some thumbnail">
                            </div>
                            <div class="thumbnail-img">
                                <img src="/some-thumbnail.jpg" alt="Some thumbnail">
                            </div>
                        </div>
                    </div>
                    <p>Card description.</p>
                </div>
            </div>
        </div>
    </div>
</section>
</template>

<script>
export default {
  // name: 'HelloWorld',
  props: {
    // msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
