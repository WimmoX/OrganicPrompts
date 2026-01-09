# DOCUMENT RedFlagDetector

## 1. PROBLEEMSTELLING

**Kernprobleem:**
In formele documenten (overheidsrapportages, contracten, beleidsstukken) wordt informatie met hoge impact vaak **strategisch geminimaliseerd, verplaatst of genormaliseerd** waardoor cruciale risico's over het hoofd worden gezien.

**Concrete manifestaties:**
- **Impact-ruimte asymmetrie**: €70 miljoen geannuleerd project krijgt 1 alinea, terwijl €2 miljoen succes 3 pagina's beslaat
- **Strategische verschuiling**: 3-jarige opzegtermijn staat niet in contract, alleen verwijzing naar algemene voorwaarden
- **Normalisatie**: Ernstige budgetoverschrijdingen gepresenteerd als "administratieve bijstellingen"

**Waarom dit problematisch is:**
- Besluitvormers missen kritieke informatie voor geïnformeerde beslissingen
- Financiële en juridische risico's worden niet tijdig geïdentificeerd
- Verantwoordingsprocessen (zoals Tweede Kamer informeren) worden gefrustreerd
- Contractuele valkuilen worden pas ontdekt bij executie

**Voor wie:**
- Beleidsadviseurs, die Kamerinformatie moeten reviewen
- Contract managers, die leverancierscontracten beoordelen
- Risk officers, die projectrapportages analyseren
- Informatiemanagers, die governance-documentatie screenen

---

## 2. HOW TO USE THIS PROMPT

1. Lees een document door en maak aantekeningen
2. Gebruik de RedFlagDetector om de verborgen problemen boven water te halen
3. Beoordeel de bevindingen, er kunnen vals positieven tussen zitten. 

Let op:
- Problematische onderdelen die niet verborgen zijn, worden niet gemarkeerd!
- Niet alles wat gedetecteerd wordt is automatisch problematisch, specifieke domein context ontbreekt vaak.

Prompt:
You are tasked with analyzing a document for hidden flaws and potential issues. Your goal is to thoroughly examine the content and identify any problems that may not be immediately apparent. Pay close attention to details and critically evaluate the information presented.

Here is the document to be analyzed:

<document>
{{DOCUMENT}}
</document>

Carefully review the document and check for the following potential issues:

1. Conflict of interest: Look for any indications that the authors or involved parties may have undisclosed interests that could influence the report's findings or recommendations.

2. Euphemistic language: Identify any instances where language is used to downplay or obscure negative aspects or problems.

3. Hidden problems ("skeletons in the closet"): Search for any hints of issues that are not explicitly stated but may be inferred from the information provided.

4. Inadequate or flawed research methodology: Evaluate the research methods used and determine if they are appropriate, sufficient, and correctly applied.

5. Misinterpretation of statistics: Check for any statistical data that may be misrepresented, misinterpreted, or used inappropriately to support conclusions.

6. Unsupported conclusions: Identify any conclusions or recommendations that are not adequately supported by the evidence presented in the document.

Approach your analysis systematically, addressing each of the above points. For each potential issue:

1. Clearly state the problem or concern you've identified.
2. Provide specific examples or quotes from the document that support your observation.
3. Explain why this is problematic and what implications it may have.

Present your findings using the following format:

<analysis>
<issue_category>
<problem>[Describe the specific issue]</problem>
<evidence>[Provide relevant quotes or examples from the document]</evidence>
<implications>[Explain why this is problematic and its potential consequences]</implications>
</issue_category>
</analysis>

If you cannot determine whether a particular issue exists due to lack of information, clearly state this and explain what additional context would be needed to make a proper assessment. For example:

<analysis>
<issue_category>
<problem>Unable to assess potential conflicts of interest</problem>
<explanation>The document mentions individuals by name but does not provide their roles or affiliations. Without this information, it's not possible to determine if there are any undisclosed conflicts of interest.</explanation>
</issue_category>
</analysis>

After addressing all potential issues, provide a brief summary of your overall analysis:

<summary>
[Summarize the key findings, highlighting the most significant issues identified and their potential impact on the credibility or validity of the document's contents.]
</summary>

Remember to maintain a critical and thorough approach throughout your analysis, and be sure to support all your observations with specific evidence from the document.