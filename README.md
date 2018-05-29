# rexf
Real Estate Exchange Format (REXF) is a listing format that favours convention over configuration.

## Goals

* Extendable
  * It must support generalized concepts as Literals, ie apartments are apartments.
  * However it must support real estate changes between countries, ie are apartments / flats the same?
* Country-based
  * Since every country differs in how they call shit, this implementation shall be segregated by countries.
  * For example in Italy they have this shit they call "Baita's", like what the fuck is that, right? Let's keep that shit in Italy.

#### Compact

* Simple: Informative 'enough' for real estate agents/brokers/owners and their clients.
* Concise: Not too long, but still informative; hence not too short. 
* Timely: Easy to create, easy to read. Easy to skim, comprehensible in less than 30 seconds.
* Portable: Easily 

#### Internationalized & Localized

* Variety of options vary by country.

#### Structured

* Follows a flow, some attributes have dependencies, others don't.
* Attributes are designed for search, supporting the following operations:
  * Sort
  * Filter
  * Group By

* It must be easily used on simple listings, and easily extendable on complex / special-case listings.
* A listing's attributes shall be ingestible by search platforms, such as ElasticSearch.

#### Listing Attributes & Search

* Each listing should allow the following operations:
  * Sort
  * Filter
  * Group-by

## Will Use
* Flow Types

## License

Attribution 4.0 International (CC BY 4.0)

* https://creativecommons.org/licenses/by/4.0/
* https://creativecommons.org/licenses/by/4.0/legalcode.txt

![cc](https://creativecommons.org/images/deed/cc_blue_x2.png) ![by](https://creativecommons.org/images/deed/attribution_icon_blue_x2.png)
