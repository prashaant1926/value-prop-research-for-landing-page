# Literature Review Automation

## Research Focus
Analysis of automated literature review systems and AI-powered research discovery tools, with emphasis on identifying fundamental assumptions that can be challenged.

## Key Assumption Categories

### A1: Search-Centric Assumption
**Current Assumption**: Better search algorithms are the primary need for literature discovery
**Evidence**: Most tools focus on query optimization, semantic search, and relevance ranking

**Potential Flip**: Researchers need **synthesis tools** that identify cross-paper assumption patterns, not just better search results

### A2: Individual Process Assumption  
**Current Assumption**: Literature review is primarily an individual, sequential process
**Evidence**: Tools designed for single-user workflows and linear paper processing

**Potential Flip**: Literature review should be a **collaborative assumption-mapping process** where teams systematically identify and test literature-level hypotheses

### A3: Manual Synthesis Assumption
**Current Assumption**: Quality synthesis requires human intellectual work that AI cannot meaningfully assist
**Evidence**: AI tools limited to summarization, organization, and citation management

**Potential Flip**: AI can identify **implicit assumption patterns** across papers that humans miss, enabling novel research directions

## Papers for Investigation

### High-Impact Venues to Search
- **Information Science**: Journal of Informetrics, Information Processing & Management
- **AI/ML Venues**: NeurIPS, ICML workshops on AI for Science
- **HCI Venues**: CHI, CSCW (for user studies of research tools)
- **Digital Libraries**: JCDL, Digital Library conferences

### Specific Paper Types to Find

#### 1. Systematic Review Automation
- Papers on automated systematic review protocols
- Machine learning approaches to literature categorization
- Tools for bias detection in literature selection

**Analysis Focus**: What assumptions do these make about the review process?

#### 2. Research Discovery Systems
- Semantic search systems for academic papers
- Recommendation systems for researchers
- Knowledge graph approaches to literature organization

**Analysis Focus**: Do these optimize for finding papers or for discovering insights?

#### 3. Research Synthesis Tools
- Tools for concept mapping across papers  
- Automated thematic analysis of literature
- Systems for identifying research gaps

**Analysis Focus**: How do these define "synthesis" and what assumptions underlie their approach?

## Research Questions for Each Paper

### 1. Problem Framing Analysis
- How does the paper frame the "literature review problem"?
- What aspects of literature review does it assume are most important to optimize?

### 2. Solution Philosophy
- Does the solution assume literature review is about **information gathering** or **insight generation**?
- What role does the tool assume humans vs. AI should play?

### 3. Evaluation Methodology
- How is "success" in literature review measured?
- Does evaluation focus on efficiency metrics or research impact metrics?

### 4. Assumption Discovery Potential
- Could this tool be modified to identify assumption patterns across papers?
- Does it have components that could support assumption-flipping workflows?

## Research Synthesis Framework

### Cross-Paper Pattern Analysis

#### Technical Patterns to Track
1. **Information Retrieval Focus**: Papers that primarily improve search and filtering
2. **Organization Focus**: Papers that help structure and categorize findings  
3. **Synthesis Focus**: Papers that attempt to generate new insights from literature

#### Assumption Patterns to Track
1. **Efficiency Assumptions**: Literature review is about processing more papers faster
2. **Comprehensiveness Assumptions**: Good review requires covering all relevant papers
3. **Individual Assumptions**: Literature review is primarily a solo intellectual activity

### Gap Identification Process

For each major assumption category (A1-A3):
1. **Current State**: Document how existing tools embody this assumption
2. **Flip Opportunity**: Describe what the inverted assumption would look like
3. **Technical Requirements**: What would be needed to build tools based on the flipped assumption
4. **Validation Methods**: How could we test whether the flip leads to better research outcomes

## Oslo Platform Design Implications

### Core Design Principle
**Instead of optimizing literature review for coverage and efficiency, optimize for assumption discovery and hypothesis generation**

### Specific Features Suggested
1. **Assumption Pattern Detection**: AI that identifies recurring assumptions across papers in a domain
2. **Collaborative Assumption Mapping**: Multi-researcher tools for mapping and challenging assumptions
3. **Flip Suggestion Engine**: AI that proposes research directions based on assumption inversions
4. **Impact Validation**: Tools to assess whether assumption-flips affect broad swaths of existing work

## Literature Collection Strategy

### Phase 1: Foundational Papers (5-7 papers)
- Seminal papers in automated literature review
- Papers that explicitly discuss assumptions in research processes
- High-impact papers on AI research assistance

### Phase 2: Technical Deep-Dive (10-12 papers)
- Papers with novel technical approaches to literature analysis
- Systems papers with extensive evaluation of research impact
- Papers that challenge existing paradigms in research tools

### Phase 3: Synthesis & Gap Analysis (8-10 papers)
- Recent papers that demonstrate assumption-challenging approaches
- Papers with implications for collaborative research platforms
- Evaluation studies of research synthesis methodologies

## Connection to Research Methodology

This literature analysis directly supports the research methodology from CLAUDE.md:
1. **Identify assumptions** implicit across the literature review automation field
2. **Propose flips** that challenge these assumptions systematically
3. **Validate impact** by showing how flips affect multiple existing research areas

**Target Outcome**: Literature review that demonstrates Oslo's approach represents a fundamental paradigm shift, not incremental improvement.