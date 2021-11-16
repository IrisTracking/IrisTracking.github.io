<style>
.markdown-body h1 {
    border-bottom: none
}
.markdown-body h2 {
    border-bottom: 2px solid grey;
}
.markdown-body {
    border-bottom: 2px solid black;
    padding-left: 65px !important;
    padding-right: 65px !important;
    box-shadow: 5px 2px 2px grey;
    background: white;
}
body {
    background: #c1bebe;
}
</style>
<div>
    <br><br><br>
    <h1 style="text-align:center;"><b>Finding Stars from Fireworks: Improving <br>Non-Cooperative Iris Tracking</b></h1>
<!--     <p style="font-size:20px;text-align:center;"><b>Improving Non-Cooperative Iris Tracking</b></p> -->
</div>






## **Overview**

In this project, we revisit the problem of iris tracking with RGB cameras, which aims to obtain the iris contours from the captured eye images. We find the reason that limits the performance of the state-of-the-art method in more general non-cooperative environments, which prohibits a wider adoption of this useful technique in practice. We reason that because the iris boundary could be inherently unclear and blocked, and its pixels occupy only an extremely limited percentage of those on the entire eye image, similar to the stars hidden in fireworks, we should not treat the boundary pixels as one class to conduct an end-to-end recognition directly. Thus, we propose to learn features from iris and sclera regions first, and then leverage entropy to sketch the thin and sharp iris boundary pixels, where we can trace more precise parameterized iris contours. In this work, we also collect a new data set by smart phone with 22K eye images from video clips. We annotate a subset of 2K images, so that the label propagation can be applied to enhance the system performance further. Extensive experiments over both public and our data sets show that our method outperforms the state-of-the-art method. Results also indicate that our method can improve the coarsely labeled data to enhance the iris contour's accuracy and support the downstream application better than the prior method.

## Demo Video



<iframe width="560" height="315" src="https://www.youtube.com/embed/Mq2oSL2LuAU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## **MobileIris Dataset** and Code
Our new iris tracking dataset ***MobileIris*** and the corresponding code will be released soon.

<br><br><br><br><br><br><br>

<br>

<br>

