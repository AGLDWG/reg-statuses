---
layout: page
title: Vocabulary
permalink: /
---
# Vocabulary

## Registry Statuses 

`https://linked.data.gov.au/def/reg-statuses`

{: .concept_scheme .alternating}  
Predicate | Value
--- | ---
[Creator](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/#http://purl.org/dc/terms/creator) | [Nicholas J. Car](http://orcid.org/0000-0002-8742-7730)
[Publisher](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/#http://purl.org/dc/terms/publisher) | [Australian Government Linked Data Working Group](https://linked.data.gov.au/org/agldwg)
[Created](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/#http://purl.org/dc/terms/created) | 23rd July 2018
[Modified](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/#http://purl.org/dc/terms/modified) | 19th July 2024
[Issued](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/#http://purl.org/dc/terms/issued) | 30th July 2018
[Description](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/#http://purl.org/dc/terms/description) | This vocabulary is a re-published and only marginally changed version of the Registry Ontology's (http://epimorphics.com/public/vocabulary/Registry.html) *Status* vocabulary (online in RDF: http://purl.org/linked-data/registry). The only real change to content has been the addition of the term `unstable`. This re-publication has been performed to allow the IRIs of each vocab term (skos:Concept) to resolve to both human-readable and machine-readable forms of content (HTML and RDF), using HTTP content negotiation.<br /><br />Note that just like the original form of this vocabulary, while it is a SKOS vocabulary implemented as a single skos:ConceptScheme, it is also an OWL Ontology and that each *Status* is both a skos:Concept and a reg:Status individual.  
Repository | <https://github.com/AGLDWG/reg-statuses>
Current Version | 2.2
[Version History](https://schema.org/versionInfo) | 2.2 - 2024-07 - fixed incorrect prefLabels for unstable & original in the RDF that used 'stable'. Also fixed preferred namespace URI. Updated Nicholas' affiliation to ANU<br /><br />2.1 - 2023-05 - added colours<br /><br />2.0 - 2023-01 - addition of Concepts addition & original, as per updated Registry Item status codes<br /><br />1.2 - 2021-11 - changes IRI to reg-statuses; added unstable<br /><br />1.1 - 2020-06 - altered structure & metadata, not content, to conform to Vocab Publication Profile<br /><br />1.0 - 2018-06 - as per Registry Ontology original

### [Concepts](https://www.w3.org/TR/skos-reference/#concepts)

* [Accepted]({{ site.baseurl }}/accepted)
    * [Deprecated]({{ site.baseurl }}/deprecated)
        * [Retired]({{ site.baseurl }}/retired)
        * [Superseded]({{ site.baseurl }}/superseded)
        * [Unstable]({{ site.baseurl }}/unstable)
    * [Valid]({{ site.baseurl }}/valid)
        * [Experimental]({{ site.baseurl }}/experimental)
        * [Stable]({{ site.baseurl }}/stable)
            * [Addition]({{ site.baseurl }}/addition)
            * [Original]({{ site.baseurl }}/original)
* [Not Accepted]({{ site.baseurl }}/notAccepted)
    * [Invalid]({{ site.baseurl }}/invalid)
    * [Reserved]({{ site.baseurl }}/reserved)
    * [Submitted]({{ site.baseurl }}/submitted)
