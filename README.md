cas-common-chemistry-api
========================
`https://commonchemistry.cas.org/commonchemistry-swagger.json`

### `/search`
- `curl -X GET "https://commonchemistry.cas.org/api/search?q=water" -H  "accept: application/json"`
- `curl -X GET "https://commonchemistry.cas.org/api/search?q=InChI=1S/H2O/h1H2" -H  "accept: application/json"`

### `/detail`
- `curl -X GET "https://commonchemistry.cas.org/api/detail?cas_rn=50-00-0" -H  "accept: application/json"`
- `curl -X GET "https://commonchemistry.cas.org/api/detail?cas_rn=7732-18-5" -H  "accept: application/json"`
  - Find cas_rn at [Search | CAS SciFinderⁿ](https://scifinder-n.cas.org/), need login account
    - examples:
      - https://scifinder-n.cas.org/search/all/65a8d9079a727d6a852890f6
	
