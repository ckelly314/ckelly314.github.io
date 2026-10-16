# Blog

Practical, step-by-step guides to scientific computing: high-performance computing (HPC) clusters, Jupyter, conda, git, and GPUs. They started as notes for my own lab work, so most examples use WHOI's Poseidon and Hydra clusters, but the workflows carry over to any SLURM cluster.

## Posts

**[Use the GPUs on Hydra](blog/use-the-gpus-on-hydra.md)** · *August 12, 2026*
: What a GPU is, when (and when not) to use one, and how to run a trained scikit-learn random forest on Hydra's GPU node with nvForest, scaling up to all four GPUs.

**[Getting started with Hydra 🐉](blog/getting-started-with-hydra.md)** · *June 10, 2026*
: Get an account, log in, set up passwordless SSH, build conda environments, and run Jupyter Notebooks on WHOI's new cluster.

**[IS announcement: Hydra, WHOI's new HPC cluster](blog/about-hydra.md)** · *June 4, 2026*
: A copy of WHOI Information Services' announcement of Hydra, with its hardware specs and migration details, for quick reference.

**[Basic version control and collaboration with git](blog/basic-git.md)** · *March 28, 2024*
: Clone a repository, work on branches, commit and push changes, and merge updates from collaborators.

**[Using Python on Poseidon](blog/poseidon-basics.md)** · *October 3, 2023*
: Log in, use SLURM to submit and monitor jobs, set up conda and pip environments, and sync files to the cluster.

**[Running Jupyter Notebooks remotely on Poseidon](blog/poseidon-jupyter.md)** · *October 2, 2023*
: Start a notebook on a compute node and open it in your local browser through an SSH tunnel, plus troubleshooting for busy ports.
