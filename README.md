# Jev diffusion experiments

Can a smart coach help a picture-making machine find a better way to draw? These seven notebooks follow that question, from early experiments to checks of what went wrong.

Each notebook has its own short ELI5 guide:

- [The first steering experiment](Closed_Loop_Diffusion_Experiment.README.md) — [notebook](Closed_Loop_Diffusion_Experiment.ipynb)
- [Can a coach steer the hand-drawing machine?](Jev_Attention_Downsampling_Hands.README.md) — [notebook](Jev_Attention_Downsampling_Hands.ipynb)
- [Does Jev follow the facts or the labels?](Jev_Checkpoint_Decision_Benchmark.README.md) — [notebook](Jev_Checkpoint_Decision_Benchmark.ipynb)
- [Try four knobs and watch what moves](Hands_Four_Methods_Computation_Dry_Run.README.md) — [notebook](Hands_Four_Methods_Computation_Dry_Run.ipynb)
- [Which little moves shaped the final picture?](Hands_Step_Vector_Attribution_Across_Seeds.README.md) — [notebook](Hands_Step_Vector_Attribution_Across_Seeds.ipynb)
- [Give the coach a memory and a picture reviewer](Hands_Jev_World_Knowledge_Feedback.README.md) — [notebook](Hands_Jev_World_Knowledge_Feedback.ipynb)
- [Fix the coach's notebook, then test the referee](Hands_Jev_Feedback_Repairs_Pilot.README.md) — [notebook](Hands_Jev_Feedback_Repairs_Pilot.ipynb)

The important finding so far: making a picture different is easier than proving it is better. The later runs kept the ordinary drawing route, so their final pictures are not evidence that Jev fixed the hands.

These are copies of a working research diary. Saved cell outputs, private keys, downloaded models, and bulky run folders are left out. Some notebooks borrow tools and saved work from earlier ones, so this is not a one-click demo. The full original experiments remain on the research machine.
