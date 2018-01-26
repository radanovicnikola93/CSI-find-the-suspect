# CSI-find-the-suspect
A program that finds and matches a DNA of a suspect
<hr>

<p>The famous CSI just asked to create a forensics program for them. Exciting, right! :)
<br>
But first, they have to teach you a bit about our DNA...</p>
<hr>

<b>DNA crash course</b>

<p>If we look deeply how our body works, it seems like a big computer. Our body cells are like programs - each of them does their own task. Each cell in our body includes DNA where our "code of life" is written. Everything about us is written here: how we look, what eye color we have, how tall are we etc. Of course part of what we are is shaped through our education and life experience, but DNA is responsible for a big chunk of what we are.</p>

<p>The language understood by computers is a binary or machine code (zeros and ones). If we write a computer program in Python, it eventually gets translated into zeros and ones (machine code), so computer knows how to run and execute commands written in the program.</p>

<p>Binary/machine code looks like this:</p>

<p background-color: grey>100011 00011 01000 00000 00001 000100</p>

<p>But language of our DNA code is not in a form of 0s and 1s - it's instead in the form of four letters: A, C, T and G. These letters represent 4 nucleobases: adenine (A), cytosine (C), guanine (G) and thymine (T). So DNA can be written like this:</p>

<p background-color: grey>ACTGCTGCATAGTCTGCAAGACTGAATCACTACGTATCG</p>

<p>This is as much biology as needed to finish this exercise. It's enough to understand that our DNA can be written in a single string made of four letters: A, C, G and T. In this DNA code we can find genes that define our personal characteristics (hair color, eye color, height etc.).</p>

<b>Crime!</b>

<p>There has been a hideous crime! A full container of ice cream was stored in the SmartNinja fridge - and now it's completely empty. But the criminal made a fatal mistake. S/he left a spoon inside the container and with a spoon also his/her DNA. A perfect case for our CSI investigators!</p>


<p>CSI lab successfully extracted the DNA and wrote it in the ACTG code format. The only thing needed now is a program that would match that DNA with the suspects DNA and find the criminal.</p>>

<p>Here's the DNA text:
<br>ACAAGATGCCATTGTCCCCCGGCCTCCTGCTGCTGCTGCTCTCCGGGGCCACGGCCACCGCTGCCCTGCCCCTGGAGGGTGGCCCCACCGGCCGAGACAGCGAGCATATGCAGGAAGCGGCAGGAATAAGGAAAAGCAGCCTCCTGACTTTCCTCGCTTGGTGGTTTGAGTGGACCTCCCAGGCCAGTGCCGGGCCCCTCATAGGAGAGGAAGCTCGGGAGGTGGCCAGGCGGCAGGAAGGCGCACCCCCCCAGCAATCCGCGCGCCGGGACAGAATGCCCTGCAGGAACTTCTTCTGGAAGACCTTCTCCTCCTGCAAATAAAACCTCACCCATGAATGCTCACGCAAGTTTAATTACAGACCTGAA 
<br>
</p>
<p>Like we said there are genes hidden in our DNA that define our personal characteristics. The CSI lab got us the following gene sequences for some of the human characteristics:</p>

<em>Hair color:</em>
<ol>
    <li></li>
    <li></li>
    <li>Black: CCAGCAATCGC</li>
    <li>Brown: GCCAGTGCCG</li>
    <li>Blonde: TTAGCTATCGC</li>
</ol>

<em>Facial shape:</em>
<ol>
    <li>Square: GCCACGG</li>
    <li>Round: ACCACAA</li>
    <li>Oval: AGGCCTCA</li>
</ol>

<em>Eye color:</em>
<ol>
    <li></li>
    <li></li>
    <li>Blue: TTGTGGTGGC</li>
    <li>Green: GGGAGGTGGC</li>
    <li>Brown: AAGTAGTGAC</li>
</ol>

<em>Gender:</em>
<ol>
    <li>Female: TGAAGGACCTTC</li>
    <li>Male: TGCAGGAACTTC</li>
</ol>



<em>Race:</em>
<ol>
    <li>White: AAAACCTCA</li>
    <li>Black: CGACTACAG</li>
    <li>Asian: CGCGGGCCG</li>
</ol>





<p>Please note that these are not real gene sequences and the "DNA" in the file is not a real DNA. It's way too short ;)</p>


<b>Suspects characteristics:</b>

<em>Eva:</em>
<ol>
    <li>Gender: Female</li>
    <li>Race: White</li>
    <li>Hair color: Blonde</li>
    <li>Eye color: Blue</li>
    <li>Face shape: Oval</li>
</ol>






<em>Larisa:</em>

<ol>
    <li>Gender: Female</li>
    <li>Race: White</li>
    <li>Hair color: Brown</li>
    <li>Eye color: Brown</li>
    <li>Face shape: Oval</li>
</ol>

<em>Matej:</em>
<ol>
    <li>Gender: Male</li>
    <li>Race: White</li>
    <li>Hair color: Black</li>
    <li>Eye color: Blue</li>
    <li>Face shape: Oval</li>
</ol>

<em>Miha:</em>
<ol>
    <li>Gender: Male</li>
    <li>Race: White</li>
    <li>Hair color: Brown</li>
    <li>Eye color: Green</li>
    <li>Face shape: Square</li>
</ol>






