## Evaluating Tools for AMR Detection and the Role of AI in Data Analysis

### Learning outcomes

At the end of the session, participants should be able to: - Use
Pathogenwatch and ResFinder to analyze AMR genes. - Compare AMR
predictions from different tools. - Apply AI tools such as ChatGPT and
claude.ai to facilitate data analysis and interpretation.

### Prerequisites

Please use one of the following web browsers: Google Chrome or Mozilla
Firefox.

Create an account with <https://pathogen.watch/>, an account with
<https://chatgpt.com/> and one with <https://claude.ai/new>

### Training materials used in this workshop

-   [FASTA
    files](https://github.com/WCSCourses/SAGESA-AMR-Genomics-Network/tree/main/docs/fasta)

-   [AMR prediction
    tables](https://github.com/WCSCourses/SAGESA-AMR-Genomics-Network/tree/main/docs/results%20files)

### Hands-on exercises and discussion

<table style="width:100%;">
<colgroup>
<col style="width: 84%" />
<col style="width: 12%" />
<col style="width: 2%" />
</colgroup>
<tbody>
<tr class="odd">
<td rowspan="2"><h1 id="amr-gene-identification-using-pathogenwatch">1.
AMR gene identification using Pathogenwatch</h1>
<p>Navigate to the following Pathogenwatch collection <a
href="https://pathogen.watch/collection/njne391gukeu-s-aureus-assessment"
class="uri">https://pathogen.watch/collection/njne391gukeu-s-aureus-assessment</a></p></td>
<td
rowspan="2"></td>
<td></td>
</tr>
<tr class="even">
<td></td>
</tr>
<tr class="odd">
<td>Explore the Genes and the Variants tab in Pathogenwatch</td>
<td colspan="2"><img src="images/pw%20genes.png" style="width:20.0%" />
| | <img src="images/pw%20genes2.png" style="width:25.0%" /></td>
</tr>
<tr class="even">
<td>Download the AMR SNPs and AMR genes tables.</td>
<td><img src="images/pw%20amr%20profile.png" style="width:20.0%" /></td>
<td></td>
</tr>
<tr class="odd">
<td>Check the information found in AMR SNPs and AMR genes tables using a
table visualisation program such as Excel or Google spreadsheets.</td>
<td></td>
<td></td>
</tr>
<tr class="even">
<td><p>Attempt to download a genome in .fasta format from
Pathogenwatch.</p>
<p>In the search bar at the top, type “G18255058”</p></td>
<td><img src="images/pw%20search%20bar.png" width="20%" /></td>
<td></td>
</tr>
<tr class="odd">
<td>Download the assembled genomes in fasta format by pressing the .fa
icon.</td>
<td><img src="images/pw%20download%20genome.png" width="100%" /></td>
<td></td>
</tr>
<tr class="even">
<td><ol start="2" type="1">
<li><strong>AMR gene identification using Resfinder</strong></li>
</ol></td>
<td></td>
<td></td>
</tr>
<tr class="odd">
<td>Navigate to <a href="http://genepi.food.dtu.dk/resfinder"
class="uri">http://genepi.food.dtu.dk/resfinder</a></td>
<td></td>
<td></td>
</tr>
<tr class="even">
<td>In the Select species box, select “Staphylococcus aureus”</td>
<td><img src="images/resfinder%20select%20species.png"
width="100%" /></td>
<td></td>
</tr>
<tr class="odd">
<td>Select input type as “FASTA”.</td>
<td><img src="images/resfinder%20select%20fasta.png" width="100%" /></td>
<td></td>
</tr>
<tr class="even">
<td>Upload the .fasta file you’ve downloaded from Pathogenwatch, or one
of the fasta files in <a
href="https://github.com/WCSCourses/SAGESA-AMR-Genomics-Network/tree/main/docs/fasta">this</a>
folder. Press “Submit Job”.</td>
<td><img src="images/resfinder%20submit%20job.png" width="100%"/></td>
<td></td>
</tr>
<tr class="odd">
<td><p>When the results are loaded, download the “Results as
tabseparated file”, from the “AMR gene results”.</p>
<p>Open this file and check the output format.</p>
<p>In case Resfinder did not produce a result for you, you can visualise
an example output, for one sample, <a
href="https://github.com/WCSCourses/SAGESA-AMR-Genomics-Network/blob/main/docs/results%20files/Resfinder%20one%20sample%20example.txt">here</a>.</p></td>
<td><img src="images/resfinder%20download.png" width="100%" /></td>
<td></td>
</tr>
<tr class="even">
<td><ol start="3" type="1">
<li><strong>Comparing Pathogenwatch and Resfinder AMR genes
identification for 6 samples.</strong></li>
</ol></td>
<td></td>
<td></td>
</tr>
<tr class="odd">
<td><p>Previously, we ran Pathogenwatch and Resfinder for 6
Staphylococcus aureus whole genome sequences stored on <a
href="https://github.com/WCSCourses/SAGESA-AMR-Genomics-Network/tree/main/docs/fasta">Github</a>.</p>
<p>The aggregated results for the 6 samples have been stored on
Github.</p>
<p>Check the results produced by <a
href="https://github.com/WCSCourses/SAGESA-AMR-Genomics-Network/blob/main/docs/results%20files/PW.csv">Pathogenwatch</a>
and the results produced by <a
href="https://github.com/WCSCourses/SAGESA-AMR-Genomics-Network/blob/main/docs/results%20files/Resfinder.csv">Resfinder</a>.</p>
<p>Do you see any difference?</p></td>
<td></td>
<td></td>
</tr>
<tr class="even">
<td><p>(Optional) Here is a Python script to help you compare the
results from Pathogenwatch and Resfinder.</p>
<p><a
href="https://colab.research.google.com/github/monicaiabrudan/bacterial-genomics/blob/main/Compare_AMR_files.ipynb"
class="uri">https://colab.research.google.com/github/monicaiabrudan/bacterial-genomics/blob/main/Compare_AMR_files.ipynb</a></p></td>
<td></td>
<td></td>
</tr>
<tr class="odd">
<td>Go to <a href="https://chatgpt.com/"
class="uri">https://chatgpt.com/</a></td>
<td><img src="images/chatgpt%20upload1.png" width="100%" /></td>
<td></td>
</tr>
<tr class="even">
<td>Upload the results produced by <a
href="https://github.com/WCSCourses/SAGESA-AMR-Genomics-Network/blob/main/docs/results%20files/PW.csv">Pathogenwatch</a>
and the results produced by <a
href="https://github.com/WCSCourses/SAGESA-AMR-Genomics-Network/blob/main/docs/results%20files/Resfinder.csv">Resfinder</a>
and input the following prompt “Compare the PW and the Resfinder
results. Which genes were identified by both methods?”.</td>
<td><img src="images/chatgpt%20upload2.png" width="100%" /></td>
<td></td>
</tr>
<tr class="odd">
<td><p>This is an example of a ChatGPT answer. You might have got a
different answer, depending on the model you’ve used!</p>
<p>How to you interpret the answers?</p>
<p>Compare ChatGPT’s AMR gene identification with manual method. Are the
results identical? Where do they differ?</p>
<p>Look at the genes “ermC” and “erm(C)”.</p>
<p>Was ChatGPT able to realise these were one and the same?</p></td>
<td><img src="images/chatgpt%20output%20example1.png" width="100%" /></td>
<td></td>
</tr>
<tr class="even">
<td>(Optional) If you have the option, try running the tasks above using
a different model of ChatGPT.</td>
<td><img src="images/chatgpt%20models.png" width="100%" /></td>
<td></td>
</tr>
<tr class="odd">
<td>Go to <a href="https://claude.ai/new"
class="uri">https://claude.ai/new</a></td>
<td></td>
<td></td>
</tr>
<tr class="even">
<td>Upload the results produced by <a
href="https://github.com/WCSCourses/SAGESA-AMR-Genomics-Network/blob/main/docs/results%20files/PW.csv">Pathogenwatch</a>
and the results produced by <a
href="https://github.com/WCSCourses/SAGESA-AMR-Genomics-Network/blob/main/docs/results%20files/Resfinder.csv">Resfinder</a>.</td>
<td><img src="images/claude%20upload.png" width="200%" /></td>
<td></td>
</tr>
<tr class="odd">
<td>Type the following prompt: Compare the PW and the Resfinder results.
Which genes were identified by both methods?”</td>
<td><img src="images/claude%20prompt.png" width="200%" /></td>
<td></td>
</tr>
<tr class="even">
<td><p>An example of a result from Claude.ai</p>
<p>How to you interpret the answers?</p>
<p>Compare Claude.ai AMR gene identification with manual method. Are the
results identical? Where do they differ?</p>
<p>Look at the genes “ermC” and “erm(C)”.</p>
<p>Was Claude.ai able to realise these were one and the same?</p></td>
<td><img src="images/clause%20results.png" width="200%"/></td>
<td></td>
</tr>
<tr class="odd">
<td><p><strong>Important note:</strong></p>
<p><strong>Importance of Validation</strong>: Always cross-check LLM
outputs against known databases (e.g., <strong>CARD</strong>,
<strong>ResFinder</strong>, <strong>ARG-ANNOT</strong>) or relevant
literature to ensure the accuracy of gene–drug resistance
links.</p></td>
<td></td>
<td></td>
</tr>
</tbody>
</table>
