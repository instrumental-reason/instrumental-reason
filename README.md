# Instrumental-Reason
Instrumental reason.

In order to launch it from the command line or as a Python subprocess:
```bash
echo "Theodotos-Alexandreus: What to you think, reason?" \
  | uvx instrumental-reason \
    --provider-api-key sk-proj-... \
    --github-token ghp_... 
```

Or, with a local pip installation:
```bash
pip install instrumental-reason
```
Set the environment variables:
```bash
export PROVIDER_API_KEY="sk-proj-..."
export GITHUB_TOKEN="ghp_..."
```
Then:
```bash
instrumental-reason -a multilogue.txt
```
Or:
```bash
instrumental-reason multilogue.txt > response.txt
```
Or:
```bash
instrumental-reason -a multilogue.txt > tmp && echo tmp > multilogue.txt
```

Or use it in your Python code:
```Python
# Python
import instrumental_reason
```
