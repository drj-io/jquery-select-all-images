# jquery-select-all-images
Just a quick snippet to select all images from chrome console.


```
$('.theimages').remove();
$('body').append("<div class='theimages'></div>");
$("img").each(function() {  
  $('.theimages').append('<li>'+this.src+'</li>');
}); 
```
