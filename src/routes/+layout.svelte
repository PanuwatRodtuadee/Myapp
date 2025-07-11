<!-- src/routes/+layout.svelte -->
<header>
    <nav class="name-container">
      <ul>
        <h1>CS Media</h1>
      </ul>
    </nav>
    <nav class="menu">
      <ul>
        <li><h3><a href="/">Home</a></h3></li>
        <li><h3><a href="/About">About</a></h3></li>
        <nav class = "ig">
          <!-- <li><h3><a href="https://www.instagram.com/cs_media.workshop/" class = "icon-button"> <img src="/static/ig logo.jpg" alt="instagram logo" width=30px ></a></h3></li> -->
          <li><h3><a href="https://www.instagram.com/cs_media.workshop/" class="btn instagram"><i class="fab fa-instagram"></i></a></h3></li>
        </nav>
        <!-- <li><h3><a href="/Borrow">Equipment</a></h3></li> -->
        <!-- <li><h3><a href="/Return">Return</a></h3></li> -->
      </ul>
    </nav>
  </header>

  
  <slot />
  
  <style>
    header {
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 0 50px;
      background-color: gray;
    }
    .name-container {
      display: flex;
      font-size: 20px;
    }
    .menu ul {
      text-align: right;
      display: flex;
    }
    .menu li {
      display: flex;
      margin-left: 100px;
      padding-right: 100px;
    }
    .menu a{
      font-size: 25px;
    }
    footer{
      list-style: none;
      background-color: gray;
      padding: 40px;
    }
    footer p{
      text-align: right;
    }
    .igfooterlogo{
      font-size: 25px;
      text-align: right;
      list-style: none;
    }
    
    
  </style>
<footer>
  <p>Contact</p> 
  <nav class="igfooterlogo">
    <li><a href="https://www.instagram.com/cs_media.workshop/" class ="btn instagram"><i class="fab fa-instagram"></i> instagram</a></li>
  </nav>
</footer>