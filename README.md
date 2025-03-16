<!--Semantic Elements (Layout the Body)
Semantic elements improve accessibility and readability.-->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>D&amp;S Coffee Shop</></title>
    <link rel="Coffee1.gif" href="C:\Users\Kristine\Desktop\DAISY\Abregana_Amigable\D&S favicon.jpg" type="image/x-icon">
    
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header, nav, main, section, article, aside, footer {
            padding: 0px;
            margin: 1px;
            border-radius: 0px;
        }
        header { background: #704214; color: white; text-align: center; }
        nav { background: #D7B899 ; color: black; text-align: center; }
        nav a { color: black; margin: 0 10px; text-decoration: none; }
        main { display: flex; flex-wrap: wrap; width: 100%; }
        section { flex: 2; background: #f4f4f4; }
        aside { flex: 1; background: #ddd; }
        article { background: white; padding: 10px; margin-bottom: 10px; }
        footer { background: #FFF5E1; color: black; text-align: center; }

        header {
            display: flex;
            align-items: center;
        }
        img {
            margin-right: 350px;
        }
    </style>
</head>
<body>

    <header>
        <img src="C:\Users\Kristine\Desktop\DAISY\Abregana_Amigable\Coffee1.gif" alt="Coffee1" height="100" width="100">
        <div>
            <h1>D&S Coffee Shop</h1>
            <p><i>Fueling Code, One Cup at a Time.</i></p>
        </div>
    </header>

    <nav>
        <a href="#Home">Home</a>
        <a href="#">Brewing Daily</a>
        <a href="#About">About Us</a>
        <a href="#Contact">Contact</a>
    </nav>

    <main>
        <section>
            <h2 id="Home">Details</h2>
            <p>"D&amp;S Coffee Shop" is a cozy online space where coffee lovers and programmers come together. Our website showcases our menu, special brews, and a relaxing atmosphere for coding and creativity. Whether you need a strong espresso to power through debugging or a smooth latte to unwind, we've got the perfect cup for you.&#x2615;&#x1F4BB;</p>
            <article>
                <h3>Coding or Coffee</h3>
                <p>Love coding and coffee? Join us for the perfect blend of both! <br><br> Start by viewing our tutorial on how to get started with JavaScript!"</p>
                <iframe width="560" height="315" src="https://www.youtube.com/embed/ajdRvxDWH4w?si=sqNJi9KZQKSc6vaU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
            </article>
        </section>
     </main>

     <main>
        <section>
            <article>
                <h3>Enjoying?</h3>
                <p>Ready to kickstart your JavaScript journey? Visit our affiliated school today!</p>
<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2995.30836223738!2d123.89601690000003!3d10.294432899999995!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x33a99bfcc60d650d%3A0x5ee73506c68dd233!2sCebu%20Eastern%20College%20Cebu%20city!5e1!3m2!1sen!2sph!4v1741727989960!5m2!1sen!2sph" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
            </article>

            <details>
                <summary><b>Brewing Daily</b></summary>
                <ul><strong>"Top 5 Preferred Coffees"</strong></ul>
                <li>Espresso Machine</li>
                <li>French Press</li>
                <li>Drip Coffee (Coffee Maker)</li>
                <li>French Press</li>
                <li>AeroPress</li>
            </details>
        </section>
    </main>
        <aside>
            <h2>Related Content</h2>
            <p>Check out these resources:</p>
            <ul>
                <li><a href="https://youtu.be/salY_Sm6mv4?si=pfYxdtIONfiX8eq5">HTML5 Guide</a></li>
                <li><a href="https://youtu.be/1PnVor36_40?si=p5UeHNIwkiJ4o11Y">CSS Basics</a></li>
                <li><a href="https://youtu.be/xwKbtUP87Dk?si=w-phnHtnuGksFVU7">JavaScript Basics</a></li>
            </ul>

<h2 id="About">Clickable Image Map Example</h2>

    <!-- Image with clickable regions -->
    <img src="C:\Users\Kristine\Desktop\DAISY\Abregana_Amigable\CEC_map.jpg" alt="Clickable Image" usemap="#image-map" width="500" height="300">
  
    <!-- Define the image map -->
    <map name="image-map">
        <!-- First clickable region (rectangle) -->
        <area shape="rect" coords="50,50,150,150" href="https://maps.app.goo.gl/b6qCX7pc9QCUZneH9" alt="Link 1" target="_blank">

    <img src="C:\Users\Kristine\Desktop\DAISY\Abregana_Amigable\USJR_map.jpg" alt="Clickable Image" usemap="#image-map" width="500" height="300">
        <!-- Second clickable region (circle) -->
        <area shape="circle" coords="300,100,50" href="https://maps.app.goo.gl/b6qCX7pc9QCUZneH9" alt="Link 2" target="_blank">
    </map>
        </aside>
    </main>

    <figure>

    <footer id="Contact">
        <p>D&amp;S Coffee Shop <sup>Est. 2025</sup></p>
        <p>&#x1F4E7;d&scoffeeshop.est2025@gmail.com</p>
        <p>&copy; All rights reserved</p>
        <p><i>Personal Portfolio Website</i></p>
    </footer>

</body>
</html>
