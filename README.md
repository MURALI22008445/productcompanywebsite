# Web Design for a Software Product Company

## AIM:

To design a static website for a software product company company.

## DESIGN STEPS:

### Step 1:

Requirement collection.

### Step 2:

Creating the layout using HTML and CSS.

### Step 3:

Updating the sample content.

### Step 4:

Choose the appropriate style and color scheme.

### Step 5:

Validate the layout in various browsers.

### Step 6:

Validate the HTML code.

### Step 6:

Publish the website in the given URL.

## PROGRAM :
Homepage
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Andrew mobiles</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Andrew mobiles.</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact Us.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/logo1.PNG" alt="logo1" />
          <div class="contenttext">
            Shop the latest and trending Smartphones and Accessories from a wide
            range of products at the best price and exciting offers
            and deals. Andrew partners with top brands like Apple, Samsung, 
            OnePlus, Nokia, Oppo, Vivo, Micromax, and realme to offer the
            best-in-class Smartphones that satisfies your budget and needs. 
            The everyday accessories that simplify and accompany your daily life like
            Mobile Chargers, Connectors, Headphones, Headsets, Memory Cards, Power Banks, 
            and Speakers are also available at an affordable price range.
            <br />
            Meeting your daily goals in the hustle-bustle life is undoubtedly a task!
            Accomplish your daily goals and fitness wellness like a Pro with our advanced Smart Wearable gadgets from Andrew.
            Shop from a variety of Fitness Trackers, Smartwatches, Smart Trackers, 
            Smart Lighting and Smart Speakers from best-selling brands like
            Amazon, Apple, Boat, Bose, Fastrack, Fitbit, Amazfit, Lenovo, Marshall OnePlus, Samsung, and Xiaomi.
            The real Avenger is here.
                        <ul>
              <li>unlimited offers</li>
              <li>No cost EMI</li>
              <li>Anywhere free delivery</li>
            </ul>          </div>        </div>      </div>      <div class="footer">
        Copyright &#169; 2021 Andrew mobiles, Developed by Murali S.
      </div>  </div>  </body></html>
```

products:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Andrew mobiles</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Andrew mobiles.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact Us.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/i phn.JPG" alt="product image">
                  </div>
                  <div class="itemname">i phn</div>
                  <div class="itemprice">Price: Rs.1,50,000 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/lava.PNG"  alt="product image">
                  </div>
                  <div class="itemname">lava</div>
                  <div class="itemprice">Price: Rs.10,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/lg.PNG"  alt="product image">
                </div>
                <div class="itemname">lg</div>
                <div class="itemprice">Price: Rs.24,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/motorola.JPG"  alt="product image">
                </div>
                <div class="itemname">motorola</div>
                <div class="itemprice">Price: Rs.15,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/nokia.PNG"  alt="product image">
                </div>
                <div class="itemname">nokia</div>
                <div class="itemprice">Price: Rs.1,500,000.00 </div>
              </div>
              <div class="productitem">
                <div class="itemimage">
                <img src="/static/img/one plus.JPG"  alt="product image">
                </div>
                <div class="itemname">one plus</div>
                <div class="itemprice">Price: Rs.40,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/oppo.webp"  alt="product image">
                </div>
                <div class="itemname">oppo</div>
                <div class="itemprice">Price: Rs.14,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/realme.JPG"  alt="product image">
                </div>
                <div class="itemname">realme</div>
                <div class="itemprice">Price: Rs.22,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/redmi.PNG"  alt="product image">
                </div>
                <div class="itemname">redmi</div>
                <div class="itemprice">Price: Rs.32,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/samsung.webp"  alt="product image">
                </div>
                <div class="itemname">samsung</div>
                <div class="itemprice">Price: Rs.18,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/vivo.JPG"  alt="product image">
                </div>
                <div class="itemname">vivo</div>
                <div class="itemprice">Price: Rs.21,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/xiomi.PNG"  alt="product image">
                </div>
                <div class="itemname">xiomi</div>
                <div class="itemprice">Price: Rs.39,000.00 </div>
              </div>

          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 Andrew mobiles, Developed by Murali S.
      </div>    </div>  </body></html>
```

peoples:
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Andrew mobiles</title>
        <link rel="stylesheet" href="./css/layout.css" />
        <link rel="icon" href="./img/icon.png" type="image/x-icon" />
    </head>
    <body>
        <div class="container">
            <div class="banner">Andrew mobiles</div>
            <div class="menu">
                <div class="menuitem"><a href="/static/home.html">Home</a></div>
                <div class="menuitem"><a href="/static/products.html">Products</a></div>
                <div class="menuitemselected"><a href='/static/people.html'>people</a></div>
                <div class="menuitem"><a href='/static/contact Us.html'>contact Us</a></div>
            </div>
            <div class="content">
                <div class="productcontent">
                    <h1>Our Crew Welcomes You All</h1>
                    <div class="productitems">
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="./img/person1.jpg" alt="people image">
                            </div>
                            <div class="itemname">Chief Executive Officer</div>
                            <div class="itemprice">alexa</div>
                        </div>
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="./img/person2.jpg" alt="people image">
                            </div>
                            <div class="itemname">Chief Financial Officer</div>
                            <div class="itemprice">kim</div>
                        </div>
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="./img/person3.jpg" alt="people image">
                            </div>
                            <div class="itemname">Chief Operating Officer</div>
                            <div class="itemprice">srisha</div>
                        </div>
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="./img/person4.jpg" alt="people image">
                            </div>
                            <div class="itemname">Chief Marketing Officer</div>
                            <div class="itemprice">asifa</div>
                        </div>
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="./img/person5.jpg" alt="people image">
                            </div>
                            <div class="itemname">Chief Technology Officer</div>
                            <div class="itemprice">Rohit</div>
                        </div>
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="./img/person6.jpg" alt="people image">
                            </div>
                            <div class="itemname">President</div>
                            <div class="itemprice">sahaa</div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="footer">
                Copyright &#169; 2021 Andrew mobiles, Developed by Murali S. 
            </div>        </div>    </body></html>
```

Contact:
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Andrew mobiles</title>
        <link rel="stylesheet" href="./css/layout.css" />
        <link rel="icon" href="./img/icon.png" type="image/x-icon" />
    </head>

    <body>
        <div class="container">
            <div class="banner">Andrew mobiles</div>
            <div class="menu">
                <div class="menuitem"><a href="/static/home.html">Home</a></div>
                <div class="menuitem"><a href="/static/products.html">Products</a></div>
                <div class="menuitem"><a href='/static/people.html'>people</a></div>
                <div class="menuitemselected"><a href='/static/contact Us.html'>contact Us</a></div>
            </div>
            <div class="content">
                <div class="Peoplecontent">
                    <h1>FEEL FREE TO CONTACT US</h1> 
                    <div class="Peopleitems">
                        <h2>For Enquiry</h2>
                        <h3>EMAIL : andrewmobiles@gmail.com</h3>
                        <h3>NUMBER: +91 6655443321</h3>
                        <h3>ADDRESS: 12B,rich street,Anna nagar,chennai.</h3>
                    </div>
                </div>
            </div>
            <div class="footer">
            Copyright &#169; 2021 Andrew mobiles, Developed by Lakshmi priya.
            </div>        </div>    </body></html>
```


    
## OUTPUT:

### Home Page:
![img](so1.png)

### Product Page:
![img](so2.png)

### People Page:
![img](so3.png)

### Contact Page:
![img](so4.png)


## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
