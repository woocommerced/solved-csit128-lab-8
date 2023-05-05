Download Link: https://assignmentchef.com/product/solved-csit128-lab-8
<br>
Here is a sample of XSD code:

&lt;?xml version=”1.0″ ?&gt;

&lt;xsd:schema xmlns:xsd=”http://www.w3.org/2001/XMLSchema”&gt;

. . .

&lt;/xsd:schema&gt;

<strong>Question 1.</strong> Given the following XML code containing an exam result where score is an integer; and contestant id, exam id, band and digital signature are strings. Your task is to write the corresponding XSD code and save it into the file q1.xsd.

&lt;?xml version=”1.0″?&gt;

&lt;result ref=”10007629P”&gt;

&lt;contestantId&gt;00025142&lt;/contestantId&gt;

&lt;examId&gt;KB253DG&lt;/examId&gt;

&lt;score&gt;156&lt;/score&gt;

&lt;band&gt;C&lt;/band&gt;

&lt;digitalSignature&gt;a720cf8e23bc1256bce2&lt;/digitalSignature&gt; &lt;/result&gt;

<strong>Question 2.</strong> Copy the code from q1.xsd to q2.xsd.​    In q2.xsd, add the following restrictions:

<ul>

 <li>Band values must be A, B, C or D.</li>

 <li>Score values must be an integer between 0 and 300.</li>

</ul>

Here is a sample of restriction code:

&lt;xsd:restriction base=”xsd:integer”&gt;

&lt;xsd:minInclusive value=”0″ /&gt;

&lt;xsd:maxInclusive value=”100″ /&gt;

&lt;/xsd:restriction&gt;

&lt;xsd:restriction base=”xsd:string”&gt;

&lt;xsd:enumeration value=”LARGE” /&gt;

&lt;xsd:enumeration value=”MEDIUM” /&gt;

&lt;xsd:enumeration value=”SMALL” /&gt;

&lt;/xsd:restriction&gt;

<strong>Question 3.</strong> Given the following XML code.​

Your task is to write the corresponding XSD code and save it into the file q3.xsd.

&lt;?xml version=”1.0″?&gt;

&lt;audit campus=”Woolloomooloo” year=”2000″ session=”A”&gt;




&lt;subject sid=”0769642″&gt;

&lt;code&gt;MATH101&lt;/code&gt;

&lt;title&gt;Calculus&lt;/title&gt;

&lt;statistics&gt;

&lt;enrol&gt;170&lt;/enrol&gt;

&lt;withdrawn&gt;31&lt;/withdrawn&gt;

&lt;/statistics&gt;

&lt;/subject&gt;




&lt;subject sid=”1734231″&gt;

&lt;code&gt;MATH234&lt;/code&gt;

&lt;title&gt;Abstract Algebra&lt;/title&gt;

&lt;statistics&gt;

&lt;enrol&gt;40&lt;/enrol&gt;

&lt;withdrawn&gt;15&lt;/withdrawn&gt;

&lt;/statistics&gt;

&lt;/subject&gt;




&lt;/audit&gt;











