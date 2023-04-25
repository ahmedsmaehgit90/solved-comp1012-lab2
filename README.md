Download Link: https://assignmentchef.com/product/solved-comp1012-lab2
<br>
<h2 id="exercise-1-getting-input">Exercise 1: Getting input</h2>

We can request input from the user using the <code>input</code> function.

<code>input</code> is provided a <code>string</code> which it displays to the user as a prompt. The prompt should be something meaningful, instructing the user to provide something to the program.

Try running the code:

Modify the above code in Spyder to ask for:

<ol type="1">

 <li>first (given) name,</li>

 <li>last (family) name, and</li>

 <li>a favourite colour.</li>

</ol>

Your output should look like:

<pre><code>Your name is Jerry Smith, and your favourite colour is Yellow</code></pre>

Be sure to use meaningful names for your variables!

<h2 id="exercise-2-getting-numbers">Exercise 2: Getting numbers</h2>

The <code>input</code> function always returns a <code>str</code>ing, but we want to ask our user to enter numbers as input. To convert <code>str</code>ings to numbers, we use the <code>int()</code> or <code>float()</code> functions, which convert <code>str</code>ings into <code>int</code> and <code>float</code> types, respectively.

Try:

For now, we will assume that the user always enters an actual number when we convert to a numeric type. Later, we’ll investigate how to <em>check</em> that the input the user provides is valid.

Write a new script that asks for four (4) numbers and stores the four (4) numbers in four (4) distinct variables. You will need to call <code>input</code> four (4) times to do this. Once you’ve got all four (4) numbers, compute and print out the sum, and the average of these numbers. Use string formatting to only show four (4) decimal places for the average.

Your output should look like:

<pre><code>Sum: 10Average: 2.5000</code></pre>

<h2 id="exercise-3-bmi-calculation">Exercise 3: BMI Calculation</h2>

Write a complete script that will prompt the user for:

<ol type="1">

 <li>their weight (in kilograms),</li>

 <li>their height (in centimetres)</li>

</ol>

Then, calculate and report their <a href="https://en.wikipedia.org/wiki/Body_mass_index">body-mass index</a>. The BMI formula is:

<span class="math display"><span class="mjx-chtml MJXc-display"><span id="MathJax-Element-1-Frame" class="mjx-chtml MathJax_CHTML" style="display: inline-block; line-height: 0; text-indent: 0px; text-align: center; text-transform: none; font-style: normal; font-weight: normal; font-size: 16.16px; letter-spacing: normal; overflow-wrap: normal; word-spacing: normal; white-space: nowrap; float: none; direction: ltr; max-width: none; max-height: none; min-width: 0px; min-height: 0px; border: 0px; margin: 0px; padding: 1px 0px; position: relative;" tabindex="0" role="presentation" data-mathml="<math xmlns=&quot;http://www.w3.org/1998/Math/MathML&quot; display=&quot;block&quot;><mtext>BMI</mtext><mo>=</mo><mfrac><mi>w</mi><msup><mi>h</mi><mn>2</mn></msup></mfrac></math>"><span id="MJXc-Node-1" class="mjx-math" aria-hidden="true"><span id="MJXc-Node-2" class="mjx-mrow"><span id="MJXc-Node-3" class="mjx-mtext"><span class="mjx-char MJXc-TeX-main-R">BMI</span></span><span id="MJXc-Node-4" class="mjx-mo MJXc-space3"><span class="mjx-char MJXc-TeX-main-R">=</span></span><span id="MJXc-Node-5" class="mjx-mfrac MJXc-space3"><span class="mjx-box MJXc-stacked"><span class="mjx-numerator"><span id="MJXc-Node-6" class="mjx-mi"><span class="mjx-char MJXc-TeX-math-I">w</span></span></span><span class="mjx-denominator"><span id="MJXc-Node-7" class="mjx-msubsup"><span class="mjx-base"><span id="MJXc-Node-8" class="mjx-mi"><span class="mjx-char MJXc-TeX-math-I">h</span></span></span><span class="mjx-sup"><span id="MJXc-Node-9" class="mjx-mn"><span class="mjx-char MJXc-TeX-main-R">2</span></span></span></span></span></span></span></span></span><span class="MJX_Assistive_MathML MJX_Assistive_MathML_Block" role="presentation">BMI=wh2</span></span></span></span>

Where <span class="math inline"><span id="MathJax-Element-2-Frame" class="mjx-chtml MathJax_CHTML" style="display: inline-block; line-height: 0; text-indent: 0px; text-align: left; text-transform: none; font-style: normal; font-weight: normal; font-size: 16.16px; letter-spacing: normal; overflow-wrap: normal; word-spacing: normal; white-space: nowrap; float: none; direction: ltr; max-width: none; max-height: none; min-width: 0px; min-height: 0px; border: 0px; margin: 0px; padding: 1px 0px; position: relative;" tabindex="0" role="presentation" data-mathml="<math xmlns=&quot;http://www.w3.org/1998/Math/MathML&quot;><mi>w</mi></math>"><span id="MJXc-Node-10" class="mjx-math" aria-hidden="true"><span id="MJXc-Node-11" class="mjx-mrow"><span id="MJXc-Node-12" class="mjx-mi"><span class="mjx-char MJXc-TeX-math-I">w</span></span></span></span><span class="MJX_Assistive_MathML" role="presentation">w</span></span></span> is weight in kg, and <span class="math inline"><span id="MathJax-Element-3-Frame" class="mjx-chtml MathJax_CHTML" style="display: inline-block; line-height: 0; text-indent: 0px; text-align: left; text-transform: none; font-style: normal; font-weight: normal; font-size: 16.16px; letter-spacing: normal; overflow-wrap: normal; word-spacing: normal; white-space: nowrap; float: none; direction: ltr; max-width: none; max-height: none; min-width: 0px; min-height: 0px; border: 0px; margin: 0px; padding: 1px 0px; position: relative;" tabindex="0" role="presentation" data-mathml="<math xmlns=&quot;http://www.w3.org/1998/Math/MathML&quot;><mi>h</mi></math>"><span id="MJXc-Node-13" class="mjx-math" aria-hidden="true"><span id="MJXc-Node-14" class="mjx-mrow"><span id="MJXc-Node-15" class="mjx-mi"><span class="mjx-char MJXc-TeX-math-I">h</span></span></span></span><span class="MJX_Assistive_MathML" role="presentation">h</span></span></span> is height in metres.

Convert the height you read in from centimeters to meters, then report the BMI to two decimal places.

Your output should look something like (<mark>highlighted</mark> text means the user typed this in):

<pre>What is your weight in kgs? &gt; <mark>90</mark>What is your height in cm? &gt; <mark>180</mark>Your BMI is 27.78</pre>

<h2 id="exercise-4-jump-height-calculator">Exercise 4: Jump height calculator</h2>

Given the <a href="https://www.physicsclassroom.com/class/1DKin/Lesson-6/Kinematic-Equations">kinematic equation</a>:

<span class="math display"><span class="mjx-chtml MJXc-display"><span id="MathJax-Element-4-Frame" class="mjx-chtml MathJax_CHTML" style="display: inline-block; line-height: 0; text-indent: 0px; text-align: center; text-transform: none; font-style: normal; font-weight: normal; font-size: 16.16px; letter-spacing: normal; overflow-wrap: normal; word-spacing: normal; white-space: nowrap; float: none; direction: ltr; max-width: none; max-height: none; min-width: 0px; min-height: 0px; border: 0px; margin: 0px; padding: 1px 0px; position: relative;" tabindex="0" role="presentation" data-mathml="<math xmlns=&quot;http://www.w3.org/1998/Math/MathML&quot; display=&quot;block&quot;><msubsup><mi>v</mi><mi>f</mi><mn>2</mn></msubsup><mo>=</mo><msubsup><mi>v</mi><mi>i</mi><mn>2</mn></msubsup><mo>+</mo><mn>2</mn><mo>&amp;#x00D7;</mo><mi>a</mi><mo>&amp;#x00D7;</mo><mi>d</mi></math>"><span id="MJXc-Node-16" class="mjx-math" aria-hidden="true"><span id="MJXc-Node-17" class="mjx-mrow"><span id="MJXc-Node-18" class="mjx-msubsup"><span class="mjx-base"><span id="MJXc-Node-19" class="mjx-mi"><span class="mjx-char MJXc-TeX-math-I">v</span></span></span><span class="mjx-stack"><span class="mjx-sup"><span id="MJXc-Node-21" class="mjx-mn"><span class="mjx-char MJXc-TeX-main-R">2</span></span></span><span class="mjx-sub"><span id="MJXc-Node-20" class="mjx-mi"><span class="mjx-char MJXc-TeX-math-I">f</span></span></span></span></span><span id="MJXc-Node-22" class="mjx-mo MJXc-space3"><span class="mjx-char MJXc-TeX-main-R">=</span></span><span id="MJXc-Node-23" class="mjx-msubsup MJXc-space3"><span class="mjx-base"><span id="MJXc-Node-24" class="mjx-mi"><span class="mjx-char MJXc-TeX-math-I">v</span></span></span><span class="mjx-stack"><span class="mjx-sup"><span id="MJXc-Node-26" class="mjx-mn"><span class="mjx-char MJXc-TeX-main-R">2</span></span></span><span class="mjx-sub"><span id="MJXc-Node-25" class="mjx-mi"><span class="mjx-char MJXc-TeX-math-I">i</span></span></span></span></span><span id="MJXc-Node-27" class="mjx-mo MJXc-space2"><span class="mjx-char MJXc-TeX-main-R">+</span></span><span id="MJXc-Node-28" class="mjx-mn MJXc-space2"><span class="mjx-char MJXc-TeX-main-R">2</span></span><span id="MJXc-Node-29" class="mjx-mo MJXc-space2"><span class="mjx-char MJXc-TeX-main-R">×</span></span><span id="MJXc-Node-30" class="mjx-mi MJXc-space2"><span class="mjx-char MJXc-TeX-math-I">a</span></span><span id="MJXc-Node-31" class="mjx-mo MJXc-space2"><span class="mjx-char MJXc-TeX-main-R">×</span></span><span id="MJXc-Node-32" class="mjx-mi MJXc-space2"><span class="mjx-char MJXc-TeX-math-I">d</span></span></span></span><span class="MJX_Assistive_MathML MJX_Assistive_MathML_Block" role="presentation">vf2=vi2+2×a×d</span></span></span></span>

Make a calculator that calculates how high a jump will be, given the velocity at the start of the jump. You’re going to have to <em>rewrite</em> this equation to solve for <span class="math inline"><span id="MathJax-Element-5-Frame" class="mjx-chtml MathJax_CHTML" style="display: inline-block; line-height: 0; text-indent: 0px; text-align: left; text-transform: none; font-style: normal; font-weight: normal; font-size: 16.16px; letter-spacing: normal; overflow-wrap: normal; word-spacing: normal; white-space: nowrap; float: none; direction: ltr; max-width: none; max-height: none; min-width: 0px; min-height: 0px; border: 0px; margin: 0px; padding: 1px 0px; position: relative;" tabindex="0" role="presentation" data-mathml="<math xmlns=&quot;http://www.w3.org/1998/Math/MathML&quot;><mi>d</mi></math>"><span id="MJXc-Node-33" class="mjx-math" aria-hidden="true"><span id="MJXc-Node-34" class="mjx-mrow"><span id="MJXc-Node-35" class="mjx-mi"><span class="mjx-char MJXc-TeX-math-I">d</span></span></span></span><span class="MJX_Assistive_MathML" role="presentation">d</span></span></span>.

<strong>Reminder</strong>: the acceleration of gravity is <span class="math inline"><span id="MathJax-Element-6-Frame" class="mjx-chtml MathJax_CHTML" style="display: inline-block; line-height: 0; text-indent: 0px; text-align: left; text-transform: none; font-style: normal; font-weight: normal; font-size: 16.16px; letter-spacing: normal; overflow-wrap: normal; word-spacing: normal; white-space: nowrap; float: none; direction: ltr; max-width: none; max-height: none; min-width: 0px; min-height: 0px; border: 0px; margin: 0px; padding: 1px 0px; position: relative;" tabindex="0" role="presentation" data-mathml="<math xmlns=&quot;http://www.w3.org/1998/Math/MathML&quot;><mn>9.8</mn><mfrac><mi>m</mi><msup><mi>s</mi><mn>2</mn></msup></mfrac></math>"><span id="MJXc-Node-36" class="mjx-math" aria-hidden="true"><span id="MJXc-Node-37" class="mjx-mrow"><span id="MJXc-Node-38" class="mjx-mn"><span class="mjx-char MJXc-TeX-main-R">9.8</span></span><span id="MJXc-Node-39" class="mjx-mfrac"><span class="mjx-box MJXc-stacked"><span class="mjx-numerator"><span id="MJXc-Node-40" class="mjx-mi"><span class="mjx-char MJXc-TeX-math-I">m</span></span></span><span class="mjx-denominator"><span id="MJXc-Node-41" class="mjx-msubsup"><span class="mjx-base"><span id="MJXc-Node-42" class="mjx-mi"><span class="mjx-char MJXc-TeX-math-I">s</span></span></span><span class="mjx-sup"><span id="MJXc-Node-43" class="mjx-mn"><span class="mjx-char MJXc-TeX-main-R">2</span></span></span></span></span></span></span></span></span><span class="MJX_Assistive_MathML" role="presentation">9.8ms2</span></span></span>.

Write the calculations in two ways: once using the <code>**</code> operator, and once using <code>math.pow()</code>. Are the outputs any different? Is either of these versions more <em>readable</em> than the other? You will have to <code>import math</code> to be use the <code>pow()</code> function.

Your output should look something like (<mark>highlighted</mark> text means the user typed this in):

<pre>How fast were you when you left the ground, in m/s? &gt; <mark>3</mark>You have jumped 0.4591836734693877m in that jump</pre>

<strong>Note</strong>: Remember that at the end of a jump (the final velocity), your speed is 0.

<h2 id="bonus-question-pokémon-damage-calculator">Bonus Question: Pokémon Damage Calculator</h2>

Pokémon involves a lot of fairly complicated math behind the scenes. Below is <a href="https://bulbapedia.bulbagarden.net/wiki/Damage">the formula</a> to calculate base damage, assuming no modifiers. Given the level of the attacking Pokémon and the other relevant stats seen below, calculate the base damage as shown here.

<span class="math display"><span class="mjx-chtml MJXc-display"><span id="MathJax-Element-7-Frame" class="mjx-chtml MathJax_CHTML" style="display: inline-block; line-height: 0; text-indent: 0px; text-align: center; text-transform: none; font-style: normal; font-weight: normal; font-size: 16.16px; letter-spacing: normal; overflow-wrap: normal; word-spacing: normal; white-space: nowrap; float: none; direction: ltr; max-width: none; max-height: none; min-width: 0px; min-height: 0px; border: 0px; margin: 0px; padding: 1px 0px; position: relative;" tabindex="0" role="presentation" data-mathml="<math xmlns=&quot;http://www.w3.org/1998/Math/MathML&quot; display=&quot;block&quot;><mtext>Base Damage</mtext><mo>=</mo><mrow><mo>&amp;#x230A;</mo><mfrac><mrow><mo>&amp;#x230A;</mo><mfrac><mrow><mrow><mo>&amp;#x230A;</mo><mrow><mfrac><mrow><mn>2</mn><mo>&amp;#x00D7;</mo><mtext>Level</mtext></mrow><mn>5</mn></mfrac><mo>+</mo><mn>2</mn></mrow><mo>&amp;#x230B;</mo></mrow><mo>&amp;#x00D7;</mo><mtext>Base Power</mtext><mo>&amp;#x00D7;</mo><mtext>Attack</mtext></mrow><mtext>Defense</mtext></mfrac><mo>&amp;#x230B;</mo></mrow><mn>50</mn></mfrac><mo>&amp;#x230B;</mo></mrow><mo>+</mo><mn>2</mn></math>"><span id="MJXc-Node-44" class="mjx-math" aria-hidden="true"><span id="MJXc-Node-45" class="mjx-mrow"><span id="MJXc-Node-46" class="mjx-mtext"><span class="mjx-char MJXc-TeX-main-R">Base Damage</span></span><span id="MJXc-Node-47" class="mjx-mo MJXc-space3"><span class="mjx-char MJXc-TeX-main-R">=</span></span><span id="MJXc-Node-48" class="mjx-mrow MJXc-space3"><span id="MJXc-Node-49" class="mjx-mo"><span class="mjx-delim-v"><span class="mjx-char MJXc-TeX-size4-R">⎢</span><span class="mjx-char MJXc-TeX-size4-R">⎢ ⎢ ⎢ ⎢ ⎢ ⎢ ⎢ ⎢</span><span class="mjx-char MJXc-TeX-size4-R">⎣</span></span></span><span id="MJXc-Node-50" class="mjx-mfrac"><span class="mjx-box MJXc-stacked"><span class="mjx-numerator"><span id="MJXc-Node-51" class="mjx-mrow"><span id="MJXc-Node-52" class="mjx-mo"><span class="mjx-char MJXc-TeX-size4-R">⌊</span></span><span id="MJXc-Node-53" class="mjx-mfrac"><span id="MJXc-Node-54" class="mjx-mrow"><span id="MJXc-Node-55" class="mjx-mrow"><span id="MJXc-Node-56" class="mjx-mo"><span class="mjx-char MJXc-TeX-size2-R">⌊</span></span><span id="MJXc-Node-57" class="mjx-mrow"><span id="MJXc-Node-58" class="mjx-mfrac"><span id="MJXc-Node-59" class="mjx-mrow"><span id="MJXc-Node-60" class="mjx-mn"><span class="mjx-char MJXc-TeX-main-R">2</span></span><span id="MJXc-Node-61" class="mjx-mo"><span class="mjx-char MJXc-TeX-main-R">×</span></span><span id="MJXc-Node-62" class="mjx-mtext"><span class="mjx-char MJXc-TeX-main-R">Level</span></span></span><span class="mjx-denominator"><span id="MJXc-Node-63" class="mjx-mn"><span class="mjx-char MJXc-TeX-main-R">5</span></span></span></span><span id="MJXc-Node-64" class="mjx-mo"><span class="mjx-char MJXc-TeX-main-R">+</span></span><span id="MJXc-Node-65" class="mjx-mn"><span class="mjx-char MJXc-TeX-main-R">2</span></span></span><span id="MJXc-Node-66" class="mjx-mo"><span class="mjx-char MJXc-TeX-size2-R">⌋</span></span></span><span id="MJXc-Node-67" class="mjx-mo"><span class="mjx-char MJXc-TeX-main-R">×</span></span><span id="MJXc-Node-68" class="mjx-mtext"><span class="mjx-char MJXc-TeX-main-R">Base Power</span></span><span id="MJXc-Node-69" class="mjx-mo"><span class="mjx-char MJXc-TeX-main-R">×</span></span><span id="MJXc-Node-70" class="mjx-mtext"><span class="mjx-char MJXc-TeX-main-R">Attack</span></span></span><span class="mjx-denominator"><span id="MJXc-Node-71" class="mjx-mtext"><span class="mjx-char MJXc-TeX-main-R">Defense</span></span></span></span><span id="MJXc-Node-72" class="mjx-mo"><span class="mjx-char MJXc-TeX-size4-R">⌋</span></span></span></span><span class="mjx-denominator"><span id="MJXc-Node-73" class="mjx-mn"><span class="mjx-char MJXc-TeX-main-R">50</span></span></span></span></span><span id="MJXc-Node-74" class="mjx-mo"><span class="mjx-delim-v"><span class="mjx-char MJXc-TeX-size4-R">⎥</span><span class="mjx-char MJXc-TeX-size4-R">⎥ ⎥ ⎥ ⎥ ⎥ ⎥ ⎥ ⎥</span><span class="mjx-char MJXc-TeX-size4-R">⎦</span></span></span></span><span id="MJXc-Node-75" class="mjx-mo MJXc-space2"><span class="mjx-char MJXc-TeX-main-R">+</span></span><span id="MJXc-Node-76" class="mjx-mn MJXc-space2"><span class="mjx-char MJXc-TeX-main-R">2</span></span></span></span><span class="MJX_Assistive_MathML MJX_Assistive_MathML_Block" role="presentation">Base Damage=⌊⌊⌊2×Level5+2⌋×Base Power×AttackDefense⌋50⌋+2</span></span></span></span>

Reminder: The floor function shown here (<span class="math inline"><span id="MathJax-Element-8-Frame" class="mjx-chtml MathJax_CHTML" style="display: inline-block; line-height: 0; text-indent: 0px; text-align: left; text-transform: none; font-style: normal; font-weight: normal; font-size: 16.16px; letter-spacing: normal; overflow-wrap: normal; word-spacing: normal; white-space: nowrap; float: none; direction: ltr; max-width: none; max-height: none; min-width: 0px; min-height: 0px; border: 0px; margin: 0px; padding: 1px 0px; position: relative;" tabindex="0" role="presentation" data-mathml="<math xmlns=&quot;http://www.w3.org/1998/Math/MathML&quot;><mo fence=&quot;false&quot; stretchy=&quot;false&quot;>&amp;#x230A;</mo><mi>x</mi><mo fence=&quot;false&quot; stretchy=&quot;false&quot;>&amp;#x230B;</mo></math>"><span id="MJXc-Node-77" class="mjx-math" aria-hidden="true"><span id="MJXc-Node-78" class="mjx-mrow"><span id="MJXc-Node-79" class="mjx-mo"><span class="mjx-char MJXc-TeX-main-R">⌊</span></span><span id="MJXc-Node-80" class="mjx-mi"><span class="mjx-char MJXc-TeX-math-I">x</span></span><span id="MJXc-Node-81" class="mjx-mo"><span class="mjx-char MJXc-TeX-main-R">⌋</span></span></span></span><span class="MJX_Assistive_MathML" role="presentation">⌊x⌋</span></span></span>) rounds down to the nearest integer. Look in the <a href="https://docs.python.org/3/library/math.html"><code>math</code> library</a> for something that can do this.

Your output should look something like (<mark>highlighted</mark> text means the user typed this in):

<pre>What level is the attacking Pokemon? &gt; <mark>50</mark>What is the attacking Pokemon's ATK stat? &gt; <mark>100</mark>What is the defending Pokemon's DEF stat? &gt; <mark>70</mark>What is the base power of the attack? &gt; <mark>90</mark>The base damage of the attack (before modifiers) is 58</pre>

5/5 - (1 vote)

<pre class="sourceCode python"><code class="sourceCode python"><a id="cb1-1" class="sourceLine" title="1"></a>whatTheyType <span class="op">=</span> <span class="bu">input</span>(<span class="st">'I am the great and powerful fortune-teller. What is your name? &gt; '</span>)<a id="cb1-2" class="sourceLine" title="2"></a><span class="bu">print</span>(<span class="st">"I think your name is </span><span class="sc">{}</span><span class="st">"</span>.<span class="bu">format</span>(whatTheyType))</code></pre>