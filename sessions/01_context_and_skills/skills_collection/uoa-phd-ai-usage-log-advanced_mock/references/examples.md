# Examples

Completed entries, filled in by the user. Match their level of detail. Each one covers a different kind of use: code, statistics, writing, figures, modelling, ideas, and explanation only.

## Computational neuroscience: code

```
20-22/10/2026 - Used Claude Opus 5.5 to implement analysis scripts examining stability between experts across layers. This was done by deriving dissimilarity matrices between experts within and between models, and doing the same at the gating level. Conceptualised in the meeting with the supervisor; brainstormed by self before prompting. Code and outputs manually inspected; maths suggested by Claude double-checked; scripts refined across multiple iterations.
```

## Psychology: statistics

```
03/11/2026 - Used Claude Opus 5.5 to generate R code for analysing reaction times in a Stroop-style attentional bias task. This was done by fitting a linear mixed-effects model with lme4 on log-transformed RTs, with condition as a fixed effect and random intercepts and slopes for participants and items, then comparing models with likelihood-ratio tests. Conceptualised from the preregistered analysis plan written by self and approved by the supervisor. Model specification checked against the preregistration; convergence warnings and residual plots inspected by self; final model simplified by self after singular fit.
```

## Psychology: writing

```
07/11/2026 - Used Claude Sonnet 5.5 to modify the wording of the Discussion section of a manuscript on emotion regulation and rumination; no new arguments or citations were generated. This was done by asking for edits that improve clarity, shorten long sentences and point out unclear transitions on text drafted by self. Arguments and structure conceptualised by self and discussed with co-authors. Every suggested edit reviewed individually, with about half rejected; all claims and citations checked against the original sources by self.
```

## Cognitive neuroscience: EEG pipeline

```
12/09/2026 - Used Claude Opus 5.5 to generate an MNE-Python preprocessing pipeline for 64-channel EEG data from an oddball paradigm. This was done by band-pass filtering, re-referencing to the average, removing ocular artefacts with ICA, epoching around stimulus onset and extracting P300 amplitudes in a 250-500 ms window over parietal electrodes. Conceptualised from the lab's standard preprocessing protocol and discussed with the lab's postdoc. ICA components selected manually by self from topographies and time courses; ERPs compared against the lab's previous pipeline on two pilot participants.
```

## Cognitive neuroscience: figures

```
18/09/2026 - Used Claude Opus 5.5 to generate matplotlib code for the manuscript figure showing representational dissimilarity matrices from ventral visual cortex ROIs. This was done by plotting RDMs as heatmaps ordered by category, adding an MDS embedding panel and a bar plot of model-to-brain Spearman correlations with bootstrapped confidence intervals. Figure layout conceptualised by self from a hand sketch agreed with the supervisor. Plotted values checked against the saved analysis outputs; colour scale and labels revised by self across several iterations.
```

## Cognitive science: computational modelling

```
25/08-02/09/2026 - Used Claude Opus 5.5 to implement and fit a drift diffusion model to choice and response-time data from a perceptual decision-making task. This was done by fitting drift rate, boundary separation and non-decision time per participant with PyDDM, letting drift vary with stimulus coherence, then running parameter recovery on simulated data. Model choice conceptualised by self from the literature and confirmed with the supervisor. Parameter recovery results inspected by self; fits compared with posterior predictive checks of RT quantiles; likelihood derivation checked by self against the original papers.
```

## Cognitive science: ideas and literature

```
14/10/2026 - Used Claude Sonnet 5.5 to brainstorm possible confounds and control conditions for an experiment on working-memory load and visual search; no text from the session was used in written work. This was done by describing the planned design and asking for alternative explanations of the predicted effect, such as differences in eye movements and in how difficult the conditions are, along with matching controls. Research question conceptualised by self in the PhD proposal. Suggestions treated as prompts only; each one checked against published studies found by self before two controls were added to the design.
```

## Explanation only

```
29/10/2026 - Used Claude Opus 5.5 only to explain concepts; no content was generated for the thesis. This was done by asking for an explanation of cluster-based permutation testing for time-series data and how it controls the family-wise error rate, followed by questions on choosing the cluster-forming threshold. Question arose from reading by self for the EEG analysis chapter. Understanding checked against Maris and Oostenveld 2007 and the FieldTrip documentation by self.
```