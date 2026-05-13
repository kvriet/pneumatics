---
title: Inflatables Design
layout: default
nav_order: 3
---

## Table of contents
{: .no_toc }

1. TOC
{:toc}
---

## Inflatables design
To design inflatables, think in terms of **outlines** and **internal structures**. Your device outline should always be closed, unless you want to intentionally introduce a leak into your system. 



## Working with the sealing machines
You need a formal training to use the sealing machines. After successfully completing the training, you will receive a detailed sealing manual which shows the sealing procedure in depth. 

To already become familiar with the process, see a brief overview below:


## Working with silicones and moulds
You can 3D print moulds and pour silicone into them. We call this silicone casting. 

There are a few techniques you can use:

1. Design your geometry as **one mould** with an inner structure. As long as you can pull out the inner mould from the silicone part you cast, you should be good to go. You can find and example here [link](https://www.softmodbot.com/fabrication/#resistor).
1. Design your geometry in **two halves/parts**. You make two moulds (each for one half), cast each part separately, and then glue together with some additional silicone or silicone glue (FormX). You can find an example of that method here: [link](https://softroboticstoolkit.com/book/pneunets-bending-actuator) and here [link](https://www.softmodbot.com/fabrication/#bulb).
1. Design your geometry to be glued together in **multiple steps**. You can make this quite complex. See an example of that here: [link](https://www.softmodbot.com/fabrication/#transistor_NO).
1. Design your geometry with an outer and inner mould. Print the inner mould in soluble filament (PVA or BVOH). Once the silicone has cured, demould as much as you can and put the silicone in water to dissolve the inner. See an example of that here: [link](https://www.softmodbot.com/fabrication/#bellow).


## Advanced techniques

### Connecting sealed pouches
If you leave some material around your outer seal line, you can sew pouches together as long as you don't stitch through the inflatable areas. By using this strategy, you can create multilayer devices.

### Sealing larger areas
You are normally limited to the 30x30cm printbed of the Sovol for sealing. However, you can get around this by using a larger sheet, sealing up to a certain point, moving the material, and then continuing the rest of the sealing pattern in exactly the right spot. This is tricky to achieve. The diagram below shows you one method of doing this.



