<!DOCTYPE html>
<haed>

    <meta name="viewport" content="width=device-width, initial-scale=1">
    <style>
        html{scroll-behavior: smooth;}
        .class1
        {
            float: left;font-size: 1vw;font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
           
        }
        .class1:hover{ border-bottom: 3px solid red;}
        .first
        {
         
            height: 550px;
            float: left;
        }
        .col
        {
            float: left;
            height: 500px;
           margin-bottom: 20px;
            margin-left: 5px;
        }
        .toolhead{font-size: 24px; color: rgb(122, 107, 107);}
        .tool{height: 500px;}
        .content{ overflow-y:scroll ; height: 390px;width: cover;margin-top: 10px;}
        ul{
            list-style-type: circle;
        }
        .level, .level1
        {
            margin-left: 10px;text-align: center;
            float: left;
            background-color: rgb(154, 154, 240);
            color: white;font-size: 30px;
            width:150px;
            height: 40px;
            border: blue solid 1px ;border-radius: 6px;
        }
        .learning-content
        {
            margin-top: 10px;
            width: 100%;
            height: 1000px;
            background-color: burlywood;
        }
        .artigal
        {
            float: left;
            width: 320px;
            height: 320px;
            margin-right: 11px;
            margin-bottom: 11px;
        }
        .artist{height: 700px;width: 100%;margin-top: 30px;margin-bottom: ;}
        .lrncol
        {
            float: left;
        }
        ol li{font-size: 20px;}
        .lrncol ul li{
            width: 634px;height: 30px;
            list-style-type:none;margin-left: -40px;font-size: 20px;padding-left: 20px;
        }
        .lrncol ul li:hover{ box-shadow:0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);}
        .eyestp
        {
            width: 150px;border: 1px solid rgb(187, 176, 176);
            height: 180px;float: left;margin-right: 10px;margin-top: 30px;
        }
        .eyestp span{font-size: 18px;text-align: center;margin-left: 50px;}
        .level{float:left;margin-right: 20px;width: 150px; height: 35px;color: white;text-align: center;background-color: blue;}

        .advancelist li{
            float: left;width: 90px;background-color: rgb(209, 192, 192);list-style-type: none;height:40px;font-size: 30px;text-align: center;
            margin-left: 20px;border-radius: 6px;
        }
        .advancelist li:hover{background-color: rgb(95, 81, 81);color: white;}
        .level:hover{background-color: rgb(84, 124, 43);}
        .top :hover {background-color: rgb(158, 148, 148);}
            .last
            {
                width: 100%;
                height: 250px;
                border: 1px solid black;
                background-color:rgb(39, 36, 36);
                color: white;
            }
            .last .part2
            {
                margin-top: 40px;
                width: 200px;
                float: left;
            }
    </style>
</haed>
<body>
    <div style="height: 100px; width: 100%; border-bottom: 4px solid rgb(231, 213, 213);" >
        <div class="class1"><img  src="logo.jpeg" width="80px" height="80px"></div>
    <div class="class1"><img src="mainpic.png" width="200px" height="80px"></div>
    <a href="about.html"><div class="class1" style="width: 60px; padding-top: 30px; margin-left: 100px;width: 100px;color: blue;font-size: 1.8vw;"><center>About us</center></div></a>
  
    <a href="shoping.html"> <div  class="class1" style="width: 60px; padding-top: 30px; margin-left: 100px;width: 100px;color:rgba(255, 166, 0, 0.747) ;font-size:  1.8vw;"><center>shoping</center></div></a>
    
    <div class="class1" onclick="scrl(710)"  style="width: 60px; padding-top: 30px; margin-left: 100px;width: 100px;color:red;font-size:  1.8vw;"><center>Tools</center></div>
    <div  class="class1" onclick="scrl(1600)"  style="width: 60px; padding-top: 30px; margin-left: 100px;width: 100px;color:rgb(179, 167, 167);font-size:  1.8vw;"><center><b >Learning</b></center></div>
    <div class="class1" onclick="scrl(2640)" style="width: 60px; padding-top: 30px; margin-left: 100px;width: 100px;color:palevioletred;font-size:  1.8vw;"><center>Inspiration</center></div>
</div>
<div style="width: 100%; height: 600px; " >
    <div class="first" style="width: 700px; margin-top: 30px;height: 550px;">
        <center><img src="firstpic.jpg" width="94%" height="500px"></center>
    </div>
    <div class="first" style="width: 500px; margin-left: 20px;margin-top: 30px; ">
        <h1>What is sketching</h1>
        <p style="font-size: 22px;">A type of drawing which is completely done with free hand. It ia an art to create a representation for design or complete drawing.
            An artist who makes sketch is known as sketch artist. They often create their own variation art. Sketching is all about drawing and shading.
        The whole art depends on these aspects. The choise of pencils, graphite and pastels makes the art perfect. <br>
        Sketching is drawing made rapidly without too many details to represent an individual, scenery or idea. Sketches are often spontaneous and done
         using one or two different kinds of medium. Sometimes, they are used by artists to recall one or more aspects of a particular subject.  </p>
    </div>
</div>
    
    <div class="tools" style="width: 100%; height: 600px;" >
    <nav style=" font-size: 60px;color: rgb(126, 8, 126); border-bottom: 4px solid rgb(214, 205, 205);margin-bottom: 20px;">
    Tools</nav>
    <div class="col" style="width : 38%">
        <img src="alltools.png" width="500px" height="500px" usemap="#tools">
        <map name="tools">
            <area shape="circle" coords="275,337,60" onclick="ftool(2)">
            <area shape="rect" coords="0,0,275,246" onclick="ftool(3)">
            <area shape="rect" coords="0,310,200,560" onclick="ftool(4)">
            <area shape="rect" coords="302,216,475,64" onclick="ftool(5)">

        </map>
    </div>
    <div class="col" style="width: 59%; border: 1px solid rgb(209, 198, 198);">
        <div class="tool" style="font-size: 20px;padding-left: 10px; ">
            <div style="margin-left: -10px; color: red;height: 60px;text-align: center; background-image: linear-gradient(to bottom ,white, rgb(238, 230, 230));"><h1><b>  Essantial tools for sketching</b></h1></div>
            <ul>
                <li>Graphite pencil</li>
                <li>Charcol pencil</li>
                <li>white charcoal pencil</li><li>Mechani pencil</li><li>Kneaded eraser</li><li>tombow eraser</li><li>colored pencil</li>
                <li>tombow eraser</li><li>charcol powder</li><li>blending stumps</li><li>soft paper</li><li>fixative spray</li>
            </ul>
            <br>
            <span style="color: blue;">now click on the picture of the tool for which you want to know.</span>
        </div>
        <div class="tool" style="font-size: 20px;padding-left: 10px;display: none;">
            <div style="margin-left: -10px; color: red;height: 60px;text-align: center; background-image: linear-gradient(to bottom ,white, rgb(238, 230, 230));"><h1><b>  Variety of eraers</b></h1></div>
            <div class="content"><span class="toolhead">Kneaded Eraser –</span> This eraser lifts material from the surface, instead of using fricti
            on to remove it.  It can be pulled and fashioned into different forms to create specific marks.  This eraser gets dirt
            y over time, but can be cleaned by pulling and “kneading” it.<br><br>
            <center><img src="p3.jpg" width="100px" height="100px"> </center>
            <span class="toolhead">Vinyl or Plastic Erasers –</span> This eraser is the toughest of the bunch.  It can erase
             almost anything.  But be warned – this eraser can tear the paper if you’re not careful.<br><br>
             <center><img src="vinera.jpg" width="100px" height="100px"> </center>
             <span class="toolhead">Tombow eraser</span> mainly to erase penciled sketch lines after applying ink lines. A larger 
             eraser becomes a liability as it results in pencil and ink lines to bleed too much. It is also handy when working with Scantron forms.<br><br>
             <center><img src="22.jpg" width="100px" height="100px"> </center>
             <span class="toolhead">Gum Eraser –</span> “The Crumbler”.  This eraser is great for removing media from surfaces that are sensitive 
             to tearing.  A gum eraser removes the medium through friction, but crumbles as it does so – preserving the surface.<br><br>
             <center><img src="gumera.jpg" width="100px" height="100px"> </center></div>
        </div>
        <div class="tool" style="font-size: 20px;padding-left: 10px;display: none;">
            <div style="margin-left: -10px; color: red;height: 60px;text-align: center; background-image: linear-gradient(to bottom ,white, rgb(238, 230, 230));"><h1><b> Blending tools</b></h1></div>
            <div class="content"><span class="toolhead">Blending stumps –</span> Blending stumps are essential for the artist wanting to smudge or move material around on the surface.  A blending stump allows the artist to create
             gradations in value without introducing the oils of the finger (through finger smudging) which can make a drawing look dirty or uncontrolled.<br><br>
             <center><img src="p6.jpg" width="100px" height="100px"> </center>
            <span class="toolhead">Cotton –</span> you can use cotton for blending.you can also go with go with  cotton bud to do blending. You can also make use of tissue and tortillon. <br><br>
            <center><img src="cotbud.jpg" width="100px" height="100px"> </center>
             <span class="toolhead">brushes -</span> Blending Brush can be used with wet or dry products. This loose, dome-shaped brush is perfect for blending eyeshadow. It blends color effortlessly on the lid and 
             crease and can also be used to apply concealer. ... In a sweeping movement, glide the brush across the eyelid to blend color.<br><br>
             <center><img src="p8.jpg" width="100px" height="100px"> </center></div>
            
        </div>
        <div class="tool" style="font-size: 20px;padding-left: 10px;display: none;">
            <div style="margin-left: -10px; color: red;height: 60px;text-align: center; background-image: linear-gradient(to bottom ,white, rgb(238, 230, 230));"><h1><b> varity of pencils</b></h1></div>
            <div class="content"><span class="toolhead">charcol pencil –</span> Pencil charcoal comes in a range from hard to soft, just like drawing pencils. The advantage of a charcoal pencil is that you can get a very fine point 
            and apply quite a lot of pressure. You will also keep a bit cleaner. Charcoal pencils work perfectly for small pieces<br><br>
            <center><img   src="charpen.jpg" width="100px" height="100px"> </center>
            
            <span class="toolhead">graphite pencil –</span> Solid graphite pencils, also known as woodless pencils, are often used for art and drawing. While a standard pencil is a thin core of graphite (well, graphite 
            mixed with clay, generally) inside a wooden body, a solid graphite pencil does away with the wood<br><br>
            <center><img src="grapen.jpg" width="100px" height="100px"> </center>
            <span class="toolhead">Mechanical pencil -</span> Mechanical pencils can achieve the type of precision and detail a regular wooden pencil cannot. With lead size ranging from as small as 0.3mm, you can draw very
             fine lines, perfect for adding detail to any creative project.<br><br>
             <center><img src="mech.jpg" width="100px" height="100px"> </center></div>
            
        </div>
        <div class="tool" style="font-size: 20px;padding-left: 10px;display: none;">
            <div style="margin-left: -10px; color: red;height: 60px;text-align: center; background-image: linear-gradient(to bottom ,white, rgb(238, 230, 230));"><h1><b>carbon powder & Fixative spray</b></h1></div>
            <div class="content"><span class="toolhead">fixative spray –</span> A fixative is a liquid, similar to varnish, which is usually sprayed over a finished piece of artwork, usually a dry media artwork, to better preserve it and prevent smudging.<br>
                Artwork media requiring fixative include drawings done in pencil, charcoal, and pastel. An artist will often fix layers of a work in progress, in order to easily add further 
                layers. Such a technique requires a workable fixative. Fixative is most commonly available in aerosol sprays. Fixative can also come in a
                 liquid form that can be used from the bottle via a manual spray diffuser. This form is better for one's lungs and has less of an impact 
                 on the environment
                 <center><img src="fixspr.jpg" width="150px" height="150px"> </center>
                 <span class="toolhead">carbon powder –</span>Powdered charcoal is a material that consists of pulverized charcoal. Charcoal material is crushed into small powder-like pieces resulting in powdered charcoal.
                 <br>The manner in which powdered charcoal is used in a drawing is ultimately up the creativity of the artist. Mostly, it is used as a means of toning the paper. (Paper can also be toned in a similar manner by
                  applying vine charcoal to the surface and then working it in to the surface with a paper towel or chamois.
                  <center><img src="charpow.jpg" width="150px" height="150px"> </center>
                </div>
            
        </div>
    </div> 
</div>
        <div style="font-size: 24px;margin-top: 20px;">Sketchart provides all these matrial on their self plateform with a affordable price.
            <a  href="shoping.html">check it</a> <span style="color: blue; "></span>
        <center>
            <a href="shoping.html"><img style="margin-top: 10px; border: 2px solid rgb(209, 187, 187);" src="shopcar.jpg" width="200px" height="200px"></a>
        </center>
    </div>
    <div style="font-size: 20px;height: 1020px;margin-top: 20px;" >
        <nav style=" font-size: 60px;color: rgb(126, 8, 126); border-bottom: 4px solid rgb(214, 205, 205);margin-bottom: 20px;">
            Learning</nav>
            <p style="margin-left: 10px;">
        tools are useful but only when, if you have better skills.So it is much important to work on your skills first.<br>
        here we provides you tutorial and links to improove your skills.<br>
        Follow these guide lines according to your level.<br></p>
        <div style="width: 100%; height: 50px;">
            <div onclick="lvlfunc(1)" class="level">begginer</div><div onclick="lvlfunc(2)" class="level">advance</div>
        </div>
        <div class="level-container" style="height:800px ;" >
            <div class="lrncol" style="width: 48%;height: 800px; border: 1px solid rgb(179, 167, 167);;">
                <div style="width: full;height: 60px;background-image:linear-gradient(to bottom,white , rgb(214, 206, 206));"><h1>Sketching tips for a beginner</video></h1></div>
                <div style="width: full;height: 680px;margin-top: 20px;overflow-y: scroll;">
                <ol>
                    <li><h2>know your pencil</h2>
                        Having the right pencil for your sketch is essential. The hardness of the graphite is indicated on 
                        the side of the pencil: 'B' pencils are softer, 'H' are harder, and 'HB' sits in the middle – there's a big difference between a
                         4H and a 4B.<br>When you're learning how to draw, it's also worth considering using mechanical pencils alongside traditional ones.
                         Keep in mind that most mechanical pencils come with HB pre-inserted, which gives you only the middle range to work with.
                         <center><img src="big1.jpg" width="400px" height="300px"></center>
                    </li>
                    <li><h2>Try different mark-making methods</h2><br>
                        There are plenty of sketching techniques to help you achieve different styles and effects. Above are some examples demonstrating different
                         ways to create form and depth. "It’s important to experiment and find what works best for you, to not only complement but enhance your 
                         style," explains Von Rueden. "While I prefer smoother value transitions with the pencil strokes blending in against a thin outline, you may be more partial to cross-hatching against a bold outline."
                         <center><img src="big2.jpg" width="400px" height="300px"></center>
                    </li>
                    <li><h2>Avoid smudging</h2>
                        Use an extra piece of paper under your hand to avoid smudging your work
                       When shading, use an extra piece of paper underneath your hand.
                       <center><img src="big3.jpg" width="400px" height="300px"></center>
                    </li>
                    <li><h2> Differentiate different textures</h2>
                        To show different textures within your sketch, you need to adjust your technique.A good starting point is to consider if the texture is rough or smooth, and then if it absorb or reflects light.
                        <center><img src="big4.jpg" width="400px" height="300px"></center>
                    </li>
                </ol></div>
            </div>
            <div class="lrncol" style="margin-left: 1%; width: 49%;border: 1px solid rgb(165, 149, 149);">
                <div style="width: full;height: 60px;background-image:linear-gradient(to bottom,white , rgb(214, 206, 206));"><h1>Video tutorials</video></h1></div>
                <div style="width: 95%; height: 65%;margin-left: 18px;margin-bottom: 20px;">
                <video  controls class="video" width="100%" height="100%" poster="logo2.jpeg">
                    <source src="bigvid1.mp4" type="video/mp4">
                </video>
                <video controls class="video" width="100%" height="350px" style="display: none;">
                    <source src="bigvid2.mp4" type="video/mp4">
                </video>
                <video controls class="video" width="100%" height="100%"style="display: none;">
                    <source src="bigvid3.mp4" type="video/mp4">
                </video></div>
                <span style="font-size: 20px;margin-left: 20px;color: red;">basic tutorials for a beginner</span>
                <ul>
                    <li onclick="func(1)">Learn to draw flying object</li>
                    <li onclick="func(2)">Face tutorial</li>
                    <li onclick="func(3)">Draw a realistic eye</li>
                </ul>
                <span style="font-size: 20px;margin-left: 20px;color: red;">youtube links</span>
                <ul>
                    <a href="https://www.youtube.com/watch?v=36_AwMmPWxs"><li>basics for a  portrait</li></a>
                    <a href="https://www.youtube.com/watch?v=NJHwXoNU3lo"><li>how to draw portrait</li></a>
                    <a href="https://www.youtube.com/channel/UCcc1rEeoxyi4SJWPqhvM7Ww"><li>how to draw realistic hair</li></a>
                    <a href="https://www.youtube.com/watch?v=9H96bljWcpA"><li>how to draw realistic lips</li></a>
                </ul>
            </div>
        </div>
            <div class="level-container" style="width:100%;height: 800px; display: none;border: 1px solid rgb(224, 203, 203);">
                <ul class="advancelist" style="height: 50px;width: 100%;" >
                    <li onclick="advfunc(1)">eye</li>
                    <li onclick="advfunc(2)">hair</li>
                    <li>clothes</li>
                    <li>ear</li>
                    <li>nose</li>
                </ul>
                <div class="part" style="width:100%;margin-top: 20px; height: 708px;">
                    <div class="part1" style="margin-top: 20px; width: 300px;height: 330px;"><img src="eye.jpg" width="100%" height="250px"></div>
                    <div class="part1" style="padding-left: 20px; margin-top: -330px;float: right; font-size: 20px; width: 1000px;height: 330px;">
                        Take a look at the pupil(the black area in the center), this area contracts in size when light hits it. The area around the pupil is the iris, this is the area that gives us our eye color. As you can see its not just a blotch of brown, its made up highlights and shadows and this is what we will concentrate on. Adding the right shadows and highlights gives they eye depth and life. All eyes are different and you will see that adding different highlights in different areas gives different effects. The white dot close to the eye is the reflection of light source, it can be big or large, it depends if the person is indoor or outdoor. Another thing you must take into consideration is the shape of the eye. The surface of the eye is not flat, it has a curve to it. So taking that into consideration when drawing highlights will give the eye much more dimension. These are the tools that i used.
                        <br><br><span style="color: blue;font-size: 24px;">Tools used</span>
                        <ul>
                            <li>2h wood cased pencil</li><li>2b 0.5 Mechanical Pencil</li><li>Smooth bristol paper</li>
                        </ul>
                    </div>
                    <div style="height: 210px;width: 100%; ">
                    <div class="eyestp" style="margin-left: 20px;">
                       <img src="eyestp1.jpg" width="150px" height="150px">
                       <span >step1</span> 
                    </div>
                    <div class="eyestp">
                        <img src="eyestp3.jpg" width="150px" height="150px">
                        <span style=" ">step2</span> 
                     </div>
                     <div class="eyestp">
                        <img src="eyestp4.jpg" width="150px" height="150px">
                        <span >step3</span> 
                     </div>
                     <div class="eyestp">
                        <img src="eyestp5.jpg" width="150px" height="150px">
                        <span>step4</span> 
                     </div>
                     <div class="eyestp">
                        <img src="eyestp6.jpg" width="150px" height="150px" style="">
                        <span>step5</span> 
                     </div>
                     <div class="eyestp">
                        <img src="eyestp7.jpg" width="150px" height="150px" style="">
                        <span >step6</span> 
                     </div>
                     <div class="eyestp">
                        <img src="eyestp8.jpg" width="150px" height="150px" style="">
                        <span >step7</span> 
                     </div>
                     <div class="eyestp">
                        <img src="eyestp9.jpg" width="150px" height="150px" style="">
                        <span >step8</span>
                     </div>
                    </div>
                     <div style="height: 80px;">
                     <nav style="margin-left: 20px; margin-top: 20px; font-size: 25px;">for video tutorial </video></nav>
                        <a href="https://www.youtube.com/results?search_query=how+to+draw+realistic+eyes"><span style="font-size: 30px;margin-left: 20px;color: blue;" >click here</span></a>   
                     </div>
                </div>


                <div class="part" style="width:100%;margin-top: 20px; height: 708px;display: none;">
                    <div class="part1" style="margin-top: 20px; width: 300px;height: 330px;"><img src="hair.jpg" width="100%" height="250px"></div>
                    <div class="part1" style="padding-left: 20px; margin-top: -330px;float: right; font-size: 20px; width: 1000px;height: 330px;">
                        <h2 style="margin-top: -10px;"> some essential tips for drawing hair:</h2>
                        <ul style="margin-top: -10px;">
                            <li>The pencil strokes always replicate the hair’s direction and the length.</li>
                            <li>The color of the hair is determined by how dark or how light your pencil lines are.</li>
                            <li>A band of light is created in the hair anytime there is a curved area. You will see it in curls and around the circumference of the head.</li>
                            <li>Highlights are always seen on rounded or protruding areas.</li>
                            <li>Blend the paper to a gray tone before you lift highlights. This makes them look like they are on the outer surface.</li>
                        </ul>
                        <span style="color: blue;font-size: 24px;">Tools used</span>
                        <ul>
                            <li>2h,2B,4B,6B wood cased pencil</li><li>Tombow eraser, kneaded eraser</li><li>Smooth bristol paper</li>
                        </ul>
                    </div>
                    <div style="height: 210px;width: 100%; ">
                    <div class="eyestp" style="margin-left: 20px;">
                       <img src="hairstp1.jpg" width="150px" height="150px">
                       <span >step1</span> 
                    </div>
                    <div class="eyestp">
                        <img src="hairstp2.jpg" width="150px" height="150px">
                        <span style=" ">step2</span> 
                     </div>
                     <div class="eyestp">
                        <img src="hairstp3.jpg" width="150px" height="150px">
                        <span >step3</span> 
                     </div>
                     
                    
                    </div>
                     <div style="height: 80px;">
                     <nav style="margin-left: 20px; margin-top: 20px; font-size: 25px;">for video tutorial </video></nav>
                        <a href="https://www.youtube.com/channel/UCcc1rEeoxyi4SJWPqhvM7Ww"><span style="font-size: 30px;margin-left: 20px;color: blue;" >click here</span></a>   
                     </div>
                </div>
            </div>



            
                
    </div>
    <div style="font-size: 20px; height: 1700px;width: 100%;margin-top: 20px;">
        <nav style=" font-size: 60px;color: rgb(126, 8, 126); border-bottom: 4px solid rgb(214, 205, 205);margin-bottom: 20px;">
            Inspiration</nav>
        Inspiration is much important for learning new thingg. Here we introduce you some artist.<br>
        <div class="artist">
            <div style="" class="artigal">
            <img src="arti1_1.png" width="320px" height="320px"></div>

            <div style="width: 653px;border: 1px solid rgb(161, 152, 152);height: 318px;" class="artigal">
                <div style="display: inline;" class="pic">
                    <img src="artist1.png" width="319px" height="318px">
                </div>
                <div class="pic" style="float:right;padding-left: 10px;    width: 310px; height: 318px;">
                    <span style="color: rgb(85, 18, 241);font-size: 24;">Name : </span>Nasim<br><br>
                    <span style="color: rgb(85, 18, 241);font-size: 24;">Country : </span>Iran mashaad<br><br>
                    <span style="color: rgb(85, 18, 241);font-size: 24;">Master of Architecture</span><br><br>
                    <span style="color: rgb(85, 18, 241);font-size: 24;">Instagram handle : </span>na30mart<br><br>
                    <a href="https://www.instagram.com/na30mart/?hl=en"><img src="iconinsta.jpg" width="50px" height="50px"></a>

                </div>
            </div>
            <div style="" class="artigal">
                <img src="arti1_2.png" width="320px" height="320px"></div>
                <div style="" class="artigal">
                    <img src="arti1_3.png" width="320px" height="320px"></div>
                    <div style="" class="artigal">
                        <img src="arti1_4.png" width="320px" height="320px"></div>
                        <div style="" class="artigal">
                            <img src="arti1_5.png" width="320px" height="320px"></div>

                                <div style="" class="artigal">
                                    <img src="arti1_6.png" width="320px" height="320px"></div>
                                    
         </div>

         <div class="artist" style="margin-bottom: 20px;">
            <div style="" class="artigal">
            <img src="arti2_1.png" width="320px" height="320px"></div>

            <div style="width: 653px;border: 1px solid rgb(161, 152, 152);height: 318px;" class="artigal">
                <div style="display: inline;" class="pic">
                    <img src="pic2.png" width="319px" height="318px">
                </div>
                <div class="pic" style="float:right;padding-left: 10px;    width: 310px; height: 318px;">
                    <span style="color: rgb(85, 18, 241);font-size: 24;">Name : </span>Ankita Mahta<br><br>
                    <span style="color: rgb(85, 18, 241);font-size: 24;">Country : </span>Uthrakhand, India<br><br>
                    <span style="color: rgb(85, 18, 241);font-size: 24;">Instagram handle : </span>begginers_archives<br><br>
                    <a href="https://www.instagram.com/beginners__archives/?hl=en"><img src="iconinsta.jpg" width="50px" height="50px"></a><br>
                    <span style="font-size: 16px;color: greenyellow;">She has a you tube channel espacially for begginers</span><br>
                    <a href="https://www.youtube.com/watch?v=9H96bljWcpA&feature=youtu.be"><img src="iconyou.png" width="50px" height="50px"></a>
                </div>
            </div>
            <div style="" class="artigal">
                <img src="arti2_2.png" width="320px" height="320px"></div>
                <div style="" class="artigal">
                    <img src="arti2_3.png" width="320px" height="320px"></div>
                    <div style="" class="artigal">
                        <img src="arti2_4.png" width="320px" height="320px"></div>
                        <div style="" class="artigal">
                            <img src="arti2_5.png" width="320px" height="320px"></div>

                                <div style="" class="artigal">
                                    <img src="arti2_6.png" width="320px" height="320px"></div>
                                    
         </div>
         Some more artists
         <ul>
         <li><span style="font-size: 24px;color: rgb(95, 95, 102);">Arinze stanely </span>from south africa<span style="font-size: 14px; color: rgb(104, 161, 19);">  176k instagram follower</span> 
         <a href="https://www.instagram.com/arinze/?hl=en"><span style="color: blue;">check profile</span></a></li>
         <li><span style="font-size: 24px;color: rgb(95, 95, 102);">Naaz </span>from mumbai, India<span style="font-size: 14px; color: rgb(104, 161, 19);">  22k instagram follower</span> 
            <a href="https://www.instagram.com/naazart/?hl=en"><span style="color: blue;">check profile</span></a></li>
        <li><span style="font-size: 24px;color: rgb(95, 95, 102);">Vaibhav Tiwari </span>from mumbai, India<span style="font-size: 14px; color: rgb(104, 161, 19);">  29k instagram follower</span> 
            <a href="https://www.instagram.com/vaibhav_sketches/?hl=en"><span style="color: blue;">check profile</span></a></li><br>
        </ul>
    </div>

    <a href="#top"><center><div class="top" style="height: 50px ;border: 1px solid black; margin-top: 30px; width:100%; color:white;background-color: rgb(90, 85, 85);"> back to top</div></center></a>
    <div class="last" >
        <div class="part2" style="margin-left: 200px;"><p><b>Get to know as</b></p><p style="color: rgb(206, 195, 195);">
            <a href="about.html"> about us</a><br><br>press releases<br><br>gift a smile</p></div>
    
        <div class="part2">
            <p><b>Connect with us</b></p>
            <img  src="iconfb.jpg" width="50px" height="50px">
             <img style="margin-left: 10px;" src="icontw.png" width="50px" height="50px">
            <img style="margin-left: 10px;" src="iconinsta.jpg" width="50px" height="50px">
        </div>
        <div class="part2" style="margin-left: 50px;">
            <p><b>Make money with us</b></p><p </p><p style="color: rgb(206, 195, 195);">>sell on sketchart<br><br>sell under sketchart accelerator<br><br>addvertisement on sketchart</p>
        </div>
        <div class="part2" style="margin-left: 50px;">
            <p><b>Let us help you</b></p><p style="color: rgb(206, 195, 195);">your account<br><br>Return center<br><br>100% purchase protection</p>
        </div>
    </div>
    <div style="border: 1px solid rgb(204, 191, 191); width: 100%;height: 60px;background-color:rgb(39, 36, 36);">
        <p style="color: rgb(235, 228, 228);float: right;margin-right: 30px">Made in India</p>
        <img src="logo.jpeg" width="30px" height="30px" style="float: right;margin-right: 10px;margin-top: 10px;">
        <center><p style="color:rgb(235, 228, 228) ;">Copyright © 2020 All Rights Reserved. NIT Kurukshetra | Designed and developed by Gaurav Saini</p></center>
    </div>
    
    

        <script>
             function ftool(n)
        {
            var i,j;
           
            var slide=document.getElementsByClassName("tool");
            for(i=0;i<slide.length;i++)
            {
                slide[i].style.display="none";
            }
            slide[n-1].style.display="block";
            
        }
        function func(n)
        {
            var i;
            var vid=document.getElementsByClassName("video");
            for(i=0;i<vid.length;i++)
            {
                vid[i].style.display="none";
                vid[i].pause();
            }
            vid[n-1].style.display="block";
            vid[n-1].play();
        }
        function lvlfunc(n)
        {
            var i;
            var x=document.getElementsByClassName("level-container");
            for(i=0;i<x.length;i++)
            {
                x[i].style.display="none";
            }
            x[n-1].style.display="block";
        }
        function advfunc(n)
        {
            var i;
            var x=document.getElementsByClassName("part");
            for(i=0;i<x.length;i++)
            {
                x[i].style.display="none";
            }
            x[n-1].style.display="block";
        }
        function scrl(n)
        {
            var i;
            
            scrollTo(0,n);
        }
        </script>
        

    
</body>
