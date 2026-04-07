This is the DTU Python Installation Support Workshop repo.

The documents will contain everything to do with our workshops, which will help students
with Computational Thinking.

Please add guides to the correct folder and materials under the material folders.

## Contributions

Since this repo will contain notebooks, we have to maintain a sustainable platform
that does not introduce too much complexity when doing merges and developments
of the material.

To easily bypass the problems related to merge-conflicts of notebooks we rely on
`pre-commit` which cleans the notebooks upon commit.

So, before you do your work, ensure you have done this:

1. Clone the repository to your local machine (however you wish)

2. Enable the pre-commit hooks in the repository:

   ```bash
   cd pythonsupport-workshops
   python3 -m pip install pre-commit
   pre-commit install
   ```
   This will install some details and needs only to be done
   once.
