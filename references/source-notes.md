# Source notes for research talk slides

These notes distill the supplied teaching material into presentation choices.

## Pages guide

*Presentation Structure Guide.pages* is a one-page outline. It calls for background and motivation; significance and impact; prior work, limitations, or missing functions; a research question in one sentence; and the input/output of a proposed tool or model. It also advises deliberate slide order and spoken transitions, knowing the question well, focusing on impact, presenting the high level first, adjusting to the audience, speaking at a measured pace with keyword emphasis, message-bearing slide titles, eye contact, figures, simplicity, and highlighted keywords.

## Teaching recording

*St Marys Rd.m4a* is about 63 minutes long. The opening explains why the first 6–8 slides of a full talk need to establish the question before technical details. The speaker distinguishes significance from impact and demonstrates a story that goes from a broad real-world problem through existing approaches and their limits to a focused question and the input/output of a computational tool.

Later sections stress that a talk is a chain of reasoning: one slide raises the issue answered by the next. The same research should be explained differently to biology and computer science audiences. The speaker recommends clear titles, a slower speaking pace, audible emphasis on key terms, eye contact, visuals that carry meaning, and less text. In the final Q&A, the speaker discusses identifying sources for figures and screenshots.

## Worked example 1: cancer immunotherapy (about 7–15 minutes)

The speaker begins with the promise of immune checkpoint treatment and explains its basic mechanism before introducing the practical problem: not every patient benefits. That creates a need to predict response and understand resistance. Existing biomarkers and measurements help but leave limitations in sample size, cost, prior candidate selection, or cell-type resolution. Widely available bulk expression data offers an opportunity, yet it mixes cell types. The speaker can now state a focused question and a tool concept: use bulk data as input to estimate patient-level, cell-type-specific expression as output.

The reusable move is to connect the human or scientific consequence to a specific information gap, then show why a readily available data source and a new method belong in the story.

## Worked example 2: enhancer activity (about 41–52 minutes)

The speaker first uses a simple mechanism diagram to explain enhancers and then published evidence to show why their activity matters clinically. The story turns to measurement: direct approaches can be difficult to apply across existing clinical cohorts. Bulk sequencing data may offer a practical route, and prior work suggests it contains relevant signal, but aggregate analysis can miss cell-type differences. That limitation leads to a one-sentence research goal with a clear data input and cell-type-resolved output.

The reusable move is to justify each transition with evidence: mechanism → consequence → measurement challenge → opportunity in existing data → remaining gap → research goal. A method comparison alone is a weak opening unless the audience understands why the missing resolution matters.

Around minute 55, the speaker suggests a reverse check: imagine a perfect version of the proposed model and ask what valuable question its output would answer. Use this to test whether the claimed impact follows from the actual input and output.

These notes were prepared from local automatic transcription; verify exact biomedical terms and quotations against the recording before using them as scientific claims.
