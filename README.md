# FastAI Course
Repository for storing course materials and my own thoughts / projects as I complete the course. The question and answer pairs are compiled from various fastai forum users. All credit to original authors

## Development Environment
Start the container:
```
docker compose up -d
```

Attach to the container using vscode's dev container extension

```
micromamba activate venv
```

When finished developing, run:
```
docker compose down -v --rmi all
```