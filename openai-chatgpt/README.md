# Vega JSON code generated using OpenAI ChatGPT

Session 1:

*write Vega JSON code to draw a bar chart. Use dummy data, 10 categories, where each category is a fruit. Random values for each category. Make all bars blue, the largest one - red.*

Bugs in the generated code:
1) I had to add 2 new code rows to define chart view height and width
2) I had to fix identical bug in 2 code rows used to define axes X and Y. There were unsupported "type" property instead of required "orient" property.

Also "Make all bars blue, the largest one - red" was implemented by AI as a condition that compares category value with hardcoded largest value in the dataset.

I fixed the above problems manually as well as I was able to fix them in dialogue with ChatGPT.

*prompt - to be inserted*

Session 2:

*<Vega JSON code created in previous ChatGPT session>*
*Take this code and update it to add white spaces between the bars on the chart.*

*great. also add data labels on to of the bars and remove axis Y*

*value labels are no visible. verify text marks. something with the fill color?*

*make value labels red for the largest value and blue for all other values*

*add chart title*

*chart title covers the label above one of the bars. increase distance between the chart and the title*

*make blue and red colors lighter*
