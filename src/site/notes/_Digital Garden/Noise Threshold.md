---
{"dg-publish":true,"permalink":"/digital-garden/noise-threshold/","noteIcon":"1","created":"2025-04-09T17:17:11.872-04:00","updated":"2025-04-09T17:43:41.931-04:00"}
---

Realistically this should be called Adaptive sampling. It's essentially when blender decides to stop rendering certain sections because they are below the noise threshold.  The Naïve way to increase quality on a noisy texture but that increases the samples everywhere. Manipulating the noise threshold value allows blender to determine how to handle the render on a per pixel level. 

#### Sources
[Blender Render Optimization- Noise Threshold](https://blendergrid.com/learn/articles/blender-render-optimization-noise-threshold)