<a href="https://juncture-digital.org"><img src="https://juncture-digital.org/images/ve-button.png"></a>

<param ve-config 
       title="How to Read Flowers in Art"
       author="Kristan Hanson"
       banner="https://upload.wikimedia.org/wikipedia/commons/thumb/9/96/Ambrosius_Bosschaert_the_Elder_%28Dutch_-_Flower_Still_Life_-_Google_Art_Project.jpg/1280px-Ambrosius_Bosschaert_the_Elder_%28Dutch_-_Flower_Still_Life_-_Google_Art_Project.jpg" 
       layout="vertical">

<!-- Entities discussed throughout the essay are typically defined before the essay text and
     are thus available in all text.  Entity identifiers (QIDs) can be found in either
     Wikipedia or Wikidata (https://www.wikidata.org)> -->
<param ve-entity eid="Q185372"> <!-- Girl with a Pearl Earring painting -->
<param ve-entity eid="Q41264"> <!-- Johannes Vermeer -->
<param ve-entity eid="Q221092"> <!-- Mauritshuis -->
<param ve-entity eid="Q36600"> <!-- The Hague -->
<param ve-entity eid="Q60"> <!-- New York City -->
<param ve-entity eid="Q36600"> <!-- New Guinea -->
<param ve-entity eid="Q244"> <!-- Barbados -->

# Sample visual essay

This is a sample visual essay demonstrating a few key features of a Visual Essay. Additional [Documentation](https://github.com/JSTOR-Labs/juncture/wiki) and [examples](https://jstor-labs.github.io/juncture-examples) are available for reference. Information about <span data-click-image-zoomto="3338,1140,2850,2534">image interactions</span> can be found [here](https://github.com/JSTOR-Labs/juncture/wiki/Visual-Essay-Image-Tag).
<param ve-image 
       manifest="https://ids.si.edu/ids/manifest/ark:/65665/m366f8ac28cdf64aba99b33cb34f351b81">
       
# Basic usage

## Image

_Hyacinthus orientalis_ is a garden ornamental distinguish by its columnar spike of waxy flowers. Much of the hyacinth’s story, however, actually revolves around its bulb. Reconstructing this narrative reveals how the hyacinth bulb contributed to the plant’s survival in its native range over millennia, enabled its mobility in trade networks under the Ottoman Empire, and culminated in its use for forcing indoors at the French court from the mid-1740s. Today, this story can also raise awareness of the environmental impact of the Dutch flower bulb trade and the need for sustainable solutions in modern flower gardening.[^1]
<param ve-image 
       label="Girl with a Pearl Earring" 
       description="painting by Johannes Vermeer" 
       license="public domain" 
       url="https://upload.wikimedia.org/wikipedia/commons/thumb/9/96/Ambrosius_Bosschaert_the_Elder_%28Dutch_-_Flower_Still_Life_-_Google_Art_Project.jpg/1280px-Ambrosius_Bosschaert_the_Elder_%28Dutch_-_Flower_Still_Life_-_Google_Art_Project.jpg">
       <param ve-entity eid="Q157428"> <!-- Hyacinthus orientalis -->

If possible, please use digital images and other resources that are free and open access. A list of open access image collections for artworks that are out of copyright can be found [here.](https://www.apollo-magazine.com/open-access-image-libraries-a-handy-list/) Photographs of plants with a Creative Commons license can be accessed on [Openverse](https://wordpress.org/openverse/) and [iNaturalist.](https://www.inaturalist.org/) When uploading a personal image to GitHub, use a [Creative Commons](https://creativecommons.org/licenses/) license.
<param ve-image url="https://github.com/kristanmhanson/Juncture_training_2/blob/main/Flickr_CC_BY_NC_SA_2.0.jpg?raw=true" fit="cover">

Visit the [Visual Essay Image Tag](https://github.com/jstor-labs/juncture/wiki/Visual-Essay-Image-Tag) to learn about customizing image display. The region attribute (region="0,421,3192,2590") is used to show a cropped region of an image in the image viewer. And the fit attribute defines how an image will be scaled or cropped in the image viewer window.
<param ve-compare curtain manifest="https://iiif.lib.harvard.edu/manifests/drs:436030170" seq="58">
<param ve-compare manifest="https://iiif.juncture-digital.org/manifest/c5e3bb5b8f05a40314bba386bdc2df7bc32818a04dae348d0450feb3b63c5520" fit="contain">

Full digital facsimiles of select titles in the Dumbarton Oaks Rare Book Collection can be accessed [here.](https://www.doaks.org/resources/rare-books#c6-operator=or&c7-operator=or&b_start=0) You are welcome to work with our [Rare Book team](https://www.doaks.org/research/library-archives/rare-book-collection) to find something to feature.
<param ve-compare sync fit="contain" manifest="https://iiif.lib.harvard.edu/manifests/drs:436574052" seq="291">
<param ve-compare manifest="https://iiif.juncture-digital.org/manifest/c5e3bb5b8f05a40314bba386bdc2df7bc32818a04dae348d0450feb3b63c5520" fit="contain">

## Plant Specimen

Linnaeus further implored English nurseryman James Gordon for live specimens in 1772, to no avail. He was nonetheless susceptible to the awe *Dionaea* inspired, and his incredulity regarding the deadly trapping mechanism might simply be attributed to the lack of necessary empirical evidence. The flattened, dried, and inert specimens he received from correspondents failed to show the speed and precision of the lethal snap-trap in action and understandably inspired the impression of a sleeping eyelid, as Linnaeus described in his letter to Burman.
<param ve-plant-specimen jpid="10.5555/al.ap.specimen.cord00022454" label="Datura stramonium L. from Cordoba, Argentina.">

## YouTube Video

Today, black-eyed peas are grown commercially in at least 33 countries, reflecting the widespread embrace of the bean among geographically disparate peoples, places, and cultures. As acclaimed food historian and chef <span eid="Q49562413">Michael W. Twitty</span> points out: “Very few people in the modern West eat one cuisine or live within one culinary construct,” but rather enjoy a multiplicity of culinary histories.
<param ve-video id="_B6yRDDxOzw" title="What is botanical art?" author="Royal Botanic Gardens, Kew">

## Map

The work has been in the collection of the Mauritshuis in The Hague since 1902 and has been the subject of various 
literary treatments. In 2006, the Dutch public selected it as the most beautiful painting in the Netherlands.
<param ve-map center="Q36600" zoom="11" prefer-geojson>

The Frick Collection in New York City has four paintings by Vermeer. Unlike  _Girl with a Pearl Earring_, the Frick Vermeers are genre scenes. In addition to these paintings by Vermeer, the Frick Collection has works by Frans Hals, Rembrandt, and Meyndert Hobbema.
<param ve-map center="Q60" zoom="8" prefer-geojson>

## Map of Plant Mobility: Sugarcane

Kew’s [Plants of the World Online](https://powo.science.kew.org/) is a great resource for determining the native and introduced ranges of a plant such as sugarcane (_Saccharum officinarum_), which is native to New Guinea. A Plant of the World Online map can serve as the basis for creating a static map in [Map Chart](https://www.mapchart.net/world-subdivisions.html) or a dynamic one in Juncture.
<param ve-map center="Q36600" zoom="11" prefer-geojson>
<param ve-map-marker url="https://upload.wikimedia.org/wikipedia/commons/thumb/2/28/Saint_Lucy%2C_Barbados_005.jpg/640px-Saint_Lucy%2C_Barbados_005.jpg" coords="13.30, -59.63” size="129, 170” circle="true">

Custom GeoJSON files for certain countries and regions can be found on GitHub [glynnbird/countriesgeojson.](https://github.com/glynnbird/countriesgeojson) But, in some cases, you will need to create your own using [geojson.io.](https://geojson.io/#map=6/10.164/-3.988) The island nation of Barbados, to which sugarcane was introduced, is a good case in point.
<param ve-map center="Q244" zoom="5">
<param ve-map-layer geojson active url="babados.json" title="Barbados.">
<param ve-map-marker url="https://upload.wikimedia.org/wikipedia/commons/thumb/2/28/Saint_Lucy%2C_Barbados_005.jpg/640px-Saint_Lucy%2C_Barbados_005.jpg" coords="13.30, -59.63” size="129, 170” circle="true">

## Multiple viewers

Multiple viewers may be defined for a single paragraph of text. The first viewer defined is displayed as the default viewer.  
Others are selectable using icons displayed in the top right margin of the paragraph.
<param ve-image 
       manifest="https://ids.si.edu/ids/manifest/ark:/65665/m366f8ac28cdf64aba99b33cb34f351b81">
<param ve-map center="Q36600" zoom="11">

# References

[^1]: [Wikipedia: Girl with a Pearl Earring](https://en.wikipedia.org/wiki/Girl_with_a_Pearl_Earring)
