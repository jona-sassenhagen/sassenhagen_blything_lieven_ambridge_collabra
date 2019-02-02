# Analysis code for Sassenhagen, Blything, Lieven & Ambridge (2018)

This documents the actual analysis for our Collabra paper. You can read and download it at: [www.collabra.org/articles/10.1525/collabra.87](https://www.collabra.org/articles/10.1525/collabra.87).

In this paper, we discuss an experiment on brain data recorded while humans read sentences with syntactic errors and common vs. infrequent verbs. Analysing the brain data (EEG), we find different responses to errors for common vs. infrequent verbs.

The Jupyter Notebook plus the epoch files are sufficient to reproduce the analyses in the paper. If you have Conda installed, the only dependency is [MNE-Python](https://github.com/mne-tools/mne-python).




## Frequency Sensitivity of Neural Responses to English Verb Argument Structure Violations
Jona Sassenhagen, Ryan Blything, Elena Lieven, Ben Ambridge

### Abstract

How are verb-argument structure preferences acquired? Children typically receive very little negative evidence, raising the question of how they come to understand the restrictions on grammatical constructions. Statistical learning theories propose stochastic patterns in the input contain sufficient clues. For example, if a verb is very common, but never observed in transitive constructions, this would indicate that transitive usage of that verb is illegal. Ambridge et al.(2008) have shown that in offline grammaticality judgements of intransitive verbs used in transitive constructions, low-frequency verbs elicit higher acceptability ratings than high-frequency verbs, as predicted if relative frequency is a cue during statistical learning. Here, we investigate if the same pattern also emerges in on-line processing of English sentences. EEG was recorded while healthy adults listened to sentences featuring transitive uses of semantically matched verb pairs of differing frequencies. We replicate the finding of higher acceptabilities of transitive uses of low-vs. high-frequency intransitive verbs. Event-Related Potentials indicate a similar result: early electrophysiological signals distinguish between misuse of high-vs low-frequency verbs. This indicates online processing shows a similar sensitivity to frequency as off-line judgements, consistent with a parser that reflects an original acquisition of grammatical constructions via statistical cues. However, the nature of the observed neural responses was not of the expected, or an easily interpretable, form, motivating further work into neural correlates of online processing of syntactic constructions.
