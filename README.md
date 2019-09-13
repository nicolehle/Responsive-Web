# Responsive-Web
Building Responsive Web Designs based on Free Code Camp's coding challenge. 

<strong>1. Build a Tribute-page (HTML, CSS)</strong>
+ Challenges and Solutions/Efficiency

1.<i>Building a page that classes and ids in html elements corresponding with CSS.</i> <br><br>

-<i>Make 'img' element responsively resize, relative to the width of its parent element, whitout exceeding its original size.</i>   

Set a size of parents of image element by 640 x 480.

#img-div {
  margin: 0 auto;
  width: 640px;
  height: 480px;
}

Use 'max-width' elements to achieve responsive image size.

#image {
  display: block;
  text-align: center;
  max-width: 100%;
}


<br>

2.<i>Make margin of text-section responsively resize with mediaquery.</i> 

section {
  margin: 50px 150px;
  line-height: 1.5rem;
}

@media only screen and (max-width: 500px) {
  section {
    margin: 30px;
  }
}


----------------------------------------------------------------------------------------------------
<strong>2. Build a Survey-form (HTML, CSS)</strong>
+ Challenges and Solutions/Efficiency

1.<i>Use different types of input.</i> <br>
 
2.<i>Condider UX for arranging checkbox elements center but with same start point. </i> 

-Set text-align to the left while other elements are centered to give checkbox look organized. Then center the element as adjusting margin-left

ul {
  margin-left: 37%;
  text-align: left;
}

<br>


3.<i>Imporve efficiency applying css on each div block by distinguishing reusable variables.</i>

-Each div has rowtab class that provides same margin element making the page consistency as well.

.rowtab {
  margin: 50px 0;
}

.rowtab-second {
  margin: 15px 0 0 10px;
}
