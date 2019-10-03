# qs_ext_rag_select
A KPI list of buttons in a customizeable text- and background-color (e.g. for Red/Amber/Green coloring). On click it selects that dimension and jumps to the next or any given sheet.

<a href="https://www.youtube.com/watch?v=dhQowB_Q9xU"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b8/YouTube_Logo_2017.svg/200px-YouTube_Logo_2017.svg.png" width="100"/> &nbsp;https://www.youtube.com/watch?v=Z0_NTnZG0q4

 * The Dimension is used for the title in the buttons
 * The 1st Measure is used to style the background-color of the buttons (if missing, it assumes #eee)
 * The 2nd Measure is used to style the text color of the buttons (if missing, it assumes #333)

You can add some more css styling in the extension settings, which goes into every button element.

The sheet setting can be 
 * empty: on click, it just selects but stays on current sheet
 * "next": on click it selects and goes to the next sheet
 * <any sheetid>: on click it selects and goes to that particular sheet

![alttext](https://github.com/ChristofSchwarz/pics/raw/master/rag_card.png "screenshot")

