 CRISPR-Cas9
    A DNA manipulation tool that involves directly editing genes within an organism
    It is an enzyme found in bacteria that functions similar to an immune system
    CRISPR-Cas9 works in bacteria by recognising viral DNA and cleaving it, thereby protecting the bacterium from the virus
    It is utilised to edit genomes, allowing for CRISPR-Cas9 to cleave DNA at a specific location
	    - Cas9 is a programmable endonuclease that looks for sequences of DNA that matches the guide RNA held in its binding site.
	    - Cas9 binds and unwinds DNA, reading it until it finds a match
	    - Once it finds a complementary DNA strand to its guide RNA, Cas9 will break the phosphodiester bonds that hold together the sugar-phosphate backbone of DNA strands 
    CRISPR-Cas9 in Bacteria
        When viral DNA enters the cell for the first time, a sequence of DNA (spacer) is incorporated into the bacterial genome within the CRISPR array
	    If this same viral DNA enters the cell at another time, the bacterium will recognise the DNA due to the spacer that matches it
        This DNA spacer will be transcribed, becoming the guide RNA
        This guide RNA joins the Cas9 enzyme to form the Cas9 complex, which will find the corresponding section of viral DNA and cleave it, effectively destroying the viral DNA and preventing infection
	        CRISPR reactions inhibit the replication of bacteriophages
        CRISPR associated sequence genes
			Adjacent to the CRISPR region are certain genes, called CRISPR-associated sequences (Cas).
			These genes code for proteins that act on DNA or RNA in different ways.
			One Cas gene that plays a particularly important role in genomic editing technology codes for the nuclease Cas9.
			Other Cas proteins help incorporate new spacers into a CRISPR array
			![](https://lh7-us.googleusercontent.com/-UOkECkiA0ucJ7s8wI6vvM72KdDs1s0Xxh6peOKECOifAotfXYfgQvnp0cn5B1i5HtAQoPVMlu2YRrE1UwA15sLgVQPZzhHmiZD1myh6uoHa9oMVJ5OncibdvBMUnd6FZUf0uDDhiFzyQyMjiSRh4A=s2048)![](https://lh7-us.googleusercontent.com/jNvv5uSRyPHMaO0gQaYL4DNcZLsjzipFUHkMNp4i_woi8EkimcyLz1v6iQW8gpa41w29vqGTxisLoYWmKPl2o_Kb9yA4v5OxWIcWkgKWIXolS009bU5DxuGu2vWA0xMqbuL3E7e1tio1hRhi_I8pBw=s2048)
		CRISPR Array
			Once the bacterium has gathered genetic information from viruses, it will keep sections of the invading viruses (spacers) in an array
			This array is then transcribed into CRISPR RNA (crRNA) which is cut into smaller sections
			The crRNA is then joined to a Cas protein (an endonuclease) which will use the specific crRNA inside it as a guide to know where to cut on DNA
			This complex will attack and break apart the DNA of invading viruses that have been encountered in the past![[21crispr array.png]]![[0120crispr array.png]]![[crispr array.png]]![[array repeat.png]]
		Creating gRNA
			![[tracr rna.png]]RNA polymerase transcribes the entire CRISPR sequence resulting in one long chain of CRISPR RNA (crRNA). TracrRNA is present in the bacterium and contains a complementary sequence to the spacer DNA. The tracrRNA binds with the palindromic repeat and an enzyme clips off other CRISPR sequences. The combination of the tracrRNA and crRNA forms the complete guide RNA.![[gRna.png]]
		Guide RNA
			The DNA sequence interacts with the gRNA by binding any complimentary base pairs
			 together.
			 Complementary base pairing is where the nitrogenous bases within the DNA double helix form hydrogen bonds between specific bases. Guanine always pairs with Cytosine and Adenine always pairs with Thymine. Because CRISPR utilizes RNA, Thymine is represented as Uracil. ![[gRNa comple.png]]
    Applications in Genome editing
        In bacteria, the guide RNA matches the viral DNA to be cleaved, however, the guide RNA can be created with an artificial sequence - for example a gene responsible for a hereditary disease
        Using the guide RNA, which is complementary to the gene of interest, the Cas9 complex will find the gene in the cell and cleave it
        Cutting the gene inactivates it, however another gene can be inserted or a section of a gene can be completely deleted
        ![](https://remnote-user-data.s3.amazonaws.com/2rukoj_oDTsysXZIyGjRj0kAI06g1Yn8Njb5i8hvAV7zmAG1as7FCiKMpcDn0WXE5ltgWihmwpHxNs_G_RbKbkNyAUKPSeIFfy_kVbZaIjLPXEivydVb3Y9vS5msmh4N.png)
        Gene editing with CRISPR-Cas9
			Two key RNAs (tracrRNA and crRNA) involved in Cas9 cutting could be fused into a "single-guide" RNA (often abbreviated sgRNA) which simplified the system and increased success rates of their experiments
			Once DNA has been cut, genes could be edited in numerous ways, such as introducing a new functional gene into the genome or switching a faulty gene off completely![](https://lh7-us.googleusercontent.com/mdrWE8zQUkb7mSb7gYhdPq6jV929yOVqmmWTzkYe-lhMU8ccaoocI5ZQksxlRP8S9Gdt-8RKcOj1v9Xx6sUzWeBqs3Yrr0qUo8Or5bJ4BTyI5zH7acA3U3_Gu_L02Vh5q1lE6D7DnVXrhJVEdPOsmw=s2048)![[uses of crisprcas9.png]]![[crispr array 2.png]]
    PAM Sequence
        The CRISPR-Cas9 system has a safeguard known as the PAM sequence, which is similar to how bacterial DNA is methylated, which allows for endonucleases to distinguish foreign DNA
        The PAM sequence is how Cas9 knows how to cleave viral DNA but not the spacer in the CRISPR array
        Cas9 will only cleave DNA that is followed by a PAM sequence (2-6) nucleotides
            The DNA spacers within the CRISPR array are not followed by a PAM sequence, which is why Cas9 doesn't cleave this DNA
        Before scientists create a guide RNA, they first make sure there is a PAM sequence next to the gene they're targeting
        PAM speeds up the search for target DNA
			- To increase the efficiency of finding invading viral DNA to cut, CRISPR-Cas9 specifically looks for PAM sequences to bind to rather than unzipping the whole genome.
			- This allows the Cas protein to find its target much faster and buys valuable time for the bacterium to defend itself against invaders 
			![](https://lh7-us.googleusercontent.com/XFTCB6W4jIVZP3FcPtpBaKCmi-bKihFTl3VpztFNJgM_pUsWVxsIiNAskh8tIQiDD6Gu_CpggcP6gFDKcf8yQCi93uguabyQFYNUKQH_IuQ1a94f2zxwJDgWs8-Z4TwM4Se1sTPZRaVhuy0PDcY-pw=s2048)!
		PAM preventing self attacks for bacteria
			 1. Cas9 must first bind the PAM in the DNA, and only then can it interrogate the flanking DNA for a match for its crRNA. 
			2. If there is a complete sequence match, then the Cas9 endonuclease is activated and cuts the DNA upstream of the PAM (DNA before the PAM region). 
			3. The reliance on PAM target recognition prevents self-targeting of a bacterium’s own CRISPR array, because the spacers in the CRISPR array are flanked by the repeats, which never possess PAM sequences.  
			4. This allows bacteria to distinguish self versus non-self, a key part of any immune system, and thus prevent an autoimmune response.![What is the PAM sequence for CRISPR and where is it? | IDT](https://lh7-us.googleusercontent.com/j4uamoZIGKyNtktxBLYUGXMTrXwHYmZNAoctYbQUJXIMaSOlehSj8HsbXpZqppMJCvK2LAmAo7OFjs1Oewq9iZ0P6knx5ZSq_5LVN6FyQC5p7MPZIh91ObnGS2B0SZSSImREsvqE4_mt80TQTzAM5g=s2048)
    Concerns
        Some concerns are
            If a gene is inserted, what happens when it’s done it’s job and is no longer required?
            What if Cas9 cleaves at unwanted locations?
            Will it work in the long-term? For example, people with chronic diseases will constantly need the gene to be working.
            What if a gene has unknown influence on a certain characteristic/function, and is inactivated?
            What if the mutations caused by CRISPR-Cas9 lead to cancer?
        The main issue is potential off-target effects

Example questions
	1. Draw the process of programming a Cas9 protein against a particular viral sequence
	2. CRISPR-Cas9 is effective against virus A but ineffective against virus B. Explain why.
		Because Cas 9 is programmed to recognise specific sequences of viral DNA, the gRNA in the CRISPR-Cas9 complex is only complementary to virus A. This specific CRISPR-Cas9 is ineffective against virus B because it's gRNA is not complementary to virus B, therefore the viral DNA will not be cleaved.
	3. What is the purpose of the PAM sequences?
		The purpose of PAM sequences is to tell Cas 9 where to unwind DNA. PAM sequences makes the process of comparing guide RNA to DNA more efficient as the Cas 9 protein looks for PAM sequences first so that not all DNA needs to be unwound

  

  














