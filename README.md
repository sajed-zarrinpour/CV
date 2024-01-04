# CV
My own simple CV in latex
Usage:
`\name{ Your Name }`
Print your name at the begining of your CV.

\contactInfo{ Adress }{ Phone }{ Email }{ Web Page }{ LinkedIn }

\eduEntry{ Start Year-End Year }{ University }{ Degree }{ Thesis }

\expEntry{ Start Date \\- End Date }{ Title }{ Company }{ Location }
{
	% IMPORTANT : entries to this list are devided by ;  (remember to seperate lines by comments (%) so it will not intrupt the command and remain readable)
	%if you want a paragraph here which your list indents according to that; write your paragraph and end it with a ; and then leave a blank line before next item
	\explist{ 
		Paragraph;
	
		item 1;
		%
		item 2;
		%
		item 3
	}
}

\interestslist{ item1, item2, item3 }

\confEntry{ Date }{ Title }{ Host }

\languageEnry{ Language Name }{ Profiecency }

\selfAssessedEng{ Listening }{ Reading }{ Spoken Interaction }{ Spoken Production }{ Writing }

\skills{ item1, item2, item3 }

\refEntry{ Relation }{ Title & Name }{ Position }{ eMail }{ Address }