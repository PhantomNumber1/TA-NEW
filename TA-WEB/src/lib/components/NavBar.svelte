<script>

</script>
  
  <style>
    .navbar {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 1rem 1rem;
      background-color: #1A1F21;
      color: white;
      position: fixed;
      top:0;
      left: 0;
      width: 100%;
    }
  
    .menu a {
        color: white;
        text-decoration: none;
        padding: 0.5rem 0.5rem;
        position: relative;
    }

    .navbar .menu a::after {
        content: '';
        position: absolute;
        left: 50%;
        bottom: 0;
        width: 0;
        height: 2px;
        background-image: linear-gradient(to right,#F79533 0%, #F37055 15%, #EF4E7B 30%, #A166AB 44%, #5073B8 58%, #1098AD 72%, #07B39B 86%, #6DBA82 100%); /* Color of underline */
        transition: width 0.3s ease-in-out, left 0.3s ease-in-out;
        transform: translateX(12.5%);
    }

    .menu a:hover::after {
        width: calc(100% - 1rem);
        left: 0;
    }

    .menu{
        margin-right: 3rem;
        display: flex;
        gap: 0.1rem;
    }
    
    img{
      width: 15%;
    }
  
    @media (max-width: 768px) {
      .navbar .menu.open {
        display: flex;
        align-items: center;
      }
    }
  </style>
  
  <header class="navbar">
    <img class="logo" src="assets/logos/colourText.svg" alt="Logo">
    <nav class="menu open">
      <a href="#ABOUT">ABOUT US</a>
      <a href="SATELLITE">SATELLITE</a>
      <a href="#ROCKET">ROCKET</a>
      <a href="#TEAM">TEAM</a>
      <a href="#ACHIEVEMENTS">ACHIEVEMENTS</a>
      <a href="#ALUMINI">ALUMINI</a>
      <a href="#SPONSORSHIP">SPONSORSHIP</a>
      <a href="#CONTACT">CONTACT</a>
    </nav>
  </header>
  