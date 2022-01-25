---
widget: slider
headless: true  # This file represents a page section.

title: Carousal
subtitle: main page
weight: 1  # section position on page
design:
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns: '1'

# ... Put Your Section Options Here (section position etc.) ...

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval: false

# Minimum slide height.
# Specify a height to ensure a consistent height for each slide.
height: 650px


item:
  - title: Remote Sensing & Spatial Analytics
    content: 'Information Technology University of the Punjab (ITU)'
    # Choose `center`, `left`, or `right` alignment.
    align: center
    # Overlay a color or image (optional).
    #   Deactivate an option by commenting out the line, prefixing it with `#`.
    #overlay_color: '#666'  # An HTML color value.
    overlay_img: pakistan_snapshot_01-25-2022_18_56_56.jpeg  # Image path relative to your `assets/media/` folder
    #overlay_filter: 0.25  # Darken the image. Value in range 0-1.
    # Call to action button (optional).
    #   Activate the button by specifying a URL and button label below.
    #   Deactivate by commenting out parameters, prefixing lines with `#`.
    #cta_label: Download my app
    #cta_url: 'https://example.org'
    #cta_icon_pack: fas
    #cta_icon: graduation-cap
  - title: Left
    content: 'I am left aligned 😄'
    align: left
    overlay_color: '#555'
    overlay_img: ''
    overlay_filter: 0.5
  - title: Right
    content: 'I am right aligned 😄'
    align: right
    overlay_color: '#333'
    overlay_img: ''
    overlay_filter: 0.5
---
