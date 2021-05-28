<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width">
    <title>repl.it</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-+0n0xVW2eSR5OomGNYDnhzAbDsOXxcvSN1TPprVMTNDbiYZCxYbOOl7+AMvyTG2x" crossorigin="anonymous">
  </head>
  <body>
    
    <!-- Navbar -->
    <nav class="navbar navbar sticky-top navbar-expand-lg navbar-dark bg-danger">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">Sakshi Gupta</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" 
    id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
       <li class="nav-item">
          <a class="nav-link active" aria-current="page"
           href="#hero">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#skills">My skills</a>
        </li>
        
        <li class="nav-item">
          <a class="nav-link" href="#works">My works</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#contact">Contact me</a>
        </li>
       
      </ul>
      
    </div>
  </div>
</nav>
<main class="container mt-3">
  <section id="hero" class="d-flex justify-content-sm-center justify-content-md-evenly align-items-center flex-column-reverse gap-3 flex-md-row">
    <!-- Hero -->
    <div class="d-flex justify-content-sm-center align-items-center flex-column flex-md-column justify-content-md-start align-items-md-start"
    >
      <h5> Hi!👋</h5>
      <h1> I'm Sakshi Gupta </h1>
      <p> Entrepreneur in Bizvidyalaya </p>
      <p> B.tech cse student  </p>
      <p> Rustamji institute of technology ,Gwalior </p>
      <button class="btn btn-info btn-sm">My Dashboard 👩‍🎓 </button>
    </div>
    <div class="d-md-none w-50 w-50">
      <img src="https://bizvidyalaya.com/wp-content/uploads/2021/03/IMG_20210301_1638319960.jpg" alt="Sakshi Gupta"
      class="w-100 h-100 rounded-circle shadow">
    </div>
    <div class="d-none d-md-block w-25 h-25">
       <img src="https://bizvidyalaya.com/wp-content/uploads/2021/03/IMG_20210301_1638319960.jpg" alt="Sakshi Gupta"
      class="w-100 h-100 rounded-circle shadow">
      </div>
    </section>
     <section id="skills" class=" mt-4 bg-secondary p-4 rounded">
        <!--My skills-->
        <h1 class="text-warning text-center bg-success gap-3">My Skills</h1>
        <h4 class="text-dark gap-2 ">My Skill Set</h4>
         <div class="d-flex flex-column flex-md-row
    justify-content-md-evenly gap-3">
        <div class="  card mb-3 " "margin:3px;" >
    <img src="https://image.flaticon.com/icons/png/512/200/200701.png"
    class="card-img-top " alt="....">
     <div class="card-body">
    <h5 class="card-title">HTML5</h5>
        </div>
        </div>
        <div class=" w-85 h-100 card mb-3 gap-3" style="margin:5px;"  >
    <img src="https://i.pinimg.com/originals/e4/3e/4c/e43e4cd41ddffc21d2e6600dfca20306.jpg"class="  card-img-top alt="...">
        </div>
        <div class="  w-70 h-100 card mb-3" style="margin:5px;"  >
        
    <img src="https://i.redd.it/31b2ii8hchi31.jpg"  class="  card-img-top alt="...."
    >
        </div>

     </section>    
    <section id="works" class="mt-4 p-4 ">
    <!-- My works -->
    <h1 class="text-success text-center">My works</h1>
   <div class="d-flex flex-column flex-md-row
    justify-content-md-evenly gap-3">
   <div class="card mb-3" >
  <img
   src="https://images.unsplash.com/photo-1554415707-6e8cfc93fe23?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1500&q=80" class="card-img-top"alt="...">
  <div class="card-body">
    <h5 class="card-title">Portfolio Website</h5>
    <p class="card-text">Built an amazing responsive website with Bootstrap.</p>
    <p class=" card-text"> #Work from home opportunity in Biz Vidyalaya.</p>
    <a href="#" class="btn btn-primary">Visit Here <i class="fab fa-github"></i> </a>
  </div>
  
   </div><div class="card mb-3" >
  <img
   src="https://images.unsplash.com/photo-1554415707-6e8cfc93fe23?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1500&q=80" class="card-img-top" alt="...">
  <div class="card-body">
    <h5 class="card-title">Portfolio Website</h5>
    <p class="card-text">Built an amazing responsive website with Bootstrap.</p>
    <p class=" card-text"> #Work from home opportunity in Biz Vidyalaya.</p>
    <a href="#" class="btn btn-primary">Visit Here <i class="fab fa-github"></i> </a>
  </div>
  
  </div>
    </section>
    <section id="contact" class="mt-4 py-4">
    <!-- Contact me -->
     <h1 class="text-success text-center">Contact Form</h1>
     <form>
  <div class="mb-3">
  <label for="exampleFormControlInput1" class="form-label">Email address</label>
  <input type="email" required class="form-control" id="exampleFormControlInput1" placeholder="name@example.com">
</div>
<div class="mb-3">
  <label for="exampleFormControlTextarea1" class="form-label">Your Message </label>
  <textarea class="form-control" id="exampleFormControlTextarea1" required placeholder="enter your amazing message!" rows="3"></textarea>
</div>
<button type="submit"class="btn btn-primary">Submit

</button>
</form> 


      
    </section>
</main>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/js/bootstrap.bundle.min.js" integrity="sha384-gtEjrD/SeCtmISkJkNUaaKMoLD0//ElJ19smozuHV6z3Iehds+3Ulb9Bn9Plx0x4" crossorigin="anonymous"></script>
  </body>
</html>
