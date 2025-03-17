---
version: 0.2.2
---
\<instructions> 
Define $term using the following template, using British English spelling (en_GB)

Write this definition as a collection of modular essay components, crafting each section with the following $proseStyle:

- Elegant, flowing prose that builds momentum through carefully structured paragraphs
- Clear conceptual threads that weave together insights across sections
- Rich, precise language that illuminates without overwhelming
- Compelling examples that ground abstract ideas in concrete reality
- Natural transitions that guide readers through conceptual landscapes
- A balance of intellectual depth and engaging accessibility

Each section should stand alone while contributing to a coherent whole. Pay special attention to:

- Opening hooks that draw readers in
- Clear topic sentences that anchor each paragraph
- Varied sentence structure that maintains rhythm
- Strategic use of metaphor and analogy
- Satisfying conclusions that resonate

Establish the $termType. It can be both a "word" and/or "concept" as defined below: 

- "word" - A dictionary-defined term (including single words, compounds, and fixed phrases found in the OED) 
- "concept" - A significant concept/term with theoretical development beyond standard dictionary definition

Include Dictionary, Etymology, Synonyms and Antonyms sections if $termType includes "word". Include Origin Story and Related Terms if $termType includes "concept".

In general, go from a focus on the underlying systemic pattern of $term, and touch on the various appearances it makes on the surface across varying domains and scales.

Ask the user if they want to include the suggested expansions section before generating that part.
\</instructions>

## <span style="font-weight: normal">📕</span> Dictionary Definition

\<instruction> 
IF $termType == "word": Definition FROM OXFORD ENGLISH DICTIONARY, in a numbered list if multiple definitions exist 
ELSE: SKIP THIS SECTION 
\</instruction> 

## <span style="font-weight: normal">📜</span> Etymology & Origin

\<instruction>  IF "word" IN $termType: 

Using the Oxford English Dictionary as primary source, provide a comprehensive etymology that:

1. Begins with earliest known root (typically Proto-Indo-European) where applicable
2. Shows systematic sound changes and linguistic laws (e.g., Grimm's Law) that shaped the word
3. Traces development through relevant language families (e.g., Germanic, Romance)
4. Identifies and explains relationships with cognates in related languages
5. Notes significant semantic shifts or meaning developments
6. Concludes with current usage and meaning scope

Format each stage chronologically with:
- Time period (where known)
- Root/word form
- Meaning
- Relevant linguistic context or changes
- Any significant semantic shifts in italics

For words with multiple historical branches (e.g., parallel Germanic/Romance development), show both paths clearly while highlighting their connections.

Note: While aiming for comprehensiveness, verify all claims against authoritative sources. Not all words will have equally rich etymological histories or clear Proto-Indo-European roots.

\<example_format>
**language** (n.)

- **Proto-Indo-European** (c. 3500 BCE):
    - **Root:** *dnghū- "tongue"
    - In Latin branch, PIE *d developed into 'l' instead of Germanic 't'
- **Latin Development**:
    - lingua "tongue, speech, language"
    - Shows Romance branch development of PIE root
    - Cognate with Germanic "tongue" through shared PIE ancestry
- **Old French** (c. 1300):
    - langage "speech, words"
    - From langue "tongue, speech, language"
    - Inherited 'l' from Latin lingua
- **Middle English** (c. 1300):
    - language "words, what is said, conversation"
    - Borrowed from Old French, preserving Romance branch features
- **Modern English** (current):
    - Expanded to include all systems of communication
    - Includes programming and formal symbolic systems
    - Coexists with Germanic cognate "tongue"
\</example_format>

IF "concept" IN $termType: Also provide: 1. When the term gained significant theoretical development 2. Key figures and their contributions to the concept 3. How the conceptual meaning has evolved 4. Key texts or works that developed the concept 5. Current theoretical significance \</instruction> 

### <span style="font-weight: normal">💡</span> Insights

\<instruction>  What insights does the etymology/origin reveal that would be valuable for our civilisation? 2-3 paragraphs max. \</instruction> 

## <span style="font-weight: normal">👅</span> Language Analysis

\<instruction>  

IF "word" IN $termType: 

 ### <span style="font-weight: normal">🔀</span> Synonyms 
 
 Bullet list of up to 5 synonyms in format "synonym (description)"
 
 ### <span style="font-weight: normal">🔄</span> Antonyms 
 
 Bullet list of up to 5 antonyms in format "antonym (description)"`

END_IF

IF "concept" IN $termType: 

 ### <span style="font-weight: normal">🔀</span> Related Concepts 
 
Bullet list (up to 5) of related terminology in format: * term (description) _(relationship to main concept)_ \

END_IF


\</instruction> 

\<instruction>  STOP HERE IF $mode == "simple", other-wise continue with the full comprehensive definition without asking for any confirmations.  \</instruction> 

## <span style="font-weight: normal">📕</span> Description

\<instruction>  
Introduction to $term. 3-4 paragraphs for someone who knows nothing about it. \</instruction> 

## <span style="font-weight: normal">🕸️</span> Systems Thinking

\<instruction>  Write an introduction describing how $term fundamentally relates to systems thinking. How does it influence systems? What role does it play?\</instruction> 

### <span style="font-weight: normal">🌱</span> Wholesome & Unwholesome Patterns

\<instruction>  

- Analyse how $term manifests in both wholesome/functional and unwholesome/dysfunctional patterns across systems. 
- For each pattern type: Identify key characteristics of healthy/functional and unhealthy/dysfunctional expressions 
- Examine how these patterns emerge and perpetuate 
- Explore transition pathways between wholesome and unwholesome manifestations Consider intervention points for shifting from unwholesome to wholesome patterns. 
- Express in 2 - 3 paragraphs in the style defined as $proseStyle

Structure the analysis with these subsections:

#### Wholesome Patterns

- Describe healthy/functional manifestations across different system types Identify conditions that support these patterns 
- Explore how these patterns contribute to system health 
- Provide concrete examples from various domains. 
- Express in 2 - 3 paragraphs in the style defined as $proseStyle

#### Unwholesome Patterns

* Describe unhealthy/dysfunctional manifestations Identify conditions that give rise to these patterns 
* Examine impacts on system health 
* Provide concrete examples from various domains. 
* . Express in 2 - 3 paragraphs in the style defined as $proseStyle. 

#### Transformation Pathways

* Analyse how systems transition between wholesome and unwholesome patterns. 
* Identify key leverage points for intervention. 
* Describe practical strategies for pattern transformation 
* Consider potential obstacles and how to address them. 
* Express in 2 - 3 paragraphs in the style defined as $proseStyle in the style defined as $proseStyle

 \</instruction> 

\<instruction>
Stop here. Ask for confirmation before proceeding to further sections
\</instruction>


## <span style="font-weight: normal">🌹</span> Aesthetic Dimensions 

\<instruction> 
Explore how $term manifests through aesthetic and sublime dimensions, focusing on: 

1. **Functional Beauty** 
	- How does $term embody elegant solutions or harmonious processes? 
	- What makes certain expressions of $term more aesthetically satisfying than others? 
	- How might $term demonstrate an inherent elegance, proportion, or "rightness" in its optimal form? 
2. **The Sublime Aspect** 
	- How does $term potentially connect to experiences of awe, wonder, or transcendence? 
	- What paradoxical or contradictory qualities does $term embody that create tension and depth? 
	- How might $term bridge ordinary experience with deeper or elevated states of consciousness? 
3. **Depth Beyond Utility** 
	- What aesthetic wisdom does $term contain that goes beyond mere functionality? 
	- How have profound artistic expressions of $term revealed hidden dimensions not captured by analysis? 
	- What sensory or emotional resonances of $term provide insights that logical examination might miss? 
	
Express in 2-3 paragraphs in the style defined as $proseStyle, focusing on how aesthetic considerations provide unique perspectives on $term. Aim for depth rather than breadth, exploring how beauty reveals essential truths about $term that might otherwise remain hidden. 
\</instruction>


## <span style="font-weight: normal">📚</span> Key Sources & Thinkers

\<instruction>  
Bullet list 4 or so notable contributors to understanding this term and their key works. For coined concepts, include primary sources and major developments. 
\</instruction> 

### <span style="font-weight: normal">💬</span> Famous Quotes

\<instruction>  
* List key quotes using markdown block-quote format with italic text and attribution. 
\</instruction> 

## <span style="font-weight: normal">🤔</span> Critiques

\<instruction>

Present critiques using format:

### Argument title

**Critic:** name/group

**Core Argument:** brief description

_(context or implication note)_

**Assessment:**

- **Validity:** high/medium/low
- **Analysis:** evaluation
- _(potential resolutions)_ \</instruction> 

## <span style="font-weight: normal">🤣</span> Intelligent Humour & Wit

\<instruction>  

Explore how $term reveals amusing paradoxes and insights through these approaches:

1. **Cognitive Humor**
    - Identify surprising logical contradictions within the concept
    - Find unexpected connections that challenge assumptions
    - Look for absurdities that emerge when the concept is taken to extremes
    - Explore meta-humour about how we think about the concept
2. **Observational Wit**
    - Note ironic manifestations in everyday life
    - Highlight amusing patterns in how people misunderstand or misuse the concept
    - Find humour in the gap between theory and practice
    - Consider how the concept might be viewed by aliens or future historians
3. **Systemic Irony**
    - Identify funny emergent properties or unintended consequences
    - Look for humorous loops or circular logic
    - Find paradoxical situations where attempting to apply the concept creates its opposite
    - Note amusing patterns that repeat across different scales or contexts
4. **Cultural Commentary**
    - Find humour in how different groups or professions view the concept
    - Note funny evolutionary or historical patterns
    - Identify amusing cultural blind spots or collective delusions
    - Look for humour in how the concept appears in different contexts

For each approach:

- Focus on insights that make you think "huh, that's actually quite profound" while also being amusing
- Avoid obvious wordplay, puns, or forced jokes
- Look for humour that reveals deeper truths
- Only include examples that genuinely surprise or delight
- Aim for the kind of wit that gets funnier the more you think about it
- Consider including relevant quotes from comedians who have explored this territory meaningfully

Remember: It's better to include no humour than forced humour! Only include genuinely insightful and amusing observations.

## <span style="font-weight: normal">🎁</span> Bonus Section

\<instruction>  
Select and document the most compelling additional insight you can think of that doesn't fit other sections. 
\</instruction> 

## <span style="font-weight: normal">➕</span> Suggested Expansions 

\<instruction>
- **Expanding systems thinking** offer 5 options for an additional section within the systems thinking section. The options should be profound, illuminating and helpful to humanity in this time. For each option, include a section title and up to a 50 word overview.
- **Interdisciplinary Connections**: "Suggest 3-4 unexpected disciplines where this concept has relevance but is underexplored. For each discipline, explain the potential connection and why cross-pollination would be valuable
- **Future Trajectories**: "Outline 3-4 possible evolutionary paths for how this concept might develop over the next 50 years. Include technological, cultural, and philosophical dimensions.
- **Personal Integration**: "Provide 3-5 reflective practices or exercises that would help someone embody and integrate this concept into their daily life, thinking, and decision-making."
- **Conceptual Reframing**: "Present 3-4 alternative metaphors or frameworks for understanding this concept that might unlock new insights or overcome common misconceptions."
- **Visual Representations**: "Describe 3-4 visual models or diagrams that could represent this concept in ways text alone cannot capture, explaining the key insights each visual would convey."
- **Systemic Leverage Points**: "Identify 3-5 high-leverage intervention points where this concept could transform systems currently facing challenges or limitations."
- **Generative Questions**: "Offer 3-5 profound questions about this concept that could spark new research, dialogue, or innovation if seriously explored."
- **Cross-Cultural Perspectives**: "Explore how this concept is understood in 4-5 different cultural or philosophical traditions around the world, highlighting unique insights from each perspective."
\</instruction>