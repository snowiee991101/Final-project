# Final-project
/*!
 * Start Bootstrap - Stylish Portfolio v5.0.1 (https://startbootstrap.com/template-overviews/stylish-portfolio)
 * Copyright 2013-2018 Start Bootstrap
 * Licensed under MIT (https://github.com/BlackrockDigital/startbootstrap-stylish-portfolio/blob/master/LICENSE)
 */

.whoSection
{

  /* background-color: coral; */
}

body,
html {
  width: 100%;
  height: 100%;
}
.mb-1:hover {
  color: pink
}

body {
    font-family: 'Source Sans Pro';
    color: rgb(255, 255, 255);
}

.btn-xl {
  padding: 1.25rem 2.5rem;
}

.content-section {
  padding-top: 7.5rem;
  padding-bottom: 7.5rem;
}

.content-section-heading h2 {
  font-size: 3rem;
}

.content-section-heading h3 {
  font-size: 1rem;
  text-transform: uppercase;
}

#whoised {
  color: rgb(247, 118, 118);
  font-size: 2rem;
  font: weight 600;
}
.carousel-item {
  height: 100vh;
  min-height: 300px;
  background: no-repeat center center scroll;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
}


.whoSection {

  background-color: white;
  background: linear-gradient(white,rgb(255, 184,188))
}
h1,
h2,
h3,
h4,
h5,
h6 {
  font-weight: 700;
}
.mv {
  font-weight: 7070;
  font: rgb(247, 126, 126)
}

.para {
  font-weight: 800;
  color: #000000
}

.text-faded {
  color: rgba(255, 255, 255, 0.7);
}

/* Map */
.map {
  height: 30rem;
}

@media (max-width: 992px) {
  .map {
    height: 75%;
  }
}

.map iframe {
  pointer-events: none;
}

.scroll-to-top {
  position: fixed;
  right: 15px;
  bottom: 15px;
  display: none;
  width: 50px;
  height: 50px;
  text-align: center;
  color: rgb(255, 251, 251);
  background: rgb(247, 146, 146);
  line-height: 45px;
}

.scroll-to-top:focus, .scroll-to-top:hover {
  color: rgb(255, 255, 255);
}

.scroll-to-top:hover {
  background: #fd8686;
}

.scroll-to-top i {
  font-weight: 800;
}

.masthead {
  min-height: 30rem;
  position: relative;
  display: table;
  width: 100%;
  height: auto;
  padding-top: 8rem;
  padding-bottom: 8rem;
  background: -webkit-gradient(linear, left top, right top, from(rgba(255, 255, 255, 0.1)), to(rgba(255, 255, 255, 0.13))), url("../img/bg-masthead.jpg");
  background: linear-gradient(90deg, rgba(255, 255, 255, 0.1) 0%, rgba(255, 255, 255, 0.1) 100%), url("../img/bg-masthead.jpg");
  background-position: center center;
  background-repeat: no-repeat;
  background-size: cover;
}

.masthead h1 {
  font-size: 4rem;
  margin: 0;
  padding: 0;
}

@media (min-width: 992px) {
  .masthead {
    height: 100vh;
  }
  .masthead h1 {
    font-size: 5.5rem;
  }
}

/* Side Menu */
#sidebar-wrapper {
  position: fixed;
  z-index: 2;
  right: 0;
  width: 250px;
  height: 100%;
  -webkit-transition: all 0.4s ease 0s;
  transition: all 0.4s ease 0s;
  -webkit-transform: translateX(250px);
  transform: translateX(250px);
  background: rgb(247, 152, 164);
  border-left: 1px solid rgba(238, 212, 212, 0.116);
}

.sidebar-nav {
  position: absolute;
  top: 0;
  width: 250px;
  margin: 0;
  padding: 0;
  list-style: none;
}

.sidebar-nav li.sidebar-nav-item a {
  display: block;
  text-decoration: none;
  color: rgb(255, 255, 255);
  padding: 15px;
}

.sidebar-nav li a:hover {
  text-decoration: none;
  color: rgb(255, 254, 254);
  background: rgb(252, 126, 126);
}

.sidebar-nav li a:active,
.sidebar-nav li a:focus {
  text-decoration: none;
}

.sidebar-nav > .sidebar-brand {
  font-size: 1.2rem;
  background: rgb(245, 101, 101);
  height: 80px;
  line-height: 50px;
  padding-top: 15px;
  padding-bottom: 15px;
  padding-left: 15px;
}

.sidebar-nav > .sidebar-brand a {
  color: rgb(255, 255, 255);
}

.sidebar-nav > .sidebar-brand a:hover {
  color: #fff;
  background: ;
}

#sidebar-wrapper.active {
  right: 250px;
  width: 250px;
  -webkit-transition: all 0.4s ease 0s;
  transition: all 0.4s ease 0s;
}

.menu-toggle {
  position: fixed;
  right: 15px;
  top: 15px;
  width: 50px;
  height: 50px;
  text-align: center;
  color: #fff;
  background: rgb(247, 146, 146);
  line-height: 50px;
  z-index: 999;
}

.menu-toggle:focus, .menu-toggle:hover {
  color: rgb(252, 248, 248);
}

.menu-toggle:hover {
  background: #fd8686;
}

.service-icon {
  background-color: rgb(241, 131, 131);
  color: rgb(235, 241, 243);
  height: 7rem;
  width: 7rem;
  display: block;
  line-height: 7.5rem;
  font-size: 2.25rem;
  -webkit-box-shadow: 0 3px 3px 0 rgba(240, 138, 138, 0.158);
  box-shadow: 0 3px 3px 0 rgb(255, 255, 255);
}

.callout {
  padding: 15rem 0;
  background: -webkit-gradient(linear, left top, right top, from(rgba(255, 255, 255, 0.1)), to(rgba(255, 255, 255, 0.1))), url("../img/bg-callout.jpg");
  background: linear-gradient(90deg, rgba(255, 255, 255, 0.1) 0%, rgba(255, 255, 255, 0.1) 100%), url("../img/bg-callout.jpg");
  background-position: center center;
  background-repeat: no-repeat;
  background-size: cover;
}

.callout h2 {
  font-size: 3.5rem;
  font-weight: 700;
  display: block;
  max-width: 30rem;
}

.portfolio-item {
  display: block;
  position: relative;
  overflow: hidden;
  max-width: 530px;
  margin: auto auto 1rem;
}

.portfolio-item .caption {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  height: 100%;
  width: 100%;
  background-color: rgba(240, 175, 175, 0.329);
  position: absolute;
  top: 0;
  bottom: 0;
  z-index: 1;
}

.portfolio-item .caption .caption-content {
  color: rgb(255, 126, 126);
  margin: auto 2rem 2rem;
  font-size: x-large
}

.portfolio-item .caption .caption-content h2 {
  font-size: 0.8rem;
  text-transform: uppercase;
}

.portfolio-item .caption .caption-content p {
  font-weight: 300;
  font-size: 1.2rem;
}

 #test {
  border-radius: 50%;
  height:127px;
  padding-bottom: 15   
}
#x {
  border-radius: 50%;
  height:127px;
  padding-bottom: 15   
}
 
#divide {
  border-radius: 50%;
  height:127px;
  padding-bottom: 15   
}

@media (min-width: 992px) {
  .portfolio-item {
    max-width: none;
    margin: 0;
  }
  .portfolio-item .caption {
    -webkit-transition: -webkit-clip-path 0.25s ease-out, background-color 0.7s;
    -webkit-clip-path: inset(0px);
    clip-path: inset(0px);
  }
  .portfolio-item .caption .caption-content {
    -webkit-transition: opacity 0.25s;
    transition: opacity 0.25s;
    margin-left: 5rem;
    margin-right: 5rem;
    margin-bottom: 5rem;
  }
  .portfolio-item img {
    -webkit-transition: -webkit-clip-path 0.25s ease-out;
    -webkit-clip-path: inset(-1px);
    clip-path: inset(-1px);
  }
  .portfolio-item:hover img {
    -webkit-clip-path: inset(2rem);
    clip-path: inset(2rem);
  }
  .portfolio-item:hover .caption {
    background-color: rgba(165, 97, 97, 0.9);
    -webkit-clip-path: inset(2rem);
    clip-path: inset(2rem);
  }
}

footer.footer {
  padding-top: 5rem;
  padding-bottom: 5rem;
}

footer.footer .social-link {
  display: block;
  height: 4rem;
  width: 4rem;
  line-height: 4.3rem;
  font-size: 1.5rem;
  background-color: rgb(243, 196, 196);
  -webkit-transition: background-color 0.15s ease-in-out;
  transition: background-color 0.15s ease-in-out;
  -webkit-box-shadow: 0 3px 3px 0 rgba(0, 0, 0, 0.1);
  box-shadow: 0 3px 3px 0 rgba(0, 0, 0, 0.1);
}

footer.footer .social-link:hover {
  background-color: #f7f5f6;
  text-decoration: none;
}

a {
  color: rgb(236, 115, 115);
}

a:hover, a:focus, a:active {
  color: #155d74;
}

.btn-primary {
  background-color: rgb(255, 255, 255) !important;
  border-color: rgb(250, 250, 250) !important;
  color: rgb(243, 132, 132) !important;
}

.btn-primary:hover, .btn-primary:focus, .btn-primary:active {
  background-color: #fcd4da !important;
  border-color: #fcd4da !important;
}

.btn-secondary {
  background-color: #ecb807 !important;
  border-color: #ecb807 !important;
  color: #fff !important;
}

.btn-secondary:hover, .btn-secondary:focus, .btn-secondary:active {
  background-color: #ba9106 !important;
  border-color: #ba9106 !important;
}

.btn-dark {
  color: rgb(255, 255, 255) !important;
}

.btn {
  -webkit-box-shadow: 0px 3px 3px 0px rgb(0, 0, 0);
  box-shadow: 0px 3px 3px 0px rgb(0, 0, 0);
  font-weight: 700;
}

.bg-primary {
  background-color: rgb(255, 184, 188) !important;
}

.text-primary {
  color: rgb(240, 80, 106) !important;
}

.text-secondary {
  color: #fd5959 !important;
}
