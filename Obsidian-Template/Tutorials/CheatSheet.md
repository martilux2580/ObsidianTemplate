%%   
<!-- <span class="c">![[xdd.png]]  <br> elpepe</span> -->    
		for centering images and the kinda caption below.
%%

%% 
<!-- <div style="page-break-after: always;"></div> --> 
		for inserting a page break and adding a new blank page.
%%

%%Remove markdown and html comments for getting the actual code of the previous HTML commands.%%
# Cheatsheet for Obsidian and Markdown
### Cheatsheet for Obsidian and Markdown

### Cheatsheet for Obsidian and Markdown

Paragraph1 with line between.

Paragraph2.

multiple &nbsp;&nbsp;&nbsp; blank spaces and <br> for  new lines.

Ctrl+Shift+V for pasting everything so that it doesnt appear under backticks.

---
(three hyphens or asterisks at least for a horizontal divider line)
**bold text** or __bold text__ 
*italic text* or _italic text_ 
***blod and italic text*** or ___bold and italic text___
~~striked out text by hitting altgr and 4~~
**bold with *italic* inside**
==Highlighted text==
<u>Underlined text with html, markdown doesnt have this as it is confusing with hyperlinks</u>

```js
function isEven(n) { 
    return (n % 2 == 0); 
} 
```

3 backticks \` to show code, colors of code will be shown if we put the language after initial backticks. Languages [supported](https://github.com/jincheng9/markdown_supported_languages#heres-a-full-list-of-supported-languages) by markdown are these (nearly each popular one nowadays)...



"Quotes" seem to 'work' well on Obsidian...

[Obsidian Help](https://help.obsidian.md) links with the text between square brackets [] and the link after between parenthesis (). Escape whitespaces in links substituting them with ```%20```.

Images from webpages with ![Engelbart|100x145](https://history-computer.com/ModernComputer/Basis/images/Engelbart.jpg) ending exclamation marks followed by the text in case image doesn't render in between square brackets and the link after between parenthesis. Can set the size of it.

You can just take a screenshot of something and paste it here ![[Image1.png|200x200]] and the image will be saved in the Imagess folder as it has been set  in Obsidian as the Attachment Folder, can change it in Obsidian Settings. Also can set the size of it....

<span class="center">![[Image1.png|250x250]]  <br> Kinda Caption for Image1</span>
<span class="right">![Engelbart|100x145](https://history-computer.com/ModernComputer/Basis/images/Engelbart.jpg)  <br> Kinda Caption for Image2, which is right aligned....</span>

1. Element 1
2. Element 2.
	1. Element 2.1
		1. Element 2.1.1
			1. Element 2.1.1.1
				1. Element 2.1.1.1.1

- Bulleted 1
	- Bulleted 1.1
		- Bulleted 1.1.1
			- Bulleted 1.1.1.1

- [ ] This is an unchecked task.
- [x] Checked task, striked out.
- [a] Checkboxes aren't editable in PDF.

Commenting code in markdown is wrapped between double percentages \%\%. Escaped with \\.


Tables like these....

Col1 | Col2
-- | --
Row1 | Row1
Row2 | Row2

Alignments inside it like these

Left text | Centered text | Right text
:-- | :--: | --:
Row1 | Row1 | Row1

Possibility to add diagrams and math formulas, last ones with LaTeX support, wont explain it as I think I wont use them much....

Help for [simple Markdown formatting](https://help.obsidian.md/Editing+and+formatting/Basic+formatting+syntax) as well as [advanced Markdown formatting](https://help.obsidian.md/Editing+and+formatting/Advanced+formatting+syntax) by clicking the following links.

Help about [Obsidian and more Markdown](https://help.obsidian.md) by clicking the following [links](https://github.com/obsidianmd/obsidian-help).


line before inserting the page break command (line 108).
<div style="page-break-after: always;"></div>
line after inserting the page break command (line 110) (in Obsidian goes from 108 to 110, skips 109).

Xtra Stuff:
- HTML code in Obsidian will hide (for example centering an image....first comment of this ) the code and sometimes the line of code (like page breaks). For showing it up, just select the previous, actual and next row with the mouse and the code or command should appear, same with some other Markdown comments.
- Margins in Markdown sometimes don't work aesthetically correctly, none and minimal margins specially. Default Obsidian margin seems good.
- For gitignore for Obsidian Vaults just ignore the workspace.json in the .obsidian folder of your vault. Rest should be OK.
- When closing Obsidian, you should close your Vault by clicking the button at the bottom left corner to Open Another Vault and then closing the window of your working Vault. That way when you open up Obsidian again, it wont automatically open your last opened Vault, it will pop you up with the select or create vault window.
- Vault settings come back to default for new vaults created. Those settings are saved in the .obsidian folder.
- Community plugins will be saved in plugins folder inside .obsidian folder.
- Need to set up the Attachment Folder by creating the folder in the Obsidian Vault and right click on it and select the option for that (already done here, it is Resourcess as every screenshot, audio or stuff will be saved auto there...).
- Needed the align.css snippet located in the snippets folder of the .obsidian folder to be able to center stuff. Make sure it is loaded in the settings of Obsidian (already done here).
- Left Ctrl+Shift (just below Enter button) + E to export as PDF, hotkey.
- Cannot impede Obsidian from popping up your default PDF reader once exported, even though it has a default PDF reader....
- [Creating a template repository](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-template-repository) and [creating a repository from a template](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template) tutorials should come in handy...
- Spaces and whether upper or lower case and that stuff is important in Markdown.
- Better using open source community plugins...for security reasons.
- Not sure if you can create a good index or table of contents in Markdown....I guess I can live without knowing that....
- Use the name of the note file between two square brackets for referencing a new note. A new connection in the Graph view will appear.


With everything said, now you are ready for taking notes using Obsidian. Go to the [[InitialFile]] and start :)



































