## Data Integrity 
(Source: http://www.fdewb.unimaas.nl/marc/ecais_new/files/boritz.doc)

**Integrity** is defined as the representational faithfulness of information to the true state of the object that the information represents.

**Representational faithfulness** is composed of four essential qualities or core attributes: 

- accuracy/correctness
	- information corresponds to reality
	- neutral (lack of bias)
- completeness
	- trades off with accuracy
	- sets an upper bound
- currency/timeliness
	- changes in data
	- time stamping
- validity/authorization
	- review
	- approval
	
## Types of integrity constraints 
(Source: https://en.wikipedia.org/wiki/Data_integrity)

- Entity integrity
	- a rule that requires every table to have a primary key
	- the primary key should be unique and not null

- Domain integrity 
	- a rule that requires all data items in a column to be of the same type
	- a domain is a set of values of the same type

- User-defined integrity 
	- a set of rules specified by a user

## Questions for spreadsheets:
(Source: https://arxiv.org/ftp/arxiv/papers/0908/0908.1186.pdf)

- What is the purpose of the spreadsheet?
	- Criticality – what if it were lost or corrupted?
	
- Where is it kept – network location, set of files
- How do we know which is the current version?
	- Complete list of data sources it depends upon
	- What depends on this spreadsheet?
		
- How is it used? (Process documentation, instructions)

- Is it for one person or is it re-used by others?

- Is it once-off (project) or has it a periodic operation?

- Who peer reviews its structure and version changes?
	- If none, likelihood of key-person risk?
	- Evidence of test (with results) and acceptance
  
- What controls are around it?
	  - Who reviews & signs off its output?
	  - Reconciliation with data sources
	
- What checks are included within it?
	- Cross-foot, balance checks, etc
	
- What evidence is there of conformity to good design practices?
	- Clear block layout, formats, print output header/footer
	- Formula integrity, protection, no errors, no external links
	- Use of timesaving formulas and features
	
- What are the pain points?
	- Quality of input data; duplication, update
	- Grunt work transforming data
	- Effort maintaining & updating formulas
	- Training in more efficient Excel skills
	- Possible to replace with controlled shared system?
