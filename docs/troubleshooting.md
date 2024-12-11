# troubleshooting

## PoseHeadingDegrees is missing

Camera compass needs to be callibrated.  See
article:

[GPS Data/Image Pano Heading - Missing PoseHeadingDegrees - RICOH THETA X](https://community.theta360.guide/t/gps-data-image-pano-heading-missing-poseheadingdegrees-ricoh-theta-x/9822?u=craig)

## PosePitchDegrees and PoseRollDegrees always zero

To get the PosePitch and PoseRoll, the camera topBottomCorrection
needs to be disabled.

With the newer THETA X firmware, topBottomCorrection can
be enabled and disabled from the body of the camera.

For API use see this article:

[RICOH THETA Disable Auto-Level topBottomCorrection for Interval Shooting](https://community.theta360.guide/t/ricoh-theta-disable-auto-level-topbottomcorrection-for-interval-shooting/9338/2)
