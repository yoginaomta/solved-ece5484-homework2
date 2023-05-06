Download Link: https://assignmentchef.com/product/solved-ece5484-homework2
<br>
<strong>Homework 2 consists of the following problems.</strong>

<ol>

 <li>Construct a truth table for the following: F = (x + y)(x’ + z’)(y’ + z’)</li>

 <li>Using truth tables, show that:</li>

</ol>

xz = (x+y)(x+y’)(x’+z)

<ol start="3">

 <li>The truth table for a Boolean expression is shown. Write the Boolean expression in sum-of-products form.</li>

</ol>

<table width="77">

 <tbody>

  <tr>

   <td width="23">x</td>

   <td width="23">y</td>

   <td width="23">z</td>

   <td width="9">F</td>

  </tr>

  <tr>

   <td width="23">0</td>

   <td width="23">0</td>

   <td width="23">0</td>

   <td width="9">1</td>

  </tr>

  <tr>

   <td width="23">0</td>

   <td width="23">0</td>

   <td width="23">1</td>

   <td width="9">1</td>

  </tr>

  <tr>

   <td width="23">0</td>

   <td width="23">1</td>

   <td width="23">0</td>

   <td width="9">1</td>

  </tr>

  <tr>

   <td width="23">0</td>

   <td width="23">1</td>

   <td width="23">1</td>

   <td width="9">0</td>

  </tr>

  <tr>

   <td width="23">1</td>

   <td width="23">0</td>

   <td width="23">0</td>

   <td width="9">1</td>

  </tr>

  <tr>

   <td width="23">1</td>

   <td width="23">0</td>

   <td width="23">1</td>

   <td width="9">1</td>

  </tr>

  <tr>

   <td width="23">1</td>

   <td width="23">1</td>

   <td width="23">0</td>

   <td width="9">0</td>

  </tr>

  <tr>

   <td width="23">1</td>

   <td width="23">1</td>

   <td width="23">1</td>

   <td width="9">0</td>

  </tr>

 </tbody>

</table>

<ol start="4">

 <li>Draw the combinational circuit that directly implements the following Boolean expression: F(x,y,z) = y’ + xy + y’z.</li>

 <li>Consider the parity generator (even parity) shown in the truth table below. The parity bit Y is a function of Boolean variables A, B, and C. Represent this parity function in the following ways:</li>

 <li>As a Boolean algebraic expression.</li>

 <li>As a combinational logic diagram (logic circuit).</li>

 <li>Complete the truth table for the following circuit</li>

 <li>Complete the tutorial provided with Logisim 2.7.1. The tutorial is under the “Help” menu in Logisim or at <a href="http://www.cburch.com/logisim/docs/2.7/en/html/guide/tutorial/">http://www.cburch.com/logisim/docs/2.7/en/html/guide/tutorial/.</a> Insert a picture of the circuit,</li>

</ol>

as drawn in Logisim, into your homework submission. INCLUDE A TEXT LABEL WITH YOUR NAME AND DATE. Use the “Export Image” function in the “File” menu to save an image file and then insert that in your submission. Uncheck the “Printer View” box when exporting the image from Logisim. <em>Do not provide the picture as a separate file</em>.

<ol start="8">

 <li>For this problem, you are to design a simple combinational logic circuit and then use Logisim to simulate and test the circuit. The circuit is a 2-bit priority encoder with inputs I<sub>2 </sub>and I<sub>1 </sub>and outputs Z<sub>1 </sub>and Z<sub>0</sub>. The circuit behaves as follows:

  <ul>

   <li>If I<sub>2</sub>I<sub>1 </sub>= 00, then Z<sub>1</sub>Z<sub>0 </sub>= 00 (no active input)</li>

   <li>If I<sub>2</sub>I<sub>1 </sub>= 01, then Z<sub>1</sub>Z<sub>0 </sub>= 01 (low-priority input, I<sub>1</sub>, is active)</li>

   <li>If I<sub>2</sub>I<sub>1 </sub>= 1-, then Z<sub>1</sub>Z<sub>0 </sub>= 10 (high-priority input, I<sub>2</sub>, is active)</li>

  </ul></li>

</ol>

Note that the value of input I<sub>1 </sub>does not matter if the high-priority input, I<sub>2</sub>, is active. Also, output combination Z<sub>1</sub>Z<sub>0 </sub>= 11 should never occur.

<ol>

 <li>Give the truth table that shows outputs Z<sub>1 </sub>and Z<sub>0 </sub>as functions of inputs I<sub>2 </sub>and I<sub>1</sub>.</li>

 <li>Give the Boolean algebra expressions for output Z<sub>1 </sub>and output Z<sub>0</sub>.</li>

 <li>Simulate your circuit using Logisim. Label all inputs and the output. Test for all four input combinations. INCLUDE A TEXT LABEL WITH YOUR NAME AND DATE. Insert a picture of the circuit, as drawn in Logisim, into your homework submission. Uncheck the “Printer View” box when exporting the image from Logisim. Your picture should show the circuit with input combination I<sub>2</sub>I<sub>1 </sub>= 11. <em>Do not provide the picture as a separate file.</em></li>

</ol>

<ol start="9">

 <li><em><sub>Scavenger Hunt: </sub></em>The JK flip-flop is sometimes called the “Jump-Kill” flip-flop. Although disputed, according to some sources it was named “JK” after one of the engineers on the team that designed a JK flip-flop circuit. The engineer’s initials were “JK.” This engineer later won a Nobel Prize.

  <ol>

   <li>Who was this engineer?</li>

   <li>In your own words, why did he receive the Nobel Prize?</li>

  </ol></li>

</ol>