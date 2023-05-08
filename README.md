Download Link: https://assignmentchef.com/product/solved-ve216-homework-2
<br>



<ol>

 <li>[3!] Assume a system has the input-output relationship <em>y</em>(<em>t</em>) = <em>f</em>(<em>t</em>)<em>x</em>(<em>t</em>), where <em>x</em>(<em>t</em>) is the input and <em>y</em>(<em>t</em>) is the output. <em>f</em>(<em>t</em>) is not constant, i.e., there exists <em>t</em><sub>0</sub><em>,t</em><sub>1 </sub>that <em>f</em>(<em>t</em><sub>0</sub>) ≠ <em>f</em>(<em>t</em><sub>1</sub>). Show that this system is timevariant. That is, a system with time-variant gain cannot be time-invariant. (<em>Hint: find a counterexample.</em>)</li>

 <li>[9!]Here are input-output relationships for a few systems, all of which are linear. Some of them are timeinvariant, some are not. Determine which are which. Find the impulse response of the time-invariant systems.</li>

</ol>

,

,

.

Hint: Note that if you can transform the above relationships into the exact form of convolution <em>y</em>(<em>t</em>) = <em>g</em>(<em>t</em>) ∗ <em>x</em>(<em>t</em>), then the system is immediately time-invariant with <em>g</em>(<em>t</em>) being the impulse response <em>h</em>(<em>t</em>). That is because different from algebraic operators like multiplication, the convolution operator implies time-invariance itself.

<ol start="3">

 <li>[9!]One of following two statements is correct, and the other is incorrect. The symbol ∗ denotes <em>convolution</em>.

  <ul>

   <li>If <em>y</em>(<em>t</em>) = <em>h</em>(<em>t</em>) ∗ <em>x</em>(<em>t</em>) then <em>y</em>(<em>t </em>− 3) = <em>h</em>(<em>t </em>− 3) ∗ <em>x</em>(<em>t </em>− 3);</li>

   <li>Or if <em>y</em>(<em>t</em>) = <em>h</em>(<em>t</em>) ∗ <em>x</em>(<em>t</em>) then <em>y</em>(<em>t </em>− 3) = <em>h</em>(<em>t</em>) ∗ <em>x</em>(<em>t </em>− 3).</li>

   <li>Give a simple proof of the correct statement.</li>

   <li>Give a simple counterexample for the incorrect statement.</li>

   <li>Repeat (a) and (b) for the following two statements. The symbol denotes <em>multiplication</em>.</li>

   <li>If <em>y</em>(<em>t</em>) = <em>h</em>(<em>t</em>) · <em>x</em>(<em>t</em>) then <em>y</em>(<em>t </em>− 3) = <em>h</em>(<em>t </em>− 3) · <em>x</em>(<em>t </em>− 3);</li>

   <li>Or if <em>y</em>(<em>t</em>) = <em>h</em>(<em>t</em>) · <em>x</em>(<em>t</em>) then <em>y</em>(<em>t </em>− 3) = <em>h</em>(<em>t</em>) · <em>x</em>(<em>t </em>− 3).</li>

  </ul></li>

</ol>

Be careful with the notation <em>h</em>(<em>t</em>) ∗ <em>x</em>(<em>t</em>). More precise notation is (<em>h </em>∗ <em>x</em>)(<em>t</em>), which makes it clear that convolution is an operation on two signals, not a point-wise operation like multiplication.

<ol start="4">

 <li>[8!] Often we will be convolving two signals that are zero everywhere except over some finite range (called <strong>finite support </strong>signals). Suppose <em>x</em><sub>1</sub>(<em>t</em>) is non-zero over the range <em>a </em>≤ <em>t </em>≤ <em>b </em>and that <em>x</em><sub>2</sub>(<em>t</em>) is non-zero over the range <em>c </em>≤ <em>t </em>≤ <em>d</em>. Suppose <em>y</em>(<em>t</em>) = <em>x</em><sub>1</sub>(<em>t</em>) ∗ <em>x</em><sub>2</sub>(<em>t</em>).</li>

</ol>

<ul>

 <li>Find the range of values of <em>t </em>for which <em>y</em>(<em>t</em>) is possibly non-zero.</li>

 <li>Compute <em>rect</em>((<em>t </em>− 2)<em>/</em>2) ∗ <em>rect</em>((<em>t </em>+ 3)<em>/</em>4) (express answer with braces and carefully sketch). Check your result with part (a).</li>

</ul>

<ol start="5">

 <li>[6!] For each of the following pairs of waveforms, use convolution integral to find the response <em>y</em>(<em>t</em>) of the LTI system with impulse response <em>h</em>(<em>t</em>) and input <em>x</em>(<em>t</em>). Sketch your results.

  <ul>

   <li><em>x</em>(<em>t</em>) = <em>e</em><sup>−<em>αt</em></sup><em>u</em>(<em>t</em>)<em>,h</em>(<em>t</em>) = <em>e</em><sup>−<em>βt</em></sup><em>u</em>(<em>t</em>) (Do this both when <em>α </em>= <em>β </em>and <em>α </em>≠ <em>β</em>)</li>

   <li><em>x</em>(<em>t</em>) and <em>h</em>(<em>t</em>) as in the figure below, the slope for the straight line is <em>a </em>and the line intersects y-axis at (0<em>,b</em>):</li>

  </ul></li>

 <li>[6!]

  <ul>

   <li>Consider a linear system with input <em>x</em>(<em>t</em>) and output <em>y</em>(<em>t</em>) given by</li>

  </ul></li>

</ol>

<em>.</em>

Is this system time-invariant?

<ul>

 <li>Consider another LTI system. Let its impulse response <em>h</em>(<em>t</em>) be the triangular pulse shown below, and <em>x</em>(<em>t</em>) be the <strong>impulse train</strong></li>

</ul>

<em>,</em>

SKETCH <em>y</em>(<em>t</em>) = <em>x</em>(<em>t</em>) ∗ <em>h</em>(<em>t</em>) for <em>T </em>= 4<em>,</em>2<em>,</em>1<em>.</em>5 and 1.(No formulae are needed though you still want to label your graphs clearly.)

<em>h</em>(<em>t</em>)

<ol start="7">

 <li>[6!] Let <em>y</em>(<em>t</em>) = (<em>x </em>∗ <em>h</em>)(<em>t</em>). Show the following properties of convolution.</li>

</ol>

,

,

<ol start="8">

 <li>[6!] Compute the following convolution:

  <ul>

   <li><em>u</em>(<em>t</em>) ∗ <em>u</em>(<em>t</em>),</li>

   <li><em>u</em>(<em>t</em>) ∗ <em>t</em><sup>2</sup><em>u</em>(<em>t</em>).</li>

  </ul></li>

 <li>[3!] Suppose you have a ”black box” LTI system and you discover that for a unit-step input signal the response of the system is the function (3 − <em>t</em>)<em>rect</em>(<em><u><sup>t</sup></u></em><u><sup>−</sup></u><sub>2</sub><u><sup>1</sup></u>). Determine the impulse response of the system. (<em>Hint: See Problem 7.</em>)</li>

 <li>[6!] Determine whether the following systems are linear, stable, causal, time-invariant, and memoryless.</li>

 <li>[6!] Consider an LTI system whose response to the signal <em>x</em><sub>1</sub>(<em>t</em>) is the signal <em>y</em><sub>1</sub>(<em>t</em>) which are illustrated below.

  <ul>

   <li>Determine and sketch carefully the response of the system to the input <em>x</em><sub>2</sub>(<em>t</em>) depicted below. (b) Determine and sketch carefully the response of the system to the input <em>x</em><sub>3</sub>(<em>t</em>) depicted below.</li>

  </ul></li>

 <li>[6!] The triangular pulse is defined as tri(<em>t</em>) = (1 − |<em>t</em>|)rect(<em>t/</em>2).</li>

</ol>

Compute <em>x</em>(<em>t</em>) = tri(<em>t/</em>2) ∗ rect(<em><u><sup>t</sup></u></em><u><sup>−</sup></u><sub>2</sub><u><sup>1</sup></u>).Express your answer using braces, and carefully sketch.

<ol start="13">

 <li>[6!] Find the impulse response of the following LTI systems and further determine whether they are causal, stable and static.</li>

 <li>[3!] Consider an LTI system <em>S </em>and a signal <em>x</em>(<em>t</em>) = 2<em>e</em><sup>−3<em>t</em></sup><em>u</em>(<em>t </em>− 1). If</li>

</ol>

<em>x</em>(<em>t</em>) → <em>y</em>(<em>t</em>)

and

determine the impulse response

<ol start="15">

 <li>[12!] We are given a certain LTI system with impulse response <em>h</em><sub>0</sub>(<em>t</em>). We are told that when the input is <em>x</em><sub>0</sub>(<em>t</em>) the output is <em>y</em><sub>0</sub>(<em>t</em>), which is sketched below. We are then given the following set of inputs to LTI systems with the indicated impulse responses.</li>

</ol>

Input <em>x</em>(<em>t</em>)                                Impulse response <em>h</em>(<em>t</em>)

(a)       <em>x</em>(<em>t</em>) = 2<em>x</em><sub>0</sub>(<em>t</em>)                            <em>h</em>(<em>t</em>) = <em>h</em><sub>0</sub>(<em>t</em>)

(b)

<ul>

 <li><sub>0 </sub>− 0</li>

 <li><em>x</em>(<em>t</em>) = <em>x</em><sub>0</sub>(−<em>t</em>) <em>h</em>(<em>t</em>) = <em>h</em><sub>0</sub>(−<em>t</em>)</li>

 <li><em>x</em>(<em>t</em>) = <em>x</em><sup>′</sup><sub>0</sub>(<em>t</em>) <em>h</em>(<em>t</em>) = <em>h</em><sub>0</sub>(<em>t</em>)</li>

 <li><em>x</em>(<em>t</em>) = <em>x</em><sup>′</sup><sub>0</sub>(<em>t</em>) <em>h</em>(<em>t</em>) = <em>h</em><sup>′</sup><sub>0</sub>(<em>t</em>)</li>

</ul>

In each of these cases, determine whether or not we have enough information to determine the output <em>y</em>(<em>t</em>) when the input is <em>x</em>(<em>t</em>) and the system has impulse response <em>h</em>(<em>t</em>). If so, provide an accurate sketch of it with numerical values clearly indicated on the graph.

<ol start="16">

 <li>[5!] Find the expression of response of the CT system described by the linear constant-coefficient differential equation.</li>

</ol>