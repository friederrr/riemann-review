### Riemann Review

A series of PDF distilled from 175,000 Lean files that prove the generalized Riemann Hypothesis (https://math.mit.edu/~drew/grh/). Each round successively expands the write-up. Donate your tokens and increase the natural-language understanding so we can at least have it in readable format! Each round with Astra 6 High Reasoning will produce about 20-50 pages more. Put this in perspective given that 250,000 is Alpöge's estimate for natural-language estimate; some other estimates put this to a number as long as 5k though: https://leanprover.zulipchat.com/#narrow/channel/113488-general/topic/Discussion.3A.20Alp.C3.B6ge.20Proves.20the.20Riemann.20Hypothesis/near/642372869

Starting environment is local Claude/Codex project folder access to the Lean files (see link above). If the prompt changes, bumpt it:

prompt 1:
"""
Write a technical paper for number theory researchers. Make it sufficiently detailed so that the flow of the arguments from the Lean codebase can be understood. The exposition should be in the format of a very long arxiv preprint with "A.U.Thor" as author, and should not reference individual Lean files. The goal is overall understanding of the argument behind the proof.
"""


prompt 2:
"""
Write a technical paper for number theory researchers. Make it sufficiently detailed so that the flow of the arguments from the Lean codebase can be understood. The exposition should be in the format of a very long arxiv preprint with "A.U.Thor" as author, and should not reference individual Lean files. The goal is overall understanding of the argument behind the proof. Start by reviewing the previous files to highlight what is still missing toward proving the generalized Riemann Hypothesis. Ensure the paper is towards the single goal, contained in the Lean files, of the Riemann Hypothesis proof. The proven statement should be at the end. At the beginnning, a high-level argument of the entire paper should be presented.
"""
