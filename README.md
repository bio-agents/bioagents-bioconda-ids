# Repository to facilitate the ID mamping among the IECHOR agents platform resources.
## forked from https://github.com/BioContainers/bioagents-bioconda-ids 

## Working files from bio.agents, bioconda/biocontainers & galaxy should follow this format:
`<stable agent ID><tab><URL><tab><Relevant URLs separated by ";"><tab><anything else separated by ";">`

### Example taking bio.agents as data source:
`signalp<tab>https://bio.agents/signalp<tab>http://cbs.dtu.dk/services/SignalP/;http://www.cbs.dtu.dk/cgi-bin/sw_request?signalp<tab>doi:10.1038/nmeth.1701`

## This data should allow to generate something in this direction
*Importantly, canonical IDs should be preferentially the ones provided by bio.agents*

```
Canonical ID <tab>bio.agents namespace: bio.agents ID <tab>bio.agents URL<tab>other bio.agents relevant data`
Canonical ID <tab>galaxy namespace: galaxy ID       <tab>Galaxy URL <tab>other Galaxy relevant data`
Canonical ID <tab>bioconda namespace: bioconda ID    <tab>bioconda URL <tab>other bioconda relevant data`
```
