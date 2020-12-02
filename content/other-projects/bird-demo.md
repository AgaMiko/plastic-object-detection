+++
# Hero widget.
widget = "hero"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 100  # Order that this section will appear.

title = ""

# Hero image (optional). Enter filename of an image in the `static/img/` folder.
# hero_media = "hero.png"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  # color = "navy"
  
  # Background gradient.
  gradient_start = "#f8ad9d"
  gradient_end = "#f08080"
  
  # Background image.
 image = "birds-project.png"  # Name of image in `static/img/`.
 image_darken = 0.4  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
 image_size = "cover"  #  Options are `cover` (default), `contain`, or `actual` size.
 image_position = "right"  # Options include `left`, `center` (default), or `right`.
 image_parallax = true  # Use a fun parallax-like fixed background effect? true/false
  
  # Text color (true=light or false=dark).
  text_color_light = true

# Call to action links (optional).
#   Display link(s) by specifying a URL and label below. Icon is optional for `[cta]`.
#   Remove a link/note by deleting a cta/note block.
[cta]
  url = "https://towardsdatascience.com/sound-based-bird-classification-965d0ecacb2b"
  label = "Read more about"
  icon_pack = "fab"
  icon = "readme"
  
[cta_alt]
  url = "https://wimlds.voicelab.ai/"
  label = "Test it yourself"

# Note. An optional note to show underneath the links.
[cta_note]
  label = "Find out what bird is singing nearby!"
+++


