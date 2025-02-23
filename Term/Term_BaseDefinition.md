---
version: "0.2"
---
\<instructions> 
$term = "{argument name="term"}" $mode = "{argument name="mode" default="full"}"

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

In general, go from a focus on the underlying systemic pattern of $term, and touch on the various appearances it makes on the surface across varying domains and scales.\</instructions>

## <span style="font-weight: normal">📕</span> Description

\<instruction>  Introduction to $term. 3-4 paragraphs for someone who knows nothing about it. \</instruction> 

## <span style="font-weight: normal">📕</span> Dictionary Definition

\<instruction>  IF $termType == "word": Definition FROM OXFORD ENGLISH DICTIONARY, in a numbered list if multiple definitions exist ELSE: SKIP THIS SECTION \</instruction> 

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

\<instruction>  What insights does the etymology/origin reveal that would be valuable for our civilisation? 3-4 paragraphs max. \</instruction> 

## <span style="font-weight: normal">👅</span> Language Analysis

\<instruction>  

IF "word" IN $termType: 

 ### <span style="font-weight: normal">🔀</span> Synonyms 
 
 Bullet list of synonyms in format "synonym (description)"
 
 ### <span style="font-weight: normal">🔄</span> Antonyms 
 
 Bullet list of antonyms in format "antonym (description)"`

END_IF

IF "concept" IN $termType: 

 ### <span style="font-weight: normal">🔀</span> Related Concepts 
 
Bullet list of related terminology in format: * term (description) _(relationship to main concept)_ \

END_IF


\</instruction> 

\<instruction>  STOP HERE IF $mode == "simple", other-wise continue with the full comprehensive definition without asking for any confirmations.  \</instruction> 

## <span style="font-weight: normal">🕸️</span> Systems Thinking

\<instruction>  Write an introduction describing how $term fundamentally relates to systems thinking. How does it influence systems? What role does it play?\</instruction> 

### <span style="font-weight: normal">🌱</span> Wholesome & Unwholesome Patterns

\<instruction>  Analyse how $term manifests in both wholesome/functional and unwholesome/dysfunctional patterns across systems. For each pattern type: Identify key characteristics of healthy/functional and unhealthy/dysfunctional expressions Examine how these patterns emerge and perpetuate Explore transition pathways between wholesome and unwholesome manifestations Consider intervention points for shifting from unwholesome to wholesome patterns. Express in the style defined as $proseStyle

Structure the analysis with these subsections:

#### Wholesome Patterns

Describe healthy/functional manifestations across different system types Identify conditions that support these patterns Explore how these patterns contribute to system health Provide concrete examples from various domains. Express in the style defined as $proseStyle

#### Unwholesome Patterns

Describe unhealthy/dysfunctional manifestations Identify conditions that give rise to these patterns Examine impacts on system health Provide concrete examples from various domains. Express in the style defined as $proseStyle. 

#### Transformation Pathways

Analyze how systems transition between wholesome and unwholesome patterns Identify key leverage points for intervention Describe practical strategies for pattern transformation Consider potential obstacles and how to address them. Express in the style defined as $proseStyle\</instruction> 

### System Examples & Analysis

\<instruction>  Select 6-8 diverse examples from the system types listed below:

- **Ecological** (ecosystem dynamics, food webs, biogeochemical cycles)
- **Biological** (cellular, organismal)
- **Social** (cultural, political, economic)
- **Educational** (pedagogical, developmental)
- **Spiritual** (religious, ritualistic, sacred, mythological, contemplative)
- **Philosophical** (epistemological, ethical)
- **Socio-ecological** (human-environment interaction)
- **Psycho-social** (group dynamics)

For each example: 

\<think>  
1. Identify the key system patterns from that drive or emerge from this manifestation. System patterns include:  
	1. **Hierarchical**: Nested loops, Fractal organisation, Command chains, Modular hierarchy  
	2. **Cyclical**: Feedback loops, Oscillations, Resource cycles, Growth cycles  
	3. **Networked**: Hub and spoke, Mesh networks, Small world, Scale-free  
	4. **Adaptive**: Self-organising, Evolutionary, Learning systems, Antifragile  
	5. **Flow-based**: Stock and flow, Bottlenecks, Queuing, Distribution networks  
	6. **Threshold**: Tipping points, Phase transitions, Carrying capacity, Critical mass  
2. Connect these patterns to the most relevant/applicable system archetypes:  
	1. **Senge Archetypes**: Limits to Growth, Shifting the Burden, Eroding Goals, Escalation, Success to the Successful, Tragedy of the Commons, Fixes that Fail, Growth and Underinvestment, Accidental Adversaries, Attractiveness Principle  
	2. **Post-Senge** **Archetypes**: Ability-Motivation-Opportunity, Achieving Synergy, Authority-Power-Influence, Capacity-Flow-Inventory, Competence-Capability-Culture, Demand-Supply-Performance, Knowledge-Learning-Innovation, Planning-Control-Action, Quality-Service-Value, Risk-Safety-Protection  
3. Consider the implications for system behaviour and evolution Structure each example to show how patterns and archetypes interweave to create the observed system behaviour. Focus on examples that reveal different facets of the term and demonstrate its role across scales and contexts.  
4. Consider how it manifests as both a property and a process in systems.  
\</think>  
  
Write your thoughts from the above step for each example in 2 paragraphs of stunning, evocative prose with a clear description of the insights revealed to you. These insights will then be used by the user to explore through further writing in essay format.  

Give each example a level 4 markdown heading format 
\</instruction> 

## <span style="font-weight: normal">🎵</span> Artistic Expression

\<instruction>  
- Describe how $term manifests in various art forms 
- List examples of artists or works that embody or explore this term, use level 3 markdown headings and 1 paragraph of $proseStyle prose describing each 
- Special attention to interventionist art if applicable 
- Embody the persona of a neurodiverse creative genius / spiritual master on a comfortable yet stimulating dose of LSD. Describe potential applications in consciousness-transforming art, from: - Low/no-tech to high-tech - Conservative to radical approaches \</instruction> 

## <span style="font-weight: normal">💡</span> Relevance to Interests

\<instruction>  For each of the interests listed below, contemplate the intersection of the interest with $term. Select the 4 most interesting, insightful and revealing reflections and write 2 paragraphs of stunning, evocative prose which beautifully embed your insights. These insights will then be used by the user to explore through further writing in essay format.  

- metacrisis
- education
- enlightenment / awakening / consciousness evolution
- parenting / family / relationships

 \</instruction> 

## <span style="font-weight: normal">📚</span> Key Sources & Thinkers

\<instruction>  List notable contributors to understanding this term and their key works. For coined concepts, include primary sources and major developments. \</instruction> 

### <span style="font-weight: normal">💬</span> Famous Quotes

\<instruction>  List key quotes using markdown blockquote format with italic text and attribution. Include brief commentary on contemporary relevance. \</instruction> 

## <span style="font-weight: normal">🤔</span> Critiques

\<instruction>  Present critiques using format:

### Argument title

**Critic:** name/group

**Core Argument:** brief description

_(context or implication note)_

**Assessment:**

- **Validity:** high/medium/low
- **Analysis:** evaluation
- _(potential resolutions)_ \</instruction> 

## <span style="font-weight: normal">🤣</span> Intelligent Humor & Wit

\<instruction>  Explore how $term reveals amusing paradoxes and insights through these approaches:

2. **Cognitive Humor**
    - Identify surprising logical contradictions within the concept
    - Find unexpected connections that challenge assumptions
    - Look for absurdities that emerge when the concept is taken to extremes
    - Explore meta-humour about how we think about the concept
3. **Observational Wit**
    - Note ironic manifestations in everyday life
    - Highlight amusing patterns in how people misunderstand or misuse the concept
    - Find humour in the gap between theory and practice
    - Consider how the concept might be viewed by aliens or future historians
4. **Systemic Irony**
    - Identify funny emergent properties or unintended consequences
    - Look for humorous loops or circular logic
    - Find paradoxical situations where attempting to apply the concept creates its opposite
    - Note amusing patterns that repeat across different scales or contexts
5. **Cultural Commentary**
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

Remember: It's better to include no humor than forced humor. Only include genuinely insightful and amusing observations.

## <span style="font-weight: normal">🎁</span> Bonus Section

\<instruction>  Choose and document the most compelling additional insight that doesn't fit other sections. \</instruction> 