<h1>Perspective JS</h1>
<b>Simple vanilla javascript library to create 3d visuals :star:</b>
<p>Hi welcome to Perspective JS. Perspective JS is a simple vanilla javascript library that allows to create 3D animation with mouse movements. It is so easy to use!</p>
<h2>How to use</h2>
<h3>Must requirements</h3>
<p>Just import <b>perspective.js</b> to your file and then call function <b>perspective();</b></p>
<p>Default function parameters can be seen below.</p>

    function perspective(multiplier = 1, blur = 20, shadow = "#000000") {
     ...
    }
    
<ul>
 <li><b>multiplier</b> defines rotation multiplier. Setting this value to high numbers can make your modal rotate completely. You may keep it between 0 and 1.5 but you can also experiment with it.</li>
 <li><b>blur</b> defines blur of shadows as pixels.</li>
 <li><b>shadow</b> defines shadow color as rgb values.</li>
</ul>
<p>Make sure you have add class name <b>perspective-container</b> to your container which defines area for mouse movements. Also make sure your <b>card element</b> which is expected to move like 3D object, is the first children of <b>perspective-container</b> and has CSS <b>transform-origin: center</b>.</p>
<h3>Suggested requirements</h3>
<p>You can also import <b>style.css</b> file to make quick start then you can change styling as you wish.</p>
<h3><a href="https://www.youtube.com/watch?v=3VeezhTsPaw">Tutorial Video on Youtube</a></h3>
<h4><a href="https://www.linkedin.com/in/barış-demirezen-655879190/">Follow me on linkedin</a></h4>

![Image of Yaktocat](https://i.ibb.co/T8d3Wcv/Thumbnail.jpg)
