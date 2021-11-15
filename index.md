<style>
.markdown-body h1 {
    border-bottom: none
}
.markdown-body h2 {
    border-bottom: 2px solid grey;
}
.markdown-body {
    border-bottom: 2px solid black;
    padding-left: 20px !important;
    padding-right: 20px !important;
    box-shadow: 5px 2px 2px grey;
    background: white;
}
body {
    background: #c1bebe;
}
</style>

<div>
    <br><br><br>
    <h1 style="text-align:center;"><b>Finding Stars from Fireworks: ImprovingNon-Cooperative Iris Tracking</b></h1>
<!--     <p style="font-size:20px;text-align:center;"><b>Improving Non-Cooperative Iris Tracking</b></p> -->
</div>





## **Overview**

We  revisit  the  problem  of  iris  tracking  with  RGBcameras, which aims to obtain the iris contours from the capturedeye  images.  We  find  the  reason  that  limits  the  performanceof  the  state-of-the-art  method  in  more  general  non-cooperativeenvironments,  which  prohibits  a  wider  adoption  of  this  usefultechnique in practice. We reason that because the iris boundarycould  be  inherently  unclear  and  blocked,  and  its  pixels  occupyonly  an  extremely  limited  percentage  of  those  on  the  entire  eyeimage,  similar  to  the  stars  hidden  in  fireworks,  we  should  nottreat the boundary pixels as one class to conduct an end-to-endrecognition  directly.  Thus,  we  propose  to  learn  features  fromiris and sclera regions first, and then leverage entropy to sketchthe  thin  and  sharp  iris  boundary  pixels,  where  we  can  tracemore  precise  parameterized  iris  contours.  In  this  work,  we  alsocollect a new data set by smart phone with 22K eye images fromvideo clips. We annotate a subset of 2K images, so that the labelpropagation  can  be  applied  to  enhance  the  system  performancefurther. Extensive experiments over both public and our data setsshow  that  our  method  outperforms  the  state-of-the-art  method.Results  also  indicate  that  our  method  can  improve  the  coarselylabeled data to enhance the iris contour’s accuracy and supportthe  downstream  application  better  than  the  prior  method.

## Demo Video



<iframe width="560" height="315" src="https://www.youtube.com/embed/Mq2oSL2LuAU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## **MobileIris Dataset**

A dataset for both iris tracking and gaze estimation.
Coming soon...

<br><br><br><br><br><br><br>

<br>

<br>

