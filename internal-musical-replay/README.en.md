# Internal Musical Replay and Affective Drift: From R to R*

**Second Entry**  
Date: 2026-08-11

---

## 1. Core Idea

After listening to a piece of music, the human mind often continues to replay it involuntarily (involuntary musical imagery / earworms).

- Let **R** be the representation formed by the initial listening.
- Let **R\*** be the drifted representation that accumulates through repeated internal replay.

**R\* accumulates** as a normal process.

While knowledge learning is fundamentally driven by correction against a ground truth,  
music has no such correct answer. Instead, what occurs is:

- It did not elevate me as much as expected
- I noticed parts I do not like
- My understanding of the lyrics changed

These are mismatches with experience or shifts in mood.  
The central question is how the accumulated R\* changes the emotion score when the same piece is heard again.

---

## 2. What the Machine Version Aims to Do

Intentionally induce this internal replay process inside a machine.

- Take a once-learned R and run repeated internal rehearsal (“dream training”)
- Generate and accumulate a drifted representation R\*
- Observe how emotion prediction changes when R\* is fed back as input

This is not the knowledge-style iteration that moves toward a correct answer.  
It is an attempt to examine, through the machine’s internal dynamics,  
how experiential mismatch and mood change are reflected.

---

## 3. Relation to Existing Research

**Human side (INMI / earworms)**  
This phenomenon has been studied extensively. Frequency, duration, musical features, and relations to mood have been examined. Key researchers include Kelly Jakubowski and Lassi Liikkanen.

**Still thin areas**
- How internal replay causes representational drift (R → R\*)
- How that drift modulates affective response on re-listening
- Intentionally inducing and observing this process in a machine

Existing Music Emotion Recognition is largely one-shot prediction from acoustic features to emotion scores.  
Designs that deliberately shift representations through internal rehearsal and then examine changes in emotion prediction are almost absent.

---

## 4. Function of the Mechanism (Current Theories)

The function is not yet clear. Main hypotheses are:

1. **Memory consolidation**  
   Repetition as a reflection of the process that consolidates musical memory into long-term storage.

2. **Mood / emotion regulation**  
   The possibility that the mechanism helps maintain or adjust everyday mood.

3. **Epiphenomenon**  
   No special purpose; a natural byproduct of auditory memory systems.

The view that “in domains without a correct answer, such as music, the observational result of learning should be treated as emotional fluctuation”  
stands as a hypothesis that advances beyond existing frameworks.

The drift from R to R\* can be seen not as “correcting what was wrong,”  
but as a process of “re-processing the value and feel of this piece for the current self.”

---

## 5. Field Positioning

The intersection of music psychology (Musical Imagery × Music & Emotion)  
and research on spontaneous cognition / memory.  
If the machine side is pursued, it also steps into computational music cognition.

The distinctive point is not merely observing human INMI,  
but **intentionally inducing R → R\* drift inside a machine and examining the resulting change in emotion prediction**.

---

## 6. Open Questions

- On which dimensions (valence, arousal, semantic content, structural expectation) does R\* drift most strongly?
- Under what conditions does “amplification” switch to “correction”?
- What architecture, when given internal rehearsal, produces drift closest to the human phenomenon?
