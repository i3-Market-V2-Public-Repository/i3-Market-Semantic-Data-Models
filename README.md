# i3-Market Semantic Models

Repository for sharing and managing models files

One of The main contribution of the Data Models / Ontologies  is to enable the mapping of the data assets, provided from i3-Market stakeholders, to the model/”ontology” concepts to capture the structural and semantic characteristics metadata of the various entities in each data asset = Data Offering. More specifically, the core uses of this model are for: 1) data Registration on mapping which corresponds to the data harmonization process. In this way, each provided data asset will be registered in our Registry with concepts from the i3-Market data offering model in a semi-automatic way; 2) metadata linking where any provided data asset metadata will be linked with other relevant sources (or data assets) that exist in Backplane; 3) data Discovery which involves the development of algorithms and software for supporting the selection of the most appropriate metadata data assets that best match user preferences. 
The i3-Market Models will be used for capturing the structural and semantic characteristics of the various entities involved in the i3-Market backplane domain, whereas the underlying conceptual models facilitate the use of lightweight reasoning during the discovery and operational process e.g. for contracts and service/agreements operations..


Model Coding: The representation of the ontology capture was transformed into a
formal (ontology) language (e.g. OWL) using Protégé.
I. Top-level Ontology: Create a top-level ontology that describes the main high level concepts and links for the i3-Market backplane domain
II. Integrating Existing sub topic Ontologies: Use existing related domains ontologies and  incorporate them under the top-level ontology.
III. Expanding the Domain-level use-cases pilots categories/annotations: Expand (Build-on-top) the domain-level conceptSkeme categorization taxonomies and include the new concepts, data fields and relationships between the concepts that were extracted from the demonstrators’ domains.

MAIN MODELS BLOCKS
AGENTS in Marketplaces and Data Spaces
-	Providers
-	Consumers
-	Owners
-   Data Markets
Data Offering
- Data assets description
- Extensions for Domain Categorization
- Data Service Descriptions
Extra Service Details 
- for data access info
- and for SLA contract info
Pricing/Cost Model
SLA / SLO / SLS info

## Credits
This repo was created by:
Achille Zappa <achille.zappa@nuigalway.ie>
## Contributing
Contributions are always appreciated.
## License
```
This is free and unencumbered software released into the public domain.

Anyone is free to copy, modify, publish, use, compile, sell, or
distribute this software, either in source code form or as a compiled
binary, for any purpose, commercial or non-commercial, and by any
means.

In jurisdictions that recognize copyright laws, the author or authors
of this software dedicate any and all copyright interest in the
software to the public domain. We make this dedication for the benefit
of the public at large and to the detriment of our heirs and
successors. We intend this dedication to be an overt act of
relinquishment in perpetuity of all present and future rights to this
software under copyright law.

 dc:contributor "Achille Zappa, NUIG, Galway"@en;
            dcterms:license <https://creativecommons.org/licenses/by/4.0/> ;                
            dc:description ""@en;
            dc:rights "Copyright Achille Zappa, NUIGalway";
            dc:title " i3-Market Semantic Models"@en;
            dcterms:issued "2020"^^xsd:date;
            dcterms:modified "2020"^^xsd:date;
            rdfs:comment " "@en;
          
           

The Documents in this repository are under license <https://creativecommons.org/licenses/by/4.0/> 


THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES OR
OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE,
ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.


