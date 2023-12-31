![Banner](/banner.png)
# simple CV

## Import

```\usepackage{simplecv}```

## Name

```\name{<Your Name>}```

> [!IMPORTANT]
> Replace values wrapped in `<` and `>` signs with your actual data.

> [!NOTE]
> Please do not add a space after`{` or `}` symbols in commands. For example use `\name{Sajed Zarinpor}` instead of `\name{ Sajed zarinpour }`


## Contact information

```\contactInfo{<Location>}{<Phone>}{<Email>}{<LinkedIn>}```

## Education
```\eduEntry{<Start Year> - <End Year>}{<University Name>}{<Degree>}{<Thesis title>}```

## Experience

```
\expEntry{<Start Date> - <End Date>}{<Job Title>}{<Company>}{<Location>}
{
	\explist{ 
		item 1;
		%
		item 2;
		%
		item 3
	}
	
	\skills{item1, item2}
}
```

> [!TIP]
> Entries to \explist are divided by `;`. If you wish to separate them in your code, use `%` so it will not interrupt the command and remain readable.
> Do not add `;` at the end of the last entry

> [!TIP]
> In my opinion, including the skills used in a job here in your job entry is good practice.

## Research & Interests

```\interestslist{item1, item2, item3}```

> [!WARNING]
> Note that this list uses the `,` sign to separate items.

## Schools & Conferences

```\confEntry{<Date>}{<Title>}{<Host>}```

## languages

```\languageEnry{<Language>}{<Profiecency>}```

> [!TIP]
> If you wish, you can use [https://europass.cedefop.europa.eu/resources/european-language-levels-cefr](https://europass.cedefop.europa.eu/resources/european-language-levels-cefr) chart.
> If you did that, use the following command.

```\selfAssessedEng{<Listening>}{<Reading>}{<Spoken Interaction>}{<Spoken Production>}{<Writing>}```

## Skills

```\skills{item1, item2, item3}```

> [!WARNING]
> Note that this list uses the `,` sign to separate items.

## References

```\refEntry{(<Relation>)}{<Title & Name>}{<Associasion>}{<eMail>}{<Address>}```

> [!TIP]
> Try not to include your references occasionally. You can say **Available on request** in this section. Moreover, I suggest separating your references in another file.

## PDF Metadata
> [!CAUTION]
> Don't forget to edit lines 29, 30, and 31 in the `simplecv.sty` file. You shall see the following content.

``` 
 \usepackage[
	bookmarks, 
	colorlinks, 
	breaklinks, 
	% ---- FILL IN HERE THE TITLE AND AUTHOR
	pdftitle={Sajed Zarinpour - vita},
	pdfauthor={Sajed Zarinpour},
	pdfproducer={https://github.com/sajed-zarrinpour}
 ]{hyperref}
```
