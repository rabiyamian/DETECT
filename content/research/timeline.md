+++

widget = "blank" 
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 10  # Order that this section will appear.

title = "Timeline"
subtitle = ""

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "2"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  # color = "navy"
  
  # Background gradient.
  # gradient_start = "DarkGreen"
  # gradient_end = "ForestGreen"
  
  # Background image.
  # image = "image.jpg"  # Name of image in `static/media/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
  # image_size = "cover"  #  Options are `cover` (default), `contain`, or `actual` size.
  # image_position = "center"  # Options include `left`, `center` (default), or `right`.
  # image_parallax = true  # Use a fun parallax-like fixed background effect? true/false
  
  # Text color (true=light or false=dark).
  text_color_light = false

[design.spacing]
  # Customize the section spacing. Order is top, right, bottom, left.
  padding = ["20px", "0", "20px", "0"]

[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++

<div class="timeline">
  <div class="container left">
    <div class="content">
      <h2>2014</h2>
      <p>Start of DETECT Project</p>
    </div>
  </div>
  <div class="container right">
    <div class="content">
      <h2>2015</h2>
      <p>DETECT 5-Week Pilot Study</p>
    </div>
  </div>
  <div class="container right">
    <div class="content">
      <h2>2015 – 2017</h2>
      <p>Wash-Out Period</p>
    </div>
  </div>
  <div class="container right">
    <div class="content">
      <h2>2017 – 2018</h2>
      <p>DETECT 1-Year Observational Study</p>
    </div>
  </div>
  <div class="container right">
    <div class="content">
      <h2>2019 to Present</h2>
      <p>DETECT Follow-Up Interviews</p>
    </div>
  </div>
</div>
