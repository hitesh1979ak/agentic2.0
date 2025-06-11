# Create New Python Environment

conda create -n agentic_2_base python=3.11

# Activate the newly created enviornment

conda env list # (make sure its base)
conda activate name of the envionment
conta activate agentic_2_base

# Create New folder
conda create -p abcd001 python=3.6
conda env list # empty one
conda activate PATH (provide path of the new envionrment)
conda create -p abcd002 c:\hk\abcd002 python=3.11

# Install requirements

Pip install -r requirements.txt

Pip freeze
Pip freeze > requirements.txt

Pip list
Pip list > list.txt




