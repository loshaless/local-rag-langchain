# Install dependencies

```bash
python -m venv myenv
```

On Windows:

```bash
myenv\Scripts\activate
```

On macOS and Linux:

```bash
source myenv/bin/activate
pip install -r requirements.txt
```

# install ollama

you need to install ollama from https://ollama.com
then you need to pull mistral model

```bash
ollama pull mistral
ollama pull nomic-embed-text
```
