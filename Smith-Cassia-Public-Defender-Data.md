# Public Defender Case File Basics

By Cassia Smith

## Intro/Caveat


This document is based on general guidance on the recordkeeping associated with public defenders' offices. It's drawn from a document from 1976 advocating for incorporating paralegals into public defenders' office workflow. According to the librarians at the Law Library on campus, the specific case file requirements and best practices for the Champaign County public defenders are most likely kept in an internal-use-only handbook. I thought it would be best to wait to contact the public defenders' office about this document until after we had a chance to discuss that decision in class. This proposal may need to be adjusted if we choose to involve the public defenders' office in the project.

## Broad Categories of Information Useful to Public Defenders


There are a few broad categories of information that seem to be needed by most public defenders. I will note overlaps with the jail dataset as I describe each category.


### Employment Information

Public defenders are interested in employment information for two main reasons that I can see. First, it might be involved in the determination of whether a defendant eligible for their services, as public defenders are generally intended to serve indigent defendants. Secondly, it's a way of establishing a defendant's ties to the community, which may be significant in both setting a bail amount (or getting the defendant released without bail)  and possibly during the sentencing phase of an eventual trial. Though the jail data provides employment information in the EMPLOYMENT STATUS and OCCUPATION columns, the example client inverview form in the paralegal guidance document requests contact information, job title, earnings, supervisor name, etc for the previous 3 employers, in addition to current employment information. I'm not convinced that this is additional information that the jail should be requesting, but it is worth noting that the jail information is incomplete for the purposes of the public defenders' office.

### Contacts for Friends, Relatives, and Third Party Custodians

Another piece of information that the public defender needs very early in their relationship with the client is contact information for friends and relatives who may be able to help pay bail or act as "third party custodians" who can convince the judge to release the defendant into their custody without bail. Depending on what family members they have and how close the relationship is, they may be examples of the close community ties that can get bail reduced or deemed unnecessary as well. And these people may end up being helpful once the attorneys or their investigators begin to look into the case. This also feels like detail that it may not be appropriate for the jail to request, but it is a very important category of information for the public defenders.

### Addiction Status

A third piece of useful information that is not currently found in the jail data but that I think could be interesting for them to ask for is whether or not the defendant is currently addicted to eg, alcohol or narcotics. This is a change that might need to be made in consultation with the public defenders, since I don't know if it would count as an admission of guilt in some cases. But if the public defenders know early on that their client is an addict, they can sometimes arrange to have representatives from addiction treatment services on hand at the hearing to show that there are treatment options available to the defendant. It would probably also be useful information for the jail from a population management perspective, particularly if they typically expect inmates to detox while they're in custody. 

### Charges

Obviously, any attorney needs to know the charges their client is facing. The CHARGE/STATUE and CRIME CODE columns provide some of this information, but judging by the monthly reports found on the Champaign County public defenders' website, this information will need to be integrated with or at least parseable by a separate taxonomy of FELONIES, MISDEMEANORS, TRAFFIC, JUVENILE DELINQUENCIES, MENTAL HEALTH, ABUSE/NEGLECT, and MISCELLANEOUS. My guess is that juvenile delinquencies might not be relevant to the jail data, since juveniles are probably held at a separate facility. It is easy to assume that the ABUSE/NEGLECT category refers to crimes against children, but I think it would be a good practice to clarify with the public defenders whether mistreatment of animals or elders is also included in this category. The biggest challenge, however, is clearly the MENTAL HEALTH category. This category clearly captures an important facet of the jail population, but there is no clear one-to-one entity in the jail data. My colleagues' ontologies of mental health may be useful for retrieving this category, but without knowing how the public defenders' office identifies these cases, it's hard to say.

### Previous Arrests

Previous convictions would probably not be within the jail's purview. However, being able to pull previous arrests by jacket number would be useful to public defenders as they prepare for the bail hearing. If being able to scan them by category is helpful, then this could probably repeat the taxonomy discussed under CHARGES, above.

### Local Community Services

I mention this mostly because it may hook into another classmate's ontology. Public defenders need to be aware of the community services available to their clients. This includes not only the addiction services mentioned earlier, but also employment programs that can help them find work while they're awaiting trial, and other social services.


## Additional Details of Interest

These are too specific to count as categories, per se, but they are useful pieces of information that public defenders need in order to do their jobs.


### Booking Date and Time

Timelines are very important to defense attorneys. Knowing what time a defendant was booked into the jail can help them reconstruct the events leading up to (and immediately after) the arrest.

### Jacket Number

The jacket number is a simple but essential piece of identifying information for the public defender's client. 

### Police Officer / Police Report

The name of the police officer involved in the case and a copy of the police report are two pieces of information public defenders typically need in order to build their case. Again, this is not information in our copy of the jail data, but it seems worth including (assuming the actual database doesn't include it, which seems surprising to me).

