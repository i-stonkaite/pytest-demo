# pytest-demo
Virtual environment:

To active virtual environment navigate to it's folder (~/venv/frameworkenv/bin) via terminal and once in type 'source activate'.
To deactivate VE use command 'deactivate' (in any repo).

Run marked tests (test suits):
single: pytest -m {mark}
multiple: pytest -m "{one_mark} or {other_mark}"
Note - giving a class a marker will give that marker to every method underneath that class. Markers are documented in "pytest.ini" file.