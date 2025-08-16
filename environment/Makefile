.PHONY: environment remove-env test

MODULE=mass-spec-prediction
ENVIRONMENT=mass-spec

environment: 
	conda env create -f environment.yml

remove-env:
	conda remove --name $(ENVIRONMENT) --all --yes

test:
	pytest -v