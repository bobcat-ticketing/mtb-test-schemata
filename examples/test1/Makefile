VALIDATOR=	python3 ../../scripts/schemacheck.py
SCHEMADIR=	../../schemata


check:
	$(VALIDATOR) --input geography.yaml $(SCHEMADIR)/geography.yaml
	$(VALIDATOR) --input tickets.yaml $(SCHEMADIR)/tickets.yaml
	$(VALIDATOR) --input validations.yaml $(SCHEMADIR)/validations.yaml
	$(VALIDATOR) --input ticklemacros.json $(SCHEMADIR)/ticklemacros.yaml
