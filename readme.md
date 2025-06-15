# Create New Python Environment
conda create -p venv python==3.13

conda create -n agentic_2_base python=3.11
Conda activate venv/

# Activate the newly created enviornment

conda env list # (make sure its base)
conda activate name of the envionment
conta activate agentic_2_base

# Create New folder
conda create -p abcd001 python=3.6
conda env list # empty one
conda activate PATH (provide path of the new envionrment)
conda create -p abcd002 c:\hk\abcd002 python=3.11

conda env remove --prefix "C:\hk\agentic_ai_2_0\13-05-2025\abcd001"


# Install requirements

Pip install -r requirements.txt

Pip freeze
Pip freeze > requirements.txt

Pip list
Pip list > list.txt




