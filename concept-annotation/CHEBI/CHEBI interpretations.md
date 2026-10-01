**ATOM OR ELEMENTAL MOLECULAR ENTITY:** Indicates that the annotation class can be interpreted as referring to either atoms of the specified element or to the corresponding elemental molecular entities, i.e., molecular entities all atoms of which are of the same element, which can be monoatomic (e.g., iron(0), iron(2+)) or polyatomic (e.g., dioxygen, peroxide).

- subclasses of atom (`CHEBI_33250`)

**GENE, TRANSCRIPT OR PROTEIN:** Indicates that the annotation class can be interpreted as referring to proteins or to their corresponding genes or transcripts.

- subclasses of protein (`CHEBI_36080`) except:
    - hemoglobin (`CHEBI_35143`)
    - glycoprotein (`CHEBI_17089`) and its subclasses
    - lipoprotein (`CHEBI_6495`) and its subclasses
    - protein disulfide (`CHEBI_16249`)
- Adiponectin (`CHEBI_81572`)
- angiotensin (`CHEBI_48433`)
- argipressin (`CHEBI_34543`)
- Factor X (`CHEBI_4964`)
- gastrin (`CHEBI_75436`)
- insulin (`CHEBI_145810`)
- insulin (human) (`CHEBI_5931`)
- Insulin-like growth factor I (`CHEBI_80343`)
- Insulin-like growth factor II (`CHEBI_80344`)
- Leptin (`CHEBI_81571`)
- Prolactin (`CHEBI_81580`)
- Prothrombin (`CHEBI_8583`)
- somatostatin (`CHEBI_64628`)
- vasopressin (`CHEBI_9937`)

**GENE, TRANSCRIPT, PROTEIN OR MACROMOLECULAR COMPLEX:** Indicates that the annotation class can be interpreted as referring to proteins, to their corresponding genes or transcripts, or to macromolecular complexes all of whose subunits are the corresponding proteins.

- hemoglobin (`CHEBI_35143`)

**GENE, TRANSCRIPT, PROTEIN OR POLYMER:** Indicates that the annotation class can be interpreted as referring to either proteins, to their corresponding genes or transcripts, or to polymeric mixtures of the corresponding proteins.

- Collagen (`CHEBI_3815`)

**MACROMOLECULE OR POLYMER:** Indicates that the annotation class can be interpreted as referring to either macromolecules (i.e., individual molecules) or to corresponding polymers (i.e., mixtures of types of the corresponding macromolecules).

- subclasses of macromolecule (`CHEBI_33839`) other than biomacromolecule (`CHEBI_33694`) and polypeptide (`CHEBI_15841`) and their subclasses

**MOLECULAR ENTITY OR SUBSTITUENT GROUP:** Indicates that the annotation class can be interpreted as referring to either molecular entities (i.e., separately distinguishable chemical entities, e.g., an alanine molecule) or to corresponding substituent groups (e.g., alanyl group, alanine residue).

- amino acid (`CHEBI_33709`) and its subclasses other than non-proteinogenic amino acid (`CHEBI_83820`) and its subclasses AND that are an object of an `is_substituent_group_from` assertion
- nucleobase (`CHEBI_18282`) and its subclasses AND that are an object of an `is_substituent_group_from` assertion
- nucleoside (`CHEBI_33838`) and its subclasses AND that are an object of an `is_substituent_group_from` assertion
- nucleotide (`CHEBI_36976`) and its subclasses AND that are an object of an `is_substituent_group_from` assertion
- polynucleotide (`CHEBI_15986`) and its subclasses AND that are an object of an `is_substituent_group_from` assertion

Excluded are:

- messenger RNA (`CHEBI_33699`)
- nucleic acid (`CHEBI_33696`)
- ribosomal RNA (`CHEBI_18111`)
- tRNA(Trp) (`CHEBI_29181`)
- transfer RNA (`CHEBI_17843`)

But included are:

- 2'-deoxycytidine (`CHEBI_15698`)
- dATP (`CHEBI_16284`)
- dCTP (`CHEBI_16311`)
- dGTP (`CHEBI_16497`)
- dUTP (`CHEBI_17625`)
- deoxyribonucleotide (`CHEBI_4431`)
- dinucleotide (`CHEBI_47885`)
- double-stranded DNA (`CHEBI_4705`)
- double-stranded RNA (`CHEBI_67208`)
- nucleotide (`CHEBI_36976`)
- ornithine (`CHEBI_18257`)
- poly(cytidylic acid) (`CHEBI_84498`)
- poly(deoxyadenylic acid) (`CHEBI_73276`)
- poly(deoxycytidylic acid) (`CHEBI_73277`)
- poly(deoxyguanylic acid) (`CHEBI_76043`)
- poly(deoxythymidylic acid) (`CHEBI_73300`)
- polynucleotide (`CHEBI_15986`)
- purine (`CHEBI_35584`)
- single-stranded DNA (`CHEBI_9160`)
- thymidine (`CHEBI_17748`)

**OCCURRENCE, ATTRIBUTE OR AREA OF STUDY:** Indicates that the annotation class can be interpreted as referring to roles, conceptualized as either occurrences/processes (e.g., biochemical occurrences/processes), to attributes of entities (e.g., biochemical functionalities possessed by entities), or to areas of study of these occurrences, attributes, and bearers (e.g., the field of biochemistry).

- biochemical role (`CHEBI_52206`)
- biological role (`CHEBI_24432`)
- biophysical role (`CHEBI_52208`)
- chemical role (`CHEBI_51086`)

**ROLE-BEARING ENTITY:** Indicates that the annotation class is be interpreted as referring to the bearers of the specified roles rather than the functionalities possessed by these bearers.

- subclasses of application (`CHEBI_33232`), biological role (`CHEBI_24432`), and chemical role (`CHEBI_51086`) other than biochemical role (`CHEBI_52206`) and biophysical role (`CHEBI_52208`)
