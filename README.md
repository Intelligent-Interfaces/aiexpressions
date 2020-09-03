# ai-expressions
Mini-course on ai expressions: descriptions and examples.

## Introduction to ai expressions (aiE | AiE | AIE)
Before we start with the detailing of definitions, operations, tools, and the associated theoretical and computational machinery, it is essential to set out foundations. In Japanese "Ai" [/ay/] means love. And so, we start with **love**, always.

**ai expressions** is just a playful way for the self to make art generation less scary and enjoyable. Making digital art enjoyable and less scary does several things, _which we do not claim to know the scope of consequences of such things at this current point_, but perhaps the essential thing that it does is make interfacing with computational structures for art generation closer to the soul of the animal mind. 

---
## ai expressions for [`python`](https://www.python.org/download/releases/3.0/)
The `python` branch of the `ai-expressions` repo contains the translation and creation of the `ai expression` library (package) for the `python` programming language. 

### Example 1: [OpenAI](https://openai.com/)
We can use `ai expressions` to describe AI systems:

```python
# Spellbook for openai (openai.sb):
import synthesis.engine as se
import analysis.engine as ae
import application as app
import environment as env
import openai

# Describe core functions
resources.app() = [education, platforms, tools]
blog.se() = [first_entry, ..., recent_entry]
progress.se() = union(milestones, papers)

def about(message): 
	print(message)

# message = "OpenAI is an AI research and deployment company based in San Francisco,
# California. Our mission is to ensure that artificial general intelligence benefits all of
# humanity. The OpenAI Charter describes the principles that guide us as we execute on
# our mission.”

# Collect OpenAI prompt
message = openai.message()

# Start openai enviornment
openai.env() = [about(message), progress, resources, blog]
```

We can be increasingly specific about these components:

```python
# Understanding the openai resources (openai.res):
education.app() = [spinning_up]
app platforms = [microscope, gym, baselines]
app tools = [tool_1, ..., tool_n]

# Understanding spinning up (openai.spin):
def spinning_up (introduction, essay, curated_list, code_repo, excersises):
	openai.spinup.introduction(part_1, part_2, part_3)
	openai.spinup.essay()
	openai.spinup.code_repo(docs, spinup, test)
	openai.spinup.exercises(pset1, pset2) 
	
# Understanding openai platforms (openai.plat):
microscope.app() = []
gym.app() = []
baselines.app() = []

# Understanding microscope (openai.microscope):
microscope.app = []

# Understanding gym (openai.gym):
gym.app() = []

# Understanding baselines (openai.baselines):
baseline.app() = []

# Understanding openai tools (openai.tool):
tool_apps.app() = [tool_1, ..., tool_n]
tool_syn.se() = [tool_1, ..., tool_n]
tool_analy.ae() = [tool_1, ..., tool_n]
tool.app() = [tool_apps, tool_syn, tool_analy]

# Understanding tool_apps (openai.tool.apps):
tool_apps.app() = []

# Understanding tool_syn (openai.tool.syn):
tool_syn.se() = []

# Understanding tool_analy (openai.tool.analy):
tool_analy.ae() = []

# Understanding openai progress (openai.prog):
se milestones = [milestone_1, ..., milestone_n]
papers.se() = [paper_1, ..., paper_n]

# Understanding openai milestones (openai.mile): 
milestones.se() = []

# Understanding openai papers (openai.paper):
paper.se() = [] 
```
