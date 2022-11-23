<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Hygraph</title>

    <style>
      h1 {
        text-align: center;

        color: #090E24;
        display: block;

      }
      h2 {
        text-align: center;
        border: 1px;
        line-height: 32px;
        padding: 10px;
        padding-left: 2px;
        padding-right: 2px;
        border-radius: 3px;
        color:  #6246EA;
      
      }
      img {
        display: block;
        margin: 0 auto;
        font-size-adjust: 20%;
        max-width: 100%;
        max-height: 10%;
        border-radius: 4px;
        border-color: black;
      }
      p {
        line-height: 1.5;
        font-size: 16px;
        margin: 15;
        color: black;
        text-align: center
        
      }
      .learn-more {
        display: block;
        margin-top: 10px;
        text-decoration: none;
        color: #6246EA;
        font-size: 16px;
        text-shadow: #e5d8bf;
        text-align: center;
      }
      button {
        display: block;
        margin: 20px auto;
        background-color: 	#d1bee4;
        font-size: 32px;
        box-shadow: #8f1d14;
        border:#94aa2a
        border: 1px solid;
        border-radius: 16px;

      
      }

      button:hover {
        opacity: 0.8;
        cursor: pointer;
      

      }
      .footer{
        text-align: center;
        
      }
       .container {
        max-width: 600px;
        margin: 0 auto;
        padding: 60px;
       }
       body {
        background-color: CCFFFF;
       }
      ]
    
    </style>
  </head>
  <body>
    <div class="container">
      <h1>Hygraph</h1>
      <h2>The federated Content Platform</h2>
      <img
        src="https://media.graphassets.com/LjKKW6RwShAwtS0TEoFA"
    width="1200"
    height="350"
        />
      <p>
         Hygraph is the <strong>first native GraphQL Headless CMS</strong>focused on Content Federation. As a frontend and backend agnostic API-first solution, Hygraph enables over 50,000 teams around the world to create, enrich, and deliver content programmatically.
      </p>

      <p>
          <strong> Go-to-market, and optimize ROI</strong> 
Hygraph empowers teams to work in an agile manner. Your developers are free to continue working with their preferred tech stack, whilst content editors can create, manage, and distribute content in parallel.
Hygraph reduces implementation time, helps lower overheads and maintenance, fits into your evolving tech stack, and allows you to scale projects as you go.
      </p>
<p>
  <strong>Future proof digital experiences</strong>
Manage all your team’s content within a unified content repository, and let your developers query it from a single GraphQL endpoint.

Hygraph delivers all requests via API, allowing you to deliver content natively to all platforms across web, mobile, wearables, and other digital displays.

  
      <a
        href="https://hygraph.com/"
        target="_blank"
        class="learn-more"
      >
        Learn more on Hygraph.com
      </a>
      <p>
        <button class="buy-button">
          💻  Let's Talk 💻  
        </button>
      </p>
      <p class="footer">
        This page was built by: 
        <a href="https://www.linkedin.com/in/juela-kapllani/" target="_blank">
          Juela Kapllani🌻
        </a>
      </p>
    </div>
   <script>
      function buybook() {
        let name = prompt ("What is your name?");
        let email = prompt ("What is your email address?");
         
        if(name === null)
        alert( "Thank you! Please check your email for further info! 🌻"
        );
        else{
           alert( "Thank you," + name + ", please check your email for further info! 🌻"
        );
        }
      }
      let button = document.querySelector(".buy-button");
      button.addEventListener("click",buybook);
    </script>
  </body>
</html>

