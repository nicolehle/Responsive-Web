# Responsive-Web
Building Responsive Web Designs based on Free Code Camp's coding challenge. 

<strong>1. Build a Tribute-page (HTML, CSS)</strong>
+ Goals of the project

-<i>Building a page that classes and ids in html elements corresponding with CSS.</i> <br><br>

-<i>Making 'img' element responsively resize, relative to the width of its parent element, whitout exceeding its original size.</i>   

#img-div {
  margin: 0 auto;
  width: 640px;
  height: 480px;
}
=> Setting a size of parents of image element by 640 x 480.

#image {
  display: block;
  text-align: center;
  max-width: 100%;
}
=> Using 'max-width' elements to achieve responsive image size.

<br>

-<i>Making margin of text-section responsively resize with mediaquery.</i> 

section {
  margin: 50px 150px;
  line-height: 1.5rem;
}

@media only screen and (max-width: 500px) {
  section {
    margin: 30px;
  }
}

