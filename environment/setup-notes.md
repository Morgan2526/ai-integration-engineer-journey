# Environment Setup Notes

## Machine
- OS: Windows 11
- Python version: Python 3.14.6
- Editor: Pycharm

## Tools Installed
- ✅ Python 3.14.6
- ✅ uv or Poetry
- ✅ Docker Desktop
- ✅ Git (configured with name & email)
- ✅ Local Postgres (Docker preferred)

## Commands Used for Setup
- Setup env


    cd ai-integration-engineer-journey
    py --version
    py -m venv env
    .\env\Scripts\activate
    #UV installation command
    powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"