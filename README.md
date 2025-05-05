# com2041-lab-1-lexical-analysis-and-parsing-solved
**TO GET THIS SOLUTION VISIT:** [COM2041 Lab 1-Lexical Analysis and Parsing Solved](https://www.ankitcodinghub.com/product/com2041-lab-1-lexical-analysis-and-parsing-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;99813&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COM2041 Lab 1-Lexical Analysis and Parsing Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Tutorial #1 &amp;&amp; 2: “Lexical Analysis and Parsing”

Objective:

To learn the lexical and syntax analysis of context-free grammars using lex&amp;yacc and to design a syntax analyzer for your own pogramming language.

Background Information:

Read “lexyacc.pdf” in the course homepage.

Implementation:

You will design a lexical and syntax analyzer for your own programming language. Give some rules for your programming language and call it as MPL (My Programming Language). For example, your rules may be as;

<ul>
<li>– &nbsp;all programs must start with “begin” and end with “end”</li>
<li>– &nbsp;all commands must be ended by “;”</li>
<li>– &nbsp;all variables must be declared just after “begin” in the following format;
int: i num;

float: fl;
</li>
<li>– &nbsp;three types exist; “int”, “float”, “char”</li>
<li>– &nbsp;variables names may be any alphanumeric string, but they must start with a letter</li>
<li>– &nbsp;statements between “begin” and “end” can be either a variable declaration or an assignment</li>
<li>– &nbsp;an assignment includes four type of operators; +,-,*,/.</li>
<li>– &nbsp;the number of variables or constants in an expression is unlimited</li>
<li>– &nbsp;the presedence of operators given as…………..</li>
<li>– &nbsp;……..</li>
<li>– &nbsp;.etc
The minimum requirements are: a well defined regular grammar for variable names, rules for variable declerations, at least 4 arithmetic, 2 logical and 2 comparison operators with their presedence and associativity rules, at least one conditional statement (like if, switch) and at least one loop structure (like for, while, do-while, repeat-until…). Instead of using the grammar for C langugae, try to bring new ideas for your language.

After writing CFG rules for your language, design and implement a syntax analyzer for it. This analyzer will include a lex source (e.g mpl.l), a yacc source (e.g mpl.y) and example inputs (source codes written in your language, e.g myprog.mpl).

To test your analyzer, follow the steps below;

<pre>     $ lex mpl.l
     $ yacc mpl.y
     $ gcc –o mpl y.tab.c –lfl
     $ mpl &lt; myprog.mpl
</pre>
In the last step, if there is no syntax error in myprog.mpl, the program should give an “OK” message, otherwise, a “syntax error” message. Check your program for correct and wrong inputs.

Note: Do not deal with any semantic rule, just give syntax rules!

Report:

Your report should include; (1) description of the rules which you designed (in your own words) (2)details of your grammar in BNF or EBNF notation, (3)code descriptions, (4)the
</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
BİL240 PROGRAMMING LANGUAGES Tutorial #1 &amp;&amp; 2: “Lexical Analysis and Parsing”

content of mpl.l, mpl.y files and an example myprog.mpl file, (5)any explanation which clarifies that you made your assingment with your own effort.

</div>
</div>
</div>
