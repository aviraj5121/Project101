<!doctype html>
<html class="scroll-smooth">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link href="/dist/output.css" rel="stylesheet">
  <title> Portfolio </title>
  <!-- CSS -->
  <link rel="stylesheet" href="input.css">
  <!-- devicons -->
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.15.1/devicon.min.css">
  <!-- font awesome -->
  <script src="https://kit.fontawesome.com/96892ad5c1.js" crossorigin="anonymous"></script>
  <script type="module" src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.esm.js"></script>
  <script nomodule src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.js"></script>
  <link rel="stylesheet"
          href="https://fonts.googleapis.com/css?family=Tangerine">

</head>

<body>

  <!-- square animation -->
  <!-- <ul class="square" id="sqanimate">
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
  </ul> -->

  <!-- about section -->
  <section id="about" class="h-100% w-100%">
    <!-- Nav bar -->
    <nav class="bg-transparent shadow-sm w-3.5">
      <div class=" grid grid-cols-2 max-w-6xl mx-auto p-4">
        <div class="justify-start">
          <a class="text-4xl text-white  px-8 py-4" href="" style=" font-family:Tangerine, serif; font-size: 3vw; ">Aishwar Pathak</a>
        </div>
        <div class="flex justify-end">
          <div class="flex space-x-7">

            <!-- Portfolio Logo -->
            <div class="">
              <img src="/img/logo.png" alt="Logo" class="p-1 h-10 w-10 mr-2" />
            </div>

            <!-- Primary Navbar items -->
            <div class="hidden md:flex items-center space-x-1 text-lg ">
              <!-- <a href="#about" class="py-4 px-2 text-white font-semibold transition duration-500 hover:scale-125"
                id="navlinks">About</a> -->
              <a href="#projects" class=" w-3 font-size: 3vw text4x1 py-4 px-2 text-white font-semibold transition duration-500 hover:scale-125"
                id="navlinks">Projects</a>

              <a href="#contact" class="w-3 font-size: 3vw text-4x1 py-4 px-2 text-white font-semibold transition duration-500 hover:scale-125"
                id="navlinks">Contact</a>
            </div>
          </div>
        </div>
      </div>
    </nav>


    <div class="grid grid-cols-2 py-20">
      <!-- photo and social container -->
      <div id="box-1" class="flex w-full  mx-40 h-200 w-20 bg-opaq rounded-xl shadow-lg sm:block sm:items-center ">
        <!-- Photograph -->
        <div class="content-center" id="photo">
          <img src="pfp.jpg" alt="pfp">
          <br>
        </div>

        <!-- Social media links -->
        <div
          class="flex w-full py-8 px-8 max-w-sm mx-auto bg-opaq rounded-xl shadow-lg space-y-2 sm:py-4 sm:flex sm:items-center sm:space-y-0 sm:space-x-6 ">

          <div id="social-links" class="">
            <a href="#" target="_blank"><i class="fab fa-github-square fa-3x" aria-hidden="true"></i></a>
            <a href="#" target="_blank"><i class="fab fa-linkedin fa-3x" aria-hidden="true"></i></a>
            <a href="#" target="_blank"><i class="fab fa-instagram fa-3x" aria-hidden="true"></i></a>
          </div>

        </div>
      </div>

      <!-- About me part -->
      <div
        class="flex w-full  py-8 px-8 max-w-sm mx-auto bg-opaq rounded-xl shadow-lg space-y-2 sm:py-4 sm:flex sm:items-center sm:space-y-0 sm:space-x-6 text-white">
        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Porro quas minus sint earum in expedita voluptate
          fuga perferendis atque! Cupiditate enim doloremque debitis, perspiciatis aut consectetur id facere eligendi
          quia.
          Fugit similique, eius dolore consequatur mollitia, commodi obcaecati odit minus, excepturi provident
          asperiores pariatur molestias distinctio quo veritatis dicta odio aliquam ullam aliquid dolorum soluta magnam?
          Culpa doloribus quibusdam consequatur.</p>
      </div>

    </div>
    <!-- Hobbies -->

  </section>

  <!-- project secction -->
  <section id="projects" class="">
    <h2 class="text-8xl grid-cols-1 text-center text-white pb-5" id="project_heading">Projects</h2>

    <!-- Tech stack -->
    <div class="grid-cols-9 border-2 border-y-8 p-5 mx-5 mx-auto" id="tech_stack">
      <!-- <p class="text-6xl">Tech Stack</p> -->
      <div class="text-8xl text-center">
        <i class="devicon-html5-plain-wordmark"></i>
        <i class="devicon-css3-plain-wordmark"></i>
        <i class="devicon-javascript-plain"></i>
        <i class="devicon-bootstrap-plain-wordmark"></i>
        <i class="devicon-jquery-plain-wordmark"></i>
        <i class="devicon-nodejs-plain-wordmark"></i>
        <i class="devicon-express-original-wordmark"></i>
        <i class="devicon-mongodb-plain-wordmark"></i>
        <i class="devicon-react-original-wordmark"></i>
      </div>
    </div>

    <!-- project cards -->
    <div class=" grid grid-cols-3 ">

      <!-- Project Card -->
      <div id="project_box1"
        class=" mt-5 mb-5 pb-5 border-2 border-y-8 py-5 px-5 max-w-sm mx-auto bg-opaq rounded-xl shadow-lg space-y-2 sm:pt-2 sm:block sm:items-center sm:space-y-0 sm:space-x-6">
        <!-- Project Name -->
        <h3 id="project_name" class="mt-1 mb-3 text-4xl text-white text-center min-width">Project 1</h3>
        <!-- Project Info -->
        <p id="projectinfo" class="flex w-full text-white text-xl mx-3">Lorem ipsum dolor, sit
          amet consectetur adipisicing elit.
          Excepturi velit deleniti suscipit tempora nobis, consequuntur aperiam illum enim minus hic, consectetur
          minima, fugit incidunt odit dolores reprehenderit neque inventore soluta?</p>
        <!-- button  -->
        <div>
          <button
            class="justify-center mt-5 mx-3 text-black bg-white text-xl font-bold px-20 py-3 rounded-xl hover:scale-105 transition duration-200 hover:bg-black hover:text-white align-baseline"><span
              class=""><a href="#projects" class="projectlink1">To be linked</a></span></button>
        </div>
      </div>

      <!-- Project Card -->
      <div id="project_box2"
        class="mt-5 mb-5 pb-5 border-2 border-y-8 py-5 px-5 max-w-sm mx-auto bg-opaq rounded-xl shadow-lg space-y-2 sm:pt-2 sm:block sm:items-center sm:space-y-0 sm:space-x-6 ">
        <!-- Project Name -->
        <h3 id="project_name" class="flex w-full  mt-1 mb-3 text-4xl text-white text-center">Project 2</h3>
        <!-- Project Info -->
        <p id="projectinfo" class="flex w-full text-white text-xl mx-3 min-w-min">Lorem ipsum dolor, sit amet consectetur adipisicing elit.
          Excepturi velit deleniti suscipit tempora nobis, consequuntur aperiam illum enim minus hic, consectetur
          minima, fugit incidunt odit dolores reprehenderit neque inventore soluta?</p>
        <!-- button  -->
        <div>
          <button
            class="justify-center mt-5 mx-3 text-black bg-white text-xl font-bold px-20 py-3 rounded-xl hover:scale-105 transition duration-200 hover:bg-black hover:text-white align-baseline"><span
              class=""><a href="#projects" class="projectlink2">To be linked</a></span></button>
        </div>

      </div>

      <!-- Project Card -->
      <div id="project_box3"
        class=" flex w-full    mt-5 mb-5 pb-5 border-2 border-y-8 py-5 px-5 max-w-sm mx-auto bg-opaq rounded-xl shadow-lg space-y-2 sm:pt-2 sm:block sm:items-center sm:space-y-0 sm:space-x-6 ">
        <!-- Project Name -->
        <h3 id="project_name" class="mt-1 mb-3 text-4xl text-white text-center min-width">Project 3</h3>
        <!-- Project Info -->
        <p id="projectinfo" class="text-white text-xl mx-3">Lorem ipsum dolor, sit amet consectetur adipisicing elit.
          Excepturi velit deleniti suscipit tempora nobis, consequuntur aperiam illum enim minus hic, consectetur
          minima, fugit incidunt odit dolores reprehenderit neque inventore soluta?</p>
        <!-- button  -->
        <div>
          <button
            class="flex w-full justify-center mt-5 mx-3 text-black bg-white text-xl font-bold px-20 py-3 rounded-xl hover:scale-105 transition duration-200 hover:bg-black hover:text-white align-baseline"><span
              class=""><a href="#projects" class="projectlink3">To be linked</a></span></button>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <!-- heading  -->
    <h2 class="text-8xl text-center text-white p-2" id="project_heading">Contact</h2>
    <div class="flex w-full min-h-screen justify-center items-center">
      <div class="bg-transparent w-full max-w-4xl p-8 rounded-xl shadow-lg text-wh">
  
        <div class="flex flex-col justify-betweenv space-y-9 text-4xl p-2">
          <div>
            <p class="pt-2 text-white text-xl"> Excepturi velit deleniti suscipit tempora nobis,
              consequuntur aperiam illum enim minus hic, consectetur
            </p>
          </div>
  
        </div>
        <div class="flex flex-col space-y-8">
          <DIV class="inline-flex space-x-2 items-center">
            <ion-icon name="logo-whatsapp" class="text-white text-3xl"></ion-icon>
            <span class="text-white ">+91-7089037084</span>
          </DIV>
          <DIV class="inline-flex space-x-2 items-center">
            <ion-icon name="mail-sharp" class="text-white text-3xl"></ion-icon>
            <span class="text-white ">avirajaj@gmail.com</span>
          </DIV>
          <DIV class="inline-flex space-x-2 items-center">
            <ion-icon name="location-sharp" class="text-white text-3xl"></ion-icon>
            <span class="text-white ">NIIT University</span>
          </DIV>
        </div>
        <div class="space-y-4 m-5">
          <div class="bg-transparent rounded-xl shadow-lg p-8 space-y-4">
            <form action="" class="flex flex-col space-y-6">
              <div>
                <label for="" class="text-sm text-white"> Your name </label>
                <input for="" placeholder="Your name"
                  class="ring-1 ring-gray-300 w-full rounded-md px-4 py-2 outline-none focus:ring-2 focus:ring-offset-black">
              </div>
              <div>
                <label for="" class="text-sm text-white"> Email address </label>
                <input for="" placeholder="Email address"
                  class="ring-1 ring-gray-300 w-full rounded-md px-4 py-2 outline-none focus:ring-2 focus:ring-offset-black">
              </div>
              <div>
                <label for="" class="text-sm text-white"> Message </label>
                <input for="" placeholder="message"
                  class="ring-1 ring-gray-300 w-full rounded-md px-4 py-2 outline-none focus:ring-2 focus:ring-offset-black">
              </div>
              <button class="inline-block self-end  bg-black text-white rounded-lg px-6 py-2 text-sm hover:scale-105 transition duration-200 hover:bg-white hover:text-black">
                Submit
              </button>
            </form>
          </div>
        </div>
      </div>
    </div>
    </div>
  </section>
  
</body>


<!-- Javascript added -->
<script src="app.js"></script>
<script src="https://cdn.tailwindcss.com"></script>

</html>
