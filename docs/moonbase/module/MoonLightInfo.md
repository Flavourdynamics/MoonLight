# MoonLight info

<img width="350" src="https://github.com/user-attachments/assets/13719483-cf75-49be-8b25-97d379e5c126" />

Shows info about the physical and virtual layer

* **NrOfLights**: the nr of lights defined in the layer
* **Channels per light**: e.g. normal RGB strip/panel is 3 channels per light
* **Chipset**: FastLED chipset defined (for FastLED hardcoded in the firmware ...)
* **Size**: the outer bounds of the fixture, e.g. for a 16x16 panel it is 16x16x1
* **Layers**: The virtual layers defined (currently only 1)
    * **NrOfLights and size**: virtual layer can differ from the physical layer (.e.g when mirroring it is only half)
    * **Color#**: the number of lights which are not mapped to a physical pixel (color is stored in the mapping table)
    * **Phys#**: The number of lights which have a 1:1 mapping between physical and virtual (if no modifier all is phys)
    * **Mapping table indexes**: The number of physical lights which are in a 1:many mapping
    * **Phys M**: the number of virtual lights which are in a 1:many mapping
    * **Nodes#**: The number of nodes assigned to a virtual layer (currently all)
