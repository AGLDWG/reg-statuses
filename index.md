---
layout: page
title: Vocabulary
permalink: /
---
# Vocabulary

## Registry Statuses 

{: .concept_scheme .alternating}  
Element | Value
--- | ---
[Identifier](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/#http://purl.org/dc/terms/identifier) | <https://linked.data.gov.au/def/reg-statuses>
[Creator](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/#http://purl.org/dc/terms/creator) | [Nicholas J. Car](http://orcid.org/0000-0002-8742-7730)
[Publisher](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/#http://purl.org/dc/terms/publisher) | [Australian Government Linked Data Working Group](https://linked.data.gov.au/org/agldwg)
[Created](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/#http://purl.org/dc/terms/created) | 23rd July 2018
[Modified](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/#http://purl.org/dc/terms/modified) | 7th November 2021
[Issued](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/#http://purl.org/dc/terms/issued) | 30th July 2018
[Description](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/#http://purl.org/dc/terms/description) | This vocabulary is a re-published and only marginally changed version of the Registry Ontology's (http://epimorphics.com/public/vocabulary/Registry.html) *Status* vocabulary (online in RDF: http://purl.org/linked-data/registry). The only real change to content has been the addition of the term `unstable`. This re-publication has been performed to allow the IRIs of each vocab term (skos:Concept) to resolve to both human-readable and machine-readable forms of content (HTML and RDF), using HTTP content negotiation.<br /><br />Note that just like the original form of this vocabulary, while it is a SKOS vocabulary implemented as a single skos:ConceptScheme, it is also an OWL Ontology and that each *Status* is both a skos:Concept and a reg:Status individual.  
Repository | <https://github.com/AGLDWG/reg-statuses>

### [Concepts](https://www.w3.org/TR/skos-reference/#concepts)

* [Accepted]({{ site.baseurl }}/accepted)
    * [Deprecated]({{ site.baseurl }}/deprecated)
        * [Retired]({{ site.baseurl }}/retired)
        * [Superseded]({{ site.baseurl }}/superseded)
        * [Unstable]({{ site.baseurl }}/unstable)
    * [Valid]({{ site.baseurl }}/valid)
        * [Experimental]({{ site.baseurl }}/experimental)
        * [Stable]({{ site.baseurl }}/stable)
* [Not Accepted]({{ site.baseurl }}/notAccepted)
    * [Invalid]({{ site.baseurl }}/invalid)
    * [Reserved]({{ site.baseurl }}/reserved)
    * [Submitted]({{ site.baseurl }}/submitted)
