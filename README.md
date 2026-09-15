# Tharun Arety

**AI systems × engineering intelligence × computational geometry**

I build AI systems that turn ambiguous real-world inputs into **structured representations, executable actions, and validated outputs**. My current work focuses on multimodal engineering systems, agentic workflows, CAD/geometry, retrieval and tool use — grounded in a background in computational mechanics, composites, and optimization.

The recurring pattern across my work is:

```text
raw / multimodal inputs
        ↓
structured representation
        ↓
reasoning & planning
        ↓
tool / geometry execution
        ↓
validation, guardrails & feedback
```

---

## Featured work

### [Spec2CAD](https://github.com/Tharun-arety/Spec2CAD)
**Multimodal engineering intent → validated parametric CAD.**

Takes combinations of written requirements, sketches, and technical documents; extracts traceable evidence; builds an **Engineering Intent Graph**; compiles typed requirement predicates and CAD feature plans; generates parametric geometry; and validates the resulting B-Rep before release.

```text
Text / Sketch / Technical Docs
            ↓
     Evidence extraction
            ↓
   Engineering Intent Graph
            ↓
  Requirement Predicate IR
            ↓
      Feature planning
            ↓
     Parametric CAD
            ↓
 B-Rep / STEP validation
            ↓
   Repair / release gate
```

[Live demo](https://spec2cad.vercel.app) · [Repository](https://github.com/Tharun-arety/Spec2CAD)

---

### [Agentic Enterprise Tool](https://github.com/Tharun-arety/Agentic_Enterprise_Tool)
**Agentic interface over engineering ERP / PDM / QMS workflows.**

A multi-domain engineering system where a LangGraph router selects bounded domain agents for PDM, QMS, controlled knowledge, procurement, programs and related enterprise data. Reads are evidence-backed; writes become permission-aware proposals that require human approval before taking effect.

`FastAPI` · `PostgreSQL` · `pgvector` · `LangGraph` · `OpenAI SDK` · `MCP` · `Next.js`

---

### [Agent Architecture Model](https://github.com/Tharun-arety/Agent_Architecture_model)
**Tool-using engineering agents with explicit guardrails, retrieval grounding, and evaluation.**

A hand-built tool-calling loop over engineering knowledge and telemetry with deterministic input checks, schema + database-aware argument validation, calibrated retrieval thresholds, citation verification, bounded retries, and offline evals for routing, faithfulness, relevance, and guardrail specificity.

`TypeScript` · `OpenAI API` · `RAG` · `tool calling` · `guardrails` · `evaluation`

---

### [Fiber Patch Placement](https://github.com/Tharun-arety/Fiber_Patch_Placement)
**Differentiable structural optimization for composite design.**

Master's thesis work coupling finite-element analysis with PyTorch autograd so fiber-patch position and orientation become learnable variables. The optimization balances structural response with manufacturability and strength constraints rather than optimizing geometry in isolation.

`PyTorch` · `torch-FEM` · `pygmsh` · `differentiable optimization` · `composites`

---

## What I work on

**AI systems**  
Agent orchestration · tool calling · structured outputs · retrieval / grounding · multimodal pipelines · evaluation · guardrails · human-in-the-loop execution

**Engineering AI**  
Computational geometry · parametric CAD · engineering intent representation · geometric validation · differentiable simulation · constrained optimization

**Software systems**  
Python · TypeScript · FastAPI · React / Next.js · PostgreSQL · pgvector · APIs · MCP · workflow automation

---

## Background

I started in **mechanical and materials engineering**, working across composites, FEM, manufacturing, and optimization. That background still shapes how I build AI systems: make constraints explicit, preserve provenance, separate representations from execution, measure the real output, and refuse to treat a plausible model response as proof that a system worked.

M.Sc. Materials Science & Engineering — University of Augsburg  
B.Tech. Mechanical Engineering — NIT Agartala

---

### Current direction

I am especially interested in systems where AI has to do more than generate text — where it must **understand engineering evidence, operate tools, modify structured systems, generate geometry, and prove that the result satisfies the original intent**.
