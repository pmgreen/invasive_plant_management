# Invasive Plant Management

[QField](https://qfield.org/) app to identify, and to track removal of, invasive plants. 

The main layer is `clipboard` (to mimic using a clipboard in the field).
There are two modes:
 - observation
 - removal
 
If `removal` is selected, methods of removal are displayed, e.g. `wrench` (for weed wrench)

<img width="20%" alt="map_screenshot_20260516-171736 QField" src="https://github.com/user-attachments/assets/355bcbad-e935-4892-b959-e3d1899dacc8" />
<img width="20%" alt="form_screenshot_20260515-002136 QField" src="https://github.com/user-attachments/assets/8721d405-f4ab-4bc4-98f2-69e71c0c72a4" />


### Target species

Species are defined within the QGIS app as a value relation widget in the attributes form of the clipboard layer.

| common |	latin |
 -- | --
privet |	Ligustrum sinense
autumn olive	| Elaeagnus umbellata 
multiflora rose | Rosa multiflora
bush honeysuckle	| Lonicera maackii
vine honeysuckle	| Lonicera japonica
kudzu	| Pueraria montana
english ivy	| Hedera helix
wintercreeper	| Euonymus fortunei
burning bush	| Euonymous alatus
stilt grass	| Microstegium
bush clover	| Lespedeza cuneata
tree of heaven	| Ailanthus altissima
mimosa	| Albizia julibrissin
mullein	| Verbascum thapsus

---

This is a [Kart](https://kartproject.org/) repository, enabling version control and collaboration. To check it out, follow this [quick start](https://docs.kartproject.org/en/latest/pages/quick_guide.html#quick-guide) guide to install Kart and then either use the [QGIS Kart plugin](https://plugins.qgis.org/plugins/kart/) or the command line to clone this repo. (Note: the [kart plugin](https://plugins.qgis.org/plugins/kart/) only works with certain versions of QGIS but you could always use the command line.) 
