---
marp: true
html: true
paginate: true
theme: default
style: |
  section ul {
    animation: none;
  }
---

<style>
@import url('https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css');
</style>

# Mapping Ambient Vulnerabilities

<div class="columns">
<div>

*Lenka Hasova*  
Quantitative Spatial Science group
Department of Geographical Sciences
University of Bristol

<div style="display: flex; gap: 1.5rem; align-items: center; font-size: 1.1rem;">


<a href="lenka.hasova@bristol.ac.uk">
  <i class="fa-solid fa-envelope"></i> 
</a>

<a href="https://www.linkedin.com/in/lenka-ha%C5%A1ov%C3%A1-88340a88/?locale=en" target="_blank">
  <i class="fa-brands fa-linkedin"></i> 
</a>

</div>

 #
 #

![width:250](./../logos/esrc.png) ![width:250](./../logos/Bristol.png) 

</div>
<div>

![width:600](./../logos/mav_triangle.png) 

Website: [ambient-vulnerability.co.uk](https://ambient-vulnerability.co.uk/)




</div>
</div>

<style>
.columns {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 1rem;
}
</style>

----

## Air Quality **vulnerability** through peoples lives

**3 parts**: exposure, sensitivity, and adaptability make up vulnerability
**3 stages**: at home, on the move, and at work
**3 outputs**: journal article, policy briefing, interactive online outputs


#

![](./pic10.png) 



------

## **Exposure** to air pollution on the move
 

![](./pic1.jpg) 




------
## Motivation

* Commuting is often the **period of highest** pollution exposure in everyday life.
* Most large-scale air pollution research measures exposure at **fixed locations** (e.g. home, work, junctions), overlooking daily mobility.
* Policy-relevant studies of commuter exposure are often limited in spatial scale and **difficult to scale up or down**.
* Exposure “on the move” **may be** unevenly distributed across populations and places.



-------

## How
Routing with [Pandana](https://udst.github.io/pandana/) is the core, the rest is just GIS

![](./pic5.png)

------


![](./pic6.png)

-------

## Results
![](./pic7.png)
#### Pm2.5 exposure per journey per commuter **within** the region

-------

![](./pic8.png)
#### Deprivation deciles paired with the exposure deciles across **whole England**

-------

## Implications

![width:780px](./pic14.png)
##### Paired with our [previous study](https://journals.sagepub.com/doi/10.1177/23998083251344678) 

----

* ###### Deprivation is generally concentrated in urban areas.
* ###### Rural areas are often perceived as cleaner, safer, and more spacious, which can make properties more expensive.
* ###### Public transport access in rural areas is often limited
* ###### Choosing a rural location can be viewed as an adaptation strategy, trading accessibility and transport convenience for environmental and residential benefits.


![width:600px](./pic11.png) 

###### Walking to work, [your pm2.5 intake is higher than if commuting in car](https://www.sciencedirect.com/science/article/pii/S2214140522000378).


-------

## Future steps

* **Refine** and scale the simulation using more dynamic traffic and pollution data


* **Explore** how commuting patterns, socio-economics, and transport systems shape exposure inequalities


* **Relate** the findings to environmental justice and fairer transport and air quality policy

* **Expand** the study for cyclicts, walkers, children, ...




----



# Thank you!....questions?

<div class="columns">
<div>


![width:250](./../logos/esrc.png)           ![width:250](./../logos/Bristol.png) 

</div>
<div>


Website: [ambient-vulnerability.co.uk](https://ambient-vulnerability.co.uk/)




</div>
</div>

<style>
.columns {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 1rem;
}
</style>