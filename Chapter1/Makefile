.PHONY: clean environment tests lint format

clean:
	rm -rf ./chapter1

environment:
	python3 -m venv chapter1
	. chapter1/bin/activate
	pip install -r requirements.txt

tests:
	python -m pytest tests/

lint:
	pylint my_python_project

format:
	black my_python_project
