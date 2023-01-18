# dvc-project-template
DVC NLP project

## Reference repository
[official reference repo](https://github.com/iterative/example-get-started)

[my view](https://studio.iterative.ai/user/Rahul-Shedge/projects/DVC-NLP-Simple_Usecase-kjkavqmvtb)
## STEPS -



### STEP 01- Create a repository by using template repository

### STEP 02- Clone the new repository

### STEP 03- Create a conda environment after opening the repository in VSCODE

```bash
conda create --prefix ./env python=3.9 -y
```

```bash
conda activate ./env
```
OR
```bash
source activate ./env
```

### STEP 04- install the requirements
```bash
pip install -r requirements.txt
```

### STEP 05- initialize the dvc project
```bash
dvc init
```

### STEP 06- commit and push the changes to the remote repository