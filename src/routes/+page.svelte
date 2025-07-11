<body>
    <div class = "logoimg">
        <img src="/workshopNoShadow.png" alt="">
            <div class = "MainFunc">
                <button><a href="/Inventory">Inventory</a></button>
                <button><a href="/Borrow">Borrow</a></button>
                <button><a href="/Return">Return</a></button>
            </div>
        <p style="#Background"></p>
    </div>
</body>
<!-- <div>
  <input type="text" bind:value = {inputname}>
  <button on:click={changename}> Change Name</button>
</div> -->
<style>
  body{
    background-color: #FFF8F2;
  }
  /* .img-container img{
    width: 80px;
    height: 80px;
    border-radius: 50%
  } */
  .logoimg{
    margin: 50px;
    text-align: center;
  }
  .logoimg img{
    width: 200px;
    height: 200px;
    border-radius: 50%;
  }
  .MainFunc{
    font-size: 50px;
    font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif ;
    text-align: center;
    padding-top: 70px;
    padding: 50px;
  }
  .MainFunc button{
    display: inline-block;
    text-decoration: underline;
    padding: 5px 25px;
    margin: 120px;
    /* margin: 200px; */
  }
</style>