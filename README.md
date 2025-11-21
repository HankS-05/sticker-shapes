# sticker-shapes
Sticker shapes project, started November 2025

The premise of this program is to create closed shapes out of smoothly connected copies of a curve segment.
To be smoothly connected to the previous curve, the next curve must be rotated by a certain angle according 
to the tangent at the start of the curve, and the tangent at the end of the curve, as well as the orientation
of the previous curve. This can be also be done to a flipped copy of the curve, or a different parity, which
requires a different angle of rotation. Thus to return back to the start with a smooth connection, there must
be certain relationship between the parities of the curve segments, the start tangent, and the final tangent. 
