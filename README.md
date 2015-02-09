# SNAC Data Model

The SNAC data model is based on
[ISSAR(CPF)](http://www.ica.org/10203/standards/isaar-cpf-international-standard-archival-authority-record-for-corporate-bodies-persons-and-families-2nd-edition.html)
and [EAC-CPF](http://eac.staatsbibliothek-berlin.de) standards.

 * eac-cpf	↴		
    * [control](https://github.com/snac-pilot/data-model/wiki/control) [ISAAR (CPF) 5.4]
    * cpfDescription	↴	
      * [identity](https://github.com/snac-pilot/data-model/wiki/identity) [ISAAR (CPF) 5.1]
      * description [ISAAR (CPF) 5.2] 
        * [existDates](https://github.com/snac-pilot/data-model/wiki/existDates)
        * [biogHist](https://github.com/snac-pilot/data-model/wiki/biogHist)
        * [generalContext](https://github.com/snac-pilot/data-model/wiki/generalContext)
        * [occupation](https://github.com/snac-pilot/data-model/wiki/occupation)
        * [localDescription](https://github.com/snac-pilot/data-model/wiki/localDescription)
      * relations [ISAAR (CPF) 5.3] ↴
        * [cpfRelation](https://github.com/snac-pilot/data-model/wiki/cpfRelation)
        * [resourceRelation](https://github.com/snac-pilot/data-model/wiki/resourceRelation)

 * Location of Archival Materials and Other Resources (create EAC-CPF for each location with archival collections?)
   * [locations](https://github.com/snac-pilot/data-model/wiki/locations)

 * system events
  * [events](https://github.com/snac-pilot/data-model/wiki/events)

 * application user data
  * [Amazon Cognito](https://github.com/snac-pilot/data-model/wiki/cognito)

 * indexes, caches, auxiliary databases
  * [XML](https://github.com/snac-pilot/data-model/wiki/xml)
  * [XTF](https://github.com/snac-pilot/xtf-reindex-queue)
