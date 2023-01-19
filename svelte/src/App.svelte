<script>
  import { Router, Route, Link } from "svelte-navigator"; 
  import Footer from "./lib/Footer.svelte";
  import Generator from "./Generator.svelte";
  import Decoder from "./Decoder.svelte";
</script>

<Router>
    <!-- Header Section starts -->
    <div class="row header pt-2 pb-2">
     
      <div class=" text-light text-center pt-3">
 
        <!-- Navbar Starts -->
        <nav>
          <nav class="navbar navbar-expand-lg mb-2">
            <a class="navbar-brand" href="/">
              
              <h2  style=" font-family:'Times New Roman', Times, serif; color:white" >User Agent</h2>
            </a>
              <div class="container-fluid">
                  <button
                      class="navbar-toggler"
                      type="button"
                      data-bs-toggle="collapse"
                      data-bs-target="#navbarNavAltMarkup"
                      aria-controls="navbarNavAltMarkup"
                      aria-expanded="false"
                      aria-label="Toggle navigation"
                  >
                      <span class="navbar-toggler-icon" />
                  </button>
                  <div class="collapse navbar-collapse justify-content-end" id="navbarNavAltMarkup">
                      <div class="navbar-nav">
                        
                          <a href="/" class="nav-link">Home</a>
                          <a href="Generator" class="nav-link">Generator</a>
                          <a href="Decoder" class = "nav-link">Decoder</a>
                      </div>
                  </div>
              </div>
          </nav>
        </nav>
        <!-- Navbar Ends. -->
      </div>
    </div>
    <!-- Header Section End -->

    <Route>
      <br>
      <br>
<div class="container">
  <div class="row">
    <div class="col">
      <h2  style=" font-family:'Times New Roman', Times, serif" >User Agent</h2>
      <br>
        <p style="font-size: 20px; font-family:'Times New Roman', Times, serif">A user agent is a computer program representing a person, for example, a browser in a Web context.</p>

        <p style="font-size: 20px;font-family:'Times New Roman', Times, serif">Besides a browser, a user agent could be a bot scraping webpages, a download manager, or another app accessing the Web. Along with each request they make to the server, browsers include a self-identifying User-Agent HTTP header called a user agent (UA) string. This string often identifies the browser, its version number, and its host operating system.</p>
        
        
    </div>
    <br>
    <br>
    <br>
    <br>
    <div class="col">
      <center><img src="./src/assets/image/homeImg.png"class="rounded float-right" style="height: 250px; width: 400px;"></center></div>
    
        <div class="w-100"></div>
    <br>
    <br>
    <br>
    <div class="col">
        
        <div class="col">
            <div class="shadow-lg p-5 mb-5 bg-white rounded">
              <center><img src="./src/assets/image/Generator.png" style=" height: 150px; width: 200px;" ></center>
              <br>
              <div class="card-body">
                <h5 style="text-align: center;  font-family:'Times New Roman', Times, serif" class="card-title">User Agent Generator</h5>
                <br>
                <p class="card-text"  style="text-align: center; font-family:'Times New Roman', Times, serif" >The string comes from a website's brower internal rendering engine. When a brower sends a request for website pages, it sends a piece of data called[HTTP Header] that is called user agent. It is relatively short line of text that contain website brower specifiation. </p>
            </div>
            </div>
          </div>
    </div>
    <div class="col">
        <div class="col">
            <div class="shadow-lg p-5 mb-5 bg-white rounded">
            <center><img src="./src/assets/image/Decoder.jfif" style=" height: 150px; width: 200px;"></center>
            <br>
              <div class="card-body">
                <h5 style="text-align: center; font-family:'Times New Roman', Times, serif" class="card-title">User Agent Decoder</h5>
                <br>
                <p class="card-text"  style="text-align: center; font-family:'Times New Roman', Times, serif" >User agent String Decoder is a tool that allows tranlating a browser user agent String into data blocks.
                </p>
                <br>
              </div>
            </div>
          </div>
    </div>
  </div>
</div> 
</Route>

    <Route path = "Generator/*Generator" component = {Generator}/>
    <Route path = "Decoder/*Decoder" component = {Decoder}/>
    <Footer />

</Router>


<style>

.header {
  background: rgb(75, 93, 250)
}

.navbar
{
  /*border-radius: 10px;*/
  color: white;
  background:transparent;
}
.nav-link:hover {
  
  color: rgb(75, 93, 250);
  background-color: white;
  border-radius: 10px;
  font-size: 24px;
}
.nav-link
{
  color: white;
  font-size: 24px;
}
.navbar-brand
{
  padding-left: 70px;
}
</style>