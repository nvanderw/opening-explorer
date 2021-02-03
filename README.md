# Opening Explorer

To get started using Python3, run:

    python -m venv .venv
    .venv\Scripts\Activate.ps1 # Assuming powershell
    pip install -r requirements.txt

This will install all the dependencies. Running the program once will generate the settings.json file:

    python -m opex

Alternatively, edit `settings.json.default` and rename to `settings.json`. Point that file at your UCI engine, and run again to generate `output_directory/<nickname>.uci`, which will contain default engine settings.