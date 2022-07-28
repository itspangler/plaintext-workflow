# The Metadata Day

## What's metadata?

Metadata is just information about data, or more commonly, "data about data." This includes stuff like year published, author/creator, long-form field names (if a spatial or tabular dataset), etc.

Common spatial data formats are formalized by the [International Organization for Standardization](https://www.fgdc.gov/metadata/iso-standards). Elsewhere, in map libraries for example, metadata often conforms to standards such as [MODS XML](http://www.loc.gov/standards/mods/) or [MARC XML](https://www.loc.gov/standards/marcxml/). You can see a full list of metadata standards at the [Library of Congress' website](https://www.loc.gov/librarians/standards). 

## Why is this useful?

For a lot of reasons, metadata comes in handy when trying to understand a dataset's origin. It can also specify workflows used to create a dataset, which is instrumental for replicating workflows and data creation processes if time has passed since the data's original creation.

### APIs!

That's not the only useful aspect of metadata, though! Because metadata is **[structured](https://en.wikipedia.org/wiki/Data_model**, all items written to a particular metadata standard follow the same constraints. This allows users to access big batches of metadata via [application programming interface or API](https://en.wikipedia.org/wiki/API). APIs are essentially techniques for computer programs to communicate with one another. Those techniques are typically executed in programming environments like [Jupyter notebooks](https://en.wikipedia.org/wiki/Project_Jupyter), and they consist of programmatic statements that retrieve structured information about data.

In the context of Ian's work at the [Leventhal Map & Education Center](https://www.leventhalmap.org/), metadata is integral to cataloging and management of map collections. If you want to learn more about APIs and metadata at the Map Center, check out [this Jupyter notebook](https://hub-binder.mybinder.ovh/user/itspangler-cogapp-hack-day-4w5hm900/lab/tree/01_json-api.ipynb) for code snippets that demonstrate how to query the map collections via JSON and IIIF API.

**TL;DR: having structured metadata gives people access points to programmatically retrieve information about objects (e.g., map collections), which is instrumental in developing cool web apps about those objects.**

### Allmaps!

Allmaps is another example of why metadata is useful. Developed by [Bert Spaan](https://bertspaan.nl/), [Allmaps](https://allmaps.org/) is a next-generation web georeferencing platform that relies on the [international image interoperability framework (IIIF)](https://iiif.io) to transform scanned maps in a web browser.

IIIF is a metadata standard that keeps structured metadata tied to an image URL. One of the benefits of this is that you can easily adjust different qualities of an image (e.g., resolution, size, color, rotation) by simply adjusting the URL. Allmaps relies on this metadata standard to first retrieve images from their existing location on a server, and then warps those maps in a web browser according to user-generated ground control points. At no point in the process do you need to go through the arduous task of downloading a GIS software or a large TIFF image. Nice!

**To use Allmaps, all you need is a URL.** Navigate to the Allmaps platform, click the link to Allmaps editor, and paste the IIIF manifest URL to a IIIF-compliant map image to get going. [Here is a list](https://iiif.io/guides/finding_resources/) of a lot of institutions with IIIF-compliant collections.

If you wanted to georeference any of the [Map Center's collection items](https://collections.leventhalmap.org/), for example, you'd simply append `/manifest` to the end of a collections item URL. So this:

    https://collections.leventhalmap.org/search/commonwealth:q524n229g

becomes this:

    https://collections.leventhalmap.org/search/commonwealth:q524n229g/manifest

Paste `https://collections.leventhalmap.org/search/commonwealth:q524n229g/manifest` into the Allmaps Editor, and you're georeferencing!

Also, check out the [Atlascope](https://atlascope.leventhalmap.org/) tool, from the Map Center, for an example of a fully-formed public facing georeferencing project. As we expand Atlascope to cover the state of Masssachusetts instead of just Boston, this is the kind of thing that we hope to route through Allmaps in the future.