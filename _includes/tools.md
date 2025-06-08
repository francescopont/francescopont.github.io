<h1 id="tools"></h1>
<h2 style="margin: 60px 0px 10px;">Tools</h2>
<h3 style="margin: 20px 0px 0px;">
<a href='https://github.com/michiari/POMC'>POMC</a>
</h3>
The Precedence Oriented Model Checker is a model checker for recursive procedural programs and context-free properties such as pre/post conditions and exception safety. It supports a custom domain-specific programming language, MiniProc, and specifications expressed in the logic <a href='https://doi.org/10.46298/lmcs-18(3:11)2022'>POTL</a> (standing for Precedence Oriented Temporal Logic). The tool is written in Haskell.

<h3 style="margin: 20px 0px 0px;">
<a href='https://github.com/michiari/POMC'>POPACheck</a>
</h3>
An extension of POMC towards the verification of probabilistic recursive programs. It support a custom domain-specific programming language, MiniProb, and specifications in LTL and a fragment of POTL. The extension is written in Haskell as well.

<h3 style="margin: 20px 0px 0px;">
<a href='https://github.com/probing-lab/HyperPAYNT'> HyperPAYNT </a> / <a href='https://github.com/francescopont/hyper-synthesis'> PHSynt </a>
</h3>
Two tools for synthesizing controllers for  Markov Decision Processes against probabilistic hyperproperty specifications. They are extensions of <a href='https://github.com/randriu/synthesis'>PAYNT</a>, and use a customized version of <a href='https://www.stormchecker.org/'>STORM</a> as underlying model checker. The tools are written in Python.