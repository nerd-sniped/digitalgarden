---
{"dg-publish":true,"permalink":"/digital-garden/topological/","tags":["DigitalGarden"],"noteIcon":"1","created":"2025-04-13T16:50:39.700-04:00","updated":"2025-04-13T17:48:52.194-04:00"}
---

Topography is the study of forms. focused on the surface elements. in the context of [[3D modeling\|3D modeling]] Its a type of editing that directly modifies the surface of a 3D form. This is in contrast to [[Boundary Representation\|Boundary Representation]] modeling which modifies the equations that define a enclosed volume.  

In layman's terms, usually Topological modeling is used for organic flowing shapes, and [[Boundary Representation\|B-REP]] Modeling is used for production work and or [[Hard Surface\|Hard Surface]] Modeling. 

 Blender is a common example of a Topographic modeling program, while fusion360 or solidworks would primarily be Boundary Representation modelers.  

In topological modeling, a decision needs to be made fairly early on; [[_Digital Garden/Quads\|Quads]] or [[_Digital Garden/Triangles\|Triangles]].  Most modelers insist on quads being superior, but there are good cases for both.  

Historically Triangles have been used.  This largely is due to memory optimization.  A triangle defines a plane, and can be defined using only 3 points.   

A Quad can represent MANY different surfaces depending on the  curvature. It requires more information to properly define a shape using quads, but the shape is much smoother.   This is why modelers tend to prefer them. They contain much better surface information, instead of a relatively low poly collection of planes, you can define surfaces with known curvature, which makes renders, shaders, and other *quality* focused elements run better.  

Additionally Triangles are harder to subdivide.  The "flow" of a surface is much easier to parse/understand intuitively when the surface is a quad. 

You can Split a quad by drawing two lines from adjacent mid points.
# Excalidraw Data

## Text Elements
