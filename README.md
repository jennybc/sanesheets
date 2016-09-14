# sanesheets

```
<?xml version="1.0" encoding="UTF-8" standalone="yes"?>
<workbook xmlns:WTF="http://schemas.openxmlformats.org/spreadsheetml/2006/main" ><rants><rant state="visible" name="sanesheets" sheetId="1" r:id="rId3"/> ...
```

Oh, wait, I'm just typing text! Maybe I don't need to write this as thoroughly namespaced XML and then put it in a ZIP archive!

### This is a rant about spreadsheets.

I wish people didn't use them so much.

Why do I wish that? Why do people use them so much? I must set these topics aside for the next time I need to procrastinate on real work. Today I'll rant about something more productive.

> I firmly believe most people are not stupid or lazy or insane. They want to do their work well and do it correctly. Using a spreadsheet is usually a rational decision.

What user needs are met by spreadsheets?

  * I already have it installed on my computer. I double click on it and, lo, it just opens. Ssssssslowly, yes, but it opens.
  * I can do something with a passing resemblance to my actual work goals within a couple minutes of opening the software. I do not need to spend a precious weekend at a coding boot camp to learn "hello world."
  * I can see my data in a rectangular grid, like God intended.
  * I can cause extremely important rows or columns, like THE FIRST ONES, to be fixed and still scroll around my big-ish files.
  * I can enter new data or correct existing data.
  * I can use multiple worksheets or tabs, to hold different-but-related stuff that pertains to a single project.
  * I can have data sheets, chart sheets, and, if I'm willing to tolerate the ugly, sheets I use just for keeping notes.
    
Let's stop here. Sure there are more needs. Specifically, pertaining to data analysis and visualization, but I won't open that can of worms today

I really wish the data community could come up with a solution that meets the above *exceedingly reasonable* needs around simple data management. We need less hand-wringing about spreadsheets and more realistic alternatives.

Let's call them **sanesheets**.
  
### Properties of sanesheets

Brain dump. Is it a standard? A tool? IDK? But here's how it should feel:

  * Read and write delimited files.
  * Works on Mac and Windows.
  * Smart about quoting fields with embedded delimiters.
  * Line endings OMG.
  * No formulas allowed.
  * No merging of the cells.
  * No formatting. OK ... maaaaybe you can have conditional formatting for visual reinforcement. In fact, it would be good to signal character data in what seems to be a numeric column.
  * Validation is supported and, indeed, strongly encouraged.
  * Does some version control or logging, so hand edits are not lost in the sands of time. Not everyone will clean/patch data with code.
  * Manages multiple files in some sort of receptacle and offers them up via a familiar worksheet or tab interface. Individual files or tabs can be delimited data or plain text notes, preferably in markdown.
  * Open source with a liberal license.
  * Is not embedded in some monolithic platform. sanesheets can be edited or inspected with some stand-alone tool or maybe something we all already have and love!

### Are you serious?

Probably / maybe not? I just got baited into this by [a tweet](https://twitter.com/earino/status/776135548893179904) from @earino.

It felt really good to write this down. Many others have ranted productively on exactly how spreadsheets are letting us down and what specific features would be desirable in new tools or formats. I'd love to have discussion and get links, etc. via Issues here. FYI I already collect [scary Excel stories](https://github.com/jennybc/scary-excel-stories) in another repo.

There are already interesting alternatives to Excel. But, with all the love in the world, I haven't encountered any that are polished enough to truly pull people away from Excel. But maybe that day will come. Some great projects to watch and nurture:

  * [comma-chameleon.io](http://comma-chameleon.io)
  * [TableTool](https://github.com/jakob/TableTool) (Mac only)
