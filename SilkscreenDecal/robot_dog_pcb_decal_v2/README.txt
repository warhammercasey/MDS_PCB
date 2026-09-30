Robot-dog decal v2 - 20 x 15 mm (1:1 scale in the SVGs)

dog_decal_silkscreen.svg / _1200dpi.png               -> F.SilkS (black = print)
dog_decal_copper_and_mask_opening.svg / _1200dpi.png  -> F.Cu AND F.Mask (same art)
preview_*.png                                          -> look on blue / black / green mask

Design rules used: every silk line and mask gap is >= 0.18 mm; silk is pulled
back 0.20 mm from exposed copper. Smallest copper feature is 0.36 mm.
Check your fab's minimum silk width - if it's 0.2 mm+, the knee pin holes are
the first thing that may fill in (harmless).

KiCad: File > Import > Graphics (SVG, scale 1.0) onto each layer, or
Image Converter at 1200 DPI. Put the copper art on both F.Cu and F.Mask,
leave it on no net, and keep normal clearance to pours.
