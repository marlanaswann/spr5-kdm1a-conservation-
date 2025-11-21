####AI Use Log 

###RBH Colab Notebook
Task #1
Tool/model & version: Chat-GPT 5 mini
What I asked for: Help me set up code to run RBH for SPR-5 and KDM1A to confirm orthology
What I changed before committing: I added extra sections of code to uncompress the large proteome files because the BLAST databases would not work due to the code still being compressed.
How I verified correctness (tests, sample data): I used commands  !head -n 5 humanproteome.fasta and
!head -n 5 celegansproteome.fasta to view file format before creating databases. 

Task #2 
Tool/model & version: Chat-GPT 5 mini
What I asked for: Help me run the forward and reverse best hits. Also help me summarize the top results in a seperate table.
What I changed before committing: I edited code to help with formatting the table.
How I verified correctness (tests, sample data): I looked up each TrEMBL ascession in UniProt to verify if follow-up hits were isoforms. I also compared the reciprocal hits which complement each other when analyzing outputs like percent identiy, evalue, and bitscore. 

###Domain Annotation Notebook

Task #3
Tool/model & version: Chat-GPT 5 mini
What I asked for: I asked Chat GPT to help me use my JSON files from Interproscan to annotate the domains of SPR-5 and KDM1A. I also asked Chat to organize the domains by names because a lot of the domain names were repetitive but not exclusively grouped together. These groupings were included in a domain table. I also asked Chat-GPT to help create plots that visualize a domain plot, shared domains by count, and a heatmap of visualization domain occurences. Lastly, I asked Chat-GPT to make a table of domain occurences that also maps the amino acid range. 
What I changed before committing: My changes included the heat map and domain table edits.
How I verified correctness (tests, sample data): The tables and visualization plots allowed me to compare and confirm that the differences were consistently expressed across all figures. 

Tool/model & version: 
What I asked for: 
What I changed before committing: 
How I verified correctness (tests, sample data): 

Tool/model & version: 
What I asked for: 
What I changed before committing: 
How I verified correctness (tests, sample data): 
