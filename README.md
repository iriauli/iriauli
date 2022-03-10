import panel as pn
from bokeh.resources import INLINE

SimpleTable = pn.panel("""
| ### Hi there 👋 | I'm Irakli |
| --------------- | ------------ |
| Junior Salesforce Developer at Sweeft Digital | ![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=iriauli&layout=compact) |

""")

SimpleTable.save('SimpleTable', resources=INLINE) 
