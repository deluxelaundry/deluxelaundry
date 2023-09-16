<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Cascade Laundry</title>
    <meta charset="UTF-8">
    <meta name="description" content="Phoenix technologies">
    <meta name="author" content="OKINDO BRIAN">
    <meta http-equiv="refresh" content="30">
    <meta name="viewport" content="width=device-width,initial-scale=1.0">

    
    <style>
      body { font-size: 200%; font-family:"quicksand", sans-serif; padding: 50px; 
      background-image: url('https://media.scurto.net/2015/media/56343-towelsonblue-h.jpg'); 
    background-attachment: fixed; font-size: 2vw;}
    address {font-family:sans-serif; background-color: lightgray;}
     
      table,th,td { border-collapse: collapse; border: 1px solid black;}
      table {border-spacing: 30px;}
      a:hover,a:active{background-color: #d4ddb7;}
      h1 {font-size: 200%;text-align: center; background-color: #d4ddb7;border: none;padding: 100px;}
      h2 {font-size: 150%; text-align: center;}
      img {width: 100%;}
       tr:nth-child(even){background-color: #d6eeee;}
      tr:nth-child(odd){background-color: #ffffff;}
      tr:hover{background-color: #d4ddb7; border-bottom: 1px solid black;}
      .discount {background-color: rgba(233, 242, 251, 1); border: 1px solid black; padding: 20px; margin: 20px;}
     
    </style>
  </head>
  <body>
    <div>

    <h1 id="Our services">Our Services</h1>
    <form style="float: right;">
      <label for="search">Search sevices</label>
      <input type="search" id="search" name="search">
    </form>

    </div>

    <h2>Domestic prices</h2>
    <table style="width: 100%;">
      <caption style="background-color: #ffffff; margin-left: 400px; margin-right: 400px;"><strong><span style="color: blue;">Note:
      </span></strong> Prices are 
        inclusive of washing and drying</caption>
        
    
      <tr>
        <th style="width: 10%;">serial n<sub>o</sub></th>
        <th>description</th>
        <th>quantity</th>
        <th>wash</th>
        <th>dry</th>
      </tr>
      <tr>
        <td>1</td>
        <td>duvet 3*6</td>
        <td>per piece</td>
        <td>300</td>
        <td>300</td>

      </tr>
      <tr>
        <td></td>
        <td>duvet 4*6 and 5*6</td>
        <td>per piece</td>
        <td>400</td>
      </tr>
      <tr>
        <td></td>
        <td>duvet 6*6</td>
        <td>per piece</td>
        <td>500</td>

      </tr>
      <tr>
        <td>2</td>
        <td>bed sheet</td>
        <td>8 kg</td>
        <td>400</td>
        <td>300</td>
      </tr>
      <tr>
        <td>3</td>
        <td>normal clothes</td>
        <td>8 kg</td>
        <td>400</td>
        <td>300</td>

      </tr>
      <tr>
        <td>4</td>
        <td>overalls</td>
        <td>8 kg</td>
        <td>400</td>
        <td>300</td>
      </tr>
      <tr>
        <td>5</td>
        <td>curtains</td>
        <td>8 kg</td>
        <td>400</td>
        <td>300</td>

      </tr>
      <tr>
        <td>6</td>
        <td>towels</td>
        <td>8 kg</td>
        <td>500</td>
        <td>400</td>

      </tr>
      <td>7</td>
      <td>ironing</td>
      <td>8 kg</td>
      <td>400</td>
      <td>N/A</td>
    </table><br/>
    <br/>
    <div class="discount">
      <h2>Enjoy Our discounts</h2>
      <dl>
        <dt>First time</dt>
        <dd>Enjoy 5% discount when your ask for our services for the first time</dd>
        <dt>Referals</dt>
        <dd>Get 5% discount any time you refer a friend to our services</dd>
      </dl>

    </div>
    <br/>
    <img src="https://lavenderialaundromat.co.ke/wp-content/uploads/2020/06/serv1.jpg" alt="cascade laundromat" style="float: right; 
    width: 300px; height: 300px; padding-right: 500px; max-width: 100%; height: auto;">
    <br/>
    <pre>



    </pre>

    <address>
      For more information<br/>
      <a href="https://www.cascadelaundromat.co.ke" title="Cascade Laundry" target="_blank">
        <img src="https://www.w3schools.com/images/img_bootcamp_green_html_300.png" alt="cl" style="width: 24px; height: 42px;">
      </a><br/>
      P.O BOX 6-60100 Embu, Kenya.<br/>
      phone <i style="color: blue;">+254 790 547 660, +254 748 716 402</i><br/>
      <a href="mailto:cascadelaundromat.co.ke" title="cascadelaundromat.co.ke">send us an email</a>
      
    </address>
    
    <pre> You are welcome to check our prices.
      Our prices are pocket friendly.
      All priced are inclusive of pick up and delivery if any.
      <a href="#Our services">check our services at the top</a>
    </pre>
    <div class="discount">
      <h3>Fill in the details below to become part of our community</h3><br/>
      <form action="/action_page.php" id="form1">
        <label for="username">Username</label><br/>
        <input type="text" id="username" name="username" size="50" required autocomplete="off"><br/>
        <label for="email">Enter your email:</label><br/>
        <input type="email" id="email" name="email" value="okindobrian97@gmail.com" disabled><br/>
        <label for="phone">Telephone:</label><br/>
        <input type="tel" id="phone" name="phone" placeholder="123-45-678" pattern="[0-9]{3}-[0-9]{2}-[0-9]{3}"><br/>
        <label for="cv">Upload Cv:</label><br/>
        <input type="file" id="cv" name="cv" multiple><br/>
        <label for="pwd">Password:</label><br/>
        <input type="password" id="pwd" name="pwd" size="4" maxlength="4"><br/>
        <label for="bdaytime">Birthday(date and time):</label><br/>
        <input type="datetime-local" id="bdaytime" name="bdaytime"><br/>
        <label for="qty">Quantity between 1 and 5</label><br/>
        <input type="number" id="qty" name="qty" min="1" max="10" step="2"><br/>
        <label for="area">Volume</label><br/>
        <input type="range" id="area" name="area" min="0" max="100" step="0.2" value="0.5"><br/>
        <label for="t">leave your comments here</label><br/>
        <textarea id="t" name="t" rows="10" cols="30"></textarea><br/>
        <button type="button" onclick="alert('Fall in love with your Laundry')">click me</button>
        <input type="submit" value="submit withou validation" formnovalidate><br/>
        <input type="reset" value="recall">
      </form>
      <label for="feedback">Did you like our services?</label>
      <select id="feedback" name="feedback" form="form1">
        <option value="yes">yes</option>
        <option value="no">no</option>
      </select>
    </div>
    <video width="320" height="240" controls autoplay muted>
      <source src="https://www.w3schools.com/html/mov_bbb.mp4">
    </video><br/>
    <iframe src="file:///C:/Users/HP/OneDrive/Desktop/web%20dev/HTML/favicon.html"  name="fish" title="our fish supplies"
     style="height: 300px; width: 400px; border: 2px solid black;"></iframe><br/>
     <br/>
     <a href="file:///C:/Users/HP/OneDrive/Desktop/web%20dev/HTML/favicon.html" target="fish">fish haven</a><br/>
     <footer>

      <nav>
        <a href="www.cascadelaundromat.com">cadcade laundromat</a>|<br/>
        <a href="www.executivelaundromat.com">executivelaundromat</a>|<br/>
        <a href="www.cleanitlaundromat.com">cleanitlaundromat</a>
      </nav>
     </footer>
  </body>
</html>
