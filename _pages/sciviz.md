---
permalink: /sciviz/
title: "SciViz"
---

In order to better communicate the science done the supercomputing resources of the [Argonne Leadership Computing Facility](https://www.alcf.anl.gov/), I helped develop a pipeline to leverage VFX software and high quality rendering tools on HPC resources. Since datasets were often hundreds of gigabytes, if not terabytes, being able to use these tools on the supercomputers was crucial. 

## Videos

{% include video id="M0S7ihKdCRM" provider="youtube" %}
"Visualizing Turbulent Flow in an Internal Combustion Engine (ICE)" was the first movie we created with this method. I presented this video, along with a slide show explaining the technical details of the pipeline, at the [PEARC21](https://pearc.acm.org/pearc21/) Visualization Showcase. Texturing and modeling was done in AutoDesk Maya, and the final video was rendered in parallel with the V-Ray render engine. 


<br>
{% include video id="0DSk1wPc_cE" provider="youtube" %}
"Visualizing the Supernova Explosion of a 25-Solar-Mass Star and the Simultaneous Birth of a Neutron-Star" was shown the following year at the SC22 SciViz Showcase. 

<br>
{% include video id="Nl3m2Zz61D4" provider="youtube" %}
In addition to Maya, I have also replicated this pipeline with Houdini for texturing, modeling, and scene generation. 

## Still Images


![Bloodflow]({{ site.url }}{{ site.baseurl }}/assets/images/sciviz/took-forever.png)
{: .full}

![Bloodflow]({{ site.url }}{{ site.baseurl }}/assets/images/sciviz/1ocio_blinn.png)
{: .full}
Above are volumetric renderings showing simulated bloodflow through an eye. These images were created with Maya and V-Ray. Simulation dataset provided by [Dr. Jifu Tan](https://sites.google.com/site/tanjifu/) of Northern Illinois University. 

<br>
![Star]({{ site.url }}{{ site.baseurl }}/assets/images/sciviz/high_res_dpi300.png)
{: .full}
A still from from the Supernova Explosion visualization. 

<br>
![TRB]({{ site.url }}{{ site.baseurl }}/assets/images/sciviz/hbrynt2_2023_2000px.webp)
{: .full}
![TRB]({{ site.url }}{{ site.baseurl }}/assets/images/sciviz/renders0001.png)
{: .full}
Above are visualizations of a suspended fluid within a Rayleigh–Bénard convection rendered in Blender and ParaView. This visualization project was awarded an Honorable Mention at the University of Illinois Chicago [Images of Research](https://grad.uic.edu/funding-awards/the-image-of-research/ior-winners-hm-23/) Competition, and was shown at the APS [Gallery of Fluid Motion](https://gfm.aps.org/meetings/dfd-2023/6504c509199e4c16c66a9562). Fluid simulation provided by [Dr. Parisa Mirbod and Abbas Moradi Bilondi.](https://themirbod.lab.uic.edu/)

