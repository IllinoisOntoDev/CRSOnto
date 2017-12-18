# CRSOnto
#Final Project 590OD (Ontology Development)

##Project Goals

The goal of this project was to create an ontology that could be used by public defenders and other caseworkers to establish a inmate's ties to the community. This information is useful to legal counsel in the bail, trial, and sentencing phases of the legal process, and could potentially be of interest to social workers and other professionals serving the incarcerated community

##Project Research

I drew the majority of my research on this topic from *Paralegals: A resource for public defenders and correctional services*, by John Hollister Stein. This publication included extensive information on the clerical information typically gathered at all stages of the criminal legal defense process, including sample forms and extensive descriptions of information gathering activities. I supplemented this information with the sections of the Virginia Risk Assessment Instrument (VRAI) highlighted in the 2013 Champaign County Criminal Justice System report and the Champaign County jail data itself. 

##Project Obstacles

###Inference Problems

I was able to follow the course objectives fairly closely until we needed to establish inference relationships in Protege, where I met a significant roadblock. In spite of referring repeatedly to resources within and outside of the course, I was unable to establish someValuesFrom relationships consistently within Protege. This is a topic I intend to return to at some point after the course has ended, but a number of my inferences are still non-existent or imperfectly expressed in spite of my best efforts and multiple meetings with the professor. 

###Ontology Inconsistencies

Because of my struggles with the establishment of inference, it took me an additional week to determine that one of the difficulties was not caused by me but by an imported ontology. The Employment ontology relates Employee and Student to its Client, which made it difficult for me to establish a relationship with my own Client entity without breaking the reasoner. If I had been able to determine this obstacle earlier, I might have been able to resolve it through conversation with the ontology creator. At it was, that was not possible and there are significant gaps in the ontology as a result.
