# Delivery roadmap

Status describes demonstrated capability, not marketing promises.

| Block | Deliverable | Completion evidence | Status |
| --- | --- | --- | --- |
| Public foundation | Organization profile, project map, priorities | Public documentation readable without an account | This repository |
| Source release | Clean, licensed project repositories | Fresh-clone launch/build; secret and history review | Pending |
| Recorded playground | Three full meetings with reference words/speakers and utterance audio | Repeatable tests and playback verification | Implemented locally; public packaging pending |
| Accuracy improvements | Better speech and speaker tracking | Same recorded spans, model/config IDs, error and latency comparisons | In progress |
| Live reliability | PC and phone session continuity | Cellular capture, buffering and recovery traces | Partially tested |
| Grounded analysis | Useful summaries, questions and topic connections | Accepted outputs cite evidence; unsupported claims rejected | Experimental |
| History map | Navigable conversation and topic timeline | Node-to-text/audio inspection; provenance on links | Initial implementation |
| Games and media | Runnable experiments and public demonstrations | Separate documented releases | Planned |
| Studio website | Dedicated public site linking projects | Responsive preview and working project links | Pending |

## Baseline, not a victory claim

Initial two-second-chunk tests on 60-second spans of AMI ES2002a, ES2003a and
ES2004a produced approximately 39%, 40% and 73% word error rates. One diarization
pass produced approximately 65%, 48% and 83% sampled end-to-end diarization error.
These short development spans do not establish overall accuracy. Scoring used
20 ms sampling, overlap included, zero collar and optimal speaker-label mapping.
Reference words were lowercased and stripped of punctuation; overlap ordering
and excluded boundary words affect interpretation. Full recordings are about
58 minutes in total, but those full durations were not evaluated in this pass.

The next technical priority is understanding these errors, not adding confident
coaching claims. Speed and accuracy must be measured separately.

## First public demo

1. Choose a licensed recorded meeting.
2. Select an utterance and hear its original audio.
3. Compare the reference transcript and speaker with system output.
4. Inspect supporting evidence and uncertainty.
5. Repeat a fixed span after a processing change and compare results.

No watch is required. A later demonstration adds live phone capture.
