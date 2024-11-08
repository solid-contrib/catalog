# Catalog of Solid Resources

The Catalog of Solid Resources is an RDF repository of the software, people, organizations, and other resources engaged in the Solid Project.  This is a work in progress and is missing many resoures and details of the resources listed but, is the most complete list I am aware of and, I believe, a good basis on which to build.  In addition to the RDF data itself, the current version uses [Solid Web Components](https://github.com/solidos/solid-web-components) to present a searchable UI of the data.

Please [visit the Catalog](https://solidproject.solidcommunity.net/catalog/).

The Catalog consists of the following resources :

* [An RDF datasource](./catalog-data.ttl)
* [A SHACL shape and set of RDF subclasses](./catalog-shape.ttl)
* [A display template](./catalog-view.js)
* [A minimal HTML file](./index.html)
* [A CSS file](./catalog.css)

Because the model for the catalog is captured in the SHACL shape and subclass structure specified, it is easy to modify the structure of the catalog.  The proposed types and subclasses are provisional and suggested changes are welcome.  Some changes already in progress :

* keywords are currently strings, once we have an idea of the keywords we'll need, we can make the URIs tied to SKOS concepts
* I have invented a number of classes in the yet to be written soar: (Solid Organizations and Resources) vocab, again, suggestions welcome if there are appropriate existing terms.
* I intend to create shapes for the invididual types.  For example, people and organizations will use vcard and ontologies will use vann.

Please [correct information about yourself and your projectss](./catalog-data.ttl).
Please [suggest changes to the shapes and terms](https://github.com/solid-contrib/catalog/issues).


