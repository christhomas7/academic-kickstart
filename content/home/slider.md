+++
widget = "slider"  # Use the Slider widget
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 40  # Order that this section will appear.

# ... Put Your Section Options Here (section position etc.) ...

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = 3000

# Minimum slide height.
# Specify a height to ensure a consistent height for each slide.
height = "400px"

# Slides.
# Duplicate an `[[item]]` block to add more slides.
[[item]]
  title = "strength and power"
  content = "assessment, intrpretation, intervention"
  align = "center"  # Choose `center`, `left`, or `right`.
  overlay_color = "#404040"  # An HTML color value. Optional
  overlay_img = "slider/strength_power.png"  # relative to `static/img/`
  overlay_filter = 0.4  # Darken the image. Value in range 0-1.
  cta_label = "project details"
  cta_url = "/project/strength_power/"
  cta_icon_pack = "fas"
  cta_icon = "book-reader"

  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  #cta_label = "Get Academic"
  #cta_url = "https://sourcethemes.com/academic/"
  #cta_icon_pack = "fas"
  #cta_icon = "graduation-cap"

[[item]]
  title = "change of direction"
  content = "ACL injury, sidestepping, neuromuscular risk factors"
  align = "center"
  overlay_color = "#404040"  # An HTML color value.
  overlay_img = "slider/cod.png"  # relative to `static/img/` folder.
  overlay_filter = 0.4  # Darken the image. Value in range 0-1.
  cta_label = "project details"
  cta_url = "/project/cod/"
  cta_icon_pack = "fas"
  cta_icon = "book-reader" 
  

[[item]]
  title = "performance assessment"
  content = "acquisition and interpretation of data"
  align = "center"  # Choose `center`, `left`, or `right`.
  overlay_color = "#404040"  # An HTML color value. Optional
  overlay_img = "slider/perfassessment.png"  # relative to `static/img/`
  overlay_filter = 0.4  # Darken the image. Value in range 0-1.
  cta_label = "project details"
  cta_url = "/project/perf_assess/"
  cta_icon_pack = "fas"
  cta_icon = "book-reader"


[[item]]
  title = "asymmetry"
  content = "asessment and monitoring"
  align = "center"  # Choose `center`, `left`, or `right`.
  overlay_color = "#404040"  # An HTML color value. Optional
  overlay_img = "slider/asymmetry.png"  # relative to `static/img/`
  overlay_filter = 0.4  # Darken the image. Value in range 0-1.
  cta_label = "project details"
  cta_url = "/project/asymmetry/"
  cta_icon_pack = "fas"
  cta_icon = "book-reader"  

+++
