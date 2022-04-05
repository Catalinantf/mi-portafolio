<template>
  <footer id="footer" class="p-2 pt-4">
    <!-- Container -->
    <div class="container">
      <!-- Row -->
      <div class="row">
        <div class="col-md-12">
          <!-- footer follow -->
          <ul class="footer-follow pb-4">
            <li class="p-3">
              <a href="https://github.com/Catalinantf" target="_blank"
                ><b-icon icon="github" scale="2"></b-icon></a>
            </li>
            <li class="p-3">
              <a href="www.linkedin.com/in/catalinantf" target="_blank"
                ><b-icon icon="linkedin" scale="2"></b-icon></a>
            </li>
            <li class="p-3">
              <a href="https://drive.google.com/file/d/1p9ggGkpS6NrN7EzdSxk4A16fW6bpMa_J/view?usp=sharing" target="_blank"
                ><i> <strong>CV</strong> </i></a
              >
            </li>
          </ul>
          <!-- /footer follow -->
          <!-- footer copyright -->
          <div class="footer-copyright">
            <p>
              Copyright © 2022. All Rights Reserved. Designed by Catalina Tapia
            </p>
          </div>
          <!-- /footer copyright -->
        </div>
      </div>
      <!-- /Row -->
    </div>
    <!-- /Container -->
  </footer>
</template>

<script>
export default {
  name: "Footer",
};
</script>
<style>
footer{
  background-color: #332b44;
  color: #EBECE2;
}
li{
display: inline;
}
.footer-follow li a {
display: inline-block;
width: 50px;
height: 50px;
line-height: 50px;
text-align: center;
border-radius: 3px;
background-color: #EBECE2;
color:  #332b44;
}
ul{
margin: 0;
padding: 0;
list-style: none;
}
a {
    text-decoration: none;
}

</style>