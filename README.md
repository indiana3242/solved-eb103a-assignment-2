Download Link: https://assignmentchef.com/product/solved-eb103a-assignment-2
<br>
The are two assignments. One is to review some course material; two to create an ER diagram with an annotations 54                      file.

55               Precise submission details are given in Section 3.

<h1><a name="_Toc5998"></a>56           2.2        Assignments</h1>

<ul>

 <li>Please read the file University01.pdf and review the implementation of that application as an ER diagram</li>

 <li>in Unit 2.</li>

 <li>For the third-person singular pronoun I will generally use “it” and its declensions.</li>

 <li>Some words are in bold. This has no semantic implications and they are written in this way to make the 61 reading easier.</li>

</ul>

62                  Consider the application described in Section 2.2.1. Do <em>not </em>make any assumptions about the application 63 beyond the specifications listed.

64 Following the notation we used in class, using draw.io and the shapes provided by it, produce an ER diagram 65 for the application. Do not use any other notation. For example, you may not use cardinality constraints in 66 your diagram. Start with the given ER02.drawio and put your own Net ID in the cloud there.

67 Because the software you will use has slight differences compared to what we did, please consult the file 68 NotationForER.pdf so that you know how to produce your diagram. 69 Do not optimize your design, just follow the specification given.

70                  Anything that cannot be specified in your ER diagram, put as annotations in text02.txt file, as described 71    in Item 1 of Section 3, starting with 1. and continuing as needed.

72                  Do <em>not </em>put anything in the annotations that can be reflected in the ER diagram, make sure that the diagram 73                      reflects that. The idea is for you to think what’s needed and where to put it: the diagram or the annotations.

<h1><a name="_Toc5999"></a>74                            2.2.1          The Application</h1>

75                  Note that you cannot make any assumptions that are not forced by the specifications. For example, if the 76                      value of an attribute is not required to be known, you cannot assume that it is always known.

77                  There are Companies. A Company may be Small or Big but cannot be both. Companies have 78           an attribute TIN (Tax Identification Number) and RegNumber (Registration Number) and they are 79   always known. No two Companies can have the same TIN and no two Companies can have the same 80                    RegNumber.

<ul>

 <li>A Company may have one or more Nicknames.</li>

 <li>Small Companies may Help each other and we want to know which Small Company Helps which 83 Small Company. A Small Company may not Help itself.</li>

</ul>

84 There are Managers. Each has the attribute FamName (Family Name) and the attribute PerName 85 (Personal Name), which are always known. No two Managers can have both the same PerName and the

86 same FamName. Managers also have the attributes Salary and Bonus, which are always known. Bonus 87 is computed as 5% of Salary.

88                  A Big Company has the attribute Value. For a Big Company there may be at most one Manager who 89             Supervises it. If a Manager Supervises a Company, that relationship has attribute Start. 90                 The domains of the attributes have not been specified.

<ul>

 <li>Start with the given ER02.drawio but put your own NetID in the cloud drawn there.</li>

 <li>If the system does not allow you to upload ER02.drawio, rename your ER02.drawio to be ER02.txt. Then 93 upload ER02.txt, and state that you have done that in Item 1b of Section 3.</li>

</ul>